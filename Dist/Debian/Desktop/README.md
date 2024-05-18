Debian - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 7758

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H310M M.2 x.x               | [fc06be20c3](https://linux-hardware.org/?probe=fc06be20c3) | May 09, 2024 |
| Gigabyte      | Z97X-Gaming 5               | [8256dfc204](https://linux-hardware.org/?probe=8256dfc204) | May 08, 2024 |
| Dell          | 0M5DCD A00                  | [3c353c281f](https://linux-hardware.org/?probe=3c353c281f) | May 08, 2024 |
| ASUSTek       | PRIME A520M-K               | [5de84bcb38](https://linux-hardware.org/?probe=5de84bcb38) | May 08, 2024 |
| HP            | 89EB 11                     | [f53a08bd5c](https://linux-hardware.org/?probe=f53a08bd5c) | May 08, 2024 |
| ASUSTek       | PRIME X570-P                | [43cb45f5c4](https://linux-hardware.org/?probe=43cb45f5c4) | May 08, 2024 |
| Dell          | 0GN6JF A01                  | [b9877feccd](https://linux-hardware.org/?probe=b9877feccd) | May 08, 2024 |
| ASUSTek       | P8Z77-V LX                  | [b245c99221](https://linux-hardware.org/?probe=b245c99221) | May 07, 2024 |
| Unknown       | Unknown                     | [857bd41fc3](https://linux-hardware.org/?probe=857bd41fc3) | May 07, 2024 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | [e04c4654da](https://linux-hardware.org/?probe=e04c4654da) | May 07, 2024 |
| Sapphire      | PI-AM3RS760G2               | [7a48c1a73b](https://linux-hardware.org/?probe=7a48c1a73b) | May 07, 2024 |
| MSI           | B450-A PRO MAX              | [27adbf1266](https://linux-hardware.org/?probe=27adbf1266) | May 07, 2024 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [5a5f459292](https://linux-hardware.org/?probe=5a5f459292) | May 06, 2024 |
| ASUSTek       | PRIME A520M-K               | [602683adef](https://linux-hardware.org/?probe=602683adef) | May 06, 2024 |
| ASUSTek       | P9X79                       | [dd0d50c3bf](https://linux-hardware.org/?probe=dd0d50c3bf) | May 06, 2024 |
| Gigabyte      | H61M-S2PV                   | [cece4d3b5e](https://linux-hardware.org/?probe=cece4d3b5e) | May 06, 2024 |
| ASRock        | H310CM-HDV                  | [1312cfac28](https://linux-hardware.org/?probe=1312cfac28) | May 06, 2024 |
| Gigabyte      | H61M-S2PV                   | [98e922adae](https://linux-hardware.org/?probe=98e922adae) | May 06, 2024 |
| ASRock        | 990FX Extreme4              | [cb063ef0b2](https://linux-hardware.org/?probe=cb063ef0b2) | May 06, 2024 |
| Supermicro    | X9SCL/X9SCMA                | [bb7e4b6de6](https://linux-hardware.org/?probe=bb7e4b6de6) | May 06, 2024 |
| Foxconn       | PANGU-B 1A32N3500-600-G     | [e2c56e50f1](https://linux-hardware.org/?probe=e2c56e50f1) | May 05, 2024 |
| Gigabyte      | B85M-D3H                    | [1d637d8802](https://linux-hardware.org/?probe=1d637d8802) | May 05, 2024 |
| SZMZ          | X99 DUAL Z8                 | [24f362dbe8](https://linux-hardware.org/?probe=24f362dbe8) | May 05, 2024 |
| Gigabyte      | H610M K DDR4                | [da4e59e69d](https://linux-hardware.org/?probe=da4e59e69d) | May 05, 2024 |
| ASUSTek       | CM6870                      | [63591686d7](https://linux-hardware.org/?probe=63591686d7) | May 05, 2024 |
| ASUSTek       | CM6870                      | [6d828aab44](https://linux-hardware.org/?probe=6d828aab44) | May 05, 2024 |
| MSI           | H110M ECO                   | [2c97e6ca20](https://linux-hardware.org/?probe=2c97e6ca20) | May 05, 2024 |
| ASRock        | B450M Pro4                  | [b1caabc9b5](https://linux-hardware.org/?probe=b1caabc9b5) | May 05, 2024 |
| ASRock        | B650 PG Lightning           | [d0b08c1666](https://linux-hardware.org/?probe=d0b08c1666) | May 05, 2024 |
| ASRock        | B650 PG Lightning           | [d9c907af86](https://linux-hardware.org/?probe=d9c907af86) | May 05, 2024 |
| ASRock        | 990FX Extreme4              | [4a08259d5e](https://linux-hardware.org/?probe=4a08259d5e) | May 05, 2024 |
| Gigabyte      | GA-970A-D3                  | [1ee81eb650](https://linux-hardware.org/?probe=1ee81eb650) | May 05, 2024 |
| Huanan        | X99-TF                      | [804eb7916a](https://linux-hardware.org/?probe=804eb7916a) | May 05, 2024 |
| Gigabyte      | GA-970A-D3                  | [4fa09a0b8e](https://linux-hardware.org/?probe=4fa09a0b8e) | May 04, 2024 |
| Digiboard     | G41M-S                      | [7b5f122417](https://linux-hardware.org/?probe=7b5f122417) | May 04, 2024 |
| Acer          | Veriton N4640G              | [ce50a47462](https://linux-hardware.org/?probe=ce50a47462) | May 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5e3b7c6308](https://linux-hardware.org/?probe=5e3b7c6308) | May 03, 2024 |
| Gigabyte      | H310M M.2 x.x               | [1b1d2cd8c6](https://linux-hardware.org/?probe=1b1d2cd8c6) | May 02, 2024 |
| Acer          | Veriton N4640G              | [d18d5f8d9d](https://linux-hardware.org/?probe=d18d5f8d9d) | May 02, 2024 |
| ASUSTek       | H81M-K                      | [f4dbf33638](https://linux-hardware.org/?probe=f4dbf33638) | May 02, 2024 |
| Gigabyte      | X570S AORUS ELITE           | [a76ca4fae1](https://linux-hardware.org/?probe=a76ca4fae1) | May 02, 2024 |
| MSI           | MEG Z490 UNIFY              | [73e7f9d576](https://linux-hardware.org/?probe=73e7f9d576) | May 02, 2024 |
| MSI           | MS-7204                     | [5d3f1b6a58](https://linux-hardware.org/?probe=5d3f1b6a58) | May 01, 2024 |
| ASUSTek       | PRIME H510M-E               | [c3b30e066b](https://linux-hardware.org/?probe=c3b30e066b) | May 01, 2024 |
| Acer          | Aspire M5910                | [61b5809dc9](https://linux-hardware.org/?probe=61b5809dc9) | May 01, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8739bc2d60](https://linux-hardware.org/?probe=8739bc2d60) | May 01, 2024 |
| HP            | 8906 SMVB                   | [6c9a72d2cb](https://linux-hardware.org/?probe=6c9a72d2cb) | May 01, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [67a23e48b6](https://linux-hardware.org/?probe=67a23e48b6) | May 01, 2024 |
| Pegatron      | 2A99                        | [fcd74433b3](https://linux-hardware.org/?probe=fcd74433b3) | Apr 30, 2024 |
| Biostar       | G41D3B                      | [748e0749c5](https://linux-hardware.org/?probe=748e0749c5) | Apr 30, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [164f516c10](https://linux-hardware.org/?probe=164f516c10) | Apr 30, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [38975e46ec](https://linux-hardware.org/?probe=38975e46ec) | Apr 30, 2024 |
| ASRock        | N68-S                       | [a099ad6775](https://linux-hardware.org/?probe=a099ad6775) | Apr 30, 2024 |
| Sapphire      | PI-AM3RS760G2               | [4c7535b1ac](https://linux-hardware.org/?probe=4c7535b1ac) | Apr 30, 2024 |
| Gigabyte      | H81M-S2V                    | [11f391fabc](https://linux-hardware.org/?probe=11f391fabc) | Apr 30, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | [8a21aa2463](https://linux-hardware.org/?probe=8a21aa2463) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | [56f9ef0976](https://linux-hardware.org/?probe=56f9ef0976) | Apr 30, 2024 |
| ASRock        | B560M Pro4                  | [510e90dcb8](https://linux-hardware.org/?probe=510e90dcb8) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | [57a68c0dec](https://linux-hardware.org/?probe=57a68c0dec) | Apr 30, 2024 |
| ASRock        | 990FX Extreme4              | [4939bdb260](https://linux-hardware.org/?probe=4939bdb260) | Apr 30, 2024 |
| Gigabyte      | GA-78LMT-S2                 | [56e690c86e](https://linux-hardware.org/?probe=56e690c86e) | Apr 30, 2024 |
| PCWare        | IPMH310G PRO                | [f38e07cde2](https://linux-hardware.org/?probe=f38e07cde2) | Apr 30, 2024 |
| BCM Advanc... | MX87QD                      | [5f5deeae12](https://linux-hardware.org/?probe=5f5deeae12) | Apr 30, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [e0cb14de08](https://linux-hardware.org/?probe=e0cb14de08) | Apr 30, 2024 |
| ASUSTek       | M5A99X EVO                  | [aedd483ccc](https://linux-hardware.org/?probe=aedd483ccc) | Apr 29, 2024 |
| ASUSTek       | F2A85-M_PRO                 | [b4beb034b2](https://linux-hardware.org/?probe=b4beb034b2) | Apr 29, 2024 |
| BESSTAR Te... | HM80                        | [7e9ff18aba](https://linux-hardware.org/?probe=7e9ff18aba) | Apr 29, 2024 |
| ASUSTek       | H97M-PLUS                   | [6ad2b206a6](https://linux-hardware.org/?probe=6ad2b206a6) | Apr 29, 2024 |
| ASUSTek       | Pro A620M-C                 | [124b68b5bf](https://linux-hardware.org/?probe=124b68b5bf) | Apr 29, 2024 |
| Sapphire      | PI-AM3RS760G2               | [c31443d648](https://linux-hardware.org/?probe=c31443d648) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | [9f0eda367d](https://linux-hardware.org/?probe=9f0eda367d) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | [06b56e10dc](https://linux-hardware.org/?probe=06b56e10dc) | Apr 28, 2024 |
| ASRock        | 990FX Extreme4              | [3e16c2d8c6](https://linux-hardware.org/?probe=3e16c2d8c6) | Apr 28, 2024 |
| ASRock        | B760M-HDV/M.2               | [01633e2e6d](https://linux-hardware.org/?probe=01633e2e6d) | Apr 28, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [31af2ca036](https://linux-hardware.org/?probe=31af2ca036) | Apr 28, 2024 |
| ASRock        | 970 Pro3 R2.0               | [7918dabd8f](https://linux-hardware.org/?probe=7918dabd8f) | Apr 28, 2024 |
| AZW           | U59                         | [d310713234](https://linux-hardware.org/?probe=d310713234) | Apr 28, 2024 |
| ASRock        | 970 Pro3 R2.0               | [0902f17c99](https://linux-hardware.org/?probe=0902f17c99) | Apr 27, 2024 |
| ASRock        | 970 Pro3 R2.0               | [91449c8a93](https://linux-hardware.org/?probe=91449c8a93) | Apr 27, 2024 |
| ASRock        | B760M-HDV/M.2               | [324ac4ff48](https://linux-hardware.org/?probe=324ac4ff48) | Apr 27, 2024 |
| Fujitsu       | D3167-A1 S26361-D3167-A1    | [5182ad8bd7](https://linux-hardware.org/?probe=5182ad8bd7) | Apr 27, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [7d60545173](https://linux-hardware.org/?probe=7d60545173) | Apr 27, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [b4d4155591](https://linux-hardware.org/?probe=b4d4155591) | Apr 27, 2024 |
| ASUSTek       | P5QL-CM                     | [28a4852048](https://linux-hardware.org/?probe=28a4852048) | Apr 26, 2024 |
| ASUSTek       | P5QL-CM                     | [bf1873c20d](https://linux-hardware.org/?probe=bf1873c20d) | Apr 26, 2024 |
| Gigabyte      | H55M-UD2H                   | [6caa28f904](https://linux-hardware.org/?probe=6caa28f904) | Apr 26, 2024 |
| ASUSTek       | P7H55-M LE                  | [517a020485](https://linux-hardware.org/?probe=517a020485) | Apr 26, 2024 |
| MSI           | B550-A PRO                  | [083c88fe82](https://linux-hardware.org/?probe=083c88fe82) | Apr 26, 2024 |
| Gigabyte      | Z270-Gaming K3              | [e21d70e37d](https://linux-hardware.org/?probe=e21d70e37d) | Apr 26, 2024 |
| Gigabyte      | P75-D3                      | [496e1605e9](https://linux-hardware.org/?probe=496e1605e9) | Apr 26, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [d25ca314d4](https://linux-hardware.org/?probe=d25ca314d4) | Apr 26, 2024 |
| Dell          | 0GTK4K A02                  | [80bf3e1bd7](https://linux-hardware.org/?probe=80bf3e1bd7) | Apr 26, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [d378d3e2a8](https://linux-hardware.org/?probe=d378d3e2a8) | Apr 26, 2024 |
| ASRock        | G31M-GS                     | [5a76ec66ed](https://linux-hardware.org/?probe=5a76ec66ed) | Apr 26, 2024 |
| HPE           | ProLiant MicroServer Gen... | [ca351b002d](https://linux-hardware.org/?probe=ca351b002d) | Apr 26, 2024 |
| ASUSTek       | P5KPL-CM                    | [8992ae65ab](https://linux-hardware.org/?probe=8992ae65ab) | Apr 26, 2024 |
| MSI           | MAG B550M MORTAR MAX WIF... | [d486386bde](https://linux-hardware.org/?probe=d486386bde) | Apr 26, 2024 |
| Sapphire      | PI-AM3RS760G2               | [bf18be8805](https://linux-hardware.org/?probe=bf18be8805) | Apr 26, 2024 |
| ASRock        | 990FX Extreme4              | [773cffce7f](https://linux-hardware.org/?probe=773cffce7f) | Apr 26, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [a2f7e0ec28](https://linux-hardware.org/?probe=a2f7e0ec28) | Apr 26, 2024 |
| Dell          | 01XK1W A00                  | [a5fcd90239](https://linux-hardware.org/?probe=a5fcd90239) | Apr 26, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [79f0b7e272](https://linux-hardware.org/?probe=79f0b7e272) | Apr 26, 2024 |
| ECS           | H61H2-M13                   | [677042f9b9](https://linux-hardware.org/?probe=677042f9b9) | Apr 25, 2024 |
| ASUSTek       | F2A85-M                     | [94e6f654e9](https://linux-hardware.org/?probe=94e6f654e9) | Apr 25, 2024 |
| ASRock        | 990FX Extreme4              | [7f54c26bc1](https://linux-hardware.org/?probe=7f54c26bc1) | Apr 25, 2024 |
| ASRock        | 990FX Extreme4              | [e7a56f20f9](https://linux-hardware.org/?probe=e7a56f20f9) | Apr 25, 2024 |
| ASRock        | 990FX Extreme4              | [8ed8b87e84](https://linux-hardware.org/?probe=8ed8b87e84) | Apr 25, 2024 |
| Inventec      | DQ Class A02                | [5edaa0ed95](https://linux-hardware.org/?probe=5edaa0ed95) | Apr 24, 2024 |
| ASUSTek       | P5N-MX                      | [8c9cb42e87](https://linux-hardware.org/?probe=8c9cb42e87) | Apr 24, 2024 |
| Sapphire      | PI-AM3RS760G2               | [45b756650e](https://linux-hardware.org/?probe=45b756650e) | Apr 24, 2024 |
| Sapphire      | PI-AM3RS760G2               | [1086d184b6](https://linux-hardware.org/?probe=1086d184b6) | Apr 24, 2024 |
| ASUSTek       | PRIME N100I-D D4            | [d6c9b24678](https://linux-hardware.org/?probe=d6c9b24678) | Apr 24, 2024 |
| Shenzhen M... | RPBNB                       | [37eb2f2a94](https://linux-hardware.org/?probe=37eb2f2a94) | Apr 23, 2024 |
| HP            | 895C                        | [08b147d945](https://linux-hardware.org/?probe=08b147d945) | Apr 23, 2024 |
| ASUSTek       | P5N-MX                      | [8bb509b6d7](https://linux-hardware.org/?probe=8bb509b6d7) | Apr 23, 2024 |
| ADLINK Tec... | LEC-EL A1                   | [72b115951b](https://linux-hardware.org/?probe=72b115951b) | Apr 22, 2024 |
| Gigabyte      | B650I AORUS ULTRA se2       | [0fcc20ba38](https://linux-hardware.org/?probe=0fcc20ba38) | Apr 22, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [02420cbf38](https://linux-hardware.org/?probe=02420cbf38) | Apr 22, 2024 |
| HP            | 8835                        | [63962138e6](https://linux-hardware.org/?probe=63962138e6) | Apr 22, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [2a4799164d](https://linux-hardware.org/?probe=2a4799164d) | Apr 22, 2024 |
| ASRock        | 990FX Extreme4              | [0a9ede9e09](https://linux-hardware.org/?probe=0a9ede9e09) | Apr 22, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [4a46b6f322](https://linux-hardware.org/?probe=4a46b6f322) | Apr 22, 2024 |
| Minix         | NEO Z83-4 V1.1              | [546846d640](https://linux-hardware.org/?probe=546846d640) | Apr 22, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [1c066ce5e2](https://linux-hardware.org/?probe=1c066ce5e2) | Apr 21, 2024 |
| Sapphire      | PI-AM3RS760G2               | [0b6a8b8487](https://linux-hardware.org/?probe=0b6a8b8487) | Apr 21, 2024 |
| ASRock        | B550M-ITX/ac                | [6389731461](https://linux-hardware.org/?probe=6389731461) | Apr 21, 2024 |
| ASRock        | 990FX Extreme4              | [a1cc621a2f](https://linux-hardware.org/?probe=a1cc621a2f) | Apr 21, 2024 |
| ASRock        | 990FX Extreme4              | [5ff81fe9b8](https://linux-hardware.org/?probe=5ff81fe9b8) | Apr 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1fe127b27d](https://linux-hardware.org/?probe=1fe127b27d) | Apr 21, 2024 |
| Huanan        | X99-TF V3.0 JX              | [bb51640f19](https://linux-hardware.org/?probe=bb51640f19) | Apr 21, 2024 |
| ASUSTek       | P9X79                       | [f5f0955b10](https://linux-hardware.org/?probe=f5f0955b10) | Apr 20, 2024 |
| HP            | 82A2                        | [1eeebb4829](https://linux-hardware.org/?probe=1eeebb4829) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS II    | [9666b7dd0c](https://linux-hardware.org/?probe=9666b7dd0c) | Apr 20, 2024 |
| MSI           | MS-7235                     | [67ea957848](https://linux-hardware.org/?probe=67ea957848) | Apr 20, 2024 |
| Colorful T... | C.A68M-E V15                | [b0b7690daa](https://linux-hardware.org/?probe=b0b7690daa) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a1f1d3f4a0](https://linux-hardware.org/?probe=a1f1d3f4a0) | Apr 20, 2024 |
| ASRock        | 990FX Extreme4              | [22ba7e810f](https://linux-hardware.org/?probe=22ba7e810f) | Apr 20, 2024 |
| ASRock        | B450M Steel Legend          | [0df86cd712](https://linux-hardware.org/?probe=0df86cd712) | Apr 20, 2024 |
| ASRock        | 990FX Extreme4              | [88986725e7](https://linux-hardware.org/?probe=88986725e7) | Apr 20, 2024 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [f0e2928850](https://linux-hardware.org/?probe=f0e2928850) | Apr 20, 2024 |
| Dell          | 0R790T A00                  | [82b384c367](https://linux-hardware.org/?probe=82b384c367) | Apr 20, 2024 |
| Gigabyte      | Z390 UD                     | [2f4860118a](https://linux-hardware.org/?probe=2f4860118a) | Apr 19, 2024 |
| Sapphire      | PI-AM3RS760G2               | [3022280b20](https://linux-hardware.org/?probe=3022280b20) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | [018abcebe4](https://linux-hardware.org/?probe=018abcebe4) | Apr 19, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [b1b415511d](https://linux-hardware.org/?probe=b1b415511d) | Apr 19, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [40a4bdb47b](https://linux-hardware.org/?probe=40a4bdb47b) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | [e65c84d822](https://linux-hardware.org/?probe=e65c84d822) | Apr 19, 2024 |
| ASRock        | 990FX Extreme4              | [d1cf256cf2](https://linux-hardware.org/?probe=d1cf256cf2) | Apr 19, 2024 |
| Dell          | 0D9JG3 A00                  | [b5c9c5d6b0](https://linux-hardware.org/?probe=b5c9c5d6b0) | Apr 19, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [8d3a6c05f9](https://linux-hardware.org/?probe=8d3a6c05f9) | Apr 19, 2024 |
| AZW           | U59                         | [3923393266](https://linux-hardware.org/?probe=3923393266) | Apr 19, 2024 |
| ASUSTek       | H110M-D                     | [994b125f04](https://linux-hardware.org/?probe=994b125f04) | Apr 19, 2024 |
| Unknown       | i855-W83627HF               | [e1c3562c4a](https://linux-hardware.org/?probe=e1c3562c4a) | Apr 18, 2024 |
| MSI           | B450-A PRO MAX              | [1babcb92fd](https://linux-hardware.org/?probe=1babcb92fd) | Apr 18, 2024 |
| ASRock        | B450 Pro4 R2.0              | [68b9255929](https://linux-hardware.org/?probe=68b9255929) | Apr 18, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [91410dd38c](https://linux-hardware.org/?probe=91410dd38c) | Apr 18, 2024 |
| ASRock        | 990FX Extreme4              | [e1f8cb5a4d](https://linux-hardware.org/?probe=e1f8cb5a4d) | Apr 18, 2024 |
| Gigabyte      | X570 UD                     | [5240449916](https://linux-hardware.org/?probe=5240449916) | Apr 18, 2024 |
| ASRock        | B550 Pro4                   | [f906fa4f7c](https://linux-hardware.org/?probe=f906fa4f7c) | Apr 18, 2024 |
| Gigabyte      | Z790 UD AC                  | [340a3e1a78](https://linux-hardware.org/?probe=340a3e1a78) | Apr 18, 2024 |
| Intel         | DH67CL AAG10212-207         | [276f923b44](https://linux-hardware.org/?probe=276f923b44) | Apr 18, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [24acebde2b](https://linux-hardware.org/?probe=24acebde2b) | Apr 18, 2024 |
| HP            | 805B                        | [d5bf7c2652](https://linux-hardware.org/?probe=d5bf7c2652) | Apr 18, 2024 |
| Gigabyte      | B450M K-CF                  | [74fb485917](https://linux-hardware.org/?probe=74fb485917) | Apr 17, 2024 |
| Intel         | H55                         | [28e666728f](https://linux-hardware.org/?probe=28e666728f) | Apr 17, 2024 |
| Gigabyte      | Z97X-Gaming 5               | [f08c90bc44](https://linux-hardware.org/?probe=f08c90bc44) | Apr 17, 2024 |
| Intel         | H55                         | [27ee1cd49f](https://linux-hardware.org/?probe=27ee1cd49f) | Apr 17, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [e5f340aec0](https://linux-hardware.org/?probe=e5f340aec0) | Apr 17, 2024 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [68691105b0](https://linux-hardware.org/?probe=68691105b0) | Apr 17, 2024 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [b408b88671](https://linux-hardware.org/?probe=b408b88671) | Apr 17, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | [0d46687bb7](https://linux-hardware.org/?probe=0d46687bb7) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [ba12ac8498](https://linux-hardware.org/?probe=ba12ac8498) | Apr 17, 2024 |
| Intel         | ADL-F10                     | [036f5e1450](https://linux-hardware.org/?probe=036f5e1450) | Apr 16, 2024 |
| MSI           | H61M-P20                    | [17a91ba1d0](https://linux-hardware.org/?probe=17a91ba1d0) | Apr 16, 2024 |
| Sapphire      | PI-AM3RS760G2               | [cfacf09dbe](https://linux-hardware.org/?probe=cfacf09dbe) | Apr 16, 2024 |
| AMI           | Cherry Trail CR             | [e60bc95699](https://linux-hardware.org/?probe=e60bc95699) | Apr 16, 2024 |
| Intel         | D201GLY AAD81205-301        | [1b2fcf83fa](https://linux-hardware.org/?probe=1b2fcf83fa) | Apr 16, 2024 |
| Gigabyte      | GA-78LMT-S2                 | [c9be366373](https://linux-hardware.org/?probe=c9be366373) | Apr 16, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | [7cad8d2493](https://linux-hardware.org/?probe=7cad8d2493) | Apr 16, 2024 |
| ASRock        | 990FX Extreme4              | [7cd3cf42ef](https://linux-hardware.org/?probe=7cd3cf42ef) | Apr 16, 2024 |
| ASRock        | 990FX Extreme4              | [fd99b7519e](https://linux-hardware.org/?probe=fd99b7519e) | Apr 16, 2024 |
| ASRock        | 990FX Extreme4              | [9c51df5a4a](https://linux-hardware.org/?probe=9c51df5a4a) | Apr 15, 2024 |
| ASRock        | 990FX Extreme4              | [4b84c41edf](https://linux-hardware.org/?probe=4b84c41edf) | Apr 15, 2024 |
| ASUSTek       | B85M-G                      | [d8294ede23](https://linux-hardware.org/?probe=d8294ede23) | Apr 15, 2024 |
| AMI           | Intel                       | [d620a9c686](https://linux-hardware.org/?probe=d620a9c686) | Apr 15, 2024 |
| Unknown       | Unknown                     | [b8c681a7fb](https://linux-hardware.org/?probe=b8c681a7fb) | Apr 15, 2024 |
| Pegatron      | 2ACD                        | [897550ea8a](https://linux-hardware.org/?probe=897550ea8a) | Apr 14, 2024 |
| ASRock        | 990FX Extreme4              | [9f29571aab](https://linux-hardware.org/?probe=9f29571aab) | Apr 14, 2024 |
| ASRock        | 990FX Extreme4              | [7259447d3b](https://linux-hardware.org/?probe=7259447d3b) | Apr 14, 2024 |
| ASRock        | FM2A88M Extreme4+           | [2ee0e2ace7](https://linux-hardware.org/?probe=2ee0e2ace7) | Apr 14, 2024 |
| ASRock        | FM2A88M Extreme4+           | [20e465155b](https://linux-hardware.org/?probe=20e465155b) | Apr 14, 2024 |
| ASRock        | X670E PG Lightning          | [e3bd195788](https://linux-hardware.org/?probe=e3bd195788) | Apr 14, 2024 |
| Gigabyte      | X570 GAMING X               | [d79972631a](https://linux-hardware.org/?probe=d79972631a) | Apr 14, 2024 |
| Gigabyte      | X570 GAMING X               | [fa6b81bbbf](https://linux-hardware.org/?probe=fa6b81bbbf) | Apr 14, 2024 |
| ASUSTek       | PRIME A320M-K               | [f3d0eefe93](https://linux-hardware.org/?probe=f3d0eefe93) | Apr 14, 2024 |
| Dell          | 0GXM1W A02                  | [7acfaf7395](https://linux-hardware.org/?probe=7acfaf7395) | Apr 14, 2024 |
| Dell          | 0GXM1W A02                  | [e10d403882](https://linux-hardware.org/?probe=e10d403882) | Apr 14, 2024 |
| Sapphire      | PI-AM3RS760G2               | [64eef30697](https://linux-hardware.org/?probe=64eef30697) | Apr 13, 2024 |
| ASRock        | 990FX Extreme4              | [14ff2613c4](https://linux-hardware.org/?probe=14ff2613c4) | Apr 13, 2024 |
| Gigabyte      | Z270X-UD3-CF                | [b3a5999470](https://linux-hardware.org/?probe=b3a5999470) | Apr 13, 2024 |
| ASUSTek       | CUSL2-C                     | [0d7e468cb8](https://linux-hardware.org/?probe=0d7e468cb8) | Apr 13, 2024 |
| ASUSTek       | CUSL2-C                     | [c64a5747f2](https://linux-hardware.org/?probe=c64a5747f2) | Apr 12, 2024 |
| ASRock        | Z690 PG Riptide             | [b5891958b5](https://linux-hardware.org/?probe=b5891958b5) | Apr 12, 2024 |
| HP            | 8053                        | [7518745fe0](https://linux-hardware.org/?probe=7518745fe0) | Apr 12, 2024 |
| Gigabyte      | Z77X-UD3H                   | [716fbdb5b2](https://linux-hardware.org/?probe=716fbdb5b2) | Apr 12, 2024 |
| ASUSTek       | P8H77-V                     | [ff2fb02615](https://linux-hardware.org/?probe=ff2fb02615) | Apr 12, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [d9ab381361](https://linux-hardware.org/?probe=d9ab381361) | Apr 12, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [861ffd6210](https://linux-hardware.org/?probe=861ffd6210) | Apr 12, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [bc8e13b93d](https://linux-hardware.org/?probe=bc8e13b93d) | Apr 12, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [8d3873a49f](https://linux-hardware.org/?probe=8d3873a49f) | Apr 12, 2024 |
| HP            | 3397                        | [878192f0bd](https://linux-hardware.org/?probe=878192f0bd) | Apr 11, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [026c72df1c](https://linux-hardware.org/?probe=026c72df1c) | Apr 11, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [75b741a57b](https://linux-hardware.org/?probe=75b741a57b) | Apr 11, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [ab8331fb24](https://linux-hardware.org/?probe=ab8331fb24) | Apr 11, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [204eec6335](https://linux-hardware.org/?probe=204eec6335) | Apr 11, 2024 |
| Lenovo        | Bantry CRB NOK              | [451151dc37](https://linux-hardware.org/?probe=451151dc37) | Apr 11, 2024 |
| ASUSTek       | Pro B560M-C                 | [e7a4618bc4](https://linux-hardware.org/?probe=e7a4618bc4) | Apr 11, 2024 |
| ASUSTek       | PRIME Z270-A                | [44d8afa05f](https://linux-hardware.org/?probe=44d8afa05f) | Apr 11, 2024 |
| Intel         | D845GRG AAA81583-300        | [678a3f7bf8](https://linux-hardware.org/?probe=678a3f7bf8) | Apr 10, 2024 |
| Sapphire      | PI-AM3RS760G2               | [bcb9300739](https://linux-hardware.org/?probe=bcb9300739) | Apr 10, 2024 |
| Gigabyte      | B460M D3H                   | [93b276e677](https://linux-hardware.org/?probe=93b276e677) | Apr 10, 2024 |
| HP            | 1998                        | [c0b0ec87ec](https://linux-hardware.org/?probe=c0b0ec87ec) | Apr 10, 2024 |
| ASUSTek       | Q87T                        | [9b85fb5652](https://linux-hardware.org/?probe=9b85fb5652) | Apr 10, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [0b230ea544](https://linux-hardware.org/?probe=0b230ea544) | Apr 10, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [bdcccf8c92](https://linux-hardware.org/?probe=bdcccf8c92) | Apr 10, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [2ca0777f6f](https://linux-hardware.org/?probe=2ca0777f6f) | Apr 10, 2024 |
| GenMachine    | Ren12                       | [f5ec7252ac](https://linux-hardware.org/?probe=f5ec7252ac) | Apr 10, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [09d22d5711](https://linux-hardware.org/?probe=09d22d5711) | Apr 10, 2024 |
| Lenovo        | 36E9 SDK0R32862 WIN 3258... | [e494587893](https://linux-hardware.org/?probe=e494587893) | Apr 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | [79a4ac6c52](https://linux-hardware.org/?probe=79a4ac6c52) | Apr 09, 2024 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [5c33da7024](https://linux-hardware.org/?probe=5c33da7024) | Apr 09, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [ffd26f8255](https://linux-hardware.org/?probe=ffd26f8255) | Apr 09, 2024 |
| Lenovo        | 32E6 NOK                    | [b560c0d5fe](https://linux-hardware.org/?probe=b560c0d5fe) | Apr 09, 2024 |
| Lenovo        | 3740 NOK                    | [355c32d663](https://linux-hardware.org/?probe=355c32d663) | Apr 09, 2024 |
| HP            | 158B                        | [d7c58cf079](https://linux-hardware.org/?probe=d7c58cf079) | Apr 09, 2024 |
| Gigabyte      | GA-78LMT-S2                 | [bf17502965](https://linux-hardware.org/?probe=bf17502965) | Apr 09, 2024 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [2f2ae87a60](https://linux-hardware.org/?probe=2f2ae87a60) | Apr 08, 2024 |
| Intel         | ADL-F10                     | [17a43967f2](https://linux-hardware.org/?probe=17a43967f2) | Apr 08, 2024 |
| MSI           | MPG B650I EDGE WIFI         | [295a425d96](https://linux-hardware.org/?probe=295a425d96) | Apr 08, 2024 |
| ASRock        | B650M Pro RS                | [8a6331a3b2](https://linux-hardware.org/?probe=8a6331a3b2) | Apr 08, 2024 |
| ASRock        | B650M Pro RS                | [9c421a9dbb](https://linux-hardware.org/?probe=9c421a9dbb) | Apr 08, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [9cc14232f1](https://linux-hardware.org/?probe=9cc14232f1) | Apr 08, 2024 |
| ASUSTek       | P5KPL-CM                    | [794f80b5a2](https://linux-hardware.org/?probe=794f80b5a2) | Apr 08, 2024 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | [6c9980ed7d](https://linux-hardware.org/?probe=6c9980ed7d) | Apr 08, 2024 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | [08f0877b81](https://linux-hardware.org/?probe=08f0877b81) | Apr 08, 2024 |
| Gigabyte      | B85M-D3H                    | [fa70861321](https://linux-hardware.org/?probe=fa70861321) | Apr 07, 2024 |
| Dell          | 01XK1W A00                  | [708da72614](https://linux-hardware.org/?probe=708da72614) | Apr 07, 2024 |
| ASRock        | X570S PG Riptide            | [2ceec9259b](https://linux-hardware.org/?probe=2ceec9259b) | Apr 07, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [ee31a1ab57](https://linux-hardware.org/?probe=ee31a1ab57) | Apr 07, 2024 |
| SolidRun      | CEX7 Platform               | [921a652a7e](https://linux-hardware.org/?probe=921a652a7e) | Apr 07, 2024 |
| Dell          | 06X1TJ A00                  | [9a4f23a1e2](https://linux-hardware.org/?probe=9a4f23a1e2) | Apr 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [ebc11c966d](https://linux-hardware.org/?probe=ebc11c966d) | Apr 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [c917535f70](https://linux-hardware.org/?probe=c917535f70) | Apr 06, 2024 |
| Gigabyte      | B760I AORUS PRO             | [3de78e9354](https://linux-hardware.org/?probe=3de78e9354) | Apr 06, 2024 |
| SZMZ          | X99-S3                      | [a3be3fb7ae](https://linux-hardware.org/?probe=a3be3fb7ae) | Apr 06, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [edd04ef397](https://linux-hardware.org/?probe=edd04ef397) | Apr 06, 2024 |
| ASUSTek       | M4A785-M                    | [dae4d8f0c7](https://linux-hardware.org/?probe=dae4d8f0c7) | Apr 05, 2024 |
| ASUSTek       | PRIME H410M-A               | [1cb1d0f6bf](https://linux-hardware.org/?probe=1cb1d0f6bf) | Apr 05, 2024 |
| ASUSTek       | M4A785-M                    | [1a3e173e11](https://linux-hardware.org/?probe=1a3e173e11) | Apr 05, 2024 |
| ASUSTek       | STRIX Z270G GAMING          | [67a3c40ae1](https://linux-hardware.org/?probe=67a3c40ae1) | Apr 05, 2024 |
| MSI           | MS-B0A21                    | [e74fc30957](https://linux-hardware.org/?probe=e74fc30957) | Apr 05, 2024 |
| ASUSTek       | TUF Gaming B460-PLUS        | [3c7ff2a204](https://linux-hardware.org/?probe=3c7ff2a204) | Apr 05, 2024 |
| ASRock        | 990FX Extreme4              | [b2df81d7c6](https://linux-hardware.org/?probe=b2df81d7c6) | Apr 05, 2024 |
| ASRock        | Z97 Extreme4                | [b3391cd116](https://linux-hardware.org/?probe=b3391cd116) | Apr 05, 2024 |
| ASUSTek       | PRIME Z270-AR               | [d994e7a27c](https://linux-hardware.org/?probe=d994e7a27c) | Apr 05, 2024 |
| ASUSTek       | PRIME Z270-AR               | [f4fc63ac25](https://linux-hardware.org/?probe=f4fc63ac25) | Apr 05, 2024 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [09d25c6ea8](https://linux-hardware.org/?probe=09d25c6ea8) | Apr 04, 2024 |
| Dell          | 0XKH0D A02                  | [ee1a50dbca](https://linux-hardware.org/?probe=ee1a50dbca) | Apr 04, 2024 |
| Dell          | 0PU052                      | [6555bfeb7b](https://linux-hardware.org/?probe=6555bfeb7b) | Apr 04, 2024 |
| ASRock        | B450M/ac R2.0               | [454169b7c9](https://linux-hardware.org/?probe=454169b7c9) | Apr 04, 2024 |
| Gigabyte      | B360M H                     | [acb3dd01b9](https://linux-hardware.org/?probe=acb3dd01b9) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | [a12df57269](https://linux-hardware.org/?probe=a12df57269) | Apr 04, 2024 |
| Gigabyte      | B85M-D3H                    | [f4641bc90c](https://linux-hardware.org/?probe=f4641bc90c) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | [648e1cbe49](https://linux-hardware.org/?probe=648e1cbe49) | Apr 04, 2024 |
| ASRock        | 990FX Extreme4              | [e41ebb7b08](https://linux-hardware.org/?probe=e41ebb7b08) | Apr 04, 2024 |
| Gigabyte      | B450M DS3H-CF               | [31a5f26be7](https://linux-hardware.org/?probe=31a5f26be7) | Apr 03, 2024 |
| ASUSTek       | G11CB                       | [372379f18a](https://linux-hardware.org/?probe=372379f18a) | Apr 03, 2024 |
| MSI           | H110M PRO-VH                | [a135bec51e](https://linux-hardware.org/?probe=a135bec51e) | Apr 03, 2024 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [3463a25d2c](https://linux-hardware.org/?probe=3463a25d2c) | Apr 03, 2024 |
| Supermicro    | X8ST3                       | [45765546f5](https://linux-hardware.org/?probe=45765546f5) | Apr 03, 2024 |
| ASRock        | H55M-LE                     | [603c13de70](https://linux-hardware.org/?probe=603c13de70) | Apr 03, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | [29d954b3b6](https://linux-hardware.org/?probe=29d954b3b6) | Apr 03, 2024 |
| Google        | Fizz                        | [55cd95ea52](https://linux-hardware.org/?probe=55cd95ea52) | Apr 03, 2024 |
| Shenzhen M... | AHBNB OEM                   | [1c9bd6a74d](https://linux-hardware.org/?probe=1c9bd6a74d) | Apr 03, 2024 |
| Gigabyte      | Z97X-Gaming 5               | [ce53254be7](https://linux-hardware.org/?probe=ce53254be7) | Apr 02, 2024 |
| ASUSTek       | M5A97 PLUS                  | [b45101bd55](https://linux-hardware.org/?probe=b45101bd55) | Apr 02, 2024 |
| ASUSTek       | P8H61-MX R2.0               | [2f768997ff](https://linux-hardware.org/?probe=2f768997ff) | Apr 02, 2024 |
| Intel         | DX58SO2 AAG10925-207        | [170582acfb](https://linux-hardware.org/?probe=170582acfb) | Apr 02, 2024 |
| Intel         | DX58SO2 AAG10925-207        | [a91ca2286f](https://linux-hardware.org/?probe=a91ca2286f) | Apr 02, 2024 |
| Dell          | 04MFRM A02                  | [588fc1d405](https://linux-hardware.org/?probe=588fc1d405) | Apr 01, 2024 |
| Dinson        | Unknown                     | [2aff8e107a](https://linux-hardware.org/?probe=2aff8e107a) | Apr 01, 2024 |
| Gigabyte      | EP35C-DS3R                  | [bfc80c9d90](https://linux-hardware.org/?probe=bfc80c9d90) | Apr 01, 2024 |
| MSI           | X399 SLI PLUS               | [e519990ad6](https://linux-hardware.org/?probe=e519990ad6) | Apr 01, 2024 |
| ASUSTek       | PRIME B450M-K II            | [f8bc7da1fc](https://linux-hardware.org/?probe=f8bc7da1fc) | Apr 01, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [c8f03b02ba](https://linux-hardware.org/?probe=c8f03b02ba) | Mar 31, 2024 |
| Dell          | 0J2J3Y A00                  | [34c276b20a](https://linux-hardware.org/?probe=34c276b20a) | Mar 31, 2024 |
| MSI           | B350M MORTAR                | [fa958acf10](https://linux-hardware.org/?probe=fa958acf10) | Mar 31, 2024 |
| Intel         | DP35DP AAD81073-207         | [8d783be6f7](https://linux-hardware.org/?probe=8d783be6f7) | Mar 31, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [9f092af8fc](https://linux-hardware.org/?probe=9f092af8fc) | Mar 31, 2024 |
| Unknown       | Unknown                     | [1c48ba772e](https://linux-hardware.org/?probe=1c48ba772e) | Mar 31, 2024 |
| ASUSTek       | PRIME B660M-A AC D4         | [09927387b6](https://linux-hardware.org/?probe=09927387b6) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | [c03a952f7a](https://linux-hardware.org/?probe=c03a952f7a) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | [eeb5af4e4d](https://linux-hardware.org/?probe=eeb5af4e4d) | Mar 31, 2024 |
| ASRock        | 990FX Extreme4              | [45c3f7f796](https://linux-hardware.org/?probe=45c3f7f796) | Mar 31, 2024 |
| ASUSTek       | H110M-K                     | [8b3c41683d](https://linux-hardware.org/?probe=8b3c41683d) | Mar 30, 2024 |
| ASUSTek       | PRIME B460M-A               | [dbc70004b3](https://linux-hardware.org/?probe=dbc70004b3) | Mar 30, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [e988ec8d61](https://linux-hardware.org/?probe=e988ec8d61) | Mar 30, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [0c67b02957](https://linux-hardware.org/?probe=0c67b02957) | Mar 30, 2024 |
| Gigabyte      | J1900N-D3V                  | [b79b70e996](https://linux-hardware.org/?probe=b79b70e996) | Mar 30, 2024 |
| HP            | 8463                        | [dd77e7dc68](https://linux-hardware.org/?probe=dd77e7dc68) | Mar 30, 2024 |
| ASRock        | 990FX Extreme4              | [e1a32810f8](https://linux-hardware.org/?probe=e1a32810f8) | Mar 29, 2024 |
| ASRock        | 990FX Extreme4              | [9be524311b](https://linux-hardware.org/?probe=9be524311b) | Mar 29, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | [fd1414dbcb](https://linux-hardware.org/?probe=fd1414dbcb) | Mar 29, 2024 |
| JGINYUE       | X99M-PLUS D4 V3.1           | [e44ab52f45](https://linux-hardware.org/?probe=e44ab52f45) | Mar 29, 2024 |
| Gigabyte      | X570 UD                     | [539238d399](https://linux-hardware.org/?probe=539238d399) | Mar 29, 2024 |
| ASRock        | B550 Pro4                   | [9144eb7fe4](https://linux-hardware.org/?probe=9144eb7fe4) | Mar 29, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [d84d712a77](https://linux-hardware.org/?probe=d84d712a77) | Mar 29, 2024 |
| MSI           | X470 GAMING PLUS            | [e312018423](https://linux-hardware.org/?probe=e312018423) | Mar 29, 2024 |
| Gigabyte      | Z790 UD AX                  | [d0b7751780](https://linux-hardware.org/?probe=d0b7751780) | Mar 28, 2024 |
| Unknown       | Unknown                     | [dcdb71e975](https://linux-hardware.org/?probe=dcdb71e975) | Mar 28, 2024 |
| MSI           | H110M PRO-VD                | [f14980865f](https://linux-hardware.org/?probe=f14980865f) | Mar 28, 2024 |
| ASUSTek       | B85M-G                      | [e80bef29a7](https://linux-hardware.org/?probe=e80bef29a7) | Mar 28, 2024 |
| Dell          | 0WR7PY A01                  | [aa3125e137](https://linux-hardware.org/?probe=aa3125e137) | Mar 27, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [31a385d0e9](https://linux-hardware.org/?probe=31a385d0e9) | Mar 27, 2024 |
| Gigabyte      | H81M-S2V                    | [af7633b712](https://linux-hardware.org/?probe=af7633b712) | Mar 27, 2024 |
| Lenovo        | ThinkServer TS440           | [063d6aafdb](https://linux-hardware.org/?probe=063d6aafdb) | Mar 27, 2024 |
| Gigabyte      | Z77-D3H                     | [f74c46802a](https://linux-hardware.org/?probe=f74c46802a) | Mar 27, 2024 |
| Dell          | 0D6H9T A00                  | [26269c60d1](https://linux-hardware.org/?probe=26269c60d1) | Mar 27, 2024 |
| MSI           | B450M MORTAR MAX            | [ae5952b714](https://linux-hardware.org/?probe=ae5952b714) | Mar 27, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [f6f2e4d8d3](https://linux-hardware.org/?probe=f6f2e4d8d3) | Mar 26, 2024 |
| Biostar       | B450MX-S                    | [dd90661bff](https://linux-hardware.org/?probe=dd90661bff) | Mar 26, 2024 |
| Gigabyte      | B365M D2V                   | [bd13d968ce](https://linux-hardware.org/?probe=bd13d968ce) | Mar 26, 2024 |
| Dell          | 088DT1 A01                  | [9eb745f7d5](https://linux-hardware.org/?probe=9eb745f7d5) | Mar 26, 2024 |
| ASRock        | 990FX Extreme4              | [1652f0954c](https://linux-hardware.org/?probe=1652f0954c) | Mar 26, 2024 |
| ASRock        | 990FX Extreme4              | [e772c3db14](https://linux-hardware.org/?probe=e772c3db14) | Mar 26, 2024 |
| Gigabyte      | B760M DS3H DDR4             | [069f9b2bc9](https://linux-hardware.org/?probe=069f9b2bc9) | Mar 26, 2024 |
| AZW           | MINI S 10                   | [1e65a63efc](https://linux-hardware.org/?probe=1e65a63efc) | Mar 25, 2024 |
| Dell          | 0DR845                      | [81bc347039](https://linux-hardware.org/?probe=81bc347039) | Mar 25, 2024 |
| ASUSTek       | P5Q SE2                     | [7cad0a2b84](https://linux-hardware.org/?probe=7cad0a2b84) | Mar 24, 2024 |
| Dell          | 06D7TR A02                  | [ae3cf563b4](https://linux-hardware.org/?probe=ae3cf563b4) | Mar 24, 2024 |
| Intel         | DX58SO AAE29331-503         | [7e3d9e89de](https://linux-hardware.org/?probe=7e3d9e89de) | Mar 24, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [773df1edad](https://linux-hardware.org/?probe=773df1edad) | Mar 24, 2024 |
| Packard Be... | WMCP78M                     | [854bfb4d53](https://linux-hardware.org/?probe=854bfb4d53) | Mar 24, 2024 |
| Medion        | MS-7616                     | [56b5e8ba1d](https://linux-hardware.org/?probe=56b5e8ba1d) | Mar 24, 2024 |
| Dell          | 06D7TR A02                  | [d66b1dcb1a](https://linux-hardware.org/?probe=d66b1dcb1a) | Mar 24, 2024 |
| Dell          | 01XK1W A00                  | [6940ab6143](https://linux-hardware.org/?probe=6940ab6143) | Mar 24, 2024 |
| ASUSTek       | P5Q SE PLUS                 | [54ee23abb0](https://linux-hardware.org/?probe=54ee23abb0) | Mar 24, 2024 |
| ASUSTek       | PRIME X370-PRO              | [1cbf811621](https://linux-hardware.org/?probe=1cbf811621) | Mar 24, 2024 |
| SYWZ          | S210HA Series               | [0adb0f4432](https://linux-hardware.org/?probe=0adb0f4432) | Mar 23, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [04f792e4fe](https://linux-hardware.org/?probe=04f792e4fe) | Mar 23, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [4629f81fff](https://linux-hardware.org/?probe=4629f81fff) | Mar 23, 2024 |
| Dell          | 048DY8 A01                  | [05267117e8](https://linux-hardware.org/?probe=05267117e8) | Mar 23, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [b0092a8e43](https://linux-hardware.org/?probe=b0092a8e43) | Mar 23, 2024 |
| Acer          | RS880M05                    | [d4f039d786](https://linux-hardware.org/?probe=d4f039d786) | Mar 23, 2024 |
| Biostar       | B450MX-S                    | [6afcf0e275](https://linux-hardware.org/?probe=6afcf0e275) | Mar 23, 2024 |
| SYWZ          | S210HA Series               | [0fbf298970](https://linux-hardware.org/?probe=0fbf298970) | Mar 23, 2024 |
| HP            | 8266                        | [df49dd1099](https://linux-hardware.org/?probe=df49dd1099) | Mar 22, 2024 |
| HP            | 82A2                        | [fcb3205539](https://linux-hardware.org/?probe=fcb3205539) | Mar 22, 2024 |
| ASUSTek       | PRIME X670-P                | [e3c04a457d](https://linux-hardware.org/?probe=e3c04a457d) | Mar 22, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [b9335282c7](https://linux-hardware.org/?probe=b9335282c7) | Mar 22, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [5a4786b744](https://linux-hardware.org/?probe=5a4786b744) | Mar 22, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [619de50d8d](https://linux-hardware.org/?probe=619de50d8d) | Mar 22, 2024 |
| Intel         | D510MO AAE76523-403         | [4017a437d3](https://linux-hardware.org/?probe=4017a437d3) | Mar 21, 2024 |
| Shuttle       | FX79R                       | [eb2e392958](https://linux-hardware.org/?probe=eb2e392958) | Mar 21, 2024 |
| ASRock        | Z77 Pro3                    | [51c0a74384](https://linux-hardware.org/?probe=51c0a74384) | Mar 21, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [3597d1a106](https://linux-hardware.org/?probe=3597d1a106) | Mar 21, 2024 |
| ASUSTek       | P8H61-M LX3                 | [5b4707338f](https://linux-hardware.org/?probe=5b4707338f) | Mar 21, 2024 |
| ASUSTek       | P8H61-M LX3                 | [0801a23a0f](https://linux-hardware.org/?probe=0801a23a0f) | Mar 21, 2024 |
| Gigabyte      | H61M-DS2                    | [fa35d836d3](https://linux-hardware.org/?probe=fa35d836d3) | Mar 21, 2024 |
| ASUSTek       | PRIME B760M-A D4            | [870960dbb0](https://linux-hardware.org/?probe=870960dbb0) | Mar 21, 2024 |
| ASUSTek       | P8H61-M LX3                 | [bbd6d31a0c](https://linux-hardware.org/?probe=bbd6d31a0c) | Mar 21, 2024 |
| ASUSTek       | P8H61-M LX3                 | [131fa6deb3](https://linux-hardware.org/?probe=131fa6deb3) | Mar 21, 2024 |
| MSI           | G31TM-P21                   | [da55967c61](https://linux-hardware.org/?probe=da55967c61) | Mar 21, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [b12ff3e977](https://linux-hardware.org/?probe=b12ff3e977) | Mar 21, 2024 |
| Intel         | DB85FL AAG89861-201         | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| Gigabyte      | H81ND2H                     | [9b5fecade5](https://linux-hardware.org/?probe=9b5fecade5) | Mar 21, 2024 |
| ASRock        | 990FX Extreme4              | [e5613c8592](https://linux-hardware.org/?probe=e5613c8592) | Mar 21, 2024 |
| ASRock        | 990FX Extreme4              | [e1da52705a](https://linux-hardware.org/?probe=e1da52705a) | Mar 21, 2024 |
| ASRock        | 990FX Extreme4              | [99789095cd](https://linux-hardware.org/?probe=99789095cd) | Mar 21, 2024 |
| MSI           | Z97 GAMING 3                | [ed6f176128](https://linux-hardware.org/?probe=ed6f176128) | Mar 20, 2024 |
| Gigabyte      | H61M-S2PV                   | [a8ead75f81](https://linux-hardware.org/?probe=a8ead75f81) | Mar 20, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b3bd8d15bb](https://linux-hardware.org/?probe=b3bd8d15bb) | Mar 20, 2024 |
| OEM           | X79G                        | [3e4d82db74](https://linux-hardware.org/?probe=3e4d82db74) | Mar 20, 2024 |
| Intel         | H55                         | [bb1c373ea6](https://linux-hardware.org/?probe=bb1c373ea6) | Mar 20, 2024 |
| ASUSTek       | PRIME Z270-A                | [1aab338075](https://linux-hardware.org/?probe=1aab338075) | Mar 20, 2024 |
| Gigabyte      | Z97-HD3                     | [d6dfd879ee](https://linux-hardware.org/?probe=d6dfd879ee) | Mar 20, 2024 |
| ASUSTek       | PRIME B460M-A               | [6d5c05f0a7](https://linux-hardware.org/?probe=6d5c05f0a7) | Mar 20, 2024 |
| ASUSTek       | PRIME Z590-P                | [73f72d473b](https://linux-hardware.org/?probe=73f72d473b) | Mar 19, 2024 |
| ASUSTek       | PRIME Z590-P                | [b526dd935f](https://linux-hardware.org/?probe=b526dd935f) | Mar 19, 2024 |
| ASUSTek       | PRIME H410M-R               | [5213638a3c](https://linux-hardware.org/?probe=5213638a3c) | Mar 19, 2024 |
| ASUSTek       | M5A97 PRO                   | [56aa7a5265](https://linux-hardware.org/?probe=56aa7a5265) | Mar 19, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2ec5403695](https://linux-hardware.org/?probe=2ec5403695) | Mar 19, 2024 |
| JGINYUE       | X99-D8 Server V1.0          | [aad6effeb0](https://linux-hardware.org/?probe=aad6effeb0) | Mar 18, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [fecb6cf968](https://linux-hardware.org/?probe=fecb6cf968) | Mar 18, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | [e467a62b44](https://linux-hardware.org/?probe=e467a62b44) | Mar 18, 2024 |
| Intel         | H61 V1.1                    | [eb0d3daea7](https://linux-hardware.org/?probe=eb0d3daea7) | Mar 18, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [86302bbd71](https://linux-hardware.org/?probe=86302bbd71) | Mar 18, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [0a5c9e24b5](https://linux-hardware.org/?probe=0a5c9e24b5) | Mar 17, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [b187be84a4](https://linux-hardware.org/?probe=b187be84a4) | Mar 17, 2024 |
| ASRock        | 990FX Extreme4              | [d02fd3d860](https://linux-hardware.org/?probe=d02fd3d860) | Mar 17, 2024 |
| ASRock        | 990FX Extreme4              | [3bd52dc634](https://linux-hardware.org/?probe=3bd52dc634) | Mar 17, 2024 |
| Unknown       | 1.0                         | [95713f1f4b](https://linux-hardware.org/?probe=95713f1f4b) | Mar 17, 2024 |
| ASRock        | 990FX Extreme4              | [35209a450e](https://linux-hardware.org/?probe=35209a450e) | Mar 17, 2024 |
| HP            | 2B38                        | [b0457c0f4a](https://linux-hardware.org/?probe=b0457c0f4a) | Mar 17, 2024 |
| Intel         | DB43LD AAE60577-204         | [9b9fab3f17](https://linux-hardware.org/?probe=9b9fab3f17) | Mar 17, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e8e05c9b6f](https://linux-hardware.org/?probe=e8e05c9b6f) | Mar 17, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | [b51fd9bc2b](https://linux-hardware.org/?probe=b51fd9bc2b) | Mar 16, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | [a3a01d0403](https://linux-hardware.org/?probe=a3a01d0403) | Mar 16, 2024 |
| AZW           | GK mini                     | [afe9ed8283](https://linux-hardware.org/?probe=afe9ed8283) | Mar 16, 2024 |
| Gigabyte      | Z170-HD3P-CF                | [291b222709](https://linux-hardware.org/?probe=291b222709) | Mar 16, 2024 |
| Gigabyte      | B450M AORUS ELITE           | [d54d058ff4](https://linux-hardware.org/?probe=d54d058ff4) | Mar 16, 2024 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [048f588fac](https://linux-hardware.org/?probe=048f588fac) | Mar 16, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [17aa01dfc2](https://linux-hardware.org/?probe=17aa01dfc2) | Mar 16, 2024 |
| Sapphire      | PI-AM3RS760G2               | [12ebbdd41a](https://linux-hardware.org/?probe=12ebbdd41a) | Mar 15, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [d63edacb71](https://linux-hardware.org/?probe=d63edacb71) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | [9170891a99](https://linux-hardware.org/?probe=9170891a99) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | [1da99640ba](https://linux-hardware.org/?probe=1da99640ba) | Mar 15, 2024 |
| ASRock        | 990FX Extreme4              | [00e6d44f41](https://linux-hardware.org/?probe=00e6d44f41) | Mar 15, 2024 |
| Gigabyte      | H61M-DS2                    | [af8cc61afe](https://linux-hardware.org/?probe=af8cc61afe) | Mar 14, 2024 |
| Gigabyte      | H61M-DS2                    | [ba3ec85a8c](https://linux-hardware.org/?probe=ba3ec85a8c) | Mar 14, 2024 |
| Sapphire      | PI-AM3RS760G2               | [1c8ceb24a1](https://linux-hardware.org/?probe=1c8ceb24a1) | Mar 14, 2024 |
| ASRockRack    | B450D4U-V1L                 | [4611e234b8](https://linux-hardware.org/?probe=4611e234b8) | Mar 14, 2024 |
| Intel         | H81                         | [e7d551c959](https://linux-hardware.org/?probe=e7d551c959) | Mar 14, 2024 |
| ASUSTek       | AT4NM10T-I                  | [6d006ade6c](https://linux-hardware.org/?probe=6d006ade6c) | Mar 13, 2024 |
| ASUSTek       | AT4NM10T-I                  | [f7ddcc5c64](https://linux-hardware.org/?probe=f7ddcc5c64) | Mar 13, 2024 |
| Intel         | X58 V1608                   | [48e5f0f5a6](https://linux-hardware.org/?probe=48e5f0f5a6) | Mar 13, 2024 |
| Intel         | X58 V1608                   | [84ccc96b6b](https://linux-hardware.org/?probe=84ccc96b6b) | Mar 13, 2024 |
| Gigabyte      | H81M-S2V                    | [951c32a197](https://linux-hardware.org/?probe=951c32a197) | Mar 13, 2024 |
| Sapphire      | PI-AM3RS760G2               | [d75eaeebc0](https://linux-hardware.org/?probe=d75eaeebc0) | Mar 13, 2024 |
| ASRock        | X570 Phantom Gaming X       | [2a14a96457](https://linux-hardware.org/?probe=2a14a96457) | Mar 12, 2024 |
| Intel         | X79G-A V2.0                 | [87e5ff547d](https://linux-hardware.org/?probe=87e5ff547d) | Mar 12, 2024 |
| Sapphire      | PI-AM3RS760G2               | [5391520be0](https://linux-hardware.org/?probe=5391520be0) | Mar 12, 2024 |
| ASUSTek       | PRIME A520M-K               | [859c361cb9](https://linux-hardware.org/?probe=859c361cb9) | Mar 12, 2024 |
| ASRock        | ConRoe1333-DVI/H            | [568d966b3f](https://linux-hardware.org/?probe=568d966b3f) | Mar 12, 2024 |
| ASUSTek       | P8Z77-M                     | [9b5be8dd07](https://linux-hardware.org/?probe=9b5be8dd07) | Mar 12, 2024 |
| Dell          | 0RCPW3 A03                  | [4fcaa7c300](https://linux-hardware.org/?probe=4fcaa7c300) | Mar 12, 2024 |
| GEEKOM        | Mini IT13                   | [945ed05c48](https://linux-hardware.org/?probe=945ed05c48) | Mar 11, 2024 |
| Huanan        | X99-TF V3.0 JX              | [23c5dd18e5](https://linux-hardware.org/?probe=23c5dd18e5) | Mar 11, 2024 |
| ASRock        | B450M-HDV R4.0              | [f17a5b4720](https://linux-hardware.org/?probe=f17a5b4720) | Mar 11, 2024 |
| Gigabyte      | B75M-D3H                    | [e350a0f21a](https://linux-hardware.org/?probe=e350a0f21a) | Mar 10, 2024 |
| Inventec      | DQ Class A02                | [37d048c93a](https://linux-hardware.org/?probe=37d048c93a) | Mar 10, 2024 |
| ASRockRack    | B550D4U-2T R1.00            | [79de662be3](https://linux-hardware.org/?probe=79de662be3) | Mar 10, 2024 |
| HP            | 2175                        | [49dc8b7f3e](https://linux-hardware.org/?probe=49dc8b7f3e) | Mar 10, 2024 |
| Supermicro    | X9DR3-F                     | [4f5a5a1b7c](https://linux-hardware.org/?probe=4f5a5a1b7c) | Mar 10, 2024 |
| Supermicro    | X9DR3-F                     | [f4f1646c44](https://linux-hardware.org/?probe=f4f1646c44) | Mar 10, 2024 |
| ASRock        | A320M-DGS                   | [74a9159cb7](https://linux-hardware.org/?probe=74a9159cb7) | Mar 10, 2024 |
| Sapphire      | PI-AM3RS760G2               | [1eecb13729](https://linux-hardware.org/?probe=1eecb13729) | Mar 10, 2024 |
| Gigabyte      | B650 GAMING X AX            | [36d3d4da58](https://linux-hardware.org/?probe=36d3d4da58) | Mar 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | [79ca53b90b](https://linux-hardware.org/?probe=79ca53b90b) | Mar 09, 2024 |
| ASUSTek       | PRIME A320M-K               | [26a448f763](https://linux-hardware.org/?probe=26a448f763) | Mar 09, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [caa3411c2c](https://linux-hardware.org/?probe=caa3411c2c) | Mar 09, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | [3890a0c9b5](https://linux-hardware.org/?probe=3890a0c9b5) | Mar 09, 2024 |
| System76      | Thelio thelio-r2            | [f991b0cab8](https://linux-hardware.org/?probe=f991b0cab8) | Mar 09, 2024 |
| ASRock        | X570 Phantom Gaming X       | [abc44a83ff](https://linux-hardware.org/?probe=abc44a83ff) | Mar 09, 2024 |
| Intel         | BQM5                        | [36ca4efb8c](https://linux-hardware.org/?probe=36ca4efb8c) | Mar 09, 2024 |
| ASRock        | 990FX Extreme4              | [3080527b19](https://linux-hardware.org/?probe=3080527b19) | Mar 09, 2024 |
| MSI           | X99S SLI PLUS               | [310dce5320](https://linux-hardware.org/?probe=310dce5320) | Mar 09, 2024 |
| Dell          | 0PJDGF A02                  | [6b66f42f95](https://linux-hardware.org/?probe=6b66f42f95) | Mar 08, 2024 |
| ASRock        | D1800M                      | [9098eafea6](https://linux-hardware.org/?probe=9098eafea6) | Mar 08, 2024 |
| Gigabyte      | H77N-WIFI                   | [c58d7ff7b8](https://linux-hardware.org/?probe=c58d7ff7b8) | Mar 08, 2024 |
| Dell          | 0M3918                      | [28a616adee](https://linux-hardware.org/?probe=28a616adee) | Mar 08, 2024 |
| Dell          | 0M3918                      | [4f73764337](https://linux-hardware.org/?probe=4f73764337) | Mar 08, 2024 |
| ASUSTek       | PRIME B365M-K               | [343dc1071f](https://linux-hardware.org/?probe=343dc1071f) | Mar 08, 2024 |
| MSI           | B450M MORTAR MAX            | [f5af865ffc](https://linux-hardware.org/?probe=f5af865ffc) | Mar 07, 2024 |
| MSI           | Z390-A PRO                  | [47d746805d](https://linux-hardware.org/?probe=47d746805d) | Mar 07, 2024 |
| Unknown       | Unknown                     | [f582976129](https://linux-hardware.org/?probe=f582976129) | Mar 07, 2024 |
| HP            | 1589                        | [624b940448](https://linux-hardware.org/?probe=624b940448) | Mar 07, 2024 |
| MSI           | B450M MORTAR MAX            | [f9ed40afc2](https://linux-hardware.org/?probe=f9ed40afc2) | Mar 06, 2024 |
| ASUSTek       | P8Z77-M                     | [031b9032f6](https://linux-hardware.org/?probe=031b9032f6) | Mar 06, 2024 |
| Hardkernel    | ODROID-H3                   | [175145ad7c](https://linux-hardware.org/?probe=175145ad7c) | Mar 06, 2024 |
| Sapphire      | PI-AM3RS760G2               | [34c6283f00](https://linux-hardware.org/?probe=34c6283f00) | Mar 05, 2024 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [29b9dd14e6](https://linux-hardware.org/?probe=29b9dd14e6) | Mar 05, 2024 |
| Gigabyte      | H97M-HD3                    | [912c171bc5](https://linux-hardware.org/?probe=912c171bc5) | Mar 05, 2024 |
| HP            | ProLiant ML310e Gen8 v2     | [3b6afc68c7](https://linux-hardware.org/?probe=3b6afc68c7) | Mar 05, 2024 |
| BESSTAR Te... | HM80                        | [b0dd533b6a](https://linux-hardware.org/?probe=b0dd533b6a) | Mar 05, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [76317bf019](https://linux-hardware.org/?probe=76317bf019) | Mar 05, 2024 |
| Biostar       | M7MKB                       | [8d1cf151f7](https://linux-hardware.org/?probe=8d1cf151f7) | Mar 05, 2024 |
| Biostar       | M7MKB                       | [bd1260c783](https://linux-hardware.org/?probe=bd1260c783) | Mar 05, 2024 |
| ASUSTek       | P8H61-M PRO                 | [888ce42ec2](https://linux-hardware.org/?probe=888ce42ec2) | Mar 04, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4b55061676](https://linux-hardware.org/?probe=4b55061676) | Mar 04, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6cb53dc79e](https://linux-hardware.org/?probe=6cb53dc79e) | Mar 04, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | [7105302b8d](https://linux-hardware.org/?probe=7105302b8d) | Mar 04, 2024 |
| AZW           | Green G5                    | [0d917a5d84](https://linux-hardware.org/?probe=0d917a5d84) | Mar 04, 2024 |
| Acer          | Aspire X3960                | [ac6dc6f4ce](https://linux-hardware.org/?probe=ac6dc6f4ce) | Mar 04, 2024 |
| ASUSTek       | PRIME H510M-E               | [35d70301d6](https://linux-hardware.org/?probe=35d70301d6) | Mar 04, 2024 |
| ASUSTek       | P7H55-M SI                  | [b7775135ef](https://linux-hardware.org/?probe=b7775135ef) | Mar 04, 2024 |
| Lenovo        | 32E1 NOK                    | [f8482cdaa3](https://linux-hardware.org/?probe=f8482cdaa3) | Mar 04, 2024 |
| Unknown       | Unknown                     | [267b3b9397](https://linux-hardware.org/?probe=267b3b9397) | Mar 03, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [00190a62fa](https://linux-hardware.org/?probe=00190a62fa) | Mar 03, 2024 |
| ASUSTek       | PRIME A520M-E               | [42a2042f1d](https://linux-hardware.org/?probe=42a2042f1d) | Mar 03, 2024 |
| ASRock        | B760M Steel Legend WiFi     | [e693b43cc0](https://linux-hardware.org/?probe=e693b43cc0) | Mar 03, 2024 |
| Gigabyte      | GA-880GM-USB3L              | [61f2f3738a](https://linux-hardware.org/?probe=61f2f3738a) | Mar 03, 2024 |
| Gigabyte      | GA-880GM-USB3L              | [83e5cbff40](https://linux-hardware.org/?probe=83e5cbff40) | Mar 03, 2024 |
| Lenovo        | ThinkCentre M81 0385A2G     | [f66c00d744](https://linux-hardware.org/?probe=f66c00d744) | Mar 02, 2024 |
| Lenovo        | ThinkCentre M81 0385A2G     | [81dc4aff97](https://linux-hardware.org/?probe=81dc4aff97) | Mar 02, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [e36a1c7814](https://linux-hardware.org/?probe=e36a1c7814) | Mar 02, 2024 |
| MSI           | B450M PRO-M2                | [c7ea528f52](https://linux-hardware.org/?probe=c7ea528f52) | Mar 02, 2024 |
| MSI           | MAG B560M MORTAR WIFI       | [e1c6361be6](https://linux-hardware.org/?probe=e1c6361be6) | Mar 02, 2024 |
| MSI           | A320M-A PRO                 | [e69e7cf8f3](https://linux-hardware.org/?probe=e69e7cf8f3) | Mar 02, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [f526190f31](https://linux-hardware.org/?probe=f526190f31) | Mar 01, 2024 |
| ASRock        | H370M-ITX/ac                | [65085cd786](https://linux-hardware.org/?probe=65085cd786) | Mar 01, 2024 |
| Dell          | 0WMJ54 A01                  | [6678e6f966](https://linux-hardware.org/?probe=6678e6f966) | Mar 01, 2024 |
| Gigabyte      | X99-Gaming 5                | [0399ec813e](https://linux-hardware.org/?probe=0399ec813e) | Mar 01, 2024 |
| MSI           | B85M-G43                    | [07f9ba58d1](https://linux-hardware.org/?probe=07f9ba58d1) | Mar 01, 2024 |
| HP            | 1495                        | [ee01c60448](https://linux-hardware.org/?probe=ee01c60448) | Feb 29, 2024 |
| Intel         | DN2820FYK H24582-201        | [72aeddd030](https://linux-hardware.org/?probe=72aeddd030) | Feb 29, 2024 |
| ASUSTek       | Maximus III Formula         | [a81f1bdc21](https://linux-hardware.org/?probe=a81f1bdc21) | Feb 29, 2024 |
| Pegatron      | IPM41-D3                    | [5249318369](https://linux-hardware.org/?probe=5249318369) | Feb 29, 2024 |
| ASRock        | H410M-HDV                   | [36cc5fd948](https://linux-hardware.org/?probe=36cc5fd948) | Feb 29, 2024 |
| ECS           | BAT-I                       | [073ae6ee14](https://linux-hardware.org/?probe=073ae6ee14) | Feb 28, 2024 |
| ECS           | BAT-I                       | [df04815eeb](https://linux-hardware.org/?probe=df04815eeb) | Feb 28, 2024 |
| ASUSTek       | H81M-R                      | [b1b7cec12e](https://linux-hardware.org/?probe=b1b7cec12e) | Feb 28, 2024 |
| ECS           | BAT-I                       | [800d47cce0](https://linux-hardware.org/?probe=800d47cce0) | Feb 28, 2024 |
| ECS           | BAT-I                       | [ec66a61d5d](https://linux-hardware.org/?probe=ec66a61d5d) | Feb 28, 2024 |
| Inventec      | ZQ Class A02                | [5d17abe74b](https://linux-hardware.org/?probe=5d17abe74b) | Feb 28, 2024 |
| ASUSTek       | H81M-R                      | [5e67b3baca](https://linux-hardware.org/?probe=5e67b3baca) | Feb 28, 2024 |
| ECS           | BAT-I                       | [7851503e83](https://linux-hardware.org/?probe=7851503e83) | Feb 28, 2024 |
| ECS           | BAT-I                       | [2ae8282db0](https://linux-hardware.org/?probe=2ae8282db0) | Feb 28, 2024 |
| ASUSTek       | H81M-R                      | [f68c142e54](https://linux-hardware.org/?probe=f68c142e54) | Feb 28, 2024 |
| ASRock        | H81M-VG4 R2.0               | [3ece13ca96](https://linux-hardware.org/?probe=3ece13ca96) | Feb 28, 2024 |
| ASRock        | P5B-DE                      | [421ce59360](https://linux-hardware.org/?probe=421ce59360) | Feb 28, 2024 |
| ASUSTek       | TUF Z270 MARK 2             | [ae5155916f](https://linux-hardware.org/?probe=ae5155916f) | Feb 28, 2024 |
| Biostar       | G41D3C                      | [9717a25aa6](https://linux-hardware.org/?probe=9717a25aa6) | Feb 27, 2024 |
| Gigabyte      | H97-HD3                     | [d63757d6a3](https://linux-hardware.org/?probe=d63757d6a3) | Feb 27, 2024 |
| Gigabyte      | H61M-S1                     | [28003e844a](https://linux-hardware.org/?probe=28003e844a) | Feb 27, 2024 |
| ASUSTek       | M2N-E                       | [b3041e34a7](https://linux-hardware.org/?probe=b3041e34a7) | Feb 27, 2024 |
| Gigabyte      | A320M-S2H-CF                | [1c6d76b89e](https://linux-hardware.org/?probe=1c6d76b89e) | Feb 27, 2024 |
| ASUSTek       | P8H67-M                     | [fdbff4dbee](https://linux-hardware.org/?probe=fdbff4dbee) | Feb 27, 2024 |
| ASRock        | 990FX Extreme4              | [cd83a56af8](https://linux-hardware.org/?probe=cd83a56af8) | Feb 27, 2024 |
| ASUSTek       | Z170-A                      | [1501e42b01](https://linux-hardware.org/?probe=1501e42b01) | Feb 27, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | [57357cc10c](https://linux-hardware.org/?probe=57357cc10c) | Feb 27, 2024 |
| ASRock        | B450M Pro4-F                | [82ad67277f](https://linux-hardware.org/?probe=82ad67277f) | Feb 27, 2024 |
| Dell          | 0WR7PY A01                  | [b3cf18859d](https://linux-hardware.org/?probe=b3cf18859d) | Feb 26, 2024 |
| Dell          | 0WR7PY A01                  | [781e201621](https://linux-hardware.org/?probe=781e201621) | Feb 26, 2024 |
| MSI           | B365M PRO-VH                | [030fdfa47e](https://linux-hardware.org/?probe=030fdfa47e) | Feb 26, 2024 |
| HP            | 3646h                       | [0b7dd1d774](https://linux-hardware.org/?probe=0b7dd1d774) | Feb 26, 2024 |
| ECS           | G31T-M9                     | [7a01032f18](https://linux-hardware.org/?probe=7a01032f18) | Feb 26, 2024 |
| ECS           | G31T-M9                     | [1b5a1b2fbe](https://linux-hardware.org/?probe=1b5a1b2fbe) | Feb 26, 2024 |
| Gigabyte      | B85M-D3H                    | [fbce03b2f2](https://linux-hardware.org/?probe=fbce03b2f2) | Feb 26, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [16759c3ced](https://linux-hardware.org/?probe=16759c3ced) | Feb 26, 2024 |
| ASUSTek       | STRIX Z270G GAMING          | [8ad7f250df](https://linux-hardware.org/?probe=8ad7f250df) | Feb 25, 2024 |
| Unknown       | Unknown                     | [14c3da9627](https://linux-hardware.org/?probe=14c3da9627) | Feb 25, 2024 |
| ASUSTek       | M5A97 R2.0                  | [702dee066a](https://linux-hardware.org/?probe=702dee066a) | Feb 25, 2024 |
| ASRock        | X299 Taichi XE              | [521236e0a3](https://linux-hardware.org/?probe=521236e0a3) | Feb 25, 2024 |
| Dell          | 06D7TR A02                  | [3997e84bc6](https://linux-hardware.org/?probe=3997e84bc6) | Feb 25, 2024 |
| Shenzhen M... | F7BAA                       | [9be5a91625](https://linux-hardware.org/?probe=9be5a91625) | Feb 25, 2024 |
| Acer          | Aspire XC-105               | [ad7181f076](https://linux-hardware.org/?probe=ad7181f076) | Feb 25, 2024 |
| ASUSTek       | Q87M-E                      | [fde65d09e5](https://linux-hardware.org/?probe=fde65d09e5) | Feb 24, 2024 |
| Dell          | 0M3F6C A01                  | [a6d9ac4ceb](https://linux-hardware.org/?probe=a6d9ac4ceb) | Feb 24, 2024 |
| ASRock        | EP2C602-4L/D16              | [e6606b546e](https://linux-hardware.org/?probe=e6606b546e) | Feb 23, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [064fa8c5e8](https://linux-hardware.org/?probe=064fa8c5e8) | Feb 23, 2024 |
| Sapphire      | PI-AM3RS760G2               | [dc85539c15](https://linux-hardware.org/?probe=dc85539c15) | Feb 23, 2024 |
| MSI           | B450M PRO-M2                | [cb4de14dbc](https://linux-hardware.org/?probe=cb4de14dbc) | Feb 23, 2024 |
| ASUSTek       | PRIME B460M-A               | [faaab964ee](https://linux-hardware.org/?probe=faaab964ee) | Feb 22, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [81f080198e](https://linux-hardware.org/?probe=81f080198e) | Feb 22, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | [fff9712c8b](https://linux-hardware.org/?probe=fff9712c8b) | Feb 22, 2024 |
| Gigabyte      | B760M DS3H AX               | [a409a01e6a](https://linux-hardware.org/?probe=a409a01e6a) | Feb 22, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [973fbe0a55](https://linux-hardware.org/?probe=973fbe0a55) | Feb 22, 2024 |
| ASRock        | B450 Steel Legend           | [ed5e87fbaf](https://linux-hardware.org/?probe=ed5e87fbaf) | Feb 21, 2024 |
| Alienware     | 0PGRP5 A01                  | [4b1c4f1d09](https://linux-hardware.org/?probe=4b1c4f1d09) | Feb 21, 2024 |
| MSI           | PRO X670-P WIFI             | [0984d4145f](https://linux-hardware.org/?probe=0984d4145f) | Feb 21, 2024 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [9c3d65e57a](https://linux-hardware.org/?probe=9c3d65e57a) | Feb 21, 2024 |
| Unknown       | Lanner 1510                 | [5dc79bba04](https://linux-hardware.org/?probe=5dc79bba04) | Feb 21, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [e9af1989be](https://linux-hardware.org/?probe=e9af1989be) | Feb 21, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | [8e13111e3d](https://linux-hardware.org/?probe=8e13111e3d) | Feb 21, 2024 |
| ASUSTek       | P5LD2-SE                    | [0cf69dbca1](https://linux-hardware.org/?probe=0cf69dbca1) | Feb 21, 2024 |
| Dell          | 088DT1 A01                  | [2d163839aa](https://linux-hardware.org/?probe=2d163839aa) | Feb 21, 2024 |
| BESSTAR Te... | HM80                        | [ec826c4feb](https://linux-hardware.org/?probe=ec826c4feb) | Feb 20, 2024 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | [0dd2083acb](https://linux-hardware.org/?probe=0dd2083acb) | Feb 20, 2024 |
| ASUSTek       | VC66                        | [99329fa851](https://linux-hardware.org/?probe=99329fa851) | Feb 20, 2024 |
| Gowin Solu... | GW-MB-U01                   | [3705828f74](https://linux-hardware.org/?probe=3705828f74) | Feb 20, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [f8bb2afc13](https://linux-hardware.org/?probe=f8bb2afc13) | Feb 20, 2024 |
| Dell          | 0VRWRC A00                  | [6b3b3a204b](https://linux-hardware.org/?probe=6b3b3a204b) | Feb 19, 2024 |
| Dell          | 0VRWRC A00                  | [b19dc32aca](https://linux-hardware.org/?probe=b19dc32aca) | Feb 19, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [62c475de32](https://linux-hardware.org/?probe=62c475de32) | Feb 19, 2024 |
| ASUSTek       | Z170-A                      | [a14a54ac8f](https://linux-hardware.org/?probe=a14a54ac8f) | Feb 19, 2024 |
| MSI           | MS-B1711                    | [6c87a44b5e](https://linux-hardware.org/?probe=6c87a44b5e) | Feb 19, 2024 |
| HP            | 8299                        | [8ada04898c](https://linux-hardware.org/?probe=8ada04898c) | Feb 18, 2024 |
| ASRock        | B760M Steel Legend WiFi     | [189241b2a9](https://linux-hardware.org/?probe=189241b2a9) | Feb 18, 2024 |
| Gigabyte      | B450M DS3H-CF               | [36a49f2b71](https://linux-hardware.org/?probe=36a49f2b71) | Feb 18, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [4f55d722f7](https://linux-hardware.org/?probe=4f55d722f7) | Feb 18, 2024 |
| ASUSTek       | P8Z77-V LX                  | [dae19ec723](https://linux-hardware.org/?probe=dae19ec723) | Feb 18, 2024 |
| Dell          | 09430Y A00                  | [9f8d5462dc](https://linux-hardware.org/?probe=9f8d5462dc) | Feb 18, 2024 |
| Dell          | 09430Y A00                  | [6f65212b30](https://linux-hardware.org/?probe=6f65212b30) | Feb 18, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [a003d712e7](https://linux-hardware.org/?probe=a003d712e7) | Feb 18, 2024 |
| MSI           | FM2-A55M-E33                | [840f8a0855](https://linux-hardware.org/?probe=840f8a0855) | Feb 17, 2024 |
| Gowin Solu... | GW-MB-U01                   | [8f756612ce](https://linux-hardware.org/?probe=8f756612ce) | Feb 17, 2024 |
| Unknown       | KLX99                       | [f987799e6d](https://linux-hardware.org/?probe=f987799e6d) | Feb 17, 2024 |
| ASRock        | B760M Steel Legend WiFi     | [6307ab0c5c](https://linux-hardware.org/?probe=6307ab0c5c) | Feb 16, 2024 |
| Gigabyte      | H81M-S2PV                   | [db78c3ff86](https://linux-hardware.org/?probe=db78c3ff86) | Feb 16, 2024 |
| Acer          | Veriton M480                | [97843f7233](https://linux-hardware.org/?probe=97843f7233) | Feb 16, 2024 |
| Supermicro    | X9DR3-F                     | [1ce39d5a62](https://linux-hardware.org/?probe=1ce39d5a62) | Feb 16, 2024 |
| Dell          | 0WR7PY A01                  | [01a25cac2b](https://linux-hardware.org/?probe=01a25cac2b) | Feb 15, 2024 |
| ASRock        | G41M-VGS3                   | [f24334673c](https://linux-hardware.org/?probe=f24334673c) | Feb 15, 2024 |
| ASRock        | G41M-VGS3                   | [a997315810](https://linux-hardware.org/?probe=a997315810) | Feb 15, 2024 |
| Dell          | 05842Y A00                  | [50fc41ef5c](https://linux-hardware.org/?probe=50fc41ef5c) | Feb 15, 2024 |
| ASUSTek       | B85M-G                      | [cb455b8cc6](https://linux-hardware.org/?probe=cb455b8cc6) | Feb 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | [64bdaa6db8](https://linux-hardware.org/?probe=64bdaa6db8) | Feb 15, 2024 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [56739f7004](https://linux-hardware.org/?probe=56739f7004) | Feb 15, 2024 |
| Dell          | 0XR1GT A00                  | [df08346360](https://linux-hardware.org/?probe=df08346360) | Feb 14, 2024 |
| Dell          | 0XR1GT A00                  | [5e4e1c4000](https://linux-hardware.org/?probe=5e4e1c4000) | Feb 14, 2024 |
| Biostar       | B450NH                      | [973991e95a](https://linux-hardware.org/?probe=973991e95a) | Feb 14, 2024 |
| ASUSTek       | Z170-A                      | [6428e7d8bf](https://linux-hardware.org/?probe=6428e7d8bf) | Feb 14, 2024 |
| Gigabyte      | M52L-S3P                    | [342b394311](https://linux-hardware.org/?probe=342b394311) | Feb 13, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [a4297d40d4](https://linux-hardware.org/?probe=a4297d40d4) | Feb 13, 2024 |
| Gigabyte      | 970A-UD3P                   | [1c23d35f29](https://linux-hardware.org/?probe=1c23d35f29) | Feb 13, 2024 |
| ASUSTek       | B85M-G                      | [fb903aa2de](https://linux-hardware.org/?probe=fb903aa2de) | Feb 13, 2024 |
| Lenovo        | SHARKBAY NO DPK             | [e8c1265b41](https://linux-hardware.org/?probe=e8c1265b41) | Feb 13, 2024 |
| Gigabyte      | 970A-DS3P                   | [22194a7763](https://linux-hardware.org/?probe=22194a7763) | Feb 13, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [d8b81d94dd](https://linux-hardware.org/?probe=d8b81d94dd) | Feb 13, 2024 |
| Gigabyte      | Z97X-Gaming 5               | [e9061646f8](https://linux-hardware.org/?probe=e9061646f8) | Feb 12, 2024 |
| Sapphire      | PI-AM3RS760G2               | [da0c61667c](https://linux-hardware.org/?probe=da0c61667c) | Feb 12, 2024 |
| Acer          | EQ45M                       | [bccab98448](https://linux-hardware.org/?probe=bccab98448) | Feb 12, 2024 |
| Acer          | Veriton M480                | [808cfea21d](https://linux-hardware.org/?probe=808cfea21d) | Feb 12, 2024 |
| Acer          | EQ45M                       | [bd853978df](https://linux-hardware.org/?probe=bd853978df) | Feb 12, 2024 |
| Acer          | Veriton M480                | [70ea4ffae2](https://linux-hardware.org/?probe=70ea4ffae2) | Feb 12, 2024 |
| Acer          | Veriton S480G               | [91b73c9d95](https://linux-hardware.org/?probe=91b73c9d95) | Feb 12, 2024 |
| Acer          | Veriton M480                | [cd12d15067](https://linux-hardware.org/?probe=cd12d15067) | Feb 12, 2024 |
| Acer          | Veriton M480                | [3060b2b68d](https://linux-hardware.org/?probe=3060b2b68d) | Feb 12, 2024 |
| Acer          | Veriton M480                | [75068101a1](https://linux-hardware.org/?probe=75068101a1) | Feb 12, 2024 |
| Acer          | Veriton M480                | [f6093b20a9](https://linux-hardware.org/?probe=f6093b20a9) | Feb 12, 2024 |
| Acer          | Veriton M480                | [3865a5a78a](https://linux-hardware.org/?probe=3865a5a78a) | Feb 12, 2024 |
| ASRock        | 4Core1600-GLAN              | [18ede4bf05](https://linux-hardware.org/?probe=18ede4bf05) | Feb 12, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | [0fbc4b07a6](https://linux-hardware.org/?probe=0fbc4b07a6) | Feb 12, 2024 |
| YANYU         | EPIC-C19                    | [9a93a8fd98](https://linux-hardware.org/?probe=9a93a8fd98) | Feb 12, 2024 |
| ASUSTek       | M5A97 R2.0                  | [2ef5e51010](https://linux-hardware.org/?probe=2ef5e51010) | Feb 12, 2024 |
| HP            | 3646h                       | [8b68b9442a](https://linux-hardware.org/?probe=8b68b9442a) | Feb 11, 2024 |
| ASUSTek       | Z87M-PLUS                   | [8d1d5db604](https://linux-hardware.org/?probe=8d1d5db604) | Feb 11, 2024 |
| ASUSTek       | PRIME B560-PLUS             | [cd76bb2ee9](https://linux-hardware.org/?probe=cd76bb2ee9) | Feb 11, 2024 |
| Gigabyte      | Z77-HD3                     | [c89887925f](https://linux-hardware.org/?probe=c89887925f) | Feb 11, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [b899696a86](https://linux-hardware.org/?probe=b899696a86) | Feb 10, 2024 |
| Gowin Solu... | GW-MB-U01                   | [b4436f45a1](https://linux-hardware.org/?probe=b4436f45a1) | Feb 10, 2024 |
| Dell          | 08NPPY A00                  | [887c943a6c](https://linux-hardware.org/?probe=887c943a6c) | Feb 10, 2024 |
| NetGear       | ReadyNAS                    | [fa4ca7cbab](https://linux-hardware.org/?probe=fa4ca7cbab) | Feb 10, 2024 |
| Intel         | X99                         | [d4c2465bfe](https://linux-hardware.org/?probe=d4c2465bfe) | Feb 10, 2024 |
| Intel         | X99                         | [1fa5f7b075](https://linux-hardware.org/?probe=1fa5f7b075) | Feb 10, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e1cb948290](https://linux-hardware.org/?probe=e1cb948290) | Feb 10, 2024 |
| MSI           | X99S MPOWER                 | [b9b6a88d61](https://linux-hardware.org/?probe=b9b6a88d61) | Feb 10, 2024 |
| MSI           | PRO B550-VC                 | [22b2bb66f9](https://linux-hardware.org/?probe=22b2bb66f9) | Feb 09, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [7d3bc858b6](https://linux-hardware.org/?probe=7d3bc858b6) | Feb 09, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | [a0aee2033e](https://linux-hardware.org/?probe=a0aee2033e) | Feb 09, 2024 |
| Gigabyte      | GA-M56S-S3                  | [b4b56dd0e0](https://linux-hardware.org/?probe=b4b56dd0e0) | Feb 09, 2024 |
| HP            | 859C                        | [15a3365f93](https://linux-hardware.org/?probe=15a3365f93) | Feb 09, 2024 |
| Intel         | X99 V1.0                    | [225644e904](https://linux-hardware.org/?probe=225644e904) | Feb 09, 2024 |
| MSI           | H110M PRO-VD                | [ba8e24ef8f](https://linux-hardware.org/?probe=ba8e24ef8f) | Feb 08, 2024 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [2c485349d8](https://linux-hardware.org/?probe=2c485349d8) | Feb 08, 2024 |
| HP            | 1998                        | [5cac532a6d](https://linux-hardware.org/?probe=5cac532a6d) | Feb 08, 2024 |
| HP            | 212B                        | [720fcf3685](https://linux-hardware.org/?probe=720fcf3685) | Feb 08, 2024 |
| Gigabyte      | H61M-DS2                    | [b8e75e61a1](https://linux-hardware.org/?probe=b8e75e61a1) | Feb 08, 2024 |
| ASRock        | B760 Pro RS/D4              | [924b3da655](https://linux-hardware.org/?probe=924b3da655) | Feb 08, 2024 |
| Gigabyte      | EP31-DS3L                   | [17a3a784b0](https://linux-hardware.org/?probe=17a3a784b0) | Feb 08, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [03fbfca08c](https://linux-hardware.org/?probe=03fbfca08c) | Feb 08, 2024 |
| ECS           | H61H2-M13                   | [40ca590999](https://linux-hardware.org/?probe=40ca590999) | Feb 08, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [0ff4b6606b](https://linux-hardware.org/?probe=0ff4b6606b) | Feb 08, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [26ac3e2d7d](https://linux-hardware.org/?probe=26ac3e2d7d) | Feb 08, 2024 |
| ASUSTek       | PRIME H270M-PLUS            | [7956ad0720](https://linux-hardware.org/?probe=7956ad0720) | Feb 08, 2024 |
| Gigabyte      | M52L-S3P                    | [50564565d6](https://linux-hardware.org/?probe=50564565d6) | Feb 07, 2024 |
| ICP / iEi     | E338 V1.0                   | [df2c3919fe](https://linux-hardware.org/?probe=df2c3919fe) | Feb 07, 2024 |
| OEM           | X79G                        | [7eb9b85189](https://linux-hardware.org/?probe=7eb9b85189) | Feb 07, 2024 |
| ASUSTek       | P6X58D PREMIUM              | [e4feb283a2](https://linux-hardware.org/?probe=e4feb283a2) | Feb 07, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [9330504797](https://linux-hardware.org/?probe=9330504797) | Feb 07, 2024 |
| American M... | K7S41GX                     | [2ea09aff2d](https://linux-hardware.org/?probe=2ea09aff2d) | Feb 07, 2024 |
| ASRock        | G31M-GS                     | [50925f48af](https://linux-hardware.org/?probe=50925f48af) | Feb 06, 2024 |
| ASRock        | P45DE                       | [2dbcbb8483](https://linux-hardware.org/?probe=2dbcbb8483) | Feb 06, 2024 |
| ASUSTek       | PRIME B550M-A               | [fdc99fe4fa](https://linux-hardware.org/?probe=fdc99fe4fa) | Feb 06, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [51ac9437bb](https://linux-hardware.org/?probe=51ac9437bb) | Feb 06, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [c47a46ccaf](https://linux-hardware.org/?probe=c47a46ccaf) | Feb 06, 2024 |
| Gigabyte      | X570S AORUS ELITE           | [bb05e3b208](https://linux-hardware.org/?probe=bb05e3b208) | Feb 06, 2024 |
| ASUSTek       | F2A85-M                     | [fb9b1f2ddb](https://linux-hardware.org/?probe=fb9b1f2ddb) | Feb 05, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d8d66e42bc](https://linux-hardware.org/?probe=d8d66e42bc) | Feb 05, 2024 |
| HP            | 212B                        | [b3bc6c9d57](https://linux-hardware.org/?probe=b3bc6c9d57) | Feb 05, 2024 |
| HP            | 212B                        | [4ce740d8ad](https://linux-hardware.org/?probe=4ce740d8ad) | Feb 05, 2024 |
| HP            | 212B                        | [7ea5081cc7](https://linux-hardware.org/?probe=7ea5081cc7) | Feb 05, 2024 |
| HP            | 212B                        | [13dac46d00](https://linux-hardware.org/?probe=13dac46d00) | Feb 05, 2024 |
| HP            | 212B                        | [ca3ce84394](https://linux-hardware.org/?probe=ca3ce84394) | Feb 05, 2024 |
| HP            | 212B                        | [3e5dd21126](https://linux-hardware.org/?probe=3e5dd21126) | Feb 05, 2024 |
| HP            | 212B                        | [94722f627b](https://linux-hardware.org/?probe=94722f627b) | Feb 05, 2024 |
| HP            | 212B                        | [45ef556ddc](https://linux-hardware.org/?probe=45ef556ddc) | Feb 05, 2024 |
| HP            | 212B                        | [a289a17f37](https://linux-hardware.org/?probe=a289a17f37) | Feb 05, 2024 |
| ASRock        | H97 Pro4                    | [38b13ade3f](https://linux-hardware.org/?probe=38b13ade3f) | Feb 05, 2024 |
| Huanan        | X99-4MF V1.0                | [ea01d597b3](https://linux-hardware.org/?probe=ea01d597b3) | Feb 04, 2024 |
| ASUSTek       | P7H55D-M PRO                | [0a67d6191d](https://linux-hardware.org/?probe=0a67d6191d) | Feb 04, 2024 |
| HP            | 3399                        | [61695a8b90](https://linux-hardware.org/?probe=61695a8b90) | Feb 04, 2024 |
| ASRock        | Q1900B-ITX                  | [7b33d8adaf](https://linux-hardware.org/?probe=7b33d8adaf) | Feb 04, 2024 |
| ASRock        | Q1900B-ITX                  | [0e96f23985](https://linux-hardware.org/?probe=0e96f23985) | Feb 04, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f27df69b16](https://linux-hardware.org/?probe=f27df69b16) | Feb 03, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8a962ab826](https://linux-hardware.org/?probe=8a962ab826) | Feb 03, 2024 |
| ASUSTek       | Z170-A                      | [93f73b46ec](https://linux-hardware.org/?probe=93f73b46ec) | Feb 03, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [12a237d742](https://linux-hardware.org/?probe=12a237d742) | Feb 03, 2024 |
| ASUSTek       | PRIME A320M-K               | [dfa3229b6d](https://linux-hardware.org/?probe=dfa3229b6d) | Feb 03, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [c06ad0ce81](https://linux-hardware.org/?probe=c06ad0ce81) | Feb 03, 2024 |
| ASRock        | A520M-HDV                   | [dbc84495cb](https://linux-hardware.org/?probe=dbc84495cb) | Feb 03, 2024 |
| ASUSTek       | PRIME X570-PRO              | [8bc4248cea](https://linux-hardware.org/?probe=8bc4248cea) | Feb 03, 2024 |
| ASUSTek       | P5K                         | [9d9a5f3fd4](https://linux-hardware.org/?probe=9d9a5f3fd4) | Feb 03, 2024 |
| ASUSTek       | P7P55D-E                    | [7173101a68](https://linux-hardware.org/?probe=7173101a68) | Feb 02, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [ef41c12950](https://linux-hardware.org/?probe=ef41c12950) | Feb 02, 2024 |
| Sapphire      | PI-AM3RS760G2               | [9b2e938cb4](https://linux-hardware.org/?probe=9b2e938cb4) | Feb 02, 2024 |
| Gigabyte      | B560M H                     | [84e64db583](https://linux-hardware.org/?probe=84e64db583) | Feb 02, 2024 |
| ASRock        | 990FX Extreme4              | [b412a671e4](https://linux-hardware.org/?probe=b412a671e4) | Feb 02, 2024 |
| Lenovo        | 312A NOK                    | [366174cd75](https://linux-hardware.org/?probe=366174cd75) | Feb 02, 2024 |
| HP            | 1998                        | [0056c33526](https://linux-hardware.org/?probe=0056c33526) | Feb 02, 2024 |
| Lenovo        | SHARKBAY NOK                | [f4caef7bf1](https://linux-hardware.org/?probe=f4caef7bf1) | Feb 02, 2024 |
| Dell          | 0G214D A00                  | [2973076de3](https://linux-hardware.org/?probe=2973076de3) | Feb 01, 2024 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [763dd9417b](https://linux-hardware.org/?probe=763dd9417b) | Jan 31, 2024 |
| Gigabyte      | B85M-D3H                    | [059252dc92](https://linux-hardware.org/?probe=059252dc92) | Jan 31, 2024 |
| Dell          | 018D1Y A00                  | [28a3a41219](https://linux-hardware.org/?probe=28a3a41219) | Jan 31, 2024 |
| ASRock        | X99 Taichi                  | [1799faad1e](https://linux-hardware.org/?probe=1799faad1e) | Jan 31, 2024 |
| Unknown       | T3 MRD                      | [744984b9d3](https://linux-hardware.org/?probe=744984b9d3) | Jan 31, 2024 |
| ASUSTek       | PRIME A320M-K               | [348cad0405](https://linux-hardware.org/?probe=348cad0405) | Jan 31, 2024 |
| MSI           | H110M PRO-VD                | [29fd183b3b](https://linux-hardware.org/?probe=29fd183b3b) | Jan 31, 2024 |
| ASRock        | A520M-HDV                   | [fa42ae183a](https://linux-hardware.org/?probe=fa42ae183a) | Jan 31, 2024 |
| ASRock        | A520M-HDV                   | [23be9724fe](https://linux-hardware.org/?probe=23be9724fe) | Jan 31, 2024 |
| Lenovo        | 312A NOK                    | [4cb29324fc](https://linux-hardware.org/?probe=4cb29324fc) | Jan 30, 2024 |
| HP            | 1495                        | [a2017adb28](https://linux-hardware.org/?probe=a2017adb28) | Jan 30, 2024 |
| ASUSTek       | B85M-E/BR                   | [d3a20c90d1](https://linux-hardware.org/?probe=d3a20c90d1) | Jan 30, 2024 |
| Lenovo        | 312A NOK                    | [dea06ca305](https://linux-hardware.org/?probe=dea06ca305) | Jan 30, 2024 |
| Lenovo        | 312A NOK                    | [83eec08588](https://linux-hardware.org/?probe=83eec08588) | Jan 30, 2024 |
| ASRock        | 990FX Extreme4              | [dbb897d3e1](https://linux-hardware.org/?probe=dbb897d3e1) | Jan 30, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [e5435a9682](https://linux-hardware.org/?probe=e5435a9682) | Jan 30, 2024 |
| Dell          | 0D4MD1 A00                  | [9dd5ab2544](https://linux-hardware.org/?probe=9dd5ab2544) | Jan 30, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [141329c8f3](https://linux-hardware.org/?probe=141329c8f3) | Jan 29, 2024 |
| Huanan        | X99-4MF V1.0                | [63f228ae04](https://linux-hardware.org/?probe=63f228ae04) | Jan 29, 2024 |
| Shenzhen M... | F6BFC                       | [3ecbf7ef23](https://linux-hardware.org/?probe=3ecbf7ef23) | Jan 29, 2024 |
| HP            | 3397                        | [fcbc5b3ac6](https://linux-hardware.org/?probe=fcbc5b3ac6) | Jan 29, 2024 |
| ASRock        | X300TM-ITX                  | [c3277a6c4c](https://linux-hardware.org/?probe=c3277a6c4c) | Jan 29, 2024 |
| MSI           | MS-7060                     | [cfc1584314](https://linux-hardware.org/?probe=cfc1584314) | Jan 29, 2024 |
| HP            | 1495                        | [2bf6b5d794](https://linux-hardware.org/?probe=2bf6b5d794) | Jan 28, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [e4b1d774f6](https://linux-hardware.org/?probe=e4b1d774f6) | Jan 28, 2024 |
| Intel         | DX58SO AAE29331-503         | [57959fa365](https://linux-hardware.org/?probe=57959fa365) | Jan 28, 2024 |
| ASUSTek       | PRIME X570-P                | [0b1a4a9d6c](https://linux-hardware.org/?probe=0b1a4a9d6c) | Jan 28, 2024 |
| ASUSTek       | PRIME B250M-C               | [5c34879ea0](https://linux-hardware.org/?probe=5c34879ea0) | Jan 28, 2024 |
| ASRock        | B550M Phantom Gaming 4      | [19712e098a](https://linux-hardware.org/?probe=19712e098a) | Jan 28, 2024 |
| ASUSTek       | Z97-K                       | [777446f160](https://linux-hardware.org/?probe=777446f160) | Jan 28, 2024 |
| Gateway       | DS10G                       | [869339de12](https://linux-hardware.org/?probe=869339de12) | Jan 28, 2024 |
| Unknown       | Unknown                     | [52ae8cfe76](https://linux-hardware.org/?probe=52ae8cfe76) | Jan 28, 2024 |
| Unknown       | Unknown                     | [1834dd7444](https://linux-hardware.org/?probe=1834dd7444) | Jan 28, 2024 |
| Gigabyte      | H61M-D2-B3                  | [a177c22fb5](https://linux-hardware.org/?probe=a177c22fb5) | Jan 28, 2024 |
| ASUSTek       | PRIME A320M-K               | [c5777be509](https://linux-hardware.org/?probe=c5777be509) | Jan 28, 2024 |
| ASUSTek       | PRIME A320M-K               | [4fa63d205f](https://linux-hardware.org/?probe=4fa63d205f) | Jan 28, 2024 |
| HP            | 21EF                        | [9fcfe8d663](https://linux-hardware.org/?probe=9fcfe8d663) | Jan 28, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [08f64cc902](https://linux-hardware.org/?probe=08f64cc902) | Jan 27, 2024 |
| Dell          | 042P49 A01                  | [c419b892e0](https://linux-hardware.org/?probe=c419b892e0) | Jan 27, 2024 |
| Unknown       | Unknown                     | [2bf1eac05d](https://linux-hardware.org/?probe=2bf1eac05d) | Jan 27, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [a6240580d2](https://linux-hardware.org/?probe=a6240580d2) | Jan 27, 2024 |
| Biostar       | A10N-8800E                  | [6035efec56](https://linux-hardware.org/?probe=6035efec56) | Jan 27, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [48d7c58756](https://linux-hardware.org/?probe=48d7c58756) | Jan 27, 2024 |
| Biostar       | A10N-8800E                  | [9eab4dee46](https://linux-hardware.org/?probe=9eab4dee46) | Jan 27, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [ff65cf66c3](https://linux-hardware.org/?probe=ff65cf66c3) | Jan 27, 2024 |
| Medion        | MS-7616                     | [3645021c62](https://linux-hardware.org/?probe=3645021c62) | Jan 27, 2024 |
| Gigabyte      | A520M DS3H V2               | [507d3e9bbf](https://linux-hardware.org/?probe=507d3e9bbf) | Jan 27, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f7b37dcead](https://linux-hardware.org/?probe=f7b37dcead) | Jan 27, 2024 |
| HC Technol... | HCAR5000-MI2                | [19a4048799](https://linux-hardware.org/?probe=19a4048799) | Jan 27, 2024 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [b0019abd70](https://linux-hardware.org/?probe=b0019abd70) | Jan 26, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [fcdc8fc8e3](https://linux-hardware.org/?probe=fcdc8fc8e3) | Jan 26, 2024 |
| ASUSTek       | Z87-C                       | [a63ba339e5](https://linux-hardware.org/?probe=a63ba339e5) | Jan 26, 2024 |
| ASUSTek       | PRIME X570-P                | [f0eb2463d7](https://linux-hardware.org/?probe=f0eb2463d7) | Jan 26, 2024 |
| ECS           | G31T-M9                     | [8af1e631e7](https://linux-hardware.org/?probe=8af1e631e7) | Jan 26, 2024 |
| MSI           | G31M3 V2                    | [b98a012c0e](https://linux-hardware.org/?probe=b98a012c0e) | Jan 26, 2024 |
| Gigabyte      | H81M-S2V                    | [42abec13ac](https://linux-hardware.org/?probe=42abec13ac) | Jan 26, 2024 |
| HP            | 2AAC                        | [d397b1b3b3](https://linux-hardware.org/?probe=d397b1b3b3) | Jan 26, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [431bc1335a](https://linux-hardware.org/?probe=431bc1335a) | Jan 26, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [c9df4c296f](https://linux-hardware.org/?probe=c9df4c296f) | Jan 26, 2024 |
| ASRock        | 990FX Extreme4              | [80c0bacde5](https://linux-hardware.org/?probe=80c0bacde5) | Jan 25, 2024 |
| ASRock        | 990FX Extreme4              | [70a0ef842a](https://linux-hardware.org/?probe=70a0ef842a) | Jan 25, 2024 |
| Unknown       | Unknown                     | [a1cdf62b17](https://linux-hardware.org/?probe=a1cdf62b17) | Jan 25, 2024 |
| Unknown       | Unknown                     | [a743ba7b8b](https://linux-hardware.org/?probe=a743ba7b8b) | Jan 24, 2024 |
| ECS           | G31T-M9                     | [87e9fbf4fd](https://linux-hardware.org/?probe=87e9fbf4fd) | Jan 24, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [298f2d1380](https://linux-hardware.org/?probe=298f2d1380) | Jan 24, 2024 |
| ASRock        | G31M-GS                     | [8c46163f5c](https://linux-hardware.org/?probe=8c46163f5c) | Jan 24, 2024 |
| ASRock        | G31M-GS                     | [dbe6d0fdd4](https://linux-hardware.org/?probe=dbe6d0fdd4) | Jan 24, 2024 |
| Foxconn       | G33M03                      | [dd33710847](https://linux-hardware.org/?probe=dd33710847) | Jan 24, 2024 |
| ASUSTek       | P7H55-M LE                  | [a864af0be4](https://linux-hardware.org/?probe=a864af0be4) | Jan 24, 2024 |
| Gigabyte      | H55M-UD2H                   | [10c2d49a41](https://linux-hardware.org/?probe=10c2d49a41) | Jan 24, 2024 |
| Foxconn       | G33M03                      | [bd9087ac07](https://linux-hardware.org/?probe=bd9087ac07) | Jan 24, 2024 |
| ASUSTek       | H110M-R                     | [7ed41d411e](https://linux-hardware.org/?probe=7ed41d411e) | Jan 24, 2024 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [0dc2ae0570](https://linux-hardware.org/?probe=0dc2ae0570) | Jan 24, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [8b61369e83](https://linux-hardware.org/?probe=8b61369e83) | Jan 24, 2024 |
| Gigabyte      | H61M-S1                     | [b0ac9a9edd](https://linux-hardware.org/?probe=b0ac9a9edd) | Jan 24, 2024 |
| HP            | 158B                        | [d433cc30c0](https://linux-hardware.org/?probe=d433cc30c0) | Jan 23, 2024 |
| ASUSTek       | Pro WS 565-ACE              | [46ef259c25](https://linux-hardware.org/?probe=46ef259c25) | Jan 23, 2024 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [6887beeb2a](https://linux-hardware.org/?probe=6887beeb2a) | Jan 23, 2024 |
| ASUSTek       | M2N-E SLI                   | [113665efbe](https://linux-hardware.org/?probe=113665efbe) | Jan 23, 2024 |
| Gigabyte      | H61M-D2-B3                  | [a8315f32a0](https://linux-hardware.org/?probe=a8315f32a0) | Jan 23, 2024 |
| ASUSTek       | B150-PRO D3                 | [1f8cd5afac](https://linux-hardware.org/?probe=1f8cd5afac) | Jan 23, 2024 |
| ASRock        | 990FX Extreme4              | [1a19df4d59](https://linux-hardware.org/?probe=1a19df4d59) | Jan 23, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [70551a607e](https://linux-hardware.org/?probe=70551a607e) | Jan 23, 2024 |
| ASRock        | 970M Pro3                   | [f5a09bd7f0](https://linux-hardware.org/?probe=f5a09bd7f0) | Jan 23, 2024 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [f265beb810](https://linux-hardware.org/?probe=f265beb810) | Jan 22, 2024 |
| Intel         | DX58SO AAE29331-503         | [ed61279750](https://linux-hardware.org/?probe=ed61279750) | Jan 22, 2024 |
| MSI           | MEG X570 ACE                | [85c7d79003](https://linux-hardware.org/?probe=85c7d79003) | Jan 22, 2024 |
| ASUSTek       | J1800I-C                    | [6adb9446f3](https://linux-hardware.org/?probe=6adb9446f3) | Jan 22, 2024 |
| ASUSTek       | H81M-R                      | [dd7840e283](https://linux-hardware.org/?probe=dd7840e283) | Jan 22, 2024 |
| MSI           | MPG B460I GAMING EDGE WI... | [2449b6b678](https://linux-hardware.org/?probe=2449b6b678) | Jan 22, 2024 |
| Inventec      | D CLASS A02                 | [25d4886028](https://linux-hardware.org/?probe=25d4886028) | Jan 22, 2024 |
| HC            | HCAR357-MI V1.0             | [1f15fb2119](https://linux-hardware.org/?probe=1f15fb2119) | Jan 22, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [d2c27751fe](https://linux-hardware.org/?probe=d2c27751fe) | Jan 22, 2024 |
| ASRock        | H61M-HVS                    | [3cfc574d2d](https://linux-hardware.org/?probe=3cfc574d2d) | Jan 22, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | [24555759ee](https://linux-hardware.org/?probe=24555759ee) | Jan 22, 2024 |
| MSI           | MS-B1711                    | [0949139f7e](https://linux-hardware.org/?probe=0949139f7e) | Jan 22, 2024 |
| MSI           | PRO B760M-P DDR4            | [75f120a935](https://linux-hardware.org/?probe=75f120a935) | Jan 21, 2024 |
| ASRock        | 990FX Extreme4              | [5722aa300f](https://linux-hardware.org/?probe=5722aa300f) | Jan 21, 2024 |
| MACHINIST     | X99 PR9                     | [2cac18e4ae](https://linux-hardware.org/?probe=2cac18e4ae) | Jan 21, 2024 |
| ASRock        | 990FX Extreme4              | [bc8248af06](https://linux-hardware.org/?probe=bc8248af06) | Jan 21, 2024 |
| Gigabyte      | 945GZM-S2                   | [41c285445b](https://linux-hardware.org/?probe=41c285445b) | Jan 21, 2024 |
| Unknown       | Unknown                     | [8e5e6256ee](https://linux-hardware.org/?probe=8e5e6256ee) | Jan 21, 2024 |
| ASRock        | 990FX Extreme4              | [17f186ad10](https://linux-hardware.org/?probe=17f186ad10) | Jan 20, 2024 |
| Unknown       | Unknown                     | [98da52d37e](https://linux-hardware.org/?probe=98da52d37e) | Jan 20, 2024 |
| Gigabyte      | H110M-S2H-CF                | [d57cdb4371](https://linux-hardware.org/?probe=d57cdb4371) | Jan 20, 2024 |
| ASUSTek       | PRIME B450M-K               | [5e16786940](https://linux-hardware.org/?probe=5e16786940) | Jan 20, 2024 |
| ASRock        | 970M Pro3                   | [37613f1ec6](https://linux-hardware.org/?probe=37613f1ec6) | Jan 20, 2024 |
| IBM           | 830381U                     | [8af6dd9c05](https://linux-hardware.org/?probe=8af6dd9c05) | Jan 20, 2024 |
| ASRock        | N100DC-ITX                  | [dbca9c4ba2](https://linux-hardware.org/?probe=dbca9c4ba2) | Jan 19, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [a77218f826](https://linux-hardware.org/?probe=a77218f826) | Jan 19, 2024 |
| Gigabyte      | B250M-DS3H-CF               | [b4073d28df](https://linux-hardware.org/?probe=b4073d28df) | Jan 19, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e62243f63a](https://linux-hardware.org/?probe=e62243f63a) | Jan 19, 2024 |
| Intel         | DH77EB AAG39073-304         | [6c6bbd8cc8](https://linux-hardware.org/?probe=6c6bbd8cc8) | Jan 19, 2024 |
| Dell          | 0YJMC0 A02                  | [6dcdea7ca2](https://linux-hardware.org/?probe=6dcdea7ca2) | Jan 19, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [d64ba116db](https://linux-hardware.org/?probe=d64ba116db) | Jan 19, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [5b5d90211c](https://linux-hardware.org/?probe=5b5d90211c) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [a8adaf0c17](https://linux-hardware.org/?probe=a8adaf0c17) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [26510e18f5](https://linux-hardware.org/?probe=26510e18f5) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [4ca7c404f0](https://linux-hardware.org/?probe=4ca7c404f0) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [a2967a1948](https://linux-hardware.org/?probe=a2967a1948) | Jan 18, 2024 |
| Gigabyte      | H610M H DDR4                | [1d9bce4a06](https://linux-hardware.org/?probe=1d9bce4a06) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [a0c4c6c96a](https://linux-hardware.org/?probe=a0c4c6c96a) | Jan 18, 2024 |
| ASUSTek       | PRIME H310M-E               | [6674d084a8](https://linux-hardware.org/?probe=6674d084a8) | Jan 18, 2024 |
| Grandstrea... | T3 MRD                      | [21c38a3719](https://linux-hardware.org/?probe=21c38a3719) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [900d299461](https://linux-hardware.org/?probe=900d299461) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [56d6cc2713](https://linux-hardware.org/?probe=56d6cc2713) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [3bc6ca5cba](https://linux-hardware.org/?probe=3bc6ca5cba) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [a71b94ef53](https://linux-hardware.org/?probe=a71b94ef53) | Jan 18, 2024 |
| ASRock        | H61M                        | [653436b855](https://linux-hardware.org/?probe=653436b855) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [01d717f8fc](https://linux-hardware.org/?probe=01d717f8fc) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [12129124f0](https://linux-hardware.org/?probe=12129124f0) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [6ebd6d855d](https://linux-hardware.org/?probe=6ebd6d855d) | Jan 18, 2024 |
| ASUSTek       | P5QL-CM                     | [362052b28a](https://linux-hardware.org/?probe=362052b28a) | Jan 18, 2024 |
| OEM           | X79G                        | [992b83b632](https://linux-hardware.org/?probe=992b83b632) | Jan 18, 2024 |
| HP            | 1495                        | [0e16d785bc](https://linux-hardware.org/?probe=0e16d785bc) | Jan 18, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [9cea75cc3c](https://linux-hardware.org/?probe=9cea75cc3c) | Jan 18, 2024 |
| MSI           | PRO Z790-A WIFI             | [9c84b7f26a](https://linux-hardware.org/?probe=9c84b7f26a) | Jan 17, 2024 |
| HP            | 82A2                        | [2d14e52635](https://linux-hardware.org/?probe=2d14e52635) | Jan 17, 2024 |
| SYWZ          | S210H Series                | [b918a28247](https://linux-hardware.org/?probe=b918a28247) | Jan 17, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [2b7eda6458](https://linux-hardware.org/?probe=2b7eda6458) | Jan 17, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [f5e8165d7b](https://linux-hardware.org/?probe=f5e8165d7b) | Jan 17, 2024 |
| ASRock        | 990FX Extreme4              | [99bcba4ae3](https://linux-hardware.org/?probe=99bcba4ae3) | Jan 17, 2024 |
| Intel         | DH77KC AAG39641-400         | [b9c3c9837d](https://linux-hardware.org/?probe=b9c3c9837d) | Jan 17, 2024 |
| IBM           | 830381U                     | [114d68f889](https://linux-hardware.org/?probe=114d68f889) | Jan 17, 2024 |
| ASUSTek       | PRIME A320M-K               | [832ff6a79d](https://linux-hardware.org/?probe=832ff6a79d) | Jan 16, 2024 |
| HP            | ProLiant ML310e Gen8 v2     | [75c345abd6](https://linux-hardware.org/?probe=75c345abd6) | Jan 16, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [60694d3668](https://linux-hardware.org/?probe=60694d3668) | Jan 16, 2024 |
| ASUSTek       | P5Q SE2                     | [e357bf8b25](https://linux-hardware.org/?probe=e357bf8b25) | Jan 16, 2024 |
| ASRock        | 990FX Extreme4              | [196ce97a62](https://linux-hardware.org/?probe=196ce97a62) | Jan 16, 2024 |
| Gigabyte      | B560M DS3H V2               | [01f214a86d](https://linux-hardware.org/?probe=01f214a86d) | Jan 15, 2024 |
| ASRock        | 990FX Extreme4              | [bf7672b4a4](https://linux-hardware.org/?probe=bf7672b4a4) | Jan 15, 2024 |
| HP            | 8105                        | [003cac54c4](https://linux-hardware.org/?probe=003cac54c4) | Jan 15, 2024 |
| HP            | 8062                        | [58b81c8ab8](https://linux-hardware.org/?probe=58b81c8ab8) | Jan 15, 2024 |
| HP            | 8105                        | [36e0151976](https://linux-hardware.org/?probe=36e0151976) | Jan 15, 2024 |
| HP            | 8062                        | [9ff293cb06](https://linux-hardware.org/?probe=9ff293cb06) | Jan 15, 2024 |
| HP            | 8105                        | [2ee1b30f19](https://linux-hardware.org/?probe=2ee1b30f19) | Jan 15, 2024 |
| HP            | 8062                        | [64be9fb79c](https://linux-hardware.org/?probe=64be9fb79c) | Jan 15, 2024 |
| HP            | 8062                        | [502adc9396](https://linux-hardware.org/?probe=502adc9396) | Jan 15, 2024 |
| HP            | 8105                        | [142985ca4f](https://linux-hardware.org/?probe=142985ca4f) | Jan 15, 2024 |
| HP            | 8105                        | [aa402dfc3b](https://linux-hardware.org/?probe=aa402dfc3b) | Jan 15, 2024 |
| HP            | 8105                        | [f508c2b4c4](https://linux-hardware.org/?probe=f508c2b4c4) | Jan 15, 2024 |
| HP            | 8105                        | [eb9adb982e](https://linux-hardware.org/?probe=eb9adb982e) | Jan 15, 2024 |
| HP            | 8105                        | [fc6c21da40](https://linux-hardware.org/?probe=fc6c21da40) | Jan 15, 2024 |
| MSI           | B450M MORTAR MAX            | [6ddfddee65](https://linux-hardware.org/?probe=6ddfddee65) | Jan 15, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | [8c2cab8ef9](https://linux-hardware.org/?probe=8c2cab8ef9) | Jan 15, 2024 |
| Gigabyte      | B550M AORUS PRO             | [a91d050e76](https://linux-hardware.org/?probe=a91d050e76) | Jan 15, 2024 |
| ASRock        | 990FX Extreme4              | [8a02dab1f4](https://linux-hardware.org/?probe=8a02dab1f4) | Jan 15, 2024 |
| ASUSTek       | PRIME A320M-K               | [2ce7044dec](https://linux-hardware.org/?probe=2ce7044dec) | Jan 15, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [236dc2d07a](https://linux-hardware.org/?probe=236dc2d07a) | Jan 15, 2024 |
| ASRock        | J5040-ITX                   | [1d65e65b24](https://linux-hardware.org/?probe=1d65e65b24) | Jan 14, 2024 |
| AZW           | EQ MINI 10                  | [e702ea54ea](https://linux-hardware.org/?probe=e702ea54ea) | Jan 14, 2024 |
| T-bao Tian... | GOD78                       | [c2f6e2c9e1](https://linux-hardware.org/?probe=c2f6e2c9e1) | Jan 14, 2024 |
| ASRock        | 990FX Extreme4              | [cb5bd1f14f](https://linux-hardware.org/?probe=cb5bd1f14f) | Jan 14, 2024 |
| ASUSTek       | ET1610PT                    | [f71bcea580](https://linux-hardware.org/?probe=f71bcea580) | Jan 14, 2024 |
| ASRock        | 990FX Extreme4              | [439b30f633](https://linux-hardware.org/?probe=439b30f633) | Jan 14, 2024 |
| ASRock        | C2750D4I                    | [c1426b3157](https://linux-hardware.org/?probe=c1426b3157) | Jan 14, 2024 |
| ASRock        | Z68 Extreme3 Gen3           | [9bc7ba0294](https://linux-hardware.org/?probe=9bc7ba0294) | Jan 14, 2024 |
| ASRock        | 990FX Extreme4              | [35533bf402](https://linux-hardware.org/?probe=35533bf402) | Jan 14, 2024 |
| ASUSTek       | PRIME B550M-K               | [3b6eae725e](https://linux-hardware.org/?probe=3b6eae725e) | Jan 13, 2024 |
| ASRock        | 990FX Extreme4              | [783185e5af](https://linux-hardware.org/?probe=783185e5af) | Jan 13, 2024 |
| ASRock        | 990FX Extreme4              | [1742e2e526](https://linux-hardware.org/?probe=1742e2e526) | Jan 13, 2024 |
| ASRock        | 990FX Extreme4              | [43ceb02173](https://linux-hardware.org/?probe=43ceb02173) | Jan 13, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [58771677c3](https://linux-hardware.org/?probe=58771677c3) | Jan 13, 2024 |
| Gigabyte      | B450M S2H                   | [f29e741e2b](https://linux-hardware.org/?probe=f29e741e2b) | Jan 13, 2024 |
| ASRock        | 990FX Extreme4              | [6adea77d15](https://linux-hardware.org/?probe=6adea77d15) | Jan 13, 2024 |
| ASUSTek       | Z87-C                       | [acc914cabd](https://linux-hardware.org/?probe=acc914cabd) | Jan 12, 2024 |
| Biostar       | A320MH                      | [5bec64f55c](https://linux-hardware.org/?probe=5bec64f55c) | Jan 12, 2024 |
| ASRock        | 990FX Extreme4              | [cde9d2553f](https://linux-hardware.org/?probe=cde9d2553f) | Jan 12, 2024 |
| ASRock        | 990FX Extreme4              | [6c82d498ba](https://linux-hardware.org/?probe=6c82d498ba) | Jan 12, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e73c5fda0f](https://linux-hardware.org/?probe=e73c5fda0f) | Jan 12, 2024 |
| HP            | 339A                        | [75faedbb21](https://linux-hardware.org/?probe=75faedbb21) | Jan 12, 2024 |
| Dell          | 0F6X5P A00                  | [bf6a022632](https://linux-hardware.org/?probe=bf6a022632) | Jan 12, 2024 |
| Dell          | 0F6X5P A00                  | [8d2b313d2a](https://linux-hardware.org/?probe=8d2b313d2a) | Jan 12, 2024 |
| Dell          | 0F6X5P A00                  | [6f7cf4ae8d](https://linux-hardware.org/?probe=6f7cf4ae8d) | Jan 12, 2024 |
| ASUSTek       | PRIME B350M-A               | [7eabdfe5d0](https://linux-hardware.org/?probe=7eabdfe5d0) | Jan 12, 2024 |
| HP            | 0B4Ch D                     | [d04339c0dc](https://linux-hardware.org/?probe=d04339c0dc) | Jan 12, 2024 |
| MSI           | H110M PRO-VD                | [10efa0c4e5](https://linux-hardware.org/?probe=10efa0c4e5) | Jan 12, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [95c2b6739c](https://linux-hardware.org/?probe=95c2b6739c) | Jan 12, 2024 |
| ASUSTek       | PRIME B360M-A               | [5fb795a75b](https://linux-hardware.org/?probe=5fb795a75b) | Jan 12, 2024 |
| Lenovo        | SHARKBAY NOK                | [1ece67bdd1](https://linux-hardware.org/?probe=1ece67bdd1) | Jan 12, 2024 |
| MSI           | MS-7318                     | [58f55e6bd3](https://linux-hardware.org/?probe=58f55e6bd3) | Jan 11, 2024 |
| Gigabyte      | H77N-WIFI                   | [aeb566949b](https://linux-hardware.org/?probe=aeb566949b) | Jan 11, 2024 |
| Gigabyte      | MFLP5IP-00                  | [82e2bfd859](https://linux-hardware.org/?probe=82e2bfd859) | Jan 11, 2024 |
| HP            | ProLiant ML310e Gen8 v2     | [d6e4987996](https://linux-hardware.org/?probe=d6e4987996) | Jan 11, 2024 |
| Gigabyte      | GA-M56S-S3                  | [77af17feec](https://linux-hardware.org/?probe=77af17feec) | Jan 11, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [53c94d0753](https://linux-hardware.org/?probe=53c94d0753) | Jan 11, 2024 |
| Phoenix       | 945GM                       | [12f56a36d9](https://linux-hardware.org/?probe=12f56a36d9) | Jan 11, 2024 |
| MSI           | Z97S SLI Krait Edition      | [24a9b78491](https://linux-hardware.org/?probe=24a9b78491) | Jan 11, 2024 |
| MSI           | MS-B1711                    | [dc032b6456](https://linux-hardware.org/?probe=dc032b6456) | Jan 11, 2024 |
| HP            | 8767 A                      | [b8a28f8c5f](https://linux-hardware.org/?probe=b8a28f8c5f) | Jan 10, 2024 |
| Gigabyte      | A520M K V2                  | [3485cdf9ff](https://linux-hardware.org/?probe=3485cdf9ff) | Jan 10, 2024 |
| ASRock        | 990FX Extreme4              | [975fff0a28](https://linux-hardware.org/?probe=975fff0a28) | Jan 10, 2024 |
| ASRock        | 990FX Extreme4              | [4d91095fa0](https://linux-hardware.org/?probe=4d91095fa0) | Jan 10, 2024 |
| Gigabyte      | A520M K V2                  | [2f7bb41141](https://linux-hardware.org/?probe=2f7bb41141) | Jan 10, 2024 |
| ASRock        | 990FX Extreme4              | [6909d543b0](https://linux-hardware.org/?probe=6909d543b0) | Jan 10, 2024 |
| Medion        | MS-7616                     | [c8a2c8be49](https://linux-hardware.org/?probe=c8a2c8be49) | Jan 10, 2024 |
| newplatfor... | NP-1008i.1                  | [3da4bb5017](https://linux-hardware.org/?probe=3da4bb5017) | Jan 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | [e08d38f8a0](https://linux-hardware.org/?probe=e08d38f8a0) | Jan 09, 2024 |
| ASRock        | 990FX Extreme4              | [a3fa43281d](https://linux-hardware.org/?probe=a3fa43281d) | Jan 09, 2024 |
| Intel         | X99H                        | [b0bb3cb105](https://linux-hardware.org/?probe=b0bb3cb105) | Jan 09, 2024 |
| Dell          | 00V62H A01                  | [6f8302ddde](https://linux-hardware.org/?probe=6f8302ddde) | Jan 08, 2024 |
| ASRock        | 990FX Extreme4              | [ddc21e0978](https://linux-hardware.org/?probe=ddc21e0978) | Jan 08, 2024 |
| HP            | 8105                        | [ff8505bc17](https://linux-hardware.org/?probe=ff8505bc17) | Jan 08, 2024 |
| HP            | 8105                        | [7f6df56de0](https://linux-hardware.org/?probe=7f6df56de0) | Jan 08, 2024 |
| HP            | 8105                        | [bff2ea3f8f](https://linux-hardware.org/?probe=bff2ea3f8f) | Jan 08, 2024 |
| HP            | 8105                        | [ca99b2e20d](https://linux-hardware.org/?probe=ca99b2e20d) | Jan 08, 2024 |
| HP            | 8062                        | [4250f0bb2a](https://linux-hardware.org/?probe=4250f0bb2a) | Jan 08, 2024 |
| HP            | 8105                        | [4c3d033a45](https://linux-hardware.org/?probe=4c3d033a45) | Jan 08, 2024 |
| HP            | 8062                        | [2ed973c58e](https://linux-hardware.org/?probe=2ed973c58e) | Jan 08, 2024 |
| HP            | 8062                        | [d644042c15](https://linux-hardware.org/?probe=d644042c15) | Jan 08, 2024 |
| HP            | 8105                        | [e4afcbf22b](https://linux-hardware.org/?probe=e4afcbf22b) | Jan 08, 2024 |
| HP            | 8105                        | [86900314fe](https://linux-hardware.org/?probe=86900314fe) | Jan 08, 2024 |
| HP            | 8105                        | [5eacb006cf](https://linux-hardware.org/?probe=5eacb006cf) | Jan 08, 2024 |
| HP            | 8105                        | [5c691ff566](https://linux-hardware.org/?probe=5c691ff566) | Jan 08, 2024 |
| HP            | 8105                        | [a049370355](https://linux-hardware.org/?probe=a049370355) | Jan 08, 2024 |
| HP            | 8105                        | [98eef698ee](https://linux-hardware.org/?probe=98eef698ee) | Jan 08, 2024 |
| HP            | 8105                        | [6c13f7a773](https://linux-hardware.org/?probe=6c13f7a773) | Jan 08, 2024 |
| Shenzhen M... | F6BFC                       | [5b8c8357ea](https://linux-hardware.org/?probe=5b8c8357ea) | Jan 08, 2024 |
| ASRock        | 990FX Extreme4              | [40407d3445](https://linux-hardware.org/?probe=40407d3445) | Jan 08, 2024 |
| Gigabyte      | 945GZM-S2                   | [931f2e4a0e](https://linux-hardware.org/?probe=931f2e4a0e) | Jan 08, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | [19d6b3732e](https://linux-hardware.org/?probe=19d6b3732e) | Jan 07, 2024 |
| ASRock        | B450 Pro4 R2.0              | [9729786ea6](https://linux-hardware.org/?probe=9729786ea6) | Jan 07, 2024 |
| Dell          | 0NK5PH A00                  | [6a6d55183a](https://linux-hardware.org/?probe=6a6d55183a) | Jan 07, 2024 |
| ASRock        | J5040-ITX                   | [2dc9e2367b](https://linux-hardware.org/?probe=2dc9e2367b) | Jan 07, 2024 |
| ASRock        | 990FX Extreme4              | [cb1ceea0b8](https://linux-hardware.org/?probe=cb1ceea0b8) | Jan 07, 2024 |
| ASRock        | 990FX Extreme4              | [ca81fd63fd](https://linux-hardware.org/?probe=ca81fd63fd) | Jan 07, 2024 |
| HP            | 82F2                        | [eaa0d60c1f](https://linux-hardware.org/?probe=eaa0d60c1f) | Jan 07, 2024 |
| newplatfor... | NP-1004i.1                  | [95788038c5](https://linux-hardware.org/?probe=95788038c5) | Jan 06, 2024 |
| MSI           | X79A-GD65                   | [55c0071638](https://linux-hardware.org/?probe=55c0071638) | Jan 06, 2024 |
| Dell          | 00V62H A01                  | [a44b8f65f6](https://linux-hardware.org/?probe=a44b8f65f6) | Jan 06, 2024 |
| ASUSTek       | PRIME B550M-K               | [7536a68c05](https://linux-hardware.org/?probe=7536a68c05) | Jan 06, 2024 |
| Dell          | 0G919G A00                  | [29eda2d272](https://linux-hardware.org/?probe=29eda2d272) | Jan 06, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [af48a525ff](https://linux-hardware.org/?probe=af48a525ff) | Jan 06, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [a7c6792366](https://linux-hardware.org/?probe=a7c6792366) | Jan 05, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [bb1b5c33d2](https://linux-hardware.org/?probe=bb1b5c33d2) | Jan 05, 2024 |
| Sapphire      | PI-AM3RS760G2               | [c192611a71](https://linux-hardware.org/?probe=c192611a71) | Jan 05, 2024 |
| MSI           | Z590 PRO WIFI               | [4cec5133bd](https://linux-hardware.org/?probe=4cec5133bd) | Jan 05, 2024 |
| Sapphire      | PI-AM3RS760G2               | [78696f8410](https://linux-hardware.org/?probe=78696f8410) | Jan 05, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [408830a147](https://linux-hardware.org/?probe=408830a147) | Jan 05, 2024 |
| ASRock        | 990FX Extreme4              | [c4f303d6a1](https://linux-hardware.org/?probe=c4f303d6a1) | Jan 05, 2024 |
| ASRock        | 990FX Extreme4              | [37999c37df](https://linux-hardware.org/?probe=37999c37df) | Jan 05, 2024 |
| ASRock        | 990FX Extreme4              | [1aec475668](https://linux-hardware.org/?probe=1aec475668) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [05f8b32828](https://linux-hardware.org/?probe=05f8b32828) | Jan 05, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fe773de97b](https://linux-hardware.org/?probe=fe773de97b) | Jan 05, 2024 |
| Dell          | 01XK1W A00                  | [90e3c8644a](https://linux-hardware.org/?probe=90e3c8644a) | Jan 05, 2024 |
| ASRock        | 990FX Extreme4              | [8e8ffbd00e](https://linux-hardware.org/?probe=8e8ffbd00e) | Jan 04, 2024 |
| Dell          | 0PU052                      | [06e3c796ba](https://linux-hardware.org/?probe=06e3c796ba) | Jan 04, 2024 |
| ASRock        | J5040-ITX                   | [18b422e05b](https://linux-hardware.org/?probe=18b422e05b) | Jan 04, 2024 |
| ASUSTek       | PRIME Z270-P                | [e4413dc480](https://linux-hardware.org/?probe=e4413dc480) | Jan 04, 2024 |
| ASRock        | 990FX Extreme4              | [11efc6aeb2](https://linux-hardware.org/?probe=11efc6aeb2) | Jan 04, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [74565d105e](https://linux-hardware.org/?probe=74565d105e) | Jan 04, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [461cbd9fc4](https://linux-hardware.org/?probe=461cbd9fc4) | Jan 04, 2024 |
| Phoenix Co... | PSB514 A12                  | [424bbc0491](https://linux-hardware.org/?probe=424bbc0491) | Jan 03, 2024 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | [b8716bfb8f](https://linux-hardware.org/?probe=b8716bfb8f) | Jan 03, 2024 |
| Gowin Solu... | GW-MB-U01                   | [9cbf31ad86](https://linux-hardware.org/?probe=9cbf31ad86) | Jan 03, 2024 |
| ASUSTek       | PRIME B760-PLUS             | [59769c2318](https://linux-hardware.org/?probe=59769c2318) | Jan 03, 2024 |
| Dell          | 0C2XKD A01                  | [2db4c37daa](https://linux-hardware.org/?probe=2db4c37daa) | Jan 03, 2024 |
| ASRock        | 990FX Extreme4              | [beb2119db9](https://linux-hardware.org/?probe=beb2119db9) | Jan 03, 2024 |
| ASRock        | 990FX Extreme4              | [8ea5e6198c](https://linux-hardware.org/?probe=8ea5e6198c) | Jan 03, 2024 |
| ASRock        | 990FX Extreme4              | [5744834a9e](https://linux-hardware.org/?probe=5744834a9e) | Jan 03, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [ee8caab1b7](https://linux-hardware.org/?probe=ee8caab1b7) | Jan 03, 2024 |
| Sapphire      | PI-AM3RS760G2               | [4d0fa4b70d](https://linux-hardware.org/?probe=4d0fa4b70d) | Jan 02, 2024 |
| Sapphire      | PI-AM3RS760G2               | [edfe085e75](https://linux-hardware.org/?probe=edfe085e75) | Jan 02, 2024 |
| Acer          | Veriton X2611G V1.0         | [6bd375379c](https://linux-hardware.org/?probe=6bd375379c) | Jan 02, 2024 |
| Acer          | Veriton X2631G V:1.0        | [09ab487a05](https://linux-hardware.org/?probe=09ab487a05) | Jan 02, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5dc394a7e9](https://linux-hardware.org/?probe=5dc394a7e9) | Jan 02, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [6e68bc0fac](https://linux-hardware.org/?probe=6e68bc0fac) | Jan 02, 2024 |
| HP            | 18E7                        | [e1269783df](https://linux-hardware.org/?probe=e1269783df) | Jan 02, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [acadabf6d3](https://linux-hardware.org/?probe=acadabf6d3) | Jan 02, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [e5c35b5d54](https://linux-hardware.org/?probe=e5c35b5d54) | Jan 02, 2024 |
| Gigabyte      | B85M-D3H                    | [a146bec6e1](https://linux-hardware.org/?probe=a146bec6e1) | Jan 02, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [b5c2b00a99](https://linux-hardware.org/?probe=b5c2b00a99) | Jan 02, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a2146214ff](https://linux-hardware.org/?probe=a2146214ff) | Jan 02, 2024 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [fd906c174e](https://linux-hardware.org/?probe=fd906c174e) | Jan 02, 2024 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [260c5bb8f6](https://linux-hardware.org/?probe=260c5bb8f6) | Jan 02, 2024 |
| HP            | 198E                        | [e7e8af40a6](https://linux-hardware.org/?probe=e7e8af40a6) | Jan 02, 2024 |
| Gigabyte      | X58A-UD3R                   | [757bac1cef](https://linux-hardware.org/?probe=757bac1cef) | Jan 01, 2024 |
| Sapphire      | PI-AM3RS760G2               | [5f34a26ab3](https://linux-hardware.org/?probe=5f34a26ab3) | Jan 01, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Debian 11               | 2600     | 46.61%  |
| Debian 12               | 1454     | 26.07%  |
| Debian 10               | 759      | 13.61%  |
| Debian Testing          | 231      | 4.14%   |
| Debian                  | 209      | 3.75%   |
| Debian 9                | 149      | 2.67%   |
| Debian Unstable         | 116      | 2.08%   |
| Debian 8                | 25       | 0.45%   |
| Debian 11-updates       | 16       | 0.29%   |
| Debian 7                | 6        | 0.11%   |
| Debian Testing/unstable | 4        | 0.07%   |
| Debian Sid              | 2        | 0.04%   |
| Debian 6                | 2        | 0.04%   |
| Debian 23               | 2        | 0.04%   |
| Debian 23100609         | 1        | 0.02%   |
| Debian 12-updates       | 1        | 0.02%   |
| Debian 1                | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Debian | 5287     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Desktops | Percent |
|-----------------|----------|---------|
| 5.10.0-7-amd64  | 515      | 8.5%    |
| 6.1.0-4-amd64   | 271      | 4.47%   |
| 5.10.0-8-amd64  | 240      | 3.96%   |
| 6.1.0-13-amd64  | 188      | 3.1%    |
| 5.10.0-21-amd64 | 179      | 2.95%   |
| 6.1.0-18-amd64  | 144      | 2.38%   |
| 5.10.0-9-amd64  | 123      | 2.03%   |
| 5.10.0-2-amd64  | 117      | 1.93%   |
| 6.1.0-17-amd64  | 107      | 1.77%   |
| 5.10.0-19-amd64 | 106      | 1.75%   |
| 5.10.0-20-amd64 | 105      | 1.73%   |
| 6.1.0-10-amd64  | 100      | 1.65%   |
| 6.1.0-9-amd64   | 98       | 1.62%   |
| 5.10.0-23-amd64 | 95       | 1.57%   |
| 6.1.0-16-amd64  | 87       | 1.44%   |
| 5.10.0-13-amd64 | 87       | 1.44%   |
| 5.10.0-18-amd64 | 84       | 1.39%   |
| 5.10.0-10-amd64 | 75       | 1.24%   |
| 5.10.0-11-amd64 | 73       | 1.21%   |
| 5.10.0-16-amd64 | 69       | 1.14%   |
| 6.1.0-11-amd64  | 66       | 1.09%   |
| 6.1.0-12-amd64  | 65       | 1.07%   |
| 6.1.0-20-amd64  | 57       | 0.94%   |
| 4.19.0-6-amd64  | 56       | 0.92%   |
| 4.19.0-16-amd64 | 52       | 0.86%   |
| 4.19.0-14-amd64 | 52       | 0.86%   |
| 5.10.0-14-amd64 | 51       | 0.84%   |
| 4.19.0-13-amd64 | 50       | 0.83%   |
| 4.19.0-9-amd64  | 48       | 0.79%   |
| 4.19.0-17-amd64 | 48       | 0.79%   |
| 4.19.0-8-amd64  | 47       | 0.78%   |
| 5.10.0-22-amd64 | 44       | 0.73%   |
| 5.10.0-15-amd64 | 44       | 0.73%   |
| 5.10.0-17-amd64 | 43       | 0.71%   |
| 4.19.0-12-amd64 | 38       | 0.63%   |
| 5.15.0-2-amd64  | 35       | 0.58%   |
| 4.19.0-10-amd64 | 34       | 0.56%   |
| 5.10.0-26-amd64 | 31       | 0.51%   |
| 4.9.0-8-amd64   | 31       | 0.51%   |
| 6.1.0-7-amd64   | 30       | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 2201     | 38.13%  |
| 6.1.0    | 1322     | 22.9%   |
| 4.19.0   | 522      | 9.04%   |
| 4.9.0    | 110      | 1.91%   |
| 6.0.0    | 94       | 1.63%   |
| 5.18.0   | 79       | 1.37%   |
| 6.5.0    | 71       | 1.23%   |
| 5.9.0    | 59       | 1.02%   |
| 5.16.0   | 59       | 1.02%   |
| 5.15.0   | 57       | 0.99%   |
| 5.8.0    | 55       | 0.95%   |
| 5.7.0    | 54       | 0.94%   |
| 6.2.16   | 51       | 0.88%   |
| 5.6.0    | 48       | 0.83%   |
| 5.4.0    | 44       | 0.76%   |
| 5.13.19  | 44       | 0.76%   |
| 5.19.0   | 41       | 0.71%   |
| 6.5.11   | 40       | 0.69%   |
| 6.4.0    | 35       | 0.61%   |
| 5.14.0   | 33       | 0.57%   |
| 5.17.0   | 26       | 0.45%   |
| 6.5.13   | 21       | 0.36%   |
| 5.15.102 | 20       | 0.35%   |
| 6.6.13   | 19       | 0.33%   |
| 5.15.107 | 19       | 0.33%   |
| 5.11.22  | 19       | 0.33%   |
| 6.3.0    | 18       | 0.31%   |
| 5.3.0    | 18       | 0.31%   |
| 5.5.0    | 14       | 0.24%   |
| 5.15.83  | 14       | 0.24%   |
| 6.6.15   | 13       | 0.23%   |
| 5.15.74  | 13       | 0.23%   |
| 5.15.39  | 13       | 0.23%   |
| 5.15.35  | 13       | 0.23%   |
| 5.15.85  | 12       | 0.21%   |
| 5.15.30  | 12       | 0.21%   |
| 5.15.53  | 11       | 0.19%   |
| 3.16.0   | 11       | 0.19%   |
| 5.4.106  | 10       | 0.17%   |
| 5.15.108 | 9        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 2239     | 39.08%  |
| 6.1     | 1345     | 23.47%  |
| 4.19    | 535      | 9.34%   |
| 5.15    | 221      | 3.86%   |
| 6.5     | 134      | 2.34%   |
| 4.9     | 116      | 2.02%   |
| 6.0     | 107      | 1.87%   |
| 5.4     | 100      | 1.75%   |
| 5.18    | 84       | 1.47%   |
| 6.2     | 69       | 1.2%    |
| 5.16    | 65       | 1.13%   |
| 5.9     | 62       | 1.08%   |
| 5.8     | 61       | 1.06%   |
| 5.7     | 58       | 1.01%   |
| 5.13    | 54       | 0.94%   |
| 5.6     | 52       | 0.91%   |
| 5.19    | 51       | 0.89%   |
| 6.6     | 50       | 0.87%   |
| 6.4     | 44       | 0.77%   |
| 5.14    | 36       | 0.63%   |
| 5.11    | 31       | 0.54%   |
| 5.3     | 30       | 0.52%   |
| 5.17    | 30       | 0.52%   |
| 6.3     | 22       | 0.38%   |
| 6.7     | 18       | 0.31%   |
| 5.5     | 17       | 0.3%    |
| 4.15    | 11       | 0.19%   |
| 3.16    | 11       | 0.19%   |
| 6.8     | 10       | 0.17%   |
| 4.18    | 10       | 0.17%   |
| 5.2     | 8        | 0.14%   |
| 5.0     | 8        | 0.14%   |
| 4.1     | 8        | 0.14%   |
| 4.17    | 5        | 0.09%   |
| 5.12    | 3        | 0.05%   |
| 5.1     | 3        | 0.05%   |
| 4.16    | 3        | 0.05%   |
| 2.6     | 3        | 0.05%   |
| 4.20    | 2        | 0.03%   |
| 4.14    | 2        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 5133     | 97.05%  |
| i686        | 114      | 2.16%   |
| riscv64     | 9        | 0.17%   |
| armv7l      | 8        | 0.15%   |
| ppc64       | 7        | 0.13%   |
| aarch64     | 4        | 0.08%   |
| loongarch64 | 3        | 0.06%   |
| ppc64le     | 2        | 0.04%   |
| mips64      | 2        | 0.04%   |
| i586        | 2        | 0.04%   |
| sparc64     | 1        | 0.02%   |
| sh4a        | 1        | 0.02%   |
| ppc         | 1        | 0.02%   |
| i486        | 1        | 0.02%   |
| armv6l      | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 1854     | 34.24%  |
| GNOME             | 1103     | 20.37%  |
| KDE5              | 749      | 13.83%  |
| XFCE              | 618      | 11.41%  |
| MATE              | 251      | 4.64%   |
| X-Cinnamon        | 195      | 3.6%    |
| Cinnamon          | 133      | 2.46%   |
| LXDE              | 123      | 2.27%   |
| LXQt              | 86       | 1.59%   |
| KDE               | 84       | 1.55%   |
| i3                | 40       | 0.74%   |
| Openbox           | 36       | 0.66%   |
| GNOME Flashback   | 34       | 0.63%   |
| lightdm-xsession  | 19       | 0.35%   |
| GNOME Classic     | 18       | 0.33%   |
| trinity           | 15       | 0.28%   |
| Budgie            | 15       | 0.28%   |
| sway              | 6        | 0.11%   |
| awesome           | 6        | 0.11%   |
| icewm             | 5        | 0.09%   |
| KDE4              | 4        | 0.07%   |
| fluxbox           | 4        | 0.07%   |
| dwm               | 3        | 0.06%   |
| Enlightenment     | 2        | 0.04%   |
| xmonad            | 1        | 0.02%   |
| x-session-manager | 1        | 0.02%   |
| UKUI              | 1        | 0.02%   |
| sway:GNOME        | 1        | 0.02%   |
| i3-with-shmlog    | 1        | 0.02%   |
| GNUstep           | 1        | 0.02%   |
| gnome-xorg        | 1        | 0.02%   |
| e16-session       | 1        | 0.02%   |
| default           | 1        | 0.02%   |
| Cutefish          | 1        | 0.02%   |
| bspwm             | 1        | 0.02%   |
| /etc/X11/Xsession | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 2709     | 50.19%  |
| Unknown     | 1084     | 20.09%  |
| Tty         | 841      | 15.58%  |
| Wayland     | 758      | 14.04%  |
| Web         | 3        | 0.06%   |
| Unspecified | 2        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2690     | 49.82%  |
| LightDM | 866      | 16.04%  |
| SDDM    | 616      | 11.41%  |
| GDM     | 515      | 9.54%   |
| GDM3    | 393      | 7.28%   |
| TDM     | 250      | 4.63%   |
| SLiM    | 18       | 0.33%   |
| XDM     | 17       | 0.31%   |
| NODM    | 14       | 0.26%   |
| KDM     | 7        | 0.13%   |
| LXDM    | 6        | 0.11%   |
| WDM     | 3        | 0.06%   |
| Ly      | 2        | 0.04%   |
| SU      | 1        | 0.02%   |
| LDM     | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1912     | 35.74%  |
| ru_RU   | 989      | 18.49%  |
| de_DE   | 334      | 6.24%   |
| Unknown | 324      | 6.06%   |
| fr_FR   | 296      | 5.53%   |
| en_GB   | 238      | 4.45%   |
| pt_BR   | 159      | 2.97%   |
| es_ES   | 150      | 2.8%    |
| it_IT   | 115      | 2.15%   |
| en_CA   | 80       | 1.5%    |
| C       | 78       | 1.46%   |
| en_AU   | 73       | 1.36%   |
| pl_PL   | 61       | 1.14%   |
| es_AR   | 30       | 0.56%   |
| en_IE   | 29       | 0.54%   |
| zh_CN   | 26       | 0.49%   |
| en_IN   | 26       | 0.49%   |
| hu_HU   | 25       | 0.47%   |
| es_MX   | 23       | 0.43%   |
| en_ZA   | 22       | 0.41%   |
| es_VE   | 20       | 0.37%   |
| de_AT   | 20       | 0.37%   |
| nl_NL   | 19       | 0.36%   |
| ja_JP   | 18       | 0.34%   |
| nl_BE   | 16       | 0.3%    |
| de_CH   | 15       | 0.28%   |
| pt_PT   | 14       | 0.26%   |
| cs_CZ   | 13       | 0.24%   |
| fr_BE   | 12       | 0.22%   |
| es_CL   | 12       | 0.22%   |
| en_NZ   | 11       | 0.21%   |
| sv_SE   | 9        | 0.17%   |
| en_DK   | 9        | 0.17%   |
| fi_FI   | 8        | 0.15%   |
| fr_CA   | 7        | 0.13%   |
| en_HK   | 7        | 0.13%   |
| da_DK   | 7        | 0.13%   |
| ca_ES   | 7        | 0.13%   |
| zh_TW   | 6        | 0.11%   |
| ru_UA   | 6        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3183     | 59.4%   |
| EFI  | 2176     | 40.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 3764     | 70.33%  |
| Overlay    | 941      | 17.58%  |
| Btrfs      | 228      | 4.26%   |
| Zfs        | 139      | 2.6%    |
| Unknown    | 84       | 1.57%   |
| Xfs        | 83       | 1.55%   |
| Tmpfs      | 49       | 0.92%   |
| Ext3       | 29       | 0.54%   |
| Rootfs     | 13       | 0.24%   |
| Ext2       | 10       | 0.19%   |
| Aufs       | 4        | 0.07%   |
| F2fs       | 3        | 0.06%   |
| Jfs        | 2        | 0.04%   |
| XXXXXXX    | 1        | 0.02%   |
| XXXXX      | 1        | 0.02%   |
| Fuse.sshfs | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 2685     | 49.83%  |
| MBR     | 1657     | 30.75%  |
| Unknown | 1046     | 19.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4317     | 80.35%  |
| Yes       | 1056     | 19.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3408     | 63.68%  |
| Yes       | 1944     | 36.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1387     | 26.23%  |
| Gigabyte Technology                  | 860      | 16.27%  |
| MSI                                  | 552      | 10.44%  |
| ASRock                               | 500      | 9.46%   |
| Dell                                 | 350      | 6.62%   |
| Hewlett-Packard                      | 344      | 6.51%   |
| Lenovo                               | 196      | 3.71%   |
| Intel                                | 165      | 3.12%   |
| Unknown                              | 128      | 2.42%   |
| ECS                                  | 68       | 1.29%   |
| Fujitsu                              | 64       | 1.21%   |
| Acer                                 | 60       | 1.13%   |
| AZW                                  | 52       | 0.98%   |
| Foxconn                              | 47       | 0.89%   |
| Supermicro                           | 42       | 0.79%   |
| ASRockRack                           | 38       | 0.72%   |
| Biostar                              | 37       | 0.7%    |
| Pegatron                             | 26       | 0.49%   |
| Huanan                               | 21       | 0.4%    |
| Shuttle                              | 18       | 0.34%   |
| Inventec                             | 17       | 0.32%   |
| BESSTAR Tech                         | 15       | 0.28%   |
| Apple                                | 15       | 0.28%   |
| Shenzhen Meigao Electronic Equipment | 14       | 0.26%   |
| Google                               | 12       | 0.23%   |
| Medion                               | 11       | 0.21%   |
| Fujitsu Siemens                      | 11       | 0.21%   |
| Positivo                             | 10       | 0.19%   |
| IceWhale Technology                  | 7        | 0.13%   |
| HPE                                  | 7        | 0.13%   |
| Packard Bell                         | 6        | 0.11%   |
| OEM                                  | 6        | 0.11%   |
| Hardkernel                           | 6        | 0.11%   |
| AMI                                  | 6        | 0.11%   |
| PCWare                               | 5        | 0.09%   |
| Gateway                              | 5        | 0.09%   |
| Alienware                            | 5        | 0.09%   |
| YANYU                                | 4        | 0.08%   |
| Wistron                              | 4        | 0.08%   |
| Techvision                           | 4        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 152      | 2.87%   |
| Unknown                           | 136      | 2.57%   |
| ASUS S20 K29                      | 55       | 1.04%   |
| MSI MS-7996                       | 49       | 0.93%   |
| MSI MS-7817                       | 27       | 0.51%   |
| ECS G31T-M9                       | 27       | 0.51%   |
| Gigabyte H81M-S2V                 | 26       | 0.49%   |
| Dell OptiPlex 7010                | 24       | 0.45%   |
| ASUS TUF Gaming X570-PLUS         | 24       | 0.45%   |
| ASUS PRIME A320M-K                | 22       | 0.42%   |
| HP ProDesk 400 G2.5 SFF           | 20       | 0.38%   |
| Gigabyte B450M DS3H               | 20       | 0.38%   |
| ASUS PRIME H510M-A                | 20       | 0.38%   |
| ASRock H470M-HVS                  | 20       | 0.38%   |
| ECS H61H2-M13                     | 19       | 0.36%   |
| MSI MS-7C56                       | 18       | 0.34%   |
| MSI MS-7B79                       | 18       | 0.34%   |
| ASUS H110M-R                      | 17       | 0.32%   |
| Lenovo ThinkCentre M55p 8808D8U   | 16       | 0.3%    |
| Gigabyte H410M S2H                | 16       | 0.3%    |
| ASUS P8H61-M LX3 R2.0             | 16       | 0.3%    |
| ASUS P5QL-CM                      | 16       | 0.3%    |
| AZW U59                           | 15       | 0.28%   |
| AZW MINI S                        | 15       | 0.28%   |
| ASUS PRIME B450M-A                | 15       | 0.28%   |
| ASRock B450M Pro4                 | 15       | 0.28%   |
| ASUS PRIME B450M-K                | 14       | 0.26%   |
| MSI MS-7C02                       | 13       | 0.25%   |
| Dell OptiPlex 3010                | 13       | 0.25%   |
| MSI MS-7C91                       | 12       | 0.23%   |
| MSI MS-7A34                       | 12       | 0.23%   |
| HP Z420 Workstation               | 12       | 0.23%   |
| HP ProLiant MicroServer Gen8      | 12       | 0.23%   |
| HP Compaq Elite 8300 SFF          | 12       | 0.23%   |
| Gigabyte B450M S2H                | 12       | 0.23%   |
| Dell OptiPlex 9020                | 12       | 0.23%   |
| ASUS PRIME B450-PLUS              | 12       | 0.23%   |
| Intel Jasper Lake Client Platform | 11       | 0.21%   |
| Gigabyte H61M-S2PV                | 11       | 0.21%   |
| Gigabyte B550I AORUS PRO AX       | 11       | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 310      | 5.86%   |
| Dell OptiPlex          | 196      | 3.71%   |
| ASUS All               | 152      | 2.87%   |
| Unknown                | 136      | 2.57%   |
| ASUS ROG               | 134      | 2.53%   |
| Lenovo ThinkCentre     | 125      | 2.36%   |
| ASUS TUF               | 97       | 1.83%   |
| HP Compaq              | 80       | 1.51%   |
| Dell Precision         | 65       | 1.23%   |
| HP ProDesk             | 56       | 1.06%   |
| ASUS S20               | 55       | 1.04%   |
| Gigabyte B450M         | 50       | 0.95%   |
| MSI MS-7996            | 49       | 0.93%   |
| HP EliteDesk           | 47       | 0.89%   |
| Gigabyte X570          | 45       | 0.85%   |
| ASUS P8H61-M           | 44       | 0.83%   |
| HP ProLiant            | 34       | 0.64%   |
| Fujitsu ESPRIMO        | 34       | 0.64%   |
| ASUS PRO               | 32       | 0.61%   |
| Lenovo ThinkStation    | 31       | 0.59%   |
| Gigabyte B550          | 28       | 0.53%   |
| ASRock B450M           | 28       | 0.53%   |
| Acer Aspire            | 28       | 0.53%   |
| MSI MS-7817            | 27       | 0.51%   |
| ECS G31T-M9            | 27       | 0.51%   |
| Gigabyte H81M-S2V      | 26       | 0.49%   |
| Gigabyte B450          | 25       | 0.47%   |
| Dell Inspiron          | 24       | 0.45%   |
| ASRock B450            | 23       | 0.44%   |
| Acer Veriton           | 23       | 0.44%   |
| ASUS M5A97             | 22       | 0.42%   |
| Gigabyte H410M         | 21       | 0.4%    |
| Gigabyte B550M         | 21       | 0.4%    |
| Dell XPS               | 20       | 0.38%   |
| ASRock X570            | 20       | 0.38%   |
| ASRock H470M-HVS       | 20       | 0.38%   |
| Gigabyte GA-78LMT-USB3 | 19       | 0.36%   |
| Gigabyte A320M-S2H     | 19       | 0.36%   |
| ECS H61H2-M13          | 19       | 0.36%   |
| ASUS P5G41T-M          | 19       | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 481      | 9.1%    |
| 2018    | 472      | 8.93%   |
| 2012    | 460      | 8.7%    |
| 2013    | 388      | 7.34%   |
| 2019    | 375      | 7.09%   |
| 2021    | 358      | 6.77%   |
| 2014    | 322      | 6.09%   |
| 2011    | 316      | 5.98%   |
| 2022    | 290      | 5.49%   |
| 2017    | 270      | 5.11%   |
| 2015    | 259      | 4.9%    |
| 2009    | 244      | 4.62%   |
| 2010    | 229      | 4.33%   |
| 2016    | 226      | 4.27%   |
| 2008    | 182      | 3.44%   |
| 2007    | 142      | 2.69%   |
| 2023    | 119      | 2.25%   |
| 2006    | 52       | 0.98%   |
| Unknown | 37       | 0.7%    |
| 2005    | 29       | 0.55%   |
| 2004    | 15       | 0.28%   |
| 2003    | 6        | 0.11%   |
| 2024    | 5        | 0.09%   |
| 2000    | 4        | 0.08%   |
| 2002    | 3        | 0.06%   |
| 2001    | 3        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 5287     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 5190     | 97.94%  |
| Enabled  | 109      | 2.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 5264     | 99.56%  |
| Yes  | 23       | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1065     | 19.77%  |
| 4.01-8.0        | 851      | 15.8%   |
| 32.01-64.0      | 846      | 15.7%   |
| 3.01-4.0        | 792      | 14.7%   |
| 8.01-16.0       | 783      | 14.53%  |
| 64.01-256.0     | 499      | 9.26%   |
| 1.01-2.0        | 213      | 3.95%   |
| 24.01-32.0      | 155      | 2.88%   |
| 2.01-3.0        | 84       | 1.56%   |
| 0.51-1.0        | 37       | 0.69%   |
| More than 256.0 | 26       | 0.48%   |
| Unknown         | 18       | 0.33%   |
| 0.01-0.5        | 16       | 0.3%    |
| 0               | 2        | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 1.01-2.0        | 1166     | 20.25%  |
| 0.51-1.0        | 1147     | 19.92%  |
| 2.01-3.0        | 960      | 16.67%  |
| 4.01-8.0        | 945      | 16.41%  |
| 3.01-4.0        | 608      | 10.56%  |
| 8.01-16.0       | 378      | 6.56%   |
| 0.01-0.5        | 222      | 3.85%   |
| 16.01-24.0      | 143      | 2.48%   |
| 32.01-64.0      | 80       | 1.39%   |
| 24.01-32.0      | 61       | 1.06%   |
| 64.01-256.0     | 25       | 0.43%   |
| Unknown         | 23       | 0.4%    |
| More than 256.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2341     | 42.79%  |
| 2       | 1287     | 23.52%  |
| 3       | 743      | 13.58%  |
| 4       | 476      | 8.7%    |
| 5       | 217      | 3.97%   |
| 6       | 146      | 2.67%   |
| 7       | 73       | 1.33%   |
| 8       | 51       | 0.93%   |
| 0       | 36       | 0.66%   |
| 9       | 28       | 0.51%   |
| 10      | 17       | 0.31%   |
| 11      | 11       | 0.2%    |
| 12      | 9        | 0.16%   |
| 13      | 8        | 0.15%   |
| 14      | 4        | 0.07%   |
| 19      | 3        | 0.05%   |
| 16      | 3        | 0.05%   |
| 29      | 2        | 0.04%   |
| 27      | 2        | 0.04%   |
| 21      | 2        | 0.04%   |
| 18      | 2        | 0.04%   |
| 17      | 2        | 0.04%   |
| 15      | 2        | 0.04%   |
| Unknown | 2        | 0.04%   |
| 46      | 1        | 0.02%   |
| 32      | 1        | 0.02%   |
| 28      | 1        | 0.02%   |
| 22      | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3502     | 65.58%  |
| Yes       | 1838     | 34.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5239     | 99.09%  |
| No        | 48       | 0.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3552     | 66.67%  |
| Yes       | 1776     | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3885     | 72.63%  |
| Yes       | 1464     | 27.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 1133     | 21.39%  |
| USA          | 794      | 14.99%  |
| Germany      | 547      | 10.32%  |
| France       | 356      | 6.72%   |
| Brazil       | 245      | 4.62%   |
| Spain        | 210      | 3.96%   |
| Italy        | 180      | 3.4%    |
| UK           | 169      | 3.19%   |
| Canada       | 143      | 2.7%    |
| Poland       | 102      | 1.93%   |
| Australia    | 100      | 1.89%   |
| Netherlands  | 85       | 1.6%    |
| Switzerland  | 65       | 1.23%   |
| China        | 63       | 1.19%   |
| Austria      | 56       | 1.06%   |
| Belgium      | 55       | 1.04%   |
| Mexico       | 53       | 1%      |
| Hungary      | 49       | 0.92%   |
| Argentina    | 48       | 0.91%   |
| Sweden       | 40       | 0.76%   |
| Finland      | 40       | 0.76%   |
| Ukraine      | 38       | 0.72%   |
| India        | 37       | 0.7%    |
| Norway       | 36       | 0.68%   |
| Czechia      | 34       | 0.64%   |
| Romania      | 33       | 0.62%   |
| Portugal     | 33       | 0.62%   |
| Japan        | 26       | 0.49%   |
| Venezuela    | 25       | 0.47%   |
| South Africa | 25       | 0.47%   |
| Denmark      | 24       | 0.45%   |
| Bulgaria     | 24       | 0.45%   |
| Greece       | 22       | 0.42%   |
| Malaysia     | 21       | 0.4%    |
| Turkey       | 20       | 0.38%   |
| Taiwan       | 17       | 0.32%   |
| Hong Kong    | 17       | 0.32%   |
| Belarus      | 16       | 0.3%    |
| New Zealand  | 15       | 0.28%   |
| Chile        | 15       | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 767      | 13.94%  |
| Moscow            | 94       | 1.71%   |
| St Petersburg     | 67       | 1.22%   |
| Paris             | 45       | 0.82%   |
| Vienna            | 41       | 0.74%   |
| Berlin            | 39       | 0.71%   |
| Sao Paulo         | 37       | 0.67%   |
| Roubaix           | 34       | 0.62%   |
| Madrid            | 30       | 0.55%   |
| Falkenstein       | 29       | 0.53%   |
| Bangor            | 29       | 0.53%   |
| Seville           | 25       | 0.45%   |
| Amsterdam         | 25       | 0.45%   |
| Toronto           | 24       | 0.44%   |
| Rio de Janeiro    | 23       | 0.42%   |
| Melbourne         | 23       | 0.42%   |
| Frankfurt am Main | 23       | 0.42%   |
| Barcelona         | 23       | 0.42%   |
| Sydney            | 21       | 0.38%   |
| Milan             | 20       | 0.36%   |
| Zurich            | 18       | 0.33%   |
| Brisbane          | 18       | 0.33%   |
| Yekaterinburg     | 17       | 0.31%   |
| Warsaw            | 17       | 0.31%   |
| Perm              | 17       | 0.31%   |
| Munich            | 17       | 0.31%   |
| Kuala Lumpur      | 16       | 0.29%   |
| Hamburg           | 16       | 0.29%   |
| Budapest          | 16       | 0.29%   |
| Bagneux           | 16       | 0.29%   |
| Valencia          | 15       | 0.27%   |
| Athens            | 15       | 0.27%   |
| New York          | 14       | 0.25%   |
| Helsinki          | 14       | 0.25%   |
| Stuttgart         | 13       | 0.24%   |
| Nuremberg         | 13       | 0.24%   |
| London            | 13       | 0.24%   |
| Cologne           | 13       | 0.24%   |
| Chicago           | 13       | 0.24%   |
| Central           | 13       | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 1716     | 3255   | 18.12%  |
| Seagate                     | 1639     | 3024   | 17.3%   |
| Samsung Electronics         | 1368     | 2272   | 14.44%  |
| Kingston                    | 641      | 890    | 6.77%   |
| Toshiba                     | 591      | 1080   | 6.24%   |
| Crucial                     | 534      | 752    | 5.64%   |
| Sandisk                     | 352      | 483    | 3.72%   |
| Hitachi                     | 314      | 472    | 3.32%   |
| Intel                       | 163      | 227    | 1.72%   |
| A-DATA Technology           | 142      | 190    | 1.5%    |
| China                       | 139      | 166    | 1.47%   |
| HGST                        | 138      | 290    | 1.46%   |
| Unknown                     | 118      | 196    | 1.25%   |
| SPCC                        | 76       | 86     | 0.8%    |
| PNY                         | 68       | 129    | 0.72%   |
| Corsair                     | 66       | 89     | 0.7%    |
| Transcend                   | 62       | 78     | 0.65%   |
| Phison                      | 60       | 89     | 0.63%   |
| OCZ                         | 59       | 71     | 0.62%   |
| Maxtor                      | 56       | 64     | 0.59%   |
| Hewlett-Packard             | 50       | 87     | 0.53%   |
| Patriot                     | 49       | 66     | 0.52%   |
| SK hynix                    | 46       | 77     | 0.49%   |
| Netac                       | 45       | 127    | 0.48%   |
| Micron Technology           | 44       | 54     | 0.46%   |
| Intenso                     | 39       | 53     | 0.41%   |
| Gigabyte Technology         | 39       | 50     | 0.41%   |
| Unknown                     | 38       | 41     | 0.4%    |
| GOODRAM                     | 36       | 75     | 0.38%   |
| Kingston Technology Company | 35       | 51     | 0.37%   |
| Silicon Motion              | 30       | 37     | 0.32%   |
| Micron/Crucial Technology   | 26       | 37     | 0.27%   |
| Phison Electronics          | 25       | 39     | 0.26%   |
| Apacer                      | 24       | 33     | 0.25%   |
| JMicron Technology          | 23       | 25     | 0.24%   |
| Plextor                     | 22       | 29     | 0.23%   |
| XPG                         | 21       | 37     | 0.22%   |
| Team                        | 21       | 32     | 0.22%   |
| LITEON                      | 18       | 22     | 0.19%   |
| MAXIO Technology (Hangzhou) | 15       | 16     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                   | 153      | 1.35%   |
| Kingston SA400S37240G 240GB SSD                   | 152      | 1.34%   |
| Seagate ST1000DM010-2EP102 1TB                    | 125      | 1.1%    |
| Toshiba DT01ACA050 500GB                          | 101      | 0.89%   |
| Crucial CT480BX500SSD1 480GB                      | 92       | 0.81%   |
| Kingston SA400S37480G 480GB SSD                   | 85       | 0.75%   |
| Toshiba DT01ACA100 1TB                            | 77       | 0.68%   |
| Samsung SSD 860 EVO 500GB                         | 74       | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB                    | 73       | 0.64%   |
| Kingston SV300S37A120G 120GB SSD                  | 73       | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 69       | 0.61%   |
| Samsung SSD 850 EVO 250GB                         | 69       | 0.61%   |
| Crucial CT500MX500SSD1 500GB                      | 67       | 0.59%   |
| Samsung SSD 860 EVO 250GB                         | 65       | 0.57%   |
| Kingston SA400S37120G 120GB SSD                   | 64       | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB                    | 61       | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB                      | 61       | 0.54%   |
| Samsung SSD 860 EVO 1TB                           | 61       | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB                    | 60       | 0.53%   |
| Crucial CT240BX500SSD1 240GB                      | 60       | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                       | 60       | 0.53%   |
| Samsung SSD 970 EVO Plus 500GB                    | 58       | 0.51%   |
| Samsung SSD 850 EVO 500GB                         | 58       | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB                    | 54       | 0.48%   |
| Toshiba HDWD110 1TB                               | 52       | 0.46%   |
| Samsung SSD 980 PRO 1TB                           | 50       | 0.44%   |
| Hitachi HDS721050CLA362 500GB                     | 45       | 0.4%    |
| WDC WD5000AAKX-60U6AA0 500GB                      | 44       | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                        | 44       | 0.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 44       | 0.39%   |
| Toshiba DT01ACA200 2TB                            | 42       | 0.37%   |
| Seagate ST3500418AS 500GB                         | 40       | 0.35%   |
| Samsung SSD 870 EVO 500GB                         | 39       | 0.34%   |
| WDC WD20EFRX-68EUZN0 2TB                          | 38       | 0.34%   |
| Unknown                                           | 38       | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB                    | 37       | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 36       | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB                    | 35       | 0.31%   |
| Crucial CT250MX500SSD1 250GB                      | 34       | 0.3%    |
| WDC WD40EFRX-68N32N0 4TB                          | 32       | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1607     | 2945   | 35.84%  |
| WDC                 | 1503     | 2875   | 33.52%  |
| Toshiba             | 538      | 993    | 12%     |
| Hitachi             | 314      | 472    | 7%      |
| Samsung Electronics | 187      | 254    | 4.17%   |
| HGST                | 137      | 288    | 3.06%   |
| Maxtor              | 55       | 63     | 1.23%   |
| Unknown             | 24       | 31     | 0.54%   |
| Hewlett-Packard     | 15       | 36     | 0.33%   |
| SABRENT             | 12       | 13     | 0.27%   |
| JMicron Technology  | 12       | 14     | 0.27%   |
| Fujitsu             | 8        | 9      | 0.18%   |
| ASMT                | 7        | 19     | 0.16%   |
| Apple               | 7        | 8      | 0.16%   |
| TO Exter            | 4        | 4      | 0.09%   |
| Intenso             | 4        | 5      | 0.09%   |
| HPE                 | 4        | 9      | 0.09%   |
| ASMedia             | 3        | 3      | 0.07%   |
| Unknown (CF)        | 2        | 2      | 0.04%   |
| QUANTUM             | 2        | 2      | 0.04%   |
| QNAP                | 2        | 3      | 0.04%   |
| Inateck             | 2        | 2      | 0.04%   |
| H/W                 | 2        | 10     | 0.04%   |
| XrayDisk            | 1        | 1      | 0.02%   |
| WD MediaMax         | 1        | 6      | 0.02%   |
| USB 3.0             | 1        | 2      | 0.02%   |
| USB                 | 1        | 1      | 0.02%   |
| Synology            | 1        | 1      | 0.02%   |
| StoreJet            | 1        | 1      | 0.02%   |
| Shenzhen            | 1        | 1      | 0.02%   |
| SD                  | 1        | 1      | 0.02%   |
| RSH-319             | 1        | 1      | 0.02%   |
| pqi                 | 1        | 1      | 0.02%   |
| Pear 2TB            | 1        | 1      | 0.02%   |
| NAS                 | 1        | 10     | 0.02%   |
| MaxDigital          | 1        | 4      | 0.02%   |
| MARVELL             | 1        | 2      | 0.02%   |
| MARSHAL             | 1        | 1      | 0.02%   |
| Magnetic Data       | 1        | 1      | 0.02%   |
| LIO-ORG             | 1        | 8      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 730      | 1085   | 21.62%  |
| Kingston            | 555      | 746    | 16.43%  |
| Crucial             | 457      | 637    | 13.53%  |
| SanDisk             | 212      | 287    | 6.28%   |
| WDC                 | 185      | 240    | 5.48%   |
| China               | 136      | 163    | 4.03%   |
| A-DATA Technology   | 100      | 129    | 2.96%   |
| Intel               | 92       | 124    | 2.72%   |
| SPCC                | 65       | 71     | 1.92%   |
| OCZ                 | 59       | 71     | 1.75%   |
| PNY                 | 56       | 114    | 1.66%   |
| Transcend           | 54       | 69     | 1.6%    |
| Toshiba             | 41       | 52     | 1.21%   |
| Netac               | 40       | 121    | 1.18%   |
| Patriot             | 38       | 49     | 1.13%   |
| Intenso             | 33       | 43     | 0.98%   |
| Goodram             | 31       | 48     | 0.92%   |
| Corsair             | 26       | 31     | 0.77%   |
| Micron Technology   | 25       | 31     | 0.74%   |
| Apacer              | 20       | 27     | 0.59%   |
| Gigabyte Technology | 19       | 22     | 0.56%   |
| Plextor             | 17       | 24     | 0.5%    |
| Hewlett-Packard     | 17       | 23     | 0.5%    |
| Unknown             | 16       | 17     | 0.47%   |
| Team                | 14       | 19     | 0.41%   |
| LITEON              | 14       | 18     | 0.41%   |
| Seagate             | 12       | 15     | 0.36%   |
| SK hynix            | 11       | 13     | 0.33%   |
| KingDian            | 11       | 12     | 0.33%   |
| Mushkin             | 10       | 11     | 0.3%    |
| Innodisk            | 9        | 9      | 0.27%   |
| Fanxiang            | 9        | 11     | 0.27%   |
| Unknown             | 8        | 11     | 0.24%   |
| LITEONIT            | 8        | 13     | 0.24%   |
| Lexar               | 8        | 10     | 0.24%   |
| Hajaan              | 8        | 11     | 0.24%   |
| NGFF                | 7        | 7      | 0.21%   |
| KingSpec            | 7        | 10     | 0.21%   |
| Verbatim            | 6        | 9      | 0.18%   |
| T-FORCE             | 6        | 8      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3455     | 8122   | 43.6%   |
| SSD     | 2794     | 4657   | 35.26%  |
| NVMe    | 1503     | 2505   | 18.97%  |
| Unknown | 110      | 219    | 1.39%   |
| MMC     | 62       | 76     | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4710     | 12221  | 71.27%  |
| NVMe | 1497     | 2480   | 22.65%  |
| SAS  | 340      | 802    | 5.14%   |
| MMC  | 62       | 76     | 0.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives  | Percent |
|------------|----------|---------|---------|
| 0.01-0.5   | 3551     | 5982    | 50.5%   |
| 0.51-1.0   | 1704     | 2876    | 24.24%  |
| 1.01-2.0   | 763      | 1426    | 10.85%  |
| 3.01-4.0   | 406      | 887     | 5.77%   |
| 4.01-10.0  | 280      | 817     | 3.98%   |
| 2.01-3.0   | 234      | 466     | 3.33%   |
| 10.01-20.0 | 91       | 324     | 1.29%   |
| 20.01-50.0 | 1        | 1       | 0.01%   |
| 0          | 1        | Unknown | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 1042     | 18.94%  |
| 101-250        | 856      | 15.56%  |
| 251-500        | 783      | 14.23%  |
| 501-1000       | 738      | 13.42%  |
| More than 3000 | 641      | 11.65%  |
| 1001-2000      | 512      | 9.31%   |
| 51-100         | 300      | 5.45%   |
| 2001-3000      | 266      | 4.84%   |
| 1-20           | 207      | 3.76%   |
| 21-50          | 156      | 2.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1485     | 26.39%  |
| Unknown        | 1042     | 18.52%  |
| 101-250        | 563      | 10.01%  |
| 21-50          | 524      | 9.31%   |
| 251-500        | 438      | 7.78%   |
| 51-100         | 420      | 7.46%   |
| 501-1000       | 408      | 7.25%   |
| 1001-2000      | 313      | 5.56%   |
| More than 3000 | 285      | 5.06%   |
| 2001-3000      | 139      | 2.47%   |
| 0              | 10       | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 39       | 55     | 3.18%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 21       | 38     | 1.71%   |
| Kingston SV300S37A120G 120GB SSD | 20       | 22     | 1.63%   |
| WDC WD3200AAJS-00L7A0 320GB      | 15       | 16     | 1.22%   |
| Hitachi HDS721050CLA362 500GB    | 15       | 17     | 1.22%   |
| Seagate ST3500418AS 500GB        | 13       | 19     | 1.06%   |
| Seagate ST1000DM003-9YN162 1TB   | 12       | 17     | 0.98%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 10       | 10     | 0.82%   |
| Seagate ST3250318AS 250GB        | 10       | 11     | 0.82%   |
| Seagate ST31000528AS 1TB         | 10       | 12     | 0.82%   |
| Seagate ST31500341AS 1TB         | 9        | 15     | 0.73%   |
| Seagate ST250DM000-1BD141 250GB  | 9        | 9      | 0.73%   |
| WDC WD5000AAKX-001CA0 500GB      | 8        | 10     | 0.65%   |
| WDC WD20EARS-00MVWB0 2TB         | 8        | 8      | 0.65%   |
| Toshiba DT01ACA050 500GB         | 8        | 9      | 0.65%   |
| Seagate ST3250410AS 250GB        | 8        | 9      | 0.65%   |
| Seagate ST3160815AS 160GB        | 8        | 10     | 0.65%   |
| Seagate ST2000DM006-2DM164 2TB   | 8        | 9      | 0.65%   |
| WDC WD20EFRX-68EUZN0 2TB         | 7        | 18     | 0.57%   |
| WDC WD20EARX-00PASB0 2TB         | 7        | 10     | 0.57%   |
| WDC WD2002FAEX-007BA0 2TB        | 7        | 8      | 0.57%   |
| Toshiba DT01ACA100 1TB           | 7        | 9      | 0.57%   |
| Seagate ST3320613AS 320GB        | 7        | 7      | 0.57%   |
| Seagate ST2000DM001-1CH164 2TB   | 7        | 10     | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB   | 7        | 7      | 0.57%   |
| WDC WD2500AAJS-00L7A0 250GB      | 6        | 6      | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 6      | 0.49%   |
| Seagate ST3500413AS 500GB        | 6        | 7      | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB   | 6        | 7      | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB   | 6        | 7      | 0.49%   |
| Hitachi HDS721050DLE630 500GB    | 6        | 11     | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 5        | 5      | 0.41%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 5        | 6      | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 5        | 6      | 0.41%   |
| WDC WD10EARS-00Y5B1 1TB          | 5        | 5      | 0.41%   |
| WDC WD10EADS-00M2B0 1TB          | 5        | 5      | 0.41%   |
| Seagate ST9500325AS 500GB        | 5        | 7      | 0.41%   |
| Seagate ST3160811AS 160GB        | 5        | 5      | 0.41%   |
| Seagate ST31000524AS 1TB         | 5        | 5      | 0.41%   |
| Seagate ST2000DL003-9VT166 2TB   | 5        | 5      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 350      | 489    | 30.2%   |
| WDC                 | 332      | 480    | 28.65%  |
| Samsung Electronics | 103      | 118    | 8.89%   |
| Hitachi             | 80       | 112    | 6.9%    |
| Toshiba             | 56       | 75     | 4.83%   |
| Kingston            | 45       | 54     | 3.88%   |
| Intel               | 26       | 34     | 2.24%   |
| Maxtor              | 23       | 25     | 1.98%   |
| Crucial             | 23       | 30     | 1.98%   |
| A-DATA Technology   | 20       | 27     | 1.73%   |
| SanDisk             | 13       | 16     | 1.12%   |
| HGST                | 11       | 12     | 0.95%   |
| OCZ                 | 9        | 10     | 0.78%   |
| China               | 7        | 8      | 0.6%    |
| Corsair             | 5        | 5      | 0.43%   |
| SK hynix            | 4        | 8      | 0.35%   |
| Micron Technology   | 4        | 4      | 0.35%   |
| KingDian            | 4        | 4      | 0.35%   |
| Transcend           | 3        | 3      | 0.26%   |
| SPCC                | 3        | 3      | 0.26%   |
| ASMT                | 3        | 4      | 0.26%   |
| Mushkin             | 2        | 2      | 0.17%   |
| LITEONIT            | 2        | 2      | 0.17%   |
| LITEON              | 2        | 2      | 0.17%   |
| Hewlett-Packard     | 2        | 3      | 0.17%   |
| Fujitsu             | 2        | 3      | 0.17%   |
| Apple               | 2        | 2      | 0.17%   |
| Apacer              | 2        | 2      | 0.17%   |
| ZHITAI              | 1        | 1      | 0.09%   |
| XPG                 | 1        | 1      | 0.09%   |
| Western Digital     | 1        | 2      | 0.09%   |
| Unknown             | 1        | 1      | 0.09%   |
| Teclast             | 1        | 1      | 0.09%   |
| SSSTC               | 1        | 1      | 0.09%   |
| ShiJi               | 1        | 1      | 0.09%   |
| PNY                 | 1        | 1      | 0.09%   |
| Plextor             | 1        | 2      | 0.09%   |
| Patriot             | 1        | 1      | 0.09%   |
| Netac               | 1        | 2      | 0.09%   |
| Lenovo              | 1        | 1      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 350      | 489    | 38.89%  |
| WDC                 | 317      | 463    | 35.22%  |
| Hitachi             | 80       | 112    | 8.89%   |
| Samsung Electronics | 56       | 62     | 6.22%   |
| Toshiba             | 54       | 73     | 6%      |
| Maxtor              | 23       | 25     | 2.56%   |
| HGST                | 11       | 12     | 1.22%   |
| Hewlett-Packard     | 2        | 3      | 0.22%   |
| ASMT                | 2        | 3      | 0.22%   |
| Apple               | 2        | 2      | 0.22%   |
| Unknown             | 1        | 1      | 0.11%   |
| IBM                 | 1        | 1      | 0.11%   |
| Fujitsu             | 1        | 2      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 808      | 1248   | 75.87%  |
| SSD  | 222      | 266    | 20.85%  |
| NVMe | 35       | 47     | 3.29%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2        | 3      | 9.52%   |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1        | 1      | 4.76%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1        | 1      | 4.76%   |
| Seagate ST500DM005 HD502HJ 500GB                 | 1        | 1      | 4.76%   |
| Seagate ST3500830AS 500GB                        | 1        | 1      | 4.76%   |
| Seagate ST3500630A 500GB                         | 1        | 1      | 4.76%   |
| Seagate ST31000528AS 1TB                         | 1        | 1      | 4.76%   |
| Seagate ST2000NM0011 2TB                         | 1        | 1      | 4.76%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1        | 1      | 4.76%   |
| Samsung Electronics SSD 980 1TB                  | 1        | 1      | 4.76%   |
| Samsung Electronics SP0802N 80GB                 | 1        | 1      | 4.76%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 4.76%   |
| Samsung Electronics HD253GJ 250GB                | 1        | 1      | 4.76%   |
| Samsung Electronics HD103SJ 1TB                  | 1        | 2      | 4.76%   |
| Intel SSDSC2KW256G8 256GB                        | 1        | 1      | 4.76%   |
| Inland SATA SSD 128GB                            | 1        | 1      | 4.76%   |
| HGST HUH728080ALN600 8TB                         | 1        | 1      | 4.76%   |
| HGST HDN724040ALE640 4TB                         | 1        | 1      | 4.76%   |
| Hewlett-Packard SSD S700 500GB                   | 1        | 2      | 4.76%   |
| Crucial CT1000P1SSD8 1TB                         | 1        | 1      | 4.76%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 8      | 33.33%  |
| Samsung Electronics | 6        | 8      | 28.57%  |
| WDC                 | 2        | 2      | 9.52%   |
| HGST                | 2        | 2      | 9.52%   |
| Intel               | 1        | 1      | 4.76%   |
| Inland              | 1        | 1      | 4.76%   |
| Hewlett-Packard     | 1        | 2      | 4.76%   |
| Crucial             | 1        | 1      | 4.76%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 3789     | 9910   | 60.44%  |
| Detected | 1435     | 4081   | 22.89%  |
| Malfunc  | 1022     | 1561   | 16.3%   |
| Failed   | 21       | 25     | 0.33%   |
| Limited  | 2        | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3491     | 45.25%  |
| AMD                              | 1578     | 20.45%  |
| Samsung Electronics              | 614      | 7.96%   |
| ASMedia Technology               | 291      | 3.77%   |
| SanDisk                          | 240      | 3.11%   |
| Marvell Technology Group         | 182      | 2.36%   |
| Phison Electronics               | 179      | 2.32%   |
| JMicron Technology               | 160      | 2.07%   |
| Kingston Technology Company      | 136      | 1.76%   |
| Micron/Crucial Technology        | 114      | 1.48%   |
| Nvidia                           | 109      | 1.41%   |
| Silicon Motion                   | 68       | 0.88%   |
| ADATA Technology                 | 65       | 0.84%   |
| LSI Logic / Symbios Logic        | 56       | 0.73%   |
| VIA Technologies                 | 51       | 0.66%   |
| Broadcom / LSI                   | 48       | 0.62%   |
| SK hynix                         | 32       | 0.41%   |
| MAXIO Technology (Hangzhou)      | 32       | 0.41%   |
| Silicon Image                    | 29       | 0.38%   |
| Toshiba America Info Systems     | 25       | 0.32%   |
| Adaptec                          | 24       | 0.31%   |
| Realtek Semiconductor            | 22       | 0.29%   |
| Micron Technology                | 21       | 0.27%   |
| KIOXIA                           | 21       | 0.27%   |
| Seagate Technology               | 15       | 0.19%   |
| Lite-On Technology               | 11       | 0.14%   |
| INNOGRIT                         | 11       | 0.14%   |
| Shenzhen Longsys Electronics     | 9        | 0.12%   |
| Silicon Integrated Systems [SiS] | 8        | 0.1%    |
| Biwin Storage Technology         | 7        | 0.09%   |
| Yangtze Memory Technologies      | 6        | 0.08%   |
| Hewlett-Packard                  | 6        | 0.08%   |
| IBM                              | 5        | 0.06%   |
| Transcend                        | 4        | 0.05%   |
| Netac Technology                 | 4        | 0.05%   |
| Loongson Technology              | 4        | 0.05%   |
| Integrated Technology Express    | 4        | 0.05%   |
| HighPoint Technologies           | 4        | 0.05%   |
| Solidigm                         | 3        | 0.04%   |
| Solid State Storage Technology   | 3        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 874      | 9.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 432      | 4.53%   |
| AMD 400 Series Chipset SATA Controller                                                  | 338      | 3.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 337      | 3.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 264      | 2.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 262      | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 249      | 2.61%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 249      | 2.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 240      | 2.52%   |
| AMD 500 Series Chipset SATA Controller                                                  | 215      | 2.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 187      | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 183      | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 175      | 1.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 168      | 1.76%   |
| Intel SATA Controller [RAID mode]                                                       | 161      | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 145      | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 123      | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 119      | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 118      | 1.24%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 116      | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 102      | 1.07%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 101      | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 86       | 0.9%    |
| Phison E12 NVMe Controller                                                              | 85       | 0.89%   |
| AMD 600 Series Chipset SATA Controller                                                  | 79       | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 78       | 0.82%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 75       | 0.79%   |
| AMD 300 Series Chipset SATA Controller                                                  | 75       | 0.79%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 74       | 0.78%   |
| AMD FCH SATA Controller D                                                               | 72       | 0.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 71       | 0.74%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 70       | 0.73%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 69       | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 65       | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 65       | 0.68%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 59       | 0.62%   |
| Nvidia MCP61 SATA Controller                                                            | 56       | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 56       | 0.59%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 55       | 0.58%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 54       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4301     | 57.51%  |
| NVMe | 1502     | 20.08%  |
| IDE  | 1194     | 15.96%  |
| RAID | 338      | 4.52%   |
| SAS  | 109      | 1.46%   |
| SCSI | 35       | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3537     | 66.9%   |
| AMD                   | 1703     | 32.21%  |
| Unknown               | 9        | 0.17%   |
| ARM                   | 8        | 0.15%   |
| CentaurHauls          | 7        | 0.13%   |
| CHRP IBM,8233-E8B     | 5        | 0.09%   |
| sifive,u74-mc         | 4        | 0.08%   |
| sifive,bullet0        | 3        | 0.06%   |
| Loongson              | 3        | 0.06%   |
| Marvell Semiconductor | 2        | 0.04%   |
| CHRP IBM,9131-52A     | 2        | 0.04%   |
| thead,c906            | 1        | 0.02%   |
| PowerNV FP5466G2      | 1        | 0.02%   |
| PowerNV C829UAG3      | 1        | 0.02%   |
| PowerBook3,5          | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 87       | 1.64%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 68       | 1.28%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 63       | 1.19%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 57       | 1.07%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 50       | 0.94%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 50       | 0.94%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 48       | 0.9%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 47       | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 46       | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 46       | 0.87%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 45       | 0.85%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 44       | 0.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 42       | 0.79%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 42       | 0.79%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 42       | 0.79%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 40       | 0.75%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 39       | 0.73%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 39       | 0.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 39       | 0.73%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 39       | 0.73%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 37       | 0.7%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 36       | 0.68%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 34       | 0.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 34       | 0.64%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 33       | 0.62%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 33       | 0.62%   |
| AMD FX-8350 Eight-Core Processor            | 33       | 0.62%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 32       | 0.6%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 32       | 0.6%    |
| Intel Core i3-10100 CPU @ 3.60GHz           | 32       | 0.6%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 32       | 0.6%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 31       | 0.58%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 31       | 0.58%   |
| Intel Celeron N5105 @ 2.00GHz               | 31       | 0.58%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 30       | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 29       | 0.55%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 29       | 0.55%   |
| AMD FX-6300 Six-Core Processor              | 29       | 0.55%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 28       | 0.53%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 28       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 779      | 14.69%  |
| Intel Core i7           | 518      | 9.77%   |
| Intel Core i3           | 430      | 8.11%   |
| AMD Ryzen 5             | 406      | 7.65%   |
| Intel Xeon              | 357      | 6.73%   |
| AMD Ryzen 7             | 328      | 6.18%   |
| Other                   | 306      | 5.77%   |
| Intel Celeron           | 284      | 5.35%   |
| Intel Pentium           | 269      | 5.07%   |
| AMD Ryzen 9             | 213      | 4.02%   |
| Intel Core 2 Duo        | 196      | 3.7%    |
| AMD FX                  | 151      | 2.85%   |
| Intel Pentium Dual-Core | 91       | 1.72%   |
| Intel Core 2 Quad       | 88       | 1.66%   |
| AMD Ryzen 3             | 83       | 1.56%   |
| Intel Atom              | 58       | 1.09%   |
| Intel Core i9           | 47       | 0.89%   |
| Intel Core 2            | 45       | 0.85%   |
| AMD Ryzen Threadripper  | 42       | 0.79%   |
| AMD Athlon 64 X2        | 40       | 0.75%   |
| AMD Phenom II X4        | 38       | 0.72%   |
| AMD Athlon II X2        | 37       | 0.7%    |
| AMD A10                 | 37       | 0.7%    |
| AMD Athlon              | 35       | 0.66%   |
| Intel Pentium 4         | 34       | 0.64%   |
| AMD A8                  | 32       | 0.6%    |
| Intel Pentium Gold      | 31       | 0.58%   |
| AMD Ryzen 5 PRO         | 26       | 0.49%   |
| AMD GX                  | 25       | 0.47%   |
| AMD Phenom II X6        | 21       | 0.4%    |
| AMD Athlon II X4        | 18       | 0.34%   |
| Intel Pentium Silver    | 17       | 0.32%   |
| Intel Pentium Dual      | 17       | 0.32%   |
| AMD A4                  | 15       | 0.28%   |
| AMD Sempron             | 14       | 0.26%   |
| Intel Pentium D         | 13       | 0.25%   |
| AMD A6                  | 13       | 0.25%   |
| AMD Athlon 64           | 12       | 0.23%   |
| AMD PRO A8              | 11       | 0.21%   |
| AMD Phenom              | 11       | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1791     | 33.75%  |
| 2       | 1476     | 27.81%  |
| 6       | 770      | 14.51%  |
| 8       | 541      | 10.19%  |
| 12      | 182      | 3.43%   |
| 16      | 161      | 3.03%   |
| 1       | 160      | 3.01%   |
| 3       | 58       | 1.09%   |
| 10      | 52       | 0.98%   |
| 24      | 30       | 0.57%   |
| 14      | 26       | 0.49%   |
| 32      | 16       | 0.3%    |
| Unknown | 14       | 0.26%   |
| 18      | 7        | 0.13%   |
| 20      | 6        | 0.11%   |
| 22      | 5        | 0.09%   |
| 64      | 3        | 0.06%   |
| 44      | 3        | 0.06%   |
| 28      | 3        | 0.06%   |
| 36      | 2        | 0.04%   |
| 5       | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 5189     | 98.09%  |
| 2       | 87       | 1.64%   |
| Unknown | 12       | 0.23%   |
| 16      | 1        | 0.02%   |
| 0       | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 2940     | 55.51%  |
| 1       | 2335     | 44.09%  |
| Unknown | 14       | 0.26%   |
| 4       | 6        | 0.11%   |
| 8       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 5152     | 97.34%  |
| Unknown        | 89       | 1.68%   |
| 32-bit         | 52       | 0.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1389     | 25.49%  |
| 0x306c3    | 426      | 7.82%   |
| 0x1067a    | 245      | 4.5%    |
| 0x206a7    | 232      | 4.26%   |
| 0x306a9    | 228      | 4.18%   |
| 0x506e3    | 191      | 3.5%    |
| 0x906ea    | 149      | 2.73%   |
| 0x08701021 | 148      | 2.72%   |
| 0x906e9    | 113      | 2.07%   |
| 0xa0653    | 100      | 1.83%   |
| 0x0800820d | 75       | 1.38%   |
| 0x08108109 | 74       | 1.36%   |
| 0x0a201016 | 64       | 1.17%   |
| 0xa0655    | 58       | 1.06%   |
| 0xa0671    | 56       | 1.03%   |
| 0x906c0    | 54       | 0.99%   |
| 0x0a50000d | 54       | 0.99%   |
| 0x90672    | 52       | 0.95%   |
| 0x010000c8 | 49       | 0.9%    |
| 0x08701013 | 46       | 0.84%   |
| 0x306f2    | 45       | 0.83%   |
| 0x0a601203 | 43       | 0.79%   |
| 0x906ed    | 42       | 0.77%   |
| 0x06003106 | 41       | 0.75%   |
| 0x06000852 | 41       | 0.75%   |
| 0x6fd      | 37       | 0.68%   |
| 0x08101016 | 36       | 0.66%   |
| 0x306e4    | 35       | 0.64%   |
| 0x206d7    | 34       | 0.62%   |
| 0x6fb      | 32       | 0.59%   |
| 0x08600106 | 32       | 0.59%   |
| 0x08001137 | 32       | 0.59%   |
| 0x0a20120a | 31       | 0.57%   |
| 0x906eb    | 30       | 0.55%   |
| 0x08001138 | 30       | 0.55%   |
| 0x0a50000c | 29       | 0.53%   |
| 0x10676    | 28       | 0.51%   |
| 0xb0671    | 26       | 0.48%   |
| 0x90675    | 25       | 0.46%   |
| 0x106a5    | 25       | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 629      | 11.84%  |
| KabyLake         | 458      | 8.62%   |
| SandyBridge      | 347      | 6.53%   |
| Penryn           | 345      | 6.49%   |
| Zen 2            | 339      | 6.38%   |
| IvyBridge        | 339      | 6.38%   |
| Zen 3            | 323      | 6.08%   |
| Skylake          | 276      | 5.2%    |
| Unknown          | 261      | 4.91%   |
| Zen+             | 228      | 4.29%   |
| CometLake        | 202      | 3.8%    |
| Zen              | 163      | 3.07%   |
| K10              | 157      | 2.96%   |
| Core             | 152      | 2.86%   |
| Piledriver       | 148      | 2.79%   |
| Alderlake Hybrid | 96       | 1.81%   |
| Westmere         | 82       | 1.54%   |
| Silvermont       | 77       | 1.45%   |
| Nehalem          | 70       | 1.32%   |
| Tremont          | 69       | 1.3%    |
| K8 Hammer        | 66       | 1.24%   |
| NetBurst         | 57       | 1.07%   |
| Steamroller      | 51       | 0.96%   |
| Goldmont plus    | 51       | 0.96%   |
| Broadwell        | 42       | 0.79%   |
| Bulldozer        | 37       | 0.7%    |
| Icelake          | 34       | 0.64%   |
| Bonnell          | 34       | 0.64%   |
| Goldmont         | 33       | 0.62%   |
| Excavator        | 32       | 0.6%    |
| Jaguar           | 29       | 0.55%   |
| Bobcat           | 21       | 0.4%    |
| Gracemont        | 17       | 0.32%   |
| Puma             | 12       | 0.23%   |
| P6               | 9        | 0.17%   |
| K6               | 9        | 0.17%   |
| TigerLake        | 8        | 0.15%   |
| K10 Llano        | 8        | 0.15%   |
| Geode            | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2129     | 38.05%  |
| Nvidia                                       | 1777     | 31.76%  |
| AMD                                          | 1516     | 27.1%   |
| ASPEED Technology                            | 96       | 1.72%   |
| Matrox Electronics Systems                   | 54       | 0.97%   |
| VIA Technologies                             | 11       | 0.2%    |
| Silicon Integrated Systems [SiS]             | 4        | 0.07%   |
| Loongson Technology                          | 3        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.02%   |
| Silicon Motion                               | 1        | 0.02%   |
| Cirrus Logic                                 | 1        | 0.02%   |
| ATI Technologies                             | 1        | 0.02%   |
| 3DLabs                                       | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 296      | 5.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 173      | 3.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 170      | 2.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 161      | 2.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 136      | 2.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 120      | 2.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 117      | 2.04%   |
| Intel HD Graphics 530                                                       | 109      | 1.9%    |
| Nvidia GK208B [GeForce GT 710]                                              | 103      | 1.79%   |
| ASPEED Technology ASPEED Graphics Family                                    | 96       | 1.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 94       | 1.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 89       | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 89       | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 88       | 1.53%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 87       | 1.51%   |
| Intel HD Graphics 630                                                       | 75       | 1.31%   |
| AMD Raphael                                                                 | 70       | 1.22%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 67       | 1.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 63       | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 59       | 1.03%   |
| Intel JasperLake [UHD Graphics]                                             | 58       | 1.01%   |
| Nvidia GF108 [GeForce GT 730]                                               | 56       | 0.97%   |
| Intel HD Graphics 510                                                       | 54       | 0.94%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 54       | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 50       | 0.87%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 49       | 0.85%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 48       | 0.84%   |
| Intel AlderLake-S GT1                                                       | 47       | 0.82%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 47       | 0.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 42       | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 42       | 0.73%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 42       | 0.73%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 41       | 0.71%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 41       | 0.71%   |
| Nvidia GK208B [GeForce GT 730]                                              | 40       | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 38       | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 37       | 0.64%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 37       | 0.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 37       | 0.64%   |
| Nvidia GF108 [GeForce GT 630]                                               | 35       | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 1894     | 35.42%  |
| 1 x Nvidia                        | 1591     | 29.75%  |
| 1 x AMD                           | 1340     | 25.06%  |
| Intel + Nvidia                    | 94       | 1.76%   |
| 1 x ASPEED                        | 75       | 1.4%    |
| 2 x AMD                           | 72       | 1.35%   |
| Other                             | 56       | 1.05%   |
| AMD + Nvidia                      | 56       | 1.05%   |
| 1 x Matrox                        | 51       | 0.95%   |
| Intel + AMD                       | 29       | 0.54%   |
| 2 x Nvidia                        | 17       | 0.32%   |
| 2 x Intel                         | 16       | 0.3%    |
| Nvidia + ASPEED                   | 14       | 0.26%   |
| 1 x VIA                           | 11       | 0.21%   |
| AMD + ASPEED                      | 6        | 0.11%   |
| 1 x SiS                           | 4        | 0.07%   |
| AMD + Matrox                      | 4        | 0.07%   |
| 3 x AMD                           | 3        | 0.06%   |
| Intel + 2 x Nvidia                | 3        | 0.06%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.02%   |
| 2 x Loongson Technology           | 1        | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.02%   |
| 2 x AMD + 1 x Nvidia              | 1        | 0.02%   |
| 1 x XGI                           | 1        | 0.02%   |
| 1 x Silicon Motion                | 1        | 0.02%   |
| 1 x Loongson Technology           | 1        | 0.02%   |
| Intel + Matrox                    | 1        | 0.02%   |
| 1 x Cirrus Logic                  | 1        | 0.02%   |
| AMD + 2 x Nvidia                  | 1        | 0.02%   |
| AMD + Loongson Technology         | 1        | 0.02%   |
| AMD + 3DLabs                      | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3184     | 59.46%  |
| Unknown     | 1308     | 24.43%  |
| Proprietary | 863      | 16.12%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3286     | 60.78%  |
| 1.01-2.0   | 463      | 8.56%   |
| 0.01-0.5   | 349      | 6.46%   |
| 0.51-1.0   | 336      | 6.22%   |
| 3.01-4.0   | 334      | 6.18%   |
| 7.01-8.0   | 309      | 5.72%   |
| 5.01-6.0   | 137      | 2.53%   |
| 8.01-16.0  | 107      | 1.98%   |
| 2.01-3.0   | 48       | 0.89%   |
| 16.01-24.0 | 29       | 0.54%   |
| 4.01-5.0   | 6        | 0.11%   |
| 32.01-64.0 | 1        | 0.02%   |
| 24.01-32.0 | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 659      | 15.32%  |
| Dell                 | 506      | 11.76%  |
| Goldstar             | 415      | 9.65%   |
| Hewlett-Packard      | 276      | 6.42%   |
| Acer                 | 270      | 6.28%   |
| Philips              | 252      | 5.86%   |
| BenQ                 | 241      | 5.6%    |
| AOC                  | 207      | 4.81%   |
| Ancor Communications | 192      | 4.46%   |
| Iiyama               | 99       | 2.3%    |
| ViewSonic            | 97       | 2.25%   |
| Unknown              | 96       | 2.23%   |
| ASUSTek Computer     | 88       | 2.05%   |
| Lenovo               | 75       | 1.74%   |
| LG Electronics       | 57       | 1.32%   |
| Eizo                 | 45       | 1.05%   |
| Sony                 | 42       | 0.98%   |
| NEC Computers        | 35       | 0.81%   |
| Unknown              | 31       | 0.72%   |
| Fujitsu Siemens      | 24       | 0.56%   |
| Sceptre Tech         | 22       | 0.51%   |
| Medion               | 20       | 0.46%   |
| Vizio                | 16       | 0.37%   |
| Vestel Elektronik    | 14       | 0.33%   |
| MSI                  | 14       | 0.33%   |
| HannStar             | 14       | 0.33%   |
| Toshiba              | 13       | 0.3%    |
| RTK                  | 12       | 0.28%   |
| Panasonic            | 12       | 0.28%   |
| Hitachi              | 12       | 0.28%   |
| Mi                   | 10       | 0.23%   |
| Idek Iiyama          | 10       | 0.23%   |
| Belinea              | 10       | 0.23%   |
| Packard Bell         | 9        | 0.21%   |
| MStar                | 9        | 0.21%   |
| HPN                  | 9        | 0.21%   |
| Apple                | 9        | 0.21%   |
| HKC                  | 8        | 0.19%   |
| CHR                  | 8        | 0.19%   |
| HUAWEI               | 7        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 55       | 1.2%    |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                    | 44       | 0.96%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 36       | 0.78%   |
| Unknown                                                               | 31       | 0.67%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 20       | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 17       | 0.37%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 15       | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 15       | 0.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 14       | 0.3%    |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 13       | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 12       | 0.26%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 11       | 0.24%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch  | 11       | 0.24%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 11       | 0.24%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 10       | 0.22%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 10       | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 10       | 0.22%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 10       | 0.22%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 10       | 0.22%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 10       | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 9        | 0.2%    |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 9        | 0.2%    |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 9        | 0.2%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 9        | 0.2%    |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 9        | 0.2%    |
| AOC G2460PG AOC2460 1920x1080 531x299mm 24.0-inch                     | 9        | 0.2%    |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 8        | 0.17%   |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                    | 8        | 0.17%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 8        | 0.17%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 8        | 0.17%   |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                    | 8        | 0.17%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 8        | 0.17%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 8        | 0.17%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 8        | 0.17%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 7        | 0.15%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 7        | 0.15%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch | 7        | 0.15%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 7        | 0.15%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 7        | 0.15%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                | 7        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1779     | 41.91%  |
| 3840x2160 (4K)     | 404      | 9.52%   |
| 2560x1440 (QHD)    | 343      | 8.08%   |
| 1280x1024 (SXGA)   | 326      | 7.68%   |
| 1680x1050 (WSXGA+) | 194      | 4.57%   |
| 1366x768 (WXGA)    | 172      | 4.05%   |
| 1920x1200 (WUXGA)  | 142      | 3.35%   |
| Unknown            | 135      | 3.18%   |
| 1440x900 (WXGA+)   | 113      | 2.66%   |
| 1600x900 (HD+)     | 107      | 2.52%   |
| 2560x1080          | 76       | 1.79%   |
| 3440x1440          | 71       | 1.67%   |
| 2288x1287          | 57       | 1.34%   |
| 3840x1080          | 52       | 1.22%   |
| 1360x768           | 48       | 1.13%   |
| 1024x768 (XGA)     | 41       | 0.97%   |
| 1600x1200          | 33       | 0.78%   |
| 1920x540           | 17       | 0.4%    |
| 4480x1440          | 12       | 0.28%   |
| 2560x1600          | 10       | 0.24%   |
| 5760x2160          | 8        | 0.19%   |
| 3840x1600          | 8        | 0.19%   |
| 3200x1080          | 7        | 0.16%   |
| 1280x720 (HD)      | 7        | 0.16%   |
| 7680x2160          | 6        | 0.14%   |
| 5760x1080          | 6        | 0.14%   |
| 3840x1200          | 5        | 0.12%   |
| 2048x1152          | 4        | 0.09%   |
| 1400x1050          | 4        | 0.09%   |
| 5120x1440          | 3        | 0.07%   |
| 3360x1050          | 3        | 0.07%   |
| 6400x2160          | 2        | 0.05%   |
| 5760x1200          | 2        | 0.05%   |
| 5360x1440          | 2        | 0.05%   |
| 3600x1080          | 2        | 0.05%   |
| 2720x768           | 2        | 0.05%   |
| 2560x1024          | 2        | 0.05%   |
| 2048x1536          | 2        | 0.05%   |
| 1280x800 (WXGA)    | 2        | 0.05%   |
| 9440x2160          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 622      | 14.63%  |
| 27      | 569      | 13.38%  |
| 23      | 481      | 11.31%  |
| 21      | 427      | 10.04%  |
| Unknown | 403      | 9.48%   |
| 19      | 263      | 6.19%   |
| 18      | 191      | 4.49%   |
| 17      | 157      | 3.69%   |
| 31      | 154      | 3.62%   |
| 22      | 127      | 2.99%   |
| 20      | 124      | 2.92%   |
| 34      | 113      | 2.66%   |
| 15      | 84       | 1.98%   |
| 84      | 61       | 1.43%   |
| 142     | 55       | 1.29%   |
| 25      | 44       | 1.03%   |
| 32      | 42       | 0.99%   |
| 72      | 36       | 0.85%   |
| 54      | 36       | 0.85%   |
| 40      | 32       | 0.75%   |
| 28      | 21       | 0.49%   |
| 26      | 21       | 0.49%   |
| 52      | 20       | 0.47%   |
| 48      | 17       | 0.4%    |
| 29      | 12       | 0.28%   |
| 65      | 9        | 0.21%   |
| 43      | 9        | 0.21%   |
| 39      | 9        | 0.21%   |
| 37      | 9        | 0.21%   |
| 33      | 9        | 0.21%   |
| 16      | 9        | 0.21%   |
| 35      | 8        | 0.19%   |
| 13      | 8        | 0.19%   |
| 46      | 7        | 0.16%   |
| 12      | 7        | 0.16%   |
| 42      | 6        | 0.14%   |
| 36      | 6        | 0.14%   |
| 49      | 5        | 0.12%   |
| 38      | 4        | 0.09%   |
| 14      | 4        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1555     | 37.7%   |
| 401-500        | 965      | 23.39%  |
| Unknown        | 403      | 9.77%   |
| 601-700        | 253      | 6.13%   |
| 301-350        | 234      | 5.67%   |
| 351-400        | 180      | 4.36%   |
| 701-800        | 167      | 4.05%   |
| 1001-1500      | 109      | 2.64%   |
| 1501-2000      | 104      | 2.52%   |
| 801-900        | 59       | 1.43%   |
| More than 2000 | 56       | 1.36%   |
| 201-300        | 19       | 0.46%   |
| 901-1000       | 19       | 0.46%   |
| 101-200        | 2        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2475     | 62.41%  |
| 16/10   | 463      | 11.67%  |
| Unknown | 356      | 8.98%   |
| 5/4     | 303      | 7.64%   |
| 21/9    | 141      | 3.56%   |
| 4/3     | 98       | 2.47%   |
| 1.00    | 58       | 1.46%   |
| 3/2     | 29       | 0.73%   |
| 32/9    | 17       | 0.43%   |
| 6/5     | 15       | 0.38%   |
| 0.56    | 3        | 0.08%   |
| 2.65    | 2        | 0.05%   |
| 2.00    | 2        | 0.05%   |
| 1.96    | 2        | 0.05%   |
| 3.20    | 1        | 0.03%   |
| 11/10   | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1320     | 31.65%  |
| 301-350        | 582      | 13.95%  |
| 151-200        | 498      | 11.94%  |
| Unknown        | 403      | 9.66%   |
| 351-500        | 347      | 8.32%   |
| 141-150        | 298      | 7.14%   |
| 251-300        | 253      | 6.07%   |
| More than 1000 | 246      | 5.9%    |
| 501-1000       | 97       | 2.33%   |
| 101-110        | 72       | 1.73%   |
| 131-140        | 14       | 0.34%   |
| 111-120        | 12       | 0.29%   |
| 71-80          | 10       | 0.24%   |
| 121-130        | 7        | 0.17%   |
| 81-90          | 5        | 0.12%   |
| 91-100         | 3        | 0.07%   |
| 1-40           | 2        | 0.05%   |
| 61-70          | 1        | 0.02%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2395     | 59.95%  |
| 101-120       | 713      | 17.85%  |
| Unknown       | 404      | 10.11%  |
| 121-160       | 203      | 5.08%   |
| 1-50          | 198      | 4.96%   |
| 161-240       | 79       | 1.98%   |
| More than 240 | 3        | 0.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3069     | 57.11%  |
| 0     | 1540     | 28.66%  |
| 2     | 677      | 12.6%   |
| 3     | 82       | 1.53%   |
| 4     | 6        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3295     | 45.69%  |
| Intel                             | 2205     | 30.57%  |
| Qualcomm Atheros                  | 371      | 5.14%   |
| Broadcom                          | 188      | 2.61%   |
| Ralink Technology                 | 117      | 1.62%   |
| MediaTek                          | 111      | 1.54%   |
| Nvidia                            | 92       | 1.28%   |
| TP-Link                           | 82       | 1.14%   |
| Ralink                            | 53       | 0.73%   |
| Marvell Technology Group          | 53       | 0.73%   |
| Aquantia                          | 50       | 0.69%   |
| Broadcom Limited                  | 44       | 0.61%   |
| Mellanox Technologies             | 29       | 0.4%    |
| ASIX Electronics                  | 29       | 0.4%    |
| D-Link System                     | 28       | 0.39%   |
| Qualcomm Atheros Communications   | 27       | 0.37%   |
| Samsung Electronics               | 24       | 0.33%   |
| Microsoft                         | 22       | 0.31%   |
| ASUSTek Computer                  | 21       | 0.29%   |
| VIA Technologies                  | 20       | 0.28%   |
| D-Link                            | 19       | 0.26%   |
| NetGear                           | 18       | 0.25%   |
| Huawei Technologies               | 18       | 0.25%   |
| American Megatrends               | 17       | 0.24%   |
| Edimax Technology                 | 15       | 0.21%   |
| QinHeng Electronics               | 12       | 0.17%   |
| 3Com                              | 12       | 0.17%   |
| Xiaomi                            | 11       | 0.15%   |
| Sigma Designs                     | 11       | 0.15%   |
| Gemtek                            | 8        | 0.11%   |
| Belkin Components                 | 8        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 7        | 0.1%    |
| Dresden Elektronik                | 7        | 0.1%    |
| Texas Instruments                 | 6        | 0.08%   |
| IMC Networks                      | 6        | 0.08%   |
| DisplayLink                       | 6        | 0.08%   |
| Wilocity                          | 5        | 0.07%   |
| Sundance Technology Inc / IC Plus | 5        | 0.07%   |
| Motorola PCS                      | 5        | 0.07%   |
| Linksys                           | 5        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2615     | 32.17%  |
| Realtek RTL8125 2.5GbE Controller                                      | 307      | 3.78%   |
| Intel I211 Gigabit Network Connection                                  | 259      | 3.19%   |
| Intel Wi-Fi 6 AX200                                                    | 190      | 2.34%   |
| Intel Ethernet Controller I225-V                                       | 174      | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 161      | 1.98%   |
| Intel Ethernet Connection (2) I219-V                                   | 153      | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 129      | 1.59%   |
| Intel Ethernet Connection I217-LM                                      | 122      | 1.5%    |
| Intel I210 Gigabit Network Connection                                  | 98       | 1.21%   |
| Intel 82579V Gigabit Network Connection                                | 85       | 1.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 79       | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 77       | 0.95%   |
| Intel 82574L Gigabit Network Connection                                | 76       | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                   | 61       | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                  | 58       | 0.71%   |
| Intel Wireless 3165                                                    | 56       | 0.69%   |
| Intel Ethernet Connection (14) I219-V                                  | 52       | 0.64%   |
| Nvidia MCP61 Ethernet                                                  | 51       | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 50       | 0.62%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 50       | 0.62%   |
| Ralink MT7601U Wireless Adapter                                        | 48       | 0.59%   |
| Intel Ethernet Connection I217-V                                       | 46       | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                   | 46       | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 45       | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 45       | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 45       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 45       | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 42       | 0.52%   |
| Realtek 802.11ac NIC                                                   | 41       | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 40       | 0.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 39       | 0.48%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 39       | 0.48%   |
| Intel I350 Gigabit Network Connection                                  | 38       | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 37       | 0.46%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 37       | 0.46%   |
| Intel Ethernet Controller I226-V                                       | 36       | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 34       | 0.42%   |
| Intel Wireless 7260                                                    | 31       | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 30       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 721      | 38.19%  |
| Realtek Semiconductor                 | 375      | 19.86%  |
| Qualcomm Atheros                      | 192      | 10.17%  |
| Ralink Technology                     | 117      | 6.2%    |
| MediaTek                              | 103      | 5.46%   |
| TP-Link                               | 76       | 4.03%   |
| Broadcom                              | 56       | 2.97%   |
| Ralink                                | 53       | 2.81%   |
| Qualcomm Atheros Communications       | 27       | 1.43%   |
| ASUSTek Computer                      | 21       | 1.11%   |
| D-Link                                | 19       | 1.01%   |
| NetGear                               | 18       | 0.95%   |
| Microsoft                             | 18       | 0.95%   |
| Edimax Technology                     | 15       | 0.79%   |
| D-Link System                         | 13       | 0.69%   |
| Broadcom Limited                      | 8        | 0.42%   |
| Belkin Components                     | 8        | 0.42%   |
| IMC Networks                          | 6        | 0.32%   |
| Gemtek                                | 6        | 0.32%   |
| Wilocity                              | 5        | 0.26%   |
| Marvell Technology Group              | 5        | 0.26%   |
| Linksys                               | 5        | 0.26%   |
| AVM                                   | 5        | 0.26%   |
| Qualcomm Technologies                 | 3        | 0.16%   |
| ZyDAS                                 | 1        | 0.05%   |
| Xiaomi                                | 1        | 0.05%   |
| TRENDnet                              | 1        | 0.05%   |
| Tenda                                 | 1        | 0.05%   |
| Sitecom Europe                        | 1        | 0.05%   |
| PLANEX                                | 1        | 0.05%   |
| Micro Star International              | 1        | 0.05%   |
| Fiberline                             | 1        | 0.05%   |
| Encore Electronics                    | 1        | 0.05%   |
| Dell                                  | 1        | 0.05%   |
| CyberTAN Technology                   | 1        | 0.05%   |
| BUFFALO                               | 1        | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 190      | 9.97%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 79       | 4.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 77       | 4.04%   |
| Intel Wireless 3165                                            | 56       | 2.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 50       | 2.62%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 50       | 2.62%   |
| Ralink MT7601U Wireless Adapter                                | 48       | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 45       | 2.36%   |
| Realtek 802.11ac NIC                                           | 41       | 2.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 40       | 2.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 39       | 2.05%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 39       | 2.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 34       | 1.78%   |
| Intel Wireless 7260                                            | 31       | 1.63%   |
| Intel Wireless 7265                                            | 30       | 1.57%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 30       | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 29       | 1.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 25       | 1.31%   |
| Ralink RT5370 Wireless Adapter                                 | 24       | 1.26%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 23       | 1.21%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 23       | 1.21%   |
| Qualcomm Atheros AR9271 802.11n                                | 23       | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 21       | 1.1%    |
| Intel Wireless 8260                                            | 20       | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 20       | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 19       | 1%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 17       | 0.89%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 17       | 0.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 17       | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16       | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 16       | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 16       | 0.84%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 15       | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15       | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14       | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 13       | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 13       | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 12       | 0.63%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 12       | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 12       | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 3163     | 54.38%  |
| Intel                                  | 1815     | 31.21%  |
| Qualcomm Atheros                       | 197      | 3.39%   |
| Broadcom                               | 138      | 2.37%   |
| Nvidia                                 | 91       | 1.56%   |
| Aquantia                               | 50       | 0.86%   |
| Marvell Technology Group               | 49       | 0.84%   |
| Broadcom Limited                       | 36       | 0.62%   |
| ASIX Electronics                       | 29       | 0.5%    |
| Mellanox Technologies                  | 27       | 0.46%   |
| Samsung Electronics                    | 24       | 0.41%   |
| VIA Technologies                       | 20       | 0.34%   |
| American Megatrends                    | 17       | 0.29%   |
| D-Link System                          | 15       | 0.26%   |
| Huawei Technologies                    | 12       | 0.21%   |
| 3Com                                   | 12       | 0.21%   |
| Xiaomi                                 | 10       | 0.17%   |
| Silicon Integrated Systems [SiS]       | 7        | 0.12%   |
| MediaTek                               | 7        | 0.12%   |
| TP-Link                                | 6        | 0.1%    |
| DisplayLink                            | 6        | 0.1%    |
| Sundance Technology Inc / IC Plus      | 5        | 0.09%   |
| ICS Advent                             | 5        | 0.09%   |
| IBM                                    | 5        | 0.09%   |
| Google                                 | 5        | 0.09%   |
| Emulex                                 | 5        | 0.09%   |
| ADMtek                                 | 5        | 0.09%   |
| Qualcomm                               | 4        | 0.07%   |
| QLogic                                 | 4        | 0.07%   |
| Motorola PCS                           | 4        | 0.07%   |
| Microsoft                              | 4        | 0.07%   |
| OPPO Electronics                       | 3        | 0.05%   |
| JMicron Technology                     | 3        | 0.05%   |
| Insyde Software                        | 3        | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.03%   |
| SysKonnect                             | 2        | 0.03%   |
| Spreadtrum Communications              | 2        | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.03%   |
| Solarflare Communications              | 2        | 0.03%   |
| Microchip Technology                   | 2        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 2615     | 42.79%  |
| Realtek RTL8125 2.5GbE Controller                                              | 307      | 5.02%   |
| Intel I211 Gigabit Network Connection                                          | 259      | 4.24%   |
| Intel Ethernet Controller I225-V                                               | 174      | 2.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 161      | 2.63%   |
| Intel Ethernet Connection (2) I219-V                                           | 153      | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 129      | 2.11%   |
| Intel Ethernet Connection I217-LM                                              | 122      | 2%      |
| Intel I210 Gigabit Network Connection                                          | 98       | 1.6%    |
| Intel 82579V Gigabit Network Connection                                        | 85       | 1.39%   |
| Intel 82574L Gigabit Network Connection                                        | 76       | 1.24%   |
| Intel Ethernet Connection (7) I219-V                                           | 61       | 1%      |
| Intel Ethernet Connection (2) I219-LM                                          | 58       | 0.95%   |
| Intel Ethernet Connection (14) I219-V                                          | 52       | 0.85%   |
| Nvidia MCP61 Ethernet                                                          | 51       | 0.83%   |
| Intel Ethernet Connection I217-V                                               | 46       | 0.75%   |
| Intel Ethernet Connection (2) I218-V                                           | 46       | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 45       | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 45       | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 45       | 0.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 42       | 0.69%   |
| Intel I350 Gigabit Network Connection                                          | 38       | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 37       | 0.61%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 37       | 0.61%   |
| Intel Ethernet Controller I226-V                                               | 36       | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 30       | 0.49%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 26       | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                          | 25       | 0.41%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 24       | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 24       | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 24       | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 24       | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 24       | 0.39%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 24       | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 23       | 0.38%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 23       | 0.38%   |
| Intel Ethernet Connection (2) I218-LM                                          | 22       | 0.36%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 22       | 0.36%   |
| Intel Ethernet Controller X550                                                 | 21       | 0.34%   |
| Intel 82566DM Gigabit Network Connection                                       | 20       | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5240     | 73.66%  |
| WiFi     | 1769     | 24.87%  |
| Modem    | 92       | 1.29%   |
| Unknown  | 13       | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4573     | 86.06%  |
| WiFi     | 741      | 13.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3304     | 62.05%  |
| 2     | 1488     | 27.94%  |
| 3     | 310      | 5.82%   |
| 4     | 87       | 1.63%   |
| 0     | 48       | 0.9%    |
| 6     | 31       | 0.58%   |
| 5     | 29       | 0.54%   |
| 8     | 9        | 0.17%   |
| 7     | 8        | 0.15%   |
| 9     | 4        | 0.08%   |
| 12    | 3        | 0.06%   |
| 33    | 1        | 0.02%   |
| 21    | 1        | 0.02%   |
| 17    | 1        | 0.02%   |
| 13    | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 4384     | 81.88%  |
| Yes     | 969      | 18.1%   |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 670      | 44.11%  |
| Cambridge Silicon Radio         | 285      | 18.76%  |
| Realtek Semiconductor           | 137      | 9.02%   |
| ASUSTek Computer                | 94       | 6.19%   |
| MediaTek                        | 73       | 4.81%   |
| Broadcom                        | 69       | 4.54%   |
| Qualcomm Atheros Communications | 53       | 3.49%   |
| IMC Networks                    | 35       | 2.3%    |
| TP-Link                         | 22       | 1.45%   |
| Foxconn / Hon Hai               | 19       | 1.25%   |
| Apple                           | 15       | 0.99%   |
| Edimax Technology               | 6        | 0.39%   |
| Realtek                         | 5        | 0.33%   |
| Integrated System Solution      | 5        | 0.33%   |
| Belkin Components               | 5        | 0.33%   |
| Lite-On Technology              | 4        | 0.26%   |
| Actions                         | 4        | 0.26%   |
| Micro Star International        | 3        | 0.2%    |
| Dynex                           | 3        | 0.2%    |
| Unknown                         | 3        | 0.2%    |
| Toshiba                         | 1        | 0.07%   |
| Sitecom Europe                  | 1        | 0.07%   |
| SINO WEALTH                     | 1        | 0.07%   |
| Qcom                            | 1        | 0.07%   |
| Microsoft                       | 1        | 0.07%   |
| Kensington                      | 1        | 0.07%   |
| HTC (High Tech Computer)        | 1        | 0.07%   |
| Hewlett-Packard                 | 1        | 0.07%   |
| Com One                         | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 285      | 18.75%  |
| Intel AX200 Bluetooth                                 | 178      | 11.71%  |
| Intel Bluetooth wireless interface                    | 118      | 7.76%   |
| Realtek Bluetooth Radio                               | 113      | 7.43%   |
| Intel Wireless-AC 3168 Bluetooth                      | 74       | 4.87%   |
| MediaTek Wireless_Device                              | 73       | 4.8%    |
| Intel AX210 Bluetooth                                 | 69       | 4.54%   |
| Intel AX201 Bluetooth                                 | 62       | 4.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 52       | 3.42%   |
| Intel AX211 Bluetooth                                 | 49       | 3.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 47       | 3.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 30       | 1.97%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 30       | 1.97%   |
| Intel Bluetooth Device                                | 29       | 1.91%   |
| TP-Link UB500 Adapter                                 | 22       | 1.45%   |
| Qualcomm Atheros  Bluetooth Device                    | 20       | 1.32%   |
| IMC Networks Bluetooth Radio                          | 19       | 1.25%   |
| ASUS ASUS USB-BT500                                   | 19       | 1.25%   |
| Foxconn / Hon Hai Wireless_Device                     | 13       | 0.86%   |
| ASUS Bluetooth Adapter                                | 12       | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 10       | 0.66%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 10       | 0.66%   |
| ASUS Bluetooth Radio                                  | 10       | 0.66%   |
| Realtek  Bluetooth 4.2 Adapter                        | 9        | 0.59%   |
| IMC Networks Wireless_Device                          | 8        | 0.53%   |
| IMC Networks Bluetooth Device                         | 7        | 0.46%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 7        | 0.46%   |
| Apple Bluetooth Host Controller                       | 7        | 0.46%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 6        | 0.39%   |
| ASUS BCM20702A0                                       | 6        | 0.39%   |
| Realtek 802.11ac WLAN Adapter                         | 5        | 0.33%   |
| Realtek Bluetooth Radio                               | 5        | 0.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 5        | 0.33%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)       | 5        | 0.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 5        | 0.33%   |
| ASUS Qualcomm Bluetooth 4.1                           | 5        | 0.33%   |
| ASUS Bluetooth Device                                 | 5        | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 5        | 0.33%   |
| Realtek RTL8821A Bluetooth                            | 4        | 0.26%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4        | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 3237     | 40.43%  |
| AMD                                          | 1969     | 24.59%  |
| Nvidia                                       | 1670     | 20.86%  |
| C-Media Electronics                          | 187      | 2.34%   |
| Logitech                                     | 82       | 1.02%   |
| Creative Labs                                | 77       | 0.96%   |
| ASUSTek Computer                             | 60       | 0.75%   |
| Texas Instruments                            | 39       | 0.49%   |
| Micro Star International                     | 38       | 0.47%   |
| Generalplus Technology                       | 33       | 0.41%   |
| GN Netcom                                    | 30       | 0.37%   |
| KTMicro                                      | 29       | 0.36%   |
| JMTek                                        | 28       | 0.35%   |
| Focusrite-Novation                           | 28       | 0.35%   |
| VIA Technologies                             | 26       | 0.32%   |
| Zoran Co. Personal Media Division (Nogatech) | 24       | 0.3%    |
| Creative Technology                          | 24       | 0.3%    |
| SteelSeries ApS                              | 21       | 0.26%   |
| Kingston Technology                          | 21       | 0.26%   |
| Plantronics                                  | 17       | 0.21%   |
| Razer USA                                    | 16       | 0.2%    |
| BEHRINGER International                      | 16       | 0.2%    |
| Corsair                                      | 15       | 0.19%   |
| Dell                                         | 14       | 0.17%   |
| Blue Microphones                             | 13       | 0.16%   |
| Realtek Semiconductor                        | 12       | 0.15%   |
| GYROCOM C&C                                  | 12       | 0.15%   |
| RODE Microphones                             | 10       | 0.12%   |
| Cambridge Silicon Radio                      | 10       | 0.12%   |
| M-Audio                                      | 9        | 0.11%   |
| Silicon Integrated Systems [SiS]             | 8        | 0.1%    |
| Giga-Byte Technology                         | 8        | 0.1%    |
| DSEA A/S                                     | 8        | 0.1%    |
| BR25                                         | 8        | 0.1%    |
| Yamaha                                       | 7        | 0.09%   |
| Samson Technologies                          | 7        | 0.09%   |
| Tenx Technology                              | 6        | 0.07%   |
| Hewlett-Packard                              | 6        | 0.07%   |
| SAVITECH                                     | 5        | 0.06%   |
| Microsoft                                    | 5        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 461      | 4.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 455      | 4.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 384      | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 352      | 3.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 344      | 3.65%   |
| Intel 200 Series PCH HD Audio                                              | 275      | 2.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 274      | 2.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 248      | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 244      | 2.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 216      | 2.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 202      | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 190      | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 159      | 1.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 153      | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 140      | 1.48%   |
| AMD FCH Azalia Controller                                                  | 139      | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 138      | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 128      | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                              | 125      | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 121      | 1.28%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 118      | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                              | 105      | 1.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 105      | 1.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 93       | 0.99%   |
| Intel Alder Lake-S HD Audio Controller                                     | 92       | 0.97%   |
| Nvidia High Definition Audio Controller                                    | 84       | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 81       | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 79       | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 79       | 0.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 78       | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 76       | 0.81%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 75       | 0.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 74       | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 74       | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                              | 72       | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 68       | 0.72%   |
| AMD Navi 10 HDMI Audio                                                     | 68       | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                              | 67       | 0.71%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 67       | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                              | 63       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 912      | 18.8%   |
| Unknown                      | 743      | 15.31%  |
| Samsung Electronics          | 521      | 10.74%  |
| Crucial                      | 501      | 10.33%  |
| Corsair                      | 445      | 9.17%   |
| SK hynix                     | 402      | 8.29%   |
| G.Skill                      | 337      | 6.95%   |
| Micron Technology            | 188      | 3.87%   |
| Patriot                      | 104      | 2.14%   |
| A-DATA Technology            | 103      | 2.12%   |
| Unknown                      | 79       | 1.63%   |
| Team                         | 43       | 0.89%   |
| Ramaxel Technology           | 39       | 0.8%    |
| Unknown (ABCD)               | 32       | 0.66%   |
| Nanya Technology             | 31       | 0.64%   |
| AMD                          | 30       | 0.62%   |
| Transcend                    | 25       | 0.52%   |
| Elpida                       | 23       | 0.47%   |
| Hikvision                    | 21       | 0.43%   |
| Smart                        | 16       | 0.33%   |
| GOODRAM                      | 14       | 0.29%   |
| Apacer                       | 12       | 0.25%   |
| Hewlett-Packard              | 11       | 0.23%   |
| Timetec                      | 10       | 0.21%   |
| GeIL                         | 10       | 0.21%   |
| Avant                        | 10       | 0.21%   |
| Micro Memory Bank            | 9        | 0.19%   |
| Qimonda                      | 7        | 0.14%   |
| PNY                          | 7        | 0.14%   |
| Patriot Memory (PDP Systems) | 7        | 0.14%   |
| Unknown (0x5846)             | 6        | 0.12%   |
| Unifosa                      | 6        | 0.12%   |
| Unknown (0x0DD5)             | 5        | 0.1%    |
| Toshiba                      | 5        | 0.1%    |
| Kingmax                      | 5        | 0.1%    |
| Wilk Elektronik              | 4        | 0.08%   |
| Unknown (AB)                 | 4        | 0.08%   |
| Unknown (0x0B45)             | 4        | 0.08%   |
| Patriot Memory               | 4        | 0.08%   |
| KLEVV                        | 4        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown                                                      | 79       | 1.48%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 63       | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 46       | 0.86%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 42       | 0.79%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 41       | 0.77%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s     | 39       | 0.73%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4096MB DIMM DDR4 2133MT/s    | 38       | 0.71%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 33       | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 32       | 0.6%    |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s        | 31       | 0.58%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 26       | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 24       | 0.45%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 24       | 0.45%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s         | 24       | 0.45%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s          | 23       | 0.43%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s        | 23       | 0.43%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s          | 20       | 0.38%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s        | 20       | 0.38%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 20       | 0.38%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s      | 20       | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s       | 20       | 0.38%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s        | 19       | 0.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 19       | 0.36%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s          | 19       | 0.36%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s              | 18       | 0.34%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 17       | 0.32%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s       | 17       | 0.32%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                  | 17       | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 16       | 0.3%    |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 16       | 0.3%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 16       | 0.3%    |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s          | 16       | 0.3%    |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s       | 16       | 0.3%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 16       | 0.3%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s       | 16       | 0.3%    |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s       | 16       | 0.3%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 15       | 0.28%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 15       | 0.28%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                         | 15       | 0.28%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 15       | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1965     | 45.19%  |
| DDR3         | 1400     | 32.2%   |
| Unknown      | 272      | 6.26%   |
| DDR2         | 239      | 5.5%    |
| SDRAM        | 217      | 4.99%   |
| DDR5         | 129      | 2.97%   |
| LPDDR4       | 51       | 1.17%   |
| DDR          | 51       | 1.17%   |
| DRAM         | 15       | 0.34%   |
| LPDDR5       | 5        | 0.11%   |
| EPROM        | 2        | 0.05%   |
| LPDDR3       | 1        | 0.02%   |
| DDR2 FB-DIMM | 1        | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 3838     | 89.51%  |
| SODIMM       | 395      | 9.21%   |
| Row Of Chips | 24       | 0.56%   |
| RIMM         | 13       | 0.3%    |
| FB-DIMM      | 10       | 0.23%   |
| Unknown      | 7        | 0.16%   |
| Chip         | 1        | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 1474     | 31.24%  |
| 4096    | 1044     | 22.13%  |
| 16384   | 838      | 17.76%  |
| 2048    | 706      | 14.96%  |
| 32768   | 358      | 7.59%   |
| 1024    | 221      | 4.68%   |
| 512     | 48       | 1.02%   |
| 256     | 9        | 0.19%   |
| 65536   | 6        | 0.13%   |
| 49152   | 3        | 0.06%   |
| 24576   | 2        | 0.04%   |
| 3072    | 2        | 0.04%   |
| 128     | 2        | 0.04%   |
| 6144    | 1        | 0.02%   |
| 1536    | 1        | 0.02%   |
| 64      | 1        | 0.02%   |
| 16      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 812      | 17.14%  |
| 1333    | 481      | 10.15%  |
| 3200    | 447      | 9.44%   |
| 2667    | 346      | 7.3%    |
| 2400    | 295      | 6.23%   |
| 3600    | 287      | 6.06%   |
| 2133    | 249      | 5.26%   |
| 800     | 192      | 4.05%   |
| Unknown | 166      | 3.5%    |
| 667     | 127      | 2.68%   |
| 1866    | 112      | 2.36%   |
| 2666    | 100      | 2.11%   |
| 1867    | 76       | 1.6%    |
| 3733    | 62       | 1.31%   |
| 1066    | 60       | 1.27%   |
| 3800    | 59       | 1.25%   |
| 1800    | 54       | 1.14%   |
| 4800    | 52       | 1.1%    |
| 3000    | 52       | 1.1%    |
| 2933    | 52       | 1.1%    |
| 3400    | 51       | 1.08%   |
| 1067    | 37       | 0.78%   |
| 6000    | 31       | 0.65%   |
| 3466    | 28       | 0.59%   |
| 2866    | 27       | 0.57%   |
| 3866    | 26       | 0.55%   |
| 400     | 25       | 0.53%   |
| 533     | 23       | 0.49%   |
| 1334    | 21       | 0.44%   |
| 3933    | 20       | 0.42%   |
| 3666    | 20       | 0.42%   |
| 5200    | 17       | 0.36%   |
| 3534    | 17       | 0.36%   |
| 6400    | 16       | 0.34%   |
| 4333    | 16       | 0.34%   |
| 3100    | 16       | 0.34%   |
| 3266    | 15       | 0.32%   |
| 1648    | 15       | 0.32%   |
| 5600    | 14       | 0.3%    |
| 2048    | 14       | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 61       | 30.2%   |
| Brother Industries     | 45       | 22.28%  |
| Canon                  | 26       | 12.87%  |
| Samsung Electronics    | 15       | 7.43%   |
| Seiko Epson            | 9        | 4.46%   |
| Dymo-CoStar            | 7        | 3.47%   |
| Lexmark International  | 6        | 2.97%   |
| Prolific Technology    | 5        | 2.48%   |
| Zebra                  | 4        | 1.98%   |
| Xerox                  | 4        | 1.98%   |
| Pantum                 | 4        | 1.98%   |
| QinHeng Electronics    | 3        | 1.49%   |
| Kyocera                | 2        | 0.99%   |
| STMicroelectronics     | 1        | 0.5%    |
| Ricoh                  | 1        | 0.5%    |
| Printer                | 1        | 0.5%    |
| Oki Data               | 1        | 0.5%    |
| nemonic                | 1        | 0.5%    |
| Konica Minolta         | 1        | 0.5%    |
| GODEX INTERNATIONAL    | 1        | 0.5%    |
| Dell                   | 1        | 0.5%    |
| Datamax-O'Neil         | 1        | 0.5%    |
| Custom Engineering SPA | 1        | 0.5%    |
| Apple                  | 1        | 0.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                          | 6        | 2.97%   |
| Prolific PL2305 Parallel Port                             | 5        | 2.48%   |
| HP LaserJet 1200                                          | 5        | 2.48%   |
| Xerox B205                                                | 3        | 1.49%   |
| Samsung ML-1660 Series                                    | 3        | 1.49%   |
| QinHeng CH340S                                            | 3        | 1.49%   |
| HP LaserJet Pro M404-M405                                 | 3        | 1.49%   |
| HP LaserJet M101-M106                                     | 3        | 1.49%   |
| HP DeskJet 2700 series                                    | 3        | 1.49%   |
| Canon LiDE 400                                            | 3        | 1.49%   |
| Brother HL-52x0 series                                    | 3        | 1.49%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 0.99%   |
| Samsung M2020 Series                                      | 2        | 0.99%   |
| Pantum P2500W series                                      | 2        | 0.99%   |
| Lexmark International CS417dn                             | 2        | 0.99%   |
| HP LaserJet P1005                                         | 2        | 0.99%   |
| HP LaserJet 400 M401dne                                   | 2        | 0.99%   |
| HP HP LaserJet M14-M17                                    | 2        | 0.99%   |
| HP ENVY Photo 6200 series                                 | 2        | 0.99%   |
| HP ENVY 5540 series                                       | 2        | 0.99%   |
| HP ENVY 4520 series                                       | 2        | 0.99%   |
| HP DeskJet 2130 series                                    | 2        | 0.99%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 0.99%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 2        | 0.99%   |
| Canon PIXMA MG3600 Series                                 | 2        | 0.99%   |
| Canon MF4410                                              | 2        | 0.99%   |
| Canon MF4010 series                                       | 2        | 0.99%   |
| Canon MF3010                                              | 2        | 0.99%   |
| Brother MFC-7460DN                                        | 2        | 0.99%   |
| Brother HL-L2300D series                                  | 2        | 0.99%   |
| Brother HL-3040CN series                                  | 2        | 0.99%   |
| Brother HL-2030 Laser Printer                             | 2        | 0.99%   |
| Brother HL-1110 series                                    | 2        | 0.99%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 0.5%    |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 0.5%    |
| Zebra ZTC S4M-200dpi ZPL                                  | 1        | 0.5%    |
| Zebra Thrmal 2844                                         | 1        | 0.5%    |
| Xerox Phaser 3260                                         | 1        | 0.5%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.5%    |
| Seiko Epson XP-205 207 Series                             | 1        | 0.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 38       | 64.41%  |
| Seiko Epson        | 11       | 18.64%  |
| Hewlett-Packard    | 4        | 6.78%   |
| Mustek Systems     | 2        | 3.39%   |
| AGFA-Gevaert NV    | 2        | 3.39%   |
| Ultima Electronics | 1        | 1.69%   |
| Plustek            | 1        | 1.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 8        | 13.56%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 6        | 10.17%  |
| Canon CanoScan LiDE 210                                                               | 6        | 10.17%  |
| Canon CanoScan LiDE 220                                                               | 4        | 6.78%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 3        | 5.08%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 3        | 5.08%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 3.39%   |
| Canon CanoScan LiDE 60                                                                | 2        | 3.39%   |
| Canon CanoScan LIDE 25                                                                | 2        | 3.39%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2        | 3.39%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 1.69%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 1.69%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1        | 1.69%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 1.69%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1        | 1.69%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 1.69%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1        | 1.69%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 1.69%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 1.69%   |
| Plustek 1200dpi USB Scanner                                                           | 1        | 1.69%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 1        | 1.69%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1        | 1.69%   |
| HP ScanJet Pro 2500 f1                                                                | 1        | 1.69%   |
| HP ScanJet 82x0C                                                                      | 1        | 1.69%   |
| HP ScanJet 3970c                                                                      | 1        | 1.69%   |
| HP Scanjet 300                                                                        | 1        | 1.69%   |
| Canon CanoScan 9000F Mark II                                                          | 1        | 1.69%   |
| Canon CanoScan 8800F                                                                  | 1        | 1.69%   |
| Canon CanoScan 5600F                                                                  | 1        | 1.69%   |
| Canon CanoScan 4400F                                                                  | 1        | 1.69%   |
| Canon CanoScan 1220U                                                                  | 1        | 1.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 332      | 42.03%  |
| Microdia                               | 63       | 7.97%   |
| Microsoft                              | 49       | 6.2%    |
| Sunplus Innovation Technology          | 33       | 4.18%   |
| Generalplus Technology                 | 32       | 4.05%   |
| Samsung Electronics                    | 29       | 3.67%   |
| Creative Technology                    | 18       | 2.28%   |
| Apple                                  | 16       | 2.03%   |
| KYE Systems (Mouse Systems)            | 15       | 1.9%    |
| Jieli Technology                       | 15       | 1.9%    |
| Z-Star Microelectronics                | 14       | 1.77%   |
| GEMBIRD                                | 11       | 1.39%   |
| ARC International                      | 11       | 1.39%   |
| Realtek Semiconductor                  | 10       | 1.27%   |
| Chicony Electronics                    | 9        | 1.14%   |
| MacroSilicon                           | 8        | 1.01%   |
| AVerMedia Technologies                 | 7        | 0.89%   |
| Trust                                  | 5        | 0.63%   |
| Huawei Technologies                    | 5        | 0.63%   |
| Hewlett-Packard                        | 5        | 0.63%   |
| 2M UVC CAMERA                          | 5        | 0.63%   |
| Razer USA                              | 4        | 0.51%   |
| Novatek Microelectronics               | 4        | 0.51%   |
| Genesys Logic                          | 4        | 0.51%   |
| Cubeternet                             | 4        | 0.51%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.51%   |
| Aveo Technology                        | 4        | 0.51%   |
| Sunplus IT                             | 3        | 0.38%   |
| Quanta                                 | 3        | 0.38%   |
| IMC Networks                           | 3        | 0.38%   |
| Google                                 | 3        | 0.38%   |
| Anker PowerConf C200                   | 3        | 0.38%   |
| Xiongmai                               | 2        | 0.25%   |
| Valve Software                         | 2        | 0.25%   |
| ValueHD                                | 2        | 0.25%   |
| Tobii Technology AB                    | 2        | 0.25%   |
| Syntek                                 | 2        | 0.25%   |
| Ruision                                | 2        | 0.25%   |
| Pixart Imaging                         | 2        | 0.25%   |
| Nintendo                               | 2        | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 89       | 11.18%  |
| Logitech HD Pro Webcam C920               | 46       | 5.78%   |
| Logitech C922 Pro Stream Webcam           | 32       | 4.02%   |
| Samsung Galaxy series, misc. (MTP mode)   | 28       | 3.52%   |
| Microsoft LifeCam HD-3000                 | 28       | 3.52%   |
| Microdia USB 2.0 Camera                   | 21       | 2.64%   |
| Generalplus CAMERA - UVC                  | 20       | 2.51%   |
| Microdia Webcam Vitade AF                 | 17       | 2.14%   |
| Logitech HD Webcam C525                   | 17       | 2.14%   |
| Logitech Webcam C170                      | 16       | 2.01%   |
| Logitech Webcam C310                      | 15       | 1.88%   |
| Logitech C920 PRO HD Webcam               | 15       | 1.88%   |
| Jieli USB PHY 2.0                         | 15       | 1.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 15       | 1.88%   |
| Sunplus PC Camera                         | 11       | 1.38%   |
| Logitech HD Webcam C615                   | 11       | 1.38%   |
| KYE Systems (Mouse Systems) Genius Webcam | 11       | 1.38%   |
| Sunplus Full HD webcam                    | 9        | 1.13%   |
| Logitech HD Webcam C910                   | 9        | 1.13%   |
| Generalplus 808 Camera                    | 9        | 1.13%   |
| Z-Star Venus USB2.0 Camera                | 8        | 1.01%   |
| Microdia Integrated Camera                | 8        | 1.01%   |
| Logitech BRIO Ultra HD Webcam             | 8        | 1.01%   |
| ARC International Camera                  | 8        | 1.01%   |
| Microdia Camera                           | 6        | 0.75%   |
| Logitech Webcam C925e                     | 6        | 0.75%   |
| Logitech StreamCam                        | 6        | 0.75%   |
| GEMBIRD USB2.0 PC CAMERA                  | 6        | 0.75%   |
| Microsoft LifeCam HD-5000                 | 5        | 0.63%   |
| MacroSilicon MiraBox Capture              | 5        | 0.63%   |
| Huawei HiCamera                           | 5        | 0.63%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam       | 5        | 0.63%   |
| Razer USA Gaming Webcam [Kiyo]            | 4        | 0.5%    |
| Novatek HP High Definition 2MP Webcam     | 4        | 0.5%    |
| Microdia Sonix USB 2.0 Camera             | 4        | 0.5%    |
| Logitech Webcam Pro 9000                  | 4        | 0.5%    |
| Logitech Webcam C210                      | 4        | 0.5%    |
| Logitech QuickCam Pro 9000                | 4        | 0.5%    |
| Logitech QuickCam E 3500                  | 4        | 0.5%    |
| Logitech HD Webcam C510                   | 4        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Validity Sensors      | 1        | 25%     |
| Synaptics             | 1        | 25%     |
| Microsoft             | 1        | 25%     |
| Elan Microelectronics | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 25%     |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 25%     |
| Microsoft Fingerprint Reader                 | 1        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| SCM Microsystems           | 6        | 12.24%  |
| Gemalto (was Gemplus)      | 6        | 12.24%  |
| Alcor Micro                | 6        | 12.24%  |
| Realtek Semiconductor      | 4        | 8.16%   |
| Chicony Electronics        | 4        | 8.16%   |
| Cherry                     | 4        | 8.16%   |
| Advanced Card Systems      | 4        | 8.16%   |
| Reiner SCT Kartensysteme   | 3        | 6.12%   |
| Clay Logic                 | 3        | 6.12%   |
| Aladdin Knowledge Systems  | 3        | 6.12%   |
| Yubico.com                 | 2        | 4.08%   |
| OmniKey                    | 1        | 2.04%   |
| Lenovo                     | 1        | 2.04%   |
| Feitian Technologies       | 1        | 2.04%   |
| Athena Smartcard Solutions | 1        | 2.04%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 5        | 10.2%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 5        | 10.2%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 8.16%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 4        | 8.16%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 6.12%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 3        | 6.12%   |
| Aladdin Knowledge Systems Token JC                                         | 3        | 6.12%   |
| Clay Logic Nitrokey Pro                                                    | 2        | 4.08%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                | 2        | 4.08%   |
| Advanced Card Systems ACR122U                                              | 2        | 4.08%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 1        | 2.04%   |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.04%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 2.04%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.04%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 2.04%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.04%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 2.04%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 2.04%   |
| Feitian Technologies SCR301                                                | 1        | 2.04%   |
| Clay Logic Nitrokey Start                                                  | 1        | 2.04%   |
| Cherry SmartTerminal XX1X                                                  | 1        | 2.04%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                 | 1        | 2.04%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 1        | 2.04%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 2.04%   |
| Advanced Card Systems ACR39U                                               | 1        | 2.04%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 2.04%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3513     | 65.39%  |
| 1     | 1592     | 29.64%  |
| 2     | 228      | 4.24%   |
| 3     | 27       | 0.5%    |
| 5     | 5        | 0.09%   |
| 4     | 4        | 0.07%   |
| 6     | 2        | 0.04%   |
| 7     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1400     | 68.29%  |
| Net/wireless             | 217      | 10.59%  |
| Unassigned class         | 102      | 4.98%   |
| Communication controller | 100      | 4.88%   |
| Sound                    | 41       | 2%      |
| Multimedia controller    | 39       | 1.9%    |
| Bluetooth                | 31       | 1.51%   |
| Chipcard                 | 23       | 1.12%   |
| Net/ethernet             | 20       | 0.98%   |
| Camera                   | 18       | 0.88%   |
| Card reader              | 12       | 0.59%   |
| Storage/raid             | 10       | 0.49%   |
| Storage/ide              | 7        | 0.34%   |
| Network                  | 7        | 0.34%   |
| Modem                    | 6        | 0.29%   |
| Fingerprint reader       | 4        | 0.2%    |
| Dvb card                 | 4        | 0.2%    |
| Tv card                  | 3        | 0.15%   |
| Wireless                 | 2        | 0.1%    |
| Storage/nvme             | 2        | 0.1%    |
| Storage                  | 2        | 0.1%    |


LMDE 5 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 209

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Q87M-D2H                    | [56421d7b0f](https://linux-hardware.org/?probe=56421d7b0f) | Jun 09, 2023 |
| AZW           | GK mini                     | [d9d37cb11a](https://linux-hardware.org/?probe=d9d37cb11a) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | [ac442da472](https://linux-hardware.org/?probe=ac442da472) | Jun 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [05a3b3210a](https://linux-hardware.org/?probe=05a3b3210a) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | [eeaf6dbd4c](https://linux-hardware.org/?probe=eeaf6dbd4c) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| Medion        | TJ4125                      | [3faed0102f](https://linux-hardware.org/?probe=3faed0102f) | Jun 04, 2023 |
| Gigabyte      | A520M S2H                   | [81caf6e8cf](https://linux-hardware.org/?probe=81caf6e8cf) | Jun 04, 2023 |
| Gigabyte      | A520M S2H                   | [0169222312](https://linux-hardware.org/?probe=0169222312) | Jun 03, 2023 |
| Intel         | B75                         | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| Medion        | TJ4125                      | [6244ae0e43](https://linux-hardware.org/?probe=6244ae0e43) | Jun 02, 2023 |
| Unknown       | X99                         | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| Gigabyte      | Q87M-D2H                    | [8f3525a119](https://linux-hardware.org/?probe=8f3525a119) | Jun 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [7400ec0f1a](https://linux-hardware.org/?probe=7400ec0f1a) | May 31, 2023 |
| Gigabyte      | Q87M-D2H                    | [5e7eb5b41c](https://linux-hardware.org/?probe=5e7eb5b41c) | May 29, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bf6e9cf4d0](https://linux-hardware.org/?probe=bf6e9cf4d0) | May 26, 2023 |
| Gigabyte      | Q87M-D2H                    | [a3e5c89fe6](https://linux-hardware.org/?probe=a3e5c89fe6) | May 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [3c82eec4d2](https://linux-hardware.org/?probe=3c82eec4d2) | May 23, 2023 |
| Gigabyte      | Q87M-D2H                    | [ee4eca623f](https://linux-hardware.org/?probe=ee4eca623f) | May 21, 2023 |
| MSI           | B350M BAZOOKA               | [49e536226c](https://linux-hardware.org/?probe=49e536226c) | May 19, 2023 |
| MSI           | B350M BAZOOKA               | [2abefd21ea](https://linux-hardware.org/?probe=2abefd21ea) | May 19, 2023 |
| Alienware     | 04VWF2 A00                  | [311799f80a](https://linux-hardware.org/?probe=311799f80a) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Gigabyte      | E2100N                      | [cce0e87f11](https://linux-hardware.org/?probe=cce0e87f11) | May 17, 2023 |
| Gigabyte      | Q87M-D2H                    | [98f104037a](https://linux-hardware.org/?probe=98f104037a) | May 15, 2023 |
| AZW           | MINI S                      | [72c9908514](https://linux-hardware.org/?probe=72c9908514) | May 14, 2023 |
| AZW           | MINI S                      | [788d932e58](https://linux-hardware.org/?probe=788d932e58) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | [42db835c47](https://linux-hardware.org/?probe=42db835c47) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | [3f4eafaf9c](https://linux-hardware.org/?probe=3f4eafaf9c) | May 13, 2023 |
| Medion        | TJ4125                      | [a0fcafbf70](https://linux-hardware.org/?probe=a0fcafbf70) | May 12, 2023 |
| Medion        | TJ4125                      | [4d7467c0bc](https://linux-hardware.org/?probe=4d7467c0bc) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [99c9764b7e](https://linux-hardware.org/?probe=99c9764b7e) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [a70e02af94](https://linux-hardware.org/?probe=a70e02af94) | May 09, 2023 |
| ASRock        | 775Dual-VSTA                | [89ccdd7262](https://linux-hardware.org/?probe=89ccdd7262) | May 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [7d861acbd6](https://linux-hardware.org/?probe=7d861acbd6) | May 07, 2023 |
| Medion        | TJ4125                      | [583b49089e](https://linux-hardware.org/?probe=583b49089e) | May 07, 2023 |
| Medion        | TJ4125                      | [2255946fa5](https://linux-hardware.org/?probe=2255946fa5) | May 05, 2023 |
| ASRock        | B450M Pro4                  | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| Gigabyte      | Q87M-D2H                    | [ae586408c4](https://linux-hardware.org/?probe=ae586408c4) | May 02, 2023 |
| ASUSTek       | P7Q57-M DO                  | [897fc61b8c](https://linux-hardware.org/?probe=897fc61b8c) | Apr 30, 2023 |
| ASUSTek       | P7Q57-M DO                  | [4f502dcb59](https://linux-hardware.org/?probe=4f502dcb59) | Apr 30, 2023 |
| Gigabyte      | Q87M-D2H                    | [16279b3c8b](https://linux-hardware.org/?probe=16279b3c8b) | Apr 30, 2023 |
| Medion        | TJ4125                      | [ad46974b2a](https://linux-hardware.org/?probe=ad46974b2a) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| Medion        | TJ4125                      | [8f319cff50](https://linux-hardware.org/?probe=8f319cff50) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [6503ed5a4c](https://linux-hardware.org/?probe=6503ed5a4c) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [5827cd2604](https://linux-hardware.org/?probe=5827cd2604) | Apr 23, 2023 |
| Medion        | TJ4125                      | [faa241e4bc](https://linux-hardware.org/?probe=faa241e4bc) | Apr 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [93a6cb1a8a](https://linux-hardware.org/?probe=93a6cb1a8a) | Apr 22, 2023 |
| Gigabyte      | A520M DS3H                  | [c4b35f2a05](https://linux-hardware.org/?probe=c4b35f2a05) | Apr 16, 2023 |
| Intel         | SHARKBAY                    | [3bb10a5574](https://linux-hardware.org/?probe=3bb10a5574) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d6f8675bc9](https://linux-hardware.org/?probe=d6f8675bc9) | Apr 11, 2023 |
| Intel         | SHARKBAY                    | [4b50be64da](https://linux-hardware.org/?probe=4b50be64da) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | [d041ee40cc](https://linux-hardware.org/?probe=d041ee40cc) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | [2c83dbd3ef](https://linux-hardware.org/?probe=2c83dbd3ef) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | [d1e9eaed8b](https://linux-hardware.org/?probe=d1e9eaed8b) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | [82a96ca347](https://linux-hardware.org/?probe=82a96ca347) | Apr 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [4552b7c999](https://linux-hardware.org/?probe=4552b7c999) | Apr 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [b627db43dd](https://linux-hardware.org/?probe=b627db43dd) | Apr 01, 2023 |
| ASUSTek       | P7P55D                      | [b50f27ad05](https://linux-hardware.org/?probe=b50f27ad05) | Mar 31, 2023 |
| Dell          | 00F82W A02                  | [8bf22304e0](https://linux-hardware.org/?probe=8bf22304e0) | Mar 31, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [b53d1202dc](https://linux-hardware.org/?probe=b53d1202dc) | Mar 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [dd71be113d](https://linux-hardware.org/?probe=dd71be113d) | Mar 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [e5cef530ff](https://linux-hardware.org/?probe=e5cef530ff) | Mar 27, 2023 |
| Gigabyte      | Q87M-D2H                    | [8690ae647e](https://linux-hardware.org/?probe=8690ae647e) | Mar 26, 2023 |
| BESSTAR Te... | TH50                        | [7165e2c0d0](https://linux-hardware.org/?probe=7165e2c0d0) | Mar 21, 2023 |
| Gigabyte      | A520M DS3H                  | [79104099a5](https://linux-hardware.org/?probe=79104099a5) | Mar 20, 2023 |
| Gigabyte      | Q87M-D2H                    | [fb5c67c585](https://linux-hardware.org/?probe=fb5c67c585) | Mar 19, 2023 |
| Gigabyte      | Q87M-D2H                    | [7051e25dc0](https://linux-hardware.org/?probe=7051e25dc0) | Mar 18, 2023 |
| ASRock        | B365M Pro4                  | [e237668eb2](https://linux-hardware.org/?probe=e237668eb2) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [29f50579db](https://linux-hardware.org/?probe=29f50579db) | Mar 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bf2b5490ba](https://linux-hardware.org/?probe=bf2b5490ba) | Mar 15, 2023 |
| Gigabyte      | Z87X-OC Force-CF            | [17deac9c67](https://linux-hardware.org/?probe=17deac9c67) | Mar 12, 2023 |
| SiYW          | V200 Series                 | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| ASUSTek       | PRIME A320M-K               | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| MSI           | 970A-G46                    | [8c3d20fa95](https://linux-hardware.org/?probe=8c3d20fa95) | Mar 08, 2023 |
| Dell          | 096JG8 A01                  | [fddb284e37](https://linux-hardware.org/?probe=fddb284e37) | Mar 03, 2023 |
| Gigabyte      | Z590 GAMING X               | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Medion        | MS-7800                     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| Dell          | 0NK70N A03                  | [3da6e11665](https://linux-hardware.org/?probe=3da6e11665) | Feb 18, 2023 |
| ASUSTek       | P7P55D                      | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | [2c98a8340f](https://linux-hardware.org/?probe=2c98a8340f) | Feb 17, 2023 |
| Dell          | 0MF24N A03                  | [e48d83d96d](https://linux-hardware.org/?probe=e48d83d96d) | Feb 15, 2023 |
| Gigabyte      | B450M S2H                   | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| HP            | 843C                        | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| Gigabyte      | B450 AORUS M                | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [1985f76677](https://linux-hardware.org/?probe=1985f76677) | Feb 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [6c094e2027](https://linux-hardware.org/?probe=6c094e2027) | Jan 31, 2023 |
| ASUSTek       | P7P55D                      | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [40152faf5b](https://linux-hardware.org/?probe=40152faf5b) | Jan 28, 2023 |
| Intel         | H61M-DS2V                   | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| ASRock        | Z87 Pro3                    | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| Dell          | 0C27VV A01                  | [e43d24d2b6](https://linux-hardware.org/?probe=e43d24d2b6) | Jan 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c5dd2e8482](https://linux-hardware.org/?probe=c5dd2e8482) | Jan 19, 2023 |
| Gigabyte      | H310M S2H                   | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [563d7aaba5](https://linux-hardware.org/?probe=563d7aaba5) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Intel         | B75                         | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| MSI           | FM2-A55M-E33                | [1ce8a2718b](https://linux-hardware.org/?probe=1ce8a2718b) | Jan 07, 2023 |
| Acer          | Aspire XC-780               | [66823871a5](https://linux-hardware.org/?probe=66823871a5) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Gigabyte      | GA-970A-D3                  | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Dell          | 0C27VV A01                  | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| MSI           | PRO B660M-A DDR4            | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Dell          | 0T1D10 A01                  | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell          | 0T1D10 A01                  | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| ASUSTek       | P7P55D                      | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW          | V200 Series                 | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| HP            | 8299                        | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI           | A320M-A PRO MAX             | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Dell          | 0C27VV A01                  | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| Dell          | 0C27VV A01                  | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| Dell          | 0N826N A03                  | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| MSI           | A320M-A PRO MAX             | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| HP            | 8299                        | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| HP            | 8299                        | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| AZW           | MINI S                      | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Gateway       | DX4870                      | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Dell          | 0XC837                      | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| MSI           | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | PRIME H610M-E D4            | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell          | 0FJ030                      | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Pegatron      | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| ASUSTek       | P5K-E                       | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Dell          | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| MSI           | B85I                        | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Gigabyte      | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| ASRock        | H61M-DGS                    | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| HP            | 8433 11                     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Gigabyte      | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek       | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Dell          | 0XR1GT A00                  | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Lenovo        | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Dell          | 0XR1GT A00                  | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| Acer          | Seawolf                     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Intel         | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP            | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| ASRock        | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| ASUSTek       | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Acer          | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek       | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| ASUSTek       | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| HP            | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.0-21-amd64          | 28       | 20.9%   |
| 5.10.0-12-amd64          | 20       | 14.93%  |
| 5.10.0-20-amd64          | 12       | 8.96%   |
| 5.10.0-23-amd64          | 11       | 8.21%   |
| 5.10.0-17-amd64          | 11       | 8.21%   |
| 5.10.0-14-amd64          | 10       | 7.46%   |
| 5.10.0-13-amd64          | 10       | 7.46%   |
| 5.10.0-18-amd64          | 9        | 6.72%   |
| 5.10.0-19-amd64          | 8        | 5.97%   |
| 5.10.0-22-amd64          | 5        | 3.73%   |
| 5.10.0-15-amd64          | 3        | 2.24%   |
| 5.10.0-16-amd64          | 2        | 1.49%   |
| 6.1.0-0.deb11.7-amd64    | 1        | 0.75%   |
| 6.1.0-0.deb11.5-amd64    | 1        | 0.75%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 0.75%   |
| 5.19.0-0.deb11.2-amd64   | 1        | 0.75%   |
| 5.10.0-13-686            | 1        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 117      | 96.69%  |
| 6.1.0   | 2        | 1.65%   |
| 6.0.2   | 1        | 0.83%   |
| 5.19.0  | 1        | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 117      | 96.69%  |
| 6.1     | 2        | 1.65%   |
| 6.0     | 1        | 0.83%   |
| 5.19    | 1        | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 119      | 99.17%  |
| i686   | 1        | 0.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 105      | 86.78%  |
| Cinnamon   | 11       | 9.09%   |
| MATE       | 3        | 2.48%   |
| XFCE       | 1        | 0.83%   |
| KDE5       | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 120      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 77       | 64.17%  |
| LightDM | 41       | 34.17%  |
| SDDM    | 1        | 0.83%   |
| GDM     | 1        | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 44       | 36.67%  |
| de_DE | 16       | 13.33%  |
| pt_BR | 11       | 9.17%   |
| ru_RU | 8        | 6.67%   |
| fr_FR | 6        | 5%      |
| it_IT | 5        | 4.17%   |
| en_GB | 4        | 3.33%   |
| es_ES | 3        | 2.5%    |
| en_CA | 3        | 2.5%    |
| sv_SE | 2        | 1.67%   |
| ru_UA | 2        | 1.67%   |
| pl_PL | 2        | 1.67%   |
| fr_CA | 2        | 1.67%   |
| en_AU | 2        | 1.67%   |
| sk_SK | 1        | 0.83%   |
| it_CH | 1        | 0.83%   |
| fr_BE | 1        | 0.83%   |
| es_PA | 1        | 0.83%   |
| es_NI | 1        | 0.83%   |
| es_AR | 1        | 0.83%   |
| en_ZA | 1        | 0.83%   |
| de_AT | 1        | 0.83%   |
| cs_CZ | 1        | 0.83%   |
| ar_EG | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 63       | 52.5%   |
| EFI  | 57       | 47.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 111      | 92.5%   |
| Tmpfs   | 4        | 3.33%   |
| Btrfs   | 3        | 2.5%    |
| Overlay | 2        | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 78       | 65%     |
| GPT     | 27       | 22.5%   |
| MBR     | 15       | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 104      | 86.67%  |
| Yes       | 16       | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 85%     |
| Yes       | 18       | 15%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 26       | 21.67%  |
| Gigabyte Technology | 21       | 17.5%   |
| MSI                 | 15       | 12.5%   |
| Dell                | 14       | 11.67%  |
| ASRock              | 7        | 5.83%   |
| Intel               | 6        | 5%      |
| Hewlett-Packard     | 6        | 5%      |
| Acer                | 4        | 3.33%   |
| Lenovo              | 3        | 2.5%    |
| AZW                 | 3        | 2.5%    |
| Medion              | 2        | 1.67%   |
| Fujitsu             | 2        | 1.67%   |
| SiYW                | 1        | 0.83%   |
| Samsung Electronics | 1        | 0.83%   |
| Pegatron            | 1        | 0.83%   |
| Packard Bell        | 1        | 0.83%   |
| Gateway             | 1        | 0.83%   |
| Foxconn             | 1        | 0.83%   |
| eMachines           | 1        | 0.83%   |
| Digiboard           | 1        | 0.83%   |
| BESSTAR Tech        | 1        | 0.83%   |
| ADVANSUS            | 1        | 0.83%   |
| Unknown             | 1        | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7B79                         | 2        | 1.67%   |
| Intel B75                           | 2        | 1.67%   |
| Gigabyte B450 AORUS M               | 2        | 1.67%   |
| AZW MINI S                          | 2        | 1.67%   |
| ASUS ROG STRIX B450-F GAMING        | 2        | 1.67%   |
| ASUS PRIME B350M-A                  | 2        | 1.67%   |
| SiYW V200 Series                    | 1        | 0.83%   |
| Samsung DeskTop System              | 1        | 0.83%   |
| Pegatron Pro 3015 Microtower PC     | 1        | 0.83%   |
| Packard Bell IMEDIA J9640           | 1        | 0.83%   |
| MSI MS-7D54                         | 1        | 0.83%   |
| MSI MS-7C95                         | 1        | 0.83%   |
| MSI MS-7C52                         | 1        | 0.83%   |
| MSI MS-7B23                         | 1        | 0.83%   |
| MSI MS-7B17                         | 1        | 0.83%   |
| MSI MS-7A40                         | 1        | 0.83%   |
| MSI MS-7A38                         | 1        | 0.83%   |
| MSI MS-7984                         | 1        | 0.83%   |
| MSI MS-7977                         | 1        | 0.83%   |
| MSI MS-7974                         | 1        | 0.83%   |
| MSI MS-7851                         | 1        | 0.83%   |
| MSI MS-7721                         | 1        | 0.83%   |
| MSI MS-7693                         | 1        | 0.83%   |
| Medion S23003                       | 1        | 0.83%   |
| Medion MS-7800                      | 1        | 0.83%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 0.83%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 0.83%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 0.83%   |
| Intel SHARKBAY                      | 1        | 0.83%   |
| Intel H61M-DS2V                     | 1        | 0.83%   |
| Intel DQ77MK AAG39642-400           | 1        | 0.83%   |
| Intel DB85FL AAG89861-202           | 1        | 0.83%   |
| HP Z820 Workstation                 | 1        | 0.83%   |
| HP Z600 Workstation                 | 1        | 0.83%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 0.83%   |
| HP EliteDesk 800 G3 SFF             | 1        | 0.83%   |
| HP Compaq Pro 6300 SFF              | 1        | 0.83%   |
| HP 290 G2 MT Business PC            | 1        | 0.83%   |
| Gigabyte Z87X-OC Force              | 1        | 0.83%   |
| Gigabyte Z68A-D3H-B3                | 1        | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 7        | 5.83%   |
| Dell Precision      | 4        | 3.33%   |
| Dell OptiPlex       | 4        | 3.33%   |
| ASUS ROG            | 4        | 3.33%   |
| Gigabyte B450       | 3        | 2.5%    |
| Acer Aspire         | 3        | 2.5%    |
| MSI MS-7B79         | 2        | 1.67%   |
| Lenovo ThinkCentre  | 2        | 1.67%   |
| Intel B75           | 2        | 1.67%   |
| Gigabyte B450M      | 2        | 1.67%   |
| Gigabyte A520M      | 2        | 1.67%   |
| Dell Vostro         | 2        | 1.67%   |
| Dell Inspiron       | 2        | 1.67%   |
| AZW MINI            | 2        | 1.67%   |
| SiYW V200           | 1        | 0.83%   |
| Samsung DeskTop     | 1        | 0.83%   |
| Pegatron Pro        | 1        | 0.83%   |
| Packard Bell IMEDIA | 1        | 0.83%   |
| MSI MS-7D54         | 1        | 0.83%   |
| MSI MS-7C95         | 1        | 0.83%   |
| MSI MS-7C52         | 1        | 0.83%   |
| MSI MS-7B23         | 1        | 0.83%   |
| MSI MS-7B17         | 1        | 0.83%   |
| MSI MS-7A40         | 1        | 0.83%   |
| MSI MS-7A38         | 1        | 0.83%   |
| MSI MS-7984         | 1        | 0.83%   |
| MSI MS-7977         | 1        | 0.83%   |
| MSI MS-7974         | 1        | 0.83%   |
| MSI MS-7851         | 1        | 0.83%   |
| MSI MS-7721         | 1        | 0.83%   |
| MSI MS-7693         | 1        | 0.83%   |
| Medion S23003       | 1        | 0.83%   |
| Medion MS-7800      | 1        | 0.83%   |
| Lenovo V55t-15ARE   | 1        | 0.83%   |
| Intel SHARKBAY      | 1        | 0.83%   |
| Intel H61M-DS2V     | 1        | 0.83%   |
| Intel DQ77MK        | 1        | 0.83%   |
| Intel DB85FL        | 1        | 0.83%   |
| HP Z820             | 1        | 0.83%   |
| HP Z600             | 1        | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 20%     |
| 2012 | 16       | 13.33%  |
| 2021 | 9        | 7.5%    |
| 2017 | 8        | 6.67%   |
| 2015 | 7        | 5.83%   |
| 2013 | 7        | 5.83%   |
| 2009 | 7        | 5.83%   |
| 2022 | 6        | 5%      |
| 2019 | 6        | 5%      |
| 2011 | 5        | 4.17%   |
| 2010 | 5        | 4.17%   |
| 2020 | 4        | 3.33%   |
| 2016 | 4        | 3.33%   |
| 2007 | 4        | 3.33%   |
| 2006 | 4        | 3.33%   |
| 2014 | 3        | 2.5%    |
| 2008 | 1        | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 120      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 118      | 97.52%  |
| Enabled  | 3        | 2.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 120      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 29       | 23.77%  |
| 8.01-16.0       | 23       | 18.85%  |
| 4.01-8.0        | 22       | 18.03%  |
| 32.01-64.0      | 21       | 17.21%  |
| 3.01-4.0        | 12       | 9.84%   |
| 1.01-2.0        | 6        | 4.92%   |
| 24.01-32.0      | 4        | 3.28%   |
| 64.01-256.0     | 2        | 1.64%   |
| More than 256.0 | 1        | 0.82%   |
| 2.01-3.0        | 1        | 0.82%   |
| 0.51-1.0        | 1        | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 47       | 36.15%  |
| 2.01-3.0   | 37       | 28.46%  |
| 4.01-8.0   | 18       | 13.85%  |
| 3.01-4.0   | 15       | 11.54%  |
| 0.51-1.0   | 6        | 4.62%   |
| 8.01-16.0  | 5        | 3.85%   |
| 24.01-32.0 | 1        | 0.77%   |
| 16.01-24.0 | 1        | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 43.8%   |
| 2      | 30       | 24.79%  |
| 3      | 18       | 14.88%  |
| 4      | 10       | 8.26%   |
| 5      | 7        | 5.79%   |
| 6      | 3        | 2.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 58.68%  |
| Yes       | 50       | 41.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 119      | 99.17%  |
| No        | 1        | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 52.89%  |
| Yes       | 57       | 47.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 70.83%  |
| Yes       | 35       | 29.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 29       | 24.17%  |
| Germany      | 18       | 15%     |
| Brazil       | 12       | 10%     |
| Russia       | 10       | 8.33%   |
| Italy        | 7        | 5.83%   |
| France       | 7        | 5.83%   |
| Canada       | 6        | 5%      |
| UK           | 3        | 2.5%    |
| Sweden       | 3        | 2.5%    |
| Spain        | 3        | 2.5%    |
| Australia    | 3        | 2.5%    |
| Ukraine      | 2        | 1.67%   |
| South Africa | 2        | 1.67%   |
| Poland       | 2        | 1.67%   |
| Venezuela    | 1        | 0.83%   |
| Turkey       | 1        | 0.83%   |
| Slovakia     | 1        | 0.83%   |
| Panama       | 1        | 0.83%   |
| Nicaragua    | 1        | 0.83%   |
| Netherlands  | 1        | 0.83%   |
| Mexico       | 1        | 0.83%   |
| Latvia       | 1        | 0.83%   |
| Kazakhstan   | 1        | 0.83%   |
| Bolivia      | 1        | 0.83%   |
| Belgium      | 1        | 0.83%   |
| Austria      | 1        | 0.83%   |
| Argentina    | 1        | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Berlin                   | 3        | 2.42%   |
| Montreal                 | 2        | 1.61%   |
| Melbourne                | 2        | 1.61%   |
| Frankfurt am Main        | 2        | 1.61%   |
| Delligsen                | 2        | 1.61%   |
| Columbia City            | 2        | 1.61%   |
| Belém                   | 2        | 1.61%   |
| Witzenhausen             | 1        | 0.81%   |
| Washington               | 1        | 0.81%   |
| Volta Redonda            | 1        | 0.81%   |
| Volgograd                | 1        | 0.81%   |
| Vitória da Conquista    | 1        | 0.81%   |
| Vincennes                | 1        | 0.81%   |
| Vicente Guerrero         | 1        | 0.81%   |
| Varese                   | 1        | 0.81%   |
| Ulyanovsk                | 1        | 0.81%   |
| Trieste                  | 1        | 0.81%   |
| Toronto                  | 1        | 0.81%   |
| Tolyatti                 | 1        | 0.81%   |
| Toledo                   | 1        | 0.81%   |
| Toccoa                   | 1        | 0.81%   |
| Tacoma                   | 1        | 0.81%   |
| Stockelsdorf             | 1        | 0.81%   |
| Stockbridge              | 1        | 0.81%   |
| Spruce Grove             | 1        | 0.81%   |
| Sollentuna               | 1        | 0.81%   |
| Solingen                 | 1        | 0.81%   |
| Schwelm                  | 1        | 0.81%   |
| Schruns                  | 1        | 0.81%   |
| Sao Lourenço            | 1        | 0.81%   |
| Santa Luzia              | 1        | 0.81%   |
| Santa Ana                | 1        | 0.81%   |
| Sant Feliu de Llobregat  | 1        | 0.81%   |
| San Miguel De Abona      | 1        | 0.81%   |
| San Antonio de Los Altos | 1        | 0.81%   |
| San Antonio              | 1        | 0.81%   |
| Rome                     | 1        | 0.81%   |
| Rio de Janeiro           | 1        | 0.81%   |
| Riga                     | 1        | 0.81%   |
| Reynoldsburg             | 1        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 42       | 69     | 19.81%  |
| Seagate                   | 34       | 47     | 16.04%  |
| Samsung Electronics       | 30       | 59     | 14.15%  |
| Kingston                  | 17       | 25     | 8.02%   |
| Toshiba                   | 13       | 15     | 6.13%   |
| Crucial                   | 11       | 13     | 5.19%   |
| Sandisk                   | 8        | 8      | 3.77%   |
| Hitachi                   | 5        | 6      | 2.36%   |
| China                     | 4        | 4      | 1.89%   |
| SPCC                      | 3        | 3      | 1.42%   |
| SK hynix                  | 3        | 4      | 1.42%   |
| Silicon Motion            | 3        | 4      | 1.42%   |
| PNY                       | 2        | 2      | 0.94%   |
| Phison                    | 2        | 4      | 0.94%   |
| Patriot                   | 2        | 2      | 0.94%   |
| Apple                     | 2        | 2      | 0.94%   |
| ADATA Technology          | 2        | 2      | 0.94%   |
| A-DATA Technology         | 2        | 2      | 0.94%   |
| XrayDisk                  | 1        | 2      | 0.47%   |
| WALRAM                    | 1        | 1      | 0.47%   |
| Unknown                   | 1        | 1      | 0.47%   |
| Transcend                 | 1        | 2      | 0.47%   |
| TGT                       | 1        | 1      | 0.47%   |
| Team                      | 1        | 1      | 0.47%   |
| TakeMS                    | 1        | 1      | 0.47%   |
| T-FORCE                   | 1        | 1      | 0.47%   |
| Phison Electronics        | 1        | 1      | 0.47%   |
| OCZ-VERTEX                | 1        | 1      | 0.47%   |
| OCZ                       | 1        | 1      | 0.47%   |
| NGFF                      | 1        | 1      | 0.47%   |
| Netac                     | 1        | 1      | 0.47%   |
| Micron/Crucial Technology | 1        | 1      | 0.47%   |
| Micron Technology         | 1        | 1      | 0.47%   |
| LITEONIT                  | 1        | 1      | 0.47%   |
| Intenso                   | 1        | 1      | 0.47%   |
| Intel                     | 1        | 1      | 0.47%   |
| Hewlett-Packard           | 1        | 1      | 0.47%   |
| GOODRAM                   | 1        | 1      | 0.47%   |
| Gigabyte Technology       | 1        | 2      | 0.47%   |
| Emtec                     | 1        | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 6        | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 4        | 1.63%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.63%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.63%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 1.22%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB   | 3        | 1.22%   |
| Seagate ST500DM002-1BD142 500GB                     | 3        | 1.22%   |
| Samsung SSD 970 EVO 500GB                           | 3        | 1.22%   |
| Samsung SSD 850 EVO 500GB                           | 3        | 1.22%   |
| Crucial CT480BX500SSD1 480GB                        | 3        | 1.22%   |
| WDC WD3003FZEX-00Z4SA0 3TB                          | 2        | 0.81%   |
| Toshiba HDWD110 1TB                                 | 2        | 0.81%   |
| Seagate ST3320418AS 320GB                           | 2        | 0.81%   |
| Seagate ST3250318AS 250GB                           | 2        | 0.81%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 0.81%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2        | 0.81%   |
| Seagate ST1000DM003-1ER162 1TB                      | 2        | 0.81%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 0.81%   |
| Samsung SSD 980 PRO 1TB                             | 2        | 0.81%   |
| Samsung SSD 870 QVO 1TB                             | 2        | 0.81%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 2        | 0.81%   |
| Samsung NVMe SSD Drive 500GB                        | 2        | 0.81%   |
| Kingston SA400S37480G 480GB SSD                     | 2        | 0.81%   |
| XrayDisk 480GB                                      | 1        | 0.41%   |
| XrayDisk 1TB                                        | 1        | 0.41%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1        | 0.41%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1        | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 0.41%   |
| WDC WD60EZAZ-00ZGHB0 6TB                            | 1        | 0.41%   |
| WDC WD60EFAX-68SHWN0 6TB                            | 1        | 0.41%   |
| WDC WD5000LPSX-08A6W 500GB                          | 1        | 0.41%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 1        | 0.41%   |
| WDC WD5000AZLX-08K2TA0 500GB                        | 1        | 0.41%   |
| WDC WD5000AVVS-63M8B0 500GB                         | 1        | 0.41%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1        | 0.41%   |
| WDC WD5000AAKX-22ERMA0 500GB                        | 1        | 0.41%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1        | 0.41%   |
| WDC WD5000AAJS-00TKA0 500GB                         | 1        | 0.41%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 40       | 66     | 39.22%  |
| Seagate             | 34       | 46     | 33.33%  |
| Toshiba             | 12       | 14     | 11.76%  |
| Samsung Electronics | 7        | 10     | 6.86%   |
| Hitachi             | 5        | 6      | 4.9%    |
| Unknown             | 1        | 1      | 0.98%   |
| Intenso             | 1        | 1      | 0.98%   |
| ASMedia             | 1        | 1      | 0.98%   |
| Apple               | 1        | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 28     | 21.43%  |
| Kingston            | 14       | 22     | 16.67%  |
| Crucial             | 10       | 12     | 11.9%   |
| SanDisk             | 5        | 5      | 5.95%   |
| China               | 4        | 4      | 4.76%   |
| WDC                 | 3        | 3      | 3.57%   |
| SPCC                | 3        | 3      | 3.57%   |
| SK hynix            | 2        | 2      | 2.38%   |
| PNY                 | 2        | 2      | 2.38%   |
| Patriot             | 2        | 2      | 2.38%   |
| A-DATA Technology   | 2        | 2      | 2.38%   |
| Transcend           | 1        | 2      | 1.19%   |
| Toshiba             | 1        | 1      | 1.19%   |
| Team                | 1        | 1      | 1.19%   |
| TakeMS              | 1        | 1      | 1.19%   |
| T-FORCE             | 1        | 1      | 1.19%   |
| Phison              | 1        | 3      | 1.19%   |
| OCZ-VERTEX          | 1        | 1      | 1.19%   |
| OCZ                 | 1        | 1      | 1.19%   |
| NGFF                | 1        | 1      | 1.19%   |
| Netac               | 1        | 1      | 1.19%   |
| Micron Technology   | 1        | 1      | 1.19%   |
| LITEONIT            | 1        | 1      | 1.19%   |
| Hewlett-Packard     | 1        | 1      | 1.19%   |
| GOODRAM             | 1        | 1      | 1.19%   |
| Gigabyte Technology | 1        | 2      | 1.19%   |
| Apple               | 1        | 1      | 1.19%   |
| Apacer              | 1        | 1      | 1.19%   |
| 2.5''               | 1        | 1      | 1.19%   |
| Unknown             | 1        | 2      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 81       | 146    | 44.02%  |
| SSD     | 70       | 109    | 38.04%  |
| NVMe    | 28       | 41     | 15.22%  |
| Unknown | 5        | 6      | 2.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 114      | 249    | 75.5%   |
| NVMe | 28       | 41     | 18.54%  |
| SAS  | 9        | 12     | 5.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 86       | 145    | 55.13%  |
| 0.51-1.0   | 42       | 70     | 26.92%  |
| 1.01-2.0   | 13       | 15     | 8.33%   |
| 3.01-4.0   | 5        | 8      | 3.21%   |
| 2.01-3.0   | 5        | 10     | 3.21%   |
| 4.01-10.0  | 5        | 7      | 3.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 34       | 27.87%  |
| 251-500        | 27       | 22.13%  |
| 1001-2000      | 18       | 14.75%  |
| 501-1000       | 18       | 14.75%  |
| More than 3000 | 9        | 7.38%   |
| 2001-3000      | 6        | 4.92%   |
| 1-20           | 6        | 4.92%   |
| 51-100         | 3        | 2.46%   |
| 21-50          | 1        | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 40       | 32%     |
| 21-50          | 21       | 16.8%   |
| 101-250        | 16       | 12.8%   |
| 251-500        | 14       | 11.2%   |
| 51-100         | 13       | 10.4%   |
| 501-1000       | 9        | 7.2%    |
| 1001-2000      | 7        | 5.6%    |
| 2001-3000      | 3        | 2.4%    |
| More than 3000 | 2        | 1.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD10EZEX-60WN4A0 1TB        | 1        | 1      | 10%     |
| WDC WD1002FAEX-00Y9A0 1TB       | 1        | 1      | 10%     |
| Toshiba MQ04ABF100 1TB          | 1        | 1      | 10%     |
| Toshiba HDWD110 1TB             | 1        | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 10%     |
| Seagate ST3250318AS 250GB       | 1        | 1      | 10%     |
| Seagate ST2000DX001-1CM164 2TB  | 1        | 1      | 10%     |
| Seagate ST1000LM048-2E7172 1TB  | 1        | 1      | 10%     |
| Samsung Electronics HD153WI 1TB | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 50%     |
| WDC                 | 2        | 2      | 20%     |
| Toshiba             | 2        | 2      | 20%     |
| Samsung Electronics | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 50%     |
| WDC                 | 2        | 2      | 20%     |
| Toshiba             | 2        | 2      | 20%     |
| Samsung Electronics | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 10     | 100%    |

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
| Detected | 84       | 191    | 63.64%  |
| Works    | 39       | 101    | 29.55%  |
| Malfunc  | 9        | 10     | 6.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 78       | 47.85%  |
| AMD                         | 39       | 23.93%  |
| Samsung Electronics         | 11       | 6.75%   |
| JMicron Technology          | 4        | 2.45%   |
| ASMedia Technology          | 4        | 2.45%   |
| Silicon Motion              | 3        | 1.84%   |
| SanDisk                     | 3        | 1.84%   |
| Phison Electronics          | 3        | 1.84%   |
| Kingston Technology Company | 3        | 1.84%   |
| Broadcom / LSI              | 3        | 1.84%   |
| VIA Technologies            | 2        | 1.23%   |
| Nvidia                      | 2        | 1.23%   |
| Micron/Crucial Technology   | 2        | 1.23%   |
| Marvell Technology Group    | 2        | 1.23%   |
| ADATA Technology            | 2        | 1.23%   |
| SK hynix                    | 1        | 0.61%   |
| LSI Logic / Symbios Logic   | 1        | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 11.27%  |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 6.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 4.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 4.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 2.82%   |
| AMD FCH SATA Controller D                                                               | 5        | 2.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.88%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 1.41%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.41%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 1.41%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.41%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.94%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.94%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.94%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.94%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.94%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.94%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 0.94%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 0.94%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.47%   |
| VIA Serial ATA Controller                                                               | 1        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 104      | 60.47%  |
| NVMe | 28       | 16.28%  |
| IDE  | 28       | 16.28%  |
| RAID | 8        | 4.65%   |
| SAS  | 3        | 1.74%   |
| SCSI | 1        | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 79       | 65.83%  |
| AMD    | 41       | 34.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 4.96%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 3.31%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 3.31%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 2.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.48%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 2.48%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 1.65%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.65%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 1.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.65%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 1.65%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.65%   |
| Intel Celeron N5095 @ 2.00GHz               | 2        | 1.65%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 1.65%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.65%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2        | 1.65%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.65%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.65%   |
| AMD FX-4300 Quad-Core Processor             | 2        | 1.65%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.83%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 0.83%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.83%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 0.83%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.83%   |
| Intel Xeon CPU 3.40GHz                      | 1        | 0.83%   |
| Intel Pentium Gold G7400                    | 1        | 0.83%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.83%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.83%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.83%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.83%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.83%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.83%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1        | 0.83%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.83%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.83%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.83%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 0.83%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 18       | 14.88%  |
| Intel Core i5           | 18       | 14.88%  |
| AMD Ryzen 5             | 12       | 9.92%   |
| AMD Ryzen 7             | 10       | 8.26%   |
| Intel Xeon              | 9        | 7.44%   |
| Intel Core i3           | 6        | 4.96%   |
| Other                   | 5        | 4.13%   |
| Intel Celeron           | 5        | 4.13%   |
| Intel Pentium           | 4        | 3.31%   |
| Intel Core 2 Duo        | 4        | 3.31%   |
| AMD Ryzen 3             | 4        | 3.31%   |
| Intel Core 2 Quad       | 3        | 2.48%   |
| AMD FX                  | 3        | 2.48%   |
| Intel Pentium Gold      | 2        | 1.65%   |
| Intel Pentium Dual-Core | 2        | 1.65%   |
| Intel Pentium D         | 2        | 1.65%   |
| AMD Athlon II X2        | 2        | 1.65%   |
| AMD Athlon              | 2        | 1.65%   |
| AMD A4                  | 2        | 1.65%   |
| Intel Pentium Dual      | 1        | 0.83%   |
| Intel Core 2            | 1        | 0.83%   |
| AMD Ryzen 9             | 1        | 0.83%   |
| AMD Phenom II X6        | 1        | 0.83%   |
| AMD Phenom II X4        | 1        | 0.83%   |
| AMD G                   | 1        | 0.83%   |
| AMD E1                  | 1        | 0.83%   |
| AMD A8                  | 1        | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 51       | 42.15%  |
| 2      | 33       | 27.27%  |
| 8      | 17       | 14.05%  |
| 6      | 12       | 9.92%   |
| 16     | 5        | 4.13%   |
| 1      | 2        | 1.65%   |
| 10     | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 114      | 95%     |
| 2      | 6        | 5%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 68       | 56.2%   |
| 1      | 53       | 43.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 120      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 12       | 9.84%   |
| 0x306c3    | 9        | 7.38%   |
| 0x206a7    | 8        | 6.56%   |
| 0x0800820d | 6        | 4.92%   |
| 0x506e3    | 5        | 4.1%    |
| 0x1067a    | 5        | 4.1%    |
| 0x08108109 | 5        | 4.1%    |
| 0x08701021 | 4        | 3.28%   |
| Unknown    | 4        | 3.28%   |
| 0xa0671    | 3        | 2.46%   |
| 0x906ed    | 3        | 2.46%   |
| 0x6fd      | 3        | 2.46%   |
| 0x0a50000d | 3        | 2.46%   |
| 0x906ea    | 2        | 1.64%   |
| 0x906e9    | 2        | 1.64%   |
| 0x906c0    | 2        | 1.64%   |
| 0x90675    | 2        | 1.64%   |
| 0x706a8    | 2        | 1.64%   |
| 0x206d7    | 2        | 1.64%   |
| 0x20655    | 2        | 1.64%   |
| 0x106e5    | 2        | 1.64%   |
| 0x08101016 | 2        | 1.64%   |
| 0x0810100b | 2        | 1.64%   |
| 0x08001138 | 2        | 1.64%   |
| 0x06001119 | 2        | 1.64%   |
| 0x06000852 | 2        | 1.64%   |
| 0x010000c8 | 2        | 1.64%   |
| 0xf65      | 1        | 0.82%   |
| 0xf47      | 1        | 0.82%   |
| 0xf43      | 1        | 0.82%   |
| 0xa0655    | 1        | 0.82%   |
| 0xa0653    | 1        | 0.82%   |
| 0x806ea    | 1        | 0.82%   |
| 0x806c2    | 1        | 0.82%   |
| 0x6fb      | 1        | 0.82%   |
| 0x6f2      | 1        | 0.82%   |
| 0x306f2    | 1        | 0.82%   |
| 0x306e4    | 1        | 0.82%   |
| 0x206d6    | 1        | 0.82%   |
| 0x206c2    | 1        | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 14       | 11.57%  |
| Zen+          | 11       | 9.09%   |
| SandyBridge   | 11       | 9.09%   |
| Haswell       | 10       | 8.26%   |
| Zen           | 8        | 6.61%   |
| KabyLake      | 8        | 6.61%   |
| Zen 3         | 6        | 4.96%   |
| Penryn        | 6        | 4.96%   |
| Skylake       | 5        | 4.13%   |
| Piledriver    | 5        | 4.13%   |
| Core          | 5        | 4.13%   |
| Unknown       | 5        | 4.13%   |
| Zen 2         | 4        | 3.31%   |
| K10           | 4        | 3.31%   |
| Westmere      | 3        | 2.48%   |
| NetBurst      | 3        | 2.48%   |
| Nehalem       | 3        | 2.48%   |
| Tremont       | 2        | 1.65%   |
| Goldmont plus | 2        | 1.65%   |
| CometLake     | 2        | 1.65%   |
| TigerLake     | 1        | 0.83%   |
| Jaguar        | 1        | 0.83%   |
| Bulldozer     | 1        | 0.83%   |
| Bobcat        | 1        | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 65       | 49.24%  |
| Intel  | 35       | 26.52%  |
| AMD    | 32       | 24.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 4.44%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 4.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 3.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 3.7%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 2.96%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 2.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.96%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 2.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.22%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.48%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 1.48%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.48%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.48%   |
| Intel HD Graphics 530                                                       | 2        | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.48%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 2        | 1.48%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.74%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.74%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.74%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.74%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.74%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.74%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.74%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.74%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.74%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 58       | 47.54%  |
| 1 x Intel      | 29       | 23.77%  |
| 1 x AMD        | 25       | 20.49%  |
| 2 x AMD        | 3        | 2.46%   |
| Intel + Nvidia | 3        | 2.46%   |
| AMD + Nvidia   | 3        | 2.46%   |
| Intel + AMD    | 1        | 0.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 81       | 66.94%  |
| Proprietary | 28       | 23.14%  |
| Unknown     | 12       | 9.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 32.79%  |
| 1.01-2.0   | 27       | 22.13%  |
| 0.01-0.5   | 16       | 13.11%  |
| 0.51-1.0   | 12       | 9.84%   |
| 3.01-4.0   | 11       | 9.02%   |
| 7.01-8.0   | 7        | 5.74%   |
| 5.01-6.0   | 5        | 4.1%    |
| 8.01-16.0  | 2        | 1.64%   |
| 2.01-3.0   | 1        | 0.82%   |
| 16.01-24.0 | 1        | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 22       | 19.82%  |
| Goldstar             | 12       | 10.81%  |
| Acer                 | 9        | 8.11%   |
| Dell                 | 8        | 7.21%   |
| Hewlett-Packard      | 7        | 6.31%   |
| BenQ                 | 7        | 6.31%   |
| Philips              | 6        | 5.41%   |
| Unknown              | 5        | 4.5%    |
| Sony                 | 4        | 3.6%    |
| Ancor Communications | 4        | 3.6%    |
| AOC                  | 3        | 2.7%    |
| ViewSonic            | 2        | 1.8%    |
| Iiyama               | 2        | 1.8%    |
| ___                  | 1        | 0.9%    |
| Unknown (XXX)        | 1        | 0.9%    |
| SKY                  | 1        | 0.9%    |
| PLN                  | 1        | 0.9%    |
| Pioneer              | 1        | 0.9%    |
| Nixeus               | 1        | 0.9%    |
| NEC Computers        | 1        | 0.9%    |
| MSI                  | 1        | 0.9%    |
| Medion               | 1        | 0.9%    |
| Lenovo Group Limited | 1        | 0.9%    |
| Lenovo               | 1        | 0.9%    |
| Insignia             | 1        | 0.9%    |
| Idek Iiyama          | 1        | 0.9%    |
| HUAWEI               | 1        | 0.9%    |
| HPN                  | 1        | 0.9%    |
| HannStar             | 1        | 0.9%    |
| DENON                | 1        | 0.9%    |
| AUS                  | 1        | 0.9%    |
| ASUSTek Computer     | 1        | 0.9%    |
| Unknown              | 1        | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3        | 2.52%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 2        | 1.68%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2        | 1.68%   |
| ___ LCDTV16 ___0101 1920x1080                                        | 1        | 0.84%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch           | 1        | 0.84%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch             | 1        | 0.84%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                   | 1        | 0.84%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 1        | 0.84%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                 | 1        | 0.84%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.84%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                        | 1        | 0.84%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 0.84%   |
| Sony TV SNY8E01 1360x768                                             | 1        | 0.84%   |
| Sony TV SNY8701 1440x900                                             | 1        | 0.84%   |
| Sony LCD Monitor TV 3840x1080                                        | 1        | 0.84%   |
| Sony LCD Monitor TV  *00 1920x1080                                   | 1        | 0.84%   |
| SKY TV SKY1502 3840x2160 708x398mm 32.0-inch                         | 1        | 0.84%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                        | 1        | 0.84%   |
| SKY Toshiba TV SKY1402 3840x2160 708x398mm 32.0-inch                 | 1        | 0.84%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 520x290mm 23.4-inch | 1        | 0.84%   |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch  | 1        | 0.84%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch | 1        | 0.84%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 1        | 0.84%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.84%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 530x300mm 24.0-inch  | 1        | 0.84%   |
| Samsung Electronics SMFX2490HD SAM074A 1920x1080 530x300mm 24.0-inch | 1        | 0.84%   |
| Samsung Electronics SME1920N SAM06A3 1360x768 410x230mm 18.5-inch    | 1        | 0.84%   |
| Samsung Electronics SMBX1950N SAM0716 1366x768 410x230mm 18.5-inch   | 1        | 0.84%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 0.84%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1        | 0.84%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 0.84%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch    | 1        | 0.84%   |
| Samsung Electronics S24B370 SAM08DD 1920x1080 531x299mm 24.0-inch    | 1        | 0.84%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 0.84%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 0.84%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch     | 1        | 0.84%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch    | 1        | 0.84%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 1        | 0.84%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 0.84%   |
| Samsung Electronics LCD Monitor S27R65 3840x1080                     | 1        | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 48       | 44.86%  |
| 1680x1050 (WSXGA+) | 8        | 7.48%   |
| 3840x2160 (4K)     | 7        | 6.54%   |
| 1600x900 (HD+)     | 5        | 4.67%   |
| 1366x768 (WXGA)    | 5        | 4.67%   |
| 1280x1024 (SXGA)   | 5        | 4.67%   |
| 3440x1440          | 4        | 3.74%   |
| 2560x1440 (QHD)    | 4        | 3.74%   |
| 2560x1080          | 3        | 2.8%    |
| 1920x1200 (WUXGA)  | 3        | 2.8%    |
| 1440x900 (WXGA+)   | 3        | 2.8%    |
| 1360x768           | 3        | 2.8%    |
| Unknown            | 3        | 2.8%    |
| 3840x1080          | 2        | 1.87%   |
| 4480x1440          | 1        | 0.93%   |
| 1600x1200          | 1        | 0.93%   |
| 1280x768           | 1        | 0.93%   |
| 1024x768 (XGA)     | 1        | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 20.72%  |
| 24      | 15       | 13.51%  |
| 21      | 13       | 11.71%  |
| 23      | 9        | 8.11%   |
| 27      | 8        | 7.21%   |
| 20      | 6        | 5.41%   |
| 34      | 5        | 4.5%    |
| 22      | 5        | 4.5%    |
| 18      | 5        | 4.5%    |
| 72      | 4        | 3.6%    |
| 19      | 4        | 3.6%    |
| 31      | 3        | 2.7%    |
| 32      | 2        | 1.8%    |
| 15      | 2        | 1.8%    |
| 64      | 1        | 0.9%    |
| 54      | 1        | 0.9%    |
| 52      | 1        | 0.9%    |
| 40      | 1        | 0.9%    |
| 28      | 1        | 0.9%    |
| 25      | 1        | 0.9%    |
| 17      | 1        | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 31       | 29.52%  |
| 401-500     | 27       | 25.71%  |
| Unknown     | 23       | 21.9%   |
| 701-800     | 7        | 6.67%   |
| 601-700     | 5        | 4.76%   |
| 1501-2000   | 4        | 3.81%   |
| 301-350     | 3        | 2.86%   |
| 351-400     | 2        | 1.9%    |
| 1001-1500   | 2        | 1.9%    |
| 801-900     | 1        | 0.95%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 54       | 53.47%  |
| Unknown | 22       | 21.78%  |
| 16/10   | 12       | 11.88%  |
| 21/9    | 6        | 5.94%   |
| 4/3     | 4        | 3.96%   |
| 5/4     | 3        | 2.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 35       | 32.41%  |
| Unknown        | 23       | 21.3%   |
| 351-500        | 10       | 9.26%   |
| 151-200        | 10       | 9.26%   |
| 301-350        | 8        | 7.41%   |
| 251-300        | 7        | 6.48%   |
| More than 1000 | 6        | 5.56%   |
| 141-150        | 6        | 5.56%   |
| 111-120        | 1        | 0.93%   |
| 101-110        | 1        | 0.93%   |
| 501-1000       | 1        | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 60       | 57.14%  |
| Unknown | 23       | 21.9%   |
| 101-120 | 16       | 15.24%  |
| 1-50    | 5        | 4.76%   |
| 121-160 | 1        | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 93       | 76.23%  |
| 2     | 17       | 13.93%  |
| 0     | 10       | 8.2%    |
| 3     | 2        | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 73       | 42.94%  |
| Intel                    | 54       | 31.76%  |
| Qualcomm Atheros         | 9        | 5.29%   |
| TP-Link                  | 5        | 2.94%   |
| Ralink Technology        | 4        | 2.35%   |
| Broadcom                 | 3        | 1.76%   |
| Samsung Electronics      | 2        | 1.18%   |
| Ralink                   | 2        | 1.18%   |
| Nvidia                   | 2        | 1.18%   |
| NetGear                  | 2        | 1.18%   |
| MediaTek                 | 2        | 1.18%   |
| Marvell Technology Group | 2        | 1.18%   |
| Huawei Technologies      | 2        | 1.18%   |
| VIA Technologies         | 1        | 0.59%   |
| Qualcomm                 | 1        | 0.59%   |
| Microsoft                | 1        | 0.59%   |
| Mercucys                 | 1        | 0.59%   |
| IMC Networks             | 1        | 0.59%   |
| HTC (High Tech Computer) | 1        | 0.59%   |
| Belkin Components        | 1        | 0.59%   |
| ASUSTek Computer         | 1        | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58       | 29.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 5.05%   |
| Intel I211 Gigabit Network Connection                             | 7        | 3.54%   |
| Intel Wireless 3165                                               | 5        | 2.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4        | 2.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 2.02%   |
| Intel Ethernet Connection I217-V                                  | 4        | 2.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3        | 1.52%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.01%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.01%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 1.01%   |
| Realtek 802.11ac NIC                                              | 2        | 1.01%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 1.01%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 1.01%   |
| Intel Wireless-AC 9260                                            | 2        | 1.01%   |
| Intel Wireless 8260                                               | 2        | 1.01%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.01%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.01%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.01%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 1.01%   |
| Huawei ANE-LX1                                                    | 2        | 1.01%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.51%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.51%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                             | 1        | 0.51%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.51%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.51%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 20       | 31.75%  |
| Intel                    | 17       | 26.98%  |
| TP-Link                  | 5        | 7.94%   |
| Ralink Technology        | 4        | 6.35%   |
| Qualcomm Atheros         | 4        | 6.35%   |
| Ralink                   | 2        | 3.17%   |
| NetGear                  | 2        | 3.17%   |
| MediaTek                 | 2        | 3.17%   |
| Microsoft                | 1        | 1.59%   |
| Mercucys                 | 1        | 1.59%   |
| Marvell Technology Group | 1        | 1.59%   |
| IMC Networks             | 1        | 1.59%   |
| Broadcom                 | 1        | 1.59%   |
| Belkin Components        | 1        | 1.59%   |
| ASUSTek Computer         | 1        | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                                                           | 5        | 7.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 4        | 6.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 6.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 3        | 4.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 4.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 3.03%   |
| Realtek RTL8187 Wireless Adapter                                                              | 2        | 3.03%   |
| Realtek 802.11ac NIC                                                                          | 2        | 3.03%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 2        | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 3.03%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 2        | 3.03%   |
| Intel Wireless-AC 9260                                                                        | 2        | 3.03%   |
| Intel Wireless 8260                                                                           | 2        | 3.03%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 3.03%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 1        | 1.52%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 1.52%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.52%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.52%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.52%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.52%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.52%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 1.52%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 1        | 1.52%   |
| NetGear A6210                                                                                 | 1        | 1.52%   |
| NetGear A6150                                                                                 | 1        | 1.52%   |
| Microsoft XBOX ACC                                                                            | 1        | 1.52%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 1.52%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                                           | 1        | 1.52%   |
| Intel Wireless 7265                                                                           | 1        | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1        | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.52%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                          | 1        | 1.52%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 66       | 51.97%  |
| Intel                    | 44       | 34.65%  |
| Qualcomm Atheros         | 5        | 3.94%   |
| Samsung Electronics      | 2        | 1.57%   |
| Nvidia                   | 2        | 1.57%   |
| Huawei Technologies      | 2        | 1.57%   |
| Broadcom                 | 2        | 1.57%   |
| VIA Technologies         | 1        | 0.79%   |
| Qualcomm                 | 1        | 0.79%   |
| Marvell Technology Group | 1        | 0.79%   |
| HTC (High Tech Computer) | 1        | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58       | 43.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 7.58%   |
| Intel I211 Gigabit Network Connection                             | 7        | 5.3%    |
| Intel Ethernet Connection I217-V                                  | 4        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.27%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.27%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.52%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.52%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.52%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.52%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.52%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 1.52%   |
| Huawei ANE-LX1                                                    | 2        | 1.52%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.76%   |
| Qualcomm MDM9207-MTP _SN:E06E7622                                 | 1        | 0.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.76%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.76%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.76%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.76%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.76%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.76%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.76%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.76%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.76%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.76%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.76%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.76%   |
| Intel 82545GM Gigabit Ethernet Controller                         | 1        | 0.76%   |
| HTC (High Tech Computer) Desire HD (modem mode)                   | 1        | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 119      | 67.61%  |
| WiFi     | 57       | 32.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 75.2%   |
| WiFi     | 31       | 24.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 66.67%  |
| 2     | 37       | 30.83%  |
| 3     | 2        | 1.67%   |
| 0     | 1        | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 86       | 70.49%  |
| Yes  | 36       | 29.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 17       | 47.22%  |
| Cambridge Silicon Radio | 8        | 22.22%  |
| Realtek Semiconductor   | 2        | 5.56%   |
| MediaTek                | 2        | 5.56%   |
| Lite-On Technology      | 2        | 5.56%   |
| Broadcom                | 2        | 5.56%   |
| ISSC                    | 1        | 2.78%   |
| Dynex                   | 1        | 2.78%   |
| Dell                    | 1        | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                       | 8        | 22.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 8        | 22.22%  |
| MediaTek Wireless_Device                                 | 2        | 5.56%   |
| Lite-On Bluetooth Device                                 | 2        | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 2        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2        | 5.56%   |
| Intel AX200 Bluetooth                                    | 2        | 5.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1        | 2.78%   |
| Realtek Bluetooth Radio                                  | 1        | 2.78%   |
| ISSC Bluetooth Device                                    | 1        | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 2.78%   |
| Intel AX210 Bluetooth                                    | 1        | 2.78%   |
| Intel AX201 Bluetooth                                    | 1        | 2.78%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 2.78%   |
| Dell BT Mini-Receiver                                    | 1        | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 74       | 37%     |
| Nvidia                               | 59       | 29.5%   |
| AMD                                  | 45       | 22.5%   |
| C-Media Electronics                  | 6        | 3%      |
| VIA Technologies                     | 2        | 1%      |
| Thesycon Systemsoftware & Consulting | 2        | 1%      |
| KTMicro                              | 2        | 1%      |
| JMTek                                | 2        | 1%      |
| Turtle Beach                         | 1        | 0.5%    |
| Sony                                 | 1        | 0.5%    |
| Native Instruments                   | 1        | 0.5%    |
| Micro Star International             | 1        | 0.5%    |
| Logitech                             | 1        | 0.5%    |
| GN Netcom                            | 1        | 0.5%    |
| Generalplus Technology               | 1        | 0.5%    |
| DCMT Technology                      | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                      | 13       | 5.63%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 5.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 4.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 4.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 3.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 3.46%   |
| Nvidia High Definition Audio Controller                                    | 6        | 2.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 2.6%    |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.16%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.73%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 1.73%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.73%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.73%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.73%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.3%    |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.3%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 2        | 0.87%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                              | 2        | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.87%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.87%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.87%   |
| KTMicro KT USB Audio                                                       | 2        | 0.87%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 0.87%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 9        | 16.98%  |
| Samsung Electronics | 9        | 16.98%  |
| Corsair             | 7        | 13.21%  |
| Kingston            | 5        | 9.43%   |
| Micron Technology   | 4        | 7.55%   |
| SK hynix            | 3        | 5.66%   |
| G.Skill             | 3        | 5.66%   |
| Crucial             | 3        | 5.66%   |
| Team                | 2        | 3.77%   |
| Unknown (ABCD)      | 1        | 1.89%   |
| Smart               | 1        | 1.89%   |
| Nanya Technology    | 1        | 1.89%   |
| KLEVV               | 1        | 1.89%   |
| GeIL                | 1        | 1.89%   |
| Elpida              | 1        | 1.89%   |
| AVEXIR              | 1        | 1.89%   |
| A-DATA Technology   | 1        | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 2        | 3.45%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 1.72%   |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                     | 1        | 1.72%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 1.72%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 1.72%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 1.72%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 1.72%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.72%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                       | 1        | 1.72%   |
| Unknown RAM Module 1GB DIMM DDR2 266MT/s                       | 1        | 1.72%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 1        | 1.72%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s        | 1        | 1.72%   |
| Unknown RAM D4 8G 8GB DIMM DDR4 2666MT/s                       | 1        | 1.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.72%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s             | 1        | 1.72%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s             | 1        | 1.72%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s          | 1        | 1.72%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1.72%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s           | 1        | 1.72%   |
| SK hynix RAM HKNNNFBMAVAR-NEH 2GB Row Of Chips LPDDR4 3200MT/s | 1        | 1.72%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                      | 1        | 1.72%   |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s                      | 1        | 1.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.72%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s          | 1        | 1.72%   |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s            | 1        | 1.72%   |
| Samsung RAM M393B2G70DB0-CMA 16GB DIMM DDR3 1867MT/s           | 1        | 1.72%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s            | 1        | 1.72%   |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s            | 1        | 1.72%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 1333MT/s                | 1        | 1.72%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s           | 1        | 1.72%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s              | 1        | 1.72%   |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s           | 1        | 1.72%   |
| Micron RAM 18KSF1G72PZ-1G4E1 8GB DIMM DDR3 1333MT/s            | 1        | 1.72%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s            | 1        | 1.72%   |
| Micron RAM 16JTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s        | 1        | 1.72%   |
| KLEVV RAM KD48GU880-36A180C 8GB DIMM DDR4 3600MT/s             | 1        | 1.72%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 1        | 1.72%   |
| Kingston RAM HP497157-D88 2GB DIMM DDR3 1333MT/s               | 1        | 1.72%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 1        | 1.72%   |
| Kingston RAM 99U5403-034.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 19       | 42.22%  |
| DDR3    | 16       | 35.56%  |
| DDR2    | 4        | 8.89%   |
| SDRAM   | 2        | 4.44%   |
| LPDDR4  | 2        | 4.44%   |
| Unknown | 2        | 4.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 40       | 90.91%  |
| SODIMM       | 3        | 6.82%   |
| Row Of Chips | 1        | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 31.37%  |
| 4096  | 13       | 25.49%  |
| 16384 | 9        | 17.65%  |
| 2048  | 7        | 13.73%  |
| 1024  | 3        | 5.88%   |
| 32768 | 2        | 3.92%   |
| 512   | 1        | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 11       | 22.45%  |
| 1333  | 6        | 12.24%  |
| 3600  | 5        | 10.2%   |
| 2667  | 4        | 8.16%   |
| 2400  | 4        | 8.16%   |
| 3200  | 3        | 6.12%   |
| 2133  | 3        | 6.12%   |
| 1866  | 2        | 4.08%   |
| 667   | 2        | 4.08%   |
| 3733  | 1        | 2.04%   |
| 3533  | 1        | 2.04%   |
| 1867  | 1        | 2.04%   |
| 1800  | 1        | 2.04%   |
| 1334  | 1        | 2.04%   |
| 1066  | 1        | 2.04%   |
| 800   | 1        | 2.04%   |
| 533   | 1        | 2.04%   |
| 266   | 1        | 2.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 40%     |
| Seiko Epson        | 1        | 20%     |
| Konica Minolta     | 1        | 20%     |
| Brother Industries | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson ET-2820 Series | 1        | 20%     |
| Konica Minolta 185         | 1        | 20%     |
| HP OfficeJet Pro 8730      | 1        | 20%     |
| HP DeskJet 2130 series     | 1        | 20%     |
| Brother MFC-L2685DW        | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 33.33%  |
| Sunplus Innovation Technology | 3        | 14.29%  |
| Huawei Technologies           | 2        | 9.52%   |
| Creative Technology           | 2        | 9.52%   |
| Z-Star Microelectronics       | 1        | 4.76%   |
| Samsung Electronics           | 1        | 4.76%   |
| Pixart Imaging                | 1        | 4.76%   |
| OmniVision Technologies       | 1        | 4.76%   |
| MacroSilicon                  | 1        | 4.76%   |
| ARC International             | 1        | 4.76%   |
| Alcor Micro                   | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Sunplus FHD Camera Microphone                  | 2        | 9.52%   |
| Logitech Webcam C270                           | 2        | 9.52%   |
| Huawei UVC Camera                              | 2        | 9.52%   |
| Z-Star Venus USB2.0 Camera                     | 1        | 4.76%   |
| Sunplus Webcam                                 | 1        | 4.76%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 4.76%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1        | 4.76%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 4.76%   |
| MacroSilicon usb video                         | 1        | 4.76%   |
| Logitech Webcam C925e                          | 1        | 4.76%   |
| Logitech Webcam C210                           | 1        | 4.76%   |
| Logitech Webcam B500                           | 1        | 4.76%   |
| Logitech QuickCam Communicate Deluxe/S7500     | 1        | 4.76%   |
| Logitech Logi Webcam C920e                     | 1        | 4.76%   |
| Creative VF0610 Live! Cam Socialize HD         | 1        | 4.76%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 4.76%   |
| ARC International Camera                       | 1        | 4.76%   |
| Alcor Micro USB 5.0M AF Camera                 | 1        | 4.76%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 87       | 71.31%  |
| 1     | 33       | 27.05%  |
| 2     | 2        | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 17       | 43.59%  |
| Net/wireless             | 14       | 35.9%   |
| Multimedia controller    | 3        | 7.69%   |
| Communication controller | 2        | 5.13%   |
| Unassigned class         | 1        | 2.56%   |
| Storage/raid             | 1        | 2.56%   |
| Camera                   | 1        | 2.56%   |


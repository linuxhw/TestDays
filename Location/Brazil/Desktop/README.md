Linux in Brazil - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 6673

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A97 EVO R2.0              | [3f218796ae](https://linux-hardware.org/?probe=3f218796ae) | Apr 01, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [ee536703f8](https://linux-hardware.org/?probe=ee536703f8) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| Intel         | H61 V1.1                    | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | A58M-A/BR                   | [90724dc86e](https://linux-hardware.org/?probe=90724dc86e) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [1fa3e0934f](https://linux-hardware.org/?probe=1fa3e0934f) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [ebd6135034](https://linux-hardware.org/?probe=ebd6135034) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [88864f0e2d](https://linux-hardware.org/?probe=88864f0e2d) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3aac57dfbd](https://linux-hardware.org/?probe=3aac57dfbd) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Dell          | 0KWVT8 A02                  | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| Daten Tecn... | DQ77PRO                     | [86885bfc03](https://linux-hardware.org/?probe=86885bfc03) | Mar 29, 2023 |
| Intel         | B75                         | [2bddb84c2e](https://linux-hardware.org/?probe=2bddb84c2e) | Mar 29, 2023 |
| HOUTER        | IPMH61R1                    | [bcabc2573c](https://linux-hardware.org/?probe=bcabc2573c) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| Intel         | H61 V1.1                    | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [7ec74ffcfa](https://linux-hardware.org/?probe=7ec74ffcfa) | Mar 28, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [7e5cb33850](https://linux-hardware.org/?probe=7e5cb33850) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9c9e155f84](https://linux-hardware.org/?probe=9c9e155f84) | Mar 28, 2023 |
| Intel         | H61                         | [56437a0e05](https://linux-hardware.org/?probe=56437a0e05) | Mar 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [6b4122e888](https://linux-hardware.org/?probe=6b4122e888) | Mar 28, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [727f980b20](https://linux-hardware.org/?probe=727f980b20) | Mar 27, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | [ec1f547743](https://linux-hardware.org/?probe=ec1f547743) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| PCWare        | IPMH61R3                    | [2fbd1f3f64](https://linux-hardware.org/?probe=2fbd1f3f64) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| MSI           | A520M-A PRO                 | [f2a2593a06](https://linux-hardware.org/?probe=f2a2593a06) | Mar 24, 2023 |
| Gigabyte      | H170-D3H-CF                 | [0bcd7ee5e8](https://linux-hardware.org/?probe=0bcd7ee5e8) | Mar 24, 2023 |
| Intel         | X99 V1.x                    | [391a73b307](https://linux-hardware.org/?probe=391a73b307) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [4e2b8b9de9](https://linux-hardware.org/?probe=4e2b8b9de9) | Mar 24, 2023 |
| PCWare        | IPMH310G                    | [3cc2e91e56](https://linux-hardware.org/?probe=3cc2e91e56) | Mar 24, 2023 |
| Itautec       | ST 4265                     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2536217d87](https://linux-hardware.org/?probe=2536217d87) | Mar 23, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [cd3e7fa4e5](https://linux-hardware.org/?probe=cd3e7fa4e5) | Mar 23, 2023 |
| Intel         | DH87RL AAG74240-401         | [3465e562e8](https://linux-hardware.org/?probe=3465e562e8) | Mar 23, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [7d303a08d4](https://linux-hardware.org/?probe=7d303a08d4) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Digiboard     | NM70-TI                     | [d654b9738a](https://linux-hardware.org/?probe=d654b9738a) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [47b661fcb3](https://linux-hardware.org/?probe=47b661fcb3) | Mar 22, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [f848ecf9cf](https://linux-hardware.org/?probe=f848ecf9cf) | Mar 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [568fac441d](https://linux-hardware.org/?probe=568fac441d) | Mar 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2e6307252f](https://linux-hardware.org/?probe=2e6307252f) | Mar 22, 2023 |
| Gigabyte      | GA-970A-UD3                 | [982f47fec3](https://linux-hardware.org/?probe=982f47fec3) | Mar 22, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [1e299101d8](https://linux-hardware.org/?probe=1e299101d8) | Mar 22, 2023 |
| CCE           | NM70-I                      | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| Dell          | 03NVJ6 A01                  | [2060b57720](https://linux-hardware.org/?probe=2060b57720) | Mar 20, 2023 |
| Dell          | 0KWVT8 A00                  | [b15061e252](https://linux-hardware.org/?probe=b15061e252) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Win elemen... | M600                        | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [32d80303b6](https://linux-hardware.org/?probe=32d80303b6) | Mar 20, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [6e6c326058](https://linux-hardware.org/?probe=6e6c326058) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| MSI           | 970 GAMING                  | [99e92fa4df](https://linux-hardware.org/?probe=99e92fa4df) | Mar 18, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [1a93d601d7](https://linux-hardware.org/?probe=1a93d601d7) | Mar 18, 2023 |
| ASRock        | FM2A68M-DG3+                | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Intel         | H61                         | [10b44e8f3e](https://linux-hardware.org/?probe=10b44e8f3e) | Mar 18, 2023 |
| ASRock        | FM2A68M-DG3+                | [16b1b61892](https://linux-hardware.org/?probe=16b1b61892) | Mar 17, 2023 |
| Positivo      | POS-EIH61CE SIM             | [19a69ab150](https://linux-hardware.org/?probe=19a69ab150) | Mar 17, 2023 |
| HP            | 8266                        | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [452349c032](https://linux-hardware.org/?probe=452349c032) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [2215bc867b](https://linux-hardware.org/?probe=2215bc867b) | Mar 17, 2023 |
| Intel         | X99                         | [e7d23adc36](https://linux-hardware.org/?probe=e7d23adc36) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| HP            | 8266                        | [90ee08c208](https://linux-hardware.org/?probe=90ee08c208) | Mar 16, 2023 |
| Intel         | X99 V1.0                    | [1e1b3b6542](https://linux-hardware.org/?probe=1e1b3b6542) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| HP            | 8299                        | [d76d2b1088](https://linux-hardware.org/?probe=d76d2b1088) | Mar 15, 2023 |
| PCWare        | IPX4105G Pro                | [f685771047](https://linux-hardware.org/?probe=f685771047) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270-A                | [1451ae2f05](https://linux-hardware.org/?probe=1451ae2f05) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270-A                | [26971576bb](https://linux-hardware.org/?probe=26971576bb) | Mar 14, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [7649d9be35](https://linux-hardware.org/?probe=7649d9be35) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASRock        | A320M-HDV R4.0              | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| ASUSTek       | PRIME B350M-K               | [ae6352dc35](https://linux-hardware.org/?probe=ae6352dc35) | Mar 13, 2023 |
| Biostar       | A320MH                      | [6fbd813bc2](https://linux-hardware.org/?probe=6fbd813bc2) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [89e2967e3c](https://linux-hardware.org/?probe=89e2967e3c) | Mar 12, 2023 |
| Pegatron      | SM3330B 0500B               | [1ece615e2d](https://linux-hardware.org/?probe=1ece615e2d) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| Dell          | 0HHV7N A00                  | [75e9243247](https://linux-hardware.org/?probe=75e9243247) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3e9c39ec40](https://linux-hardware.org/?probe=3e9c39ec40) | Mar 11, 2023 |
| Intel         | H61                         | [0a38ec61cc](https://linux-hardware.org/?probe=0a38ec61cc) | Mar 11, 2023 |
| Gigabyte      | H81M-H                      | [fd3c999c22](https://linux-hardware.org/?probe=fd3c999c22) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| Intel         | X99H                        | [a89ad204c8](https://linux-hardware.org/?probe=a89ad204c8) | Mar 11, 2023 |
| Positivo      | POS-PIB150DT                | [0842fc186b](https://linux-hardware.org/?probe=0842fc186b) | Mar 10, 2023 |
| Lenovo        | NOK                         | [2e90ce2e87](https://linux-hardware.org/?probe=2e90ce2e87) | Mar 10, 2023 |
| Dell          | 0G2DM9 A02                  | [e6d8fa1563](https://linux-hardware.org/?probe=e6d8fa1563) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5a1af5afcf](https://linux-hardware.org/?probe=5a1af5afcf) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | [8b2c5b902c](https://linux-hardware.org/?probe=8b2c5b902c) | Mar 10, 2023 |
| Positivo      | POS-PIQ77CL                 | [789838055a](https://linux-hardware.org/?probe=789838055a) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | [3a0c1c2237](https://linux-hardware.org/?probe=3a0c1c2237) | Mar 10, 2023 |
| HP            | 1905                        | [dc86818199](https://linux-hardware.org/?probe=dc86818199) | Mar 09, 2023 |
| Dell          | 0TW904                      | [19f37f2901](https://linux-hardware.org/?probe=19f37f2901) | Mar 09, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [a05bd1ffa7](https://linux-hardware.org/?probe=a05bd1ffa7) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Gigabyte      | A320M-S2H-CF                | [daf758d941](https://linux-hardware.org/?probe=daf758d941) | Mar 08, 2023 |
| Intel         | B75 V124                    | [8a643c9a04](https://linux-hardware.org/?probe=8a643c9a04) | Mar 08, 2023 |
| Dell          | 0TW904                      | [20e3b7cc23](https://linux-hardware.org/?probe=20e3b7cc23) | Mar 08, 2023 |
| Intel         | B75 V124                    | [777cb32ba1](https://linux-hardware.org/?probe=777cb32ba1) | Mar 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [d7ac4c2edb](https://linux-hardware.org/?probe=d7ac4c2edb) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | [1ef5bb11d6](https://linux-hardware.org/?probe=1ef5bb11d6) | Mar 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | [0bad20c48c](https://linux-hardware.org/?probe=0bad20c48c) | Mar 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [4ca3d88758](https://linux-hardware.org/?probe=4ca3d88758) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [955e69578c](https://linux-hardware.org/?probe=955e69578c) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [22273fa42e](https://linux-hardware.org/?probe=22273fa42e) | Mar 06, 2023 |
| Lenovo        | ThinkCentre M91P 4518NR1    | [dfea3b8d9f](https://linux-hardware.org/?probe=dfea3b8d9f) | Mar 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [349f7731c8](https://linux-hardware.org/?probe=349f7731c8) | Mar 06, 2023 |
| Gigabyte      | B450 AORUS M                | [e67eb9d235](https://linux-hardware.org/?probe=e67eb9d235) | Mar 06, 2023 |
| MSI           | 970 GAMING                  | [ca2ad0edee](https://linux-hardware.org/?probe=ca2ad0edee) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [a21f4171f1](https://linux-hardware.org/?probe=a21f4171f1) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [7e9b335ee0](https://linux-hardware.org/?probe=7e9b335ee0) | Mar 05, 2023 |
| PCWare        | APM-A320G                   | [2bc24b8935](https://linux-hardware.org/?probe=2bc24b8935) | Mar 04, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [62309a2dac](https://linux-hardware.org/?probe=62309a2dac) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b61241e05e](https://linux-hardware.org/?probe=b61241e05e) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | [871c72708d](https://linux-hardware.org/?probe=871c72708d) | Mar 04, 2023 |
| OEM           | Unknown                     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| Positivo      | POS-PIH55BO POSITIVO        | [6396907447](https://linux-hardware.org/?probe=6396907447) | Mar 03, 2023 |
| Biostar       | B450MX-S                    | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| Gigabyte      | Z87M-D3H                    | [4f279ee581](https://linux-hardware.org/?probe=4f279ee581) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| ASUSTek       | M2N68-AM SE2                | [f4292f5622](https://linux-hardware.org/?probe=f4292f5622) | Mar 03, 2023 |
| Intel         | D525MW AAE93082-401         | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| DIEBOLD       | H55H-CM                     | [fadb939dd7](https://linux-hardware.org/?probe=fadb939dd7) | Mar 02, 2023 |
| ASRock        | 970A-G                      | [4a8ff8612a](https://linux-hardware.org/?probe=4a8ff8612a) | Mar 02, 2023 |
| Positivo      | POS-PIH55BO POSITIVO        | [ab9ad1a310](https://linux-hardware.org/?probe=ab9ad1a310) | Mar 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [85456379c1](https://linux-hardware.org/?probe=85456379c1) | Mar 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b6930e4615](https://linux-hardware.org/?probe=b6930e4615) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| Pegatron      | SM3330B 0500B               | [7ec6d4d881](https://linux-hardware.org/?probe=7ec6d4d881) | Mar 01, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [44e24e77eb](https://linux-hardware.org/?probe=44e24e77eb) | Mar 01, 2023 |
| ASUSTek       | P8H61-M LX                  | [5721cbc403](https://linux-hardware.org/?probe=5721cbc403) | Feb 28, 2023 |
| ASRock        | H81M-HG4 R4.0               | [47ed7baef0](https://linux-hardware.org/?probe=47ed7baef0) | Feb 28, 2023 |
| Gigabyte      | H61M-S1                     | [ee8e20d95e](https://linux-hardware.org/?probe=ee8e20d95e) | Feb 27, 2023 |
| PCWare        | IPMH61R2                    | [52a17bf9c1](https://linux-hardware.org/?probe=52a17bf9c1) | Feb 27, 2023 |
| Gigabyte      | H110M-S2V-CF                | [509c2a6e57](https://linux-hardware.org/?probe=509c2a6e57) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| Gigabyte      | B560M DS3H V2               | [31f6d9e11d](https://linux-hardware.org/?probe=31f6d9e11d) | Feb 26, 2023 |
| FIC           | PTM33 PCB                   | [b70b076cda](https://linux-hardware.org/?probe=b70b076cda) | Feb 26, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| ASRock        | H110M-HG4                   | [0a5dfbb9e6](https://linux-hardware.org/?probe=0a5dfbb9e6) | Feb 26, 2023 |
| Gigabyte      | M68MT-S2P                   | [d205de771a](https://linux-hardware.org/?probe=d205de771a) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | [336a7cad31](https://linux-hardware.org/?probe=336a7cad31) | Feb 25, 2023 |
| MSI           | 970 GAMING                  | [37bcb5eb45](https://linux-hardware.org/?probe=37bcb5eb45) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [30afdb56c5](https://linux-hardware.org/?probe=30afdb56c5) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bfa5623f15](https://linux-hardware.org/?probe=bfa5623f15) | Feb 25, 2023 |
| HP            | 2AA2                        | [b9411eadb7](https://linux-hardware.org/?probe=b9411eadb7) | Feb 25, 2023 |
| ASUSTek       | A88XM-A                     | [dff66700c0](https://linux-hardware.org/?probe=dff66700c0) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | [3f931a7600](https://linux-hardware.org/?probe=3f931a7600) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| ASRock        | N68-GS4 FX R2.0             | [6d03ea4905](https://linux-hardware.org/?probe=6d03ea4905) | Feb 24, 2023 |
| PCWare        | IPMH61R2                    | [eda674b9a5](https://linux-hardware.org/?probe=eda674b9a5) | Feb 24, 2023 |
| ASUSTek       | A68HM-K                     | [5c7e454884](https://linux-hardware.org/?probe=5c7e454884) | Feb 24, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [2a8b727725](https://linux-hardware.org/?probe=2a8b727725) | Feb 24, 2023 |
| MSI           | MEG Z390 GODLIKE            | [5f091de01b](https://linux-hardware.org/?probe=5f091de01b) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| ASUSTek       | B85M-E/BR                   | [e60b570c27](https://linux-hardware.org/?probe=e60b570c27) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| Intel         | H61                         | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| Positivo      | POS-PQ45AU POSITIVO         | [8ed6dacaa7](https://linux-hardware.org/?probe=8ed6dacaa7) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [fd084cb513](https://linux-hardware.org/?probe=fd084cb513) | Feb 23, 2023 |
| Intel         | H61                         | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| PCWare        | IPMH61R2                    | [f02c3d5895](https://linux-hardware.org/?probe=f02c3d5895) | Feb 22, 2023 |
| MSI           | MEG Z390 GODLIKE            | [974ae4135b](https://linux-hardware.org/?probe=974ae4135b) | Feb 22, 2023 |
| MSI           | B350 TOMAHAWK               | [71aa647a28](https://linux-hardware.org/?probe=71aa647a28) | Feb 22, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [aa39c9a471](https://linux-hardware.org/?probe=aa39c9a471) | Feb 22, 2023 |
| ASUSTek       | AM1M-A/BR                   | [d1c356a1c7](https://linux-hardware.org/?probe=d1c356a1c7) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ae2e7a22a0](https://linux-hardware.org/?probe=ae2e7a22a0) | Feb 21, 2023 |
| ASRock        | AM1B-MH                     | [d67d348d90](https://linux-hardware.org/?probe=d67d348d90) | Feb 20, 2023 |
| Win elemen... | M600                        | [76c26f5ebb](https://linux-hardware.org/?probe=76c26f5ebb) | Feb 20, 2023 |
| AMD           | A78FX VER                   | [36eb566c26](https://linux-hardware.org/?probe=36eb566c26) | Feb 20, 2023 |
| Intel         | H55                         | [6102979c67](https://linux-hardware.org/?probe=6102979c67) | Feb 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [8c8ae38704](https://linux-hardware.org/?probe=8c8ae38704) | Feb 19, 2023 |
| Dell          | 04YP6J A03                  | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | F2A68HM-H                   | [6be03ad579](https://linux-hardware.org/?probe=6be03ad579) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Login Info... | LOG-H61H2-M2                | [889231ad64](https://linux-hardware.org/?probe=889231ad64) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Intel         | H61                         | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [f3c66a583b](https://linux-hardware.org/?probe=f3c66a583b) | Feb 17, 2023 |
| MSI           | B350 TOMAHAWK               | [de9c98193e](https://linux-hardware.org/?probe=de9c98193e) | Feb 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9d88e03390](https://linux-hardware.org/?probe=9d88e03390) | Feb 17, 2023 |
| Lenovo        | 3164 NOK                    | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| ASUSTek       | M4N68T-M LE                 | [7b5fe965fd](https://linux-hardware.org/?probe=7b5fe965fd) | Feb 16, 2023 |
| DIEBOLD       | H55H-CM                     | [fdfc5c5e92](https://linux-hardware.org/?probe=fdfc5c5e92) | Feb 16, 2023 |
| Philco        | DTC-A55                     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| ASUSTek       | H61M-K                      | [b66ca441a7](https://linux-hardware.org/?probe=b66ca441a7) | Feb 16, 2023 |
| Pegatron      | SM3330B 0500B               | [701fdae932](https://linux-hardware.org/?probe=701fdae932) | Feb 16, 2023 |
| ASUSTek       | H81M-A/BR                   | [37674ee96e](https://linux-hardware.org/?probe=37674ee96e) | Feb 16, 2023 |
| Itautec       | ST 4265                     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| HP            | 8434 11                     | [2f4023e5f3](https://linux-hardware.org/?probe=2f4023e5f3) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| ASRock        | A320M-HD                    | [35fcd679e5](https://linux-hardware.org/?probe=35fcd679e5) | Feb 15, 2023 |
| ASRock        | N68-S3 FX                   | [a401dfe086](https://linux-hardware.org/?probe=a401dfe086) | Feb 14, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | [3569214674](https://linux-hardware.org/?probe=3569214674) | Feb 14, 2023 |
| ASRock        | N68-S3 FX                   | [5fefbd2419](https://linux-hardware.org/?probe=5fefbd2419) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [0b0a816ecc](https://linux-hardware.org/?probe=0b0a816ecc) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [4785d6d596](https://linux-hardware.org/?probe=4785d6d596) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [60794bd7c3](https://linux-hardware.org/?probe=60794bd7c3) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| DIEBOLD       | NM70-I                      | [ed4d687c32](https://linux-hardware.org/?probe=ed4d687c32) | Feb 14, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [39564bbf72](https://linux-hardware.org/?probe=39564bbf72) | Feb 13, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Lenovo        | ThinkCentre M57p 6073AG7    | [56411004d4](https://linux-hardware.org/?probe=56411004d4) | Feb 13, 2023 |
| ASUSTek       | M5A88-M                     | [e4b1d6656b](https://linux-hardware.org/?probe=e4b1d6656b) | Feb 13, 2023 |
| Intel         | H61                         | [f220565e36](https://linux-hardware.org/?probe=f220565e36) | Feb 12, 2023 |
| Unknown       | Unknown                     | [df52d514c9](https://linux-hardware.org/?probe=df52d514c9) | Feb 12, 2023 |
| Intel         | H61                         | [800d3a961c](https://linux-hardware.org/?probe=800d3a961c) | Feb 12, 2023 |
| Intel         | H61                         | [7a6e4d8211](https://linux-hardware.org/?probe=7a6e4d8211) | Feb 12, 2023 |
| ASUSTek       | M5A88-M                     | [f1b285512e](https://linux-hardware.org/?probe=f1b285512e) | Feb 12, 2023 |
| Pegatron      | SM3330B 0500B               | [d2fec952ae](https://linux-hardware.org/?probe=d2fec952ae) | Feb 12, 2023 |
| Colorful T... | CVN B450M GAMING V14        | [fdedcd0d4a](https://linux-hardware.org/?probe=fdedcd0d4a) | Feb 11, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [1623076357](https://linux-hardware.org/?probe=1623076357) | Feb 11, 2023 |
| Compaq        | Presario CQ-14              | [515b629bbc](https://linux-hardware.org/?probe=515b629bbc) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [d85a564e73](https://linux-hardware.org/?probe=d85a564e73) | Feb 11, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [abfd3f65af](https://linux-hardware.org/?probe=abfd3f65af) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| Gigabyte      | GA-A75-UD4H                 | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Lenovo        | Unknown                     | [253bcab6fa](https://linux-hardware.org/?probe=253bcab6fa) | Feb 09, 2023 |
| ASRock        | B450M Pro4-F                | [35bd9cf04c](https://linux-hardware.org/?probe=35bd9cf04c) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3b71a70207](https://linux-hardware.org/?probe=3b71a70207) | Feb 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fe84bf2bc9](https://linux-hardware.org/?probe=fe84bf2bc9) | Feb 09, 2023 |
| Lenovo        | 3164 NOK                    | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Dell          | 0TW904                      | [01c887764a](https://linux-hardware.org/?probe=01c887764a) | Feb 08, 2023 |
| Intel         | H61                         | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Dell          | 0TW904                      | [f88778be48](https://linux-hardware.org/?probe=f88778be48) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| Lenovo        | 3102 NOK                    | [2a34c65a5d](https://linux-hardware.org/?probe=2a34c65a5d) | Feb 06, 2023 |
| Lenovo        | 3102 NOK                    | [0b35653efd](https://linux-hardware.org/?probe=0b35653efd) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [cfdb3767fb](https://linux-hardware.org/?probe=cfdb3767fb) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [f0aa46956b](https://linux-hardware.org/?probe=f0aa46956b) | Feb 06, 2023 |
| Gigabyte      | B450 AORUS M                | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L LE                   | [0e0bd23571](https://linux-hardware.org/?probe=0e0bd23571) | Feb 05, 2023 |
| ASUSTek       | M5A78L LE                   | [5c63c52fd4](https://linux-hardware.org/?probe=5c63c52fd4) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| LG Electro... | R590-U.BE57P1               | [7de316c06f](https://linux-hardware.org/?probe=7de316c06f) | Feb 05, 2023 |
| ASRock        | H61M-HP4                    | [826a81ae2e](https://linux-hardware.org/?probe=826a81ae2e) | Feb 05, 2023 |
| OEM           | Intel H81                   | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [7cd8292c5f](https://linux-hardware.org/?probe=7cd8292c5f) | Feb 04, 2023 |
| Lenovo        | ThinkCentre M57p 6073AG7    | [01a8e618f5](https://linux-hardware.org/?probe=01a8e618f5) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [2cb7086ff1](https://linux-hardware.org/?probe=2cb7086ff1) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| HP            | 3048h                       | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | [5c7d71b636](https://linux-hardware.org/?probe=5c7d71b636) | Feb 03, 2023 |
| Intel         | H61                         | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| Dell          | 0TW904                      | [83d5b82840](https://linux-hardware.org/?probe=83d5b82840) | Feb 03, 2023 |
| Gigabyte      | G31M-S2C                    | [3e5a2f20cc](https://linux-hardware.org/?probe=3e5a2f20cc) | Feb 03, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [a99bd855d2](https://linux-hardware.org/?probe=a99bd855d2) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | [2aa4452578](https://linux-hardware.org/?probe=2aa4452578) | Feb 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [516e83f7e6](https://linux-hardware.org/?probe=516e83f7e6) | Feb 02, 2023 |
| PCWare        | IPMH61R3                    | [e296e8530f](https://linux-hardware.org/?probe=e296e8530f) | Feb 02, 2023 |
| ASUSTek       | H81M-A/BR                   | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6aa10285fe](https://linux-hardware.org/?probe=6aa10285fe) | Feb 01, 2023 |
| PCWare        | IPX525R2-D3                 | [20868d90a7](https://linux-hardware.org/?probe=20868d90a7) | Feb 01, 2023 |
| PCWare        | IPX525R2-D3                 | [d67831dc82](https://linux-hardware.org/?probe=d67831dc82) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [aa3b7e2dc8](https://linux-hardware.org/?probe=aa3b7e2dc8) | Feb 01, 2023 |
| AZW           | U59                         | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| AMD           | Inagua CRB                  | [3f497311dd](https://linux-hardware.org/?probe=3f497311dd) | Jan 31, 2023 |
| Dell          | 06HR05 A00                  | [b80c55d90d](https://linux-hardware.org/?probe=b80c55d90d) | Jan 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [d8d386cb1d](https://linux-hardware.org/?probe=d8d386cb1d) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| ASUSTek       | H61M-A/BR                   | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| PCWare        | IPMH110G                    | [95fe94d9f4](https://linux-hardware.org/?probe=95fe94d9f4) | Jan 30, 2023 |
| ASUSTek       | H81M-CS/BR                  | [ca82a3e5a7](https://linux-hardware.org/?probe=ca82a3e5a7) | Jan 29, 2023 |
| Intel         | H61                         | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| Dell          | 0VRWRC A01                  | [0e6a170715](https://linux-hardware.org/?probe=0e6a170715) | Jan 29, 2023 |
| Intel         | H61                         | [0ce404915f](https://linux-hardware.org/?probe=0ce404915f) | Jan 29, 2023 |
| Toshiba       | STI 010433                  | [fead488cf1](https://linux-hardware.org/?probe=fead488cf1) | Jan 29, 2023 |
| ASUSTek       | PRIME Z690-A                | [8dee7ae6ec](https://linux-hardware.org/?probe=8dee7ae6ec) | Jan 28, 2023 |
| ASUSTek       | H81M-A/BR                   | [ca72045652](https://linux-hardware.org/?probe=ca72045652) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASRock        | N68C-S UCC                  | [de8739d9d5](https://linux-hardware.org/?probe=de8739d9d5) | Jan 28, 2023 |
| ASUSTek       | A58M-A/BR                   | [2e6e55e6ea](https://linux-hardware.org/?probe=2e6e55e6ea) | Jan 28, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [41ff395299](https://linux-hardware.org/?probe=41ff395299) | Jan 28, 2023 |
| Gigabyte      | B75M-D3H                    | [3ee2e6ab56](https://linux-hardware.org/?probe=3ee2e6ab56) | Jan 27, 2023 |
| Intel         | DH77EB AAG39073-304         | [8965805130](https://linux-hardware.org/?probe=8965805130) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| Positivo      | POS-PIB150DT                | [5a333d4e71](https://linux-hardware.org/?probe=5a333d4e71) | Jan 26, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [90de00d686](https://linux-hardware.org/?probe=90de00d686) | Jan 26, 2023 |
| HP            | 225E                        | [bace147a01](https://linux-hardware.org/?probe=bace147a01) | Jan 26, 2023 |
| HP            | 8299                        | [d73eaeeb81](https://linux-hardware.org/?probe=d73eaeeb81) | Jan 26, 2023 |
| HP            | 8299                        | [47b5f3fdef](https://linux-hardware.org/?probe=47b5f3fdef) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| Gigabyte      | B75M-D3H                    | [6eafb4ceab](https://linux-hardware.org/?probe=6eafb4ceab) | Jan 25, 2023 |
| ASUSTek       | P8H67-M LX                  | [b8045702e2](https://linux-hardware.org/?probe=b8045702e2) | Jan 25, 2023 |
| Gigabyte      | M68MT-S2P                   | [5e044ca68b](https://linux-hardware.org/?probe=5e044ca68b) | Jan 25, 2023 |
| Intel         | DG31PR AAE58249-306         | [a123c38d76](https://linux-hardware.org/?probe=a123c38d76) | Jan 25, 2023 |
| MSI           | 2A9C                        | [cea7204c4b](https://linux-hardware.org/?probe=cea7204c4b) | Jan 25, 2023 |
| Gigabyte      | H310M M.2                   | [2fbe64570f](https://linux-hardware.org/?probe=2fbe64570f) | Jan 25, 2023 |
| Gigabyte      | H310M M.2                   | [30967bc549](https://linux-hardware.org/?probe=30967bc549) | Jan 23, 2023 |
| Gigabyte      | A520M S2H                   | [08f11b861b](https://linux-hardware.org/?probe=08f11b861b) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| Intel         | DG31PR AAE58249-306         | [885f180987](https://linux-hardware.org/?probe=885f180987) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Unknown       | G41T-M7                     | [026810c423](https://linux-hardware.org/?probe=026810c423) | Jan 22, 2023 |
| Biostar       | A320MH                      | [4c75d6c079](https://linux-hardware.org/?probe=4c75d6c079) | Jan 22, 2023 |
| Gigabyte      | A320M-H-CF                  | [14a5fa99db](https://linux-hardware.org/?probe=14a5fa99db) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| ASUSTek       | PRIME H310M-K               | [b066912bf8](https://linux-hardware.org/?probe=b066912bf8) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| Intel         | DG31PR AAE58249-306         | [e5fff0ebe0](https://linux-hardware.org/?probe=e5fff0ebe0) | Jan 21, 2023 |
| ASUSTek       | PRIME H510M-A               | [42e0ba4db2](https://linux-hardware.org/?probe=42e0ba4db2) | Jan 21, 2023 |
| Intel         | DG31PR AAE58249-306         | [8a3035382a](https://linux-hardware.org/?probe=8a3035382a) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| Lenovo        | 3148 SDK0L22692 WIN 3792... | [f66c33020e](https://linux-hardware.org/?probe=f66c33020e) | Jan 21, 2023 |
| Dell          | 0VC8RJ X02                  | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Intel         | B75                         | [40da372747](https://linux-hardware.org/?probe=40da372747) | Jan 20, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [2d420c3acb](https://linux-hardware.org/?probe=2d420c3acb) | Jan 20, 2023 |
| Gigabyte      | H61M-S1                     | [97987f88e7](https://linux-hardware.org/?probe=97987f88e7) | Jan 20, 2023 |
| AZW           | SEi                         | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| AZW           | SEi                         | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1320f35331](https://linux-hardware.org/?probe=1320f35331) | Jan 20, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [c2f25e54e6](https://linux-hardware.org/?probe=c2f25e54e6) | Jan 19, 2023 |
| Unknown       | Unknown                     | [d4480b6267](https://linux-hardware.org/?probe=d4480b6267) | Jan 19, 2023 |
| Intel         | H110                        | [532f2a340e](https://linux-hardware.org/?probe=532f2a340e) | Jan 19, 2023 |
| Digitron      | G31T-M7                     | [ee9978ae25](https://linux-hardware.org/?probe=ee9978ae25) | Jan 19, 2023 |
| ASUSTek       | H110M-C/BR                  | [58bed7db63](https://linux-hardware.org/?probe=58bed7db63) | Jan 19, 2023 |
| Intel         | H61                         | [be9b2384b0](https://linux-hardware.org/?probe=be9b2384b0) | Jan 18, 2023 |
| Gigabyte      | H61M-S1                     | [80022afba6](https://linux-hardware.org/?probe=80022afba6) | Jan 18, 2023 |
| Toshiba       | STI 014293                  | [8e47b89089](https://linux-hardware.org/?probe=8e47b89089) | Jan 18, 2023 |
| ASRock        | H510M-HVS R2.0              | [3ee772766c](https://linux-hardware.org/?probe=3ee772766c) | Jan 18, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [1a8a1eea59](https://linux-hardware.org/?probe=1a8a1eea59) | Jan 17, 2023 |
| Login Info... | LOG-H110M-G3                | [74defcfa62](https://linux-hardware.org/?probe=74defcfa62) | Jan 17, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [0b7d83316f](https://linux-hardware.org/?probe=0b7d83316f) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| ASUSTek       | M2N68-AM                    | [e08287f623](https://linux-hardware.org/?probe=e08287f623) | Jan 17, 2023 |
| ASUSTek       | M2N68-AM                    | [c4dbd0f9fe](https://linux-hardware.org/?probe=c4dbd0f9fe) | Jan 17, 2023 |
| Gigabyte      | 945GCM-S2C                  | [23a3b53ebd](https://linux-hardware.org/?probe=23a3b53ebd) | Jan 17, 2023 |
| ASUSTek       | PRIME H410M-E               | [57aec688e4](https://linux-hardware.org/?probe=57aec688e4) | Jan 17, 2023 |
| Gigabyte      | H61M-S1                     | [a7970f0c50](https://linux-hardware.org/?probe=a7970f0c50) | Jan 16, 2023 |
| Gigabyte      | H61M-S1                     | [bf5d9763f7](https://linux-hardware.org/?probe=bf5d9763f7) | Jan 16, 2023 |
| Toshiba       | STI 007030                  | [c0eb39ae66](https://linux-hardware.org/?probe=c0eb39ae66) | Jan 16, 2023 |
| Biostar       | A320MH                      | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Intel         | JSL MRD                     | [edbaf7bb5d](https://linux-hardware.org/?probe=edbaf7bb5d) | Jan 16, 2023 |
| MSI           | 2A9C                        | [7a4c26c267](https://linux-hardware.org/?probe=7a4c26c267) | Jan 15, 2023 |
| Lenovo        | ThinkCentre M58e 7303BZ2    | [af99ffb577](https://linux-hardware.org/?probe=af99ffb577) | Jan 15, 2023 |
| Biostar       | A320MH                      | [3fb3a04230](https://linux-hardware.org/?probe=3fb3a04230) | Jan 14, 2023 |
| Gigabyte      | H310M M.2                   | [4eecdbd79d](https://linux-hardware.org/?probe=4eecdbd79d) | Jan 14, 2023 |
| MAXSUN        | MS-TZZ B460M                | [14758fc3e7](https://linux-hardware.org/?probe=14758fc3e7) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d1e2f08907](https://linux-hardware.org/?probe=d1e2f08907) | Jan 14, 2023 |
| MACHINIST     | B75 PRO V1.0                | [c0728b5e41](https://linux-hardware.org/?probe=c0728b5e41) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| Intel         | H55                         | [4fdea85eec](https://linux-hardware.org/?probe=4fdea85eec) | Jan 14, 2023 |
| Intel         | H55                         | [d875a18037](https://linux-hardware.org/?probe=d875a18037) | Jan 14, 2023 |
| ASUSTek       | PRIME H410M-E               | [0c15b80c58](https://linux-hardware.org/?probe=0c15b80c58) | Jan 13, 2023 |
| PCWare        | IPX1800E2                   | [57e454fc85](https://linux-hardware.org/?probe=57e454fc85) | Jan 13, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [dc7954e720](https://linux-hardware.org/?probe=dc7954e720) | Jan 13, 2023 |
| Intel         | H61                         | [fde46524d3](https://linux-hardware.org/?probe=fde46524d3) | Jan 13, 2023 |
| ASUSTek       | A88XM-A                     | [06851118fe](https://linux-hardware.org/?probe=06851118fe) | Jan 13, 2023 |
| MSI           | A68HM-E33                   | [8e81067cd2](https://linux-hardware.org/?probe=8e81067cd2) | Jan 13, 2023 |
| Pegatron      | IPM31G                      | [04e04dc57b](https://linux-hardware.org/?probe=04e04dc57b) | Jan 12, 2023 |
| HP            | 3047h                       | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| HP            | 3047h                       | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| ASRock        | H110M-HG4                   | [e14d589500](https://linux-hardware.org/?probe=e14d589500) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| ASRock        | FM2A68M-DG3+                | [acc9ea9c40](https://linux-hardware.org/?probe=acc9ea9c40) | Jan 11, 2023 |
| HP            | 82A2                        | [21321971f7](https://linux-hardware.org/?probe=21321971f7) | Jan 11, 2023 |
| ADVANSUS      | 945G                        | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Gigabyte      | B450 AORUS M                | [0851440887](https://linux-hardware.org/?probe=0851440887) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Gigabyte      | M68MT-S2P                   | [97f4c3c67a](https://linux-hardware.org/?probe=97f4c3c67a) | Jan 11, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [f4d9052764](https://linux-hardware.org/?probe=f4d9052764) | Jan 10, 2023 |
| ASUSTek       | P8Z77-V LX                  | [0239336b7c](https://linux-hardware.org/?probe=0239336b7c) | Jan 10, 2023 |
| ASUSTek       | H81M-CS/BR                  | [26747becd2](https://linux-hardware.org/?probe=26747becd2) | Jan 10, 2023 |
| ASUSTek       | M2A-VM HDMI                 | [02524a1989](https://linux-hardware.org/?probe=02524a1989) | Jan 10, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [52164aa403](https://linux-hardware.org/?probe=52164aa403) | Jan 10, 2023 |
| Gigabyte      | A520M DS3H                  | [d4ea636610](https://linux-hardware.org/?probe=d4ea636610) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| Intel         | B75                         | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [6c7320f939](https://linux-hardware.org/?probe=6c7320f939) | Jan 09, 2023 |
| Dell          | 0VRWRC A01                  | [45e73c7052](https://linux-hardware.org/?probe=45e73c7052) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [699eb66c12](https://linux-hardware.org/?probe=699eb66c12) | Jan 09, 2023 |
| ASUSTek       | M4A88T-M                    | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| Dell          | 0N820C A02                  | [6fa7639fd2](https://linux-hardware.org/?probe=6fa7639fd2) | Jan 07, 2023 |
| Dell          | 0VXN67 A01                  | [843a02520e](https://linux-hardware.org/?probe=843a02520e) | Jan 07, 2023 |
| Biostar       | G31-M7 TE                   | [16dd478d1e](https://linux-hardware.org/?probe=16dd478d1e) | Jan 06, 2023 |
| MSI           | H61M-E22/W8                 | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [122079f900](https://linux-hardware.org/?probe=122079f900) | Jan 06, 2023 |
| Pegatron      | 2AC3                        | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| Dell          | 01XK1W A00                  | [bb487db79f](https://linux-hardware.org/?probe=bb487db79f) | Jan 05, 2023 |
| Positivo      | POS-PIQ57BQA                | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | [5b13eb0dad](https://linux-hardware.org/?probe=5b13eb0dad) | Jan 04, 2023 |
| Unknown       | Unknown                     | [1e69c79d74](https://linux-hardware.org/?probe=1e69c79d74) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| Dell          | 0P99M4 A01                  | [0b6a911c16](https://linux-hardware.org/?probe=0b6a911c16) | Jan 03, 2023 |
| Dell          | 0VTJVC A00                  | [8a502c849f](https://linux-hardware.org/?probe=8a502c849f) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| ASUSTek       | B85M-E/BR                   | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| JGINYUE       | B85I PLUS V2.0              | [28a07cbbe1](https://linux-hardware.org/?probe=28a07cbbe1) | Jan 02, 2023 |
| JGINYUE       | B85I PLUS V2.0              | [3cde9738e7](https://linux-hardware.org/?probe=3cde9738e7) | Jan 02, 2023 |
| PCWare        | IPMH110G                    | [a795f33f7a](https://linux-hardware.org/?probe=a795f33f7a) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e26cc7285f](https://linux-hardware.org/?probe=e26cc7285f) | Jan 02, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [de65f4b654](https://linux-hardware.org/?probe=de65f4b654) | Dec 31, 2022 |
| Dell          | 0VR8V9 A01                  | [0e7d4ac326](https://linux-hardware.org/?probe=0e7d4ac326) | Dec 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [2508c5972e](https://linux-hardware.org/?probe=2508c5972e) | Dec 31, 2022 |
| ASRock        | B360M Performance           | [679d25f9be](https://linux-hardware.org/?probe=679d25f9be) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| HOUTER        | IPMIP-GS                    | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [1c7a329282](https://linux-hardware.org/?probe=1c7a329282) | Dec 30, 2022 |
| PCWare        | IPMH61R1                    | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [83608f4248](https://linux-hardware.org/?probe=83608f4248) | Dec 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [2522f716da](https://linux-hardware.org/?probe=2522f716da) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASRock        | H61M-HG4                    | [8658fa0fa3](https://linux-hardware.org/?probe=8658fa0fa3) | Dec 27, 2022 |
| ASRock        | H61M-HG4                    | [cf7ba71c5e](https://linux-hardware.org/?probe=cf7ba71c5e) | Dec 27, 2022 |
| Megaware      | MW-H61M-2H v1.3 - 17/07/... | [868a87a1f8](https://linux-hardware.org/?probe=868a87a1f8) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e12a45a65f](https://linux-hardware.org/?probe=e12a45a65f) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [4f28247dcb](https://linux-hardware.org/?probe=4f28247dcb) | Dec 25, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | [d66db29328](https://linux-hardware.org/?probe=d66db29328) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [27612d2f72](https://linux-hardware.org/?probe=27612d2f72) | Dec 24, 2022 |
| Intel         | H61                         | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | [2979740651](https://linux-hardware.org/?probe=2979740651) | Dec 24, 2022 |
| ASRock        | A320M-HD                    | [5307c53c91](https://linux-hardware.org/?probe=5307c53c91) | Dec 22, 2022 |
| PERTOSA       | IPMSBA                      | [8cd4fff2ce](https://linux-hardware.org/?probe=8cd4fff2ce) | Dec 22, 2022 |
| PCWare        | IPMH310 PRO 1.0             | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Intel         | X99 V1.0                    | [20c96ed6dd](https://linux-hardware.org/?probe=20c96ed6dd) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [363c106fa2](https://linux-hardware.org/?probe=363c106fa2) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [ed29442d39](https://linux-hardware.org/?probe=ed29442d39) | Dec 21, 2022 |
| Intel         | B75                         | [368e71afd7](https://linux-hardware.org/?probe=368e71afd7) | Dec 21, 2022 |
| Intel         | X99 V1.x                    | [5e961d12dc](https://linux-hardware.org/?probe=5e961d12dc) | Dec 21, 2022 |
| PCWare        | IPMH81G1                    | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| Gigabyte      | F2A68HM-H                   | [79cf1b618f](https://linux-hardware.org/?probe=79cf1b618f) | Dec 20, 2022 |
| ECS           | G31T-M7                     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [533bf9eafc](https://linux-hardware.org/?probe=533bf9eafc) | Dec 19, 2022 |
| Gigabyte      | 970A-DS3P                   | [6870f7c47f](https://linux-hardware.org/?probe=6870f7c47f) | Dec 18, 2022 |
| Intel         | HM570                       | [627a39bc3f](https://linux-hardware.org/?probe=627a39bc3f) | Dec 18, 2022 |
| Intel         | HM570                       | [303e68f585](https://linux-hardware.org/?probe=303e68f585) | Dec 18, 2022 |
| Dell          | 0UY894 A02                  | [904ee2bb12](https://linux-hardware.org/?probe=904ee2bb12) | Dec 18, 2022 |
| ASRock        | 960GC-GS FX                 | [a61b5c0129](https://linux-hardware.org/?probe=a61b5c0129) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| Biostar       | X470GTN                     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| Intel         | H55                         | [c034f3b3db](https://linux-hardware.org/?probe=c034f3b3db) | Dec 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [0b1367de2f](https://linux-hardware.org/?probe=0b1367de2f) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [60848aa48e](https://linux-hardware.org/?probe=60848aa48e) | Dec 16, 2022 |
| Pegatron      | IPM41-D3                    | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [6bd184b75a](https://linux-hardware.org/?probe=6bd184b75a) | Dec 15, 2022 |
| Biostar       | B460GTQ                     | [7f3836bddf](https://linux-hardware.org/?probe=7f3836bddf) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [bed03c8f85](https://linux-hardware.org/?probe=bed03c8f85) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d6244def87](https://linux-hardware.org/?probe=d6244def87) | Dec 14, 2022 |
| MSI           | X370 SLI PLUS               | [7c32d0f453](https://linux-hardware.org/?probe=7c32d0f453) | Dec 14, 2022 |
| ASUSTek       | M4N78 SE                    | [e37cb274ff](https://linux-hardware.org/?probe=e37cb274ff) | Dec 14, 2022 |
| Gigabyte      | B75M-D3H                    | [f522fb6cbd](https://linux-hardware.org/?probe=f522fb6cbd) | Dec 13, 2022 |
| Gigabyte      | B75M-D3H                    | [4de5804244](https://linux-hardware.org/?probe=4de5804244) | Dec 13, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [70506a428c](https://linux-hardware.org/?probe=70506a428c) | Dec 13, 2022 |
| PCWare        | IPMH110G                    | [baa0f26af0](https://linux-hardware.org/?probe=baa0f26af0) | Dec 13, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [51acd303f0](https://linux-hardware.org/?probe=51acd303f0) | Dec 12, 2022 |
| Dell          | 042P49 A01                  | [fc5be35686](https://linux-hardware.org/?probe=fc5be35686) | Dec 12, 2022 |
| ASUSTek       | SABERTOOTH X99              | [c0bf1336d5](https://linux-hardware.org/?probe=c0bf1336d5) | Dec 12, 2022 |
| Braview       | BRW-BSWI-D2                 | [1568a74103](https://linux-hardware.org/?probe=1568a74103) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | [dcd96a2b45](https://linux-hardware.org/?probe=dcd96a2b45) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | [9f9fafa75b](https://linux-hardware.org/?probe=9f9fafa75b) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| Intel         | DX58SO AAE29331-702         | [685274600b](https://linux-hardware.org/?probe=685274600b) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a64decb842](https://linux-hardware.org/?probe=a64decb842) | Dec 10, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [830ec0e7be](https://linux-hardware.org/?probe=830ec0e7be) | Dec 10, 2022 |
| ASUSTek       | Z170M-PLUS/BR               | [62779a600c](https://linux-hardware.org/?probe=62779a600c) | Dec 09, 2022 |
| ASUSTek       | Z170M-PLUS/BR               | [ac8d321e9a](https://linux-hardware.org/?probe=ac8d321e9a) | Dec 09, 2022 |
| ASRock        | A320M-HD                    | [aea1c7da95](https://linux-hardware.org/?probe=aea1c7da95) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | [b1ac2fbabe](https://linux-hardware.org/?probe=b1ac2fbabe) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| PCWare        | IPMH61R3                    | [d216c11fea](https://linux-hardware.org/?probe=d216c11fea) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c376825cca](https://linux-hardware.org/?probe=c376825cca) | Dec 07, 2022 |
| Unknown       | PCWARE APMCP68              | [bf85f27d83](https://linux-hardware.org/?probe=bf85f27d83) | Dec 07, 2022 |
| Gigabyte      | B75M-D3H                    | [33472ea902](https://linux-hardware.org/?probe=33472ea902) | Dec 06, 2022 |
| Gigabyte      | B75M-D3H                    | [f4f7580aff](https://linux-hardware.org/?probe=f4f7580aff) | Dec 06, 2022 |
| HP            | 3397                        | [efcd9d806e](https://linux-hardware.org/?probe=efcd9d806e) | Dec 06, 2022 |
| Dell          | 0HN7XN A01                  | [72203965d8](https://linux-hardware.org/?probe=72203965d8) | Dec 06, 2022 |
| Dell          | 01XK1W A00                  | [e2ec28bd7c](https://linux-hardware.org/?probe=e2ec28bd7c) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [97595fe5a1](https://linux-hardware.org/?probe=97595fe5a1) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69cc6b3ad3](https://linux-hardware.org/?probe=69cc6b3ad3) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| PCWare        | IPMH110G                    | [0574aeace9](https://linux-hardware.org/?probe=0574aeace9) | Dec 05, 2022 |
| MSI           | X370 SLI PLUS               | [e6941ba491](https://linux-hardware.org/?probe=e6941ba491) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [b5c74add87](https://linux-hardware.org/?probe=b5c74add87) | Dec 04, 2022 |
| MSI           | MAG B550M MORTAR            | [ad81cbb6e4](https://linux-hardware.org/?probe=ad81cbb6e4) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | 2A9C                        | [d7b2898f42](https://linux-hardware.org/?probe=d7b2898f42) | Dec 03, 2022 |
| Intel         | H61                         | [4050e46b94](https://linux-hardware.org/?probe=4050e46b94) | Dec 03, 2022 |
| MSI           | 2A9C                        | [52ab7bcdde](https://linux-hardware.org/?probe=52ab7bcdde) | Dec 03, 2022 |
| Unknown       | DH61BR G32662-203           | [c22d1caae4](https://linux-hardware.org/?probe=c22d1caae4) | Dec 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c2c53a959d](https://linux-hardware.org/?probe=c2c53a959d) | Dec 03, 2022 |
| Intel         | X99                         | [bd1d84cf82](https://linux-hardware.org/?probe=bd1d84cf82) | Dec 02, 2022 |
| Intel         | X99                         | [4051f684d8](https://linux-hardware.org/?probe=4051f684d8) | Dec 02, 2022 |
| ABIT          | I-45CV                      | [54b95d7794](https://linux-hardware.org/?probe=54b95d7794) | Dec 02, 2022 |
| Lenovo        | 3102 NOK                    | [8bfdcedec6](https://linux-hardware.org/?probe=8bfdcedec6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [7ff54a3b05](https://linux-hardware.org/?probe=7ff54a3b05) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| Colorful T... | DJ H310M-E V20              | [ef8cb053dc](https://linux-hardware.org/?probe=ef8cb053dc) | Nov 30, 2022 |
| Colorful T... | DJ H310M-E V20              | [9831bd75b9](https://linux-hardware.org/?probe=9831bd75b9) | Nov 30, 2022 |
| Unknown       | X99H                        | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| Biostar       | H81MHV3 5.0                 | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Intel         | H61                         | [42f943bc9c](https://linux-hardware.org/?probe=42f943bc9c) | Nov 28, 2022 |
| PCWare        | IPMH61R1                    | [7872d8f10f](https://linux-hardware.org/?probe=7872d8f10f) | Nov 28, 2022 |
| Gigabyte      | B450 AORUS M                | [8263c8ba6f](https://linux-hardware.org/?probe=8263c8ba6f) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| AMD           | 58514                       | [7558bc36a0](https://linux-hardware.org/?probe=7558bc36a0) | Nov 27, 2022 |
| ASUSTek       | H81M-K                      | [4de72d3d12](https://linux-hardware.org/?probe=4de72d3d12) | Nov 26, 2022 |
| MSI           | P55-CD53                    | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| ASUSTek       | B150M-C                     | [bbbdc2b291](https://linux-hardware.org/?probe=bbbdc2b291) | Nov 26, 2022 |
| Unknown       | PCWARE APMCP68              | [0cb03d53bb](https://linux-hardware.org/?probe=0cb03d53bb) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Intel         | Unknown                     | [bcf46201bc](https://linux-hardware.org/?probe=bcf46201bc) | Nov 25, 2022 |
| ASRock        | B460M-HDV                   | [00c07e7aa9](https://linux-hardware.org/?probe=00c07e7aa9) | Nov 25, 2022 |
| Intel         | H61                         | [76825e4753](https://linux-hardware.org/?probe=76825e4753) | Nov 25, 2022 |
| HP            | 18E7                        | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Positivo      | P5VD2-MX                    | [c9d4c5ea2b](https://linux-hardware.org/?probe=c9d4c5ea2b) | Nov 25, 2022 |
| ASUSTek       | J1800I-C/BR                 | [9cfe40fa0b](https://linux-hardware.org/?probe=9cfe40fa0b) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| PCWare        | APM-A320G                   | [a56cdcbd3b](https://linux-hardware.org/?probe=a56cdcbd3b) | Nov 24, 2022 |
| ASRock        | X570M Pro4                  | [2b2778b81a](https://linux-hardware.org/?probe=2b2778b81a) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| HP            | 0266                        | [13e2e10478](https://linux-hardware.org/?probe=13e2e10478) | Nov 23, 2022 |
| MSI           | 2A9C                        | [ee8683a595](https://linux-hardware.org/?probe=ee8683a595) | Nov 23, 2022 |
| MSI           | 2A9C                        | [77dd7e3fbc](https://linux-hardware.org/?probe=77dd7e3fbc) | Nov 23, 2022 |
| Intel         | B75                         | [24b64d225a](https://linux-hardware.org/?probe=24b64d225a) | Nov 22, 2022 |
| PCWare        | IPMH61R2                    | [93db11744b](https://linux-hardware.org/?probe=93db11744b) | Nov 22, 2022 |
| PCWare        | IPMH110G                    | [7d952c2b0d](https://linux-hardware.org/?probe=7d952c2b0d) | Nov 22, 2022 |
| Biostar       | A320MH                      | [79eeacd665](https://linux-hardware.org/?probe=79eeacd665) | Nov 21, 2022 |
| Gigabyte      | B75M-D3H                    | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| ASRock        | H310CM-HG4                  | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [4599b81a6b](https://linux-hardware.org/?probe=4599b81a6b) | Nov 21, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [93bb909388](https://linux-hardware.org/?probe=93bb909388) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| MSI           | Z77A-G43                    | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| MSI           | H61M-P21                    | [a91ee7dc9d](https://linux-hardware.org/?probe=a91ee7dc9d) | Nov 19, 2022 |
| ASUSTek       | P8H61-M PLUS V2             | [ff279b1860](https://linux-hardware.org/?probe=ff279b1860) | Nov 18, 2022 |
| Dell          | 0KWVT8 A02                  | [e1b586a15a](https://linux-hardware.org/?probe=e1b586a15a) | Nov 18, 2022 |
| Gigabyte      | G31M-S2L                    | [bc588177c4](https://linux-hardware.org/?probe=bc588177c4) | Nov 18, 2022 |
| AMD           | A88                         | [4f23ffbfe2](https://linux-hardware.org/?probe=4f23ffbfe2) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| PCWare        | IPX4005G                    | [9989340108](https://linux-hardware.org/?probe=9989340108) | Nov 17, 2022 |
| Login Info... | LOG-H61H2-M2                | [aff41de38e](https://linux-hardware.org/?probe=aff41de38e) | Nov 17, 2022 |
| ASUSTek       | P5KPL/1600                  | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| Intel         | H61                         | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| Dell          | 0RW199                      | [df40ccbcdb](https://linux-hardware.org/?probe=df40ccbcdb) | Nov 15, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e7f05e6eac](https://linux-hardware.org/?probe=e7f05e6eac) | Nov 15, 2022 |
| Huanan        | X99-F8                      | [0e3b4121ea](https://linux-hardware.org/?probe=0e3b4121ea) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| Gigabyte      | Z370XP SLI-CF               | [3b6d611387](https://linux-hardware.org/?probe=3b6d611387) | Nov 14, 2022 |
| Gigabyte      | B75M-D3H                    | [62348f8b41](https://linux-hardware.org/?probe=62348f8b41) | Nov 13, 2022 |
| PCWare        | IPMH61R3                    | [7b7925f93d](https://linux-hardware.org/?probe=7b7925f93d) | Nov 13, 2022 |
| ASUSTek       | TUF B360-PLUS GAMING        | [d29245dafc](https://linux-hardware.org/?probe=d29245dafc) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Intel         | H55                         | [b3cbb34a98](https://linux-hardware.org/?probe=b3cbb34a98) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| Intel         | H55                         | [c4171c6957](https://linux-hardware.org/?probe=c4171c6957) | Nov 12, 2022 |
| Colorful T... | DJ H310M-E V20              | [6ac470070c](https://linux-hardware.org/?probe=6ac470070c) | Nov 12, 2022 |
| Gigabyte      | Z370XP SLI-CF               | [4e0b0368b8](https://linux-hardware.org/?probe=4e0b0368b8) | Nov 12, 2022 |
| Intel         | H61                         | [7d93f12ac4](https://linux-hardware.org/?probe=7d93f12ac4) | Nov 11, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [13f37888d5](https://linux-hardware.org/?probe=13f37888d5) | Nov 11, 2022 |
| Intel         | DG41WV AAE90316-102         | [517598326a](https://linux-hardware.org/?probe=517598326a) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [f20eddfba9](https://linux-hardware.org/?probe=f20eddfba9) | Nov 10, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
| PCWare        | IPMH61R1                    | [6a668c9151](https://linux-hardware.org/?probe=6a668c9151) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [3e90cd2d25](https://linux-hardware.org/?probe=3e90cd2d25) | Nov 09, 2022 |
| OKI Brasil    | ST 4280 Padrao              | [f2841b0f4d](https://linux-hardware.org/?probe=f2841b0f4d) | Nov 08, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [3ffeeccb58](https://linux-hardware.org/?probe=3ffeeccb58) | Nov 08, 2022 |
| OKI Brasil    | ST 4280 Padrao              | [58cb07d7e1](https://linux-hardware.org/?probe=58cb07d7e1) | Nov 08, 2022 |
| MSI           | H110M PRO-VH PLUS           | [533c6216c7](https://linux-hardware.org/?probe=533c6216c7) | Nov 08, 2022 |
| Intel         | H61                         | [67af788bd9](https://linux-hardware.org/?probe=67af788bd9) | Nov 08, 2022 |
| ASRock        | H81M-HG4 R4.0               | [732e924bbb](https://linux-hardware.org/?probe=732e924bbb) | Nov 07, 2022 |
| ASRock        | AB350M                      | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Dell          | 0GDG8Y A02                  | [e61ccb96d0](https://linux-hardware.org/?probe=e61ccb96d0) | Nov 06, 2022 |
| PCWare        | IPMH110G                    | [3409bf9968](https://linux-hardware.org/?probe=3409bf9968) | Nov 06, 2022 |
| Gigabyte      | A320M-HD2-CF                | [185fcc2c4f](https://linux-hardware.org/?probe=185fcc2c4f) | Nov 06, 2022 |
| Gigabyte      | A320M-HD2-CF                | [7d038a7549](https://linux-hardware.org/?probe=7d038a7549) | Nov 06, 2022 |
| Huanan        | X99-F8D PLUS V1.1           | [a552bf9362](https://linux-hardware.org/?probe=a552bf9362) | Nov 06, 2022 |
| MSI           | Z170A SLI PLUS              | [f9b39389e6](https://linux-hardware.org/?probe=f9b39389e6) | Nov 05, 2022 |
| ASRock        | B450M Steel Legend          | [0f6ca0628c](https://linux-hardware.org/?probe=0f6ca0628c) | Nov 05, 2022 |
| VS Company    | MCP61M                      | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [31234e156e](https://linux-hardware.org/?probe=31234e156e) | Nov 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [787df838b7](https://linux-hardware.org/?probe=787df838b7) | Nov 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [0081f15a32](https://linux-hardware.org/?probe=0081f15a32) | Nov 03, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [0f369008f6](https://linux-hardware.org/?probe=0f369008f6) | Nov 03, 2022 |
| ASUSTek       | PRIME Z270-P                | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
| Gigabyte      | H81M-S1                     | [fa134687f2](https://linux-hardware.org/?probe=fa134687f2) | Nov 03, 2022 |
| Lenovo        | NOK                         | [8c9f8ff505](https://linux-hardware.org/?probe=8c9f8ff505) | Nov 03, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [df76e744d7](https://linux-hardware.org/?probe=df76e744d7) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | H61M-P31                    | [819c124b25](https://linux-hardware.org/?probe=819c124b25) | Nov 01, 2022 |
| VS Company    | G31T-M                      | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| Pegatron      | 2AABh                       | [94dd13992c](https://linux-hardware.org/?probe=94dd13992c) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| MSI           | Z97 GAMING 3                | [cc2d45c3ff](https://linux-hardware.org/?probe=cc2d45c3ff) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | [c0926e68a0](https://linux-hardware.org/?probe=c0926e68a0) | Oct 30, 2022 |
| Pegatron      | IPMIP-GS                    | [4e46d903ae](https://linux-hardware.org/?probe=4e46d903ae) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [93d25dfb1f](https://linux-hardware.org/?probe=93d25dfb1f) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [8384c9e137](https://linux-hardware.org/?probe=8384c9e137) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [eb71b41aa8](https://linux-hardware.org/?probe=eb71b41aa8) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [650f1fd648](https://linux-hardware.org/?probe=650f1fd648) | Oct 29, 2022 |
| ASUSTek       | PRIME H410M-K               | [5a371accfe](https://linux-hardware.org/?probe=5a371accfe) | Oct 29, 2022 |
| ASRock        | H510M-HVS                   | [e9ce2f5011](https://linux-hardware.org/?probe=e9ce2f5011) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Intel         | B75                         | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| ASRock        | H510M-HVS                   | [e377db3a9e](https://linux-hardware.org/?probe=e377db3a9e) | Oct 28, 2022 |
| Lenovo        | 3102 NOK                    | [973ebfcf3e](https://linux-hardware.org/?probe=973ebfcf3e) | Oct 27, 2022 |
| ASRock        | H61M-VG4                    | [25b8826346](https://linux-hardware.org/?probe=25b8826346) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Intel         | H55                         | [fb3cf518ac](https://linux-hardware.org/?probe=fb3cf518ac) | Oct 27, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [9285fb0d9d](https://linux-hardware.org/?probe=9285fb0d9d) | Oct 27, 2022 |
| Acer          | Veriton M275                | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| ASUSTek       | P7H57D-V EVO                | [785405287b](https://linux-hardware.org/?probe=785405287b) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| PCWare        | IPMH61R3                    | [9f9410b99d](https://linux-hardware.org/?probe=9f9410b99d) | Oct 25, 2022 |
| Toshiba       | STI 005492G                 | [e7fccc3a84](https://linux-hardware.org/?probe=e7fccc3a84) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Dell          | 01XK1W A00                  | [c0fb49f07a](https://linux-hardware.org/?probe=c0fb49f07a) | Oct 25, 2022 |
| ASRock        | H61M-VG4                    | [b393d57b17](https://linux-hardware.org/?probe=b393d57b17) | Oct 24, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [31cae2266e](https://linux-hardware.org/?probe=31cae2266e) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | [1e80f1de23](https://linux-hardware.org/?probe=1e80f1de23) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4540d714bc](https://linux-hardware.org/?probe=4540d714bc) | Oct 24, 2022 |
| Biostar       | A320MH                      | [b38eca2979](https://linux-hardware.org/?probe=b38eca2979) | Oct 24, 2022 |
| Dell          | 01XK1W A00                  | [86e8f9141a](https://linux-hardware.org/?probe=86e8f9141a) | Oct 24, 2022 |
| ASRock        | H81M-HG4 R4.0               | [da9c01eb20](https://linux-hardware.org/?probe=da9c01eb20) | Oct 23, 2022 |
| Gigabyte      | G41MT-S2P                   | [9d2d49b8e4](https://linux-hardware.org/?probe=9d2d49b8e4) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| Gigabyte      | A520M DS3H                  | [3faf4b3ca9](https://linux-hardware.org/?probe=3faf4b3ca9) | Oct 22, 2022 |
| Philco        | DTC-A55                     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| Huanan        | X99-F8 GAMING V2.0          | [7bc7482286](https://linux-hardware.org/?probe=7bc7482286) | Oct 21, 2022 |
| ASUSTek       | H81M-A/BR                   | [462091e8a8](https://linux-hardware.org/?probe=462091e8a8) | Oct 21, 2022 |
| MSI           | Z97 GAMING 3                | [2b5803628a](https://linux-hardware.org/?probe=2b5803628a) | Oct 20, 2022 |
| MSI           | Z97 GAMING 3                | [94c634f9b8](https://linux-hardware.org/?probe=94c634f9b8) | Oct 20, 2022 |
| Gigabyte      | H87M-D3H                    | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7799fd6266](https://linux-hardware.org/?probe=7799fd6266) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| Dell          | 0YXT71 A02                  | [137e154b2d](https://linux-hardware.org/?probe=137e154b2d) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | [d46ae4e597](https://linux-hardware.org/?probe=d46ae4e597) | Oct 19, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [c395183020](https://linux-hardware.org/?probe=c395183020) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | [e57ed46372](https://linux-hardware.org/?probe=e57ed46372) | Oct 19, 2022 |
| Dell          | 0XJ8C4 A00                  | [83da6e6509](https://linux-hardware.org/?probe=83da6e6509) | Oct 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | [de13cd2a09](https://linux-hardware.org/?probe=de13cd2a09) | Oct 19, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [46a99f3d0e](https://linux-hardware.org/?probe=46a99f3d0e) | Oct 18, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [d9b4d01e7f](https://linux-hardware.org/?probe=d9b4d01e7f) | Oct 18, 2022 |
| ASRock        | X670E Steel Legend          | [2b0983acd6](https://linux-hardware.org/?probe=2b0983acd6) | Oct 18, 2022 |
| ASRock        | B450M Steel Legend          | [6718ea22a9](https://linux-hardware.org/?probe=6718ea22a9) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Dell          | 01XK1W A00                  | [d86b86e8a8](https://linux-hardware.org/?probe=d86b86e8a8) | Oct 17, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| PCWare        | IPMH110G                    | [cde154a026](https://linux-hardware.org/?probe=cde154a026) | Oct 16, 2022 |
| Intel         | H55                         | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Dell          | 09KPNV A01                  | [5261790ba7](https://linux-hardware.org/?probe=5261790ba7) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [b966faf224](https://linux-hardware.org/?probe=b966faf224) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A               | [f13203e3ce](https://linux-hardware.org/?probe=f13203e3ce) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Toshiba       | STI 005492G                 | [e803b9bcf3](https://linux-hardware.org/?probe=e803b9bcf3) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Pegatron      | 2AD2A                       | [01827879c5](https://linux-hardware.org/?probe=01827879c5) | Oct 13, 2022 |
| ASRock        | N68-VS3 FX                  | [b271788734](https://linux-hardware.org/?probe=b271788734) | Oct 12, 2022 |
| Gigabyte      | 945GCM-S2C                  | [d0fe56248f](https://linux-hardware.org/?probe=d0fe56248f) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| PCWare        | IPMH110G                    | [2bcf719742](https://linux-hardware.org/?probe=2bcf719742) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| Unknown       | Unknown                     | [3414f3f4c0](https://linux-hardware.org/?probe=3414f3f4c0) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| Intel         | DH67CL AAG10212-206         | [01ebc77ef1](https://linux-hardware.org/?probe=01ebc77ef1) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | A320M-A PRO MAX             | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [ce045937bc](https://linux-hardware.org/?probe=ce045937bc) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [939e426600](https://linux-hardware.org/?probe=939e426600) | Oct 08, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0085d792fd](https://linux-hardware.org/?probe=0085d792fd) | Oct 07, 2022 |
| MSI           | X370 SLI PLUS               | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Dell          | 09KPNV A01                  | [6ad101df29](https://linux-hardware.org/?probe=6ad101df29) | Oct 06, 2022 |
| MSI           | MEG Z390 GODLIKE            | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| Intel         | B75                         | [a15b4ede9b](https://linux-hardware.org/?probe=a15b4ede9b) | Oct 05, 2022 |
| HP            | 2AA2                        | [e6bc6050b6](https://linux-hardware.org/?probe=e6bc6050b6) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Intel         | X99 V1.0                    | [d96984ac77](https://linux-hardware.org/?probe=d96984ac77) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [16f99421ab](https://linux-hardware.org/?probe=16f99421ab) | Oct 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [9954860560](https://linux-hardware.org/?probe=9954860560) | Oct 04, 2022 |
| Intel         | H55                         | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6209CM1    | [15fb3b5261](https://linux-hardware.org/?probe=15fb3b5261) | Oct 02, 2022 |
| ASUSTek       | A78M-A                      | [91434dfd86](https://linux-hardware.org/?probe=91434dfd86) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [7309d377f6](https://linux-hardware.org/?probe=7309d377f6) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [aedfaab130](https://linux-hardware.org/?probe=aedfaab130) | Oct 02, 2022 |
| Positivo      | POS-PIH81DL                 | [c17fe23ea7](https://linux-hardware.org/?probe=c17fe23ea7) | Oct 01, 2022 |
| ASUSTek       | A78M-A                      | [5ad2e5f2a6](https://linux-hardware.org/?probe=5ad2e5f2a6) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | A320MH                      | [b07b6c4fc5](https://linux-hardware.org/?probe=b07b6c4fc5) | Oct 01, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Intel         | H61                         | [37af3b0cdb](https://linux-hardware.org/?probe=37af3b0cdb) | Sep 30, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [2c08befa41](https://linux-hardware.org/?probe=2c08befa41) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | [5cdce489b9](https://linux-hardware.org/?probe=5cdce489b9) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | [3bfbb3744e](https://linux-hardware.org/?probe=3bfbb3744e) | Sep 30, 2022 |
| ASRock        | A320M-HD                    | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| ASUSTek       | P5K Premium                 | [ec3962c685](https://linux-hardware.org/?probe=ec3962c685) | Sep 28, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | B85M-E/BR                   | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [88f0d42935](https://linux-hardware.org/?probe=88f0d42935) | Sep 27, 2022 |
| Intel         | H55                         | [a155052bce](https://linux-hardware.org/?probe=a155052bce) | Sep 26, 2022 |
| Dell          | 01XK1W A00                  | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| ASUSTek       | P7H55-M LX                  | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Intel         | X99 V1.0                    | [7565f85860](https://linux-hardware.org/?probe=7565f85860) | Sep 24, 2022 |
| Unknown       | WZBTDT1 R110                | [8b6b5af31a](https://linux-hardware.org/?probe=8b6b5af31a) | Sep 24, 2022 |
| Gigabyte      | 970A-DS3P                   | [1e9a7dd793](https://linux-hardware.org/?probe=1e9a7dd793) | Sep 24, 2022 |
| ASUSTek       | M2N68                       | [4b23dadbca](https://linux-hardware.org/?probe=4b23dadbca) | Sep 23, 2022 |
| Foxconn       | Q77M                        | [63d0fe0c57](https://linux-hardware.org/?probe=63d0fe0c57) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASRock        | G31M-S                      | [76d9b33c76](https://linux-hardware.org/?probe=76d9b33c76) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| ASUSTek       | M2N68-AM SE2                | [412f70b76b](https://linux-hardware.org/?probe=412f70b76b) | Sep 23, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [fef79bcff4](https://linux-hardware.org/?probe=fef79bcff4) | Sep 22, 2022 |
| Foxconn       | H61M-S/H61M                 | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| Gigabyte      | 945GM-S2                    | [9fcea940e6](https://linux-hardware.org/?probe=9fcea940e6) | Sep 22, 2022 |
| OEM           | B75 Ver:1.41                | [e22d2bac17](https://linux-hardware.org/?probe=e22d2bac17) | Sep 22, 2022 |
| Intel         | DN2800MT AAG23738-801       | [0019b51cff](https://linux-hardware.org/?probe=0019b51cff) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | [ace83d527c](https://linux-hardware.org/?probe=ace83d527c) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [38234e238c](https://linux-hardware.org/?probe=38234e238c) | Sep 20, 2022 |
| Gigabyte      | B450M DS3H-CF               | [54d0318e27](https://linux-hardware.org/?probe=54d0318e27) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | 0D883F A06                  | [55f97310c8](https://linux-hardware.org/?probe=55f97310c8) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| MSI           | A68HM-E33                   | [2905913e7e](https://linux-hardware.org/?probe=2905913e7e) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| PCWare        | IPMH110G                    | [6ba309be15](https://linux-hardware.org/?probe=6ba309be15) | Sep 18, 2022 |
| ASUSTek       | M4A785-M                    | [411449bc6d](https://linux-hardware.org/?probe=411449bc6d) | Sep 18, 2022 |
| Intel         | H61                         | [923e50e023](https://linux-hardware.org/?probe=923e50e023) | Sep 18, 2022 |
| MSI           | J1800I                      | [ff28c29a3e](https://linux-hardware.org/?probe=ff28c29a3e) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| Intel         | X79M-S                      | [91e75d3183](https://linux-hardware.org/?probe=91e75d3183) | Sep 17, 2022 |
| Intel         | X79M-S                      | [48c5f5ed77](https://linux-hardware.org/?probe=48c5f5ed77) | Sep 17, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Intel         | H61                         | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| Unknown       | Unknown                     | [c292f41bc5](https://linux-hardware.org/?probe=c292f41bc5) | Sep 15, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME B350M-A               | [47b0975057](https://linux-hardware.org/?probe=47b0975057) | Sep 13, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | [70aa78efc6](https://linux-hardware.org/?probe=70aa78efc6) | Sep 13, 2022 |
| Positivo      | POS-PQ45AU                  | [0879f8d9ce](https://linux-hardware.org/?probe=0879f8d9ce) | Sep 13, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| PCWare        | IPMH61R3                    | [2312ab0f92](https://linux-hardware.org/?probe=2312ab0f92) | Sep 12, 2022 |
| Intel         | H61                         | [d805e24841](https://linux-hardware.org/?probe=d805e24841) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [aa4d90c7e7](https://linux-hardware.org/?probe=aa4d90c7e7) | Sep 11, 2022 |
| Dell          | 01XK1W A00                  | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [d79e449b58](https://linux-hardware.org/?probe=d79e449b58) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [1d6ec4fb3b](https://linux-hardware.org/?probe=1d6ec4fb3b) | Sep 10, 2022 |
| Intel         | Unknown                     | [74059aa424](https://linux-hardware.org/?probe=74059aa424) | Sep 10, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8d1d861b1c](https://linux-hardware.org/?probe=8d1d861b1c) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | [944fa39fb6](https://linux-hardware.org/?probe=944fa39fb6) | Sep 09, 2022 |
| Intel         | X79G V2.x                   | [8efdbea978](https://linux-hardware.org/?probe=8efdbea978) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | [c716a6bba5](https://linux-hardware.org/?probe=c716a6bba5) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Intel         | X99                         | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [4942b09228](https://linux-hardware.org/?probe=4942b09228) | Sep 08, 2022 |
| Intel         | D33217CK G76541-301         | [1f1e6e67ab](https://linux-hardware.org/?probe=1f1e6e67ab) | Sep 07, 2022 |
| Biostar       | G41D3C                      | [2825db69bf](https://linux-hardware.org/?probe=2825db69bf) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [f547e07cca](https://linux-hardware.org/?probe=f547e07cca) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [b1bdd1703e](https://linux-hardware.org/?probe=b1bdd1703e) | Sep 06, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f61f170b4c](https://linux-hardware.org/?probe=f61f170b4c) | Sep 06, 2022 |
| Intel         | H61                         | [b2d888f266](https://linux-hardware.org/?probe=b2d888f266) | Sep 05, 2022 |
| ASUSTek       | P5GZ-MX                     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [1f5b368c96](https://linux-hardware.org/?probe=1f5b368c96) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [078680a25d](https://linux-hardware.org/?probe=078680a25d) | Sep 04, 2022 |
| Intel         | DX58SO AAE29331-702         | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Intel         | H61                         | [af78b53f51](https://linux-hardware.org/?probe=af78b53f51) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| ASUSTek       | PRIME Z270-A                | [e742b2e06c](https://linux-hardware.org/?probe=e742b2e06c) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ECS           | H61H2-M2                    | [11dd923e56](https://linux-hardware.org/?probe=11dd923e56) | Sep 02, 2022 |
| Intel         | DP55WB AAE64798-206         | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| MSI           | H97 GAMING 3                | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| AMI           | T3 MRD                      | [d0a254e1b7](https://linux-hardware.org/?probe=d0a254e1b7) | Sep 02, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [9525064f53](https://linux-hardware.org/?probe=9525064f53) | Sep 02, 2022 |
| Lenovo        | 3168 NOK                    | [58c82b01e2](https://linux-hardware.org/?probe=58c82b01e2) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [ea730c9b2d](https://linux-hardware.org/?probe=ea730c9b2d) | Sep 01, 2022 |
| ASRock        | B550M-ITX/ac                | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Gigabyte      | VM900M                      | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a77d5e141e](https://linux-hardware.org/?probe=a77d5e141e) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Supermicro    | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [c7ace10271](https://linux-hardware.org/?probe=c7ace10271) | Aug 28, 2022 |
| Gigabyte      | F2A68HM-S1                  | [420036f4d6](https://linux-hardware.org/?probe=420036f4d6) | Aug 28, 2022 |
| MSI           | B560M PRO-VDH               | [d8a638184b](https://linux-hardware.org/?probe=d8a638184b) | Aug 28, 2022 |
| Intel         | H61                         | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| Gigabyte      | H61M-S1                     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7642980e6e](https://linux-hardware.org/?probe=7642980e6e) | Aug 27, 2022 |
| Dell          | 01XK1W A00                  | [7728612d53](https://linux-hardware.org/?probe=7728612d53) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [ee6cec5f61](https://linux-hardware.org/?probe=ee6cec5f61) | Aug 26, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [da0b51aa63](https://linux-hardware.org/?probe=da0b51aa63) | Aug 25, 2022 |
| MSI           | B560M PRO-VDH               | [437118237f](https://linux-hardware.org/?probe=437118237f) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| OEM           | A320                        | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| Dell          | 01XK1W A00                  | [604a0a7789](https://linux-hardware.org/?probe=604a0a7789) | Aug 25, 2022 |
| HP            | 3397                        | [f65d0fdb85](https://linux-hardware.org/?probe=f65d0fdb85) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [5754d37860](https://linux-hardware.org/?probe=5754d37860) | Aug 23, 2022 |
| AMI           | Cherry Trail Tablet         | [8cdf70d6e3](https://linux-hardware.org/?probe=8cdf70d6e3) | Aug 23, 2022 |
| ASUSTek       | P5KPL-CM                    | [53a4b425d3](https://linux-hardware.org/?probe=53a4b425d3) | Aug 22, 2022 |
| ASUSTek       | PRIME H410M-E               | [5270930555](https://linux-hardware.org/?probe=5270930555) | Aug 22, 2022 |
| Biostar       | A68N-5100                   | [2c6df92279](https://linux-hardware.org/?probe=2c6df92279) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASRock        | X370 Taichi                 | [8f952ff258](https://linux-hardware.org/?probe=8f952ff258) | Aug 21, 2022 |
| Intel         | DH61WW AAG23116-203         | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| Biostar       | G31-M7 TE                   | [aaacebef4a](https://linux-hardware.org/?probe=aaacebef4a) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Gigabyte      | B75M-D3H                    | [6503feb8b7](https://linux-hardware.org/?probe=6503feb8b7) | Aug 20, 2022 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [2e1445b2c8](https://linux-hardware.org/?probe=2e1445b2c8) | Aug 19, 2022 |
| Dell          | 0TVR1F A01                  | [1b8906bb20](https://linux-hardware.org/?probe=1b8906bb20) | Aug 19, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [ffb095f0c3](https://linux-hardware.org/?probe=ffb095f0c3) | Aug 19, 2022 |
| ASUSTek       | B150M-C/BR                  | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Arquimedes... | 760GM                       | [5f653afdff](https://linux-hardware.org/?probe=5f653afdff) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4242f8b9c2](https://linux-hardware.org/?probe=4242f8b9c2) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [bac870dd75](https://linux-hardware.org/?probe=bac870dd75) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [52b9313de4](https://linux-hardware.org/?probe=52b9313de4) | Aug 18, 2022 |
| Intel         | Unknown                     | [23f3bdae8a](https://linux-hardware.org/?probe=23f3bdae8a) | Aug 18, 2022 |
| HP            | 2215                        | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| ASRock        | AB350M-HDV                  | [3e3ab3842f](https://linux-hardware.org/?probe=3e3ab3842f) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Intel         | B75                         | [8eb918ea53](https://linux-hardware.org/?probe=8eb918ea53) | Aug 16, 2022 |
| Gigabyte      | B550M DS3H                  | [6ef5e022c7](https://linux-hardware.org/?probe=6ef5e022c7) | Aug 15, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| ASRock        | B450M Steel Legend          | [1e198f7c54](https://linux-hardware.org/?probe=1e198f7c54) | Aug 15, 2022 |
| ASRock        | FM2A55M-HD+                 | [dc086ed32c](https://linux-hardware.org/?probe=dc086ed32c) | Aug 14, 2022 |
| ASUSTek       | P8H61-M LX3                 | [7c37c2a6d7](https://linux-hardware.org/?probe=7c37c2a6d7) | Aug 14, 2022 |
| ASRock        | FM2A55M-HD+                 | [6c7f56d3cd](https://linux-hardware.org/?probe=6c7f56d3cd) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | [4443a6c129](https://linux-hardware.org/?probe=4443a6c129) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | [082a5297bd](https://linux-hardware.org/?probe=082a5297bd) | Aug 14, 2022 |
| Gigabyte      | Z77M-D3H                    | [15633ed7b1](https://linux-hardware.org/?probe=15633ed7b1) | Aug 14, 2022 |
| Biostar       | G31-M7 TE                   | [c5737e52bd](https://linux-hardware.org/?probe=c5737e52bd) | Aug 14, 2022 |
| ASUSTek       | Z97-A                       | [14fa58515f](https://linux-hardware.org/?probe=14fa58515f) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [f17b91fcb8](https://linux-hardware.org/?probe=f17b91fcb8) | Aug 13, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [98cc4a3075](https://linux-hardware.org/?probe=98cc4a3075) | Aug 12, 2022 |
| Gigabyte      | H61M-S1                     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| MSI           | X370 SLI PLUS               | [8b4bc6f127](https://linux-hardware.org/?probe=8b4bc6f127) | Aug 11, 2022 |
| Foxconn       | 2ADA                        | [9aae49b54c](https://linux-hardware.org/?probe=9aae49b54c) | Aug 11, 2022 |
| Gigabyte      | G31M-S2C                    | [3f67c470be](https://linux-hardware.org/?probe=3f67c470be) | Aug 11, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [c66de39c4c](https://linux-hardware.org/?probe=c66de39c4c) | Aug 11, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [d081204e0a](https://linux-hardware.org/?probe=d081204e0a) | Aug 10, 2022 |
| Foxconn       | 2ABF                        | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e54e09e3cf](https://linux-hardware.org/?probe=e54e09e3cf) | Aug 09, 2022 |
| ASUSTek       | H81M-CS/BR                  | [8c2dc32c37](https://linux-hardware.org/?probe=8c2dc32c37) | Aug 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a84fd5a16](https://linux-hardware.org/?probe=5a84fd5a16) | Aug 09, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [b66253f362](https://linux-hardware.org/?probe=b66253f362) | Aug 09, 2022 |
| Intel         | H61                         | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [aada9001dd](https://linux-hardware.org/?probe=aada9001dd) | Aug 08, 2022 |
| HP            | 1998                        | [1ae818eb7c](https://linux-hardware.org/?probe=1ae818eb7c) | Aug 07, 2022 |
| Toshiba       | STI 006998G                 | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| PCWare        | IPX3060E                    | [3fc0886f3b](https://linux-hardware.org/?probe=3fc0886f3b) | Aug 06, 2022 |
| Gigabyte      | F2A55M-S1                   | [cf3ed2131f](https://linux-hardware.org/?probe=cf3ed2131f) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 566      | 11.74%  |
| Ubuntu 18.04                 | 408      | 8.46%   |
| OpenMandriva 4.2             | 172      | 3.57%   |
| Ubuntu 22.04                 | 141      | 2.92%   |
| OpenMandriva 4.3             | 131      | 2.72%   |
| Linux Mint 20                | 119      | 2.47%   |
| Linux Mint 19.3              | 115      | 2.39%   |
| Pop!_OS 20.04                | 114      | 2.36%   |
| Linux Mint 19.1              | 110      | 2.28%   |
| KDE neon 20.04               | 97       | 2.01%   |
| Ubuntu 19.04                 | 95       | 1.97%   |
| Linux Mint 20.1              | 87       | 1.8%    |
| Zorin 16                     | 77       | 1.6%    |
| Linux Mint 20.3              | 73       | 1.51%   |
| Manjaro                      | 69       | 1.43%   |
| Arch                         | 69       | 1.43%   |
| Linux Mint 20.2              | 65       | 1.35%   |
| Debian 11                    | 63       | 1.31%   |
| Pop!_OS 20.10                | 61       | 1.27%   |
| Debian 10                    | 61       | 1.27%   |
| Arch Rolling                 | 60       | 1.24%   |
| Ubuntu MATE 20.04            | 58       | 1.2%    |
| Ubuntu 19.10                 | 58       | 1.2%    |
| Pop!_OS 21.04                | 57       | 1.18%   |
| Zorin 15                     | 54       | 1.12%   |
| Pop!_OS 22.04                | 53       | 1.1%    |
| OpenMandriva 23.01           | 50       | 1.04%   |
| Fedora 36                    | 49       | 1.02%   |
| Linux Mint 19.2              | 48       | 1%      |
| Xubuntu 20.04                | 44       | 0.91%   |
| Linux Mint 21                | 43       | 0.89%   |
| Fedora 34                    | 43       | 0.89%   |
| Fedora 37                    | 42       | 0.87%   |
| Fedora 32                    | 39       | 0.81%   |
| Fedora 33                    | 38       | 0.79%   |
| Ubuntu 18.10                 | 36       | 0.75%   |
| Kubuntu 20.04                | 36       | 0.75%   |
| Ubuntu 20.10                 | 35       | 0.73%   |
| Xubuntu 18.04                | 33       | 0.68%   |
| openSUSE Tumbleweed-XXXXXXXX | 32       | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1395     | 30.33%  |
| Linux Mint    | 680      | 14.79%  |
| OpenMandriva  | 381      | 8.28%   |
| Pop!_OS       | 302      | 6.57%   |
| Fedora        | 246      | 5.35%   |
| Debian        | 170      | 3.7%    |
| Endless       | 163      | 3.54%   |
| Manjaro       | 146      | 3.17%   |
| Zorin         | 136      | 2.96%   |
| Arch          | 126      | 2.74%   |
| KDE neon      | 115      | 2.5%    |
| Xubuntu       | 96       | 2.09%   |
| Kubuntu       | 83       | 1.8%    |
| ROSA          | 73       | 1.59%   |
| Ubuntu MATE   | 71       | 1.54%   |
| openSUSE      | 49       | 1.07%   |
| Ubuntu Unity  | 32       | 0.7%    |
| Lubuntu       | 31       | 0.67%   |
| Elementary    | 29       | 0.63%   |
| LMDE          | 25       | 0.54%   |
| ArcoLinux     | 21       | 0.46%   |
| LinuxFX       | 16       | 0.35%   |
| CentOS        | 16       | 0.35%   |
| BlackPanther  | 16       | 0.35%   |
| Kali          | 15       | 0.33%   |
| Deepin        | 15       | 0.33%   |
| BigLinux      | 12       | 0.26%   |
| Ubuntu Budgie | 11       | 0.24%   |
| Gentoo        | 9        | 0.2%    |
| Clear Linux   | 9        | 0.2%    |
| Linux Lite    | 7        | 0.15%   |
| Peppermint    | 6        | 0.13%   |
| Parrot        | 6        | 0.13%   |
| MX            | 6        | 0.13%   |
| EndeavourOS   | 6        | 0.13%   |
| Ubuntu Studio | 5        | 0.11%   |
| Solus         | 5        | 0.11%   |
| Nobara        | 5        | 0.11%   |
| Garuda Linux  | 5        | 0.11%   |
| UbuntuDDE     | 4        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 229      | 4.39%   |
| 5.10.14-desktop-1omv4002 | 167      | 3.2%    |
| 5.16.7-desktop-1omv4003  | 122      | 2.34%   |
| 4.15.0-46-generic        | 84       | 1.61%   |
| 5.4.0-48-generic         | 65       | 1.25%   |
| 4.18.0-15-generic        | 49       | 0.94%   |
| 5.4.0-7634-generic       | 48       | 0.92%   |
| 5.4.0-58-generic         | 45       | 0.86%   |
| 6.1.1-desktop-1omv2290   | 44       | 0.84%   |
| 5.4.0-52-generic         | 43       | 0.82%   |
| 5.3.0-40-generic         | 43       | 0.82%   |
| 5.4.0-40-generic         | 41       | 0.79%   |
| 5.4.0-47-generic         | 40       | 0.77%   |
| 5.11.0-7620-generic      | 37       | 0.71%   |
| 5.3.0-28-generic         | 36       | 0.69%   |
| 5.4.0-26-generic         | 35       | 0.67%   |
| 4.15.0-20-generic        | 33       | 0.63%   |
| 5.4.0-70-generic         | 32       | 0.61%   |
| 5.4.0-72-generic         | 31       | 0.59%   |
| 5.15.0-56-generic        | 30       | 0.58%   |
| 5.0.0-32-generic         | 30       | 0.58%   |
| 5.3.0-46-generic         | 28       | 0.54%   |
| 5.0.0-37-generic         | 28       | 0.54%   |
| 5.8.0-7630-generic       | 27       | 0.52%   |
| 5.4.0-91-generic         | 27       | 0.52%   |
| 5.4.0-33-generic         | 27       | 0.52%   |
| 4.15.0-54-generic        | 27       | 0.52%   |
| 5.15.0-46-generic        | 25       | 0.48%   |
| 5.15.0-52-generic        | 24       | 0.46%   |
| 5.11.0-37-generic        | 24       | 0.46%   |
| 5.8.0-59-generic         | 23       | 0.44%   |
| 5.8.0-14-generic         | 23       | 0.44%   |
| 5.4.0-74-generic         | 23       | 0.44%   |
| 5.4.0-66-generic         | 23       | 0.44%   |
| 5.4.0-54-generic         | 23       | 0.44%   |
| 5.4.0-37-generic         | 23       | 0.44%   |
| 5.15.0-41-generic        | 23       | 0.44%   |
| 5.11.0-27-generic        | 23       | 0.44%   |
| 5.0.0-13-generic         | 23       | 0.44%   |
| 4.18.0-16-generic        | 23       | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 1121     | 22.8%   |
| 4.15.0  | 415      | 8.44%   |
| 5.15.0  | 281      | 5.71%   |
| 5.8.0   | 258      | 5.25%   |
| 5.11.0  | 250      | 5.08%   |
| 5.3.0   | 244      | 4.96%   |
| 5.0.0   | 231      | 4.7%    |
| 5.13.0  | 174      | 3.54%   |
| 4.18.0  | 173      | 3.52%   |
| 5.10.14 | 167      | 3.4%    |
| 5.16.7  | 122      | 2.48%   |
| 5.10.0  | 85       | 1.73%   |
| 4.19.0  | 74       | 1.5%    |
| 5.19.0  | 68       | 1.38%   |
| 6.1.1   | 47       | 0.96%   |
| 5.7.9   | 21       | 0.43%   |
| 5.17.5  | 21       | 0.43%   |
| 4.4.0   | 19       | 0.39%   |
| 4.9.0   | 18       | 0.37%   |
| 4.9.60  | 15       | 0.31%   |
| 6.0.12  | 14       | 0.28%   |
| 5.13.19 | 14       | 0.28%   |
| 6.2.6   | 13       | 0.26%   |
| 5.7.0   | 13       | 0.26%   |
| 5.18.12 | 13       | 0.26%   |
| 6.0.10  | 12       | 0.24%   |
| 5.17.15 | 12       | 0.24%   |
| 5.15.5  | 12       | 0.24%   |
| 4.18.16 | 12       | 0.24%   |
| 6.0.7   | 11       | 0.22%   |
| 5.16.11 | 11       | 0.22%   |
| 5.16.0  | 11       | 0.22%   |
| 5.14.0  | 11       | 0.22%   |
| 5.12.4  | 11       | 0.22%   |
| 4.9.20  | 11       | 0.22%   |
| 5.6.19  | 10       | 0.2%    |
| 5.16.13 | 10       | 0.2%    |
| 6.1.12  | 9        | 0.18%   |
| 5.7.10  | 9        | 0.18%   |
| 5.6.15  | 9        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 1168     | 24.05%  |
| 4.15    | 415      | 8.54%   |
| 5.15    | 362      | 7.45%   |
| 5.10    | 331      | 6.81%   |
| 5.8     | 300      | 6.18%   |
| 5.11    | 277      | 5.7%    |
| 5.3     | 264      | 5.44%   |
| 5.0     | 245      | 5.04%   |
| 5.13    | 207      | 4.26%   |
| 4.18    | 189      | 3.89%   |
| 5.16    | 177      | 3.64%   |
| 5.19    | 116      | 2.39%   |
| 6.1     | 99       | 2.04%   |
| 4.19    | 90       | 1.85%   |
| 6.0     | 77       | 1.59%   |
| 5.7     | 70       | 1.44%   |
| 5.18    | 57       | 1.17%   |
| 4.9     | 56       | 1.15%   |
| 5.17    | 53       | 1.09%   |
| 5.6     | 52       | 1.07%   |
| 5.12    | 49       | 1.01%   |
| 5.14    | 41       | 0.84%   |
| 5.9     | 35       | 0.72%   |
| 6.2     | 29       | 0.6%    |
| 4.4     | 19       | 0.39%   |
| 5.5     | 16       | 0.33%   |
| 5.2     | 13       | 0.27%   |
| 5.1     | 11       | 0.23%   |
| 4.1     | 8        | 0.16%   |
| 3.10    | 8        | 0.16%   |
| 4.13    | 6        | 0.12%   |
| 4.20    | 5        | 0.1%    |
| 4.12    | 5        | 0.1%    |
| 4.10    | 4        | 0.08%   |
| 4.8     | 2        | 0.04%   |
| 4.14    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 4290     | 97.17%  |
| i686   | 125      | 2.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 1816     | 39.24%  |
| Unknown                  | 772      | 16.68%  |
| KDE5                     | 697      | 15.06%  |
| X-Cinnamon               | 402      | 8.69%   |
| XFCE                     | 331      | 7.15%   |
| MATE                     | 158      | 3.41%   |
| KDE                      | 140      | 3.03%   |
| Cinnamon                 | 84       | 1.82%   |
| KDE4                     | 38       | 0.82%   |
| Unity                    | 33       | 0.71%   |
| LXQt                     | 29       | 0.63%   |
| Pantheon                 | 25       | 0.54%   |
| Budgie                   | 20       | 0.43%   |
| Deepin                   | 18       | 0.39%   |
| LXDE                     | 16       | 0.35%   |
| GNOME Flashback          | 13       | 0.28%   |
| i3                       | 11       | 0.24%   |
| awesome                  | 5        | 0.11%   |
| GNOME Classic            | 4        | 0.09%   |
| openbox                  | 3        | 0.06%   |
| Enlightenment            | 3        | 0.06%   |
| sway                     | 2        | 0.04%   |
| qtile                    | 2        | 0.04%   |
| bspwm                    | 2        | 0.04%   |
| icewm                    | 1        | 0.02%   |
| Hyprland                 | 1        | 0.02%   |
| 03WindowMaker            | 1        | 0.02%   |
| /usr/bin/openbox-session | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3706     | 82.25%  |
| Wayland | 406      | 9.01%   |
| Unknown | 358      | 7.94%   |
| Tty     | 34       | 0.75%   |
| Web     | 2        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2759     | 60.72%  |
| SDDM    | 600      | 13.2%   |
| GDM     | 418      | 9.2%    |
| GDM3    | 252      | 5.55%   |
| TDM     | 236      | 5.19%   |
| LightDM | 231      | 5.08%   |
| KDM     | 39       | 0.86%   |
| XDM     | 4        | 0.09%   |
| SLiM    | 2        | 0.04%   |
| SLIMSKI | 1        | 0.02%   |
| MDM     | 1        | 0.02%   |
| LXDM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| pt_BR       | 2937     | 65.04%  |
| Unknown     | 749      | 16.59%  |
| en_US       | 724      | 16.03%  |
| C           | 58       | 1.28%   |
| pt_PT       | 15       | 0.33%   |
| en_GB       | 15       | 0.33%   |
| es_ES       | 6        | 0.13%   |
| en_CA       | 4        | 0.09%   |
| en_AG       | 2        | 0.04%   |
| pt_BRutf8   | 1        | 0.02%   |
| eo          | 1        | 0.02%   |
| en_US.utf-8 | 1        | 0.02%   |
| en_IN       | 1        | 0.02%   |
| de_DE       | 1        | 0.02%   |
| C.UTF8      | 1        | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3099     | 68.73%  |
| EFI  | 1410     | 31.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3382     | 74.77%  |
| Overlay | 444      | 9.82%   |
| Btrfs   | 305      | 6.74%   |
| Unknown | 304      | 6.72%   |
| Xfs     | 37       | 0.82%   |
| Zfs     | 19       | 0.42%   |
| Ext3    | 8        | 0.18%   |
| Ext2    | 8        | 0.18%   |
| Tmpfs   | 7        | 0.15%   |
| F2fs    | 7        | 0.15%   |
| Aufs    | 2        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2904     | 64.28%  |
| GPT     | 959      | 21.23%  |
| MBR     | 655      | 14.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3818     | 84.66%  |
| Yes       | 692      | 15.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3042     | 67.54%  |
| Yes       | 1462     | 32.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1165     | 26.41%  |
| Gigabyte Technology | 760      | 17.23%  |
| ASRock              | 383      | 8.68%   |
| Intel               | 356      | 8.07%   |
| Dell                | 254      | 5.76%   |
| MSI                 | 189      | 4.28%   |
| Positivo            | 188      | 4.26%   |
| Unknown             | 146      | 3.31%   |
| Hewlett-Packard     | 138      | 3.13%   |
| PCWare              | 109      | 2.47%   |
| Biostar             | 85       | 1.93%   |
| Lenovo              | 80       | 1.81%   |
| Pegatron            | 67       | 1.52%   |
| ECS                 | 61       | 1.38%   |
| Semp Toshiba        | 43       | 0.97%   |
| Itautec             | 39       | 0.88%   |
| Huanan              | 30       | 0.68%   |
| Megaware            | 27       | 0.61%   |
| Foxconn             | 27       | 0.61%   |
| OEM                 | 18       | 0.41%   |
| Login Informatica   | 16       | 0.36%   |
| Qbex                | 12       | 0.27%   |
| MACHINIST           | 12       | 0.27%   |
| AMD                 | 12       | 0.27%   |
| VS Company          | 10       | 0.23%   |
| PCChips             | 10       | 0.23%   |
| Digiboard           | 10       | 0.23%   |
| Supermicro          | 9        | 0.2%    |
| Philco              | 9        | 0.2%    |
| Digitron            | 8        | 0.18%   |
| Colorful Technology | 7        | 0.16%   |
| Phitronics          | 6        | 0.14%   |
| INTELBRAS           | 6        | 0.14%   |
| CCE                 | 6        | 0.14%   |
| IBM                 | 5        | 0.11%   |
| Daten Tecnologia    | 5        | 0.11%   |
| Centrium            | 5        | 0.11%   |
| AMI                 | 5        | 0.11%   |
| MEGA                | 4        | 0.09%   |
| Kllisre             | 4        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 162      | 3.67%   |
| ASUS All Series               | 143      | 3.24%   |
| Intel H61                     | 78       | 1.77%   |
| ASUS PRIME B450M-GAMING/BR    | 59       | 1.34%   |
| ASRock A320M-HD               | 50       | 1.13%   |
| ASUS PRIME A320M-K/BR         | 49       | 1.11%   |
| ASUS M5A78L-M LX/BR           | 47       | 1.07%   |
| Intel H55                     | 44       | 1%      |
| Semp Toshiba STI              | 42       | 0.95%   |
| Gigabyte H61M-S1              | 38       | 0.86%   |
| Gigabyte A320M-S2H            | 35       | 0.79%   |
| Gigabyte B75M-D3H             | 33       | 0.75%   |
| ASRock B450M Steel Legend     | 33       | 0.75%   |
| ASUS P8H61-M LX3 R2.0         | 32       | 0.73%   |
| ASUS M5A78L-M PLUS/USB3       | 30       | 0.68%   |
| ASRock N68-S3 FX              | 28       | 0.63%   |
| ASUS H61M-A/BR                | 25       | 0.57%   |
| ASUS TUF Gaming X570-PLUS_BR  | 24       | 0.54%   |
| ASUS M5A78L-M/USB3            | 24       | 0.54%   |
| Gigabyte B450M DS3H           | 23       | 0.52%   |
| Gigabyte AB350M-DS3H V2       | 22       | 0.5%    |
| ASUS P8H61-M LX2 R2.0         | 22       | 0.5%    |
| Intel B75                     | 21       | 0.48%   |
| ASUS P5G41T-M LX2/BR          | 21       | 0.48%   |
| Intel MAHOBAY                 | 20       | 0.45%   |
| Positivo POS-EIH61CE          | 19       | 0.43%   |
| Gigabyte 970A-DS3P            | 19       | 0.43%   |
| ASUS M4N68T-M LE              | 19       | 0.43%   |
| HP Compaq 6005 Pro SFF PC     | 18       | 0.41%   |
| ASUS TUF B360M-PLUS GAMING/BR | 18       | 0.41%   |
| Gigabyte G31M-ES2C            | 17       | 0.39%   |
| Gigabyte 945GCM-S2C           | 17       | 0.39%   |
| Dell XPS 8700                 | 17       | 0.39%   |
| Gigabyte M68MT-S2P            | 16       | 0.36%   |
| ASUS PRIME H310M-E R2.0/BR    | 16       | 0.36%   |
| Pegatron IPM41-D3             | 15       | 0.34%   |
| MSI MS-7788                   | 15       | 0.34%   |
| Gigabyte GA-78LMT-USB3 6.0    | 15       | 0.34%   |
| Gigabyte B450 AORUS M         | 15       | 0.34%   |
| Biostar A320MH                | 15       | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 225      | 5.1%    |
| Unknown                | 162      | 3.67%   |
| Dell OptiPlex          | 150      | 3.4%    |
| ASUS All               | 143      | 3.24%   |
| ASUS M5A78L-M          | 117      | 2.65%   |
| ASUS TUF               | 101      | 2.29%   |
| ASUS P8H61-M           | 82       | 1.86%   |
| Intel H61              | 81       | 1.84%   |
| HP Compaq              | 69       | 1.56%   |
| Lenovo ThinkCentre     | 55       | 1.25%   |
| ASRock A320M-HD        | 51       | 1.16%   |
| ASUS ROG               | 47       | 1.07%   |
| Intel H55              | 44       | 1%      |
| Semp Toshiba STI       | 43       | 0.97%   |
| Gigabyte H61M-S1       | 38       | 0.86%   |
| Gigabyte A320M-S2H     | 35       | 0.79%   |
| ASRock B450M           | 35       | 0.79%   |
| Itautec Infoway        | 33       | 0.75%   |
| Gigabyte B75M-D3H      | 33       | 0.75%   |
| Gigabyte B450M         | 33       | 0.75%   |
| ASRock N68-S3          | 29       | 0.66%   |
| Dell XPS               | 28       | 0.63%   |
| Gigabyte GA-78LMT-USB3 | 27       | 0.61%   |
| Dell Precision         | 27       | 0.61%   |
| HP EliteDesk           | 26       | 0.59%   |
| Dell Inspiron          | 26       | 0.59%   |
| ASUS H61M-A            | 25       | 0.57%   |
| Intel B75              | 24       | 0.54%   |
| Gigabyte B450          | 24       | 0.54%   |
| ASUS P5G41T-M          | 24       | 0.54%   |
| Gigabyte AB350M-DS3H   | 22       | 0.5%    |
| Intel X99              | 21       | 0.48%   |
| Intel MAHOBAY          | 20       | 0.45%   |
| Gigabyte 970A-DS3P     | 20       | 0.45%   |
| Positivo POS-EIH61CE   | 19       | 0.43%   |
| ASUS M5A97             | 19       | 0.43%   |
| ASUS M4N68T-M          | 19       | 0.43%   |
| ASRock N68-GS4         | 19       | 0.43%   |
| Dell Vostro            | 18       | 0.41%   |
| ASUS P5GC-MX           | 18       | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 473      | 10.72%  |
| 2011    | 460      | 10.43%  |
| 2012    | 453      | 10.27%  |
| 2017    | 379      | 8.59%   |
| 2013    | 341      | 7.73%   |
| 2010    | 312      | 7.07%   |
| 2014    | 306      | 6.94%   |
| 2009    | 281      | 6.37%   |
| 2019    | 278      | 6.3%    |
| 2008    | 230      | 5.21%   |
| 2016    | 198      | 4.49%   |
| 2020    | 195      | 4.42%   |
| 2007    | 186      | 4.22%   |
| 2015    | 110      | 2.49%   |
| 2021    | 87       | 1.97%   |
| 2006    | 60       | 1.36%   |
| 2022    | 32       | 0.73%   |
| 2005    | 17       | 0.39%   |
| Unknown | 7        | 0.16%   |
| 2004    | 5        | 0.11%   |
| 2003    | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4411     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4336     | 97.99%  |
| Enabled  | 89       | 2.01%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4411     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 1074     | 23.81%  |
| 8.01-16.0       | 1036     | 22.97%  |
| 16.01-24.0      | 871      | 19.31%  |
| 4.01-8.0        | 821      | 18.2%   |
| 1.01-2.0        | 251      | 5.56%   |
| 32.01-64.0      | 238      | 5.28%   |
| 2.01-3.0        | 84       | 1.86%   |
| 24.01-32.0      | 63       | 1.4%    |
| 64.01-256.0     | 50       | 1.11%   |
| 0.51-1.0        | 19       | 0.42%   |
| Unknown         | 2        | 0.04%   |
| More than 256.0 | 1        | 0.02%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1854     | 38.02%  |
| 2.01-3.0   | 1247     | 25.57%  |
| 4.01-8.0   | 578      | 11.85%  |
| 3.01-4.0   | 569      | 11.67%  |
| 0.51-1.0   | 428      | 8.78%   |
| 8.01-16.0  | 112      | 2.3%    |
| 0.01-0.5   | 64       | 1.31%   |
| 16.01-24.0 | 16       | 0.33%   |
| 24.01-32.0 | 5        | 0.1%    |
| Unknown    | 2        | 0.04%   |
| 32.01-64.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2268     | 49.42%  |
| 2       | 1297     | 28.26%  |
| 3       | 556      | 12.12%  |
| 4       | 262      | 5.71%   |
| 5       | 81       | 1.77%   |
| 0       | 57       | 1.24%   |
| 6       | 47       | 1.02%   |
| 7       | 10       | 0.22%   |
| 8       | 7        | 0.15%   |
| 9       | 3        | 0.07%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2757     | 61.75%  |
| Yes       | 1708     | 38.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4338     | 98.32%  |
| No        | 74       | 1.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2889     | 64.57%  |
| Yes       | 1585     | 35.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3713     | 83.33%  |
| Yes       | 743      | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 4411     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Sao Paulo             | 611      | 13.27%  |
| Rio de Janeiro        | 301      | 6.54%   |
| Brasília             | 128      | 2.78%   |
| Belo Horizonte        | 128      | 2.78%   |
| Curitiba              | 107      | 2.32%   |
| Porto Alegre          | 105      | 2.28%   |
| Fortaleza             | 79       | 1.72%   |
| Campinas              | 67       | 1.46%   |
| Salvador              | 60       | 1.3%    |
| Recife                | 55       | 1.19%   |
| Goiânia              | 51       | 1.11%   |
| Santo André          | 50       | 1.09%   |
| Florianópolis        | 46       | 1%      |
| Guarulhos             | 43       | 0.93%   |
| Niterói              | 39       | 0.85%   |
| Manaus                | 37       | 0.8%    |
| Osasco                | 32       | 0.7%    |
| Sorocaba              | 31       | 0.67%   |
| Sao José dos Campos  | 30       | 0.65%   |
| Maringá              | 30       | 0.65%   |
| Londrina              | 30       | 0.65%   |
| Juiz de Fora          | 30       | 0.65%   |
| Serra                 | 28       | 0.61%   |
| Natal                 | 28       | 0.61%   |
| Campo Grande          | 28       | 0.61%   |
| Duque de Caxias       | 27       | 0.59%   |
| Belém                | 26       | 0.56%   |
| Joinville             | 25       | 0.54%   |
| Blumenau              | 23       | 0.5%    |
| Sao Goncalo           | 21       | 0.46%   |
| Ribeirao Preto        | 21       | 0.46%   |
| Maceió               | 21       | 0.46%   |
| Uberlândia           | 20       | 0.43%   |
| Palmas                | 20       | 0.43%   |
| Teresina              | 19       | 0.41%   |
| Sao Bernardo do Campo | 19       | 0.41%   |
| Joao Pessoa           | 19       | 0.41%   |
| Sao Luís             | 18       | 0.39%   |
| Sao Jose              | 18       | 0.39%   |
| Cuiabá               | 18       | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 1774     | 2677   | 24.8%   |
| WDC                       | 1343     | 1840   | 18.78%  |
| Samsung Electronics       | 958      | 1388   | 13.39%  |
| Kingston                  | 803      | 1097   | 11.23%  |
| SanDisk                   | 316      | 447    | 4.42%   |
| Toshiba                   | 315      | 372    | 4.4%    |
| China                     | 188      | 216    | 2.63%   |
| Hitachi                   | 180      | 217    | 2.52%   |
| Crucial                   | 132      | 165    | 1.85%   |
| Maxtor                    | 115      | 135    | 1.61%   |
| A-DATA Technology         | 96       | 115    | 1.34%   |
| Silicon Motion            | 93       | 126    | 1.3%    |
| Lexar                     | 56       | 60     | 0.78%   |
| Realtek Semiconductor     | 50       | 60     | 0.7%    |
| Unknown                   | 46       | 65     | 0.64%   |
| KingSpec                  | 45       | 52     | 0.63%   |
| XPG                       | 42       | 52     | 0.59%   |
| Intel                     | 35       | 40     | 0.49%   |
| Corsair                   | 35       | 47     | 0.49%   |
| Phison                    | 33       | 51     | 0.46%   |
| HGST                      | 31       | 36     | 0.43%   |
| Hewlett-Packard           | 27       | 32     | 0.38%   |
| XrayDisk                  | 23       | 29     | 0.32%   |
| Patriot                   | 23       | 35     | 0.32%   |
| PNY                       | 22       | 23     | 0.31%   |
| Netac                     | 22       | 32     | 0.31%   |
| JMicron Technology        | 22       | 24     | 0.31%   |
| Gigabyte Technology       | 19       | 27     | 0.27%   |
| LITEON                    | 15       | 15     | 0.21%   |
| KingDian                  | 14       | 15     | 0.2%    |
| OCZ                       | 12       | 13     | 0.17%   |
| Fujitsu                   | 12       | 13     | 0.17%   |
| Unknown                   | 11       | 11     | 0.15%   |
| SK hynix                  | 10       | 25     | 0.14%   |
| Phison Electronics        | 10       | 13     | 0.14%   |
| ExcelStor                 | 10       | 11     | 0.14%   |
| ADATA Technology          | 10       | 14     | 0.14%   |
| WALRAM                    | 9        | 9      | 0.13%   |
| Smart                     | 9        | 11     | 0.13%   |
| Micron/Crucial Technology | 9        | 13     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD     | 270      | 3.39%   |
| Seagate ST500DM002-1BD142 500GB     | 245      | 3.08%   |
| Seagate ST1000DM010-2EP102 1TB      | 205      | 2.58%   |
| Kingston SA400S37120G 120GB SSD     | 161      | 2.02%   |
| Kingston SA400S37480G 480GB SSD     | 122      | 1.53%   |
| Samsung HD322HJ 320GB               | 118      | 1.48%   |
| Samsung HD161HJ 160GB               | 100      | 1.26%   |
| Samsung HD502HJ 500GB               | 99       | 1.24%   |
| Samsung HD502HI 500GB               | 96       | 1.21%   |
| Seagate ST1000DM003-1ER162 1TB      | 94       | 1.18%   |
| Seagate ST1000DM003-1CH162 1TB      | 87       | 1.09%   |
| Kingston SV300S37A120G 120GB SSD    | 81       | 1.02%   |
| WDC WD5000AAKX-003CA0 500GB         | 77       | 0.97%   |
| WDC WD10EARS-00Y5B1 1TB             | 68       | 0.85%   |
| Seagate ST3500418AS 500GB           | 66       | 0.83%   |
| SanDisk SSD PLUS 240GB              | 65       | 0.82%   |
| Seagate ST3500312CS 500GB           | 62       | 0.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 60       | 0.75%   |
| Seagate Expansion+ 2TB              | 58       | 0.73%   |
| Seagate ST31000524AS 1TB            | 57       | 0.72%   |
| WDC WD10EZEX-00BN5A0 1TB            | 56       | 0.7%    |
| WDC WD10EZEX-00WN4A0 1TB            | 55       | 0.69%   |
| Toshiba DT01ACA050 500GB            | 55       | 0.69%   |
| Seagate ST2000DM006-2DM164 2TB      | 55       | 0.69%   |
| Crucial CT240BX500SSD1 240GB        | 53       | 0.67%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 51       | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 50       | 0.63%   |
| Toshiba HDWD110 1TB                 | 50       | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 48       | 0.6%    |
| Seagate ST3320418AS 320GB           | 47       | 0.59%   |
| SanDisk SDSSDA120G 120GB            | 46       | 0.58%   |
| Samsung HD103SI 1TB                 | 45       | 0.57%   |
| Samsung HD161GJ 160GB               | 43       | 0.54%   |
| Seagate ST3500413AS 500GB           | 42       | 0.53%   |
| Seagate ST31000528AS 1TB            | 42       | 0.53%   |
| SanDisk SDSSDA240G 240GB            | 42       | 0.53%   |
| Samsung HD103SJ 1TB                 | 42       | 0.53%   |
| SanDisk SSD PLUS 120GB              | 41       | 0.52%   |
| Toshiba DT01ACA100 1TB              | 39       | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB      | 38       | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1769     | 2660   | 39.52%  |
| WDC                 | 1197     | 1621   | 26.74%  |
| Samsung Electronics | 819      | 1117   | 18.3%   |
| Toshiba             | 302      | 356    | 6.75%   |
| Hitachi             | 180      | 217    | 4.02%   |
| Maxtor              | 110      | 129    | 2.46%   |
| HGST                | 31       | 36     | 0.69%   |
| Hewlett-Packard     | 16       | 18     | 0.36%   |
| Fujitsu             | 12       | 13     | 0.27%   |
| Unknown             | 10       | 10     | 0.22%   |
| ExcelStor           | 10       | 11     | 0.22%   |
| HPE                 | 4        | 4      | 0.09%   |
| USB3.0              | 2        | 2      | 0.04%   |
| JMicron Technology  | 2        | 3      | 0.04%   |
| ASMT                | 2        | 2      | 0.04%   |
| SAGE                | 1        | 2      | 0.02%   |
| SABRENT             | 1        | 1      | 0.02%   |
| MDT                 | 1        | 1      | 0.02%   |
| Lenovo              | 1        | 1      | 0.02%   |
| IBM                 | 1        | 3      | 0.02%   |
| HGST HTS            | 1        | 1      | 0.02%   |
| FEASSO              | 1        | 2      | 0.02%   |
| China               | 1        | 1      | 0.02%   |
| Apple               | 1        | 1      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 775      | 1051   | 36.11%  |
| SanDisk             | 284      | 399    | 13.23%  |
| China               | 187      | 215    | 8.71%   |
| WDC                 | 154      | 196    | 7.18%   |
| Crucial             | 127      | 159    | 5.92%   |
| Samsung Electronics | 99       | 187    | 4.61%   |
| A-DATA Technology   | 74       | 85     | 3.45%   |
| Lexar               | 54       | 58     | 2.52%   |
| KingSpec            | 44       | 51     | 2.05%   |
| Corsair             | 28       | 37     | 1.3%    |
| Intel               | 26       | 29     | 1.21%   |
| Patriot             | 22       | 33     | 1.03%   |
| PNY                 | 20       | 21     | 0.93%   |
| JMicron Technology  | 18       | 19     | 0.84%   |
| Netac               | 15       | 24     | 0.7%    |
| KingDian            | 14       | 15     | 0.65%   |
| Gigabyte Technology | 14       | 21     | 0.65%   |
| OCZ                 | 12       | 13     | 0.56%   |
| XrayDisk            | 11       | 12     | 0.51%   |
| LITEON              | 11       | 11     | 0.51%   |
| Toshiba             | 9        | 11     | 0.42%   |
| Smart               | 9        | 11     | 0.42%   |
| Hewlett-Packard     | 8        | 10     | 0.37%   |
| Seagate             | 7        | 8      | 0.33%   |
| BHT                 | 7        | 11     | 0.33%   |
| Unknown             | 7        | 7      | 0.33%   |
| Unknown             | 6        | 6      | 0.28%   |
| Team                | 5        | 5      | 0.23%   |
| Maxtor              | 5        | 6      | 0.23%   |
| HS-SSD-C100         | 5        | 5      | 0.23%   |
| SK hynix            | 4        | 5      | 0.19%   |
| RZX                 | 4        | 9      | 0.19%   |
| Pichau              | 4        | 4      | 0.19%   |
| KODAK               | 4        | 4      | 0.19%   |
| Apacer              | 4        | 4      | 0.19%   |
| Plextor             | 3        | 4      | 0.14%   |
| KINGBANK            | 3        | 5      | 0.14%   |
| Colorful            | 3        | 4      | 0.14%   |
| Zheino              | 2        | 5      | 0.09%   |
| WALRAM              | 2        | 2      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3561     | 6213   | 59.71%  |
| SSD     | 1859     | 2836   | 31.17%  |
| NVMe    | 467      | 690    | 7.83%   |
| Unknown | 72       | 101    | 1.21%   |
| MMC     | 5        | 6      | 0.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4233     | 8899   | 86.74%  |
| NVMe | 466      | 688    | 9.55%   |
| SAS  | 176      | 253    | 3.61%   |
| MMC  | 5        | 6      | 0.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 3515     | 5998   | 62.77%  |
| 0.51-1.0   | 1514     | 2212   | 27.04%  |
| 1.01-2.0   | 393      | 581    | 7.02%   |
| 3.01-4.0   | 68       | 104    | 1.21%   |
| 2.01-3.0   | 63       | 86     | 1.13%   |
| 4.01-10.0  | 43       | 62     | 0.77%   |
| 10.01-20.0 | 4        | 6      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1174     | 24.96%  |
| 251-500        | 1076     | 22.87%  |
| 501-1000       | 668      | 14.2%   |
| 1001-2000      | 473      | 10.06%  |
| 1-20           | 381      | 8.1%    |
| 51-100         | 313      | 6.65%   |
| 21-50          | 184      | 3.91%   |
| 2001-3000      | 173      | 3.68%   |
| More than 3000 | 154      | 3.27%   |
| Unknown        | 108      | 2.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1835     | 38.03%  |
| 21-50          | 853      | 17.68%  |
| 101-250        | 561      | 11.63%  |
| 51-100         | 505      | 10.47%  |
| 251-500        | 355      | 7.36%   |
| 501-1000       | 337      | 6.98%   |
| 1001-2000      | 169      | 3.5%    |
| Unknown        | 108      | 2.24%   |
| 2001-3000      | 55       | 1.14%   |
| More than 3000 | 47       | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 45       | 48     | 5.81%   |
| WDC WD5000AAKX-003CA0 500GB         | 24       | 24     | 3.1%    |
| Samsung Electronics HD322HJ 320GB   | 22       | 29     | 2.84%   |
| Samsung Electronics HD161HJ 160GB   | 19       | 20     | 2.45%   |
| Samsung Electronics HD502HI 500GB   | 17       | 20     | 2.19%   |
| Samsung Electronics HD502HJ 500GB   | 14       | 14     | 1.81%   |
| WDC WD10EARS-00Y5B1 1TB             | 12       | 15     | 1.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10       | 10     | 1.29%   |
| Seagate ST1000DM010-2EP102 1TB      | 10       | 13     | 1.29%   |
| Maxtor STM3160215AS 160GB           | 10       | 11     | 1.29%   |
| WDC WD3200AAJS-00L7A0 320GB         | 9        | 9      | 1.16%   |
| Seagate ST3500418AS 500GB           | 9        | 14     | 1.16%   |
| Seagate ST3320418AS 320GB           | 9        | 13     | 1.16%   |
| Samsung Electronics HD250HJ 250GB   | 9        | 10     | 1.16%   |
| Samsung Electronics HD080HJ 80GB    | 9        | 11     | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8        | 9      | 1.03%   |
| Samsung Electronics HD103SJ 1TB     | 8        | 10     | 1.03%   |
| Seagate ST31000524AS 1TB            | 7        | 7      | 0.9%    |
| Seagate ST2000DM001-1CH164 2TB      | 7        | 9      | 0.9%    |
| Seagate ST1500DL003-9VT16L 1TB      | 7        | 8      | 0.9%    |
| Seagate ST1000DM003-1CH162 1TB      | 7        | 9      | 0.9%    |
| WDC WD5000AAKX-083CA1 500GB         | 6        | 6      | 0.77%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 6        | 7      | 0.77%   |
| Seagate ST3500413AS 500GB           | 6        | 7      | 0.77%   |
| Seagate ST3500312CS 500GB           | 6        | 6      | 0.77%   |
| Seagate ST1000DM003-9YN162 1TB      | 6        | 6      | 0.77%   |
| Seagate ST1000DM003-1ER162 1TB      | 6        | 8      | 0.77%   |
| Samsung Electronics HD103SI 1TB     | 6        | 7      | 0.77%   |
| Maxtor STM3250310AS 250GB           | 6        | 6      | 0.77%   |
| Kingston SV300S37A120G 120GB SSD    | 6        | 6      | 0.77%   |
| Kingston SA400S37120G 120GB SSD     | 6        | 9      | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5        | 5      | 0.65%   |
| Toshiba MQ01ABD050 500GB            | 5        | 5      | 0.65%   |
| Toshiba DT01ACA050 500GB            | 5        | 5      | 0.65%   |
| Seagate ST3250318AS 250GB           | 5        | 5      | 0.65%   |
| Seagate ST3160318AS 160GB           | 5        | 5      | 0.65%   |
| Seagate ST31000528AS 1TB            | 5        | 8      | 0.65%   |
| Samsung Electronics HD081GJ 80GB    | 5        | 5      | 0.65%   |
| Kingston SA400S37480G 480GB SSD     | 5        | 6      | 0.65%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4        | 5      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 238      | 299    | 32.83%  |
| WDC                 | 179      | 206    | 24.69%  |
| Samsung Electronics | 151      | 186    | 20.83%  |
| Hitachi             | 35       | 36     | 4.83%   |
| Toshiba             | 30       | 32     | 4.14%   |
| Kingston            | 24       | 28     | 3.31%   |
| Maxtor              | 21       | 23     | 2.9%    |
| China               | 9        | 10     | 1.24%   |
| SanDisk             | 6        | 6      | 0.83%   |
| XPG                 | 4        | 4      | 0.55%   |
| Intel               | 3        | 3      | 0.41%   |
| A-DATA Technology   | 3        | 3      | 0.41%   |
| OCZ                 | 2        | 2      | 0.28%   |
| Hewlett-Packard     | 2        | 2      | 0.28%   |
| Crucial             | 2        | 2      | 0.28%   |
| Unknown             | 2        | 2      | 0.28%   |
| XrayDisk            | 1        | 1      | 0.14%   |
| PNY                 | 1        | 1      | 0.14%   |
| Plextor             | 1        | 1      | 0.14%   |
| OCZ-VERTEX3         | 1        | 1      | 0.14%   |
| Netac               | 1        | 1      | 0.14%   |
| Mushkin             | 1        | 1      | 0.14%   |
| KingSpec            | 1        | 1      | 0.14%   |
| Initio              | 1        | 1      | 0.14%   |
| HGST                | 1        | 1      | 0.14%   |
| Fujitsu             | 1        | 1      | 0.14%   |
| FEASSO              | 1        | 2      | 0.14%   |
| ExcelStor           | 1        | 2      | 0.14%   |
| EGON                | 1        | 1      | 0.14%   |
| Corsair             | 1        | 1      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 238      | 299    | 36.5%   |
| WDC                 | 172      | 198    | 26.38%  |
| Samsung Electronics | 150      | 185    | 23.01%  |
| Hitachi             | 35       | 36     | 5.37%   |
| Toshiba             | 30       | 32     | 4.6%    |
| Maxtor              | 21       | 23     | 3.22%   |
| Hewlett-Packard     | 2        | 2      | 0.31%   |
| HGST                | 1        | 1      | 0.15%   |
| Fujitsu             | 1        | 1      | 0.15%   |
| FEASSO              | 1        | 2      | 0.15%   |
| ExcelStor           | 1        | 2      | 0.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 567      | 781    | 88.73%  |
| SSD  | 64       | 71     | 10.02%  |
| NVMe | 8        | 8      | 1.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3        | 3      | 18.75%  |
| Samsung Electronics HD502HJ 500GB | 2        | 4      | 12.5%   |
| WDC WD5000AAKS-00C8A0 500GB       | 1        | 1      | 6.25%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 1        | 1      | 6.25%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 6.25%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 6.25%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 6.25%   |
| Seagate ST31000340NS 1TB          | 1        | 1      | 6.25%   |
| Samsung Electronics HM250HI 250GB | 1        | 1      | 6.25%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 6.25%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 6.25%   |
| Samsung Electronics HD080HJ 80GB  | 1        | 1      | 6.25%   |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 37.5%   |
| Samsung Electronics | 6        | 8      | 37.5%   |
| WDC                 | 2        | 2      | 12.5%   |
| Toshiba             | 1        | 1      | 6.25%   |
| Hitachi             | 1        | 1      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3016     | 6763   | 62.25%  |
| Works    | 1200     | 2205   | 24.77%  |
| Malfunc  | 613      | 860    | 12.65%  |
| Failed   | 16       | 18     | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2895     | 56.13%  |
| AMD                              | 1230     | 23.85%  |
| Nvidia                           | 218      | 4.23%   |
| Silicon Motion                   | 108      | 2.09%   |
| JMicron Technology               | 80       | 1.55%   |
| Marvell Technology Group         | 77       | 1.49%   |
| Realtek Semiconductor            | 72       | 1.4%    |
| ASMedia Technology               | 69       | 1.34%   |
| Samsung Electronics              | 63       | 1.22%   |
| SanDisk                          | 58       | 1.12%   |
| Phison Electronics               | 56       | 1.09%   |
| VIA Technologies                 | 49       | 0.95%   |
| ADATA Technology                 | 49       | 0.95%   |
| Kingston Technology Company      | 38       | 0.74%   |
| Micron/Crucial Technology        | 15       | 0.29%   |
| MAXIO Technology (Hangzhou)      | 9        | 0.17%   |
| LSI Logic / Symbios Logic        | 9        | 0.17%   |
| Silicon Integrated Systems [SiS] | 8        | 0.16%   |
| Broadcom / LSI                   | 8        | 0.16%   |
| Lite-On Technology               | 6        | 0.12%   |
| SK hynix                         | 5        | 0.1%    |
| Silicon Image                    | 5        | 0.1%    |
| Beijing Starblaze Technology     | 5        | 0.1%    |
| Seagate Technology               | 4        | 0.08%   |
| OCZ Technology Group             | 4        | 0.08%   |
| Shenzhen Longsys Electronics     | 3        | 0.06%   |
| Adaptec                          | 3        | 0.06%   |
| Solid State Storage Technology   | 2        | 0.04%   |
| Netac Technology                 | 2        | 0.04%   |
| ULi Electronics                  | 1        | 0.02%   |
| TenaFe                           | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| Micron Technology                | 1        | 0.02%   |
| Lenovo                           | 1        | 0.02%   |
| INNOGRIT                         | 1        | 0.02%   |
| Broadcom                         | 1        | 0.02%   |
| Biwin Storage Technology         | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 676      | 9.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 561      | 7.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 430      | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 393      | 5.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 313      | 4.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 296      | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 244      | 3.34%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 244      | 3.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 233      | 3.19%   |
| AMD FCH SATA Controller D                                                               | 219      | 3%      |
| AMD 400 Series Chipset SATA Controller                                                  | 216      | 2.96%   |
| Nvidia MCP61 SATA Controller                                                            | 179      | 2.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 164      | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 164      | 2.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 156      | 2.13%   |
| Nvidia MCP61 IDE                                                                        | 146      | 2%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 113      | 1.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 112      | 1.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 95       | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 90       | 1.23%   |
| Intel SATA Controller [RAID mode]                                                       | 88       | 1.2%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 82       | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                                  | 82       | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 66       | 0.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 66       | 0.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 64       | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 59       | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 59       | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 55       | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 48       | 0.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 47       | 0.64%   |
| AMD FCH IDE Controller                                                                  | 44       | 0.6%    |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 42       | 0.57%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 39       | 0.53%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 38       | 0.52%   |
| JMicron JMB368 IDE controller                                                           | 36       | 0.49%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 35       | 0.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 34       | 0.47%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 33       | 0.45%   |
| AMD X370 Series Chipset SATA Controller                                                 | 33       | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2978     | 55.55%  |
| IDE  | 1764     | 32.9%   |
| NVMe | 473      | 8.82%   |
| RAID | 130      | 2.42%   |
| SCSI | 10       | 0.19%   |
| SAS  | 6        | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 2965     | 67.22%  |
| AMD          | 1440     | 32.65%  |
| CentaurHauls | 5        | 0.11%   |
| Unknown      | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD FX-6300 Six-Core Processor              | 94       | 2.12%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 81       | 1.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 78       | 1.76%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 76       | 1.71%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 62       | 1.4%    |
| Intel Core i5 CPU 650 @ 3.20GHz             | 61       | 1.38%   |
| AMD Ryzen 5 3600 6-Core Processor           | 58       | 1.31%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 57       | 1.28%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 55       | 1.24%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 55       | 1.24%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 55       | 1.24%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 54       | 1.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 53       | 1.19%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 51       | 1.15%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 49       | 1.1%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 48       | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 48       | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 45       | 1.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 44       | 0.99%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 40       | 0.9%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 39       | 0.88%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 34       | 0.77%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 34       | 0.77%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 32       | 0.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 31       | 0.7%    |
| AMD FX-8300 Eight-Core Processor            | 31       | 0.7%    |
| AMD Ryzen 7 2700 Eight-Core Processor       | 30       | 0.68%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 29       | 0.65%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 28       | 0.63%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 28       | 0.63%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 28       | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 27       | 0.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 27       | 0.61%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 27       | 0.61%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 27       | 0.61%   |
| AMD FX-8350 Eight-Core Processor            | 27       | 0.61%   |
| AMD FX-4300 Quad-Core Processor             | 27       | 0.61%   |
| AMD Athlon II X2 250 Processor              | 27       | 0.61%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 26       | 0.59%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 25       | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 742      | 16.74%  |
| Intel Core i3           | 517      | 11.67%  |
| Intel Core i7           | 404      | 9.12%   |
| AMD Ryzen 5             | 350      | 7.9%    |
| AMD FX                  | 258      | 5.82%   |
| Intel Core 2 Duo        | 239      | 5.39%   |
| Intel Celeron           | 229      | 5.17%   |
| Intel Xeon              | 195      | 4.4%    |
| Intel Pentium Dual-Core | 173      | 3.9%    |
| AMD Ryzen 7             | 148      | 3.34%   |
| Intel Pentium           | 130      | 2.93%   |
| Intel Core 2 Quad       | 97       | 2.19%   |
| AMD Ryzen 3             | 91       | 2.05%   |
| AMD Phenom II X4        | 78       | 1.76%   |
| AMD Athlon II X2        | 73       | 1.65%   |
| Intel Pentium Dual      | 72       | 1.62%   |
| AMD Athlon 64 X2        | 45       | 1.02%   |
| AMD A8                  | 44       | 0.99%   |
| AMD Athlon              | 40       | 0.9%    |
| AMD A10                 | 37       | 0.83%   |
| AMD A4                  | 36       | 0.81%   |
| Intel Core 2            | 33       | 0.74%   |
| Intel Atom              | 33       | 0.74%   |
| AMD Ryzen 9             | 31       | 0.7%    |
| AMD Sempron             | 30       | 0.68%   |
| Other                   | 28       | 0.63%   |
| Intel Pentium 4         | 28       | 0.63%   |
| AMD Phenom II X6        | 27       | 0.61%   |
| AMD A6                  | 24       | 0.54%   |
| Intel Pentium Gold      | 19       | 0.43%   |
| Intel Core i9           | 19       | 0.43%   |
| AMD Athlon II X4        | 18       | 0.41%   |
| AMD Phenom II X2        | 17       | 0.38%   |
| AMD Phenom              | 14       | 0.32%   |
| Intel Pentium D         | 13       | 0.29%   |
| Intel Genuine           | 13       | 0.29%   |
| AMD Athlon II X3        | 13       | 0.29%   |
| AMD Ryzen 3 PRO         | 8        | 0.18%   |
| AMD E                   | 7        | 0.16%   |
| AMD Ryzen 5 PRO         | 6        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1715     | 38.7%   |
| 4       | 1579     | 35.64%  |
| 6       | 495      | 11.17%  |
| 8       | 223      | 5.03%   |
| 1       | 185      | 4.18%   |
| 3       | 135      | 3.05%   |
| 12      | 46       | 1.04%   |
| 10      | 17       | 0.38%   |
| 16      | 16       | 0.36%   |
| Unknown | 11       | 0.25%   |
| 24      | 4        | 0.09%   |
| 14      | 3        | 0.07%   |
| 28      | 1        | 0.02%   |
| 20      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 4391     | 99.52%  |
| 2       | 20       | 0.45%   |
| Unknown | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2240     | 50.7%   |
| 2       | 2166     | 49.03%  |
| Unknown | 11       | 0.25%   |
| 4       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4166     | 93.85%  |
| Unknown        | 229      | 5.16%   |
| 64-bit         | 29       | 0.65%   |
| 32-bit         | 15       | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 864      | 18.94%  |
| 0x306a9    | 385      | 8.44%   |
| 0x206a7    | 380      | 8.33%   |
| 0x1067a    | 370      | 8.11%   |
| 0x306c3    | 304      | 6.67%   |
| 0x06000852 | 152      | 3.33%   |
| 0x906e9    | 127      | 2.78%   |
| 0x906ea    | 114      | 2.5%    |
| 0x010000c8 | 113      | 2.48%   |
| 0x6fd      | 100      | 2.19%   |
| 0x0800820d | 81       | 1.78%   |
| 0x08701021 | 74       | 1.62%   |
| 0x20655    | 73       | 1.6%    |
| 0x08108109 | 72       | 1.58%   |
| 0x08701013 | 53       | 1.16%   |
| 0x6fb      | 50       | 1.1%    |
| 0x306f2    | 50       | 1.1%    |
| 0x506e3    | 48       | 1.05%   |
| 0x20652    | 45       | 0.99%   |
| 0x10676    | 43       | 0.94%   |
| 0x06001119 | 43       | 0.94%   |
| 0x08101016 | 40       | 0.88%   |
| 0x30678    | 35       | 0.77%   |
| 0x106e5    | 34       | 0.75%   |
| 0x08001138 | 34       | 0.75%   |
| 0xa0653    | 33       | 0.72%   |
| 0x010000db | 32       | 0.7%    |
| 0x0600611a | 30       | 0.66%   |
| 0x06003106 | 30       | 0.66%   |
| 0x906ed    | 28       | 0.61%   |
| 0x906eb    | 27       | 0.59%   |
| 0x306e4    | 27       | 0.59%   |
| 0x010000dc | 26       | 0.57%   |
| 0x10661    | 25       | 0.55%   |
| 0x0600063e | 25       | 0.55%   |
| 0x0810100b | 24       | 0.53%   |
| 0x206d7    | 20       | 0.44%   |
| 0x08001137 | 20       | 0.44%   |
| 0x6f2      | 18       | 0.39%   |
| 0x08108102 | 18       | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 485      | 10.97%  |
| Penryn           | 473      | 10.7%   |
| SandyBridge      | 460      | 10.41%  |
| Haswell          | 424      | 9.59%   |
| KabyLake         | 370      | 8.37%   |
| Piledriver       | 272      | 6.15%   |
| K10              | 270      | 6.11%   |
| Core             | 232      | 5.25%   |
| Zen+             | 222      | 5.02%   |
| Zen              | 190      | 4.3%    |
| Zen 2            | 170      | 3.85%   |
| Westmere         | 145      | 3.28%   |
| Zen 3            | 75       | 1.7%    |
| Skylake          | 70       | 1.58%   |
| Silvermont       | 70       | 1.58%   |
| K8 Hammer        | 66       | 1.49%   |
| CometLake        | 65       | 1.47%   |
| Nehalem          | 55       | 1.24%   |
| NetBurst         | 49       | 1.11%   |
| Bulldozer        | 41       | 0.93%   |
| Steamroller      | 40       | 0.9%    |
| Excavator        | 38       | 0.86%   |
| Bonnell          | 28       | 0.63%   |
| Unknown          | 21       | 0.48%   |
| Bobcat           | 19       | 0.43%   |
| Jaguar           | 18       | 0.41%   |
| K10 Llano        | 14       | 0.32%   |
| Broadwell        | 11       | 0.25%   |
| Icelake          | 9        | 0.2%    |
| Goldmont plus    | 9        | 0.2%    |
| Alderlake Hybrid | 4        | 0.09%   |
| Tremont          | 3        | 0.07%   |
| Puma             | 1        | 0.02%   |
| K6               | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1679     | 36.17%  |
| Nvidia                           | 1605     | 34.58%  |
| AMD                              | 1304     | 28.09%  |
| VIA Technologies                 | 31       | 0.67%   |
| Matrox Electronics Systems       | 8        | 0.17%   |
| Silicon Integrated Systems [SiS] | 5        | 0.11%   |
| Silicon Motion                   | 4        | 0.09%   |
| ATI Technologies                 | 4        | 0.09%   |
| S3 Graphics                      | 1        | 0.02%   |
| ASPEED Technology                | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 282      | 5.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 233      | 4.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 185      | 3.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 163      | 3.44%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 159      | 3.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 155      | 3.27%   |
| Nvidia GT218 [GeForce 210]                                                  | 143      | 3.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 101      | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                         | 97       | 2.05%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 96       | 2.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 88       | 1.86%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 84       | 1.77%   |
| AMD RS780L [Radeon 3000]                                                    | 82       | 1.73%   |
| Nvidia GK208B [GeForce GT 710]                                              | 74       | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 74       | 1.56%   |
| Intel HD Graphics 630                                                       | 68       | 1.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 67       | 1.41%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 62       | 1.31%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 58       | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 58       | 1.22%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 58       | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 53       | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 50       | 1.06%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 48       | 1.01%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 48       | 1.01%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 46       | 0.97%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 45       | 0.95%   |
| Nvidia GF108 [GeForce GT 730]                                               | 38       | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 36       | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 36       | 0.76%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 34       | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 33       | 0.7%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 32       | 0.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 32       | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 30       | 0.63%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 29       | 0.61%   |
| Intel HD Graphics 530                                                       | 29       | 0.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 28       | 0.59%   |
| AMD RS880 [Radeon HD 4200]                                                  | 28       | 0.59%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 28       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 1539     | 34.38%  |
| 1 x Nvidia              | 1512     | 33.77%  |
| 1 x AMD                 | 1238     | 27.65%  |
| Intel + Nvidia          | 45       | 1.01%   |
| 2 x AMD                 | 36       | 0.8%    |
| 1 x VIA                 | 30       | 0.67%   |
| AMD + Nvidia            | 20       | 0.45%   |
| Intel + AMD             | 18       | 0.4%    |
| 2 x Nvidia              | 15       | 0.34%   |
| 1 x Matrox              | 7        | 0.16%   |
| 1 x SiS                 | 5        | 0.11%   |
| 2 x Intel               | 2        | 0.04%   |
| Intel + Silicon Motion  | 2        | 0.04%   |
| Other                   | 1        | 0.02%   |
| 1 x Silicon Motion      | 1        | 0.02%   |
| 1 x S3 Graphics         | 1        | 0.02%   |
| Nvidia + Silicon Motion | 1        | 0.02%   |
| Intel + 2 x AMD         | 1        | 0.02%   |
| 1 x ASPEED              | 1        | 0.02%   |
| AMD + 2 x Nvidia        | 1        | 0.02%   |
| AMD + Matrox            | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3416     | 76.2%   |
| Proprietary | 847      | 18.89%  |
| Unknown     | 220      | 4.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2029     | 44.53%  |
| 1.01-2.0   | 678      | 14.88%  |
| 0.51-1.0   | 611      | 13.41%  |
| 0.01-0.5   | 493      | 10.82%  |
| 3.01-4.0   | 377      | 8.27%   |
| 7.01-8.0   | 180      | 3.95%   |
| 5.01-6.0   | 119      | 2.61%   |
| 2.01-3.0   | 44       | 0.97%   |
| 8.01-16.0  | 21       | 0.46%   |
| 4.01-5.0   | 2        | 0.04%   |
| 16.01-24.0 | 2        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 1166     | 26.84%  |
| Samsung Electronics  | 980      | 22.55%  |
| AOC                  | 651      | 14.98%  |
| Dell                 | 335      | 7.71%   |
| Philips              | 236      | 5.43%   |
| LG Electronics       | 147      | 3.38%   |
| Acer                 | 140      | 3.22%   |
| Hewlett-Packard      | 88       | 2.03%   |
| BenQ                 | 55       | 1.27%   |
| Unknown              | 51       | 1.17%   |
| Sony                 | 50       | 1.15%   |
| Positivo             | 39       | 0.9%    |
| Lenovo               | 37       | 0.85%   |
| Ancor Communications | 22       | 0.51%   |
| Panasonic            | 20       | 0.46%   |
| ASUSTek Computer     | 18       | 0.41%   |
| GDH                  | 14       | 0.32%   |
| TXD                  | 12       | 0.28%   |
| RTK                  | 12       | 0.28%   |
| NCS                  | 12       | 0.28%   |
| Daewoo               | 12       | 0.28%   |
| HB@                  | 11       | 0.25%   |
| VIE                  | 9        | 0.21%   |
| Unknown (XXX)        | 9        | 0.21%   |
| Toshiba              | 9        | 0.21%   |
| Envision             | 9        | 0.21%   |
| AGO                  | 9        | 0.21%   |
| PZG                  | 7        | 0.16%   |
| MSI                  | 7        | 0.16%   |
| JRY                  | 7        | 0.16%   |
| ___                  | 6        | 0.14%   |
| STA                  | 6        | 0.14%   |
| SKY                  | 6        | 0.14%   |
| Envision Peripherals | 6        | 0.14%   |
| CVT                  | 6        | 0.14%   |
| Proview              | 5        | 0.12%   |
| MStar                | 5        | 0.12%   |
| Unknown              | 5        | 0.12%   |
| STD                  | 4        | 0.09%   |
| Semp Toshiba         | 4        | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 95       | 2.05%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 61       | 1.31%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 55       | 1.18%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 53       | 1.14%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 43       | 0.93%   |
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 35       | 0.75%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 32       | 0.69%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 32       | 0.69%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 31       | 0.67%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 28       | 0.6%    |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 28       | 0.6%    |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 27       | 0.58%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 27       | 0.58%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 27       | 0.58%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 24       | 0.52%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 24       | 0.52%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                       | 24       | 0.52%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 23       | 0.5%    |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 22       | 0.47%   |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                | 22       | 0.47%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 21       | 0.45%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 20       | 0.43%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 20       | 0.43%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch               | 20       | 0.43%   |
| AOC 1621Wb AOC1621 1366x768 344x194mm 15.5-inch                      | 20       | 0.43%   |
| AOC 1619w AOC1619 1366x768 340x190mm 15.3-inch                       | 20       | 0.43%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch            | 19       | 0.41%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 19       | 0.41%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 18       | 0.39%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch    | 17       | 0.37%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 17       | 0.37%   |
| AOC 712Sa AOC1712 1280x1024 340x270mm 17.1-inch                      | 17       | 0.37%   |
| AOC 1943W AOC1943 1366x768 410x230mm 18.5-inch                       | 17       | 0.37%   |
| Positivo LCD Monitor NON1801 1360x768 410x230mm 18.5-inch            | 16       | 0.34%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 16       | 0.34%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                | 16       | 0.34%   |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 16       | 0.34%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 16       | 0.34%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 15       | 0.32%   |
| Goldstar L1552S GSM3BAE 1024x768 304x228mm 15.0-inch                 | 15       | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1484     | 33.84%  |
| 1366x768 (WXGA)    | 706      | 16.1%   |
| 1600x900 (HD+)     | 330      | 7.53%   |
| 1280x1024 (SXGA)   | 298      | 6.8%    |
| 1440x900 (WXGA+)   | 295      | 6.73%   |
| 1360x768           | 266      | 6.07%   |
| 2560x1080          | 225      | 5.13%   |
| 3840x2160 (4K)     | 168      | 3.83%   |
| 1680x1050 (WSXGA+) | 151      | 3.44%   |
| 1024x768 (XGA)     | 96       | 2.19%   |
| Unknown            | 94       | 2.14%   |
| 2560x1440 (QHD)    | 52       | 1.19%   |
| 1280x720 (HD)      | 38       | 0.87%   |
| 3840x1080          | 26       | 0.59%   |
| 1920x540           | 19       | 0.43%   |
| 1920x1200 (WUXGA)  | 16       | 0.36%   |
| 2288x1287          | 14       | 0.32%   |
| 3440x1440          | 13       | 0.3%    |
| 1152x864           | 9        | 0.21%   |
| 4480x1080          | 6        | 0.14%   |
| 1280x800 (WXGA)    | 6        | 0.14%   |
| 3360x1080          | 5        | 0.11%   |
| 3200x1080          | 5        | 0.11%   |
| 1600x1200          | 5        | 0.11%   |
| 5760x1080          | 4        | 0.09%   |
| 3286x1080          | 4        | 0.09%   |
| 3520x1080          | 3        | 0.07%   |
| 2732x768           | 3        | 0.07%   |
| 2560x1600          | 3        | 0.07%   |
| 6400x1080          | 2        | 0.05%   |
| 3360x1050          | 2        | 0.05%   |
| 2800x900           | 2        | 0.05%   |
| 2720x1024          | 2        | 0.05%   |
| 2646x768           | 2        | 0.05%   |
| 2646x1024          | 2        | 0.05%   |
| 1280x960           | 2        | 0.05%   |
| 640x480            | 1        | 0.02%   |
| 6400x2160          | 1        | 0.02%   |
| 5760x2160          | 1        | 0.02%   |
| 5440x1080          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 666      | 15.11%  |
| 21      | 518      | 11.75%  |
| 23      | 471      | 10.69%  |
| Unknown | 449      | 10.19%  |
| 17      | 334      | 7.58%   |
| 15      | 273      | 6.19%   |
| 19      | 242      | 5.49%   |
| 20      | 241      | 5.47%   |
| 24      | 236      | 5.35%   |
| 34      | 189      | 4.29%   |
| 27      | 181      | 4.11%   |
| 22      | 101      | 2.29%   |
| 31      | 84       | 1.91%   |
| 72      | 43       | 0.98%   |
| 40      | 39       | 0.88%   |
| 32      | 38       | 0.86%   |
| 28      | 34       | 0.77%   |
| 84      | 30       | 0.68%   |
| 54      | 29       | 0.66%   |
| 26      | 25       | 0.57%   |
| 16      | 24       | 0.54%   |
| 46      | 22       | 0.5%    |
| 52      | 19       | 0.43%   |
| 14      | 19       | 0.43%   |
| 12      | 18       | 0.41%   |
| 13      | 12       | 0.27%   |
| 142     | 10       | 0.23%   |
| 47      | 9        | 0.2%    |
| 48      | 7        | 0.16%   |
| 25      | 6        | 0.14%   |
| 39      | 5        | 0.11%   |
| 37      | 5        | 0.11%   |
| 65      | 3        | 0.07%   |
| 50      | 3        | 0.07%   |
| 43      | 3        | 0.07%   |
| 41      | 3        | 0.07%   |
| 29      | 3        | 0.07%   |
| 38      | 2        | 0.05%   |
| 75      | 1        | 0.02%   |
| 64      | 1        | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 1655     | 38.59%  |
| 501-600        | 845      | 19.7%   |
| 301-350        | 529      | 12.33%  |
| Unknown        | 449      | 10.47%  |
| 701-800        | 228      | 5.32%   |
| 351-400        | 164      | 3.82%   |
| 601-700        | 143      | 3.33%   |
| 1001-1500      | 96       | 2.24%   |
| 1501-2000      | 74       | 1.73%   |
| 801-900        | 51       | 1.19%   |
| 201-300        | 38       | 0.89%   |
| More than 2000 | 10       | 0.23%   |
| 901-1000       | 7        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2667     | 64.33%  |
| Unknown | 399      | 9.62%   |
| 16/10   | 392      | 9.45%   |
| 5/4     | 292      | 7.04%   |
| 21/9    | 210      | 5.07%   |
| 4/3     | 133      | 3.21%   |
| 3/2     | 36       | 0.87%   |
| 1.00    | 12       | 0.29%   |
| 6/5     | 1        | 0.02%   |
| 32/9    | 1        | 0.02%   |
| 2.00    | 1        | 0.02%   |
| 0.56    | 1        | 0.02%   |
| 0.31    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1118     | 25.69%  |
| 141-150        | 844      | 19.39%  |
| 151-200        | 659      | 15.14%  |
| Unknown        | 449      | 10.32%  |
| 351-500        | 322      | 7.4%    |
| 101-110        | 249      | 5.72%   |
| 301-350        | 184      | 4.23%   |
| More than 1000 | 149      | 3.42%   |
| 251-300        | 98       | 2.25%   |
| 501-1000       | 91       | 2.09%   |
| 131-140        | 90       | 2.07%   |
| 111-120        | 30       | 0.69%   |
| 81-90          | 18       | 0.41%   |
| 71-80          | 18       | 0.41%   |
| 91-100         | 18       | 0.41%   |
| 121-130        | 13       | 0.3%    |
| 51-60          | 1        | 0.02%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2710     | 64.71%  |
| 101-120 | 734      | 17.53%  |
| Unknown | 450      | 10.74%  |
| 1-50    | 218      | 5.21%   |
| 121-160 | 47       | 1.12%   |
| 161-240 | 29       | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3616     | 80.66%  |
| 2     | 578      | 12.89%  |
| 0     | 254      | 5.67%   |
| 3     | 31       | 0.69%   |
| 4     | 4        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3133     | 52.9%   |
| Intel                             | 808      | 13.64%  |
| Qualcomm Atheros                  | 516      | 8.71%   |
| Ralink Technology                 | 330      | 5.57%   |
| Nvidia                            | 187      | 3.16%   |
| Broadcom                          | 141      | 2.38%   |
| TP-Link                           | 119      | 2.01%   |
| Qualcomm Atheros Communications   | 106      | 1.79%   |
| Ralink                            | 82       | 1.38%   |
| Samsung Electronics               | 56       | 0.95%   |
| D-Link                            | 52       | 0.88%   |
| VIA Technologies                  | 46       | 0.78%   |
| Microsoft                         | 41       | 0.69%   |
| Marvell Technology Group          | 41       | 0.69%   |
| Broadcom Limited                  | 29       | 0.49%   |
| D-Link System                     | 27       | 0.46%   |
| Xiaomi                            | 26       | 0.44%   |
| MediaTek                          | 21       | 0.35%   |
| JMicron Technology                | 20       | 0.34%   |
| Motorola PCS                      | 17       | 0.29%   |
| Motorola                          | 14       | 0.24%   |
| ASIX Electronics                  | 7        | 0.12%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.1%    |
| ICS Advent                        | 6        | 0.1%    |
| Huawei Technologies               | 6        | 0.1%    |
| Mercucys                          | 5        | 0.08%   |
| Edimax Technology                 | 5        | 0.08%   |
| ASUSTek Computer                  | 5        | 0.08%   |
| 3Com                              | 5        | 0.08%   |
| Sundance Technology Inc / IC Plus | 4        | 0.07%   |
| DisplayLink                       | 4        | 0.07%   |
| Qualcomm                          | 3        | 0.05%   |
| LG Electronics                    | 3        | 0.05%   |
| Hangzhou Silan Microelectronics   | 3        | 0.05%   |
| Encore Electronics                | 3        | 0.05%   |
| Arduino SA                        | 3        | 0.05%   |
| Accton Technology                 | 3        | 0.05%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.03%   |
| T & A Mobile Phones               | 2        | 0.03%   |
| STMicroelectronics                | 2        | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2426     | 37.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 419      | 6.51%   |
| Ralink MT7601U Wireless Adapter                                   | 183      | 2.84%   |
| Nvidia MCP61 Ethernet                                             | 159      | 2.47%   |
| Qualcomm Atheros AR9271 802.11n                                   | 94       | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 89       | 1.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 89       | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 86       | 1.34%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 81       | 1.26%   |
| Intel Ethernet Connection (7) I219-V                              | 79       | 1.23%   |
| Intel I211 Gigabit Network Connection                             | 78       | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 76       | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 75       | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 68       | 1.06%   |
| Ralink RT5370 Wireless Adapter                                    | 68       | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 64       | 0.99%   |
| Intel Wi-Fi 6 AX200                                               | 58       | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 52       | 0.81%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 48       | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 46       | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 45       | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 40       | 0.62%   |
| Intel Ethernet Connection I217-LM                                 | 39       | 0.61%   |
| Realtek 802.11ac NIC                                              | 38       | 0.59%   |
| Microsoft Xbox 360 Wireless Adapter                               | 36       | 0.56%   |
| Intel 82578DC Gigabit Network Connection                          | 36       | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 35       | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 34       | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 34       | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 32       | 0.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 29       | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 29       | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 28       | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 28       | 0.44%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 27       | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 26       | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 26       | 0.4%    |
| Ralink RT2561/RT61 802.11g PCI                                    | 26       | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 25       | 0.39%   |
| Intel 82578DM Gigabit Network Connection                          | 25       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 441      | 26.28%  |
| Ralink Technology                     | 330      | 19.67%  |
| Qualcomm Atheros                      | 244      | 14.54%  |
| Intel                                 | 166      | 9.89%   |
| TP-Link                               | 116      | 6.91%   |
| Qualcomm Atheros Communications       | 106      | 6.32%   |
| Ralink                                | 82       | 4.89%   |
| D-Link                                | 52       | 3.1%    |
| Microsoft                             | 41       | 2.44%   |
| Broadcom                              | 34       | 2.03%   |
| D-Link System                         | 16       | 0.95%   |
| MediaTek                              | 15       | 0.89%   |
| Mercucys                              | 5        | 0.3%    |
| Marvell Technology Group              | 5        | 0.3%    |
| Edimax Technology                     | 5        | 0.3%    |
| Broadcom Limited                      | 4        | 0.24%   |
| Encore Electronics                    | 3        | 0.18%   |
| IMC Networks                          | 2        | 0.12%   |
| ASUSTek Computer                      | 2        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.12%   |
| Texas Instruments                     | 1        | 0.06%   |
| Samsung Electronics                   | 1        | 0.06%   |
| Philips (or NXP)                      | 1        | 0.06%   |
| NetGear                               | 1        | 0.06%   |
| Micro Star International              | 1        | 0.06%   |
| Linksys                               | 1        | 0.06%   |
| Accton Technology                     | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                      | 183      | 10.78%  |
| Qualcomm Atheros AR9271 802.11n                                      | 94       | 5.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 81       | 4.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 76       | 4.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 68       | 4%      |
| Ralink RT5370 Wireless Adapter                                       | 68       | 4%      |
| Intel Wi-Fi 6 AX200                                                  | 58       | 3.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 40       | 2.36%   |
| Realtek 802.11ac NIC                                                 | 38       | 2.24%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 36       | 2.12%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 32       | 1.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 29       | 1.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 28       | 1.65%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 27       | 1.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 26       | 1.53%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 26       | 1.53%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 26       | 1.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 25       | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 23       | 1.35%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 22       | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 21       | 1.24%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter           | 21       | 1.24%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 18       | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 17       | 1%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 17       | 1%      |
| Intel Wireless-AC 9260                                               | 16       | 0.94%   |
| Intel Wireless 7260                                                  | 16       | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 15       | 0.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 14       | 0.82%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter             | 13       | 0.77%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 13       | 0.77%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 13       | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 12       | 0.71%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 11       | 0.65%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 11       | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 11       | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 11       | 0.65%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 11       | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 10       | 0.59%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller            | 10       | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2995     | 65.04%  |
| Intel                             | 721      | 15.66%  |
| Qualcomm Atheros                  | 291      | 6.32%   |
| Nvidia                            | 187      | 4.06%   |
| Broadcom                          | 108      | 2.35%   |
| Samsung Electronics               | 55       | 1.19%   |
| VIA Technologies                  | 45       | 0.98%   |
| Marvell Technology Group          | 36       | 0.78%   |
| Xiaomi                            | 26       | 0.56%   |
| Broadcom Limited                  | 25       | 0.54%   |
| JMicron Technology                | 20       | 0.43%   |
| Motorola PCS                      | 13       | 0.28%   |
| D-Link System                     | 11       | 0.24%   |
| ASIX Electronics                  | 7        | 0.15%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.13%   |
| MediaTek                          | 6        | 0.13%   |
| ICS Advent                        | 6        | 0.13%   |
| 3Com                              | 5        | 0.11%   |
| Sundance Technology Inc / IC Plus | 4        | 0.09%   |
| Huawei Technologies               | 4        | 0.09%   |
| DisplayLink                       | 4        | 0.09%   |
| TP-Link                           | 3        | 0.07%   |
| Qualcomm                          | 3        | 0.07%   |
| LG Electronics                    | 3        | 0.07%   |
| Hangzhou Silan Microelectronics   | 3        | 0.07%   |
| ASUSTek Computer                  | 3        | 0.07%   |
| T & A Mobile Phones               | 2        | 0.04%   |
| Aquantia                          | 2        | 0.04%   |
| Apple                             | 2        | 0.04%   |
| Accton Technology                 | 2        | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.02%   |
| Spreadtrum Communications         | 1        | 0.02%   |
| SK hynix                          | 1        | 0.02%   |
| OPPO Electronics                  | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| IBM                               | 1        | 0.02%   |
| AMD                               | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2426     | 51.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 419      | 8.93%   |
| Nvidia MCP61 Ethernet                                             | 159      | 3.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 89       | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 89       | 1.9%    |
| Intel Ethernet Connection (2) I219-V                              | 86       | 1.83%   |
| Intel Ethernet Connection (7) I219-V                              | 79       | 1.68%   |
| Intel I211 Gigabit Network Connection                             | 78       | 1.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 75       | 1.6%    |
| Intel 82579V Gigabit Network Connection                           | 64       | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 52       | 1.11%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 48       | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 46       | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 45       | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 39       | 0.83%   |
| Intel 82578DC Gigabit Network Connection                          | 36       | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 35       | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 34       | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 34       | 0.72%   |
| Intel Ethernet Connection (2) I218-V                              | 29       | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 28       | 0.6%    |
| Intel 82578DM Gigabit Network Connection                          | 25       | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22       | 0.47%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 20       | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20       | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19       | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 19       | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 18       | 0.38%   |
| Intel Ethernet Controller I225-V                                  | 18       | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 17       | 0.36%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 16       | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 15       | 0.32%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 14       | 0.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 13       | 0.28%   |
| Motorola PCS moto g pure                                          | 13       | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.26%   |
| Intel Ethernet Connection (12) I219-V                             | 12       | 0.26%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 0.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 11       | 0.23%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 11       | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4338     | 72.72%  |
| WiFi     | 1584     | 26.55%  |
| Modem    | 32       | 0.54%   |
| Unknown  | 11       | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3470     | 76.94%  |
| WiFi     | 1039     | 23.04%  |
| Unknown  | 1        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3475     | 78.23%  |
| 2     | 830      | 18.69%  |
| 0     | 70       | 1.58%   |
| 3     | 60       | 1.35%   |
| 4     | 5        | 0.11%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3563     | 78.76%  |
| Yes  | 961      | 21.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 403      | 53.59%  |
| Intel                           | 146      | 19.41%  |
| Realtek Semiconductor           | 58       | 7.71%   |
| Qualcomm Atheros Communications | 56       | 7.45%   |
| Broadcom                        | 23       | 3.06%   |
| ASUSTek Computer                | 18       | 2.39%   |
| MediaTek                        | 11       | 1.46%   |
| Integrated System Solution      | 7        | 0.93%   |
| Apple                           | 7        | 0.93%   |
| IMC Networks                    | 6        | 0.8%    |
| Conwise Technology              | 3        | 0.4%    |
| Unknown                         | 3        | 0.4%    |
| Foxconn / Hon Hai               | 2        | 0.27%   |
| Actions                         | 2        | 0.27%   |
| SINO WEALTH                     | 1        | 0.13%   |
| Realtek                         | 1        | 0.13%   |
| Ralink                          | 1        | 0.13%   |
| Qcom                            | 1        | 0.13%   |
| Motorola PCS                    | 1        | 0.13%   |
| Micro Star International        | 1        | 0.13%   |
| D-Link                          | 1        | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 403      | 53.45%  |
| Realtek Bluetooth Radio                               | 55       | 7.29%   |
| Intel AX200 Bluetooth                                 | 50       | 6.63%   |
| Intel Bluetooth wireless interface                    | 43       | 5.7%    |
| Qualcomm Atheros  Bluetooth Device                    | 23       | 3.05%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 17       | 2.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 16       | 2.12%   |
| MediaTek Wireless_Device                              | 11       | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                      | 11       | 1.46%   |
| Intel AX210 Bluetooth                                 | 11       | 1.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 9        | 1.19%   |
| Apple Bluetooth Host Controller                       | 6        | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 5        | 0.66%   |
| Intel AX201 Bluetooth                                 | 5        | 0.66%   |
| ASUS Bluetooth Radio                                  | 5        | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 4        | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4        | 0.53%   |
| Integrated System Solution Bluetooth Device           | 4        | 0.53%   |
| Broadcom BCM92045B3 ROM                               | 4        | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 0.53%   |
| ASUS Bluetooth Adapter                                | 4        | 0.53%   |
| Qualcomm Atheros Bluetooth                            | 3        | 0.4%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.4%    |
| IMC Networks Bluetooth Radio                          | 3        | 0.4%    |
| Conwise CW6622                                        | 3        | 0.4%    |
| Broadcom Bluetooth 2.0+eDR dongle                     | 3        | 0.4%    |
| Unknown                                               | 3        | 0.4%    |
| IMC Networks Wireless_Device                          | 2        | 0.27%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 0.27%   |
| Broadcom Bluetooth Controller                         | 2        | 0.27%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle    | 2        | 0.27%   |
| Broadcom BCM2210 Bluetooth                            | 2        | 0.27%   |
| ASUS Qualcomm Bluetooth 4.1                           | 2        | 0.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 0.27%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 0.27%   |
| ASUS BCM20702A0                                       | 2        | 0.27%   |
| Actions general adapter                               | 2        | 0.27%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.13%   |
| Realtek RTL8821A Bluetooth                            | 1        | 0.13%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 0.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 2859     | 42.92%  |
| AMD                                             | 1641     | 24.64%  |
| Nvidia                                          | 1431     | 21.48%  |
| C-Media Electronics                             | 174      | 2.61%   |
| Generalplus Technology                          | 75       | 1.13%   |
| VIA Technologies                                | 51       | 0.77%   |
| JMTek                                           | 48       | 0.72%   |
| Logitech                                        | 42       | 0.63%   |
| Creative Labs                                   | 37       | 0.56%   |
| Kingston Technology                             | 32       | 0.48%   |
| Texas Instruments                               | 28       | 0.42%   |
| Corsair                                         | 18       | 0.27%   |
| Microsoft                                       | 15       | 0.23%   |
| Tenx Technology                                 | 13       | 0.2%    |
| BEHRINGER International                         | 12       | 0.18%   |
| Razer USA                                       | 10       | 0.15%   |
| Licensed by Sony Computer Entertainment America | 10       | 0.15%   |
| Plantronics                                     | 9        | 0.14%   |
| Sony                                            | 7        | 0.11%   |
| Silicon Integrated Systems [SiS]                | 7        | 0.11%   |
| GN Netcom                                       | 7        | 0.11%   |
| M-Audio                                         | 6        | 0.09%   |
| Fry's Electronics                               | 6        | 0.09%   |
| Philips (or NXP)                                | 5        | 0.08%   |
| Focusrite-Novation                              | 5        | 0.08%   |
| Creative Technology                             | 5        | 0.08%   |
| Cirrus Logic                                    | 5        | 0.08%   |
| BY EDIFIER                                      | 5        | 0.08%   |
| SteelSeries ApS                                 | 4        | 0.06%   |
| Goldvish                                        | 4        | 0.06%   |
| Elite Silicon                                   | 4        | 0.06%   |
| Dell                                            | 4        | 0.06%   |
| ATI Technologies                                | 4        | 0.06%   |
| UCQ01000                                        | 3        | 0.05%   |
| Samson Technologies                             | 3        | 0.05%   |
| Medeli Electronics                              | 3        | 0.05%   |
| KTMicro                                         | 3        | 0.05%   |
| JBL                                             | 3        | 0.05%   |
| Cambridge Silicon Radio                         | 3        | 0.05%   |
| ASUSTek Computer                                | 3        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 648      | 8.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 561      | 7.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 389      | 5.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 333      | 4.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 251      | 3.25%   |
| AMD Family 17h/19h HD Audio Controller                                            | 245      | 3.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 211      | 2.73%   |
| Nvidia High Definition Audio Controller                                           | 208      | 2.69%   |
| AMD Starship/Matisse HD Audio Controller                                          | 201      | 2.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 195      | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 185      | 2.4%    |
| Nvidia MCP61 High Definition Audio                                                | 173      | 2.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 170      | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 168      | 2.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 155      | 2.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 140      | 1.81%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 138      | 1.79%   |
| AMD FCH Azalia Controller                                                         | 138      | 1.79%   |
| Intel 200 Series PCH HD Audio                                                     | 135      | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                        | 129      | 1.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 113      | 1.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 100      | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                     | 95       | 1.23%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 88       | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                                     | 84       | 1.09%   |
| Generalplus Technology USB Audio Device                                           | 75       | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 72       | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                     | 59       | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 58       | 0.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 52       | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                                     | 50       | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                                | 48       | 0.62%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 48       | 0.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 48       | 0.62%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 45       | 0.58%   |
| Nvidia GM206 High Definition Audio Controller                                     | 44       | 0.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 44       | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                                | 43       | 0.56%   |
| AMD Kabini HDMI/DP Audio                                                          | 40       | 0.52%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 39       | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 608      | 29.12%  |
| Kingston            | 530      | 25.38%  |
| Corsair             | 164      | 7.85%   |
| Smart               | 129      | 6.18%   |
| Crucial             | 96       | 4.6%    |
| A-DATA Technology   | 75       | 3.59%   |
| Samsung Electronics | 63       | 3.02%   |
| SK hynix            | 56       | 2.68%   |
| Team                | 44       | 2.11%   |
| G.Skill             | 34       | 1.63%   |
| Unknown             | 32       | 1.53%   |
| Micron Technology   | 28       | 1.34%   |
| Teikon              | 25       | 1.2%    |
| Multilaser          | 20       | 0.96%   |
| Patriot             | 13       | 0.62%   |
| Atermiter           | 12       | 0.57%   |
| Apacer              | 10       | 0.48%   |
| Avant               | 9        | 0.43%   |
| GeIL                | 8        | 0.38%   |
| Kreton              | 7        | 0.34%   |
| RZX                 | 6        | 0.29%   |
| HBS                 | 6        | 0.29%   |
| CSX                 | 6        | 0.29%   |
| Unknown (82B5)      | 5        | 0.24%   |
| Nanya Technology    | 5        | 0.24%   |
| GLOWAY              | 5        | 0.24%   |
| Elpida              | 5        | 0.24%   |
| Asgard              | 5        | 0.24%   |
| Qbex                | 4        | 0.19%   |
| PUSKILL             | 4        | 0.19%   |
| Positivo            | 4        | 0.19%   |
| MemoWise            | 4        | 0.19%   |
| Kllisre             | 4        | 0.19%   |
| Kingmax             | 4        | 0.19%   |
| Hewlett-Packard     | 4        | 0.19%   |
| Smart Modular       | 3        | 0.14%   |
| AMD                 | 3        | 0.14%   |
| Transcend           | 2        | 0.1%    |
| Silicon Power       | 2        | 0.1%    |
| SanDisk             | 2        | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 45       | 1.94%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 33       | 1.42%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 32       | 1.38%   |
| Unknown                                                  | 32       | 1.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 31       | 1.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 30       | 1.29%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 30       | 1.29%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 29       | 1.25%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 26       | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 18       | 0.77%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s      | 18       | 0.77%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 17       | 0.73%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s             | 17       | 0.73%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 16       | 0.69%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 16       | 0.69%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 15       | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 15       | 0.65%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 14       | 0.6%    |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 13       | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 13       | 0.56%   |
| Kingston RAM 99U5474-028.A00LF 4096MB DIMM DDR3 1333MT/s | 13       | 0.56%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s    | 13       | 0.56%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 12       | 0.52%   |
| Smart RAM SH564568FH8N0QHSCR 2GB DIMM DDR3 1333MT/s      | 12       | 0.52%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s      | 12       | 0.52%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 11       | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 11       | 0.47%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 11       | 0.47%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s            | 11       | 0.47%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 11       | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 10       | 0.43%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s      | 10       | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 9        | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 9        | 0.39%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 9        | 0.39%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 9        | 0.39%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s      | 9        | 0.39%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s        | 9        | 0.39%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1600MT/s      | 9        | 0.39%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s    | 9        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 729      | 39.99%  |
| DDR4         | 604      | 33.13%  |
| Unknown      | 188      | 10.31%  |
| DDR2         | 140      | 7.68%   |
| SDRAM        | 122      | 6.69%   |
| DDR          | 32       | 1.76%   |
| DDR5         | 4        | 0.22%   |
| LPDDR4       | 2        | 0.11%   |
| DRAM         | 1        | 0.05%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1731     | 96.01%  |
| SODIMM       | 66       | 3.66%   |
| RIMM         | 4        | 0.22%   |
| Row Of Chips | 1        | 0.06%   |
| FB-DIMM      | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 678      | 33.22%  |
| 8192  | 642      | 31.46%  |
| 2048  | 418      | 20.48%  |
| 16384 | 160      | 7.84%   |
| 1024  | 74       | 3.63%   |
| 32768 | 54       | 2.65%   |
| 512   | 11       | 0.54%   |
| 256   | 2        | 0.1%    |
| 1536  | 1        | 0.05%   |
| 16    | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 408      | 20.18%  |
| 1600    | 355      | 17.56%  |
| Unknown | 155      | 7.67%   |
| 2400    | 129      | 6.38%   |
| 800     | 98       | 4.85%   |
| 667     | 86       | 4.25%   |
| 2667    | 81       | 4.01%   |
| 3400    | 68       | 3.36%   |
| 3200    | 65       | 3.21%   |
| 3000    | 62       | 3.07%   |
| 2133    | 62       | 3.07%   |
| 3600    | 57       | 2.82%   |
| 1867    | 40       | 1.98%   |
| 3466    | 35       | 1.73%   |
| 1866    | 32       | 1.58%   |
| 2800    | 29       | 1.43%   |
| 1066    | 26       | 1.29%   |
| 2933    | 20       | 0.99%   |
| 1067    | 20       | 0.99%   |
| 400     | 18       | 0.89%   |
| 3151    | 17       | 0.84%   |
| 2666    | 16       | 0.79%   |
| 3733    | 15       | 0.74%   |
| 333     | 15       | 0.74%   |
| 533     | 14       | 0.69%   |
| 3800    | 13       | 0.64%   |
| 3334    | 9        | 0.45%   |
| 1334    | 7        | 0.35%   |
| 3333    | 6        | 0.3%    |
| 3266    | 5        | 0.25%   |
| 41632   | 4        | 0.2%    |
| 5354    | 3        | 0.15%   |
| 3066    | 3        | 0.15%   |
| 2733    | 3        | 0.15%   |
| 2132    | 3        | 0.15%   |
| 49926   | 2        | 0.1%    |
| 6000    | 2        | 0.1%    |
| 4800    | 2        | 0.1%    |
| 3100    | 2        | 0.1%    |
| 3007    | 2        | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 91       | 47.64%  |
| Seiko Epson           | 45       | 23.56%  |
| Samsung Electronics   | 16       | 8.38%   |
| Canon                 | 14       | 7.33%   |
| Brother Industries    | 14       | 7.33%   |
| Lexmark International | 3        | 1.57%   |
| QinHeng Electronics   | 2        | 1.05%   |
| Apple                 | 2        | 1.05%   |
| Ricoh                 | 1        | 0.52%   |
| Prolific Technology   | 1        | 0.52%   |
| Oki Data              | 1        | 0.52%   |
| ARGOX                 | 1        | 0.52%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson L396 Series           | 9        | 4.69%   |
| HP DeskJet 2130 series            | 8        | 4.17%   |
| Seiko Epson L365 Series           | 7        | 3.65%   |
| HP Ink Tank Wireless 410 series   | 7        | 3.65%   |
| Seiko Epson L355 Series           | 6        | 3.13%   |
| Seiko Epson ET-2710 Series        | 6        | 3.13%   |
| HP Deskjet 3050 J610 series       | 5        | 2.6%    |
| HP Deskjet 2540 series            | 5        | 2.6%    |
| Canon G3010 series                | 5        | 2.6%    |
| Samsung SCX-4200 series           | 4        | 2.08%   |
| Samsung M2070 Series              | 4        | 2.08%   |
| HP LaserJet P1005                 | 4        | 2.08%   |
| HP DeskJet F4100 Printer series   | 4        | 2.08%   |
| HP DeskJet 2700 series            | 4        | 2.08%   |
| HP DeskJet 2600 series            | 4        | 2.08%   |
| HP Deskjet 2050 J510              | 4        | 2.08%   |
| HP LaserJet Professional P1102w   | 3        | 1.56%   |
| HP LaserJet 1020                  | 3        | 1.56%   |
| HP Deskjet F4400 series           | 3        | 1.56%   |
| HP DeskJet F4200 series           | 3        | 1.56%   |
| HP DeskJet 3630 series            | 3        | 1.56%   |
| Brother HL-1200 series            | 3        | 1.56%   |
| Seiko Epson XP-243 245 247 Series | 2        | 1.04%   |
| Seiko Epson L375 Series           | 2        | 1.04%   |
| Seiko Epson L3110 Series          | 2        | 1.04%   |
| Seiko Epson L220 Series           | 2        | 1.04%   |
| Seiko Epson L210 Series           | 2        | 1.04%   |
| Samsung SCX-3200 Series           | 2        | 1.04%   |
| Samsung M2020 Series              | 2        | 1.04%   |
| QinHeng CH340S                    | 2        | 1.04%   |
| HP Printing Support               | 2        | 1.04%   |
| HP LaserJet 1018                  | 2        | 1.04%   |
| HP Deskjet 4620 series            | 2        | 1.04%   |
| HP DeskJet 1110 series            | 2        | 1.04%   |
| Canon PIXMA MG3000 series         | 2        | 1.04%   |
| Brother HL-1210W series           | 2        | 1.04%   |
| Brother DCP-7055 scanner/printer  | 2        | 1.04%   |
| Apple Gamesir-T1s 2.0b            | 2        | 1.04%   |
| Seiko Epson XP-211 214 216 Series | 1        | 0.52%   |
| Seiko Epson Printer               | 1        | 0.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 6        | 40%     |
| Canon           | 6        | 40%     |
| Seiko Epson     | 2        | 13.33%  |
| Mustek Systems  | 1        | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                        | 4        | 26.67%  |
| Canon CanoScan LIDE 25                                  | 4        | 26.67%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 6.67%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 6.67%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 6.67%   |
| HP ScanJet G4050                                        | 1        | 6.67%   |
| HP ScanJet 3800c                                        | 1        | 6.67%   |
| Canon CanoScan LiDE 210                                 | 1        | 6.67%   |
| Canon CanoScan LiDE 110                                 | 1        | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 212      | 31.59%  |
| Generalplus Technology        | 52       | 7.75%   |
| Microsoft                     | 42       | 6.26%   |
| Samsung Electronics           | 37       | 5.51%   |
| Z-Star Microelectronics       | 36       | 5.37%   |
| Microdia                      | 35       | 5.22%   |
| Aveo Technology               | 28       | 4.17%   |
| GEMBIRD                       | 18       | 2.68%   |
| Cubeternet                    | 16       | 2.38%   |
| Jieli Technology              | 14       | 2.09%   |
| Chicony Electronics           | 14       | 2.09%   |
| Sunplus Innovation Technology | 13       | 1.94%   |
| Pixart Imaging                | 11       | 1.64%   |
| LG Electronics                | 8        | 1.19%   |
| Genesys Logic                 | 8        | 1.19%   |
| Apple                         | 8        | 1.19%   |
| Alcor Micro                   | 8        | 1.19%   |
| Arkmicro Technologies         | 7        | 1.04%   |
| MacroSilicon                  | 6        | 0.89%   |
| KYE Systems (Mouse Systems)   | 6        | 0.89%   |
| SunplusIT                     | 5        | 0.75%   |
| Realtek Semiconductor         | 5        | 0.75%   |
| Philips (or NXP)              | 5        | 0.75%   |
| Hewlett-Packard               | 5        | 0.75%   |
| Acer                          | 5        | 0.75%   |
| Sunplus Technology            | 4        | 0.6%    |
| Sonix Technology              | 4        | 0.6%    |
| Lenovo                        | 4        | 0.6%    |
| Huawei Technologies           | 4        | 0.6%    |
| Silicon Motion                | 3        | 0.45%   |
| IMC Networks                  | 3        | 0.45%   |
| GenesysLogic Technology       | 3        | 0.45%   |
| Creative Technology           | 3        | 0.45%   |
| Asuscom Network               | 3        | 0.45%   |
| ARC International             | 3        | 0.45%   |
| A4Tech                        | 3        | 0.45%   |
| Xiongmai                      | 2        | 0.3%    |
| WCM_USB                       | 2        | 0.3%    |
| WaveRider Communications      | 2        | 0.3%    |
| Mimaki Engineering            | 2        | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 82       | 12.17%  |
| Logitech HD Pro Webcam C920              | 46       | 6.82%   |
| Generalplus GENERAL WEBCAM               | 40       | 5.93%   |
| Samsung Galaxy A5 (MTP)                  | 36       | 5.34%   |
| Logitech C922 Pro Stream Webcam          | 20       | 2.97%   |
| Z-Star Venus USB2.0 Camera               | 18       | 2.67%   |
| GEMBIRD USB2.0 PC CAMERA                 | 16       | 2.37%   |
| Jieli USB PHY 2.0                        | 14       | 2.08%   |
| Aveo USB2.0 Camera                       | 14       | 2.08%   |
| Logitech BRIO Ultra HD Webcam            | 12       | 1.78%   |
| Generalplus 808 Camera #9 (web-cam mode) | 12       | 1.78%   |
| Logitech HD Webcam C525                  | 11       | 1.63%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 10       | 1.48%   |
| Microdia USB 2.0 Camera                  | 9        | 1.34%   |
| Microdia Integrated Camera               | 9        | 1.34%   |
| Logitech Webcam C925e                    | 9        | 1.34%   |
| Logitech C920 PRO HD Webcam              | 9        | 1.34%   |
| Z-Star Vimicro USB Camera (Altair)       | 8        | 1.19%   |
| Microsoft LifeCam VX-500 [1357]          | 8        | 1.19%   |
| Sunplus WEMISS CM-A1                     | 7        | 1.04%   |
| Microsoft LifeCam VX-2000                | 7        | 1.04%   |
| Microsoft LifeCam HD-3000                | 7        | 1.04%   |
| Chicony HP Webcam                        | 7        | 1.04%   |
| Aveo Camera                              | 7        | 1.04%   |
| Microsoft LifeCam VX-800                 | 6        | 0.89%   |
| Microsoft LifeCam HD-5000                | 6        | 0.89%   |
| Microsoft LifeCam Cinema                 | 6        | 0.89%   |
| Logitech Logi Webcam C920e               | 6        | 0.89%   |
| Cubeternet GL-UPC822 UVC WebCam          | 6        | 0.89%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 6        | 0.89%   |
| Philips (or NXP) Webcam SPC530NC         | 5        | 0.74%   |
| Microdia Webcam Vitade AF                | 5        | 0.74%   |
| Microdia Sonix USB 2.0 Camera            | 5        | 0.74%   |
| MacroSilicon USB Video                   | 5        | 0.74%   |
| Aveo UVC camera (Bresser microscope)     | 5        | 0.74%   |
| SunplusIT USB camera                     | 4        | 0.59%   |
| Lenovo FHD Webcam Audio                  | 4        | 0.59%   |
| Huawei UVC Camera                        | 4        | 0.59%   |
| Cubeternet WebCam                        | 4        | 0.59%   |
| Cubeternet USB2.0 Camera                 | 4        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Futronic Technology | 1        | 50%     |
| Dell                | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Futronic FS81 Fingerprint Scanner Module       | 1        | 50%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 14       | 40%     |
| Giesecke & Devrient               | 4        | 11.43%  |
| Alcor Micro                       | 4        | 11.43%  |
| SCM Microsystems                  | 3        | 8.57%   |
| Chicony Electronics               | 3        | 8.57%   |
| Watchdata                         | 2        | 5.71%   |
| OmniKey                           | 2        | 5.71%   |
| VASCO Data Security International | 1        | 2.86%   |
| Realtek Semiconductor             | 1        | 2.86%   |
| Aladdin Knowledge Systems         | 1        | 2.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 13       | 37.14%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 11.43%  |
| Giesecke & Devrient StarSign CUT S                              | 3        | 8.57%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 3        | 8.57%   |
| Watchdata USB Key                                               | 2        | 5.71%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 2        | 5.71%   |
| OmniKey CardMan 3021 / 3121                                     | 2        | 5.71%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 2.86%   |
| SCM Microsystems SCR35xx Smart Card Reader                      | 1        | 2.86%   |
| Realtek Semiconductor Smart Card Reader Interface               | 1        | 2.86%   |
| Giesecke & Devrient StarSign CUT                                | 1        | 2.86%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                | 1        | 2.86%   |
| Aladdin Knowledge Systems Token JC                              | 1        | 2.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3836     | 85.47%  |
| 1     | 582      | 12.97%  |
| 2     | 52       | 1.16%   |
| 3     | 11       | 0.25%   |
| 4     | 7        | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 269      | 38.16%  |
| Net/wireless             | 191      | 27.09%  |
| Communication controller | 49       | 6.95%   |
| Unassigned class         | 45       | 6.38%   |
| Sound                    | 25       | 3.55%   |
| Multimedia controller    | 25       | 3.55%   |
| Chipcard                 | 23       | 3.26%   |
| Modem                    | 17       | 2.41%   |
| Camera                   | 16       | 2.27%   |
| Net/ethernet             | 11       | 1.56%   |
| Storage/ide              | 7        | 0.99%   |
| Network                  | 6        | 0.85%   |
| Bluetooth                | 6        | 0.85%   |
| Card reader              | 5        | 0.71%   |
| Storage/raid             | 4        | 0.57%   |
| Wireless                 | 1        | 0.14%   |
| Video                    | 1        | 0.14%   |
| Storage/nvme             | 1        | 0.14%   |
| Storage                  | 1        | 0.14%   |
| Firewire controller      | 1        | 0.14%   |
| Dvb card                 | 1        | 0.14%   |


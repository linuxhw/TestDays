Ubuntu Budgie - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie/Notebook/README.md).

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

Total: 720

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2a95697c62](https://linux-hardware.org/?probe=2a95697c62) | Jul 25, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Alienware     | M11xR3                      | Notebook    | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [d2ed25b6e8](https://linux-hardware.org/?probe=d2ed25b6e8) | Jul 16, 2022 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | Notebook    | [f1dcf09169](https://linux-hardware.org/?probe=f1dcf09169) | Jul 14, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| Google        | Eve                         | Convertible | [be0c82653c](https://linux-hardware.org/?probe=be0c82653c) | Jul 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Dell          | Latitude E7450              | Notebook    | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Positivo      | Q232A                       | Notebook    | [c297e38afb](https://linux-hardware.org/?probe=c297e38afb) | Jun 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [8774fcf3a2](https://linux-hardware.org/?probe=8774fcf3a2) | Jun 27, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | Notebook    | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [add98928e5](https://linux-hardware.org/?probe=add98928e5) | Jun 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [bfecf091a6](https://linux-hardware.org/?probe=bfecf091a6) | Jun 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [3195007eb2](https://linux-hardware.org/?probe=3195007eb2) | May 30, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e97309bc05](https://linux-hardware.org/?probe=e97309bc05) | May 07, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [9505d0e8b7](https://linux-hardware.org/?probe=9505d0e8b7) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [96eae556f2](https://linux-hardware.org/?probe=96eae556f2) | Apr 15, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI           | H81M-E33                    | Desktop     | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | Notebook    | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | Notebook    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | Notebook    | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | Notebook    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| HP            | 8158 A01                    | Mini pc     | [3ba669d072](https://linux-hardware.org/?probe=3ba669d072) | Mar 20, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [ca76b3a899](https://linux-hardware.org/?probe=ca76b3a899) | Mar 18, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [f444e85d64](https://linux-hardware.org/?probe=f444e85d64) | Mar 18, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| HP            | Pavilion dm4                | Notebook    | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | Notebook    | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [5be284f90d](https://linux-hardware.org/?probe=5be284f90d) | Feb 26, 2022 |
| Microsoft     | Surface Book                | Tablet      | [a94d46ec1d](https://linux-hardware.org/?probe=a94d46ec1d) | Feb 25, 2022 |
| Microsoft     | Surface Book                | Tablet      | [f62d16f3b1](https://linux-hardware.org/?probe=f62d16f3b1) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9b8714532b](https://linux-hardware.org/?probe=9b8714532b) | Feb 20, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Dell          | 0RW199                      | Desktop     | [5cf70558c8](https://linux-hardware.org/?probe=5cf70558c8) | Feb 14, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | Notebook    | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [6f4c9d5553](https://linux-hardware.org/?probe=6f4c9d5553) | Jan 27, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | Notebook    | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | Notebook    | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [d7414a7101](https://linux-hardware.org/?probe=d7414a7101) | Jan 15, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [e4d4e112f7](https://linux-hardware.org/?probe=e4d4e112f7) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ecaadc9cb3](https://linux-hardware.org/?probe=ecaadc9cb3) | Jan 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [bd181b10da](https://linux-hardware.org/?probe=bd181b10da) | Jan 04, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| Teclast       | X6 plus                     | Tablet      | [d476f875d2](https://linux-hardware.org/?probe=d476f875d2) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ddf55561ad](https://linux-hardware.org/?probe=ddf55561ad) | Dec 21, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [8e1c093fb8](https://linux-hardware.org/?probe=8e1c093fb8) | Dec 20, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [7eabc884a6](https://linux-hardware.org/?probe=7eabc884a6) | Dec 19, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [d416ec7878](https://linux-hardware.org/?probe=d416ec7878) | Dec 17, 2021 |
| HP            | Pavilion dm1                | Notebook    | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [2aaaff47a4](https://linux-hardware.org/?probe=2aaaff47a4) | Dec 17, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d34989fcaa](https://linux-hardware.org/?probe=d34989fcaa) | Dec 16, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7587f8f78a](https://linux-hardware.org/?probe=7587f8f78a) | Dec 16, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [bd9653afdd](https://linux-hardware.org/?probe=bd9653afdd) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | Notebook    | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [ade1f1db1a](https://linux-hardware.org/?probe=ade1f1db1a) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [126c160ef3](https://linux-hardware.org/?probe=126c160ef3) | Dec 04, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [945995abf6](https://linux-hardware.org/?probe=945995abf6) | Dec 02, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [35a82530fb](https://linux-hardware.org/?probe=35a82530fb) | Dec 02, 2021 |
| Sony          | VPCEJ1L1E                   | Notebook    | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | Notebook    | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [e62e98d46d](https://linux-hardware.org/?probe=e62e98d46d) | Nov 30, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3cea520e1f](https://linux-hardware.org/?probe=3cea520e1f) | Nov 29, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3fbd626bf6](https://linux-hardware.org/?probe=3fbd626bf6) | Nov 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [ba184983ea](https://linux-hardware.org/?probe=ba184983ea) | Nov 27, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| HP            | 0A5Ch                       | Desktop     | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [61f2f6aeab](https://linux-hardware.org/?probe=61f2f6aeab) | Nov 19, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f18f314bc7](https://linux-hardware.org/?probe=f18f314bc7) | Nov 01, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [8ecbd29abd](https://linux-hardware.org/?probe=8ecbd29abd) | Oct 29, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90e49546c2](https://linux-hardware.org/?probe=90e49546c2) | Oct 21, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [cc51204b2c](https://linux-hardware.org/?probe=cc51204b2c) | Oct 20, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | 0A5Ch                       | Desktop     | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP            | 0A5Ch                       | Desktop     | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4cb5912db3](https://linux-hardware.org/?probe=4cb5912db3) | Oct 15, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [feb38e948d](https://linux-hardware.org/?probe=feb38e948d) | Sep 13, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [17c9df42cd](https://linux-hardware.org/?probe=17c9df42cd) | Sep 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [01d203a7af](https://linux-hardware.org/?probe=01d203a7af) | Sep 07, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | Notebook    | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Fujitsu       | LIFEBOOK U9311A             | Notebook    | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [7257c7b0bb](https://linux-hardware.org/?probe=7257c7b0bb) | Aug 20, 2021 |
| Google        | Peppy                       | Notebook    | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [15b41a9b17](https://linux-hardware.org/?probe=15b41a9b17) | Aug 16, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [dcbe85bfb3](https://linux-hardware.org/?probe=dcbe85bfb3) | Aug 16, 2021 |
| TUXEDO        | Book XP1511                 | Notebook    | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53a8be279f](https://linux-hardware.org/?probe=53a8be279f) | Aug 12, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | Notebook    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| TUXEDO        | Book_XA1510                 | Notebook    | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | Notebook    | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6f7de51af1](https://linux-hardware.org/?probe=6f7de51af1) | Jul 25, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [18951b50fd](https://linux-hardware.org/?probe=18951b50fd) | Jul 23, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e0f1466068](https://linux-hardware.org/?probe=e0f1466068) | Jul 09, 2021 |
| HP            | 1588h                       | Desktop     | [28a2da9b7f](https://linux-hardware.org/?probe=28a2da9b7f) | Jul 05, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [d90efe186a](https://linux-hardware.org/?probe=d90efe186a) | Jun 25, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | Notebook    | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [6a63f48182](https://linux-hardware.org/?probe=6a63f48182) | May 29, 2021 |
| AWOW          | AK41                        | Notebook    | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | Notebook    | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | Notebook    | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [75877fb3b1](https://linux-hardware.org/?probe=75877fb3b1) | May 19, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [91cee123e9](https://linux-hardware.org/?probe=91cee123e9) | May 19, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | Notebook    | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ec195ffe95](https://linux-hardware.org/?probe=ec195ffe95) | May 12, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | Notebook    | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | Notebook    | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [8260769b47](https://linux-hardware.org/?probe=8260769b47) | May 01, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [a2fb8f6b18](https://linux-hardware.org/?probe=a2fb8f6b18) | May 01, 2021 |
| Dell          | Latitude D531               | Notebook    | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | Notebook    | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [289b0a89c0](https://linux-hardware.org/?probe=289b0a89c0) | Apr 25, 2021 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [c2c4591ef9](https://linux-hardware.org/?probe=c2c4591ef9) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | Notebook    | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9c8b7bc48a](https://linux-hardware.org/?probe=9c8b7bc48a) | Apr 06, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | Notebook    | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| Huanan        | X79 249PC V2.2              | Desktop     | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [104c966a1a](https://linux-hardware.org/?probe=104c966a1a) | Mar 30, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [87168e11ee](https://linux-hardware.org/?probe=87168e11ee) | Mar 26, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [72adf1881e](https://linux-hardware.org/?probe=72adf1881e) | Mar 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f769aaeedd](https://linux-hardware.org/?probe=f769aaeedd) | Mar 26, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c755699d3](https://linux-hardware.org/?probe=4c755699d3) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP            | 3031h                       | Desktop     | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [0cc10a7f8b](https://linux-hardware.org/?probe=0cc10a7f8b) | Mar 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [26c69c1a34](https://linux-hardware.org/?probe=26c69c1a34) | Mar 07, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [d9cc78fcff](https://linux-hardware.org/?probe=d9cc78fcff) | Mar 07, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| HP            | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [bc79c52365](https://linux-hardware.org/?probe=bc79c52365) | Mar 04, 2021 |
| Timi          | TM1701                      | Notebook    | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| Dell          | 0KJCC5 A00                  | Desktop     | [5587c00381](https://linux-hardware.org/?probe=5587c00381) | Mar 02, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d1866f15b4](https://linux-hardware.org/?probe=d1866f15b4) | Mar 02, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | Notebook    | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6d24d073b](https://linux-hardware.org/?probe=c6d24d073b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | Notebook    | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| BCM           | RX965Q                      | Desktop     | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [10e0380862](https://linux-hardware.org/?probe=10e0380862) | Feb 19, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASUSTek       | H61M-A                      | Desktop     | [2b8de1db1f](https://linux-hardware.org/?probe=2b8de1db1f) | Feb 19, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [745c1185fd](https://linux-hardware.org/?probe=745c1185fd) | Feb 18, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [d470929ba8](https://linux-hardware.org/?probe=d470929ba8) | Feb 14, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Lenovo        | 36F2 SDK0J40700 WIN 3258... | All in one  | [f172b5b1ea](https://linux-hardware.org/?probe=f172b5b1ea) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | Notebook    | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [13979999ed](https://linux-hardware.org/?probe=13979999ed) | Feb 07, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [f48bc9fc78](https://linux-hardware.org/?probe=f48bc9fc78) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [1f3b4b8203](https://linux-hardware.org/?probe=1f3b4b8203) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [005301f0e8](https://linux-hardware.org/?probe=005301f0e8) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [48a778609f](https://linux-hardware.org/?probe=48a778609f) | Feb 06, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | Notebook    | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| Positivo      | C14CR21TV                   | Notebook    | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3d2867cd98](https://linux-hardware.org/?probe=3d2867cd98) | Jan 30, 2021 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [bb89e367c8](https://linux-hardware.org/?probe=bb89e367c8) | Jan 17, 2021 |
| Dell          | XPS L322X                   | Notebook    | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [3a07ab383e](https://linux-hardware.org/?probe=3a07ab383e) | Jan 15, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bb66f59b76](https://linux-hardware.org/?probe=bb66f59b76) | Jan 12, 2021 |
| HP            | 1589                        | Desktop     | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| MSI           | GE70 2PC\2PE                | Notebook    | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bff63b3c48](https://linux-hardware.org/?probe=bff63b3c48) | Jan 05, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| eMachines     | EZ1600                      | All in one  | [2c5f74bdac](https://linux-hardware.org/?probe=2c5f74bdac) | Jan 01, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Toshiba       | Satellite P750              | Notebook    | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0d1e39a79a](https://linux-hardware.org/?probe=0d1e39a79a) | Dec 27, 2020 |
| HP            | Pavilion 17                 | Notebook    | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| eMachines     | EZ1600                      | All in one  | [2181178e2b](https://linux-hardware.org/?probe=2181178e2b) | Dec 25, 2020 |
| Dell          | 0PK096                      | Desktop     | [e1a520e089](https://linux-hardware.org/?probe=e1a520e089) | Dec 24, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [6260a9fb0f](https://linux-hardware.org/?probe=6260a9fb0f) | Dec 22, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c671dc11ee](https://linux-hardware.org/?probe=c671dc11ee) | Dec 20, 2020 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [05c93972e0](https://linux-hardware.org/?probe=05c93972e0) | Dec 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | Notebook    | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | Notebook    | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [25ff6d84d0](https://linux-hardware.org/?probe=25ff6d84d0) | Dec 07, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | Notebook    | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| ASRock        | P67 Extreme4                | Desktop     | [ca2f3a785a](https://linux-hardware.org/?probe=ca2f3a785a) | Dec 06, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [77dc96c206](https://linux-hardware.org/?probe=77dc96c206) | Nov 27, 2020 |
| LattePanda    | Alpha                       | Desktop     | [706f930815](https://linux-hardware.org/?probe=706f930815) | Nov 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c620f65d2b](https://linux-hardware.org/?probe=c620f65d2b) | Nov 25, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| LattePanda    | Alpha                       | Desktop     | [a5c3e54e65](https://linux-hardware.org/?probe=a5c3e54e65) | Nov 24, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [304945ac43](https://linux-hardware.org/?probe=304945ac43) | Nov 23, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [8bbc1a2d1c](https://linux-hardware.org/?probe=8bbc1a2d1c) | Nov 22, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [732043cc5f](https://linux-hardware.org/?probe=732043cc5f) | Nov 21, 2020 |
| ASUSTek       | P8Z68-V                     | Desktop     | [643bb20dc1](https://linux-hardware.org/?probe=643bb20dc1) | Nov 20, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Sony          | SVS13A25PBS                 | Notebook    | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | Notebook    | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [eb2134b274](https://linux-hardware.org/?probe=eb2134b274) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Apple         | Mac-F2218FC8                | All in one  | [b72a5d9506](https://linux-hardware.org/?probe=b72a5d9506) | Oct 31, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | Notebook    | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aead0dde26](https://linux-hardware.org/?probe=aead0dde26) | Oct 27, 2020 |
| HP            | ZBook 14                    | Notebook    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| HP            | Stream 7 Tablet             | Tablet      | [1cb5fb4518](https://linux-hardware.org/?probe=1cb5fb4518) | Oct 25, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [a5246866a5](https://linux-hardware.org/?probe=a5246866a5) | Oct 21, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [19879c3493](https://linux-hardware.org/?probe=19879c3493) | Oct 21, 2020 |
| Dell          | Latitude 5400               | Notebook    | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [69ed04c55d](https://linux-hardware.org/?probe=69ed04c55d) | Oct 20, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| ASRock        | Q1900B-ITX                  | Desktop     | [527411a589](https://linux-hardware.org/?probe=527411a589) | Oct 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [f82db8cb1c](https://linux-hardware.org/?probe=f82db8cb1c) | Oct 13, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [9d2f2dbd87](https://linux-hardware.org/?probe=9d2f2dbd87) | Oct 12, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | Notebook    | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | Notebook    | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| Dell          | 0M9KCM A00                  | Desktop     | [f884d19586](https://linux-hardware.org/?probe=f884d19586) | Oct 02, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| MSI           | Modern 14 A10RB             | Notebook    | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | Notebook    | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Dell          | Latitude 5400               | Notebook    | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| Dell          | 0RY007                      | Desktop     | [b1ca551538](https://linux-hardware.org/?probe=b1ca551538) | Sep 22, 2020 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| HP            | ProBook 4730s               | Notebook    | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | Notebook    | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Radxa         | ROCK Pi 4A                  | Soc         | [b335776d4a](https://linux-hardware.org/?probe=b335776d4a) | Sep 14, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART       | 6.0                         | Desktop     | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI           | Z97 GAMING 5                | Desktop     | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| HP            | Pavilion g6                 | Notebook    | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [bc9c588fd8](https://linux-hardware.org/?probe=bc9c588fd8) | Aug 30, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | Notebook    | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| Sony          | VPCEK20AL                   | Notebook    | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | Notebook    | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| ASUSTek       | U47A                        | Notebook    | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| Standard      | MT40II                      | Notebook    | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | Notebook    | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Apple         | MacBook3,1                  | Notebook    | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP            | 82F2                        | Desktop     | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0479f5e75d](https://linux-hardware.org/?probe=0479f5e75d) | Jul 26, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | Notebook    | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | Notebook    | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | Notebook    | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| HP            | 3397                        | Desktop     | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP            | 3397                        | Desktop     | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Dell          | G3 3579                     | Notebook    | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | Notebook    | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | Notebook    | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | Notebook    | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [12a4926d36](https://linux-hardware.org/?probe=12a4926d36) | Jul 17, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| Dell          | 0P301D A02                  | Desktop     | [709ca37e1e](https://linux-hardware.org/?probe=709ca37e1e) | Jul 12, 2020 |
| MSI           | GP72 7RE                    | Notebook    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c7cdebaa45](https://linux-hardware.org/?probe=c7cdebaa45) | Jul 09, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | Notebook    | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | Notebook    | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [33d1532efd](https://linux-hardware.org/?probe=33d1532efd) | Jun 23, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [110bf098e8](https://linux-hardware.org/?probe=110bf098e8) | Jun 22, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | Notebook    | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | Notebook    | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | Notebook    | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | Notebook    | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | Notebook    | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | Notebook    | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | Notebook    | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | Notebook    | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Acer          | Aspire ZC-105               | All in one  | [42b2dbab31](https://linux-hardware.org/?probe=42b2dbab31) | Jun 01, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [fbbc2c4d98](https://linux-hardware.org/?probe=fbbc2c4d98) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ca71847ca1](https://linux-hardware.org/?probe=ca71847ca1) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | Notebook    | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | Notebook    | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | Notebook    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | Notebook    | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| ASUSTek       | S400CA                      | Notebook    | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | Notebook    | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Dell          | 0TNXNR A01                  | Desktop     | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | Notebook    | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | Notebook    | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | Notebook    | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [181868c1fe](https://linux-hardware.org/?probe=181868c1fe) | May 05, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | Notebook                    | Notebook    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [7db8dc0e44](https://linux-hardware.org/?probe=7db8dc0e44) | Apr 28, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | Notebook    | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| HP            | 0A80h                       | Desktop     | [f51e29fc6f](https://linux-hardware.org/?probe=f51e29fc6f) | Apr 13, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [c6df4257a4](https://linux-hardware.org/?probe=c6df4257a4) | Apr 11, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | Notebook    | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c17da47049](https://linux-hardware.org/?probe=c17da47049) | Apr 03, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [18f447ca5d](https://linux-hardware.org/?probe=18f447ca5d) | Apr 03, 2020 |
| HP            | 8433 11                     | Desktop     | [e20dd4e4a3](https://linux-hardware.org/?probe=e20dd4e4a3) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [eafaace7ee](https://linux-hardware.org/?probe=eafaace7ee) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [0e29f294ba](https://linux-hardware.org/?probe=0e29f294ba) | Apr 02, 2020 |
| HP            | 84EE 1100                   | All in one  | [870857c93c](https://linux-hardware.org/?probe=870857c93c) | Mar 30, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5b8ef620f7](https://linux-hardware.org/?probe=5b8ef620f7) | Mar 27, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [384177f515](https://linux-hardware.org/?probe=384177f515) | Mar 23, 2020 |
| HP            | Compaq 6720s                | Notebook    | [7a81993a9b](https://linux-hardware.org/?probe=7a81993a9b) | Mar 22, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [477afd03f4](https://linux-hardware.org/?probe=477afd03f4) | Mar 21, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [efb8737ca2](https://linux-hardware.org/?probe=efb8737ca2) | Mar 20, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | Notebook    | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| ASUSTek       | X750JB                      | Notebook    | [6d8e7e2bf9](https://linux-hardware.org/?probe=6d8e7e2bf9) | Mar 15, 2020 |
| MSI           | Z270-A PRO                  | Desktop     | [5e41eb4c66](https://linux-hardware.org/?probe=5e41eb4c66) | Mar 14, 2020 |
| Dell          | Latitude 5400               | Notebook    | [3bda0aef33](https://linux-hardware.org/?probe=3bda0aef33) | Mar 14, 2020 |
| HP            | 2000                        | Notebook    | [fa3539bb75](https://linux-hardware.org/?probe=fa3539bb75) | Mar 14, 2020 |
| Standard      | MT40II                      | Notebook    | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [210b1c0abf](https://linux-hardware.org/?probe=210b1c0abf) | Mar 13, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [9ca13583bb](https://linux-hardware.org/?probe=9ca13583bb) | Mar 09, 2020 |
| Dell          | Latitude E6420              | Notebook    | [7653562a2f](https://linux-hardware.org/?probe=7653562a2f) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e008a514e](https://linux-hardware.org/?probe=1e008a514e) | Mar 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [01c8982ddb](https://linux-hardware.org/?probe=01c8982ddb) | Mar 06, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4b844d95eb](https://linux-hardware.org/?probe=4b844d95eb) | Mar 05, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [b88f46d2eb](https://linux-hardware.org/?probe=b88f46d2eb) | Mar 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1dba6c5acf](https://linux-hardware.org/?probe=1dba6c5acf) | Mar 03, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [5a7b311c84](https://linux-hardware.org/?probe=5a7b311c84) | Mar 02, 2020 |
| ASUSTek       | N751JK                      | Notebook    | [a08a81ed83](https://linux-hardware.org/?probe=a08a81ed83) | Mar 01, 2020 |
| eMachines     | EL1852G                     | Desktop     | [e90ac3f652](https://linux-hardware.org/?probe=e90ac3f652) | Feb 27, 2020 |
| HP            | ENVY x360 Convertible       | Convertible | [d98a9e0c48](https://linux-hardware.org/?probe=d98a9e0c48) | Feb 27, 2020 |
| Intel         | DQ965CO AAD34641-506        | Desktop     | [3c3c53b8e5](https://linux-hardware.org/?probe=3c3c53b8e5) | Feb 26, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [45382a84f3](https://linux-hardware.org/?probe=45382a84f3) | Feb 21, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [002a2b6abe](https://linux-hardware.org/?probe=002a2b6abe) | Feb 21, 2020 |
| HP            | 2215                        | Desktop     | [f9ecf106d2](https://linux-hardware.org/?probe=f9ecf106d2) | Feb 19, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [9e101537c5](https://linux-hardware.org/?probe=9e101537c5) | Feb 17, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [e38723516e](https://linux-hardware.org/?probe=e38723516e) | Feb 17, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [aef314a65c](https://linux-hardware.org/?probe=aef314a65c) | Feb 17, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [31a6b6bac8](https://linux-hardware.org/?probe=31a6b6bac8) | Feb 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [6cfda70306](https://linux-hardware.org/?probe=6cfda70306) | Feb 15, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [ac2755b222](https://linux-hardware.org/?probe=ac2755b222) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [317f9ded14](https://linux-hardware.org/?probe=317f9ded14) | Feb 12, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [81d2b1c515](https://linux-hardware.org/?probe=81d2b1c515) | Jan 25, 2020 |
| Intel         | ChiefRiver                  | Desktop     | [1ca590a614](https://linux-hardware.org/?probe=1ca590a614) | Jan 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [5603e706a3](https://linux-hardware.org/?probe=5603e706a3) | Jan 19, 2020 |
| Dell          | 0C27VV A01                  | Desktop     | [b896b0fef0](https://linux-hardware.org/?probe=b896b0fef0) | Jan 18, 2020 |
| Gigabyte      | MSH87TN-00                  | Desktop     | [624e731bcd](https://linux-hardware.org/?probe=624e731bcd) | Jan 16, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [df0bc17152](https://linux-hardware.org/?probe=df0bc17152) | Jan 13, 2020 |
| HP            | 2000                        | Notebook    | [adde2680e0](https://linux-hardware.org/?probe=adde2680e0) | Jan 08, 2020 |
| Lenovo        | ThinkPad T530 23943V0       | Notebook    | [fdb43e275c](https://linux-hardware.org/?probe=fdb43e275c) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [282e4941e2](https://linux-hardware.org/?probe=282e4941e2) | Dec 27, 2019 |
| HP            | Compaq 8460p USAO           | Notebook    | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [a6b5f083ca](https://linux-hardware.org/?probe=a6b5f083ca) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [2c44aa3122](https://linux-hardware.org/?probe=2c44aa3122) | Nov 21, 2019 |
| Supermicro    | X9DRT                       | Server      | [f5f0a90676](https://linux-hardware.org/?probe=f5f0a90676) | Nov 19, 2019 |
| Dell          | Inspiron 5559               | Notebook    | [6571c933d2](https://linux-hardware.org/?probe=6571c933d2) | Mar 08, 2019 |
| ASUSTek       | T102HA                      | Tablet      | [7c47ab2fd4](https://linux-hardware.org/?probe=7c47ab2fd4) | Jun 14, 2018 |
| Dell          | 0G9322                      | Desktop     | [62b841a44f](https://linux-hardware.org/?probe=62b841a44f) | Jun 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 246       | 48.33%  |
| Ubuntu Budgie 20.10 | 61        | 11.98%  |
| Ubuntu Budgie 21.10 | 55        | 10.81%  |
| Ubuntu Budgie 22.04 | 40        | 7.86%   |
| Ubuntu Budgie 18.04 | 38        | 7.47%   |
| Ubuntu Budgie 21.04 | 35        | 6.88%   |
| Ubuntu Budgie 19.10 | 29        | 5.7%    |
| Ubuntu Budgie       | 3         | 0.59%   |
| Ubuntu Budgie 16.04 | 2         | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 490       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 27        | 4.87%   |
| 5.3.0-40-generic  | 15        | 2.71%   |
| 5.13.0-22-generic | 14        | 2.53%   |
| 5.4.0-40-generic  | 13        | 2.35%   |
| 5.15.0-27-generic | 11        | 1.99%   |
| 5.4.0-52-generic  | 10        | 1.81%   |
| 5.4.0-37-generic  | 10        | 1.81%   |
| 5.13.0-19-generic | 10        | 1.81%   |
| 5.4.0-58-generic  | 9         | 1.62%   |
| 5.4.0-48-generic  | 9         | 1.62%   |
| 5.4.0-29-generic  | 9         | 1.62%   |
| 5.13.0-39-generic | 9         | 1.62%   |
| 5.8.0-48-generic  | 8         | 1.44%   |
| 5.8.0-44-generic  | 8         | 1.44%   |
| 5.8.0-41-generic  | 8         | 1.44%   |
| 5.13.0-40-generic | 8         | 1.44%   |
| 5.13.0-30-generic | 8         | 1.44%   |
| 5.13.0-28-generic | 8         | 1.44%   |
| 5.8.0-43-generic  | 7         | 1.26%   |
| 5.4.0-47-generic  | 7         | 1.26%   |
| 5.4.0-33-generic  | 7         | 1.26%   |
| 5.4.0-31-generic  | 7         | 1.26%   |
| 5.8.0-53-generic  | 6         | 1.08%   |
| 5.8.0-45-generic  | 6         | 1.08%   |
| 5.8.0-29-generic  | 6         | 1.08%   |
| 5.15.0-30-generic | 6         | 1.08%   |
| 5.13.0-35-generic | 6         | 1.08%   |
| 5.11.0-41-generic | 6         | 1.08%   |
| 5.8.0-33-generic  | 5         | 0.9%    |
| 5.8.0-25-generic  | 5         | 0.9%    |
| 5.4.0-91-generic  | 5         | 0.9%    |
| 5.4.0-45-generic  | 5         | 0.9%    |
| 5.3.0-42-generic  | 5         | 0.9%    |
| 5.3.0-26-generic  | 5         | 0.9%    |
| 5.15.0-39-generic | 5         | 0.9%    |
| 5.11.0-22-generic | 5         | 0.9%    |
| 5.11.0-16-generic | 5         | 0.9%    |
| 5.8.0-59-generic  | 4         | 0.72%   |
| 5.8.0-26-generic  | 4         | 0.72%   |
| 5.4.0-72-generic  | 4         | 0.72%   |
| 5.4.0-66-generic  | 4         | 0.72%   |
| 5.4.0-59-generic  | 4         | 0.72%   |
| 5.4.0-28-generic  | 4         | 0.72%   |
| 5.15.0-25-generic | 4         | 0.72%   |
| 5.11.0-34-generic | 4         | 0.72%   |
| 5.11.0-25-generic | 4         | 0.72%   |
| 5.11.0-18-generic | 4         | 0.72%   |
| 5.8.0-50-generic  | 3         | 0.54%   |
| 5.8.0-31-generic  | 3         | 0.54%   |
| 5.4.0-80-generic  | 3         | 0.54%   |
| 5.4.0-73-generic  | 3         | 0.54%   |
| 5.4.0-65-generic  | 3         | 0.54%   |
| 5.4.0-62-generic  | 3         | 0.54%   |
| 5.4.0-54-generic  | 3         | 0.54%   |
| 5.4.0-26-generic  | 3         | 0.54%   |
| 5.3.0-24-generic  | 3         | 0.54%   |
| 5.15.0-41-generic | 3         | 0.54%   |
| 5.15.0-40-generic | 3         | 0.54%   |
| 5.15.0-33-generic | 3         | 0.54%   |
| 5.13.0-27-generic | 3         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 170       | 33.14%  |
| 5.8.0   | 89        | 17.35%  |
| 5.13.0  | 78        | 15.2%   |
| 5.11.0  | 51        | 9.94%   |
| 5.3.0   | 42        | 8.19%   |
| 5.15.0  | 40        | 7.8%    |
| 4.15.0  | 12        | 2.34%   |
| 5.6.0   | 3         | 0.58%   |
| 5.0.0   | 3         | 0.58%   |
| 5.6.7   | 2         | 0.39%   |
| 5.12.0  | 2         | 0.39%   |
| 5.10.0  | 2         | 0.39%   |
| 4.18.0  | 2         | 0.39%   |
| 5.9.1   | 1         | 0.19%   |
| 5.9.0   | 1         | 0.19%   |
| 5.8.6   | 1         | 0.19%   |
| 5.8.11  | 1         | 0.19%   |
| 5.7.7   | 1         | 0.19%   |
| 5.5.8   | 1         | 0.19%   |
| 5.5.0   | 1         | 0.19%   |
| 5.17.2  | 1         | 0.19%   |
| 5.17.1  | 1         | 0.19%   |
| 5.16.2  | 1         | 0.19%   |
| 5.16.14 | 1         | 0.19%   |
| 5.15.11 | 1         | 0.19%   |
| 5.14.2  | 1         | 0.19%   |
| 5.14.1  | 1         | 0.19%   |
| 5.10.11 | 1         | 0.19%   |
| 4.4.178 | 1         | 0.19%   |
| 4.4.0   | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 170       | 33.2%   |
| 5.8     | 91        | 17.77%  |
| 5.13    | 78        | 15.23%  |
| 5.11    | 51        | 9.96%   |
| 5.3     | 42        | 8.2%    |
| 5.15    | 41        | 8.01%   |
| 4.15    | 12        | 2.34%   |
| 5.6     | 5         | 0.98%   |
| 5.10    | 3         | 0.59%   |
| 5.0     | 3         | 0.59%   |
| 5.9     | 2         | 0.39%   |
| 5.5     | 2         | 0.39%   |
| 5.17    | 2         | 0.39%   |
| 5.16    | 2         | 0.39%   |
| 5.12    | 2         | 0.39%   |
| 4.4     | 2         | 0.39%   |
| 4.18    | 2         | 0.39%   |
| 5.7     | 1         | 0.2%    |
| 5.14    | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 477       | 97.35%  |
| i686    | 9         | 1.84%   |
| aarch64 | 3         | 0.61%   |
| armv7l  | 1         | 0.2%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 479       | 97.76%  |
| GNOME  | 9         | 1.84%   |
| XFCE   | 1         | 0.2%    |
| KDE    | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 477       | 97.35%  |
| Wayland | 11        | 2.24%   |
| Tty     | 2         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 229       | 45.89%  |
| LightDM | 132       | 26.45%  |
| TDM     | 92        | 18.44%  |
| GDM     | 32        | 6.41%   |
| GDM3    | 12        | 2.4%    |
| SDDM    | 2         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 177       | 36.05%  |
| de_DE   | 66        | 13.44%  |
| pt_BR   | 34        | 6.92%   |
| fr_FR   | 33        | 6.72%   |
| en_GB   | 26        | 5.3%    |
| en_CA   | 21        | 4.28%   |
| it_IT   | 12        | 2.44%   |
| ru_RU   | 11        | 2.24%   |
| es_ES   | 10        | 2.04%   |
| es_AR   | 9         | 1.83%   |
| en_IN   | 9         | 1.83%   |
| es_MX   | 8         | 1.63%   |
| en_AU   | 8         | 1.63%   |
| C       | 7         | 1.43%   |
| Unknown | 6         | 1.22%   |
| pl_PL   | 4         | 0.81%   |
| es_CL   | 4         | 0.81%   |
| uk_UA   | 3         | 0.61%   |
| pt_PT   | 3         | 0.61%   |
| nl_NL   | 3         | 0.61%   |
| hu_HU   | 3         | 0.61%   |
| de_AT   | 3         | 0.61%   |
| zh_TW   | 2         | 0.41%   |
| fi_FI   | 2         | 0.41%   |
| es_CO   | 2         | 0.41%   |
| en_IE   | 2         | 0.41%   |
| de_CH   | 2         | 0.41%   |
| zh_CN   | 1         | 0.2%    |
| tr_TR   | 1         | 0.2%    |
| sv_SE   | 1         | 0.2%    |
| ru_UA   | 1         | 0.2%    |
| ro_RO   | 1         | 0.2%    |
| nl_BE   | 1         | 0.2%    |
| nb_NO   | 1         | 0.2%    |
| lv_LV   | 1         | 0.2%    |
| ja_JP   | 1         | 0.2%    |
| id_ID   | 1         | 0.2%    |
| fr_CH   | 1         | 0.2%    |
| fr_CA   | 1         | 0.2%    |
| fr_BE   | 1         | 0.2%    |
| es_US   | 1         | 0.2%    |
| es_SV   | 1         | 0.2%    |
| es_GT   | 1         | 0.2%    |
| es_EC   | 1         | 0.2%    |
| en_ZA   | 1         | 0.2%    |
| en_SG   | 1         | 0.2%    |
| en_IL   | 1         | 0.2%    |
| bg_BG   | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 276       | 54.65%  |
| BIOS | 229       | 45.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 457       | 92.89%  |
| Zfs     | 13        | 2.64%   |
| Overlay | 12        | 2.44%   |
| Btrfs   | 6         | 1.22%   |
| Xfs     | 3         | 0.61%   |
| Jfs     | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 287       | 58.1%   |
| GPT     | 168       | 34.01%  |
| MBR     | 39        | 7.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 426       | 85.54%  |
| Yes       | 72        | 14.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 343       | 68.74%  |
| Yes       | 156       | 31.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 73        | 14.9%   |
| ASUSTek Computer        | 73        | 14.9%   |
| Lenovo                  | 66        | 13.47%  |
| Dell                    | 57        | 11.63%  |
| TUXEDO                  | 35        | 7.14%   |
| Gigabyte Technology     | 30        | 6.12%   |
| MSI                     | 24        | 4.9%    |
| Apple                   | 24        | 4.9%    |
| Acer                    | 22        | 4.49%   |
| ASRock                  | 11        | 2.24%   |
| Intel                   | 7         | 1.43%   |
| Samsung Electronics     | 6         | 1.22%   |
| Sony                    | 5         | 1.02%   |
| HUAWEI                  | 5         | 1.02%   |
| Unknown                 | 5         | 1.02%   |
| Google                  | 4         | 0.82%   |
| Fujitsu                 | 4         | 0.82%   |
| Toshiba                 | 3         | 0.61%   |
| Raspberry Pi Foundation | 3         | 0.61%   |
| Packard Bell            | 3         | 0.61%   |
| Timi                    | 2         | 0.41%   |
| Standard                | 2         | 0.41%   |
| Positivo                | 2         | 0.41%   |
| eMachines               | 2         | 0.41%   |
| Alienware               | 2         | 0.41%   |
| Viglen                  | 1         | 0.2%    |
| Teclast                 | 1         | 0.2%    |
| Supermicro              | 1         | 0.2%    |
| Razer                   | 1         | 0.2%    |
| Radxa                   | 1         | 0.2%    |
| Quanta                  | 1         | 0.2%    |
| Pegatron                | 1         | 0.2%    |
| PCSMART                 | 1         | 0.2%    |
| PC Specialist           | 1         | 0.2%    |
| Microsoft               | 1         | 0.2%    |
| LattePanda              | 1         | 0.2%    |
| Huanan                  | 1         | 0.2%    |
| GPU Company             | 1         | 0.2%    |
| EVOO                    | 1         | 0.2%    |
| Chuwi                   | 1         | 0.2%    |
| Biostar                 | 1         | 0.2%    |
| BCM                     | 1         | 0.2%    |
| BANGHO                  | 1         | 0.2%    |
| AWOW                    | 1         | 0.2%    |
| Avell High Performance  | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 15        | 3.06%   |
| ASUS All Series                        | 5         | 1.02%   |
| HP Pavilion g6                         | 3         | 0.61%   |
| TUXEDO Pulse 15 Gen1                   | 2         | 0.41%   |
| TUXEDO Polaris 15 AMD Gen1             | 2         | 0.41%   |
| TUXEDO InfinityBook S 15 Gen6          | 2         | 0.41%   |
| TUXEDO InfinityBook S 14 Gen6          | 2         | 0.41%   |
| TUXEDO InfinityBook Pro 14 Gen6        | 2         | 0.41%   |
| TUXEDO Aura 15 Gen1                    | 2         | 0.41%   |
| Standard MT40II                        | 2         | 0.41%   |
| RPi Raspberry Pi 4 Model B Rev 1.4     | 2         | 0.41%   |
| MSI MS-7C84                            | 2         | 0.41%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 2         | 0.41%   |
| Lenovo IdeaPad 330S-15ARR 81FB         | 2         | 0.41%   |
| Lenovo IdeaPad 320-15IKB 80XL          | 2         | 0.41%   |
| HP ZBook Studio G3                     | 2         | 0.41%   |
| HP Notebook                            | 2         | 0.41%   |
| HP ENVY 17                             | 2         | 0.41%   |
| HP ENVY 15                             | 2         | 0.41%   |
| HP EliteDesk 800 G1 SFF                | 2         | 0.41%   |
| HP 2000                                | 2         | 0.41%   |
| Gigabyte Z68M-D2H                      | 2         | 0.41%   |
| Gigabyte AB350-Gaming 3                | 2         | 0.41%   |
| Dell XPS 13 9380                       | 2         | 0.41%   |
| Dell Precision WorkStation T3500       | 2         | 0.41%   |
| Dell OptiPlex 9010                     | 2         | 0.41%   |
| Dell OptiPlex 780                      | 2         | 0.41%   |
| Dell Latitude E6540                    | 2         | 0.41%   |
| Dell Latitude 5400                     | 2         | 0.41%   |
| Dell Inspiron 5570                     | 2         | 0.41%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT | 2         | 0.41%   |
| ASUS P8H77-M PRO                       | 2         | 0.41%   |
| Apple MacPro1,1                        | 2         | 0.41%   |
| Apple MacBookPro8,1                    | 2         | 0.41%   |
| Acer TravelMate P446-M                 | 2         | 0.41%   |
| Viglen VUB1                            | 1         | 0.2%    |
| TUXEDO Stellaris Intel Gen3 (TGL)      | 1         | 0.2%    |
| TUXEDO Stellaris AMD Gen3 (CZN)        | 1         | 0.2%    |
| TUXEDO Polaris AMD Gen3 (CZN)          | 1         | 0.2%    |
| TUXEDO Polaris 17 AMD Gen1             | 1         | 0.2%    |
| TUXEDO P95_HR                          | 1         | 0.2%    |
| TUXEDO P95_HP                          | 1         | 0.2%    |
| TUXEDO P7xxTM1                         | 1         | 0.2%    |
| TUXEDO InfinityBook_Pro13_14_v4        | 1         | 0.2%    |
| TUXEDO InfinityBook S 14 v5            | 1         | 0.2%    |
| TUXEDO InfinityBook Pro 15 v4          | 1         | 0.2%    |
| TUXEDO Book_XA1510                     | 1         | 0.2%    |
| TUXEDO Book XP1511                     | 1         | 0.2%    |
| TUXEDO Book XP15 / XP17 Gen12          | 1         | 0.2%    |
| Toshiba Satellite S55-C                | 1         | 0.2%    |
| Toshiba Satellite P750                 | 1         | 0.2%    |
| Toshiba Satellite P300                 | 1         | 0.2%    |
| Timi TM1701                            | 1         | 0.2%    |
| Timi TM1604                            | 1         | 0.2%    |
| Teclast X6 plus                        | 1         | 0.2%    |
| Supermicro X9DRT                       | 1         | 0.2%    |
| Sony VPCEK20AL                         | 1         | 0.2%    |
| Sony VPCEJ1L1E                         | 1         | 0.2%    |
| Sony VPCEA47FX                         | 1         | 0.2%    |
| Sony VPCCW25FL                         | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 30        | 6.12%   |
| Dell Latitude         | 16        | 3.27%   |
| Dell Inspiron         | 16        | 3.27%   |
| HP Pavilion           | 15        | 3.06%   |
| Unknown               | 15        | 3.06%   |
| Lenovo IdeaPad        | 14        | 2.86%   |
| Acer Aspire           | 14        | 2.86%   |
| TUXEDO InfinityBook   | 9         | 1.84%   |
| HP EliteBook          | 9         | 1.84%   |
| Dell XPS              | 9         | 1.84%   |
| HP ENVY               | 8         | 1.63%   |
| Dell OptiPlex         | 7         | 1.43%   |
| ASUS VivoBook         | 7         | 1.43%   |
| ASUS ROG              | 7         | 1.43%   |
| HP Compaq             | 6         | 1.22%   |
| ASUS PRIME            | 6         | 1.22%   |
| HP Spectre            | 5         | 1.02%   |
| Dell Precision        | 5         | 1.02%   |
| ASUS All              | 5         | 1.02%   |
| TUXEDO Polaris        | 4         | 0.82%   |
| HP ZBook              | 4         | 0.82%   |
| HP Laptop             | 4         | 0.82%   |
| HP EliteDesk          | 4         | 0.82%   |
| Acer Swift            | 4         | 0.82%   |
| TUXEDO Book           | 3         | 0.61%   |
| Toshiba Satellite     | 3         | 0.61%   |
| RPi Raspberry         | 3         | 0.61%   |
| Lenovo Yoga           | 3         | 0.61%   |
| Lenovo ThinkBook      | 3         | 0.61%   |
| HP ProBook            | 3         | 0.61%   |
| Fujitsu LIFEBOOK      | 3         | 0.61%   |
| ASUS TUF              | 3         | 0.61%   |
| ASUS P8H77-M          | 3         | 0.61%   |
| Apple MacBookPro8     | 3         | 0.61%   |
| TUXEDO Stellaris      | 2         | 0.41%   |
| TUXEDO Pulse          | 2         | 0.41%   |
| TUXEDO P95            | 2         | 0.41%   |
| TUXEDO Aura           | 2         | 0.41%   |
| Standard MT40II       | 2         | 0.41%   |
| Packard Bell EasyNote | 2         | 0.41%   |
| MSI Prestige          | 2         | 0.41%   |
| MSI MS-7C84           | 2         | 0.41%   |
| MSI Modern            | 2         | 0.41%   |
| Lenovo IdeaCentre     | 2         | 0.41%   |
| HP Stream             | 2         | 0.41%   |
| HP Notebook           | 2         | 0.41%   |
| HP 2000               | 2         | 0.41%   |
| Gigabyte Z68M-D2H     | 2         | 0.41%   |
| Gigabyte B360         | 2         | 0.41%   |
| Gigabyte AB350-Gaming | 2         | 0.41%   |
| Dell Vostro           | 2         | 0.41%   |
| ASUS P8Z68-V          | 2         | 0.41%   |
| ASRock B550           | 2         | 0.41%   |
| Apple MacPro1         | 2         | 0.41%   |
| Apple MacBookPro11    | 2         | 0.41%   |
| Apple iMac18          | 2         | 0.41%   |
| Acer TravelMate       | 2         | 0.41%   |
| Viglen VUB1           | 1         | 0.2%    |
| TUXEDO P7xxTM1        | 1         | 0.2%    |
| Timi TM1701           | 1         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 62        | 12.65%  |
| 2018    | 58        | 11.84%  |
| 2020    | 54        | 11.02%  |
| 2017    | 38        | 7.76%   |
| 2011    | 37        | 7.55%   |
| 2012    | 35        | 7.14%   |
| 2013    | 33        | 6.73%   |
| 2014    | 28        | 5.71%   |
| 2021    | 26        | 5.31%   |
| 2015    | 26        | 5.31%   |
| 2016    | 25        | 5.1%    |
| 2010    | 19        | 3.88%   |
| 2009    | 16        | 3.27%   |
| 2008    | 16        | 3.27%   |
| 2007    | 13        | 2.65%   |
| Unknown | 3         | 0.61%   |
| 2022    | 1         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 306       | 62.45%  |
| Desktop        | 142       | 28.98%  |
| Convertible    | 13        | 2.65%   |
| All in one     | 13        | 2.65%   |
| Mini pc        | 6         | 1.22%   |
| Tablet         | 5         | 1.02%   |
| System on chip | 4         | 0.82%   |
| Server         | 1         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 453       | 92.07%  |
| Enabled  | 39        | 7.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 486       | 99.18%  |
| Yes  | 4         | 0.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 123       | 24.85%  |
| 4.01-8.0    | 115       | 23.23%  |
| 3.01-4.0    | 82        | 16.57%  |
| 8.01-16.0   | 81        | 16.36%  |
| 32.01-64.0  | 52        | 10.51%  |
| 64.01-256.0 | 20        | 4.04%   |
| 1.01-2.0    | 11        | 2.22%   |
| 24.01-32.0  | 6         | 1.21%   |
| 2.01-3.0    | 3         | 0.61%   |
| 0.51-1.0    | 2         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 162       | 30.68%  |
| 1.01-2.0   | 146       | 27.65%  |
| 4.01-8.0   | 95        | 17.99%  |
| 3.01-4.0   | 86        | 16.29%  |
| 8.01-16.0  | 25        | 4.73%   |
| 0.51-1.0   | 9         | 1.7%    |
| 16.01-24.0 | 2         | 0.38%   |
| 32.01-64.0 | 1         | 0.19%   |
| 24.01-32.0 | 1         | 0.19%   |
| 0.01-0.5   | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 295       | 58.88%  |
| 2      | 129       | 25.75%  |
| 3      | 38        | 7.58%   |
| 4      | 17        | 3.39%   |
| 5      | 12        | 2.4%    |
| 8      | 4         | 0.8%    |
| 6      | 3         | 0.6%    |
| 11     | 1         | 0.2%    |
| 9      | 1         | 0.2%    |
| 0      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 314       | 63.69%  |
| Yes       | 179       | 36.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 412       | 83.91%  |
| No        | 79        | 16.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 408       | 82.93%  |
| No        | 84        | 17.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 346       | 70.04%  |
| No        | 148       | 29.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 93        | 18.94%  |
| Germany            | 75        | 15.27%  |
| Brazil             | 36        | 7.33%   |
| France             | 33        | 6.72%   |
| Canada             | 20        | 4.07%   |
| UK                 | 17        | 3.46%   |
| Italy              | 15        | 3.05%   |
| Russia             | 13        | 2.65%   |
| Argentina          | 12        | 2.44%   |
| Mexico             | 11        | 2.24%   |
| India              | 11        | 2.24%   |
| Spain              | 10        | 2.04%   |
| Poland             | 10        | 2.04%   |
| Netherlands        | 10        | 2.04%   |
| Australia          | 8         | 1.63%   |
| Ukraine            | 7         | 1.43%   |
| Switzerland        | 7         | 1.43%   |
| Austria            | 7         | 1.43%   |
| Norway             | 6         | 1.22%   |
| Portugal           | 5         | 1.02%   |
| Japan              | 5         | 1.02%   |
| Hungary            | 5         | 1.02%   |
| Sweden             | 4         | 0.81%   |
| Finland            | 4         | 0.81%   |
| Croatia            | 4         | 0.81%   |
| Colombia           | 4         | 0.81%   |
| Chile              | 4         | 0.81%   |
| Belgium            | 4         | 0.81%   |
| Turkey             | 3         | 0.61%   |
| South Africa       | 3         | 0.61%   |
| Ireland            | 3         | 0.61%   |
| Iran               | 3         | 0.61%   |
| Greece             | 3         | 0.61%   |
| Dominican Republic | 3         | 0.61%   |
| Slovenia           | 2         | 0.41%   |
| Romania            | 2         | 0.41%   |
| Malaysia           | 2         | 0.41%   |
| Indonesia          | 2         | 0.41%   |
| Ecuador            | 2         | 0.41%   |
| Thailand           | 1         | 0.2%    |
| Taiwan             | 1         | 0.2%    |
| Slovakia           | 1         | 0.2%    |
| Singapore          | 1         | 0.2%    |
| Serbia             | 1         | 0.2%    |
| Saudi Arabia       | 1         | 0.2%    |
| Puerto Rico        | 1         | 0.2%    |
| Philippines        | 1         | 0.2%    |
| Myanmar            | 1         | 0.2%    |
| Libya              | 1         | 0.2%    |
| Latvia             | 1         | 0.2%    |
| Kenya              | 1         | 0.2%    |
| Jordan             | 1         | 0.2%    |
| Israel             | 1         | 0.2%    |
| Hong Kong          | 1         | 0.2%    |
| Honduras           | 1         | 0.2%    |
| Guatemala          | 1         | 0.2%    |
| Ghana              | 1         | 0.2%    |
| El Salvador        | 1         | 0.2%    |
| Egypt              | 1         | 0.2%    |
| Bulgaria           | 1         | 0.2%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 7         | 1.4%    |
| Berlin             | 6         | 1.2%    |
| Ravensburg         | 5         | 1%      |
| Moscow             | 5         | 1%      |
| Hamburg            | 5         | 1%      |
| Montreal           | 4         | 0.8%    |
| Budapest           | 4         | 0.8%    |
| Zurich             | 3         | 0.6%    |
| Zagreb             | 3         | 0.6%    |
| Vienna             | 3         | 0.6%    |
| Tehran             | 3         | 0.6%    |
| Sydney             | 3         | 0.6%    |
| Santo Domingo Este | 3         | 0.6%    |
| Paris              | 3         | 0.6%    |
| Miami              | 3         | 0.6%    |
| Lisbon             | 3         | 0.6%    |
| Dublin             | 3         | 0.6%    |
| Brasília          | 3         | 0.6%    |
| Bogotá            | 3         | 0.6%    |
| Barcelona          | 3         | 0.6%    |
| Austin             | 3         | 0.6%    |
| Athens             | 3         | 0.6%    |
| Wolfsburg          | 2         | 0.4%    |
| Vancouver          | 2         | 0.4%    |
| Uman               | 2         | 0.4%    |
| Trondheim          | 2         | 0.4%    |
| Toronto            | 2         | 0.4%    |
| Timișoara         | 2         | 0.4%    |
| Stuttgart          | 2         | 0.4%    |
| St Petersburg      | 2         | 0.4%    |
| San Miguel         | 2         | 0.4%    |
| San Jose           | 2         | 0.4%    |
| San Francisco      | 2         | 0.4%    |
| San Antonio        | 2         | 0.4%    |
| Queens             | 2         | 0.4%    |
| Portland           | 2         | 0.4%    |
| Nuremberg          | 2         | 0.4%    |
| Niterói           | 2         | 0.4%    |
| New York           | 2         | 0.4%    |
| Nagoya             | 2         | 0.4%    |
| Münster           | 2         | 0.4%    |
| Munich             | 2         | 0.4%    |
| Mumbai             | 2         | 0.4%    |
| Milan              | 2         | 0.4%    |
| Maringá           | 2         | 0.4%    |
| Los Angeles        | 2         | 0.4%    |
| Kyiv               | 2         | 0.4%    |
| Kassel             | 2         | 0.4%    |
| Istanbul           | 2         | 0.4%    |
| Gurgaon            | 2         | 0.4%    |
| Frankfurt am Main  | 2         | 0.4%    |
| Dresden            | 2         | 0.4%    |
| Dnipro             | 2         | 0.4%    |
| Dallas             | 2         | 0.4%    |
| Cologne            | 2         | 0.4%    |
| Burzaco            | 2         | 0.4%    |
| Belo Horizonte     | 2         | 0.4%    |
| Bamberg            | 2         | 0.4%    |
| Zambrów           | 1         | 0.2%    |
| Zabrze             | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 136       | 189    | 18.66%  |
| WDC                       | 99        | 144    | 13.58%  |
| Seagate                   | 99        | 143    | 13.58%  |
| Toshiba                   | 50        | 54     | 6.86%   |
| SanDisk                   | 43        | 54     | 5.9%    |
| Unknown                   | 36        | 42     | 4.94%   |
| Kingston                  | 33        | 43     | 4.53%   |
| Intel                     | 23        | 39     | 3.16%   |
| Hitachi                   | 20        | 27     | 2.74%   |
| Crucial                   | 20        | 23     | 2.74%   |
| SK hynix                  | 16        | 18     | 2.19%   |
| Phison                    | 12        | 17     | 1.65%   |
| HGST                      | 11        | 15     | 1.51%   |
| A-DATA Technology         | 11        | 15     | 1.51%   |
| Apple                     | 10        | 12     | 1.37%   |
| Micron Technology         | 9         | 12     | 1.23%   |
| China                     | 9         | 11     | 1.23%   |
| SPCC                      | 8         | 10     | 1.1%    |
| PNY                       | 7         | 9      | 0.96%   |
| JMicron Technology        | 5         | 6      | 0.69%   |
| Patriot                   | 4         | 6      | 0.55%   |
| OCZ                       | 3         | 6      | 0.41%   |
| Micron/Crucial Technology | 3         | 3      | 0.41%   |
| Maxtor                    | 3         | 6      | 0.41%   |
| LITEON                    | 3         | 3      | 0.41%   |
| KIOXIA                    | 3         | 3      | 0.41%   |
| Transcend                 | 2         | 2      | 0.27%   |
| SABRENT                   | 2         | 3      | 0.27%   |
| Netac                     | 2         | 2      | 0.27%   |
| Lenovo                    | 2         | 2      | 0.27%   |
| LaCie                     | 2         | 2      | 0.27%   |
| Intenso                   | 2         | 3      | 0.27%   |
| HS-SSD-C100               | 2         | 2      | 0.27%   |
| Hewlett-Packard           | 2         | 1      | 0.27%   |
| Gigabyte Technology       | 2         | 2      | 0.27%   |
| Apacer                    | 2         | 2      | 0.27%   |
| AMD                       | 2         | 17     | 0.27%   |
| Zheino                    | 1         | 1      | 0.14%   |
| XrayDisk                  | 1         | 1      | 0.14%   |
| Vaseky                    | 1         | 1      | 0.14%   |
| USB30                     | 1         | 1      | 0.14%   |
| USB3.0                    | 1         | 1      | 0.14%   |
| Union Memory              | 1         | 1      | 0.14%   |
| TO Exter                  | 1         | 1      | 0.14%   |
| Teclast                   | 1         | 1      | 0.14%   |
| TDAS                      | 1         | 3      | 0.14%   |
| Silicon Motion            | 1         | 1      | 0.14%   |
| Realtek Semiconductor     | 1         | 2      | 0.14%   |
| Plextor                   | 1         | 1      | 0.14%   |
| Phison Electronics        | 1         | 1      | 0.14%   |
| OWC                       | 1         | 1      | 0.14%   |
| MDT                       | 1         | 1      | 0.14%   |
| LITEONIT                  | 1         | 1      | 0.14%   |
| LDLC                      | 1         | 1      | 0.14%   |
| KingSpec                  | 1         | 1      | 0.14%   |
| KingDian                  | 1         | 1      | 0.14%   |
| KimMiDi                   | 1         | 1      | 0.14%   |
| HP Phison                 | 1         | 1      | 0.14%   |
| GOODRAM                   | 1         | 1      | 0.14%   |
| GALAX TA                  | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 9         | 1.11%   |
| Samsung NVMe SSD Drive 512GB       | 9         | 1.11%   |
| Unknown MMC Card  64GB             | 8         | 0.98%   |
| Samsung NVMe SSD Drive 500GB       | 8         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 0.86%   |
| Samsung NVMe SSD Drive 1TB         | 7         | 0.86%   |
| Unknown MMC Card  32GB             | 6         | 0.74%   |
| Seagate ST9500325AS 500GB          | 6         | 0.74%   |
| Samsung SSD 860 QVO 1TB            | 6         | 0.74%   |
| Samsung NVMe SSD Drive 256GB       | 6         | 0.74%   |
| Kingston SA400S37480G 480GB SSD    | 6         | 0.74%   |
| Kingston SA400S37240G 240GB SSD    | 6         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB           | 5         | 0.61%   |
| Toshiba MQ04ABF100 1TB             | 5         | 0.61%   |
| Toshiba MQ01ABD100 1TB             | 5         | 0.61%   |
| SK hynix NVMe SSD Drive 256GB      | 5         | 0.61%   |
| Seagate ST500DM002-1BD142 500GB    | 5         | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB     | 5         | 0.61%   |
| SanDisk SDSSDA240G 240GB           | 5         | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB     | 5         | 0.61%   |
| Samsung SSD 850 EVO 500GB          | 5         | 0.61%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 4         | 0.49%   |
| Unknown SD/MMC/MS PRO 64GB         | 4         | 0.49%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 0.49%   |
| SanDisk SDSSDA120G 120GB           | 4         | 0.49%   |
| SanDisk NVMe SSD Drive 512GB       | 4         | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB       | 4         | 0.49%   |
| Samsung SSD 860 EVO M.2 500GB      | 4         | 0.49%   |
| Samsung SSD 860 EVO M.2 250GB      | 4         | 0.49%   |
| Samsung SSD 860 EVO 250GB          | 4         | 0.49%   |
| Samsung SSD 850 EVO 250GB          | 4         | 0.49%   |
| Samsung SSD 750 EVO 250GB          | 4         | 0.49%   |
| Samsung NVMe SSD Drive 2TB         | 4         | 0.49%   |
| Samsung NVMe SSD Drive 250GB       | 4         | 0.49%   |
| Intel NVMe SSD Drive 512GB         | 4         | 0.49%   |
| China SATA SSD 240GB               | 4         | 0.49%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 3         | 0.37%   |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.37%   |
| Unknown SD64G  64GB                | 3         | 0.37%   |
| Unknown MMC Card  16GB             | 3         | 0.37%   |
| Toshiba DT01ACA100 1TB             | 3         | 0.37%   |
| SPCC Solid State Disk 120GB        | 3         | 0.37%   |
| Seagate ST4000DM000-1F2168 4TB     | 3         | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB     | 3         | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB     | 3         | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB     | 3         | 0.37%   |
| Seagate ST1000LX015-1U7172 1TB     | 3         | 0.37%   |
| Seagate ST1000LM048-2E7172 1TB     | 3         | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB     | 3         | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB     | 3         | 0.37%   |
| Samsung SSD 970 EVO 500GB          | 3         | 0.37%   |
| Phison NVMe SSD Drive 1TB          | 3         | 0.37%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 3         | 0.37%   |
| JMicron Generic 2TB                | 3         | 0.37%   |
| Intel NVMe SSD Drive 32GB          | 3         | 0.37%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 0.37%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 2         | 0.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 96        | 140    | 36.36%  |
| WDC                 | 75        | 116    | 28.41%  |
| Toshiba             | 40        | 43     | 15.15%  |
| Hitachi             | 20        | 27     | 7.58%   |
| HGST                | 11        | 15     | 4.17%   |
| Samsung Electronics | 6         | 7      | 2.27%   |
| Unknown             | 4         | 4      | 1.52%   |
| Apple               | 4         | 4      | 1.52%   |
| Maxtor              | 3         | 6      | 1.14%   |
| SABRENT             | 2         | 3      | 0.76%   |
| USB3.0              | 1         | 1      | 0.38%   |
| Fujitsu             | 1         | 1      | 0.38%   |
| ASMT109x            | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 94     | 28.46%  |
| SanDisk             | 29        | 37     | 11.46%  |
| Kingston            | 29        | 37     | 11.46%  |
| Crucial             | 18        | 21     | 7.11%   |
| WDC                 | 15        | 15     | 5.93%   |
| China               | 9         | 11     | 3.56%   |
| A-DATA Technology   | 9         | 13     | 3.56%   |
| SPCC                | 7         | 9      | 2.77%   |
| PNY                 | 6         | 8      | 2.37%   |
| Intel               | 6         | 6      | 2.37%   |
| Micron Technology   | 5         | 6      | 1.98%   |
| Apple               | 5         | 5      | 1.98%   |
| Patriot             | 4         | 6      | 1.58%   |
| LITEON              | 3         | 3      | 1.19%   |
| SK hynix            | 2         | 2      | 0.79%   |
| Seagate             | 2         | 2      | 0.79%   |
| OCZ                 | 2         | 2      | 0.79%   |
| Netac               | 2         | 2      | 0.79%   |
| Intenso             | 2         | 3      | 0.79%   |
| Gigabyte Technology | 2         | 2      | 0.79%   |
| Apacer              | 2         | 2      | 0.79%   |
| AMD                 | 2         | 17     | 0.79%   |
| Zheino              | 1         | 1      | 0.4%    |
| Vaseky              | 1         | 1      | 0.4%    |
| USB30               | 1         | 1      | 0.4%    |
| Unknown             | 1         | 1      | 0.4%    |
| Union Memory        | 1         | 1      | 0.4%    |
| Transcend           | 1         | 1      | 0.4%    |
| Toshiba             | 1         | 1      | 0.4%    |
| TO Exter            | 1         | 1      | 0.4%    |
| Teclast             | 1         | 1      | 0.4%    |
| Plextor             | 1         | 1      | 0.4%    |
| OWC                 | 1         | 1      | 0.4%    |
| LITEONIT            | 1         | 1      | 0.4%    |
| KingSpec            | 1         | 1      | 0.4%    |
| KingDian            | 1         | 1      | 0.4%    |
| HP Phison           | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.4%    |
| GOODRAM             | 1         | 1      | 0.4%    |
| Dogfish             | 1         | 1      | 0.4%    |
| BIWIN               | 1         | 1      | 0.4%    |
| Axiom               | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 223       | 368    | 34.25%  |
| SSD     | 214       | 323    | 32.87%  |
| NVMe    | 166       | 233    | 25.5%   |
| MMC     | 33        | 40     | 5.07%   |
| Unknown | 15        | 18     | 2.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 351       | 677    | 60.73%  |
| NVMe | 165       | 230    | 28.55%  |
| MMC  | 33        | 40     | 5.71%   |
| SAS  | 29        | 35     | 5.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 265       | 423    | 58.37%  |
| 0.51-1.0   | 136       | 187    | 29.96%  |
| 1.01-2.0   | 30        | 50     | 6.61%   |
| 3.01-4.0   | 15        | 22     | 3.3%    |
| 4.01-10.0  | 5         | 6      | 1.1%    |
| 2.01-3.0   | 3         | 3      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 149       | 29.45%  |
| 251-500        | 140       | 27.67%  |
| 501-1000       | 77        | 15.22%  |
| 51-100         | 36        | 7.11%   |
| 1001-2000      | 33        | 6.52%   |
| 21-50          | 21        | 4.15%   |
| More than 3000 | 17        | 3.36%   |
| 1-20           | 15        | 2.96%   |
| 2001-3000      | 11        | 2.17%   |
| Unknown        | 7         | 1.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 168       | 32.43%  |
| 21-50          | 95        | 18.34%  |
| 101-250        | 91        | 17.57%  |
| 51-100         | 65        | 12.55%  |
| 251-500        | 46        | 8.88%   |
| 501-1000       | 22        | 4.25%   |
| 1001-2000      | 16        | 3.09%   |
| Unknown        | 7         | 1.35%   |
| More than 3000 | 6         | 1.16%   |
| 2001-3000      | 2         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 3         | 3      | 6.82%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 2      | 4.55%   |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 4.55%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2      | 4.55%   |
| WDC WD6400BPVT-60HXZT3 640GB         | 1         | 1      | 2.27%   |
| WDC WD6000HLHX-01JJPV0 600GB         | 1         | 1      | 2.27%   |
| WDC WD5000BPVT-00HXZT1 500GB         | 1         | 1      | 2.27%   |
| WDC WD5000AVCS-632DY1 500GB          | 1         | 1      | 2.27%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1         | 1      | 2.27%   |
| WDC WD2500AAJS-60M0A0 250GB          | 1         | 1      | 2.27%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 2      | 2.27%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 1      | 2.27%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 2.27%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 2.27%   |
| Toshiba MK5055GSX 500GB              | 1         | 1      | 2.27%   |
| Toshiba MK2561GSYN 250GB             | 1         | 1      | 2.27%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 2.27%   |
| Seagate ST9500423AS 500GB            | 1         | 1      | 2.27%   |
| Seagate ST500LX012-1LM162-SSHD 500GB | 1         | 1      | 2.27%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 2.27%   |
| Seagate ST5000DM000-1FK178 5TB       | 1         | 1      | 2.27%   |
| Seagate ST3500320AS 500GB            | 1         | 1      | 2.27%   |
| Seagate ST3320620AS 320GB            | 1         | 1      | 2.27%   |
| Seagate ST3160815AS 160GB            | 1         | 1      | 2.27%   |
| Seagate ST1000DX001-1NS162 1TB       | 1         | 1      | 2.27%   |
| Seagate ST1000DM003-1SB102 1TB       | 1         | 1      | 2.27%   |
| PNY SSD2SC120G3LC709B121-460I 120GB  | 1         | 1      | 2.27%   |
| Patriot Pyro m3 240GB SSD            | 1         | 1      | 2.27%   |
| Maxtor STM3250310AS 250GB            | 1         | 1      | 2.27%   |
| Maxtor 6B200M0 208GB                 | 1         | 2      | 2.27%   |
| Kingston SNS4151S316G 16GB SSD       | 1         | 1      | 2.27%   |
| HP Phison PSSBN032GA27MC1 32GB       | 1         | 1      | 2.27%   |
| Hitachi HTS545025B9SA02 250GB        | 1         | 1      | 2.27%   |
| Hitachi HDS721032CLA362 320GB        | 1         | 1      | 2.27%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 2.27%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 2.27%   |
| Crucial CT500P1SSD8 500GB            | 1         | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 17        | 17     | 38.64%  |
| WDC       | 10        | 11     | 22.73%  |
| Toshiba   | 6         | 6      | 13.64%  |
| Maxtor    | 2         | 3      | 4.55%   |
| Hitachi   | 2         | 2      | 4.55%   |
| HGST      | 2         | 3      | 4.55%   |
| PNY       | 1         | 1      | 2.27%   |
| Patriot   | 1         | 1      | 2.27%   |
| Kingston  | 1         | 1      | 2.27%   |
| HP Phison | 1         | 1      | 2.27%   |
| Crucial   | 1         | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 17     | 43.59%  |
| WDC     | 10        | 11     | 25.64%  |
| Toshiba | 6         | 6      | 15.38%  |
| Maxtor  | 2         | 3      | 5.13%   |
| Hitachi | 2         | 2      | 5.13%   |
| HGST    | 2         | 3      | 5.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 42     | 87.18%  |
| SSD  | 4         | 4      | 10.26%  |
| NVMe | 1         | 1      | 2.56%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 310       | 644    | 58.38%  |
| Works    | 182       | 291    | 34.27%  |
| Malfunc  | 39        | 47     | 7.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 342       | 57.1%   |
| Samsung Electronics           | 71        | 11.85%  |
| AMD                           | 68        | 11.35%  |
| SanDisk                       | 23        | 3.84%   |
| Phison Electronics            | 14        | 2.34%   |
| SK hynix                      | 12        | 2%      |
| Marvell Technology Group      | 9         | 1.5%    |
| Toshiba America Info Systems  | 8         | 1.34%   |
| JMicron Technology            | 6         | 1%      |
| Nvidia                        | 5         | 0.83%   |
| Micron/Crucial Technology     | 5         | 0.83%   |
| Kingston Technology Company   | 5         | 0.83%   |
| ASMedia Technology            | 5         | 0.83%   |
| Micron Technology             | 4         | 0.67%   |
| KIOXIA                        | 4         | 0.67%   |
| Silicon Motion                | 3         | 0.5%    |
| ADATA Technology              | 3         | 0.5%    |
| Realtek Semiconductor         | 2         | 0.33%   |
| Lenovo                        | 2         | 0.33%   |
| Unknown                       | 1         | 0.17%   |
| Union Memory (Shenzhen)       | 1         | 0.17%   |
| Silicon Image                 | 1         | 0.17%   |
| Shenzhen Longsys Electronics  | 1         | 0.17%   |
| OCZ Technology Group          | 1         | 0.17%   |
| Integrated Technology Express | 1         | 0.17%   |
| Apple                         | 1         | 0.17%   |
| Adaptec                       | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 50        | 7.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 43        | 6.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 34        | 5.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 26        | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 22        | 3.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 19        | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 2.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 14        | 2.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 14        | 2.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 1.62%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 10        | 1.47%   |
| Intel SATA Controller [RAID mode]                                                | 9         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 1.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 9         | 1.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 8         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 1.18%   |
| AMD 500 Series Chipset SATA Controller                                           | 8         | 1.18%   |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 1.18%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 1.03%   |
| Phison E12 NVMe Controller                                                       | 7         | 1.03%   |
| Intel SSD 660P Series                                                            | 7         | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 7         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.03%   |
| Intel Non-Volatile memory controller                                             | 6         | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 5         | 0.74%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 5         | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5         | 0.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 0.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.74%   |
| SanDisk PC SN520 NVMe SSD                                                        | 4         | 0.59%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.59%   |
| Micron Non-Volatile memory controller                                            | 4         | 0.59%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 0.59%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 0.59%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.59%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 4         | 0.59%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                     | 4         | 0.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 4         | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 0.59%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.44%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.44%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.44%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.44%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3         | 0.44%   |
| Intel NVMe Optane Memory Series                                                  | 3         | 0.44%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 352       | 57.99%  |
| NVMe | 168       | 27.68%  |
| IDE  | 51        | 8.4%    |
| RAID | 34        | 5.6%    |
| SAS  | 2         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 403       | 82.24%  |
| AMD    | 83        | 16.94%  |
| ARM    | 4         | 0.82%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 16        | 3.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 2.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 1.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 1.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 1.02%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 5         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.02%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 1.02%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.81%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.81%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 0.81%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.81%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 3         | 0.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.61%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.61%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.61%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.61%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 3         | 0.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.61%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.61%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.61%   |
| ARM Processor                                 | 3         | 0.61%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.61%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.61%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.61%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 0.61%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.61%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 0.61%   |
| Intel Xeon CPU 5150 @ 2.66GHz                 | 2         | 0.41%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.41%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 2         | 0.41%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 2         | 0.41%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.41%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.41%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.41%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.41%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.41%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.41%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.41%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 153       | 31.16%  |
| Intel Core i5           | 106       | 21.59%  |
| Intel Core i3           | 30        | 6.11%   |
| AMD Ryzen 5             | 25        | 5.09%   |
| Other                   | 24        | 4.89%   |
| Intel Core 2 Duo        | 20        | 4.07%   |
| AMD Ryzen 7             | 20        | 4.07%   |
| Intel Celeron           | 16        | 3.26%   |
| Intel Xeon              | 11        | 2.24%   |
| Intel Pentium           | 11        | 2.24%   |
| Intel Atom              | 10        | 2.04%   |
| Intel Core i9           | 5         | 1.02%   |
| Intel Core 2            | 5         | 1.02%   |
| Intel Pentium Silver    | 4         | 0.81%   |
| Intel Pentium Dual      | 4         | 0.81%   |
| AMD Ryzen 9             | 4         | 0.81%   |
| AMD Ryzen 3             | 4         | 0.81%   |
| Intel Genuine           | 3         | 0.61%   |
| AMD FX                  | 3         | 0.61%   |
| AMD E                   | 3         | 0.61%   |
| AMD A8                  | 3         | 0.61%   |
| AMD A6                  | 3         | 0.61%   |
| Intel Pentium Dual-Core | 2         | 0.41%   |
| Intel Core m3           | 2         | 0.41%   |
| AMD Turion 64 X2 Mobile | 2         | 0.41%   |
| AMD E1                  | 2         | 0.41%   |
| AMD A4                  | 2         | 0.41%   |
| AMD A10                 | 2         | 0.41%   |
| Intel Pentium 4         | 1         | 0.2%    |
| Intel Core m5           | 1         | 0.2%    |
| Intel Core 2 Quad       | 1         | 0.2%    |
| ARM BCM                 | 1         | 0.2%    |
| AMD Sempron             | 1         | 0.2%    |
| AMD Ryzen Threadripper  | 1         | 0.2%    |
| AMD Quad-Core           | 1         | 0.2%    |
| AMD Phenom II X6        | 1         | 0.2%    |
| AMD Phenom II X4        | 1         | 0.2%    |
| AMD Phenom II X2        | 1         | 0.2%    |
| AMD Embedded            | 1         | 0.2%    |
| AMD Athlon II           | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 208       | 42.45%  |
| 2      | 180       | 36.73%  |
| 6      | 47        | 9.59%   |
| 8      | 38        | 7.76%   |
| 1      | 7         | 1.43%   |
| 16     | 4         | 0.82%   |
| 12     | 2         | 0.41%   |
| 3      | 2         | 0.41%   |
| 24     | 1         | 0.2%    |
| 14     | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 483       | 98.57%  |
| 2      | 7         | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 343       | 69.86%  |
| 1      | 148       | 30.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 484       | 98.78%  |
| 32-bit         | 3         | 0.61%   |
| Unknown        | 3         | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 27.76%  |
| 0x206a7    | 33        | 6.5%    |
| 0x306a9    | 29        | 5.71%   |
| 0x806ec    | 22        | 4.33%   |
| 0x306c3    | 21        | 4.13%   |
| 0x906ea    | 16        | 3.15%   |
| 0x806ea    | 15        | 2.95%   |
| 0x806e9    | 14        | 2.76%   |
| 0x1067a    | 13        | 2.56%   |
| 0x40651    | 12        | 2.36%   |
| 0x806c1    | 11        | 2.17%   |
| 0x906e9    | 10        | 1.97%   |
| 0x406e3    | 9         | 1.77%   |
| 0x306d4    | 9         | 1.77%   |
| 0x506e3    | 8         | 1.57%   |
| 0x806eb    | 7         | 1.38%   |
| 0x08600103 | 6         | 1.18%   |
| 0x30678    | 5         | 0.98%   |
| 0x106e5    | 5         | 0.98%   |
| 0xa0652    | 4         | 0.79%   |
| 0x706e5    | 4         | 0.79%   |
| 0x6fd      | 4         | 0.79%   |
| 0x406c4    | 4         | 0.79%   |
| 0x20655    | 4         | 0.79%   |
| 0x10676    | 4         | 0.79%   |
| 0x0a50000c | 4         | 0.79%   |
| 0x08701021 | 4         | 0.79%   |
| 0x08108109 | 4         | 0.79%   |
| 0x0810100b | 4         | 0.79%   |
| 0x0800820d | 4         | 0.79%   |
| 0xa0660    | 3         | 0.59%   |
| 0x906ed    | 3         | 0.59%   |
| 0x906ec    | 3         | 0.59%   |
| 0x706a1    | 3         | 0.59%   |
| 0x6f6      | 3         | 0.59%   |
| 0x6f2      | 3         | 0.59%   |
| 0x406c3    | 3         | 0.59%   |
| 0x08600106 | 3         | 0.59%   |
| 0x08600104 | 3         | 0.59%   |
| 0x0600611a | 3         | 0.59%   |
| 0x05000119 | 3         | 0.59%   |
| 0xa0671    | 2         | 0.39%   |
| 0x706a8    | 2         | 0.39%   |
| 0x206d7    | 2         | 0.39%   |
| 0x20652    | 2         | 0.39%   |
| 0x08701013 | 2         | 0.39%   |
| 0x0700010f | 2         | 0.39%   |
| 0x06001119 | 2         | 0.39%   |
| 0x06000852 | 2         | 0.39%   |
| 0x010000c8 | 2         | 0.39%   |
| 0xf34      | 1         | 0.2%    |
| 0xa0655    | 1         | 0.2%    |
| 0x906eb    | 1         | 0.2%    |
| 0x906c0    | 1         | 0.2%    |
| 0x906a3    | 1         | 0.2%    |
| 0x806d1    | 1         | 0.2%    |
| 0x6fb      | 1         | 0.2%    |
| 0x6fa      | 1         | 0.2%    |
| 0x506c9    | 1         | 0.2%    |
| 0x406f1    | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 125       | 25.51%  |
| SandyBridge      | 41        | 8.37%   |
| IvyBridge        | 40        | 8.16%   |
| Haswell          | 40        | 8.16%   |
| Zen 2            | 29        | 5.92%   |
| Penryn           | 22        | 4.49%   |
| Skylake          | 21        | 4.29%   |
| Silvermont       | 16        | 3.27%   |
| TigerLake        | 14        | 2.86%   |
| Core             | 14        | 2.86%   |
| CometLake        | 13        | 2.65%   |
| Broadwell        | 13        | 2.65%   |
| Zen+             | 11        | 2.24%   |
| Westmere         | 10        | 2.04%   |
| Icelake          | 10        | 2.04%   |
| Goldmont plus    | 9         | 1.84%   |
| Zen              | 8         | 1.63%   |
| Nehalem          | 7         | 1.43%   |
| Excavator        | 6         | 1.22%   |
| Unknown          | 6         | 1.22%   |
| Zen 3            | 5         | 1.02%   |
| Piledriver       | 5         | 1.02%   |
| K10              | 5         | 1.02%   |
| Puma             | 3         | 0.61%   |
| Jaguar           | 3         | 0.61%   |
| Bobcat           | 3         | 0.61%   |
| K8 Hammer        | 2         | 0.41%   |
| Bonnell          | 2         | 0.41%   |
| Tremont          | 1         | 0.2%    |
| Steamroller      | 1         | 0.2%    |
| P6               | 1         | 0.2%    |
| NetBurst         | 1         | 0.2%    |
| K10 Llano        | 1         | 0.2%    |
| Goldmont         | 1         | 0.2%    |
| Alderlake Hybrid | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 322       | 54.03%  |
| Nvidia                     | 162       | 27.18%  |
| AMD                        | 110       | 18.46%  |
| Matrox Electronics Systems | 1         | 0.17%   |
| ASPEED Technology          | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 5.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 23        | 3.8%    |
| Intel UHD Graphics 620                                                                   | 22        | 3.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 3.63%   |
| AMD Renoir                                                                               | 15        | 2.48%   |
| Intel HD Graphics 620                                                                    | 14        | 2.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 2.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 2.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 2.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 13        | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.65%   |
| Intel HD Graphics 5500                                                                   | 10        | 1.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 1.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.49%   |
| Intel HD Graphics 630                                                                    | 8         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.83%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.83%   |
| Intel Comet Lake UHD Graphics                                                            | 5         | 0.83%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 5         | 0.83%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 0.83%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 4         | 0.66%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.66%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.66%   |
| Intel HD Graphics 530                                                                    | 4         | 0.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.66%   |
| AMD Cezanne                                                                              | 4         | 0.66%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.5%    |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.5%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.5%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.5%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.5%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.5%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 0.5%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.33%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 2         | 0.33%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 229       | 46.17%  |
| 1 x AMD         | 79        | 15.93%  |
| 1 x Nvidia      | 77        | 15.52%  |
| Intel + Nvidia  | 73        | 14.72%  |
| Intel + AMD     | 17        | 3.43%   |
| AMD + Nvidia    | 10        | 2.02%   |
| Other           | 4         | 0.81%   |
| 2 x AMD         | 3         | 0.6%    |
| 2 x Nvidia      | 1         | 0.2%    |
| 2 x Intel       | 1         | 0.2%    |
| Nvidia + Matrox | 1         | 0.2%    |
| 1 x ASPEED      | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 364       | 72.8%   |
| Proprietary | 122       | 24.4%   |
| Unknown     | 14        | 2.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 310       | 61.39%  |
| 1.01-2.0   | 53        | 10.5%   |
| 3.01-4.0   | 33        | 6.53%   |
| 0.01-0.5   | 31        | 6.14%   |
| 7.01-8.0   | 26        | 5.15%   |
| 0.51-1.0   | 26        | 5.15%   |
| 5.01-6.0   | 23        | 4.55%   |
| 2.01-3.0   | 2         | 0.4%    |
| 8.01-16.0  | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 73        | 12.7%   |
| AU Optronics            | 69        | 12%     |
| Samsung Electronics     | 66        | 11.48%  |
| BOE                     | 47        | 8.17%   |
| LG Display              | 42        | 7.3%    |
| Dell                    | 39        | 6.78%   |
| Goldstar                | 22        | 3.83%   |
| Hewlett-Packard         | 21        | 3.65%   |
| Apple                   | 17        | 2.96%   |
| Acer                    | 15        | 2.61%   |
| Ancor Communications    | 13        | 2.26%   |
| AOC                     | 12        | 2.09%   |
| Sharp                   | 11        | 1.91%   |
| BenQ                    | 11        | 1.91%   |
| Chi Mei Optoelectronics | 10        | 1.74%   |
| Philips                 | 9         | 1.57%   |
| Lenovo                  | 8         | 1.39%   |
| Unknown                 | 7         | 1.22%   |
| PANDA                   | 6         | 1.04%   |
| ASUSTek Computer        | 6         | 1.04%   |
| LG Electronics          | 4         | 0.7%    |
| InfoVision              | 4         | 0.7%    |
| Iiyama                  | 4         | 0.7%    |
| Idek Iiyama             | 4         | 0.7%    |
| LGD                     | 3         | 0.52%   |
| Fujitsu Siemens         | 3         | 0.52%   |
| Eizo                    | 3         | 0.52%   |
| ViewSonic               | 2         | 0.35%   |
| Unknown (AAA)           | 2         | 0.35%   |
| Sony                    | 2         | 0.35%   |
| Sceptre Tech            | 2         | 0.35%   |
| MStar                   | 2         | 0.35%   |
| Medion                  | 2         | 0.35%   |
| AGO                     | 2         | 0.35%   |
| Vizio                   | 1         | 0.17%   |
| VIZ                     | 1         | 0.17%   |
| Vestel Elektronik       | 1         | 0.17%   |
| Vestel                  | 1         | 0.17%   |
| UPD                     | 1         | 0.17%   |
| Unknown (XXX)           | 1         | 0.17%   |
| Sun                     | 1         | 0.17%   |
| SANYO                   | 1         | 0.17%   |
| RTK                     | 1         | 0.17%   |
| Pioneer Electronic      | 1         | 0.17%   |
| Panasonic               | 1         | 0.17%   |
| Orion                   | 1         | 0.17%   |
| ONN                     | 1         | 0.17%   |
| NEC Computers           | 1         | 0.17%   |
| MPI                     | 1         | 0.17%   |
| Microstep               | 1         | 0.17%   |
| LG Philips              | 1         | 0.17%   |
| LaCie                   | 1         | 0.17%   |
| KTC                     | 1         | 0.17%   |
| JDI                     | 1         | 0.17%   |
| ITE                     | 1         | 0.17%   |
| Insignia                | 1         | 0.17%   |
| InnoLux Display         | 1         | 0.17%   |
| IBM                     | 1         | 0.17%   |
| Hyundai ImageQuest      | 1         | 0.17%   |
| Huion                   | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 5         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch        | 5         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 4         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 4         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 3         | 0.5%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch          | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 3         | 0.5%    |
| Unknown LCD Monitor SAMSUNG                                             | 2         | 0.33%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 2         | 0.33%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch       | 2         | 0.33%   |
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch       | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 1872x1053mm 84.6-inch | 2         | 0.33%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                       | 2         | 0.33%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 2         | 0.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 2         | 0.33%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 2         | 0.33%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                          | 2         | 0.33%   |
| LGD LCD Monitor 1920x1080                                               | 2         | 0.33%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 2         | 0.33%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch            | 2         | 0.33%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch             | 2         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch            | 2         | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 0.33%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch             | 2         | 0.33%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch              | 2         | 0.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 2         | 0.33%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 2         | 0.33%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 0.33%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                       | 2         | 0.33%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                        | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch        | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch         | 2         | 0.33%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 2         | 0.33%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                       | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch           | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch          | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch           | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch          | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch          | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch           | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch           | 2         | 0.33%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 509x286mm 23.0-inch   | 2         | 0.33%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch   | 2         | 0.33%   |
| Vizio E320VT VIZ0067 1920x1080 700x390mm 31.5-inch                      | 1         | 0.17%   |
| Vizio D50u-D1 VIZ1011 3840x2160 941x529mm 42.5-inch                     | 1         | 0.17%   |
| VIZ LCD Monitor M50-C1 3840x2160                                        | 1         | 0.17%   |
| ViewSonic VX2476 Series VSC9939 1920x1080 527x296mm 23.8-inch           | 1         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 239       | 43.69%  |
| 1366x768 (WXGA)    | 105       | 19.2%   |
| 3840x2160 (4K)     | 30        | 5.48%   |
| 2560x1440 (QHD)    | 21        | 3.84%   |
| 1600x900 (HD+)     | 17        | 3.11%   |
| 1280x1024 (SXGA)   | 15        | 2.74%   |
| Unknown            | 14        | 2.56%   |
| 1920x1200 (WUXGA)  | 13        | 2.38%   |
| 1680x1050 (WSXGA+) | 12        | 2.19%   |
| 1280x800 (WXGA)    | 11        | 2.01%   |
| 3440x1440          | 8         | 1.46%   |
| 2560x1080          | 8         | 1.46%   |
| 3840x1080          | 6         | 1.1%    |
| 1440x900 (WXGA+)   | 6         | 1.1%    |
| 3200x1800 (QHD+)   | 4         | 0.73%   |
| 2880x1800          | 4         | 0.73%   |
| 2560x1600          | 3         | 0.55%   |
| 3520x1080          | 2         | 0.37%   |
| 2160x1440          | 2         | 0.37%   |
| 1920x540           | 2         | 0.37%   |
| 1600x1200          | 2         | 0.37%   |
| 7680x2160          | 1         | 0.18%   |
| 5760x2160          | 1         | 0.18%   |
| 4480x1080          | 1         | 0.18%   |
| 3840x2400          | 1         | 0.18%   |
| 3840x1440          | 1         | 0.18%   |
| 3840x1200          | 1         | 0.18%   |
| 3840x1100          | 1         | 0.18%   |
| 3600x1080          | 1         | 0.18%   |
| 3000x2000          | 1         | 0.18%   |
| 2880x1920          | 1         | 0.18%   |
| 2646x768           | 1         | 0.18%   |
| 2560x1024          | 1         | 0.18%   |
| 2400x1600          | 1         | 0.18%   |
| 2390x768           | 1         | 0.18%   |
| 2288x1287          | 1         | 0.18%   |
| 2256x1504          | 1         | 0.18%   |
| 2048x1152          | 1         | 0.18%   |
| 1920x1280          | 1         | 0.18%   |
| 1400x1050          | 1         | 0.18%   |
| 1360x768           | 1         | 0.18%   |
| 1280x960           | 1         | 0.18%   |
| 1280x768           | 1         | 0.18%   |
| 1280x720 (HD)      | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 146       | 25.52%  |
| 13      | 74        | 12.94%  |
| Unknown | 49        | 8.57%   |
| 14      | 46        | 8.04%   |
| 24      | 42        | 7.34%   |
| 27      | 37        | 6.47%   |
| 23      | 34        | 5.94%   |
| 17      | 27        | 4.72%   |
| 21      | 21        | 3.67%   |
| 19      | 12        | 2.1%    |
| 34      | 11        | 1.92%   |
| 11      | 10        | 1.75%   |
| 12      | 9         | 1.57%   |
| 31      | 7         | 1.22%   |
| 54      | 5         | 0.87%   |
| 22      | 5         | 0.87%   |
| 18      | 5         | 0.87%   |
| 84      | 4         | 0.7%    |
| 20      | 4         | 0.7%    |
| 52      | 2         | 0.35%   |
| 48      | 2         | 0.35%   |
| 40      | 2         | 0.35%   |
| 32      | 2         | 0.35%   |
| 29      | 2         | 0.35%   |
| 28      | 2         | 0.35%   |
| 142     | 1         | 0.17%   |
| 72      | 1         | 0.17%   |
| 63      | 1         | 0.17%   |
| 46      | 1         | 0.17%   |
| 44      | 1         | 0.17%   |
| 42      | 1         | 0.17%   |
| 37      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 25      | 1         | 0.17%   |
| 16      | 1         | 0.17%   |
| 10      | 1         | 0.17%   |
| 8       | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 229       | 40.32%  |
| 501-600        | 105       | 18.49%  |
| 201-300        | 58        | 10.21%  |
| Unknown        | 49        | 8.63%   |
| 401-500        | 39        | 6.87%   |
| 351-400        | 35        | 6.16%   |
| 601-700        | 17        | 2.99%   |
| 701-800        | 13        | 2.29%   |
| 1001-1500      | 11        | 1.94%   |
| 1501-2000      | 5         | 0.88%   |
| 801-900        | 3         | 0.53%   |
| 901-1000       | 2         | 0.35%   |
| More than 2000 | 1         | 0.18%   |
| 101-200        | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 362       | 71.68%  |
| 16/10   | 52        | 10.3%   |
| Unknown | 44        | 8.71%   |
| 5/4     | 13        | 2.57%   |
| 21/9    | 13        | 2.57%   |
| 4/3     | 8         | 1.58%   |
| 3/2     | 8         | 1.58%   |
| 32/9    | 2         | 0.4%    |
| 6/5     | 1         | 0.2%    |
| 3.40    | 1         | 0.2%    |
| 1.00    | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 144       | 25.44%  |
| 81-90          | 88        | 15.55%  |
| 201-250        | 74        | 13.07%  |
| Unknown        | 49        | 8.66%   |
| 301-350        | 37        | 6.54%   |
| 71-80          | 34        | 6.01%   |
| 351-500        | 22        | 3.89%   |
| 251-300        | 21        | 3.71%   |
| 151-200        | 21        | 3.71%   |
| 121-130        | 19        | 3.36%   |
| More than 1000 | 15        | 2.65%   |
| 51-60          | 11        | 1.94%   |
| 141-150        | 9         | 1.59%   |
| 501-1000       | 7         | 1.24%   |
| 61-70          | 6         | 1.06%   |
| 131-140        | 5         | 0.88%   |
| 91-100         | 2         | 0.35%   |
| 41-50          | 1         | 0.18%   |
| 1-40           | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 149       | 26.99%  |
| 121-160       | 145       | 26.27%  |
| 101-120       | 133       | 24.09%  |
| Unknown       | 49        | 8.88%   |
| 161-240       | 40        | 7.25%   |
| More than 240 | 21        | 3.8%    |
| 1-50          | 15        | 2.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 375       | 74.7%   |
| 2     | 99        | 19.72%  |
| 3     | 14        | 2.79%   |
| 0     | 13        | 2.59%   |
| 4     | 1         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 270       | 35.39%  |
| Realtek Semiconductor                 | 254       | 33.29%  |
| Qualcomm Atheros                      | 91        | 11.93%  |
| Broadcom                              | 48        | 6.29%   |
| Broadcom Limited                      | 15        | 1.97%   |
| Marvell Technology Group              | 8         | 1.05%   |
| Ralink Technology                     | 7         | 0.92%   |
| Ralink                                | 7         | 0.92%   |
| Nvidia                                | 5         | 0.66%   |
| MediaTek                              | 5         | 0.66%   |
| Hewlett-Packard                       | 5         | 0.66%   |
| ASIX Electronics                      | 4         | 0.52%   |
| Xiaomi                                | 3         | 0.39%   |
| Qualcomm Atheros Communications       | 3         | 0.39%   |
| Microsoft                             | 3         | 0.39%   |
| D-Link System                         | 3         | 0.39%   |
| Sierra Wireless                       | 2         | 0.26%   |
| OnePlus Technology (Shenzhen)         | 2         | 0.26%   |
| Linksys                               | 2         | 0.26%   |
| Lenovo                                | 2         | 0.26%   |
| JMicron Technology                    | 2         | 0.26%   |
| Huawei Technologies                   | 2         | 0.26%   |
| DisplayLink                           | 2         | 0.26%   |
| Wacom                                 | 1         | 0.13%   |
| TP-Link                               | 1         | 0.13%   |
| Samsung Electronics                   | 1         | 0.13%   |
| Novatek Microelectronics              | 1         | 0.13%   |
| NetGear                               | 1         | 0.13%   |
| Mercucys                              | 1         | 0.13%   |
| Luminary Micro                        | 1         | 0.13%   |
| Google                                | 1         | 0.13%   |
| Exar                                  | 1         | 0.13%   |
| Ericsson Business Mobile Networks     | 1         | 0.13%   |
| Edimax Technology                     | 1         | 0.13%   |
| Dell                                  | 1         | 0.13%   |
| D-Link                                | 1         | 0.13%   |
| BUFFALO                               | 1         | 0.13%   |
| Belkin Components                     | 1         | 0.13%   |
| ASUSTek Computer                      | 1         | 0.13%   |
| Apple                                 | 1         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 163       | 18.29%  |
| Intel Wi-Fi 6 AX200                                               | 44        | 4.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32        | 3.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 3.14%   |
| Intel Wireless 8265 / 8275                                        | 24        | 2.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 2.13%   |
| Intel Wireless-AC 9260                                            | 19        | 2.13%   |
| Intel Wireless 7265                                               | 14        | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.23%   |
| Intel Wireless 8260                                               | 11        | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.9%    |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.79%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.67%   |
| Intel Wireless 7260                                               | 6         | 0.67%   |
| Intel Wireless 3165                                               | 6         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.56%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.45%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 0.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.34%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.34%   |
| Realtek 802.11ac NIC                                              | 3         | 0.34%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.34%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.34%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.34%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.34%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.34%   |
| Intel WiFi Link 5100                                              | 3         | 0.34%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 220       | 51.16%  |
| Qualcomm Atheros                      | 70        | 16.28%  |
| Realtek Semiconductor                 | 52        | 12.09%  |
| Broadcom                              | 33        | 7.67%   |
| Broadcom Limited                      | 12        | 2.79%   |
| Ralink Technology                     | 7         | 1.63%   |
| Ralink                                | 7         | 1.63%   |
| MediaTek                              | 5         | 1.16%   |
| Qualcomm Atheros Communications       | 3         | 0.7%    |
| Microsoft                             | 3         | 0.7%    |
| Sierra Wireless                       | 2         | 0.47%   |
| Linksys                               | 2         | 0.47%   |
| D-Link System                         | 2         | 0.47%   |
| Wacom                                 | 1         | 0.23%   |
| TP-Link                               | 1         | 0.23%   |
| NetGear                               | 1         | 0.23%   |
| Mercucys                              | 1         | 0.23%   |
| Marvell Technology Group              | 1         | 0.23%   |
| Hewlett-Packard                       | 1         | 0.23%   |
| Edimax Technology                     | 1         | 0.23%   |
| D-Link                                | 1         | 0.23%   |
| BUFFALO                               | 1         | 0.23%   |
| Belkin Components                     | 1         | 0.23%   |
| ASUSTek Computer                      | 1         | 0.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 44        | 10.19%  |
| Intel Wireless 8265 / 8275                                              | 24        | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 4.4%    |
| Intel Wireless-AC 9260                                                  | 19        | 4.4%    |
| Intel Wireless 7265                                                     | 14        | 3.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 3.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 2.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 2.55%   |
| Intel Wireless 8260                                                     | 11        | 2.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.85%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 1.39%   |
| Intel Wireless 7260                                                     | 6         | 1.39%   |
| Intel Wireless 3165                                                     | 6         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 0.93%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 4         | 0.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.69%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 3         | 0.69%   |
| Intel WiFi Link 5100                                                    | 3         | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.69%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.69%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 0.69%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 0.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.69%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.46%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.46%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.46%   |
| Ralink RT5372 Wireless Adapter                                          | 2         | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.46%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2         | 0.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.46%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                       | 2         | 0.46%   |
| Intel Wireless 3160                                                     | 2         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 230       | 52.63%  |
| Intel                         | 119       | 27.23%  |
| Qualcomm Atheros              | 28        | 6.41%   |
| Broadcom                      | 24        | 5.49%   |
| Marvell Technology Group      | 7         | 1.6%    |
| Nvidia                        | 5         | 1.14%   |
| ASIX Electronics              | 4         | 0.92%   |
| Xiaomi                        | 3         | 0.69%   |
| Broadcom Limited              | 3         | 0.69%   |
| OnePlus Technology (Shenzhen) | 2         | 0.46%   |
| Lenovo                        | 2         | 0.46%   |
| JMicron Technology            | 2         | 0.46%   |
| Hewlett-Packard               | 2         | 0.46%   |
| DisplayLink                   | 2         | 0.46%   |
| Samsung Electronics           | 1         | 0.23%   |
| Google                        | 1         | 0.23%   |
| D-Link System                 | 1         | 0.23%   |
| Apple                         | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 163       | 36.22%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 32        | 7.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 28        | 6.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 22        | 4.89%   |
| Realtek RTL8125 2.5GbE Controller                                              | 12        | 2.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.78%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 1.78%   |
| Intel Ethernet Connection (7) I219-V                                           | 8         | 1.78%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 1.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 6         | 1.33%   |
| Intel Ethernet Connection (6) I219-V                                           | 6         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.11%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.11%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.89%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 4         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.67%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 0.67%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.67%   |
| Intel Ethernet Controller I225-V                                               | 3         | 0.67%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.67%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.67%   |
| Intel 82566DM Gigabit Network Connection                                       | 3         | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.44%   |
| OnePlus (Shenzhen) OnePlus                                                     | 2         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.44%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.44%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.44%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 2         | 0.44%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.44%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.22%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.22%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.22%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.22%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.22%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.22%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 412       | 49.76%  |
| WiFi     | 407       | 49.15%  |
| Modem    | 9         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 338       | 64.63%  |
| Ethernet | 185       | 35.37%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 289       | 58.86%  |
| 1     | 177       | 36.05%  |
| 0     | 13        | 2.65%   |
| 3     | 12        | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 422       | 85.08%  |
| Yes  | 74        | 14.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 179       | 51.29%  |
| Qualcomm Atheros Communications | 30        | 8.6%    |
| Realtek Semiconductor           | 23        | 6.59%   |
| Cambridge Silicon Radio         | 21        | 6.02%   |
| Apple                           | 20        | 5.73%   |
| Broadcom                        | 19        | 5.44%   |
| Lite-On Technology              | 10        | 2.87%   |
| IMC Networks                    | 10        | 2.87%   |
| Foxconn / Hon Hai               | 8         | 2.29%   |
| Hewlett-Packard                 | 5         | 1.43%   |
| Dell                            | 5         | 1.43%   |
| Realtek                         | 4         | 1.15%   |
| Ralink                          | 3         | 0.86%   |
| ASUSTek Computer                | 3         | 0.86%   |
| Toshiba                         | 2         | 0.57%   |
| Belkin Components               | 2         | 0.57%   |
| Unknown                         | 1         | 0.29%   |
| MediaTek                        | 1         | 0.29%   |
| Marvell Semiconductor           | 1         | 0.29%   |
| Integrated System Solution      | 1         | 0.29%   |
| Foxconn International           | 1         | 0.29%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 62        | 17.77%  |
| Intel AX200 Bluetooth                                                               | 42        | 12.03%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 22        | 6.3%    |
| Intel Bluetooth Device                                                              | 21        | 6.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 21        | 6.02%   |
| Intel AX201 Bluetooth                                                               | 20        | 5.73%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 4.58%   |
| Realtek Bluetooth Radio                                                             | 11        | 3.15%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 2.29%   |
| Apple Bluetooth Host Controller                                                     | 8         | 2.29%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 2.01%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.43%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 1.43%   |
| Realtek Bluetooth Radio                                                             | 4         | 1.15%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.15%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.15%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.15%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 1.15%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.86%   |
| Lite-On Bluetooth Device                                                            | 3         | 0.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.86%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.86%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.57%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.57%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.57%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.57%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.57%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.57%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.57%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.57%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 2         | 0.57%   |
| Unknown Bluetooth Device                                                            | 1         | 0.29%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.29%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.29%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.29%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.29%   |
| MediaTek Wireless_Device                                                            | 1         | 0.29%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.29%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.29%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.29%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.29%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.29%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.29%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.29%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.29%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.29%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.29%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.29%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.29%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.29%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.29%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 386       | 56.68%  |
| Nvidia                    | 112       | 16.45%  |
| AMD                       | 108       | 15.86%  |
| C-Media Electronics       | 9         | 1.32%   |
| Realtek Semiconductor     | 8         | 1.17%   |
| Logitech                  | 7         | 1.03%   |
| GN Netcom                 | 5         | 0.73%   |
| JMTek                     | 4         | 0.59%   |
| Creative Labs             | 4         | 0.59%   |
| Sennheiser Communications | 3         | 0.44%   |
| Kingston Technology       | 3         | 0.44%   |
| Creative Technology       | 3         | 0.44%   |
| Samson Technologies       | 2         | 0.29%   |
| Plantronics               | 2         | 0.29%   |
| Focusrite-Novation        | 2         | 0.29%   |
| Blue Microphones          | 2         | 0.29%   |
| XMOS                      | 1         | 0.15%   |
| Texas Instruments         | 1         | 0.15%   |
| SteelSeries ApS           | 1         | 0.15%   |
| Razer USA                 | 1         | 0.15%   |
| OPPO Electronics          | 1         | 0.15%   |
| No brand                  | 1         | 0.15%   |
| Native Instruments        | 1         | 0.15%   |
| Nam Tai E&E Products      | 1         | 0.15%   |
| Microsoft                 | 1         | 0.15%   |
| M-Audio                   | 1         | 0.15%   |
| Lenovo                    | 1         | 0.15%   |
| Hewlett-Packard           | 1         | 0.15%   |
| GYROCOM C&C               | 1         | 0.15%   |
| Giga-Byte Technology      | 1         | 0.15%   |
| Generalplus Technology    | 1         | 0.15%   |
| Conexant Systems          | 1         | 0.15%   |
| Cambridge Audio           | 1         | 0.15%   |
| C&T                       | 1         | 0.15%   |
| Bose                      | 1         | 0.15%   |
| Apple                     | 1         | 0.15%   |
| AKAI Professional M.I.    | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 53        | 6.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 37        | 4.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 4.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 25        | 3.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 25        | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 2.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 2.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 1.9%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 14        | 1.77%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 14        | 1.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 1.77%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 1.77%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 1.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 1.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 13        | 1.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 1.52%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 1.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.52%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.52%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.14%   |
| Realtek Semiconductor USB Audio                                                                   | 8         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 0.63%   |
| Nvidia TU104 HD Audio Controller                                                                  | 4         | 0.51%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 0.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.51%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.51%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 0.51%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.51%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.51%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.38%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.38%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.38%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.38%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.38%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 89        | 28.16%  |
| SK hynix            | 66        | 20.89%  |
| Kingston            | 30        | 9.49%   |
| Micron Technology   | 27        | 8.54%   |
| Unknown             | 22        | 6.96%   |
| Crucial             | 18        | 5.7%    |
| Corsair             | 10        | 3.16%   |
| Ramaxel Technology  | 9         | 2.85%   |
| G.Skill             | 6         | 1.9%    |
| A-DATA Technology   | 5         | 1.58%   |
| Unknown (ABCD)      | 4         | 1.27%   |
| Team                | 3         | 0.95%   |
| Teikon              | 2         | 0.63%   |
| Smart               | 2         | 0.63%   |
| PNY                 | 2         | 0.63%   |
| Nanya Technology    | 2         | 0.63%   |
| Goodram             | 2         | 0.63%   |
| Elpida              | 2         | 0.63%   |
| Unknown             | 2         | 0.63%   |
| Unknown (F301)      | 1         | 0.32%   |
| Unknown (0x873E)    | 1         | 0.32%   |
| Transcend           | 1         | 0.32%   |
| Timetec             | 1         | 0.32%   |
| Smart Brazil        | 1         | 0.32%   |
| Sesame              | 1         | 0.32%   |
| Patriot             | 1         | 0.32%   |
| Kingmax             | 1         | 0.32%   |
| Goldkey             | 1         | 0.32%   |
| Cors                | 1         | 0.32%   |
| Avant               | 1         | 0.32%   |
| ASint Technology    | 1         | 0.32%   |
| Apacer              | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 6         | 1.79%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 6         | 1.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.49%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.49%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 4         | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.19%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.19%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.9%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.9%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.9%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.9%    |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.9%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.9%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.9%    |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.9%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 2         | 0.6%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.6%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 2         | 0.6%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 2         | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.6%    |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 2         | 0.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.6%    |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.6%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.6%    |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.6%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 0.6%    |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.6%    |
| Kingston RAM 9905403-199.A00LF 4GB DIMM DDR3 1600MT/s            | 2         | 0.6%    |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s            | 2         | 0.6%    |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s           | 2         | 0.6%    |
| Unknown                                                          | 2         | 0.6%    |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.3%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1         | 0.3%    |
| Unknown RAM Module 512MB DIMM 533MT/s                            | 1         | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.3%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.3%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.3%    |
| Unknown RAM Module 4096MB SODIMM                                 | 1         | 0.3%    |
| Unknown RAM Module 4096MB DIMM DDR 1066MT/s                      | 1         | 0.3%    |
| Unknown RAM Module 4096MB DIMM 400MT/s                           | 1         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.3%    |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.3%    |
| Unknown RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.3%    |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                      | 1         | 0.3%    |
| Unknown RAM Module 2048MB DIMM DDR 1066MT/s                      | 1         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 126       | 46.15%  |
| DDR3    | 97        | 35.53%  |
| LPDDR3  | 14        | 5.13%   |
| LPDDR4  | 12        | 4.4%    |
| DDR2    | 10        | 3.66%   |
| SDRAM   | 7         | 2.56%   |
| Unknown | 5         | 1.83%   |
| DDR     | 2         | 0.73%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 174       | 64.93%  |
| DIMM         | 66        | 24.63%  |
| Row Of Chips | 23        | 8.58%   |
| FB-DIMM      | 2         | 0.75%   |
| RIMM         | 1         | 0.37%   |
| Chip         | 1         | 0.37%   |
| Unknown      | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 103       | 34.68%  |
| 4096  | 97        | 32.66%  |
| 16384 | 42        | 14.14%  |
| 2048  | 31        | 10.44%  |
| 32768 | 13        | 4.38%   |
| 1024  | 9         | 3.03%   |
| 512   | 2         | 0.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 70        | 23.26%  |
| 2667    | 59        | 19.6%   |
| 3200    | 32        | 10.63%  |
| 2400    | 26        | 8.64%   |
| 2133    | 20        | 6.64%   |
| 1333    | 18        | 5.98%   |
| 1334    | 10        | 3.32%   |
| 667     | 7         | 2.33%   |
| 3266    | 6         | 1.99%   |
| 1867    | 6         | 1.99%   |
| Unknown | 6         | 1.99%   |
| 4267    | 4         | 1.33%   |
| 1067    | 4         | 1.33%   |
| 800     | 4         | 1.33%   |
| 8400    | 3         | 1%      |
| 4199    | 3         | 1%      |
| 3600    | 3         | 1%      |
| 1066    | 3         | 1%      |
| 533     | 3         | 1%      |
| 4266    | 1         | 0.33%   |
| 3733    | 1         | 0.33%   |
| 3500    | 1         | 0.33%   |
| 3466    | 1         | 0.33%   |
| 3007    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 2933    | 1         | 0.33%   |
| 2666    | 1         | 0.33%   |
| 2134    | 1         | 0.33%   |
| 2048    | 1         | 0.33%   |
| 1866    | 1         | 0.33%   |
| 1800    | 1         | 0.33%   |
| 1639    | 1         | 0.33%   |
| 400     | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 33.33%  |
| Canon               | 4         | 33.33%  |
| Sharp               | 1         | 8.33%   |
| Samsung Electronics | 1         | 8.33%   |
| Fuji Xerox          | 1         | 8.33%   |
| Brother Industries  | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Sharp AL-2030                 | 1         | 8.33%   |
| Samsung M2020 Series          | 1         | 8.33%   |
| HP LaserJet 1320              | 1         | 8.33%   |
| HP Deskjet 3050 J610 series   | 1         | 8.33%   |
| HP Deskjet 2540 series        | 1         | 8.33%   |
| HP DeskJet 2130 series        | 1         | 8.33%   |
| Fuji Xerox DocuPrint CM305 df | 1         | 8.33%   |
| Canon TR7500 series           | 1         | 8.33%   |
| Canon MF4010 series           | 1         | 8.33%   |
| Canon MF240 Series V4         | 1         | 8.33%   |
| Canon LiDE 400                | 1         | 8.33%   |
| Brother MFC-1810              | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 33.33%  |
| Canon CanoScan LiDE 120 | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 82        | 24.33%  |
| Sunplus Innovation Technology          | 29        | 8.61%   |
| Acer                                   | 29        | 8.61%   |
| Realtek Semiconductor                  | 28        | 8.31%   |
| IMC Networks                           | 27        | 8.01%   |
| Microdia                               | 24        | 7.12%   |
| Logitech                               | 17        | 5.04%   |
| Apple                                  | 17        | 5.04%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.86%   |
| Syntek                                 | 9         | 2.67%   |
| Suyin                                  | 9         | 2.67%   |
| Quanta                                 | 8         | 2.37%   |
| Silicon Motion                         | 6         | 1.78%   |
| Lite-On Technology                     | 5         | 1.48%   |
| Ricoh                                  | 3         | 0.89%   |
| Microsoft                              | 3         | 0.89%   |
| Generalplus Technology                 | 3         | 0.89%   |
| Alcor Micro                            | 3         | 0.89%   |
| Luxvisions Innotech Limited            | 2         | 0.59%   |
| LG Electronics                         | 2         | 0.59%   |
| ARC International                      | 2         | 0.59%   |
| Z-Star Microelectronics                | 1         | 0.3%    |
| Unknown                                | 1         | 0.3%    |
| Tobii Technology AB                    | 1         | 0.3%    |
| Sonix Technology                       | 1         | 0.3%    |
| Samsung Electronics                    | 1         | 0.3%    |
| Primax Electronics                     | 1         | 0.3%    |
| OPPO Electronics                       | 1         | 0.3%    |
| Omnivision                             | 1         | 0.3%    |
| Linux Foundation                       | 1         | 0.3%    |
| IPEVO                                  | 1         | 0.3%    |
| Importek                               | 1         | 0.3%    |
| icSpring                               | 1         | 0.3%    |
| Guillemot                              | 1         | 0.3%    |
| Cubeternet                             | 1         | 0.3%    |
| Creative Technology                    | 1         | 0.3%    |
| Unknown                                | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 15        | 4.42%   |
| Chicony HD Webcam                                                          | 13        | 3.83%   |
| Chicony Integrated Camera                                                  | 11        | 3.24%   |
| Realtek Integrated_Webcam_HD                                               | 9         | 2.65%   |
| Microdia Integrated_Webcam_HD                                              | 9         | 2.65%   |
| IMC Networks Integrated Camera                                             | 9         | 2.65%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 7         | 2.06%   |
| Acer HD Webcam                                                             | 7         | 2.06%   |
| Chicony HP HD Camera                                                       | 6         | 1.77%   |
| Sunplus HD WebCam                                                          | 5         | 1.47%   |
| Logitech HD Pro Webcam C920                                                | 5         | 1.47%   |
| Apple FaceTime HD Camera (Built-in)                                        | 5         | 1.47%   |
| Apple Built-in iSight                                                      | 5         | 1.47%   |
| Acer Integrated Camera                                                     | 5         | 1.47%   |
| Acer BisonCam,NB Pro                                                       | 5         | 1.47%   |
| Syntek Integrated Camera                                                   | 4         | 1.18%   |
| IMC Networks VGA UVC WebCam                                                | 4         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 4         | 1.18%   |
| Apple FaceTime HD Camera                                                   | 4         | 1.18%   |
| Sunplus USB Camera                                                         | 3         | 0.88%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 0.88%   |
| Realtek USB2.0 HD UVC WebCam                                               | 3         | 0.88%   |
| Realtek Integrated Webcam                                                  | 3         | 0.88%   |
| Microdia Sonix USB 2.0 Camera                                              | 3         | 0.88%   |
| IMC Networks ov9734_azurewave_camera                                       | 3         | 0.88%   |
| Chicony Integrated Camera [ThinkPad]                                       | 3         | 0.88%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 0.88%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 0.88%   |
| Acer BisonCam, NB Pro                                                      | 3         | 0.88%   |
| Syntek EasyCamera                                                          | 2         | 0.59%   |
| Suyin HP Truevision HD                                                     | 2         | 0.59%   |
| Sunplus Lenovo EasyCamera                                                  | 2         | 0.59%   |
| Sunplus Integrated_Webcam_FHD                                              | 2         | 0.59%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 0.59%   |
| Sunplus HD User Facing                                                     | 2         | 0.59%   |
| Sunplus Aukey-PC-LM1E Camera                                               | 2         | 0.59%   |
| Sunplus ASUS Webcam                                                        | 2         | 0.59%   |
| Realtek Lenovo EasyCamera                                                  | 2         | 0.59%   |
| Realtek HP "Truevision HD" laptop camera                                   | 2         | 0.59%   |
| Realtek HD WebCam                                                          | 2         | 0.59%   |
| Microsoft LifeCam HD-3000                                                  | 2         | 0.59%   |
| Logitech Webcam C270                                                       | 2         | 0.59%   |
| Logitech Webcam B500                                                       | 2         | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 0.59%   |
| Generalplus WEB CAM                                                        | 2         | 0.59%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 2         | 0.59%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.59%   |
| Chicony thinkpad t430s camera                                              | 2         | 0.59%   |
| Chicony HP Wide Vision FHD Camera                                          | 2         | 0.59%   |
| Chicony HP TrueVision HD                                                   | 2         | 0.59%   |
| Chicony HP Integrated Webcam                                               | 2         | 0.59%   |
| Chicony HD WebCam (Asus N-series)                                          | 2         | 0.59%   |
| Chicony FJ Camera                                                          | 2         | 0.59%   |
| Chicony EasyCamera                                                         | 2         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 0.59%   |
| ARC International Camera                                                   | 2         | 0.59%   |
| Alcor Micro USB 2.0 PC cam                                                 | 2         | 0.59%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 0.59%   |
| Acer EasyCamera                                                            | 2         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 31        | 38.75%  |
| Validity Sensors           | 25        | 31.25%  |
| Shenzhen Goodix Technology | 10        | 12.5%   |
| LighTuning Technology      | 6         | 7.5%    |
| Elan Microelectronics      | 5         | 6.25%   |
| AuthenTec                  | 3         | 3.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 12        | 15%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 10%     |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 8.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 5         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5%      |
| Synaptics WBDI Device                                                      | 4         | 5%      |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.75%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 3.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.5%    |
| Validity Sensors VFS491                                                    | 2         | 2.5%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.5%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 2.5%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.25%   |
| Synaptics  WBDI                                                            | 1         | 1.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.25%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.25%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.25%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.25%   |
| AuthenTec AES2810                                                          | 1         | 1.25%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.25%   |
| AuthenTec AES1600                                                          | 1         | 1.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 47.62%  |
| Upek        | 5         | 23.81%  |
| Alcor Micro | 4         | 19.05%  |
| Lenovo      | 2         | 9.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 23.81%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 19.05%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 19.05%  |
| Broadcom 5880                                                                | 3         | 14.29%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 9.52%   |
| Broadcom 58200                                                               | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 332       | 66.94%  |
| 1     | 132       | 26.61%  |
| 2     | 27        | 5.44%   |
| 3     | 3         | 0.6%    |
| 4     | 2         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 79        | 41.58%  |
| Graphics card            | 36        | 18.95%  |
| Chipcard                 | 20        | 10.53%  |
| Net/wireless             | 16        | 8.42%   |
| Communication controller | 13        | 6.84%   |
| Multimedia controller    | 5         | 2.63%   |
| Camera                   | 5         | 2.63%   |
| Storage                  | 3         | 1.58%   |
| Sound                    | 3         | 1.58%   |
| Card reader              | 3         | 1.58%   |
| Bluetooth                | 3         | 1.58%   |
| Unassigned class         | 2         | 1.05%   |
| Net/ethernet             | 2         | 1.05%   |


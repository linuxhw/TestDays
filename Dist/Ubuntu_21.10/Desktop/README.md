Ubuntu 21.10 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Z370 GAMING PLUS            | [72ad880143](https://linux-hardware.org/?probe=72ad880143) | Jan 31, 2022 |
| ASUSTek       | CM6870                      | [f217244fb2](https://linux-hardware.org/?probe=f217244fb2) | Jan 31, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [44411daa5a](https://linux-hardware.org/?probe=44411daa5a) | Jan 31, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [f3ed6567f9](https://linux-hardware.org/?probe=f3ed6567f9) | Jan 31, 2022 |
| BESSTAR Te... | UM300 V1.0                  | [66320a8981](https://linux-hardware.org/?probe=66320a8981) | Jan 31, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [927a82eb86](https://linux-hardware.org/?probe=927a82eb86) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fc9ddc34b0](https://linux-hardware.org/?probe=fc9ddc34b0) | Jan 30, 2022 |
| Gigabyte      | GA-890FXA-UD5               | [a7a2a13e23](https://linux-hardware.org/?probe=a7a2a13e23) | Jan 30, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [87a19ca6bd](https://linux-hardware.org/?probe=87a19ca6bd) | Jan 30, 2022 |
| HP            | 3048h                       | [cb51d0cf78](https://linux-hardware.org/?probe=cb51d0cf78) | Jan 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [38eb148f2e](https://linux-hardware.org/?probe=38eb148f2e) | Jan 29, 2022 |
| ASRock        | H570M-ITX/ac                | [e901364a26](https://linux-hardware.org/?probe=e901364a26) | Jan 28, 2022 |
| ASRock        | 970 Extreme3                | [82d0c3e60e](https://linux-hardware.org/?probe=82d0c3e60e) | Jan 28, 2022 |
| MSI           | B560M PRO                   | [00b3d4717d](https://linux-hardware.org/?probe=00b3d4717d) | Jan 28, 2022 |
| ASRock        | H570M-ITX/ac                | [7295dda221](https://linux-hardware.org/?probe=7295dda221) | Jan 28, 2022 |
| MSI           | B560M PRO                   | [b3a84eebc3](https://linux-hardware.org/?probe=b3a84eebc3) | Jan 28, 2022 |
| Chuwi         | LarkBox                     | [8ddd1a7c4d](https://linux-hardware.org/?probe=8ddd1a7c4d) | Jan 28, 2022 |
| Dell          | 0WMJ54 A01                  | [d4c6610ae0](https://linux-hardware.org/?probe=d4c6610ae0) | Jan 28, 2022 |
| ASUSTek       | H81M-K                      | [74149e531c](https://linux-hardware.org/?probe=74149e531c) | Jan 27, 2022 |
| Gigabyte      | X58A-UD3R                   | [42f1ea1af3](https://linux-hardware.org/?probe=42f1ea1af3) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f967c472e5](https://linux-hardware.org/?probe=f967c472e5) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [e92de9ab2e](https://linux-hardware.org/?probe=e92de9ab2e) | Jan 27, 2022 |
| ASUSTek       | PRIME Z370-A                | [53b2c696ff](https://linux-hardware.org/?probe=53b2c696ff) | Jan 26, 2022 |
| HP            | 8054                        | [332217129d](https://linux-hardware.org/?probe=332217129d) | Jan 26, 2022 |
| ASUSTek       | PRIME Z370-A                | [7b2482036e](https://linux-hardware.org/?probe=7b2482036e) | Jan 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [00cdb626d7](https://linux-hardware.org/?probe=00cdb626d7) | Jan 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [12e94e5413](https://linux-hardware.org/?probe=12e94e5413) | Jan 25, 2022 |
| Gigabyte      | B460M AORUS PRO             | [33521b66a1](https://linux-hardware.org/?probe=33521b66a1) | Jan 25, 2022 |
| Medion        | H110H4-CM2                  | [8574d37f58](https://linux-hardware.org/?probe=8574d37f58) | Jan 25, 2022 |
| Dell          | 0DXYK6 A01                  | [f270a1ab38](https://linux-hardware.org/?probe=f270a1ab38) | Jan 25, 2022 |
| Medion        | P2A4-EM                     | [6e80bcdcd1](https://linux-hardware.org/?probe=6e80bcdcd1) | Jan 24, 2022 |
| Dell          | 0DXYK6 A01                  | [a145a49fc6](https://linux-hardware.org/?probe=a145a49fc6) | Jan 23, 2022 |
| ASUSTek       | D642MF                      | [1d59c9470c](https://linux-hardware.org/?probe=1d59c9470c) | Jan 23, 2022 |
| MSI           | 760GM-P23                   | [65ce5265d3](https://linux-hardware.org/?probe=65ce5265d3) | Jan 23, 2022 |
| Huanan        | X99-BD4 V1.3                | [d9cbf7e314](https://linux-hardware.org/?probe=d9cbf7e314) | Jan 23, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [b1cfd38100](https://linux-hardware.org/?probe=b1cfd38100) | Jan 23, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [b63214b1e1](https://linux-hardware.org/?probe=b63214b1e1) | Jan 23, 2022 |
| ASUSTek       | P8B75-M LX                  | [dc2c32aac2](https://linux-hardware.org/?probe=dc2c32aac2) | Jan 23, 2022 |
| Acer          | FIH57                       | [af79e42583](https://linux-hardware.org/?probe=af79e42583) | Jan 23, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [7f92d6ff46](https://linux-hardware.org/?probe=7f92d6ff46) | Jan 22, 2022 |
| ASUSTek       | PRIME B360M-A               | [3825d7e113](https://linux-hardware.org/?probe=3825d7e113) | Jan 22, 2022 |
| ASUSTek       | H81M-R                      | [d324ae2959](https://linux-hardware.org/?probe=d324ae2959) | Jan 22, 2022 |
| MSI           | H55M-E33                    | [bb0b689514](https://linux-hardware.org/?probe=bb0b689514) | Jan 22, 2022 |
| HP            | 843F                        | [75459e99d4](https://linux-hardware.org/?probe=75459e99d4) | Jan 21, 2022 |
| ASRock        | H510 Pro BTC+               | [ff2dd45add](https://linux-hardware.org/?probe=ff2dd45add) | Jan 21, 2022 |
| ASRock        | H510 Pro BTC+               | [234acd7143](https://linux-hardware.org/?probe=234acd7143) | Jan 21, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [773f86769e](https://linux-hardware.org/?probe=773f86769e) | Jan 21, 2022 |
| MSI           | MS-7469 100                 | [8476ffa27e](https://linux-hardware.org/?probe=8476ffa27e) | Jan 20, 2022 |
| ASUSTek       | Z97-K                       | [7d370214de](https://linux-hardware.org/?probe=7d370214de) | Jan 20, 2022 |
| HP            | 18EB                        | [59cce3a9a2](https://linux-hardware.org/?probe=59cce3a9a2) | Jan 19, 2022 |
| Gigabyte      | X58A-UD3R                   | [93b6fafb6e](https://linux-hardware.org/?probe=93b6fafb6e) | Jan 19, 2022 |
| ASUSTek       | PRIME B350M-A               | [8cf30a73c8](https://linux-hardware.org/?probe=8cf30a73c8) | Jan 19, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [f6a7e71141](https://linux-hardware.org/?probe=f6a7e71141) | Jan 18, 2022 |
| Acer          | Predator G6-710             | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASRock        | Z270M-ITX/ac                | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| Dell          | 0KH290                      | [1ec02399c2](https://linux-hardware.org/?probe=1ec02399c2) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [e3f87f47e8](https://linux-hardware.org/?probe=e3f87f47e8) | Jan 18, 2022 |
| MSI           | A320M-A PRO MAX             | [f8018a96fb](https://linux-hardware.org/?probe=f8018a96fb) | Jan 17, 2022 |
| Lenovo        | ThinkCentre M71e 3157R75    | [871b2aecd9](https://linux-hardware.org/?probe=871b2aecd9) | Jan 17, 2022 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [1668e6dc43](https://linux-hardware.org/?probe=1668e6dc43) | Jan 17, 2022 |
| PCWare        | IPMH61R1                    | [9bad24f3d9](https://linux-hardware.org/?probe=9bad24f3d9) | Jan 17, 2022 |
| Gigabyte      | Z270X-Gaming 5              | [d1cf9b9344](https://linux-hardware.org/?probe=d1cf9b9344) | Jan 17, 2022 |
| Gigabyte      | X58A-UD3R                   | [dc02dbb307](https://linux-hardware.org/?probe=dc02dbb307) | Jan 16, 2022 |
| HP            | 8906 SMVB                   | [566e943f08](https://linux-hardware.org/?probe=566e943f08) | Jan 16, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [17d01b9a1d](https://linux-hardware.org/?probe=17d01b9a1d) | Jan 16, 2022 |
| ASUSTek       | Z97-K                       | [4b03f84c93](https://linux-hardware.org/?probe=4b03f84c93) | Jan 16, 2022 |
| HP            | 8266                        | [c2cbb29774](https://linux-hardware.org/?probe=c2cbb29774) | Jan 15, 2022 |
| HP            | 3048h                       | [d6f6435471](https://linux-hardware.org/?probe=d6f6435471) | Jan 15, 2022 |
| ASUSTek       | SABERTOOTH P67              | [5d9e7dcdd1](https://linux-hardware.org/?probe=5d9e7dcdd1) | Jan 15, 2022 |
| MSI           | Z490-A PRO                  | [62d5c59aec](https://linux-hardware.org/?probe=62d5c59aec) | Jan 15, 2022 |
| HP            | 1495                        | [ea7df45832](https://linux-hardware.org/?probe=ea7df45832) | Jan 14, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [9b8c21a3d0](https://linux-hardware.org/?probe=9b8c21a3d0) | Jan 14, 2022 |
| HP            | 0AECh D                     | [c42b2d840d](https://linux-hardware.org/?probe=c42b2d840d) | Jan 14, 2022 |
| Unknown       | X99-GT                      | [4562aa0142](https://linux-hardware.org/?probe=4562aa0142) | Jan 13, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [7723b652d9](https://linux-hardware.org/?probe=7723b652d9) | Jan 13, 2022 |
| Dell          | 0KWVT8 A00                  | [c4a3e67da7](https://linux-hardware.org/?probe=c4a3e67da7) | Jan 13, 2022 |
| MSI           | H510I PRO WIFI              | [efc8b1b1ff](https://linux-hardware.org/?probe=efc8b1b1ff) | Jan 13, 2022 |
| MSI           | H510I PRO WIFI              | [58bc68bd8c](https://linux-hardware.org/?probe=58bc68bd8c) | Jan 13, 2022 |
| MSI           | A320M-A PRO MAX             | [c0cb966fb7](https://linux-hardware.org/?probe=c0cb966fb7) | Jan 13, 2022 |
| MSI           | Z270 GAMING PLUS            | [bf0493bb07](https://linux-hardware.org/?probe=bf0493bb07) | Jan 13, 2022 |
| MSI           | Z270 GAMING PLUS            | [cbc37c86d0](https://linux-hardware.org/?probe=cbc37c86d0) | Jan 13, 2022 |
| MSI           | Z270 GAMING PLUS            | [126563feda](https://linux-hardware.org/?probe=126563feda) | Jan 13, 2022 |
| MSI           | B75MA-P45                   | [dc73e7a540](https://linux-hardware.org/?probe=dc73e7a540) | Jan 12, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [2b42fd9ee4](https://linux-hardware.org/?probe=2b42fd9ee4) | Jan 12, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [1dd4561367](https://linux-hardware.org/?probe=1dd4561367) | Jan 12, 2022 |
| MSI           | B75MA-P45                   | [60d7670ca3](https://linux-hardware.org/?probe=60d7670ca3) | Jan 12, 2022 |
| Packard Be... | EG43M                       | [bd7097f415](https://linux-hardware.org/?probe=bd7097f415) | Jan 12, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [7dac64a6ff](https://linux-hardware.org/?probe=7dac64a6ff) | Jan 12, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [1e08ba87bd](https://linux-hardware.org/?probe=1e08ba87bd) | Jan 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [2afab06632](https://linux-hardware.org/?probe=2afab06632) | Jan 11, 2022 |
| HP            | 212B                        | [c8d010ae43](https://linux-hardware.org/?probe=c8d010ae43) | Jan 11, 2022 |
| ASRock        | FM2A88M-HD+                 | [2d834a40f5](https://linux-hardware.org/?probe=2d834a40f5) | Jan 10, 2022 |
| MSI           | B550M-A PRO                 | [450ef59cb0](https://linux-hardware.org/?probe=450ef59cb0) | Jan 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b431bed91e](https://linux-hardware.org/?probe=b431bed91e) | Jan 10, 2022 |
| ASUSTek       | H81M-PLUS                   | [67ab65d5f0](https://linux-hardware.org/?probe=67ab65d5f0) | Jan 10, 2022 |
| HP            | 0AECh D                     | [f755fbe60f](https://linux-hardware.org/?probe=f755fbe60f) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | [78f18e59c9](https://linux-hardware.org/?probe=78f18e59c9) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | [569783a078](https://linux-hardware.org/?probe=569783a078) | Jan 09, 2022 |
| Gigabyte      | B85M-D3PH                   | [5602ba99c2](https://linux-hardware.org/?probe=5602ba99c2) | Jan 08, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [72fa18d5dd](https://linux-hardware.org/?probe=72fa18d5dd) | Jan 08, 2022 |
| MSI           | B550M PRO-VDH               | [5c63b79779](https://linux-hardware.org/?probe=5c63b79779) | Jan 07, 2022 |
| MSI           | B150 GAMING M3              | [3514e82b43](https://linux-hardware.org/?probe=3514e82b43) | Jan 07, 2022 |
| TYAN Compu... | Tempest-i5000VS-S5372-LC... | [d1cfd7ca04](https://linux-hardware.org/?probe=d1cfd7ca04) | Jan 07, 2022 |
| ASUSTek       | P8H77-M PRO                 | [14a4cdc223](https://linux-hardware.org/?probe=14a4cdc223) | Jan 06, 2022 |
| MSI           | B450M PRO-M2 MAX            | [32cae94f00](https://linux-hardware.org/?probe=32cae94f00) | Jan 06, 2022 |
| MSI           | B450M PRO-M2 MAX            | [c103969fdf](https://linux-hardware.org/?probe=c103969fdf) | Jan 06, 2022 |
| MSI           | Z390-A PRO                  | [b1fe0d9671](https://linux-hardware.org/?probe=b1fe0d9671) | Jan 06, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f00aac4419](https://linux-hardware.org/?probe=f00aac4419) | Jan 05, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [40324b4766](https://linux-hardware.org/?probe=40324b4766) | Jan 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [81efe23b11](https://linux-hardware.org/?probe=81efe23b11) | Jan 04, 2022 |
| Dell          | 0D28YY A00                  | [8525880542](https://linux-hardware.org/?probe=8525880542) | Jan 04, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [ad7422345b](https://linux-hardware.org/?probe=ad7422345b) | Jan 04, 2022 |
| Intel         | HURONRIVER                  | [85b441d7cb](https://linux-hardware.org/?probe=85b441d7cb) | Jan 04, 2022 |
| MSI           | B85M ECO                    | [927ae260f1](https://linux-hardware.org/?probe=927ae260f1) | Jan 04, 2022 |
| MSI           | A320M-A PRO MAX             | [d595df0e84](https://linux-hardware.org/?probe=d595df0e84) | Jan 04, 2022 |
| MSI           | A320M PRO-VD/S              | [40afcf3662](https://linux-hardware.org/?probe=40afcf3662) | Jan 03, 2022 |
| HP            | 0AECh D                     | [c25b4d18af](https://linux-hardware.org/?probe=c25b4d18af) | Jan 03, 2022 |
| HP            | 82B4                        | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| HP            | 0AECh D                     | [6cf0733967](https://linux-hardware.org/?probe=6cf0733967) | Jan 03, 2022 |
| HP            | 0AECh D                     | [78a40041d5](https://linux-hardware.org/?probe=78a40041d5) | Jan 03, 2022 |
| Biostar       | Z490A-SILVER                | [b5e7622be0](https://linux-hardware.org/?probe=b5e7622be0) | Jan 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [c30b1e6110](https://linux-hardware.org/?probe=c30b1e6110) | Jan 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [eeb310ed49](https://linux-hardware.org/?probe=eeb310ed49) | Jan 02, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [f8f1977c46](https://linux-hardware.org/?probe=f8f1977c46) | Jan 01, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [f5589634ef](https://linux-hardware.org/?probe=f5589634ef) | Jan 01, 2022 |
| MSI           | A320M-A PRO MAX             | [b010826415](https://linux-hardware.org/?probe=b010826415) | Jan 01, 2022 |
| HP            | 0AA0h                       | [bf7b3e968e](https://linux-hardware.org/?probe=bf7b3e968e) | Jan 01, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [3df571fbbb](https://linux-hardware.org/?probe=3df571fbbb) | Jan 01, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [3fe93d0957](https://linux-hardware.org/?probe=3fe93d0957) | Jan 01, 2022 |
| Gigabyte      | Z77X-D3H                    | [3ebf180dc4](https://linux-hardware.org/?probe=3ebf180dc4) | Jan 01, 2022 |
| MSI           | A320M-A PRO MAX             | [6601708090](https://linux-hardware.org/?probe=6601708090) | Dec 31, 2021 |
| MSI           | A320M PRO-M2 V2             | [4e84971678](https://linux-hardware.org/?probe=4e84971678) | Dec 30, 2021 |
| Gigabyte      | X570 GAMING X               | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| MSI           | Q45MDO                      | [e3ea0d80d3](https://linux-hardware.org/?probe=e3ea0d80d3) | Dec 30, 2021 |
| ASUSTek       | P8H61                       | [682efb70d7](https://linux-hardware.org/?probe=682efb70d7) | Dec 29, 2021 |
| Pegatron      | Narra6                      | [da3be9b31b](https://linux-hardware.org/?probe=da3be9b31b) | Dec 29, 2021 |
| ASRock        | B550M-ITX/ac                | [1e4bffb013](https://linux-hardware.org/?probe=1e4bffb013) | Dec 29, 2021 |
| ASRock        | Z170 Gaming K4              | [590ae02fdb](https://linux-hardware.org/?probe=590ae02fdb) | Dec 29, 2021 |
| Gigabyte      | 965P-DS3                    | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| EVGA          | 134-KS-E377                 | [503b4d620c](https://linux-hardware.org/?probe=503b4d620c) | Dec 29, 2021 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [8b006f4339](https://linux-hardware.org/?probe=8b006f4339) | Dec 28, 2021 |
| ASRock        | 4Core1600P35-WiFi+          | [a3af4e5057](https://linux-hardware.org/?probe=a3af4e5057) | Dec 28, 2021 |
| ASRock        | 4Core1600P35-WiFi+          | [bae2ef5b28](https://linux-hardware.org/?probe=bae2ef5b28) | Dec 28, 2021 |
| ASUSTek       | Maximus VIII EXTREME        | [ccc49903fd](https://linux-hardware.org/?probe=ccc49903fd) | Dec 28, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.308     | [cb6cfc3c5e](https://linux-hardware.org/?probe=cb6cfc3c5e) | Dec 27, 2021 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [5ea8f7d7a8](https://linux-hardware.org/?probe=5ea8f7d7a8) | Dec 27, 2021 |
| ASUSTek       | CM6870                      | [0a24371b49](https://linux-hardware.org/?probe=0a24371b49) | Dec 27, 2021 |
| Acer          | Predator PO3-620            | [d33f608e2e](https://linux-hardware.org/?probe=d33f608e2e) | Dec 27, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [9089dc4f34](https://linux-hardware.org/?probe=9089dc4f34) | Dec 27, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [a5e698c32b](https://linux-hardware.org/?probe=a5e698c32b) | Dec 27, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [757d6a5d20](https://linux-hardware.org/?probe=757d6a5d20) | Dec 27, 2021 |
| Dell          | 0HD5W2 A01                  | [143f0ef296](https://linux-hardware.org/?probe=143f0ef296) | Dec 27, 2021 |
| Positivo      | POS-MIH61CF                 | [a8fd13db4c](https://linux-hardware.org/?probe=a8fd13db4c) | Dec 27, 2021 |
| ASUSTek       | P5G41T-M LX3                | [05b30c96fd](https://linux-hardware.org/?probe=05b30c96fd) | Dec 26, 2021 |
| ASRock        | Z690M-ITX/ax                | [0a35834719](https://linux-hardware.org/?probe=0a35834719) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | [4ca65158f1](https://linux-hardware.org/?probe=4ca65158f1) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| Dell          | 0WN7Y6 A01                  | [45220bb46c](https://linux-hardware.org/?probe=45220bb46c) | Dec 26, 2021 |
| ASRock        | Z690M-ITX/ax                | [fcc19136e0](https://linux-hardware.org/?probe=fcc19136e0) | Dec 26, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [8881d4e351](https://linux-hardware.org/?probe=8881d4e351) | Dec 25, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [0ed55de90b](https://linux-hardware.org/?probe=0ed55de90b) | Dec 25, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [e93a789ba7](https://linux-hardware.org/?probe=e93a789ba7) | Dec 25, 2021 |
| Foxconn       | 2ABF                        | [fdc6aac853](https://linux-hardware.org/?probe=fdc6aac853) | Dec 25, 2021 |
| Medion        | MS-7707                     | [2590f9fac3](https://linux-hardware.org/?probe=2590f9fac3) | Dec 25, 2021 |
| Medion        | MS-7707                     | [9a64e7919f](https://linux-hardware.org/?probe=9a64e7919f) | Dec 25, 2021 |
| HP            | 8643 SMVB                   | [18fdb46bb5](https://linux-hardware.org/?probe=18fdb46bb5) | Dec 24, 2021 |
| Positivo      | POS-MIH61CF                 | [f10e90bd72](https://linux-hardware.org/?probe=f10e90bd72) | Dec 24, 2021 |
| Dell          | 0F3KHR A00                  | [3efe58bf92](https://linux-hardware.org/?probe=3efe58bf92) | Dec 24, 2021 |
| HP            | 158A                        | [dc1212a83a](https://linux-hardware.org/?probe=dc1212a83a) | Dec 24, 2021 |
| Gigabyte      | B150M-HD3-CF                | [8b9eeb5990](https://linux-hardware.org/?probe=8b9eeb5990) | Dec 24, 2021 |
| ASUSTek       | TUF GAMING Z690-PLUS WIF... | [26b64d67a9](https://linux-hardware.org/?probe=26b64d67a9) | Dec 24, 2021 |
| HP            | 82B4                        | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| HP            | 83EE                        | [225f3c4b8d](https://linux-hardware.org/?probe=225f3c4b8d) | Dec 24, 2021 |
| Lenovo        | NOK                         | [5671e681fe](https://linux-hardware.org/?probe=5671e681fe) | Dec 24, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [04f1714e45](https://linux-hardware.org/?probe=04f1714e45) | Dec 23, 2021 |
| Dell          | 0WN7Y6 A01                  | [80a3b049dd](https://linux-hardware.org/?probe=80a3b049dd) | Dec 23, 2021 |
| HP            | 3048h                       | [2e47687170](https://linux-hardware.org/?probe=2e47687170) | Dec 23, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [35e30d5285](https://linux-hardware.org/?probe=35e30d5285) | Dec 23, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [040ae5d30d](https://linux-hardware.org/?probe=040ae5d30d) | Dec 23, 2021 |
| MSI           | Z97 GAMING 5                | [4f71fa3090](https://linux-hardware.org/?probe=4f71fa3090) | Dec 23, 2021 |
| ASRock        | Z370 Pro4                   | [482842307e](https://linux-hardware.org/?probe=482842307e) | Dec 23, 2021 |
| Dell          | 0VHWTR A02                  | [3be006d99a](https://linux-hardware.org/?probe=3be006d99a) | Dec 23, 2021 |
| ASUSTek       | P5P43TD PRO                 | [6019461793](https://linux-hardware.org/?probe=6019461793) | Dec 22, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [c66f391530](https://linux-hardware.org/?probe=c66f391530) | Dec 22, 2021 |
| MSI           | H81M PRO-VD                 | [b0c70d78fd](https://linux-hardware.org/?probe=b0c70d78fd) | Dec 22, 2021 |
| Dell          | 0MM599                      | [91a32378db](https://linux-hardware.org/?probe=91a32378db) | Dec 22, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [427ddfb2d9](https://linux-hardware.org/?probe=427ddfb2d9) | Dec 21, 2021 |
| MSI           | B85M ECO                    | [034b632cee](https://linux-hardware.org/?probe=034b632cee) | Dec 21, 2021 |
| MSI           | B85M ECO                    | [9c63b4bd85](https://linux-hardware.org/?probe=9c63b4bd85) | Dec 21, 2021 |
| MSI           | 790XT-G45                   | [8f8e171a52](https://linux-hardware.org/?probe=8f8e171a52) | Dec 20, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [bcd3f5edf4](https://linux-hardware.org/?probe=bcd3f5edf4) | Dec 20, 2021 |
| ASRock        | X58 Extreme3                | [0e188e9dd0](https://linux-hardware.org/?probe=0e188e9dd0) | Dec 19, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [16017b88bc](https://linux-hardware.org/?probe=16017b88bc) | Dec 19, 2021 |
| MSI           | B450 TOMAHAWK               | [125b9e5965](https://linux-hardware.org/?probe=125b9e5965) | Dec 19, 2021 |
| ASUSTek       | M4A77TD PRO                 | [4e65d26e64](https://linux-hardware.org/?probe=4e65d26e64) | Dec 18, 2021 |
| Dell          | 042P49 A02                  | [56afcbdd15](https://linux-hardware.org/?probe=56afcbdd15) | Dec 18, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [1564f2f5ea](https://linux-hardware.org/?probe=1564f2f5ea) | Dec 18, 2021 |
| MSI           | X399 SLI PLUS               | [08c23ed037](https://linux-hardware.org/?probe=08c23ed037) | Dec 17, 2021 |
| ASUSTek       | PRIME B450M-A               | [b639c498bb](https://linux-hardware.org/?probe=b639c498bb) | Dec 17, 2021 |
| MSI           | MAG B460 TORPEDO            | [a26f1ed9a0](https://linux-hardware.org/?probe=a26f1ed9a0) | Dec 17, 2021 |
| Gigabyte      | EP35-DS4                    | [46e2648ab6](https://linux-hardware.org/?probe=46e2648ab6) | Dec 16, 2021 |
| Dell          | 0WR7PY A02                  | [459b162eab](https://linux-hardware.org/?probe=459b162eab) | Dec 16, 2021 |
| Biostar       | H61MLC                      | [ff1c843adf](https://linux-hardware.org/?probe=ff1c843adf) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [6aee0ff442](https://linux-hardware.org/?probe=6aee0ff442) | Dec 15, 2021 |
| ASUSTek       | P6T DELUXE V2               | [275bcfce49](https://linux-hardware.org/?probe=275bcfce49) | Dec 15, 2021 |
| Dell          | 0WN7Y6 A01                  | [48e34ad548](https://linux-hardware.org/?probe=48e34ad548) | Dec 15, 2021 |
| Dell          | 0TP412                      | [8c26fae09d](https://linux-hardware.org/?probe=8c26fae09d) | Dec 15, 2021 |
| Positivo      | POS-MIH61CF                 | [20ecdbd153](https://linux-hardware.org/?probe=20ecdbd153) | Dec 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [906909677d](https://linux-hardware.org/?probe=906909677d) | Dec 14, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [38d013c7db](https://linux-hardware.org/?probe=38d013c7db) | Dec 14, 2021 |
| HP            | 8054                        | [454fd4c8c7](https://linux-hardware.org/?probe=454fd4c8c7) | Dec 13, 2021 |
| ASRock        | Z170 Gaming K4              | [4f8e294d95](https://linux-hardware.org/?probe=4f8e294d95) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | [648ce917b9](https://linux-hardware.org/?probe=648ce917b9) | Dec 13, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [a85c1b3793](https://linux-hardware.org/?probe=a85c1b3793) | Dec 13, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [1ee5ab4347](https://linux-hardware.org/?probe=1ee5ab4347) | Dec 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [6e9b3e47ac](https://linux-hardware.org/?probe=6e9b3e47ac) | Dec 12, 2021 |
| Dell          | 0YXT71 A01                  | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [36f09857c2](https://linux-hardware.org/?probe=36f09857c2) | Dec 12, 2021 |
| ASRock        | N68-GS4 FX                  | [17296e4753](https://linux-hardware.org/?probe=17296e4753) | Dec 11, 2021 |
| ASRock        | N68-GS4 FX                  | [883dca4bce](https://linux-hardware.org/?probe=883dca4bce) | Dec 11, 2021 |
| EVGA          | 134-KS-E377                 | [537cce12a4](https://linux-hardware.org/?probe=537cce12a4) | Dec 11, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [19a0f28f2f](https://linux-hardware.org/?probe=19a0f28f2f) | Dec 11, 2021 |
| EVGA          | 134-KS-E377                 | [1ad3ddd70b](https://linux-hardware.org/?probe=1ad3ddd70b) | Dec 11, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [15df6092b7](https://linux-hardware.org/?probe=15df6092b7) | Dec 11, 2021 |
| ASUSTek       | P5N-D                       | [772d984bb8](https://linux-hardware.org/?probe=772d984bb8) | Dec 10, 2021 |
| Dell          | 03KWTV A02                  | [446130659d](https://linux-hardware.org/?probe=446130659d) | Dec 10, 2021 |
| MSI           | H510I PRO WIFI              | [86ba639fd8](https://linux-hardware.org/?probe=86ba639fd8) | Dec 10, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [2ad79030d4](https://linux-hardware.org/?probe=2ad79030d4) | Dec 10, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8d9bc5957a](https://linux-hardware.org/?probe=8d9bc5957a) | Dec 10, 2021 |
| Dell          | 03KWTV A02                  | [643a045c8b](https://linux-hardware.org/?probe=643a045c8b) | Dec 09, 2021 |
| MSI           | Z87-G45 GAMING              | [1a012f2f1f](https://linux-hardware.org/?probe=1a012f2f1f) | Dec 09, 2021 |
| ASRock        | X58 Extreme3                | [5c8c08277f](https://linux-hardware.org/?probe=5c8c08277f) | Dec 09, 2021 |
| ASRock        | X58 Extreme3                | [73fa8b0ca4](https://linux-hardware.org/?probe=73fa8b0ca4) | Dec 09, 2021 |
| ASUSTek       | PRIME B450M-A               | [b6e2e39051](https://linux-hardware.org/?probe=b6e2e39051) | Dec 09, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [83df1d7ac7](https://linux-hardware.org/?probe=83df1d7ac7) | Dec 09, 2021 |
| ASUSTek       | H97I-PLUS                   | [47f631ff16](https://linux-hardware.org/?probe=47f631ff16) | Dec 09, 2021 |
| Gigabyte      | 945GCM-S2L                  | [a253c74be5](https://linux-hardware.org/?probe=a253c74be5) | Dec 08, 2021 |
| Dell          | 088DT1 A00                  | [1825e90eed](https://linux-hardware.org/?probe=1825e90eed) | Dec 08, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [160b6097cd](https://linux-hardware.org/?probe=160b6097cd) | Dec 08, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [caa363c86c](https://linux-hardware.org/?probe=caa363c86c) | Dec 08, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [38c5e135f8](https://linux-hardware.org/?probe=38c5e135f8) | Dec 08, 2021 |
| MSI           | Z270 GAMING PLUS            | [dc62f56792](https://linux-hardware.org/?probe=dc62f56792) | Dec 08, 2021 |
| OEM           | TOP77D Ver1.0               | [5747ccfcd4](https://linux-hardware.org/?probe=5747ccfcd4) | Dec 07, 2021 |
| Gigabyte      | EX58-UD5                    | [29f0eb6b67](https://linux-hardware.org/?probe=29f0eb6b67) | Dec 07, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [70d51853a0](https://linux-hardware.org/?probe=70d51853a0) | Dec 07, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [c0928aad35](https://linux-hardware.org/?probe=c0928aad35) | Dec 07, 2021 |
| ASRock        | B360M-ITX/ac                | [2490a94114](https://linux-hardware.org/?probe=2490a94114) | Dec 07, 2021 |
| MSI           | MEG X570 ACE                | [ce4bd7acd9](https://linux-hardware.org/?probe=ce4bd7acd9) | Dec 07, 2021 |
| Gigabyte      | B450 AORUS M                | [1493fa959b](https://linux-hardware.org/?probe=1493fa959b) | Dec 06, 2021 |
| EVGA          | 111-CS-E371                 | [e6af9b4e1e](https://linux-hardware.org/?probe=e6af9b4e1e) | Dec 06, 2021 |
| Gigabyte      | B365M DS3H                  | [8365e0bff7](https://linux-hardware.org/?probe=8365e0bff7) | Dec 05, 2021 |
| ASUSTek       | TUF GAMING Z690-PLUS WIF... | [0a69990530](https://linux-hardware.org/?probe=0a69990530) | Dec 05, 2021 |
| Dell          | 0KRC95 A00                  | [d16dfb27de](https://linux-hardware.org/?probe=d16dfb27de) | Dec 05, 2021 |
| ASUSTek       | M4A87TD/USB3                | [6550b760b5](https://linux-hardware.org/?probe=6550b760b5) | Dec 05, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7a511dda3d](https://linux-hardware.org/?probe=7a511dda3d) | Dec 04, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60e7267ddb](https://linux-hardware.org/?probe=60e7267ddb) | Dec 04, 2021 |
| ASUSTek       | PRIME A320M-K               | [1f37d4567d](https://linux-hardware.org/?probe=1f37d4567d) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [142f88e753](https://linux-hardware.org/?probe=142f88e753) | Dec 04, 2021 |
| HP            | 1587h                       | [aaa0c74349](https://linux-hardware.org/?probe=aaa0c74349) | Dec 04, 2021 |
| Gigabyte      | X79-UP4                     | [c98cb8462e](https://linux-hardware.org/?probe=c98cb8462e) | Dec 04, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [a83c80b9bd](https://linux-hardware.org/?probe=a83c80b9bd) | Dec 04, 2021 |
| ASUSTek       | A88XM-PLUS                  | [16fa85e296](https://linux-hardware.org/?probe=16fa85e296) | Dec 03, 2021 |
| ASRock        | ConRoe1333-D667             | [dce4f3f103](https://linux-hardware.org/?probe=dce4f3f103) | Dec 03, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [b9550ddc31](https://linux-hardware.org/?probe=b9550ddc31) | Dec 03, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [61d0324f27](https://linux-hardware.org/?probe=61d0324f27) | Dec 03, 2021 |
| MSI           | B450M-A PRO MAX             | [17a6983b50](https://linux-hardware.org/?probe=17a6983b50) | Dec 03, 2021 |
| Gigabyte      | 970A-DS3P                   | [054aa7b858](https://linux-hardware.org/?probe=054aa7b858) | Dec 02, 2021 |
| OEM           | TOP77D Ver1.0               | [8348cb42fc](https://linux-hardware.org/?probe=8348cb42fc) | Dec 02, 2021 |
| Lenovo        | NO DPK                      | [0d7784e414](https://linux-hardware.org/?probe=0d7784e414) | Dec 02, 2021 |
| Gigabyte      | X570 UD                     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [876f4598f0](https://linux-hardware.org/?probe=876f4598f0) | Dec 01, 2021 |
| HP            | 212B                        | [b8688e6712](https://linux-hardware.org/?probe=b8688e6712) | Dec 01, 2021 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [0e0cd0b225](https://linux-hardware.org/?probe=0e0cd0b225) | Dec 01, 2021 |
| OEM           | TOP77D Ver1.0               | [6b91b58b81](https://linux-hardware.org/?probe=6b91b58b81) | Nov 30, 2021 |
| MSI           | B460M-A PRO                 | [f972dc5e2a](https://linux-hardware.org/?probe=f972dc5e2a) | Nov 30, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [b3f648de8e](https://linux-hardware.org/?probe=b3f648de8e) | Nov 29, 2021 |
| ECS           | G31T-M7                     | [749da166c4](https://linux-hardware.org/?probe=749da166c4) | Nov 29, 2021 |
| ASRock        | G31M-VS                     | [b042297ea5](https://linux-hardware.org/?probe=b042297ea5) | Nov 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [8c2024b822](https://linux-hardware.org/?probe=8c2024b822) | Nov 28, 2021 |
| Dell          | 0WR7PY A01                  | [f886714ec5](https://linux-hardware.org/?probe=f886714ec5) | Nov 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | [17bd2e3558](https://linux-hardware.org/?probe=17bd2e3558) | Nov 28, 2021 |
| ASUSTek       | PRIME B450M-A               | [629e6cac75](https://linux-hardware.org/?probe=629e6cac75) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [88cf97c553](https://linux-hardware.org/?probe=88cf97c553) | Nov 27, 2021 |
| Gigabyte      | P35-S3G                     | [f8b94398df](https://linux-hardware.org/?probe=f8b94398df) | Nov 27, 2021 |
| ASRock        | A320M-HDV R4.0              | [59f124bbad](https://linux-hardware.org/?probe=59f124bbad) | Nov 27, 2021 |
| Pegatron      | 2A86E01                     | [17a1186394](https://linux-hardware.org/?probe=17a1186394) | Nov 26, 2021 |
| Gigabyte      | GA-MA770-UD3                | [551c45ed6b](https://linux-hardware.org/?probe=551c45ed6b) | Nov 26, 2021 |
| HP            | 2129                        | [8379f5fd56](https://linux-hardware.org/?probe=8379f5fd56) | Nov 26, 2021 |
| Gigabyte      | GA-MA770-UD3                | [58da56c671](https://linux-hardware.org/?probe=58da56c671) | Nov 26, 2021 |
| Gigabyte      | H77M-D3H                    | [a2606aebd8](https://linux-hardware.org/?probe=a2606aebd8) | Nov 26, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | [52d32ab3be](https://linux-hardware.org/?probe=52d32ab3be) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1c3cabc42a](https://linux-hardware.org/?probe=1c3cabc42a) | Nov 25, 2021 |
| MSI           | MPG Z590 GAMING CARBON W... | [651bc7560d](https://linux-hardware.org/?probe=651bc7560d) | Nov 25, 2021 |
| Acer          | G31T-M5                     | [a561aa834a](https://linux-hardware.org/?probe=a561aa834a) | Nov 25, 2021 |
| Gigabyte      | 970A-D3P                    | [76e0745afc](https://linux-hardware.org/?probe=76e0745afc) | Nov 24, 2021 |
| ASRock        | A320M-HDV R4.0              | [e7ab7b2011](https://linux-hardware.org/?probe=e7ab7b2011) | Nov 24, 2021 |
| MSI           | H510I PRO WIFI              | [b9b9b8c6ee](https://linux-hardware.org/?probe=b9b9b8c6ee) | Nov 24, 2021 |
| MSI           | H510I PRO WIFI              | [1abf510439](https://linux-hardware.org/?probe=1abf510439) | Nov 24, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [148f8b6de1](https://linux-hardware.org/?probe=148f8b6de1) | Nov 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | [011f4ef64a](https://linux-hardware.org/?probe=011f4ef64a) | Nov 24, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [021d70dbf2](https://linux-hardware.org/?probe=021d70dbf2) | Nov 24, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [bcf9812525](https://linux-hardware.org/?probe=bcf9812525) | Nov 24, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [dab9856bd1](https://linux-hardware.org/?probe=dab9856bd1) | Nov 24, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9bd8ca78c3](https://linux-hardware.org/?probe=9bd8ca78c3) | Nov 24, 2021 |
| HP            | 3397                        | [5412dd8b52](https://linux-hardware.org/?probe=5412dd8b52) | Nov 23, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [2d5ec95a93](https://linux-hardware.org/?probe=2d5ec95a93) | Nov 23, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [3fcd092ee3](https://linux-hardware.org/?probe=3fcd092ee3) | Nov 23, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [8e73316539](https://linux-hardware.org/?probe=8e73316539) | Nov 23, 2021 |
| ASUSTek       | PRIME Z590-P                | [69fe9cde99](https://linux-hardware.org/?probe=69fe9cde99) | Nov 23, 2021 |
| Unknown       | Unknown                     | [57364e93b2](https://linux-hardware.org/?probe=57364e93b2) | Nov 23, 2021 |
| MSI           | PRO Z690-A DDR4             | [1022ba26e4](https://linux-hardware.org/?probe=1022ba26e4) | Nov 22, 2021 |
| JGINYUE       | H97I PLUS V2.0              | [fcefb22fe5](https://linux-hardware.org/?probe=fcefb22fe5) | Nov 22, 2021 |
| Gigabyte      | A320M-DS2-CF                | [02020c5820](https://linux-hardware.org/?probe=02020c5820) | Nov 22, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [c2d85e5d81](https://linux-hardware.org/?probe=c2d85e5d81) | Nov 22, 2021 |
| Gigabyte      | B75M-D3H                    | [939cd87ee7](https://linux-hardware.org/?probe=939cd87ee7) | Nov 22, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [4c603f8b64](https://linux-hardware.org/?probe=4c603f8b64) | Nov 22, 2021 |
| Dell          | 0C27VV A00                  | [d3a7b5b39b](https://linux-hardware.org/?probe=d3a7b5b39b) | Nov 22, 2021 |
| Unknown       | Unknown                     | [ebc991da95](https://linux-hardware.org/?probe=ebc991da95) | Nov 22, 2021 |
| ASRock        | X99M Extreme4               | [3f738eedfc](https://linux-hardware.org/?probe=3f738eedfc) | Nov 22, 2021 |
| Lenovo        | 1036 SDK0T76457 WIN 3915... | [f894442edc](https://linux-hardware.org/?probe=f894442edc) | Nov 22, 2021 |
| ASRock        | Z390 Extreme4               | [12f1aecfc3](https://linux-hardware.org/?probe=12f1aecfc3) | Nov 21, 2021 |
| ASUSTek       | P5L-VM 1394                 | [a43426b94f](https://linux-hardware.org/?probe=a43426b94f) | Nov 21, 2021 |
| ASUSTek       | M2N                         | [06bba5770c](https://linux-hardware.org/?probe=06bba5770c) | Nov 21, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [4edef515e0](https://linux-hardware.org/?probe=4edef515e0) | Nov 21, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [64591821a6](https://linux-hardware.org/?probe=64591821a6) | Nov 20, 2021 |
| Lenovo        | ThinkServer TS140           | [da5af2478e](https://linux-hardware.org/?probe=da5af2478e) | Nov 20, 2021 |
| MSI           | PRO Z690-A DDR4             | [64e545e8b1](https://linux-hardware.org/?probe=64e545e8b1) | Nov 20, 2021 |
| Dell          | 0Y5DDC A00                  | [9f04ac4715](https://linux-hardware.org/?probe=9f04ac4715) | Nov 20, 2021 |
| Fujitsu       | FujitsuTP7000 -1            | [a509f56734](https://linux-hardware.org/?probe=a509f56734) | Nov 20, 2021 |
| ASUSTek       | M2N                         | [dfc5087439](https://linux-hardware.org/?probe=dfc5087439) | Nov 20, 2021 |
| ASUSTek       | PRIME H510M-K               | [dc3ffc2288](https://linux-hardware.org/?probe=dc3ffc2288) | Nov 20, 2021 |
| ASRock        | Z690 Steel Legend           | [73afa3e4f2](https://linux-hardware.org/?probe=73afa3e4f2) | Nov 19, 2021 |
| ASUSTek       | Rampage IV EXTREME          | [50dbf1ce3d](https://linux-hardware.org/?probe=50dbf1ce3d) | Nov 19, 2021 |
| MSI           | Z170A SLI                   | [2705718ac8](https://linux-hardware.org/?probe=2705718ac8) | Nov 19, 2021 |
| Gigabyte      | A320M-H-CF                  | [8eeef70a27](https://linux-hardware.org/?probe=8eeef70a27) | Nov 19, 2021 |
| MSI           | Z270 GAMING PLUS            | [28b50f68d2](https://linux-hardware.org/?probe=28b50f68d2) | Nov 19, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [a1261a6eca](https://linux-hardware.org/?probe=a1261a6eca) | Nov 19, 2021 |
| HP            | ProLiant ML350 Gen9         | [9a5ec34f4b](https://linux-hardware.org/?probe=9a5ec34f4b) | Nov 18, 2021 |
| HP            | 0AECh D                     | [e52cea7894](https://linux-hardware.org/?probe=e52cea7894) | Nov 18, 2021 |
| HP            | 304Ah                       | [988e1e374a](https://linux-hardware.org/?probe=988e1e374a) | Nov 18, 2021 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [61ba55d34f](https://linux-hardware.org/?probe=61ba55d34f) | Nov 18, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [c754a471ba](https://linux-hardware.org/?probe=c754a471ba) | Nov 17, 2021 |
| MSI           | Z97-G45 GAMING              | [fc7a1caa36](https://linux-hardware.org/?probe=fc7a1caa36) | Nov 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [8377977aee](https://linux-hardware.org/?probe=8377977aee) | Nov 17, 2021 |
| Gigabyte      | Z77X-UD5H                   | [f1cd45b49a](https://linux-hardware.org/?probe=f1cd45b49a) | Nov 17, 2021 |
| HP            | 1494                        | [a1e8628159](https://linux-hardware.org/?probe=a1e8628159) | Nov 17, 2021 |
| Gigabyte      | Z690 UD DDR4                | [8435741705](https://linux-hardware.org/?probe=8435741705) | Nov 17, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e460a37b0f](https://linux-hardware.org/?probe=e460a37b0f) | Nov 17, 2021 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [2c5829a148](https://linux-hardware.org/?probe=2c5829a148) | Nov 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3cc581951b](https://linux-hardware.org/?probe=3cc581951b) | Nov 17, 2021 |
| MSI           | H270 GAMING M3              | [d863ad50dd](https://linux-hardware.org/?probe=d863ad50dd) | Nov 16, 2021 |
| Dell          | 0FM586                      | [79a63f7f55](https://linux-hardware.org/?probe=79a63f7f55) | Nov 16, 2021 |
| MSI           | PRO Z690-A DDR4             | [63c901cb53](https://linux-hardware.org/?probe=63c901cb53) | Nov 16, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | [22cf0835fb](https://linux-hardware.org/?probe=22cf0835fb) | Nov 16, 2021 |
| Dell          | 0Y5DDC A00                  | [f90eb0a986](https://linux-hardware.org/?probe=f90eb0a986) | Nov 16, 2021 |
| Dell          | 088DT1 A00                  | [0a20b8ab82](https://linux-hardware.org/?probe=0a20b8ab82) | Nov 16, 2021 |
| MSI           | MEG B550 UNIFY-X            | [c50d253bab](https://linux-hardware.org/?probe=c50d253bab) | Nov 16, 2021 |
| MSI           | MEG B550 UNIFY-X            | [d9142d6737](https://linux-hardware.org/?probe=d9142d6737) | Nov 16, 2021 |
| HP            | 8056                        | [f62a924908](https://linux-hardware.org/?probe=f62a924908) | Nov 16, 2021 |
| ASRock        | Z590M-ITX/ax                | [aa81c59d8a](https://linux-hardware.org/?probe=aa81c59d8a) | Nov 16, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | [1eac89d527](https://linux-hardware.org/?probe=1eac89d527) | Nov 15, 2021 |
| Gigabyte      | A320M-H-CF                  | [a8e3d44c9e](https://linux-hardware.org/?probe=a8e3d44c9e) | Nov 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [1755230380](https://linux-hardware.org/?probe=1755230380) | Nov 15, 2021 |
| MSI           | MS-7250                     | [84c50a42f3](https://linux-hardware.org/?probe=84c50a42f3) | Nov 15, 2021 |
| Dell          | 0HJ054                      | [f7dee29940](https://linux-hardware.org/?probe=f7dee29940) | Nov 14, 2021 |
| Dell          | 0VRWRC A01                  | [e202cef308](https://linux-hardware.org/?probe=e202cef308) | Nov 14, 2021 |
| Pegatron      | 2AB6                        | [3f03379235](https://linux-hardware.org/?probe=3f03379235) | Nov 14, 2021 |
| HP            | 1998                        | [2e830badd5](https://linux-hardware.org/?probe=2e830badd5) | Nov 14, 2021 |
| ASUSTek       | PRIME Z370-A                | [01b7731b34](https://linux-hardware.org/?probe=01b7731b34) | Nov 14, 2021 |
| ASUSTek       | Z87-EXPERT                  | [445090e2b7](https://linux-hardware.org/?probe=445090e2b7) | Nov 14, 2021 |
| Dell          | 0HJ054                      | [298206106c](https://linux-hardware.org/?probe=298206106c) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b1edada81b](https://linux-hardware.org/?probe=b1edada81b) | Nov 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [7ae75212ce](https://linux-hardware.org/?probe=7ae75212ce) | Nov 13, 2021 |
| ASUSTek       | H110M-C                     | [594c61d37a](https://linux-hardware.org/?probe=594c61d37a) | Nov 13, 2021 |
| MSI           | MS-7346                     | [66b30282c8](https://linux-hardware.org/?probe=66b30282c8) | Nov 13, 2021 |
| Acer          | RS780DV                     | [415847f244](https://linux-hardware.org/?probe=415847f244) | Nov 13, 2021 |
| Dell          | 0Y5DDC A00                  | [66188284bd](https://linux-hardware.org/?probe=66188284bd) | Nov 13, 2021 |
| Dell          | 0WMJ54 A01                  | [12892e0de3](https://linux-hardware.org/?probe=12892e0de3) | Nov 13, 2021 |
| Acer          | RS780DV                     | [610927f2e1](https://linux-hardware.org/?probe=610927f2e1) | Nov 12, 2021 |
| Gigabyte      | Z690 UD DDR4                | [8ca8eff19e](https://linux-hardware.org/?probe=8ca8eff19e) | Nov 12, 2021 |
| Gigabyte      | Z690 UD DDR4                | [7f1c2cfc0b](https://linux-hardware.org/?probe=7f1c2cfc0b) | Nov 12, 2021 |
| Dell          | 0WMJ54 A01                  | [eccf63021f](https://linux-hardware.org/?probe=eccf63021f) | Nov 12, 2021 |
| MSI           | B75MA-P45                   | [8196870f95](https://linux-hardware.org/?probe=8196870f95) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-K               | [e995b26637](https://linux-hardware.org/?probe=e995b26637) | Nov 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [867958b2cc](https://linux-hardware.org/?probe=867958b2cc) | Nov 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [27171367d8](https://linux-hardware.org/?probe=27171367d8) | Nov 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [15600f6f21](https://linux-hardware.org/?probe=15600f6f21) | Nov 11, 2021 |
| Dell          | 08HPGT A02                  | [9bf3a3f311](https://linux-hardware.org/?probe=9bf3a3f311) | Nov 10, 2021 |
| ASRock        | Z370 Pro4                   | [e0856ca7fa](https://linux-hardware.org/?probe=e0856ca7fa) | Nov 10, 2021 |
| HP            | 1494                        | [b748a69ed1](https://linux-hardware.org/?probe=b748a69ed1) | Nov 10, 2021 |
| ASRock        | A300M-STX                   | [712e203294](https://linux-hardware.org/?probe=712e203294) | Nov 10, 2021 |
| Gigabyte      | GA-790XTA-UD4               | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| ASUSTek       | P5QP18L/T5-P5G41E           | [c64c41d162](https://linux-hardware.org/?probe=c64c41d162) | Nov 10, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [6f7902132b](https://linux-hardware.org/?probe=6f7902132b) | Nov 10, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [da9d9b9d1e](https://linux-hardware.org/?probe=da9d9b9d1e) | Nov 10, 2021 |
| EVGA          | 111-CS-E371                 | [fd202c951f](https://linux-hardware.org/?probe=fd202c951f) | Nov 09, 2021 |
| Gigabyte      | B85M-D2V                    | [6fbd588373](https://linux-hardware.org/?probe=6fbd588373) | Nov 09, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [2458e67cf5](https://linux-hardware.org/?probe=2458e67cf5) | Nov 09, 2021 |
| MSI           | B350M PRO-VDH               | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| HP            | 1998                        | [c2ab98c42f](https://linux-hardware.org/?probe=c2ab98c42f) | Nov 07, 2021 |
| ASUSTek       | H87-PLUS                    | [a699d4683c](https://linux-hardware.org/?probe=a699d4683c) | Nov 07, 2021 |
| MSI           | MAG B550M MORTAR            | [35b24a070f](https://linux-hardware.org/?probe=35b24a070f) | Nov 07, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [3cf5d9865c](https://linux-hardware.org/?probe=3cf5d9865c) | Nov 07, 2021 |
| HP            | 0A98h                       | [faff7d4f1b](https://linux-hardware.org/?probe=faff7d4f1b) | Nov 07, 2021 |
| MSI           | MEG X570 UNIFY              | [651ac91f37](https://linux-hardware.org/?probe=651ac91f37) | Nov 06, 2021 |
| Lenovo        | ThinkCentre A62 9935B5U     | [85db2ee229](https://linux-hardware.org/?probe=85db2ee229) | Nov 06, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [9ceab9ce1b](https://linux-hardware.org/?probe=9ceab9ce1b) | Nov 06, 2021 |
| Lenovo        | SHARKBAY No DPK             | [92be8f6c8b](https://linux-hardware.org/?probe=92be8f6c8b) | Nov 06, 2021 |
| HP            | Compaq 8200 Elite SFF PC    | [8227932323](https://linux-hardware.org/?probe=8227932323) | Nov 06, 2021 |
| Dell          | 088DT1 A00                  | [1c0647daa9](https://linux-hardware.org/?probe=1c0647daa9) | Nov 05, 2021 |
| Gigabyte      | H510M S2H                   | [1a749d9336](https://linux-hardware.org/?probe=1a749d9336) | Nov 05, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [6d1875bdd9](https://linux-hardware.org/?probe=6d1875bdd9) | Nov 04, 2021 |
| MSI           | A75MA-G55                   | [ccdd789559](https://linux-hardware.org/?probe=ccdd789559) | Nov 04, 2021 |
| MSI           | B150 PC MATE                | [3fdd2f72ac](https://linux-hardware.org/?probe=3fdd2f72ac) | Nov 04, 2021 |
| Dell          | 0NW73C A00                  | [b02dd0e75e](https://linux-hardware.org/?probe=b02dd0e75e) | Nov 04, 2021 |
| MSI           | 3664h                       | [f2547bae94](https://linux-hardware.org/?probe=f2547bae94) | Nov 03, 2021 |
| Gigabyte      | GA-MA74GMT-S2               | [a94050d3b2](https://linux-hardware.org/?probe=a94050d3b2) | Nov 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f8baadef0e](https://linux-hardware.org/?probe=f8baadef0e) | Nov 03, 2021 |
| Dell          | 0YXT71 A01                  | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| ASUSTek       | Z97-K                       | [1e136c311c](https://linux-hardware.org/?probe=1e136c311c) | Nov 03, 2021 |
| Dell          | 0N826N A03                  | [d7d0a0b507](https://linux-hardware.org/?probe=d7d0a0b507) | Nov 03, 2021 |
| Gigabyte      | EP45-UD3R                   | [30d809be04](https://linux-hardware.org/?probe=30d809be04) | Nov 03, 2021 |
| MSI           | Z370M MORTAR                | [b6d4cdb6b9](https://linux-hardware.org/?probe=b6d4cdb6b9) | Nov 03, 2021 |
| MSI           | Z370M MORTAR                | [af4e356569](https://linux-hardware.org/?probe=af4e356569) | Nov 03, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [2e8569e851](https://linux-hardware.org/?probe=2e8569e851) | Nov 02, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [290c114444](https://linux-hardware.org/?probe=290c114444) | Nov 02, 2021 |
| MSI           | 3664h                       | [61d2ff264b](https://linux-hardware.org/?probe=61d2ff264b) | Nov 02, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [ebaea435bf](https://linux-hardware.org/?probe=ebaea435bf) | Nov 02, 2021 |
| ASUSTek       | M3N78                       | [07562bbf08](https://linux-hardware.org/?probe=07562bbf08) | Nov 01, 2021 |
| MSI           | B550-A PRO                  | [ee7c2851a5](https://linux-hardware.org/?probe=ee7c2851a5) | Nov 01, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [e4aeb69a18](https://linux-hardware.org/?probe=e4aeb69a18) | Nov 01, 2021 |
| EVGA          | Z390 FTW                    | [22e9e0f01b](https://linux-hardware.org/?probe=22e9e0f01b) | Nov 01, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [2bee1e8a30](https://linux-hardware.org/?probe=2bee1e8a30) | Nov 01, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [3676c4f8f0](https://linux-hardware.org/?probe=3676c4f8f0) | Nov 01, 2021 |
| EVGA          | 134-KS-E377                 | [27e29303bc](https://linux-hardware.org/?probe=27e29303bc) | Nov 01, 2021 |
| EVGA          | 111-CS-E371                 | [2fc377709d](https://linux-hardware.org/?probe=2fc377709d) | Nov 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [068bee7912](https://linux-hardware.org/?probe=068bee7912) | Oct 31, 2021 |
| Gigabyte      | G1.Assassin                 | [40c84c9637](https://linux-hardware.org/?probe=40c84c9637) | Oct 31, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [5b55e39c35](https://linux-hardware.org/?probe=5b55e39c35) | Oct 31, 2021 |
| ASUSTek       | M2N-E                       | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| HP            | 1587h                       | [0d99c162a3](https://linux-hardware.org/?probe=0d99c162a3) | Oct 31, 2021 |
| HP            | 1587h                       | [2aeea457fd](https://linux-hardware.org/?probe=2aeea457fd) | Oct 31, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [46ebbae78b](https://linux-hardware.org/?probe=46ebbae78b) | Oct 31, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [e13dd10e78](https://linux-hardware.org/?probe=e13dd10e78) | Oct 31, 2021 |
| Gigabyte      | G31M-ES2L                   | [23b6458508](https://linux-hardware.org/?probe=23b6458508) | Oct 30, 2021 |
| ASUSTek       | PRIME H310T R2.0            | [9f69e439bc](https://linux-hardware.org/?probe=9f69e439bc) | Oct 30, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [0184e22e18](https://linux-hardware.org/?probe=0184e22e18) | Oct 30, 2021 |
| ASRock        | 960GM/U3S3 FX               | [7a2ec5ecff](https://linux-hardware.org/?probe=7a2ec5ecff) | Oct 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [4f64db367f](https://linux-hardware.org/?probe=4f64db367f) | Oct 30, 2021 |
| HP            | 0AA8h                       | [40da7a8ae9](https://linux-hardware.org/?probe=40da7a8ae9) | Oct 30, 2021 |
| Dell          | 0N826N A03                  | [ffb75356ef](https://linux-hardware.org/?probe=ffb75356ef) | Oct 30, 2021 |
| MSI           | 3664h                       | [7d44291de8](https://linux-hardware.org/?probe=7d44291de8) | Oct 30, 2021 |
| MSI           | B450M MORTAR MAX            | [cadb142111](https://linux-hardware.org/?probe=cadb142111) | Oct 29, 2021 |
| MSI           | B150M BAZOOKA               | [b396e1c4f4](https://linux-hardware.org/?probe=b396e1c4f4) | Oct 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | [2ce7e668c7](https://linux-hardware.org/?probe=2ce7e668c7) | Oct 29, 2021 |
| Dell          | 0N826N A03                  | [db2a7eba35](https://linux-hardware.org/?probe=db2a7eba35) | Oct 29, 2021 |
| HP            | 0AECh D                     | [665bae2867](https://linux-hardware.org/?probe=665bae2867) | Oct 29, 2021 |
| Dell          | 0C3YXR A00                  | [3fbbe71d21](https://linux-hardware.org/?probe=3fbbe71d21) | Oct 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [89c1a7f472](https://linux-hardware.org/?probe=89c1a7f472) | Oct 28, 2021 |
| Dell          | 0773VG A00                  | [f17f22efdc](https://linux-hardware.org/?probe=f17f22efdc) | Oct 28, 2021 |
| ASUSTek       | CM6870                      | [1575e2c682](https://linux-hardware.org/?probe=1575e2c682) | Oct 28, 2021 |
| MSI           | A88X-G43                    | [1c7a02bd63](https://linux-hardware.org/?probe=1c7a02bd63) | Oct 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d10e4364a0](https://linux-hardware.org/?probe=d10e4364a0) | Oct 27, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [28ddff13b5](https://linux-hardware.org/?probe=28ddff13b5) | Oct 27, 2021 |
| Foxconn       | 2ABF                        | [380d5ab9f0](https://linux-hardware.org/?probe=380d5ab9f0) | Oct 27, 2021 |
| Dell          | 05CNYF A01                  | [95530db3a8](https://linux-hardware.org/?probe=95530db3a8) | Oct 27, 2021 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [0e8d69e9b8](https://linux-hardware.org/?probe=0e8d69e9b8) | Oct 27, 2021 |
| Acer          | Aspire X3450                | [8f27aff70b](https://linux-hardware.org/?probe=8f27aff70b) | Oct 27, 2021 |
| Gigabyte      | GA-970A-UD3                 | [aae0c56d3a](https://linux-hardware.org/?probe=aae0c56d3a) | Oct 27, 2021 |
| MSI           | H61M-P31                    | [e5bf692305](https://linux-hardware.org/?probe=e5bf692305) | Oct 26, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [16a6718949](https://linux-hardware.org/?probe=16a6718949) | Oct 26, 2021 |
| MSI           | Z270 PC MATE                | [24329438d1](https://linux-hardware.org/?probe=24329438d1) | Oct 26, 2021 |
| Unknown       | Unknown                     | [668f61352d](https://linux-hardware.org/?probe=668f61352d) | Oct 26, 2021 |
| ASRock        | Z590M-ITX/ax                | [1fcc4e6895](https://linux-hardware.org/?probe=1fcc4e6895) | Oct 26, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [f5ede0a97c](https://linux-hardware.org/?probe=f5ede0a97c) | Oct 25, 2021 |
| ASUSTek       | PRIME B350M-A               | [19eba77c24](https://linux-hardware.org/?probe=19eba77c24) | Oct 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [97620628a8](https://linux-hardware.org/?probe=97620628a8) | Oct 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [f15c4d9b54](https://linux-hardware.org/?probe=f15c4d9b54) | Oct 25, 2021 |
| Gigabyte      | P67A-UD3                    | [ecaeb257a3](https://linux-hardware.org/?probe=ecaeb257a3) | Oct 24, 2021 |
| Dell          | 0V8F20 A01                  | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| Dell          | 0J3C2F A01                  | [e8cf16b696](https://linux-hardware.org/?probe=e8cf16b696) | Oct 24, 2021 |
| AMI           | Cherry Trail CR             | [9333e233d6](https://linux-hardware.org/?probe=9333e233d6) | Oct 24, 2021 |
| AMI           | Cherry Trail CR             | [7d78a3c31f](https://linux-hardware.org/?probe=7d78a3c31f) | Oct 24, 2021 |
| ASUSTek       | H110M-C                     | [ba3ddf870d](https://linux-hardware.org/?probe=ba3ddf870d) | Oct 24, 2021 |
| ASUSTek       | PRIME Z390-P                | [681b537e82](https://linux-hardware.org/?probe=681b537e82) | Oct 23, 2021 |
| Lenovo        | NO DPK                      | [9c71a67df3](https://linux-hardware.org/?probe=9c71a67df3) | Oct 23, 2021 |
| Acer          | Aspire TC-281               | [5114976821](https://linux-hardware.org/?probe=5114976821) | Oct 23, 2021 |
| ASRock        | N3150DC-ITX                 | [6e3084cf7f](https://linux-hardware.org/?probe=6e3084cf7f) | Oct 23, 2021 |
| ASRock        | N3150DC-ITX                 | [c1808f5d2f](https://linux-hardware.org/?probe=c1808f5d2f) | Oct 23, 2021 |
| Dell          | 0T10XW A00                  | [971b85f5db](https://linux-hardware.org/?probe=971b85f5db) | Oct 23, 2021 |
| ASUSTek       | PRIME X470-PRO              | [48db1afdd3](https://linux-hardware.org/?probe=48db1afdd3) | Oct 23, 2021 |
| Supermicro    | X7DVL                       | [bcbe094156](https://linux-hardware.org/?probe=bcbe094156) | Oct 23, 2021 |
| Dell          | 051FJ8 A02                  | [d04dae2a56](https://linux-hardware.org/?probe=d04dae2a56) | Oct 23, 2021 |
| MSI           | MEG X570 UNIFY              | [7b9e7ec5f4](https://linux-hardware.org/?probe=7b9e7ec5f4) | Oct 23, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [e071387ed6](https://linux-hardware.org/?probe=e071387ed6) | Oct 22, 2021 |
| Lenovo        | NO DPK                      | [ad7c805198](https://linux-hardware.org/?probe=ad7c805198) | Oct 22, 2021 |
| Dell          | 0J3C2F A01                  | [a5ca7f2501](https://linux-hardware.org/?probe=a5ca7f2501) | Oct 22, 2021 |
| Gigabyte      | B550 AORUS PRO              | [f5c3648170](https://linux-hardware.org/?probe=f5c3648170) | Oct 22, 2021 |
| Gigabyte      | B75M-D3H                    | [74c2c9d725](https://linux-hardware.org/?probe=74c2c9d725) | Oct 22, 2021 |
| Dell          | 0N826N A03                  | [5fea6b8b9a](https://linux-hardware.org/?probe=5fea6b8b9a) | Oct 22, 2021 |
| Dell          | 0N826N A03                  | [eb508ab31e](https://linux-hardware.org/?probe=eb508ab31e) | Oct 22, 2021 |
| ICP / iEi     | SA58 V1.01                  | [bca4498e5d](https://linux-hardware.org/?probe=bca4498e5d) | Oct 21, 2021 |
| Dell          | 0200DY A01                  | [c67a8bb677](https://linux-hardware.org/?probe=c67a8bb677) | Oct 21, 2021 |
| Gigabyte      | B450M S2H                   | [71c19b42fc](https://linux-hardware.org/?probe=71c19b42fc) | Oct 21, 2021 |
| Google        | Guado                       | [5aba3d29f4](https://linux-hardware.org/?probe=5aba3d29f4) | Oct 21, 2021 |
| Google        | Guado                       | [2393c52b33](https://linux-hardware.org/?probe=2393c52b33) | Oct 21, 2021 |
| MSI           | B450M PRO-VDH MAX           | [b914028ca9](https://linux-hardware.org/?probe=b914028ca9) | Oct 20, 2021 |
| ASRock        | TRX40 Creator               | [8789f3f1e1](https://linux-hardware.org/?probe=8789f3f1e1) | Oct 20, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [1d5227420f](https://linux-hardware.org/?probe=1d5227420f) | Oct 20, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [b961168b44](https://linux-hardware.org/?probe=b961168b44) | Oct 20, 2021 |
| ASUSTek       | Q87M-E                      | [a549c95cbd](https://linux-hardware.org/?probe=a549c95cbd) | Oct 20, 2021 |
| MSI           | 2A9C                        | [a47442aa1f](https://linux-hardware.org/?probe=a47442aa1f) | Oct 19, 2021 |
| Gigabyte      | H61M-S1                     | [9978664bd7](https://linux-hardware.org/?probe=9978664bd7) | Oct 19, 2021 |
| Gigabyte      | H61M-S1                     | [b0fb0061f2](https://linux-hardware.org/?probe=b0fb0061f2) | Oct 19, 2021 |
| ASUSTek       | P7P55 LX                    | [d2e3eb969f](https://linux-hardware.org/?probe=d2e3eb969f) | Oct 18, 2021 |
| ASRock        | B450 Gaming K4              | [92647c0170](https://linux-hardware.org/?probe=92647c0170) | Oct 18, 2021 |
| ASRock        | B450 Gaming K4              | [c7372168fd](https://linux-hardware.org/?probe=c7372168fd) | Oct 18, 2021 |
| ASRock        | Z87 Extreme4                | [2ec87a3f6f](https://linux-hardware.org/?probe=2ec87a3f6f) | Oct 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [20ca9b4679](https://linux-hardware.org/?probe=20ca9b4679) | Oct 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7e6f5e6e9f](https://linux-hardware.org/?probe=7e6f5e6e9f) | Oct 18, 2021 |
| Acer          | Aspire XC600 v1.0           | [56dd661396](https://linux-hardware.org/?probe=56dd661396) | Oct 18, 2021 |
| Gigabyte      | GA-MA785GM-US2H             | [6522d9dc18](https://linux-hardware.org/?probe=6522d9dc18) | Oct 18, 2021 |
| HP            | 1998                        | [3228ce7734](https://linux-hardware.org/?probe=3228ce7734) | Oct 18, 2021 |
| EPSON DIRE... | ST170E                      | [dfa0ed56ab](https://linux-hardware.org/?probe=dfa0ed56ab) | Oct 18, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [fcc82222d9](https://linux-hardware.org/?probe=fcc82222d9) | Oct 17, 2021 |
| MSI           | Z77A-G45                    | [3d516c23c5](https://linux-hardware.org/?probe=3d516c23c5) | Oct 17, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [7313df4bd9](https://linux-hardware.org/?probe=7313df4bd9) | Oct 17, 2021 |
| Gigabyte      | Z77-D3H                     | [f7ffa54af0](https://linux-hardware.org/?probe=f7ffa54af0) | Oct 17, 2021 |
| Gigabyte      | M68MT-S2P                   | [d10202fe29](https://linux-hardware.org/?probe=d10202fe29) | Oct 17, 2021 |
| ASRock        | B560M-HDV                   | [200bfff8ba](https://linux-hardware.org/?probe=200bfff8ba) | Oct 17, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [122a03804e](https://linux-hardware.org/?probe=122a03804e) | Oct 17, 2021 |
| Intel         | DG31PR AAE39516-304         | [b6addf8d7b](https://linux-hardware.org/?probe=b6addf8d7b) | Oct 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [dd6513e107](https://linux-hardware.org/?probe=dd6513e107) | Oct 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [35b768567f](https://linux-hardware.org/?probe=35b768567f) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [8c1989ae75](https://linux-hardware.org/?probe=8c1989ae75) | Oct 16, 2021 |
| HP            | 870C                        | [8b056a8a9f](https://linux-hardware.org/?probe=8b056a8a9f) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [8b50d81590](https://linux-hardware.org/?probe=8b50d81590) | Oct 16, 2021 |
| Dell          | 0G214D A00                  | [69857eb3a8](https://linux-hardware.org/?probe=69857eb3a8) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7f15c21293](https://linux-hardware.org/?probe=7f15c21293) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [6c2357c3a8](https://linux-hardware.org/?probe=6c2357c3a8) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [6e15fcad52](https://linux-hardware.org/?probe=6e15fcad52) | Oct 15, 2021 |
| Pegatron      | Eureka3                     | [6499d1cf77](https://linux-hardware.org/?probe=6499d1cf77) | Oct 15, 2021 |
| Pegatron      | Eureka3                     | [a456734f94](https://linux-hardware.org/?probe=a456734f94) | Oct 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [e646d30e4f](https://linux-hardware.org/?probe=e646d30e4f) | Oct 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [152b670fcb](https://linux-hardware.org/?probe=152b670fcb) | Oct 15, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [22b047f0a1](https://linux-hardware.org/?probe=22b047f0a1) | Oct 15, 2021 |
| ASRock        | 990FX Extreme3              | [5de7270820](https://linux-hardware.org/?probe=5de7270820) | Oct 11, 2021 |
| ASRock        | 990FX Extreme3              | [b4eb4dbe24](https://linux-hardware.org/?probe=b4eb4dbe24) | Oct 11, 2021 |
| Dell          | 0Y2MRG A00                  | [d60ca7a452](https://linux-hardware.org/?probe=d60ca7a452) | Oct 09, 2021 |
| HP            | 3647h                       | [729a9e9683](https://linux-hardware.org/?probe=729a9e9683) | Oct 05, 2021 |
| ASRock        | X370 Killer SLI/ac          | [52d4dd8f39](https://linux-hardware.org/?probe=52d4dd8f39) | Oct 02, 2021 |
| Dell          | 0RY007                      | [4e574a8988](https://linux-hardware.org/?probe=4e574a8988) | Oct 02, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [db26b44773](https://linux-hardware.org/?probe=db26b44773) | Oct 02, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [3be52ed98f](https://linux-hardware.org/?probe=3be52ed98f) | Oct 02, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [b6f82cf92b](https://linux-hardware.org/?probe=b6f82cf92b) | Sep 30, 2021 |
| Intel         | DG41WV AAE90316-103         | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| ASUSTek       | A68HM-PLUS                  | [8ea8e6afe8](https://linux-hardware.org/?probe=8ea8e6afe8) | Sep 30, 2021 |
| ASRock        | 990FX Extreme4              | [9c631b51b1](https://linux-hardware.org/?probe=9c631b51b1) | Sep 28, 2021 |
| Gigabyte      | H81M-D2V                    | [e8749db36a](https://linux-hardware.org/?probe=e8749db36a) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [aa1a6086e7](https://linux-hardware.org/?probe=aa1a6086e7) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [b05cdb0bab](https://linux-hardware.org/?probe=b05cdb0bab) | Sep 26, 2021 |
| ASRock        | X399M Taichi                | [eba541c6b9](https://linux-hardware.org/?probe=eba541c6b9) | Sep 25, 2021 |
| Gigabyte      | H81M-S                      | [357f7466e6](https://linux-hardware.org/?probe=357f7466e6) | Sep 25, 2021 |
| ASRock        | Z390M Pro4                  | [138ae00012](https://linux-hardware.org/?probe=138ae00012) | Sep 23, 2021 |
| Medion        | B360H4-EM V1.0              | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Gigabyte      | B85M-D3H                    | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| HP            | 3032h                       | [3fad749d1a](https://linux-hardware.org/?probe=3fad749d1a) | Sep 12, 2021 |
| Huanan        | X99 F8D V2.2                | [c080ec772f](https://linux-hardware.org/?probe=c080ec772f) | Sep 03, 2021 |
| Huanan        | X99 F8D V2.2                | [30fe8d6bb3](https://linux-hardware.org/?probe=30fe8d6bb3) | Aug 26, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1a371ea24e](https://linux-hardware.org/?probe=1a371ea24e) | Aug 16, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| MSI           | MAG B550M MORTAR            | [912b2a77a2](https://linux-hardware.org/?probe=912b2a77a2) | Aug 05, 2021 |
| Huanan        | X99 F8D V2.2                | [74e4c61bbf](https://linux-hardware.org/?probe=74e4c61bbf) | Jul 23, 2021 |
| Huanan        | X99 F8D V2.2                | [02ad72fb54](https://linux-hardware.org/?probe=02ad72fb54) | Jul 21, 2021 |
| Gigabyte      | F2A55M-HD2                  | [6a69f09403](https://linux-hardware.org/?probe=6a69f09403) | Jul 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.13.0-22-generic           | 101      | 22.9%   |
| 5.13.0-21-generic           | 82       | 18.59%  |
| 5.13.0-20-generic           | 70       | 15.87%  |
| 5.13.0-19-generic           | 61       | 13.83%  |
| 5.13.0-27-generic           | 30       | 6.8%    |
| 5.13.0-23-generic           | 28       | 6.35%   |
| 5.13.0-25-generic           | 21       | 4.76%   |
| 5.13.0-16-generic           | 12       | 2.72%   |
| 5.15.2-051502-generic       | 5        | 1.13%   |
| 5.13.0-28-generic           | 3        | 0.68%   |
| 5.13.0-14-generic           | 3        | 0.68%   |
| 5.14.0-051400rc7-lowlatency | 2        | 0.45%   |
| 5.13.0-24-generic           | 2        | 0.45%   |
| 5.13.0-22-lowlatency        | 2        | 0.45%   |
| 5.13.0-192110311031-generic | 2        | 0.45%   |
| 5.13.0-17-generic           | 2        | 0.45%   |
| 5.13.0-12-generic           | 2        | 0.45%   |
| 5.8.0-50-generic            | 1        | 0.23%   |
| 5.16.1-tkg-pds              | 1        | 0.23%   |
| 5.16.0                      | 1        | 0.23%   |
| 5.15.11-051511-generic      | 1        | 0.23%   |
| 5.15.0                      | 1        | 0.23%   |
| 5.14.15                     | 1        | 0.23%   |
| 5.14.14-xanmod2             | 1        | 0.23%   |
| 5.14.14-051414-generic      | 1        | 0.23%   |
| 5.13.0-1010-oracle          | 1        | 0.23%   |
| 5.13.0-051300-generic       | 1        | 0.23%   |
| 5.11.0-44-generic           | 1        | 0.23%   |
| 5.11.0-25-generic           | 1        | 0.23%   |
| 5.11.0-20-generic           | 1        | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 403      | 95.72%  |
| 5.15.2  | 5        | 1.19%   |
| 5.11.0  | 3        | 0.71%   |
| 5.14.14 | 2        | 0.48%   |
| 5.14.0  | 2        | 0.48%   |
| 5.8.0   | 1        | 0.24%   |
| 5.16.1  | 1        | 0.24%   |
| 5.16.0  | 1        | 0.24%   |
| 5.15.11 | 1        | 0.24%   |
| 5.15.0  | 1        | 0.24%   |
| 5.14.15 | 1        | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 403      | 95.72%  |
| 5.15    | 7        | 1.66%   |
| 5.14    | 5        | 1.19%   |
| 5.11    | 3        | 0.71%   |
| 5.16    | 2        | 0.48%   |
| 5.8     | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 417      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 383      | 91.19%  |
| Unknown         | 20       | 4.76%   |
| X-Cinnamon      | 7        | 1.67%   |
| i3              | 3        | 0.71%   |
| GNOME Flashback | 3        | 0.71%   |
| Unity           | 2        | 0.48%   |
| sway            | 1        | 0.24%   |
| Cinnamon        | 1        | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 230      | 54.63%  |
| X11     | 177      | 42.04%  |
| Tty     | 8        | 1.9%    |
| Unknown | 6        | 1.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 283      | 67.7%   |
| GDM     | 91       | 21.77%  |
| Unknown | 35       | 8.37%   |
| LightDM | 8        | 1.91%   |
| SDDM    | 1        | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 150      | 35.63%  |
| de_DE | 78       | 18.53%  |
| fr_FR | 20       | 4.75%   |
| it_IT | 18       | 4.28%   |
| en_GB | 16       | 3.8%    |
| en_AU | 14       | 3.33%   |
| pt_BR | 13       | 3.09%   |
| en_CA | 12       | 2.85%   |
| pl_PL | 11       | 2.61%   |
| ru_RU | 8        | 1.9%    |
| es_ES | 6        | 1.43%   |
| en_IN | 6        | 1.43%   |
| C     | 6        | 1.43%   |
| nl_NL | 5        | 1.19%   |
| hu_HU | 5        | 1.19%   |
| zh_CN | 4        | 0.95%   |
| ja_JP | 4        | 0.95%   |
| sv_SE | 3        | 0.71%   |
| es_MX | 3        | 0.71%   |
| es_AR | 3        | 0.71%   |
| el_GR | 3        | 0.71%   |
| de_CH | 3        | 0.71%   |
| ru_UA | 2        | 0.48%   |
| nb_NO | 2        | 0.48%   |
| fr_BE | 2        | 0.48%   |
| fi_FI | 2        | 0.48%   |
| et_EE | 2        | 0.48%   |
| es_PE | 2        | 0.48%   |
| de_AT | 2        | 0.48%   |
| da_DK | 2        | 0.48%   |
| ar_EG | 2        | 0.48%   |
| tr_TR | 1        | 0.24%   |
| sk_SK | 1        | 0.24%   |
| pt_PT | 1        | 0.24%   |
| ko_KR | 1        | 0.24%   |
| hr_HR | 1        | 0.24%   |
| es_CO | 1        | 0.24%   |
| es_BO | 1        | 0.24%   |
| en_ZW | 1        | 0.24%   |
| en_PH | 1        | 0.24%   |
| en_NG | 1        | 0.24%   |
| en_HK | 1        | 0.24%   |
| cs_CZ | 1        | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 321      | 76.98%  |
| EFI  | 96       | 23.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 372      | 89.21%  |
| Overlay | 20       | 4.8%    |
| Zfs     | 12       | 2.88%   |
| Btrfs   | 8        | 1.92%   |
| Xfs     | 3        | 0.72%   |
| Ext3    | 1        | 0.24%   |
| Ext2    | 1        | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 323      | 77.46%  |
| GPT     | 85       | 20.38%  |
| MBR     | 9        | 2.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 335      | 79.57%  |
| Yes       | 86       | 20.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 234      | 55.85%  |
| Yes       | 185      | 44.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 98       | 23.5%   |
| MSI                 | 72       | 17.27%  |
| Gigabyte Technology | 68       | 16.31%  |
| Dell                | 38       | 9.11%   |
| ASRock              | 36       | 8.63%   |
| Hewlett-Packard     | 33       | 7.91%   |
| Lenovo              | 15       | 3.6%    |
| Acer                | 9        | 2.16%   |
| Fujitsu             | 6        | 1.44%   |
| Medion              | 5        | 1.2%    |
| Pegatron            | 4        | 0.96%   |
| Intel               | 3        | 0.72%   |
| Huanan              | 3        | 0.72%   |
| Foxconn             | 3        | 0.72%   |
| EVGA                | 3        | 0.72%   |
| Biostar             | 2        | 0.48%   |
| Apple               | 2        | 0.48%   |
| Unknown             | 2        | 0.48%   |
| TYAN Computer       | 1        | 0.24%   |
| Supermicro          | 1        | 0.24%   |
| Positivo            | 1        | 0.24%   |
| PCWare              | 1        | 0.24%   |
| Packard Bell        | 1        | 0.24%   |
| OEM                 | 1        | 0.24%   |
| MACHINIST           | 1        | 0.24%   |
| JGINYUE             | 1        | 0.24%   |
| ICP / iEi           | 1        | 0.24%   |
| Google              | 1        | 0.24%   |
| EPSON DIRECT        | 1        | 0.24%   |
| ECS                 | 1        | 0.24%   |
| Chuwi               | 1        | 0.24%   |
| BESSTAR Tech        | 1        | 0.24%   |
| AMI                 | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 9        | 2.16%   |
| Dell OptiPlex 7010                | 5        | 1.2%    |
| MSI MS-7D25                       | 4        | 0.96%   |
| ASUS PRIME B450M-A                | 4        | 0.96%   |
| MSI MS-7C37                       | 3        | 0.72%   |
| MSI MS-7C35                       | 3        | 0.72%   |
| HP Z800 Workstation               | 3        | 0.72%   |
| Gigabyte X570 AORUS MASTER        | 3        | 0.72%   |
| Dell OptiPlex 9010                | 3        | 0.72%   |
| ASUS TUF GAMING X570-PLUS         | 3        | 0.72%   |
| MSI MS-7C94                       | 2        | 0.48%   |
| MSI MS-7C80                       | 2        | 0.48%   |
| MSI MS-7C52                       | 2        | 0.48%   |
| MSI MS-7C02                       | 2        | 0.48%   |
| MSI MS-7B84                       | 2        | 0.48%   |
| MSI MS-7B09                       | 2        | 0.48%   |
| MSI MS-7A38                       | 2        | 0.48%   |
| MSI MS-7821                       | 2        | 0.48%   |
| MSI MS-7817                       | 2        | 0.48%   |
| HP EliteDesk 800 G2 SFF           | 2        | 0.48%   |
| HP EliteDesk 800 G1 SFF           | 2        | 0.48%   |
| HP Compaq 8200 Elite CMT PC       | 2        | 0.48%   |
| Gigabyte X58A-UD3R                | 2        | 0.48%   |
| Gigabyte GA-78LMT-USB3            | 2        | 0.48%   |
| Dell OptiPlex 790                 | 2        | 0.48%   |
| Dell OptiPlex 780                 | 2        | 0.48%   |
| Dell OptiPlex 3020                | 2        | 0.48%   |
| Dell OptiPlex 3010                | 2        | 0.48%   |
| Dell Inspiron 545                 | 2        | 0.48%   |
| ASUS TUF GAMING Z690-PLUS WIFI D4 | 2        | 0.48%   |
| ASUS PRIME Z690-P WIFI D4         | 2        | 0.48%   |
| ASUS PRIME B350M-A                | 2        | 0.48%   |
| ASUS PRIME A320M-K                | 2        | 0.48%   |
| ASUS M5A78L-M/USB3                | 2        | 0.48%   |
| ASUS M4A89GTD-PRO/USB3            | 2        | 0.48%   |
| ASUS H110M-C                      | 2        | 0.48%   |
| ASUS CROSSHAIR VI HERO            | 2        | 0.48%   |
| ASUS B250 MINING EXPERT           | 2        | 0.48%   |
| ASRock Z590M-ITX/ax               | 2        | 0.48%   |
| ASRock Z370 Pro4                  | 2        | 0.48%   |
| Apple MacPro3,1                   | 2        | 0.48%   |
| Unknown                           | 2        | 0.48%   |
| TYAN Tempest-i5000VS-S5372-LC/LH  | 1        | 0.24%   |
| Supermicro X7DVL                  | 1        | 0.24%   |
| Positivo POS-MIH61CF              | 1        | 0.24%   |
| Pegatron WH637AA-UUW CQ5307SC     | 1        | 0.24%   |
| Pegatron VC903AA-ABF p6145fr      | 1        | 0.24%   |
| Pegatron p6730de                  | 1        | 0.24%   |
| Pegatron HPE-590t                 | 1        | 0.24%   |
| PCWare IPMH61R1                   | 1        | 0.24%   |
| Packard Bell IXTREME M5722        | 1        | 0.24%   |
| OEM TOP77D                        | 1        | 0.24%   |
| MSI X5836                         | 1        | 0.24%   |
| MSI Silent Gamer GTX 650 R1       | 1        | 0.24%   |
| MSI Pro 3000/3080                 | 1        | 0.24%   |
| MSI PPPPP-CCC#MMMMMMMM            | 1        | 0.24%   |
| MSI MS-7D20                       | 1        | 0.24%   |
| MSI MS-7D16                       | 1        | 0.24%   |
| MSI MS-7D13                       | 1        | 0.24%   |
| MSI MS-7D06                       | 1        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 24       | 5.76%   |
| ASUS PRIME                    | 21       | 5.04%   |
| ASUS ROG                      | 11       | 2.64%   |
| Lenovo ThinkCentre            | 10       | 2.4%    |
| HP Compaq                     | 10       | 2.4%    |
| ASUS All                      | 9        | 2.16%   |
| Gigabyte X570                 | 8        | 1.92%   |
| HP EliteDesk                  | 7        | 1.68%   |
| ASUS TUF                      | 6        | 1.44%   |
| Dell Inspiron                 | 5        | 1.2%    |
| Acer Aspire                   | 5        | 1.2%    |
| MSI MS-7D25                   | 4        | 0.96%   |
| Dell Precision                | 4        | 0.96%   |
| MSI MS-7C37                   | 3        | 0.72%   |
| MSI MS-7C35                   | 3        | 0.72%   |
| HP Z800                       | 3        | 0.72%   |
| HP ProDesk                    | 3        | 0.72%   |
| Gigabyte GA-78LMT-USB3        | 3        | 0.72%   |
| Fujitsu ESPRIMO               | 3        | 0.72%   |
| Dell XPS                      | 3        | 0.72%   |
| ASUS M5A78L-M                 | 3        | 0.72%   |
| MSI MS-7C94                   | 2        | 0.48%   |
| MSI MS-7C80                   | 2        | 0.48%   |
| MSI MS-7C52                   | 2        | 0.48%   |
| MSI MS-7C02                   | 2        | 0.48%   |
| MSI MS-7B84                   | 2        | 0.48%   |
| MSI MS-7B09                   | 2        | 0.48%   |
| MSI MS-7A38                   | 2        | 0.48%   |
| MSI MS-7821                   | 2        | 0.48%   |
| MSI MS-7817                   | 2        | 0.48%   |
| HP Pavilion                   | 2        | 0.48%   |
| Gigabyte Z370                 | 2        | 0.48%   |
| Gigabyte X58A-UD3R            | 2        | 0.48%   |
| Gigabyte X470                 | 2        | 0.48%   |
| Gigabyte B550M                | 2        | 0.48%   |
| Gigabyte B550                 | 2        | 0.48%   |
| Gigabyte B450M                | 2        | 0.48%   |
| ASUS STRIX                    | 2        | 0.48%   |
| ASUS P8H61                    | 2        | 0.48%   |
| ASUS M5A97                    | 2        | 0.48%   |
| ASUS M4A89GTD-PRO             | 2        | 0.48%   |
| ASUS H110M-C                  | 2        | 0.48%   |
| ASUS CROSSHAIR                | 2        | 0.48%   |
| ASUS B250                     | 2        | 0.48%   |
| ASRock Z590M-ITX              | 2        | 0.48%   |
| ASRock Z370                   | 2        | 0.48%   |
| ASRock 990FX                  | 2        | 0.48%   |
| Apple MacPro3                 | 2        | 0.48%   |
| Acer Predator                 | 2        | 0.48%   |
| Unknown                       | 2        | 0.48%   |
| TYAN Tempest-i5000VS-S5372-LC | 1        | 0.24%   |
| Supermicro X7DVL              | 1        | 0.24%   |
| Positivo POS-MIH61CF          | 1        | 0.24%   |
| Pegatron WH637AA-UUW          | 1        | 0.24%   |
| Pegatron VC903AA-ABF          | 1        | 0.24%   |
| Pegatron p6730de              | 1        | 0.24%   |
| Pegatron HPE-590t             | 1        | 0.24%   |
| PCWare IPMH61R1               | 1        | 0.24%   |
| Packard Bell IXTREME          | 1        | 0.24%   |
| OEM TOP77D                    | 1        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 42       | 10.07%  |
| 2021 | 41       | 9.83%   |
| 2019 | 41       | 9.83%   |
| 2012 | 35       | 8.39%   |
| 2020 | 33       | 7.91%   |
| 2013 | 30       | 7.19%   |
| 2011 | 29       | 6.95%   |
| 2017 | 28       | 6.71%   |
| 2010 | 26       | 6.24%   |
| 2014 | 24       | 5.76%   |
| 2009 | 23       | 5.52%   |
| 2008 | 20       | 4.8%    |
| 2015 | 19       | 4.56%   |
| 2016 | 11       | 2.64%   |
| 2007 | 9        | 2.16%   |
| 2006 | 6        | 1.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 417      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 409      | 98.08%  |
| Enabled  | 8        | 1.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 415      | 99.52%  |
| Yes  | 2        | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 100      | 23.87%  |
| 32.01-64.0  | 80       | 19.09%  |
| 8.01-16.0   | 78       | 18.62%  |
| 4.01-8.0    | 69       | 16.47%  |
| 3.01-4.0    | 50       | 11.93%  |
| 64.01-256.0 | 26       | 6.21%   |
| 24.01-32.0  | 9        | 2.15%   |
| 1.01-2.0    | 6        | 1.43%   |
| 2.01-3.0    | 1        | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 177      | 41.07%  |
| 2.01-3.0   | 118      | 27.38%  |
| 4.01-8.0   | 64       | 14.85%  |
| 3.01-4.0   | 53       | 12.3%   |
| 8.01-16.0  | 12       | 2.78%   |
| 0.51-1.0   | 4        | 0.93%   |
| 16.01-24.0 | 2        | 0.46%   |
| 32.01-64.0 | 1        | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 158      | 37.62%  |
| 2      | 118      | 28.1%   |
| 3      | 57       | 13.57%  |
| 4      | 38       | 9.05%   |
| 5      | 30       | 7.14%   |
| 6      | 8        | 1.9%    |
| 7      | 6        | 1.43%   |
| 11     | 2        | 0.48%   |
| 9      | 1        | 0.24%   |
| 8      | 1        | 0.24%   |
| 0      | 1        | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 216      | 51.67%  |
| Yes       | 202      | 48.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 413      | 99.04%  |
| No        | 4        | 0.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 217      | 51.91%  |
| Yes       | 201      | 48.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 270      | 64.59%  |
| Yes       | 148      | 35.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| Germany                | 86       | 20.62%  |
| USA                    | 85       | 20.38%  |
| Italy                  | 22       | 5.28%   |
| France                 | 22       | 5.28%   |
| Brazil                 | 17       | 4.08%   |
| UK                     | 16       | 3.84%   |
| Poland                 | 14       | 3.36%   |
| Canada                 | 14       | 3.36%   |
| Australia              | 14       | 3.36%   |
| Russia                 | 9        | 2.16%   |
| Ukraine                | 6        | 1.44%   |
| Switzerland            | 6        | 1.44%   |
| Netherlands            | 6        | 1.44%   |
| Mexico                 | 6        | 1.44%   |
| India                  | 6        | 1.44%   |
| Hungary                | 6        | 1.44%   |
| Sweden                 | 5        | 1.2%    |
| Greece                 | 5        | 1.2%    |
| China                  | 5        | 1.2%    |
| Spain                  | 4        | 0.96%   |
| Japan                  | 4        | 0.96%   |
| Belgium                | 4        | 0.96%   |
| Norway                 | 3        | 0.72%   |
| Lithuania              | 3        | 0.72%   |
| Finland                | 3        | 0.72%   |
| Denmark                | 3        | 0.72%   |
| Argentina              | 3        | 0.72%   |
| Turkey                 | 2        | 0.48%   |
| South Korea            | 2        | 0.48%   |
| South Africa           | 2        | 0.48%   |
| Peru                   | 2        | 0.48%   |
| Iran                   | 2        | 0.48%   |
| Estonia                | 2        | 0.48%   |
| Austria                | 2        | 0.48%   |
| Uruguay                | 1        | 0.24%   |
| Thailand               | 1        | 0.24%   |
| Sri Lanka              | 1        | 0.24%   |
| Slovenia               | 1        | 0.24%   |
| Serbia                 | 1        | 0.24%   |
| Saudi Arabia           | 1        | 0.24%   |
| Portugal               | 1        | 0.24%   |
| Philippines            | 1        | 0.24%   |
| Nigeria                | 1        | 0.24%   |
| New Zealand            | 1        | 0.24%   |
| Malaysia               | 1        | 0.24%   |
| Kazakhstan             | 1        | 0.24%   |
| Israel                 | 1        | 0.24%   |
| Iceland                | 1        | 0.24%   |
| Hong Kong              | 1        | 0.24%   |
| Honduras               | 1        | 0.24%   |
| Georgia                | 1        | 0.24%   |
| Egypt                  | 1        | 0.24%   |
| Czechia                | 1        | 0.24%   |
| Croatia                | 1        | 0.24%   |
| Colombia               | 1        | 0.24%   |
| Chile                  | 1        | 0.24%   |
| Bulgaria               | 1        | 0.24%   |
| Bosnia and Herzegovina | 1        | 0.24%   |
| Bolivia                | 1        | 0.24%   |
| Angola                 | 1        | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Cleveland         | 10       | 2.37%   |
| Berlin            | 7        | 1.66%   |
| Sydney            | 4        | 0.95%   |
| Milan             | 4        | 0.95%   |
| Dresden           | 4        | 0.95%   |
| Wuhan             | 3        | 0.71%   |
| Warsaw            | 3        | 0.71%   |
| S??o Paulo        | 3        | 0.71%   |
| Munich            | 3        | 0.71%   |
| Madrid            | 3        | 0.71%   |
| Brisbane          | 3        | 0.71%   |
| Wroclaw           | 2        | 0.47%   |
| Wittlich          | 2        | 0.47%   |
| Washington        | 2        | 0.47%   |
| Vladivostok       | 2        | 0.47%   |
| Vilnius           | 2        | 0.47%   |
| Tijuana           | 2        | 0.47%   |
| Thessaloniki      | 2        | 0.47%   |
| Tehran            | 2        | 0.47%   |
| Stuttgart         | 2        | 0.47%   |
| San Pedro         | 2        | 0.47%   |
| Poznan            | 2        | 0.47%   |
| Perth             | 2        | 0.47%   |
| Paris             | 2        | 0.47%   |
| Oslo              | 2        | 0.47%   |
| Oakland           | 2        | 0.47%   |
| Lima              | 2        | 0.47%   |
| Landsberg am Lech | 2        | 0.47%   |
| Kyiv              | 2        | 0.47%   |
| Houston           | 2        | 0.47%   |
| Helsinki          | 2        | 0.47%   |
| Essen             | 2        | 0.47%   |
| El Paso           | 2        | 0.47%   |
| Dubuque           | 2        | 0.47%   |
| Cannes            | 2        | 0.47%   |
| Brussels          | 2        | 0.47%   |
| Bodenheim         | 2        | 0.47%   |
| Birmingham        | 2        | 0.47%   |
| Belo Horizonte    | 2        | 0.47%   |
| Athens            | 2        | 0.47%   |
| Amsterdam         | 2        | 0.47%   |
| Zevenaar          | 1        | 0.24%   |
| Zaventem          | 1        | 0.24%   |
| Zagreb            | 1        | 0.24%   |
| Yakima            | 1        | 0.24%   |
| Xanthi            | 1        | 0.24%   |
| Wynau             | 1        | 0.24%   |
| Wuppertal         | 1        | 0.24%   |
| Woodstock         | 1        | 0.24%   |
| Wo?�omin          | 1        | 0.24%   |
| Wittenberg        | 1        | 0.24%   |
| Winsen            | 1        | 0.24%   |
| Winnipeg          | 1        | 0.24%   |
| Wildeshausen      | 1        | 0.24%   |
| Wiesbaden         | 1        | 0.24%   |
| West Malling      | 1        | 0.24%   |
| Weisendorf        | 1        | 0.24%   |
| Waterloo          | 1        | 0.24%   |
| Walthamstow       | 1        | 0.24%   |
| Waldsassen        | 1        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 146      | 213    | 19.19%  |
| Seagate                     | 137      | 209    | 18%     |
| Samsung Electronics         | 129      | 205    | 16.95%  |
| Kingston                    | 48       | 60     | 6.31%   |
| Sandisk                     | 37       | 48     | 4.86%   |
| Crucial                     | 36       | 41     | 4.73%   |
| Toshiba                     | 35       | 46     | 4.6%    |
| Hitachi                     | 31       | 44     | 4.07%   |
| A-DATA Technology           | 13       | 14     | 1.71%   |
| Phison                      | 11       | 14     | 1.45%   |
| Silicon Motion              | 10       | 14     | 1.31%   |
| HGST                        | 9        | 13     | 1.18%   |
| Intel                       | 8        | 9      | 1.05%   |
| Unknown                     | 7        | 10     | 0.92%   |
| PNY                         | 7        | 9      | 0.92%   |
| Micron/Crucial Technology   | 6        | 6      | 0.79%   |
| MAXTOR                      | 6        | 6      | 0.79%   |
| Phison Electronics          | 5        | 6      | 0.66%   |
| Intenso                     | 5        | 5      | 0.66%   |
| SK Hynix                    | 3        | 8      | 0.39%   |
| Realtek Semiconductor       | 3        | 3      | 0.39%   |
| OCZ                         | 3        | 3      | 0.39%   |
| LITEON                      | 3        | 3      | 0.39%   |
| Corsair                     | 3        | 3      | 0.39%   |
| China                       | 3        | 3      | 0.39%   |
| Unknown                     | 3        | 3      | 0.39%   |
| Transcend                   | 2        | 2      | 0.26%   |
| SPCC                        | 2        | 2      | 0.26%   |
| SABRENT                     | 2        | 2      | 0.26%   |
| PLEXTOR                     | 2        | 3      | 0.26%   |
| Patriot                     | 2        | 2      | 0.26%   |
| Netac                       | 2        | 3      | 0.26%   |
| LITEONIT                    | 2        | 2      | 0.26%   |
| LDLC                        | 2        | 2      | 0.26%   |
| KIOXIA-EXCERIA              | 2        | 2      | 0.26%   |
| JMicron                     | 2        | 2      | 0.26%   |
| Hewlett-Packard             | 2        | 2      | 0.26%   |
| GOODRAM                     | 2        | 3      | 0.26%   |
| Gigabyte Technology         | 2        | 2      | 0.26%   |
| XPG                         | 1        | 1      | 0.13%   |
| TO Exter                    | 1        | 1      | 0.13%   |
| Team                        | 1        | 1      | 0.13%   |
| SUPERSONIC                  | 1        | 1      | 0.13%   |
| SSSTC                       | 1        | 1      | 0.13%   |
| Q200                        | 1        | 4      | 0.13%   |
| PHD 3.0                     | 1        | 1      | 0.13%   |
| OYUNKEY                     | 1        | 1      | 0.13%   |
| OWC                         | 1        | 1      | 0.13%   |
| NTC                         | 1        | 1      | 0.13%   |
| Maxone                      | 1        | 1      | 0.13%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.13%   |
| MARVELL                     | 1        | 1      | 0.13%   |
| Lexar                       | 1        | 1      | 0.13%   |
| KLEVV                       | 1        | 3      | 0.13%   |
| KIOXIA                      | 1        | 1      | 0.13%   |
| KingDian                    | 1        | 1      | 0.13%   |
| kimtigo                     | 1        | 1      | 0.13%   |
| INTEL SS                    | 1        | 1      | 0.13%   |
| Green House                 | 1        | 1      | 0.13%   |
| Gigastone                   | 1        | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD     | 13       | 1.44%   |
| Seagate ST500DM002-1BD142 500GB     | 12       | 1.33%   |
| Samsung SSD 850 EVO 250GB           | 12       | 1.33%   |
| Seagate ST2000DM008-2FR102 2TB      | 11       | 1.22%   |
| Samsung NVMe SSD Drive 250GB        | 11       | 1.22%   |
| Samsung SSD 860 EVO 1TB             | 10       | 1.1%    |
| Samsung SSD 860 EVO 500GB           | 9        | 0.99%   |
| Samsung SSD 850 EVO 500GB           | 9        | 0.99%   |
| Samsung NVMe SSD Drive 1TB          | 9        | 0.99%   |
| Samsung SSD 970 EVO 500GB           | 8        | 0.88%   |
| Seagate ST1000DM003-1CH162 1TB      | 7        | 0.77%   |
| Sandisk NVMe SSD Drive 1TB          | 7        | 0.77%   |
| Samsung NVMe SSD Drive 500GB        | 7        | 0.77%   |
| Kingston SA400S37120G 120GB SSD     | 7        | 0.77%   |
| Toshiba DT01ACA100 1TB              | 6        | 0.66%   |
| Sandisk NVMe SSD Drive 500GB        | 6        | 0.66%   |
| Kingston SV300S37A120G 120GB SSD    | 6        | 0.66%   |
| Kingston SA400S37480G 480GB SSD     | 6        | 0.66%   |
| Crucial CT500MX500SSD1 500GB        | 6        | 0.66%   |
| Seagate ST4000DM004-2CV104 4TB      | 5        | 0.55%   |
| Seagate ST3250318AS 250GB           | 5        | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB      | 5        | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB      | 5        | 0.55%   |
| SanDisk SSD PLUS 240GB              | 5        | 0.55%   |
| Phison PCIe SSD 1TB                 | 5        | 0.55%   |
| Hitachi HUS724030ALE641 3TB         | 5        | 0.55%   |
| WDC WD40EZRZ-00GXCB0 4TB            | 4        | 0.44%   |
| WDC WD20EZRX-00D8PB0 2TB            | 4        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB            | 4        | 0.44%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4        | 0.44%   |
| Silicon Motion NVMe SSD Drive 256GB | 4        | 0.44%   |
| Seagate ST2000DL003-9VT166 2TB      | 4        | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 0.44%   |
| SanDisk Ultra II 480GB SSD          | 4        | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB        | 4        | 0.44%   |
| Samsung HD501LJ 500GB               | 4        | 0.44%   |
| Phison NVMe SSD Drive 256GB         | 4        | 0.44%   |
| Kingston SV300S37A240G 240GB SSD    | 4        | 0.44%   |
| Kingston NVMe SSD Drive 500GB       | 4        | 0.44%   |
| Crucial CT240BX500SSD1 240GB        | 4        | 0.44%   |
| WDC WDBNCE0010PNC 1TB SSD           | 3        | 0.33%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 3        | 0.33%   |
| WDC WD20EZRX-00DC0B0 2TB            | 3        | 0.33%   |
| WDC WD20EARX-00PASB0 2TB            | 3        | 0.33%   |
| WDC WD2002FAEX-007BA0 2TB           | 3        | 0.33%   |
| WDC WD10EZEX-08M2NA0 1TB            | 3        | 0.33%   |
| Unknown SD/MMC/MS PRO 128GB         | 3        | 0.33%   |
| Toshiba HDWD130 3TB                 | 3        | 0.33%   |
| Toshiba DT01ACA200 2TB              | 3        | 0.33%   |
| Toshiba DT01ACA050 500GB            | 3        | 0.33%   |
| Silicon Motion NVMe SSD Drive 512GB | 3        | 0.33%   |
| Seagate ST3160812AS 160GB           | 3        | 0.33%   |
| Seagate ST31000524AS 1TB            | 3        | 0.33%   |
| Seagate ST1000DM003-1SB10C 1TB      | 3        | 0.33%   |
| Seagate Expansion 1TB               | 3        | 0.33%   |
| SanDisk SSD PLUS 1000GB             | 3        | 0.33%   |
| Samsung SSD 980 PRO 1TB             | 3        | 0.33%   |
| Samsung SSD 870 QVO 1TB             | 3        | 0.33%   |
| Samsung SSD 870 EVO 250GB           | 3        | 0.33%   |
| Samsung SSD 870 EVO 1TB             | 3        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 136      | 206    | 35.98%  |
| WDC                 | 131      | 192    | 34.66%  |
| Hitachi             | 31       | 44     | 8.2%    |
| Toshiba             | 30       | 40     | 7.94%   |
| Samsung Electronics | 25       | 31     | 6.61%   |
| HGST                | 9        | 13     | 2.38%   |
| MAXTOR              | 6        | 6      | 1.59%   |
| Unknown             | 3        | 3      | 0.79%   |
| TO Exter            | 1        | 1      | 0.26%   |
| PHD 3.0             | 1        | 1      | 0.26%   |
| Maxone              | 1        | 1      | 0.26%   |
| MARVELL             | 1        | 1      | 0.26%   |
| Intenso             | 1        | 1      | 0.26%   |
| Hewlett-Packard     | 1        | 1      | 0.26%   |
| Unknown             | 1        | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 67       | 97     | 26.27%  |
| Kingston            | 40       | 52     | 15.69%  |
| Crucial             | 30       | 34     | 11.76%  |
| SanDisk             | 24       | 31     | 9.41%   |
| WDC                 | 18       | 19     | 7.06%   |
| A-DATA Technology   | 9        | 10     | 3.53%   |
| PNY                 | 6        | 7      | 2.35%   |
| Intel               | 6        | 7      | 2.35%   |
| Toshiba             | 5        | 5      | 1.96%   |
| OCZ                 | 3        | 3      | 1.18%   |
| LITEON              | 3        | 3      | 1.18%   |
| Intenso             | 3        | 3      | 1.18%   |
| China               | 3        | 3      | 1.18%   |
| Transcend           | 2        | 2      | 0.78%   |
| SABRENT             | 2        | 2      | 0.78%   |
| PLEXTOR             | 2        | 3      | 0.78%   |
| Patriot             | 2        | 2      | 0.78%   |
| Netac               | 2        | 3      | 0.78%   |
| LITEONIT            | 2        | 2      | 0.78%   |
| LDLC                | 2        | 2      | 0.78%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.78%   |
| Team                | 1        | 1      | 0.39%   |
| SPCC                | 1        | 1      | 0.39%   |
| SK Hynix            | 1        | 2      | 0.39%   |
| Seagate             | 1        | 1      | 0.39%   |
| Q200                | 1        | 4      | 0.39%   |
| OYUNKEY             | 1        | 1      | 0.39%   |
| Lexar               | 1        | 1      | 0.39%   |
| KLEVV               | 1        | 3      | 0.39%   |
| KingDian            | 1        | 1      | 0.39%   |
| kimtigo             | 1        | 1      | 0.39%   |
| INTEL SS            | 1        | 1      | 0.39%   |
| Hewlett-Packard     | 1        | 1      | 0.39%   |
| Green House         | 1        | 1      | 0.39%   |
| GOODRAM             | 1        | 1      | 0.39%   |
| Gigabyte Technology | 1        | 1      | 0.39%   |
| FORESEE             | 1        | 1      | 0.39%   |
| Corsair             | 1        | 1      | 0.39%   |
| BAITITON            | 1        | 1      | 0.39%   |
| ASMT                | 1        | 1      | 0.39%   |
| Apacer              | 1        | 1      | 0.39%   |
| 2-Power             | 1        | 2      | 0.39%   |
| Unknown             | 1        | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 287      | 542    | 45.2%   |
| SSD     | 203      | 321    | 31.97%  |
| NVMe    | 131      | 181    | 20.63%  |
| Unknown | 12       | 15     | 1.89%   |
| MMC     | 2        | 2      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 372      | 840    | 69.53%  |
| NVMe | 131      | 180    | 24.49%  |
| SAS  | 30       | 39     | 5.61%   |
| MMC  | 2        | 2      | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 269      | 451    | 48.91%  |
| 0.51-1.0   | 153      | 216    | 27.82%  |
| 1.01-2.0   | 67       | 90     | 12.18%  |
| 3.01-4.0   | 25       | 43     | 4.55%   |
| 2.01-3.0   | 20       | 34     | 3.64%   |
| 4.01-10.0  | 12       | 25     | 2.18%   |
| 10.01-20.0 | 3        | 3      | 0.55%   |
| 0          | 1        | 1      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 115      | 27.45%  |
| 501-1000       | 72       | 17.18%  |
| 251-500        | 68       | 16.23%  |
| 1001-2000      | 47       | 11.22%  |
| More than 3000 | 36       | 8.59%   |
| 1-20           | 28       | 6.68%   |
| 2001-3000      | 25       | 5.97%   |
| 51-100         | 19       | 4.53%   |
| 21-50          | 8        | 1.91%   |
| Unknown        | 1        | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 153      | 35.92%  |
| 21-50          | 65       | 15.26%  |
| 101-250        | 54       | 12.68%  |
| 51-100         | 52       | 12.21%  |
| 501-1000       | 32       | 7.51%   |
| 251-500        | 26       | 6.1%    |
| 1001-2000      | 21       | 4.93%   |
| More than 3000 | 15       | 3.52%   |
| 2001-3000      | 7        | 1.64%   |
| Unknown        | 1        | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| Seagate ST1000DM003-1CH162 1TB             | 2        | 2      | 8.33%   |
| WDC WD5000BPVT-00HXZT3 500GB               | 1        | 1      | 4.17%   |
| WDC WD5000AAKX-083CA1 500GB                | 1        | 1      | 4.17%   |
| WDC WD30EZRX-00DC0B0 3TB                   | 1        | 1      | 4.17%   |
| WDC WD2500HHTZ-04N21V0 250GB               | 1        | 1      | 4.17%   |
| WDC WD20EARX-00PASB0 2TB                   | 1        | 1      | 4.17%   |
| WDC WD1600AAJS-00L7A0 160GB                | 1        | 1      | 4.17%   |
| WDC WD10EZEX-00BN5A0 1TB                   | 1        | 1      | 4.17%   |
| WDC WD10EARS-00Y5B1 1TB                    | 1        | 1      | 4.17%   |
| WDC WD1002FAEX-00Z3A0 1TB                  | 1        | 1      | 4.17%   |
| Toshiba MQ01ABD100 1TB                     | 1        | 2      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1      | 4.17%   |
| Seagate ST3500320AS 500GB                  | 1        | 1      | 4.17%   |
| Seagate ST31000528AS 1TB                   | 1        | 1      | 4.17%   |
| Seagate ST3000DM001-1CH166 3TB             | 1        | 2      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 1        | 1      | 4.17%   |
| Seagate ST1000DM003-9YN162 1TB             | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 870 EVO 500GB      | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 870 EVO 1TB        | 1        | 1      | 4.17%   |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1        | 1      | 4.17%   |
| MAXTOR 6G160E0 160GB                       | 1        | 1      | 4.17%   |
| Kingston SV300S37A120G 120GB SSD           | 1        | 1      | 4.17%   |
| Hitachi HDS721680PLA380 80GB               | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 9      | 39.13%  |
| Seagate             | 8        | 9      | 34.78%  |
| Samsung Electronics | 2        | 3      | 8.7%    |
| Toshiba             | 1        | 2      | 4.35%   |
| MAXTOR              | 1        | 1      | 4.35%   |
| Kingston            | 1        | 1      | 4.35%   |
| Hitachi             | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 9        | 9      | 45%     |
| Seagate | 8        | 9      | 40%     |
| Toshiba | 1        | 2      | 5%      |
| MAXTOR  | 1        | 1      | 5%      |
| Hitachi | 1        | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 22     | 85.71%  |
| SSD  | 2        | 3      | 9.52%   |
| NVMe | 1        | 1      | 4.76%   |

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
| Detected | 318      | 778    | 72.44%  |
| Works    | 100      | 257    | 22.78%  |
| Malfunc  | 21       | 26     | 4.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 273      | 43.82%  |
| AMD                          | 131      | 21.03%  |
| Samsung Electronics          | 58       | 9.31%   |
| JMicron Technology           | 21       | 3.37%   |
| Phison Electronics           | 20       | 3.21%   |
| Marvell Technology Group     | 17       | 2.73%   |
| ASMedia Technology           | 16       | 2.57%   |
| Sandisk                      | 15       | 2.41%   |
| Silicon Motion               | 12       | 1.93%   |
| Micron/Crucial Technology    | 11       | 1.77%   |
| Nvidia                       | 9        | 1.44%   |
| Kingston Technology Company  | 8        | 1.28%   |
| Realtek Semiconductor        | 5        | 0.8%    |
| LSI Logic / Symbios Logic    | 5        | 0.8%    |
| SK Hynix                     | 3        | 0.48%   |
| ADATA Technology             | 3        | 0.48%   |
| Silicon Image                | 2        | 0.32%   |
| Broadcom / LSI               | 2        | 0.32%   |
| VIA Technologies             | 1        | 0.16%   |
| Toshiba America Info Systems | 1        | 0.16%   |
| Shenzhen Longsys Electronics | 1        | 0.16%   |
| Seagate Technology           | 1        | 0.16%   |
| Micron Technology            | 1        | 0.16%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.16%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.16%   |
| KIOXIA                       | 1        | 0.16%   |
| Hewlett-Packard              | 1        | 0.16%   |
| Advanced System Products     | 1        | 0.16%   |
| Adaptec                      | 1        | 0.16%   |
| 3ware                        | 1        | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 75       | 9.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 38       | 4.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 33       | 4.28%   |
| Intel SATA Controller [RAID mode]                                                       | 24       | 3.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 24       | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23       | 2.98%   |
| AMD 400 Series Chipset SATA Controller                                                  | 22       | 2.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 2.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 19       | 2.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18       | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17       | 2.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17       | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16       | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14       | 1.82%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14       | 1.82%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 14       | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 12       | 1.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 12       | 1.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 11       | 1.43%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 11       | 1.43%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 11       | 1.43%   |
| Phison E12 NVMe Controller                                                              | 10       | 1.3%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 9        | 1.17%   |
| AMD FCH SATA Controller D                                                               | 9        | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 1.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 8        | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 7        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 0.91%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6        | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 6        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.78%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 6        | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 0.78%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 5        | 0.65%   |
| Kingston Company A2000 NVMe SSD                                                         | 5        | 0.65%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 0.65%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 5        | 0.65%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.65%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 0.52%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 0.52%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.52%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 4        | 0.52%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4        | 0.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.52%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.52%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 0.39%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 3        | 0.39%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 3        | 0.39%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 3        | 0.39%   |
| JMicron JMB361 AHCI/IDE                                                                 | 3        | 0.39%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 0.39%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 3        | 0.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 329      | 53.06%  |
| NVMe | 130      | 20.97%  |
| IDE  | 107      | 17.26%  |
| RAID | 43       | 6.94%   |
| SCSI | 8        | 1.29%   |
| SAS  | 3        | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 277      | 66.43%  |
| AMD    | 140      | 33.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-8700K CPU @ 3.70GHz           | 8        | 1.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8        | 1.92%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 8        | 1.92%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 1.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 7        | 1.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 7        | 1.68%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 6        | 1.44%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 1.44%   |
| AMD FX-6300 Six-Core Processor              | 6        | 1.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5        | 1.2%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 5        | 1.2%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 1.2%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 1.2%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.2%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 0.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 0.96%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 0.96%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 0.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.96%   |
| Intel 12th Gen Core i7-12700K               | 4        | 0.96%   |
| Intel 12th Gen Core i5-12600K               | 4        | 0.96%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 0.96%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 0.96%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 0.96%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 0.72%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 0.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 0.72%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 3        | 0.72%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.72%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.72%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 3        | 0.72%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.72%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 0.72%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 0.72%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 0.72%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.72%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 0.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.72%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 3        | 0.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 0.72%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 0.72%   |
| AMD FX-8320 Eight-Core Processor            | 3        | 0.72%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 2        | 0.48%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 2        | 0.48%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 0.48%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.48%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 2        | 0.48%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.48%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 2        | 0.48%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.48%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 0.48%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 0.48%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.48%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.48%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 2        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 73       | 17.51%  |
| Intel Core i5           | 68       | 16.31%  |
| AMD Ryzen 5             | 31       | 7.43%   |
| Intel Core i3           | 30       | 7.19%   |
| AMD Ryzen 7             | 27       | 6.47%   |
| Intel Xeon              | 22       | 5.28%   |
| Other                   | 17       | 4.08%   |
| AMD FX                  | 16       | 3.84%   |
| Intel Core 2 Duo        | 14       | 3.36%   |
| AMD Ryzen 9             | 13       | 3.12%   |
| Intel Core 2 Quad       | 11       | 2.64%   |
| Intel Celeron           | 9        | 2.16%   |
| Intel Pentium Dual-Core | 8        | 1.92%   |
| Intel Core i9           | 8        | 1.92%   |
| AMD Ryzen 3             | 7        | 1.68%   |
| AMD Ryzen Threadripper  | 5        | 1.2%    |
| AMD Athlon II X2        | 5        | 1.2%    |
| AMD A8                  | 5        | 1.2%    |
| Intel Pentium           | 4        | 0.96%   |
| AMD Phenom II X6        | 4        | 0.96%   |
| AMD Phenom II X4        | 4        | 0.96%   |
| AMD Athlon 64 X2        | 4        | 0.96%   |
| Intel Pentium Dual      | 3        | 0.72%   |
| AMD Athlon II X4        | 3        | 0.72%   |
| Intel Pentium Gold      | 2        | 0.48%   |
| Intel Pentium D         | 2        | 0.48%   |
| Intel Core 2            | 2        | 0.48%   |
| Intel Atom              | 2        | 0.48%   |
| AMD Ryzen 5 PRO         | 2        | 0.48%   |
| AMD A6                  | 2        | 0.48%   |
| AMD A10                 | 2        | 0.48%   |
| Intel Genuine           | 1        | 0.24%   |
| Intel Celeron D         | 1        | 0.24%   |
| AMD Sempron             | 1        | 0.24%   |
| AMD Ryzen 7 PRO         | 1        | 0.24%   |
| AMD PRO A10             | 1        | 0.24%   |
| AMD Phenom II X3        | 1        | 0.24%   |
| AMD Phenom II X2        | 1        | 0.24%   |
| AMD Phenom              | 1        | 0.24%   |
| AMD Athlon X4           | 1        | 0.24%   |
| AMD Athlon Dual Core    | 1        | 0.24%   |
| AMD Athlon              | 1        | 0.24%   |
| AMD A4                  | 1        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 150      | 35.97%  |
| 2      | 96       | 23.02%  |
| 6      | 65       | 15.59%  |
| 8      | 51       | 12.23%  |
| 12     | 21       | 5.04%   |
| 3      | 10       | 2.4%    |
| 16     | 9        | 2.16%   |
| 10     | 8        | 1.92%   |
| 1      | 4        | 0.96%   |
| 32     | 1        | 0.24%   |
| 28     | 1        | 0.24%   |
| 24     | 1        | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 405      | 97.12%  |
| 2      | 12       | 2.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 240      | 57.55%  |
| 1      | 177      | 42.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 417      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 290      | 68.4%   |
| 0x306c3    | 11       | 2.59%   |
| 0x906ea    | 9        | 2.12%   |
| 0x206a7    | 9        | 2.12%   |
| 0x90672    | 8        | 1.89%   |
| 0x306a9    | 7        | 1.65%   |
| 0x0a201009 | 6        | 1.42%   |
| 0x08701013 | 6        | 1.42%   |
| 0x906ed    | 5        | 1.18%   |
| 0x0a201016 | 5        | 1.18%   |
| 0x06000852 | 5        | 1.18%   |
| 0xa0671    | 4        | 0.94%   |
| 0xa0655    | 4        | 0.94%   |
| 0x906e9    | 4        | 0.94%   |
| 0x506e3    | 4        | 0.94%   |
| 0x0a50000c | 4        | 0.94%   |
| 0x1067a    | 3        | 0.71%   |
| 0x08701021 | 3        | 0.71%   |
| 0x0800820d | 3        | 0.71%   |
| 0x306f2    | 2        | 0.47%   |
| 0x206d7    | 2        | 0.47%   |
| 0x106a5    | 2        | 0.47%   |
| 0x08108109 | 2        | 0.47%   |
| 0x08001138 | 2        | 0.47%   |
| 0x010000dc | 2        | 0.47%   |
| 0x010000db | 2        | 0.47%   |
| 0xf65      | 1        | 0.24%   |
| 0xf47      | 1        | 0.24%   |
| 0xa0653    | 1        | 0.24%   |
| 0x906ec    | 1        | 0.24%   |
| 0x706a1    | 1        | 0.24%   |
| 0x6fd      | 1        | 0.24%   |
| 0x6fb      | 1        | 0.24%   |
| 0x506e8    | 1        | 0.24%   |
| 0x50654    | 1        | 0.24%   |
| 0x406c3    | 1        | 0.24%   |
| 0x306d4    | 1        | 0.24%   |
| 0x0a201204 | 1        | 0.24%   |
| 0x08600103 | 1        | 0.24%   |
| 0x08108102 | 1        | 0.24%   |
| 0x08001137 | 1        | 0.24%   |
| 0x0600611a | 1        | 0.24%   |
| 0x06006118 | 1        | 0.24%   |
| 0x0600063e | 1        | 0.24%   |
| 0x010000c8 | 1        | 0.24%   |
| 0x010000c7 | 1        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 47       | 11.27%  |
| Haswell          | 47       | 11.27%  |
| Penryn           | 33       | 7.91%   |
| IvyBridge        | 33       | 7.91%   |
| SandyBridge      | 30       | 7.19%   |
| Zen 3            | 28       | 6.71%   |
| Zen 2            | 25       | 6%      |
| Piledriver       | 21       | 5.04%   |
| K10              | 20       | 4.8%    |
| Zen+             | 18       | 4.32%   |
| Skylake          | 17       | 4.08%   |
| Zen              | 16       | 3.84%   |
| CometLake        | 15       | 3.6%    |
| Nehalem          | 11       | 2.64%   |
| Core             | 11       | 2.64%   |
| Alderlake Hybrid | 8        | 1.92%   |
| Westmere         | 5        | 1.2%    |
| K8 Hammer        | 5        | 1.2%    |
| Unknown          | 5        | 1.2%    |
| Icelake          | 4        | 0.96%   |
| Excavator        | 4        | 0.96%   |
| NetBurst         | 3        | 0.72%   |
| Broadwell        | 3        | 0.72%   |
| Silvermont       | 2        | 0.48%   |
| Goldmont plus    | 2        | 0.48%   |
| Bulldozer        | 2        | 0.48%   |
| K10 Llano        | 1        | 0.24%   |
| Bonnell          | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 179      | 41.63%  |
| AMD                                          | 127      | 29.53%  |
| Intel                                        | 123      | 28.6%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 4.32%   |
| Nvidia GK208B [GeForce GT 710]                                              | 15       | 3.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 13       | 2.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13       | 2.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12       | 2.73%   |
| Intel AlderLake-S GT1                                                       | 10       | 2.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 2.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 9        | 2.05%   |
| AMD Cezanne                                                                 | 9        | 2.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 1.82%   |
| Intel HD Graphics 530                                                       | 8        | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 8        | 1.82%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 1.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 1.59%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.36%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 1.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 1.36%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 6        | 1.36%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 5        | 1.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.14%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.14%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 1.14%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 0.91%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 0.91%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.91%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 0.91%   |
| Intel HD Graphics 630                                                       | 4        | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.91%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 0.91%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 0.68%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 0.68%   |
| Nvidia GK107 [GeForce GT 640]                                               | 3        | 0.68%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 0.68%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.68%   |
| AMD Richland [Radeon HD 8570D]                                              | 3        | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 0.68%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 0.68%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                | 3        | 0.68%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 3        | 0.68%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 0.68%   |
| AMD Barts XT [Radeon HD 6870]                                               | 3        | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.45%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.45%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.45%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.45%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 2        | 0.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.45%   |
| Nvidia GP100GL [Quadro GP100]                                               | 2        | 0.45%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.45%   |
| Nvidia GM107GL [Quadro K2200]                                               | 2        | 0.45%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.45%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 2        | 0.45%   |
| Nvidia GK107GL [GRID K1]                                                    | 2        | 0.45%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.45%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 166      | 39.81%  |
| 1 x AMD        | 118      | 28.3%   |
| 1 x Intel      | 114      | 27.34%  |
| 2 x Nvidia     | 5        | 1.2%    |
| 2 x AMD        | 4        | 0.96%   |
| Intel + Nvidia | 4        | 0.96%   |
| Intel + AMD    | 3        | 0.72%   |
| AMD + Nvidia   | 2        | 0.48%   |
| 1 x XGI        | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 294      | 69.83%  |
| Proprietary | 107      | 25.42%  |
| Unknown     | 20       | 4.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 300      | 71.6%   |
| 1.01-2.0   | 34       | 8.11%   |
| 7.01-8.0   | 20       | 4.77%   |
| 0.51-1.0   | 17       | 4.06%   |
| 3.01-4.0   | 14       | 3.34%   |
| 0.01-0.5   | 11       | 2.63%   |
| 8.01-16.0  | 10       | 2.39%   |
| 5.01-6.0   | 8        | 1.91%   |
| 2.01-3.0   | 5        | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 67       | 15.47%  |
| Dell                 | 54       | 12.47%  |
| Goldstar             | 45       | 10.39%  |
| Hewlett-Packard      | 25       | 5.77%   |
| Acer                 | 24       | 5.54%   |
| Philips              | 23       | 5.31%   |
| AOC                  | 23       | 5.31%   |
| Ancor Communications | 20       | 4.62%   |
| BenQ                 | 18       | 4.16%   |
| ASUSTek Computer     | 11       | 2.54%   |
| ViewSonic            | 10       | 2.31%   |
| Unknown              | 9        | 2.08%   |
| Lenovo               | 9        | 2.08%   |
| Iiyama               | 9        | 2.08%   |
| Sony                 | 7        | 1.62%   |
| Medion               | 6        | 1.39%   |
| NEC Computers        | 5        | 1.15%   |
| Vizio                | 4        | 0.92%   |
| Fujitsu Siemens      | 4        | 0.92%   |
| Toshiba              | 3        | 0.69%   |
| MSI                  | 3        | 0.69%   |
| LG Electronics       | 3        | 0.69%   |
| Hyundai ImageQuest   | 3        | 0.69%   |
| Compaq Computer      | 3        | 0.69%   |
| SKY                  | 2        | 0.46%   |
| Sceptre Tech         | 2        | 0.46%   |
| Packard Bell         | 2        | 0.46%   |
| HJW                  | 2        | 0.46%   |
| HannStar             | 2        | 0.46%   |
| Eizo                 | 2        | 0.46%   |
| ___                  | 1        | 0.23%   |
| Westinghouse         | 1        | 0.23%   |
| Wacom                | 1        | 0.23%   |
| VIZ                  | 1        | 0.23%   |
| VIE                  | 1        | 0.23%   |
| Sun                  | 1        | 0.23%   |
| Sanyo                | 1        | 0.23%   |
| SAC                  | 1        | 0.23%   |
| PZG                  | 1        | 0.23%   |
| PKB                  | 1        | 0.23%   |
| Panasonic            | 1        | 0.23%   |
| OEM                  | 1        | 0.23%   |
| NVISION              | 1        | 0.23%   |
| NUL                  | 1        | 0.23%   |
| MStar                | 1        | 0.23%   |
| LYC                  | 1        | 0.23%   |
| LED                  | 1        | 0.23%   |
| IPS                  | 1        | 0.23%   |
| Hitachi              | 1        | 0.23%   |
| HannStar Display     | 1        | 0.23%   |
| Grundig              | 1        | 0.23%   |
| Gigabyte Technology  | 1        | 0.23%   |
| FUS                  | 1        | 0.23%   |
| Fujitsu              | 1        | 0.23%   |
| Denver               | 1        | 0.23%   |
| DENON                | 1        | 0.23%   |
| CVT                  | 1        | 0.23%   |
| CHD                  | 1        | 0.23%   |
| Belinea              | 1        | 0.23%   |
| AUS                  | 1        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 4        | 0.87%   |
| ASUSTek Computer VP278 AUS27AE 1920x1080 598x336mm 27.0-inch          | 4        | 0.87%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.65%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 3        | 0.65%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.65%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 3        | 0.65%   |
| AOC 27B1 AOC2701 1920x1080 598x336mm 27.0-inch                        | 3        | 0.65%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 3        | 0.65%   |
| Vizio D55-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                    | 2        | 0.44%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 0.44%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.44%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.44%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 600x340mm 27.2-inch               | 2        | 0.44%   |
| Philips 220XW PHLC01B 1680x1050 474x297mm 22.0-inch                   | 2        | 0.44%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch          | 2        | 0.44%   |
| Goldstar W2442 GSM56CC 1920x1080 531x299mm 24.0-inch                  | 2        | 0.44%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 2        | 0.44%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 0.44%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                    | 2        | 0.44%   |
| Compaq Computer Compaq Q1859 CPQ2826 1366x768 410x230mm 18.5-inch     | 2        | 0.44%   |
| BenQ GL2580 BNQ78E5 1920x1080 544x303mm 24.5-inch                     | 2        | 0.44%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 2        | 0.44%   |
| ASUSTek Computer VZ239 AUS23CC 1920x1080 509x286mm 23.0-inch          | 2        | 0.44%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 620x340mm 27.8-inch          | 2        | 0.44%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                     | 2        | 0.44%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 2        | 0.44%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 480x270mm 21.7-inch | 2        | 0.44%   |
| Acer K272HL ACR0523 1920x1080 598x336mm 27.0-inch                     | 2        | 0.44%   |
| ___ LCDTV16 ___0101 1360x768                                          | 1        | 0.22%   |
| Westinghouse LTV-19w6 WDE1906 1440x900 408x255mm 18.9-inch            | 1        | 0.22%   |
| Wacom Cintiq21UX WAC1014 1600x1200 432x324mm 21.3-inch                | 1        | 0.22%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                    | 1        | 0.22%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                   | 1        | 0.22%   |
| VIZ LCD Monitor V405-H9 3840x2160                                     | 1        | 0.22%   |
| ViewSonic XG270QC VSCC438 2560x1440 597x336mm 27.0-inch               | 1        | 0.22%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                | 1        | 0.22%   |
| ViewSonic VX2476 Series VSC9939 1920x1080 527x296mm 23.8-inch         | 1        | 0.22%   |
| ViewSonic VP2468 Series VSCB032 1920x1080 527x296mm 23.8-inch         | 1        | 0.22%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                 | 1        | 0.22%   |
| ViewSonic VA2703 Series VSC622A 1920x1080 598x336mm 27.0-inch         | 1        | 0.22%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                | 1        | 0.22%   |
| ViewSonic PF790-2 VSC4500 1600x1200 353x265mm 17.4-inch               | 1        | 0.22%   |
| VIE A2256 VIEE001 1920x1080 509x286mm 23.0-inch                       | 1        | 0.22%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 1        | 0.22%   |
| Unknown LCD Monitor XXX WXGA TV 1360x768                              | 1        | 0.22%   |
| Unknown LCD Monitor XXX WXGA TV                                       | 1        | 0.22%   |
| Unknown LCD Monitor XMD Mi TV 1920x1080                               | 1        | 0.22%   |
| Unknown LCD Monitor Sanyo Electric Co.,Ltd. SANYO-TV 1360x765         | 1        | 0.22%   |
| Unknown LCD Monitor PHILIPS FTV 1360x768                              | 1        | 0.22%   |
| Unknown LCD Monitor Maxdata/XXXXXXX BelArtist22W 5520x2160            | 1        | 0.22%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.22%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 1        | 0.22%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1        | 0.22%   |
| Toshiba 55UHD_LCD_TV TSB3700 3840x2160 1872x1053mm 84.6-inch          | 1        | 0.22%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1        | 0.22%   |
| Sony TV SNY5501 1024x768 1600x900mm 72.3-inch                         | 1        | 0.22%   |
| Sony TV SNY2801 1920x1080                                             | 1        | 0.22%   |
| Sony TV *00 SNYF303 1920x1080 952x535mm 43.0-inch                     | 1        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 188      | 44.55%  |
| 3840x2160 (4K)     | 40       | 9.48%   |
| 1680x1050 (WSXGA+) | 33       | 7.82%   |
| 1280x1024 (SXGA)   | 31       | 7.35%   |
| 2560x1440 (QHD)    | 30       | 7.11%   |
| 1920x1200 (WUXGA)  | 14       | 3.32%   |
| 1440x900 (WXGA+)   | 13       | 3.08%   |
| Unknown            | 11       | 2.61%   |
| 3440x1440          | 8        | 1.9%    |
| 1366x768 (WXGA)    | 8        | 1.9%    |
| 1360x768           | 8        | 1.9%    |
| 2560x1080          | 7        | 1.66%   |
| 1600x900 (HD+)     | 7        | 1.66%   |
| 3840x1080          | 5        | 1.18%   |
| 1600x1200          | 3        | 0.71%   |
| 3200x1080          | 2        | 0.47%   |
| 2560x1600          | 2        | 0.47%   |
| 1920x540           | 2        | 0.47%   |
| 5520x2160          | 1        | 0.24%   |
| 4480x1440          | 1        | 0.24%   |
| 4480x1080          | 1        | 0.24%   |
| 3840x1600          | 1        | 0.24%   |
| 2288x1287          | 1        | 0.24%   |
| 1400x1050          | 1        | 0.24%   |
| 1360x765           | 1        | 0.24%   |
| 1280x768           | 1        | 0.24%   |
| 1280x720 (HD)      | 1        | 0.24%   |
| 1024x768 (XGA)     | 1        | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 65       | 15.51%  |
| 23      | 55       | 13.13%  |
| 24      | 48       | 11.46%  |
| 21      | 45       | 10.74%  |
| Unknown | 39       | 9.31%   |
| 19      | 25       | 5.97%   |
| 22      | 23       | 5.49%   |
| 17      | 16       | 3.82%   |
| 18      | 14       | 3.34%   |
| 34      | 12       | 2.86%   |
| 31      | 12       | 2.86%   |
| 20      | 10       | 2.39%   |
| 72      | 7        | 1.67%   |
| 84      | 6        | 1.43%   |
| 40      | 5        | 1.19%   |
| 26      | 5        | 1.19%   |
| 54      | 3        | 0.72%   |
| 49      | 3        | 0.72%   |
| 65      | 2        | 0.48%   |
| 33      | 2        | 0.48%   |
| 32      | 2        | 0.48%   |
| 30      | 2        | 0.48%   |
| 15      | 2        | 0.48%   |
| 142     | 1        | 0.24%   |
| 75      | 1        | 0.24%   |
| 74      | 1        | 0.24%   |
| 64      | 1        | 0.24%   |
| 63      | 1        | 0.24%   |
| 59      | 1        | 0.24%   |
| 57      | 1        | 0.24%   |
| 52      | 1        | 0.24%   |
| 48      | 1        | 0.24%   |
| 46      | 1        | 0.24%   |
| 42      | 1        | 0.24%   |
| 41      | 1        | 0.24%   |
| 38      | 1        | 0.24%   |
| 37      | 1        | 0.24%   |
| 28      | 1        | 0.24%   |
| 14      | 1        | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 156      | 38.14%  |
| 401-500        | 99       | 24.21%  |
| Unknown        | 39       | 9.54%   |
| 601-700        | 24       | 5.87%   |
| 351-400        | 17       | 4.16%   |
| 301-350        | 17       | 4.16%   |
| 701-800        | 16       | 3.91%   |
| 1501-2000      | 15       | 3.67%   |
| 1001-1500      | 15       | 3.67%   |
| 801-900        | 7        | 1.71%   |
| 901-1000       | 2        | 0.49%   |
| More than 2000 | 1        | 0.24%   |
| 201-300        | 1        | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 240      | 61.54%  |
| 16/10   | 55       | 14.1%   |
| Unknown | 36       | 9.23%   |
| 5/4     | 30       | 7.69%   |
| 21/9    | 15       | 3.85%   |
| 4/3     | 6        | 1.54%   |
| 3/2     | 4        | 1.03%   |
| 6/5     | 2        | 0.51%   |
| 1.00    | 2        | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 141      | 34.14%  |
| 301-350        | 68       | 16.46%  |
| 151-200        | 51       | 12.35%  |
| Unknown        | 39       | 9.44%   |
| 351-500        | 31       | 7.51%   |
| More than 1000 | 30       | 7.26%   |
| 141-150        | 21       | 5.08%   |
| 251-300        | 19       | 4.6%    |
| 501-1000       | 10       | 2.42%   |
| 101-110        | 3        | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 249      | 62.25%  |
| 101-120 | 67       | 16.75%  |
| Unknown | 39       | 9.75%   |
| 1-50    | 23       | 5.75%   |
| 121-160 | 13       | 3.25%   |
| 161-240 | 9        | 2.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 309      | 73.4%   |
| 2     | 75       | 17.81%  |
| 0     | 27       | 6.41%   |
| 3     | 10       | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 253      | 42.31%  |
| Intel                           | 186      | 31.1%   |
| Qualcomm Atheros                | 40       | 6.69%   |
| Broadcom                        | 23       | 3.85%   |
| TP-Link                         | 17       | 2.84%   |
| Ralink Technology               | 12       | 2.01%   |
| Ralink                          | 6        | 1%      |
| Nvidia                          | 6        | 1%      |
| Microsoft                       | 5        | 0.84%   |
| Marvell Technology Group        | 5        | 0.84%   |
| Aquantia                        | 5        | 0.84%   |
| Qualcomm Atheros Communications | 4        | 0.67%   |
| NetGear                         | 4        | 0.67%   |
| Linksys                         | 3        | 0.5%    |
| ASUSTek Computer                | 3        | 0.5%    |
| Samsung Electronics             | 2        | 0.33%   |
| Micro Star International        | 2        | 0.33%   |
| MediaTek                        | 2        | 0.33%   |
| DisplayLink                     | 2        | 0.33%   |
| D-Link System                   | 2        | 0.33%   |
| Broadcom Limited                | 2        | 0.33%   |
| Wacom                           | 1        | 0.17%   |
| VIA Technologies                | 1        | 0.17%   |
| Tenda                           | 1        | 0.17%   |
| STMicroelectronics              | 1        | 0.17%   |
| SILICON Laboratories            | 1        | 0.17%   |
| Microchip Technology            | 1        | 0.17%   |
| JMicron Technology              | 1        | 0.17%   |
| IMC Networks                    | 1        | 0.17%   |
| GDMicroelectronics              | 1        | 0.17%   |
| Elecom                          | 1        | 0.17%   |
| D-Link                          | 1        | 0.17%   |
| Belkin Components               | 1        | 0.17%   |
| AVM                             | 1        | 0.17%   |
| ASIX Electronics                | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 183      | 26.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 34       | 4.99%   |
| Intel Wi-Fi 6 AX200                                               | 28       | 4.11%   |
| Intel I211 Gigabit Network Connection                             | 26       | 3.82%   |
| Intel Ethernet Connection (2) I219-V                              | 22       | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 3.23%   |
| Intel Ethernet Connection (7) I219-V                              | 13       | 1.91%   |
| Intel Ethernet Controller I225-V                                  | 11       | 1.62%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8        | 1.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.03%   |
| Realtek 802.11ac NIC                                              | 7        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 7        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 7        | 1.03%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6        | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 6        | 0.88%   |
| Ralink MT7601U Wireless Adapter                                   | 6        | 0.88%   |
| Intel Wireless-AC 9260                                            | 6        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 6        | 0.88%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6        | 0.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 5        | 0.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5        | 0.73%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 4        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 0.59%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4        | 0.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.59%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.59%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 4        | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4        | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.44%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.44%   |
| Microsoft Xbox 360 Wireless Adapter                               | 3        | 0.44%   |
| Intel Wireless 7260                                               | 3        | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.29%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.29%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.29%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2        | 0.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 0.29%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.29%   |
| Ralink RT5372 Wireless Adapter                                    | 2        | 0.29%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.29%   |
| Ralink RT2800 802.11n PCI                                         | 2        | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.29%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 78       | 36.28%  |
| Realtek Semiconductor           | 44       | 20.47%  |
| Qualcomm Atheros                | 18       | 8.37%   |
| TP-Link                         | 16       | 7.44%   |
| Ralink Technology               | 12       | 5.58%   |
| Broadcom                        | 9        | 4.19%   |
| Ralink                          | 6        | 2.79%   |
| Microsoft                       | 5        | 2.33%   |
| Qualcomm Atheros Communications | 4        | 1.86%   |
| NetGear                         | 4        | 1.86%   |
| Linksys                         | 3        | 1.4%    |
| ASUSTek Computer                | 3        | 1.4%    |
| Micro Star International        | 2        | 0.93%   |
| D-Link System                   | 2        | 0.93%   |
| Wacom                           | 1        | 0.47%   |
| Tenda                           | 1        | 0.47%   |
| MediaTek                        | 1        | 0.47%   |
| IMC Networks                    | 1        | 0.47%   |
| Elecom                          | 1        | 0.47%   |
| D-Link                          | 1        | 0.47%   |
| Broadcom Limited                | 1        | 0.47%   |
| Belkin Components               | 1        | 0.47%   |
| AVM                             | 1        | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 28       | 13.02%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 8        | 3.72%   |
| Realtek 802.11ac NIC                                                       | 7        | 3.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 7        | 3.26%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 7        | 3.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 6        | 2.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 6        | 2.79%   |
| Ralink MT7601U Wireless Adapter                                            | 6        | 2.79%   |
| Intel Wireless-AC 9260                                                     | 6        | 2.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 6        | 2.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 5        | 2.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 5        | 2.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 4        | 1.86%   |
| Qualcomm Atheros AR9271 802.11n                                            | 4        | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4        | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3        | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 3        | 1.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 3        | 1.4%    |
| Microsoft Xbox 360 Wireless Adapter                                        | 3        | 1.4%    |
| Intel Wireless 7260                                                        | 3        | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                             | 3        | 1.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2        | 0.93%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 2        | 0.93%   |
| TP-Link 802.11ac WLAN Adapter                                              | 2        | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 2        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 2        | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 2        | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2        | 0.93%   |
| Ralink RT5372 Wireless Adapter                                             | 2        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                             | 2        | 0.93%   |
| Ralink RT2800 802.11n PCI                                                  | 2        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2        | 0.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 0.93%   |
| Microsoft Wireless XBox Controller Dongle                                  | 2        | 0.93%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 2        | 0.93%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                          | 2        | 0.93%   |
| Intel Wireless 8260                                                        | 2        | 0.93%   |
| Intel Wireless 7265                                                        | 2        | 0.93%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]          | 2        | 0.93%   |
| Broadcom Network controller                                                | 2        | 0.93%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]             | 2        | 0.93%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                   | 1        | 0.47%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 1        | 0.47%   |
| TP-Link Archer T4U ver.3                                                   | 1        | 0.47%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                  | 1        | 0.47%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 0.47%   |
| TP-Link 802.11n NIC                                                        | 1        | 0.47%   |
| Tenda U12                                                                  | 1        | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.47%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                        | 1        | 0.47%   |
| Realtek RTL8813AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                    | 1        | 0.47%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.47%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 0.47%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                     | 1        | 0.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1        | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 0.47%   |
| Realtek RTL8187 Wireless Adapter                                           | 1        | 0.47%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1        | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 235      | 51.54%  |
| Intel                    | 158      | 34.65%  |
| Qualcomm Atheros         | 22       | 4.82%   |
| Broadcom                 | 14       | 3.07%   |
| Nvidia                   | 6        | 1.32%   |
| Marvell Technology Group | 5        | 1.1%    |
| Aquantia                 | 5        | 1.1%    |
| Samsung Electronics      | 2        | 0.44%   |
| DisplayLink              | 2        | 0.44%   |
| VIA Technologies         | 1        | 0.22%   |
| TP-Link                  | 1        | 0.22%   |
| Microchip Technology     | 1        | 0.22%   |
| MediaTek                 | 1        | 0.22%   |
| JMicron Technology       | 1        | 0.22%   |
| Broadcom Limited         | 1        | 0.22%   |
| ASIX Electronics         | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 183      | 39.52%  |
| Realtek RTL8125 2.5GbE Controller                                 | 34       | 7.34%   |
| Intel I211 Gigabit Network Connection                             | 26       | 5.62%   |
| Intel Ethernet Connection (2) I219-V                              | 22       | 4.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 4.75%   |
| Intel Ethernet Connection (7) I219-V                              | 13       | 2.81%   |
| Intel Ethernet Controller I225-V                                  | 11       | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 2.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.51%   |
| Intel 82579V Gigabit Network Connection                           | 7        | 1.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 1.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 6        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 6        | 1.3%    |
| Intel Ethernet Connection (14) I219-V                             | 6        | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.86%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 4        | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4        | 0.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.65%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.43%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.43%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.43%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.43%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.43%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 2        | 0.43%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 0.43%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.43%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.22%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.22%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.22%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.22%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.22%   |
| Microchip LAN9500A/LAN9500Ai                                      | 1        | 0.22%   |
| MediaTek Infinix HOT 10T                                          | 1        | 0.22%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.22%   |
| Marvell Group 88E8070 based Ethernet Controller                   | 1        | 0.22%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.22%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.22%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.22%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.22%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.22%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.22%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 413      | 66.94%  |
| WiFi     | 201      | 32.58%  |
| Modem    | 3        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 365      | 69.52%  |
| WiFi     | 160      | 30.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 262      | 62.83%  |
| 2     | 121      | 29.02%  |
| 3     | 28       | 6.71%   |
| 5     | 2        | 0.48%   |
| 0     | 2        | 0.48%   |
| 6     | 1        | 0.24%   |
| 4     | 1        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 268      | 63.51%  |
| Yes  | 154      | 36.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 69       | 46%     |
| Cambridge Silicon Radio         | 43       | 28.67%  |
| Realtek Semiconductor           | 11       | 7.33%   |
| ASUSTek Computer                | 8        | 5.33%   |
| Qualcomm Atheros Communications | 7        | 4.67%   |
| Broadcom                        | 4        | 2.67%   |
| Micro Star International        | 2        | 1.33%   |
| Belkin Components               | 2        | 1.33%   |
| Apple                           | 2        | 1.33%   |
| Integrated System Solution      | 1        | 0.67%   |
| Edimax Technology               | 1        | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 43       | 28.67%  |
| Intel Bluetooth Device                                | 41       | 27.33%  |
| Realtek Bluetooth Radio                               | 9        | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 7        | 4.67%   |
| Intel AX210 Bluetooth                                 | 7        | 4.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 6        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                      | 6        | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 2.67%   |
| Qualcomm Atheros  Bluetooth Device                    | 3        | 2%      |
| ASUS ASUS USB-BT500                                   | 3        | 2%      |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 1.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 2        | 1.33%   |
| Micro Star International Bluetooth Device             | 2        | 1.33%   |
| Intel Bluetooth wireless interface                    | 2        | 1.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 1.33%   |
| Apple Bluetooth HCI                                   | 2        | 1.33%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1        | 0.67%   |
| Integrated System Solution Bluetooth Device           | 1        | 0.67%   |
| Edimax Bluetooth Adapter                              | 1        | 0.67%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.67%   |
| Belkin Components F8T001v2 Bluetooth                  | 1        | 0.67%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.67%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.67%   |
| ASUS Bluetooth Device                                 | 1        | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 257      | 36.87%  |
| Nvidia                     | 170      | 24.39%  |
| AMD                        | 166      | 23.82%  |
| Creative Labs              | 19       | 2.73%   |
| C-Media Electronics        | 14       | 2.01%   |
| Logitech                   | 10       | 1.43%   |
| ASUSTek Computer           | 5        | 0.72%   |
| Razer USA                  | 4        | 0.57%   |
| GN Netcom                  | 4        | 0.57%   |
| VIA Technologies           | 3        | 0.43%   |
| Tenx Technology            | 3        | 0.43%   |
| Focusrite-Novation         | 3        | 0.43%   |
| Corsair                    | 3        | 0.43%   |
| Yamaha                     | 2        | 0.29%   |
| XMOS                       | 2        | 0.29%   |
| Texas Instruments          | 2        | 0.29%   |
| Realtek Semiconductor      | 2        | 0.29%   |
| JMTek                      | 2        | 0.29%   |
| Generalplus Technology     | 2        | 0.29%   |
| Digidesign                 | 2        | 0.29%   |
| Creative Technology        | 2        | 0.29%   |
| Unknown                    | 1        | 0.14%   |
| Sennheiser Communications  | 1        | 0.14%   |
| SAVITECH                   | 1        | 0.14%   |
| Samson Technologies        | 1        | 0.14%   |
| RODE Microphones           | 1        | 0.14%   |
| PreSonus Audio Electronics | 1        | 0.14%   |
| Plantronics                | 1        | 0.14%   |
| Panasonic (Matsushita)     | 1        | 0.14%   |
| Native Instruments         | 1        | 0.14%   |
| Micro Star International   | 1        | 0.14%   |
| MAG Technology             | 1        | 0.14%   |
| M-Audio                    | 1        | 0.14%   |
| Kingston Technology        | 1        | 0.14%   |
| FIFINE Microphones         | 1        | 0.14%   |
| FENDER MUSICAL INSTRUMENTS | 1        | 0.14%   |
| DCMT Technology            | 1        | 0.14%   |
| Cambridge Silicon Radio    | 1        | 0.14%   |
| Bose                       | 1        | 0.14%   |
| Audio-Technica             | 1        | 0.14%   |
| Astro Gaming               | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 38       | 4.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 36       | 4.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 34       | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 32       | 3.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 26       | 3.22%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 24       | 2.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 23       | 2.85%   |
| Intel 200 Series PCH HD Audio                                                     | 22       | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 20       | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                        | 18       | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 18       | 2.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 18       | 2.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 17       | 2.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 15       | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 12       | 1.49%   |
| Nvidia High Definition Audio Controller                                           | 11       | 1.36%   |
| Intel Alder Lake-S HD Audio Controller                                            | 11       | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 11       | 1.36%   |
| Nvidia TU104 HD Audio Controller                                                  | 10       | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                                     | 10       | 1.24%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 10       | 1.24%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                         | 10       | 1.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 1.24%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 10       | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 9        | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                                     | 8        | 0.99%   |
| Nvidia GK107 HDMI Audio Controller                                                | 8        | 0.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 0.99%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 8        | 0.99%   |
| AMD Navi 10 HDMI Audio                                                            | 8        | 0.99%   |
| Nvidia GM206 High Definition Audio Controller                                     | 7        | 0.87%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 7        | 0.87%   |
| AMD FCH Azalia Controller                                                         | 7        | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                     | 6        | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                                     | 6        | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 6        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6        | 0.74%   |
| Intel Audio device                                                                | 6        | 0.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 6        | 0.74%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 0.74%   |
| Nvidia GK106 HDMI Audio Controller                                                | 5        | 0.62%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 5        | 0.62%   |
| Intel Comet Lake PCH cAVS                                                         | 5        | 0.62%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 5        | 0.62%   |
| AMD Trinity HDMI Audio Controller                                                 | 5        | 0.62%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 5        | 0.62%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 5        | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.5%    |
| Nvidia MCP61 High Definition Audio                                                | 4        | 0.5%    |
| Nvidia GM204 High Definition Audio Controller                                     | 4        | 0.5%    |
| Nvidia GK110 High Definition Audio Controller                                     | 4        | 0.5%    |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 0.5%    |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 0.5%    |
| Nvidia Audio device                                                               | 4        | 0.5%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 4        | 0.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 0.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 0.5%    |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 4        | 0.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 4        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 28       | 15.91%  |
| Corsair             | 26       | 14.77%  |
| G.Skill             | 22       | 12.5%   |
| Crucial             | 21       | 11.93%  |
| Unknown             | 19       | 10.8%   |
| Samsung Electronics | 16       | 9.09%   |
| SK Hynix            | 8        | 4.55%   |
| Micron Technology   | 8        | 4.55%   |
| Team                | 4        | 2.27%   |
| Nanya Technology    | 4        | 2.27%   |
| Patriot             | 3        | 1.7%    |
| A-DATA Technology   | 3        | 1.7%    |
| Transcend           | 2        | 1.14%   |
| PNY                 | 2        | 1.14%   |
| V-Color             | 1        | 0.57%   |
| Unknown (ABCD)      | 1        | 0.57%   |
| SMART               | 1        | 0.57%   |
| Ramaxel Technology  | 1        | 0.57%   |
| Kingmax             | 1        | 0.57%   |
| Hewlett-Packard     | 1        | 0.57%   |
| GEIL                | 1        | 0.57%   |
| Elpida              | 1        | 0.57%   |
| ASint Technology    | 1        | 0.57%   |
| Unknown             | 1        | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 7        | 3.7%    |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s         | 5        | 2.65%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s        | 3        | 1.59%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s          | 3        | 1.59%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 2        | 1.06%   |
| SK Hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s       | 2        | 1.06%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 1.06%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s          | 2        | 1.06%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s           | 2        | 1.06%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 2        | 1.06%   |
| Kingston RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s         | 2        | 1.06%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 2        | 1.06%   |
| G.Skill RAM F3-2133C9-8GXH 8GB DIMM DDR3 2133MT/s              | 2        | 1.06%   |
| Corsair RAM CMX8GX3M2A1600C9 4096MB DIMM DDR3 1800MT/s         | 2        | 1.06%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s         | 2        | 1.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 2        | 1.06%   |
| V-Color RAM TD48G26S819K-VC 8GB DIMM DDR4 2667MT/s             | 1        | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                      | 1        | 0.53%   |
| Unknown RAM Module 8GB DIMM 400MT/s                            | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 1        | 0.53%   |
| Unknown RAM Module 4GB DDR3 1600MT/s                           | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                      | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                           | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.53%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.53%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1        | 0.53%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s          | 1        | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 1        | 0.53%   |
| Transcend RAM TS512MLK72W6H 4GB DIMM DDR3 1600MT/s             | 1        | 0.53%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s               | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s            | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s             | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s             | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s          | 1        | 0.53%   |
| SMART RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1        | 0.53%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1333MT/s                     | 1        | 0.53%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.53%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.53%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.53%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s           | 1        | 0.53%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.53%   |
| Samsung RAM Module 32GB DIMM DDR4 2933MT/s                     | 1        | 0.53%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 1        | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DIMM DDR4 2667MT/s            | 1        | 0.53%   |
| Samsung RAM M393B1K70DH0 8192MB DIMM DDR3 1866MT/s             | 1        | 0.53%   |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1333MT/s            | 1        | 0.53%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.53%   |
| Samsung RAM M378B5773DH0-CK0 2048MB DIMM DDR3 1600MT/s         | 1        | 0.53%   |
| Samsung RAM M378B5673FH0-CF8 2048MB DIMM DDR3 1067MT/s         | 1        | 0.53%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s          | 1        | 0.53%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s         | 1        | 0.53%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s            | 1        | 0.53%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2400MT/s            | 1        | 0.53%   |
| Samsung RAM M378A2K43CB1-CRC 16GB DIMM DDR4 2400MT/s           | 1        | 0.53%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s           | 1        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 93       | 60%     |
| DDR3    | 39       | 25.16%  |
| Unknown | 10       | 6.45%   |
| DDR2    | 5        | 3.23%   |
| SDRAM   | 3        | 1.94%   |
| DRAM    | 2        | 1.29%   |
| DDR     | 2        | 1.29%   |
| LPDDR4  | 1        | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 144      | 95.36%  |
| SODIMM  | 6        | 3.97%   |
| Unknown | 1        | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 70       | 41.67%  |
| 16384 | 36       | 21.43%  |
| 4096  | 34       | 20.24%  |
| 2048  | 15       | 8.93%   |
| 32768 | 10       | 5.95%   |
| 1024  | 3        | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 29       | 17.26%  |
| 1600    | 18       | 10.71%  |
| 1333    | 17       | 10.12%  |
| 2400    | 14       | 8.33%   |
| 3600    | 13       | 7.74%   |
| 2667    | 13       | 7.74%   |
| 2133    | 13       | 7.74%   |
| 1800    | 5        | 2.98%   |
| 2933    | 4        | 2.38%   |
| 3533    | 3        | 1.79%   |
| 3266    | 3        | 1.79%   |
| 2048    | 3        | 1.79%   |
| 1867    | 3        | 1.79%   |
| 49926   | 2        | 1.19%   |
| 3733    | 2        | 1.19%   |
| 3000    | 2        | 1.19%   |
| 2666    | 2        | 1.19%   |
| 1067    | 2        | 1.19%   |
| 800     | 2        | 1.19%   |
| 533     | 2        | 1.19%   |
| Unknown | 2        | 1.19%   |
| 4266    | 1        | 0.6%    |
| 4000    | 1        | 0.6%    |
| 3866    | 1        | 0.6%    |
| 3800    | 1        | 0.6%    |
| 3400    | 1        | 0.6%    |
| 3067    | 1        | 0.6%    |
| 2800    | 1        | 0.6%    |
| 2733    | 1        | 0.6%    |
| 2134    | 1        | 0.6%    |
| 2000    | 1        | 0.6%    |
| 1866    | 1        | 0.6%    |
| 1066    | 1        | 0.6%    |
| 667     | 1        | 0.6%    |
| 400     | 1        | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 9        | 33.33%  |
| Hewlett-Packard     | 7        | 25.93%  |
| Canon               | 7        | 25.93%  |
| Brother Industries  | 4        | 14.81%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung SCX-3400 Series                               | 2        | 7.41%   |
| Samsung M283x Series                                  | 2        | 7.41%   |
| Brother Printer                                       | 2        | 7.41%   |
| Samsung ML-216x Series Laser Printer                  | 1        | 3.7%    |
| Samsung ML-1865                                       | 1        | 3.7%    |
| Samsung Composite Device                              | 1        | 3.7%    |
| Samsung C48x Series Color Laser Multifunction Printer | 1        | 3.7%    |
| Samsung C43x Series                                   | 1        | 3.7%    |
| HP OfficeJet 5200 series                              | 1        | 3.7%    |
| HP LaserJet 400 M401dne                               | 1        | 3.7%    |
| HP LaserJet 400 colorMFP M475dw                       | 1        | 3.7%    |
| HP ENVY Photo 6200 series                             | 1        | 3.7%    |
| HP DeskJet F4100 Printer series                       | 1        | 3.7%    |
| HP DeskJet 3700 series                                | 1        | 3.7%    |
| HP Deskjet 1050 J410                                  | 1        | 3.7%    |
| Canon TR8600 series                                   | 1        | 3.7%    |
| Canon TR4500 series                                   | 1        | 3.7%    |
| Canon PIXMA MP280                                     | 1        | 3.7%    |
| Canon PIXMA MG3600 Series                             | 1        | 3.7%    |
| Canon PIXMA MG2500 Series                             | 1        | 3.7%    |
| Canon MF731C/733C                                     | 1        | 3.7%    |
| Canon iP7200 series                                   | 1        | 3.7%    |
| Brother HL-3140CW series                              | 1        | 3.7%    |
| Brother HL-1430 Laser Printer                         | 1        | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 5        | 55.56%  |
| Seiko Epson     | 3        | 33.33%  |
| Hewlett-Packard | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                          | 2        | 20%     |
| Seiko Epson Scanner                              | 1        | 10%     |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1        | 10%     |
| Seiko Epson GT-9400UF [Perfection 3170]          | 1        | 10%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]    | 1        | 10%     |
| HP ScanJet 3970c                                 | 1        | 10%     |
| Canon CanoScan N1240U/LiDE 30                    | 1        | 10%     |
| Canon CanoScan LIDE 25                           | 1        | 10%     |
| Canon CanoScan LiDE 200                          | 1        | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 39       | 48.75%  |
| Microdia                      | 7        | 8.75%   |
| Microsoft                     | 5        | 6.25%   |
| Generalplus Technology        | 4        | 5%      |
| Samsung Electronics           | 3        | 3.75%   |
| ARC International             | 3        | 3.75%   |
| Apple                         | 3        | 3.75%   |
| Unknown                       | 2        | 2.5%    |
| Sunplus Innovation Technology | 2        | 2.5%    |
| Realtek Semiconductor         | 2        | 2.5%    |
| Huawei Technologies           | 2        | 2.5%    |
| Z-Star Microelectronics       | 1        | 1.25%   |
| Sony                          | 1        | 1.25%   |
| PrehKeyTec                    | 1        | 1.25%   |
| Philips (or NXP)              | 1        | 1.25%   |
| PC-LM1E                       | 1        | 1.25%   |
| OmniVision Technologies       | 1        | 1.25%   |
| Jieli Technology              | 1        | 1.25%   |
| Creative Technology           | 1        | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 11       | 13.75%  |
| Logitech HD Webcam C910                   | 4        | 5%      |
| Samsung Galaxy A5 (MTP)                   | 3        | 3.75%   |
| Logitech Webcam C930e                     | 3        | 3.75%   |
| Logitech HD Webcam C615                   | 3        | 3.75%   |
| Logitech HD Pro Webcam C920               | 3        | 3.75%   |
| ARC International Camera                  | 3        | 3.75%   |
| Microsoft LifeCam HD-3000                 | 2        | 2.5%    |
| Microdia Webcam Vitade AF                 | 2        | 2.5%    |
| Microdia USB Live camera                  | 2        | 2.5%    |
| Logitech C922 Pro Stream Webcam           | 2        | 2.5%    |
| Logitech BRIO                             | 2        | 2.5%    |
| Huawei UVC Camera                         | 2        | 2.5%    |
| Generalplus GENERAL WEBCAM                | 2        | 2.5%    |
| Generalplus 808 Camera                    | 2        | 2.5%    |
| Z-Star Lenovo USB 2.0 UVC Camera          | 1        | 1.25%   |
| Unknown Integrated RGB Camera             | 1        | 1.25%   |
| Unknown HD camera                         | 1        | 1.25%   |
| Sunplus HD 720P webcam                    | 1        | 1.25%   |
| Sunplus FHD Camera Microphone             | 1        | 1.25%   |
| Sony CEVCECM                              | 1        | 1.25%   |
| Realtek NexiGo N660P FHD Webcam           | 1        | 1.25%   |
| Realtek HK 2M CAM                         | 1        | 1.25%   |
| PrehKeyTec TA-0120-AS                     | 1        | 1.25%   |
| Philips (or NXP) SPC 520/525NC PC Camera  | 1        | 1.25%   |
| PC-LM1E PC-LM1E                           | 1        | 1.25%   |
| OmniVision Monitor Webcam                 | 1        | 1.25%   |
| Microsoft LifeCam VX-7000 (UVC-compliant) | 1        | 1.25%   |
| Microsoft LifeCam Studio                  | 1        | 1.25%   |
| Microsoft LifeCam HD-5000                 | 1        | 1.25%   |
| Microdia USB camera                       | 1        | 1.25%   |
| Microdia USB 2.0 Camera                   | 1        | 1.25%   |
| Microdia Sonix USB 2.0 Camera             | 1        | 1.25%   |
| Logitech Webcam Pro 9000                  | 1        | 1.25%   |
| Logitech Webcam C310                      | 1        | 1.25%   |
| Logitech Webcam C300                      | 1        | 1.25%   |
| Logitech Webcam C110                      | 1        | 1.25%   |
| Logitech QuickCam Pro for Notebooks       | 1        | 1.25%   |
| Logitech QuickCam Pro 9000                | 1        | 1.25%   |
| Logitech QuickCam Orbit/Sphere AF         | 1        | 1.25%   |
| Logitech HD Webcam C525                   | 1        | 1.25%   |
| Logitech HD Webcam B910                   | 1        | 1.25%   |
| Logitech C920 PRO HD Webcam               | 1        | 1.25%   |
| Logitech B525 HD Webcam                   | 1        | 1.25%   |
| Jieli USB PHY 2.0                         | 1        | 1.25%   |
| Creative Live! Cam Chat HD [VF0700]       | 1        | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE                 | 1        | 1.25%   |
| Apple iPhone 4S                           | 1        | 1.25%   |
| Apple iPhone 4                            | 1        | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Elan ELAN:Fingerprint | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Reiner SCT Kartensysteme | 1        | 33.33%  |
| Realtek Semiconductor    | 1        | 33.33%  |
| Hewlett-Packard          | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 33.33%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 33.33%  |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                              | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 356      | 85.17%  |
| 1     | 55       | 13.16%  |
| 2     | 6        | 1.44%   |
| 5     | 1        | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 27       | 40.3%   |
| Net/wireless             | 17       | 25.37%  |
| Unassigned class         | 5        | 7.46%   |
| Multimedia controller    | 4        | 5.97%   |
| Communication controller | 3        | 4.48%   |
| Storage/raid             | 2        | 2.99%   |
| Sound                    | 2        | 2.99%   |
| Chipcard                 | 2        | 2.99%   |
| Modem                    | 1        | 1.49%   |
| Fingerprint reader       | 1        | 1.49%   |
| Card reader              | 1        | 1.49%   |
| Camera                   | 1        | 1.49%   |
| Bluetooth                | 1        | 1.49%   |


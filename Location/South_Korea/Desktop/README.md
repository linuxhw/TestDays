Linux in South Korea - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in South Korea.

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

Total: 309

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Pelco by S... | DS-SRV2 S584XF01            | [7ed2a57a58](https://linux-hardware.org/?probe=7ed2a57a58) | Jan 03, 2025 |
| Gigabyte      | AX370-Gaming 3-CF           | [0124649cba](https://linux-hardware.org/?probe=0124649cba) | Dec 10, 2024 |
| Samsung       | DB400TDA-Y0J/C SGLA933A0... | [60318edf7e](https://linux-hardware.org/?probe=60318edf7e) | Dec 02, 2024 |
| ASUSTek       | PRIME B550M-A               | [1666d53ef2](https://linux-hardware.org/?probe=1666d53ef2) | Nov 29, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [005802da6e](https://linux-hardware.org/?probe=005802da6e) | Nov 27, 2024 |
| ASRock        | Z370 Pro4                   | [444d9d7d0b](https://linux-hardware.org/?probe=444d9d7d0b) | Nov 25, 2024 |
| Gigabyte      | H310M DS2V                  | [dbdc4d0b28](https://linux-hardware.org/?probe=dbdc4d0b28) | Nov 16, 2024 |
| Gigabyte      | H310M DS2V                  | [d7105643fd](https://linux-hardware.org/?probe=d7105643fd) | Nov 16, 2024 |
| MSI           | H110M PRO-D                 | [452d20c7fd](https://linux-hardware.org/?probe=452d20c7fd) | Nov 13, 2024 |
| ASUSTek       | PRIME A520M-K               | [f33ffb3943](https://linux-hardware.org/?probe=f33ffb3943) | Nov 09, 2024 |
| MSI           | H110M PRO-D                 | [57f9a23010](https://linux-hardware.org/?probe=57f9a23010) | Nov 08, 2024 |
| MACHINIST     | B450 TFA AM4 Ver:1.00       | [1c53ab0ce4](https://linux-hardware.org/?probe=1c53ab0ce4) | Nov 03, 2024 |
| ASRock        | B650 LiveMixer              | [1cae9e87fc](https://linux-hardware.org/?probe=1cae9e87fc) | Oct 25, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ba5edb5b03](https://linux-hardware.org/?probe=ba5edb5b03) | Sep 24, 2024 |
| MSI           | Z68A-G45                    | [1ce550c189](https://linux-hardware.org/?probe=1ce550c189) | Sep 23, 2024 |
| ASRock        | B660M Pro RS                | [e76b66c215](https://linux-hardware.org/?probe=e76b66c215) | Sep 10, 2024 |
| SZQFTX        | MI2-SC                      | [354ecda750](https://linux-hardware.org/?probe=354ecda750) | Sep 06, 2024 |
| Gigabyte      | X299 UD4 Pro-CF             | [a2599a2d08](https://linux-hardware.org/?probe=a2599a2d08) | Sep 03, 2024 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | [65e4e049fb](https://linux-hardware.org/?probe=65e4e049fb) | Aug 26, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [cb33d4fa31](https://linux-hardware.org/?probe=cb33d4fa31) | Aug 25, 2024 |
| ASUSTek       | Z87-C                       | [8950e85ffb](https://linux-hardware.org/?probe=8950e85ffb) | Aug 23, 2024 |
| ASRock        | B650 LiveMixer              | [5570dc6d1f](https://linux-hardware.org/?probe=5570dc6d1f) | Aug 13, 2024 |
| ASRock        | 970A-G                      | [7d66332210](https://linux-hardware.org/?probe=7d66332210) | Jul 26, 2024 |
| MSI           | MPG Z690 EDGE WIFI          | [48f334b6ed](https://linux-hardware.org/?probe=48f334b6ed) | Jul 19, 2024 |
| ASRock        | X300M-STX                   | [724187bcd6](https://linux-hardware.org/?probe=724187bcd6) | Jul 13, 2024 |
| SZQFTX        | MI2-SC                      | [c95dd74d91](https://linux-hardware.org/?probe=c95dd74d91) | Jul 07, 2024 |
| ASUSTek       | H310M-C/HDMI R2.0           | [8767868edd](https://linux-hardware.org/?probe=8767868edd) | Jun 25, 2024 |
| Gigabyte      | F2A88X-UP4                  | [0c0aa2515c](https://linux-hardware.org/?probe=0c0aa2515c) | Jun 18, 2024 |
| Gigabyte      | F2A88X-UP4                  | [385923ca25](https://linux-hardware.org/?probe=385923ca25) | Jun 10, 2024 |
| ASUSTek       | ROG Maximus Z790 FORMULA    | [99d8c9e8b1](https://linux-hardware.org/?probe=99d8c9e8b1) | Jun 02, 2024 |
| ASUSTek       | Z10PE-D16 Series            | [52a0a645ba](https://linux-hardware.org/?probe=52a0a645ba) | May 27, 2024 |
| Shuttle       | FH170                       | [0a04e61b00](https://linux-hardware.org/?probe=0a04e61b00) | May 23, 2024 |
| Shuttle       | FH170                       | [5103536dc4](https://linux-hardware.org/?probe=5103536dc4) | May 18, 2024 |
| ASUSTek       | H110M-A                     | [16c08bf32a](https://linux-hardware.org/?probe=16c08bf32a) | May 14, 2024 |
| Gigabyte      | H110M-DS2V-CF               | [40fe788bf0](https://linux-hardware.org/?probe=40fe788bf0) | Apr 14, 2024 |
| SZQFTX        | MI2-SC                      | [be8172007e](https://linux-hardware.org/?probe=be8172007e) | Apr 11, 2024 |
| ASRock        | B150M Pro4                  | [75a5d3af57](https://linux-hardware.org/?probe=75a5d3af57) | Apr 06, 2024 |
| Gigabyte      | H81M-D2V                    | [6bc3e596e6](https://linux-hardware.org/?probe=6bc3e596e6) | Mar 28, 2024 |
| SZQFTX        | MI2-SC                      | [4364c74d90](https://linux-hardware.org/?probe=4364c74d90) | Mar 26, 2024 |
| ASUSTek       | H110M-A                     | [fc2fe23179](https://linux-hardware.org/?probe=fc2fe23179) | Mar 22, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [d63edacb71](https://linux-hardware.org/?probe=d63edacb71) | Mar 15, 2024 |
| Google        | Panther                     | [9fee846e7c](https://linux-hardware.org/?probe=9fee846e7c) | Mar 09, 2024 |
| Google        | Panther                     | [9b94bb7555](https://linux-hardware.org/?probe=9b94bb7555) | Mar 09, 2024 |
| INRUKO        | HM87S V2.5                  | [b422e4c8ab](https://linux-hardware.org/?probe=b422e4c8ab) | Mar 06, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [7bc1964f22](https://linux-hardware.org/?probe=7bc1964f22) | Feb 24, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [f537e67907](https://linux-hardware.org/?probe=f537e67907) | Feb 23, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [225c50ba01](https://linux-hardware.org/?probe=225c50ba01) | Feb 22, 2024 |
| Unknown       | Unknown                     | [13504f6300](https://linux-hardware.org/?probe=13504f6300) | Feb 20, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [4fb324edd0](https://linux-hardware.org/?probe=4fb324edd0) | Feb 19, 2024 |
| Unknown       | Unknown                     | [d4ffec2f30](https://linux-hardware.org/?probe=d4ffec2f30) | Feb 15, 2024 |
| MSI           | B450M MORTAR MAX            | [7d93273d71](https://linux-hardware.org/?probe=7d93273d71) | Feb 08, 2024 |
| ASUSTek       | PRIME A520M-K               | [7baccc479c](https://linux-hardware.org/?probe=7baccc479c) | Dec 31, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [cb215ce5f6](https://linux-hardware.org/?probe=cb215ce5f6) | Dec 28, 2023 |
| AZW           | SER V1                      | [9491b3dfb6](https://linux-hardware.org/?probe=9491b3dfb6) | Dec 28, 2023 |
| HP            | 212B                        | [8fa44a703b](https://linux-hardware.org/?probe=8fa44a703b) | Dec 22, 2023 |
| Gigabyte      | X670 GAMING X AX            | [18d321d9d6](https://linux-hardware.org/?probe=18d321d9d6) | Dec 06, 2023 |
| Unknown       | G-GLK01                     | [5c5efbafff](https://linux-hardware.org/?probe=5c5efbafff) | Dec 06, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [360f0c3419](https://linux-hardware.org/?probe=360f0c3419) | Nov 26, 2023 |
| MSI           | B450M MORTAR MAX            | [44bd871680](https://linux-hardware.org/?probe=44bd871680) | Nov 25, 2023 |
| Unknown       | Unknown                     | [de44cb2821](https://linux-hardware.org/?probe=de44cb2821) | Nov 23, 2023 |
| ASUSTek       | H110M-A                     | [79a1012336](https://linux-hardware.org/?probe=79a1012336) | Nov 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [4f49f31e87](https://linux-hardware.org/?probe=4f49f31e87) | Nov 11, 2023 |
| ASUSTek       | PRIME A520M-K               | [8e450b21e1](https://linux-hardware.org/?probe=8e450b21e1) | Nov 10, 2023 |
| ASUSTek       | PRIME A520M-K               | [907a7f6dd8](https://linux-hardware.org/?probe=907a7f6dd8) | Nov 05, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [8f09f37e41](https://linux-hardware.org/?probe=8f09f37e41) | Oct 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [feee3cfca0](https://linux-hardware.org/?probe=feee3cfca0) | Oct 20, 2023 |
| Unknown       | Unknown                     | [23768d9009](https://linux-hardware.org/?probe=23768d9009) | Oct 15, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [3d6223857b](https://linux-hardware.org/?probe=3d6223857b) | Oct 14, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [bf515bb1b4](https://linux-hardware.org/?probe=bf515bb1b4) | Oct 12, 2023 |
| Gigabyte      | H61M-S2PV                   | [691c015f6f](https://linux-hardware.org/?probe=691c015f6f) | Oct 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | [a8bea5ed82](https://linux-hardware.org/?probe=a8bea5ed82) | Sep 30, 2023 |
| HP            | 8906 SMVB                   | [55c34c64a6](https://linux-hardware.org/?probe=55c34c64a6) | Sep 27, 2023 |
| ASRock        | H81M-DG6                    | [ac6944c3df](https://linux-hardware.org/?probe=ac6944c3df) | Sep 25, 2023 |
| Unknown       | Unknown                     | [aa67f256bc](https://linux-hardware.org/?probe=aa67f256bc) | Sep 09, 2023 |
| ASRock        | B550M Steel Legend          | [ecd59bd254](https://linux-hardware.org/?probe=ecd59bd254) | Sep 08, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [da16406c15](https://linux-hardware.org/?probe=da16406c15) | Sep 01, 2023 |
| Unknown       | Unknown                     | [269a4ac17d](https://linux-hardware.org/?probe=269a4ac17d) | Aug 28, 2023 |
| Gigabyte      | B75M-D3H                    | [215ff35620](https://linux-hardware.org/?probe=215ff35620) | Aug 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [2bb217b4df](https://linux-hardware.org/?probe=2bb217b4df) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [b9701cd43c](https://linux-hardware.org/?probe=b9701cd43c) | Aug 20, 2023 |
| Unknown       | Unknown                     | [a9f30f8dd0](https://linux-hardware.org/?probe=a9f30f8dd0) | Aug 11, 2023 |
| Gigabyte      | TRX40 DESIGNARE             | [a71dc0067b](https://linux-hardware.org/?probe=a71dc0067b) | Aug 07, 2023 |
| ASUSTek       | Z170-A                      | [87a26e01e6](https://linux-hardware.org/?probe=87a26e01e6) | Jul 06, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [669754af36](https://linux-hardware.org/?probe=669754af36) | Jul 02, 2023 |
| Gigabyte      | A620M GAMING X              | [76238267ab](https://linux-hardware.org/?probe=76238267ab) | Jul 01, 2023 |
| ASUSTek       | PRIME A520M-K               | [2fe8080014](https://linux-hardware.org/?probe=2fe8080014) | Jun 11, 2023 |
| ASRock        | B150M Pro4                  | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| ASRock        | X670E Taichi                | [6616151cda](https://linux-hardware.org/?probe=6616151cda) | Jun 04, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [f4fce509ae](https://linux-hardware.org/?probe=f4fce509ae) | May 18, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [abb92fef7d](https://linux-hardware.org/?probe=abb92fef7d) | May 06, 2023 |
| MSI           | B450 TOMAHAWK               | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| ASRock        | Z370 Extreme4               | [0f126ade53](https://linux-hardware.org/?probe=0f126ade53) | Apr 29, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [dca43563dd](https://linux-hardware.org/?probe=dca43563dd) | Apr 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | [bab80153bf](https://linux-hardware.org/?probe=bab80153bf) | Apr 22, 2023 |
| Dell          | 0MR5MV A00                  | [ed13b58a51](https://linux-hardware.org/?probe=ed13b58a51) | Apr 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [30fdc58d69](https://linux-hardware.org/?probe=30fdc58d69) | Apr 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [dfd9900ccf](https://linux-hardware.org/?probe=dfd9900ccf) | Mar 30, 2023 |
| MSI           | B450M MORTAR                | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [fa7272f576](https://linux-hardware.org/?probe=fa7272f576) | Mar 27, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | [19a060d86d](https://linux-hardware.org/?probe=19a060d86d) | Mar 20, 2023 |
| ECS2          | EASTWOOD2 V1.0              | [822e4fa621](https://linux-hardware.org/?probe=822e4fa621) | Mar 11, 2023 |
| Dell          | 0TNXNR A01                  | [30fa0c9cb7](https://linux-hardware.org/?probe=30fa0c9cb7) | Mar 09, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [484e0755de](https://linux-hardware.org/?probe=484e0755de) | Feb 26, 2023 |
| ASUSTek       | P8H67-M                     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Samsung       | DB400T7Y-Z202C SGL9325A0... | [b75c596e7f](https://linux-hardware.org/?probe=b75c596e7f) | Feb 21, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | [5b452754c0](https://linux-hardware.org/?probe=5b452754c0) | Feb 19, 2023 |
| ASRock        | Z370 Pro4                   | [bafba5486b](https://linux-hardware.org/?probe=bafba5486b) | Feb 16, 2023 |
| ASRock        | Z790 Pro RS WiFi            | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [b9fb1c5111](https://linux-hardware.org/?probe=b9fb1c5111) | Feb 01, 2023 |
| ASUSTek       | GA35DX                      | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [bb5e9ccd98](https://linux-hardware.org/?probe=bb5e9ccd98) | Jan 27, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [d54e25d6fb](https://linux-hardware.org/?probe=d54e25d6fb) | Jan 27, 2023 |
| ASRock        | B560M Pro4                  | [6c8d492f56](https://linux-hardware.org/?probe=6c8d492f56) | Jan 19, 2023 |
| ASUSTek       | H110M-K                     | [8975ee2ce6](https://linux-hardware.org/?probe=8975ee2ce6) | Jan 14, 2023 |
| Unknown       | Unknown                     | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                     | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| ELSKY         | M219FN-6C                   | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eda96539d7](https://linux-hardware.org/?probe=eda96539d7) | Dec 26, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | [7020686bc7](https://linux-hardware.org/?probe=7020686bc7) | Dec 19, 2022 |
| Huanan        | X58-RX3.0 V110              | [32e6a4d219](https://linux-hardware.org/?probe=32e6a4d219) | Dec 10, 2022 |
| Lenovo        | 370A NOK                    | [b06728a8bf](https://linux-hardware.org/?probe=b06728a8bf) | Dec 05, 2022 |
| Dell          | 00D7V6 A00                  | [6047fbcb06](https://linux-hardware.org/?probe=6047fbcb06) | Dec 05, 2022 |
| Dell          | 00D7V6 A00                  | [9aebb424cc](https://linux-hardware.org/?probe=9aebb424cc) | Dec 05, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | [6d4f229020](https://linux-hardware.org/?probe=6d4f229020) | Nov 29, 2022 |
| Gigabyte      | 990FXA-UD3                  | [d5c76baafa](https://linux-hardware.org/?probe=d5c76baafa) | Nov 18, 2022 |
| ASUSTek       | P8H67                       | [0ccbbf67e8](https://linux-hardware.org/?probe=0ccbbf67e8) | Nov 10, 2022 |
| ASUSTek       | PRIME B365M-K               | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| WTM           | W-N95 B0                    | [56611d3c8f](https://linux-hardware.org/?probe=56611d3c8f) | Oct 31, 2022 |
| HP            | 8425                        | [6d26af6597](https://linux-hardware.org/?probe=6d26af6597) | Oct 27, 2022 |
| Gigabyte      | B360M D3H-CF                | [ad1d808caa](https://linux-hardware.org/?probe=ad1d808caa) | Oct 14, 2022 |
| MSI           | A320M-A PRO                 | [40dd630e96](https://linux-hardware.org/?probe=40dd630e96) | Oct 05, 2022 |
| ASUSTek       | PRIME B550M-K               | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| Gigabyte      | MZBAYAP-00                  | [2fccc9ec66](https://linux-hardware.org/?probe=2fccc9ec66) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD3                  | [5c2eac6d83](https://linux-hardware.org/?probe=5c2eac6d83) | Sep 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | [ea7d5b0424](https://linux-hardware.org/?probe=ea7d5b0424) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [156da35e98](https://linux-hardware.org/?probe=156da35e98) | Aug 24, 2022 |
| MSI           | MAG B660M MORTAR WIFI       | [4e1b75908c](https://linux-hardware.org/?probe=4e1b75908c) | Aug 13, 2022 |
| HP            | 8906 SMVB                   | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASRock        | B250M Pro4                  | [59704c823a](https://linux-hardware.org/?probe=59704c823a) | Jul 29, 2022 |
| PCPartner     | MILANO-P Rev.00             | [1b6d72c5ac](https://linux-hardware.org/?probe=1b6d72c5ac) | Jul 18, 2022 |
| Gigabyte      | A320M-H-CF                  | [5bdae5b8f7](https://linux-hardware.org/?probe=5bdae5b8f7) | Jul 18, 2022 |
| HP            | 8906 SMVB                   | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| ASUSTek       | P8H67                       | [8971b67abc](https://linux-hardware.org/?probe=8971b67abc) | Jul 08, 2022 |
| Gigabyte      | B360M D3H-CF                | [251bc4d58d](https://linux-hardware.org/?probe=251bc4d58d) | Jul 04, 2022 |
| Gigabyte      | MQLP5AP-00                  | [8014a14842](https://linux-hardware.org/?probe=8014a14842) | Jun 30, 2022 |
| Gigabyte      | TRX40 AORUS XTREME          | [2d23125cd0](https://linux-hardware.org/?probe=2d23125cd0) | May 15, 2022 |
| Gigabyte      | X99-SLI-CF                  | [55f1cc4480](https://linux-hardware.org/?probe=55f1cc4480) | May 10, 2022 |
| Alienware     | 0CPDXD A00                  | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| MSI           | H110M PRO-VD PLUS           | [80bdc044eb](https://linux-hardware.org/?probe=80bdc044eb) | May 01, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [9a15614b1e](https://linux-hardware.org/?probe=9a15614b1e) | Apr 13, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [90aa422ea2](https://linux-hardware.org/?probe=90aa422ea2) | Mar 31, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [fa4526e9f3](https://linux-hardware.org/?probe=fa4526e9f3) | Mar 24, 2022 |
| ASUSTek       | P8H67                       | [05cdb119e9](https://linux-hardware.org/?probe=05cdb119e9) | Mar 07, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [14f8855baa](https://linux-hardware.org/?probe=14f8855baa) | Feb 03, 2022 |
| ASUSTek       | PRIME B350M-A               | [7843ddc3fb](https://linux-hardware.org/?probe=7843ddc3fb) | Dec 24, 2021 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [151434ab61](https://linux-hardware.org/?probe=151434ab61) | Dec 21, 2021 |
| Lenovo        | 1036 SDK0T76457 WIN 3915... | [f894442edc](https://linux-hardware.org/?probe=f894442edc) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [4d11bd6b59](https://linux-hardware.org/?probe=4d11bd6b59) | Nov 20, 2021 |
| ASUSTek       | PRIME B350M-A               | [19eba77c24](https://linux-hardware.org/?probe=19eba77c24) | Oct 25, 2021 |
| ASRock        | M3A770DE                    | [4d966dec54](https://linux-hardware.org/?probe=4d966dec54) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | [de6577e71a](https://linux-hardware.org/?probe=de6577e71a) | Oct 03, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [23cf6f38e8](https://linux-hardware.org/?probe=23cf6f38e8) | Sep 21, 2021 |
| ASRock        | AB350M Pro4                 | [24de612862](https://linux-hardware.org/?probe=24de612862) | Aug 31, 2021 |
| ASUSTek       | Z170-A                      | [3abd60af90](https://linux-hardware.org/?probe=3abd60af90) | Aug 22, 2021 |
| ASUSTek       | Z170-A                      | [e523ad86d2](https://linux-hardware.org/?probe=e523ad86d2) | Aug 02, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | [1e96b02bf3](https://linux-hardware.org/?probe=1e96b02bf3) | Jul 28, 2021 |
| ASUSTek       | P5QL/EPU                    | [972c061d3c](https://linux-hardware.org/?probe=972c061d3c) | Jul 22, 2021 |
| Gigabyte      | Z390 D                      | [8bf86066a5](https://linux-hardware.org/?probe=8bf86066a5) | Jul 22, 2021 |
| HP            | 3397                        | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| ASRockRack    | WC621D8A-2T                 | [d9c47162dc](https://linux-hardware.org/?probe=d9c47162dc) | Jun 25, 2021 |
| ASRockRack    | WC621D8A-2T                 | [b568edaa5e](https://linux-hardware.org/?probe=b568edaa5e) | Jun 25, 2021 |
| Gigabyte      | B75M-D3V                    | [9aaad9b2d4](https://linux-hardware.org/?probe=9aaad9b2d4) | Jun 07, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | [be07a70b2e](https://linux-hardware.org/?probe=be07a70b2e) | May 27, 2021 |
| ASUSTek       | P5QL/EPU                    | [965bc51c8d](https://linux-hardware.org/?probe=965bc51c8d) | May 06, 2021 |
| ASRock        | A75M-ITX                    | [1ad3e30eec](https://linux-hardware.org/?probe=1ad3e30eec) | May 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | [72d14b2ed7](https://linux-hardware.org/?probe=72d14b2ed7) | Apr 23, 2021 |
| Gigabyte      | A320M-S2H-CF                | [2300013263](https://linux-hardware.org/?probe=2300013263) | Apr 18, 2021 |
| ASRock        | FM2A88M-HD+ R2.0            | [fdac2fa1fd](https://linux-hardware.org/?probe=fdac2fa1fd) | Apr 14, 2021 |
| ASUSTek       | P8H67                       | [b17bb9b31a](https://linux-hardware.org/?probe=b17bb9b31a) | Apr 12, 2021 |
| ASRock        | AB350 Pro4                  | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| Gigabyte      | 945GCMX-S2                  | [d4399ab9d0](https://linux-hardware.org/?probe=d4399ab9d0) | Apr 06, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [b55dc75624](https://linux-hardware.org/?probe=b55dc75624) | Mar 20, 2021 |
| Gigabyte      | B360M DS3H                  | [f7740321e0](https://linux-hardware.org/?probe=f7740321e0) | Mar 18, 2021 |
| MSI           | B75MA-E33                   | [e459ded47c](https://linux-hardware.org/?probe=e459ded47c) | Mar 10, 2021 |
| ASUSTek       | PRIME Z490-A                | [15c42588c8](https://linux-hardware.org/?probe=15c42588c8) | Mar 04, 2021 |
| ASUSTek       | WS X299 SAGE                | [541a436664](https://linux-hardware.org/?probe=541a436664) | Mar 02, 2021 |
| ASRock        | H110M-HDVP2                 | [8e6128682d](https://linux-hardware.org/?probe=8e6128682d) | Feb 28, 2021 |
| ASRock        | H110M-HDVP2                 | [778fcc3093](https://linux-hardware.org/?probe=778fcc3093) | Feb 28, 2021 |
| Gigabyte      | B75M-D3H                    | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [8dd1ebdfb8](https://linux-hardware.org/?probe=8dd1ebdfb8) | Feb 25, 2021 |
| MSI           | B450M MORTAR MAX            | [a222f11ebf](https://linux-hardware.org/?probe=a222f11ebf) | Feb 09, 2021 |
| ASUSTek       | PRIME B350M-A               | [0de61d3d11](https://linux-hardware.org/?probe=0de61d3d11) | Feb 06, 2021 |
| ASUSTek       | Z170-A                      | [65aa2efd23](https://linux-hardware.org/?probe=65aa2efd23) | Feb 05, 2021 |
| ASRock        | H110M-HDVP2                 | [27d324f7e1](https://linux-hardware.org/?probe=27d324f7e1) | Feb 04, 2021 |
| MSI           | B360M PRO-VDH               | [59b7bd58df](https://linux-hardware.org/?probe=59b7bd58df) | Jan 30, 2021 |
| MSI           | Z490-A PRO                  | [a29449d114](https://linux-hardware.org/?probe=a29449d114) | Jan 27, 2021 |
| MSI           | Z490-A PRO                  | [9595d4107b](https://linux-hardware.org/?probe=9595d4107b) | Jan 26, 2021 |
| ASRock        | B450M Steel Legend          | [a6226b7401](https://linux-hardware.org/?probe=a6226b7401) | Jan 20, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [ffa2d06213](https://linux-hardware.org/?probe=ffa2d06213) | Jan 05, 2021 |
| HP            | 18E7                        | [e9590ba71a](https://linux-hardware.org/?probe=e9590ba71a) | Jan 01, 2021 |
| ASUSTek       | PRIME B250M-A               | [77ad294d93](https://linux-hardware.org/?probe=77ad294d93) | Dec 20, 2020 |
| MSI           | B360M PRO-VDH               | [ae9a14bb34](https://linux-hardware.org/?probe=ae9a14bb34) | Dec 11, 2020 |
| ASUSTek       | PRIME B250M-PLUS            | [b1476b4c51](https://linux-hardware.org/?probe=b1476b4c51) | Dec 09, 2020 |
| ASRock        | H81M-DGS R2.0               | [a706242b44](https://linux-hardware.org/?probe=a706242b44) | Dec 05, 2020 |
| MSI           | B360M PRO-VDH               | [f16f5d30de](https://linux-hardware.org/?probe=f16f5d30de) | Dec 05, 2020 |
| ASUSTek       | PRIME B250M-A               | [425fda9034](https://linux-hardware.org/?probe=425fda9034) | Dec 04, 2020 |
| ASUSTek       | P8B75-M LX PLUS             | [e6f9b2cf07](https://linux-hardware.org/?probe=e6f9b2cf07) | Dec 04, 2020 |
| ASRock        | B85M Pro4                   | [0354f4d9bc](https://linux-hardware.org/?probe=0354f4d9bc) | Nov 25, 2020 |
| ASRock        | B85M Pro4                   | [8dcc7ce213](https://linux-hardware.org/?probe=8dcc7ce213) | Nov 22, 2020 |
| Gigabyte      | H97M-D3H                    | [f9b97f5918](https://linux-hardware.org/?probe=f9b97f5918) | Nov 22, 2020 |
| ECS           | G31T-M7                     | [f93ce4415e](https://linux-hardware.org/?probe=f93ce4415e) | Nov 12, 2020 |
| PC Partner... | A236 0A                     | [14030da2e5](https://linux-hardware.org/?probe=14030da2e5) | Nov 10, 2020 |
| PC Partner... | A236 0A                     | [fc118d784c](https://linux-hardware.org/?probe=fc118d784c) | Nov 10, 2020 |
| ASUSTek       | P7P55D                      | [11e315efbd](https://linux-hardware.org/?probe=11e315efbd) | Nov 07, 2020 |
| ASRock        | H81M-DGS R2.0               | [9b33944102](https://linux-hardware.org/?probe=9b33944102) | Nov 04, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [39cc53a5e3](https://linux-hardware.org/?probe=39cc53a5e3) | Oct 13, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [3aba059c2c](https://linux-hardware.org/?probe=3aba059c2c) | Sep 24, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [c535500f86](https://linux-hardware.org/?probe=c535500f86) | Sep 24, 2020 |
| ASRock        | H310M-STX/COM               | [5b22b538ee](https://linux-hardware.org/?probe=5b22b538ee) | Sep 23, 2020 |
| ASUSTek       | P5LD2                       | [56efa94b22](https://linux-hardware.org/?probe=56efa94b22) | Sep 09, 2020 |
| ASUSTek       | P5LD2                       | [00f5eba2ea](https://linux-hardware.org/?probe=00f5eba2ea) | Sep 09, 2020 |
| Gigabyte      | B75M-D3H                    | [934bb9c2ef](https://linux-hardware.org/?probe=934bb9c2ef) | Sep 09, 2020 |
| ASRock        | H310CM-HDV                  | [7acf41575b](https://linux-hardware.org/?probe=7acf41575b) | Sep 09, 2020 |
| ASRock        | H81M-HDS                    | [8b55873fbd](https://linux-hardware.org/?probe=8b55873fbd) | Sep 07, 2020 |
| Foxconn       | H61MXE                      | [7a31014e98](https://linux-hardware.org/?probe=7a31014e98) | Sep 04, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| Lenovo        | ThinkServer TS140           | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| ASRock        | H61M-HVGS                   | [36c19012ed](https://linux-hardware.org/?probe=36c19012ed) | Jul 25, 2020 |
| ASRock        | H61M-HVGS                   | [ea9287adc1](https://linux-hardware.org/?probe=ea9287adc1) | Jul 25, 2020 |
| ASRock        | Z390 Taichi                 | [ce94a11d8b](https://linux-hardware.org/?probe=ce94a11d8b) | Jun 26, 2020 |
| Huanan        | X99-F8                      | [74f9976527](https://linux-hardware.org/?probe=74f9976527) | Jun 25, 2020 |
| Gigabyte      | X570 GAMING X               | [cbd4390e56](https://linux-hardware.org/?probe=cbd4390e56) | Jun 23, 2020 |
| ASRock        | Z390 Taichi                 | [6989759d9c](https://linux-hardware.org/?probe=6989759d9c) | Jun 21, 2020 |
| ASRock        | Z390M Pro4                  | [eb53bb80ea](https://linux-hardware.org/?probe=eb53bb80ea) | Jun 20, 2020 |
| ECS           | H81H3-MV                    | [d39e7a605d](https://linux-hardware.org/?probe=d39e7a605d) | Jun 20, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [c05f965fec](https://linux-hardware.org/?probe=c05f965fec) | Jun 17, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [835aa152dd](https://linux-hardware.org/?probe=835aa152dd) | Jun 16, 2020 |
| Unknown       | Unknown                     | [e6e0a356a2](https://linux-hardware.org/?probe=e6e0a356a2) | May 19, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [e526204afd](https://linux-hardware.org/?probe=e526204afd) | May 16, 2020 |
| ASUSTek       | P5B-Deluxe                  | [24ce1a41e9](https://linux-hardware.org/?probe=24ce1a41e9) | May 16, 2020 |
| HP            | 158A                        | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [d5b8f91a79](https://linux-hardware.org/?probe=d5b8f91a79) | May 10, 2020 |
| Gigabyte      | B150M-D3H-CF                | [c259824b35](https://linux-hardware.org/?probe=c259824b35) | May 09, 2020 |
| ASRock        | X470 Taichi                 | [261241bb2f](https://linux-hardware.org/?probe=261241bb2f) | May 07, 2020 |
| Biostar       | H61MH                       | [aacc6bcb68](https://linux-hardware.org/?probe=aacc6bcb68) | May 07, 2020 |
| Gigabyte      | H81M-DS2V                   | [36cbf906a0](https://linux-hardware.org/?probe=36cbf906a0) | May 07, 2020 |
| Gigabyte      | B75M-D3V                    | [a4130d0549](https://linux-hardware.org/?probe=a4130d0549) | Apr 29, 2020 |
| ASRock        | G31M-S                      | [6a55997759](https://linux-hardware.org/?probe=6a55997759) | Apr 28, 2020 |
| ASUSTek       | B85M-G                      | [5d58ef4cec](https://linux-hardware.org/?probe=5d58ef4cec) | Apr 19, 2020 |
| ASUSTek       | Rampage V EXTREME           | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| MSI           | B250M PRO-VD                | [d797379451](https://linux-hardware.org/?probe=d797379451) | Apr 13, 2020 |
| Gigabyte      | TRX40 AORUS XTREME          | [0f078bd16f](https://linux-hardware.org/?probe=0f078bd16f) | Apr 11, 2020 |
| Dell          | 0Y2MRG A01                  | [053b33bcbc](https://linux-hardware.org/?probe=053b33bcbc) | Apr 05, 2020 |
| ASUSTek       | P5K                         | [8ec1f94a9f](https://linux-hardware.org/?probe=8ec1f94a9f) | Apr 05, 2020 |
| ASUSTek       | H110M-F                     | [c5861fb518](https://linux-hardware.org/?probe=c5861fb518) | Mar 31, 2020 |
| ASUSTek       | PRIME A320M-K               | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [c54c1dcc2f](https://linux-hardware.org/?probe=c54c1dcc2f) | Mar 18, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [de7d898371](https://linux-hardware.org/?probe=de7d898371) | Mar 16, 2020 |
| ASRock        | FM2A88M-HD+ R3.0            | [b5def2acfb](https://linux-hardware.org/?probe=b5def2acfb) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | [ca363a8ddc](https://linux-hardware.org/?probe=ca363a8ddc) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | [2b56d27ead](https://linux-hardware.org/?probe=2b56d27ead) | Mar 02, 2020 |
| ECS           | H61H2-MV                    | [8b42886c6f](https://linux-hardware.org/?probe=8b42886c6f) | Mar 02, 2020 |
| ASUSTek       | P8H61-MX R2.0               | [fd4e08618e](https://linux-hardware.org/?probe=fd4e08618e) | Feb 28, 2020 |
| MSI           | B350M MORTAR                | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| LattePanda    | Alpha                       | [eb27db2005](https://linux-hardware.org/?probe=eb27db2005) | Feb 01, 2020 |
| LattePanda    | Alpha                       | [72a1cd44a0](https://linux-hardware.org/?probe=72a1cd44a0) | Feb 01, 2020 |
| MSI           | B350M MORTAR                | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P5B-PLUS Series             | [b0a90d8478](https://linux-hardware.org/?probe=b0a90d8478) | Jan 02, 2020 |
| ASUSTek       | PRIME A320M-K               | [2fb35125e3](https://linux-hardware.org/?probe=2fb35125e3) | Dec 22, 2019 |
| Gigabyte      | 945GM-S2                    | [c6b23ec021](https://linux-hardware.org/?probe=c6b23ec021) | Dec 07, 2019 |
| ECS           | H81H3-M4                    | [2a11653db0](https://linux-hardware.org/?probe=2a11653db0) | Oct 05, 2019 |
| ASUSTek       | PRIME H310M-R R2.0          | [37c348afcc](https://linux-hardware.org/?probe=37c348afcc) | Sep 11, 2019 |
| ECS           | G41T-M6                     | [91cafa3b5b](https://linux-hardware.org/?probe=91cafa3b5b) | Aug 30, 2019 |
| Gigabyte      | H81M-DS2V                   | [68069aeff1](https://linux-hardware.org/?probe=68069aeff1) | Aug 21, 2019 |
| ASRock        | Z390 Extreme4               | [8c8af8b557](https://linux-hardware.org/?probe=8c8af8b557) | Jul 13, 2019 |
| ASRock        | AB350M Pro4                 | [88354e515f](https://linux-hardware.org/?probe=88354e515f) | Jul 08, 2019 |
| ASRock        | AB350M Pro4                 | [7506cb2993](https://linux-hardware.org/?probe=7506cb2993) | Jul 08, 2019 |
| Gigabyte      | GA-MA790FX-DS5              | [727b2b7099](https://linux-hardware.org/?probe=727b2b7099) | Jun 27, 2019 |
| AMD           | R690A-M2T                   | [da36474b90](https://linux-hardware.org/?probe=da36474b90) | Jun 18, 2019 |
| Gigabyte      | AB350M-DS2-CF               | [553908ddb3](https://linux-hardware.org/?probe=553908ddb3) | Jun 09, 2019 |
| ASUSTek       | PRIME X399-A                | [ae94045380](https://linux-hardware.org/?probe=ae94045380) | May 29, 2019 |
| Lenovo        | NO DPK                      | [b89b8c9364](https://linux-hardware.org/?probe=b89b8c9364) | May 27, 2019 |
| ASRock        | H61M-DGS                    | [6dc8ccd0f6](https://linux-hardware.org/?probe=6dc8ccd0f6) | May 08, 2019 |
| Foxconn       | P35A01                      | [f2685edfa8](https://linux-hardware.org/?probe=f2685edfa8) | Apr 21, 2019 |
| ASUSTek       | Z170-A                      | [322d76fe62](https://linux-hardware.org/?probe=322d76fe62) | Apr 04, 2019 |
| ASUSTek       | Z170-A                      | [0fa2f9b10a](https://linux-hardware.org/?probe=0fa2f9b10a) | Apr 04, 2019 |
| ASUSTek       | PRIME B450M-A               | [45f363040f](https://linux-hardware.org/?probe=45f363040f) | Mar 30, 2019 |
| ASRock        | P55 Pro                     | [041e899a1b](https://linux-hardware.org/?probe=041e899a1b) | Jan 15, 2019 |
| Gigabyte      | H55M-S2V                    | [36d1703d67](https://linux-hardware.org/?probe=36d1703d67) | Dec 23, 2018 |
| LattePanda    | Alpha                       | [287f0d8110](https://linux-hardware.org/?probe=287f0d8110) | Nov 27, 2018 |
| LattePanda    | Alpha                       | [37c9db1d31](https://linux-hardware.org/?probe=37c9db1d31) | Nov 27, 2018 |
| Gigabyte      | P55-US3L                    | [e216d60f26](https://linux-hardware.org/?probe=e216d60f26) | Sep 19, 2018 |
| Gigabyte      | B75M-D3H                    | [08f9437e06](https://linux-hardware.org/?probe=08f9437e06) | Jul 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | [16f456428f](https://linux-hardware.org/?probe=16f456428f) | May 10, 2018 |
| ECS           | A55F2-M3                    | [e4af897158](https://linux-hardware.org/?probe=e4af897158) | May 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | [f3036847e4](https://linux-hardware.org/?probe=f3036847e4) | May 10, 2018 |
| ECS           | A55F2-M3                    | [eb58cea516](https://linux-hardware.org/?probe=eb58cea516) | May 10, 2018 |
| ASRock        | G41M-VS3                    | [18d59d7ea8](https://linux-hardware.org/?probe=18d59d7ea8) | Apr 13, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 42       | 17.43%  |
| Ubuntu 22.04                 | 27       | 11.2%   |
| Ubuntu 18.04                 | 21       | 8.71%   |
| HamoniKR 7.0                 | 5        | 2.07%   |
| Ubuntu 20.10                 | 4        | 1.66%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.66%   |
| Fedora 39                    | 4        | 1.66%   |
| Debian 12                    | 4        | 1.66%   |
| ArcoLinux Rolling            | 4        | 1.66%   |
| Arch Rolling                 | 4        | 1.66%   |
| Arch                         | 4        | 1.66%   |
| Ubuntu 19.10                 | 3        | 1.24%   |
| Ubuntu 16.04                 | 3        | 1.24%   |
| Pop!_OS 22.04                | 3        | 1.24%   |
| Fedora 40                    | 3        | 1.24%   |
| Fedora 37                    | 3        | 1.24%   |
| Fedora 32                    | 3        | 1.24%   |
| CentOS 7                     | 3        | 1.24%   |
| Zorin 15                     | 2        | 0.83%   |
| Ubuntu Unity 16.04           | 2        | 0.83%   |
| Ubuntu 24.04                 | 2        | 0.83%   |
| Ubuntu 23.10                 | 2        | 0.83%   |
| Ubuntu 23.04                 | 2        | 0.83%   |
| Ubuntu 21.10                 | 2        | 0.83%   |
| TmaxOS 21.12.02              | 2        | 0.83%   |
| RHEL 8                       | 2        | 0.83%   |
| OpenMandriva 5.0             | 2        | 0.83%   |
| OpenMandriva 4.3             | 2        | 0.83%   |
| OpenMandriva 23.03           | 2        | 0.83%   |
| OpenMandriva 23.01           | 2        | 0.83%   |
| No1 2018                     | 2        | 0.83%   |
| Linux Mint 21.1              | 2        | 0.83%   |
| Linux Mint 20.2              | 2        | 0.83%   |
| Linux Mint 20.1              | 2        | 0.83%   |
| Linux Mint 20                | 2        | 0.83%   |
| Linux Mint 19.3              | 2        | 0.83%   |
| HamoniKR 6.0                 | 2        | 0.83%   |
| Fedora 36                    | 2        | 0.83%   |
| Fedora 34                    | 2        | 0.83%   |
| Debian 11                    | 2        | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 111      | 47.44%  |
| Fedora           | 19       | 8.12%   |
| Linux Mint       | 11       | 4.7%    |
| HamoniKR         | 10       | 4.27%   |
| OpenMandriva     | 9        | 3.85%   |
| Debian           | 9        | 3.85%   |
| Arch             | 8        | 3.42%   |
| openSUSE         | 5        | 2.14%   |
| Zorin            | 4        | 1.71%   |
| Rocky Linux      | 4        | 1.71%   |
| Pop!_OS          | 4        | 1.71%   |
| CentOS           | 4        | 1.71%   |
| ArcoLinux        | 4        | 1.71%   |
| No1 Linux        | 3        | 1.28%   |
| Manjaro          | 3        | 1.28%   |
| Kubuntu          | 3        | 1.28%   |
| Ubuntu Unity     | 2        | 0.85%   |
| TmaxOS           | 2        | 0.85%   |
| ROSA             | 2        | 0.85%   |
| RHEL             | 2        | 0.85%   |
| Chrome OS        | 2        | 0.85%   |
| org.kde.Platform | 1        | 0.43%   |
| Nobara           | 1        | 0.43%   |
| MX               | 1        | 0.43%   |
| Lubuntu          | 1        | 0.43%   |
| KDE neon         | 1        | 0.43%   |
| Kali             | 1        | 0.43%   |
| Gooroom          | 1        | 0.43%   |
| Endless          | 1        | 0.43%   |
| EndeavourOS      | 1        | 0.43%   |
| Devuan           | 1        | 0.43%   |
| ChimeraOS        | 1        | 0.43%   |
| BlackPanther     | 1        | 0.43%   |
| AlmaLinux        | 1        | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.4.0-29-generic        | 4        | 1.51%   |
| 5.15.0-43-generic       | 4        | 1.51%   |
| 6.5.6-300.fc39.x86_64   | 3        | 1.13%   |
| 6.5.0-35-generic        | 3        | 1.13%   |
| 5.4.0-26-generic        | 3        | 1.13%   |
| 5.19.0-38-generic       | 3        | 1.13%   |
| 5.15.0-71-generic       | 3        | 1.13%   |
| 5.15.0-41-generic       | 3        | 1.13%   |
| 6.8.0-49-generic        | 2        | 0.75%   |
| 6.8.0-48-generic        | 2        | 0.75%   |
| 6.6.2-desktop-1omv2390  | 2        | 0.75%   |
| 6.5.9-arch2-1           | 2        | 0.75%   |
| 6.2.6-desktop-1omv2390  | 2        | 0.75%   |
| 6.1.1-desktop-1omv2290  | 2        | 0.75%   |
| 6.1.0-16-amd64          | 2        | 0.75%   |
| 5.8.0-48-generic        | 2        | 0.75%   |
| 5.8.0-38-generic        | 2        | 0.75%   |
| 5.4.0-56-generic        | 2        | 0.75%   |
| 5.4.0-54-generic        | 2        | 0.75%   |
| 5.4.0-52-generic        | 2        | 0.75%   |
| 5.4.0-47-generic        | 2        | 0.75%   |
| 5.4.0-42-generic        | 2        | 0.75%   |
| 5.4.0-37-generic        | 2        | 0.75%   |
| 5.3.0-51-generic        | 2        | 0.75%   |
| 5.3.0-40-generic        | 2        | 0.75%   |
| 5.19.0-46-generic       | 2        | 0.75%   |
| 5.16.7-desktop-1omv4003 | 2        | 0.75%   |
| 5.15.0-89-generic       | 2        | 0.75%   |
| 5.15.0-58-generic       | 2        | 0.75%   |
| 5.15.0-53-generic       | 2        | 0.75%   |
| 5.15.0-52-generic       | 2        | 0.75%   |
| 5.15.0-50-generic       | 2        | 0.75%   |
| 5.14.0-0.bpo.2-amd64    | 2        | 0.75%   |
| 5.13.0-21-generic       | 2        | 0.75%   |
| 4.19.0-14-amd64         | 2        | 0.75%   |
| 4.18.0-25-generic       | 2        | 0.75%   |
| 4.15.0-91-generic       | 2        | 0.75%   |
| 6.9.9-chos1-chimeraos-1 | 1        | 0.38%   |
| 6.9.7+bpo-amd64         | 1        | 0.38%   |
| 6.9.6-200.fc40.x86_64   | 1        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 35       | 13.62%  |
| 5.15.0  | 32       | 12.45%  |
| 4.15.0  | 18       | 7%      |
| 5.8.0   | 13       | 5.06%   |
| 4.18.0  | 10       | 3.89%   |
| 5.3.0   | 9        | 3.5%    |
| 6.8.0   | 7        | 2.72%   |
| 5.14.0  | 7        | 2.72%   |
| 6.2.0   | 6        | 2.33%   |
| 5.19.0  | 6        | 2.33%   |
| 6.5.0   | 5        | 1.95%   |
| 5.13.0  | 5        | 1.95%   |
| 6.1.0   | 4        | 1.56%   |
| 6.5.6   | 3        | 1.17%   |
| 5.0.0   | 3        | 1.17%   |
| 4.19.0  | 3        | 1.17%   |
| 6.6.2   | 2        | 0.78%   |
| 6.5.9   | 2        | 0.78%   |
| 6.2.6   | 2        | 0.78%   |
| 6.1.1   | 2        | 0.78%   |
| 5.16.7  | 2        | 0.78%   |
| 5.11.0  | 2        | 0.78%   |
| 5.10.0  | 2        | 0.78%   |
| 4.13.0  | 2        | 0.78%   |
| 3.10.0  | 2        | 0.78%   |
| 6.9.9   | 1        | 0.39%   |
| 6.9.7   | 1        | 0.39%   |
| 6.9.6   | 1        | 0.39%   |
| 6.9.5   | 1        | 0.39%   |
| 6.9.12  | 1        | 0.39%   |
| 6.8.9   | 1        | 0.39%   |
| 6.8.1   | 1        | 0.39%   |
| 6.7.9   | 1        | 0.39%   |
| 6.7.5   | 1        | 0.39%   |
| 6.7.4   | 1        | 0.39%   |
| 6.7.11  | 1        | 0.39%   |
| 6.6.8   | 1        | 0.39%   |
| 6.6.59  | 1        | 0.39%   |
| 6.6.27  | 1        | 0.39%   |
| 6.6.1   | 1        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 14.68%  |
| 5.15    | 34       | 13.49%  |
| 4.15    | 19       | 7.54%   |
| 5.8     | 16       | 6.35%   |
| 6.5     | 13       | 5.16%   |
| 6.1     | 12       | 4.76%   |
| 4.18    | 11       | 4.37%   |
| 6.2     | 10       | 3.97%   |
| 5.14    | 10       | 3.97%   |
| 5.3     | 9        | 3.57%   |
| 6.8     | 8        | 3.17%   |
| 5.19    | 7        | 2.78%   |
| 6.0     | 6        | 2.38%   |
| 6.9     | 5        | 1.98%   |
| 6.6     | 5        | 1.98%   |
| 5.13    | 5        | 1.98%   |
| 5.10    | 5        | 1.98%   |
| 5.16    | 4        | 1.59%   |
| 5.11    | 4        | 1.59%   |
| 5.0     | 4        | 1.59%   |
| 4.19    | 4        | 1.59%   |
| 6.7     | 3        | 1.19%   |
| 6.4     | 2        | 0.79%   |
| 6.11    | 2        | 0.79%   |
| 6.10    | 2        | 0.79%   |
| 5.6     | 2        | 0.79%   |
| 5.18    | 2        | 0.79%   |
| 4.9     | 2        | 0.79%   |
| 4.13    | 2        | 0.79%   |
| 3.10    | 2        | 0.79%   |
| 6.12    | 1        | 0.4%    |
| 5.9     | 1        | 0.4%    |
| 5.7     | 1        | 0.4%    |
| 5.12    | 1        | 0.4%    |
| 4.17    | 1        | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 230      | 99.57%  |
| i686   | 1        | 0.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 122      | 51.26%  |
| Unknown         | 40       | 16.81%  |
| KDE5            | 31       | 13.03%  |
| X-Cinnamon      | 17       | 7.14%   |
| XFCE            | 9        | 3.78%   |
| Cinnamon        | 3        | 1.26%   |
| Unity           | 2        | 0.84%   |
| TOS:GNOME       | 2        | 0.84%   |
| KDE             | 2        | 0.84%   |
| Hyprland        | 2        | 0.84%   |
| MATE            | 1        | 0.42%   |
| LXDE            | 1        | 0.42%   |
| KDE6            | 1        | 0.42%   |
| KDE4            | 1        | 0.42%   |
| GNOME Flashback | 1        | 0.42%   |
| GNOME Classic   | 1        | 0.42%   |
| Enlightenment   | 1        | 0.42%   |
| Deepin          | 1        | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 154      | 65.25%  |
| Wayland | 46       | 19.49%  |
| Unknown | 24       | 10.17%  |
| Tty     | 12       | 5.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 118      | 50.43%  |
| GDM3    | 36       | 15.38%  |
| SDDM    | 28       | 11.97%  |
| GDM     | 27       | 11.54%  |
| LightDM | 21       | 8.97%   |
| TDM     | 3        | 1.28%   |
| SLiM    | 1        | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ko_KR   | 103      | 44.02%  |
| en_US   | 89       | 38.03%  |
| Unknown | 29       | 12.39%  |
| C       | 5        | 2.14%   |
| en_GB   | 2        | 0.85%   |
| ru_UA   | 1        | 0.43%   |
| ru_RU   | 1        | 0.43%   |
| id_ID   | 1        | 0.43%   |
| fr_FR   | 1        | 0.43%   |
| en_CA   | 1        | 0.43%   |
| en_AU   | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 131      | 55.98%  |
| BIOS | 103      | 44.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 177      | 74.68%  |
| Btrfs   | 23       | 9.7%    |
| Xfs     | 11       | 4.64%   |
| Unknown | 9        | 3.8%    |
| Overlay | 6        | 2.53%   |
| Tmpfs   | 5        | 2.11%   |
| Zfs     | 4        | 1.69%   |
| Rootfs  | 1        | 0.42%   |
| F2fs    | 1        | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 110      | 47.21%  |
| GPT     | 107      | 45.92%  |
| MBR     | 16       | 6.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 81.2%   |
| Yes       | 44       | 18.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 158      | 67.81%  |
| Yes       | 75       | 32.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUSTek Computer            | 53       | 22.94%  |
| Gigabyte Technology         | 50       | 21.65%  |
| ASRock                      | 39       | 16.88%  |
| MSI                         | 27       | 11.69%  |
| Samsung Electronics         | 8        | 3.46%   |
| ECS                         | 7        | 3.03%   |
| Unknown                     | 7        | 3.03%   |
| Lenovo                      | 6        | 2.6%    |
| Hewlett-Packard             | 6        | 2.6%    |
| Dell                        | 4        | 1.73%   |
| Foxconn                     | 3        | 1.3%    |
| LattePanda                  | 2        | 0.87%   |
| Huanan                      | 2        | 0.87%   |
| WTM                         | 1        | 0.43%   |
| SZQFTX                      | 1        | 0.43%   |
| Shuttle                     | 1        | 0.43%   |
| Pelco by Schneider Electric | 1        | 0.43%   |
| PCPartner                   | 1        | 0.43%   |
| PC Partner Limited          | 1        | 0.43%   |
| MACHINIST                   | 1        | 0.43%   |
| INRUKO                      | 1        | 0.43%   |
| Google                      | 1        | 0.43%   |
| Fujitsu                     | 1        | 0.43%   |
| ELSKY                       | 1        | 0.43%   |
| ECS2                        | 1        | 0.43%   |
| Biostar                     | 1        | 0.43%   |
| AZW                         | 1        | 0.43%   |
| ASRockRack                  | 1        | 0.43%   |
| AMD                         | 1        | 0.43%   |
| Alienware                   | 1        | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 7        | 3.03%   |
| Samsung DeskTop System                  | 5        | 2.16%   |
| MSI MS-7B89                             | 4        | 1.73%   |
| Gigabyte B75M-D3H                       | 3        | 1.3%    |
| ASUS ROG STRIX Z690-A GAMING WIFI D4    | 3        | 1.3%    |
| ASUS PRIME B350M-A                      | 3        | 1.3%    |
| ASUS PRIME A320M-K                      | 3        | 1.3%    |
| ASUS All Series                         | 3        | 1.3%    |
| MSI MS-7D91                             | 2        | 0.87%   |
| MSI MS-7D42                             | 2        | 0.87%   |
| MSI MS-7C94                             | 2        | 0.87%   |
| LattePanda Alpha                        | 2        | 0.87%   |
| Gigabyte TRX40 AORUS XTREME             | 2        | 0.87%   |
| Gigabyte H81M-DS2V                      | 2        | 0.87%   |
| Gigabyte B75M-D3V                       | 2        | 0.87%   |
| Gigabyte B360M-D3H                      | 2        | 0.87%   |
| Gigabyte AB350-Gaming 3                 | 2        | 0.87%   |
| Gigabyte A320M-S2H                      | 2        | 0.87%   |
| ASUS Z170-A                             | 2        | 0.87%   |
| ASUS ROG STRIX B650E-E GAMING WIFI      | 2        | 0.87%   |
| ASUS EX-A320M-GAMING                    | 2        | 0.87%   |
| ASRock H81M-DGS R2.0                    | 2        | 0.87%   |
| ASRock AB350M Pro4                      | 2        | 0.87%   |
| WTM W-N95                               | 1        | 0.43%   |
| SZQFTX MN56                             | 1        | 0.43%   |
| Shuttle DH170                           | 1        | 0.43%   |
| Samsung 500T8A/500S8A/500T9A/500S9A     | 1        | 0.43%   |
| Samsung 400TDA/400SDA                   | 1        | 0.43%   |
| Samsung 400T7A/400S7A                   | 1        | 0.43%   |
| Pelco by Schneider Electric E1-MGW-SVRP | 1        | 0.43%   |
| PCPartner DREAMSYS                      | 1        | 0.43%   |
| PC Partner Limited S70BS.AH3511         | 1        | 0.43%   |
| MSI MS-7E25                             | 1        | 0.43%   |
| MSI MS-7D76                             | 1        | 0.43%   |
| MSI MS-7D74                             | 1        | 0.43%   |
| MSI MS-7D32                             | 1        | 0.43%   |
| MSI MS-7D31                             | 1        | 0.43%   |
| MSI MS-7C75                             | 1        | 0.43%   |
| MSI MS-7C51                             | 1        | 0.43%   |
| MSI MS-7C02                             | 1        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS PRIME                              | 16       | 6.93%   |
| ASUS ROG                                | 11       | 4.76%   |
| Unknown                                 | 7        | 3.03%   |
| Samsung DeskTop                         | 5        | 2.16%   |
| MSI MS-7B89                             | 4        | 1.73%   |
| Lenovo ThinkStation                     | 3        | 1.3%    |
| Gigabyte TRX40                          | 3        | 1.3%    |
| Gigabyte B75M-D3H                       | 3        | 1.3%    |
| ASUS All                                | 3        | 1.3%    |
| MSI MS-7D91                             | 2        | 0.87%   |
| MSI MS-7D42                             | 2        | 0.87%   |
| MSI MS-7C94                             | 2        | 0.87%   |
| LattePanda Alpha                        | 2        | 0.87%   |
| Gigabyte Z390                           | 2        | 0.87%   |
| Gigabyte X570                           | 2        | 0.87%   |
| Gigabyte H81M-DS2V                      | 2        | 0.87%   |
| Gigabyte B75M-D3V                       | 2        | 0.87%   |
| Gigabyte B360M-D3H                      | 2        | 0.87%   |
| Gigabyte AB350-Gaming                   | 2        | 0.87%   |
| Gigabyte A320M-S2H                      | 2        | 0.87%   |
| Dell Vostro                             | 2        | 0.87%   |
| Dell OptiPlex                           | 2        | 0.87%   |
| ASUS Z170-A                             | 2        | 0.87%   |
| ASUS TUF                                | 2        | 0.87%   |
| ASUS EX-A320M-GAMING                    | 2        | 0.87%   |
| ASRock Z390                             | 2        | 0.87%   |
| ASRock Z370                             | 2        | 0.87%   |
| ASRock H81M-DGS                         | 2        | 0.87%   |
| ASRock FM2A88M-HD+                      | 2        | 0.87%   |
| ASRock AB350M                           | 2        | 0.87%   |
| WTM W-N95                               | 1        | 0.43%   |
| SZQFTX MN56                             | 1        | 0.43%   |
| Shuttle DH170                           | 1        | 0.43%   |
| Samsung 500T8A                          | 1        | 0.43%   |
| Samsung 400TDA                          | 1        | 0.43%   |
| Samsung 400T7A                          | 1        | 0.43%   |
| Pelco by Schneider Electric E1-MGW-SVRP | 1        | 0.43%   |
| PCPartner DREAMSYS                      | 1        | 0.43%   |
| PC Partner Limited S70BS.AH3511         | 1        | 0.43%   |
| MSI MS-7E25                             | 1        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 10.39%  |
| 2017 | 22       | 9.52%   |
| 2022 | 19       | 8.23%   |
| 2020 | 19       | 8.23%   |
| 2012 | 17       | 7.36%   |
| 2021 | 16       | 6.93%   |
| 2019 | 15       | 6.49%   |
| 2015 | 15       | 6.49%   |
| 2013 | 15       | 6.49%   |
| 2014 | 13       | 5.63%   |
| 2023 | 12       | 5.19%   |
| 2016 | 9        | 3.9%    |
| 2009 | 8        | 3.46%   |
| 2011 | 7        | 3.03%   |
| 2008 | 6        | 2.6%    |
| 2010 | 5        | 2.16%   |
| 2007 | 5        | 2.16%   |
| 2006 | 2        | 0.87%   |
| 2024 | 1        | 0.43%   |
| 2005 | 1        | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 231      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 223      | 96.12%  |
| Enabled  | 9        | 3.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 230      | 99.57%  |
| Yes  | 1        | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 46       | 19.57%  |
| 64.01-256.0     | 42       | 17.87%  |
| 16.01-24.0      | 41       | 17.45%  |
| 32.01-64.0      | 35       | 14.89%  |
| 4.01-8.0        | 30       | 12.77%  |
| 3.01-4.0        | 22       | 9.36%   |
| 24.01-32.0      | 11       | 4.68%   |
| 1.01-2.0        | 4        | 1.7%    |
| More than 256.0 | 2        | 0.85%   |
| 2.01-3.0        | 2        | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 68       | 26.88%  |
| 2.01-3.0   | 52       | 20.55%  |
| 3.01-4.0   | 48       | 18.97%  |
| 4.01-8.0   | 46       | 18.18%  |
| 8.01-16.0  | 17       | 6.72%   |
| 0.51-1.0   | 11       | 4.35%   |
| 16.01-24.0 | 5        | 1.98%   |
| 32.01-64.0 | 4        | 1.58%   |
| 24.01-32.0 | 1        | 0.4%    |
| 0.01-0.5   | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 86       | 36.29%  |
| 2      | 75       | 31.65%  |
| 3      | 32       | 13.5%   |
| 4      | 18       | 7.59%   |
| 5      | 12       | 5.06%   |
| 6      | 6        | 2.53%   |
| 7      | 3        | 1.27%   |
| 8      | 2        | 0.84%   |
| 10     | 1        | 0.42%   |
| 9      | 1        | 0.42%   |
| 0      | 1        | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 73.71%  |
| Yes       | 61       | 26.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 229      | 99.13%  |
| No        | 2        | 0.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 138      | 59.48%  |
| Yes       | 94       | 40.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 57.45%  |
| Yes       | 100      | 42.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| South Korea | 231      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Seoul           | 19       | 7.69%   |
| Seongnam-si     | 17       | 6.88%   |
| Yongin-si       | 10       | 4.05%   |
| Suwon           | 10       | 4.05%   |
| Dongjak-gu      | 6        | 2.43%   |
| Busan           | 6        | 2.43%   |
| Pyeongtaek-si   | 5        | 2.02%   |
| Incheon         | 5        | 2.02%   |
| Gangbuk-gu      | 5        | 2.02%   |
| Cheonan         | 5        | 2.02%   |
| Yongsan-gu      | 4        | 1.62%   |
| Yangcheon-gu    | 4        | 1.62%   |
| Hwaseong-si     | 4        | 1.62%   |
| Gwanak-gu       | 4        | 1.62%   |
| Gangseo-gu      | 4        | 1.62%   |
| Daejeon         | 4        | 1.62%   |
| Bucheon-si      | 4        | 1.62%   |
| Anyang-si       | 4        | 1.62%   |
| Seongbuk-gu     | 3        | 1.21%   |
| Seo-gu          | 3        | 1.21%   |
| Nam-gu          | 3        | 1.21%   |
| Jungnang-gu     | 3        | 1.21%   |
| Icheon-si       | 3        | 1.21%   |
| Gyeonggi-do     | 3        | 1.21%   |
| Guri-si         | 3        | 1.21%   |
| Goyang-si       | 3        | 1.21%   |
| Geumcheon-gu    | 3        | 1.21%   |
| Gangnam-gu      | 3        | 1.21%   |
| Buk-gu          | 3        | 1.21%   |
| Ansan-si        | 3        | 1.21%   |
| Yeongdeungpo-gu | 2        | 0.81%   |
| Uiwang          | 2        | 0.81%   |
| Uiseong-gun     | 2        | 0.81%   |
| Songpa-gu       | 2        | 0.81%   |
| Siheung-si      | 2        | 0.81%   |
| Seongdong-gu    | 2        | 0.81%   |
| Sejong          | 2        | 0.81%   |
| Pocheon-si      | 2        | 0.81%   |
| Paju            | 2        | 0.81%   |
| Osan            | 2        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 78       | 119    | 17.89%  |
| WDC                          | 74       | 125    | 16.97%  |
| Seagate                      | 57       | 92     | 13.07%  |
| Toshiba                      | 28       | 47     | 6.42%   |
| Sandisk                      | 28       | 35     | 6.42%   |
| Crucial                      | 25       | 32     | 5.73%   |
| SK hynix                     | 17       | 23     | 3.9%    |
| Hitachi                      | 14       | 15     | 3.21%   |
| Unknown                      | 12       | 15     | 2.75%   |
| Transcend                    | 8        | 8      | 1.83%   |
| HGST                         | 8        | 10     | 1.83%   |
| Silicon Motion               | 7        | 9      | 1.61%   |
| A-DATA Technology            | 7        | 7      | 1.61%   |
| Micron Technology            | 6        | 7      | 1.38%   |
| Plextor                      | 4        | 8      | 0.92%   |
| TAMMUZ                       | 3        | 4      | 0.69%   |
| SPCC                         | 3        | 3      | 0.69%   |
| RevuAhn                      | 3        | 5      | 0.69%   |
| OCZ                          | 3        | 4      | 0.69%   |
| LITEON                       | 3        | 3      | 0.69%   |
| Intel                        | 3        | 3      | 0.69%   |
| China                        | 3        | 3      | 0.69%   |
| Unknown                      | 3        | 3      | 0.69%   |
| Team                         | 2        | 2      | 0.46%   |
| Seagate Technology           | 2        | 3      | 0.46%   |
| QNIX                         | 2        | 2      | 0.46%   |
| Micron/Crucial Technology    | 2        | 2      | 0.46%   |
| Imation                      | 2        | 3      | 0.46%   |
| Hewlett-Packard              | 2        | 3      | 0.46%   |
| Gigabyte Technology          | 2        | 2      | 0.46%   |
| Corsair                      | 2        | 2      | 0.46%   |
| ZOTAC                        | 1        | 1      | 0.23%   |
| XPG                          | 1        | 1      | 0.23%   |
| Shenzhen Longsys Electronics | 1        | 4      | 0.23%   |
| Realtek Semiconductor        | 1        | 1      | 0.23%   |
| Ramsta                       | 1        | 3      | 0.23%   |
| PNY                          | 1        | 1      | 0.23%   |
| Phison Electronics           | 1        | 1      | 0.23%   |
| Phison                       | 1        | 2      | 0.23%   |
| PHINOCOM                     | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Toshiba DT01ACA300 3TB                               | 8        | 1.57%   |
| Crucial CT500MX500SSD1 500GB                         | 7        | 1.37%   |
| Seagate ST500DM002-1BD142 500GB                      | 6        | 1.18%   |
| Crucial CT240BX500SSD1 240GB                         | 6        | 1.18%   |
| SK hynix SHGP31-2000GM 2TB                           | 5        | 0.98%   |
| Seagate ST2000DM008-2FR102 2TB                       | 5        | 0.98%   |
| WDC WD5000AAKX-00ERMA0 500GB                         | 4        | 0.78%   |
| Toshiba DT01ACA200 2TB                               | 4        | 0.78%   |
| Toshiba DT01ACA050 500GB                             | 4        | 0.78%   |
| SK hynix SHGP31-500GM 500GB                          | 4        | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB                       | 4        | 0.78%   |
| SanDisk SD8SBAT128G1122 128GB SSD                    | 4        | 0.78%   |
| Samsung SSD 980 1TB                                  | 4        | 0.78%   |
| Samsung SSD 850 EVO 120GB                            | 4        | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 4        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 4        | 0.78%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 3        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 3        | 0.59%   |
| WDC WD40EZRZ-00GXCB0 4TB                             | 3        | 0.59%   |
| WDC WD40EZAZ-00SF3B0 4TB                             | 3        | 0.59%   |
| WDC WD40EFRX-68WT0N0 4TB                             | 3        | 0.59%   |
| WDC WD3200AAJS-00L7A0 320GB                          | 3        | 0.59%   |
| WDC WD20EARX-00PASB0 2TB                             | 3        | 0.59%   |
| WDC WD10EZEX-22MFCA0 1TB                             | 3        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 3        | 0.59%   |
| Unknown SD/MMC/MS PRO 128GB                          | 3        | 0.59%   |
| Transcend TS240GSSD220S 240GB                        | 3        | 0.59%   |
| Seagate ST3500418AS 500GB                            | 3        | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB                       | 3        | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 3        | 0.59%   |
| Samsung SSD 850 PRO 256GB                            | 3        | 0.59%   |
| Samsung SSD 850 EVO 250GB                            | 3        | 0.59%   |
| Crucial CT275MX300SSD4 275GB                         | 3        | 0.59%   |
| Crucial CT250MX200SSD1 250GB                         | 3        | 0.59%   |
| A-DATA SU800 256GB SSD                               | 3        | 0.59%   |
| Unknown                                              | 3        | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 2        | 0.39%   |
| WDC WD10EZEX-00WN4A0 1TB                             | 2        | 0.39%   |
| Unknown NVMe SSD Drive 512GB                         | 2        | 0.39%   |
| Transcend TS120GSSD220S 120GB                        | 2        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 64       | 105    | 34.59%  |
| Seagate             | 55       | 87     | 29.73%  |
| Toshiba             | 24       | 36     | 12.97%  |
| Hitachi             | 14       | 15     | 7.57%   |
| Samsung Electronics | 12       | 14     | 6.49%   |
| HGST                | 8        | 10     | 4.32%   |
| Unknown             | 3        | 4      | 1.62%   |
| MARVELL             | 1        | 1      | 0.54%   |
| LaCie               | 1        | 1      | 0.54%   |
| JMicron Technology  | 1        | 1      | 0.54%   |
| Hewlett-Packard     | 1        | 1      | 0.54%   |
| Fujitsu             | 1        | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 46     | 21.38%  |
| Crucial             | 24       | 31     | 15.09%  |
| SanDisk             | 22       | 27     | 13.84%  |
| WDC                 | 13       | 17     | 8.18%   |
| Transcend           | 8        | 8      | 5.03%   |
| A-DATA Technology   | 6        | 6      | 3.77%   |
| Toshiba             | 4        | 11     | 2.52%   |
| TAMMUZ              | 3        | 4      | 1.89%   |
| SPCC                | 3        | 3      | 1.89%   |
| Seagate             | 3        | 4      | 1.89%   |
| RevuAhn             | 3        | 5      | 1.89%   |
| Plextor             | 3        | 7      | 1.89%   |
| OCZ                 | 3        | 4      | 1.89%   |
| LITEON              | 3        | 3      | 1.89%   |
| China               | 3        | 3      | 1.89%   |
| Unknown             | 3        | 3      | 1.89%   |
| SK hynix            | 2        | 4      | 1.26%   |
| QNIX                | 2        | 2      | 1.26%   |
| Intel               | 2        | 2      | 1.26%   |
| Imation             | 2        | 3      | 1.26%   |
| Gigabyte Technology | 2        | 2      | 1.26%   |
| Team                | 1        | 1      | 0.63%   |
| Ramsta              | 1        | 3      | 0.63%   |
| PNY                 | 1        | 1      | 0.63%   |
| PHINOCOM            | 1        | 1      | 0.63%   |
| OSCOO               | 1        | 1      | 0.63%   |
| Netac               | 1        | 1      | 0.63%   |
| Micron Technology   | 1        | 1      | 0.63%   |
| KingSpec            | 1        | 1      | 0.63%   |
| GLOWAY              | 1        | 1      | 0.63%   |
| Biostar             | 1        | 1      | 0.63%   |
| Apacer              | 1        | 1      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 140      | 276    | 38.67%  |
| SSD     | 131      | 208    | 36.19%  |
| NVMe    | 84       | 139    | 23.2%   |
| Unknown | 4        | 5      | 1.1%    |
| MMC     | 3        | 3      | 0.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 193      | 475    | 66.1%   |
| NVMe | 84       | 138    | 28.77%  |
| SAS  | 12       | 15     | 4.11%   |
| MMC  | 3        | 3      | 1.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 147      | 248    | 48.84%  |
| 0.51-1.0   | 61       | 89     | 20.27%  |
| 1.01-2.0   | 38       | 49     | 12.62%  |
| 3.01-4.0   | 25       | 46     | 8.31%   |
| 4.01-10.0  | 13       | 23     | 4.32%   |
| 2.01-3.0   | 12       | 18     | 3.99%   |
| 10.01-20.0 | 4        | 10     | 1.33%   |
| 20.01-50.0 | 1        | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 54       | 22.78%  |
| 501-1000       | 40       | 16.88%  |
| 251-500        | 38       | 16.03%  |
| More than 3000 | 30       | 12.66%  |
| 1001-2000      | 28       | 11.81%  |
| 2001-3000      | 17       | 7.17%   |
| 21-50          | 11       | 4.64%   |
| 51-100         | 9        | 3.8%    |
| 1-20           | 6        | 2.53%   |
| Unknown        | 4        | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 81       | 32.4%   |
| 101-250        | 41       | 16.4%   |
| 21-50          | 31       | 12.4%   |
| 51-100         | 27       | 10.8%   |
| 251-500        | 21       | 8.4%    |
| 501-1000       | 18       | 7.2%    |
| More than 3000 | 10       | 4%      |
| 1001-2000      | 9        | 3.6%    |
| 2001-3000      | 8        | 3.2%    |
| Unknown        | 4        | 1.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 2        | 2      | 7.69%   |
| WDC WD7500AACS-00D6B0 752GB                                     | 1        | 1      | 3.85%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 1        | 1      | 3.85%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 1        | 1      | 3.85%   |
| WDC WD40EZRZ-00WN9B0 4TB                                        | 1        | 1      | 3.85%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 1        | 2      | 3.85%   |
| WDC WD2000F9YZ-09N20L1 2TB                                      | 1        | 1      | 3.85%   |
| WDC WD1600BEVT-22A23T0 160GB                                    | 1        | 1      | 3.85%   |
| WDC WD10EZEX-60ZF5A0 1TB                                        | 1        | 1      | 3.85%   |
| WDC WD1003FBYX-01Y7B0 1TB                                       | 1        | 1      | 3.85%   |
| WDC WD1001FALS-00J7B1 1TB                                       | 1        | 1      | 3.85%   |
| Seagate ST500DM009-2F110A 500GB                                 | 1        | 1      | 3.85%   |
| Seagate ST4000DM000-1F2168 4TB                                  | 1        | 1      | 3.85%   |
| Seagate ST3500418AS 500GB                                       | 1        | 1      | 3.85%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 1        | 1      | 3.85%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 1        | 1      | 3.85%   |
| Samsung Electronics HM160HI 160GB                               | 1        | 1      | 3.85%   |
| Samsung Electronics HD160JJ 160GB                               | 1        | 1      | 3.85%   |
| Ramsta SSD S600 480GB                                           | 1        | 3      | 3.85%   |
| LITEON LMH-128V2M 128GB SSD                                     | 1        | 1      | 3.85%   |
| Hitachi HTS543216L9A300 160GB                                   | 1        | 1      | 3.85%   |
| Hitachi HDS721050CLA362 500GB                                   | 1        | 1      | 3.85%   |
| Hitachi HDS721010CLA632 1TB                                     | 1        | 1      | 3.85%   |
| HGST HDN726060ALE610 6TB                                        | 1        | 1      | 3.85%   |
| A-DATA Technology SU650 240GB SSD                               | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 11     | 38.46%  |
| Seagate             | 5        | 5      | 19.23%  |
| Samsung Electronics | 4        | 4      | 15.38%  |
| Hitachi             | 3        | 3      | 11.54%  |
| Ramsta              | 1        | 3      | 3.85%   |
| LITEON              | 1        | 1      | 3.85%   |
| HGST                | 1        | 1      | 3.85%   |
| A-DATA Technology   | 1        | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 11     | 47.62%  |
| Seagate             | 5        | 5      | 23.81%  |
| Hitachi             | 3        | 3      | 14.29%  |
| Samsung Electronics | 2        | 2      | 9.52%   |
| HGST                | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 22     | 77.27%  |
| SSD  | 3        | 5      | 13.64%  |
| NVMe | 2        | 2      | 9.09%   |

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
| Detected | 127      | 328    | 49.61%  |
| Works    | 107      | 274    | 41.8%   |
| Malfunc  | 22       | 29     | 8.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 149      | 40.38%  |
| AMD                          | 74       | 20.05%  |
| Samsung Electronics          | 42       | 11.38%  |
| ASMedia Technology           | 25       | 6.78%   |
| SK hynix                     | 15       | 4.07%   |
| JMicron Technology           | 11       | 2.98%   |
| Silicon Motion               | 8        | 2.17%   |
| SanDisk                      | 8        | 2.17%   |
| Phison Electronics           | 6        | 1.63%   |
| Micron Technology            | 5        | 1.36%   |
| Marvell Technology Group     | 4        | 1.08%   |
| Seagate Technology           | 3        | 0.81%   |
| Micron/Crucial Technology    | 3        | 0.81%   |
| Biwin Storage Technology     | 2        | 0.54%   |
| ADATA Technology             | 2        | 0.54%   |
| VIA Technologies             | 1        | 0.27%   |
| Solidigm                     | 1        | 0.27%   |
| Shenzhen Longsys Electronics | 1        | 0.27%   |
| Realtek Semiconductor        | 1        | 0.27%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.27%   |
| LSI Logic / Symbios Logic    | 1        | 0.27%   |
| Lite-On Technology           | 1        | 0.27%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.27%   |
| KIOXIA                       | 1        | 0.27%   |
| INNOGRIT                     | 1        | 0.27%   |
| Broadcom / LSI               | 1        | 0.27%   |
| 3ware                        | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 43       | 9.47%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 24       | 5.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22       | 4.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18       | 3.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16       | 3.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15       | 3.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 2.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 2.42%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 10       | 2.2%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 2.2%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 10       | 2.2%    |
| AMD 600 Series Chipset SATA Controller                                                  | 10       | 2.2%    |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 2.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 1.98%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 1.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 1.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 1.76%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.54%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 7        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 1.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 1.32%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 1.32%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 5        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.1%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 4        | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4        | 0.88%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 0.88%   |
| AMD FCH IDE Controller                                                                  | 4        | 0.88%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.66%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3        | 0.66%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 3        | 0.66%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 3        | 0.66%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 0.66%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 197      | 58.63%  |
| NVMe | 86       | 25.6%   |
| IDE  | 38       | 11.31%  |
| RAID | 13       | 3.87%   |
| SAS  | 2        | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 152      | 65.8%   |
| AMD    | 79       | 34.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-3570 CPU @ 3.40GHz               | 9        | 3.9%    |
| AMD Ryzen 5 1600 Six-Core Processor            | 6        | 2.6%    |
| Intel Core i5-8500 CPU @ 3.00GHz               | 5        | 2.16%   |
| Intel Pentium CPU G4400 @ 3.30GHz              | 4        | 1.73%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 4        | 1.73%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 4        | 1.73%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 4        | 1.73%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 4        | 1.73%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 4        | 1.73%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 3        | 1.3%    |
| Intel Core i9-14900K                           | 3        | 1.3%    |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 1.3%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 1.3%    |
| Intel 12th Gen Core i9-12900K                  | 3        | 1.3%    |
| AMD Ryzen 9 7900X 12-Core Processor            | 3        | 1.3%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 3        | 1.3%    |
| Intel Pentium 4 CPU 3.00GHz                    | 2        | 0.87%   |
| Intel Core i9-10900K CPU @ 3.70GHz             | 2        | 0.87%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 2        | 0.87%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 0.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 0.87%   |
| Intel Core i5-7600 CPU @ 3.50GHz               | 2        | 0.87%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 2        | 0.87%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 2        | 0.87%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 2        | 0.87%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 2        | 0.87%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 0.87%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 2        | 0.87%   |
| Intel Core i5 CPU 760 @ 2.80GHz                | 2        | 0.87%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz          | 2        | 0.87%   |
| Intel 13th Gen Core i9-13900K                  | 2        | 0.87%   |
| Intel 13th Gen Core i7-13700K                  | 2        | 0.87%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 2        | 0.87%   |
| AMD Ryzen 9 7900 12-Core Processor             | 2        | 0.87%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 2        | 0.87%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics     | 2        | 0.87%   |
| AMD Ryzen 5 7600 6-Core Processor              | 2        | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 0.87%   |
| AMD FX-8300 Eight-Core Processor               | 2        | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 41       | 17.75%  |
| AMD Ryzen 5             | 28       | 12.12%  |
| Intel Core i7           | 20       | 8.66%   |
| Other                   | 18       | 7.79%   |
| Intel Xeon              | 16       | 6.93%   |
| Intel Core i3           | 13       | 5.63%   |
| AMD Ryzen 7             | 12       | 5.19%   |
| AMD Ryzen 9             | 11       | 4.76%   |
| Intel Core i9           | 10       | 4.33%   |
| Intel Pentium           | 9        | 3.9%    |
| Intel Celeron           | 8        | 3.46%   |
| AMD Ryzen Threadripper  | 7        | 3.03%   |
| Intel Core 2 Quad       | 6        | 2.6%    |
| AMD Ryzen 3             | 5        | 2.16%   |
| AMD A10                 | 3        | 1.3%    |
| Intel Pentium Gold      | 2        | 0.87%   |
| Intel Pentium Dual-Core | 2        | 0.87%   |
| Intel Pentium 4         | 2        | 0.87%   |
| Intel Core m3           | 2        | 0.87%   |
| Intel Core 2 Duo        | 2        | 0.87%   |
| AMD Ryzen 5 PRO         | 2        | 0.87%   |
| AMD FX                  | 2        | 0.87%   |
| AMD A8                  | 2        | 0.87%   |
| Intel Core 2            | 1        | 0.43%   |
| AMD Ryzen Embedded      | 1        | 0.43%   |
| AMD Ryzen 7 PRO         | 1        | 0.43%   |
| AMD Phenom II X6        | 1        | 0.43%   |
| AMD Phenom              | 1        | 0.43%   |
| AMD Athlon II X2        | 1        | 0.43%   |
| AMD Athlon 64 X2        | 1        | 0.43%   |
| AMD Athlon              | 1        | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 75       | 32.47%  |
| 6      | 48       | 20.78%  |
| 2      | 44       | 19.05%  |
| 8      | 21       | 9.09%   |
| 16     | 13       | 5.63%   |
| 12     | 8        | 3.46%   |
| 24     | 5        | 2.16%   |
| 10     | 5        | 2.16%   |
| 32     | 3        | 1.3%    |
| 28     | 2        | 0.87%   |
| 1      | 2        | 0.87%   |
| 64     | 1        | 0.43%   |
| 22     | 1        | 0.43%   |
| 20     | 1        | 0.43%   |
| 18     | 1        | 0.43%   |
| 14     | 1        | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 229      | 99.13%  |
| 2      | 2        | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 139      | 59.91%  |
| 1      | 93       | 40.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 229      | 98.71%  |
| Unknown        | 3        | 1.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 76       | 32.34%  |
| 0x306c3    | 18       | 7.66%   |
| 0x306a9    | 18       | 7.66%   |
| 0x906ea    | 8        | 3.4%    |
| 0x906e9    | 7        | 2.98%   |
| 0x506e3    | 6        | 2.55%   |
| 0x306f2    | 5        | 2.13%   |
| 0x1067a    | 5        | 2.13%   |
| 0x08001138 | 5        | 2.13%   |
| 0xb0671    | 4        | 1.7%    |
| 0x906ed    | 4        | 1.7%    |
| 0x206a7    | 4        | 1.7%    |
| 0x106e5    | 4        | 1.7%    |
| 0x08101016 | 4        | 1.7%    |
| 0x0800820d | 4        | 1.7%    |
| 0x08001137 | 4        | 1.7%    |
| 0xa0655    | 3        | 1.28%   |
| 0x90672    | 3        | 1.28%   |
| 0x6fb      | 3        | 1.28%   |
| 0x0a20120a | 3        | 1.28%   |
| 0x08701021 | 3        | 1.28%   |
| 0x906ec    | 2        | 0.85%   |
| 0x806e9    | 2        | 0.85%   |
| 0x50654    | 2        | 0.85%   |
| 0x0a601206 | 2        | 0.85%   |
| 0x0a601203 | 2        | 0.85%   |
| 0x0a601201 | 2        | 0.85%   |
| 0x0a50000d | 2        | 0.85%   |
| 0x0a201016 | 2        | 0.85%   |
| 0x08600106 | 2        | 0.85%   |
| 0x08108109 | 2        | 0.85%   |
| 0x0810100b | 2        | 0.85%   |
| 0xf49      | 1        | 0.43%   |
| 0xa0671    | 1        | 0.43%   |
| 0x906eb    | 1        | 0.43%   |
| 0x90675    | 1        | 0.43%   |
| 0x406f1    | 1        | 0.43%   |
| 0x306e4    | 1        | 0.43%   |
| 0x306d4    | 1        | 0.43%   |
| 0x30678    | 1        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 31       | 13.42%  |
| Haswell          | 30       | 12.99%  |
| Unknown          | 22       | 9.52%   |
| IvyBridge        | 21       | 9.09%   |
| Zen              | 19       | 8.23%   |
| Zen 3            | 14       | 6.06%   |
| Skylake          | 14       | 6.06%   |
| Zen 2            | 13       | 5.63%   |
| Zen+             | 9        | 3.9%    |
| Alderlake Hybrid | 9        | 3.9%    |
| Penryn           | 8        | 3.46%   |
| CometLake        | 5        | 2.16%   |
| SandyBridge      | 4        | 1.73%   |
| Piledriver       | 4        | 1.73%   |
| Nehalem          | 4        | 1.73%   |
| Core             | 4        | 1.73%   |
| K10              | 3        | 1.3%    |
| Broadwell        | 3        | 1.3%    |
| Steamroller      | 2        | 0.87%   |
| Silvermont       | 2        | 0.87%   |
| NetBurst         | 2        | 0.87%   |
| Icelake          | 2        | 0.87%   |
| Gracemont        | 2        | 0.87%   |
| Westmere         | 1        | 0.43%   |
| K8 Hammer        | 1        | 0.43%   |
| K10 Llano        | 1        | 0.43%   |
| Goldmont plus    | 1        | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 116      | 43.94%  |
| Intel             | 83       | 31.44%  |
| AMD               | 62       | 23.48%  |
| ASPEED Technology | 3        | 1.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 4.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 3.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 3.31%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8        | 2.94%   |
| AMD Raphael                                                                 | 8        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 2.57%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 6        | 2.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 1.84%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 1.47%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 1.47%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.47%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 4        | 1.47%   |
| Intel HD Graphics 510                                                       | 4        | 1.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.47%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 4        | 1.47%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.1%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 1.1%    |
| Nvidia GF108 [GeForce GT 440]                                               | 3        | 1.1%    |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 3        | 1.1%    |
| Intel HD Graphics 630                                                       | 3        | 1.1%    |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 1.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.1%    |
| ASPEED Technology ASPEED Graphics Family                                    | 3        | 1.1%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.74%   |
| Nvidia TU102 [TITAN RTX]                                                    | 2        | 0.74%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.74%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.74%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.74%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.74%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 2        | 0.74%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 0.74%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| 1 x Nvidia                | 101      | 43.16%  |
| 1 x Intel                 | 63       | 26.92%  |
| 1 x AMD                   | 49       | 20.94%  |
| AMD + Nvidia              | 7        | 2.99%   |
| 2 x AMD                   | 4        | 1.71%   |
| Intel + Nvidia            | 4        | 1.71%   |
| 2 x Nvidia                | 1        | 0.43%   |
| Nvidia + ASPEED           | 1        | 0.43%   |
| Intel + AMD               | 1        | 0.43%   |
| 1 x ASPEED                | 1        | 0.43%   |
| AMD + 2 x Nvidia          | 1        | 0.43%   |
| AMD + Nvidia + 1 x ASPEED | 1        | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 154      | 65.81%  |
| Proprietary | 69       | 29.49%  |
| Unknown     | 11       | 4.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 106      | 44.73%  |
| 1.01-2.0   | 27       | 11.39%  |
| 0.51-1.0   | 26       | 10.97%  |
| 7.01-8.0   | 20       | 8.44%   |
| 3.01-4.0   | 15       | 6.33%   |
| 0.01-0.5   | 14       | 5.91%   |
| 8.01-16.0  | 13       | 5.49%   |
| 5.01-6.0   | 6        | 2.53%   |
| 16.01-24.0 | 5        | 2.11%   |
| 2.01-3.0   | 4        | 1.69%   |
| 4.01-5.0   | 1        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 48       | 20.69%  |
| Samsung Electronics  | 41       | 17.67%  |
| Dell                 | 12       | 5.17%   |
| Unknown              | 11       | 4.74%   |
| AOC                  | 10       | 4.31%   |
| Philips              | 9        | 3.88%   |
| Hewlett-Packard      | 9        | 3.88%   |
| LG Electronics       | 7        | 3.02%   |
| PRISM+               | 5        | 2.16%   |
| OUT                  | 5        | 2.16%   |
| BenQ                 | 5        | 2.16%   |
| Unknown (ADE)        | 4        | 1.72%   |
| RTK                  | 4        | 1.72%   |
| JCH                  | 3        | 1.29%   |
| ZTL                  | 2        | 0.86%   |
| XUE                  | 2        | 0.86%   |
| Xiangye              | 2        | 0.86%   |
| SANYO                | 2        | 0.86%   |
| OOO                  | 2        | 0.86%   |
| MStar                | 2        | 0.86%   |
| MiTAC                | 2        | 0.86%   |
| Lenovo               | 2        | 0.86%   |
| JRY                  | 2        | 0.86%   |
| HXM                  | 2        | 0.86%   |
| Ancor Communications | 2        | 0.86%   |
| ALP                  | 2        | 0.86%   |
| Yamaha               | 1        | 0.43%   |
| Xiaomi               | 1        | 0.43%   |
| WIT                  | 1        | 0.43%   |
| ViewSonic            | 1        | 0.43%   |
| UPV                  | 1        | 0.43%   |
| TopView              | 1        | 0.43%   |
| TGL                  | 1        | 0.43%   |
| TCH                  | 1        | 0.43%   |
| Sun                  | 1        | 0.43%   |
| SiS                  | 1        | 0.43%   |
| SGT                  | 1        | 0.43%   |
| RAT                  | 1        | 0.43%   |
| Pixio                | 1        | 0.43%   |
| PBK                  | 1        | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 5        | 2.07%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5        | 2.07%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch      | 3        | 1.24%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                         | 3        | 1.24%   |
| ZTL ZM29W1 ZTL1506 2560x1080 1600x1000mm 74.3-inch                     | 2        | 0.83%   |
| XUE Type-C XUE1600 2560x1600 360x190mm 16.0-inch                       | 2        | 0.83%   |
| Xiangye N2408HZ XYE2700 1920x1080 597x336mm 27.0-inch                  | 2        | 0.83%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1020x570mm 46.0-inch | 2        | 0.83%   |
| PRISM+ ULTRON 3547UC INN0035 2560x1080 820x345mm 35.0-inch             | 2        | 0.83%   |
| PRISM+ CK27FC INN0027 1920x1080 598x336mm 27.0-inch                    | 2        | 0.83%   |
| OOO 13.3' monitor OOO0001 1920x1080 409x230mm 18.5-inch                | 2        | 0.83%   |
| MiTAC OK_TV MTC0030 3840x2160 708x398mm 32.0-inch                      | 2        | 0.83%   |
| JRY Digital JRY0215 1920x1080 340x255mm 16.7-inch                      | 2        | 0.83%   |
| JCH UDEA Monitor JCHE321 1920x1080 443x249mm 20.0-inch                 | 2        | 0.83%   |
| Goldstar LG HDR QHD GSM5B96 2560x1440 700x390mm 31.5-inch              | 2        | 0.83%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch              | 2        | 0.83%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 2        | 0.83%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 2        | 0.83%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                       | 2        | 0.83%   |
| Yamaha YSP-1600 YMH331A 1920x540                                       | 1        | 0.41%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                     | 1        | 0.41%   |
| WIT HDMI WIT5082 2560x1440 596x335mm 26.9-inch                         | 1        | 0.41%   |
| ViewSonic VX3218 Series VSC7032 2560x1440 698x393mm 31.5-inch          | 1        | 0.41%   |
| UPV UP-M30W1 UPV0001 2560x1600 641x401mm 29.8-inch                     | 1        | 0.41%   |
| Unknown LCD Monitor STD 32Q-HDMI 2560x1440                             | 1        | 0.41%   |
| Unknown LCD Monitor SKYDATA S.P.A. LG TV 1920x1080                     | 1        | 0.41%   |
| Unknown LCD Monitor SAMSUNG 3286x1080                                  | 1        | 0.41%   |
| Unknown LCD Monitor OUT Digital 3200x1080                              | 1        | 0.41%   |
| Unknown LCD Monitor ORC DIGITAL MONITOR 1280x1024                      | 1        | 0.41%   |
| Unknown LCD Monitor NQM NewQ System 1280x1024                          | 1        | 0.41%   |
| Unknown LCD Monitor INN ULTRON 3479UC 4880x2560                        | 1        | 0.41%   |
| Unknown LCD Monitor ICB ULTRON4079 3840x2160                           | 1        | 0.41%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.41%   |
| Unknown LCD Monitor Digital Projection Limited DP                      | 1        | 0.41%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                             | 1        | 0.41%   |
| Unknown LCD Monitor Chuntex/CTX NL27 3840x2160                         | 1        | 0.41%   |
| Unknown (ADE) TSLED22D ADEB22D 1920x1080 477x268mm 21.5-inch           | 1        | 0.41%   |
| Unknown (ADE) TLED20DHS ADE2000 1600x900 443x249mm 20.0-inch           | 1        | 0.41%   |
| Unknown (ADE) P2400HDT ADE00F0 1920x1080 521x293mm 23.5-inch           | 1        | 0.41%   |
| Unknown (ADE) N2413 ADS LED ADE2413 1920x1080 521x293mm 23.5-inch      | 1        | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 112      | 49.34%  |
| 3840x2160 (4K)     | 33       | 14.54%  |
| 2560x1440 (QHD)    | 25       | 11.01%  |
| 1280x1024 (SXGA)   | 11       | 4.85%   |
| 1920x1200 (WUXGA)  | 7        | 3.08%   |
| 3440x1440          | 6        | 2.64%   |
| 2560x1080          | 6        | 2.64%   |
| 1680x1050 (WSXGA+) | 6        | 2.64%   |
| 2560x1600          | 3        | 1.32%   |
| 1440x900 (WXGA+)   | 3        | 1.32%   |
| Unknown            | 3        | 1.32%   |
| 3840x1080          | 2        | 0.88%   |
| 1600x900 (HD+)     | 2        | 0.88%   |
| 4880x2560          | 1        | 0.44%   |
| 3840x1600          | 1        | 0.44%   |
| 3286x1080          | 1        | 0.44%   |
| 3200x1080          | 1        | 0.44%   |
| 2288x1287          | 1        | 0.44%   |
| 1920x540           | 1        | 0.44%   |
| 1600x1200          | 1        | 0.44%   |
| 1280x960           | 1        | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 39       | 17.03%  |
| Unknown | 35       | 15.28%  |
| 23      | 23       | 10.04%  |
| 24      | 21       | 9.17%   |
| 31      | 19       | 8.3%    |
| 21      | 17       | 7.42%   |
| 16      | 11       | 4.8%    |
| 19      | 8        | 3.49%   |
| 20      | 7        | 3.06%   |
| 34      | 4        | 1.75%   |
| 84      | 3        | 1.31%   |
| 40      | 3        | 1.31%   |
| 29      | 3        | 1.31%   |
| 22      | 3        | 1.31%   |
| 18      | 3        | 1.31%   |
| 17      | 3        | 1.31%   |
| 74      | 2        | 0.87%   |
| 52      | 2        | 0.87%   |
| 42      | 2        | 0.87%   |
| 39      | 2        | 0.87%   |
| 35      | 2        | 0.87%   |
| 28      | 2        | 0.87%   |
| 25      | 2        | 0.87%   |
| 15      | 2        | 0.87%   |
| 142     | 1        | 0.44%   |
| 72      | 1        | 0.44%   |
| 57      | 1        | 0.44%   |
| 54      | 1        | 0.44%   |
| 49      | 1        | 0.44%   |
| 48      | 1        | 0.44%   |
| 46      | 1        | 0.44%   |
| 37      | 1        | 0.44%   |
| 33      | 1        | 0.44%   |
| 32      | 1        | 0.44%   |
| 26      | 1        | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 78       | 34.98%  |
| Unknown        | 35       | 15.7%   |
| 401-500        | 31       | 13.9%   |
| 601-700        | 26       | 11.66%  |
| 351-400        | 12       | 5.38%   |
| 301-350        | 11       | 4.93%   |
| 801-900        | 8        | 3.59%   |
| 1001-1500      | 7        | 3.14%   |
| 701-800        | 6        | 2.69%   |
| 1501-2000      | 6        | 2.69%   |
| 901-1000       | 2        | 0.9%    |
| More than 2000 | 1        | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 135      | 63.38%  |
| Unknown | 31       | 14.55%  |
| 16/10   | 16       | 7.51%   |
| 5/4     | 9        | 4.23%   |
| 4/3     | 8        | 3.76%   |
| 21/9    | 8        | 3.76%   |
| 32/9    | 3        | 1.41%   |
| 6/5     | 1        | 0.47%   |
| 3/2     | 1        | 0.47%   |
| 1.00    | 1        | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 51       | 22.47%  |
| 301-350        | 41       | 18.06%  |
| Unknown        | 35       | 15.42%  |
| 351-500        | 32       | 14.1%   |
| 151-200        | 19       | 8.37%   |
| More than 1000 | 11       | 4.85%   |
| 251-300        | 11       | 4.85%   |
| 501-1000       | 10       | 4.41%   |
| 131-140        | 6        | 2.64%   |
| 141-150        | 4        | 1.76%   |
| 101-110        | 4        | 1.76%   |
| 111-120        | 3        | 1.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 105      | 48.39%  |
| 101-120 | 38       | 17.51%  |
| Unknown | 35       | 16.13%  |
| 121-160 | 23       | 10.6%   |
| 1-50    | 10       | 4.61%   |
| 161-240 | 6        | 2.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 184      | 79.31%  |
| 2     | 30       | 12.93%  |
| 0     | 17       | 7.33%   |
| 3     | 1        | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 165      | 54.1%   |
| Intel                           | 90       | 29.51%  |
| Qualcomm Atheros                | 9        | 2.95%   |
| MediaTek                        | 9        | 2.95%   |
| Ralink Technology               | 6        | 1.97%   |
| Broadcom                        | 4        | 1.31%   |
| Ralink                          | 3        | 0.98%   |
| Marvell Technology Group        | 2        | 0.66%   |
| Exar                            | 2        | 0.66%   |
| Broadcom Limited                | 2        | 0.66%   |
| ASIX Electronics                | 2        | 0.66%   |
| Aquantia                        | 2        | 0.66%   |
| Wilocity                        | 1        | 0.33%   |
| Qualcomm Technologies           | 1        | 0.33%   |
| Qualcomm Atheros Communications | 1        | 0.33%   |
| PEAK-System Technik             | 1        | 0.33%   |
| NetGear                         | 1        | 0.33%   |
| Kinesis                         | 1        | 0.33%   |
| D-Link                          | 1        | 0.33%   |
| Chelsio Communications          | 1        | 0.33%   |
| American Megatrends             | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 135      | 36.59%  |
| Realtek RTL8125 2.5GbE Controller                                      | 16       | 4.34%   |
| Intel Wi-Fi 6 AX200                                                    | 15       | 4.07%   |
| Intel Ethernet Controller I225-V                                       | 13       | 3.52%   |
| Intel Ethernet Connection (2) I219-V                                   | 9        | 2.44%   |
| Intel I211 Gigabit Network Connection                                  | 8        | 2.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 1.63%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 1.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5        | 1.36%   |
| Intel I210 Gigabit Network Connection                                  | 5        | 1.36%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 5        | 1.36%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 4        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4        | 1.08%   |
| Realtek 802.11ac NIC                                                   | 4        | 1.08%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 4        | 1.08%   |
| Intel Ethernet Controller X550                                         | 4        | 1.08%   |
| Intel Ethernet Controller I226-V                                       | 4        | 1.08%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 1.08%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 3        | 0.81%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 3        | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3        | 0.81%   |
| Ralink MT7601U Wireless Adapter                                        | 3        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 0.81%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.81%   |
| Intel Ethernet Connection (2) I218-LM                                  | 3        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 0.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 0.81%   |
| Realtek 802.11n NIC                                                    | 2        | 0.54%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2        | 0.54%   |
| MediaTek WiFi                                                          | 2        | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2        | 0.54%   |
| Intel Wireless 3165                                                    | 2        | 0.54%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 2        | 0.54%   |
| Intel Ethernet Connection (11) I219-V                                  | 2        | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.54%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 0.54%   |
| Exar XR21V1410 USB-UART IC                                             | 2        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 42       | 42%     |
| Realtek Semiconductor           | 30       | 30%     |
| MediaTek                        | 8        | 8%      |
| Ralink Technology               | 6        | 6%      |
| Ralink                          | 3        | 3%      |
| Qualcomm Atheros                | 3        | 3%      |
| Broadcom                        | 2        | 2%      |
| Wilocity                        | 1        | 1%      |
| Qualcomm Technologies           | 1        | 1%      |
| Qualcomm Atheros Communications | 1        | 1%      |
| NetGear                         | 1        | 1%      |
| D-Link                          | 1        | 1%      |
| Broadcom Limited                | 1        | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                              | 15       | 14.85%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]        | 6        | 5.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 5        | 4.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                               | 4        | 3.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 4        | 3.96%   |
| Realtek 802.11ac NIC                                             | 4        | 3.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter    | 4        | 3.96%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                | 4        | 3.96%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter          | 3        | 2.97%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                       | 3        | 2.97%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 3        | 2.97%   |
| Ralink MT7601U Wireless Adapter                                  | 3        | 2.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 3        | 2.97%   |
| Realtek 802.11n NIC                                              | 2        | 1.98%   |
| MediaTek WiFi                                                    | 2        | 1.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter    | 2        | 1.98%   |
| Intel Wireless 3165                                              | 2        | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 2        | 1.98%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter     | 2        | 1.98%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter               | 1        | 0.99%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 1        | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 1        | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1        | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                  | 1        | 0.99%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                  | 1        | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 1        | 0.99%   |
| Ralink RT5572 Wireless Adapter                                   | 1        | 0.99%   |
| Ralink RT5372 Wireless Adapter                                   | 1        | 0.99%   |
| Ralink RT3072 Wireless Adapter                                   | 1        | 0.99%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                        | 1        | 0.99%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1        | 0.99%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                             | 1        | 0.99%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800] | 1        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 1        | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                  | 1        | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 1        | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 1        | 0.99%   |
| NetGear Wireless_Device                                          | 1        | 0.99%   |
| Intel Wireless 8265 / 8275                                       | 1        | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 159      | 63.86%  |
| Intel                    | 72       | 28.92%  |
| Qualcomm Atheros         | 6        | 2.41%   |
| Marvell Technology Group | 2        | 0.8%    |
| Broadcom                 | 2        | 0.8%    |
| ASIX Electronics         | 2        | 0.8%    |
| Aquantia                 | 2        | 0.8%    |
| MediaTek                 | 1        | 0.4%    |
| Chelsio Communications   | 1        | 0.4%    |
| Broadcom Limited         | 1        | 0.4%    |
| American Megatrends      | 1        | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 135      | 51.14%  |
| Realtek RTL8125 2.5GbE Controller                                              | 16       | 6.06%   |
| Intel Ethernet Controller I225-V                                               | 13       | 4.92%   |
| Intel Ethernet Connection (2) I219-V                                           | 9        | 3.41%   |
| Intel I211 Gigabit Network Connection                                          | 8        | 3.03%   |
| Intel Ethernet Connection (7) I219-V                                           | 6        | 2.27%   |
| Intel I210 Gigabit Network Connection                                          | 5        | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4        | 1.52%   |
| Intel Ethernet Controller X550                                                 | 4        | 1.52%   |
| Intel Ethernet Controller I226-V                                               | 4        | 1.52%   |
| Intel Ethernet Connection I217-LM                                              | 4        | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 1.14%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 1.14%   |
| Intel Ethernet Connection (2) I218-LM                                          | 3        | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 1.14%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 2        | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2        | 0.76%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                | 2        | 0.76%   |
| Intel Ethernet Connection (11) I219-V                                          | 2        | 0.76%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 0.76%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2        | 0.76%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.76%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1        | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1        | 0.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 0.38%   |
| Realtek RT8126 PCIe Ethernet Controller                                        | 1        | 0.38%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1        | 0.38%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1        | 0.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 1        | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1        | 0.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.38%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1        | 0.38%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.38%   |
| Intel Ethernet Controller X710 for 10GBASE-T                                   | 1        | 0.38%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.38%   |
| Intel Ethernet Connection (17) I219-V                                          | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 229      | 70.25%  |
| WiFi     | 93       | 28.53%  |
| Modem    | 3        | 0.92%   |
| Unknown  | 1        | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 193      | 81.09%  |
| WiFi     | 45       | 18.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 141      | 61.04%  |
| 2     | 73       | 31.6%   |
| 3     | 12       | 5.19%   |
| 4     | 3        | 1.3%    |
| 5     | 2        | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 231      | 99.57%  |
| Yes  | 1        | 0.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 41       | 40.59%  |
| Cambridge Silicon Radio | 28       | 27.72%  |
| Realtek Semiconductor   | 12       | 11.88%  |
| MediaTek                | 4        | 3.96%   |
| IMC Networks            | 4        | 3.96%   |
| Broadcom                | 4        | 3.96%   |
| Foxconn / Hon Hai       | 3        | 2.97%   |
| ASUSTek Computer        | 3        | 2.97%   |
| TP-Link                 | 1        | 0.99%   |
| Unknown                 | 1        | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 28       | 27.45%  |
| Intel AX200 Bluetooth                                 | 13       | 12.75%  |
| Realtek Bluetooth Radio                               | 9        | 8.82%   |
| Intel Bluetooth wireless interface                    | 6        | 5.88%   |
| Intel AX211 Bluetooth                                 | 6        | 5.88%   |
| Intel AX210 Bluetooth                                 | 5        | 4.9%    |
| MediaTek Wireless_Device                              | 4        | 3.92%   |
| Intel AX201 Bluetooth                                 | 4        | 3.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 3.92%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 2.94%   |
| Realtek Bluetooth 5.3 Radio                           | 2        | 1.96%   |
| Intel Bluetooth Device                                | 2        | 1.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 1.96%   |
| IMC Networks Wireless_Device                          | 2        | 1.96%   |
| TP-Link TP-Link Bluetooth USB Adapter                 | 1        | 0.98%   |
| Realtek 802.11ac WLAN Adapter                         | 1        | 0.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 0.98%   |
| IMC Networks Bluetooth Radio                          | 1        | 0.98%   |
| IMC Networks Bluetooth Device                         | 1        | 0.98%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 0.98%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth           | 1        | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 0.98%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.98%   |
| ASUS Bluetooth Radio                                  | 1        | 0.98%   |
| ASUS Bluetooth Device                                 | 1        | 0.98%   |
| Unknown                                               | 1        | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 148      | 36.63%  |
| Nvidia                                       | 111      | 27.48%  |
| AMD                                          | 93       | 23.02%  |
| C-Media Electronics                          | 10       | 2.48%   |
| ASUSTek Computer                             | 8        | 1.98%   |
| Micro Star International                     | 6        | 1.49%   |
| Giga-Byte Technology                         | 3        | 0.74%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.5%    |
| TTGK Technology                              | 2        | 0.5%    |
| XMOS                                         | 1        | 0.25%   |
| VIA Technologies                             | 1        | 0.25%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.25%   |
| Texas Instruments                            | 1        | 0.25%   |
| Sony                                         | 1        | 0.25%   |
| Samsung Electronics                          | 1        | 0.25%   |
| Medeli Electronics                           | 1        | 0.25%   |
| Kingston Technology                          | 1        | 0.25%   |
| JMTek                                        | 1        | 0.25%   |
| Generalplus Technology                       | 1        | 0.25%   |
| Fry's Electronics                            | 1        | 0.25%   |
| Focusrite-Novation                           | 1        | 0.25%   |
| EGO SYStems                                  | 1        | 0.25%   |
| DigiTech                                     | 1        | 0.25%   |
| Corsair                                      | 1        | 0.25%   |
| Conexant Systems                             | 1        | 0.25%   |
| BEHRINGER International                      | 1        | 0.25%   |
| Barco Display Systems                        | 1        | 0.25%   |
| B & W Group                                  | 1        | 0.25%   |
| Audient                                      | 1        | 0.25%   |
| ASRock                                       | 1        | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 28       | 5.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21       | 4.49%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17       | 3.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16       | 3.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16       | 3.42%   |
| Intel 200 Series PCH HD Audio                                              | 15       | 3.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14       | 2.99%   |
| Nvidia GA102 High Definition Audio Controller                              | 10       | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 2.14%   |
| Intel Alder Lake-S HD Audio Controller                                     | 10       | 2.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 2.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10       | 2.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 1.92%   |
| ASUSTek Computer USB Audio                                                 | 8        | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 1.5%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 1.5%    |
| Micro Star International USB Audio                                         | 6        | 1.28%   |
| Intel Raptor Lake High Definition Audio Controller                         | 6        | 1.28%   |
| Nvidia High Definition Audio Controller                                    | 5        | 1.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.07%   |
| C-Media Electronics USB Audio Device                                       | 5        | 1.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.07%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 1.07%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.07%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 0.85%   |
| Nvidia TU102 High Definition Audio Controller                              | 4        | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.85%   |
| Nvidia AD102 High Definition Audio Controller                              | 4        | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Samsung Electronics        | 83       | 64.34%  |
| Unknown                    | 6        | 4.65%   |
| Crucial                    | 6        | 4.65%   |
| Team                       | 5        | 3.88%   |
| SK hynix                   | 5        | 3.88%   |
| Kingston                   | 5        | 3.88%   |
| G.Skill                    | 4        | 3.1%    |
| Unknown                    | 4        | 3.1%    |
| KLEVV                      | 2        | 1.55%   |
| Shenzhen Jinge Information | 1        | 0.78%   |
| PUSKILL                    | 1        | 0.78%   |
| PNY                        | 1        | 0.78%   |
| Imation                    | 1        | 0.78%   |
| GeIL                       | 1        | 0.78%   |
| Essencore Limited          | 1        | 0.78%   |
| Corsair                    | 1        | 0.78%   |
| Apacer                     | 1        | 0.78%   |
| A-DATA Technology          | 1        | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s   | 8        | 5.52%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s    | 7        | 4.83%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s   | 5        | 3.45%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 4        | 2.76%   |
| Unknown                                                | 4        | 2.76%   |
| Samsung RAM M378B5273EB0-CK0 8GB DIMM DDR3 1800MT/s    | 3        | 2.07%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 2.07%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s | 3        | 2.07%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s   | 3        | 2.07%   |
| Samsung RAM M378A2K43EB1-CWE 16GB DIMM DDR4 3933MT/s   | 3        | 2.07%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s    | 3        | 2.07%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s    | 3        | 2.07%   |
| Samsung RAM M378A1G43EB1-CPB 8192MB DIMM DDR4 2667MT/s | 3        | 2.07%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s           | 2        | 1.38%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s  | 2        | 1.38%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s    | 2        | 1.38%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s    | 2        | 1.38%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s    | 2        | 1.38%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s    | 2        | 1.38%   |
| Samsung RAM M378A2K43BB1-CRC 16GB DIMM DDR4 3200MT/s   | 2        | 1.38%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 3000MT/s   | 2        | 1.38%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s    | 2        | 1.38%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s    | 2        | 1.38%   |
| Samsung RAM M378A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s    | 2        | 1.38%   |
| Samsung RAM M323R4GA3BB0-CQKOL 32GB DIMM DDR5 4800MT/s | 2        | 1.38%   |
| Crucial RAM CT16G56C46U5.M8G1 16GB DIMM DDR5 5600MT/s  | 2        | 1.38%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s            | 1        | 0.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 1        | 0.69%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 1        | 0.69%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 1        | 0.69%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s     | 1        | 0.69%   |
| Team RAM TEAMGROUP-UD4-2666 4GB DIMM DDR4              | 1        | 0.69%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s    | 1        | 0.69%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s     | 1        | 0.69%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2666MT/s     | 1        | 0.69%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 1        | 0.69%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.69%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 1        | 0.69%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s  | 1        | 0.69%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1        | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 77       | 61.6%   |
| DDR3    | 30       | 24%     |
| DDR5    | 15       | 12%     |
| SDRAM   | 2        | 1.6%    |
| Unknown | 1        | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 113      | 90.4%   |
| SODIMM | 12       | 9.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 43       | 32.09%  |
| 16384 | 36       | 26.87%  |
| 32768 | 25       | 18.66%  |
| 4096  | 22       | 16.42%  |
| 2048  | 3        | 2.24%   |
| 49152 | 2        | 1.49%   |
| 65536 | 1        | 0.75%   |
| 24576 | 1        | 0.75%   |
| 1024  | 1        | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 32       | 22.86%  |
| 1600    | 20       | 14.29%  |
| 2667    | 9        | 6.43%   |
| 2133    | 8        | 5.71%   |
| 5600    | 7        | 5%      |
| 3500    | 7        | 5%      |
| 2400    | 7        | 5%      |
| 4800    | 5        | 3.57%   |
| 3466    | 4        | 2.86%   |
| 3066    | 4        | 2.86%   |
| 2666    | 4        | 2.86%   |
| 1800    | 4        | 2.86%   |
| 3933    | 3        | 2.14%   |
| 3400    | 3        | 2.14%   |
| 3266    | 3        | 2.14%   |
| 3000    | 3        | 2.14%   |
| 1867    | 3        | 2.14%   |
| 1866    | 3        | 2.14%   |
| 2933    | 2        | 1.43%   |
| 1333    | 2        | 1.43%   |
| Unknown | 2        | 1.43%   |
| 6400    | 1        | 0.71%   |
| 5200    | 1        | 0.71%   |
| 4802    | 1        | 0.71%   |
| 4000    | 1        | 0.71%   |
| 3733    | 1        | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 4        | 44.44%  |
| Seiko Epson         | 2        | 22.22%  |
| Samsung Electronics | 2        | 22.22%  |
| Brother Industries  | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson L360 Series    | 1        | 11.11%  |
| Seiko Epson ET-4850 Series | 1        | 11.11%  |
| Samsung M203x Series       | 1        | 11.11%  |
| Samsung CLX-3180 Series    | 1        | 11.11%  |
| Canon PIXMA MP280          | 1        | 11.11%  |
| Canon MF4800 Series        | 1        | 11.11%  |
| Canon G4010 series         | 1        | 11.11%  |
| Canon E560 series          | 1        | 11.11%  |
| Brother DCP-T310           | 1        | 11.11%  |

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
| Logitech                      | 5        | 27.78%  |
| Sunplus Innovation Technology | 4        | 22.22%  |
| Samsung Electronics           | 2        | 11.11%  |
| Microdia                      | 2        | 11.11%  |
| lihappe8                      | 2        | 11.11%  |
| Z-Star Microelectronics       | 1        | 5.56%   |
| Realtek Semiconductor         | 1        | 5.56%   |
| LG Electronics                | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Sunplus DICOTA 4K                                     | 2        | 11.11%  |
| Samsung Galaxy series, misc. (MTP mode)               | 2        | 11.11%  |
| Logitech Webcam C110                                  | 2        | 11.11%  |
| lihappe8 USB 2.0 Camera                               | 2        | 11.11%  |
| Z-Star Vimicro USB Camera (Altair)                    | 1        | 5.56%   |
| Sunplus Sandberg USB Webcam Pro                       | 1        | 5.56%   |
| Sunplus Hy-Usb2.0-1*MIC                               | 1        | 5.56%   |
| Realtek FULL HD 1080P Webcam                          | 1        | 5.56%   |
| Microdia Lenovo EasyCamera                            | 1        | 5.56%   |
| Microdia HP Webcam                                    | 1        | 5.56%   |
| Logitech StreamCam                                    | 1        | 5.56%   |
| Logitech HD Webcam C510                               | 1        | 5.56%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 5.56%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 5.56%   |

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
| 0     | 194      | 83.26%  |
| 1     | 29       | 12.45%  |
| 2     | 5        | 2.15%   |
| 4     | 2        | 0.86%   |
| 3     | 2        | 0.86%   |
| 5     | 1        | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 19       | 38%     |
| Unassigned class         | 9        | 18%     |
| Net/wireless             | 7        | 14%     |
| Net/ethernet             | 5        | 10%     |
| Communication controller | 4        | 8%      |
| Network                  | 2        | 4%      |
| Camera                   | 2        | 4%      |
| Storage/raid             | 1        | 2%      |
| Sound                    | 1        | 2%      |


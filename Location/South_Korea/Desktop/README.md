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

Total: 275

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 40       | 18.6%   |
| Ubuntu 22.04                 | 23       | 10.7%   |
| Ubuntu 18.04                 | 21       | 9.77%   |
| Ubuntu 20.10                 | 4        | 1.86%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.86%   |
| Fedora 39                    | 4        | 1.86%   |
| ArcoLinux Rolling            | 4        | 1.86%   |
| Arch Rolling                 | 4        | 1.86%   |
| Arch                         | 4        | 1.86%   |
| Ubuntu 19.10                 | 3        | 1.4%    |
| Ubuntu 16.04                 | 3        | 1.4%    |
| Pop!_OS 22.04                | 3        | 1.4%    |
| HamoniKR 7.0                 | 3        | 1.4%    |
| Fedora 37                    | 3        | 1.4%    |
| Fedora 32                    | 3        | 1.4%    |
| Debian 12                    | 3        | 1.4%    |
| CentOS 7                     | 3        | 1.4%    |
| Zorin 15                     | 2        | 0.93%   |
| Ubuntu Unity 16.04           | 2        | 0.93%   |
| Ubuntu 23.04                 | 2        | 0.93%   |
| Ubuntu 21.10                 | 2        | 0.93%   |
| TmaxOS 21.12.02              | 2        | 0.93%   |
| RHEL 8                       | 2        | 0.93%   |
| OpenMandriva 5.0             | 2        | 0.93%   |
| OpenMandriva 4.3             | 2        | 0.93%   |
| OpenMandriva 23.03           | 2        | 0.93%   |
| OpenMandriva 23.01           | 2        | 0.93%   |
| No1 2018                     | 2        | 0.93%   |
| Linux Mint 21.1              | 2        | 0.93%   |
| Linux Mint 20.2              | 2        | 0.93%   |
| Linux Mint 20.1              | 2        | 0.93%   |
| Linux Mint 20                | 2        | 0.93%   |
| Linux Mint 19.3              | 2        | 0.93%   |
| HamoniKR 6.0                 | 2        | 0.93%   |
| Fedora 36                    | 2        | 0.93%   |
| Fedora 34                    | 2        | 0.93%   |
| Debian 11                    | 2        | 0.93%   |
| Debian 10                    | 2        | 0.93%   |
| Chrome OS                    | 2        | 0.93%   |
| Zorin 16                     | 1        | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 102      | 48.57%  |
| Fedora       | 17       | 8.1%    |
| Linux Mint   | 10       | 4.76%   |
| OpenMandriva | 9        | 4.29%   |
| Debian       | 8        | 3.81%   |
| Arch         | 8        | 3.81%   |
| HamoniKR     | 7        | 3.33%   |
| openSUSE     | 5        | 2.38%   |
| Pop!_OS      | 4        | 1.9%    |
| CentOS       | 4        | 1.9%    |
| ArcoLinux    | 4        | 1.9%    |
| Zorin        | 3        | 1.43%   |
| Rocky Linux  | 3        | 1.43%   |
| No1 Linux    | 3        | 1.43%   |
| Kubuntu      | 3        | 1.43%   |
| Ubuntu Unity | 2        | 0.95%   |
| TmaxOS       | 2        | 0.95%   |
| RHEL         | 2        | 0.95%   |
| Chrome OS    | 2        | 0.95%   |
| ROSA         | 1        | 0.48%   |
| Nobara       | 1        | 0.48%   |
| MX           | 1        | 0.48%   |
| Manjaro      | 1        | 0.48%   |
| Lubuntu      | 1        | 0.48%   |
| KDE neon     | 1        | 0.48%   |
| Kali         | 1        | 0.48%   |
| Gooroom      | 1        | 0.48%   |
| Endless      | 1        | 0.48%   |
| EndeavourOS  | 1        | 0.48%   |
| Devuan       | 1        | 0.48%   |
| BlackPanther | 1        | 0.48%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.4.0-29-generic        | 4        | 1.7%    |
| 5.15.0-43-generic       | 4        | 1.7%    |
| 6.5.6-300.fc39.x86_64   | 3        | 1.28%   |
| 5.4.0-26-generic        | 3        | 1.28%   |
| 5.19.0-38-generic       | 3        | 1.28%   |
| 5.15.0-71-generic       | 3        | 1.28%   |
| 5.15.0-41-generic       | 3        | 1.28%   |
| 6.6.2-desktop-1omv2390  | 2        | 0.85%   |
| 6.5.9-arch2-1           | 2        | 0.85%   |
| 6.2.6-desktop-1omv2390  | 2        | 0.85%   |
| 6.1.1-desktop-1omv2290  | 2        | 0.85%   |
| 6.1.0-16-amd64          | 2        | 0.85%   |
| 5.8.0-48-generic        | 2        | 0.85%   |
| 5.8.0-38-generic        | 2        | 0.85%   |
| 5.4.0-56-generic        | 2        | 0.85%   |
| 5.4.0-54-generic        | 2        | 0.85%   |
| 5.4.0-52-generic        | 2        | 0.85%   |
| 5.4.0-47-generic        | 2        | 0.85%   |
| 5.4.0-42-generic        | 2        | 0.85%   |
| 5.4.0-37-generic        | 2        | 0.85%   |
| 5.3.0-51-generic        | 2        | 0.85%   |
| 5.3.0-40-generic        | 2        | 0.85%   |
| 5.19.0-46-generic       | 2        | 0.85%   |
| 5.16.7-desktop-1omv4003 | 2        | 0.85%   |
| 5.15.0-89-generic       | 2        | 0.85%   |
| 5.15.0-58-generic       | 2        | 0.85%   |
| 5.15.0-53-generic       | 2        | 0.85%   |
| 5.15.0-52-generic       | 2        | 0.85%   |
| 5.15.0-50-generic       | 2        | 0.85%   |
| 5.14.0-0.bpo.2-amd64    | 2        | 0.85%   |
| 5.13.0-21-generic       | 2        | 0.85%   |
| 4.19.0-14-amd64         | 2        | 0.85%   |
| 4.18.0-25-generic       | 2        | 0.85%   |
| 4.15.0-91-generic       | 2        | 0.85%   |
| 6.8.1-arch1-1           | 1        | 0.43%   |
| 6.7.9-200.fc39.x86_64   | 1        | 0.43%   |
| 6.7.5                   | 1        | 0.43%   |
| 6.7.4-arch1-1           | 1        | 0.43%   |
| 6.7.11-200.fc39.x86_64  | 1        | 0.43%   |
| 6.6.8-arch1-1           | 1        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 35       | 15.35%  |
| 5.15.0  | 28       | 12.28%  |
| 4.15.0  | 18       | 7.89%   |
| 5.8.0   | 13       | 5.7%    |
| 4.18.0  | 10       | 4.39%   |
| 5.3.0   | 9        | 3.95%   |
| 6.2.0   | 6        | 2.63%   |
| 5.19.0  | 6        | 2.63%   |
| 5.14.0  | 5        | 2.19%   |
| 5.13.0  | 5        | 2.19%   |
| 6.1.0   | 4        | 1.75%   |
| 6.5.6   | 3        | 1.32%   |
| 5.0.0   | 3        | 1.32%   |
| 4.19.0  | 3        | 1.32%   |
| 6.6.2   | 2        | 0.88%   |
| 6.5.9   | 2        | 0.88%   |
| 6.5.0   | 2        | 0.88%   |
| 6.2.6   | 2        | 0.88%   |
| 6.1.1   | 2        | 0.88%   |
| 5.16.7  | 2        | 0.88%   |
| 5.11.0  | 2        | 0.88%   |
| 5.10.0  | 2        | 0.88%   |
| 4.13.0  | 2        | 0.88%   |
| 3.10.0  | 2        | 0.88%   |
| 6.8.1   | 1        | 0.44%   |
| 6.7.9   | 1        | 0.44%   |
| 6.7.5   | 1        | 0.44%   |
| 6.7.4   | 1        | 0.44%   |
| 6.7.11  | 1        | 0.44%   |
| 6.6.8   | 1        | 0.44%   |
| 6.6.1   | 1        | 0.44%   |
| 6.5.8   | 1        | 0.44%   |
| 6.5.7   | 1        | 0.44%   |
| 6.5.4   | 1        | 0.44%   |
| 6.5.13  | 1        | 0.44%   |
| 6.4.6   | 1        | 0.44%   |
| 6.4.14  | 1        | 0.44%   |
| 6.2.8   | 1        | 0.44%   |
| 6.2.2   | 1        | 0.44%   |
| 6.1.8   | 1        | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 16.44%  |
| 5.15    | 30       | 13.33%  |
| 4.15    | 19       | 8.44%   |
| 5.8     | 16       | 7.11%   |
| 6.1     | 12       | 5.33%   |
| 4.18    | 11       | 4.89%   |
| 6.5     | 10       | 4.44%   |
| 6.2     | 10       | 4.44%   |
| 5.3     | 9        | 4%      |
| 5.14    | 8        | 3.56%   |
| 5.19    | 7        | 3.11%   |
| 6.0     | 6        | 2.67%   |
| 5.13    | 5        | 2.22%   |
| 5.10    | 5        | 2.22%   |
| 6.6     | 4        | 1.78%   |
| 5.16    | 4        | 1.78%   |
| 5.11    | 4        | 1.78%   |
| 5.0     | 4        | 1.78%   |
| 4.19    | 4        | 1.78%   |
| 6.7     | 3        | 1.33%   |
| 6.4     | 2        | 0.89%   |
| 5.6     | 2        | 0.89%   |
| 5.18    | 2        | 0.89%   |
| 4.9     | 2        | 0.89%   |
| 4.13    | 2        | 0.89%   |
| 3.10    | 2        | 0.89%   |
| 6.8     | 1        | 0.44%   |
| 5.9     | 1        | 0.44%   |
| 5.7     | 1        | 0.44%   |
| 5.12    | 1        | 0.44%   |
| 4.17    | 1        | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 206      | 99.52%  |
| i686   | 1        | 0.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 108      | 50.7%   |
| Unknown         | 38       | 17.84%  |
| KDE5            | 29       | 13.62%  |
| X-Cinnamon      | 13       | 6.1%    |
| XFCE            | 9        | 4.23%   |
| Cinnamon        | 3        | 1.41%   |
| Unity           | 2        | 0.94%   |
| TOS:GNOME       | 2        | 0.94%   |
| KDE             | 2        | 0.94%   |
| MATE            | 1        | 0.47%   |
| LXDE            | 1        | 0.47%   |
| KDE4            | 1        | 0.47%   |
| Hyprland        | 1        | 0.47%   |
| GNOME Flashback | 1        | 0.47%   |
| GNOME Classic   | 1        | 0.47%   |
| Deepin          | 1        | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 143      | 67.45%  |
| Wayland | 36       | 16.98%  |
| Unknown | 23       | 10.85%  |
| Tty     | 10       | 4.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 111      | 53.11%  |
| GDM3    | 30       | 14.35%  |
| GDM     | 25       | 11.96%  |
| SDDM    | 24       | 11.48%  |
| LightDM | 15       | 7.18%   |
| TDM     | 3        | 1.44%   |
| SLiM    | 1        | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ko_KR   | 93       | 44.5%   |
| en_US   | 77       | 36.84%  |
| Unknown | 29       | 13.88%  |
| C       | 3        | 1.44%   |
| en_GB   | 2        | 0.96%   |
| ru_RU   | 1        | 0.48%   |
| id_ID   | 1        | 0.48%   |
| fr_FR   | 1        | 0.48%   |
| en_CA   | 1        | 0.48%   |
| en_AU   | 1        | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 117      | 55.71%  |
| BIOS | 93       | 44.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 161      | 75.94%  |
| Btrfs   | 19       | 8.96%   |
| Unknown | 9        | 4.25%   |
| Xfs     | 8        | 3.77%   |
| Overlay | 5        | 2.36%   |
| Zfs     | 4        | 1.89%   |
| Tmpfs   | 4        | 1.89%   |
| Rootfs  | 1        | 0.47%   |
| F2fs    | 1        | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 104      | 49.76%  |
| GPT     | 91       | 43.54%  |
| MBR     | 14       | 6.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 81.82%  |
| Yes       | 38       | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 67.94%  |
| Yes       | 67       | 32.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 46       | 22.22%  |
| ASUSTek Computer    | 46       | 22.22%  |
| ASRock              | 35       | 16.91%  |
| MSI                 | 22       | 10.63%  |
| Samsung Electronics | 7        | 3.38%   |
| ECS                 | 7        | 3.38%   |
| Unknown             | 7        | 3.38%   |
| Lenovo              | 6        | 2.9%    |
| Hewlett-Packard     | 6        | 2.9%    |
| Dell                | 4        | 1.93%   |
| Foxconn             | 3        | 1.45%   |
| LattePanda          | 2        | 0.97%   |
| Huanan              | 2        | 0.97%   |
| WTM                 | 1        | 0.48%   |
| SZQFTX              | 1        | 0.48%   |
| PCPartner           | 1        | 0.48%   |
| PC Partner Limited  | 1        | 0.48%   |
| INRUKO              | 1        | 0.48%   |
| Google              | 1        | 0.48%   |
| Fujitsu             | 1        | 0.48%   |
| ELSKY               | 1        | 0.48%   |
| ECS2                | 1        | 0.48%   |
| Biostar             | 1        | 0.48%   |
| AZW                 | 1        | 0.48%   |
| ASRockRack          | 1        | 0.48%   |
| AMD                 | 1        | 0.48%   |
| Alienware           | 1        | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 7        | 3.38%   |
| Samsung DeskTop System               | 5        | 2.42%   |
| MSI MS-7B89                          | 4        | 1.93%   |
| Gigabyte B75M-D3H                    | 3        | 1.45%   |
| ASUS PRIME B350M-A                   | 3        | 1.45%   |
| ASUS PRIME A320M-K                   | 3        | 1.45%   |
| MSI MS-7D91                          | 2        | 0.97%   |
| MSI MS-7D42                          | 2        | 0.97%   |
| MSI MS-7C94                          | 2        | 0.97%   |
| LattePanda Alpha                     | 2        | 0.97%   |
| Gigabyte TRX40 AORUS XTREME          | 2        | 0.97%   |
| Gigabyte H81M-DS2V                   | 2        | 0.97%   |
| Gigabyte B75M-D3V                    | 2        | 0.97%   |
| Gigabyte B360M-D3H                   | 2        | 0.97%   |
| Gigabyte AB350-Gaming 3              | 2        | 0.97%   |
| Gigabyte A320M-S2H                   | 2        | 0.97%   |
| ASUS Z170-A                          | 2        | 0.97%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 2        | 0.97%   |
| ASUS ROG STRIX B650E-E GAMING WIFI   | 2        | 0.97%   |
| ASUS EX-A320M-GAMING                 | 2        | 0.97%   |
| ASUS All Series                      | 2        | 0.97%   |
| ASRock H81M-DGS R2.0                 | 2        | 0.97%   |
| ASRock AB350M Pro4                   | 2        | 0.97%   |
| WTM W-N95                            | 1        | 0.48%   |
| SZQFTX MN56                          | 1        | 0.48%   |
| Samsung 500T8A/500S8A/500T9A/500S9A  | 1        | 0.48%   |
| Samsung 400T7A/400S7A                | 1        | 0.48%   |
| PCPartner DREAMSYS                   | 1        | 0.48%   |
| PC Partner Limited S70BS.AH3511      | 1        | 0.48%   |
| MSI MS-7D76                          | 1        | 0.48%   |
| MSI MS-7D74                          | 1        | 0.48%   |
| MSI MS-7C75                          | 1        | 0.48%   |
| MSI MS-7C51                          | 1        | 0.48%   |
| MSI MS-7C02                          | 1        | 0.48%   |
| MSI MS-7B85                          | 1        | 0.48%   |
| MSI MS-7B24                          | 1        | 0.48%   |
| MSI MS-7A74                          | 1        | 0.48%   |
| MSI MS-7A37                          | 1        | 0.48%   |
| MSI MS-7A20                          | 1        | 0.48%   |
| MSI MS-7A15                          | 1        | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS PRIME                      | 15       | 7.25%   |
| ASUS ROG                        | 8        | 3.86%   |
| Unknown                         | 7        | 3.38%   |
| Samsung DeskTop                 | 5        | 2.42%   |
| MSI MS-7B89                     | 4        | 1.93%   |
| Lenovo ThinkStation             | 3        | 1.45%   |
| Gigabyte TRX40                  | 3        | 1.45%   |
| Gigabyte B75M-D3H               | 3        | 1.45%   |
| MSI MS-7D91                     | 2        | 0.97%   |
| MSI MS-7D42                     | 2        | 0.97%   |
| MSI MS-7C94                     | 2        | 0.97%   |
| LattePanda Alpha                | 2        | 0.97%   |
| Gigabyte Z390                   | 2        | 0.97%   |
| Gigabyte X570                   | 2        | 0.97%   |
| Gigabyte H81M-DS2V              | 2        | 0.97%   |
| Gigabyte B75M-D3V               | 2        | 0.97%   |
| Gigabyte B360M-D3H              | 2        | 0.97%   |
| Gigabyte AB350-Gaming           | 2        | 0.97%   |
| Gigabyte A320M-S2H              | 2        | 0.97%   |
| Dell Vostro                     | 2        | 0.97%   |
| Dell OptiPlex                   | 2        | 0.97%   |
| ASUS Z170-A                     | 2        | 0.97%   |
| ASUS TUF                        | 2        | 0.97%   |
| ASUS EX-A320M-GAMING            | 2        | 0.97%   |
| ASUS All                        | 2        | 0.97%   |
| ASRock Z390                     | 2        | 0.97%   |
| ASRock Z370                     | 2        | 0.97%   |
| ASRock H81M-DGS                 | 2        | 0.97%   |
| ASRock FM2A88M-HD+              | 2        | 0.97%   |
| ASRock AB350M                   | 2        | 0.97%   |
| WTM W-N95                       | 1        | 0.48%   |
| SZQFTX MN56                     | 1        | 0.48%   |
| Samsung 500T8A                  | 1        | 0.48%   |
| Samsung 400T7A                  | 1        | 0.48%   |
| PCPartner DREAMSYS              | 1        | 0.48%   |
| PC Partner Limited S70BS.AH3511 | 1        | 0.48%   |
| MSI MS-7D76                     | 1        | 0.48%   |
| MSI MS-7D74                     | 1        | 0.48%   |
| MSI MS-7C75                     | 1        | 0.48%   |
| MSI MS-7C51                     | 1        | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 22       | 10.63%  |
| 2017 | 21       | 10.14%  |
| 2020 | 17       | 8.21%   |
| 2012 | 17       | 8.21%   |
| 2022 | 16       | 7.73%   |
| 2021 | 13       | 6.28%   |
| 2019 | 13       | 6.28%   |
| 2015 | 13       | 6.28%   |
| 2013 | 13       | 6.28%   |
| 2014 | 12       | 5.8%    |
| 2016 | 9        | 4.35%   |
| 2023 | 8        | 3.86%   |
| 2009 | 8        | 3.86%   |
| 2011 | 6        | 2.9%    |
| 2010 | 5        | 2.42%   |
| 2008 | 5        | 2.42%   |
| 2007 | 5        | 2.42%   |
| 2006 | 2        | 0.97%   |
| 2024 | 1        | 0.48%   |
| 2005 | 1        | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 207      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 202      | 97.12%  |
| Enabled  | 6        | 2.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 206      | 99.52%  |
| Yes  | 1        | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 42       | 20%     |
| 16.01-24.0      | 36       | 17.14%  |
| 64.01-256.0     | 34       | 16.19%  |
| 32.01-64.0      | 30       | 14.29%  |
| 4.01-8.0        | 29       | 13.81%  |
| 3.01-4.0        | 22       | 10.48%  |
| 24.01-32.0      | 9        | 4.29%   |
| 1.01-2.0        | 4        | 1.9%    |
| More than 256.0 | 2        | 0.95%   |
| 2.01-3.0        | 2        | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 66       | 29.33%  |
| 2.01-3.0   | 46       | 20.44%  |
| 4.01-8.0   | 40       | 17.78%  |
| 3.01-4.0   | 40       | 17.78%  |
| 8.01-16.0  | 13       | 5.78%   |
| 0.51-1.0   | 11       | 4.89%   |
| 32.01-64.0 | 4        | 1.78%   |
| 16.01-24.0 | 3        | 1.33%   |
| 24.01-32.0 | 1        | 0.44%   |
| 0.01-0.5   | 1        | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 77       | 36.32%  |
| 2      | 68       | 32.08%  |
| 3      | 28       | 13.21%  |
| 4      | 17       | 8.02%   |
| 5      | 10       | 4.72%   |
| 6      | 6        | 2.83%   |
| 7      | 2        | 0.94%   |
| 10     | 1        | 0.47%   |
| 9      | 1        | 0.47%   |
| 8      | 1        | 0.47%   |
| 0      | 1        | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 149      | 71.63%  |
| Yes       | 59       | 28.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 206      | 99.52%  |
| No        | 1        | 0.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 59.62%  |
| Yes       | 84       | 40.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 57.35%  |
| Yes       | 90       | 42.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| South Korea | 207      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Seoul           | 16       | 7.17%   |
| Seongnam-si     | 16       | 7.17%   |
| Yongin-si       | 10       | 4.48%   |
| Suwon           | 8        | 3.59%   |
| Busan           | 6        | 2.69%   |
| Pyeongtaek-si   | 5        | 2.24%   |
| Dongjak-gu      | 5        | 2.24%   |
| Cheonan         | 5        | 2.24%   |
| Yongsan-gu      | 4        | 1.79%   |
| Incheon         | 4        | 1.79%   |
| Hwaseong-si     | 4        | 1.79%   |
| Gwanak-gu       | 4        | 1.79%   |
| Gangseo-gu      | 4        | 1.79%   |
| Gangbuk-gu      | 4        | 1.79%   |
| Daejeon         | 4        | 1.79%   |
| Bucheon-si      | 4        | 1.79%   |
| Anyang-si       | 4        | 1.79%   |
| Yangcheon-gu    | 3        | 1.35%   |
| Seo-gu          | 3        | 1.35%   |
| Nam-gu          | 3        | 1.35%   |
| Jungnang-gu     | 3        | 1.35%   |
| Gyeonggi-do     | 3        | 1.35%   |
| Guri-si         | 3        | 1.35%   |
| Goyang-si       | 3        | 1.35%   |
| Gangnam-gu      | 3        | 1.35%   |
| Ansan-si        | 3        | 1.35%   |
| Yeongdeungpo-gu | 2        | 0.9%    |
| Uiwang          | 2        | 0.9%    |
| Uiseong-gun     | 2        | 0.9%    |
| Siheung-si      | 2        | 0.9%    |
| Seongdong-gu    | 2        | 0.9%    |
| Seongbuk-gu     | 2        | 0.9%    |
| Sejong          | 2        | 0.9%    |
| Pocheon-si      | 2        | 0.9%    |
| Paju            | 2        | 0.9%    |
| Osan            | 2        | 0.9%    |
| Mokpo           | 2        | 0.9%    |
| Icheon-si       | 2        | 0.9%    |
| Gwangmyeong-si  | 2        | 0.9%    |
| Guro-gu         | 2        | 0.9%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 70       | 102    | 18.18%  |
| WDC                          | 67       | 114    | 17.4%   |
| Seagate                      | 52       | 84     | 13.51%  |
| SanDisk                      | 26       | 33     | 6.75%   |
| Toshiba                      | 25       | 44     | 6.49%   |
| Crucial                      | 25       | 31     | 6.49%   |
| SK hynix                     | 13       | 18     | 3.38%   |
| Unknown                      | 12       | 15     | 3.12%   |
| Hitachi                      | 12       | 13     | 3.12%   |
| HGST                         | 8        | 9      | 2.08%   |
| Transcend                    | 6        | 6      | 1.56%   |
| A-DATA Technology            | 6        | 6      | 1.56%   |
| Silicon Motion               | 5        | 6      | 1.3%    |
| Micron Technology            | 5        | 6      | 1.3%    |
| Plextor                      | 4        | 8      | 1.04%   |
| TAMMUZ                       | 3        | 4      | 0.78%   |
| SPCC                         | 3        | 3      | 0.78%   |
| RevuAhn                      | 3        | 5      | 0.78%   |
| Intel                        | 3        | 3      | 0.78%   |
| China                        | 3        | 3      | 0.78%   |
| Seagate Technology           | 2        | 3      | 0.52%   |
| OCZ                          | 2        | 3      | 0.52%   |
| Micron/Crucial Technology    | 2        | 2      | 0.52%   |
| LITEON                       | 2        | 2      | 0.52%   |
| Unknown                      | 2        | 2      | 0.52%   |
| ZOTAC                        | 1        | 1      | 0.26%   |
| Team                         | 1        | 1      | 0.26%   |
| Shenzhen Longsys Electronics | 1        | 2      | 0.26%   |
| Realtek Semiconductor        | 1        | 1      | 0.26%   |
| Ramsta                       | 1        | 2      | 0.26%   |
| QNIX                         | 1        | 1      | 0.26%   |
| Phison Electronics           | 1        | 1      | 0.26%   |
| Phison                       | 1        | 2      | 0.26%   |
| PHINOCOM                     | 1        | 1      | 0.26%   |
| OSCOO                        | 1        | 1      | 0.26%   |
| Netac                        | 1        | 1      | 0.26%   |
| MARVELL                      | 1        | 1      | 0.26%   |
| LaCie                        | 1        | 1      | 0.26%   |
| KIOXIA                       | 1        | 4      | 0.26%   |
| KingSpec                     | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Toshiba DT01ACA300 3TB                             | 8        | 1.79%   |
| Crucial CT500MX500SSD1 500GB                       | 7        | 1.57%   |
| Seagate ST500DM002-1BD142 500GB                    | 6        | 1.34%   |
| Crucial CT240BX500SSD1 240GB                       | 6        | 1.34%   |
| WDC WD5000AAKX-00ERMA0 500GB                       | 4        | 0.89%   |
| Toshiba DT01ACA200 2TB                             | 4        | 0.89%   |
| SK hynix SHGP31-500GM 500GB                        | 4        | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB                     | 4        | 0.89%   |
| SanDisk SD8SBAT128G1122 128GB SSD                  | 4        | 0.89%   |
| Samsung SSD 850 EVO 120GB                          | 4        | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4        | 0.89%   |
| WDC WD40EZRZ-00GXCB0 4TB                           | 3        | 0.67%   |
| WDC WD40EZAZ-00SF3B0 4TB                           | 3        | 0.67%   |
| WDC WD40EFRX-68WT0N0 4TB                           | 3        | 0.67%   |
| WDC WD3200AAJS-00L7A0 320GB                        | 3        | 0.67%   |
| WDC WD20EARX-00PASB0 2TB                           | 3        | 0.67%   |
| WDC WD10EZEX-22MFCA0 1TB                           | 3        | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 3        | 0.67%   |
| Unknown SD/MMC/MS PRO 128GB                        | 3        | 0.67%   |
| Toshiba DT01ACA050 500GB                           | 3        | 0.67%   |
| Seagate ST3500418AS 500GB                          | 3        | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB                     | 3        | 0.67%   |
| Seagate ST1000DM003-1CH162 1TB                     | 3        | 0.67%   |
| Samsung SSD 980 1TB                                | 3        | 0.67%   |
| Samsung SSD 850 PRO 256GB                          | 3        | 0.67%   |
| Samsung SSD 850 EVO 250GB                          | 3        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3        | 0.67%   |
| Crucial CT275MX300SSD4 275GB                       | 3        | 0.67%   |
| Crucial CT250MX200SSD1 250GB                       | 3        | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 2        | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 2        | 0.45%   |
| WDC WD10EZEX-00WN4A0 1TB                           | 2        | 0.45%   |
| Unknown NVMe SSD Drive 512GB                       | 2        | 0.45%   |
| Transcend TS240GSSD220S 240GB                      | 2        | 0.45%   |
| Toshiba THNSNJ128GCSU 128GB SSD                    | 2        | 0.45%   |
| Toshiba HDWD130 3TB                                | 2        | 0.45%   |
| Toshiba HDWD120 2TB                                | 2        | 0.45%   |
| TAMMUZ SSD 128GB                                   | 2        | 0.45%   |
| SK hynix SHPP41-2000GM 2TB                         | 2        | 0.45%   |
| SK hynix SHGP31-2000GM 2TB                         | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 59       | 98     | 34.91%  |
| Seagate             | 50       | 79     | 29.59%  |
| Toshiba             | 21       | 33     | 12.43%  |
| Hitachi             | 12       | 13     | 7.1%    |
| Samsung Electronics | 11       | 13     | 6.51%   |
| HGST                | 8        | 9      | 4.73%   |
| Unknown             | 3        | 4      | 1.78%   |
| MARVELL             | 1        | 1      | 0.59%   |
| LaCie               | 1        | 1      | 0.59%   |
| JMicron Technology  | 1        | 1      | 0.59%   |
| Hewlett-Packard     | 1        | 1      | 0.59%   |
| Fujitsu             | 1        | 1      | 0.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 39     | 22.14%  |
| Crucial             | 24       | 30     | 17.14%  |
| SanDisk             | 22       | 27     | 15.71%  |
| WDC                 | 10       | 14     | 7.14%   |
| Transcend           | 6        | 6      | 4.29%   |
| A-DATA Technology   | 5        | 5      | 3.57%   |
| Toshiba             | 4        | 11     | 2.86%   |
| TAMMUZ              | 3        | 4      | 2.14%   |
| SPCC                | 3        | 3      | 2.14%   |
| Seagate             | 3        | 4      | 2.14%   |
| RevuAhn             | 3        | 5      | 2.14%   |
| Plextor             | 3        | 7      | 2.14%   |
| China               | 3        | 3      | 2.14%   |
| SK hynix            | 2        | 4      | 1.43%   |
| OCZ                 | 2        | 3      | 1.43%   |
| LITEON              | 2        | 2      | 1.43%   |
| Intel               | 2        | 2      | 1.43%   |
| Unknown             | 2        | 2      | 1.43%   |
| Ramsta              | 1        | 2      | 0.71%   |
| QNIX                | 1        | 1      | 0.71%   |
| PHINOCOM            | 1        | 1      | 0.71%   |
| OSCOO               | 1        | 1      | 0.71%   |
| Netac               | 1        | 1      | 0.71%   |
| Micron Technology   | 1        | 1      | 0.71%   |
| KingSpec            | 1        | 1      | 0.71%   |
| Imation             | 1        | 2      | 0.71%   |
| GLOWAY              | 1        | 1      | 0.71%   |
| Biostar             | 1        | 1      | 0.71%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 128      | 254    | 39.38%  |
| SSD     | 119      | 183    | 36.62%  |
| NVMe    | 71       | 111    | 21.85%  |
| Unknown | 4        | 5      | 1.23%   |
| MMC     | 3        | 3      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 177      | 429    | 67.82%  |
| NVMe | 71       | 111    | 27.2%   |
| SAS  | 10       | 13     | 3.83%   |
| MMC  | 3        | 3      | 1.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 134      | 221    | 49.63%  |
| 0.51-1.0   | 58       | 85     | 21.48%  |
| 1.01-2.0   | 31       | 42     | 11.48%  |
| 3.01-4.0   | 23       | 43     | 8.52%   |
| 2.01-3.0   | 12       | 18     | 4.44%   |
| 4.01-10.0  | 8        | 18     | 2.96%   |
| 10.01-20.0 | 4        | 10     | 1.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 49       | 23.11%  |
| 501-1000       | 38       | 17.92%  |
| 251-500        | 36       | 16.98%  |
| More than 3000 | 23       | 10.85%  |
| 1001-2000      | 22       | 10.38%  |
| 2001-3000      | 16       | 7.55%   |
| 21-50          | 10       | 4.72%   |
| 51-100         | 8        | 3.77%   |
| 1-20           | 6        | 2.83%   |
| Unknown        | 4        | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 76       | 34.23%  |
| 101-250        | 36       | 16.22%  |
| 21-50          | 29       | 13.06%  |
| 51-100         | 25       | 11.26%  |
| 251-500        | 17       | 7.66%   |
| 501-1000       | 14       | 6.31%   |
| More than 3000 | 9        | 4.05%   |
| 2001-3000      | 7        | 3.15%   |
| 1001-2000      | 5        | 2.25%   |
| Unknown        | 4        | 1.8%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 2        | 2      | 10.53%  |
| WDC WD7500AACS-00D6B0 752GB                                   | 1        | 1      | 5.26%   |
| WDC WD5000AAKX-75U6AA0 500GB                                  | 1        | 1      | 5.26%   |
| WDC WD5000AAKX-001CA0 500GB                                   | 1        | 1      | 5.26%   |
| WDC WD40EZRZ-00WN9B0 4TB                                      | 1        | 1      | 5.26%   |
| WDC WD3200AAJS-00L7A0 320GB                                   | 1        | 2      | 5.26%   |
| WDC WD1600BEVT-22A23T0 160GB                                  | 1        | 1      | 5.26%   |
| WDC WD1001FALS-00J7B1 1TB                                     | 1        | 1      | 5.26%   |
| Seagate ST500DM009-2F110A 500GB                               | 1        | 1      | 5.26%   |
| Seagate ST4000DM000-1F2168 4TB                                | 1        | 1      | 5.26%   |
| Seagate ST3500418AS 500GB                                     | 1        | 1      | 5.26%   |
| Seagate ST1000DM003-1CH162 1TB                                | 1        | 1      | 5.26%   |
| Samsung Electronics HD160JJ 160GB                             | 1        | 1      | 5.26%   |
| Ramsta SSD S600 480GB                                         | 1        | 2      | 5.26%   |
| LITEON LMH-128V2M 128GB SSD                                   | 1        | 1      | 5.26%   |
| Hitachi HTS543216L9A300 160GB                                 | 1        | 1      | 5.26%   |
| HGST HDN726060ALE610 6TB                                      | 1        | 1      | 5.26%   |
| A-DATA Technology SU650 240GB SSD                             | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 36.84%  |
| Seagate             | 4        | 4      | 21.05%  |
| Samsung Electronics | 3        | 3      | 15.79%  |
| Ramsta              | 1        | 2      | 5.26%   |
| LITEON              | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |
| HGST                | 1        | 1      | 5.26%   |
| A-DATA Technology   | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 50%     |
| Seagate             | 4        | 4      | 28.57%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| HGST                | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 15     | 70.59%  |
| SSD  | 3        | 4      | 17.65%  |
| NVMe | 2        | 2      | 11.76%  |

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
| Detected | 120      | 315    | 52.86%  |
| Works    | 90       | 220    | 39.65%  |
| Malfunc  | 17       | 21     | 7.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 132      | 40.62%  |
| AMD                          | 68       | 20.92%  |
| Samsung Electronics          | 38       | 11.69%  |
| ASMedia Technology           | 22       | 6.77%   |
| SK hynix                     | 11       | 3.38%   |
| JMicron Technology           | 11       | 3.38%   |
| Silicon Motion               | 6        | 1.85%   |
| SanDisk                      | 5        | 1.54%   |
| Phison Electronics           | 5        | 1.54%   |
| Micron Technology            | 4        | 1.23%   |
| Marvell Technology Group     | 4        | 1.23%   |
| Seagate Technology           | 3        | 0.92%   |
| Micron/Crucial Technology    | 3        | 0.92%   |
| VIA Technologies             | 1        | 0.31%   |
| Solidigm                     | 1        | 0.31%   |
| Shenzhen Longsys Electronics | 1        | 0.31%   |
| Realtek Semiconductor        | 1        | 0.31%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.31%   |
| LSI Logic / Symbios Logic    | 1        | 0.31%   |
| Lite-On Technology           | 1        | 0.31%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.31%   |
| KIOXIA                       | 1        | 0.31%   |
| INNOGRIT                     | 1        | 0.31%   |
| Broadcom / LSI               | 1        | 0.31%   |
| Biwin Storage Technology     | 1        | 0.31%   |
| ADATA Technology             | 1        | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 40       | 10.03%  |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 21       | 5.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20       | 5.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17       | 4.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 3.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 3.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10       | 2.51%   |
| AMD FCH SATA Controller D                                                               | 10       | 2.51%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 2.51%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 2.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.26%   |
| AMD 600 Series Chipset SATA Controller                                                  | 9        | 2.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.01%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 2.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 7        | 1.75%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 1.75%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 1.5%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.25%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 1.25%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 4        | 1%      |
| Intel Raptor Lake SATA AHCI Controller                                                  | 4        | 1%      |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 1%      |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 1%      |
| AMD FCH IDE Controller                                                                  | 4        | 1%      |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.75%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 0.75%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 0.75%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.5%    |
| Seagate FireCuda/IronWolf 510 SSD                                                       | 2        | 0.5%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.5%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2        | 0.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.5%    |
| Micron 2210 NVMe SSD [Cobain]                                                           | 2        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 175      | 59.32%  |
| NVMe | 73       | 24.75%  |
| IDE  | 37       | 12.54%  |
| RAID | 8        | 2.71%   |
| SAS  | 2        | 0.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 135      | 65.22%  |
| AMD    | 72       | 34.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-3570 CPU @ 3.40GHz               | 9        | 4.35%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 6        | 2.9%    |
| Intel Core i5-8500 CPU @ 3.00GHz               | 5        | 2.42%   |
| Intel Pentium CPU G4400 @ 3.30GHz              | 4        | 1.93%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 4        | 1.93%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 4        | 1.93%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 4        | 1.93%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 3        | 1.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 1.45%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 1.45%   |
| AMD Ryzen 9 7900X 12-Core Processor            | 3        | 1.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 3        | 1.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 1.45%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 3        | 1.45%   |
| Intel Pentium 4 CPU 3.00GHz                    | 2        | 0.97%   |
| Intel Core i9-10900K CPU @ 3.70GHz             | 2        | 0.97%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 2        | 0.97%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 0.97%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 0.97%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 2        | 0.97%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 2        | 0.97%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 2        | 0.97%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 2        | 0.97%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 0.97%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 2        | 0.97%   |
| Intel Core i5 CPU 760 @ 2.80GHz                | 2        | 0.97%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz          | 2        | 0.97%   |
| Intel 13th Gen Core i9-13900K                  | 2        | 0.97%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 2        | 0.97%   |
| AMD Ryzen 9 7900 12-Core Processor             | 2        | 0.97%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 2        | 0.97%   |
| AMD Ryzen 5 7600 6-Core Processor              | 2        | 0.97%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 0.97%   |
| Intel Xeon W-3275M CPU @ 2.50GHz               | 1        | 0.48%   |
| Intel Xeon W-2133 CPU @ 3.60GHz                | 1        | 0.48%   |
| Intel Xeon CPU X5680 @ 3.33GHz                 | 1        | 0.48%   |
| Intel Xeon CPU X3430 @ 2.40GHz                 | 1        | 0.48%   |
| Intel Xeon CPU E5450 @ 3.00GHz                 | 1        | 0.48%   |
| Intel Xeon CPU E5-2699 v3 @ 2.30GHz            | 1        | 0.48%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz            | 1        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 39       | 18.84%  |
| AMD Ryzen 5             | 25       | 12.08%  |
| Intel Core i7           | 17       | 8.21%   |
| Intel Xeon              | 14       | 6.76%   |
| Other                   | 13       | 6.28%   |
| Intel Core i3           | 11       | 5.31%   |
| AMD Ryzen 9             | 11       | 5.31%   |
| AMD Ryzen 7             | 11       | 5.31%   |
| Intel Pentium           | 9        | 4.35%   |
| Intel Celeron           | 8        | 3.86%   |
| Intel Core i9           | 7        | 3.38%   |
| AMD Ryzen Threadripper  | 7        | 3.38%   |
| Intel Core 2 Quad       | 6        | 2.9%    |
| AMD Ryzen 3             | 5        | 2.42%   |
| Intel Pentium Gold      | 2        | 0.97%   |
| Intel Pentium Dual-Core | 2        | 0.97%   |
| Intel Pentium 4         | 2        | 0.97%   |
| Intel Core m3           | 2        | 0.97%   |
| Intel Core 2 Duo        | 2        | 0.97%   |
| AMD A8                  | 2        | 0.97%   |
| AMD A10                 | 2        | 0.97%   |
| Intel Core 2            | 1        | 0.48%   |
| AMD Ryzen Embedded      | 1        | 0.48%   |
| AMD Ryzen 7 PRO         | 1        | 0.48%   |
| AMD Ryzen 5 PRO         | 1        | 0.48%   |
| AMD Phenom II X6        | 1        | 0.48%   |
| AMD Phenom              | 1        | 0.48%   |
| AMD FX                  | 1        | 0.48%   |
| AMD Athlon II X2        | 1        | 0.48%   |
| AMD Athlon 64 X2        | 1        | 0.48%   |
| AMD Athlon              | 1        | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 70       | 33.82%  |
| 2      | 42       | 20.29%  |
| 6      | 41       | 19.81%  |
| 8      | 19       | 9.18%   |
| 16     | 10       | 4.83%   |
| 12     | 8        | 3.86%   |
| 10     | 4        | 1.93%   |
| 32     | 3        | 1.45%   |
| 24     | 2        | 0.97%   |
| 1      | 2        | 0.97%   |
| 64     | 1        | 0.48%   |
| 28     | 1        | 0.48%   |
| 22     | 1        | 0.48%   |
| 20     | 1        | 0.48%   |
| 18     | 1        | 0.48%   |
| 14     | 1        | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 206      | 99.52%  |
| 2      | 1        | 0.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 121      | 58.45%  |
| 1      | 86       | 41.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 205      | 98.56%  |
| Unknown        | 3        | 1.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 56       | 26.54%  |
| 0x306c3    | 18       | 8.53%   |
| 0x306a9    | 17       | 8.06%   |
| 0x906ea    | 8        | 3.79%   |
| 0x906e9    | 7        | 3.32%   |
| 0x506e3    | 6        | 2.84%   |
| 0x306f2    | 5        | 2.37%   |
| 0x1067a    | 5        | 2.37%   |
| 0x08001138 | 5        | 2.37%   |
| 0x906ed    | 4        | 1.9%    |
| 0x206a7    | 4        | 1.9%    |
| 0x106e5    | 4        | 1.9%    |
| 0x08101016 | 4        | 1.9%    |
| 0x0800820d | 4        | 1.9%    |
| 0x08001137 | 4        | 1.9%    |
| 0xb0671    | 3        | 1.42%   |
| 0xa0655    | 3        | 1.42%   |
| 0x6fb      | 3        | 1.42%   |
| 0x0a20120a | 3        | 1.42%   |
| 0x08701021 | 3        | 1.42%   |
| 0x906ec    | 2        | 0.95%   |
| 0x90672    | 2        | 0.95%   |
| 0x806e9    | 2        | 0.95%   |
| 0x50654    | 2        | 0.95%   |
| 0x0a601203 | 2        | 0.95%   |
| 0x0a601201 | 2        | 0.95%   |
| 0x0a50000d | 2        | 0.95%   |
| 0x0a201016 | 2        | 0.95%   |
| 0x08600106 | 2        | 0.95%   |
| 0x08108109 | 2        | 0.95%   |
| 0x0810100b | 2        | 0.95%   |
| 0xf49      | 1        | 0.47%   |
| 0xa0671    | 1        | 0.47%   |
| 0x906eb    | 1        | 0.47%   |
| 0x90675    | 1        | 0.47%   |
| 0x406f1    | 1        | 0.47%   |
| 0x306e4    | 1        | 0.47%   |
| 0x306d4    | 1        | 0.47%   |
| 0x30678    | 1        | 0.47%   |
| 0x0a601206 | 1        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 28       | 13.53%  |
| KabyLake         | 27       | 13.04%  |
| IvyBridge        | 20       | 9.66%   |
| Zen              | 19       | 9.18%   |
| Unknown          | 19       | 9.18%   |
| Zen 3            | 13       | 6.28%   |
| Skylake          | 13       | 6.28%   |
| Zen 2            | 11       | 5.31%   |
| Zen+             | 8        | 3.86%   |
| Penryn           | 8        | 3.86%   |
| CometLake        | 5        | 2.42%   |
| SandyBridge      | 4        | 1.93%   |
| Nehalem          | 4        | 1.93%   |
| Core             | 4        | 1.93%   |
| Alderlake Hybrid | 4        | 1.93%   |
| K10              | 3        | 1.45%   |
| Steamroller      | 2        | 0.97%   |
| Silvermont       | 2        | 0.97%   |
| Piledriver       | 2        | 0.97%   |
| NetBurst         | 2        | 0.97%   |
| Gracemont        | 2        | 0.97%   |
| Broadwell        | 2        | 0.97%   |
| Westmere         | 1        | 0.48%   |
| K8 Hammer        | 1        | 0.48%   |
| K10 Llano        | 1        | 0.48%   |
| Icelake          | 1        | 0.48%   |
| Goldmont plus    | 1        | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 103      | 43.83%  |
| Intel             | 75       | 31.91%  |
| AMD               | 55       | 23.4%   |
| ASPEED Technology | 2        | 0.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 4.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 4.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 3.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8        | 3.31%   |
| AMD Raphael                                                                 | 8        | 3.31%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 7        | 2.89%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 2.07%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 1.65%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.65%   |
| Intel HD Graphics 510                                                       | 4        | 1.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 1.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.24%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.24%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 1.24%   |
| Nvidia GF108 [GeForce GT 440]                                               | 3        | 1.24%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 3        | 1.24%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 3        | 1.24%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 1.24%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.24%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 3        | 1.24%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.83%   |
| Nvidia TU102 [TITAN RTX]                                                    | 2        | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.83%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.83%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.83%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 0.83%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.83%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 2        | 0.83%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 0.83%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 0.83%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2        | 0.83%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 0.83%   |
| Nvidia G98 [GeForce 9300 GS]                                                | 2        | 0.83%   |
| Intel HD Graphics 630                                                       | 2        | 0.83%   |
| Intel HD Graphics 530                                                       | 2        | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| 1 x Nvidia       | 90       | 42.86%  |
| 1 x Intel        | 58       | 27.62%  |
| 1 x AMD          | 43       | 20.48%  |
| AMD + Nvidia     | 7        | 3.33%   |
| 2 x AMD          | 4        | 1.9%    |
| Intel + Nvidia   | 3        | 1.43%   |
| 2 x Nvidia       | 1        | 0.48%   |
| Nvidia + ASPEED  | 1        | 0.48%   |
| Intel + AMD      | 1        | 0.48%   |
| 1 x ASPEED       | 1        | 0.48%   |
| AMD + 2 x Nvidia | 1        | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 139      | 66.19%  |
| Proprietary | 65       | 30.95%  |
| Unknown     | 6        | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 91       | 42.92%  |
| 1.01-2.0   | 26       | 12.26%  |
| 0.51-1.0   | 25       | 11.79%  |
| 7.01-8.0   | 16       | 7.55%   |
| 0.01-0.5   | 14       | 6.6%    |
| 3.01-4.0   | 12       | 5.66%   |
| 8.01-16.0  | 12       | 5.66%   |
| 5.01-6.0   | 6        | 2.83%   |
| 16.01-24.0 | 5        | 2.36%   |
| 2.01-3.0   | 4        | 1.89%   |
| 4.01-5.0   | 1        | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 43       | 20.87%  |
| Samsung Electronics  | 34       | 16.5%   |
| Unknown              | 10       | 4.85%   |
| Dell                 | 10       | 4.85%   |
| AOC                  | 10       | 4.85%   |
| Hewlett-Packard      | 9        | 4.37%   |
| Philips              | 8        | 3.88%   |
| LG Electronics       | 7        | 3.4%    |
| PRISM+               | 5        | 2.43%   |
| OUT                  | 5        | 2.43%   |
| BenQ                 | 5        | 2.43%   |
| Unknown (ADE)        | 4        | 1.94%   |
| RTK                  | 4        | 1.94%   |
| JCH                  | 3        | 1.46%   |
| OOO                  | 2        | 0.97%   |
| MStar                | 2        | 0.97%   |
| Lenovo               | 2        | 0.97%   |
| JRY                  | 2        | 0.97%   |
| HXM                  | 2        | 0.97%   |
| Ancor Communications | 2        | 0.97%   |
| ALP                  | 2        | 0.97%   |
| Yamaha               | 1        | 0.49%   |
| XUE                  | 1        | 0.49%   |
| Xiangye              | 1        | 0.49%   |
| ViewSonic            | 1        | 0.49%   |
| UPV                  | 1        | 0.49%   |
| TopView              | 1        | 0.49%   |
| TGL                  | 1        | 0.49%   |
| TCH                  | 1        | 0.49%   |
| SiS                  | 1        | 0.49%   |
| SGT                  | 1        | 0.49%   |
| SANYO                | 1        | 0.49%   |
| RAT                  | 1        | 0.49%   |
| Pixio                | 1        | 0.49%   |
| PBK                  | 1        | 0.49%   |
| ORM                  | 1        | 0.49%   |
| NME                  | 1        | 0.49%   |
| NEW                  | 1        | 0.49%   |
| MON                  | 1        | 0.49%   |
| MiTAC                | 1        | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 5        | 2.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4        | 1.86%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                         | 3        | 1.4%    |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1210x680mm 54.6-inch | 2        | 0.93%   |
| PRISM+ ULTRON 3547UC INN0035 2560x1080 820x345mm 35.0-inch             | 2        | 0.93%   |
| PRISM+ CK27FC INN0027 1920x1080 598x336mm 27.0-inch                    | 2        | 0.93%   |
| OOO Monitor OOO0001 1920x1080 345x194mm 15.6-inch                      | 2        | 0.93%   |
| JRY Digital JRY0215 1920x1080 340x255mm 16.7-inch                      | 2        | 0.93%   |
| JCH UDEA Monitor JCHE321 1920x1080 443x249mm 20.0-inch                 | 2        | 0.93%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch              | 2        | 0.93%   |
| Goldstar HDR QHD GSM5B96 2560x1440 698x392mm 31.5-inch                 | 2        | 0.93%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 2        | 0.93%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 2        | 0.93%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                       | 2        | 0.93%   |
| Yamaha YSP-1600 YMH331A 1920x540                                       | 1        | 0.47%   |
| XUE Type-C XUE1600 2560x1600 360x190mm 16.0-inch                       | 1        | 0.47%   |
| Xiangye N2408HZ XYE2700 1920x1080 597x336mm 27.0-inch                  | 1        | 0.47%   |
| ViewSonic VX3218 Series VSC7032 2560x1440 698x393mm 31.5-inch          | 1        | 0.47%   |
| UPV UP-M30W1 UPV0001 2560x1600 641x401mm 29.8-inch                     | 1        | 0.47%   |
| Unknown LCD Monitor STD 32Q-HDMI 2560x1440                             | 1        | 0.47%   |
| Unknown LCD Monitor SKYDATA S.P.A. LG TV 1920x1080                     | 1        | 0.47%   |
| Unknown LCD Monitor SAMSUNG 3286x1080                                  | 1        | 0.47%   |
| Unknown LCD Monitor OUT Digital 3200x1080                              | 1        | 0.47%   |
| Unknown LCD Monitor ORC DIGITAL MONITOR 1280x1024                      | 1        | 0.47%   |
| Unknown LCD Monitor NQM NewQ System 1280x1024                          | 1        | 0.47%   |
| Unknown LCD Monitor INN ULTRON 3479UC 4880x2560                        | 1        | 0.47%   |
| Unknown LCD Monitor ICB ULTRON4079 3840x2160                           | 1        | 0.47%   |
| Unknown LCD Monitor Digital Projection Limited DP                      | 1        | 0.47%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                             | 1        | 0.47%   |
| Unknown LCD Monitor Chuntex/CTX NL27 3840x2160                         | 1        | 0.47%   |
| Unknown (ADE) TSLED22D ADEB22D 1920x1080 477x268mm 21.5-inch           | 1        | 0.47%   |
| Unknown (ADE) TLED20DHS ADE2000 1600x900 443x249mm 20.0-inch           | 1        | 0.47%   |
| Unknown (ADE) P2400HDT ADE00F0 1920x1080 521x293mm 23.5-inch           | 1        | 0.47%   |
| Unknown (ADE) N2413 ADS LED ADE2413 1920x1080 521x293mm 23.5-inch      | 1        | 0.47%   |
| TopView TOPSYNC TOP049B 2560x1440 597x336mm 27.0-inch                  | 1        | 0.47%   |
| TGL TGL A190 TGL0908 1280x1024 376x301mm 19.0-inch                     | 1        | 0.47%   |
| TCH HDMI TCH5600 1920x1080 344x194mm 15.5-inch                         | 1        | 0.47%   |
| SiS DV 24 TV SIS0330 1920x1080 930x530mm 42.1-inch                     | 1        | 0.47%   |
| SGT HX156U SGT1560 3840x2160 345x194mm 15.6-inch                       | 1        | 0.47%   |
| SANYO LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch                | 1        | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 103      | 51.24%  |
| 3840x2160 (4K)     | 27       | 13.43%  |
| 2560x1440 (QHD)    | 21       | 10.45%  |
| 1280x1024 (SXGA)   | 11       | 5.47%   |
| 1920x1200 (WUXGA)  | 7        | 3.48%   |
| 1680x1050 (WSXGA+) | 6        | 2.99%   |
| 3440x1440          | 4        | 1.99%   |
| 2560x1080          | 4        | 1.99%   |
| Unknown            | 3        | 1.49%   |
| 3840x1080          | 2        | 1%      |
| 2560x1600          | 2        | 1%      |
| 1600x900 (HD+)     | 2        | 1%      |
| 1440x900 (WXGA+)   | 2        | 1%      |
| 4880x2560          | 1        | 0.5%    |
| 3840x1600          | 1        | 0.5%    |
| 3286x1080          | 1        | 0.5%    |
| 3200x1080          | 1        | 0.5%    |
| 1920x540           | 1        | 0.5%    |
| 1600x1200          | 1        | 0.5%    |
| 1280x960           | 1        | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 16.75%  |
| 27      | 33       | 16.26%  |
| 21      | 23       | 11.33%  |
| 23      | 20       | 9.85%   |
| 24      | 19       | 9.36%   |
| 31      | 10       | 4.93%   |
| 16      | 10       | 4.93%   |
| 19      | 7        | 3.45%   |
| 20      | 6        | 2.96%   |
| 34      | 4        | 1.97%   |
| 84      | 3        | 1.48%   |
| 29      | 3        | 1.48%   |
| 22      | 3        | 1.48%   |
| 18      | 3        | 1.48%   |
| 17      | 3        | 1.48%   |
| 42      | 2        | 0.99%   |
| 40      | 2        | 0.99%   |
| 39      | 2        | 0.99%   |
| 35      | 2        | 0.99%   |
| 28      | 2        | 0.99%   |
| 25      | 2        | 0.99%   |
| 15      | 2        | 0.99%   |
| 72      | 1        | 0.49%   |
| 52      | 1        | 0.49%   |
| 49      | 1        | 0.49%   |
| 48      | 1        | 0.49%   |
| 46      | 1        | 0.49%   |
| 37      | 1        | 0.49%   |
| 33      | 1        | 0.49%   |
| 32      | 1        | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 67       | 34.01%  |
| 401-500     | 34       | 17.26%  |
| Unknown     | 34       | 17.26%  |
| 601-700     | 17       | 8.63%   |
| 351-400     | 11       | 5.58%   |
| 301-350     | 11       | 5.58%   |
| 801-900     | 7        | 3.55%   |
| 701-800     | 6        | 3.05%   |
| 1501-2000   | 4        | 2.03%   |
| 1001-1500   | 4        | 2.03%   |
| 901-1000    | 2        | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 115      | 60.85%  |
| Unknown | 31       | 16.4%   |
| 16/10   | 13       | 6.88%   |
| 5/4     | 9        | 4.76%   |
| 4/3     | 8        | 4.23%   |
| 21/9    | 8        | 4.23%   |
| 32/9    | 3        | 1.59%   |
| 6/5     | 1        | 0.53%   |
| 3/2     | 1        | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 51       | 25.5%   |
| 301-350        | 35       | 17.5%   |
| Unknown        | 34       | 17%     |
| 351-500        | 22       | 11%     |
| 151-200        | 17       | 8.5%    |
| 251-300        | 11       | 5.5%    |
| 501-1000       | 9        | 4.5%    |
| 131-140        | 6        | 3%      |
| More than 1000 | 5        | 2.5%    |
| 141-150        | 4        | 2%      |
| 111-120        | 3        | 1.5%    |
| 101-110        | 3        | 1.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 90       | 46.63%  |
| 101-120 | 42       | 21.76%  |
| Unknown | 34       | 17.62%  |
| 121-160 | 19       | 9.84%   |
| 1-50    | 4        | 2.07%   |
| 161-240 | 4        | 2.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 166      | 79.81%  |
| 2     | 26       | 12.5%   |
| 0     | 15       | 7.21%   |
| 3     | 1        | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 151      | 55.31%  |
| Intel                           | 77       | 28.21%  |
| Qualcomm Atheros                | 9        | 3.3%    |
| MediaTek                        | 9        | 3.3%    |
| Ralink Technology               | 4        | 1.47%   |
| Broadcom                        | 4        | 1.47%   |
| Ralink                          | 3        | 1.1%    |
| Marvell Technology Group        | 2        | 0.73%   |
| Exar                            | 2        | 0.73%   |
| Broadcom Limited                | 2        | 0.73%   |
| ASIX Electronics                | 2        | 0.73%   |
| Aquantia                        | 2        | 0.73%   |
| Wilocity                        | 1        | 0.37%   |
| Qualcomm Atheros Communications | 1        | 0.37%   |
| PEAK-System Technik             | 1        | 0.37%   |
| Kinesis                         | 1        | 0.37%   |
| D-Link                          | 1        | 0.37%   |
| American Megatrends             | 1        | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 124      | 37.92%  |
| Realtek RTL8125 2.5GbE Controller                                      | 15       | 4.59%   |
| Intel Wi-Fi 6 AX200                                                    | 13       | 3.98%   |
| Intel Ethernet Controller I225-V                                       | 9        | 2.75%   |
| Intel I211 Gigabit Network Connection                                  | 8        | 2.45%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 2.45%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 1.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5        | 1.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5        | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 1.22%   |
| Realtek 802.11ac NIC                                                   | 4        | 1.22%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 4        | 1.22%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 1.22%   |
| Intel Ethernet Controller X550                                         | 4        | 1.22%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 3        | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3        | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.92%   |
| Intel Ethernet Controller I226-V                                       | 3        | 0.92%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.92%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.92%   |
| Intel Ethernet Connection (2) I218-LM                                  | 3        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 0.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 3        | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.61%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 2        | 0.61%   |
| Realtek 802.11n NIC                                                    | 2        | 0.61%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 0.61%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2        | 0.61%   |
| MediaTek WiFi                                                          | 2        | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2        | 0.61%   |
| Intel Wireless 3165                                                    | 2        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.61%   |
| Intel Ethernet Connection (11) I219-V                                  | 2        | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 0.61%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.61%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 0.61%   |
| Exar XR21V1410 USB-UART IC                                             | 2        | 0.61%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 2        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 39       | 43.33%  |
| Realtek Semiconductor           | 26       | 28.89%  |
| MediaTek                        | 9        | 10%     |
| Ralink Technology               | 4        | 4.44%   |
| Ralink                          | 3        | 3.33%   |
| Qualcomm Atheros                | 3        | 3.33%   |
| Broadcom                        | 2        | 2.22%   |
| Wilocity                        | 1        | 1.11%   |
| Qualcomm Atheros Communications | 1        | 1.11%   |
| D-Link                          | 1        | 1.11%   |
| Broadcom Limited                | 1        | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 13       | 14.44%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 5        | 5.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 5        | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4        | 4.44%   |
| Realtek 802.11ac NIC                                          | 4        | 4.44%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 4        | 4.44%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 3        | 3.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 3        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3        | 3.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 3        | 3.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 2.22%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 2        | 2.22%   |
| Realtek 802.11n NIC                                           | 2        | 2.22%   |
| Ralink MT7601U Wireless Adapter                               | 2        | 2.22%   |
| MediaTek WiFi                                                 | 2        | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2        | 2.22%   |
| Intel Wireless 3165                                           | 2        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2        | 2.22%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 2        | 2.22%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter            | 1        | 1.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1        | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1        | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1        | 1.11%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 1        | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 1.11%   |
| Ralink RT5572 Wireless Adapter                                | 1        | 1.11%   |
| Ralink RT5372 Wireless Adapter                                | 1        | 1.11%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                     | 1        | 1.11%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1        | 1.11%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                          | 1        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1        | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                               | 1        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 1.11%   |
| Intel Wireless 8265 / 8275                                    | 1        | 1.11%   |
| Intel Wireless 7265                                           | 1        | 1.11%   |
| Intel Wireless 7260                                           | 1        | 1.11%   |
| Intel Wireless 3160                                           | 1        | 1.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 1        | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 146      | 65.77%  |
| Intel                    | 60       | 27.03%  |
| Qualcomm Atheros         | 6        | 2.7%    |
| Marvell Technology Group | 2        | 0.9%    |
| Broadcom                 | 2        | 0.9%    |
| ASIX Electronics         | 2        | 0.9%    |
| Aquantia                 | 2        | 0.9%    |
| Broadcom Limited         | 1        | 0.45%   |
| American Megatrends      | 1        | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 124      | 53.22%  |
| Realtek RTL8125 2.5GbE Controller                                              | 15       | 6.44%   |
| Intel Ethernet Controller I225-V                                               | 9        | 3.86%   |
| Intel I211 Gigabit Network Connection                                          | 8        | 3.43%   |
| Intel Ethernet Connection (2) I219-V                                           | 8        | 3.43%   |
| Intel Ethernet Connection (7) I219-V                                           | 6        | 2.58%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 1.72%   |
| Intel Ethernet Controller X550                                                 | 4        | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 1.29%   |
| Intel Ethernet Controller I226-V                                               | 3        | 1.29%   |
| Intel Ethernet Connection I217-LM                                              | 3        | 1.29%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 1.29%   |
| Intel Ethernet Connection (2) I218-LM                                          | 3        | 1.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 1.29%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 2        | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2        | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2        | 0.86%   |
| Intel Ethernet Connection (11) I219-V                                          | 2        | 0.86%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 0.86%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2        | 0.86%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.86%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1        | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1        | 0.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.43%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1        | 0.43%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1        | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1        | 0.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.43%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1        | 0.43%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 1        | 0.43%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.43%   |
| Intel 82575EB Gigabit Network Connection                                       | 1        | 0.43%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 1        | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.43%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                                | 1        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 206      | 70.07%  |
| WiFi     | 84       | 28.57%  |
| Modem    | 3        | 1.02%   |
| Unknown  | 1        | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 177      | 81.94%  |
| WiFi     | 39       | 18.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 127      | 61.35%  |
| 2     | 67       | 32.37%  |
| 3     | 11       | 5.31%   |
| 5     | 1        | 0.48%   |
| 4     | 1        | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 207      | 99.52%  |
| Yes  | 1        | 0.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 36       | 40%     |
| Cambridge Silicon Radio | 27       | 30%     |
| Realtek Semiconductor   | 11       | 12.22%  |
| IMC Networks            | 4        | 4.44%   |
| MediaTek                | 3        | 3.33%   |
| Broadcom                | 3        | 3.33%   |
| ASUSTek Computer        | 3        | 3.33%   |
| Foxconn / Hon Hai       | 2        | 2.22%   |
| TP-Link                 | 1        | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 27       | 30%     |
| Intel AX200 Bluetooth                                 | 11       | 12.22%  |
| Realtek Bluetooth Radio                               | 10       | 11.11%  |
| Intel Bluetooth wireless interface                    | 5        | 5.56%   |
| Intel AX211 Bluetooth                                 | 5        | 5.56%   |
| Intel AX210 Bluetooth                                 | 5        | 5.56%   |
| MediaTek Wireless_Device                              | 3        | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 3.33%   |
| Intel AX201 Bluetooth                                 | 3        | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 2.22%   |
| IMC Networks Wireless_Device                          | 2        | 2.22%   |
| TP-Link UB500 Adapter                                 | 1        | 1.11%   |
| Realtek Bluetooth 5.3 Radio                           | 1        | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.11%   |
| Intel Bluetooth Device                                | 1        | 1.11%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.11%   |
| IMC Networks Bluetooth Device                         | 1        | 1.11%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 1.11%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth           | 1        | 1.11%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.11%   |
| ASUS Bluetooth Radio                                  | 1        | 1.11%   |
| ASUS Bluetooth Device                                 | 1        | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 132      | 37.18%  |
| Nvidia                                       | 98       | 27.61%  |
| AMD                                          | 83       | 23.38%  |
| C-Media Electronics                          | 8        | 2.25%   |
| ASUSTek Computer                             | 5        | 1.41%   |
| Micro Star International                     | 4        | 1.13%   |
| Giga-Byte Technology                         | 3        | 0.85%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.56%   |
| TTGK Technology                              | 2        | 0.56%   |
| XMOS                                         | 1        | 0.28%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.28%   |
| Texas Instruments                            | 1        | 0.28%   |
| Sony                                         | 1        | 0.28%   |
| Samsung Electronics                          | 1        | 0.28%   |
| Medeli Electronics                           | 1        | 0.28%   |
| Kingston Technology                          | 1        | 0.28%   |
| JMTek                                        | 1        | 0.28%   |
| Generalplus Technology                       | 1        | 0.28%   |
| Fry's Electronics                            | 1        | 0.28%   |
| Focusrite-Novation                           | 1        | 0.28%   |
| EGO SYStems                                  | 1        | 0.28%   |
| DigiTech                                     | 1        | 0.28%   |
| Corsair                                      | 1        | 0.28%   |
| Conexant Systems                             | 1        | 0.28%   |
| BEHRINGER International                      | 1        | 0.28%   |
| Audient                                      | 1        | 0.28%   |
| ASRock                                       | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 25       | 6.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19       | 4.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17       | 4.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 3.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14       | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 3.14%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 2.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 2.66%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 2.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 2.42%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10       | 2.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 2.17%   |
| Nvidia GA102 High Definition Audio Controller                              | 8        | 1.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 1.69%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 1.69%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.21%   |
| ASUSTek Computer USB Audio                                                 | 5        | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.21%   |
| Nvidia TU102 High Definition Audio Controller                              | 4        | 0.97%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.97%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.97%   |
| Micro Star International USB Audio                                         | 4        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.97%   |
| C-Media Electronics USB Audio Device                                       | 4        | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4        | 0.97%   |
| AMD FCH Azalia Controller                                                  | 4        | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.72%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Samsung Electronics        | 74       | 66.07%  |
| Unknown                    | 6        | 5.36%   |
| SK hynix                   | 5        | 4.46%   |
| Crucial                    | 5        | 4.46%   |
| Team                       | 4        | 3.57%   |
| Kingston                   | 4        | 3.57%   |
| Unknown                    | 4        | 3.57%   |
| KLEVV                      | 2        | 1.79%   |
| G.Skill                    | 2        | 1.79%   |
| Shenzhen Jinge Information | 1        | 0.89%   |
| PUSKILL                    | 1        | 0.89%   |
| Imation                    | 1        | 0.89%   |
| GeIL                       | 1        | 0.89%   |
| Corsair                    | 1        | 0.89%   |
| A-DATA Technology          | 1        | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                       | 7        | 5.51%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                        | 7        | 5.51%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s                       | 5        | 3.94%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s                        | 4        | 3.15%   |
| Unknown                                                                    | 4        | 3.15%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s                        | 3        | 2.36%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                        | 3        | 2.36%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                        | 3        | 2.36%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s                       | 3        | 2.36%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s                        | 3        | 2.36%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2667MT/s                        | 3        | 2.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                               | 2        | 1.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                      | 2        | 1.57%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s                        | 2        | 1.57%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                        | 2        | 1.57%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s                        | 2        | 1.57%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s                     | 2        | 1.57%   |
| Samsung RAM M378A2K43EB1-CWE 16GB DIMM DDR4 3200MT/s                       | 2        | 1.57%   |
| Samsung RAM M378A2K43BB1-CRC 16GB DIMM DDR4 3200MT/s                       | 2        | 1.57%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s                       | 2        | 1.57%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s                        | 2        | 1.57%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                        | 2        | 1.57%   |
| Samsung RAM M378A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s                        | 2        | 1.57%   |
| Crucial RAM CT16G56C46U5.M8G1 16GB DIMM DDR5 5600MT/s                      | 2        | 1.57%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                                | 1        | 0.79%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                       | 1        | 0.79%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                    | 1        | 0.79%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                       | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3200MT/s                         | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s                        | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s                         | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2666MT/s                         | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1067MT/s                         | 1        | 0.79%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s                       | 1        | 0.79%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                       | 1        | 0.79%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s                      | 1        | 0.79%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8192MB DIMM DDR4 3200MT/s                    | 1        | 0.79%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s                      | 1        | 0.79%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB DIMM DDR4 2133MT/s                      | 1        | 0.79%   |
| Shenzhen Jinge Information RAM BRBN2G416G16C3200 16GB SODIMM DDR4 3200MT/s | 1        | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 68       | 62.96%  |
| DDR3    | 27       | 25%     |
| DDR5    | 8        | 7.41%   |
| Unknown | 3        | 2.78%   |
| SDRAM   | 2        | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 97       | 89.81%  |
| SODIMM | 11       | 10.19%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 37       | 31.62%  |
| 16384 | 32       | 27.35%  |
| 4096  | 22       | 18.8%   |
| 32768 | 21       | 17.95%  |
| 2048  | 3        | 2.56%   |
| 65536 | 1        | 0.85%   |
| 1024  | 1        | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 29       | 23.97%  |
| 1600    | 18       | 14.88%  |
| 2667    | 9        | 7.44%   |
| 2400    | 9        | 7.44%   |
| 3500    | 7        | 5.79%   |
| 2133    | 7        | 5.79%   |
| 5600    | 5        | 4.13%   |
| 3466    | 4        | 3.31%   |
| 3066    | 4        | 3.31%   |
| 1800    | 4        | 3.31%   |
| 3400    | 3        | 2.48%   |
| 1866    | 3        | 2.48%   |
| 4800    | 2        | 1.65%   |
| 3266    | 2        | 1.65%   |
| 2933    | 2        | 1.65%   |
| 2666    | 2        | 1.65%   |
| 1867    | 2        | 1.65%   |
| 1333    | 2        | 1.65%   |
| Unknown | 2        | 1.65%   |
| 5200    | 1        | 0.83%   |
| 4802    | 1        | 0.83%   |
| 3866    | 1        | 0.83%   |
| 3600    | 1        | 0.83%   |
| 3000    | 1        | 0.83%   |

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
| Sunplus Innovation Technology | 4        | 25%     |
| Logitech                      | 4        | 25%     |
| Samsung Electronics           | 2        | 12.5%   |
| Microdia                      | 2        | 12.5%   |
| lihappe8                      | 2        | 12.5%   |
| Z-Star Microelectronics       | 1        | 6.25%   |
| LG Electronics                | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Sunplus PC Camera                                     | 2        | 12.5%   |
| Samsung Galaxy series, misc. (MTP mode)               | 2        | 12.5%   |
| Logitech Webcam C110                                  | 2        | 12.5%   |
| lihappe8 USB 2.0 Camera                               | 2        | 12.5%   |
| Z-Star Vimicro USB Camera (Altair)                    | 1        | 6.25%   |
| Sunplus Sandberg USB Webcam Pro                       | 1        | 6.25%   |
| Sunplus Hy-Usb2.0-1*MIC                               | 1        | 6.25%   |
| Microdia Lenovo EasyCamera                            | 1        | 6.25%   |
| Microdia HP Webcam                                    | 1        | 6.25%   |
| Logitech StreamCam                                    | 1        | 6.25%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 6.25%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 6.25%   |

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
| 0     | 177      | 84.69%  |
| 1     | 26       | 12.44%  |
| 2     | 3        | 1.44%   |
| 5     | 1        | 0.48%   |
| 4     | 1        | 0.48%   |
| 3     | 1        | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 31.58%  |
| Unassigned class         | 8        | 21.05%  |
| Net/wireless             | 7        | 18.42%  |
| Net/ethernet             | 4        | 10.53%  |
| Communication controller | 3        | 7.89%   |
| Camera                   | 2        | 5.26%   |
| Sound                    | 1        | 2.63%   |
| Network                  | 1        | 2.63%   |


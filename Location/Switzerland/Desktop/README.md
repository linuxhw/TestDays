Linux in Switzerland - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

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

Total: 1320

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | D915GEV AAC63667-501        | [4d65f6d8fa](https://linux-hardware.org/?probe=4d65f6d8fa) | Aug 11, 2023 |
| HP            | 8433 11                     | [eac08c7b54](https://linux-hardware.org/?probe=eac08c7b54) | Aug 09, 2023 |
| Dell          | 0WR7PY A03                  | [b97d54f6d8](https://linux-hardware.org/?probe=b97d54f6d8) | Aug 09, 2023 |
| HP            | 894D                        | [e1c397df93](https://linux-hardware.org/?probe=e1c397df93) | Aug 09, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [cb5a99b4fb](https://linux-hardware.org/?probe=cb5a99b4fb) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| AZW           | GTR V02                     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| HP            | 2AF7                        | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| HP            | 843E                        | [dbbfb83ae4](https://linux-hardware.org/?probe=dbbfb83ae4) | Aug 03, 2023 |
| HP            | 843E                        | [952db006c3](https://linux-hardware.org/?probe=952db006c3) | Aug 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [b298625640](https://linux-hardware.org/?probe=b298625640) | Aug 01, 2023 |
| Dell          | 0K240Y A01                  | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| Acer          | Elena                       | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [45e8471971](https://linux-hardware.org/?probe=45e8471971) | Jul 26, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [b3d68108a2](https://linux-hardware.org/?probe=b3d68108a2) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [fbb58d4f7c](https://linux-hardware.org/?probe=fbb58d4f7c) | Jul 18, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [b44c0d94f4](https://linux-hardware.org/?probe=b44c0d94f4) | Jul 09, 2023 |
| Medion        | MS-7667                     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e0e1896cc3](https://linux-hardware.org/?probe=e0e1896cc3) | Jul 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [3908772779](https://linux-hardware.org/?probe=3908772779) | Jul 07, 2023 |
| ASUSTek       | H81M-PLUS                   | [80ed1496a1](https://linux-hardware.org/?probe=80ed1496a1) | Jul 05, 2023 |
| ASUSTek       | H170M-PLUS                  | [530d25db12](https://linux-hardware.org/?probe=530d25db12) | Jul 03, 2023 |
| HP            | 8918                        | [da7b695c7b](https://linux-hardware.org/?probe=da7b695c7b) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [277a9bb8e4](https://linux-hardware.org/?probe=277a9bb8e4) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [7f5dfae0db](https://linux-hardware.org/?probe=7f5dfae0db) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [8619447305](https://linux-hardware.org/?probe=8619447305) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [bddefdfb2c](https://linux-hardware.org/?probe=bddefdfb2c) | Jun 27, 2023 |
| Gigabyte      | Z97-HD3                     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| Gigabyte      | P67A-D3-B3                  | [f8dee044e2](https://linux-hardware.org/?probe=f8dee044e2) | Jun 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASUSTek       | P8P67 LE                    | [212ff65852](https://linux-hardware.org/?probe=212ff65852) | Jun 09, 2023 |
| ASUSTek       | WS Z390 PRO                 | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| HP            | 2B36                        | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| HP            | 8918                        | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| HP            | 843C                        | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [4d24b9b7d5](https://linux-hardware.org/?probe=4d24b9b7d5) | Jun 03, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| HP            | 8918                        | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [e98b2555d7](https://linux-hardware.org/?probe=e98b2555d7) | Jun 01, 2023 |
| HP            | 2B36                        | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | [2f3952dcfe](https://linux-hardware.org/?probe=2f3952dcfe) | May 27, 2023 |
| ASUSTek       | PRIME X399-A                | [a5a990a94c](https://linux-hardware.org/?probe=a5a990a94c) | May 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [aa0bf32546](https://linux-hardware.org/?probe=aa0bf32546) | May 23, 2023 |
| Medion        | B360H4-EM V1.0              | [ae4f01f58e](https://linux-hardware.org/?probe=ae4f01f58e) | May 22, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [bdaec355df](https://linux-hardware.org/?probe=bdaec355df) | May 16, 2023 |
| ASUSTek       | H97-PLUS                    | [e67567bd2a](https://linux-hardware.org/?probe=e67567bd2a) | May 15, 2023 |
| HP            | 0B4Ch D                     | [64b813a7dc](https://linux-hardware.org/?probe=64b813a7dc) | May 14, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| Gigabyte      | P67A-D3-B3                  | [41d9417c57](https://linux-hardware.org/?probe=41d9417c57) | May 11, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| Dell          | 0KRC95 A00                  | [f0f22d5d3f](https://linux-hardware.org/?probe=f0f22d5d3f) | May 08, 2023 |
| Medion        | MS-7797                     | [590e39bef4](https://linux-hardware.org/?probe=590e39bef4) | May 07, 2023 |
| Dell          | 09KPNV A00                  | [6089dfdeab](https://linux-hardware.org/?probe=6089dfdeab) | May 07, 2023 |
| ASRock        | 4X4-4000 Series             | [df056ec6f1](https://linux-hardware.org/?probe=df056ec6f1) | May 07, 2023 |
| Medion        | MS-7797                     | [d7eb2caa26](https://linux-hardware.org/?probe=d7eb2caa26) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Intel         | DH67CL AAG10212-210         | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| ASUSTek       | P8H77-M LE                  | [2a4b061b07](https://linux-hardware.org/?probe=2a4b061b07) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | [54417e14cf](https://linux-hardware.org/?probe=54417e14cf) | May 05, 2023 |
| HP            | 212B                        | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | [4b705b9dca](https://linux-hardware.org/?probe=4b705b9dca) | May 03, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [61873cde49](https://linux-hardware.org/?probe=61873cde49) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P                | [bbd9496296](https://linux-hardware.org/?probe=bbd9496296) | May 03, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [7a44b651f4](https://linux-hardware.org/?probe=7a44b651f4) | May 03, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [a720d9d42e](https://linux-hardware.org/?probe=a720d9d42e) | May 01, 2023 |
| Intel         | DH67CL AAG10212-210         | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | [910d4a6ad8](https://linux-hardware.org/?probe=910d4a6ad8) | Apr 29, 2023 |
| Intel         | DH67CL AAG10212-210         | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| Gigabyte      | Z97-HD3                     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| ASUSTek       | PRIME Z490-A                | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | [c7fdbbb95b](https://linux-hardware.org/?probe=c7fdbbb95b) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | [363bb28966](https://linux-hardware.org/?probe=363bb28966) | Apr 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| HP            | 8433 11                     | [e885f0469c](https://linux-hardware.org/?probe=e885f0469c) | Apr 22, 2023 |
| AZW           | GTR V02                     | [104badc0d7](https://linux-hardware.org/?probe=104badc0d7) | Apr 22, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | [65c9942c32](https://linux-hardware.org/?probe=65c9942c32) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | [607dbbf4d8](https://linux-hardware.org/?probe=607dbbf4d8) | Apr 21, 2023 |
| Gigabyte      | P55A-UD7                    | [59f8c4d262](https://linux-hardware.org/?probe=59f8c4d262) | Apr 20, 2023 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [f20338e169](https://linux-hardware.org/?probe=f20338e169) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [2c6da4e91f](https://linux-hardware.org/?probe=2c6da4e91f) | Apr 20, 2023 |
| ASUSTek       | H87M-PLUS                   | [472922fafd](https://linux-hardware.org/?probe=472922fafd) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | [a1b9ea4fd9](https://linux-hardware.org/?probe=a1b9ea4fd9) | Apr 20, 2023 |
| Intel         | DX58SO2 AAG10925-207        | [4e31c5af6b](https://linux-hardware.org/?probe=4e31c5af6b) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | [27a629fd15](https://linux-hardware.org/?probe=27a629fd15) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [f3a680d9bc](https://linux-hardware.org/?probe=f3a680d9bc) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | [96d5a26185](https://linux-hardware.org/?probe=96d5a26185) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [b6306c2e97](https://linux-hardware.org/?probe=b6306c2e97) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [fbedbcb213](https://linux-hardware.org/?probe=fbedbcb213) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [6e77ac0ec9](https://linux-hardware.org/?probe=6e77ac0ec9) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [c1b2a75484](https://linux-hardware.org/?probe=c1b2a75484) | Apr 20, 2023 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | [756eccb961](https://linux-hardware.org/?probe=756eccb961) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | [ef04208d0f](https://linux-hardware.org/?probe=ef04208d0f) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [c419c9200f](https://linux-hardware.org/?probe=c419c9200f) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [1be8dc273c](https://linux-hardware.org/?probe=1be8dc273c) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [244222ae5c](https://linux-hardware.org/?probe=244222ae5c) | Apr 20, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | [f77fe53c69](https://linux-hardware.org/?probe=f77fe53c69) | Apr 20, 2023 |
| Dell          | 08NPPY A00                  | [7d49aa5207](https://linux-hardware.org/?probe=7d49aa5207) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [d53ce13aa3](https://linux-hardware.org/?probe=d53ce13aa3) | Apr 20, 2023 |
| ASRock        | B550M Pro4                  | [ec13e17577](https://linux-hardware.org/?probe=ec13e17577) | Apr 20, 2023 |
| ASUSTek       | PRIME Z390-P                | [9fde2b21fc](https://linux-hardware.org/?probe=9fde2b21fc) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | [ddc7ba8ccb](https://linux-hardware.org/?probe=ddc7ba8ccb) | Apr 20, 2023 |
| Fujitsu       | D3348-A2 S26361-D3348-A2    | [3dbd4f731c](https://linux-hardware.org/?probe=3dbd4f731c) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [d46e9b11d5](https://linux-hardware.org/?probe=d46e9b11d5) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [afbf28c15a](https://linux-hardware.org/?probe=afbf28c15a) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [f185782be2](https://linux-hardware.org/?probe=f185782be2) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [731671f1b8](https://linux-hardware.org/?probe=731671f1b8) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [463c62da83](https://linux-hardware.org/?probe=463c62da83) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [0356125777](https://linux-hardware.org/?probe=0356125777) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [0a45e9e9af](https://linux-hardware.org/?probe=0a45e9e9af) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [ccf2e2bbc3](https://linux-hardware.org/?probe=ccf2e2bbc3) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [3171099090](https://linux-hardware.org/?probe=3171099090) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [032f3a72c6](https://linux-hardware.org/?probe=032f3a72c6) | Apr 20, 2023 |
| Intel         | DH87MC AAG74242-401         | [df7041b726](https://linux-hardware.org/?probe=df7041b726) | Apr 20, 2023 |
| ASUSTek       | P9X79 WS                    | [04e9cd2455](https://linux-hardware.org/?probe=04e9cd2455) | Apr 20, 2023 |
| Intel         | DP55WB AAE64798-207         | [0dd9e12f5a](https://linux-hardware.org/?probe=0dd9e12f5a) | Apr 20, 2023 |
| HP            | 870B                        | [ad6a3cc4d0](https://linux-hardware.org/?probe=ad6a3cc4d0) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | [9e668ff813](https://linux-hardware.org/?probe=9e668ff813) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [5dc0cb1f28](https://linux-hardware.org/?probe=5dc0cb1f28) | Apr 20, 2023 |
| Medion        | GA-Z170X-Gaming 7           | [706cfb4c50](https://linux-hardware.org/?probe=706cfb4c50) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | [b3b27e0fcf](https://linux-hardware.org/?probe=b3b27e0fcf) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [bdbd8d06e2](https://linux-hardware.org/?probe=bdbd8d06e2) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [ff10999142](https://linux-hardware.org/?probe=ff10999142) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [11da8c5d96](https://linux-hardware.org/?probe=11da8c5d96) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [128d16cf7f](https://linux-hardware.org/?probe=128d16cf7f) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [c2de2809a0](https://linux-hardware.org/?probe=c2de2809a0) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [c3a3c03c3f](https://linux-hardware.org/?probe=c3a3c03c3f) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [1ae9258a0d](https://linux-hardware.org/?probe=1ae9258a0d) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [ab89260502](https://linux-hardware.org/?probe=ab89260502) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [3f99aeec69](https://linux-hardware.org/?probe=3f99aeec69) | Apr 20, 2023 |
| HP            | 870B                        | [50f654b2a0](https://linux-hardware.org/?probe=50f654b2a0) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | [9949a0748f](https://linux-hardware.org/?probe=9949a0748f) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [e3cfbf7435](https://linux-hardware.org/?probe=e3cfbf7435) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [9817f90648](https://linux-hardware.org/?probe=9817f90648) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | [cf4854d704](https://linux-hardware.org/?probe=cf4854d704) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [296676f929](https://linux-hardware.org/?probe=296676f929) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [2eeebec1ec](https://linux-hardware.org/?probe=2eeebec1ec) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [68ac671aab](https://linux-hardware.org/?probe=68ac671aab) | Apr 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [a069d32b86](https://linux-hardware.org/?probe=a069d32b86) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [1b1a3da7b2](https://linux-hardware.org/?probe=1b1a3da7b2) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [2a1fcefe29](https://linux-hardware.org/?probe=2a1fcefe29) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [5c54edc96d](https://linux-hardware.org/?probe=5c54edc96d) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | [563e45a22a](https://linux-hardware.org/?probe=563e45a22a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [0000720fb6](https://linux-hardware.org/?probe=0000720fb6) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [fdda3d6276](https://linux-hardware.org/?probe=fdda3d6276) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [ee95d83f31](https://linux-hardware.org/?probe=ee95d83f31) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [1e49dc0f67](https://linux-hardware.org/?probe=1e49dc0f67) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| HP            | 89D8 SMVB                   | [c4c1d8086c](https://linux-hardware.org/?probe=c4c1d8086c) | Apr 20, 2023 |
| ASRock        | B560M-HDV                   | [b835e48fad](https://linux-hardware.org/?probe=b835e48fad) | Apr 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [882d6f625d](https://linux-hardware.org/?probe=882d6f625d) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f16bcad94](https://linux-hardware.org/?probe=8f16bcad94) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [848607e7f1](https://linux-hardware.org/?probe=848607e7f1) | Apr 19, 2023 |
| ASUSTek       | PRIME Z590-P                | [79225bdfaf](https://linux-hardware.org/?probe=79225bdfaf) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [4d802fb610](https://linux-hardware.org/?probe=4d802fb610) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [2b749e898e](https://linux-hardware.org/?probe=2b749e898e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [702377976d](https://linux-hardware.org/?probe=702377976d) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [32f7392dce](https://linux-hardware.org/?probe=32f7392dce) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [b7f40b0d8e](https://linux-hardware.org/?probe=b7f40b0d8e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [9602690aa2](https://linux-hardware.org/?probe=9602690aa2) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [bbf0a5108a](https://linux-hardware.org/?probe=bbf0a5108a) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [000ec3362e](https://linux-hardware.org/?probe=000ec3362e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [7d67899067](https://linux-hardware.org/?probe=7d67899067) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [256a2110b0](https://linux-hardware.org/?probe=256a2110b0) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [9f69cc7127](https://linux-hardware.org/?probe=9f69cc7127) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [997c25143e](https://linux-hardware.org/?probe=997c25143e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [71822fdac9](https://linux-hardware.org/?probe=71822fdac9) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [b3f9111b79](https://linux-hardware.org/?probe=b3f9111b79) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [df314b2a9c](https://linux-hardware.org/?probe=df314b2a9c) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | [dc155ce308](https://linux-hardware.org/?probe=dc155ce308) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | [aaff05d28f](https://linux-hardware.org/?probe=aaff05d28f) | Apr 17, 2023 |
| ASRock        | Z170 Extreme4               | [fc6c4adaa4](https://linux-hardware.org/?probe=fc6c4adaa4) | Apr 17, 2023 |
| ASRock        | Z170 Extreme4               | [a0f5ba360c](https://linux-hardware.org/?probe=a0f5ba360c) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| Intel         | DH67CL AAG10212-210         | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Apple         | Mac-F221BEC8                | [c4f2e4e7d8](https://linux-hardware.org/?probe=c4f2e4e7d8) | Apr 14, 2023 |
| HP            | 0B4Ch D                     | [a0247e45a6](https://linux-hardware.org/?probe=a0247e45a6) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | [f205e700dc](https://linux-hardware.org/?probe=f205e700dc) | Apr 13, 2023 |
| HP            | 8433 11                     | [61c92812be](https://linux-hardware.org/?probe=61c92812be) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [cc25df15df](https://linux-hardware.org/?probe=cc25df15df) | Apr 08, 2023 |
| ASUSTek       | P8P67                       | [a62766f42e](https://linux-hardware.org/?probe=a62766f42e) | Apr 08, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8566b9511a](https://linux-hardware.org/?probe=8566b9511a) | Apr 02, 2023 |
| ASUSTek       | Maximus IV Extreme-Z        | [36d245f86b](https://linux-hardware.org/?probe=36d245f86b) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3a8d512ae4](https://linux-hardware.org/?probe=3a8d512ae4) | Apr 02, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | [452a3fa4a8](https://linux-hardware.org/?probe=452a3fa4a8) | Mar 29, 2023 |
| HP            | 844C                        | [8270d682a8](https://linux-hardware.org/?probe=8270d682a8) | Mar 27, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | [35e0a73e8f](https://linux-hardware.org/?probe=35e0a73e8f) | Mar 26, 2023 |
| ASUSTek       | SABERTOOTH X79              | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
| HP            | 8433 11                     | [5ab010ffd4](https://linux-hardware.org/?probe=5ab010ffd4) | Mar 25, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [704fb36197](https://linux-hardware.org/?probe=704fb36197) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| ASRock        | H270 Pro4                   | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Dell          | 09KPNV A00                  | [5074a23172](https://linux-hardware.org/?probe=5074a23172) | Mar 20, 2023 |
| HP            | 2B36                        | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| Medion        | B360H4-EM V1.0              | [839899a14d](https://linux-hardware.org/?probe=839899a14d) | Mar 15, 2023 |
| ASUSTek       | PRIME Z590-P                | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| HP            | 212B                        | [8d5ef71d93](https://linux-hardware.org/?probe=8d5ef71d93) | Mar 13, 2023 |
| Dell          | 0T7D40 A01                  | [c2174a1837](https://linux-hardware.org/?probe=c2174a1837) | Mar 12, 2023 |
| Dell          | 09KPNV A00                  | [6c90dd73e7](https://linux-hardware.org/?probe=6c90dd73e7) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | [c792b83b69](https://linux-hardware.org/?probe=c792b83b69) | Mar 11, 2023 |
| Gigabyte      | Z97-HD3                     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| Inventec      | D CLASS A02                 | [b9e49da1f7](https://linux-hardware.org/?probe=b9e49da1f7) | Mar 10, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [d52a175b61](https://linux-hardware.org/?probe=d52a175b61) | Mar 07, 2023 |
| AZW           | GTR V02                     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [971feb34e4](https://linux-hardware.org/?probe=971feb34e4) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8fc8fee94a](https://linux-hardware.org/?probe=8fc8fee94a) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [576314ab03](https://linux-hardware.org/?probe=576314ab03) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| Gigabyte      | X79-UD3                     | [f8dfa838b7](https://linux-hardware.org/?probe=f8dfa838b7) | Feb 18, 2023 |
| Gigabyte      | H81M-H                      | [d773500fcb](https://linux-hardware.org/?probe=d773500fcb) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [92a61cd4ee](https://linux-hardware.org/?probe=92a61cd4ee) | Feb 16, 2023 |
| Philco        | DTC-A55                     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [e927a19203](https://linux-hardware.org/?probe=e927a19203) | Feb 16, 2023 |
| HP            | 8653 A                      | [5854a10eb0](https://linux-hardware.org/?probe=5854a10eb0) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e7fd395c49](https://linux-hardware.org/?probe=e7fd395c49) | Feb 05, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [384a4f7da2](https://linux-hardware.org/?probe=384a4f7da2) | Feb 05, 2023 |
| HP            | 2B36                        | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| ASUSTek       | P8H77-M                     | [9e7d0b79cf](https://linux-hardware.org/?probe=9e7d0b79cf) | Feb 05, 2023 |
| Gigabyte      | H81M-H                      | [5dbc22fda8](https://linux-hardware.org/?probe=5dbc22fda8) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | [4626133ef2](https://linux-hardware.org/?probe=4626133ef2) | Feb 04, 2023 |
| Medion        | MS-7728                     | [60cf9e4948](https://linux-hardware.org/?probe=60cf9e4948) | Jan 31, 2023 |
| Dell          | 02YRK5 A02                  | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [11b07d4e11](https://linux-hardware.org/?probe=11b07d4e11) | Jan 29, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| ASUSTek       | M5A99X EVO                  | [14b3eb9a58](https://linux-hardware.org/?probe=14b3eb9a58) | Jan 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [b6afa43240](https://linux-hardware.org/?probe=b6afa43240) | Jan 24, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [141c9ffa73](https://linux-hardware.org/?probe=141c9ffa73) | Jan 24, 2023 |
| AZW           | GTR V02                     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| Medion        | MS-7728                     | [93d0aaac10](https://linux-hardware.org/?probe=93d0aaac10) | Jan 21, 2023 |
| Medion        | MS-7728                     | [eb9cef403c](https://linux-hardware.org/?probe=eb9cef403c) | Jan 21, 2023 |
| ASRock        | Z370 Pro4                   | [bf7bab9d7c](https://linux-hardware.org/?probe=bf7bab9d7c) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | [e05b7e7729](https://linux-hardware.org/?probe=e05b7e7729) | Jan 19, 2023 |
| Medion        | MS-7728                     | [b5e3ddf859](https://linux-hardware.org/?probe=b5e3ddf859) | Jan 18, 2023 |
| Acer          | Veriton M2110G              | [7097a3cf90](https://linux-hardware.org/?probe=7097a3cf90) | Jan 18, 2023 |
| Acer          | Aspire M5910                | [d2d4e86b49](https://linux-hardware.org/?probe=d2d4e86b49) | Jan 17, 2023 |
| HP            | 212B                        | [00822b2263](https://linux-hardware.org/?probe=00822b2263) | Jan 16, 2023 |
| Medion        | MS-7728                     | [5168c2f916](https://linux-hardware.org/?probe=5168c2f916) | Jan 16, 2023 |
| AZW           | GTR V02                     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK               | [ebb69311f7](https://linux-hardware.org/?probe=ebb69311f7) | Jan 14, 2023 |
| ELSKY         | QM10u                       | [c9bde314b5](https://linux-hardware.org/?probe=c9bde314b5) | Jan 11, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [d014e736fc](https://linux-hardware.org/?probe=d014e736fc) | Jan 11, 2023 |
| Medion        | MS-7728                     | [8310cf0974](https://linux-hardware.org/?probe=8310cf0974) | Jan 10, 2023 |
| HP            | 3048h                       | [e13a2bdf6e](https://linux-hardware.org/?probe=e13a2bdf6e) | Jan 10, 2023 |
| HP            | 158A                        | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| AZW           | GTR V02                     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [ac69fa3d31](https://linux-hardware.org/?probe=ac69fa3d31) | Jan 07, 2023 |
| ASUSTek       | P8H77-M PRO                 | [03524fa074](https://linux-hardware.org/?probe=03524fa074) | Jan 07, 2023 |
| MSI           | IONA                        | [8e49c8c0b1](https://linux-hardware.org/?probe=8e49c8c0b1) | Jan 06, 2023 |
| MSI           | IONA                        | [ca8adec17c](https://linux-hardware.org/?probe=ca8adec17c) | Jan 06, 2023 |
| Medion        | MS-7728                     | [4b3e96394b](https://linux-hardware.org/?probe=4b3e96394b) | Jan 06, 2023 |
| Medion        | MS-7728                     | [0ffef4911e](https://linux-hardware.org/?probe=0ffef4911e) | Jan 05, 2023 |
| Gigabyte      | Z690 UD DDR4                | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
| Medion        | MS-7728                     | [9c2439adf6](https://linux-hardware.org/?probe=9c2439adf6) | Jan 04, 2023 |
| ASUSTek       | P7H55-M PRO                 | [518b2272d4](https://linux-hardware.org/?probe=518b2272d4) | Jan 04, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | [b341980e6c](https://linux-hardware.org/?probe=b341980e6c) | Jan 04, 2023 |
| ASUSTek       | Crosshair IV Formula        | [77ee14ad98](https://linux-hardware.org/?probe=77ee14ad98) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | [1c022f7ff8](https://linux-hardware.org/?probe=1c022f7ff8) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | P7H55-M PRO                 | [b445490856](https://linux-hardware.org/?probe=b445490856) | Dec 25, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [47397487a7](https://linux-hardware.org/?probe=47397487a7) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [e954c9ca37](https://linux-hardware.org/?probe=e954c9ca37) | Dec 19, 2022 |
| Gigabyte      | P67A-D3-B3                  | [9ed715edc4](https://linux-hardware.org/?probe=9ed715edc4) | Dec 11, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [6c26c9ff8c](https://linux-hardware.org/?probe=6c26c9ff8c) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| BESSTAR Te... | B550                        | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | PRIME B350M-A               | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| Dell          | 0HN7XN A00                  | [f2ba8a7d55](https://linux-hardware.org/?probe=f2ba8a7d55) | Dec 06, 2022 |
| Dell          | 0HN7XN A00                  | [927991f54f](https://linux-hardware.org/?probe=927991f54f) | Dec 06, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [ee9c9e919b](https://linux-hardware.org/?probe=ee9c9e919b) | Dec 05, 2022 |
| ASUSTek       | Maximus VII RANGER          | [9a0718a60f](https://linux-hardware.org/?probe=9a0718a60f) | Dec 04, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [13b2f864f8](https://linux-hardware.org/?probe=13b2f864f8) | Dec 02, 2022 |
| ASUSTek       | H81M-PLUS                   | [8d98938198](https://linux-hardware.org/?probe=8d98938198) | Nov 30, 2022 |
| Pegatron      | VIOLET                      | [f0f25e6854](https://linux-hardware.org/?probe=f0f25e6854) | Nov 28, 2022 |
| ASRock        | B550M Pro4                  | [3ba26453f1](https://linux-hardware.org/?probe=3ba26453f1) | Nov 24, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE                  | [54f10b9d0b](https://linux-hardware.org/?probe=54f10b9d0b) | Nov 21, 2022 |
| ASUSTek       | P6T DELUXE                  | [576ca67a28](https://linux-hardware.org/?probe=576ca67a28) | Nov 21, 2022 |
| ASUSTek       | P7H55-M PRO                 | [b25dd25478](https://linux-hardware.org/?probe=b25dd25478) | Nov 20, 2022 |
| HP            | 212B                        | [574a94ad86](https://linux-hardware.org/?probe=574a94ad86) | Nov 18, 2022 |
| HP            | 212B                        | [3995268826](https://linux-hardware.org/?probe=3995268826) | Nov 18, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| ASUSTek       | PRIME B350M-A               | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [2053688baa](https://linux-hardware.org/?probe=2053688baa) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [15f6c6a1aa](https://linux-hardware.org/?probe=15f6c6a1aa) | Nov 14, 2022 |
| ASUSTek       | P6T DELUXE                  | [3726e23d23](https://linux-hardware.org/?probe=3726e23d23) | Nov 14, 2022 |
| Alienware     | 07W25T A00                  | [f320cc2659](https://linux-hardware.org/?probe=f320cc2659) | Nov 11, 2022 |
| ASRock        | X570M Pro4                  | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| HP            | 3396                        | [d42479acb8](https://linux-hardware.org/?probe=d42479acb8) | Oct 28, 2022 |
| Acer          | WG43M                       | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a83d0f0ade](https://linux-hardware.org/?probe=a83d0f0ade) | Oct 20, 2022 |
| MSI           | H170I PRO AC                | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| ASRock        | Z97 Extreme6                | [9d2cf83f81](https://linux-hardware.org/?probe=9d2cf83f81) | Oct 12, 2022 |
| ASRock        | Z97 Extreme6                | [feb997ebfc](https://linux-hardware.org/?probe=feb997ebfc) | Oct 12, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [10e153f71e](https://linux-hardware.org/?probe=10e153f71e) | Oct 10, 2022 |
| Chuwi         | RZBOX                       | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| Dell          | 0T656F A01                  | [24da875cf7](https://linux-hardware.org/?probe=24da875cf7) | Oct 04, 2022 |
| HP            | 213D A01                    | [e81fd5fea5](https://linux-hardware.org/?probe=e81fd5fea5) | Oct 04, 2022 |
| MSI           | B450 TOMAHAWK               | [6a5067b548](https://linux-hardware.org/?probe=6a5067b548) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK               | [2044c11c98](https://linux-hardware.org/?probe=2044c11c98) | Oct 02, 2022 |
| MSI           | 2A9C                        | [a933ad6bca](https://linux-hardware.org/?probe=a933ad6bca) | Oct 01, 2022 |
| Pegatron      | IPMSB-GS                    | [5e38213b3b](https://linux-hardware.org/?probe=5e38213b3b) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| Packard Be... | IMEDIA S1300                | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| HP            | 8053                        | [d46ac6d7db](https://linux-hardware.org/?probe=d46ac6d7db) | Sep 22, 2022 |
| Packard Be... | IMEDIA S1300                | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| HP            | 0AA8h                       | [3c274fc7f3](https://linux-hardware.org/?probe=3c274fc7f3) | Sep 19, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| Gigabyte      | Z590 VISION G               | [ec15390099](https://linux-hardware.org/?probe=ec15390099) | Sep 14, 2022 |
| ASUSTek       | SABERTOOTH X58              | [ce9d09e18a](https://linux-hardware.org/?probe=ce9d09e18a) | Sep 10, 2022 |
| Apple         | Mac-F221BEC8                | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| MSI           | B250M PRO-VDH               | [6c5483e3f5](https://linux-hardware.org/?probe=6c5483e3f5) | Sep 07, 2022 |
| Acer          | Aspire X3950                | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| Dell          | 0GN6JF A01                  | [390fbaaca7](https://linux-hardware.org/?probe=390fbaaca7) | Sep 05, 2022 |
| HP            | 8076                        | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| ASUSTek       | Z97-PRO                     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [08cfa37b81](https://linux-hardware.org/?probe=08cfa37b81) | Sep 03, 2022 |
| HP            | 2B36                        | [c6de6225af](https://linux-hardware.org/?probe=c6de6225af) | Aug 29, 2022 |
| Medion        | Cattle24 1M                 | [eb19c533e0](https://linux-hardware.org/?probe=eb19c533e0) | Aug 29, 2022 |
| ASRock        | B450M Pro4                  | [8f0f345242](https://linux-hardware.org/?probe=8f0f345242) | Aug 28, 2022 |
| Pegatron      | IPMSB-GS                    | [9edb57e041](https://linux-hardware.org/?probe=9edb57e041) | Aug 28, 2022 |
| HP            | 2B36                        | [9890b96e0e](https://linux-hardware.org/?probe=9890b96e0e) | Aug 21, 2022 |
| HP            | 212B                        | [ba5bf87e58](https://linux-hardware.org/?probe=ba5bf87e58) | Aug 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8a48025d15](https://linux-hardware.org/?probe=8a48025d15) | Aug 18, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [d0c25e4ba8](https://linux-hardware.org/?probe=d0c25e4ba8) | Aug 17, 2022 |
| ASUSTek       | Berkeley                    | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| Biostar       | A960D+V3                    | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASUSTek       | P5B                         | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| HP            | 0B4Ch D                     | [98ea1068a3](https://linux-hardware.org/?probe=98ea1068a3) | Aug 15, 2022 |
| Acer          | Aspire XC-605               | [125a8c791a](https://linux-hardware.org/?probe=125a8c791a) | Aug 14, 2022 |
| Pegatron      | IPMSB-GS                    | [7d2cd4cc35](https://linux-hardware.org/?probe=7d2cd4cc35) | Aug 11, 2022 |
| Pegatron      | IPMSB-GS                    | [7e2bf60517](https://linux-hardware.org/?probe=7e2bf60517) | Aug 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| ASUSTek       | H81T                        | [4049aa824c](https://linux-hardware.org/?probe=4049aa824c) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | [49098497d4](https://linux-hardware.org/?probe=49098497d4) | Aug 11, 2022 |
| HP            | 0B4Ch D                     | [06422a72b8](https://linux-hardware.org/?probe=06422a72b8) | Aug 08, 2022 |
| ASRock        | 880GM-LE FX                 | [957edc332a](https://linux-hardware.org/?probe=957edc332a) | Aug 06, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [42cb82f584](https://linux-hardware.org/?probe=42cb82f584) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| Gigabyte      | EP45-DS3                    | [5b5fe46f75](https://linux-hardware.org/?probe=5b5fe46f75) | Jul 26, 2022 |
| Gigabyte      | G31M-S2L                    | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| MSI           | PRO B660M-A WIFI            | [e8da564bb8](https://linux-hardware.org/?probe=e8da564bb8) | Jul 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [7d3501365a](https://linux-hardware.org/?probe=7d3501365a) | Jul 23, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [e80a3e71e2](https://linux-hardware.org/?probe=e80a3e71e2) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
| HP            | 1998                        | [8aa7e05c70](https://linux-hardware.org/?probe=8aa7e05c70) | Jul 17, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASUSTek       | X99-A                       | [6db5d85e5c](https://linux-hardware.org/?probe=6db5d85e5c) | Jul 13, 2022 |
| ZOTAC         | Unknown                     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6fa5768750](https://linux-hardware.org/?probe=6fa5768750) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | [924537ba87](https://linux-hardware.org/?probe=924537ba87) | Jul 02, 2022 |
| Apple         | Mac-F221BEC8                | [564950d244](https://linux-hardware.org/?probe=564950d244) | Jul 02, 2022 |
| Medion        | MS-7667                     | [22ac257e4a](https://linux-hardware.org/?probe=22ac257e4a) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Gigabyte      | C1037UN-EU                  | [a2729b2e3b](https://linux-hardware.org/?probe=a2729b2e3b) | Jun 30, 2022 |
| Gigabyte      | X570 AORUS PRO              | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| MSI           | 2A9C                        | [c4d999a9a5](https://linux-hardware.org/?probe=c4d999a9a5) | Jun 26, 2022 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [62aec95456](https://linux-hardware.org/?probe=62aec95456) | Jun 22, 2022 |
| Lenovo        | ThinkStation S20 4105J6G    | [3182b17f83](https://linux-hardware.org/?probe=3182b17f83) | Jun 21, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| ASUSTek       | PRIME Z270-A                | [0f85d8c023](https://linux-hardware.org/?probe=0f85d8c023) | Jun 19, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [d84600d5b0](https://linux-hardware.org/?probe=d84600d5b0) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASUSTek       | PRIME B360M-C               | [c250d3b2e0](https://linux-hardware.org/?probe=c250d3b2e0) | Jun 14, 2022 |
| ASUSTek       | PRIME Z270-A                | [dd22c99aac](https://linux-hardware.org/?probe=dd22c99aac) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Acer          | Aspire X3950                | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| HP            | 3032h                       | [fee76c58db](https://linux-hardware.org/?probe=fee76c58db) | Jun 09, 2022 |
| ASUSTek       | WS X299 PRO                 | [219d19f97e](https://linux-hardware.org/?probe=219d19f97e) | Jun 06, 2022 |
| Dell          | 0T7D40 A01                  | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Shuttle       | DS10U                       | [f2d2634abd](https://linux-hardware.org/?probe=f2d2634abd) | Jun 04, 2022 |
| Gigabyte      | Z590 VISION G               | [c91b17ed23](https://linux-hardware.org/?probe=c91b17ed23) | Jun 04, 2022 |
| ASUSTek       | PRIME B360M-C               | [b57fa63f1a](https://linux-hardware.org/?probe=b57fa63f1a) | Jun 04, 2022 |
| Gigabyte      | Z590 VISION G               | [a2a510d9dd](https://linux-hardware.org/?probe=a2a510d9dd) | Jun 03, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [d8134fd2fe](https://linux-hardware.org/?probe=d8134fd2fe) | Jun 02, 2022 |
| ASUSTek       | P5B                         | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| HP            | 212B                        | [f651b20f02](https://linux-hardware.org/?probe=f651b20f02) | May 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e474768a25](https://linux-hardware.org/?probe=e474768a25) | May 30, 2022 |
| Minix         | NEO Z83-4A V1.1             | [e828d9bd38](https://linux-hardware.org/?probe=e828d9bd38) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| ASRock        | FM2A85X Extreme6            | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| Dell          | 073MMW A02                  | [6c7cfb5226](https://linux-hardware.org/?probe=6c7cfb5226) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| ASUSTek       | P8Z77-V LX                  | [5f505dd767](https://linux-hardware.org/?probe=5f505dd767) | May 26, 2022 |
| ASRock        | FM2A85X Extreme6            | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| HP            | 8703                        | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| HP            | 805F                        | [c682455b49](https://linux-hardware.org/?probe=c682455b49) | May 13, 2022 |
| HP            | 805F                        | [ef6a65832f](https://linux-hardware.org/?probe=ef6a65832f) | May 13, 2022 |
| Shuttle       | DS10U                       | [2f2acb55e9](https://linux-hardware.org/?probe=2f2acb55e9) | May 13, 2022 |
| ASUSTek       | GA35DX                      | [f604073d1f](https://linux-hardware.org/?probe=f604073d1f) | May 11, 2022 |
| Gigabyte      | Z590 VISION G               | [0e12a4aa26](https://linux-hardware.org/?probe=0e12a4aa26) | May 11, 2022 |
| ASRock        | J4105B-ITX                  | [6e507d9a68](https://linux-hardware.org/?probe=6e507d9a68) | May 09, 2022 |
| ASRock        | J4105B-ITX                  | [c4eea9f630](https://linux-hardware.org/?probe=c4eea9f630) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| HP            | 870C                        | [adb470192a](https://linux-hardware.org/?probe=adb470192a) | May 08, 2022 |
| Lenovo        | SDK0E50510 WIN 262504835... | [5565a2f131](https://linux-hardware.org/?probe=5565a2f131) | May 07, 2022 |
| ASUSTek       | P8H77-M                     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| MSI           | PRO B660M-A WIFI            | [878c361636](https://linux-hardware.org/?probe=878c361636) | May 01, 2022 |
| Medion        | Cattle24 1M                 | [920d1b35ab](https://linux-hardware.org/?probe=920d1b35ab) | Apr 30, 2022 |
| Acer          | Predator G3620              | [556a67d50d](https://linux-hardware.org/?probe=556a67d50d) | Apr 28, 2022 |
| NF541         | 1.0                         | [c0999696b6](https://linux-hardware.org/?probe=c0999696b6) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | [99b46394bf](https://linux-hardware.org/?probe=99b46394bf) | Apr 27, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [475131a6f4](https://linux-hardware.org/?probe=475131a6f4) | Apr 23, 2022 |
| Gigabyte      | Z590 VISION G               | [597940fbe8](https://linux-hardware.org/?probe=597940fbe8) | Apr 22, 2022 |
| ASUSTek       | H97-PLUS                    | [6495b55188](https://linux-hardware.org/?probe=6495b55188) | Apr 21, 2022 |
| HP            | 3048h                       | [b35df4ed74](https://linux-hardware.org/?probe=b35df4ed74) | Apr 20, 2022 |
| MSI           | B550-A PRO                  | [3af8357ab9](https://linux-hardware.org/?probe=3af8357ab9) | Apr 20, 2022 |
| MSI           | X99A SLI PLUS               | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| ASUSTek       | P6T DELUXE                  | [1ceaddfc92](https://linux-hardware.org/?probe=1ceaddfc92) | Apr 16, 2022 |
| HP            | 8298                        | [a9796ddd8d](https://linux-hardware.org/?probe=a9796ddd8d) | Apr 14, 2022 |
| MSI           | B450-A PRO MAX              | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8e46ef2a00](https://linux-hardware.org/?probe=8e46ef2a00) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [18a9612e64](https://linux-hardware.org/?probe=18a9612e64) | Apr 13, 2022 |
| PC Engines    | apu4                        | [601866ecaa](https://linux-hardware.org/?probe=601866ecaa) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | [36e8e44760](https://linux-hardware.org/?probe=36e8e44760) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | [50d7c349cd](https://linux-hardware.org/?probe=50d7c349cd) | Apr 10, 2022 |
| Gigabyte      | Z590 VISION G               | [b160291e93](https://linux-hardware.org/?probe=b160291e93) | Apr 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| MSI           | 2A9C                        | [d56d880fd1](https://linux-hardware.org/?probe=d56d880fd1) | Apr 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [7e44cf1d2c](https://linux-hardware.org/?probe=7e44cf1d2c) | Apr 04, 2022 |
| Gigabyte      | H410M S2H V3                | [0c9c9dd7e9](https://linux-hardware.org/?probe=0c9c9dd7e9) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| ASRock        | B550M Pro4                  | [6755915c96](https://linux-hardware.org/?probe=6755915c96) | Mar 29, 2022 |
| MSI           | Z170A PC MATE               | [546a66dcf1](https://linux-hardware.org/?probe=546a66dcf1) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [85f4e6ff91](https://linux-hardware.org/?probe=85f4e6ff91) | Mar 26, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a9df37f3f0](https://linux-hardware.org/?probe=a9df37f3f0) | Mar 23, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d98f42c86b](https://linux-hardware.org/?probe=d98f42c86b) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [04e11e3668](https://linux-hardware.org/?probe=04e11e3668) | Mar 16, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [b0d9828f83](https://linux-hardware.org/?probe=b0d9828f83) | Mar 16, 2022 |
| Gigabyte      | Z590 VISION G               | [bf629bc1a5](https://linux-hardware.org/?probe=bf629bc1a5) | Mar 14, 2022 |
| Gigabyte      | Z590 VISION G               | [f56d8f0fe4](https://linux-hardware.org/?probe=f56d8f0fe4) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | [f4f7ab1aaf](https://linux-hardware.org/?probe=f4f7ab1aaf) | Mar 12, 2022 |
| HP            | 806A                        | [60d334dbf5](https://linux-hardware.org/?probe=60d334dbf5) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| MSI           | MAG B460M MORTAR            | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LX                  | [af17a2da6b](https://linux-hardware.org/?probe=af17a2da6b) | Mar 05, 2022 |
| Dell          | 0K240Y A02                  | [95d4a7b220](https://linux-hardware.org/?probe=95d4a7b220) | Mar 05, 2022 |
| HP            | 8592                        | [a34dbdb173](https://linux-hardware.org/?probe=a34dbdb173) | Mar 01, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [e0d39731a0](https://linux-hardware.org/?probe=e0d39731a0) | Feb 27, 2022 |
| ASRock        | Z370 Pro4                   | [e996ec20ea](https://linux-hardware.org/?probe=e996ec20ea) | Feb 25, 2022 |
| Gigabyte      | B550M AORUS PRO             | [98a6706e6a](https://linux-hardware.org/?probe=98a6706e6a) | Feb 23, 2022 |
| MSI           | B550-A PRO                  | [9d3f01a706](https://linux-hardware.org/?probe=9d3f01a706) | Feb 23, 2022 |
| Gigabyte      | MSH87TN-00                  | [6baa824f3a](https://linux-hardware.org/?probe=6baa824f3a) | Feb 17, 2022 |
| ASUSTek       | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [f2d47f2d8b](https://linux-hardware.org/?probe=f2d47f2d8b) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [a82c9b223f](https://linux-hardware.org/?probe=a82c9b223f) | Feb 14, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [4583e687ca](https://linux-hardware.org/?probe=4583e687ca) | Feb 13, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [0f83b2fd97](https://linux-hardware.org/?probe=0f83b2fd97) | Feb 12, 2022 |
| HP            | 8618                        | [6976caf9ed](https://linux-hardware.org/?probe=6976caf9ed) | Feb 12, 2022 |
| HP            | 8618                        | [1038885608](https://linux-hardware.org/?probe=1038885608) | Feb 12, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [c5b6cfb8bc](https://linux-hardware.org/?probe=c5b6cfb8bc) | Feb 11, 2022 |
| MSI           | G31TM-P35                   | [6312e054ab](https://linux-hardware.org/?probe=6312e054ab) | Feb 09, 2022 |
| Medion        | B460H6-EM                   | [b32b83ff4b](https://linux-hardware.org/?probe=b32b83ff4b) | Feb 09, 2022 |
| MSI           | B450-A PRO MAX              | [da25fcadb3](https://linux-hardware.org/?probe=da25fcadb3) | Feb 09, 2022 |
| HP            | 18E5                        | [85267de714](https://linux-hardware.org/?probe=85267de714) | Feb 09, 2022 |
| ASUSTek       | P8P67                       | [59a8e93ae4](https://linux-hardware.org/?probe=59a8e93ae4) | Feb 07, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [30bb989cfa](https://linux-hardware.org/?probe=30bb989cfa) | Feb 05, 2022 |
| MSI           | B550-A PRO                  | [091a9c467d](https://linux-hardware.org/?probe=091a9c467d) | Feb 04, 2022 |
| MSI           | B550-A PRO                  | [7ff1fc83fc](https://linux-hardware.org/?probe=7ff1fc83fc) | Feb 04, 2022 |
| ASUSTek       | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| ASUSTek       | H81M-PLUS                   | [dde47afaff](https://linux-hardware.org/?probe=dde47afaff) | Feb 03, 2022 |
| Unknown       | 1.0                         | [03f9d9de62](https://linux-hardware.org/?probe=03f9d9de62) | Jan 31, 2022 |
| MSI           | B450-A PRO MAX              | [08a04a280f](https://linux-hardware.org/?probe=08a04a280f) | Jan 30, 2022 |
| HP            | 3048h                       | [cb51d0cf78](https://linux-hardware.org/?probe=cb51d0cf78) | Jan 30, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [4a0bd17330](https://linux-hardware.org/?probe=4a0bd17330) | Jan 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | [c528c04bb7](https://linux-hardware.org/?probe=c528c04bb7) | Jan 22, 2022 |
| ASUSTek       | H87M-PLUS                   | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Medion        | Cattle24 1M                 | [328e103a74](https://linux-hardware.org/?probe=328e103a74) | Jan 21, 2022 |
| Gigabyte      | H97-D3H-CF                  | [8e39cc0d01](https://linux-hardware.org/?probe=8e39cc0d01) | Jan 21, 2022 |
| MSI           | MEG X570 UNIFY              | [0bb120993f](https://linux-hardware.org/?probe=0bb120993f) | Jan 21, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d70ebfd602](https://linux-hardware.org/?probe=d70ebfd602) | Jan 20, 2022 |
| ASRock        | Z97 Extreme6                | [4b8a587819](https://linux-hardware.org/?probe=4b8a587819) | Jan 20, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [f1c61e2a1b](https://linux-hardware.org/?probe=f1c61e2a1b) | Jan 19, 2022 |
| ASRock        | Z97 Extreme6                | [d897de368d](https://linux-hardware.org/?probe=d897de368d) | Jan 17, 2022 |
| HP            | 3048h                       | [d6f6435471](https://linux-hardware.org/?probe=d6f6435471) | Jan 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | [d508a12888](https://linux-hardware.org/?probe=d508a12888) | Jan 15, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [2d14961843](https://linux-hardware.org/?probe=2d14961843) | Jan 14, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [0c991d9fae](https://linux-hardware.org/?probe=0c991d9fae) | Jan 14, 2022 |
| Gigabyte      | H55M-USB3                   | [88396d099b](https://linux-hardware.org/?probe=88396d099b) | Jan 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| MSI           | MEG X570 UNIFY              | [0eb5cecbac](https://linux-hardware.org/?probe=0eb5cecbac) | Jan 12, 2022 |
| Gigabyte      | GA-970A-UD3                 | [bb65153cf2](https://linux-hardware.org/?probe=bb65153cf2) | Jan 12, 2022 |
| MSI           | MEG X570 UNIFY              | [102e1371f8](https://linux-hardware.org/?probe=102e1371f8) | Jan 11, 2022 |
| ASUSTek       | P5K Deluxe                  | [0c0a6589e8](https://linux-hardware.org/?probe=0c0a6589e8) | Jan 11, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [2cbbce1a0e](https://linux-hardware.org/?probe=2cbbce1a0e) | Jan 10, 2022 |
| ASUSTek       | H87M-PLUS                   | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| Gigabyte      | H55M-USB3                   | [aad9837ee4](https://linux-hardware.org/?probe=aad9837ee4) | Jan 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [ad5ae136c9](https://linux-hardware.org/?probe=ad5ae136c9) | Jan 05, 2022 |
| Dell          | 096JG8 A01                  | [fecf0d29c7](https://linux-hardware.org/?probe=fecf0d29c7) | Jan 05, 2022 |
| MSI           | 2A9Ch                       | [358b325347](https://linux-hardware.org/?probe=358b325347) | Jan 05, 2022 |
| Gigabyte      | X570 AORUS PRO              | [843345dfe6](https://linux-hardware.org/?probe=843345dfe6) | Jan 04, 2022 |
| Medion        | Cattle24 1M                 | [9980b9fb17](https://linux-hardware.org/?probe=9980b9fb17) | Jan 04, 2022 |
| ASUSTek       | P5K Deluxe                  | [bb8b56ca21](https://linux-hardware.org/?probe=bb8b56ca21) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [5209cf627a](https://linux-hardware.org/?probe=5209cf627a) | Jan 02, 2022 |
| ASUSTek       | P5K Deluxe                  | [48524c94d1](https://linux-hardware.org/?probe=48524c94d1) | Jan 01, 2022 |
| Intel         | DP35DP AAD81073-208         | [469127a5f9](https://linux-hardware.org/?probe=469127a5f9) | Dec 31, 2021 |
| MSI           | 2A9C                        | [2e51628103](https://linux-hardware.org/?probe=2e51628103) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1c36b4c1cd](https://linux-hardware.org/?probe=1c36b4c1cd) | Dec 29, 2021 |
| ASUSTek       | H170M-PLUS                  | [997c8caab6](https://linux-hardware.org/?probe=997c8caab6) | Dec 29, 2021 |
| Gigabyte      | H55M-USB3                   | [6ae95f862e](https://linux-hardware.org/?probe=6ae95f862e) | Dec 28, 2021 |
| Intel         | MONTARA                     | [963db2e79c](https://linux-hardware.org/?probe=963db2e79c) | Dec 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | [41edb1b55b](https://linux-hardware.org/?probe=41edb1b55b) | Dec 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | [f113b07c3e](https://linux-hardware.org/?probe=f113b07c3e) | Dec 26, 2021 |
| Shuttle       | FZ87                        | [e26f5a10e8](https://linux-hardware.org/?probe=e26f5a10e8) | Dec 24, 2021 |
| Shuttle       | FZ87                        | [62a0a858a6](https://linux-hardware.org/?probe=62a0a858a6) | Dec 24, 2021 |
| HP            | 3048h                       | [2e47687170](https://linux-hardware.org/?probe=2e47687170) | Dec 23, 2021 |
| ASRock        | Z77 Pro3                    | [da59408c08](https://linux-hardware.org/?probe=da59408c08) | Dec 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [72ba2d0d17](https://linux-hardware.org/?probe=72ba2d0d17) | Dec 22, 2021 |
| Lenovo        | 3176 SDK0J40697 WIN 3305... | [7ffa31df44](https://linux-hardware.org/?probe=7ffa31df44) | Dec 20, 2021 |
| ASUSTek       | PRIME X570-P                | [711a930635](https://linux-hardware.org/?probe=711a930635) | Dec 20, 2021 |
| Dell          | 0KC9NP A01                  | [aa65cbb14e](https://linux-hardware.org/?probe=aa65cbb14e) | Dec 19, 2021 |
| HP            | 8056                        | [68992da248](https://linux-hardware.org/?probe=68992da248) | Dec 19, 2021 |
| Dell          | 0KWVT8 A02                  | [60db65ec3a](https://linux-hardware.org/?probe=60db65ec3a) | Dec 19, 2021 |
| HP            | 18E4                        | [b4a1d6b778](https://linux-hardware.org/?probe=b4a1d6b778) | Dec 19, 2021 |
| ASUSTek       | H170M-PLUS                  | [3e25d6dd20](https://linux-hardware.org/?probe=3e25d6dd20) | Dec 18, 2021 |
| Medion        | Cattle24 1M                 | [2d145ac87e](https://linux-hardware.org/?probe=2d145ac87e) | Dec 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | [c821efaed8](https://linux-hardware.org/?probe=c821efaed8) | Dec 14, 2021 |
| Medion        | Cattle24 1M                 | [4fdfe223e0](https://linux-hardware.org/?probe=4fdfe223e0) | Dec 13, 2021 |
| Intel         | DG965WH AAD41692-304        | [663a79c9de](https://linux-hardware.org/?probe=663a79c9de) | Dec 11, 2021 |
| Intel         | DG965WH AAD41692-304        | [4166d874cc](https://linux-hardware.org/?probe=4166d874cc) | Dec 11, 2021 |
| ASRock        | B560M-HDV                   | [6390e2db9b](https://linux-hardware.org/?probe=6390e2db9b) | Dec 09, 2021 |
| ASUSTek       | P8Z77-V LX                  | [892d6ba035](https://linux-hardware.org/?probe=892d6ba035) | Dec 09, 2021 |
| ASUSTek       | P8Z77-V LX                  | [64c5154edc](https://linux-hardware.org/?probe=64c5154edc) | Dec 07, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| ASUSTek       | P8Z77-V LX                  | [585c81c884](https://linux-hardware.org/?probe=585c81c884) | Dec 04, 2021 |
| ASUSTek       | STRIX Z270G GAMING          | [0e777fade8](https://linux-hardware.org/?probe=0e777fade8) | Dec 03, 2021 |
| Unknown       | 1.0                         | [412614529f](https://linux-hardware.org/?probe=412614529f) | Dec 02, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [74dcac77ec](https://linux-hardware.org/?probe=74dcac77ec) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [9bbe9ad940](https://linux-hardware.org/?probe=9bbe9ad940) | Nov 27, 2021 |
| Unknown       | Unknown                     | [3b55838cb6](https://linux-hardware.org/?probe=3b55838cb6) | Nov 27, 2021 |
| Gigabyte      | EP45-DS3                    | [b7cb8d0193](https://linux-hardware.org/?probe=b7cb8d0193) | Nov 27, 2021 |
| MSI           | X99A SLI PLUS               | [6c1248588e](https://linux-hardware.org/?probe=6c1248588e) | Nov 24, 2021 |
| MSI           | X99A SLI PLUS               | [4ae4bcc876](https://linux-hardware.org/?probe=4ae4bcc876) | Nov 24, 2021 |
| ASUSTek       | P8P67 LE                    | [0a637eba53](https://linux-hardware.org/?probe=0a637eba53) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [c0960ee402](https://linux-hardware.org/?probe=c0960ee402) | Nov 21, 2021 |
| MSI           | B450M PRO-VDH MAX           | [ec72611685](https://linux-hardware.org/?probe=ec72611685) | Nov 21, 2021 |
| Dell          | 0KRC95 A00                  | [fa7d35906a](https://linux-hardware.org/?probe=fa7d35906a) | Nov 19, 2021 |
| HP            | ProLiant ML350 Gen9         | [9a5ec34f4b](https://linux-hardware.org/?probe=9a5ec34f4b) | Nov 18, 2021 |
| ASUSTek       | Z87-DELUXE                  | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [701785b28a](https://linux-hardware.org/?probe=701785b28a) | Nov 17, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [2fd9cf16d9](https://linux-hardware.org/?probe=2fd9cf16d9) | Nov 17, 2021 |
| ASRock        | B450 Pro4                   | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| MSI           | A320M-A PRO MAX             | [09a1713d46](https://linux-hardware.org/?probe=09a1713d46) | Nov 14, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [a283cb744b](https://linux-hardware.org/?probe=a283cb744b) | Nov 13, 2021 |
| ASRock        | X570 Steel Legend           | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Dell          | 0KC9NP A01                  | [20898da2a5](https://linux-hardware.org/?probe=20898da2a5) | Nov 10, 2021 |
| ASRock        | Z370 Pro4                   | [e0856ca7fa](https://linux-hardware.org/?probe=e0856ca7fa) | Nov 10, 2021 |
| Intel         | DH77DF AAG40293-300         | [64ba244f45](https://linux-hardware.org/?probe=64ba244f45) | Nov 09, 2021 |
| ASUSTek       | P6T DELUXE                  | [e0d50907c2](https://linux-hardware.org/?probe=e0d50907c2) | Nov 07, 2021 |
| ASUSTek       | P6T DELUXE                  | [e4a203dda2](https://linux-hardware.org/?probe=e4a203dda2) | Nov 07, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [86f84e606c](https://linux-hardware.org/?probe=86f84e606c) | Nov 05, 2021 |
| ASUSTek       | A85XM-A                     | [f28dea1e67](https://linux-hardware.org/?probe=f28dea1e67) | Nov 03, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [5fabc60d11](https://linux-hardware.org/?probe=5fabc60d11) | Nov 03, 2021 |
| HP            | 1494                        | [ef0237e3cf](https://linux-hardware.org/?probe=ef0237e3cf) | Nov 03, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [bc49b41641](https://linux-hardware.org/?probe=bc49b41641) | Nov 03, 2021 |
| ASUSTek       | P6T DELUXE                  | [6c7ecc284b](https://linux-hardware.org/?probe=6c7ecc284b) | Oct 31, 2021 |
| ASUSTek       | P6T DELUXE                  | [f35cfefa93](https://linux-hardware.org/?probe=f35cfefa93) | Oct 31, 2021 |
| HP            | 1998                        | [f943d839a8](https://linux-hardware.org/?probe=f943d839a8) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS PRO              | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Acer          | Aspire X3450                | [8f27aff70b](https://linux-hardware.org/?probe=8f27aff70b) | Oct 27, 2021 |
| Supermicro    | X9DR3-F                     | [6908407322](https://linux-hardware.org/?probe=6908407322) | Oct 26, 2021 |
| Pegatron      | 2AB5                        | [d19235c3d0](https://linux-hardware.org/?probe=d19235c3d0) | Oct 24, 2021 |
| ASUSTek       | PRIME Z390-P                | [681b537e82](https://linux-hardware.org/?probe=681b537e82) | Oct 23, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | [117223995c](https://linux-hardware.org/?probe=117223995c) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | [e97646cc2e](https://linux-hardware.org/?probe=e97646cc2e) | Oct 23, 2021 |
| Dell          | 0KC9NP A01                  | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [2edb67185b](https://linux-hardware.org/?probe=2edb67185b) | Oct 21, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [88785336ba](https://linux-hardware.org/?probe=88785336ba) | Oct 19, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [b8d302afbb](https://linux-hardware.org/?probe=b8d302afbb) | Oct 19, 2021 |
| ASUSTek       | Z87-PRO                     | [6bb186c28b](https://linux-hardware.org/?probe=6bb186c28b) | Oct 19, 2021 |
| Gigabyte      | H55M-USB3                   | [4f5274c16a](https://linux-hardware.org/?probe=4f5274c16a) | Oct 17, 2021 |
| HP            | 870C                        | [8b056a8a9f](https://linux-hardware.org/?probe=8b056a8a9f) | Oct 16, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| HP            | 8054                        | [ba0e318652](https://linux-hardware.org/?probe=ba0e318652) | Oct 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [3638982195](https://linux-hardware.org/?probe=3638982195) | Oct 12, 2021 |
| HP            | 8054                        | [9a1bdf2e07](https://linux-hardware.org/?probe=9a1bdf2e07) | Oct 10, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [cfbe862160](https://linux-hardware.org/?probe=cfbe862160) | Oct 10, 2021 |
| ASRock        | J4105B-ITX                  | [33fc4b9e37](https://linux-hardware.org/?probe=33fc4b9e37) | Oct 08, 2021 |
| ASUSTek       | Z87-DELUXE                  | [63b48dfa23](https://linux-hardware.org/?probe=63b48dfa23) | Oct 07, 2021 |
| Acer          | Aspire XC-886 V:2.0         | [e9ee820848](https://linux-hardware.org/?probe=e9ee820848) | Oct 06, 2021 |
| ASUSTek       | P7P55D LE                   | [21e7391f6a](https://linux-hardware.org/?probe=21e7391f6a) | Oct 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | [2792a3ef1c](https://linux-hardware.org/?probe=2792a3ef1c) | Oct 03, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [a31bd40281](https://linux-hardware.org/?probe=a31bd40281) | Oct 03, 2021 |
| Gigabyte      | Z97-HD3                     | [de56866167](https://linux-hardware.org/?probe=de56866167) | Sep 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | [4340e989f9](https://linux-hardware.org/?probe=4340e989f9) | Sep 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b2b889b773](https://linux-hardware.org/?probe=b2b889b773) | Sep 16, 2021 |
| Dell          | 0YJPT1 A00                  | [69d571e9f5](https://linux-hardware.org/?probe=69d571e9f5) | Sep 15, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [491b5db2ce](https://linux-hardware.org/?probe=491b5db2ce) | Sep 12, 2021 |
| Gigabyte      | P35-DS4                     | [ff9057981b](https://linux-hardware.org/?probe=ff9057981b) | Sep 11, 2021 |
| Gigabyte      | P35-DS4                     | [d5cbc70a78](https://linux-hardware.org/?probe=d5cbc70a78) | Sep 11, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [74d478552c](https://linux-hardware.org/?probe=74d478552c) | Sep 10, 2021 |
| HP            | 8750                        | [b5bbf3502f](https://linux-hardware.org/?probe=b5bbf3502f) | Sep 08, 2021 |
| Dell          | 0NW6H5 A00                  | [c9716b0149](https://linux-hardware.org/?probe=c9716b0149) | Sep 06, 2021 |
| HP            | 870C                        | [f46fa4ba94](https://linux-hardware.org/?probe=f46fa4ba94) | Sep 06, 2021 |
| HP            | 870C                        | [fcd88590bc](https://linux-hardware.org/?probe=fcd88590bc) | Sep 06, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [c98e112d49](https://linux-hardware.org/?probe=c98e112d49) | Sep 05, 2021 |
| MSI           | IONA                        | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| MSI           | AMETHYST-M                  | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| MSI           | IONA                        | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| HP            | 3396                        | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| Unknown       | Unknown                     | [022e87f791](https://linux-hardware.org/?probe=022e87f791) | Sep 04, 2021 |
| ASRock        | Z370 Pro4                   | [a507f9835b](https://linux-hardware.org/?probe=a507f9835b) | Sep 03, 2021 |
| ASUSTek       | P7P55D LE                   | [8bbe7e58ae](https://linux-hardware.org/?probe=8bbe7e58ae) | Sep 02, 2021 |
| ASUSTek       | P7P55D LE                   | [21fd5c096a](https://linux-hardware.org/?probe=21fd5c096a) | Sep 02, 2021 |
| Gigabyte      | G41M-ES2L                   | [b9fdcaf2f7](https://linux-hardware.org/?probe=b9fdcaf2f7) | Sep 02, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [61fdddc7a9](https://linux-hardware.org/?probe=61fdddc7a9) | Sep 01, 2021 |
| ASUSTek       | Q87M-E                      | [588e2a68e5](https://linux-hardware.org/?probe=588e2a68e5) | Aug 28, 2021 |
| ASRock        | B450M Steel Legend          | [9b335e87fe](https://linux-hardware.org/?probe=9b335e87fe) | Aug 28, 2021 |
| Pegatron      | IPMSB-GS                    | [b17f032a44](https://linux-hardware.org/?probe=b17f032a44) | Aug 27, 2021 |
| Pegatron      | IPMSB-GS                    | [9d2bbbabf1](https://linux-hardware.org/?probe=9d2bbbabf1) | Aug 27, 2021 |
| Shuttle       | FH61V                       | [11b6744d1c](https://linux-hardware.org/?probe=11b6744d1c) | Aug 27, 2021 |
| ASRock        | B550M Pro4                  | [2135d34339](https://linux-hardware.org/?probe=2135d34339) | Aug 25, 2021 |
| Shuttle       | FH61V                       | [1b74c0ad1d](https://linux-hardware.org/?probe=1b74c0ad1d) | Aug 25, 2021 |
| HP            | 8054                        | [d54cd14c63](https://linux-hardware.org/?probe=d54cd14c63) | Aug 24, 2021 |
| MSI           | Z170-A PRO                  | [6713ee6c8f](https://linux-hardware.org/?probe=6713ee6c8f) | Aug 22, 2021 |
| MSI           | Z97 XPOWER AC               | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| Dell          | 0KC9NP A01                  | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [6d761276c9](https://linux-hardware.org/?probe=6d761276c9) | Aug 16, 2021 |
| MSI           | MEG X570 UNIFY              | [8724bdb133](https://linux-hardware.org/?probe=8724bdb133) | Aug 15, 2021 |
| MSI           | MEG X570 UNIFY              | [21e8e956d2](https://linux-hardware.org/?probe=21e8e956d2) | Aug 15, 2021 |
| Dell          | 096JG8 A01                  | [64f4c407c6](https://linux-hardware.org/?probe=64f4c407c6) | Aug 14, 2021 |
| MSI           | B550-A PRO                  | [b3ff3985c5](https://linux-hardware.org/?probe=b3ff3985c5) | Aug 13, 2021 |
| Gigabyte      | H81M-D2V                    | [3f6cd51532](https://linux-hardware.org/?probe=3f6cd51532) | Aug 13, 2021 |
| Dell          | 0KC9NP A01                  | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| ASUSTek       | P7H55-M/USB3                | [5091bbdda5](https://linux-hardware.org/?probe=5091bbdda5) | Aug 11, 2021 |
| ASRock        | B550M Pro4                  | [9092457b4b](https://linux-hardware.org/?probe=9092457b4b) | Aug 10, 2021 |
| ASUSTek       | H87M-PLUS                   | [c2ed04ce87](https://linux-hardware.org/?probe=c2ed04ce87) | Aug 09, 2021 |
| Biostar       | X370GTN                     | [eeff407867](https://linux-hardware.org/?probe=eeff407867) | Aug 08, 2021 |
| MSI           | Z97 XPOWER AC               | [a8b7705861](https://linux-hardware.org/?probe=a8b7705861) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| ASRock        | B550M Pro4                  | [7d11767c07](https://linux-hardware.org/?probe=7d11767c07) | Aug 07, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [b42131915e](https://linux-hardware.org/?probe=b42131915e) | Aug 05, 2021 |
| ASRock        | Z170 OC Formula             | [0d1ca849b8](https://linux-hardware.org/?probe=0d1ca849b8) | Jul 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [8dbd1ca0eb](https://linux-hardware.org/?probe=8dbd1ca0eb) | Jul 26, 2021 |
| Dell          | 0HD5W2 A01                  | [ece0155c70](https://linux-hardware.org/?probe=ece0155c70) | Jul 20, 2021 |
| ASUSTek       | Maximus IV Extreme          | [592fa7e11f](https://linux-hardware.org/?probe=592fa7e11f) | Jul 18, 2021 |
| Dell          | 0K240Y A02                  | [c2ed93c130](https://linux-hardware.org/?probe=c2ed93c130) | Jul 07, 2021 |
| ASUSTek       | Z87-DELUXE                  | [3aa1e79866](https://linux-hardware.org/?probe=3aa1e79866) | Jul 05, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [734f246fde](https://linux-hardware.org/?probe=734f246fde) | Jul 02, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [0ffffb72ed](https://linux-hardware.org/?probe=0ffffb72ed) | Jul 02, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| HP            | 8056                        | [d10cd539f1](https://linux-hardware.org/?probe=d10cd539f1) | Jul 01, 2021 |
| Dell          | 0K240Y A02                  | [ddaae68bd8](https://linux-hardware.org/?probe=ddaae68bd8) | Jun 30, 2021 |
| Lenovo        | 31900058 STD                | [338127e8ca](https://linux-hardware.org/?probe=338127e8ca) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [68cd01f446](https://linux-hardware.org/?probe=68cd01f446) | Jun 25, 2021 |
| HP            | 8703                        | [e43f806f55](https://linux-hardware.org/?probe=e43f806f55) | Jun 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [7366bb28e8](https://linux-hardware.org/?probe=7366bb28e8) | Jun 19, 2021 |
| Dell          | 0KC9NP A01                  | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Dell          | 0D28YY A00                  | [d9cac45ec3](https://linux-hardware.org/?probe=d9cac45ec3) | Jun 16, 2021 |
| MSI           | B360M PRO-VH                | [78845a4897](https://linux-hardware.org/?probe=78845a4897) | Jun 15, 2021 |
| Acer          | Aspire X3400                | [8fcc9b6607](https://linux-hardware.org/?probe=8fcc9b6607) | Jun 10, 2021 |
| HP            | 0B4Ch D                     | [5ac932248a](https://linux-hardware.org/?probe=5ac932248a) | Jun 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [68ec58f92a](https://linux-hardware.org/?probe=68ec58f92a) | Jun 08, 2021 |
| Pegatron      | 2AD5                        | [503cffa288](https://linux-hardware.org/?probe=503cffa288) | Jun 08, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5521709029](https://linux-hardware.org/?probe=5521709029) | Jun 08, 2021 |
| HP            | 3032h                       | [dade0cb1d6](https://linux-hardware.org/?probe=dade0cb1d6) | Jun 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [62ddf1b4f0](https://linux-hardware.org/?probe=62ddf1b4f0) | May 31, 2021 |
| HP            | 3032h                       | [ea009f77d1](https://linux-hardware.org/?probe=ea009f77d1) | May 31, 2021 |
| HP            | 8056                        | [fc6d4c2e7d](https://linux-hardware.org/?probe=fc6d4c2e7d) | May 30, 2021 |
| ASRock        | B450M-HDV R4.0              | [0f7555a7bd](https://linux-hardware.org/?probe=0f7555a7bd) | May 30, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [8ab1f1c2cf](https://linux-hardware.org/?probe=8ab1f1c2cf) | May 29, 2021 |
| HP            | 18E7                        | [74314fffc3](https://linux-hardware.org/?probe=74314fffc3) | May 27, 2021 |
| HP            | 18E7                        | [dbb0731dd9](https://linux-hardware.org/?probe=dbb0731dd9) | May 27, 2021 |
| Gigabyte      | B550 GAMING X V2            | [75bca9816e](https://linux-hardware.org/?probe=75bca9816e) | May 23, 2021 |
| Gigabyte      | B550 GAMING X V2            | [bc4b4dca67](https://linux-hardware.org/?probe=bc4b4dca67) | May 23, 2021 |
| Gigabyte      | P35-DQ6                     | [5b2102ba4e](https://linux-hardware.org/?probe=5b2102ba4e) | May 23, 2021 |
| Gigabyte      | P35-DQ6                     | [e5ef68ed7f](https://linux-hardware.org/?probe=e5ef68ed7f) | May 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [92d06972e9](https://linux-hardware.org/?probe=92d06972e9) | May 22, 2021 |
| eMachines     | ET1861                      | [732f584b67](https://linux-hardware.org/?probe=732f584b67) | May 22, 2021 |
| HP            | 8055                        | [d6291acc4a](https://linux-hardware.org/?probe=d6291acc4a) | May 20, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [895d614ba3](https://linux-hardware.org/?probe=895d614ba3) | May 19, 2021 |
| Pegatron      | NARRA3                      | [38ac9a9ea6](https://linux-hardware.org/?probe=38ac9a9ea6) | May 18, 2021 |
| HP            | 87C3                        | [6ef8441fda](https://linux-hardware.org/?probe=6ef8441fda) | May 16, 2021 |
| ASUSTek       | PRIME X370-PRO              | [d180569750](https://linux-hardware.org/?probe=d180569750) | May 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [344858ad94](https://linux-hardware.org/?probe=344858ad94) | May 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [a1d8f5a045](https://linux-hardware.org/?probe=a1d8f5a045) | May 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [25a571732b](https://linux-hardware.org/?probe=25a571732b) | May 15, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [356a329ce3](https://linux-hardware.org/?probe=356a329ce3) | May 14, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [ef1799419d](https://linux-hardware.org/?probe=ef1799419d) | May 12, 2021 |
| ASUSTek       | B85M-G                      | [29ad7fb8e1](https://linux-hardware.org/?probe=29ad7fb8e1) | May 12, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [fab7d18783](https://linux-hardware.org/?probe=fab7d18783) | May 12, 2021 |
| ASUSTek       | P8Z77-V LX                  | [e08abc7d05](https://linux-hardware.org/?probe=e08abc7d05) | May 08, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [d20858b78f](https://linux-hardware.org/?probe=d20858b78f) | May 08, 2021 |
| ASUSTek       | Z170-PRO                    | [f72c74aa38](https://linux-hardware.org/?probe=f72c74aa38) | May 06, 2021 |
| Lenovo        | ThinkCentre M58 8820AJG     | [239c4bf44d](https://linux-hardware.org/?probe=239c4bf44d) | May 06, 2021 |
| Lenovo        | 30C7 SDK0J40709 WIN 3259... | [24f944159d](https://linux-hardware.org/?probe=24f944159d) | May 05, 2021 |
| ASRock        | X300M-STX                   | [ff0d2758aa](https://linux-hardware.org/?probe=ff0d2758aa) | May 04, 2021 |
| ASRock        | X79 Extreme4                | [87e9e3ff1c](https://linux-hardware.org/?probe=87e9e3ff1c) | May 04, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [523fba1dd3](https://linux-hardware.org/?probe=523fba1dd3) | May 04, 2021 |
| MSI           | Z170-A PRO                  | [7a38618a4f](https://linux-hardware.org/?probe=7a38618a4f) | May 02, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [d490ee9c19](https://linux-hardware.org/?probe=d490ee9c19) | May 02, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [5be5e699bf](https://linux-hardware.org/?probe=5be5e699bf) | May 02, 2021 |
| Dell          | 0KC9NP A01                  | [019f1d6c17](https://linux-hardware.org/?probe=019f1d6c17) | Apr 30, 2021 |
| MSI           | Z170-A PRO                  | [9689ca0570](https://linux-hardware.org/?probe=9689ca0570) | Apr 30, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [fcfd291a4f](https://linux-hardware.org/?probe=fcfd291a4f) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fb11e4cdcc](https://linux-hardware.org/?probe=fb11e4cdcc) | Apr 29, 2021 |
| HP            | 8056                        | [34d3f923a3](https://linux-hardware.org/?probe=34d3f923a3) | Apr 29, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [2ff23ca44c](https://linux-hardware.org/?probe=2ff23ca44c) | Apr 28, 2021 |
| ASUSTek       | H87M-PLUS                   | [7ecfe05882](https://linux-hardware.org/?probe=7ecfe05882) | Apr 25, 2021 |
| Dell          | 0TP406                      | [5a53a4349a](https://linux-hardware.org/?probe=5a53a4349a) | Apr 21, 2021 |
| HP            | 0B4Ch D                     | [3721f71fb0](https://linux-hardware.org/?probe=3721f71fb0) | Apr 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [414dee060e](https://linux-hardware.org/?probe=414dee060e) | Apr 15, 2021 |
| HP            | 3033h                       | [bbdefab03d](https://linux-hardware.org/?probe=bbdefab03d) | Apr 13, 2021 |
| Dell          | 0TP406                      | [d903abaa08](https://linux-hardware.org/?probe=d903abaa08) | Apr 10, 2021 |
| Dell          | 0TP406                      | [bf1adf4111](https://linux-hardware.org/?probe=bf1adf4111) | Apr 10, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [3dd02b4af9](https://linux-hardware.org/?probe=3dd02b4af9) | Apr 09, 2021 |
| ASRock        | B550M Pro4                  | [5bc4edd8b4](https://linux-hardware.org/?probe=5bc4edd8b4) | Apr 08, 2021 |
| HP            | 1497                        | [d93ce1eeb3](https://linux-hardware.org/?probe=d93ce1eeb3) | Apr 07, 2021 |
| ASUSTek       | Z87-DELUXE                  | [e4f7f8688b](https://linux-hardware.org/?probe=e4f7f8688b) | Apr 05, 2021 |
| ASUSTek       | H97-PLUS                    | [cc943c576f](https://linux-hardware.org/?probe=cc943c576f) | Apr 05, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1f560968ab](https://linux-hardware.org/?probe=1f560968ab) | Apr 04, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [c5010e1348](https://linux-hardware.org/?probe=c5010e1348) | Apr 03, 2021 |
| Acer          | Predator G3610              | [58f942e8c3](https://linux-hardware.org/?probe=58f942e8c3) | Apr 02, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [9e4b82fb49](https://linux-hardware.org/?probe=9e4b82fb49) | Apr 02, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [2b3b29eb9e](https://linux-hardware.org/?probe=2b3b29eb9e) | Apr 02, 2021 |
| ASUSTek       | P7H55-M PRO                 | [426f11f2d2](https://linux-hardware.org/?probe=426f11f2d2) | Mar 31, 2021 |
| Gigabyte      | B460M AORUS PRO             | [d40236931f](https://linux-hardware.org/?probe=d40236931f) | Mar 31, 2021 |
| ASRock        | Z77 Pro4                    | [981009625b](https://linux-hardware.org/?probe=981009625b) | Mar 29, 2021 |
| Medion        | MS-7621                     | [d0f1e17b38](https://linux-hardware.org/?probe=d0f1e17b38) | Mar 29, 2021 |
| HP            | 1497                        | [57f83dc5e5](https://linux-hardware.org/?probe=57f83dc5e5) | Mar 28, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [7ccab1854d](https://linux-hardware.org/?probe=7ccab1854d) | Mar 27, 2021 |
| Gigabyte      | X570 AORUS PRO              | [a21b63e491](https://linux-hardware.org/?probe=a21b63e491) | Mar 26, 2021 |
| HP            | 1497                        | [d28570a6cb](https://linux-hardware.org/?probe=d28570a6cb) | Mar 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0e12cc8e95](https://linux-hardware.org/?probe=0e12cc8e95) | Mar 25, 2021 |
| PC Engines    | APU2                        | [76bdee5902](https://linux-hardware.org/?probe=76bdee5902) | Mar 24, 2021 |
| PC Engines    | APU2                        | [c8a3d807bb](https://linux-hardware.org/?probe=c8a3d807bb) | Mar 24, 2021 |
| PC Engines    | APU2                        | [aacc455c74](https://linux-hardware.org/?probe=aacc455c74) | Mar 24, 2021 |
| ASUSTek       | H170M-E D3                  | [454261a973](https://linux-hardware.org/?probe=454261a973) | Mar 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [1ef0fbf40d](https://linux-hardware.org/?probe=1ef0fbf40d) | Mar 23, 2021 |
| Shuttle       | FH61R                       | [5b90db2538](https://linux-hardware.org/?probe=5b90db2538) | Mar 21, 2021 |
| Acer          | Predator PO3-600 V:1.1      | [329c4eed31](https://linux-hardware.org/?probe=329c4eed31) | Mar 20, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [2892bb172b](https://linux-hardware.org/?probe=2892bb172b) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ceb09854c9](https://linux-hardware.org/?probe=ceb09854c9) | Mar 18, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | [75cb082ef8](https://linux-hardware.org/?probe=75cb082ef8) | Mar 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7156475fba](https://linux-hardware.org/?probe=7156475fba) | Mar 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [63e83f6ac6](https://linux-hardware.org/?probe=63e83f6ac6) | Mar 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [1111114ddb](https://linux-hardware.org/?probe=1111114ddb) | Mar 15, 2021 |
| eMachines     | ET1861                      | [c8e6e483f5](https://linux-hardware.org/?probe=c8e6e483f5) | Mar 15, 2021 |
| Gigabyte      | H110-D3A-CF                 | [2847b20ae0](https://linux-hardware.org/?probe=2847b20ae0) | Mar 14, 2021 |
| HP            | 1998                        | [78e05b078e](https://linux-hardware.org/?probe=78e05b078e) | Mar 12, 2021 |
| HP            | 1998                        | [2d721136a1](https://linux-hardware.org/?probe=2d721136a1) | Mar 12, 2021 |
| Gigabyte      | EP35-DS3R                   | [4ebcc8525d](https://linux-hardware.org/?probe=4ebcc8525d) | Mar 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5f46359865](https://linux-hardware.org/?probe=5f46359865) | Mar 12, 2021 |
| ASUSTek       | PRIME Z270-P                | [f5a10112c1](https://linux-hardware.org/?probe=f5a10112c1) | Mar 12, 2021 |
| Gigabyte      | EP35-DS3R                   | [0c64fa32bb](https://linux-hardware.org/?probe=0c64fa32bb) | Mar 12, 2021 |
| ASRock        | B550M Pro4                  | [32ba5b9a6e](https://linux-hardware.org/?probe=32ba5b9a6e) | Mar 11, 2021 |
| ASUSTek       | P8H67-M EVO                 | [7cac1d69b0](https://linux-hardware.org/?probe=7cac1d69b0) | Mar 11, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [55af96f7d6](https://linux-hardware.org/?probe=55af96f7d6) | Mar 11, 2021 |
| ASUSTek       | P8H67-M EVO                 | [ac9a248a29](https://linux-hardware.org/?probe=ac9a248a29) | Mar 11, 2021 |
| ASUSTek       | P8H67-M EVO                 | [c20fa07cef](https://linux-hardware.org/?probe=c20fa07cef) | Mar 11, 2021 |
| ASUSTek       | PRIME B450M-A               | [5c28995118](https://linux-hardware.org/?probe=5c28995118) | Mar 10, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [56dfe79cf3](https://linux-hardware.org/?probe=56dfe79cf3) | Mar 09, 2021 |
| ASUSTek       | AM1M-A                      | [bdbb6f7cb7](https://linux-hardware.org/?probe=bdbb6f7cb7) | Mar 09, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [26b1d3237f](https://linux-hardware.org/?probe=26b1d3237f) | Mar 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [ae4c33fe91](https://linux-hardware.org/?probe=ae4c33fe91) | Mar 09, 2021 |
| ASUSTek       | P8H67-M EVO                 | [63c5c732d0](https://linux-hardware.org/?probe=63c5c732d0) | Mar 09, 2021 |
| HP            | 843B                        | [6c0504f168](https://linux-hardware.org/?probe=6c0504f168) | Mar 08, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [43719f69cc](https://linux-hardware.org/?probe=43719f69cc) | Mar 08, 2021 |
| Acer          | Predator G3610              | [49b3263bb1](https://linux-hardware.org/?probe=49b3263bb1) | Mar 07, 2021 |
| Dell          | 0R230R A00                  | [d51bdac334](https://linux-hardware.org/?probe=d51bdac334) | Mar 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [d80f548759](https://linux-hardware.org/?probe=d80f548759) | Mar 04, 2021 |
| ASUSTek       | Z170-A                      | [1c477e6a87](https://linux-hardware.org/?probe=1c477e6a87) | Feb 28, 2021 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [e684219b02](https://linux-hardware.org/?probe=e684219b02) | Feb 25, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [91e4ee1214](https://linux-hardware.org/?probe=91e4ee1214) | Feb 24, 2021 |
| ASUSTek       | P8H67-V                     | [3dac06ca11](https://linux-hardware.org/?probe=3dac06ca11) | Feb 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [52b46f5660](https://linux-hardware.org/?probe=52b46f5660) | Feb 23, 2021 |
| Dell          | 0WG855                      | [2d58070beb](https://linux-hardware.org/?probe=2d58070beb) | Feb 23, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [ede7d0e26c](https://linux-hardware.org/?probe=ede7d0e26c) | Feb 21, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [6e7ed306ee](https://linux-hardware.org/?probe=6e7ed306ee) | Feb 20, 2021 |
| Dell          | 06XMFM A01                  | [648b9905de](https://linux-hardware.org/?probe=648b9905de) | Feb 20, 2021 |
| ASUSTek       | PRIME B350M-A               | [201d0f8a0c](https://linux-hardware.org/?probe=201d0f8a0c) | Feb 20, 2021 |
| ASRock        | Z77 Pro4                    | [ac6c97daff](https://linux-hardware.org/?probe=ac6c97daff) | Feb 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5e5ead9c6a](https://linux-hardware.org/?probe=5e5ead9c6a) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [184fbe6548](https://linux-hardware.org/?probe=184fbe6548) | Feb 18, 2021 |
| MSI           | Z370 GAMING PLUS            | [b098b42d49](https://linux-hardware.org/?probe=b098b42d49) | Feb 18, 2021 |
| ASUSTek       | P8P67 LE                    | [e0a760df71](https://linux-hardware.org/?probe=e0a760df71) | Feb 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [23e2da6146](https://linux-hardware.org/?probe=23e2da6146) | Feb 17, 2021 |
| HP            | 2B2C                        | [8c45c42df1](https://linux-hardware.org/?probe=8c45c42df1) | Feb 17, 2021 |
| HP            | 845A                        | [9e9db37079](https://linux-hardware.org/?probe=9e9db37079) | Feb 16, 2021 |
| HP            | 8703                        | [5f8e1f5b57](https://linux-hardware.org/?probe=5f8e1f5b57) | Feb 15, 2021 |
| ASRock        | 990FX Extreme3              | [8815b92009](https://linux-hardware.org/?probe=8815b92009) | Feb 15, 2021 |
| ASRock        | Z77E-ITX                    | [ce16fccf9d](https://linux-hardware.org/?probe=ce16fccf9d) | Feb 14, 2021 |
| ASUSTek       | P8Z77-V LX                  | [23a6027065](https://linux-hardware.org/?probe=23a6027065) | Feb 14, 2021 |
| ASRock        | B450M-HDV R4.0              | [fd9c733ca2](https://linux-hardware.org/?probe=fd9c733ca2) | Feb 14, 2021 |
| Gigabyte      | H81M-D2W                    | [0c4d4005b0](https://linux-hardware.org/?probe=0c4d4005b0) | Feb 13, 2021 |
| ASUSTek       | P5Q-E                       | [381e94eee9](https://linux-hardware.org/?probe=381e94eee9) | Feb 13, 2021 |
| ASUSTek       | P8H67-V                     | [02406791c2](https://linux-hardware.org/?probe=02406791c2) | Feb 13, 2021 |
| HP            | ProLiant MicroServer Gen... | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| ASRock        | 990FX Extreme3              | [1c912f6f4b](https://linux-hardware.org/?probe=1c912f6f4b) | Feb 11, 2021 |
| Intel         | ChiefRiver                  | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| MSI           | B450M MORTAR MAX            | [6e5763c38e](https://linux-hardware.org/?probe=6e5763c38e) | Feb 08, 2021 |
| Pegatron      | 2AB5                        | [a37995c746](https://linux-hardware.org/?probe=a37995c746) | Feb 08, 2021 |
| ASUSTek       | M5A99X EVO                  | [899f63eec0](https://linux-hardware.org/?probe=899f63eec0) | Feb 07, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f9f288372e](https://linux-hardware.org/?probe=f9f288372e) | Feb 06, 2021 |
| ASUSTek       | Z87-EXPERT                  | [9815c7f01c](https://linux-hardware.org/?probe=9815c7f01c) | Feb 03, 2021 |
| Pegatron      | 2AB5                        | [c35aaa7489](https://linux-hardware.org/?probe=c35aaa7489) | Feb 03, 2021 |
| ASUSTek       | G20CB                       | [253070b21b](https://linux-hardware.org/?probe=253070b21b) | Feb 01, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [c8b5f3921a](https://linux-hardware.org/?probe=c8b5f3921a) | Jan 31, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9947e9c2b1](https://linux-hardware.org/?probe=9947e9c2b1) | Jan 31, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [015d322a6f](https://linux-hardware.org/?probe=015d322a6f) | Jan 31, 2021 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [2b8a47f04b](https://linux-hardware.org/?probe=2b8a47f04b) | Jan 30, 2021 |
| ASUSTek       | F1A75-V PRO                 | [c317851bb7](https://linux-hardware.org/?probe=c317851bb7) | Jan 30, 2021 |
| ASUSTek       | P5KPL-SE                    | [58ac4fe903](https://linux-hardware.org/?probe=58ac4fe903) | Jan 30, 2021 |
| ASUSTek       | P5KPL-SE                    | [cecce826bf](https://linux-hardware.org/?probe=cecce826bf) | Jan 29, 2021 |
| ASUSTek       | F1A75-V PRO                 | [a52ad0ac35](https://linux-hardware.org/?probe=a52ad0ac35) | Jan 29, 2021 |
| Medion        | B360H4-EM V1.0              | [c036495c81](https://linux-hardware.org/?probe=c036495c81) | Jan 26, 2021 |
| Medion        | B360H4-EM V1.0              | [ce7dd9632f](https://linux-hardware.org/?probe=ce7dd9632f) | Jan 26, 2021 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [bf9124e2f7](https://linux-hardware.org/?probe=bf9124e2f7) | Jan 24, 2021 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [3cb541a737](https://linux-hardware.org/?probe=3cb541a737) | Jan 24, 2021 |
| HP            | 2B47                        | [406d514ed5](https://linux-hardware.org/?probe=406d514ed5) | Jan 24, 2021 |
| Pegatron      | 2AED                        | [ffee72581f](https://linux-hardware.org/?probe=ffee72581f) | Jan 23, 2021 |
| Gigabyte      | EP35-DS3R                   | [2012688df3](https://linux-hardware.org/?probe=2012688df3) | Jan 22, 2021 |
| ASRock        | X470 Taichi Ultimate        | [76934bec17](https://linux-hardware.org/?probe=76934bec17) | Jan 21, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [b5f6cc5993](https://linux-hardware.org/?probe=b5f6cc5993) | Jan 19, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [731e0dfa98](https://linux-hardware.org/?probe=731e0dfa98) | Jan 17, 2021 |
| ASUSTek       | AM1M-A                      | [287cefb90e](https://linux-hardware.org/?probe=287cefb90e) | Jan 17, 2021 |
| Acer          | Aspire X3990                | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [25fb58cc9f](https://linux-hardware.org/?probe=25fb58cc9f) | Jan 16, 2021 |
| Gigabyte      | EP35-DS3R                   | [bbc0778ca2](https://linux-hardware.org/?probe=bbc0778ca2) | Jan 15, 2021 |
| ASUSTek       | TUF H310M-PLUS GAMING       | [9d96d0c467](https://linux-hardware.org/?probe=9d96d0c467) | Jan 14, 2021 |
| ASRock        | B450M Pro4                  | [a0a962c57c](https://linux-hardware.org/?probe=a0a962c57c) | Jan 13, 2021 |
| ASRock        | B450M Pro4                  | [7cb0f8bbd2](https://linux-hardware.org/?probe=7cb0f8bbd2) | Jan 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e881933fc](https://linux-hardware.org/?probe=9e881933fc) | Jan 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9589d96b86](https://linux-hardware.org/?probe=9589d96b86) | Jan 13, 2021 |
| MSI           | Z370 GAMING PLUS            | [04aa021d72](https://linux-hardware.org/?probe=04aa021d72) | Jan 13, 2021 |
| ASRock        | J4105-ITX                   | [7917a1f444](https://linux-hardware.org/?probe=7917a1f444) | Jan 11, 2021 |
| ASUSTek       | M11AD                       | [9cf107a36f](https://linux-hardware.org/?probe=9cf107a36f) | Jan 09, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [53ebfb5925](https://linux-hardware.org/?probe=53ebfb5925) | Jan 08, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [0720e27a99](https://linux-hardware.org/?probe=0720e27a99) | Jan 06, 2021 |
| Dell          | 0Y2MRG A00                  | [df07a5791b](https://linux-hardware.org/?probe=df07a5791b) | Jan 05, 2021 |
| Dell          | 0Y2MRG A00                  | [308605d361](https://linux-hardware.org/?probe=308605d361) | Jan 05, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [403e79415b](https://linux-hardware.org/?probe=403e79415b) | Jan 01, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [120cc88a70](https://linux-hardware.org/?probe=120cc88a70) | Dec 31, 2020 |
| Gigabyte      | H110-D3A-CF                 | [cd772a516d](https://linux-hardware.org/?probe=cd772a516d) | Dec 30, 2020 |
| ASUSTek       | M51AC                       | [fa31ae75bf](https://linux-hardware.org/?probe=fa31ae75bf) | Dec 29, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [05666d1c95](https://linux-hardware.org/?probe=05666d1c95) | Dec 29, 2020 |
| ASRock        | A780GMH/128M                | [bf97146186](https://linux-hardware.org/?probe=bf97146186) | Dec 28, 2020 |
| Acer          | Predator G3-605             | [fd882239bd](https://linux-hardware.org/?probe=fd882239bd) | Dec 27, 2020 |
| ASUSTek       | H110M-A                     | [232d92124f](https://linux-hardware.org/?probe=232d92124f) | Dec 26, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [e37c5dee56](https://linux-hardware.org/?probe=e37c5dee56) | Dec 25, 2020 |
| MSI           | 970 GAMING                  | [c1da0ab577](https://linux-hardware.org/?probe=c1da0ab577) | Dec 24, 2020 |
| ASRock        | X79 Extreme6/GB             | [2f789c5a38](https://linux-hardware.org/?probe=2f789c5a38) | Dec 24, 2020 |
| ASUSTek       | M51AC                       | [30cd09db67](https://linux-hardware.org/?probe=30cd09db67) | Dec 21, 2020 |
| ASUSTek       | M51AC                       | [dd42567df3](https://linux-hardware.org/?probe=dd42567df3) | Dec 21, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [0966f43d9e](https://linux-hardware.org/?probe=0966f43d9e) | Dec 19, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [829e9caa8c](https://linux-hardware.org/?probe=829e9caa8c) | Dec 19, 2020 |
| Dell          | 0773VG A00                  | [af06892f03](https://linux-hardware.org/?probe=af06892f03) | Dec 19, 2020 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [f10be822b8](https://linux-hardware.org/?probe=f10be822b8) | Dec 17, 2020 |
| Pegatron      | IPMSB-GS                    | [dacde4d76b](https://linux-hardware.org/?probe=dacde4d76b) | Dec 14, 2020 |
| Dell          | 0KC9NP A01                  | [33f50f83ff](https://linux-hardware.org/?probe=33f50f83ff) | Dec 14, 2020 |
| Dell          | 0KC9NP A01                  | [b3ae5f5dbf](https://linux-hardware.org/?probe=b3ae5f5dbf) | Dec 14, 2020 |
| PC Engines    | apu4                        | [7231a77ab4](https://linux-hardware.org/?probe=7231a77ab4) | Dec 14, 2020 |
| PC Engines    | APU2                        | [33e1d553df](https://linux-hardware.org/?probe=33e1d553df) | Dec 14, 2020 |
| PC Engines    | APU2                        | [e062ad33d4](https://linux-hardware.org/?probe=e062ad33d4) | Dec 14, 2020 |
| PC Engines    | APU2                        | [1a4672add5](https://linux-hardware.org/?probe=1a4672add5) | Dec 14, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [6f483bd376](https://linux-hardware.org/?probe=6f483bd376) | Dec 13, 2020 |
| Medion        | MS-7707                     | [30a66403c3](https://linux-hardware.org/?probe=30a66403c3) | Dec 13, 2020 |
| eMachines     | ET1861                      | [48ea624990](https://linux-hardware.org/?probe=48ea624990) | Dec 12, 2020 |
| Packard Be... | IXTREME M5850               | [f3d8657377](https://linux-hardware.org/?probe=f3d8657377) | Dec 07, 2020 |
| MSI           | B450 TOMAHAWK               | [e5622116f9](https://linux-hardware.org/?probe=e5622116f9) | Dec 05, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [94dd9615c9](https://linux-hardware.org/?probe=94dd9615c9) | Dec 03, 2020 |
| PC Engines    | APU2                        | [569b195a9d](https://linux-hardware.org/?probe=569b195a9d) | Dec 02, 2020 |
| PC Engines    | apu4                        | [7170ad3e95](https://linux-hardware.org/?probe=7170ad3e95) | Dec 02, 2020 |
| PC Engines    | apu4                        | [38969f1f9b](https://linux-hardware.org/?probe=38969f1f9b) | Dec 02, 2020 |
| Gigabyte      | H370M DS3H-CF               | [33c705cbf6](https://linux-hardware.org/?probe=33c705cbf6) | Dec 02, 2020 |
| ASRock        | FM2A85X Extreme6            | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| ASUSTek       | Z170-PRO                    | [2c51e8d9ab](https://linux-hardware.org/?probe=2c51e8d9ab) | Nov 29, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [0a0bbf9708](https://linux-hardware.org/?probe=0a0bbf9708) | Nov 29, 2020 |
| ASUSTek       | Z170-PRO                    | [15fdf5da42](https://linux-hardware.org/?probe=15fdf5da42) | Nov 29, 2020 |
| Acer          | Veriton X4660G V:1.0        | [8eb6f7795d](https://linux-hardware.org/?probe=8eb6f7795d) | Nov 28, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [37437b477e](https://linux-hardware.org/?probe=37437b477e) | Nov 28, 2020 |
| Acer          | Veriton X4660G V:1.0        | [4691a7224b](https://linux-hardware.org/?probe=4691a7224b) | Nov 28, 2020 |
| ASUSTek       | H87-PLUS                    | [563b11dfc7](https://linux-hardware.org/?probe=563b11dfc7) | Nov 27, 2020 |
| ASUSTek       | H87-PLUS                    | [7b22071212](https://linux-hardware.org/?probe=7b22071212) | Nov 27, 2020 |
| ASRock        | J4105B-ITX                  | [f11bfd2c5d](https://linux-hardware.org/?probe=f11bfd2c5d) | Nov 22, 2020 |
| ASRock        | B450 Gaming K4              | [521ec439fa](https://linux-hardware.org/?probe=521ec439fa) | Nov 22, 2020 |
| Gigabyte      | H61M-DS2                    | [7c3fde4136](https://linux-hardware.org/?probe=7c3fde4136) | Nov 20, 2020 |
| MSI           | Z270-A PRO                  | [caf24dedc0](https://linux-hardware.org/?probe=caf24dedc0) | Nov 18, 2020 |
| MSI           | Z270-A PRO                  | [f5551f2781](https://linux-hardware.org/?probe=f5551f2781) | Nov 18, 2020 |
| Gigabyte      | G41M-ES2L                   | [965a2c7deb](https://linux-hardware.org/?probe=965a2c7deb) | Nov 14, 2020 |
| Gigabyte      | G41M-ES2L                   | [f44a4e3bfb](https://linux-hardware.org/?probe=f44a4e3bfb) | Nov 12, 2020 |
| ASUSTek       | TUF H310M-PLUS GAMING       | [4004a93f83](https://linux-hardware.org/?probe=4004a93f83) | Nov 12, 2020 |
| HP            | 198E                        | [b894e40cf6](https://linux-hardware.org/?probe=b894e40cf6) | Nov 12, 2020 |
| HP            | 198E                        | [1078da35fb](https://linux-hardware.org/?probe=1078da35fb) | Nov 12, 2020 |
| Shuttle       | FH61V                       | [078f8f6f11](https://linux-hardware.org/?probe=078f8f6f11) | Nov 11, 2020 |
| ASUSTek       | SABERTOOTH X79              | [d8543c7406](https://linux-hardware.org/?probe=d8543c7406) | Nov 09, 2020 |
| Pegatron      | IPMSB-GS                    | [977bda281d](https://linux-hardware.org/?probe=977bda281d) | Nov 05, 2020 |
| ASUSTek       | AM1M-A                      | [c70d54792c](https://linux-hardware.org/?probe=c70d54792c) | Nov 02, 2020 |
| Dell          | 0KC9NP A01                  | [b2b887c55b](https://linux-hardware.org/?probe=b2b887c55b) | Nov 01, 2020 |
| Gigabyte      | Z77M-D3H                    | [6d530055ab](https://linux-hardware.org/?probe=6d530055ab) | Oct 31, 2020 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [edbb5344b2](https://linux-hardware.org/?probe=edbb5344b2) | Oct 29, 2020 |
| ASUSTek       | P8Z77-V LX                  | [258c5c88be](https://linux-hardware.org/?probe=258c5c88be) | Oct 29, 2020 |
| ASUSTek       | H87M-PLUS                   | [7df4485d80](https://linux-hardware.org/?probe=7df4485d80) | Oct 28, 2020 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [c2d0ba9f5a](https://linux-hardware.org/?probe=c2d0ba9f5a) | Oct 26, 2020 |
| ASUSTek       | SABERTOOTH X79              | [5b96832844](https://linux-hardware.org/?probe=5b96832844) | Oct 25, 2020 |
| MSI           | B350M GAMING PRO            | [cb5ad0c5c6](https://linux-hardware.org/?probe=cb5ad0c5c6) | Oct 24, 2020 |
| Pegatron      | IPMSB-GS                    | [8175f30936](https://linux-hardware.org/?probe=8175f30936) | Oct 23, 2020 |
| Pegatron      | IPMSB-GS                    | [2c61275a87](https://linux-hardware.org/?probe=2c61275a87) | Oct 23, 2020 |
| ASUSTek       | Z97-K                       | [816557b1e9](https://linux-hardware.org/?probe=816557b1e9) | Oct 22, 2020 |
| MSI           | 990XA-GD55                  | [2f0471bbf2](https://linux-hardware.org/?probe=2f0471bbf2) | Oct 22, 2020 |
| ASUSTek       | P8H61-M LE R2.0             | [5fe1c3bf7f](https://linux-hardware.org/?probe=5fe1c3bf7f) | Oct 20, 2020 |
| ASUSTek       | PRIME B460-PLUS             | [c1bcb36fc6](https://linux-hardware.org/?probe=c1bcb36fc6) | Oct 20, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | [2833baf5af](https://linux-hardware.org/?probe=2833baf5af) | Oct 13, 2020 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [489b1319b4](https://linux-hardware.org/?probe=489b1319b4) | Oct 13, 2020 |
| ASRock        | X370 Professional Gaming    | [2b432df0be](https://linux-hardware.org/?probe=2b432df0be) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [097db248db](https://linux-hardware.org/?probe=097db248db) | Oct 12, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [ede21e126b](https://linux-hardware.org/?probe=ede21e126b) | Oct 12, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [aa1a7a9b37](https://linux-hardware.org/?probe=aa1a7a9b37) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [41141f049e](https://linux-hardware.org/?probe=41141f049e) | Oct 11, 2020 |
| Dell          | 0KC9NP A01                  | [cbe082ec38](https://linux-hardware.org/?probe=cbe082ec38) | Oct 11, 2020 |
| ASUSTek       | AM1M-A                      | [e7f8db7d2d](https://linux-hardware.org/?probe=e7f8db7d2d) | Oct 10, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [47dc69334e](https://linux-hardware.org/?probe=47dc69334e) | Oct 10, 2020 |
| HP            | 1998                        | [36f71f3062](https://linux-hardware.org/?probe=36f71f3062) | Oct 07, 2020 |
| ASUSTek       | P8P67-M                     | [1d67603237](https://linux-hardware.org/?probe=1d67603237) | Oct 06, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [31719f8646](https://linux-hardware.org/?probe=31719f8646) | Oct 06, 2020 |
| ASRock        | H77 Pro4/MVP                | [7b8341379e](https://linux-hardware.org/?probe=7b8341379e) | Oct 05, 2020 |
| ASRock        | AB350 Pro4                  | [6ba5f5a971](https://linux-hardware.org/?probe=6ba5f5a971) | Oct 05, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | [1193653309](https://linux-hardware.org/?probe=1193653309) | Oct 04, 2020 |
| ASUSTek       | AM1M-A                      | [12f0e8aae9](https://linux-hardware.org/?probe=12f0e8aae9) | Oct 04, 2020 |
| ASUSTek       | AM1M-A                      | [c621d4658d](https://linux-hardware.org/?probe=c621d4658d) | Oct 04, 2020 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [e26e52e0a5](https://linux-hardware.org/?probe=e26e52e0a5) | Oct 02, 2020 |
| ASUSTek       | H87M-PLUS                   | [07387013eb](https://linux-hardware.org/?probe=07387013eb) | Sep 30, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [0406278a16](https://linux-hardware.org/?probe=0406278a16) | Sep 29, 2020 |
| ASRock        | H77 Pro4/MVP                | [8d4c5d114f](https://linux-hardware.org/?probe=8d4c5d114f) | Sep 28, 2020 |
| MSI           | Z370 GAMING PRO CARBON      | [f6828f515f](https://linux-hardware.org/?probe=f6828f515f) | Sep 28, 2020 |
| ASRock        | X570 Creator                | [35756027f1](https://linux-hardware.org/?probe=35756027f1) | Sep 23, 2020 |
| ASUSTek       | M5A97 R2.0                  | [c00efa87f7](https://linux-hardware.org/?probe=c00efa87f7) | Sep 21, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [467adb37ce](https://linux-hardware.org/?probe=467adb37ce) | Sep 19, 2020 |
| HP            | 212B                        | [a7683d9b64](https://linux-hardware.org/?probe=a7683d9b64) | Sep 16, 2020 |
| HP            | 212B                        | [ea4618cf40](https://linux-hardware.org/?probe=ea4618cf40) | Sep 16, 2020 |
| ASRock        | X570M Pro4                  | [4e53e35223](https://linux-hardware.org/?probe=4e53e35223) | Sep 15, 2020 |
| ASUSTek       | P5Q-EM                      | [510a70ab34](https://linux-hardware.org/?probe=510a70ab34) | Sep 15, 2020 |
| ASUSTek       | P9X79 WS                    | [14142cd530](https://linux-hardware.org/?probe=14142cd530) | Sep 09, 2020 |
| ASUSTek       | P9X79 WS                    | [4734a349de](https://linux-hardware.org/?probe=4734a349de) | Sep 09, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | [04ec95546f](https://linux-hardware.org/?probe=04ec95546f) | Sep 06, 2020 |
| ASUSTek       | Z87-DELUXE                  | [beeac93f6f](https://linux-hardware.org/?probe=beeac93f6f) | Sep 04, 2020 |
| ASUSTek       | Q170T                       | [a424aaa559](https://linux-hardware.org/?probe=a424aaa559) | Sep 03, 2020 |
| Intel         | D54250WYK H13922-303        | [219e110c70](https://linux-hardware.org/?probe=219e110c70) | Sep 03, 2020 |
| Dell          | 0773VG A00                  | [7002eaa135](https://linux-hardware.org/?probe=7002eaa135) | Sep 03, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [9cd9dff24f](https://linux-hardware.org/?probe=9cd9dff24f) | Sep 03, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [755f86c144](https://linux-hardware.org/?probe=755f86c144) | Sep 03, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [40ab9f3cc9](https://linux-hardware.org/?probe=40ab9f3cc9) | Sep 03, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | [bb1b799e64](https://linux-hardware.org/?probe=bb1b799e64) | Sep 03, 2020 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [ea3b88b23f](https://linux-hardware.org/?probe=ea3b88b23f) | Sep 02, 2020 |
| Pegatron      | 2AB5                        | [06a5617e63](https://linux-hardware.org/?probe=06a5617e63) | Sep 02, 2020 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [e21dcc1b23](https://linux-hardware.org/?probe=e21dcc1b23) | Aug 31, 2020 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [cd93574726](https://linux-hardware.org/?probe=cd93574726) | Aug 31, 2020 |
| ASRock        | H170M Pro4                  | [10d84618d9](https://linux-hardware.org/?probe=10d84618d9) | Aug 29, 2020 |
| ASUSTek       | PRIME B460-PLUS             | [24cdd4715c](https://linux-hardware.org/?probe=24cdd4715c) | Aug 28, 2020 |
| ASUSTek       | PRIME B460-PLUS             | [c74ee85b0b](https://linux-hardware.org/?probe=c74ee85b0b) | Aug 26, 2020 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [9abc29d5de](https://linux-hardware.org/?probe=9abc29d5de) | Aug 21, 2020 |
| Gigabyte      | 990FXA-UD5                  | [d86cfc12cc](https://linux-hardware.org/?probe=d86cfc12cc) | Aug 19, 2020 |
| ASRock        | X570 Steel Legend           | [b5a4ca1efe](https://linux-hardware.org/?probe=b5a4ca1efe) | Aug 18, 2020 |
| Gigabyte      | 990FXA-UD5                  | [937f502004](https://linux-hardware.org/?probe=937f502004) | Aug 18, 2020 |
| HP            | 3033h                       | [11c542a41c](https://linux-hardware.org/?probe=11c542a41c) | Aug 17, 2020 |
| Gigabyte      | H81M-D2W                    | [5a58efce4c](https://linux-hardware.org/?probe=5a58efce4c) | Aug 15, 2020 |
| Dell          | 0P1KTG A00                  | [2af9ac31a0](https://linux-hardware.org/?probe=2af9ac31a0) | Aug 14, 2020 |
| Dell          | 0XCR8D A01                  | [33ff30025d](https://linux-hardware.org/?probe=33ff30025d) | Aug 11, 2020 |
| HP            | 83E7                        | [0d0c333a28](https://linux-hardware.org/?probe=0d0c333a28) | Aug 10, 2020 |
| Medion        | B360H4-EM V1.0              | [0f16448380](https://linux-hardware.org/?probe=0f16448380) | Aug 07, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 18.04                 | 142      | 15.07%  |
| Ubuntu 22.04                 | 133      | 14.12%  |
| Ubuntu 20.04                 | 116      | 12.31%  |
| openSUSE Tumbleweed-XXXXXXXX | 21       | 2.23%   |
| Linux Mint 20.3              | 20       | 2.12%   |
| Debian 11                    | 19       | 2.02%   |
| OpenMandriva 4.3             | 18       | 1.91%   |
| Ubuntu 21.10                 | 15       | 1.59%   |
| OpenMandriva 4.2             | 15       | 1.59%   |
| OpenMandriva 23.01           | 14       | 1.49%   |
| Linux Mint 20.2              | 14       | 1.49%   |
| KDE neon 20.04               | 13       | 1.38%   |
| Arch Rolling                 | 13       | 1.38%   |
| Arch                         | 13       | 1.38%   |
| Linux Mint 20.1              | 12       | 1.27%   |
| Ubuntu 19.04                 | 11       | 1.17%   |
| Linux Mint 21.1              | 11       | 1.17%   |
| Ubuntu 21.04                 | 10       | 1.06%   |
| Fedora 33                    | 10       | 1.06%   |
| Debian 10                    | 10       | 1.06%   |
| Zorin 16                     | 9        | 0.96%   |
| Pop!_OS 20.04                | 9        | 0.96%   |
| Linux Mint 20                | 9        | 0.96%   |
| Fedora 34                    | 9        | 0.96%   |
| Fedora 35                    | 8        | 0.85%   |
| Fedora 32                    | 8        | 0.85%   |
| Pop!_OS 22.04                | 7        | 0.74%   |
| Pop!_OS 21.04                | 7        | 0.74%   |
| Pop!_OS 20.10                | 7        | 0.74%   |
| ArcoLinux Rolling            | 7        | 0.74%   |
| Zorin 15                     | 6        | 0.64%   |
| Xubuntu 20.04                | 6        | 0.64%   |
| Ubuntu 22.10                 | 6        | 0.64%   |
| ROSA R9                      | 6        | 0.64%   |
| Manjaro                      | 6        | 0.64%   |
| Lubuntu 20.04                | 6        | 0.64%   |
| Linux Mint 19.3              | 6        | 0.64%   |
| Fedora 36                    | 6        | 0.64%   |
| OpenMandriva 23.03           | 5        | 0.53%   |
| Kubuntu 22.04                | 5        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 393      | 46.45%  |
| Linux Mint    | 71       | 8.39%   |
| OpenMandriva  | 53       | 6.26%   |
| Fedora        | 49       | 5.79%   |
| Debian        | 44       | 5.2%    |
| Pop!_OS       | 29       | 3.43%   |
| openSUSE      | 27       | 3.19%   |
| Arch          | 26       | 3.07%   |
| Manjaro       | 19       | 2.25%   |
| Zorin         | 15       | 1.77%   |
| KDE neon      | 15       | 1.77%   |
| Kubuntu       | 13       | 1.54%   |
| ROSA          | 10       | 1.18%   |
| Xubuntu       | 8        | 0.95%   |
| Gentoo        | 8        | 0.95%   |
| Lubuntu       | 7        | 0.83%   |
| ArcoLinux     | 7        | 0.83%   |
| CentOS        | 6        | 0.71%   |
| Ubuntu Budgie | 5        | 0.59%   |
| Elementary    | 5        | 0.59%   |
| Ubuntu Unity  | 3        | 0.35%   |
| Ubuntu MATE   | 3        | 0.35%   |
| MX            | 3        | 0.35%   |
| Kali          | 3        | 0.35%   |
| EndeavourOS   | 3        | 0.35%   |
| LFS           | 2        | 0.24%   |
| Feren OS      | 2        | 0.24%   |
| BlackPanther  | 2        | 0.24%   |
| Artix         | 2        | 0.24%   |
| Virtuozzo     | 1        | 0.12%   |
| Ubuntu Studio | 1        | 0.12%   |
| TUXEDO OS     | 1        | 0.12%   |
| Sparky        | 1        | 0.12%   |
| RHEL          | 1        | 0.12%   |
| PCS           | 1        | 0.12%   |
| Nobara        | 1        | 0.12%   |
| NixOS         | 1        | 0.12%   |
| Makulu        | 1        | 0.12%   |
| Garuda Linux  | 1        | 0.12%   |
| Endless       | 1        | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 4.15.0-88-generic        | 41       | 3.84%   |
| 5.15.0-67-generic        | 30       | 2.81%   |
| 5.15.0-69-generic        | 24       | 2.25%   |
| 5.15.0-58-generic        | 21       | 1.97%   |
| 4.15.0-91-generic        | 18       | 1.69%   |
| 5.15.0-46-generic        | 17       | 1.59%   |
| 5.16.7-desktop-1omv4003  | 16       | 1.5%    |
| 5.4.0-42-generic         | 14       | 1.31%   |
| 5.10.14-desktop-1omv4002 | 14       | 1.31%   |
| 4.15.0-96-generic        | 14       | 1.31%   |
| 6.1.1-desktop-1omv2290   | 10       | 0.94%   |
| 5.4.0-58-generic         | 10       | 0.94%   |
| 5.4.0-48-generic         | 9        | 0.84%   |
| 5.4.0-52-generic         | 8        | 0.75%   |
| 5.4.0-26-generic         | 8        | 0.75%   |
| 5.8.0-48-generic         | 7        | 0.66%   |
| 5.8.0-43-generic         | 7        | 0.66%   |
| 5.15.0-56-generic        | 7        | 0.66%   |
| 5.15.0-43-generic        | 7        | 0.66%   |
| 5.11.0-27-generic        | 7        | 0.66%   |
| 5.8.0-44-generic         | 6        | 0.56%   |
| 5.19.0-35-generic        | 6        | 0.56%   |
| 5.15.0-47-generic        | 6        | 0.56%   |
| 5.11.0-43-generic        | 6        | 0.56%   |
| 5.11.0-31-generic        | 6        | 0.56%   |
| 4.15.0-55-generic        | 6        | 0.56%   |
| 6.2.6-desktop-1omv2390   | 5        | 0.47%   |
| 5.8.0-53-generic         | 5        | 0.47%   |
| 5.4.0-91-generic         | 5        | 0.47%   |
| 5.4.0-81-generic         | 5        | 0.47%   |
| 5.4.0-70-generic         | 5        | 0.47%   |
| 5.4.0-66-generic         | 5        | 0.47%   |
| 5.4.0-54-generic         | 5        | 0.47%   |
| 5.4.0-40-generic         | 5        | 0.47%   |
| 5.4.0-122-generic        | 5        | 0.47%   |
| 5.3.0-42-generic         | 5        | 0.47%   |
| 5.15.0-71-generic        | 5        | 0.47%   |
| 5.13.0-39-generic        | 5        | 0.47%   |
| 5.13.0-35-generic        | 5        | 0.47%   |
| 4.15.0-76-generic        | 5        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 157      | 15.84%  |
| 5.4.0   | 141      | 14.23%  |
| 4.15.0  | 119      | 12.01%  |
| 5.8.0   | 50       | 5.05%   |
| 5.11.0  | 44       | 4.44%   |
| 5.13.0  | 41       | 4.14%   |
| 5.19.0  | 23       | 2.32%   |
| 5.10.0  | 22       | 2.22%   |
| 5.0.0   | 20       | 2.02%   |
| 5.3.0   | 18       | 1.82%   |
| 5.16.7  | 17       | 1.72%   |
| 4.18.0  | 17       | 1.72%   |
| 5.10.14 | 14       | 1.41%   |
| 6.1.1   | 10       | 1.01%   |
| 6.2.6   | 8        | 0.81%   |
| 6.2.0   | 8        | 0.81%   |
| 4.19.0  | 7        | 0.71%   |
| 5.17.5  | 6        | 0.61%   |
| 6.1.0   | 5        | 0.5%    |
| 5.6.15  | 4        | 0.4%    |
| 5.6.0   | 4        | 0.4%    |
| 5.16.13 | 4        | 0.4%    |
| 5.10.7  | 4        | 0.4%    |
| 4.9.20  | 4        | 0.4%    |
| 6.2.10  | 3        | 0.3%    |
| 6.1.4   | 3        | 0.3%    |
| 5.8.5   | 3        | 0.3%    |
| 5.8.4   | 3        | 0.3%    |
| 5.8.16  | 3        | 0.3%    |
| 5.7.1   | 3        | 0.3%    |
| 5.17.1  | 3        | 0.3%    |
| 5.15.15 | 3        | 0.3%    |
| 5.14.21 | 3        | 0.3%    |
| 5.14.0  | 3        | 0.3%    |
| 5.11.16 | 3        | 0.3%    |
| 5.10.9  | 3        | 0.3%    |
| 5.10.16 | 3        | 0.3%    |
| 4.9.60  | 3        | 0.3%    |
| 4.13.0  | 3        | 0.3%    |
| 3.10.0  | 3        | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 171      | 17.67%  |
| 5.4     | 147      | 15.19%  |
| 4.15    | 120      | 12.4%   |
| 5.8     | 70       | 7.23%   |
| 5.11    | 56       | 5.79%   |
| 5.10    | 55       | 5.68%   |
| 5.13    | 45       | 4.65%   |
| 5.16    | 31       | 3.2%    |
| 5.19    | 28       | 2.89%   |
| 6.2     | 26       | 2.69%   |
| 6.1     | 26       | 2.69%   |
| 5.3     | 21       | 2.17%   |
| 5.0     | 21       | 2.17%   |
| 4.18    | 19       | 1.96%   |
| 5.14    | 15       | 1.55%   |
| 5.6     | 12       | 1.24%   |
| 5.17    | 11       | 1.14%   |
| 6.0     | 10       | 1.03%   |
| 5.7     | 10       | 1.03%   |
| 5.12    | 9        | 0.93%   |
| 4.19    | 9        | 0.93%   |
| 5.18    | 8        | 0.83%   |
| 4.9     | 8        | 0.83%   |
| 5.9     | 7        | 0.72%   |
| 6.3     | 6        | 0.62%   |
| 6.4     | 3        | 0.31%   |
| 5.5     | 3        | 0.31%   |
| 4.13    | 3        | 0.31%   |
| 3.10    | 3        | 0.31%   |
| 4.4     | 2        | 0.21%   |
| 4.20    | 2        | 0.21%   |
| 3.16    | 2        | 0.21%   |
| 5.1     | 1        | 0.1%    |
| 5       | 1        | 0.1%    |
| 4.2     | 1        | 0.1%    |
| 4.16    | 1        | 0.1%    |
| 4.14    | 1        | 0.1%    |
| 4.12    | 1        | 0.1%    |
| 4.10    | 1        | 0.1%    |
| 4.1     | 1        | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 813      | 99.15%  |
| i686   | 7        | 0.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 304      | 35.68%  |
| KDE5            | 127      | 14.91%  |
| GNUstep         | 122      | 14.32%  |
| Unknown         | 120      | 14.08%  |
| X-Cinnamon      | 49       | 5.75%   |
| XFCE            | 33       | 3.87%   |
| MATE            | 19       | 2.23%   |
| KDE             | 16       | 1.88%   |
| Cinnamon        | 15       | 1.76%   |
| LXQt            | 10       | 1.17%   |
| Pantheon        | 6        | 0.7%    |
| KDE4            | 6        | 0.7%    |
| Budgie          | 6        | 0.7%    |
| Unity           | 3        | 0.35%   |
| GNOME Flashback | 3        | 0.35%   |
| qtile           | 2        | 0.23%   |
| i3              | 2        | 0.23%   |
| DWM             | 2        | 0.23%   |
| xmonad          | 1        | 0.12%   |
| sway            | 1        | 0.12%   |
| none+awesome    | 1        | 0.12%   |
| ICEWM           | 1        | 0.12%   |
| GNOME Classic   | 1        | 0.12%   |
| fluxbox         | 1        | 0.12%   |
| bspwm           | 1        | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 623      | 70.08%  |
| Wayland | 110      | 12.37%  |
| Tty     | 92       | 10.35%  |
| Unknown | 61       | 6.86%   |
| Web     | 3        | 0.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 336      | 38.93%  |
| LightDM | 196      | 22.71%  |
| SDDM    | 120      | 13.9%   |
| GDM3    | 96       | 11.12%  |
| GDM     | 78       | 9.04%   |
| TDM     | 28       | 3.24%   |
| KDM     | 6        | 0.7%    |
| SLiM    | 2        | 0.23%   |
| XDM     | 1        | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 297      | 33.71%  |
| de_CH      | 178      | 20.2%   |
| Unknown    | 175      | 19.86%  |
| fr_CH      | 61       | 6.92%   |
| de_DE      | 57       | 6.47%   |
| en_GB      | 30       | 3.41%   |
| fr_FR      | 19       | 2.16%   |
| C          | 18       | 2.04%   |
| it_CH      | 8        | 0.91%   |
| it_IT      | 7        | 0.79%   |
| pt_PT      | 6        | 0.68%   |
| ru_RU      | 5        | 0.57%   |
| es_ES      | 4        | 0.45%   |
| en_AU      | 2        | 0.23%   |
| sk_SK      | 1        | 0.11%   |
| pt_BR      | 1        | 0.11%   |
| POSIX      | 1        | 0.11%   |
| pl_PL      | 1        | 0.11%   |
| hu_HU      | 1        | 0.11%   |
| gsw_CH     | 1        | 0.11%   |
| fi_FI      | 1        | 0.11%   |
| en_IE      | 1        | 0.11%   |
| en_CH      | 1        | 0.11%   |
| en_AG      | 1        | 0.11%   |
| de_IT      | 1        | 0.11%   |
| de_CH.UTF8 | 1        | 0.11%   |
| cs_CZ      | 1        | 0.11%   |
| C.UTF8     | 1        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 449      | 53.39%  |
| EFI  | 392      | 46.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 664      | 78.77%  |
| Btrfs   | 64       | 7.59%   |
| Overlay | 53       | 6.29%   |
| Xfs     | 20       | 2.37%   |
| Unknown | 20       | 2.37%   |
| Tmpfs   | 10       | 1.19%   |
| Zfs     | 3        | 0.36%   |
| F2fs    | 3        | 0.36%   |
| Ext2    | 2        | 0.24%   |
| Jfs     | 1        | 0.12%   |
| ExX4    | 1        | 0.12%   |
| Ext3    | 1        | 0.12%   |
| Aufs    | 1        | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 402      | 47.97%  |
| Unknown | 342      | 40.81%  |
| MBR     | 94       | 11.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 662      | 77.88%  |
| Yes       | 188      | 22.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 603      | 71.7%   |
| Yes       | 238      | 28.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUSTek Computer     | 307      | 37.44%  |
| Gigabyte Technology  | 84       | 10.24%  |
| Hewlett-Packard      | 78       | 9.51%   |
| ASRock               | 64       | 7.8%    |
| MSI                  | 61       | 7.44%   |
| Dell                 | 46       | 5.61%   |
| Fujitsu              | 32       | 3.9%    |
| Intel                | 30       | 3.66%   |
| Lenovo               | 20       | 2.44%   |
| Acer                 | 18       | 2.2%    |
| Medion               | 15       | 1.83%   |
| Shuttle              | 8        | 0.98%   |
| Pegatron             | 7        | 0.85%   |
| PC Engines           | 7        | 0.85%   |
| DALCO AG Switzerland | 6        | 0.73%   |
| Apple                | 6        | 0.73%   |
| Unknown              | 6        | 0.73%   |
| Supermicro           | 4        | 0.49%   |
| Biostar              | 3        | 0.37%   |
| Packard Bell         | 2        | 0.24%   |
| ZOTAC                | 1        | 0.12%   |
| Philco               | 1        | 0.12%   |
| NF541                | 1        | 0.12%   |
| Minix                | 1        | 0.12%   |
| MACHINIST            | 1        | 0.12%   |
| LattePanda           | 1        | 0.12%   |
| Inventec             | 1        | 0.12%   |
| ICP / iEi            | 1        | 0.12%   |
| Fujitsu Siemens      | 1        | 0.12%   |
| eMachines            | 1        | 0.12%   |
| ELSKY                | 1        | 0.12%   |
| Chuwi                | 1        | 0.12%   |
| BESSTAR Tech         | 1        | 0.12%   |
| AZW                  | 1        | 0.12%   |
| Alienware            | 1        | 0.12%   |
| AAEON                | 1        | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Desktops | Percent |
|---------------------------------------|----------|---------|
| ASUS All Series                       | 34       | 4.15%   |
| ASUS PRIME Z590-P                     | 17       | 2.07%   |
| Fujitsu CELSIUS_W550                  | 12       | 1.46%   |
| ASUS PRIME X570-PRO                   | 12       | 1.46%   |
| ASUS ROG STRIX X570-E GAMING          | 11       | 1.34%   |
| ASUS PRIME B550M-A                    | 10       | 1.22%   |
| ASUS STRIX Z270F GAMING               | 8        | 0.98%   |
| ASUS P9X79 WS                         | 7        | 0.85%   |
| ASUS P8Z77-V LX                       | 7        | 0.85%   |
| Unknown                               | 7        | 0.85%   |
| MSI MS-7C02                           | 6        | 0.73%   |
| DALCO AG Switzerland +41 44 908 38 38 | 6        | 0.73%   |
| PC Engines APU2                       | 5        | 0.61%   |
| Intel DP67BA AAG10219-303             | 5        | 0.61%   |
| HP EliteDesk 800 G1 SFF               | 5        | 0.61%   |
| Fujitsu CELSIUS W570                  | 5        | 0.61%   |
| Dell OptiPlex 9020                    | 5        | 0.61%   |
| Dell OptiPlex 7010                    | 5        | 0.61%   |
| ASUS ROG STRIX Z370-F GAMING          | 5        | 0.61%   |
| Intel DP55WB AAE64798-207             | 4        | 0.49%   |
| HP Z400 Workstation                   | 4        | 0.49%   |
| Gigabyte X570 AORUS ELITE             | 4        | 0.49%   |
| Gigabyte H97-HD3                      | 4        | 0.49%   |
| Dell OptiPlex 790                     | 4        | 0.49%   |
| ASUS PRIME Z370-A II                  | 4        | 0.49%   |
| ASUS PRIME X370-PRO                   | 4        | 0.49%   |
| Apple MacPro5,1                       | 4        | 0.49%   |
| MSI MS-7D25                           | 3        | 0.37%   |
| MSI MS-7C56                           | 3        | 0.37%   |
| MSI MS-7971                           | 3        | 0.37%   |
| HP ProDesk 600 G1 TWR                 | 3        | 0.37%   |
| HP OMEN 30L Desktop GT13-0xxx         | 3        | 0.37%   |
| HP EliteDesk 800 G1 USDT              | 3        | 0.37%   |
| Gigabyte X570 AORUS PRO               | 3        | 0.37%   |
| Gigabyte X399 AORUS XTREME            | 3        | 0.37%   |
| Dell Precision Tower 5810             | 3        | 0.37%   |
| Dell OptiPlex 7040                    | 3        | 0.37%   |
| ASUS TUF Gaming X570-PLUS             | 3        | 0.37%   |
| ASUS ROG STRIX B450-F GAMING          | 3        | 0.37%   |
| ASUS ROG CROSSHAIR VIII HERO          | 3        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME               | 76       | 9.27%   |
| ASUS ROG                 | 61       | 7.44%   |
| ASUS All                 | 34       | 4.15%   |
| Dell OptiPlex            | 31       | 3.78%   |
| Fujitsu CELSIUS          | 27       | 3.29%   |
| HP EliteDesk             | 20       | 2.44%   |
| HP Compaq                | 16       | 1.95%   |
| ASUS TUF                 | 16       | 1.95%   |
| Gigabyte X570            | 9        | 1.1%    |
| ASUS STRIX               | 9        | 1.1%    |
| Acer Aspire              | 9        | 1.1%    |
| ASUS P9X79               | 8        | 0.98%   |
| ASUS P8Z77-V             | 8        | 0.98%   |
| HP ProDesk               | 7        | 0.85%   |
| Dell Precision           | 7        | 0.85%   |
| Unknown                  | 7        | 0.85%   |
| MSI MS-7C02              | 6        | 0.73%   |
| Intel DP55WB             | 6        | 0.73%   |
| DALCO AG Switzerland +41 | 6        | 0.73%   |
| ASUS SABERTOOTH          | 6        | 0.73%   |
| ASRock X570              | 6        | 0.73%   |
| PC Engines APU2          | 5        | 0.61%   |
| Lenovo ThinkCentre       | 5        | 0.61%   |
| Lenovo Legion            | 5        | 0.61%   |
| Lenovo IdeaCentre        | 5        | 0.61%   |
| Intel DP67BA             | 5        | 0.61%   |
| HP Z400                  | 4        | 0.49%   |
| HP Pavilion              | 4        | 0.49%   |
| HP OMEN                  | 4        | 0.49%   |
| Gigabyte H97-HD3         | 4        | 0.49%   |
| Fujitsu ESPRIMO          | 4        | 0.49%   |
| ASUS P8P67               | 4        | 0.49%   |
| ASUS P8H77-M             | 4        | 0.49%   |
| ASUS P7H55-M             | 4        | 0.49%   |
| ASUS P6T                 | 4        | 0.49%   |
| ASUS M5A78L-M            | 4        | 0.49%   |
| ASRock B450              | 4        | 0.49%   |
| Apple MacPro5            | 4        | 0.49%   |
| Acer Predator            | 4        | 0.49%   |
| MSI MS-7D25              | 3        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 83       | 10.12%  |
| 2018    | 75       | 9.15%   |
| 2012    | 68       | 8.29%   |
| 2020    | 64       | 7.8%    |
| 2017    | 61       | 7.44%   |
| 2021    | 60       | 7.32%   |
| 2014    | 58       | 7.07%   |
| 2013    | 58       | 7.07%   |
| 2011    | 58       | 7.07%   |
| 2015    | 55       | 6.71%   |
| 2010    | 41       | 5%      |
| 2016    | 38       | 4.63%   |
| 2009    | 30       | 3.66%   |
| 2008    | 26       | 3.17%   |
| 2022    | 15       | 1.83%   |
| 2007    | 11       | 1.34%   |
| 2006    | 11       | 1.34%   |
| 2023    | 3        | 0.37%   |
| 2004    | 2        | 0.24%   |
| 2005    | 1        | 0.12%   |
| 2003    | 1        | 0.12%   |
| Unknown | 1        | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 820      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 801      | 96.86%  |
| Enabled  | 26       | 3.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 813      | 99.15%  |
| Yes  | 7        | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 221      | 26.34%  |
| 32.01-64.0      | 215      | 25.63%  |
| 8.01-16.0       | 110      | 13.11%  |
| 64.01-256.0     | 109      | 12.99%  |
| 4.01-8.0        | 79       | 9.42%   |
| 3.01-4.0        | 63       | 7.51%   |
| 24.01-32.0      | 20       | 2.38%   |
| 1.01-2.0        | 13       | 1.55%   |
| More than 256.0 | 4        | 0.48%   |
| 2.01-3.0        | 4        | 0.48%   |
| 0.01-0.5        | 1        | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 302      | 31.36%  |
| 2.01-3.0    | 199      | 20.66%  |
| 4.01-8.0    | 149      | 15.47%  |
| 3.01-4.0    | 109      | 11.32%  |
| 0.51-1.0    | 87       | 9.03%   |
| 8.01-16.0   | 77       | 8%      |
| 16.01-24.0  | 15       | 1.56%   |
| 0.01-0.5    | 11       | 1.14%   |
| 24.01-32.0  | 7        | 0.73%   |
| 32.01-64.0  | 4        | 0.42%   |
| 64.01-256.0 | 2        | 0.21%   |
| Unknown     | 1        | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 321      | 36.9%   |
| 2      | 261      | 30%     |
| 3      | 137      | 15.75%  |
| 4      | 62       | 7.13%   |
| 5      | 41       | 4.71%   |
| 6      | 21       | 2.41%   |
| 7      | 16       | 1.84%   |
| 0      | 8        | 0.92%   |
| 14     | 1        | 0.11%   |
| 11     | 1        | 0.11%   |
| 8      | 1        | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 446      | 53.22%  |
| Yes       | 392      | 46.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 816      | 99.51%  |
| No        | 4        | 0.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 505      | 60.77%  |
| Yes       | 326      | 39.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 566      | 68.03%  |
| Yes       | 266      | 31.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Switzerland | 820      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Zurich                             | 282      | 31.69%  |
| Bern                               | 35       | 3.93%   |
| Lucerne                            | 27       | 3.03%   |
| Geneva                             | 25       | 2.81%   |
| Wiesendangen / Wiesendangen (Dorf) | 12       | 1.35%   |
| Lausanne                           | 12       | 1.35%   |
| Basel                              | 12       | 1.35%   |
| Neuchatel                          | 11       | 1.24%   |
| Lyss                               | 9        | 1.01%   |
| Winterthur                         | 8        | 0.9%    |
| Dietikon                           | 8        | 0.9%    |
| Wil                                | 7        | 0.79%   |
| Wetzikon                           | 6        | 0.67%   |
| Thun                               | 6        | 0.67%   |
| St. Gallen                         | 6        | 0.67%   |
| Lugano                             | 6        | 0.67%   |
| Aarau                              | 6        | 0.67%   |
| Wettingen                          | 5        | 0.56%   |
| Uster                              | 5        | 0.56%   |
| Schaffhausen                       | 5        | 0.56%   |
| Glattbrugg                         | 5        | 0.56%   |
| Caslano                            | 5        | 0.56%   |
| Willisau                           | 4        | 0.45%   |
| Sion                               | 4        | 0.45%   |
| Morges                             | 4        | 0.45%   |
| Kloten                             | 4        | 0.45%   |
| Heerbrugg                          | 4        | 0.45%   |
| Burgdorf                           | 4        | 0.45%   |
| Bulle                              | 4        | 0.45%   |
| Bulach                             | 4        | 0.45%   |
| Biel/Bienne                        | 4        | 0.45%   |
| Baden                              | 4        | 0.45%   |
| Zug                                | 3        | 0.34%   |
| Wallisellen                        | 3        | 0.34%   |
| Vevey                              | 3        | 0.34%   |
| Schwarzenbach                      | 3        | 0.34%   |
| Schafisheim                        | 3        | 0.34%   |
| Regensdorf                         | 3        | 0.34%   |
| Prilly                             | 3        | 0.34%   |
| Opfikon                            | 3        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 396      | 845    | 27.29%  |
| WDC                       | 278      | 491    | 19.16%  |
| Seagate                   | 240      | 367    | 16.54%  |
| Sandisk                   | 59       | 78     | 4.07%   |
| Hitachi                   | 55       | 78     | 3.79%   |
| Toshiba                   | 48       | 68     | 3.31%   |
| Kingston                  | 48       | 76     | 3.31%   |
| Crucial                   | 45       | 61     | 3.1%    |
| Intel                     | 41       | 65     | 2.83%   |
| Corsair                   | 22       | 26     | 1.52%   |
| OCZ                       | 16       | 21     | 1.1%    |
| A-DATA Technology         | 15       | 22     | 1.03%   |
| Phison                    | 14       | 23     | 0.96%   |
| HGST                      | 13       | 17     | 0.9%    |
| Unknown                   | 12       | 19     | 0.83%   |
| Micron Technology         | 12       | 17     | 0.83%   |
| SK hynix                  | 10       | 13     | 0.69%   |
| China                     | 10       | 11     | 0.69%   |
| Intenso                   | 8        | 8      | 0.55%   |
| Hewlett-Packard           | 6        | 9      | 0.41%   |
| Apple                     | 6        | 6      | 0.41%   |
| SPCC                      | 5        | 6      | 0.34%   |
| Plextor                   | 5        | 6      | 0.34%   |
| Patriot                   | 5        | 6      | 0.34%   |
| KingSpec                  | 5        | 10     | 0.34%   |
| Phison Electronics        | 4        | 5      | 0.28%   |
| Micron/Crucial Technology | 4        | 7      | 0.28%   |
| Maxtor                    | 4        | 6      | 0.28%   |
| XPG                       | 3        | 3      | 0.21%   |
| Transcend                 | 3        | 9      | 0.21%   |
| Silicon Motion            | 3        | 3      | 0.21%   |
| PNY                       | 3        | 8      | 0.21%   |
| LITEONIT                  | 3        | 4      | 0.21%   |
| LITEON                    | 3        | 4      | 0.21%   |
| KIOXIA-EXCERIA            | 3        | 3      | 0.21%   |
| HPE                       | 3        | 9      | 0.21%   |
| ASMT                      | 3        | 5      | 0.21%   |
| LaCie                     | 2        | 2      | 0.14%   |
| KIOXIA                    | 2        | 3      | 0.14%   |
| KingFast                  | 2        | 7      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB                           | 30       | 1.73%   |
| Samsung NVMe SSD Drive 1TB                          | 26       | 1.5%    |
| Samsung SSD 860 EVO 1TB                             | 25       | 1.45%   |
| Seagate ST2000DM008-2FR102 2TB                      | 23       | 1.33%   |
| Samsung SSD 980 PRO 1TB                             | 23       | 1.33%   |
| Samsung SSD 850 EVO 250GB                           | 23       | 1.33%   |
| Seagate ST2000DM006-2DM164 2TB                      | 19       | 1.1%    |
| Samsung SSD 860 EVO 500GB                           | 18       | 1.04%   |
| Samsung SSD 970 EVO Plus 1TB                        | 16       | 0.92%   |
| Samsung SSD 860 EVO 250GB                           | 16       | 0.92%   |
| Samsung SSD 840 EVO 250GB                           | 16       | 0.92%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13       | 0.75%   |
| Seagate ST4000DM004-2CV104 4TB                      | 12       | 0.69%   |
| Samsung SSD 850 EVO 1TB                             | 12       | 0.69%   |
| Toshiba DT01ACA100 1TB                              | 11       | 0.64%   |
| Samsung SSD 860 QVO 1TB                             | 11       | 0.64%   |
| Samsung SSD 850 PRO 256GB                           | 11       | 0.64%   |
| Samsung NVMe SSD Drive 500GB                        | 11       | 0.64%   |
| Samsung HD103SJ 1TB                                 | 11       | 0.64%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 9        | 0.52%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 9        | 0.52%   |
| Toshiba DT01ACA200 2TB                              | 9        | 0.52%   |
| Seagate Expansion 1TB                               | 9        | 0.52%   |
| SanDisk NVMe SSD Drive 1TB                          | 9        | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 9        | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 9        | 0.52%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 8        | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB                      | 8        | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB                      | 8        | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                      | 8        | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB                      | 8        | 0.46%   |
| Samsung SSD 970 EVO Plus 500GB                      | 8        | 0.46%   |
| Samsung SSD 860 QVO 2TB                             | 8        | 0.46%   |
| Samsung SSD 850 PRO 512GB                           | 8        | 0.46%   |
| Hitachi HUA722020ALA330 2TB                         | 8        | 0.46%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 7        | 0.4%    |
| Samsung SSD 970 EVO 500GB                           | 7        | 0.4%    |
| Samsung SSD 870 QVO 1TB                             | 7        | 0.4%    |
| Samsung SSD 870 EVO 500GB                           | 7        | 0.4%    |
| Samsung SSD 870 EVO 1TB                             | 7        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 246      | 424    | 38.2%   |
| Seagate             | 232      | 348    | 36.02%  |
| Hitachi             | 55       | 78     | 8.54%   |
| Samsung Electronics | 37       | 56     | 5.75%   |
| Toshiba             | 33       | 48     | 5.12%   |
| HGST                | 13       | 17     | 2.02%   |
| Unknown             | 5        | 6      | 0.78%   |
| Maxtor              | 4        | 6      | 0.62%   |
| Intenso             | 3        | 3      | 0.47%   |
| JMicron Technology  | 2        | 2      | 0.31%   |
| Hewlett-Packard     | 2        | 4      | 0.31%   |
| ASMT                | 2        | 3      | 0.31%   |
| Apple               | 2        | 2      | 0.31%   |
| Initio              | 1        | 1      | 0.16%   |
| IET                 | 1        | 1      | 0.16%   |
| ICY BOX             | 1        | 1      | 0.16%   |
| HPE                 | 1        | 6      | 0.16%   |
| Fujitsu             | 1        | 1      | 0.16%   |
| ExcelStor           | 1        | 2      | 0.16%   |
| ASMT109x            | 1        | 1      | 0.16%   |
| ASMedia             | 1        | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 258      | 522    | 45.83%  |
| Crucial             | 43       | 59     | 7.64%   |
| SanDisk             | 42       | 55     | 7.46%   |
| Kingston            | 36       | 57     | 6.39%   |
| WDC                 | 33       | 45     | 5.86%   |
| Intel               | 25       | 36     | 4.44%   |
| OCZ                 | 16       | 21     | 2.84%   |
| Micron Technology   | 10       | 14     | 1.78%   |
| China               | 10       | 11     | 1.78%   |
| Corsair             | 9        | 9      | 1.6%    |
| A-DATA Technology   | 9        | 15     | 1.6%    |
| Toshiba             | 8        | 11     | 1.42%   |
| SPCC                | 5        | 6      | 0.89%   |
| Plextor             | 5        | 6      | 0.89%   |
| Patriot             | 5        | 6      | 0.89%   |
| KingSpec            | 5        | 10     | 0.89%   |
| Intenso             | 4        | 4      | 0.71%   |
| Transcend           | 3        | 9      | 0.53%   |
| SK hynix            | 3        | 4      | 0.53%   |
| LITEONIT            | 3        | 4      | 0.53%   |
| LITEON              | 3        | 4      | 0.53%   |
| KIOXIA-EXCERIA      | 3        | 3      | 0.53%   |
| Hewlett-Packard     | 3        | 4      | 0.53%   |
| Seagate             | 2        | 2      | 0.36%   |
| Apple               | 2        | 2      | 0.36%   |
| XSTAR               | 1        | 1      | 0.18%   |
| VERICO              | 1        | 1      | 0.18%   |
| Unknown             | 1        | 1      | 0.18%   |
| TO Exter            | 1        | 1      | 0.18%   |
| PNY                 | 1        | 2      | 0.18%   |
| Palit               | 1        | 1      | 0.18%   |
| NVME                | 1        | 2      | 0.18%   |
| Netac               | 1        | 1      | 0.18%   |
| Mushkin             | 1        | 1      | 0.18%   |
| Leven               | 1        | 1      | 0.18%   |
| HPE                 | 1        | 1      | 0.18%   |
| FORESEE             | 1        | 1      | 0.18%   |
| ASMT                | 1        | 2      | 0.18%   |
| Argon               | 1        | 1      | 0.18%   |
| Apacer              | 1        | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 510      | 1011   | 40.22%  |
| SSD     | 467      | 941    | 36.83%  |
| NVMe    | 269      | 474    | 21.21%  |
| Unknown | 19       | 33     | 1.5%    |
| MMC     | 3        | 3      | 0.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 717      | 1897   | 68.29%  |
| NVMe | 269      | 474    | 25.62%  |
| SAS  | 61       | 88     | 5.81%   |
| MMC  | 3        | 3      | 0.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 440      | 831    | 40%     |
| 0.51-1.0   | 293      | 545    | 26.64%  |
| 1.01-2.0   | 199      | 326    | 18.09%  |
| 3.01-4.0   | 69       | 108    | 6.27%   |
| 2.01-3.0   | 46       | 67     | 4.18%   |
| 4.01-10.0  | 38       | 52     | 3.45%   |
| 10.01-20.0 | 15       | 23     | 1.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 170      | 18.72%  |
| 1001-2000      | 141      | 15.53%  |
| 501-1000       | 128      | 14.1%   |
| More than 3000 | 124      | 13.66%  |
| 251-500        | 117      | 12.89%  |
| 2001-3000      | 85       | 9.36%   |
| Unknown        | 54       | 5.95%   |
| 1-20           | 50       | 5.51%   |
| 51-100         | 26       | 2.86%   |
| 21-50          | 13       | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 231      | 24.71%  |
| 51-100         | 110      | 11.76%  |
| 501-1000       | 105      | 11.23%  |
| 101-250        | 103      | 11.02%  |
| 251-500        | 100      | 10.7%   |
| 21-50          | 83       | 8.88%   |
| 1001-2000      | 72       | 7.7%    |
| More than 3000 | 58       | 6.2%    |
| Unknown        | 54       | 5.78%   |
| 2001-3000      | 19       | 2.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD3000HLHX-01JJPV0 304GB          | 2        | 2      | 2.38%   |
| WDC WD20EARS-00J99B0 2TB              | 2        | 2      | 2.38%   |
| WDC WD10EARS-00Y5B1 1TB               | 2        | 2      | 2.38%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 2.38%   |
| Seagate ST31500341AS 1TB              | 2        | 5      | 2.38%   |
| Samsung Electronics SSD 850 EVO 1TB   | 2        | 2      | 2.38%   |
| Hitachi HUA722020ALA330 2TB           | 2        | 2      | 2.38%   |
| XSTAR SSD 128GB                       | 1        | 1      | 1.19%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1      | 1.19%   |
| WDC WD5000AAKS-65A7B0 500GB           | 1        | 1      | 1.19%   |
| WDC WD5000AAKS-00TMA0 500GB           | 1        | 1      | 1.19%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1        | 1      | 1.19%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1        | 1      | 1.19%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 1        | 2      | 1.19%   |
| WDC WD3200AAKS-00B3A0 320GB           | 1        | 1      | 1.19%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1        | 1      | 1.19%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 1.19%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 2      | 1.19%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 1      | 1.19%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1        | 1      | 1.19%   |
| WDC WD10EADS-22M2B0 1TB               | 1        | 1      | 1.19%   |
| WDC WD10EADS-11M2B3 1TB               | 1        | 1      | 1.19%   |
| WDC WD10EADS-00L5B1 1TB               | 1        | 1      | 1.19%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 1      | 1.19%   |
| WDC WD1001FALS-403AA0 1TB             | 1        | 1      | 1.19%   |
| Toshiba MK7575GSX 752GB               | 1        | 3      | 1.19%   |
| Toshiba MG08ACA16TE 16TB              | 1        | 1      | 1.19%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 1.19%   |
| SK hynix HFS256G32MND-2200A 256GB SSD | 1        | 1      | 1.19%   |
| Seagate ST9500325ASG 500GB            | 1        | 1      | 1.19%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 1.19%   |
| Seagate ST5000NM0024-1HT170 5TB       | 1        | 4      | 1.19%   |
| Seagate ST3500630NS 500GB             | 1        | 2      | 1.19%   |
| Seagate ST3500413AS 500GB             | 1        | 2      | 1.19%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 1.19%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 1.19%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 1.19%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 2      | 1.19%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 1.19%   |
| SanDisk SSD PLUS 240GB                | 1        | 1      | 1.19%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 25     | 27.71%  |
| Seagate             | 13       | 23     | 15.66%  |
| Samsung Electronics | 12       | 13     | 14.46%  |
| Hitachi             | 7        | 8      | 8.43%   |
| Kingston            | 4        | 5      | 4.82%   |
| Toshiba             | 3        | 5      | 3.61%   |
| OCZ                 | 3        | 4      | 3.61%   |
| A-DATA Technology   | 3        | 5      | 3.61%   |
| SanDisk             | 2        | 2      | 2.41%   |
| Intel               | 2        | 2      | 2.41%   |
| HGST                | 2        | 2      | 2.41%   |
| XSTAR               | 1        | 1      | 1.2%    |
| SK hynix            | 1        | 1      | 1.2%    |
| Patriot             | 1        | 2      | 1.2%    |
| Micron Technology   | 1        | 2      | 1.2%    |
| Initio              | 1        | 1      | 1.2%    |
| Fujitsu             | 1        | 1      | 1.2%    |
| Crucial             | 1        | 1      | 1.2%    |
| China               | 1        | 1      | 1.2%    |
| ASMedia             | 1        | 1      | 1.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 24     | 40.74%  |
| Seagate             | 13       | 23     | 24.07%  |
| Hitachi             | 7        | 8      | 12.96%  |
| Samsung Electronics | 4        | 5      | 7.41%   |
| Toshiba             | 3        | 5      | 5.56%   |
| HGST                | 2        | 2      | 3.7%    |
| Initio              | 1        | 1      | 1.85%   |
| Fujitsu             | 1        | 1      | 1.85%   |
| ASMedia             | 1        | 1      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 47       | 70     | 61.84%  |
| SSD  | 25       | 30     | 32.89%  |
| NVMe | 4        | 5      | 5.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3750528AS 752GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 448      | 1240   | 47.71%  |
| Works    | 421      | 1116   | 44.83%  |
| Malfunc  | 69       | 105    | 7.35%   |
| Failed   | 1        | 1      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 558      | 44.08%  |
| AMD                          | 239      | 18.88%  |
| Samsung Electronics          | 171      | 13.51%  |
| ASMedia Technology           | 62       | 4.9%    |
| Marvell Technology Group     | 49       | 3.87%   |
| JMicron Technology           | 32       | 2.53%   |
| Phison Electronics           | 29       | 2.29%   |
| Sandisk                      | 25       | 1.97%   |
| Nvidia                       | 16       | 1.26%   |
| Kingston Technology Company  | 15       | 1.18%   |
| Seagate Technology           | 11       | 0.87%   |
| SK hynix                     | 7        | 0.55%   |
| ADATA Technology             | 7        | 0.55%   |
| Toshiba America Info Systems | 6        | 0.47%   |
| Silicon Motion               | 6        | 0.47%   |
| Micron/Crucial Technology    | 6        | 0.47%   |
| LSI Logic / Symbios Logic    | 6        | 0.47%   |
| KIOXIA                       | 3        | 0.24%   |
| Silicon Image                | 2        | 0.16%   |
| Micron Technology            | 2        | 0.16%   |
| Hewlett-Packard              | 2        | 0.16%   |
| Areca Technology             | 2        | 0.16%   |
| Apple                        | 2        | 0.16%   |
| Adaptec                      | 2        | 0.16%   |
| VIA Technologies             | 1        | 0.08%   |
| Union Memory (Shenzhen)      | 1        | 0.08%   |
| Tekram Technology            | 1        | 0.08%   |
| Realtek Semiconductor        | 1        | 0.08%   |
| Lenovo                       | 1        | 0.08%   |
| Broadcom / LSI               | 1        | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 155      | 10.18%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 87       | 5.71%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 58       | 3.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 56       | 3.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 55       | 3.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 53       | 3.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 48       | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 41       | 2.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 41       | 2.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 40       | 2.63%   |
| Intel SATA Controller [RAID mode]                                              | 36       | 2.36%   |
| AMD 500 Series Chipset SATA Controller                                         | 35       | 2.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 28       | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 28       | 1.84%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 28       | 1.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 25       | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25       | 1.64%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 19       | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 19       | 1.25%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 17       | 1.12%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 16       | 1.05%   |
| AMD 300 Series Chipset SATA Controller                                         | 15       | 0.98%   |
| Phison E12 NVMe Controller                                                     | 13       | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                             | 13       | 0.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 12       | 0.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 12       | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12       | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                               | 11       | 0.72%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo          | 11       | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                          | 11       | 0.72%   |
| AMD X370 Series Chipset SATA Controller                                        | 11       | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10       | 0.66%   |
| AMD X399 Series Chipset SATA Controller                                        | 10       | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 10       | 0.66%   |
| JMicron JMB362 SATA Controller                                                 | 9        | 0.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 9        | 0.59%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 9        | 0.59%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 9        | 0.59%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 9        | 0.59%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 8        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 694      | 58.76%  |
| NVMe | 272      | 23.03%  |
| IDE  | 138      | 11.69%  |
| RAID | 67       | 5.67%   |
| SAS  | 9        | 0.76%   |
| SCSI | 1        | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 563      | 68.66%  |
| AMD     | 256      | 31.22%  |
| Unknown | 1        | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i7-6700 CPU @ 3.40GHz        | 22       | 2.68%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 22       | 2.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 18       | 2.19%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 18       | 2.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 17       | 2.07%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 17       | 2.07%   |
| Intel 11th Gen Core i9-11900F @ 2.50GHz | 16       | 1.95%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 16       | 1.95%   |
| AMD Ryzen 5 3600 6-Core Processor       | 16       | 1.95%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 14       | 1.71%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 13       | 1.58%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 12       | 1.46%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 10       | 1.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 10       | 1.22%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 9        | 1.1%    |
| Intel Core i7-3770K CPU @ 3.50GHz       | 9        | 1.1%    |
| AMD Ryzen 9 5950X 16-Core Processor     | 9        | 1.1%    |
| Intel Core i5-6500 CPU @ 3.20GHz        | 8        | 0.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 8        | 0.97%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 8        | 0.97%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 7        | 0.85%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 7        | 0.85%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 7        | 0.85%   |
| AMD Quad-Core Opteron Processor 2354    | 7        | 0.85%   |
| AMD GX-412TC SOC                        | 7        | 0.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 6        | 0.73%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 6        | 0.73%   |
| Intel Core i7 CPU 920 @ 2.67GHz         | 6        | 0.73%   |
| Intel Core i5 CPU 760 @ 2.80GHz         | 6        | 0.73%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 6        | 0.73%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 6        | 0.73%   |
| AMD Ryzen 5 2600X Six-Core Processor    | 6        | 0.73%   |
| Intel Xeon CPU E3-1240 v6 @ 3.70GHz     | 5        | 0.61%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 5        | 0.61%   |
| Intel Core i7-3930K CPU @ 3.20GHz       | 5        | 0.61%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 5        | 0.61%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 5        | 0.61%   |
| Intel Core i5-3570K CPU @ 3.40GHz       | 5        | 0.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 5        | 0.61%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 5        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 228      | 27.77%  |
| Intel Core i5           | 120      | 14.62%  |
| AMD Ryzen 7             | 64       | 7.8%    |
| Intel Xeon              | 57       | 6.94%   |
| AMD Ryzen 5             | 56       | 6.82%   |
| Other                   | 47       | 5.72%   |
| AMD Ryzen 9             | 42       | 5.12%   |
| Intel Core i3           | 31       | 3.78%   |
| Intel Core 2 Duo        | 19       | 2.31%   |
| AMD FX                  | 19       | 2.31%   |
| AMD Ryzen Threadripper  | 14       | 1.71%   |
| Intel Core i9           | 13       | 1.58%   |
| Intel Core 2 Quad       | 13       | 1.58%   |
| Intel Celeron           | 10       | 1.22%   |
| Intel Pentium Dual-Core | 9        | 1.1%    |
| AMD GX                  | 8        | 0.97%   |
| AMD Ryzen 3             | 7        | 0.85%   |
| AMD Quad-Core Opteron   | 7        | 0.85%   |
| Intel Core 2            | 5        | 0.61%   |
| AMD Phenom II X4        | 5        | 0.61%   |
| AMD Athlon              | 5        | 0.61%   |
| AMD A8                  | 5        | 0.61%   |
| Intel Pentium 4         | 4        | 0.49%   |
| Intel Atom              | 4        | 0.49%   |
| AMD Phenom II X6        | 4        | 0.49%   |
| AMD A10                 | 4        | 0.49%   |
| Intel Pentium           | 3        | 0.37%   |
| AMD Phenom              | 3        | 0.37%   |
| AMD Athlon II X2        | 3        | 0.37%   |
| AMD Ryzen 5 PRO         | 2        | 0.24%   |
| AMD Phenom II X3        | 2        | 0.24%   |
| AMD Athlon II X4        | 2        | 0.24%   |
| Intel Core m3           | 1        | 0.12%   |
| Intel Celeron M         | 1        | 0.12%   |
| AMD G                   | 1        | 0.12%   |
| AMD Athlon Dual Core    | 1        | 0.12%   |
| AMD Athlon 64 X2        | 1        | 0.12%   |
| AMD Athlon 64           | 1        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 355      | 43.24%  |
| 6       | 136      | 16.57%  |
| 8       | 134      | 16.32%  |
| 2       | 95       | 11.57%  |
| 12      | 36       | 4.38%   |
| 16      | 29       | 3.53%   |
| 10      | 9        | 1.1%    |
| 3       | 7        | 0.85%   |
| 24      | 6        | 0.73%   |
| 1       | 6        | 0.73%   |
| 32      | 4        | 0.49%   |
| 18      | 2        | 0.24%   |
| 14      | 1        | 0.12%   |
| Unknown | 1        | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 805      | 98.17%  |
| 2      | 15       | 1.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 572      | 69.33%  |
| 1       | 252      | 30.55%  |
| Unknown | 1        | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 810      | 98.78%  |
| Unknown        | 6        | 0.73%   |
| 32-bit         | 4        | 0.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 169      | 19.74%  |
| 0x306c3    | 73       | 8.53%   |
| 0x506e3    | 50       | 5.84%   |
| 0x306a9    | 48       | 5.61%   |
| 0x206a7    | 43       | 5.02%   |
| 0x08701021 | 32       | 3.74%   |
| 0x906ea    | 29       | 3.39%   |
| 0x1067a    | 25       | 2.92%   |
| 0x906e9    | 22       | 2.57%   |
| 0xa0671    | 20       | 2.34%   |
| 0x0800820d | 19       | 2.22%   |
| 0xa0655    | 16       | 1.87%   |
| 0x306f2    | 14       | 1.64%   |
| 0x0a201016 | 14       | 1.64%   |
| 0x08701013 | 13       | 1.52%   |
| 0x106e5    | 11       | 1.29%   |
| 0x206d7    | 10       | 1.17%   |
| 0x106a5    | 10       | 1.17%   |
| 0x906ed    | 9        | 1.05%   |
| 0x50654    | 9        | 1.05%   |
| 0x08001138 | 9        | 1.05%   |
| 0x0a201009 | 8        | 0.93%   |
| 0x06000852 | 8        | 0.93%   |
| 0x01000083 | 8        | 0.93%   |
| 0x206c2    | 7        | 0.82%   |
| 0x07030105 | 7        | 0.82%   |
| 0x010000c8 | 6        | 0.7%    |
| 0xa0653    | 5        | 0.58%   |
| 0x90672    | 5        | 0.58%   |
| 0x406f1    | 5        | 0.58%   |
| 0x306e4    | 5        | 0.58%   |
| 0x20655    | 5        | 0.58%   |
| 0x0a20120a | 5        | 0.58%   |
| 0x0a201204 | 5        | 0.58%   |
| 0x08001137 | 5        | 0.58%   |
| 0xb0671    | 4        | 0.47%   |
| 0x906eb    | 4        | 0.47%   |
| 0x6fd      | 4        | 0.47%   |
| 0x0a50000c | 4        | 0.47%   |
| 0x0a201205 | 4        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 109      | 13.26%  |
| KabyLake         | 85       | 10.34%  |
| Skylake          | 67       | 8.15%   |
| Zen 2            | 64       | 7.79%   |
| SandyBridge      | 64       | 7.79%   |
| IvyBridge        | 58       | 7.06%   |
| Zen 3            | 57       | 6.93%   |
| Zen+             | 32       | 3.89%   |
| Penryn           | 32       | 3.89%   |
| Zen              | 29       | 3.53%   |
| Nehalem          | 28       | 3.41%   |
| K10              | 26       | 3.16%   |
| Unknown          | 23       | 2.8%    |
| CometLake        | 22       | 2.68%   |
| Piledriver       | 20       | 2.43%   |
| Icelake          | 19       | 2.31%   |
| Westmere         | 18       | 2.19%   |
| Core             | 15       | 1.82%   |
| Alderlake Hybrid | 9        | 1.09%   |
| Puma             | 8        | 0.97%   |
| Broadwell        | 5        | 0.61%   |
| Silvermont       | 4        | 0.49%   |
| NetBurst         | 4        | 0.49%   |
| K8 Hammer        | 4        | 0.49%   |
| Jaguar           | 4        | 0.49%   |
| Goldmont plus    | 4        | 0.49%   |
| Bulldozer        | 3        | 0.36%   |
| K10 Llano        | 2        | 0.24%   |
| Goldmont         | 2        | 0.24%   |
| Steamroller      | 1        | 0.12%   |
| P6               | 1        | 0.12%   |
| Excavator        | 1        | 0.12%   |
| Bonnell          | 1        | 0.12%   |
| Bobcat           | 1        | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 437      | 50.29%  |
| AMD                                          | 210      | 24.17%  |
| Intel                                        | 206      | 23.71%  |
| XGI Technology (eXtreme Graphics Innovation) | 8        | 0.92%   |
| Matrox Electronics Systems                   | 6        | 0.69%   |
| ASPEED Technology                            | 2        | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 41       | 4.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 37       | 4.15%   |
| Intel HD Graphics 530                                                       | 27       | 3.03%   |
| Nvidia GP107GL [Quadro P400]                                                | 20       | 2.24%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 20       | 2.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 20       | 2.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 20       | 2.24%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 19       | 2.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 16       | 1.8%    |
| Nvidia GK208B [GeForce GT 710]                                              | 15       | 1.68%   |
| Nvidia GK107GL [Quadro K420]                                                | 15       | 1.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 1.35%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 12       | 1.35%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 11       | 1.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 1.12%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 9        | 1.01%   |
| Nvidia GP102 [TITAN Xp]                                                     | 9        | 1.01%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 9        | 1.01%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 9        | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 9        | 1.01%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 9        | 1.01%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)              | 8        | 0.9%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 8        | 0.9%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 8        | 0.9%    |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                          | 8        | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 0.9%    |
| Intel HD Graphics 630                                                       | 8        | 0.9%    |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 0.79%   |
| Nvidia GF108 [GeForce GT 630]                                               | 7        | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 0.79%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 0.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 0.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 6        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 6        | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 0.67%   |
| Nvidia GM200 [GeForce GTX TITAN X]                                          | 6        | 0.67%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 6        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 413      | 49.7%   |
| 1 x AMD                  | 191      | 22.98%  |
| 1 x Intel                | 168      | 20.22%  |
| Intel + Nvidia           | 11       | 1.32%   |
| Other                    | 9        | 1.08%   |
| 1 x XGI                  | 8        | 0.96%   |
| AMD + Nvidia             | 7        | 0.84%   |
| 2 x AMD                  | 6        | 0.72%   |
| Intel + AMD              | 6        | 0.72%   |
| 1 x Matrox               | 5        | 0.6%    |
| 2 x Nvidia               | 3        | 0.36%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.12%   |
| Nvidia + Matrox          | 1        | 0.12%   |
| Nvidia + ASPEED          | 1        | 0.12%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 485      | 57.95%  |
| Proprietary | 309      | 36.92%  |
| Unknown     | 43       | 5.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 270      | 31.62%  |
| 1.01-2.0   | 143      | 16.74%  |
| 7.01-8.0   | 101      | 11.83%  |
| 0.51-1.0   | 89       | 10.42%  |
| 3.01-4.0   | 71       | 8.31%   |
| 8.01-16.0  | 70       | 8.2%    |
| 0.01-0.5   | 58       | 6.79%   |
| 5.01-6.0   | 27       | 3.16%   |
| 16.01-24.0 | 13       | 1.52%   |
| 2.01-3.0   | 10       | 1.17%   |
| 4.01-5.0   | 2        | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 186      | 21.02%  |
| Dell                 | 113      | 12.77%  |
| Acer                 | 76       | 8.59%   |
| Philips              | 63       | 7.12%   |
| Hewlett-Packard      | 60       | 6.78%   |
| BenQ                 | 54       | 6.1%    |
| Ancor Communications | 48       | 5.42%   |
| AOC                  | 37       | 4.18%   |
| Goldstar             | 32       | 3.62%   |
| Unknown              | 24       | 2.71%   |
| Eizo                 | 23       | 2.6%    |
| ASUSTek Computer     | 19       | 2.15%   |
| Sony                 | 14       | 1.58%   |
| Lenovo               | 12       | 1.36%   |
| Apple                | 12       | 1.36%   |
| Iiyama               | 11       | 1.24%   |
| NEC Computers        | 10       | 1.13%   |
| Medion               | 6        | 0.68%   |
| Fujitsu Siemens      | 6        | 0.68%   |
| Sharp                | 5        | 0.56%   |
| AUS                  | 5        | 0.56%   |
| ViewSonic            | 4        | 0.45%   |
| Panasonic            | 4        | 0.45%   |
| MSI                  | 4        | 0.45%   |
| LG Electronics       | 4        | 0.45%   |
| Gigabyte Technology  | 4        | 0.45%   |
| ___                  | 3        | 0.34%   |
| Toshiba              | 3        | 0.34%   |
| Belinea              | 3        | 0.34%   |
| Vestel               | 2        | 0.23%   |
| Onkyo                | 2        | 0.23%   |
| Medion Akoya         | 2        | 0.23%   |
| Idek Iiyama          | 2        | 0.23%   |
| HPN                  | 2        | 0.23%   |
| DENON                | 2        | 0.23%   |
| Compal               | 2        | 0.23%   |
| Yamaha               | 1        | 0.11%   |
| VMO                  | 1        | 0.11%   |
| Vestel Elektronik    | 1        | 0.11%   |
| USR                  | 1        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                   | 15       | 1.52%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                  | 11       | 1.12%   |
| Philips LCD Monitor PHL 272S4L 2560x1440                              | 7        | 0.71%   |
| Dell LCD Monitor P2719H 3840x1080                                     | 7        | 0.71%   |
| Dell LCD Monitor P2719H                                               | 7        | 0.71%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 7        | 0.71%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 520x320mm 24.0-inch  | 6        | 0.61%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 5        | 0.51%   |
| Sharp HDMI SHP1022 1920x1080 820x460mm 37.0-inch                      | 4        | 0.41%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 4        | 0.41%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 4        | 0.41%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 4        | 0.41%   |
| Samsung Electronics LCD Monitor SMS24A450 1920x1200                   | 4        | 0.41%   |
| Samsung Electronics C49HG9x SAM0E5D 1920x1080 1200x340mm 49.1-inch    | 4        | 0.41%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4        | 0.41%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 4        | 0.41%   |
| Acer X223HQ ACR0098 1920x1080 477x268mm 21.5-inch                     | 4        | 0.41%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 3        | 0.3%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 3        | 0.3%    |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 3        | 0.3%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.3%    |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 3        | 0.3%    |
| Samsung Electronics LCD Monitor SyncMaster 1600x1200                  | 3        | 0.3%    |
| Samsung Electronics LCD Monitor SMS24A450                             | 3        | 0.3%    |
| Samsung Electronics LCD Monitor S24C650 3840x1200                     | 3        | 0.3%    |
| Samsung Electronics LCD Monitor S24C650                               | 3        | 0.3%    |
| Philips LCD Monitor PHL 272S4L                                        | 3        | 0.3%    |
| Philips 272P4 PHL08C5 2560x1440 597x336mm 27.0-inch                   | 3        | 0.3%    |
| Philips 220SW PHL086F 1680x1050 474x296mm 22.0-inch                   | 3        | 0.3%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 3        | 0.3%    |
| Hewlett-Packard ZR2240w HWP2950 1920x1080 475x267mm 21.5-inch         | 3        | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3        | 0.3%    |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 3        | 0.3%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3        | 0.3%    |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 3        | 0.3%    |
| Dell LCD Monitor P2719H 1920x1080                                     | 3        | 0.3%    |
| Dell LCD Monitor 2001FP 1600x1200                                     | 3        | 0.3%    |
| Dell 2007FP DELA021 1600x1200 410x310mm 20.2-inch                     | 3        | 0.3%    |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                    | 3        | 0.3%    |
| BenQ LCD Monitor EW3270U 3840x2160                                    | 3        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 322      | 36.02%  |
| 3840x2160 (4K)     | 97       | 10.85%  |
| 2560x1440 (QHD)    | 83       | 9.28%   |
| 1920x1200 (WUXGA)  | 70       | 7.83%   |
| Unknown            | 64       | 7.16%   |
| 1680x1050 (WSXGA+) | 52       | 5.82%   |
| 1280x1024 (SXGA)   | 47       | 5.26%   |
| 3440x1440          | 28       | 3.13%   |
| 3840x1080          | 26       | 2.91%   |
| 1600x1200          | 19       | 2.13%   |
| 3840x1200          | 10       | 1.12%   |
| 2560x1600          | 9        | 1.01%   |
| 1440x900 (WXGA+)   | 7        | 0.78%   |
| 4480x1440          | 6        | 0.67%   |
| 2560x1080          | 6        | 0.67%   |
| 1360x768           | 5        | 0.56%   |
| 3520x1200          | 4        | 0.45%   |
| 7680x2160          | 3        | 0.34%   |
| 5120x1440          | 3        | 0.34%   |
| 3360x1050          | 3        | 0.34%   |
| 6400x1440          | 2        | 0.22%   |
| 3840x1600          | 2        | 0.22%   |
| 3200x1080          | 2        | 0.22%   |
| 2048x1152          | 2        | 0.22%   |
| 1920x540           | 2        | 0.22%   |
| 1600x900 (HD+)     | 2        | 0.22%   |
| 6400x2160          | 1        | 0.11%   |
| 5760x2160          | 1        | 0.11%   |
| 5760x1080          | 1        | 0.11%   |
| 5440x1080          | 1        | 0.11%   |
| 5348x1080          | 1        | 0.11%   |
| 3968x1200          | 1        | 0.11%   |
| 3600x1200          | 1        | 0.11%   |
| 3200x1800 (QHD+)   | 1        | 0.11%   |
| 2880x1200          | 1        | 0.11%   |
| 2560x1024          | 1        | 0.11%   |
| 2288x1287          | 1        | 0.11%   |
| 1400x1050          | 1        | 0.11%   |
| 1366x768 (WXGA)    | 1        | 0.11%   |
| 1280x960           | 1        | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 192      | 22.33%  |
| 27      | 136      | 15.81%  |
| 24      | 121      | 14.07%  |
| 23      | 85       | 9.88%   |
| 21      | 54       | 6.28%   |
| 31      | 40       | 4.65%   |
| 22      | 30       | 3.49%   |
| 19      | 26       | 3.02%   |
| 34      | 24       | 2.79%   |
| 20      | 22       | 2.56%   |
| 17      | 16       | 1.86%   |
| 32      | 12       | 1.4%    |
| 72      | 10       | 1.16%   |
| 84      | 9        | 1.05%   |
| 40      | 8        | 0.93%   |
| 29      | 8        | 0.93%   |
| 46      | 7        | 0.81%   |
| 28      | 6        | 0.7%    |
| 25      | 6        | 0.7%    |
| 37      | 5        | 0.58%   |
| 49      | 4        | 0.47%   |
| 26      | 4        | 0.47%   |
| 18      | 4        | 0.47%   |
| 54      | 3        | 0.35%   |
| 48      | 3        | 0.35%   |
| 33      | 3        | 0.35%   |
| 15      | 3        | 0.35%   |
| 60      | 2        | 0.23%   |
| 55      | 2        | 0.23%   |
| 42      | 2        | 0.23%   |
| 35      | 2        | 0.23%   |
| 142     | 1        | 0.12%   |
| 74      | 1        | 0.12%   |
| 65      | 1        | 0.12%   |
| 59      | 1        | 0.12%   |
| 50      | 1        | 0.12%   |
| 47      | 1        | 0.12%   |
| 43      | 1        | 0.12%   |
| 39      | 1        | 0.12%   |
| 30      | 1        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 307      | 36.77%  |
| Unknown        | 192      | 22.99%  |
| 401-500        | 112      | 13.41%  |
| 601-700        | 73       | 8.74%   |
| 701-800        | 39       | 4.67%   |
| 351-400        | 26       | 3.11%   |
| 1001-1500      | 26       | 3.11%   |
| 301-350        | 20       | 2.4%    |
| 1501-2000      | 20       | 2.4%    |
| 801-900        | 16       | 1.92%   |
| 901-1000       | 2        | 0.24%   |
| More than 2000 | 1        | 0.12%   |
| 201-300        | 1        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 398      | 49.63%  |
| Unknown | 183      | 22.82%  |
| 16/10   | 120      | 14.96%  |
| 5/4     | 41       | 5.11%   |
| 21/9    | 30       | 3.74%   |
| 4/3     | 15       | 1.87%   |
| 32/9    | 7        | 0.87%   |
| 3/2     | 3        | 0.37%   |
| 6/5     | 2        | 0.25%   |
| 1.00    | 2        | 0.25%   |
| 3.20    | 1        | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 209      | 24.73%  |
| Unknown        | 192      | 22.72%  |
| 301-350        | 139      | 16.45%  |
| 351-500        | 93       | 11.01%  |
| 251-300        | 68       | 8.05%   |
| 151-200        | 63       | 7.46%   |
| More than 1000 | 33       | 3.91%   |
| 501-1000       | 27       | 3.2%    |
| 141-150        | 16       | 1.89%   |
| 101-110        | 2        | 0.24%   |
| 71-80          | 1        | 0.12%   |
| 131-140        | 1        | 0.12%   |
| 91-100         | 1        | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 385      | 47.89%  |
| Unknown       | 192      | 23.88%  |
| 101-120       | 129      | 16.04%  |
| 121-160       | 48       | 5.97%   |
| 1-50          | 33       | 4.1%    |
| 161-240       | 16       | 1.99%   |
| More than 240 | 1        | 0.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 573      | 66.32%  |
| 2     | 178      | 20.6%   |
| 0     | 80       | 9.26%   |
| 3     | 29       | 3.36%   |
| 4     | 4        | 0.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 490      | 42.87%  |
| Realtek Semiconductor           | 387      | 33.86%  |
| Qualcomm Atheros                | 48       | 4.2%    |
| Broadcom                        | 38       | 3.32%   |
| Aquantia                        | 27       | 2.36%   |
| Ralink Technology               | 12       | 1.05%   |
| Ralink                          | 11       | 0.96%   |
| Nvidia                          | 11       | 0.96%   |
| MediaTek                        | 10       | 0.87%   |
| Marvell Technology Group        | 10       | 0.87%   |
| TP-Link                         | 9        | 0.79%   |
| NetGear                         | 9        | 0.79%   |
| Edimax Technology               | 8        | 0.7%    |
| D-Link                          | 6        | 0.52%   |
| Microsoft                       | 5        | 0.44%   |
| IMC Networks                    | 5        | 0.44%   |
| Broadcom Limited                | 5        | 0.44%   |
| Huawei Technologies             | 4        | 0.35%   |
| ASUSTek Computer                | 4        | 0.35%   |
| ASIX Electronics                | 4        | 0.35%   |
| Xiaomi                          | 3        | 0.26%   |
| Samsung Electronics             | 3        | 0.26%   |
| D-Link System                   | 3        | 0.26%   |
| AVM                             | 3        | 0.26%   |
| Wilocity                        | 2        | 0.17%   |
| Qualcomm Atheros Communications | 2        | 0.17%   |
| NetXen Incorporated             | 2        | 0.17%   |
| Microchip Technology            | 2        | 0.17%   |
| Micro Star International        | 2        | 0.17%   |
| Mellanox Technologies           | 2        | 0.17%   |
| ZEPHYR                          | 1        | 0.09%   |
| SEGGER                          | 1        | 0.09%   |
| QNAP System                     | 1        | 0.09%   |
| Philips (or NXP)                | 1        | 0.09%   |
| Netopia                         | 1        | 0.09%   |
| Netchip Technology              | 1        | 0.09%   |
| Linksys                         | 1        | 0.09%   |
| InterBiometrics                 | 1        | 0.09%   |
| Gemtek                          | 1        | 0.09%   |
| Fitbit                          | 1        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 298      | 22.82%  |
| Intel I211 Gigabit Network Connection                             | 94       | 7.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 58       | 4.44%   |
| Intel Ethernet Connection (2) I219-V                              | 56       | 4.29%   |
| Intel Wi-Fi 6 AX200                                               | 51       | 3.91%   |
| Intel Ethernet Connection I217-LM                                 | 37       | 2.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 31       | 2.37%   |
| Intel 82574L Gigabit Network Connection                           | 31       | 2.37%   |
| Intel 82579V Gigabit Network Connection                           | 30       | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30       | 2.3%    |
| Intel Ethernet Controller I225-V                                  | 24       | 1.84%   |
| Intel Ethernet Connection (2) I218-V                              | 23       | 1.76%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 1.61%   |
| Intel I210 Gigabit Network Connection                             | 16       | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12       | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10       | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 9        | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 9        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8        | 0.61%   |
| Intel Wireless-AC 9260                                            | 8        | 0.61%   |
| Intel Wireless 7260                                               | 8        | 0.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 0.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 7        | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 7        | 0.54%   |
| Intel Wireless 8260                                               | 7        | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6        | 0.46%   |
| Nvidia MCP55 Ethernet                                             | 6        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 6        | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5        | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 5        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5        | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5        | 0.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5        | 0.38%   |
| Intel Wireless 8265 / 8275                                        | 5        | 0.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5        | 0.38%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 143      | 41.69%  |
| Realtek Semiconductor                 | 57       | 16.62%  |
| Qualcomm Atheros                      | 31       | 9.04%   |
| Broadcom                              | 14       | 4.08%   |
| Ralink Technology                     | 12       | 3.5%    |
| Ralink                                | 11       | 3.21%   |
| NetGear                               | 9        | 2.62%   |
| MediaTek                              | 9        | 2.62%   |
| TP-Link                               | 8        | 2.33%   |
| Edimax Technology                     | 8        | 2.33%   |
| D-Link                                | 6        | 1.75%   |
| Microsoft                             | 5        | 1.46%   |
| IMC Networks                          | 5        | 1.46%   |
| ASUSTek Computer                      | 4        | 1.17%   |
| D-Link System                         | 3        | 0.87%   |
| AVM                                   | 3        | 0.87%   |
| Wilocity                              | 2        | 0.58%   |
| Qualcomm Atheros Communications       | 2        | 0.58%   |
| Micro Star International              | 2        | 0.58%   |
| Broadcom Limited                      | 2        | 0.58%   |
| Philips (or NXP)                      | 1        | 0.29%   |
| Netopia                               | 1        | 0.29%   |
| Marvell Technology Group              | 1        | 0.29%   |
| Gemtek                                | 1        | 0.29%   |
| Belkin Components                     | 1        | 0.29%   |
| Arduino SA                            | 1        | 0.29%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 51       | 14.78%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12       | 3.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10       | 2.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 9        | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8        | 2.32%   |
| Intel Wireless-AC 9260                                         | 8        | 2.32%   |
| Intel Wireless 7260                                            | 8        | 2.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 8        | 2.32%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 7        | 2.03%   |
| Intel Wireless 8260                                            | 7        | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6        | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5        | 1.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 5        | 1.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 5        | 1.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5        | 1.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5        | 1.45%   |
| Intel Wireless 8265 / 8275                                     | 5        | 1.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5        | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5        | 1.45%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]           | 5        | 1.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 5        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4        | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 4        | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4        | 1.16%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 4        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4        | 1.16%   |
| NetGear A6210                                                  | 4        | 1.16%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 4        | 1.16%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 3        | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3        | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3        | 0.87%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 3        | 0.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3        | 0.87%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3        | 0.87%   |
| Intel Wireless 3165                                            | 3        | 0.87%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3        | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3        | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3        | 0.87%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 2        | 0.58%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 428      | 46.98%  |
| Realtek Semiconductor    | 368      | 40.4%   |
| Aquantia                 | 27       | 2.96%   |
| Broadcom                 | 24       | 2.63%   |
| Qualcomm Atheros         | 18       | 1.98%   |
| Nvidia                   | 11       | 1.21%   |
| Marvell Technology Group | 9        | 0.99%   |
| Huawei Technologies      | 4        | 0.44%   |
| ASIX Electronics         | 4        | 0.44%   |
| Xiaomi                   | 3        | 0.33%   |
| Broadcom Limited         | 3        | 0.33%   |
| NetXen Incorporated      | 2        | 0.22%   |
| Mellanox Technologies    | 2        | 0.22%   |
| TP-Link                  | 1        | 0.11%   |
| Samsung Electronics      | 1        | 0.11%   |
| QNAP System              | 1        | 0.11%   |
| Netchip Technology       | 1        | 0.11%   |
| MediaTek                 | 1        | 0.11%   |
| Linksys                  | 1        | 0.11%   |
| DisplayLink              | 1        | 0.11%   |
| ADMtek                   | 1        | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 298      | 31.3%   |
| Intel I211 Gigabit Network Connection                             | 94       | 9.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 58       | 6.09%   |
| Intel Ethernet Connection (2) I219-V                              | 56       | 5.88%   |
| Intel Ethernet Connection I217-LM                                 | 37       | 3.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 31       | 3.26%   |
| Intel 82574L Gigabit Network Connection                           | 31       | 3.26%   |
| Intel 82579V Gigabit Network Connection                           | 30       | 3.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30       | 3.15%   |
| Intel Ethernet Controller I225-V                                  | 24       | 2.52%   |
| Intel Ethernet Connection (2) I218-V                              | 23       | 2.42%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 2.21%   |
| Intel I210 Gigabit Network Connection                             | 16       | 1.68%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 9        | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 0.84%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 7        | 0.74%   |
| Nvidia MCP55 Ethernet                                             | 6        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 6        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.42%   |
| Intel Ethernet Connection (11) I219-LM                            | 4        | 0.42%   |
| Huawei WLZ-AN00                                                   | 4        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4        | 0.42%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 4        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.32%   |
| Nvidia MCP77 Ethernet                                             | 3        | 0.32%   |
| Intel I350 Gigabit Network Connection                             | 3        | 0.32%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.32%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.32%   |
| Intel 82583V Gigabit Network Connection                           | 3        | 0.32%   |
| Intel 82567V-2 Gigabit Network Connection                         | 3        | 0.32%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.32%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 3        | 0.32%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 3        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 816      | 71.02%  |
| WiFi     | 325      | 28.29%  |
| Modem    | 8        | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 693      | 83.7%   |
| WiFi     | 135      | 16.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 477      | 57.47%  |
| 2     | 263      | 31.69%  |
| 3     | 64       | 7.71%   |
| 4     | 13       | 1.57%   |
| 0     | 5        | 0.6%    |
| 5     | 4        | 0.48%   |
| 6     | 3        | 0.36%   |
| 7     | 1        | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 679      | 80.74%  |
| Yes  | 162      | 19.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 136      | 49.82%  |
| Cambridge Silicon Radio         | 48       | 17.58%  |
| ASUSTek Computer                | 27       | 9.89%   |
| Realtek Semiconductor           | 15       | 5.49%   |
| IMC Networks                    | 11       | 4.03%   |
| Qualcomm Atheros Communications | 8        | 2.93%   |
| Broadcom                        | 7        | 2.56%   |
| MediaTek                        | 5        | 1.83%   |
| Apple                           | 5        | 1.83%   |
| Micro Star International        | 2        | 0.73%   |
| Lite-On Technology              | 2        | 0.73%   |
| Realtek                         | 1        | 0.37%   |
| Logitech                        | 1        | 0.37%   |
| Integrated System Solution      | 1        | 0.37%   |
| Foxconn / Hon Hai               | 1        | 0.37%   |
| Edimax Technology               | 1        | 0.37%   |
| Dell                            | 1        | 0.37%   |
| Unknown                         | 1        | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 48       | 17.58%  |
| Intel AX200 Bluetooth                                   | 47       | 17.22%  |
| Intel Bluetooth wireless interface                      | 26       | 9.52%   |
| Intel AX201 Bluetooth                                   | 15       | 5.49%   |
| Intel Wireless-AC 3168 Bluetooth                        | 12       | 4.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 10       | 3.66%   |
| Realtek Bluetooth Radio                                 | 9        | 3.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 9        | 3.3%    |
| Intel Bluetooth Device                                  | 7        | 2.56%   |
| Intel AX210 Bluetooth                                   | 7        | 2.56%   |
| IMC Networks Bluetooth Radio                            | 7        | 2.56%   |
| ASUS ASUS USB-BT500                                     | 7        | 2.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 6        | 2.2%    |
| MediaTek Wireless_Device                                | 5        | 1.83%   |
| ASUS Qualcomm Bluetooth 4.1                             | 4        | 1.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 4        | 1.47%   |
| ASUS Bluetooth Device                                   | 4        | 1.47%   |
| ASUS BCM20702A0                                         | 4        | 1.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                    | 4        | 1.47%   |
| Realtek  Bluetooth 4.2 Adapter                          | 3        | 1.1%    |
| Qualcomm Atheros  Bluetooth Device                      | 3        | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver           | 3        | 1.1%    |
| IMC Networks Wireless_Device                            | 3        | 1.1%    |
| ASUS Bluetooth Radio                                    | 3        | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                       | 2        | 0.73%   |
| Micro Star International Bluetooth Device               | 2        | 0.73%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                 | 1        | 0.37%   |
| Realtek RTL8821A Bluetooth                              | 1        | 0.37%   |
| Realtek Bluetooth 5.1 Radio                             | 1        | 0.37%   |
| Realtek Bluetooth Radio                                 | 1        | 0.37%   |
| Qualcomm Atheros Bluetooth USB Host Controller          | 1        | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                       | 1        | 0.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 1        | 0.37%   |
| Logitech BT Mini-Receiver (HCI mode)                    | 1        | 0.37%   |
| Lite-On Bluetooth Device                                | 1        | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                        | 1        | 0.37%   |
| Integrated System Solution Bluetooth Device             | 1        | 0.37%   |
| IMC Networks Bluetooth Module                           | 1        | 0.37%   |
| Foxconn / Hon Hai Wireless_Device                       | 1        | 0.37%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 541      | 37.49%  |
| Nvidia                     | 407      | 28.21%  |
| AMD                        | 306      | 21.21%  |
| C-Media Electronics        | 24       | 1.66%   |
| Logitech                   | 21       | 1.46%   |
| GN Netcom                  | 20       | 1.39%   |
| ASUSTek Computer           | 17       | 1.18%   |
| Creative Labs              | 10       | 0.69%   |
| SteelSeries ApS            | 7        | 0.49%   |
| Kingston Technology        | 6        | 0.42%   |
| RODE Microphones           | 5        | 0.35%   |
| Razer USA                  | 5        | 0.35%   |
| Apple                      | 5        | 0.35%   |
| Samson Technologies        | 4        | 0.28%   |
| Plantronics                | 4        | 0.28%   |
| Texas Instruments          | 3        | 0.21%   |
| Tenx Technology            | 3        | 0.21%   |
| Corsair                    | 3        | 0.21%   |
| BEHRINGER International    | 3        | 0.21%   |
| Yamaha                     | 2        | 0.14%   |
| XMOS                       | 2        | 0.14%   |
| TerraTec Electronic        | 2        | 0.14%   |
| Sony                       | 2        | 0.14%   |
| Sennheiser Communications  | 2        | 0.14%   |
| Roland                     | 2        | 0.14%   |
| ROCCAT                     | 2        | 0.14%   |
| JMTek                      | 2        | 0.14%   |
| Giga-Byte Technology       | 2        | 0.14%   |
| Creative Technology        | 2        | 0.14%   |
| Trust                      | 1        | 0.07%   |
| Textech International      | 1        | 0.07%   |
| TEAC                       | 1        | 0.07%   |
| Shure                      | 1        | 0.07%   |
| SAVITECH                   | 1        | 0.07%   |
| PreSonus Audio Electronics | 1        | 0.07%   |
| Microsoft                  | 1        | 0.07%   |
| Micronas                   | 1        | 0.07%   |
| Micro Star International   | 1        | 0.07%   |
| HiFiBerry                  | 1        | 0.07%   |
| Hewlett-Packard            | 1        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 109      | 6.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 61       | 3.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 61       | 3.74%   |
| Intel 200 Series PCH HD Audio                                                     | 52       | 3.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 51       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 49       | 3%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 48       | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 43       | 2.63%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 39       | 2.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 37       | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 33       | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                        | 31       | 1.9%    |
| Nvidia GP102 HDMI Audio Controller                                                | 28       | 1.72%   |
| Nvidia GA104 High Definition Audio Controller                                     | 28       | 1.72%   |
| Nvidia GK107 HDMI Audio Controller                                                | 27       | 1.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 27       | 1.65%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 26       | 1.59%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 25       | 1.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 23       | 1.41%   |
| Nvidia GA102 High Definition Audio Controller                                     | 23       | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 22       | 1.35%   |
| AMD Family 17h/19h HD Audio Controller                                            | 22       | 1.35%   |
| Nvidia GP106 High Definition Audio Controller                                     | 21       | 1.29%   |
| Nvidia GP104 High Definition Audio Controller                                     | 21       | 1.29%   |
| Nvidia GK104 HDMI Audio Controller                                                | 21       | 1.29%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 20       | 1.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 19       | 1.16%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 18       | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 18       | 1.1%    |
| AMD Navi 10 HDMI Audio                                                            | 18       | 1.1%    |
| Nvidia GF119 HDMI Audio Controller                                                | 17       | 1.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 16       | 0.98%   |
| Nvidia GM204 High Definition Audio Controller                                     | 14       | 0.86%   |
| ASUSTek Computer USB Audio                                                        | 13       | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 13       | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                                     | 12       | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                     | 12       | 0.74%   |
| Nvidia TU102 High Definition Audio Controller                                     | 12       | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                     | 12       | 0.74%   |
| AMD FCH Azalia Controller                                                         | 12       | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 153      | 27.08%  |
| Corsair             | 122      | 21.59%  |
| Samsung Electronics | 64       | 11.33%  |
| SK hynix            | 55       | 9.73%   |
| Unknown             | 43       | 7.61%   |
| G.Skill             | 38       | 6.73%   |
| Micron Technology   | 30       | 5.31%   |
| Crucial             | 27       | 4.78%   |
| Patriot             | 4        | 0.71%   |
| Elpida              | 3        | 0.53%   |
| Avant               | 3        | 0.53%   |
| Unknown (0x9801)    | 2        | 0.35%   |
| Nanya Technology    | 2        | 0.35%   |
| Hewlett-Packard     | 2        | 0.35%   |
| Apacer              | 2        | 0.35%   |
| Unknown (ABCD)      | 1        | 0.18%   |
| Unifosa             | 1        | 0.18%   |
| Team                | 1        | 0.18%   |
| Smart               | 1        | 0.18%   |
| Ramaxel Technology  | 1        | 0.18%   |
| Princeton           | 1        | 0.18%   |
| Patriot Memory      | 1        | 0.18%   |
| OCZ                 | 1        | 0.18%   |
| Kingmax             | 1        | 0.18%   |
| KANMEIQi            | 1        | 0.18%   |
| G-Alantic           | 1        | 0.18%   |
| Advantech           | 1        | 0.18%   |
| A-DATA Technology   | 1        | 0.18%   |
| 48spaces            | 1        | 0.18%   |
| Unknown             | 1        | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s     | 13       | 2.09%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s | 13       | 2.09%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s     | 9        | 1.44%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s    | 8        | 1.28%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s    | 7        | 1.12%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 6        | 0.96%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s     | 5        | 0.8%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s    | 5        | 0.8%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s     | 5        | 0.8%    |
| Corsair RAM CM4X16GC3000C16K8 16GB DIMM DDR4 3000MT/s     | 5        | 0.8%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 4        | 0.64%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s      | 4        | 0.64%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s      | 4        | 0.64%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                 | 4        | 0.64%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s       | 4        | 0.64%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s             | 4        | 0.64%   |
| Kingston RAM Module 2048MB DIMM DDR3 1333MT/s             | 4        | 0.64%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s          | 4        | 0.64%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s     | 4        | 0.64%   |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s     | 4        | 0.64%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s     | 4        | 0.64%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s    | 4        | 0.64%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 4        | 0.64%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 3        | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 3        | 0.48%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                   | 3        | 0.48%   |
| SK hynix RAM Module 16GB DIMM DDR4 3200MT/s               | 3        | 0.48%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s       | 3        | 0.48%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s       | 3        | 0.48%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2667MT/s       | 3        | 0.48%   |
| Micron RAM 18ASF1G72PZ-2G1A2 8GB RIMM DDR4 2133MT/s       | 3        | 0.48%   |
| Micron RAM 18ASF1G72PZ-2G1A2 8GB DIMM DDR4 2400MT/s       | 3        | 0.48%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 3        | 0.48%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 3        | 0.48%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s         | 3        | 0.48%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 3        | 0.48%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s     | 3        | 0.48%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s     | 3        | 0.48%   |
| Kingston RAM 9905734-120.A00G 16GB DIMM DDR4 3200MT/s     | 3        | 0.48%   |
| Kingston RAM 9905734-020.A00G 16GB DIMM DDR4 3200MT/s     | 3        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 306      | 57.63%  |
| DDR3    | 165      | 31.07%  |
| Unknown | 20       | 3.77%   |
| DDR2    | 18       | 3.39%   |
| SDRAM   | 11       | 2.07%   |
| DDR5    | 8        | 1.51%   |
| DDR     | 2        | 0.38%   |
| LPDDR4  | 1        | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 486      | 92.4%   |
| SODIMM  | 33       | 6.27%   |
| RIMM    | 6        | 1.14%   |
| Unknown | 1        | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 204      | 36.62%  |
| 16384 | 154      | 27.65%  |
| 4096  | 103      | 18.49%  |
| 2048  | 50       | 8.98%   |
| 32768 | 37       | 6.64%   |
| 1024  | 9        | 1.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 98       | 17.1%   |
| 3200  | 75       | 13.09%  |
| 1333  | 62       | 10.82%  |
| 2133  | 41       | 7.16%   |
| 2400  | 39       | 6.81%   |
| 2667  | 33       | 5.76%   |
| 3600  | 29       | 5.06%   |
| 3000  | 25       | 4.36%   |
| 3400  | 19       | 3.32%   |
| 2666  | 17       | 2.97%   |
| 800   | 16       | 2.79%   |
| 3800  | 7        | 1.22%   |
| 1066  | 7        | 1.22%   |
| 3266  | 6        | 1.05%   |
| 2933  | 6        | 1.05%   |
| 1800  | 6        | 1.05%   |
| 667   | 6        | 1.05%   |
| 3533  | 5        | 0.87%   |
| 3100  | 5        | 0.87%   |
| 2000  | 5        | 0.87%   |
| 1866  | 5        | 0.87%   |
| 1334  | 5        | 0.87%   |
| 5808  | 4        | 0.7%    |
| 3733  | 4        | 0.7%    |
| 3666  | 4        | 0.7%    |
| 2465  | 4        | 0.7%    |
| 6000  | 3        | 0.52%   |
| 3500  | 3        | 0.52%   |
| 1867  | 3        | 0.52%   |
| 4800  | 2        | 0.35%   |
| 3933  | 2        | 0.35%   |
| 3534  | 2        | 0.35%   |
| 3466  | 2        | 0.35%   |
| 3334  | 2        | 0.35%   |
| 2800  | 2        | 0.35%   |
| 1648  | 2        | 0.35%   |
| 333   | 2        | 0.35%   |
| 4199  | 1        | 0.17%   |
| 3867  | 1        | 0.17%   |
| 3866  | 1        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 23       | 50%     |
| Brother Industries       | 9        | 19.57%  |
| STMicroelectronics       | 3        | 6.52%   |
| Samsung Electronics      | 3        | 6.52%   |
| Canon                    | 3        | 6.52%   |
| Seiko Epson              | 2        | 4.35%   |
| Zhuhai Poskey Technology | 1        | 2.17%   |
| Oki Data                 | 1        | 2.17%   |
| Dymo-CoStar              | 1        | 2.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 3        | 6.52%   |
| HP OfficeJet Pro 7730 series                               | 2        | 4.35%   |
| HP OfficeJet 6950                                          | 2        | 4.35%   |
| HP LaserJet Pro M148f-M149f                                | 2        | 4.35%   |
| HP ENVY 5540 series                                        | 2        | 4.35%   |
| HP Deskjet 2540 series                                     | 2        | 4.35%   |
| Brother Printer                                            | 2        | 4.35%   |
| Zhuhai Poskey Printer                                      | 1        | 2.17%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 2.17%   |
| Seiko Epson ET-2820 Series                                 | 1        | 2.17%   |
| Samsung M337x 387x 407x Series                             | 1        | 2.17%   |
| Samsung M332x 382x 402x Series                             | 1        | 2.17%   |
| Samsung C48x Series Color Laser Multifunction Printer      | 1        | 2.17%   |
| Oki Data USB Device                                        | 1        | 2.17%   |
| HP Smart Tank Plus 550 series                              | 1        | 2.17%   |
| HP Smart Tank 7000 series                                  | 1        | 2.17%   |
| HP Officejet 4630 series                                   | 1        | 2.17%   |
| HP LaserJet P3010 Series                                   | 1        | 2.17%   |
| HP LaserJet P2055 series                                   | 1        | 2.17%   |
| HP LaserJet P1102                                          | 1        | 2.17%   |
| HP LaserJet 3050                                           | 1        | 2.17%   |
| HP LaserJet 3020                                           | 1        | 2.17%   |
| HP LaserJet 1320                                           | 1        | 2.17%   |
| HP LaserJet 1020                                           | 1        | 2.17%   |
| HP ENVY 6400 series                                        | 1        | 2.17%   |
| HP ENVY 4520 series                                        | 1        | 2.17%   |
| HP DeskJet F2100 Printer series                            | 1        | 2.17%   |
| Dymo-CoStar LabelWriter 450                                | 1        | 2.17%   |
| Canon TS3300 series                                        | 1        | 2.17%   |
| Canon PIXMA MX450 Series                                   | 1        | 2.17%   |
| Canon iP7200 series                                        | 1        | 2.17%   |
| Brother MFC-9320CW                                         | 1        | 2.17%   |
| Brother MFC Composite Device                               | 1        | 2.17%   |
| Brother HL-L2360D series                                   | 1        | 2.17%   |
| Brother HL-L2350DW series                                  | 1        | 2.17%   |
| Brother HL-2130 series                                     | 1        | 2.17%   |
| Brother DCP-9020CDW                                        | 1        | 2.17%   |
| Brother DCP-7030                                           | 1        | 2.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 6        | 50%     |
| Seiko Epson     | 3        | 25%     |
| Hewlett-Packard | 2        | 16.67%  |
| Fujitsu         | 1        | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                                       | 2        | 16.67%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                   | 1        | 8.33%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1        | 8.33%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 8.33%   |
| HP ScanJet 4070 PhotoSmart                                    | 1        | 8.33%   |
| HP ScanJet 2400c                                              | 1        | 8.33%   |
| Fujitsu ScanSnap SV600                                        | 1        | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20                            | 1        | 8.33%   |
| Canon CanoScan N650U/N656U                                    | 1        | 8.33%   |
| Canon CanoScan LIDE 25                                        | 1        | 8.33%   |
| Canon CanoScan LiDE 100                                       | 1        | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 65       | 51.18%  |
| Microsoft                     | 8        | 6.3%    |
| Microdia                      | 8        | 6.3%    |
| Apple                         | 8        | 6.3%    |
| Sunplus Innovation Technology | 7        | 5.51%   |
| Samsung Electronics           | 4        | 3.15%   |
| Chicony Electronics           | 3        | 2.36%   |
| Z-Star Microelectronics       | 2        | 1.57%   |
| Realtek Semiconductor         | 2        | 1.57%   |
| MacroSilicon                  | 2        | 1.57%   |
| Generalplus Technology        | 2        | 1.57%   |
| Creative Technology           | 2        | 1.57%   |
| YGTek                         | 1        | 0.79%   |
| Xiaomi                        | 1        | 0.79%   |
| Sonix Technology              | 1        | 0.79%   |
| LeCroy                        | 1        | 0.79%   |
| IPEVO                         | 1        | 0.79%   |
| Intel                         | 1        | 0.79%   |
| IMC Networks                  | 1        | 0.79%   |
| Huawei Technologies           | 1        | 0.79%   |
| HD USB Camera                 | 1        | 0.79%   |
| Fujitsu                       | 1        | 0.79%   |
| Bison Electronics             | 1        | 0.79%   |
| Aveo Technology               | 1        | 0.79%   |
| ASUSTek Computer              | 1        | 0.79%   |
| A4Tech                        | 1        | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech Webcam C270                        | 13       | 10.24%  |
| Logitech HD Pro Webcam C920                 | 12       | 9.45%   |
| Logitech HD Webcam C615                     | 6        | 4.72%   |
| Logitech Webcam C930e                       | 5        | 3.94%   |
| Sunplus SPCA2281 Web Camera                 | 4        | 3.15%   |
| Samsung Galaxy series, misc. (MTP mode)     | 4        | 3.15%   |
| Microsoft LifeCam HD-3000                   | 4        | 3.15%   |
| Logitech HD Webcam C525                     | 4        | 3.15%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X             | 4        | 3.15%   |
| Logitech QuickCam Pro 9000                  | 3        | 2.36%   |
| Apple iSight in LED Cinema Display          | 3        | 2.36%   |
| Microdia Camera                             | 2        | 1.57%   |
| MacroSilicon USB Video                      | 2        | 1.57%   |
| Logitech Webcam Pro 9000                    | 2        | 1.57%   |
| Logitech StreamCam                          | 2        | 1.57%   |
| Logitech BRIO Ultra HD Webcam               | 2        | 1.57%   |
| Generalplus GENERAL WEBCAM                  | 2        | 1.57%   |
| Creative Live! Cam Chat HD [VF0700]         | 2        | 1.57%   |
| Z-Star Vimicro USB2.0 UVC PC Camera         | 1        | 0.79%   |
| Z-Star Integrated Camera                    | 1        | 0.79%   |
| YGTek webcam                                | 1        | 0.79%   |
| Xiaomi Mi 9T Pro                            | 1        | 0.79%   |
| Sunplus Sandberg USB Webcam Pro             | 1        | 0.79%   |
| Sunplus Aukey-PC-LM1E Camera                | 1        | 0.79%   |
| Sunplus 1080P Webcam                        | 1        | 0.79%   |
| Sonix QHD Webcam                            | 1        | 0.79%   |
| Realtek HP 1.0MP High Definition Webcam     | 1        | 0.79%   |
| Realtek FULL HD 1080P Webcam                | 1        | 0.79%   |
| Microsoft MicrosoftÂ LifeCam Studio        | 1        | 0.79%   |
| Microsoft LifeCam VX-5000                   | 1        | 0.79%   |
| Microsoft LifeCam VX-500 [1357]             | 1        | 0.79%   |
| Microsoft LifeCam Cinema                    | 1        | 0.79%   |
| Microdia Sonix USB 2.0 Camera               | 1        | 0.79%   |
| Microdia Front camera                       | 1        | 0.79%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 0.79%   |
| Microdia CyberTrack H6                      | 1        | 0.79%   |
| Microdia AUKEY-W1                           | 1        | 0.79%   |
| Microdia AUKEY PC-LM3                       | 1        | 0.79%   |
| Logitech Webcam C600                        | 1        | 0.79%   |
| Logitech Webcam C310                        | 1        | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Alcor Micro           | 3        | 37.5%   |
| Yubico.com            | 2        | 25%     |
| Clay Logic            | 1        | 12.5%   |
| Bit4id                | 1        | 12.5%   |
| Advanced Card Systems | 1        | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3        | 37.5%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID | 1        | 12.5%   |
| Yubico.com Yubikey 4/5 U2F+CCID     | 1        | 12.5%   |
| Clay Logic Nitrokey Start           | 1        | 12.5%   |
| Bit4id miniLector-s                 | 1        | 12.5%   |
| Advanced Card Systems ACR122U       | 1        | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 712      | 84.26%  |
| 1     | 111      | 13.14%  |
| 2     | 15       | 1.78%   |
| 3     | 3        | 0.36%   |
| 6     | 2        | 0.24%   |
| 4     | 2        | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 46       | 28.75%  |
| Net/wireless             | 36       | 22.5%   |
| Unassigned class         | 24       | 15%     |
| Communication controller | 10       | 6.25%   |
| Sound                    | 9        | 5.63%   |
| Multimedia controller    | 7        | 4.38%   |
| Camera                   | 5        | 3.13%   |
| Bluetooth                | 5        | 3.13%   |
| Storage/raid             | 4        | 2.5%    |
| Network                  | 4        | 2.5%    |
| Net/ethernet             | 3        | 1.88%   |
| Chipcard                 | 3        | 1.88%   |
| Storage/nvme             | 1        | 0.63%   |
| Modem                    | 1        | 0.63%   |
| Firewire controller      | 1        | 0.63%   |
| Fingerprint reader       | 1        | 0.63%   |


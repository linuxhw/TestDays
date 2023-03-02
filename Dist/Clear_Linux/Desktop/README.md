Clear Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Clear Linux.

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

Total: 446

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell       | 0KWVT8 A03                  | [fcea958b77](https://linux-hardware.org/?probe=fcea958b77) | Feb 26, 2023 |
| Dell       | 0GXM1W A00                  | [e7edf0f7c3](https://linux-hardware.org/?probe=e7edf0f7c3) | Feb 23, 2023 |
| Dell       | 00V62H A01                  | [ade0244936](https://linux-hardware.org/?probe=ade0244936) | Feb 21, 2023 |
| HP         | 212A                        | [5b9c217d02](https://linux-hardware.org/?probe=5b9c217d02) | Jan 27, 2023 |
| MSI        | TRX40 PRO 10G               | [492a6fb119](https://linux-hardware.org/?probe=492a6fb119) | Jan 14, 2023 |
| ASUSTek    | TUF B360M-PLUS GAMING/BR    | [52164aa403](https://linux-hardware.org/?probe=52164aa403) | Jan 10, 2023 |
| HP         | 8399                        | [8a4ef9ab88](https://linux-hardware.org/?probe=8a4ef9ab88) | Dec 29, 2022 |
| ASUSTek    | Z170-DELUXE                 | [915c2dd055](https://linux-hardware.org/?probe=915c2dd055) | Dec 17, 2022 |
| Gigabyte   | G1.SNIPER B7-CF             | [c53295ce70](https://linux-hardware.org/?probe=c53295ce70) | Nov 25, 2022 |
| ASUSTek    | P8H61-I LX/RM/SI            | [61cfa154b0](https://linux-hardware.org/?probe=61cfa154b0) | Nov 24, 2022 |
| ASUSTek    | Z97M-PLUS                   | [be2b867450](https://linux-hardware.org/?probe=be2b867450) | Nov 20, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [8084d88d4b](https://linux-hardware.org/?probe=8084d88d4b) | Nov 17, 2022 |
| ASUSTek    | Z170 PRO GAMING             | [c1103d767e](https://linux-hardware.org/?probe=c1103d767e) | Nov 12, 2022 |
| HP         | 3397                        | [27c0a5213d](https://linux-hardware.org/?probe=27c0a5213d) | Nov 11, 2022 |
| HP         | 8643 SMVB                   | [768e2bbf53](https://linux-hardware.org/?probe=768e2bbf53) | Nov 04, 2022 |
| Dell       | 042P49 A01                  | [1fb51cc10c](https://linux-hardware.org/?probe=1fb51cc10c) | Oct 31, 2022 |
| ASUSTek    | Z170I PRO GAMING            | [2ae55c9228](https://linux-hardware.org/?probe=2ae55c9228) | Oct 27, 2022 |
| HP         | 8643 SMVB                   | [34f98de888](https://linux-hardware.org/?probe=34f98de888) | Oct 27, 2022 |
| HP         | 8643 SMVB                   | [b29a0df34f](https://linux-hardware.org/?probe=b29a0df34f) | Oct 27, 2022 |
| ASUSTek    | P8P67 LE                    | [a78f249f0e](https://linux-hardware.org/?probe=a78f249f0e) | Oct 23, 2022 |
| Dell       | 0VRWRC A00                  | [543bbf49af](https://linux-hardware.org/?probe=543bbf49af) | Oct 19, 2022 |
| Dell       | 0VRWRC A00                  | [f13dd4393d](https://linux-hardware.org/?probe=f13dd4393d) | Oct 19, 2022 |
| ASUSTek    | ROG ZENITH II EXTREME AL... | [ff225777df](https://linux-hardware.org/?probe=ff225777df) | Oct 18, 2022 |
| ASUSTek    | ROG Maximus Z690 HERO       | [b966faf224](https://linux-hardware.org/?probe=b966faf224) | Oct 14, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [28a985f0e9](https://linux-hardware.org/?probe=28a985f0e9) | Oct 06, 2022 |
| Gigabyte   | H270N-WIFI-CF               | [908c7afaf3](https://linux-hardware.org/?probe=908c7afaf3) | Oct 06, 2022 |
| Gigabyte   | H87-HD3                     | [bc172de17b](https://linux-hardware.org/?probe=bc172de17b) | Oct 02, 2022 |
| ASUSTek    | PRIME H510M-K               | [5bdf95fbdc](https://linux-hardware.org/?probe=5bdf95fbdc) | Oct 02, 2022 |
| Gigabyte   | Z77-DS3H                    | [5de472d6c0](https://linux-hardware.org/?probe=5de472d6c0) | Sep 18, 2022 |
| MSI        | 760GM-P21                   | [172a6c16be](https://linux-hardware.org/?probe=172a6c16be) | Sep 14, 2022 |
| Dell       | 09M8Y8 A01                  | [c719d7f544](https://linux-hardware.org/?probe=c719d7f544) | Sep 11, 2022 |
| ASUSTek    | PRIME Z270-P                | [4a00a1ca0b](https://linux-hardware.org/?probe=4a00a1ca0b) | Sep 10, 2022 |
| Dell       | 0N4YC8 A00                  | [8cd8165ff0](https://linux-hardware.org/?probe=8cd8165ff0) | Sep 02, 2022 |
| ASUSTek    | PRIME H510M-K               | [6fa51d2c4e](https://linux-hardware.org/?probe=6fa51d2c4e) | Aug 31, 2022 |
| Gigabyte   | B75M-D3H                    | [6503feb8b7](https://linux-hardware.org/?probe=6503feb8b7) | Aug 20, 2022 |
| Dell       | 096JG8 A01                  | [6605c5f8ec](https://linux-hardware.org/?probe=6605c5f8ec) | Aug 18, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [a083c7a306](https://linux-hardware.org/?probe=a083c7a306) | Aug 06, 2022 |
| Gigabyte   | Z590I AORUS ULTRA           | [7711256117](https://linux-hardware.org/?probe=7711256117) | Aug 05, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [c810dc35f9](https://linux-hardware.org/?probe=c810dc35f9) | Aug 05, 2022 |
| Unknown    | Intel X79                   | [f013fa996e](https://linux-hardware.org/?probe=f013fa996e) | Aug 04, 2022 |
| Gigabyte   | B365M H                     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| MSI        | MAG B550M BAZOOKA           | [76f5f39b78](https://linux-hardware.org/?probe=76f5f39b78) | Jul 24, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [e311d24fa1](https://linux-hardware.org/?probe=e311d24fa1) | Jul 22, 2022 |
| Huanan     | X99-TF                      | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [aae85dbe4b](https://linux-hardware.org/?probe=aae85dbe4b) | Jul 15, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [628dd44ea9](https://linux-hardware.org/?probe=628dd44ea9) | Jul 15, 2022 |
| Dell       | 0VHWTR A02                  | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| Intel      | DN2820FYB H24582-205        | [147320c75c](https://linux-hardware.org/?probe=147320c75c) | Jul 04, 2022 |
| Acer       | Aspire TC-1660 V:1.1        | [4b65cbc6e6](https://linux-hardware.org/?probe=4b65cbc6e6) | Jul 03, 2022 |
| Fujitsu    | D3161-A1 S26361-D3161-A1    | [f9630aadbb](https://linux-hardware.org/?probe=f9630aadbb) | Jun 26, 2022 |
| Fujitsu    | D3161-A1 S26361-D3161-A1    | [c49e821c3c](https://linux-hardware.org/?probe=c49e821c3c) | Jun 26, 2022 |
| Dell       | 01HYR7 A01                  | [465ffdd126](https://linux-hardware.org/?probe=465ffdd126) | Jun 21, 2022 |
| Huanan     | X99-TF                      | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| MSI        | PRO Z690-A WIFI DDR4        | [da44ae8ded](https://linux-hardware.org/?probe=da44ae8ded) | Jun 15, 2022 |
| Dell       | 01HYR7 A01                  | [4e33fa1a1d](https://linux-hardware.org/?probe=4e33fa1a1d) | Jun 15, 2022 |
| Dell       | 01HYR7 A01                  | [71f9801165](https://linux-hardware.org/?probe=71f9801165) | Jun 15, 2022 |
| MSI        | H510M PRO                   | [b75b035492](https://linux-hardware.org/?probe=b75b035492) | Jun 14, 2022 |
| Intel      | DN2820FYB H24582-205        | [c8b26ae553](https://linux-hardware.org/?probe=c8b26ae553) | Jun 13, 2022 |
| HP         | 1850                        | [0048661597](https://linux-hardware.org/?probe=0048661597) | Jun 12, 2022 |
| Biostar    | H61MLV3                     | [dd47d4aac6](https://linux-hardware.org/?probe=dd47d4aac6) | Jun 08, 2022 |
| Biostar    | H61MLV3                     | [906bb764d6](https://linux-hardware.org/?probe=906bb764d6) | Jun 08, 2022 |
| Huanan     | X99-TF                      | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| ASUSTek    | H110M-K                     | [58566ab4b6](https://linux-hardware.org/?probe=58566ab4b6) | May 30, 2022 |
| MSI        | TRX40 PRO WIFI              | [36ee0ea60c](https://linux-hardware.org/?probe=36ee0ea60c) | May 27, 2022 |
| ASUSTek    | PRIME B460M-K               | [a6dafabf0c](https://linux-hardware.org/?probe=a6dafabf0c) | May 27, 2022 |
| Gigabyte   | H87-HD3                     | [38875f631e](https://linux-hardware.org/?probe=38875f631e) | May 27, 2022 |
| ASUSTek    | H110M-K                     | [9c2c8025ed](https://linux-hardware.org/?probe=9c2c8025ed) | May 26, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [5076d170e0](https://linux-hardware.org/?probe=5076d170e0) | May 24, 2022 |
| ASUSTek    | H110M-K                     | [d0d6870830](https://linux-hardware.org/?probe=d0d6870830) | May 23, 2022 |
| Dell       | 01HYR7 A01                  | [2cd1f7fd5e](https://linux-hardware.org/?probe=2cd1f7fd5e) | May 23, 2022 |
| Gigabyte   | AX370M-Gaming 3-CF          | [830532746e](https://linux-hardware.org/?probe=830532746e) | May 20, 2022 |
| Gigabyte   | AX370M-Gaming 3-CF          | [27289062cb](https://linux-hardware.org/?probe=27289062cb) | May 19, 2022 |
| Medion     | MS-7728                     | [72b22a927a](https://linux-hardware.org/?probe=72b22a927a) | May 19, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [fccf22ebe1](https://linux-hardware.org/?probe=fccf22ebe1) | May 14, 2022 |
| Intel      | DN2820FYB H24582-205        | [5af3adc742](https://linux-hardware.org/?probe=5af3adc742) | May 13, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [58c936ec28](https://linux-hardware.org/?probe=58c936ec28) | May 11, 2022 |
| Intel      | DN2820FYB H24582-205        | [ba9835cb43](https://linux-hardware.org/?probe=ba9835cb43) | May 10, 2022 |
| Dell       | 00V62H A01                  | [fc3604980a](https://linux-hardware.org/?probe=fc3604980a) | May 04, 2022 |
| ASRock     | H370 Pro4                   | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| ASUSTek    | TUF Gaming Z690-PLUS WIF... | [b4d4e52220](https://linux-hardware.org/?probe=b4d4e52220) | Apr 30, 2022 |
| Gigabyte   | 970A-DS3P                   | [1fc7423fdf](https://linux-hardware.org/?probe=1fc7423fdf) | Apr 27, 2022 |
| Dell       | 01HYR7 A01                  | [d7757bf097](https://linux-hardware.org/?probe=d7757bf097) | Apr 27, 2022 |
| ASUSTek    | PRIME B660M-A WIFI D4       | [288bb26592](https://linux-hardware.org/?probe=288bb26592) | Apr 27, 2022 |
| ASUSTek    | PRIME Z690M-PLUS D4         | [f0aea29124](https://linux-hardware.org/?probe=f0aea29124) | Apr 25, 2022 |
| Intel      | DN2820FYB H24582-205        | [fb612cbcd5](https://linux-hardware.org/?probe=fb612cbcd5) | Apr 24, 2022 |
| HP         | 158B                        | [af3f62d027](https://linux-hardware.org/?probe=af3f62d027) | Apr 22, 2022 |
| Gigabyte   | H97-Gaming 3                | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| Intel      | DN2820FYB H24582-205        | [48e5060f20](https://linux-hardware.org/?probe=48e5060f20) | Apr 10, 2022 |
| Dell       | 0YXT71 A01                  | [ff682e31dc](https://linux-hardware.org/?probe=ff682e31dc) | Apr 09, 2022 |
| Intel      | DN2820FYB H24582-205        | [a19db5a006](https://linux-hardware.org/?probe=a19db5a006) | Apr 05, 2022 |
| Acer       | Aspire XC-895 V:1.0         | [2671214482](https://linux-hardware.org/?probe=2671214482) | Apr 01, 2022 |
| HP         | 843B                        | [9c9f43770f](https://linux-hardware.org/?probe=9c9f43770f) | Mar 30, 2022 |
| HP         | 843B                        | [84ae0f086f](https://linux-hardware.org/?probe=84ae0f086f) | Mar 30, 2022 |
| Intel      | DN2820FYB H24582-205        | [87a81b14f0](https://linux-hardware.org/?probe=87a81b14f0) | Mar 25, 2022 |
| MSI        | B560M PRO-VDH               | [b171a344f7](https://linux-hardware.org/?probe=b171a344f7) | Mar 20, 2022 |
| Gigabyte   | Z690 GAMING X DDR4          | [8b31578713](https://linux-hardware.org/?probe=8b31578713) | Mar 18, 2022 |
| ASUSTek    | PRIME H510M-K               | [8a97b4f2d3](https://linux-hardware.org/?probe=8a97b4f2d3) | Mar 09, 2022 |
| ASUSTek    | PRIME Z590M-PLUS            | [4980da013a](https://linux-hardware.org/?probe=4980da013a) | Feb 25, 2022 |
| ASUSTek    | ROG ZENITH II EXTREME AL... | [15efc7df1a](https://linux-hardware.org/?probe=15efc7df1a) | Feb 18, 2022 |
| ASUSTek    | H81M-CS                     | [28b9a2b500](https://linux-hardware.org/?probe=28b9a2b500) | Feb 14, 2022 |
| ASUSTek    | H81M-CS                     | [4f647b985e](https://linux-hardware.org/?probe=4f647b985e) | Feb 12, 2022 |
| Dell       | 0K240Y A04                  | [4342c15fb0](https://linux-hardware.org/?probe=4342c15fb0) | Feb 11, 2022 |
| Gigabyte   | H97-Gaming 3                | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| ECS        | BSWI-DA                     | [2b3dda83e5](https://linux-hardware.org/?probe=2b3dda83e5) | Feb 04, 2022 |
| HP         | 1495                        | [b5cb1ae686](https://linux-hardware.org/?probe=b5cb1ae686) | Feb 03, 2022 |
| ASUSTek    | A88XM-A                     | [a91c7ce0bd](https://linux-hardware.org/?probe=a91c7ce0bd) | Jan 26, 2022 |
| ASUSTek    | A88XM-A                     | [c6c0f18149](https://linux-hardware.org/?probe=c6c0f18149) | Jan 26, 2022 |
| MSI        | H81M-P33                    | [5906cdc7bb](https://linux-hardware.org/?probe=5906cdc7bb) | Jan 24, 2022 |
| Lenovo     | 3098 SDK0E50510 WIN         | [b6b0ace138](https://linux-hardware.org/?probe=b6b0ace138) | Jan 23, 2022 |
| HP         | 1495                        | [f391be3ce3](https://linux-hardware.org/?probe=f391be3ce3) | Jan 14, 2022 |
| ASUSTek    | A88X-PRO                    | [bd78c03781](https://linux-hardware.org/?probe=bd78c03781) | Jan 11, 2022 |
| Dell       | 0CRH6C A00                  | [e6e6da8cf0](https://linux-hardware.org/?probe=e6e6da8cf0) | Jan 07, 2022 |
| Gigabyte   | 990FXA-UD5 R5               | [e80c5b0522](https://linux-hardware.org/?probe=e80c5b0522) | Jan 01, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [7f8ea5d071](https://linux-hardware.org/?probe=7f8ea5d071) | Dec 26, 2021 |
| HP         | 21D0                        | [50548c11b7](https://linux-hardware.org/?probe=50548c11b7) | Dec 04, 2021 |
| ASUSTek    | PRIME Z590-P                | [6490a6beba](https://linux-hardware.org/?probe=6490a6beba) | Nov 29, 2021 |
| ASUSTek    | ROG Maximus XIII HERO       | [36fa5a689f](https://linux-hardware.org/?probe=36fa5a689f) | Nov 28, 2021 |
| ASUSTek    | ROG Maximus Z690 HERO       | [f3e1cfcdab](https://linux-hardware.org/?probe=f3e1cfcdab) | Nov 26, 2021 |
| MSI        | MAG B550M MORTAR WIFI       | [2879c07a24](https://linux-hardware.org/?probe=2879c07a24) | Nov 23, 2021 |
| ASUSTek    | PRIME B360-PLUS             | [8c90375658](https://linux-hardware.org/?probe=8c90375658) | Nov 20, 2021 |
| ASUSTek    | PRIME B360-PLUS             | [a385b829b0](https://linux-hardware.org/?probe=a385b829b0) | Nov 20, 2021 |
| HP         | 339A                        | [a30141ff62](https://linux-hardware.org/?probe=a30141ff62) | Nov 14, 2021 |
| HP         | 339A                        | [46b4ce405b](https://linux-hardware.org/?probe=46b4ce405b) | Nov 13, 2021 |
| Dell       | 0CRH6C A00                  | [0741aa1566](https://linux-hardware.org/?probe=0741aa1566) | Nov 10, 2021 |
| MSI        | MPG X570 GAMING PRO CARB... | [640758abea](https://linux-hardware.org/?probe=640758abea) | Nov 09, 2021 |
| Pegatron   | SKLD4-P1                    | [c4b1d5c274](https://linux-hardware.org/?probe=c4b1d5c274) | Nov 01, 2021 |
| Pegatron   | SKLD4-P1                    | [715a0f960e](https://linux-hardware.org/?probe=715a0f960e) | Nov 01, 2021 |
| ASUSTek    | ROG STRIX Z390-H GAMING     | [1f0c766b1c](https://linux-hardware.org/?probe=1f0c766b1c) | Oct 27, 2021 |
| ASUSTek    | ROG STRIX Z390-H GAMING     | [51c82ff556](https://linux-hardware.org/?probe=51c82ff556) | Oct 24, 2021 |
| ASUSTek    | PRIME Z270-P                | [5b429fd560](https://linux-hardware.org/?probe=5b429fd560) | Oct 23, 2021 |
| Dell       | 0DF42J A00                  | [61ad2cb211](https://linux-hardware.org/?probe=61ad2cb211) | Oct 17, 2021 |
| Dell       | 0DF42J A00                  | [16a04162fc](https://linux-hardware.org/?probe=16a04162fc) | Oct 17, 2021 |
| ASUSTek    | PRIME Z590-P                | [36e45017ff](https://linux-hardware.org/?probe=36e45017ff) | Oct 14, 2021 |
| ASUSTek    | PRIME Z590-P                | [36d8e83f29](https://linux-hardware.org/?probe=36d8e83f29) | Oct 11, 2021 |
| Shuttle    | FH67H                       | [fcf20902e3](https://linux-hardware.org/?probe=fcf20902e3) | Oct 10, 2021 |
| Gigabyte   | H61M-DS2                    | [62bd532ea6](https://linux-hardware.org/?probe=62bd532ea6) | Oct 07, 2021 |
| ASUSTek    | M5A99X EVO R2.0             | [ee15b6dab0](https://linux-hardware.org/?probe=ee15b6dab0) | Oct 07, 2021 |
| ASRock     | H97 Anniversary             | [a73dde5e98](https://linux-hardware.org/?probe=a73dde5e98) | Oct 05, 2021 |
| Dell       | 0XR1GT A00                  | [39257b61d6](https://linux-hardware.org/?probe=39257b61d6) | Oct 05, 2021 |
| Dell       | 0XR1GT A00                  | [b9fef09cfa](https://linux-hardware.org/?probe=b9fef09cfa) | Oct 05, 2021 |
| ASRock     | Z590M-ITX/ax                | [90dbdbed7b](https://linux-hardware.org/?probe=90dbdbed7b) | Oct 04, 2021 |
| HP         | 843B                        | [66ea3388b1](https://linux-hardware.org/?probe=66ea3388b1) | Oct 01, 2021 |
| Gigabyte   | Z370 AORUS ULTRA GAMING-... | [2f27c4c6f0](https://linux-hardware.org/?probe=2f27c4c6f0) | Sep 29, 2021 |
| HP         | 843B                        | [3f53b96972](https://linux-hardware.org/?probe=3f53b96972) | Sep 28, 2021 |
| HP         | 843B                        | [8de340a761](https://linux-hardware.org/?probe=8de340a761) | Sep 28, 2021 |
| Hampoo     | Cherry Trail CR             | [a059116962](https://linux-hardware.org/?probe=a059116962) | Sep 18, 2021 |
| Gigabyte   | B450 AORUS PRO-CF           | [73d4452fc3](https://linux-hardware.org/?probe=73d4452fc3) | Sep 15, 2021 |
| MSI        | MAG B550M BAZOOKA           | [6ddab6806e](https://linux-hardware.org/?probe=6ddab6806e) | Sep 14, 2021 |
| MSI        | MAG B550M BAZOOKA           | [72352cd62b](https://linux-hardware.org/?probe=72352cd62b) | Sep 14, 2021 |
| Gigabyte   | X570 AORUS PRO WIFI         | [a48ec730b7](https://linux-hardware.org/?probe=a48ec730b7) | Sep 13, 2021 |
| ASRock     | B450 Gaming K4              | [356430d4ae](https://linux-hardware.org/?probe=356430d4ae) | Sep 11, 2021 |
| HP         | 1589                        | [0a77f3540b](https://linux-hardware.org/?probe=0a77f3540b) | Sep 08, 2021 |
| ASUSTek    | ROG STRIX X570-I GAMING     | [f8b30bd0cf](https://linux-hardware.org/?probe=f8b30bd0cf) | Sep 04, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [596f8a121f](https://linux-hardware.org/?probe=596f8a121f) | Aug 27, 2021 |
| ASRock     | X300M-STX                   | [246709cb9b](https://linux-hardware.org/?probe=246709cb9b) | Aug 27, 2021 |
| ASUSTek    | ROG STRIX TRX40-E GAMING    | [afd5f8b9b1](https://linux-hardware.org/?probe=afd5f8b9b1) | Aug 27, 2021 |
| ASRock     | AB350 Gaming K4             | [f25ecb1f4d](https://linux-hardware.org/?probe=f25ecb1f4d) | Aug 25, 2021 |
| ASRock     | B550M Pro4                  | [6d4b2d1904](https://linux-hardware.org/?probe=6d4b2d1904) | Aug 19, 2021 |
| Unknown    | Intel X79                   | [1c9353265e](https://linux-hardware.org/?probe=1c9353265e) | Aug 17, 2021 |
| Gigabyte   | Z68MA-D2H-B3                | [bf398306f4](https://linux-hardware.org/?probe=bf398306f4) | Aug 12, 2021 |
| ASRock     | H470M-STX                   | [73dd46e48a](https://linux-hardware.org/?probe=73dd46e48a) | Aug 11, 2021 |
| HP         | 8767 A                      | [5944b600c5](https://linux-hardware.org/?probe=5944b600c5) | Aug 09, 2021 |
| HP         | 8767 A                      | [39a268c1b4](https://linux-hardware.org/?probe=39a268c1b4) | Aug 09, 2021 |
| Gigabyte   | B75M-D3H                    | [dbcb2750e9](https://linux-hardware.org/?probe=dbcb2750e9) | Aug 09, 2021 |
| Foxconn    | 2ABF                        | [605fe34818](https://linux-hardware.org/?probe=605fe34818) | Aug 06, 2021 |
| Foxconn    | 2ABF                        | [236eefa6a3](https://linux-hardware.org/?probe=236eefa6a3) | Aug 06, 2021 |
| HP         | 8767 A                      | [e3b0eb537d](https://linux-hardware.org/?probe=e3b0eb537d) | Aug 04, 2021 |
| HP         | 8767 A                      | [7b9311366d](https://linux-hardware.org/?probe=7b9311366d) | Aug 03, 2021 |
| ASUSTek    | ROG STRIX X570-F GAMING     | [1bcb4e3744](https://linux-hardware.org/?probe=1bcb4e3744) | Aug 03, 2021 |
| ASRock     | H470M-STX                   | [2b06fc5589](https://linux-hardware.org/?probe=2b06fc5589) | Jul 22, 2021 |
| Dell       | 0YXT71 A03                  | [9f6c5866ae](https://linux-hardware.org/?probe=9f6c5866ae) | Jul 20, 2021 |
| Dell       | 0YXT71 A03                  | [74f54d66b2](https://linux-hardware.org/?probe=74f54d66b2) | Jul 20, 2021 |
| MSI        | TRX40 PRO 10G               | [a06646b4da](https://linux-hardware.org/?probe=a06646b4da) | Jul 19, 2021 |
| Gigabyte   | H61M-DS2                    | [eda44f6d7c](https://linux-hardware.org/?probe=eda44f6d7c) | Jul 18, 2021 |
| ASRock     | H470M-STX                   | [929192be0f](https://linux-hardware.org/?probe=929192be0f) | Jul 14, 2021 |
| HP         | 1497                        | [12f471ea0d](https://linux-hardware.org/?probe=12f471ea0d) | Jul 12, 2021 |
| Dell       | 0YXT71 A03                  | [e6d4cd2e90](https://linux-hardware.org/?probe=e6d4cd2e90) | Jul 10, 2021 |
| Lenovo     | ThinkServer TS140           | [ce4504e2f0](https://linux-hardware.org/?probe=ce4504e2f0) | Jul 09, 2021 |
| Lenovo     | ThinkServer TS140           | [927c1f1b83](https://linux-hardware.org/?probe=927c1f1b83) | Jul 09, 2021 |
| Intel      | DQ77MK AAG39642-500         | [e185c99124](https://linux-hardware.org/?probe=e185c99124) | Jul 02, 2021 |
| ASUSTek    | H110M-A/M.2                 | [fd2d0c3aea](https://linux-hardware.org/?probe=fd2d0c3aea) | Jun 25, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | [913c59fc58](https://linux-hardware.org/?probe=913c59fc58) | Jun 21, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | [617842a492](https://linux-hardware.org/?probe=617842a492) | Jun 21, 2021 |
| Unknown    | Unknown                     | [489dc53e4d](https://linux-hardware.org/?probe=489dc53e4d) | Jun 20, 2021 |
| Unknown    | Unknown                     | [077a1849dd](https://linux-hardware.org/?probe=077a1849dd) | Jun 20, 2021 |
| ASUSTek    | ROG ZENITH II EXTREME AL... | [70c81260fe](https://linux-hardware.org/?probe=70c81260fe) | Jun 18, 2021 |
| ASUSTek    | ROG ZENITH II EXTREME AL... | [90f62d9ea2](https://linux-hardware.org/?probe=90f62d9ea2) | Jun 18, 2021 |
| ASUSTek    | B85M-G                      | [f2d7281431](https://linux-hardware.org/?probe=f2d7281431) | Jun 13, 2021 |
| Unknown    | Unknown                     | [fbfc225ce7](https://linux-hardware.org/?probe=fbfc225ce7) | Jun 07, 2021 |
| Unknown    | Unknown                     | [6bad6316a0](https://linux-hardware.org/?probe=6bad6316a0) | Jun 07, 2021 |
| MSI        | Z590 PRO WIFI               | [35b29f391f](https://linux-hardware.org/?probe=35b29f391f) | Jun 01, 2021 |
| ASRock     | B550M Pro4                  | [d5f17bf23f](https://linux-hardware.org/?probe=d5f17bf23f) | Jun 01, 2021 |
| ASUSTek    | TUF Gaming B460-PRO         | [93390ed697](https://linux-hardware.org/?probe=93390ed697) | May 29, 2021 |
| Gigabyte   | Z490I AORUS ULTRA           | [57a08ffceb](https://linux-hardware.org/?probe=57a08ffceb) | May 28, 2021 |
| MSI        | B450 TOMAHAWK               | [616f23126b](https://linux-hardware.org/?probe=616f23126b) | May 22, 2021 |
| ASUSTek    | PRIME Z390M-PLUS            | [8748a193b6](https://linux-hardware.org/?probe=8748a193b6) | May 19, 2021 |
| Gigabyte   | B365M D2V                   | [887f18105e](https://linux-hardware.org/?probe=887f18105e) | May 17, 2021 |
| Gigabyte   | B365M D2V                   | [644431aa47](https://linux-hardware.org/?probe=644431aa47) | May 17, 2021 |
| Unknown    | Unknown                     | [b7dc673e5c](https://linux-hardware.org/?probe=b7dc673e5c) | May 07, 2021 |
| Unknown    | Unknown                     | [9936062c88](https://linux-hardware.org/?probe=9936062c88) | May 07, 2021 |
| AZW        | AP35                        | [ac530e40ad](https://linux-hardware.org/?probe=ac530e40ad) | May 05, 2021 |
| Biostar    | B360MHD PRO2                | [88839213ee](https://linux-hardware.org/?probe=88839213ee) | May 03, 2021 |
| AZW        | AP35                        | [867223f2cf](https://linux-hardware.org/?probe=867223f2cf) | May 02, 2021 |
| AZW        | AP35                        | [45487d6ab8](https://linux-hardware.org/?probe=45487d6ab8) | May 02, 2021 |
| Acer       | Aspire XC-885 V:1.1         | [5c8af3a6f6](https://linux-hardware.org/?probe=5c8af3a6f6) | Apr 26, 2021 |
| Acer       | Aspire TC-885 V:1.1         | [a0753ae0f8](https://linux-hardware.org/?probe=a0753ae0f8) | Apr 26, 2021 |
| Gigabyte   | Z97X-UD3H-CF                | [c941a697c2](https://linux-hardware.org/?probe=c941a697c2) | Apr 22, 2021 |
| Acer       | Aspire XC-885 V:1.1         | [6d786229f3](https://linux-hardware.org/?probe=6d786229f3) | Apr 21, 2021 |
| Acer       | Aspire XC-885 V:1.1         | [d659fa1ad2](https://linux-hardware.org/?probe=d659fa1ad2) | Apr 21, 2021 |
| ASUSTek    | F2A85-M PRO                 | [285fc011a7](https://linux-hardware.org/?probe=285fc011a7) | Apr 18, 2021 |
| ASUSTek    | F2A85-M PRO                 | [24cda07874](https://linux-hardware.org/?probe=24cda07874) | Apr 18, 2021 |
| Intel      | B75                         | [b87d332f6c](https://linux-hardware.org/?probe=b87d332f6c) | Apr 17, 2021 |
| Gigabyte   | B85M-D3H                    | [a16e9aea15](https://linux-hardware.org/?probe=a16e9aea15) | Apr 17, 2021 |
| Lenovo     | SHARKBAY SDK0E50510 WIN     | [4849762adf](https://linux-hardware.org/?probe=4849762adf) | Apr 14, 2021 |
| Unknown    | Unknown                     | [270515effb](https://linux-hardware.org/?probe=270515effb) | Apr 13, 2021 |
| ASUSTek    | X99-E WS                    | [4e03caf1b2](https://linux-hardware.org/?probe=4e03caf1b2) | Apr 13, 2021 |
| AZW        | AP35                        | [d9275d56b3](https://linux-hardware.org/?probe=d9275d56b3) | Apr 02, 2021 |
| HP         | 18E4                        | [d97f86a6f8](https://linux-hardware.org/?probe=d97f86a6f8) | Mar 26, 2021 |
| Unknown    | Unknown                     | [f99039c20b](https://linux-hardware.org/?probe=f99039c20b) | Mar 20, 2021 |
| Unknown    | Unknown                     | [3c469f8c33](https://linux-hardware.org/?probe=3c469f8c33) | Mar 20, 2021 |
| GMK        | NucBox                      | [d9c312187f](https://linux-hardware.org/?probe=d9c312187f) | Mar 12, 2021 |
| Intel      | B75                         | [6a917fae14](https://linux-hardware.org/?probe=6a917fae14) | Mar 08, 2021 |
| Gigabyte   | B550 AORUS ELITE V2         | [6093659817](https://linux-hardware.org/?probe=6093659817) | Mar 07, 2021 |
| Gigabyte   | B450M DS3H-CF               | [9161109236](https://linux-hardware.org/?probe=9161109236) | Mar 06, 2021 |
| MAXSUN     | TA300 Series                | [efbd8e2910](https://linux-hardware.org/?probe=efbd8e2910) | Mar 06, 2021 |
| HP         | 2AF7                        | [32795fb797](https://linux-hardware.org/?probe=32795fb797) | Mar 04, 2021 |
| Intel      | B75                         | [55e99d4728](https://linux-hardware.org/?probe=55e99d4728) | Mar 01, 2021 |
| ASUSTek    | B85M-G                      | [cd9d36e77b](https://linux-hardware.org/?probe=cd9d36e77b) | Feb 28, 2021 |
| MSI        | H110M PRO-VD                | [07963851fe](https://linux-hardware.org/?probe=07963851fe) | Feb 26, 2021 |
| ASUSTek    | H81I-PLUS                   | [b6c7d98eb2](https://linux-hardware.org/?probe=b6c7d98eb2) | Feb 23, 2021 |
| Gigabyte   | Z490 AORUS XTREME           | [78d71ec4a3](https://linux-hardware.org/?probe=78d71ec4a3) | Feb 22, 2021 |
| Gigabyte   | Z490 AORUS XTREME           | [cfc160c199](https://linux-hardware.org/?probe=cfc160c199) | Feb 22, 2021 |
| Dell       | 048DY8 A01                  | [7d749b3ecc](https://linux-hardware.org/?probe=7d749b3ecc) | Feb 21, 2021 |
| iEi        | B202 V1.0                   | [3dce687709](https://linux-hardware.org/?probe=3dce687709) | Feb 14, 2021 |
| Unknown    | Unknown                     | [0730e68b60](https://linux-hardware.org/?probe=0730e68b60) | Feb 13, 2021 |
| Unknown    | Unknown                     | [5c52adac31](https://linux-hardware.org/?probe=5c52adac31) | Feb 09, 2021 |
| Unknown    | Unknown                     | [fb9143648d](https://linux-hardware.org/?probe=fb9143648d) | Feb 09, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [414df2922d](https://linux-hardware.org/?probe=414df2922d) | Feb 07, 2021 |
| MSI        | B360 GAMING PLUS            | [f409735b4a](https://linux-hardware.org/?probe=f409735b4a) | Feb 01, 2021 |
| Gigabyte   | X570 AORUS MASTER           | [928c36893b](https://linux-hardware.org/?probe=928c36893b) | Jan 29, 2021 |
| ASUSTek    | ROG STRIX X370-F GAMING     | [8d455bbc9b](https://linux-hardware.org/?probe=8d455bbc9b) | Jan 20, 2021 |
| ASUSTek    | ROG STRIX Z390-H GAMING     | [a298dd061d](https://linux-hardware.org/?probe=a298dd061d) | Jan 16, 2021 |
| Pegatron   | 2AD5                        | [e289a86560](https://linux-hardware.org/?probe=e289a86560) | Jan 16, 2021 |
| ASUSTek    | AM1I-A                      | [ae008b3ccf](https://linux-hardware.org/?probe=ae008b3ccf) | Jan 11, 2021 |
| Gigabyte   | A320M-S2H-CF                | [ee3769c94b](https://linux-hardware.org/?probe=ee3769c94b) | Jan 11, 2021 |
| ASUSTek    | H110M-E/M.2                 | [cd5fa09ba3](https://linux-hardware.org/?probe=cd5fa09ba3) | Jan 07, 2021 |
| Gigabyte   | X570 AORUS PRO WIFI         | [9f873d681e](https://linux-hardware.org/?probe=9f873d681e) | Jan 07, 2021 |
| Gigabyte   | X570 AORUS PRO WIFI         | [b7f5733608](https://linux-hardware.org/?probe=b7f5733608) | Jan 06, 2021 |
| Lenovo     | SHARKBAY NOK                | [4cf58c8a8c](https://linux-hardware.org/?probe=4cf58c8a8c) | Jan 02, 2021 |
| MSI        | A320M-A PRO                 | [0edf382cee](https://linux-hardware.org/?probe=0edf382cee) | Dec 25, 2020 |
| MSI        | A320M-A PRO                 | [550ec69d3e](https://linux-hardware.org/?probe=550ec69d3e) | Dec 25, 2020 |
| ASUSTek    | ROG Maximus XII FORMULA     | [656256db83](https://linux-hardware.org/?probe=656256db83) | Dec 22, 2020 |
| Gigabyte   | H310M H                     | [dfa5c13a96](https://linux-hardware.org/?probe=dfa5c13a96) | Dec 22, 2020 |
| HP         | 8459                        | [b5eb47ab31](https://linux-hardware.org/?probe=b5eb47ab31) | Dec 19, 2020 |
| MSI        | B450 TOMAHAWK MAX           | [1842fb451a](https://linux-hardware.org/?probe=1842fb451a) | Dec 15, 2020 |
| ASRock     | TRX40 Creator               | [dd14b01c46](https://linux-hardware.org/?probe=dd14b01c46) | Dec 13, 2020 |
| ASUSTek    | PRIME A320M-R               | [653c485c8d](https://linux-hardware.org/?probe=653c485c8d) | Dec 08, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [c381251f06](https://linux-hardware.org/?probe=c381251f06) | Dec 08, 2020 |
| HP         | 8459                        | [3755e58561](https://linux-hardware.org/?probe=3755e58561) | Dec 03, 2020 |
| Gigabyte   | Z370 AORUS Gaming 5-CF      | [af0867c0cd](https://linux-hardware.org/?probe=af0867c0cd) | Nov 28, 2020 |
| Gigabyte   | X570 AORUS PRO              | [e9cff0432f](https://linux-hardware.org/?probe=e9cff0432f) | Nov 24, 2020 |
| Unknown    | Unknown                     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown    | Unknown                     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| ASUSTek    | P8Z77-I DELUXE              | [ab463224ae](https://linux-hardware.org/?probe=ab463224ae) | Nov 02, 2020 |
| iEi        | B202 V1.0                   | [ad705b0098](https://linux-hardware.org/?probe=ad705b0098) | Oct 29, 2020 |
| ASUSTek    | ProArt Z490-CREATOR 10G     | [511ec72263](https://linux-hardware.org/?probe=511ec72263) | Oct 27, 2020 |
| ASUSTek    | B85M-K                      | [593f27d247](https://linux-hardware.org/?probe=593f27d247) | Oct 19, 2020 |
| ASUSTek    | Z87-PLUS                    | [40a7a6d4ae](https://linux-hardware.org/?probe=40a7a6d4ae) | Oct 13, 2020 |
| ASUSTek    | Z87-PLUS                    | [2b044d627b](https://linux-hardware.org/?probe=2b044d627b) | Oct 13, 2020 |
| Gigabyte   | G1.Sniper Z97               | [204e4aff9e](https://linux-hardware.org/?probe=204e4aff9e) | Oct 13, 2020 |
| ASUSTek    | TUF Gaming X570-PLUS        | [eed7ced527](https://linux-hardware.org/?probe=eed7ced527) | Oct 11, 2020 |
| ASUSTek    | TUF Gaming X570-PLUS        | [9c37b1dfff](https://linux-hardware.org/?probe=9c37b1dfff) | Oct 11, 2020 |
| Gigabyte   | X570 AORUS ELITE            | [968e3c668b](https://linux-hardware.org/?probe=968e3c668b) | Oct 08, 2020 |
| ASUSTek    | ROG STRIX Z390-E GAMING     | [7f79b48532](https://linux-hardware.org/?probe=7f79b48532) | Sep 30, 2020 |
| Gigabyte   | Z390 UD                     | [1b0a93d73d](https://linux-hardware.org/?probe=1b0a93d73d) | Sep 29, 2020 |
| ASUSTek    | PRIME TRX40-PRO             | [cf1b29d15f](https://linux-hardware.org/?probe=cf1b29d15f) | Sep 24, 2020 |
| ASUSTek    | ROG Maximus XII FORMULA     | [5152450400](https://linux-hardware.org/?probe=5152450400) | Sep 19, 2020 |
| HP         | 82F2 A01                    | [f01ac2045a](https://linux-hardware.org/?probe=f01ac2045a) | Sep 05, 2020 |
| Acer       | Aspire TC-885G V:1.1        | [4053fd88a8](https://linux-hardware.org/?probe=4053fd88a8) | Aug 29, 2020 |
| ASUSTek    | M5A78L LE                   | [af37124d62](https://linux-hardware.org/?probe=af37124d62) | Aug 28, 2020 |
| ASRock     | TRX40 Taichi                | [dae871210e](https://linux-hardware.org/?probe=dae871210e) | Aug 23, 2020 |
| ASRock     | TRX40 Taichi                | [d5e4a3484b](https://linux-hardware.org/?probe=d5e4a3484b) | Aug 23, 2020 |
| ASRock     | TRX40 Creator               | [97fdcce42e](https://linux-hardware.org/?probe=97fdcce42e) | Aug 22, 2020 |
| ASRock     | H410M-HDV/M.2               | [8c6f947041](https://linux-hardware.org/?probe=8c6f947041) | Aug 16, 2020 |
| HP         | 802E                        | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP         | 802E                        | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP         | 802E                        | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| ASRock     | TRX40 Creator               | [3e4a555186](https://linux-hardware.org/?probe=3e4a555186) | Aug 10, 2020 |
| HP         | 8459                        | [c0c5068e12](https://linux-hardware.org/?probe=c0c5068e12) | Aug 08, 2020 |
| ASRock     | 970A-G                      | [9fcf5d6433](https://linux-hardware.org/?probe=9fcf5d6433) | Aug 08, 2020 |
| ASRock     | A300M-STX                   | [b90097a987](https://linux-hardware.org/?probe=b90097a987) | Aug 03, 2020 |
| ASUSTek    | Maximus VIII IMPACT         | [eba5d19e5f](https://linux-hardware.org/?probe=eba5d19e5f) | Aug 01, 2020 |
| Dell       | 0773VG A01                  | [e423142ac2](https://linux-hardware.org/?probe=e423142ac2) | Jul 28, 2020 |
| ASUSTek    | PRIME Z370-P                | [f526c1ab74](https://linux-hardware.org/?probe=f526c1ab74) | Jul 24, 2020 |
| HP         | 8425                        | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| HP         | 1497                        | [114fc860bc](https://linux-hardware.org/?probe=114fc860bc) | Jul 06, 2020 |
| ASUSTek    | PRIME B450M-A               | [5b37542530](https://linux-hardware.org/?probe=5b37542530) | Jul 03, 2020 |
| MSI        | MPG X570 GAMING PLUS        | [77345420dd](https://linux-hardware.org/?probe=77345420dd) | Jun 30, 2020 |
| Gigabyte   | Z390 AORUS ULTRA-CF         | [f61fb65566](https://linux-hardware.org/?probe=f61fb65566) | Jun 27, 2020 |
| ASRock     | X99 Extreme11               | [fa8d061f8f](https://linux-hardware.org/?probe=fa8d061f8f) | Jun 27, 2020 |
| ASRock     | X99 Extreme11               | [2f6eabe3fc](https://linux-hardware.org/?probe=2f6eabe3fc) | Jun 27, 2020 |
| Foxconn    | 2ABF                        | [ad7aca7798](https://linux-hardware.org/?probe=ad7aca7798) | Jun 25, 2020 |
| Intel      | X79 INTEL(INTEL Xeon E5/... | [79099f1375](https://linux-hardware.org/?probe=79099f1375) | Jun 18, 2020 |
| ASUSTek    | TUF Z370-PLUS GAMING II     | [44fc6290e2](https://linux-hardware.org/?probe=44fc6290e2) | Jun 17, 2020 |
| Dell       | 00V62H A01                  | [a7e9be3818](https://linux-hardware.org/?probe=a7e9be3818) | Jun 16, 2020 |
| MSI        | Z370 GAMING PLUS            | [b3ae454f4d](https://linux-hardware.org/?probe=b3ae454f4d) | Jun 07, 2020 |
| Lenovo     | 30C9 SDK0J40697 WIN 3305... | [0bd408c7b1](https://linux-hardware.org/?probe=0bd408c7b1) | Jun 03, 2020 |
| Gigabyte   | H110M-S2H-CF                | [4d40264618](https://linux-hardware.org/?probe=4d40264618) | Jun 01, 2020 |
| ASRock     | AB350 Pro4                  | [a83a3c451a](https://linux-hardware.org/?probe=a83a3c451a) | May 25, 2020 |
| Gigabyte   | TRX40 DESIGNARE             | [2732c1d769](https://linux-hardware.org/?probe=2732c1d769) | May 22, 2020 |
| ASUSTek    | Z97-A                       | [32fc505cab](https://linux-hardware.org/?probe=32fc505cab) | May 17, 2020 |
| MSI        | B450 TOMAHAWK MAX           | [db8887bb7a](https://linux-hardware.org/?probe=db8887bb7a) | May 13, 2020 |
| Intel      | X79 V2.4E                   | [c95d31e867](https://linux-hardware.org/?probe=c95d31e867) | May 12, 2020 |
| Gigabyte   | H77M-D3H                    | [de237bc9f1](https://linux-hardware.org/?probe=de237bc9f1) | May 12, 2020 |
| ASUSTek    | ROG ZENITH II EXTREME       | [f5152b2ec1](https://linux-hardware.org/?probe=f5152b2ec1) | May 07, 2020 |
| MSI        | Z370 TOMAHAWK               | [9ef1c24681](https://linux-hardware.org/?probe=9ef1c24681) | May 06, 2020 |
| ASUSTek    | C8HM70-I/HDMI               | [1bce8d72b4](https://linux-hardware.org/?probe=1bce8d72b4) | May 04, 2020 |
| ASUSTek    | P8P67 LE                    | [2701a098f7](https://linux-hardware.org/?probe=2701a098f7) | May 02, 2020 |
| ASUSTek    | PRIME H270-PRO              | [f2de5c3a83](https://linux-hardware.org/?probe=f2de5c3a83) | May 02, 2020 |
| HP         | 0AECh D                     | [a1b7a080a8](https://linux-hardware.org/?probe=a1b7a080a8) | May 02, 2020 |
| HP         | 0AECh D                     | [80d5a1434e](https://linux-hardware.org/?probe=80d5a1434e) | May 01, 2020 |
| MSI        | X470 GAMING M7 AC           | [66b75d7bff](https://linux-hardware.org/?probe=66b75d7bff) | Apr 28, 2020 |
| ASUSTek    | PRIME Z370-P                | [7dfa763f99](https://linux-hardware.org/?probe=7dfa763f99) | Apr 28, 2020 |
| ASRock     | B450M-HDV R4.0              | [1ba348dd3d](https://linux-hardware.org/?probe=1ba348dd3d) | Apr 18, 2020 |
| Dell       | 0Y5DDC A00                  | [a607ebd7d9](https://linux-hardware.org/?probe=a607ebd7d9) | Apr 15, 2020 |
| HP         | 8459                        | [c241c2fa75](https://linux-hardware.org/?probe=c241c2fa75) | Apr 13, 2020 |
| ASUSTek    | PRIME Z370-P                | [ad5a70ea5b](https://linux-hardware.org/?probe=ad5a70ea5b) | Apr 07, 2020 |
| ASUSTek    | TUF Z390-PRO GAMING         | [de0d4452e5](https://linux-hardware.org/?probe=de0d4452e5) | Apr 06, 2020 |
| ASRock     | Q1900M                      | [11c1c6b498](https://linux-hardware.org/?probe=11c1c6b498) | Apr 06, 2020 |
| Gigabyte   | F2A68HM-HD2                 | [1013dc1d5f](https://linux-hardware.org/?probe=1013dc1d5f) | Apr 06, 2020 |
| Gigabyte   | F2A68HM-HD2                 | [3c115dc0b0](https://linux-hardware.org/?probe=3c115dc0b0) | Apr 06, 2020 |
| MSI        | X470 GAMING M7 AC           | [47f06299cb](https://linux-hardware.org/?probe=47f06299cb) | Apr 04, 2020 |
| Gigabyte   | Z97X-UD3H-CF                | [03662c05b2](https://linux-hardware.org/?probe=03662c05b2) | Apr 04, 2020 |
| ASUSTek    | PRIME Z390-A                | [cc3bde6b84](https://linux-hardware.org/?probe=cc3bde6b84) | Mar 30, 2020 |
| ASUSTek    | ROG Maximus X HERO          | [581217af06](https://linux-hardware.org/?probe=581217af06) | Mar 26, 2020 |
| ASUSTek    | ROG Maximus X HERO          | [e9424adfcc](https://linux-hardware.org/?probe=e9424adfcc) | Mar 26, 2020 |
| ASUSTek    | PRIME Z390-A                | [edd441d5a3](https://linux-hardware.org/?probe=edd441d5a3) | Mar 25, 2020 |
| ASUSTek    | PRIME B350M-A               | [0b821be62a](https://linux-hardware.org/?probe=0b821be62a) | Mar 23, 2020 |
| ASUSTek    | PRIME Z390-A                | [f2eec9742e](https://linux-hardware.org/?probe=f2eec9742e) | Mar 20, 2020 |
| ASUSTek    | M5A97 R2.0                  | [ce917a03e4](https://linux-hardware.org/?probe=ce917a03e4) | Mar 18, 2020 |
| ASUSTek    | TUF B450M-PRO GAMING        | [bdbb9118bc](https://linux-hardware.org/?probe=bdbb9118bc) | Mar 15, 2020 |
| Gigabyte   | B450 AORUS M                | [3c6e4bca36](https://linux-hardware.org/?probe=3c6e4bca36) | Mar 13, 2020 |
| Acer       | Aspire X1935                | [bbfb5f1f3e](https://linux-hardware.org/?probe=bbfb5f1f3e) | Mar 05, 2020 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [7ea9f32ae7](https://linux-hardware.org/?probe=7ea9f32ae7) | Mar 04, 2020 |
| Supermicro | X10SRA                      | [47e52c7012](https://linux-hardware.org/?probe=47e52c7012) | Mar 03, 2020 |
| ASRock     | H81M-VG4 R2.0               | [3708a45377](https://linux-hardware.org/?probe=3708a45377) | Mar 03, 2020 |
| ASUSTek    | ROG STRIX Z390-I GAMING     | [267507fb84](https://linux-hardware.org/?probe=267507fb84) | Mar 01, 2020 |
| ASUSTek    | GL12CM                      | [f094f68a37](https://linux-hardware.org/?probe=f094f68a37) | Mar 01, 2020 |
| ASUSTek    | Z97-A                       | [8bc7b7979a](https://linux-hardware.org/?probe=8bc7b7979a) | Mar 01, 2020 |
| Dell       | 0PGKWF A01                  | [cbbf7e3478](https://linux-hardware.org/?probe=cbbf7e3478) | Feb 29, 2020 |
| Gigabyte   | J1800M-D3P                  | [803029cff0](https://linux-hardware.org/?probe=803029cff0) | Feb 28, 2020 |
| Gigabyte   | J1800M-D3P                  | [54abb6e16a](https://linux-hardware.org/?probe=54abb6e16a) | Feb 28, 2020 |
| Dell       | 0K240Y A04                  | [f939a0998f](https://linux-hardware.org/?probe=f939a0998f) | Feb 27, 2020 |
| Dell       | 0K240Y A04                  | [2499cafa99](https://linux-hardware.org/?probe=2499cafa99) | Feb 27, 2020 |
| Gigabyte   | J1800M-D3P                  | [8adc425674](https://linux-hardware.org/?probe=8adc425674) | Feb 27, 2020 |
| Gigabyte   | Z170-HD3P-CF                | [41cd90fda5](https://linux-hardware.org/?probe=41cd90fda5) | Feb 26, 2020 |
| Gigabyte   | Z170-HD3P-CF                | [bd66d1fdd8](https://linux-hardware.org/?probe=bd66d1fdd8) | Feb 26, 2020 |
| Dell       | 0X9M3X A04                  | [21538fb1e9](https://linux-hardware.org/?probe=21538fb1e9) | Feb 25, 2020 |
| HP         | 1497                        | [fe95ac27b8](https://linux-hardware.org/?probe=fe95ac27b8) | Feb 24, 2020 |
| MSI        | Z97A GAMING 7               | [1befa15987](https://linux-hardware.org/?probe=1befa15987) | Feb 23, 2020 |
| MSI        | Z97A GAMING 7               | [f0924024d4](https://linux-hardware.org/?probe=f0924024d4) | Feb 23, 2020 |
| MSI        | Z97A GAMING 7               | [532b9c71a9](https://linux-hardware.org/?probe=532b9c71a9) | Feb 23, 2020 |
| Intel      | X99 V102                    | [d05866e3c1](https://linux-hardware.org/?probe=d05866e3c1) | Feb 21, 2020 |
| Intel      | X99 V102                    | [9b81b3499d](https://linux-hardware.org/?probe=9b81b3499d) | Feb 21, 2020 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [30976e85b2](https://linux-hardware.org/?probe=30976e85b2) | Feb 21, 2020 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [958869cf0f](https://linux-hardware.org/?probe=958869cf0f) | Feb 21, 2020 |
| ASRock     | Z170 Gaming K4              | [fb5c561a90](https://linux-hardware.org/?probe=fb5c561a90) | Feb 21, 2020 |
| Gigabyte   | X79-UD3                     | [f91e107db3](https://linux-hardware.org/?probe=f91e107db3) | Feb 18, 2020 |
| ASUSTek    | Z170-A                      | [1ef6222ab2](https://linux-hardware.org/?probe=1ef6222ab2) | Feb 16, 2020 |
| ASUSTek    | Z170-A                      | [c96f9af8a3](https://linux-hardware.org/?probe=c96f9af8a3) | Feb 16, 2020 |
| Dell       | 0DF42J A00                  | [315459c675](https://linux-hardware.org/?probe=315459c675) | Feb 16, 2020 |
| ASRock     | X399 Taichi                 | [ceecf1b739](https://linux-hardware.org/?probe=ceecf1b739) | Feb 15, 2020 |
| Biostar    | TB85                        | [ee5bd25897](https://linux-hardware.org/?probe=ee5bd25897) | Feb 13, 2020 |
| Huanan     | X99-F8                      | [9a66d849b3](https://linux-hardware.org/?probe=9a66d849b3) | Feb 13, 2020 |
| ASRock     | Z390 Phantom Gaming-ITX/... | [f320068ea4](https://linux-hardware.org/?probe=f320068ea4) | Feb 13, 2020 |
| Gigabyte   | Z390 AORUS MASTER-CF        | [a708959c5d](https://linux-hardware.org/?probe=a708959c5d) | Feb 12, 2020 |
| Gigabyte   | Z390 AORUS MASTER-CF        | [8f09b5d8a7](https://linux-hardware.org/?probe=8f09b5d8a7) | Feb 12, 2020 |
| MSI        | Z370 SLI PLUS               | [c76ba1a6d0](https://linux-hardware.org/?probe=c76ba1a6d0) | Feb 08, 2020 |
| Intel      | DH61BE AAG14062-204         | [7f2b3ed726](https://linux-hardware.org/?probe=7f2b3ed726) | Feb 08, 2020 |
| Intel      | DH61BE AAG14062-204         | [61ae489c00](https://linux-hardware.org/?probe=61ae489c00) | Feb 08, 2020 |
| Acer       | Aspire TC-885G V:1.1        | [13f5754871](https://linux-hardware.org/?probe=13f5754871) | Feb 08, 2020 |
| ASRock     | B150M-HDV                   | [c08c6d0574](https://linux-hardware.org/?probe=c08c6d0574) | Feb 08, 2020 |
| Shuttle    | FS81                        | [93c00d64e6](https://linux-hardware.org/?probe=93c00d64e6) | Feb 07, 2020 |
| ASUSTek    | PRIME B450M-A               | [f62741949a](https://linux-hardware.org/?probe=f62741949a) | Feb 07, 2020 |
| Dell       | 0PGKWF A01                  | [bee05c475f](https://linux-hardware.org/?probe=bee05c475f) | Jan 25, 2020 |
| HP         | 82F2                        | [74dceabd1d](https://linux-hardware.org/?probe=74dceabd1d) | Jan 24, 2020 |
| Dell       | 0PGKWF A01                  | [a01daae028](https://linux-hardware.org/?probe=a01daae028) | Jan 24, 2020 |
| Dell       | 0PGKWF A01                  | [c56b762cab](https://linux-hardware.org/?probe=c56b762cab) | Jan 22, 2020 |
| Acer       | Aspire TC-780               | [409a76b0f1](https://linux-hardware.org/?probe=409a76b0f1) | Jan 21, 2020 |
| Acer       | Aspire TC-780               | [dcb51adf05](https://linux-hardware.org/?probe=dcb51adf05) | Jan 21, 2020 |
| Gigabyte   | A320M-S2H V2-CF             | [7bf277e620](https://linux-hardware.org/?probe=7bf277e620) | Jan 18, 2020 |
| Gigabyte   | A320M-S2H V2-CF             | [065a2d2ef5](https://linux-hardware.org/?probe=065a2d2ef5) | Jan 18, 2020 |
| ASUSTek    | PRIME H310M-R R2.0          | [cb5aa49150](https://linux-hardware.org/?probe=cb5aa49150) | Jan 16, 2020 |
| Dell       | 0773VG A01                  | [c4bfa83ca3](https://linux-hardware.org/?probe=c4bfa83ca3) | Jan 15, 2020 |
| ASUSTek    | G11DF                       | [5e1039a3a1](https://linux-hardware.org/?probe=5e1039a3a1) | Jan 08, 2020 |
| ASUSTek    | G11DF                       | [a76b1d2af6](https://linux-hardware.org/?probe=a76b1d2af6) | Jan 08, 2020 |
| ASUSTek    | B85M-G                      | [302a15feb4](https://linux-hardware.org/?probe=302a15feb4) | Jan 02, 2020 |
| Dell       | 0PGKWF A01                  | [3b48d2db7d](https://linux-hardware.org/?probe=3b48d2db7d) | Jan 02, 2020 |
| Gigabyte   | F2A88XM-HD3                 | [328148394f](https://linux-hardware.org/?probe=328148394f) | Dec 19, 2019 |
| Gigabyte   | F2A88XM-HD3                 | [a526c59a72](https://linux-hardware.org/?probe=a526c59a72) | Dec 19, 2019 |
| Dell       | 0PGKWF A01                  | [e6ff0bd804](https://linux-hardware.org/?probe=e6ff0bd804) | Dec 18, 2019 |
| ASUSTek    | PRIME B250M-A               | [e8674bffb4](https://linux-hardware.org/?probe=e8674bffb4) | Dec 14, 2019 |
| ASUSTek    | Z97-C                       | [d9048f1428](https://linux-hardware.org/?probe=d9048f1428) | Dec 13, 2019 |
| Lenovo     | SHARKBAY 0B98401 WIN        | [c7d04d3d16](https://linux-hardware.org/?probe=c7d04d3d16) | Dec 05, 2019 |
| Gigabyte   | F2A68HM-H                   | [b9efdbd9ea](https://linux-hardware.org/?probe=b9efdbd9ea) | Nov 19, 2019 |
| Dell       | 0PGKWF A01                  | [e0d9d87400](https://linux-hardware.org/?probe=e0d9d87400) | Nov 14, 2019 |
| Dell       | 0PGKWF A01                  | [0db06e6c68](https://linux-hardware.org/?probe=0db06e6c68) | Nov 14, 2019 |
| Dell       | 0PGKWF A01                  | [d9cd3df5f4](https://linux-hardware.org/?probe=d9cd3df5f4) | Nov 13, 2019 |
| iEi        | B202 V1.0                   | [16699afe19](https://linux-hardware.org/?probe=16699afe19) | Nov 13, 2019 |
| ASUSTek    | M5A97 R2.0                  | [e4e6ac6035](https://linux-hardware.org/?probe=e4e6ac6035) | Nov 10, 2019 |
| ASUSTek    | M5A97 R2.0                  | [14b215a494](https://linux-hardware.org/?probe=14b215a494) | Nov 10, 2019 |
| Gigabyte   | H77-D3H                     | [ad9349bbff](https://linux-hardware.org/?probe=ad9349bbff) | Nov 10, 2019 |
| ASRock     | H110M-DGS R3.0              | [78d267783c](https://linux-hardware.org/?probe=78d267783c) | Nov 06, 2019 |
| ASUSTek    | Z170-A                      | [7766dda677](https://linux-hardware.org/?probe=7766dda677) | Nov 04, 2019 |
| ASUSTek    | Z170-A                      | [15aaac44b3](https://linux-hardware.org/?probe=15aaac44b3) | Nov 04, 2019 |
| iEi        | B202 V1.0                   | [bffdad4a05](https://linux-hardware.org/?probe=bffdad4a05) | Oct 26, 2019 |
| ASRock     | IMB-170                     | [aeee40220b](https://linux-hardware.org/?probe=aeee40220b) | Oct 17, 2019 |
| ASUSTek    | H81M-PLUS                   | [dab482c9fe](https://linux-hardware.org/?probe=dab482c9fe) | Oct 17, 2019 |
| MSI        | Z390-A PRO                  | [7b13483e17](https://linux-hardware.org/?probe=7b13483e17) | Oct 14, 2019 |
| ASRock     | H110M-DGS                   | [724931a3b9](https://linux-hardware.org/?probe=724931a3b9) | Oct 14, 2019 |
| ASRock     | Z77 Pro4-M                  | [7291533e89](https://linux-hardware.org/?probe=7291533e89) | Oct 01, 2019 |
| MSI        | H270 TOMAHAWK ARCTIC        | [a3e9040cd5](https://linux-hardware.org/?probe=a3e9040cd5) | Sep 15, 2019 |
| ASUSTek    | H81M-PLUS                   | [91337a6d76](https://linux-hardware.org/?probe=91337a6d76) | Sep 11, 2019 |
| ASUSTek    | H81M-PLUS                   | [7a8b0b27b5](https://linux-hardware.org/?probe=7a8b0b27b5) | Sep 03, 2019 |
| Dell       | 0XCR8D A02                  | [ed9cabe6d7](https://linux-hardware.org/?probe=ed9cabe6d7) | Aug 16, 2019 |
| MSI        | MPG Z390 GAMING EDGE AC     | [f1c3773063](https://linux-hardware.org/?probe=f1c3773063) | Aug 13, 2019 |
| ASRock     | Z390 Steel Legend           | [416c87c987](https://linux-hardware.org/?probe=416c87c987) | Aug 12, 2019 |
| ASRock     | Z390 Steel Legend           | [e7df22136e](https://linux-hardware.org/?probe=e7df22136e) | Aug 06, 2019 |
| MSI        | H110M PRO-VH PLUS           | [cdce9b48f0](https://linux-hardware.org/?probe=cdce9b48f0) | Jul 20, 2019 |
| ASUSTek    | PRIME B250M-A               | [6f6ca5ee9d](https://linux-hardware.org/?probe=6f6ca5ee9d) | Jul 06, 2019 |
| ASUSTek    | PRIME B250M-A               | [84a0645101](https://linux-hardware.org/?probe=84a0645101) | Jul 06, 2019 |
| Gigabyte   | Z370 AORUS Gaming K3-CF     | [0f152d6ad7](https://linux-hardware.org/?probe=0f152d6ad7) | Jul 01, 2019 |
| Gigabyte   | Z370N WIFI-CF               | [1920d53d00](https://linux-hardware.org/?probe=1920d53d00) | Jun 14, 2019 |
| AAEON      | UP-CHT01 V0.4               | [90f9bd30f6](https://linux-hardware.org/?probe=90f9bd30f6) | Jun 04, 2019 |
| MSI        | B75A-G43 GAMING             | [fad87cd401](https://linux-hardware.org/?probe=fad87cd401) | May 31, 2019 |
| MSI        | B75A-G43 GAMING             | [2663832777](https://linux-hardware.org/?probe=2663832777) | May 31, 2019 |
| ASUSTek    | H110M-A/M.2                 | [6e8096d588](https://linux-hardware.org/?probe=6e8096d588) | May 28, 2019 |
| Gigabyte   | X79-UD3                     | [2fb24608fb](https://linux-hardware.org/?probe=2fb24608fb) | May 25, 2019 |
| Dell       | 0Y7WYT A00                  | [5e6308d089](https://linux-hardware.org/?probe=5e6308d089) | May 21, 2019 |
| Gigabyte   | Z370 AORUS Gaming K3-CF     | [ab671458e9](https://linux-hardware.org/?probe=ab671458e9) | May 19, 2019 |
| Gigabyte   | Z370 AORUS Gaming K3-CF     | [5e34a31988](https://linux-hardware.org/?probe=5e34a31988) | May 19, 2019 |
| Gigabyte   | X79-UD3                     | [987629983c](https://linux-hardware.org/?probe=987629983c) | May 15, 2019 |
| Gigabyte   | X79-UD3                     | [e361b0b9f1](https://linux-hardware.org/?probe=e361b0b9f1) | May 15, 2019 |
| Gigabyte   | X79-UD3                     | [92399f97c7](https://linux-hardware.org/?probe=92399f97c7) | May 15, 2019 |
| Lenovo     | 313C SDK0J40697 WIN 3305... | [d6926e4f6c](https://linux-hardware.org/?probe=d6926e4f6c) | May 10, 2019 |
| SYS        | BAT-MINI                    | [b4f7b429bf](https://linux-hardware.org/?probe=b4f7b429bf) | Apr 02, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Clear Linux 35000 | 14       | 4.18%   |
| Clear Linux 36010 | 13       | 3.88%   |
| Clear Linux 33590 | 8        | 2.39%   |
| Clear Linux 34930 | 6        | 1.79%   |
| Clear Linux 34500 | 6        | 1.79%   |
| Clear Linux 32480 | 5        | 1.49%   |
| Clear Linux 35110 | 4        | 1.19%   |
| Clear Linux 34860 | 4        | 1.19%   |
| Clear Linux 32270 | 4        | 1.19%   |
| Clear Linux 36640 | 3        | 0.9%    |
| Clear Linux 36480 | 3        | 0.9%    |
| Clear Linux 35090 | 3        | 0.9%    |
| Clear Linux 34820 | 3        | 0.9%    |
| Clear Linux 34670 | 3        | 0.9%    |
| Clear Linux 34320 | 3        | 0.9%    |
| Clear Linux 34000 | 3        | 0.9%    |
| Clear Linux 33460 | 3        | 0.9%    |
| Clear Linux 33440 | 3        | 0.9%    |
| Clear Linux 32910 | 3        | 0.9%    |
| Clear Linux 32760 | 3        | 0.9%    |
| Clear Linux 32510 | 3        | 0.9%    |
| Clear Linux 32330 | 3        | 0.9%    |
| Clear Linux 31470 | 3        | 0.9%    |
| Clear Linux       | 3        | 0.9%    |
| Clear Linux 37610 | 2        | 0.6%    |
| Clear Linux 37450 | 2        | 0.6%    |
| Clear Linux 37390 | 2        | 0.6%    |
| Clear Linux 37000 | 2        | 0.6%    |
| Clear Linux 36750 | 2        | 0.6%    |
| Clear Linux 36580 | 2        | 0.6%    |
| Clear Linux 36470 | 2        | 0.6%    |
| Clear Linux 36410 | 2        | 0.6%    |
| Clear Linux 36360 | 2        | 0.6%    |
| Clear Linux 36250 | 2        | 0.6%    |
| Clear Linux 35800 | 2        | 0.6%    |
| Clear Linux 35680 | 2        | 0.6%    |
| Clear Linux 35470 | 2        | 0.6%    |
| Clear Linux 35320 | 2        | 0.6%    |
| Clear Linux 35280 | 2        | 0.6%    |
| Clear Linux 35250 | 2        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Clear Linux | 295      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.13.13-1070.native | 24       | 7.32%   |
| 5.16.13-1132.native | 21       | 6.4%    |
| 5.7.13-975.native   | 12       | 3.66%   |
| 5.10.19-1032.native | 12       | 3.66%   |
| 5.5.6-914.native    | 7        | 2.13%   |
| 5.9.12-1004.native  | 6        | 1.83%   |
| 5.4.18-902.native   | 6        | 1.83%   |
| 5.13.8-1065.native  | 6        | 1.83%   |
| 5.12.14-1051.native | 6        | 1.83%   |
| 6.0.2-1201.native   | 3        | 0.91%   |
| 5.9.16-1009.native  | 3        | 0.91%   |
| 5.7.7-967.native    | 3        | 0.91%   |
| 5.7.6-966.native    | 3        | 0.91%   |
| 5.7.2-962.native    | 3        | 0.91%   |
| 5.6.6-942.native    | 3        | 0.91%   |
| 5.6.10-947.native   | 3        | 0.91%   |
| 5.5.9-918.native    | 3        | 0.91%   |
| 5.5.5-911.native    | 3        | 0.91%   |
| 5.5.4-910.native    | 3        | 0.91%   |
| 5.5.3-908.native    | 3        | 0.91%   |
| 5.4.2-875.native    | 3        | 0.91%   |
| 5.3.5-847.native    | 3        | 0.91%   |
| 5.18.16-1165.native | 3        | 0.91%   |
| 5.14.8-1078.native  | 3        | 0.91%   |
| 5.10.18-1027.native | 3        | 0.91%   |
| 6.0.7-1207.native   | 2        | 0.61%   |
| 5.9.8-1000.native   | 2        | 0.61%   |
| 5.9.13-1006.native  | 2        | 0.61%   |
| 5.9.1-992.native    | 2        | 0.61%   |
| 5.8.14-991.native   | 2        | 0.61%   |
| 5.7.18-980.native   | 2        | 0.61%   |
| 5.7.11-973.native   | 2        | 0.61%   |
| 5.7.10-972.native   | 2        | 0.61%   |
| 5.6.15-957.native   | 2        | 0.61%   |
| 5.6.11-949.native   | 2        | 0.61%   |
| 5.5.2-903.native    | 2        | 0.61%   |
| 5.5.15-930.native   | 2        | 0.61%   |
| 5.4.17-901.native   | 2        | 0.61%   |
| 5.4.16-900.native   | 2        | 0.61%   |
| 5.4.13-895.native   | 2        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.13 | 24       | 7.32%   |
| 5.16.13 | 21       | 6.4%    |
| 5.7.13  | 12       | 3.66%   |
| 5.10.19 | 12       | 3.66%   |
| 5.5.6   | 7        | 2.13%   |
| 5.9.12  | 6        | 1.83%   |
| 5.4.18  | 6        | 1.83%   |
| 5.13.8  | 6        | 1.83%   |
| 5.12.14 | 6        | 1.83%   |
| 5.5.4   | 4        | 1.22%   |
| 5.18.2  | 4        | 1.22%   |
| 6.0.2   | 3        | 0.91%   |
| 5.9.16  | 3        | 0.91%   |
| 5.7.7   | 3        | 0.91%   |
| 5.7.6   | 3        | 0.91%   |
| 5.7.2   | 3        | 0.91%   |
| 5.6.6   | 3        | 0.91%   |
| 5.6.11  | 3        | 0.91%   |
| 5.6.10  | 3        | 0.91%   |
| 5.5.9   | 3        | 0.91%   |
| 5.5.5   | 3        | 0.91%   |
| 5.5.3   | 3        | 0.91%   |
| 5.4.2   | 3        | 0.91%   |
| 5.3.5   | 3        | 0.91%   |
| 5.18.16 | 3        | 0.91%   |
| 5.16.18 | 3        | 0.91%   |
| 5.14.8  | 3        | 0.91%   |
| 5.10.18 | 3        | 0.91%   |
| 6.0.7   | 2        | 0.61%   |
| 5.9.8   | 2        | 0.61%   |
| 5.9.13  | 2        | 0.61%   |
| 5.9.1   | 2        | 0.61%   |
| 5.8.14  | 2        | 0.61%   |
| 5.7.18  | 2        | 0.61%   |
| 5.7.11  | 2        | 0.61%   |
| 5.7.10  | 2        | 0.61%   |
| 5.6.8   | 2        | 0.61%   |
| 5.6.15  | 2        | 0.61%   |
| 5.5.2   | 2        | 0.61%   |
| 5.5.15  | 2        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 36       | 11.25%  |
| 5.7     | 31       | 9.69%   |
| 5.16    | 31       | 9.69%   |
| 5.5     | 29       | 9.06%   |
| 5.10    | 29       | 9.06%   |
| 5.4     | 27       | 8.44%   |
| 5.6     | 21       | 6.56%   |
| 5.9     | 18       | 5.63%   |
| 5.12    | 16       | 5%      |
| 5.18    | 13       | 4.06%   |
| 5.3     | 11       | 3.44%   |
| 6.0     | 8        | 2.5%    |
| 6.1     | 6        | 1.88%   |
| 5.2     | 6        | 1.88%   |
| 5.15    | 6        | 1.88%   |
| 5.14    | 6        | 1.88%   |
| 5.1     | 6        | 1.88%   |
| 5.0     | 6        | 1.88%   |
| 5.17    | 5        | 1.56%   |
| 5.8     | 4        | 1.25%   |
| 5.19    | 3        | 0.94%   |
| 6.2     | 1        | 0.31%   |
| 4.19    | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 295      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 255      | 84.72%  |
| Unknown         | 30       | 9.97%   |
| KDE             | 5        | 1.66%   |
| XFCE            | 4        | 1.33%   |
| GNOME Flashback | 4        | 1.33%   |
| KDE5            | 2        | 0.66%   |
| GNOME-Flashback | 1        | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 278      | 93.29%  |
| Wayland | 17       | 5.7%    |
| Tty     | 3        | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 292      | 98.98%  |
| GDM     | 3        | 1.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 193      | 63.91%  |
| Unknown    | 28       | 9.27%   |
| ru_RU      | 18       | 5.96%   |
| es_MX      | 11       | 3.64%   |
| en_GB      | 8        | 2.65%   |
| de_DE      | 8        | 2.65%   |
| it_IT      | 7        | 2.32%   |
| fr_FR      | 7        | 2.32%   |
| pl_PL      | 4        | 1.32%   |
| es_ES      | 3        | 0.99%   |
| zh_TW      | 2        | 0.66%   |
| zh_CN      | 2        | 0.66%   |
| pt_PT      | 2        | 0.66%   |
| pt_BR      | 2        | 0.66%   |
| C          | 2        | 0.66%   |
| nl_BE      | 1        | 0.33%   |
| en_US.UTF8 | 1        | 0.33%   |
| en_AU      | 1        | 0.33%   |
| de_AT      | 1        | 0.33%   |
| bg_BG      | 1        | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 295      | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 258      | 86%     |
| Unknown | 31       | 10.33%  |
| Btrfs   | 6        | 2%      |
| Xfs     | 5        | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 288      | 97.3%   |
| GPT     | 8        | 2.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 294      | 99.66%  |
| Yes       | 1        | 0.34%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 293      | 99.32%  |
| Yes       | 2        | 0.68%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 80       | 27.12%  |
| Gigabyte Technology | 52       | 17.63%  |
| MSI                 | 30       | 10.17%  |
| ASRock              | 30       | 10.17%  |
| Hewlett-Packard     | 25       | 8.47%   |
| Dell                | 25       | 8.47%   |
| Intel               | 10       | 3.39%   |
| Lenovo              | 7        | 2.37%   |
| Acer                | 7        | 2.37%   |
| Unknown             | 7        | 2.37%   |
| Biostar             | 3        | 1.02%   |
| Shuttle             | 2        | 0.68%   |
| Pegatron            | 2        | 0.68%   |
| Huanan              | 2        | 0.68%   |
| Foxconn             | 2        | 0.68%   |
| SYS                 | 1        | 0.34%   |
| Supermicro          | 1        | 0.34%   |
| Medion              | 1        | 0.34%   |
| MAXSUN              | 1        | 0.34%   |
| iEi                 | 1        | 0.34%   |
| Hampoo              | 1        | 0.34%   |
| GMK                 | 1        | 0.34%   |
| Fujitsu             | 1        | 0.34%   |
| ECS                 | 1        | 0.34%   |
| AZW                 | 1        | 0.34%   |
| AAEON               | 1        | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 12       | 4.07%   |
| Unknown                      | 7        | 2.37%   |
| Dell OptiPlex 9020           | 5        | 1.69%   |
| Intel DN2820FYB H24582-205   | 4        | 1.36%   |
| Dell OptiPlex 7010           | 4        | 1.36%   |
| MSI MS-7C60                  | 3        | 1.02%   |
| MSI MS-7C02                  | 3        | 1.02%   |
| ASRock TRX40 Creator         | 3        | 1.02%   |
| MSI MS-7C95                  | 2        | 0.68%   |
| HP Compaq 8200 Elite SFF PC  | 2        | 0.68%   |
| HP Compaq 6200 Pro SFF PC    | 2        | 0.68%   |
| Gigabyte Z97X-UD3H           | 2        | 0.68%   |
| Gigabyte X79-UD3             | 2        | 0.68%   |
| Gigabyte X570 AORUS PRO WIFI | 2        | 0.68%   |
| Gigabyte H61M-DS2            | 2        | 0.68%   |
| Gigabyte B75M-D3H            | 2        | 0.68%   |
| Dell XPS 8930                | 2        | 0.68%   |
| Dell OptiPlex 7040           | 2        | 0.68%   |
| ASUS Z170-A                  | 2        | 0.68%   |
| ASUS TUF Gaming X570-PRO     | 2        | 0.68%   |
| ASUS TUF Gaming X570-PLUS    | 2        | 0.68%   |
| ASUS ROG Maximus Z690 HERO   | 2        | 0.68%   |
| ASUS ROG Maximus XII FORMULA | 2        | 0.68%   |
| ASUS PRIME B450M-A           | 2        | 0.68%   |
| ASUS P8P67 LE                | 2        | 0.68%   |
| ASUS H110M-A/M.2             | 2        | 0.68%   |
| SYS BAT-MINI                 | 1        | 0.34%   |
| Supermicro SYS-5038A-I       | 1        | 0.34%   |
| Shuttle SH67H                | 1        | 0.34%   |
| Shuttle DS81D                | 1        | 0.34%   |
| Pegatron SKLD4-P1            | 1        | 0.34%   |
| Pegatron h8-1400ex           | 1        | 0.34%   |
| MSI MS-7D25                  | 1        | 0.34%   |
| MSI MS-7D22                  | 1        | 0.34%   |
| MSI MS-7D18                  | 1        | 0.34%   |
| MSI MS-7D09                  | 1        | 0.34%   |
| MSI MS-7C94                  | 1        | 0.34%   |
| MSI MS-7C51                  | 1        | 0.34%   |
| MSI MS-7C37                  | 1        | 0.34%   |
| MSI MS-7B98                  | 1        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 19       | 6.44%   |
| ASUS ROG               | 18       | 6.1%    |
| Dell OptiPlex          | 16       | 5.42%   |
| ASUS All               | 12       | 4.07%   |
| HP Compaq              | 8        | 2.71%   |
| ASUS TUF               | 8        | 2.71%   |
| Acer Aspire            | 7        | 2.37%   |
| Unknown                | 7        | 2.37%   |
| Lenovo ThinkCentre     | 6        | 2.03%   |
| HP Pavilion            | 5        | 1.69%   |
| Gigabyte X570          | 5        | 1.69%   |
| Intel DN2820FYB        | 4        | 1.36%   |
| Dell Precision         | 4        | 1.36%   |
| ASRock TRX40           | 4        | 1.36%   |
| MSI MS-7C60            | 3        | 1.02%   |
| MSI MS-7C02            | 3        | 1.02%   |
| Gigabyte Z390          | 3        | 1.02%   |
| Gigabyte Z370          | 3        | 1.02%   |
| Gigabyte B450          | 3        | 1.02%   |
| Dell XPS               | 3        | 1.02%   |
| MSI MS-7C95            | 2        | 0.68%   |
| Intel X79              | 2        | 0.68%   |
| Gigabyte Z97X-UD3H     | 2        | 0.68%   |
| Gigabyte X79-UD3       | 2        | 0.68%   |
| Gigabyte H61M-DS2      | 2        | 0.68%   |
| Gigabyte G1.SNIPER     | 2        | 0.68%   |
| Gigabyte B75M-D3H      | 2        | 0.68%   |
| Gigabyte B365M         | 2        | 0.68%   |
| Gigabyte A320M-S2H     | 2        | 0.68%   |
| ASUS Z170-A            | 2        | 0.68%   |
| ASUS P8P67             | 2        | 0.68%   |
| ASUS H110M-A           | 2        | 0.68%   |
| ASRock Z390            | 2        | 0.68%   |
| ASRock H110M-DGS       | 2        | 0.68%   |
| ASRock AB350           | 2        | 0.68%   |
| SYS BAT-MINI           | 1        | 0.34%   |
| Supermicro SYS-5038A-I | 1        | 0.34%   |
| Shuttle SH67H          | 1        | 0.34%   |
| Shuttle DS81D          | 1        | 0.34%   |
| Pegatron SKLD4-P1      | 1        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 48       | 16.27%  |
| 2019 | 37       | 12.54%  |
| 2020 | 31       | 10.51%  |
| 2012 | 31       | 10.51%  |
| 2014 | 29       | 9.83%   |
| 2013 | 22       | 7.46%   |
| 2017 | 21       | 7.12%   |
| 2016 | 20       | 6.78%   |
| 2021 | 19       | 6.44%   |
| 2015 | 19       | 6.44%   |
| 2011 | 14       | 4.75%   |
| 2022 | 2        | 0.68%   |
| 2010 | 2        | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 295      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 295      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 295      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 92       | 30.77%  |
| 8.01-16.0       | 55       | 18.39%  |
| 32.01-64.0      | 47       | 15.72%  |
| 4.01-8.0        | 35       | 11.71%  |
| 64.01-256.0     | 32       | 10.7%   |
| 3.01-4.0        | 25       | 8.36%   |
| 24.01-32.0      | 9        | 3.01%   |
| More than 256.0 | 2        | 0.67%   |
| 1.01-2.0        | 2        | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 110      | 34.48%  |
| 2.01-3.0    | 93       | 29.15%  |
| 4.01-8.0    | 47       | 14.73%  |
| 3.01-4.0    | 42       | 13.17%  |
| 8.01-16.0   | 16       | 5.02%   |
| 0.51-1.0    | 8        | 2.51%   |
| 32.01-64.0  | 1        | 0.31%   |
| 64.01-256.0 | 1        | 0.31%   |
| 16.01-24.0  | 1        | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 113      | 37.05%  |
| 2      | 84       | 27.54%  |
| 3      | 51       | 16.72%  |
| 4      | 35       | 11.48%  |
| 5      | 14       | 4.59%   |
| 6      | 4        | 1.31%   |
| 7      | 3        | 0.98%   |
| 0      | 1        | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 207      | 69.93%  |
| Yes       | 89       | 30.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 291      | 98.64%  |
| No        | 4        | 1.36%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 53.69%  |
| Yes       | 138      | 46.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 175      | 58.92%  |
| Yes       | 122      | 41.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 81       | 27.46%  |
| Russia       | 24       | 8.14%   |
| UK           | 23       | 7.8%    |
| Germany      | 17       | 5.76%   |
| Italy        | 14       | 4.75%   |
| France       | 11       | 3.73%   |
| Brazil       | 9        | 3.05%   |
| India        | 8        | 2.71%   |
| Canada       | 8        | 2.71%   |
| Argentina    | 8        | 2.71%   |
| Sweden       | 7        | 2.37%   |
| Spain        | 7        | 2.37%   |
| Australia    | 7        | 2.37%   |
| Poland       | 6        | 2.03%   |
| Netherlands  | 6        | 2.03%   |
| Romania      | 5        | 1.69%   |
| Norway       | 4        | 1.36%   |
| Serbia       | 3        | 1.02%   |
| Indonesia    | 3        | 1.02%   |
| China        | 3        | 1.02%   |
| Austria      | 3        | 1.02%   |
| Vietnam      | 2        | 0.68%   |
| Ukraine      | 2        | 0.68%   |
| Thailand     | 2        | 0.68%   |
| Taiwan       | 2        | 0.68%   |
| South Africa | 2        | 0.68%   |
| Portugal     | 2        | 0.68%   |
| Mexico       | 2        | 0.68%   |
| Latvia       | 2        | 0.68%   |
| Japan        | 2        | 0.68%   |
| Hong Kong    | 2        | 0.68%   |
| Bulgaria     | 2        | 0.68%   |
| Belgium      | 2        | 0.68%   |
| Turkey       | 1        | 0.34%   |
| Saudi Arabia | 1        | 0.34%   |
| Myanmar      | 1        | 0.34%   |
| Lithuania    | 1        | 0.34%   |
| Lebanon      | 1        | 0.34%   |
| Kazakhstan   | 1        | 0.34%   |
| Ireland      | 1        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 7        | 2.29%   |
| St Petersburg    | 4        | 1.31%   |
| Brisbane         | 4        | 1.31%   |
| Springfield      | 3        | 0.98%   |
| Shelbyville      | 3        | 0.98%   |
| Buenos Aires     | 3        | 0.98%   |
| Villa Elisa      | 2        | 0.65%   |
| Toronto          | 2        | 0.65%   |
| Stockton         | 2        | 0.65%   |
| San Jose         | 2        | 0.65%   |
| Rome             | 2        | 0.65%   |
| Riga             | 2        | 0.65%   |
| Portland         | 2        | 0.65%   |
| Palermo          | 2        | 0.65%   |
| Mumbai           | 2        | 0.65%   |
| Milan            | 2        | 0.65%   |
| Madrid           | 2        | 0.65%   |
| Lisbon           | 2        | 0.65%   |
| Las Vegas        | 2        | 0.65%   |
| La Plata         | 2        | 0.65%   |
| Ho Chi Minh City | 2        | 0.65%   |
| Groton           | 2        | 0.65%   |
| Gijón           | 2        | 0.65%   |
| Cincinnati       | 2        | 0.65%   |
| Bengaluru        | 2        | 0.65%   |
| Belgrade         | 2        | 0.65%   |
| Athens           | 2        | 0.65%   |
| Zaandam          | 1        | 0.33%   |
| Yogyakarta       | 1        | 0.33%   |
| Yekaterinburg    | 1        | 0.33%   |
| Yangon           | 1        | 0.33%   |
| Wroclaw          | 1        | 0.33%   |
| Woodbine         | 1        | 0.33%   |
| Wolfenbüttel    | 1        | 0.33%   |
| Wezep            | 1        | 0.33%   |
| Wetteren         | 1        | 0.33%   |
| Weinbach         | 1        | 0.33%   |
| Weilburg         | 1        | 0.33%   |
| Warsaw           | 1        | 0.33%   |
| Warrington       | 1        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 100      | 146    | 18.05%  |
| Samsung Electronics         | 79       | 128    | 14.26%  |
| WDC                         | 68       | 91     | 12.27%  |
| Toshiba                     | 38       | 55     | 6.86%   |
| SanDisk                     | 29       | 37     | 5.23%   |
| Kingston                    | 25       | 32     | 4.51%   |
| Crucial                     | 22       | 28     | 3.97%   |
| Phison                      | 21       | 29     | 3.79%   |
| Unknown                     | 20       | 21     | 3.61%   |
| Intel                       | 19       | 21     | 3.43%   |
| A-DATA Technology           | 12       | 12     | 2.17%   |
| Hitachi                     | 10       | 10     | 1.81%   |
| SPCC                        | 7        | 8      | 1.26%   |
| Silicon Motion              | 6        | 7      | 1.08%   |
| Patriot                     | 6        | 6      | 1.08%   |
| HGST                        | 6        | 10     | 1.08%   |
| Transcend                   | 5        | 5      | 0.9%    |
| SK hynix                    | 5        | 6      | 0.9%    |
| PNY                         | 5        | 9      | 0.9%    |
| Micron/Crucial Technology   | 5        | 7      | 0.9%    |
| XPG                         | 4        | 4      | 0.72%   |
| Micron Technology           | 4        | 7      | 0.72%   |
| LITEONIT                    | 4        | 6      | 0.72%   |
| JMicron Technology          | 4        | 4      | 0.72%   |
| China                       | 4        | 24     | 0.72%   |
| Team                        | 3        | 3      | 0.54%   |
| Apacer                      | 3        | 4      | 0.54%   |
| Yangtze Memory Technologies | 2        | 2      | 0.36%   |
| Realtek Semiconductor       | 2        | 2      | 0.36%   |
| Netac                       | 2        | 2      | 0.36%   |
| Maxtor                      | 2        | 2      | 0.36%   |
| KIOXIA                      | 2        | 4      | 0.36%   |
| KingDian                    | 2        | 4      | 0.36%   |
| Hewlett-Packard             | 2        | 2      | 0.36%   |
| GOODRAM                     | 2        | 2      | 0.36%   |
| Corsair                     | 2        | 6      | 0.36%   |
| ADATA Technology            | 2        | 2      | 0.36%   |
| WDC WDS2                    | 1        | 1      | 0.18%   |
| Verbatim                    | 1        | 2      | 0.18%   |
| USB3.0                      | 1        | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB           | 16       | 2.49%   |
| Samsung NVMe SSD Drive 1TB             | 11       | 1.71%   |
| Samsung SSD 850 EVO 250GB              | 9        | 1.4%    |
| Unknown SD/MMC/MS PRO 16GB             | 8        | 1.25%   |
| Toshiba DT01ACA100 1TB                 | 8        | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB         | 8        | 1.25%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 7        | 1.09%   |
| WDC WD10EZEX-08WN4A0 1TB               | 6        | 0.93%   |
| Toshiba DT01ACA050 500GB               | 6        | 0.93%   |
| Phison NVMe SSD Drive 1TB              | 6        | 0.93%   |
| Toshiba HDWD110 1TB                    | 5        | 0.78%   |
| Seagate ST2000DM008-2FR102 2TB         | 5        | 0.78%   |
| Crucial CT500MX500SSD1 500GB           | 5        | 0.78%   |
| Unknown MMC Card  64GB                 | 4        | 0.62%   |
| Seagate ST500LM030-2E717D 500GB        | 4        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB        | 4        | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB         | 4        | 0.62%   |
| SanDisk NVMe SSD Drive 500GB           | 4        | 0.62%   |
| Samsung SSD 860 EVO 250GB              | 4        | 0.62%   |
| Samsung SSD 840 EVO 120GB              | 4        | 0.62%   |
| Samsung NVMe SSD Drive 2TB             | 4        | 0.62%   |
| Samsung NVMe SSD Drive 1024GB          | 4        | 0.62%   |
| Phison NVMe SSD Drive 512GB            | 4        | 0.62%   |
| Kingston SA400S37240G 240GB SSD        | 4        | 0.62%   |
| Kingston SA400S37120G 120GB SSD        | 4        | 0.62%   |
| Intel NVMe SSD Drive 1024GB            | 4        | 0.62%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 3        | 0.47%   |
| WDC WD10EZEX-60WN4A0 1TB               | 3        | 0.47%   |
| Toshiba DT01ACA200 2TB                 | 3        | 0.47%   |
| Seagate ST6000VN0033-2EE110 6TB        | 3        | 0.47%   |
| Seagate ST4000DM005-2DP166 4TB         | 3        | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB         | 3        | 0.47%   |
| Seagate ST250DM000-1BD141 250GB        | 3        | 0.47%   |
| Seagate ST2000DM001-1CH164 2TB         | 3        | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB         | 3        | 0.47%   |
| SanDisk SSD PLUS 480GB                 | 3        | 0.47%   |
| SanDisk SDSSDP128G 128GB               | 3        | 0.47%   |
| SanDisk NVMe SSD Drive 256GB           | 3        | 0.47%   |
| Samsung SSD 860 QVO 1TB                | 3        | 0.47%   |
| Samsung SSD 850 EVO 500GB              | 3        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 95       | 134    | 41.85%  |
| WDC                 | 62       | 82     | 27.31%  |
| Toshiba             | 30       | 47     | 13.22%  |
| Hitachi             | 10       | 10     | 4.41%   |
| Unknown             | 8        | 8      | 3.52%   |
| Samsung Electronics | 7        | 7      | 3.08%   |
| HGST                | 6        | 10     | 2.64%   |
| JMicron Technology  | 3        | 3      | 1.32%   |
| Maxtor              | 2        | 2      | 0.88%   |
| USB3.0              | 1        | 1      | 0.44%   |
| MARVELL             | 1        | 1      | 0.44%   |
| Fujitsu             | 1        | 1      | 0.44%   |
| ASMT                | 1        | 2      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 44       | 61     | 21.46%  |
| Kingston            | 24       | 30     | 11.71%  |
| Crucial             | 22       | 28     | 10.73%  |
| SanDisk             | 18       | 20     | 8.78%   |
| A-DATA Technology   | 12       | 12     | 5.85%   |
| Intel               | 10       | 11     | 4.88%   |
| WDC                 | 8        | 9      | 3.9%    |
| SPCC                | 7        | 8      | 3.41%   |
| Patriot             | 6        | 6      | 2.93%   |
| Transcend           | 5        | 5      | 2.44%   |
| Toshiba             | 5        | 5      | 2.44%   |
| PNY                 | 5        | 9      | 2.44%   |
| LITEONIT            | 4        | 6      | 1.95%   |
| China               | 4        | 24     | 1.95%   |
| Team                | 3        | 3      | 1.46%   |
| Apacer              | 3        | 4      | 1.46%   |
| Seagate             | 2        | 2      | 0.98%   |
| Micron Technology   | 2        | 2      | 0.98%   |
| KingDian            | 2        | 4      | 0.98%   |
| Hewlett-Packard     | 2        | 2      | 0.98%   |
| GOODRAM             | 2        | 2      | 0.98%   |
| Corsair             | 2        | 6      | 0.98%   |
| WDC WDS2            | 1        | 1      | 0.49%   |
| Verbatim            | 1        | 2      | 0.49%   |
| Unknown             | 1        | 1      | 0.49%   |
| SK hynix            | 1        | 2      | 0.49%   |
| Plextor             | 1        | 1      | 0.49%   |
| OCZ                 | 1        | 2      | 0.49%   |
| Netac               | 1        | 1      | 0.49%   |
| KingSpec            | 1        | 1      | 0.49%   |
| Intenso             | 1        | 1      | 0.49%   |
| Hoodisk             | 1        | 2      | 0.49%   |
| Hikvision           | 1        | 1      | 0.49%   |
| Gigabyte Technology | 1        | 1      | 0.49%   |
| Acer                | 1        | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 190      | 308    | 39.58%  |
| SSD     | 166      | 276    | 34.58%  |
| NVMe    | 110      | 173    | 22.92%  |
| Unknown | 8        | 11     | 1.67%   |
| MMC     | 6        | 6      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 258      | 565    | 64.82%  |
| NVMe | 109      | 172    | 27.39%  |
| SAS  | 25       | 31     | 6.28%   |
| MMC  | 6        | 6      | 1.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 192      | 358    | 52.75%  |
| 0.51-1.0   | 90       | 121    | 24.73%  |
| 1.01-2.0   | 38       | 47     | 10.44%  |
| 4.01-10.0  | 17       | 23     | 4.67%   |
| 3.01-4.0   | 12       | 16     | 3.3%    |
| 2.01-3.0   | 9        | 9      | 2.47%   |
| 10.01-20.0 | 6        | 10     | 1.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 99       | 32.35%  |
| 251-500        | 65       | 21.24%  |
| 501-1000       | 44       | 14.38%  |
| 1001-2000      | 26       | 8.5%    |
| 51-100         | 20       | 6.54%   |
| Unknown        | 17       | 5.56%   |
| More than 3000 | 14       | 4.58%   |
| 2001-3000      | 12       | 3.92%   |
| 21-50          | 8        | 2.61%   |
| 1-20           | 1        | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 130      | 41.67%  |
| 21-50          | 72       | 23.08%  |
| 101-250        | 25       | 8.01%   |
| 51-100         | 24       | 7.69%   |
| Unknown        | 17       | 5.45%   |
| 251-500        | 16       | 5.13%   |
| 501-1000       | 11       | 3.53%   |
| 1001-2000      | 8        | 2.56%   |
| More than 3000 | 7        | 2.24%   |
| 2001-3000      | 2        | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500LM030-2E717D 500GB | 2        | 2      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 289      | 752    | 96.98%  |
| Works    | 7        | 20     | 2.35%   |
| Malfunc  | 2        | 2      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 215      | 48.75%  |
| AMD                          | 76       | 17.23%  |
| Samsung Electronics          | 45       | 10.2%   |
| Phison Electronics           | 21       | 4.76%   |
| ASMedia Technology           | 18       | 4.08%   |
| SanDisk                      | 12       | 2.72%   |
| Marvell Technology Group     | 8        | 1.81%   |
| ADATA Technology             | 7        | 1.59%   |
| Silicon Motion               | 6        | 1.36%   |
| Micron/Crucial Technology    | 5        | 1.13%   |
| SK hynix                     | 4        | 0.91%   |
| Seagate Technology           | 4        | 0.91%   |
| Toshiba America Info Systems | 3        | 0.68%   |
| Realtek Semiconductor        | 3        | 0.68%   |
| Broadcom / LSI               | 3        | 0.68%   |
| Yangtze Memory Technologies  | 2        | 0.45%   |
| Micron Technology            | 2        | 0.45%   |
| LSI Logic / Symbios Logic    | 2        | 0.45%   |
| KIOXIA                       | 2        | 0.45%   |
| Kingston Technology Company  | 2        | 0.45%   |
| Lite-On Technology           | 1        | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 59       | 11.61%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 32       | 6.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 28       | 5.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 23       | 4.53%   |
| Intel SATA Controller [RAID mode]                                              | 21       | 4.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21       | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 19       | 3.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 18       | 3.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 18       | 3.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 18       | 3.54%   |
| AMD 400 Series Chipset SATA Controller                                         | 16       | 3.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9        | 1.77%   |
| Phison E16 PCIe4 NVMe Controller                                               | 8        | 1.57%   |
| Phison E12 NVMe Controller                                                     | 8        | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7        | 1.38%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 7        | 1.38%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 7        | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7        | 1.38%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 7        | 1.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6        | 1.18%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 6        | 1.18%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 6        | 1.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6        | 1.18%   |
| AMD 300 Series Chipset SATA Controller                                         | 6        | 1.18%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 5        | 0.98%   |
| Intel SSD 660P Series                                                          | 5        | 0.98%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 5        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 5        | 0.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4        | 0.79%   |
| Seagate FireCuda 520 SSD                                                       | 4        | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4        | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3        | 0.59%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 0.59%   |
| Realtek Realtek Non-Volatile memory controller                                 | 3        | 0.59%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3        | 0.59%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 260      | 61.47%  |
| NVMe | 111      | 26.24%  |
| RAID | 32       | 7.57%   |
| IDE  | 15       | 3.55%   |
| SAS  | 4        | 0.95%   |
| SCSI | 1        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 219      | 74.24%  |
| AMD    | 76       | 25.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen Threadripper 3960X 24-Core Processor | 7        | 2.36%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 6        | 2.03%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 6        | 2.03%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 5        | 1.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 5        | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 5        | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor              | 5        | 1.69%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 4        | 1.35%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 4        | 1.35%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 4        | 1.35%   |
| Intel Core i5-8600K CPU @ 3.60GHz              | 4        | 1.35%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 4        | 1.35%   |
| Intel Celeron CPU N2830 @ 2.16GHz              | 4        | 1.35%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 1.35%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 4        | 1.35%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 4        | 1.35%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 3        | 1.01%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 3        | 1.01%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 3        | 1.01%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 3        | 1.01%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 3        | 1.01%   |
| Intel Core i5-3550 CPU @ 3.30GHz               | 3        | 1.01%   |
| Intel Core i3-8100 CPU @ 3.60GHz               | 3        | 1.01%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 3        | 1.01%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 3        | 1.01%   |
| Intel 12th Gen Core i9-12900K                  | 3        | 1.01%   |
| AMD Ryzen Threadripper 3990X 64-Core Processor | 3        | 1.01%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 1.01%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 1.01%   |
| AMD FX-8350 Eight-Core Processor               | 3        | 1.01%   |
| Intel Xeon CPU X5675 @ 3.07GHz                 | 2        | 0.68%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz            | 2        | 0.68%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz            | 2        | 0.68%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 2        | 0.68%   |
| Intel Core i9-10900K CPU @ 3.70GHz             | 2        | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 2        | 0.68%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 2        | 0.68%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 2        | 0.68%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 2        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 78       | 26.44%  |
| Intel Core i7          | 50       | 16.95%  |
| Intel Xeon             | 22       | 7.46%   |
| Intel Core i3          | 21       | 7.12%   |
| AMD Ryzen 5            | 17       | 5.76%   |
| Other                  | 15       | 5.08%   |
| Intel Celeron          | 15       | 5.08%   |
| AMD Ryzen Threadripper | 13       | 4.41%   |
| AMD Ryzen 7            | 13       | 4.41%   |
| AMD Ryzen 9            | 9        | 3.05%   |
| Intel Pentium          | 7        | 2.37%   |
| Intel Core i9          | 7        | 2.37%   |
| AMD FX                 | 7        | 2.37%   |
| AMD Ryzen 3            | 6        | 2.03%   |
| AMD Athlon             | 3        | 1.02%   |
| AMD A10                | 3        | 1.02%   |
| Intel Atom             | 2        | 0.68%   |
| AMD A6                 | 2        | 0.68%   |
| Intel Pentium Gold     | 1        | 0.34%   |
| Intel Genuine          | 1        | 0.34%   |
| AMD Ryzen 5 PRO        | 1        | 0.34%   |
| AMD A8                 | 1        | 0.34%   |
| AMD A4                 | 1        | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 123      | 41.69%  |
| 6      | 58       | 19.66%  |
| 2      | 44       | 14.92%  |
| 8      | 29       | 9.83%   |
| 12     | 13       | 4.41%   |
| 24     | 8        | 2.71%   |
| 16     | 6        | 2.03%   |
| 10     | 5        | 1.69%   |
| 64     | 3        | 1.02%   |
| 1      | 3        | 1.02%   |
| 32     | 2        | 0.68%   |
| 36     | 1        | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 290      | 98.31%  |
| 2      | 5        | 1.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 177      | 59.8%   |
| 1      | 119      | 40.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 273      | 91.61%  |
| Unknown        | 25       | 8.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 280      | 94.28%  |
| 0x506e3 | 4        | 1.35%   |
| 0x906e9 | 3        | 1.01%   |
| 0x306c3 | 3        | 1.01%   |
| 0x30678 | 3        | 1.01%   |
| 0x906ea | 2        | 0.67%   |
| 0x406c4 | 1        | 0.34%   |
| 0x206a7 | 1        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 54       | 18.31%  |
| Haswell       | 47       | 15.93%  |
| Zen 2         | 29       | 9.83%   |
| IvyBridge     | 29       | 9.83%   |
| SandyBridge   | 23       | 7.8%    |
| Skylake       | 19       | 6.44%   |
| Zen+          | 16       | 5.42%   |
| Unknown       | 15       | 5.08%   |
| CometLake     | 13       | 4.41%   |
| Silvermont    | 12       | 4.07%   |
| Piledriver    | 11       | 3.73%   |
| Zen 3         | 8        | 2.71%   |
| Zen           | 8        | 2.71%   |
| Westmere      | 2        | 0.68%   |
| Goldmont plus | 2        | 0.68%   |
| Broadwell     | 2        | 0.68%   |
| Steamroller   | 1        | 0.34%   |
| Jaguar        | 1        | 0.34%   |
| Goldmont      | 1        | 0.34%   |
| Excavator     | 1        | 0.34%   |
| Bulldozer     | 1        | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 142      | 44.1%   |
| Intel  | 104      | 32.3%   |
| AMD    | 76       | 23.6%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 18       | 5.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15       | 4.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11       | 3.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11       | 3.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10       | 3.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 3.06%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 9        | 2.75%   |
| Intel HD Graphics 630                                                                    | 9        | 2.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8        | 2.45%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7        | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7        | 2.14%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6        | 1.83%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 6        | 1.83%   |
| Intel HD Graphics 530                                                                    | 6        | 1.83%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6        | 1.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5        | 1.53%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 5        | 1.53%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 5        | 1.53%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5        | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 1.53%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 4        | 1.22%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4        | 1.22%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4        | 1.22%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.22%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 1.22%   |
| Intel AlderLake-S GT1                                                                    | 4        | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 3        | 0.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 0.92%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 3        | 0.92%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 3        | 0.92%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3        | 0.92%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3        | 0.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 0.61%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2        | 0.61%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 2        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 2        | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 0.61%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 134      | 44.97%  |
| 1 x Intel                | 82       | 27.52%  |
| 1 x AMD                  | 71       | 23.83%  |
| Intel + Nvidia           | 5        | 1.68%   |
| Intel + AMD              | 2        | 0.67%   |
| 2 x Nvidia               | 1        | 0.34%   |
| 2 x AMD + 1 x Nvidia     | 1        | 0.34%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.34%   |
| AMD + Nvidia             | 1        | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 275      | 92.59%  |
| Proprietary | 19       | 6.4%    |
| Unknown     | 3        | 1.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 272      | 91.58%  |
| 7.01-8.0   | 6        | 2.02%   |
| 3.01-4.0   | 6        | 2.02%   |
| 1.01-2.0   | 6        | 2.02%   |
| 5.01-6.0   | 2        | 0.67%   |
| 8.01-16.0  | 2        | 0.67%   |
| 0.51-1.0   | 2        | 0.67%   |
| 16.01-24.0 | 1        | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 68       | 20.61%  |
| Dell                 | 34       | 10.3%   |
| Goldstar             | 31       | 9.39%   |
| AOC                  | 22       | 6.67%   |
| Hewlett-Packard      | 21       | 6.36%   |
| BenQ                 | 19       | 5.76%   |
| Ancor Communications | 16       | 4.85%   |
| Acer                 | 15       | 4.55%   |
| ViewSonic            | 14       | 4.24%   |
| Philips              | 11       | 3.33%   |
| MSI                  | 6        | 1.82%   |
| Hitachi              | 6        | 1.82%   |
| ASUSTek Computer     | 6        | 1.82%   |
| Sony                 | 5        | 1.52%   |
| LG Electronics       | 4        | 1.21%   |
| Iiyama               | 4        | 1.21%   |
| Unknown              | 3        | 0.91%   |
| Toshiba              | 3        | 0.91%   |
| Sharp                | 3        | 0.91%   |
| Medion               | 3        | 0.91%   |
| Lenovo               | 3        | 0.91%   |
| Vizio                | 2        | 0.61%   |
| Sceptre Tech         | 2        | 0.61%   |
| RTK                  | 2        | 0.61%   |
| Insignia             | 2        | 0.61%   |
| Fujitsu Siemens      | 2        | 0.61%   |
| Arnos Instruments    | 2        | 0.61%   |
| Yuraku               | 1        | 0.3%    |
| Westinghouse         | 1        | 0.3%    |
| Vestel Elektronik    | 1        | 0.3%    |
| Unknown (XXX)        | 1        | 0.3%    |
| STD                  | 1        | 0.3%    |
| Pixio                | 1        | 0.3%    |
| NEC Computers        | 1        | 0.3%    |
| MStar                | 1        | 0.3%    |
| MiTAC                | 1        | 0.3%    |
| Medion Akoya         | 1        | 0.3%    |
| HVR                  | 1        | 0.3%    |
| HannStar             | 1        | 0.3%    |
| Haier                | 1        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 5        | 1.43%   |
| MSI MAG341CQ MSI1462 3440x1440 797x334mm 34.0-inch                      | 4        | 1.14%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                   | 4        | 1.14%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 3        | 0.86%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3        | 0.86%   |
| ViewSonic LCD Monitor VA2212 Series                                     | 2        | 0.57%   |
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                         | 2        | 0.57%   |
| Samsung Electronics U28E510 SAM0D64 3840x2160 608x345mm 27.5-inch       | 2        | 0.57%   |
| Samsung Electronics U28E510 SAM0D63 1680x1050 610x350mm 27.7-inch       | 2        | 0.57%   |
| Samsung Electronics S24D391 SAM0B87 1920x1080 521x293mm 23.5-inch       | 2        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 2        | 0.57%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 2        | 0.57%   |
| Hitachi W240D DVI HIT7D03 1920x1200 520x320mm 24.0-inch                 | 2        | 0.57%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                | 2        | 0.57%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch                | 2        | 0.57%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 2        | 0.57%   |
| Goldstar Ultra HD GSM5B08 3780x2160 600x340mm 27.2-inch                 | 2        | 0.57%   |
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                       | 2        | 0.57%   |
| AOC AG352QG2 AOC3520 2560x1080 820x346mm 35.0-inch                      | 2        | 0.57%   |
| AOC 2276WM AOC2276 1920x1080 477x268mm 21.5-inch                        | 2        | 0.57%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                       | 2        | 0.57%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch        | 2        | 0.57%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch   | 2        | 0.57%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                      | 2        | 0.57%   |
| Yuraku MA2221 FAC2221 1920x1080 410x230mm 18.5-inch                     | 1        | 0.29%   |
| Westinghouse WD32HD1390 WET3553 1680x1050 708x398mm 32.0-inch           | 1        | 0.29%   |
| Vizio LCD Monitor VIZ0026 1360x768 580x320mm 26.1-inch                  | 1        | 0.29%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1        | 0.29%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1        | 0.29%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch           | 1        | 0.29%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch           | 1        | 0.29%   |
| ViewSonic VX2257 VSCB731 1920x1080 477x268mm 21.5-inch                  | 1        | 0.29%   |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch           | 1        | 0.29%   |
| ViewSonic VX2039 Series VSCB531 1440x900 419x262mm 19.5-inch            | 1        | 0.29%   |
| ViewSonic VX2035wm VSCAF1E 1680x1050 433x271mm 20.1-inch                | 1        | 0.29%   |
| ViewSonic VP171s VSCB716 1280x1024 338x270mm 17.0-inch                  | 1        | 0.29%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch           | 1        | 0.29%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch           | 1        | 0.29%   |
| ViewSonic VA2219 Series VSC7932 1920x1080 477x268mm 21.5-inch           | 1        | 0.29%   |
| ViewSonic G90fb-2 VSC4907 1920x1440 357x268mm 17.6-inch                 | 1        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 156      | 48.3%   |
| 3840x2160 (4K)     | 44       | 13.62%  |
| 2560x1440 (QHD)    | 21       | 6.5%    |
| 1280x1024 (SXGA)   | 15       | 4.64%   |
| 1680x1050 (WSXGA+) | 14       | 4.33%   |
| 3440x1440          | 10       | 3.1%    |
| 2560x1080          | 10       | 3.1%    |
| 1920x1200 (WUXGA)  | 9        | 2.79%   |
| 1440x900 (WXGA+)   | 7        | 2.17%   |
| 1366x768 (WXGA)    | 6        | 1.86%   |
| 1360x768           | 6        | 1.86%   |
| Unknown            | 5        | 1.55%   |
| 1920x540           | 3        | 0.93%   |
| 1600x900 (HD+)     | 3        | 0.93%   |
| 5760x2160          | 2        | 0.62%   |
| 3840x1080          | 2        | 0.62%   |
| 1024x768 (XGA)     | 2        | 0.62%   |
| 4480x1440          | 1        | 0.31%   |
| 3840x1600          | 1        | 0.31%   |
| 3600x1080          | 1        | 0.31%   |
| 3360x1050          | 1        | 0.31%   |
| 2160x1200          | 1        | 0.31%   |
| 2048x1152          | 1        | 0.31%   |
| 1600x1200          | 1        | 0.31%   |
| 1280x720 (HD)      | 1        | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 56       | 16.92%  |
| 24      | 49       | 14.8%   |
| 23      | 37       | 11.18%  |
| 21      | 37       | 11.18%  |
| Unknown | 20       | 6.04%   |
| 34      | 14       | 4.23%   |
| 19      | 13       | 3.93%   |
| 84      | 12       | 3.63%   |
| 22      | 12       | 3.63%   |
| 20      | 9        | 2.72%   |
| 17      | 9        | 2.72%   |
| 18      | 8        | 2.42%   |
| 31      | 7        | 2.11%   |
| 72      | 5        | 1.51%   |
| 40      | 5        | 1.51%   |
| 54      | 4        | 1.21%   |
| 25      | 4        | 1.21%   |
| 48      | 3        | 0.91%   |
| 37      | 3        | 0.91%   |
| 35      | 3        | 0.91%   |
| 32      | 3        | 0.91%   |
| 26      | 3        | 0.91%   |
| 52      | 2        | 0.6%    |
| 29      | 2        | 0.6%    |
| 15      | 2        | 0.6%    |
| 65      | 1        | 0.3%    |
| 57      | 1        | 0.3%    |
| 55      | 1        | 0.3%    |
| 50      | 1        | 0.3%    |
| 43      | 1        | 0.3%    |
| 42      | 1        | 0.3%    |
| 36      | 1        | 0.3%    |
| 33      | 1        | 0.3%    |
| 28      | 1        | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 126      | 39.5%   |
| 401-500     | 69       | 21.63%  |
| 601-700     | 23       | 7.21%   |
| 701-800     | 20       | 6.27%   |
| Unknown     | 20       | 6.27%   |
| 1501-2000   | 17       | 5.33%   |
| 1001-1500   | 12       | 3.76%   |
| 801-900     | 11       | 3.45%   |
| 301-350     | 10       | 3.13%   |
| 351-400     | 9        | 2.82%   |
| 901-1000    | 2        | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 212      | 69.06%  |
| 16/10   | 33       | 10.75%  |
| 21/9    | 20       | 6.51%   |
| 5/4     | 16       | 5.21%   |
| Unknown | 16       | 5.21%   |
| 4/3     | 5        | 1.63%   |
| 32/9    | 2        | 0.65%   |
| 1.96    | 1        | 0.33%   |
| 1.00    | 1        | 0.33%   |
| 0.56    | 1        | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 109      | 33.54%  |
| 301-350        | 58       | 17.85%  |
| 151-200        | 34       | 10.46%  |
| 351-500        | 28       | 8.62%   |
| More than 1000 | 27       | 8.31%   |
| Unknown        | 20       | 6.15%   |
| 251-300        | 18       | 5.54%   |
| 141-150        | 15       | 4.62%   |
| 501-1000       | 14       | 4.31%   |
| 101-110        | 2        | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 178      | 58.36%  |
| 101-120 | 65       | 21.31%  |
| Unknown | 20       | 6.56%   |
| 1-50    | 18       | 5.9%    |
| 121-160 | 18       | 5.9%    |
| 161-240 | 6        | 1.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 242      | 81.48%  |
| 2     | 44       | 14.81%  |
| 3     | 7        | 2.36%   |
| 0     | 4        | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 159      | 38.88%  |
| Intel                           | 156      | 38.14%  |
| Qualcomm Atheros                | 32       | 7.82%   |
| Aquantia                        | 9        | 2.2%    |
| Ralink Technology               | 8        | 1.96%   |
| Broadcom                        | 7        | 1.71%   |
| TP-Link                         | 4        | 0.98%   |
| Samsung Electronics             | 4        | 0.98%   |
| Microsoft                       | 4        | 0.98%   |
| Ralink                          | 3        | 0.73%   |
| Qualcomm Atheros Communications | 3        | 0.73%   |
| Broadcom Limited                | 3        | 0.73%   |
| Microchip Technology            | 2        | 0.49%   |
| HMD Global                      | 2        | 0.49%   |
| D-Link                          | 2        | 0.49%   |
| ASUSTek Computer                | 2        | 0.49%   |
| Xiaomi                          | 1        | 0.24%   |
| Nordic Semiconductor ASA        | 1        | 0.24%   |
| Micro Star International        | 1        | 0.24%   |
| MediaTek                        | 1        | 0.24%   |
| LeafLabs                        | 1        | 0.24%   |
| DisplayLink                     | 1        | 0.24%   |
| Digital Equipment               | 1        | 0.24%   |
| D-Link System                   | 1        | 0.24%   |
| Apple                           | 1        | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 135      | 27.66%  |
| Intel I211 Gigabit Network Connection                             | 25       | 5.12%   |
| Intel Wi-Fi 6 AX200                                               | 22       | 4.51%   |
| Intel Ethernet Connection (2) I219-V                              | 22       | 4.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 3.48%   |
| Intel Ethernet Controller I225-V                                  | 16       | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 14       | 2.87%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 2.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 2.25%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7        | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7        | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7        | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5        | 1.02%   |
| Intel Centrino Wireless-N 2230                                    | 5        | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4        | 0.82%   |
| Intel Wireless 8265 / 8275                                        | 4        | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.61%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.61%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.61%   |
| Intel Wireless-AC 9260                                            | 3        | 0.61%   |
| Intel Wireless 7260                                               | 3        | 0.61%   |
| Intel Wireless 3165                                               | 3        | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.61%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 0.61%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 69       | 46.31%  |
| Realtek Semiconductor           | 24       | 16.11%  |
| Qualcomm Atheros                | 21       | 14.09%  |
| Ralink Technology               | 8        | 5.37%   |
| Broadcom                        | 5        | 3.36%   |
| TP-Link                         | 4        | 2.68%   |
| Microsoft                       | 4        | 2.68%   |
| Ralink                          | 3        | 2.01%   |
| Qualcomm Atheros Communications | 3        | 2.01%   |
| D-Link                          | 2        | 1.34%   |
| Broadcom Limited                | 2        | 1.34%   |
| ASUSTek Computer                | 2        | 1.34%   |
| Micro Star International        | 1        | 0.67%   |
| D-Link System                   | 1        | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 22       | 14.67%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 7        | 4.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 7        | 4.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 7        | 4.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5        | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 5        | 3.33%   |
| Intel Centrino Wireless-N 2230                                                                | 5        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 4        | 2.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 4        | 2.67%   |
| Intel Wireless 8265 / 8275                                                                    | 4        | 2.67%   |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 2%      |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 2%      |
| Qualcomm Atheros AR9271 802.11n                                                               | 3        | 2%      |
| Intel Wireless-AC 9260                                                                        | 3        | 2%      |
| Intel Wireless 7260                                                                           | 3        | 2%      |
| Intel Wireless 3165                                                                           | 3        | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 3        | 2%      |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 3        | 2%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3        | 2%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2        | 1.33%   |
| Realtek 802.11ac NIC                                                                          | 2        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 1.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 2        | 1.33%   |
| Microsoft XBOX ACC                                                                            | 2        | 1.33%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                         | 1        | 0.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.67%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1        | 0.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.67%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 0.67%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.67%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 151      | 47.34%  |
| Intel                 | 134      | 42.01%  |
| Qualcomm Atheros      | 12       | 3.76%   |
| Aquantia              | 9        | 2.82%   |
| Samsung Electronics   | 4        | 1.25%   |
| HMD Global            | 2        | 0.63%   |
| Broadcom              | 2        | 0.63%   |
| Xiaomi                | 1        | 0.31%   |
| MediaTek              | 1        | 0.31%   |
| DisplayLink           | 1        | 0.31%   |
| Broadcom Limited      | 1        | 0.31%   |
| Apple                 | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 135      | 40.54%  |
| Intel I211 Gigabit Network Connection                                         | 25       | 7.51%   |
| Intel Ethernet Connection (2) I219-V                                          | 22       | 6.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17       | 5.11%   |
| Intel Ethernet Controller I225-V                                              | 16       | 4.8%    |
| Intel Ethernet Connection I217-LM                                             | 14       | 4.2%    |
| Intel Ethernet Connection (7) I219-V                                          | 14       | 4.2%    |
| Realtek RTL8125 2.5GbE Controller                                             | 11       | 3.3%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 9        | 2.7%    |
| Intel 82579V Gigabit Network Connection                                       | 6        | 1.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 4        | 1.2%    |
| Intel Ethernet Connection I217-V                                              | 4        | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 3        | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 0.9%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3        | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 3        | 0.9%    |
| Intel I210 Gigabit Network Connection                                         | 3        | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.9%    |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 0.9%    |
| Intel Ethernet Connection (14) I219-V                                         | 3        | 0.9%    |
| Intel 82574L Gigabit Network Connection                                       | 3        | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.6%    |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.6%    |
| Intel Ethernet Connection (17) I219-V                                         | 2        | 0.6%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.6%    |
| HMD Global Android                                                            | 2        | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1        | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.3%    |
| MediaTek moto e(6) plus                                                       | 1        | 0.3%    |
| Intel Ethernet Controller I225-LM                                             | 1        | 0.3%    |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.3%    |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.3%    |
| Intel Ethernet Connection (10) I219-V                                         | 1        | 0.3%    |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.3%    |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.3%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.3%    |
| DisplayLink Dell D3100 Docking Station                                        | 1        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 293      | 67.2%   |
| WiFi     | 138      | 31.65%  |
| Modem    | 4        | 0.92%   |
| Unknown  | 1        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 231      | 76.74%  |
| WiFi     | 70       | 23.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 169      | 57.09%  |
| 2     | 99       | 33.45%  |
| 3     | 23       | 7.77%   |
| 5     | 2        | 0.68%   |
| 4     | 2        | 0.68%   |
| 0     | 1        | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 251      | 84.8%   |
| Yes  | 45       | 15.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 68       | 54.84%  |
| Cambridge Silicon Radio         | 21       | 16.94%  |
| Realtek Semiconductor           | 8        | 6.45%   |
| ASUSTek Computer                | 7        | 5.65%   |
| Qualcomm Atheros Communications | 5        | 4.03%   |
| Broadcom                        | 5        | 4.03%   |
| IMC Networks                    | 3        | 2.42%   |
| HTC (High Tech Computer)        | 2        | 1.61%   |
| Micro Star International        | 1        | 0.81%   |
| Lite-On Technology              | 1        | 0.81%   |
| Creative Technology             | 1        | 0.81%   |
| Belkin Components               | 1        | 0.81%   |
| Apple                           | 1        | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 22       | 17.74%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 21       | 16.94%  |
| Intel Bluetooth wireless interface                                   | 13       | 10.48%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 8        | 6.45%   |
| Intel AX201 Bluetooth                                                | 8        | 6.45%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 7        | 5.65%   |
| Intel AX210 Bluetooth                                                | 6        | 4.84%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 5        | 4.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3        | 2.42%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 2.42%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3        | 2.42%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 1.61%   |
| IMC Networks Bluetooth Device                                        | 2        | 1.61%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 1.61%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 2        | 1.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 1.61%   |
| Realtek Bluetooth Radio                                              | 1        | 0.81%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.81%   |
| Qualcomm Atheros Bluetooth (AR3011)                                  | 1        | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.81%   |
| Micro Star International Bluetooth Device                            | 1        | 0.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1        | 0.81%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.81%   |
| Creative Bluetooth Audio W2                                          | 1        | 0.81%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 0.81%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.81%   |
| Belkin Components F8T012 Bluetooth Adapter                           | 1        | 0.81%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.81%   |
| ASUS Bluetooth Device                                                | 1        | 0.81%   |
| ASUS BCM20702A0                                                      | 1        | 0.81%   |
| Apple Bluetooth USB Host Controller                                  | 1        | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 211      | 39.37%  |
| Nvidia                               | 138      | 25.75%  |
| AMD                                  | 109      | 20.34%  |
| C-Media Electronics                  | 12       | 2.24%   |
| ASUSTek Computer                     | 9        | 1.68%   |
| Logitech                             | 6        | 1.12%   |
| Unknown                              | 4        | 0.75%   |
| JMTek                                | 4        | 0.75%   |
| SteelSeries ApS                      | 3        | 0.56%   |
| Micro Star International             | 3        | 0.56%   |
| KORG                                 | 3        | 0.56%   |
| Creative Labs                        | 3        | 0.56%   |
| Corsair                              | 3        | 0.56%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.37%   |
| Creative Technology                  | 2        | 0.37%   |
| Blue Microphones                     | 2        | 0.37%   |
| Yamaha                               | 1        | 0.19%   |
| VIA Technologies                     | 1        | 0.19%   |
| Texas Instruments                    | 1        | 0.19%   |
| TEAC                                 | 1        | 0.19%   |
| Schiit Audio                         | 1        | 0.19%   |
| Samsung Electronics                  | 1        | 0.19%   |
| PreSonus Audio Electronics           | 1        | 0.19%   |
| Plantronics                          | 1        | 0.19%   |
| MAG Technology                       | 1        | 0.19%   |
| Kingston Technology                  | 1        | 0.19%   |
| JBL                                  | 1        | 0.19%   |
| Guillemot                            | 1        | 0.19%   |
| Giga-Byte Technology                 | 1        | 0.19%   |
| Generalplus Technology               | 1        | 0.19%   |
| Focusrite-Novation                   | 1        | 0.19%   |
| DSEA A/S                             | 1        | 0.19%   |
| Cooler Master                        | 1        | 0.19%   |
| Bose                                 | 1        | 0.19%   |
| BEHRINGER International              | 1        | 0.19%   |
| AudioQuest                           | 1        | 0.19%   |
| Audio-Technica                       | 1        | 0.19%   |
| AKAI Professional M.I.               | 1        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 34       | 5.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 31       | 5.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25       | 4.19%   |
| Intel 200 Series PCH HD Audio                                              | 24       | 4.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24       | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20       | 3.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 20       | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20       | 3.35%   |
| Nvidia GP104 High Definition Audio Controller                              | 19       | 3.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18       | 3.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 17       | 2.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 15       | 2.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12       | 2.01%   |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 1.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9        | 1.51%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 1.51%   |
| Nvidia TU106 High Definition Audio Controller                              | 8        | 1.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.34%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 8        | 1.34%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 8        | 1.34%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 1.34%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7        | 1.17%   |
| Intel Comet Lake PCH cAVS                                                  | 7        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7        | 1.17%   |
| Intel Alder Lake-S HD Audio Controller                                     | 7        | 1.17%   |
| ASUSTek Computer USB Audio                                                 | 7        | 1.17%   |
| AMD FCH Azalia Controller                                                  | 7        | 1.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 7        | 1.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 1.01%   |
| Nvidia GK104 HDMI Audio Controller                                         | 6        | 1.01%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6        | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 0.84%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 0.84%   |
| Unknown USB Audio                                                          | 4        | 0.67%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 0.67%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.67%   |
| Logitech G430 Surround Sound Gaming Headset                                | 4        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Corsair           | 4        | 40%     |
| Goldkey           | 2        | 20%     |
| Unknown           | 1        | 10%     |
| SK hynix          | 1        | 10%     |
| Micron Technology | 1        | 10%     |
| Crucial           | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Goldkey RAM GKH400SO51208-1333 4GB DIMM DDR3 1333MT/s     | 2        | 20%     |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s | 1        | 10%     |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 10%     |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 10%     |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM 1600MT/s          | 1        | 10%     |
| Corsair RAM CMY32GX3M4A1600C9 8192MB DIMM DDR3 1600MT/s   | 1        | 10%     |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 1        | 10%     |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s     | 1        | 10%     |
| Corsair RAM CM4X16GC3000C15K4 16GB DIMM DDR4 3000MT/s     | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 5        | 55.56%  |
| DDR4 | 4        | 44.44%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 9        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 4        | 44.44%  |
| 8192  | 3        | 33.33%  |
| 16384 | 2        | 22.22%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 30%     |
| 1333  | 2        | 20%     |
| 3466  | 1        | 10%     |
| 3000  | 1        | 10%     |
| 2933  | 1        | 10%     |
| 2800  | 1        | 10%     |
| 1800  | 1        | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 33.33%  |
| Canon               | 6        | 33.33%  |
| Samsung Electronics | 3        | 16.67%  |
| Seiko Epson         | 1        | 5.56%   |
| Ricoh               | 1        | 5.56%   |
| Dymo-CoStar         | 1        | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Canon PIXMA MG2500 Series            | 2        | 11.11%  |
| Seiko Epson ET-2710 Series           | 1        | 5.56%   |
| Samsung SCX-4216F Scanner            | 1        | 5.56%   |
| Samsung SCX-4200 series              | 1        | 5.56%   |
| Samsung ML-1640 Series Laser Printer | 1        | 5.56%   |
| Ricoh Printing Support               | 1        | 5.56%   |
| HP Laser 107w                        | 1        | 5.56%   |
| HP ENVY Pro 6400 series              | 1        | 5.56%   |
| HP ENVY 6000 series                  | 1        | 5.56%   |
| HP ENVY 4520 series                  | 1        | 5.56%   |
| HP Deskjet 3520 series               | 1        | 5.56%   |
| HP Deskjet 2540 series               | 1        | 5.56%   |
| Dymo-CoStar DYMO LabelWriter 4XL     | 1        | 5.56%   |
| Canon MF3010                         | 1        | 5.56%   |
| Canon LBP6000                        | 1        | 5.56%   |
| Canon iP2700 series                  | 1        | 5.56%   |
| Canon G3010 series                   | 1        | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| HP ScanJet 6200c                   | 1        | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 33.33%  |
| Canon CanoScan 8800F               | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 12       | 31.58%  |
| Microsoft                     | 6        | 15.79%  |
| KYE Systems (Mouse Systems)   | 3        | 7.89%   |
| Samsung Electronics           | 2        | 5.26%   |
| Realtek Semiconductor         | 2        | 5.26%   |
| Hewlett-Packard               | 2        | 5.26%   |
| Creative Technology           | 2        | 5.26%   |
| Apple                         | 2        | 5.26%   |
| Z-Star Microelectronics       | 1        | 2.63%   |
| Sunplus Innovation Technology | 1        | 2.63%   |
| Microdia                      | 1        | 2.63%   |
| Cubeternet                    | 1        | 2.63%   |
| Arkmicro Technologies         | 1        | 2.63%   |
| ARC International             | 1        | 2.63%   |
| Anchor Chips                  | 1        | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 4        | 10.26%  |
| Logitech HD Pro Webcam C920                     | 3        | 7.69%   |
| Samsung Galaxy A5 (MTP)                         | 2        | 5.13%   |
| Microsoft LifeCam HD-3000                       | 2        | 5.13%   |
| Apple iPhone 5/5C/5S/6/SE                       | 2        | 5.13%   |
| Z-Star Venus USB2.0 Camera                      | 1        | 2.56%   |
| Sunplus Sandberg USB Webcam Pro                 | 1        | 2.56%   |
| Realtek NexiGo N960E FHD Webcam                 | 1        | 2.56%   |
| Realtek FULL HD 1080P Webcam                    | 1        | 2.56%   |
| Microsoft LifeCam VX-7000 (UVC-compliant)       | 1        | 2.56%   |
| Microsoft LifeCam VX-700                        | 1        | 2.56%   |
| Microsoft LifeCam Studio                        | 1        | 2.56%   |
| Microsoft LifeCam Cinema                        | 1        | 2.56%   |
| Microdia Sonix USB 2.0 Camera                   | 1        | 2.56%   |
| Logitech Webcam C925e                           | 1        | 2.56%   |
| Logitech QuickCam Zoom                          | 1        | 2.56%   |
| Logitech Logitech Webcam C160                   | 1        | 2.56%   |
| Logitech C922 Pro Stream Webcam                 | 1        | 2.56%   |
| Logitech BRIO 4K Stream Edition                 | 1        | 2.56%   |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam | 1        | 2.56%   |
| KYE Systems (Mouse Systems) eFace 2050AF        | 1        | 2.56%   |
| KYE Systems (Mouse Systems) eFace 2025          | 1        | 2.56%   |
| HP Webcam HD 4310                               | 1        | 2.56%   |
| HP Webcam HD 2300                               | 1        | 2.56%   |
| Cubeternet USB2.0 Camera                        | 1        | 2.56%   |
| Creative Live! Cam Sync HD [VF0770]             | 1        | 2.56%   |
| Creative Live! Cam Chat HD [VF0700]             | 1        | 2.56%   |
| Arkmicro Webcam Carrefour                       | 1        | 2.56%   |
| ARC International Camera                        | 1        | 2.56%   |
| Apple iPod Touch 5.Gen [A1421]                  | 1        | 2.56%   |
| Anchor Chips USB2.0 Camera                      | 1        | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| AuthenTec | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| AuthenTec AES2550 Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 50%     |
| Advanced Card Systems | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |
| Advanced Card Systems ACR1281 1S Dual Reader      | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 233      | 77.67%  |
| 1     | 55       | 18.33%  |
| 2     | 12       | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 21       | 26.25%  |
| Net/ethernet             | 11       | 13.75%  |
| Unassigned class         | 8        | 10%     |
| Sound                    | 8        | 10%     |
| Firewire controller      | 7        | 8.75%   |
| Storage/ide              | 6        | 7.5%    |
| Graphics card            | 5        | 6.25%   |
| Camera                   | 4        | 5%      |
| Network                  | 2        | 2.5%    |
| Multimedia controller    | 2        | 2.5%    |
| Communication controller | 2        | 2.5%    |
| Chipcard                 | 2        | 2.5%    |
| Fingerprint reader       | 1        | 1.25%   |
| Card reader              | 1        | 1.25%   |


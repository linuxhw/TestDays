Linux in Croatia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

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

Total: 227

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B550M Phantom Gaming 4      | [e0158c541c](https://linux-hardware.org/?probe=e0158c541c) | Sep 29, 2023 |
| Gigabyte      | X570S UD                    | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [bd389fb2a0](https://linux-hardware.org/?probe=bd389fb2a0) | Sep 15, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Intel         | DH61CR AAG14064-204         | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| ASRock        | B560 Steel Legend           | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| HP            | 2B47                        | [06373794be](https://linux-hardware.org/?probe=06373794be) | Aug 01, 2023 |
| ASRock        | B450M-HDV R4.0              | [289d9fe165](https://linux-hardware.org/?probe=289d9fe165) | Jun 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| MSI           | PRO Z690-A DDR4             | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| HPE           | ProLiant ML30 Gen10 Plus    | [3a75fa5c03](https://linux-hardware.org/?probe=3a75fa5c03) | May 07, 2023 |
| ASUSTek       | GRYPHON Z87                 | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| ASUSTek       | PRIME B560M-A               | [171e39cdb6](https://linux-hardware.org/?probe=171e39cdb6) | Apr 05, 2023 |
| MSI           | B450M PRO-M2 MAX            | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| ASUSTek       | H110M-R                     | [2409dc15b4](https://linux-hardware.org/?probe=2409dc15b4) | Mar 10, 2023 |
| ASRock        | H97 Pro4                    | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| MSI           | 0A90                        | [9210981559](https://linux-hardware.org/?probe=9210981559) | Feb 06, 2023 |
| MSI           | 0A90                        | [aedd414dbf](https://linux-hardware.org/?probe=aedd414dbf) | Feb 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| ASUSTek       | PRIME B560M-A               | [2b04043ef0](https://linux-hardware.org/?probe=2b04043ef0) | Jan 10, 2023 |
| ASRock        | B550M Steel Legend          | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| ASRock        | K10N78D                     | [b5e2e7a024](https://linux-hardware.org/?probe=b5e2e7a024) | Dec 02, 2022 |
| ASRock        | B550M-ITX/ac                | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| HP            | 1998                        | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| ASUSTek       | PRIME H410M-A               | [b3cac9f8b8](https://linux-hardware.org/?probe=b3cac9f8b8) | Nov 02, 2022 |
| ASUSTek       | PRIME B560M-A               | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| ASUSTek       | M5A78L LE                   | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Lenovo        | 0x30F617AA NOK              | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [0dca3e500c](https://linux-hardware.org/?probe=0dca3e500c) | Sep 22, 2022 |
| ASUSTek       | Z97-PRO                     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5ddb15f201](https://linux-hardware.org/?probe=5ddb15f201) | Aug 07, 2022 |
| HP            | 1825                        | [4a21a02ae4](https://linux-hardware.org/?probe=4a21a02ae4) | Jul 29, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [3c665fb25f](https://linux-hardware.org/?probe=3c665fb25f) | Jul 28, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| ASRock        | K10N78D                     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| WinFast       | NF-MCP55 FAB1.0             | [bb066cc2da](https://linux-hardware.org/?probe=bb066cc2da) | Jul 03, 2022 |
| MSI           | Z87-G41 PC Mate             | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [0d4266a0f3](https://linux-hardware.org/?probe=0d4266a0f3) | Jun 15, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [987ef7b2e7](https://linux-hardware.org/?probe=987ef7b2e7) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Gigabyte      | X48T-DQ6                    | [2953148fae](https://linux-hardware.org/?probe=2953148fae) | May 16, 2022 |
| Dell          | 0J37VM A01                  | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4                | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
| ASRock        | H470M-HDV                   | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | B450 TOMAHAWK               | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| Gigabyte      | P31-ES3G                    | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| Intel         | H61M-S2PV                   | [caa602b556](https://linux-hardware.org/?probe=caa602b556) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| ASRock        | H61M-DGS                    | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| ASRock        | H97 Pro4                    | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Pegatron      | 2AC3                        | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASRock        | A320M-HDV R4.0              | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| Gigabyte      | X48T-DQ6                    | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| ASRock        | B360 Gaming K4              | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| ASUSTek       | Z170-P                      | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| ASRock        | H97 Pro4                    | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                    | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| Foxconn       | 2A8Ch                       | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Gigabyte      | H410M H V3                  | [d0ee45a4b1](https://linux-hardware.org/?probe=d0ee45a4b1) | Feb 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                    | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Gigabyte      | B85M-DS3H                   | [98d6451ac1](https://linux-hardware.org/?probe=98d6451ac1) | Feb 07, 2022 |
| ASRock        | Z97M Pro4                   | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| Foxconn       | 2A8Ch                       | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| ASRock        | Z590 Pro4                   | [a89877d9de](https://linux-hardware.org/?probe=a89877d9de) | Jan 16, 2022 |
| ASRock        | Z590 Pro4                   | [7a2453280a](https://linux-hardware.org/?probe=7a2453280a) | Jan 14, 2022 |
| ECS           | H61H2-M2                    | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Gigabyte      | 965P-DS3                    | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| ECS           | H61H2-M2                    | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| ASRock        | 870 Extreme3                | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| Intel         | DH61CR AAG14064-204         | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204         | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| ASRock        | B450M-HDV R4.0              | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | PRIME A320M-K               | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| Dell          | 0GDG8Y A00                  | [d0cf0cc443](https://linux-hardware.org/?probe=d0cf0cc443) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                       | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| Foxconn       | 2A8Ch                       | [1f650ebd72](https://linux-hardware.org/?probe=1f650ebd72) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [c77e499435](https://linux-hardware.org/?probe=c77e499435) | Nov 13, 2021 |
| ASUSTek       | M4A78T-E                    | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [12bf811a5c](https://linux-hardware.org/?probe=12bf811a5c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | M5A78L LE                   | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Pegatron      | 2A73h                       | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| ASUSTek       | PRIME H410M-R               | [d891006b52](https://linux-hardware.org/?probe=d891006b52) | Oct 14, 2021 |
| ASUSTek       | B85M-E                      | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| ASUSTek       | A58M-K                      | [2ca6ce79db](https://linux-hardware.org/?probe=2ca6ce79db) | Oct 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e5508ac7ab](https://linux-hardware.org/?probe=e5508ac7ab) | Sep 27, 2021 |
| ASUSTek       | M4A78T-E                    | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| MSI           | A320M PRO-VH PLUS           | [149504315f](https://linux-hardware.org/?probe=149504315f) | Aug 10, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| ASRock        | B450M-HDV R4.0              | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| ASRock        | Z370 Pro4                   | [9a9f7c5e69](https://linux-hardware.org/?probe=9a9f7c5e69) | Jul 20, 2021 |
| Gigabyte      | GA-990XA-UD3                | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [83b3cc659a](https://linux-hardware.org/?probe=83b3cc659a) | Jun 07, 2021 |
| Dell          | 06CV2N A01                  | [35a0afd617](https://linux-hardware.org/?probe=35a0afd617) | May 25, 2021 |
| MSI           | B450 TOMAHAWK               | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASRock        | P45DE                       | [2f6b602e36](https://linux-hardware.org/?probe=2f6b602e36) | Apr 18, 2021 |
| ASRock        | Z370 Pro4                   | [7ad77d82ba](https://linux-hardware.org/?probe=7ad77d82ba) | Apr 03, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
| MSI           | B450M PRO-M2 MAX            | [6e5e0c9ef4](https://linux-hardware.org/?probe=6e5e0c9ef4) | Mar 19, 2021 |
| MSI           | Z390-A PRO                  | [12566ee726](https://linux-hardware.org/?probe=12566ee726) | Mar 10, 2021 |
| Gigabyte      | G1.Sniper Z87               | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| ASRock        | FM2A75M-DGS                 | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME A320M-K               | [24a672b8ac](https://linux-hardware.org/?probe=24a672b8ac) | Feb 25, 2021 |
| ASRock        | Z87 Extreme4                | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| Dell          | 0NNGP2 A00                  | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Dell          | 0J37VM A01                  | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [eee7c1f592](https://linux-hardware.org/?probe=eee7c1f592) | Feb 03, 2021 |
| ASRock        | ConRoe1333-D667             | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | [28cb4726bb](https://linux-hardware.org/?probe=28cb4726bb) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | [0b4b751863](https://linux-hardware.org/?probe=0b4b751863) | Jan 31, 2021 |
| ASRock        | X570M Pro4                  | [9cd91004ab](https://linux-hardware.org/?probe=9cd91004ab) | Jan 24, 2021 |
| Gigabyte      | F2A78M-DS2                  | [9afb5c207a](https://linux-hardware.org/?probe=9afb5c207a) | Jan 23, 2021 |
| Dell          | 0DFRFW A01                  | [482bc5334f](https://linux-hardware.org/?probe=482bc5334f) | Jan 22, 2021 |
| MSI           | B450 TOMAHAWK               | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | [df34a7d718](https://linux-hardware.org/?probe=df34a7d718) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | [0d8e905a30](https://linux-hardware.org/?probe=0d8e905a30) | Jan 16, 2021 |
| ASUSTek       | Maximus VII HERO            | [9b72f3a82b](https://linux-hardware.org/?probe=9b72f3a82b) | Jan 11, 2021 |
| ASUSTek       | M4A78T-E                    | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| HP            | 18EA                        | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3                | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| ASUSTek       | H81M-K                      | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| ASRock        | Z370 Pro4                   | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| ASUSTek       | M5A78L LE                   | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L LE                   | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| ASRock        | N68-S3 UCC                  | [b75cfae4a3](https://linux-hardware.org/?probe=b75cfae4a3) | Nov 01, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [ff7ecd0641](https://linux-hardware.org/?probe=ff7ecd0641) | Oct 15, 2020 |
| Pegatron      | 2A94h                       | [668c4bbb8b](https://linux-hardware.org/?probe=668c4bbb8b) | Oct 06, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [b098cfc85e](https://linux-hardware.org/?probe=b098cfc85e) | Sep 30, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [df11954c4f](https://linux-hardware.org/?probe=df11954c4f) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [8220732bda](https://linux-hardware.org/?probe=8220732bda) | Sep 28, 2020 |
| ASUSTek       | M5A78L LE                   | [7f4940b41c](https://linux-hardware.org/?probe=7f4940b41c) | Sep 28, 2020 |
| ASRock        | N68-S3 UCC                  | [42ed26b195](https://linux-hardware.org/?probe=42ed26b195) | Sep 19, 2020 |
| ASUSTek       | M4A77                       | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| ASRock        | Z87E-ITX                    | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASRock        | N68-S3 UCC                  | [a2d99d11fc](https://linux-hardware.org/?probe=a2d99d11fc) | Aug 30, 2020 |
| ASUSTek       | P8H77-V LE                  | [1c2eaa2346](https://linux-hardware.org/?probe=1c2eaa2346) | Aug 23, 2020 |
| HP            | 2129                        | [d1eda00971](https://linux-hardware.org/?probe=d1eda00971) | Aug 20, 2020 |
| MSI           | Z87-G41 PC Mate             | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| Gigabyte      | G41M-Combo                  | [2f3657530f](https://linux-hardware.org/?probe=2f3657530f) | Jun 29, 2020 |
| ASUSTek       | B85M-E                      | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| ASRock        | H97M Pro4                   | [31f3732dc9](https://linux-hardware.org/?probe=31f3732dc9) | Jun 19, 2020 |
| Gigabyte      | G31MX-S2                    | [7da6752573](https://linux-hardware.org/?probe=7da6752573) | May 31, 2020 |
| Gigabyte      | G31MX-S2                    | [5472c53dca](https://linux-hardware.org/?probe=5472c53dca) | May 31, 2020 |
| ASRock        | H81M-DGS R2.0               | [26a9c7f62c](https://linux-hardware.org/?probe=26a9c7f62c) | May 30, 2020 |
| Gigabyte      | 990FXA-UD3                  | [e3042f4583](https://linux-hardware.org/?probe=e3042f4583) | May 24, 2020 |
| ASUSTek       | P8H77-V LE                  | [e6f20d976d](https://linux-hardware.org/?probe=e6f20d976d) | May 17, 2020 |
| Gigabyte      | 965P-DS3                    | [abfb95a938](https://linux-hardware.org/?probe=abfb95a938) | May 11, 2020 |
| Gigabyte      | 965P-DS3                    | [e59e1593d5](https://linux-hardware.org/?probe=e59e1593d5) | May 11, 2020 |
| MSI           | MS-7360                     | [ab94189bcf](https://linux-hardware.org/?probe=ab94189bcf) | May 07, 2020 |
| MSI           | Z87-G41 PC Mate             | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | 3031h                       | [b4638888cb](https://linux-hardware.org/?probe=b4638888cb) | Apr 14, 2020 |
| ASUSTek       | M5A78L LE                   | [1562c544a6](https://linux-hardware.org/?probe=1562c544a6) | Apr 14, 2020 |
| ASRock        | H61M-DGS                    | [0a090881ae](https://linux-hardware.org/?probe=0a090881ae) | Apr 12, 2020 |
| ASUSTek       | A8V-MQ                      | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| ASRock        | H61M-VS                     | [799e1670fd](https://linux-hardware.org/?probe=799e1670fd) | Mar 18, 2020 |
| HP            | 212B                        | [6058dd53b1](https://linux-hardware.org/?probe=6058dd53b1) | Mar 16, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [26545c7add](https://linux-hardware.org/?probe=26545c7add) | Feb 24, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [1693523c61](https://linux-hardware.org/?probe=1693523c61) | Feb 21, 2020 |
| Intel         | DH67BL AAG10189-213         | [b0e9895bef](https://linux-hardware.org/?probe=b0e9895bef) | Feb 16, 2020 |
| ASRock        | B150M-HDV                   | [c08c6d0574](https://linux-hardware.org/?probe=c08c6d0574) | Feb 08, 2020 |
| HP            | 18E7                        | [de846e5f4f](https://linux-hardware.org/?probe=de846e5f4f) | Jan 22, 2020 |
| Intel         | DH67BL AAG10189-213         | [9ed2076b0d](https://linux-hardware.org/?probe=9ed2076b0d) | Jan 18, 2020 |
| Intel         | DH67BL AAG10189-213         | [dc121e5512](https://linux-hardware.org/?probe=dc121e5512) | Jan 18, 2020 |
| Acer          | Veriton S680G               | [277889b2ff](https://linux-hardware.org/?probe=277889b2ff) | Jan 15, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [e097415087](https://linux-hardware.org/?probe=e097415087) | Dec 26, 2019 |
| ASRock        | N68-S3 UCC                  | [9cbd6c2e0e](https://linux-hardware.org/?probe=9cbd6c2e0e) | Dec 25, 2019 |
| ASRock        | 990FX Extreme3              | [107280e5a9](https://linux-hardware.org/?probe=107280e5a9) | Dec 23, 2019 |
| ASRock        | 990FX Extreme3              | [66a084d547](https://linux-hardware.org/?probe=66a084d547) | Dec 11, 2019 |
| ASRock        | H97 Killer                  | [8538b88e3d](https://linux-hardware.org/?probe=8538b88e3d) | Nov 27, 2019 |
| ASRock        | 970 Pro3 R2.0               | [73c6829ffb](https://linux-hardware.org/?probe=73c6829ffb) | Nov 27, 2019 |
| HP            | 18EA                        | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| ASRock        | A320M-HDV R3.0              | [d3d79c2a8d](https://linux-hardware.org/?probe=d3d79c2a8d) | Sep 16, 2019 |
| Gigabyte      | A320M-H-CF                  | [a35aea421b](https://linux-hardware.org/?probe=a35aea421b) | Sep 09, 2019 |
| Intel         | DX58SO AAE29331-501         | [349ef8982a](https://linux-hardware.org/?probe=349ef8982a) | Sep 09, 2019 |
| Gigabyte      | A320M-H-CF                  | [59782a89ea](https://linux-hardware.org/?probe=59782a89ea) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | [b4ef0f5499](https://linux-hardware.org/?probe=b4ef0f5499) | Sep 05, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | [be3a07802c](https://linux-hardware.org/?probe=be3a07802c) | Aug 13, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | [9cdd546881](https://linux-hardware.org/?probe=9cdd546881) | Jul 29, 2019 |
| ASRock        | A300M-STX                   | [edf300f175](https://linux-hardware.org/?probe=edf300f175) | Jul 29, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | [aad0551e27](https://linux-hardware.org/?probe=aad0551e27) | Jul 25, 2019 |
| ASUSTek       | E35M1-M                     | [1b78cc518f](https://linux-hardware.org/?probe=1b78cc518f) | Jul 08, 2019 |
| ASUSTek       | E35M1-M                     | [1f5e6b026b](https://linux-hardware.org/?probe=1f5e6b026b) | Jun 23, 2019 |
| ASUSTek       | PRIME A320M-K               | [f8c4365b6c](https://linux-hardware.org/?probe=f8c4365b6c) | Jun 07, 2019 |
| ASUSTek       | PRIME A320M-K               | [3968b06d9c](https://linux-hardware.org/?probe=3968b06d9c) | Jun 07, 2019 |
| HP            | 83ED                        | [532b72754e](https://linux-hardware.org/?probe=532b72754e) | May 06, 2019 |
| Gigabyte      | Z77P-D3                     | [e7259783d1](https://linux-hardware.org/?probe=e7259783d1) | Apr 13, 2019 |
| Pegatron      | 2A99                        | [196712630c](https://linux-hardware.org/?probe=196712630c) | Feb 26, 2019 |
| ASUSTek       | B150M-C                     | [88898f6797](https://linux-hardware.org/?probe=88898f6797) | Feb 10, 2019 |
| ECS           | A770M-A                     | [feacfccf11](https://linux-hardware.org/?probe=feacfccf11) | Feb 05, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [bf1298d356](https://linux-hardware.org/?probe=bf1298d356) | Jan 29, 2019 |
| ABIT          | IP35-E                      | [87b22d6a66](https://linux-hardware.org/?probe=87b22d6a66) | Jan 26, 2019 |
| Gigabyte      | AX370-Gaming K7             | [bc26ed35a0](https://linux-hardware.org/?probe=bc26ed35a0) | Dec 08, 2018 |
| Unknown       | Grantsdale                  | [65da6a461b](https://linux-hardware.org/?probe=65da6a461b) | Nov 21, 2018 |
| Pegatron      | 2AB6                        | [00a8407210](https://linux-hardware.org/?probe=00a8407210) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 20       | 11.83%  |
| Ubuntu 18.04                 | 14       | 8.28%   |
| Debian 11                    | 7        | 4.14%   |
| OpenMandriva 4.3             | 6        | 3.55%   |
| Linux Mint 20.3              | 6        | 3.55%   |
| Linux Mint 20.2              | 6        | 3.55%   |
| Ubuntu 18.10                 | 5        | 2.96%   |
| Zorin 16                     | 4        | 2.37%   |
| Ubuntu 22.04                 | 4        | 2.37%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 2.37%   |
| Fedora 38                    | 4        | 2.37%   |
| Debian 10                    | 4        | 2.37%   |
| Ubuntu MATE 22.04            | 3        | 1.78%   |
| Ubuntu 19.10                 | 3        | 1.78%   |
| Pop!_OS 21.10                | 3        | 1.78%   |
| OpenMandriva 4.2             | 3        | 1.78%   |
| Manjaro                      | 3        | 1.78%   |
| Fedora 31                    | 3        | 1.78%   |
| Ubuntu 21.04                 | 2        | 1.18%   |
| Pop!_OS 20.10                | 2        | 1.18%   |
| openSUSE Leap-15.2           | 2        | 1.18%   |
| OpenMandriva 4.50            | 2        | 1.18%   |
| OpenMandriva 23.03           | 2        | 1.18%   |
| Linux Mint 20                | 2        | 1.18%   |
| KDE neon 20.04               | 2        | 1.18%   |
| EndeavourOS Rolling          | 2        | 1.18%   |
| ArcoLinux Rolling            | 2        | 1.18%   |
| Zorin 15                     | 1        | 0.59%   |
| Xubuntu 20.04                | 1        | 0.59%   |
| Xubuntu 18.04                | 1        | 0.59%   |
| Ubuntu Unity 18.04           | 1        | 0.59%   |
| Ubuntu MATE 20.04            | 1        | 0.59%   |
| Ubuntu MATE 19.10            | 1        | 0.59%   |
| Ubuntu Budgie 22.04          | 1        | 0.59%   |
| Ubuntu Budgie 20.04          | 1        | 0.59%   |
| Ubuntu Budgie 18.04          | 1        | 0.59%   |
| Ubuntu 22.10                 | 1        | 0.59%   |
| Ubuntu 21.10                 | 1        | 0.59%   |
| Ubuntu 20.10                 | 1        | 0.59%   |
| Ubuntu 17.10                 | 1        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 52       | 32.91%  |
| Linux Mint    | 17       | 10.76%  |
| OpenMandriva  | 14       | 8.86%   |
| Debian        | 10       | 6.33%   |
| Pop!_OS       | 8        | 5.06%   |
| Manjaro       | 8        | 5.06%   |
| Fedora        | 8        | 5.06%   |
| openSUSE      | 6        | 3.8%    |
| Zorin         | 5        | 3.16%   |
| Ubuntu MATE   | 3        | 1.9%    |
| Ubuntu Budgie | 3        | 1.9%    |
| KDE neon      | 3        | 1.9%    |
| Xubuntu       | 2        | 1.27%   |
| Gentoo        | 2        | 1.27%   |
| EndeavourOS   | 2        | 1.27%   |
| ArcoLinux     | 2        | 1.27%   |
| Arch          | 2        | 1.27%   |
| Ubuntu Unity  | 1        | 0.63%   |
| ROSA          | 1        | 0.63%   |
| Nobara        | 1        | 0.63%   |
| MX            | 1        | 0.63%   |
| Lubuntu       | 1        | 0.63%   |
| LMDE          | 1        | 0.63%   |
| LinuxFX       | 1        | 0.63%   |
| Kubuntu       | 1        | 0.63%   |
| Endless       | 1        | 0.63%   |
| Elementary    | 1        | 0.63%   |
| Clear Linux   | 1        | 0.63%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003      | 6        | 3.21%   |
| 5.4.0-58-generic             | 4        | 2.14%   |
| 6.2.9-300.fc38.x86_64        | 3        | 1.6%    |
| 5.4.0-91-generic             | 3        | 1.6%    |
| 5.3.0-26-generic             | 3        | 1.6%    |
| 5.10.14-desktop-1omv4002     | 3        | 1.6%    |
| 5.0.0-27-generic             | 3        | 1.6%    |
| 6.2.6-desktop-1omv2390       | 2        | 1.07%   |
| 5.8.0-48-generic             | 2        | 1.07%   |
| 5.4.0-48-generic             | 2        | 1.07%   |
| 5.4.0-42-generic             | 2        | 1.07%   |
| 5.4.0-26-generic             | 2        | 1.07%   |
| 5.4.0-100-generic            | 2        | 1.07%   |
| 5.3.0-42-generic             | 2        | 1.07%   |
| 5.3.0-28-generic             | 2        | 1.07%   |
| 5.15.0-52-generic            | 2        | 1.07%   |
| 5.15.0-48-generic            | 2        | 1.07%   |
| 5.13.0-40-generic            | 2        | 1.07%   |
| 5.12.4-desktop-1omv4050      | 2        | 1.07%   |
| 5.11.0-41-generic            | 2        | 1.07%   |
| 5.11.0-38-generic            | 2        | 1.07%   |
| 5.11.0-37-generic            | 2        | 1.07%   |
| 5.10.0-13-amd64              | 2        | 1.07%   |
| 4.19.0-14-amd64              | 2        | 1.07%   |
| 4.18.0-10-generic            | 2        | 1.07%   |
| 4.15.0-45-generic            | 2        | 1.07%   |
| 4.15.0-20-generic            | 2        | 1.07%   |
| 6.5.4-1-default              | 1        | 0.53%   |
| 6.4.15-200.fc38.x86_64       | 1        | 0.53%   |
| 6.4.11-desktop-1omv2390      | 1        | 0.53%   |
| 6.3.4-zen1-1-zen             | 1        | 0.53%   |
| 6.3.13-2-MANJARO             | 1        | 0.53%   |
| 6.2.14-300.fsync.fc37.x86_64 | 1        | 0.53%   |
| 6.1.8-201.fsync.fc37.x86_64  | 1        | 0.53%   |
| 6.1.38-gentoo-dist           | 1        | 0.53%   |
| 6.1.0-12-amd64               | 1        | 0.53%   |
| 6.0.6-zen1-1-zen             | 1        | 0.53%   |
| 6.0.5-4-rt14-MANJARO         | 1        | 0.53%   |
| 5.9.0-0.bpo.5-amd64          | 1        | 0.53%   |
| 5.8.0-59-generic             | 1        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 18.86%  |
| 5.11.0  | 12       | 6.86%   |
| 5.3.0   | 11       | 6.29%   |
| 4.15.0  | 10       | 5.71%   |
| 5.15.0  | 8        | 4.57%   |
| 5.10.0  | 8        | 4.57%   |
| 4.18.0  | 8        | 4.57%   |
| 5.16.7  | 6        | 3.43%   |
| 5.13.0  | 6        | 3.43%   |
| 5.8.0   | 5        | 2.86%   |
| 5.0.0   | 4        | 2.29%   |
| 6.2.9   | 3        | 1.71%   |
| 5.12.4  | 3        | 1.71%   |
| 5.10.14 | 3        | 1.71%   |
| 4.19.0  | 3        | 1.71%   |
| 6.2.6   | 2        | 1.14%   |
| 5.3.18  | 2        | 1.14%   |
| 5.19.0  | 2        | 1.14%   |
| 5.16.11 | 2        | 1.14%   |
| 6.5.4   | 1        | 0.57%   |
| 6.4.15  | 1        | 0.57%   |
| 6.4.11  | 1        | 0.57%   |
| 6.3.4   | 1        | 0.57%   |
| 6.3.13  | 1        | 0.57%   |
| 6.2.14  | 1        | 0.57%   |
| 6.1.8   | 1        | 0.57%   |
| 6.1.38  | 1        | 0.57%   |
| 6.1.0   | 1        | 0.57%   |
| 6.0.6   | 1        | 0.57%   |
| 6.0.5   | 1        | 0.57%   |
| 5.9.0   | 1        | 0.57%   |
| 5.7.11  | 1        | 0.57%   |
| 5.7.0   | 1        | 0.57%   |
| 5.6.12  | 1        | 0.57%   |
| 5.4.64  | 1        | 0.57%   |
| 5.4.20  | 1        | 0.57%   |
| 5.4.2   | 1        | 0.57%   |
| 5.4.18  | 1        | 0.57%   |
| 5.3.16  | 1        | 0.57%   |
| 5.19.2  | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 21.39%  |
| 5.10    | 15       | 8.67%   |
| 5.3     | 14       | 8.09%   |
| 5.15    | 13       | 7.51%   |
| 5.11    | 13       | 7.51%   |
| 4.15    | 10       | 5.78%   |
| 5.16    | 8        | 4.62%   |
| 4.18    | 8        | 4.62%   |
| 6.2     | 6        | 3.47%   |
| 5.13    | 6        | 3.47%   |
| 5.8     | 5        | 2.89%   |
| 5.19    | 5        | 2.89%   |
| 5.0     | 4        | 2.31%   |
| 6.1     | 3        | 1.73%   |
| 5.18    | 3        | 1.73%   |
| 5.12    | 3        | 1.73%   |
| 4.19    | 3        | 1.73%   |
| 6.4     | 2        | 1.16%   |
| 6.3     | 2        | 1.16%   |
| 6.0     | 2        | 1.16%   |
| 5.7     | 2        | 1.16%   |
| 5.17    | 2        | 1.16%   |
| 5.14    | 2        | 1.16%   |
| 6.5     | 1        | 0.58%   |
| 5.9     | 1        | 0.58%   |
| 5.6     | 1        | 0.58%   |
| 4.14    | 1        | 0.58%   |
| 4.13    | 1        | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 151      | 98.69%  |
| i686   | 2        | 1.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 61       | 38.61%  |
| KDE5       | 33       | 20.89%  |
| Unknown    | 22       | 13.92%  |
| X-Cinnamon | 10       | 6.33%   |
| XFCE       | 8        | 5.06%   |
| MATE       | 5        | 3.16%   |
| KDE        | 4        | 2.53%   |
| Cinnamon   | 4        | 2.53%   |
| Budgie     | 3        | 1.9%    |
| Unity      | 1        | 0.63%   |
| ubuntu     | 1        | 0.63%   |
| Pantheon   | 1        | 0.63%   |
| openbox    | 1        | 0.63%   |
| LXQt       | 1        | 0.63%   |
| LXDE       | 1        | 0.63%   |
| i3         | 1        | 0.63%   |
| DWM        | 1        | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 128      | 81.01%  |
| Wayland | 15       | 9.49%   |
| Unknown | 10       | 6.33%   |
| Tty     | 5        | 3.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 53.75%  |
| SDDM    | 28       | 17.5%   |
| LightDM | 17       | 10.63%  |
| GDM3    | 13       | 8.13%   |
| GDM     | 12       | 7.5%    |
| TDM     | 4        | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 83       | 52.53%  |
| hr_HR   | 41       | 25.95%  |
| Unknown | 25       | 15.82%  |
| en_GB   | 7        | 4.43%   |
| C       | 2        | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 85       | 55.19%  |
| EFI  | 69       | 44.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 118      | 75.16%  |
| Btrfs   | 16       | 10.19%  |
| Overlay | 15       | 9.55%   |
| Unknown | 4        | 2.55%   |
| Zfs     | 3        | 1.91%   |
| Xfs     | 1        | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 89       | 57.05%  |
| GPT     | 49       | 31.41%  |
| MBR     | 18       | 11.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 77.99%  |
| Yes       | 35       | 22.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 61.78%  |
| Yes       | 60       | 38.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 38       | 24.84%  |
| ASRock              | 38       | 24.84%  |
| Gigabyte Technology | 28       | 18.3%   |
| MSI                 | 13       | 8.5%    |
| Hewlett-Packard     | 9        | 5.88%   |
| Pegatron            | 5        | 3.27%   |
| Intel               | 5        | 3.27%   |
| Dell                | 4        | 2.61%   |
| Lenovo              | 3        | 1.96%   |
| ECS                 | 3        | 1.96%   |
| WinFast             | 1        | 0.65%   |
| HPE                 | 1        | 0.65%   |
| Fujitsu Siemens     | 1        | 0.65%   |
| Foxconn             | 1        | 0.65%   |
| Acer                | 1        | 0.65%   |
| ABIT                | 1        | 0.65%   |
| Unknown             | 1        | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 6        | 3.92%   |
| ASUS PRIME A320M-K                     | 3        | 1.96%   |
| ASRock B450M-HDV R4.0                  | 3        | 1.96%   |
| MSI MS-7850                            | 2        | 1.31%   |
| Intel DH61CR AAG14064-204              | 2        | 1.31%   |
| Gigabyte A320M-S2H                     | 2        | 1.31%   |
| ASUS P8H77-V LE                        | 2        | 1.31%   |
| ASUS M5A78L LE                         | 2        | 1.31%   |
| ASRock H61M-DGS                        | 2        | 1.31%   |
| WinFast N570SM2AA                      | 1        | 0.65%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.65%   |
| Pegatron HPE-520ad                     | 1        | 0.65%   |
| Pegatron G5261de                       | 1        | 0.65%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 0.65%   |
| Pegatron 27-1001eu                     | 1        | 0.65%   |
| MSI MS-7D40                            | 1        | 0.65%   |
| MSI MS-7D25                            | 1        | 0.65%   |
| MSI MS-7C02                            | 1        | 0.65%   |
| MSI MS-7B98                            | 1        | 0.65%   |
| MSI MS-7B84                            | 1        | 0.65%   |
| MSI MS-7B07                            | 1        | 0.65%   |
| MSI MS-7817                            | 1        | 0.65%   |
| MSI MS-7681                            | 1        | 0.65%   |
| MSI MS-7586                            | 1        | 0.65%   |
| MSI MS-7360                            | 1        | 0.65%   |
| MSI 0A90                               | 1        | 0.65%   |
| Lenovo ThinkStation P310 30AT0029GE    | 1        | 0.65%   |
| Lenovo ThinkCentre A58 77057FG         | 1        | 0.65%   |
| Lenovo S510                            | 1        | 0.65%   |
| Intel H61M-S2PV                        | 1        | 0.65%   |
| Intel DX58SO AAE29331-501              | 1        | 0.65%   |
| Intel DH67BL AAG10189-213              | 1        | 0.65%   |
| HPE ProLiant ML30 Gen10 Plus           | 1        | 0.65%   |
| HP Z840 Workstation                    | 1        | 0.65%   |
| HP Z440 Workstation                    | 1        | 0.65%   |
| HP ProOne 400 G1 AiO                   | 1        | 0.65%   |
| HP ProDesk 600 G4 PCI MT               | 1        | 0.65%   |
| HP ProDesk 600 G1 SFF                  | 1        | 0.65%   |
| HP EliteDesk 800 G1 SFF                | 1        | 0.65%   |
| HP EliteDesk 800 G1 DM                 | 1        | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 8        | 5.23%   |
| ASUS All            | 6        | 3.92%   |
| ASUS TUF            | 4        | 2.61%   |
| Dell Vostro         | 3        | 1.96%   |
| ASUS ROG            | 3        | 1.96%   |
| ASRock B450M-HDV    | 3        | 1.96%   |
| MSI MS-7850         | 2        | 1.31%   |
| Intel DH61CR        | 2        | 1.31%   |
| HP ProDesk          | 2        | 1.31%   |
| HP EliteDesk        | 2        | 1.31%   |
| Gigabyte Z390       | 2        | 1.31%   |
| Gigabyte B450       | 2        | 1.31%   |
| Gigabyte A320M-S2H  | 2        | 1.31%   |
| ASUS P8H77-V        | 2        | 1.31%   |
| ASUS M5A78L         | 2        | 1.31%   |
| ASRock H97          | 2        | 1.31%   |
| ASRock H61M-DGS     | 2        | 1.31%   |
| ASRock B550M        | 2        | 1.31%   |
| ASRock A320M-HDV    | 2        | 1.31%   |
| WinFast N570SM2AA   | 1        | 0.65%   |
| Pegatron Pro        | 1        | 0.65%   |
| Pegatron HPE-520ad  | 1        | 0.65%   |
| Pegatron G5261de    | 1        | 0.65%   |
| Pegatron Compaq     | 1        | 0.65%   |
| Pegatron 27-1001eu  | 1        | 0.65%   |
| MSI MS-7D40         | 1        | 0.65%   |
| MSI MS-7D25         | 1        | 0.65%   |
| MSI MS-7C02         | 1        | 0.65%   |
| MSI MS-7B98         | 1        | 0.65%   |
| MSI MS-7B84         | 1        | 0.65%   |
| MSI MS-7B07         | 1        | 0.65%   |
| MSI MS-7817         | 1        | 0.65%   |
| MSI MS-7681         | 1        | 0.65%   |
| MSI MS-7586         | 1        | 0.65%   |
| MSI MS-7360         | 1        | 0.65%   |
| MSI 0A90            | 1        | 0.65%   |
| Lenovo ThinkStation | 1        | 0.65%   |
| Lenovo ThinkCentre  | 1        | 0.65%   |
| Lenovo S510         | 1        | 0.65%   |
| Intel H61M-S2PV     | 1        | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 18       | 11.76%  |
| 2018 | 15       | 9.8%    |
| 2017 | 13       | 8.5%    |
| 2012 | 13       | 8.5%    |
| 2011 | 13       | 8.5%    |
| 2020 | 12       | 7.84%   |
| 2021 | 10       | 6.54%   |
| 2009 | 9        | 5.88%   |
| 2019 | 8        | 5.23%   |
| 2014 | 8        | 5.23%   |
| 2015 | 7        | 4.58%   |
| 2010 | 7        | 4.58%   |
| 2008 | 7        | 4.58%   |
| 2007 | 5        | 3.27%   |
| 2022 | 4        | 2.61%   |
| 2006 | 2        | 1.31%   |
| 2005 | 2        | 1.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 153      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 147      | 95.45%  |
| Enabled  | 7        | 4.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 153      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 42       | 26.75%  |
| 16.01-24.0  | 40       | 25.48%  |
| 4.01-8.0    | 25       | 15.92%  |
| 3.01-4.0    | 19       | 12.1%   |
| 32.01-64.0  | 18       | 11.46%  |
| 1.01-2.0    | 6        | 3.82%   |
| 64.01-256.0 | 4        | 2.55%   |
| 24.01-32.0  | 2        | 1.27%   |
| 2.01-3.0    | 1        | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 65       | 38.46%  |
| 2.01-3.0   | 44       | 26.04%  |
| 4.01-8.0   | 24       | 14.2%   |
| 3.01-4.0   | 18       | 10.65%  |
| 0.51-1.0   | 8        | 4.73%   |
| 8.01-16.0  | 5        | 2.96%   |
| 16.01-24.0 | 4        | 2.37%   |
| 0.01-0.5   | 1        | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 34.57%  |
| 2      | 49       | 30.25%  |
| 3      | 29       | 17.9%   |
| 4      | 13       | 8.02%   |
| 5      | 9        | 5.56%   |
| 6      | 2        | 1.23%   |
| 0      | 2        | 1.23%   |
| 8      | 1        | 0.62%   |
| 7      | 1        | 0.62%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 50.32%  |
| Yes       | 77       | 49.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 150      | 98.04%  |
| No        | 3        | 1.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 63.87%  |
| Yes       | 56       | 36.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 78.71%  |
| Yes       | 33       | 21.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Croatia | 153      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Zagreb          | 81       | 47.93%  |
| Split           | 13       | 7.69%   |
| Rijeka          | 9        | 5.33%   |
| Velika Gorica   | 4        | 2.37%   |
| Pula            | 4        | 2.37%   |
| Osijek          | 4        | 2.37%   |
| Varaždin       | 3        | 1.78%   |
| Samobor         | 3        | 1.78%   |
| Koprivnica      | 3        | 1.78%   |
| Zaprešić      | 2        | 1.18%   |
| Virovitica      | 2        | 1.18%   |
| Slatina         | 2        | 1.18%   |
| Pitomaca        | 2        | 1.18%   |
| Ivanja Reka     | 2        | 1.18%   |
| GJurgevac       | 2        | 1.18%   |
| Bjelovar        | 2        | 1.18%   |
| Zadar           | 1        | 0.59%   |
| Visnjevac       | 1        | 0.59%   |
| Supetar         | 1        | 0.59%   |
| Stari Perkovci  | 1        | 0.59%   |
| Skrad           | 1        | 0.59%   |
| Sisak           | 1        | 0.59%   |
| Sesvete         | 1        | 0.59%   |
| Raslina         | 1        | 0.59%   |
| Prelog          | 1        | 0.59%   |
| Postira         | 1        | 0.59%   |
| Novi Marof      | 1        | 0.59%   |
| Nerezine        | 1        | 0.59%   |
| Matulji         | 1        | 0.59%   |
| Mali Lošinj    | 1        | 0.59%   |
| Mahicno         | 1        | 0.59%   |
| Lovran          | 1        | 0.59%   |
| Labin           | 1        | 0.59%   |
| Kućan Marof    | 1        | 0.59%   |
| Krizevci        | 1        | 0.59%   |
| Krapina         | 1        | 0.59%   |
| Kastel Gomilica | 1        | 0.59%   |
| Hvar            | 1        | 0.59%   |
| Grad            | 1        | 0.59%   |
| Galgovo         | 1        | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 70       | 128    | 24.73%  |
| Samsung Electronics         | 34       | 56     | 12.01%  |
| Kingston                    | 34       | 51     | 12.01%  |
| Seagate                     | 29       | 43     | 10.25%  |
| Toshiba                     | 21       | 35     | 7.42%   |
| Crucial                     | 16       | 22     | 5.65%   |
| Intel                       | 11       | 13     | 3.89%   |
| A-DATA Technology           | 11       | 15     | 3.89%   |
| SanDisk                     | 5        | 8      | 1.77%   |
| Patriot                     | 5        | 8      | 1.77%   |
| Hitachi                     | 5        | 8      | 1.77%   |
| Transcend                   | 3        | 7      | 1.06%   |
| Silicon Motion              | 3        | 4      | 1.06%   |
| Phison                      | 3        | 3      | 1.06%   |
| OCZ                         | 2        | 3      | 0.71%   |
| Maxtor                      | 2        | 2      | 0.71%   |
| HPE                         | 2        | 4      | 0.71%   |
| Gigabyte Technology         | 2        | 2      | 0.71%   |
| Corsair                     | 2        | 2      | 0.71%   |
| XPG                         | 1        | 3      | 0.35%   |
| Unknown                     | 1        | 1      | 0.35%   |
| TO Exter                    | 1        | 1      | 0.35%   |
| SPCC                        | 1        | 1      | 0.35%   |
| Realtek Semiconductor       | 1        | 1      | 0.35%   |
| PNY                         | 1        | 1      | 0.35%   |
| Netac                       | 1        | 1      | 0.35%   |
| Mushkin                     | 1        | 2      | 0.35%   |
| Min Yi U                    | 1        | 1      | 0.35%   |
| Micron/Crucial Technology   | 1        | 1      | 0.35%   |
| Micron Technology           | 1        | 1      | 0.35%   |
| Kingston Technology Company | 1        | 1      | 0.35%   |
| KingSpec                    | 1        | 1      | 0.35%   |
| Kingmax                     | 1        | 1      | 0.35%   |
| INNOVATION IT               | 1        | 1      | 0.35%   |
| HGST HTS                    | 1        | 1      | 0.35%   |
| HGST                        | 1        | 1      | 0.35%   |
| GOODRAM                     | 1        | 1      | 0.35%   |
| External                    | 1        | 1      | 0.35%   |
| China                       | 1        | 1      | 0.35%   |
| ASMedia                     | 1        | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD   | 6        | 1.82%   |
| Kingston SV300S37A120G 120GB SSD  | 5        | 1.52%   |
| Kingston SA400S37240G 240GB SSD   | 5        | 1.52%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4        | 1.22%   |
| Toshiba HDWD130 3TB               | 4        | 1.22%   |
| Toshiba HDWD110 1TB               | 4        | 1.22%   |
| Samsung SSD 850 EVO 250GB         | 4        | 1.22%   |
| Kingston SA400S37120G 120GB SSD   | 4        | 1.22%   |
| WDC WD5000AAKX-001CA0 500GB       | 3        | 0.91%   |
| Toshiba DT01ACA100 1TB            | 3        | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 0.91%   |
| SanDisk SDSSDA240G 240GB          | 3        | 0.91%   |
| Samsung SSD 970 EVO Plus 1TB      | 3        | 0.91%   |
| Samsung HD103SI 1TB               | 3        | 0.91%   |
| Patriot Burst 240GB SSD           | 3        | 0.91%   |
| Intel SSDSC2BW120A4 120GB         | 3        | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 2        | 0.61%   |
| WDC WD6400AAKS-22A7B0 640GB       | 2        | 0.61%   |
| WDC WD5003ABYX-88 LEN 500GB       | 2        | 0.61%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 0.61%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 2        | 0.61%   |
| WDC WD3200AAKS-00L9A0 320GB       | 2        | 0.61%   |
| WDC WD30EZRX-00AZ6B0 3TB          | 2        | 0.61%   |
| WDC WD30EFRX-68EUZN0 3TB          | 2        | 0.61%   |
| WDC WD2500AVJS-63WDA0 250GB       | 2        | 0.61%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 2        | 0.61%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.61%   |
| WDC WD1600AAJS-07M0A0 160GB       | 2        | 0.61%   |
| Toshiba MQ01ABD100 1TB            | 2        | 0.61%   |
| Toshiba HDWD240 4TB               | 2        | 0.61%   |
| Toshiba HDWD120 2TB               | 2        | 0.61%   |
| Toshiba DT01ACA300 3TB            | 2        | 0.61%   |
| Seagate ST3160815AS 160GB         | 2        | 0.61%   |
| Seagate ST31000528AS 1TB          | 2        | 0.61%   |
| Seagate ST31000524AS 1TB          | 2        | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB    | 2        | 0.61%   |
| Seagate ST10000DM0004-1ZC101 10TB | 2        | 0.61%   |
| Samsung SSD 860 QVO 1TB           | 2        | 0.61%   |
| Samsung SSD 860 PRO 256GB         | 2        | 0.61%   |
| Samsung SSD 860 EVO 250GB         | 2        | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 68       | 119    | 49.28%  |
| Seagate             | 28       | 42     | 20.29%  |
| Toshiba             | 21       | 35     | 15.22%  |
| Samsung Electronics | 7        | 9      | 5.07%   |
| Hitachi             | 5        | 8      | 3.62%   |
| Maxtor              | 2        | 2      | 1.45%   |
| Unknown             | 1        | 1      | 0.72%   |
| Min Yi U            | 1        | 1      | 0.72%   |
| HPE                 | 1        | 2      | 0.72%   |
| HGST HTS            | 1        | 1      | 0.72%   |
| HGST                | 1        | 1      | 0.72%   |
| External            | 1        | 1      | 0.72%   |
| ASMedia             | 1        | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 31       | 43     | 28.7%   |
| Samsung Electronics | 17       | 26     | 15.74%  |
| Crucial             | 14       | 19     | 12.96%  |
| Intel               | 9        | 11     | 8.33%   |
| A-DATA Technology   | 9        | 12     | 8.33%   |
| Patriot             | 4        | 7      | 3.7%    |
| SanDisk             | 3        | 5      | 2.78%   |
| WDC                 | 2        | 2      | 1.85%   |
| Transcend           | 2        | 2      | 1.85%   |
| OCZ                 | 2        | 3      | 1.85%   |
| Gigabyte Technology | 2        | 2      | 1.85%   |
| TO Exter            | 1        | 1      | 0.93%   |
| SPCC                | 1        | 1      | 0.93%   |
| Seagate             | 1        | 1      | 0.93%   |
| PNY                 | 1        | 1      | 0.93%   |
| Netac               | 1        | 1      | 0.93%   |
| Mushkin             | 1        | 2      | 0.93%   |
| KingSpec            | 1        | 1      | 0.93%   |
| Kingmax             | 1        | 1      | 0.93%   |
| INNOVATION IT       | 1        | 1      | 0.93%   |
| GOODRAM             | 1        | 1      | 0.93%   |
| Corsair             | 1        | 1      | 0.93%   |
| China               | 1        | 1      | 0.93%   |
| AMD                 | 1        | 2      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 108      | 223    | 45.57%  |
| SSD     | 88       | 147    | 37.13%  |
| NVMe    | 40       | 69     | 16.88%  |
| Unknown | 1        | 2      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 137      | 363    | 74.46%  |
| NVMe | 40       | 69     | 21.74%  |
| SAS  | 7        | 9      | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 111      | 209    | 53.37%  |
| 0.51-1.0   | 54       | 90     | 25.96%  |
| 1.01-2.0   | 19       | 30     | 9.13%   |
| 2.01-3.0   | 13       | 27     | 6.25%   |
| 3.01-4.0   | 8        | 10     | 3.85%   |
| 4.01-10.0  | 3        | 4      | 1.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 46       | 27.54%  |
| 251-500        | 25       | 14.97%  |
| 501-1000       | 25       | 14.97%  |
| 1001-2000      | 19       | 11.38%  |
| More than 3000 | 15       | 8.98%   |
| 1-20           | 12       | 7.19%   |
| 51-100         | 10       | 5.99%   |
| Unknown        | 7        | 4.19%   |
| 2001-3000      | 6        | 3.59%   |
| 21-50          | 2        | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 75       | 43.6%   |
| 21-50          | 18       | 10.47%  |
| 501-1000       | 15       | 8.72%   |
| 251-500        | 14       | 8.14%   |
| 51-100         | 13       | 7.56%   |
| 101-250        | 11       | 6.4%    |
| 1001-2000      | 9        | 5.23%   |
| Unknown        | 7        | 4.07%   |
| More than 3000 | 5        | 2.91%   |
| 2001-3000      | 5        | 2.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-07A7B0 640GB        | 1        | 1      | 5%      |
| WDC WD5003ABYX-88 LEN 500GB        | 1        | 1      | 5%      |
| WDC WD5000AAKX-221CA1 500GB        | 1        | 1      | 5%      |
| WDC WD3200AAKS-00L9A0 320GB        | 1        | 1      | 5%      |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1      | 5%      |
| WDC WD10EZRZ-00HTKB0 1TB           | 1        | 1      | 5%      |
| WDC WD10EZEX-00MFCA0 1TB           | 1        | 1      | 5%      |
| Transcend TS480GSSD220S 480GB      | 1        | 1      | 5%      |
| Toshiba DT01ACA100 1TB             | 1        | 1      | 5%      |
| SPCC Solid State Disk 128GB        | 1        | 1      | 5%      |
| Seagate ST31500341AS 1TB           | 1        | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 3      | 5%      |
| SanDisk SDSSDA240G 240GB           | 1        | 1      | 5%      |
| Kingston SHFS37A120G 120GB SSD     | 1        | 1      | 5%      |
| Intel SSDSC2BW180A4 180GB          | 1        | 1      | 5%      |
| Intel SSDSC2BW120A4 120GB          | 1        | 1      | 5%      |
| Hitachi HDS723020BLA642 2TB        | 1        | 1      | 5%      |
| Crucial CT525MX300SSD1 528GB       | 1        | 1      | 5%      |
| Crucial CT120BX500SSD1 120GB       | 1        | 2      | 5%      |
| A-DATA Technology SP900 64GB SSD   | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 7        | 7      | 35%     |
| Seagate           | 2        | 4      | 10%     |
| Intel             | 2        | 2      | 10%     |
| Crucial           | 2        | 3      | 10%     |
| Transcend         | 1        | 1      | 5%      |
| Toshiba           | 1        | 1      | 5%      |
| SPCC              | 1        | 1      | 5%      |
| SanDisk           | 1        | 1      | 5%      |
| Kingston          | 1        | 1      | 5%      |
| Hitachi           | 1        | 1      | 5%      |
| A-DATA Technology | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 7      | 63.64%  |
| Seagate | 2        | 4      | 18.18%  |
| Toshiba | 1        | 1      | 9.09%   |
| Hitachi | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 13     | 55%     |
| SSD  | 9        | 10     | 45%     |

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
| Detected | 95       | 259    | 55.56%  |
| Works    | 58       | 159    | 33.92%  |
| Malfunc  | 18       | 23     | 10.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 97       | 46.41%  |
| AMD                         | 50       | 23.92%  |
| Samsung Electronics         | 14       | 6.7%    |
| Kingston Technology Company | 7        | 3.35%   |
| Phison Electronics          | 5        | 2.39%   |
| JMicron Technology          | 5        | 2.39%   |
| Nvidia                      | 4        | 1.91%   |
| ASMedia Technology          | 4        | 1.91%   |
| ADATA Technology            | 4        | 1.91%   |
| Silicon Motion              | 3        | 1.44%   |
| SanDisk                     | 3        | 1.44%   |
| Micron/Crucial Technology   | 3        | 1.44%   |
| Marvell Technology Group    | 3        | 1.44%   |
| VIA Technologies            | 1        | 0.48%   |
| Transcend                   | 1        | 0.48%   |
| Silicon Image               | 1        | 0.48%   |
| Realtek Semiconductor       | 1        | 0.48%   |
| Micron Technology           | 1        | 0.48%   |
| Broadcom / LSI              | 1        | 0.48%   |
| Adaptec                     | 1        | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 9.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 5.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 4.01%   |
| AMD FCH SATA Controller D                                                               | 10       | 3.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 3.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 2.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 2.55%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.55%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 2.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.82%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 1.46%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.46%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.46%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.46%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.46%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.09%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 0.73%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.73%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.73%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 0.73%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.73%   |
| Intel SSD 600P Series                                                                   | 2        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.73%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.73%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.73%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.73%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.73%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 117      | 54.42%  |
| IDE  | 48       | 22.33%  |
| NVMe | 40       | 18.6%   |
| RAID | 9        | 4.19%   |
| SAS  | 1        | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 63.4%   |
| AMD    | 56       | 36.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 3.21%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.92%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 1.92%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 1.92%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.92%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 3        | 1.92%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.92%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.92%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.92%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.28%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 1.28%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.28%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 2        | 1.28%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.28%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.28%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.28%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.28%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 2        | 1.28%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.28%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.28%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.28%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.28%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.28%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.28%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 1.28%   |
| AMD Phenom II X4 965 Processor              | 2        | 1.28%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.28%   |
| AMD Athlon X4 740 Quad Core Processor       | 2        | 1.28%   |
| AMD Athlon 64 X2 Dual Core Processor 6400+  | 2        | 1.28%   |
| Intel Xeon E-2314 CPU @ 2.80GHz             | 1        | 0.64%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.64%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz         | 1        | 0.64%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.64%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.64%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.64%   |
| Intel Pentium CPU G4560T @ 2.90GHz          | 1        | 0.64%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.64%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.64%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 19.87%  |
| Intel Core i3           | 16       | 10.26%  |
| Intel Core i7           | 15       | 9.62%   |
| AMD Ryzen 5             | 12       | 7.69%   |
| Intel Core 2 Duo        | 8        | 5.13%   |
| Other                   | 7        | 4.49%   |
| Intel Pentium           | 5        | 3.21%   |
| AMD Ryzen 9             | 5        | 3.21%   |
| AMD Ryzen 3             | 5        | 3.21%   |
| AMD FX                  | 5        | 3.21%   |
| Intel Xeon              | 4        | 2.56%   |
| AMD Ryzen 7             | 4        | 2.56%   |
| AMD Athlon II X4        | 4        | 2.56%   |
| AMD Phenom II X4        | 3        | 1.92%   |
| AMD Athlon X4           | 3        | 1.92%   |
| AMD Athlon 64 X2        | 3        | 1.92%   |
| Intel Pentium Dual-Core | 2        | 1.28%   |
| Intel Pentium Dual      | 2        | 1.28%   |
| Intel Pentium 4         | 2        | 1.28%   |
| Intel Core i9           | 2        | 1.28%   |
| Intel Core 2 Quad       | 2        | 1.28%   |
| Intel Core 2            | 2        | 1.28%   |
| AMD A8                  | 2        | 1.28%   |
| Intel Celeron           | 1        | 0.64%   |
| AMD Ryzen Threadripper  | 1        | 0.64%   |
| AMD Ryzen 7 PRO         | 1        | 0.64%   |
| AMD Ryzen 5 PRO         | 1        | 0.64%   |
| AMD Ryzen 3 PRO         | 1        | 0.64%   |
| AMD Phenom II X6        | 1        | 0.64%   |
| AMD Phenom II X2        | 1        | 0.64%   |
| AMD Phenom              | 1        | 0.64%   |
| AMD E                   | 1        | 0.64%   |
| AMD Athlon 64           | 1        | 0.64%   |
| AMD Athlon              | 1        | 0.64%   |
| AMD A6                  | 1        | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 68       | 43.59%  |
| 2      | 40       | 25.64%  |
| 6      | 21       | 13.46%  |
| 8      | 9        | 5.77%   |
| 1      | 5        | 3.21%   |
| 12     | 4        | 2.56%   |
| 3      | 3        | 1.92%   |
| 24     | 2        | 1.28%   |
| 16     | 2        | 1.28%   |
| 10     | 2        | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 152      | 99.35%  |
| 2      | 1        | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 79       | 51.3%   |
| 1      | 75       | 48.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 151      | 98.69%  |
| Unknown        | 2        | 1.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 22.36%  |
| 0x306c3    | 21       | 13.04%  |
| 0x206a7    | 11       | 6.83%   |
| 0x1067a    | 7        | 4.35%   |
| 0xa0653    | 5        | 3.11%   |
| 0x906ea    | 5        | 3.11%   |
| 0x0800820d | 5        | 3.11%   |
| 0x506e3    | 4        | 2.48%   |
| 0x010000db | 4        | 2.48%   |
| 0x010000c8 | 4        | 2.48%   |
| 0xa0671    | 3        | 1.86%   |
| 0x906e9    | 3        | 1.86%   |
| 0x6fd      | 3        | 1.86%   |
| 0x306a9    | 3        | 1.86%   |
| 0x08701021 | 3        | 1.86%   |
| 0x06001119 | 3        | 1.86%   |
| 0xf43      | 2        | 1.24%   |
| 0xa0655    | 2        | 1.24%   |
| 0x906ed    | 2        | 1.24%   |
| 0x906eb    | 2        | 1.24%   |
| 0x6fb      | 2        | 1.24%   |
| 0x306f2    | 2        | 1.24%   |
| 0x08600106 | 2        | 1.24%   |
| 0x0810100b | 2        | 1.24%   |
| 0x08001137 | 2        | 1.24%   |
| 0x06000852 | 2        | 1.24%   |
| 0x0600063e | 2        | 1.24%   |
| 0xb0671    | 1        | 0.62%   |
| 0x90672    | 1        | 0.62%   |
| 0x6f6      | 1        | 0.62%   |
| 0x20655    | 1        | 0.62%   |
| 0x106a4    | 1        | 0.62%   |
| 0x0a601203 | 1        | 0.62%   |
| 0x0a50000d | 1        | 0.62%   |
| 0x0a201009 | 1        | 0.62%   |
| 0x0a201005 | 1        | 0.62%   |
| 0x08701030 | 1        | 0.62%   |
| 0x08701013 | 1        | 0.62%   |
| 0x08600103 | 1        | 0.62%   |
| 0x08108109 | 1        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 26       | 16.88%  |
| SandyBridge      | 13       | 8.44%   |
| KabyLake         | 11       | 7.14%   |
| Zen+             | 9        | 5.84%   |
| Zen              | 9        | 5.84%   |
| K10              | 9        | 5.84%   |
| Zen 2            | 8        | 5.19%   |
| Piledriver       | 8        | 5.19%   |
| Penryn           | 8        | 5.19%   |
| Core             | 8        | 5.19%   |
| CometLake        | 8        | 5.19%   |
| Skylake          | 6        | 3.9%    |
| Zen 3            | 4        | 2.6%    |
| K8 Hammer        | 4        | 2.6%    |
| IvyBridge        | 4        | 2.6%    |
| Icelake          | 4        | 2.6%    |
| Alderlake Hybrid | 3        | 1.95%   |
| Unknown          | 3        | 1.95%   |
| Westmere         | 2        | 1.3%    |
| NetBurst         | 2        | 1.3%    |
| Bulldozer        | 2        | 1.3%    |
| Nehalem          | 1        | 0.65%   |
| Excavator        | 1        | 0.65%   |
| Bobcat           | 1        | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 64       | 37.65%  |
| AMD                        | 61       | 35.88%  |
| Intel                      | 43       | 25.29%  |
| Matrox Electronics Systems | 1        | 0.59%   |
| ATI Technologies           | 1        | 0.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 6.4%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 5.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 3.49%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 2.91%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 2.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.74%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 1.74%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.74%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.74%   |
| Intel HD Graphics 530                                                       | 3        | 1.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.74%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 3        | 1.74%   |
| AMD Renoir                                                                  | 3        | 1.74%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.74%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.16%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.16%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 1.16%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.16%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.16%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.16%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.16%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.16%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 1.16%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 1.16%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.58%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.58%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.58%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.58%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.58%   |
| Nvidia GM206 [GeForce GTX 750 v2]                                           | 1        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 58       | 36.94%  |
| 1 x AMD        | 55       | 35.03%  |
| 1 x Intel      | 33       | 21.02%  |
| Intel + Nvidia | 4        | 2.55%   |
| 2 x AMD        | 2        | 1.27%   |
| Intel + AMD    | 2        | 1.27%   |
| AMD + Nvidia   | 2        | 1.27%   |
| 1 x Matrox     | 1        | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 109      | 68.55%  |
| Proprietary | 46       | 28.93%  |
| Unknown     | 4        | 2.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 58       | 36.48%  |
| 1.01-2.0   | 29       | 18.24%  |
| 0.51-1.0   | 28       | 17.61%  |
| 7.01-8.0   | 12       | 7.55%   |
| 3.01-4.0   | 11       | 6.92%   |
| 0.01-0.5   | 10       | 6.29%   |
| 5.01-6.0   | 4        | 2.52%   |
| 8.01-16.0  | 4        | 2.52%   |
| 2.01-3.0   | 3        | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 39       | 23.21%  |
| Dell                 | 21       | 12.5%   |
| AOC                  | 21       | 12.5%   |
| Philips              | 16       | 9.52%   |
| Acer                 | 16       | 9.52%   |
| Goldstar             | 14       | 8.33%   |
| Ancor Communications | 9        | 5.36%   |
| Hewlett-Packard      | 5        | 2.98%   |
| LG Electronics       | 3        | 1.79%   |
| BenQ                 | 3        | 1.79%   |
| ASUSTek Computer     | 3        | 1.79%   |
| Unknown              | 2        | 1.19%   |
| Huion                | 2        | 1.19%   |
| Grundig              | 2        | 1.19%   |
| Fujitsu Siemens      | 2        | 1.19%   |
| Vestel Elektronik    | 1        | 0.6%    |
| Sony                 | 1        | 0.6%    |
| RTK                  | 1        | 0.6%    |
| Panasonic            | 1        | 0.6%    |
| NOA VISION           | 1        | 0.6%    |
| NEC Computers        | 1        | 0.6%    |
| LG Display           | 1        | 0.6%    |
| Lenovo               | 1        | 0.6%    |
| KTC                  | 1        | 0.6%    |
| InnoLux Display      | 1        | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0509 1920x1080                    | 2        | 1.1%    |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                   | 2        | 1.1%    |
| Huion Kamvas Pro 22 HAT2150 1920x1080 480x260mm 21.5-inch            | 2        | 1.1%    |
| Grundig WXGA GRU4448 1600x1200                                       | 2        | 1.1%    |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 2        | 1.1%    |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                    | 2        | 1.1%    |
| Dell LCD Monitor SE2416H 5760x1080                                   | 2        | 1.1%    |
| Dell LCD Monitor SE2416H                                             | 2        | 1.1%    |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                    | 2        | 1.1%    |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                    | 2        | 1.1%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 1.1%    |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 2        | 1.1%    |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 2        | 1.1%    |
| AOC 22P1W AOC2201 1920x1080 477x268mm 21.5-inch                      | 2        | 1.1%    |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                    | 2        | 1.1%    |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch   | 1        | 0.55%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.55%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                          | 1        | 0.55%   |
| Sony TV SNY1A02 1920x1080                                            | 1        | 0.55%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1        | 0.55%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM06A3 1360x768 410x230mm 18.5-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0608 1920x1080 510x290mm 23.1-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM05C6 1920x1080 520x290mm 23.4-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM01E7 1920x1200 518x324mm 24.1-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM01B8 1280x1024 338x270mm 17.0-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0168 1280x1024 338x270mm 17.0-inch | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch | 1        | 0.55%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch | 1        | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 76       | 46.06%  |
| 2560x1440 (QHD)    | 15       | 9.09%   |
| 1280x1024 (SXGA)   | 12       | 7.27%   |
| 3840x2160 (4K)     | 11       | 6.67%   |
| 1680x1050 (WSXGA+) | 10       | 6.06%   |
| Unknown            | 8        | 4.85%   |
| 1920x1200 (WUXGA)  | 6        | 3.64%   |
| 1600x900 (HD+)     | 5        | 3.03%   |
| 3840x1080          | 4        | 2.42%   |
| 1440x900 (WXGA+)   | 4        | 2.42%   |
| 1360x768           | 4        | 2.42%   |
| 5760x1080          | 2        | 1.21%   |
| 2560x1080          | 2        | 1.21%   |
| 2048x1152          | 2        | 1.21%   |
| 1366x768 (WXGA)    | 2        | 1.21%   |
| 4480x1440          | 1        | 0.61%   |
| 2560x1600          | 1        | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 31       | 18.45%  |
| 27      | 24       | 14.29%  |
| 24      | 20       | 11.9%   |
| 21      | 20       | 11.9%   |
| Unknown | 19       | 11.31%  |
| 19      | 9        | 5.36%   |
| 22      | 8        | 4.76%   |
| 17      | 7        | 4.17%   |
| 20      | 6        | 3.57%   |
| 31      | 4        | 2.38%   |
| 54      | 3        | 1.79%   |
| 18      | 3        | 1.79%   |
| 84      | 2        | 1.19%   |
| 33      | 2        | 1.19%   |
| 25      | 2        | 1.19%   |
| 72      | 1        | 0.6%    |
| 60      | 1        | 0.6%    |
| 58      | 1        | 0.6%    |
| 46      | 1        | 0.6%    |
| 39      | 1        | 0.6%    |
| 34      | 1        | 0.6%    |
| 32      | 1        | 0.6%    |
| 26      | 1        | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 68       | 42.24%  |
| 401-500     | 39       | 24.22%  |
| Unknown     | 19       | 11.8%   |
| 601-700     | 9        | 5.59%   |
| 351-400     | 6        | 3.73%   |
| 301-350     | 6        | 3.73%   |
| 1001-1500   | 6        | 3.73%   |
| 701-800     | 4        | 2.48%   |
| 1501-2000   | 3        | 1.86%   |
| 901-1000    | 1        | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 100      | 65.36%  |
| 16/10   | 22       | 14.38%  |
| Unknown | 17       | 11.11%  |
| 5/4     | 11       | 7.19%   |
| 21/9    | 2        | 1.31%   |
| 3/2     | 1        | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 35.37%  |
| 301-350        | 25       | 15.24%  |
| 151-200        | 24       | 14.63%  |
| Unknown        | 19       | 11.59%  |
| 251-300        | 10       | 6.1%    |
| 141-150        | 9        | 5.49%   |
| More than 1000 | 8        | 4.88%   |
| 351-500        | 8        | 4.88%   |
| 501-1000       | 2        | 1.22%   |
| 121-130        | 1        | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 92       | 59.35%  |
| 101-120 | 31       | 20%     |
| Unknown | 19       | 12.26%  |
| 1-50    | 7        | 4.52%   |
| 121-160 | 5        | 3.23%   |
| 161-240 | 1        | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 117      | 74.52%  |
| 2     | 29       | 18.47%  |
| 0     | 7        | 4.46%   |
| 3     | 3        | 1.91%   |
| 4     | 1        | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 98       | 44.14%  |
| Intel                             | 49       | 22.07%  |
| Qualcomm Atheros                  | 10       | 4.5%    |
| TP-Link                           | 8        | 3.6%    |
| Broadcom                          | 7        | 3.15%   |
| Ralink Technology                 | 5        | 2.25%   |
| Ralink                            | 5        | 2.25%   |
| Qualcomm Atheros Communications   | 5        | 2.25%   |
| Nvidia                            | 4        | 1.8%    |
| MediaTek                          | 3        | 1.35%   |
| Marvell Technology Group          | 3        | 1.35%   |
| D-Link                            | 3        | 1.35%   |
| Xiaomi                            | 2        | 0.9%    |
| Sundance Technology Inc / IC Plus | 2        | 0.9%    |
| Samsung Electronics               | 2        | 0.9%    |
| NetGear                           | 2        | 0.9%    |
| ASIX Electronics                  | 2        | 0.9%    |
| VIA Technologies                  | 1        | 0.45%   |
| T & A Mobile Phones               | 1        | 0.45%   |
| Nokia Mobile Phones               | 1        | 0.45%   |
| Microsoft                         | 1        | 0.45%   |
| Linksys                           | 1        | 0.45%   |
| ICS Advent                        | 1        | 0.45%   |
| Huawei Technologies               | 1        | 0.45%   |
| Edimax Technology                 | 1        | 0.45%   |
| D-Link System                     | 1        | 0.45%   |
| Broadcom Limited                  | 1        | 0.45%   |
| ASUSTek Computer                  | 1        | 0.45%   |
| Aquantia                          | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 81       | 34.47%  |
| Realtek RTL8125 2.5GbE Controller                                          | 7        | 2.98%   |
| Qualcomm Atheros AR9271 802.11n                                            | 5        | 2.13%   |
| Intel Wi-Fi 6 AX200                                                        | 5        | 2.13%   |
| Intel Ethernet Connection (2) I218-V                                       | 5        | 2.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 4        | 1.7%    |
| Intel I211 Gigabit Network Connection                                      | 4        | 1.7%    |
| Intel Ethernet Controller I225-V                                           | 4        | 1.7%    |
| Intel Ethernet Connection I217-V                                           | 4        | 1.7%    |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 1.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.28%   |
| Ralink MT7601U Wireless Adapter                                            | 3        | 1.28%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 3        | 1.28%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.28%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.85%   |
| TP-Link 802.11ac NIC                                                       | 2        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 0.85%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 2        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.85%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                 | 2        | 0.85%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 0.85%   |
| NetGear A6210                                                              | 2        | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 0.85%   |
| Intel Wireless 3165                                                        | 2        | 0.85%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 0.85%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.85%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 0.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 2        | 0.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 2        | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.43%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 1        | 0.43%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                      | 1        | 0.43%   |
| T & A Mobile Phones 9008A                                                  | 1        | 0.43%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.43%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 18.03%  |
| TP-Link                         | 8        | 13.11%  |
| Realtek Semiconductor           | 7        | 11.48%  |
| Ralink Technology               | 5        | 8.2%    |
| Ralink                          | 5        | 8.2%    |
| Qualcomm Atheros Communications | 5        | 8.2%    |
| Broadcom                        | 5        | 8.2%    |
| Qualcomm Atheros                | 4        | 6.56%   |
| D-Link                          | 3        | 4.92%   |
| NetGear                         | 2        | 3.28%   |
| MediaTek                        | 2        | 3.28%   |
| Microsoft                       | 1        | 1.64%   |
| Linksys                         | 1        | 1.64%   |
| Edimax Technology               | 1        | 1.64%   |
| ASUSTek Computer                | 1        | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                         | 5        | 8.06%   |
| Intel Wi-Fi 6 AX200                                                     | 5        | 8.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4        | 6.45%   |
| Ralink MT7601U Wireless Adapter                                         | 3        | 4.84%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 3        | 4.84%   |
| TP-Link 802.11ac NIC                                                    | 2        | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 3.23%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 2        | 3.23%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2        | 3.23%   |
| NetGear A6210                                                           | 2        | 3.23%   |
| Intel Wireless 3165                                                     | 2        | 3.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2        | 3.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2        | 3.23%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 1.61%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1        | 1.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 1.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.61%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                  | 1        | 1.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1        | 1.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1        | 1.61%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.61%   |
| Ralink RT2070 Wireless Adapter                                          | 1        | 1.61%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1        | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.61%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 1.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1        | 1.61%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1        | 1.61%   |
| Linksys WUSB6400M                                                       | 1        | 1.61%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 1.61%   |
| Intel 700 Series Chipset Family Wi-Fi                                   | 1        | 1.61%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                | 1        | 1.61%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]    | 1        | 1.61%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.61%   |
| D-Link 11ac adapter                                                     | 1        | 1.61%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1        | 1.61%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]         | 1        | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 94       | 55.95%  |
| Intel                             | 43       | 25.6%   |
| Qualcomm Atheros                  | 6        | 3.57%   |
| Nvidia                            | 4        | 2.38%   |
| Marvell Technology Group          | 3        | 1.79%   |
| Xiaomi                            | 2        | 1.19%   |
| Sundance Technology Inc / IC Plus | 2        | 1.19%   |
| Samsung Electronics               | 2        | 1.19%   |
| Broadcom                          | 2        | 1.19%   |
| ASIX Electronics                  | 2        | 1.19%   |
| VIA Technologies                  | 1        | 0.6%    |
| T & A Mobile Phones               | 1        | 0.6%    |
| MediaTek                          | 1        | 0.6%    |
| ICS Advent                        | 1        | 0.6%    |
| Huawei Technologies               | 1        | 0.6%    |
| D-Link System                     | 1        | 0.6%    |
| Broadcom Limited                  | 1        | 0.6%    |
| Aquantia                          | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 81       | 47.09%  |
| Realtek RTL8125 2.5GbE Controller                                          | 7        | 4.07%   |
| Intel Ethernet Connection (2) I218-V                                       | 5        | 2.91%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.33%   |
| Intel Ethernet Controller I225-V                                           | 4        | 2.33%   |
| Intel Ethernet Connection I217-V                                           | 4        | 2.33%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.74%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.74%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.16%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 1.16%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.16%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.16%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 1.16%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 1.16%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.58%   |
| T & A Mobile Phones 9008A                                                  | 1        | 0.58%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.58%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.58%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.58%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.58%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.58%   |
| MediaTek Infinix SMART 6 HD                                                | 1        | 0.58%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.58%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.58%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.58%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 150      | 72.46%  |
| WiFi     | 56       | 27.05%  |
| Modem    | 1        | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 114      | 74.51%  |
| WiFi     | 39       | 25.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 111      | 72.08%  |
| 2     | 38       | 24.68%  |
| 0     | 3        | 1.95%   |
| 4     | 1        | 0.65%   |
| 3     | 1        | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 146      | 94.81%  |
| Yes  | 8        | 5.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 32.35%  |
| Cambridge Silicon Radio         | 7        | 20.59%  |
| Broadcom                        | 4        | 11.76%  |
| Realtek Semiconductor           | 2        | 5.88%   |
| Integrated System Solution      | 2        | 5.88%   |
| Foxconn / Hon Hai               | 2        | 5.88%   |
| ASUSTek Computer                | 2        | 5.88%   |
| TP-Link                         | 1        | 2.94%   |
| Qualcomm Atheros Communications | 1        | 2.94%   |
| IMC Networks                    | 1        | 2.94%   |
| Apple                           | 1        | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 20.59%  |
| Intel AX200 Bluetooth                                 | 5        | 14.71%  |
| Intel Bluetooth wireless interface                    | 3        | 8.82%   |
| Realtek Bluetooth Radio                               | 2        | 5.88%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 5.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 5.88%   |
| TP-Link UB5A Adapter                                  | 1        | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.94%   |
| Intel Bluetooth Device                                | 1        | 2.94%   |
| Intel AX201 Bluetooth                                 | 1        | 2.94%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.94%   |
| Integrated System Solution Bluetooth Device           | 1        | 2.94%   |
| IMC Networks BCM20702A0                               | 1        | 2.94%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 2.94%   |
| Foxconn / Hon Hai BT                                  | 1        | 2.94%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 2.94%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 2.94%   |
| Apple Bluetooth Host Controller                       | 1        | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 95       | 34.67%  |
| AMD                 | 82       | 29.93%  |
| Nvidia              | 62       | 22.63%  |
| C-Media Electronics | 10       | 3.65%   |
| Logitech            | 4        | 1.46%   |
| Creative Labs       | 3        | 1.09%   |
| Microsoft           | 2        | 0.73%   |
| Yamaha              | 1        | 0.36%   |
| XMOS                | 1        | 0.36%   |
| VIA Technologies    | 1        | 0.36%   |
| Trust               | 1        | 0.36%   |
| Tenx Technology     | 1        | 0.36%   |
| Razer USA           | 1        | 0.36%   |
| Native Instruments  | 1        | 0.36%   |
| MCS                 | 1        | 0.36%   |
| Kingston Technology | 1        | 0.36%   |
| JMTek               | 1        | 0.36%   |
| Focusrite-Novation  | 1        | 0.36%   |
| Ensoniq             | 1        | 0.36%   |
| Cirrus Logic        | 1        | 0.36%   |
| ATI Technologies    | 1        | 0.36%   |
| ASUSTek Computer    | 1        | 0.36%   |
| Astro Gaming        | 1        | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16       | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 3.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 3.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 3.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 3.18%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 2.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 2.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 2.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 2.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 2.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 2.55%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 1.91%   |
| Nvidia GM206 High Definition Audio Controller                              | 6        | 1.91%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 6        | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.59%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 1.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 1.59%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.27%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.27%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 1.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.27%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 4        | 1.27%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4        | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 0.96%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.96%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.64%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.64%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 27       | 30.68%  |
| Corsair             | 12       | 13.64%  |
| Unknown             | 10       | 11.36%  |
| G.Skill             | 10       | 11.36%  |
| Samsung Electronics | 7        | 7.95%   |
| SK hynix            | 5        | 5.68%   |
| Crucial             | 4        | 4.55%   |
| Transcend           | 3        | 3.41%   |
| Patriot             | 2        | 2.27%   |
| Kingmax             | 2        | 2.27%   |
| Elpida              | 2        | 2.27%   |
| Ramaxel Technology  | 1        | 1.14%   |
| Mushkin             | 1        | 1.14%   |
| Apacer              | 1        | 1.14%   |
| A-DATA Technology   | 1        | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 3        | 3.19%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 3.19%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                  | 2        | 2.13%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s  | 2        | 2.13%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 2.13%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s    | 2        | 2.13%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 2        | 2.13%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s              | 1        | 1.06%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 1.06%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 1        | 1.06%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 1.06%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 1        | 1.06%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s               | 1        | 1.06%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                    | 1        | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 1.06%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                 | 1        | 1.06%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 1        | 1.06%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s              | 1        | 1.06%   |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s   | 1        | 1.06%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s    | 1        | 1.06%   |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s       | 1        | 1.06%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s       | 1        | 1.06%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 1        | 1.06%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.06%   |
| SK hynix RAM HMT125U6BFR8C-H9 2GB DIMM SDRAM 1333MT/s   | 1        | 1.06%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 1.06%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s    | 1        | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 1.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.06%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.06%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s     | 1        | 1.06%   |
| Ramaxel RAM RMUA5090KE68H9F2133 4GB DIMM DDR4 2133MT/s  | 1        | 1.06%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s          | 1        | 1.06%   |
| Patriot RAM PSD22G80026 2GB DIMM DDR2 800MT/s           | 1        | 1.06%   |
| Mushkin RAM 99[2/7/4]199[F/T] 8192MB DIMM DDR4 2400MT/s | 1        | 1.06%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s     | 1        | 1.06%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 1        | 1.06%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s    | 1        | 1.06%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 1        | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 51.32%  |
| DDR3    | 24       | 31.58%  |
| SDRAM   | 4        | 5.26%   |
| Unknown | 4        | 5.26%   |
| DDR2    | 3        | 3.95%   |
| DDR5    | 1        | 1.32%   |
| DDR     | 1        | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 72       | 96%     |
| SODIMM | 3        | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 31       | 37.8%   |
| 4096  | 21       | 25.61%  |
| 16384 | 12       | 14.63%  |
| 2048  | 12       | 14.63%  |
| 1024  | 3        | 3.66%   |
| 32768 | 2        | 2.44%   |
| 512   | 1        | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 14       | 17.5%   |
| 3200  | 11       | 13.75%  |
| 2667  | 8        | 10%     |
| 1333  | 8        | 10%     |
| 2400  | 7        | 8.75%   |
| 3600  | 4        | 5%      |
| 3400  | 4        | 5%      |
| 2133  | 3        | 3.75%   |
| 800   | 3        | 3.75%   |
| 3866  | 2        | 2.5%    |
| 1800  | 2        | 2.5%    |
| 667   | 2        | 2.5%    |
| 4800  | 1        | 1.25%   |
| 4000  | 1        | 1.25%   |
| 3533  | 1        | 1.25%   |
| 3466  | 1        | 1.25%   |
| 3334  | 1        | 1.25%   |
| 3333  | 1        | 1.25%   |
| 2933  | 1        | 1.25%   |
| 2800  | 1        | 1.25%   |
| 1867  | 1        | 1.25%   |
| 1067  | 1        | 1.25%   |
| 533   | 1        | 1.25%   |
| 400   | 1        | 1.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 60%     |
| Prolific Technology | 2        | 20%     |
| Canon               | 2        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Prolific PL2305 Parallel Port   | 2        | 20%     |
| HP DeskJet 3630 series          | 2        | 20%     |
| HP LaserJet M14-M17             | 1        | 10%     |
| HP LaserJet M101-M106           | 1        | 10%     |
| HP Ink Tank Wireless 410 series | 1        | 10%     |
| HP DeskJet 2130 series          | 1        | 10%     |
| Canon PIXMA iP1800 Printer      | 1        | 10%     |
| Canon LiDE 400                  | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1        | 50%     |
| Canon CanoScan LiDE 220       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 12       | 44.44%  |
| Sunplus Innovation Technology | 4        | 14.81%  |
| Realtek Semiconductor         | 3        | 11.11%  |
| Microdia                      | 3        | 11.11%  |
| Chicony Electronics           | 2        | 7.41%   |
| Trust                         | 1        | 3.7%    |
| GenesysLogic Technology       | 1        | 3.7%    |
| Alcor Micro                   | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 14.81%  |
| Sunplus HD 720P webcam                | 3        | 11.11%  |
| Microdia Camera                       | 2        | 7.41%   |
| Logitech Webcam C170                  | 2        | 7.41%   |
| Trust Full HD Webcam                  | 1        | 3.7%    |
| Sunplus Full HD webcam                | 1        | 3.7%    |
| Realtek Full HD webcam                | 1        | 3.7%    |
| Realtek FULL HD 1080P Webcam          | 1        | 3.7%    |
| Realtek Asus laptop camera            | 1        | 3.7%    |
| Microdia Sonix USB 2.0 Camera         | 1        | 3.7%    |
| Logitech Webcam C925e                 | 1        | 3.7%    |
| Logitech Webcam C250                  | 1        | 3.7%    |
| Logitech Webcam C210                  | 1        | 3.7%    |
| Logitech Webcam C110                  | 1        | 3.7%    |
| Logitech HD Pro Webcam C920           | 1        | 3.7%    |
| Logitech C922 Pro Stream Webcam       | 1        | 3.7%    |
| GenesysLogic USB2.0 UVC PC Camera     | 1        | 3.7%    |
| Chicony HP High Definition Webcam     | 1        | 3.7%    |
| Chicony HP High Definition 1MP Webcam | 1        | 3.7%    |
| Alcor Micro USB 2.0 Web Camera        | 1        | 3.7%    |

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


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Gemalto (was Gemplus)      | 1        | 50%     |
| Athena Smartcard Solutions | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |
| Athena Smartcard Solutions ASEDrive CCID          | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 138      | 88.46%  |
| 1     | 14       | 8.97%   |
| 2     | 4        | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 33.33%  |
| Net/wireless             | 4        | 19.05%  |
| Bluetooth                | 3        | 14.29%  |
| Unassigned class         | 2        | 9.52%   |
| Chipcard                 | 2        | 9.52%   |
| Storage/raid             | 1        | 4.76%   |
| Fingerprint reader       | 1        | 4.76%   |
| Communication controller | 1        | 4.76%   |


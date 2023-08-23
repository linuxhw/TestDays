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

Total: 220

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 20       | 12.27%  |
| Ubuntu 18.04                 | 14       | 8.59%   |
| Debian 11                    | 7        | 4.29%   |
| OpenMandriva 4.3             | 6        | 3.68%   |
| Linux Mint 20.3              | 6        | 3.68%   |
| Linux Mint 20.2              | 6        | 3.68%   |
| Ubuntu 18.10                 | 5        | 3.07%   |
| Zorin 16                     | 4        | 2.45%   |
| Ubuntu 22.04                 | 4        | 2.45%   |
| Debian 10                    | 4        | 2.45%   |
| Ubuntu MATE 22.04            | 3        | 1.84%   |
| Ubuntu 19.10                 | 3        | 1.84%   |
| Pop!_OS 21.10                | 3        | 1.84%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.84%   |
| OpenMandriva 4.2             | 3        | 1.84%   |
| Manjaro                      | 3        | 1.84%   |
| Fedora 31                    | 3        | 1.84%   |
| Ubuntu 21.04                 | 2        | 1.23%   |
| Pop!_OS 20.10                | 2        | 1.23%   |
| openSUSE Leap-15.2           | 2        | 1.23%   |
| OpenMandriva 4.50            | 2        | 1.23%   |
| OpenMandriva 23.03           | 2        | 1.23%   |
| Linux Mint 20                | 2        | 1.23%   |
| KDE neon 20.04               | 2        | 1.23%   |
| Fedora 38                    | 2        | 1.23%   |
| EndeavourOS Rolling          | 2        | 1.23%   |
| ArcoLinux Rolling            | 2        | 1.23%   |
| Zorin 15                     | 1        | 0.61%   |
| Xubuntu 20.04                | 1        | 0.61%   |
| Xubuntu 18.04                | 1        | 0.61%   |
| Ubuntu Unity 18.04           | 1        | 0.61%   |
| Ubuntu MATE 20.04            | 1        | 0.61%   |
| Ubuntu MATE 19.10            | 1        | 0.61%   |
| Ubuntu Budgie 22.04          | 1        | 0.61%   |
| Ubuntu Budgie 20.04          | 1        | 0.61%   |
| Ubuntu Budgie 18.04          | 1        | 0.61%   |
| Ubuntu 22.10                 | 1        | 0.61%   |
| Ubuntu 21.10                 | 1        | 0.61%   |
| Ubuntu 20.10                 | 1        | 0.61%   |
| Ubuntu 17.10                 | 1        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 52       | 34.21%  |
| Linux Mint    | 17       | 11.18%  |
| OpenMandriva  | 13       | 8.55%   |
| Debian        | 9        | 5.92%   |
| Pop!_OS       | 8        | 5.26%   |
| Manjaro       | 7        | 4.61%   |
| Fedora        | 6        | 3.95%   |
| Zorin         | 5        | 3.29%   |
| openSUSE      | 5        | 3.29%   |
| Ubuntu MATE   | 3        | 1.97%   |
| Ubuntu Budgie | 3        | 1.97%   |
| KDE neon      | 3        | 1.97%   |
| Xubuntu       | 2        | 1.32%   |
| Gentoo        | 2        | 1.32%   |
| EndeavourOS   | 2        | 1.32%   |
| ArcoLinux     | 2        | 1.32%   |
| Arch          | 2        | 1.32%   |
| Ubuntu Unity  | 1        | 0.66%   |
| ROSA          | 1        | 0.66%   |
| Nobara        | 1        | 0.66%   |
| MX            | 1        | 0.66%   |
| Lubuntu       | 1        | 0.66%   |
| LMDE          | 1        | 0.66%   |
| LinuxFX       | 1        | 0.66%   |
| Kubuntu       | 1        | 0.66%   |
| Endless       | 1        | 0.66%   |
| Elementary    | 1        | 0.66%   |
| Clear Linux   | 1        | 0.66%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003      | 6        | 3.31%   |
| 5.4.0-58-generic             | 4        | 2.21%   |
| 5.4.0-91-generic             | 3        | 1.66%   |
| 5.3.0-26-generic             | 3        | 1.66%   |
| 5.10.14-desktop-1omv4002     | 3        | 1.66%   |
| 5.0.0-27-generic             | 3        | 1.66%   |
| 6.2.9-300.fc38.x86_64        | 2        | 1.1%    |
| 6.2.6-desktop-1omv2390       | 2        | 1.1%    |
| 5.8.0-48-generic             | 2        | 1.1%    |
| 5.4.0-48-generic             | 2        | 1.1%    |
| 5.4.0-42-generic             | 2        | 1.1%    |
| 5.4.0-26-generic             | 2        | 1.1%    |
| 5.4.0-100-generic            | 2        | 1.1%    |
| 5.3.0-42-generic             | 2        | 1.1%    |
| 5.3.0-28-generic             | 2        | 1.1%    |
| 5.15.0-52-generic            | 2        | 1.1%    |
| 5.15.0-48-generic            | 2        | 1.1%    |
| 5.13.0-40-generic            | 2        | 1.1%    |
| 5.12.4-desktop-1omv4050      | 2        | 1.1%    |
| 5.11.0-41-generic            | 2        | 1.1%    |
| 5.11.0-38-generic            | 2        | 1.1%    |
| 5.11.0-37-generic            | 2        | 1.1%    |
| 5.10.0-13-amd64              | 2        | 1.1%    |
| 4.19.0-14-amd64              | 2        | 1.1%    |
| 4.18.0-10-generic            | 2        | 1.1%    |
| 4.15.0-45-generic            | 2        | 1.1%    |
| 4.15.0-20-generic            | 2        | 1.1%    |
| 6.3.4-zen1-1-zen             | 1        | 0.55%   |
| 6.2.14-300.fsync.fc37.x86_64 | 1        | 0.55%   |
| 6.1.8-201.fsync.fc37.x86_64  | 1        | 0.55%   |
| 6.1.38-gentoo-dist           | 1        | 0.55%   |
| 6.0.6-zen1-1-zen             | 1        | 0.55%   |
| 6.0.5-4-rt14-MANJARO         | 1        | 0.55%   |
| 5.9.0-0.bpo.5-amd64          | 1        | 0.55%   |
| 5.8.0-59-generic             | 1        | 0.55%   |
| 5.8.0-41-generic             | 1        | 0.55%   |
| 5.8.0-40-generic             | 1        | 0.55%   |
| 5.8.0-34-generic             | 1        | 0.55%   |
| 5.7.11-100.fc31.x86_64       | 1        | 0.55%   |
| 5.7.0-0.bpo.2-amd64          | 1        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 19.53%  |
| 5.11.0  | 12       | 7.1%    |
| 5.3.0   | 11       | 6.51%   |
| 4.15.0  | 10       | 5.92%   |
| 5.15.0  | 8        | 4.73%   |
| 5.10.0  | 8        | 4.73%   |
| 4.18.0  | 8        | 4.73%   |
| 5.16.7  | 6        | 3.55%   |
| 5.13.0  | 6        | 3.55%   |
| 5.8.0   | 5        | 2.96%   |
| 5.0.0   | 4        | 2.37%   |
| 5.12.4  | 3        | 1.78%   |
| 5.10.14 | 3        | 1.78%   |
| 4.19.0  | 3        | 1.78%   |
| 6.2.9   | 2        | 1.18%   |
| 6.2.6   | 2        | 1.18%   |
| 5.3.18  | 2        | 1.18%   |
| 5.19.0  | 2        | 1.18%   |
| 5.16.11 | 2        | 1.18%   |
| 6.3.4   | 1        | 0.59%   |
| 6.2.14  | 1        | 0.59%   |
| 6.1.8   | 1        | 0.59%   |
| 6.1.38  | 1        | 0.59%   |
| 6.0.6   | 1        | 0.59%   |
| 6.0.5   | 1        | 0.59%   |
| 5.9.0   | 1        | 0.59%   |
| 5.7.11  | 1        | 0.59%   |
| 5.7.0   | 1        | 0.59%   |
| 5.6.12  | 1        | 0.59%   |
| 5.4.64  | 1        | 0.59%   |
| 5.4.20  | 1        | 0.59%   |
| 5.4.2   | 1        | 0.59%   |
| 5.4.18  | 1        | 0.59%   |
| 5.3.16  | 1        | 0.59%   |
| 5.19.2  | 1        | 0.59%   |
| 5.19.13 | 1        | 0.59%   |
| 5.19.12 | 1        | 0.59%   |
| 5.18.4  | 1        | 0.59%   |
| 5.18.14 | 1        | 0.59%   |
| 5.18.12 | 1        | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 22.16%  |
| 5.10    | 15       | 8.98%   |
| 5.3     | 14       | 8.38%   |
| 5.15    | 13       | 7.78%   |
| 5.11    | 13       | 7.78%   |
| 4.15    | 10       | 5.99%   |
| 5.16    | 8        | 4.79%   |
| 4.18    | 8        | 4.79%   |
| 5.13    | 6        | 3.59%   |
| 6.2     | 5        | 2.99%   |
| 5.8     | 5        | 2.99%   |
| 5.19    | 5        | 2.99%   |
| 5.0     | 4        | 2.4%    |
| 5.18    | 3        | 1.8%    |
| 5.12    | 3        | 1.8%    |
| 4.19    | 3        | 1.8%    |
| 6.1     | 2        | 1.2%    |
| 6.0     | 2        | 1.2%    |
| 5.7     | 2        | 1.2%    |
| 5.17    | 2        | 1.2%    |
| 5.14    | 2        | 1.2%    |
| 6.3     | 1        | 0.6%    |
| 5.9     | 1        | 0.6%    |
| 5.6     | 1        | 0.6%    |
| 4.14    | 1        | 0.6%    |
| 4.13    | 1        | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 145      | 98.64%  |
| i686   | 2        | 1.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 59       | 38.82%  |
| KDE5       | 30       | 19.74%  |
| Unknown    | 22       | 14.47%  |
| X-Cinnamon | 10       | 6.58%   |
| XFCE       | 7        | 4.61%   |
| MATE       | 5        | 3.29%   |
| KDE        | 4        | 2.63%   |
| Cinnamon   | 4        | 2.63%   |
| Budgie     | 3        | 1.97%   |
| Unity      | 1        | 0.66%   |
| ubuntu     | 1        | 0.66%   |
| Pantheon   | 1        | 0.66%   |
| openbox    | 1        | 0.66%   |
| LXQt       | 1        | 0.66%   |
| LXDE       | 1        | 0.66%   |
| i3         | 1        | 0.66%   |
| DWM        | 1        | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 126      | 82.89%  |
| Wayland | 11       | 7.24%   |
| Unknown | 10       | 6.58%   |
| Tty     | 5        | 3.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 84       | 54.55%  |
| SDDM    | 26       | 16.88%  |
| LightDM | 16       | 10.39%  |
| GDM3    | 12       | 7.79%   |
| GDM     | 12       | 7.79%   |
| TDM     | 4        | 2.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 78       | 51.32%  |
| hr_HR   | 40       | 26.32%  |
| Unknown | 25       | 16.45%  |
| en_GB   | 7        | 4.61%   |
| C       | 2        | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 84       | 56.76%  |
| EFI  | 64       | 43.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 116      | 76.82%  |
| Overlay | 14       | 9.27%   |
| Btrfs   | 13       | 8.61%   |
| Unknown | 4        | 2.65%   |
| Zfs     | 3        | 1.99%   |
| Xfs     | 1        | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 87       | 58%     |
| GPT     | 46       | 30.67%  |
| MBR     | 17       | 11.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 77.78%  |
| Yes       | 34       | 22.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 61.59%  |
| Yes       | 58       | 38.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 38       | 25.85%  |
| ASRock              | 36       | 24.49%  |
| Gigabyte Technology | 27       | 18.37%  |
| MSI                 | 12       | 8.16%   |
| Hewlett-Packard     | 9        | 6.12%   |
| Pegatron            | 5        | 3.4%    |
| Intel               | 4        | 2.72%   |
| Dell                | 4        | 2.72%   |
| ECS                 | 3        | 2.04%   |
| Lenovo              | 2        | 1.36%   |
| WinFast             | 1        | 0.68%   |
| HPE                 | 1        | 0.68%   |
| Fujitsu Siemens     | 1        | 0.68%   |
| Foxconn             | 1        | 0.68%   |
| Acer                | 1        | 0.68%   |
| ABIT                | 1        | 0.68%   |
| Unknown             | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 6        | 4.08%   |
| ASUS PRIME A320M-K                     | 3        | 2.04%   |
| ASRock B450M-HDV R4.0                  | 3        | 2.04%   |
| MSI MS-7850                            | 2        | 1.36%   |
| Gigabyte A320M-S2H                     | 2        | 1.36%   |
| ASUS P8H77-V LE                        | 2        | 1.36%   |
| ASUS M5A78L LE                         | 2        | 1.36%   |
| ASRock H61M-DGS                        | 2        | 1.36%   |
| WinFast N570SM2AA                      | 1        | 0.68%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.68%   |
| Pegatron HPE-520ad                     | 1        | 0.68%   |
| Pegatron G5261de                       | 1        | 0.68%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 0.68%   |
| Pegatron 27-1001eu                     | 1        | 0.68%   |
| MSI MS-7D25                            | 1        | 0.68%   |
| MSI MS-7C02                            | 1        | 0.68%   |
| MSI MS-7B98                            | 1        | 0.68%   |
| MSI MS-7B84                            | 1        | 0.68%   |
| MSI MS-7B07                            | 1        | 0.68%   |
| MSI MS-7817                            | 1        | 0.68%   |
| MSI MS-7681                            | 1        | 0.68%   |
| MSI MS-7586                            | 1        | 0.68%   |
| MSI MS-7360                            | 1        | 0.68%   |
| MSI 0A90                               | 1        | 0.68%   |
| Lenovo ThinkStation P310 30AT0029GE    | 1        | 0.68%   |
| Lenovo S510                            | 1        | 0.68%   |
| Intel H61M-S2PV                        | 1        | 0.68%   |
| Intel DX58SO AAE29331-501              | 1        | 0.68%   |
| Intel DH67BL AAG10189-213              | 1        | 0.68%   |
| Intel DH61CR AAG14064-204              | 1        | 0.68%   |
| HPE ProLiant ML30 Gen10 Plus           | 1        | 0.68%   |
| HP Z840 Workstation                    | 1        | 0.68%   |
| HP Z440 Workstation                    | 1        | 0.68%   |
| HP ProOne 400 G1 AiO                   | 1        | 0.68%   |
| HP ProDesk 600 G4 PCI MT               | 1        | 0.68%   |
| HP ProDesk 600 G1 SFF                  | 1        | 0.68%   |
| HP EliteDesk 800 G1 SFF                | 1        | 0.68%   |
| HP EliteDesk 800 G1 DM                 | 1        | 0.68%   |
| HP Compaq dc7900 Small Form Factor     | 1        | 0.68%   |
| HP 750-100ny                           | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 8        | 5.44%   |
| ASUS All            | 6        | 4.08%   |
| ASUS TUF            | 4        | 2.72%   |
| Dell Vostro         | 3        | 2.04%   |
| ASUS ROG            | 3        | 2.04%   |
| ASRock B450M-HDV    | 3        | 2.04%   |
| MSI MS-7850         | 2        | 1.36%   |
| HP ProDesk          | 2        | 1.36%   |
| HP EliteDesk        | 2        | 1.36%   |
| Gigabyte Z390       | 2        | 1.36%   |
| Gigabyte B450       | 2        | 1.36%   |
| Gigabyte A320M-S2H  | 2        | 1.36%   |
| ASUS P8H77-V        | 2        | 1.36%   |
| ASUS M5A78L         | 2        | 1.36%   |
| ASRock H97          | 2        | 1.36%   |
| ASRock H61M-DGS     | 2        | 1.36%   |
| ASRock A320M-HDV    | 2        | 1.36%   |
| WinFast N570SM2AA   | 1        | 0.68%   |
| Pegatron Pro        | 1        | 0.68%   |
| Pegatron HPE-520ad  | 1        | 0.68%   |
| Pegatron G5261de    | 1        | 0.68%   |
| Pegatron Compaq     | 1        | 0.68%   |
| Pegatron 27-1001eu  | 1        | 0.68%   |
| MSI MS-7D25         | 1        | 0.68%   |
| MSI MS-7C02         | 1        | 0.68%   |
| MSI MS-7B98         | 1        | 0.68%   |
| MSI MS-7B84         | 1        | 0.68%   |
| MSI MS-7B07         | 1        | 0.68%   |
| MSI MS-7817         | 1        | 0.68%   |
| MSI MS-7681         | 1        | 0.68%   |
| MSI MS-7586         | 1        | 0.68%   |
| MSI MS-7360         | 1        | 0.68%   |
| MSI 0A90            | 1        | 0.68%   |
| Lenovo ThinkStation | 1        | 0.68%   |
| Lenovo S510         | 1        | 0.68%   |
| Intel H61M-S2PV     | 1        | 0.68%   |
| Intel DX58SO        | 1        | 0.68%   |
| Intel DH67BL        | 1        | 0.68%   |
| Intel DH61CR        | 1        | 0.68%   |
| HPE ProLiant        | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 18       | 12.24%  |
| 2018 | 15       | 10.2%   |
| 2017 | 13       | 8.84%   |
| 2012 | 13       | 8.84%   |
| 2011 | 12       | 8.16%   |
| 2020 | 11       | 7.48%   |
| 2019 | 8        | 5.44%   |
| 2014 | 8        | 5.44%   |
| 2009 | 8        | 5.44%   |
| 2021 | 7        | 4.76%   |
| 2015 | 7        | 4.76%   |
| 2010 | 7        | 4.76%   |
| 2008 | 7        | 4.76%   |
| 2007 | 5        | 3.4%    |
| 2022 | 4        | 2.72%   |
| 2006 | 2        | 1.36%   |
| 2005 | 2        | 1.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 147      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 142      | 95.95%  |
| Enabled  | 6        | 4.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 147      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 42       | 27.81%  |
| 16.01-24.0  | 39       | 25.83%  |
| 4.01-8.0    | 25       | 16.56%  |
| 3.01-4.0    | 17       | 11.26%  |
| 32.01-64.0  | 16       | 10.6%   |
| 1.01-2.0    | 6        | 3.97%   |
| 64.01-256.0 | 3        | 1.99%   |
| 24.01-32.0  | 2        | 1.32%   |
| 2.01-3.0    | 1        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 64       | 39.26%  |
| 2.01-3.0   | 42       | 25.77%  |
| 4.01-8.0   | 23       | 14.11%  |
| 3.01-4.0   | 17       | 10.43%  |
| 0.51-1.0   | 8        | 4.91%   |
| 16.01-24.0 | 4        | 2.45%   |
| 8.01-16.0  | 4        | 2.45%   |
| 0.01-0.5   | 1        | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 33.97%  |
| 2      | 48       | 30.77%  |
| 3      | 28       | 17.95%  |
| 4      | 12       | 7.69%   |
| 5      | 9        | 5.77%   |
| 6      | 2        | 1.28%   |
| 0      | 2        | 1.28%   |
| 8      | 1        | 0.64%   |
| 7      | 1        | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 50.34%  |
| Yes       | 74       | 49.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 144      | 97.96%  |
| No        | 3        | 2.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 64.43%  |
| Yes       | 53       | 35.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 79.19%  |
| Yes       | 31       | 20.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Croatia | 147      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Zagreb          | 79       | 48.47%  |
| Split           | 12       | 7.36%   |
| Rijeka          | 8        | 4.91%   |
| Pula            | 4        | 2.45%   |
| Osijek          | 4        | 2.45%   |
| Velika Gorica   | 3        | 1.84%   |
| Varaždin       | 3        | 1.84%   |
| Samobor         | 3        | 1.84%   |
| Koprivnica      | 3        | 1.84%   |
| Zaprešić      | 2        | 1.23%   |
| Virovitica      | 2        | 1.23%   |
| Slatina         | 2        | 1.23%   |
| Pitomaca        | 2        | 1.23%   |
| Ivanja Reka     | 2        | 1.23%   |
| GJurgevac       | 2        | 1.23%   |
| Bjelovar        | 2        | 1.23%   |
| Zadar           | 1        | 0.61%   |
| Visnjevac       | 1        | 0.61%   |
| Supetar         | 1        | 0.61%   |
| Stari Perkovci  | 1        | 0.61%   |
| Skrad           | 1        | 0.61%   |
| Sisak           | 1        | 0.61%   |
| Sesvete         | 1        | 0.61%   |
| Raslina         | 1        | 0.61%   |
| Prelog          | 1        | 0.61%   |
| Postira         | 1        | 0.61%   |
| Novi Marof      | 1        | 0.61%   |
| Nerezine        | 1        | 0.61%   |
| Matulji         | 1        | 0.61%   |
| Mali Lošinj    | 1        | 0.61%   |
| Mahicno         | 1        | 0.61%   |
| Lovran          | 1        | 0.61%   |
| Labin           | 1        | 0.61%   |
| Kućan Marof    | 1        | 0.61%   |
| Krizevci        | 1        | 0.61%   |
| Krapina         | 1        | 0.61%   |
| Kastel Gomilica | 1        | 0.61%   |
| Hvar            | 1        | 0.61%   |
| Grad            | 1        | 0.61%   |
| Galgovo         | 1        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 69       | 127    | 25.18%  |
| Kingston              | 34       | 51     | 12.41%  |
| Samsung Electronics   | 32       | 50     | 11.68%  |
| Seagate               | 28       | 42     | 10.22%  |
| Toshiba               | 21       | 35     | 7.66%   |
| Crucial               | 15       | 21     | 5.47%   |
| Intel                 | 10       | 12     | 3.65%   |
| A-DATA Technology     | 10       | 14     | 3.65%   |
| SanDisk               | 5        | 8      | 1.82%   |
| Patriot               | 5        | 8      | 1.82%   |
| Hitachi               | 5        | 8      | 1.82%   |
| Transcend             | 3        | 7      | 1.09%   |
| Silicon Motion        | 3        | 4      | 1.09%   |
| Phison                | 3        | 3      | 1.09%   |
| OCZ                   | 2        | 3      | 0.73%   |
| Maxtor                | 2        | 2      | 0.73%   |
| HPE                   | 2        | 4      | 0.73%   |
| Gigabyte Technology   | 2        | 2      | 0.73%   |
| Corsair               | 2        | 2      | 0.73%   |
| XPG                   | 1        | 3      | 0.36%   |
| Unknown               | 1        | 1      | 0.36%   |
| TO Exter              | 1        | 1      | 0.36%   |
| SPCC                  | 1        | 1      | 0.36%   |
| Realtek Semiconductor | 1        | 1      | 0.36%   |
| PNY                   | 1        | 1      | 0.36%   |
| Netac                 | 1        | 1      | 0.36%   |
| Mushkin               | 1        | 2      | 0.36%   |
| Min Yi U              | 1        | 1      | 0.36%   |
| Micron Technology     | 1        | 1      | 0.36%   |
| KingSpec              | 1        | 1      | 0.36%   |
| Kingmax               | 1        | 1      | 0.36%   |
| INNOVATION IT         | 1        | 1      | 0.36%   |
| HGST HTS              | 1        | 1      | 0.36%   |
| HGST                  | 1        | 1      | 0.36%   |
| GOODRAM               | 1        | 1      | 0.36%   |
| External              | 1        | 1      | 0.36%   |
| China                 | 1        | 1      | 0.36%   |
| ASMedia               | 1        | 1      | 0.36%   |
| AMD                   | 1        | 2      | 0.36%   |
| ADATA Technology      | 1        | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD   | 6        | 1.89%   |
| Kingston SV300S37A120G 120GB SSD  | 5        | 1.57%   |
| Kingston SA400S37240G 240GB SSD   | 5        | 1.57%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4        | 1.26%   |
| Toshiba HDWD130 3TB               | 4        | 1.26%   |
| Toshiba HDWD110 1TB               | 4        | 1.26%   |
| Samsung SSD 850 EVO 250GB         | 4        | 1.26%   |
| Kingston SA400S37120G 120GB SSD   | 4        | 1.26%   |
| WDC WD5000AAKX-001CA0 500GB       | 3        | 0.94%   |
| Toshiba DT01ACA100 1TB            | 3        | 0.94%   |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 0.94%   |
| SanDisk SDSSDA240G 240GB          | 3        | 0.94%   |
| Samsung SSD 970 EVO Plus 1TB      | 3        | 0.94%   |
| Samsung HD103SI 1TB               | 3        | 0.94%   |
| Patriot Burst 240GB SSD           | 3        | 0.94%   |
| Intel SSDSC2BW120A4 120GB         | 3        | 0.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 2        | 0.63%   |
| WDC WD6400AAKS-22A7B0 640GB       | 2        | 0.63%   |
| WDC WD5003ABYX-88 LEN 500GB       | 2        | 0.63%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 0.63%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 2        | 0.63%   |
| WDC WD3200AAKS-00L9A0 320GB       | 2        | 0.63%   |
| WDC WD30EZRX-00AZ6B0 3TB          | 2        | 0.63%   |
| WDC WD30EFRX-68EUZN0 3TB          | 2        | 0.63%   |
| WDC WD2500AVJS-63WDA0 250GB       | 2        | 0.63%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 2        | 0.63%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.63%   |
| WDC WD1600AAJS-07M0A0 160GB       | 2        | 0.63%   |
| Toshiba MQ01ABD100 1TB            | 2        | 0.63%   |
| Toshiba HDWD240 4TB               | 2        | 0.63%   |
| Toshiba HDWD120 2TB               | 2        | 0.63%   |
| Toshiba DT01ACA300 3TB            | 2        | 0.63%   |
| Seagate ST3160815AS 160GB         | 2        | 0.63%   |
| Seagate ST31000528AS 1TB          | 2        | 0.63%   |
| Seagate ST31000524AS 1TB          | 2        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB    | 2        | 0.63%   |
| Seagate ST10000DM0004-1ZC101 10TB | 2        | 0.63%   |
| Samsung SSD 860 QVO 1TB           | 2        | 0.63%   |
| Samsung SSD 860 PRO 256GB         | 2        | 0.63%   |
| Samsung SSD 860 EVO 250GB         | 2        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 67       | 118    | 49.26%  |
| Seagate             | 27       | 41     | 19.85%  |
| Toshiba             | 21       | 35     | 15.44%  |
| Samsung Electronics | 7        | 9      | 5.15%   |
| Hitachi             | 5        | 8      | 3.68%   |
| Maxtor              | 2        | 2      | 1.47%   |
| Unknown             | 1        | 1      | 0.74%   |
| Min Yi U            | 1        | 1      | 0.74%   |
| HPE                 | 1        | 2      | 0.74%   |
| HGST HTS            | 1        | 1      | 0.74%   |
| HGST                | 1        | 1      | 0.74%   |
| External            | 1        | 1      | 0.74%   |
| ASMedia             | 1        | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 31       | 43     | 29.52%  |
| Samsung Electronics | 16       | 24     | 15.24%  |
| Crucial             | 14       | 19     | 13.33%  |
| Intel               | 8        | 10     | 7.62%   |
| A-DATA Technology   | 8        | 11     | 7.62%   |
| Patriot             | 4        | 7      | 3.81%   |
| SanDisk             | 3        | 5      | 2.86%   |
| WDC                 | 2        | 2      | 1.9%    |
| Transcend           | 2        | 2      | 1.9%    |
| OCZ                 | 2        | 3      | 1.9%    |
| Gigabyte Technology | 2        | 2      | 1.9%    |
| TO Exter            | 1        | 1      | 0.95%   |
| SPCC                | 1        | 1      | 0.95%   |
| Seagate             | 1        | 1      | 0.95%   |
| PNY                 | 1        | 1      | 0.95%   |
| Netac               | 1        | 1      | 0.95%   |
| Mushkin             | 1        | 2      | 0.95%   |
| KingSpec            | 1        | 1      | 0.95%   |
| Kingmax             | 1        | 1      | 0.95%   |
| INNOVATION IT       | 1        | 1      | 0.95%   |
| GOODRAM             | 1        | 1      | 0.95%   |
| Corsair             | 1        | 1      | 0.95%   |
| China               | 1        | 1      | 0.95%   |
| AMD                 | 1        | 2      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 106      | 221    | 46.49%  |
| SSD     | 85       | 143    | 37.28%  |
| NVMe    | 36       | 62     | 15.79%  |
| Unknown | 1        | 2      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 132      | 357    | 75.43%  |
| NVMe | 36       | 62     | 20.57%  |
| SAS  | 7        | 9      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 106      | 204    | 52.48%  |
| 0.51-1.0   | 55       | 92     | 27.23%  |
| 1.01-2.0   | 17       | 27     | 8.42%   |
| 2.01-3.0   | 13       | 27     | 6.44%   |
| 3.01-4.0   | 8        | 10     | 3.96%   |
| 4.01-10.0  | 3        | 4      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 46       | 28.57%  |
| 251-500        | 25       | 15.53%  |
| 501-1000       | 23       | 14.29%  |
| 1001-2000      | 19       | 11.8%   |
| More than 3000 | 13       | 8.07%   |
| 1-20           | 11       | 6.83%   |
| 51-100         | 9        | 5.59%   |
| Unknown        | 7        | 4.35%   |
| 2001-3000      | 6        | 3.73%   |
| 21-50          | 2        | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 73       | 43.98%  |
| 21-50          | 16       | 9.64%   |
| 501-1000       | 15       | 9.04%   |
| 251-500        | 14       | 8.43%   |
| 51-100         | 12       | 7.23%   |
| 101-250        | 10       | 6.02%   |
| 1001-2000      | 9        | 5.42%   |
| Unknown        | 7        | 4.22%   |
| More than 3000 | 5        | 3.01%   |
| 2001-3000      | 5        | 3.01%   |

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
| Detected | 92       | 255    | 55.76%  |
| Works    | 55       | 150    | 33.33%  |
| Malfunc  | 18       | 23     | 10.91%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 93       | 46.97%  |
| AMD                         | 48       | 24.24%  |
| Samsung Electronics         | 12       | 6.06%   |
| Kingston Technology Company | 6        | 3.03%   |
| Phison Electronics          | 5        | 2.53%   |
| JMicron Technology          | 5        | 2.53%   |
| Nvidia                      | 4        | 2.02%   |
| ASMedia Technology          | 4        | 2.02%   |
| ADATA Technology            | 4        | 2.02%   |
| Silicon Motion              | 3        | 1.52%   |
| SanDisk                     | 3        | 1.52%   |
| Marvell Technology Group    | 3        | 1.52%   |
| VIA Technologies            | 1        | 0.51%   |
| Transcend                   | 1        | 0.51%   |
| Silicon Image               | 1        | 0.51%   |
| Realtek Semiconductor       | 1        | 0.51%   |
| Micron/Crucial Technology   | 1        | 0.51%   |
| Micron Technology           | 1        | 0.51%   |
| Broadcom / LSI              | 1        | 0.51%   |
| Adaptec                     | 1        | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 9.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 6.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 4.2%    |
| AMD FCH SATA Controller D                                                               | 10       | 3.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 3.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 2.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 2.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.91%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.53%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.53%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.53%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.53%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 1.15%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.15%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 0.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.76%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.76%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.76%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.76%   |
| Intel SSD 600P Series                                                                   | 2        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.76%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.76%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.76%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.76%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.76%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 112      | 54.63%  |
| IDE  | 47       | 22.93%  |
| NVMe | 37       | 18.05%  |
| RAID | 8        | 3.9%    |
| SAS  | 1        | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 93       | 63.27%  |
| AMD    | 54       | 36.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 3.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2%      |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 2%      |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 2%      |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 2%      |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2%      |
| Intel Core i3-10100F CPU @ 3.60GHz          | 3        | 2%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2%      |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 2%      |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 2%      |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.33%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.33%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 2        | 1.33%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.33%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.33%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.33%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.33%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 2        | 1.33%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.33%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.33%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.33%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.33%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 1.33%   |
| AMD Phenom II X4 965 Processor              | 2        | 1.33%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.33%   |
| AMD Athlon X4 740 Quad Core Processor       | 2        | 1.33%   |
| AMD Athlon 64 X2 Dual Core Processor 6400+  | 2        | 1.33%   |
| Intel Xeon E-2314 CPU @ 2.80GHz             | 1        | 0.67%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.67%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz         | 1        | 0.67%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.67%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.67%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.67%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.67%   |
| Intel Pentium CPU G4560T @ 2.90GHz          | 1        | 0.67%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.67%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.67%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.67%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 20.67%  |
| Intel Core i3           | 16       | 10.67%  |
| Intel Core i7           | 15       | 10%     |
| AMD Ryzen 5             | 11       | 7.33%   |
| Intel Core 2 Duo        | 7        | 4.67%   |
| Other                   | 5        | 3.33%   |
| AMD Ryzen 9             | 5        | 3.33%   |
| AMD Ryzen 3             | 5        | 3.33%   |
| AMD FX                  | 5        | 3.33%   |
| Intel Xeon              | 4        | 2.67%   |
| Intel Pentium           | 4        | 2.67%   |
| AMD Athlon II X4        | 4        | 2.67%   |
| AMD Ryzen 7             | 3        | 2%      |
| AMD Phenom II X4        | 3        | 2%      |
| AMD Athlon X4           | 3        | 2%      |
| AMD Athlon 64 X2        | 3        | 2%      |
| Intel Pentium Dual-Core | 2        | 1.33%   |
| Intel Pentium Dual      | 2        | 1.33%   |
| Intel Pentium 4         | 2        | 1.33%   |
| Intel Core i9           | 2        | 1.33%   |
| Intel Core 2 Quad       | 2        | 1.33%   |
| Intel Core 2            | 2        | 1.33%   |
| AMD A8                  | 2        | 1.33%   |
| Intel Celeron           | 1        | 0.67%   |
| AMD Ryzen Threadripper  | 1        | 0.67%   |
| AMD Ryzen 7 PRO         | 1        | 0.67%   |
| AMD Ryzen 5 PRO         | 1        | 0.67%   |
| AMD Ryzen 3 PRO         | 1        | 0.67%   |
| AMD Phenom II X6        | 1        | 0.67%   |
| AMD Phenom II X2        | 1        | 0.67%   |
| AMD Phenom              | 1        | 0.67%   |
| AMD E                   | 1        | 0.67%   |
| AMD Athlon 64           | 1        | 0.67%   |
| AMD Athlon              | 1        | 0.67%   |
| AMD A6                  | 1        | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 68       | 45.33%  |
| 2      | 38       | 25.33%  |
| 6      | 19       | 12.67%  |
| 8      | 8        | 5.33%   |
| 1      | 5        | 3.33%   |
| 12     | 4        | 2.67%   |
| 3      | 3        | 2%      |
| 16     | 2        | 1.33%   |
| 10     | 2        | 1.33%   |
| 24     | 1        | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 146      | 99.32%  |
| 2      | 1        | 0.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 75       | 50.68%  |
| 1      | 73       | 49.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 145      | 98.64%  |
| Unknown        | 2        | 1.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 21.29%  |
| 0x306c3    | 21       | 13.55%  |
| 0x206a7    | 11       | 7.1%    |
| 0x1067a    | 7        | 4.52%   |
| 0xa0653    | 5        | 3.23%   |
| 0x906ea    | 5        | 3.23%   |
| 0x0800820d | 5        | 3.23%   |
| 0x506e3    | 4        | 2.58%   |
| 0x010000db | 4        | 2.58%   |
| 0x010000c8 | 4        | 2.58%   |
| 0xa0671    | 3        | 1.94%   |
| 0x906e9    | 3        | 1.94%   |
| 0x6fd      | 3        | 1.94%   |
| 0x306a9    | 3        | 1.94%   |
| 0x06001119 | 3        | 1.94%   |
| 0xf43      | 2        | 1.29%   |
| 0xa0655    | 2        | 1.29%   |
| 0x906ed    | 2        | 1.29%   |
| 0x906eb    | 2        | 1.29%   |
| 0x6fb      | 2        | 1.29%   |
| 0x306f2    | 2        | 1.29%   |
| 0x08701021 | 2        | 1.29%   |
| 0x08600106 | 2        | 1.29%   |
| 0x0810100b | 2        | 1.29%   |
| 0x08001137 | 2        | 1.29%   |
| 0x06000852 | 2        | 1.29%   |
| 0x0600063e | 2        | 1.29%   |
| 0x90672    | 1        | 0.65%   |
| 0x6f6      | 1        | 0.65%   |
| 0x20655    | 1        | 0.65%   |
| 0x106a4    | 1        | 0.65%   |
| 0x0a601203 | 1        | 0.65%   |
| 0x0a50000d | 1        | 0.65%   |
| 0x0a201009 | 1        | 0.65%   |
| 0x0a201005 | 1        | 0.65%   |
| 0x08701013 | 1        | 0.65%   |
| 0x08600103 | 1        | 0.65%   |
| 0x08108109 | 1        | 0.65%   |
| 0x08108102 | 1        | 0.65%   |
| 0x08001138 | 1        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 26       | 17.57%  |
| SandyBridge      | 12       | 8.11%   |
| KabyLake         | 11       | 7.43%   |
| Zen+             | 9        | 6.08%   |
| Zen              | 9        | 6.08%   |
| K10              | 9        | 6.08%   |
| Piledriver       | 8        | 5.41%   |
| Core             | 8        | 5.41%   |
| CometLake        | 8        | 5.41%   |
| Penryn           | 7        | 4.73%   |
| Zen 2            | 6        | 4.05%   |
| Skylake          | 6        | 4.05%   |
| Zen 3            | 4        | 2.7%    |
| K8 Hammer        | 4        | 2.7%    |
| IvyBridge        | 4        | 2.7%    |
| Icelake          | 3        | 2.03%   |
| Unknown          | 3        | 2.03%   |
| Westmere         | 2        | 1.35%   |
| NetBurst         | 2        | 1.35%   |
| Bulldozer        | 2        | 1.35%   |
| Alderlake Hybrid | 2        | 1.35%   |
| Nehalem          | 1        | 0.68%   |
| Excavator        | 1        | 0.68%   |
| Bobcat           | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 61       | 37.42%  |
| AMD                        | 58       | 35.58%  |
| Intel                      | 42       | 25.77%  |
| Matrox Electronics Systems | 1        | 0.61%   |
| ATI Technologies           | 1        | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 6.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 5.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 3.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 3.03%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 2.42%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.82%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 1.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.82%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.82%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.82%   |
| Intel HD Graphics 530                                                       | 3        | 1.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.82%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 3        | 1.82%   |
| AMD Renoir                                                                  | 3        | 1.82%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.82%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.21%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 1.21%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.21%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.21%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.21%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.21%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.21%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.21%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 1.21%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.21%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 1.21%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.21%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.61%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.61%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.61%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.61%   |
| Nvidia GM206 [GeForce GTX 750 v2]                                           | 1        | 0.61%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 55       | 36.42%  |
| 1 x AMD        | 53       | 35.1%   |
| 1 x Intel      | 33       | 21.85%  |
| Intel + Nvidia | 4        | 2.65%   |
| 2 x AMD        | 2        | 1.32%   |
| AMD + Nvidia   | 2        | 1.32%   |
| 1 x Matrox     | 1        | 0.66%   |
| Intel + AMD    | 1        | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 105      | 68.63%  |
| Proprietary | 45       | 29.41%  |
| Unknown     | 3        | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 57       | 37.25%  |
| 1.01-2.0   | 28       | 18.3%   |
| 0.51-1.0   | 27       | 17.65%  |
| 7.01-8.0   | 12       | 7.84%   |
| 3.01-4.0   | 11       | 7.19%   |
| 0.01-0.5   | 10       | 6.54%   |
| 5.01-6.0   | 3        | 1.96%   |
| 2.01-3.0   | 3        | 1.96%   |
| 8.01-16.0  | 2        | 1.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 37       | 22.84%  |
| Dell                 | 21       | 12.96%  |
| AOC                  | 21       | 12.96%  |
| Philips              | 16       | 9.88%   |
| Acer                 | 15       | 9.26%   |
| Goldstar             | 14       | 8.64%   |
| Ancor Communications | 9        | 5.56%   |
| Hewlett-Packard      | 5        | 3.09%   |
| LG Electronics       | 3        | 1.85%   |
| BenQ                 | 3        | 1.85%   |
| Unknown              | 2        | 1.23%   |
| Huion                | 2        | 1.23%   |
| Grundig              | 2        | 1.23%   |
| Fujitsu Siemens      | 2        | 1.23%   |
| ASUSTek Computer     | 2        | 1.23%   |
| Vestel Elektronik    | 1        | 0.62%   |
| RTK                  | 1        | 0.62%   |
| Panasonic            | 1        | 0.62%   |
| NOA VISION           | 1        | 0.62%   |
| NEC Computers        | 1        | 0.62%   |
| LG Display           | 1        | 0.62%   |
| KTC                  | 1        | 0.62%   |
| InnoLux Display      | 1        | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0509 1920x1080                    | 2        | 1.14%   |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                   | 2        | 1.14%   |
| Huion Kamvas Pro 22 HAT2150 1920x1080 480x260mm 21.5-inch            | 2        | 1.14%   |
| Grundig WUXGA GRU4448 1920x1080                                      | 2        | 1.14%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 2        | 1.14%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 2        | 1.14%   |
| Dell LCD Monitor SE2416H 5760x1080                                   | 2        | 1.14%   |
| Dell LCD Monitor SE2416H                                             | 2        | 1.14%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                    | 2        | 1.14%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                    | 2        | 1.14%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 1.14%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 2        | 1.14%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 2        | 1.14%   |
| AOC 22B1WG5 AOC2201 1920x1080 479x260mm 21.5-inch                    | 2        | 1.14%   |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                    | 2        | 1.14%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                     | 1        | 0.57%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.57%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                          | 1        | 0.57%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.57%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch    | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0608 1920x1080 510x290mm 23.1-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM05C6 1920x1080 520x290mm 23.4-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch  | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch  | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 460x300mm 21.6-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM01E7 1920x1200 518x324mm 24.1-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM01B8 1280x1024 338x270mm 17.0-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0168 1280x1024 338x270mm 17.0-inch | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch | 1        | 0.57%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch | 1        | 0.57%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch    | 1        | 0.57%   |
| Samsung Electronics SMB1940 SAM06BA 1280x1024 376x301mm 19.0-inch    | 1        | 0.57%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 74       | 46.54%  |
| 2560x1440 (QHD)    | 13       | 8.18%   |
| 1280x1024 (SXGA)   | 12       | 7.55%   |
| 3840x2160 (4K)     | 10       | 6.29%   |
| 1680x1050 (WSXGA+) | 10       | 6.29%   |
| Unknown            | 8        | 5.03%   |
| 1920x1200 (WUXGA)  | 6        | 3.77%   |
| 1600x900 (HD+)     | 5        | 3.14%   |
| 3840x1080          | 4        | 2.52%   |
| 1360x768           | 4        | 2.52%   |
| 1440x900 (WXGA+)   | 3        | 1.89%   |
| 5760x1080          | 2        | 1.26%   |
| 2560x1080          | 2        | 1.26%   |
| 2048x1152          | 2        | 1.26%   |
| 1366x768 (WXGA)    | 2        | 1.26%   |
| 4480x1440          | 1        | 0.63%   |
| 2560x1600          | 1        | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 31       | 19.14%  |
| 27      | 22       | 13.58%  |
| 24      | 20       | 12.35%  |
| 21      | 19       | 11.73%  |
| Unknown | 19       | 11.73%  |
| 22      | 8        | 4.94%   |
| 19      | 8        | 4.94%   |
| 17      | 7        | 4.32%   |
| 20      | 6        | 3.7%    |
| 31      | 4        | 2.47%   |
| 54      | 3        | 1.85%   |
| 18      | 3        | 1.85%   |
| 84      | 2        | 1.23%   |
| 33      | 2        | 1.23%   |
| 25      | 2        | 1.23%   |
| 60      | 1        | 0.62%   |
| 58      | 1        | 0.62%   |
| 46      | 1        | 0.62%   |
| 34      | 1        | 0.62%   |
| 32      | 1        | 0.62%   |
| 26      | 1        | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 66       | 42.58%  |
| 401-500     | 37       | 23.87%  |
| Unknown     | 19       | 12.26%  |
| 601-700     | 9        | 5.81%   |
| 351-400     | 6        | 3.87%   |
| 301-350     | 6        | 3.87%   |
| 1001-1500   | 6        | 3.87%   |
| 701-800     | 4        | 2.58%   |
| 1501-2000   | 2        | 1.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 97       | 65.54%  |
| 16/10   | 21       | 14.19%  |
| Unknown | 17       | 11.49%  |
| 5/4     | 11       | 7.43%   |
| 3/2     | 1        | 0.68%   |
| 21/9    | 1        | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 57       | 36.08%  |
| 301-350        | 23       | 14.56%  |
| 151-200        | 23       | 14.56%  |
| Unknown        | 19       | 12.03%  |
| 251-300        | 10       | 6.33%   |
| 141-150        | 9        | 5.7%    |
| 351-500        | 8        | 5.06%   |
| More than 1000 | 7        | 4.43%   |
| 121-130        | 1        | 0.63%   |
| 501-1000       | 1        | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 91       | 61.07%  |
| 101-120 | 27       | 18.12%  |
| Unknown | 19       | 12.75%  |
| 1-50    | 6        | 4.03%   |
| 121-160 | 5        | 3.36%   |
| 161-240 | 1        | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 113      | 74.83%  |
| 2     | 28       | 18.54%  |
| 0     | 6        | 3.97%   |
| 3     | 3        | 1.99%   |
| 4     | 1        | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 94       | 44.34%  |
| Intel                             | 47       | 22.17%  |
| Qualcomm Atheros                  | 10       | 4.72%   |
| TP-Link                           | 7        | 3.3%    |
| Broadcom                          | 6        | 2.83%   |
| Ralink Technology                 | 5        | 2.36%   |
| Ralink                            | 5        | 2.36%   |
| Qualcomm Atheros Communications   | 5        | 2.36%   |
| Nvidia                            | 4        | 1.89%   |
| MediaTek                          | 3        | 1.42%   |
| D-Link                            | 3        | 1.42%   |
| Sundance Technology Inc / IC Plus | 2        | 0.94%   |
| Samsung Electronics               | 2        | 0.94%   |
| NetGear                           | 2        | 0.94%   |
| Marvell Technology Group          | 2        | 0.94%   |
| ASIX Electronics                  | 2        | 0.94%   |
| Xiaomi                            | 1        | 0.47%   |
| VIA Technologies                  | 1        | 0.47%   |
| T & A Mobile Phones               | 1        | 0.47%   |
| Nokia Mobile Phones               | 1        | 0.47%   |
| Microsoft                         | 1        | 0.47%   |
| Linksys                           | 1        | 0.47%   |
| ICS Advent                        | 1        | 0.47%   |
| Huawei Technologies               | 1        | 0.47%   |
| Edimax Technology                 | 1        | 0.47%   |
| D-Link System                     | 1        | 0.47%   |
| Broadcom Limited                  | 1        | 0.47%   |
| ASUSTek Computer                  | 1        | 0.47%   |
| Aquantia                          | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 80       | 35.56%  |
| Qualcomm Atheros AR9271 802.11n                                            | 5        | 2.22%   |
| Intel Wi-Fi 6 AX200                                                        | 5        | 2.22%   |
| Intel Ethernet Connection (2) I218-V                                       | 5        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                          | 4        | 1.78%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 1.78%   |
| Intel Ethernet Controller I225-V                                           | 4        | 1.78%   |
| Intel Ethernet Connection I217-V                                           | 4        | 1.78%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 1.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 3        | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.33%   |
| Ralink MT7601U Wireless Adapter                                            | 3        | 1.33%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 3        | 1.33%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.33%   |
| TP-Link 802.11ac NIC                                                       | 2        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 0.89%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 2        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.89%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                 | 2        | 0.89%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 0.89%   |
| NetGear A6210                                                              | 2        | 0.89%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 0.89%   |
| Intel Wireless 3165                                                        | 2        | 0.89%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 0.89%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.89%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 0.89%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 0.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 2        | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.44%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 1        | 0.44%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 0.44%   |
| T & A Mobile Phones 9010X                                                  | 1        | 0.44%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.44%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 17.24%  |
| TP-Link                         | 7        | 12.07%  |
| Realtek Semiconductor           | 7        | 12.07%  |
| Ralink Technology               | 5        | 8.62%   |
| Ralink                          | 5        | 8.62%   |
| Qualcomm Atheros Communications | 5        | 8.62%   |
| Qualcomm Atheros                | 4        | 6.9%    |
| Broadcom                        | 4        | 6.9%    |
| D-Link                          | 3        | 5.17%   |
| NetGear                         | 2        | 3.45%   |
| MediaTek                        | 2        | 3.45%   |
| Microsoft                       | 1        | 1.72%   |
| Linksys                         | 1        | 1.72%   |
| Edimax Technology               | 1        | 1.72%   |
| ASUSTek Computer                | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                         | 5        | 8.47%   |
| Intel Wi-Fi 6 AX200                                                     | 5        | 8.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3        | 5.08%   |
| Ralink MT7601U Wireless Adapter                                         | 3        | 5.08%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 3        | 5.08%   |
| TP-Link 802.11ac NIC                                                    | 2        | 3.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 3.39%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 2        | 3.39%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2        | 3.39%   |
| NetGear A6210                                                           | 2        | 3.39%   |
| Intel Wireless 3165                                                     | 2        | 3.39%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2        | 3.39%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 1.69%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1        | 1.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 1.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.69%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                  | 1        | 1.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1        | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1        | 1.69%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.69%   |
| Ralink RT2070 Wireless Adapter                                          | 1        | 1.69%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1        | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.69%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 1.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1        | 1.69%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1        | 1.69%   |
| Linksys WUSB6400M                                                       | 1        | 1.69%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 1.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 1.69%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                | 1        | 1.69%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]    | 1        | 1.69%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.69%   |
| D-Link 11ac adapter                                                     | 1        | 1.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 1.69%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1        | 1.69%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]         | 1        | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 90       | 56.25%  |
| Intel                             | 42       | 26.25%  |
| Qualcomm Atheros                  | 6        | 3.75%   |
| Nvidia                            | 4        | 2.5%    |
| Sundance Technology Inc / IC Plus | 2        | 1.25%   |
| Marvell Technology Group          | 2        | 1.25%   |
| Broadcom                          | 2        | 1.25%   |
| ASIX Electronics                  | 2        | 1.25%   |
| Xiaomi                            | 1        | 0.63%   |
| VIA Technologies                  | 1        | 0.63%   |
| T & A Mobile Phones               | 1        | 0.63%   |
| Samsung Electronics               | 1        | 0.63%   |
| MediaTek                          | 1        | 0.63%   |
| ICS Advent                        | 1        | 0.63%   |
| Huawei Technologies               | 1        | 0.63%   |
| D-Link System                     | 1        | 0.63%   |
| Broadcom Limited                  | 1        | 0.63%   |
| Aquantia                          | 1        | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 80       | 48.78%  |
| Intel Ethernet Connection (2) I218-V                                       | 5        | 3.05%   |
| Realtek RTL8125 2.5GbE Controller                                          | 4        | 2.44%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.44%   |
| Intel Ethernet Controller I225-V                                           | 4        | 2.44%   |
| Intel Ethernet Connection I217-V                                           | 4        | 2.44%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.83%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.22%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 1.22%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.22%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 1.22%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.22%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 1.22%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 1.22%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.61%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.61%   |
| T & A Mobile Phones 9010X                                                  | 1        | 0.61%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.61%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.61%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.61%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.61%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.61%   |
| MediaTek Titan pocket                                                      | 1        | 0.61%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.61%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.61%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.61%   |
| Intel Ethernet Connection (11) I219-LM                                     | 1        | 0.61%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 144      | 72.36%  |
| WiFi     | 53       | 26.63%  |
| Modem    | 2        | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 110      | 74.32%  |
| WiFi     | 38       | 25.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 107      | 72.3%   |
| 2     | 36       | 24.32%  |
| 0     | 3        | 2.03%   |
| 4     | 1        | 0.68%   |
| 3     | 1        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 141      | 95.27%  |
| Yes  | 7        | 4.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 31.25%  |
| Cambridge Silicon Radio         | 7        | 21.88%  |
| Broadcom                        | 4        | 12.5%   |
| Realtek Semiconductor           | 2        | 6.25%   |
| Integrated System Solution      | 2        | 6.25%   |
| Foxconn / Hon Hai               | 2        | 6.25%   |
| ASUSTek Computer                | 2        | 6.25%   |
| TP-Link                         | 1        | 3.13%   |
| Qualcomm Atheros Communications | 1        | 3.13%   |
| IMC Networks                    | 1        | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 21.88%  |
| Intel AX200 Bluetooth                                 | 5        | 15.63%  |
| Intel Bluetooth wireless interface                    | 3        | 9.38%   |
| Realtek Bluetooth Radio                               | 2        | 6.25%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 6.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 6.25%   |
| TP-Link UB500 Adapter                                 | 1        | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 3.13%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 3.13%   |
| Intel AX201 Bluetooth                                 | 1        | 3.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 3.13%   |
| Integrated System Solution Bluetooth Device           | 1        | 3.13%   |
| IMC Networks BCM20702A0                               | 1        | 3.13%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 3.13%   |
| Foxconn / Hon Hai BT                                  | 1        | 3.13%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 3.13%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 91       | 34.73%  |
| AMD                 | 77       | 29.39%  |
| Nvidia              | 59       | 22.52%  |
| C-Media Electronics | 10       | 3.82%   |
| Logitech            | 4        | 1.53%   |
| Creative Labs       | 3        | 1.15%   |
| Microsoft           | 2        | 0.76%   |
| Yamaha              | 1        | 0.38%   |
| XMOS                | 1        | 0.38%   |
| VIA Technologies    | 1        | 0.38%   |
| Trust               | 1        | 0.38%   |
| Tenx Technology     | 1        | 0.38%   |
| Razer USA           | 1        | 0.38%   |
| Native Instruments  | 1        | 0.38%   |
| MCS                 | 1        | 0.38%   |
| Kingston Technology | 1        | 0.38%   |
| JMTek               | 1        | 0.38%   |
| Focusrite-Novation  | 1        | 0.38%   |
| Ensoniq             | 1        | 0.38%   |
| Cirrus Logic        | 1        | 0.38%   |
| ATI Technologies    | 1        | 0.38%   |
| ASUSTek Computer    | 1        | 0.38%   |
| Astro Gaming        | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16       | 5.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 3.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 3.97%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 3.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 3.31%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 2.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 2.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 2.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 2.32%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 2.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 2.32%   |
| Nvidia GM206 High Definition Audio Controller                              | 6        | 1.99%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 1.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 6        | 1.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.66%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 1.66%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 1.66%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.32%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 1.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.32%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 4        | 1.32%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4        | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 0.99%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.99%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.99%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.66%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.66%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 26       | 30.95%  |
| Corsair             | 11       | 13.1%   |
| G.Skill             | 10       | 11.9%   |
| Unknown             | 9        | 10.71%  |
| Samsung Electronics | 7        | 8.33%   |
| SK hynix            | 5        | 5.95%   |
| Crucial             | 4        | 4.76%   |
| Transcend           | 3        | 3.57%   |
| Patriot             | 2        | 2.38%   |
| Kingmax             | 2        | 2.38%   |
| Ramaxel Technology  | 1        | 1.19%   |
| Mushkin             | 1        | 1.19%   |
| Elpida              | 1        | 1.19%   |
| Apacer              | 1        | 1.19%   |
| A-DATA Technology   | 1        | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 3        | 3.33%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                   | 2        | 2.22%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s      | 2        | 2.22%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 2        | 2.22%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s     | 2        | 2.22%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 2        | 2.22%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 2.22%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s               | 1        | 1.11%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.11%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 1.11%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.11%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                     | 1        | 1.11%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 1.11%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                  | 1        | 1.11%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                 | 1        | 1.11%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s               | 1        | 1.11%   |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s    | 1        | 1.11%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s     | 1        | 1.11%   |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s        | 1        | 1.11%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s        | 1        | 1.11%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 1.11%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.11%   |
| SK hynix RAM HMT125U6BFR8C-H9 2GB DIMM SDRAM 1333MT/s    | 1        | 1.11%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s    | 1        | 1.11%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s     | 1        | 1.11%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s | 1        | 1.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 1.11%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.11%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s      | 1        | 1.11%   |
| Ramaxel RAM RMUA5090KE68H9F2133 4GB DIMM DDR4 2133MT/s   | 1        | 1.11%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.11%   |
| Patriot RAM PSD22G80026 2GB DIMM DDR2 800MT/s            | 1        | 1.11%   |
| Mushkin RAM 99[2/7/4]199[F/T] 8192MB DIMM DDR4 2400MT/s  | 1        | 1.11%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s      | 1        | 1.11%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 1.11%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s     | 1        | 1.11%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 1.11%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s     | 1        | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 37       | 51.39%  |
| DDR3    | 24       | 33.33%  |
| Unknown | 4        | 5.56%   |
| DDR2    | 3        | 4.17%   |
| SDRAM   | 2        | 2.78%   |
| DDR5    | 1        | 1.39%   |
| DDR     | 1        | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 68       | 95.77%  |
| SODIMM | 3        | 4.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 30       | 38.46%  |
| 4096  | 21       | 26.92%  |
| 16384 | 12       | 15.38%  |
| 2048  | 10       | 12.82%  |
| 1024  | 3        | 3.85%   |
| 32768 | 1        | 1.28%   |
| 512   | 1        | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 14       | 18.42%  |
| 3200  | 10       | 13.16%  |
| 2667  | 8        | 10.53%  |
| 2400  | 7        | 9.21%   |
| 1333  | 7        | 9.21%   |
| 3400  | 4        | 5.26%   |
| 3600  | 3        | 3.95%   |
| 2133  | 3        | 3.95%   |
| 3866  | 2        | 2.63%   |
| 1800  | 2        | 2.63%   |
| 800   | 2        | 2.63%   |
| 667   | 2        | 2.63%   |
| 4800  | 1        | 1.32%   |
| 4000  | 1        | 1.32%   |
| 3533  | 1        | 1.32%   |
| 3334  | 1        | 1.32%   |
| 3333  | 1        | 1.32%   |
| 2933  | 1        | 1.32%   |
| 2800  | 1        | 1.32%   |
| 2666  | 1        | 1.32%   |
| 1867  | 1        | 1.32%   |
| 1067  | 1        | 1.32%   |
| 533   | 1        | 1.32%   |
| 400   | 1        | 1.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 66.67%  |
| Prolific Technology | 2        | 22.22%  |
| Canon               | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Prolific PL2305 Parallel Port   | 2        | 22.22%  |
| HP DeskJet 3630 series          | 2        | 22.22%  |
| HP LaserJet M14-M17             | 1        | 11.11%  |
| HP LaserJet M101-M106           | 1        | 11.11%  |
| HP Ink Tank Wireless 410 series | 1        | 11.11%  |
| HP DeskJet 2130 series          | 1        | 11.11%  |
| Canon PIXMA iP1800 Printer      | 1        | 11.11%  |

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
| Realtek FULL HD 1080P Webcam          | 2        | 7.41%   |
| Microdia Camera                       | 2        | 7.41%   |
| Logitech Webcam C170                  | 2        | 7.41%   |
| Trust Full HD Webcam                  | 1        | 3.7%    |
| Sunplus papalook AF 925               | 1        | 3.7%    |
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
| Alcor Micro USB 2.0 Camera            | 1        | 3.7%    |

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
| 0     | 133      | 88.67%  |
| 1     | 13       | 8.67%   |
| 2     | 4        | 2.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 30%     |
| Net/wireless             | 4        | 20%     |
| Bluetooth                | 3        | 15%     |
| Unassigned class         | 2        | 10%     |
| Chipcard                 | 2        | 10%     |
| Storage/raid             | 1        | 5%      |
| Fingerprint reader       | 1        | 5%      |
| Communication controller | 1        | 5%      |


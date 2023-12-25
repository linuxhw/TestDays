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

Total: 236

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MPG B760I EDGE WIFI DDR4    | [58bbd67a73](https://linux-hardware.org/?probe=58bbd67a73) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| Dell          | 0R790T A00                  | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| eMachines     | ET1850                      | [b433ca3cfa](https://linux-hardware.org/?probe=b433ca3cfa) | Dec 02, 2023 |
| MSI           | PRO B650M-A WIFI            | [2a9ba6fc77](https://linux-hardware.org/?probe=2a9ba6fc77) | Nov 17, 2023 |
| HP            | 18E4                        | [fb73ea4228](https://linux-hardware.org/?probe=fb73ea4228) | Nov 12, 2023 |
| ASRock        | B450M-HDV R4.0              | [c019f410aa](https://linux-hardware.org/?probe=c019f410aa) | Nov 08, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [24304767eb](https://linux-hardware.org/?probe=24304767eb) | Oct 21, 2023 |
| Intel         | DG965RY AAD41691-301        | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
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
| Ubuntu 20.04                 | 20       | 11.3%   |
| Ubuntu 18.04                 | 14       | 7.91%   |
| Debian 11                    | 7        | 3.95%   |
| OpenMandriva 4.3             | 6        | 3.39%   |
| Linux Mint 20.3              | 6        | 3.39%   |
| Linux Mint 20.2              | 6        | 3.39%   |
| Ubuntu 18.10                 | 5        | 2.82%   |
| Zorin 16                     | 4        | 2.26%   |
| Ubuntu 22.04                 | 4        | 2.26%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 2.26%   |
| Manjaro                      | 4        | 2.26%   |
| Fedora 38                    | 4        | 2.26%   |
| Debian 10                    | 4        | 2.26%   |
| Ubuntu MATE 22.04            | 3        | 1.69%   |
| Ubuntu 19.10                 | 3        | 1.69%   |
| Pop!_OS 21.10                | 3        | 1.69%   |
| OpenMandriva 4.2             | 3        | 1.69%   |
| Fedora 31                    | 3        | 1.69%   |
| ArcoLinux Rolling            | 3        | 1.69%   |
| Ubuntu 21.04                 | 2        | 1.13%   |
| Pop!_OS 20.10                | 2        | 1.13%   |
| openSUSE Leap-15.2           | 2        | 1.13%   |
| OpenMandriva 4.50            | 2        | 1.13%   |
| OpenMandriva 23.11           | 2        | 1.13%   |
| OpenMandriva 23.03           | 2        | 1.13%   |
| Linux Mint 20                | 2        | 1.13%   |
| KDE neon 20.04               | 2        | 1.13%   |
| EndeavourOS Rolling          | 2        | 1.13%   |
| Debian 12                    | 2        | 1.13%   |
| Zorin 15                     | 1        | 0.56%   |
| Xubuntu 20.04                | 1        | 0.56%   |
| Xubuntu 18.04                | 1        | 0.56%   |
| Ubuntu Unity 18.04           | 1        | 0.56%   |
| Ubuntu MATE 20.04            | 1        | 0.56%   |
| Ubuntu MATE 19.10            | 1        | 0.56%   |
| Ubuntu Budgie 22.04          | 1        | 0.56%   |
| Ubuntu Budgie 20.04          | 1        | 0.56%   |
| Ubuntu Budgie 18.04          | 1        | 0.56%   |
| Ubuntu 22.10                 | 1        | 0.56%   |
| Ubuntu 21.10                 | 1        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 52       | 31.33%  |
| Linux Mint    | 18       | 10.84%  |
| OpenMandriva  | 17       | 10.24%  |
| Debian        | 11       | 6.63%   |
| Pop!_OS       | 9        | 5.42%   |
| Manjaro       | 9        | 5.42%   |
| Fedora        | 8        | 4.82%   |
| openSUSE      | 6        | 3.61%   |
| Zorin         | 5        | 3.01%   |
| Ubuntu MATE   | 3        | 1.81%   |
| Ubuntu Budgie | 3        | 1.81%   |
| KDE neon      | 3        | 1.81%   |
| ArcoLinux     | 3        | 1.81%   |
| Xubuntu       | 2        | 1.2%    |
| Gentoo        | 2        | 1.2%    |
| EndeavourOS   | 2        | 1.2%    |
| Arch          | 2        | 1.2%    |
| Ubuntu Unity  | 1        | 0.6%    |
| ROSA          | 1        | 0.6%    |
| Nobara        | 1        | 0.6%    |
| MX            | 1        | 0.6%    |
| Lubuntu       | 1        | 0.6%    |
| LMDE          | 1        | 0.6%    |
| LinuxFX       | 1        | 0.6%    |
| Kubuntu       | 1        | 0.6%    |
| Endless       | 1        | 0.6%    |
| Elementary    | 1        | 0.6%    |
| Clear Linux   | 1        | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003      | 6        | 3.06%   |
| 5.4.0-58-generic             | 4        | 2.04%   |
| 6.2.9-300.fc38.x86_64        | 3        | 1.53%   |
| 5.4.0-91-generic             | 3        | 1.53%   |
| 5.3.0-26-generic             | 3        | 1.53%   |
| 5.10.14-desktop-1omv4002     | 3        | 1.53%   |
| 5.0.0-27-generic             | 3        | 1.53%   |
| 6.6.2-desktop-1omv2390       | 2        | 1.02%   |
| 6.2.6-desktop-1omv2390       | 2        | 1.02%   |
| 5.8.0-48-generic             | 2        | 1.02%   |
| 5.4.0-48-generic             | 2        | 1.02%   |
| 5.4.0-42-generic             | 2        | 1.02%   |
| 5.4.0-26-generic             | 2        | 1.02%   |
| 5.4.0-100-generic            | 2        | 1.02%   |
| 5.3.0-42-generic             | 2        | 1.02%   |
| 5.3.0-28-generic             | 2        | 1.02%   |
| 5.15.0-52-generic            | 2        | 1.02%   |
| 5.15.0-48-generic            | 2        | 1.02%   |
| 5.13.0-40-generic            | 2        | 1.02%   |
| 5.12.4-desktop-1omv4050      | 2        | 1.02%   |
| 5.11.0-41-generic            | 2        | 1.02%   |
| 5.11.0-38-generic            | 2        | 1.02%   |
| 5.11.0-37-generic            | 2        | 1.02%   |
| 5.10.0-13-amd64              | 2        | 1.02%   |
| 4.19.0-14-amd64              | 2        | 1.02%   |
| 4.18.0-10-generic            | 2        | 1.02%   |
| 4.15.0-45-generic            | 2        | 1.02%   |
| 4.15.0-20-generic            | 2        | 1.02%   |
| 6.6.0-desktop-1omv2390       | 1        | 0.51%   |
| 6.5.9-zen2-1-zen             | 1        | 0.51%   |
| 6.5.4-76060504-generic       | 1        | 0.51%   |
| 6.5.4-1-default              | 1        | 0.51%   |
| 6.5.13-6-MANJARO             | 1        | 0.51%   |
| 6.4.15-200.fc38.x86_64       | 1        | 0.51%   |
| 6.4.11-desktop-1omv2390      | 1        | 0.51%   |
| 6.3.4-zen1-1-zen             | 1        | 0.51%   |
| 6.3.13-2-MANJARO             | 1        | 0.51%   |
| 6.2.14-300.fsync.fc37.x86_64 | 1        | 0.51%   |
| 6.2.0-35-generic             | 1        | 0.51%   |
| 6.1.8-201.fsync.fc37.x86_64  | 1        | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 18.03%  |
| 5.11.0  | 12       | 6.56%   |
| 5.3.0   | 11       | 6.01%   |
| 4.15.0  | 10       | 5.46%   |
| 5.15.0  | 8        | 4.37%   |
| 5.10.0  | 8        | 4.37%   |
| 4.18.0  | 8        | 4.37%   |
| 5.16.7  | 6        | 3.28%   |
| 5.13.0  | 6        | 3.28%   |
| 5.8.0   | 5        | 2.73%   |
| 5.0.0   | 4        | 2.19%   |
| 6.2.9   | 3        | 1.64%   |
| 5.12.4  | 3        | 1.64%   |
| 5.10.14 | 3        | 1.64%   |
| 4.19.0  | 3        | 1.64%   |
| 6.6.2   | 2        | 1.09%   |
| 6.5.4   | 2        | 1.09%   |
| 6.2.6   | 2        | 1.09%   |
| 6.1.0   | 2        | 1.09%   |
| 5.3.18  | 2        | 1.09%   |
| 5.19.0  | 2        | 1.09%   |
| 5.16.11 | 2        | 1.09%   |
| 6.6.0   | 1        | 0.55%   |
| 6.5.9   | 1        | 0.55%   |
| 6.5.13  | 1        | 0.55%   |
| 6.4.15  | 1        | 0.55%   |
| 6.4.11  | 1        | 0.55%   |
| 6.3.4   | 1        | 0.55%   |
| 6.3.13  | 1        | 0.55%   |
| 6.2.14  | 1        | 0.55%   |
| 6.2.0   | 1        | 0.55%   |
| 6.1.8   | 1        | 0.55%   |
| 6.1.38  | 1        | 0.55%   |
| 6.0.6   | 1        | 0.55%   |
| 6.0.5   | 1        | 0.55%   |
| 5.9.0   | 1        | 0.55%   |
| 5.7.11  | 1        | 0.55%   |
| 5.7.0   | 1        | 0.55%   |
| 5.6.12  | 1        | 0.55%   |
| 5.4.64  | 1        | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 20.44%  |
| 5.10    | 15       | 8.29%   |
| 5.3     | 14       | 7.73%   |
| 5.15    | 13       | 7.18%   |
| 5.11    | 13       | 7.18%   |
| 4.15    | 10       | 5.52%   |
| 5.16    | 8        | 4.42%   |
| 4.18    | 8        | 4.42%   |
| 6.2     | 7        | 3.87%   |
| 5.13    | 6        | 3.31%   |
| 5.8     | 5        | 2.76%   |
| 5.19    | 5        | 2.76%   |
| 6.5     | 4        | 2.21%   |
| 6.1     | 4        | 2.21%   |
| 5.0     | 4        | 2.21%   |
| 6.6     | 3        | 1.66%   |
| 5.18    | 3        | 1.66%   |
| 5.12    | 3        | 1.66%   |
| 4.19    | 3        | 1.66%   |
| 6.4     | 2        | 1.1%    |
| 6.3     | 2        | 1.1%    |
| 6.0     | 2        | 1.1%    |
| 5.7     | 2        | 1.1%    |
| 5.17    | 2        | 1.1%    |
| 5.14    | 2        | 1.1%    |
| 5.9     | 1        | 0.55%   |
| 5.6     | 1        | 0.55%   |
| 4.14    | 1        | 0.55%   |
| 4.13    | 1        | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 159      | 98.76%  |
| i686   | 2        | 1.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 62       | 37.35%  |
| KDE5       | 39       | 23.49%  |
| Unknown    | 22       | 13.25%  |
| X-Cinnamon | 11       | 6.63%   |
| XFCE       | 8        | 4.82%   |
| MATE       | 5        | 3.01%   |
| KDE        | 4        | 2.41%   |
| Cinnamon   | 4        | 2.41%   |
| Budgie     | 3        | 1.81%   |
| Unity      | 1        | 0.6%    |
| ubuntu     | 1        | 0.6%    |
| Pantheon   | 1        | 0.6%    |
| openbox    | 1        | 0.6%    |
| LXQt       | 1        | 0.6%    |
| LXDE       | 1        | 0.6%    |
| i3         | 1        | 0.6%    |
| DWM        | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 132      | 79.52%  |
| Wayland | 19       | 11.45%  |
| Unknown | 10       | 6.02%   |
| Tty     | 5        | 3.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 88       | 52.38%  |
| SDDM    | 33       | 19.64%  |
| LightDM | 18       | 10.71%  |
| GDM3    | 13       | 7.74%   |
| GDM     | 12       | 7.14%   |
| TDM     | 4        | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 89       | 53.61%  |
| hr_HR   | 42       | 25.3%   |
| Unknown | 25       | 15.06%  |
| en_GB   | 8        | 4.82%   |
| C       | 2        | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 89       | 54.94%  |
| EFI  | 73       | 45.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 125      | 75.76%  |
| Overlay | 16       | 9.7%    |
| Btrfs   | 16       | 9.7%    |
| Unknown | 4        | 2.42%   |
| Zfs     | 3        | 1.82%   |
| Xfs     | 1        | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 91       | 55.49%  |
| GPT     | 55       | 33.54%  |
| MBR     | 18       | 10.98%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 77.84%  |
| Yes       | 37       | 22.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 104      | 63.03%  |
| Yes       | 61       | 36.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 40       | 24.84%  |
| ASUSTek Computer    | 38       | 23.6%   |
| Gigabyte Technology | 29       | 18.01%  |
| MSI                 | 14       | 8.7%    |
| Hewlett-Packard     | 10       | 6.21%   |
| Intel               | 6        | 3.73%   |
| Pegatron            | 5        | 3.11%   |
| Dell                | 5        | 3.11%   |
| Lenovo              | 3        | 1.86%   |
| ECS                 | 3        | 1.86%   |
| WinFast             | 1        | 0.62%   |
| HPE                 | 1        | 0.62%   |
| Fujitsu Siemens     | 1        | 0.62%   |
| Foxconn             | 1        | 0.62%   |
| eMachines           | 1        | 0.62%   |
| Acer                | 1        | 0.62%   |
| ABIT                | 1        | 0.62%   |
| Unknown             | 1        | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 6        | 3.73%   |
| ASRock B450M-HDV R4.0                  | 4        | 2.48%   |
| ASUS PRIME A320M-K                     | 3        | 1.86%   |
| MSI MS-7850                            | 2        | 1.24%   |
| Intel DH61CR AAG14064-204              | 2        | 1.24%   |
| Gigabyte A320M-S2H                     | 2        | 1.24%   |
| ASUS P8H77-V LE                        | 2        | 1.24%   |
| ASUS M5A78L LE                         | 2        | 1.24%   |
| ASRock H61M-DGS                        | 2        | 1.24%   |
| WinFast N570SM2AA                      | 1        | 0.62%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.62%   |
| Pegatron HPE-520ad                     | 1        | 0.62%   |
| Pegatron G5261de                       | 1        | 0.62%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 0.62%   |
| Pegatron 27-1001eu                     | 1        | 0.62%   |
| MSI MS-7D77                            | 1        | 0.62%   |
| MSI MS-7D40                            | 1        | 0.62%   |
| MSI MS-7D25                            | 1        | 0.62%   |
| MSI MS-7C02                            | 1        | 0.62%   |
| MSI MS-7B98                            | 1        | 0.62%   |
| MSI MS-7B84                            | 1        | 0.62%   |
| MSI MS-7B07                            | 1        | 0.62%   |
| MSI MS-7817                            | 1        | 0.62%   |
| MSI MS-7681                            | 1        | 0.62%   |
| MSI MS-7586                            | 1        | 0.62%   |
| MSI MS-7360                            | 1        | 0.62%   |
| MSI 0A90                               | 1        | 0.62%   |
| Lenovo ThinkStation P310 30AT0029GE    | 1        | 0.62%   |
| Lenovo ThinkCentre A58 77057FG         | 1        | 0.62%   |
| Lenovo S510                            | 1        | 0.62%   |
| Intel H61M-S2PV                        | 1        | 0.62%   |
| Intel DX58SO AAE29331-501              | 1        | 0.62%   |
| Intel DH67BL AAG10189-213              | 1        | 0.62%   |
| Intel DG965RY AAD41691-301             | 1        | 0.62%   |
| HPE ProLiant ML30 Gen10 Plus           | 1        | 0.62%   |
| HP Z840 Workstation                    | 1        | 0.62%   |
| HP Z440 Workstation                    | 1        | 0.62%   |
| HP ProOne 400 G1 AiO                   | 1        | 0.62%   |
| HP ProDesk 600 G4 PCI MT               | 1        | 0.62%   |
| HP ProDesk 600 G1 SFF                  | 1        | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 8        | 4.97%   |
| ASUS All            | 6        | 3.73%   |
| ASUS TUF            | 4        | 2.48%   |
| ASRock B450M-HDV    | 4        | 2.48%   |
| HP EliteDesk        | 3        | 1.86%   |
| Dell Vostro         | 3        | 1.86%   |
| ASUS ROG            | 3        | 1.86%   |
| MSI MS-7850         | 2        | 1.24%   |
| Intel DH61CR        | 2        | 1.24%   |
| HP ProDesk          | 2        | 1.24%   |
| Gigabyte Z390       | 2        | 1.24%   |
| Gigabyte B450       | 2        | 1.24%   |
| Gigabyte A320M-S2H  | 2        | 1.24%   |
| Dell OptiPlex       | 2        | 1.24%   |
| ASUS P8H77-V        | 2        | 1.24%   |
| ASUS M5A78L         | 2        | 1.24%   |
| ASRock H97          | 2        | 1.24%   |
| ASRock H61M-DGS     | 2        | 1.24%   |
| ASRock B550M        | 2        | 1.24%   |
| ASRock A320M-HDV    | 2        | 1.24%   |
| WinFast N570SM2AA   | 1        | 0.62%   |
| Pegatron Pro        | 1        | 0.62%   |
| Pegatron HPE-520ad  | 1        | 0.62%   |
| Pegatron G5261de    | 1        | 0.62%   |
| Pegatron Compaq     | 1        | 0.62%   |
| Pegatron 27-1001eu  | 1        | 0.62%   |
| MSI MS-7D77         | 1        | 0.62%   |
| MSI MS-7D40         | 1        | 0.62%   |
| MSI MS-7D25         | 1        | 0.62%   |
| MSI MS-7C02         | 1        | 0.62%   |
| MSI MS-7B98         | 1        | 0.62%   |
| MSI MS-7B84         | 1        | 0.62%   |
| MSI MS-7B07         | 1        | 0.62%   |
| MSI MS-7817         | 1        | 0.62%   |
| MSI MS-7681         | 1        | 0.62%   |
| MSI MS-7586         | 1        | 0.62%   |
| MSI MS-7360         | 1        | 0.62%   |
| MSI 0A90            | 1        | 0.62%   |
| Lenovo ThinkStation | 1        | 0.62%   |
| Lenovo ThinkCentre  | 1        | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 19       | 11.8%   |
| 2018 | 17       | 10.56%  |
| 2017 | 13       | 8.07%   |
| 2012 | 13       | 8.07%   |
| 2011 | 13       | 8.07%   |
| 2020 | 12       | 7.45%   |
| 2021 | 10       | 6.21%   |
| 2009 | 9        | 5.59%   |
| 2019 | 8        | 4.97%   |
| 2014 | 8        | 4.97%   |
| 2010 | 8        | 4.97%   |
| 2015 | 7        | 4.35%   |
| 2008 | 7        | 4.35%   |
| 2022 | 6        | 3.73%   |
| 2007 | 6        | 3.73%   |
| 2006 | 2        | 1.24%   |
| 2005 | 2        | 1.24%   |
| 2023 | 1        | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 161      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 155      | 95.68%  |
| Enabled  | 7        | 4.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 161      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 42       | 25.45%  |
| 8.01-16.0   | 42       | 25.45%  |
| 4.01-8.0    | 25       | 15.15%  |
| 32.01-64.0  | 19       | 11.52%  |
| 3.01-4.0    | 19       | 11.52%  |
| 1.01-2.0    | 8        | 4.85%   |
| 24.01-32.0  | 5        | 3.03%   |
| 64.01-256.0 | 4        | 2.42%   |
| 2.01-3.0    | 1        | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 69       | 38.98%  |
| 2.01-3.0   | 45       | 25.42%  |
| 4.01-8.0   | 24       | 13.56%  |
| 3.01-4.0   | 19       | 10.73%  |
| 0.51-1.0   | 8        | 4.52%   |
| 8.01-16.0  | 7        | 3.95%   |
| 16.01-24.0 | 4        | 2.26%   |
| 0.01-0.5   | 1        | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 61       | 35.88%  |
| 2      | 51       | 30%     |
| 3      | 29       | 17.06%  |
| 4      | 13       | 7.65%   |
| 5      | 10       | 5.88%   |
| 6      | 2        | 1.18%   |
| 0      | 2        | 1.18%   |
| 8      | 1        | 0.59%   |
| 7      | 1        | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 50.31%  |
| Yes       | 81       | 49.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 158      | 98.14%  |
| No        | 3        | 1.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 63.19%  |
| Yes       | 60       | 36.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 127      | 77.91%  |
| Yes       | 36       | 22.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Croatia | 161      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Zagreb          | 84       | 47.19%  |
| Split           | 13       | 7.3%    |
| Rijeka          | 11       | 6.18%   |
| Osijek          | 5        | 2.81%   |
| Velika Gorica   | 4        | 2.25%   |
| Pula            | 4        | 2.25%   |
| Zaprešić      | 3        | 1.69%   |
| Varaždin       | 3        | 1.69%   |
| Samobor         | 3        | 1.69%   |
| Koprivnica      | 3        | 1.69%   |
| Bjelovar        | 3        | 1.69%   |
| Virovitica      | 2        | 1.12%   |
| Slatina         | 2        | 1.12%   |
| Pitomaca        | 2        | 1.12%   |
| Ivanja Reka     | 2        | 1.12%   |
| GJurgevac       | 2        | 1.12%   |
| Zadar           | 1        | 0.56%   |
| Visnjevac       | 1        | 0.56%   |
| Supetar         | 1        | 0.56%   |
| Stari Perkovci  | 1        | 0.56%   |
| Skrad           | 1        | 0.56%   |
| Sisak           | 1        | 0.56%   |
| Sesvete         | 1        | 0.56%   |
| Raslina         | 1        | 0.56%   |
| Prelog          | 1        | 0.56%   |
| Postira         | 1        | 0.56%   |
| Novi Marof      | 1        | 0.56%   |
| Nerezine        | 1        | 0.56%   |
| Matulji         | 1        | 0.56%   |
| Mali Lošinj    | 1        | 0.56%   |
| Mahicno         | 1        | 0.56%   |
| Lovran          | 1        | 0.56%   |
| Labin           | 1        | 0.56%   |
| Kućan Marof    | 1        | 0.56%   |
| Krizevci        | 1        | 0.56%   |
| Krapina         | 1        | 0.56%   |
| Kastel Gomilica | 1        | 0.56%   |
| Jesenice        | 1        | 0.56%   |
| Hvar            | 1        | 0.56%   |
| Grad            | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 71       | 129    | 24.15%  |
| Samsung Electronics         | 36       | 61     | 12.24%  |
| Kingston                    | 35       | 53     | 11.9%   |
| Seagate                     | 31       | 46     | 10.54%  |
| Toshiba                     | 22       | 36     | 7.48%   |
| Crucial                     | 19       | 27     | 6.46%   |
| Intel                       | 11       | 13     | 3.74%   |
| A-DATA Technology           | 11       | 15     | 3.74%   |
| SanDisk                     | 5        | 8      | 1.7%    |
| Patriot                     | 5        | 8      | 1.7%    |
| Hitachi                     | 5        | 8      | 1.7%    |
| Transcend                   | 3        | 7      | 1.02%   |
| Silicon Motion              | 3        | 4      | 1.02%   |
| Phison                      | 3        | 3      | 1.02%   |
| OCZ                         | 2        | 3      | 0.68%   |
| Maxtor                      | 2        | 2      | 0.68%   |
| HPE                         | 2        | 4      | 0.68%   |
| Gigabyte Technology         | 2        | 2      | 0.68%   |
| Corsair                     | 2        | 2      | 0.68%   |
| XPG                         | 1        | 3      | 0.34%   |
| Unknown                     | 1        | 1      | 0.34%   |
| TO Exter                    | 1        | 1      | 0.34%   |
| SPCC                        | 1        | 1      | 0.34%   |
| Realtek Semiconductor       | 1        | 1      | 0.34%   |
| PNY                         | 1        | 1      | 0.34%   |
| Phison Electronics          | 1        | 1      | 0.34%   |
| Netac                       | 1        | 1      | 0.34%   |
| Mushkin                     | 1        | 2      | 0.34%   |
| Min Yi U                    | 1        | 1      | 0.34%   |
| Micron/Crucial Technology   | 1        | 1      | 0.34%   |
| Micron Technology           | 1        | 1      | 0.34%   |
| Kingston Technology Company | 1        | 1      | 0.34%   |
| KingSpec                    | 1        | 1      | 0.34%   |
| Kingmax                     | 1        | 1      | 0.34%   |
| INNOVATION IT               | 1        | 1      | 0.34%   |
| HGST HTS                    | 1        | 1      | 0.34%   |
| HGST                        | 1        | 1      | 0.34%   |
| GOODRAM                     | 1        | 1      | 0.34%   |
| External                    | 1        | 1      | 0.34%   |
| China                       | 1        | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD   | 6        | 1.75%   |
| Toshiba HDWD130 3TB               | 5        | 1.46%   |
| Kingston SV300S37A120G 120GB SSD  | 5        | 1.46%   |
| Kingston SA400S37240G 240GB SSD   | 5        | 1.46%   |
| Kingston SA400S37120G 120GB SSD   | 5        | 1.46%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4        | 1.17%   |
| Toshiba HDWD110 1TB               | 4        | 1.17%   |
| Samsung SSD 850 EVO 250GB         | 4        | 1.17%   |
| WDC WD5000AAKX-001CA0 500GB       | 3        | 0.87%   |
| Toshiba DT01ACA100 1TB            | 3        | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 0.87%   |
| SanDisk SDSSDA240G 240GB          | 3        | 0.87%   |
| Samsung SSD 970 EVO Plus 1TB      | 3        | 0.87%   |
| Samsung HD103SI 1TB               | 3        | 0.87%   |
| Patriot Burst 240GB SSD           | 3        | 0.87%   |
| Intel SSDSC2BW120A4 120GB         | 3        | 0.87%   |
| Crucial CT120BX500SSD1 120GB      | 3        | 0.87%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 2        | 0.58%   |
| WDC WD6400AAKS-22A7B0 640GB       | 2        | 0.58%   |
| WDC WD5003ABYX-88 LEN 500GB       | 2        | 0.58%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 0.58%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 2        | 0.58%   |
| WDC WD3200AAKS-00L9A0 320GB       | 2        | 0.58%   |
| WDC WD30EZRX-00AZ6B0 3TB          | 2        | 0.58%   |
| WDC WD30EFRX-68EUZN0 3TB          | 2        | 0.58%   |
| WDC WD2500AVJS-63WDA0 250GB       | 2        | 0.58%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 2        | 0.58%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.58%   |
| WDC WD1600AAJS-07M0A0 160GB       | 2        | 0.58%   |
| Toshiba MQ01ABD100 1TB            | 2        | 0.58%   |
| Toshiba HDWD240 4TB               | 2        | 0.58%   |
| Toshiba HDWD120 2TB               | 2        | 0.58%   |
| Toshiba DT01ACA300 3TB            | 2        | 0.58%   |
| Seagate ST3250410AS 250GB         | 2        | 0.58%   |
| Seagate ST3160815AS 160GB         | 2        | 0.58%   |
| Seagate ST31000528AS 1TB          | 2        | 0.58%   |
| Seagate ST31000524AS 1TB          | 2        | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB    | 2        | 0.58%   |
| Seagate ST10000DM0004-1ZC101 10TB | 2        | 0.58%   |
| Samsung SSD 860 QVO 1TB           | 2        | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 69       | 120    | 47.92%  |
| Seagate             | 30       | 45     | 20.83%  |
| Toshiba             | 22       | 36     | 15.28%  |
| Samsung Electronics | 8        | 10     | 5.56%   |
| Hitachi             | 5        | 8      | 3.47%   |
| Maxtor              | 2        | 2      | 1.39%   |
| Unknown             | 1        | 1      | 0.69%   |
| TO Exter            | 1        | 1      | 0.69%   |
| Min Yi U            | 1        | 1      | 0.69%   |
| HPE                 | 1        | 2      | 0.69%   |
| HGST HTS            | 1        | 1      | 0.69%   |
| HGST                | 1        | 1      | 0.69%   |
| External            | 1        | 1      | 0.69%   |
| ASMedia             | 1        | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 32       | 44     | 29.36%  |
| Samsung Electronics | 17       | 28     | 15.6%   |
| Crucial             | 15       | 20     | 13.76%  |
| Intel               | 9        | 11     | 8.26%   |
| A-DATA Technology   | 9        | 12     | 8.26%   |
| Patriot             | 4        | 7      | 3.67%   |
| SanDisk             | 3        | 5      | 2.75%   |
| WDC                 | 2        | 2      | 1.83%   |
| Transcend           | 2        | 2      | 1.83%   |
| OCZ                 | 2        | 3      | 1.83%   |
| Gigabyte Technology | 2        | 2      | 1.83%   |
| SPCC                | 1        | 1      | 0.92%   |
| Seagate             | 1        | 1      | 0.92%   |
| PNY                 | 1        | 1      | 0.92%   |
| Netac               | 1        | 1      | 0.92%   |
| Mushkin             | 1        | 2      | 0.92%   |
| KingSpec            | 1        | 1      | 0.92%   |
| Kingmax             | 1        | 1      | 0.92%   |
| INNOVATION IT       | 1        | 1      | 0.92%   |
| GOODRAM             | 1        | 1      | 0.92%   |
| Corsair             | 1        | 1      | 0.92%   |
| China               | 1        | 1      | 0.92%   |
| AMD                 | 1        | 2      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 112      | 230    | 45.53%  |
| SSD     | 89       | 150    | 36.18%  |
| NVMe    | 44       | 77     | 17.89%  |
| Unknown | 1        | 2      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 142      | 373    | 73.58%  |
| NVMe | 44       | 77     | 22.8%   |
| SAS  | 7        | 9      | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 114      | 213    | 53.27%  |
| 0.51-1.0   | 56       | 92     | 26.17%  |
| 1.01-2.0   | 19       | 32     | 8.88%   |
| 2.01-3.0   | 14       | 29     | 6.54%   |
| 3.01-4.0   | 8        | 10     | 3.74%   |
| 4.01-10.0  | 3        | 4      | 1.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 47       | 26.86%  |
| 251-500        | 27       | 15.43%  |
| 501-1000       | 26       | 14.86%  |
| 1001-2000      | 21       | 12%     |
| More than 3000 | 16       | 9.14%   |
| 1-20           | 13       | 7.43%   |
| 51-100         | 10       | 5.71%   |
| Unknown        | 7        | 4%      |
| 2001-3000      | 6        | 3.43%   |
| 21-50          | 2        | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 78       | 43.09%  |
| 21-50          | 20       | 11.05%  |
| 251-500        | 16       | 8.84%   |
| 501-1000       | 16       | 8.84%   |
| 51-100         | 13       | 7.18%   |
| 101-250        | 12       | 6.63%   |
| 1001-2000      | 9        | 4.97%   |
| Unknown        | 7        | 3.87%   |
| More than 3000 | 5        | 2.76%   |
| 2001-3000      | 5        | 2.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-07A7B0 640GB        | 1        | 1      | 4.55%   |
| WDC WD5003ABYX-88 LEN 500GB        | 1        | 1      | 4.55%   |
| WDC WD5000AAKX-221CA1 500GB        | 1        | 1      | 4.55%   |
| WDC WD3200AAKS-00L9A0 320GB        | 1        | 1      | 4.55%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1      | 4.55%   |
| WDC WD10EZRZ-00HTKB0 1TB           | 1        | 1      | 4.55%   |
| WDC WD10EZEX-00MFCA0 1TB           | 1        | 1      | 4.55%   |
| Transcend TS480GSSD220S 480GB      | 1        | 1      | 4.55%   |
| Toshiba DT01ACA100 1TB             | 1        | 1      | 4.55%   |
| SPCC Solid State Disk 128GB        | 1        | 1      | 4.55%   |
| Seagate ST3250410AS 250GB          | 1        | 1      | 4.55%   |
| Seagate ST31500341AS 1TB           | 1        | 1      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 3      | 4.55%   |
| Seagate ST1000DX002-2DV162 1TB     | 1        | 1      | 4.55%   |
| SanDisk SDSSDA240G 240GB           | 1        | 1      | 4.55%   |
| Kingston SHFS37A120G 120GB SSD     | 1        | 1      | 4.55%   |
| Intel SSDSC2BW180A4 180GB          | 1        | 1      | 4.55%   |
| Intel SSDSC2BW120A4 120GB          | 1        | 1      | 4.55%   |
| Hitachi HDS723020BLA642 2TB        | 1        | 1      | 4.55%   |
| Crucial CT525MX300SSD1 528GB       | 1        | 1      | 4.55%   |
| Crucial CT120BX500SSD1 120GB       | 1        | 2      | 4.55%   |
| A-DATA Technology SP900 64GB SSD   | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 7        | 7      | 33.33%  |
| Seagate           | 3        | 6      | 14.29%  |
| Intel             | 2        | 2      | 9.52%   |
| Crucial           | 2        | 3      | 9.52%   |
| Transcend         | 1        | 1      | 4.76%   |
| Toshiba           | 1        | 1      | 4.76%   |
| SPCC              | 1        | 1      | 4.76%   |
| SanDisk           | 1        | 1      | 4.76%   |
| Kingston          | 1        | 1      | 4.76%   |
| Hitachi           | 1        | 1      | 4.76%   |
| A-DATA Technology | 1        | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 7      | 58.33%  |
| Seagate | 3        | 6      | 25%     |
| Toshiba | 1        | 1      | 8.33%   |
| Hitachi | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 15     | 57.14%  |
| SSD  | 9        | 10     | 42.86%  |

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
| Detected | 97       | 265    | 54.19%  |
| Works    | 63       | 169    | 35.2%   |
| Malfunc  | 19       | 25     | 10.61%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 102      | 45.54%  |
| AMD                         | 53       | 23.66%  |
| Samsung Electronics         | 15       | 6.7%    |
| Kingston Technology Company | 8        | 3.57%   |
| Phison Electronics          | 6        | 2.68%   |
| Micron/Crucial Technology   | 5        | 2.23%   |
| JMicron Technology          | 5        | 2.23%   |
| ASMedia Technology          | 5        | 2.23%   |
| Nvidia                      | 4        | 1.79%   |
| Marvell Technology Group    | 4        | 1.79%   |
| ADATA Technology            | 4        | 1.79%   |
| Silicon Motion              | 3        | 1.34%   |
| SanDisk                     | 3        | 1.34%   |
| VIA Technologies            | 1        | 0.45%   |
| Transcend                   | 1        | 0.45%   |
| Silicon Image               | 1        | 0.45%   |
| Realtek Semiconductor       | 1        | 0.45%   |
| Micron Technology           | 1        | 0.45%   |
| Broadcom / LSI              | 1        | 0.45%   |
| Adaptec                     | 1        | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30       | 10.24%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 5.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 3.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 3.41%   |
| AMD FCH SATA Controller D                                                               | 10       | 3.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 3.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 2.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 2.73%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.73%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 2.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.37%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.37%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 4        | 1.37%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.37%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.37%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.37%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.37%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 0.68%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2        | 0.68%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 2        | 0.68%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.68%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.68%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 2        | 0.68%   |
| Intel SSD 600P Series                                                                   | 2        | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.68%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.68%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.68%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 123      | 54.19%  |
| IDE  | 50       | 22.03%  |
| NVMe | 45       | 19.82%  |
| RAID | 8        | 3.52%   |
| SAS  | 1        | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 102      | 63.35%  |
| AMD    | 59       | 36.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 3.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 1.83%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 1.83%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 1.83%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.83%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 3        | 1.83%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.83%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.83%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.83%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.83%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.22%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 1.22%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.22%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 2        | 1.22%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.22%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.22%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 2        | 1.22%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.22%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.22%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.22%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.22%   |
| Intel Core 2 CPU 6320 @ 1.86GHz             | 2        | 1.22%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.22%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 1.22%   |
| AMD Phenom II X4 965 Processor              | 2        | 1.22%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.22%   |
| AMD Athlon X4 740 Quad Core Processor       | 2        | 1.22%   |
| AMD Athlon 64 X2 Dual Core Processor 6400+  | 2        | 1.22%   |
| Intel Xeon E-2314 CPU @ 2.80GHz             | 1        | 0.61%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz         | 1        | 0.61%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.61%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.61%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.61%   |
| Intel Pentium CPU G4560T @ 2.90GHz          | 1        | 0.61%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.61%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 32       | 19.51%  |
| Intel Core i3           | 17       | 10.37%  |
| Intel Core i7           | 15       | 9.15%   |
| AMD Ryzen 5             | 13       | 7.93%   |
| Intel Core 2 Duo        | 9        | 5.49%   |
| Other                   | 8        | 4.88%   |
| AMD Ryzen 9             | 6        | 3.66%   |
| Intel Pentium           | 5        | 3.05%   |
| AMD Ryzen 7             | 5        | 3.05%   |
| AMD Ryzen 3             | 5        | 3.05%   |
| AMD FX                  | 5        | 3.05%   |
| Intel Xeon              | 4        | 2.44%   |
| AMD Athlon II X4        | 4        | 2.44%   |
| Intel Core 2            | 3        | 1.83%   |
| AMD Phenom II X4        | 3        | 1.83%   |
| AMD Athlon X4           | 3        | 1.83%   |
| AMD Athlon 64 X2        | 3        | 1.83%   |
| Intel Pentium Dual-Core | 2        | 1.22%   |
| Intel Pentium Dual      | 2        | 1.22%   |
| Intel Pentium 4         | 2        | 1.22%   |
| Intel Core i9           | 2        | 1.22%   |
| Intel Core 2 Quad       | 2        | 1.22%   |
| AMD A8                  | 2        | 1.22%   |
| Intel Celeron           | 1        | 0.61%   |
| AMD Ryzen Threadripper  | 1        | 0.61%   |
| AMD Ryzen 7 PRO         | 1        | 0.61%   |
| AMD Ryzen 5 PRO         | 1        | 0.61%   |
| AMD Ryzen 3 PRO         | 1        | 0.61%   |
| AMD Phenom II X6        | 1        | 0.61%   |
| AMD Phenom II X2        | 1        | 0.61%   |
| AMD Phenom              | 1        | 0.61%   |
| AMD E                   | 1        | 0.61%   |
| AMD Athlon 64           | 1        | 0.61%   |
| AMD Athlon              | 1        | 0.61%   |
| AMD A6                  | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 69       | 42.07%  |
| 2      | 43       | 26.22%  |
| 6      | 22       | 13.41%  |
| 8      | 10       | 6.1%    |
| 12     | 5        | 3.05%   |
| 1      | 5        | 3.05%   |
| 3      | 3        | 1.83%   |
| 24     | 2        | 1.22%   |
| 16     | 2        | 1.22%   |
| 10     | 2        | 1.22%   |
| 14     | 1        | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 160      | 99.38%  |
| 2      | 1        | 0.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 84       | 51.85%  |
| 1      | 78       | 48.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 159      | 98.76%  |
| Unknown        | 2        | 1.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 41       | 24.26%  |
| 0x306c3    | 21       | 12.43%  |
| 0x206a7    | 11       | 6.51%   |
| 0x1067a    | 7        | 4.14%   |
| 0xa0653    | 5        | 2.96%   |
| 0x906ea    | 5        | 2.96%   |
| 0x0800820d | 5        | 2.96%   |
| 0x506e3    | 4        | 2.37%   |
| 0x010000db | 4        | 2.37%   |
| 0x010000c8 | 4        | 2.37%   |
| 0xa0671    | 3        | 1.78%   |
| 0x906e9    | 3        | 1.78%   |
| 0x6fd      | 3        | 1.78%   |
| 0x306a9    | 3        | 1.78%   |
| 0x0a601203 | 3        | 1.78%   |
| 0x08701021 | 3        | 1.78%   |
| 0x06001119 | 3        | 1.78%   |
| 0xf43      | 2        | 1.18%   |
| 0xa0655    | 2        | 1.18%   |
| 0x906ed    | 2        | 1.18%   |
| 0x906eb    | 2        | 1.18%   |
| 0x6fb      | 2        | 1.18%   |
| 0x306f2    | 2        | 1.18%   |
| 0x08701013 | 2        | 1.18%   |
| 0x08600106 | 2        | 1.18%   |
| 0x0810100b | 2        | 1.18%   |
| 0x08001137 | 2        | 1.18%   |
| 0x06000852 | 2        | 1.18%   |
| 0x0600063e | 2        | 1.18%   |
| 0xb0671    | 1        | 0.59%   |
| 0x90672    | 1        | 0.59%   |
| 0x6f6      | 1        | 0.59%   |
| 0x20655    | 1        | 0.59%   |
| 0x106a4    | 1        | 0.59%   |
| 0x0a50000d | 1        | 0.59%   |
| 0x0a201009 | 1        | 0.59%   |
| 0x0a201005 | 1        | 0.59%   |
| 0x08701030 | 1        | 0.59%   |
| 0x08600103 | 1        | 0.59%   |
| 0x08108109 | 1        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 27       | 16.67%  |
| SandyBridge      | 13       | 8.02%   |
| KabyLake         | 11       | 6.79%   |
| Zen+             | 9        | 5.56%   |
| Zen 2            | 9        | 5.56%   |
| Zen              | 9        | 5.56%   |
| Penryn           | 9        | 5.56%   |
| K10              | 9        | 5.56%   |
| Core             | 9        | 5.56%   |
| Piledriver       | 8        | 4.94%   |
| CometLake        | 8        | 4.94%   |
| Skylake          | 7        | 4.32%   |
| Unknown          | 6        | 3.7%    |
| Zen 3            | 4        | 2.47%   |
| K8 Hammer        | 4        | 2.47%   |
| IvyBridge        | 4        | 2.47%   |
| Icelake          | 4        | 2.47%   |
| Alderlake Hybrid | 3        | 1.85%   |
| Westmere         | 2        | 1.23%   |
| NetBurst         | 2        | 1.23%   |
| Bulldozer        | 2        | 1.23%   |
| Nehalem          | 1        | 0.62%   |
| Excavator        | 1        | 0.62%   |
| Bobcat           | 1        | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 67       | 37.02%  |
| AMD                        | 66       | 36.46%  |
| Intel                      | 46       | 25.41%  |
| Matrox Electronics Systems | 1        | 0.55%   |
| ATI Technologies           | 1        | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 6.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 5.46%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 3.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 2.73%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 2.19%   |
| Intel HD Graphics 530                                                       | 4        | 2.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.64%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 1.64%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 1.64%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.64%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.64%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.64%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 3        | 1.64%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 3        | 1.64%   |
| AMD Raphael                                                                 | 3        | 1.64%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.64%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.09%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 1.09%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.09%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.09%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.09%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.09%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.09%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 1.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.09%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.09%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.09%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 1.09%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 1.09%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.09%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.55%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.55%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 59       | 35.76%  |
| 1 x AMD        | 58       | 35.15%  |
| 1 x Intel      | 34       | 20.61%  |
| Intel + Nvidia | 5        | 3.03%   |
| Intel + AMD    | 3        | 1.82%   |
| AMD + Nvidia   | 3        | 1.82%   |
| 2 x AMD        | 2        | 1.21%   |
| 1 x Matrox     | 1        | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 115      | 68.86%  |
| Proprietary | 47       | 28.14%  |
| Unknown     | 5        | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 36.53%  |
| 0.51-1.0   | 30       | 17.96%  |
| 1.01-2.0   | 29       | 17.37%  |
| 7.01-8.0   | 12       | 7.19%   |
| 3.01-4.0   | 12       | 7.19%   |
| 0.01-0.5   | 11       | 6.59%   |
| 5.01-6.0   | 5        | 2.99%   |
| 8.01-16.0  | 4        | 2.4%    |
| 2.01-3.0   | 3        | 1.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 42       | 23.73%  |
| Dell                 | 24       | 13.56%  |
| AOC                  | 21       | 11.86%  |
| Philips              | 16       | 9.04%   |
| Acer                 | 16       | 9.04%   |
| Goldstar             | 15       | 8.47%   |
| Ancor Communications | 9        | 5.08%   |
| Hewlett-Packard      | 5        | 2.82%   |
| BenQ                 | 4        | 2.26%   |
| LG Electronics       | 3        | 1.69%   |
| ASUSTek Computer     | 3        | 1.69%   |
| Unknown              | 2        | 1.13%   |
| Huion                | 2        | 1.13%   |
| Grundig              | 2        | 1.13%   |
| Fujitsu Siemens      | 2        | 1.13%   |
| Vestel Elektronik    | 1        | 0.56%   |
| Sony                 | 1        | 0.56%   |
| RTK                  | 1        | 0.56%   |
| Panasonic            | 1        | 0.56%   |
| NOA VISION           | 1        | 0.56%   |
| NEC Computers        | 1        | 0.56%   |
| LG Display           | 1        | 0.56%   |
| Lenovo               | 1        | 0.56%   |
| KTC                  | 1        | 0.56%   |
| Jean                 | 1        | 0.56%   |
| InnoLux Display      | 1        | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0509 1920x1080                    | 2        | 1.05%   |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                   | 2        | 1.05%   |
| Huion Kamvas 22plus HAT2150 1920x1080 476x267mm 21.5-inch            | 2        | 1.05%   |
| Grundig WXGA GRU4448 1600x1200                                       | 2        | 1.05%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 2        | 1.05%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                    | 2        | 1.05%   |
| Dell LCD Monitor SE2416H 5760x1080                                   | 2        | 1.05%   |
| Dell LCD Monitor SE2416H                                             | 2        | 1.05%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                    | 2        | 1.05%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                    | 2        | 1.05%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 1.05%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 2        | 1.05%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 2        | 1.05%   |
| AOC 22B1WG5 AOC2201 1920x1080 479x260mm 21.5-inch                    | 2        | 1.05%   |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                    | 2        | 1.05%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch   | 1        | 0.53%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.53%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                          | 1        | 0.53%   |
| Sony TV SNY1A02 1920x1080                                            | 1        | 0.53%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1        | 0.53%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch    | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0608 1920x1080 510x290mm 23.1-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM05C6 1920x1080 520x290mm 23.4-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch  | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch  | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM01E7 1920x1200 518x324mm 24.1-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM01B8 1280x1024 338x270mm 17.0-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0168 1280x1024 338x270mm 17.0-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 77       | 44.51%  |
| 2560x1440 (QHD)    | 16       | 9.25%   |
| 1280x1024 (SXGA)   | 14       | 8.09%   |
| 3840x2160 (4K)     | 12       | 6.94%   |
| 1680x1050 (WSXGA+) | 11       | 6.36%   |
| Unknown            | 8        | 4.62%   |
| 1920x1200 (WUXGA)  | 6        | 3.47%   |
| 3840x1080          | 5        | 2.89%   |
| 1600x900 (HD+)     | 5        | 2.89%   |
| 1440x900 (WXGA+)   | 4        | 2.31%   |
| 1360x768           | 4        | 2.31%   |
| 2560x1080          | 3        | 1.73%   |
| 5760x1080          | 2        | 1.16%   |
| 2048x1152          | 2        | 1.16%   |
| 1366x768 (WXGA)    | 2        | 1.16%   |
| 4480x1440          | 1        | 0.58%   |
| 2560x1600          | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 31       | 17.61%  |
| 27      | 25       | 14.2%   |
| 21      | 21       | 11.93%  |
| 24      | 20       | 11.36%  |
| Unknown | 19       | 10.8%   |
| 19      | 10       | 5.68%   |
| 22      | 9        | 5.11%   |
| 17      | 8        | 4.55%   |
| 20      | 6        | 3.41%   |
| 31      | 4        | 2.27%   |
| 84      | 3        | 1.7%    |
| 54      | 3        | 1.7%    |
| 18      | 3        | 1.7%    |
| 34      | 2        | 1.14%   |
| 33      | 2        | 1.14%   |
| 25      | 2        | 1.14%   |
| 72      | 1        | 0.57%   |
| 60      | 1        | 0.57%   |
| 58      | 1        | 0.57%   |
| 49      | 1        | 0.57%   |
| 46      | 1        | 0.57%   |
| 39      | 1        | 0.57%   |
| 32      | 1        | 0.57%   |
| 26      | 1        | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 69       | 40.83%  |
| 401-500     | 41       | 24.26%  |
| Unknown     | 19       | 11.24%  |
| 601-700     | 9        | 5.33%   |
| 351-400     | 7        | 4.14%   |
| 301-350     | 7        | 4.14%   |
| 1001-1500   | 7        | 4.14%   |
| 701-800     | 5        | 2.96%   |
| 1501-2000   | 4        | 2.37%   |
| 901-1000    | 1        | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 103      | 63.98%  |
| 16/10   | 23       | 14.29%  |
| Unknown | 17       | 10.56%  |
| 5/4     | 13       | 8.07%   |
| 21/9    | 3        | 1.86%   |
| 32/9    | 1        | 0.62%   |
| 3/2     | 1        | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 60       | 34.88%  |
| 301-350        | 26       | 15.12%  |
| 151-200        | 25       | 14.53%  |
| Unknown        | 19       | 11.05%  |
| 251-300        | 10       | 5.81%   |
| 141-150        | 10       | 5.81%   |
| More than 1000 | 9        | 5.23%   |
| 351-500        | 9        | 5.23%   |
| 501-1000       | 3        | 1.74%   |
| 121-130        | 1        | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 98       | 60.12%  |
| 101-120 | 33       | 20.25%  |
| Unknown | 19       | 11.66%  |
| 1-50    | 7        | 4.29%   |
| 121-160 | 5        | 3.07%   |
| 161-240 | 1        | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 124      | 75.15%  |
| 2     | 30       | 18.18%  |
| 0     | 7        | 4.24%   |
| 3     | 3        | 1.82%   |
| 4     | 1        | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 104      | 44.26%  |
| Intel                             | 53       | 22.55%  |
| Qualcomm Atheros                  | 10       | 4.26%   |
| TP-Link                           | 8        | 3.4%    |
| Broadcom                          | 7        | 2.98%   |
| Ralink Technology                 | 6        | 2.55%   |
| Ralink                            | 5        | 2.13%   |
| Qualcomm Atheros Communications   | 5        | 2.13%   |
| MediaTek                          | 5        | 2.13%   |
| Nvidia                            | 4        | 1.7%    |
| Marvell Technology Group          | 3        | 1.28%   |
| D-Link                            | 3        | 1.28%   |
| Xiaomi                            | 2        | 0.85%   |
| Sundance Technology Inc / IC Plus | 2        | 0.85%   |
| Samsung Electronics               | 2        | 0.85%   |
| NetGear                           | 2        | 0.85%   |
| ASIX Electronics                  | 2        | 0.85%   |
| VIA Technologies                  | 1        | 0.43%   |
| T & A Mobile Phones               | 1        | 0.43%   |
| Nokia Mobile Phones               | 1        | 0.43%   |
| Microsoft                         | 1        | 0.43%   |
| Linksys                           | 1        | 0.43%   |
| ICS Advent                        | 1        | 0.43%   |
| Huawei Technologies               | 1        | 0.43%   |
| Edimax Technology                 | 1        | 0.43%   |
| D-Link System                     | 1        | 0.43%   |
| Broadcom Limited                  | 1        | 0.43%   |
| ASUSTek Computer                  | 1        | 0.43%   |
| Aquantia                          | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84       | 33.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 3.63%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 2.02%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 2.02%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 2.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 1.61%   |
| Intel I211 Gigabit Network Connection                             | 4        | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.61%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.61%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.21%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.21%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.21%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 3        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.81%   |
| TP-Link 802.11ac NIC                                              | 2        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.81%   |
| Ralink RT2070 Wireless Adapter                                    | 2        | 0.81%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 2        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.81%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2        | 0.81%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.81%   |
| NetGear A6210                                                     | 2        | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2        | 0.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.81%   |
| Intel Wireless 3165                                               | 2        | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.81%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.81%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.81%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 2        | 0.81%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 2        | 0.81%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2        | 0.81%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.4%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 1        | 0.4%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.4%    |
| T & A Mobile Phones 9008A                                         | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 18.46%  |
| TP-Link                         | 8        | 12.31%  |
| Realtek Semiconductor           | 7        | 10.77%  |
| Ralink Technology               | 6        | 9.23%   |
| Ralink                          | 5        | 7.69%   |
| Qualcomm Atheros Communications | 5        | 7.69%   |
| Broadcom                        | 5        | 7.69%   |
| Qualcomm Atheros                | 4        | 6.15%   |
| MediaTek                        | 4        | 6.15%   |
| D-Link                          | 3        | 4.62%   |
| NetGear                         | 2        | 3.08%   |
| Microsoft                       | 1        | 1.54%   |
| Linksys                         | 1        | 1.54%   |
| Edimax Technology               | 1        | 1.54%   |
| ASUSTek Computer                | 1        | 1.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                         | 5        | 7.58%   |
| Intel Wi-Fi 6 AX200                                                     | 5        | 7.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4        | 6.06%   |
| Ralink MT7601U Wireless Adapter                                         | 3        | 4.55%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 3        | 4.55%   |
| TP-Link 802.11ac NIC                                                    | 2        | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 3.03%   |
| Ralink RT2070 Wireless Adapter                                          | 2        | 3.03%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 2        | 3.03%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2        | 3.03%   |
| NetGear A6210                                                           | 2        | 3.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2        | 3.03%   |
| Intel Wireless 3165                                                     | 2        | 3.03%   |
| Intel 700 Series Chipset Family Wi-Fi                                   | 2        | 3.03%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 2        | 3.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2        | 3.03%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 1.52%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1        | 1.52%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 1.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.52%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                  | 1        | 1.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1        | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1        | 1.52%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.52%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1        | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.52%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 1.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 1.52%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1        | 1.52%   |
| Linksys WUSB6400M                                                       | 1        | 1.52%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 1.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 1.52%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                | 1        | 1.52%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]    | 1        | 1.52%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.52%   |
| D-Link 11ac adapter                                                     | 1        | 1.52%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter            | 1        | 1.52%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]         | 1        | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 100      | 56.82%  |
| Intel                             | 46       | 26.14%  |
| Qualcomm Atheros                  | 6        | 3.41%   |
| Nvidia                            | 4        | 2.27%   |
| Marvell Technology Group          | 3        | 1.7%    |
| Xiaomi                            | 2        | 1.14%   |
| Sundance Technology Inc / IC Plus | 2        | 1.14%   |
| Broadcom                          | 2        | 1.14%   |
| ASIX Electronics                  | 2        | 1.14%   |
| VIA Technologies                  | 1        | 0.57%   |
| T & A Mobile Phones               | 1        | 0.57%   |
| Samsung Electronics               | 1        | 0.57%   |
| MediaTek                          | 1        | 0.57%   |
| ICS Advent                        | 1        | 0.57%   |
| Huawei Technologies               | 1        | 0.57%   |
| D-Link System                     | 1        | 0.57%   |
| Broadcom Limited                  | 1        | 0.57%   |
| Aquantia                          | 1        | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 84       | 46.67%  |
| Realtek RTL8125 2.5GbE Controller                                          | 9        | 5%      |
| Intel Ethernet Connection (2) I218-V                                       | 5        | 2.78%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.22%   |
| Intel Ethernet Controller I225-V                                           | 4        | 2.22%   |
| Intel Ethernet Connection I217-V                                           | 4        | 2.22%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 2.22%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 1.67%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.11%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 1.11%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.11%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 1.11%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 1.11%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 1.11%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.56%   |
| T & A Mobile Phones 9008A                                                  | 1        | 0.56%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.56%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 1        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.56%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.56%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.56%   |
| MediaTek X55                                                               | 1        | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.56%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.56%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.56%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 158      | 71.82%  |
| WiFi     | 60       | 27.27%  |
| Modem    | 2        | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 120      | 74.53%  |
| WiFi     | 41       | 25.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 70.99%  |
| 2     | 42       | 25.93%  |
| 0     | 3        | 1.85%   |
| 4     | 1        | 0.62%   |
| 3     | 1        | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 153      | 94.44%  |
| Yes  | 9        | 5.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 32.43%  |
| Cambridge Silicon Radio         | 7        | 18.92%  |
| Broadcom                        | 4        | 10.81%  |
| Realtek Semiconductor           | 2        | 5.41%   |
| MediaTek                        | 2        | 5.41%   |
| Integrated System Solution      | 2        | 5.41%   |
| Foxconn / Hon Hai               | 2        | 5.41%   |
| ASUSTek Computer                | 2        | 5.41%   |
| TP-Link                         | 1        | 2.7%    |
| Qualcomm Atheros Communications | 1        | 2.7%    |
| IMC Networks                    | 1        | 2.7%    |
| Apple                           | 1        | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 18.92%  |
| Intel AX200 Bluetooth                                 | 5        | 13.51%  |
| Intel Bluetooth wireless interface                    | 3        | 8.11%   |
| Realtek Bluetooth Radio                               | 2        | 5.41%   |
| MediaTek Wireless_Device                              | 2        | 5.41%   |
| Intel Bluetooth Device                                | 2        | 5.41%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 5.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 5.41%   |
| TP-Link TP-Cdj+ UB5A Adapter                          | 1        | 2.7%    |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.7%    |
| Intel AX201 Bluetooth                                 | 1        | 2.7%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.7%    |
| Integrated System Solution Bluetooth Device           | 1        | 2.7%    |
| IMC Networks BCM20702A0                               | 1        | 2.7%    |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 2.7%    |
| Foxconn / Hon Hai BT                                  | 1        | 2.7%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 2.7%    |
| Broadcom BCM2045 Bluetooth                            | 1        | 2.7%    |
| Apple Bluetooth Host Controller                       | 1        | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 100      | 34.84%  |
| AMD                      | 87       | 30.31%  |
| Nvidia                   | 64       | 22.3%   |
| C-Media Electronics      | 10       | 3.48%   |
| Logitech                 | 4        | 1.39%   |
| Creative Labs            | 3        | 1.05%   |
| Microsoft                | 2        | 0.7%    |
| Yamaha                   | 1        | 0.35%   |
| XMOS                     | 1        | 0.35%   |
| VIA Technologies         | 1        | 0.35%   |
| Trust                    | 1        | 0.35%   |
| Tenx Technology          | 1        | 0.35%   |
| Razer USA                | 1        | 0.35%   |
| Nordic Semiconductor ASA | 1        | 0.35%   |
| Native Instruments       | 1        | 0.35%   |
| MCS                      | 1        | 0.35%   |
| Kingston Technology      | 1        | 0.35%   |
| JMTek                    | 1        | 0.35%   |
| Focusrite-Novation       | 1        | 0.35%   |
| Ensoniq                  | 1        | 0.35%   |
| Cirrus Logic             | 1        | 0.35%   |
| ATI Technologies         | 1        | 0.35%   |
| ASUSTek Computer         | 1        | 0.35%   |
| Astro Gaming             | 1        | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 17       | 5.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13       | 3.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 13       | 3.93%   |
| AMD Family 17h/19h HD Audio Controller                                            | 13       | 3.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 12       | 3.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 3.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 3.02%   |
| Nvidia GP106 High Definition Audio Controller                                     | 9        | 2.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 2.72%   |
| AMD Starship/Matisse HD Audio Controller                                          | 9        | 2.72%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 8        | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8        | 2.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 2.42%   |
| Nvidia TU116 High Definition Audio Controller                                     | 7        | 2.11%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 7        | 2.11%   |
| Nvidia GM206 High Definition Audio Controller                                     | 6        | 1.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 6        | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 1.51%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 1.51%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 5        | 1.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 5        | 1.51%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 1.21%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 1.21%   |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4        | 1.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 1.21%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 1.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 0.91%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 3        | 0.91%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 0.91%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.6%    |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.6%    |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 27       | 28.13%  |
| Corsair             | 14       | 14.58%  |
| Unknown             | 10       | 10.42%  |
| G.Skill             | 10       | 10.42%  |
| SK hynix            | 7        | 7.29%   |
| Samsung Electronics | 7        | 7.29%   |
| Crucial             | 6        | 6.25%   |
| Transcend           | 3        | 3.13%   |
| Patriot             | 2        | 2.08%   |
| Kingmax             | 2        | 2.08%   |
| Elpida              | 2        | 2.08%   |
| Silicon Power       | 1        | 1.04%   |
| Ramaxel Technology  | 1        | 1.04%   |
| Mushkin             | 1        | 1.04%   |
| Micron Technology   | 1        | 1.04%   |
| Apacer              | 1        | 1.04%   |
| A-DATA Technology   | 1        | 1.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 3        | 2.94%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 2.94%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                  | 2        | 1.96%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s     | 2        | 1.96%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 1.96%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s    | 2        | 1.96%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 2        | 1.96%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s              | 1        | 0.98%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.98%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 1        | 0.98%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 0.98%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 1        | 0.98%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s               | 1        | 0.98%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                    | 1        | 0.98%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 0.98%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                 | 1        | 0.98%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 1        | 0.98%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s              | 1        | 0.98%   |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s   | 1        | 0.98%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s    | 1        | 0.98%   |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s       | 1        | 0.98%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s       | 1        | 0.98%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s              | 1        | 0.98%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.98%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 1        | 0.98%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 0.98%   |
| SK hynix RAM HMT125U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.98%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 0.98%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s    | 1        | 0.98%   |
| Silicon Power RAM Module 8GB DIMM DDR3 1600MT/s         | 1        | 0.98%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.98%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.98%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s     | 1        | 0.98%   |
| Ramaxel RAM RMUA5090KE68H9F2133 4GB DIMM DDR4 2133MT/s  | 1        | 0.98%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s          | 1        | 0.98%   |
| Patriot RAM PSD22G80026 2GB DIMM DDR2 800MT/s           | 1        | 0.98%   |
| Mushkin RAM 99[2/7/4]199[F/T] 8192MB DIMM DDR4 2400MT/s | 1        | 0.98%   |
| Micron RAM 8KTF51264AZ-1G6P1 4GB DIMM DDR3 1600MT/s     | 1        | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 40       | 48.78%  |
| DDR3    | 27       | 32.93%  |
| SDRAM   | 4        | 4.88%   |
| Unknown | 4        | 4.88%   |
| DDR5    | 3        | 3.66%   |
| DDR2    | 3        | 3.66%   |
| DDR     | 1        | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 78       | 96.3%   |
| SODIMM | 3        | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 33       | 37.08%  |
| 4096  | 22       | 24.72%  |
| 16384 | 15       | 16.85%  |
| 2048  | 13       | 14.61%  |
| 1024  | 3        | 3.37%   |
| 32768 | 2        | 2.25%   |
| 512   | 1        | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 15       | 17.44%  |
| 3200  | 10       | 11.63%  |
| 2667  | 8        | 9.3%    |
| 1333  | 8        | 9.3%    |
| 2400  | 7        | 8.14%   |
| 3400  | 6        | 6.98%   |
| 3600  | 3        | 3.49%   |
| 2133  | 3        | 3.49%   |
| 1800  | 3        | 3.49%   |
| 800   | 3        | 3.49%   |
| 4800  | 2        | 2.33%   |
| 3866  | 2        | 2.33%   |
| 667   | 2        | 2.33%   |
| 5200  | 1        | 1.16%   |
| 4000  | 1        | 1.16%   |
| 3733  | 1        | 1.16%   |
| 3533  | 1        | 1.16%   |
| 3466  | 1        | 1.16%   |
| 3334  | 1        | 1.16%   |
| 3333  | 1        | 1.16%   |
| 2933  | 1        | 1.16%   |
| 2800  | 1        | 1.16%   |
| 1867  | 1        | 1.16%   |
| 1067  | 1        | 1.16%   |
| 1066  | 1        | 1.16%   |
| 533   | 1        | 1.16%   |
| 400   | 1        | 1.16%   |

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
| Logitech                      | 12       | 41.38%  |
| Sunplus Innovation Technology | 4        | 13.79%  |
| Realtek Semiconductor         | 3        | 10.34%  |
| Microdia                      | 3        | 10.34%  |
| Chicony Electronics           | 2        | 6.9%    |
| Trust                         | 1        | 3.45%   |
| GenesysLogic Technology       | 1        | 3.45%   |
| Genesys Logic                 | 1        | 3.45%   |
| Anker                         | 1        | 3.45%   |
| Alcor Micro                   | 1        | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 13.79%  |
| Sunplus HD 720P webcam                | 3        | 10.34%  |
| Realtek FULL HD 1080P Webcam          | 2        | 6.9%    |
| Microdia Camera                       | 2        | 6.9%    |
| Logitech Webcam C170                  | 2        | 6.9%    |
| Trust Full HD Webcam                  | 1        | 3.45%   |
| Sunplus WEBCAM ESSENTIELB W1          | 1        | 3.45%   |
| Realtek Asus laptop camera            | 1        | 3.45%   |
| Microdia Sonix USB 2.0 Camera         | 1        | 3.45%   |
| Logitech Webcam C250                  | 1        | 3.45%   |
| Logitech Webcam C210                  | 1        | 3.45%   |
| Logitech Webcam C110                  | 1        | 3.45%   |
| Logitech Logitech Webcam C925e        | 1        | 3.45%   |
| Logitech HD Pro Webcam C920           | 1        | 3.45%   |
| Logitech C922 Pro Stream Webcam       | 1        | 3.45%   |
| GenesysLogic USB2.0 UVC PC Camera     | 1        | 3.45%   |
| Genesys Logic USB2.0 UVC PC Camera    | 1        | 3.45%   |
| Chicony HP High Definition Webcam     | 1        | 3.45%   |
| Chicony HP High Definition 1MP Webcam | 1        | 3.45%   |
| Anker PowerConf C300                  | 1        | 3.45%   |
| Alcor Micro USB 2.0 Camera            | 1        | 3.45%   |

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
| 0     | 144      | 87.8%   |
| 1     | 16       | 9.76%   |
| 2     | 4        | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 9        | 39.13%  |
| Net/wireless             | 4        | 17.39%  |
| Bluetooth                | 3        | 13.04%  |
| Unassigned class         | 2        | 8.7%    |
| Chipcard                 | 2        | 8.7%    |
| Storage/raid             | 1        | 4.35%   |
| Fingerprint reader       | 1        | 4.35%   |
| Communication controller | 1        | 4.35%   |


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

Total: 192

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | A320M-S2H-CF             | [5ddb15f201](https://linux-hardware.org/?probe=5ddb15f201) | Aug 07, 2022 |
| HP            | 1825                     | [4a21a02ae4](https://linux-hardware.org/?probe=4a21a02ae4) | Jul 29, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF        | [3c665fb25f](https://linux-hardware.org/?probe=3c665fb25f) | Jul 28, 2022 |
| Gigabyte      | Z97-D3H-CF               | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| ASRock        | K10N78D                  | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| WinFast       | NF-MCP55 FAB1.0          | [bb066cc2da](https://linux-hardware.org/?probe=bb066cc2da) | Jul 03, 2022 |
| MSI           | Z87-G41 PC Mate          | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| ASUSTek       | B250 MINING EXPERT       | [0d4266a0f3](https://linux-hardware.org/?probe=0d4266a0f3) | Jun 15, 2022 |
| ASUSTek       | B250 MINING EXPERT       | [8a57d29a3c](https://linux-hardware.org/?probe=8a57d29a3c) | Jun 03, 2022 |
| ASUSTek       | B250 MINING EXPERT       | [ac2e497963](https://linux-hardware.org/?probe=ac2e497963) | May 28, 2022 |
| ASUSTek       | B250 MINING EXPERT       | [987ef7b2e7](https://linux-hardware.org/?probe=987ef7b2e7) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A            | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Gigabyte      | X48T-DQ6                 | [2953148fae](https://linux-hardware.org/?probe=2953148fae) | May 16, 2022 |
| Dell          | 0J37VM A01               | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A            | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4             | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
| ASRock        | H470M-HDV                | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | B450 TOMAHAWK            | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| Gigabyte      | P31-ES3G                 | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| Intel         | H61M-S2PV                | [caa602b556](https://linux-hardware.org/?probe=caa602b556) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                 | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1 | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| ASRock        | H61M-DGS                 | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| ASRock        | H97 Pro4                 | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Pegatron      | 2AC3                     | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| ASUSTek       | P8H61 PRO                | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| Dell          | 00V62H A01               | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASRock        | A320M-HDV R4.0           | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0           | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| Gigabyte      | X48T-DQ6                 | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A            | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS     | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| ASRock        | B360 Gaming K4           | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| ASUSTek       | Z170-P                   | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| ASRock        | H97 Pro4                 | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                 | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| Foxconn       | 2A8Ch                    | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Gigabyte      | H410M H V3               | [d0ee45a4b1](https://linux-hardware.org/?probe=d0ee45a4b1) | Feb 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS    | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                 | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Gigabyte      | B85M-DS3H                | [98d6451ac1](https://linux-hardware.org/?probe=98d6451ac1) | Feb 07, 2022 |
| ASRock        | Z97M Pro4                | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| Foxconn       | 2A8Ch                    | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| ASRock        | Z590 Pro4                | [a89877d9de](https://linux-hardware.org/?probe=a89877d9de) | Jan 16, 2022 |
| ASRock        | Z590 Pro4                | [7a2453280a](https://linux-hardware.org/?probe=7a2453280a) | Jan 14, 2022 |
| ECS           | H61H2-M2                 | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| ASUSTek       | X750LB                   | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| ASUSTek       | X750LB                   | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| MSI           | H81M-P33                 | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Gigabyte      | 965P-DS3                 | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| ECS           | H61H2-M2                 | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| ASRock        | 870 Extreme3             | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| Intel         | DH61CR AAG14064-204      | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204      | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| ASRock        | B450M-HDV R4.0           | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASRock        | M3A770DE                 | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                 | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | PRIME A320M-K            | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| Dell          | 0GDG8Y A00               | [d0cf0cc443](https://linux-hardware.org/?probe=d0cf0cc443) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                    | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| Foxconn       | 2A8Ch                    | [1f650ebd72](https://linux-hardware.org/?probe=1f650ebd72) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LX               | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Gigabyte      | GB-BRR7H-4800            | [c77e499435](https://linux-hardware.org/?probe=c77e499435) | Nov 13, 2021 |
| ASUSTek       | M4A78T-E                 | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| ASUSTek       | P8Z77-V LX               | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX               | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| MSI           | P55-CD53                 | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| MSI           | P55-CD53                 | [12bf811a5c](https://linux-hardware.org/?probe=12bf811a5c) | Oct 24, 2021 |
| MSI           | P55-CD53                 | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | M5A78L LE                | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Pegatron      | 2A73h                    | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| ASUSTek       | PRIME H410M-R            | [d891006b52](https://linux-hardware.org/?probe=d891006b52) | Oct 14, 2021 |
| ASUSTek       | B85M-E                   | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| ASUSTek       | A58M-K                   | [2ca6ce79db](https://linux-hardware.org/?probe=2ca6ce79db) | Oct 03, 2021 |
| Gigabyte      | A320M-S2H-CF             | [e5508ac7ab](https://linux-hardware.org/?probe=e5508ac7ab) | Sep 27, 2021 |
| ASUSTek       | M4A78T-E                 | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| MSI           | A320M PRO-VH PLUS        | [149504315f](https://linux-hardware.org/?probe=149504315f) | Aug 10, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| ASRock        | B450M-HDV R4.0           | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| ASRock        | Z370 Pro4                | [9a9f7c5e69](https://linux-hardware.org/?probe=9a9f7c5e69) | Jul 20, 2021 |
| Gigabyte      | GA-990XA-UD3             | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO  | [83b3cc659a](https://linux-hardware.org/?probe=83b3cc659a) | Jun 07, 2021 |
| Dell          | 06CV2N A01               | [35a0afd617](https://linux-hardware.org/?probe=35a0afd617) | May 25, 2021 |
| MSI           | B450 TOMAHAWK            | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Gigabyte      | Z390 M GAMING-CF         | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| ASUSTek       | P5KPL-AM SE              | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASRock        | P45DE                    | [2f6b602e36](https://linux-hardware.org/?probe=2f6b602e36) | Apr 18, 2021 |
| ASRock        | Z370 Pro4                | [7ad77d82ba](https://linux-hardware.org/?probe=7ad77d82ba) | Apr 03, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS     | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
| MSI           | B450M PRO-M2 MAX         | [6e5e0c9ef4](https://linux-hardware.org/?probe=6e5e0c9ef4) | Mar 19, 2021 |
| MSI           | Z390-A PRO               | [12566ee726](https://linux-hardware.org/?probe=12566ee726) | Mar 10, 2021 |
| Gigabyte      | G1.Sniper Z87            | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| ASRock        | FM2A75M-DGS              | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME A320M-K            | [24a672b8ac](https://linux-hardware.org/?probe=24a672b8ac) | Feb 25, 2021 |
| ASRock        | Z87 Extreme4             | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| Dell          | 0NNGP2 A00               | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Dell          | 0J37VM A01               | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01               | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| ASRock        | X570 Phantom Gaming 4    | [eee7c1f592](https://linux-hardware.org/?probe=eee7c1f592) | Feb 03, 2021 |
| ASRock        | ConRoe1333-D667          | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X            | [28cb4726bb](https://linux-hardware.org/?probe=28cb4726bb) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X            | [0b4b751863](https://linux-hardware.org/?probe=0b4b751863) | Jan 31, 2021 |
| ASRock        | X570M Pro4               | [9cd91004ab](https://linux-hardware.org/?probe=9cd91004ab) | Jan 24, 2021 |
| Gigabyte      | F2A78M-DS2               | [9afb5c207a](https://linux-hardware.org/?probe=9afb5c207a) | Jan 23, 2021 |
| Dell          | 0DFRFW A01               | [482bc5334f](https://linux-hardware.org/?probe=482bc5334f) | Jan 22, 2021 |
| MSI           | B450 TOMAHAWK            | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2               | [df34a7d718](https://linux-hardware.org/?probe=df34a7d718) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2               | [0d8e905a30](https://linux-hardware.org/?probe=0d8e905a30) | Jan 16, 2021 |
| ASUSTek       | Maximus VII HERO         | [9b72f3a82b](https://linux-hardware.org/?probe=9b72f3a82b) | Jan 11, 2021 |
| ASUSTek       | M4A78T-E                 | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                 | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0            | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0            | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H         | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| HP            | 18EA                     | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3             | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| ASUSTek       | H81M-K                   | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| ASRock        | Z370 Pro4                | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| ASUSTek       | M5A78L LE                | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L LE                | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| ASRock        | N68-S3 UCC               | [b75cfae4a3](https://linux-hardware.org/?probe=b75cfae4a3) | Nov 01, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING  | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING  | [ff7ecd0641](https://linux-hardware.org/?probe=ff7ecd0641) | Oct 15, 2020 |
| Pegatron      | 2A94h                    | [668c4bbb8b](https://linux-hardware.org/?probe=668c4bbb8b) | Oct 06, 2020 |
| ASUSTek       | PRIME H310M-A R2.0       | [b098cfc85e](https://linux-hardware.org/?probe=b098cfc85e) | Sep 30, 2020 |
| ASUSTek       | PRIME H310M-A R2.0       | [df11954c4f](https://linux-hardware.org/?probe=df11954c4f) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-A R2.0       | [8220732bda](https://linux-hardware.org/?probe=8220732bda) | Sep 28, 2020 |
| ASUSTek       | M5A78L LE                | [7f4940b41c](https://linux-hardware.org/?probe=7f4940b41c) | Sep 28, 2020 |
| ASRock        | N68-S3 UCC               | [42ed26b195](https://linux-hardware.org/?probe=42ed26b195) | Sep 19, 2020 |
| ASUSTek       | M4A77                    | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| ASRock        | Z87E-ITX                 | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASRock        | N68-S3 UCC               | [a2d99d11fc](https://linux-hardware.org/?probe=a2d99d11fc) | Aug 30, 2020 |
| ASUSTek       | P8H77-V LE               | [1c2eaa2346](https://linux-hardware.org/?probe=1c2eaa2346) | Aug 23, 2020 |
| HP            | 2129                     | [d1eda00971](https://linux-hardware.org/?probe=d1eda00971) | Aug 20, 2020 |
| MSI           | Z87-G41 PC Mate          | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| Gigabyte      | G41M-Combo               | [2f3657530f](https://linux-hardware.org/?probe=2f3657530f) | Jun 29, 2020 |
| ASUSTek       | B85M-E                   | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| ASRock        | H97M Pro4                | [31f3732dc9](https://linux-hardware.org/?probe=31f3732dc9) | Jun 19, 2020 |
| Gigabyte      | G31MX-S2                 | [7da6752573](https://linux-hardware.org/?probe=7da6752573) | May 31, 2020 |
| Gigabyte      | G31MX-S2                 | [5472c53dca](https://linux-hardware.org/?probe=5472c53dca) | May 31, 2020 |
| ASRock        | H81M-DGS R2.0            | [26a9c7f62c](https://linux-hardware.org/?probe=26a9c7f62c) | May 30, 2020 |
| Gigabyte      | 990FXA-UD3               | [e3042f4583](https://linux-hardware.org/?probe=e3042f4583) | May 24, 2020 |
| ASUSTek       | P8H77-V LE               | [e6f20d976d](https://linux-hardware.org/?probe=e6f20d976d) | May 17, 2020 |
| Gigabyte      | 965P-DS3                 | [abfb95a938](https://linux-hardware.org/?probe=abfb95a938) | May 11, 2020 |
| Gigabyte      | 965P-DS3                 | [e59e1593d5](https://linux-hardware.org/?probe=e59e1593d5) | May 11, 2020 |
| MSI           | MS-7360                  | [ab94189bcf](https://linux-hardware.org/?probe=ab94189bcf) | May 07, 2020 |
| MSI           | Z87-G41 PC Mate          | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | 3031h                    | [b4638888cb](https://linux-hardware.org/?probe=b4638888cb) | Apr 14, 2020 |
| ASUSTek       | M5A78L LE                | [1562c544a6](https://linux-hardware.org/?probe=1562c544a6) | Apr 14, 2020 |
| ASRock        | H61M-DGS                 | [0a090881ae](https://linux-hardware.org/?probe=0a090881ae) | Apr 12, 2020 |
| ASUSTek       | A8V-MQ                   | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| ASRock        | H61M-VS                  | [799e1670fd](https://linux-hardware.org/?probe=799e1670fd) | Mar 18, 2020 |
| HP            | 212B                     | [6058dd53b1](https://linux-hardware.org/?probe=6058dd53b1) | Mar 16, 2020 |
| Gigabyte      | Z390 M GAMING-CF         | [26545c7add](https://linux-hardware.org/?probe=26545c7add) | Feb 24, 2020 |
| Gigabyte      | Z390 M GAMING-CF         | [1693523c61](https://linux-hardware.org/?probe=1693523c61) | Feb 21, 2020 |
| Intel         | DH67BL AAG10189-213      | [b0e9895bef](https://linux-hardware.org/?probe=b0e9895bef) | Feb 16, 2020 |
| ASRock        | B150M-HDV                | [c08c6d0574](https://linux-hardware.org/?probe=c08c6d0574) | Feb 08, 2020 |
| HP            | 18E7                     | [de846e5f4f](https://linux-hardware.org/?probe=de846e5f4f) | Jan 22, 2020 |
| Intel         | DH67BL AAG10189-213      | [9ed2076b0d](https://linux-hardware.org/?probe=9ed2076b0d) | Jan 18, 2020 |
| Intel         | DH67BL AAG10189-213      | [dc121e5512](https://linux-hardware.org/?probe=dc121e5512) | Jan 18, 2020 |
| Acer          | Veriton S680G            | [277889b2ff](https://linux-hardware.org/?probe=277889b2ff) | Jan 15, 2020 |
| Gigabyte      | Z390 M GAMING-CF         | [e097415087](https://linux-hardware.org/?probe=e097415087) | Dec 26, 2019 |
| ASRock        | N68-S3 UCC               | [9cbd6c2e0e](https://linux-hardware.org/?probe=9cbd6c2e0e) | Dec 25, 2019 |
| ASRock        | 990FX Extreme3           | [107280e5a9](https://linux-hardware.org/?probe=107280e5a9) | Dec 23, 2019 |
| ASRock        | 990FX Extreme3           | [66a084d547](https://linux-hardware.org/?probe=66a084d547) | Dec 11, 2019 |
| ASRock        | H97 Killer               | [8538b88e3d](https://linux-hardware.org/?probe=8538b88e3d) | Nov 27, 2019 |
| ASRock        | 970 Pro3 R2.0            | [73c6829ffb](https://linux-hardware.org/?probe=73c6829ffb) | Nov 27, 2019 |
| HP            | 18EA                     | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| ASRock        | A320M-HDV R3.0           | [d3d79c2a8d](https://linux-hardware.org/?probe=d3d79c2a8d) | Sep 16, 2019 |
| Gigabyte      | A320M-H-CF               | [a35aea421b](https://linux-hardware.org/?probe=a35aea421b) | Sep 09, 2019 |
| Intel         | DX58SO AAE29331-501      | [349ef8982a](https://linux-hardware.org/?probe=349ef8982a) | Sep 09, 2019 |
| Gigabyte      | A320M-H-CF               | [59782a89ea](https://linux-hardware.org/?probe=59782a89ea) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF               | [b4ef0f5499](https://linux-hardware.org/?probe=b4ef0f5499) | Sep 05, 2019 |
| ASRock        | FM2A55M-DGS R2.0         | [be3a07802c](https://linux-hardware.org/?probe=be3a07802c) | Aug 13, 2019 |
| ASRock        | FM2A55M-DGS R2.0         | [9cdd546881](https://linux-hardware.org/?probe=9cdd546881) | Jul 29, 2019 |
| ASRock        | A300M-STX                | [edf300f175](https://linux-hardware.org/?probe=edf300f175) | Jul 29, 2019 |
| Gigabyte      | X299 UD4 Pro-CF          | [aad0551e27](https://linux-hardware.org/?probe=aad0551e27) | Jul 25, 2019 |
| ASUSTek       | E35M1-M                  | [1b78cc518f](https://linux-hardware.org/?probe=1b78cc518f) | Jul 08, 2019 |
| ASUSTek       | E35M1-M                  | [1f5e6b026b](https://linux-hardware.org/?probe=1f5e6b026b) | Jun 23, 2019 |
| ASUSTek       | PRIME A320M-K            | [f8c4365b6c](https://linux-hardware.org/?probe=f8c4365b6c) | Jun 07, 2019 |
| ASUSTek       | PRIME A320M-K            | [3968b06d9c](https://linux-hardware.org/?probe=3968b06d9c) | Jun 07, 2019 |
| HP            | 83ED                     | [532b72754e](https://linux-hardware.org/?probe=532b72754e) | May 06, 2019 |
| Gigabyte      | Z77P-D3                  | [e7259783d1](https://linux-hardware.org/?probe=e7259783d1) | Apr 13, 2019 |
| Pegatron      | 2A99                     | [196712630c](https://linux-hardware.org/?probe=196712630c) | Feb 26, 2019 |
| ASUSTek       | B150M-C                  | [88898f6797](https://linux-hardware.org/?probe=88898f6797) | Feb 10, 2019 |
| ECS           | A770M-A                  | [feacfccf11](https://linux-hardware.org/?probe=feacfccf11) | Feb 05, 2019 |
| Gigabyte      | AB350-Gaming 3-CF        | [bf1298d356](https://linux-hardware.org/?probe=bf1298d356) | Jan 29, 2019 |
| ABIT          | IP35-E                   | [87b22d6a66](https://linux-hardware.org/?probe=87b22d6a66) | Jan 26, 2019 |
| Gigabyte      | AX370-Gaming K7          | [bc26ed35a0](https://linux-hardware.org/?probe=bc26ed35a0) | Dec 08, 2018 |
| Unknown       | Grantsdale               | [65da6a461b](https://linux-hardware.org/?probe=65da6a461b) | Nov 21, 2018 |
| Pegatron      | 2AB6                     | [00a8407210](https://linux-hardware.org/?probe=00a8407210) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 20       | 14.29%  |
| Ubuntu 18.04                 | 15       | 10.71%  |
| Linux Mint 20.2              | 6        | 4.29%   |
| Debian 11                    | 6        | 4.29%   |
| Ubuntu 18.10                 | 5        | 3.57%   |
| Linux Mint 20.3              | 5        | 3.57%   |
| Zorin 16                     | 4        | 2.86%   |
| OpenMandriva 4.3             | 4        | 2.86%   |
| Debian 10                    | 4        | 2.86%   |
| Ubuntu 19.10                 | 3        | 2.14%   |
| Pop!_OS 21.10                | 3        | 2.14%   |
| OpenMandriva 4.2             | 3        | 2.14%   |
| Manjaro                      | 3        | 2.14%   |
| Fedora 31                    | 3        | 2.14%   |
| Xubuntu 20.04                | 2        | 1.43%   |
| Ubuntu 21.04                 | 2        | 1.43%   |
| Pop!_OS 20.10                | 2        | 1.43%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.43%   |
| openSUSE Leap-15.2           | 2        | 1.43%   |
| OpenMandriva 4.50            | 2        | 1.43%   |
| Linux Mint 20                | 2        | 1.43%   |
| KDE neon 20.04               | 2        | 1.43%   |
| ArcoLinux Rolling            | 2        | 1.43%   |
| Zorin 15                     | 1        | 0.71%   |
| Xubuntu 18.04                | 1        | 0.71%   |
| Ubuntu MATE 22.04            | 1        | 0.71%   |
| Ubuntu MATE 20.04            | 1        | 0.71%   |
| Ubuntu MATE 19.10            | 1        | 0.71%   |
| Ubuntu Budgie 22.04          | 1        | 0.71%   |
| Ubuntu Budgie 20.04          | 1        | 0.71%   |
| Ubuntu Budgie 18.04          | 1        | 0.71%   |
| Ubuntu 22.04                 | 1        | 0.71%   |
| Ubuntu 21.10                 | 1        | 0.71%   |
| Ubuntu 20.10                 | 1        | 0.71%   |
| Ubuntu 17.10                 | 1        | 0.71%   |
| Ubuntu                       | 1        | 0.71%   |
| ROSA R11                     | 1        | 0.71%   |
| Pop!_OS 21.04                | 1        | 0.71%   |
| Pop!_OS 20.04                | 1        | 0.71%   |
| Pop!_OS 19.10                | 1        | 0.71%   |
| openSUSE Leap-15.3           | 1        | 0.71%   |
| OpenMandriva 4.90            | 1        | 0.71%   |
| Manjaro 21.3.3               | 1        | 0.71%   |
| Manjaro 21.1.0               | 1        | 0.71%   |
| Manjaro 21.0.6               | 1        | 0.71%   |
| Manjaro 20.1                 | 1        | 0.71%   |
| Lubuntu 19.10                | 1        | 0.71%   |
| LMDE 4                       | 1        | 0.71%   |
| LinuxFX 10                   | 1        | 0.71%   |
| Linux Mint 19.3              | 1        | 0.71%   |
| Linux Mint 19.1              | 1        | 0.71%   |
| Linux Mint 19                | 1        | 0.71%   |
| Kubuntu 20.04                | 1        | 0.71%   |
| Fedora 34                    | 1        | 0.71%   |
| Fedora 32                    | 1        | 0.71%   |
| Endless 3.7.8                | 1        | 0.71%   |
| Elementary 5.1.7             | 1        | 0.71%   |
| Elementary 5.0               | 1        | 0.71%   |
| Clear Linux 32270            | 1        | 0.71%   |
| Arch Rolling                 | 1        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 49       | 37.12%  |
| Linux Mint    | 15       | 11.36%  |
| OpenMandriva  | 10       | 7.58%   |
| Pop!_OS       | 8        | 6.06%   |
| Debian        | 8        | 6.06%   |
| Manjaro       | 7        | 5.3%    |
| Zorin         | 5        | 3.79%   |
| openSUSE      | 4        | 3.03%   |
| Fedora        | 4        | 3.03%   |
| Xubuntu       | 3        | 2.27%   |
| Ubuntu Budgie | 3        | 2.27%   |
| Ubuntu MATE   | 2        | 1.52%   |
| KDE neon      | 2        | 1.52%   |
| ArcoLinux     | 2        | 1.52%   |
| Arch          | 2        | 1.52%   |
| ROSA          | 1        | 0.76%   |
| Lubuntu       | 1        | 0.76%   |
| LMDE          | 1        | 0.76%   |
| LinuxFX       | 1        | 0.76%   |
| Kubuntu       | 1        | 0.76%   |
| Endless       | 1        | 0.76%   |
| Elementary    | 1        | 0.76%   |
| Clear Linux   | 1        | 0.76%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-58-generic         | 4        | 2.61%   |
| 5.16.7-desktop-1omv4003  | 4        | 2.61%   |
| 5.4.0-91-generic         | 3        | 1.96%   |
| 5.3.0-26-generic         | 3        | 1.96%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.96%   |
| 5.0.0-27-generic         | 3        | 1.96%   |
| 5.8.0-48-generic         | 2        | 1.31%   |
| 5.4.0-48-generic         | 2        | 1.31%   |
| 5.4.0-42-generic         | 2        | 1.31%   |
| 5.4.0-26-generic         | 2        | 1.31%   |
| 5.4.0-100-generic        | 2        | 1.31%   |
| 5.3.0-42-generic         | 2        | 1.31%   |
| 5.3.0-28-generic         | 2        | 1.31%   |
| 5.13.0-40-generic        | 2        | 1.31%   |
| 5.12.4-desktop-1omv4050  | 2        | 1.31%   |
| 5.11.0-41-generic        | 2        | 1.31%   |
| 5.11.0-38-generic        | 2        | 1.31%   |
| 5.11.0-37-generic        | 2        | 1.31%   |
| 5.10.0-13-amd64          | 2        | 1.31%   |
| 4.19.0-14-amd64          | 2        | 1.31%   |
| 4.18.0-10-generic        | 2        | 1.31%   |
| 4.15.0-45-generic        | 2        | 1.31%   |
| 4.15.0-20-generic        | 2        | 1.31%   |
| 5.9.0-0.bpo.5-amd64      | 1        | 0.65%   |
| 5.8.0-59-generic         | 1        | 0.65%   |
| 5.8.0-41-generic         | 1        | 0.65%   |
| 5.8.0-40-generic         | 1        | 0.65%   |
| 5.8.0-34-generic         | 1        | 0.65%   |
| 5.7.11-100.fc31.x86_64   | 1        | 0.65%   |
| 5.7.0-0.bpo.2-amd64      | 1        | 0.65%   |
| 5.6.12-300.fc32.x86_64   | 1        | 0.65%   |
| 5.4.64-1-MANJARO         | 1        | 0.65%   |
| 5.4.20-200.fc31.x86_64   | 1        | 0.65%   |
| 5.4.2-300.fc31.x86_64    | 1        | 0.65%   |
| 5.4.18-902.native        | 1        | 0.65%   |
| 5.4.0-97-generic         | 1        | 0.65%   |
| 5.4.0-92-generic         | 1        | 0.65%   |
| 5.4.0-90-generic         | 1        | 0.65%   |
| 5.4.0-89-generic         | 1        | 0.65%   |
| 5.4.0-7626-generic       | 1        | 0.65%   |
| 5.4.0-74-generic         | 1        | 0.65%   |
| 5.4.0-66-generic         | 1        | 0.65%   |
| 5.4.0-60-generic         | 1        | 0.65%   |
| 5.4.0-56-generic         | 1        | 0.65%   |
| 5.4.0-52-generic         | 1        | 0.65%   |
| 5.4.0-51-generic         | 1        | 0.65%   |
| 5.4.0-45-generic         | 1        | 0.65%   |
| 5.4.0-40-generic         | 1        | 0.65%   |
| 5.4.0-37-generic         | 1        | 0.65%   |
| 5.4.0-33-generic         | 1        | 0.65%   |
| 5.4.0-31-generic         | 1        | 0.65%   |
| 5.4.0-28-generic         | 1        | 0.65%   |
| 5.4.0-21-generic         | 1        | 0.65%   |
| 5.4.0-121-generic        | 1        | 0.65%   |
| 5.4.0-109-generic        | 1        | 0.65%   |
| 5.3.18-lp152.63-default  | 1        | 0.65%   |
| 5.3.18-lp152.57-preempt  | 1        | 0.65%   |
| 5.3.18-59.27-preempt     | 1        | 0.65%   |
| 5.3.18-59.24-preempt     | 1        | 0.65%   |
| 5.3.16-300.fc31.x86_64   | 1        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 33       | 22.76%  |
| 5.11.0   | 12       | 8.28%   |
| 5.3.0    | 11       | 7.59%   |
| 4.15.0   | 10       | 6.9%    |
| 4.18.0   | 8        | 5.52%   |
| 5.13.0   | 7        | 4.83%   |
| 5.10.0   | 6        | 4.14%   |
| 5.8.0    | 5        | 3.45%   |
| 5.16.7   | 4        | 2.76%   |
| 5.0.0    | 4        | 2.76%   |
| 5.15.0   | 3        | 2.07%   |
| 5.12.4   | 3        | 2.07%   |
| 5.10.14  | 3        | 2.07%   |
| 4.19.0   | 3        | 2.07%   |
| 5.3.18   | 2        | 1.38%   |
| 5.16.11  | 2        | 1.38%   |
| 5.9.0    | 1        | 0.69%   |
| 5.7.11   | 1        | 0.69%   |
| 5.7.0    | 1        | 0.69%   |
| 5.6.12   | 1        | 0.69%   |
| 5.4.64   | 1        | 0.69%   |
| 5.4.20   | 1        | 0.69%   |
| 5.4.2    | 1        | 0.69%   |
| 5.4.18   | 1        | 0.69%   |
| 5.3.16   | 1        | 0.69%   |
| 5.18.4   | 1        | 0.69%   |
| 5.18.14  | 1        | 0.69%   |
| 5.18.12  | 1        | 0.69%   |
| 5.17.4   | 1        | 0.69%   |
| 5.17.3   | 1        | 0.69%   |
| 5.16.18  | 1        | 0.69%   |
| 5.16.15  | 1        | 0.69%   |
| 5.15.8   | 1        | 0.69%   |
| 5.15.53  | 1        | 0.69%   |
| 5.15.32  | 1        | 0.69%   |
| 5.15.15  | 1        | 0.69%   |
| 5.14.7   | 1        | 0.69%   |
| 5.14.11  | 1        | 0.69%   |
| 5.11.20  | 1        | 0.69%   |
| 5.10.92  | 1        | 0.69%   |
| 5.10.79  | 1        | 0.69%   |
| 5.10.7   | 1        | 0.69%   |
| 5.10.53  | 1        | 0.69%   |
| 4.14.234 | 1        | 0.69%   |
| 4.13.0   | 1        | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 25.87%  |
| 5.3     | 14       | 9.79%   |
| 5.11    | 13       | 9.09%   |
| 5.10    | 13       | 9.09%   |
| 4.15    | 10       | 6.99%   |
| 4.18    | 8        | 5.59%   |
| 5.15    | 7        | 4.9%    |
| 5.13    | 7        | 4.9%    |
| 5.16    | 6        | 4.2%    |
| 5.8     | 5        | 3.5%    |
| 5.0     | 4        | 2.8%    |
| 5.18    | 3        | 2.1%    |
| 5.12    | 3        | 2.1%    |
| 4.19    | 3        | 2.1%    |
| 5.7     | 2        | 1.4%    |
| 5.17    | 2        | 1.4%    |
| 5.14    | 2        | 1.4%    |
| 5.9     | 1        | 0.7%    |
| 5.6     | 1        | 0.7%    |
| 4.14    | 1        | 0.7%    |
| 4.13    | 1        | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 129      | 98.47%  |
| i686   | 2        | 1.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 53       | 40.15%  |
| KDE5       | 23       | 17.42%  |
| Unknown    | 21       | 15.91%  |
| X-Cinnamon | 9        | 6.82%   |
| XFCE       | 7        | 5.3%    |
| MATE       | 4        | 3.03%   |
| KDE        | 4        | 3.03%   |
| Cinnamon   | 3        | 2.27%   |
| Budgie     | 3        | 2.27%   |
| Unity      | 1        | 0.76%   |
| Pantheon   | 1        | 0.76%   |
| openbox    | 1        | 0.76%   |
| LXQt       | 1        | 0.76%   |
| DWM        | 1        | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 114      | 86.36%  |
| Unknown | 9        | 6.82%   |
| Wayland | 6        | 4.55%   |
| Tty     | 3        | 2.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 76       | 56.3%   |
| SDDM    | 22       | 16.3%   |
| LightDM | 14       | 10.37%  |
| GDM     | 10       | 7.41%   |
| GDM3    | 9        | 6.67%   |
| TDM     | 4        | 2.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 67       | 49.63%  |
| hr_HR   | 36       | 26.67%  |
| Unknown | 24       | 17.78%  |
| en_GB   | 6        | 4.44%   |
| C       | 2        | 1.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 78       | 59.54%  |
| EFI  | 53       | 40.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 106      | 79.1%   |
| Overlay | 12       | 8.96%   |
| Btrfs   | 8        | 5.97%   |
| Unknown | 4        | 2.99%   |
| Zfs     | 3        | 2.24%   |
| Xfs     | 1        | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 82       | 62.12%  |
| GPT     | 35       | 26.52%  |
| MBR     | 15       | 11.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 79.26%  |
| Yes       | 28       | 20.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 62.41%  |
| Yes       | 50       | 37.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 33       | 25.19%  |
| ASRock              | 32       | 24.43%  |
| Gigabyte Technology | 26       | 19.85%  |
| MSI                 | 10       | 7.63%   |
| Hewlett-Packard     | 7        | 5.34%   |
| Pegatron            | 5        | 3.82%   |
| Dell                | 5        | 3.82%   |
| Intel               | 4        | 3.05%   |
| ECS                 | 3        | 2.29%   |
| WinFast             | 1        | 0.76%   |
| Fujitsu Siemens     | 1        | 0.76%   |
| Foxconn             | 1        | 0.76%   |
| Acer                | 1        | 0.76%   |
| ABIT                | 1        | 0.76%   |
| Unknown             | 1        | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 4        | 3.05%   |
| ASUS PRIME A320M-K                     | 3        | 2.29%   |
| MSI MS-7850                            | 2        | 1.53%   |
| Gigabyte A320M-S2H                     | 2        | 1.53%   |
| ASUS P8H77-V LE                        | 2        | 1.53%   |
| ASUS M5A78L LE                         | 2        | 1.53%   |
| ASRock H61M-DGS                        | 2        | 1.53%   |
| ASRock B450M-HDV R4.0                  | 2        | 1.53%   |
| WinFast N570SM2AA                      | 1        | 0.76%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.76%   |
| Pegatron HPE-520ad                     | 1        | 0.76%   |
| Pegatron G5261de                       | 1        | 0.76%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 0.76%   |
| Pegatron 27-1001eu                     | 1        | 0.76%   |
| MSI MS-7C02                            | 1        | 0.76%   |
| MSI MS-7B98                            | 1        | 0.76%   |
| MSI MS-7B84                            | 1        | 0.76%   |
| MSI MS-7B07                            | 1        | 0.76%   |
| MSI MS-7817                            | 1        | 0.76%   |
| MSI MS-7681                            | 1        | 0.76%   |
| MSI MS-7586                            | 1        | 0.76%   |
| MSI MS-7360                            | 1        | 0.76%   |
| Intel H61M-S2PV                        | 1        | 0.76%   |
| Intel DX58SO AAE29331-501              | 1        | 0.76%   |
| Intel DH67BL AAG10189-213              | 1        | 0.76%   |
| Intel DH61CR AAG14064-204              | 1        | 0.76%   |
| HP Z840 Workstation                    | 1        | 0.76%   |
| HP Z440 Workstation                    | 1        | 0.76%   |
| HP ProOne 400 G1 AiO                   | 1        | 0.76%   |
| HP ProDesk 600 G4 PCI MT               | 1        | 0.76%   |
| HP ProDesk 600 G1 SFF                  | 1        | 0.76%   |
| HP EliteDesk 800 G1 DM                 | 1        | 0.76%   |
| HP Compaq dc7900 Small Form Factor     | 1        | 0.76%   |
| Gigabyte Z97-D3H                       | 1        | 0.76%   |
| Gigabyte Z77P-D3                       | 1        | 0.76%   |
| Gigabyte Z390 M GAMING                 | 1        | 0.76%   |
| Gigabyte Z390 AORUS PRO                | 1        | 0.76%   |
| Gigabyte X48T-DQ6                      | 1        | 0.76%   |
| Gigabyte X399 AORUS XTREME             | 1        | 0.76%   |
| Gigabyte X299 UD4 Pro                  | 1        | 0.76%   |
| Gigabyte P31-ES3G                      | 1        | 0.76%   |
| Gigabyte H410M H V3                    | 1        | 0.76%   |
| Gigabyte GB-BRR7H-4800                 | 1        | 0.76%   |
| Gigabyte GA-MA785GMT-UD2H              | 1        | 0.76%   |
| Gigabyte GA-MA770-UD3                  | 1        | 0.76%   |
| Gigabyte GA-990XA-UD3                  | 1        | 0.76%   |
| Gigabyte G41M-Combo                    | 1        | 0.76%   |
| Gigabyte G31MX-S2                      | 1        | 0.76%   |
| Gigabyte G1.Sniper Z87                 | 1        | 0.76%   |
| Gigabyte F2A78M-DS2                    | 1        | 0.76%   |
| Gigabyte B85M-DS3H                     | 1        | 0.76%   |
| Gigabyte B450 GAMING X                 | 1        | 0.76%   |
| Gigabyte AX370-Gaming K7               | 1        | 0.76%   |
| Gigabyte AB350-Gaming 3                | 1        | 0.76%   |
| Gigabyte A320M-H                       | 1        | 0.76%   |
| Gigabyte 990FXA-UD3                    | 1        | 0.76%   |
| Gigabyte 965P-DS3                      | 1        | 0.76%   |
| Fujitsu Siemens D2151-A1               | 1        | 0.76%   |
| Foxconn Compaq 500B Microtower         | 1        | 0.76%   |
| ECS H61H2-M2                           | 1        | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 8        | 6.11%   |
| ASUS All                  | 4        | 3.05%   |
| Dell Vostro               | 3        | 2.29%   |
| ASUS TUF                  | 3        | 2.29%   |
| MSI MS-7850               | 2        | 1.53%   |
| HP ProDesk                | 2        | 1.53%   |
| Gigabyte Z390             | 2        | 1.53%   |
| Gigabyte A320M-S2H        | 2        | 1.53%   |
| Dell OptiPlex             | 2        | 1.53%   |
| ASUS ROG                  | 2        | 1.53%   |
| ASUS P8H77-V              | 2        | 1.53%   |
| ASUS M5A78L               | 2        | 1.53%   |
| ASRock H97                | 2        | 1.53%   |
| ASRock H61M-DGS           | 2        | 1.53%   |
| ASRock B450M-HDV          | 2        | 1.53%   |
| ASRock A320M-HDV          | 2        | 1.53%   |
| WinFast N570SM2AA         | 1        | 0.76%   |
| Pegatron Pro              | 1        | 0.76%   |
| Pegatron HPE-520ad        | 1        | 0.76%   |
| Pegatron G5261de          | 1        | 0.76%   |
| Pegatron Compaq           | 1        | 0.76%   |
| Pegatron 27-1001eu        | 1        | 0.76%   |
| MSI MS-7C02               | 1        | 0.76%   |
| MSI MS-7B98               | 1        | 0.76%   |
| MSI MS-7B84               | 1        | 0.76%   |
| MSI MS-7B07               | 1        | 0.76%   |
| MSI MS-7817               | 1        | 0.76%   |
| MSI MS-7681               | 1        | 0.76%   |
| MSI MS-7586               | 1        | 0.76%   |
| MSI MS-7360               | 1        | 0.76%   |
| Intel H61M-S2PV           | 1        | 0.76%   |
| Intel DX58SO              | 1        | 0.76%   |
| Intel DH67BL              | 1        | 0.76%   |
| Intel DH61CR              | 1        | 0.76%   |
| HP Z840                   | 1        | 0.76%   |
| HP Z440                   | 1        | 0.76%   |
| HP ProOne                 | 1        | 0.76%   |
| HP EliteDesk              | 1        | 0.76%   |
| HP Compaq                 | 1        | 0.76%   |
| Gigabyte Z97-D3H          | 1        | 0.76%   |
| Gigabyte Z77P-D3          | 1        | 0.76%   |
| Gigabyte X48T-DQ6         | 1        | 0.76%   |
| Gigabyte X399             | 1        | 0.76%   |
| Gigabyte X299             | 1        | 0.76%   |
| Gigabyte P31-ES3G         | 1        | 0.76%   |
| Gigabyte H410M            | 1        | 0.76%   |
| Gigabyte GB-BRR7H-4800    | 1        | 0.76%   |
| Gigabyte GA-MA785GMT-UD2H | 1        | 0.76%   |
| Gigabyte GA-MA770-UD3     | 1        | 0.76%   |
| Gigabyte GA-990XA-UD3     | 1        | 0.76%   |
| Gigabyte G41M-Combo       | 1        | 0.76%   |
| Gigabyte G31MX-S2         | 1        | 0.76%   |
| Gigabyte G1.Sniper        | 1        | 0.76%   |
| Gigabyte F2A78M-DS2       | 1        | 0.76%   |
| Gigabyte B85M-DS3H        | 1        | 0.76%   |
| Gigabyte B450             | 1        | 0.76%   |
| Gigabyte AX370-Gaming     | 1        | 0.76%   |
| Gigabyte AB350-Gaming     | 1        | 0.76%   |
| Gigabyte A320M-H          | 1        | 0.76%   |
| Gigabyte 990FXA-UD3       | 1        | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 16       | 12.21%  |
| 2018 | 13       | 9.92%   |
| 2012 | 13       | 9.92%   |
| 2017 | 12       | 9.16%   |
| 2011 | 12       | 9.16%   |
| 2020 | 9        | 6.87%   |
| 2014 | 8        | 6.11%   |
| 2009 | 8        | 6.11%   |
| 2019 | 7        | 5.34%   |
| 2010 | 7        | 5.34%   |
| 2008 | 7        | 5.34%   |
| 2015 | 6        | 4.58%   |
| 2021 | 5        | 3.82%   |
| 2007 | 4        | 3.05%   |
| 2006 | 2        | 1.53%   |
| 2005 | 2        | 1.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 131      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 128      | 96.97%  |
| Enabled  | 4        | 3.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 131      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 36       | 26.87%  |
| 8.01-16.0   | 36       | 26.87%  |
| 4.01-8.0    | 25       | 18.66%  |
| 3.01-4.0    | 17       | 12.69%  |
| 32.01-64.0  | 10       | 7.46%   |
| 1.01-2.0    | 5        | 3.73%   |
| 24.01-32.0  | 2        | 1.49%   |
| 64.01-256.0 | 2        | 1.49%   |
| 2.01-3.0    | 1        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 61       | 42.96%  |
| 2.01-3.0   | 37       | 26.06%  |
| 4.01-8.0   | 17       | 11.97%  |
| 3.01-4.0   | 13       | 9.15%   |
| 0.51-1.0   | 9        | 6.34%   |
| 16.01-24.0 | 2        | 1.41%   |
| 8.01-16.0  | 2        | 1.41%   |
| 0.01-0.5   | 1        | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 37.23%  |
| 2      | 44       | 32.12%  |
| 3      | 25       | 18.25%  |
| 5      | 8        | 5.84%   |
| 4      | 6        | 4.38%   |
| 0      | 2        | 1.46%   |
| 7      | 1        | 0.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 70       | 53.03%  |
| No        | 62       | 46.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 128      | 97.71%  |
| No        | 3        | 2.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 64.66%  |
| Yes       | 47       | 35.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 83.21%  |
| Yes       | 22       | 16.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Croatia | 131      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Zagreb          | 72       | 51.06%  |
| Split           | 11       | 7.8%    |
| Rijeka          | 6        | 4.26%   |
| Varaždin       | 3        | 2.13%   |
| Samobor         | 3        | 2.13%   |
| Osijek          | 3        | 2.13%   |
| Koprivnica      | 3        | 2.13%   |
| Zaprešić      | 2        | 1.42%   |
| Virovitica      | 2        | 1.42%   |
| Velika Gorica   | 2        | 1.42%   |
| Pula            | 2        | 1.42%   |
| Ivanja Reka     | 2        | 1.42%   |
| GJurgevac       | 2        | 1.42%   |
| Bjelovar        | 2        | 1.42%   |
| Zadar           | 1        | 0.71%   |
| Visnjevac       | 1        | 0.71%   |
| Supetar         | 1        | 0.71%   |
| Stari Perkovci  | 1        | 0.71%   |
| Slatina         | 1        | 0.71%   |
| Skrad           | 1        | 0.71%   |
| Sisak           | 1        | 0.71%   |
| Raslina         | 1        | 0.71%   |
| Prelog          | 1        | 0.71%   |
| Postira         | 1        | 0.71%   |
| Pitomaca        | 1        | 0.71%   |
| Novi Marof      | 1        | 0.71%   |
| Matulji         | 1        | 0.71%   |
| Mali Lošinj    | 1        | 0.71%   |
| Mahicno         | 1        | 0.71%   |
| Labin           | 1        | 0.71%   |
| Kućan Marof    | 1        | 0.71%   |
| Krizevci        | 1        | 0.71%   |
| Kastel Gomilica | 1        | 0.71%   |
| Hvar            | 1        | 0.71%   |
| Grad            | 1        | 0.71%   |
| Galgovo         | 1        | 0.71%   |
| Dubrovnik       | 1        | 0.71%   |
| Dobrec          | 1        | 0.71%   |
| Bosnjaci        | 1        | 0.71%   |
| Baska Voda      | 1        | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 61       | 106    | 26.18%  |
| Kingston            | 29       | 41     | 12.45%  |
| Samsung Electronics | 28       | 40     | 12.02%  |
| Seagate             | 23       | 34     | 9.87%   |
| Toshiba             | 20       | 25     | 8.58%   |
| Crucial             | 12       | 15     | 5.15%   |
| Intel               | 9        | 10     | 3.86%   |
| A-DATA Technology   | 8        | 11     | 3.43%   |
| Patriot             | 4        | 7      | 1.72%   |
| Hitachi             | 4        | 5      | 1.72%   |
| Transcend           | 3        | 3      | 1.29%   |
| Silicon Motion      | 3        | 4      | 1.29%   |
| SanDisk             | 3        | 4      | 1.29%   |
| Phison              | 3        | 3      | 1.29%   |
| OCZ                 | 2        | 3      | 0.86%   |
| Maxtor              | 2        | 2      | 0.86%   |
| Gigabyte Technology | 2        | 2      | 0.86%   |
| Corsair             | 2        | 2      | 0.86%   |
| XPG                 | 1        | 3      | 0.43%   |
| TO Exter            | 1        | 1      | 0.43%   |
| SK hynix            | 1        | 1      | 0.43%   |
| Netac               | 1        | 1      | 0.43%   |
| Mushkin             | 1        | 2      | 0.43%   |
| Min Yi U            | 1        | 1      | 0.43%   |
| KingSpec            | 1        | 1      | 0.43%   |
| Kingmax             | 1        | 1      | 0.43%   |
| HPE                 | 1        | 2      | 0.43%   |
| HGST HTS            | 1        | 1      | 0.43%   |
| HGST                | 1        | 1      | 0.43%   |
| Goodram             | 1        | 1      | 0.43%   |
| External            | 1        | 1      | 0.43%   |
| ASMedia             | 1        | 1      | 0.43%   |
| AMD                 | 1        | 2      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SV300S37A120G 120GB SSD | 5        | 1.89%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 1.89%   |
| Toshiba HDWD130 3TB              | 4        | 1.51%   |
| Samsung SSD 850 EVO 250GB        | 4        | 1.51%   |
| Kingston SA400S37120G 120GB SSD  | 4        | 1.51%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 1.13%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.13%   |
| Toshiba HDWD110 1TB              | 3        | 1.13%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 1.13%   |
| Samsung HD103SI 1TB              | 3        | 1.13%   |
| Patriot Burst 240GB SSD          | 3        | 1.13%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.13%   |
| Intel SSDSC2BW120A4 120GB        | 3        | 1.13%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 0.75%   |
| WDC WD6400AAKS-22A7B0 640GB      | 2        | 0.75%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2        | 0.75%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.75%   |
| WDC WD3200AAKS-00L9A0 320GB      | 2        | 0.75%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 0.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 2        | 0.75%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 0.75%   |
| WDC WD1600AAJS-07M0A0 160GB      | 2        | 0.75%   |
| Toshiba HDWD120 2TB              | 2        | 0.75%   |
| Toshiba DT01ACA300 3TB           | 2        | 0.75%   |
| Seagate ST31000524AS 1TB         | 2        | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.75%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.75%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.75%   |
| Samsung SSD 860 PRO 256GB        | 2        | 0.75%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 0.75%   |
| Samsung NVMe SSD Drive 1TB       | 2        | 0.75%   |
| Samsung HD256GJ 250GB            | 2        | 0.75%   |
| Kingston SV300S37A60G 64GB SSD   | 2        | 0.75%   |
| Kingston SUV400S37240G 240GB SSD | 2        | 0.75%   |
| Kingston SHFS37A120G 120GB SSD   | 2        | 0.75%   |
| Intel SSDSC2BW120H6 120GB        | 2        | 0.75%   |
| Intel SSDPEKKW256G7 256GB        | 2        | 0.75%   |
| Crucial CT480BX500SSD1 480GB     | 2        | 0.75%   |
| Crucial CT240BX500SSD1 240GB     | 2        | 0.75%   |
| Crucial CT120BX500SSD1 120GB     | 2        | 0.75%   |
| A-DATA SU650 240GB SSD           | 2        | 0.75%   |
| XPG NVMe SSD Drive 256GB         | 1        | 0.38%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1        | 0.38%   |
| WDC WDS250G2X0C-00L350 250GB     | 1        | 0.38%   |
| WDC WDS100T3XHC-00SJG0 1TB       | 1        | 0.38%   |
| WDC WD800JD-08LSA0 80GB          | 1        | 0.38%   |
| WDC WD800AAJS-00TDA0 80GB        | 1        | 0.38%   |
| WDC WD6401AALS-00L3B2 640GB      | 1        | 0.38%   |
| WDC WD6400AAKS-65A7B2 640GB      | 1        | 0.38%   |
| WDC WD6400AAKS-07A7B0 640GB      | 1        | 0.38%   |
| WDC WD5003ABYX-88 LEN 500GB      | 1        | 0.38%   |
| WDC WD5000LPCX-22VHAT1 500GB     | 1        | 0.38%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 1        | 0.38%   |
| WDC WD5000AAKX-221CA1 500GB      | 1        | 0.38%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1        | 0.38%   |
| WDC WD5000AAKX-003CA0 500GB      | 1        | 0.38%   |
| WDC WD5000AAKS-55V0A0 500GB      | 1        | 0.38%   |
| WDC WD40PURZ-85TTDY0 4TB         | 1        | 0.38%   |
| WDC WD40PURZ-74AKKY0 4TB         | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 59       | 97     | 50.86%  |
| Seagate             | 23       | 34     | 19.83%  |
| Toshiba             | 19       | 24     | 16.38%  |
| Samsung Electronics | 7        | 9      | 6.03%   |
| Hitachi             | 4        | 5      | 3.45%   |
| Maxtor              | 2        | 2      | 1.72%   |
| HGST HTS            | 1        | 1      | 0.86%   |
| HGST                | 1        | 1      | 0.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 27       | 36     | 30.34%  |
| Samsung Electronics | 13       | 19     | 14.61%  |
| Crucial             | 11       | 13     | 12.36%  |
| Intel               | 7        | 8      | 7.87%   |
| A-DATA Technology   | 6        | 8      | 6.74%   |
| Patriot             | 3        | 6      | 3.37%   |
| WDC                 | 2        | 2      | 2.25%   |
| Transcend           | 2        | 2      | 2.25%   |
| SanDisk             | 2        | 3      | 2.25%   |
| OCZ                 | 2        | 3      | 2.25%   |
| Gigabyte Technology | 2        | 2      | 2.25%   |
| Toshiba             | 1        | 1      | 1.12%   |
| TO Exter            | 1        | 1      | 1.12%   |
| SK hynix            | 1        | 1      | 1.12%   |
| Netac               | 1        | 1      | 1.12%   |
| Mushkin             | 1        | 2      | 1.12%   |
| Min Yi U            | 1        | 1      | 1.12%   |
| KingSpec            | 1        | 1      | 1.12%   |
| Kingmax             | 1        | 1      | 1.12%   |
| Goodram             | 1        | 1      | 1.12%   |
| Corsair             | 1        | 1      | 1.12%   |
| ASMedia             | 1        | 1      | 1.12%   |
| AMD                 | 1        | 2      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 93       | 173    | 47.45%  |
| SSD     | 73       | 116    | 37.24%  |
| NVMe    | 29       | 46     | 14.8%   |
| Unknown | 1        | 2      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 117      | 285    | 77.48%  |
| NVMe | 28       | 45     | 18.54%  |
| SAS  | 6        | 7      | 3.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 95       | 174    | 55.23%  |
| 0.51-1.0   | 46       | 68     | 26.74%  |
| 1.01-2.0   | 15       | 21     | 8.72%   |
| 2.01-3.0   | 11       | 21     | 6.4%    |
| 3.01-4.0   | 4        | 4      | 2.33%   |
| 4.01-10.0  | 1        | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 42       | 30%     |
| 251-500        | 22       | 15.71%  |
| 501-1000       | 21       | 15%     |
| 1001-2000      | 16       | 11.43%  |
| More than 3000 | 9        | 6.43%   |
| 1-20           | 9        | 6.43%   |
| 51-100         | 9        | 6.43%   |
| Unknown        | 6        | 4.29%   |
| 2001-3000      | 4        | 2.86%   |
| 21-50          | 2        | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 66       | 45.21%  |
| 21-50          | 15       | 10.27%  |
| 251-500        | 14       | 9.59%   |
| 501-1000       | 11       | 7.53%   |
| 101-250        | 10       | 6.85%   |
| 51-100         | 10       | 6.85%   |
| 1001-2000      | 8        | 5.48%   |
| Unknown        | 6        | 4.11%   |
| 2001-3000      | 4        | 2.74%   |
| More than 3000 | 2        | 1.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-07A7B0 640GB        | 1        | 1      | 5.88%   |
| WDC WD5000AAKX-221CA1 500GB        | 1        | 1      | 5.88%   |
| WDC WD3200AAKS-00L9A0 320GB        | 1        | 1      | 5.88%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1      | 5.88%   |
| WDC WD10EZEX-00MFCA0 1TB           | 1        | 1      | 5.88%   |
| Transcend TS480GSSD220S 480GB      | 1        | 1      | 5.88%   |
| Toshiba DT01ACA100 1TB             | 1        | 1      | 5.88%   |
| SK hynix SH920 2.5 7MM 256GB SSD   | 1        | 1      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 5.88%   |
| Seagate ST31500341AS 1TB           | 1        | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 5.88%   |
| SanDisk SDSSDA240G 240GB           | 1        | 1      | 5.88%   |
| Kingston SHFS37A120G 120GB SSD     | 1        | 1      | 5.88%   |
| Intel SSDSC2BW120A4 120GB          | 1        | 1      | 5.88%   |
| Hitachi HDS723020BLA642 2TB        | 1        | 1      | 5.88%   |
| Crucial CT525MX300SSD1 528GB       | 1        | 1      | 5.88%   |
| Crucial CT120BX500SSD1 120GB       | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Desktops | Drives | Percent |
|-----------|----------|--------|---------|
| WDC       | 5        | 5      | 29.41%  |
| Seagate   | 3        | 3      | 17.65%  |
| Crucial   | 2        | 2      | 11.76%  |
| Transcend | 1        | 1      | 5.88%   |
| Toshiba   | 1        | 1      | 5.88%   |
| SK hynix  | 1        | 1      | 5.88%   |
| SanDisk   | 1        | 1      | 5.88%   |
| Kingston  | 1        | 1      | 5.88%   |
| Intel     | 1        | 1      | 5.88%   |
| Hitachi   | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 5      | 50%     |
| Seagate | 3        | 3      | 30%     |
| Toshiba | 1        | 1      | 10%     |
| Hitachi | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 10     | 58.82%  |
| SSD  | 7        | 7      | 41.18%  |

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
| Detected | 85       | 219    | 58.62%  |
| Works    | 46       | 101    | 31.72%  |
| Malfunc  | 14       | 17     | 9.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 83       | 48.26%  |
| AMD                         | 42       | 24.42%  |
| Samsung Electronics         | 10       | 5.81%   |
| Phison Electronics          | 5        | 2.91%   |
| JMicron Technology          | 5        | 2.91%   |
| Nvidia                      | 4        | 2.33%   |
| Kingston Technology Company | 4        | 2.33%   |
| Silicon Motion              | 3        | 1.74%   |
| Marvell Technology Group    | 3        | 1.74%   |
| ASMedia Technology          | 3        | 1.74%   |
| ADATA Technology            | 3        | 1.74%   |
| SanDisk                     | 2        | 1.16%   |
| VIA Technologies            | 1        | 0.58%   |
| Unknown                     | 1        | 0.58%   |
| Micron/Crucial Technology   | 1        | 0.58%   |
| Broadcom / LSI              | 1        | 0.58%   |
| Adaptec                     | 1        | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 10.39%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 6.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 4.76%   |
| AMD FCH SATA Controller D                                                               | 9        | 3.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 3.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.16%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.16%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.73%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.73%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.3%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.87%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.87%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.87%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.87%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.87%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.87%   |
| Intel SSD 600P Series                                                                   | 2        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.87%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.87%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.87%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.87%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.43%   |
| VIA VT8251 AHCI/SATA 4-Port Controller                                                  | 1        | 0.43%   |
| Unknown Non-Volatile memory controller                                                  | 1        | 0.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.43%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.43%   |
| Samsung NVMe SSD Controller 172Xa/172Xb                                                 | 1        | 0.43%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.43%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.43%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.43%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 0.43%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.43%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.43%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.43%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.43%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.43%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.43%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 0.43%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 0.43%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 98       | 54.75%  |
| IDE  | 46       | 25.7%   |
| NVMe | 29       | 16.2%   |
| RAID | 5        | 2.79%   |
| SAS  | 1        | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 83       | 63.36%  |
| AMD    | 48       | 36.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 3.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 2.24%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 2.24%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.24%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 3        | 2.24%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2.24%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.49%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.49%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 2        | 1.49%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.49%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.49%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 2        | 1.49%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.49%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.49%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.49%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.49%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.49%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.49%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.49%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 1.49%   |
| AMD Phenom II X4 965 Processor              | 2        | 1.49%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.49%   |
| AMD Athlon X4 740 Quad Core Processor       | 2        | 1.49%   |
| AMD Athlon 64 X2 Dual Core Processor 6400+  | 2        | 1.49%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.75%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz         | 1        | 0.75%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.75%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.75%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.75%   |
| Intel Pentium CPU G4560T @ 2.90GHz          | 1        | 0.75%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.75%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.75%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.75%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.75%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.75%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.75%   |
| Intel Core i7 CPU 965 @ 3.20GHz             | 1        | 0.75%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.75%   |
| Intel Core i5-7640X CPU @ 4.00GHz           | 1        | 0.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.75%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 0.75%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 0.75%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 0.75%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 0.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.75%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 0.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1        | 0.75%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.75%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 0.75%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 0.75%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 0.75%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 0.75%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 0.75%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.75%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1        | 0.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 27       | 20.15%  |
| Intel Core i3           | 17       | 12.69%  |
| Intel Core i7           | 12       | 8.96%   |
| AMD Ryzen 5             | 8        | 5.97%   |
| Intel Core 2 Duo        | 7        | 5.22%   |
| AMD FX                  | 5        | 3.73%   |
| Intel Pentium           | 4        | 2.99%   |
| AMD Ryzen 3             | 4        | 2.99%   |
| AMD Athlon II X4        | 4        | 2.99%   |
| Other                   | 3        | 2.24%   |
| Intel Xeon              | 3        | 2.24%   |
| AMD Ryzen 9             | 3        | 2.24%   |
| AMD Ryzen 7             | 3        | 2.24%   |
| AMD Phenom II X4        | 3        | 2.24%   |
| AMD Athlon X4           | 3        | 2.24%   |
| AMD Athlon 64 X2        | 3        | 2.24%   |
| Intel Pentium Dual-Core | 2        | 1.49%   |
| Intel Pentium 4         | 2        | 1.49%   |
| Intel Core i9           | 2        | 1.49%   |
| Intel Core 2 Quad       | 2        | 1.49%   |
| Intel Core 2            | 2        | 1.49%   |
| AMD A8                  | 2        | 1.49%   |
| Intel Pentium Dual      | 1        | 0.75%   |
| Intel Celeron           | 1        | 0.75%   |
| AMD Ryzen Threadripper  | 1        | 0.75%   |
| AMD Ryzen 7 PRO         | 1        | 0.75%   |
| AMD Ryzen 5 PRO         | 1        | 0.75%   |
| AMD Ryzen 3 PRO         | 1        | 0.75%   |
| AMD Phenom II X6        | 1        | 0.75%   |
| AMD Phenom II X2        | 1        | 0.75%   |
| AMD Phenom              | 1        | 0.75%   |
| AMD E                   | 1        | 0.75%   |
| AMD Athlon 64           | 1        | 0.75%   |
| AMD Athlon              | 1        | 0.75%   |
| AMD A6                  | 1        | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 59       | 44.03%  |
| 2      | 39       | 29.1%   |
| 6      | 15       | 11.19%  |
| 8      | 8        | 5.97%   |
| 1      | 4        | 2.99%   |
| 12     | 3        | 2.24%   |
| 3      | 3        | 2.24%   |
| 24     | 1        | 0.75%   |
| 16     | 1        | 0.75%   |
| 10     | 1        | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 130      | 99.24%  |
| 2      | 1        | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 66       | 50%     |
| 1      | 66       | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 129      | 98.47%  |
| Unknown        | 2        | 1.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 17.65%  |
| 0x306c3    | 19       | 13.97%  |
| 0x206a7    | 11       | 8.09%   |
| 0x1067a    | 7        | 5.15%   |
| 0xa0653    | 5        | 3.68%   |
| 0x906ea    | 5        | 3.68%   |
| 0x0800820d | 5        | 3.68%   |
| 0x010000db | 4        | 2.94%   |
| 0x010000c8 | 4        | 2.94%   |
| 0xa0671    | 3        | 2.21%   |
| 0x6fd      | 3        | 2.21%   |
| 0x306a9    | 3        | 2.21%   |
| 0x06001119 | 3        | 2.21%   |
| 0xf43      | 2        | 1.47%   |
| 0xa0655    | 2        | 1.47%   |
| 0x906ed    | 2        | 1.47%   |
| 0x906eb    | 2        | 1.47%   |
| 0x906e9    | 2        | 1.47%   |
| 0x6fb      | 2        | 1.47%   |
| 0x506e3    | 2        | 1.47%   |
| 0x306f2    | 2        | 1.47%   |
| 0x0810100b | 2        | 1.47%   |
| 0x08001137 | 2        | 1.47%   |
| 0x06000852 | 2        | 1.47%   |
| 0x0600063e | 2        | 1.47%   |
| 0x6f6      | 1        | 0.74%   |
| 0x20655    | 1        | 0.74%   |
| 0x106a4    | 1        | 0.74%   |
| 0x0a201009 | 1        | 0.74%   |
| 0x0a201005 | 1        | 0.74%   |
| 0x08701021 | 1        | 0.74%   |
| 0x08701013 | 1        | 0.74%   |
| 0x08600106 | 1        | 0.74%   |
| 0x08600103 | 1        | 0.74%   |
| 0x08108109 | 1        | 0.74%   |
| 0x08108102 | 1        | 0.74%   |
| 0x08001138 | 1        | 0.74%   |
| 0x08001129 | 1        | 0.74%   |
| 0x05000029 | 1        | 0.74%   |
| 0x010000dc | 1        | 0.74%   |
| 0x00000000 | 1        | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 24       | 18.32%  |
| SandyBridge | 12       | 9.16%   |
| KabyLake    | 10       | 7.63%   |
| Zen+        | 9        | 6.87%   |
| K10         | 9        | 6.87%   |
| Zen         | 8        | 6.11%   |
| Piledriver  | 8        | 6.11%   |
| CometLake   | 8        | 6.11%   |
| Penryn      | 7        | 5.34%   |
| Core        | 7        | 5.34%   |
| Zen 2       | 4        | 3.05%   |
| K8 Hammer   | 4        | 3.05%   |
| IvyBridge   | 4        | 3.05%   |
| Skylake     | 3        | 2.29%   |
| Zen 3       | 2        | 1.53%   |
| Westmere    | 2        | 1.53%   |
| NetBurst    | 2        | 1.53%   |
| Icelake     | 2        | 1.53%   |
| Bulldozer   | 2        | 1.53%   |
| Nehalem     | 1        | 0.76%   |
| Excavator   | 1        | 0.76%   |
| Bobcat      | 1        | 0.76%   |
| Unknown     | 1        | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 54       | 37.76%  |
| AMD              | 52       | 36.36%  |
| Intel            | 36       | 25.17%  |
| ATI Technologies | 1        | 0.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 6.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 5.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 4.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 3.45%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 2.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.76%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 2.07%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.07%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.07%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 3        | 2.07%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 2.07%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.38%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.38%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.38%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 1.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.38%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.38%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.38%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.38%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.38%   |
| AMD Renoir                                                                  | 2        | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.38%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 1.38%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.38%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 1.38%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.38%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.69%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.69%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.69%   |
| Nvidia GM206 [GeForce GTX 750 v2]                                           | 1        | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.69%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1        | 0.69%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.69%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.69%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.69%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.69%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.69%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 0.69%   |
| Nvidia GF106 [GeForce GT 440]                                               | 1        | 0.69%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1        | 0.69%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 0.69%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 0.69%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 1        | 0.69%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 0.69%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 0.69%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 0.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 0.69%   |
| Intel HD Graphics 610                                                       | 1        | 0.69%   |
| Intel HD Graphics 530                                                       | 1        | 0.69%   |
| Intel HD Graphics 510                                                       | 1        | 0.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 0.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 0.69%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 0.69%   |
| ATI Technologies Wani [Radeon R5/R6/R7 Graphics]                            | 1        | 0.69%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 50       | 37.31%  |
| 1 x AMD        | 48       | 35.82%  |
| 1 x Intel      | 29       | 21.64%  |
| Intel + Nvidia | 3        | 2.24%   |
| 2 x AMD        | 2        | 1.49%   |
| Intel + AMD    | 1        | 0.75%   |
| AMD + Nvidia   | 1        | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 94       | 69.63%  |
| Proprietary | 39       | 28.89%  |
| Unknown     | 2        | 1.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 35.29%  |
| 1.01-2.0   | 27       | 19.85%  |
| 0.51-1.0   | 27       | 19.85%  |
| 3.01-4.0   | 11       | 8.09%   |
| 7.01-8.0   | 9        | 6.62%   |
| 0.01-0.5   | 8        | 5.88%   |
| 5.01-6.0   | 2        | 1.47%   |
| 2.01-3.0   | 2        | 1.47%   |
| 8.01-16.0  | 2        | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 30       | 20.98%  |
| AOC                  | 19       | 13.29%  |
| Dell                 | 18       | 12.59%  |
| Philips              | 16       | 11.19%  |
| Acer                 | 13       | 9.09%   |
| Goldstar             | 12       | 8.39%   |
| Ancor Communications | 8        | 5.59%   |
| Hewlett-Packard      | 5        | 3.5%    |
| LG Electronics       | 3        | 2.1%    |
| Unknown              | 2        | 1.4%    |
| Huion                | 2        | 1.4%    |
| Fujitsu Siemens      | 2        | 1.4%    |
| BenQ                 | 2        | 1.4%    |
| Vestel Elektronik    | 1        | 0.7%    |
| RTK                  | 1        | 0.7%    |
| Panasonic            | 1        | 0.7%    |
| NOA VISION           | 1        | 0.7%    |
| NEC Computers        | 1        | 0.7%    |
| LG Display           | 1        | 0.7%    |
| Lenovo               | 1        | 0.7%    |
| KTC                  | 1        | 0.7%    |
| InnoLux Display      | 1        | 0.7%    |
| Grundig              | 1        | 0.7%    |
| ASUSTek Computer     | 1        | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0509 1920x1080                       | 2        | 1.3%    |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                      | 2        | 1.3%    |
| Huion GT221 HAT2150 1920x1080 476x267mm 21.5-inch                       | 2        | 1.3%    |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                     | 2        | 1.3%    |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                       | 2        | 1.3%    |
| Dell LCD Monitor SE2416H 5760x1080                                      | 2        | 1.3%    |
| Dell LCD Monitor SE2416H                                                | 2        | 1.3%    |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                       | 2        | 1.3%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                     | 2        | 1.3%    |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                         | 2        | 1.3%    |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                          | 2        | 1.3%    |
| AOC 22B1W AOC2201 1920x1080 476x268mm 21.5-inch                         | 2        | 1.3%    |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                       | 2        | 1.3%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1        | 0.65%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.65%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                             | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0608 1920x1080 510x290mm 23.1-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM05C6 1920x1080 520x290mm 23.4-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch     | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch     | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch     | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch     | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM01E7 1920x1200 518x324mm 24.1-inch    | 1        | 0.65%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch    | 1        | 0.65%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch       | 1        | 0.65%   |
| Samsung Electronics SMB1940 SAM06BA 1280x1024 376x301mm 19.0-inch       | 1        | 0.65%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.65%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch       | 1        | 0.65%   |
| Samsung Electronics LS24A600U SAM7160 2560x1440 527x297mm 23.8-inch     | 1        | 0.65%   |
| Samsung Electronics LF27T450F SAM7097 1920x1080 600x340mm 27.2-inch     | 1        | 0.65%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 480x270mm 21.7-inch       | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                    | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                    | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0FB9 3840x2160 1872x1053mm 84.6-inch | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch    | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch  | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                        | 1        | 0.65%   |
| Samsung Electronics LCD Monitor S24F350 3840x1080                       | 1        | 0.65%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch      | 1        | 0.65%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1        | 0.65%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                  | 1        | 0.65%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 0.65%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                 | 1        | 0.65%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 0.65%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 0.65%   |
| Philips PHL 242E2F PHLC238 1920x1080 530x300mm 24.0-inch                | 1        | 0.65%   |
| Philips LCD Monitor PHL0850 1680x1050 470x300mm 22.0-inch               | 1        | 0.65%   |
| Philips LCD Monitor PHL 272B8Q 2560x1440                                | 1        | 0.65%   |
| Philips LCD Monitor PHL 243V5 1920x1080                                 | 1        | 0.65%   |
| Philips LCD Monitor FTV                                                 | 1        | 0.65%   |
| Philips LCD Monitor 231T                                                | 1        | 0.65%   |
| Philips LCD Monitor 170S 1280x1024                                      | 1        | 0.65%   |
| Philips 235PL PHL089B 1920x1080 510x287mm 23.0-inch                     | 1        | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 65       | 45.77%  |
| 2560x1440 (QHD)    | 11       | 7.75%   |
| 1680x1050 (WSXGA+) | 11       | 7.75%   |
| 1280x1024 (SXGA)   | 9        | 6.34%   |
| Unknown            | 8        | 5.63%   |
| 3840x2160 (4K)     | 6        | 4.23%   |
| 1920x1200 (WUXGA)  | 6        | 4.23%   |
| 1600x900 (HD+)     | 5        | 3.52%   |
| 3840x1080          | 4        | 2.82%   |
| 1360x768           | 4        | 2.82%   |
| 1440x900 (WXGA+)   | 3        | 2.11%   |
| 5760x1080          | 2        | 1.41%   |
| 2560x1080          | 2        | 1.41%   |
| 2048x1152          | 2        | 1.41%   |
| 1366x768 (WXGA)    | 2        | 1.41%   |
| 4480x1440          | 1        | 0.7%    |
| 2560x1600          | 1        | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 26       | 18.44%  |
| Unknown | 19       | 13.48%  |
| 21      | 18       | 12.77%  |
| 24      | 17       | 12.06%  |
| 27      | 15       | 10.64%  |
| 22      | 9        | 6.38%   |
| 19      | 8        | 5.67%   |
| 20      | 6        | 4.26%   |
| 31      | 4        | 2.84%   |
| 17      | 4        | 2.84%   |
| 18      | 3        | 2.13%   |
| 84      | 2        | 1.42%   |
| 33      | 2        | 1.42%   |
| 25      | 2        | 1.42%   |
| 60      | 1        | 0.71%   |
| 54      | 1        | 0.71%   |
| 46      | 1        | 0.71%   |
| 34      | 1        | 0.71%   |
| 32      | 1        | 0.71%   |
| 26      | 1        | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 56       | 41.18%  |
| 401-500     | 37       | 27.21%  |
| Unknown     | 19       | 13.97%  |
| 601-700     | 6        | 4.41%   |
| 351-400     | 6        | 4.41%   |
| 701-800     | 4        | 2.94%   |
| 301-350     | 3        | 2.21%   |
| 1001-1500   | 3        | 2.21%   |
| 1501-2000   | 2        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 84       | 63.64%  |
| 16/10   | 21       | 15.91%  |
| Unknown | 17       | 12.88%  |
| 5/4     | 8        | 6.06%   |
| 3/2     | 1        | 0.76%   |
| 21/9    | 1        | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 51       | 36.96%  |
| 151-200        | 23       | 16.67%  |
| Unknown        | 19       | 13.77%  |
| 301-350        | 16       | 11.59%  |
| 251-300        | 9        | 6.52%   |
| 351-500        | 8        | 5.8%    |
| 141-150        | 6        | 4.35%   |
| More than 1000 | 4        | 2.9%    |
| 121-130        | 1        | 0.72%   |
| 501-1000       | 1        | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 80       | 61.07%  |
| 101-120 | 25       | 19.08%  |
| Unknown | 19       | 14.5%   |
| 1-50    | 4        | 3.05%   |
| 121-160 | 2        | 1.53%   |
| 161-240 | 1        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 101      | 75.94%  |
| 2     | 25       | 18.8%   |
| 0     | 5        | 3.76%   |
| 4     | 1        | 0.75%   |
| 3     | 1        | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 85       | 45.7%   |
| Intel                             | 37       | 19.89%  |
| Qualcomm Atheros                  | 10       | 5.38%   |
| TP-Link                           | 6        | 3.23%   |
| Ralink                            | 5        | 2.69%   |
| Qualcomm Atheros Communications   | 5        | 2.69%   |
| Broadcom                          | 5        | 2.69%   |
| Ralink Technology                 | 4        | 2.15%   |
| Nvidia                            | 4        | 2.15%   |
| Sundance Technology Inc / IC Plus | 2        | 1.08%   |
| Samsung Electronics               | 2        | 1.08%   |
| Realtek                           | 2        | 1.08%   |
| MediaTek                          | 2        | 1.08%   |
| Marvell Technology Group          | 2        | 1.08%   |
| D-Link                            | 2        | 1.08%   |
| Xiaomi                            | 1        | 0.54%   |
| VIA Technologies                  | 1        | 0.54%   |
| T & A Mobile Phones               | 1        | 0.54%   |
| Nokia Mobile Phones               | 1        | 0.54%   |
| Microsoft                         | 1        | 0.54%   |
| Linksys                           | 1        | 0.54%   |
| Huawei Technologies               | 1        | 0.54%   |
| Edimax Technology                 | 1        | 0.54%   |
| D-Link System                     | 1        | 0.54%   |
| Broadcom Limited                  | 1        | 0.54%   |
| ASUSTek Computer                  | 1        | 0.54%   |
| ASIX Electronics                  | 1        | 0.54%   |
| Aquantia                          | 1        | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 72       | 36.92%  |
| Qualcomm Atheros AR9271 802.11n                                            | 5        | 2.56%   |
| TP-Link TL-WN722N v2                                                       | 4        | 2.05%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.05%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.05%   |
| Intel Ethernet Connection (2) I218-V                                       | 4        | 2.05%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.54%   |
| Ralink MT7601U Wireless Adapter                                            | 3        | 1.54%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 1.54%   |
| Intel Ethernet Connection I217-V                                           | 3        | 1.54%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 1.03%   |
| Realtek 802.11ac NIC                                                       | 2        | 1.03%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 2        | 1.03%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 2        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.03%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                 | 2        | 1.03%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 1.03%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.03%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.03%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 1.03%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 1.03%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 2        | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.51%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 1        | 0.51%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 0.51%   |
| T & A Mobile Phones 9010X                                                  | 1        | 0.51%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.51%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.51%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                    | 1        | 0.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.51%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1        | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.51%   |
| Ralink RT5370 Wireless Adapter                                             | 1        | 0.51%   |
| Ralink RT2561/RT61 rev B 802.11g                                           | 1        | 0.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.51%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.51%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.51%   |
| Nokia Mobile Phones Nokia X2-00                                            | 1        | 0.51%   |
| Microsoft Xbox 360 Wireless Adapter                                        | 1        | 0.51%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                        | 1        | 0.51%   |
| MediaTek moto e6s                                                          | 1        | 0.51%   |
| Linksys WUSB6400M                                                          | 1        | 0.51%   |
| Intel Wireless 8265 / 8275                                                 | 1        | 0.51%   |
| Intel Wireless 3165                                                        | 1        | 0.51%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 7        | 14.29%  |
| TP-Link                         | 6        | 12.24%  |
| Ralink                          | 5        | 10.2%   |
| Qualcomm Atheros Communications | 5        | 10.2%   |
| Intel                           | 5        | 10.2%   |
| Ralink Technology               | 4        | 8.16%   |
| Qualcomm Atheros                | 4        | 8.16%   |
| Broadcom                        | 4        | 8.16%   |
| Realtek                         | 2        | 4.08%   |
| D-Link                          | 2        | 4.08%   |
| Microsoft                       | 1        | 2.04%   |
| MediaTek                        | 1        | 2.04%   |
| Linksys                         | 1        | 2.04%   |
| Edimax Technology               | 1        | 2.04%   |
| ASUSTek Computer                | 1        | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                         | 5        | 10.2%   |
| TP-Link TL-WN722N v2                                                    | 4        | 8.16%   |
| Ralink MT7601U Wireless Adapter                                         | 3        | 6.12%   |
| Intel Wi-Fi 6 AX200                                                     | 3        | 6.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 4.08%   |
| Realtek 802.11ac NIC                                                    | 2        | 4.08%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 2        | 4.08%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 2        | 4.08%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2        | 4.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2        | 4.08%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 2.04%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1        | 2.04%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 2.04%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.04%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                  | 1        | 2.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1        | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1        | 2.04%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 2.04%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1        | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 2.04%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 2.04%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1        | 2.04%   |
| Linksys WUSB6400M                                                       | 1        | 2.04%   |
| Intel Wireless 8265 / 8275                                              | 1        | 2.04%   |
| Intel Wireless 3165                                                     | 1        | 2.04%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                | 1        | 2.04%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 2.04%   |
| D-Link 11ac adapter                                                     | 1        | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 2.04%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1        | 2.04%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]         | 1        | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 81       | 57.04%  |
| Intel                             | 35       | 24.65%  |
| Qualcomm Atheros                  | 6        | 4.23%   |
| Nvidia                            | 4        | 2.82%   |
| Sundance Technology Inc / IC Plus | 2        | 1.41%   |
| Samsung Electronics               | 2        | 1.41%   |
| Marvell Technology Group          | 2        | 1.41%   |
| Xiaomi                            | 1        | 0.7%    |
| VIA Technologies                  | 1        | 0.7%    |
| T & A Mobile Phones               | 1        | 0.7%    |
| MediaTek                          | 1        | 0.7%    |
| Huawei Technologies               | 1        | 0.7%    |
| D-Link System                     | 1        | 0.7%    |
| Broadcom Limited                  | 1        | 0.7%    |
| Broadcom                          | 1        | 0.7%    |
| ASIX Electronics                  | 1        | 0.7%    |
| Aquantia                          | 1        | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 72       | 49.66%  |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.76%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.76%   |
| Intel Ethernet Connection (2) I218-V                                       | 4        | 2.76%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3        | 2.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 2.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2.07%   |
| Intel Ethernet Connection I217-V                                           | 3        | 2.07%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 2.07%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.38%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 1.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.38%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.38%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 1.38%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 1.38%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.69%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.69%   |
| T & A Mobile Phones 9010X                                                  | 1        | 0.69%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.69%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.69%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.69%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.69%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.69%   |
| MediaTek moto e6s                                                          | 1        | 0.69%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.69%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.69%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.69%   |
| Intel Ethernet Connection (11) I219-LM                                     | 1        | 0.69%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 1        | 0.69%   |
| Intel 82567LM-2 Gigabit Network Connection                                 | 1        | 0.69%   |
| Huawei JNY-LX1                                                             | 1        | 0.69%   |
| D-Link System RTL8139 Ethernet                                             | 1        | 0.69%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 1        | 0.69%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express            | 1        | 0.69%   |
| ASIX AX88772A Fast Ethernet                                                | 1        | 0.69%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]          | 1        | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 128      | 72.73%  |
| WiFi     | 47       | 26.7%   |
| Modem    | 1        | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 96       | 73.85%  |
| WiFi     | 34       | 26.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 98       | 74.24%  |
| 2     | 29       | 21.97%  |
| 0     | 3        | 2.27%   |
| 4     | 1        | 0.76%   |
| 3     | 1        | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 128      | 97.71%  |
| Yes  | 3        | 2.29%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 6        | 27.27%  |
| Intel                           | 5        | 22.73%  |
| Broadcom                        | 4        | 18.18%  |
| Realtek Semiconductor           | 2        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 4.55%   |
| Integrated System Solution      | 1        | 4.55%   |
| IMC Networks                    | 1        | 4.55%   |
| Foxconn / Hon Hai               | 1        | 4.55%   |
| ASUSTek Computer                | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 6        | 27.27%  |
| Intel AX200 Bluetooth                                 | 3        | 13.64%  |
| Realtek Bluetooth Radio                               | 2        | 9.09%   |
| Intel Bluetooth wireless interface                    | 2        | 9.09%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 9.09%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 4.55%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 4.55%   |
| IMC Networks BCM20702A0                               | 1        | 4.55%   |
| Foxconn / Hon Hai BT                                  | 1        | 4.55%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 4.55%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 4.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 82       | 35.34%  |
| AMD                 | 69       | 29.74%  |
| Nvidia              | 52       | 22.41%  |
| C-Media Electronics | 8        | 3.45%   |
| Logitech            | 3        | 1.29%   |
| Creative Labs       | 3        | 1.29%   |
| Microsoft           | 2        | 0.86%   |
| Yamaha              | 1        | 0.43%   |
| XMOS                | 1        | 0.43%   |
| VIA Technologies    | 1        | 0.43%   |
| Trust               | 1        | 0.43%   |
| Tenx Technology     | 1        | 0.43%   |
| Razer USA           | 1        | 0.43%   |
| Native Instruments  | 1        | 0.43%   |
| JMTek               | 1        | 0.43%   |
| Focusrite-Novation  | 1        | 0.43%   |
| Ensoniq             | 1        | 0.43%   |
| Cirrus Logic        | 1        | 0.43%   |
| ATI Technologies    | 1        | 0.43%   |
| Astro Gaming        | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 5.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 4.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 4.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 3.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 2.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 2.97%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 2.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 2.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 2.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 2.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 2.23%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 6        | 2.23%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.86%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 1.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 1.86%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.86%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 1.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4        | 1.49%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 1.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.12%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.12%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 3        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.12%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.74%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.74%   |
| Microsoft LifeChat LX-3000 Headset                                         | 2        | 0.74%   |
| Logitech EasyCall Speakerphone                                             | 2        | 0.74%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 0.74%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 2        | 0.74%   |
| C-Media Electronics Audio Adapter                                          | 2        | 0.74%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2        | 0.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 0.74%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 2        | 0.74%   |
| Yamaha Steinberg UR12                                                      | 1        | 0.37%   |
| XMOS Soekris dac1xxx USB Audio 2.0                                         | 1        | 0.37%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.37%   |
| Trust GXT 232 Microphone                                                   | 1        | 0.37%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.37%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.37%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.37%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1        | 0.37%   |
| Nvidia MCP55 High Definition Audio                                         | 1        | 0.37%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.37%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.37%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 22       | 30.14%  |
| Unknown             | 9        | 12.33%  |
| Corsair             | 9        | 12.33%  |
| G.Skill             | 7        | 9.59%   |
| SK hynix            | 6        | 8.22%   |
| Samsung Electronics | 6        | 8.22%   |
| Transcend           | 3        | 4.11%   |
| Crucial             | 3        | 4.11%   |
| Patriot             | 2        | 2.74%   |
| Kingmax             | 2        | 2.74%   |
| Mushkin             | 1        | 1.37%   |
| Elpida              | 1        | 1.37%   |
| Apacer              | 1        | 1.37%   |
| A-DATA Technology   | 1        | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 667MT/s                   | 2        | 2.5%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 2.5%    |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s      | 2        | 2.5%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 2        | 2.5%    |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s     | 2        | 2.5%    |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s               | 1        | 1.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.25%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 1.25%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.25%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 1.25%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                     | 1        | 1.25%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 1.25%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                  | 1        | 1.25%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                 | 1        | 1.25%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s               | 1        | 1.25%   |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s    | 1        | 1.25%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s     | 1        | 1.25%   |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s        | 1        | 1.25%   |
| Transcend RAM JM1333KLN-2G 2048MB DIMM DDR3 1333MT/s     | 1        | 1.25%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 1.25%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.25%   |
| SK hynix RAM HMT125U6BFR8C-H9 2GB DIMM 1333MT/s          | 1        | 1.25%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s    | 1        | 1.25%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s     | 1        | 1.25%   |
| Samsung RAM M471B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s   | 1        | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 1.25%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s | 1        | 1.25%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s      | 1        | 1.25%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.25%   |
| Patriot RAM PSD22G80026 2048MB DIMM DDR2 800MT/s         | 1        | 1.25%   |
| Mushkin RAM 99[2/7/4]199[F/T] 8192MB DIMM DDR4 2400MT/s  | 1        | 1.25%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s      | 1        | 1.25%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 1.25%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s     | 1        | 1.25%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 1        | 1.25%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s     | 1        | 1.25%   |
| Kingston RAM KHX2133C13D4/8GX 8192MB DIMM DDR4 2133MT/s  | 1        | 1.25%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 1        | 1.25%   |
| Kingston RAM KHX1866C10D3/4G 4096MB DIMM DDR3 1867MT/s   | 1        | 1.25%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 1        | 1.25%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 1        | 1.25%   |
| Kingston RAM KF2666C16D4/8G 8192MB DIMM DDR4 2667MT/s    | 1        | 1.25%   |
| Kingston RAM KF2666C16D4/16G 16GB DIMM DDR4 2666MT/s     | 1        | 1.25%   |
| Kingston RAM 99U5584-016.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.25%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.25%   |
| Kingston RAM 99U5474-037.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.25%   |
| Kingston RAM 9905711-039.A00G 8GB SODIMM DDR4 3200MT/s   | 1        | 1.25%   |
| Kingston RAM 9905702-203.A00G 8GB DIMM DDR4 2400MT/s     | 1        | 1.25%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s     | 1        | 1.25%   |
| Kingston RAM 9905595-011.A00LF 2048MB DIMM DDR3 1333MT/s | 1        | 1.25%   |
| Kingston RAM 9905471-084.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 1.25%   |
| Kingmax RAM KLDD48F-A8KB5 1024MB DIMM DDR2 800MT/s       | 1        | 1.25%   |
| Kingmax RAM FLGG45F-D8 8192MB DIMM DDR3 1067MT/s         | 1        | 1.25%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s      | 1        | 1.25%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 1        | 1.25%   |
| G.Skill RAM F4-3200C15-16GTZR 16384MB DIMM DDR4 3200MT/s | 1        | 1.25%   |
| G.Skill RAM F3-1600C11-4GNS 4096MB DIMM DDR3 1600MT/s    | 1        | 1.25%   |
| G.Skill RAM F3-12800CL9-2GBNQ 2GB DIMM 1333MT/s          | 1        | 1.25%   |
| G.Skill RAM F3-10666CL9-2GBNS 2048MB DIMM DDR3 1333MT/s  | 1        | 1.25%   |
| G.Skill RAM F3-10600CL9-2GBNT 2048MB DIMM DDR3 1333MT/s  | 1        | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 30       | 48.39%  |
| DDR3    | 22       | 35.48%  |
| Unknown | 4        | 6.45%   |
| DDR2    | 3        | 4.84%   |
| SDRAM   | 2        | 3.23%   |
| DDR     | 1        | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 58       | 95.08%  |
| SODIMM | 3        | 4.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 40.3%   |
| 4096  | 18       | 26.87%  |
| 2048  | 10       | 14.93%  |
| 16384 | 8        | 11.94%  |
| 1024  | 3        | 4.48%   |
| 512   | 1        | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 13       | 20%     |
| 3200  | 8        | 12.31%  |
| 1333  | 7        | 10.77%  |
| 2667  | 6        | 9.23%   |
| 2400  | 5        | 7.69%   |
| 2133  | 3        | 4.62%   |
| 3600  | 2        | 3.08%   |
| 3466  | 2        | 3.08%   |
| 3400  | 2        | 3.08%   |
| 2933  | 2        | 3.08%   |
| 2666  | 2        | 3.08%   |
| 1800  | 2        | 3.08%   |
| 800   | 2        | 3.08%   |
| 667   | 2        | 3.08%   |
| 4000  | 1        | 1.54%   |
| 3334  | 1        | 1.54%   |
| 3333  | 1        | 1.54%   |
| 1867  | 1        | 1.54%   |
| 1067  | 1        | 1.54%   |
| 533   | 1        | 1.54%   |
| 400   | 1        | 1.54%   |

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
| Logitech                      | 11       | 42.31%  |
| Sunplus Innovation Technology | 4        | 15.38%  |
| Realtek Semiconductor         | 3        | 11.54%  |
| Microdia                      | 3        | 11.54%  |
| Chicony Electronics           | 2        | 7.69%   |
| Trust                         | 1        | 3.85%   |
| GenesysLogic Technology       | 1        | 3.85%   |
| Alcor Micro                   | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 15.38%  |
| Sunplus HD 720P webcam                | 3        | 11.54%  |
| Microdia Camera                       | 2        | 7.69%   |
| Logitech Webcam C170                  | 2        | 7.69%   |
| Trust Full HD Webcam                  | 1        | 3.85%   |
| Sunplus Full HD webcam                | 1        | 3.85%   |
| Realtek Streaming Webcam              | 1        | 3.85%   |
| Realtek FULL HD 1080P Webcam          | 1        | 3.85%   |
| Realtek Asus laptop camera            | 1        | 3.85%   |
| Microdia Sonix USB 2.0 Camera         | 1        | 3.85%   |
| Logitech Webcam C925e                 | 1        | 3.85%   |
| Logitech Webcam C250                  | 1        | 3.85%   |
| Logitech Webcam C210                  | 1        | 3.85%   |
| Logitech Webcam C110                  | 1        | 3.85%   |
| Logitech HD Pro Webcam C920           | 1        | 3.85%   |
| GenesysLogic USB2.0 UVC PC Camera     | 1        | 3.85%   |
| Chicony HP High Definition Webcam     | 1        | 3.85%   |
| Chicony HP High Definition 1MP Webcam | 1        | 3.85%   |
| Alcor Micro USB 2.0 Camera            | 1        | 3.85%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 120      | 89.55%  |
| 1     | 12       | 8.96%   |
| 2     | 2        | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Graphics card      | 5        | 31.25%  |
| Net/wireless       | 3        | 18.75%  |
| Bluetooth          | 3        | 18.75%  |
| Unassigned class   | 2        | 12.5%   |
| Storage/raid       | 1        | 6.25%   |
| Fingerprint reader | 1        | 6.25%   |
| Chipcard           | 1        | 6.25%   |


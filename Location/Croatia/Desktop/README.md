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

Total: 195

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Lenovo        | 0x30F617AA NOK           | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| ASRock        | A320M-DVS R4.0           | [0dca3e500c](https://linux-hardware.org/?probe=0dca3e500c) | Sep 22, 2022 |
| ASUSTek       | Z97-PRO                  | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
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
| Ubuntu 20.04                 | 20       | 13.99%  |
| Ubuntu 18.04                 | 14       | 9.79%   |
| Linux Mint 20.2              | 6        | 4.2%    |
| Debian 11                    | 6        | 4.2%    |
| Ubuntu 18.10                 | 5        | 3.5%    |
| OpenMandriva 4.3             | 5        | 3.5%    |
| Linux Mint 20.3              | 5        | 3.5%    |
| Zorin 16                     | 4        | 2.8%    |
| Debian 10                    | 4        | 2.8%    |
| Ubuntu 19.10                 | 3        | 2.1%    |
| Pop!_OS 21.10                | 3        | 2.1%    |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 2.1%    |
| OpenMandriva 4.2             | 3        | 2.1%    |
| Manjaro                      | 3        | 2.1%    |
| Fedora 31                    | 3        | 2.1%    |
| Xubuntu 20.04                | 2        | 1.4%    |
| Ubuntu 22.04                 | 2        | 1.4%    |
| Ubuntu 21.04                 | 2        | 1.4%    |
| Pop!_OS 20.10                | 2        | 1.4%    |
| openSUSE Leap-15.2           | 2        | 1.4%    |
| OpenMandriva 4.50            | 2        | 1.4%    |
| Linux Mint 20                | 2        | 1.4%    |
| KDE neon 20.04               | 2        | 1.4%    |
| ArcoLinux Rolling            | 2        | 1.4%    |
| Zorin 15                     | 1        | 0.7%    |
| Xubuntu 18.04                | 1        | 0.7%    |
| Ubuntu Unity 18.04           | 1        | 0.7%    |
| Ubuntu MATE 22.04            | 1        | 0.7%    |
| Ubuntu MATE 20.04            | 1        | 0.7%    |
| Ubuntu MATE 19.10            | 1        | 0.7%    |
| Ubuntu Budgie 22.04          | 1        | 0.7%    |
| Ubuntu Budgie 20.04          | 1        | 0.7%    |
| Ubuntu Budgie 18.04          | 1        | 0.7%    |
| Ubuntu 21.10                 | 1        | 0.7%    |
| Ubuntu 20.10                 | 1        | 0.7%    |
| Ubuntu 17.10                 | 1        | 0.7%    |
| Ubuntu                       | 1        | 0.7%    |
| ROSA R11                     | 1        | 0.7%    |
| Pop!_OS 21.04                | 1        | 0.7%    |
| Pop!_OS 20.04                | 1        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 49       | 36.3%   |
| Linux Mint    | 15       | 11.11%  |
| OpenMandriva  | 11       | 8.15%   |
| Pop!_OS       | 8        | 5.93%   |
| Debian        | 8        | 5.93%   |
| Manjaro       | 7        | 5.19%   |
| Zorin         | 5        | 3.7%    |
| openSUSE      | 5        | 3.7%    |
| Fedora        | 4        | 2.96%   |
| Xubuntu       | 3        | 2.22%   |
| Ubuntu Budgie | 3        | 2.22%   |
| Ubuntu MATE   | 2        | 1.48%   |
| KDE neon      | 2        | 1.48%   |
| ArcoLinux     | 2        | 1.48%   |
| Arch          | 2        | 1.48%   |
| Ubuntu Unity  | 1        | 0.74%   |
| ROSA          | 1        | 0.74%   |
| Lubuntu       | 1        | 0.74%   |
| LMDE          | 1        | 0.74%   |
| LinuxFX       | 1        | 0.74%   |
| Kubuntu       | 1        | 0.74%   |
| Endless       | 1        | 0.74%   |
| Elementary    | 1        | 0.74%   |
| Clear Linux   | 1        | 0.74%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 5        | 3.21%   |
| 5.4.0-58-generic         | 4        | 2.56%   |
| 5.4.0-91-generic         | 3        | 1.92%   |
| 5.3.0-26-generic         | 3        | 1.92%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.92%   |
| 5.0.0-27-generic         | 3        | 1.92%   |
| 5.8.0-48-generic         | 2        | 1.28%   |
| 5.4.0-48-generic         | 2        | 1.28%   |
| 5.4.0-42-generic         | 2        | 1.28%   |
| 5.4.0-26-generic         | 2        | 1.28%   |
| 5.4.0-100-generic        | 2        | 1.28%   |
| 5.3.0-42-generic         | 2        | 1.28%   |
| 5.3.0-28-generic         | 2        | 1.28%   |
| 5.13.0-40-generic        | 2        | 1.28%   |
| 5.12.4-desktop-1omv4050  | 2        | 1.28%   |
| 5.11.0-41-generic        | 2        | 1.28%   |
| 5.11.0-38-generic        | 2        | 1.28%   |
| 5.11.0-37-generic        | 2        | 1.28%   |
| 5.10.0-13-amd64          | 2        | 1.28%   |
| 4.19.0-14-amd64          | 2        | 1.28%   |
| 4.18.0-10-generic        | 2        | 1.28%   |
| 4.15.0-45-generic        | 2        | 1.28%   |
| 4.15.0-20-generic        | 2        | 1.28%   |
| 5.9.0-0.bpo.5-amd64      | 1        | 0.64%   |
| 5.8.0-59-generic         | 1        | 0.64%   |
| 5.8.0-41-generic         | 1        | 0.64%   |
| 5.8.0-40-generic         | 1        | 0.64%   |
| 5.8.0-34-generic         | 1        | 0.64%   |
| 5.7.11-100.fc31.x86_64   | 1        | 0.64%   |
| 5.7.0-0.bpo.2-amd64      | 1        | 0.64%   |
| 5.6.12-300.fc32.x86_64   | 1        | 0.64%   |
| 5.4.64-1-MANJARO         | 1        | 0.64%   |
| 5.4.20-200.fc31.x86_64   | 1        | 0.64%   |
| 5.4.2-300.fc31.x86_64    | 1        | 0.64%   |
| 5.4.18-902.native        | 1        | 0.64%   |
| 5.4.0-97-generic         | 1        | 0.64%   |
| 5.4.0-92-generic         | 1        | 0.64%   |
| 5.4.0-90-generic         | 1        | 0.64%   |
| 5.4.0-89-generic         | 1        | 0.64%   |
| 5.4.0-7626-generic       | 1        | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 22.3%   |
| 5.11.0  | 12       | 8.11%   |
| 5.3.0   | 11       | 7.43%   |
| 4.15.0  | 10       | 6.76%   |
| 4.18.0  | 8        | 5.41%   |
| 5.13.0  | 7        | 4.73%   |
| 5.10.0  | 6        | 4.05%   |
| 5.8.0   | 5        | 3.38%   |
| 5.16.7  | 5        | 3.38%   |
| 5.15.0  | 4        | 2.7%    |
| 5.0.0   | 4        | 2.7%    |
| 5.12.4  | 3        | 2.03%   |
| 5.10.14 | 3        | 2.03%   |
| 4.19.0  | 3        | 2.03%   |
| 5.3.18  | 2        | 1.35%   |
| 5.16.11 | 2        | 1.35%   |
| 5.9.0   | 1        | 0.68%   |
| 5.7.11  | 1        | 0.68%   |
| 5.7.0   | 1        | 0.68%   |
| 5.6.12  | 1        | 0.68%   |
| 5.4.64  | 1        | 0.68%   |
| 5.4.20  | 1        | 0.68%   |
| 5.4.2   | 1        | 0.68%   |
| 5.4.18  | 1        | 0.68%   |
| 5.3.16  | 1        | 0.68%   |
| 5.19.2  | 1        | 0.68%   |
| 5.18.4  | 1        | 0.68%   |
| 5.18.14 | 1        | 0.68%   |
| 5.18.12 | 1        | 0.68%   |
| 5.17.4  | 1        | 0.68%   |
| 5.17.3  | 1        | 0.68%   |
| 5.16.18 | 1        | 0.68%   |
| 5.16.15 | 1        | 0.68%   |
| 5.15.8  | 1        | 0.68%   |
| 5.15.53 | 1        | 0.68%   |
| 5.15.32 | 1        | 0.68%   |
| 5.15.15 | 1        | 0.68%   |
| 5.14.7  | 1        | 0.68%   |
| 5.14.11 | 1        | 0.68%   |
| 5.11.20 | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 25.34%  |
| 5.3     | 14       | 9.59%   |
| 5.11    | 13       | 8.9%    |
| 5.10    | 13       | 8.9%    |
| 4.15    | 10       | 6.85%   |
| 5.15    | 8        | 5.48%   |
| 4.18    | 8        | 5.48%   |
| 5.16    | 7        | 4.79%   |
| 5.13    | 7        | 4.79%   |
| 5.8     | 5        | 3.42%   |
| 5.0     | 4        | 2.74%   |
| 5.18    | 3        | 2.05%   |
| 5.12    | 3        | 2.05%   |
| 4.19    | 3        | 2.05%   |
| 5.7     | 2        | 1.37%   |
| 5.17    | 2        | 1.37%   |
| 5.14    | 2        | 1.37%   |
| 5.9     | 1        | 0.68%   |
| 5.6     | 1        | 0.68%   |
| 5.19    | 1        | 0.68%   |
| 4.14    | 1        | 0.68%   |
| 4.13    | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 132      | 98.51%  |
| i686   | 2        | 1.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 54       | 40%     |
| KDE5       | 25       | 18.52%  |
| Unknown    | 21       | 15.56%  |
| X-Cinnamon | 9        | 6.67%   |
| XFCE       | 7        | 5.19%   |
| MATE       | 4        | 2.96%   |
| KDE        | 4        | 2.96%   |
| Cinnamon   | 3        | 2.22%   |
| Budgie     | 3        | 2.22%   |
| Unity      | 1        | 0.74%   |
| Pantheon   | 1        | 0.74%   |
| openbox    | 1        | 0.74%   |
| LXQt       | 1        | 0.74%   |
| DWM        | 1        | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 117      | 86.67%  |
| Unknown | 9        | 6.67%   |
| Wayland | 6        | 4.44%   |
| Tty     | 3        | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 77       | 55.8%   |
| SDDM    | 23       | 16.67%  |
| LightDM | 14       | 10.14%  |
| GDM3    | 10       | 7.25%   |
| GDM     | 10       | 7.25%   |
| TDM     | 4        | 2.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 70       | 50.72%  |
| hr_HR   | 36       | 26.09%  |
| Unknown | 24       | 17.39%  |
| en_GB   | 6        | 4.35%   |
| C       | 2        | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 79       | 58.96%  |
| EFI  | 55       | 41.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 107      | 78.1%   |
| Overlay | 13       | 9.49%   |
| Btrfs   | 9        | 6.57%   |
| Unknown | 4        | 2.92%   |
| Zfs     | 3        | 2.19%   |
| Xfs     | 1        | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 83       | 61.48%  |
| GPT     | 36       | 26.67%  |
| MBR     | 16       | 11.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 78.99%  |
| Yes       | 29       | 21.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 61.76%  |
| Yes       | 52       | 38.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 34       | 25.37%  |
| ASRock              | 33       | 24.63%  |
| Gigabyte Technology | 26       | 19.4%   |
| MSI                 | 10       | 7.46%   |
| Hewlett-Packard     | 7        | 5.22%   |
| Pegatron            | 5        | 3.73%   |
| Dell                | 5        | 3.73%   |
| Intel               | 4        | 2.99%   |
| ECS                 | 3        | 2.24%   |
| WinFast             | 1        | 0.75%   |
| Lenovo              | 1        | 0.75%   |
| Fujitsu Siemens     | 1        | 0.75%   |
| Foxconn             | 1        | 0.75%   |
| Acer                | 1        | 0.75%   |
| ABIT                | 1        | 0.75%   |
| Unknown             | 1        | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 5        | 3.73%   |
| ASUS PRIME A320M-K                     | 3        | 2.24%   |
| MSI MS-7850                            | 2        | 1.49%   |
| Gigabyte A320M-S2H                     | 2        | 1.49%   |
| ASUS P8H77-V LE                        | 2        | 1.49%   |
| ASUS M5A78L LE                         | 2        | 1.49%   |
| ASRock H61M-DGS                        | 2        | 1.49%   |
| ASRock B450M-HDV R4.0                  | 2        | 1.49%   |
| WinFast N570SM2AA                      | 1        | 0.75%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.75%   |
| Pegatron HPE-520ad                     | 1        | 0.75%   |
| Pegatron G5261de                       | 1        | 0.75%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 0.75%   |
| Pegatron 27-1001eu                     | 1        | 0.75%   |
| MSI MS-7C02                            | 1        | 0.75%   |
| MSI MS-7B98                            | 1        | 0.75%   |
| MSI MS-7B84                            | 1        | 0.75%   |
| MSI MS-7B07                            | 1        | 0.75%   |
| MSI MS-7817                            | 1        | 0.75%   |
| MSI MS-7681                            | 1        | 0.75%   |
| MSI MS-7586                            | 1        | 0.75%   |
| MSI MS-7360                            | 1        | 0.75%   |
| Lenovo S510                            | 1        | 0.75%   |
| Intel H61M-S2PV                        | 1        | 0.75%   |
| Intel DX58SO AAE29331-501              | 1        | 0.75%   |
| Intel DH67BL AAG10189-213              | 1        | 0.75%   |
| Intel DH61CR AAG14064-204              | 1        | 0.75%   |
| HP Z840 Workstation                    | 1        | 0.75%   |
| HP Z440 Workstation                    | 1        | 0.75%   |
| HP ProOne 400 G1 AiO                   | 1        | 0.75%   |
| HP ProDesk 600 G4 PCI MT               | 1        | 0.75%   |
| HP ProDesk 600 G1 SFF                  | 1        | 0.75%   |
| HP EliteDesk 800 G1 DM                 | 1        | 0.75%   |
| HP Compaq dc7900 Small Form Factor     | 1        | 0.75%   |
| Gigabyte Z97-D3H                       | 1        | 0.75%   |
| Gigabyte Z77P-D3                       | 1        | 0.75%   |
| Gigabyte Z390 M GAMING                 | 1        | 0.75%   |
| Gigabyte Z390 AORUS PRO                | 1        | 0.75%   |
| Gigabyte X48T-DQ6                      | 1        | 0.75%   |
| Gigabyte X399 AORUS XTREME             | 1        | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 8        | 5.97%   |
| ASUS All           | 5        | 3.73%   |
| Dell Vostro        | 3        | 2.24%   |
| ASUS TUF           | 3        | 2.24%   |
| MSI MS-7850        | 2        | 1.49%   |
| HP ProDesk         | 2        | 1.49%   |
| Gigabyte Z390      | 2        | 1.49%   |
| Gigabyte A320M-S2H | 2        | 1.49%   |
| Dell OptiPlex      | 2        | 1.49%   |
| ASUS ROG           | 2        | 1.49%   |
| ASUS P8H77-V       | 2        | 1.49%   |
| ASUS M5A78L        | 2        | 1.49%   |
| ASRock H97         | 2        | 1.49%   |
| ASRock H61M-DGS    | 2        | 1.49%   |
| ASRock B450M-HDV   | 2        | 1.49%   |
| ASRock A320M-HDV   | 2        | 1.49%   |
| WinFast N570SM2AA  | 1        | 0.75%   |
| Pegatron Pro       | 1        | 0.75%   |
| Pegatron HPE-520ad | 1        | 0.75%   |
| Pegatron G5261de   | 1        | 0.75%   |
| Pegatron Compaq    | 1        | 0.75%   |
| Pegatron 27-1001eu | 1        | 0.75%   |
| MSI MS-7C02        | 1        | 0.75%   |
| MSI MS-7B98        | 1        | 0.75%   |
| MSI MS-7B84        | 1        | 0.75%   |
| MSI MS-7B07        | 1        | 0.75%   |
| MSI MS-7817        | 1        | 0.75%   |
| MSI MS-7681        | 1        | 0.75%   |
| MSI MS-7586        | 1        | 0.75%   |
| MSI MS-7360        | 1        | 0.75%   |
| Lenovo S510        | 1        | 0.75%   |
| Intel H61M-S2PV    | 1        | 0.75%   |
| Intel DX58SO       | 1        | 0.75%   |
| Intel DH67BL       | 1        | 0.75%   |
| Intel DH61CR       | 1        | 0.75%   |
| HP Z840            | 1        | 0.75%   |
| HP Z440            | 1        | 0.75%   |
| HP ProOne          | 1        | 0.75%   |
| HP EliteDesk       | 1        | 0.75%   |
| HP Compaq          | 1        | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 16       | 11.94%  |
| 2018 | 13       | 9.7%    |
| 2012 | 13       | 9.7%    |
| 2017 | 12       | 8.96%   |
| 2011 | 12       | 8.96%   |
| 2020 | 10       | 7.46%   |
| 2014 | 9        | 6.72%   |
| 2009 | 8        | 5.97%   |
| 2019 | 7        | 5.22%   |
| 2010 | 7        | 5.22%   |
| 2008 | 7        | 5.22%   |
| 2021 | 6        | 4.48%   |
| 2015 | 6        | 4.48%   |
| 2007 | 4        | 2.99%   |
| 2006 | 2        | 1.49%   |
| 2005 | 2        | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 134      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 129      | 95.56%  |
| Enabled  | 6        | 4.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 134      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 37       | 27.01%  |
| 8.01-16.0   | 37       | 27.01%  |
| 4.01-8.0    | 25       | 18.25%  |
| 3.01-4.0    | 17       | 12.41%  |
| 32.01-64.0  | 11       | 8.03%   |
| 1.01-2.0    | 5        | 3.65%   |
| 24.01-32.0  | 2        | 1.46%   |
| 64.01-256.0 | 2        | 1.46%   |
| 2.01-3.0    | 1        | 0.73%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 62       | 42.76%  |
| 2.01-3.0   | 37       | 25.52%  |
| 4.01-8.0   | 18       | 12.41%  |
| 3.01-4.0   | 13       | 8.97%   |
| 0.51-1.0   | 9        | 6.21%   |
| 16.01-24.0 | 3        | 2.07%   |
| 8.01-16.0  | 2        | 1.38%   |
| 0.01-0.5   | 1        | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 36.43%  |
| 2      | 44       | 31.43%  |
| 3      | 26       | 18.57%  |
| 5      | 8        | 5.71%   |
| 4      | 7        | 5%      |
| 0      | 2        | 1.43%   |
| 7      | 1        | 0.71%   |
| 6      | 1        | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 50.37%  |
| No        | 67       | 49.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 131      | 97.76%  |
| No        | 3        | 2.24%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 65.44%  |
| Yes       | 47       | 34.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 82.84%  |
| Yes       | 23       | 17.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Croatia | 134      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Zagreb          | 73       | 50.69%  |
| Split           | 11       | 7.64%   |
| Rijeka          | 6        | 4.17%   |
| Velika Gorica   | 3        | 2.08%   |
| Varaždin       | 3        | 2.08%   |
| Samobor         | 3        | 2.08%   |
| Osijek          | 3        | 2.08%   |
| Koprivnica      | 3        | 2.08%   |
| Zaprešić      | 2        | 1.39%   |
| Virovitica      | 2        | 1.39%   |
| Pula            | 2        | 1.39%   |
| Ivanja Reka     | 2        | 1.39%   |
| GJurgevac       | 2        | 1.39%   |
| Bjelovar        | 2        | 1.39%   |
| Zadar           | 1        | 0.69%   |
| Visnjevac       | 1        | 0.69%   |
| Supetar         | 1        | 0.69%   |
| Stari Perkovci  | 1        | 0.69%   |
| Slatina         | 1        | 0.69%   |
| Skrad           | 1        | 0.69%   |
| Sisak           | 1        | 0.69%   |
| Sesvete         | 1        | 0.69%   |
| Raslina         | 1        | 0.69%   |
| Prelog          | 1        | 0.69%   |
| Postira         | 1        | 0.69%   |
| Pitomaca        | 1        | 0.69%   |
| Novi Marof      | 1        | 0.69%   |
| Matulji         | 1        | 0.69%   |
| Mali Lošinj    | 1        | 0.69%   |
| Mahicno         | 1        | 0.69%   |
| Labin           | 1        | 0.69%   |
| Kućan Marof    | 1        | 0.69%   |
| Krizevci        | 1        | 0.69%   |
| Kastel Gomilica | 1        | 0.69%   |
| Hvar            | 1        | 0.69%   |
| Grad            | 1        | 0.69%   |
| Galgovo         | 1        | 0.69%   |
| Dubrovnik       | 1        | 0.69%   |
| Dobrec          | 1        | 0.69%   |
| Bosnjaci        | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 63       | 110    | 25.93%  |
| Kingston            | 30       | 42     | 12.35%  |
| Samsung Electronics | 29       | 42     | 11.93%  |
| Seagate             | 24       | 35     | 9.88%   |
| Toshiba             | 20       | 25     | 8.23%   |
| Crucial             | 12       | 15     | 4.94%   |
| Intel               | 10       | 11     | 4.12%   |
| A-DATA Technology   | 9        | 12     | 3.7%    |
| Patriot             | 5        | 8      | 2.06%   |
| Hitachi             | 4        | 5      | 1.65%   |
| Transcend           | 3        | 3      | 1.23%   |
| Silicon Motion      | 3        | 4      | 1.23%   |
| SanDisk             | 3        | 4      | 1.23%   |
| Phison              | 3        | 3      | 1.23%   |
| OCZ                 | 2        | 3      | 0.82%   |
| Maxtor              | 2        | 2      | 0.82%   |
| Gigabyte Technology | 2        | 2      | 0.82%   |
| Corsair             | 2        | 2      | 0.82%   |
| XPG                 | 1        | 3      | 0.41%   |
| TO Exter            | 1        | 1      | 0.41%   |
| SK hynix            | 1        | 1      | 0.41%   |
| PNY                 | 1        | 1      | 0.41%   |
| Netac               | 1        | 1      | 0.41%   |
| Mushkin             | 1        | 2      | 0.41%   |
| Min Yi U            | 1        | 1      | 0.41%   |
| Micron Technology   | 1        | 1      | 0.41%   |
| KingSpec            | 1        | 1      | 0.41%   |
| Kingmax             | 1        | 1      | 0.41%   |
| HPE                 | 1        | 2      | 0.41%   |
| HGST HTS            | 1        | 1      | 0.41%   |
| HGST                | 1        | 1      | 0.41%   |
| Goodram             | 1        | 1      | 0.41%   |
| External            | 1        | 1      | 0.41%   |
| ASMedia             | 1        | 1      | 0.41%   |
| AMD                 | 1        | 2      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SV300S37A120G 120GB SSD | 5        | 1.81%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 1.81%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 1.44%   |
| Toshiba HDWD130 3TB              | 4        | 1.44%   |
| Samsung SSD 850 EVO 250GB        | 4        | 1.44%   |
| Kingston SA400S37120G 120GB SSD  | 4        | 1.44%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 1.08%   |
| Toshiba HDWD110 1TB              | 3        | 1.08%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.08%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 1.08%   |
| Samsung HD103SI 1TB              | 3        | 1.08%   |
| Patriot Burst 240GB SSD          | 3        | 1.08%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.08%   |
| Intel SSDSC2BW120A4 120GB        | 3        | 1.08%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 0.72%   |
| WDC WD6400AAKS-22A7B0 640GB      | 2        | 0.72%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2        | 0.72%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.72%   |
| WDC WD3200AAKS-00L9A0 320GB      | 2        | 0.72%   |
| WDC WD30EZRX-00AZ6B0 3TB         | 2        | 0.72%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 0.72%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 2        | 0.72%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 0.72%   |
| WDC WD1600AAJS-07M0A0 160GB      | 2        | 0.72%   |
| Toshiba HDWD120 2TB              | 2        | 0.72%   |
| Toshiba DT01ACA300 3TB           | 2        | 0.72%   |
| Seagate ST31000528AS 1TB         | 2        | 0.72%   |
| Seagate ST31000524AS 1TB         | 2        | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.72%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.72%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.72%   |
| Samsung SSD 860 QVO 1TB          | 2        | 0.72%   |
| Samsung SSD 860 PRO 256GB        | 2        | 0.72%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 0.72%   |
| Samsung NVMe SSD Drive 1TB       | 2        | 0.72%   |
| Samsung HD256GJ 250GB            | 2        | 0.72%   |
| Kingston SV300S37A60G 64GB SSD   | 2        | 0.72%   |
| Kingston SUV400S37240G 240GB SSD | 2        | 0.72%   |
| Kingston SHFS37A120G 120GB SSD   | 2        | 0.72%   |
| Kingston SA2000M8500G 500GB      | 2        | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 61       | 101    | 51.26%  |
| Seagate             | 24       | 35     | 20.17%  |
| Toshiba             | 19       | 24     | 15.97%  |
| Samsung Electronics | 7        | 9      | 5.88%   |
| Hitachi             | 4        | 5      | 3.36%   |
| Maxtor              | 2        | 2      | 1.68%   |
| HGST HTS            | 1        | 1      | 0.84%   |
| HGST                | 1        | 1      | 0.84%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 27       | 36     | 28.72%  |
| Samsung Electronics | 14       | 21     | 14.89%  |
| Crucial             | 11       | 13     | 11.7%   |
| Intel               | 8        | 9      | 8.51%   |
| A-DATA Technology   | 7        | 9      | 7.45%   |
| Patriot             | 4        | 7      | 4.26%   |
| WDC                 | 2        | 2      | 2.13%   |
| Transcend           | 2        | 2      | 2.13%   |
| SanDisk             | 2        | 3      | 2.13%   |
| OCZ                 | 2        | 3      | 2.13%   |
| Gigabyte Technology | 2        | 2      | 2.13%   |
| Toshiba             | 1        | 1      | 1.06%   |
| TO Exter            | 1        | 1      | 1.06%   |
| SK hynix            | 1        | 1      | 1.06%   |
| PNY                 | 1        | 1      | 1.06%   |
| Netac               | 1        | 1      | 1.06%   |
| Mushkin             | 1        | 2      | 1.06%   |
| Min Yi U            | 1        | 1      | 1.06%   |
| KingSpec            | 1        | 1      | 1.06%   |
| Kingmax             | 1        | 1      | 1.06%   |
| Goodram             | 1        | 1      | 1.06%   |
| Corsair             | 1        | 1      | 1.06%   |
| ASMedia             | 1        | 1      | 1.06%   |
| AMD                 | 1        | 2      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 95       | 178    | 46.8%   |
| SSD     | 76       | 122    | 37.44%  |
| NVMe    | 31       | 48     | 15.27%  |
| Unknown | 1        | 2      | 0.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 120      | 296    | 76.92%  |
| NVMe | 30       | 47     | 19.23%  |
| SAS  | 6        | 7      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 98       | 178    | 54.44%  |
| 0.51-1.0   | 49       | 72     | 27.22%  |
| 1.01-2.0   | 15       | 21     | 8.33%   |
| 2.01-3.0   | 12       | 23     | 6.67%   |
| 3.01-4.0   | 5        | 5      | 2.78%   |
| 4.01-10.0  | 1        | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 43       | 30.07%  |
| 251-500        | 22       | 15.38%  |
| 501-1000       | 21       | 14.69%  |
| 1001-2000      | 16       | 11.19%  |
| More than 3000 | 10       | 6.99%   |
| 1-20           | 10       | 6.99%   |
| 51-100         | 9        | 6.29%   |
| Unknown        | 6        | 4.2%    |
| 2001-3000      | 4        | 2.8%    |
| 21-50          | 2        | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 68       | 45.64%  |
| 21-50          | 15       | 10.07%  |
| 251-500        | 14       | 9.4%    |
| 501-1000       | 11       | 7.38%   |
| 101-250        | 10       | 6.71%   |
| 51-100         | 10       | 6.71%   |
| 1001-2000      | 8        | 5.37%   |
| Unknown        | 6        | 4.03%   |
| 2001-3000      | 4        | 2.68%   |
| More than 3000 | 3        | 2.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-07A7B0 640GB        | 1        | 1      | 5.26%   |
| WDC WD5000AAKX-221CA1 500GB        | 1        | 1      | 5.26%   |
| WDC WD3200AAKS-00L9A0 320GB        | 1        | 1      | 5.26%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1      | 5.26%   |
| WDC WD10EZEX-00MFCA0 1TB           | 1        | 1      | 5.26%   |
| Transcend TS480GSSD220S 480GB      | 1        | 1      | 5.26%   |
| Toshiba DT01ACA100 1TB             | 1        | 1      | 5.26%   |
| SK hynix SH920 2.5 7MM 256GB SSD   | 1        | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 5.26%   |
| Seagate ST31500341AS 1TB           | 1        | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 5.26%   |
| SanDisk SDSSDA240G 240GB           | 1        | 1      | 5.26%   |
| Kingston SHFS37A120G 120GB SSD     | 1        | 1      | 5.26%   |
| Intel SSDSC2BW180A4 180GB          | 1        | 1      | 5.26%   |
| Intel SSDSC2BW120A4 120GB          | 1        | 1      | 5.26%   |
| Hitachi HDS723020BLA642 2TB        | 1        | 1      | 5.26%   |
| Crucial CT525MX300SSD1 528GB       | 1        | 1      | 5.26%   |
| Crucial CT120BX500SSD1 120GB       | 1        | 1      | 5.26%   |
| A-DATA Technology SP900 64GB SSD   | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 5        | 5      | 26.32%  |
| Seagate           | 3        | 3      | 15.79%  |
| Intel             | 2        | 2      | 10.53%  |
| Crucial           | 2        | 2      | 10.53%  |
| Transcend         | 1        | 1      | 5.26%   |
| Toshiba           | 1        | 1      | 5.26%   |
| SK hynix          | 1        | 1      | 5.26%   |
| SanDisk           | 1        | 1      | 5.26%   |
| Kingston          | 1        | 1      | 5.26%   |
| Hitachi           | 1        | 1      | 5.26%   |
| A-DATA Technology | 1        | 1      | 5.26%   |

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
| HDD  | 10       | 10     | 52.63%  |
| SSD  | 9        | 9      | 47.37%  |

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
| Detected | 86       | 225    | 57.33%  |
| Works    | 48       | 106    | 32%     |
| Malfunc  | 16       | 19     | 10.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 85       | 47.75%  |
| AMD                         | 43       | 24.16%  |
| Samsung Electronics         | 10       | 5.62%   |
| Phison Electronics          | 5        | 2.81%   |
| Kingston Technology Company | 5        | 2.81%   |
| JMicron Technology          | 5        | 2.81%   |
| Nvidia                      | 4        | 2.25%   |
| ASMedia Technology          | 4        | 2.25%   |
| Silicon Motion              | 3        | 1.69%   |
| Marvell Technology Group    | 3        | 1.69%   |
| ADATA Technology            | 3        | 1.69%   |
| SanDisk                     | 2        | 1.12%   |
| VIA Technologies            | 1        | 0.56%   |
| Transcend                   | 1        | 0.56%   |
| Micron/Crucial Technology   | 1        | 0.56%   |
| Micron Technology           | 1        | 0.56%   |
| Broadcom / LSI              | 1        | 0.56%   |
| Adaptec                     | 1        | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 10.13%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 6.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 4.64%   |
| AMD FCH SATA Controller D                                                               | 10       | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 3.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 2.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.53%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 2.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.11%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.11%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.69%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.69%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.69%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.69%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 1.27%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.84%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.84%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.84%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.84%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.84%   |
| Intel SSD 600P Series                                                                   | 2        | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.84%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.84%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.84%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.84%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.84%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 101      | 54.89%  |
| IDE  | 46       | 25%     |
| NVMe | 31       | 16.85%  |
| RAID | 5        | 2.72%   |
| SAS  | 1        | 0.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 85       | 63.43%  |
| AMD    | 49       | 36.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 3.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.19%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 2.19%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 2.19%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.19%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 3        | 2.19%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2.19%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 1.46%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.46%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 2        | 1.46%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.46%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.46%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.46%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 2        | 1.46%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.46%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.46%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.46%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.46%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.46%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.46%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.46%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 1.46%   |
| AMD Phenom II X4 965 Processor              | 2        | 1.46%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.46%   |
| AMD Athlon X4 740 Quad Core Processor       | 2        | 1.46%   |
| AMD Athlon 64 X2 Dual Core Processor 6400+  | 2        | 1.46%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.73%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz         | 1        | 0.73%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.73%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.73%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.73%   |
| Intel Pentium CPU G4560T @ 2.90GHz          | 1        | 0.73%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.73%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.73%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.73%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.73%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.73%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.73%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.73%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 20.44%  |
| Intel Core i3           | 17       | 12.41%  |
| Intel Core i7           | 13       | 9.49%   |
| AMD Ryzen 5             | 9        | 6.57%   |
| Intel Core 2 Duo        | 7        | 5.11%   |
| AMD FX                  | 5        | 3.65%   |
| Intel Pentium           | 4        | 2.92%   |
| AMD Ryzen 3             | 4        | 2.92%   |
| AMD Athlon II X4        | 4        | 2.92%   |
| Other                   | 3        | 2.19%   |
| Intel Xeon              | 3        | 2.19%   |
| AMD Ryzen 9             | 3        | 2.19%   |
| AMD Ryzen 7             | 3        | 2.19%   |
| AMD Phenom II X4        | 3        | 2.19%   |
| AMD Athlon X4           | 3        | 2.19%   |
| AMD Athlon 64 X2        | 3        | 2.19%   |
| Intel Pentium Dual-Core | 2        | 1.46%   |
| Intel Pentium 4         | 2        | 1.46%   |
| Intel Core i9           | 2        | 1.46%   |
| Intel Core 2 Quad       | 2        | 1.46%   |
| Intel Core 2            | 2        | 1.46%   |
| AMD A8                  | 2        | 1.46%   |
| Intel Pentium Dual      | 1        | 0.73%   |
| Intel Celeron           | 1        | 0.73%   |
| AMD Ryzen Threadripper  | 1        | 0.73%   |
| AMD Ryzen 7 PRO         | 1        | 0.73%   |
| AMD Ryzen 5 PRO         | 1        | 0.73%   |
| AMD Ryzen 3 PRO         | 1        | 0.73%   |
| AMD Phenom II X6        | 1        | 0.73%   |
| AMD Phenom II X2        | 1        | 0.73%   |
| AMD Phenom              | 1        | 0.73%   |
| AMD E                   | 1        | 0.73%   |
| AMD Athlon 64           | 1        | 0.73%   |
| AMD Athlon              | 1        | 0.73%   |
| AMD A6                  | 1        | 0.73%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 61       | 44.53%  |
| 2      | 39       | 28.47%  |
| 6      | 16       | 11.68%  |
| 8      | 8        | 5.84%   |
| 1      | 4        | 2.92%   |
| 12     | 3        | 2.19%   |
| 3      | 3        | 2.19%   |
| 24     | 1        | 0.73%   |
| 16     | 1        | 0.73%   |
| 10     | 1        | 0.73%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 133      | 99.25%  |
| 2      | 1        | 0.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 68       | 50.37%  |
| 1      | 67       | 49.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 132      | 98.51%  |
| Unknown        | 2        | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 17.27%  |
| 0x306c3    | 20       | 14.39%  |
| 0x206a7    | 11       | 7.91%   |
| 0x1067a    | 7        | 5.04%   |
| 0xa0653    | 5        | 3.6%    |
| 0x906ea    | 5        | 3.6%    |
| 0x0800820d | 5        | 3.6%    |
| 0x010000db | 4        | 2.88%   |
| 0x010000c8 | 4        | 2.88%   |
| 0xa0671    | 3        | 2.16%   |
| 0x6fd      | 3        | 2.16%   |
| 0x506e3    | 3        | 2.16%   |
| 0x306a9    | 3        | 2.16%   |
| 0x06001119 | 3        | 2.16%   |
| 0xf43      | 2        | 1.44%   |
| 0xa0655    | 2        | 1.44%   |
| 0x906ed    | 2        | 1.44%   |
| 0x906eb    | 2        | 1.44%   |
| 0x906e9    | 2        | 1.44%   |
| 0x6fb      | 2        | 1.44%   |
| 0x306f2    | 2        | 1.44%   |
| 0x08701021 | 2        | 1.44%   |
| 0x0810100b | 2        | 1.44%   |
| 0x08001137 | 2        | 1.44%   |
| 0x06000852 | 2        | 1.44%   |
| 0x0600063e | 2        | 1.44%   |
| 0x6f6      | 1        | 0.72%   |
| 0x20655    | 1        | 0.72%   |
| 0x106a4    | 1        | 0.72%   |
| 0x0a201009 | 1        | 0.72%   |
| 0x0a201005 | 1        | 0.72%   |
| 0x08701013 | 1        | 0.72%   |
| 0x08600106 | 1        | 0.72%   |
| 0x08600103 | 1        | 0.72%   |
| 0x08108109 | 1        | 0.72%   |
| 0x08108102 | 1        | 0.72%   |
| 0x08001138 | 1        | 0.72%   |
| 0x08001129 | 1        | 0.72%   |
| 0x05000029 | 1        | 0.72%   |
| 0x010000dc | 1        | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 25       | 18.66%  |
| SandyBridge | 12       | 8.96%   |
| KabyLake    | 10       | 7.46%   |
| Zen+        | 9        | 6.72%   |
| K10         | 9        | 6.72%   |
| Zen         | 8        | 5.97%   |
| Piledriver  | 8        | 5.97%   |
| CometLake   | 8        | 5.97%   |
| Penryn      | 7        | 5.22%   |
| Core        | 7        | 5.22%   |
| Zen 2       | 5        | 3.73%   |
| Skylake     | 4        | 2.99%   |
| K8 Hammer   | 4        | 2.99%   |
| IvyBridge   | 4        | 2.99%   |
| Zen 3       | 2        | 1.49%   |
| Westmere    | 2        | 1.49%   |
| NetBurst    | 2        | 1.49%   |
| Icelake     | 2        | 1.49%   |
| Bulldozer   | 2        | 1.49%   |
| Nehalem     | 1        | 0.75%   |
| Excavator   | 1        | 0.75%   |
| Bobcat      | 1        | 0.75%   |
| Unknown     | 1        | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 56       | 38.36%  |
| AMD              | 52       | 35.62%  |
| Intel            | 37       | 25.34%  |
| ATI Technologies | 1        | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 6.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 5.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 4.05%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 3.38%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 2.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 2.03%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.03%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 3        | 2.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 2.03%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 1.35%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.35%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.35%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.35%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 1.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.35%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.35%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.35%   |
| Intel HD Graphics 530                                                       | 2        | 1.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.35%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.35%   |
| AMD Renoir                                                                  | 2        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.35%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 1.35%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.35%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 1.35%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.68%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.68%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.68%   |
| Nvidia GM206 [GeForce GTX 750 v2]                                           | 1        | 0.68%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1        | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.68%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.68%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 52       | 37.96%  |
| 1 x AMD        | 48       | 35.04%  |
| 1 x Intel      | 30       | 21.9%   |
| Intel + Nvidia | 3        | 2.19%   |
| 2 x AMD        | 2        | 1.46%   |
| Intel + AMD    | 1        | 0.73%   |
| AMD + Nvidia   | 1        | 0.73%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 95       | 68.84%  |
| Proprietary | 41       | 29.71%  |
| Unknown     | 2        | 1.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 35.97%  |
| 1.01-2.0   | 28       | 20.14%  |
| 0.51-1.0   | 27       | 19.42%  |
| 3.01-4.0   | 11       | 7.91%   |
| 7.01-8.0   | 9        | 6.47%   |
| 0.01-0.5   | 8        | 5.76%   |
| 5.01-6.0   | 2        | 1.44%   |
| 2.01-3.0   | 2        | 1.44%   |
| 8.01-16.0  | 2        | 1.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 31       | 21.23%  |
| AOC                  | 20       | 13.7%   |
| Dell                 | 18       | 12.33%  |
| Philips              | 16       | 10.96%  |
| Goldstar             | 13       | 8.9%    |
| Acer                 | 13       | 8.9%    |
| Ancor Communications | 8        | 5.48%   |
| Hewlett-Packard      | 5        | 3.42%   |
| LG Electronics       | 3        | 2.05%   |
| Unknown              | 2        | 1.37%   |
| Huion                | 2        | 1.37%   |
| Fujitsu Siemens      | 2        | 1.37%   |
| BenQ                 | 2        | 1.37%   |
| Vestel Elektronik    | 1        | 0.68%   |
| RTK                  | 1        | 0.68%   |
| Panasonic            | 1        | 0.68%   |
| NOA VISION           | 1        | 0.68%   |
| NEC Computers        | 1        | 0.68%   |
| LG Display           | 1        | 0.68%   |
| Lenovo               | 1        | 0.68%   |
| KTC                  | 1        | 0.68%   |
| InnoLux Display      | 1        | 0.68%   |
| Grundig              | 1        | 0.68%   |
| ASUSTek Computer     | 1        | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0509 1920x1080                    | 2        | 1.27%   |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                   | 2        | 1.27%   |
| Huion GT221 HAT2150 1920x1080 476x267mm 21.5-inch                    | 2        | 1.27%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 2        | 1.27%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                    | 2        | 1.27%   |
| Dell LCD Monitor SE2416H 5760x1080                                   | 2        | 1.27%   |
| Dell LCD Monitor SE2416H                                             | 2        | 1.27%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                    | 2        | 1.27%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 1.27%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 2        | 1.27%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 2        | 1.27%   |
| AOC 22B1W AOC2201 1920x1080 476x268mm 21.5-inch                      | 2        | 1.27%   |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                    | 2        | 1.27%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch   | 1        | 0.64%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.64%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                          | 1        | 0.64%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch    | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0608 1920x1080 510x290mm 23.1-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM05C6 1920x1080 520x290mm 23.4-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM01E7 1920x1200 518x324mm 24.1-inch | 1        | 0.64%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch | 1        | 0.64%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch    | 1        | 0.64%   |
| Samsung Electronics SMB1940 SAM06BA 1280x1024 376x301mm 19.0-inch    | 1        | 0.64%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 0.64%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch    | 1        | 0.64%   |
| Samsung Electronics LS24A600U SAM7160 2560x1440 527x297mm 23.8-inch  | 1        | 0.64%   |
| Samsung Electronics LF27T450F SAM7097 1920x1080 597x336mm 27.0-inch  | 1        | 0.64%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 480x270mm 21.7-inch    | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                 | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                 | 1        | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 67       | 46.21%  |
| 2560x1440 (QHD)    | 11       | 7.59%   |
| 1680x1050 (WSXGA+) | 11       | 7.59%   |
| 1280x1024 (SXGA)   | 9        | 6.21%   |
| Unknown            | 8        | 5.52%   |
| 3840x2160 (4K)     | 7        | 4.83%   |
| 1920x1200 (WUXGA)  | 6        | 4.14%   |
| 1600x900 (HD+)     | 5        | 3.45%   |
| 3840x1080          | 4        | 2.76%   |
| 1360x768           | 4        | 2.76%   |
| 1440x900 (WXGA+)   | 3        | 2.07%   |
| 5760x1080          | 2        | 1.38%   |
| 2560x1080          | 2        | 1.38%   |
| 2048x1152          | 2        | 1.38%   |
| 1366x768 (WXGA)    | 2        | 1.38%   |
| 4480x1440          | 1        | 0.69%   |
| 2560x1600          | 1        | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 27       | 18.75%  |
| Unknown | 19       | 13.19%  |
| 24      | 18       | 12.5%   |
| 21      | 18       | 12.5%   |
| 27      | 16       | 11.11%  |
| 22      | 9        | 6.25%   |
| 19      | 8        | 5.56%   |
| 20      | 6        | 4.17%   |
| 31      | 4        | 2.78%   |
| 17      | 4        | 2.78%   |
| 18      | 3        | 2.08%   |
| 84      | 2        | 1.39%   |
| 33      | 2        | 1.39%   |
| 25      | 2        | 1.39%   |
| 60      | 1        | 0.69%   |
| 54      | 1        | 0.69%   |
| 46      | 1        | 0.69%   |
| 34      | 1        | 0.69%   |
| 32      | 1        | 0.69%   |
| 26      | 1        | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 58       | 41.73%  |
| 401-500     | 37       | 26.62%  |
| Unknown     | 19       | 13.67%  |
| 601-700     | 7        | 5.04%   |
| 351-400     | 6        | 4.32%   |
| 701-800     | 4        | 2.88%   |
| 301-350     | 3        | 2.16%   |
| 1001-1500   | 3        | 2.16%   |
| 1501-2000   | 2        | 1.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 86       | 63.7%   |
| 16/10   | 22       | 16.3%   |
| Unknown | 17       | 12.59%  |
| 5/4     | 8        | 5.93%   |
| 3/2     | 1        | 0.74%   |
| 21/9    | 1        | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 52       | 36.88%  |
| 151-200        | 23       | 16.31%  |
| Unknown        | 19       | 13.48%  |
| 301-350        | 17       | 12.06%  |
| 251-300        | 10       | 7.09%   |
| 351-500        | 8        | 5.67%   |
| 141-150        | 6        | 4.26%   |
| More than 1000 | 4        | 2.84%   |
| 121-130        | 1        | 0.71%   |
| 501-1000       | 1        | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 82       | 61.19%  |
| 101-120 | 25       | 18.66%  |
| Unknown | 19       | 14.18%  |
| 1-50    | 4        | 2.99%   |
| 121-160 | 3        | 2.24%   |
| 161-240 | 1        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 104      | 76.47%  |
| 2     | 25       | 18.38%  |
| 0     | 5        | 3.68%   |
| 4     | 1        | 0.74%   |
| 3     | 1        | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 88       | 46.32%  |
| Intel                             | 38       | 20%     |
| Qualcomm Atheros                  | 10       | 5.26%   |
| TP-Link                           | 8        | 4.21%   |
| Ralink                            | 5        | 2.63%   |
| Qualcomm Atheros Communications   | 5        | 2.63%   |
| Broadcom                          | 5        | 2.63%   |
| Ralink Technology                 | 4        | 2.11%   |
| Nvidia                            | 4        | 2.11%   |
| Sundance Technology Inc / IC Plus | 2        | 1.05%   |
| Samsung Electronics               | 2        | 1.05%   |
| MediaTek                          | 2        | 1.05%   |
| Marvell Technology Group          | 2        | 1.05%   |
| D-Link                            | 2        | 1.05%   |
| Xiaomi                            | 1        | 0.53%   |
| VIA Technologies                  | 1        | 0.53%   |
| T & A Mobile Phones               | 1        | 0.53%   |
| Nokia Mobile Phones               | 1        | 0.53%   |
| Microsoft                         | 1        | 0.53%   |
| Linksys                           | 1        | 0.53%   |
| Huawei Technologies               | 1        | 0.53%   |
| Edimax Technology                 | 1        | 0.53%   |
| D-Link System                     | 1        | 0.53%   |
| Broadcom Limited                  | 1        | 0.53%   |
| ASUSTek Computer                  | 1        | 0.53%   |
| ASIX Electronics                  | 1        | 0.53%   |
| Aquantia                          | 1        | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 75       | 37.5%   |
| Qualcomm Atheros AR9271 802.11n                                            | 5        | 2.5%    |
| Intel Ethernet Connection (2) I218-V                                       | 5        | 2.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 4        | 2%      |
| Intel I211 Gigabit Network Connection                                      | 4        | 2%      |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                          | 3        | 1.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.5%    |
| Ralink MT7601U Wireless Adapter                                            | 3        | 1.5%    |
| Intel Wi-Fi 6 AX200                                                        | 3        | 1.5%    |
| Intel Ethernet Connection I217-V                                           | 3        | 1.5%    |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.5%    |
| TP-Link 802.11ac NIC                                                       | 2        | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 1%      |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 2        | 1%      |
| Ralink RT2561/RT61 802.11g PCI                                             | 2        | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                 | 2        | 1%      |
| Nvidia MCP61 Ethernet                                                      | 2        | 1%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1%      |
| Intel I210 Gigabit Network Connection                                      | 2        | 1%      |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1%      |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 1%      |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 1%      |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1%      |
| Broadcom BCM43228 802.11a/b/g/n                                            | 2        | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.5%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 1        | 0.5%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 0.5%    |
| T & A Mobile Phones 9010X                                                  | 1        | 0.5%    |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.5%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                    | 1        | 0.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.5%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| TP-Link                         | 8        | 16.33%  |
| Realtek Semiconductor           | 7        | 14.29%  |
| Ralink                          | 5        | 10.2%   |
| Qualcomm Atheros Communications | 5        | 10.2%   |
| Intel                           | 5        | 10.2%   |
| Ralink Technology               | 4        | 8.16%   |
| Qualcomm Atheros                | 4        | 8.16%   |
| Broadcom                        | 4        | 8.16%   |
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
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4        | 8.16%   |
| Ralink MT7601U Wireless Adapter                                         | 3        | 6.12%   |
| Intel Wi-Fi 6 AX200                                                     | 3        | 6.12%   |
| TP-Link 802.11ac NIC                                                    | 2        | 4.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 4.08%   |
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
| Realtek Semiconductor             | 84       | 57.53%  |
| Intel                             | 36       | 24.66%  |
| Qualcomm Atheros                  | 6        | 4.11%   |
| Nvidia                            | 4        | 2.74%   |
| Sundance Technology Inc / IC Plus | 2        | 1.37%   |
| Samsung Electronics               | 2        | 1.37%   |
| Marvell Technology Group          | 2        | 1.37%   |
| Xiaomi                            | 1        | 0.68%   |
| VIA Technologies                  | 1        | 0.68%   |
| T & A Mobile Phones               | 1        | 0.68%   |
| MediaTek                          | 1        | 0.68%   |
| Huawei Technologies               | 1        | 0.68%   |
| D-Link System                     | 1        | 0.68%   |
| Broadcom Limited                  | 1        | 0.68%   |
| Broadcom                          | 1        | 0.68%   |
| ASIX Electronics                  | 1        | 0.68%   |
| Aquantia                          | 1        | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 75       | 50%     |
| Intel Ethernet Connection (2) I218-V                                       | 5        | 3.33%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.67%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.67%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3        | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2%      |
| Intel Ethernet Connection I217-V                                           | 3        | 2%      |
| Intel Ethernet Connection I217-LM                                          | 3        | 2%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.33%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 1.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.33%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.33%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 1.33%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 1.33%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.67%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.67%   |
| T & A Mobile Phones 9010X                                                  | 1        | 0.67%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.67%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.67%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.67%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.67%   |
| MediaTek Nokia 5.1 Plus                                                    | 1        | 0.67%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1        | 0.67%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.67%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.67%   |
| Intel Ethernet Connection (11) I219-LM                                     | 1        | 0.67%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 131      | 73.18%  |
| WiFi     | 47       | 26.26%  |
| Modem    | 1        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 99       | 74.44%  |
| WiFi     | 34       | 25.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 100      | 74.07%  |
| 2     | 30       | 22.22%  |
| 0     | 3        | 2.22%   |
| 4     | 1        | 0.74%   |
| 3     | 1        | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 131      | 97.76%  |
| Yes  | 3        | 2.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 6        | 26.09%  |
| Intel                           | 5        | 21.74%  |
| Broadcom                        | 4        | 17.39%  |
| Realtek Semiconductor           | 2        | 8.7%    |
| ASUSTek Computer                | 2        | 8.7%    |
| Qualcomm Atheros Communications | 1        | 4.35%   |
| Integrated System Solution      | 1        | 4.35%   |
| IMC Networks                    | 1        | 4.35%   |
| Foxconn / Hon Hai               | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 6        | 26.09%  |
| Intel AX200 Bluetooth                                 | 3        | 13.04%  |
| Realtek Bluetooth Radio                               | 2        | 8.7%    |
| Intel Bluetooth wireless interface                    | 2        | 8.7%    |
| Broadcom HP Portable Bumble Bee                       | 2        | 8.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 8.7%    |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 4.35%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 4.35%   |
| IMC Networks BCM20702A0                               | 1        | 4.35%   |
| Foxconn / Hon Hai BT                                  | 1        | 4.35%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 4.35%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 84       | 35.29%  |
| AMD                 | 70       | 29.41%  |
| Nvidia              | 54       | 22.69%  |
| C-Media Electronics | 9        | 3.78%   |
| Logitech            | 3        | 1.26%   |
| Creative Labs       | 3        | 1.26%   |
| Microsoft           | 2        | 0.84%   |
| Yamaha              | 1        | 0.42%   |
| XMOS                | 1        | 0.42%   |
| VIA Technologies    | 1        | 0.42%   |
| Trust               | 1        | 0.42%   |
| Tenx Technology     | 1        | 0.42%   |
| Razer USA           | 1        | 0.42%   |
| Native Instruments  | 1        | 0.42%   |
| JMTek               | 1        | 0.42%   |
| Focusrite-Novation  | 1        | 0.42%   |
| Ensoniq             | 1        | 0.42%   |
| Cirrus Logic        | 1        | 0.42%   |
| ATI Technologies    | 1        | 0.42%   |
| Astro Gaming        | 1        | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 5.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 4.36%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 4.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 3.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 2.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 2.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 2.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 2.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 2.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 2.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 2.18%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 6        | 2.18%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.82%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 1.82%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 1.82%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.45%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 1.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 1.45%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4        | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 1.09%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.09%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.09%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.09%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 3        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.73%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.73%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.73%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.73%   |
| Microsoft LifeChat LX-3000 Headset                                         | 2        | 0.73%   |
| Logitech EasyCall Speakerphone                                             | 2        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 22       | 28.95%  |
| Unknown             | 9        | 11.84%  |
| G.Skill             | 9        | 11.84%  |
| Corsair             | 9        | 11.84%  |
| SK hynix            | 6        | 7.89%   |
| Samsung Electronics | 6        | 7.89%   |
| Transcend           | 3        | 3.95%   |
| Crucial             | 3        | 3.95%   |
| Patriot             | 2        | 2.63%   |
| Kingmax             | 2        | 2.63%   |
| Ramaxel Technology  | 1        | 1.32%   |
| Mushkin             | 1        | 1.32%   |
| Elpida              | 1        | 1.32%   |
| Apacer              | 1        | 1.32%   |
| A-DATA Technology   | 1        | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 667MT/s                  | 2        | 2.41%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 2.41%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s     | 2        | 2.41%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 2        | 2.41%   |
| Kingston RAM 99U5702-095.A00G 8192MB DIMM DDR4 2667MT/s | 2        | 2.41%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s              | 1        | 1.2%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 1.2%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 1        | 1.2%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 1.2%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM 1600MT/s                    | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM 1600MT/s                 | 1        | 1.2%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 1        | 1.2%    |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s              | 1        | 1.2%    |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s   | 1        | 1.2%    |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s    | 1        | 1.2%    |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s       | 1        | 1.2%    |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s       | 1        | 1.2%    |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 1        | 1.2%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.2%    |
| SK hynix RAM HMT125U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 1.2%    |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 1.2%    |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s    | 1        | 1.2%    |
| Samsung RAM M471B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s  | 1        | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.2%    |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s     | 1        | 1.2%    |
| Ramaxel RAM RMUA5090KE68H9F2133 4GB DIMM DDR4 2133MT/s  | 1        | 1.2%    |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s          | 1        | 1.2%    |
| Patriot RAM PSD22G80026 2048MB DIMM DDR2 800MT/s        | 1        | 1.2%    |
| Mushkin RAM 99[2/7/4]199[F/T] 8192MB DIMM DDR4 2400MT/s | 1        | 1.2%    |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s     | 1        | 1.2%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 1        | 1.2%    |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s    | 1        | 1.2%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s       | 1        | 1.2%    |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s    | 1        | 1.2%    |
| Kingston RAM KHX2133C13D4/8GX 8192MB DIMM DDR4 2133MT/s | 1        | 1.2%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s     | 1        | 1.2%    |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s     | 1        | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 50%     |
| DDR3    | 22       | 34.38%  |
| Unknown | 4        | 6.25%   |
| DDR2    | 3        | 4.69%   |
| SDRAM   | 2        | 3.13%   |
| DDR     | 1        | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 60       | 95.24%  |
| SODIMM | 3        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 28       | 40%     |
| 4096  | 19       | 27.14%  |
| 2048  | 10       | 14.29%  |
| 16384 | 9        | 12.86%  |
| 1024  | 3        | 4.29%   |
| 512   | 1        | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 13       | 19.12%  |
| 3200  | 8        | 11.76%  |
| 2667  | 7        | 10.29%  |
| 1333  | 7        | 10.29%  |
| 2400  | 5        | 7.35%   |
| 2133  | 4        | 5.88%   |
| 3600  | 2        | 2.94%   |
| 3466  | 2        | 2.94%   |
| 3400  | 2        | 2.94%   |
| 2933  | 2        | 2.94%   |
| 2666  | 2        | 2.94%   |
| 1800  | 2        | 2.94%   |
| 800   | 2        | 2.94%   |
| 667   | 2        | 2.94%   |
| 4000  | 1        | 1.47%   |
| 3334  | 1        | 1.47%   |
| 3333  | 1        | 1.47%   |
| 3000  | 1        | 1.47%   |
| 1867  | 1        | 1.47%   |
| 1067  | 1        | 1.47%   |
| 533   | 1        | 1.47%   |
| 400   | 1        | 1.47%   |

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
| Sunplus PAPALOOK_229AF                | 1        | 3.85%   |
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
| Alcor Micro SHUNCCM2MP                | 1        | 3.85%   |

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
| 0     | 122      | 89.05%  |
| 1     | 13       | 9.49%   |
| 2     | 2        | 1.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Graphics card      | 5        | 29.41%  |
| Net/wireless       | 3        | 17.65%  |
| Bluetooth          | 3        | 17.65%  |
| Unassigned class   | 2        | 11.76%  |
| Chipcard           | 2        | 11.76%  |
| Storage/raid       | 1        | 5.88%   |
| Fingerprint reader | 1        | 5.88%   |


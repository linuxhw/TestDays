Linux in Portugal - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

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

Total: 518

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME H510M-K               | [6fa51d2c4e](https://linux-hardware.org/?probe=6fa51d2c4e) | Aug 31, 2022 |
| OEM           | Intel H81                   | [4b45e6dc61](https://linux-hardware.org/?probe=4b45e6dc61) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | [08f930384d](https://linux-hardware.org/?probe=08f930384d) | Aug 25, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [ba3fb2513f](https://linux-hardware.org/?probe=ba3fb2513f) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [7ee8720a43](https://linux-hardware.org/?probe=7ee8720a43) | Aug 21, 2022 |
| MSI           | Z370 PC PRO                 | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| MSI           | B85M-E45                    | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| ASUSTek       | Basswood                    | [26e4efad3f](https://linux-hardware.org/?probe=26e4efad3f) | Aug 14, 2022 |
| ASRock        | H410M-HVS                   | [4d1acc8488](https://linux-hardware.org/?probe=4d1acc8488) | Aug 11, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| ASUSTek       | P8Z77-V                     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| ASUSTek       | P8H67                       | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| ASUSTek       | P5G41C-M LX                 | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [ae71cae955](https://linux-hardware.org/?probe=ae71cae955) | Jul 25, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [b3dbd37276](https://linux-hardware.org/?probe=b3dbd37276) | Jul 22, 2022 |
| MSI           | A78M-E45 V2                 | [c5007c5729](https://linux-hardware.org/?probe=c5007c5729) | Jul 22, 2022 |
| ASUSTek       | P8Z77-V                     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [e1313016ee](https://linux-hardware.org/?probe=e1313016ee) | Jul 17, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Acer          | FMCP7AM                     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [15088a414c](https://linux-hardware.org/?probe=15088a414c) | Jul 03, 2022 |
| MSI           | B450M BAZOOKA V2            | [bded0a2071](https://linux-hardware.org/?probe=bded0a2071) | Jul 03, 2022 |
| HP            | 8169                        | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| MSI           | A78M-E45 V2                 | [e4cd6586b4](https://linux-hardware.org/?probe=e4cd6586b4) | Jun 26, 2022 |
| Gigabyte      | H310M H                     | [90038bfa8e](https://linux-hardware.org/?probe=90038bfa8e) | Jun 22, 2022 |
| MSI           | A78M-E45 V2                 | [97b9d51036](https://linux-hardware.org/?probe=97b9d51036) | Jun 20, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| MSI           | A78M-E45 V2                 | [86394fa5df](https://linux-hardware.org/?probe=86394fa5df) | Jun 16, 2022 |
| MSI           | A78M-E45 V2                 | [a2d26ab800](https://linux-hardware.org/?probe=a2d26ab800) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | [70438d549d](https://linux-hardware.org/?probe=70438d549d) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | [56abd525d8](https://linux-hardware.org/?probe=56abd525d8) | Jun 14, 2022 |
| MSI           | B460M-A PRO                 | [c858bede94](https://linux-hardware.org/?probe=c858bede94) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| MSI           | MAG B550M BAZOOKA           | [9399a639c8](https://linux-hardware.org/?probe=9399a639c8) | May 29, 2022 |
| MSI           | MAG B550M BAZOOKA           | [42b16ce834](https://linux-hardware.org/?probe=42b16ce834) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | [4620e51e7b](https://linux-hardware.org/?probe=4620e51e7b) | May 28, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [ccf347729e](https://linux-hardware.org/?probe=ccf347729e) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASUSTek       | Maximus IV Extreme          | [08dedbb3cb](https://linux-hardware.org/?probe=08dedbb3cb) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a83bed6668](https://linux-hardware.org/?probe=a83bed6668) | May 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| ASRockRack    | X399D8A-2T                  | [f1d2fbc435](https://linux-hardware.org/?probe=f1d2fbc435) | May 12, 2022 |
| Gigabyte      | Z77P-D3                     | [40de59e6f7](https://linux-hardware.org/?probe=40de59e6f7) | May 10, 2022 |
| ASUSTek       | PRIME B360M-A               | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | M4A78LT-M                   | [2a10a13430](https://linux-hardware.org/?probe=2a10a13430) | May 06, 2022 |
| ASRock        | Z77 Pro3                    | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| MSI           | MS-7053                     | [6de132b805](https://linux-hardware.org/?probe=6de132b805) | May 02, 2022 |
| ASUSTek       | PRIME B360M-A               | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| HP            | 8719                        | [7e0ae3d91f](https://linux-hardware.org/?probe=7e0ae3d91f) | Apr 22, 2022 |
| ASUSTek       | P5G41T-M LX3                | [a21dad9ee4](https://linux-hardware.org/?probe=a21dad9ee4) | Apr 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | [278c76b54f](https://linux-hardware.org/?probe=278c76b54f) | Apr 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5f49d4d7d8](https://linux-hardware.org/?probe=5f49d4d7d8) | Apr 14, 2022 |
| ASUSTek       | P5G41T-M LX                 | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| Gigabyte      | B550 GAMING X V2            | [9493efcabe](https://linux-hardware.org/?probe=9493efcabe) | Apr 03, 2022 |
| Gigabyte      | G31M-ES2L                   | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| Gigabyte      | A520M H                     | [46b8c80485](https://linux-hardware.org/?probe=46b8c80485) | Mar 17, 2022 |
| ASUSTek       | B85M-E                      | [36c1044633](https://linux-hardware.org/?probe=36c1044633) | Mar 16, 2022 |
| Gigabyte      | A520M H                     | [483e47645c](https://linux-hardware.org/?probe=483e47645c) | Mar 16, 2022 |
| ASUSTek       | PRIME H510M-K               | [8a97b4f2d3](https://linux-hardware.org/?probe=8a97b4f2d3) | Mar 09, 2022 |
| HP            | 0A54h                       | [2dfc948414](https://linux-hardware.org/?probe=2dfc948414) | Mar 08, 2022 |
| Gigabyte      | G31M-S2L                    | [dd40993d97](https://linux-hardware.org/?probe=dd40993d97) | Mar 03, 2022 |
| HP            | 3396                        | [f952a8f044](https://linux-hardware.org/?probe=f952a8f044) | Mar 01, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | [8aa7469422](https://linux-hardware.org/?probe=8aa7469422) | Feb 27, 2022 |
| Biostar       | H81MHV3                     | [3fd07aef04](https://linux-hardware.org/?probe=3fd07aef04) | Feb 25, 2022 |
| ASUSTek       | PRIME X570-P                | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| IBM           | 819046G                     | [54b0798b76](https://linux-hardware.org/?probe=54b0798b76) | Feb 22, 2022 |
| ASUSTek       | P5VDC-X                     | [40943e3ee0](https://linux-hardware.org/?probe=40943e3ee0) | Feb 22, 2022 |
| HP            | 83F3                        | [9421f4385a](https://linux-hardware.org/?probe=9421f4385a) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [f7ee45924c](https://linux-hardware.org/?probe=f7ee45924c) | Feb 17, 2022 |
| ASRock        | B550M Pro4                  | [b39fbbaec6](https://linux-hardware.org/?probe=b39fbbaec6) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MS-7053                     | [2ee97bf0a8](https://linux-hardware.org/?probe=2ee97bf0a8) | Feb 13, 2022 |
| MSI           | H61M-P20                    | [81b315b229](https://linux-hardware.org/?probe=81b315b229) | Feb 09, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Foxconn       | H67M-S/H67M-V/H67           | [a3f3367577](https://linux-hardware.org/?probe=a3f3367577) | Feb 02, 2022 |
| ASUSTek       | P5K3L-ASUS-S1-P5G35         | [f9e7838b90](https://linux-hardware.org/?probe=f9e7838b90) | Jan 31, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [5b23faaf76](https://linux-hardware.org/?probe=5b23faaf76) | Jan 22, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [3791490565](https://linux-hardware.org/?probe=3791490565) | Jan 22, 2022 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [6cad862612](https://linux-hardware.org/?probe=6cad862612) | Jan 21, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| ASUSTek       | P5K PRO                     | [9338817523](https://linux-hardware.org/?probe=9338817523) | Jan 13, 2022 |
| ASUSTek       | V-P7H55E                    | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [409de37ae4](https://linux-hardware.org/?probe=409de37ae4) | Jan 09, 2022 |
| Gigabyte      | P41T-D3P                    | [1c94714d99](https://linux-hardware.org/?probe=1c94714d99) | Jan 01, 2022 |
| Google        | Sion                        | [08215c86b6](https://linux-hardware.org/?probe=08215c86b6) | Dec 31, 2021 |
| ASUSTek       | A_F_K31AN                   | [4bd56c7243](https://linux-hardware.org/?probe=4bd56c7243) | Dec 29, 2021 |
| RKM           | Cherry Trail CR             | [907cacf8cc](https://linux-hardware.org/?probe=907cacf8cc) | Dec 29, 2021 |
| Huanan        | X79-8D VAA31                | [79be6da608](https://linux-hardware.org/?probe=79be6da608) | Dec 26, 2021 |
| HP            | 1998                        | [fffadbe1cf](https://linux-hardware.org/?probe=fffadbe1cf) | Dec 25, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [855061aa1a](https://linux-hardware.org/?probe=855061aa1a) | Dec 18, 2021 |
| MSI           | MS-7053                     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [830b8475ac](https://linux-hardware.org/?probe=830b8475ac) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-P                | [1812d44a36](https://linux-hardware.org/?probe=1812d44a36) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Pegatron      | Benicia                     | [d50daedc5d](https://linux-hardware.org/?probe=d50daedc5d) | Nov 26, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [22f1f5326e](https://linux-hardware.org/?probe=22f1f5326e) | Nov 21, 2021 |
| Biostar       | FX9830M                     | [f845fe2694](https://linux-hardware.org/?probe=f845fe2694) | Nov 19, 2021 |
| Gigabyte      | G31M-ES2L                   | [f30f49d634](https://linux-hardware.org/?probe=f30f49d634) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [fccd73da9d](https://linux-hardware.org/?probe=fccd73da9d) | Nov 12, 2021 |
| Dell          | 0HD5W2 A00                  | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| Minix         | NEO Z83-4 V1.1              | [c7b52e35cf](https://linux-hardware.org/?probe=c7b52e35cf) | Nov 08, 2021 |
| ASUSTek       | H87M-PLUS                   | [72e74c86fb](https://linux-hardware.org/?probe=72e74c86fb) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | [bbb4e58192](https://linux-hardware.org/?probe=bbb4e58192) | Nov 04, 2021 |
| ASUSTek       | P5LD2-SE                    | [4f817c0167](https://linux-hardware.org/?probe=4f817c0167) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [b643635a41](https://linux-hardware.org/?probe=b643635a41) | Nov 02, 2021 |
| ASUSTek       | P5LD2-SE                    | [8ba60d9634](https://linux-hardware.org/?probe=8ba60d9634) | Nov 01, 2021 |
| MSI           | P55-CD53                    | [d342f4e0a4](https://linux-hardware.org/?probe=d342f4e0a4) | Oct 29, 2021 |
| ASUSTek       | A_F_K31AN                   | [ebd51400e3](https://linux-hardware.org/?probe=ebd51400e3) | Oct 25, 2021 |
| ASUSTek       | B85M-E                      | [7a6479dc2d](https://linux-hardware.org/?probe=7a6479dc2d) | Oct 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [7313df4bd9](https://linux-hardware.org/?probe=7313df4bd9) | Oct 17, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [005e2591e8](https://linux-hardware.org/?probe=005e2591e8) | Oct 17, 2021 |
| ASUSTek       | PRIME H510M-K               | [2ee0e02dca](https://linux-hardware.org/?probe=2ee0e02dca) | Oct 08, 2021 |
| ASUSTek       | H81M-A                      | [b73e4dc969](https://linux-hardware.org/?probe=b73e4dc969) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | [cc60b4cc30](https://linux-hardware.org/?probe=cc60b4cc30) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | [dae39c15c9](https://linux-hardware.org/?probe=dae39c15c9) | Oct 06, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [eeae519a3e](https://linux-hardware.org/?probe=eeae519a3e) | Oct 04, 2021 |
| ASRock        | B450M Pro4                  | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASUSTek       | P5KC                        | [c6c9f72f10](https://linux-hardware.org/?probe=c6c9f72f10) | Sep 29, 2021 |
| ASUSTek       | M4N68T-M                    | [adaee7ea4e](https://linux-hardware.org/?probe=adaee7ea4e) | Sep 28, 2021 |
| ASUSTek       | PRIME H510M-K               | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| ASUSTek       | PRIME X570-P                | [d8d6573dea](https://linux-hardware.org/?probe=d8d6573dea) | Sep 23, 2021 |
| Shuttle       | NC03U                       | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| Foxconn       | A74ML-K                     | [b7a9a59c77](https://linux-hardware.org/?probe=b7a9a59c77) | Sep 19, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a7a8c2cead](https://linux-hardware.org/?probe=a7a8c2cead) | Sep 18, 2021 |
| Biostar       | A68MHE                      | [8a2cdafa86](https://linux-hardware.org/?probe=8a2cdafa86) | Sep 18, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [82058974d9](https://linux-hardware.org/?probe=82058974d9) | Sep 17, 2021 |
| Libretrend    | LT1000                      | [781fa86fea](https://linux-hardware.org/?probe=781fa86fea) | Sep 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [e8ac4691b0](https://linux-hardware.org/?probe=e8ac4691b0) | Sep 16, 2021 |
| ASRock        | X570M Pro4                  | [297bbaf6a4](https://linux-hardware.org/?probe=297bbaf6a4) | Sep 14, 2021 |
| Acer          | Elena                       | [c05122b62f](https://linux-hardware.org/?probe=c05122b62f) | Sep 14, 2021 |
| ASUSTek       | B85M-E                      | [1ef0a151b1](https://linux-hardware.org/?probe=1ef0a151b1) | Sep 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | [4404093ccf](https://linux-hardware.org/?probe=4404093ccf) | Sep 12, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | [b92b2f815b](https://linux-hardware.org/?probe=b92b2f815b) | Sep 07, 2021 |
| ASUSTek       | P5L8L-SE                    | [32e39bbd4f](https://linux-hardware.org/?probe=32e39bbd4f) | Sep 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | [73edbfaf52](https://linux-hardware.org/?probe=73edbfaf52) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | [cefaaa7f19](https://linux-hardware.org/?probe=cefaaa7f19) | Sep 01, 2021 |
| ASRock        | 760GM-HDV                   | [7b2322353d](https://linux-hardware.org/?probe=7b2322353d) | Aug 29, 2021 |
| Unknown       | 1.0                         | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| ECS           | Livermore8                  | [a86f5a7745](https://linux-hardware.org/?probe=a86f5a7745) | Aug 18, 2021 |
| Unknown       | Unknown                     | [65ebd0006e](https://linux-hardware.org/?probe=65ebd0006e) | Aug 16, 2021 |
| ASUSTek       | P5P43TD PRO                 | [0576757382](https://linux-hardware.org/?probe=0576757382) | Aug 08, 2021 |
| Biostar       | A68MHE                      | [160e00a244](https://linux-hardware.org/?probe=160e00a244) | Aug 04, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [a6df82ec75](https://linux-hardware.org/?probe=a6df82ec75) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [b33ddef912](https://linux-hardware.org/?probe=b33ddef912) | Jul 30, 2021 |
| HP            | ProLiant ML350 G5           | [189789f8d5](https://linux-hardware.org/?probe=189789f8d5) | Jul 23, 2021 |
| Intel         | DH61WW AAG23116-206         | [bdd8ae093d](https://linux-hardware.org/?probe=bdd8ae093d) | Jul 21, 2021 |
| Dell          | 04MFRM A02                  | [9d92f05e1c](https://linux-hardware.org/?probe=9d92f05e1c) | Jul 17, 2021 |
| Dell          | 04MFRM A02                  | [2b2a31a2f9](https://linux-hardware.org/?probe=2b2a31a2f9) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [1056457127](https://linux-hardware.org/?probe=1056457127) | Jul 17, 2021 |
| ASUSTek       | Crosshair IV Formula        | [4004b6bcb6](https://linux-hardware.org/?probe=4004b6bcb6) | Jul 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | [1a9dfe2f20](https://linux-hardware.org/?probe=1a9dfe2f20) | Jul 16, 2021 |
| Gigabyte      | H110-D3A-CF                 | [e2a2b5ba07](https://linux-hardware.org/?probe=e2a2b5ba07) | Jul 13, 2021 |
| Gigabyte      | B365M HD3                   | [e663cfd24c](https://linux-hardware.org/?probe=e663cfd24c) | Jul 10, 2021 |
| ASRock        | N68-VS3 FX                  | [3bde956fe7](https://linux-hardware.org/?probe=3bde956fe7) | Jul 08, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [119260db14](https://linux-hardware.org/?probe=119260db14) | Jul 05, 2021 |
| ASUSTek       | P8H67-V                     | [66b161d8d5](https://linux-hardware.org/?probe=66b161d8d5) | Jul 02, 2021 |
| HP            | ProLiant ML350 G5           | [bc362bd630](https://linux-hardware.org/?probe=bc362bd630) | Jun 30, 2021 |
| ASRock        | H370M-ITX/ac                | [a6c720d609](https://linux-hardware.org/?probe=a6c720d609) | Jun 29, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [d2a4ffa502](https://linux-hardware.org/?probe=d2a4ffa502) | Jun 26, 2021 |
| MSI           | Z590-A PRO                  | [d6df0a85b4](https://linux-hardware.org/?probe=d6df0a85b4) | Jun 12, 2021 |
| MSI           | Z590-A PRO                  | [c7295eb580](https://linux-hardware.org/?probe=c7295eb580) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [d19e5c9398](https://linux-hardware.org/?probe=d19e5c9398) | Jun 11, 2021 |
| MSI           | B250 PC MATE                | [efa385c98c](https://linux-hardware.org/?probe=efa385c98c) | Jun 11, 2021 |
| ASUSTek       | D425MC                      | [aa893a2c50](https://linux-hardware.org/?probe=aa893a2c50) | Jun 10, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [599b4af4cf](https://linux-hardware.org/?probe=599b4af4cf) | Jun 06, 2021 |
| ASUSTek       | D425MC                      | [fc261e7b44](https://linux-hardware.org/?probe=fc261e7b44) | Jun 06, 2021 |
| Gigabyte      | Z77P-D3                     | [6a2bb03dcb](https://linux-hardware.org/?probe=6a2bb03dcb) | Jun 02, 2021 |
| ASUSTek       | D425MC                      | [d78ca41229](https://linux-hardware.org/?probe=d78ca41229) | Jun 01, 2021 |
| Gigabyte      | G41MT-S2                    | [5efbefcaa5](https://linux-hardware.org/?probe=5efbefcaa5) | May 30, 2021 |
| MSI           | Z490-A PRO                  | [654c105561](https://linux-hardware.org/?probe=654c105561) | May 28, 2021 |
| ASUSTek       | H110M-R                     | [62b22bfb20](https://linux-hardware.org/?probe=62b22bfb20) | May 26, 2021 |
| HP            | 3397                        | [ee57980b90](https://linux-hardware.org/?probe=ee57980b90) | May 25, 2021 |
| HP            | 1497                        | [7fa5ad3e42](https://linux-hardware.org/?probe=7fa5ad3e42) | May 25, 2021 |
| ASUSTek       | Z97-A                       | [0767c99abb](https://linux-hardware.org/?probe=0767c99abb) | May 19, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | [0548f9650b](https://linux-hardware.org/?probe=0548f9650b) | May 18, 2021 |
| MSI           | H270M BAZOOKA               | [c2fdd4a7da](https://linux-hardware.org/?probe=c2fdd4a7da) | May 06, 2021 |
| ASUSTek       | P5S-MX SE                   | [2853189089](https://linux-hardware.org/?probe=2853189089) | May 01, 2021 |
| ASUSTek       | P5S-MX SE                   | [0d40576169](https://linux-hardware.org/?probe=0d40576169) | Apr 27, 2021 |
| NEC Comput... | PALOMAR                     | [3eebff8fad](https://linux-hardware.org/?probe=3eebff8fad) | Apr 16, 2021 |
| ASUSTek       | P9X79                       | [e9636d21ef](https://linux-hardware.org/?probe=e9636d21ef) | Apr 15, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f0a9a9b376](https://linux-hardware.org/?probe=f0a9a9b376) | Apr 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [0f16d1f407](https://linux-hardware.org/?probe=0f16d1f407) | Apr 15, 2021 |
| MSI           | 760GA-P43                   | [f836b01395](https://linux-hardware.org/?probe=f836b01395) | Apr 14, 2021 |
| ASUSTek       | P5KC                        | [b9b6d74f4e](https://linux-hardware.org/?probe=b9b6d74f4e) | Apr 13, 2021 |
| Dell          | 0FH884                      | [93acc58efb](https://linux-hardware.org/?probe=93acc58efb) | Apr 10, 2021 |
| NEC Comput... | PALOMAR                     | [69d2761186](https://linux-hardware.org/?probe=69d2761186) | Apr 09, 2021 |
| ASUSTek       | P5KC                        | [2147d0b585](https://linux-hardware.org/?probe=2147d0b585) | Apr 08, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [3a66ababd9](https://linux-hardware.org/?probe=3a66ababd9) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [9b436e3e3c](https://linux-hardware.org/?probe=9b436e3e3c) | Apr 07, 2021 |
| Dell          | 0G261D A00                  | [8b417f82c5](https://linux-hardware.org/?probe=8b417f82c5) | Apr 06, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ed7761776f](https://linux-hardware.org/?probe=ed7761776f) | Apr 02, 2021 |
| ASUSTek       | PRIME B450M-A II            | [292671b8bb](https://linux-hardware.org/?probe=292671b8bb) | Mar 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [25b48fc578](https://linux-hardware.org/?probe=25b48fc578) | Mar 26, 2021 |
| ASUSTek       | P8H67-M LE                  | [d85cd54281](https://linux-hardware.org/?probe=d85cd54281) | Mar 21, 2021 |
| Gigabyte      | G41M-Combo                  | [b5838dd904](https://linux-hardware.org/?probe=b5838dd904) | Mar 20, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [d699973a80](https://linux-hardware.org/?probe=d699973a80) | Mar 15, 2021 |
| Pegatron      | 2A94h                       | [3b44f86cb2](https://linux-hardware.org/?probe=3b44f86cb2) | Mar 14, 2021 |
| ASRock        | A520M-HDV                   | [53bee57a08](https://linux-hardware.org/?probe=53bee57a08) | Mar 14, 2021 |
| MSI           | X470 GAMING PRO             | [d80b4b42b5](https://linux-hardware.org/?probe=d80b4b42b5) | Mar 10, 2021 |
| ASUSTek       | P5G41T-M LE                 | [a4382b583f](https://linux-hardware.org/?probe=a4382b583f) | Mar 09, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [aeb9dde634](https://linux-hardware.org/?probe=aeb9dde634) | Mar 09, 2021 |
| Acer          | FMCP7AM                     | [0f4686671e](https://linux-hardware.org/?probe=0f4686671e) | Mar 05, 2021 |
| ASUSTek       | A_F_K31DA_K31DAG_K20DA      | [84d8d1fd23](https://linux-hardware.org/?probe=84d8d1fd23) | Mar 03, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [f2186654a5](https://linux-hardware.org/?probe=f2186654a5) | Mar 03, 2021 |
| HP            | 3646h                       | [ae2d7f8ca8](https://linux-hardware.org/?probe=ae2d7f8ca8) | Mar 02, 2021 |
| Dell          | 0FH884                      | [e8894d16b4](https://linux-hardware.org/?probe=e8894d16b4) | Mar 02, 2021 |
| HP            | 08B8h                       | [c6f567409e](https://linux-hardware.org/?probe=c6f567409e) | Mar 02, 2021 |
| Acer          | FMCP7AM                     | [e73467285a](https://linux-hardware.org/?probe=e73467285a) | Mar 01, 2021 |
| Dell          | 0FH884                      | [3f73f703ea](https://linux-hardware.org/?probe=3f73f703ea) | Feb 25, 2021 |
| Dell          | 0FH884                      | [9ef7d7ac26](https://linux-hardware.org/?probe=9ef7d7ac26) | Feb 24, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [e0b5fd0d0f](https://linux-hardware.org/?probe=e0b5fd0d0f) | Feb 22, 2021 |
| BCM           | RX965Q                      | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a4096f684a](https://linux-hardware.org/?probe=a4096f684a) | Feb 21, 2021 |
| Lenovo        | MAHOBAY NOK                 | [517098f97e](https://linux-hardware.org/?probe=517098f97e) | Feb 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [aadae3018a](https://linux-hardware.org/?probe=aadae3018a) | Feb 19, 2021 |
| ASRock        | AB350M Pro4                 | [427b038f6c](https://linux-hardware.org/?probe=427b038f6c) | Feb 16, 2021 |
| MSI           | MS-7145                     | [9339e94272](https://linux-hardware.org/?probe=9339e94272) | Feb 15, 2021 |
| ASRock        | J3455M                      | [3858448941](https://linux-hardware.org/?probe=3858448941) | Feb 15, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [5e21989251](https://linux-hardware.org/?probe=5e21989251) | Feb 14, 2021 |
| HP            | 2B36                        | [822dd71f17](https://linux-hardware.org/?probe=822dd71f17) | Feb 14, 2021 |
| Acer          | Aspire X1900                | [15ea004f33](https://linux-hardware.org/?probe=15ea004f33) | Feb 14, 2021 |
| MSI           | 890FXA-GD70                 | [ea6af67da0](https://linux-hardware.org/?probe=ea6af67da0) | Feb 13, 2021 |
| MSI           | G41M-P43 Combo              | [9854e43724](https://linux-hardware.org/?probe=9854e43724) | Feb 11, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [039362868b](https://linux-hardware.org/?probe=039362868b) | Feb 03, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [4c1fa69861](https://linux-hardware.org/?probe=4c1fa69861) | Feb 03, 2021 |
| MSI           | B360 GAMING PLUS            | [f409735b4a](https://linux-hardware.org/?probe=f409735b4a) | Feb 01, 2021 |
| ASRock        | AB350M Pro4                 | [f82376b2fc](https://linux-hardware.org/?probe=f82376b2fc) | Feb 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [159f94f03e](https://linux-hardware.org/?probe=159f94f03e) | Jan 29, 2021 |
| Dell          | 0GU083 A00                  | [b56844119d](https://linux-hardware.org/?probe=b56844119d) | Jan 29, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [273c518e4f](https://linux-hardware.org/?probe=273c518e4f) | Jan 28, 2021 |
| ASUSTek       | PRIME B350M-A               | [511b309049](https://linux-hardware.org/?probe=511b309049) | Jan 27, 2021 |
| MSI           | A320M PRO-VD/S              | [b0c09b63f4](https://linux-hardware.org/?probe=b0c09b63f4) | Jan 18, 2021 |
| MSI           | A320M PRO-VD/S              | [48710cf657](https://linux-hardware.org/?probe=48710cf657) | Jan 18, 2021 |
| ASUSTek       | P5SD2-VM                    | [9847d231eb](https://linux-hardware.org/?probe=9847d231eb) | Jan 14, 2021 |
| ASUSTek       | P5SD2-VM                    | [ee830fe216](https://linux-hardware.org/?probe=ee830fe216) | Jan 12, 2021 |
| ASUSTek       | P5G41T-M LX                 | [4db19bc22f](https://linux-hardware.org/?probe=4db19bc22f) | Jan 09, 2021 |
| HP            | 3397                        | [4c8e59bc44](https://linux-hardware.org/?probe=4c8e59bc44) | Jan 09, 2021 |
| HP            | Asterope                    | [9d863bfc8f](https://linux-hardware.org/?probe=9d863bfc8f) | Jan 08, 2021 |
| ASRock        | 775Dual-VSTA                | [e45a885545](https://linux-hardware.org/?probe=e45a885545) | Jan 03, 2021 |
| ASUSTek       | H87M-E                      | [d5d1562a32](https://linux-hardware.org/?probe=d5d1562a32) | Jan 01, 2021 |
| ASUSTek       | H87M-E                      | [b4a1983b91](https://linux-hardware.org/?probe=b4a1983b91) | Dec 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [660a038a14](https://linux-hardware.org/?probe=660a038a14) | Dec 23, 2020 |
| Dell          | 0RF703                      | [6f883fe6f5](https://linux-hardware.org/?probe=6f883fe6f5) | Dec 20, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [609543807e](https://linux-hardware.org/?probe=609543807e) | Dec 19, 2020 |
| Gigabyte      | P75-D3                      | [e50b2ea863](https://linux-hardware.org/?probe=e50b2ea863) | Dec 16, 2020 |
| ASUSTek       | B150M PRO GAMING            | [50e588847b](https://linux-hardware.org/?probe=50e588847b) | Dec 16, 2020 |
| HP            | 3031h                       | [b1c4657359](https://linux-hardware.org/?probe=b1c4657359) | Dec 16, 2020 |
| ASUSTek       | H87M-E                      | [ba189ceaa2](https://linux-hardware.org/?probe=ba189ceaa2) | Dec 14, 2020 |
| Intel         | D865GSA AAD53275-204        | [1decb62bf9](https://linux-hardware.org/?probe=1decb62bf9) | Dec 13, 2020 |
| Intel         | D865GSA AAD53275-204        | [b94183234b](https://linux-hardware.org/?probe=b94183234b) | Dec 13, 2020 |
| MSI           | X470 GAMING PRO             | [b910c55313](https://linux-hardware.org/?probe=b910c55313) | Dec 01, 2020 |
| ASUSTek       | D425MC                      | [a2a7090e43](https://linux-hardware.org/?probe=a2a7090e43) | Nov 23, 2020 |
| MSI           | 990FXA GAMING               | [c67dd69ea3](https://linux-hardware.org/?probe=c67dd69ea3) | Nov 21, 2020 |
| MSI           | 990FXA GAMING               | [7b6ef87411](https://linux-hardware.org/?probe=7b6ef87411) | Nov 21, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [3914e82da0](https://linux-hardware.org/?probe=3914e82da0) | Nov 14, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [65b64eedcc](https://linux-hardware.org/?probe=65b64eedcc) | Nov 13, 2020 |
| Gigabyte      | F2A68HM-DS2                 | [a255bdcfbc](https://linux-hardware.org/?probe=a255bdcfbc) | Nov 12, 2020 |
| ASUSTek       | D425MC                      | [50665babae](https://linux-hardware.org/?probe=50665babae) | Nov 09, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [4abd6c9e42](https://linux-hardware.org/?probe=4abd6c9e42) | Nov 08, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [0e4becb647](https://linux-hardware.org/?probe=0e4becb647) | Nov 06, 2020 |
| MSI           | G41M-P43 Combo              | [1d92dd04a2](https://linux-hardware.org/?probe=1d92dd04a2) | Oct 30, 2020 |
| ASUSTek       | P5G41T-M LE                 | [5d0df96501](https://linux-hardware.org/?probe=5d0df96501) | Oct 29, 2020 |
| ASUSTek       | P5G41T-M LE                 | [e4af11643b](https://linux-hardware.org/?probe=e4af11643b) | Oct 29, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [20acead566](https://linux-hardware.org/?probe=20acead566) | Oct 26, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [4b14ad2894](https://linux-hardware.org/?probe=4b14ad2894) | Oct 25, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | [8136a41002](https://linux-hardware.org/?probe=8136a41002) | Oct 24, 2020 |
| ASUSTek       | P8P67                       | [17105ed101](https://linux-hardware.org/?probe=17105ed101) | Oct 23, 2020 |
| ASUSTek       | B85M-E                      | [b6190da277](https://linux-hardware.org/?probe=b6190da277) | Oct 23, 2020 |
| ASUSTek       | H110M-K                     | [08c91cec4d](https://linux-hardware.org/?probe=08c91cec4d) | Oct 21, 2020 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [b2c4383da1](https://linux-hardware.org/?probe=b2c4383da1) | Oct 20, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [12fab28ee5](https://linux-hardware.org/?probe=12fab28ee5) | Oct 14, 2020 |
| ASUSTek       | P5LD2-SE                    | [53e64ff105](https://linux-hardware.org/?probe=53e64ff105) | Oct 12, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [bfe6259c0c](https://linux-hardware.org/?probe=bfe6259c0c) | Oct 12, 2020 |
| ASUSTek       | Salmon                      | [1a9191eedc](https://linux-hardware.org/?probe=1a9191eedc) | Oct 12, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [19ef25af06](https://linux-hardware.org/?probe=19ef25af06) | Oct 09, 2020 |
| ASUSTek       | P5G41C-M LX                 | [d8d853d435](https://linux-hardware.org/?probe=d8d853d435) | Oct 09, 2020 |
| ASUSTek       | P8Z77-V LK                  | [490b10c9b5](https://linux-hardware.org/?probe=490b10c9b5) | Oct 03, 2020 |
| ASUSTek       | P9X79                       | [0cca3e59e7](https://linux-hardware.org/?probe=0cca3e59e7) | Oct 02, 2020 |
| MSI           | B350 PC MATE                | [fb4c90c999](https://linux-hardware.org/?probe=fb4c90c999) | Oct 02, 2020 |
| Foxconn       | 2ACA                        | [d1ca27b882](https://linux-hardware.org/?probe=d1ca27b882) | Oct 02, 2020 |
| ASUSTek       | Salmon                      | [67ec1c9e21](https://linux-hardware.org/?probe=67ec1c9e21) | Sep 30, 2020 |
| MSI           | B450M MORTAR                | [eb4023b66b](https://linux-hardware.org/?probe=eb4023b66b) | Sep 29, 2020 |
| MSI           | B150M MORTAR                | [1919443ef9](https://linux-hardware.org/?probe=1919443ef9) | Sep 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [aa8ff9653f](https://linux-hardware.org/?probe=aa8ff9653f) | Sep 28, 2020 |
| Medion        | MS-7728                     | [27aa2e9b05](https://linux-hardware.org/?probe=27aa2e9b05) | Sep 28, 2020 |
| MSI           | B350M BAZOOKA               | [bc99ab4879](https://linux-hardware.org/?probe=bc99ab4879) | Sep 28, 2020 |
| ASUSTek       | P8H61-M LX                  | [f6ce95194c](https://linux-hardware.org/?probe=f6ce95194c) | Sep 27, 2020 |
| ASRock        | 775Dual-VSTA                | [40ed4cc83b](https://linux-hardware.org/?probe=40ed4cc83b) | Sep 24, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [1abfd8ee8e](https://linux-hardware.org/?probe=1abfd8ee8e) | Sep 23, 2020 |
| ASUSTek       | Z97-A                       | [caef8bbdd2](https://linux-hardware.org/?probe=caef8bbdd2) | Sep 23, 2020 |
| ASRock        | X399 Taichi                 | [785a16d818](https://linux-hardware.org/?probe=785a16d818) | Sep 18, 2020 |
| ASUSTek       | P5GC-MX/1333                | [dc4566d1a7](https://linux-hardware.org/?probe=dc4566d1a7) | Sep 16, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [deaed50282](https://linux-hardware.org/?probe=deaed50282) | Sep 04, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [24077cd964](https://linux-hardware.org/?probe=24077cd964) | Sep 03, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [b084c1b4b6](https://linux-hardware.org/?probe=b084c1b4b6) | Aug 29, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [6fbe8eb952](https://linux-hardware.org/?probe=6fbe8eb952) | Aug 29, 2020 |
| Foxconn       | 2ACA                        | [3293f910eb](https://linux-hardware.org/?probe=3293f910eb) | Aug 26, 2020 |
| Foxconn       | 2ACA                        | [20eb163379](https://linux-hardware.org/?probe=20eb163379) | Aug 26, 2020 |
| Gigabyte      | G31M-ES2L                   | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| Gigabyte      | EP45C-DS3R                  | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| ASUSTek       | P8H61-M LX                  | [dcc65ae2a7](https://linux-hardware.org/?probe=dcc65ae2a7) | Aug 23, 2020 |
| ASUSTek       | B85M-E                      | [cb8240a746](https://linux-hardware.org/?probe=cb8240a746) | Aug 21, 2020 |
| ASUSTek       | P5KPL-AM IN/GB              | [004f0c4c8d](https://linux-hardware.org/?probe=004f0c4c8d) | Aug 19, 2020 |
| Gigabyte      | B75M-D3V                    | [a8a68b1821](https://linux-hardware.org/?probe=a8a68b1821) | Aug 10, 2020 |
| MSI           | G41M-P43 Combo              | [312331a2e9](https://linux-hardware.org/?probe=312331a2e9) | Aug 10, 2020 |
| ASRock        | B450M Pro4-F                | [bd00a821fd](https://linux-hardware.org/?probe=bd00a821fd) | Aug 07, 2020 |
| ASUSTek       | H87M-PLUS                   | [82f189206f](https://linux-hardware.org/?probe=82f189206f) | Aug 03, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [fff6cf2563](https://linux-hardware.org/?probe=fff6cf2563) | Aug 02, 2020 |
| ASRock        | 775Dual-VSTA                | [a2ad60fd2b](https://linux-hardware.org/?probe=a2ad60fd2b) | Aug 01, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [b981971204](https://linux-hardware.org/?probe=b981971204) | Aug 01, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2195cd2a66](https://linux-hardware.org/?probe=2195cd2a66) | Aug 01, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e834a1db4](https://linux-hardware.org/?probe=5e834a1db4) | Jul 26, 2020 |
| ASUSTek       | B85M-E                      | [d745653595](https://linux-hardware.org/?probe=d745653595) | Jul 25, 2020 |
| MSI           | H81M-E33                    | [2ea88d42b6](https://linux-hardware.org/?probe=2ea88d42b6) | Jul 24, 2020 |
| Intel         | H81                         | [cd0d9e970b](https://linux-hardware.org/?probe=cd0d9e970b) | Jul 24, 2020 |
| ASUSTek       | P5VD2-MX                    | [b145b99009](https://linux-hardware.org/?probe=b145b99009) | Jul 24, 2020 |
| MSI           | B450 TOMAHAWK               | [b76c563f0f](https://linux-hardware.org/?probe=b76c563f0f) | Jul 24, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [9f64ca3b62](https://linux-hardware.org/?probe=9f64ca3b62) | Jul 24, 2020 |
| ASUSTek       | H110M-K                     | [8aeea51ed4](https://linux-hardware.org/?probe=8aeea51ed4) | Jul 24, 2020 |
| ASUSTek       | B85M-E                      | [256e33e5db](https://linux-hardware.org/?probe=256e33e5db) | Jul 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | [df67dac45a](https://linux-hardware.org/?probe=df67dac45a) | Jul 23, 2020 |
| ASUSTek       | PRIME Z390-P                | [fcea9afdb8](https://linux-hardware.org/?probe=fcea9afdb8) | Jul 18, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [ed3275a3ef](https://linux-hardware.org/?probe=ed3275a3ef) | Jul 13, 2020 |
| ASUSTek       | P8H61-M                     | [a96a1f0249](https://linux-hardware.org/?probe=a96a1f0249) | Jul 08, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [b5a22259cb](https://linux-hardware.org/?probe=b5a22259cb) | Jul 06, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [3194e779dc](https://linux-hardware.org/?probe=3194e779dc) | Jul 05, 2020 |
| Acer          | Aspire M3910                | [574212361b](https://linux-hardware.org/?probe=574212361b) | Jun 28, 2020 |
| ASRock        | AB350M Pro4                 | [14e2fc82a2](https://linux-hardware.org/?probe=14e2fc82a2) | Jun 25, 2020 |
| Dell          | 09WH54 A00                  | [5c11bd4168](https://linux-hardware.org/?probe=5c11bd4168) | Jun 21, 2020 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [edab290676](https://linux-hardware.org/?probe=edab290676) | Jun 20, 2020 |
| ASUSTek       | H110M-K                     | [4d9b1b16c1](https://linux-hardware.org/?probe=4d9b1b16c1) | Jun 16, 2020 |
| HP            | 0A60h                       | [51cea91fd2](https://linux-hardware.org/?probe=51cea91fd2) | Jun 13, 2020 |
| ASRock        | 775Dual-VSTA                | [0e5ac5a0bf](https://linux-hardware.org/?probe=0e5ac5a0bf) | Jun 12, 2020 |
| HP            | 8436                        | [a714970832](https://linux-hardware.org/?probe=a714970832) | Jun 11, 2020 |
| HP            | 843B                        | [dddd13622f](https://linux-hardware.org/?probe=dddd13622f) | Jun 10, 2020 |
| MSI           | G41M-P26                    | [01089d258b](https://linux-hardware.org/?probe=01089d258b) | Jun 09, 2020 |
| ASUSTek       | H110M-K                     | [e87bd7a1e6](https://linux-hardware.org/?probe=e87bd7a1e6) | Jun 09, 2020 |
| ASRock        | 775Dual-VSTA                | [a4f3841c00](https://linux-hardware.org/?probe=a4f3841c00) | May 29, 2020 |
| Gigabyte      | B75M-D3H                    | [2e9b2bd361](https://linux-hardware.org/?probe=2e9b2bd361) | May 26, 2020 |
| ASUSTek       | PRIME A320M-K               | [2b0f0312d9](https://linux-hardware.org/?probe=2b0f0312d9) | May 20, 2020 |
| HP            | 0A54h                       | [0eb9ef0dd8](https://linux-hardware.org/?probe=0eb9ef0dd8) | May 18, 2020 |
| HP            | 0A54h                       | [c6dfcc177a](https://linux-hardware.org/?probe=c6dfcc177a) | May 17, 2020 |
| MSI           | B150M BAZOOKA PLUS          | [6042465eaf](https://linux-hardware.org/?probe=6042465eaf) | May 10, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b03c78fe4f](https://linux-hardware.org/?probe=b03c78fe4f) | May 09, 2020 |
| HP            | 3397                        | [3e224cf71e](https://linux-hardware.org/?probe=3e224cf71e) | May 07, 2020 |
| ASRock        | 775Dual-VSTA                | [3fe70d9fdd](https://linux-hardware.org/?probe=3fe70d9fdd) | May 06, 2020 |
| HP            | 8436                        | [cca70af9c6](https://linux-hardware.org/?probe=cca70af9c6) | May 05, 2020 |
| Acer          | Aspire X1900                | [8504ed80cb](https://linux-hardware.org/?probe=8504ed80cb) | May 05, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [7e0d4adca9](https://linux-hardware.org/?probe=7e0d4adca9) | May 04, 2020 |
| MSI           | 970A SLI Krait Edition      | [019e7deab8](https://linux-hardware.org/?probe=019e7deab8) | May 02, 2020 |
| HP            | 0AE8h C                     | [94f0b85b34](https://linux-hardware.org/?probe=94f0b85b34) | May 01, 2020 |
| ASRock        | 775Dual-VSTA                | [8fa9935547](https://linux-hardware.org/?probe=8fa9935547) | Apr 27, 2020 |
| Gigabyte      | B75M-D3V                    | [997cebc492](https://linux-hardware.org/?probe=997cebc492) | Apr 26, 2020 |
| Gigabyte      | B75M-D3V                    | [0001f7367a](https://linux-hardware.org/?probe=0001f7367a) | Apr 25, 2020 |
| Intel         | H81                         | [20f12251b6](https://linux-hardware.org/?probe=20f12251b6) | Apr 24, 2020 |
| ECS           | Nettle2                     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [4389b84dc5](https://linux-hardware.org/?probe=4389b84dc5) | Apr 16, 2020 |
| ASUSTek       | P5LD2-SE                    | [6d04e1a950](https://linux-hardware.org/?probe=6d04e1a950) | Apr 13, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b70c50223a](https://linux-hardware.org/?probe=b70c50223a) | Apr 13, 2020 |
| MSI           | AMETHYST-M                  | [d42d07bebb](https://linux-hardware.org/?probe=d42d07bebb) | Apr 13, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [8ceac6a75e](https://linux-hardware.org/?probe=8ceac6a75e) | Apr 13, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [6b51a788d2](https://linux-hardware.org/?probe=6b51a788d2) | Apr 13, 2020 |
| MSI           | AMETHYST-M                  | [7c3997226d](https://linux-hardware.org/?probe=7c3997226d) | Apr 12, 2020 |
| ASUSTek       | M5A78L-M LX3                | [946ccde46f](https://linux-hardware.org/?probe=946ccde46f) | Apr 11, 2020 |
| Dell          | 0D28YY A00                  | [df89132283](https://linux-hardware.org/?probe=df89132283) | Apr 07, 2020 |
| Dell          | 0D28YY A00                  | [b87bc42bd0](https://linux-hardware.org/?probe=b87bc42bd0) | Apr 07, 2020 |
| Gigabyte      | B450M S2H                   | [1d19709a92](https://linux-hardware.org/?probe=1d19709a92) | Apr 07, 2020 |
| eMachines     | EMCP73M                     | [7ff7403af5](https://linux-hardware.org/?probe=7ff7403af5) | Apr 05, 2020 |
| ASUSTek       | P5LD2-SE                    | [21301abfd3](https://linux-hardware.org/?probe=21301abfd3) | Apr 03, 2020 |
| ASUSTek       | H97M-PLUS                   | [f33249c23f](https://linux-hardware.org/?probe=f33249c23f) | Apr 02, 2020 |
| ASUSTek       | A88X-PLUS                   | [eca8e2e768](https://linux-hardware.org/?probe=eca8e2e768) | Apr 02, 2020 |
| Dell          | 0D28YY A00                  | [616bad5cf3](https://linux-hardware.org/?probe=616bad5cf3) | Apr 01, 2020 |
| Gigabyte      | H310M H x.x                 | [b162dadd40](https://linux-hardware.org/?probe=b162dadd40) | Apr 01, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ec95a666d](https://linux-hardware.org/?probe=6ec95a666d) | Apr 01, 2020 |
| MSI           | MS-7341 10                  | [05450f5d8f](https://linux-hardware.org/?probe=05450f5d8f) | Mar 26, 2020 |
| MSI           | MS-7341 10                  | [98321d452d](https://linux-hardware.org/?probe=98321d452d) | Mar 21, 2020 |
| Acer          | RS740DVF                    | [93b6fee4e0](https://linux-hardware.org/?probe=93b6fee4e0) | Mar 12, 2020 |
| Acer          | RS740DVF                    | [be9d829372](https://linux-hardware.org/?probe=be9d829372) | Mar 11, 2020 |
| ASUSTek       | Z97-A                       | [40aef28c8a](https://linux-hardware.org/?probe=40aef28c8a) | Mar 08, 2020 |
| ASUSTek       | P5Q SE/R                    | [e7178ba8e7](https://linux-hardware.org/?probe=e7178ba8e7) | Mar 06, 2020 |
| AMI           | Cherry Trail CR             | [7f33611531](https://linux-hardware.org/?probe=7f33611531) | Mar 06, 2020 |
| AMI           | Cherry Trail CR             | [6ba8797a59](https://linux-hardware.org/?probe=6ba8797a59) | Mar 06, 2020 |
| Gigabyte      | H310M H x.x                 | [e5d85d26dd](https://linux-hardware.org/?probe=e5d85d26dd) | Mar 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [e302ca148e](https://linux-hardware.org/?probe=e302ca148e) | Mar 05, 2020 |
| Acer          | RS740DVF                    | [aeb499b9d4](https://linux-hardware.org/?probe=aeb499b9d4) | Mar 04, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | [b822a2ccbc](https://linux-hardware.org/?probe=b822a2ccbc) | Mar 02, 2020 |
| ASUSTek       | M3N-H/HDMI                  | [4b08896af8](https://linux-hardware.org/?probe=4b08896af8) | Mar 01, 2020 |
| ASUSTek       | P5G41T-M LX                 | [900ebfc65f](https://linux-hardware.org/?probe=900ebfc65f) | Mar 01, 2020 |
| MSI           | 970A GAMING PRO CARBON      | [84a38bd601](https://linux-hardware.org/?probe=84a38bd601) | Mar 01, 2020 |
| ASUSTek       | P5G41T-M LX                 | [f29225f74c](https://linux-hardware.org/?probe=f29225f74c) | Feb 24, 2020 |
| Medion        | MS-7366                     | [63d7b30a5a](https://linux-hardware.org/?probe=63d7b30a5a) | Feb 23, 2020 |
| Medion        | MS-7366                     | [ca03901ede](https://linux-hardware.org/?probe=ca03901ede) | Feb 23, 2020 |
| ASUSTek       | P5G41T-M LX                 | [e60551ae18](https://linux-hardware.org/?probe=e60551ae18) | Feb 22, 2020 |
| HP            | 2B36                        | [9e63f29da5](https://linux-hardware.org/?probe=9e63f29da5) | Feb 17, 2020 |
| Gigabyte      | G1.Sniper B6-CF             | [34bc4e6ef8](https://linux-hardware.org/?probe=34bc4e6ef8) | Feb 07, 2020 |
| Gigabyte      | G1.Sniper B6-CF             | [dcb876e046](https://linux-hardware.org/?probe=dcb876e046) | Feb 07, 2020 |
| ASUSTek       | P5LD2-VM                    | [3b118987fd](https://linux-hardware.org/?probe=3b118987fd) | Feb 03, 2020 |
| ASUSTek       | P5LD2-VM                    | [7eb3d3f57c](https://linux-hardware.org/?probe=7eb3d3f57c) | Jan 27, 2020 |
| HP            | 843B                        | [603aa1061c](https://linux-hardware.org/?probe=603aa1061c) | Jan 26, 2020 |
| HP            | 843B                        | [3673691cb2](https://linux-hardware.org/?probe=3673691cb2) | Jan 24, 2020 |
| HP            | 843B                        | [19231872c2](https://linux-hardware.org/?probe=19231872c2) | Jan 24, 2020 |
| Gigabyte      | B450M S2H                   | [ce8c8e3437](https://linux-hardware.org/?probe=ce8c8e3437) | Jan 19, 2020 |
| ASRock        | N68C-GS FX                  | [ed869b8762](https://linux-hardware.org/?probe=ed869b8762) | Jan 16, 2020 |
| ASRock        | N68-GS4/USB3 FX R2.0        | [1a903c9d61](https://linux-hardware.org/?probe=1a903c9d61) | Jan 14, 2020 |
| Huanan        | X79 VAA1                    | [bf970865ee](https://linux-hardware.org/?probe=bf970865ee) | Jan 13, 2020 |
| Dell          | 0GU083 A00                  | [f0711f3888](https://linux-hardware.org/?probe=f0711f3888) | Jan 10, 2020 |
| ASUSTek       | P5K SE/EPU                  | [5ee0f1db4c](https://linux-hardware.org/?probe=5ee0f1db4c) | Dec 19, 2019 |
| ASUSTek       | P5K SE/EPU                  | [9761122ab6](https://linux-hardware.org/?probe=9761122ab6) | Dec 17, 2019 |
| ASUSTek       | PRIME B250M-A               | [ae2fce57b5](https://linux-hardware.org/?probe=ae2fce57b5) | Dec 15, 2019 |
| Gigabyte      | B450M S2H                   | [65309beec0](https://linux-hardware.org/?probe=65309beec0) | Dec 09, 2019 |
| Gigabyte      | B450M S2H                   | [69cdd45ef3](https://linux-hardware.org/?probe=69cdd45ef3) | Dec 07, 2019 |
| Gigabyte      | B450M S2H                   | [985f0a93d2](https://linux-hardware.org/?probe=985f0a93d2) | Dec 07, 2019 |
| ASRock        | ConRoe945G-DVI              | [984156a325](https://linux-hardware.org/?probe=984156a325) | Dec 05, 2019 |
| ASUSTek       | P5KPL-AM SE                 | [e62db6e4e2](https://linux-hardware.org/?probe=e62db6e4e2) | Dec 02, 2019 |
| ASUSTek       | PRIME B250M-A               | [636cf95a59](https://linux-hardware.org/?probe=636cf95a59) | Nov 28, 2019 |
| Gigabyte      | B450M S2H                   | [e08baa017d](https://linux-hardware.org/?probe=e08baa017d) | Nov 23, 2019 |
| MSI           | 760GA-P43                   | [8e365df17f](https://linux-hardware.org/?probe=8e365df17f) | Nov 23, 2019 |
| Gigabyte      | G31M-ES2L                   | [0a1bc31c2a](https://linux-hardware.org/?probe=0a1bc31c2a) | Nov 19, 2019 |
| MSI           | B360M PRO-VDH               | [f83d0a812d](https://linux-hardware.org/?probe=f83d0a812d) | Nov 15, 2019 |
| Gigabyte      | AX370M-Gaming 3-CF          | [1679a050fb](https://linux-hardware.org/?probe=1679a050fb) | Nov 15, 2019 |
| Gigabyte      | AX370M-Gaming 3-CF          | [7850ee9963](https://linux-hardware.org/?probe=7850ee9963) | Nov 14, 2019 |
| ASUSTek       | P7H55-M                     | [376e73248b](https://linux-hardware.org/?probe=376e73248b) | Nov 10, 2019 |
| ASUSTek       | P7H55-M                     | [79e7d0b350](https://linux-hardware.org/?probe=79e7d0b350) | Nov 10, 2019 |
| Gigabyte      | B450M S2H                   | [b90be9510c](https://linux-hardware.org/?probe=b90be9510c) | Nov 07, 2019 |
| ASUSTek       | PRIME B250M-A               | [eb9fc83248](https://linux-hardware.org/?probe=eb9fc83248) | Nov 04, 2019 |
| ASUSTek       | PRIME B250M-A               | [1300445d89](https://linux-hardware.org/?probe=1300445d89) | Nov 03, 2019 |
| ASUSTek       | P5P43TD PRO                 | [b56c2b2e60](https://linux-hardware.org/?probe=b56c2b2e60) | Nov 02, 2019 |
| Dell          | 0KWVT8 A02                  | [6ed3187d7a](https://linux-hardware.org/?probe=6ed3187d7a) | Nov 01, 2019 |
| Intel         | D945GCZ AAC99321-502        | [9939882441](https://linux-hardware.org/?probe=9939882441) | Oct 15, 2019 |
| Intel         | D945GCZ AAC99321-502        | [7062600603](https://linux-hardware.org/?probe=7062600603) | Oct 15, 2019 |
| eMachines     | EL1850                      | [0ab5268867](https://linux-hardware.org/?probe=0ab5268867) | Oct 12, 2019 |
| GIADA         | SHARKBAY JHS688             | [51a3f3bf52](https://linux-hardware.org/?probe=51a3f3bf52) | Oct 07, 2019 |
| Unknown       | Unknown                     | [3a75852dac](https://linux-hardware.org/?probe=3a75852dac) | Oct 05, 2019 |
| Acer          | GRS400M                     | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| ASUSTek       | Z170-A                      | [8a875af2b7](https://linux-hardware.org/?probe=8a875af2b7) | Sep 28, 2019 |
| Acer          | GRS400M                     | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                     | [213156ffb7](https://linux-hardware.org/?probe=213156ffb7) | Sep 22, 2019 |
| Gigabyte      | F2A68HM-DS2                 | [b2450355f1](https://linux-hardware.org/?probe=b2450355f1) | Sep 22, 2019 |
| HP            | 18E4                        | [169718ec5d](https://linux-hardware.org/?probe=169718ec5d) | Sep 20, 2019 |
| Gigabyte      | G31M-ES2L                   | [1e6cb16b41](https://linux-hardware.org/?probe=1e6cb16b41) | Sep 16, 2019 |
| ASUSTek       | P8H67-V                     | [b0c20b14d8](https://linux-hardware.org/?probe=b0c20b14d8) | Sep 13, 2019 |
| Gigabyte      | G31M-ES2L                   | [bb555c11ae](https://linux-hardware.org/?probe=bb555c11ae) | Sep 11, 2019 |
| ASUSTek       | M4A78 PRO                   | [85dbb03610](https://linux-hardware.org/?probe=85dbb03610) | Sep 02, 2019 |
| ASUSTek       | P8H67-M PRO                 | [e287f6207b](https://linux-hardware.org/?probe=e287f6207b) | Aug 28, 2019 |
| Intel         | D33217CK G76541-301         | [11b398d3ef](https://linux-hardware.org/?probe=11b398d3ef) | Aug 20, 2019 |
| MSI           | B360M PRO-VDH               | [2d45947160](https://linux-hardware.org/?probe=2d45947160) | Aug 09, 2019 |
| Gigabyte      | B75M-D3V                    | [eaac8d48ee](https://linux-hardware.org/?probe=eaac8d48ee) | Jul 29, 2019 |
| Gigabyte      | 970A-UD3P                   | [8cdd8ffe23](https://linux-hardware.org/?probe=8cdd8ffe23) | Jul 26, 2019 |
| Gigabyte      | 970A-UD3P                   | [69d1517ba1](https://linux-hardware.org/?probe=69d1517ba1) | Jul 26, 2019 |
| ASUSTek       | PRIME B250M-A               | [7f1f084a4f](https://linux-hardware.org/?probe=7f1f084a4f) | Jul 22, 2019 |
| Acer          | Aspire X1900                | [3c153b6c2a](https://linux-hardware.org/?probe=3c153b6c2a) | Jul 01, 2019 |
| ASUSTek       | PRIME B250M-A               | [26bcd3b325](https://linux-hardware.org/?probe=26bcd3b325) | Jun 27, 2019 |
| MSI           | Z68A-GD80                   | [c63ed488ad](https://linux-hardware.org/?probe=c63ed488ad) | Jun 21, 2019 |
| MSI           | Z68A-GD80                   | [ef06e84cda](https://linux-hardware.org/?probe=ef06e84cda) | Jun 20, 2019 |
| Gigabyte      | Z97-HD3                     | [5bb09aeb32](https://linux-hardware.org/?probe=5bb09aeb32) | Jun 19, 2019 |
| Dell          | 03NVJ6 A02                  | [160c2de51f](https://linux-hardware.org/?probe=160c2de51f) | Jun 17, 2019 |
| MSI           | B75A-G41                    | [0a593d376a](https://linux-hardware.org/?probe=0a593d376a) | Jun 16, 2019 |
| Gigabyte      | 8I915P-D                    | [1012bd5a43](https://linux-hardware.org/?probe=1012bd5a43) | Jun 16, 2019 |
| Gigabyte      | 8I915P-D                    | [770fa46180](https://linux-hardware.org/?probe=770fa46180) | Jun 16, 2019 |
| Gigabyte      | X58A-UD7                    | [a72ee8fc63](https://linux-hardware.org/?probe=a72ee8fc63) | Jun 11, 2019 |
| ASRock        | 970 Extreme4                | [0fa01e4d66](https://linux-hardware.org/?probe=0fa01e4d66) | Jun 06, 2019 |
| OEM           | EIRD-SAM                    | [db87d8567e](https://linux-hardware.org/?probe=db87d8567e) | May 30, 2019 |
| HP            | 1494                        | [25810f9dc3](https://linux-hardware.org/?probe=25810f9dc3) | May 28, 2019 |
| ASUSTek       | PRIME B250M-A               | [6555e3060d](https://linux-hardware.org/?probe=6555e3060d) | May 26, 2019 |
| Gigabyte      | H55M-S2H                    | [7d62e5bc34](https://linux-hardware.org/?probe=7d62e5bc34) | May 21, 2019 |
| ASUSTek       | PRIME B250M-A               | [a595e6c0f8](https://linux-hardware.org/?probe=a595e6c0f8) | May 19, 2019 |
| ASUSTek       | P5B-VM                      | [79d120d78a](https://linux-hardware.org/?probe=79d120d78a) | May 18, 2019 |
| ASUSTek       | PRIME B250M-A               | [5c5bd85a88](https://linux-hardware.org/?probe=5c5bd85a88) | May 15, 2019 |
| ASUSTek       | PRIME B250M-A               | [eea01b0dc4](https://linux-hardware.org/?probe=eea01b0dc4) | May 15, 2019 |
| ASUSTek       | PRIME B250M-A               | [b0e6f5b516](https://linux-hardware.org/?probe=b0e6f5b516) | May 14, 2019 |
| eMachines     | EMCP73M                     | [d2994e2fad](https://linux-hardware.org/?probe=d2994e2fad) | Apr 23, 2019 |
| ASUSTek       | H81-GAMER                   | [9145f41194](https://linux-hardware.org/?probe=9145f41194) | Apr 22, 2019 |
| ASUSTek       | H110M-K                     | [73b13633f2](https://linux-hardware.org/?probe=73b13633f2) | Apr 19, 2019 |
| Acer          | FMP55                       | [8c28446a53](https://linux-hardware.org/?probe=8c28446a53) | Apr 19, 2019 |
| ASUSTek       | B85M-G                      | [658bcf12c4](https://linux-hardware.org/?probe=658bcf12c4) | Apr 15, 2019 |
| Foxconn       | G31MXP FAB:1.1              | [84ae7d38dd](https://linux-hardware.org/?probe=84ae7d38dd) | Apr 14, 2019 |
| ASUSTek       | Benicia                     | [1f8cda3921](https://linux-hardware.org/?probe=1f8cda3921) | Apr 09, 2019 |
| ASUSTek       | Benicia                     | [b1615f3369](https://linux-hardware.org/?probe=b1615f3369) | Apr 09, 2019 |
| HP            | ProLiant ML310e Gen8        | [6ffa42170b](https://linux-hardware.org/?probe=6ffa42170b) | Mar 30, 2019 |
| HP            | 1494                        | [44ac651021](https://linux-hardware.org/?probe=44ac651021) | Mar 28, 2019 |
| ASUSTek       | PRIME B250M-A               | [2f6bc6be29](https://linux-hardware.org/?probe=2f6bc6be29) | Mar 28, 2019 |
| Gigabyte      | G1.Sniper B6-CF             | [c20b184fc3](https://linux-hardware.org/?probe=c20b184fc3) | Mar 27, 2019 |
| ASRock        | 970 Extreme4                | [e2e8bb29ea](https://linux-hardware.org/?probe=e2e8bb29ea) | Mar 22, 2019 |
| Intel         | D2500HN AAG81480-500        | [18f900cb5b](https://linux-hardware.org/?probe=18f900cb5b) | Mar 04, 2019 |
| MSI           | H81M-E33                    | [920d422115](https://linux-hardware.org/?probe=920d422115) | Feb 06, 2019 |
| HP            | 843B                        | [5ffb1194b1](https://linux-hardware.org/?probe=5ffb1194b1) | Jan 30, 2019 |
| MSI           | H310M PRO-VD                | [33c6c6f3a6](https://linux-hardware.org/?probe=33c6c6f3a6) | Jan 14, 2019 |
| ASRock        | Q1900B-ITX                  | [18ca69190b](https://linux-hardware.org/?probe=18ca69190b) | Jan 07, 2019 |
| ABIT          | F-I90HD                     | [b158a21c8f](https://linux-hardware.org/?probe=b158a21c8f) | Dec 22, 2018 |
| Gigabyte      | H55M-S2H                    | [34831e35fd](https://linux-hardware.org/?probe=34831e35fd) | Dec 18, 2018 |
| ASUSTek       | M5A97 R2.0                  | [89b0446385](https://linux-hardware.org/?probe=89b0446385) | Dec 14, 2018 |
| HP            | 3031h                       | [0c08eee650](https://linux-hardware.org/?probe=0c08eee650) | Dec 12, 2018 |
| HP            | 3031h                       | [2c22bfe429](https://linux-hardware.org/?probe=2c22bfe429) | Dec 12, 2018 |
| ASUSTek       | H110M-K                     | [5169edc36e](https://linux-hardware.org/?probe=5169edc36e) | Dec 12, 2018 |
| HP            | 3646h                       | [d930f87402](https://linux-hardware.org/?probe=d930f87402) | Dec 11, 2018 |
| ASUSTek       | P5G41T-M LX2/GB             | [fe5f95f298](https://linux-hardware.org/?probe=fe5f95f298) | Nov 14, 2018 |
| Gigabyte      | GA-MA785GMT-UD2H            | [ca9cd7920f](https://linux-hardware.org/?probe=ca9cd7920f) | Oct 24, 2018 |
| Gigabyte      | GA-MA785GMT-UD2H            | [edc37ce67e](https://linux-hardware.org/?probe=edc37ce67e) | Oct 24, 2018 |
| ASUSTek       | M5A78L LE                   | [762df5fa40](https://linux-hardware.org/?probe=762df5fa40) | Oct 22, 2018 |
| ASUSTek       | PRIME B350-PLUS             | [e2d2b150a5](https://linux-hardware.org/?probe=e2d2b150a5) | Sep 26, 2018 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [491d157b81](https://linux-hardware.org/?probe=491d157b81) | Jun 03, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 57       | 15.16%  |
| Ubuntu 18.04                 | 48       | 12.77%  |
| OpenMandriva 4.2             | 14       | 3.72%   |
| Debian 11                    | 13       | 3.46%   |
| OpenMandriva 4.3             | 12       | 3.19%   |
| Linux Mint 20                | 10       | 2.66%   |
| Linux Mint 19.3              | 10       | 2.66%   |
| Ubuntu 22.04                 | 7        | 1.86%   |
| Ubuntu 21.04                 | 7        | 1.86%   |
| Ubuntu 19.10                 | 7        | 1.86%   |
| Pop!_OS 20.04                | 7        | 1.86%   |
| Manjaro                      | 7        | 1.86%   |
| Linux Mint 20.2              | 6        | 1.6%    |
| Fedora 31                    | 6        | 1.6%    |
| ArcoLinux Rolling            | 6        | 1.6%    |
| Ubuntu 20.10                 | 5        | 1.33%   |
| Pop!_OS 21.04                | 5        | 1.33%   |
| openSUSE Tumbleweed-XXXXXXXX | 5        | 1.33%   |
| Linux Mint 20.1              | 5        | 1.33%   |
| Zorin 16                     | 4        | 1.06%   |
| Zorin 15                     | 4        | 1.06%   |
| Xubuntu 20.04                | 4        | 1.06%   |
| Xubuntu 18.04                | 4        | 1.06%   |
| Ubuntu 16.04                 | 4        | 1.06%   |
| Pop!_OS 21.10                | 4        | 1.06%   |
| Linux Mint 20.3              | 4        | 1.06%   |
| Fedora 32                    | 4        | 1.06%   |
| Debian 10                    | 4        | 1.06%   |
| Ubuntu 19.04                 | 3        | 0.8%    |
| ROSA R11.1                   | 3        | 0.8%    |
| Manjaro 20.1                 | 3        | 0.8%    |
| Linux Mint 19.1              | 3        | 0.8%    |
| KDE neon 20.04               | 3        | 0.8%    |
| Debian 9                     | 3        | 0.8%    |
| UbuntuDDE 20.04              | 2        | 0.53%   |
| Ubuntu 21.10                 | 2        | 0.53%   |
| Ubuntu 18.10                 | 2        | 0.53%   |
| ROSA R11                     | 2        | 0.53%   |
| ROSA R10                     | 2        | 0.53%   |
| Pop!_OS 20.10                | 2        | 0.53%   |
| openSUSE Leap-15.1           | 2        | 0.53%   |
| OpenMandriva 4.50            | 2        | 0.53%   |
| Manjaro 21.1.6               | 2        | 0.53%   |
| LMDE 4                       | 2        | 0.53%   |
| Linux Mint 19.2              | 2        | 0.53%   |
| Fedora 34                    | 2        | 0.53%   |
| Fedora 33                    | 2        | 0.53%   |
| Debian Testing               | 2        | 0.53%   |
| Arch Rolling                 | 2        | 0.53%   |
| Arch                         | 2        | 0.53%   |
| Zorin 12                     | 1        | 0.27%   |
| Xubuntu 22.04                | 1        | 0.27%   |
| Xubuntu 19.10                | 1        | 0.27%   |
| Xero                         | 1        | 0.27%   |
| Ubuntu MATE 22.04            | 1        | 0.27%   |
| Ubuntu MATE 19.10            | 1        | 0.27%   |
| Ubuntu Budgie 20.10          | 1        | 0.27%   |
| Ubuntu Budgie 18.04          | 1        | 0.27%   |
| Ubuntu                       | 1        | 0.27%   |
| SteamOS 3.3                  | 1        | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 138      | 38.87%  |
| Linux Mint    | 40       | 11.27%  |
| OpenMandriva  | 28       | 7.89%   |
| Debian        | 21       | 5.92%   |
| Pop!_OS       | 17       | 4.79%   |
| Manjaro       | 17       | 4.79%   |
| Fedora        | 14       | 3.94%   |
| Zorin         | 9        | 2.54%   |
| Xubuntu       | 9        | 2.54%   |
| ROSA          | 7        | 1.97%   |
| Endless       | 7        | 1.97%   |
| openSUSE      | 6        | 1.69%   |
| ArcoLinux     | 6        | 1.69%   |
| Kubuntu       | 5        | 1.41%   |
| Arch          | 4        | 1.13%   |
| KDE neon      | 3        | 0.85%   |
| UbuntuDDE     | 2        | 0.56%   |
| Ubuntu MATE   | 2        | 0.56%   |
| Ubuntu Budgie | 2        | 0.56%   |
| LMDE          | 2        | 0.56%   |
| Clear Linux   | 2        | 0.56%   |
| CentOS        | 2        | 0.56%   |
| BigLinux      | 2        | 0.56%   |
| Xero          | 1        | 0.28%   |
| SteamOS       | 1        | 0.28%   |
| Solus         | 1        | 0.28%   |
| Slackware     | 1        | 0.28%   |
| Rocky Linux   | 1        | 0.28%   |
| Peppermint    | 1        | 0.28%   |
| Lubuntu       | 1        | 0.28%   |
| Feren OS      | 1        | 0.28%   |
| EndeavourOS   | 1        | 0.28%   |
| Elementary    | 1        | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002         | 14       | 3.34%   |
| 5.4.0-42-generic                 | 13       | 3.1%    |
| 5.16.7-desktop-1omv4003          | 10       | 2.39%   |
| 5.8.0-43-generic                 | 5        | 1.19%   |
| 5.4.0-58-generic                 | 5        | 1.19%   |
| 5.4.0-48-generic                 | 5        | 1.19%   |
| 5.4.0-26-generic                 | 5        | 1.19%   |
| 5.10.0-8-amd64                   | 5        | 1.19%   |
| 5.8.0-48-generic                 | 4        | 0.95%   |
| 5.8.0-44-generic                 | 4        | 0.95%   |
| 5.4.0-77-generic                 | 4        | 0.95%   |
| 5.4.0-52-generic                 | 4        | 0.95%   |
| 5.13.0-7614-generic              | 4        | 0.95%   |
| 5.4.0-7634-generic               | 3        | 0.72%   |
| 5.4.0-40-generic                 | 3        | 0.72%   |
| 5.4.0-37-generic                 | 3        | 0.72%   |
| 5.4.0-29-generic                 | 3        | 0.72%   |
| 5.4.0-28-generic                 | 3        | 0.72%   |
| 5.3.0-51-generic                 | 3        | 0.72%   |
| 5.3.0-46-generic                 | 3        | 0.72%   |
| 5.3.0-40-generic                 | 3        | 0.72%   |
| 5.15.0-40-generic                | 3        | 0.72%   |
| 5.13.0-28-generic                | 3        | 0.72%   |
| 5.11.0-38-generic                | 3        | 0.72%   |
| 5.11.0-34-generic                | 3        | 0.72%   |
| 5.0.0-37-generic                 | 3        | 0.72%   |
| 5.0.0-23-generic                 | 3        | 0.72%   |
| 4.9.155-nrj-desktop-1rosa-x86_64 | 3        | 0.72%   |
| 4.18.0-17-generic                | 3        | 0.72%   |
| 4.15.0-55-generic                | 3        | 0.72%   |
| 4.15.0-51-generic                | 3        | 0.72%   |
| 4.15.0-42-generic                | 3        | 0.72%   |
| 5.8.6-1-MANJARO                  | 2        | 0.48%   |
| 5.8.0-59-generic                 | 2        | 0.48%   |
| 5.8.0-41-generic                 | 2        | 0.48%   |
| 5.8.0-36-generic                 | 2        | 0.48%   |
| 5.4.0-80-generic                 | 2        | 0.48%   |
| 5.4.0-74-generic                 | 2        | 0.48%   |
| 5.4.0-70-generic                 | 2        | 0.48%   |
| 5.4.0-67-generic                 | 2        | 0.48%   |
| 5.4.0-66-generic                 | 2        | 0.48%   |
| 5.4.0-64-generic                 | 2        | 0.48%   |
| 5.4.0-47-generic                 | 2        | 0.48%   |
| 5.3.0-53-generic                 | 2        | 0.48%   |
| 5.3.0-41-generic                 | 2        | 0.48%   |
| 5.3.0-28-generic                 | 2        | 0.48%   |
| 5.3.0-23-generic                 | 2        | 0.48%   |
| 5.3.0-19-generic                 | 2        | 0.48%   |
| 5.15.7-arch1-1                   | 2        | 0.48%   |
| 5.15.7-1-MANJARO                 | 2        | 0.48%   |
| 5.15.0-43-generic                | 2        | 0.48%   |
| 5.15.0-27-generic                | 2        | 0.48%   |
| 5.13.19-2-MANJARO                | 2        | 0.48%   |
| 5.13.0-27-generic                | 2        | 0.48%   |
| 5.12.4-desktop-1omv4050          | 2        | 0.48%   |
| 5.11.0-7633-generic              | 2        | 0.48%   |
| 5.11.0-43-generic                | 2        | 0.48%   |
| 5.11.0-35-generic                | 2        | 0.48%   |
| 5.11.0-27-generic                | 2        | 0.48%   |
| 5.11.0-17-generic                | 2        | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 77       | 19.74%  |
| 4.15.0  | 39       | 10%     |
| 5.8.0   | 28       | 7.18%   |
| 5.3.0   | 25       | 6.41%   |
| 5.11.0  | 21       | 5.38%   |
| 5.13.0  | 17       | 4.36%   |
| 5.0.0   | 16       | 4.1%    |
| 5.10.14 | 14       | 3.59%   |
| 5.15.0  | 13       | 3.33%   |
| 4.18.0  | 13       | 3.33%   |
| 5.16.7  | 10       | 2.56%   |
| 5.10.0  | 10       | 2.56%   |
| 4.19.0  | 5        | 1.28%   |
| 5.15.7  | 4        | 1.03%   |
| 5.11.12 | 4        | 1.03%   |
| 4.9.155 | 4        | 1.03%   |
| 5.13.19 | 3        | 0.77%   |
| 5.8.6   | 2        | 0.51%   |
| 5.8.12  | 2        | 0.51%   |
| 5.7.10  | 2        | 0.51%   |
| 5.7.0   | 2        | 0.51%   |
| 5.6.10  | 2        | 0.51%   |
| 5.18.16 | 2        | 0.51%   |
| 5.12.4  | 2        | 0.51%   |
| 4.10.0  | 2        | 0.51%   |
| 5.9.6   | 1        | 0.26%   |
| 5.9.16  | 1        | 0.26%   |
| 5.9.15  | 1        | 0.26%   |
| 5.9.1   | 1        | 0.26%   |
| 5.9.0   | 1        | 0.26%   |
| 5.8.3   | 1        | 0.26%   |
| 5.8.11  | 1        | 0.26%   |
| 5.8.10  | 1        | 0.26%   |
| 5.7.8   | 1        | 0.26%   |
| 5.7.12  | 1        | 0.26%   |
| 5.6.6   | 1        | 0.26%   |
| 5.6.2   | 1        | 0.26%   |
| 5.5.7   | 1        | 0.26%   |
| 5.5.15  | 1        | 0.26%   |
| 5.5.13  | 1        | 0.26%   |
| 5.4.72  | 1        | 0.26%   |
| 5.4.66  | 1        | 0.26%   |
| 5.4.32  | 1        | 0.26%   |
| 5.4.18  | 1        | 0.26%   |
| 5.4.15  | 1        | 0.26%   |
| 5.3.8   | 1        | 0.26%   |
| 5.3.7   | 1        | 0.26%   |
| 5.3.15  | 1        | 0.26%   |
| 5.2.11  | 1        | 0.26%   |
| 5.19.2  | 1        | 0.26%   |
| 5.18.12 | 1        | 0.26%   |
| 5.18.10 | 1        | 0.26%   |
| 5.18.1  | 1        | 0.26%   |
| 5.18.0  | 1        | 0.26%   |
| 5.17.7  | 1        | 0.26%   |
| 5.17.6  | 1        | 0.26%   |
| 5.17.15 | 1        | 0.26%   |
| 5.16.13 | 1        | 0.26%   |
| 5.16.12 | 1        | 0.26%   |
| 5.16.11 | 1        | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 82       | 21.41%  |
| 4.15    | 40       | 10.44%  |
| 5.8     | 35       | 9.14%   |
| 5.10    | 27       | 7.05%   |
| 5.11    | 26       | 6.79%   |
| 5.3     | 25       | 6.53%   |
| 5.13    | 24       | 6.27%   |
| 5.15    | 21       | 5.48%   |
| 5.0     | 16       | 4.18%   |
| 4.18    | 15       | 3.92%   |
| 5.16    | 14       | 3.66%   |
| 4.9     | 8        | 2.09%   |
| 5.7     | 6        | 1.57%   |
| 5.18    | 6        | 1.57%   |
| 4.19    | 6        | 1.57%   |
| 5.9     | 5        | 1.31%   |
| 5.14    | 5        | 1.31%   |
| 5.12    | 5        | 1.31%   |
| 5.6     | 3        | 0.78%   |
| 5.5     | 3        | 0.78%   |
| 5.17    | 3        | 0.78%   |
| 4.10    | 2        | 0.52%   |
| 5.2     | 1        | 0.26%   |
| 5.19    | 1        | 0.26%   |
| 5.1     | 1        | 0.26%   |
| 4.4     | 1        | 0.26%   |
| 4.12    | 1        | 0.26%   |
| 2.6     | 1        | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 323      | 95.28%  |
| i686   | 16       | 4.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 143      | 39.72%  |
| Unknown    | 67       | 18.61%  |
| KDE5       | 47       | 13.06%  |
| XFCE       | 34       | 9.44%   |
| X-Cinnamon | 28       | 7.78%   |
| KDE        | 11       | 3.06%   |
| MATE       | 6        | 1.67%   |
| Budgie     | 5        | 1.39%   |
| awesome    | 4        | 1.11%   |
| Unity      | 3        | 0.83%   |
| KDE4       | 3        | 0.83%   |
| Cinnamon   | 3        | 0.83%   |
| Deepin     | 2        | 0.56%   |
| Pantheon   | 1        | 0.28%   |
| LXQt       | 1        | 0.28%   |
| LeftWM     | 1        | 0.28%   |
| i3         | 1        | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 271      | 78.32%  |
| Unknown | 41       | 11.85%  |
| Wayland | 30       | 8.67%   |
| Tty     | 4        | 1.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 213      | 61.03%  |
| SDDM    | 41       | 11.75%  |
| GDM     | 30       | 8.6%    |
| LightDM | 27       | 7.74%   |
| GDM3    | 20       | 5.73%   |
| TDM     | 14       | 4.01%   |
| KDM     | 3        | 0.86%   |
| XDM     | 1        | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| pt_PT   | 160      | 45.2%   |
| en_US   | 94       | 26.55%  |
| Unknown | 63       | 17.8%   |
| en_GB   | 14       | 3.95%   |
| C       | 6        | 1.69%   |
| sv_SE   | 3        | 0.85%   |
| ru_RU   | 3        | 0.85%   |
| pt_BR   | 3        | 0.85%   |
| fr_FR   | 3        | 0.85%   |
| es_ES   | 2        | 0.56%   |
| de_DE   | 2        | 0.56%   |
| en_CA   | 1        | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 248      | 71.06%  |
| EFI  | 101      | 28.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 265      | 76.37%  |
| Overlay | 31       | 8.93%   |
| Unknown | 22       | 6.34%   |
| Btrfs   | 20       | 5.76%   |
| Xfs     | 6        | 1.73%   |
| Zfs     | 2        | 0.58%   |
| F2fs    | 1        | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 234      | 67.24%  |
| GPT     | 69       | 19.83%  |
| MBR     | 45       | 12.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 285      | 82.85%  |
| Yes       | 59       | 17.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 239      | 68.68%  |
| Yes       | 109      | 31.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 128      | 37.76%  |
| MSI                 | 44       | 12.98%  |
| Gigabyte Technology | 43       | 12.68%  |
| Hewlett-Packard     | 27       | 7.96%   |
| ASRock              | 21       | 6.19%   |
| Dell                | 13       | 3.83%   |
| Acer                | 8        | 2.36%   |
| Foxconn             | 7        | 2.06%   |
| Intel               | 6        | 1.77%   |
| Fujitsu             | 5        | 1.47%   |
| Lenovo              | 4        | 1.18%   |
| eMachines           | 3        | 0.88%   |
| Biostar             | 3        | 0.88%   |
| Unknown             | 3        | 0.88%   |
| Pegatron            | 2        | 0.59%   |
| OEM                 | 2        | 0.59%   |
| Minix               | 2        | 0.59%   |
| Medion              | 2        | 0.59%   |
| Huanan              | 2        | 0.59%   |
| ECS                 | 2        | 0.59%   |
| Shuttle             | 1        | 0.29%   |
| RKM                 | 1        | 0.29%   |
| NEC Computers       | 1        | 0.29%   |
| Libretrend          | 1        | 0.29%   |
| IBM                 | 1        | 0.29%   |
| Google              | 1        | 0.29%   |
| GIADA               | 1        | 0.29%   |
| BCM                 | 1        | 0.29%   |
| ASRockRack          | 1        | 0.29%   |
| Apple               | 1        | 0.29%   |
| AMI                 | 1        | 0.29%   |
| ABIT                | 1        | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 12       | 3.54%   |
| MSI MS-7817                        | 4        | 1.18%   |
| ASUS P5G41T-M LX                   | 4        | 1.18%   |
| ASUS H110M-K                       | 4        | 1.18%   |
| HP Compaq Elite 8300 SFF           | 3        | 0.88%   |
| Gigabyte B550 AORUS ELITE          | 3        | 0.88%   |
| ASUS PRIME H510M-K                 | 3        | 0.88%   |
| ASUS M5A78L-M/USB3                 | 3        | 0.88%   |
| Unknown                            | 3        | 0.88%   |
| MSI MS-7A38                        | 2        | 0.59%   |
| MSI MS-7A34                        | 2        | 0.59%   |
| MSI MS-7592                        | 2        | 0.59%   |
| Minix Z83-4                        | 2        | 0.59%   |
| HP Compaq dc7900 Small Form Factor | 2        | 0.59%   |
| HP Compaq dc7700 Small Form Factor | 2        | 0.59%   |
| HP Compaq 8000 Elite SFF PC        | 2        | 0.59%   |
| Gigabyte H55M-S2H                  | 2        | 0.59%   |
| Gigabyte H110M-Gaming 3            | 2        | 0.59%   |
| Gigabyte G31M-ES2L                 | 2        | 0.59%   |
| Gigabyte B450M DS3H                | 2        | 0.59%   |
| eMachines EL1830                   | 2        | 0.59%   |
| Dell Precision WorkStation 490     | 2        | 0.59%   |
| ASUS SABERTOOTH 990FX R2.0         | 2        | 0.59%   |
| ASUS ROG STRIX X470-F GAMING       | 2        | 0.59%   |
| ASUS PRIME B450-PLUS               | 2        | 0.59%   |
| ASUS PRIME B350-PLUS               | 2        | 0.59%   |
| ASUS PRIME A320M-K                 | 2        | 0.59%   |
| ASUS P9X79                         | 2        | 0.59%   |
| ASUS P8H67-V                       | 2        | 0.59%   |
| ASUS P8H67                         | 2        | 0.59%   |
| ASUS P5P43TD PRO                   | 2        | 0.59%   |
| ASUS P5LD2-SE                      | 2        | 0.59%   |
| ASUS P5G41T-M LX2/GB               | 2        | 0.59%   |
| ASUS P5G41T-M LE                   | 2        | 0.59%   |
| ASUS P5G41C-M LX                   | 2        | 0.59%   |
| ASUS M32CD_A_F_K20CD_K31CD         | 2        | 0.59%   |
| ASUS A_F_K31AN                     | 2        | 0.59%   |
| ASRock 775Dual-VSTA                | 2        | 0.59%   |
| Shuttle NC03U                      | 1        | 0.29%   |
| RKM MK36S                          | 1        | 0.29%   |
| Pegatron SERIES                    | 1        | 0.29%   |
| Pegatron FZ096AA-AB9 a6643pt       | 1        | 0.29%   |
| OEM Intel H81                      | 1        | 0.29%   |
| OEM EIRD-SAM                       | 1        | 0.29%   |
| NEC Computers PALOMAR              | 1        | 0.29%   |
| MSI T6520                          | 1        | 0.29%   |
| MSI MS-7D09                        | 1        | 0.29%   |
| MSI MS-7C95                        | 1        | 0.29%   |
| MSI MS-7C91                        | 1        | 0.29%   |
| MSI MS-7C88                        | 1        | 0.29%   |
| MSI MS-7C75                        | 1        | 0.29%   |
| MSI MS-7C37                        | 1        | 0.29%   |
| MSI MS-7C02                        | 1        | 0.29%   |
| MSI MS-7B89                        | 1        | 0.29%   |
| MSI MS-7B85                        | 1        | 0.29%   |
| MSI MS-7B79                        | 1        | 0.29%   |
| MSI MS-7B49                        | 1        | 0.29%   |
| MSI MS-7B33                        | 1        | 0.29%   |
| MSI MS-7B24                        | 1        | 0.29%   |
| MSI MS-7B22                        | 1        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 18       | 5.31%   |
| HP Compaq             | 13       | 3.83%   |
| ASUS All              | 12       | 3.54%   |
| Dell OptiPlex         | 9        | 2.65%   |
| ASUS P5G41T-M         | 9        | 2.65%   |
| ASUS ROG              | 8        | 2.36%   |
| Acer Aspire           | 7        | 2.06%   |
| Gigabyte B550         | 5        | 1.47%   |
| MSI MS-7817           | 4        | 1.18%   |
| ASUS P8H61-M          | 4        | 1.18%   |
| ASUS M5A78L-M         | 4        | 1.18%   |
| ASUS H110M-K          | 4        | 1.18%   |
| Lenovo ThinkCentre    | 3        | 0.88%   |
| HP ProDesk            | 3        | 0.88%   |
| HP Pavilion           | 3        | 0.88%   |
| Gigabyte B450M        | 3        | 0.88%   |
| Fujitsu ESPRIMO       | 3        | 0.88%   |
| Dell Precision        | 3        | 0.88%   |
| ASUS P8Z77-V          | 3        | 0.88%   |
| ASUS A                | 3        | 0.88%   |
| Unknown               | 3        | 0.88%   |
| MSI MS-7A38           | 2        | 0.59%   |
| MSI MS-7A34           | 2        | 0.59%   |
| MSI MS-7592           | 2        | 0.59%   |
| Minix Z83-4           | 2        | 0.59%   |
| HP ProLiant           | 2        | 0.59%   |
| Gigabyte H55M-S2H     | 2        | 0.59%   |
| Gigabyte H310M        | 2        | 0.59%   |
| Gigabyte H110M-Gaming | 2        | 0.59%   |
| Gigabyte G31M-ES2L    | 2        | 0.59%   |
| Fujitsu PRIMERGY      | 2        | 0.59%   |
| eMachines EL1830      | 2        | 0.59%   |
| ASUS STRIX            | 2        | 0.59%   |
| ASUS SABERTOOTH       | 2        | 0.59%   |
| ASUS P9X79            | 2        | 0.59%   |
| ASUS P8H67-V          | 2        | 0.59%   |
| ASUS P8H67-M          | 2        | 0.59%   |
| ASUS P8H67            | 2        | 0.59%   |
| ASUS P5Q              | 2        | 0.59%   |
| ASUS P5P43TD          | 2        | 0.59%   |
| ASUS P5LD2-SE         | 2        | 0.59%   |
| ASUS P5KPL-AM         | 2        | 0.59%   |
| ASUS P5K              | 2        | 0.59%   |
| ASUS P5G41C-M         | 2        | 0.59%   |
| ASUS Maximus          | 2        | 0.59%   |
| ASUS M5A97            | 2        | 0.59%   |
| ASUS M32CD            | 2        | 0.59%   |
| ASRock B450M          | 2        | 0.59%   |
| ASRock 775Dual-VSTA   | 2        | 0.59%   |
| Shuttle NC03U         | 1        | 0.29%   |
| RKM MK36S             | 1        | 0.29%   |
| Pegatron SERIES       | 1        | 0.29%   |
| Pegatron FZ096AA-AB9  | 1        | 0.29%   |
| OEM Intel             | 1        | 0.29%   |
| OEM EIRD-SAM          | 1        | 0.29%   |
| NEC Computers PALOMAR | 1        | 0.29%   |
| MSI T6520             | 1        | 0.29%   |
| MSI MS-7D09           | 1        | 0.29%   |
| MSI MS-7C95           | 1        | 0.29%   |
| MSI MS-7C91           | 1        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 37       | 10.91%  |
| 2012 | 32       | 9.44%   |
| 2010 | 28       | 8.26%   |
| 2009 | 25       | 7.37%   |
| 2020 | 23       | 6.78%   |
| 2011 | 22       | 6.49%   |
| 2016 | 21       | 6.19%   |
| 2008 | 19       | 5.6%    |
| 2019 | 18       | 5.31%   |
| 2017 | 18       | 5.31%   |
| 2006 | 18       | 5.31%   |
| 2014 | 17       | 5.01%   |
| 2013 | 15       | 4.42%   |
| 2007 | 14       | 4.13%   |
| 2021 | 11       | 3.24%   |
| 2015 | 11       | 3.24%   |
| 2005 | 7        | 2.06%   |
| 2004 | 2        | 0.59%   |
| 2003 | 1        | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 339      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 334      | 97.38%  |
| Enabled  | 9        | 2.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 337      | 99.41%  |
| Yes  | 2        | 0.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 84       | 24%     |
| 16.01-24.0  | 74       | 21.14%  |
| 8.01-16.0   | 65       | 18.57%  |
| 4.01-8.0    | 48       | 13.71%  |
| 32.01-64.0  | 35       | 10%     |
| 1.01-2.0    | 19       | 5.43%   |
| 2.01-3.0    | 11       | 3.14%   |
| 64.01-256.0 | 10       | 2.86%   |
| 24.01-32.0  | 3        | 0.86%   |
| 0.51-1.0    | 1        | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 148      | 39.15%  |
| 2.01-3.0   | 78       | 20.63%  |
| 4.01-8.0   | 56       | 14.81%  |
| 3.01-4.0   | 36       | 9.52%   |
| 0.51-1.0   | 32       | 8.47%   |
| 8.01-16.0  | 16       | 4.23%   |
| 0.01-0.5   | 4        | 1.06%   |
| 24.01-32.0 | 3        | 0.79%   |
| 16.01-24.0 | 3        | 0.79%   |
| 32.01-64.0 | 1        | 0.26%   |
| Unknown    | 1        | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 134      | 38.18%  |
| 2      | 107      | 30.48%  |
| 3      | 57       | 16.24%  |
| 4      | 28       | 7.98%   |
| 5      | 8        | 2.28%   |
| 0      | 7        | 1.99%   |
| 6      | 5        | 1.42%   |
| 10     | 2        | 0.57%   |
| 7      | 2        | 0.57%   |
| 8      | 1        | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 175      | 51.17%  |
| Yes       | 167      | 48.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 338      | 99.71%  |
| No        | 1        | 0.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 223      | 64.45%  |
| Yes       | 123      | 35.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 279      | 80.87%  |
| Yes       | 66       | 19.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Portugal | 339      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Lisbon                      | 75       | 21.19%  |
| Porto                       | 24       | 6.78%   |
| Leiria                      | 11       | 3.11%   |
| Braga                       | 11       | 3.11%   |
| Coimbra                     | 8        | 2.26%   |
| Setúbal                    | 7        | 1.98%   |
| Faro                        | 7        | 1.98%   |
| Aveiro                      | 7        | 1.98%   |
| Vila Nova de Gaia           | 6        | 1.69%   |
| Portimao                    | 6        | 1.69%   |
| Amora                       | 6        | 1.69%   |
| Torres Vedras               | 5        | 1.41%   |
| Povoa de Santa Iria         | 5        | 1.41%   |
| Evora                       | 5        | 1.41%   |
| Sintra                      | 4        | 1.13%   |
| Sao Domingos de Rana        | 4        | 1.13%   |
| Mafra                       | 4        | 1.13%   |
| Guimaraes                   | 4        | 1.13%   |
| Amadora                     | 4        | 1.13%   |
| Vila do Conde               | 3        | 0.85%   |
| Trofa                       | 3        | 0.85%   |
| Quinta Do Conde             | 3        | 0.85%   |
| Ponta Delgada               | 3        | 0.85%   |
| Matosinhos Municipality     | 3        | 0.85%   |
| Loures                      | 3        | 0.85%   |
| Covilha                     | 3        | 0.85%   |
| Cascais                     | 3        | 0.85%   |
| Barreiro                    | 3        | 0.85%   |
| Azeitao                     | 3        | 0.85%   |
| Viseu                       | 2        | 0.56%   |
| Vila Nova de Famalicao      | 2        | 0.56%   |
| Tomar                       | 2        | 0.56%   |
| Senhora da Hora             | 2        | 0.56%   |
| Sao Joao da Madeira         | 2        | 0.56%   |
| Ramada                      | 2        | 0.56%   |
| Paredes                     | 2        | 0.56%   |
| Odemira                     | 2        | 0.56%   |
| Montijo                     | 2        | 0.56%   |
| Moita                       | 2        | 0.56%   |
| Mem Martins                 | 2        | 0.56%   |
| Gondomar                    | 2        | 0.56%   |
| Funchal                     | 2        | 0.56%   |
| Ericeira                    | 2        | 0.56%   |
| Entroncamento               | 2        | 0.56%   |
| Elvas                       | 2        | 0.56%   |
| Chaves                      | 2        | 0.56%   |
| Beja                        | 2        | 0.56%   |
| Barcelos                    | 2        | 0.56%   |
| Baixa da Banheira           | 2        | 0.56%   |
| Baguim do Monte             | 2        | 0.56%   |
| Vila Real de Santo António | 1        | 0.28%   |
| Vila Praia de Ancora        | 1        | 0.28%   |
| Viana do Castelo            | 1        | 0.28%   |
| Venda do Pinheiro           | 1        | 0.28%   |
| Valongo                     | 1        | 0.28%   |
| Valega                      | 1        | 0.28%   |
| Vale de Santarem            | 1        | 0.28%   |
| Vagos                       | 1        | 0.28%   |
| Torreira                    | 1        | 0.28%   |
| Tires                       | 1        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 116      | 204    | 18.95%  |
| Seagate                      | 103      | 153    | 16.83%  |
| Samsung Electronics          | 87       | 135    | 14.22%  |
| Kingston                     | 76       | 110    | 12.42%  |
| Toshiba                      | 46       | 74     | 7.52%   |
| Hitachi                      | 28       | 35     | 4.58%   |
| Crucial                      | 27       | 37     | 4.41%   |
| Maxtor                       | 16       | 23     | 2.61%   |
| SanDisk                      | 13       | 16     | 2.12%   |
| Unknown                      | 9        | 11     | 1.47%   |
| Phison                       | 7        | 12     | 1.14%   |
| BlueRay                      | 7        | 7      | 1.14%   |
| PNY                          | 6        | 10     | 0.98%   |
| GOODRAM                      | 6        | 7      | 0.98%   |
| Intel                        | 5        | 7      | 0.82%   |
| KIOXIA-EXCERIA               | 4        | 4      | 0.65%   |
| Hewlett-Packard              | 4        | 5      | 0.65%   |
| KIOXIA                       | 3        | 4      | 0.49%   |
| HGST                         | 3        | 8      | 0.49%   |
| ExcelStor                    | 3        | 3      | 0.49%   |
| China                        | 3        | 3      | 0.49%   |
| A-DATA Technology            | 3        | 3      | 0.49%   |
| XPG                          | 2        | 3      | 0.33%   |
| Vaseky                       | 2        | 2      | 0.33%   |
| SK hynix                     | 2        | 2      | 0.33%   |
| OCZ                          | 2        | 2      | 0.33%   |
| KingDian                     | 2        | 5      | 0.33%   |
| Gigabyte Technology          | 2        | 2      | 0.33%   |
| Fujitsu                      | 2        | 2      | 0.33%   |
| Emtec                        | 2        | 2      | 0.33%   |
| Zheino                       | 1        | 2      | 0.16%   |
| Transcend                    | 1        | 1      | 0.16%   |
| Team                         | 1        | 1      | 0.16%   |
| T-FORCE                      | 1        | 2      | 0.16%   |
| Shenzhen Longsys Electronics | 1        | 2      | 0.16%   |
| S3+                          | 1        | 1      | 0.16%   |
| Realtek Semiconductor        | 1        | 1      | 0.16%   |
| Quantum                      | 1        | 1      | 0.16%   |
| Phison Electronics           | 1        | 1      | 0.16%   |
| Mushkin                      | 1        | 1      | 0.16%   |
| Micron/Crucial Technology    | 1        | 1      | 0.16%   |
| Micron Technology            | 1        | 1      | 0.16%   |
| JMicron Technology           | 1        | 1      | 0.16%   |
| INNOVATION IT                | 1        | 1      | 0.16%   |
| INDMEM                       | 1        | 1      | 0.16%   |
| IBM                          | 1        | 1      | 0.16%   |
| Faspeed                      | 1        | 1      | 0.16%   |
| BAITITON                     | 1        | 1      | 0.16%   |
| ASMedia                      | 1        | 2      | 0.16%   |
| ADATA Technology             | 1        | 1      | 0.16%   |
| 2-Power                      | 1        | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 18       | 2.64%   |
| Seagate ST1000DM010-2EP102 1TB   | 13       | 1.91%   |
| Kingston SA400S37120G 120GB SSD  | 11       | 1.61%   |
| Seagate ST3500418AS 500GB        | 10       | 1.47%   |
| Kingston SV300S37A240G 240GB SSD | 8        | 1.17%   |
| Samsung SSD 850 EVO 250GB        | 7        | 1.03%   |
| Kingston SV300S37A120G 120GB SSD | 7        | 1.03%   |
| Kingston SUV400S37120G 120GB SSD | 7        | 1.03%   |
| Toshiba HDWD110 1TB              | 6        | 0.88%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 0.73%   |
| Samsung HD161HJ 160GB            | 5        | 0.73%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 0.73%   |
| WDC WD3200AAJS-00L7A0 320GB      | 4        | 0.59%   |
| WDC WD10EZEX-00BN5A0 1TB         | 4        | 0.59%   |
| Toshiba DT01ACA050 500GB         | 4        | 0.59%   |
| Samsung SSD 860 EVO 500GB        | 4        | 0.59%   |
| Samsung SSD 840 EVO 250GB        | 4        | 0.59%   |
| Samsung NVMe SSD Drive 500GB     | 4        | 0.59%   |
| Samsung HD502IJ 500GB            | 4        | 0.59%   |
| Samsung HD502HJ 500GB            | 4        | 0.59%   |
| Samsung HD252HJ 250GB            | 4        | 0.59%   |
| Samsung HD160JJ 160GB            | 4        | 0.59%   |
| Samsung HD103SJ 1TB              | 4        | 0.59%   |
| Kingston SA400S37960G 960GB SSD  | 4        | 0.59%   |
| Crucial CT500MX500SSD1 500GB     | 4        | 0.59%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 3        | 0.44%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.44%   |
| WDC WD20EARX-00PASB0 2TB         | 3        | 0.44%   |
| WDC WD10EARX-00N0YB0 1TB         | 3        | 0.44%   |
| WDC WD10EALX-009BA0 1TB          | 3        | 0.44%   |
| Toshiba HDWD130 3TB              | 3        | 0.44%   |
| Toshiba HDWD120 2TB              | 3        | 0.44%   |
| Toshiba DT01ACA100 1TB           | 3        | 0.44%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 0.44%   |
| Seagate ST3250820AS 250GB        | 3        | 0.44%   |
| Seagate ST3250310AS 250GB        | 3        | 0.44%   |
| Seagate ST3160023AS 160GB        | 3        | 0.44%   |
| Seagate ST1000LM048-2E7172 1TB   | 3        | 0.44%   |
| Seagate Expansion Desk 4TB       | 3        | 0.44%   |
| Seagate Expansion 500GB          | 3        | 0.44%   |
| Samsung SSD 850 PRO 256GB        | 3        | 0.44%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.44%   |
| Samsung NVMe SSD Drive 2TB       | 3        | 0.44%   |
| Samsung HD103UJ 1TB              | 3        | 0.44%   |
| PNY CS3030 500GB SSD             | 3        | 0.44%   |
| Phison NVMe SSD Drive 1TB        | 3        | 0.44%   |
| Maxtor 6L200M0 208GB             | 3        | 0.44%   |
| Kingston SUV400S37240G 240GB SSD | 3        | 0.44%   |
| Hitachi HDP725050GLA360 500GB    | 3        | 0.44%   |
| WDC WDS250G2B0B-00YS70 250GB SSD | 2        | 0.29%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 2        | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.29%   |
| WDC WD800JD-60LSA0 80GB          | 2        | 0.29%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 0.29%   |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 0.29%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2        | 0.29%   |
| WDC WD3200AAKX-00ERMA0 320GB     | 2        | 0.29%   |
| WDC WD10EZRX-00A8LB0 1TB         | 2        | 0.29%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 103      | 177    | 30.56%  |
| Seagate             | 100      | 150    | 29.67%  |
| Toshiba             | 40       | 64     | 11.87%  |
| Samsung Electronics | 40       | 60     | 11.87%  |
| Hitachi             | 28       | 35     | 8.31%   |
| Maxtor              | 15       | 22     | 4.45%   |
| HGST                | 3        | 8      | 0.89%   |
| ExcelStor           | 3        | 3      | 0.89%   |
| Fujitsu             | 2        | 2      | 0.59%   |
| Unknown             | 1        | 1      | 0.3%    |
| Quantum             | 1        | 1      | 0.3%    |
| Hewlett-Packard     | 1        | 2      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 71       | 98     | 32.13%  |
| Samsung Electronics | 37       | 57     | 16.74%  |
| Crucial             | 26       | 36     | 11.76%  |
| WDC                 | 13       | 22     | 5.88%   |
| SanDisk             | 11       | 14     | 4.98%   |
| BlueRay             | 6        | 6      | 2.71%   |
| Toshiba             | 5        | 8      | 2.26%   |
| Unknown             | 4        | 4      | 1.81%   |
| GOODRAM             | 4        | 5      | 1.81%   |
| PNY                 | 3        | 6      | 1.36%   |
| Intel               | 3        | 4      | 1.36%   |
| Hewlett-Packard     | 3        | 3      | 1.36%   |
| China               | 3        | 3      | 1.36%   |
| A-DATA Technology   | 3        | 3      | 1.36%   |
| Vaseky              | 2        | 2      | 0.9%    |
| SK hynix            | 2        | 2      | 0.9%    |
| OCZ                 | 2        | 2      | 0.9%    |
| KIOXIA-EXCERIA      | 2        | 2      | 0.9%    |
| KingDian            | 2        | 5      | 0.9%    |
| Gigabyte Technology | 2        | 2      | 0.9%    |
| Emtec               | 2        | 2      | 0.9%    |
| Zheino              | 1        | 2      | 0.45%   |
| Transcend           | 1        | 1      | 0.45%   |
| Team                | 1        | 1      | 0.45%   |
| Seagate             | 1        | 1      | 0.45%   |
| S3+                 | 1        | 1      | 0.45%   |
| Mushkin             | 1        | 1      | 0.45%   |
| Micron Technology   | 1        | 1      | 0.45%   |
| Maxtor              | 1        | 1      | 0.45%   |
| JMicron Technology  | 1        | 1      | 0.45%   |
| INNOVATION IT       | 1        | 1      | 0.45%   |
| INDMEM              | 1        | 1      | 0.45%   |
| Faspeed             | 1        | 1      | 0.45%   |
| BAITITON            | 1        | 1      | 0.45%   |
| ASMedia             | 1        | 2      | 0.45%   |
| 2-Power             | 1        | 2      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 251      | 525    | 50.81%  |
| SSD     | 183      | 304    | 37.04%  |
| NVMe    | 51       | 78     | 10.32%  |
| Unknown | 5        | 6      | 1.01%   |
| MMC     | 4        | 4      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 314      | 814    | 82.2%   |
| NVMe | 51       | 78     | 13.35%  |
| SAS  | 13       | 21     | 3.4%    |
| MMC  | 4        | 4      | 1.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 271      | 536    | 61.59%  |
| 0.51-1.0   | 105      | 192    | 23.86%  |
| 1.01-2.0   | 34       | 55     | 7.73%   |
| 2.01-3.0   | 10       | 13     | 2.27%   |
| 3.01-4.0   | 9        | 16     | 2.05%   |
| 4.01-10.0  | 9        | 12     | 2.05%   |
| 10.01-20.0 | 1        | 4      | 0.23%   |
| 0          | 1        | 1      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 99       | 27.2%   |
| 251-500        | 67       | 18.41%  |
| 501-1000       | 44       | 12.09%  |
| 51-100         | 31       | 8.52%   |
| 1001-2000      | 30       | 8.24%   |
| 1-20           | 28       | 7.69%   |
| More than 3000 | 25       | 6.87%   |
| 21-50          | 15       | 4.12%   |
| 2001-3000      | 15       | 4.12%   |
| Unknown        | 10       | 2.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 149      | 39.95%  |
| 21-50          | 54       | 14.48%  |
| 51-100         | 39       | 10.46%  |
| 101-250        | 38       | 10.19%  |
| 251-500        | 24       | 6.43%   |
| 501-1000       | 23       | 6.17%   |
| 1001-2000      | 19       | 5.09%   |
| Unknown        | 10       | 2.68%   |
| More than 3000 | 9        | 2.41%   |
| 2001-3000      | 8        | 2.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB         | 3        | 3      | 5.45%   |
| WDC WD800JD-60LSA0 80GB           | 2        | 2      | 3.64%   |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 2      | 3.64%   |
| Toshiba MK2552GSX 250GB           | 2        | 2      | 3.64%   |
| Samsung Electronics HD252HJ 250GB | 2        | 2      | 3.64%   |
| WDC WD6400AADS-00M2B0 640GB       | 1        | 1      | 1.82%   |
| WDC WD5000LPCX-60VHAT0 500GB      | 1        | 1      | 1.82%   |
| WDC WD5000BPVT-22HXZT1 500GB      | 1        | 1      | 1.82%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 1      | 1.82%   |
| WDC WD5000AAKS-00A7B0 500GB       | 1        | 4      | 1.82%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 2      | 1.82%   |
| WDC WD3200AAJS-00B4A0 320GB       | 1        | 1      | 1.82%   |
| WDC WD30EZRS-11J99B1 3TB          | 1        | 1      | 1.82%   |
| WDC WD2500JS-40TGB0 250GB         | 1        | 1      | 1.82%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 1.82%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1      | 1.82%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 1.82%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 1.82%   |
| WDC WD10EADS-11M2B1 1TB           | 1        | 1      | 1.82%   |
| WDC WD1002FBYS-02A6B0 1TB         | 1        | 1      | 1.82%   |
| WDC WD1001FALS-00J7B0 1TB         | 1        | 4      | 1.82%   |
| Unknown FM-25S2S-60GBP2 64GB SSD  | 1        | 1      | 1.82%   |
| Toshiba MK3252GSX 320GB           | 1        | 2      | 1.82%   |
| SK hynix SH920 2.5 7MM 512GB SSD  | 1        | 1      | 1.82%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 1.82%   |
| Seagate ST9250827AS 250GB         | 1        | 1      | 1.82%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 1.82%   |
| Seagate ST480HM000-1G5162 480GB   | 1        | 1      | 1.82%   |
| Seagate ST3320820AS 320GB         | 1        | 1      | 1.82%   |
| Seagate ST3250820AS 250GB         | 1        | 1      | 1.82%   |
| Seagate ST3160812AS 160GB         | 1        | 1      | 1.82%   |
| Seagate ST2000DM001-9YN164 2TB    | 1        | 1      | 1.82%   |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 1.82%   |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 1.82%   |
| Samsung Electronics HD103SI 1TB   | 1        | 1      | 1.82%   |
| Maxtor STM3320820AS 320GB         | 1        | 2      | 1.82%   |
| Maxtor STM3250820AS 250GB         | 1        | 2      | 1.82%   |
| Maxtor 7L300S0 304GB              | 1        | 2      | 1.82%   |
| Maxtor 6Y120M0 122GB              | 1        | 1      | 1.82%   |
| Kingston SUV400S37240G 240GB SSD  | 1        | 1      | 1.82%   |
| Kingston SA400S37240G 240GB SSD   | 1        | 1      | 1.82%   |
| KingDian S280 120GB SSD           | 1        | 2      | 1.82%   |
| Hitachi HTS723232A7A364 320GB     | 1        | 1      | 1.82%   |
| Hitachi HTS547550A9E384 500GB     | 1        | 1      | 1.82%   |
| Hitachi HDT725050VLA360 500GB     | 1        | 1      | 1.82%   |
| Hitachi HDS721050CLA362 500GB     | 1        | 1      | 1.82%   |
| Hitachi HDP725050GLA360 500GB     | 1        | 1      | 1.82%   |
| Crucial CT525MX300SSD1 528GB      | 1        | 1      | 1.82%   |
| Crucial CT1050MX300SSD1 1050GB    | 1        | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 27     | 38.46%  |
| Seagate             | 9        | 11     | 17.31%  |
| Hitachi             | 5        | 5      | 9.62%   |
| Samsung Electronics | 4        | 5      | 7.69%   |
| Maxtor              | 4        | 7      | 7.69%   |
| Toshiba             | 3        | 4      | 5.77%   |
| Kingston            | 2        | 2      | 3.85%   |
| Crucial             | 2        | 2      | 3.85%   |
| Unknown             | 1        | 1      | 1.92%   |
| SK hynix            | 1        | 1      | 1.92%   |
| KingDian            | 1        | 2      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 27     | 44.44%  |
| Seagate             | 9        | 11     | 20%     |
| Hitachi             | 5        | 5      | 11.11%  |
| Samsung Electronics | 4        | 5      | 8.89%   |
| Maxtor              | 4        | 7      | 8.89%   |
| Toshiba             | 3        | 4      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 59     | 85.42%  |
| SSD  | 7        | 8      | 14.58%  |

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
| Detected | 239      | 635    | 63.23%  |
| Works    | 94       | 215    | 24.87%  |
| Malfunc  | 45       | 67     | 11.9%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 223      | 50.11%  |
| AMD                              | 93       | 20.9%   |
| Samsung Electronics              | 19       | 4.27%   |
| JMicron Technology               | 17       | 3.82%   |
| VIA Technologies                 | 13       | 2.92%   |
| Phison Electronics               | 12       | 2.7%    |
| ASMedia Technology               | 12       | 2.7%    |
| Nvidia                           | 11       | 2.47%   |
| Marvell Technology Group         | 9        | 2.02%   |
| Kingston Technology Company      | 7        | 1.57%   |
| SanDisk                          | 5        | 1.12%   |
| KIOXIA                           | 5        | 1.12%   |
| Silicon Integrated Systems [SiS] | 3        | 0.67%   |
| Shenzhen Longsys Electronics     | 3        | 0.67%   |
| ADATA Technology                 | 3        | 0.67%   |
| LSI Logic / Symbios Logic        | 2        | 0.45%   |
| Adaptec                          | 2        | 0.45%   |
| ULi Electronics                  | 1        | 0.22%   |
| Toshiba America Info Systems     | 1        | 0.22%   |
| Realtek Semiconductor            | 1        | 0.22%   |
| Micron/Crucial Technology        | 1        | 0.22%   |
| Micron Technology                | 1        | 0.22%   |
| Hewlett-Packard                  | 1        | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 45       | 7.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 37       | 6.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 31       | 5.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 20       | 3.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 3.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 3.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14       | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 2.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 2.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 2.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 1.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 1.99%   |
| Phison E12 NVMe Controller                                                              | 11       | 1.82%   |
| Intel SATA Controller [RAID mode]                                                       | 10       | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 1.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 1.49%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 1.33%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 8        | 1.33%   |
| AMD 300 Series Chipset SATA Controller                                                  | 8        | 1.33%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 6        | 1%      |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6        | 1%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 1%      |
| Nvidia MCP61 SATA Controller                                                            | 5        | 0.83%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.83%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.83%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 4        | 0.66%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.66%   |
| KIOXIA NVMe SSD                                                                         | 4        | 0.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 0.66%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.66%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.66%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4        | 0.66%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 4        | 0.66%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 4        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.66%   |
| AMD FCH SATA Controller D                                                               | 4        | 0.66%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 3        | 0.5%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 3        | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.5%    |
| Nvidia MCP73 IDE Controller                                                             | 3        | 0.5%    |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 3        | 0.5%    |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.5%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.5%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 0.5%    |
| Intel 82801EB (ICH5) SATA Controller                                                    | 3        | 0.5%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.5%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 0.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.5%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.5%    |
| AMD X370 Series Chipset SATA Controller                                                 | 3        | 0.5%    |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 3        | 0.5%    |
| AMD IXP SB4x0 IDE Controller                                                            | 3        | 0.5%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 224      | 51.14%  |
| IDE  | 137      | 31.28%  |
| NVMe | 52       | 11.87%  |
| RAID | 22       | 5.02%   |
| SCSI | 2        | 0.46%   |
| SAS  | 1        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 241      | 71.09%  |
| AMD    | 98       | 28.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 2.05%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 1.76%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 6        | 1.76%   |
| AMD FX-6300 Six-Core Processor              | 6        | 1.76%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 1.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 1.47%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 1.47%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 1.47%   |
| Intel Pentium D CPU 3.00GHz                 | 4        | 1.17%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 1.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.17%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 4        | 1.17%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 4        | 1.17%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 1.17%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.17%   |
| AMD FX-8320 Eight-Core Processor            | 4        | 1.17%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 3        | 0.88%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 3        | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.88%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.88%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.88%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.88%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.88%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 3        | 0.88%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.88%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 3        | 0.88%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3        | 0.88%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz      | 3        | 0.88%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.88%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.88%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.88%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 2        | 0.59%   |
| Intel Xeon CPU E5345 @ 2.33GHz              | 2        | 0.59%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 2        | 0.59%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 0.59%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 0.59%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 0.59%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 2        | 0.59%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 2        | 0.59%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 0.59%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2        | 0.59%   |
| Intel Pentium 4 CPU 3.40GHz                 | 2        | 0.59%   |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 0.59%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.59%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 2        | 0.59%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.59%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.59%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 0.59%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2        | 0.59%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.59%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.59%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 2        | 0.59%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.59%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.59%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 0.59%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 0.59%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.59%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 56       | 16.42%  |
| Intel Core i7           | 32       | 9.38%   |
| AMD Ryzen 5             | 28       | 8.21%   |
| Intel Core i3           | 21       | 6.16%   |
| Intel Core 2 Quad       | 21       | 6.16%   |
| AMD FX                  | 21       | 6.16%   |
| Intel Xeon              | 17       | 4.99%   |
| Intel Pentium Dual-Core | 15       | 4.4%    |
| AMD Ryzen 7             | 12       | 3.52%   |
| Intel Pentium 4         | 11       | 3.23%   |
| Intel Pentium           | 11       | 3.23%   |
| Intel Core 2 Duo        | 11       | 3.23%   |
| Intel Core 2            | 10       | 2.93%   |
| Intel Celeron           | 9        | 2.64%   |
| Other                   | 7        | 2.05%   |
| Intel Atom              | 7        | 2.05%   |
| Intel Pentium D         | 6        | 1.76%   |
| Intel Pentium Dual      | 5        | 1.47%   |
| AMD Ryzen 3             | 5        | 1.47%   |
| AMD A10                 | 4        | 1.17%   |
| AMD Athlon II X2        | 3        | 0.88%   |
| AMD Athlon 64           | 3        | 0.88%   |
| Intel Pentium Gold      | 2        | 0.59%   |
| Intel Core i9           | 2        | 0.59%   |
| AMD Ryzen Threadripper  | 2        | 0.59%   |
| AMD Ryzen 9             | 2        | 0.59%   |
| AMD E                   | 2        | 0.59%   |
| AMD Athlon II X3        | 2        | 0.59%   |
| AMD Athlon              | 2        | 0.59%   |
| AMD A6                  | 2        | 0.59%   |
| Intel Genuine           | 1        | 0.29%   |
| AMD Sempron             | 1        | 0.29%   |
| AMD Ryzen 7 PRO         | 1        | 0.29%   |
| AMD Phenom II X6        | 1        | 0.29%   |
| AMD Phenom II X4        | 1        | 0.29%   |
| AMD Phenom II X3        | 1        | 0.29%   |
| AMD Phenom              | 1        | 0.29%   |
| AMD Athlon 64 X2        | 1        | 0.29%   |
| AMD A8                  | 1        | 0.29%   |
| AMD A4                  | 1        | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 136      | 39.77%  |
| 2       | 102      | 29.82%  |
| 6       | 42       | 12.28%  |
| 8       | 21       | 6.14%   |
| 1       | 21       | 6.14%   |
| 3       | 11       | 3.22%   |
| 16      | 3        | 0.88%   |
| 12      | 2        | 0.58%   |
| 10      | 2        | 0.58%   |
| 24      | 1        | 0.29%   |
| Unknown | 1        | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 334      | 98.53%  |
| 2      | 5        | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 185      | 54.25%  |
| 2       | 155      | 45.45%  |
| Unknown | 1        | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 326      | 94.49%  |
| Unknown        | 14       | 4.06%   |
| 32-bit         | 4        | 1.16%   |
| 64-bit         | 1        | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 81       | 22.63%  |
| 0x1067a    | 26       | 7.26%   |
| 0x306c3    | 21       | 5.87%   |
| 0x206a7    | 20       | 5.59%   |
| 0x306a9    | 17       | 4.75%   |
| 0x506e3    | 14       | 3.91%   |
| 0x06000852 | 13       | 3.63%   |
| 0x08701021 | 11       | 3.07%   |
| 0x906ea    | 10       | 2.79%   |
| 0x6fb      | 9        | 2.51%   |
| 0x906e9    | 8        | 2.23%   |
| 0x0800820d | 8        | 2.23%   |
| 0x106e5    | 5        | 1.4%    |
| 0x10677    | 5        | 1.4%    |
| 0x10676    | 5        | 1.4%    |
| 0xf43      | 4        | 1.12%   |
| 0x6fd      | 4        | 1.12%   |
| 0x6f6      | 4        | 1.12%   |
| 0x6f2      | 4        | 1.12%   |
| 0x010000c8 | 4        | 1.12%   |
| 0xf41      | 3        | 0.84%   |
| 0xa0671    | 3        | 0.84%   |
| 0xa0655    | 3        | 0.84%   |
| 0x906eb    | 3        | 0.84%   |
| 0x406c4    | 3        | 0.84%   |
| 0x30678    | 3        | 0.84%   |
| 0x206d7    | 3        | 0.84%   |
| 0x08101016 | 3        | 0.84%   |
| 0xf65      | 2        | 0.56%   |
| 0xf64      | 2        | 0.56%   |
| 0xf62      | 2        | 0.56%   |
| 0xf4a      | 2        | 0.56%   |
| 0xf34      | 2        | 0.56%   |
| 0x906ec    | 2        | 0.56%   |
| 0x6f7      | 2        | 0.56%   |
| 0x30661    | 2        | 0.56%   |
| 0x08701013 | 2        | 0.56%   |
| 0x08600106 | 2        | 0.56%   |
| 0x0800820b | 2        | 0.56%   |
| 0x08001138 | 2        | 0.56%   |
| 0x08001137 | 2        | 0.56%   |
| 0x06003106 | 2        | 0.56%   |
| 0x06000626 | 2        | 0.56%   |
| 0xf47      | 1        | 0.28%   |
| 0xf27      | 1        | 0.28%   |
| 0x906ed    | 1        | 0.28%   |
| 0x706a8    | 1        | 0.28%   |
| 0x506e8    | 1        | 0.28%   |
| 0x506c9    | 1        | 0.28%   |
| 0x406e3    | 1        | 0.28%   |
| 0x406c3    | 1        | 0.28%   |
| 0x40651    | 1        | 0.28%   |
| 0x306e4    | 1        | 0.28%   |
| 0x206c2    | 1        | 0.28%   |
| 0x20655    | 1        | 0.28%   |
| 0x20652    | 1        | 0.28%   |
| 0x106a5    | 1        | 0.28%   |
| 0x10661    | 1        | 0.28%   |
| 0x0a201205 | 1        | 0.28%   |
| 0x0a201009 | 1        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 41       | 12.02%  |
| KabyLake      | 29       | 8.5%    |
| Haswell       | 29       | 8.5%    |
| Core          | 29       | 8.5%    |
| SandyBridge   | 23       | 6.74%   |
| Skylake       | 19       | 5.57%   |
| Piledriver    | 19       | 5.57%   |
| NetBurst      | 19       | 5.57%   |
| IvyBridge     | 19       | 5.57%   |
| Zen 2         | 17       | 4.99%   |
| Zen+          | 16       | 4.69%   |
| Zen           | 14       | 4.11%   |
| K10           | 11       | 3.23%   |
| Silvermont    | 8        | 2.35%   |
| Nehalem       | 6        | 1.76%   |
| CometLake     | 6        | 1.76%   |
| Zen 3         | 5        | 1.47%   |
| K8 Hammer     | 4        | 1.17%   |
| Excavator     | 4        | 1.17%   |
| Westmere      | 3        | 0.88%   |
| Steamroller   | 3        | 0.88%   |
| Icelake       | 3        | 0.88%   |
| Bulldozer     | 3        | 0.88%   |
| Bonnell       | 3        | 0.88%   |
| Unknown       | 3        | 0.88%   |
| Bobcat        | 2        | 0.59%   |
| Puma          | 1        | 0.29%   |
| Goldmont plus | 1        | 0.29%   |
| Goldmont      | 1        | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 132      | 36.57%  |
| AMD                              | 117      | 32.41%  |
| Intel                            | 108      | 29.92%  |
| Silicon Integrated Systems [SiS] | 2        | 0.55%   |
| Matrox Electronics Systems       | 1        | 0.28%   |
| ASPEED Technology                | 1        | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20       | 5.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 17       | 4.55%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13       | 3.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 11       | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 2.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 2.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9        | 2.41%   |
| Intel HD Graphics 530                                                                    | 9        | 2.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9        | 2.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7        | 1.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 6        | 1.6%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5        | 1.34%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 1.34%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 5        | 1.34%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 5        | 1.34%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5        | 1.34%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 4        | 1.07%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4        | 1.07%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 1.07%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 4        | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3        | 0.8%    |
| Nvidia GT216 [GeForce 315]                                                               | 3        | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 0.8%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 0.8%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 0.8%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 0.8%    |
| Nvidia GK106 [GeForce GTX 660]                                                           | 3        | 0.8%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 0.8%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 3        | 0.8%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 3        | 0.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 0.8%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3        | 0.8%    |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 3        | 0.8%    |
| AMD RS780L [Radeon 3000]                                                                 | 3        | 0.8%    |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 3        | 0.8%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 0.8%    |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 3        | 0.8%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 2        | 0.53%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.53%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 0.53%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 2        | 0.53%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 0.53%   |
| Nvidia GF108GL [Quadro 600]                                                              | 2        | 0.53%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 2        | 0.53%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 0.53%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 2        | 0.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2        | 0.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 0.53%   |
| Intel HD Graphics 630                                                                    | 2        | 0.53%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.53%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 0.53%   |
| Intel 82865G Integrated Graphics Controller                                              | 2        | 0.53%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 0.53%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 2        | 0.53%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                                  | 2        | 0.53%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                                       | 2        | 0.53%   |
| AMD RS480 [Radeon Xpress 200 Series]                                                     | 2        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 126      | 36.42%  |
| 1 x AMD         | 109      | 31.5%   |
| 1 x Intel       | 96       | 27.75%  |
| 2 x AMD         | 7        | 2.02%   |
| 2 x Nvidia      | 2        | 0.58%   |
| 1 x SiS         | 2        | 0.58%   |
| Nvidia + Matrox | 1        | 0.29%   |
| Nvidia + ASPEED | 1        | 0.29%   |
| Intel + Nvidia  | 1        | 0.29%   |
| AMD + Nvidia    | 1        | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 254      | 73.62%  |
| Proprietary | 76       | 22.03%  |
| Unknown     | 15       | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 149      | 42.21%  |
| 0.01-0.5   | 50       | 14.16%  |
| 1.01-2.0   | 49       | 13.88%  |
| 0.51-1.0   | 45       | 12.75%  |
| 3.01-4.0   | 29       | 8.22%   |
| 7.01-8.0   | 18       | 5.1%    |
| 5.01-6.0   | 6        | 1.7%    |
| 8.01-16.0  | 4        | 1.13%   |
| 2.01-3.0   | 3        | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 66       | 18.44%  |
| Goldstar             | 59       | 16.48%  |
| Ancor Communications | 48       | 13.41%  |
| Hewlett-Packard      | 47       | 13.13%  |
| Dell                 | 17       | 4.75%   |
| BenQ                 | 14       | 3.91%   |
| AOC                  | 14       | 3.91%   |
| Philips              | 11       | 3.07%   |
| LG Electronics       | 9        | 2.51%   |
| Acer                 | 9        | 2.51%   |
| Unknown              | 7        | 1.96%   |
| Sony                 | 7        | 1.96%   |
| ASUSTek Computer     | 6        | 1.68%   |
| Lenovo               | 5        | 1.4%    |
| Fujitsu Siemens      | 4        | 1.12%   |
| ViewSonic            | 3        | 0.84%   |
| HPN                  | 3        | 0.84%   |
| Apple                | 3        | 0.84%   |
| ___                  | 2        | 0.56%   |
| AVX                  | 2        | 0.56%   |
| Vestel Elektronik    | 1        | 0.28%   |
| Vestel               | 1        | 0.28%   |
| Toshiba              | 1        | 0.28%   |
| TEO                  | 1        | 0.28%   |
| TCL                  | 1        | 0.28%   |
| TAR                  | 1        | 0.28%   |
| RTK                  | 1        | 0.28%   |
| NEC Computers        | 1        | 0.28%   |
| MSI                  | 1        | 0.28%   |
| Mi                   | 1        | 0.28%   |
| Lenovo Group Limited | 1        | 0.28%   |
| KOC                  | 1        | 0.28%   |
| IBM                  | 1        | 0.28%   |
| HXF                  | 1        | 0.28%   |
| HUAWEI               | 1        | 0.28%   |
| HJW                  | 1        | 0.28%   |
| Hitachi              | 1        | 0.28%   |
| FUS                  | 1        | 0.28%   |
| Eizo                 | 1        | 0.28%   |
| CTV                  | 1        | 0.28%   |
| CHI                  | 1        | 0.28%   |
| AUS                  | 1        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                 | 4        | 1.05%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch       | 4        | 1.05%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 4        | 1.05%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3        | 0.79%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 3        | 0.79%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 3        | 0.79%   |
| Goldstar M227WD GSM56D5 1920x1080 480x270mm 21.7-inch                  | 3        | 0.79%   |
| Goldstar L1919S GSM4AF0 1280x1024 376x301mm 19.0-inch                  | 3        | 0.79%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 0.79%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                 | 3        | 0.79%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 3        | 0.79%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch       | 3        | 0.79%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch       | 3        | 0.79%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 3        | 0.79%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch   | 3        | 0.79%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                      | 3        | 0.79%   |
| ___ LCDTV16 ___0101 1920x1080                                          | 2        | 0.52%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 2        | 0.52%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                    | 2        | 0.52%   |
| Sony SDM-HS93 SNY1190 1280x1024 357x286mm 18.0-inch                    | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch   | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM0301 1680x1050 459x296mm 21.5-inch   | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM0230 1280x1024 376x301mm 19.0-inch   | 2        | 0.52%   |
| Samsung Electronics LCD Monitor SAM0992 1920x1080 890x500mm 40.2-inch  | 2        | 0.52%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                     | 2        | 0.52%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                     | 2        | 0.52%   |
| Lenovo Q24i-10 LEN65F3 1920x1080 527x296mm 23.8-inch                   | 2        | 0.52%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch            | 2        | 0.52%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch             | 2        | 0.52%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 2        | 0.52%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch            | 2        | 0.52%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch     | 2        | 0.52%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 2        | 0.52%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                    | 2        | 0.52%   |
| Goldstar ULTRAGEAR GSM5B72 1920x1080 531x298mm 24.0-inch               | 2        | 0.52%   |
| Goldstar L194W GSM4B6A 1440x900 408x255mm 18.9-inch                    | 2        | 0.52%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                  | 2        | 0.52%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                  | 2        | 0.52%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                    | 2        | 0.52%   |
| Goldstar 27GL650F GSM5B71 1920x1080 597x336mm 27.0-inch                | 2        | 0.52%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 2        | 0.52%   |
| Dell E2013H DELD05C 1600x900 443x249mm 20.0-inch                       | 2        | 0.52%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                      | 2        | 0.52%   |
| AVX AVT GC513 AVX0034 1920x1080 698x392mm 31.5-inch                    | 2        | 0.52%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.52%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                    | 2        | 0.52%   |
| Ancor Communications ASUSMS238 ACI23F5 1920x1080 509x286mm 23.0-inch   | 2        | 0.52%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch  | 2        | 0.52%   |
| Ancor Communications ASUS VH222H ACI22F4 1920x1080 477x268mm 21.5-inch | 2        | 0.52%   |
| Ancor Communications ASUS VH197 ACI19EB 1366x768 410x230mm 18.5-inch   | 2        | 0.52%   |
| Acer AT2055 ACR2055 1600x900 400x300mm 19.7-inch                       | 2        | 0.52%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.26%   |
| ViewSonic VA902 VSC1B1C 1280x1024 376x301mm 19.0-inch                  | 1        | 0.26%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch          | 1        | 0.26%   |
| Vestel LCD Monitor 32W_LCD_TV 1920x1080                                | 1        | 0.26%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.26%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 1        | 0.26%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                     | 1        | 0.26%   |
| Unknown LCD Monitor WAM OZDSP27IPS 2560x2520                           | 1        | 0.26%   |
| Unknown LCD Monitor Sony SDM-HS93 1280x1024                            | 1        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 152      | 43.3%   |
| 1280x1024 (SXGA)   | 55       | 15.67%  |
| 3840x2160 (4K)     | 29       | 8.26%   |
| 1680x1050 (WSXGA+) | 18       | 5.13%   |
| 1440x900 (WXGA+)   | 17       | 4.84%   |
| 2560x1440 (QHD)    | 14       | 3.99%   |
| 1366x768 (WXGA)    | 14       | 3.99%   |
| 1600x900 (HD+)     | 10       | 2.85%   |
| 1920x1200 (WUXGA)  | 8        | 2.28%   |
| 1360x768           | 7        | 1.99%   |
| Unknown            | 7        | 1.99%   |
| 1024x768 (XGA)     | 4        | 1.14%   |
| 3840x1080          | 3        | 0.85%   |
| 2560x1080          | 3        | 0.85%   |
| 3440x1440          | 2        | 0.57%   |
| 1152x864           | 2        | 0.57%   |
| 4480x1600          | 1        | 0.28%   |
| 3360x1080          | 1        | 0.28%   |
| 3360x1050          | 1        | 0.28%   |
| 2944x1080          | 1        | 0.28%   |
| 2560x2520          | 1        | 0.28%   |
| 1400x1050          | 1        | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 56       | 15.6%   |
| 24      | 42       | 11.7%   |
| Unknown | 38       | 10.58%  |
| 23      | 37       | 10.31%  |
| 19      | 34       | 9.47%   |
| 27      | 31       | 8.64%   |
| 17      | 28       | 7.8%    |
| 18      | 21       | 5.85%   |
| 20      | 14       | 3.9%    |
| 31      | 10       | 2.79%   |
| 15      | 10       | 2.79%   |
| 22      | 7        | 1.95%   |
| 84      | 5        | 1.39%   |
| 54      | 5        | 1.39%   |
| 34      | 4        | 1.11%   |
| 33      | 3        | 0.84%   |
| 32      | 3        | 0.84%   |
| 72      | 2        | 0.56%   |
| 46      | 2        | 0.56%   |
| 40      | 2        | 0.56%   |
| 48      | 1        | 0.28%   |
| 39      | 1        | 0.28%   |
| 26      | 1        | 0.28%   |
| 25      | 1        | 0.28%   |
| 16      | 1        | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 108      | 30.95%  |
| 501-600     | 99       | 28.37%  |
| 301-350     | 39       | 11.17%  |
| Unknown     | 38       | 10.89%  |
| 351-400     | 22       | 6.3%    |
| 601-700     | 15       | 4.3%    |
| 701-800     | 10       | 2.87%   |
| 1001-1500   | 8        | 2.29%   |
| 1501-2000   | 7        | 2.01%   |
| 801-900     | 3        | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 194      | 57.91%  |
| 5/4     | 46       | 13.73%  |
| 16/10   | 36       | 10.75%  |
| Unknown | 36       | 10.75%  |
| 4/3     | 13       | 3.88%   |
| 21/9    | 4        | 1.19%   |
| 6/5     | 3        | 0.9%    |
| 3/2     | 3        | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 123      | 34.84%  |
| 151-200        | 60       | 17%     |
| 141-150        | 45       | 12.75%  |
| Unknown        | 38       | 10.76%  |
| 301-350        | 32       | 9.07%   |
| 351-500        | 19       | 5.38%   |
| More than 1000 | 13       | 3.68%   |
| 251-300        | 7        | 1.98%   |
| 111-120        | 5        | 1.42%   |
| 101-110        | 5        | 1.42%   |
| 501-1000       | 5        | 1.42%   |
| 131-140        | 1        | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 207      | 61.42%  |
| 101-120 | 67       | 19.88%  |
| Unknown | 38       | 11.28%  |
| 1-50    | 11       | 3.26%   |
| 121-160 | 10       | 2.97%   |
| 161-240 | 4        | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 274      | 78.51%  |
| 2     | 45       | 12.89%  |
| 0     | 23       | 6.59%   |
| 3     | 6        | 1.72%   |
| 4     | 1        | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 207      | 46%     |
| Intel                                 | 95       | 21.11%  |
| Qualcomm Atheros                      | 45       | 10%     |
| Qualcomm Atheros Communications       | 12       | 2.67%   |
| Broadcom                              | 12       | 2.67%   |
| Nvidia                                | 11       | 2.44%   |
| TP-Link                               | 10       | 2.22%   |
| Ralink Technology                     | 7        | 1.56%   |
| VIA Technologies                      | 5        | 1.11%   |
| Marvell Technology Group              | 5        | 1.11%   |
| D-Link                                | 5        | 1.11%   |
| Silicon Integrated Systems [SiS]      | 3        | 0.67%   |
| Samsung Electronics                   | 3        | 0.67%   |
| Ralink                                | 3        | 0.67%   |
| Edimax Technology                     | 3        | 0.67%   |
| Broadcom Limited                      | 3        | 0.67%   |
| ASUSTek Computer                      | 3        | 0.67%   |
| D-Link System                         | 2        | 0.44%   |
| ADMtek                                | 2        | 0.44%   |
| TRENDnet                              | 1        | 0.22%   |
| Smart Link                            | 1        | 0.22%   |
| Sitecom Europe                        | 1        | 0.22%   |
| Realtek                               | 1        | 0.22%   |
| Motorola                              | 1        | 0.22%   |
| Microsoft                             | 1        | 0.22%   |
| Mellanox Technologies                 | 1        | 0.22%   |
| Dresden Elektronik                    | 1        | 0.22%   |
| dog hunter                            | 1        | 0.22%   |
| Belkin Components                     | 1        | 0.22%   |
| ASIX Electronics                      | 1        | 0.22%   |
| Apple                                 | 1        | 0.22%   |
| Accton Technology                     | 1        | 0.22%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 176      | 34.92%  |
| Intel I211 Gigabit Network Connection                                                | 13       | 2.58%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 10       | 1.98%   |
| Intel Ethernet Connection (2) I219-V                                                 | 9        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 9        | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 7        | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 7        | 1.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 7        | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 7        | 1.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                             | 7        | 1.39%   |
| Intel 82579V Gigabit Network Connection                                              | 7        | 1.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6        | 1.19%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 6        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 6        | 1.19%   |
| Intel Ethernet Connection (2) I218-V                                                 | 6        | 1.19%   |
| Intel 82567LM-3 Gigabit Network Connection                                           | 6        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 5        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                                      | 5        | 0.99%   |
| Nvidia MCP61 Ethernet                                                                | 5        | 0.99%   |
| Intel Wi-Fi 6 AX200                                                                  | 5        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                                 | 5        | 0.99%   |
| VIA VT6102/VT6103 [Rhine-II]                                                         | 4        | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 4        | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 4        | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 4        | 0.79%   |
| Intel Ethernet Connection (14) I219-V                                                | 4        | 0.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 3        | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                      | 3        | 0.6%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                        | 3        | 0.6%    |
| Nvidia MCP73 Ethernet                                                                | 3        | 0.6%    |
| Intel Wireless 7265                                                                  | 3        | 0.6%    |
| Intel Ethernet Controller I225-V                                                     | 3        | 0.6%    |
| Intel Ethernet Connection I217-LM                                                    | 3        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                                | 3        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 3        | 0.6%    |
| Intel 82566DM Gigabit Network Connection                                             | 3        | 0.6%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                              | 3        | 0.6%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 2        | 0.4%    |
| TP-Link TL-WN722N v2                                                                 | 2        | 0.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                        | 2        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                                        | 2        | 0.4%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 2        | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 0.4%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                             | 2        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                            | 2        | 0.4%    |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 2        | 0.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2        | 0.4%    |
| Nvidia MCP79 Ethernet                                                                | 2        | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                              | 2        | 0.4%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                    | 2        | 0.4%    |
| Intel Wireless 3160                                                                  | 2        | 0.4%    |
| Intel I210 Gigabit Network Connection                                                | 2        | 0.4%    |
| Intel Ethernet Connection I217-V                                                     | 2        | 0.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 0.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                           | 2        | 0.4%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 0.4%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                      | 2        | 0.4%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                              | 2        | 0.4%    |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                                 | 2        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 34       | 26.98%  |
| Qualcomm Atheros                      | 22       | 17.46%  |
| Intel                                 | 19       | 15.08%  |
| Qualcomm Atheros Communications       | 12       | 9.52%   |
| TP-Link                               | 9        | 7.14%   |
| Ralink Technology                     | 7        | 5.56%   |
| D-Link                                | 5        | 3.97%   |
| Ralink                                | 3        | 2.38%   |
| Edimax Technology                     | 3        | 2.38%   |
| ASUSTek Computer                      | 3        | 2.38%   |
| Broadcom                              | 2        | 1.59%   |
| TRENDnet                              | 1        | 0.79%   |
| Sitecom Europe                        | 1        | 0.79%   |
| Realtek                               | 1        | 0.79%   |
| Microsoft                             | 1        | 0.79%   |
| Broadcom Limited                      | 1        | 0.79%   |
| Belkin Components                     | 1        | 0.79%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                       | 10       | 7.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 7        | 5.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 6        | 4.72%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 6        | 4.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5        | 3.94%   |
| Ralink MT7601U Wireless Adapter                                                       | 5        | 3.94%   |
| Intel Wi-Fi 6 AX200                                                                   | 5        | 3.94%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 4        | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4        | 3.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 3        | 2.36%   |
| Intel Wireless 7265                                                                   | 3        | 2.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3        | 2.36%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 2        | 1.57%   |
| TP-Link TL-WN722N v2                                                                  | 2        | 1.57%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 2        | 1.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 2        | 1.57%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 2        | 1.57%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287]  | 2        | 1.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2        | 1.57%   |
| Intel Wireless 3160                                                                   | 2        | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2        | 1.57%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 2        | 1.57%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]            | 1        | 0.79%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                 | 1        | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1        | 0.79%   |
| Sitecom Europe WL-345 Wireless USB adapter 300N X3                                    | 1        | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 0.79%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                   | 1        | 0.79%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                | 1        | 0.79%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                             | 1        | 0.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1        | 0.79%   |
| Realtek 802.11ac NIC                                                                  | 1        | 0.79%   |
| Ralink RT2770 Wireless Adapter                                                        | 1        | 0.79%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                     | 1        | 0.79%   |
| Ralink RT2561/RT61 rev B 802.11g                                                      | 1        | 0.79%   |
| Ralink RT2561/RT61 802.11g PCI                                                        | 1        | 0.79%   |
| Ralink RT2500 Wireless 802.11bg                                                       | 1        | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1        | 0.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1        | 0.79%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.79%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                | 1        | 0.79%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]        | 1        | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 0.79%   |
| Microsoft XBOX ACC                                                                    | 1        | 0.79%   |
| Intel Wireless-AC 9260                                                                | 1        | 0.79%   |
| Intel Wireless 8260                                                                   | 1        | 0.79%   |
| Intel Centrino Wireless-N 2200                                                        | 1        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1        | 0.79%   |
| Edimax 802.11n NIC                                                                    | 1        | 0.79%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                  | 1        | 0.79%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                         | 1        | 0.79%   |
| D-Link 802.11n WLAN Adapter                                                           | 1        | 0.79%   |
| D-Link 802.11ac NIC                                                                   | 1        | 0.79%   |
| D-Link 802.11 n WLAN                                                                  | 1        | 0.79%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                | 1        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 196      | 54.6%   |
| Intel                            | 89       | 24.79%  |
| Qualcomm Atheros                 | 26       | 7.24%   |
| Nvidia                           | 11       | 3.06%   |
| Broadcom                         | 10       | 2.79%   |
| VIA Technologies                 | 5        | 1.39%   |
| Marvell Technology Group         | 5        | 1.39%   |
| Silicon Integrated Systems [SiS] | 3        | 0.84%   |
| Samsung Electronics              | 3        | 0.84%   |
| D-Link System                    | 2        | 0.56%   |
| Broadcom Limited                 | 2        | 0.56%   |
| ADMtek                           | 2        | 0.56%   |
| TP-Link                          | 1        | 0.28%   |
| Mellanox Technologies            | 1        | 0.28%   |
| ASIX Electronics                 | 1        | 0.28%   |
| Apple                            | 1        | 0.28%   |
| Accton Technology                | 1        | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 176      | 47.18%  |
| Intel I211 Gigabit Network Connection                                          | 13       | 3.49%   |
| Intel Ethernet Connection (2) I219-V                                           | 9        | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9        | 2.41%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7        | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7        | 1.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7        | 1.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 7        | 1.88%   |
| Intel 82579V Gigabit Network Connection                                        | 7        | 1.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6        | 1.61%   |
| Intel Ethernet Connection (2) I218-V                                           | 6        | 1.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 6        | 1.61%   |
| Nvidia MCP61 Ethernet                                                          | 5        | 1.34%   |
| Intel Ethernet Connection (7) I219-V                                           | 5        | 1.34%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 4        | 1.07%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 4        | 1.07%   |
| Intel Ethernet Connection (14) I219-V                                          | 4        | 1.07%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3        | 0.8%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 3        | 0.8%    |
| Nvidia MCP73 Ethernet                                                          | 3        | 0.8%    |
| Intel Ethernet Controller I225-V                                               | 3        | 0.8%    |
| Intel Ethernet Connection I217-LM                                              | 3        | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 0.8%    |
| Intel 82566DM Gigabit Network Connection                                       | 3        | 0.8%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                        | 3        | 0.8%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 2        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 0.54%   |
| Nvidia MCP79 Ethernet                                                          | 2        | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2        | 0.54%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 2        | 0.54%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 0.54%   |
| Intel Ethernet Connection I217-V                                               | 2        | 0.54%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 2        | 0.54%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 2        | 0.54%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 2        | 0.54%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                           | 2        | 0.54%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1        | 0.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1        | 0.27%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1        | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 0.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1        | 0.27%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1        | 0.27%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 0.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1        | 0.27%   |
| Nvidia MCP77 Ethernet                                                          | 1        | 0.27%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1        | 0.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.27%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1        | 0.27%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.27%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.27%   |
| Intel Ethernet Controller X550                                                 | 1        | 0.27%   |
| Intel Ethernet Connection I219-LM                                              | 1        | 0.27%   |
| Intel Ethernet Connection I218-LM                                              | 1        | 0.27%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.27%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.27%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 0.27%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 0.27%   |
| Intel 82578DC Gigabit Network Connection                                       | 1        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 338      | 73%     |
| WiFi     | 121      | 26.13%  |
| Modem    | 4        | 0.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 265      | 75.5%   |
| WiFi     | 86       | 24.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 251      | 73.39%  |
| 2     | 80       | 23.39%  |
| 3     | 8        | 2.34%   |
| 5     | 2        | 0.58%   |
| 6     | 1        | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 285      | 82.13%  |
| Yes  | 62       | 17.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 22       | 32.84%  |
| Intel                           | 17       | 25.37%  |
| ASUSTek Computer                | 13       | 19.4%   |
| Realtek Semiconductor           | 7        | 10.45%  |
| Broadcom                        | 2        | 2.99%   |
| Belkin Components               | 2        | 2.99%   |
| Toshiba                         | 1        | 1.49%   |
| Qualcomm Atheros Communications | 1        | 1.49%   |
| IMC Networks                    | 1        | 1.49%   |
| Apple                           | 1        | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 22       | 32.84%  |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 8        | 11.94%  |
| Intel AX200 Bluetooth                                | 6        | 8.96%   |
| Intel Bluetooth wireless interface                   | 5        | 7.46%   |
| Realtek Bluetooth Radio                              | 4        | 5.97%   |
| Realtek  Bluetooth 4.2 Adapter                       | 3        | 4.48%   |
| Intel Wireless-AC 3168 Bluetooth                     | 3        | 4.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2        | 2.99%   |
| Broadcom BCM20702A0 Bluetooth 4.0                    | 2        | 2.99%   |
| ASUS ASUS USB-BT500                                  | 2        | 2.99%   |
| Toshiba Atheros AR3012 Bluetooth                     | 1        | 1.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller       | 1        | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1        | 1.49%   |
| IMC Networks Bluetooth Device                        | 1        | 1.49%   |
| Belkin Components Bluetooth Mini Dongle              | 1        | 1.49%   |
| Belkin Components Bluetooth Device with trace filter | 1        | 1.49%   |
| ASUS Qualcomm Bluetooth 4.1                          | 1        | 1.49%   |
| ASUS Bluetooth Radio                                 | 1        | 1.49%   |
| ASUS Bluetooth Adapter                               | 1        | 1.49%   |
| Apple Bluetooth HCI                                  | 1        | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 215      | 38.46%  |
| AMD                              | 144      | 25.76%  |
| Nvidia                           | 119      | 21.29%  |
| Creative Labs                    | 19       | 3.4%    |
| C-Media Electronics              | 14       | 2.5%    |
| Logitech                         | 7        | 1.25%   |
| Kingston Technology              | 6        | 1.07%   |
| JMTek                            | 5        | 0.89%   |
| Texas Instruments                | 3        | 0.54%   |
| Silicon Integrated Systems [SiS] | 3        | 0.54%   |
| VIA Technologies                 | 2        | 0.36%   |
| Razer USA                        | 2        | 0.36%   |
| WinChipHead                      | 1        | 0.18%   |
| ULi Electronics                  | 1        | 0.18%   |
| Turtle Beach                     | 1        | 0.18%   |
| SteelSeries ApS                  | 1        | 0.18%   |
| Sennheiser Communications        | 1        | 0.18%   |
| Samsung Electronics              | 1        | 0.18%   |
| Samson Technologies              | 1        | 0.18%   |
| Realtek Semiconductor            | 1        | 0.18%   |
| Plantronics                      | 1        | 0.18%   |
| Microchip Technology             | 1        | 0.18%   |
| Hewlett-Packard                  | 1        | 0.18%   |
| Harman                           | 1        | 0.18%   |
| Guillemot                        | 1        | 0.18%   |
| Generalplus Technology           | 1        | 0.18%   |
| Evolution Electronics            | 1        | 0.18%   |
| EGO SYStems                      | 1        | 0.18%   |
| Corsair                          | 1        | 0.18%   |
| Blue Microphones                 | 1        | 0.18%   |
| ASUSTek Computer                 | 1        | 0.18%   |
| Apple                            | 1        | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 37       | 5.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 30       | 4.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 22       | 3.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 22       | 3.5%    |
| AMD Starship/Matisse HD Audio Controller                                          | 20       | 3.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 3.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 19       | 3.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 18       | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 18       | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 15       | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 15       | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                        | 14       | 2.23%   |
| Nvidia High Definition Audio Controller                                           | 12       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 1.75%   |
| Intel 200 Series PCH HD Audio                                                     | 10       | 1.59%   |
| AMD Family 17h/19h HD Audio Controller                                            | 10       | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 1.43%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 9        | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                                     | 8        | 1.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 8        | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 8        | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                                     | 7        | 1.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7        | 1.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 7        | 1.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 0.95%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 6        | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6        | 0.95%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 0.95%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 5        | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 0.79%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 5        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 0.79%   |
| AMD Navi 10 HDMI Audio                                                            | 5        | 0.79%   |
| AMD FCH Azalia Controller                                                         | 5        | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 0.64%   |
| Nvidia GT216 HDMI Audio Controller                                                | 4        | 0.64%   |
| Nvidia GM204 High Definition Audio Controller                                     | 4        | 0.64%   |
| Kingston Technology HyperX 7.1 Audio                                              | 4        | 0.64%   |
| Intel Sunrise Point-LP HD Audio                                                   | 4        | 0.64%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 0.64%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 4        | 0.64%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 4        | 0.64%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 4        | 0.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 4        | 0.64%   |
| AMD Kabini HDMI/DP Audio                                                          | 4        | 0.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 4        | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.48%   |
| Nvidia MCP73 High Definition Audio                                                | 3        | 0.48%   |
| Nvidia GP102 HDMI Audio Controller                                                | 3        | 0.48%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.48%   |
| Nvidia GK106 HDMI Audio Controller                                                | 3        | 0.48%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 3        | 0.48%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 3        | 0.48%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 3        | 0.48%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 3        | 0.48%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 3        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 37       | 24.03%  |
| Unknown             | 34       | 22.08%  |
| G.Skill             | 20       | 12.99%  |
| Crucial             | 13       | 8.44%   |
| SK hynix            | 12       | 7.79%   |
| Corsair             | 10       | 6.49%   |
| Samsung Electronics | 9        | 5.84%   |
| Team                | 5        | 3.25%   |
| Unknown (ABCD)      | 1        | 0.65%   |
| Unifosa             | 1        | 0.65%   |
| Transcend           | 1        | 0.65%   |
| Silicon Power       | 1        | 0.65%   |
| Ramaxel Technology  | 1        | 0.65%   |
| Patriot             | 1        | 0.65%   |
| Nanya Technology    | 1        | 0.65%   |
| Micron Technology   | 1        | 0.65%   |
| Lexar               | 1        | 0.65%   |
| Infineon            | 1        | 0.65%   |
| Elpida              | 1        | 0.65%   |
| Apacer              | 1        | 0.65%   |
| A-DATA Technology   | 1        | 0.65%   |
| Unknown             | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                  | 3        | 1.69%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 3        | 1.69%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 2        | 1.12%   |
| Unknown RAM Module 4096MB DIMM                               | 2        | 1.12%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 2        | 1.12%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s          | 2        | 1.12%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s      | 2        | 1.12%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s        | 2        | 1.12%   |
| G.Skill RAM F4-2400C15-16GIS 16GB DIMM DDR4 2400MT/s         | 2        | 1.12%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s        | 2        | 1.12%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s        | 2        | 1.12%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 2        | 1.12%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                 | 1        | 0.56%   |
| Unknown RAM Module 512MB DIMM 533MT/s                        | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 667MT/s                          | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 400MT/s                          | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM                                  | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                    | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2                             | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM                                  | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                 | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                  | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                      | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM                               | 1        | 0.56%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1        | 0.56%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                  | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR                           | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                       | 1        | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 1        | 0.56%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.56%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s             | 1        | 0.56%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s          | 1        | 0.56%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s           | 1        | 0.56%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                   | 1        | 0.56%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                   | 1        | 0.56%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                   | 1        | 0.56%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.56%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.56%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.56%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s      | 1        | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s              | 1        | 0.56%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.56%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1        | 0.56%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8192MB DIMM DDR4 2667MT/s      | 1        | 0.56%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8192MB DIMM DDR4 2465MT/s      | 1        | 0.56%   |
| Silicon Power RAM SP008GBLFU240B02 8GB DIMM DDR4 2400MT/s    | 1        | 0.56%   |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s                 | 1        | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 55       | 37.93%  |
| DDR4    | 49       | 33.79%  |
| Unknown | 17       | 11.72%  |
| DDR2    | 13       | 8.97%   |
| SDRAM   | 8        | 5.52%   |
| DDR     | 2        | 1.38%   |
| LPDDR4  | 1        | 0.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 140      | 97.22%  |
| SODIMM | 4        | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 49       | 32.03%  |
| 4096  | 41       | 26.8%   |
| 2048  | 30       | 19.61%  |
| 16384 | 20       | 13.07%  |
| 1024  | 9        | 5.88%   |
| 32768 | 2        | 1.31%   |
| 512   | 2        | 1.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 39       | 23.93%  |
| 1333    | 21       | 12.88%  |
| 2400    | 12       | 7.36%   |
| Unknown | 10       | 6.13%   |
| 3200    | 9        | 5.52%   |
| 2133    | 8        | 4.91%   |
| 667     | 7        | 4.29%   |
| 2667    | 6        | 3.68%   |
| 800     | 6        | 3.68%   |
| 3600    | 5        | 3.07%   |
| 1867    | 5        | 3.07%   |
| 3000    | 4        | 2.45%   |
| 2666    | 4        | 2.45%   |
| 533     | 4        | 2.45%   |
| 3466    | 2        | 1.23%   |
| 2048    | 2        | 1.23%   |
| 2000    | 2        | 1.23%   |
| 1800    | 2        | 1.23%   |
| 400     | 2        | 1.23%   |
| 43889   | 1        | 0.61%   |
| 3800    | 1        | 0.61%   |
| 3400    | 1        | 0.61%   |
| 3334    | 1        | 0.61%   |
| 3067    | 1        | 0.61%   |
| 3066    | 1        | 0.61%   |
| 2933    | 1        | 0.61%   |
| 2733    | 1        | 0.61%   |
| 2465    | 1        | 0.61%   |
| 2187    | 1        | 0.61%   |
| 2134    | 1        | 0.61%   |
| 1866    | 1        | 0.61%   |
| 1067    | 1        | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 14       | 70%     |
| Canon                 | 2        | 10%     |
| Brother Industries    | 2        | 10%     |
| Xerox                 | 1        | 5%      |
| Lexmark International | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| HP Deskjet 1050 J410            | 4        | 18.18%  |
| Xerox Phaser 6000B              | 1        | 4.55%   |
| Lexmark International E120(n)   | 1        | 4.55%   |
| HP Officejet 4620 series        | 1        | 4.55%   |
| HP Officejet 4500 G510g-m       | 1        | 4.55%   |
| HP LaserJet Professional P1102w | 1        | 4.55%   |
| HP LaserJet M14-M17             | 1        | 4.55%   |
| HP ENVY 6000 series             | 1        | 4.55%   |
| HP ENVY 4520 series             | 1        | 4.55%   |
| HP DeskJet F300 series          | 1        | 4.55%   |
| HP DeskJet 930c                 | 1        | 4.55%   |
| HP DeskJet 3630 series          | 1        | 4.55%   |
| HP Deskjet 3050 J610 series     | 1        | 4.55%   |
| HP DeskJet 2700 series          | 1        | 4.55%   |
| Canon TS6300 series             | 1        | 4.55%   |
| Canon PIXMA MG2900 Series       | 1        | 4.55%   |
| Canon LBP6200                   | 1        | 4.55%   |
| Brother DCP-L3550CDW            | 1        | 4.55%   |
| Brother DCP-1610W               | 1        | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Mustek Systems  | 3        | 37.5%   |
| Canon           | 3        | 37.5%   |
| Seiko Epson     | 1        | 12.5%   |
| Hewlett-Packard | 1        | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB    | 2        | 25%     |
| Seiko Epson GT-X770 [Perfection V500] | 1        | 12.5%   |
| Mustek Systems BearPaw 2448 CU Pro    | 1        | 12.5%   |
| HP ScanJet 5300c/5370c                | 1        | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20    | 1        | 12.5%   |
| Canon CanoScan LiDE 110               | 1        | 12.5%   |
| Canon CanoScan 4400F                  | 1        | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 17       | 25.76%  |
| Microsoft                     | 12       | 18.18%  |
| Hewlett-Packard               | 7        | 10.61%  |
| Creative Technology           | 6        | 9.09%   |
| Microdia                      | 3        | 4.55%   |
| Aveo Technology               | 3        | 4.55%   |
| Sunplus Innovation Technology | 2        | 3.03%   |
| Samsung Electronics           | 2        | 3.03%   |
| Realtek Semiconductor         | 2        | 3.03%   |
| Generalplus Technology        | 2        | 3.03%   |
| Cubeternet                    | 2        | 3.03%   |
| Chicony Electronics           | 2        | 3.03%   |
| Z-Star Microelectronics       | 1        | 1.52%   |
| WaveRider Communications      | 1        | 1.52%   |
| Razer USA                     | 1        | 1.52%   |
| Philips (or NXP)              | 1        | 1.52%   |
| Huawei Technologies           | 1        | 1.52%   |
| Apple                         | 1        | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                     | 7        | 10.61%  |
| HP Webcam HD 2300                             | 6        | 9.09%   |
| Logitech Webcam C270                          | 5        | 7.58%   |
| Logitech Webcam C310                          | 3        | 4.55%   |
| Logitech C922 Pro Stream Webcam               | 3        | 4.55%   |
| Creative Live! Cam Sync 1080p                 | 3        | 4.55%   |
| Aveo UVC camera (Bresser microscope)          | 3        | 4.55%   |
| Samsung Galaxy series, misc. (MTP mode)       | 2        | 3.03%   |
| Microsoft LifeCam VX-800                      | 2        | 3.03%   |
| Microsoft LifeCam VX-2000                     | 2        | 3.03%   |
| Microdia Sonix USB 2.0 Camera                 | 2        | 3.03%   |
| Logitech QuickCam Express                     | 2        | 3.03%   |
| Generalplus 808 Camera #9 (web-cam mode)      | 2        | 3.03%   |
| Z-Star Vega USB 2.0 Camera                    | 1        | 1.52%   |
| WaveRider USB Live camera                     | 1        | 1.52%   |
| Sunplus HD 720P webcam                        | 1        | 1.52%   |
| Sunplus Depstech webcam MIC                   | 1        | 1.52%   |
| Realtek Streaming Webcam                      | 1        | 1.52%   |
| Realtek NexiGo N660P FHD Webcam               | 1        | 1.52%   |
| Razer USA Razer Kiyo Pro                      | 1        | 1.52%   |
| Philips (or NXP) Webcam SPC530NC              | 1        | 1.52%   |
| Microsoft LifeCam VX-700                      | 1        | 1.52%   |
| Microdia CyberTrack H6                        | 1        | 1.52%   |
| Logitech Webcam C200                          | 1        | 1.52%   |
| Logitech Webcam C170                          | 1        | 1.52%   |
| Logitech QuickCam Pro 4000                    | 1        | 1.52%   |
| Logitech HD Webcam C525                       | 1        | 1.52%   |
| Huawei UVC Camera                             | 1        | 1.52%   |
| HP Webcam HD 4310                             | 1        | 1.52%   |
| Cubeternet USB2.0 Camera                      | 1        | 1.52%   |
| Cubeternet GL-UPC822 UVC WebCam               | 1        | 1.52%   |
| Creative Webcam Live! Effects                 | 1        | 1.52%   |
| Creative VF0540 Live! Cam Video IM/Video Chat | 1        | 1.52%   |
| Creative Live! Cam Sync HD [VF0770]           | 1        | 1.52%   |
| Chicony HP High Definition 1MP Webcam         | 1        | 1.52%   |
| Chicony CNF7166                               | 1        | 1.52%   |
| Apple iSight in LED Cinema Display            | 1        | 1.52%   |

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


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AuthenTec AES1600 | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 3        | 42.86%  |
| Bit4id                | 2        | 28.57%  |
| Realtek Semiconductor | 1        | 14.29%  |
| Alcor Micro           | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 3        | 42.86%  |
| Bit4id miniLector EVO                             | 2        | 28.57%  |
| Realtek Semiconductor Smart Card Reader Interface | 1        | 14.29%  |
| Alcor Micro Watchdata W 1981                      | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 304      | 87.36%  |
| 1     | 40       | 11.49%  |
| 2     | 4        | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 21       | 44.68%  |
| Chipcard                 | 6        | 12.77%  |
| Net/wireless             | 5        | 10.64%  |
| Multimedia controller    | 3        | 6.38%   |
| Bluetooth                | 3        | 6.38%   |
| Network                  | 2        | 4.26%   |
| Camera                   | 2        | 4.26%   |
| Net/ethernet             | 1        | 2.13%   |
| Modem                    | 1        | 2.13%   |
| Fingerprint reader       | 1        | 2.13%   |
| Communication controller | 1        | 2.13%   |
| Card reader              | 1        | 2.13%   |


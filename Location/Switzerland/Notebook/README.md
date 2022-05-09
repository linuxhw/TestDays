Linux in Switzerland - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

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

Total: 1193

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Apple         | MacBookPro9,2               | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| Dell          | Inspiron 1720               | [e95b0172b4](https://linux-hardware.org/?probe=e95b0172b4) | May 06, 2022 |
| Dell          | Inspiron 1720               | [a888a93774](https://linux-hardware.org/?probe=a888a93774) | May 06, 2022 |
| HP            | ProBook 450 G4              | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [94806fd9bf](https://linux-hardware.org/?probe=94806fd9bf) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ebc49550d4](https://linux-hardware.org/?probe=ebc49550d4) | May 05, 2022 |
| Apple         | MacBookPro11,3              | [21f611f3c7](https://linux-hardware.org/?probe=21f611f3c7) | May 03, 2022 |
| Dell          | XPS 13 9380                 | [aa294d2650](https://linux-hardware.org/?probe=aa294d2650) | May 02, 2022 |
| Acer          | Aspire A515-56              | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| HP            | ENVY 17                     | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| Dell          | XPS 13 9380                 | [c052066ee4](https://linux-hardware.org/?probe=c052066ee4) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [37b1ff3685](https://linux-hardware.org/?probe=37b1ff3685) | Apr 21, 2022 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | [1cabdda156](https://linux-hardware.org/?probe=1cabdda156) | Apr 21, 2022 |
| Lenovo        | ThinkPad E580 20KS006EMZ    | [4d54c594ff](https://linux-hardware.org/?probe=4d54c594ff) | Apr 20, 2022 |
| System76      | Galago Pro                  | [32b09fd215](https://linux-hardware.org/?probe=32b09fd215) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | [451ce5305a](https://linux-hardware.org/?probe=451ce5305a) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | [fa843a199c](https://linux-hardware.org/?probe=fa843a199c) | Apr 19, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [50b0cb93c7](https://linux-hardware.org/?probe=50b0cb93c7) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [6d63a9c8bc](https://linux-hardware.org/?probe=6d63a9c8bc) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Acer          | TMP455-M                    | [451dbf0a20](https://linux-hardware.org/?probe=451dbf0a20) | Apr 15, 2022 |
| Acer          | TMP455-M                    | [b7b9924190](https://linux-hardware.org/?probe=b7b9924190) | Apr 15, 2022 |
| Acer          | Swift SF514-51              | [147a0161aa](https://linux-hardware.org/?probe=147a0161aa) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NY000JM... | [e93e7d9ad1](https://linux-hardware.org/?probe=e93e7d9ad1) | Apr 13, 2022 |
| Dell          | Latitude E7240              | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| Dell          | Latitude D400               | [46981d939b](https://linux-hardware.org/?probe=46981d939b) | Apr 11, 2022 |
| Apple         | MacBookPro10,1              | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| HP            | ProBook 4530s               | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| HP            | ProBook 450 G5              | [3aa8c7cbc6](https://linux-hardware.org/?probe=3aa8c7cbc6) | Apr 04, 2022 |
| Acer          | Swift SF314-57              | [e43f33eef1](https://linux-hardware.org/?probe=e43f33eef1) | Apr 03, 2022 |
| QUANMAX       | Platin SE                   | [5090da9cbf](https://linux-hardware.org/?probe=5090da9cbf) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| QUANMAX       | Platin SE                   | [2388fe9587](https://linux-hardware.org/?probe=2388fe9587) | Apr 03, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [bc44d9076b](https://linux-hardware.org/?probe=bc44d9076b) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Acer          | Aspire E5-773G              | [b43b436e59](https://linux-hardware.org/?probe=b43b436e59) | Mar 31, 2022 |
| HP            | Pavilion g7                 | [44a6ea06b0](https://linux-hardware.org/?probe=44a6ea06b0) | Mar 28, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [edbd5fd6aa](https://linux-hardware.org/?probe=edbd5fd6aa) | Mar 27, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | [95526f5b3e](https://linux-hardware.org/?probe=95526f5b3e) | Mar 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [ed949b0853](https://linux-hardware.org/?probe=ed949b0853) | Mar 24, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [684a4fd3c3](https://linux-hardware.org/?probe=684a4fd3c3) | Mar 24, 2022 |
| Dell          | XPS 15 7590                 | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Dell          | Inspiron 7400               | [a17dc3be48](https://linux-hardware.org/?probe=a17dc3be48) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| HP            | EliteBook 840 G5            | [dd13dcfd89](https://linux-hardware.org/?probe=dd13dcfd89) | Mar 22, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [28c8bc52b8](https://linux-hardware.org/?probe=28c8bc52b8) | Mar 22, 2022 |
| ASUSTek       | K73E                        | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [7664c536f4](https://linux-hardware.org/?probe=7664c536f4) | Mar 18, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [7649fad366](https://linux-hardware.org/?probe=7649fad366) | Mar 14, 2022 |
| Dell          | Latitude 5400               | [e23429d8ea](https://linux-hardware.org/?probe=e23429d8ea) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK E782               | [77b3a7f272](https://linux-hardware.org/?probe=77b3a7f272) | Mar 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f735730566](https://linux-hardware.org/?probe=f735730566) | Mar 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e8ffb57db8](https://linux-hardware.org/?probe=e8ffb57db8) | Mar 11, 2022 |
| Acer          | Aspire V3-772G              | [1526117b64](https://linux-hardware.org/?probe=1526117b64) | Mar 10, 2022 |
| HP            | ProBook 470 G5              | [c98fcbec3c](https://linux-hardware.org/?probe=c98fcbec3c) | Mar 10, 2022 |
| HUAWEI        | WRT-WX9                     | [2bd4f9201a](https://linux-hardware.org/?probe=2bd4f9201a) | Mar 09, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Dell          | XPS 13 9350                 | [ce5fd5227f](https://linux-hardware.org/?probe=ce5fd5227f) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| HP            | EliteBook 820 G3            | [fd01513251](https://linux-hardware.org/?probe=fd01513251) | Mar 04, 2022 |
| Acer          | Swift SF314-42              | [5c8b94d514](https://linux-hardware.org/?probe=5c8b94d514) | Mar 03, 2022 |
| Dell          | XPS 13 9370                 | [75b63c2d2c](https://linux-hardware.org/?probe=75b63c2d2c) | Mar 02, 2022 |
| Medion        | P6624                       | [0a502fd230](https://linux-hardware.org/?probe=0a502fd230) | Feb 28, 2022 |
| Dell          | XPS 15 9560                 | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| Notebook      | N13xWU                      | [50acf36954](https://linux-hardware.org/?probe=50acf36954) | Feb 25, 2022 |
| Acer          | TMP455-MG                   | [f1a500ae43](https://linux-hardware.org/?probe=f1a500ae43) | Feb 25, 2022 |
| Dell          | Precision 3551              | [9394fc8844](https://linux-hardware.org/?probe=9394fc8844) | Feb 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [923930ee4e](https://linux-hardware.org/?probe=923930ee4e) | Feb 22, 2022 |
| Dell          | XPS 15 9570                 | [226452fec0](https://linux-hardware.org/?probe=226452fec0) | Feb 21, 2022 |
| ASUSTek       | G551JK                      | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [b0e0d82d12](https://linux-hardware.org/?probe=b0e0d82d12) | Feb 20, 2022 |
| Dell          | Latitude 7490               | [2620ebab43](https://linux-hardware.org/?probe=2620ebab43) | Feb 15, 2022 |
| Acer          | Aspire 3820                 | [7364dc5d5e](https://linux-hardware.org/?probe=7364dc5d5e) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | [34bb725d27](https://linux-hardware.org/?probe=34bb725d27) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | [3dd59d8ebe](https://linux-hardware.org/?probe=3dd59d8ebe) | Feb 13, 2022 |
| HP            | Compaq 15                   | [fa22db8854](https://linux-hardware.org/?probe=fa22db8854) | Feb 12, 2022 |
| Acer          | Aspire V3-772G              | [6a16b1953c](https://linux-hardware.org/?probe=6a16b1953c) | Feb 11, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8b31b460fc](https://linux-hardware.org/?probe=8b31b460fc) | Feb 11, 2022 |
| PC Special... | NH5x_7xRCx,RDx              | [3fad293703](https://linux-hardware.org/?probe=3fad293703) | Feb 10, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | [e06f742b06](https://linux-hardware.org/?probe=e06f742b06) | Feb 09, 2022 |
| whyopencom... | Unknown                     | [ed4f02d91d](https://linux-hardware.org/?probe=ed4f02d91d) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | [f252168753](https://linux-hardware.org/?probe=f252168753) | Feb 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [73738d3f0c](https://linux-hardware.org/?probe=73738d3f0c) | Feb 08, 2022 |
| Quanta        | TW8/SW8/DW8                 | [a542c42556](https://linux-hardware.org/?probe=a542c42556) | Feb 08, 2022 |
| Dell          | Latitude E5410              | [fd73c50faa](https://linux-hardware.org/?probe=fd73c50faa) | Feb 07, 2022 |
| Acer          | Aspire A515-52G             | [cfc69482e3](https://linux-hardware.org/?probe=cfc69482e3) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [99770a5e77](https://linux-hardware.org/?probe=99770a5e77) | Feb 06, 2022 |
| Packard Be... | EasyNote TV44HC             | [60aaa89bfa](https://linux-hardware.org/?probe=60aaa89bfa) | Feb 03, 2022 |
| Acer          | Aspire V3-772G              | [1e4b8a880e](https://linux-hardware.org/?probe=1e4b8a880e) | Jan 29, 2022 |
| Clevo         | W76x/M77xCUH                | [48d0efb057](https://linux-hardware.org/?probe=48d0efb057) | Jan 26, 2022 |
| AMI           | Cherry Trail Tablet         | [0560bf99e5](https://linux-hardware.org/?probe=0560bf99e5) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [dbeeb0a6f3](https://linux-hardware.org/?probe=dbeeb0a6f3) | Jan 24, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [8ee01c475e](https://linux-hardware.org/?probe=8ee01c475e) | Jan 23, 2022 |
| Packard Be... | EasyNote TV44HC             | [38fb76e085](https://linux-hardware.org/?probe=38fb76e085) | Jan 23, 2022 |
| Apple         | MacBookPro5,3               | [e0b61bcde4](https://linux-hardware.org/?probe=e0b61bcde4) | Jan 22, 2022 |
| Packard Be... | EasyNote TV44HC             | [d2a1835844](https://linux-hardware.org/?probe=d2a1835844) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| Packard Be... | EasyNote TV44HC             | [556cf29fcc](https://linux-hardware.org/?probe=556cf29fcc) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| HP            | Pavilion g7                 | [f789fa0e4b](https://linux-hardware.org/?probe=f789fa0e4b) | Jan 20, 2022 |
| HP            | Pavilion g7                 | [064474c7e0](https://linux-hardware.org/?probe=064474c7e0) | Jan 20, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | [e2161b5856](https://linux-hardware.org/?probe=e2161b5856) | Jan 20, 2022 |
| ASUSTek       | UX330UAK                    | [3749e7dc2e](https://linux-hardware.org/?probe=3749e7dc2e) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [1478a3da5a](https://linux-hardware.org/?probe=1478a3da5a) | Jan 17, 2022 |
| Notebook      | PCx0Dx                      | [1c35674fd1](https://linux-hardware.org/?probe=1c35674fd1) | Jan 17, 2022 |
| Acer          | Aspire E5-511               | [c2691bf00b](https://linux-hardware.org/?probe=c2691bf00b) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [80a80d7619](https://linux-hardware.org/?probe=80a80d7619) | Jan 16, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| Acer          | Aspire V3-772G              | [c6dc2d8971](https://linux-hardware.org/?probe=c6dc2d8971) | Jan 14, 2022 |
| Dell          | XPS 15 9510                 | [642e01d970](https://linux-hardware.org/?probe=642e01d970) | Jan 13, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [06f3fa0e22](https://linux-hardware.org/?probe=06f3fa0e22) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [ec88cd8e93](https://linux-hardware.org/?probe=ec88cd8e93) | Jan 12, 2022 |
| Acer          | Aspire V3-772G              | [aaf1227ec4](https://linux-hardware.org/?probe=aaf1227ec4) | Jan 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [7ce7a30da1](https://linux-hardware.org/?probe=7ce7a30da1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [ac620bc1b6](https://linux-hardware.org/?probe=ac620bc1b6) | Jan 10, 2022 |
| Acer          | Aspire R7-572G              | [dc4a930b99](https://linux-hardware.org/?probe=dc4a930b99) | Jan 08, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4d67659f6c](https://linux-hardware.org/?probe=4d67659f6c) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [b3428338c0](https://linux-hardware.org/?probe=b3428338c0) | Jan 07, 2022 |
| ASUSTek       | K53U                        | [62410e0adc](https://linux-hardware.org/?probe=62410e0adc) | Jan 07, 2022 |
| Apple         | MacBookPro14,3              | [96b76bc44b](https://linux-hardware.org/?probe=96b76bc44b) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [0551fb871e](https://linux-hardware.org/?probe=0551fb871e) | Dec 31, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [40eee8c893](https://linux-hardware.org/?probe=40eee8c893) | Dec 30, 2021 |
| Dell          | Latitude E5420              | [a2d1902586](https://linux-hardware.org/?probe=a2d1902586) | Dec 29, 2021 |
| HP            | EliteBook 840 G1            | [ca7f3a7275](https://linux-hardware.org/?probe=ca7f3a7275) | Dec 29, 2021 |
| Acer          | Aspire V3-572               | [57f2afd2a3](https://linux-hardware.org/?probe=57f2afd2a3) | Dec 28, 2021 |
| HP            | Pavilion dv7                | [79cc0303f4](https://linux-hardware.org/?probe=79cc0303f4) | Dec 27, 2021 |
| HP            | Pavilion dv7                | [3ab4ebdbfd](https://linux-hardware.org/?probe=3ab4ebdbfd) | Dec 27, 2021 |
| HP            | Pavilion dv7                | [d9456116de](https://linux-hardware.org/?probe=d9456116de) | Dec 27, 2021 |
| HP            | 300-250                     | [94f3405ce4](https://linux-hardware.org/?probe=94f3405ce4) | Dec 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [cb4cb1ea51](https://linux-hardware.org/?probe=cb4cb1ea51) | Dec 26, 2021 |
| Lenovo        | B50-10 80QR                 | [0195687c06](https://linux-hardware.org/?probe=0195687c06) | Dec 26, 2021 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [7ebdb585ab](https://linux-hardware.org/?probe=7ebdb585ab) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| HP            | ProBook 4740s               | [149c7edca2](https://linux-hardware.org/?probe=149c7edca2) | Dec 23, 2021 |
| Acer          | Aspire A315-31              | [a55ed0d992](https://linux-hardware.org/?probe=a55ed0d992) | Dec 20, 2021 |
| HP            | Pavilion dv7                | [e1ac371752](https://linux-hardware.org/?probe=e1ac371752) | Dec 18, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [6e8ba23594](https://linux-hardware.org/?probe=6e8ba23594) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [70a9d341b1](https://linux-hardware.org/?probe=70a9d341b1) | Dec 16, 2021 |
| Dell          | Latitude E5410              | [433ad50dd3](https://linux-hardware.org/?probe=433ad50dd3) | Dec 16, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [d103baf427](https://linux-hardware.org/?probe=d103baf427) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | [d680085d25](https://linux-hardware.org/?probe=d680085d25) | Dec 15, 2021 |
| Dell          | Inspiron 16 7610            | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Apple         | MacBookAir3,1               | [edebb4d39b](https://linux-hardware.org/?probe=edebb4d39b) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| ASUSTek       | N551JW                      | [95f2828cd6](https://linux-hardware.org/?probe=95f2828cd6) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1dba035790](https://linux-hardware.org/?probe=1dba035790) | Dec 07, 2021 |
| Acer          | Aspire E5-511               | [9e8fd519f0](https://linux-hardware.org/?probe=9e8fd519f0) | Dec 07, 2021 |
| HP            | ENVY dv7                    | [1ab140a424](https://linux-hardware.org/?probe=1ab140a424) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [d78c027940](https://linux-hardware.org/?probe=d78c027940) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| Razer         | Blade Stealth               | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [09a9693ee7](https://linux-hardware.org/?probe=09a9693ee7) | Dec 04, 2021 |
| HP            | ProBook 450 G4              | [0cc317d213](https://linux-hardware.org/?probe=0cc317d213) | Dec 04, 2021 |
| Lenovo        | G50-70 20351                | [6de772fed7](https://linux-hardware.org/?probe=6de772fed7) | Nov 27, 2021 |
| MSI           | MS-17G                      | [0fd0763f15](https://linux-hardware.org/?probe=0fd0763f15) | Nov 26, 2021 |
| MSI           | MS-17G                      | [00c3cd9a83](https://linux-hardware.org/?probe=00c3cd9a83) | Nov 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [fbec23b579](https://linux-hardware.org/?probe=fbec23b579) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| Toshiba       | Satellite C660              | [ab7e1ab2f6](https://linux-hardware.org/?probe=ab7e1ab2f6) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | [bf8a290d91](https://linux-hardware.org/?probe=bf8a290d91) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | [3b2959cf2d](https://linux-hardware.org/?probe=3b2959cf2d) | Nov 23, 2021 |
| HP            | Notebook                    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| Lenovo        | ThinkPad X250 20CM004UGE    | [26bd0cd883](https://linux-hardware.org/?probe=26bd0cd883) | Nov 22, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [012d05e37c](https://linux-hardware.org/?probe=012d05e37c) | Nov 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [80d0bc77b6](https://linux-hardware.org/?probe=80d0bc77b6) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Google        | Lars                        | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [2067df0e1e](https://linux-hardware.org/?probe=2067df0e1e) | Nov 16, 2021 |
| Acer          | Aspire V3-772G              | [1e66881588](https://linux-hardware.org/?probe=1e66881588) | Nov 16, 2021 |
| HP            | ZBook 15 G2                 | [f40c4458aa](https://linux-hardware.org/?probe=f40c4458aa) | Nov 16, 2021 |
| Dell          | Latitude E7240              | [aaf6395a70](https://linux-hardware.org/?probe=aaf6395a70) | Nov 14, 2021 |
| Dell          | Latitude E7270              | [b462d15a6b](https://linux-hardware.org/?probe=b462d15a6b) | Nov 14, 2021 |
| HP            | EliteBook 735 G5            | [79600db29f](https://linux-hardware.org/?probe=79600db29f) | Nov 14, 2021 |
| HP            | Pavilion 15                 | [366558c9a6](https://linux-hardware.org/?probe=366558c9a6) | Nov 11, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [f9f140b132](https://linux-hardware.org/?probe=f9f140b132) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3876a60641](https://linux-hardware.org/?probe=3876a60641) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [92b50813ac](https://linux-hardware.org/?probe=92b50813ac) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [258574fc87](https://linux-hardware.org/?probe=258574fc87) | Nov 10, 2021 |
| ASUSTek       | UX430UNR                    | [292992ce5a](https://linux-hardware.org/?probe=292992ce5a) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | [6f9b7bffd1](https://linux-hardware.org/?probe=6f9b7bffd1) | Nov 06, 2021 |
| Acer          | V3-771                      | [bf99ad481c](https://linux-hardware.org/?probe=bf99ad481c) | Nov 04, 2021 |
| ASUSTek       | U36SD                       | [84e47bb477](https://linux-hardware.org/?probe=84e47bb477) | Nov 03, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [8686d92d45](https://linux-hardware.org/?probe=8686d92d45) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [3f7a2585fe](https://linux-hardware.org/?probe=3f7a2585fe) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [e6958a71d6](https://linux-hardware.org/?probe=e6958a71d6) | Oct 31, 2021 |
| Acer          | TravelMate P459-G2-MG       | [05087f89c1](https://linux-hardware.org/?probe=05087f89c1) | Oct 30, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| Acer          | TravelMate P459-G2-MG       | [4a80b949aa](https://linux-hardware.org/?probe=4a80b949aa) | Oct 30, 2021 |
| HP            | EliteBook 840 G6            | [d0307fd66e](https://linux-hardware.org/?probe=d0307fd66e) | Oct 29, 2021 |
| HP            | EliteBook 840 G6            | [a5abf5d5ee](https://linux-hardware.org/?probe=a5abf5d5ee) | Oct 29, 2021 |
| Medion        | S3409 MD60234               | [4bb4415dae](https://linux-hardware.org/?probe=4bb4415dae) | Oct 27, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [304ebad6f7](https://linux-hardware.org/?probe=304ebad6f7) | Oct 27, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B80... | [a567978a3c](https://linux-hardware.org/?probe=a567978a3c) | Oct 26, 2021 |
| Acer          | V3-771                      | [b953b67d06](https://linux-hardware.org/?probe=b953b67d06) | Oct 25, 2021 |
| TUXEDO        | BC1510 1710                 | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Packard Be... | EasyNote TV44HC             | [5ebedd4a1c](https://linux-hardware.org/?probe=5ebedd4a1c) | Oct 23, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [3517455df5](https://linux-hardware.org/?probe=3517455df5) | Oct 22, 2021 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b198944ad7](https://linux-hardware.org/?probe=b198944ad7) | Oct 22, 2021 |
| Acer          | Swift SF314-43              | [ef2da9ecca](https://linux-hardware.org/?probe=ef2da9ecca) | Oct 21, 2021 |
| Medion        | E6226                       | [ebc0f3d72b](https://linux-hardware.org/?probe=ebc0f3d72b) | Oct 20, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4f400bb9ab](https://linux-hardware.org/?probe=4f400bb9ab) | Oct 20, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4d7535970d](https://linux-hardware.org/?probe=4d7535970d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [d8302cc197](https://linux-hardware.org/?probe=d8302cc197) | Oct 19, 2021 |
| whyopencom... | Unknown                     | [90b1930c43](https://linux-hardware.org/?probe=90b1930c43) | Oct 18, 2021 |
| Acer          | Aspire 1410                 | [dc42de3c30](https://linux-hardware.org/?probe=dc42de3c30) | Oct 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [dda062734d](https://linux-hardware.org/?probe=dda062734d) | Oct 17, 2021 |
| Dell          | XPS 15 7590                 | [ff55772306](https://linux-hardware.org/?probe=ff55772306) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Dell          | Latitude 5410               | [bdd46a0cd7](https://linux-hardware.org/?probe=bdd46a0cd7) | Oct 14, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [62872f38de](https://linux-hardware.org/?probe=62872f38de) | Oct 14, 2021 |
| Acer          | Swift SF515-51T             | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [b72f6d9f64](https://linux-hardware.org/?probe=b72f6d9f64) | Oct 08, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [770a47642f](https://linux-hardware.org/?probe=770a47642f) | Oct 03, 2021 |
| Acer          | Aspire A515-52              | [1f5c815672](https://linux-hardware.org/?probe=1f5c815672) | Oct 02, 2021 |
| Packard Be... | EasyNote TV44HC             | [ba505c4969](https://linux-hardware.org/?probe=ba505c4969) | Sep 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [feed153041](https://linux-hardware.org/?probe=feed153041) | Sep 28, 2021 |
| Acer          | Aspire 1410                 | [bb25067861](https://linux-hardware.org/?probe=bb25067861) | Sep 25, 2021 |
| Acer          | Aspire 1410                 | [8db88d13ec](https://linux-hardware.org/?probe=8db88d13ec) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Dell          | XPS 15 9560                 | [cc4ac84959](https://linux-hardware.org/?probe=cc4ac84959) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [2c7e4f944f](https://linux-hardware.org/?probe=2c7e4f944f) | Sep 18, 2021 |
| Acer          | Swift SF515-51T             | [a0a6460520](https://linux-hardware.org/?probe=a0a6460520) | Sep 17, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ab2e5dcff2](https://linux-hardware.org/?probe=ab2e5dcff2) | Sep 14, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f01a6435b7](https://linux-hardware.org/?probe=f01a6435b7) | Sep 14, 2021 |
| Lenovo        | ThinkPad T550 20CJS03300    | [2b53cd0d2d](https://linux-hardware.org/?probe=2b53cd0d2d) | Sep 11, 2021 |
| Lenovo        | ThinkPad W540 20BHS27X02    | [60ee8c9731](https://linux-hardware.org/?probe=60ee8c9731) | Sep 10, 2021 |
| Lenovo        | ThinkPad W540 20BHS27X02    | [c11d22f126](https://linux-hardware.org/?probe=c11d22f126) | Sep 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3333d2aabd](https://linux-hardware.org/?probe=3333d2aabd) | Sep 09, 2021 |
| Lenovo        | ThinkPad L460 20FVS01500    | [065324adcb](https://linux-hardware.org/?probe=065324adcb) | Sep 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Medion        | S3409 MD60234               | [30a93543cd](https://linux-hardware.org/?probe=30a93543cd) | Sep 07, 2021 |
| Medion        | S3409 MD60234               | [274fe63960](https://linux-hardware.org/?probe=274fe63960) | Sep 06, 2021 |
| Acer          | Swift SF114-32              | [41a2fef2aa](https://linux-hardware.org/?probe=41a2fef2aa) | Sep 05, 2021 |
| HP            | Laptop 15-bw0xx             | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| Packard Be... | EasyNote TV44HC             | [4e61ece773](https://linux-hardware.org/?probe=4e61ece773) | Sep 02, 2021 |
| Packard Be... | EasyNote TV44HC             | [87353376d7](https://linux-hardware.org/?probe=87353376d7) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [4fc1ff5f76](https://linux-hardware.org/?probe=4fc1ff5f76) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [2087b72fe1](https://linux-hardware.org/?probe=2087b72fe1) | Aug 31, 2021 |
| Packard Be... | EasyNote TV44HC             | [4d4510dbfb](https://linux-hardware.org/?probe=4d4510dbfb) | Aug 30, 2021 |
| Lenovo        | ThinkPad T420 4236NGG       | [6f82a1cdeb](https://linux-hardware.org/?probe=6f82a1cdeb) | Aug 30, 2021 |
| Samsung       | 700G7C                      | [9bdbd478e5](https://linux-hardware.org/?probe=9bdbd478e5) | Aug 29, 2021 |
| TUXEDO        | BC1510 1710                 | [9061a72f3a](https://linux-hardware.org/?probe=9061a72f3a) | Aug 29, 2021 |
| Acer          | Aspire ES1-512              | [666660f555](https://linux-hardware.org/?probe=666660f555) | Aug 29, 2021 |
| whyopencom... | Unknown                     | [3cf7a8a461](https://linux-hardware.org/?probe=3cf7a8a461) | Aug 28, 2021 |
| Dell          | Precision M6700             | [c1e66e1633](https://linux-hardware.org/?probe=c1e66e1633) | Aug 28, 2021 |
| TrekStor      | Surfbook E11B               | [9014dfda1f](https://linux-hardware.org/?probe=9014dfda1f) | Aug 26, 2021 |
| Dell          | Precision 5520              | [12782a8da6](https://linux-hardware.org/?probe=12782a8da6) | Aug 24, 2021 |
| ASUSTek       | ZenBook UX431DA             | [76b34b8383](https://linux-hardware.org/?probe=76b34b8383) | Aug 24, 2021 |
| ASUSTek       | ZenBook UX431DA             | [35b4ea3ba9](https://linux-hardware.org/?probe=35b4ea3ba9) | Aug 24, 2021 |
| Dell          | Precision 5520              | [43f1c9c69c](https://linux-hardware.org/?probe=43f1c9c69c) | Aug 24, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3598b4e555](https://linux-hardware.org/?probe=3598b4e555) | Aug 23, 2021 |
| Dell          | Latitude E5550              | [186ab38330](https://linux-hardware.org/?probe=186ab38330) | Aug 23, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [e59555689c](https://linux-hardware.org/?probe=e59555689c) | Aug 23, 2021 |
| HP            | EliteBook Folio 9470m       | [ddd4cdd7ca](https://linux-hardware.org/?probe=ddd4cdd7ca) | Aug 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [7f439ff799](https://linux-hardware.org/?probe=7f439ff799) | Aug 22, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [47cea1b5c7](https://linux-hardware.org/?probe=47cea1b5c7) | Aug 20, 2021 |
| Dell          | Precision 5520              | [bb6728e105](https://linux-hardware.org/?probe=bb6728e105) | Aug 19, 2021 |
| Dell          | Precision 5520              | [87389dc90a](https://linux-hardware.org/?probe=87389dc90a) | Aug 19, 2021 |
| Acer          | V3-771                      | [5235c8cb39](https://linux-hardware.org/?probe=5235c8cb39) | Aug 18, 2021 |
| Acer          | Aspire 5253                 | [8d12d69ada](https://linux-hardware.org/?probe=8d12d69ada) | Aug 18, 2021 |
| Acer          | Aspire 5253                 | [e44f3b4caf](https://linux-hardware.org/?probe=e44f3b4caf) | Aug 18, 2021 |
| Toshiba       | Satellite C660D             | [eb50acee36](https://linux-hardware.org/?probe=eb50acee36) | Aug 16, 2021 |
| Toshiba       | Satellite C660D             | [2afd21c6f7](https://linux-hardware.org/?probe=2afd21c6f7) | Aug 16, 2021 |
| Acer          | Aspire 5253                 | [06a6ece9cb](https://linux-hardware.org/?probe=06a6ece9cb) | Aug 16, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [d628c6c320](https://linux-hardware.org/?probe=d628c6c320) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| HP            | ProBook 650 G2              | [8bd4184e25](https://linux-hardware.org/?probe=8bd4184e25) | Aug 15, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [4b51090679](https://linux-hardware.org/?probe=4b51090679) | Aug 13, 2021 |
| Dell          | Latitude 7490               | [f78358fed7](https://linux-hardware.org/?probe=f78358fed7) | Aug 13, 2021 |
| Dell          | Latitude 7490               | [3c3c535058](https://linux-hardware.org/?probe=3c3c535058) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [4dc4a0efe0](https://linux-hardware.org/?probe=4dc4a0efe0) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6e44d2998d](https://linux-hardware.org/?probe=6e44d2998d) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | [9fef85ae5d](https://linux-hardware.org/?probe=9fef85ae5d) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| ASUSTek       | GL702ZC                     | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| Dell          | Latitude E7440              | [33a205253e](https://linux-hardware.org/?probe=33a205253e) | Aug 10, 2021 |
| HP            | ENVY dv7                    | [888257031e](https://linux-hardware.org/?probe=888257031e) | Aug 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [92fb2e26c0](https://linux-hardware.org/?probe=92fb2e26c0) | Aug 10, 2021 |
| Dell          | Latitude E7440              | [89a521499a](https://linux-hardware.org/?probe=89a521499a) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [05628cae80](https://linux-hardware.org/?probe=05628cae80) | Aug 09, 2021 |
| Lenovo        | ThinkPad W500 406152G       | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| GPD           | P2 MAX                      | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| TUXEDO        | Unknown                     | [15b26f4936](https://linux-hardware.org/?probe=15b26f4936) | Aug 07, 2021 |
| Acer          | Aspire E5-571G              | [ed862d4cb6](https://linux-hardware.org/?probe=ed862d4cb6) | Aug 07, 2021 |
| Acer          | Aspire E5-571G              | [5e1a0f0e89](https://linux-hardware.org/?probe=5e1a0f0e89) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Lenovo        | ThinkPad T510 43494JG       | [80fafef64f](https://linux-hardware.org/?probe=80fafef64f) | Aug 05, 2021 |
| Dell          | Inspiron 15-5578            | [1169a22f51](https://linux-hardware.org/?probe=1169a22f51) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T420 4236NGG       | [5b70933531](https://linux-hardware.org/?probe=5b70933531) | Aug 01, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [e2db581d0b](https://linux-hardware.org/?probe=e2db581d0b) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [b893ad294a](https://linux-hardware.org/?probe=b893ad294a) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| HP            | Pavilion dv7                | [e9254ad52f](https://linux-hardware.org/?probe=e9254ad52f) | Jul 31, 2021 |
| Acer          | Aspire E1-572G              | [3963220295](https://linux-hardware.org/?probe=3963220295) | Jul 31, 2021 |
| Acer          | Aspire E1-572G              | [f8eb40a0a3](https://linux-hardware.org/?probe=f8eb40a0a3) | Jul 30, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [9cf9065745](https://linux-hardware.org/?probe=9cf9065745) | Jul 30, 2021 |
| Dell          | Latitude E5550              | [84d60c9f30](https://linux-hardware.org/?probe=84d60c9f30) | Jul 30, 2021 |
| Dell          | XPS 13 9310                 | [4ad09b336f](https://linux-hardware.org/?probe=4ad09b336f) | Jul 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [cde8deea7e](https://linux-hardware.org/?probe=cde8deea7e) | Jul 26, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [7330b29e94](https://linux-hardware.org/?probe=7330b29e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [1a104c4440](https://linux-hardware.org/?probe=1a104c4440) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| GPD           | P2 MAX                      | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| Lenovo        | G580 20150                  | [a52bc56d5e](https://linux-hardware.org/?probe=a52bc56d5e) | Jul 23, 2021 |
| Medion        | E6226                       | [aee8a0be6f](https://linux-hardware.org/?probe=aee8a0be6f) | Jul 22, 2021 |
| HP            | Pavilion g7                 | [59f46869ee](https://linux-hardware.org/?probe=59f46869ee) | Jul 21, 2021 |
| HP            | Pavilion g7                 | [b71a21e87a](https://linux-hardware.org/?probe=b71a21e87a) | Jul 21, 2021 |
| HP            | ProBook 450 G3              | [8b355a2630](https://linux-hardware.org/?probe=8b355a2630) | Jul 20, 2021 |
| Medion        | P6618                       | [d8b3d2db11](https://linux-hardware.org/?probe=d8b3d2db11) | Jul 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [5c3f0aef89](https://linux-hardware.org/?probe=5c3f0aef89) | Jul 17, 2021 |
| Sony          | SVE14A2V1EW                 | [2b1ce53eca](https://linux-hardware.org/?probe=2b1ce53eca) | Jul 16, 2021 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [c61db52d00](https://linux-hardware.org/?probe=c61db52d00) | Jul 16, 2021 |
| whyopencom... | Unknown                     | [b9f3462ccb](https://linux-hardware.org/?probe=b9f3462ccb) | Jul 15, 2021 |
| Dell          | XPS 13 9360                 | [90fcb82f7e](https://linux-hardware.org/?probe=90fcb82f7e) | Jul 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [427828621f](https://linux-hardware.org/?probe=427828621f) | Jul 12, 2021 |
| Acer          | Swift SF114-33              | [7aa338a8dc](https://linux-hardware.org/?probe=7aa338a8dc) | Jul 12, 2021 |
| Toshiba       | NB550D                      | [6e4b998cc0](https://linux-hardware.org/?probe=6e4b998cc0) | Jul 12, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [04163e3fa8](https://linux-hardware.org/?probe=04163e3fa8) | Jul 12, 2021 |
| Notebook      | NS50MU                      | [6841e398e3](https://linux-hardware.org/?probe=6841e398e3) | Jul 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS3... | [6c9599ccf7](https://linux-hardware.org/?probe=6c9599ccf7) | Jul 07, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [8887f14351](https://linux-hardware.org/?probe=8887f14351) | Jul 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [70c0bc44a2](https://linux-hardware.org/?probe=70c0bc44a2) | Jul 05, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | [7bbd48efde](https://linux-hardware.org/?probe=7bbd48efde) | Jul 03, 2021 |
| Lenovo        | ThinkPad T450s 20BX004KM... | [dbd8629d3c](https://linux-hardware.org/?probe=dbd8629d3c) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | [78ad5dbea0](https://linux-hardware.org/?probe=78ad5dbea0) | Jul 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [6fde0ddd03](https://linux-hardware.org/?probe=6fde0ddd03) | Jul 01, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d85a7c67f9](https://linux-hardware.org/?probe=d85a7c67f9) | Jun 30, 2021 |
| HP            | Laptop 15-bs0xx             | [934190169c](https://linux-hardware.org/?probe=934190169c) | Jun 30, 2021 |
| whyopencom... | Unknown                     | [8cfc64102b](https://linux-hardware.org/?probe=8cfc64102b) | Jun 29, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | [fa358451aa](https://linux-hardware.org/?probe=fa358451aa) | Jun 25, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | [05a46ada33](https://linux-hardware.org/?probe=05a46ada33) | Jun 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [ea4ab7e535](https://linux-hardware.org/?probe=ea4ab7e535) | Jun 22, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [766b569b0e](https://linux-hardware.org/?probe=766b569b0e) | Jun 20, 2021 |
| HP            | ProBook 470 G5              | [94fbab0837](https://linux-hardware.org/?probe=94fbab0837) | Jun 19, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [822acd5e9b](https://linux-hardware.org/?probe=822acd5e9b) | Jun 19, 2021 |
| HUAWEI        | MACH-WX9                    | [4c0b858cde](https://linux-hardware.org/?probe=4c0b858cde) | Jun 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32c83da9dd](https://linux-hardware.org/?probe=32c83da9dd) | Jun 19, 2021 |
| Apple         | MacBookPro14,1              | [a69ed7dfd9](https://linux-hardware.org/?probe=a69ed7dfd9) | Jun 18, 2021 |
| HP            | EliteBook Folio 9470m       | [33fce68a70](https://linux-hardware.org/?probe=33fce68a70) | Jun 18, 2021 |
| whyopencom... | Unknown                     | [a571af169c](https://linux-hardware.org/?probe=a571af169c) | Jun 17, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [790371eae7](https://linux-hardware.org/?probe=790371eae7) | Jun 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [96ee62e1dc](https://linux-hardware.org/?probe=96ee62e1dc) | Jun 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [980c684572](https://linux-hardware.org/?probe=980c684572) | Jun 13, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [f0a5e0cbb6](https://linux-hardware.org/?probe=f0a5e0cbb6) | Jun 13, 2021 |
| Dell          | Latitude E6510              | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [ba7c5a0113](https://linux-hardware.org/?probe=ba7c5a0113) | Jun 10, 2021 |
| Acer          | Aspire E5-571G              | [455a20d0a7](https://linux-hardware.org/?probe=455a20d0a7) | Jun 10, 2021 |
| Acer          | Aspire E5-571G              | [467c46c227](https://linux-hardware.org/?probe=467c46c227) | Jun 08, 2021 |
| Dell          | XPS 13 9310                 | [5456739d8f](https://linux-hardware.org/?probe=5456739d8f) | Jun 08, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| HP            | ProBook 4510s (NX684EA)     | [55591c1e24](https://linux-hardware.org/?probe=55591c1e24) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [5b983aacb6](https://linux-hardware.org/?probe=5b983aacb6) | Jun 06, 2021 |
| Dell          | Inspiron 5577               | [188fcc64df](https://linux-hardware.org/?probe=188fcc64df) | Jun 06, 2021 |
| Dell          | XPS 15 7590                 | [08b1e4c99f](https://linux-hardware.org/?probe=08b1e4c99f) | Jun 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [bbf006f0df](https://linux-hardware.org/?probe=bbf006f0df) | Jun 05, 2021 |
| Acer          | Aspire 1410                 | [c0022674fa](https://linux-hardware.org/?probe=c0022674fa) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell          | Latitude E7440              | [32b9a694b3](https://linux-hardware.org/?probe=32b9a694b3) | Jun 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [1f3037ec58](https://linux-hardware.org/?probe=1f3037ec58) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | ProBook 440 G8 Notebook ... | [c1ec69ad60](https://linux-hardware.org/?probe=c1ec69ad60) | Jun 02, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [11f1e42fbe](https://linux-hardware.org/?probe=11f1e42fbe) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [5002e43f11](https://linux-hardware.org/?probe=5002e43f11) | May 30, 2021 |
| HP            | 355 G2                      | [c80a118e90](https://linux-hardware.org/?probe=c80a118e90) | May 29, 2021 |
| Acer          | Aspire 7736                 | [f8cf9b2aa2](https://linux-hardware.org/?probe=f8cf9b2aa2) | May 29, 2021 |
| HP            | ENVY 17                     | [bdaee2e27b](https://linux-hardware.org/?probe=bdaee2e27b) | May 28, 2021 |
| Acer          | Aspire F5-573G              | [d0c45f9b31](https://linux-hardware.org/?probe=d0c45f9b31) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [049671564e](https://linux-hardware.org/?probe=049671564e) | May 27, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [cb5051e015](https://linux-hardware.org/?probe=cb5051e015) | May 27, 2021 |
| HP            | Unknown                     | [42eeaf84d9](https://linux-hardware.org/?probe=42eeaf84d9) | May 24, 2021 |
| Acer          | TravelMate P215-53          | [dc89b4797f](https://linux-hardware.org/?probe=dc89b4797f) | May 24, 2021 |
| Acer          | TravelMate P215-53          | [18ea2a888a](https://linux-hardware.org/?probe=18ea2a888a) | May 23, 2021 |
| Notebook      | NH5x_7xDPx                  | [4a9dd7d6a1](https://linux-hardware.org/?probe=4a9dd7d6a1) | May 22, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [71e74768b0](https://linux-hardware.org/?probe=71e74768b0) | May 21, 2021 |
| whyopencom... | Unknown                     | [73dd49b204](https://linux-hardware.org/?probe=73dd49b204) | May 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [901f37d11b](https://linux-hardware.org/?probe=901f37d11b) | May 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [8b98b114e0](https://linux-hardware.org/?probe=8b98b114e0) | May 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [39f2002b6b](https://linux-hardware.org/?probe=39f2002b6b) | May 19, 2021 |
| Acer          | Aspire 1410                 | [877462fbca](https://linux-hardware.org/?probe=877462fbca) | May 18, 2021 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [abdc61ad94](https://linux-hardware.org/?probe=abdc61ad94) | May 18, 2021 |
| HP            | Compaq CQ58                 | [710fdca60a](https://linux-hardware.org/?probe=710fdca60a) | May 16, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [241b13488e](https://linux-hardware.org/?probe=241b13488e) | May 15, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| HP            | ProBook 455 G4              | [aca836bae8](https://linux-hardware.org/?probe=aca836bae8) | May 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [674a800477](https://linux-hardware.org/?probe=674a800477) | May 14, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [42a1bf7901](https://linux-hardware.org/?probe=42a1bf7901) | May 14, 2021 |
| HP            | Pavilion 15                 | [7e38915bdc](https://linux-hardware.org/?probe=7e38915bdc) | May 13, 2021 |
| HP            | OMEN by HP Laptop           | [43907153c2](https://linux-hardware.org/?probe=43907153c2) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [36ade7dd15](https://linux-hardware.org/?probe=36ade7dd15) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [06c1bbc65e](https://linux-hardware.org/?probe=06c1bbc65e) | May 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [b5fd7c0d6d](https://linux-hardware.org/?probe=b5fd7c0d6d) | May 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [b313183fd5](https://linux-hardware.org/?probe=b313183fd5) | May 11, 2021 |
| Acer          | Swift SF114-33              | [e2d8f58e1e](https://linux-hardware.org/?probe=e2d8f58e1e) | May 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [6361a1cd7f](https://linux-hardware.org/?probe=6361a1cd7f) | May 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [e126e1aa0c](https://linux-hardware.org/?probe=e126e1aa0c) | May 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [952093c613](https://linux-hardware.org/?probe=952093c613) | May 09, 2021 |
| Acer          | Swift SF114-33              | [a6ed80ed47](https://linux-hardware.org/?probe=a6ed80ed47) | May 08, 2021 |
| Google        | Lars                        | [2cba94fe45](https://linux-hardware.org/?probe=2cba94fe45) | May 08, 2021 |
| HP            | Compaq nc4400 (EN004AV)     | [eedf4bb0ca](https://linux-hardware.org/?probe=eedf4bb0ca) | May 08, 2021 |
| Acer          | Swift SF314-42              | [f28c9e243e](https://linux-hardware.org/?probe=f28c9e243e) | May 07, 2021 |
| HP            | Compaq nc4400 (EN004AV)     | [d6154d7955](https://linux-hardware.org/?probe=d6154d7955) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [06d44f569d](https://linux-hardware.org/?probe=06d44f569d) | May 06, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LM... | [0b155bcbcd](https://linux-hardware.org/?probe=0b155bcbcd) | May 04, 2021 |
| HP            | Notebook                    | [4e09e8ff3b](https://linux-hardware.org/?probe=4e09e8ff3b) | May 03, 2021 |
| HP            | 2133                        | [e81cac058d](https://linux-hardware.org/?probe=e81cac058d) | May 03, 2021 |
| Alienware     | m15 R2                      | [4884d06d2e](https://linux-hardware.org/?probe=4884d06d2e) | May 02, 2021 |
| HP            | EliteBook Folio 1040 G1     | [226f359e79](https://linux-hardware.org/?probe=226f359e79) | May 01, 2021 |
| HP            | 250 G7 Notebook PC          | [e69f0b2a6e](https://linux-hardware.org/?probe=e69f0b2a6e) | May 01, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ08    | [7efd61973c](https://linux-hardware.org/?probe=7efd61973c) | Apr 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [be1fac0a5c](https://linux-hardware.org/?probe=be1fac0a5c) | Apr 29, 2021 |
| Lenovo        | Z50-70 20354                | [93033f85c6](https://linux-hardware.org/?probe=93033f85c6) | Apr 29, 2021 |
| HP            | 2133                        | [fd8d7a6a94](https://linux-hardware.org/?probe=fd8d7a6a94) | Apr 29, 2021 |
| TrekStor      | Surfbook E11B               | [67fda204e7](https://linux-hardware.org/?probe=67fda204e7) | Apr 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Acer          | Aspire 1410                 | [759234ef11](https://linux-hardware.org/?probe=759234ef11) | Apr 28, 2021 |
| Alienware     | m15 R2                      | [77d90d2a91](https://linux-hardware.org/?probe=77d90d2a91) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | [909c049308](https://linux-hardware.org/?probe=909c049308) | Apr 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6fd9f38406](https://linux-hardware.org/?probe=6fd9f38406) | Apr 26, 2021 |
| Dell          | Latitude E7440              | [b8c6136bd0](https://linux-hardware.org/?probe=b8c6136bd0) | Apr 26, 2021 |
| HP            | EliteBook 2170p             | [98a664ebcc](https://linux-hardware.org/?probe=98a664ebcc) | Apr 26, 2021 |
| ASUSTek       | K72Jr                       | [ff3ba69d3e](https://linux-hardware.org/?probe=ff3ba69d3e) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [e4b338aa1a](https://linux-hardware.org/?probe=e4b338aa1a) | Apr 25, 2021 |
| OriginPC      | ND-17                       | [8ff850fe97](https://linux-hardware.org/?probe=8ff850fe97) | Apr 25, 2021 |
| ASUSTek       | K72Jr                       | [bcc4e8b350](https://linux-hardware.org/?probe=bcc4e8b350) | Apr 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [b6b305b0bd](https://linux-hardware.org/?probe=b6b305b0bd) | Apr 24, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [101cc9e3ae](https://linux-hardware.org/?probe=101cc9e3ae) | Apr 23, 2021 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [41ade399b3](https://linux-hardware.org/?probe=41ade399b3) | Apr 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [926fa9f69a](https://linux-hardware.org/?probe=926fa9f69a) | Apr 21, 2021 |
| HP            | ENVY Laptop 17-cg1xxx       | [38221d2991](https://linux-hardware.org/?probe=38221d2991) | Apr 21, 2021 |
| Acer          | Aspire 1410                 | [7288f31e3c](https://linux-hardware.org/?probe=7288f31e3c) | Apr 20, 2021 |
| whyopencom... | Unknown                     | [87c196c75f](https://linux-hardware.org/?probe=87c196c75f) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5b66c48c4a](https://linux-hardware.org/?probe=5b66c48c4a) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| Dell          | Latitude E7240              | [45870a7f89](https://linux-hardware.org/?probe=45870a7f89) | Apr 14, 2021 |
| whyopencom... | Unknown                     | [aad3ad526f](https://linux-hardware.org/?probe=aad3ad526f) | Apr 13, 2021 |
| HP            | 250 G6 Notebook PC          | [bc738ac65f](https://linux-hardware.org/?probe=bc738ac65f) | Apr 11, 2021 |
| Dell          | XPS 13 9343                 | [4d759a05db](https://linux-hardware.org/?probe=4d759a05db) | Apr 09, 2021 |
| Dell          | Latitude E6500              | [3bdee6855c](https://linux-hardware.org/?probe=3bdee6855c) | Apr 07, 2021 |
| Lenovo        | IdeaPad Yoga 13 2191        | [44aa3ba48f](https://linux-hardware.org/?probe=44aa3ba48f) | Apr 05, 2021 |
| Dell          | XPS 15 9570                 | [f74fdee693](https://linux-hardware.org/?probe=f74fdee693) | Apr 01, 2021 |
| TrekStor      | Surfbook E11B               | [464dce7796](https://linux-hardware.org/?probe=464dce7796) | Apr 01, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [84cc759796](https://linux-hardware.org/?probe=84cc759796) | Mar 30, 2021 |
| Dell          | Latitude E5450              | [5ce2bad1c1](https://linux-hardware.org/?probe=5ce2bad1c1) | Mar 29, 2021 |
| Dell          | Latitude E5450              | [9a98d3e9b3](https://linux-hardware.org/?probe=9a98d3e9b3) | Mar 28, 2021 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [449ee0c3ef](https://linux-hardware.org/?probe=449ee0c3ef) | Mar 28, 2021 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [44e41b06e8](https://linux-hardware.org/?probe=44e41b06e8) | Mar 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6bf5c0b770](https://linux-hardware.org/?probe=6bf5c0b770) | Mar 27, 2021 |
| Medion        | S3409 MD60234               | [eee4e7256b](https://linux-hardware.org/?probe=eee4e7256b) | Mar 26, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [7e10f0b649](https://linux-hardware.org/?probe=7e10f0b649) | Mar 25, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [27a3733dc4](https://linux-hardware.org/?probe=27a3733dc4) | Mar 25, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [f00d8623c8](https://linux-hardware.org/?probe=f00d8623c8) | Mar 24, 2021 |
| Lenovo        | ThinkPad T460s 20F9005CS... | [c03bed695b](https://linux-hardware.org/?probe=c03bed695b) | Mar 24, 2021 |
| HP            | 250 G8 Notebook PC          | [8889dc5ad5](https://linux-hardware.org/?probe=8889dc5ad5) | Mar 22, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [045f977209](https://linux-hardware.org/?probe=045f977209) | Mar 22, 2021 |
| Acer          | V3-771                      | [a602c93819](https://linux-hardware.org/?probe=a602c93819) | Mar 21, 2021 |
| Apple         | MacBookAir5,2               | [23d38894c7](https://linux-hardware.org/?probe=23d38894c7) | Mar 20, 2021 |
| Dell          | Inspiron 7577               | [25f556cacf](https://linux-hardware.org/?probe=25f556cacf) | Mar 18, 2021 |
| HP            | EliteBook 2760p             | [49ee1765af](https://linux-hardware.org/?probe=49ee1765af) | Mar 16, 2021 |
| HP            | EliteBook 2760p             | [20bf0cfe70](https://linux-hardware.org/?probe=20bf0cfe70) | Mar 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [25c2dd2a64](https://linux-hardware.org/?probe=25c2dd2a64) | Mar 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1deb9edb46](https://linux-hardware.org/?probe=1deb9edb46) | Mar 14, 2021 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [6c33ce2e79](https://linux-hardware.org/?probe=6c33ce2e79) | Mar 14, 2021 |
| ASUSTek       | GL702ZC                     | [1d220bf375](https://linux-hardware.org/?probe=1d220bf375) | Mar 14, 2021 |
| HP            | Laptop 15-bs1xx             | [bd1886f540](https://linux-hardware.org/?probe=bd1886f540) | Mar 14, 2021 |
| Acer          | Aspire E1-731               | [23ea26d43f](https://linux-hardware.org/?probe=23ea26d43f) | Mar 12, 2021 |
| Acer          | Aspire 7736                 | [f3777d97b2](https://linux-hardware.org/?probe=f3777d97b2) | Mar 11, 2021 |
| Medion        | E6226                       | [fd72b6bbc9](https://linux-hardware.org/?probe=fd72b6bbc9) | Mar 11, 2021 |
| Dell          | Latitude E7440              | [4521f4c1a3](https://linux-hardware.org/?probe=4521f4c1a3) | Mar 10, 2021 |
| HP            | ProBook 4720s               | [1dbaa2aa4b](https://linux-hardware.org/?probe=1dbaa2aa4b) | Mar 10, 2021 |
| GPD           | P2 MAX                      | [931b98f992](https://linux-hardware.org/?probe=931b98f992) | Mar 09, 2021 |
| Acer          | Nitro AN515-52              | [332460236a](https://linux-hardware.org/?probe=332460236a) | Mar 09, 2021 |
| ASUSTek       | GL702ZC                     | [b866314500](https://linux-hardware.org/?probe=b866314500) | Mar 09, 2021 |
| Lenovo        | G50-80 80E5                 | [7d142fb2ab](https://linux-hardware.org/?probe=7d142fb2ab) | Mar 09, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [09ff2814ff](https://linux-hardware.org/?probe=09ff2814ff) | Mar 08, 2021 |
| Fujitsu       | LIFEBOOK E782               | [b926f7249f](https://linux-hardware.org/?probe=b926f7249f) | Mar 06, 2021 |
| Acer          | Aspire V3-771               | [6aea799f3a](https://linux-hardware.org/?probe=6aea799f3a) | Mar 06, 2021 |
| Acer          | Aspire V3-771               | [f87b2a351a](https://linux-hardware.org/?probe=f87b2a351a) | Mar 06, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [c1211fb175](https://linux-hardware.org/?probe=c1211fb175) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [025319ae47](https://linux-hardware.org/?probe=025319ae47) | Mar 03, 2021 |
| Lenovo        | ThinkPad W530 2441B32       | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| Acer          | Aspire A315-42              | [44974397a8](https://linux-hardware.org/?probe=44974397a8) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK E782               | [0c2c32289a](https://linux-hardware.org/?probe=0c2c32289a) | Feb 28, 2021 |
| HP            | Pavilion Notebook g6        | [e8fb0d80d6](https://linux-hardware.org/?probe=e8fb0d80d6) | Feb 27, 2021 |
| Medion        | P6624                       | [29fba6cccc](https://linux-hardware.org/?probe=29fba6cccc) | Feb 24, 2021 |
| HP            | Pavilion Notebook g6        | [786a3e39df](https://linux-hardware.org/?probe=786a3e39df) | Feb 21, 2021 |
| Toshiba       | QOSMIO X770                 | [1d2a7b2b7a](https://linux-hardware.org/?probe=1d2a7b2b7a) | Feb 20, 2021 |
| Acer          | V3-771                      | [b6e90947b8](https://linux-hardware.org/?probe=b6e90947b8) | Feb 20, 2021 |
| Acer          | V3-771                      | [7b374de735](https://linux-hardware.org/?probe=7b374de735) | Feb 20, 2021 |
| HP            | Pavilion g7                 | [35f315adb8](https://linux-hardware.org/?probe=35f315adb8) | Feb 19, 2021 |
| HP            | Pavilion g7                 | [93b1476aa8](https://linux-hardware.org/?probe=93b1476aa8) | Feb 19, 2021 |
| HP            | Laptop 15-bs0xx             | [f80d7003a7](https://linux-hardware.org/?probe=f80d7003a7) | Feb 18, 2021 |
| TUXEDO        | N13xWU                      | [905dae2b25](https://linux-hardware.org/?probe=905dae2b25) | Feb 18, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [fd4dd43574](https://linux-hardware.org/?probe=fd4dd43574) | Feb 16, 2021 |
| ASUSTek       | GL702ZC                     | [8730756c6f](https://linux-hardware.org/?probe=8730756c6f) | Feb 16, 2021 |
| Samsung       | 730U3E/740U3E               | [094783ff7a](https://linux-hardware.org/?probe=094783ff7a) | Feb 15, 2021 |
| ASUSTek       | X550ZE                      | [d8957c1789](https://linux-hardware.org/?probe=d8957c1789) | Feb 14, 2021 |
| Acer          | Aspire E5-774G              | [f002df90ed](https://linux-hardware.org/?probe=f002df90ed) | Feb 14, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [6e7025de29](https://linux-hardware.org/?probe=6e7025de29) | Feb 14, 2021 |
| Medion        | S621xT                      | [3b77cd1079](https://linux-hardware.org/?probe=3b77cd1079) | Feb 14, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [d955eb3433](https://linux-hardware.org/?probe=d955eb3433) | Feb 14, 2021 |
| HP            | ENVY 15                     | [ab6ef5e4cf](https://linux-hardware.org/?probe=ab6ef5e4cf) | Feb 12, 2021 |
| Samsung       | 730U3E/740U3E               | [df4eb897c9](https://linux-hardware.org/?probe=df4eb897c9) | Feb 12, 2021 |
| Apple         | MacBookPro10,1              | [0fdb263ea1](https://linux-hardware.org/?probe=0fdb263ea1) | Feb 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [49d0895c1c](https://linux-hardware.org/?probe=49d0895c1c) | Feb 08, 2021 |
| Acer          | V3-771                      | [525217a48b](https://linux-hardware.org/?probe=525217a48b) | Feb 07, 2021 |
| Dell          | Latitude E5440              | [421629b6e9](https://linux-hardware.org/?probe=421629b6e9) | Feb 07, 2021 |
| Medion        | X782X                       | [384e3543dd](https://linux-hardware.org/?probe=384e3543dd) | Feb 05, 2021 |
| Apple         | MacBookPro9,2               | [c3062ebba4](https://linux-hardware.org/?probe=c3062ebba4) | Feb 04, 2021 |
| Apple         | MacBookPro9,2               | [2203826b83](https://linux-hardware.org/?probe=2203826b83) | Feb 04, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| Sony          | SVE1511F4E                  | [6e713387ef](https://linux-hardware.org/?probe=6e713387ef) | Feb 01, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [669829c000](https://linux-hardware.org/?probe=669829c000) | Jan 31, 2021 |
| Acer          | V3-771                      | [5be8740644](https://linux-hardware.org/?probe=5be8740644) | Jan 31, 2021 |
| HP            | ZBook 17 G2                 | [ccf18d4e4e](https://linux-hardware.org/?probe=ccf18d4e4e) | Jan 31, 2021 |
| MSI           | Prestige 14 A10SC           | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Hampoo        | Cherry Trail CR             | [ecaf6db2cc](https://linux-hardware.org/?probe=ecaf6db2cc) | Jan 31, 2021 |
| Schenker      | SCHENKER VIA 15 Pro         | [4f091c50f8](https://linux-hardware.org/?probe=4f091c50f8) | Jan 30, 2021 |
| Acer          | V3-771                      | [84fb01f37b](https://linux-hardware.org/?probe=84fb01f37b) | Jan 30, 2021 |
| HP            | Pavilion zd8000 (PW934EA... | [640a4d1741](https://linux-hardware.org/?probe=640a4d1741) | Jan 29, 2021 |
| Acer          | Aspire 7736                 | [361d552fde](https://linux-hardware.org/?probe=361d552fde) | Jan 28, 2021 |
| Sony          | VGN-AR61ZU                  | [32858b781b](https://linux-hardware.org/?probe=32858b781b) | Jan 25, 2021 |
| Sony          | SVE1511N1ESI                | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [fb80ef0b97](https://linux-hardware.org/?probe=fb80ef0b97) | Jan 21, 2021 |
| Lenovo        | ThinkPad X260 20F6CT01WW    | [6f921d73e3](https://linux-hardware.org/?probe=6f921d73e3) | Jan 20, 2021 |
| Lenovo        | ThinkPad Edge E530 32597... | [bb6fc12e56](https://linux-hardware.org/?probe=bb6fc12e56) | Jan 20, 2021 |
| Dell          | XPS 17 9700                 | [d2bc47e82b](https://linux-hardware.org/?probe=d2bc47e82b) | Jan 20, 2021 |
| Sony          | SVE14A2V1EW                 | [baaf829145](https://linux-hardware.org/?probe=baaf829145) | Jan 20, 2021 |
| Lenovo        | ThinkPad T430 2349G5G       | [f552a37632](https://linux-hardware.org/?probe=f552a37632) | Jan 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | [db6d4d3deb](https://linux-hardware.org/?probe=db6d4d3deb) | Jan 20, 2021 |
| ASUSTek       | K53SD                       | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| ASUSTek       | GL702ZC                     | [662efa6f54](https://linux-hardware.org/?probe=662efa6f54) | Jan 18, 2021 |
| ASUSTek       | GL702ZC                     | [ba6a149cba](https://linux-hardware.org/?probe=ba6a149cba) | Jan 17, 2021 |
| Acer          | Nitro AN515-52              | [f5873c65c2](https://linux-hardware.org/?probe=f5873c65c2) | Jan 17, 2021 |
| GPD           | P2 MAX                      | [cdc2c0ab67](https://linux-hardware.org/?probe=cdc2c0ab67) | Jan 17, 2021 |
| GPD           | P2 MAX                      | [bb15abf7cc](https://linux-hardware.org/?probe=bb15abf7cc) | Jan 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [951df975ad](https://linux-hardware.org/?probe=951df975ad) | Jan 17, 2021 |
| whyopencom... | Unknown                     | [c120bc7ad7](https://linux-hardware.org/?probe=c120bc7ad7) | Jan 17, 2021 |
| Acer          | V3-771                      | [75e10f15f8](https://linux-hardware.org/?probe=75e10f15f8) | Jan 17, 2021 |
| ASUSTek       | F5RL                        | [79907a946b](https://linux-hardware.org/?probe=79907a946b) | Jan 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e07ae256e7](https://linux-hardware.org/?probe=e07ae256e7) | Jan 16, 2021 |
| Notebook      | W65_67SZ                    | [1992f23f11](https://linux-hardware.org/?probe=1992f23f11) | Jan 15, 2021 |
| whyopencom... | Unknown                     | [05e1dc54c4](https://linux-hardware.org/?probe=05e1dc54c4) | Jan 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [680db2a270](https://linux-hardware.org/?probe=680db2a270) | Jan 14, 2021 |
| Acer          | V3-771                      | [b3da82ed71](https://linux-hardware.org/?probe=b3da82ed71) | Jan 13, 2021 |
| HP            | Laptop 15s-eq1xxx           | [51f542581b](https://linux-hardware.org/?probe=51f542581b) | Jan 13, 2021 |
| Sony          | SVE1511F4E                  | [18f6b7a23f](https://linux-hardware.org/?probe=18f6b7a23f) | Jan 13, 2021 |
| HP            | EliteBook 840 G4            | [2e35accad4](https://linux-hardware.org/?probe=2e35accad4) | Jan 12, 2021 |
| Dell          | Latitude XT2                | [958e277130](https://linux-hardware.org/?probe=958e277130) | Jan 12, 2021 |
| Acer          | V3-771                      | [816da2c056](https://linux-hardware.org/?probe=816da2c056) | Jan 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1209b7ddaa](https://linux-hardware.org/?probe=1209b7ddaa) | Jan 10, 2021 |
| Dell          | XPS 13 7390                 | [ee990dcfb4](https://linux-hardware.org/?probe=ee990dcfb4) | Jan 10, 2021 |
| Lenovo        | ThinkPad T490 20N3S4AF00    | [88d0c92974](https://linux-hardware.org/?probe=88d0c92974) | Jan 05, 2021 |
| Acer          | V3-771                      | [4bb5cb91f1](https://linux-hardware.org/?probe=4bb5cb91f1) | Jan 05, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [6226d61b8d](https://linux-hardware.org/?probe=6226d61b8d) | Jan 05, 2021 |
| Lenovo        | ThinkPad X200 74591P0       | [0280683b9f](https://linux-hardware.org/?probe=0280683b9f) | Jan 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0f6cbbdc40](https://linux-hardware.org/?probe=0f6cbbdc40) | Jan 03, 2021 |
| Dell          | XPS 13 7390                 | [7fcac0b28e](https://linux-hardware.org/?probe=7fcac0b28e) | Jan 01, 2021 |
| HP            | ProBook 650 G2              | [4e4dfa1185](https://linux-hardware.org/?probe=4e4dfa1185) | Jan 01, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [7c5bea876e](https://linux-hardware.org/?probe=7c5bea876e) | Dec 30, 2020 |
| Sony          | SVE1511F4E                  | [2482a9cf42](https://linux-hardware.org/?probe=2482a9cf42) | Dec 29, 2020 |
| Sony          | SVE1511F4E                  | [9ddcb0cab8](https://linux-hardware.org/?probe=9ddcb0cab8) | Dec 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9e768a771f](https://linux-hardware.org/?probe=9e768a771f) | Dec 29, 2020 |
| Dell          | Latitude E7470              | [5e06bae0e3](https://linux-hardware.org/?probe=5e06bae0e3) | Dec 28, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [0566fe029e](https://linux-hardware.org/?probe=0566fe029e) | Dec 28, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [ff668fef04](https://linux-hardware.org/?probe=ff668fef04) | Dec 28, 2020 |
| HP            | OMEN by HP Laptop 15-dc1... | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [07471413eb](https://linux-hardware.org/?probe=07471413eb) | Dec 27, 2020 |
| Acer          | Nitro AN515-44              | [017b4363ac](https://linux-hardware.org/?probe=017b4363ac) | Dec 26, 2020 |
| HP            | Pavilion 17                 | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [c5acd280dc](https://linux-hardware.org/?probe=c5acd280dc) | Dec 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [f85418ac43](https://linux-hardware.org/?probe=f85418ac43) | Dec 25, 2020 |
| Sony          | VPCEH2P1E                   | [f68b654e04](https://linux-hardware.org/?probe=f68b654e04) | Dec 24, 2020 |
| Acer          | Nitro AN515-44              | [28a3b8bc6f](https://linux-hardware.org/?probe=28a3b8bc6f) | Dec 24, 2020 |
| Lenovo        | ThinkPad T460 20FMS08Q1B    | [97f9380c82](https://linux-hardware.org/?probe=97f9380c82) | Dec 24, 2020 |
| Samsung       | 700T1C                      | [0f8a8671f2](https://linux-hardware.org/?probe=0f8a8671f2) | Dec 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [206f63e80b](https://linux-hardware.org/?probe=206f63e80b) | Dec 24, 2020 |
| Acer          | Aspire 7741                 | [bb04468cdd](https://linux-hardware.org/?probe=bb04468cdd) | Dec 22, 2020 |
| Apple         | MacBookPro11,1              | [7b60dbe66e](https://linux-hardware.org/?probe=7b60dbe66e) | Dec 22, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9736b48f8d](https://linux-hardware.org/?probe=9736b48f8d) | Dec 22, 2020 |
| SLIMBOOK      | PROX15-AMD                  | [1746196bea](https://linux-hardware.org/?probe=1746196bea) | Dec 22, 2020 |
| ASUSTek       | UX331UA                     | [f570bd4fca](https://linux-hardware.org/?probe=f570bd4fca) | Dec 21, 2020 |
| Apple         | MacBookPro11,1              | [86f1e40ed8](https://linux-hardware.org/?probe=86f1e40ed8) | Dec 21, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [991d88e936](https://linux-hardware.org/?probe=991d88e936) | Dec 21, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [f5320272b1](https://linux-hardware.org/?probe=f5320272b1) | Dec 21, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6461d40f9a](https://linux-hardware.org/?probe=6461d40f9a) | Dec 20, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [1dddf64cc8](https://linux-hardware.org/?probe=1dddf64cc8) | Dec 20, 2020 |
| IGEL Techn... | M330C                       | [e2f47ddf56](https://linux-hardware.org/?probe=e2f47ddf56) | Dec 20, 2020 |
| IGEL Techn... | M330C                       | [e22d107c2b](https://linux-hardware.org/?probe=e22d107c2b) | Dec 20, 2020 |
| Dell          | Vostro 7590                 | [d71985d7a7](https://linux-hardware.org/?probe=d71985d7a7) | Dec 16, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [a1b69bb2a0](https://linux-hardware.org/?probe=a1b69bb2a0) | Dec 14, 2020 |
| Lenovo        | ThinkPad T440p 20AWS37D0... | [c35140641b](https://linux-hardware.org/?probe=c35140641b) | Dec 13, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d7cc0106d2](https://linux-hardware.org/?probe=d7cc0106d2) | Dec 12, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [d89c8f909d](https://linux-hardware.org/?probe=d89c8f909d) | Dec 12, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [df3e36f6ed](https://linux-hardware.org/?probe=df3e36f6ed) | Dec 11, 2020 |
| HP            | ProBook 650 G2              | [88c6bb8d12](https://linux-hardware.org/?probe=88c6bb8d12) | Dec 11, 2020 |
| Packard Be... | EasyNote TE11HC             | [ecfcd2d772](https://linux-hardware.org/?probe=ecfcd2d772) | Dec 10, 2020 |
| Acer          | Aspire F5-771G              | [6d732fe2b5](https://linux-hardware.org/?probe=6d732fe2b5) | Dec 10, 2020 |
| ASUSTek       | G771JW                      | [0ebe86b001](https://linux-hardware.org/?probe=0ebe86b001) | Dec 08, 2020 |
| ASUSTek       | BU201LA                     | [4120fa5430](https://linux-hardware.org/?probe=4120fa5430) | Dec 07, 2020 |
| ASUSTek       | BU201LA                     | [06be6e8e94](https://linux-hardware.org/?probe=06be6e8e94) | Dec 07, 2020 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [307334cdad](https://linux-hardware.org/?probe=307334cdad) | Dec 07, 2020 |
| ASUSTek       | BU201LA                     | [f3fea11b14](https://linux-hardware.org/?probe=f3fea11b14) | Dec 07, 2020 |
| ASUSTek       | BU201LA                     | [efdfbd73d5](https://linux-hardware.org/?probe=efdfbd73d5) | Dec 06, 2020 |
| Acer          | Aspire V3-772G              | [5c75458a8d](https://linux-hardware.org/?probe=5c75458a8d) | Dec 05, 2020 |
| Acer          | Aspire V3-772G              | [4c05678eea](https://linux-hardware.org/?probe=4c05678eea) | Dec 05, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | [112d12030c](https://linux-hardware.org/?probe=112d12030c) | Dec 04, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0UD0... | [992060a459](https://linux-hardware.org/?probe=992060a459) | Dec 02, 2020 |
| Samsung       | 730U3E/740U3E               | [fda68fa5cf](https://linux-hardware.org/?probe=fda68fa5cf) | Dec 02, 2020 |
| Samsung       | 730U3E/740U3E               | [f392da9fc9](https://linux-hardware.org/?probe=f392da9fc9) | Dec 02, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0UD0... | [47e51b151b](https://linux-hardware.org/?probe=47e51b151b) | Dec 01, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [b80ed54426](https://linux-hardware.org/?probe=b80ed54426) | Dec 01, 2020 |
| Lenovo        | ThinkPad SL510 28479UU      | [f805d10499](https://linux-hardware.org/?probe=f805d10499) | Nov 28, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [afff87899c](https://linux-hardware.org/?probe=afff87899c) | Nov 28, 2020 |
| Toshiba       | TECRA R950                  | [e9755d13c3](https://linux-hardware.org/?probe=e9755d13c3) | Nov 28, 2020 |
| Samsung       | QX310/QX410/QX510/SF310/... | [dec24f879f](https://linux-hardware.org/?probe=dec24f879f) | Nov 26, 2020 |
| Dell          | XPS 15 9560                 | [7da87ec366](https://linux-hardware.org/?probe=7da87ec366) | Nov 26, 2020 |
| Dell          | XPS 15 9560                 | [30c4a823d8](https://linux-hardware.org/?probe=30c4a823d8) | Nov 26, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [02eb447fc0](https://linux-hardware.org/?probe=02eb447fc0) | Nov 26, 2020 |
| HP            | ProBook 440 G6              | [d4f0cf4cf6](https://linux-hardware.org/?probe=d4f0cf4cf6) | Nov 25, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [814797bb7b](https://linux-hardware.org/?probe=814797bb7b) | Nov 24, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [a45fc859a5](https://linux-hardware.org/?probe=a45fc859a5) | Nov 24, 2020 |
| ARIMA         | W622-DCX                    | [07cc1e0952](https://linux-hardware.org/?probe=07cc1e0952) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | [7388498d54](https://linux-hardware.org/?probe=7388498d54) | Nov 22, 2020 |
| Dell          | Latitude E6430              | [a1d7b0f9ab](https://linux-hardware.org/?probe=a1d7b0f9ab) | Nov 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [07b3330478](https://linux-hardware.org/?probe=07b3330478) | Nov 19, 2020 |
| HP            | ProBook 455 G7              | [86e6b8d3b3](https://linux-hardware.org/?probe=86e6b8d3b3) | Nov 18, 2020 |
| Acer          | Aspire V3-772G              | [663a957006](https://linux-hardware.org/?probe=663a957006) | Nov 18, 2020 |
| Apple         | MacBookAir5,2               | [3170b03077](https://linux-hardware.org/?probe=3170b03077) | Nov 17, 2020 |
| Lenovo        | ThinkPad T530 24296HG       | [04b88a5f7b](https://linux-hardware.org/?probe=04b88a5f7b) | Nov 16, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [eafab55a01](https://linux-hardware.org/?probe=eafab55a01) | Nov 15, 2020 |
| HP            | EliteBook Folio 1040 G1     | [572a7393df](https://linux-hardware.org/?probe=572a7393df) | Nov 14, 2020 |
| HP            | ENVY 15                     | [fb33289aed](https://linux-hardware.org/?probe=fb33289aed) | Nov 13, 2020 |
| Dell          | Precision 7530              | [2dca9dbf01](https://linux-hardware.org/?probe=2dca9dbf01) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | [7c89e8677b](https://linux-hardware.org/?probe=7c89e8677b) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | [e996126e7f](https://linux-hardware.org/?probe=e996126e7f) | Nov 12, 2020 |
| HP            | EliteBook x360 1040 G5      | [77d6b5680d](https://linux-hardware.org/?probe=77d6b5680d) | Nov 11, 2020 |
| HP            | Pavilion x2 Detachable P... | [f2fb66005f](https://linux-hardware.org/?probe=f2fb66005f) | Nov 11, 2020 |
| Lenovo        | ThinkPad E15 20RD003HMZ     | [3895f41e90](https://linux-hardware.org/?probe=3895f41e90) | Nov 10, 2020 |
| Acer          | Swift SF314-56              | [0a2c9a74a4](https://linux-hardware.org/?probe=0a2c9a74a4) | Nov 10, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [233b60886e](https://linux-hardware.org/?probe=233b60886e) | Nov 10, 2020 |
| Acer          | Aspire S7-391               | [b2b78adbd5](https://linux-hardware.org/?probe=b2b78adbd5) | Nov 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [04dd6da950](https://linux-hardware.org/?probe=04dd6da950) | Nov 09, 2020 |
| HP            | ProBook 4510s (NX684EA)     | [dfea38f16e](https://linux-hardware.org/?probe=dfea38f16e) | Nov 07, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | EliteBook 8560w             | [8393d44a56](https://linux-hardware.org/?probe=8393d44a56) | Nov 06, 2020 |
| Acer          | Aspire V3-772G              | [ef2f846e22](https://linux-hardware.org/?probe=ef2f846e22) | Nov 04, 2020 |
| ASUSTek       | F3U                         | [a48a07cbcf](https://linux-hardware.org/?probe=a48a07cbcf) | Nov 03, 2020 |
| ASUSTek       | F3U                         | [828ad4fe18](https://linux-hardware.org/?probe=828ad4fe18) | Nov 03, 2020 |
| Acer          | Aspire V3-772G              | [754191159a](https://linux-hardware.org/?probe=754191159a) | Nov 03, 2020 |
| Acer          | V3-771                      | [225dbbeb1d](https://linux-hardware.org/?probe=225dbbeb1d) | Nov 03, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e68efeb7b8](https://linux-hardware.org/?probe=e68efeb7b8) | Nov 01, 2020 |
| Schenker      | SCHENKER SLIM15 SSL15L19    | [fa9a4ec7af](https://linux-hardware.org/?probe=fa9a4ec7af) | Oct 31, 2020 |
| Acer          | Aspire V3-772G              | [5eaea33f57](https://linux-hardware.org/?probe=5eaea33f57) | Oct 31, 2020 |
| HP            | EliteBook 850 G6            | [14f636e00d](https://linux-hardware.org/?probe=14f636e00d) | Oct 30, 2020 |
| Acer          | V3-771                      | [074aa86b30](https://linux-hardware.org/?probe=074aa86b30) | Oct 30, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [cd1259f1c9](https://linux-hardware.org/?probe=cd1259f1c9) | Oct 29, 2020 |
| Dell          | Latitude E7240              | [60701e4df3](https://linux-hardware.org/?probe=60701e4df3) | Oct 29, 2020 |
| TUXEDO        | Unknown                     | [5dead208ed](https://linux-hardware.org/?probe=5dead208ed) | Oct 26, 2020 |
| HP            | OMEN by HP Laptop           | [5f09eb2168](https://linux-hardware.org/?probe=5f09eb2168) | Oct 26, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [3ed569dfa5](https://linux-hardware.org/?probe=3ed569dfa5) | Oct 25, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [72335ec621](https://linux-hardware.org/?probe=72335ec621) | Oct 25, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [a7b0028a1e](https://linux-hardware.org/?probe=a7b0028a1e) | Oct 25, 2020 |
| HP            | EliteBook Folio 1040 G1     | [9489cd1e52](https://linux-hardware.org/?probe=9489cd1e52) | Oct 24, 2020 |
| TUXEDO        | Unknown                     | [f5b04bf34f](https://linux-hardware.org/?probe=f5b04bf34f) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [5aa23a1d7e](https://linux-hardware.org/?probe=5aa23a1d7e) | Oct 23, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [94a8a3e5b3](https://linux-hardware.org/?probe=94a8a3e5b3) | Oct 22, 2020 |
| HP            | EliteBook x360 1040 G5      | [78cbc1663e](https://linux-hardware.org/?probe=78cbc1663e) | Oct 22, 2020 |
| Acer          | V3-771                      | [25aef0ed9b](https://linux-hardware.org/?probe=25aef0ed9b) | Oct 22, 2020 |
| Acer          | V3-771                      | [a360f75508](https://linux-hardware.org/?probe=a360f75508) | Oct 22, 2020 |
| HP            | EliteBook 840 G2            | [3b00a26eab](https://linux-hardware.org/?probe=3b00a26eab) | Oct 22, 2020 |
| HP            | ProBook 650 G2              | [0e8e3a9c90](https://linux-hardware.org/?probe=0e8e3a9c90) | Oct 21, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [4a883571a1](https://linux-hardware.org/?probe=4a883571a1) | Oct 21, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [c527497a87](https://linux-hardware.org/?probe=c527497a87) | Oct 20, 2020 |
| TUXEDO        | Unknown                     | [6a651142bc](https://linux-hardware.org/?probe=6a651142bc) | Oct 20, 2020 |
| TUXEDO        | Book XC1711                 | [85474c7447](https://linux-hardware.org/?probe=85474c7447) | Oct 19, 2020 |
| Unknown       | Unknown                     | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| Lenovo        | ThinkPad W510 4389A16       | [4d825513e3](https://linux-hardware.org/?probe=4d825513e3) | Oct 18, 2020 |
| HP            | Pavilion dv6700             | [632f3c5363](https://linux-hardware.org/?probe=632f3c5363) | Oct 18, 2020 |
| HP            | Pavilion dv6700             | [7fee612d83](https://linux-hardware.org/?probe=7fee612d83) | Oct 18, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [25c98f28de](https://linux-hardware.org/?probe=25c98f28de) | Oct 15, 2020 |
| Lenovo        | ThinkPad R500 2732BHG       | [ce5551a52f](https://linux-hardware.org/?probe=ce5551a52f) | Oct 15, 2020 |
| Dell          | Latitude 7490               | [8b6e96473e](https://linux-hardware.org/?probe=8b6e96473e) | Oct 15, 2020 |
| Dell          | XPS 13 9350                 | [f99a03a6fa](https://linux-hardware.org/?probe=f99a03a6fa) | Oct 14, 2020 |
| Lenovo        | Z51-70 80K6                 | [1392da5d39](https://linux-hardware.org/?probe=1392da5d39) | Oct 14, 2020 |
| Lenovo        | ThinkPad T61 7661WBL        | [f19b646a14](https://linux-hardware.org/?probe=f19b646a14) | Oct 14, 2020 |
| ASUSTek       | GL702ZC                     | [9fef193c0d](https://linux-hardware.org/?probe=9fef193c0d) | Oct 10, 2020 |
| Lenovo        | ThinkPad Edge E530 3259A... | [ee0934ca90](https://linux-hardware.org/?probe=ee0934ca90) | Oct 10, 2020 |
| ASUSTek       | K73SD                       | [776517f452](https://linux-hardware.org/?probe=776517f452) | Oct 10, 2020 |
| ASUSTek       | K73SD                       | [d7b4adfb60](https://linux-hardware.org/?probe=d7b4adfb60) | Oct 10, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [83ae97a2cc](https://linux-hardware.org/?probe=83ae97a2cc) | Oct 08, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [fb75c1edd7](https://linux-hardware.org/?probe=fb75c1edd7) | Oct 05, 2020 |
| Apple         | MacBookAir5,2               | [55abec6174](https://linux-hardware.org/?probe=55abec6174) | Oct 04, 2020 |
| Lenovo        | B71-80 80RJ                 | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| Apple         | MacBookAir5,2               | [ae92ea7a52](https://linux-hardware.org/?probe=ae92ea7a52) | Oct 04, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [b02303b4f3](https://linux-hardware.org/?probe=b02303b4f3) | Oct 04, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [6b46fbb6cd](https://linux-hardware.org/?probe=6b46fbb6cd) | Oct 04, 2020 |
| ASUSTek       | GL702ZC                     | [660657b197](https://linux-hardware.org/?probe=660657b197) | Oct 04, 2020 |
| Lenovo        | B71-80 80RJ                 | [ac6a6e6885](https://linux-hardware.org/?probe=ac6a6e6885) | Oct 03, 2020 |
| Unknown       | Unknown                     | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| Sony          | VPCYB3V1E                   | [f116097e48](https://linux-hardware.org/?probe=f116097e48) | Oct 02, 2020 |
| Samsung       | NC10                        | [8ba791387e](https://linux-hardware.org/?probe=8ba791387e) | Oct 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a295a656f1](https://linux-hardware.org/?probe=a295a656f1) | Sep 30, 2020 |
| Sony          | VGN-AR61ZU                  | [b7d1817106](https://linux-hardware.org/?probe=b7d1817106) | Sep 29, 2020 |
| Dell          | Latitude 7490               | [13cb89196f](https://linux-hardware.org/?probe=13cb89196f) | Sep 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [5faa8e4ca3](https://linux-hardware.org/?probe=5faa8e4ca3) | Sep 28, 2020 |
| ASUSTek       | X510URR                     | [e0520a6f96](https://linux-hardware.org/?probe=e0520a6f96) | Sep 21, 2020 |
| Dell          | XPS 13 9300                 | [b66433f2e6](https://linux-hardware.org/?probe=b66433f2e6) | Sep 20, 2020 |
| ASUSTek       | X541UAK                     | [d0712e5a04](https://linux-hardware.org/?probe=d0712e5a04) | Sep 19, 2020 |
| HP            | Laptop 15-bs1xx             | [711a85f008](https://linux-hardware.org/?probe=711a85f008) | Sep 19, 2020 |
| Lenovo        | ThinkPad T470s 20HGS0B80... | [123de4a1c7](https://linux-hardware.org/?probe=123de4a1c7) | Sep 17, 2020 |
| Toshiba       | Satellite P50-C             | [6245fb1a20](https://linux-hardware.org/?probe=6245fb1a20) | Sep 17, 2020 |
| HP            | ZBook 15 G6                 | [4e73019ac5](https://linux-hardware.org/?probe=4e73019ac5) | Sep 16, 2020 |
| Sony          | SVE1511F4E                  | [891f09413c](https://linux-hardware.org/?probe=891f09413c) | Sep 16, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6130ae6b01](https://linux-hardware.org/?probe=6130ae6b01) | Sep 16, 2020 |
| ASUSTek       | K73SD                       | [67507a1125](https://linux-hardware.org/?probe=67507a1125) | Sep 16, 2020 |
| Lenovo        | ThinkPad P51 20HJS20100     | [0f91d1ee1f](https://linux-hardware.org/?probe=0f91d1ee1f) | Sep 16, 2020 |
| Lenovo        | ThinkPad P51 20HJS20100     | [1288fee0ed](https://linux-hardware.org/?probe=1288fee0ed) | Sep 16, 2020 |
| HP            | Laptop 15-dw0xxx            | [4c0cfd6509](https://linux-hardware.org/?probe=4c0cfd6509) | Sep 16, 2020 |
| HP            | EliteBook 840 G5            | [5511ff7784](https://linux-hardware.org/?probe=5511ff7784) | Sep 15, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [4c15a9819a](https://linux-hardware.org/?probe=4c15a9819a) | Sep 14, 2020 |
| HP            | OMEN by HP Laptop           | [1aca06c6ec](https://linux-hardware.org/?probe=1aca06c6ec) | Sep 14, 2020 |
| HP            | Compaq 15                   | [3c3d5c4299](https://linux-hardware.org/?probe=3c3d5c4299) | Sep 12, 2020 |
| HP            | Compaq 15                   | [8ae9fd7bff](https://linux-hardware.org/?probe=8ae9fd7bff) | Sep 12, 2020 |
| Razer         | Blade                       | [8a242cff29](https://linux-hardware.org/?probe=8a242cff29) | Sep 11, 2020 |
| Toshiba       | PORTEGE Z10T-A              | [0a43ad62d7](https://linux-hardware.org/?probe=0a43ad62d7) | Sep 08, 2020 |
| HP            | EliteBook 840 G5            | [a4465c328f](https://linux-hardware.org/?probe=a4465c328f) | Sep 08, 2020 |
| Lenovo        | ThinkPad Edge E530 3259A... | [deca89911a](https://linux-hardware.org/?probe=deca89911a) | Sep 07, 2020 |
| Dell          | Latitude E7470              | [42f49c6394](https://linux-hardware.org/?probe=42f49c6394) | Sep 07, 2020 |
| Apple         | MacBookPro9,2               | [96509c0af6](https://linux-hardware.org/?probe=96509c0af6) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [59ed33b893](https://linux-hardware.org/?probe=59ed33b893) | Sep 06, 2020 |
| Lenovo        | ThinkPad T590 20N4000BMZ    | [ff7f82b032](https://linux-hardware.org/?probe=ff7f82b032) | Sep 04, 2020 |
| Lenovo        | ThinkPad T590 20N4000BMZ    | [587d4d9277](https://linux-hardware.org/?probe=587d4d9277) | Sep 04, 2020 |
| HP            | Pavilion g6                 | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Apple         | MacBookPro9,2               | [55c17526eb](https://linux-hardware.org/?probe=55c17526eb) | Sep 03, 2020 |
| Apple         | MacBookPro9,2               | [6b4ddf377d](https://linux-hardware.org/?probe=6b4ddf377d) | Sep 03, 2020 |
| HP            | Pavilion g6                 | [ad8002e60e](https://linux-hardware.org/?probe=ad8002e60e) | Sep 01, 2020 |
| HP            | Laptop 15s-fq1xxx           | [5e853f5521](https://linux-hardware.org/?probe=5e853f5521) | Aug 31, 2020 |
| ASUSTek       | GL752VW                     | [d350d76726](https://linux-hardware.org/?probe=d350d76726) | Aug 29, 2020 |
| HP            | Laptop 15s-fq1xxx           | [57bdfdb823](https://linux-hardware.org/?probe=57bdfdb823) | Aug 28, 2020 |
| HP            | ProBook 650 G2              | [ad27d76a1a](https://linux-hardware.org/?probe=ad27d76a1a) | Aug 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | [f58e055469](https://linux-hardware.org/?probe=f58e055469) | Aug 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | [d19c11c74a](https://linux-hardware.org/?probe=d19c11c74a) | Aug 25, 2020 |
| Apple         | MacBookAir4,1               | [b6d976fc76](https://linux-hardware.org/?probe=b6d976fc76) | Aug 24, 2020 |
| Lenovo        | ThinkPad X230 23252S4       | [5fe0becd60](https://linux-hardware.org/?probe=5fe0becd60) | Aug 22, 2020 |
| Lenovo        | ThinkPad X280 20KES3DB00    | [c5e30308a8](https://linux-hardware.org/?probe=c5e30308a8) | Aug 19, 2020 |
| ASUSTek       | GL702ZC                     | [f685b1bfc0](https://linux-hardware.org/?probe=f685b1bfc0) | Aug 18, 2020 |
| HP            | Laptop 15s-fq1xxx           | [3f770a739d](https://linux-hardware.org/?probe=3f770a739d) | Aug 18, 2020 |
| HP            | ZBook 14u G6                | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | [5ffb6aaedb](https://linux-hardware.org/?probe=5ffb6aaedb) | Aug 17, 2020 |
| Acer          | TMP455-M                    | [8ebc259273](https://linux-hardware.org/?probe=8ebc259273) | Aug 17, 2020 |
| HP            | Laptop 15s-fq1xxx           | [19d3840414](https://linux-hardware.org/?probe=19d3840414) | Aug 17, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | [0aebb46ce0](https://linux-hardware.org/?probe=0aebb46ce0) | Aug 16, 2020 |
| Lenovo        | ThinkPad W530 24415QG       | [03d4068143](https://linux-hardware.org/?probe=03d4068143) | Aug 14, 2020 |
| Razer         | Blade Stealth 13 Late 20... | [32d0727725](https://linux-hardware.org/?probe=32d0727725) | Aug 13, 2020 |
| HP            | Pavilion dm1                | [60fa55c570](https://linux-hardware.org/?probe=60fa55c570) | Aug 12, 2020 |
| HP            | Pavilion dm1                | [dc90ba192e](https://linux-hardware.org/?probe=dc90ba192e) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ac527dcde7](https://linux-hardware.org/?probe=ac527dcde7) | Aug 11, 2020 |
| Acer          | Aspire E1-572G              | [1a738a3991](https://linux-hardware.org/?probe=1a738a3991) | Aug 08, 2020 |
| PC Special... | X170SM                      | [0c9f2dc741](https://linux-hardware.org/?probe=0c9f2dc741) | Aug 07, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [1b44a0dac4](https://linux-hardware.org/?probe=1b44a0dac4) | Jul 31, 2020 |
| HP            | EliteBook Folio 1040 G1     | [379f2065ae](https://linux-hardware.org/?probe=379f2065ae) | Jul 31, 2020 |
| HP            | EliteBook Folio 1040 G1     | [50c100fc45](https://linux-hardware.org/?probe=50c100fc45) | Jul 31, 2020 |
| Dell          | Latitude E7470              | [b01705d65a](https://linux-hardware.org/?probe=b01705d65a) | Jul 31, 2020 |
| Dell          | XPS L502X                   | [2d4d18566a](https://linux-hardware.org/?probe=2d4d18566a) | Jul 28, 2020 |
| Dell          | XPS L502X                   | [8bb4b95768](https://linux-hardware.org/?probe=8bb4b95768) | Jul 28, 2020 |
| HP            | Pavilion dm1                | [db3461a440](https://linux-hardware.org/?probe=db3461a440) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| TUXEDO        | Unknown                     | [472fe9bea2](https://linux-hardware.org/?probe=472fe9bea2) | Jul 23, 2020 |
| HP            | EliteBook 840 G6            | [cdc922b41d](https://linux-hardware.org/?probe=cdc922b41d) | Jul 23, 2020 |
| Dell          | XPS 15 9500                 | [de8b60de3d](https://linux-hardware.org/?probe=de8b60de3d) | Jul 23, 2020 |
| Dell          | XPS 15 9560                 | [c90f589ae7](https://linux-hardware.org/?probe=c90f589ae7) | Jul 21, 2020 |
| HP            | OMEN by HP Laptop           | [a9202a9c5e](https://linux-hardware.org/?probe=a9202a9c5e) | Jul 20, 2020 |
| HP            | OMEN by HP Laptop           | [5830171dc4](https://linux-hardware.org/?probe=5830171dc4) | Jul 20, 2020 |
| HP            | Pavilion dm1                | [84fc871f29](https://linux-hardware.org/?probe=84fc871f29) | Jul 18, 2020 |
| HP            | Pavilion dm1                | [ccc4a944e8](https://linux-hardware.org/?probe=ccc4a944e8) | Jul 18, 2020 |
| Lenovo        | ThinkPad T530 24296JG       | [4a78a5df90](https://linux-hardware.org/?probe=4a78a5df90) | Jul 17, 2020 |
| HP            | OMEN by HP Laptop           | [2b163aed02](https://linux-hardware.org/?probe=2b163aed02) | Jul 16, 2020 |
| Lenovo        | ThinkPad T410 2522FY2       | [0b82f79ac2](https://linux-hardware.org/?probe=0b82f79ac2) | Jul 16, 2020 |
| Dell          | XPS 13 9300                 | [26cc806766](https://linux-hardware.org/?probe=26cc806766) | Jul 15, 2020 |
| ASUSTek       | GL702ZC                     | [d6263e655e](https://linux-hardware.org/?probe=d6263e655e) | Jul 15, 2020 |
| Dell          | Latitude E7470              | [1ea1fa80cc](https://linux-hardware.org/?probe=1ea1fa80cc) | Jul 14, 2020 |
| whyopencom... | Unknown                     | [8d75881990](https://linux-hardware.org/?probe=8d75881990) | Jul 14, 2020 |
| Lenovo        | V340-17IWL 81RG             | [49816db41b](https://linux-hardware.org/?probe=49816db41b) | Jul 13, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [e8a304ecb6](https://linux-hardware.org/?probe=e8a304ecb6) | Jul 10, 2020 |
| HP            | EliteBook 820 G2            | [312aabd74a](https://linux-hardware.org/?probe=312aabd74a) | Jul 09, 2020 |
| ASUSTek       | GL702ZC                     | [1c2d33f3dd](https://linux-hardware.org/?probe=1c2d33f3dd) | Jul 08, 2020 |
| HP            | EliteBook 820 G2            | [74b86d62c3](https://linux-hardware.org/?probe=74b86d62c3) | Jul 08, 2020 |
| HP            | EliteBook 820 G2            | [317f89a84a](https://linux-hardware.org/?probe=317f89a84a) | Jul 08, 2020 |
| Dell          | Latitude E4200              | [562288b958](https://linux-hardware.org/?probe=562288b958) | Jun 27, 2020 |
| Acer          | Aspire E1-522               | [e386d1b82d](https://linux-hardware.org/?probe=e386d1b82d) | Jun 22, 2020 |
| Acer          | Aspire E1-522               | [0a89c3643f](https://linux-hardware.org/?probe=0a89c3643f) | Jun 22, 2020 |
| Fujitsu       | LIFEBOOK S782               | [a7efefc897](https://linux-hardware.org/?probe=a7efefc897) | Jun 20, 2020 |
| HP            | EliteBook Folio 1040 G1     | [cd065f162e](https://linux-hardware.org/?probe=cd065f162e) | Jun 20, 2020 |
| ASUSTek       | X550EA                      | [98ccbfcea2](https://linux-hardware.org/?probe=98ccbfcea2) | Jun 19, 2020 |
| ASUSTek       | UX303UB                     | [822415c699](https://linux-hardware.org/?probe=822415c699) | Jun 17, 2020 |
| Lenovo        | ThinkPad T430s 2356GU7      | [287790c54d](https://linux-hardware.org/?probe=287790c54d) | Jun 17, 2020 |
| HP            | EliteBook Folio 1040 G1     | [f0d01779c7](https://linux-hardware.org/?probe=f0d01779c7) | Jun 17, 2020 |
| GPD           | P2 MAX                      | [8786ccb6b6](https://linux-hardware.org/?probe=8786ccb6b6) | Jun 17, 2020 |
| Toshiba       | Satellite L770D-10M         | [6d5d87e5a8](https://linux-hardware.org/?probe=6d5d87e5a8) | Jun 17, 2020 |
| Acer          | Nitro AN515-52              | [37b7bdbe2b](https://linux-hardware.org/?probe=37b7bdbe2b) | Jun 17, 2020 |
| ASUSTek       | GL702ZC                     | [12bfc396d3](https://linux-hardware.org/?probe=12bfc396d3) | Jun 17, 2020 |
| HP            | EliteBook Folio 1040 G1     | [b6fee1670d](https://linux-hardware.org/?probe=b6fee1670d) | Jun 16, 2020 |
| Dell          | Latitude E4200              | [2ee7249efc](https://linux-hardware.org/?probe=2ee7249efc) | Jun 14, 2020 |
| Apple         | MacBookPro6,2               | [e22d69a6c7](https://linux-hardware.org/?probe=e22d69a6c7) | Jun 14, 2020 |
| HP            | Pavilion g7                 | [ee9eefa3e9](https://linux-hardware.org/?probe=ee9eefa3e9) | Jun 14, 2020 |
| HP            | EliteBook 735 G5            | [f0fd278615](https://linux-hardware.org/?probe=f0fd278615) | Jun 13, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [b7b58ba2d6](https://linux-hardware.org/?probe=b7b58ba2d6) | Jun 10, 2020 |
| HP            | ProBook 650 G2              | [3c556d8bae](https://linux-hardware.org/?probe=3c556d8bae) | Jun 10, 2020 |
| ASUSTek       | GL553VD                     | [aa6d4f78a1](https://linux-hardware.org/?probe=aa6d4f78a1) | Jun 09, 2020 |
| ASUSTek       | GL553VD                     | [cc19d86c6b](https://linux-hardware.org/?probe=cc19d86c6b) | Jun 09, 2020 |
| Dell          | Latitude E7470              | [91977e2445](https://linux-hardware.org/?probe=91977e2445) | Jun 07, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [030eb5990c](https://linux-hardware.org/?probe=030eb5990c) | Jun 07, 2020 |
| Lenovo        | Z51-70 80K6                 | [00d1356ce8](https://linux-hardware.org/?probe=00d1356ce8) | Jun 06, 2020 |
| Lenovo        | ThinkPad T410 2539FN8       | [cd7eaa3370](https://linux-hardware.org/?probe=cd7eaa3370) | Jun 06, 2020 |
| HP            | EliteBook Folio 1040 G1     | [c7abaff76b](https://linux-hardware.org/?probe=c7abaff76b) | Jun 02, 2020 |
| Apple         | MacBook5,1                  | [57f813b6d6](https://linux-hardware.org/?probe=57f813b6d6) | May 30, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [7c82f48b11](https://linux-hardware.org/?probe=7c82f48b11) | May 27, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [f7c5e1f4cf](https://linux-hardware.org/?probe=f7c5e1f4cf) | May 27, 2020 |
| Toshiba       | Satellite L770D-10M         | [45d7d93e61](https://linux-hardware.org/?probe=45d7d93e61) | May 27, 2020 |
| GPD           | P2 MAX                      | [0ab7631fa0](https://linux-hardware.org/?probe=0ab7631fa0) | May 27, 2020 |
| Acer          | Nitro AN515-52              | [00fcd3136e](https://linux-hardware.org/?probe=00fcd3136e) | May 27, 2020 |
| ASUSTek       | GL702ZC                     | [408b01ac63](https://linux-hardware.org/?probe=408b01ac63) | May 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [520b0f5836](https://linux-hardware.org/?probe=520b0f5836) | May 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [bf07595146](https://linux-hardware.org/?probe=bf07595146) | May 26, 2020 |
| Lenovo        | ThinkPad T430 2349K63       | [43257c3441](https://linux-hardware.org/?probe=43257c3441) | May 26, 2020 |
| Acer          | Nitro AN515-52              | [b4796fcbb2](https://linux-hardware.org/?probe=b4796fcbb2) | May 25, 2020 |
| ASUSTek       | GL702ZC                     | [9805d6e311](https://linux-hardware.org/?probe=9805d6e311) | May 25, 2020 |
| HP            | ProBook 4720s               | [8a930097b3](https://linux-hardware.org/?probe=8a930097b3) | May 25, 2020 |
| Apple         | MacBookPro11,1              | [316c2aa080](https://linux-hardware.org/?probe=316c2aa080) | May 24, 2020 |
| HP            | Spectre XT Ultrabook PC     | [33888211a1](https://linux-hardware.org/?probe=33888211a1) | May 23, 2020 |
| HP            | Pavilion Notebook           | [fc33c76bdd](https://linux-hardware.org/?probe=fc33c76bdd) | May 23, 2020 |
| HP            | ENVY 15                     | [0cb17045b2](https://linux-hardware.org/?probe=0cb17045b2) | May 23, 2020 |
| HP            | Presario M2000 (EF152EA#... | [0fe7032974](https://linux-hardware.org/?probe=0fe7032974) | May 21, 2020 |
| Dell          | Latitude 5580               | [39fa074546](https://linux-hardware.org/?probe=39fa074546) | May 21, 2020 |
| HP            | ZBook 17 G5                 | [81b70e2c63](https://linux-hardware.org/?probe=81b70e2c63) | May 21, 2020 |
| HP            | EliteBook 840 G2            | [9db9c52de8](https://linux-hardware.org/?probe=9db9c52de8) | May 21, 2020 |
| Dell          | Inspiron MM061              | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| HP            | Pavilion Notebook           | [2450db4a51](https://linux-hardware.org/?probe=2450db4a51) | May 20, 2020 |
| HP            | Pavilion Notebook           | [4afdcc3247](https://linux-hardware.org/?probe=4afdcc3247) | May 20, 2020 |
| HP            | Pavilion Notebook           | [651828652f](https://linux-hardware.org/?probe=651828652f) | May 19, 2020 |
| Dell          | XPS 15 9550                 | [6ea6d22be6](https://linux-hardware.org/?probe=6ea6d22be6) | May 18, 2020 |
| ASUSTek       | GL702ZC                     | [786f385151](https://linux-hardware.org/?probe=786f385151) | May 17, 2020 |
| HP            | EliteBook 840 G2            | [7e2e078ed7](https://linux-hardware.org/?probe=7e2e078ed7) | May 17, 2020 |
| Toshiba       | Satellite L770D-10M         | [0535faa68f](https://linux-hardware.org/?probe=0535faa68f) | May 16, 2020 |
| GPD           | P2 MAX                      | [21f999efbb](https://linux-hardware.org/?probe=21f999efbb) | May 16, 2020 |
| Toshiba       | Satellite L770D-10M         | [2af8e25e81](https://linux-hardware.org/?probe=2af8e25e81) | May 16, 2020 |
| Acer          | Nitro AN515-52              | [44c92d0b7b](https://linux-hardware.org/?probe=44c92d0b7b) | May 16, 2020 |
| ASUSTek       | GL702ZC                     | [0b2ab34e82](https://linux-hardware.org/?probe=0b2ab34e82) | May 16, 2020 |
| HP            | EliteBook 850 G1            | [dcf31c4bd0](https://linux-hardware.org/?probe=dcf31c4bd0) | May 16, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [f3c754042c](https://linux-hardware.org/?probe=f3c754042c) | May 16, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [33c9a53840](https://linux-hardware.org/?probe=33c9a53840) | May 16, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [952d1e7072](https://linux-hardware.org/?probe=952d1e7072) | May 15, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [0478994a03](https://linux-hardware.org/?probe=0478994a03) | May 15, 2020 |
| HP            | G61                         | [37be6028e2](https://linux-hardware.org/?probe=37be6028e2) | May 13, 2020 |
| HP            | ProBook 4510s (NX684EA)     | [d5ef290d7c](https://linux-hardware.org/?probe=d5ef290d7c) | May 11, 2020 |
| Dell          | Latitude E7470              | [faf9979211](https://linux-hardware.org/?probe=faf9979211) | May 10, 2020 |
| HP            | Pavilion dv7                | [886f774f58](https://linux-hardware.org/?probe=886f774f58) | May 07, 2020 |
| Dell          | XPS 15 9550                 | [421908643f](https://linux-hardware.org/?probe=421908643f) | May 06, 2020 |
| Fujitsu       | STYLISTIC Q702              | [df6eb0ead4](https://linux-hardware.org/?probe=df6eb0ead4) | May 06, 2020 |
| Notebook      | N130BU                      | [a82966c663](https://linux-hardware.org/?probe=a82966c663) | May 05, 2020 |
| HP            | Notebook                    | [b181cd3ea7](https://linux-hardware.org/?probe=b181cd3ea7) | May 05, 2020 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [59cab1b572](https://linux-hardware.org/?probe=59cab1b572) | May 04, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [cfa1314238](https://linux-hardware.org/?probe=cfa1314238) | May 04, 2020 |
| Dell          | XPS 15 9550                 | [10f7deeb9a](https://linux-hardware.org/?probe=10f7deeb9a) | May 03, 2020 |
| Dell          | Latitude E4200              | [aa2e8b7fd6](https://linux-hardware.org/?probe=aa2e8b7fd6) | May 03, 2020 |
| Apple         | MacBookPro8,1               | [b2b19968b0](https://linux-hardware.org/?probe=b2b19968b0) | May 03, 2020 |
| HP            | EliteBook 820 G1            | [4962abc204](https://linux-hardware.org/?probe=4962abc204) | May 02, 2020 |
| Razer         | Blade                       | [295cd53ffd](https://linux-hardware.org/?probe=295cd53ffd) | May 01, 2020 |
| ASUSTek       | K54HR                       | [4e3b225150](https://linux-hardware.org/?probe=4e3b225150) | May 01, 2020 |
| HP            | Presario CQ62               | [dbca6018f8](https://linux-hardware.org/?probe=dbca6018f8) | Apr 30, 2020 |
| HP            | EliteBook Folio 1040 G1     | [41cc636255](https://linux-hardware.org/?probe=41cc636255) | Apr 30, 2020 |
| HP            | Presario M2000 (EF152EA#... | [306e665622](https://linux-hardware.org/?probe=306e665622) | Apr 29, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | [88f3f693f1](https://linux-hardware.org/?probe=88f3f693f1) | Apr 28, 2020 |
| ASUSTek       | X751LA                      | [b2d722393a](https://linux-hardware.org/?probe=b2d722393a) | Apr 28, 2020 |
| ASUSTek       | X751LA                      | [803678b78d](https://linux-hardware.org/?probe=803678b78d) | Apr 28, 2020 |
| Dell          | XPS 13 7390                 | [e1dad7a6ef](https://linux-hardware.org/?probe=e1dad7a6ef) | Apr 27, 2020 |
| Dell          | XPS 15 9550                 | [81a846949f](https://linux-hardware.org/?probe=81a846949f) | Apr 27, 2020 |
| ASUSTek       | UX32LA                      | [5324d81db6](https://linux-hardware.org/?probe=5324d81db6) | Apr 26, 2020 |
| ASUSTek       | X205TA                      | [ff7c3fbf23](https://linux-hardware.org/?probe=ff7c3fbf23) | Apr 25, 2020 |
| Lenovo        | ThinkPad W530 24415QG       | [68355ffdc7](https://linux-hardware.org/?probe=68355ffdc7) | Apr 25, 2020 |
| Notebook      | W65_67SZ                    | [dd1415c69a](https://linux-hardware.org/?probe=dd1415c69a) | Apr 22, 2020 |
| ASUSTek       | X205TA                      | [a51b445475](https://linux-hardware.org/?probe=a51b445475) | Apr 21, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [ad2959d25b](https://linux-hardware.org/?probe=ad2959d25b) | Apr 20, 2020 |
| Lenovo        | ThinkPad R61e/R61i 76508... | [6c8a68f429](https://linux-hardware.org/?probe=6c8a68f429) | Apr 19, 2020 |
| Lenovo        | ThinkPad R61e/R61i 76508... | [79cc39e4fe](https://linux-hardware.org/?probe=79cc39e4fe) | Apr 19, 2020 |
| Acer          | Aspire 5250                 | [64c3331e4b](https://linux-hardware.org/?probe=64c3331e4b) | Apr 19, 2020 |
| HP            | Spectre XT Ultrabook PC     | [61a6ec6e80](https://linux-hardware.org/?probe=61a6ec6e80) | Apr 19, 2020 |
| Dell          | Latitude 7490               | [e758664c53](https://linux-hardware.org/?probe=e758664c53) | Apr 18, 2020 |
| HP            | EliteBook 840 G2            | [bd484a81ae](https://linux-hardware.org/?probe=bd484a81ae) | Apr 18, 2020 |
| ASUSTek       | X205TA                      | [ad8ada015d](https://linux-hardware.org/?probe=ad8ada015d) | Apr 16, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | [e9b2348697](https://linux-hardware.org/?probe=e9b2348697) | Apr 16, 2020 |
| Acer          | Aspire E5-576G              | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [fae24ef621](https://linux-hardware.org/?probe=fae24ef621) | Apr 15, 2020 |
| Toshiba       | Satellite C670D-11G         | [bd4c6365f0](https://linux-hardware.org/?probe=bd4c6365f0) | Apr 14, 2020 |
| Toshiba       | Satellite C670D-11G         | [19dc60998e](https://linux-hardware.org/?probe=19dc60998e) | Apr 14, 2020 |
| Toshiba       | PORTEGE Z10T-A              | [e589328dfd](https://linux-hardware.org/?probe=e589328dfd) | Apr 14, 2020 |
| Toshiba       | Satellite C670D-11G         | [4933df93fe](https://linux-hardware.org/?probe=4933df93fe) | Apr 14, 2020 |
| Toshiba       | Satellite C670D-11G         | [32516fb79e](https://linux-hardware.org/?probe=32516fb79e) | Apr 14, 2020 |
| Toshiba       | Satellite C670D-11G         | [e5d9f42564](https://linux-hardware.org/?probe=e5d9f42564) | Apr 14, 2020 |
| Fujitsu       | LIFEBOOK E782               | [d4cc1d31f8](https://linux-hardware.org/?probe=d4cc1d31f8) | Apr 12, 2020 |
| Acer          | Swift SF514-52T             | [5aab994428](https://linux-hardware.org/?probe=5aab994428) | Apr 11, 2020 |
| Toshiba       | Satellite L830              | [b61b14b568](https://linux-hardware.org/?probe=b61b14b568) | Apr 10, 2020 |
| HP            | 250 G6 Notebook PC          | [5fccd4e61a](https://linux-hardware.org/?probe=5fccd4e61a) | Apr 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e3e43fc692](https://linux-hardware.org/?probe=e3e43fc692) | Apr 08, 2020 |
| Toshiba       | Satellite L770D-10M         | [0fbcc1478f](https://linux-hardware.org/?probe=0fbcc1478f) | Apr 08, 2020 |
| GPD           | P2 MAX                      | [1b618772c1](https://linux-hardware.org/?probe=1b618772c1) | Apr 08, 2020 |
| ASUSTek       | GL702ZC                     | [61d485d89a](https://linux-hardware.org/?probe=61d485d89a) | Apr 08, 2020 |
| Acer          | Nitro AN515-52              | [c043b205ae](https://linux-hardware.org/?probe=c043b205ae) | Apr 08, 2020 |
| ASUSTek       | GL702ZC                     | [6d53521870](https://linux-hardware.org/?probe=6d53521870) | Apr 08, 2020 |
| Toshiba       | Satellite L770D-10M         | [2de171c7fb](https://linux-hardware.org/?probe=2de171c7fb) | Apr 08, 2020 |
| GPD           | P2 MAX                      | [4d0fb79b80](https://linux-hardware.org/?probe=4d0fb79b80) | Apr 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [415525e0cb](https://linux-hardware.org/?probe=415525e0cb) | Apr 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [604566e117](https://linux-hardware.org/?probe=604566e117) | Apr 08, 2020 |
| HP            | 250 G6 Notebook PC          | [460449dbc2](https://linux-hardware.org/?probe=460449dbc2) | Apr 07, 2020 |
| HP            | 250 G6 Notebook PC          | [fc6c1fb9af](https://linux-hardware.org/?probe=fc6c1fb9af) | Apr 07, 2020 |
| Acer          | Aspire E1-572G              | [65b7187917](https://linux-hardware.org/?probe=65b7187917) | Apr 06, 2020 |
| Dell          | XPS 15 9570                 | [8fda391db3](https://linux-hardware.org/?probe=8fda391db3) | Apr 03, 2020 |
| HP            | EliteBook 8460p             | [95ea11518e](https://linux-hardware.org/?probe=95ea11518e) | Apr 01, 2020 |
| HP            | EliteBook 8460p             | [10fda9ca4f](https://linux-hardware.org/?probe=10fda9ca4f) | Apr 01, 2020 |
| Acer          | AOD255E                     | [f04d1a1bf5](https://linux-hardware.org/?probe=f04d1a1bf5) | Apr 01, 2020 |
| HP            | Laptop 15-bs1xx             | [266020f70f](https://linux-hardware.org/?probe=266020f70f) | Mar 29, 2020 |
| ASUSTek       | BU201LA                     | [e7400380e1](https://linux-hardware.org/?probe=e7400380e1) | Mar 28, 2020 |
| HP            | Pavilion dv7                | [4dfd72b613](https://linux-hardware.org/?probe=4dfd72b613) | Mar 25, 2020 |
| Alienware     | M17xR3                      | [c95c1a6306](https://linux-hardware.org/?probe=c95c1a6306) | Mar 22, 2020 |
| ASUSTek       | X205TA                      | [1a7c0f8913](https://linux-hardware.org/?probe=1a7c0f8913) | Mar 22, 2020 |
| HP            | Compaq 8510p                | [df003f9b94](https://linux-hardware.org/?probe=df003f9b94) | Mar 19, 2020 |
| HP            | Compaq 8510p                | [6a272fe91c](https://linux-hardware.org/?probe=6a272fe91c) | Mar 19, 2020 |
| Lenovo        | ThinkPad T440s 20ARA0K40... | [e44cab8ed9](https://linux-hardware.org/?probe=e44cab8ed9) | Mar 19, 2020 |
| HP            | EliteBook 1050 G1           | [167fb7714a](https://linux-hardware.org/?probe=167fb7714a) | Mar 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [be9fa7d137](https://linux-hardware.org/?probe=be9fa7d137) | Mar 18, 2020 |
| ASUSTek       | X205TA                      | [6fc8fe8a2b](https://linux-hardware.org/?probe=6fc8fe8a2b) | Mar 18, 2020 |
| ASUSTek       | X205TA                      | [b119001ebe](https://linux-hardware.org/?probe=b119001ebe) | Mar 18, 2020 |
| ASUSTek       | X205TA                      | [6d20d53901](https://linux-hardware.org/?probe=6d20d53901) | Mar 17, 2020 |
| ASUSTek       | X205TA                      | [fe149adc3e](https://linux-hardware.org/?probe=fe149adc3e) | Mar 17, 2020 |
| ASUSTek       | BU201LA                     | [ca91d7623b](https://linux-hardware.org/?probe=ca91d7623b) | Mar 16, 2020 |
| ASUSTek       | X205TA                      | [9c6027e4f4](https://linux-hardware.org/?probe=9c6027e4f4) | Mar 16, 2020 |
| Acer          | Aspire V3-772               | [a272506aba](https://linux-hardware.org/?probe=a272506aba) | Mar 15, 2020 |
| Apple         | MacBookAir4,2               | [4067c9ebf6](https://linux-hardware.org/?probe=4067c9ebf6) | Mar 14, 2020 |
| Apple         | MacBookAir4,2               | [33202d11c3](https://linux-hardware.org/?probe=33202d11c3) | Mar 14, 2020 |
| Apple         | MacBookAir4,2               | [5e585ebf8d](https://linux-hardware.org/?probe=5e585ebf8d) | Mar 14, 2020 |
| Lenovo        | V110-17IKB 80V2             | [627d8806c0](https://linux-hardware.org/?probe=627d8806c0) | Mar 14, 2020 |
| HP            | ProBook 440 G6              | [8bb55a3d9e](https://linux-hardware.org/?probe=8bb55a3d9e) | Mar 13, 2020 |
| ASUSTek       | BU201LA                     | [77506db6b3](https://linux-hardware.org/?probe=77506db6b3) | Mar 07, 2020 |
| ASUSTek       | BU201LA                     | [2d8726b789](https://linux-hardware.org/?probe=2d8726b789) | Mar 07, 2020 |
| Dell          | Latitude E7240              | [5a2177b51f](https://linux-hardware.org/?probe=5a2177b51f) | Mar 07, 2020 |
| Apple         | MacBookPro5,5               | [626eb80e57](https://linux-hardware.org/?probe=626eb80e57) | Mar 06, 2020 |
| Lenovo        | V330-14IKB 81B0             | [f36db4ade4](https://linux-hardware.org/?probe=f36db4ade4) | Mar 03, 2020 |
| Lenovo        | ThinkPad T580 20L90025MZ    | [eec9fced7e](https://linux-hardware.org/?probe=eec9fced7e) | Feb 20, 2020 |
| ASUSTek       | BU201LA                     | [8deefa2e71](https://linux-hardware.org/?probe=8deefa2e71) | Feb 18, 2020 |
| Acer          | Aspire 5250                 | [094dcdba54](https://linux-hardware.org/?probe=094dcdba54) | Feb 16, 2020 |
| Lenovo        | ThinkPad L490 20Q500E2GE    | [600d77c38c](https://linux-hardware.org/?probe=600d77c38c) | Feb 12, 2020 |
| Acer          | Aspire E5-571               | [35c5646f7a](https://linux-hardware.org/?probe=35c5646f7a) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [00b272b639](https://linux-hardware.org/?probe=00b272b639) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [26283f93ce](https://linux-hardware.org/?probe=26283f93ce) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [afc0a67e40](https://linux-hardware.org/?probe=afc0a67e40) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [ca579e3df3](https://linux-hardware.org/?probe=ca579e3df3) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [bea5172578](https://linux-hardware.org/?probe=bea5172578) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [56b40d8872](https://linux-hardware.org/?probe=56b40d8872) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [e4e6b2ff99](https://linux-hardware.org/?probe=e4e6b2ff99) | Feb 06, 2020 |
| Razer         | Blade                       | [f3ca010de6](https://linux-hardware.org/?probe=f3ca010de6) | Feb 05, 2020 |
| HP            | EliteBook 840 G5            | [16a5c6cce2](https://linux-hardware.org/?probe=16a5c6cce2) | Feb 05, 2020 |
| HP            | EliteBook 840 G5            | [cf9327ee85](https://linux-hardware.org/?probe=cf9327ee85) | Feb 03, 2020 |
| HP            | EliteBook 840 G5            | [0b86ca51ce](https://linux-hardware.org/?probe=0b86ca51ce) | Feb 02, 2020 |
| Lenovo        | ThinkPad T460s 20FAS35H0... | [3cac01dde7](https://linux-hardware.org/?probe=3cac01dde7) | Jan 30, 2020 |
| Acer          | Extensa 5620                | [74ce2714b9](https://linux-hardware.org/?probe=74ce2714b9) | Jan 28, 2020 |
| HP            | Pavilion g6                 | [b4dc59c9b5](https://linux-hardware.org/?probe=b4dc59c9b5) | Jan 26, 2020 |
| Dell          | Latitude E5470              | [b7cde05446](https://linux-hardware.org/?probe=b7cde05446) | Jan 25, 2020 |
| HP            | ProBook 470 G4              | [e892d44c9a](https://linux-hardware.org/?probe=e892d44c9a) | Jan 24, 2020 |
| Toshiba       | Satellite C660              | [b26cdf336b](https://linux-hardware.org/?probe=b26cdf336b) | Jan 23, 2020 |
| Dell          | Inspiron 7586               | [817366445e](https://linux-hardware.org/?probe=817366445e) | Jan 19, 2020 |
| Acer          | Aspire A515-51              | [d62b0e00e5](https://linux-hardware.org/?probe=d62b0e00e5) | Jan 16, 2020 |
| Dell          | XPS 15 9570                 | [30eef366f0](https://linux-hardware.org/?probe=30eef366f0) | Jan 14, 2020 |
| Dell          | XPS 15 9570                 | [6c4e2e9577](https://linux-hardware.org/?probe=6c4e2e9577) | Jan 12, 2020 |
| HP            | ProBook 4510s (NX684EA)     | [c5e3713f32](https://linux-hardware.org/?probe=c5e3713f32) | Jan 11, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [52afbedeb1](https://linux-hardware.org/?probe=52afbedeb1) | Jan 11, 2020 |
| HP            | ProBook 4510s (NX684EA)     | [adc6fb36d6](https://linux-hardware.org/?probe=adc6fb36d6) | Jan 11, 2020 |
| HP            | EliteBook Folio 1040 G1     | [aba575e92e](https://linux-hardware.org/?probe=aba575e92e) | Jan 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [46fbb0765e](https://linux-hardware.org/?probe=46fbb0765e) | Jan 08, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [25f2dfdae2](https://linux-hardware.org/?probe=25f2dfdae2) | Jan 02, 2020 |
| whyopencom... | Unknown                     | [f129eb9932](https://linux-hardware.org/?probe=f129eb9932) | Dec 29, 2019 |
| HP            | Laptop 15-bs1xx             | [466f00e8ce](https://linux-hardware.org/?probe=466f00e8ce) | Dec 28, 2019 |
| HP            | Laptop 15-bs1xx             | [3c1859d120](https://linux-hardware.org/?probe=3c1859d120) | Dec 28, 2019 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [41b8e420f5](https://linux-hardware.org/?probe=41b8e420f5) | Dec 25, 2019 |
| HP            | ENVY 15                     | [2e33715189](https://linux-hardware.org/?probe=2e33715189) | Dec 23, 2019 |
| Dell          | XPS 15 9570                 | [0f12a3e78b](https://linux-hardware.org/?probe=0f12a3e78b) | Dec 22, 2019 |
| Acer          | Swift SF515-51T             | [82680ee78b](https://linux-hardware.org/?probe=82680ee78b) | Dec 19, 2019 |
| ASUSTek       | N53SN                       | [b7b1c7df29](https://linux-hardware.org/?probe=b7b1c7df29) | Dec 18, 2019 |
| HP            | EliteBook Folio 1040 G1     | [f9cd4d265e](https://linux-hardware.org/?probe=f9cd4d265e) | Dec 18, 2019 |
| Dell          | XPS 13 9380                 | [ed8598db62](https://linux-hardware.org/?probe=ed8598db62) | Dec 18, 2019 |
| HP            | EliteBook Folio 1040 G1     | [1652336410](https://linux-hardware.org/?probe=1652336410) | Dec 15, 2019 |
| HP            | EliteBook Folio 1040 G1     | [8962c13bbb](https://linux-hardware.org/?probe=8962c13bbb) | Dec 15, 2019 |
| HP            | EliteBook Folio 1040 G1     | [a028ac88e0](https://linux-hardware.org/?probe=a028ac88e0) | Dec 15, 2019 |
| HP            | EliteBook 840 G6            | [6b2396c6ac](https://linux-hardware.org/?probe=6b2396c6ac) | Dec 08, 2019 |
| Dell          | XPS 13 9380                 | [5ad2c7bcc8](https://linux-hardware.org/?probe=5ad2c7bcc8) | Dec 07, 2019 |
| Lenovo        | ThinkPad L380 20M50011MZ    | [9d7fe6ed8f](https://linux-hardware.org/?probe=9d7fe6ed8f) | Dec 05, 2019 |
| ASUSTek       | UX32LA                      | [e6d66177e4](https://linux-hardware.org/?probe=e6d66177e4) | Dec 02, 2019 |
| Intel         | SLIMBOOK                    | [83fd1e037a](https://linux-hardware.org/?probe=83fd1e037a) | Nov 30, 2019 |
| Sony          | VGN-AR61ZU                  | [29555cdbc9](https://linux-hardware.org/?probe=29555cdbc9) | Nov 29, 2019 |
| Sony          | VGN-AR61ZU                  | [f0fdef9237](https://linux-hardware.org/?probe=f0fdef9237) | Nov 29, 2019 |
| Sony          | VGN-AR61ZU                  | [f2d1cef8d0](https://linux-hardware.org/?probe=f2d1cef8d0) | Nov 29, 2019 |
| HP            | ProBook 440 G6              | [c5d25d77c1](https://linux-hardware.org/?probe=c5d25d77c1) | Nov 25, 2019 |
| Acer          | Aspire 5750G                | [12268e6403](https://linux-hardware.org/?probe=12268e6403) | Nov 24, 2019 |
| Lenovo        | IdeaPad C340-14API 81N6     | [e3f4b8cc47](https://linux-hardware.org/?probe=e3f4b8cc47) | Nov 21, 2019 |
| Samsung       | N150P/N210P/N220P           | [ca81165f05](https://linux-hardware.org/?probe=ca81165f05) | Nov 11, 2019 |
| Purism        | Librem 15 v3                | [8200c0dcd0](https://linux-hardware.org/?probe=8200c0dcd0) | Nov 11, 2019 |
| Lenovo        | G50-80 80E5                 | [c8baf0aedf](https://linux-hardware.org/?probe=c8baf0aedf) | Nov 04, 2019 |
| Lenovo        | ThinkPad W530 24415QG       | [e9fdf75898](https://linux-hardware.org/?probe=e9fdf75898) | Nov 03, 2019 |
| HP            | ProBook 4510s (NX684EA)     | [0f854e2760](https://linux-hardware.org/?probe=0f854e2760) | Nov 03, 2019 |
| Lenovo        | ThinkPad X200 7458AL7       | [82bf41baa8](https://linux-hardware.org/?probe=82bf41baa8) | Oct 30, 2019 |
| HP            | ProBook 4720s               | [2b18aab1d4](https://linux-hardware.org/?probe=2b18aab1d4) | Oct 27, 2019 |
| Dell          | XPS 13 9360                 | [6345d39841](https://linux-hardware.org/?probe=6345d39841) | Oct 24, 2019 |
| HP            | 340 G1                      | [f863818e22](https://linux-hardware.org/?probe=f863818e22) | Oct 20, 2019 |
| HP            | 340 G1                      | [e3c7d03451](https://linux-hardware.org/?probe=e3c7d03451) | Oct 16, 2019 |
| HP            | 340 G1                      | [215a000bc9](https://linux-hardware.org/?probe=215a000bc9) | Oct 15, 2019 |
| Acer          | Swift SF515-51T             | [41acdd878f](https://linux-hardware.org/?probe=41acdd878f) | Oct 11, 2019 |
| HP            | ZBook 15u G5                | [2da8c12709](https://linux-hardware.org/?probe=2da8c12709) | Oct 11, 2019 |
| HP            | ZBook 15u G5                | [64f3687189](https://linux-hardware.org/?probe=64f3687189) | Oct 05, 2019 |
| Acer          | Aspire V3-772G              | [9cbde1e6e7](https://linux-hardware.org/?probe=9cbde1e6e7) | Oct 04, 2019 |
| HP            | Pavilion dv6                | [b4abc46a27](https://linux-hardware.org/?probe=b4abc46a27) | Sep 26, 2019 |
| ASUSTek       | UX32LA                      | [0c008d217d](https://linux-hardware.org/?probe=0c008d217d) | Sep 25, 2019 |
| ASUSTek       | UX32LA                      | [e39e3a2562](https://linux-hardware.org/?probe=e39e3a2562) | Sep 25, 2019 |
| ASUSTek       | UX32LA                      | [e0f1a331b9](https://linux-hardware.org/?probe=e0f1a331b9) | Sep 25, 2019 |
| HP            | Pavilion dv6                | [0641c08d81](https://linux-hardware.org/?probe=0641c08d81) | Sep 25, 2019 |
| HP            | Pavilion dv6                | [0486a0da54](https://linux-hardware.org/?probe=0486a0da54) | Sep 25, 2019 |
| Lenovo        | Flex 2-15 20405             | [33a0e5fdca](https://linux-hardware.org/?probe=33a0e5fdca) | Sep 22, 2019 |
| HP            | Laptop 15-da1xxx            | [a615b72041](https://linux-hardware.org/?probe=a615b72041) | Sep 22, 2019 |
| Lenovo        | ThinkPad W530 24415QG       | [38f63abc72](https://linux-hardware.org/?probe=38f63abc72) | Sep 20, 2019 |
| Acer          | Aspire 9420                 | [ba6be6e3d1](https://linux-hardware.org/?probe=ba6be6e3d1) | Sep 18, 2019 |
| Acer          | Aspire 9420                 | [e3d0a72d4c](https://linux-hardware.org/?probe=e3d0a72d4c) | Sep 18, 2019 |
| Acer          | Aspire 9420                 | [812a215a30](https://linux-hardware.org/?probe=812a215a30) | Sep 18, 2019 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [5b2acded8d](https://linux-hardware.org/?probe=5b2acded8d) | Sep 18, 2019 |
| HP            | Laptop 15-da1xxx            | [d0baad03d5](https://linux-hardware.org/?probe=d0baad03d5) | Sep 17, 2019 |
| ASUSTek       | X541UAK                     | [3391ce42a4](https://linux-hardware.org/?probe=3391ce42a4) | Sep 15, 2019 |
| Lenovo        | ThinkPad X220 429136G       | [e608c63a17](https://linux-hardware.org/?probe=e608c63a17) | Sep 13, 2019 |
| HP            | ProBook 4510s (NX684EA)     | [f3e6275a5e](https://linux-hardware.org/?probe=f3e6275a5e) | Sep 03, 2019 |
| Dell          | XPS 13 9370                 | [db11a12d79](https://linux-hardware.org/?probe=db11a12d79) | Aug 30, 2019 |
| Lenovo        | ThinkPad X230 232578G       | [ec40f1eaf7](https://linux-hardware.org/?probe=ec40f1eaf7) | Aug 29, 2019 |
| Sony          | VGN-N31Z_W                  | [b389939ee8](https://linux-hardware.org/?probe=b389939ee8) | Aug 26, 2019 |
| HP            | EliteBook 8570w             | [6505212d74](https://linux-hardware.org/?probe=6505212d74) | Aug 20, 2019 |
| HP            | EliteBook 2540p             | [c7c67b372e](https://linux-hardware.org/?probe=c7c67b372e) | Aug 18, 2019 |
| Acer          | Aspire A515-51              | [c84b37d646](https://linux-hardware.org/?probe=c84b37d646) | Aug 07, 2019 |
| HP            | Laptop 15-dw0xxx            | [e42e6b15b6](https://linux-hardware.org/?probe=e42e6b15b6) | Jul 31, 2019 |
| HP            | ProBook 4510s (NX684EA)     | [ed4599659c](https://linux-hardware.org/?probe=ed4599659c) | Jul 29, 2019 |
| Lenovo        | ThinkPad T440s 20ARA0K3M... | [efd88a9c7a](https://linux-hardware.org/?probe=efd88a9c7a) | Jul 29, 2019 |
| Lenovo        | ThinkPad T440s 20ARA0K3M... | [19fe1122be](https://linux-hardware.org/?probe=19fe1122be) | Jul 29, 2019 |
| HP            | ZBook 14 G2                 | [ac96dd45f9](https://linux-hardware.org/?probe=ac96dd45f9) | Jul 26, 2019 |
| HP            | Pavilion dv6                | [e09686c315](https://linux-hardware.org/?probe=e09686c315) | Jul 24, 2019 |
| HP            | Compaq 6730b (NB021ET#UU... | [6832a5fe8d](https://linux-hardware.org/?probe=6832a5fe8d) | Jul 16, 2019 |
| Sony          | VGN-SZ3HP_B                 | [50e5b9d6ca](https://linux-hardware.org/?probe=50e5b9d6ca) | Jul 10, 2019 |
| Dell          | XPS 13 9380                 | [d4a2d02674](https://linux-hardware.org/?probe=d4a2d02674) | Jul 06, 2019 |
| whyopencom... | Unknown                     | [9ebfe9a2d8](https://linux-hardware.org/?probe=9ebfe9a2d8) | Jul 03, 2019 |
| Lenovo        | ThinkPad L380 20M50011MZ    | [252e0b908d](https://linux-hardware.org/?probe=252e0b908d) | Jun 28, 2019 |
| HP            | TouchSmart tm2              | [746faf4d3a](https://linux-hardware.org/?probe=746faf4d3a) | Jun 28, 2019 |
| HP            | ZBook 14 G2                 | [5bf8f80c1a](https://linux-hardware.org/?probe=5bf8f80c1a) | Jun 26, 2019 |
| HP            | Pavilion 15                 | [cc56a61ba6](https://linux-hardware.org/?probe=cc56a61ba6) | Jun 22, 2019 |
| HP            | ProBook 6560b               | [6140d0688e](https://linux-hardware.org/?probe=6140d0688e) | Jun 19, 2019 |
| HP            | ProBook 6560b               | [8a19b4d629](https://linux-hardware.org/?probe=8a19b4d629) | Jun 19, 2019 |
| Lenovo        | G50-80 80E5                 | [0f8766c667](https://linux-hardware.org/?probe=0f8766c667) | Jun 19, 2019 |
| Samsung       | 700G7C                      | [6e5c32f6b0](https://linux-hardware.org/?probe=6e5c32f6b0) | Jun 18, 2019 |
| HP            | ProBook 4720s               | [a6ec431460](https://linux-hardware.org/?probe=a6ec431460) | Jun 17, 2019 |
| Notebook      | MIM2300                     | [25be6b90ca](https://linux-hardware.org/?probe=25be6b90ca) | Jun 15, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [a659440214](https://linux-hardware.org/?probe=a659440214) | Jun 15, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [0c996875e4](https://linux-hardware.org/?probe=0c996875e4) | Jun 15, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c09ceb2357](https://linux-hardware.org/?probe=c09ceb2357) | Jun 15, 2019 |
| HP            | ProBook 4720s               | [b3e69d5f2c](https://linux-hardware.org/?probe=b3e69d5f2c) | Jun 13, 2019 |
| MPMAN         | NT10                        | [30c34ab5a7](https://linux-hardware.org/?probe=30c34ab5a7) | Jun 08, 2019 |
| HP            | Unknown                     | [6ae9888758](https://linux-hardware.org/?probe=6ae9888758) | Jun 07, 2019 |
| Acer          | Extensa 5630                | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |
| HP            | Pavilion x2 Detachable P... | [7347f3c28f](https://linux-hardware.org/?probe=7347f3c28f) | Jun 02, 2019 |
| HP            | EliteBook 735 G5            | [607dee6bbb](https://linux-hardware.org/?probe=607dee6bbb) | May 30, 2019 |
| HP            | ProBook 4720s               | [4cfb07305a](https://linux-hardware.org/?probe=4cfb07305a) | May 24, 2019 |
| Lenovo        | Flex 2-15 20405             | [539d35250d](https://linux-hardware.org/?probe=539d35250d) | May 20, 2019 |
| Apple         | MacBookPro6,2               | [1beb0f5895](https://linux-hardware.org/?probe=1beb0f5895) | May 12, 2019 |
| HP            | EliteBook 735 G5            | [c261abdcb2](https://linux-hardware.org/?probe=c261abdcb2) | May 11, 2019 |
| Apple         | MacBookPro6,2               | [7dcaaa0aba](https://linux-hardware.org/?probe=7dcaaa0aba) | May 10, 2019 |
| ASUSTek       | X550CA                      | [1bb7adda0a](https://linux-hardware.org/?probe=1bb7adda0a) | May 08, 2019 |
| Dell          | Latitude E7450              | [6c5f8e4975](https://linux-hardware.org/?probe=6c5f8e4975) | May 07, 2019 |
| Lenovo        | ThinkPad T61 6460D6G        | [e313ef3c46](https://linux-hardware.org/?probe=e313ef3c46) | May 05, 2019 |
| HP            | Pavilion dv6700             | [060bde41b0](https://linux-hardware.org/?probe=060bde41b0) | May 04, 2019 |
| Toshiba       | Satellite C850D-102         | [1a0a4e8bcb](https://linux-hardware.org/?probe=1a0a4e8bcb) | Apr 25, 2019 |
| Medion        | Akoya E7226                 | [79d0fc293a](https://linux-hardware.org/?probe=79d0fc293a) | Apr 14, 2019 |
| HP            | Pavilion x2 Detachable P... | [01a6ccacea](https://linux-hardware.org/?probe=01a6ccacea) | Apr 13, 2019 |
| ASUSTek       | X540LA                      | [a75bac056c](https://linux-hardware.org/?probe=a75bac056c) | Apr 11, 2019 |
| ASUSTek       | X540LA                      | [b65a74387a](https://linux-hardware.org/?probe=b65a74387a) | Apr 10, 2019 |
| ASUSTek       | X540LA                      | [249b38e89f](https://linux-hardware.org/?probe=249b38e89f) | Apr 10, 2019 |
| ASUSTek       | X540LA                      | [e26b14d1de](https://linux-hardware.org/?probe=e26b14d1de) | Apr 10, 2019 |
| ASUSTek       | X540LA                      | [0bd2e9c163](https://linux-hardware.org/?probe=0bd2e9c163) | Apr 10, 2019 |
| Acer          | Aspire one 1-431            | [c7647bf1c9](https://linux-hardware.org/?probe=c7647bf1c9) | Apr 09, 2019 |
| Dell          | Latitude E6520              | [8b18d510e6](https://linux-hardware.org/?probe=8b18d510e6) | Apr 09, 2019 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [f582fc7b09](https://linux-hardware.org/?probe=f582fc7b09) | Apr 09, 2019 |
| ASUSTek       | X540LA                      | [a4281ced7f](https://linux-hardware.org/?probe=a4281ced7f) | Apr 07, 2019 |
| Lenovo        | ThinkPad T440s 20ARS0MG0... | [764e1505f9](https://linux-hardware.org/?probe=764e1505f9) | Mar 30, 2019 |
| HP            | Compaq 6910p                | [5ff034e324](https://linux-hardware.org/?probe=5ff034e324) | Mar 27, 2019 |
| HP            | Compaq 6910p                | [d4fd792576](https://linux-hardware.org/?probe=d4fd792576) | Mar 27, 2019 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [ebe0baee7f](https://linux-hardware.org/?probe=ebe0baee7f) | Mar 27, 2019 |
| Acer          | Extensa 5620                | [13df1a9427](https://linux-hardware.org/?probe=13df1a9427) | Mar 16, 2019 |
| LG Electro... | 14ZD970-GX5SK               | [421a29844a](https://linux-hardware.org/?probe=421a29844a) | Mar 09, 2019 |
| Apple         | MacBookPro9,2               | [23c23d0963](https://linux-hardware.org/?probe=23c23d0963) | Feb 10, 2019 |
| Sony          | VPCCB3S1E                   | [1825e1aed8](https://linux-hardware.org/?probe=1825e1aed8) | Feb 06, 2019 |
| Apple         | MacBookPro11,4              | [3faa4af120](https://linux-hardware.org/?probe=3faa4af120) | Jan 17, 2019 |
| HUAWEI        | MACH-WX9                    | [e91a9060a0](https://linux-hardware.org/?probe=e91a9060a0) | Jan 13, 2019 |
| Acer          | Extensa 5510                | [af4af03783](https://linux-hardware.org/?probe=af4af03783) | Dec 29, 2018 |
| HP            | Pavilion dv6                | [17f74b1c5e](https://linux-hardware.org/?probe=17f74b1c5e) | Dec 28, 2018 |
| HP            | Pavilion dv6                | [c296c8a5e5](https://linux-hardware.org/?probe=c296c8a5e5) | Dec 28, 2018 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1e7adbe67a](https://linux-hardware.org/?probe=1e7adbe67a) | Dec 26, 2018 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [a684d1aeea](https://linux-hardware.org/?probe=a684d1aeea) | Dec 26, 2018 |
| Toshiba       | Satellite R850              | [fb960a89a5](https://linux-hardware.org/?probe=fb960a89a5) | Dec 18, 2018 |
| Acer          | TravelMate B113             | [3a384dbaba](https://linux-hardware.org/?probe=3a384dbaba) | Dec 09, 2018 |
| Acer          | TravelMate B113             | [dc1ec21b77](https://linux-hardware.org/?probe=dc1ec21b77) | Dec 09, 2018 |
| Lenovo        | IdeaPad Y500 20193          | [8c427755b7](https://linux-hardware.org/?probe=8c427755b7) | Nov 29, 2018 |
| Notebook      | MIM2300                     | [bb190776db](https://linux-hardware.org/?probe=bb190776db) | Nov 23, 2018 |
| Notebook      | MIM2300                     | [13f74d56de](https://linux-hardware.org/?probe=13f74d56de) | Nov 23, 2018 |
| Acer          | TravelMate B113             | [34b1209bb2](https://linux-hardware.org/?probe=34b1209bb2) | Nov 20, 2018 |
| ASUSTek       | 1015P                       | [58ce9d06ac](https://linux-hardware.org/?probe=58ce9d06ac) | Nov 17, 2018 |
| Dell          | Latitude E6520              | [8e5073fe38](https://linux-hardware.org/?probe=8e5073fe38) | Nov 16, 2018 |
| ASUSTek       | X553MA                      | [c3f51f2dbc](https://linux-hardware.org/?probe=c3f51f2dbc) | Nov 14, 2018 |
| ASUSTek       | X553MA                      | [cd6d60c127](https://linux-hardware.org/?probe=cd6d60c127) | Nov 14, 2018 |
| ASUSTek       | X553MA                      | [1c301b81a1](https://linux-hardware.org/?probe=1c301b81a1) | Nov 14, 2018 |
| ASUSTek       | X553MA                      | [2427e68955](https://linux-hardware.org/?probe=2427e68955) | Nov 12, 2018 |
| Dell          | Latitude D810               | [01ec82b9fa](https://linux-hardware.org/?probe=01ec82b9fa) | Nov 07, 2018 |
| Acer          | Aspire 5253                 | [c49cd8e4e3](https://linux-hardware.org/?probe=c49cd8e4e3) | Nov 02, 2018 |
| Acer          | Aspire 5253                 | [a56b554665](https://linux-hardware.org/?probe=a56b554665) | Nov 02, 2018 |
| Acer          | Aspire 5253                 | [2ff8269050](https://linux-hardware.org/?probe=2ff8269050) | Nov 02, 2018 |
| Sony          | SVE1511F4E                  | [1cbcf1ea17](https://linux-hardware.org/?probe=1cbcf1ea17) | Nov 01, 2018 |
| Sony          | SVE1511F4E                  | [14fa60ef8b](https://linux-hardware.org/?probe=14fa60ef8b) | Nov 01, 2018 |
| Medion        | X783X                       | [852662bdf3](https://linux-hardware.org/?probe=852662bdf3) | Oct 31, 2018 |
| ASUSTek       | X553MA                      | [5e9cf1c9fb](https://linux-hardware.org/?probe=5e9cf1c9fb) | Oct 28, 2018 |
| ASUSTek       | X553MA                      | [e13a3969cf](https://linux-hardware.org/?probe=e13a3969cf) | Oct 28, 2018 |
| ASUSTek       | X553MA                      | [b2a4f5cbe1](https://linux-hardware.org/?probe=b2a4f5cbe1) | Oct 28, 2018 |
| Acer          | Aspire E5-521               | [31181c5775](https://linux-hardware.org/?probe=31181c5775) | Oct 23, 2018 |
| Lenovo        | G570 20079                  | [d1bd6fb889](https://linux-hardware.org/?probe=d1bd6fb889) | Apr 14, 2018 |
| Lenovo        | ThinkPad X230 2320LFG       | [d8640a1ab3](https://linux-hardware.org/?probe=d8640a1ab3) | Mar 12, 2018 |
| Acer          | Aspire A515-51              | [ce4d09bd98](https://linux-hardware.org/?probe=ce4d09bd98) | Feb 03, 2018 |
| ASUSTek       | N73Jn                       | [d97e769583](https://linux-hardware.org/?probe=d97e769583) | Jan 03, 2018 |
| ASUSTek       | N73Jn                       | [0354996b8b](https://linux-hardware.org/?probe=0354996b8b) | Dec 30, 2017 |
| ASUSTek       | N73Jn                       | [6f752ca5a9](https://linux-hardware.org/?probe=6f752ca5a9) | Dec 30, 2017 |
| Dell          | Latitude E6530              | [a53c93d7c1](https://linux-hardware.org/?probe=a53c93d7c1) | Nov 17, 2017 |
| Lenovo        | ThinkPad T420 4236ML1       | [8fa7c7d8e4](https://linux-hardware.org/?probe=8fa7c7d8e4) | Nov 05, 2017 |
| HP            | Pavilion dv6                | [68afe6213f](https://linux-hardware.org/?probe=68afe6213f) | Oct 17, 2017 |
| HP            | ENVY dv7                    | [903c2180a3](https://linux-hardware.org/?probe=903c2180a3) | Oct 04, 2017 |
| Dell          | Inspiron 1720               | [0db1f5a27a](https://linux-hardware.org/?probe=0db1f5a27a) | Sep 17, 2017 |
| HP            | ENVY Laptop 17-ae0xx        | [e116e381dd](https://linux-hardware.org/?probe=e116e381dd) | Aug 22, 2017 |
| HP            | ENVY Laptop 17-ae0xx        | [0fef681def](https://linux-hardware.org/?probe=0fef681def) | Aug 15, 2017 |
| Lenovo        | ThinkPad X230 2320LFG       | [64dd6b6919](https://linux-hardware.org/?probe=64dd6b6919) | Mar 07, 2017 |
| Lenovo        | ThinkPad X230 2320LFG       | [3464d7a029](https://linux-hardware.org/?probe=3464d7a029) | Jan 16, 2017 |
| Dell          | Latitude E5550              | [b451c295b3](https://linux-hardware.org/?probe=b451c295b3) | Dec 31, 2016 |
| HP            | EliteBook 2540p             | [3d853c3fd8](https://linux-hardware.org/?probe=3d853c3fd8) | Dec 20, 2016 |
| HP            | EliteBook 2540p             | [c855dfd733](https://linux-hardware.org/?probe=c855dfd733) | Dec 19, 2016 |
| Lenovo        | G570 20079                  | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |
| Lenovo        | G570 20079                  | [2239d316e8](https://linux-hardware.org/?probe=2239d316e8) | Nov 26, 2015 |
| Lenovo        | G570 20079                  | [8c602f13e9](https://linux-hardware.org/?probe=8c602f13e9) | Nov 26, 2015 |
| Lenovo        | G570 20079                  | [46ebaff7ec](https://linux-hardware.org/?probe=46ebaff7ec) | Nov 25, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 126       | 16.82%  |
| Ubuntu 18.04        | 89        | 11.88%  |
| Debian 10           | 24        | 3.2%    |
| Linux Mint 20.1     | 20        | 2.67%   |
| Debian 11           | 20        | 2.67%   |
| Linux Mint 20.2     | 19        | 2.54%   |
| Ubuntu 21.10        | 17        | 2.27%   |
| OpenMandriva 4.2    | 15        | 2%      |
| Ubuntu 20.10        | 14        | 1.87%   |
| KDE neon 20.04      | 14        | 1.87%   |
| Ubuntu 19.10        | 13        | 1.74%   |
| Linux Mint 20.3     | 13        | 1.74%   |
| Pop!_OS 21.04       | 12        | 1.6%    |
| Linux Mint 19.3     | 11        | 1.47%   |
| Fedora 32           | 11        | 1.47%   |
| Arch                | 11        | 1.47%   |
| Pop!_OS 20.10       | 10        | 1.34%   |
| Pop!_OS 20.04       | 10        | 1.34%   |
| OpenMandriva 4.3    | 10        | 1.34%   |
| Manjaro             | 10        | 1.34%   |
| Kubuntu 20.04       | 10        | 1.34%   |
| Fedora 34           | 10        | 1.34%   |
| Fedora 33           | 9         | 1.2%    |
| Zorin 15            | 8         | 1.07%   |
| Fedora 35           | 8         | 1.07%   |
| ArcoLinux Rolling   | 8         | 1.07%   |
| Arch Rolling        | 8         | 1.07%   |
| Zorin 16            | 7         | 0.93%   |
| Fedora 31           | 7         | 0.93%   |
| Ubuntu MATE 20.04   | 6         | 0.8%    |
| Ubuntu 21.04        | 6         | 0.8%    |
| Ubuntu 19.04        | 6         | 0.8%    |
| LMDE 4              | 6         | 0.8%    |
| ROSA R10            | 5         | 0.67%   |
| Linux Mint 19.1     | 5         | 0.67%   |
| BlackPanther 18.1   | 5         | 0.67%   |
| Xubuntu 18.04       | 4         | 0.53%   |
| openSUSE 20200615   | 4         | 0.53%   |
| openSUSE 20200523   | 4         | 0.53%   |
| openSUSE 20200405   | 4         | 0.53%   |
| Manjaro 20.2        | 4         | 0.53%   |
| Linux Mint 20       | 4         | 0.53%   |
| Kubuntu 18.04       | 4         | 0.53%   |
| Elementary 6.1      | 4         | 0.53%   |
| Ubuntu 16.04        | 3         | 0.4%    |
| ROSA R9             | 3         | 0.4%    |
| ROSA R8             | 3         | 0.4%    |
| ROSA R11.1          | 3         | 0.4%    |
| openSUSE 20210114   | 3         | 0.4%    |
| Lubuntu 20.04       | 3         | 0.4%    |
| Linux Mint 19.2     | 3         | 0.4%    |
| Gentoo 2.7          | 3         | 0.4%    |
| Fedora 29           | 3         | 0.4%    |
| Debian Testing      | 3         | 0.4%    |
| Debian 9            | 3         | 0.4%    |
| Xubuntu 20.04       | 2         | 0.27%   |
| Void Linux          | 2         | 0.27%   |
| Ubuntu Budgie 20.10 | 2         | 0.27%   |
| Ubuntu Budgie 20.04 | 2         | 0.27%   |
| Ubuntu 18.10        | 2         | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 256       | 37.93%  |
| Linux Mint    | 64        | 9.48%   |
| Debian        | 48        | 7.11%   |
| Fedora        | 45        | 6.67%   |
| Pop!_OS       | 34        | 5.04%   |
| OpenMandriva  | 26        | 3.85%   |
| Manjaro       | 25        | 3.7%    |
| Kubuntu       | 18        | 2.67%   |
| Arch          | 18        | 2.67%   |
| Zorin         | 15        | 2.22%   |
| ROSA          | 14        | 2.07%   |
| KDE neon      | 14        | 2.07%   |
| openSUSE      | 12        | 1.78%   |
| ArcoLinux     | 10        | 1.48%   |
| Ubuntu MATE   | 8         | 1.19%   |
| Xubuntu       | 7         | 1.04%   |
| LMDE          | 6         | 0.89%   |
| Endless       | 6         | 0.89%   |
| Elementary    | 6         | 0.89%   |
| Lubuntu       | 5         | 0.74%   |
| Kali          | 5         | 0.74%   |
| Gentoo        | 5         | 0.74%   |
| BlackPanther  | 5         | 0.74%   |
| Ubuntu Budgie | 4         | 0.59%   |
| Void Linux    | 3         | 0.44%   |
| Clear Linux   | 3         | 0.44%   |
| RHEL          | 2         | 0.3%    |
| Artix         | 2         | 0.3%    |
| Solus         | 1         | 0.15%   |
| Reborn OS     | 1         | 0.15%   |
| Peppermint    | 1         | 0.15%   |
| Parrot        | 1         | 0.15%   |
| NixOS         | 1         | 0.15%   |
| MX            | 1         | 0.15%   |
| KaOS          | 1         | 0.15%   |
| Kaisen        | 1         | 0.15%   |
| Garuda Linux  | 1         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 15        | 1.78%   |
| 5.4.0-52-generic         | 14        | 1.66%   |
| 5.4.0-42-generic         | 12        | 1.42%   |
| 5.4.0-58-generic         | 10        | 1.18%   |
| 5.4.0-47-generic         | 10        | 1.18%   |
| 5.16.7-desktop-1omv4003  | 10        | 1.18%   |
| 5.8.0-55-generic         | 8         | 0.95%   |
| 5.4.0-80-generic         | 8         | 0.95%   |
| 5.4.0-72-generic         | 8         | 0.95%   |
| 5.3.0-28-generic         | 8         | 0.95%   |
| 5.8.0-59-generic         | 7         | 0.83%   |
| 5.4.0-81-generic         | 7         | 0.83%   |
| 5.4.0-65-generic         | 7         | 0.83%   |
| 5.4.0-62-generic         | 7         | 0.83%   |
| 5.4.0-48-generic         | 7         | 0.83%   |
| 5.4.0-37-generic         | 7         | 0.83%   |
| 5.13.0-30-generic        | 7         | 0.83%   |
| 5.11.0-43-generic        | 7         | 0.83%   |
| 5.10.0-8-amd64           | 7         | 0.83%   |
| 5.0.0-37-generic         | 7         | 0.83%   |
| 5.4.0-91-generic         | 6         | 0.71%   |
| 5.4.0-73-generic         | 6         | 0.71%   |
| 5.4.0-51-generic         | 6         | 0.71%   |
| 5.3.0-53-generic         | 6         | 0.71%   |
| 5.3.0-51-generic         | 6         | 0.71%   |
| 5.3.0-40-generic         | 6         | 0.71%   |
| 5.13.0-39-generic        | 6         | 0.71%   |
| 5.13.0-35-generic        | 6         | 0.71%   |
| 5.11.0-7620-generic      | 6         | 0.71%   |
| 5.11.0-40-generic        | 6         | 0.71%   |
| 5.11.0-38-generic        | 6         | 0.71%   |
| 4.15.0-96-generic        | 6         | 0.71%   |
| 5.8.0-53-generic         | 5         | 0.59%   |
| 5.4.0-74-generic         | 5         | 0.59%   |
| 5.4.0-66-generic         | 5         | 0.59%   |
| 5.4.0-45-generic         | 5         | 0.59%   |
| 5.4.0-33-generic         | 5         | 0.59%   |
| 5.4.0-29-generic         | 5         | 0.59%   |
| 5.13.0-27-generic        | 5         | 0.59%   |
| 5.11.0-27-generic        | 5         | 0.59%   |
| 4.19.0-13-amd64          | 5         | 0.59%   |
| 4.18.0-15-generic        | 5         | 0.59%   |
| 4.15.0-91-generic        | 5         | 0.59%   |
| 5.8.0-48-generic         | 4         | 0.47%   |
| 5.6.12-1-default         | 4         | 0.47%   |
| 5.6.0-1-default          | 4         | 0.47%   |
| 5.4.0-77-generic         | 4         | 0.47%   |
| 5.4.0-7642-generic       | 4         | 0.47%   |
| 5.4.0-7634-generic       | 4         | 0.47%   |
| 5.3.0-46-generic         | 4         | 0.47%   |
| 5.3.0-24-generic         | 4         | 0.47%   |
| 5.13.0-7620-generic      | 4         | 0.47%   |
| 5.13.0-28-generic        | 4         | 0.47%   |
| 5.11.0-34-generic        | 4         | 0.47%   |
| 5.10.0-9-amd64           | 4         | 0.47%   |
| 5.0.0-27-generic         | 4         | 0.47%   |
| 4.19.0-6-amd64           | 4         | 0.47%   |
| 4.19.0-10-amd64          | 4         | 0.47%   |
| 4.18.16-desktop-1bP      | 4         | 0.47%   |
| 4.18.0-16-generic        | 4         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 162       | 21.09%  |
| 5.8.0   | 59        | 7.68%   |
| 4.15.0  | 56        | 7.29%   |
| 5.11.0  | 53        | 6.9%    |
| 5.13.0  | 44        | 5.73%   |
| 5.3.0   | 41        | 5.34%   |
| 5.0.0   | 26        | 3.39%   |
| 4.19.0  | 26        | 3.39%   |
| 5.10.0  | 24        | 3.13%   |
| 4.18.0  | 18        | 2.34%   |
| 5.10.14 | 16        | 2.08%   |
| 5.16.7  | 10        | 1.3%    |
| 5.6.0   | 7         | 0.91%   |
| 5.6.14  | 6         | 0.78%   |
| 5.15.0  | 6         | 0.78%   |
| 5.14.0  | 6         | 0.78%   |
| 5.9.16  | 4         | 0.52%   |
| 5.6.12  | 4         | 0.52%   |
| 5.5.8   | 4         | 0.52%   |
| 4.18.16 | 4         | 0.52%   |
| 5.9.8   | 3         | 0.39%   |
| 5.9.11  | 3         | 0.39%   |
| 5.7.0   | 3         | 0.39%   |
| 5.6.4   | 3         | 0.39%   |
| 5.16.0  | 3         | 0.39%   |
| 5.13.8  | 3         | 0.39%   |
| 5.12.9  | 3         | 0.39%   |
| 5.11.4  | 3         | 0.39%   |
| 5.11.2  | 3         | 0.39%   |
| 5.11.16 | 3         | 0.39%   |
| 5.10.7  | 3         | 0.39%   |
| 4.9.60  | 3         | 0.39%   |
| 5.9.14  | 2         | 0.26%   |
| 5.9.10  | 2         | 0.26%   |
| 5.9.1   | 2         | 0.26%   |
| 5.8.18  | 2         | 0.26%   |
| 5.8.15  | 2         | 0.26%   |
| 5.7.9   | 2         | 0.26%   |
| 5.7.8   | 2         | 0.26%   |
| 5.7.1   | 2         | 0.26%   |
| 5.6.6   | 2         | 0.26%   |
| 5.3.18  | 2         | 0.26%   |
| 5.17.5  | 2         | 0.26%   |
| 5.17.1  | 2         | 0.26%   |
| 5.16.18 | 2         | 0.26%   |
| 5.16.11 | 2         | 0.26%   |
| 5.15.7  | 2         | 0.26%   |
| 5.15.6  | 2         | 0.26%   |
| 5.15.21 | 2         | 0.26%   |
| 5.15.14 | 2         | 0.26%   |
| 5.14.14 | 2         | 0.26%   |
| 5.13.13 | 2         | 0.26%   |
| 5.11.18 | 2         | 0.26%   |
| 5.10.12 | 2         | 0.26%   |
| 4.9.41  | 2         | 0.26%   |
| 4.9.0   | 2         | 0.26%   |
| 4.4.0   | 2         | 0.26%   |
| 4.1.34  | 2         | 0.26%   |
| 5.9.6   | 1         | 0.13%   |
| 5.9.13  | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 170       | 22.7%   |
| 5.8     | 70        | 9.35%   |
| 5.11    | 69        | 9.21%   |
| 4.15    | 56        | 7.48%   |
| 5.13    | 55        | 7.34%   |
| 5.10    | 53        | 7.08%   |
| 5.3     | 46        | 6.14%   |
| 4.19    | 31        | 4.14%   |
| 5.0     | 28        | 3.74%   |
| 4.18    | 24        | 3.2%    |
| 5.16    | 23        | 3.07%   |
| 5.15    | 20        | 2.67%   |
| 5.9     | 18        | 2.4%    |
| 5.6     | 18        | 2.4%    |
| 5.7     | 12        | 1.6%    |
| 5.12    | 12        | 1.6%    |
| 5.14    | 11        | 1.47%   |
| 4.9     | 11        | 1.47%   |
| 5.5     | 6         | 0.8%    |
| 5.17    | 6         | 0.8%    |
| 5.2     | 2         | 0.27%   |
| 4.4     | 2         | 0.27%   |
| 4.14    | 2         | 0.27%   |
| 4.1     | 2         | 0.27%   |
| 4.20    | 1         | 0.13%   |
| 4.10    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 633       | 97.24%  |
| i686   | 18        | 2.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 297       | 42.98%  |
| Unknown         | 112       | 16.21%  |
| KDE5            | 83        | 12.01%  |
| X-Cinnamon      | 55        | 7.96%   |
| XFCE            | 34        | 4.92%   |
| MATE            | 20        | 2.89%   |
| KDE             | 15        | 2.17%   |
| Cinnamon        | 14        | 2.03%   |
| LXDE            | 10        | 1.45%   |
| LXQt            | 8         | 1.16%   |
| KDE4            | 8         | 1.16%   |
| Pantheon        | 6         | 0.87%   |
| i3              | 6         | 0.87%   |
| Budgie          | 6         | 0.87%   |
| GNOME Flashback | 4         | 0.58%   |
| bspwm           | 4         | 0.58%   |
| Unity           | 2         | 0.29%   |
| qtile           | 2         | 0.29%   |
| sway            | 1         | 0.14%   |
| openbox         | 1         | 0.14%   |
| herbstluftwm    | 1         | 0.14%   |
| GNUstep         | 1         | 0.14%   |
| GNOME Classic   | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 505       | 74.7%   |
| Wayland | 90        | 13.31%  |
| Unknown | 70        | 10.36%  |
| Tty     | 11        | 1.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 362       | 53.16%  |
| GDM     | 105       | 15.42%  |
| SDDM    | 70        | 10.28%  |
| LightDM | 58        | 8.52%   |
| TDM     | 41        | 6.02%   |
| GDM3    | 33        | 4.85%   |
| KDM     | 8         | 1.17%   |
| XDM     | 2         | 0.29%   |
| LXDM    | 1         | 0.15%   |
| GREETD  | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 216       | 32%     |
| de_CH   | 158       | 23.41%  |
| Unknown | 120       | 17.78%  |
| fr_CH   | 44        | 6.52%   |
| de_DE   | 39        | 5.78%   |
| en_GB   | 30        | 4.44%   |
| C       | 16        | 2.37%   |
| fr_FR   | 13        | 1.93%   |
| pt_PT   | 9         | 1.33%   |
| it_IT   | 6         | 0.89%   |
| it_CH   | 4         | 0.59%   |
| pl_PL   | 3         | 0.44%   |
| es_ES   | 2         | 0.3%    |
| en_IE   | 2         | 0.3%    |
| en_CH   | 2         | 0.3%    |
| en_CA   | 2         | 0.3%    |
| de_AT   | 2         | 0.3%    |
| tr_TR   | 1         | 0.15%   |
| ru_RU   | 1         | 0.15%   |
| POSIX   | 1         | 0.15%   |
| nl_BE   | 1         | 0.15%   |
| en_AU   | 1         | 0.15%   |
| de_IT   | 1         | 0.15%   |
| ca_ES   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 379       | 57.51%  |
| BIOS | 280       | 42.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 534       | 79.82%  |
| Btrfs   | 43        | 6.43%   |
| Overlay | 37        | 5.53%   |
| Unknown | 36        | 5.38%   |
| Xfs     | 8         | 1.2%    |
| Zfs     | 6         | 0.9%    |
| Ext2    | 4         | 0.6%    |
| Ext3    | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 375       | 56.39%  |
| GPT     | 224       | 33.68%  |
| MBR     | 66        | 9.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 594       | 89.59%  |
| Yes       | 69        | 10.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 508       | 76.51%  |
| Yes       | 156       | 23.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 163       | 25.08%  |
| Hewlett-Packard     | 155       | 23.85%  |
| Dell                | 82        | 12.62%  |
| Acer                | 66        | 10.15%  |
| ASUSTek Computer    | 55        | 8.46%   |
| Apple               | 27        | 4.15%   |
| Toshiba             | 14        | 2.15%   |
| Sony                | 10        | 1.54%   |
| TUXEDO              | 8         | 1.23%   |
| Notebook            | 8         | 1.23%   |
| Medion              | 8         | 1.23%   |
| Samsung Electronics | 7         | 1.08%   |
| Razer               | 5         | 0.77%   |
| HUAWEI              | 4         | 0.62%   |
| Fujitsu             | 4         | 0.62%   |
| Schenker            | 3         | 0.46%   |
| whyopencomputing    | 2         | 0.31%   |
| PC Specialist       | 2         | 0.31%   |
| Packard Bell        | 2         | 0.31%   |
| MSI                 | 2         | 0.31%   |
| Clevo               | 2         | 0.31%   |
| Alienware           | 2         | 0.31%   |
| TrekStor            | 1         | 0.15%   |
| System76            | 1         | 0.15%   |
| SLIMBOOK            | 1         | 0.15%   |
| Quanta              | 1         | 0.15%   |
| QUANMAX             | 1         | 0.15%   |
| Purism              | 1         | 0.15%   |
| Polaroid            | 1         | 0.15%   |
| OriginPC            | 1         | 0.15%   |
| MPMAN               | 1         | 0.15%   |
| LG Electronics      | 1         | 0.15%   |
| Intel               | 1         | 0.15%   |
| IGEL Technology     | 1         | 0.15%   |
| Hampoo              | 1         | 0.15%   |
| GPD                 | 1         | 0.15%   |
| Google              | 1         | 0.15%   |
| Fujitsu Siemens     | 1         | 0.15%   |
| ARIMA               | 1         | 0.15%   |
| AMI                 | 1         | 0.15%   |
| Unknown             | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 6         | 0.92%   |
| HP Pavilion dv7                       | 5         | 0.77%   |
| Dell XPS 15 9570                      | 5         | 0.77%   |
| Dell Latitude E7240                   | 5         | 0.77%   |
| Dell Latitude 7490                    | 5         | 0.77%   |
| HP Pavilion g7                        | 4         | 0.62%   |
| HP Pavilion dv6                       | 4         | 0.62%   |
| HP Laptop 15-bs1xx                    | 4         | 0.62%   |
| HP ENVY 15                            | 4         | 0.62%   |
| HP EliteBook Folio 1040 G1            | 4         | 0.62%   |
| Dell XPS 15 7590                      | 4         | 0.62%   |
| Apple MacBookPro9,2                   | 4         | 0.62%   |
| Razer Blade                           | 3         | 0.46%   |
| HP Pavilion g6                        | 3         | 0.46%   |
| HP Pavilion 15                        | 3         | 0.46%   |
| HP Notebook                           | 3         | 0.46%   |
| HP ENVY dv7                           | 3         | 0.46%   |
| HP EliteBook 840 G6                   | 3         | 0.46%   |
| HP EliteBook 840 G5                   | 3         | 0.46%   |
| Dell XPS 15 9560                      | 3         | 0.46%   |
| Dell XPS 13 7390                      | 3         | 0.46%   |
| Dell Latitude E7470                   | 3         | 0.46%   |
| Apple MacBookPro8,1                   | 3         | 0.46%   |
| Apple MacBookPro6,2                   | 3         | 0.46%   |
| Apple MacBookPro11,1                  | 3         | 0.46%   |
| Apple MacBookPro10,1                  | 3         | 0.46%   |
| Acer Aspire V3-772G                   | 3         | 0.46%   |
| Acer Aspire A515-51                   | 3         | 0.46%   |
| TUXEDO Pulse 15 Gen1                  | 2         | 0.31%   |
| TUXEDO BC1510 1710                    | 2         | 0.31%   |
| Toshiba Satellite C660                | 2         | 0.31%   |
| Samsung 700G7C                        | 2         | 0.31%   |
| Notebook W65_67SZ                     | 2         | 0.31%   |
| Lenovo Z50-70 20354                   | 2         | 0.31%   |
| Lenovo Yoga Slim 7 14ITL05 82A3       | 2         | 0.31%   |
| Lenovo Yoga 3 Pro-1370 80HE           | 2         | 0.31%   |
| Lenovo ThinkPad X250 20CLS1G70A       | 2         | 0.31%   |
| Lenovo ThinkPad X230 232578G          | 2         | 0.31%   |
| Lenovo ThinkPad X1 Extreme 20MF000RMZ | 2         | 0.31%   |
| Lenovo ThinkPad T530 24296HG          | 2         | 0.31%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW | 2         | 0.31%   |
| Lenovo ThinkPad L15 Gen 2 20X3000YMZ  | 2         | 0.31%   |
| Lenovo ThinkPad E490 20N8CTO1WW       | 2         | 0.31%   |
| Lenovo IdeaPad Y700-15ISK 80NV        | 2         | 0.31%   |
| Lenovo G50-80 80E5                    | 2         | 0.31%   |
| HUAWEI MACH-WX9                       | 2         | 0.31%   |
| HP ProBook 650 G2                     | 2         | 0.31%   |
| HP ProBook 470 G5                     | 2         | 0.31%   |
| HP ProBook 440 G6                     | 2         | 0.31%   |
| HP Pavilion x2 Detachable PC 10       | 2         | 0.31%   |
| HP Pavilion Laptop 15-cs0xxx          | 2         | 0.31%   |
| HP Pavilion dv6700                    | 2         | 0.31%   |
| HP Laptop 15s-fq1xxx                  | 2         | 0.31%   |
| HP Laptop 15-dw0xxx                   | 2         | 0.31%   |
| HP Laptop 15-bs0xx                    | 2         | 0.31%   |
| HP ENVY 17                            | 2         | 0.31%   |
| HP EliteBook Folio 9470m              | 2         | 0.31%   |
| HP EliteBook 855 G7 Notebook PC       | 2         | 0.31%   |
| HP EliteBook 840 G7 Notebook PC       | 2         | 0.31%   |
| HP EliteBook 840 G2                   | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 122       | 18.77%  |
| Acer Aspire           | 43        | 6.62%   |
| HP EliteBook          | 39        | 6%      |
| Dell Latitude         | 35        | 5.38%   |
| HP Pavilion           | 34        | 5.23%   |
| Dell XPS              | 32        | 4.92%   |
| HP ProBook            | 21        | 3.23%   |
| Lenovo IdeaPad        | 15        | 2.31%   |
| HP Laptop             | 15        | 2.31%   |
| HP ENVY               | 12        | 1.85%   |
| Acer Swift            | 11        | 1.69%   |
| Toshiba Satellite     | 10        | 1.54%   |
| Dell Inspiron         | 10        | 1.54%   |
| HP ZBook              | 9         | 1.38%   |
| ASUS VivoBook         | 9         | 1.38%   |
| Lenovo Yoga           | 7         | 1.08%   |
| HP Compaq             | 7         | 1.08%   |
| ASUS ZenBook          | 7         | 1.08%   |
| Unknown               | 6         | 0.92%   |
| Razer Blade           | 5         | 0.77%   |
| Apple MacBookPro11    | 5         | 0.77%   |
| Dell Precision        | 4         | 0.62%   |
| Apple MacBookPro9     | 4         | 0.62%   |
| Lenovo ThinkBook      | 3         | 0.46%   |
| HP OMEN               | 3         | 0.46%   |
| HP Notebook           | 3         | 0.46%   |
| HP 250                | 3         | 0.46%   |
| Fujitsu LIFEBOOK      | 3         | 0.46%   |
| ASUS ROG              | 3         | 0.46%   |
| Apple MacBookPro8     | 3         | 0.46%   |
| Apple MacBookPro6     | 3         | 0.46%   |
| Apple MacBookPro10    | 3         | 0.46%   |
| Acer TravelMate       | 3         | 0.46%   |
| Acer Extensa          | 3         | 0.46%   |
| TUXEDO Pulse          | 2         | 0.31%   |
| TUXEDO BC1510         | 2         | 0.31%   |
| Schenker SCHENKER     | 2         | 0.31%   |
| Samsung 700G7C        | 2         | 0.31%   |
| Packard Bell EasyNote | 2         | 0.31%   |
| Notebook W65          | 2         | 0.31%   |
| Lenovo Z50-70         | 2         | 0.31%   |
| Lenovo Legion         | 2         | 0.31%   |
| Lenovo G50-80         | 2         | 0.31%   |
| HUAWEI MACH-WX9       | 2         | 0.31%   |
| HP Presario           | 2         | 0.31%   |
| ASUS X541UAK          | 2         | 0.31%   |
| Apple MacBookPro5     | 2         | 0.31%   |
| Apple MacBookPro14    | 2         | 0.31%   |
| Apple MacBookAir4     | 2         | 0.31%   |
| Acer Nitro            | 2         | 0.31%   |
| TUXEDO N13xWU         | 1         | 0.15%   |
| TUXEDO Book           | 1         | 0.15%   |
| TrekStor Surfbook     | 1         | 0.15%   |
| Toshiba TECRA         | 1         | 0.15%   |
| Toshiba QOSMIO        | 1         | 0.15%   |
| Toshiba PORTEGE       | 1         | 0.15%   |
| Toshiba NB550D        | 1         | 0.15%   |
| System76 Galago       | 1         | 0.15%   |
| Sony VPCYB3V1E        | 1         | 0.15%   |
| Sony VPCEH2P1E        | 1         | 0.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 74        | 11.38%  |
| 2019 | 68        | 10.46%  |
| 2020 | 67        | 10.31%  |
| 2012 | 58        | 8.92%   |
| 2014 | 50        | 7.69%   |
| 2017 | 46        | 7.08%   |
| 2011 | 46        | 7.08%   |
| 2015 | 42        | 6.46%   |
| 2013 | 38        | 5.85%   |
| 2010 | 37        | 5.69%   |
| 2016 | 32        | 4.92%   |
| 2021 | 28        | 4.31%   |
| 2008 | 21        | 3.23%   |
| 2007 | 17        | 2.62%   |
| 2009 | 16        | 2.46%   |
| 2005 | 5         | 0.77%   |
| 2006 | 4         | 0.62%   |
| 2004 | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 650       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 569       | 86.34%  |
| Enabled  | 90        | 13.66%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 646       | 99.38%  |
| Yes  | 4         | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 167       | 25.04%  |
| 4.01-8.0    | 150       | 22.49%  |
| 8.01-16.0   | 118       | 17.69%  |
| 3.01-4.0    | 107       | 16.04%  |
| 32.01-64.0  | 69        | 10.34%  |
| 1.01-2.0    | 21        | 3.15%   |
| 24.01-32.0  | 12        | 1.8%    |
| 2.01-3.0    | 9         | 1.35%   |
| 64.01-256.0 | 7         | 1.05%   |
| 0.51-1.0    | 7         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 261       | 35.37%  |
| 2.01-3.0   | 183       | 24.8%   |
| 4.01-8.0   | 115       | 15.58%  |
| 3.01-4.0   | 83        | 11.25%  |
| 0.51-1.0   | 53        | 7.18%   |
| 8.01-16.0  | 32        | 4.34%   |
| 16.01-24.0 | 5         | 0.68%   |
| 0.01-0.5   | 4         | 0.54%   |
| 24.01-32.0 | 2         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 506       | 75.41%  |
| 2      | 132       | 19.67%  |
| 3      | 21        | 3.13%   |
| 0      | 8         | 1.19%   |
| 5      | 3         | 0.45%   |
| 4      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 425       | 65.18%  |
| Yes       | 227       | 34.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 547       | 83.26%  |
| No        | 110       | 16.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 640       | 98.46%  |
| No        | 10        | 1.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 517       | 77.98%  |
| No        | 146       | 22.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Switzerland | 650       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Zurich            | 164       | 22.68%  |
| Bern              | 47        | 6.5%    |
| Geneva            | 32        | 4.43%   |
| Basel             | 23        | 3.18%   |
| Lausanne          | 18        | 2.49%   |
| Fribourg          | 15        | 2.07%   |
| Winterthur        | 14        | 1.94%   |
| St. Gallen        | 13        | 1.8%    |
| Neuchatel         | 13        | 1.8%    |
| Lucerne           | 12        | 1.66%   |
| Lugano            | 9         | 1.24%   |
| Biel/Bienne       | 6         | 0.83%   |
| Solothurn         | 5         | 0.69%   |
| Dietikon          | 5         | 0.69%   |
| Bussigny          | 5         | 0.69%   |
| Wettingen         | 4         | 0.55%   |
| Thun              | 4         | 0.55%   |
| Therwil           | 4         | 0.55%   |
| Sion              | 4         | 0.55%   |
| Oftringen         | 4         | 0.55%   |
| Le Sentier        | 4         | 0.55%   |
| Gerlafingen       | 4         | 0.55%   |
| Baden             | 4         | 0.55%   |
| Yverdon-les-Bains | 3         | 0.41%   |
| Uster             | 3         | 0.41%   |
| Staufen           | 3         | 0.41%   |
| Siebnen           | 3         | 0.41%   |
| Riehen            | 3         | 0.41%   |
| Munchenstein      | 3         | 0.41%   |
| Morges            | 3         | 0.41%   |
| Mettmenstetten    | 3         | 0.41%   |
| Meggen            | 3         | 0.41%   |
| Lutisburg         | 3         | 0.41%   |
| Hinwil            | 3         | 0.41%   |
| Grabs             | 3         | 0.41%   |
| Glattbrugg        | 3         | 0.41%   |
| Carouge           | 3         | 0.41%   |
| Zuchwil           | 2         | 0.28%   |
| Wurenlos          | 2         | 0.28%   |
| Wittenbach        | 2         | 0.28%   |
| Wetzikon          | 2         | 0.28%   |
| Villars-sur-Glane | 2         | 0.28%   |
| Viganello         | 2         | 0.28%   |
| Versoix           | 2         | 0.28%   |
| Vernier           | 2         | 0.28%   |
| Uerikon           | 2         | 0.28%   |
| Thalwil           | 2         | 0.28%   |
| Sierre            | 2         | 0.28%   |
| Schaffhausen      | 2         | 0.28%   |
| Rossrueti         | 2         | 0.28%   |
| Reinach           | 2         | 0.28%   |
| Rafz              | 2         | 0.28%   |
| Pully             | 2         | 0.28%   |
| Othmarsingen      | 2         | 0.28%   |
| Opfikon           | 2         | 0.28%   |
| Oberrohrdorf      | 2         | 0.28%   |
| Nyon              | 2         | 0.28%   |
| Nottwil           | 2         | 0.28%   |
| Moriken           | 2         | 0.28%   |
| Meyrin            | 2         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 197       | 312    | 24.56%  |
| Seagate                   | 84        | 110    | 10.47%  |
| WDC                       | 83        | 113    | 10.35%  |
| Toshiba                   | 65        | 85     | 8.1%    |
| SanDisk                   | 51        | 64     | 6.36%   |
| Intel                     | 51        | 59     | 6.36%   |
| SK Hynix                  | 41        | 50     | 5.11%   |
| Unknown                   | 36        | 55     | 4.49%   |
| Hitachi                   | 22        | 31     | 2.74%   |
| Crucial                   | 22        | 40     | 2.74%   |
| Micron Technology         | 17        | 23     | 2.12%   |
| Kingston                  | 16        | 28     | 2%      |
| HGST                      | 16        | 21     | 2%      |
| Apple                     | 15        | 18     | 1.87%   |
| LITEON                    | 12        | 17     | 1.5%    |
| LITEONIT                  | 7         | 8      | 0.87%   |
| Transcend                 | 6         | 9      | 0.75%   |
| OCZ                       | 6         | 6      | 0.75%   |
| A-DATA Technology         | 6         | 11     | 0.75%   |
| Fujitsu                   | 5         | 8      | 0.62%   |
| Intenso                   | 4         | 4      | 0.5%    |
| Corsair                   | 4         | 5      | 0.5%    |
| Lenovo                    | 3         | 3      | 0.37%   |
| KIOXIA                    | 3         | 4      | 0.37%   |
| JMicron                   | 3         | 3      | 0.37%   |
| ASMT                      | 3         | 3      | 0.37%   |
| Silicon Motion            | 2         | 3      | 0.25%   |
| Phison                    | 2         | 4      | 0.25%   |
| LaCie                     | 2         | 2      | 0.25%   |
| USB3.0                    | 1         | 2      | 0.12%   |
| Unknown (CF)              | 1         | 1      | 0.12%   |
| SPCC                      | 1         | 1      | 0.12%   |
| SABRENT                   | 1         | 1      | 0.12%   |
| PLEXTOR                   | 1         | 1      | 0.12%   |
| Phison Electronics        | 1         | 7      | 0.12%   |
| ORICO                     | 1         | 1      | 0.12%   |
| Mushkin                   | 1         | 1      | 0.12%   |
| Micron/Crucial Technology | 1         | 1      | 0.12%   |
| Lite-On                   | 1         | 1      | 0.12%   |
| Leven                     | 1         | 1      | 0.12%   |
| Kolink                    | 1         | 1      | 0.12%   |
| KingSpec                  | 1         | 1      | 0.12%   |
| KingDian                  | 1         | 1      | 0.12%   |
| External                  | 1         | 1      | 0.12%   |
| China                     | 1         | 1      | 0.12%   |
| BIWIN                     | 1         | 1      | 0.12%   |
| ASMedia                   | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB           | 10        | 1.2%    |
| Unknown MMC Card  32GB                  | 9         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 9         | 1.08%   |
| HGST HTS721010A9E630 1TB                | 9         | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB          | 8         | 0.96%   |
| Samsung NVMe SSD Drive 1024GB           | 8         | 0.96%   |
| Toshiba MQ01ABD100 1TB                  | 7         | 0.84%   |
| Seagate ST1000LM048-2E7172 1TB          | 7         | 0.84%   |
| Sandisk NVMe SSD Drive 512GB            | 7         | 0.84%   |
| Samsung SSD 860 EVO 500GB               | 7         | 0.84%   |
| Samsung SSD 850 EVO 500GB               | 7         | 0.84%   |
| Intel NVMe SSD Drive 512GB              | 7         | 0.84%   |
| Unknown MMC Card  128GB                 | 6         | 0.72%   |
| Seagate ST2000LM015-2E8174 2TB          | 6         | 0.72%   |
| Samsung NVMe SSD Drive 512GB            | 6         | 0.72%   |
| Samsung NVMe SSD Drive 2TB              | 6         | 0.72%   |
| Samsung NVMe SSD Drive 256GB            | 6         | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB                | 5         | 0.6%    |
| Toshiba NVMe SSD Drive 512GB            | 5         | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB          | 5         | 0.6%    |
| Samsung SSD 970 EVO 1TB                 | 5         | 0.6%    |
| Samsung SSD 860 EVO 250GB               | 5         | 0.6%    |
| Samsung SSD 860 EVO 1TB                 | 5         | 0.6%    |
| Intel NVMe SSD Drive 1024GB             | 5         | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 4         | 0.48%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 4         | 0.48%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB    | 4         | 0.48%   |
| Unknown MMC Card  64GB                  | 4         | 0.48%   |
| Toshiba NVMe SSD Drive 256GB            | 4         | 0.48%   |
| Toshiba MQ01ABF050 500GB                | 4         | 0.48%   |
| SK Hynix NVMe SSD Drive 1024GB          | 4         | 0.48%   |
| Seagate ST9320325AS 320GB               | 4         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB         | 4         | 0.48%   |
| Samsung SSD 860 EVO M.2 500GB           | 4         | 0.48%   |
| Samsung SSD 850 EVO 250GB               | 4         | 0.48%   |
| Samsung NVMe SSD Drive 500GB            | 4         | 0.48%   |
| Samsung NVMe SSD Drive 1TB              | 4         | 0.48%   |
| Samsung MZVLB512HAJQ-000H1 512GB        | 4         | 0.48%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 4         | 0.48%   |
| Intel SSDPEKNW512G8H 512GB              | 4         | 0.48%   |
| Intel SSDPEKKW256G7 256GB               | 4         | 0.48%   |
| Crucial CT1000MX500SSD1 1TB             | 4         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3         | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.36%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB      | 3         | 0.36%   |
| SK Hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 3         | 0.36%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 0.36%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 3         | 0.36%   |
| Seagate ST9250410AS 250GB               | 3         | 0.36%   |
| Seagate ST2000LM007-1R8174 2TB          | 3         | 0.36%   |
| Seagate ST1000LM049-2GH172 1TB          | 3         | 0.36%   |
| Seagate ST1000LM014-1EJ164 1TB          | 3         | 0.36%   |
| Seagate Expansion+ 2TB                  | 3         | 0.36%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 3         | 0.36%   |
| Sandisk NVMe SSD Drive 256GB            | 3         | 0.36%   |
| Sandisk NVMe SSD Drive 1TB              | 3         | 0.36%   |
| Samsung SSD PM851 mSATA 256GB           | 3         | 0.36%   |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 0.36%   |
| Samsung SSD 970 EVO 500GB               | 3         | 0.36%   |
| Samsung SSD 850 EVO 1TB                 | 3         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 107    | 38.76%  |
| WDC                 | 43        | 60     | 20.57%  |
| Toshiba             | 32        | 35     | 15.31%  |
| Hitachi             | 22        | 31     | 10.53%  |
| HGST                | 16        | 21     | 7.66%   |
| Fujitsu             | 5         | 8      | 2.39%   |
| Samsung Electronics | 3         | 3      | 1.44%   |
| ASMT                | 2         | 2      | 0.96%   |
| Unknown (CF)        | 1         | 1      | 0.48%   |
| Unknown             | 1         | 1      | 0.48%   |
| SABRENT             | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| ASMedia             | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 101       | 128    | 32.69%  |
| SanDisk             | 33        | 42     | 10.68%  |
| Intel               | 22        | 26     | 7.12%   |
| Crucial             | 20        | 38     | 6.47%   |
| WDC                 | 18        | 23     | 5.83%   |
| Apple               | 13        | 15     | 4.21%   |
| Toshiba             | 12        | 18     | 3.88%   |
| SK Hynix            | 12        | 14     | 3.88%   |
| Micron Technology   | 12        | 18     | 3.88%   |
| LITEON              | 12        | 17     | 3.88%   |
| Kingston            | 11        | 23     | 3.56%   |
| LITEONIT            | 7         | 8      | 2.27%   |
| Transcend           | 6         | 9      | 1.94%   |
| OCZ                 | 6         | 6      | 1.94%   |
| Corsair             | 4         | 5      | 1.29%   |
| A-DATA Technology   | 4         | 7      | 1.29%   |
| Intenso             | 3         | 3      | 0.97%   |
| JMicron             | 2         | 2      | 0.65%   |
| USB3.0              | 1         | 2      | 0.32%   |
| Seagate             | 1         | 1      | 0.32%   |
| PLEXTOR             | 1         | 1      | 0.32%   |
| Phison              | 1         | 3      | 0.32%   |
| ORICO               | 1         | 1      | 0.32%   |
| Mushkin             | 1         | 1      | 0.32%   |
| Kolink              | 1         | 1      | 0.32%   |
| KingSpec            | 1         | 1      | 0.32%   |
| KingDian            | 1         | 1      | 0.32%   |
| China               | 1         | 1      | 0.32%   |
| BIWIN               | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 286       | 416    | 37.24%  |
| NVMe    | 233       | 371    | 30.34%  |
| HDD     | 206       | 272    | 26.82%  |
| MMC     | 36        | 55     | 4.69%   |
| Unknown | 7         | 10     | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 427       | 665    | 59.06%  |
| NVMe | 233       | 371    | 32.23%  |
| MMC  | 36        | 55     | 4.98%   |
| SAS  | 27        | 33     | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 325       | 465    | 66.46%  |
| 0.51-1.0   | 143       | 199    | 29.24%  |
| 1.01-2.0   | 18        | 21     | 3.68%   |
| 3.01-4.0   | 2         | 2      | 0.41%   |
| 4.01-10.0  | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 183       | 26.37%  |
| 251-500        | 181       | 26.08%  |
| 501-1000       | 105       | 15.13%  |
| 1001-2000      | 53        | 7.64%   |
| 1-20           | 51        | 7.35%   |
| 51-100         | 47        | 6.77%   |
| Unknown        | 30        | 4.32%   |
| 21-50          | 28        | 4.03%   |
| 2001-3000      | 11        | 1.59%   |
| More than 3000 | 5         | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 296       | 40.66%  |
| 21-50     | 112       | 15.38%  |
| 101-250   | 98        | 13.46%  |
| 51-100    | 85        | 11.68%  |
| 251-500   | 58        | 7.97%   |
| 501-1000  | 30        | 4.12%   |
| Unknown   | 30        | 4.12%   |
| 1001-2000 | 16        | 2.2%    |
| 2001-3000 | 3         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                      | 2         | 2      | 5.88%   |
| WDC WD1600BEKT-60A25T1 160GB                   | 1         | 1      | 2.94%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 2.94%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 2.94%   |
| SK Hynix SC401 SATA 512GB SSD                  | 1         | 2      | 2.94%   |
| SK Hynix SC210 mSATA 256GB SSD                 | 1         | 1      | 2.94%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD          | 1         | 1      | 2.94%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 2.94%   |
| Seagate ST9500420AS 500GB                      | 1         | 2      | 2.94%   |
| Seagate ST9120822AS 120GB                      | 1         | 1      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 2.94%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD            | 1         | 1      | 2.94%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD            | 1         | 1      | 2.94%   |
| SanDisk SD7SB3Q256G1002 256GB SSD              | 1         | 2      | 2.94%   |
| Samsung Electronics SSD 860 EVO M.2 1TB        | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 3      | 2.94%   |
| Samsung Electronics HM500JI 500GB              | 1         | 1      | 2.94%   |
| Micron Technology C300-MTFDDAC064MAG 64GB SSD  | 1         | 1      | 2.94%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.94%   |
| LITEONIT LAT-256M3S 256GB SSD                  | 1         | 1      | 2.94%   |
| Kingston SUV400S37240G 240GB SSD               | 1         | 1      | 2.94%   |
| Intenso SSD Sata III 256GB                     | 1         | 1      | 2.94%   |
| Intel SSDSCKKF256G8H 256GB                     | 1         | 1      | 2.94%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 2.94%   |
| Intel SSDPEKKW256G7 256GB                      | 1         | 1      | 2.94%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 2.94%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 2.94%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 2.94%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 2.94%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 2.94%   |
| Crucial CT512MX100SSD1 512GB                   | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 14.71%  |
| Toshiba             | 4         | 4      | 11.76%  |
| SK Hynix            | 4         | 5      | 11.76%  |
| SanDisk             | 3         | 4      | 8.82%   |
| Samsung Electronics | 3         | 5      | 8.82%   |
| Intel               | 3         | 3      | 8.82%   |
| Hitachi             | 3         | 3      | 8.82%   |
| Micron Technology   | 2         | 2      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| WDC                 | 1         | 1      | 2.94%   |
| LITEONIT            | 1         | 1      | 2.94%   |
| Kingston            | 1         | 1      | 2.94%   |
| Intenso             | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 31.25%  |
| Toshiba             | 4         | 4      | 25%     |
| Hitachi             | 3         | 3      | 18.75%  |
| HGST                | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 17        | 21     | 50%     |
| HDD  | 16        | 17     | 47.06%  |
| NVMe | 1         | 1      | 2.94%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 405       | 675    | 58.02%  |
| Works    | 260       | 410    | 37.25%  |
| Malfunc  | 33        | 39     | 4.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 480       | 63.83%  |
| Samsung Electronics          | 103       | 13.7%   |
| AMD                          | 44        | 5.85%   |
| Sandisk                      | 37        | 4.92%   |
| SK Hynix                     | 28        | 3.72%   |
| Toshiba America Info Systems | 23        | 3.06%   |
| Micron Technology            | 6         | 0.8%    |
| Nvidia                       | 5         | 0.66%   |
| Kingston Technology Company  | 5         | 0.66%   |
| Phison Electronics           | 3         | 0.4%    |
| Marvell Technology Group     | 3         | 0.4%    |
| Lenovo                       | 3         | 0.4%    |
| VIA Technologies             | 2         | 0.27%   |
| Silicon Motion               | 2         | 0.27%   |
| Lite-On Technology           | 2         | 0.27%   |
| KIOXIA                       | 2         | 0.27%   |
| Realtek Semiconductor        | 1         | 0.13%   |
| Micron/Crucial Technology    | 1         | 0.13%   |
| Apple                        | 1         | 0.13%   |
| ADATA Technology             | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 69        | 8.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 65        | 8.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 61        | 7.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 41        | 5.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 38        | 4.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 36        | 4.46%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 31        | 3.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 23        | 2.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 22        | 2.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 21        | 2.6%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 20        | 2.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 17        | 2.1%    |
| Intel SSD 660P Series                                                                  | 15        | 1.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 13        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 13        | 1.61%   |
| Samsung NVMe SSD Controller 980                                                        | 12        | 1.49%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 12        | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 12        | 1.49%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 11        | 1.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 11        | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 11        | 1.36%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 11        | 1.36%   |
| SK Hynix Non-Volatile memory controller                                                | 10        | 1.24%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 10        | 1.24%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 10        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 10        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 10        | 1.24%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 8         | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 8         | 0.99%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 7         | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 7         | 0.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 7         | 0.87%   |
| SK Hynix Gold P31 SSD                                                                  | 6         | 0.74%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 6         | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 6         | 0.74%   |
| Micron Non-Volatile memory controller                                                  | 6         | 0.74%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 5         | 0.62%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 5         | 0.62%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 4         | 0.5%    |
| SK Hynix BC511                                                                         | 4         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 4         | 0.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 0.5%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 0.37%   |
| Sandisk PC SN520 NVMe SSD                                                              | 3         | 0.37%   |
| Nvidia MCP79 AHCI Controller                                                           | 3         | 0.37%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 3         | 0.37%   |
| Lenovo Non-Volatile memory controller                                                  | 3         | 0.37%   |
| Intel SSD 600P Series                                                                  | 3         | 0.37%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.37%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.25%   |
| Samsung Apple PCIe SSD                                                                 | 2         | 0.25%   |
| Phison E12 NVMe Controller                                                             | 2         | 0.25%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.25%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 0.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 0.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 2         | 0.25%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 2         | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 440       | 56.19%  |
| NVMe | 235       | 30.01%  |
| RAID | 63        | 8.05%   |
| IDE  | 45        | 5.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 583       | 89.69%  |
| AMD          | 65        | 10%     |
| CentaurHauls | 2         | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 28        | 4.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 25        | 3.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 18        | 2.77%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 14        | 2.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 13        | 2%      |
| Intel Core i7-8750H CPU @ 2.20GHz           | 12        | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 12        | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 12        | 1.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 10        | 1.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 10        | 1.54%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 9         | 1.38%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 8         | 1.23%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 8         | 1.23%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 8         | 1.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 8         | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 7         | 1.08%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 7         | 1.08%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 7         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 7         | 1.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7         | 1.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 7         | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 7         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 7         | 1.08%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 6         | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 0.92%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 6         | 0.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 5         | 0.77%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 5         | 0.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 5         | 0.77%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 5         | 0.77%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 5         | 0.77%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 5         | 0.77%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 5         | 0.77%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 5         | 0.77%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 5         | 0.77%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 5         | 0.77%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 5         | 0.77%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 5         | 0.77%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 5         | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 5         | 0.77%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 4         | 0.62%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 4         | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 0.62%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 4         | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 0.62%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 4         | 0.62%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 0.62%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 3         | 0.46%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 3         | 0.46%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 3         | 0.46%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 3         | 0.46%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.46%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 3         | 0.46%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 3         | 0.46%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 3         | 0.46%   |
| Intel Core i7-10710U CPU @ 1.10GHz          | 3         | 0.46%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 3         | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 276       | 42.46%  |
| Intel Core i5           | 151       | 23.23%  |
| Other                   | 32        | 4.92%   |
| Intel Core 2 Duo        | 31        | 4.77%   |
| Intel Celeron           | 21        | 3.23%   |
| Intel Core i3           | 17        | 2.62%   |
| AMD Ryzen 7             | 15        | 2.31%   |
| Intel Pentium           | 14        | 2.15%   |
| Intel Atom              | 11        | 1.69%   |
| AMD Ryzen 7 PRO         | 10        | 1.54%   |
| AMD Ryzen 5             | 9         | 1.38%   |
| Intel Core 2            | 7         | 1.08%   |
| Intel Core i9           | 6         | 0.92%   |
| AMD E                   | 5         | 0.77%   |
| Intel Pentium Dual-Core | 4         | 0.62%   |
| Intel Pentium M         | 3         | 0.46%   |
| AMD E1                  | 3         | 0.46%   |
| AMD A8                  | 3         | 0.46%   |
| Intel Xeon              | 2         | 0.31%   |
| Intel Pentium Silver    | 2         | 0.31%   |
| Intel Core M            | 2         | 0.31%   |
| AMD Ryzen 9             | 2         | 0.31%   |
| AMD Phenom II           | 2         | 0.31%   |
| AMD E2                  | 2         | 0.31%   |
| AMD C-50                | 2         | 0.31%   |
| AMD A4                  | 2         | 0.31%   |
| Intel Pentium Gold      | 1         | 0.15%   |
| Intel Pentium Dual      | 1         | 0.15%   |
| Intel Pentium 4         | 1         | 0.15%   |
| Intel Genuine           | 1         | 0.15%   |
| Intel Core m3           | 1         | 0.15%   |
| Intel Celeron Dual-Core | 1         | 0.15%   |
| CentaurHauls VIA Eden   | 1         | 0.15%   |
| CentaurHauls VIA C7     | 1         | 0.15%   |
| AMD Turion 64 X2 Mobile | 1         | 0.15%   |
| AMD Turion 64 Mobile    | 1         | 0.15%   |
| AMD Ryzen 5 PRO         | 1         | 0.15%   |
| AMD Ryzen 3             | 1         | 0.15%   |
| AMD FX                  | 1         | 0.15%   |
| AMD C-60                | 1         | 0.15%   |
| AMD Athlon 64 X2        | 1         | 0.15%   |
| AMD A6                  | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 308       | 47.31%  |
| 4       | 244       | 37.48%  |
| 6       | 45        | 6.91%   |
| 8       | 41        | 6.3%    |
| 1       | 12        | 1.84%   |
| Unknown | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 650       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 520       | 79.75%  |
| 1       | 131       | 20.09%  |
| Unknown | 1         | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 631       | 96.48%  |
| Unknown        | 17        | 2.6%    |
| 32-bit         | 6         | 0.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 16.97%  |
| 0x306a9    | 57        | 8.56%   |
| 0x806ea    | 46        | 6.91%   |
| 0x40651    | 43        | 6.46%   |
| 0x206a7    | 41        | 6.16%   |
| 0x806ec    | 30        | 4.5%    |
| 0x906ea    | 28        | 4.2%    |
| 0x806c1    | 26        | 3.9%    |
| 0x806e9    | 22        | 3.3%    |
| 0x306d4    | 22        | 3.3%    |
| 0x1067a    | 20        | 3%      |
| 0x306c3    | 15        | 2.25%   |
| 0x406e3    | 14        | 2.1%    |
| 0x20655    | 13        | 1.95%   |
| 0xa0652    | 12        | 1.8%    |
| 0x806eb    | 11        | 1.65%   |
| 0x30678    | 11        | 1.65%   |
| 0x20652    | 9         | 1.35%   |
| 0x906e9    | 8         | 1.2%    |
| 0x706e5    | 8         | 1.2%    |
| 0x10676    | 8         | 1.2%    |
| 0x08600103 | 8         | 1.2%    |
| 0x6fd      | 7         | 1.05%   |
| 0x08600106 | 7         | 1.05%   |
| 0x706a1    | 6         | 0.9%    |
| 0x0a50000c | 6         | 0.9%    |
| 0x6f6      | 5         | 0.75%   |
| 0x506e3    | 5         | 0.75%   |
| 0x406c4    | 5         | 0.75%   |
| 0x05000119 | 5         | 0.75%   |
| 0x05000029 | 4         | 0.6%    |
| 0x906ed    | 3         | 0.45%   |
| 0x106ca    | 3         | 0.45%   |
| 0x08108102 | 3         | 0.45%   |
| 0xa0660    | 2         | 0.3%    |
| 0x706a8    | 2         | 0.3%    |
| 0x6fa      | 2         | 0.3%    |
| 0x6d8      | 2         | 0.3%    |
| 0x406c3    | 2         | 0.3%    |
| 0x08608103 | 2         | 0.3%    |
| 0x08600102 | 2         | 0.3%    |
| 0x07030104 | 2         | 0.3%    |
| 0x0700010f | 2         | 0.3%    |
| 0x06006705 | 2         | 0.3%    |
| 0x010000c8 | 2         | 0.3%    |
| 0xf41      | 1         | 0.15%   |
| 0xa0655    | 1         | 0.15%   |
| 0x906ec    | 1         | 0.15%   |
| 0x6f2      | 1         | 0.15%   |
| 0x6d6      | 1         | 0.15%   |
| 0x506c9    | 1         | 0.15%   |
| 0x40661    | 1         | 0.15%   |
| 0x106c2    | 1         | 0.15%   |
| 0x0a50000b | 1         | 0.15%   |
| 0x08608102 | 1         | 0.15%   |
| 0x08600104 | 1         | 0.15%   |
| 0x08108109 | 1         | 0.15%   |
| 0x0810100b | 1         | 0.15%   |
| 0x08001137 | 1         | 0.15%   |
| 0x07000110 | 1         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 177       | 27.23%  |
| Haswell       | 71        | 10.92%  |
| IvyBridge     | 67        | 10.31%  |
| SandyBridge   | 46        | 7.08%   |
| Penryn        | 31        | 4.77%   |
| TigerLake     | 28        | 4.31%   |
| Skylake       | 27        | 4.15%   |
| Broadwell     | 27        | 4.15%   |
| Westmere      | 25        | 3.85%   |
| Zen 2         | 22        | 3.38%   |
| Silvermont    | 20        | 3.08%   |
| CometLake     | 17        | 2.62%   |
| Core          | 16        | 2.46%   |
| IceLake       | 10        | 1.54%   |
| Bobcat        | 10        | 1.54%   |
| Goldmont plus | 8         | 1.23%   |
| Unknown       | 8         | 1.23%   |
| Zen 3         | 7         | 1.08%   |
| Zen+          | 4         | 0.62%   |
| Bonnell       | 4         | 0.62%   |
| P6            | 3         | 0.46%   |
| K8 Hammer     | 3         | 0.46%   |
| Jaguar        | 3         | 0.46%   |
| Excavator     | 3         | 0.46%   |
| Zen           | 2         | 0.31%   |
| Puma          | 2         | 0.31%   |
| K10 Llano     | 2         | 0.31%   |
| K10           | 2         | 0.31%   |
| Steamroller   | 1         | 0.15%   |
| Piledriver    | 1         | 0.15%   |
| NetBurst      | 1         | 0.15%   |
| Nehalem       | 1         | 0.15%   |
| Goldmont      | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 525       | 63.48%  |
| Nvidia           | 190       | 22.97%  |
| AMD              | 110       | 13.3%   |
| VIA Technologies | 2         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 61        | 7.24%   |
| Intel UHD Graphics 620                                                                   | 48        | 5.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 46        | 5.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 39        | 4.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39        | 4.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 30        | 3.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 3.21%   |
| Intel HD Graphics 620                                                                    | 25        | 2.97%   |
| Intel HD Graphics 5500                                                                   | 24        | 2.85%   |
| AMD Renoir                                                                               | 22        | 2.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 2.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 2.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 1.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 1.43%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.95%   |
| Intel HD Graphics 630                                                                    | 8         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.95%   |
| Intel Iris Plus Graphics G7                                                              | 7         | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.71%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 6         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.71%   |
| Intel HD Graphics 530                                                                    | 6         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.71%   |
| AMD Cezanne                                                                              | 6         | 0.71%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.59%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 0.59%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 5         | 0.59%   |
| Nvidia GF108M [NVS 5400M]                                                                | 5         | 0.59%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 0.59%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.59%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.59%   |
| Nvidia GT218M [NVS 3100M]                                                                | 4         | 0.48%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 4         | 0.48%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.48%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.48%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.36%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 3         | 0.36%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.36%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 0.36%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 3         | 0.36%   |
| Nvidia GM108M [GeForce 940M]                                                             | 3         | 0.36%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.36%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.36%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 3         | 0.36%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 3         | 0.36%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 3         | 0.36%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 3         | 0.36%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.36%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.36%   |
| Intel Comet Lake UHD Graphics                                                            | 3         | 0.36%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.36%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 355       | 54.28%  |
| Intel + Nvidia | 149       | 22.78%  |
| 1 x AMD        | 79        | 12.08%  |
| 1 x Nvidia     | 37        | 5.66%   |
| Intel + AMD    | 23        | 3.52%   |
| AMD + Nvidia   | 4         | 0.61%   |
| 2 x AMD        | 3         | 0.46%   |
| 1 x VIA        | 2         | 0.31%   |
| Other          | 1         | 0.15%   |
| 2 x Nvidia     | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 552       | 84.27%  |
| Proprietary | 86        | 13.13%  |
| Unknown     | 17        | 2.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 401       | 60.21%  |
| 1.01-2.0   | 88        | 13.21%  |
| 0.01-0.5   | 75        | 11.26%  |
| 3.01-4.0   | 54        | 8.11%   |
| 0.51-1.0   | 31        | 4.65%   |
| 7.01-8.0   | 10        | 1.5%    |
| 5.01-6.0   | 6         | 0.9%    |
| 2.01-3.0   | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 155       | 20.26%  |
| LG Display              | 138       | 18.04%  |
| Chimei Innolux          | 80        | 10.46%  |
| Samsung Electronics     | 67        | 8.76%   |
| BOE                     | 56        | 7.32%   |
| Sharp                   | 33        | 4.31%   |
| Apple                   | 29        | 3.79%   |
| Lenovo                  | 28        | 3.66%   |
| Dell                    | 24        | 3.14%   |
| Hewlett-Packard         | 19        | 2.48%   |
| Acer                    | 18        | 2.35%   |
| Chi Mei Optoelectronics | 16        | 2.09%   |
| Philips                 | 15        | 1.96%   |
| BenQ                    | 12        | 1.57%   |
| Goldstar                | 10        | 1.31%   |
| InfoVision              | 8         | 1.05%   |
| PANDA                   | 5         | 0.65%   |
| CSO                     | 5         | 0.65%   |
| Sony                    | 4         | 0.52%   |
| LG Philips              | 4         | 0.52%   |
| Ancor Communications    | 4         | 0.52%   |
| Vestel Elektronik       | 3         | 0.39%   |
| Toshiba                 | 3         | 0.39%   |
| Iiyama                  | 3         | 0.39%   |
| Eizo                    | 3         | 0.39%   |
| AOC                     | 3         | 0.39%   |
| Panasonic               | 2         | 0.26%   |
| LGD                     | 2         | 0.26%   |
| HannStar                | 2         | 0.26%   |
| ViewSonic               | 1         | 0.13%   |
| Unknown                 | 1         | 0.13%   |
| TIANMA XM               | 1         | 0.13%   |
| Nvidia                  | 1         | 0.13%   |
| MSI                     | 1         | 0.13%   |
| Matrox                  | 1         | 0.13%   |
| LPL                     | 1         | 0.13%   |
| KDC                     | 1         | 0.13%   |
| JDI                     | 1         | 0.13%   |
| IBM                     | 1         | 0.13%   |
| Denver                  | 1         | 0.13%   |
| CPT                     | 1         | 0.13%   |
| CHD                     | 1         | 0.13%   |
| ASUSTek Computer        | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 7         | 0.9%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.77%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.77%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 6         | 0.77%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.64%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 5         | 0.64%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 5         | 0.64%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 4         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 4         | 0.51%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch             | 4         | 0.51%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 4         | 0.51%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 4         | 0.51%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch             | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 4         | 0.51%   |
| BOE LCD Monitor BOE06EE 1920x1080 309x173mm 13.9-inch                    | 4         | 0.51%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.51%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch     | 3         | 0.38%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 3         | 0.38%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 3         | 0.38%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 3         | 0.38%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 3         | 0.38%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 3         | 0.38%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 3         | 0.38%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 3         | 0.38%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1409 1920x1080 309x173mm 13.9-inch         | 3         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.38%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO429D 1920x1080 382x215mm 17.3-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO31ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.38%   |
| Apple LCD Monitor Color LCD 2880x1800                                    | 3         | 0.38%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                   | 3         | 0.38%   |
| Acer V276HL ACR032F 1920x1080 598x336mm 27.0-inch                        | 3         | 0.38%   |
| Acer ED273 ACR0575 1920x1080 531x299mm 24.0-inch                         | 3         | 0.38%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 2         | 0.26%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 2         | 0.26%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 2         | 0.26%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                  | 2         | 0.26%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.26%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.26%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch                  | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 336       | 46.47%  |
| 1366x768 (WXGA)    | 115       | 15.91%  |
| 1600x900 (HD+)     | 58        | 8.02%   |
| 3840x2160 (4K)     | 41        | 5.67%   |
| 2560x1440 (QHD)    | 36        | 4.98%   |
| 1280x800 (WXGA)    | 31        | 4.29%   |
| 1440x900 (WXGA+)   | 17        | 2.35%   |
| 1920x1200 (WUXGA)  | 14        | 1.94%   |
| 1680x1050 (WSXGA+) | 10        | 1.38%   |
| 3440x1440          | 7         | 0.97%   |
| 2880x1800          | 7         | 0.97%   |
| 3200x1800 (QHD+)   | 6         | 0.83%   |
| 1280x1024 (SXGA)   | 6         | 0.83%   |
| 2560x1600          | 5         | 0.69%   |
| 1024x600           | 5         | 0.69%   |
| 3840x2400          | 3         | 0.41%   |
| 3840x1600          | 3         | 0.41%   |
| 1600x1200          | 3         | 0.41%   |
| 3840x1100          | 2         | 0.28%   |
| 3000x2000          | 2         | 0.28%   |
| 2560x1080          | 2         | 0.28%   |
| 2160x1440          | 2         | 0.28%   |
| 1360x768           | 2         | 0.28%   |
| 1024x768 (XGA)     | 2         | 0.28%   |
| 3840x1080          | 1         | 0.14%   |
| 3286x1080          | 1         | 0.14%   |
| 3072x1920          | 1         | 0.14%   |
| 2560x1024          | 1         | 0.14%   |
| 2288x1287          | 1         | 0.14%   |
| 2048x1152          | 1         | 0.14%   |
| 1920x515           | 1         | 0.14%   |
| Unknown            | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 279       | 36.19%  |
| 13      | 102       | 13.23%  |
| 14      | 90        | 11.67%  |
| 17      | 79        | 10.25%  |
| 27      | 50        | 6.49%   |
| 12      | 38        | 4.93%   |
| 24      | 25        | 3.24%   |
| 23      | 15        | 1.95%   |
| Unknown | 14        | 1.82%   |
| 21      | 12        | 1.56%   |
| 34      | 9         | 1.17%   |
| 31      | 9         | 1.17%   |
| 11      | 9         | 1.17%   |
| 84      | 4         | 0.52%   |
| 20      | 4         | 0.52%   |
| 10      | 4         | 0.52%   |
| 37      | 3         | 0.39%   |
| 32      | 3         | 0.39%   |
| 22      | 3         | 0.39%   |
| 19      | 3         | 0.39%   |
| 54      | 2         | 0.26%   |
| 48      | 2         | 0.26%   |
| 40      | 2         | 0.26%   |
| 25      | 2         | 0.26%   |
| 18      | 2         | 0.26%   |
| 142     | 1         | 0.13%   |
| 72      | 1         | 0.13%   |
| 55      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 16      | 1         | 0.13%   |
| 9       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 404       | 53.02%  |
| 201-300        | 109       | 14.3%   |
| 351-400        | 88        | 11.55%  |
| 501-600        | 85        | 11.15%  |
| 401-500        | 21        | 2.76%   |
| Unknown        | 14        | 1.84%   |
| 701-800        | 12        | 1.57%   |
| 601-700        | 12        | 1.57%   |
| 801-900        | 5         | 0.66%   |
| 1501-2000      | 5         | 0.66%   |
| 1001-1500      | 5         | 0.66%   |
| More than 2000 | 1         | 0.13%   |
| 101-200        | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 537       | 80.51%  |
| 16/10   | 84        | 12.59%  |
| 21/9    | 12        | 1.8%    |
| Unknown | 10        | 1.5%    |
| 3/2     | 7         | 1.05%   |
| 4/3     | 6         | 0.9%    |
| 5/4     | 5         | 0.75%   |
| 3.40    | 2         | 0.3%    |
| 32/9    | 1         | 0.15%   |
| 3.73    | 1         | 0.15%   |
| 2.50    | 1         | 0.15%   |
| 1.00    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 277       | 35.97%  |
| 81-90          | 139       | 18.05%  |
| 121-130        | 68        | 8.83%   |
| 301-350        | 51        | 6.62%   |
| 71-80          | 50        | 6.49%   |
| 201-250        | 42        | 5.45%   |
| 61-70          | 38        | 4.94%   |
| 351-500        | 21        | 2.73%   |
| Unknown        | 14        | 1.82%   |
| 251-300        | 13        | 1.69%   |
| 51-60          | 11        | 1.43%   |
| More than 1000 | 10        | 1.3%    |
| 151-200        | 9         | 1.17%   |
| 131-140        | 9         | 1.17%   |
| 501-1000       | 6         | 0.78%   |
| 41-50          | 4         | 0.52%   |
| 141-150        | 3         | 0.39%   |
| 111-120        | 2         | 0.26%   |
| 91-100         | 2         | 0.26%   |
| 1-40           | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 326       | 43.29%  |
| 101-120       | 182       | 24.17%  |
| 51-100        | 119       | 15.8%   |
| 161-240       | 65        | 8.63%   |
| More than 240 | 40        | 5.31%   |
| Unknown       | 14        | 1.86%   |
| 1-50          | 7         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 513       | 76.45%  |
| 2     | 123       | 18.33%  |
| 0     | 18        | 2.68%   |
| 3     | 17        | 2.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 419       | 39.79%  |
| Realtek Semiconductor             | 269       | 25.55%  |
| Qualcomm Atheros                  | 111       | 10.54%  |
| Broadcom                          | 73        | 6.93%   |
| Broadcom Limited                  | 22        | 2.09%   |
| Ralink                            | 19        | 1.8%    |
| Lenovo                            | 14        | 1.33%   |
| Sierra Wireless                   | 10        | 0.95%   |
| Marvell Technology Group          | 10        | 0.95%   |
| Hewlett-Packard                   | 10        | 0.95%   |
| Dell                              | 10        | 0.95%   |
| MEDIATEK                          | 9         | 0.85%   |
| Ericsson Business Mobile Networks | 9         | 0.85%   |
| Huawei Technologies               | 8         | 0.76%   |
| ASIX Electronics                  | 8         | 0.76%   |
| DisplayLink                       | 7         | 0.66%   |
| Samsung Electronics               | 5         | 0.47%   |
| Nvidia                            | 4         | 0.38%   |
| Fibocom                           | 4         | 0.38%   |
| ASUSTek Computer                  | 4         | 0.38%   |
| TP-Link                           | 3         | 0.28%   |
| Ralink Technology                 | 3         | 0.28%   |
| Edimax Technology                 | 3         | 0.28%   |
| Qualcomm                          | 2         | 0.19%   |
| Linksys                           | 2         | 0.19%   |
| D-Link                            | 2         | 0.19%   |
| Xiaomi                            | 1         | 0.09%   |
| Wilocity                          | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.09%   |
| Novatek Microelectronics          | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| MosChip Semiconductor             | 1         | 0.09%   |
| JMicron Technology                | 1         | 0.09%   |
| Intersil                          | 1         | 0.09%   |
| HMD Global                        | 1         | 0.09%   |
| AVM                               | 1         | 0.09%   |
| Arduino SA                        | 1         | 0.09%   |
| Apple                             | 1         | 0.09%   |
| AMD                               | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 184       | 14.15%  |
| Intel Wi-Fi 6 AX200                                                     | 56        | 4.31%   |
| Intel Wireless 8265 / 8275                                              | 47        | 3.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 39        | 3%      |
| Intel Wireless 7260                                                     | 38        | 2.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 36        | 2.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 33        | 2.54%   |
| Intel Wireless 7265                                                     | 28        | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 20        | 1.54%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 1.46%   |
| Intel Ethernet Connection I218-LM                                       | 19        | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 15        | 1.15%   |
| Intel Wireless 8260                                                     | 15        | 1.15%   |
| Intel Centrino Ultimate-N 6300                                          | 15        | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 1.08%   |
| Intel Ethernet Connection (6) I219-V                                    | 13        | 1%      |
| Intel Ethernet Connection (4) I219-LM                                   | 12        | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                                   | 11        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 0.85%   |
| Intel 82577LM Gigabit Network Connection                                | 11        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.85%   |
| Intel Ethernet Connection (4) I219-V                                    | 10        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 0.77%   |
| Intel Wireless-AC 9260                                                  | 9         | 0.69%   |
| Intel Ethernet Connection I219-LM                                       | 9         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 0.69%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.62%   |
| Intel Wireless 3165                                                     | 8         | 0.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.54%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.54%   |
| Intel Wireless 3160                                                     | 7         | 0.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.54%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                                | 7         | 0.54%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 7         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 7         | 0.54%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                           | 7         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.46%   |
| Intel Ultimate N WiFi Link 5300                                         | 6         | 0.46%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                   | 6         | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.46%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 6         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 5         | 0.38%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 5         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 411       | 60.53%  |
| Qualcomm Atheros      | 94        | 13.84%  |
| Broadcom              | 53        | 7.81%   |
| Realtek Semiconductor | 43        | 6.33%   |
| Ralink                | 19        | 2.8%    |
| Broadcom Limited      | 12        | 1.77%   |
| MEDIATEK              | 7         | 1.03%   |
| Sierra Wireless       | 6         | 0.88%   |
| Dell                  | 6         | 0.88%   |
| Hewlett-Packard       | 5         | 0.74%   |
| Fibocom               | 4         | 0.59%   |
| ASUSTek Computer      | 4         | 0.59%   |
| Ralink Technology     | 3         | 0.44%   |
| Edimax Technology     | 3         | 0.44%   |
| TP-Link               | 2         | 0.29%   |
| Qualcomm              | 2         | 0.29%   |
| Wilocity              | 1         | 0.15%   |
| NetGear               | 1         | 0.15%   |
| Linksys               | 1         | 0.15%   |
| D-Link                | 1         | 0.15%   |
| AVM                   | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 56        | 8.19%   |
| Intel Wireless 8265 / 8275                                              | 47        | 6.87%   |
| Intel Wireless 7260                                                     | 38        | 5.56%   |
| Intel Wireless 7265                                                     | 28        | 4.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 3.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 20        | 2.92%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 2.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.19%   |
| Intel Wireless 8260                                                     | 15        | 2.19%   |
| Intel Centrino Ultimate-N 6300                                          | 15        | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 1.46%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.32%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 1.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.17%   |
| Intel Wireless 3165                                                     | 8         | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.02%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.02%   |
| Intel Wireless 3160                                                     | 7         | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.02%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                         | 6         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.88%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 6         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.73%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 5         | 0.73%   |
| Dell Hub of E-Port Replicator                                           | 5         | 0.73%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 5         | 0.73%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 5         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.58%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.58%   |
| Intel WiFi Link 5100                                                    | 4         | 0.58%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.58%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 4         | 0.58%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.58%   |
| Sierra Wireless EM7455                                                  | 3         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.44%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 3         | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.44%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.44%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                  | 3         | 0.44%   |
| ASUS 802.11ac NIC                                                       | 3         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 256       | 44.06%  |
| Intel                         | 180       | 30.98%  |
| Qualcomm Atheros              | 34        | 5.85%   |
| Broadcom                      | 34        | 5.85%   |
| Lenovo                        | 14        | 2.41%   |
| Marvell Technology Group      | 10        | 1.72%   |
| Broadcom Limited              | 10        | 1.72%   |
| ASIX Electronics              | 8         | 1.38%   |
| DisplayLink                   | 7         | 1.2%    |
| Samsung Electronics           | 5         | 0.86%   |
| Sierra Wireless               | 4         | 0.69%   |
| Nvidia                        | 4         | 0.69%   |
| Huawei Technologies           | 3         | 0.52%   |
| MediaTek                      | 2         | 0.34%   |
| Xiaomi                        | 1         | 0.17%   |
| TP-Link                       | 1         | 0.17%   |
| OnePlus Technology (Shenzhen) | 1         | 0.17%   |
| MosChip Semiconductor         | 1         | 0.17%   |
| Linksys                       | 1         | 0.17%   |
| JMicron Technology            | 1         | 0.17%   |
| HMD Global                    | 1         | 0.17%   |
| Hewlett-Packard               | 1         | 0.17%   |
| D-Link                        | 1         | 0.17%   |
| Apple                         | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 184       | 31.45%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 39        | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 36        | 6.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 33        | 5.64%   |
| Intel Ethernet Connection I218-LM                                              | 19        | 3.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 15        | 2.56%   |
| Intel Ethernet Connection (6) I219-V                                           | 13        | 2.22%   |
| Intel Ethernet Connection (4) I219-LM                                          | 12        | 2.05%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 1.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 11        | 1.88%   |
| Intel Ethernet Connection (4) I219-V                                           | 10        | 1.71%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 1.54%   |
| Intel 82567LM Gigabit Network Connection                                       | 7         | 1.2%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 7         | 1.2%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 7         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 1.2%    |
| Intel Ethernet Connection I217-LM                                              | 6         | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 0.85%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 5         | 0.85%   |
| Intel Ethernet Connection (13) I219-V                                          | 5         | 0.85%   |
| Intel 82566MM Gigabit Network Connection                                       | 5         | 0.85%   |
| Sierra Wireless EM7345 4G LTE                                                  | 4         | 0.68%   |
| Intel Ethernet Connection I219-V                                               | 4         | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.68%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.68%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.51%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.51%   |
| Lenovo USB-C Dock Ethernet                                                     | 3         | 0.51%   |
| Lenovo ThinkPad Lan                                                            | 3         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.51%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.51%   |
| DisplayLink Dell Universal Dock D6000                                          | 3         | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 3         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.34%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.34%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.34%   |
| MediaTek NOA N2                                                                | 2         | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.34%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.34%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 2         | 0.34%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 2         | 0.34%   |
| Intel Ethernet Connection I218-V                                               | 2         | 0.34%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.34%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.34%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.34%   |
| Huawei E353/E3131                                                              | 2         | 0.34%   |
| DisplayLink USB3.0 5K Graphic Docking                                          | 2         | 0.34%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 2         | 0.34%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 2         | 0.34%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 2         | 0.34%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 640       | 52.72%  |
| Ethernet | 544       | 44.81%  |
| Modem    | 29        | 2.39%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 557       | 64.84%  |
| Ethernet | 301       | 35.04%  |
| Modem    | 1         | 0.12%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 480       | 73.85%  |
| 1     | 150       | 23.08%  |
| 3     | 12        | 1.85%   |
| 0     | 8         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 561       | 84.87%  |
| Yes  | 100       | 15.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 299       | 57.5%   |
| Broadcom                        | 43        | 8.27%   |
| Qualcomm Atheros Communications | 26        | 5%      |
| Lite-On Technology              | 24        | 4.62%   |
| Foxconn / Hon Hai               | 24        | 4.62%   |
| Apple                           | 24        | 4.62%   |
| Realtek Semiconductor           | 22        | 4.23%   |
| IMC Networks                    | 12        | 2.31%   |
| Hewlett-Packard                 | 11        | 2.12%   |
| Dell                            | 10        | 1.92%   |
| Ralink                          | 8         | 1.54%   |
| Cambridge Silicon Radio         | 6         | 1.15%   |
| Toshiba                         | 2         | 0.38%   |
| Alps Electric                   | 2         | 0.38%   |
| USI                             | 1         | 0.19%   |
| Taiyo Yuden                     | 1         | 0.19%   |
| Ralink Technology               | 1         | 0.19%   |
| Micro Star International        | 1         | 0.19%   |
| Foxconn International           | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |
| ASUSTek Computer                | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 139       | 26.68%  |
| Intel AX200 Bluetooth                                                               | 54        | 10.36%  |
| Intel AX201 Bluetooth                                                               | 45        | 8.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 32        | 6.14%   |
| Apple Bluetooth Host Controller                                                     | 17        | 3.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 2.88%   |
| Realtek Bluetooth Radio                                                             | 13        | 2.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 2.3%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 2.11%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 10        | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 1.73%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 9         | 1.73%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 1.54%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 1.34%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 7         | 1.34%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 1.15%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.15%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 1.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 1.15%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 0.77%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 4         | 0.77%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.77%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 0.77%   |
| Realtek 802.11n WLAN Adapter                                                        | 3         | 0.58%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 0.58%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.58%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 0.58%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.58%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.58%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.58%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 0.58%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.58%   |
| Lite-On Wireless_Device                                                             | 2         | 0.38%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]                                         | 2         | 0.38%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.38%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.38%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.38%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.38%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.38%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.38%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.38%   |
| USI Bluetooth Device                                                                | 1         | 0.19%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.19%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 0.19%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.19%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.19%   |
| Ralink CSR BS8510                                                                   | 1         | 0.19%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.19%   |
| Micro Star International Bluetooth EDR Device                                       | 1         | 0.19%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.19%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.19%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.19%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.19%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 1         | 0.19%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 1         | 0.19%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.19%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 571       | 71.11%  |
| Nvidia                   | 92        | 11.46%  |
| AMD                      | 82        | 10.21%  |
| Lenovo                   | 10        | 1.25%   |
| GN Netcom                | 7         | 0.87%   |
| Hewlett-Packard          | 6         | 0.75%   |
| Realtek Semiconductor    | 5         | 0.62%   |
| Plantronics              | 4         | 0.5%    |
| C-Media Electronics      | 4         | 0.5%    |
| VIA Technologies         | 2         | 0.25%   |
| Logitech                 | 2         | 0.25%   |
| Conexant Systems         | 2         | 0.25%   |
| BEHRINGER International  | 2         | 0.25%   |
| Tenx Technology          | 1         | 0.12%   |
| SteelSeries ApS          | 1         | 0.12%   |
| RODE Microphones         | 1         | 0.12%   |
| Other World Computing    | 1         | 0.12%   |
| miniDSP                  | 1         | 0.12%   |
| Magic Control Technology | 1         | 0.12%   |
| Kingston Technology      | 1         | 0.12%   |
| JMTek                    | 1         | 0.12%   |
| Griffin Technology       | 1         | 0.12%   |
| freeVoice                | 1         | 0.12%   |
| Elite Silicon            | 1         | 0.12%   |
| Cambridge Silicon Radio  | 1         | 0.12%   |
| Astro Gaming             | 1         | 0.12%   |
| Afatech                  | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 97        | 10.16%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 73        | 7.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 4.92%   |
| Intel 8 Series HD Audio Controller                                                                | 47        | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 40        | 4.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 39        | 4.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 37        | 3.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 35        | 3.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 29        | 3.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 28        | 2.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 2.83%   |
| Intel Broadwell-U Audio Controller                                                                | 27        | 2.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24        | 2.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 23        | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 1.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 1.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 1.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 1.36%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 12        | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 12        | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 1.26%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 1.05%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 0.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 0.73%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 0.73%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 0.63%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 6         | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.52%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 5         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 0.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.52%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.42%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.42%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.42%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.42%   |
| Nvidia Audio device                                                                               | 4         | 0.42%   |
| Hewlett-Packard USB Audio                                                                         | 4         | 0.42%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.31%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.31%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.31%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 3         | 0.31%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.31%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.31%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.31%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.31%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.31%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.21%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.21%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.21%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.21%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 152       | 35.68%  |
| SK Hynix            | 101       | 23.71%  |
| Kingston            | 47        | 11.03%  |
| Micron Technology   | 43        | 10.09%  |
| Unknown             | 26        | 6.1%    |
| Crucial             | 15        | 3.52%   |
| Elpida              | 10        | 2.35%   |
| Corsair             | 9         | 2.11%   |
| Ramaxel Technology  | 8         | 1.88%   |
| A-DATA Technology   | 8         | 1.88%   |
| Nanya Technology    | 3         | 0.7%    |
| Unknown (08AE)      | 1         | 0.23%   |
| OnBoard             | 1         | 0.23%   |
| G.Skill             | 1         | 0.23%   |
| ASint Technology    | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 10        | 2.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 10        | 2.2%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 10        | 2.2%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 9         | 1.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 7         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 6         | 1.32%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 6         | 1.32%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 5         | 1.1%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 5         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.1%    |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                    | 4         | 0.88%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.88%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.88%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 4         | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.88%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.88%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.88%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 4         | 0.88%   |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 3         | 0.66%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 3         | 0.66%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 3         | 0.66%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s            | 3         | 0.66%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.66%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s               | 3         | 0.66%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 3         | 0.66%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16384MB SODIMM DDR4 3200MT/s           | 3         | 0.66%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 3         | 0.66%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s              | 3         | 0.66%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s                      | 2         | 0.44%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.44%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                | 2         | 0.44%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.44%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s           | 2         | 0.44%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 2         | 0.44%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                         | 2         | 0.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 2         | 0.44%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 2         | 0.44%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 2         | 0.44%   |
| Samsung RAM Module 2048MB SODIMM LPDDR4 2400MT/s                    | 2         | 0.44%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 2         | 0.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| Samsung RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 2         | 0.44%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 2         | 0.44%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 164       | 45.43%  |
| DDR3    | 135       | 37.4%   |
| LPDDR3  | 28        | 7.76%   |
| LPDDR4  | 15        | 4.16%   |
| DDR2    | 10        | 2.77%   |
| SDRAM   | 5         | 1.39%   |
| DDR     | 3         | 0.83%   |
| Unknown | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 316       | 87.53%  |
| Row Of Chips | 35        | 9.7%    |
| Chip         | 7         | 1.94%   |
| Unknown      | 2         | 0.55%   |
| DIMM         | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 162       | 40.91%  |
| 4096  | 104       | 26.26%  |
| 16384 | 74        | 18.69%  |
| 2048  | 35        | 8.84%   |
| 1024  | 11        | 2.78%   |
| 32768 | 9         | 2.27%   |
| 512   | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 89        | 23%     |
| 2667    | 87        | 22.48%  |
| 3200    | 52        | 13.44%  |
| 2133    | 38        | 9.82%   |
| 2400    | 30        | 7.75%   |
| 1334    | 24        | 6.2%    |
| 1333    | 18        | 4.65%   |
| 1067    | 7         | 1.81%   |
| 4267    | 6         | 1.55%   |
| Unknown | 6         | 1.55%   |
| 3266    | 5         | 1.29%   |
| 667     | 4         | 1.03%   |
| 2048    | 3         | 0.78%   |
| 1867    | 3         | 0.78%   |
| 800     | 3         | 0.78%   |
| 4266    | 2         | 0.52%   |
| 3733    | 2         | 0.52%   |
| 975     | 2         | 0.52%   |
| 4199    | 1         | 0.26%   |
| 3000    | 1         | 0.26%   |
| 1639    | 1         | 0.26%   |
| 1066    | 1         | 0.26%   |
| 333     | 1         | 0.26%   |
| 266     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 44.44%  |
| Samsung Electronics | 1         | 11.11%  |
| Prolific Technology | 1         | 11.11%  |
| Konica Minolta      | 1         | 11.11%  |
| Hewlett-Packard     | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series | 1         | 11.11%  |
| Prolific PL2305 Parallel Port  | 1         | 11.11%  |
| Konica Minolta Printer         | 1         | 11.11%  |
| HP Laserjet P1505              | 1         | 11.11%  |
| Canon PIXMA TS6250             | 1         | 11.11%  |
| Brother MFC Composite Device   | 1         | 11.11%  |
| Brother HL-3040CN series       | 1         | 11.11%  |
| Brother HL-2030 Laser Printer  | 1         | 11.11%  |
| Brother DCP-7055W              | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Seiko Epson       | 1         | 50%     |
| Canon Electronics | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon P-150 Scanner                                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 186       | 30.95%  |
| Acer                                   | 48        | 7.99%   |
| IMC Networks                           | 46        | 7.65%   |
| Microdia                               | 43        | 7.15%   |
| Realtek Semiconductor                  | 41        | 6.82%   |
| Sunplus Innovation Technology          | 31        | 5.16%   |
| Quanta                                 | 29        | 4.83%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 4.33%   |
| Apple                                  | 25        | 4.16%   |
| Lite-On Technology                     | 22        | 3.66%   |
| Suyin                                  | 21        | 3.49%   |
| Lenovo                                 | 13        | 2.16%   |
| Logitech                               | 11        | 1.83%   |
| Syntek                                 | 10        | 1.66%   |
| Ricoh                                  | 8         | 1.33%   |
| Alcor Micro                            | 7         | 1.16%   |
| Silicon Motion                         | 5         | 0.83%   |
| Samsung Electronics                    | 4         | 0.67%   |
| Z-Star Microelectronics                | 3         | 0.5%    |
| Primax Electronics                     | 3         | 0.5%    |
| Luxvisions Innotech Limited            | 3         | 0.5%    |
| OmniVision Technologies                | 2         | 0.33%   |
| DigiTech                               | 2         | 0.33%   |
| ALi                                    | 2         | 0.33%   |
| Xiaomi                                 | 1         | 0.17%   |
| Pixart Imaging                         | 1         | 0.17%   |
| Novatek Microelectronics               | 1         | 0.17%   |
| Mimaki Engineering                     | 1         | 0.17%   |
| Leap Motion                            | 1         | 0.17%   |
| Importek                               | 1         | 0.17%   |
| Genesys Logic                          | 1         | 0.17%   |
| Generalplus Technology                 | 1         | 0.17%   |
| Foxconn / Hon Hai                      | 1         | 0.17%   |
| DJJHFA1BIF5CB0                         | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 39        | 6.4%    |
| Microdia Integrated_Webcam_HD                       | 27        | 4.43%   |
| Chicony HD Webcam                                   | 24        | 3.94%   |
| IMC Networks Integrated Camera                      | 19        | 3.12%   |
| Realtek Integrated_Webcam_HD                        | 16        | 2.63%   |
| Chicony HP HD Camera                                | 15        | 2.46%   |
| Acer Integrated Camera                              | 14        | 2.3%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 1.97%   |
| Lite-On Integrated Camera                           | 11        | 1.81%   |
| Sunplus HD WebCam                                   | 10        | 1.64%   |
| Chicony USB2.0 Camera                               | 10        | 1.64%   |
| Quanta HP HD Camera                                 | 9         | 1.48%   |
| Chicony HP Truevision HD                            | 9         | 1.48%   |
| Sunplus Integrated_Webcam_HD                        | 8         | 1.31%   |
| Microdia Integrated Webcam                          | 7         | 1.15%   |
| Apple FaceTime HD Camera                            | 7         | 1.15%   |
| Suyin HP Truevision HD                              | 6         | 0.99%   |
| Quanta HD Webcam                                    | 6         | 0.99%   |
| Lite-On HP HD Camera                                | 6         | 0.99%   |
| Lenovo Integrated Webcam                            | 6         | 0.99%   |
| Chicony Integrated Camera (1280x720@30)             | 6         | 0.99%   |
| Chicony HP HD Webcam                                | 6         | 0.99%   |
| Chicony CNF9055 Toshiba Webcam                      | 6         | 0.99%   |
| Apple Built-in iSight                               | 6         | 0.99%   |
| Syntek Lenovo EasyCamera                            | 5         | 0.82%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.82%   |
| Chicony HD User Facing                              | 5         | 0.82%   |
| Acer SunplusIT Integrated Camera                    | 5         | 0.82%   |
| Acer Lenovo EasyCamera                              | 5         | 0.82%   |
| Samsung Galaxy A5 (MTP)                             | 4         | 0.66%   |
| Realtek HP "Truevision HD" laptop camera            | 4         | 0.66%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.66%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 4         | 0.66%   |
| Chicony VGA Webcam                                  | 4         | 0.66%   |
| Chicony USB2.0 HD UVC WebCam                        | 4         | 0.66%   |
| Chicony TOSHIBA Web Camera - HD                     | 4         | 0.66%   |
| Chicony Lenovo EasyCamera                           | 4         | 0.66%   |
| Chicony FJ Camera                                   | 4         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE                           | 4         | 0.66%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 0.66%   |
| Acer ThinkPad Integrated Camera                     | 4         | 0.66%   |
| Acer BisonCam,NB Pro                                | 4         | 0.66%   |
| Syntek Integrated Camera                            | 3         | 0.49%   |
| Suyin USB2.0 RGBIR Camera                           | 3         | 0.49%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 0.49%   |
| Suyin 1.3M HD WebCam                                | 3         | 0.49%   |
| Sunplus HP TrueVision HD Camera                     | 3         | 0.49%   |
| Realtek USB Camera                                  | 3         | 0.49%   |
| Realtek Lenovo EasyCamera                           | 3         | 0.49%   |
| Realtek Integrated Webcam HD                        | 3         | 0.49%   |
| Realtek HP Truevision HD                            | 3         | 0.49%   |
| Quanta HP Webcam                                    | 3         | 0.49%   |
| Quanta HD User Facing                               | 3         | 0.49%   |
| Primax HP HD Webcam [Fixed]                         | 3         | 0.49%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 0.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 0.49%   |
| IMC Networks UVC VGA Webcam                         | 3         | 0.49%   |
| IMC Networks USB2.0 HD IR UVC WebCam                | 3         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 78        | 38.05%  |
| Synaptics                  | 66        | 32.2%   |
| Shenzhen Goodix Technology | 15        | 7.32%   |
| AuthenTec                  | 13        | 6.34%   |
| Upek                       | 12        | 5.85%   |
| Elan Microelectronics      | 11        | 5.37%   |
| LighTuning Technology      | 8         | 3.9%    |
| STMicroelectronics         | 2         | 0.98%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 28        | 13.66%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 9.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 5.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 5.85%   |
| Unknown                                                                    | 10        | 4.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 4.39%   |
| Elan ELAN:ARM-M4                                                           | 8         | 3.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 3.41%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 3.41%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 3.41%   |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 3.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 2.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.93%   |
| Validity Sensors VFS491                                                    | 5         | 2.44%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 2.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.44%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 2.44%   |
| AuthenTec AES2810                                                          | 5         | 2.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.46%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.46%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.46%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.46%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.98%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.98%   |
| Synaptics  WBDI                                                            | 2         | 0.98%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.98%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.49%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.49%   |
| Synaptics WBDI Device                                                      | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 28        | 38.89%  |
| Alcor Micro               | 28        | 38.89%  |
| Upek                      | 8         | 11.11%  |
| O2 Micro                  | 3         | 4.17%   |
| Lenovo                    | 2         | 2.78%   |
| Yubico.com                | 1         | 1.39%   |
| OmniKey                   | 1         | 1.39%   |
| Aladdin Knowledge Systems | 1         | 1.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 28        | 38.89%  |
| Broadcom 5880                                                                | 10        | 13.89%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 4.17%   |
| Broadcom 58200                                                               | 3         | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.78%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.39%   |
| OmniKey CardMan 4321                                                         | 1         | 1.39%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 335       | 49.85%  |
| 1     | 257       | 38.24%  |
| 2     | 67        | 9.97%   |
| 3     | 10        | 1.49%   |
| 4     | 2         | 0.3%    |
| 7     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 202       | 47.53%  |
| Chipcard                 | 66        | 15.53%  |
| Graphics card            | 52        | 12.24%  |
| Net/wireless             | 32        | 7.53%   |
| Multimedia controller    | 14        | 3.29%   |
| Bluetooth                | 13        | 3.06%   |
| Communication controller | 8         | 1.88%   |
| Card reader              | 8         | 1.88%   |
| Camera                   | 8         | 1.88%   |
| Net/ethernet             | 6         | 1.41%   |
| Storage                  | 4         | 0.94%   |
| Modem                    | 4         | 0.94%   |
| Sound                    | 2         | 0.47%   |
| Network                  | 2         | 0.47%   |
| Unassigned class         | 1         | 0.24%   |
| Storage/nvme             | 1         | 0.24%   |
| Flash memory             | 1         | 0.24%   |
| Dvb card                 | 1         | 0.24%   |


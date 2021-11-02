Ubuntu Budgie 20.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-budgie-20.04

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO   | Book XP15 / XP17 Gen12      | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Acer     | Aspire 4752                 | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| TUXEDO   | InfinityBook S 15 Gen6      | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek  | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| HP       | ZBook Studio G3             | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP       | x360 310 G2 PC              | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Dell     | XPS 15 9560                 | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO   | InfinityBook S 15 Gen6      | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| TUXEDO   | Book XP1511                 | [7526222677](https://linux-hardware.org/?probe=7526222677) | Aug 15, 2021 |
| TUXEDO   | Book XP1511                 | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Lenovo   | ThinkPad E490 20N8S07A00    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| TUXEDO   | TUXEDO_Book_XA1510          | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO   | P95_HR                      | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| Fujitsu  | LIFEBOOK E756               | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| TUXEDO   | InfinityBook Pro 14 Gen6    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Fujitsu  | LIFEBOOK E756               | [1c72549a32](https://linux-hardware.org/?probe=1c72549a32) | Jun 29, 2021 |
| HP       | Notebook                    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| Acer     | TravelMate P446-M           | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| Toshiba  | Satellite P300              | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| Toshiba  | Satellite P300              | [a53633e2b1](https://linux-hardware.org/?probe=a53633e2b1) | Jun 09, 2021 |
| Toshiba  | Satellite P300              | [3984b7401d](https://linux-hardware.org/?probe=3984b7401d) | Jun 02, 2021 |
| Acer     | Aspire A515-44              | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer     | Aspire A515-44              | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| Dell     | Latitude E6410              | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell     | Latitude E6410              | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba  | Satellite P300              | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO   | Unknown                     | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek  | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer     | Aspire A515-51G             | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| ASUSTek  | N53SM                       | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| HP       | EliteBook 850 G1            | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba  | Satellite P300              | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| Dell     | XPS 15 9500                 | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell     | XPS 15 9500                 | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| HP       | Pavilion g6                 | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| TUXEDO   | Polaris 17 AMD Gen1         | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| Sony     | SVS13A25PBS                 | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| MSI      | CX62 6QL                    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI      | CX62 6QL                    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| TUXEDO   | Aura 15 Gen1                | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| HP       | ProBook 640 G2              | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo   | ThinkPad P43s 20RHS00100    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo   | ThinkPad P43s 20RHS00100    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO   | InfinityBook S 14 Gen6      | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO   | InfinityBook S 14 Gen6      | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Fujitsu  | LIFEBOOK E756               | [2e450a6687](https://linux-hardware.org/?probe=2e450a6687) | Mar 06, 2021 |
| HP       | ENVY 15                     | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| TUXEDO   | Polaris 15 AMD Gen1         | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell     | Latitude 5590               | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell     | Latitude 7490               | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Lenovo   | ThinkPad P1 20MES01400      | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| HP       | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell     | Latitude 5580               | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| ASUSTek  | X551CA                      | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek  | N53SM                       | [e4689416a8](https://linux-hardware.org/?probe=e4689416a8) | Feb 02, 2021 |
| HP       | Laptop 15-da0xxx            | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI      | GP73 Leopard 8RE            | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| ASUSTek  | N53SM                       | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| MSI      | GE70 2PC\2PE                | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Acer     | TravelMate P446-M           | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer     | TravelMate P446-M           | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer     | Aspire V3-771               | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer     | Aspire V3-771               | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| Acer     | TravelMate P446-M           | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| TUXEDO   | Aura 15 Gen1                | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| ASUSTek  | F9E                         | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP       | EliteBook 850 G1            | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek  | ZenBook UX425EA_UX425EA     | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP       | Pavilion Gaming Laptop 1... | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu  | LIFEBOOK E756               | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| Acer     | Aspire E1-532               | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| HP       | Laptop 17-ak0xx             | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| HP       | Laptop 17-ak0xx             | [e51b8a2e3d](https://linux-hardware.org/?probe=e51b8a2e3d) | Nov 14, 2020 |
| HP       | Laptop 17-ak0xx             | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Fujitsu  | LIFEBOOK E756               | [3d1548beea](https://linux-hardware.org/?probe=3d1548beea) | Nov 06, 2020 |
| Sony     | SVS13A25PBS                 | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO   | Unknown                     | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Fujitsu  | LIFEBOOK E756               | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Dell     | Latitude E6540              | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| HP       | Elite x2 1012 G1            | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP       | Elite x2 1012 G1            | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| Dell     | Latitude 5400               | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell     | Latitude 5400               | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP       | Laptop 14-dk0xxx            | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo   | ThinkPad P43s 20RH0013US    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo   | 20SL                        | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple    | MacBookPro8,1               | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO   | P7xxTM1                     | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| MSI      | Modern 14 A10RB             | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| Samsung  | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek  | UX430UQ                     | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| Dell     | Latitude 5400               | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| HP       | ProBook 4730s               | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell     | Inspiron 7560               | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Fujitsu  | LIFEBOOK A512               | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| HP       | Pavilion g6                 | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell     | G7 7588                     | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Dell     | Inspiron 11-3168            | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell     | Inspiron 11-3168            | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| MSI      | Prestige 15 A10SC           | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell     | Inspiron 11-3168            | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell     | Inspiron 11-3168            | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| Standard | MT40II                      | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo   | ThinkPad T430s 23539WU      | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung  | 340XAA/350XAA/550XAA        | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| Samsung  | 340XAA/350XAA/550XAA        | [89e1df883c](https://linux-hardware.org/?probe=89e1df883c) | Aug 01, 2020 |
| Samsung  | 340XAA/350XAA/550XAA        | [545f6ed65f](https://linux-hardware.org/?probe=545f6ed65f) | Jul 31, 2020 |
| Apple    | MacBook3,1                  | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| HUAWEI   | MACH-WX9                    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| Samsung  | 340XAA/350XAA/550XAA        | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung  | 300E5EV/300E4EV/270E5EV/... | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| Samsung  | 530U3C/530U4C/532U3C        | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP       | Pavilion 14                 | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP       | Pavilion dv6                | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP       | EliteBook 2560p             | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell     | Latitude E6320              | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| Dell     | G3 3579                     | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell     | G7 7588                     | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell     | Inspiron 5437               | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo   | IdeaPad S145-15IWL 81S9     | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer     | Aspire A315-41              | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek  | K53E                        | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI      | GL62M 7RD                   | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| MSI      | GP72 7RE                    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| ASUSTek  | X510UAR                     | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP       | EliteBook 840 G6            | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell     | Inspiron 3537               | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell     | Inspiron 3537               | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP       | Pavilion Laptop 15-cw1xx... | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo   | IdeaPad 320-15IKB 80XL      | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell     | XPS L401X                   | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP       | Pavilion Laptop 15-cw1xx... | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| Dell     | Latitude E6220              | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| HP       | Laptop 15-dw0xxx            | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| Acer     | Aspire R3-131T              | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer     | Aspire R3-131T              | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO   | InfinityBook Pro 15 v4      | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP       | ENVY 17                     | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell     | Inspiron 7590               | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony     | VPCCW25FL                   | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP       | ENVY 17                     | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| Acer     | Aspire V3-572G              | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek  | X540LA                      | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP       | ENVY 17                     | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP       | ENVY 17                     | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo   | ThinkPad X230 23257G6       | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Lenovo   | ThinkPad X230 23257G6       | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI   | MACH-WX9                    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo   | IdeaPad 5 15ARE05 81YQ      | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| ASUSTek  | VivoBook_ASUSLaptop X571... | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP       | ENVY 17                     | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP       | ENVY 17                     | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo   | ThinkPad X260 20F5S2HF06    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| Lenovo   | ThinkPad T430 2349P74       | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek  | S400CA                      | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek  | X510UNR                     | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek  | X510UNR                     | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer     | Aspire F5-573G              | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| Dell     | Latitude 5400               | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Lenovo   | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo   | G550 2958                   | [e4d76f72dc](https://linux-hardware.org/?probe=e4d76f72dc) | May 11, 2020 |
| Lenovo   | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| ASUSTek  | S551LN                      | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek  | S551LN                      | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta   | QL3 TBD                     | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte | GB-BKi7A-7500               | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP       | EliteBook 840 G5            | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek  | G55VW                       | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP       | EliteBook 8560w             | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer     | Aspire F5-573G              | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| HP       | Notebook                    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| Lenovo   | ThinkPad W530 2447GW3       | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| Lenovo   | ThinkPad X230 2306CTO       | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| HUAWEI   | BOHK-WAX9X                  | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| Lenovo   | ThinkPad T410 2537H21       | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| Lenovo   | ThinkPad P53 20QQS1JE00     | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| HP       | Compaq 8460p USAO           | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.4.0-42-generic           | 16        | 12.03%  |
| 5.4.0-40-generic           | 9         | 6.77%   |
| 5.4.0-37-generic           | 6         | 4.51%   |
| 5.4.0-29-generic           | 6         | 4.51%   |
| 5.4.0-52-generic           | 5         | 3.76%   |
| 5.4.0-48-generic           | 5         | 3.76%   |
| 5.4.0-33-generic           | 5         | 3.76%   |
| 5.8.0-53-generic           | 4         | 3.01%   |
| 5.4.0-58-generic           | 4         | 3.01%   |
| 5.4.0-31-generic           | 4         | 3.01%   |
| 5.4.0-73-generic           | 3         | 2.26%   |
| 5.4.0-28-generic           | 3         | 2.26%   |
| 5.8.0-49-generic           | 2         | 1.5%    |
| 5.8.0-48-generic           | 2         | 1.5%    |
| 5.8.0-45-generic           | 2         | 1.5%    |
| 5.8.0-44-generic           | 2         | 1.5%    |
| 5.4.0-80-generic           | 2         | 1.5%    |
| 5.4.0-72-generic           | 2         | 1.5%    |
| 5.4.0-66-generic           | 2         | 1.5%    |
| 5.4.0-65-generic           | 2         | 1.5%    |
| 5.4.0-60-generic           | 2         | 1.5%    |
| 5.4.0-59-generic           | 2         | 1.5%    |
| 5.4.0-56-generic           | 2         | 1.5%    |
| 5.4.0-47-generic           | 2         | 1.5%    |
| 5.4.0-26-generic           | 2         | 1.5%    |
| 5.11.0-27-generic          | 2         | 1.5%    |
| 5.9.0-050900rc6-lowlatency | 1         | 0.75%   |
| 5.8.11-050811-generic      | 1         | 0.75%   |
| 5.8.0-63-generic           | 1         | 0.75%   |
| 5.8.0-59-generic           | 1         | 0.75%   |
| 5.8.0-50-generic           | 1         | 0.75%   |
| 5.8.0-43-generic           | 1         | 0.75%   |
| 5.8.0-41-generic           | 1         | 0.75%   |
| 5.6.7-050607-generic       | 1         | 0.75%   |
| 5.6.0-1048-oem             | 1         | 0.75%   |
| 5.6.0-1042-oem             | 1         | 0.75%   |
| 5.6.0-1034-oem             | 1         | 0.75%   |
| 5.5.0-2.1-liquorix-amd64   | 1         | 0.75%   |
| 5.4.0-89-generic           | 1         | 0.75%   |
| 5.4.0-77-generic           | 1         | 0.75%   |
| 5.4.0-74-generic           | 1         | 0.75%   |
| 5.4.0-62-generic           | 1         | 0.75%   |
| 5.4.0-61-generic           | 1         | 0.75%   |
| 5.4.0-55-generic           | 1         | 0.75%   |
| 5.4.0-54-generic           | 1         | 0.75%   |
| 5.4.0-51-generic           | 1         | 0.75%   |
| 5.4.0-48-lowlatency        | 1         | 0.75%   |
| 5.4.0-45-generic           | 1         | 0.75%   |
| 5.4.0-44-generic           | 1         | 0.75%   |
| 5.4.0-41-generic           | 1         | 0.75%   |
| 5.4.0-30-generic           | 1         | 0.75%   |
| 5.4.0-25-generic           | 1         | 0.75%   |
| 5.4.0-21-generic           | 1         | 0.75%   |
| 5.4.0-18-generic           | 1         | 0.75%   |
| 5.3.0-46-generic           | 1         | 0.75%   |
| 5.3.0-24-generic           | 1         | 0.75%   |
| 5.12.0-051200-generic      | 1         | 0.75%   |
| 5.11.0-37-generic          | 1         | 0.75%   |
| 5.11.0-36-generic          | 1         | 0.75%   |
| 5.11.0-25-generic          | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 89        | 72.95%  |
| 5.8.0   | 17        | 13.93%  |
| 5.11.0  | 5         | 4.1%    |
| 5.6.0   | 3         | 2.46%   |
| 5.3.0   | 2         | 1.64%   |
| 5.9.0   | 1         | 0.82%   |
| 5.8.11  | 1         | 0.82%   |
| 5.6.7   | 1         | 0.82%   |
| 5.5.0   | 1         | 0.82%   |
| 5.12.0  | 1         | 0.82%   |
| 5.10.11 | 1         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 89        | 72.95%  |
| 5.8     | 18        | 14.75%  |
| 5.11    | 5         | 4.1%    |
| 5.6     | 4         | 3.28%   |
| 5.3     | 2         | 1.64%   |
| 5.9     | 1         | 0.82%   |
| 5.5     | 1         | 0.82%   |
| 5.12    | 1         | 0.82%   |
| 5.10    | 1         | 0.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 120       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 117       | 97.5%   |
| GNOME  | 2         | 1.67%   |
| XFCE   | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 115       | 95.83%  |
| Wayland | 5         | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 55        | 45.83%  |
| TDM     | 33        | 27.5%   |
| GDM     | 18        | 15%     |
| LightDM | 14        | 11.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 35        | 28.93%  |
| pt_BR   | 13        | 10.74%  |
| de_DE   | 13        | 10.74%  |
| en_GB   | 9         | 7.44%   |
| fr_FR   | 8         | 6.61%   |
| en_CA   | 6         | 4.96%   |
| ru_RU   | 3         | 2.48%   |
| it_IT   | 3         | 2.48%   |
| es_ES   | 3         | 2.48%   |
| en_IN   | 3         | 2.48%   |
| pt_PT   | 2         | 1.65%   |
| fi_FI   | 2         | 1.65%   |
| es_AR   | 2         | 1.65%   |
| en_AU   | 2         | 1.65%   |
| de_CH   | 2         | 1.65%   |
| C       | 2         | 1.65%   |
| pl_PL   | 1         | 0.83%   |
| nb_NO   | 1         | 0.83%   |
| id_ID   | 1         | 0.83%   |
| hu_HU   | 1         | 0.83%   |
| fr_CH   | 1         | 0.83%   |
| es_US   | 1         | 0.83%   |
| es_SV   | 1         | 0.83%   |
| es_MX   | 1         | 0.83%   |
| es_GT   | 1         | 0.83%   |
| es_CL   | 1         | 0.83%   |
| en_SG   | 1         | 0.83%   |
| de_AT   | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 89        | 71.77%  |
| BIOS | 35        | 28.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 110       | 91.67%  |
| Zfs     | 5         | 4.17%   |
| Overlay | 2         | 1.67%   |
| Xfs     | 1         | 0.83%   |
| Jfs     | 1         | 0.83%   |
| Btrfs   | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 46.67%  |
| GPT     | 47        | 39.17%  |
| MBR     | 17        | 14.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 91.8%   |
| Yes       | 10        | 8.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 67.5%   |
| Yes       | 39        | 32.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 20%     |
| Dell                | 18        | 15%     |
| Lenovo              | 17        | 14.17%  |
| TUXEDO              | 14        | 11.67%  |
| ASUSTek Computer    | 14        | 11.67%  |
| Acer                | 11        | 9.17%   |
| MSI                 | 7         | 5.83%   |
| Samsung Electronics | 4         | 3.33%   |
| Sony                | 2         | 1.67%   |
| HUAWEI              | 2         | 1.67%   |
| Apple               | 2         | 1.67%   |
| Toshiba             | 1         | 0.83%   |
| Standard            | 1         | 0.83%   |
| Quanta              | 1         | 0.83%   |
| Gigabyte Technology | 1         | 0.83%   |
| Fujitsu             | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ZBook Studio G3                                    | 2         | 1.67%   |
| HP Pavilion g6                                        | 2         | 1.67%   |
| HP Notebook                                           | 2         | 1.67%   |
| Dell Latitude 5400                                    | 2         | 1.67%   |
| Acer TravelMate P446-M                                | 2         | 1.67%   |
| Unknown                                               | 2         | 1.67%   |
| TUXEDO TUXEDO_Book_XA1510                             | 1         | 0.83%   |
| TUXEDO Polaris 17 AMD Gen1                            | 1         | 0.83%   |
| TUXEDO Polaris 15 AMD Gen1                            | 1         | 0.83%   |
| TUXEDO P95_HR                                         | 1         | 0.83%   |
| TUXEDO P7xxTM1                                        | 1         | 0.83%   |
| TUXEDO InfinityBook S 15 Gen6                         | 1         | 0.83%   |
| TUXEDO InfinityBook S 14 Gen6                         | 1         | 0.83%   |
| TUXEDO InfinityBook Pro 15 v4                         | 1         | 0.83%   |
| TUXEDO InfinityBook Pro 14 Gen6                       | 1         | 0.83%   |
| TUXEDO Book XP1511                                    | 1         | 0.83%   |
| TUXEDO Book XP15 / XP17 Gen12                         | 1         | 0.83%   |
| TUXEDO Aura 15 Gen1                                   | 1         | 0.83%   |
| Toshiba Satellite P300                                | 1         | 0.83%   |
| Standard MT40II                                       | 1         | 0.83%   |
| Sony VPCCW25FL                                        | 1         | 0.83%   |
| Sony SVS13A25PBS                                      | 1         | 0.83%   |
| Samsung 905S3G/906S3G/915S3G/9305SG                   | 1         | 0.83%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.83%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.83%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.83%   |
| Quanta R460-L.BG22P1                                  | 1         | 0.83%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.83%   |
| MSI Modern 14 A10RB                                   | 1         | 0.83%   |
| MSI GP73 Leopard 8RE                                  | 1         | 0.83%   |
| MSI GP72 7RE                                          | 1         | 0.83%   |
| MSI GL62M 7RD                                         | 1         | 0.83%   |
| MSI GE70 2PC\2PE                                      | 1         | 0.83%   |
| MSI CX62 6QL                                          | 1         | 0.83%   |
| Lenovo ThinkPad X260 20F5S2HF06                       | 1         | 0.83%   |
| Lenovo ThinkPad X230 23257G6                          | 1         | 0.83%   |
| Lenovo ThinkPad X230 2306CTO                          | 1         | 0.83%   |
| Lenovo ThinkPad W530 2447GW3                          | 1         | 0.83%   |
| Lenovo ThinkPad T430s 23539WU                         | 1         | 0.83%   |
| Lenovo ThinkPad T430 2349P74                          | 1         | 0.83%   |
| Lenovo ThinkPad T410 2537H21                          | 1         | 0.83%   |
| Lenovo ThinkPad P53 20QQS1JE00                        | 1         | 0.83%   |
| Lenovo ThinkPad P43s 20RHS00100                       | 1         | 0.83%   |
| Lenovo ThinkPad P43s 20RH0013US                       | 1         | 0.83%   |
| Lenovo ThinkPad P1 20MES01400                         | 1         | 0.83%   |
| Lenovo ThinkPad E490 20N8S07A00                       | 1         | 0.83%   |
| Lenovo IdeaPad S145-15IWL 81S9                        | 1         | 0.83%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                         | 1         | 0.83%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.83%   |
| Lenovo G550 2958                                      | 1         | 0.83%   |
| Lenovo 20SL                                           | 1         | 0.83%   |
| HUAWEI MACH-WX9                                       | 1         | 0.83%   |
| HUAWEI BOHK-WAX9X                                     | 1         | 0.83%   |
| HP x360 310 G2 PC                                     | 1         | 0.83%   |
| HP ProBook 640 G2                                     | 1         | 0.83%   |
| HP ProBook 4730s                                      | 1         | 0.83%   |
| HP Pavilion Gaming Laptop 15-dk0xxx                   | 1         | 0.83%   |
| HP Pavilion dv6                                       | 1         | 0.83%   |
| HP Pavilion 14                                        | 1         | 0.83%   |
| HP Laptop 15-dw0xxx                                   | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 12        | 10%     |
| Dell Latitude          | 9         | 7.5%    |
| Acer Aspire            | 9         | 7.5%    |
| HP Pavilion            | 5         | 4.17%   |
| HP EliteBook           | 5         | 4.17%   |
| Dell Inspiron          | 5         | 4.17%   |
| TUXEDO InfinityBook    | 4         | 3.33%   |
| Lenovo IdeaPad         | 3         | 2.5%    |
| HP Laptop              | 3         | 2.5%    |
| TUXEDO Polaris         | 2         | 1.67%   |
| TUXEDO Book            | 2         | 1.67%   |
| HP ZBook               | 2         | 1.67%   |
| HP ProBook             | 2         | 1.67%   |
| HP Notebook            | 2         | 1.67%   |
| HP ENVY                | 2         | 1.67%   |
| Dell XPS               | 2         | 1.67%   |
| Acer TravelMate        | 2         | 1.67%   |
| Unknown                | 2         | 1.67%   |
| TUXEDO TUXEDO          | 1         | 0.83%   |
| TUXEDO P95             | 1         | 0.83%   |
| TUXEDO P7xxTM1         | 1         | 0.83%   |
| TUXEDO Aura            | 1         | 0.83%   |
| Toshiba Satellite      | 1         | 0.83%   |
| Standard MT40II        | 1         | 0.83%   |
| Sony VPCCW25FL         | 1         | 0.83%   |
| Sony SVS13A25PBS       | 1         | 0.83%   |
| Samsung 905S3G         | 1         | 0.83%   |
| Samsung 530U3C         | 1         | 0.83%   |
| Samsung 340XAA         | 1         | 0.83%   |
| Samsung 300E5EV        | 1         | 0.83%   |
| Quanta R460-L.BG22P1   | 1         | 0.83%   |
| MSI Prestige           | 1         | 0.83%   |
| MSI Modern             | 1         | 0.83%   |
| MSI GP73               | 1         | 0.83%   |
| MSI GP72               | 1         | 0.83%   |
| MSI GL62M              | 1         | 0.83%   |
| MSI GE70               | 1         | 0.83%   |
| MSI CX62               | 1         | 0.83%   |
| Lenovo G550            | 1         | 0.83%   |
| Lenovo 20SL            | 1         | 0.83%   |
| HUAWEI MACH-WX9        | 1         | 0.83%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.83%   |
| HP x360                | 1         | 0.83%   |
| HP Elite               | 1         | 0.83%   |
| HP Compaq              | 1         | 0.83%   |
| Gigabyte GB-BKi7A-7500 | 1         | 0.83%   |
| Fujitsu LIFEBOOK       | 1         | 0.83%   |
| Dell G7                | 1         | 0.83%   |
| Dell G3                | 1         | 0.83%   |
| ASUS ZenBook           | 1         | 0.83%   |
| ASUS X551CA            | 1         | 0.83%   |
| ASUS X540LA            | 1         | 0.83%   |
| ASUS X510UNR           | 1         | 0.83%   |
| ASUS X510UAR           | 1         | 0.83%   |
| ASUS X302LJ            | 1         | 0.83%   |
| ASUS VivoBook          | 1         | 0.83%   |
| ASUS UX430UQ           | 1         | 0.83%   |
| ASUS S400CA            | 1         | 0.83%   |
| ASUS N53SM             | 1         | 0.83%   |
| ASUS K53E              | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 25        | 20.83%  |
| 2020 | 24        | 20%     |
| 2018 | 17        | 14.17%  |
| 2013 | 10        | 8.33%   |
| 2017 | 8         | 6.67%   |
| 2014 | 7         | 5.83%   |
| 2012 | 7         | 5.83%   |
| 2015 | 6         | 5%      |
| 2016 | 5         | 4.17%   |
| 2011 | 3         | 2.5%    |
| 2010 | 3         | 2.5%    |
| 2008 | 3         | 2.5%    |
| 2021 | 1         | 0.83%   |
| 2009 | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 120       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 102       | 85%     |
| Enabled  | 18        | 15%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 120       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 35        | 28.69%  |
| 16.01-24.0  | 28        | 22.95%  |
| 8.01-16.0   | 23        | 18.85%  |
| 3.01-4.0    | 17        | 13.93%  |
| 32.01-64.0  | 12        | 9.84%   |
| 64.01-256.0 | 4         | 3.28%   |
| 2.01-3.0    | 2         | 1.64%   |
| 1.01-2.0    | 1         | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 39        | 30.23%  |
| 1.01-2.0  | 30        | 23.26%  |
| 3.01-4.0  | 26        | 20.16%  |
| 4.01-8.0  | 25        | 19.38%  |
| 8.01-16.0 | 9         | 6.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 71.67%  |
| 2      | 31        | 25.83%  |
| 3      | 3         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 66.94%  |
| Yes       | 40        | 33.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 88.33%  |
| No        | 14        | 11.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 82.5%   |
| No        | 21        | 17.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 17        | 14.17%  |
| Brazil             | 15        | 12.5%   |
| USA                | 11        | 9.17%   |
| France             | 7         | 5.83%   |
| Russia             | 5         | 4.17%   |
| Italy              | 5         | 4.17%   |
| UK                 | 4         | 3.33%   |
| Spain              | 4         | 3.33%   |
| Poland             | 4         | 3.33%   |
| Canada             | 4         | 3.33%   |
| Iran               | 3         | 2.5%    |
| India              | 3         | 2.5%    |
| Finland            | 3         | 2.5%    |
| Ukraine            | 2         | 1.67%   |
| Turkey             | 2         | 1.67%   |
| Switzerland        | 2         | 1.67%   |
| South Africa       | 2         | 1.67%   |
| Portugal           | 2         | 1.67%   |
| Norway             | 2         | 1.67%   |
| Netherlands        | 2         | 1.67%   |
| Indonesia          | 2         | 1.67%   |
| Austria            | 2         | 1.67%   |
| Australia          | 2         | 1.67%   |
| Argentina          | 2         | 1.67%   |
| Slovenia           | 1         | 0.83%   |
| Singapore          | 1         | 0.83%   |
| Mexico             | 1         | 0.83%   |
| Malaysia           | 1         | 0.83%   |
| Kenya              | 1         | 0.83%   |
| Japan              | 1         | 0.83%   |
| Hungary            | 1         | 0.83%   |
| Honduras           | 1         | 0.83%   |
| Guatemala          | 1         | 0.83%   |
| El Salvador        | 1         | 0.83%   |
| Ecuador            | 1         | 0.83%   |
| Dominican Republic | 1         | 0.83%   |
| Chile              | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Tehran                    | 3         | 2.42%   |
| São Paulo                | 3         | 2.42%   |
| Stuttgart                 | 3         | 2.42%   |
| Paris                     | 3         | 2.42%   |
| Moscow                    | 2         | 1.61%   |
| Montreal                  | 2         | 1.61%   |
| Los Angeles               | 2         | 1.61%   |
| Kyiv                      | 2         | 1.61%   |
| Brasília                 | 2         | 1.61%   |
| Belo Horizonte            | 2         | 1.61%   |
| Zheleznodorozhnyy         | 1         | 0.81%   |
| Zabrze                    | 1         | 0.81%   |
| Yuma                      | 1         | 0.81%   |
| Woking                    | 1         | 0.81%   |
| Wilchingen, Osterfingen   | 1         | 0.81%   |
| Waterloo                  | 1         | 0.81%   |
| Warsaw                    | 1         | 0.81%   |
| Vienna                    | 1         | 0.81%   |
| Vicente Lopez             | 1         | 0.81%   |
| Vantaa                    | 1         | 0.81%   |
| Tuttlingen                | 1         | 0.81%   |
| Tuscola                   | 1         | 0.81%   |
| Turku                     | 1         | 0.81%   |
| Totana                    | 1         | 0.81%   |
| Tokyo                     | 1         | 0.81%   |
| Tiel                      | 1         | 0.81%   |
| Teresina                  | 1         | 0.81%   |
| Tangerang                 | 1         | 0.81%   |
| São Luís                | 1         | 0.81%   |
| São José dos Campos     | 1         | 0.81%   |
| Sydney                    | 1         | 0.81%   |
| St Petersburg             | 1         | 0.81%   |
| Spilimbergo               | 1         | 0.81%   |
| Skien                     | 1         | 0.81%   |
| Singapore                 | 1         | 0.81%   |
| Sens                      | 1         | 0.81%   |
| Santo Domingo Este        | 1         | 0.81%   |
| Santarém                 | 1         | 0.81%   |
| Santa Tecla               | 1         | 0.81%   |
| San Pedro Sula            | 1         | 0.81%   |
| Salt Lake City            | 1         | 0.81%   |
| Salamanca                 | 1         | 0.81%   |
| Saint-Medard-de-Guizieres | 1         | 0.81%   |
| Saint-Junien              | 1         | 0.81%   |
| Rostov-on-Don             | 1         | 0.81%   |
| Quito                     | 1         | 0.81%   |
| Povoa de Lanhoso          | 1         | 0.81%   |
| Ponte San Pietro          | 1         | 0.81%   |
| Penzberg                  | 1         | 0.81%   |
| Parma                     | 1         | 0.81%   |
| Ovalle                    | 1         | 0.81%   |
| Oswestry                  | 1         | 0.81%   |
| Oslo                      | 1         | 0.81%   |
| Osasco                    | 1         | 0.81%   |
| Niterói                  | 1         | 0.81%   |
| Nieuwegein                | 1         | 0.81%   |
| Neu-Ulm                   | 1         | 0.81%   |
| Neenah                    | 1         | 0.81%   |
| Nairobi                   | 1         | 0.81%   |
| Munich                    | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Samsung Electronics | 35        | 46      | 23.18%  |
| Toshiba             | 18        | 20      | 11.92%  |
| Seagate             | 18        | 20      | 11.92%  |
| WDC                 | 15        | 17      | 9.93%   |
| SanDisk             | 11        | 12      | 7.28%   |
| Crucial             | 7         | 7       | 4.64%   |
| Unknown             | 6         | 7       | 3.97%   |
| HGST                | 6         | 9       | 3.97%   |
| SK Hynix            | 5         | 5       | 3.31%   |
| Kingston            | 5         | 5       | 3.31%   |
| Intel               | 5         | 6       | 3.31%   |
| Hitachi             | 4         | 4       | 2.65%   |
| A-DATA Technology   | 4         | 5       | 2.65%   |
| Micron Technology   | 3         | 5       | 1.99%   |
| PNY                 | 2         | 3       | 1.32%   |
| Vaseky              | 1         | 1       | 0.66%   |
| LITEON              | 1         | 1       | 0.66%   |
| KingSpec            | 1         | 1       | 0.66%   |
| KimMiDi             | 1         | 1       | 0.66%   |
| Hewlett-Packard     | 1         | Unknown | 0.66%   |
| Corsair             | 1         | 1       | 0.66%   |
| China               | 1         | 1       | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 4         | 2.55%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.91%   |
| Unknown MMC Card  32GB                  | 2         | 1.27%   |
| SK Hynix NVMe SSD Drive 256GB           | 2         | 1.27%   |
| Seagate ST9500325AS 500GB               | 2         | 1.27%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 1.27%   |
| Seagate BUP Slim BK 2TB                 | 2         | 1.27%   |
| SanDisk SSD PLUS 120GB                  | 2         | 1.27%   |
| Sandisk NVMe SSD Drive 512GB            | 2         | 1.27%   |
| Samsung SSD 980 PRO 1TB                 | 2         | 1.27%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 1.27%   |
| Samsung SSD 970 EVO 500GB               | 2         | 1.27%   |
| Samsung SSD 860 EVO M.2 250GB           | 2         | 1.27%   |
| Samsung SSD 750 EVO 250GB               | 2         | 1.27%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB  | 2         | 1.27%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 1.27%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.27%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 1.27%   |
| HGST HTS725050A7E630 500GB              | 2         | 1.27%   |
| Crucial CT250MX500SSD1 250GB            | 2         | 1.27%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.64%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD        | 1         | 0.64%   |
| WDC WDS100T2B0A 1TB SSD                 | 1         | 0.64%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.64%   |
| WDC WD1600BEVS-08VAT2 160GB             | 1         | 0.64%   |
| WDC WD10SPZX-75Z10T2 1TB                | 1         | 0.64%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.64%   |
| WDC WD10SPZX-35Z10T0 1TB                | 1         | 0.64%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.64%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.64%   |
| WDC WD10SPZX-17Z10T0 1TB                | 1         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.64%   |
| WDC PC SN720 SDAQNTW-256G-1001 256GB    | 1         | 0.64%   |
| WDC PC SN520 NVMe 512GB                 | 1         | 0.64%   |
| Vaseky V800/120G 120GB                  | 1         | 0.64%   |
| Unknown SD64G  64GB                     | 1         | 0.64%   |
| Unknown NVMe SSD Drive 512GB            | 1         | 0.64%   |
| Unknown MMC Card  64GB                  | 1         | 0.64%   |
| Unknown MMC Card  16GB                  | 1         | 0.64%   |
| Unknown 00000  2GB                      | 1         | 0.64%   |
| Toshiba THNSNJ512G8NY 512GB SSD         | 1         | 0.64%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.64%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.64%   |
| Toshiba MQ01ACF050 500GB                | 1         | 0.64%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.64%   |
| Toshiba MQ01ABF032 320GB                | 1         | 0.64%   |
| Toshiba MK7559GSXF 752GB                | 1         | 0.64%   |
| Toshiba MK6461GSYN 640GB                | 1         | 0.64%   |
| Toshiba MK2561GSYN 250GB                | 1         | 0.64%   |
| Toshiba MK2552GSX 250GB                 | 1         | 0.64%   |
| Toshiba KXG60ZNV256G NVMe 256GB         | 1         | 0.64%   |
| Toshiba KXG5AZNV512G 512GB              | 1         | 0.64%   |
| Toshiba KBG30ZMT512G 512GB              | 1         | 0.64%   |
| Toshiba HDWJ110 999GB                   | 1         | 0.64%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 1         | 0.64%   |
| SK Hynix HFM512GDJTNI-82A0A 512GB       | 1         | 0.64%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 0.64%   |
| Seagate ST9750420AS 752GB               | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 19     | 34.69%  |
| Toshiba | 13        | 15     | 26.53%  |
| WDC     | 9         | 10     | 18.37%  |
| HGST    | 6         | 9      | 12.24%  |
| Hitachi | 4         | 4      | 8.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 22     | 31.48%  |
| SanDisk             | 8         | 8      | 14.81%  |
| Crucial             | 6         | 6      | 11.11%  |
| Kingston            | 5         | 5      | 9.26%   |
| WDC                 | 4         | 5      | 7.41%   |
| A-DATA Technology   | 3         | 4      | 5.56%   |
| PNY                 | 2         | 3      | 3.7%    |
| Micron Technology   | 2         | 4      | 3.7%    |
| Vaseky              | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| SK Hynix            | 1         | 1      | 1.85%   |
| LITEON              | 1         | 1      | 1.85%   |
| KingSpec            | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| China               | 1         | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 51        | 64     | 35.17%  |
| HDD     | 46        | 57     | 31.72%  |
| NVMe    | 40        | 48     | 27.59%  |
| MMC     | 5         | 6      | 3.45%   |
| Unknown | 3         | 2      | 2.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 83        | 119    | 62.41%  |
| NVMe | 40        | 48     | 30.08%  |
| SAS  | 5         | 4      | 3.76%   |
| MMC  | 5         | 6      | 3.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 70     | 59.38%  |
| 0.51-1.0   | 35        | 46     | 36.46%  |
| 1.01-2.0   | 4         | 5      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 34.15%  |
| 251-500        | 31        | 25.2%   |
| 501-1000       | 21        | 17.07%  |
| 51-100         | 8         | 6.5%    |
| 1001-2000      | 7         | 5.69%   |
| 21-50          | 6         | 4.88%   |
| Unknown        | 3         | 2.44%   |
| 2001-3000      | 2         | 1.63%   |
| 1-20           | 2         | 1.63%   |
| More than 3000 | 1         | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 31        | 25.41%  |
| 101-250   | 28        | 22.95%  |
| 21-50     | 25        | 20.49%  |
| 51-100    | 20        | 16.39%  |
| 251-500   | 10        | 8.2%    |
| 501-1000  | 4         | 3.28%   |
| Unknown   | 3         | 2.46%   |
| 1001-2000 | 1         | 0.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 20%     |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 10%     |
| Toshiba MK2561GSYN 250GB            | 1         | 1      | 10%     |
| Seagate ST9750420AS 752GB           | 1         | 1      | 10%     |
| Seagate ST9500325AS 500GB           | 1         | 1      | 10%     |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 10%     |
| PNY SSD2SC120G3LC709B121-460I 120GB | 1         | 1      | 10%     |
| HGST HTS725032A7E630 320GB          | 1         | 2      | 10%     |
| Crucial CT500P1SSD8 500GB           | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 40%     |
| Seagate | 3         | 3      | 30%     |
| PNY     | 1         | 1      | 10%     |
| HGST    | 1         | 2      | 10%     |
| Crucial | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 50%     |
| Seagate | 3         | 3      | 37.5%   |
| HGST    | 1         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 80%     |
| NVMe | 1         | 1      | 10%     |
| SSD  | 1         | 1      | 10%     |

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
| Detected | 60        | 89     | 46.51%  |
| Works    | 59        | 77     | 45.74%  |
| Malfunc  | 10        | 11     | 7.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 94        | 67.14%  |
| Samsung Electronics          | 21        | 15%     |
| AMD                          | 7         | 5%      |
| Sandisk                      | 5         | 3.57%   |
| Toshiba America Info Systems | 4         | 2.86%   |
| SK Hynix                     | 4         | 2.86%   |
| Realtek Semiconductor        | 1         | 0.71%   |
| Phison Electronics           | 1         | 0.71%   |
| Micron/Crucial Technology    | 1         | 0.71%   |
| Micron Technology            | 1         | 0.71%   |
| ADATA Technology             | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 17        | 11.64%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 10.27%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 9.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 7.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 4.79%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 4.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 4.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 3.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.05%   |
| Intel SSD 660P Series                                                            | 3         | 2.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 2.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.05%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 1.37%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 1.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.37%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.37%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.68%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.68%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.68%   |
| SK Hynix BC511                                                                   | 1         | 0.68%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.68%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.68%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.68%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.68%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.68%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.68%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.68%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 0.68%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.68%   |
| ADATA Non-Volatile memory controller                                             | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 91        | 64.08%  |
| NVMe | 41        | 28.87%  |
| RAID | 7         | 4.93%   |
| IDE  | 3         | 2.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 108       | 90%     |
| AMD    | 12        | 10%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 4.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 3.33%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 3.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 3.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.5%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 2.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 2.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 2.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.67%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.67%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.67%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.67%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.67%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.67%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.83%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.83%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.83%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.83%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.83%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.83%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 0.83%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.83%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.83%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.83%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.83%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.83%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.83%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.83%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.83%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.83%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.83%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.83%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.83%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.83%   |
| Intel Core i7-3517U CPU @ 1.90GHz             | 1         | 0.83%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 0.83%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.83%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.83%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.83%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.83%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.83%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.83%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.83%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.83%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.83%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.83%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.83%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 55        | 45.83%  |
| Intel Core i5           | 30        | 25%     |
| Intel Core i3           | 8         | 6.67%   |
| AMD Ryzen 5             | 5         | 4.17%   |
| Other                   | 4         | 3.33%   |
| Intel Core 2 Duo        | 4         | 3.33%   |
| Intel Pentium           | 3         | 2.5%    |
| AMD Ryzen 7             | 3         | 2.5%    |
| Intel Celeron           | 2         | 1.67%   |
| Intel Pentium Dual-Core | 1         | 0.83%   |
| Intel Core m5           | 1         | 0.83%   |
| AMD Ryzen 9             | 1         | 0.83%   |
| AMD Quad-Core           | 1         | 0.83%   |
| AMD A8                  | 1         | 0.83%   |
| AMD A6                  | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 44.17%  |
| 4      | 50        | 41.67%  |
| 6      | 12        | 10%     |
| 8      | 4         | 3.33%   |
| 16     | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 120       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 102       | 85%     |
| 1      | 18        | 15%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 120       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 14        | 11.2%   |
| Unknown    | 12        | 9.6%    |
| 0x306a9    | 11        | 8.8%    |
| 0x906ea    | 9         | 7.2%    |
| 0x806ec    | 8         | 6.4%    |
| 0x40651    | 7         | 5.6%    |
| 0x806ea    | 6         | 4.8%    |
| 0x806e9    | 5         | 4%      |
| 0x406e3    | 5         | 4%      |
| 0x806c1    | 4         | 3.2%    |
| 0x306c3    | 4         | 3.2%    |
| 0xa0652    | 3         | 2.4%    |
| 0x906e9    | 3         | 2.4%    |
| 0x406c3    | 3         | 2.4%    |
| 0x306d4    | 3         | 2.4%    |
| 0x08600103 | 3         | 2.4%    |
| 0x806eb    | 2         | 1.6%    |
| 0x506e3    | 2         | 1.6%    |
| 0x20655    | 2         | 1.6%    |
| 0x20652    | 2         | 1.6%    |
| 0x1067a    | 2         | 1.6%    |
| 0x10676    | 2         | 1.6%    |
| 0x08108109 | 2         | 1.6%    |
| 0xa0660    | 1         | 0.8%    |
| 0x706e5    | 1         | 0.8%    |
| 0x6fb      | 1         | 0.8%    |
| 0x406c4    | 1         | 0.8%    |
| 0x08701013 | 1         | 0.8%    |
| 0x08600106 | 1         | 0.8%    |
| 0x08600102 | 1         | 0.8%    |
| 0x0810100b | 1         | 0.8%    |
| 0x07030105 | 1         | 0.8%    |
| 0x0700010f | 1         | 0.8%    |
| 0x06001119 | 1         | 0.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 39        | 32.5%   |
| SandyBridge | 14        | 11.67%  |
| IvyBridge   | 12        | 10%     |
| Haswell     | 11        | 9.17%   |
| Skylake     | 7         | 5.83%   |
| Zen 2       | 6         | 5%      |
| Westmere    | 4         | 3.33%   |
| TigerLake   | 4         | 3.33%   |
| Silvermont  | 4         | 3.33%   |
| Penryn      | 4         | 3.33%   |
| CometLake   | 4         | 3.33%   |
| Broadwell   | 3         | 2.5%    |
| Zen+        | 2         | 1.67%   |
| Zen         | 1         | 0.83%   |
| Puma        | 1         | 0.83%   |
| Piledriver  | 1         | 0.83%   |
| Jaguar      | 1         | 0.83%   |
| IceLake     | 1         | 0.83%   |
| Core        | 1         | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 102       | 61.08%  |
| Nvidia | 45        | 26.95%  |
| AMD    | 20        | 11.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 7.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 6.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 5.88%   |
| Intel UHD Graphics 620                                                                   | 7         | 4.12%   |
| Intel HD Graphics 620                                                                    | 7         | 4.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 4.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 4.12%   |
| AMD Renoir                                                                               | 5         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.35%   |
| Intel HD Graphics 630                                                                    | 4         | 2.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.76%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.76%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.76%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.76%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 1.18%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.18%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.18%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.18%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.18%   |
| Intel HD Graphics 530                                                                    | 2         | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.18%   |
| AMD Picasso                                                                              | 2         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.59%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.59%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.59%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.59%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.59%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.59%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.59%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.59%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.59%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.59%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.59%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.59%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.59%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.59%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.59%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.59%   |
| Nvidia GK107M [GeForce GT 640M LE]                                                       | 1         | 0.59%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.59%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.59%   |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 0.59%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.59%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.59%   |
| Intel HD Graphics 515                                                                    | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 47.5%   |
| Intel + Nvidia | 37        | 30.83%  |
| 1 x AMD        | 9         | 7.5%    |
| Intel + AMD    | 8         | 6.67%   |
| 1 x Nvidia     | 6         | 5%      |
| AMD + Nvidia   | 2         | 1.67%   |
| 2 x AMD        | 1         | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 84        | 70%     |
| Proprietary | 33        | 27.5%   |
| Unknown     | 3         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 60%     |
| 1.01-2.0   | 19        | 15.83%  |
| 3.01-4.0   | 8         | 6.67%   |
| 0.51-1.0   | 7         | 5.83%   |
| 0.01-0.5   | 6         | 5%      |
| 5.01-6.0   | 4         | 3.33%   |
| 7.01-8.0   | 3         | 2.5%    |
| 2.01-3.0   | 1         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 27        | 18%     |
| Chimei Innolux          | 25        | 16.67%  |
| AU Optronics            | 22        | 14.67%  |
| Samsung Electronics     | 15        | 10%     |
| BOE                     | 10        | 6.67%   |
| Dell                    | 8         | 5.33%   |
| Hewlett-Packard         | 5         | 3.33%   |
| Chi Mei Optoelectronics | 5         | 3.33%   |
| Goldstar                | 4         | 2.67%   |
| Acer                    | 3         | 2%      |
| Sharp                   | 2         | 1.33%   |
| Philips                 | 2         | 1.33%   |
| PANDA                   | 2         | 1.33%   |
| LGD                     | 2         | 1.33%   |
| InfoVision              | 2         | 1.33%   |
| BenQ                    | 2         | 1.33%   |
| Apple                   | 2         | 1.33%   |
| Ancor Communications    | 2         | 1.33%   |
| UPD                     | 1         | 0.67%   |
| Unknown                 | 1         | 0.67%   |
| Lenovo                  | 1         | 0.67%   |
| KTC                     | 1         | 0.67%   |
| JDI                     | 1         | 0.67%   |
| InnoLux Display         | 1         | 0.67%   |
| Fujitsu Siemens         | 1         | 0.67%   |
| Eizo                    | 1         | 0.67%   |
| CSO                     | 1         | 0.67%   |
| AOC                     | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 1.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2         | 1.3%    |
| LGD LCD Monitor 1920x1080                                              | 2         | 1.3%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 2         | 1.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 2         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch       | 2         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch        | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch          | 2         | 1.3%    |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                       | 1         | 0.65%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1366x768            | 1         | 0.65%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.65%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                | 1         | 0.65%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch   | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC324C 1366x768 353x198mm 15.9-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 340x190mm 15.3-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC3150 1920x1080 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1020x570mm 46.0-inch | 1         | 0.65%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 1         | 0.65%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                | 1         | 0.65%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 1         | 0.65%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD061A 1920x1080 344x194mm 15.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD0615 1920x1080 382x215mm 17.3-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD05F5 1920x1080 309x174mm 14.0-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD056D 1920x1080 380x210mm 17.1-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD04A5 1920x1280 253x169mm 12.0-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD02D9 1920x1080 350x190mm 15.7-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD027B 1600x900 382x215mm 17.3-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD0214 1600x900 345x194mm 15.6-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD01E1 1366x768 310x174mm 14.0-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch            | 1         | 0.65%   |
| Lenovo LT1952p Wide LEN0990 1440x900 408x255mm 18.9-inch               | 1         | 0.65%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                | 1         | 0.65%   |
| KTC 42 TV KTC4200 1920x1080 983x576mm 44.9-inch                        | 1         | 0.65%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                  | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 63        | 45.99%  |
| 1366x768 (WXGA)   | 43        | 31.39%  |
| 2560x1440 (QHD)   | 6         | 4.38%   |
| 1600x900 (HD+)    | 6         | 4.38%   |
| 1280x800 (WXGA)   | 4         | 2.92%   |
| 3840x2160 (4K)    | 3         | 2.19%   |
| 1920x1200 (WUXGA) | 3         | 2.19%   |
| 1440x900 (WXGA+)  | 2         | 1.46%   |
| 3840x2400         | 1         | 0.73%   |
| 3000x2000         | 1         | 0.73%   |
| 2880x1800         | 1         | 0.73%   |
| 1920x1280         | 1         | 0.73%   |
| 1600x1200         | 1         | 0.73%   |
| 1360x768          | 1         | 0.73%   |
| 1280x1024 (SXGA)  | 1         | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 57        | 37.25%  |
| 14      | 19        | 12.42%  |
| 13      | 19        | 12.42%  |
| 24      | 10        | 6.54%   |
| 27      | 8         | 5.23%   |
| 17      | 8         | 5.23%   |
| 23      | 6         | 3.92%   |
| 12      | 5         | 3.27%   |
| 31      | 3         | 1.96%   |
| 21      | 3         | 1.96%   |
| 11      | 3         | 1.96%   |
| Unknown | 3         | 1.96%   |
| 19      | 2         | 1.31%   |
| 54      | 1         | 0.65%   |
| 48      | 1         | 0.65%   |
| 44      | 1         | 0.65%   |
| 32      | 1         | 0.65%   |
| 29      | 1         | 0.65%   |
| 22      | 1         | 0.65%   |
| 18      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 56.38%  |
| 501-600     | 20        | 13.42%  |
| 201-300     | 16        | 10.74%  |
| 351-400     | 12        | 8.05%   |
| 401-500     | 6         | 4.03%   |
| 601-700     | 4         | 2.68%   |
| Unknown     | 3         | 2.01%   |
| 1001-1500   | 2         | 1.34%   |
| 701-800     | 1         | 0.67%   |
| 901-1000    | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 107       | 84.92%  |
| 16/10   | 12        | 9.52%   |
| Unknown | 3         | 2.38%   |
| 3/2     | 2         | 1.59%   |
| 5/4     | 1         | 0.79%   |
| 4/3     | 1         | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 37.5%   |
| 81-90          | 31        | 20.39%  |
| 201-250        | 17        | 11.18%  |
| 301-350        | 8         | 5.26%   |
| 71-80          | 7         | 4.61%   |
| 121-130        | 7         | 4.61%   |
| 61-70          | 5         | 3.29%   |
| 351-500        | 5         | 3.29%   |
| 51-60          | 3         | 1.97%   |
| Unknown        | 3         | 1.97%   |
| More than 1000 | 2         | 1.32%   |
| 251-300        | 2         | 1.32%   |
| 151-200        | 2         | 1.32%   |
| 141-150        | 1         | 0.66%   |
| 131-140        | 1         | 0.66%   |
| 501-1000       | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 58        | 40%     |
| 101-120       | 44        | 30.34%  |
| 51-100        | 29        | 20%     |
| More than 240 | 5         | 3.45%   |
| 1-50          | 4         | 2.76%   |
| Unknown       | 3         | 2.07%   |
| 161-240       | 2         | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 91        | 73.98%  |
| 2     | 24        | 19.51%  |
| 3     | 6         | 4.88%   |
| 0     | 2         | 1.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 76        | 38.58%  |
| Realtek Semiconductor    | 65        | 32.99%  |
| Qualcomm Atheros         | 31        | 15.74%  |
| Broadcom                 | 10        | 5.08%   |
| Ralink                   | 4         | 2.03%   |
| Marvell Technology Group | 3         | 1.52%   |
| Broadcom Limited         | 3         | 1.52%   |
| Hewlett-Packard          | 2         | 1.02%   |
| Sierra Wireless          | 1         | 0.51%   |
| NetGear                  | 1         | 0.51%   |
| Lenovo                   | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 17.43%  |
| Intel Wi-Fi 6 AX200                                               | 14        | 5.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.98%   |
| Intel Wireless 8265 / 8275                                        | 10        | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.32%   |
| Intel Wireless 8260                                               | 7         | 2.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 2.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.24%   |
| Intel Wireless-AC 9260                                            | 3         | 1.24%   |
| Intel Wireless 3165                                               | 3         | 1.24%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.24%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.24%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.24%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.83%   |
| Intel Wireless 7265                                               | 2         | 0.83%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.83%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.83%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.83%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.41%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.41%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.41%   |
| Realtek 802.11ac NIC                                              | 1         | 0.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.41%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.41%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 0.41%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.41%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.41%   |
| Intel Wireless 7260                                               | 1         | 0.41%   |
| Intel Wireless 3160                                               | 1         | 0.41%   |
| Intel WiFi Link 5100                                              | 1         | 0.41%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 57.94%  |
| Qualcomm Atheros      | 24        | 19.05%  |
| Realtek Semiconductor | 12        | 9.52%   |
| Broadcom              | 8         | 6.35%   |
| Ralink                | 4         | 3.17%   |
| Broadcom Limited      | 3         | 2.38%   |
| Sierra Wireless       | 1         | 0.79%   |
| NetGear               | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 14        | 11.02%  |
| Intel Wireless 8265 / 8275                                     | 10        | 7.87%   |
| Intel Wireless 8260                                            | 7         | 5.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 4.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 3.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 3.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 3.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 3.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.36%   |
| Intel Wireless-AC 9260                                         | 3         | 2.36%   |
| Intel Wireless 3165                                            | 3         | 2.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2.36%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 2.36%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 2.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.57%   |
| Intel Wireless 7265                                            | 2         | 1.57%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.57%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.79%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.79%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.79%   |
| Realtek 802.11ac NIC                                           | 1         | 0.79%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.79%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.79%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 0.79%   |
| Intel Wireless 7260                                            | 1         | 0.79%   |
| Intel Wireless 3160                                            | 1         | 0.79%   |
| Intel WiFi Link 5100                                           | 1         | 0.79%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.79%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.79%   |
| Intel Centrino Wireless-N 2200                                 | 1         | 0.79%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.79%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.79%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.79%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                        | 1         | 0.79%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 0.79%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 0.79%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 60        | 54.05%  |
| Intel                    | 31        | 27.93%  |
| Qualcomm Atheros         | 11        | 9.91%   |
| Broadcom                 | 4         | 3.6%    |
| Marvell Technology Group | 3         | 2.7%    |
| Lenovo                   | 1         | 0.9%    |
| Hewlett-Packard          | 1         | 0.9%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 37.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 10.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 8.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 7.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.65%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.65%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.77%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.77%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.88%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.88%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.88%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.88%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.88%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.88%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.88%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 52.86%  |
| Ethernet | 106       | 46.7%   |
| Modem    | 1         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 63.64%  |
| Ethernet | 64        | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 103       | 85.83%  |
| 1     | 17        | 14.17%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 114       | 92.68%  |
| Yes  | 9         | 7.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 53%     |
| Qualcomm Atheros Communications | 10        | 10%     |
| Lite-On Technology              | 8         | 8%      |
| Broadcom                        | 8         | 8%      |
| Realtek Semiconductor           | 5         | 5%      |
| Foxconn / Hon Hai               | 3         | 3%      |
| Dell                            | 3         | 3%      |
| Ralink                          | 2         | 2%      |
| Hewlett-Packard                 | 2         | 2%      |
| Apple                           | 2         | 2%      |
| Toshiba                         | 1         | 1%      |
| Realtek                         | 1         | 1%      |
| IMC Networks                    | 1         | 1%      |
| Cambridge Silicon Radio         | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 18        | 18%     |
| Intel AX200 Bluetooth                                                               | 13        | 13%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 7%      |
| Intel Bluetooth wireless interface                                                  | 6         | 6%      |
| Lite-On Bluetooth Device                                                            | 5         | 5%      |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 4%      |
| Intel AX201 Bluetooth                                                               | 4         | 4%      |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 3%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 3%      |
| Dell DW375 Bluetooth Module                                                         | 3         | 3%      |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2%      |
| Realtek Bluetooth Radio                                                             | 2         | 2%      |
| Ralink RT3290 Bluetooth                                                             | 2         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2%      |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2%      |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1%      |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1%      |
| Realtek Bluetooth Radio                                                             | 1         | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1%      |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 1%      |
| Lite-On Atheros Bluetooth                                                           | 1         | 1%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1%      |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1%      |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1%      |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1%      |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 1%      |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1%      |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1%      |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1%      |
| Broadcom BCM20702A0                                                                 | 1         | 1%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1%      |
| Apple Bluetooth Host Controller                                                     | 1         | 1%      |
| Apple Bluetooth HCI                                                                 | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 108       | 67.08%  |
| Nvidia                    | 23        | 14.29%  |
| AMD                       | 14        | 8.7%    |
| Realtek Semiconductor     | 5         | 3.11%   |
| Kingston Technology       | 2         | 1.24%   |
| GN Netcom                 | 2         | 1.24%   |
| Sennheiser Communications | 1         | 0.62%   |
| Razer USA                 | 1         | 0.62%   |
| Plantronics               | 1         | 0.62%   |
| Lenovo                    | 1         | 0.62%   |
| JMTek                     | 1         | 0.62%   |
| Hewlett-Packard           | 1         | 0.62%   |
| C-Media Electronics       | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 10.33%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 7.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 6.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 5.43%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 4.35%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 8         | 4.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.8%    |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.8%    |
| Realtek Semiconductor USB Audio                                                                   | 5         | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.17%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.17%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.63%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.63%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.63%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.63%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.09%   |
| Sennheiser Communications Sennheiser DECT for Lync                                                | 1         | 0.54%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.54%   |
| Plantronics C320-M                                                                                | 1         | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.54%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.54%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.54%   |
| Nvidia Audio device                                                                               | 1         | 0.54%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 0.54%   |
| Kingston Technology HyperX Cloud Stinger Wireless                                                 | 1         | 0.54%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.54%   |
| JMTek USB Audio Device                                                                            | 1         | 0.54%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.54%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.54%   |
| Hewlett-Packard USB Audio                                                                         | 1         | 0.54%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.54%   |
| GN Netcom Jabra EVOLVE 65                                                                         | 1         | 0.54%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 0.54%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.54%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.54%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 31.52%  |
| SK Hynix            | 25        | 27.17%  |
| Micron Technology   | 11        | 11.96%  |
| Kingston            | 5         | 5.43%   |
| Crucial             | 5         | 5.43%   |
| Unknown             | 3         | 3.26%   |
| A-DATA Technology   | 3         | 3.26%   |
| Smart               | 2         | 2.17%   |
| Ramaxel Technology  | 2         | 2.17%   |
| Teikon              | 1         | 1.09%   |
| SMART Brazil        | 1         | 1.09%   |
| Nanya Technology    | 1         | 1.09%   |
| Kingmax             | 1         | 1.09%   |
| Elpida              | 1         | 1.09%   |
| Corsair             | 1         | 1.09%   |
| ASint Technology    | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 3         | 3%      |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 3         | 3%      |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 3         | 3%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 3%      |
| SK Hynix RAM HMT351S6CFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 2         | 2%      |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 2         | 2%      |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 2         | 2%      |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 2         | 2%      |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s       | 2         | 2%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 2%      |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s       | 2         | 2%      |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s           | 2         | 2%      |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s         | 2         | 2%      |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                      | 1         | 1%      |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1%      |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 1%      |
| Unknown RAM Module 2048MB SODIMM DDR3                          | 1         | 1%      |
| Teikon RAM TMT451S6BFR8A-PBAJ 4096MB SODIMM DDR3 1600MT/s      | 1         | 1%      |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s          | 1         | 1%      |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s          | 1         | 1%      |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s       | 1         | 1%      |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 1%      |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s              | 1         | 1%      |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s               | 1         | 1%      |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1%      |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1%      |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1%      |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1%      |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 1%      |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1%      |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s      | 1         | 1%      |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s         | 1         | 1%      |
| SK Hynix RAM HMT125S6AFR8C-G7 2048MB SODIMM DDR3 1067MT/s      | 1         | 1%      |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 1%      |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1%      |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 1%      |
| SK Hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s         | 1         | 1%      |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 1%      |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 1         | 1%      |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 1         | 1%      |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1%      |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 1%      |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1         | 1%      |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s          | 1         | 1%      |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 1%      |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s       | 1         | 1%      |
| Samsung RAM M471B5173BH0-YK0 4096MB SODIMM DDR3 1600MT/s       | 1         | 1%      |
| Samsung RAM M471B2874EH1-CF8 1024MB SODIMM 1067MT/s            | 1         | 1%      |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1         | 1%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 1%      |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 1%      |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s      | 1         | 1%      |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s       | 1         | 1%      |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s       | 1         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s | 1         | 1%      |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s        | 1         | 1%      |
| Ramaxel RAM RMSA3260NA78HAF-2400 8GB SODIMM DDR4 2400MT/s      | 1         | 1%      |
| Nanya RAM M2S4G64CB8HG5N-CG 4096MB SODIMM DDR3 1334MT/s        | 1         | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 51.85%  |
| DDR3   | 33        | 40.74%  |
| SDRAM  | 3         | 3.7%    |
| LPDDR4 | 1         | 1.23%   |
| LPDDR3 | 1         | 1.23%   |
| DDR2   | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 97.4%   |
| Row Of Chips | 2         | 2.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 34        | 39.53%  |
| 8192  | 25        | 29.07%  |
| 16384 | 17        | 19.77%  |
| 2048  | 5         | 5.81%   |
| 32768 | 3         | 3.49%   |
| 1024  | 2         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 25        | 28.09%  |
| 1600    | 23        | 25.84%  |
| 3200    | 7         | 7.87%   |
| 2133    | 6         | 6.74%   |
| 1334    | 6         | 6.74%   |
| 1333    | 6         | 6.74%   |
| 2400    | 5         | 5.62%   |
| 1067    | 4         | 4.49%   |
| 4199    | 3         | 3.37%   |
| 3266    | 1         | 1.12%   |
| 1867    | 1         | 1.12%   |
| 667     | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung M2020 Series   | 1         | 50%     |
| HP DeskJet 2130 series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 26.85%  |
| Acer                                   | 12        | 11.11%  |
| Realtek Semiconductor                  | 11        | 10.19%  |
| Sunplus Innovation Technology          | 8         | 7.41%   |
| IMC Networks                           | 8         | 7.41%   |
| Microdia                               | 7         | 6.48%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 6.48%   |
| Quanta                                 | 5         | 4.63%   |
| Syntek                                 | 4         | 3.7%    |
| Silicon Motion                         | 4         | 3.7%    |
| Suyin                                  | 3         | 2.78%   |
| Lite-On Technology                     | 2         | 1.85%   |
| Apple                                  | 2         | 1.85%   |
| Ricoh                                  | 1         | 0.93%   |
| Primax Electronics                     | 1         | 0.93%   |
| LG Electronics                         | 1         | 0.93%   |
| Generalplus Technology                 | 1         | 0.93%   |
| Creative Technology                    | 1         | 0.93%   |
| Alcor Micro                            | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                                          | 6         | 5.56%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 4.63%   |
| Chicony Integrated Camera                                                  | 5         | 4.63%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 3.7%    |
| Chicony USB2.0 Camera                                                      | 4         | 3.7%    |
| Sunplus Asus Webcam                                                        | 3         | 2.78%   |
| Chicony HP HD Camera                                                       | 3         | 2.78%   |
| Acer BisonCam,NB Pro                                                       | 3         | 2.78%   |
| Suyin HP Truevision HD                                                     | 2         | 1.85%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.85%   |
| IMC Networks VGA UVC WebCam                                                | 2         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 1.85%   |
| IMC Networks Integrated Camera                                             | 2         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 2         | 1.85%   |
| Acer HD Webcam                                                             | 2         | 1.85%   |
| Acer BisonCam, NB Pro                                                      | 2         | 1.85%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                                       | 1         | 0.93%   |
| Syntek USB2.0 Camera                                                       | 1         | 0.93%   |
| Syntek Integrated Camera                                                   | 1         | 0.93%   |
| Syntek EasyCamera                                                          | 1         | 0.93%   |
| Suyin HD WebCam                                                            | 1         | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 0.93%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 0.93%   |
| Sunplus HD WebCam                                                          | 1         | 0.93%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 0.93%   |
| Silicon Motion WebCam SC-10HDD13335N                                       | 1         | 0.93%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.93%   |
| Silicon Motion Web Camera                                                  | 1         | 0.93%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 1         | 0.93%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 0.93%   |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 0.93%   |
| Realtek Integrated Webcam HD                                               | 1         | 0.93%   |
| Realtek Integrated Webcam                                                  | 1         | 0.93%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 0.93%   |
| Realtek HD WebCam                                                          | 1         | 0.93%   |
| Quanta VGA WebCam                                                          | 1         | 0.93%   |
| Quanta LG Webcam                                                           | 1         | 0.93%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                       | 1         | 0.93%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 0.93%   |
| Quanta HD User Facing                                                      | 1         | 0.93%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 0.93%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 0.93%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 1         | 0.93%   |
| Lite-On HP TrueVision HD Camera                                            | 1         | 0.93%   |
| Lite-On HP HD Webcam                                                       | 1         | 0.93%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)                      | 1         | 0.93%   |
| IMC Networks USB 2.0 Camera                                                | 1         | 0.93%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 0.93%   |
| Generalplus GENERAL WEBCAM                                                 | 1         | 0.93%   |
| Creative Live! Cam Chat HD [VF0700]                                        | 1         | 0.93%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 0.93%   |
| Chicony USB 2.0 Webcam Device                                              | 1         | 0.93%   |
| Chicony USB 2.0 Camera                                                     | 1         | 0.93%   |
| Chicony thinkpad t430s camera                                              | 1         | 0.93%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 0.93%   |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 43.33%  |
| Synaptics                  | 10        | 33.33%  |
| Shenzhen Goodix Technology | 3         | 10%     |
| LighTuning Technology      | 2         | 6.67%   |
| Elan Microelectronics      | 1         | 3.33%   |
| AuthenTec                  | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 13.33%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 13.33%  |
| Unknown                                                                    | 4         | 13.33%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 10%     |
| Synaptics WBDI Device                                                      | 2         | 6.67%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.33%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.33%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.33%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.33%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 54.55%  |
| Upek        | 3         | 27.27%  |
| Lenovo      | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor             | 3         | 27.27%  |
| Broadcom 5880                                              | 3         | 27.27%  |
| Lenovo Integrated Smart Card Reader                        | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 63        | 52.07%  |
| 1     | 44        | 36.36%  |
| 2     | 12        | 9.92%   |
| 4     | 1         | 0.83%   |
| 3     | 1         | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 42.86%  |
| Graphics card            | 11        | 15.71%  |
| Chipcard                 | 11        | 15.71%  |
| Communication controller | 6         | 8.57%   |
| Net/wireless             | 5         | 7.14%   |
| Storage                  | 2         | 2.86%   |
| Bluetooth                | 2         | 2.86%   |
| Net/ethernet             | 1         | 1.43%   |
| Card reader              | 1         | 1.43%   |
| Camera                   | 1         | 1.43%   |


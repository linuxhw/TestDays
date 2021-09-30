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
| 5.4.0-42-generic           | 16        | 12.21%  |
| 5.4.0-40-generic           | 9         | 6.87%   |
| 5.4.0-37-generic           | 6         | 4.58%   |
| 5.4.0-29-generic           | 6         | 4.58%   |
| 5.4.0-52-generic           | 5         | 3.82%   |
| 5.4.0-48-generic           | 5         | 3.82%   |
| 5.4.0-33-generic           | 5         | 3.82%   |
| 5.8.0-53-generic           | 4         | 3.05%   |
| 5.4.0-58-generic           | 4         | 3.05%   |
| 5.4.0-31-generic           | 4         | 3.05%   |
| 5.4.0-73-generic           | 3         | 2.29%   |
| 5.4.0-28-generic           | 3         | 2.29%   |
| 5.8.0-49-generic           | 2         | 1.53%   |
| 5.8.0-48-generic           | 2         | 1.53%   |
| 5.8.0-45-generic           | 2         | 1.53%   |
| 5.8.0-44-generic           | 2         | 1.53%   |
| 5.4.0-80-generic           | 2         | 1.53%   |
| 5.4.0-72-generic           | 2         | 1.53%   |
| 5.4.0-66-generic           | 2         | 1.53%   |
| 5.4.0-65-generic           | 2         | 1.53%   |
| 5.4.0-60-generic           | 2         | 1.53%   |
| 5.4.0-59-generic           | 2         | 1.53%   |
| 5.4.0-56-generic           | 2         | 1.53%   |
| 5.4.0-47-generic           | 2         | 1.53%   |
| 5.4.0-26-generic           | 2         | 1.53%   |
| 5.11.0-27-generic          | 2         | 1.53%   |
| 5.9.0-050900rc6-lowlatency | 1         | 0.76%   |
| 5.8.11-050811-generic      | 1         | 0.76%   |
| 5.8.0-63-generic           | 1         | 0.76%   |
| 5.8.0-59-generic           | 1         | 0.76%   |
| 5.8.0-50-generic           | 1         | 0.76%   |
| 5.8.0-43-generic           | 1         | 0.76%   |
| 5.8.0-41-generic           | 1         | 0.76%   |
| 5.6.7-050607-generic       | 1         | 0.76%   |
| 5.6.0-1048-oem             | 1         | 0.76%   |
| 5.6.0-1042-oem             | 1         | 0.76%   |
| 5.6.0-1034-oem             | 1         | 0.76%   |
| 5.5.0-2.1-liquorix-amd64   | 1         | 0.76%   |
| 5.4.0-77-generic           | 1         | 0.76%   |
| 5.4.0-74-generic           | 1         | 0.76%   |
| 5.4.0-62-generic           | 1         | 0.76%   |
| 5.4.0-61-generic           | 1         | 0.76%   |
| 5.4.0-55-generic           | 1         | 0.76%   |
| 5.4.0-54-generic           | 1         | 0.76%   |
| 5.4.0-51-generic           | 1         | 0.76%   |
| 5.4.0-48-lowlatency        | 1         | 0.76%   |
| 5.4.0-45-generic           | 1         | 0.76%   |
| 5.4.0-44-generic           | 1         | 0.76%   |
| 5.4.0-41-generic           | 1         | 0.76%   |
| 5.4.0-30-generic           | 1         | 0.76%   |
| 5.4.0-25-generic           | 1         | 0.76%   |
| 5.4.0-21-generic           | 1         | 0.76%   |
| 5.4.0-18-generic           | 1         | 0.76%   |
| 5.3.0-46-generic           | 1         | 0.76%   |
| 5.3.0-24-generic           | 1         | 0.76%   |
| 5.12.0-051200-generic      | 1         | 0.76%   |
| 5.11.0-36-generic          | 1         | 0.76%   |
| 5.11.0-25-generic          | 1         | 0.76%   |
| 5.10.11                    | 1         | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 88        | 73.33%  |
| 5.8.0   | 17        | 14.17%  |
| 5.11.0  | 4         | 3.33%   |
| 5.6.0   | 3         | 2.5%    |
| 5.3.0   | 2         | 1.67%   |
| 5.9.0   | 1         | 0.83%   |
| 5.8.11  | 1         | 0.83%   |
| 5.6.7   | 1         | 0.83%   |
| 5.5.0   | 1         | 0.83%   |
| 5.12.0  | 1         | 0.83%   |
| 5.10.11 | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 88        | 73.33%  |
| 5.8     | 18        | 15%     |
| 5.6     | 4         | 3.33%   |
| 5.11    | 4         | 3.33%   |
| 5.3     | 2         | 1.67%   |
| 5.9     | 1         | 0.83%   |
| 5.5     | 1         | 0.83%   |
| 5.12    | 1         | 0.83%   |
| 5.10    | 1         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 118       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 115       | 97.46%  |
| GNOME  | 2         | 1.69%   |
| XFCE   | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 113       | 95.76%  |
| Wayland | 5         | 4.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 55        | 46.61%  |
| TDM     | 33        | 27.97%  |
| GDM     | 18        | 15.25%  |
| LightDM | 12        | 10.17%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 34        | 28.57%  |
| pt_BR   | 13        | 10.92%  |
| de_DE   | 13        | 10.92%  |
| en_GB   | 9         | 7.56%   |
| fr_FR   | 8         | 6.72%   |
| en_CA   | 6         | 5.04%   |
| ru_RU   | 3         | 2.52%   |
| es_ES   | 3         | 2.52%   |
| en_IN   | 3         | 2.52%   |
| pt_PT   | 2         | 1.68%   |
| it_IT   | 2         | 1.68%   |
| fi_FI   | 2         | 1.68%   |
| es_AR   | 2         | 1.68%   |
| en_AU   | 2         | 1.68%   |
| de_CH   | 2         | 1.68%   |
| C       | 2         | 1.68%   |
| pl_PL   | 1         | 0.84%   |
| nb_NO   | 1         | 0.84%   |
| id_ID   | 1         | 0.84%   |
| hu_HU   | 1         | 0.84%   |
| fr_CH   | 1         | 0.84%   |
| es_US   | 1         | 0.84%   |
| es_SV   | 1         | 0.84%   |
| es_MX   | 1         | 0.84%   |
| es_GT   | 1         | 0.84%   |
| es_CL   | 1         | 0.84%   |
| en_SG   | 1         | 0.84%   |
| de_AT   | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 87        | 71.31%  |
| BIOS | 35        | 28.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 108       | 91.53%  |
| Zfs     | 5         | 4.24%   |
| Overlay | 2         | 1.69%   |
| Xfs     | 1         | 0.85%   |
| Jfs     | 1         | 0.85%   |
| Btrfs   | 1         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 47.46%  |
| GPT     | 45        | 38.14%  |
| MBR     | 17        | 14.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 92.5%   |
| Yes       | 9         | 7.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 66.95%  |
| Yes       | 39        | 33.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 20.34%  |
| Dell                | 18        | 15.25%  |
| Lenovo              | 17        | 14.41%  |
| ASUSTek Computer    | 14        | 11.86%  |
| TUXEDO              | 13        | 11.02%  |
| Acer                | 10        | 8.47%   |
| MSI                 | 7         | 5.93%   |
| Samsung Electronics | 4         | 3.39%   |
| Sony                | 2         | 1.69%   |
| HUAWEI              | 2         | 1.69%   |
| Apple               | 2         | 1.69%   |
| Toshiba             | 1         | 0.85%   |
| Standard            | 1         | 0.85%   |
| Quanta              | 1         | 0.85%   |
| Gigabyte Technology | 1         | 0.85%   |
| Fujitsu             | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ZBook Studio G3                                    | 2         | 1.69%   |
| HP Pavilion g6                                        | 2         | 1.69%   |
| HP Notebook                                           | 2         | 1.69%   |
| Dell Latitude 5400                                    | 2         | 1.69%   |
| Acer TravelMate P446-M                                | 2         | 1.69%   |
| Unknown                                               | 2         | 1.69%   |
| TUXEDO TUXEDO_Book_XA1510                             | 1         | 0.85%   |
| TUXEDO Polaris 17 AMD Gen1                            | 1         | 0.85%   |
| TUXEDO Polaris 15 AMD Gen1                            | 1         | 0.85%   |
| TUXEDO P95_HR                                         | 1         | 0.85%   |
| TUXEDO P7xxTM1                                        | 1         | 0.85%   |
| TUXEDO InfinityBook S 15 Gen6                         | 1         | 0.85%   |
| TUXEDO InfinityBook S 14 Gen6                         | 1         | 0.85%   |
| TUXEDO InfinityBook Pro 15 v4                         | 1         | 0.85%   |
| TUXEDO InfinityBook Pro 14 Gen6                       | 1         | 0.85%   |
| TUXEDO Book XP1511                                    | 1         | 0.85%   |
| TUXEDO Aura 15 Gen1                                   | 1         | 0.85%   |
| Toshiba Satellite P300                                | 1         | 0.85%   |
| Standard MT40II                                       | 1         | 0.85%   |
| Sony VPCCW25FL                                        | 1         | 0.85%   |
| Sony SVS13A25PBS                                      | 1         | 0.85%   |
| Samsung 905S3G/906S3G/915S3G/9305SG                   | 1         | 0.85%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.85%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.85%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.85%   |
| Quanta R460-L.BG22P1                                  | 1         | 0.85%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.85%   |
| MSI Modern 14 A10RB                                   | 1         | 0.85%   |
| MSI GP73 Leopard 8RE                                  | 1         | 0.85%   |
| MSI GP72 7RE                                          | 1         | 0.85%   |
| MSI GL62M 7RD                                         | 1         | 0.85%   |
| MSI GE70 2PC\2PE                                      | 1         | 0.85%   |
| MSI CX62 6QL                                          | 1         | 0.85%   |
| Lenovo ThinkPad X260 20F5S2HF06                       | 1         | 0.85%   |
| Lenovo ThinkPad X230 23257G6                          | 1         | 0.85%   |
| Lenovo ThinkPad X230 2306CTO                          | 1         | 0.85%   |
| Lenovo ThinkPad W530 2447GW3                          | 1         | 0.85%   |
| Lenovo ThinkPad T430s 23539WU                         | 1         | 0.85%   |
| Lenovo ThinkPad T430 2349P74                          | 1         | 0.85%   |
| Lenovo ThinkPad T410 2537H21                          | 1         | 0.85%   |
| Lenovo ThinkPad P53 20QQS1JE00                        | 1         | 0.85%   |
| Lenovo ThinkPad P43s 20RHS00100                       | 1         | 0.85%   |
| Lenovo ThinkPad P43s 20RH0013US                       | 1         | 0.85%   |
| Lenovo ThinkPad P1 20MES01400                         | 1         | 0.85%   |
| Lenovo ThinkPad E490 20N8S07A00                       | 1         | 0.85%   |
| Lenovo IdeaPad S145-15IWL 81S9                        | 1         | 0.85%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                         | 1         | 0.85%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.85%   |
| Lenovo G550 2958                                      | 1         | 0.85%   |
| Lenovo 20SL                                           | 1         | 0.85%   |
| HUAWEI MACH-WX9                                       | 1         | 0.85%   |
| HUAWEI BOHK-WAX9X                                     | 1         | 0.85%   |
| HP x360 310 G2 PC                                     | 1         | 0.85%   |
| HP ProBook 640 G2                                     | 1         | 0.85%   |
| HP ProBook 4730s                                      | 1         | 0.85%   |
| HP Pavilion Gaming Laptop 15-dk0xxx                   | 1         | 0.85%   |
| HP Pavilion dv6                                       | 1         | 0.85%   |
| HP Pavilion 14                                        | 1         | 0.85%   |
| HP Laptop 15-dw0xxx                                   | 1         | 0.85%   |
| HP Laptop 15-da0xxx                                   | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 12        | 10.17%  |
| Dell Latitude          | 9         | 7.63%   |
| Acer Aspire            | 8         | 6.78%   |
| HP Pavilion            | 5         | 4.24%   |
| HP EliteBook           | 5         | 4.24%   |
| Dell Inspiron          | 5         | 4.24%   |
| TUXEDO InfinityBook    | 4         | 3.39%   |
| Lenovo IdeaPad         | 3         | 2.54%   |
| HP Laptop              | 3         | 2.54%   |
| TUXEDO Polaris         | 2         | 1.69%   |
| HP ZBook               | 2         | 1.69%   |
| HP ProBook             | 2         | 1.69%   |
| HP Notebook            | 2         | 1.69%   |
| HP ENVY                | 2         | 1.69%   |
| Dell XPS               | 2         | 1.69%   |
| Acer TravelMate        | 2         | 1.69%   |
| Unknown                | 2         | 1.69%   |
| TUXEDO TUXEDO          | 1         | 0.85%   |
| TUXEDO P95             | 1         | 0.85%   |
| TUXEDO P7xxTM1         | 1         | 0.85%   |
| TUXEDO Book            | 1         | 0.85%   |
| TUXEDO Aura            | 1         | 0.85%   |
| Toshiba Satellite      | 1         | 0.85%   |
| Standard MT40II        | 1         | 0.85%   |
| Sony VPCCW25FL         | 1         | 0.85%   |
| Sony SVS13A25PBS       | 1         | 0.85%   |
| Samsung 905S3G         | 1         | 0.85%   |
| Samsung 530U3C         | 1         | 0.85%   |
| Samsung 340XAA         | 1         | 0.85%   |
| Samsung 300E5EV        | 1         | 0.85%   |
| Quanta R460-L.BG22P1   | 1         | 0.85%   |
| MSI Prestige           | 1         | 0.85%   |
| MSI Modern             | 1         | 0.85%   |
| MSI GP73               | 1         | 0.85%   |
| MSI GP72               | 1         | 0.85%   |
| MSI GL62M              | 1         | 0.85%   |
| MSI GE70               | 1         | 0.85%   |
| MSI CX62               | 1         | 0.85%   |
| Lenovo G550            | 1         | 0.85%   |
| Lenovo 20SL            | 1         | 0.85%   |
| HUAWEI MACH-WX9        | 1         | 0.85%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.85%   |
| HP x360                | 1         | 0.85%   |
| HP Elite               | 1         | 0.85%   |
| HP Compaq              | 1         | 0.85%   |
| Gigabyte GB-BKi7A-7500 | 1         | 0.85%   |
| Fujitsu LIFEBOOK       | 1         | 0.85%   |
| Dell G7                | 1         | 0.85%   |
| Dell G3                | 1         | 0.85%   |
| ASUS ZenBook           | 1         | 0.85%   |
| ASUS X551CA            | 1         | 0.85%   |
| ASUS X540LA            | 1         | 0.85%   |
| ASUS X510UNR           | 1         | 0.85%   |
| ASUS X510UAR           | 1         | 0.85%   |
| ASUS X302LJ            | 1         | 0.85%   |
| ASUS VivoBook          | 1         | 0.85%   |
| ASUS UX430UQ           | 1         | 0.85%   |
| ASUS S400CA            | 1         | 0.85%   |
| ASUS N53SM             | 1         | 0.85%   |
| ASUS K53E              | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 25        | 21.19%  |
| 2020 | 23        | 19.49%  |
| 2018 | 17        | 14.41%  |
| 2013 | 10        | 8.47%   |
| 2017 | 8         | 6.78%   |
| 2014 | 7         | 5.93%   |
| 2015 | 6         | 5.08%   |
| 2012 | 6         | 5.08%   |
| 2016 | 5         | 4.24%   |
| 2011 | 3         | 2.54%   |
| 2010 | 3         | 2.54%   |
| 2008 | 3         | 2.54%   |
| 2021 | 1         | 0.85%   |
| 2009 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 118       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 100       | 84.75%  |
| Enabled  | 18        | 15.25%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 118       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 34        | 28.33%  |
| 16.01-24.0  | 27        | 22.5%   |
| 8.01-16.0   | 23        | 19.17%  |
| 3.01-4.0    | 17        | 14.17%  |
| 32.01-64.0  | 12        | 10%     |
| 64.01-256.0 | 4         | 3.33%   |
| 2.01-3.0    | 2         | 1.67%   |
| 1.01-2.0    | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 39        | 30.71%  |
| 1.01-2.0  | 29        | 22.83%  |
| 3.01-4.0  | 26        | 20.47%  |
| 4.01-8.0  | 25        | 19.69%  |
| 8.01-16.0 | 8         | 6.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 72.03%  |
| 2      | 30        | 25.42%  |
| 3      | 3         | 2.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 66.95%  |
| Yes       | 39        | 33.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 88.14%  |
| No        | 14        | 11.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 83.05%  |
| No        | 20        | 16.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 17        | 14.41%  |
| Brazil             | 15        | 12.71%  |
| USA                | 11        | 9.32%   |
| France             | 7         | 5.93%   |
| Russia             | 5         | 4.24%   |
| UK                 | 4         | 3.39%   |
| Spain              | 4         | 3.39%   |
| Poland             | 4         | 3.39%   |
| Italy              | 4         | 3.39%   |
| Canada             | 4         | 3.39%   |
| Iran               | 3         | 2.54%   |
| India              | 3         | 2.54%   |
| Finland            | 3         | 2.54%   |
| Ukraine            | 2         | 1.69%   |
| Turkey             | 2         | 1.69%   |
| Switzerland        | 2         | 1.69%   |
| South Africa       | 2         | 1.69%   |
| Portugal           | 2         | 1.69%   |
| Norway             | 2         | 1.69%   |
| Netherlands        | 2         | 1.69%   |
| Indonesia          | 2         | 1.69%   |
| Austria            | 2         | 1.69%   |
| Australia          | 2         | 1.69%   |
| Argentina          | 2         | 1.69%   |
| Slovenia           | 1         | 0.85%   |
| Singapore          | 1         | 0.85%   |
| Mexico             | 1         | 0.85%   |
| Kenya              | 1         | 0.85%   |
| Japan              | 1         | 0.85%   |
| Hungary            | 1         | 0.85%   |
| Honduras           | 1         | 0.85%   |
| Guatemala          | 1         | 0.85%   |
| El Salvador        | 1         | 0.85%   |
| Ecuador            | 1         | 0.85%   |
| Dominican Republic | 1         | 0.85%   |
| Chile              | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Tehran                    | 3         | 2.46%   |
| São Paulo                | 3         | 2.46%   |
| Stuttgart                 | 3         | 2.46%   |
| Paris                     | 3         | 2.46%   |
| Moscow                    | 2         | 1.64%   |
| Montreal                  | 2         | 1.64%   |
| Los Angeles               | 2         | 1.64%   |
| Kyiv                      | 2         | 1.64%   |
| Brasília                 | 2         | 1.64%   |
| Belo Horizonte            | 2         | 1.64%   |
| Zheleznodorozhnyy         | 1         | 0.82%   |
| Zabrze                    | 1         | 0.82%   |
| Yuma                      | 1         | 0.82%   |
| Woking                    | 1         | 0.82%   |
| Wilchingen, Osterfingen   | 1         | 0.82%   |
| Waterloo                  | 1         | 0.82%   |
| Warsaw                    | 1         | 0.82%   |
| Vienna                    | 1         | 0.82%   |
| Vicente Lopez             | 1         | 0.82%   |
| Vantaa                    | 1         | 0.82%   |
| Tuttlingen                | 1         | 0.82%   |
| Tuscola                   | 1         | 0.82%   |
| Turku                     | 1         | 0.82%   |
| Totana                    | 1         | 0.82%   |
| Tokyo                     | 1         | 0.82%   |
| Tiel                      | 1         | 0.82%   |
| Teresina                  | 1         | 0.82%   |
| Tangerang                 | 1         | 0.82%   |
| São Luís                | 1         | 0.82%   |
| São José dos Campos     | 1         | 0.82%   |
| Sydney                    | 1         | 0.82%   |
| St Petersburg             | 1         | 0.82%   |
| Spilimbergo               | 1         | 0.82%   |
| Skien                     | 1         | 0.82%   |
| Singapore                 | 1         | 0.82%   |
| Sens                      | 1         | 0.82%   |
| Santo Domingo Este        | 1         | 0.82%   |
| Santarém                 | 1         | 0.82%   |
| Santa Tecla               | 1         | 0.82%   |
| San Pedro Sula            | 1         | 0.82%   |
| Salt Lake City            | 1         | 0.82%   |
| Salamanca                 | 1         | 0.82%   |
| Saint-Medard-de-Guizieres | 1         | 0.82%   |
| Saint-Junien              | 1         | 0.82%   |
| Rostov-on-Don             | 1         | 0.82%   |
| Quito                     | 1         | 0.82%   |
| Povoa de Lanhoso          | 1         | 0.82%   |
| Ponte San Pietro          | 1         | 0.82%   |
| Penzberg                  | 1         | 0.82%   |
| Ovalle                    | 1         | 0.82%   |
| Oswestry                  | 1         | 0.82%   |
| Oslo                      | 1         | 0.82%   |
| Osasco                    | 1         | 0.82%   |
| Niterói                  | 1         | 0.82%   |
| Nieuwegein                | 1         | 0.82%   |
| Neu-Ulm                   | 1         | 0.82%   |
| Neenah                    | 1         | 0.82%   |
| Nairobi                   | 1         | 0.82%   |
| Munich                    | 1         | 0.82%   |
| Mulgrave                  | 1         | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Samsung Electronics | 34        | 45      | 22.97%  |
| Toshiba             | 18        | 20      | 12.16%  |
| Seagate             | 17        | 19      | 11.49%  |
| WDC                 | 15        | 17      | 10.14%  |
| Sandisk             | 11        | 12      | 7.43%   |
| Unknown             | 6         | 7       | 4.05%   |
| HGST                | 6         | 9       | 4.05%   |
| Crucial             | 6         | 6       | 4.05%   |
| SK Hynix            | 5         | 5       | 3.38%   |
| Kingston            | 5         | 5       | 3.38%   |
| Intel               | 5         | 6       | 3.38%   |
| Hitachi             | 4         | 4       | 2.7%    |
| A-DATA Technology   | 4         | 5       | 2.7%    |
| Micron Technology   | 3         | 5       | 2.03%   |
| PNY                 | 2         | 3       | 1.35%   |
| Vaseky              | 1         | 1       | 0.68%   |
| LITEON              | 1         | 1       | 0.68%   |
| KingSpec            | 1         | 1       | 0.68%   |
| KimMiDi             | 1         | 1       | 0.68%   |
| Hewlett-Packard     | 1         | Unknown | 0.68%   |
| Corsair             | 1         | 1       | 0.68%   |
| China               | 1         | 1       | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 4         | 2.6%    |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.95%   |
| Unknown MMC Card  32GB                  | 2         | 1.3%    |
| SK Hynix NVMe SSD Drive 256GB           | 2         | 1.3%    |
| Seagate ST9500325AS 500GB               | 2         | 1.3%    |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 1.3%    |
| Seagate BUP Slim BK 1TB                 | 2         | 1.3%    |
| SanDisk SSD PLUS 120GB                  | 2         | 1.3%    |
| Sandisk NVMe SSD Drive 512GB            | 2         | 1.3%    |
| Samsung SSD 980 PRO 1TB                 | 2         | 1.3%    |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 1.3%    |
| Samsung SSD 970 EVO 500GB               | 2         | 1.3%    |
| Samsung SSD 860 EVO M.2 250GB           | 2         | 1.3%    |
| Samsung SSD 750 EVO 250GB               | 2         | 1.3%    |
| Samsung NVMe SSD Drive 500GB            | 2         | 1.3%    |
| Samsung NVMe SSD Drive 250GB            | 2         | 1.3%    |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.3%    |
| Hitachi HTS545050A7E380 500GB           | 2         | 1.3%    |
| HGST HTS725050A7E630 500GB              | 2         | 1.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.65%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD        | 1         | 0.65%   |
| WDC WDS100T2B0A 1TB SSD                 | 1         | 0.65%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.65%   |
| WDC WD1600BEVS-08VAT2 160GB             | 1         | 0.65%   |
| WDC WD10SPZX-75Z10T2 1TB                | 1         | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.65%   |
| WDC WD10SPZX-35Z10T0 1TB                | 1         | 0.65%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.65%   |
| WDC WD10SPZX-17Z10T0 1TB                | 1         | 0.65%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.65%   |
| WDC PC SN720 SDAQNTW-256G-1001 256GB    | 1         | 0.65%   |
| WDC PC SN520 NVMe 512GB                 | 1         | 0.65%   |
| Vaseky V800/120G 120GB                  | 1         | 0.65%   |
| Unknown SD64G  64GB                     | 1         | 0.65%   |
| Unknown NVMe SSD Drive 512GB            | 1         | 0.65%   |
| Unknown MMC Card  64GB                  | 1         | 0.65%   |
| Unknown MMC Card  16GB                  | 1         | 0.65%   |
| Unknown 00000  2GB                      | 1         | 0.65%   |
| Toshiba THNSNJ512G8NY 512GB SSD         | 1         | 0.65%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.65%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.65%   |
| Toshiba MQ01ACF050 500GB                | 1         | 0.65%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.65%   |
| Toshiba MQ01ABF032 320GB                | 1         | 0.65%   |
| Toshiba MK7559GSXF 752GB                | 1         | 0.65%   |
| Toshiba MK6461GSYN 640GB                | 1         | 0.65%   |
| Toshiba MK2561GSYN 250GB                | 1         | 0.65%   |
| Toshiba MK2552GSX 250GB                 | 1         | 0.65%   |
| Toshiba KXG60ZNV256G NVMe 256GB         | 1         | 0.65%   |
| Toshiba KXG5AZNV512G 512GB              | 1         | 0.65%   |
| Toshiba KBG30ZMT512G 512GB              | 1         | 0.65%   |
| Toshiba HDWJ110 1TB                     | 1         | 0.65%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 1         | 0.65%   |
| SK Hynix HFM512GDJTNI-82A0A 512GB       | 1         | 0.65%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 0.65%   |
| Seagate ST9750420AS 752GB               | 1         | 0.65%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 18     | 33.33%  |
| Toshiba | 13        | 15     | 27.08%  |
| WDC     | 9         | 10     | 18.75%  |
| HGST    | 6         | 9      | 12.5%   |
| Hitachi | 4         | 4      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 22     | 32.08%  |
| SanDisk             | 8         | 8      | 15.09%  |
| Kingston            | 5         | 5      | 9.43%   |
| Crucial             | 5         | 5      | 9.43%   |
| WDC                 | 4         | 5      | 7.55%   |
| A-DATA Technology   | 3         | 4      | 5.66%   |
| PNY                 | 2         | 3      | 3.77%   |
| Micron Technology   | 2         | 4      | 3.77%   |
| Vaseky              | 1         | 1      | 1.89%   |
| Toshiba             | 1         | 1      | 1.89%   |
| SK Hynix            | 1         | 1      | 1.89%   |
| LITEON              | 1         | 1      | 1.89%   |
| KingSpec            | 1         | 1      | 1.89%   |
| Intel               | 1         | 1      | 1.89%   |
| China               | 1         | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 50        | 63     | 35.21%  |
| HDD     | 45        | 56     | 31.69%  |
| NVMe    | 39        | 47     | 27.46%  |
| MMC     | 5         | 6      | 3.52%   |
| Unknown | 3         | 2      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 82        | 117    | 62.6%   |
| NVMe | 39        | 47     | 29.77%  |
| SAS  | 5         | 4      | 3.82%   |
| MMC  | 5         | 6      | 3.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 68     | 60.22%  |
| 0.51-1.0   | 35        | 48     | 37.63%  |
| 1.01-2.0   | 2         | 3      | 2.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 34.71%  |
| 251-500        | 30        | 24.79%  |
| 501-1000       | 21        | 17.36%  |
| 51-100         | 8         | 6.61%   |
| 1001-2000      | 7         | 5.79%   |
| 21-50          | 6         | 4.96%   |
| Unknown        | 3         | 2.48%   |
| 1-20           | 2         | 1.65%   |
| More than 3000 | 1         | 0.83%   |
| 2001-3000      | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 31        | 25.83%  |
| 101-250   | 28        | 23.33%  |
| 21-50     | 25        | 20.83%  |
| 51-100    | 20        | 16.67%  |
| 251-500   | 9         | 7.5%    |
| 501-1000  | 3         | 2.5%    |
| Unknown   | 3         | 2.5%    |
| 1001-2000 | 1         | 0.83%   |

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
| Detected | 60        | 89     | 47.24%  |
| Works    | 57        | 74     | 44.88%  |
| Malfunc  | 10        | 11     | 7.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 92        | 67.15%  |
| Samsung Electronics          | 20        | 14.6%   |
| AMD                          | 7         | 5.11%   |
| Sandisk                      | 5         | 3.65%   |
| Toshiba America Info Systems | 4         | 2.92%   |
| SK Hynix                     | 4         | 2.92%   |
| Realtek Semiconductor        | 1         | 0.73%   |
| Phison Electronics           | 1         | 0.73%   |
| Micron/Crucial Technology    | 1         | 0.73%   |
| Micron Technology            | 1         | 0.73%   |
| ADATA Technology             | 1         | 0.73%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 16        | 11.19%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 10.49%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 9.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 6.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 4.9%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 4.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 4.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.1%    |
| Intel SSD 660P Series                                                            | 3         | 2.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 2.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.1%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 1.4%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 1.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.4%    |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.4%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.7%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.7%    |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.7%    |
| SK Hynix BC511                                                                   | 1         | 0.7%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.7%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.7%    |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.7%    |
| Phison E12 NVMe Controller                                                       | 1         | 0.7%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.7%    |
| Micron Non-Volatile memory controller                                            | 1         | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.7%    |
| Intel Non-Volatile memory controller                                             | 1         | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 0.7%    |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.7%    |
| ADATA Non-Volatile memory controller                                             | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 89        | 64.03%  |
| NVMe | 40        | 28.78%  |
| RAID | 7         | 5.04%   |
| IDE  | 3         | 2.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 106       | 89.83%  |
| AMD    | 12        | 10.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 4.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 3.39%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 3.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 3.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.54%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 2.54%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 2.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 2.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.69%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.69%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.69%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.69%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.69%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.85%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.85%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.85%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.85%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.85%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 0.85%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.85%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.85%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.85%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.85%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.85%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.85%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.85%   |
| Intel Core i7-3517U CPU @ 1.90GHz             | 1         | 0.85%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.85%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.85%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.85%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.85%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 54        | 45.76%  |
| Intel Core i5           | 29        | 24.58%  |
| Intel Core i3           | 8         | 6.78%   |
| AMD Ryzen 5             | 5         | 4.24%   |
| Other                   | 4         | 3.39%   |
| Intel Core 2 Duo        | 4         | 3.39%   |
| Intel Pentium           | 3         | 2.54%   |
| AMD Ryzen 7             | 3         | 2.54%   |
| Intel Celeron           | 2         | 1.69%   |
| Intel Pentium Dual-Core | 1         | 0.85%   |
| Intel Core m5           | 1         | 0.85%   |
| AMD Ryzen 9             | 1         | 0.85%   |
| AMD Quad-Core           | 1         | 0.85%   |
| AMD A8                  | 1         | 0.85%   |
| AMD A6                  | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 52        | 44.07%  |
| 4      | 50        | 42.37%  |
| 6      | 12        | 10.17%  |
| 8      | 3         | 2.54%   |
| 16     | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 84.75%  |
| 1      | 18        | 15.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 118       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 13        | 10.57%  |
| Unknown    | 12        | 9.76%   |
| 0x306a9    | 11        | 8.94%   |
| 0x906ea    | 9         | 7.32%   |
| 0x806ec    | 8         | 6.5%    |
| 0x40651    | 7         | 5.69%   |
| 0x806ea    | 6         | 4.88%   |
| 0x806e9    | 5         | 4.07%   |
| 0x406e3    | 5         | 4.07%   |
| 0x806c1    | 4         | 3.25%   |
| 0x306c3    | 4         | 3.25%   |
| 0x906e9    | 3         | 2.44%   |
| 0x406c3    | 3         | 2.44%   |
| 0x306d4    | 3         | 2.44%   |
| 0x08600103 | 3         | 2.44%   |
| 0xa0652    | 2         | 1.63%   |
| 0x806eb    | 2         | 1.63%   |
| 0x506e3    | 2         | 1.63%   |
| 0x20655    | 2         | 1.63%   |
| 0x20652    | 2         | 1.63%   |
| 0x1067a    | 2         | 1.63%   |
| 0x10676    | 2         | 1.63%   |
| 0x08108109 | 2         | 1.63%   |
| 0xa0660    | 1         | 0.81%   |
| 0x706e5    | 1         | 0.81%   |
| 0x6fb      | 1         | 0.81%   |
| 0x406c4    | 1         | 0.81%   |
| 0x08701013 | 1         | 0.81%   |
| 0x08600106 | 1         | 0.81%   |
| 0x08600102 | 1         | 0.81%   |
| 0x0810100b | 1         | 0.81%   |
| 0x07030105 | 1         | 0.81%   |
| 0x0700010f | 1         | 0.81%   |
| 0x06001119 | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 39        | 33.05%  |
| SandyBridge | 13        | 11.02%  |
| IvyBridge   | 12        | 10.17%  |
| Haswell     | 11        | 9.32%   |
| Skylake     | 7         | 5.93%   |
| Zen 2       | 6         | 5.08%   |
| Westmere    | 4         | 3.39%   |
| TigerLake   | 4         | 3.39%   |
| Silvermont  | 4         | 3.39%   |
| Penryn      | 4         | 3.39%   |
| CometLake   | 3         | 2.54%   |
| Broadwell   | 3         | 2.54%   |
| Zen+        | 2         | 1.69%   |
| Zen         | 1         | 0.85%   |
| Puma        | 1         | 0.85%   |
| Piledriver  | 1         | 0.85%   |
| Jaguar      | 1         | 0.85%   |
| IceLake     | 1         | 0.85%   |
| Core        | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 100       | 61.35%  |
| Nvidia | 43        | 26.38%  |
| AMD    | 20        | 12.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 7.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 6.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 6.02%   |
| Intel UHD Graphics 620                                                                   | 7         | 4.22%   |
| Intel HD Graphics 620                                                                    | 7         | 4.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 4.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 4.22%   |
| AMD Renoir                                                                               | 5         | 3.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.41%   |
| Intel HD Graphics 630                                                                    | 4         | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.81%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.81%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 1.2%    |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.2%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.2%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.2%    |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.2%    |
| Intel HD Graphics 530                                                                    | 2         | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.2%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.2%    |
| AMD Picasso                                                                              | 2         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.6%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.6%    |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.6%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.6%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.6%    |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.6%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.6%    |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.6%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.6%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.6%    |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.6%    |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.6%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.6%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.6%    |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.6%    |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.6%    |
| Nvidia GK107M [GeForce GT 640M LE]                                                       | 1         | 0.6%    |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.6%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.6%    |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.6%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.6%    |
| Intel HD Graphics 515                                                                    | 1         | 0.6%    |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.6%    |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 48.31%  |
| Intel + Nvidia | 35        | 29.66%  |
| 1 x AMD        | 9         | 7.63%   |
| Intel + AMD    | 8         | 6.78%   |
| 1 x Nvidia     | 6         | 5.08%   |
| AMD + Nvidia   | 2         | 1.69%   |
| 2 x AMD        | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 83        | 70.34%  |
| Proprietary | 32        | 27.12%  |
| Unknown     | 3         | 2.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 60.17%  |
| 1.01-2.0   | 19        | 16.1%   |
| 3.01-4.0   | 8         | 6.78%   |
| 0.51-1.0   | 7         | 5.93%   |
| 0.01-0.5   | 6         | 5.08%   |
| 7.01-8.0   | 3         | 2.54%   |
| 5.01-6.0   | 3         | 2.54%   |
| 2.01-3.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 26        | 17.69%  |
| Chimei Innolux          | 25        | 17.01%  |
| AU Optronics            | 22        | 14.97%  |
| Samsung Electronics     | 15        | 10.2%   |
| BOE                     | 10        | 6.8%    |
| Dell                    | 7         | 4.76%   |
| Hewlett-Packard         | 5         | 3.4%    |
| Chi Mei Optoelectronics | 5         | 3.4%    |
| Goldstar                | 4         | 2.72%   |
| Acer                    | 3         | 2.04%   |
| Sharp                   | 2         | 1.36%   |
| Philips                 | 2         | 1.36%   |
| PANDA                   | 2         | 1.36%   |
| LGD                     | 2         | 1.36%   |
| InfoVision              | 2         | 1.36%   |
| BenQ                    | 2         | 1.36%   |
| Apple                   | 2         | 1.36%   |
| Ancor Communications    | 2         | 1.36%   |
| UPD                     | 1         | 0.68%   |
| Unknown                 | 1         | 0.68%   |
| Lenovo                  | 1         | 0.68%   |
| KTC                     | 1         | 0.68%   |
| JDI                     | 1         | 0.68%   |
| Fujitsu Siemens         | 1         | 0.68%   |
| Eizo                    | 1         | 0.68%   |
| CSO                     | 1         | 0.68%   |
| AOC                     | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 1.32%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2         | 1.32%   |
| LGD LCD Monitor 1920x1080                                              | 2         | 1.32%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 2         | 1.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch       | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch        | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch          | 2         | 1.32%   |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                       | 1         | 0.66%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1366x768            | 1         | 0.66%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.66%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                | 1         | 0.66%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch   | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC324C 1366x768 353x198mm 15.9-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 340x190mm 15.3-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC3150 1920x1080 344x194mm 15.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1020x570mm 46.0-inch | 1         | 0.66%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 1         | 0.66%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                | 1         | 0.66%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 1         | 0.66%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD061A 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0615 1920x1080 382x215mm 17.3-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD05F5 1920x1080 309x174mm 14.0-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD056D 1920x1080 380x210mm 17.1-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD04A5 1920x1280 253x169mm 12.0-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD02D9 1920x1080 350x190mm 15.7-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD027B 1600x900 382x215mm 17.3-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD0214 1600x900 345x194mm 15.6-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD01E1 1366x768 310x174mm 14.0-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch            | 1         | 0.66%   |
| Lenovo LT1952p Wide LEN0990 1440x900 408x255mm 18.9-inch               | 1         | 0.66%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                | 1         | 0.66%   |
| KTC 42 TV KTC4200 1920x1080 983x576mm 44.9-inch                        | 1         | 0.66%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                  | 1         | 0.66%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch           | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 61        | 45.52%  |
| 1366x768 (WXGA)   | 42        | 31.34%  |
| 2560x1440 (QHD)   | 6         | 4.48%   |
| 1600x900 (HD+)    | 6         | 4.48%   |
| 1280x800 (WXGA)   | 4         | 2.99%   |
| 3840x2160 (4K)    | 3         | 2.24%   |
| 1920x1200 (WUXGA) | 3         | 2.24%   |
| 1440x900 (WXGA+)  | 2         | 1.49%   |
| 3840x2400         | 1         | 0.75%   |
| 3000x2000         | 1         | 0.75%   |
| 2880x1800         | 1         | 0.75%   |
| 1920x1280         | 1         | 0.75%   |
| 1600x1200         | 1         | 0.75%   |
| 1360x768          | 1         | 0.75%   |
| 1280x1024 (SXGA)  | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 56        | 37.33%  |
| 13      | 19        | 12.67%  |
| 14      | 18        | 12%     |
| 24      | 9         | 6%      |
| 27      | 8         | 5.33%   |
| 17      | 8         | 5.33%   |
| 23      | 6         | 4%      |
| 12      | 5         | 3.33%   |
| 31      | 3         | 2%      |
| 21      | 3         | 2%      |
| 11      | 3         | 2%      |
| Unknown | 3         | 2%      |
| 19      | 2         | 1.33%   |
| 54      | 1         | 0.67%   |
| 48      | 1         | 0.67%   |
| 44      | 1         | 0.67%   |
| 32      | 1         | 0.67%   |
| 29      | 1         | 0.67%   |
| 22      | 1         | 0.67%   |
| 18      | 1         | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 82        | 56.16%  |
| 501-600     | 19        | 13.01%  |
| 201-300     | 16        | 10.96%  |
| 351-400     | 12        | 8.22%   |
| 401-500     | 6         | 4.11%   |
| 601-700     | 4         | 2.74%   |
| Unknown     | 3         | 2.05%   |
| 1001-1500   | 2         | 1.37%   |
| 701-800     | 1         | 0.68%   |
| 901-1000    | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 105       | 84.68%  |
| 16/10   | 12        | 9.68%   |
| Unknown | 3         | 2.42%   |
| 3/2     | 2         | 1.61%   |
| 5/4     | 1         | 0.81%   |
| 4/3     | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 56        | 37.58%  |
| 81-90          | 30        | 20.13%  |
| 201-250        | 16        | 10.74%  |
| 301-350        | 8         | 5.37%   |
| 71-80          | 7         | 4.7%    |
| 121-130        | 7         | 4.7%    |
| 61-70          | 5         | 3.36%   |
| 351-500        | 5         | 3.36%   |
| 51-60          | 3         | 2.01%   |
| Unknown        | 3         | 2.01%   |
| More than 1000 | 2         | 1.34%   |
| 251-300        | 2         | 1.34%   |
| 151-200        | 2         | 1.34%   |
| 141-150        | 1         | 0.67%   |
| 131-140        | 1         | 0.67%   |
| 501-1000       | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 40.14%  |
| 101-120       | 43        | 30.28%  |
| 51-100        | 28        | 19.72%  |
| More than 240 | 5         | 3.52%   |
| 1-50          | 4         | 2.82%   |
| Unknown       | 3         | 2.11%   |
| 161-240       | 2         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 90        | 74.38%  |
| 2     | 23        | 19.01%  |
| 3     | 6         | 4.96%   |
| 0     | 2         | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 75        | 38.86%  |
| Realtek Semiconductor    | 64        | 33.16%  |
| Qualcomm Atheros         | 30        | 15.54%  |
| Broadcom                 | 9         | 4.66%   |
| Ralink                   | 4         | 2.07%   |
| Marvell Technology Group | 3         | 1.55%   |
| Broadcom Limited         | 3         | 1.55%   |
| Hewlett-Packard          | 2         | 1.04%   |
| Sierra Wireless          | 1         | 0.52%   |
| NetGear                  | 1         | 0.52%   |
| Lenovo                   | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 17.3%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 5.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 5.06%   |
| Intel Wireless 8265 / 8275                                        | 10        | 4.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.38%   |
| Intel Wireless 8260                                               | 7         | 2.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.27%   |
| Intel Wireless-AC 9260                                            | 3         | 1.27%   |
| Intel Wireless 3165                                               | 3         | 1.27%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.84%   |
| Intel Wireless 7265                                               | 2         | 0.84%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.84%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.84%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.42%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.42%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.42%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.42%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.42%   |
| Realtek 802.11ac NIC                                              | 1         | 0.42%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.42%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.42%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 0.42%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.42%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.42%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.42%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.42%   |
| Intel Wireless 7260                                               | 1         | 0.42%   |
| Intel Wireless 3160                                               | 1         | 0.42%   |
| Intel WiFi Link 5100                                              | 1         | 0.42%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 72        | 58.06%  |
| Qualcomm Atheros      | 23        | 18.55%  |
| Realtek Semiconductor | 12        | 9.68%   |
| Broadcom              | 8         | 6.45%   |
| Ralink                | 4         | 3.23%   |
| Broadcom Limited      | 3         | 2.42%   |
| Sierra Wireless       | 1         | 0.81%   |
| NetGear               | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13        | 10.4%   |
| Intel Wireless 8265 / 8275                                     | 10        | 8%      |
| Intel Wireless 8260                                            | 7         | 5.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 4.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 3.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 3.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 3.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.4%    |
| Intel Wireless-AC 9260                                         | 3         | 2.4%    |
| Intel Wireless 3165                                            | 3         | 2.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2.4%    |
| Intel Centrino Ultimate-N 6300                                 | 3         | 2.4%    |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 2.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.6%    |
| Intel Wireless 7265                                            | 2         | 1.6%    |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.6%    |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.8%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.8%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.8%    |
| Realtek 802.11ac NIC                                           | 1         | 0.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.8%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.8%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 0.8%    |
| Intel Wireless 7260                                            | 1         | 0.8%    |
| Intel Wireless 3160                                            | 1         | 0.8%    |
| Intel WiFi Link 5100                                           | 1         | 0.8%    |
| Intel Wi-Fi 6 AX201                                            | 1         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.8%    |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.8%    |
| Intel Centrino Wireless-N 2200                                 | 1         | 0.8%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.8%    |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.8%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.8%    |
| Broadcom Limited BCM43224 802.11a/b/g/n                        | 1         | 0.8%    |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 0.8%    |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 0.8%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 59        | 54.13%  |
| Intel                    | 31        | 28.44%  |
| Qualcomm Atheros         | 11        | 10.09%  |
| Marvell Technology Group | 3         | 2.75%   |
| Broadcom                 | 3         | 2.75%   |
| Lenovo                   | 1         | 0.92%   |
| Hewlett-Packard          | 1         | 0.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 36.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 10.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 9.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 7.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.7%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.7%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.8%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.8%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.8%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.9%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.9%    |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.9%    |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.9%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.9%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.9%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.9%    |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.9%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.9%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.9%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.9%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 52.91%  |
| Ethernet | 104       | 46.64%  |
| Modem    | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 64.16%  |
| Ethernet | 62        | 35.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 85.59%  |
| 1     | 17        | 14.41%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 112       | 92.56%  |
| Yes  | 9         | 7.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 52.53%  |
| Qualcomm Atheros Communications | 10        | 10.1%   |
| Lite-On Technology              | 8         | 8.08%   |
| Broadcom                        | 8         | 8.08%   |
| Realtek Semiconductor           | 5         | 5.05%   |
| Foxconn / Hon Hai               | 3         | 3.03%   |
| Dell                            | 3         | 3.03%   |
| Ralink                          | 2         | 2.02%   |
| Hewlett-Packard                 | 2         | 2.02%   |
| Apple                           | 2         | 2.02%   |
| Toshiba                         | 1         | 1.01%   |
| Realtek                         | 1         | 1.01%   |
| IMC Networks                    | 1         | 1.01%   |
| Cambridge Silicon Radio         | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 18.18%  |
| Intel Bluetooth Device                                                              | 18        | 18.18%  |
| Intel AX200 Bluetooth                                                               | 12        | 12.12%  |
| Lite-On Bluetooth Device                                                            | 5         | 5.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 4.04%   |
| Realtek Bluetooth Radio                                                             | 3         | 3.03%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 3.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 3.03%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.02%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 2.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.02%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.02%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.01%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.01%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.01%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 1.01%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 1.01%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.01%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.01%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.01%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.01%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 1.01%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.01%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.01%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.01%   |
| Broadcom BCM20702A0                                                                 | 1         | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.01%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.01%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.01%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 106       | 67.95%  |
| Nvidia                    | 21        | 13.46%  |
| AMD                       | 14        | 8.97%   |
| Realtek Semiconductor     | 4         | 2.56%   |
| Kingston Technology       | 2         | 1.28%   |
| GN Netcom                 | 2         | 1.28%   |
| Sennheiser Communications | 1         | 0.64%   |
| Razer USA                 | 1         | 0.64%   |
| Plantronics               | 1         | 0.64%   |
| Lenovo                    | 1         | 0.64%   |
| JMTek                     | 1         | 0.64%   |
| Hewlett-Packard           | 1         | 0.64%   |
| C-Media Electronics       | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 10.61%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 7.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 6.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 5.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 4.47%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 8         | 4.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.91%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.91%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.23%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 2.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.23%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.68%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.68%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.12%   |
| Sennheiser Communications Sennheiser DECT for Lync                                                | 1         | 0.56%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.56%   |
| Plantronics C320-M                                                                                | 1         | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 0.56%   |
| Kingston Technology HyperX Cloud Stinger Wireless                                                 | 1         | 0.56%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.56%   |
| JMTek USB Audio Device                                                                            | 1         | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.56%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.56%   |
| Hewlett-Packard USB Audio                                                                         | 1         | 0.56%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.56%   |
| GN Netcom Jabra EVOLVE 65                                                                         | 1         | 0.56%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.56%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.56%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 31.46%  |
| SK Hynix            | 25        | 28.09%  |
| Micron Technology   | 11        | 12.36%  |
| Kingston            | 5         | 5.62%   |
| Crucial             | 5         | 5.62%   |
| Unknown             | 3         | 3.37%   |
| A-DATA Technology   | 3         | 3.37%   |
| Smart               | 2         | 2.25%   |
| Ramaxel Technology  | 2         | 2.25%   |
| Teikon              | 1         | 1.12%   |
| SMART Brazil        | 1         | 1.12%   |
| Elpida              | 1         | 1.12%   |
| Corsair             | 1         | 1.12%   |
| ASint Technology    | 1         | 1.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 3         | 3.09%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s      | 3         | 3.09%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s       | 3         | 3.09%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 2         | 2.06%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s      | 2         | 2.06%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s     | 2         | 2.06%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s      | 2         | 2.06%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s          | 2         | 2.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 2.06%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 2         | 2.06%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s       | 2         | 2.06%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s      | 2         | 2.06%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16384MB SODIMM DDR4 2667MT/s      | 2         | 2.06%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                      | 1         | 1.03%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1.03%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 1.03%   |
| Unknown RAM Module 2048MB SODIMM DDR3                          | 1         | 1.03%   |
| Teikon RAM TMT451S6BFR8A-PBAJ 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.03%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s          | 1         | 1.03%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.03%   |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.03%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 1.03%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s              | 1         | 1.03%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s               | 1         | 1.03%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.03%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.03%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.03%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.03%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 1.03%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.03%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s      | 1         | 1.03%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s         | 1         | 1.03%   |
| SK Hynix RAM HMT125S6AFR8C-G7 2048MB SODIMM DDR3 1067MT/s      | 1         | 1.03%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 1.03%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1.03%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 1.03%   |
| SK Hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s         | 1         | 1.03%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s     | 1         | 1.03%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s     | 1         | 1.03%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.03%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.03%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.03%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1         | 1.03%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s       | 1         | 1.03%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s       | 1         | 1.03%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s       | 1         | 1.03%   |
| Samsung RAM M471B5173BH0-YK0 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.03%   |
| Samsung RAM M471B2874EH1-CF8 1024MB SODIMM 1067MT/s            | 1         | 1.03%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 1         | 1.03%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s      | 1         | 1.03%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s      | 1         | 1.03%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.03%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s       | 1         | 1.03%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.03%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s | 1         | 1.03%   |
| Ramaxel RAM RMT3160ED58E9W1600 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.03%   |
| Ramaxel RAM RMSA3260NA78HAF-2400 8GB SODIMM DDR4 2400MT/s      | 1         | 1.03%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 1.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 41        | 51.9%   |
| DDR3   | 32        | 40.51%  |
| SDRAM  | 3         | 3.8%    |
| LPDDR4 | 1         | 1.27%   |
| LPDDR3 | 1         | 1.27%   |
| DDR2   | 1         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 97.33%  |
| Row Of Chips | 2         | 2.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 33        | 39.29%  |
| 8192  | 25        | 29.76%  |
| 16384 | 16        | 19.05%  |
| 2048  | 5         | 5.95%   |
| 32768 | 3         | 3.57%   |
| 1024  | 2         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 25        | 29.07%  |
| 1600    | 23        | 26.74%  |
| 3200    | 6         | 6.98%   |
| 2133    | 6         | 6.98%   |
| 2400    | 5         | 5.81%   |
| 1334    | 5         | 5.81%   |
| 1333    | 5         | 5.81%   |
| 1067    | 4         | 4.65%   |
| 4199    | 3         | 3.49%   |
| 3266    | 1         | 1.16%   |
| 1867    | 1         | 1.16%   |
| 667     | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

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
| Chicony Electronics                    | 29        | 27.36%  |
| Realtek Semiconductor                  | 11        | 10.38%  |
| Acer                                   | 11        | 10.38%  |
| Sunplus Innovation Technology          | 8         | 7.55%   |
| IMC Networks                           | 8         | 7.55%   |
| Microdia                               | 7         | 6.6%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 6.6%    |
| Quanta                                 | 5         | 4.72%   |
| Syntek                                 | 4         | 3.77%   |
| Silicon Motion                         | 4         | 3.77%   |
| Suyin                                  | 3         | 2.83%   |
| Lite-On Technology                     | 2         | 1.89%   |
| Apple                                  | 2         | 1.89%   |
| Ricoh                                  | 1         | 0.94%   |
| Primax Electronics                     | 1         | 0.94%   |
| LG Electronics                         | 1         | 0.94%   |
| Generalplus Technology                 | 1         | 0.94%   |
| Creative Technology                    | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                       | 6         | 5.66%   |
| Realtek Integrated_Webcam_HD                            | 5         | 4.72%   |
| Chicony Integrated Camera                               | 5         | 4.72%   |
| Microdia Integrated_Webcam_HD                           | 4         | 3.77%   |
| Chicony USB2.0 Camera                                   | 4         | 3.77%   |
| Chicony HP HD Camera                                    | 3         | 2.83%   |
| Suyin HP Truevision HD                                  | 2         | 1.89%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 1.89%   |
| Sunplus ASUS Webcam                                     | 2         | 1.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 2         | 1.89%   |
| IMC Networks Integrated Camera                          | 2         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.89%   |
| Acer HD Webcam                                          | 2         | 1.89%   |
| Acer BisonCam,NB Pro                                    | 2         | 1.89%   |
| Acer BisonCam, NB Pro                                   | 2         | 1.89%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                    | 1         | 0.94%   |
| Syntek USB2.0 Camera                                    | 1         | 0.94%   |
| Syntek Integrated Camera                                | 1         | 0.94%   |
| Syntek EasyCamera                                       | 1         | 0.94%   |
| Suyin HD WebCam                                         | 1         | 0.94%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.94%   |
| Sunplus Laptop Integrated WebCam HD                     | 1         | 0.94%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.94%   |
| Sunplus ASUS USB2.0 Webcam                              | 1         | 0.94%   |
| Silicon Motion WebCam SC-13HDL12131N                    | 1         | 0.94%   |
| Silicon Motion WebCam SC-10HDD13335N                    | 1         | 0.94%   |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.94%   |
| Silicon Motion Web Camera                               | 1         | 0.94%   |
| Ricoh Sony Vaio Integrated Webcam                       | 1         | 0.94%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 0.94%   |
| Realtek USB2.0 HD UVC WebCam                            | 1         | 0.94%   |
| Realtek Integrated Webcam HD                            | 1         | 0.94%   |
| Realtek Integrated Webcam                               | 1         | 0.94%   |
| Realtek HP "Truevision HD" laptop camera                | 1         | 0.94%   |
| Realtek HD WebCam                                       | 1         | 0.94%   |
| Quanta VGA WebCam                                       | 1         | 0.94%   |
| Quanta LG Webcam                                        | 1         | 0.94%   |
| Quanta Laptop_Integrated_Webcam_2HDM                    | 1         | 0.94%   |
| Quanta HP TrueVision HD Camera                          | 1         | 0.94%   |
| Quanta HD User Facing                                   | 1         | 0.94%   |
| Primax HP HD Webcam [Fixed]                             | 1         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 1         | 0.94%   |
| Microdia Laptop Integrated Webcam HD (Composite Device) | 1         | 0.94%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 0.94%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 0.94%   |
| Lite-On HP HD Webcam                                    | 1         | 0.94%   |
| LG G2/G3 Android Phone [MTP/PTP/Download mode]          | 1         | 0.94%   |
| IMC Networks USB 2.0 Camera                             | 1         | 0.94%   |
| IMC Networks ov9734_azurewave_camera                    | 1         | 0.94%   |
| Generalplus GENERAL WEBCAM                              | 1         | 0.94%   |
| Creative Live! Cam Chat HD [VF0700]                     | 1         | 0.94%   |
| Chicony UVC 1.00 device HD UVC WebCam                   | 1         | 0.94%   |
| Chicony USB2.0 VGA UVC WebCam                           | 1         | 0.94%   |
| Chicony USB2.0 HD UVC WebCam                            | 1         | 0.94%   |
| Chicony USB 2.0 Webcam Device                           | 1         | 0.94%   |
| Chicony USB 2.0 Camera                                  | 1         | 0.94%   |
| Chicony thinkpad t430s camera                           | 1         | 0.94%   |
| Chicony Integrated HP HD Webcam                         | 1         | 0.94%   |
| Chicony Integrated Camera [ThinkPad]                    | 1         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 44.83%  |
| Synaptics                  | 9         | 31.03%  |
| Shenzhen Goodix Technology | 3         | 10.34%  |
| LighTuning Technology      | 2         | 6.9%    |
| Elan Microelectronics      | 1         | 3.45%   |
| AuthenTec                  | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 13.79%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 13.79%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 10.34%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 10.34%  |
| Unknown                                                                    | 3         | 10.34%  |
| Synaptics WBDI Device                                                      | 2         | 6.9%    |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 6.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 6.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.45%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.45%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.45%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.45%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 3.45%   |

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
| 0     | 63        | 52.94%  |
| 1     | 43        | 36.13%  |
| 2     | 11        | 9.24%   |
| 4     | 1         | 0.84%   |
| 3     | 1         | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 29        | 43.94%  |
| Chipcard                 | 11        | 16.67%  |
| Graphics card            | 10        | 15.15%  |
| Net/wireless             | 5         | 7.58%   |
| Communication controller | 4         | 6.06%   |
| Storage                  | 2         | 3.03%   |
| Bluetooth                | 2         | 3.03%   |
| Net/ethernet             | 1         | 1.52%   |
| Card reader              | 1         | 1.52%   |
| Camera                   | 1         | 1.52%   |


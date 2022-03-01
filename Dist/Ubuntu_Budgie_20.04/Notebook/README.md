Ubuntu Budgie 20.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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
| ASUSTek  | UX303UA                     | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| TUXEDO   | InfinityBook S 15 Gen6      | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| Apple    | MacBookPro4,1               | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer    | Blade Stealth               | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer    | Blade Stealth               | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP       | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP       | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple    | MacBookPro11,5              | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer     | Aspire 8940G                | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| Sony     | SVS13A25PBS                 | [9072890c1d](https://linux-hardware.org/?probe=9072890c1d) | Feb 02, 2022 |
| Sony     | SVS13A25PBS                 | [894e40654e](https://linux-hardware.org/?probe=894e40654e) | Feb 02, 2022 |
| HP       | Laptop 15s-fq1xxx           | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo   | V145-15AST 81MT             | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| TUXEDO   | Book XP1511                 | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO   | Pulse 15 Gen1               | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| HP       | EliteBook 8570w             | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| HP       | EliteBook 8570w             | [249a326a8b](https://linux-hardware.org/?probe=249a326a8b) | Jan 17, 2022 |
| HP       | EliteBook 8570w             | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| HP       | EliteBook 8570w             | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| Lenovo   | V145-15AST 81MT             | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo   | V145-15AST 81MT             | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| TUXEDO   | Polaris AMD Gen3 (CZN)      | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| TUXEDO   | Unknown                     | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo   | V310-15ISK 80SY             | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO   | Unknown                     | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer     | Swift SF314-52              | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| HP       | Pavilion dm1                | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| TUXEDO   | Polaris 15 AMD Gen1         | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO   | Polaris 15 AMD Gen1         | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo   | ThinkPad W530 244743G       | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| TUXEDO   | P95_HP                      | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell     | Vostro 1700                 | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Unknown  | Unknown                     | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Dell     | Inspiron 5515               | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
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
| 5.4.0-42-generic           | 16        | 10.13%  |
| 5.4.0-40-generic           | 9         | 5.7%    |
| 5.4.0-37-generic           | 6         | 3.8%    |
| 5.4.0-29-generic           | 6         | 3.8%    |
| 5.4.0-52-generic           | 5         | 3.16%   |
| 5.4.0-48-generic           | 5         | 3.16%   |
| 5.4.0-33-generic           | 5         | 3.16%   |
| 5.8.0-53-generic           | 4         | 2.53%   |
| 5.4.0-58-generic           | 4         | 2.53%   |
| 5.4.0-31-generic           | 4         | 2.53%   |
| 5.13.0-28-generic          | 4         | 2.53%   |
| 5.8.0-48-generic           | 3         | 1.9%    |
| 5.4.0-91-generic           | 3         | 1.9%    |
| 5.4.0-73-generic           | 3         | 1.9%    |
| 5.4.0-28-generic           | 3         | 1.9%    |
| 5.11.0-41-generic          | 3         | 1.9%    |
| 5.11.0-27-generic          | 3         | 1.9%    |
| 5.8.0-49-generic           | 2         | 1.27%   |
| 5.8.0-45-generic           | 2         | 1.27%   |
| 5.8.0-44-generic           | 2         | 1.27%   |
| 5.4.0-80-generic           | 2         | 1.27%   |
| 5.4.0-72-generic           | 2         | 1.27%   |
| 5.4.0-66-generic           | 2         | 1.27%   |
| 5.4.0-65-generic           | 2         | 1.27%   |
| 5.4.0-60-generic           | 2         | 1.27%   |
| 5.4.0-59-generic           | 2         | 1.27%   |
| 5.4.0-56-generic           | 2         | 1.27%   |
| 5.4.0-47-generic           | 2         | 1.27%   |
| 5.4.0-26-generic           | 2         | 1.27%   |
| 5.9.0-050900rc6-lowlatency | 1         | 0.63%   |
| 5.8.11-050811-generic      | 1         | 0.63%   |
| 5.8.0-63-generic           | 1         | 0.63%   |
| 5.8.0-59-generic           | 1         | 0.63%   |
| 5.8.0-50-generic           | 1         | 0.63%   |
| 5.8.0-43-generic           | 1         | 0.63%   |
| 5.8.0-41-generic           | 1         | 0.63%   |
| 5.6.7-050607-generic       | 1         | 0.63%   |
| 5.6.0-1048-oem             | 1         | 0.63%   |
| 5.6.0-1042-oem             | 1         | 0.63%   |
| 5.6.0-1034-oem             | 1         | 0.63%   |
| 5.5.0-2.1-liquorix-amd64   | 1         | 0.63%   |
| 5.4.0-97-generic           | 1         | 0.63%   |
| 5.4.0-94-generic           | 1         | 0.63%   |
| 5.4.0-92-generic           | 1         | 0.63%   |
| 5.4.0-89-generic           | 1         | 0.63%   |
| 5.4.0-77-generic           | 1         | 0.63%   |
| 5.4.0-74-generic           | 1         | 0.63%   |
| 5.4.0-62-generic           | 1         | 0.63%   |
| 5.4.0-61-generic           | 1         | 0.63%   |
| 5.4.0-55-generic           | 1         | 0.63%   |
| 5.4.0-54-generic           | 1         | 0.63%   |
| 5.4.0-51-generic           | 1         | 0.63%   |
| 5.4.0-48-lowlatency        | 1         | 0.63%   |
| 5.4.0-45-generic           | 1         | 0.63%   |
| 5.4.0-44-generic           | 1         | 0.63%   |
| 5.4.0-41-generic           | 1         | 0.63%   |
| 5.4.0-30-generic           | 1         | 0.63%   |
| 5.4.0-25-generic           | 1         | 0.63%   |
| 5.4.0-21-generic           | 1         | 0.63%   |
| 5.4.0-18-generic           | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 96        | 65.75%  |
| 5.8.0   | 18        | 12.33%  |
| 5.11.0  | 13        | 8.9%    |
| 5.13.0  | 6         | 4.11%   |
| 5.6.0   | 3         | 2.05%   |
| 5.3.0   | 2         | 1.37%   |
| 5.9.0   | 1         | 0.68%   |
| 5.8.11  | 1         | 0.68%   |
| 5.6.7   | 1         | 0.68%   |
| 5.5.0   | 1         | 0.68%   |
| 5.15.11 | 1         | 0.68%   |
| 5.12.0  | 1         | 0.68%   |
| 5.10.11 | 1         | 0.68%   |
| 5.10.0  | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 96        | 65.75%  |
| 5.8     | 19        | 13.01%  |
| 5.11    | 13        | 8.9%    |
| 5.13    | 6         | 4.11%   |
| 5.6     | 4         | 2.74%   |
| 5.3     | 2         | 1.37%   |
| 5.10    | 2         | 1.37%   |
| 5.9     | 1         | 0.68%   |
| 5.5     | 1         | 0.68%   |
| 5.15    | 1         | 0.68%   |
| 5.12    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 143       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 140       | 97.9%   |
| GNOME  | 2         | 1.4%    |
| XFCE   | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 137       | 95.8%   |
| Wayland | 6         | 4.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 60        | 41.67%  |
| TDM     | 33        | 22.92%  |
| LightDM | 30        | 20.83%  |
| GDM     | 19        | 13.19%  |
| GDM3    | 2         | 1.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 40        | 27.78%  |
| de_DE   | 22        | 15.28%  |
| pt_BR   | 13        | 9.03%   |
| fr_FR   | 10        | 6.94%   |
| en_GB   | 10        | 6.94%   |
| ru_RU   | 6         | 4.17%   |
| en_CA   | 6         | 4.17%   |
| en_IN   | 4         | 2.78%   |
| it_IT   | 3         | 2.08%   |
| es_ES   | 3         | 2.08%   |
| pt_PT   | 2         | 1.39%   |
| fi_FI   | 2         | 1.39%   |
| es_AR   | 2         | 1.39%   |
| en_AU   | 2         | 1.39%   |
| de_CH   | 2         | 1.39%   |
| C       | 2         | 1.39%   |
| zh_CN   | 1         | 0.69%   |
| pl_PL   | 1         | 0.69%   |
| nl_NL   | 1         | 0.69%   |
| nb_NO   | 1         | 0.69%   |
| id_ID   | 1         | 0.69%   |
| hu_HU   | 1         | 0.69%   |
| fr_CH   | 1         | 0.69%   |
| es_US   | 1         | 0.69%   |
| es_SV   | 1         | 0.69%   |
| es_MX   | 1         | 0.69%   |
| es_GT   | 1         | 0.69%   |
| es_CL   | 1         | 0.69%   |
| en_SG   | 1         | 0.69%   |
| de_AT   | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 104       | 70.75%  |
| BIOS | 43        | 29.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 133       | 93.01%  |
| Zfs     | 5         | 3.5%    |
| Overlay | 2         | 1.4%    |
| Xfs     | 1         | 0.7%    |
| Jfs     | 1         | 0.7%    |
| Btrfs   | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 69        | 48.25%  |
| GPT     | 56        | 39.16%  |
| MBR     | 18        | 12.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 132       | 91.03%  |
| Yes       | 13        | 8.97%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 67.83%  |
| Yes       | 46        | 32.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 28        | 19.58%  |
| TUXEDO              | 21        | 14.69%  |
| Lenovo              | 20        | 13.99%  |
| Dell                | 19        | 13.29%  |
| ASUSTek Computer    | 16        | 11.19%  |
| Acer                | 13        | 9.09%   |
| MSI                 | 7         | 4.9%    |
| Samsung Electronics | 4         | 2.8%    |
| Apple               | 4         | 2.8%    |
| Sony                | 2         | 1.4%    |
| HUAWEI              | 2         | 1.4%    |
| Toshiba             | 1         | 0.7%    |
| Standard            | 1         | 0.7%    |
| Razer               | 1         | 0.7%    |
| Quanta              | 1         | 0.7%    |
| Gigabyte Technology | 1         | 0.7%    |
| Fujitsu             | 1         | 0.7%    |
| Unknown             | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 5         | 3.5%    |
| TUXEDO Polaris 15 AMD Gen1                            | 2         | 1.4%    |
| TUXEDO InfinityBook S 15 Gen6                         | 2         | 1.4%    |
| HP ZBook Studio G3                                    | 2         | 1.4%    |
| HP Pavilion g6                                        | 2         | 1.4%    |
| HP Notebook                                           | 2         | 1.4%    |
| Dell Latitude 5400                                    | 2         | 1.4%    |
| Acer TravelMate P446-M                                | 2         | 1.4%    |
| TUXEDO TUXEDO_Book_XA1510                             | 1         | 0.7%    |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.7%    |
| TUXEDO Polaris AMD Gen3 (CZN)                         | 1         | 0.7%    |
| TUXEDO Polaris 17 AMD Gen1                            | 1         | 0.7%    |
| TUXEDO P95_HR                                         | 1         | 0.7%    |
| TUXEDO P95_HP                                         | 1         | 0.7%    |
| TUXEDO P7xxTM1                                        | 1         | 0.7%    |
| TUXEDO InfinityBook S 14 Gen6                         | 1         | 0.7%    |
| TUXEDO InfinityBook Pro 15 v4                         | 1         | 0.7%    |
| TUXEDO InfinityBook Pro 14 Gen6                       | 1         | 0.7%    |
| TUXEDO Book XP1511                                    | 1         | 0.7%    |
| TUXEDO Book XP15 / XP17 Gen12                         | 1         | 0.7%    |
| TUXEDO Aura 15 Gen1                                   | 1         | 0.7%    |
| Toshiba Satellite P300                                | 1         | 0.7%    |
| Standard MT40II                                       | 1         | 0.7%    |
| Sony VPCCW25FL                                        | 1         | 0.7%    |
| Sony SVS13A25PBS                                      | 1         | 0.7%    |
| Samsung 905S3G/906S3G/915S3G/9305SG                   | 1         | 0.7%    |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.7%    |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.7%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.7%    |
| Razer Blade Stealth                                   | 1         | 0.7%    |
| Quanta R460-L.BG22P1                                  | 1         | 0.7%    |
| MSI Prestige 15 A10SC                                 | 1         | 0.7%    |
| MSI Modern 14 A10RB                                   | 1         | 0.7%    |
| MSI GP73 Leopard 8RE                                  | 1         | 0.7%    |
| MSI GP72 7RE                                          | 1         | 0.7%    |
| MSI GL62M 7RD                                         | 1         | 0.7%    |
| MSI GE70 2PC\2PE                                      | 1         | 0.7%    |
| MSI CX62 6QL                                          | 1         | 0.7%    |
| Lenovo V310-15ISK 80SY                                | 1         | 0.7%    |
| Lenovo V145-15AST 81MT                                | 1         | 0.7%    |
| Lenovo ThinkPad X260 20F5S2HF06                       | 1         | 0.7%    |
| Lenovo ThinkPad X230 23257G6                          | 1         | 0.7%    |
| Lenovo ThinkPad X230 2306CTO                          | 1         | 0.7%    |
| Lenovo ThinkPad W530 2447GW3                          | 1         | 0.7%    |
| Lenovo ThinkPad W530 244743G                          | 1         | 0.7%    |
| Lenovo ThinkPad T430s 23539WU                         | 1         | 0.7%    |
| Lenovo ThinkPad T430 2349P74                          | 1         | 0.7%    |
| Lenovo ThinkPad T410 2537H21                          | 1         | 0.7%    |
| Lenovo ThinkPad P53 20QQS1JE00                        | 1         | 0.7%    |
| Lenovo ThinkPad P43s 20RHS00100                       | 1         | 0.7%    |
| Lenovo ThinkPad P43s 20RH0013US                       | 1         | 0.7%    |
| Lenovo ThinkPad P1 20MES01400                         | 1         | 0.7%    |
| Lenovo ThinkPad E490 20N8S07A00                       | 1         | 0.7%    |
| Lenovo IdeaPad S145-15IWL 81S9                        | 1         | 0.7%    |
| Lenovo IdeaPad 5 15ARE05 81YQ                         | 1         | 0.7%    |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.7%    |
| Lenovo G550 2958                                      | 1         | 0.7%    |
| Lenovo 20SL                                           | 1         | 0.7%    |
| HUAWEI MACH-WX9                                       | 1         | 0.7%    |
| HUAWEI BOHK-WAX9X                                     | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 9.09%   |
| Acer Aspire            | 10        | 6.99%   |
| Dell Latitude          | 9         | 6.29%   |
| HP Pavilion            | 6         | 4.2%    |
| HP EliteBook           | 6         | 4.2%    |
| Dell Inspiron          | 6         | 4.2%    |
| TUXEDO InfinityBook    | 5         | 3.5%    |
| Unknown                | 5         | 3.5%    |
| TUXEDO Polaris         | 4         | 2.8%    |
| HP Laptop              | 4         | 2.8%    |
| Lenovo IdeaPad         | 3         | 2.1%    |
| HP ProBook             | 3         | 2.1%    |
| TUXEDO P95             | 2         | 1.4%    |
| TUXEDO Book            | 2         | 1.4%    |
| HP ZBook               | 2         | 1.4%    |
| HP Notebook            | 2         | 1.4%    |
| HP ENVY                | 2         | 1.4%    |
| Dell XPS               | 2         | 1.4%    |
| Acer TravelMate        | 2         | 1.4%    |
| TUXEDO TUXEDO          | 1         | 0.7%    |
| TUXEDO Pulse           | 1         | 0.7%    |
| TUXEDO P7xxTM1         | 1         | 0.7%    |
| TUXEDO Aura            | 1         | 0.7%    |
| Toshiba Satellite      | 1         | 0.7%    |
| Standard MT40II        | 1         | 0.7%    |
| Sony VPCCW25FL         | 1         | 0.7%    |
| Sony SVS13A25PBS       | 1         | 0.7%    |
| Samsung 905S3G         | 1         | 0.7%    |
| Samsung 530U3C         | 1         | 0.7%    |
| Samsung 340XAA         | 1         | 0.7%    |
| Samsung 300E5EV        | 1         | 0.7%    |
| Razer Blade            | 1         | 0.7%    |
| Quanta R460-L.BG22P1   | 1         | 0.7%    |
| MSI Prestige           | 1         | 0.7%    |
| MSI Modern             | 1         | 0.7%    |
| MSI GP73               | 1         | 0.7%    |
| MSI GP72               | 1         | 0.7%    |
| MSI GL62M              | 1         | 0.7%    |
| MSI GE70               | 1         | 0.7%    |
| MSI CX62               | 1         | 0.7%    |
| Lenovo V310-15ISK      | 1         | 0.7%    |
| Lenovo V145-15AST      | 1         | 0.7%    |
| Lenovo G550            | 1         | 0.7%    |
| Lenovo 20SL            | 1         | 0.7%    |
| HUAWEI MACH-WX9        | 1         | 0.7%    |
| HUAWEI BOHK-WAX9X      | 1         | 0.7%    |
| HP x360                | 1         | 0.7%    |
| HP Elite               | 1         | 0.7%    |
| HP Compaq              | 1         | 0.7%    |
| Gigabyte GB-BKi7A-7500 | 1         | 0.7%    |
| Fujitsu LIFEBOOK       | 1         | 0.7%    |
| Dell G7                | 1         | 0.7%    |
| Dell G3                | 1         | 0.7%    |
| ASUS ZenBook           | 1         | 0.7%    |
| ASUS X551CA            | 1         | 0.7%    |
| ASUS X540LA            | 1         | 0.7%    |
| ASUS X510UNR           | 1         | 0.7%    |
| ASUS X510UAR           | 1         | 0.7%    |
| ASUS X302LJ            | 1         | 0.7%    |
| ASUS VivoBook          | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 20        | 13.99%  |
| 2018 | 18        | 12.59%  |
| 2020 | 17        | 11.89%  |
| 2016 | 13        | 9.09%   |
| 2012 | 13        | 9.09%   |
| 2011 | 12        | 8.39%   |
| 2017 | 11        | 7.69%   |
| 2015 | 7         | 4.9%    |
| 2014 | 7         | 4.9%    |
| 2013 | 7         | 4.9%    |
| 2009 | 5         | 3.5%    |
| 2008 | 5         | 3.5%    |
| 2021 | 4         | 2.8%    |
| 2010 | 4         | 2.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 143       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 125       | 87.41%  |
| Enabled  | 18        | 12.59%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 143       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 45        | 31.03%  |
| 16.01-24.0  | 33        | 22.76%  |
| 8.01-16.0   | 26        | 17.93%  |
| 3.01-4.0    | 18        | 12.41%  |
| 32.01-64.0  | 14        | 9.66%   |
| 64.01-256.0 | 6         | 4.14%   |
| 2.01-3.0    | 2         | 1.38%   |
| 1.01-2.0    | 1         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 46        | 30.26%  |
| 1.01-2.0  | 36        | 23.68%  |
| 4.01-8.0  | 32        | 21.05%  |
| 3.01-4.0  | 29        | 19.08%  |
| 8.01-16.0 | 9         | 5.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 102       | 71.33%  |
| 2      | 38        | 26.57%  |
| 3      | 3         | 2.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 67.36%  |
| Yes       | 47        | 32.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 86.71%  |
| No        | 19        | 13.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 84.72%  |
| No        | 22        | 15.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 26        | 18.18%  |
| Brazil             | 15        | 10.49%  |
| USA                | 11        | 7.69%   |
| France             | 9         | 6.29%   |
| Russia             | 7         | 4.9%    |
| Italy              | 6         | 4.2%    |
| UK                 | 4         | 2.8%    |
| Spain              | 4         | 2.8%    |
| Poland             | 4         | 2.8%    |
| Netherlands        | 4         | 2.8%    |
| India              | 4         | 2.8%    |
| Finland            | 4         | 2.8%    |
| Canada             | 4         | 2.8%    |
| Ukraine            | 3         | 2.1%    |
| Iran               | 3         | 2.1%    |
| Turkey             | 2         | 1.4%    |
| Switzerland        | 2         | 1.4%    |
| South Africa       | 2         | 1.4%    |
| Portugal           | 2         | 1.4%    |
| Norway             | 2         | 1.4%    |
| Indonesia          | 2         | 1.4%    |
| Hungary            | 2         | 1.4%    |
| Austria            | 2         | 1.4%    |
| Australia          | 2         | 1.4%    |
| Argentina          | 2         | 1.4%    |
| Slovenia           | 1         | 0.7%    |
| Singapore          | 1         | 0.7%    |
| Mexico             | 1         | 0.7%    |
| Malaysia           | 1         | 0.7%    |
| Kenya              | 1         | 0.7%    |
| Japan              | 1         | 0.7%    |
| Hong Kong          | 1         | 0.7%    |
| Honduras           | 1         | 0.7%    |
| Guatemala          | 1         | 0.7%    |
| El Salvador        | 1         | 0.7%    |
| Ecuador            | 1         | 0.7%    |
| Dominican Republic | 1         | 0.7%    |
| Colombia           | 1         | 0.7%    |
| Chile              | 1         | 0.7%    |
| Belgium            | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Tehran                    | 3         | 2.03%   |
| SГЈo Paulo              | 3         | 2.03%   |
| Stuttgart                 | 3         | 2.03%   |
| Ravensburg                | 3         | 2.03%   |
| Paris                     | 3         | 2.03%   |
| Moscow                    | 3         | 2.03%   |
| Munich                    | 2         | 1.35%   |
| Montreal                  | 2         | 1.35%   |
| Los Angeles               | 2         | 1.35%   |
| Kyiv                      | 2         | 1.35%   |
| Budapest                  | 2         | 1.35%   |
| BrasГ­lia               | 2         | 1.35%   |
| Belo Horizonte            | 2         | 1.35%   |
| Zheleznodorozhnyy         | 1         | 0.68%   |
| Zabrze                    | 1         | 0.68%   |
| Yuma                      | 1         | 0.68%   |
| Wolfsburg                 | 1         | 0.68%   |
| Woking                    | 1         | 0.68%   |
| Wilchingen, Osterfingen   | 1         | 0.68%   |
| Waterloo                  | 1         | 0.68%   |
| Warsaw                    | 1         | 0.68%   |
| Villingen-Schwenningen    | 1         | 0.68%   |
| Vienna                    | 1         | 0.68%   |
| Vicente Lopez             | 1         | 0.68%   |
| Vantaa                    | 1         | 0.68%   |
| Tuttlingen                | 1         | 0.68%   |
| Tuscola                   | 1         | 0.68%   |
| Turku                     | 1         | 0.68%   |
| Totana                    | 1         | 0.68%   |
| Tokyo                     | 1         | 0.68%   |
| Tiel                      | 1         | 0.68%   |
| The Hague                 | 1         | 0.68%   |
| Teresina                  | 1         | 0.68%   |
| Tangerang                 | 1         | 0.68%   |
| SГЈo LuГ­s            | 1         | 0.68%   |
| SГЈo JosГ© dos Campos | 1         | 0.68%   |
| Sydney                    | 1         | 0.68%   |
| St Petersburg             | 1         | 0.68%   |
| Spilimbergo               | 1         | 0.68%   |
| Skien                     | 1         | 0.68%   |
| Singapore                 | 1         | 0.68%   |
| Sens                      | 1         | 0.68%   |
| Santo Domingo Este        | 1         | 0.68%   |
| SantarГ©m               | 1         | 0.68%   |
| Santa Tecla               | 1         | 0.68%   |
| San Pedro Sula            | 1         | 0.68%   |
| Salt Lake City            | 1         | 0.68%   |
| Salamanca                 | 1         | 0.68%   |
| Saint-Medard-de-Guizieres | 1         | 0.68%   |
| Saint-Junien              | 1         | 0.68%   |
| Rostov-on-Don             | 1         | 0.68%   |
| Quito                     | 1         | 0.68%   |
| Povoa de Lanhoso          | 1         | 0.68%   |
| Ponte San Pietro          | 1         | 0.68%   |
| Penzberg                  | 1         | 0.68%   |
| Parma                     | 1         | 0.68%   |
| Ovalle                    | 1         | 0.68%   |
| Oswestry                  | 1         | 0.68%   |
| Oslo                      | 1         | 0.68%   |
| Osasco                    | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives  | Percent |
|---------------------------|-----------|---------|---------|
| Samsung Electronics       | 49        | 63      | 27.07%  |
| Seagate                   | 20        | 22      | 11.05%  |
| Toshiba                   | 19        | 21      | 10.5%   |
| WDC                       | 16        | 18      | 8.84%   |
| SanDisk                   | 11        | 12      | 6.08%   |
| Unknown                   | 8         | 9       | 4.42%   |
| Crucial                   | 7         | 7       | 3.87%   |
| Kingston                  | 6         | 6       | 3.31%   |
| HGST                      | 6         | 9       | 3.31%   |
| SK Hynix                  | 5         | 5       | 2.76%   |
| Micron Technology         | 5         | 7       | 2.76%   |
| Intel                     | 5         | 6       | 2.76%   |
| Hitachi                   | 4         | 4       | 2.21%   |
| A-DATA Technology         | 4         | 5       | 2.21%   |
| PNY                       | 3         | 5       | 1.66%   |
| LITEON                    | 2         | 2       | 1.1%    |
| China                     | 2         | 2       | 1.1%    |
| Vaseky                    | 1         | 1       | 0.55%   |
| USB30                     | 1         | 1       | 0.55%   |
| Micron/Crucial Technology | 1         | 1       | 0.55%   |
| KingSpec                  | 1         | 1       | 0.55%   |
| KimMiDi                   | 1         | 1       | 0.55%   |
| Hewlett-Packard           | 1         | Unknown | 0.55%   |
| GALAX TA                  | 1         | 1       | 0.55%   |
| Corsair                   | 1         | 1       | 0.55%   |
| Apple                     | 1         | 1       | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 4         | 2.14%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 2.14%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 2.14%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.6%    |
| Samsung SSD 750 EVO 250GB            | 3         | 1.6%    |
| Samsung NVMe SSD Drive 250GB         | 3         | 1.6%    |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 1.07%   |
| Unknown MMC Card  32GB               | 2         | 1.07%   |
| SK Hynix NVMe SSD Drive 256GB        | 2         | 1.07%   |
| Seagate ST9500325AS 500GB            | 2         | 1.07%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 1.07%   |
| Seagate BUP Slim BK 1TB              | 2         | 1.07%   |
| SanDisk SSD PLUS 120GB               | 2         | 1.07%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 1.07%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.07%   |
| Samsung SSD 970 EVO 500GB            | 2         | 1.07%   |
| Samsung SSD 860 EVO M.2 250GB        | 2         | 1.07%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.07%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 1.07%   |
| Samsung MZVLB256HAHQ-00000 256GB     | 2         | 1.07%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 1.07%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 1.07%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.07%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.07%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.53%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.53%   |
| WDC WDS100T2B0A 1TB SSD              | 1         | 0.53%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.53%   |
| WDC WD1600BEVS-08VAT2 160GB          | 1         | 0.53%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 0.53%   |
| WDC WD10SPZX-35Z10T0 1TB             | 1         | 0.53%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.53%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.53%   |
| WDC WD10SPZX-17Z10T0 1TB             | 1         | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.53%   |
| WDC PC SN720 SDAQNTW-256G-1001 256GB | 1         | 0.53%   |
| WDC PC SN520 NVMe 512GB              | 1         | 0.53%   |
| Vaseky V800/120G 120GB SSD           | 1         | 0.53%   |
| USB30 Disk 500GB                     | 1         | 0.53%   |
| Unknown SD64G  64GB                  | 1         | 0.53%   |
| Unknown SD/MMC/MS PRO 64GB           | 1         | 0.53%   |
| Unknown NVMe SSD Drive 512GB         | 1         | 0.53%   |
| Unknown MMC Card  64GB               | 1         | 0.53%   |
| Unknown MMC Card  2GB                | 1         | 0.53%   |
| Unknown MMC Card  16GB               | 1         | 0.53%   |
| Unknown 00000  2GB                   | 1         | 0.53%   |
| Toshiba THNSNJ512G8NY 512GB SSD      | 1         | 0.53%   |
| Toshiba NVMe SSD Drive 512GB         | 1         | 0.53%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.53%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.53%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.53%   |
| Toshiba MQ01ABF032 320GB             | 1         | 0.53%   |
| Toshiba MK7559GSXF 752GB             | 1         | 0.53%   |
| Toshiba MK6461GSYN 640GB             | 1         | 0.53%   |
| Toshiba MK5055GSX 500GB              | 1         | 0.53%   |
| Toshiba MK2561GSYN 250GB             | 1         | 0.53%   |
| Toshiba MK2552GSX 250GB              | 1         | 0.53%   |
| Toshiba KXG60ZNV256G NVMe 256GB      | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 20     | 33.96%  |
| Toshiba | 14        | 16     | 26.42%  |
| WDC     | 10        | 11     | 18.87%  |
| HGST    | 6         | 9      | 11.32%  |
| Hitachi | 4         | 4      | 7.55%   |
| Unknown | 1         | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 30     | 35.29%  |
| SanDisk             | 8         | 8      | 11.76%  |
| Crucial             | 6         | 6      | 8.82%   |
| Kingston            | 5         | 5      | 7.35%   |
| WDC                 | 4         | 5      | 5.88%   |
| PNY                 | 3         | 5      | 4.41%   |
| Micron Technology   | 3         | 5      | 4.41%   |
| A-DATA Technology   | 3         | 4      | 4.41%   |
| LITEON              | 2         | 2      | 2.94%   |
| China               | 2         | 2      | 2.94%   |
| Vaseky              | 1         | 1      | 1.47%   |
| USB30               | 1         | 1      | 1.47%   |
| Toshiba             | 1         | 1      | 1.47%   |
| SK Hynix            | 1         | 1      | 1.47%   |
| Seagate             | 1         | 1      | 1.47%   |
| KingSpec            | 1         | 1      | 1.47%   |
| Intel               | 1         | 1      | 1.47%   |
| Apple               | 1         | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 64        | 80     | 36.99%  |
| HDD     | 50        | 61     | 28.9%   |
| NVMe    | 49        | 60     | 28.32%  |
| MMC     | 6         | 7      | 3.47%   |
| Unknown | 4         | 3      | 2.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 97        | 137    | 60.63%  |
| NVMe | 49        | 60     | 30.63%  |
| SAS  | 8         | 7      | 5%      |
| MMC  | 6         | 7      | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 86     | 62.73%  |
| 0.51-1.0   | 38        | 51     | 34.55%  |
| 1.01-2.0   | 3         | 4      | 2.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 32.19%  |
| 251-500        | 38        | 26.03%  |
| 501-1000       | 27        | 18.49%  |
| 51-100         | 10        | 6.85%   |
| 21-50          | 8         | 5.48%   |
| 1001-2000      | 8         | 5.48%   |
| Unknown        | 3         | 2.05%   |
| 2001-3000      | 2         | 1.37%   |
| 1-20           | 2         | 1.37%   |
| More than 3000 | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 40        | 27.21%  |
| 101-250   | 34        | 23.13%  |
| 21-50     | 29        | 19.73%  |
| 51-100    | 22        | 14.97%  |
| 251-500   | 12        | 8.16%   |
| 501-1000  | 6         | 4.08%   |
| Unknown   | 3         | 2.04%   |
| 1001-2000 | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 18.18%  |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 9.09%   |
| Toshiba MK5055GSX 500GB             | 1         | 1      | 9.09%   |
| Toshiba MK2561GSYN 250GB            | 1         | 1      | 9.09%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 9.09%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 9.09%   |
| PNY SSD2SC120G3LC709B121-460I 120GB | 1         | 1      | 9.09%   |
| HGST HTS725032A7E630 320GB          | 1         | 2      | 9.09%   |
| Crucial CT500P1SSD8 500GB           | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 45.45%  |
| Seagate | 3         | 3      | 27.27%  |
| PNY     | 1         | 1      | 9.09%   |
| HGST    | 1         | 2      | 9.09%   |
| Crucial | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 55.56%  |
| Seagate | 3         | 3      | 33.33%  |
| HGST    | 1         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 81.82%  |
| NVMe | 1         | 1      | 9.09%   |
| SSD  | 1         | 1      | 9.09%   |

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
| Detected | 74        | 108    | 47.74%  |
| Works    | 70        | 91     | 45.16%  |
| Malfunc  | 11        | 12     | 7.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 109       | 64.12%  |
| Samsung Electronics          | 29        | 17.06%  |
| AMD                          | 10        | 5.88%   |
| Sandisk                      | 5         | 2.94%   |
| Toshiba America Info Systems | 4         | 2.35%   |
| SK Hynix                     | 4         | 2.35%   |
| Micron/Crucial Technology    | 2         | 1.18%   |
| Micron Technology            | 2         | 1.18%   |
| Silicon Motion               | 1         | 0.59%   |
| Realtek Semiconductor        | 1         | 0.59%   |
| Phison Electronics           | 1         | 0.59%   |
| Kingston Technology Company  | 1         | 0.59%   |
| ADATA Technology             | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 12.43%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 19        | 10.73%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 9.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 6.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 5.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 3.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 6         | 3.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 2.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.69%   |
| Intel SSD 660P Series                                                            | 3         | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.69%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 1.13%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 1.13%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.13%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 1.13%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.13%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.13%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.13%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.56%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.56%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.56%   |
| SK Hynix BC511                                                                   | 1         | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.56%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.56%   |
| Samsung Electronics SATA controller                                              | 1         | 0.56%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.56%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.56%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.56%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.56%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.56%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 0.56%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.56%   |
| ADATA Non-Volatile memory controller                                             | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 109       | 63.37%  |
| NVMe | 51        | 29.65%  |
| RAID | 8         | 4.65%   |
| IDE  | 4         | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 126       | 88.11%  |
| AMD    | 17        | 11.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 4.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 3.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 3.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 2.8%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 2.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 2.1%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 2.1%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 2.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 2.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.1%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 2.1%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 2.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.4%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.4%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.4%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.4%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.4%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.4%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.4%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.4%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.7%    |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.7%    |
| Intel Genuine CPU U2300 @ 1.20GHz             | 1         | 0.7%    |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.7%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 0.7%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.7%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.7%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.7%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 0.7%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.7%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.7%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.7%    |
| Intel Core i7-3820QM CPU @ 2.70GHz            | 1         | 0.7%    |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.7%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.7%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.7%    |
| Intel Core i7-3517U CPU @ 1.90GHz             | 1         | 0.7%    |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 0.7%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.7%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.7%    |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.7%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.7%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.7%    |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.7%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 64        | 44.76%  |
| Intel Core i5           | 33        | 23.08%  |
| Intel Core i3           | 11        | 7.69%   |
| AMD Ryzen 5             | 7         | 4.9%    |
| Other                   | 5         | 3.5%    |
| Intel Core 2 Duo        | 5         | 3.5%    |
| AMD Ryzen 7             | 5         | 3.5%    |
| Intel Pentium           | 3         | 2.1%    |
| Intel Celeron           | 2         | 1.4%    |
| AMD A6                  | 2         | 1.4%    |
| Intel Pentium Dual-Core | 1         | 0.7%    |
| Intel Genuine           | 1         | 0.7%    |
| Intel Core m5           | 1         | 0.7%    |
| AMD Ryzen 9             | 1         | 0.7%    |
| AMD Quad-Core           | 1         | 0.7%    |
| AMD A8                  | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 62        | 43.36%  |
| 4      | 60        | 41.96%  |
| 6      | 14        | 9.79%   |
| 8      | 6         | 4.2%    |
| 16     | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 143       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 121       | 84.62%  |
| 1      | 22        | 15.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 143       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 10.14%  |
| 0x206a7    | 14        | 9.46%   |
| 0x306a9    | 13        | 8.78%   |
| 0x906ea    | 9         | 6.08%   |
| 0x806ec    | 9         | 6.08%   |
| 0x806ea    | 7         | 4.73%   |
| 0x406e3    | 7         | 4.73%   |
| 0x40651    | 7         | 4.73%   |
| 0x806e9    | 6         | 4.05%   |
| 0x806c1    | 5         | 3.38%   |
| 0x08600103 | 5         | 3.38%   |
| 0xa0652    | 4         | 2.7%    |
| 0x906e9    | 4         | 2.7%    |
| 0x306c3    | 4         | 2.7%    |
| 0x406c3    | 3         | 2.03%   |
| 0x306d4    | 3         | 2.03%   |
| 0x1067a    | 3         | 2.03%   |
| 0x10676    | 3         | 2.03%   |
| 0x806eb    | 2         | 1.35%   |
| 0x706e5    | 2         | 1.35%   |
| 0x506e3    | 2         | 1.35%   |
| 0x20655    | 2         | 1.35%   |
| 0x20652    | 2         | 1.35%   |
| 0x08108109 | 2         | 1.35%   |
| 0xa0660    | 1         | 0.68%   |
| 0x6fb      | 1         | 0.68%   |
| 0x406c4    | 1         | 0.68%   |
| 0x40661    | 1         | 0.68%   |
| 0x106e5    | 1         | 0.68%   |
| 0x0a50000c | 1         | 0.68%   |
| 0x08701013 | 1         | 0.68%   |
| 0x08608103 | 1         | 0.68%   |
| 0x08600106 | 1         | 0.68%   |
| 0x08600102 | 1         | 0.68%   |
| 0x0810100b | 1         | 0.68%   |
| 0x07030105 | 1         | 0.68%   |
| 0x0700010f | 1         | 0.68%   |
| 0x06006705 | 1         | 0.68%   |
| 0x06001119 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 45        | 31.47%  |
| SandyBridge | 14        | 9.79%   |
| IvyBridge   | 14        | 9.79%   |
| Haswell     | 12        | 8.39%   |
| Skylake     | 9         | 6.29%   |
| Zen 2       | 8         | 5.59%   |
| Penryn      | 6         | 4.2%    |
| TigerLake   | 5         | 3.5%    |
| CometLake   | 5         | 3.5%    |
| Westmere    | 4         | 2.8%    |
| Silvermont  | 4         | 2.8%    |
| IceLake     | 3         | 2.1%    |
| Broadwell   | 3         | 2.1%    |
| Zen+        | 2         | 1.4%    |
| Zen 3       | 1         | 0.7%    |
| Zen         | 1         | 0.7%    |
| Puma        | 1         | 0.7%    |
| Piledriver  | 1         | 0.7%    |
| Nehalem     | 1         | 0.7%    |
| Jaguar      | 1         | 0.7%    |
| Excavator   | 1         | 0.7%    |
| Core        | 1         | 0.7%    |
| Unknown     | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 59.49%  |
| Nvidia | 52        | 26.67%  |
| AMD    | 27        | 13.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 6.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 6.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 5.56%   |
| Intel UHD Graphics 620                                                                   | 9         | 4.55%   |
| Intel HD Graphics 620                                                                    | 8         | 4.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.54%   |
| AMD Renoir                                                                               | 7         | 3.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.53%   |
| Intel HD Graphics 630                                                                    | 5         | 2.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 2.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.52%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.52%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.52%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.52%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.52%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.01%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 1.01%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.01%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.01%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.01%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 1.01%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.01%   |
| Intel HD Graphics 530                                                                    | 2         | 1.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.01%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.51%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.51%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.51%   |
| Nvidia GT215M [GeForce GTS 250M]                                                         | 1         | 0.51%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.51%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.51%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.51%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.51%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.51%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.51%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.51%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.51%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.51%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.51%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.51%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.51%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.51%   |
| Nvidia GK107M [GeForce GT 640M LE]                                                       | 1         | 0.51%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.51%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.51%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.51%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.51%   |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 47.55%  |
| Intel + Nvidia | 40        | 27.97%  |
| 1 x AMD        | 14        | 9.79%   |
| 1 x Nvidia     | 8         | 5.59%   |
| Intel + AMD    | 8         | 5.59%   |
| AMD + Nvidia   | 4         | 2.8%    |
| 2 x AMD        | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 104       | 72.22%  |
| Proprietary | 37        | 25.69%  |
| Unknown     | 3         | 2.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 85        | 58.62%  |
| 1.01-2.0   | 21        | 14.48%  |
| 0.01-0.5   | 10        | 6.9%    |
| 3.01-4.0   | 9         | 6.21%   |
| 0.51-1.0   | 9         | 6.21%   |
| 5.01-6.0   | 6         | 4.14%   |
| 7.01-8.0   | 4         | 2.76%   |
| 2.01-3.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 31        | 17.51%  |
| LG Display              | 29        | 16.38%  |
| AU Optronics            | 26        | 14.69%  |
| Samsung Electronics     | 15        | 8.47%   |
| BOE                     | 15        | 8.47%   |
| Dell                    | 9         | 5.08%   |
| Chi Mei Optoelectronics | 6         | 3.39%   |
| Hewlett-Packard         | 5         | 2.82%   |
| Sharp                   | 4         | 2.26%   |
| Goldstar                | 4         | 2.26%   |
| Apple                   | 4         | 2.26%   |
| PANDA                   | 3         | 1.69%   |
| Lenovo                  | 3         | 1.69%   |
| Acer                    | 3         | 1.69%   |
| Philips                 | 2         | 1.13%   |
| LGD                     | 2         | 1.13%   |
| InfoVision              | 2         | 1.13%   |
| BenQ                    | 2         | 1.13%   |
| Ancor Communications    | 2         | 1.13%   |
| UPD                     | 1         | 0.56%   |
| Unknown                 | 1         | 0.56%   |
| KTC                     | 1         | 0.56%   |
| JDI                     | 1         | 0.56%   |
| InnoLux Display         | 1         | 0.56%   |
| Iiyama                  | 1         | 0.56%   |
| Fujitsu Siemens         | 1         | 0.56%   |
| Eizo                    | 1         | 0.56%   |
| CSO                     | 1         | 0.56%   |
| AOC                     | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 1.66%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch       | 3         | 1.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 3         | 1.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 1.1%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2         | 1.1%    |
| LGD LCD Monitor 1920x1080                                              | 2         | 1.1%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 2         | 1.1%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch        | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO13ED 1920x1080 340x190mm 15.3-inch         | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch          | 2         | 1.1%    |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                       | 1         | 0.55%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1366x768            | 1         | 0.55%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.55%   |
| Sharp LQ133Z1JW26 SHP1493 3200x1800 294x165mm 13.3-inch                | 1         | 0.55%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.55%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                | 1         | 0.55%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch      | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch   | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC3150 1920x1080 344x194mm 15.5-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0C3C 1360x768 609x347mm 27.6-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch  | 1         | 0.55%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 0.55%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                | 1         | 0.55%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 1         | 0.55%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD061A 1920x1080 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0615 1920x1080 382x215mm 17.3-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD05F5 1920x1080 309x174mm 14.0-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD04A5 1920x1280 253x169mm 12.0-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD02D9 1920x1080 345x194mm 15.6-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD027B 1600x900 382x215mm 17.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD0214 1600x900 344x194mm 15.5-inch            | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 79        | 48.77%  |
| 1366x768 (WXGA)   | 45        | 27.78%  |
| 2560x1440 (QHD)   | 8         | 4.94%   |
| 1600x900 (HD+)    | 6         | 3.7%    |
| 1440x900 (WXGA+)  | 4         | 2.47%   |
| 1280x800 (WXGA)   | 4         | 2.47%   |
| 3840x2160 (4K)    | 3         | 1.85%   |
| 1920x1200 (WUXGA) | 3         | 1.85%   |
| 2880x1800         | 2         | 1.23%   |
| 3840x2400         | 1         | 0.62%   |
| 3200x1800 (QHD+)  | 1         | 0.62%   |
| 3000x2000         | 1         | 0.62%   |
| 2256x1504         | 1         | 0.62%   |
| 1920x1280         | 1         | 0.62%   |
| 1600x1200         | 1         | 0.62%   |
| 1360x768          | 1         | 0.62%   |
| 1280x1024 (SXGA)  | 1         | 0.62%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 70        | 38.89%  |
| 13      | 25        | 13.89%  |
| 14      | 20        | 11.11%  |
| 24      | 12        | 6.67%   |
| 27      | 9         | 5%      |
| 17      | 9         | 5%      |
| 23      | 6         | 3.33%   |
| 12      | 5         | 2.78%   |
| 11      | 4         | 2.22%   |
| Unknown | 4         | 2.22%   |
| 31      | 3         | 1.67%   |
| 21      | 3         | 1.67%   |
| 19      | 2         | 1.11%   |
| 18      | 2         | 1.11%   |
| 54      | 1         | 0.56%   |
| 48      | 1         | 0.56%   |
| 44      | 1         | 0.56%   |
| 32      | 1         | 0.56%   |
| 29      | 1         | 0.56%   |
| 22      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 57.39%  |
| 501-600     | 23        | 13.07%  |
| 201-300     | 20        | 11.36%  |
| 351-400     | 13        | 7.39%   |
| 401-500     | 7         | 3.98%   |
| 601-700     | 4         | 2.27%   |
| Unknown     | 4         | 2.27%   |
| 1001-1500   | 2         | 1.14%   |
| 701-800     | 1         | 0.57%   |
| 901-1000    | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 127       | 84.11%  |
| 16/10   | 15        | 9.93%   |
| Unknown | 4         | 2.65%   |
| 3/2     | 3         | 1.99%   |
| 5/4     | 1         | 0.66%   |
| 4/3     | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 70        | 39.11%  |
| 81-90          | 36        | 20.11%  |
| 201-250        | 17        | 9.5%    |
| 71-80          | 9         | 5.03%   |
| 301-350        | 9         | 5.03%   |
| 121-130        | 8         | 4.47%   |
| 61-70          | 5         | 2.79%   |
| 351-500        | 5         | 2.79%   |
| 51-60          | 4         | 2.23%   |
| 251-300        | 4         | 2.23%   |
| Unknown        | 4         | 2.23%   |
| More than 1000 | 2         | 1.12%   |
| 151-200        | 2         | 1.12%   |
| 141-150        | 2         | 1.12%   |
| 131-140        | 1         | 0.56%   |
| 501-1000       | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 42.44%  |
| 101-120       | 48        | 27.91%  |
| 51-100        | 31        | 18.02%  |
| More than 240 | 6         | 3.49%   |
| 161-240       | 6         | 3.49%   |
| 1-50          | 4         | 2.33%   |
| Unknown       | 4         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 111       | 76.03%  |
| 2     | 27        | 18.49%  |
| 3     | 6         | 4.11%   |
| 0     | 2         | 1.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 91        | 38.72%  |
| Realtek Semiconductor    | 79        | 33.62%  |
| Qualcomm Atheros         | 32        | 13.62%  |
| Broadcom                 | 12        | 5.11%   |
| Broadcom Limited         | 5         | 2.13%   |
| Ralink                   | 4         | 1.7%    |
| Marvell Technology Group | 4         | 1.7%    |
| Hewlett-Packard          | 3         | 1.28%   |
| Sierra Wireless          | 1         | 0.43%   |
| NetGear                  | 1         | 0.43%   |
| MEDIATEK                 | 1         | 0.43%   |
| Lenovo                   | 1         | 0.43%   |
| ASIX Electronics         | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 18.25%  |
| Intel Wi-Fi 6 AX200                                               | 19        | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 4.21%   |
| Intel Wireless 8265 / 8275                                        | 11        | 3.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 3.51%   |
| Intel Wireless 8260                                               | 7         | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.11%   |
| Intel Wireless-AC 9260                                            | 6         | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.4%    |
| Intel Wireless 7265                                               | 4         | 1.4%    |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.05%   |
| Intel Wireless 3165                                               | 3         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.05%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.7%    |
| Intel WiFi Link 5100                                              | 2         | 0.7%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.7%    |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.7%    |
| HP un2430 Mobile Broadband Module                                 | 2         | 0.7%    |
| Broadcom BCM4321 802.11a/b/g/n                                    | 2         | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.7%    |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.35%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.35%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.35%   |
| Realtek 802.11ac NIC                                              | 1         | 0.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.35%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.35%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 0.35%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.35%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 88        | 59.06%  |
| Qualcomm Atheros      | 25        | 16.78%  |
| Realtek Semiconductor | 15        | 10.07%  |
| Broadcom              | 10        | 6.71%   |
| Ralink                | 4         | 2.68%   |
| Broadcom Limited      | 4         | 2.68%   |
| Sierra Wireless       | 1         | 0.67%   |
| NetGear               | 1         | 0.67%   |
| MEDIATEK              | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 19        | 12.67%  |
| Intel Wireless 8265 / 8275                                     | 11        | 7.33%   |
| Intel Wireless 8260                                            | 7         | 4.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 4%      |
| Intel Wireless-AC 9260                                         | 6         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.67%   |
| Intel Wireless 7265                                            | 4         | 2.67%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 2.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2%      |
| Intel Wireless 3165                                            | 3         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2%      |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.33%   |
| Intel WiFi Link 5100                                           | 2         | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.33%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.33%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.33%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.67%   |
| Realtek 802.11ac NIC                                           | 1         | 0.67%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.67%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 0.67%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.67%   |
| Intel Wireless 7260                                            | 1         | 0.67%   |
| Intel Wireless 3160                                            | 1         | 0.67%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.67%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.67%   |
| Intel Centrino Wireless-N 2200                                 | 1         | 0.67%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.67%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.67%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                        | 1         | 0.67%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 0.67%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 0.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 0.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 55.81%  |
| Intel                    | 33        | 25.58%  |
| Qualcomm Atheros         | 11        | 8.53%   |
| Broadcom                 | 5         | 3.88%   |
| Marvell Technology Group | 4         | 3.1%    |
| Lenovo                   | 1         | 0.78%   |
| Hewlett-Packard          | 1         | 0.78%   |
| Broadcom Limited         | 1         | 0.78%   |
| ASIX Electronics         | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 39.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 9.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 9.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 7.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.26%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.26%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.5%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.75%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.75%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.75%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.75%   |
| HP HP lt4120 Snapdragon X5 LTE                                    | 1         | 0.75%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.75%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.75%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.75%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 143       | 53.16%  |
| Ethernet | 124       | 46.1%   |
| Modem    | 2         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 62.21%  |
| Ethernet | 81        | 37.33%  |
| Modem    | 1         | 0.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 120       | 83.92%  |
| 1     | 23        | 16.08%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 130       | 89.04%  |
| Yes  | 16        | 10.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 52.85%  |
| Broadcom                        | 10        | 8.13%   |
| Qualcomm Atheros Communications | 9         | 7.32%   |
| Realtek Semiconductor           | 8         | 6.5%    |
| Lite-On Technology              | 8         | 6.5%    |
| Foxconn / Hon Hai               | 4         | 3.25%   |
| Apple                           | 4         | 3.25%   |
| Hewlett-Packard                 | 3         | 2.44%   |
| Dell                            | 3         | 2.44%   |
| Ralink                          | 2         | 1.63%   |
| Qualcomm Atheros                | 2         | 1.63%   |
| IMC Networks                    | 2         | 1.63%   |
| Toshiba                         | 1         | 0.81%   |
| Realtek                         | 1         | 0.81%   |
| Cambridge Silicon Radio         | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 25        | 20.33%  |
| Intel AX200 Bluetooth                                                               | 18        | 14.63%  |
| Intel Bluetooth wireless interface                                                  | 9         | 7.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 4.88%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 4.07%   |
| Lite-On Bluetooth Device                                                            | 5         | 4.07%   |
| Realtek Bluetooth Radio                                                             | 4         | 3.25%   |
| Intel AX201 Bluetooth                                                               | 4         | 3.25%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.44%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 2.44%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 2.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 2.44%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.63%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.63%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.63%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.63%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.81%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.81%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.81%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.81%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.81%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.81%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.81%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.81%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.81%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.81%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.81%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.81%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.81%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.81%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 126       | 64.62%  |
| Nvidia                    | 29        | 14.87%  |
| AMD                       | 21        | 10.77%  |
| Realtek Semiconductor     | 6         | 3.08%   |
| Kingston Technology       | 2         | 1.03%   |
| GN Netcom                 | 2         | 1.03%   |
| Sennheiser Communications | 1         | 0.51%   |
| Razer USA                 | 1         | 0.51%   |
| Plantronics               | 1         | 0.51%   |
| Lenovo                    | 1         | 0.51%   |
| JMTek                     | 1         | 0.51%   |
| Hewlett-Packard           | 1         | 0.51%   |
| Generalplus Technology    | 1         | 0.51%   |
| Conexant Systems          | 1         | 0.51%   |
| C-Media Electronics       | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 10.86%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 7.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 5.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 4.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.17%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.17%   |
| Realtek Semiconductor USB Audio                                                                   | 6         | 2.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.26%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.81%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.81%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.36%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.36%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.36%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia Audio device                                                                               | 2         | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.9%    |
| Sennheiser Communications Sennheiser DECT for Lync                                                | 1         | 0.45%   |
| Razer USA Razer Kraken Tournament Edition                                                         | 1         | 0.45%   |
| Plantronics C320-M                                                                                | 1         | 0.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.45%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 0.45%   |
| Kingston Technology HyperX Cloud Stinger Wireless                                                 | 1         | 0.45%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.45%   |
| JMTek USB Audio Device                                                                            | 1         | 0.45%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.45%   |
| Hewlett-Packard USB Audio                                                                         | 1         | 0.45%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.45%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.45%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.45%   |
| Conexant Systems Hi Res USB-C AUDIO                                                               | 1         | 0.45%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 0.45%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.45%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.45%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.45%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 33.64%  |
| SK Hynix            | 27        | 25.23%  |
| Micron Technology   | 12        | 11.21%  |
| Kingston            | 6         | 5.61%   |
| Crucial             | 6         | 5.61%   |
| Unknown             | 3         | 2.8%    |
| Ramaxel Technology  | 3         | 2.8%    |
| A-DATA Technology   | 3         | 2.8%    |
| Smart               | 2         | 1.87%   |
| Unknown             | 2         | 1.87%   |
| Teikon              | 1         | 0.93%   |
| SMART Brazil        | 1         | 0.93%   |
| Nanya Technology    | 1         | 0.93%   |
| Kingmax             | 1         | 0.93%   |
| Elpida              | 1         | 0.93%   |
| Corsair             | 1         | 0.93%   |
| ASint Technology    | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 4         | 3.48%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s          | 4         | 3.48%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s          | 3         | 2.61%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s        | 3         | 2.61%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 1.74%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 1.74%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 2         | 1.74%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 2         | 1.74%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s       | 2         | 1.74%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s           | 2         | 1.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 1.74%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 2         | 1.74%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s          | 2         | 1.74%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s          | 2         | 1.74%   |
| Unknown                                                         | 2         | 1.74%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.87%   |
| Unknown RAM Module 4096MB SODIMM DDR3                           | 1         | 0.87%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                   | 1         | 0.87%   |
| Unknown RAM Module 2048MB SODIMM DDR3                           | 1         | 0.87%   |
| Teikon RAM TMT451S6BFR8A-PBAJ 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.87%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s        | 1         | 0.87%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s           | 1         | 0.87%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s           | 1         | 0.87%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s | 1         | 0.87%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s               | 1         | 0.87%   |
| SK Hynix RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.87%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                | 1         | 0.87%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.87%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMT125S6AFR8C-G7 2048MB SODIMM DDR3 1067MT/s       | 1         | 0.87%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s    | 1         | 0.87%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 0.87%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 0.87%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 0.87%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.87%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s          | 1         | 0.87%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.87%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 0.87%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s        | 1         | 0.87%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.87%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 0.87%   |
| Samsung RAM M471B2874EH1-CF8 1024MB SODIMM 1067MT/s             | 1         | 0.87%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s        | 1         | 0.87%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s          | 1         | 0.87%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 0.87%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 1         | 0.87%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 0.87%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 0.87%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 50        | 52.63%  |
| DDR3    | 35        | 36.84%  |
| SDRAM   | 3         | 3.16%   |
| LPDDR4  | 2         | 2.11%   |
| LPDDR3  | 2         | 2.11%   |
| DDR2    | 1         | 1.05%   |
| DDR     | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 95.6%   |
| Row Of Chips | 4         | 4.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 37        | 36.63%  |
| 8192  | 32        | 31.68%  |
| 16384 | 19        | 18.81%  |
| 2048  | 6         | 5.94%   |
| 32768 | 5         | 4.95%   |
| 1024  | 2         | 1.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 28        | 27.18%  |
| 1600    | 25        | 24.27%  |
| 3200    | 11        | 10.68%  |
| 2133    | 7         | 6.8%    |
| 1333    | 7         | 6.8%    |
| 2400    | 6         | 5.83%   |
| 1334    | 6         | 5.83%   |
| 1067    | 4         | 3.88%   |
| 4199    | 3         | 2.91%   |
| 667     | 2         | 1.94%   |
| 3733    | 1         | 0.97%   |
| 3266    | 1         | 0.97%   |
| 1867    | 1         | 0.97%   |
| Unknown | 1         | 0.97%   |

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
| Chicony Electronics                    | 39        | 29.77%  |
| Acer                                   | 15        | 11.45%  |
| Realtek Semiconductor                  | 12        | 9.16%   |
| Sunplus Innovation Technology          | 11        | 8.4%    |
| Microdia                               | 8         | 6.11%   |
| IMC Networks                           | 8         | 6.11%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.34%   |
| Silicon Motion                         | 5         | 3.82%   |
| Quanta                                 | 5         | 3.82%   |
| Syntek                                 | 4         | 3.05%   |
| Suyin                                  | 4         | 3.05%   |
| Apple                                  | 3         | 2.29%   |
| Lite-On Technology                     | 2         | 1.53%   |
| Sonix Technology                       | 1         | 0.76%   |
| Ricoh                                  | 1         | 0.76%   |
| Primax Electronics                     | 1         | 0.76%   |
| Luxvisions Innotech Limited            | 1         | 0.76%   |
| LG Electronics                         | 1         | 0.76%   |
| Generalplus Technology                 | 1         | 0.76%   |
| Creative Technology                    | 1         | 0.76%   |
| Alcor Micro                            | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                                          | 9         | 6.87%   |
| Chicony USB2.0 Camera                                                      | 7         | 5.34%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 3.82%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 3.82%   |
| Chicony Integrated Camera                                                  | 5         | 3.82%   |
| Chicony HP HD Camera                                                       | 4         | 3.05%   |
| Sunplus Asus Webcam                                                        | 3         | 2.29%   |
| Acer HD Webcam                                                             | 3         | 2.29%   |
| Acer BisonCam,NB Pro                                                       | 3         | 2.29%   |
| Acer BisonCam, NB Pro                                                      | 3         | 2.29%   |
| Suyin HP Truevision HD                                                     | 2         | 1.53%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.53%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.53%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 1.53%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 1.53%   |
| IMC Networks Integrated Camera                                             | 2         | 1.53%   |
| Chicony Integrated Camera [ThinkPad]                                       | 2         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 2         | 1.53%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                                       | 1         | 0.76%   |
| Syntek USB2.0 Camera                                                       | 1         | 0.76%   |
| Syntek Integrated Camera                                                   | 1         | 0.76%   |
| Syntek EasyCamera                                                          | 1         | 0.76%   |
| Suyin HD WebCam                                                            | 1         | 0.76%   |
| Suyin HD Video WebCam                                                      | 1         | 0.76%   |
| Sunplus USB Camera                                                         | 1         | 0.76%   |
| Sunplus MTD Camera                                                         | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 0.76%   |
| Sunplus Laptop Integrated WebCam HD                                        | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 0.76%   |
| Sunplus Aukey-PC-LM1E Camera                                               | 1         | 0.76%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.76%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDD13335N                                       | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.76%   |
| Silicon Motion Web Camera                                                  | 1         | 0.76%   |
| Silicon Motion HP Webcam-50                                                | 1         | 0.76%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 1         | 0.76%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 0.76%   |
| Realtek Integrated Webcam HD                                               | 1         | 0.76%   |
| Realtek Integrated Webcam                                                  | 1         | 0.76%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 0.76%   |
| Realtek HD WebCam                                                          | 1         | 0.76%   |
| Quanta VGA WebCam                                                          | 1         | 0.76%   |
| Quanta LG Webcam                                                           | 1         | 0.76%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                       | 1         | 0.76%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 0.76%   |
| Quanta HD User Facing                                                      | 1         | 0.76%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 0.76%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 0.76%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 0.76%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 1         | 0.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 0.76%   |
| Lite-On HP TrueVision HD Camera                                            | 1         | 0.76%   |
| Lite-On HP HD Webcam                                                       | 1         | 0.76%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)                      | 1         | 0.76%   |
| IMC Networks USB 2.0 Camera                                                | 1         | 0.76%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 0.76%   |
| Generalplus GENERAL WEBCAM                                                 | 1         | 0.76%   |
| Creative Live! Cam Chat HD [VF0700]                                        | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 44.44%  |
| Synaptics                  | 11        | 30.56%  |
| LighTuning Technology      | 4         | 11.11%  |
| Shenzhen Goodix Technology | 3         | 8.33%   |
| Elan Microelectronics      | 1         | 2.78%   |
| AuthenTec                  | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 13.89%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 11.11%  |
| Unknown                                                                    | 4         | 11.11%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 8.33%   |
| Synaptics WBDI Device                                                      | 3         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 5.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.78%   |
| Validity Sensors VFS491                                                    | 1         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.78%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.78%   |
| LighTuning Fingerprint Reader                                              | 1         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.78%   |
| Elan ELAN:Fingerprint                                                      | 1         | 2.78%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 50%     |
| Upek        | 4         | 33.33%  |
| Lenovo      | 1         | 8.33%   |
| Alcor Micro | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 4         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor             | 3         | 25%     |
| Broadcom 5880                                              | 3         | 25%     |
| Lenovo Integrated Smart Card Reader                        | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 74        | 51.03%  |
| 1     | 55        | 37.93%  |
| 2     | 14        | 9.66%   |
| 4     | 1         | 0.69%   |
| 3     | 1         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 42.86%  |
| Graphics card            | 13        | 15.48%  |
| Chipcard                 | 12        | 14.29%  |
| Communication controller | 8         | 9.52%   |
| Net/wireless             | 6         | 7.14%   |
| Storage                  | 2         | 2.38%   |
| Multimedia controller    | 2         | 2.38%   |
| Bluetooth                | 2         | 2.38%   |
| Net/ethernet             | 1         | 1.19%   |
| Card reader              | 1         | 1.19%   |
| Camera                   | 1         | 1.19%   |


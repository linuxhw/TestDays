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

Total: 220

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | InfinityBook S 14 Gen6      | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| Apple         | MacBookPro15,1              | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| MSI           | Vector GP66 12UGS           | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| ASUSTek       | UX303UA                     | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| Apple         | MacBookPro4,1               | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| Sony          | SVS13A25PBS                 | [9072890c1d](https://linux-hardware.org/?probe=9072890c1d) | Feb 02, 2022 |
| Sony          | SVS13A25PBS                 | [894e40654e](https://linux-hardware.org/?probe=894e40654e) | Feb 02, 2022 |
| HP            | Laptop 15s-fq1xxx           | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | V145-15AST 81MT             | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| TUXEDO        | Book XP1511                 | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| HP            | EliteBook 8570w             | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | [249a326a8b](https://linux-hardware.org/?probe=249a326a8b) | Jan 17, 2022 |
| HP            | EliteBook 8570w             | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| Lenovo        | V145-15AST 81MT             | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| TUXEDO        | Unknown                     | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| HP            | Pavilion dm1                | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| TUXEDO        | P95_HP                      | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Unknown       | Unknown                     | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Dell          | Inspiron 5515               | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Acer          | Aspire 4752                 | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| HP            | ZBook Studio G3             | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| TUXEDO        | Book XP1511                 | [7526222677](https://linux-hardware.org/?probe=7526222677) | Aug 15, 2021 |
| TUXEDO        | Book XP1511                 | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| TUXEDO        | TUXEDO_Book_XA1510          | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Fujitsu       | LIFEBOOK E756               | [1c72549a32](https://linux-hardware.org/?probe=1c72549a32) | Jun 29, 2021 |
| HP            | Notebook                    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| Acer          | TravelMate P446-M           | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| Toshiba       | Satellite P300              | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| Toshiba       | Satellite P300              | [a53633e2b1](https://linux-hardware.org/?probe=a53633e2b1) | Jun 09, 2021 |
| Toshiba       | Satellite P300              | [3984b7401d](https://linux-hardware.org/?probe=3984b7401d) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| Dell          | Latitude E6410              | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| ASUSTek       | N53SM                       | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| HP            | EliteBook 850 G1            | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| Dell          | XPS 15 9500                 | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| HP            | Pavilion g6                 | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| MSI           | CX62 6QL                    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| HP            | ProBook 640 G2              | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Fujitsu       | LIFEBOOK E756               | [2e450a6687](https://linux-hardware.org/?probe=2e450a6687) | Mar 06, 2021 |
| HP            | ENVY 15                     | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| ASUSTek       | X551CA                      | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek       | N53SM                       | [e4689416a8](https://linux-hardware.org/?probe=e4689416a8) | Feb 02, 2021 |
| HP            | Laptop 15-da0xxx            | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| ASUSTek       | N53SM                       | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| MSI           | GE70 2PC\2PE                | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Acer          | TravelMate P446-M           | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| TUXEDO        | Aura 15 Gen1                | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| ASUSTek       | F9E                         | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| Acer          | Aspire E1-532               | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| HP            | Laptop 17-ak0xx             | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| HP            | Laptop 17-ak0xx             | [e51b8a2e3d](https://linux-hardware.org/?probe=e51b8a2e3d) | Nov 14, 2020 |
| HP            | Laptop 17-ak0xx             | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Fujitsu       | LIFEBOOK E756               | [3d1548beea](https://linux-hardware.org/?probe=3d1548beea) | Nov 06, 2020 |
| Sony          | SVS13A25PBS                 | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK E756               | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Dell          | Latitude E6540              | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| HP            | Elite x2 1012 G1            | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| Dell          | Latitude 5400               | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | Laptop 14-dk0xxx            | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| MSI           | Modern 14 A10RB             | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| Dell          | Latitude 5400               | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| HP            | ProBook 4730s               | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Fujitsu       | LIFEBOOK A512               | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| HP            | Pavilion g6                 | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Dell          | Inspiron 11-3168            | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| MSI           | Prestige 15 A10SC           | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| Standard      | MT40II                      | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [89e1df883c](https://linux-hardware.org/?probe=89e1df883c) | Aug 01, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [545f6ed65f](https://linux-hardware.org/?probe=545f6ed65f) | Jul 31, 2020 |
| Apple         | MacBook3,1                  | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| HUAWEI        | MACH-WX9                    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| Dell          | G3 3579                     | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| MSI           | GP72 7RE                    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| ASUSTek       | X510UAR                     | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| Dell          | Latitude E6220              | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| HP            | Laptop 15-dw0xxx            | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| Acer          | Aspire R3-131T              | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| Acer          | Aspire V3-572G              | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 17                     | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | S400CA                      | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| Dell          | Latitude 5400               | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Lenovo        | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | [e4d76f72dc](https://linux-hardware.org/?probe=e4d76f72dc) | May 11, 2020 |
| Lenovo        | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| ASUSTek       | S551LN                      | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| HP            | Notebook                    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| HP            | Compaq 8460p USAO           | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.4.0-42-generic           | 16        | 9.64%   |
| 5.4.0-40-generic           | 9         | 5.42%   |
| 5.4.0-37-generic           | 6         | 3.61%   |
| 5.4.0-29-generic           | 6         | 3.61%   |
| 5.4.0-52-generic           | 5         | 3.01%   |
| 5.4.0-48-generic           | 5         | 3.01%   |
| 5.4.0-33-generic           | 5         | 3.01%   |
| 5.8.0-53-generic           | 4         | 2.41%   |
| 5.4.0-58-generic           | 4         | 2.41%   |
| 5.4.0-31-generic           | 4         | 2.41%   |
| 5.13.0-28-generic          | 4         | 2.41%   |
| 5.8.0-48-generic           | 3         | 1.81%   |
| 5.4.0-91-generic           | 3         | 1.81%   |
| 5.4.0-73-generic           | 3         | 1.81%   |
| 5.4.0-28-generic           | 3         | 1.81%   |
| 5.11.0-41-generic          | 3         | 1.81%   |
| 5.11.0-27-generic          | 3         | 1.81%   |
| 5.8.0-49-generic           | 2         | 1.2%    |
| 5.8.0-45-generic           | 2         | 1.2%    |
| 5.8.0-44-generic           | 2         | 1.2%    |
| 5.4.0-80-generic           | 2         | 1.2%    |
| 5.4.0-72-generic           | 2         | 1.2%    |
| 5.4.0-66-generic           | 2         | 1.2%    |
| 5.4.0-65-generic           | 2         | 1.2%    |
| 5.4.0-60-generic           | 2         | 1.2%    |
| 5.4.0-59-generic           | 2         | 1.2%    |
| 5.4.0-56-generic           | 2         | 1.2%    |
| 5.4.0-47-generic           | 2         | 1.2%    |
| 5.4.0-26-generic           | 2         | 1.2%    |
| 5.13.0-30-generic          | 2         | 1.2%    |
| 5.9.0-050900rc6-lowlatency | 1         | 0.6%    |
| 5.8.11-050811-generic      | 1         | 0.6%    |
| 5.8.0-63-generic           | 1         | 0.6%    |
| 5.8.0-59-generic           | 1         | 0.6%    |
| 5.8.0-50-generic           | 1         | 0.6%    |
| 5.8.0-43-generic           | 1         | 0.6%    |
| 5.8.0-41-generic           | 1         | 0.6%    |
| 5.6.7-050607-generic       | 1         | 0.6%    |
| 5.6.0-1048-oem             | 1         | 0.6%    |
| 5.6.0-1042-oem             | 1         | 0.6%    |
| 5.6.0-1034-oem             | 1         | 0.6%    |
| 5.5.0-2.1-liquorix-amd64   | 1         | 0.6%    |
| 5.4.0-97-generic           | 1         | 0.6%    |
| 5.4.0-94-generic           | 1         | 0.6%    |
| 5.4.0-92-generic           | 1         | 0.6%    |
| 5.4.0-89-generic           | 1         | 0.6%    |
| 5.4.0-77-generic           | 1         | 0.6%    |
| 5.4.0-74-generic           | 1         | 0.6%    |
| 5.4.0-62-generic           | 1         | 0.6%    |
| 5.4.0-61-generic           | 1         | 0.6%    |
| 5.4.0-55-generic           | 1         | 0.6%    |
| 5.4.0-54-generic           | 1         | 0.6%    |
| 5.4.0-51-generic           | 1         | 0.6%    |
| 5.4.0-48-lowlatency        | 1         | 0.6%    |
| 5.4.0-45-generic           | 1         | 0.6%    |
| 5.4.0-44-generic           | 1         | 0.6%    |
| 5.4.0-41-generic           | 1         | 0.6%    |
| 5.4.0-30-generic           | 1         | 0.6%    |
| 5.4.0-25-generic           | 1         | 0.6%    |
| 5.4.0-21-generic           | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 96        | 62.34%  |
| 5.8.0   | 18        | 11.69%  |
| 5.11.0  | 13        | 8.44%   |
| 5.13.0  | 12        | 7.79%   |
| 5.6.0   | 3         | 1.95%   |
| 5.3.0   | 2         | 1.3%    |
| 5.9.0   | 1         | 0.65%   |
| 5.8.11  | 1         | 0.65%   |
| 5.6.7   | 1         | 0.65%   |
| 5.5.0   | 1         | 0.65%   |
| 5.16.14 | 1         | 0.65%   |
| 5.15.11 | 1         | 0.65%   |
| 5.15.0  | 1         | 0.65%   |
| 5.12.0  | 1         | 0.65%   |
| 5.10.11 | 1         | 0.65%   |
| 5.10.0  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 96        | 62.34%  |
| 5.8     | 19        | 12.34%  |
| 5.11    | 13        | 8.44%   |
| 5.13    | 12        | 7.79%   |
| 5.6     | 4         | 2.6%    |
| 5.3     | 2         | 1.3%    |
| 5.15    | 2         | 1.3%    |
| 5.10    | 2         | 1.3%    |
| 5.9     | 1         | 0.65%   |
| 5.5     | 1         | 0.65%   |
| 5.16    | 1         | 0.65%   |
| 5.12    | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 151       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 148       | 98.01%  |
| GNOME  | 2         | 1.32%   |
| XFCE   | 1         | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 145       | 96.03%  |
| Wayland | 6         | 3.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 40.13%  |
| LightDM | 37        | 24.34%  |
| TDM     | 33        | 21.71%  |
| GDM     | 19        | 12.5%   |
| GDM3    | 2         | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 43        | 28.29%  |
| de_DE   | 24        | 15.79%  |
| pt_BR   | 14        | 9.21%   |
| fr_FR   | 11        | 7.24%   |
| en_GB   | 11        | 7.24%   |
| ru_RU   | 6         | 3.95%   |
| en_CA   | 6         | 3.95%   |
| en_IN   | 4         | 2.63%   |
| it_IT   | 3         | 1.97%   |
| es_ES   | 3         | 1.97%   |
| pt_PT   | 2         | 1.32%   |
| fi_FI   | 2         | 1.32%   |
| es_AR   | 2         | 1.32%   |
| en_AU   | 2         | 1.32%   |
| de_CH   | 2         | 1.32%   |
| C       | 2         | 1.32%   |
| zh_CN   | 1         | 0.66%   |
| pl_PL   | 1         | 0.66%   |
| nl_NL   | 1         | 0.66%   |
| nb_NO   | 1         | 0.66%   |
| id_ID   | 1         | 0.66%   |
| hu_HU   | 1         | 0.66%   |
| fr_CH   | 1         | 0.66%   |
| es_US   | 1         | 0.66%   |
| es_SV   | 1         | 0.66%   |
| es_MX   | 1         | 0.66%   |
| es_GT   | 1         | 0.66%   |
| es_CL   | 1         | 0.66%   |
| en_SG   | 1         | 0.66%   |
| de_AT   | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 110       | 70.97%  |
| BIOS | 45        | 29.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 141       | 93.38%  |
| Zfs     | 5         | 3.31%   |
| Overlay | 2         | 1.32%   |
| Xfs     | 1         | 0.66%   |
| Jfs     | 1         | 0.66%   |
| Btrfs   | 1         | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 47.68%  |
| GPT     | 61        | 40.4%   |
| MBR     | 18        | 11.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 91.5%   |
| Yes       | 13        | 8.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 68.87%  |
| Yes       | 47        | 31.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 28        | 18.54%  |
| TUXEDO              | 24        | 15.89%  |
| Lenovo              | 21        | 13.91%  |
| Dell                | 19        | 12.58%  |
| ASUSTek Computer    | 16        | 10.6%   |
| Acer                | 13        | 8.61%   |
| MSI                 | 8         | 5.3%    |
| Apple               | 6         | 3.97%   |
| Samsung Electronics | 4         | 2.65%   |
| Sony                | 2         | 1.32%   |
| HUAWEI              | 2         | 1.32%   |
| Toshiba             | 1         | 0.66%   |
| Standard            | 1         | 0.66%   |
| Razer               | 1         | 0.66%   |
| Quanta              | 1         | 0.66%   |
| Packard Bell        | 1         | 0.66%   |
| Gigabyte Technology | 1         | 0.66%   |
| Fujitsu             | 1         | 0.66%   |
| Unknown             | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 5         | 3.31%   |
| TUXEDO Polaris 15 AMD Gen1                            | 2         | 1.32%   |
| TUXEDO InfinityBook S 15 Gen6                         | 2         | 1.32%   |
| TUXEDO InfinityBook S 14 Gen6                         | 2         | 1.32%   |
| TUXEDO InfinityBook Pro 14 Gen6                       | 2         | 1.32%   |
| HP ZBook Studio G3                                    | 2         | 1.32%   |
| HP Pavilion g6                                        | 2         | 1.32%   |
| HP Notebook                                           | 2         | 1.32%   |
| Dell Latitude 5400                                    | 2         | 1.32%   |
| Acer TravelMate P446-M                                | 2         | 1.32%   |
| TUXEDO TUXEDO_Book_XA1510                             | 1         | 0.66%   |
| TUXEDO Stellaris AMD Gen3 (CZN)                       | 1         | 0.66%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.66%   |
| TUXEDO Polaris AMD Gen3 (CZN)                         | 1         | 0.66%   |
| TUXEDO Polaris 17 AMD Gen1                            | 1         | 0.66%   |
| TUXEDO P95_HR                                         | 1         | 0.66%   |
| TUXEDO P95_HP                                         | 1         | 0.66%   |
| TUXEDO P7xxTM1                                        | 1         | 0.66%   |
| TUXEDO InfinityBook Pro 15 v4                         | 1         | 0.66%   |
| TUXEDO Book XP1511                                    | 1         | 0.66%   |
| TUXEDO Book XP15 / XP17 Gen12                         | 1         | 0.66%   |
| TUXEDO Aura 15 Gen1                                   | 1         | 0.66%   |
| Toshiba Satellite P300                                | 1         | 0.66%   |
| Standard MT40II                                       | 1         | 0.66%   |
| Sony VPCCW25FL                                        | 1         | 0.66%   |
| Sony SVS13A25PBS                                      | 1         | 0.66%   |
| Samsung 905S3G/906S3G/915S3G/9305SG                   | 1         | 0.66%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.66%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.66%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.66%   |
| Razer Blade Stealth                                   | 1         | 0.66%   |
| Quanta R460-L.BG22P1                                  | 1         | 0.66%   |
| Packard Bell ENLE11BZ                                 | 1         | 0.66%   |
| MSI Vector GP66 12UGS                                 | 1         | 0.66%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.66%   |
| MSI Modern 14 A10RB                                   | 1         | 0.66%   |
| MSI GP73 Leopard 8RE                                  | 1         | 0.66%   |
| MSI GP72 7RE                                          | 1         | 0.66%   |
| MSI GL62M 7RD                                         | 1         | 0.66%   |
| MSI GE70 2PC\2PE                                      | 1         | 0.66%   |
| MSI CX62 6QL                                          | 1         | 0.66%   |
| Lenovo V310-15ISK 80SY                                | 1         | 0.66%   |
| Lenovo V145-15AST 81MT                                | 1         | 0.66%   |
| Lenovo ThinkPad X260 20F5S2HF06                       | 1         | 0.66%   |
| Lenovo ThinkPad X230 23257G6                          | 1         | 0.66%   |
| Lenovo ThinkPad X230 2306CTO                          | 1         | 0.66%   |
| Lenovo ThinkPad W530 2447GW3                          | 1         | 0.66%   |
| Lenovo ThinkPad W530 244743G                          | 1         | 0.66%   |
| Lenovo ThinkPad T480 20L6SDR21A                       | 1         | 0.66%   |
| Lenovo ThinkPad T430s 23539WU                         | 1         | 0.66%   |
| Lenovo ThinkPad T430 2349P74                          | 1         | 0.66%   |
| Lenovo ThinkPad T410 2537H21                          | 1         | 0.66%   |
| Lenovo ThinkPad P53 20QQS1JE00                        | 1         | 0.66%   |
| Lenovo ThinkPad P43s 20RHS00100                       | 1         | 0.66%   |
| Lenovo ThinkPad P43s 20RH0013US                       | 1         | 0.66%   |
| Lenovo ThinkPad P1 20MES01400                         | 1         | 0.66%   |
| Lenovo ThinkPad E490 20N8S07A00                       | 1         | 0.66%   |
| Lenovo IdeaPad S145-15IWL 81S9                        | 1         | 0.66%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                         | 1         | 0.66%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 14        | 9.27%   |
| Acer Aspire            | 10        | 6.62%   |
| Dell Latitude          | 9         | 5.96%   |
| TUXEDO InfinityBook    | 7         | 4.64%   |
| HP Pavilion            | 6         | 3.97%   |
| HP EliteBook           | 6         | 3.97%   |
| Dell Inspiron          | 6         | 3.97%   |
| Unknown                | 5         | 3.31%   |
| TUXEDO Polaris         | 4         | 2.65%   |
| HP Laptop              | 4         | 2.65%   |
| Lenovo IdeaPad         | 3         | 1.99%   |
| HP ProBook             | 3         | 1.99%   |
| TUXEDO P95             | 2         | 1.32%   |
| TUXEDO Book            | 2         | 1.32%   |
| HP ZBook               | 2         | 1.32%   |
| HP Notebook            | 2         | 1.32%   |
| HP ENVY                | 2         | 1.32%   |
| Dell XPS               | 2         | 1.32%   |
| Acer TravelMate        | 2         | 1.32%   |
| TUXEDO TUXEDO          | 1         | 0.66%   |
| TUXEDO Stellaris       | 1         | 0.66%   |
| TUXEDO Pulse           | 1         | 0.66%   |
| TUXEDO P7xxTM1         | 1         | 0.66%   |
| TUXEDO Aura            | 1         | 0.66%   |
| Toshiba Satellite      | 1         | 0.66%   |
| Standard MT40II        | 1         | 0.66%   |
| Sony VPCCW25FL         | 1         | 0.66%   |
| Sony SVS13A25PBS       | 1         | 0.66%   |
| Samsung 905S3G         | 1         | 0.66%   |
| Samsung 530U3C         | 1         | 0.66%   |
| Samsung 340XAA         | 1         | 0.66%   |
| Samsung 300E5EV        | 1         | 0.66%   |
| Razer Blade            | 1         | 0.66%   |
| Quanta R460-L.BG22P1   | 1         | 0.66%   |
| Packard Bell ENLE11BZ  | 1         | 0.66%   |
| MSI Vector             | 1         | 0.66%   |
| MSI Prestige           | 1         | 0.66%   |
| MSI Modern             | 1         | 0.66%   |
| MSI GP73               | 1         | 0.66%   |
| MSI GP72               | 1         | 0.66%   |
| MSI GL62M              | 1         | 0.66%   |
| MSI GE70               | 1         | 0.66%   |
| MSI CX62               | 1         | 0.66%   |
| Lenovo V310-15ISK      | 1         | 0.66%   |
| Lenovo V145-15AST      | 1         | 0.66%   |
| Lenovo G550            | 1         | 0.66%   |
| Lenovo 20SL            | 1         | 0.66%   |
| HUAWEI MACH-WX9        | 1         | 0.66%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.66%   |
| HP x360                | 1         | 0.66%   |
| HP Elite               | 1         | 0.66%   |
| HP Compaq              | 1         | 0.66%   |
| Gigabyte GB-BKi7A-7500 | 1         | 0.66%   |
| Fujitsu LIFEBOOK       | 1         | 0.66%   |
| Dell G7                | 1         | 0.66%   |
| Dell G3                | 1         | 0.66%   |
| ASUS ZenBook           | 1         | 0.66%   |
| ASUS X551CA            | 1         | 0.66%   |
| ASUS X540LA            | 1         | 0.66%   |
| ASUS X510UNR           | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 20        | 13.25%  |
| 2018 | 19        | 12.58%  |
| 2020 | 17        | 11.26%  |
| 2012 | 15        | 9.93%   |
| 2016 | 14        | 9.27%   |
| 2011 | 12        | 7.95%   |
| 2017 | 11        | 7.28%   |
| 2021 | 7         | 4.64%   |
| 2015 | 7         | 4.64%   |
| 2014 | 7         | 4.64%   |
| 2013 | 7         | 4.64%   |
| 2009 | 5         | 3.31%   |
| 2008 | 5         | 3.31%   |
| 2010 | 4         | 2.65%   |
| 2022 | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 151       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 133       | 88.08%  |
| Enabled  | 18        | 11.92%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 151       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 46        | 30.07%  |
| 16.01-24.0  | 34        | 22.22%  |
| 8.01-16.0   | 27        | 17.65%  |
| 3.01-4.0    | 19        | 12.42%  |
| 32.01-64.0  | 18        | 11.76%  |
| 64.01-256.0 | 6         | 3.92%   |
| 2.01-3.0    | 2         | 1.31%   |
| 1.01-2.0    | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 48        | 30%     |
| 1.01-2.0  | 39        | 24.38%  |
| 4.01-8.0  | 33        | 20.63%  |
| 3.01-4.0  | 31        | 19.38%  |
| 8.01-16.0 | 9         | 5.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 72.19%  |
| 2      | 39        | 25.83%  |
| 3      | 3         | 1.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 105       | 69.08%  |
| Yes       | 47        | 30.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 85.43%  |
| No        | 22        | 14.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 83.55%  |
| No        | 25        | 16.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 28        | 18.54%  |
| Brazil             | 15        | 9.93%   |
| USA                | 11        | 7.28%   |
| France             | 10        | 6.62%   |
| Russia             | 7         | 4.64%   |
| Italy              | 6         | 3.97%   |
| Poland             | 5         | 3.31%   |
| UK                 | 4         | 2.65%   |
| Spain              | 4         | 2.65%   |
| Netherlands        | 4         | 2.65%   |
| India              | 4         | 2.65%   |
| Finland            | 4         | 2.65%   |
| Canada             | 4         | 2.65%   |
| Ukraine            | 3         | 1.99%   |
| Portugal           | 3         | 1.99%   |
| Iran               | 3         | 1.99%   |
| Turkey             | 2         | 1.32%   |
| Switzerland        | 2         | 1.32%   |
| South Africa       | 2         | 1.32%   |
| Norway             | 2         | 1.32%   |
| Japan              | 2         | 1.32%   |
| Indonesia          | 2         | 1.32%   |
| Hungary            | 2         | 1.32%   |
| Austria            | 2         | 1.32%   |
| Australia          | 2         | 1.32%   |
| Argentina          | 2         | 1.32%   |
| Slovenia           | 1         | 0.66%   |
| Singapore          | 1         | 0.66%   |
| Mexico             | 1         | 0.66%   |
| Malaysia           | 1         | 0.66%   |
| Kenya              | 1         | 0.66%   |
| Hong Kong          | 1         | 0.66%   |
| Honduras           | 1         | 0.66%   |
| Guatemala          | 1         | 0.66%   |
| Ghana              | 1         | 0.66%   |
| El Salvador        | 1         | 0.66%   |
| Ecuador            | 1         | 0.66%   |
| Dominican Republic | 1         | 0.66%   |
| Croatia            | 1         | 0.66%   |
| Colombia           | 1         | 0.66%   |
| Chile              | 1         | 0.66%   |
| Belgium            | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Tehran                    | 3         | 1.92%   |
| Stuttgart                 | 3         | 1.92%   |
| Sao Paulo                 | 3         | 1.92%   |
| Ravensburg                | 3         | 1.92%   |
| Paris                     | 3         | 1.92%   |
| Munich                    | 3         | 1.92%   |
| Moscow                    | 3         | 1.92%   |
| Montreal                  | 2         | 1.28%   |
| Los Angeles               | 2         | 1.28%   |
| Lisbon                    | 2         | 1.28%   |
| Kyiv                      | 2         | 1.28%   |
| Budapest                  | 2         | 1.28%   |
| BrasГ­lia               | 2         | 1.28%   |
| Belo Horizonte            | 2         | 1.28%   |
| Zheleznodorozhnyy         | 1         | 0.64%   |
| Zagreb                    | 1         | 0.64%   |
| Zabrze                    | 1         | 0.64%   |
| Yuma                      | 1         | 0.64%   |
| Wolfsburg                 | 1         | 0.64%   |
| Woking                    | 1         | 0.64%   |
| Wilchingen, Osterfingen   | 1         | 0.64%   |
| Waterloo                  | 1         | 0.64%   |
| Warsaw                    | 1         | 0.64%   |
| Villingen-Schwenningen    | 1         | 0.64%   |
| Vienna                    | 1         | 0.64%   |
| Vicente Lopez             | 1         | 0.64%   |
| Vantaa                    | 1         | 0.64%   |
| Tuttlingen                | 1         | 0.64%   |
| Tuscola                   | 1         | 0.64%   |
| Turku                     | 1         | 0.64%   |
| Totana                    | 1         | 0.64%   |
| Tokyo                     | 1         | 0.64%   |
| Tiel                      | 1         | 0.64%   |
| The Hague                 | 1         | 0.64%   |
| Teresina                  | 1         | 0.64%   |
| Tangerang                 | 1         | 0.64%   |
| SГЈo LuГ­s            | 1         | 0.64%   |
| SГЈo JosГ© dos Campos | 1         | 0.64%   |
| Sydney                    | 1         | 0.64%   |
| Steinmauern               | 1         | 0.64%   |
| St Petersburg             | 1         | 0.64%   |
| Spilimbergo               | 1         | 0.64%   |
| Skien                     | 1         | 0.64%   |
| Singapore                 | 1         | 0.64%   |
| Sens                      | 1         | 0.64%   |
| Santo Domingo Este        | 1         | 0.64%   |
| SantarГ©m               | 1         | 0.64%   |
| Santa Tecla               | 1         | 0.64%   |
| San Pedro Sula            | 1         | 0.64%   |
| Salt Lake City            | 1         | 0.64%   |
| Salamanca                 | 1         | 0.64%   |
| Saint-Medard-de-Guizieres | 1         | 0.64%   |
| Saint-Junien              | 1         | 0.64%   |
| Rostov-on-Don             | 1         | 0.64%   |
| Quito                     | 1         | 0.64%   |
| Povoa de Lanhoso          | 1         | 0.64%   |
| Ponte San Pietro          | 1         | 0.64%   |
| Penzberg                  | 1         | 0.64%   |
| Parma                     | 1         | 0.64%   |
| Ovalle                    | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives  | Percent |
|---------------------------|-----------|---------|---------|
| Samsung Electronics       | 52        | 66      | 27.37%  |
| Toshiba                   | 20        | 22      | 10.53%  |
| Seagate                   | 20        | 22      | 10.53%  |
| WDC                       | 16        | 18      | 8.42%   |
| SanDisk                   | 11        | 12      | 5.79%   |
| Unknown                   | 8         | 9       | 4.21%   |
| Crucial                   | 7         | 7       | 3.68%   |
| Micron Technology         | 6         | 8       | 3.16%   |
| Kingston                  | 6         | 6       | 3.16%   |
| Intel                     | 6         | 7       | 3.16%   |
| HGST                      | 6         | 9       | 3.16%   |
| SK Hynix                  | 5         | 5       | 2.63%   |
| Hitachi                   | 4         | 4       | 2.11%   |
| A-DATA Technology         | 4         | 5       | 2.11%   |
| PNY                       | 3         | 5       | 1.58%   |
| Apple                     | 3         | 3       | 1.58%   |
| LITEON                    | 2         | 2       | 1.05%   |
| China                     | 2         | 2       | 1.05%   |
| Vaseky                    | 1         | 1       | 0.53%   |
| USB30                     | 1         | 1       | 0.53%   |
| Micron/Crucial Technology | 1         | 1       | 0.53%   |
| LaCie                     | 1         | 1       | 0.53%   |
| KingSpec                  | 1         | 1       | 0.53%   |
| KimMiDi                   | 1         | 1       | 0.53%   |
| Hewlett-Packard           | 1         | Unknown | 0.53%   |
| GALAX TA                  | 1         | 1       | 0.53%   |
| Corsair                   | 1         | 1       | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 4         | 2.04%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 2.04%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.53%   |
| Samsung SSD 750 EVO 250GB            | 3         | 1.53%   |
| Samsung NVMe SSD Drive 250GB         | 3         | 1.53%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 1.02%   |
| Unknown MMC Card  32GB               | 2         | 1.02%   |
| SK Hynix NVMe SSD Drive 256GB        | 2         | 1.02%   |
| Seagate ST9500325AS 500GB            | 2         | 1.02%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 1.02%   |
| Seagate BUP Slim BK 1TB              | 2         | 1.02%   |
| SanDisk SSD PLUS 120GB               | 2         | 1.02%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 1.02%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.02%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 1.02%   |
| Samsung SSD 970 EVO 500GB            | 2         | 1.02%   |
| Samsung SSD 860 EVO M.2 250GB        | 2         | 1.02%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.02%   |
| Samsung NVMe SSD Drive 2TB           | 2         | 1.02%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 1.02%   |
| Samsung MZVLB256HAHQ-00000 256GB     | 2         | 1.02%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 1.02%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 1.02%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.02%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.02%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.51%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.51%   |
| WDC WDS100T2B0A 1TB SSD              | 1         | 0.51%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.51%   |
| WDC WD1600BEVS-08VAT2 160GB          | 1         | 0.51%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 0.51%   |
| WDC WD10SPZX-35Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.51%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10SPZX-17Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.51%   |
| WDC PC SN720 SDAQNTW-256G-1001 256GB | 1         | 0.51%   |
| WDC PC SN520 NVMe 512GB              | 1         | 0.51%   |
| Vaseky V800/120G 120GB SSD           | 1         | 0.51%   |
| USB30 Disk 500GB                     | 1         | 0.51%   |
| Unknown SD64G  64GB                  | 1         | 0.51%   |
| Unknown SD/MMC/MS PRO 32GB           | 1         | 0.51%   |
| Unknown NVMe SSD Drive 512GB         | 1         | 0.51%   |
| Unknown MMC Card  64GB               | 1         | 0.51%   |
| Unknown MMC Card  2GB                | 1         | 0.51%   |
| Unknown MMC Card  16GB               | 1         | 0.51%   |
| Unknown 00000  2GB                   | 1         | 0.51%   |
| Toshiba THNSNJ512G8NY 512GB SSD      | 1         | 0.51%   |
| Toshiba NVMe SSD Drive 512GB         | 1         | 0.51%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.51%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.51%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.51%   |
| Toshiba MQ01ABF032 320GB             | 1         | 0.51%   |
| Toshiba MQ01ABD050 500GB             | 1         | 0.51%   |
| Toshiba MK7559GSXF 752GB             | 1         | 0.51%   |
| Toshiba MK6461GSYN 640GB             | 1         | 0.51%   |
| Toshiba MK5055GSX 500GB              | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 20     | 33.33%  |
| Toshiba | 15        | 17     | 27.78%  |
| WDC     | 10        | 11     | 18.52%  |
| HGST    | 6         | 9      | 11.11%  |
| Hitachi | 4         | 4      | 7.41%   |
| Unknown | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 30     | 34.78%  |
| SanDisk             | 8         | 8      | 11.59%  |
| Crucial             | 6         | 6      | 8.7%    |
| Kingston            | 5         | 5      | 7.25%   |
| WDC                 | 4         | 5      | 5.8%    |
| PNY                 | 3         | 5      | 4.35%   |
| Micron Technology   | 3         | 5      | 4.35%   |
| A-DATA Technology   | 3         | 4      | 4.35%   |
| LITEON              | 2         | 2      | 2.9%    |
| China               | 2         | 2      | 2.9%    |
| Apple               | 2         | 2      | 2.9%    |
| Vaseky              | 1         | 1      | 1.45%   |
| USB30               | 1         | 1      | 1.45%   |
| Toshiba             | 1         | 1      | 1.45%   |
| SK Hynix            | 1         | 1      | 1.45%   |
| Seagate             | 1         | 1      | 1.45%   |
| KingSpec            | 1         | 1      | 1.45%   |
| Intel               | 1         | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 65        | 81     | 35.71%  |
| NVMe    | 55        | 66     | 30.22%  |
| HDD     | 51        | 62     | 28.02%  |
| MMC     | 6         | 7      | 3.3%    |
| Unknown | 5         | 4      | 2.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 99        | 139    | 58.58%  |
| NVMe | 55        | 66     | 32.54%  |
| SAS  | 9         | 8      | 5.33%   |
| MMC  | 6         | 7      | 3.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 88     | 63.39%  |
| 0.51-1.0   | 38        | 51     | 33.93%  |
| 1.01-2.0   | 3         | 4      | 2.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 49        | 31.82%  |
| 251-500        | 42        | 27.27%  |
| 501-1000       | 27        | 17.53%  |
| 51-100         | 10        | 6.49%   |
| 1001-2000      | 9         | 5.84%   |
| 21-50          | 8         | 5.19%   |
| 2001-3000      | 3         | 1.95%   |
| Unknown        | 3         | 1.95%   |
| 1-20           | 2         | 1.3%    |
| More than 3000 | 1         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 44        | 28.39%  |
| 101-250   | 35        | 22.58%  |
| 21-50     | 29        | 18.71%  |
| 51-100    | 23        | 14.84%  |
| 251-500   | 12        | 7.74%   |
| 501-1000  | 7         | 4.52%   |
| Unknown   | 3         | 1.94%   |
| 1001-2000 | 2         | 1.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 16.67%  |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 8.33%   |
| Toshiba MK5055GSX 500GB             | 1         | 1      | 8.33%   |
| Toshiba MK2561GSYN 250GB            | 1         | 1      | 8.33%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 8.33%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 8.33%   |
| PNY SSD2SC120G3LC709B121-460I 120GB | 1         | 1      | 8.33%   |
| HGST HTS725032A7E630 320GB          | 1         | 2      | 8.33%   |
| Crucial CT500P1SSD8 500GB           | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 50%     |
| Seagate | 3         | 3      | 25%     |
| PNY     | 1         | 1      | 8.33%   |
| HGST    | 1         | 2      | 8.33%   |
| Crucial | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 60%     |
| Seagate | 3         | 3      | 30%     |
| HGST    | 1         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 83.33%  |
| NVMe | 1         | 1      | 8.33%   |
| SSD  | 1         | 1      | 8.33%   |

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
| Detected | 78        | 112    | 47.56%  |
| Works    | 74        | 95     | 45.12%  |
| Malfunc  | 12        | 13     | 7.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 110       | 61.8%   |
| Samsung Electronics          | 33        | 18.54%  |
| AMD                          | 11        | 6.18%   |
| Sandisk                      | 5         | 2.81%   |
| Toshiba America Info Systems | 4         | 2.25%   |
| SK Hynix                     | 4         | 2.25%   |
| Micron Technology            | 3         | 1.69%   |
| Micron/Crucial Technology    | 2         | 1.12%   |
| Silicon Motion               | 1         | 0.56%   |
| Realtek Semiconductor        | 1         | 0.56%   |
| Phison Electronics           | 1         | 0.56%   |
| Kingston Technology Company  | 1         | 0.56%   |
| Apple                        | 1         | 0.56%   |
| ADATA Technology             | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 23        | 12.43%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 19        | 10.27%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 8.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 5.95%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 5.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 3.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 6         | 3.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 2.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 2.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.16%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.62%   |
| Micron Non-Volatile memory controller                                            | 3         | 1.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.62%   |
| Intel SSD 660P Series                                                            | 3         | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.62%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 1.08%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 1.08%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.08%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 1.08%   |
| Samsung Electronics SATA controller                                              | 2         | 1.08%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.54%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.54%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.54%   |
| SK Hynix BC511                                                                   | 1         | 0.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.54%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.54%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.54%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.54%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.54%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.54%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.54%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.54%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 0.54%   |
| Apple ANS2 NVMe Controller                                                       | 1         | 0.54%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.54%   |
| ADATA Non-Volatile memory controller                                             | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 111       | 61.67%  |
| NVMe | 57        | 31.67%  |
| RAID | 8         | 4.44%   |
| IDE  | 4         | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 132       | 87.42%  |
| AMD    | 19        | 12.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 3.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 3.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 3.31%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 2.65%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 2.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.99%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.99%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.99%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.99%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.32%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.32%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.32%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.32%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.32%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.32%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.32%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.32%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.66%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.66%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.66%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.66%   |
| Intel Genuine CPU U2300 @ 1.20GHz             | 1         | 0.66%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.66%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 0.66%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.66%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.66%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.66%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.66%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.66%   |
| Intel Core i7-5650U CPU @ 2.20GHz             | 1         | 0.66%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 0.66%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.66%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.66%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.66%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.66%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.66%   |
| Intel Core i7-3820QM CPU @ 2.70GHz            | 1         | 0.66%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.66%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.66%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.66%   |
| Intel Core i7-3517U CPU @ 1.90GHz             | 1         | 0.66%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 0.66%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.66%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.66%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.66%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.66%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.66%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.66%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 66        | 43.71%  |
| Intel Core i5           | 34        | 22.52%  |
| Intel Core i3           | 11        | 7.28%   |
| Other                   | 8         | 5.3%    |
| AMD Ryzen 5             | 7         | 4.64%   |
| Intel Core 2 Duo        | 5         | 3.31%   |
| AMD Ryzen 7             | 5         | 3.31%   |
| Intel Pentium           | 3         | 1.99%   |
| Intel Celeron           | 2         | 1.32%   |
| AMD Ryzen 9             | 2         | 1.32%   |
| AMD A6                  | 2         | 1.32%   |
| Intel Pentium Dual-Core | 1         | 0.66%   |
| Intel Genuine           | 1         | 0.66%   |
| Intel Core m5           | 1         | 0.66%   |
| AMD Quad-Core           | 1         | 0.66%   |
| AMD E                   | 1         | 0.66%   |
| AMD A8                  | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 64        | 42.38%  |
| 4      | 63        | 41.72%  |
| 6      | 15        | 9.93%   |
| 8      | 7         | 4.64%   |
| 16     | 1         | 0.66%   |
| 14     | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 151       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 127       | 84.11%  |
| 1      | 24        | 15.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 151       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 10.26%  |
| 0x206a7    | 14        | 8.97%   |
| 0x306a9    | 13        | 8.33%   |
| 0x906ea    | 9         | 5.77%   |
| 0x806ec    | 9         | 5.77%   |
| 0x806ea    | 8         | 5.13%   |
| 0x806c1    | 7         | 4.49%   |
| 0x406e3    | 7         | 4.49%   |
| 0x40651    | 7         | 4.49%   |
| 0x806e9    | 6         | 3.85%   |
| 0x08600103 | 5         | 3.21%   |
| 0xa0652    | 4         | 2.56%   |
| 0x906e9    | 4         | 2.56%   |
| 0x306d4    | 4         | 2.56%   |
| 0x306c3    | 4         | 2.56%   |
| 0x406c3    | 3         | 1.92%   |
| 0x1067a    | 3         | 1.92%   |
| 0x10676    | 3         | 1.92%   |
| 0x806eb    | 2         | 1.28%   |
| 0x706e5    | 2         | 1.28%   |
| 0x506e3    | 2         | 1.28%   |
| 0x20655    | 2         | 1.28%   |
| 0x20652    | 2         | 1.28%   |
| 0x0a50000c | 2         | 1.28%   |
| 0x08108109 | 2         | 1.28%   |
| 0xa0660    | 1         | 0.64%   |
| 0x906a3    | 1         | 0.64%   |
| 0x6fb      | 1         | 0.64%   |
| 0x406c4    | 1         | 0.64%   |
| 0x40661    | 1         | 0.64%   |
| 0x106e5    | 1         | 0.64%   |
| 0x08701013 | 1         | 0.64%   |
| 0x08608103 | 1         | 0.64%   |
| 0x08600106 | 1         | 0.64%   |
| 0x08600102 | 1         | 0.64%   |
| 0x0810100b | 1         | 0.64%   |
| 0x07030105 | 1         | 0.64%   |
| 0x0700010f | 1         | 0.64%   |
| 0x06006705 | 1         | 0.64%   |
| 0x06001119 | 1         | 0.64%   |
| 0x05000119 | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 47        | 31.13%  |
| SandyBridge      | 14        | 9.27%   |
| IvyBridge        | 14        | 9.27%   |
| Haswell          | 12        | 7.95%   |
| Skylake          | 9         | 5.96%   |
| Zen 2            | 8         | 5.3%    |
| TigerLake        | 7         | 4.64%   |
| Penryn           | 6         | 3.97%   |
| CometLake        | 5         | 3.31%   |
| Westmere         | 4         | 2.65%   |
| Silvermont       | 4         | 2.65%   |
| Broadwell        | 4         | 2.65%   |
| IceLake          | 3         | 1.99%   |
| Zen+             | 2         | 1.32%   |
| Zen 3            | 2         | 1.32%   |
| Zen              | 1         | 0.66%   |
| Puma             | 1         | 0.66%   |
| Piledriver       | 1         | 0.66%   |
| Nehalem          | 1         | 0.66%   |
| Jaguar           | 1         | 0.66%   |
| Excavator        | 1         | 0.66%   |
| Core             | 1         | 0.66%   |
| Bobcat           | 1         | 0.66%   |
| Alderlake Hybrid | 1         | 0.66%   |
| Unknown          | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 121       | 59.02%  |
| Nvidia | 54        | 26.34%  |
| AMD    | 30        | 14.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 6.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 5.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 5.29%   |
| Intel UHD Graphics 620                                                                   | 10        | 4.81%   |
| Intel HD Graphics 620                                                                    | 8         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.37%   |
| AMD Renoir                                                                               | 7         | 3.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.4%    |
| Intel HD Graphics 630                                                                    | 5         | 2.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.44%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.44%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.44%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.44%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.96%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.96%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.96%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.96%   |
| Intel HD Graphics 530                                                                    | 2         | 0.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.96%   |
| AMD Cezanne                                                                              | 2         | 0.96%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.48%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.48%   |
| Nvidia GT215M [GeForce GTS 250M]                                                         | 1         | 0.48%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.48%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.48%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.48%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.48%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.48%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.48%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.48%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.48%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.48%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.48%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.48%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.48%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.48%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.48%   |
| Nvidia GK107M [GeForce GT 640M LE]                                                       | 1         | 0.48%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.48%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.48%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.48%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 47.68%  |
| Intel + Nvidia | 41        | 27.15%  |
| 1 x AMD        | 16        | 10.6%   |
| 1 x Nvidia     | 8         | 5.3%    |
| Intel + AMD    | 8         | 5.3%    |
| AMD + Nvidia   | 5         | 3.31%   |
| 2 x AMD        | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 111       | 73.03%  |
| Proprietary | 38        | 25%     |
| Unknown     | 3         | 1.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 58.82%  |
| 1.01-2.0   | 21        | 13.73%  |
| 0.01-0.5   | 11        | 7.19%   |
| 3.01-4.0   | 9         | 5.88%   |
| 0.51-1.0   | 9         | 5.88%   |
| 7.01-8.0   | 6         | 3.92%   |
| 5.01-6.0   | 6         | 3.92%   |
| 2.01-3.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 31        | 16.67%  |
| LG Display              | 29        | 15.59%  |
| AU Optronics            | 28        | 15.05%  |
| BOE                     | 18        | 9.68%   |
| Samsung Electronics     | 15        | 8.06%   |
| Dell                    | 9         | 4.84%   |
| Chi Mei Optoelectronics | 6         | 3.23%   |
| Apple                   | 6         | 3.23%   |
| Hewlett-Packard         | 5         | 2.69%   |
| Goldstar                | 5         | 2.69%   |
| Sharp                   | 4         | 2.15%   |
| PANDA                   | 3         | 1.61%   |
| Lenovo                  | 3         | 1.61%   |
| Acer                    | 3         | 1.61%   |
| Philips                 | 2         | 1.08%   |
| LGD                     | 2         | 1.08%   |
| InfoVision              | 2         | 1.08%   |
| BenQ                    | 2         | 1.08%   |
| Ancor Communications    | 2         | 1.08%   |
| UPD                     | 1         | 0.54%   |
| Unknown                 | 1         | 0.54%   |
| KTC                     | 1         | 0.54%   |
| JDI                     | 1         | 0.54%   |
| InnoLux Display         | 1         | 0.54%   |
| Iiyama                  | 1         | 0.54%   |
| GDH                     | 1         | 0.54%   |
| Fujitsu Siemens         | 1         | 0.54%   |
| Eizo                    | 1         | 0.54%   |
| CSO                     | 1         | 0.54%   |
| AOC                     | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.58%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 3         | 1.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch  | 2         | 1.05%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2         | 1.05%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 1.05%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 1.05%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch        | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch         | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 1.05%   |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                      | 1         | 0.53%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1366x768           | 1         | 0.53%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.53%   |
| Sharp LQ133Z1JW26 SHP1493 3200x1800 294x165mm 13.3-inch               | 1         | 0.53%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.53%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch               | 1         | 0.53%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch  | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC3150 1920x1080 344x194mm 15.5-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch | 1         | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.53%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch               | 1         | 0.53%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.53%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.53%   |
| LG Display LCD Monitor LGD065A 1920x1080 340x190mm 15.3-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD061A 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0615 1920x1080 382x215mm 17.3-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD05F5 1920x1080 309x174mm 14.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD04A5 1920x1280 253x169mm 12.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch           | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 83        | 48.54%  |
| 1366x768 (WXGA)   | 45        | 26.32%  |
| 2560x1440 (QHD)   | 9         | 5.26%   |
| 1600x900 (HD+)    | 7         | 4.09%   |
| 1440x900 (WXGA+)  | 5         | 2.92%   |
| 1920x1200 (WUXGA) | 4         | 2.34%   |
| 1280x800 (WXGA)   | 4         | 2.34%   |
| 3840x2160 (4K)    | 3         | 1.75%   |
| 2880x1800         | 3         | 1.75%   |
| 3840x2400         | 1         | 0.58%   |
| 3200x1800 (QHD+)  | 1         | 0.58%   |
| 3000x2000         | 1         | 0.58%   |
| 2256x1504         | 1         | 0.58%   |
| 1920x1280         | 1         | 0.58%   |
| 1600x1200         | 1         | 0.58%   |
| 1360x768          | 1         | 0.58%   |
| 1280x1024 (SXGA)  | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 72        | 38.1%   |
| 13      | 27        | 14.29%  |
| 14      | 22        | 11.64%  |
| 24      | 12        | 6.35%   |
| 17      | 10        | 5.29%   |
| 27      | 9         | 4.76%   |
| 23      | 6         | 3.17%   |
| 12      | 5         | 2.65%   |
| 31      | 4         | 2.12%   |
| 11      | 4         | 2.12%   |
| Unknown | 4         | 2.12%   |
| 21      | 3         | 1.59%   |
| 32      | 2         | 1.06%   |
| 19      | 2         | 1.06%   |
| 18      | 2         | 1.06%   |
| 54      | 1         | 0.53%   |
| 48      | 1         | 0.53%   |
| 44      | 1         | 0.53%   |
| 29      | 1         | 0.53%   |
| 22      | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 106       | 57.3%   |
| 501-600     | 23        | 12.43%  |
| 201-300     | 21        | 11.35%  |
| 351-400     | 14        | 7.57%   |
| 401-500     | 7         | 3.78%   |
| 601-700     | 5         | 2.7%    |
| Unknown     | 4         | 2.16%   |
| 701-800     | 2         | 1.08%   |
| 1001-1500   | 2         | 1.08%   |
| 901-1000    | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 132       | 83.02%  |
| 16/10   | 18        | 11.32%  |
| Unknown | 4         | 2.52%   |
| 3/2     | 3         | 1.89%   |
| 5/4     | 1         | 0.63%   |
| 4/3     | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 38.3%   |
| 81-90          | 40        | 21.28%  |
| 201-250        | 17        | 9.04%   |
| 71-80          | 9         | 4.79%   |
| 301-350        | 9         | 4.79%   |
| 121-130        | 9         | 4.79%   |
| 351-500        | 7         | 3.72%   |
| 61-70          | 5         | 2.66%   |
| 51-60          | 4         | 2.13%   |
| 251-300        | 4         | 2.13%   |
| Unknown        | 4         | 2.13%   |
| More than 1000 | 2         | 1.06%   |
| 151-200        | 2         | 1.06%   |
| 141-150        | 2         | 1.06%   |
| 131-140        | 1         | 0.53%   |
| 501-1000       | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 76        | 41.99%  |
| 101-120       | 49        | 27.07%  |
| 51-100        | 33        | 18.23%  |
| 161-240       | 9         | 4.97%   |
| More than 240 | 6         | 3.31%   |
| 1-50          | 4         | 2.21%   |
| Unknown       | 4         | 2.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 116       | 75.32%  |
| 2     | 29        | 18.83%  |
| 3     | 6         | 3.9%    |
| 0     | 3         | 1.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 96        | 38.71%  |
| Realtek Semiconductor    | 82        | 33.06%  |
| Qualcomm Atheros         | 33        | 13.31%  |
| Broadcom                 | 13        | 5.24%   |
| Broadcom Limited         | 6         | 2.42%   |
| Ralink                   | 4         | 1.61%   |
| Marvell Technology Group | 4         | 1.61%   |
| Hewlett-Packard          | 3         | 1.21%   |
| Sierra Wireless          | 1         | 0.4%    |
| NetGear                  | 1         | 0.4%    |
| MEDIATEK                 | 1         | 0.4%    |
| Lenovo                   | 1         | 0.4%    |
| Huawei Technologies      | 1         | 0.4%    |
| ASIX Electronics         | 1         | 0.4%    |
| Apple                    | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 17.16%  |
| Intel Wi-Fi 6 AX200                                               | 21        | 6.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.96%   |
| Intel Wireless 8265 / 8275                                        | 12        | 3.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 3.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 2.31%   |
| Intel Wireless 8260                                               | 7         | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.98%   |
| Intel Wireless-AC 9260                                            | 6         | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.32%   |
| Intel Wireless 7265                                               | 4         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.99%   |
| Intel Wireless 3165                                               | 3         | 0.99%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.66%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.66%   |
| Intel WiFi Link 5100                                              | 2         | 0.66%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.66%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.66%   |
| HP un2430 Mobile Broadband Module                                 | 2         | 0.66%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 2         | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.66%   |
| Sierra Wireless EM7305                                            | 1         | 0.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.33%   |
| Realtek 802.11ac NIC                                              | 1         | 0.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 93        | 58.86%  |
| Qualcomm Atheros      | 26        | 16.46%  |
| Realtek Semiconductor | 16        | 10.13%  |
| Broadcom              | 11        | 6.96%   |
| Broadcom Limited      | 5         | 3.16%   |
| Ralink                | 4         | 2.53%   |
| Sierra Wireless       | 1         | 0.63%   |
| NetGear               | 1         | 0.63%   |
| MEDIATEK              | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 21        | 13.21%  |
| Intel Wireless 8265 / 8275                                     | 12        | 7.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 4.4%    |
| Intel Wireless 8260                                            | 7         | 4.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 3.77%   |
| Intel Wireless-AC 9260                                         | 6         | 3.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.52%   |
| Intel Wireless 7265                                            | 4         | 2.52%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 2.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.89%   |
| Intel Wireless 3165                                            | 3         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.26%   |
| Intel WiFi Link 5100                                           | 2         | 1.26%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.26%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.26%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.26%   |
| Sierra Wireless EM7305                                         | 1         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.63%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.63%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.63%   |
| Realtek 802.11ac NIC                                           | 1         | 0.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.63%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.63%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 0.63%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.63%   |
| Intel Wireless 7260                                            | 1         | 0.63%   |
| Intel Wireless 3160                                            | 1         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.63%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.63%   |
| Intel Centrino Wireless-N 2200                                 | 1         | 0.63%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.63%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 0.63%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 0.63%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.63%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                        | 1         | 0.63%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 0.63%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 0.63%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter             | 1         | 0.63%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 75        | 55.56%  |
| Intel                    | 34        | 25.19%  |
| Qualcomm Atheros         | 12        | 8.89%   |
| Broadcom                 | 5         | 3.7%    |
| Marvell Technology Group | 4         | 2.96%   |
| Lenovo                   | 1         | 0.74%   |
| Hewlett-Packard          | 1         | 0.74%   |
| Broadcom Limited         | 1         | 0.74%   |
| ASIX Electronics         | 1         | 0.74%   |
| Apple                    | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 36.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 9.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 8.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 8.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 2.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.13%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.13%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.42%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.42%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.42%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.71%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.71%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.71%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.71%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.71%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.71%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.71%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.71%   |
| Apple iBridge                                                     | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 53.36%  |
| Ethernet | 129       | 45.58%  |
| Modem    | 3         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 142       | 62.83%  |
| Ethernet | 83        | 36.73%  |
| Modem    | 1         | 0.44%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 124       | 82.12%  |
| 1     | 27        | 17.88%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 135       | 87.66%  |
| Yes  | 19        | 12.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 53.91%  |
| Qualcomm Atheros Communications | 11        | 8.59%   |
| Broadcom                        | 10        | 7.81%   |
| Realtek Semiconductor           | 8         | 6.25%   |
| Lite-On Technology              | 8         | 6.25%   |
| Apple                           | 5         | 3.91%   |
| Foxconn / Hon Hai               | 4         | 3.13%   |
| Hewlett-Packard                 | 3         | 2.34%   |
| Dell                            | 3         | 2.34%   |
| Ralink                          | 2         | 1.56%   |
| IMC Networks                    | 2         | 1.56%   |
| Toshiba                         | 1         | 0.78%   |
| Realtek                         | 1         | 0.78%   |
| Cambridge Silicon Radio         | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 26        | 20.31%  |
| Intel AX200 Bluetooth                                                               | 20        | 15.63%  |
| Intel Bluetooth Device                                                              | 7         | 5.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 5.47%   |
| Intel AX201 Bluetooth                                                               | 5         | 3.91%   |
| Realtek Bluetooth Radio                                                             | 4         | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.34%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 2.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.34%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 2.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 2.34%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.56%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.56%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.56%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.56%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.78%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.78%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.78%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.78%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.78%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.78%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.78%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.78%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.78%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.78%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.78%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.78%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.78%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.78%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.78%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.78%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 131       | 63.29%  |
| Nvidia                    | 31        | 14.98%  |
| AMD                       | 24        | 11.59%  |
| Realtek Semiconductor     | 6         | 2.9%    |
| Kingston Technology       | 2         | 0.97%   |
| GN Netcom                 | 2         | 0.97%   |
| Sennheiser Communications | 1         | 0.48%   |
| Razer USA                 | 1         | 0.48%   |
| Plantronics               | 1         | 0.48%   |
| Lenovo                    | 1         | 0.48%   |
| JMTek                     | 1         | 0.48%   |
| Hewlett-Packard           | 1         | 0.48%   |
| Generalplus Technology    | 1         | 0.48%   |
| Conexant Systems          | 1         | 0.48%   |
| CMX Systems               | 1         | 0.48%   |
| C-Media Electronics       | 1         | 0.48%   |
| Apple                     | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 10.64%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 6.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 5.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 4.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.98%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.98%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.98%   |
| Realtek Semiconductor USB Audio                                                                   | 6         | 2.55%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.13%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.7%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.7%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.7%    |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.7%    |
| AMD FCH Azalia Controller                                                                         | 4         | 1.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Nvidia Audio device                                                                               | 2         | 0.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.85%   |
| Sennheiser Communications Sennheiser DECT                                                         | 1         | 0.43%   |
| Razer USA Razer Kraken Tournament Edition                                                         | 1         | 0.43%   |
| Plantronics C320-M                                                                                | 1         | 0.43%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.43%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 0.43%   |
| Kingston Technology HyperX Cloud Stinger Wireless                                                 | 1         | 0.43%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.43%   |
| JMTek USB Audio Device                                                                            | 1         | 0.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.43%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.43%   |
| Hewlett-Packard USB Audio                                                                         | 1         | 0.43%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.43%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.43%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.43%   |
| Conexant Systems Hi Res USB-C AUDIO                                                               | 1         | 0.43%   |
| CMX Systems USB Audio Device                                                                      | 1         | 0.43%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 0.43%   |
| Apple Audio Device                                                                                | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 33.93%  |
| SK Hynix            | 29        | 25.89%  |
| Micron Technology   | 12        | 10.71%  |
| Crucial             | 7         | 6.25%   |
| Kingston            | 6         | 5.36%   |
| Unknown             | 3         | 2.68%   |
| Ramaxel Technology  | 3         | 2.68%   |
| A-DATA Technology   | 3         | 2.68%   |
| Smart               | 2         | 1.79%   |
| Unknown             | 2         | 1.79%   |
| Teikon              | 1         | 0.89%   |
| SMART Brazil        | 1         | 0.89%   |
| Nanya Technology    | 1         | 0.89%   |
| Kingmax             | 1         | 0.89%   |
| Elpida              | 1         | 0.89%   |
| Corsair             | 1         | 0.89%   |
| ASint Technology    | 1         | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 5         | 4.13%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s          | 5         | 4.13%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s       | 3         | 2.48%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s        | 3         | 2.48%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.65%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 2         | 1.65%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 2         | 1.65%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 2         | 1.65%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s        | 2         | 1.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 1.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 2         | 1.65%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s          | 2         | 1.65%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s          | 2         | 1.65%   |
| Unknown                                                         | 2         | 1.65%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR3                           | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                   | 1         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR3                           | 1         | 0.83%   |
| Teikon RAM TMT451S6BFR8A-PBAJ 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s | 1         | 0.83%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s               | 1         | 0.83%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 0.83%   |
| SK Hynix RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.83%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                | 1         | 0.83%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.83%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.83%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.83%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.83%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.83%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s       | 1         | 0.83%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s               | 1         | 0.83%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s          | 1         | 0.83%   |
| SK Hynix RAM HMT125S6AFR8C-G7 2048MB SODIMM DDR3 1067MT/s       | 1         | 0.83%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s    | 1         | 0.83%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s       | 1         | 0.83%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s       | 1         | 0.83%   |
| SK Hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s          | 1         | 0.83%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 0.83%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 0.83%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 0.83%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s       | 1         | 0.83%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.83%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s          | 1         | 0.83%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.83%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 0.83%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s        | 1         | 0.83%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s        | 1         | 0.83%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s        | 1         | 0.83%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| Samsung RAM M471B2874EH1-CF8 1024MB SODIMM 1067MT/s             | 1         | 0.83%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s        | 1         | 0.83%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s          | 1         | 0.83%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 53        | 53%     |
| DDR3    | 37        | 37%     |
| SDRAM   | 3         | 3%      |
| LPDDR4  | 2         | 2%      |
| LPDDR3  | 2         | 2%      |
| DDR2    | 1         | 1%      |
| DDR     | 1         | 1%      |
| Unknown | 1         | 1%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 92        | 95.83%  |
| Row Of Chips | 4         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 39        | 36.79%  |
| 8192  | 32        | 30.19%  |
| 16384 | 21        | 19.81%  |
| 32768 | 6         | 5.66%   |
| 2048  | 6         | 5.66%   |
| 1024  | 2         | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 28        | 25.93%  |
| 1600    | 26        | 24.07%  |
| 3200    | 14        | 12.96%  |
| 2133    | 7         | 6.48%   |
| 1334    | 7         | 6.48%   |
| 1333    | 7         | 6.48%   |
| 2400    | 6         | 5.56%   |
| 1067    | 4         | 3.7%    |
| 4199    | 3         | 2.78%   |
| 667     | 2         | 1.85%   |
| 3733    | 1         | 0.93%   |
| 3266    | 1         | 0.93%   |
| 1867    | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

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
| Chicony Electronics                    | 42        | 30.43%  |
| Acer                                   | 17        | 12.32%  |
| Sunplus Innovation Technology          | 12        | 8.7%    |
| Realtek Semiconductor                  | 12        | 8.7%    |
| Microdia                               | 8         | 5.8%    |
| IMC Networks                           | 8         | 5.8%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.07%   |
| Silicon Motion                         | 5         | 3.62%   |
| Quanta                                 | 5         | 3.62%   |
| Syntek                                 | 4         | 2.9%    |
| Suyin                                  | 4         | 2.9%    |
| Apple                                  | 4         | 2.9%    |
| Lite-On Technology                     | 2         | 1.45%   |
| Sonix Technology                       | 1         | 0.72%   |
| Ricoh                                  | 1         | 0.72%   |
| Primax Electronics                     | 1         | 0.72%   |
| Luxvisions Innotech Limited            | 1         | 0.72%   |
| LG Electronics                         | 1         | 0.72%   |
| Generalplus Technology                 | 1         | 0.72%   |
| Creative Technology                    | 1         | 0.72%   |
| Alcor Micro                            | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                                          | 11        | 7.97%   |
| Chicony USB2.0 Camera                                                      | 8         | 5.8%    |
| Realtek Integrated_Webcam_HD                                               | 5         | 3.62%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 3.62%   |
| Chicony Integrated Camera                                                  | 5         | 3.62%   |
| Chicony HP HD Camera                                                       | 4         | 2.9%    |
| Acer HD Webcam                                                             | 4         | 2.9%    |
| Sunplus Asus Webcam                                                        | 3         | 2.17%   |
| Acer BisonCam,NB Pro                                                       | 3         | 2.17%   |
| Acer BisonCam, NB Pro                                                      | 3         | 2.17%   |
| Suyin HP Truevision HD                                                     | 2         | 1.45%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.45%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.45%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 1.45%   |
| IMC Networks VGA UVC WebCam                                                | 2         | 1.45%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 1.45%   |
| IMC Networks Integrated Camera                                             | 2         | 1.45%   |
| Chicony Integrated Camera [ThinkPad]                                       | 2         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 2         | 1.45%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 1.45%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                                       | 1         | 0.72%   |
| Syntek USB2.0 Camera                                                       | 1         | 0.72%   |
| Syntek Integrated Camera                                                   | 1         | 0.72%   |
| Syntek EasyCamera                                                          | 1         | 0.72%   |
| Suyin HD WebCam                                                            | 1         | 0.72%   |
| Suyin Acer HD Crystal Eye webcam                                           | 1         | 0.72%   |
| Sunplus USB Camera                                                         | 1         | 0.72%   |
| Sunplus MTD Camera                                                         | 1         | 0.72%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 0.72%   |
| Sunplus Laptop Integrated WebCam HD                                        | 1         | 0.72%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 0.72%   |
| Sunplus HD WebCam                                                          | 1         | 0.72%   |
| Sunplus Aukey-PC-LM1E Camera                                               | 1         | 0.72%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.72%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 0.72%   |
| Silicon Motion WebCam SC-10HDD13335N                                       | 1         | 0.72%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.72%   |
| Silicon Motion Web Camera                                                  | 1         | 0.72%   |
| Silicon Motion HP Webcam-50                                                | 1         | 0.72%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 1         | 0.72%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 0.72%   |
| Realtek Integrated Webcam HD                                               | 1         | 0.72%   |
| Realtek Integrated Webcam                                                  | 1         | 0.72%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 0.72%   |
| Realtek HD WebCam                                                          | 1         | 0.72%   |
| Quanta VGA WebCam                                                          | 1         | 0.72%   |
| Quanta LG Webcam                                                           | 1         | 0.72%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                       | 1         | 0.72%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 0.72%   |
| Quanta HD User Facing                                                      | 1         | 0.72%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 0.72%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 0.72%   |
| Lite-On HP TrueVision HD Camera                                            | 1         | 0.72%   |
| Lite-On HP HD Webcam                                                       | 1         | 0.72%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)                      | 1         | 0.72%   |
| IMC Networks USB 2.0 Camera                                                | 1         | 0.72%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 0.72%   |
| Generalplus GENERAL WEBCAM                                                 | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 43.24%  |
| Synaptics                  | 12        | 32.43%  |
| LighTuning Technology      | 4         | 10.81%  |
| Shenzhen Goodix Technology | 3         | 8.11%   |
| Elan Microelectronics      | 1         | 2.7%    |
| AuthenTec                  | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 13.51%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 10.81%  |
| Unknown                                                                    | 4         | 10.81%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 8.11%   |
| Synaptics WBDI Device                                                      | 3         | 8.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 8.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 5.41%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 5.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 5.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.7%    |
| Validity Sensors VFS491                                                    | 1         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.7%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.7%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.7%    |
| LighTuning Fingerprint Reader                                              | 1         | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.7%    |
| Elan ELAN:Fingerprint                                                      | 1         | 2.7%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.7%    |

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
| 0     | 78        | 50.98%  |
| 1     | 59        | 38.56%  |
| 2     | 14        | 9.15%   |
| 4     | 1         | 0.65%   |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 42.05%  |
| Graphics card            | 14        | 15.91%  |
| Chipcard                 | 12        | 13.64%  |
| Communication controller | 9         | 10.23%  |
| Net/wireless             | 6         | 6.82%   |
| Multimedia controller    | 3         | 3.41%   |
| Storage                  | 2         | 2.27%   |
| Bluetooth                | 2         | 2.27%   |
| Net/ethernet             | 1         | 1.14%   |
| Card reader              | 1         | 1.14%   |
| Camera                   | 1         | 1.14%   |


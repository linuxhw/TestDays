Linux in Pakistan - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Pakistan.

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

Total: 227

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6420              | [8c12f58910](https://linux-hardware.org/?probe=8c12f58910) | May 01, 2022 |
| HP            | EliteBook 840 G1            | [411c79850c](https://linux-hardware.org/?probe=411c79850c) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [59a49b2d04](https://linux-hardware.org/?probe=59a49b2d04) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | [3e0d410668](https://linux-hardware.org/?probe=3e0d410668) | Apr 19, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [1974bfe63a](https://linux-hardware.org/?probe=1974bfe63a) | Apr 15, 2022 |
| Dell          | Latitude 3520               | [ee204b07aa](https://linux-hardware.org/?probe=ee204b07aa) | Apr 11, 2022 |
| HP            | Pavilion TS 11              | [9a817f6695](https://linux-hardware.org/?probe=9a817f6695) | Apr 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Dell          | Latitude 7480               | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [1936ee53b3](https://linux-hardware.org/?probe=1936ee53b3) | Mar 22, 2022 |
| Dell          | Latitude 7480               | [1083fec58a](https://linux-hardware.org/?probe=1083fec58a) | Mar 19, 2022 |
| Dell          | Latitude 7480               | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Lenovo        | V110-15IKB 80TH             | [a3aeef468a](https://linux-hardware.org/?probe=a3aeef468a) | Mar 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e0169c3e87](https://linux-hardware.org/?probe=e0169c3e87) | Feb 23, 2022 |
| HP            | EliteBook Folio 9470m       | [1aa838368f](https://linux-hardware.org/?probe=1aa838368f) | Feb 20, 2022 |
| HP            | EliteBook Folio 9470m       | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| Dell          | Inspiron 3501               | [7fdd5b66fc](https://linux-hardware.org/?probe=7fdd5b66fc) | Feb 14, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a5407aa128](https://linux-hardware.org/?probe=a5407aa128) | Feb 13, 2022 |
| Dell          | Inspiron 5547               | [2d6ff07a82](https://linux-hardware.org/?probe=2d6ff07a82) | Feb 12, 2022 |
| Dell          | Inspiron 3501               | [0dd77f2f7a](https://linux-hardware.org/?probe=0dd77f2f7a) | Feb 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [5a9a256568](https://linux-hardware.org/?probe=5a9a256568) | Feb 01, 2022 |
| Dell          | Inspiron 3501               | [4a0c4a62b7](https://linux-hardware.org/?probe=4a0c4a62b7) | Feb 01, 2022 |
| Dell          | Inspiron 3501               | [4ec888dcf3](https://linux-hardware.org/?probe=4ec888dcf3) | Jan 23, 2022 |
| Dell          | Inspiron 3501               | [c902cc42a6](https://linux-hardware.org/?probe=c902cc42a6) | Jan 18, 2022 |
| Dell          | Inspiron 3501               | [8c3d53b10f](https://linux-hardware.org/?probe=8c3d53b10f) | Jan 10, 2022 |
| Dell          | Inspiron 3501               | [ce839c3628](https://linux-hardware.org/?probe=ce839c3628) | Jan 08, 2022 |
| Lenovo        | ThinkPad T540p 20BFS5630... | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| HP            | EliteBook Folio 9470m       | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| Acer          | Aspire ES1-411              | [9a5ebb6379](https://linux-hardware.org/?probe=9a5ebb6379) | Dec 19, 2021 |
| HP            | EliteBook 8470p             | [0f7389c7d9](https://linux-hardware.org/?probe=0f7389c7d9) | Dec 14, 2021 |
| Dell          | Inspiron 5515               | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| HP            | ZBook 15 G3                 | [e662c8b956](https://linux-hardware.org/?probe=e662c8b956) | Dec 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [538c96bb62](https://linux-hardware.org/?probe=538c96bb62) | Nov 26, 2021 |
| Dell          | Latitude E6440              | [e0e5edfc03](https://linux-hardware.org/?probe=e0e5edfc03) | Nov 24, 2021 |
| HP            | Unknown                     | [ef28d45f68](https://linux-hardware.org/?probe=ef28d45f68) | Nov 23, 2021 |
| Dell          | G3 3579                     | [38e9f54ba1](https://linux-hardware.org/?probe=38e9f54ba1) | Nov 23, 2021 |
| Dell          | Inspiron 5520               | [6c6e631ffc](https://linux-hardware.org/?probe=6c6e631ffc) | Nov 20, 2021 |
| HP            | Unknown                     | [23dc38032d](https://linux-hardware.org/?probe=23dc38032d) | Nov 20, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [cd386145b8](https://linux-hardware.org/?probe=cd386145b8) | Nov 18, 2021 |
| HP            | Pavilion Laptop 14-ce2xx... | [f9ebb771b0](https://linux-hardware.org/?probe=f9ebb771b0) | Nov 14, 2021 |
| HP            | ZBook 15 G3                 | [67e5184b17](https://linux-hardware.org/?probe=67e5184b17) | Nov 13, 2021 |
| Dell          | Vostro 1500                 | [23aeb68ca2](https://linux-hardware.org/?probe=23aeb68ca2) | Nov 11, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1f56d374c2](https://linux-hardware.org/?probe=1f56d374c2) | Nov 10, 2021 |
| HP            | ZBook 15 G3                 | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Dell          | Inspiron 3501               | [5d35bd9e4a](https://linux-hardware.org/?probe=5d35bd9e4a) | Nov 07, 2021 |
| Dell          | Inspiron 15-3567            | [630a9144f1](https://linux-hardware.org/?probe=630a9144f1) | Nov 06, 2021 |
| HP            | 650                         | [c32592cabb](https://linux-hardware.org/?probe=c32592cabb) | Oct 20, 2021 |
| Apple         | MacBookPro14,1              | [bb1aa448fd](https://linux-hardware.org/?probe=bb1aa448fd) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [a47cdaa2ba](https://linux-hardware.org/?probe=a47cdaa2ba) | Oct 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c7fc550482](https://linux-hardware.org/?probe=c7fc550482) | Oct 16, 2021 |
| HP            | ProBook 450 G7              | [f2a84de135](https://linux-hardware.org/?probe=f2a84de135) | Oct 12, 2021 |
| Dell          | Latitude E5570              | [938d1a781d](https://linux-hardware.org/?probe=938d1a781d) | Oct 08, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [33137c7c23](https://linux-hardware.org/?probe=33137c7c23) | Oct 07, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [196fa579f8](https://linux-hardware.org/?probe=196fa579f8) | Oct 04, 2021 |
| Haier         | Y11C                        | [74b9ee5509](https://linux-hardware.org/?probe=74b9ee5509) | Oct 03, 2021 |
| Dell          | Precision M6400             | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| Haier         | Y11C                        | [591740bf00](https://linux-hardware.org/?probe=591740bf00) | Sep 27, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [691e7c2746](https://linux-hardware.org/?probe=691e7c2746) | Sep 27, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [867c13bfc7](https://linux-hardware.org/?probe=867c13bfc7) | Sep 25, 2021 |
| Dell          | Inspiron 5515               | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [297d4f4563](https://linux-hardware.org/?probe=297d4f4563) | Sep 13, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [758884ad15](https://linux-hardware.org/?probe=758884ad15) | Sep 12, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [d0e2e19e84](https://linux-hardware.org/?probe=d0e2e19e84) | Sep 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [966a09526a](https://linux-hardware.org/?probe=966a09526a) | Aug 14, 2021 |
| Dell          | Inspiron 3542               | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Dell          | Inspiron 5570               | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| Dell          | Inspiron 5593               | [1f6017347e](https://linux-hardware.org/?probe=1f6017347e) | Aug 05, 2021 |
| Dell          | Latitude E5250              | [f50f84a6a3](https://linux-hardware.org/?probe=f50f84a6a3) | Jul 26, 2021 |
| Dell          | Latitude E5250              | [9806ab15ab](https://linux-hardware.org/?probe=9806ab15ab) | Jul 25, 2021 |
| Dell          | Latitude E5250              | [9a475d76a4](https://linux-hardware.org/?probe=9a475d76a4) | Jul 25, 2021 |
| Dell          | Latitude E5250              | [d65621a003](https://linux-hardware.org/?probe=d65621a003) | Jul 16, 2021 |
| HP            | EliteBook 8440p             | [d89b69a6a3](https://linux-hardware.org/?probe=d89b69a6a3) | Jul 16, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d320594f42](https://linux-hardware.org/?probe=d320594f42) | Jul 07, 2021 |
| Lenovo        | ThinkPad E14 20RA007SAD     | [eb51ce8f36](https://linux-hardware.org/?probe=eb51ce8f36) | Jul 07, 2021 |
| Dell          | Precision 5530              | [7d267375f2](https://linux-hardware.org/?probe=7d267375f2) | Jul 05, 2021 |
| Dell          | Inspiron 5593               | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | [f5ac8e2aca](https://linux-hardware.org/?probe=f5ac8e2aca) | Jun 25, 2021 |
| HP            | Pavilion dv6                | [c3529dc2aa](https://linux-hardware.org/?probe=c3529dc2aa) | Jun 24, 2021 |
| Dell          | Precision M6400             | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| Dell          | Latitude 3510               | [79c73e5595](https://linux-hardware.org/?probe=79c73e5595) | Jun 09, 2021 |
| Toshiba       | Satellite L850              | [6beced18da](https://linux-hardware.org/?probe=6beced18da) | May 23, 2021 |
| Dell          | Vostro 14-3468              | [1742ee5823](https://linux-hardware.org/?probe=1742ee5823) | May 21, 2021 |
| Dell          | Latitude E5250              | [8c3b8c27c8](https://linux-hardware.org/?probe=8c3b8c27c8) | May 10, 2021 |
| Dell          | Latitude E6420              | [6e3288ca3a](https://linux-hardware.org/?probe=6e3288ca3a) | Apr 11, 2021 |
| Dell          | Inspiron 17-7779            | [2cf1f86b67](https://linux-hardware.org/?probe=2cf1f86b67) | Apr 06, 2021 |
| Gigabyte      | AERO 15-SA                  | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Gigabyte      | AERO 15-SA                  | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Dell          | Latitude 3510               | [1ef27c1786](https://linux-hardware.org/?probe=1ef27c1786) | Mar 25, 2021 |
| HP            | EliteBook 2170p             | [eba311c4d7](https://linux-hardware.org/?probe=eba311c4d7) | Mar 22, 2021 |
| HP            | EliteBook 2170p             | [e506fc315e](https://linux-hardware.org/?probe=e506fc315e) | Mar 21, 2021 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [eb713030d2](https://linux-hardware.org/?probe=eb713030d2) | Mar 18, 2021 |
| Dell          | Latitude E6420              | [c2b9bcc5fc](https://linux-hardware.org/?probe=c2b9bcc5fc) | Mar 12, 2021 |
| Dell          | Latitude E6420              | [a062baeb24](https://linux-hardware.org/?probe=a062baeb24) | Mar 12, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [6dbe550700](https://linux-hardware.org/?probe=6dbe550700) | Feb 28, 2021 |
| HP            | EliteBook 840 G3            | [b8a8ea9182](https://linux-hardware.org/?probe=b8a8ea9182) | Feb 24, 2021 |
| HP            | EliteBook 840 G3            | [ce415da689](https://linux-hardware.org/?probe=ce415da689) | Feb 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [64c73f58bb](https://linux-hardware.org/?probe=64c73f58bb) | Feb 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [0426a1c07e](https://linux-hardware.org/?probe=0426a1c07e) | Feb 20, 2021 |
| HP            | 14                          | [d5382b721f](https://linux-hardware.org/?probe=d5382b721f) | Feb 11, 2021 |
| Toshiba       | Satellite S50t-B            | [2fe86bc977](https://linux-hardware.org/?probe=2fe86bc977) | Feb 06, 2021 |
| Toshiba       | Satellite S50t-B            | [ec72426035](https://linux-hardware.org/?probe=ec72426035) | Feb 05, 2021 |
| Toshiba       | Satellite S50t-B            | [f7709c05cb](https://linux-hardware.org/?probe=f7709c05cb) | Feb 05, 2021 |
| HP            | 14                          | [f27a999e26](https://linux-hardware.org/?probe=f27a999e26) | Feb 03, 2021 |
| Sony          | SVE15126CXS                 | [8a27b129a3](https://linux-hardware.org/?probe=8a27b129a3) | Feb 02, 2021 |
| Apple         | MacBookPro16,2              | [e3790fd911](https://linux-hardware.org/?probe=e3790fd911) | Jan 31, 2021 |
| Apple         | MacBookPro16,2              | [0ee13de953](https://linux-hardware.org/?probe=0ee13de953) | Jan 31, 2021 |
| Lenovo        | ThinkPad E15 20RD0088UE     | [d2bfe04a2b](https://linux-hardware.org/?probe=d2bfe04a2b) | Jan 28, 2021 |
| HP            | ProBook 450 G5              | [e4b829fff8](https://linux-hardware.org/?probe=e4b829fff8) | Jan 26, 2021 |
| HP            | ProBook 450 G2              | [7db1cae3c0](https://linux-hardware.org/?probe=7db1cae3c0) | Jan 25, 2021 |
| HP            | ProBook 450 G5              | [0421fbf0d1](https://linux-hardware.org/?probe=0421fbf0d1) | Jan 25, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [1620987d4a](https://linux-hardware.org/?probe=1620987d4a) | Jan 17, 2021 |
| Lenovo        | ThinkPad T460 20FMS39800    | [7b4f78f648](https://linux-hardware.org/?probe=7b4f78f648) | Jan 10, 2021 |
| Dell          | Latitude E6510              | [2557f813e4](https://linux-hardware.org/?probe=2557f813e4) | Dec 15, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b04b3b207e](https://linux-hardware.org/?probe=b04b3b207e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E752               | [252afde67a](https://linux-hardware.org/?probe=252afde67a) | Dec 08, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [f84c7affac](https://linux-hardware.org/?probe=f84c7affac) | Dec 07, 2020 |
| Dell          | Latitude E7440              | [0d04075b3e](https://linux-hardware.org/?probe=0d04075b3e) | Dec 03, 2020 |
| Lenovo        | ThinkPad W500 40612HU       | [06465bf227](https://linux-hardware.org/?probe=06465bf227) | Dec 01, 2020 |
| Lenovo        | ThinkPad T60 1951WAT        | [4da418a597](https://linux-hardware.org/?probe=4da418a597) | Nov 28, 2020 |
| Dell          | Latitude E7440              | [386c1552c2](https://linux-hardware.org/?probe=386c1552c2) | Nov 28, 2020 |
| Dell          | Latitude E7450              | [20ee05f0fa](https://linux-hardware.org/?probe=20ee05f0fa) | Nov 27, 2020 |
| Dell          | Latitude E7440              | [9627b61c6f](https://linux-hardware.org/?probe=9627b61c6f) | Nov 25, 2020 |
| Dell          | Latitude E7450              | [e9a83f5dc5](https://linux-hardware.org/?probe=e9a83f5dc5) | Nov 24, 2020 |
| HP            | EliteBook 2540p             | [00a011fa83](https://linux-hardware.org/?probe=00a011fa83) | Nov 22, 2020 |
| HP            | EliteBook 2540p             | [12f4630385](https://linux-hardware.org/?probe=12f4630385) | Nov 22, 2020 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [a52f064714](https://linux-hardware.org/?probe=a52f064714) | Nov 19, 2020 |
| Dell          | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| HP            | 650                         | [67e06d1514](https://linux-hardware.org/?probe=67e06d1514) | Nov 09, 2020 |
| HP            | Pavilion g6                 | [98124ff6a4](https://linux-hardware.org/?probe=98124ff6a4) | Nov 08, 2020 |
| HP            | EliteBook 8470p             | [847807840d](https://linux-hardware.org/?probe=847807840d) | Nov 05, 2020 |
| HP            | ProBook 6560b               | [934ffc99e6](https://linux-hardware.org/?probe=934ffc99e6) | Oct 30, 2020 |
| Dell          | Inspiron 15-3567            | [2b138e461a](https://linux-hardware.org/?probe=2b138e461a) | Oct 26, 2020 |
| Dell          | Inspiron 15-3567            | [4460c27fd7](https://linux-hardware.org/?probe=4460c27fd7) | Oct 26, 2020 |
| Dell          | Inspiron 15-3567            | [b647bae107](https://linux-hardware.org/?probe=b647bae107) | Oct 24, 2020 |
| Apple         | MacBookAir6,2               | [3509d2f6e3](https://linux-hardware.org/?probe=3509d2f6e3) | Oct 22, 2020 |
| Toshiba       | PORTEGE Z30-B               | [d7c9922a29](https://linux-hardware.org/?probe=d7c9922a29) | Oct 21, 2020 |
| HP            | ProBook 4340s               | [3db4ff09f4](https://linux-hardware.org/?probe=3db4ff09f4) | Oct 18, 2020 |
| Dell          | Latitude E6540              | [36688dde6e](https://linux-hardware.org/?probe=36688dde6e) | Oct 06, 2020 |
| HP            | 650                         | [1ea9bf783e](https://linux-hardware.org/?probe=1ea9bf783e) | Oct 03, 2020 |
| HP            | ProBook 450 G5              | [94eb24ff74](https://linux-hardware.org/?probe=94eb24ff74) | Oct 02, 2020 |
| Dell          | Latitude E4300              | [12b944fb30](https://linux-hardware.org/?probe=12b944fb30) | Oct 02, 2020 |
| HP            | ProBook 450 G5              | [cb2cef5fcf](https://linux-hardware.org/?probe=cb2cef5fcf) | Oct 01, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [caf12cb57f](https://linux-hardware.org/?probe=caf12cb57f) | Sep 30, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [d3cc62a7f5](https://linux-hardware.org/?probe=d3cc62a7f5) | Sep 30, 2020 |
| Dell          | Latitude E7450              | [7df34be11f](https://linux-hardware.org/?probe=7df34be11f) | Sep 29, 2020 |
| Dell          | Latitude E7450              | [8149a50311](https://linux-hardware.org/?probe=8149a50311) | Sep 29, 2020 |
| Samsung       | QX311/QX411/QX412/QX511     | [b6f7494e44](https://linux-hardware.org/?probe=b6f7494e44) | Sep 21, 2020 |
| HP            | 650                         | [278a9afdeb](https://linux-hardware.org/?probe=278a9afdeb) | Sep 21, 2020 |
| Dell          | Vostro 14-3468              | [4ab76fd5c2](https://linux-hardware.org/?probe=4ab76fd5c2) | Sep 20, 2020 |
| HP            | 650                         | [8aaa8d7e4d](https://linux-hardware.org/?probe=8aaa8d7e4d) | Sep 19, 2020 |
| Samsung       | QX311/QX411/QX412/QX511     | [1ec83fe97e](https://linux-hardware.org/?probe=1ec83fe97e) | Sep 17, 2020 |
| HP            | EliteBook 840 G3            | [d6204bd9e2](https://linux-hardware.org/?probe=d6204bd9e2) | Sep 16, 2020 |
| Dell          | Inspiron 5567               | [a9d66d8f86](https://linux-hardware.org/?probe=a9d66d8f86) | Sep 15, 2020 |
| HP            | ProBook 455 G7              | [d84e4c8838](https://linux-hardware.org/?probe=d84e4c8838) | Sep 13, 2020 |
| HP            | ENVY 17                     | [08285409ad](https://linux-hardware.org/?probe=08285409ad) | Sep 13, 2020 |
| HP            | ProBook 455 G7              | [290aad9d0d](https://linux-hardware.org/?probe=290aad9d0d) | Sep 12, 2020 |
| HP            | ProBook 450 G7              | [85d0104e28](https://linux-hardware.org/?probe=85d0104e28) | Sep 10, 2020 |
| Dell          | Inspiron 15-3573            | [9be442a7dd](https://linux-hardware.org/?probe=9be442a7dd) | Sep 07, 2020 |
| HP            | ProBook 650 G1              | [77a7f39ace](https://linux-hardware.org/?probe=77a7f39ace) | Sep 05, 2020 |
| HP            | ProBook 440 G7              | [1c4d1f875b](https://linux-hardware.org/?probe=1c4d1f875b) | Sep 01, 2020 |
| HP            | ProBook 4340s               | [f7580ed51b](https://linux-hardware.org/?probe=f7580ed51b) | Aug 31, 2020 |
| HP            | ProBook 650 G1              | [310f83bb90](https://linux-hardware.org/?probe=310f83bb90) | Aug 30, 2020 |
| HP            | ProBook 650 G1              | [9dc2283eb6](https://linux-hardware.org/?probe=9dc2283eb6) | Aug 30, 2020 |
| Dell          | Latitude E7250              | [ff13c002c8](https://linux-hardware.org/?probe=ff13c002c8) | Aug 27, 2020 |
| HP            | EliteBook 820 G2            | [f35b20067d](https://linux-hardware.org/?probe=f35b20067d) | Aug 25, 2020 |
| HP            | Laptop 15-da2xxx            | [031606a1a9](https://linux-hardware.org/?probe=031606a1a9) | Aug 21, 2020 |
| Dell          | Latitude E7250              | [fc9b9e1e52](https://linux-hardware.org/?probe=fc9b9e1e52) | Aug 19, 2020 |
| Dell          | Latitude E7250              | [63024e0df6](https://linux-hardware.org/?probe=63024e0df6) | Aug 19, 2020 |
| HP            | ProBook 450 G7              | [8a5fc0bc23](https://linux-hardware.org/?probe=8a5fc0bc23) | Aug 13, 2020 |
| HP            | ProBook 440 G5              | [fa604583d6](https://linux-hardware.org/?probe=fa604583d6) | Aug 10, 2020 |
| HP            | ProBook 440 G5              | [255da50641](https://linux-hardware.org/?probe=255da50641) | Aug 10, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | [930fbc43ed](https://linux-hardware.org/?probe=930fbc43ed) | Aug 09, 2020 |
| HP            | Pavilion Notebook           | [f62759a869](https://linux-hardware.org/?probe=f62759a869) | Aug 05, 2020 |
| Dell          | Inspiron 15-3567            | [4af4cdfef7](https://linux-hardware.org/?probe=4af4cdfef7) | Jul 30, 2020 |
| HP            | ProBook 440 G7              | [4b38ecdae9](https://linux-hardware.org/?probe=4b38ecdae9) | Jul 28, 2020 |
| HP            | EliteBook 840 G2            | [9dbea8590b](https://linux-hardware.org/?probe=9dbea8590b) | Jul 19, 2020 |
| HP            | ProBook 450 G7              | [45478d9106](https://linux-hardware.org/?probe=45478d9106) | Jul 18, 2020 |
| HP            | ProBook 470 G2              | [c42c686ae8](https://linux-hardware.org/?probe=c42c686ae8) | Jul 09, 2020 |
| Motion Com... | J3500                       | [fd07831802](https://linux-hardware.org/?probe=fd07831802) | Jul 04, 2020 |
| HP            | ProBook 450 G3              | [a12518d58c](https://linux-hardware.org/?probe=a12518d58c) | Jun 30, 2020 |
| Dell          | Latitude E6440              | [a7fe187945](https://linux-hardware.org/?probe=a7fe187945) | Jun 28, 2020 |
| Haier         | Y11C                        | [6b98c2c449](https://linux-hardware.org/?probe=6b98c2c449) | Jun 23, 2020 |
| Haier         | Y11C                        | [621a9398df](https://linux-hardware.org/?probe=621a9398df) | Jun 23, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | [8c8ed3d489](https://linux-hardware.org/?probe=8c8ed3d489) | Jun 06, 2020 |
| Haier         | Y11C                        | [7f9f93809f](https://linux-hardware.org/?probe=7f9f93809f) | Jun 01, 2020 |
| Dell          | Latitude E6410              | [60757c8504](https://linux-hardware.org/?probe=60757c8504) | May 21, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | [86a1d31e5c](https://linux-hardware.org/?probe=86a1d31e5c) | May 21, 2020 |
| Dell          | Latitude E7450              | [1031b89b4b](https://linux-hardware.org/?probe=1031b89b4b) | May 12, 2020 |
| HP            | EliteBook Folio 1040 G1     | [34b0697bf6](https://linux-hardware.org/?probe=34b0697bf6) | May 10, 2020 |
| Dell          | Latitude E6320              | [cedc2c5001](https://linux-hardware.org/?probe=cedc2c5001) | May 10, 2020 |
| Acer          | Aspire E5-576               | [581af37cda](https://linux-hardware.org/?probe=581af37cda) | Apr 19, 2020 |
| Dell          | Latitude E5420              | [6d2ddeb934](https://linux-hardware.org/?probe=6d2ddeb934) | Apr 18, 2020 |
| Dell          | Inspiron 5567               | [6cc6232ddf](https://linux-hardware.org/?probe=6cc6232ddf) | Apr 14, 2020 |
| HP            | EliteBook 6930p             | [ea52c08646](https://linux-hardware.org/?probe=ea52c08646) | Apr 09, 2020 |
| Dell          | Latitude E4300              | [5e38d54ea2](https://linux-hardware.org/?probe=5e38d54ea2) | Mar 18, 2020 |
| HP            | EliteBook 6930p             | [541f4675eb](https://linux-hardware.org/?probe=541f4675eb) | Mar 14, 2020 |
| HP            | EliteBook 8440p             | [cd13c97ddb](https://linux-hardware.org/?probe=cd13c97ddb) | Mar 11, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [3cd2a73254](https://linux-hardware.org/?probe=3cd2a73254) | Mar 09, 2020 |
| HP            | Pavilion dv7                | [c727a0fa74](https://linux-hardware.org/?probe=c727a0fa74) | Jan 27, 2020 |
| HP            | EliteBook 8470p             | [e257c71d0b](https://linux-hardware.org/?probe=e257c71d0b) | Jan 14, 2020 |
| HP            | ProBook 450 G3              | [f73167982a](https://linux-hardware.org/?probe=f73167982a) | Jan 01, 2020 |
| Dell          | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| Dell          | Latitude XT3                | [4ccaa2e0e2](https://linux-hardware.org/?probe=4ccaa2e0e2) | Oct 29, 2019 |
| Lenovo        | ThinkPad T440 20B7S1NK05    | [310405c604](https://linux-hardware.org/?probe=310405c604) | Oct 29, 2019 |
| HP            | EliteBook 6930p             | [856fcded98](https://linux-hardware.org/?probe=856fcded98) | Oct 25, 2019 |
| HP            | Unknown                     | [25dd8af3ee](https://linux-hardware.org/?probe=25dd8af3ee) | Oct 22, 2019 |
| HP            | EliteBook 6930p             | [43c8f2b72c](https://linux-hardware.org/?probe=43c8f2b72c) | Sep 13, 2019 |
| HP            | EliteBook 6930p             | [964e933faf](https://linux-hardware.org/?probe=964e933faf) | Sep 13, 2019 |
| Samsung       | 940Z5L                      | [28c94787df](https://linux-hardware.org/?probe=28c94787df) | Sep 13, 2019 |
| AMI           | Board                       | [407590d103](https://linux-hardware.org/?probe=407590d103) | Sep 09, 2019 |
| HP            | ProBook 6470b               | [81e17acdb1](https://linux-hardware.org/?probe=81e17acdb1) | Aug 02, 2019 |
| HP            | EliteBook 840 G3            | [b419735d70](https://linux-hardware.org/?probe=b419735d70) | Jul 04, 2019 |
| Sony          | VPCCB490X                   | [ed39416136](https://linux-hardware.org/?probe=ed39416136) | Jun 22, 2019 |
| Haier         | Y11C                        | [ab6b2cf0e5](https://linux-hardware.org/?probe=ab6b2cf0e5) | Jun 20, 2019 |
| Haier         | Y11C                        | [74a3547ed6](https://linux-hardware.org/?probe=74a3547ed6) | Jun 20, 2019 |
| Dell          | Latitude E6420              | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell          | Latitude E6420              | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Haier         | Y11B                        | [d90f70d18f](https://linux-hardware.org/?probe=d90f70d18f) | May 11, 2019 |
| Haier         | Y11B                        | [e359a25a69](https://linux-hardware.org/?probe=e359a25a69) | Nov 18, 2018 |
| Haier         | Y11B                        | [13e5308d20](https://linux-hardware.org/?probe=13e5308d20) | Nov 18, 2018 |
| HP            | Pavilion Notebook           | [7e2949f7da](https://linux-hardware.org/?probe=7e2949f7da) | Nov 11, 2018 |
| Acer          | Aspire 5733                 | [970a40e3d0](https://linux-hardware.org/?probe=970a40e3d0) | Oct 23, 2018 |
| ASUSTek       | K53U                        | [f644624e98](https://linux-hardware.org/?probe=f644624e98) | Oct 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 63        | 39.38%  |
| Ubuntu 18.04        | 21        | 13.13%  |
| Ubuntu 21.04        | 4         | 2.5%    |
| KDE neon 20.04      | 4         | 2.5%    |
| Ubuntu 22.04        | 3         | 1.88%   |
| Ubuntu 21.10        | 3         | 1.88%   |
| Ubuntu 19.04        | 3         | 1.88%   |
| Pop!_OS 21.04       | 3         | 1.88%   |
| Pop!_OS 20.10       | 3         | 1.88%   |
| Pop!_OS 20.04       | 3         | 1.88%   |
| Linux Mint 20       | 3         | 1.88%   |
| Fedora 33           | 3         | 1.88%   |
| Arch                | 3         | 1.88%   |
| Zorin 15            | 2         | 1.25%   |
| Ubuntu 16.04        | 2         | 1.25%   |
| OpenMandriva 4.2    | 2         | 1.25%   |
| Linux Mint 20.2     | 2         | 1.25%   |
| Linux Mint 20.1     | 2         | 1.25%   |
| Elementary 6.1      | 2         | 1.25%   |
| Zorin 16            | 1         | 0.63%   |
| Zorin 12            | 1         | 0.63%   |
| Xero Rolling        | 1         | 0.63%   |
| Ubuntu 19.10        | 1         | 0.63%   |
| Ubuntu 18.10        | 1         | 0.63%   |
| ROSA R10            | 1         | 0.63%   |
| RHEL 8              | 1         | 0.63%   |
| Parrot 4.10         | 1         | 0.63%   |
| Oracle Linux 8.4    | 1         | 0.63%   |
| OpenMandriva 4.3    | 1         | 0.63%   |
| Manjaro 21.1.2      | 1         | 0.63%   |
| Manjaro 20.1        | 1         | 0.63%   |
| Manjaro             | 1         | 0.63%   |
| LinuxFX 11          | 1         | 0.63%   |
| Linux Mint 20.3     | 1         | 0.63%   |
| Kubuntu 21.04       | 1         | 0.63%   |
| Kubuntu 20.10       | 1         | 0.63%   |
| Kali 2020.3         | 1         | 0.63%   |
| Fedora 35           | 1         | 0.63%   |
| Fedora 34           | 1         | 0.63%   |
| Fedora 31           | 1         | 0.63%   |
| Fedora 30           | 1         | 0.63%   |
| Endless 3.8.0       | 1         | 0.63%   |
| Endless 3.7.8       | 1         | 0.63%   |
| EndeavourOS Rolling | 1         | 0.63%   |
| Deepin 15.10        | 1         | 0.63%   |
| Debian 11           | 1         | 0.63%   |
| Clear Linux 34640   | 1         | 0.63%   |
| ArcoLinux 20.1.4    | 1         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 101       | 64.74%  |
| Pop!_OS      | 8         | 5.13%   |
| Linux Mint   | 7         | 4.49%   |
| Fedora       | 6         | 3.85%   |
| Zorin        | 4         | 2.56%   |
| KDE neon     | 4         | 2.56%   |
| OpenMandriva | 3         | 1.92%   |
| Arch         | 3         | 1.92%   |
| Manjaro      | 2         | 1.28%   |
| Kubuntu      | 2         | 1.28%   |
| Endless      | 2         | 1.28%   |
| Elementary   | 2         | 1.28%   |
| Xero         | 1         | 0.64%   |
| ROSA         | 1         | 0.64%   |
| RHEL         | 1         | 0.64%   |
| Parrot       | 1         | 0.64%   |
| Oracle Linux | 1         | 0.64%   |
| LinuxFX      | 1         | 0.64%   |
| Kali         | 1         | 0.64%   |
| EndeavourOS  | 1         | 0.64%   |
| Deepin       | 1         | 0.64%   |
| Debian       | 1         | 0.64%   |
| Clear Linux  | 1         | 0.64%   |
| ArcoLinux    | 1         | 0.64%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 5.4.0-42-generic                  | 9         | 5.23%   |
| 5.11.0-37-generic                 | 5         | 2.91%   |
| 5.4.0-48-generic                  | 4         | 2.33%   |
| 5.4.0-47-generic                  | 4         | 2.33%   |
| 5.4.0-40-generic                  | 4         | 2.33%   |
| 5.8.0-7630-generic                | 3         | 1.74%   |
| 5.8.0-41-generic                  | 3         | 1.74%   |
| 5.4.0-54-generic                  | 3         | 1.74%   |
| 5.4.0-52-generic                  | 3         | 1.74%   |
| 5.4.0-26-generic                  | 3         | 1.74%   |
| 5.3.0-28-generic                  | 3         | 1.74%   |
| 5.13.0-39-generic                 | 3         | 1.74%   |
| 5.13.0-30-generic                 | 3         | 1.74%   |
| 5.9.8-200.fc33.x86_64             | 2         | 1.16%   |
| 5.8.0-59-generic                  | 2         | 1.16%   |
| 5.8.0-48-generic                  | 2         | 1.16%   |
| 5.8.0-38-generic                  | 2         | 1.16%   |
| 5.4.0-91-generic                  | 2         | 1.16%   |
| 5.4.0-58-generic                  | 2         | 1.16%   |
| 5.4.0-45-generic                  | 2         | 1.16%   |
| 5.4.0-39-generic                  | 2         | 1.16%   |
| 5.4.0-33-generic                  | 2         | 1.16%   |
| 5.4.0-29-generic                  | 2         | 1.16%   |
| 5.15.0-25-generic                 | 2         | 1.16%   |
| 5.13.0-28-generic                 | 2         | 1.16%   |
| 5.11.0-7620-generic               | 2         | 1.16%   |
| 5.11.0-43-generic                 | 2         | 1.16%   |
| 5.11.0-41-generic                 | 2         | 1.16%   |
| 5.11.0-40-generic                 | 2         | 1.16%   |
| 5.11.0-38-generic                 | 2         | 1.16%   |
| 5.11.0-27-generic                 | 2         | 1.16%   |
| 5.10.14-desktop-1omv4002          | 2         | 1.16%   |
| 5.0.0-23-generic                  | 2         | 1.16%   |
| 4.15.0-66-generic                 | 2         | 1.16%   |
| 5.9.10-200.fc33.x86_64            | 1         | 0.58%   |
| 5.9.0-rc4+                        | 1         | 0.58%   |
| 5.8.3-2-MANJARO                   | 1         | 0.58%   |
| 5.8.0-kali2-amd64                 | 1         | 0.58%   |
| 5.8.0-7625-generic                | 1         | 0.58%   |
| 5.8.0-55-generic                  | 1         | 0.58%   |
| 5.8.0-45-generic                  | 1         | 0.58%   |
| 5.8.0-44-generic                  | 1         | 0.58%   |
| 5.8.0-43-generic                  | 1         | 0.58%   |
| 5.7.9-100.fc31.x86_64             | 1         | 0.58%   |
| 5.7.19-050719-generic             | 1         | 0.58%   |
| 5.7.0-2parrot2-amd64              | 1         | 0.58%   |
| 5.6.0-1048-oem                    | 1         | 0.58%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64 | 1         | 0.58%   |
| 5.4.15-arch1-1                    | 1         | 0.58%   |
| 5.4.0-99-generic                  | 1         | 0.58%   |
| 5.4.0-7642-generic                | 1         | 0.58%   |
| 5.4.0-7634-generic                | 1         | 0.58%   |
| 5.4.0-74-generic                  | 1         | 0.58%   |
| 5.4.0-70-generic                  | 1         | 0.58%   |
| 5.4.0-67-generic                  | 1         | 0.58%   |
| 5.4.0-59-generic                  | 1         | 0.58%   |
| 5.4.0-49-generic                  | 1         | 0.58%   |
| 5.4.0-37-generic                  | 1         | 0.58%   |
| 5.4.0-31-generic                  | 1         | 0.58%   |
| 5.4.0-19-generic                  | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 48        | 30.38%  |
| 5.11.0  | 19        | 12.03%  |
| 5.8.0   | 17        | 10.76%  |
| 5.13.0  | 13        | 8.23%   |
| 4.15.0  | 12        | 7.59%   |
| 5.3.0   | 7         | 4.43%   |
| 5.0.0   | 6         | 3.8%    |
| 5.15.0  | 3         | 1.9%    |
| 4.18.0  | 3         | 1.9%    |
| 5.9.8   | 2         | 1.27%   |
| 5.10.14 | 2         | 1.27%   |
| 5.10.0  | 2         | 1.27%   |
| 5.9.10  | 1         | 0.63%   |
| 5.9.0   | 1         | 0.63%   |
| 5.8.3   | 1         | 0.63%   |
| 5.7.9   | 1         | 0.63%   |
| 5.7.19  | 1         | 0.63%   |
| 5.7.0   | 1         | 0.63%   |
| 5.6.0   | 1         | 0.63%   |
| 5.4.17  | 1         | 0.63%   |
| 5.4.15  | 1         | 0.63%   |
| 5.2.13  | 1         | 0.63%   |
| 5.16.7  | 1         | 0.63%   |
| 5.16.15 | 1         | 0.63%   |
| 5.14.8  | 1         | 0.63%   |
| 5.14.2  | 1         | 0.63%   |
| 5.14.18 | 1         | 0.63%   |
| 5.14.11 | 1         | 0.63%   |
| 5.13.9  | 1         | 0.63%   |
| 5.13.7  | 1         | 0.63%   |
| 5.13.4  | 1         | 0.63%   |
| 5.13.13 | 1         | 0.63%   |
| 5.12.5  | 1         | 0.63%   |
| 5.12.12 | 1         | 0.63%   |
| 5.10.17 | 1         | 0.63%   |
| 4.9.124 | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 50        | 31.85%  |
| 5.11    | 19        | 12.1%   |
| 5.8     | 18        | 11.46%  |
| 5.13    | 17        | 10.83%  |
| 4.15    | 12        | 7.64%   |
| 5.3     | 7         | 4.46%   |
| 5.0     | 6         | 3.82%   |
| 5.10    | 5         | 3.18%   |
| 5.14    | 4         | 2.55%   |
| 5.9     | 3         | 1.91%   |
| 5.7     | 3         | 1.91%   |
| 5.15    | 3         | 1.91%   |
| 4.18    | 3         | 1.91%   |
| 5.16    | 2         | 1.27%   |
| 5.12    | 2         | 1.27%   |
| 5.6     | 1         | 0.64%   |
| 5.2     | 1         | 0.64%   |
| 4.9     | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 149       | 98.03%  |
| i686   | 3         | 1.97%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 106       | 66.67%  |
| Unknown       | 19        | 11.95%  |
| KDE5          | 9         | 5.66%   |
| X-Cinnamon    | 6         | 3.77%   |
| KDE           | 6         | 3.77%   |
| XFCE          | 3         | 1.89%   |
| Unity         | 3         | 1.89%   |
| Pantheon      | 2         | 1.26%   |
| MATE          | 1         | 0.63%   |
| KDE4          | 1         | 0.63%   |
| i3            | 1         | 0.63%   |
| GNOME Classic | 1         | 0.63%   |
| Deepin        | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 122       | 77.71%  |
| Wayland | 20        | 12.74%  |
| Unknown | 15        | 9.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 96        | 61.94%  |
| GDM     | 31        | 20%     |
| GDM3    | 15        | 9.68%   |
| TDM     | 4         | 2.58%   |
| SDDM    | 4         | 2.58%   |
| LightDM | 4         | 2.58%   |
| KDM     | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 130       | 84.42%  |
| Unknown | 17        | 11.04%  |
| en_GB   | 3         | 1.95%   |
| en_PK   | 2         | 1.3%    |
| ur_PK   | 1         | 0.65%   |
| C       | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 83        | 53.21%  |
| BIOS | 73        | 46.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 136       | 88.89%  |
| Btrfs   | 6         | 3.92%   |
| Overlay | 5         | 3.27%   |
| Unknown | 4         | 2.61%   |
| Zfs     | 1         | 0.65%   |
| Xfs     | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 110       | 71.43%  |
| GPT     | 33        | 21.43%  |
| MBR     | 11        | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 88.89%  |
| Yes       | 17        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 64.74%  |
| Yes       | 55        | 35.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 55        | 36.18%  |
| Dell                | 46        | 30.26%  |
| Lenovo              | 25        | 16.45%  |
| Haier               | 5         | 3.29%   |
| ASUSTek Computer    | 4         | 2.63%   |
| Toshiba             | 3         | 1.97%   |
| Apple               | 3         | 1.97%   |
| Acer                | 3         | 1.97%   |
| Sony                | 2         | 1.32%   |
| Samsung Electronics | 2         | 1.32%   |
| Motion Computing    | 1         | 0.66%   |
| Gigabyte Technology | 1         | 0.66%   |
| Fujitsu             | 1         | 0.66%   |
| AMI                 | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP ProBook 450 G7                    | 5         | 3.29%   |
| Lenovo ThinkBook 15-IIL 20SM         | 3         | 1.97%   |
| HP EliteBook 8470p                   | 3         | 1.97%   |
| HP EliteBook 840 G3                  | 3         | 1.97%   |
| Haier Y11C                           | 3         | 1.97%   |
| Dell Latitude E7450                  | 3         | 1.97%   |
| Dell Latitude E6420                  | 3         | 1.97%   |
| Lenovo ThinkBook 15-IML 20RW         | 2         | 1.32%   |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 2         | 1.32%   |
| HP ZBook 15 G3                       | 2         | 1.32%   |
| HP ProBook 450 G5                    | 2         | 1.32%   |
| HP ProBook 450 G3                    | 2         | 1.32%   |
| HP ProBook 440 G7                    | 2         | 1.32%   |
| HP Pavilion Notebook                 | 2         | 1.32%   |
| HP EliteBook 8440p                   | 2         | 1.32%   |
| HP EliteBook 840 G2                  | 2         | 1.32%   |
| HP EliteBook 6930p                   | 2         | 1.32%   |
| HP 650                               | 2         | 1.32%   |
| Haier Y11B                           | 2         | 1.32%   |
| Dell Vostro 14-3468                  | 2         | 1.32%   |
| Dell Latitude E6440                  | 2         | 1.32%   |
| Dell Latitude E5250                  | 2         | 1.32%   |
| Dell Latitude E4300                  | 2         | 1.32%   |
| Dell Latitude 3510                   | 2         | 1.32%   |
| Dell Inspiron 5593                   | 2         | 1.32%   |
| Dell Inspiron 3501                   | 2         | 1.32%   |
| Dell Inspiron 15-3567                | 2         | 1.32%   |
| Toshiba Satellite S50t-B             | 1         | 0.66%   |
| Toshiba Satellite L850               | 1         | 0.66%   |
| Toshiba PORTEGE Z30-B                | 1         | 0.66%   |
| Sony VPCCB490X                       | 1         | 0.66%   |
| Sony SVE15126CXS                     | 1         | 0.66%   |
| Samsung QX311/QX411/QX412/QX511      | 1         | 0.66%   |
| Samsung 940Z5L                       | 1         | 0.66%   |
| Motion Computing J3500               | 1         | 0.66%   |
| Lenovo V110-15IKB 80TH               | 1         | 0.66%   |
| Lenovo ThinkPad X220 Tablet 4298A11  | 1         | 0.66%   |
| Lenovo ThinkPad X201 3249CTO         | 1         | 0.66%   |
| Lenovo ThinkPad W500 40612HU         | 1         | 0.66%   |
| Lenovo ThinkPad T60 1951WAT          | 1         | 0.66%   |
| Lenovo ThinkPad T540p 20BFS56300     | 1         | 0.66%   |
| Lenovo ThinkPad T460 20FMS39800      | 1         | 0.66%   |
| Lenovo ThinkPad T440p 20AWS0DU00     | 1         | 0.66%   |
| Lenovo ThinkPad T440 20B7S1NK05      | 1         | 0.66%   |
| Lenovo ThinkPad E560 20EV0010UK      | 1         | 0.66%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GF00 | 1         | 0.66%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GE00 | 1         | 0.66%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GD00 | 1         | 0.66%   |
| Lenovo ThinkPad E15 Gen 2 20TD000QUE | 1         | 0.66%   |
| Lenovo ThinkPad E15 20RD0088UE       | 1         | 0.66%   |
| Lenovo ThinkPad E14 20RA007SAD       | 1         | 0.66%   |
| Lenovo IdeaPad L340-15IWL 81LG       | 1         | 0.66%   |
| Lenovo IdeaPad 510-15ISK 80SR        | 1         | 0.66%   |
| HP ProBook 6560b                     | 1         | 0.66%   |
| HP ProBook 650 G1                    | 1         | 0.66%   |
| HP ProBook 6470b                     | 1         | 0.66%   |
| HP ProBook 470 G2                    | 1         | 0.66%   |
| HP ProBook 455 G7                    | 1         | 0.66%   |
| HP ProBook 450 G8 Notebook PC        | 1         | 0.66%   |
| HP ProBook 450 G2                    | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 25        | 16.45%  |
| HP ProBook             | 20        | 13.16%  |
| HP EliteBook           | 19        | 12.5%   |
| Lenovo ThinkPad        | 15        | 9.87%   |
| Dell Inspiron          | 15        | 9.87%   |
| HP Pavilion            | 8         | 5.26%   |
| Lenovo ThinkBook       | 7         | 4.61%   |
| Haier Y11C             | 3         | 1.97%   |
| Dell Vostro            | 3         | 1.97%   |
| Acer Aspire            | 3         | 1.97%   |
| Toshiba Satellite      | 2         | 1.32%   |
| Lenovo IdeaPad         | 2         | 1.32%   |
| HP ZBook               | 2         | 1.32%   |
| HP 650                 | 2         | 1.32%   |
| Haier Y11B             | 2         | 1.32%   |
| Dell Precision         | 2         | 1.32%   |
| Toshiba PORTEGE        | 1         | 0.66%   |
| Sony VPCCB490X         | 1         | 0.66%   |
| Sony SVE15126CXS       | 1         | 0.66%   |
| Samsung QX311          | 1         | 0.66%   |
| Samsung 940Z5L         | 1         | 0.66%   |
| Motion Computing J3500 | 1         | 0.66%   |
| Lenovo V110-15IKB      | 1         | 0.66%   |
| HP Laptop              | 1         | 0.66%   |
| HP ENVY                | 1         | 0.66%   |
| HP 14                  | 1         | 0.66%   |
| Gigabyte AERO          | 1         | 0.66%   |
| Fujitsu LIFEBOOK       | 1         | 0.66%   |
| Dell G3                | 1         | 0.66%   |
| ASUS VivoBook          | 1         | 0.66%   |
| ASUS TUF               | 1         | 0.66%   |
| ASUS ROG               | 1         | 0.66%   |
| ASUS K53U              | 1         | 0.66%   |
| Apple MacBookPro16     | 1         | 0.66%   |
| Apple MacBookPro14     | 1         | 0.66%   |
| Apple MacBookAir6      | 1         | 0.66%   |
| AMI Board              | 1         | 0.66%   |
| Unknown                | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 21        | 13.82%  |
| 2011 | 17        | 11.18%  |
| 2020 | 15        | 9.87%   |
| 2016 | 15        | 9.87%   |
| 2017 | 12        | 7.89%   |
| 2014 | 12        | 7.89%   |
| 2013 | 11        | 7.24%   |
| 2012 | 11        | 7.24%   |
| 2018 | 9         | 5.92%   |
| 2015 | 9         | 5.92%   |
| 2010 | 6         | 3.95%   |
| 2008 | 6         | 3.95%   |
| 2021 | 4         | 2.63%   |
| 2009 | 2         | 1.32%   |
| 2007 | 1         | 0.66%   |
| 2006 | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 152       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 143       | 93.46%  |
| Enabled  | 10        | 6.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 53        | 34.64%  |
| 3.01-4.0   | 35        | 22.88%  |
| 16.01-24.0 | 30        | 19.61%  |
| 8.01-16.0  | 25        | 16.34%  |
| 32.01-64.0 | 6         | 3.92%   |
| 1.01-2.0   | 3         | 1.96%   |
| 24.01-32.0 | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 58        | 35.15%  |
| 1.01-2.0  | 54        | 32.73%  |
| 4.01-8.0  | 21        | 12.73%  |
| 3.01-4.0  | 21        | 12.73%  |
| 8.01-16.0 | 6         | 3.64%   |
| 0.51-1.0  | 5         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 74.51%  |
| 2      | 35        | 22.88%  |
| 3      | 2         | 1.31%   |
| 4      | 1         | 0.65%   |
| 0      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 69.28%  |
| Yes       | 47        | 30.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 93.42%  |
| No        | 10        | 6.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 99.34%  |
| No        | 1         | 0.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 72.26%  |
| No        | 43        | 27.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Pakistan | 152       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Lahore         | 57        | 36.08%  |
| Karachi        | 37        | 23.42%  |
| Islamabad      | 28        | 17.72%  |
| Rawalpindi     | 6         | 3.8%    |
| Faisalabad     | 6         | 3.8%    |
| Sargodha       | 2         | 1.27%   |
| Multan         | 2         | 1.27%   |
| Jhelum         | 2         | 1.27%   |
| Bahawalpur     | 2         | 1.27%   |
| Sukkur         | 1         | 0.63%   |
| Sialkot        | 1         | 0.63%   |
| Shekhupura     | 1         | 0.63%   |
| Shaidu         | 1         | 0.63%   |
| Rahim Yar Khan | 1         | 0.63%   |
| Peshawar       | 1         | 0.63%   |
| Model Colony   | 1         | 0.63%   |
| Mehar          | 1         | 0.63%   |
| Larkana        | 1         | 0.63%   |
| Lakki          | 1         | 0.63%   |
| Jhang City     | 1         | 0.63%   |
| Hassan Abdal   | 1         | 0.63%   |
| Dina           | 1         | 0.63%   |
| Daska Kalan    | 1         | 0.63%   |
| Chichawatni    | 1         | 0.63%   |
| Attock         | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 34     | 14.21%  |
| WDC                 | 26        | 34     | 13.68%  |
| Samsung Electronics | 24        | 26     | 12.63%  |
| Toshiba             | 21        | 23     | 11.05%  |
| Kingston            | 9         | 10     | 4.74%   |
| Transcend           | 8         | 8      | 4.21%   |
| Hitachi             | 8         | 10     | 4.21%   |
| Unknown             | 7         | 8      | 3.68%   |
| Intel               | 7         | 9      | 3.68%   |
| SanDisk             | 6         | 7      | 3.16%   |
| HGST                | 6         | 7      | 3.16%   |
| Micron Technology   | 5         | 5      | 2.63%   |
| SK Hynix            | 4         | 7      | 2.11%   |
| Silicon Motion      | 4         | 4      | 2.11%   |
| KIOXIA              | 3         | 3      | 1.58%   |
| Apple               | 3         | 4      | 1.58%   |
| LITEON              | 2         | 2      | 1.05%   |
| Lexar               | 2         | 2      | 1.05%   |
| HS-SSD-E100         | 2         | 2      | 1.05%   |
| Fujitsu             | 2         | 2      | 1.05%   |
| A-DATA Technology   | 2         | 2      | 1.05%   |
| Team                | 1         | 1      | 0.53%   |
| PNY                 | 1         | 4      | 0.53%   |
| Phison              | 1         | 2      | 0.53%   |
| PHD 3.0             | 1         | 1      | 0.53%   |
| LITEONIT            | 1         | 1      | 0.53%   |
| Kingsand            | 1         | 1      | 0.53%   |
| KESU                | 1         | 1      | 0.53%   |
| Integral            | 1         | 2      | 0.53%   |
| HS-SSD-E100N        | 1         | 1      | 0.53%   |
| CSD                 | 1         | 1      | 0.53%   |
| Biostar             | 1         | 1      | 0.53%   |
| Apacer              | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB             | 6         | 3.08%   |
| Toshiba MQ04ABF100 1TB               | 4         | 2.05%   |
| Toshiba MQ01ABF050 500GB             | 4         | 2.05%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 2.05%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 2.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 2.05%   |
| WDC PC SN530 NVMe 256GB              | 3         | 1.54%   |
| Silicon Motion NVMe SSD Drive 512GB  | 3         | 1.54%   |
| Samsung MZALQ512HALU-000L1 512GB     | 3         | 1.54%   |
| WDC WD10SPZX-75Z10T3 1TB             | 2         | 1.03%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 1.03%   |
| Transcend TS512GMTE110S 512GB        | 2         | 1.03%   |
| Transcend TS256GMTS830S 256GB SSD    | 2         | 1.03%   |
| Toshiba MQ01ACF050 500GB             | 2         | 1.03%   |
| Toshiba MQ01ABD050 500GB             | 2         | 1.03%   |
| Seagate ST9320423AS 320GB            | 2         | 1.03%   |
| Seagate ST9250315AS 250GB            | 2         | 1.03%   |
| Seagate ST9250311CS 250GB            | 2         | 1.03%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 1.03%   |
| SanDisk X110 MSATA 128GB SSD         | 2         | 1.03%   |
| KIOXIA NVMe SSD Drive 256GB          | 2         | 1.03%   |
| Intel SSDSA2M080G2GN 73GB            | 2         | 1.03%   |
| Intel NVMe SSD Drive 512GB           | 2         | 1.03%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 1.03%   |
| Hitachi HTS543225A7A384 250GB        | 2         | 1.03%   |
| HGST HTS541010B7E610 1TB             | 2         | 1.03%   |
| HGST HTS541010A9E680 1TB             | 2         | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.51%   |
| WDC WDS128G2G0B-00EPW0 128GB SSD     | 1         | 0.51%   |
| WDC WD5000LPVT-75G33T0 500GB         | 1         | 0.51%   |
| WDC WD2500BEVT-75A23T0 250GB         | 1         | 0.51%   |
| WDC WD2500BEVT-08A23T1 250GB         | 1         | 0.51%   |
| WDC WD2500BEVS-60UST0 250GB          | 1         | 0.51%   |
| WDC WD1600BEKT-08PVMT1 160GB         | 1         | 0.51%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 0.51%   |
| WDC WD10SPZX-22Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.51%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.51%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.51%   |
| WDC WD10JPVT-75A1YT0 1TB             | 1         | 0.51%   |
| WDC PC SN520 SDAPNUW-256G-1202 256GB | 1         | 0.51%   |
| WDC PC SN520 NVMe 512GB              | 1         | 0.51%   |
| Unknown SD8GB  7GB                   | 1         | 0.51%   |
| Unknown SD64G  64GB                  | 1         | 0.51%   |
| Unknown NVMe SSD Drive 256GB         | 1         | 0.51%   |
| Unknown NVMe SSD Drive 128GB         | 1         | 0.51%   |
| Unknown MMC Card  8GB                | 1         | 0.51%   |
| Unknown MMC Card  64GB               | 1         | 0.51%   |
| Unknown HDG8a4  128GB                | 1         | 0.51%   |
| Unknown External 1TB                 | 1         | 0.51%   |
| Transcend TS512GSSD230S 512GB        | 1         | 0.51%   |
| Transcend TS256GMTE110S 256GB        | 1         | 0.51%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.51%   |
| Transcend TS120GSSD220S 120GB        | 1         | 0.51%   |
| Toshiba THNSNF128GCSS 128GB SSD      | 1         | 0.51%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.51%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.51%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.51%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.51%   |
| Toshiba MK1656GSY 160GB              | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 34     | 31.03%  |
| WDC                 | 21        | 26     | 24.14%  |
| Toshiba             | 19        | 21     | 21.84%  |
| Hitachi             | 8         | 10     | 9.2%    |
| HGST                | 6         | 7      | 6.9%    |
| Fujitsu             | 2         | 2      | 2.3%    |
| Unknown             | 1         | 1      | 1.15%   |
| Samsung Electronics | 1         | 1      | 1.15%   |
| PHD 3.0             | 1         | 1      | 1.15%   |
| KESU                | 1         | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 17     | 27.59%  |
| Kingston            | 8         | 9      | 13.79%  |
| SanDisk             | 5         | 5      | 8.62%   |
| Transcend           | 4         | 4      | 6.9%    |
| Micron Technology   | 4         | 4      | 6.9%    |
| Intel               | 4         | 5      | 6.9%    |
| SK Hynix            | 3         | 6      | 5.17%   |
| WDC                 | 2         | 2      | 3.45%   |
| LITEON              | 2         | 2      | 3.45%   |
| Lexar               | 2         | 2      | 3.45%   |
| Toshiba             | 1         | 1      | 1.72%   |
| Team                | 1         | 1      | 1.72%   |
| PNY                 | 1         | 4      | 1.72%   |
| LITEONIT            | 1         | 1      | 1.72%   |
| Biostar             | 1         | 1      | 1.72%   |
| Apple               | 1         | 1      | 1.72%   |
| Apacer              | 1         | 1      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 83        | 104    | 44.86%  |
| SSD     | 58        | 67     | 31.35%  |
| NVMe    | 34        | 43     | 18.38%  |
| Unknown | 6         | 7      | 3.24%   |
| MMC     | 4         | 5      | 2.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 126       | 175    | 75.45%  |
| NVMe | 34        | 43     | 20.36%  |
| MMC  | 4         | 5      | 2.4%    |
| SAS  | 3         | 3      | 1.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 88        | 120    | 67.18%  |
| 0.51-1.0   | 43        | 51     | 32.82%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 42.14%  |
| 251-500        | 35        | 22.01%  |
| 51-100         | 29        | 18.24%  |
| 501-1000       | 13        | 8.18%   |
| 1-20           | 7         | 4.4%    |
| 21-50          | 5         | 3.14%   |
| 1001-2000      | 2         | 1.26%   |
| More than 3000 | 1         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 68        | 40.96%  |
| 21-50    | 51        | 30.72%  |
| 51-100   | 20        | 12.05%  |
| 101-250  | 16        | 9.64%   |
| 251-500  | 7         | 4.22%   |
| 501-1000 | 4         | 2.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 14.29%  |
| SK Hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 14.29%  |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 14.29%  |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 14.29%  |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 14.29%  |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Hitachi           | 2         | 2      | 28.57%  |
| WDC               | 1         | 1      | 14.29%  |
| SK Hynix          | 1         | 1      | 14.29%  |
| Seagate           | 1         | 1      | 14.29%  |
| Micron Technology | 1         | 1      | 14.29%  |
| Intel             | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 57.14%  |
| SSD  | 3         | 3      | 42.86%  |

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
| Detected | 108       | 163    | 68.79%  |
| Works    | 42        | 56     | 26.75%  |
| Malfunc  | 7         | 7      | 4.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 134       | 77.01%  |
| Samsung Electronics         | 7         | 4.02%   |
| Silicon Motion              | 6         | 3.45%   |
| Sandisk                     | 6         | 3.45%   |
| AMD                         | 6         | 3.45%   |
| KIOXIA                      | 5         | 2.87%   |
| Unknown                     | 2         | 1.15%   |
| Apple                       | 2         | 1.15%   |
| SK Hynix                    | 1         | 0.57%   |
| Realtek Semiconductor       | 1         | 0.57%   |
| Phison Electronics          | 1         | 0.57%   |
| Micron Technology           | 1         | 0.57%   |
| Marvell Technology Group    | 1         | 0.57%   |
| Kingston Technology Company | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 26        | 13.61%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 14        | 7.33%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 13        | 6.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 10        | 5.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 4.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 9         | 4.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 6         | 3.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 3.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 3.14%   |
| Samsung NVMe SSD Controller 980                                                        | 5         | 2.62%   |
| KIOXIA Non-Volatile memory controller                                                  | 5         | 2.62%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 5         | 2.62%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 5         | 2.62%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 2.62%   |
| Sandisk Non-Volatile memory controller                                                 | 4         | 2.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 2.09%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 1.57%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 3         | 1.57%   |
| Unknown Non-Volatile memory controller                                                 | 2         | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 1.05%   |
| Intel Non-Volatile memory controller                                                   | 2         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.05%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 1.05%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 2         | 1.05%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 0.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.52%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.52%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 0.52%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.52%   |
| Micron Non-Volatile memory controller                                                  | 1         | 0.52%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 1         | 0.52%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.52%   |
| Intel SSD 660P Series                                                                  | 1         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 0.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 0.52%   |
| Apple S3X NVMe Controller                                                              | 1         | 0.52%   |
| Apple ANS2 NVMe Controller                                                             | 1         | 0.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 119       | 65.38%  |
| NVMe | 34        | 18.68%  |
| RAID | 17        | 9.34%   |
| IDE  | 12        | 6.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 145       | 95.39%  |
| AMD    | 7         | 4.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 5.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 4.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 4.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 5         | 3.29%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 3.29%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 2.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 2.63%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 3         | 1.97%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.97%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 3         | 1.97%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 1.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.97%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 2         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 1.32%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 1.32%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 1.32%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 2         | 1.32%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 1.32%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.32%   |
| Intel Core i5-3427U CPU @ 1.80GHz       | 2         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 1.32%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 1.32%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 1.32%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 2         | 1.32%   |
| Intel Core i3-2328M CPU @ 2.20GHz       | 2         | 1.32%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 1.32%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz    | 2         | 1.32%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 1.32%   |
| Intel Pentium CPU B940 @ 2.00GHz        | 1         | 0.66%   |
| Intel Genuine CPU T2400 @ 1.83GHz       | 1         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.66%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 1         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 0.66%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 0.66%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 0.66%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 0.66%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 1         | 0.66%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.66%   |
| Intel Core i7-4558U CPU @ 2.80GHz       | 1         | 0.66%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 0.66%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 0.66%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 0.66%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 0.66%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 0.66%   |
| Intel Core i7 CPU U 680 @ 1.47GHz       | 1         | 0.66%   |
| Intel Core i7 CPU M 620 @ 2.67GHz       | 1         | 0.66%   |
| Intel Core i7 CPU L 640 @ 2.13GHz       | 1         | 0.66%   |
| Intel Core i5-7360U CPU @ 2.30GHz       | 1         | 0.66%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 0.66%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 1         | 0.66%   |
| Intel Core i5-4260U CPU @ 1.40GHz       | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 60        | 39.47%  |
| Intel Core i7        | 47        | 30.92%  |
| Other                | 10        | 6.58%   |
| Intel Core i3        | 9         | 5.92%   |
| Intel Core 2 Duo     | 7         | 4.61%   |
| Intel Core m3        | 3         | 1.97%   |
| Intel Celeron        | 3         | 1.97%   |
| Intel Core M         | 2         | 1.32%   |
| AMD Ryzen 7          | 2         | 1.32%   |
| Intel Pentium        | 1         | 0.66%   |
| Intel Genuine        | 1         | 0.66%   |
| Intel Core 2 Extreme | 1         | 0.66%   |
| Intel Atom           | 1         | 0.66%   |
| AMD Ryzen 9          | 1         | 0.66%   |
| AMD Ryzen 5          | 1         | 0.66%   |
| AMD E                | 1         | 0.66%   |
| AMD A6               | 1         | 0.66%   |
| AMD A12              | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 93        | 61.18%  |
| 4      | 51        | 33.55%  |
| 6      | 5         | 3.29%   |
| 8      | 3         | 1.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 152       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 132       | 86.84%  |
| 1      | 20        | 13.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 150       | 98.04%  |
| Unknown        | 2         | 1.31%   |
| 32-bit         | 1         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 15.29%  |
| 0x206a7    | 13        | 8.28%   |
| 0x806ec    | 12        | 7.64%   |
| 0x806e9    | 11        | 7.01%   |
| 0x406e3    | 10        | 6.37%   |
| 0x306d4    | 10        | 6.37%   |
| 0x806c1    | 9         | 5.73%   |
| 0x40651    | 8         | 5.1%    |
| 0x20655    | 8         | 5.1%    |
| 0x306a9    | 7         | 4.46%   |
| 0x806ea    | 6         | 3.82%   |
| 0x706e5    | 6         | 3.82%   |
| 0x306c3    | 6         | 3.82%   |
| 0x1067a    | 4         | 2.55%   |
| 0x906ea    | 3         | 1.91%   |
| 0x506e3    | 2         | 1.27%   |
| 0x30678    | 2         | 1.27%   |
| 0x10676    | 2         | 1.27%   |
| 0xa0660    | 1         | 0.64%   |
| 0xa0652    | 1         | 0.64%   |
| 0x906e9    | 1         | 0.64%   |
| 0x806eb    | 1         | 0.64%   |
| 0x706a1    | 1         | 0.64%   |
| 0x6fd      | 1         | 0.64%   |
| 0x406c4    | 1         | 0.64%   |
| 0x0a50000c | 1         | 0.64%   |
| 0x08608103 | 1         | 0.64%   |
| 0x08600106 | 1         | 0.64%   |
| 0x08600104 | 1         | 0.64%   |
| 0x0700010f | 1         | 0.64%   |
| 0x0600611a | 1         | 0.64%   |
| 0x05000119 | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 24.34%  |
| Haswell       | 17        | 11.18%  |
| SandyBridge   | 15        | 9.87%   |
| Skylake       | 14        | 9.21%   |
| Broadwell     | 12        | 7.89%   |
| TigerLake     | 10        | 6.58%   |
| IvyBridge     | 10        | 6.58%   |
| Westmere      | 9         | 5.92%   |
| Penryn        | 7         | 4.61%   |
| IceLake       | 6         | 3.95%   |
| Silvermont    | 3         | 1.97%   |
| Zen 2         | 2         | 1.32%   |
| CometLake     | 2         | 1.32%   |
| Zen 3         | 1         | 0.66%   |
| P6            | 1         | 0.66%   |
| Jaguar        | 1         | 0.66%   |
| Goldmont plus | 1         | 0.66%   |
| Excavator     | 1         | 0.66%   |
| Core          | 1         | 0.66%   |
| Bobcat        | 1         | 0.66%   |
| Unknown       | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 138       | 73.02%  |
| Nvidia | 26        | 13.76%  |
| AMD    | 25        | 13.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 7.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 7.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 5.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 5.24%   |
| Intel HD Graphics 5500                                                                   | 10        | 5.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 5.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.19%   |
| Intel HD Graphics 620                                                                    | 7         | 3.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 3.66%   |
| Intel UHD Graphics 620                                                                   | 6         | 3.14%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3.14%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 2.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.09%   |
| Intel HD Graphics 615                                                                    | 3         | 1.57%   |
| Intel HD Graphics 530                                                                    | 3         | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.05%   |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.05%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.05%   |
| Intel HD Graphics 5300                                                                   | 2         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.05%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 2         | 1.05%   |
| AMD Renoir                                                                               | 2         | 1.05%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.52%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.52%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.52%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.52%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.52%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.52%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.52%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.52%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.52%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.52%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.52%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.52%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.52%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 0.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.52%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.52%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.52%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.52%   |
| Intel HD Graphics 630                                                                    | 1         | 0.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.52%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.52%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 0.52%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.52%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.52%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.52%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.52%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 102       | 67.11%  |
| Intel + Nvidia | 21        | 13.82%  |
| Intel + AMD    | 15        | 9.87%   |
| 1 x AMD        | 9         | 5.92%   |
| 1 x Nvidia     | 4         | 2.63%   |
| AMD + Nvidia   | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 140       | 92.11%  |
| Proprietary | 11        | 7.24%   |
| Unknown     | 1         | 0.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 70.13%  |
| 1.01-2.0   | 24        | 15.58%  |
| 0.01-0.5   | 10        | 6.49%   |
| 3.01-4.0   | 6         | 3.9%    |
| 0.51-1.0   | 5         | 3.25%   |
| 5.01-6.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 41        | 25.79%  |
| Chimei Innolux          | 28        | 17.61%  |
| AU Optronics            | 27        | 16.98%  |
| BOE                     | 18        | 11.32%  |
| Samsung Electronics     | 14        | 8.81%   |
| Dell                    | 6         | 3.77%   |
| Chi Mei Optoelectronics | 5         | 3.14%   |
| Hewlett-Packard         | 3         | 1.89%   |
| Apple                   | 3         | 1.89%   |
| Sharp                   | 2         | 1.26%   |
| PANDA                   | 2         | 1.26%   |
| LG Philips              | 2         | 1.26%   |
| Lenovo                  | 2         | 1.26%   |
| KDC                     | 2         | 1.26%   |
| Sony                    | 1         | 0.63%   |
| LPL                     | 1         | 0.63%   |
| LGD                     | 1         | 0.63%   |
| Goldstar                | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 3.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 3.14%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 3         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 3         | 1.89%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.89%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 1.26%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 2         | 1.26%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 1.26%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.26%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 2         | 1.26%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 2         | 1.26%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.26%   |
| Hewlett-Packard 24f HPN3545 1920x1080 530x300mm 24.0-inch             | 2         | 1.26%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                     | 2         | 1.26%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 1.26%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch       | 2         | 1.26%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 2         | 1.26%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 1.26%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                 | 2         | 1.26%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO5024 1280x800 286x178mm 13.3-inch         | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 2         | 1.26%   |
| Sony TV SNYAC03 1360x768                                              | 1         | 0.63%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch               | 1         | 0.63%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.63%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 0.63%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC414A 1920x1080 294x165mm 13.3-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 0.63%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 0.63%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.63%   |
| LPL LCD Monitor 1440x900                                              | 1         | 0.63%   |
| LGD LCD Monitor 1920x1080                                             | 1         | 0.63%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.63%   |
| LG Philips LCD Monitor LGP9C1C 1024x768 285x214mm 14.0-inch           | 1         | 0.63%   |
| LG Display LP156WH2-TLR2 LGD027D 1366x768 344x194mm 15.5-inch         | 1         | 0.63%   |
| LG Display LCD Monitor LGD0684 1920x1080 344x194mm 15.5-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.63%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD0436 1920x1080 276x156mm 12.5-inch          | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 67        | 43.79%  |
| 1366x768 (WXGA)    | 59        | 38.56%  |
| 1600x900 (HD+)     | 7         | 4.58%   |
| 1280x800 (WXGA)    | 6         | 3.92%   |
| 3840x2160 (4K)     | 3         | 1.96%   |
| 1440x900 (WXGA+)   | 3         | 1.96%   |
| 1680x1050 (WSXGA+) | 2         | 1.31%   |
| 2880x1800          | 1         | 0.65%   |
| 2560x1600          | 1         | 0.65%   |
| 1920x1200 (WUXGA)  | 1         | 0.65%   |
| 1360x768           | 1         | 0.65%   |
| 1280x1024 (SXGA)   | 1         | 0.65%   |
| 1024x768 (XGA)     | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 75        | 47.47%  |
| 14      | 29        | 18.35%  |
| 13      | 20        | 12.66%  |
| 17      | 8         | 5.06%   |
| 12      | 6         | 3.8%    |
| 24      | 5         | 3.16%   |
| 11      | 4         | 2.53%   |
| 23      | 3         | 1.9%    |
| 21      | 3         | 1.9%    |
| Unknown | 2         | 1.27%   |
| 72      | 1         | 0.63%   |
| 20      | 1         | 0.63%   |
| 18      | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 111       | 71.15%  |
| 201-300     | 21        | 13.46%  |
| 351-400     | 9         | 5.77%   |
| 501-600     | 7         | 4.49%   |
| 401-500     | 5         | 3.21%   |
| Unknown     | 2         | 1.28%   |
| 1501-2000   | 1         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 130       | 87.84%  |
| 16/10   | 13        | 8.78%   |
| Unknown | 2         | 1.35%   |
| 5/4     | 1         | 0.68%   |
| 4/3     | 1         | 0.68%   |
| 3/2     | 1         | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 75        | 47.77%  |
| 81-90          | 38        | 24.2%   |
| 71-80          | 9         | 5.73%   |
| 201-250        | 9         | 5.73%   |
| 61-70          | 6         | 3.82%   |
| 121-130        | 5         | 3.18%   |
| 51-60          | 4         | 2.55%   |
| 151-200        | 2         | 1.27%   |
| 141-150        | 2         | 1.27%   |
| 131-140        | 2         | 1.27%   |
| 91-100         | 2         | 1.27%   |
| Unknown        | 2         | 1.27%   |
| More than 1000 | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 46.79%  |
| 101-120       | 55        | 35.26%  |
| 51-100        | 17        | 10.9%   |
| More than 240 | 4         | 2.56%   |
| 161-240       | 4         | 2.56%   |
| Unknown       | 2         | 1.28%   |
| 1-50          | 1         | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 139       | 91.45%  |
| 2     | 11        | 7.24%   |
| 3     | 1         | 0.66%   |
| 0     | 1         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 111       | 46.25%  |
| Realtek Semiconductor | 81        | 33.75%  |
| Qualcomm Atheros      | 17        | 7.08%   |
| Broadcom              | 11        | 4.58%   |
| Hewlett-Packard       | 4         | 1.67%   |
| Broadcom Limited      | 4         | 1.67%   |
| Ralink                | 3         | 1.25%   |
| Sierra Wireless       | 2         | 0.83%   |
| MediaTek              | 2         | 0.83%   |
| Dell                  | 2         | 0.83%   |
| Qualcomm              | 1         | 0.42%   |
| Huawei Technologies   | 1         | 0.42%   |
| D-Link                | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 19.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 4.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 4.17%   |
| Intel Wireless 7265                                               | 11        | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 3.53%   |
| Intel Wireless 3165                                               | 10        | 3.21%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 3.21%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 2.56%   |
| Intel Wireless 8260                                               | 7         | 2.24%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 2.24%   |
| Intel Wireless 7260                                               | 6         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.6%    |
| Intel Ultimate N WiFi Link 5300                                   | 5         | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.6%    |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.28%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.28%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 1.28%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.96%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.64%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.64%   |
| MediaTek NOA N2                                                   | 2         | 0.64%   |
| Intel Wireless-AC 9260                                            | 2         | 0.64%   |
| Intel Wireless 3160                                               | 2         | 0.64%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.64%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]              | 2         | 0.64%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 2         | 0.64%   |
| HP lt4112 Gobi 4G Module Network Device                           | 2         | 0.64%   |
| Dell Hub of E-Port Replicator                                     | 2         | 0.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.64%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.32%   |
| Sierra Wireless EM7305                                            | 1         | 0.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.32%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.32%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.32%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.32%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.32%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.32%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 106       | 66.67%  |
| Realtek Semiconductor | 16        | 10.06%  |
| Qualcomm Atheros      | 16        | 10.06%  |
| Broadcom              | 11        | 6.92%   |
| Ralink                | 3         | 1.89%   |
| Hewlett-Packard       | 2         | 1.26%   |
| Dell                  | 2         | 1.26%   |
| Sierra Wireless       | 1         | 0.63%   |
| D-Link                | 1         | 0.63%   |
| Broadcom Limited      | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 13        | 8.07%   |
| Intel Wireless 7265                                                  | 11        | 6.83%   |
| Intel Wireless 3165                                                  | 10        | 6.21%   |
| Intel Wi-Fi 6 AX201                                                  | 10        | 6.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 4.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 8         | 4.97%   |
| Intel Wireless 8260                                                  | 7         | 4.35%   |
| Intel Wireless 7260                                                  | 6         | 3.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 5         | 3.11%   |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 3.11%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 2.48%   |
| Intel Centrino Advanced-N 6235                                       | 4         | 2.48%   |
| Intel Centrino Advanced-N 6200                                       | 4         | 2.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 3         | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 1.86%   |
| Intel Wi-Fi 6 AX200                                                  | 3         | 1.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 3         | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.24%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 2         | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 1.24%   |
| Intel Wireless-AC 9260                                               | 2         | 1.24%   |
| Intel Wireless 3160                                                  | 2         | 1.24%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 1.24%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                 | 2         | 1.24%   |
| HP lt4112 Gobi 4G Module Network Device                              | 2         | 1.24%   |
| Dell Hub of E-Port Replicator                                        | 2         | 1.24%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 1.24%   |
| Sierra Wireless EM7305                                               | 1         | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.62%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 0.62%   |
| Intel Wireless 8265 / 8275                                           | 1         | 0.62%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 1         | 0.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 0.62%   |
| Intel Centrino Wireless-N 6150                                       | 1         | 0.62%   |
| Intel Centrino Wireless-N 2230                                       | 1         | 0.62%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 1         | 0.62%   |
| Intel Centrino Wireless-N + WiMAX 6150                               | 1         | 0.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 0.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 0.62%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 0.62%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 0.62%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                   | 1         | 0.62%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                   | 1         | 0.62%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                   | 1         | 0.62%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 0.62%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 78        | 53.06%  |
| Intel                 | 58        | 39.46%  |
| Broadcom Limited      | 3         | 2.04%   |
| MediaTek              | 2         | 1.36%   |
| Sierra Wireless       | 1         | 0.68%   |
| Qualcomm Atheros      | 1         | 0.68%   |
| Qualcomm              | 1         | 0.68%   |
| Huawei Technologies   | 1         | 0.68%   |
| Hewlett-Packard       | 1         | 0.68%   |
| Broadcom              | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 9.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 7.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 6.67%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 4.67%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.33%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.67%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.67%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 2.67%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 2%      |
| MediaTek NOA N2                                                   | 2         | 1.33%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.33%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 2         | 1.33%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.67%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.67%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.67%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.67%   |
| Huawei E353/E3131                                                 | 1         | 0.67%   |
| HP lt4211 Gobi 4G Module                                          | 1         | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.67%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.67%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 0.67%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 51.36%  |
| Ethernet | 142       | 48.3%   |
| Modem    | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 140       | 70%     |
| Ethernet | 60        | 30%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 137       | 89.54%  |
| 1     | 13        | 8.5%    |
| 0     | 2         | 1.31%   |
| 3     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 147       | 96.71%  |
| Yes  | 5         | 3.29%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 62.5%   |
| Qualcomm Atheros Communications | 11        | 9.82%   |
| Realtek Semiconductor           | 9         | 8.04%   |
| Broadcom                        | 8         | 7.14%   |
| Dell                            | 4         | 3.57%   |
| Ralink                          | 3         | 2.68%   |
| Hewlett-Packard                 | 2         | 1.79%   |
| Foxconn / Hon Hai               | 2         | 1.79%   |
| Lite-On Technology              | 1         | 0.89%   |
| IMC Networks                    | 1         | 0.89%   |
| Apple                           | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 35        | 31.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 16        | 14.29%  |
| Intel AX201 Bluetooth                              | 12        | 10.71%  |
| Qualcomm Atheros  Bluetooth Device                 | 7         | 6.25%   |
| Realtek Bluetooth Radio                            | 5         | 4.46%   |
| Realtek  Bluetooth 4.2 Adapter                     | 3         | 2.68%   |
| Ralink RT3290 Bluetooth                            | 3         | 2.68%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 3         | 2.68%   |
| Intel AX200 Bluetooth                              | 3         | 2.68%   |
| Broadcom HP Portable SoftSailing                   | 3         | 2.68%   |
| HP Broadcom 2070 Bluetooth Combo                   | 2         | 1.79%   |
| Dell DW375 Bluetooth Module                        | 2         | 1.79%   |
| Realtek RTL8821A Bluetooth                         | 1         | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 0.89%   |
| Qualcomm Atheros Bluetooth USB Host Controller     | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Bluetooth                  | 1         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth                  | 1         | 0.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 0.89%   |
| Intel Bluetooth Device                             | 1         | 0.89%   |
| IMC Networks Bluetooth Radio                       | 1         | 0.89%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller    | 1         | 0.89%   |
| Foxconn / Hon Hai BCM20702A0                       | 1         | 0.89%   |
| Dell Wireless 370 Bluetooth Mini-card              | 1         | 0.89%   |
| Dell Wireless 365 Bluetooth                        | 1         | 0.89%   |
| Broadcom HP Portable Valentine                     | 1         | 0.89%   |
| Broadcom HP Portable Bumble Bee                    | 1         | 0.89%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 1         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                        | 1         | 0.89%   |
| Apple Bluetooth USB Host Controller                | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 144       | 85.71%  |
| Nvidia                 | 9         | 5.36%   |
| AMD                    | 9         | 5.36%   |
| Logitech               | 2         | 1.19%   |
| Generalplus Technology | 2         | 1.19%   |
| Realtek Semiconductor  | 1         | 0.6%    |
| Apple                  | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 28        | 13.73%  |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 7.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 6.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 5.88%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 5.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 4.9%    |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 4.9%    |
| Intel 8 Series HD Audio Controller                                         | 10        | 4.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 4.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 3.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 3.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 3.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 2.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 1.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.98%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.98%   |
| Logitech Headset H340                                                      | 2         | 0.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.98%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.98%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.49%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.49%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.49%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.49%   |
| Intel Audio device                                                         | 1         | 0.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.49%   |
| Generalplus Technology USB Microphone                                      | 1         | 0.49%   |
| Generalplus Technology Usb Audio Device                                    | 1         | 0.49%   |
| Apple Audio Device                                                         | 1         | 0.49%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.49%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.49%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 24        | 28.24%  |
| Samsung Electronics | 21        | 24.71%  |
| Micron Technology   | 10        | 11.76%  |
| A-DATA Technology   | 6         | 7.06%   |
| Transcend           | 4         | 4.71%   |
| Crucial             | 4         | 4.71%   |
| Team                | 3         | 3.53%   |
| Lexar               | 3         | 3.53%   |
| Unknown             | 2         | 2.35%   |
| Spectek             | 2         | 2.35%   |
| Elpida              | 2         | 2.35%   |
| Unknown (768A)      | 1         | 1.18%   |
| Kingston            | 1         | 1.18%   |
| Hikvision           | 1         | 1.18%   |
| AXIOM               | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s                | 5         | 5.62%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s         | 3         | 3.37%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 3.37%   |
| Lexar RAM LD4AS016G-H2666G 16384MB SODIMM DDR4 2667MT/s       | 3         | 3.37%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 2         | 2.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                | 2         | 2.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 2         | 2.25%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 2         | 2.25%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 2         | 2.25%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s          | 2         | 2.25%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                   | 1         | 1.12%   |
| Unknown RAM DDR3 1600 8G 8GB SODIMM DDR3 1333MT/s             | 1         | 1.12%   |
| Unknown (768A) RAM Module 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| Transcend RAM Module 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.12%   |
| Transcend RAM Module 8192MB SODIMM DDR4 3200MT/s              | 1         | 1.12%   |
| Transcend RAM Module 16384MB SODIMM DDR4 2667MT/s             | 1         | 1.12%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| Spectek RAM Module 8GB Row Of Chips LPDDR3 1600MT/s           | 1         | 1.12%   |
| Spectek RAM Module 8192MB Row Of Chips LPDDR3 1600MT/s        | 1         | 1.12%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2667MT/s               | 1         | 1.12%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 1.12%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.12%   |
| SK Hynix RAM Module 4096MB SODIMM DDR4 2400MT/s               | 1         | 1.12%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1066MT/s                 | 1         | 1.12%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.12%   |
| SK Hynix RAM HMT451B6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.12%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s     | 1         | 1.12%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.12%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s    | 1         | 1.12%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2400MT/s                | 1         | 1.12%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2133MT/s               | 1         | 1.12%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.12%   |
| Samsung RAM M471B5273CH0-YK0 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.12%   |
| Samsung RAM M471B5173QHY-YK0 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.12%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.12%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s         | 1         | 1.12%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s         | 1         | 1.12%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 1.12%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.12%   |
| Micron RAM Module 4096MB SODIMM LPDDR3 2133MT/s               | 1         | 1.12%   |
| Micron RAM Module 4096MB SODIMM DDR4 3200MT/s                 | 1         | 1.12%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 1         | 1.12%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s      | 1         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 1         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2B1 8192MB Row Of Chips DDR4 3200MT/s | 1         | 1.12%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 40        | 58.82%  |
| DDR3   | 22        | 32.35%  |
| LPDDR3 | 3         | 4.41%   |
| LPDDR4 | 2         | 2.94%   |
| DDR    | 1         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 91.04%  |
| Row Of Chips | 5         | 7.46%   |
| DIMM         | 1         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 38.67%  |
| 4096  | 21        | 28%     |
| 16384 | 18        | 24%     |
| 2048  | 4         | 5.33%   |
| 32768 | 3         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 25        | 32.89%  |
| 1600  | 19        | 25%     |
| 3200  | 11        | 14.47%  |
| 2400  | 6         | 7.89%   |
| 2133  | 5         | 6.58%   |
| 1334  | 4         | 5.26%   |
| 1333  | 3         | 3.95%   |
| 4267  | 1         | 1.32%   |
| 1067  | 1         | 1.32%   |
| 1066  | 1         | 1.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Plustek | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 27.94%  |
| Microdia                               | 18        | 13.24%  |
| Cheng Uei Precision Industry (Foxlink) | 13        | 9.56%   |
| Sunplus Innovation Technology          | 11        | 8.09%   |
| Realtek Semiconductor                  | 9         | 6.62%   |
| Lite-On Technology                     | 8         | 5.88%   |
| Acer                                   | 6         | 4.41%   |
| Ricoh                                  | 5         | 3.68%   |
| Quanta                                 | 5         | 3.68%   |
| IMC Networks                           | 5         | 3.68%   |
| Suyin                                  | 4         | 2.94%   |
| Syntek                                 | 3         | 2.21%   |
| Silicon Motion                         | 3         | 2.21%   |
| Apple                                  | 2         | 1.47%   |
| Primax Electronics                     | 1         | 0.74%   |
| Pixart Imaging                         | 1         | 0.74%   |
| Logitech                               | 1         | 0.74%   |
| Lenovo                                 | 1         | 0.74%   |
| DigiTech                               | 1         | 0.74%   |
| 8SSC20F27145V1SR19P0BEK                | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 9         | 6.62%   |
| Chicony HP HD Camera                                                       | 8         | 5.88%   |
| Chicony Integrated Camera                                                  | 7         | 5.15%   |
| Sunplus Integrated_Webcam_HD                                               | 6         | 4.41%   |
| Microdia Integrated Webcam                                                 | 4         | 2.94%   |
| Lite-On HP HD Webcam                                                       | 4         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 4         | 2.94%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 2.21%   |
| Realtek Integrated Webcam                                                  | 3         | 2.21%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 2.21%   |
| Chicony USB 2.0Camera                                                      | 3         | 2.21%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 2.21%   |
| Acer Integrated Camera                                                     | 3         | 2.21%   |
| Syntek Integrated Camera                                                   | 2         | 1.47%   |
| Sunplus HP Universal Camera                                                | 2         | 1.47%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 1.47%   |
| Realtek USB2.0 camera                                                      | 2         | 1.47%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 1.47%   |
| Quanta HP HD Camera                                                        | 2         | 1.47%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 1.47%   |
| Lite-On Integrated Camera                                                  | 2         | 1.47%   |
| Lite-On HP HD Camera                                                       | 2         | 1.47%   |
| IMC Networks Integrated Camera                                             | 2         | 1.47%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.47%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 1.47%   |
| Chicony HP Truevision HD                                                   | 2         | 1.47%   |
| Chicony HP HD Webcam                                                       | 2         | 1.47%   |
| Chicony EasyCamera                                                         | 2         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 2         | 1.47%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 2         | 1.47%   |
| Syntek USB 2.0 PC Cam                                                      | 1         | 0.74%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 1         | 0.74%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.74%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.74%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.74%   |
| Sunplus Laptop Integrated Webcam HD                                        | 1         | 0.74%   |
| Sunplus Integrated Webcam                                                  | 1         | 0.74%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 0.74%   |
| Silicon Motion ATIV Real HD Camera                                         | 1         | 0.74%   |
| Ricoh Integrated Webcam                                                    | 1         | 0.74%   |
| Ricoh HD Webcam                                                            | 1         | 0.74%   |
| Realtek Integrated Webcam_HD                                               | 1         | 0.74%   |
| Realtek HP Truevision HD                                                   | 1         | 0.74%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 0.74%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 0.74%   |
| Quanta HD WebCam                                                           | 1         | 0.74%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 0.74%   |
| Pixart Imaging USB_2.0_Webcam                                              | 1         | 0.74%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 0.74%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 0.74%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 0.74%   |
| Logitech HP Webcam                                                         | 1         | 0.74%   |
| Lenovo Integrated Webcam                                                   | 1         | 0.74%   |
| DigiTech WebCam SCB-0380M                                                  | 1         | 0.74%   |
| Chicony VGA Webcam                                                         | 1         | 0.74%   |
| Chicony USB2.0 Camera                                                      | 1         | 0.74%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 0.74%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 0.74%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 32        | 66.67%  |
| Synaptics                  | 7         | 14.58%  |
| AuthenTec                  | 4         | 8.33%   |
| Shenzhen Goodix Technology | 3         | 6.25%   |
| Upek                       | 2         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 16        | 33.33%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 7         | 14.58%  |
| Validity Sensors VFS491                                   | 5         | 10.42%  |
| Validity Sensors VFS451 Fingerprint Reader                | 4         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                       | 3         | 6.25%   |
| AuthenTec AES2810                                         | 3         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 2.08%   |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 2.08%   |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 2.08%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 2.08%   |
| Validity Sensors Fingerprint scanner                      | 1         | 2.08%   |
| AuthenTec Fingerprint Sensor                              | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 17        | 94.44%  |
| O2 Micro | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 38.89%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Broadcom 5880                                                                | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 77        | 50.33%  |
| 1     | 67        | 43.79%  |
| 2     | 8         | 5.23%   |
| 4     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 54.65%  |
| Chipcard                 | 18        | 20.93%  |
| Storage                  | 4         | 4.65%   |
| Net/wireless             | 4         | 4.65%   |
| Graphics card            | 4         | 4.65%   |
| Bluetooth                | 3         | 3.49%   |
| Sound                    | 1         | 1.16%   |
| Network                  | 1         | 1.16%   |
| Net/ethernet             | 1         | 1.16%   |
| Multimedia controller    | 1         | 1.16%   |
| Communication controller | 1         | 1.16%   |
| Camera                   | 1         | 1.16%   |


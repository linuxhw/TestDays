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

Total: 229

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | IdeaPad 330-15IKB 81DE      | [072d897eda](https://linux-hardware.org/?probe=072d897eda) | Jul 28, 2022 |
| Dell     | Latitude E6420              | [07a671ae31](https://linux-hardware.org/?probe=07a671ae31) | Jul 22, 2022 |
| Dell     | Latitude E5440              | [3b30865387](https://linux-hardware.org/?probe=3b30865387) | Jul 20, 2022 |
| Dell     | Latitude E6420              | [fadad1be46](https://linux-hardware.org/?probe=fadad1be46) | Jul 14, 2022 |
| Sony     | VPCEA26FG                   | [c5432e157a](https://linux-hardware.org/?probe=c5432e157a) | Jul 11, 2022 |
| Dell     | Latitude E7450              | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| Sony     | VPCEA26FG                   | [2075c04c4c](https://linux-hardware.org/?probe=2075c04c4c) | Jul 03, 2022 |
| Sony     | VPCEA26FG                   | [b72a4de42b](https://linux-hardware.org/?probe=b72a4de42b) | Jul 01, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | [18fbe5a2d0](https://linux-hardware.org/?probe=18fbe5a2d0) | Jun 28, 2022 |
| HP       | EliteBook 8470p             | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| HP       | EliteBook 8470p             | [f9895656b6](https://linux-hardware.org/?probe=f9895656b6) | Jun 23, 2022 |
| HP       | EliteBook 8470p             | [2e2bcb63d7](https://linux-hardware.org/?probe=2e2bcb63d7) | Jun 23, 2022 |
| HP       | EliteBook 850 G5            | [085f5c458d](https://linux-hardware.org/?probe=085f5c458d) | Jun 10, 2022 |
| HP       | Laptop 15s-fq2xxx           | [5bcb742cbe](https://linux-hardware.org/?probe=5bcb742cbe) | Jun 04, 2022 |
| Lenovo   | ThinkPad T450 20BV0005US    | [a795ed872f](https://linux-hardware.org/?probe=a795ed872f) | Jun 03, 2022 |
| HP       | EliteBook 8460p             | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP       | EliteBook 8460p             | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell     | Inspiron 3543               | [c48c32ae19](https://linux-hardware.org/?probe=c48c32ae19) | May 25, 2022 |
| HP       | Notebook                    | [4508e41795](https://linux-hardware.org/?probe=4508e41795) | May 22, 2022 |
| HP       | Notebook                    | [dc587c572e](https://linux-hardware.org/?probe=dc587c572e) | May 22, 2022 |
| Dell     | Latitude 3330               | [4f05d8475c](https://linux-hardware.org/?probe=4f05d8475c) | May 08, 2022 |
| Dell     | Latitude E6420              | [8c12f58910](https://linux-hardware.org/?probe=8c12f58910) | May 01, 2022 |
| HP       | EliteBook 840 G1            | [411c79850c](https://linux-hardware.org/?probe=411c79850c) | Apr 29, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TDS... | [59a49b2d04](https://linux-hardware.org/?probe=59a49b2d04) | Apr 23, 2022 |
| HP       | EliteBook 840 G2            | [3e0d410668](https://linux-hardware.org/?probe=3e0d410668) | Apr 19, 2022 |
| HP       | ProBook 450 G8 Notebook ... | [1974bfe63a](https://linux-hardware.org/?probe=1974bfe63a) | Apr 15, 2022 |
| Dell     | Latitude 3520               | [ee204b07aa](https://linux-hardware.org/?probe=ee204b07aa) | Apr 11, 2022 |
| HP       | Pavilion TS 11              | [9a817f6695](https://linux-hardware.org/?probe=9a817f6695) | Apr 09, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Dell     | Latitude 7480               | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | [1936ee53b3](https://linux-hardware.org/?probe=1936ee53b3) | Mar 22, 2022 |
| Dell     | Latitude 7480               | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Lenovo   | V110-15IKB 80TH             | [a3aeef468a](https://linux-hardware.org/?probe=a3aeef468a) | Mar 12, 2022 |
| Lenovo   | ThinkBook 15 G2 ITL 20VE    | [e0169c3e87](https://linux-hardware.org/?probe=e0169c3e87) | Feb 23, 2022 |
| HP       | EliteBook Folio 9470m       | [1aa838368f](https://linux-hardware.org/?probe=1aa838368f) | Feb 20, 2022 |
| HP       | EliteBook Folio 9470m       | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| Dell     | Inspiron 3501               | [7fdd5b66fc](https://linux-hardware.org/?probe=7fdd5b66fc) | Feb 14, 2022 |
| Lenovo   | IdeaPad 510-15ISK 80SR      | [a5407aa128](https://linux-hardware.org/?probe=a5407aa128) | Feb 13, 2022 |
| Dell     | Inspiron 5547               | [2d6ff07a82](https://linux-hardware.org/?probe=2d6ff07a82) | Feb 12, 2022 |
| Dell     | Inspiron 3501               | [0dd77f2f7a](https://linux-hardware.org/?probe=0dd77f2f7a) | Feb 12, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TDS... | [5a9a256568](https://linux-hardware.org/?probe=5a9a256568) | Feb 01, 2022 |
| Dell     | Inspiron 3501               | [4a0c4a62b7](https://linux-hardware.org/?probe=4a0c4a62b7) | Feb 01, 2022 |
| Dell     | Inspiron 3501               | [c902cc42a6](https://linux-hardware.org/?probe=c902cc42a6) | Jan 18, 2022 |
| Dell     | Inspiron 3501               | [ce839c3628](https://linux-hardware.org/?probe=ce839c3628) | Jan 08, 2022 |
| Lenovo   | ThinkPad T540p 20BFS5630... | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| HP       | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| HP       | EliteBook Folio 9470m       | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP       | EliteBook Folio 9470m       | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP       | EliteBook Folio 9470m       | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| Acer     | Aspire ES1-411              | [9a5ebb6379](https://linux-hardware.org/?probe=9a5ebb6379) | Dec 19, 2021 |
| HP       | EliteBook 8470p             | [0f7389c7d9](https://linux-hardware.org/?probe=0f7389c7d9) | Dec 14, 2021 |
| Dell     | Inspiron 5515               | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell     | Inspiron 5515               | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| HP       | ZBook 15 G3                 | [e662c8b956](https://linux-hardware.org/?probe=e662c8b956) | Dec 07, 2021 |
| Dell     | Inspiron 15 7000 Gaming     | [538c96bb62](https://linux-hardware.org/?probe=538c96bb62) | Nov 26, 2021 |
| Dell     | Latitude E6440              | [e0e5edfc03](https://linux-hardware.org/?probe=e0e5edfc03) | Nov 24, 2021 |
| HP       | Unknown                     | [ef28d45f68](https://linux-hardware.org/?probe=ef28d45f68) | Nov 23, 2021 |
| Dell     | G3 3579                     | [38e9f54ba1](https://linux-hardware.org/?probe=38e9f54ba1) | Nov 23, 2021 |
| Dell     | Inspiron 5520               | [6c6e631ffc](https://linux-hardware.org/?probe=6c6e631ffc) | Nov 20, 2021 |
| HP       | Unknown                     | [23dc38032d](https://linux-hardware.org/?probe=23dc38032d) | Nov 20, 2021 |
| Dell     | Inspiron 15 7000 Gaming     | [cd386145b8](https://linux-hardware.org/?probe=cd386145b8) | Nov 18, 2021 |
| HP       | Pavilion Laptop 14-ce2xx... | [f9ebb771b0](https://linux-hardware.org/?probe=f9ebb771b0) | Nov 14, 2021 |
| HP       | ZBook 15 G3                 | [67e5184b17](https://linux-hardware.org/?probe=67e5184b17) | Nov 13, 2021 |
| Dell     | Vostro 1500                 | [23aeb68ca2](https://linux-hardware.org/?probe=23aeb68ca2) | Nov 11, 2021 |
| HP       | ZBook 15 G3                 | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Dell     | Inspiron 3501               | [5d35bd9e4a](https://linux-hardware.org/?probe=5d35bd9e4a) | Nov 07, 2021 |
| Dell     | Inspiron 15-3567            | [630a9144f1](https://linux-hardware.org/?probe=630a9144f1) | Nov 06, 2021 |
| HP       | 650                         | [c32592cabb](https://linux-hardware.org/?probe=c32592cabb) | Oct 20, 2021 |
| Apple    | MacBookPro14,1              | [bb1aa448fd](https://linux-hardware.org/?probe=bb1aa448fd) | Oct 20, 2021 |
| HP       | ProBook 450 G7              | [a47cdaa2ba](https://linux-hardware.org/?probe=a47cdaa2ba) | Oct 20, 2021 |
| Lenovo   | ThinkBook 15-IIL 20SM       | [c7fc550482](https://linux-hardware.org/?probe=c7fc550482) | Oct 16, 2021 |
| HP       | ProBook 450 G7              | [f2a84de135](https://linux-hardware.org/?probe=f2a84de135) | Oct 12, 2021 |
| Dell     | Latitude E5570              | [938d1a781d](https://linux-hardware.org/?probe=938d1a781d) | Oct 08, 2021 |
| Lenovo   | ThinkPad X220 Tablet 429... | [33137c7c23](https://linux-hardware.org/?probe=33137c7c23) | Oct 07, 2021 |
| Lenovo   | ThinkBook 15 G2 ITL 20VE    | [196fa579f8](https://linux-hardware.org/?probe=196fa579f8) | Oct 04, 2021 |
| Haier    | Y11C                        | [74b9ee5509](https://linux-hardware.org/?probe=74b9ee5509) | Oct 03, 2021 |
| Dell     | Precision M6400             | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| Haier    | Y11C                        | [591740bf00](https://linux-hardware.org/?probe=591740bf00) | Sep 27, 2021 |
| Dell     | Inspiron 5515               | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| Lenovo   | ThinkPad X220 Tablet 429... | [d0e2e19e84](https://linux-hardware.org/?probe=d0e2e19e84) | Sep 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X571... | [966a09526a](https://linux-hardware.org/?probe=966a09526a) | Aug 14, 2021 |
| Dell     | Inspiron 3542               | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Dell     | Inspiron 5570               | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| Dell     | Inspiron 5593               | [1f6017347e](https://linux-hardware.org/?probe=1f6017347e) | Aug 05, 2021 |
| Dell     | Latitude E5250              | [f50f84a6a3](https://linux-hardware.org/?probe=f50f84a6a3) | Jul 26, 2021 |
| Dell     | Latitude E5250              | [9806ab15ab](https://linux-hardware.org/?probe=9806ab15ab) | Jul 25, 2021 |
| Dell     | Latitude E5250              | [9a475d76a4](https://linux-hardware.org/?probe=9a475d76a4) | Jul 25, 2021 |
| Dell     | Latitude E5250              | [d65621a003](https://linux-hardware.org/?probe=d65621a003) | Jul 16, 2021 |
| HP       | EliteBook 8440p             | [d89b69a6a3](https://linux-hardware.org/?probe=d89b69a6a3) | Jul 16, 2021 |
| Dell     | Inspiron 15 7000 Gaming     | [d320594f42](https://linux-hardware.org/?probe=d320594f42) | Jul 07, 2021 |
| Lenovo   | ThinkPad E14 20RA007SAD     | [eb51ce8f36](https://linux-hardware.org/?probe=eb51ce8f36) | Jul 07, 2021 |
| Dell     | Precision 5530              | [7d267375f2](https://linux-hardware.org/?probe=7d267375f2) | Jul 05, 2021 |
| Dell     | Inspiron 5593               | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| HP       | Pavilion Notebook           | [f5ac8e2aca](https://linux-hardware.org/?probe=f5ac8e2aca) | Jun 25, 2021 |
| HP       | Pavilion dv6                | [c3529dc2aa](https://linux-hardware.org/?probe=c3529dc2aa) | Jun 24, 2021 |
| Dell     | Precision M6400             | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| Dell     | Latitude 3510               | [79c73e5595](https://linux-hardware.org/?probe=79c73e5595) | Jun 09, 2021 |
| Toshiba  | Satellite L850              | [6beced18da](https://linux-hardware.org/?probe=6beced18da) | May 23, 2021 |
| Dell     | Vostro 14-3468              | [1742ee5823](https://linux-hardware.org/?probe=1742ee5823) | May 21, 2021 |
| Dell     | Latitude E5250              | [8c3b8c27c8](https://linux-hardware.org/?probe=8c3b8c27c8) | May 10, 2021 |
| Dell     | Latitude E6420              | [6e3288ca3a](https://linux-hardware.org/?probe=6e3288ca3a) | Apr 11, 2021 |
| Dell     | Inspiron 17-7779            | [2cf1f86b67](https://linux-hardware.org/?probe=2cf1f86b67) | Apr 06, 2021 |
| Gigabyte | AERO 15-SA                  | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Gigabyte | AERO 15-SA                  | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Dell     | Latitude 3510               | [1ef27c1786](https://linux-hardware.org/?probe=1ef27c1786) | Mar 25, 2021 |
| HP       | EliteBook 2170p             | [eba311c4d7](https://linux-hardware.org/?probe=eba311c4d7) | Mar 22, 2021 |
| HP       | EliteBook 2170p             | [e506fc315e](https://linux-hardware.org/?probe=e506fc315e) | Mar 21, 2021 |
| Lenovo   | IdeaPad L340-15IWL 81LG     | [eb713030d2](https://linux-hardware.org/?probe=eb713030d2) | Mar 18, 2021 |
| Dell     | Latitude E6420              | [a062baeb24](https://linux-hardware.org/?probe=a062baeb24) | Mar 12, 2021 |
| HP       | EliteBook 850 G7 Noteboo... | [6dbe550700](https://linux-hardware.org/?probe=6dbe550700) | Feb 28, 2021 |
| HP       | EliteBook 840 G3            | [b8a8ea9182](https://linux-hardware.org/?probe=b8a8ea9182) | Feb 24, 2021 |
| HP       | EliteBook 840 G3            | [ce415da689](https://linux-hardware.org/?probe=ce415da689) | Feb 23, 2021 |
| ASUSTek  | TUF Gaming FA706IU_FA706... | [64c73f58bb](https://linux-hardware.org/?probe=64c73f58bb) | Feb 22, 2021 |
| Lenovo   | ThinkBook 15-IIL 20SM       | [0426a1c07e](https://linux-hardware.org/?probe=0426a1c07e) | Feb 20, 2021 |
| HP       | 14                          | [d5382b721f](https://linux-hardware.org/?probe=d5382b721f) | Feb 11, 2021 |
| Toshiba  | Satellite S50t-B            | [2fe86bc977](https://linux-hardware.org/?probe=2fe86bc977) | Feb 06, 2021 |
| Toshiba  | Satellite S50t-B            | [ec72426035](https://linux-hardware.org/?probe=ec72426035) | Feb 05, 2021 |
| Toshiba  | Satellite S50t-B            | [f7709c05cb](https://linux-hardware.org/?probe=f7709c05cb) | Feb 05, 2021 |
| HP       | 14                          | [f27a999e26](https://linux-hardware.org/?probe=f27a999e26) | Feb 03, 2021 |
| Sony     | SVE15126CXS                 | [8a27b129a3](https://linux-hardware.org/?probe=8a27b129a3) | Feb 02, 2021 |
| Apple    | MacBookPro16,2              | [e3790fd911](https://linux-hardware.org/?probe=e3790fd911) | Jan 31, 2021 |
| Apple    | MacBookPro16,2              | [0ee13de953](https://linux-hardware.org/?probe=0ee13de953) | Jan 31, 2021 |
| Lenovo   | ThinkPad E15 20RD0088UE     | [d2bfe04a2b](https://linux-hardware.org/?probe=d2bfe04a2b) | Jan 28, 2021 |
| HP       | ProBook 450 G5              | [e4b829fff8](https://linux-hardware.org/?probe=e4b829fff8) | Jan 26, 2021 |
| HP       | ProBook 450 G2              | [7db1cae3c0](https://linux-hardware.org/?probe=7db1cae3c0) | Jan 25, 2021 |
| HP       | ProBook 450 G5              | [0421fbf0d1](https://linux-hardware.org/?probe=0421fbf0d1) | Jan 25, 2021 |
| Lenovo   | ThinkPad T460 20FMS39800    | [7b4f78f648](https://linux-hardware.org/?probe=7b4f78f648) | Jan 10, 2021 |
| Dell     | Latitude E6510              | [2557f813e4](https://linux-hardware.org/?probe=2557f813e4) | Dec 15, 2020 |
| Dell     | Inspiron 15 7000 Gaming     | [b04b3b207e](https://linux-hardware.org/?probe=b04b3b207e) | Dec 11, 2020 |
| Fujitsu  | LIFEBOOK E752               | [252afde67a](https://linux-hardware.org/?probe=252afde67a) | Dec 08, 2020 |
| Lenovo   | ThinkBook 15-IML 20RW       | [f84c7affac](https://linux-hardware.org/?probe=f84c7affac) | Dec 07, 2020 |
| Dell     | Latitude E7440              | [0d04075b3e](https://linux-hardware.org/?probe=0d04075b3e) | Dec 03, 2020 |
| Lenovo   | ThinkPad W500 40612HU       | [06465bf227](https://linux-hardware.org/?probe=06465bf227) | Dec 01, 2020 |
| Lenovo   | ThinkPad T60 1951WAT        | [4da418a597](https://linux-hardware.org/?probe=4da418a597) | Nov 28, 2020 |
| Dell     | Latitude E7450              | [20ee05f0fa](https://linux-hardware.org/?probe=20ee05f0fa) | Nov 27, 2020 |
| Dell     | Latitude E7440              | [9627b61c6f](https://linux-hardware.org/?probe=9627b61c6f) | Nov 25, 2020 |
| Dell     | Latitude E7450              | [e9a83f5dc5](https://linux-hardware.org/?probe=e9a83f5dc5) | Nov 24, 2020 |
| HP       | EliteBook 2540p             | [00a011fa83](https://linux-hardware.org/?probe=00a011fa83) | Nov 22, 2020 |
| HP       | EliteBook 2540p             | [12f4630385](https://linux-hardware.org/?probe=12f4630385) | Nov 22, 2020 |
| Lenovo   | ThinkPad E560 20EV0010UK    | [a52f064714](https://linux-hardware.org/?probe=a52f064714) | Nov 19, 2020 |
| Dell     | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| HP       | 650                         | [67e06d1514](https://linux-hardware.org/?probe=67e06d1514) | Nov 09, 2020 |
| HP       | Pavilion g6                 | [98124ff6a4](https://linux-hardware.org/?probe=98124ff6a4) | Nov 08, 2020 |
| HP       | EliteBook 8470p             | [847807840d](https://linux-hardware.org/?probe=847807840d) | Nov 05, 2020 |
| HP       | ProBook 6560b               | [934ffc99e6](https://linux-hardware.org/?probe=934ffc99e6) | Oct 30, 2020 |
| Dell     | Inspiron 15-3567            | [2b138e461a](https://linux-hardware.org/?probe=2b138e461a) | Oct 26, 2020 |
| Dell     | Inspiron 15-3567            | [4460c27fd7](https://linux-hardware.org/?probe=4460c27fd7) | Oct 26, 2020 |
| Dell     | Inspiron 15-3567            | [b647bae107](https://linux-hardware.org/?probe=b647bae107) | Oct 24, 2020 |
| Apple    | MacBookAir6,2               | [3509d2f6e3](https://linux-hardware.org/?probe=3509d2f6e3) | Oct 22, 2020 |
| Toshiba  | PORTEGE Z30-B               | [d7c9922a29](https://linux-hardware.org/?probe=d7c9922a29) | Oct 21, 2020 |
| HP       | ProBook 4340s               | [3db4ff09f4](https://linux-hardware.org/?probe=3db4ff09f4) | Oct 18, 2020 |
| Dell     | Latitude E6540              | [36688dde6e](https://linux-hardware.org/?probe=36688dde6e) | Oct 06, 2020 |
| HP       | 650                         | [1ea9bf783e](https://linux-hardware.org/?probe=1ea9bf783e) | Oct 03, 2020 |
| HP       | ProBook 450 G5              | [94eb24ff74](https://linux-hardware.org/?probe=94eb24ff74) | Oct 02, 2020 |
| Dell     | Latitude E4300              | [12b944fb30](https://linux-hardware.org/?probe=12b944fb30) | Oct 02, 2020 |
| HP       | ProBook 450 G5              | [cb2cef5fcf](https://linux-hardware.org/?probe=cb2cef5fcf) | Oct 01, 2020 |
| Lenovo   | ThinkPad T440p 20AWS0DU0... | [caf12cb57f](https://linux-hardware.org/?probe=caf12cb57f) | Sep 30, 2020 |
| Lenovo   | ThinkPad T440p 20AWS0DU0... | [d3cc62a7f5](https://linux-hardware.org/?probe=d3cc62a7f5) | Sep 30, 2020 |
| Dell     | Latitude E7450              | [7df34be11f](https://linux-hardware.org/?probe=7df34be11f) | Sep 29, 2020 |
| Dell     | Latitude E7450              | [8149a50311](https://linux-hardware.org/?probe=8149a50311) | Sep 29, 2020 |
| Samsung  | QX311/QX411/QX412/QX511     | [b6f7494e44](https://linux-hardware.org/?probe=b6f7494e44) | Sep 21, 2020 |
| HP       | 650                         | [278a9afdeb](https://linux-hardware.org/?probe=278a9afdeb) | Sep 21, 2020 |
| Dell     | Vostro 14-3468              | [4ab76fd5c2](https://linux-hardware.org/?probe=4ab76fd5c2) | Sep 20, 2020 |
| HP       | 650                         | [8aaa8d7e4d](https://linux-hardware.org/?probe=8aaa8d7e4d) | Sep 19, 2020 |
| Samsung  | QX311/QX411/QX412/QX511     | [1ec83fe97e](https://linux-hardware.org/?probe=1ec83fe97e) | Sep 17, 2020 |
| HP       | EliteBook 840 G3            | [d6204bd9e2](https://linux-hardware.org/?probe=d6204bd9e2) | Sep 16, 2020 |
| HP       | ProBook 455 G7              | [d84e4c8838](https://linux-hardware.org/?probe=d84e4c8838) | Sep 13, 2020 |
| HP       | ENVY 17                     | [08285409ad](https://linux-hardware.org/?probe=08285409ad) | Sep 13, 2020 |
| HP       | ProBook 455 G7              | [290aad9d0d](https://linux-hardware.org/?probe=290aad9d0d) | Sep 12, 2020 |
| HP       | ProBook 450 G7              | [85d0104e28](https://linux-hardware.org/?probe=85d0104e28) | Sep 10, 2020 |
| Dell     | Inspiron 15-3573            | [9be442a7dd](https://linux-hardware.org/?probe=9be442a7dd) | Sep 07, 2020 |
| HP       | ProBook 440 G7              | [1c4d1f875b](https://linux-hardware.org/?probe=1c4d1f875b) | Sep 01, 2020 |
| HP       | ProBook 4340s               | [f7580ed51b](https://linux-hardware.org/?probe=f7580ed51b) | Aug 31, 2020 |
| Dell     | Latitude E7250              | [ff13c002c8](https://linux-hardware.org/?probe=ff13c002c8) | Aug 27, 2020 |
| HP       | EliteBook 820 G2            | [f35b20067d](https://linux-hardware.org/?probe=f35b20067d) | Aug 25, 2020 |
| HP       | Laptop 15-da2xxx            | [031606a1a9](https://linux-hardware.org/?probe=031606a1a9) | Aug 21, 2020 |
| Dell     | Latitude E7250              | [63024e0df6](https://linux-hardware.org/?probe=63024e0df6) | Aug 19, 2020 |
| HP       | ProBook 450 G7              | [8a5fc0bc23](https://linux-hardware.org/?probe=8a5fc0bc23) | Aug 13, 2020 |
| HP       | ProBook 440 G5              | [fa604583d6](https://linux-hardware.org/?probe=fa604583d6) | Aug 10, 2020 |
| HP       | ProBook 440 G5              | [255da50641](https://linux-hardware.org/?probe=255da50641) | Aug 10, 2020 |
| Lenovo   | ThinkPad X201 3249CTO       | [930fbc43ed](https://linux-hardware.org/?probe=930fbc43ed) | Aug 09, 2020 |
| HP       | Pavilion Notebook           | [f62759a869](https://linux-hardware.org/?probe=f62759a869) | Aug 05, 2020 |
| Dell     | Inspiron 15-3567            | [4af4cdfef7](https://linux-hardware.org/?probe=4af4cdfef7) | Jul 30, 2020 |
| HP       | ProBook 440 G7              | [4b38ecdae9](https://linux-hardware.org/?probe=4b38ecdae9) | Jul 28, 2020 |
| HP       | EliteBook 840 G2            | [9dbea8590b](https://linux-hardware.org/?probe=9dbea8590b) | Jul 19, 2020 |
| HP       | ProBook 450 G7              | [45478d9106](https://linux-hardware.org/?probe=45478d9106) | Jul 18, 2020 |
| HP       | ProBook 470 G2              | [c42c686ae8](https://linux-hardware.org/?probe=c42c686ae8) | Jul 09, 2020 |
| MOTION   | NVX00                       | [fd07831802](https://linux-hardware.org/?probe=fd07831802) | Jul 04, 2020 |
| HP       | ProBook 450 G3              | [a12518d58c](https://linux-hardware.org/?probe=a12518d58c) | Jun 30, 2020 |
| Dell     | Latitude E6440              | [a7fe187945](https://linux-hardware.org/?probe=a7fe187945) | Jun 28, 2020 |
| Haier    | Y11C                        | [6b98c2c449](https://linux-hardware.org/?probe=6b98c2c449) | Jun 23, 2020 |
| Lenovo   | ThinkPad X201 3249CTO       | [8c8ed3d489](https://linux-hardware.org/?probe=8c8ed3d489) | Jun 06, 2020 |
| Haier    | Y11C                        | [7f9f93809f](https://linux-hardware.org/?probe=7f9f93809f) | Jun 01, 2020 |
| Dell     | Latitude E6410              | [60757c8504](https://linux-hardware.org/?probe=60757c8504) | May 21, 2020 |
| Lenovo   | ThinkPad X201 3249CTO       | [86a1d31e5c](https://linux-hardware.org/?probe=86a1d31e5c) | May 21, 2020 |
| Dell     | Latitude E7450              | [1031b89b4b](https://linux-hardware.org/?probe=1031b89b4b) | May 12, 2020 |
| HP       | EliteBook Folio 1040 G1     | [34b0697bf6](https://linux-hardware.org/?probe=34b0697bf6) | May 10, 2020 |
| Dell     | Latitude E6320              | [cedc2c5001](https://linux-hardware.org/?probe=cedc2c5001) | May 10, 2020 |
| Acer     | Aspire E5-576               | [581af37cda](https://linux-hardware.org/?probe=581af37cda) | Apr 19, 2020 |
| Dell     | Latitude E5420              | [6d2ddeb934](https://linux-hardware.org/?probe=6d2ddeb934) | Apr 18, 2020 |
| HP       | EliteBook 6930p             | [ea52c08646](https://linux-hardware.org/?probe=ea52c08646) | Apr 09, 2020 |
| Dell     | Latitude E4300              | [5e38d54ea2](https://linux-hardware.org/?probe=5e38d54ea2) | Mar 18, 2020 |
| HP       | EliteBook 8440p             | [cd13c97ddb](https://linux-hardware.org/?probe=cd13c97ddb) | Mar 11, 2020 |
| Lenovo   | ThinkBook 15-IML 20RW       | [3cd2a73254](https://linux-hardware.org/?probe=3cd2a73254) | Mar 09, 2020 |
| HP       | Pavilion dv7                | [c727a0fa74](https://linux-hardware.org/?probe=c727a0fa74) | Jan 27, 2020 |
| HP       | EliteBook 8470p             | [e257c71d0b](https://linux-hardware.org/?probe=e257c71d0b) | Jan 14, 2020 |
| HP       | ProBook 450 G3              | [f73167982a](https://linux-hardware.org/?probe=f73167982a) | Jan 01, 2020 |
| Dell     | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| Dell     | Latitude XT3                | [4ccaa2e0e2](https://linux-hardware.org/?probe=4ccaa2e0e2) | Oct 29, 2019 |
| Lenovo   | ThinkPad T440 20B7S1NK05    | [310405c604](https://linux-hardware.org/?probe=310405c604) | Oct 29, 2019 |
| HP       | EliteBook 6930p             | [856fcded98](https://linux-hardware.org/?probe=856fcded98) | Oct 25, 2019 |
| HP       | Unknown                     | [25dd8af3ee](https://linux-hardware.org/?probe=25dd8af3ee) | Oct 22, 2019 |
| HP       | EliteBook 6930p             | [43c8f2b72c](https://linux-hardware.org/?probe=43c8f2b72c) | Sep 13, 2019 |
| HP       | EliteBook 6930p             | [964e933faf](https://linux-hardware.org/?probe=964e933faf) | Sep 13, 2019 |
| Samsung  | 940Z5L                      | [28c94787df](https://linux-hardware.org/?probe=28c94787df) | Sep 13, 2019 |
| AMI      | Unknown                     | [407590d103](https://linux-hardware.org/?probe=407590d103) | Sep 09, 2019 |
| HP       | ProBook 6470b               | [81e17acdb1](https://linux-hardware.org/?probe=81e17acdb1) | Aug 02, 2019 |
| HP       | EliteBook 840 G3            | [b419735d70](https://linux-hardware.org/?probe=b419735d70) | Jul 04, 2019 |
| Sony     | VPCCB490X                   | [ed39416136](https://linux-hardware.org/?probe=ed39416136) | Jun 22, 2019 |
| Haier    | Y11C                        | [ab6b2cf0e5](https://linux-hardware.org/?probe=ab6b2cf0e5) | Jun 20, 2019 |
| Haier    | Y11C                        | [74a3547ed6](https://linux-hardware.org/?probe=74a3547ed6) | Jun 20, 2019 |
| Dell     | Latitude E6420              | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell     | Latitude E6420              | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Haier    | Y11B                        | [d90f70d18f](https://linux-hardware.org/?probe=d90f70d18f) | May 11, 2019 |
| Haier    | Y11B                        | [e359a25a69](https://linux-hardware.org/?probe=e359a25a69) | Nov 18, 2018 |
| Haier    | Y11B                        | [13e5308d20](https://linux-hardware.org/?probe=13e5308d20) | Nov 18, 2018 |
| HP       | Pavilion Notebook           | [7e2949f7da](https://linux-hardware.org/?probe=7e2949f7da) | Nov 11, 2018 |
| Acer     | Aspire 5733                 | [970a40e3d0](https://linux-hardware.org/?probe=970a40e3d0) | Oct 23, 2018 |
| ASUSTek  | K53U                        | [f644624e98](https://linux-hardware.org/?probe=f644624e98) | Oct 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 65        | 38.24%  |
| Ubuntu 18.04        | 21        | 12.35%  |
| Ubuntu 22.04        | 4         | 2.35%   |
| KDE neon 20.04      | 4         | 2.35%   |
| Arch                | 4         | 2.35%   |
| Ubuntu 21.10        | 3         | 1.76%   |
| Ubuntu 21.04        | 3         | 1.76%   |
| Ubuntu 19.04        | 3         | 1.76%   |
| Pop!_OS 21.04       | 3         | 1.76%   |
| Pop!_OS 20.10       | 3         | 1.76%   |
| Pop!_OS 20.04       | 3         | 1.76%   |
| Linux Mint 20       | 3         | 1.76%   |
| Fedora 33           | 3         | 1.76%   |
| Zorin 16            | 2         | 1.18%   |
| Zorin 15            | 2         | 1.18%   |
| Ubuntu 16.04        | 2         | 1.18%   |
| OpenMandriva 4.2    | 2         | 1.18%   |
| Linux Mint 20.3     | 2         | 1.18%   |
| Linux Mint 20.2     | 2         | 1.18%   |
| Linux Mint 20.1     | 2         | 1.18%   |
| Elementary 6.1      | 2         | 1.18%   |
| Debian 11           | 2         | 1.18%   |
| Zorin 12            | 1         | 0.59%   |
| Xero Rolling        | 1         | 0.59%   |
| Ubuntu 19.10        | 1         | 0.59%   |
| Ubuntu 18.10        | 1         | 0.59%   |
| ROSA R10            | 1         | 0.59%   |
| RHEL 8              | 1         | 0.59%   |
| Pop!_OS 22.04       | 1         | 0.59%   |
| Parrot 4.10         | 1         | 0.59%   |
| Oracle Linux 8.4    | 1         | 0.59%   |
| OpenMandriva 4.3    | 1         | 0.59%   |
| Manjaro 21.2.6      | 1         | 0.59%   |
| Manjaro 21.1.2      | 1         | 0.59%   |
| Manjaro             | 1         | 0.59%   |
| LinuxFX 11          | 1         | 0.59%   |
| Kubuntu 21.04       | 1         | 0.59%   |
| Kubuntu 20.10       | 1         | 0.59%   |
| Kali 2022.2         | 1         | 0.59%   |
| Kali 2020.3         | 1         | 0.59%   |
| Fedora 35           | 1         | 0.59%   |
| Fedora 34           | 1         | 0.59%   |
| Fedora 31           | 1         | 0.59%   |
| Fedora 30           | 1         | 0.59%   |
| Endless 4.0.7       | 1         | 0.59%   |
| Endless 3.8.0       | 1         | 0.59%   |
| Endless 3.7.8       | 1         | 0.59%   |
| EndeavourOS Rolling | 1         | 0.59%   |
| Deepin 15.10        | 1         | 0.59%   |
| Clear Linux 34640   | 1         | 0.59%   |
| ArcoLinux 20.1.4    | 1         | 0.59%   |
| AlmaLinux 8.6       | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 103       | 61.68%  |
| Pop!_OS      | 9         | 5.39%   |
| Linux Mint   | 8         | 4.79%   |
| Fedora       | 6         | 3.59%   |
| Zorin        | 5         | 2.99%   |
| KDE neon     | 4         | 2.4%    |
| Arch         | 4         | 2.4%    |
| OpenMandriva | 3         | 1.8%    |
| Manjaro      | 3         | 1.8%    |
| Endless      | 3         | 1.8%    |
| Kubuntu      | 2         | 1.2%    |
| Kali         | 2         | 1.2%    |
| Elementary   | 2         | 1.2%    |
| Debian       | 2         | 1.2%    |
| Xero         | 1         | 0.6%    |
| ROSA         | 1         | 0.6%    |
| RHEL         | 1         | 0.6%    |
| Parrot       | 1         | 0.6%    |
| Oracle Linux | 1         | 0.6%    |
| LinuxFX      | 1         | 0.6%    |
| EndeavourOS  | 1         | 0.6%    |
| Deepin       | 1         | 0.6%    |
| Clear Linux  | 1         | 0.6%    |
| ArcoLinux    | 1         | 0.6%    |
| AlmaLinux    | 1         | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 5.4.0-42-generic                  | 9         | 4.97%   |
| 5.11.0-37-generic                 | 5         | 2.76%   |
| 5.4.0-48-generic                  | 4         | 2.21%   |
| 5.4.0-47-generic                  | 4         | 2.21%   |
| 5.4.0-40-generic                  | 4         | 2.21%   |
| 5.8.0-7630-generic                | 3         | 1.66%   |
| 5.8.0-41-generic                  | 3         | 1.66%   |
| 5.4.0-54-generic                  | 3         | 1.66%   |
| 5.4.0-52-generic                  | 3         | 1.66%   |
| 5.4.0-26-generic                  | 3         | 1.66%   |
| 5.3.0-28-generic                  | 3         | 1.66%   |
| 5.13.0-39-generic                 | 3         | 1.66%   |
| 5.13.0-30-generic                 | 3         | 1.66%   |
| 5.9.8-200.fc33.x86_64             | 2         | 1.1%    |
| 5.8.0-59-generic                  | 2         | 1.1%    |
| 5.8.0-48-generic                  | 2         | 1.1%    |
| 5.4.0-91-generic                  | 2         | 1.1%    |
| 5.4.0-58-generic                  | 2         | 1.1%    |
| 5.4.0-45-generic                  | 2         | 1.1%    |
| 5.4.0-39-generic                  | 2         | 1.1%    |
| 5.4.0-33-generic                  | 2         | 1.1%    |
| 5.4.0-29-generic                  | 2         | 1.1%    |
| 5.15.0-41-generic                 | 2         | 1.1%    |
| 5.15.0-25-generic                 | 2         | 1.1%    |
| 5.13.0-44-generic                 | 2         | 1.1%    |
| 5.13.0-28-generic                 | 2         | 1.1%    |
| 5.11.0-7620-generic               | 2         | 1.1%    |
| 5.11.0-43-generic                 | 2         | 1.1%    |
| 5.11.0-41-generic                 | 2         | 1.1%    |
| 5.11.0-40-generic                 | 2         | 1.1%    |
| 5.11.0-38-generic                 | 2         | 1.1%    |
| 5.11.0-27-generic                 | 2         | 1.1%    |
| 5.10.14-desktop-1omv4002          | 2         | 1.1%    |
| 5.0.0-23-generic                  | 2         | 1.1%    |
| 4.15.0-66-generic                 | 2         | 1.1%    |
| 5.9.10-200.fc33.x86_64            | 1         | 0.55%   |
| 5.9.0-rc4+                        | 1         | 0.55%   |
| 5.8.0-kali2-amd64                 | 1         | 0.55%   |
| 5.8.0-7625-generic                | 1         | 0.55%   |
| 5.8.0-55-generic                  | 1         | 0.55%   |
| 5.8.0-45-generic                  | 1         | 0.55%   |
| 5.8.0-44-generic                  | 1         | 0.55%   |
| 5.8.0-43-generic                  | 1         | 0.55%   |
| 5.8.0-38-generic                  | 1         | 0.55%   |
| 5.7.9-100.fc31.x86_64             | 1         | 0.55%   |
| 5.7.19-050719-generic             | 1         | 0.55%   |
| 5.7.0-2parrot2-amd64              | 1         | 0.55%   |
| 5.6.0-1048-oem                    | 1         | 0.55%   |
| 5.4.175-1.el8.elrepo.x86_64       | 1         | 0.55%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64 | 1         | 0.55%   |
| 5.4.15-arch1-1                    | 1         | 0.55%   |
| 5.4.0-99-generic                  | 1         | 0.55%   |
| 5.4.0-7642-generic                | 1         | 0.55%   |
| 5.4.0-7634-generic                | 1         | 0.55%   |
| 5.4.0-74-generic                  | 1         | 0.55%   |
| 5.4.0-70-generic                  | 1         | 0.55%   |
| 5.4.0-67-generic                  | 1         | 0.55%   |
| 5.4.0-59-generic                  | 1         | 0.55%   |
| 5.4.0-49-generic                  | 1         | 0.55%   |
| 5.4.0-37-generic                  | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 49        | 28.99%  |
| 5.11.0  | 20        | 11.83%  |
| 5.8.0   | 16        | 9.47%   |
| 5.13.0  | 16        | 9.47%   |
| 4.15.0  | 12        | 7.1%    |
| 5.3.0   | 7         | 4.14%   |
| 5.0.0   | 6         | 3.55%   |
| 5.15.0  | 5         | 2.96%   |
| 5.10.0  | 3         | 1.78%   |
| 4.18.0  | 3         | 1.78%   |
| 5.9.8   | 2         | 1.18%   |
| 5.10.14 | 2         | 1.18%   |
| 5.9.10  | 1         | 0.59%   |
| 5.9.0   | 1         | 0.59%   |
| 5.7.9   | 1         | 0.59%   |
| 5.7.19  | 1         | 0.59%   |
| 5.7.0   | 1         | 0.59%   |
| 5.6.0   | 1         | 0.59%   |
| 5.4.175 | 1         | 0.59%   |
| 5.4.17  | 1         | 0.59%   |
| 5.4.15  | 1         | 0.59%   |
| 5.2.13  | 1         | 0.59%   |
| 5.17.9  | 1         | 0.59%   |
| 5.17.5  | 1         | 0.59%   |
| 5.17.15 | 1         | 0.59%   |
| 5.16.7  | 1         | 0.59%   |
| 5.16.15 | 1         | 0.59%   |
| 5.16.0  | 1         | 0.59%   |
| 5.15.41 | 1         | 0.59%   |
| 5.14.2  | 1         | 0.59%   |
| 5.14.18 | 1         | 0.59%   |
| 5.14.11 | 1         | 0.59%   |
| 5.13.9  | 1         | 0.59%   |
| 5.13.7  | 1         | 0.59%   |
| 5.13.4  | 1         | 0.59%   |
| 5.13.13 | 1         | 0.59%   |
| 5.12.5  | 1         | 0.59%   |
| 5.12.12 | 1         | 0.59%   |
| 5.10.17 | 1         | 0.59%   |
| 4.9.124 | 1         | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 52        | 30.95%  |
| 5.13    | 20        | 11.9%   |
| 5.11    | 20        | 11.9%   |
| 5.8     | 16        | 9.52%   |
| 4.15    | 12        | 7.14%   |
| 5.3     | 7         | 4.17%   |
| 5.15    | 6         | 3.57%   |
| 5.10    | 6         | 3.57%   |
| 5.0     | 6         | 3.57%   |
| 5.9     | 3         | 1.79%   |
| 5.7     | 3         | 1.79%   |
| 5.17    | 3         | 1.79%   |
| 5.16    | 3         | 1.79%   |
| 5.14    | 3         | 1.79%   |
| 4.18    | 3         | 1.79%   |
| 5.12    | 2         | 1.19%   |
| 5.6     | 1         | 0.6%    |
| 5.2     | 1         | 0.6%    |
| 4.9     | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 160       | 98.16%  |
| i686   | 3         | 1.84%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 114       | 67.86%  |
| Unknown    | 19        | 11.31%  |
| KDE5       | 9         | 5.36%   |
| X-Cinnamon | 7         | 4.17%   |
| XFCE       | 5         | 2.98%   |
| KDE        | 5         | 2.98%   |
| Unity      | 3         | 1.79%   |
| Pantheon   | 2         | 1.19%   |
| MATE       | 1         | 0.6%    |
| KDE4       | 1         | 0.6%    |
| i3         | 1         | 0.6%    |
| Deepin     | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 132       | 79.04%  |
| Wayland | 19        | 11.38%  |
| Unknown | 16        | 9.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 99        | 60%     |
| GDM     | 34        | 20.61%  |
| GDM3    | 16        | 9.7%    |
| LightDM | 6         | 3.64%   |
| SDDM    | 5         | 3.03%   |
| TDM     | 4         | 2.42%   |
| KDM     | 1         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 141       | 85.45%  |
| Unknown | 17        | 10.3%   |
| en_GB   | 3         | 1.82%   |
| en_PK   | 2         | 1.21%   |
| ur_PK   | 1         | 0.61%   |
| C       | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 88        | 52.69%  |
| BIOS | 79        | 47.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 146       | 88.48%  |
| Btrfs   | 6         | 3.64%   |
| Overlay | 5         | 3.03%   |
| Unknown | 5         | 3.03%   |
| Xfs     | 2         | 1.21%   |
| Zfs     | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 114       | 69.51%  |
| GPT     | 38        | 23.17%  |
| MBR     | 12        | 7.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 146       | 89.02%  |
| Yes       | 18        | 10.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 63.86%  |
| Yes       | 60        | 36.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 60        | 36.81%  |
| Dell                | 50        | 30.67%  |
| Lenovo              | 27        | 16.56%  |
| Haier               | 5         | 3.07%   |
| Toshiba             | 3         | 1.84%   |
| Sony                | 3         | 1.84%   |
| ASUSTek Computer    | 3         | 1.84%   |
| Apple               | 3         | 1.84%   |
| Acer                | 3         | 1.84%   |
| Samsung Electronics | 2         | 1.23%   |
| MOTION              | 1         | 0.61%   |
| Gigabyte Technology | 1         | 0.61%   |
| Fujitsu             | 1         | 0.61%   |
| AMI                 | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP ProBook 450 G7                    | 5         | 3.07%   |
| HP EliteBook 8470p                   | 5         | 3.07%   |
| Dell Latitude E7450                  | 4         | 2.45%   |
| HP EliteBook 840 G3                  | 3         | 1.84%   |
| Haier Y11C                           | 3         | 1.84%   |
| Dell Latitude E6420                  | 3         | 1.84%   |
| Lenovo ThinkBook 15-IML 20RW         | 2         | 1.23%   |
| Lenovo ThinkBook 15-IIL 20SM         | 2         | 1.23%   |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 2         | 1.23%   |
| HP ZBook 15 G3                       | 2         | 1.23%   |
| HP ProBook 450 G5                    | 2         | 1.23%   |
| HP ProBook 450 G3                    | 2         | 1.23%   |
| HP ProBook 440 G7                    | 2         | 1.23%   |
| HP Pavilion Notebook                 | 2         | 1.23%   |
| HP EliteBook 8440p                   | 2         | 1.23%   |
| HP EliteBook 840 G2                  | 2         | 1.23%   |
| HP EliteBook 6930p                   | 2         | 1.23%   |
| HP 650                               | 2         | 1.23%   |
| Haier Y11B                           | 2         | 1.23%   |
| Dell Vostro 14-3468                  | 2         | 1.23%   |
| Dell Latitude E6440                  | 2         | 1.23%   |
| Dell Latitude E5250                  | 2         | 1.23%   |
| Dell Latitude E4300                  | 2         | 1.23%   |
| Dell Latitude 3510                   | 2         | 1.23%   |
| Dell Inspiron 5593                   | 2         | 1.23%   |
| Dell Inspiron 3501                   | 2         | 1.23%   |
| Dell Inspiron 15-3567                | 2         | 1.23%   |
| Unknown                              | 2         | 1.23%   |
| Toshiba Satellite S50t-B             | 1         | 0.61%   |
| Toshiba Satellite L850               | 1         | 0.61%   |
| Toshiba PORTEGE Z30-B                | 1         | 0.61%   |
| Sony VPCEA26FG                       | 1         | 0.61%   |
| Sony VPCCB490X                       | 1         | 0.61%   |
| Sony SVE15126CXS                     | 1         | 0.61%   |
| Samsung QX311/QX411/QX412/QX511      | 1         | 0.61%   |
| Samsung 940Z5L                       | 1         | 0.61%   |
| MOTION J3500                         | 1         | 0.61%   |
| Lenovo V110-15IKB 80TH               | 1         | 0.61%   |
| Lenovo ThinkPad X220 Tablet 4298A11  | 1         | 0.61%   |
| Lenovo ThinkPad X201 3249CTO         | 1         | 0.61%   |
| Lenovo ThinkPad W500 40612HU         | 1         | 0.61%   |
| Lenovo ThinkPad T60 1951WAT          | 1         | 0.61%   |
| Lenovo ThinkPad T540p 20BFS56300     | 1         | 0.61%   |
| Lenovo ThinkPad T460 20FMS39800      | 1         | 0.61%   |
| Lenovo ThinkPad T450 20BV0005US      | 1         | 0.61%   |
| Lenovo ThinkPad T440p 20AWS0DU00     | 1         | 0.61%   |
| Lenovo ThinkPad T440 20B7S1NK05      | 1         | 0.61%   |
| Lenovo ThinkPad E560 20EV0010UK      | 1         | 0.61%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GF00 | 1         | 0.61%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GE00 | 1         | 0.61%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GD00 | 1         | 0.61%   |
| Lenovo ThinkPad E15 Gen 2 20TD000QUE | 1         | 0.61%   |
| Lenovo ThinkPad E15 Gen 2 20TD000EUE | 1         | 0.61%   |
| Lenovo ThinkPad E15 20RD0088UE       | 1         | 0.61%   |
| Lenovo ThinkPad E14 20RA007SAD       | 1         | 0.61%   |
| Lenovo IdeaPad L340-15IWL 81LG       | 1         | 0.61%   |
| Lenovo IdeaPad 510-15ISK 80SR        | 1         | 0.61%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 1         | 0.61%   |
| HP ProBook 6560b                     | 1         | 0.61%   |
| HP ProBook 6470b                     | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 28        | 17.18%  |
| HP EliteBook       | 23        | 14.11%  |
| HP ProBook         | 19        | 11.66%  |
| Lenovo ThinkPad    | 17        | 10.43%  |
| Dell Inspiron      | 16        | 9.82%   |
| HP Pavilion        | 8         | 4.91%   |
| Lenovo ThinkBook   | 6         | 3.68%   |
| Lenovo IdeaPad     | 3         | 1.84%   |
| Haier Y11C         | 3         | 1.84%   |
| Dell Vostro        | 3         | 1.84%   |
| Acer Aspire        | 3         | 1.84%   |
| Toshiba Satellite  | 2         | 1.23%   |
| HP ZBook           | 2         | 1.23%   |
| HP Laptop          | 2         | 1.23%   |
| HP 650             | 2         | 1.23%   |
| Haier Y11B         | 2         | 1.23%   |
| Dell Precision     | 2         | 1.23%   |
| Unknown            | 2         | 1.23%   |
| Toshiba PORTEGE    | 1         | 0.61%   |
| Sony VPCEA26FG     | 1         | 0.61%   |
| Sony VPCCB490X     | 1         | 0.61%   |
| Sony SVE15126CXS   | 1         | 0.61%   |
| Samsung QX311      | 1         | 0.61%   |
| Samsung 940Z5L     | 1         | 0.61%   |
| MOTION J3500       | 1         | 0.61%   |
| Lenovo V110-15IKB  | 1         | 0.61%   |
| HP Notebook        | 1         | 0.61%   |
| HP ENVY            | 1         | 0.61%   |
| HP 14              | 1         | 0.61%   |
| Gigabyte AERO      | 1         | 0.61%   |
| Fujitsu LIFEBOOK   | 1         | 0.61%   |
| Dell G3            | 1         | 0.61%   |
| ASUS VivoBook      | 1         | 0.61%   |
| ASUS TUF           | 1         | 0.61%   |
| ASUS K53U          | 1         | 0.61%   |
| Apple MacBookPro16 | 1         | 0.61%   |
| Apple MacBookPro14 | 1         | 0.61%   |
| Apple MacBookAir6  | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 20        | 12.27%  |
| 2011 | 20        | 12.27%  |
| 2020 | 17        | 10.43%  |
| 2016 | 16        | 9.82%   |
| 2014 | 14        | 8.59%   |
| 2013 | 13        | 7.98%   |
| 2017 | 12        | 7.36%   |
| 2018 | 11        | 6.75%   |
| 2012 | 11        | 6.75%   |
| 2015 | 9         | 5.52%   |
| 2010 | 7         | 4.29%   |
| 2008 | 6         | 3.68%   |
| 2021 | 3         | 1.84%   |
| 2009 | 2         | 1.23%   |
| 2007 | 1         | 0.61%   |
| 2006 | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 163       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 154       | 93.9%   |
| Enabled  | 10        | 6.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 163       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 57        | 34.76%  |
| 3.01-4.0   | 37        | 22.56%  |
| 16.01-24.0 | 33        | 20.12%  |
| 8.01-16.0  | 27        | 16.46%  |
| 32.01-64.0 | 6         | 3.66%   |
| 1.01-2.0   | 3         | 1.83%   |
| 24.01-32.0 | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 61        | 35.06%  |
| 1.01-2.0  | 58        | 33.33%  |
| 4.01-8.0  | 24        | 13.79%  |
| 3.01-4.0  | 19        | 10.92%  |
| 8.01-16.0 | 7         | 4.02%   |
| 0.51-1.0  | 5         | 2.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 123       | 75%     |
| 2      | 37        | 22.56%  |
| 3      | 2         | 1.22%   |
| 4      | 1         | 0.61%   |
| 0      | 1         | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 69.51%  |
| Yes       | 50        | 30.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 93.87%  |
| No        | 10        | 6.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 99.39%  |
| No        | 1         | 0.61%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 71.69%  |
| No        | 47        | 28.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Pakistan | 163       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lahore                         | 61        | 36.53%  |
| Karachi                        | 37        | 22.16%  |
| Islamabad                      | 28        | 16.77%  |
| Rawalpindi                     | 10        | 5.99%   |
| Multan                         | 6         | 3.59%   |
| Faisalabad                     | 6         | 3.59%   |
| Peshawar                       | 2         | 1.2%    |
| Jhelum                         | 2         | 1.2%    |
| Vehari                         | 1         | 0.6%    |
| Sialkot                        | 1         | 0.6%    |
| Sargodha                       | 1         | 0.6%    |
| Rahim Yar Khan                 | 1         | 0.6%    |
| Pindi Gheb                     | 1         | 0.6%    |
| Mirpur                         | 1         | 0.6%    |
| Layari                         | 1         | 0.6%    |
| Khanewal                       | 1         | 0.6%    |
| Hassan Abdal                   | 1         | 0.6%    |
| Ghotki                         | 1         | 0.6%    |
| Dina                           | 1         | 0.6%    |
| Daska Kalan                    | 1         | 0.6%    |
| Dadu                           | 1         | 0.6%    |
| Chak Five Hundred Seventy-five | 1         | 0.6%    |
| Bahawalpur                     | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 37     | 15.2%   |
| Seagate             | 29        | 35     | 14.22%  |
| Samsung Electronics | 24        | 25     | 11.76%  |
| Toshiba             | 23        | 24     | 11.27%  |
| Kingston            | 10        | 12     | 4.9%    |
| Hitachi             | 9         | 11     | 4.41%   |
| Intel               | 8         | 10     | 3.92%   |
| Unknown             | 7         | 8      | 3.43%   |
| Transcend           | 7         | 7      | 3.43%   |
| SanDisk             | 6         | 7      | 2.94%   |
| HGST                | 6         | 7      | 2.94%   |
| Micron Technology   | 5         | 5      | 2.45%   |
| SK hynix            | 4         | 6      | 1.96%   |
| Silicon Motion      | 4         | 4      | 1.96%   |
| KIOXIA              | 3         | 3      | 1.47%   |
| HS-SSD-E100         | 3         | 3      | 1.47%   |
| Apple               | 3         | 4      | 1.47%   |
| A-DATA Technology   | 3         | 3      | 1.47%   |
| LITEON              | 2         | 2      | 0.98%   |
| Lexar               | 2         | 2      | 0.98%   |
| Fujitsu             | 2         | 2      | 0.98%   |
| Team                | 1         | 1      | 0.49%   |
| PNY                 | 1         | 2      | 0.49%   |
| Phison              | 1         | 2      | 0.49%   |
| PHD 3.0             | 1         | 1      | 0.49%   |
| LITEONIT            | 1         | 1      | 0.49%   |
| Kingsand            | 1         | 1      | 0.49%   |
| KESU                | 1         | 1      | 0.49%   |
| Integral            | 1         | 2      | 0.49%   |
| HS-SSD-E100N        | 1         | 1      | 0.49%   |
| CSD                 | 1         | 1      | 0.49%   |
| China               | 1         | 1      | 0.49%   |
| Biostar             | 1         | 1      | 0.49%   |
| Apacer              | 1         | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB             | 6         | 2.87%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 2.39%   |
| Toshiba MQ04ABF100 1TB               | 4         | 1.91%   |
| Toshiba MQ01ABF050 500GB             | 4         | 1.91%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 1.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.91%   |
| Samsung MZALQ512HALU-000L1 512GB     | 4         | 1.91%   |
| WDC PC SN530 NVMe 256GB              | 3         | 1.44%   |
| Toshiba MQ01ACF050 500GB             | 3         | 1.44%   |
| Silicon Motion NVMe SSD Drive 512GB  | 3         | 1.44%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 0.96%   |
| WDC WD10SPZX-75Z10T3 1TB             | 2         | 0.96%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.96%   |
| Transcend TS512GMTE110S 512GB        | 2         | 0.96%   |
| Transcend TS256GMTS830S 256GB SSD    | 2         | 0.96%   |
| Seagate ST9320423AS 320GB            | 2         | 0.96%   |
| Seagate ST9250315AS 250GB            | 2         | 0.96%   |
| Seagate ST9250311CS 250GB            | 2         | 0.96%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 0.96%   |
| SanDisk X110 MSATA 128GB SSD         | 2         | 0.96%   |
| KIOXIA NVMe SSD Drive 256GB          | 2         | 0.96%   |
| Intel SSDSA2M080G2GN 73GB            | 2         | 0.96%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.96%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 0.96%   |
| Hitachi HTS543225A7A384 250GB        | 2         | 0.96%   |
| HGST HTS541010B7E610 1TB             | 2         | 0.96%   |
| HGST HTS541010A9E680 1TB             | 2         | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.48%   |
| WDC WDS128G2G0B-00EPW0 128GB SSD     | 1         | 0.48%   |
| WDC WD5000LPVT-75G33T0 500GB         | 1         | 0.48%   |
| WDC WD3200LPVX-75V0TT0 320GB         | 1         | 0.48%   |
| WDC WD3200BEKX-75B7WT0 320GB         | 1         | 0.48%   |
| WDC WD2500BEVT-75A23T0 250GB         | 1         | 0.48%   |
| WDC WD2500BEVT-08A23T1 250GB         | 1         | 0.48%   |
| WDC WD2500BEVS-60UST0 250GB          | 1         | 0.48%   |
| WDC WD1600BEKT-08PVMT1 160GB         | 1         | 0.48%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 0.48%   |
| WDC WD10SPZX-22Z10T0 1TB             | 1         | 0.48%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.48%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.48%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.48%   |
| WDC WD10JPVT-75A1YT0 1TB             | 1         | 0.48%   |
| WDC WD Elements 500GB                | 1         | 0.48%   |
| WDC PC SN520 SDAPNUW-256G-1202 256GB | 1         | 0.48%   |
| WDC PC SN520 NVMe 512GB              | 1         | 0.48%   |
| Unknown SD8GB  7GB                   | 1         | 0.48%   |
| Unknown SD64G  64GB                  | 1         | 0.48%   |
| Unknown NVMe SSD Drive 256GB         | 1         | 0.48%   |
| Unknown NVMe SSD Drive 128GB         | 1         | 0.48%   |
| Unknown MMC Card  8GB                | 1         | 0.48%   |
| Unknown MMC Card  64GB               | 1         | 0.48%   |
| Unknown HDG8a4  128GB                | 1         | 0.48%   |
| Unknown External 320GB               | 1         | 0.48%   |
| Transcend TS512GSSD230S 512GB        | 1         | 0.48%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.48%   |
| Transcend TS120GSSD220S 120GB        | 1         | 0.48%   |
| Toshiba THNSNF128GCSS 128GB SSD      | 1         | 0.48%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.48%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.48%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 35     | 30.53%  |
| WDC                 | 25        | 28     | 26.32%  |
| Toshiba             | 20        | 21     | 21.05%  |
| Hitachi             | 9         | 11     | 9.47%   |
| HGST                | 6         | 7      | 6.32%   |
| Fujitsu             | 2         | 2      | 2.11%   |
| Unknown             | 1         | 1      | 1.05%   |
| Samsung Electronics | 1         | 1      | 1.05%   |
| PHD 3.0             | 1         | 1      | 1.05%   |
| KESU                | 1         | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 15     | 24.19%  |
| Kingston            | 9         | 11     | 14.52%  |
| SanDisk             | 5         | 5      | 8.06%   |
| Transcend           | 4         | 4      | 6.45%   |
| SK hynix            | 4         | 6      | 6.45%   |
| Micron Technology   | 4         | 4      | 6.45%   |
| Intel               | 4         | 5      | 6.45%   |
| WDC                 | 2         | 2      | 3.23%   |
| LITEON              | 2         | 2      | 3.23%   |
| Lexar               | 2         | 2      | 3.23%   |
| A-DATA Technology   | 2         | 2      | 3.23%   |
| Toshiba             | 1         | 1      | 1.61%   |
| Team                | 1         | 1      | 1.61%   |
| PNY                 | 1         | 2      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| HS-SSD-E100         | 1         | 1      | 1.61%   |
| China               | 1         | 1      | 1.61%   |
| Biostar             | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |
| Apacer              | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 91        | 108    | 45.73%  |
| SSD     | 62        | 68     | 31.16%  |
| NVMe    | 35        | 44     | 17.59%  |
| Unknown | 7         | 8      | 3.52%   |
| MMC     | 4         | 5      | 2.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 135       | 180    | 75.84%  |
| NVMe | 35        | 44     | 19.66%  |
| SAS  | 4         | 4      | 2.25%   |
| MMC  | 4         | 5      | 2.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 128    | 69.23%  |
| 0.51-1.0   | 44        | 48     | 30.77%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 70        | 41.18%  |
| 251-500        | 40        | 23.53%  |
| 51-100         | 31        | 18.24%  |
| 501-1000       | 14        | 8.24%   |
| 1-20           | 7         | 4.12%   |
| 21-50          | 5         | 2.94%   |
| 1001-2000      | 2         | 1.18%   |
| More than 3000 | 1         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 70        | 40%     |
| 21-50    | 53        | 30.29%  |
| 51-100   | 21        | 12%     |
| 101-250  | 20        | 11.43%  |
| 251-500  | 7         | 4%      |
| 501-1000 | 4         | 2.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 20%     |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 10%     |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 10%     |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 10%     |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 10%     |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 10%     |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 10%     |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 10%     |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 30%     |
| Seagate           | 2         | 2      | 20%     |
| Hitachi           | 2         | 2      | 20%     |
| SK hynix          | 1         | 1      | 10%     |
| Micron Technology | 1         | 1      | 10%     |
| Intel             | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 42.86%  |
| Seagate | 2         | 2      | 28.57%  |
| Hitachi | 2         | 2      | 28.57%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 70%     |
| SSD  | 3         | 3      | 30%     |

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
| Detected | 114       | 165    | 67.46%  |
| Works    | 45        | 58     | 26.63%  |
| Malfunc  | 10        | 10     | 5.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 144       | 78.26%  |
| Samsung Electronics          | 8         | 4.35%   |
| SanDisk                      | 6         | 3.26%   |
| AMD                          | 6         | 3.26%   |
| Silicon Motion               | 5         | 2.72%   |
| KIOXIA                       | 5         | 2.72%   |
| Unknown                      | 2         | 1.09%   |
| Apple                        | 2         | 1.09%   |
| Toshiba America Info Systems | 1         | 0.54%   |
| Realtek Semiconductor        | 1         | 0.54%   |
| Phison Electronics           | 1         | 0.54%   |
| Micron Technology            | 1         | 0.54%   |
| Marvell Technology Group     | 1         | 0.54%   |
| Kingston Technology Company  | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 28        | 13.86%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 16        | 7.92%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 13        | 6.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 13        | 6.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 11        | 5.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 10        | 4.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 4.46%   |
| Samsung NVMe SSD Controller 980                                                        | 6         | 2.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 2.97%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 5         | 2.48%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 5         | 2.48%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 5         | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 2.48%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 2.48%   |
| SanDisk Non-Volatile memory controller                                                 | 4         | 1.98%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 1.98%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 1.98%   |
| Intel Non-Volatile memory controller                                                   | 3         | 1.49%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 3         | 1.49%   |
| Unknown Non-Volatile memory controller                                                 | 2         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.99%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.99%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 2         | 0.99%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.5%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.5%    |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.5%    |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 0.5%    |
| Phison E12 NVMe Controller                                                             | 1         | 0.5%    |
| Micron Non-Volatile memory controller                                                  | 1         | 0.5%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 1         | 0.5%    |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.5%    |
| Intel SSD 660P Series                                                                  | 1         | 0.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 0.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.5%    |
| Apple S3X NVMe Controller                                                              | 1         | 0.5%    |
| Apple ANS2 NVMe Controller                                                             | 1         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 126       | 65.28%  |
| NVMe | 35        | 18.13%  |
| RAID | 20        | 10.36%  |
| IDE  | 12        | 6.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 157       | 96.32%  |
| AMD    | 6         | 3.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 4.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 4.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 4.29%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 6         | 3.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 5         | 3.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 3.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 3.07%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 2.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 2.45%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 3         | 1.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.84%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.84%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 3         | 1.84%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 1.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 1.84%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 2         | 1.23%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 1.23%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 1.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 1.23%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 2         | 1.23%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 1.23%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 1.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 1.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.23%   |
| Intel Core i5-3427U CPU @ 1.80GHz       | 2         | 1.23%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 2         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 1.23%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 1.23%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 2         | 1.23%   |
| Intel Core i3-2328M CPU @ 2.20GHz       | 2         | 1.23%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 1.23%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz    | 2         | 1.23%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 1.23%   |
| Intel Pentium CPU B940 @ 2.00GHz        | 1         | 0.61%   |
| Intel Genuine CPU T2400 @ 1.83GHz       | 1         | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.61%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 1         | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 0.61%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 0.61%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 0.61%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 0.61%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 1         | 0.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.61%   |
| Intel Core i7-4558U CPU @ 2.80GHz       | 1         | 0.61%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 0.61%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 0.61%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 0.61%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 0.61%   |
| Intel Core i7 CPU U 680 @ 1.47GHz       | 1         | 0.61%   |
| Intel Core i7 CPU M 620 @ 2.67GHz       | 1         | 0.61%   |
| Intel Core i7 CPU L 640 @ 2.13GHz       | 1         | 0.61%   |
| Intel Core i5-7360U CPU @ 2.30GHz       | 1         | 0.61%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 0.61%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 68        | 41.72%  |
| Intel Core i7        | 49        | 30.06%  |
| Other                | 12        | 7.36%   |
| Intel Core i3        | 9         | 5.52%   |
| Intel Core 2 Duo     | 7         | 4.29%   |
| Intel Core m3        | 3         | 1.84%   |
| Intel Celeron        | 3         | 1.84%   |
| Intel Core M         | 2         | 1.23%   |
| AMD Ryzen 7          | 2         | 1.23%   |
| Intel Pentium        | 1         | 0.61%   |
| Intel Genuine        | 1         | 0.61%   |
| Intel Core 2 Extreme | 1         | 0.61%   |
| Intel Atom           | 1         | 0.61%   |
| AMD Ryzen 5          | 1         | 0.61%   |
| AMD E                | 1         | 0.61%   |
| AMD A6               | 1         | 0.61%   |
| AMD A12              | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 102       | 62.58%  |
| 4      | 54        | 33.13%  |
| 6      | 5         | 3.07%   |
| 8      | 2         | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 163       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 143       | 87.73%  |
| 1      | 20        | 12.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 161       | 98.17%  |
| Unknown        | 2         | 1.22%   |
| 32-bit         | 1         | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 15.57%  |
| 0x206a7    | 14        | 8.38%   |
| 0x806ec    | 12        | 7.19%   |
| 0x806e9    | 11        | 6.59%   |
| 0x806c1    | 11        | 6.59%   |
| 0x406e3    | 11        | 6.59%   |
| 0x306d4    | 11        | 6.59%   |
| 0x40651    | 9         | 5.39%   |
| 0x306a9    | 9         | 5.39%   |
| 0x20655    | 9         | 5.39%   |
| 0x806ea    | 8         | 4.79%   |
| 0x706e5    | 5         | 2.99%   |
| 0x306c3    | 5         | 2.99%   |
| 0x1067a    | 4         | 2.4%    |
| 0x906ea    | 3         | 1.8%    |
| 0x506e3    | 2         | 1.2%    |
| 0x30678    | 2         | 1.2%    |
| 0x10676    | 2         | 1.2%    |
| 0xa0660    | 1         | 0.6%    |
| 0xa0652    | 1         | 0.6%    |
| 0x906e9    | 1         | 0.6%    |
| 0x806eb    | 1         | 0.6%    |
| 0x706a1    | 1         | 0.6%    |
| 0x6fd      | 1         | 0.6%    |
| 0x406c4    | 1         | 0.6%    |
| 0x08608103 | 1         | 0.6%    |
| 0x08600106 | 1         | 0.6%    |
| 0x08600104 | 1         | 0.6%    |
| 0x0700010f | 1         | 0.6%    |
| 0x0600611a | 1         | 0.6%    |
| 0x05000119 | 1         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 39        | 23.93%  |
| Haswell       | 17        | 10.43%  |
| SandyBridge   | 16        | 9.82%   |
| Skylake       | 15        | 9.2%    |
| Broadwell     | 15        | 9.2%    |
| IvyBridge     | 13        | 7.98%   |
| TigerLake     | 12        | 7.36%   |
| Westmere      | 10        | 6.13%   |
| Penryn        | 7         | 4.29%   |
| IceLake       | 5         | 3.07%   |
| Silvermont    | 3         | 1.84%   |
| Zen 2         | 2         | 1.23%   |
| CometLake     | 2         | 1.23%   |
| P6            | 1         | 0.61%   |
| Jaguar        | 1         | 0.61%   |
| Goldmont plus | 1         | 0.61%   |
| Excavator     | 1         | 0.61%   |
| Core          | 1         | 0.61%   |
| Bobcat        | 1         | 0.61%   |
| Unknown       | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 149       | 73.76%  |
| Nvidia | 27        | 13.37%  |
| AMD    | 26        | 12.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 7.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 6.86%   |
| Intel HD Graphics 5500                                                                   | 13        | 6.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 5.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 5.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 5.39%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.92%   |
| Intel HD Graphics 620                                                                    | 7         | 3.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.43%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 3.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.94%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 1.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.96%   |
| Intel HD Graphics 615                                                                    | 3         | 1.47%   |
| Intel HD Graphics 530                                                                    | 3         | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.47%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.98%   |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 0.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.98%   |
| Intel HD Graphics 5300                                                                   | 2         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.98%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 2         | 0.98%   |
| AMD Renoir                                                                               | 2         | 0.98%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.49%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.49%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.49%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.49%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.49%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.49%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.49%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.49%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.49%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.49%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.49%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.49%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.49%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.49%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.49%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.49%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 0.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.49%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.49%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.49%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.49%   |
| Intel HD Graphics 630                                                                    | 1         | 0.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.49%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.49%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 0.49%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.49%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.49%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 68.1%   |
| Intel + Nvidia | 22        | 13.5%   |
| Intel + AMD    | 16        | 9.82%   |
| 1 x AMD        | 9         | 5.52%   |
| 1 x Nvidia     | 4         | 2.45%   |
| AMD + Nvidia   | 1         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 150       | 92.02%  |
| Proprietary | 12        | 7.36%   |
| Unknown     | 1         | 0.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 71.52%  |
| 1.01-2.0   | 25        | 15.15%  |
| 0.01-0.5   | 9         | 5.45%   |
| 3.01-4.0   | 6         | 3.64%   |
| 0.51-1.0   | 6         | 3.64%   |
| 5.01-6.0   | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 45        | 26.01%  |
| Chimei Innolux          | 31        | 17.92%  |
| AU Optronics            | 27        | 15.61%  |
| BOE                     | 22        | 12.72%  |
| Samsung Electronics     | 14        | 8.09%   |
| Dell                    | 7         | 4.05%   |
| Chi Mei Optoelectronics | 5         | 2.89%   |
| Hewlett-Packard         | 3         | 1.73%   |
| Apple                   | 3         | 1.73%   |
| Sony                    | 2         | 1.16%   |
| Sharp                   | 2         | 1.16%   |
| LG Philips              | 2         | 1.16%   |
| Lenovo                  | 2         | 1.16%   |
| KDC                     | 2         | 1.16%   |
| Goldstar                | 2         | 1.16%   |
| PANDA                   | 1         | 0.58%   |
| LPL                     | 1         | 0.58%   |
| LGD                     | 1         | 0.58%   |
| Acer                    | 1         | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 3.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 5         | 2.89%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 4         | 2.31%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 3         | 1.73%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.73%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 3         | 1.73%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 3         | 1.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.16%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 2         | 1.16%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 1.16%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 1.16%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.16%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 2         | 1.16%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.16%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2         | 1.16%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                     | 2         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 2         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1332 1366x768 293x165mm 13.2-inch       | 2         | 1.16%   |
| BOE LCD Monitor BOE08C6 1920x1080 344x194mm 15.5-inch                 | 2         | 1.16%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                 | 2         | 1.16%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO5024 1280x800 286x178mm 13.3-inch         | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 2         | 1.16%   |
| Sony TV SNYAC03 1360x768                                              | 1         | 0.58%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.58%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.58%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 0.58%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC414A 1920x1080 294x165mm 13.3-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 0.58%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.58%   |
| LPL LCD Monitor 1440x900                                              | 1         | 0.58%   |
| LGD LCD Monitor 1920x1080                                             | 1         | 0.58%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.58%   |
| LG Philips LCD Monitor LGP9C1C 1024x768 285x214mm 14.0-inch           | 1         | 0.58%   |
| LG Display LP156WH2-TLR2 LGD027D 1366x768 344x194mm 15.5-inch         | 1         | 0.58%   |
| LG Display LCD Monitor LGD0684 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch           | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 69        | 41.32%  |
| 1366x768 (WXGA)    | 68        | 40.72%  |
| 1600x900 (HD+)     | 7         | 4.19%   |
| 1280x800 (WXGA)    | 6         | 3.59%   |
| 1680x1050 (WSXGA+) | 4         | 2.4%    |
| 3840x2160 (4K)     | 3         | 1.8%    |
| 1440x900 (WXGA+)   | 3         | 1.8%    |
| 3440x1440          | 1         | 0.6%    |
| 2880x1800          | 1         | 0.6%    |
| 2560x1600          | 1         | 0.6%    |
| 1920x1200 (WUXGA)  | 1         | 0.6%    |
| 1360x768           | 1         | 0.6%    |
| 1280x1024 (SXGA)   | 1         | 0.6%    |
| 1024x768 (XGA)     | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 79        | 45.93%  |
| 14      | 33        | 19.19%  |
| 13      | 23        | 13.37%  |
| 17      | 8         | 4.65%   |
| 12      | 6         | 3.49%   |
| 24      | 5         | 2.91%   |
| 11      | 4         | 2.33%   |
| 23      | 3         | 1.74%   |
| 21      | 3         | 1.74%   |
| 22      | 2         | 1.16%   |
| Unknown | 2         | 1.16%   |
| 72      | 1         | 0.58%   |
| 40      | 1         | 0.58%   |
| 20      | 1         | 0.58%   |
| 18      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 121       | 71.18%  |
| 201-300     | 22        | 12.94%  |
| 351-400     | 9         | 5.29%   |
| 501-600     | 7         | 4.12%   |
| 401-500     | 7         | 4.12%   |
| Unknown     | 2         | 1.18%   |
| 801-900     | 1         | 0.59%   |
| 1501-2000   | 1         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 141       | 87.58%  |
| 16/10   | 15        | 9.32%   |
| Unknown | 2         | 1.24%   |
| 5/4     | 1         | 0.62%   |
| 4/3     | 1         | 0.62%   |
| 3/2     | 1         | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 45.61%  |
| 81-90          | 45        | 26.32%  |
| 201-250        | 11        | 6.43%   |
| 71-80          | 9         | 5.26%   |
| 61-70          | 6         | 3.51%   |
| 121-130        | 5         | 2.92%   |
| 51-60          | 4         | 2.34%   |
| 91-100         | 3         | 1.75%   |
| 151-200        | 2         | 1.17%   |
| 141-150        | 2         | 1.17%   |
| 131-140        | 2         | 1.17%   |
| Unknown        | 2         | 1.17%   |
| More than 1000 | 1         | 0.58%   |
| 501-1000       | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 75        | 44.12%  |
| 101-120       | 64        | 37.65%  |
| 51-100        | 20        | 11.76%  |
| More than 240 | 4         | 2.35%   |
| 161-240       | 4         | 2.35%   |
| Unknown       | 2         | 1.18%   |
| 1-50          | 1         | 0.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 147       | 90.18%  |
| 2     | 14        | 8.59%   |
| 3     | 1         | 0.61%   |
| 0     | 1         | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 118       | 45.38%  |
| Realtek Semiconductor    | 84        | 32.31%  |
| Qualcomm Atheros         | 19        | 7.31%   |
| Broadcom                 | 13        | 5%      |
| Broadcom Limited         | 6         | 2.31%   |
| MediaTek                 | 4         | 1.54%   |
| Hewlett-Packard          | 4         | 1.54%   |
| Ralink                   | 3         | 1.15%   |
| Sierra Wireless          | 2         | 0.77%   |
| Dell                     | 2         | 0.77%   |
| Qualcomm                 | 1         | 0.38%   |
| Marvell Technology Group | 1         | 0.38%   |
| Huawei Technologies      | 1         | 0.38%   |
| D-Link                   | 1         | 0.38%   |
| ASIX Electronics         | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 61        | 18.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 16        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 4.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 13        | 3.87%   |
| Intel Wireless 7265                                                            | 12        | 3.57%   |
| Intel Wi-Fi 6 AX201                                                            | 11        | 3.27%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 3.27%   |
| Intel Wireless 3165                                                            | 10        | 2.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 10        | 2.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 9         | 2.68%   |
| Intel Wireless 8260                                                            | 7         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 2.08%   |
| Intel Wireless 7260                                                            | 6         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 5         | 1.49%   |
| Intel Ultimate N WiFi Link 5300                                                | 5         | 1.49%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 1.49%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.49%   |
| Intel Centrino Advanced-N 6200                                                 | 5         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 1.19%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.19%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.19%   |
| Intel Centrino Advanced-N 6235                                                 | 4         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 0.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 3         | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 0.89%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 3         | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.6%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 2         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2         | 0.6%    |
| MediaTek moto e(6) plus                                                        | 2         | 0.6%    |
| Intel Wireless-AC 9260                                                         | 2         | 0.6%    |
| Intel Wireless 8265 / 8275                                                     | 2         | 0.6%    |
| Intel Wireless 3160                                                            | 2         | 0.6%    |
| Intel Wi-Fi 6 AX200                                                            | 2         | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 2         | 0.6%    |
| Intel Ethernet Connection I219-V                                               | 2         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 2         | 0.6%    |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                           | 2         | 0.6%    |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 0.6%    |
| HP lt4112 Gobi 4G Module Network Device                                        | 2         | 0.6%    |
| Dell Hub of E-Port Replicator                                                  | 2         | 0.6%    |
| Sierra Wireless EM7345 4G LTE                                                  | 1         | 0.3%    |
| Sierra Wireless EM7305                                                         | 1         | 0.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.3%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.3%    |
| Qualcomm BENGAL-QRD _SN:C5464635                                               | 1         | 0.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.3%    |
| MediaTek RMX3085                                                               | 1         | 0.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.3%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.3%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 1         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 110       | 64.33%  |
| Qualcomm Atheros      | 18        | 10.53%  |
| Realtek Semiconductor | 16        | 9.36%   |
| Broadcom              | 13        | 7.6%    |
| Ralink                | 3         | 1.75%   |
| Broadcom Limited      | 3         | 1.75%   |
| Sierra Wireless       | 2         | 1.17%   |
| Hewlett-Packard       | 2         | 1.17%   |
| Dell                  | 2         | 1.17%   |
| MediaTek              | 1         | 0.58%   |
| D-Link                | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 13        | 7.51%   |
| Intel Wireless 7265                                                  | 12        | 6.94%   |
| Intel Wi-Fi 6 AX201                                                  | 11        | 6.36%   |
| Intel Wireless 3165                                                  | 10        | 5.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 10        | 5.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 9         | 5.2%    |
| Intel Wireless 8260                                                  | 7         | 4.05%   |
| Intel Wireless 7260                                                  | 6         | 3.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 5         | 2.89%   |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 2.89%   |
| Intel Centrino Advanced-N 6200                                       | 5         | 2.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 2.31%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 2.31%   |
| Intel Centrino Advanced-N 6235                                       | 4         | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 2.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 3         | 1.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.73%   |
| Broadcom BCM43142 802.11b/g/n                                        | 3         | 1.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.16%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 2         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 1.16%   |
| Intel Wireless-AC 9260                                               | 2         | 1.16%   |
| Intel Wireless 8265 / 8275                                           | 2         | 1.16%   |
| Intel Wireless 3160                                                  | 2         | 1.16%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 1.16%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                 | 2         | 1.16%   |
| HP lt4112 Gobi 4G Module Network Device                              | 2         | 1.16%   |
| Dell Hub of E-Port Replicator                                        | 2         | 1.16%   |
| Sierra Wireless EM7345 4G LTE                                        | 1         | 0.58%   |
| Sierra Wireless EM7305                                               | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.58%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 1         | 0.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 0.58%   |
| Intel Centrino Wireless-N 6150                                       | 1         | 0.58%   |
| Intel Centrino Wireless-N 2230                                       | 1         | 0.58%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.58%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 1         | 0.58%   |
| Intel Centrino Wireless-N + WiMAX 6150                               | 1         | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 0.58%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 0.58%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 0.58%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1         | 0.58%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                              | 1         | 0.58%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                   | 1         | 0.58%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                   | 1         | 0.58%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                   | 1         | 0.58%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 1         | 0.58%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 0.58%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 81        | 50.94%  |
| Intel                    | 65        | 40.88%  |
| MediaTek                 | 3         | 1.89%   |
| Broadcom Limited         | 3         | 1.89%   |
| Qualcomm Atheros         | 1         | 0.63%   |
| Qualcomm                 | 1         | 0.63%   |
| Marvell Technology Group | 1         | 0.63%   |
| Huawei Technologies      | 1         | 0.63%   |
| Hewlett-Packard          | 1         | 0.63%   |
| Broadcom                 | 1         | 0.63%   |
| ASIX Electronics         | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 61        | 37.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 16        | 9.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 9.26%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 6.79%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 4.32%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 3.09%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 3.09%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 3.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.47%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 2.47%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 1.85%   |
| MediaTek moto e(6) plus                                                        | 2         | 1.23%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.23%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 1.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.62%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                               | 1         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.62%   |
| MediaTek RMX3085                                                               | 1         | 0.62%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.62%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.62%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.62%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.62%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.62%   |
| Huawei E353/E3131                                                              | 1         | 0.62%   |
| HP lt4211 Gobi 4G Module                                                       | 1         | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.62%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.62%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.62%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 51.27%  |
| Ethernet | 153       | 48.42%  |
| Modem    | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 89.09%  |
| Ethernet | 18        | 10.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 148       | 90.24%  |
| 1     | 13        | 7.93%   |
| 0     | 2         | 1.22%   |
| 3     | 1         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 95.71%  |
| Yes  | 7         | 4.29%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 59.66%  |
| Qualcomm Atheros Communications | 12        | 10.08%  |
| Broadcom                        | 11        | 9.24%   |
| Realtek Semiconductor           | 9         | 7.56%   |
| Dell                            | 4         | 3.36%   |
| Ralink                          | 3         | 2.52%   |
| Foxconn / Hon Hai               | 3         | 2.52%   |
| IMC Networks                    | 2         | 1.68%   |
| Hewlett-Packard                 | 2         | 1.68%   |
| Lite-On Technology              | 1         | 0.84%   |
| Apple                           | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 37        | 31.09%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 12.61%  |
| Intel AX201 Bluetooth                                                               | 13        | 10.92%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 7.56%   |
| Realtek Bluetooth Radio                                                             | 5         | 4.2%    |
| Broadcom HP Portable SoftSailing                                                    | 4         | 3.36%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.52%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.52%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.52%   |
| Intel AX200 Bluetooth                                                               | 2         | 1.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.68%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.68%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.68%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.84%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.84%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.84%   |
| Intel Bluetooth Device                                                              | 1         | 0.84%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.84%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.84%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.84%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.84%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.84%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.84%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.84%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.84%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.84%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.84%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 156       | 86.67%  |
| Nvidia                 | 9         | 5%      |
| AMD                    | 9         | 5%      |
| Logitech               | 2         | 1.11%   |
| Generalplus Technology | 2         | 1.11%   |
| Realtek Semiconductor  | 1         | 0.56%   |
| Apple                  | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 31        | 14.22%  |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 6.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 6.88%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 6.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 6.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 6.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 5.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 5.05%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 5.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 4.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 3.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 2.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.92%   |
| Logitech Headset H340                                                      | 2         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.92%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.92%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.46%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.46%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.46%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.46%   |
| Intel Audio device                                                         | 1         | 0.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.46%   |
| Generalplus Technology USB Microphone                                      | 1         | 0.46%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.46%   |
| Apple Audio Device                                                         | 1         | 0.46%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.46%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 0.46%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.46%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 27        | 29.03%  |
| Samsung Electronics | 23        | 24.73%  |
| Micron Technology   | 12        | 12.9%   |
| A-DATA Technology   | 7         | 7.53%   |
| Transcend           | 5         | 5.38%   |
| Team                | 3         | 3.23%   |
| Crucial             | 3         | 3.23%   |
| Unknown             | 2         | 2.15%   |
| Spectek             | 2         | 2.15%   |
| Lexar               | 2         | 2.15%   |
| Elpida              | 2         | 2.15%   |
| Unknown (768A)      | 1         | 1.08%   |
| TwinMOS             | 1         | 1.08%   |
| Kingston            | 1         | 1.08%   |
| Hikvision           | 1         | 1.08%   |
| Axiom               | 1         | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s               | 5         | 5%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 3%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 3%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3%      |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 2         | 2%      |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s              | 2         | 2%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 2%      |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s               | 2         | 2%      |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 2         | 2%      |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 2%      |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s        | 2         | 2%      |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 2         | 2%      |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 2         | 2%      |
| Lexar RAM LD4AS016G-H2666G 16384MB SODIMM DDR4 2667MT/s      | 2         | 2%      |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                  | 1         | 1%      |
| Unknown RAM DDR3 1600 8G 8GB SODIMM DDR3 1333MT/s            | 1         | 1%      |
| Unknown (768A) RAM Module 16384MB SODIMM DDR4 2667MT/s       | 1         | 1%      |
| TwinMOS RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 3200MT/s     | 1         | 1%      |
| Transcend RAM Module 8GB SODIMM DDR4 3200MT/s                | 1         | 1%      |
| Transcend RAM Module 8192MB SODIMM DDR4 3200MT/s             | 1         | 1%      |
| Transcend RAM Module 8192MB SODIMM DDR4 2400MT/s             | 1         | 1%      |
| Transcend RAM Module 16384MB SODIMM DDR4 2667MT/s            | 1         | 1%      |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s        | 1         | 1%      |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s         | 1         | 1%      |
| Spectek RAM Module 8GB Row Of Chips LPDDR3 1600MT/s          | 1         | 1%      |
| Spectek RAM Module 8192MB Row Of Chips LPDDR3 1600MT/s       | 1         | 1%      |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s              | 1         | 1%      |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s              | 1         | 1%      |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 1%      |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                | 1         | 1%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1%      |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1%      |
| SK hynix RAM HMT451B6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1%      |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1%      |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s       | 1         | 1%      |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 1%      |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 1%      |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1%      |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 1%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 1%      |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 1%      |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1%      |
| SK hynix RAM HMA81GS6DJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 1         | 1%      |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1%      |
| Samsung RAM Module 4096MB SODIMM DDR4 2400MT/s               | 1         | 1%      |
| Samsung RAM Module 16384MB SODIMM DDR4 2133MT/s              | 1         | 1%      |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1%      |
| Samsung RAM M471B5173QHY-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 1%      |
| Samsung RAM M471A5644EB0-CPB 2GB SODIMM DDR4 2133MT/s        | 1         | 1%      |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 1         | 1%      |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s        | 1         | 1%      |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 1         | 1%      |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s    | 1         | 1%      |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 1%      |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1%      |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 1%      |
| Micron RAM Module 4096MB SODIMM LPDDR3 2133MT/s              | 1         | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 56.76%  |
| DDR3   | 26        | 35.14%  |
| LPDDR3 | 3         | 4.05%   |
| LPDDR4 | 2         | 2.7%    |
| DDR    | 1         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 91.78%  |
| Row Of Chips | 5         | 6.85%   |
| DIMM         | 1         | 1.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 35.8%   |
| 4096  | 26        | 32.1%   |
| 16384 | 18        | 22.22%  |
| 2048  | 5         | 6.17%   |
| 32768 | 3         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 24        | 28.92%  |
| 2667  | 22        | 26.51%  |
| 3200  | 12        | 14.46%  |
| 2400  | 7         | 8.43%   |
| 2133  | 6         | 7.23%   |
| 1334  | 5         | 6.02%   |
| 1333  | 3         | 3.61%   |
| 8400  | 1         | 1.2%    |
| 4267  | 1         | 1.2%    |
| 1067  | 1         | 1.2%    |
| 1066  | 1         | 1.2%    |

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
| Chicony Electronics                    | 41        | 27.89%  |
| Microdia                               | 22        | 14.97%  |
| Sunplus Innovation Technology          | 13        | 8.84%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 8.84%   |
| Realtek Semiconductor                  | 9         | 6.12%   |
| Lite-On Technology                     | 8         | 5.44%   |
| Acer                                   | 6         | 4.08%   |
| Suyin                                  | 5         | 3.4%    |
| Ricoh                                  | 5         | 3.4%    |
| Quanta                                 | 5         | 3.4%    |
| IMC Networks                           | 5         | 3.4%    |
| Syntek                                 | 3         | 2.04%   |
| Silicon Motion                         | 3         | 2.04%   |
| Luxvisions Innotech Limited            | 2         | 1.36%   |
| Apple                                  | 2         | 1.36%   |
| Primax Electronics                     | 1         | 0.68%   |
| Pixart Imaging                         | 1         | 0.68%   |
| Logitech                               | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| DigiTech                               | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 11        | 7.48%   |
| Chicony HP HD Camera                                                       | 9         | 6.12%   |
| Chicony Integrated Camera                                                  | 8         | 5.44%   |
| Sunplus Integrated_Webcam_HD                                               | 6         | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 5         | 3.4%    |
| Microdia Integrated Webcam                                                 | 4         | 2.72%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 2.04%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 2.04%   |
| Realtek Integrated Webcam                                                  | 3         | 2.04%   |
| Lite-On HP HD Webcam                                                       | 3         | 2.04%   |
| Lite-On HP HD Camera                                                       | 3         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 2.04%   |
| Chicony USB 2.0Camera                                                      | 3         | 2.04%   |
| Chicony EasyCamera                                                         | 3         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 2.04%   |
| Acer Integrated Camera                                                     | 3         | 2.04%   |
| Syntek Integrated Camera                                                   | 2         | 1.36%   |
| Sunplus HP Universal Camera                                                | 2         | 1.36%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 1.36%   |
| Realtek MTD camera                                                         | 2         | 1.36%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 1.36%   |
| Quanta HP HD Camera                                                        | 2         | 1.36%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 1.36%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 1.36%   |
| Lite-On Integrated Camera                                                  | 2         | 1.36%   |
| IMC Networks Integrated Camera                                             | 2         | 1.36%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.36%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 1.36%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 1.36%   |
| Chicony HP Truevision HD                                                   | 2         | 1.36%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 2         | 1.36%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 2         | 1.36%   |
| Syntek USB 2.0 PC Cam                                                      | 1         | 0.68%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 1         | 0.68%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.68%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.68%   |
| Suyin HP TrueVision HD                                                     | 1         | 0.68%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.68%   |
| Sunplus Laptop Integrated Webcam HD                                        | 1         | 0.68%   |
| Sunplus Integrated Webcam                                                  | 1         | 0.68%   |
| Silicon Motion ATIV Real HD Camera                                         | 1         | 0.68%   |
| Ricoh Integrated Webcam                                                    | 1         | 0.68%   |
| Ricoh HD Webcam                                                            | 1         | 0.68%   |
| Realtek Integrated Webcam_HD                                               | 1         | 0.68%   |
| Realtek HP Truevision HD                                                   | 1         | 0.68%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 0.68%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 0.68%   |
| Quanta HD WebCam                                                           | 1         | 0.68%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 0.68%   |
| Pixart Imaging USB_2.0_Webcam                                              | 1         | 0.68%   |
| Microdia Webcam                                                            | 1         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 0.68%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 0.68%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 0.68%   |
| Logitech HP Webcam                                                         | 1         | 0.68%   |
| Lenovo Integrated Webcam                                                   | 1         | 0.68%   |
| DigiTech WebCam SCB-0380M                                                  | 1         | 0.68%   |
| Chicony VGA Webcam                                                         | 1         | 0.68%   |
| Chicony USB2.0 Camera                                                      | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 36        | 69.23%  |
| Synaptics                  | 7         | 13.46%  |
| AuthenTec                  | 4         | 7.69%   |
| Shenzhen Goodix Technology | 3         | 5.77%   |
| Upek                       | 2         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 28.85%  |
| Validity Sensors VFS491                                                    | 7         | 13.46%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 13.46%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.77%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.77%   |
| AuthenTec AES2810                                                          | 3         | 5.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.92%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.92%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.92%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 18        | 94.74%  |
| O2 Micro | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 47.37%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 42.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |
| Broadcom 5880                                                                | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 82        | 50%     |
| 1     | 73        | 44.51%  |
| 2     | 8         | 4.88%   |
| 4     | 1         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 55.43%  |
| Chipcard                 | 19        | 20.65%  |
| Storage                  | 4         | 4.35%   |
| Net/wireless             | 4         | 4.35%   |
| Graphics card            | 4         | 4.35%   |
| Bluetooth                | 4         | 4.35%   |
| Sound                    | 1         | 1.09%   |
| Network                  | 1         | 1.09%   |
| Net/ethernet             | 1         | 1.09%   |
| Multimedia controller    | 1         | 1.09%   |
| Communication controller | 1         | 1.09%   |
| Camera                   | 1         | 1.09%   |


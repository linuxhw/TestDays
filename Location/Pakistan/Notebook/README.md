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

Total: 265

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad E580 20KTA001GE    | [55dc6ac7ba](https://linux-hardware.org/?probe=55dc6ac7ba) | Oct 31, 2022 |
| Dell     | Inspiron 13-7359            | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| Dell     | Studio 1458                 | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| HP       | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo   | Legion 5 15IMH05H 81Y6      | [11573d282c](https://linux-hardware.org/?probe=11573d282c) | Oct 13, 2022 |
| Lenovo   | Legion 5 15IMH05H 81Y6      | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| Dell     | Vostro 15 5510              | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell     | Vostro 15 5510              | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP       | Laptop 15s-du3xxx           | [cbacce92bd](https://linux-hardware.org/?probe=cbacce92bd) | Oct 05, 2022 |
| HP       | Pavilion dv6                | [2830144a8a](https://linux-hardware.org/?probe=2830144a8a) | Oct 04, 2022 |
| HP       | EliteBook 850 G8 Noteboo... | [b01a9ac97f](https://linux-hardware.org/?probe=b01a9ac97f) | Sep 24, 2022 |
| HP       | Laptop 15-bs1xx             | [5657597c18](https://linux-hardware.org/?probe=5657597c18) | Sep 22, 2022 |
| HP       | ENVY 15                     | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| HP       | EliteBook 840 G2            | [ca96e9bf9b](https://linux-hardware.org/?probe=ca96e9bf9b) | Sep 14, 2022 |
| HP       | EliteBook 840 G3            | [be88e72feb](https://linux-hardware.org/?probe=be88e72feb) | Sep 14, 2022 |
| HP       | EliteBook 840 G3            | [2b1c502b28](https://linux-hardware.org/?probe=2b1c502b28) | Sep 14, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TDS... | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| HP       | ProBook 4540s               | [c1bf52b653](https://linux-hardware.org/?probe=c1bf52b653) | Sep 13, 2022 |
| HP       | ProBook 4540s               | [320e270f44](https://linux-hardware.org/?probe=320e270f44) | Sep 13, 2022 |
| HP       | EliteBook Folio 9470m       | [c03777782c](https://linux-hardware.org/?probe=c03777782c) | Sep 13, 2022 |
| HP       | Unknown                     | [5cf262a728](https://linux-hardware.org/?probe=5cf262a728) | Sep 10, 2022 |
| Lenovo   | ThinkPad T470 20HES3370A    | [5beda28487](https://linux-hardware.org/?probe=5beda28487) | Sep 09, 2022 |
| Dell     | Latitude 3340               | [ec720c63b1](https://linux-hardware.org/?probe=ec720c63b1) | Sep 06, 2022 |
| Lenovo   | ThinkPad T470 20HES3370A    | [3a466cef0a](https://linux-hardware.org/?probe=3a466cef0a) | Sep 05, 2022 |
| Dell     | Latitude E6420              | [98a628a92a](https://linux-hardware.org/?probe=98a628a92a) | Sep 03, 2022 |
| Dell     | Latitude E6420              | [e9c43bd2ab](https://linux-hardware.org/?probe=e9c43bd2ab) | Sep 03, 2022 |
| Dell     | Latitude 3340               | [b9d472b965](https://linux-hardware.org/?probe=b9d472b965) | Sep 01, 2022 |
| Dell     | Latitude 7390               | [571b195a12](https://linux-hardware.org/?probe=571b195a12) | Aug 31, 2022 |
| Dell     | Latitude 7390               | [3c3f6114f6](https://linux-hardware.org/?probe=3c3f6114f6) | Aug 31, 2022 |
| HP       | EliteBook 840 G2            | [5ba91d8167](https://linux-hardware.org/?probe=5ba91d8167) | Aug 30, 2022 |
| HP       | EliteBook 840 G1            | [23d73aa95c](https://linux-hardware.org/?probe=23d73aa95c) | Aug 30, 2022 |
| HP       | EliteBook 840 G2            | [bed3be5142](https://linux-hardware.org/?probe=bed3be5142) | Aug 30, 2022 |
| HP       | EliteBook 840 G2            | [b588415d06](https://linux-hardware.org/?probe=b588415d06) | Aug 30, 2022 |
| Lenovo   | ThinkPad T470 20HES3370A    | [3b1630e4bc](https://linux-hardware.org/?probe=3b1630e4bc) | Aug 30, 2022 |
| HP       | Unknown                     | [9b22ce41e3](https://linux-hardware.org/?probe=9b22ce41e3) | Aug 27, 2022 |
| Dell     | Latitude 7400               | [7f870ac8c2](https://linux-hardware.org/?probe=7f870ac8c2) | Aug 17, 2022 |
| Acer     | Predator PH317-53           | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [072d897eda](https://linux-hardware.org/?probe=072d897eda) | Jul 28, 2022 |
| Dell     | Latitude E6420              | [07a671ae31](https://linux-hardware.org/?probe=07a671ae31) | Jul 22, 2022 |
| Dell     | Latitude E5440              | [3b30865387](https://linux-hardware.org/?probe=3b30865387) | Jul 20, 2022 |
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


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 67        | 34.72%  |
| Ubuntu 18.04       | 20        | 10.36%  |
| Ubuntu 22.04       | 14        | 7.25%   |
| Arch               | 5         | 2.59%   |
| KDE neon 20.04     | 4         | 2.07%   |
| Zorin 16           | 3         | 1.55%   |
| Ubuntu 21.10       | 3         | 1.55%   |
| Ubuntu 21.04       | 3         | 1.55%   |
| Ubuntu 19.04       | 3         | 1.55%   |
| Pop!_OS 21.04      | 3         | 1.55%   |
| Pop!_OS 20.10      | 3         | 1.55%   |
| Pop!_OS 20.04      | 3         | 1.55%   |
| Linux Mint 20      | 3         | 1.55%   |
| Fedora 33          | 3         | 1.55%   |
| Zorin 15           | 2         | 1.04%   |
| OpenMandriva 4.3   | 2         | 1.04%   |
| OpenMandriva 4.2   | 2         | 1.04%   |
| Linux Mint 20.3    | 2         | 1.04%   |
| Linux Mint 20.2    | 2         | 1.04%   |
| Linux Mint 20.1    | 2         | 1.04%   |
| Kali 2022.3        | 2         | 1.04%   |
| Fedora 36          | 2         | 1.04%   |
| Elementary 6.1     | 2         | 1.04%   |
| Debian 11          | 2         | 1.04%   |
| Zorin 12           | 1         | 0.52%   |
| Xero Rolling       | 1         | 0.52%   |
| Ubuntu Unity 20.04 | 1         | 0.52%   |
| Ubuntu Unity 18.04 | 1         | 0.52%   |
| Ubuntu Unity 16.04 | 1         | 0.52%   |
| Ubuntu 19.10       | 1         | 0.52%   |
| Ubuntu 18.10       | 1         | 0.52%   |
| Ubuntu 16.04       | 1         | 0.52%   |
| ROSA R10           | 1         | 0.52%   |
| RHEL 8             | 1         | 0.52%   |
| Pop!_OS 22.04      | 1         | 0.52%   |
| Parrot 4.10        | 1         | 0.52%   |
| Oracle Linux 8.4   | 1         | 0.52%   |
| Nobara 36          | 1         | 0.52%   |
| Manjaro 21.2.6     | 1         | 0.52%   |
| Manjaro 21.1.2     | 1         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 113       | 59.47%  |
| Pop!_OS      | 9         | 4.74%   |
| Linux Mint   | 8         | 4.21%   |
| Fedora       | 8         | 4.21%   |
| Zorin        | 6         | 3.16%   |
| Arch         | 5         | 2.63%   |
| OpenMandriva | 4         | 2.11%   |
| KDE neon     | 4         | 2.11%   |
| Kali         | 4         | 2.11%   |
| Ubuntu Unity | 3         | 1.58%   |
| Manjaro      | 3         | 1.58%   |
| Kubuntu      | 3         | 1.58%   |
| Endless      | 3         | 1.58%   |
| Elementary   | 2         | 1.05%   |
| Debian       | 2         | 1.05%   |
| ArcoLinux    | 2         | 1.05%   |
| Xero         | 1         | 0.53%   |
| ROSA         | 1         | 0.53%   |
| RHEL         | 1         | 0.53%   |
| Parrot       | 1         | 0.53%   |
| Oracle Linux | 1         | 0.53%   |
| Nobara       | 1         | 0.53%   |
| LinuxFX      | 1         | 0.53%   |
| EndeavourOS  | 1         | 0.53%   |
| Deepin       | 1         | 0.53%   |
| Clear Linux  | 1         | 0.53%   |
| AlmaLinux    | 1         | 0.53%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 9         | 4.33%   |
| 5.15.0-46-generic        | 8         | 3.85%   |
| 5.15.0-47-generic        | 5         | 2.4%    |
| 5.11.0-37-generic        | 5         | 2.4%    |
| 5.4.0-48-generic         | 4         | 1.92%   |
| 5.4.0-47-generic         | 4         | 1.92%   |
| 5.4.0-40-generic         | 4         | 1.92%   |
| 5.8.0-7630-generic       | 3         | 1.44%   |
| 5.8.0-41-generic         | 3         | 1.44%   |
| 5.4.0-54-generic         | 3         | 1.44%   |
| 5.4.0-52-generic         | 3         | 1.44%   |
| 5.4.0-26-generic         | 3         | 1.44%   |
| 5.3.0-28-generic         | 3         | 1.44%   |
| 5.13.0-39-generic        | 3         | 1.44%   |
| 5.13.0-30-generic        | 3         | 1.44%   |
| 5.9.8-200.fc33.x86_64    | 2         | 0.96%   |
| 5.8.0-59-generic         | 2         | 0.96%   |
| 5.8.0-48-generic         | 2         | 0.96%   |
| 5.4.0-91-generic         | 2         | 0.96%   |
| 5.4.0-58-generic         | 2         | 0.96%   |
| 5.4.0-45-generic         | 2         | 0.96%   |
| 5.4.0-39-generic         | 2         | 0.96%   |
| 5.4.0-33-generic         | 2         | 0.96%   |
| 5.4.0-29-generic         | 2         | 0.96%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.96%   |
| 5.15.0-50-generic        | 2         | 0.96%   |
| 5.15.0-48-generic        | 2         | 0.96%   |
| 5.15.0-41-generic        | 2         | 0.96%   |
| 5.15.0-25-generic        | 2         | 0.96%   |
| 5.13.0-44-generic        | 2         | 0.96%   |
| 5.13.0-28-generic        | 2         | 0.96%   |
| 5.11.0-7620-generic      | 2         | 0.96%   |
| 5.11.0-43-generic        | 2         | 0.96%   |
| 5.11.0-41-generic        | 2         | 0.96%   |
| 5.11.0-40-generic        | 2         | 0.96%   |
| 5.11.0-38-generic        | 2         | 0.96%   |
| 5.11.0-27-generic        | 2         | 0.96%   |
| 5.10.14-desktop-1omv4002 | 2         | 0.96%   |
| 5.0.0-23-generic         | 2         | 0.96%   |
| 4.15.0-66-generic        | 2         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 25.91%  |
| 5.15.0  | 20        | 10.36%  |
| 5.11.0  | 20        | 10.36%  |
| 5.8.0   | 16        | 8.29%   |
| 5.13.0  | 16        | 8.29%   |
| 4.15.0  | 12        | 6.22%   |
| 5.3.0   | 7         | 3.63%   |
| 5.0.0   | 6         | 3.11%   |
| 5.10.0  | 3         | 1.55%   |
| 4.18.0  | 3         | 1.55%   |
| 5.9.8   | 2         | 1.04%   |
| 5.19.9  | 2         | 1.04%   |
| 5.16.7  | 2         | 1.04%   |
| 5.10.14 | 2         | 1.04%   |
| 5.9.10  | 1         | 0.52%   |
| 5.9.0   | 1         | 0.52%   |
| 5.7.9   | 1         | 0.52%   |
| 5.7.19  | 1         | 0.52%   |
| 5.7.0   | 1         | 0.52%   |
| 5.6.0   | 1         | 0.52%   |
| 5.4.175 | 1         | 0.52%   |
| 5.4.17  | 1         | 0.52%   |
| 5.4.15  | 1         | 0.52%   |
| 5.2.13  | 1         | 0.52%   |
| 5.19.14 | 1         | 0.52%   |
| 5.19.13 | 1         | 0.52%   |
| 5.19.0  | 1         | 0.52%   |
| 5.18.16 | 1         | 0.52%   |
| 5.18.0  | 1         | 0.52%   |
| 5.17.9  | 1         | 0.52%   |
| 5.17.5  | 1         | 0.52%   |
| 5.17.15 | 1         | 0.52%   |
| 5.16.15 | 1         | 0.52%   |
| 5.16.0  | 1         | 0.52%   |
| 5.15.41 | 1         | 0.52%   |
| 5.14.2  | 1         | 0.52%   |
| 5.14.18 | 1         | 0.52%   |
| 5.14.11 | 1         | 0.52%   |
| 5.13.9  | 1         | 0.52%   |
| 5.13.7  | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 27.6%   |
| 5.15    | 21        | 10.94%  |
| 5.13    | 20        | 10.42%  |
| 5.11    | 20        | 10.42%  |
| 5.8     | 16        | 8.33%   |
| 4.15    | 12        | 6.25%   |
| 5.3     | 7         | 3.65%   |
| 5.10    | 6         | 3.13%   |
| 5.0     | 6         | 3.13%   |
| 5.19    | 5         | 2.6%    |
| 5.16    | 4         | 2.08%   |
| 5.9     | 3         | 1.56%   |
| 5.7     | 3         | 1.56%   |
| 5.17    | 3         | 1.56%   |
| 5.14    | 3         | 1.56%   |
| 4.18    | 3         | 1.56%   |
| 5.18    | 2         | 1.04%   |
| 5.12    | 2         | 1.04%   |
| 5.6     | 1         | 0.52%   |
| 5.2     | 1         | 0.52%   |
| 4.9     | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 183       | 98.39%  |
| i686   | 3         | 1.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 131       | 68.59%  |
| Unknown    | 19        | 9.95%   |
| KDE5       | 12        | 6.28%   |
| XFCE       | 7         | 3.66%   |
| X-Cinnamon | 7         | 3.66%   |
| KDE        | 5         | 2.62%   |
| Unity      | 3         | 1.57%   |
| Pantheon   | 2         | 1.05%   |
| i3         | 2         | 1.05%   |
| MATE       | 1         | 0.52%   |
| KDE4       | 1         | 0.52%   |
| Deepin     | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 147       | 76.96%  |
| Wayland | 28        | 14.66%  |
| Unknown | 16        | 8.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 104       | 55.32%  |
| GDM     | 34        | 18.09%  |
| GDM3    | 29        | 15.43%  |
| SDDM    | 8         | 4.26%   |
| LightDM | 8         | 4.26%   |
| TDM     | 4         | 2.13%   |
| KDM     | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 163       | 86.7%   |
| Unknown | 17        | 9.04%   |
| en_GB   | 4         | 2.13%   |
| en_PK   | 2         | 1.06%   |
| ur_PK   | 1         | 0.53%   |
| C       | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 98        | 51.58%  |
| BIOS | 92        | 48.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 166       | 88.3%   |
| Btrfs   | 8         | 4.26%   |
| Overlay | 6         | 3.19%   |
| Unknown | 5         | 2.66%   |
| Xfs     | 2         | 1.06%   |
| Zfs     | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 128       | 68.45%  |
| GPT     | 45        | 24.06%  |
| MBR     | 14        | 7.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 166       | 88.3%   |
| Yes       | 22        | 11.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 118       | 62.43%  |
| Yes       | 71        | 37.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 72        | 38.71%  |
| Dell                | 57        | 30.65%  |
| Lenovo              | 30        | 16.13%  |
| Haier               | 5         | 2.69%   |
| Acer                | 4         | 2.15%   |
| Toshiba             | 3         | 1.61%   |
| Sony                | 3         | 1.61%   |
| ASUSTek Computer    | 3         | 1.61%   |
| Apple               | 3         | 1.61%   |
| Samsung Electronics | 2         | 1.08%   |
| MOTION              | 1         | 0.54%   |
| Gigabyte Technology | 1         | 0.54%   |
| Fujitsu             | 1         | 0.54%   |
| AMI                 | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP ProBook 450 G7               | 5         | 2.69%   |
| HP EliteBook 8470p              | 5         | 2.69%   |
| HP EliteBook 840 G3             | 4         | 2.15%   |
| Dell Latitude E7450             | 4         | 2.15%   |
| Dell Latitude E6420             | 4         | 2.15%   |
| HP ProBook 450 G5               | 3         | 1.61%   |
| HP EliteBook 840 G2             | 3         | 1.61%   |
| Haier Y11C                      | 3         | 1.61%   |
| Unknown                         | 3         | 1.61%   |
| Lenovo ThinkBook 15-IML 20RW    | 2         | 1.08%   |
| Lenovo ThinkBook 15-IIL 20SM    | 2         | 1.08%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 2         | 1.08%   |
| HP ZBook 15 G3                  | 2         | 1.08%   |
| HP ProBook 450 G3               | 2         | 1.08%   |
| HP ProBook 440 G7               | 2         | 1.08%   |
| HP Pavilion Notebook            | 2         | 1.08%   |
| HP Pavilion dv6                 | 2         | 1.08%   |
| HP EliteBook Folio 9470m        | 2         | 1.08%   |
| HP EliteBook 8440p              | 2         | 1.08%   |
| HP EliteBook 840 G1             | 2         | 1.08%   |
| HP EliteBook 6930p              | 2         | 1.08%   |
| HP 650                          | 2         | 1.08%   |
| Haier Y11B                      | 2         | 1.08%   |
| Dell Vostro 14-3468             | 2         | 1.08%   |
| Dell Latitude E6440             | 2         | 1.08%   |
| Dell Latitude E5250             | 2         | 1.08%   |
| Dell Latitude E4300             | 2         | 1.08%   |
| Dell Latitude 3510              | 2         | 1.08%   |
| Dell Inspiron 5593              | 2         | 1.08%   |
| Dell Inspiron 3501              | 2         | 1.08%   |
| Dell Inspiron 15-3567           | 2         | 1.08%   |
| Toshiba Satellite S50t-B        | 1         | 0.54%   |
| Toshiba Satellite L850          | 1         | 0.54%   |
| Toshiba PORTEGE Z30-B           | 1         | 0.54%   |
| Sony VPCEA26FG                  | 1         | 0.54%   |
| Sony VPCCB490X                  | 1         | 0.54%   |
| Sony SVE15126CXS                | 1         | 0.54%   |
| Samsung QX311/QX411/QX412/QX511 | 1         | 0.54%   |
| Samsung 940Z5L                  | 1         | 0.54%   |
| MOTION J3500                    | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 32        | 17.2%   |
| HP EliteBook       | 28        | 15.05%  |
| HP ProBook         | 21        | 11.29%  |
| Lenovo ThinkPad    | 19        | 10.22%  |
| Dell Inspiron      | 17        | 9.14%   |
| HP Pavilion        | 9         | 4.84%   |
| Lenovo ThinkBook   | 6         | 3.23%   |
| HP Laptop          | 4         | 2.15%   |
| Dell Vostro        | 4         | 2.15%   |
| Lenovo IdeaPad     | 3         | 1.61%   |
| Haier Y11C         | 3         | 1.61%   |
| Acer Aspire        | 3         | 1.61%   |
| Unknown            | 3         | 1.61%   |
| Toshiba Satellite  | 2         | 1.08%   |
| HP ZBook           | 2         | 1.08%   |
| HP ENVY            | 2         | 1.08%   |
| HP 650             | 2         | 1.08%   |
| Haier Y11B         | 2         | 1.08%   |
| Dell Precision     | 2         | 1.08%   |
| Toshiba PORTEGE    | 1         | 0.54%   |
| Sony VPCEA26FG     | 1         | 0.54%   |
| Sony VPCCB490X     | 1         | 0.54%   |
| Sony SVE15126CXS   | 1         | 0.54%   |
| Samsung QX311      | 1         | 0.54%   |
| Samsung 940Z5L     | 1         | 0.54%   |
| MOTION J3500       | 1         | 0.54%   |
| Lenovo V110-15IKB  | 1         | 0.54%   |
| Lenovo Legion      | 1         | 0.54%   |
| HP Notebook        | 1         | 0.54%   |
| HP 14              | 1         | 0.54%   |
| Gigabyte AERO      | 1         | 0.54%   |
| Fujitsu LIFEBOOK   | 1         | 0.54%   |
| Dell Studio        | 1         | 0.54%   |
| Dell G3            | 1         | 0.54%   |
| ASUS VivoBook      | 1         | 0.54%   |
| ASUS TUF           | 1         | 0.54%   |
| ASUS K53U          | 1         | 0.54%   |
| Apple MacBookPro16 | 1         | 0.54%   |
| Apple MacBookPro14 | 1         | 0.54%   |
| Apple MacBookAir6  | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 22        | 11.83%  |
| 2011 | 21        | 11.29%  |
| 2020 | 19        | 10.22%  |
| 2016 | 17        | 9.14%   |
| 2017 | 15        | 8.06%   |
| 2014 | 15        | 8.06%   |
| 2013 | 14        | 7.53%   |
| 2018 | 13        | 6.99%   |
| 2012 | 13        | 6.99%   |
| 2015 | 11        | 5.91%   |
| 2010 | 10        | 5.38%   |
| 2008 | 7         | 3.76%   |
| 2021 | 5         | 2.69%   |
| 2009 | 2         | 1.08%   |
| 2007 | 1         | 0.54%   |
| 2006 | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 186       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 176       | 94.12%  |
| Enabled  | 11        | 5.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 186       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 66        | 35.29%  |
| 3.01-4.0   | 39        | 20.86%  |
| 16.01-24.0 | 39        | 20.86%  |
| 8.01-16.0  | 32        | 17.11%  |
| 32.01-64.0 | 6         | 3.21%   |
| 1.01-2.0   | 3         | 1.6%    |
| 24.01-32.0 | 2         | 1.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 66        | 32.84%  |
| 1.01-2.0  | 64        | 31.84%  |
| 4.01-8.0  | 34        | 16.92%  |
| 3.01-4.0  | 25        | 12.44%  |
| 8.01-16.0 | 7         | 3.48%   |
| 0.51-1.0  | 5         | 2.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 74.87%  |
| 2      | 43        | 22.99%  |
| 3      | 2         | 1.07%   |
| 4      | 1         | 0.53%   |
| 0      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 132       | 70.59%  |
| Yes       | 55        | 29.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 93.55%  |
| No        | 12        | 6.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 99.46%  |
| No        | 1         | 0.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 72.49%  |
| No        | 52        | 27.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Pakistan | 186       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lahore                         | 63        | 33.16%  |
| Karachi                        | 43        | 22.63%  |
| Islamabad                      | 33        | 17.37%  |
| Rawalpindi                     | 13        | 6.84%   |
| Multan                         | 6         | 3.16%   |
| Mirpur                         | 6         | 3.16%   |
| Faisalabad                     | 6         | 3.16%   |
| Peshawar                       | 2         | 1.05%   |
| Jhelum                         | 2         | 1.05%   |
| Bahawalpur                     | 2         | 1.05%   |
| Vehari                         | 1         | 0.53%   |
| Sialkot                        | 1         | 0.53%   |
| Sargodha                       | 1         | 0.53%   |
| Rahim Yar Khan                 | 1         | 0.53%   |
| Pindi Gheb                     | 1         | 0.53%   |
| Layari                         | 1         | 0.53%   |
| Kohat                          | 1         | 0.53%   |
| Khanewal                       | 1         | 0.53%   |
| Hassan Abdal                   | 1         | 0.53%   |
| Ghotki                         | 1         | 0.53%   |
| Dina                           | 1         | 0.53%   |
| Daska Kalan                    | 1         | 0.53%   |
| Dadu                           | 1         | 0.53%   |
| Chak Five Hundred Seventy-five | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 44     | 15.09%  |
| Samsung Electronics | 32        | 37     | 13.79%  |
| Seagate             | 30        | 36     | 12.93%  |
| Toshiba             | 26        | 27     | 11.21%  |
| Kingston            | 14        | 16     | 6.03%   |
| Hitachi             | 10        | 12     | 4.31%   |
| Transcend           | 8         | 8      | 3.45%   |
| Intel               | 8         | 10     | 3.45%   |
| Unknown             | 7         | 8      | 3.02%   |
| SanDisk             | 7         | 8      | 3.02%   |
| HGST                | 6         | 7      | 2.59%   |
| SK hynix            | 5         | 7      | 2.16%   |
| Micron Technology   | 5         | 5      | 2.16%   |
| Silicon Motion      | 4         | 4      | 1.72%   |
| KIOXIA              | 4         | 4      | 1.72%   |
| A-DATA Technology   | 4         | 4      | 1.72%   |
| HS-SSD-E100         | 3         | 3      | 1.29%   |
| Apple               | 3         | 4      | 1.29%   |
| LITEON              | 2         | 2      | 0.86%   |
| Lexar               | 2         | 2      | 0.86%   |
| Fujitsu             | 2         | 2      | 0.86%   |
| China               | 2         | 3      | 0.86%   |
| Team                | 1         | 1      | 0.43%   |
| SPCC                | 1         | 1      | 0.43%   |
| PNY                 | 1         | 2      | 0.43%   |
| Phison              | 1         | 2      | 0.43%   |
| PHD 3.0             | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| Kingsand            | 1         | 1      | 0.43%   |
| KESU                | 1         | 1      | 0.43%   |
| Integral            | 1         | 2      | 0.43%   |
| HS-SSD-E100N        | 1         | 1      | 0.43%   |
| CSD                 | 1         | 1      | 0.43%   |
| Biostar             | 1         | 1      | 0.43%   |
| Apacer              | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB            | 6         | 2.51%   |
| Toshiba MQ04ABF100 1TB              | 5         | 2.09%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 2.09%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.67%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 1.67%   |
| Samsung MZALQ512HALU-000L1 512GB    | 4         | 1.67%   |
| WDC PC SN530 NVMe 256GB             | 3         | 1.26%   |
| Toshiba MQ01ACF050 500GB            | 3         | 1.26%   |
| Silicon Motion NVMe SSD Drive 512GB | 3         | 1.26%   |
| Seagate ST500LM000-1EJ162 500GB     | 3         | 1.26%   |
| Hitachi HTS545032B9A300 320GB       | 3         | 1.26%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 0.84%   |
| WDC WD10SPZX-75Z10T3 1TB            | 2         | 0.84%   |
| WDC WD10SPZX-24Z10 1TB              | 2         | 0.84%   |
| Transcend TS512GMTE110S 512GB       | 2         | 0.84%   |
| Transcend TS256GMTS830S 256GB SSD   | 2         | 0.84%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.84%   |
| Toshiba MQ01ABD050 500GB            | 2         | 0.84%   |
| Seagate ST9320423AS 320GB           | 2         | 0.84%   |
| Seagate ST9250315AS 250GB           | 2         | 0.84%   |
| Seagate ST9250311CS 250GB           | 2         | 0.84%   |
| SanDisk X110 MSATA 128GB SSD        | 2         | 0.84%   |
| Samsung SSD 870 EVO 500GB           | 2         | 0.84%   |
| KIOXIA NVMe SSD Drive 256GB         | 2         | 0.84%   |
| Intel SSDSA2M080G2GN 80GB           | 2         | 0.84%   |
| Intel NVMe SSD Drive 512GB          | 2         | 0.84%   |
| Hitachi HTS543225A7A384 250GB       | 2         | 0.84%   |
| HGST HTS541010B7E610 1TB            | 2         | 0.84%   |
| HGST HTS541010A9E680 1TB            | 2         | 0.84%   |
| WDC WDS256G2G0B-00EPW0 256GB SSD    | 1         | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.42%   |
| WDC WDS128G2G0B-00EPW0 128GB SSD    | 1         | 0.42%   |
| WDC WD5000LPVT-75G33T0 500GB        | 1         | 0.42%   |
| WDC WD3200LPVX-75V0TT0 320GB        | 1         | 0.42%   |
| WDC WD3200BEKX-75B7WT0 320GB        | 1         | 0.42%   |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 0.42%   |
| WDC WD2500BEVT-08A23T1 250GB        | 1         | 0.42%   |
| WDC WD2500BEVS-60UST0 250GB         | 1         | 0.42%   |
| WDC WD2500BEKT-75A25T0 250GB        | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 36     | 29.13%  |
| WDC                 | 27        | 31     | 26.21%  |
| Toshiba             | 23        | 24     | 22.33%  |
| Hitachi             | 10        | 12     | 9.71%   |
| HGST                | 6         | 7      | 5.83%   |
| Samsung Electronics | 2         | 2      | 1.94%   |
| Fujitsu             | 2         | 2      | 1.94%   |
| Unknown             | 1         | 1      | 0.97%   |
| PHD 3.0             | 1         | 1      | 0.97%   |
| KESU                | 1         | 1      | 0.97%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 23     | 28.95%  |
| Kingston            | 11        | 13     | 14.47%  |
| SanDisk             | 5         | 5      | 6.58%   |
| WDC                 | 4         | 6      | 5.26%   |
| Transcend           | 4         | 4      | 5.26%   |
| SK hynix            | 4         | 6      | 5.26%   |
| Micron Technology   | 4         | 4      | 5.26%   |
| Intel               | 4         | 5      | 5.26%   |
| A-DATA Technology   | 3         | 3      | 3.95%   |
| LITEON              | 2         | 2      | 2.63%   |
| Lexar               | 2         | 2      | 2.63%   |
| China               | 2         | 3      | 2.63%   |
| Toshiba             | 1         | 1      | 1.32%   |
| Team                | 1         | 1      | 1.32%   |
| SPCC                | 1         | 1      | 1.32%   |
| PNY                 | 1         | 2      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| HS-SSD-E100         | 1         | 1      | 1.32%   |
| Biostar             | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |
| Apacer              | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 99        | 117    | 43.81%  |
| SSD     | 74        | 86     | 32.74%  |
| NVMe    | 42        | 53     | 18.58%  |
| Unknown | 7         | 8      | 3.1%    |
| MMC     | 4         | 5      | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 153       | 207    | 75.37%  |
| NVMe | 42        | 53     | 20.69%  |
| SAS  | 4         | 4      | 1.97%   |
| MMC  | 4         | 5      | 1.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 113       | 149    | 69.33%  |
| 0.51-1.0   | 49        | 53     | 30.06%  |
| 1.01-2.0   | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 79        | 40.72%  |
| 251-500        | 47        | 24.23%  |
| 51-100         | 34        | 17.53%  |
| 501-1000       | 18        | 9.28%   |
| 1-20           | 8         | 4.12%   |
| 21-50          | 5         | 2.58%   |
| 1001-2000      | 2         | 1.03%   |
| More than 3000 | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 78        | 39%     |
| 21-50    | 62        | 31%     |
| 101-250  | 25        | 12.5%   |
| 51-100   | 24        | 12%     |
| 251-500  | 7         | 3.5%    |
| 501-1000 | 4         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 15.38%  |
| WDC WD2500BEKT-75A25T0 250GB                  | 1         | 2      | 7.69%   |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 7.69%   |
| Toshiba MQ04ABF100 1TB                        | 1         | 1      | 7.69%   |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 7.69%   |
| Seagate ST500LM000-1EJ162 500GB               | 1         | 1      | 7.69%   |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 7.69%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 7.69%   |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 7.69%   |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 7.69%   |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 5      | 30.77%  |
| Seagate           | 3         | 3      | 23.08%  |
| Hitachi           | 2         | 2      | 15.38%  |
| Toshiba           | 1         | 1      | 7.69%   |
| SK hynix          | 1         | 1      | 7.69%   |
| Micron Technology | 1         | 1      | 7.69%   |
| Intel             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 40%     |
| Seagate | 3         | 3      | 30%     |
| Hitachi | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 76.92%  |
| SSD  | 3         | 3      | 23.08%  |

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
| Detected | 128       | 185    | 65.98%  |
| Works    | 53        | 70     | 27.32%  |
| Malfunc  | 13        | 14     | 6.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 165       | 77.83%  |
| Samsung Electronics          | 9         | 4.25%   |
| SanDisk                      | 7         | 3.3%    |
| KIOXIA                       | 6         | 2.83%   |
| AMD                          | 6         | 2.83%   |
| Silicon Motion               | 5         | 2.36%   |
| Transcend                    | 3         | 1.42%   |
| Kingston Technology Company  | 3         | 1.42%   |
| Apple                        | 2         | 0.94%   |
| Toshiba America Info Systems | 1         | 0.47%   |
| SK hynix                     | 1         | 0.47%   |
| Realtek Semiconductor        | 1         | 0.47%   |
| Phison Electronics           | 1         | 0.47%   |
| Micron Technology            | 1         | 0.47%   |
| Marvell Technology Group     | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 34        | 14.72%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 17        | 7.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 15        | 6.49%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 13        | 5.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 12        | 5.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 11        | 4.76%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 7         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 7         | 3.03%   |
| Samsung NVMe SSD Controller 980                                                        | 6         | 2.6%    |
| KIOXIA NVMe SSD Controller BG4                                                         | 6         | 2.6%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 6         | 2.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 2.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 5         | 2.16%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 2.16%   |
| SanDisk Non-Volatile memory controller                                                 | 4         | 1.73%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 1.73%   |
| Transcend Non-Volatile memory controller                                               | 3         | 1.3%    |
| Intel Non-Volatile memory controller                                                   | 3         | 1.3%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 3         | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 0.87%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.87%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.87%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 0.87%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 2         | 0.87%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.43%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.43%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.43%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.43%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.43%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 144       | 64.86%  |
| NVMe | 42        | 18.92%  |
| RAID | 24        | 10.81%  |
| IDE  | 12        | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 180       | 96.77%  |
| AMD    | 6         | 3.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 4.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 8         | 4.3%    |
| Intel Core i5-5300U CPU @ 2.30GHz       | 7         | 3.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 3.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 3.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 3.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 3.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 5         | 2.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 2.15%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 2.15%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 4         | 2.15%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 3         | 1.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 1.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 1.61%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 1.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 1.61%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 2         | 1.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 1.08%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 1.08%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 2         | 1.08%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 1.08%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 1.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 1.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 1.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 1.08%   |
| Intel Core i5-3427U CPU @ 1.80GHz       | 2         | 1.08%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 2         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 1.08%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 1.08%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 1.08%   |
| Intel Core i3-2328M CPU @ 2.20GHz       | 2         | 1.08%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 1.08%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz    | 2         | 1.08%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 77        | 41.4%   |
| Intel Core i7        | 58        | 31.18%  |
| Other                | 15        | 8.06%   |
| Intel Core i3        | 11        | 5.91%   |
| Intel Core 2 Duo     | 7         | 3.76%   |
| Intel Core m3        | 3         | 1.61%   |
| Intel Celeron        | 3         | 1.61%   |
| Intel Core M         | 2         | 1.08%   |
| AMD Ryzen 7          | 2         | 1.08%   |
| Intel Pentium        | 1         | 0.54%   |
| Intel Genuine        | 1         | 0.54%   |
| Intel Core 2 Extreme | 1         | 0.54%   |
| Intel Atom           | 1         | 0.54%   |
| AMD Ryzen 5          | 1         | 0.54%   |
| AMD E                | 1         | 0.54%   |
| AMD A6               | 1         | 0.54%   |
| AMD A12              | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 113       | 60.75%  |
| 4      | 64        | 34.41%  |
| 6      | 7         | 3.76%   |
| 8      | 2         | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 186       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 166       | 89.25%  |
| 1      | 20        | 10.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 184       | 98.4%   |
| Unknown        | 2         | 1.07%   |
| 32-bit         | 1         | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 18.85%  |
| 0x206a7    | 15        | 7.85%   |
| 0x806c1    | 13        | 6.81%   |
| 0x406e3    | 13        | 6.81%   |
| 0x806ec    | 12        | 6.28%   |
| 0x306d4    | 12        | 6.28%   |
| 0x806e9    | 11        | 5.76%   |
| 0x306a9    | 11        | 5.76%   |
| 0x806ea    | 10        | 5.24%   |
| 0x40651    | 9         | 4.71%   |
| 0x20655    | 9         | 4.71%   |
| 0x306c3    | 6         | 3.14%   |
| 0x706e5    | 5         | 2.62%   |
| 0x1067a    | 4         | 2.09%   |
| 0x906ea    | 3         | 1.57%   |
| 0xa0652    | 2         | 1.05%   |
| 0x506e3    | 2         | 1.05%   |
| 0x30678    | 2         | 1.05%   |
| 0x10676    | 2         | 1.05%   |
| 0xa0660    | 1         | 0.52%   |
| 0x906e9    | 1         | 0.52%   |
| 0x806eb    | 1         | 0.52%   |
| 0x706a1    | 1         | 0.52%   |
| 0x6fd      | 1         | 0.52%   |
| 0x406c4    | 1         | 0.52%   |
| 0x20652    | 1         | 0.52%   |
| 0x106e5    | 1         | 0.52%   |
| 0x08608103 | 1         | 0.52%   |
| 0x08600106 | 1         | 0.52%   |
| 0x08600104 | 1         | 0.52%   |
| 0x0700010f | 1         | 0.52%   |
| 0x0600611a | 1         | 0.52%   |
| 0x05000119 | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 46        | 24.73%  |
| Haswell       | 20        | 10.75%  |
| SandyBridge   | 18        | 9.68%   |
| Skylake       | 17        | 9.14%   |
| Broadwell     | 16        | 8.6%    |
| TigerLake     | 15        | 8.06%   |
| IvyBridge     | 15        | 8.06%   |
| Westmere      | 11        | 5.91%   |
| Penryn        | 7         | 3.76%   |
| IceLake       | 5         | 2.69%   |
| Silvermont    | 3         | 1.61%   |
| CometLake     | 3         | 1.61%   |
| Zen 2         | 2         | 1.08%   |
| P6            | 1         | 0.54%   |
| Nehalem       | 1         | 0.54%   |
| Jaguar        | 1         | 0.54%   |
| Goldmont plus | 1         | 0.54%   |
| Excavator     | 1         | 0.54%   |
| Core          | 1         | 0.54%   |
| Bobcat        | 1         | 0.54%   |
| Unknown       | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 169       | 72.84%  |
| Nvidia | 34        | 14.66%  |
| AMD    | 29        | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 17        | 7.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 15        | 6.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 14        | 5.98%   |
| Intel HD Graphics 5500                                                                | 14        | 5.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 14        | 5.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 13        | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 13        | 5.56%   |
| Intel UHD Graphics 620                                                                | 12        | 5.13%   |
| Intel HD Graphics 620                                                                 | 8         | 3.42%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 3.42%   |
| Intel Core Processor Integrated Graphics Controller                                   | 7         | 2.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 2.99%   |
| Nvidia GP108M [GeForce MX230]                                                         | 4         | 1.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 1.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 1.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 1.28%   |
| Intel HD Graphics 615                                                                 | 3         | 1.28%   |
| Intel HD Graphics 530                                                                 | 3         | 1.28%   |
| Nvidia TU117M [GeForce MX450]                                                         | 2         | 0.85%   |
| Nvidia GT218M [NVS 3100M]                                                             | 2         | 0.85%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.85%   |
| Nvidia GF119M [NVS 4200M]                                                             | 2         | 0.85%   |
| Intel HD Graphics 5300                                                                | 2         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 2         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 0.85%   |
| AMD Topaz PRO [Radeon R5 M255]                                                        | 2         | 0.85%   |
| AMD Renoir                                                                            | 2         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.43%   |
| Nvidia GT218M [GeForce G 105M]                                                        | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX330]                                                         | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 0.43%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.43%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 0.43%   |
| Nvidia GM108M [GeForce MX110]                                                         | 1         | 0.43%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 124       | 66.67%  |
| Intel + Nvidia | 27        | 14.52%  |
| Intel + AMD    | 18        | 9.68%   |
| 1 x AMD        | 10        | 5.38%   |
| 1 x Nvidia     | 6         | 3.23%   |
| AMD + Nvidia   | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 168       | 90.32%  |
| Proprietary | 17        | 9.14%   |
| Unknown     | 1         | 0.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 136       | 72.34%  |
| 1.01-2.0   | 26        | 13.83%  |
| 0.01-0.5   | 11        | 5.85%   |
| 3.01-4.0   | 7         | 3.72%   |
| 0.51-1.0   | 7         | 3.72%   |
| 5.01-6.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 47        | 23.74%  |
| Chimei Innolux          | 35        | 17.68%  |
| AU Optronics            | 34        | 17.17%  |
| BOE                     | 27        | 13.64%  |
| Samsung Electronics     | 16        | 8.08%   |
| Dell                    | 9         | 4.55%   |
| Chi Mei Optoelectronics | 5         | 2.53%   |
| Hewlett-Packard         | 3         | 1.52%   |
| Apple                   | 3         | 1.52%   |
| Sony                    | 2         | 1.01%   |
| Sharp                   | 2         | 1.01%   |
| LGD                     | 2         | 1.01%   |
| LG Philips              | 2         | 1.01%   |
| Lenovo                  | 2         | 1.01%   |
| KDC                     | 2         | 1.01%   |
| Goldstar                | 2         | 1.01%   |
| PANDA                   | 1         | 0.51%   |
| LPL                     | 1         | 0.51%   |
| InfoVision              | 1         | 0.51%   |
| BenQ                    | 1         | 0.51%   |
| Acer                    | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 3.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 2.53%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 4         | 2.02%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 4         | 2.02%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 3         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.52%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 3         | 1.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.01%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 2         | 1.01%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch  | 2         | 1.01%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 1.01%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 1.01%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.01%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 2         | 1.01%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.01%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2         | 1.01%   |
| Dell P2217H DELA0D9 1920x1080 476x267mm 21.5-inch                     | 2         | 1.01%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                     | 2         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 1.01%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 2         | 1.01%   |
| Chimei Innolux LCD Monitor CMN1332 1366x768 293x165mm 13.2-inch       | 2         | 1.01%   |
| BOE LCD Monitor BOE08C6 1920x1080 344x194mm 15.5-inch                 | 2         | 1.01%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                 | 2         | 1.01%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 1.01%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.01%   |
| AU Optronics LCD Monitor AUO5024 1280x800 286x178mm 13.3-inch         | 2         | 1.01%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 1.01%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 2         | 1.01%   |
| Sony TV SNYAC03 1360x768                                              | 1         | 0.51%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.51%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch               | 1         | 0.51%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.51%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 0.51%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 80        | 42.11%  |
| 1366x768 (WXGA)    | 76        | 40%     |
| 1600x900 (HD+)     | 10        | 5.26%   |
| 1280x800 (WXGA)    | 6         | 3.16%   |
| 3840x2160 (4K)     | 4         | 2.11%   |
| 1680x1050 (WSXGA+) | 4         | 2.11%   |
| 1440x900 (WXGA+)   | 3         | 1.58%   |
| 3440x1440          | 1         | 0.53%   |
| 2880x1800          | 1         | 0.53%   |
| 2560x1600          | 1         | 0.53%   |
| 1920x1200 (WUXGA)  | 1         | 0.53%   |
| 1360x768           | 1         | 0.53%   |
| 1280x1024 (SXGA)   | 1         | 0.53%   |
| 1024x768 (XGA)     | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 89        | 45.41%  |
| 14      | 37        | 18.88%  |
| 13      | 28        | 14.29%  |
| 17      | 9         | 4.59%   |
| 12      | 7         | 3.57%   |
| 24      | 5         | 2.55%   |
| 21      | 4         | 2.04%   |
| 11      | 4         | 2.04%   |
| 23      | 3         | 1.53%   |
| Unknown | 3         | 1.53%   |
| 22      | 2         | 1.02%   |
| 72      | 1         | 0.51%   |
| 40      | 1         | 0.51%   |
| 31      | 1         | 0.51%   |
| 20      | 1         | 0.51%   |
| 18      | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 137       | 70.62%  |
| 201-300     | 26        | 13.4%   |
| 351-400     | 10        | 5.15%   |
| 401-500     | 8         | 4.12%   |
| 501-600     | 7         | 3.61%   |
| Unknown     | 3         | 1.55%   |
| 801-900     | 1         | 0.52%   |
| 601-700     | 1         | 0.52%   |
| 1501-2000   | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 162       | 88.52%  |
| 16/10   | 15        | 8.2%    |
| Unknown | 3         | 1.64%   |
| 5/4     | 1         | 0.55%   |
| 4/3     | 1         | 0.55%   |
| 3/2     | 1         | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 88        | 45.13%  |
| 81-90          | 51        | 26.15%  |
| 71-80          | 12        | 6.15%   |
| 201-250        | 12        | 6.15%   |
| 61-70          | 7         | 3.59%   |
| 121-130        | 6         | 3.08%   |
| 51-60          | 4         | 2.05%   |
| 91-100         | 3         | 1.54%   |
| Unknown        | 3         | 1.54%   |
| 151-200        | 2         | 1.03%   |
| 141-150        | 2         | 1.03%   |
| 131-140        | 2         | 1.03%   |
| More than 1000 | 1         | 0.51%   |
| 351-500        | 1         | 0.51%   |
| 501-1000       | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 88        | 45.6%   |
| 101-120       | 71        | 36.79%  |
| 51-100        | 20        | 10.36%  |
| 161-240       | 6         | 3.11%   |
| More than 240 | 4         | 2.07%   |
| Unknown       | 3         | 1.55%   |
| 1-50          | 1         | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 168       | 89.84%  |
| 2     | 17        | 9.09%   |
| 3     | 1         | 0.53%   |
| 0     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 135       | 45.61%  |
| Realtek Semiconductor    | 95        | 32.09%  |
| Qualcomm Atheros         | 21        | 7.09%   |
| Broadcom                 | 16        | 5.41%   |
| Broadcom Limited         | 7         | 2.36%   |
| MediaTek                 | 4         | 1.35%   |
| Hewlett-Packard          | 4         | 1.35%   |
| Ralink                   | 3         | 1.01%   |
| Sierra Wireless          | 2         | 0.68%   |
| Dell                     | 2         | 0.68%   |
| Xiaomi                   | 1         | 0.34%   |
| Qualcomm                 | 1         | 0.34%   |
| OPPO Electronics         | 1         | 0.34%   |
| Marvell Technology Group | 1         | 0.34%   |
| Huawei Technologies      | 1         | 0.34%   |
| D-Link                   | 1         | 0.34%   |
| ASIX Electronics         | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 18.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 4.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 4.18%   |
| Intel Wireless 7265                                               | 13        | 3.39%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 3.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 3.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 3.13%   |
| Intel Wireless 3165                                               | 11        | 2.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.35%   |
| Intel Wireless 8260                                               | 8         | 2.09%   |
| Intel Wireless 7260                                               | 8         | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.83%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.83%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.31%   |
| Intel Ultimate N WiFi Link 5300                                   | 5         | 1.31%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.31%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.31%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.31%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 1.31%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.31%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.78%   |
| Intel Wireless 3160                                               | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.52%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.52%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 2         | 0.52%   |
| Intel Wireless-AC 9260                                            | 2         | 0.52%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 126       | 64.62%  |
| Realtek Semiconductor | 20        | 10.26%  |
| Qualcomm Atheros      | 19        | 9.74%   |
| Broadcom              | 15        | 7.69%   |
| Broadcom Limited      | 4         | 2.05%   |
| Ralink                | 3         | 1.54%   |
| Sierra Wireless       | 2         | 1.03%   |
| Hewlett-Packard       | 2         | 1.03%   |
| Dell                  | 2         | 1.03%   |
| MediaTek              | 1         | 0.51%   |
| D-Link                | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                        | 13        | 6.6%    |
| Intel Wi-Fi 6 AX201                                        | 13        | 6.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 13        | 6.6%    |
| Intel Wireless 3165                                        | 11        | 5.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 11        | 5.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 9         | 4.57%   |
| Intel Wireless 8260                                        | 8         | 4.06%   |
| Intel Wireless 7260                                        | 8         | 4.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 7         | 3.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 5         | 2.54%   |
| Intel Ultimate N WiFi Link 5300                            | 5         | 2.54%   |
| Intel Centrino Advanced-N 6235                             | 5         | 2.54%   |
| Intel Centrino Advanced-N 6200                             | 5         | 2.54%   |
| Intel Wireless 8265 / 8275                                 | 4         | 2.03%   |
| Intel Centrino Ultimate-N 6300                             | 4         | 2.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 4         | 2.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 3         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 3         | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 3         | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 1.52%   |
| Intel Wireless 3160                                        | 3         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                              | 3         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 1.02%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 2         | 1.02%   |
| Intel Wireless-AC 9260                                     | 2         | 1.02%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 2         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 2         | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 1.02%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]       | 2         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 1.02%   |
| HP lt4112 Gobi 4G Module Network Device                    | 2         | 1.02%   |
| Dell Hub of E-Port Replicator                              | 2         | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 2         | 1.02%   |
| Broadcom BCM43224 802.11a/b/g/n                            | 2         | 1.02%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 0.51%   |
| Sierra Wireless EM7305                                     | 1         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 91        | 50%     |
| Intel                    | 74        | 40.66%  |
| MediaTek                 | 3         | 1.65%   |
| Broadcom Limited         | 3         | 1.65%   |
| Qualcomm Atheros         | 2         | 1.1%    |
| Broadcom                 | 2         | 1.1%    |
| Xiaomi                   | 1         | 0.55%   |
| Qualcomm                 | 1         | 0.55%   |
| OPPO Electronics         | 1         | 0.55%   |
| Marvell Technology Group | 1         | 0.55%   |
| Huawei Technologies      | 1         | 0.55%   |
| Hewlett-Packard          | 1         | 0.55%   |
| ASIX Electronics         | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 70        | 37.84%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18        | 9.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 16        | 8.65%   |
| Intel Ethernet Connection (3) I218-LM                                          | 12        | 6.49%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 3.78%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 3.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.7%    |
| Intel Ethernet Connection I219-LM                                              | 5         | 2.7%    |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.7%    |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.62%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 1.62%   |
| MediaTek TECNO Pouvoir 3 Air                                                   | 2         | 1.08%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.08%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 1.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.54%   |
| Qualcomm Mobile Router                                                         | 1         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.54%   |
| OPPO RMX2180                                                                   | 1         | 0.54%   |
| MediaTek moto e(7) power                                                       | 1         | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.54%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.54%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.54%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.54%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.54%   |
| Huawei E353/E3131                                                              | 1         | 0.54%   |
| HP lt4211 Gobi 4G Module                                                       | 1         | 0.54%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.54%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.54%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 185       | 51.39%  |
| Ethernet | 174       | 48.33%  |
| Modem    | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 167       | 88.83%  |
| Ethernet | 21        | 11.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 167       | 89.3%   |
| 1     | 16        | 8.56%   |
| 0     | 2         | 1.07%   |
| 4     | 1         | 0.53%   |
| 3     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 178       | 95.7%   |
| Yes  | 8         | 4.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 62.04%  |
| Qualcomm Atheros Communications | 13        | 9.49%   |
| Realtek Semiconductor           | 12        | 8.76%   |
| Broadcom                        | 11        | 8.03%   |
| Dell                            | 4         | 2.92%   |
| Ralink                          | 3         | 2.19%   |
| Foxconn / Hon Hai               | 3         | 2.19%   |
| IMC Networks                    | 2         | 1.46%   |
| Hewlett-Packard                 | 2         | 1.46%   |
| Lite-On Technology              | 1         | 0.73%   |
| Apple                           | 1         | 0.73%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 45        | 32.85%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 11.68%  |
| Intel AX201 Bluetooth                                                               | 16        | 11.68%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 5.84%   |
| Realtek Bluetooth Radio                                                             | 6         | 4.38%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.92%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.92%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 2.92%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.19%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1.46%   |
| Intel AX200 Bluetooth                                                               | 2         | 1.46%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.46%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.73%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.73%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.73%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.73%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.73%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.73%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.73%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.73%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.73%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.73%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.73%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.73%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.73%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.73%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.73%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.73%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.73%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 179       | 85.65%  |
| Nvidia                 | 13        | 6.22%   |
| AMD                    | 10        | 4.78%   |
| Logitech               | 2         | 0.96%   |
| Generalplus Technology | 2         | 0.96%   |
| Realtek Semiconductor  | 1         | 0.48%   |
| OPPO Electronics       | 1         | 0.48%   |
| Apple                  | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 38        | 15.14%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 6.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 16        | 6.37%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 6.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 6.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 15        | 5.98%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 5.98%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 5.18%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 5.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 4.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 2.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 2.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.2%    |
| Nvidia High Definition Audio Controller                                    | 3         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.2%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.8%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.8%    |
| Logitech Headset H340                                                      | 2         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.8%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.8%    |
| Realtek Semiconductor USB Audio                                            | 1         | 0.4%    |
| OPPO Electronics DN2103                                                    | 1         | 0.4%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.4%    |
| Intel CM238 HD Audio Controller                                            | 1         | 0.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.4%    |
| Intel Audio device                                                         | 1         | 0.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.4%    |
| Generalplus Technology USB Microphone                                      | 1         | 0.4%    |
| Generalplus Technology USB Audio Device                                    | 1         | 0.4%    |
| Apple Audio Device                                                         | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 30.19%  |
| SK hynix            | 29        | 27.36%  |
| Micron Technology   | 12        | 11.32%  |
| A-DATA Technology   | 8         | 7.55%   |
| Transcend           | 5         | 4.72%   |
| Team                | 3         | 2.83%   |
| Crucial             | 3         | 2.83%   |
| Unknown             | 2         | 1.89%   |
| Spectek             | 2         | 1.89%   |
| Lexar               | 2         | 1.89%   |
| Elpida              | 2         | 1.89%   |
| Unknown (768A)      | 1         | 0.94%   |
| TwinMOS             | 1         | 0.94%   |
| Nanya Technology    | 1         | 0.94%   |
| Kingston            | 1         | 0.94%   |
| Hikvision           | 1         | 0.94%   |
| Axiom               | 1         | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s            | 5         | 4.39%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s     | 3         | 2.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 2.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 2.63%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 3         | 2.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 2.63%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s           | 2         | 1.75%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 1.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 1.75%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s            | 2         | 1.75%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s            | 2         | 1.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 1.75%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s     | 2         | 1.75%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.75%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s      | 2         | 1.75%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 2         | 1.75%   |
| Lexar RAM LD4AS016G-H2666G 16384MB SODIMM DDR4 2667MT/s   | 2         | 1.75%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s               | 1         | 0.88%   |
| Unknown RAM DDR3 1600 8G 8GB SODIMM DDR3 1333MT/s         | 1         | 0.88%   |
| Unknown (768A) RAM Module 16384MB SODIMM DDR4 2667MT/s    | 1         | 0.88%   |
| TwinMOS RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 3200MT/s  | 1         | 0.88%   |
| Transcend RAM Module 8GB SODIMM DDR4 3200MT/s             | 1         | 0.88%   |
| Transcend RAM Module 8192MB SODIMM DDR4 3200MT/s          | 1         | 0.88%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2400MT/s          | 1         | 0.88%   |
| Transcend RAM Module 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.88%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s     | 1         | 0.88%   |
| Spectek RAM Module 8GB Row Of Chips LPDDR3 1600MT/s       | 1         | 0.88%   |
| Spectek RAM Module 8192MB Row Of Chips LPDDR3 1600MT/s    | 1         | 0.88%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 0.88%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.88%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s           | 1         | 0.88%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s           | 1         | 0.88%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s             | 1         | 0.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 0.88%   |
| SK hynix RAM HMT451B6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s    | 1         | 0.88%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s    | 1         | 0.88%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s    | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 48        | 57.14%  |
| DDR3   | 30        | 35.71%  |
| LPDDR3 | 3         | 3.57%   |
| LPDDR4 | 2         | 2.38%   |
| DDR    | 1         | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 92.77%  |
| Row Of Chips | 5         | 6.02%   |
| DIMM         | 1         | 1.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 36        | 39.13%  |
| 4096  | 27        | 29.35%  |
| 16384 | 19        | 20.65%  |
| 2048  | 7         | 7.61%   |
| 32768 | 3         | 3.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 26        | 27.37%  |
| 1600  | 26        | 27.37%  |
| 3200  | 14        | 14.74%  |
| 2400  | 8         | 8.42%   |
| 2133  | 7         | 7.37%   |
| 1334  | 7         | 7.37%   |
| 1333  | 3         | 3.16%   |
| 8400  | 1         | 1.05%   |
| 4267  | 1         | 1.05%   |
| 1067  | 1         | 1.05%   |
| 1066  | 1         | 1.05%   |

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
| Chicony Electronics                    | 49        | 28.99%  |
| Microdia                               | 23        | 13.61%  |
| Sunplus Innovation Technology          | 16        | 9.47%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 8.28%   |
| Realtek Semiconductor                  | 11        | 6.51%   |
| Lite-On Technology                     | 11        | 6.51%   |
| Suyin                                  | 7         | 4.14%   |
| Acer                                   | 6         | 3.55%   |
| Ricoh                                  | 5         | 2.96%   |
| Quanta                                 | 5         | 2.96%   |
| IMC Networks                           | 5         | 2.96%   |
| Syntek                                 | 4         | 2.37%   |
| Silicon Motion                         | 3         | 1.78%   |
| Luxvisions Innotech Limited            | 3         | 1.78%   |
| Apple                                  | 2         | 1.18%   |
| Primax Electronics                     | 1         | 0.59%   |
| Pixart Imaging                         | 1         | 0.59%   |
| Logitech                               | 1         | 0.59%   |
| Lenovo                                 | 1         | 0.59%   |
| DigiTech                               | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 11        | 6.47%   |
| Chicony HP HD Camera                                                       | 10        | 5.88%   |
| Chicony Integrated Camera                                                  | 9         | 5.29%   |
| Sunplus Integrated_Webcam_HD                                               | 8         | 4.71%   |
| Lite-On HP HD Webcam                                                       | 7         | 4.12%   |
| Microdia Integrated Webcam                                                 | 4         | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 2.35%   |
| Syntek Integrated Camera                                                   | 3         | 1.76%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.76%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 1.76%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.76%   |
| Realtek Integrated Webcam                                                  | 3         | 1.76%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.76%   |
| Chicony USB 2.0Camera                                                      | 3         | 1.76%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 1.76%   |
| Chicony HP TrueVision HD Camera                                            | 3         | 1.76%   |
| Chicony EasyCamera                                                         | 3         | 1.76%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.76%   |
| Acer Integrated Camera                                                     | 3         | 1.76%   |
| Suyin HP Truevision HD                                                     | 2         | 1.18%   |
| Sunplus Laptop Integrated Webcam HD                                        | 2         | 1.18%   |
| Sunplus HP Universal Camera                                                | 2         | 1.18%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 1.18%   |
| Realtek MTD camera                                                         | 2         | 1.18%   |
| Quanta HP HD Camera                                                        | 2         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 1.18%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 1.18%   |
| Lite-On Integrated Camera                                                  | 2         | 1.18%   |
| Lite-On HP HD Camera                                                       | 2         | 1.18%   |
| IMC Networks Integrated Camera                                             | 2         | 1.18%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.18%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 1.18%   |
| Chicony HP Truevision HD                                                   | 2         | 1.18%   |
| Chicony HP HD Webcam [Fixed]                                               | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 2         | 1.18%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 2         | 1.18%   |
| Syntek USB 2.0 PC Cam                                                      | 1         | 0.59%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 1         | 0.59%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 41        | 69.49%  |
| Synaptics                  | 9         | 15.25%  |
| AuthenTec                  | 4         | 6.78%   |
| Shenzhen Goodix Technology | 3         | 5.08%   |
| Upek                       | 2         | 3.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 30.51%  |
| Validity Sensors VFS491                                                    | 9         | 15.25%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 11.86%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 6.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.08%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.08%   |
| AuthenTec AES2810                                                          | 3         | 5.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.69%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.69%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.69%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.69%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.69%   |
| Unknown                                                                    | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 21        | 95.45%  |
| O2 Micro | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 45.45%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 36.36%  |
| Broadcom 5880                                                                | 2         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.55%   |
| Broadcom 58200                                                               | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 94        | 50.27%  |
| 1     | 82        | 43.85%  |
| 2     | 10        | 5.35%   |
| 4     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 55.24%  |
| Chipcard                 | 22        | 20.95%  |
| Storage                  | 5         | 4.76%   |
| Graphics card            | 5         | 4.76%   |
| Net/wireless             | 4         | 3.81%   |
| Bluetooth                | 4         | 3.81%   |
| Sound                    | 2         | 1.9%    |
| Network                  | 1         | 0.95%   |
| Net/ethernet             | 1         | 0.95%   |
| Multimedia controller    | 1         | 0.95%   |
| Communication controller | 1         | 0.95%   |
| Camera                   | 1         | 0.95%   |


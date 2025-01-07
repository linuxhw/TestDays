Linux in Ukraine - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ukraine.

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

Total: 2856

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | V15 G2 IJL 82QY             | [cd9b055146](https://linux-hardware.org/?probe=cd9b055146) | Dec 31, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [8e64cf40ca](https://linux-hardware.org/?probe=8e64cf40ca) | Dec 30, 2024 |
| Samsung       | SR58P                       | [70e6a978b7](https://linux-hardware.org/?probe=70e6a978b7) | Dec 23, 2024 |
| TECNO Mobi... | MEGABOOK T15DA              | [eb2b432d23](https://linux-hardware.org/?probe=eb2b432d23) | Dec 22, 2024 |
| HP            | 250 G4                      | [0d0786ce85](https://linux-hardware.org/?probe=0d0786ce85) | Dec 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [f2663b158a](https://linux-hardware.org/?probe=f2663b158a) | Dec 09, 2024 |
| Lenovo        | G570 20079                  | [d7ca5ffb0b](https://linux-hardware.org/?probe=d7ca5ffb0b) | Dec 06, 2024 |
| Apple         | MacBookAir3,1               | [8517a48127](https://linux-hardware.org/?probe=8517a48127) | Dec 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e2e36578a2](https://linux-hardware.org/?probe=e2e36578a2) | Nov 22, 2024 |
| Lenovo        | G500 20236                  | [7dcaf25e66](https://linux-hardware.org/?probe=7dcaf25e66) | Nov 17, 2024 |
| Timi          | A35S                        | [009b192f2b](https://linux-hardware.org/?probe=009b192f2b) | Nov 16, 2024 |
| Acer          | Aspire xxxx                 | [33a1540b7a](https://linux-hardware.org/?probe=33a1540b7a) | Nov 11, 2024 |
| HP            | ProBook 450 G5              | [022c2f84fc](https://linux-hardware.org/?probe=022c2f84fc) | Nov 10, 2024 |
| Acer          | Swift SF114-34              | [691b0eb5d2](https://linux-hardware.org/?probe=691b0eb5d2) | Nov 07, 2024 |
| Acer          | Aspire A515-57              | [9eb047fb07](https://linux-hardware.org/?probe=9eb047fb07) | Nov 03, 2024 |
| Google        | Pantheon                    | [41f0a72dc6](https://linux-hardware.org/?probe=41f0a72dc6) | Nov 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | [98eb489724](https://linux-hardware.org/?probe=98eb489724) | Oct 31, 2024 |
| Timi          | TM1707                      | [6f1f7e4e34](https://linux-hardware.org/?probe=6f1f7e4e34) | Oct 30, 2024 |
| ASUSTek       | U31SD                       | [fe2a70f7fa](https://linux-hardware.org/?probe=fe2a70f7fa) | Oct 29, 2024 |
| HP            | Pavilion g6                 | [3033d9b319](https://linux-hardware.org/?probe=3033d9b319) | Oct 28, 2024 |
| Samsung       | R40P/R41P                   | [7055d764e4](https://linux-hardware.org/?probe=7055d764e4) | Oct 28, 2024 |
| ASUSTek       | U31SD                       | [2c5c09f1df](https://linux-hardware.org/?probe=2c5c09f1df) | Oct 25, 2024 |
| Acer          | Aspire V5-551G              | [9193076b94](https://linux-hardware.org/?probe=9193076b94) | Oct 22, 2024 |
| Acer          | Aspire V5-551G              | [6f186ef3f1](https://linux-hardware.org/?probe=6f186ef3f1) | Oct 22, 2024 |
| ASUSTek       | K55VD                       | [55353ea5e1](https://linux-hardware.org/?probe=55353ea5e1) | Oct 21, 2024 |
| Razer         | Blade 16 - RZ09-0483        | [87977c5666](https://linux-hardware.org/?probe=87977c5666) | Oct 21, 2024 |
| Gigabyte      | G5 GE                       | [26c1aed963](https://linux-hardware.org/?probe=26c1aed963) | Oct 17, 2024 |
| HP            | Laptop 15s-eq2xxx           | [d0ac53c68a](https://linux-hardware.org/?probe=d0ac53c68a) | Oct 16, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ab67f0f4c4](https://linux-hardware.org/?probe=ab67f0f4c4) | Oct 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8dfb3bab34](https://linux-hardware.org/?probe=8dfb3bab34) | Oct 07, 2024 |
| Lenovo        | G580 20150                  | [21162c92b4](https://linux-hardware.org/?probe=21162c92b4) | Oct 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [23f6034531](https://linux-hardware.org/?probe=23f6034531) | Oct 04, 2024 |
| Valve         | Galileo                     | [a8bc5582e6](https://linux-hardware.org/?probe=a8bc5582e6) | Oct 03, 2024 |
| HP            | Pavilion g6                 | [810492a8e1](https://linux-hardware.org/?probe=810492a8e1) | Sep 30, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [9dccdf1596](https://linux-hardware.org/?probe=9dccdf1596) | Sep 30, 2024 |
| Dell          | Inspiron 3542               | [1d55438162](https://linux-hardware.org/?probe=1d55438162) | Sep 29, 2024 |
| HP            | 655                         | [ce046ad965](https://linux-hardware.org/?probe=ce046ad965) | Sep 26, 2024 |
| Valve         | Galileo                     | [8ab5e110e2](https://linux-hardware.org/?probe=8ab5e110e2) | Sep 24, 2024 |
| Dell          | G3 3579                     | [1786c1ecdd](https://linux-hardware.org/?probe=1786c1ecdd) | Sep 15, 2024 |
| HP            | EliteBook 840 G1            | [f8dd4f91b9](https://linux-hardware.org/?probe=f8dd4f91b9) | Sep 12, 2024 |
| Valve         | Jupiter                     | [96d9e41b2c](https://linux-hardware.org/?probe=96d9e41b2c) | Sep 06, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | [0cf32a7c28](https://linux-hardware.org/?probe=0cf32a7c28) | Sep 03, 2024 |
| HP            | EliteBook 850 G1            | [c5f7728016](https://linux-hardware.org/?probe=c5f7728016) | Sep 01, 2024 |
| HP            | EliteBook 850 G1            | [ee85acc05d](https://linux-hardware.org/?probe=ee85acc05d) | Sep 01, 2024 |
| HP            | Laptop 15-da0xxx            | [19aa76bbf1](https://linux-hardware.org/?probe=19aa76bbf1) | Aug 30, 2024 |
| Gigabyte      | G5 GD                       | [2840fa5a43](https://linux-hardware.org/?probe=2840fa5a43) | Aug 27, 2024 |
| Dell          | Vostro 5370                 | [ab603bbc81](https://linux-hardware.org/?probe=ab603bbc81) | Aug 24, 2024 |
| Dell          | Vostro 5370                 | [233641b58a](https://linux-hardware.org/?probe=233641b58a) | Aug 24, 2024 |
| Dell          | Precision 7530              | [67e1c5e840](https://linux-hardware.org/?probe=67e1c5e840) | Aug 24, 2024 |
| Gigabyte      | AERO 16 XE4                 | [491d0f5415](https://linux-hardware.org/?probe=491d0f5415) | Aug 22, 2024 |
| Dell          | Precision 7530              | [6dbff427a7](https://linux-hardware.org/?probe=6dbff427a7) | Aug 21, 2024 |
| Dell          | Precision 7530              | [f24cdeec73](https://linux-hardware.org/?probe=f24cdeec73) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [252054bbbb](https://linux-hardware.org/?probe=252054bbbb) | Aug 14, 2024 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [eaf1b08e39](https://linux-hardware.org/?probe=eaf1b08e39) | Aug 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [1647e0bf63](https://linux-hardware.org/?probe=1647e0bf63) | Aug 14, 2024 |
| Acer          | Aspire E1-530G              | [30fac12d0e](https://linux-hardware.org/?probe=30fac12d0e) | Aug 13, 2024 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [af25c599ca](https://linux-hardware.org/?probe=af25c599ca) | Aug 12, 2024 |
| Lenovo        | ThinkPad E595 20NF001HRT    | [ed43fa321d](https://linux-hardware.org/?probe=ed43fa321d) | Aug 11, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | [47a5c4679c](https://linux-hardware.org/?probe=47a5c4679c) | Aug 08, 2024 |
| Lenovo        | S10-3                       | [64d128d74c](https://linux-hardware.org/?probe=64d128d74c) | Aug 04, 2024 |
| HP            | ProBook 450 G3              | [e0891897e9](https://linux-hardware.org/?probe=e0891897e9) | Aug 01, 2024 |
| Lenovo        | S10-3                       | [c25cc431f8](https://linux-hardware.org/?probe=c25cc431f8) | Aug 01, 2024 |
| HONOR         | BMH-WDX9                    | [34156676c7](https://linux-hardware.org/?probe=34156676c7) | Jul 28, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [6959309c2f](https://linux-hardware.org/?probe=6959309c2f) | Jul 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [efd2967461](https://linux-hardware.org/?probe=efd2967461) | Jul 26, 2024 |
| HP            | Laptop 17-by0xxx            | [29acbbfa9a](https://linux-hardware.org/?probe=29acbbfa9a) | Jul 25, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [926de0d0c1](https://linux-hardware.org/?probe=926de0d0c1) | Jul 22, 2024 |
| Dell          | Latitude E4310              | [134a985afc](https://linux-hardware.org/?probe=134a985afc) | Jul 21, 2024 |
| Acer          | Aspire A315-58              | [2a5f95f23f](https://linux-hardware.org/?probe=2a5f95f23f) | Jul 20, 2024 |
| Apple         | MacBookAir4,2               | [9644df5e86](https://linux-hardware.org/?probe=9644df5e86) | Jul 19, 2024 |
| Fujitsu       | LIFEBOOK E734               | [f0cc03e825](https://linux-hardware.org/?probe=f0cc03e825) | Jul 15, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [77fc74f4e0](https://linux-hardware.org/?probe=77fc74f4e0) | Jun 29, 2024 |
| Acer          | Aspire A515-58P             | [40becc9aaa](https://linux-hardware.org/?probe=40becc9aaa) | Jun 29, 2024 |
| Acer          | Nitro AN17-51               | [f208c4063a](https://linux-hardware.org/?probe=f208c4063a) | Jun 26, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [c054b11de9](https://linux-hardware.org/?probe=c054b11de9) | Jun 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [e66c347a99](https://linux-hardware.org/?probe=e66c347a99) | Jun 21, 2024 |
| Lenovo        | IdeaPad Z580                | [3c9898faa1](https://linux-hardware.org/?probe=3c9898faa1) | Jun 20, 2024 |
| Lenovo        | IdeaPad Z580                | [50ac519b75](https://linux-hardware.org/?probe=50ac519b75) | Jun 20, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3d565cd28e](https://linux-hardware.org/?probe=3d565cd28e) | Jun 18, 2024 |
| HP            | ProBook 450 G7              | [e984cb8d82](https://linux-hardware.org/?probe=e984cb8d82) | Jun 18, 2024 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [d1053bfafb](https://linux-hardware.org/?probe=d1053bfafb) | Jun 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [12ee24bdf8](https://linux-hardware.org/?probe=12ee24bdf8) | Jun 14, 2024 |
| Acer          | Extensa 215-22              | [604d8cb84d](https://linux-hardware.org/?probe=604d8cb84d) | Jun 11, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | [b50b6a8837](https://linux-hardware.org/?probe=b50b6a8837) | Jun 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [91bb1074d9](https://linux-hardware.org/?probe=91bb1074d9) | Jun 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [4892cf872e](https://linux-hardware.org/?probe=4892cf872e) | Jun 09, 2024 |
| Dell          | Studio 1537                 | [9c73780c05](https://linux-hardware.org/?probe=9c73780c05) | Jun 07, 2024 |
| Valve         | Galileo                     | [c1cd10e2c9](https://linux-hardware.org/?probe=c1cd10e2c9) | Jun 05, 2024 |
| THUNDEROBO... | 911S                        | [bcc5c0d77c](https://linux-hardware.org/?probe=bcc5c0d77c) | May 29, 2024 |
| Fujitsu       | LIFEBOOK E734               | [74c8e530ad](https://linux-hardware.org/?probe=74c8e530ad) | May 22, 2024 |
| Fujitsu       | LIFEBOOK E734               | [de96d1e8d8](https://linux-hardware.org/?probe=de96d1e8d8) | May 22, 2024 |
| HP            | ProBook 450 G5              | [611c9b917e](https://linux-hardware.org/?probe=611c9b917e) | May 16, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20YE0... | [2dbc872484](https://linux-hardware.org/?probe=2dbc872484) | May 14, 2024 |
| Valve         | Jupiter                     | [23799f6a79](https://linux-hardware.org/?probe=23799f6a79) | May 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [29989717a9](https://linux-hardware.org/?probe=29989717a9) | May 09, 2024 |
| Apple         | MacBookPro11,1              | [5d23c7ed6f](https://linux-hardware.org/?probe=5d23c7ed6f) | May 08, 2024 |
| Dell          | XPS 15 9530                 | [5aee2550ce](https://linux-hardware.org/?probe=5aee2550ce) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [826e5c0fc6](https://linux-hardware.org/?probe=826e5c0fc6) | May 05, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [2cc53cfafd](https://linux-hardware.org/?probe=2cc53cfafd) | May 05, 2024 |
| Acer          | Aspire A315-42              | [bff5263ba8](https://linux-hardware.org/?probe=bff5263ba8) | Apr 07, 2024 |
| HP            | EliteBook 8440p             | [d4fbc831bb](https://linux-hardware.org/?probe=d4fbc831bb) | Apr 07, 2024 |
| HP            | Stream 11 Pro G5            | [60dbf47721](https://linux-hardware.org/?probe=60dbf47721) | Apr 06, 2024 |
| ASUSTek       | K54C                        | [d43311570d](https://linux-hardware.org/?probe=d43311570d) | Apr 01, 2024 |
| HONOR         | BOHK-WAX9X                  | [90a8f20c20](https://linux-hardware.org/?probe=90a8f20c20) | Mar 28, 2024 |
| Acer          | Aspire E3-112               | [bba28f3708](https://linux-hardware.org/?probe=bba28f3708) | Mar 27, 2024 |
| Apple         | MacBook4,1                  | [a66fe7ad17](https://linux-hardware.org/?probe=a66fe7ad17) | Mar 22, 2024 |
| Apple         | MacBook4,1                  | [82eace2b3c](https://linux-hardware.org/?probe=82eace2b3c) | Mar 22, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [153f16ac8d](https://linux-hardware.org/?probe=153f16ac8d) | Mar 18, 2024 |
| DEXP          | C15-ICW300                  | [9965e88dba](https://linux-hardware.org/?probe=9965e88dba) | Mar 11, 2024 |
| DEXP          | C15-ICW300                  | [8d8494680f](https://linux-hardware.org/?probe=8d8494680f) | Mar 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [15f6244fa0](https://linux-hardware.org/?probe=15f6244fa0) | Mar 11, 2024 |
| HONOR         | BOD-WXX9                    | [a4942d27af](https://linux-hardware.org/?probe=a4942d27af) | Mar 09, 2024 |
| Acer          | Aspire A315-34              | [de7da2949d](https://linux-hardware.org/?probe=de7da2949d) | Mar 03, 2024 |
| Valve         | Jupiter                     | [a3062daa4e](https://linux-hardware.org/?probe=a3062daa4e) | Mar 01, 2024 |
| HP            | Pavilion dv6                | [ccc6fb70da](https://linux-hardware.org/?probe=ccc6fb70da) | Feb 25, 2024 |
| Maibenben     | MaiBook M                   | [7f6b3c0f92](https://linux-hardware.org/?probe=7f6b3c0f92) | Feb 13, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [f4930d0549](https://linux-hardware.org/?probe=f4930d0549) | Feb 09, 2024 |
| Valve         | Jupiter                     | [f3af706ee0](https://linux-hardware.org/?probe=f3af706ee0) | Jan 29, 2024 |
| Acer          | TravelMate P259-MG          | [0192eb7c53](https://linux-hardware.org/?probe=0192eb7c53) | Jan 28, 2024 |
| Acer          | Aspire A717-71G             | [b7fb65f8f0](https://linux-hardware.org/?probe=b7fb65f8f0) | Jan 24, 2024 |
| Valve         | Jupiter                     | [07ee2b0014](https://linux-hardware.org/?probe=07ee2b0014) | Jan 12, 2024 |
| HP            | EliteBook 8440p             | [889462ebed](https://linux-hardware.org/?probe=889462ebed) | Jan 10, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [0350f7e562](https://linux-hardware.org/?probe=0350f7e562) | Jan 05, 2024 |
| Chuwi         | HeroBook Pro                | [97c2ff9710](https://linux-hardware.org/?probe=97c2ff9710) | Jan 01, 2024 |
| HP            | ProBook 445 14 inch G9 N... | [d3e1c0dbdc](https://linux-hardware.org/?probe=d3e1c0dbdc) | Dec 25, 2023 |
| MSI           | EX610                       | [95fe9d0294](https://linux-hardware.org/?probe=95fe9d0294) | Dec 25, 2023 |
| Packard Be... | EasyNote TE11HC             | [2c88ade0b2](https://linux-hardware.org/?probe=2c88ade0b2) | Dec 23, 2023 |
| Acer          | Aspire E5-571G              | [c136ca6eff](https://linux-hardware.org/?probe=c136ca6eff) | Dec 11, 2023 |
| TECNO Mobi... | MEGABOOK T15DA              | [afe1407fd9](https://linux-hardware.org/?probe=afe1407fd9) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ac0fd4af39](https://linux-hardware.org/?probe=ac0fd4af39) | Dec 05, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [a8192548ea](https://linux-hardware.org/?probe=a8192548ea) | Dec 03, 2023 |
| MSI           | Vector GP66 12UGS           | [9598e79260](https://linux-hardware.org/?probe=9598e79260) | Dec 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [7d194a5396](https://linux-hardware.org/?probe=7d194a5396) | Dec 01, 2023 |
| HUAWEI        | RLEF-XX                     | [9b8fabda07](https://linux-hardware.org/?probe=9b8fabda07) | Nov 29, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| Acer          | Aspire A515-45G             | [d9f708d5f2](https://linux-hardware.org/?probe=d9f708d5f2) | Nov 26, 2023 |
| MSI           | Vector GP66 12UGS           | [0fd3c87878](https://linux-hardware.org/?probe=0fd3c87878) | Nov 24, 2023 |
| ASUSTek       | N750JV                      | [27e9669d13](https://linux-hardware.org/?probe=27e9669d13) | Nov 24, 2023 |
| Acer          | TravelMate P259-MG          | [9ab55a1799](https://linux-hardware.org/?probe=9ab55a1799) | Nov 23, 2023 |
| Acer          | TravelMate P259-MG          | [aea9b092e1](https://linux-hardware.org/?probe=aea9b092e1) | Nov 23, 2023 |
| Acer          | Aspire E1-532G              | [986077984e](https://linux-hardware.org/?probe=986077984e) | Nov 18, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [613acc55d8](https://linux-hardware.org/?probe=613acc55d8) | Nov 13, 2023 |
| Unknown       | Unknown                     | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [daab2f9dc6](https://linux-hardware.org/?probe=daab2f9dc6) | Nov 11, 2023 |
| HP            | ProBook 640 G1              | [63a4283226](https://linux-hardware.org/?probe=63a4283226) | Nov 10, 2023 |
| Dynabook      | PORTEGE X30L-K              | [161674ce4a](https://linux-hardware.org/?probe=161674ce4a) | Nov 10, 2023 |
| Acer          | TravelMate P259-MG          | [b9429814ad](https://linux-hardware.org/?probe=b9429814ad) | Nov 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ac8533d263](https://linux-hardware.org/?probe=ac8533d263) | Nov 06, 2023 |
| Lenovo        | IdeaPad 710S Plus-13ISK ... | [f143d09ba7](https://linux-hardware.org/?probe=f143d09ba7) | Nov 04, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [96bda876c8](https://linux-hardware.org/?probe=96bda876c8) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [3d7ad8a1d6](https://linux-hardware.org/?probe=3d7ad8a1d6) | Oct 26, 2023 |
| Dell          | Latitude E6220              | [afc941b941](https://linux-hardware.org/?probe=afc941b941) | Oct 25, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [e0a819cb8d](https://linux-hardware.org/?probe=e0a819cb8d) | Oct 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [47186b8e71](https://linux-hardware.org/?probe=47186b8e71) | Oct 24, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [817e0c8438](https://linux-hardware.org/?probe=817e0c8438) | Oct 23, 2023 |
| Acer          | Aspire V3-571G              | [5e50c3624b](https://linux-hardware.org/?probe=5e50c3624b) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fbf9250075](https://linux-hardware.org/?probe=fbf9250075) | Oct 15, 2023 |
| Acer          | TravelMate 5744Z            | [38f2a731a5](https://linux-hardware.org/?probe=38f2a731a5) | Oct 13, 2023 |
| Acer          | Aspire A515-43              | [2b5409e1b5](https://linux-hardware.org/?probe=2b5409e1b5) | Oct 11, 2023 |
| Acer          | Aspire A515-43              | [66b780f57f](https://linux-hardware.org/?probe=66b780f57f) | Oct 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [814f6c5c52](https://linux-hardware.org/?probe=814f6c5c52) | Oct 09, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [a9fb0ad7d5](https://linux-hardware.org/?probe=a9fb0ad7d5) | Oct 06, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| Valve         | Jupiter                     | [937f10463d](https://linux-hardware.org/?probe=937f10463d) | Sep 29, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [549941d843](https://linux-hardware.org/?probe=549941d843) | Sep 25, 2023 |
| Google        | Magpie                      | [3da6f69ed3](https://linux-hardware.org/?probe=3da6f69ed3) | Sep 24, 2023 |
| Lenovo        | G560 20042                  | [a8a67a12c7](https://linux-hardware.org/?probe=a8a67a12c7) | Sep 23, 2023 |
| ASUSTek       | X510UAR                     | [1253ebfcfb](https://linux-hardware.org/?probe=1253ebfcfb) | Sep 17, 2023 |
| HP            | Laptop 15-db0xxx            | [3cbd0bc118](https://linux-hardware.org/?probe=3cbd0bc118) | Sep 16, 2023 |
| Packard Be... | EasyNote TE11HC             | [7f6effbc07](https://linux-hardware.org/?probe=7f6effbc07) | Sep 16, 2023 |
| Packard Be... | EasyNote TE11HC             | [7b4955f7d2](https://linux-hardware.org/?probe=7b4955f7d2) | Sep 16, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Gateway       | NV55C                       | [1086491e2c](https://linux-hardware.org/?probe=1086491e2c) | Sep 12, 2023 |
| ASUSTek       | X555LN                      | [d5d9b73baa](https://linux-hardware.org/?probe=d5d9b73baa) | Sep 11, 2023 |
| ASUSTek       | X555LN                      | [3aef7779ec](https://linux-hardware.org/?probe=3aef7779ec) | Sep 11, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [bb0607322d](https://linux-hardware.org/?probe=bb0607322d) | Sep 09, 2023 |
| Lenovo        | V580c 20160                 | [87f8bad27d](https://linux-hardware.org/?probe=87f8bad27d) | Sep 07, 2023 |
| ASUSTek       | X541NC                      | [927ba04557](https://linux-hardware.org/?probe=927ba04557) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ceade9f24f](https://linux-hardware.org/?probe=ceade9f24f) | Sep 04, 2023 |
| Acer          | Nitro AN515-52              | [45e892a632](https://linux-hardware.org/?probe=45e892a632) | Sep 03, 2023 |
| Lenovo        | IdeaPad Slim 5 16IAH8 83... | [2cfbf5b20c](https://linux-hardware.org/?probe=2cfbf5b20c) | Sep 02, 2023 |
| Dell          | Inspiron 5520               | [0aac344d78](https://linux-hardware.org/?probe=0aac344d78) | Sep 01, 2023 |
| Acer          | TravelMate 5744Z            | [6a875dbee6](https://linux-hardware.org/?probe=6a875dbee6) | Sep 01, 2023 |
| Samsung       | R518                        | [1869c33e8e](https://linux-hardware.org/?probe=1869c33e8e) | Aug 31, 2023 |
| ASUSTek       | N76VZ                       | [096dcfdc21](https://linux-hardware.org/?probe=096dcfdc21) | Aug 27, 2023 |
| Dell          | Inspiron 5520               | [5b99637f66](https://linux-hardware.org/?probe=5b99637f66) | Aug 25, 2023 |
| MSI           | GS65 Stealth Thin 8RE       | [b53212efce](https://linux-hardware.org/?probe=b53212efce) | Aug 24, 2023 |
| Lenovo        | ThinkPad E490 20N8001BUS    | [85d80ec89f](https://linux-hardware.org/?probe=85d80ec89f) | Aug 22, 2023 |
| HP            | ProBook 650 G1              | [b176d8959a](https://linux-hardware.org/?probe=b176d8959a) | Aug 08, 2023 |
| Acer          | TravelMate 5744Z            | [19297331fd](https://linux-hardware.org/?probe=19297331fd) | Aug 05, 2023 |
| Lenovo        | G580 20150                  | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Acer          | Aspire E5-576G              | [eac04b4464](https://linux-hardware.org/?probe=eac04b4464) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [7a6a20b8ed](https://linux-hardware.org/?probe=7a6a20b8ed) | Jul 23, 2023 |
| Google        | Lillipup                    | [7f7ba76942](https://linux-hardware.org/?probe=7f7ba76942) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [1367b103ae](https://linux-hardware.org/?probe=1367b103ae) | Jul 09, 2023 |
| ASUSTek       | N55SL                       | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| HP            | Laptop 14s-fq0xxx           | [638a590e01](https://linux-hardware.org/?probe=638a590e01) | Jul 05, 2023 |
| Chuwi         | HeroBook Pro                | [d1abb5f348](https://linux-hardware.org/?probe=d1abb5f348) | Jul 02, 2023 |
| Chuwi         | HeroBook Pro                | [c0238ceb53](https://linux-hardware.org/?probe=c0238ceb53) | Jul 02, 2023 |
| Dell          | System XPS L321X            | [abf6b8b341](https://linux-hardware.org/?probe=abf6b8b341) | Jun 29, 2023 |
| MSI           | GE66 Dragonshield 10SF      | [42f6b46bb1](https://linux-hardware.org/?probe=42f6b46bb1) | Jun 28, 2023 |
| MSI           | GE66 Dragonshield 10SF      | [00fd5b9706](https://linux-hardware.org/?probe=00fd5b9706) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d7ca07df46](https://linux-hardware.org/?probe=d7ca07df46) | Jun 22, 2023 |
| Toshiba       | Satellite L45-B             | [85b5d49142](https://linux-hardware.org/?probe=85b5d49142) | Jun 13, 2023 |
| Samsung       | RV408/RV508                 | [4ec36cfa9e](https://linux-hardware.org/?probe=4ec36cfa9e) | Jun 13, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [fba7b6bdc0](https://linux-hardware.org/?probe=fba7b6bdc0) | Jun 12, 2023 |
| Valve         | Jupiter                     | [fab558feb4](https://linux-hardware.org/?probe=fab558feb4) | Jun 10, 2023 |
| Valve         | Jupiter                     | [06f5f2068f](https://linux-hardware.org/?probe=06f5f2068f) | Jun 09, 2023 |
| Acer          | Aspire V5-551G              | [7c55457a7e](https://linux-hardware.org/?probe=7c55457a7e) | Jun 06, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [7b5291c6f8](https://linux-hardware.org/?probe=7b5291c6f8) | Jun 02, 2023 |
| Acer          | TravelMate 5744Z            | [bde6d2f364](https://linux-hardware.org/?probe=bde6d2f364) | May 31, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| THUNDEROBO... | IGER F1                     | [d492356b33](https://linux-hardware.org/?probe=d492356b33) | May 25, 2023 |
| Dell          | Vostro 15-3568              | [d80a3cd0b7](https://linux-hardware.org/?probe=d80a3cd0b7) | May 17, 2023 |
| Dell          | Vostro 15-3568              | [b4a9463feb](https://linux-hardware.org/?probe=b4a9463feb) | May 17, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [d30d7d859b](https://linux-hardware.org/?probe=d30d7d859b) | May 11, 2023 |
| HUAWEI        | BOM-WXX9                    | [8f910a1997](https://linux-hardware.org/?probe=8f910a1997) | May 09, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| Apple         | MacBookAir3,2               | [e0f325b239](https://linux-hardware.org/?probe=e0f325b239) | May 01, 2023 |
| Lenovo        | G585 20137                  | [f0b4e5c5fd](https://linux-hardware.org/?probe=f0b4e5c5fd) | Apr 29, 2023 |
| Samsung       | R528/R728                   | [1e0b02f4c5](https://linux-hardware.org/?probe=1e0b02f4c5) | Apr 28, 2023 |
| HP            | Laptop 17-ak0xx             | [6eed1fda15](https://linux-hardware.org/?probe=6eed1fda15) | Apr 27, 2023 |
| Toshiba       | Satellite L45-B             | [6869e08d2d](https://linux-hardware.org/?probe=6869e08d2d) | Apr 18, 2023 |
| Dell          | Inspiron 5559               | [945c1a2fe3](https://linux-hardware.org/?probe=945c1a2fe3) | Apr 17, 2023 |
| Dell          | Inspiron 5559               | [a25bcc21e8](https://linux-hardware.org/?probe=a25bcc21e8) | Apr 17, 2023 |
| HP            | ProBook 450 G7              | [cccf1dadac](https://linux-hardware.org/?probe=cccf1dadac) | Apr 12, 2023 |
| HP            | 635                         | [416f1683f6](https://linux-hardware.org/?probe=416f1683f6) | Apr 12, 2023 |
| Timi          | TM1707                      | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [d9f6e45e3e](https://linux-hardware.org/?probe=d9f6e45e3e) | Apr 05, 2023 |
| ASUSTek       | N53SV                       | [5b2c0ea506](https://linux-hardware.org/?probe=5b2c0ea506) | Apr 02, 2023 |
| Valve         | Jupiter                     | [1f2e4d7cd8](https://linux-hardware.org/?probe=1f2e4d7cd8) | Mar 26, 2023 |
| HP            | ProBook 5330m               | [6844efa448](https://linux-hardware.org/?probe=6844efa448) | Mar 24, 2023 |
| Fujitsu       | LIFEBOOK E734               | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| HONOR         | BOD-WXX9                    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [613aec2276](https://linux-hardware.org/?probe=613aec2276) | Mar 17, 2023 |
| Fujitsu       | LIFEBOOK E734               | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| Acer          | Aspire M3-581TG             | [2f8939e9ed](https://linux-hardware.org/?probe=2f8939e9ed) | Mar 06, 2023 |
| Acer          | Swift SFX16-52G             | [fb45390054](https://linux-hardware.org/?probe=fb45390054) | Mar 05, 2023 |
| Acer          | Swift SFX16-52G             | [b86acec192](https://linux-hardware.org/?probe=b86acec192) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| MSI           | GF63 Thin 10SC              | [29fae9ef99](https://linux-hardware.org/?probe=29fae9ef99) | Mar 03, 2023 |
| MSI           | GF63 Thin 10SC              | [36078cfcb3](https://linux-hardware.org/?probe=36078cfcb3) | Mar 03, 2023 |
| MSI           | GF63 Thin 10SC              | [3603c7c3e9](https://linux-hardware.org/?probe=3603c7c3e9) | Mar 03, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [e5b411431c](https://linux-hardware.org/?probe=e5b411431c) | Mar 02, 2023 |
| ASUSTek       | N550JK                      | [1a041d0aad](https://linux-hardware.org/?probe=1a041d0aad) | Mar 01, 2023 |
| HP            | ProBook 635 Aero G8 Note... | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| HP            | Laptop 15t-dy200            | [3ea4171270](https://linux-hardware.org/?probe=3ea4171270) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Sony          | VGN-Z21WRN_B                | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| Acer          | AO725                       | [9c6719e733](https://linux-hardware.org/?probe=9c6719e733) | Feb 24, 2023 |
| Lenovo        | Flex 2-14 20404             | [49445991dc](https://linux-hardware.org/?probe=49445991dc) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0dba794459](https://linux-hardware.org/?probe=0dba794459) | Feb 22, 2023 |
| HUAWEI        | CREF-XX                     | [e523c006bf](https://linux-hardware.org/?probe=e523c006bf) | Feb 22, 2023 |
| Timi          | TM1707                      | [9bc429fbd6](https://linux-hardware.org/?probe=9bc429fbd6) | Feb 22, 2023 |
| Acer          | Nitro AN515-52              | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | [c059bdf126](https://linux-hardware.org/?probe=c059bdf126) | Feb 12, 2023 |
| Dell          | Inspiron 3576               | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| ASUSTek       | P552SJ                      | [314c83cb10](https://linux-hardware.org/?probe=314c83cb10) | Feb 06, 2023 |
| Dell          | Vostro 1015                 | [d93258a6f8](https://linux-hardware.org/?probe=d93258a6f8) | Feb 05, 2023 |
| Valve         | Jupiter                     | [f0309f442d](https://linux-hardware.org/?probe=f0309f442d) | Feb 03, 2023 |
| Dell          | Latitude E5410              | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| HP            | Laptop 15-db0xxx            | [a9dace6356](https://linux-hardware.org/?probe=a9dace6356) | Jan 24, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [082d1b40bc](https://linux-hardware.org/?probe=082d1b40bc) | Jan 21, 2023 |
| HONOR         | NBR-WAX9                    | [ca0282295b](https://linux-hardware.org/?probe=ca0282295b) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| Lenovo        | IdeaPad Z580                | [f51c90cadc](https://linux-hardware.org/?probe=f51c90cadc) | Jan 15, 2023 |
| Irbis         | NB264                       | [ed534a1d30](https://linux-hardware.org/?probe=ed534a1d30) | Jan 15, 2023 |
| Acer          | Swift SFX16-52G             | [c8b31b22f8](https://linux-hardware.org/?probe=c8b31b22f8) | Jan 14, 2023 |
| Dell          | Inspiron 1012               | [ae34ca229c](https://linux-hardware.org/?probe=ae34ca229c) | Jan 13, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [9ebcc90bcf](https://linux-hardware.org/?probe=9ebcc90bcf) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [322e6e6dbe](https://linux-hardware.org/?probe=322e6e6dbe) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [f75fea559f](https://linux-hardware.org/?probe=f75fea559f) | Jan 08, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c721dc5ba1](https://linux-hardware.org/?probe=c721dc5ba1) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| Dell          | Vostro 15 3510              | [aaf276dad9](https://linux-hardware.org/?probe=aaf276dad9) | Jan 06, 2023 |
| Acer          | Swift SFX16-52G             | [7ff6038cf3](https://linux-hardware.org/?probe=7ff6038cf3) | Jan 04, 2023 |
| Dell          | Latitude 5420               | [b7315d38e1](https://linux-hardware.org/?probe=b7315d38e1) | Jan 04, 2023 |
| Acer          | Swift SFX16-52G             | [bd8403001c](https://linux-hardware.org/?probe=bd8403001c) | Jan 02, 2023 |
| Dell          | Latitude D620               | [5337d0b0f9](https://linux-hardware.org/?probe=5337d0b0f9) | Dec 31, 2022 |
| Dell          | Latitude D620               | [ea81d9f6a5](https://linux-hardware.org/?probe=ea81d9f6a5) | Dec 31, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [bc961748be](https://linux-hardware.org/?probe=bc961748be) | Dec 25, 2022 |
| Acer          | Aspire A315-53              | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| Dell          | Inspiron 7720               | [0a7621cb40](https://linux-hardware.org/?probe=0a7621cb40) | Dec 17, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [50e8243e50](https://linux-hardware.org/?probe=50e8243e50) | Dec 11, 2022 |
| Acer          | Aspire A114-33              | [0bb6c29bb6](https://linux-hardware.org/?probe=0bb6c29bb6) | Dec 07, 2022 |
| HIPER Tech... | HTHLP-04R/i5-8279u          | [1ead815604](https://linux-hardware.org/?probe=1ead815604) | Dec 05, 2022 |
| Dell          | Latitude E7470              | [457187e169](https://linux-hardware.org/?probe=457187e169) | Dec 01, 2022 |
| Dell          | Latitude E7470              | [b24884fe44](https://linux-hardware.org/?probe=b24884fe44) | Dec 01, 2022 |
| Acer          | Aspire 5741G                | [0a336099ba](https://linux-hardware.org/?probe=0a336099ba) | Dec 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [8a99ec717f](https://linux-hardware.org/?probe=8a99ec717f) | Nov 29, 2022 |
| Lenovo        | B590 20208                  | [b1551151f5](https://linux-hardware.org/?probe=b1551151f5) | Nov 24, 2022 |
| Acer          | Aspire A515-57              | [374b408342](https://linux-hardware.org/?probe=374b408342) | Nov 22, 2022 |
| Samsung       | R528/R728                   | [ea586efd66](https://linux-hardware.org/?probe=ea586efd66) | Nov 19, 2022 |
| Chuwi         | HeroBook Air                | [9749e5705a](https://linux-hardware.org/?probe=9749e5705a) | Nov 13, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [40cce7a719](https://linux-hardware.org/?probe=40cce7a719) | Nov 09, 2022 |
| Dell          | Inspiron 7720               | [38d24e4b4a](https://linux-hardware.org/?probe=38d24e4b4a) | Nov 06, 2022 |
| MSI           | MS-1688                     | [21dad91aac](https://linux-hardware.org/?probe=21dad91aac) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [cb2a07da11](https://linux-hardware.org/?probe=cb2a07da11) | Oct 30, 2022 |
| ASUSTek       | X501A1                      | [037e1402b1](https://linux-hardware.org/?probe=037e1402b1) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| Acer          | Enduro EUN314-51W           | [2655b43e2b](https://linux-hardware.org/?probe=2655b43e2b) | Oct 25, 2022 |
| Acer          | Extensa 5630                | [bdc63e9670](https://linux-hardware.org/?probe=bdc63e9670) | Oct 25, 2022 |
| Timi          | RedmiBook Pro 14S           | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [2dd0b46420](https://linux-hardware.org/?probe=2dd0b46420) | Oct 16, 2022 |
| ASUSTek       | K53TA                       | [8759f9f39c](https://linux-hardware.org/?probe=8759f9f39c) | Oct 15, 2022 |
| ASUSTek       | K53TA                       | [dd95142fda](https://linux-hardware.org/?probe=dd95142fda) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| HP            | Laptop 15-db0xxx            | [16bb04d1db](https://linux-hardware.org/?probe=16bb04d1db) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [52c4e232f3](https://linux-hardware.org/?probe=52c4e232f3) | Oct 10, 2022 |
| HONOR         | BOD-WXX9                    | [26c4b5f06a](https://linux-hardware.org/?probe=26c4b5f06a) | Oct 06, 2022 |
| Apple         | MacBookPro9,2               | [bdc21c1bad](https://linux-hardware.org/?probe=bdc21c1bad) | Oct 04, 2022 |
| Apple         | MacBookPro9,2               | [50e50f0533](https://linux-hardware.org/?probe=50e50f0533) | Oct 04, 2022 |
| Sony          | VPCEB1M1R                   | [343feefe62](https://linux-hardware.org/?probe=343feefe62) | Oct 02, 2022 |
| Acer          | Aspire V3-571G              | [bfd8dc3c18](https://linux-hardware.org/?probe=bfd8dc3c18) | Oct 02, 2022 |
| Acer          | Enduro EN314-51W            | [46782cf8f5](https://linux-hardware.org/?probe=46782cf8f5) | Oct 01, 2022 |
| Dell          | Latitude E7240              | [75501a47b5](https://linux-hardware.org/?probe=75501a47b5) | Sep 24, 2022 |
| HP            | ENVY Notebook               | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| Acer          | Aspire A315-23              | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| HP            | Pavilion g6                 | [dfd4d1f4e2](https://linux-hardware.org/?probe=dfd4d1f4e2) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [d9742b9445](https://linux-hardware.org/?probe=d9742b9445) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6c5e991427](https://linux-hardware.org/?probe=6c5e991427) | Sep 18, 2022 |
| Lenovo        | G580 20150                  | [fe325d1046](https://linux-hardware.org/?probe=fe325d1046) | Sep 18, 2022 |
| HP            | Pavilion dv6                | [9c9c531c6b](https://linux-hardware.org/?probe=9c9c531c6b) | Sep 15, 2022 |
| Timi          | RedmiBook Pro 14S           | [1662163cb8](https://linux-hardware.org/?probe=1662163cb8) | Sep 15, 2022 |
| Acer          | TravelMate 5744Z            | [f9846e0165](https://linux-hardware.org/?probe=f9846e0165) | Sep 13, 2022 |
| Lenovo        | Unknown                     | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| Timi          | TM1703                      | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| Timi          | TM1703                      | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | G580 20150                  | [8dba025148](https://linux-hardware.org/?probe=8dba025148) | Sep 05, 2022 |
| Dell          | Latitude 5591               | [b860997149](https://linux-hardware.org/?probe=b860997149) | Sep 01, 2022 |
| Timi          | A35                         | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Acer          | Aspire 5570Z                | [38fe74cbe3](https://linux-hardware.org/?probe=38fe74cbe3) | Aug 26, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [ba23396754](https://linux-hardware.org/?probe=ba23396754) | Aug 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [b8859a4f21](https://linux-hardware.org/?probe=b8859a4f21) | Aug 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ce734a061a](https://linux-hardware.org/?probe=ce734a061a) | Aug 23, 2022 |
| ASUSTek       | N56VZ                       | [e9e40a7df5](https://linux-hardware.org/?probe=e9e40a7df5) | Aug 20, 2022 |
| Timi          | A35                         | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| Acer          | Aspire ES1-532G             | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a533aea5e5](https://linux-hardware.org/?probe=a533aea5e5) | Aug 14, 2022 |
| Timi          | A35                         | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Dell          | XPS 15 9550                 | [abf6de9a2d](https://linux-hardware.org/?probe=abf6de9a2d) | Aug 09, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| ASUSTek       | X301A1                      | [60d9f2bc4d](https://linux-hardware.org/?probe=60d9f2bc4d) | Aug 02, 2022 |
| Acer          | Aspire A315-42              | [7d8e339d92](https://linux-hardware.org/?probe=7d8e339d92) | Aug 02, 2022 |
| HP            | 255 G7 Notebook PC          | [bc1a82a647](https://linux-hardware.org/?probe=bc1a82a647) | Jul 28, 2022 |
| Acer          | Iconia W700                 | [694887391c](https://linux-hardware.org/?probe=694887391c) | Jul 26, 2022 |
| Acer          | TravelMate 5744Z            | [aa1416d2e3](https://linux-hardware.org/?probe=aa1416d2e3) | Jul 26, 2022 |
| HP            | 255 G7 Notebook PC          | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 15 9550                 | [b4691ae23b](https://linux-hardware.org/?probe=b4691ae23b) | Jul 22, 2022 |
| Fujitsu       | LIFEBOOK AH512              | [de59ca3757](https://linux-hardware.org/?probe=de59ca3757) | Jul 17, 2022 |
| Acer          | Iconia W700                 | [f290f68268](https://linux-hardware.org/?probe=f290f68268) | Jul 14, 2022 |
| Dell          | Latitude 7280               | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| Toshiba       | Satellite C660              | [fa23f41617](https://linux-hardware.org/?probe=fa23f41617) | Jul 13, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [19209d1119](https://linux-hardware.org/?probe=19209d1119) | Jul 12, 2022 |
| MSI           | Bravo 17 A4DDK              | [9f9d1cac61](https://linux-hardware.org/?probe=9f9d1cac61) | Jul 09, 2022 |
| ASUSTek       | F3JR                        | [9a1e994bcb](https://linux-hardware.org/?probe=9a1e994bcb) | Jul 08, 2022 |
| Prestigio     | Multipad Visconte V         | [d582eea1af](https://linux-hardware.org/?probe=d582eea1af) | Jul 08, 2022 |
| MSI           | Prestige 14 A10SC           | [f1632a7901](https://linux-hardware.org/?probe=f1632a7901) | Jul 06, 2022 |
| Fujitsu       | LIFEBOOK E734               | [6494f9e1ef](https://linux-hardware.org/?probe=6494f9e1ef) | Jul 05, 2022 |
| ASUSTek       | TP501UB                     | [4cebce6bab](https://linux-hardware.org/?probe=4cebce6bab) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [6ee62813e8](https://linux-hardware.org/?probe=6ee62813e8) | Jul 04, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [f63cb64736](https://linux-hardware.org/?probe=f63cb64736) | Jul 03, 2022 |
| Acer          | Aspire 5741G                | [228eb87fbc](https://linux-hardware.org/?probe=228eb87fbc) | Jul 02, 2022 |
| Lenovo        | G550 20023                  | [0a2aa10fd1](https://linux-hardware.org/?probe=0a2aa10fd1) | Jun 27, 2022 |
| Acer          | Swift SF314-41              | [735d7a92b5](https://linux-hardware.org/?probe=735d7a92b5) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [6ebb8676bf](https://linux-hardware.org/?probe=6ebb8676bf) | Jun 16, 2022 |
| HP            | Pavilion g6                 | [c43a328a7d](https://linux-hardware.org/?probe=c43a328a7d) | Jun 13, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5c07fd1664](https://linux-hardware.org/?probe=5c07fd1664) | Jun 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [44704fc87d](https://linux-hardware.org/?probe=44704fc87d) | Jun 12, 2022 |
| HP            | ProBook 455 G7              | [60bf6f8388](https://linux-hardware.org/?probe=60bf6f8388) | Jun 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| Acer          | Swift SF314-43              | [2a3a49ac86](https://linux-hardware.org/?probe=2a3a49ac86) | Jun 10, 2022 |
| Lenovo        | ThinkPad P52s 20LBS04700    | [96e3e051da](https://linux-hardware.org/?probe=96e3e051da) | Jun 09, 2022 |
| Lenovo        | ThinkPad P52s 20LBS04700    | [547e2586ca](https://linux-hardware.org/?probe=547e2586ca) | Jun 09, 2022 |
| eMachines     | eME528                      | [1a6f2ee67f](https://linux-hardware.org/?probe=1a6f2ee67f) | Jun 09, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [f0b7599192](https://linux-hardware.org/?probe=f0b7599192) | Jun 08, 2022 |
| Acer          | Aspire A315-32              | [a610c5537a](https://linux-hardware.org/?probe=a610c5537a) | Jun 07, 2022 |
| Lenovo        | G580 20150                  | [6cb0b47bb4](https://linux-hardware.org/?probe=6cb0b47bb4) | Jun 02, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 455 G7              | [658e8ce62f](https://linux-hardware.org/?probe=658e8ce62f) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 455 G7              | [d95897f938](https://linux-hardware.org/?probe=d95897f938) | May 31, 2022 |
| HP            | ProBook 450 G5              | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| ASUSTek       | X75A1                       | [59159b4b05](https://linux-hardware.org/?probe=59159b4b05) | May 27, 2022 |
| Minix         | Z64 V1.2                    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | Pavilion g7                 | [e038c828f9](https://linux-hardware.org/?probe=e038c828f9) | May 25, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7200a39439](https://linux-hardware.org/?probe=7200a39439) | May 23, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [377330c2b5](https://linux-hardware.org/?probe=377330c2b5) | May 23, 2022 |
| Dell          | Vostro 15 3515              | [90d9ac6bf3](https://linux-hardware.org/?probe=90d9ac6bf3) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1e61b49f67](https://linux-hardware.org/?probe=1e61b49f67) | May 18, 2022 |
| Dell          | Precision M6800             | [65d5a77965](https://linux-hardware.org/?probe=65d5a77965) | May 14, 2022 |
| Irbis         | NB144                       | [abb6000f0b](https://linux-hardware.org/?probe=abb6000f0b) | May 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [eb297f3c7b](https://linux-hardware.org/?probe=eb297f3c7b) | May 12, 2022 |
| Minix         | Z64 V1.2                    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Lenovo        | Unknown                     | [3cced8a4fa](https://linux-hardware.org/?probe=3cced8a4fa) | May 12, 2022 |
| Samsung       | R530/R730/P530              | [d209735fd8](https://linux-hardware.org/?probe=d209735fd8) | May 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [ac2c2a5969](https://linux-hardware.org/?probe=ac2c2a5969) | May 06, 2022 |
| Lenovo        | ThinkPad X220 4290LD4       | [0a28279824](https://linux-hardware.org/?probe=0a28279824) | May 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [26cfc77ab9](https://linux-hardware.org/?probe=26cfc77ab9) | May 02, 2022 |
| ICL           | RAYbook Si1507              | [eaf9bd7ea3](https://linux-hardware.org/?probe=eaf9bd7ea3) | May 02, 2022 |
| HP            | ProBook 4520s               | [ba430a31ae](https://linux-hardware.org/?probe=ba430a31ae) | May 01, 2022 |
| Lenovo        | G700 20251                  | [94272db5ec](https://linux-hardware.org/?probe=94272db5ec) | Apr 30, 2022 |
| ASUSTek       | UX31A                       | [59228e735e](https://linux-hardware.org/?probe=59228e735e) | Apr 30, 2022 |
| Acer          | TravelMate 2490             | [8cc2cf84f4](https://linux-hardware.org/?probe=8cc2cf84f4) | Apr 29, 2022 |
| Timi          | A35S                        | [8a3195e10c](https://linux-hardware.org/?probe=8a3195e10c) | Apr 27, 2022 |
| Timi          | RedmiBook Pro 15S           | [d060ed71c3](https://linux-hardware.org/?probe=d060ed71c3) | Apr 26, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [4f92840d8c](https://linux-hardware.org/?probe=4f92840d8c) | Apr 26, 2022 |
| Lenovo        | G510 20238                  | [906f1626d7](https://linux-hardware.org/?probe=906f1626d7) | Apr 24, 2022 |
| Acer          | AOD257                      | [9b11649bce](https://linux-hardware.org/?probe=9b11649bce) | Apr 22, 2022 |
| Acer          | AOD257                      | [e321b17ef8](https://linux-hardware.org/?probe=e321b17ef8) | Apr 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [76bb32f682](https://linux-hardware.org/?probe=76bb32f682) | Apr 20, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | UX303LB                     | [104779add9](https://linux-hardware.org/?probe=104779add9) | Apr 17, 2022 |
| HP            | 250 G2                      | [eafcfe8215](https://linux-hardware.org/?probe=eafcfe8215) | Apr 17, 2022 |
| ASUSTek       | K50IJ                       | [ad5a24dbb3](https://linux-hardware.org/?probe=ad5a24dbb3) | Apr 15, 2022 |
| ASUSTek       | ROG Strix G713QC_G713QC     | [c54b458c01](https://linux-hardware.org/?probe=c54b458c01) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [9e8785fcdd](https://linux-hardware.org/?probe=9e8785fcdd) | Apr 14, 2022 |
| ASUSTek       | X75VCP                      | [21e0b65e1b](https://linux-hardware.org/?probe=21e0b65e1b) | Apr 13, 2022 |
| Lenovo        | G780 20138                  | [0cabea6484](https://linux-hardware.org/?probe=0cabea6484) | Apr 08, 2022 |
| Lenovo        | B570 HuronRiver Platform    | [cdb5f43cd7](https://linux-hardware.org/?probe=cdb5f43cd7) | Apr 07, 2022 |
| Timi          | A35                         | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [262e4f8317](https://linux-hardware.org/?probe=262e4f8317) | Apr 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [27f986af8c](https://linux-hardware.org/?probe=27f986af8c) | Mar 30, 2022 |
| Insignia      | NS-P11W7100                 | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [b431dc3d73](https://linux-hardware.org/?probe=b431dc3d73) | Mar 28, 2022 |
| HP            | ZBook 17 G3                 | [b016648f02](https://linux-hardware.org/?probe=b016648f02) | Mar 27, 2022 |
| Aquarius      | NS585 R32                   | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| ASUSTek       | X75VCP                      | [54e978fcca](https://linux-hardware.org/?probe=54e978fcca) | Mar 23, 2022 |
| Timi          | RedmiBook Pro 15            | [78f30b04b6](https://linux-hardware.org/?probe=78f30b04b6) | Mar 21, 2022 |
| Samsung       | R59P/R60P/R61P              | [2ec6236c3a](https://linux-hardware.org/?probe=2ec6236c3a) | Mar 20, 2022 |
| Insignia      | NS-P11W7100                 | [20aa266b33](https://linux-hardware.org/?probe=20aa266b33) | Mar 19, 2022 |
| Unknown       | Unknown                     | [58912ced73](https://linux-hardware.org/?probe=58912ced73) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [4652b9e771](https://linux-hardware.org/?probe=4652b9e771) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [091eb95750](https://linux-hardware.org/?probe=091eb95750) | Mar 17, 2022 |
| Lenovo        | IdeaPad Z580                | [80a27aca02](https://linux-hardware.org/?probe=80a27aca02) | Mar 17, 2022 |
| Insignia      | NS-P11W7100                 | [44de443312](https://linux-hardware.org/?probe=44de443312) | Mar 11, 2022 |
| HP            | ProBook 450 G7              | [5d73b6f2f7](https://linux-hardware.org/?probe=5d73b6f2f7) | Mar 08, 2022 |
| ASUSTek       | S301LP                      | [5c29218ebd](https://linux-hardware.org/?probe=5c29218ebd) | Mar 08, 2022 |
| Lenovo        | Unknown                     | [4308edfd8d](https://linux-hardware.org/?probe=4308edfd8d) | Mar 07, 2022 |
| Acer          | Swift SF314-43              | [6d16601f06](https://linux-hardware.org/?probe=6d16601f06) | Mar 07, 2022 |
| HP            | 250 G8 Notebook PC          | [11ca11b21d](https://linux-hardware.org/?probe=11ca11b21d) | Mar 03, 2022 |
| Dell          | Vostro 5470                 | [fda73ff759](https://linux-hardware.org/?probe=fda73ff759) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| Dell          | Inspiron 15-3552            | [969cea89d7](https://linux-hardware.org/?probe=969cea89d7) | Feb 24, 2022 |
| HP            | ProBook 4540s               | [6bc6c84af5](https://linux-hardware.org/?probe=6bc6c84af5) | Feb 24, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [72f330a117](https://linux-hardware.org/?probe=72f330a117) | Feb 23, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [f6175c2b08](https://linux-hardware.org/?probe=f6175c2b08) | Feb 22, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a941fd5481](https://linux-hardware.org/?probe=a941fd5481) | Feb 21, 2022 |
| Timi          | RedmiBook Pro 15S           | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b4979c164c](https://linux-hardware.org/?probe=b4979c164c) | Feb 20, 2022 |
| Lenovo        | ThinkPad ThinkPad L14 20... | [369c625e43](https://linux-hardware.org/?probe=369c625e43) | Feb 20, 2022 |
| Acer          | Swift SF315-52              | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| HP            | Compaq CQ58                 | [6f67712b57](https://linux-hardware.org/?probe=6f67712b57) | Feb 19, 2022 |
| Timi          | RedmiBook Pro 15S           | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| ASUSTek       | K54L                        | [5850a8dd22](https://linux-hardware.org/?probe=5850a8dd22) | Feb 19, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [489854bd7b](https://linux-hardware.org/?probe=489854bd7b) | Feb 18, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | [54269ad944](https://linux-hardware.org/?probe=54269ad944) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [3c30a8c6a1](https://linux-hardware.org/?probe=3c30a8c6a1) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4fba279b51](https://linux-hardware.org/?probe=4fba279b51) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [42cf76ea1b](https://linux-hardware.org/?probe=42cf76ea1b) | Feb 18, 2022 |
| Dell          | Vostro 2521                 | [b4e4037c5e](https://linux-hardware.org/?probe=b4e4037c5e) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Samsung       | 535U4C                      | [f5f9256781](https://linux-hardware.org/?probe=f5f9256781) | Feb 16, 2022 |
| HP            | ProBook 440 G7              | [bf3d7b3f6c](https://linux-hardware.org/?probe=bf3d7b3f6c) | Feb 15, 2022 |
| Lenovo        | G500 20236                  | [725807db6f](https://linux-hardware.org/?probe=725807db6f) | Feb 15, 2022 |
| ASUSTek       | X553MA                      | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| HP            | Pavilion g6                 | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| MSI           | MS-16F1                     | [cd35935349](https://linux-hardware.org/?probe=cd35935349) | Feb 13, 2022 |
| Acer          | Extensa 5620                | [d56ce9d11a](https://linux-hardware.org/?probe=d56ce9d11a) | Feb 13, 2022 |
| ASUSTek       | X550VB                      | [0485b98343](https://linux-hardware.org/?probe=0485b98343) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | [e82c11b42e](https://linux-hardware.org/?probe=e82c11b42e) | Feb 13, 2022 |
| Dell          | Latitude 5480               | [1804ba8af6](https://linux-hardware.org/?probe=1804ba8af6) | Feb 12, 2022 |
| Dell          | Latitude 5480               | [198846e977](https://linux-hardware.org/?probe=198846e977) | Feb 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [42674c38b2](https://linux-hardware.org/?probe=42674c38b2) | Feb 12, 2022 |
| HP            | 250 G5 Notebook PC          | [1e1f5d2acb](https://linux-hardware.org/?probe=1e1f5d2acb) | Feb 11, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [2cfb1f14b9](https://linux-hardware.org/?probe=2cfb1f14b9) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c4ac76b8e8](https://linux-hardware.org/?probe=c4ac76b8e8) | Feb 10, 2022 |
| Lenovo        | IdeaPad Z580                | [bfdd2f78ce](https://linux-hardware.org/?probe=bfdd2f78ce) | Feb 10, 2022 |
| HP            | Pavilion g6                 | [5d20c75fe1](https://linux-hardware.org/?probe=5d20c75fe1) | Feb 08, 2022 |
| Razer         | Blade Stealth               | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [1bbcbcc9a2](https://linux-hardware.org/?probe=1bbcbcc9a2) | Feb 07, 2022 |
| Acer          | Aspire E1-571               | [2de4d69854](https://linux-hardware.org/?probe=2de4d69854) | Feb 06, 2022 |
| Lenovo        | IdeaPad S110 20126          | [1d55b1f711](https://linux-hardware.org/?probe=1d55b1f711) | Feb 06, 2022 |
| ASUSTek       | N61Ja                       | [77e8b534fb](https://linux-hardware.org/?probe=77e8b534fb) | Feb 05, 2022 |
| Lenovo        | IdeaPad S110 20126          | [b7ae05b6a1](https://linux-hardware.org/?probe=b7ae05b6a1) | Feb 05, 2022 |
| ASUSTek       | N61Ja                       | [3fee6a87f0](https://linux-hardware.org/?probe=3fee6a87f0) | Feb 05, 2022 |
| HP            | EliteBook 840 G3            | [020d6c69c2](https://linux-hardware.org/?probe=020d6c69c2) | Feb 05, 2022 |
| Packard Be... | EasyNote_NJ66               | [11d3d91c9d](https://linux-hardware.org/?probe=11d3d91c9d) | Feb 04, 2022 |
| Packard Be... | EasyNote_NJ66               | [a686d7ec8d](https://linux-hardware.org/?probe=a686d7ec8d) | Feb 04, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [b4c8891709](https://linux-hardware.org/?probe=b4c8891709) | Feb 03, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [d9cc5f0548](https://linux-hardware.org/?probe=d9cc5f0548) | Feb 03, 2022 |
| Timi          | RedmiBook 14-APCS           | [2f335a9d87](https://linux-hardware.org/?probe=2f335a9d87) | Feb 01, 2022 |
| HP            | ProBook 440 G5              | [0e27902494](https://linux-hardware.org/?probe=0e27902494) | Jan 31, 2022 |
| MSI           | GF63 Thin 10SC              | [6ff4bcaf7c](https://linux-hardware.org/?probe=6ff4bcaf7c) | Jan 31, 2022 |
| MSI           | GF63 Thin 10SC              | [be02f0bd97](https://linux-hardware.org/?probe=be02f0bd97) | Jan 31, 2022 |
| MSI           | GF63 Thin 10SC              | [4ffd0d7f19](https://linux-hardware.org/?probe=4ffd0d7f19) | Jan 31, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ebe757d792](https://linux-hardware.org/?probe=ebe757d792) | Jan 30, 2022 |
| HP            | ProBook 440 G5              | [930aa74ba2](https://linux-hardware.org/?probe=930aa74ba2) | Jan 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [d3f7315d42](https://linux-hardware.org/?probe=d3f7315d42) | Jan 30, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a1b813490a](https://linux-hardware.org/?probe=a1b813490a) | Jan 29, 2022 |
| Dell          | Vostro 3300                 | [4213d2a7a3](https://linux-hardware.org/?probe=4213d2a7a3) | Jan 29, 2022 |
| HP            | Laptop 14-cf3xxx            | [52d1ace9ee](https://linux-hardware.org/?probe=52d1ace9ee) | Jan 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c573633ba7](https://linux-hardware.org/?probe=c573633ba7) | Jan 28, 2022 |
| Lenovo        | G500 20236                  | [5d49bf2ce4](https://linux-hardware.org/?probe=5d49bf2ce4) | Jan 27, 2022 |
| Lenovo        | G500 20236                  | [c346ce1a75](https://linux-hardware.org/?probe=c346ce1a75) | Jan 27, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [c42d3ff769](https://linux-hardware.org/?probe=c42d3ff769) | Jan 27, 2022 |
| HP            | ProBook 6560b               | [e61fbcfd64](https://linux-hardware.org/?probe=e61fbcfd64) | Jan 27, 2022 |
| MSI           | Pulse GL66 11UDK            | [06d5ba6ef3](https://linux-hardware.org/?probe=06d5ba6ef3) | Jan 26, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [d44db9ca0d](https://linux-hardware.org/?probe=d44db9ca0d) | Jan 24, 2022 |
| Timi          | RedmiBook Pro 15            | [6ed1fe66db](https://linux-hardware.org/?probe=6ed1fe66db) | Jan 24, 2022 |
| Lenovo        | ThinkPad E590 20NB0058RT    | [0b56eb1e6e](https://linux-hardware.org/?probe=0b56eb1e6e) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [06eb5b9d8d](https://linux-hardware.org/?probe=06eb5b9d8d) | Jan 23, 2022 |
| HP            | ProBook 4540s               | [4dea69e6af](https://linux-hardware.org/?probe=4dea69e6af) | Jan 23, 2022 |
| Dell          | Inspiron 5720               | [4dab658338](https://linux-hardware.org/?probe=4dab658338) | Jan 22, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [ff7be689c1](https://linux-hardware.org/?probe=ff7be689c1) | Jan 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [7926e3c998](https://linux-hardware.org/?probe=7926e3c998) | Jan 19, 2022 |
| Timi          | RedmiBook Pro 14            | [b243482994](https://linux-hardware.org/?probe=b243482994) | Jan 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [49d5581480](https://linux-hardware.org/?probe=49d5581480) | Jan 19, 2022 |
| Shuttle       | DS68U                       | [5ac4aed9d9](https://linux-hardware.org/?probe=5ac4aed9d9) | Jan 19, 2022 |
| HP            | 250 G5 Notebook PC          | [677a43f9a4](https://linux-hardware.org/?probe=677a43f9a4) | Jan 18, 2022 |
| HP            | ZBook 15v G5                | [e21cdc9211](https://linux-hardware.org/?probe=e21cdc9211) | Jan 18, 2022 |
| Dell          | Latitude 7490               | [66984a4e2b](https://linux-hardware.org/?probe=66984a4e2b) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [a84625d725](https://linux-hardware.org/?probe=a84625d725) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| Lenovo        | V580 20147                  | [b59112177d](https://linux-hardware.org/?probe=b59112177d) | Jan 17, 2022 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [3b8acf9181](https://linux-hardware.org/?probe=3b8acf9181) | Jan 17, 2022 |
| Timi          | A18R                        | [37b8388616](https://linux-hardware.org/?probe=37b8388616) | Jan 16, 2022 |
| Lenovo        | IdeaPad Z580                | [abd0e9203d](https://linux-hardware.org/?probe=abd0e9203d) | Jan 13, 2022 |
| Packard Be... | EasyNote ENTE70BH           | [decd20a2d5](https://linux-hardware.org/?probe=decd20a2d5) | Jan 13, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [7e083c332f](https://linux-hardware.org/?probe=7e083c332f) | Jan 12, 2022 |
| Timi          | RedmiBook 14-APCS           | [ea556dd23d](https://linux-hardware.org/?probe=ea556dd23d) | Jan 12, 2022 |
| Timi          | RedmiBook Pro 14            | [c115b553a2](https://linux-hardware.org/?probe=c115b553a2) | Jan 12, 2022 |
| Acer          | Aspire A515-56              | [4b9aea4afc](https://linux-hardware.org/?probe=4b9aea4afc) | Jan 11, 2022 |
| HP            | ProBook 440 G5              | [ff9bfac8e3](https://linux-hardware.org/?probe=ff9bfac8e3) | Jan 10, 2022 |
| HP            | ProBook 5310m               | [e3c8188e1e](https://linux-hardware.org/?probe=e3c8188e1e) | Jan 10, 2022 |
| HP            | Pavilion 15                 | [6e63d80da8](https://linux-hardware.org/?probe=6e63d80da8) | Jan 09, 2022 |
| HP            | ZBook 15v G5                | [f529eb1829](https://linux-hardware.org/?probe=f529eb1829) | Jan 08, 2022 |
| HP            | ZBook 15v G5                | [5d912e6781](https://linux-hardware.org/?probe=5d912e6781) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [bdfe615a8e](https://linux-hardware.org/?probe=bdfe615a8e) | Jan 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [b9751c3304](https://linux-hardware.org/?probe=b9751c3304) | Jan 07, 2022 |
| HP            | Laptop 14s-fq1xxx           | [5f51ec95e1](https://linux-hardware.org/?probe=5f51ec95e1) | Jan 05, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [65d859bfe1](https://linux-hardware.org/?probe=65d859bfe1) | Jan 05, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [cd84c7dfde](https://linux-hardware.org/?probe=cd84c7dfde) | Jan 04, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [7ed7ce0cb7](https://linux-hardware.org/?probe=7ed7ce0cb7) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [43f3abae3d](https://linux-hardware.org/?probe=43f3abae3d) | Jan 04, 2022 |
| ilife         | S806                        | [72d842b86c](https://linux-hardware.org/?probe=72d842b86c) | Jan 04, 2022 |
| Samsung       | R538/R578/R778              | [617d9d3835](https://linux-hardware.org/?probe=617d9d3835) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [08b04c15d3](https://linux-hardware.org/?probe=08b04c15d3) | Jan 03, 2022 |
| ASUSTek       | N55SF                       | [545345d609](https://linux-hardware.org/?probe=545345d609) | Jan 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [86160c79c7](https://linux-hardware.org/?probe=86160c79c7) | Jan 01, 2022 |
| HP            | Cario CQ57                  | [5ac4e3101c](https://linux-hardware.org/?probe=5ac4e3101c) | Dec 31, 2021 |
| Acer          | Aspire E5-575G              | [f6d8856ace](https://linux-hardware.org/?probe=f6d8856ace) | Dec 30, 2021 |
| Timi          | A35                         | [253959bb70](https://linux-hardware.org/?probe=253959bb70) | Dec 30, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b744f2896b](https://linux-hardware.org/?probe=b744f2896b) | Dec 30, 2021 |
| HP            | Laptop 15s-eq1xxx           | [988270bc86](https://linux-hardware.org/?probe=988270bc86) | Dec 30, 2021 |
| Acer          | Aspire 1810TZ               | [0b7bd5c1fa](https://linux-hardware.org/?probe=0b7bd5c1fa) | Dec 30, 2021 |
| Acer          | Aspire 5715Z                | [d2074751d0](https://linux-hardware.org/?probe=d2074751d0) | Dec 29, 2021 |
| Lenovo        | B50-30 20382                | [896ea31fe5](https://linux-hardware.org/?probe=896ea31fe5) | Dec 28, 2021 |
| Acer          | Swift SF114-34              | [f3683a3e4e](https://linux-hardware.org/?probe=f3683a3e4e) | Dec 28, 2021 |
| Acer          | Swift SF114-34              | [891cb4d0fd](https://linux-hardware.org/?probe=891cb4d0fd) | Dec 28, 2021 |
| Dell          | Vostro 1510                 | [38a24e373f](https://linux-hardware.org/?probe=38a24e373f) | Dec 28, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [cc15a65a54](https://linux-hardware.org/?probe=cc15a65a54) | Dec 27, 2021 |
| Google        | Barla                       | [61c74be569](https://linux-hardware.org/?probe=61c74be569) | Dec 26, 2021 |
| HP            | EliteBook 2570p             | [e17f3ed027](https://linux-hardware.org/?probe=e17f3ed027) | Dec 26, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [43c784fc78](https://linux-hardware.org/?probe=43c784fc78) | Dec 25, 2021 |
| HP            | Presario CQ57               | [0294a92fd1](https://linux-hardware.org/?probe=0294a92fd1) | Dec 25, 2021 |
| ASUSTek       | N53SV                       | [cf07bb8280](https://linux-hardware.org/?probe=cf07bb8280) | Dec 25, 2021 |
| Timi          | A35                         | [66e9c6919d](https://linux-hardware.org/?probe=66e9c6919d) | Dec 24, 2021 |
| Dell          | Latitude E7470              | [e712cd258c](https://linux-hardware.org/?probe=e712cd258c) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [a02655b4b8](https://linux-hardware.org/?probe=a02655b4b8) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [6e08796257](https://linux-hardware.org/?probe=6e08796257) | Dec 24, 2021 |
| Acer          | Swift SF314-42              | [02cb3d9b90](https://linux-hardware.org/?probe=02cb3d9b90) | Dec 23, 2021 |
| ASUSTek       | E502NA                      | [66ade120a5](https://linux-hardware.org/?probe=66ade120a5) | Dec 23, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [3a7331c884](https://linux-hardware.org/?probe=3a7331c884) | Dec 22, 2021 |
| Timi          | Mi Gaming Laptop 15.6       | [0001a4fb5e](https://linux-hardware.org/?probe=0001a4fb5e) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | [f33ca54f97](https://linux-hardware.org/?probe=f33ca54f97) | Dec 19, 2021 |
| Timi          | RedmiBook 14 II             | [b6179a5282](https://linux-hardware.org/?probe=b6179a5282) | Dec 19, 2021 |
| Fujitsu       | CELSIUS H700                | [63c35d8f1d](https://linux-hardware.org/?probe=63c35d8f1d) | Dec 19, 2021 |
| Lenovo        | G585 20137                  | [7832d9f8f6](https://linux-hardware.org/?probe=7832d9f8f6) | Dec 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e8a4a4a5f4](https://linux-hardware.org/?probe=e8a4a4a5f4) | Dec 19, 2021 |
| MSI           | Prestige 14Evo A11M         | [2ebe52d75c](https://linux-hardware.org/?probe=2ebe52d75c) | Dec 19, 2021 |
| MSI           | Prestige 14Evo A11M         | [224bb4de1c](https://linux-hardware.org/?probe=224bb4de1c) | Dec 19, 2021 |
| HP            | 630                         | [027b9733fa](https://linux-hardware.org/?probe=027b9733fa) | Dec 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [ce3508ebb4](https://linux-hardware.org/?probe=ce3508ebb4) | Dec 17, 2021 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [6ac6be1d38](https://linux-hardware.org/?probe=6ac6be1d38) | Dec 17, 2021 |
| Timi          | RedmiBook Pro 14            | [62be8931a0](https://linux-hardware.org/?probe=62be8931a0) | Dec 16, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [8218845f08](https://linux-hardware.org/?probe=8218845f08) | Dec 15, 2021 |
| Chuwi         | GemiBook                    | [9ed21194f5](https://linux-hardware.org/?probe=9ed21194f5) | Dec 15, 2021 |
| HP            | ProBook 430 G5              | [a0faef8a2b](https://linux-hardware.org/?probe=a0faef8a2b) | Dec 14, 2021 |
| HP            | 250 G5 Notebook PC          | [4e0a6f267e](https://linux-hardware.org/?probe=4e0a6f267e) | Dec 13, 2021 |
| Acer          | Extensa 5635ZG              | [d232d67b9e](https://linux-hardware.org/?probe=d232d67b9e) | Dec 13, 2021 |
| Dell          | Latitude 7290               | [8a2ecfe430](https://linux-hardware.org/?probe=8a2ecfe430) | Dec 12, 2021 |
| Lenovo        | G550 20023                  | [39aa70e7d6](https://linux-hardware.org/?probe=39aa70e7d6) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [22eeff89e5](https://linux-hardware.org/?probe=22eeff89e5) | Dec 11, 2021 |
| ASUSTek       | X705UAR                     | [74b8b78444](https://linux-hardware.org/?probe=74b8b78444) | Dec 11, 2021 |
| Lenovo        | IdeaPad Z580                | [d801c31eda](https://linux-hardware.org/?probe=d801c31eda) | Dec 10, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [8fa17a7ab6](https://linux-hardware.org/?probe=8fa17a7ab6) | Dec 10, 2021 |
| Toshiba       | Satellite L300              | [a676b11b67](https://linux-hardware.org/?probe=a676b11b67) | Dec 08, 2021 |
| HP            | Laptop 15t-dy200            | [b624d90ea8](https://linux-hardware.org/?probe=b624d90ea8) | Dec 08, 2021 |
| Lenovo        | IdeaPad Z580                | [c07a32f1c5](https://linux-hardware.org/?probe=c07a32f1c5) | Dec 08, 2021 |
| Apple         | MacBookPro8,3               | [11e7db0824](https://linux-hardware.org/?probe=11e7db0824) | Dec 06, 2021 |
| Apple         | MacBookPro8,3               | [cbc310d77b](https://linux-hardware.org/?probe=cbc310d77b) | Dec 06, 2021 |
| Dell          | Latitude E6430              | [eee07229a4](https://linux-hardware.org/?probe=eee07229a4) | Dec 05, 2021 |
| ASUSTek       | K84L                        | [dce2044275](https://linux-hardware.org/?probe=dce2044275) | Dec 05, 2021 |
| HP            | EliteBook 2760p             | [9efe885c4c](https://linux-hardware.org/?probe=9efe885c4c) | Dec 04, 2021 |
| Lenovo        | G500 20236                  | [8aadcee8ff](https://linux-hardware.org/?probe=8aadcee8ff) | Dec 04, 2021 |
| Chuwi         | GemiBook                    | [1e8e0ca774](https://linux-hardware.org/?probe=1e8e0ca774) | Dec 03, 2021 |
| HP            | Pavilion g6                 | [35f8ef913e](https://linux-hardware.org/?probe=35f8ef913e) | Dec 02, 2021 |
| HP            | Pavilion g6                 | [c009dd878b](https://linux-hardware.org/?probe=c009dd878b) | Dec 02, 2021 |
| Acer          | Swift SF314-43              | [dc17b5db95](https://linux-hardware.org/?probe=dc17b5db95) | Dec 01, 2021 |
| Acer          | Aspire 5630                 | [90453b887a](https://linux-hardware.org/?probe=90453b887a) | Dec 01, 2021 |
| Lenovo        | G500 20236                  | [f61434ecc0](https://linux-hardware.org/?probe=f61434ecc0) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [132b5eba42](https://linux-hardware.org/?probe=132b5eba42) | Nov 29, 2021 |
| Lenovo        | S10-3                       | [19cd43f2f7](https://linux-hardware.org/?probe=19cd43f2f7) | Nov 29, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [b4a83f65e8](https://linux-hardware.org/?probe=b4a83f65e8) | Nov 27, 2021 |
| HP            | Pavilion Notebook 15-bc5... | [dc1f8255a1](https://linux-hardware.org/?probe=dc1f8255a1) | Nov 27, 2021 |
| Lenovo        | G500 20236                  | [c1dd144b77](https://linux-hardware.org/?probe=c1dd144b77) | Nov 27, 2021 |
| Timi          | A35                         | [d1461858c8](https://linux-hardware.org/?probe=d1461858c8) | Nov 27, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [1a6e8764f5](https://linux-hardware.org/?probe=1a6e8764f5) | Nov 27, 2021 |
| ASUSTek       | 1101HA                      | [a97c9a7464](https://linux-hardware.org/?probe=a97c9a7464) | Nov 25, 2021 |
| ASUSTek       | 1101HA                      | [c54c721669](https://linux-hardware.org/?probe=c54c721669) | Nov 25, 2021 |
| HP            | Presario CQ56               | [a9203b72bb](https://linux-hardware.org/?probe=a9203b72bb) | Nov 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [9cffad20cd](https://linux-hardware.org/?probe=9cffad20cd) | Nov 25, 2021 |
| Timi          | A35                         | [ce66e74002](https://linux-hardware.org/?probe=ce66e74002) | Nov 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5f4fb6db3f](https://linux-hardware.org/?probe=5f4fb6db3f) | Nov 24, 2021 |
| Chuwi         | GemiBook Pro                | [1dc5d193a3](https://linux-hardware.org/?probe=1dc5d193a3) | Nov 24, 2021 |
| Timi          | RedmiBook Pro 15            | [342085ddb3](https://linux-hardware.org/?probe=342085ddb3) | Nov 24, 2021 |
| HP            | Presario CQ56               | [b50968704d](https://linux-hardware.org/?probe=b50968704d) | Nov 24, 2021 |
| Dell          | Inspiron 5558               | [772ca16963](https://linux-hardware.org/?probe=772ca16963) | Nov 23, 2021 |
| Lenovo        | ThinkPad E14 20RA0037RT     | [5a1e17caef](https://linux-hardware.org/?probe=5a1e17caef) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a8d3bc914a](https://linux-hardware.org/?probe=a8d3bc914a) | Nov 23, 2021 |
| HP            | ProBook 440 G7              | [7863ad05f4](https://linux-hardware.org/?probe=7863ad05f4) | Nov 23, 2021 |
| HP            | Pavilion Notebook           | [7045bece2c](https://linux-hardware.org/?probe=7045bece2c) | Nov 23, 2021 |
| Lenovo        | G510 20238                  | [46cddf1bf1](https://linux-hardware.org/?probe=46cddf1bf1) | Nov 21, 2021 |
| HP            | ProBook 4540s               | [5d7d756044](https://linux-hardware.org/?probe=5d7d756044) | Nov 20, 2021 |
| HP            | ProBook 450 G7              | [c80f09c408](https://linux-hardware.org/?probe=c80f09c408) | Nov 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c07f000594](https://linux-hardware.org/?probe=c07f000594) | Nov 19, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [55554fa68d](https://linux-hardware.org/?probe=55554fa68d) | Nov 18, 2021 |
| Apple         | MacBook4,1                  | [f9ee489abd](https://linux-hardware.org/?probe=f9ee489abd) | Nov 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9fc64a9c41](https://linux-hardware.org/?probe=9fc64a9c41) | Nov 15, 2021 |
| Acer          | Aspire A715-71G             | [dd0bfcd823](https://linux-hardware.org/?probe=dd0bfcd823) | Nov 15, 2021 |
| Lenovo        | ThinkPad E450 20DCS01J00    | [ce5eb49ae7](https://linux-hardware.org/?probe=ce5eb49ae7) | Nov 14, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [8020390e6c](https://linux-hardware.org/?probe=8020390e6c) | Nov 12, 2021 |
| ASUSTek       | X750JB                      | [05e39baf5f](https://linux-hardware.org/?probe=05e39baf5f) | Nov 12, 2021 |
| ASUSTek       | 1011PX                      | [2d96503388](https://linux-hardware.org/?probe=2d96503388) | Nov 10, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0ac3172f62](https://linux-hardware.org/?probe=0ac3172f62) | Nov 09, 2021 |
| Lenovo        | ThinkPad E450 20DCS01J00    | [ee83aa5751](https://linux-hardware.org/?probe=ee83aa5751) | Nov 08, 2021 |
| Apple         | MacBook4,1                  | [a87d85ac9f](https://linux-hardware.org/?probe=a87d85ac9f) | Nov 08, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [0812e26e5a](https://linux-hardware.org/?probe=0812e26e5a) | Nov 08, 2021 |
| HP            | ProBook 450 G6              | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Dell          | Latitude E6530              | [949bc94abe](https://linux-hardware.org/?probe=949bc94abe) | Nov 05, 2021 |
| Dell          | Latitude E6530              | [3160f800e5](https://linux-hardware.org/?probe=3160f800e5) | Nov 05, 2021 |
| Acer          | Swift SF114-33              | [9e177a92f3](https://linux-hardware.org/?probe=9e177a92f3) | Nov 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | PIWG1                       | [96ae269001](https://linux-hardware.org/?probe=96ae269001) | Nov 03, 2021 |
| HP            | Pavilion dv6                | [461518c8a8](https://linux-hardware.org/?probe=461518c8a8) | Nov 03, 2021 |
| Lenovo        | G710 20252                  | [6c197fdb65](https://linux-hardware.org/?probe=6c197fdb65) | Nov 02, 2021 |
| Dell          | Latitude 5520               | [51ae6048ea](https://linux-hardware.org/?probe=51ae6048ea) | Nov 01, 2021 |
| Dell          | Inspiron 5558               | [d876caae1e](https://linux-hardware.org/?probe=d876caae1e) | Oct 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [4eb6b00cac](https://linux-hardware.org/?probe=4eb6b00cac) | Oct 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c9153e029e](https://linux-hardware.org/?probe=c9153e029e) | Oct 31, 2021 |
| Acer          | Swift SF114-34              | [84b1c46f3c](https://linux-hardware.org/?probe=84b1c46f3c) | Oct 31, 2021 |
| MSI           | GT72 6QD                    | [64f2d60b7e](https://linux-hardware.org/?probe=64f2d60b7e) | Oct 30, 2021 |
| HP            | ZBook 14u G6                | [a814284f0b](https://linux-hardware.org/?probe=a814284f0b) | Oct 29, 2021 |
| Lenovo        | V580c 20160                 | [779684e41d](https://linux-hardware.org/?probe=779684e41d) | Oct 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4770866d46](https://linux-hardware.org/?probe=4770866d46) | Oct 27, 2021 |
| Apple         | MacBookPro8,2               | [966b07a428](https://linux-hardware.org/?probe=966b07a428) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [cc4c888046](https://linux-hardware.org/?probe=cc4c888046) | Oct 27, 2021 |
| Dell          | Inspiron 5558               | [e22971aa36](https://linux-hardware.org/?probe=e22971aa36) | Oct 27, 2021 |
| Acer          | Nitro AN515-55              | [2b3ef0e291](https://linux-hardware.org/?probe=2b3ef0e291) | Oct 26, 2021 |
| Acer          | Nitro AN515-55              | [2d7ac3338d](https://linux-hardware.org/?probe=2d7ac3338d) | Oct 26, 2021 |
| Acer          | Swift SF314-59              | [1e4856a770](https://linux-hardware.org/?probe=1e4856a770) | Oct 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c91bc1deb](https://linux-hardware.org/?probe=1c91bc1deb) | Oct 23, 2021 |
| Samsung       | R59P/R60P/R61P              | [fb06ae58f0](https://linux-hardware.org/?probe=fb06ae58f0) | Oct 22, 2021 |
| HP            | 255 G7 Notebook PC          | [318a6d484a](https://linux-hardware.org/?probe=318a6d484a) | Oct 22, 2021 |
| Timi          | TM1701                      | [6ee47924bd](https://linux-hardware.org/?probe=6ee47924bd) | Oct 22, 2021 |
| Dell          | Inspiron 5558               | [6ada321924](https://linux-hardware.org/?probe=6ada321924) | Oct 22, 2021 |
| Lenovo        | V580c 20160                 | [fbeb39e0ce](https://linux-hardware.org/?probe=fbeb39e0ce) | Oct 20, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [456b686d28](https://linux-hardware.org/?probe=456b686d28) | Oct 20, 2021 |
| HP            | ZBook Firefly 15 inch G8... | [25c0517a63](https://linux-hardware.org/?probe=25c0517a63) | Oct 20, 2021 |
| Sony          | VGN-CR19VN_B                | [409f7c6aed](https://linux-hardware.org/?probe=409f7c6aed) | Oct 19, 2021 |
| Shuttle       | DS57U                       | [780ca9b317](https://linux-hardware.org/?probe=780ca9b317) | Oct 19, 2021 |
| Timi          | RedmiBook Pro 14            | [0a5df275dd](https://linux-hardware.org/?probe=0a5df275dd) | Oct 18, 2021 |
| Framework     | Laptop                      | [591c9d1d8f](https://linux-hardware.org/?probe=591c9d1d8f) | Oct 18, 2021 |
| HP            | 255 G1                      | [d37ee677e9](https://linux-hardware.org/?probe=d37ee677e9) | Oct 17, 2021 |
| Acer          | Swift SF314-41              | [589beb7652](https://linux-hardware.org/?probe=589beb7652) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [532cb2dfc8](https://linux-hardware.org/?probe=532cb2dfc8) | Oct 17, 2021 |
| Acer          | Aspire A315-42G             | [6134bf279a](https://linux-hardware.org/?probe=6134bf279a) | Oct 17, 2021 |
| eMachines     | eM350                       | [09b8fc981c](https://linux-hardware.org/?probe=09b8fc981c) | Oct 16, 2021 |
| Dell          | Latitude E6440              | [e6d39c35d6](https://linux-hardware.org/?probe=e6d39c35d6) | Oct 16, 2021 |
| Acer          | TravelMate P215-53          | [3d398d4b58](https://linux-hardware.org/?probe=3d398d4b58) | Oct 16, 2021 |
| Apple         | MacBookPro14,1              | [dc7e454319](https://linux-hardware.org/?probe=dc7e454319) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | [bf9482b190](https://linux-hardware.org/?probe=bf9482b190) | Oct 15, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [3818b62208](https://linux-hardware.org/?probe=3818b62208) | Oct 15, 2021 |
| Lenovo        | IdeaPad Z580                | [6b1d1f059f](https://linux-hardware.org/?probe=6b1d1f059f) | Oct 15, 2021 |
| Lenovo        | IdeaPad Z580                | [661f69eb29](https://linux-hardware.org/?probe=661f69eb29) | Oct 15, 2021 |
| Acer          | Aspire A515-51G             | [af67b942ec](https://linux-hardware.org/?probe=af67b942ec) | Oct 14, 2021 |
| HP            | 250 G8 Notebook PC          | [7a564f9af9](https://linux-hardware.org/?probe=7a564f9af9) | Oct 14, 2021 |
| Dell          | Latitude E6440              | [a12ce4cf4a](https://linux-hardware.org/?probe=a12ce4cf4a) | Oct 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [08cda4fcb0](https://linux-hardware.org/?probe=08cda4fcb0) | Oct 13, 2021 |
| Lenovo        | S40-70 80GQ                 | [5515480ed0](https://linux-hardware.org/?probe=5515480ed0) | Oct 13, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [89840aac65](https://linux-hardware.org/?probe=89840aac65) | Oct 13, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [139f682d03](https://linux-hardware.org/?probe=139f682d03) | Oct 12, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [fcc9eab970](https://linux-hardware.org/?probe=fcc9eab970) | Oct 12, 2021 |
| Acer          | Aspire 6935                 | [93e47a1ab3](https://linux-hardware.org/?probe=93e47a1ab3) | Oct 12, 2021 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [80718210cc](https://linux-hardware.org/?probe=80718210cc) | Oct 12, 2021 |
| Timi          | RedmiBook 13 R              | [e6c38e5b79](https://linux-hardware.org/?probe=e6c38e5b79) | Oct 10, 2021 |
| HP            | EliteBook 2760p             | [0b1f6a34ce](https://linux-hardware.org/?probe=0b1f6a34ce) | Oct 10, 2021 |
| Lenovo        | G710 20252                  | [61b036977b](https://linux-hardware.org/?probe=61b036977b) | Oct 10, 2021 |
| Dell          | System Inspiron 7720        | [6728cba5a1](https://linux-hardware.org/?probe=6728cba5a1) | Oct 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d36b70e744](https://linux-hardware.org/?probe=d36b70e744) | Oct 09, 2021 |
| Timi          | RedmiBook 16                | [23546f7a48](https://linux-hardware.org/?probe=23546f7a48) | Oct 07, 2021 |
| Dell          | Latitude E6430              | [c9b6be5ccb](https://linux-hardware.org/?probe=c9b6be5ccb) | Oct 07, 2021 |
| HP            | ProBook 455R G6             | [9cfde72e18](https://linux-hardware.org/?probe=9cfde72e18) | Oct 07, 2021 |
| HP            | ProBook 450 G7              | [b4488791d9](https://linux-hardware.org/?probe=b4488791d9) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [9ca00402e4](https://linux-hardware.org/?probe=9ca00402e4) | Oct 07, 2021 |
| Dell          | Precision 7510              | [c2bddf370f](https://linux-hardware.org/?probe=c2bddf370f) | Oct 05, 2021 |
| Lenovo        | G500 20236                  | [e3d2756797](https://linux-hardware.org/?probe=e3d2756797) | Oct 03, 2021 |
| ASUSTek       | K55VM                       | [848fef92f0](https://linux-hardware.org/?probe=848fef92f0) | Oct 02, 2021 |
| HP            | 255 G7 Notebook PC          | [472633cfb7](https://linux-hardware.org/?probe=472633cfb7) | Oct 02, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [3a0cd09aa4](https://linux-hardware.org/?probe=3a0cd09aa4) | Oct 01, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [c69f22bca8](https://linux-hardware.org/?probe=c69f22bca8) | Oct 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | [b1066885ba](https://linux-hardware.org/?probe=b1066885ba) | Oct 01, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | [fbcd17f6bc](https://linux-hardware.org/?probe=fbcd17f6bc) | Oct 01, 2021 |
| HP            | 250 G7 Notebook PC          | [20517ef47c](https://linux-hardware.org/?probe=20517ef47c) | Sep 30, 2021 |
| Lenovo        | G500 20236                  | [2e1b563aa1](https://linux-hardware.org/?probe=2e1b563aa1) | Sep 29, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | [27c1d71909](https://linux-hardware.org/?probe=27c1d71909) | Sep 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009RT    | [4d28ac0812](https://linux-hardware.org/?probe=4d28ac0812) | Sep 29, 2021 |
| ASUSTek       | X751SA                      | [9b5b69452d](https://linux-hardware.org/?probe=9b5b69452d) | Sep 29, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | [834c40e64f](https://linux-hardware.org/?probe=834c40e64f) | Sep 29, 2021 |
| ASUSTek       | 1000HE                      | [c002c44040](https://linux-hardware.org/?probe=c002c44040) | Sep 27, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [591896b2ee](https://linux-hardware.org/?probe=591896b2ee) | Sep 27, 2021 |
| HP            | ProBook 450 G7              | [0696ed1853](https://linux-hardware.org/?probe=0696ed1853) | Sep 27, 2021 |
| HP            | ProBook 450 G7              | [dc36f3a40d](https://linux-hardware.org/?probe=dc36f3a40d) | Sep 27, 2021 |
| HP            | Pavilion dv6                | [ffc397f9f8](https://linux-hardware.org/?probe=ffc397f9f8) | Sep 26, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [c4680da2f6](https://linux-hardware.org/?probe=c4680da2f6) | Sep 26, 2021 |
| HP            | Pavilion dv6                | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| HP            | 250 G7 Notebook PC          | [5fbac554c3](https://linux-hardware.org/?probe=5fbac554c3) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c248e4551a](https://linux-hardware.org/?probe=c248e4551a) | Sep 25, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [de58749699](https://linux-hardware.org/?probe=de58749699) | Sep 25, 2021 |
| ASUSTek       | UX330UA                     | [175fc7f169](https://linux-hardware.org/?probe=175fc7f169) | Sep 25, 2021 |
| Acer          | TravelMate 8572G            | [dafac228b8](https://linux-hardware.org/?probe=dafac228b8) | Sep 25, 2021 |
| Acer          | Aspire 5250                 | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [1b82bac47b](https://linux-hardware.org/?probe=1b82bac47b) | Sep 21, 2021 |
| MSI           | U270 series                 | [6b98f78732](https://linux-hardware.org/?probe=6b98f78732) | Sep 19, 2021 |
| MSI           | U270 series                 | [725e0a6a36](https://linux-hardware.org/?probe=725e0a6a36) | Sep 18, 2021 |
| Dell          | Inspiron 3543               | [030a6cb62d](https://linux-hardware.org/?probe=030a6cb62d) | Sep 18, 2021 |
| Acer          | Aspire 5560                 | [f35af81d19](https://linux-hardware.org/?probe=f35af81d19) | Sep 18, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [3656e9b0ae](https://linux-hardware.org/?probe=3656e9b0ae) | Sep 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0d59451bad](https://linux-hardware.org/?probe=0d59451bad) | Sep 16, 2021 |
| HP            | ZBook 17 G6                 | [dbebd11a10](https://linux-hardware.org/?probe=dbebd11a10) | Sep 16, 2021 |
| HP            | Laptop 15-db1xxx            | [c085ff8d88](https://linux-hardware.org/?probe=c085ff8d88) | Sep 15, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [dd10c770ed](https://linux-hardware.org/?probe=dd10c770ed) | Sep 15, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [c51f5529e4](https://linux-hardware.org/?probe=c51f5529e4) | Sep 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [f55a8d5ce5](https://linux-hardware.org/?probe=f55a8d5ce5) | Sep 14, 2021 |
| Dell          | Inspiron 3595               | [14ac87b8bc](https://linux-hardware.org/?probe=14ac87b8bc) | Sep 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | [1fbb778cec](https://linux-hardware.org/?probe=1fbb778cec) | Sep 12, 2021 |
| Samsung       | RF510/RF410/RF710           | [66ec4435e0](https://linux-hardware.org/?probe=66ec4435e0) | Sep 12, 2021 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [3c2564d223](https://linux-hardware.org/?probe=3c2564d223) | Sep 11, 2021 |
| HP            | ProBook 455 G7              | [c3d2892b84](https://linux-hardware.org/?probe=c3d2892b84) | Sep 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [0fc95e8662](https://linux-hardware.org/?probe=0fc95e8662) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [7787c87e7f](https://linux-hardware.org/?probe=7787c87e7f) | Sep 09, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [3dca1ff09e](https://linux-hardware.org/?probe=3dca1ff09e) | Sep 09, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [ca3a7ba56b](https://linux-hardware.org/?probe=ca3a7ba56b) | Sep 09, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [422d6cdb0b](https://linux-hardware.org/?probe=422d6cdb0b) | Sep 08, 2021 |
| HP            | 250 G7 Notebook PC          | [2327ab2724](https://linux-hardware.org/?probe=2327ab2724) | Sep 07, 2021 |
| HP            | 250 G7 Notebook PC          | [52b780559c](https://linux-hardware.org/?probe=52b780559c) | Sep 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9e4676c4a4](https://linux-hardware.org/?probe=9e4676c4a4) | Sep 07, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9256f3fece](https://linux-hardware.org/?probe=9256f3fece) | Sep 06, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [8bbaa65e84](https://linux-hardware.org/?probe=8bbaa65e84) | Sep 06, 2021 |
| Dell          | Vostro 3500                 | [9be94cd5b2](https://linux-hardware.org/?probe=9be94cd5b2) | Sep 06, 2021 |
| Lenovo        | G500 20236                  | [6da34b890e](https://linux-hardware.org/?probe=6da34b890e) | Sep 06, 2021 |
| Acer          | TravelMate 8572G            | [3cb180e970](https://linux-hardware.org/?probe=3cb180e970) | Sep 05, 2021 |
| Lenovo        | U310                        | [0be64d0c02](https://linux-hardware.org/?probe=0be64d0c02) | Sep 03, 2021 |
| HP            | Pavilion dv6                | [db6f843983](https://linux-hardware.org/?probe=db6f843983) | Sep 02, 2021 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [972f2ce955](https://linux-hardware.org/?probe=972f2ce955) | Sep 02, 2021 |
| Dell          | Latitude 7400               | [a72ba74a3f](https://linux-hardware.org/?probe=a72ba74a3f) | Sep 02, 2021 |
| Lenovo        | IdeaPad Y580                | [e206f222ab](https://linux-hardware.org/?probe=e206f222ab) | Aug 31, 2021 |
| Dell          | Latitude 7400               | [256ab697f4](https://linux-hardware.org/?probe=256ab697f4) | Aug 31, 2021 |
| HP            | Pavilion g6                 | [5b26455c9d](https://linux-hardware.org/?probe=5b26455c9d) | Aug 30, 2021 |
| Intel         | SandyBridge Platform        | [cde550fde9](https://linux-hardware.org/?probe=cde550fde9) | Aug 30, 2021 |
| VINGA         | Iron S140                   | [8a48730847](https://linux-hardware.org/?probe=8a48730847) | Aug 29, 2021 |
| Lenovo        | G500 20236                  | [63cfcbea30](https://linux-hardware.org/?probe=63cfcbea30) | Aug 27, 2021 |
| Acer          | Swift SF314-59              | [c4ec7d7706](https://linux-hardware.org/?probe=c4ec7d7706) | Aug 27, 2021 |
| Intel         | SandyBridge Platform        | [3b2180f4ae](https://linux-hardware.org/?probe=3b2180f4ae) | Aug 26, 2021 |
| HP            | ProBook 4530s               | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [54d26d998a](https://linux-hardware.org/?probe=54d26d998a) | Aug 25, 2021 |
| HP            | 630                         | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| HP            | Laptop 15s-fq2xxx           | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| HP            | 250 G4                      | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| Dell          | Inspiron 5559               | [bb902b38e1](https://linux-hardware.org/?probe=bb902b38e1) | Aug 24, 2021 |
| Lenovo        | ThinkPad X240 20AL00C6MZ    | [fb0a4dfc32](https://linux-hardware.org/?probe=fb0a4dfc32) | Aug 23, 2021 |
| Acer          | Aspire V3-551               | [9fd29f4a13](https://linux-hardware.org/?probe=9fd29f4a13) | Aug 23, 2021 |
| Acer          | Aspire V3-551               | [7952925c50](https://linux-hardware.org/?probe=7952925c50) | Aug 23, 2021 |
| Lenovo        | G500 20236                  | [a23cf0d12d](https://linux-hardware.org/?probe=a23cf0d12d) | Aug 22, 2021 |
| Acer          | Swift SF314-56G             | [5584375657](https://linux-hardware.org/?probe=5584375657) | Aug 20, 2021 |
| Packard Be... | EasyNote_NJ66               | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| ASUSTek       | G55VW                       | [7daa09d3c3](https://linux-hardware.org/?probe=7daa09d3c3) | Aug 19, 2021 |
| Dell          | Inspiron 3541               | [231f84ef9a](https://linux-hardware.org/?probe=231f84ef9a) | Aug 18, 2021 |
| HP            | 620                         | [c2402bee8f](https://linux-hardware.org/?probe=c2402bee8f) | Aug 18, 2021 |
| HP            | ProBook 650 G2              | [c78497a286](https://linux-hardware.org/?probe=c78497a286) | Aug 17, 2021 |
| HP            | 630                         | [a57ed15001](https://linux-hardware.org/?probe=a57ed15001) | Aug 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [31fcb375f4](https://linux-hardware.org/?probe=31fcb375f4) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d2601ba1b4](https://linux-hardware.org/?probe=d2601ba1b4) | Aug 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [92440ecd49](https://linux-hardware.org/?probe=92440ecd49) | Aug 14, 2021 |
| Lenovo        | G40-30 80FY                 | [883ec5e5c4](https://linux-hardware.org/?probe=883ec5e5c4) | Aug 14, 2021 |
| Dell          | Vostro 15-3568              | [7739bbdcc5](https://linux-hardware.org/?probe=7739bbdcc5) | Aug 13, 2021 |
| HP            | Compaq CQ58                 | [23b1aab5c3](https://linux-hardware.org/?probe=23b1aab5c3) | Aug 13, 2021 |
| Pixus         | Rise                        | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| HP            | ProBook 4530s               | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Dell          | Vostro 15-3568              | [fd1b17a77d](https://linux-hardware.org/?probe=fd1b17a77d) | Aug 11, 2021 |
| HP            | 250 G4                      | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| HP            | 250 G5 Notebook PC          | [99d6dd75ef](https://linux-hardware.org/?probe=99d6dd75ef) | Aug 09, 2021 |
| Lenovo        | G550 20023                  | [d997251cee](https://linux-hardware.org/?probe=d997251cee) | Aug 09, 2021 |
| HP            | EliteBook 8740w             | [3c345bc85c](https://linux-hardware.org/?probe=3c345bc85c) | Aug 09, 2021 |
| Dell          | Latitude E7470              | [1cc51aab6f](https://linux-hardware.org/?probe=1cc51aab6f) | Aug 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ca859cbf25](https://linux-hardware.org/?probe=ca859cbf25) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| HP            | 630                         | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [2b7700c6d3](https://linux-hardware.org/?probe=2b7700c6d3) | Aug 07, 2021 |
| Dell          | XPS 15 9560                 | [cb3d844d9a](https://linux-hardware.org/?probe=cb3d844d9a) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0db1faaeaf](https://linux-hardware.org/?probe=0db1faaeaf) | Aug 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [268e93bc48](https://linux-hardware.org/?probe=268e93bc48) | Aug 05, 2021 |
| Timi          | TM1612                      | [9c80791f81](https://linux-hardware.org/?probe=9c80791f81) | Aug 04, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0030... | [c4db4594bf](https://linux-hardware.org/?probe=c4db4594bf) | Aug 03, 2021 |
| HP            | Laptop 14-cf3xxx            | [0f4f35c2dc](https://linux-hardware.org/?probe=0f4f35c2dc) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [847bf89546](https://linux-hardware.org/?probe=847bf89546) | Aug 02, 2021 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [22790f2a7e](https://linux-hardware.org/?probe=22790f2a7e) | Aug 01, 2021 |
| Samsung       | RV408/RV508                 | [20dabc5192](https://linux-hardware.org/?probe=20dabc5192) | Jul 31, 2021 |
| HP            | ZBook 15v G5                | [49ecc85467](https://linux-hardware.org/?probe=49ecc85467) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [829ad54d2c](https://linux-hardware.org/?probe=829ad54d2c) | Jul 27, 2021 |
| Acer          | Aspire V3-551               | [3d4f4e38ce](https://linux-hardware.org/?probe=3d4f4e38ce) | Jul 27, 2021 |
| Acer          | Aspire V3-551               | [a86f57cf53](https://linux-hardware.org/?probe=a86f57cf53) | Jul 27, 2021 |
| Acer          | AOD270                      | [61e7dc1d25](https://linux-hardware.org/?probe=61e7dc1d25) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude 7400               | [0ad7b49f7a](https://linux-hardware.org/?probe=0ad7b49f7a) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Dell          | Vostro 5481                 | [4b9f94e0d0](https://linux-hardware.org/?probe=4b9f94e0d0) | Jul 25, 2021 |
| HP            | Laptop 15-db1xxx            | [97b8085def](https://linux-hardware.org/?probe=97b8085def) | Jul 25, 2021 |
| LG Electro... | S525-L.ACO1R1               | [0af3286dbd](https://linux-hardware.org/?probe=0af3286dbd) | Jul 25, 2021 |
| Acer          | Extensa 7620                | [e0e9a2e532](https://linux-hardware.org/?probe=e0e9a2e532) | Jul 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [aeb61148cb](https://linux-hardware.org/?probe=aeb61148cb) | Jul 21, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [c9a87ca2b2](https://linux-hardware.org/?probe=c9a87ca2b2) | Jul 21, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [67727f3553](https://linux-hardware.org/?probe=67727f3553) | Jul 21, 2021 |
| Acer          | Aspire 7750                 | [1d55be6cb0](https://linux-hardware.org/?probe=1d55be6cb0) | Jul 21, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [be36333f4c](https://linux-hardware.org/?probe=be36333f4c) | Jul 20, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [06f084cc9f](https://linux-hardware.org/?probe=06f084cc9f) | Jul 20, 2021 |
| Dell          | Inspiron 15-3565            | [931f3dd3ce](https://linux-hardware.org/?probe=931f3dd3ce) | Jul 20, 2021 |
| Lenovo        | IdeaPad Z580                | [b6b62cb7e9](https://linux-hardware.org/?probe=b6b62cb7e9) | Jul 19, 2021 |
| ASUSTek       | X705UDR                     | [216de55d6c](https://linux-hardware.org/?probe=216de55d6c) | Jul 18, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [1ffbe324f9](https://linux-hardware.org/?probe=1ffbe324f9) | Jul 17, 2021 |
| Acer          | Aspire 7720                 | [4c7c08aef4](https://linux-hardware.org/?probe=4c7c08aef4) | Jul 17, 2021 |
| ASUSTek       | X550CL                      | [2ac04e226b](https://linux-hardware.org/?probe=2ac04e226b) | Jul 16, 2021 |
| ASUSTek       | X550CL                      | [86f477d984](https://linux-hardware.org/?probe=86f477d984) | Jul 16, 2021 |
| Acer          | AN515-52                    | [7b3eceebae](https://linux-hardware.org/?probe=7b3eceebae) | Jul 15, 2021 |
| Acer          | AN515-52                    | [f75a99b20b](https://linux-hardware.org/?probe=f75a99b20b) | Jul 15, 2021 |
| HP            | ProBook 440 G7              | [3e04f9763c](https://linux-hardware.org/?probe=3e04f9763c) | Jul 15, 2021 |
| Lenovo        | G500 20236                  | [23ba122f57](https://linux-hardware.org/?probe=23ba122f57) | Jul 15, 2021 |
| Acer          | Swift SF114-34              | [a27de08174](https://linux-hardware.org/?probe=a27de08174) | Jul 15, 2021 |
| Acer          | Aspire E5-575G              | [672a2b3117](https://linux-hardware.org/?probe=672a2b3117) | Jul 14, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [4967f4efec](https://linux-hardware.org/?probe=4967f4efec) | Jul 13, 2021 |
| ASUSTek       | A7U                         | [1fd194d456](https://linux-hardware.org/?probe=1fd194d456) | Jul 13, 2021 |
| Acer          | Aspire E1-532               | [435513eb8b](https://linux-hardware.org/?probe=435513eb8b) | Jul 12, 2021 |
| eMachines     | eM355                       | [683517b03e](https://linux-hardware.org/?probe=683517b03e) | Jul 12, 2021 |
| ASUSTek       | X441NA                      | [8e90e38d19](https://linux-hardware.org/?probe=8e90e38d19) | Jul 11, 2021 |
| Dell          | Latitude 5480               | [a0d1904129](https://linux-hardware.org/?probe=a0d1904129) | Jul 09, 2021 |
| HP            | ProBook 440 G7              | [23105ea565](https://linux-hardware.org/?probe=23105ea565) | Jul 09, 2021 |
| Dell          | Inspiron 3576               | [c5ac201e30](https://linux-hardware.org/?probe=c5ac201e30) | Jul 09, 2021 |
| eMachines     | eM350                       | [1124de4983](https://linux-hardware.org/?probe=1124de4983) | Jul 08, 2021 |
| Dell          | Inspiron 3576               | [58572f3e5a](https://linux-hardware.org/?probe=58572f3e5a) | Jul 08, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [9b525f7832](https://linux-hardware.org/?probe=9b525f7832) | Jul 06, 2021 |
| eMachines     | eM355                       | [01a11f0163](https://linux-hardware.org/?probe=01a11f0163) | Jul 06, 2021 |
| eMachines     | eM350                       | [eb388a1fdb](https://linux-hardware.org/?probe=eb388a1fdb) | Jul 06, 2021 |
| Acer          | Aspire A315-32              | [3a9edbefac](https://linux-hardware.org/?probe=3a9edbefac) | Jul 06, 2021 |
| Acer          | Aspire A315-32              | [09f71bed72](https://linux-hardware.org/?probe=09f71bed72) | Jul 06, 2021 |
| Acer          | TravelMate 5520             | [d5e520d7a5](https://linux-hardware.org/?probe=d5e520d7a5) | Jul 05, 2021 |
| HP            | Laptop 17-cp0xxx            | [0bb97c100d](https://linux-hardware.org/?probe=0bb97c100d) | Jul 03, 2021 |
| HP            | Laptop 17-cp0xxx            | [4d60d86596](https://linux-hardware.org/?probe=4d60d86596) | Jul 02, 2021 |
| HP            | 620                         | [d46db3418c](https://linux-hardware.org/?probe=d46db3418c) | Jul 02, 2021 |
| Samsung       | RV408/RV508                 | [9c6043e9e1](https://linux-hardware.org/?probe=9c6043e9e1) | Jul 01, 2021 |
| MSI           | GL63 8RD                    | [87b563bdd7](https://linux-hardware.org/?probe=87b563bdd7) | Jul 01, 2021 |
| HP            | Laptop 14-cf3xxx            | [15589bda23](https://linux-hardware.org/?probe=15589bda23) | Jun 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Samsung       | RF712                       | [535f6d5c8b](https://linux-hardware.org/?probe=535f6d5c8b) | Jun 28, 2021 |
| HP            | ProBook 440 G5              | [d7bcf08f6a](https://linux-hardware.org/?probe=d7bcf08f6a) | Jun 26, 2021 |
| ASUSTek       | X441NA                      | [c3916da9d8](https://linux-hardware.org/?probe=c3916da9d8) | Jun 26, 2021 |
| Acer          | Aspire 1551                 | [ce4a36f7f8](https://linux-hardware.org/?probe=ce4a36f7f8) | Jun 26, 2021 |
| HP            | Laptop 15s-eq1xxx           | [d1d2e34e3c](https://linux-hardware.org/?probe=d1d2e34e3c) | Jun 25, 2021 |
| HP            | Pavilion 15                 | [425cadcae4](https://linux-hardware.org/?probe=425cadcae4) | Jun 25, 2021 |
| Dell          | Inspiron 3558               | [1ff1af9090](https://linux-hardware.org/?probe=1ff1af9090) | Jun 24, 2021 |
| HP            | Pavilion g6                 | [c5340daa46](https://linux-hardware.org/?probe=c5340daa46) | Jun 23, 2021 |
| Lenovo        | G500 20236                  | [55d0bea92e](https://linux-hardware.org/?probe=55d0bea92e) | Jun 19, 2021 |
| HP            | ProBook 440 G5              | [e72ef1f580](https://linux-hardware.org/?probe=e72ef1f580) | Jun 19, 2021 |
| HP            | ZBook Studio G4             | [231843ea67](https://linux-hardware.org/?probe=231843ea67) | Jun 17, 2021 |
| HP            | ZBook Studio G4             | [4e20cbff63](https://linux-hardware.org/?probe=4e20cbff63) | Jun 17, 2021 |
| TrekStor      | Notebook Slim S130          | [312670a9e8](https://linux-hardware.org/?probe=312670a9e8) | Jun 16, 2021 |
| TrekStor      | Notebook Slim S130          | [c5bd6200eb](https://linux-hardware.org/?probe=c5bd6200eb) | Jun 16, 2021 |
| HP            | ZBook Firefly 15 inch G8... | [784bcf8ace](https://linux-hardware.org/?probe=784bcf8ace) | Jun 16, 2021 |
| Apple         | MacBookAir1,1               | [8492ea1603](https://linux-hardware.org/?probe=8492ea1603) | Jun 15, 2021 |
| ASUSTek       | K42Jr                       | [303da80ebc](https://linux-hardware.org/?probe=303da80ebc) | Jun 15, 2021 |
| Apple         | MacBookAir1,1               | [79b77baeb0](https://linux-hardware.org/?probe=79b77baeb0) | Jun 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [2ade296868](https://linux-hardware.org/?probe=2ade296868) | Jun 13, 2021 |
| Lenovo        | G575 20081                  | [9ff42cacec](https://linux-hardware.org/?probe=9ff42cacec) | Jun 13, 2021 |
| Lenovo        | G575 20081                  | [7c640d46ae](https://linux-hardware.org/?probe=7c640d46ae) | Jun 13, 2021 |
| HP            | Laptop 15-db1xxx            | [ab3536f2c6](https://linux-hardware.org/?probe=ab3536f2c6) | Jun 13, 2021 |
| VINGA         | Iron S140                   | [24d0a16acd](https://linux-hardware.org/?probe=24d0a16acd) | Jun 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| Dell          | Latitude E7440              | [3f4df169bd](https://linux-hardware.org/?probe=3f4df169bd) | Jun 11, 2021 |
| HP            | Laptop 15-db1xxx            | [b012f183ba](https://linux-hardware.org/?probe=b012f183ba) | Jun 11, 2021 |
| ASUSTek       | X550EA                      | [71b07821f1](https://linux-hardware.org/?probe=71b07821f1) | Jun 10, 2021 |
| HP            | ZBook Studio G4             | [3eb6cb2692](https://linux-hardware.org/?probe=3eb6cb2692) | Jun 10, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [ced0fe43f9](https://linux-hardware.org/?probe=ced0fe43f9) | Jun 10, 2021 |
| HP            | Pavilion 15                 | [e765081506](https://linux-hardware.org/?probe=e765081506) | Jun 10, 2021 |
| HP            | Laptop 15-db1xxx            | [d0192aebbf](https://linux-hardware.org/?probe=d0192aebbf) | Jun 09, 2021 |
| Samsung       | RV420/RV520/RV720/E3530/... | [420b42aff1](https://linux-hardware.org/?probe=420b42aff1) | Jun 08, 2021 |
| HP            | ProBook 640 G1              | [c1e0152d09](https://linux-hardware.org/?probe=c1e0152d09) | Jun 07, 2021 |
| Acer          | AOD270                      | [b688b70a31](https://linux-hardware.org/?probe=b688b70a31) | Jun 06, 2021 |
| HP            | ProBook 440 G5              | [da7cac1d47](https://linux-hardware.org/?probe=da7cac1d47) | Jun 06, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| Samsung       | RV420/RV520/RV720/E3530/... | [866f4f571c](https://linux-hardware.org/?probe=866f4f571c) | Jun 04, 2021 |
| Toshiba       | Satellite R830              | [b4a3fd7cb5](https://linux-hardware.org/?probe=b4a3fd7cb5) | Jun 04, 2021 |
| Acer          | Swift SF314-51              | [9d864598e3](https://linux-hardware.org/?probe=9d864598e3) | Jun 04, 2021 |
| Lenovo        | ThinkPad X220 4290LD4       | [22bbadb3dd](https://linux-hardware.org/?probe=22bbadb3dd) | Jun 03, 2021 |
| HP            | 250 G5 Notebook PC          | [2af2de3d81](https://linux-hardware.org/?probe=2af2de3d81) | Jun 02, 2021 |
| Dell          | Latitude 5400               | [f9d1627578](https://linux-hardware.org/?probe=f9d1627578) | Jun 01, 2021 |
| ASUSTek       | N53SV                       | [438d785f0e](https://linux-hardware.org/?probe=438d785f0e) | May 31, 2021 |
| ASUSTek       | N53SV                       | [6cf318e0c6](https://linux-hardware.org/?probe=6cf318e0c6) | May 31, 2021 |
| Acer          | AO722                       | [8a6d18ebad](https://linux-hardware.org/?probe=8a6d18ebad) | May 30, 2021 |
| Acer          | AO722                       | [bc3de3323b](https://linux-hardware.org/?probe=bc3de3323b) | May 30, 2021 |
| HP            | 255 G4                      | [3b4e5a1eb8](https://linux-hardware.org/?probe=3b4e5a1eb8) | May 30, 2021 |
| HP            | 255 G4                      | [1752290f46](https://linux-hardware.org/?probe=1752290f46) | May 30, 2021 |
| Lenovo        | ThinkPad E520 1143RB2       | [daca4b86fc](https://linux-hardware.org/?probe=daca4b86fc) | May 30, 2021 |
| HP            | 250 G7 Notebook PC          | [fd62516fae](https://linux-hardware.org/?probe=fd62516fae) | May 27, 2021 |
| HP            | 250 G7 Notebook PC          | [13b8c23c4b](https://linux-hardware.org/?probe=13b8c23c4b) | May 27, 2021 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [b477bcb60d](https://linux-hardware.org/?probe=b477bcb60d) | May 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b108ce67c4](https://linux-hardware.org/?probe=b108ce67c4) | May 25, 2021 |
| HP            | Pavilion dv6                | [0ebad3acc3](https://linux-hardware.org/?probe=0ebad3acc3) | May 25, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1daf88898e](https://linux-hardware.org/?probe=1daf88898e) | May 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e1cf7f4599](https://linux-hardware.org/?probe=e1cf7f4599) | May 24, 2021 |
| HP            | ProBook 440 G5              | [6f74cda1dd](https://linux-hardware.org/?probe=6f74cda1dd) | May 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [887b6bc67e](https://linux-hardware.org/?probe=887b6bc67e) | May 22, 2021 |
| Dell          | Latitude 5480               | [c0b53e96ba](https://linux-hardware.org/?probe=c0b53e96ba) | May 22, 2021 |
| Dell          | Latitude 5480               | [d55095b7a4](https://linux-hardware.org/?probe=d55095b7a4) | May 22, 2021 |
| HP            | ProBook 440 G7              | [b249a9a615](https://linux-hardware.org/?probe=b249a9a615) | May 22, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e4abdb2d1c](https://linux-hardware.org/?probe=e4abdb2d1c) | May 21, 2021 |
| ASUSTek       | 1011PX                      | [2a34cdeec5](https://linux-hardware.org/?probe=2a34cdeec5) | May 20, 2021 |
| Acer          | Aspire A515-51G             | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| Lenovo        | ThinkPad P50 20EN0013US     | [88a08a450d](https://linux-hardware.org/?probe=88a08a450d) | May 20, 2021 |
| ASUSTek       | X75VD1                      | [86b1bacda3](https://linux-hardware.org/?probe=86b1bacda3) | May 19, 2021 |
| HP            | Laptop 15t-dy200            | [0f0078f0e3](https://linux-hardware.org/?probe=0f0078f0e3) | May 19, 2021 |
| HP            | 255 G4                      | [6484eef067](https://linux-hardware.org/?probe=6484eef067) | May 18, 2021 |
| HP            | Laptop 15t-dy200            | [9edadc2315](https://linux-hardware.org/?probe=9edadc2315) | May 18, 2021 |
| Dell          | Latitude 7400               | [660659882e](https://linux-hardware.org/?probe=660659882e) | May 17, 2021 |
| Dell          | Latitude 7400               | [4901f6b836](https://linux-hardware.org/?probe=4901f6b836) | May 17, 2021 |
| Dell          | Vostro 5568                 | [d7921837f3](https://linux-hardware.org/?probe=d7921837f3) | May 17, 2021 |
| Acer          | TravelMate 5744Z            | [07ab62ba49](https://linux-hardware.org/?probe=07ab62ba49) | May 16, 2021 |
| Lenovo        | IdeaPad 330S-15IKB GTX10... | [0f8a6b3dcf](https://linux-hardware.org/?probe=0f8a6b3dcf) | May 15, 2021 |
| HP            | Pavilion g6                 | [dab73003cd](https://linux-hardware.org/?probe=dab73003cd) | May 14, 2021 |
| HP            | Laptop 15s-eq0xxx           | [2ae02bc53f](https://linux-hardware.org/?probe=2ae02bc53f) | May 14, 2021 |
| Gateway       | NE71B                       | [aed5c08015](https://linux-hardware.org/?probe=aed5c08015) | May 11, 2021 |
| HP            | ProBook 440 G5              | [981f4b732a](https://linux-hardware.org/?probe=981f4b732a) | May 09, 2021 |
| Lenovo        | IdeaPad Z580                | [35eff85369](https://linux-hardware.org/?probe=35eff85369) | May 07, 2021 |
| HP            | 250 G6 Notebook PC          | [0193e32ca2](https://linux-hardware.org/?probe=0193e32ca2) | May 07, 2021 |
| HP            | 250 G6 Notebook PC          | [cee69d2935](https://linux-hardware.org/?probe=cee69d2935) | May 07, 2021 |
| Lenovo        | IdeaPad Z580                | [fc7dacb9ef](https://linux-hardware.org/?probe=fc7dacb9ef) | May 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [76b5d51559](https://linux-hardware.org/?probe=76b5d51559) | May 04, 2021 |
| Dell          | Inspiron 5570               | [3c5ffb0a02](https://linux-hardware.org/?probe=3c5ffb0a02) | May 04, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ukraine/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 215       | 10.08%  |
| ROSA R10          | 142       | 6.66%   |
| Ubuntu 18.04      | 117       | 5.49%   |
| ROSA R11          | 117       | 5.49%   |
| ROSA R8.1         | 97        | 4.55%   |
| ROSA R9           | 72        | 3.38%   |
| ROSA R11.1        | 68        | 3.19%   |
| ROSA R8           | 61        | 2.86%   |
| Ubuntu 22.04      | 32        | 1.5%    |
| OpenMandriva 4.2  | 32        | 1.5%    |
| ROSA 12.2         | 31        | 1.45%   |
| Linux Mint 19.3   | 30        | 1.41%   |
| KDE neon 20.04    | 29        | 1.36%   |
| Debian 11         | 26        | 1.22%   |
| Arch Rolling      | 26        | 1.22%   |
| Linux Mint 20     | 25        | 1.17%   |
| Arch              | 25        | 1.17%   |
| Manjaro           | 24        | 1.13%   |
| ROSA 12.4         | 23        | 1.08%   |
| Linux Mint 20.2   | 20        | 0.94%   |
| Debian 10         | 19        | 0.89%   |
| Ubuntu 19.10      | 18        | 0.84%   |
| Ubuntu 21.10      | 17        | 0.8%    |
| OpenMandriva 4.3  | 17        | 0.8%    |
| Linux Mint 20.1   | 17        | 0.8%    |
| Kubuntu 20.04     | 17        | 0.8%    |
| Linux Mint 19.2   | 16        | 0.75%   |
| Fedora 34         | 16        | 0.75%   |
| ArcoLinux Rolling | 16        | 0.75%   |
| Ubuntu 19.04      | 15        | 0.7%    |
| Xubuntu 18.04     | 14        | 0.66%   |
| Ubuntu 21.04      | 14        | 0.66%   |
| Linux Mint 20.3   | 14        | 0.66%   |
| Linux Mint 19.1   | 13        | 0.61%   |
| Linux Mint 18.3   | 13        | 0.61%   |
| Debian 12         | 13        | 0.61%   |
| Ubuntu 20.10      | 12        | 0.56%   |
| Fedora 33         | 12        | 0.56%   |
| Xubuntu 20.04     | 11        | 0.52%   |
| Ubuntu 24.04      | 11        | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| ROSA          | 563       | 28.38%  |
| Ubuntu        | 458       | 23.08%  |
| Linux Mint    | 174       | 8.77%   |
| Endless       | 98        | 4.94%   |
| Manjaro       | 89        | 4.49%   |
| Fedora        | 75        | 3.78%   |
| OpenMandriva  | 69        | 3.48%   |
| Debian        | 68        | 3.43%   |
| Arch          | 51        | 2.57%   |
| KDE neon      | 43        | 2.17%   |
| Kubuntu       | 37        | 1.86%   |
| Xubuntu       | 30        | 1.51%   |
| Pop!_OS       | 21        | 1.06%   |
| ArcoLinux     | 17        | 0.86%   |
| Elementary    | 15        | 0.76%   |
| Zorin         | 14        | 0.71%   |
| Gentoo        | 14        | 0.71%   |
| openSUSE      | 11        | 0.55%   |
| Lubuntu       | 11        | 0.55%   |
| Ubuntu MATE   | 10        | 0.5%    |
| SteamOS       | 10        | 0.5%    |
| Kali          | 10        | 0.5%    |
| Ubuntu Unity  | 8         | 0.4%    |
| LMDE          | 8         | 0.4%    |
| EndeavourOS   | 8         | 0.4%    |
| Clear Linux   | 8         | 0.4%    |
| MX            | 6         | 0.3%    |
| Ubuntu Budgie | 5         | 0.25%   |
| NixOS         | 5         | 0.25%   |
| Devuan        | 5         | 0.25%   |
| Void Linux    | 4         | 0.2%    |
| Linux Lite    | 4         | 0.2%    |
| CentOS        | 4         | 0.2%    |
| Artix         | 4         | 0.2%    |
| Nobara        | 3         | 0.15%   |
| UbuntuDDE     | 2         | 0.1%    |
| Solus         | 2         | 0.1%    |
| Red OS        | 2         | 0.1%    |
| GNOME OS      | 2         | 0.1%    |
| Sonar         | 1         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 57        | 2.52%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 56        | 2.48%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 42        | 1.86%   |
| 5.4.0-42-generic                    | 33        | 1.46%   |
| 5.10.14-desktop-1omv4002            | 32        | 1.42%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 29        | 1.28%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 26        | 1.15%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 25        | 1.11%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 24        | 1.06%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 19        | 0.84%   |
| 5.8.0-14-generic                    | 18        | 0.8%    |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 18        | 0.8%    |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 17        | 0.75%   |
| 5.4.0-58-generic                    | 15        | 0.66%   |
| 5.3.0-40-generic                    | 15        | 0.66%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 15        | 0.66%   |
| 4.18.0-15-generic                   | 15        | 0.66%   |
| 4.15.0-desktop-45.1rosa-i586        | 15        | 0.66%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 15        | 0.66%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 15        | 0.66%   |
| 5.4.0-52-generic                    | 14        | 0.62%   |
| 5.16.7-desktop-1omv4003             | 14        | 0.62%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 14        | 0.62%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 14        | 0.62%   |
| 5.4.0-48-generic                    | 13        | 0.58%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 13        | 0.58%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 13        | 0.58%   |
| 5.4.0-19-generic                    | 12        | 0.53%   |
| 5.3.0-28-generic                    | 12        | 0.53%   |
| 5.4.83-generic-2rosa-x86_64         | 11        | 0.49%   |
| 5.4.0-26-generic                    | 11        | 0.49%   |
| 5.3.0-46-generic                    | 11        | 0.49%   |
| 5.3.0-42-generic                    | 11        | 0.49%   |
| 5.11.0-43-generic                   | 11        | 0.49%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 11        | 0.49%   |
| 5.0.0-32-generic                    | 11        | 0.49%   |
| 5.4.0-91-generic                    | 10        | 0.44%   |
| 5.4.0-65-generic                    | 10        | 0.44%   |
| 5.4.0-29-generic                    | 10        | 0.44%   |
| 5.3.0-51-generic                    | 10        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 272       | 12.4%   |
| 4.15.0   | 266       | 12.13%  |
| 5.8.0    | 100       | 4.56%   |
| 5.3.0    | 93        | 4.24%   |
| 4.9.60   | 82        | 3.74%   |
| 5.11.0   | 69        | 3.15%   |
| 4.9.20   | 69        | 3.15%   |
| 5.0.0    | 60        | 2.74%   |
| 5.15.0   | 50        | 2.28%   |
| 5.13.0   | 49        | 2.23%   |
| 4.18.0   | 45        | 2.05%   |
| 4.1.34   | 44        | 2.01%   |
| 4.9.124  | 33        | 1.5%    |
| 5.10.14  | 32        | 1.46%   |
| 5.10.0   | 32        | 1.46%   |
| 4.9.9    | 32        | 1.46%   |
| 5.10.74  | 27        | 1.23%   |
| 4.19.0   | 27        | 1.23%   |
| 4.1.38   | 27        | 1.23%   |
| 4.9.41   | 23        | 1.05%   |
| 6.8.0    | 21        | 0.96%   |
| 4.9.76   | 20        | 0.91%   |
| 5.4.83   | 19        | 0.87%   |
| 4.13.0   | 19        | 0.87%   |
| 5.16.7   | 17        | 0.78%   |
| 4.9.155  | 16        | 0.73%   |
| 6.1.0    | 15        | 0.68%   |
| 5.4.32   | 14        | 0.64%   |
| 5.19.0   | 14        | 0.64%   |
| 5.10.71  | 11        | 0.5%    |
| 6.2.0    | 10        | 0.46%   |
| 4.9.95   | 10        | 0.46%   |
| 6.1.20   | 9         | 0.41%   |
| 5.10.118 | 9         | 0.41%   |
| 5.9.16   | 8         | 0.36%   |
| 4.1.25   | 8         | 0.36%   |
| 6.1.52   | 7         | 0.32%   |
| 4.9.87   | 7         | 0.32%   |
| 6.5.0    | 6         | 0.27%   |
| 5.8.11   | 6         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 324       | 15.23%  |
| 4.9     | 281       | 13.21%  |
| 4.15    | 266       | 12.51%  |
| 5.10    | 158       | 7.43%   |
| 5.8     | 127       | 5.97%   |
| 5.3     | 102       | 4.8%    |
| 5.11    | 84        | 3.95%   |
| 5.15    | 79        | 3.71%   |
| 4.1     | 76        | 3.57%   |
| 5.13    | 67        | 3.15%   |
| 5.0     | 62        | 2.91%   |
| 6.1     | 51        | 2.4%    |
| 4.18    | 46        | 2.16%   |
| 4.19    | 35        | 1.65%   |
| 5.16    | 33        | 1.55%   |
| 6.8     | 27        | 1.27%   |
| 5.14    | 27        | 1.27%   |
| 5.6     | 25        | 1.18%   |
| 6.6     | 24        | 1.13%   |
| 4.13    | 20        | 0.94%   |
| 6.2     | 19        | 0.89%   |
| 5.9     | 19        | 0.89%   |
| 5.12    | 17        | 0.8%    |
| 5.19    | 16        | 0.75%   |
| 6.5     | 14        | 0.66%   |
| 6.10    | 13        | 0.61%   |
| 5.17    | 13        | 0.61%   |
| 5.5     | 12        | 0.56%   |
| 6.4     | 10        | 0.47%   |
| 4.14    | 9         | 0.42%   |
| 6.0     | 8         | 0.38%   |
| 5.7     | 7         | 0.33%   |
| 4.4     | 7         | 0.33%   |
| 6.9     | 5         | 0.24%   |
| 6.11    | 5         | 0.24%   |
| 5.18    | 5         | 0.24%   |
| 5.2     | 4         | 0.19%   |
| 5.1     | 4         | 0.19%   |
| 4.8     | 4         | 0.19%   |
| 4.10    | 4         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1744      | 89.71%  |
| i686    | 199       | 10.24%  |
| aarch64 | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 592       | 29.15%  |
| KDE4             | 366       | 18.02%  |
| KDE5             | 344       | 16.94%  |
| Unknown          | 234       | 11.52%  |
| XFCE             | 110       | 5.42%   |
| X-Cinnamon       | 76        | 3.74%   |
| MATE             | 59        | 2.9%    |
| Cinnamon         | 59        | 2.9%    |
| KDE              | 56        | 2.76%   |
| LXQt             | 53        | 2.61%   |
| i3               | 15        | 0.74%   |
| Pantheon         | 13        | 0.64%   |
| Unity            | 8         | 0.39%   |
| LXDE             | 7         | 0.34%   |
| KDE6             | 7         | 0.34%   |
| GNOME Flashback  | 5         | 0.25%   |
| Budgie           | 5         | 0.25%   |
| Deepin           | 4         | 0.2%    |
| openbox          | 3         | 0.15%   |
| GNOME Classic    | 3         | 0.15%   |
| xmonad           | 2         | 0.1%    |
| Hyprland         | 2         | 0.1%    |
| bspwm            | 2         | 0.1%    |
| qtile            | 1         | 0.05%   |
| none+i3          | 1         | 0.05%   |
| lightdm-xsession | 1         | 0.05%   |
| i3-with-shmlog   | 1         | 0.05%   |
| fluxbox          | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1582      | 80.14%  |
| Wayland | 261       | 13.22%  |
| Unknown | 124       | 6.28%   |
| Tty     | 7         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 711       | 35.08%  |
| KDM     | 368       | 18.15%  |
| SDDM    | 364       | 17.96%  |
| GDM     | 243       | 11.99%  |
| LightDM | 138       | 6.81%   |
| TDM     | 112       | 5.53%   |
| GDM3    | 74        | 3.65%   |
| MDM     | 6         | 0.3%    |
| XDM     | 5         | 0.25%   |
| SLiM    | 2         | 0.1%    |
| GREETD  | 2         | 0.1%    |
| LY-DM   | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 670       | 33.53%  |
| en_US       | 521       | 26.08%  |
| ru_RU       | 339       | 16.97%  |
| ru_UA       | 271       | 13.56%  |
| uk_UA       | 130       | 6.51%   |
| C           | 32        | 1.6%    |
| en_GB       | 15        | 0.75%   |
| ru_RU.UTF_8 | 7         | 0.35%   |
| hu_HU       | 2         | 0.1%    |
| es_ES       | 2         | 0.1%    |
| en_CA       | 2         | 0.1%    |
| POSIX       | 1         | 0.05%   |
| fr_FR       | 1         | 0.05%   |
| en_ZA       | 1         | 0.05%   |
| en_IE       | 1         | 0.05%   |
| en_AG       | 1         | 0.05%   |
| de_DE       | 1         | 0.05%   |
| C.UTF8      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1056      | 53.44%  |
| EFI  | 920       | 46.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1351      | 67.65%  |
| Unknown | 382       | 19.13%  |
| Btrfs   | 134       | 6.71%   |
| Overlay | 81        | 4.06%   |
| Tmpfs   | 19        | 0.95%   |
| Xfs     | 10        | 0.5%    |
| Zfs     | 9         | 0.45%   |
| Ext3    | 6         | 0.3%    |
| Ext2    | 3         | 0.15%   |
| F2fs    | 2         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 858       | 42.81%  |
| GPT     | 645       | 32.19%  |
| MBR     | 501       | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1738      | 88%     |
| Yes       | 237       | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1440      | 72.11%  |
| Yes       | 557       | 27.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 406       | 20.98%  |
| Hewlett-Packard      | 387       | 20%     |
| ASUSTek Computer     | 363       | 18.76%  |
| Acer                 | 253       | 13.07%  |
| Dell                 | 202       | 10.44%  |
| Samsung Electronics  | 63        | 3.26%   |
| Timi                 | 29        | 1.5%    |
| MSI                  | 29        | 1.5%    |
| Toshiba              | 24        | 1.24%   |
| Apple                | 17        | 0.88%   |
| Fujitsu              | 13        | 0.67%   |
| Sony                 | 12        | 0.62%   |
| eMachines            | 11        | 0.57%   |
| Valve                | 10        | 0.52%   |
| Packard Bell         | 8         | 0.41%   |
| Fujitsu Siemens      | 8         | 0.41%   |
| HUAWEI               | 6         | 0.31%   |
| Unknown              | 6         | 0.31%   |
| Google               | 5         | 0.26%   |
| Gigabyte Technology  | 5         | 0.26%   |
| VINGA                | 4         | 0.21%   |
| HONOR                | 4         | 0.21%   |
| Chuwi                | 4         | 0.21%   |
| Shuttle              | 3         | 0.16%   |
| Notebook             | 3         | 0.16%   |
| Navigator            | 3         | 0.16%   |
| Medion               | 3         | 0.16%   |
| THUNDEROBOT          | 2         | 0.1%    |
| TECNO Mobile Limited | 2         | 0.1%    |
| Razer                | 2         | 0.1%    |
| Prestigio            | 2         | 0.1%    |
| Pixus                | 2         | 0.1%    |
| Minix                | 2         | 0.1%    |
| LG Electronics       | 2         | 0.1%    |
| Irbis                | 2         | 0.1%    |
| Hampoo               | 2         | 0.1%    |
| Gateway              | 2         | 0.1%    |
| Dream Machines       | 2         | 0.1%    |
| AMI                  | 2         | 0.1%    |
| Xplore               | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Pavilion g6                             | 24        | 1.24%   |
| Unknown                                    | 14        | 0.72%   |
| Lenovo G500 20236                          | 13        | 0.67%   |
| HP Pavilion dv6                            | 12        | 0.62%   |
| HP Pavilion 15                             | 12        | 0.62%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 12        | 0.62%   |
| Acer Aspire V3-571G                        | 8         | 0.41%   |
| Valve Jupiter                              | 7         | 0.36%   |
| Lenovo V580c 20160                         | 7         | 0.36%   |
| Lenovo IdeaPad Z580                        | 7         | 0.36%   |
| Lenovo IdeaPad Z510 20287                  | 7         | 0.36%   |
| Lenovo G580 20150                          | 7         | 0.36%   |
| HP 250 G5 Notebook PC                      | 7         | 0.36%   |
| Samsung R59P/R60P/R61P                     | 6         | 0.31%   |
| Samsung R528/R728                          | 6         | 0.31%   |
| Lenovo G580 20157                          | 6         | 0.31%   |
| Lenovo G550 20023                          | 6         | 0.31%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 6         | 0.31%   |
| HP Pavilion g7                             | 6         | 0.31%   |
| HP Notebook                                | 6         | 0.31%   |
| HP Laptop 15-bw0xx                         | 6         | 0.31%   |
| HP 620                                     | 6         | 0.31%   |
| HP 255 G7 Notebook PC                      | 6         | 0.31%   |
| HP 250 G4                                  | 6         | 0.31%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 6         | 0.31%   |
| Lenovo S10-3                               | 5         | 0.26%   |
| Lenovo IdeaPad S340-14API 81NB             | 5         | 0.26%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 5         | 0.26%   |
| HP ZBook 15v G5                            | 5         | 0.26%   |
| HP ProBook 650 G1                          | 5         | 0.26%   |
| HP ProBook 450 G7                          | 5         | 0.26%   |
| HP ProBook 450 G6                          | 5         | 0.26%   |
| HP ProBook 440 G7                          | 5         | 0.26%   |
| HP Laptop 15s-eq1xxx                       | 5         | 0.26%   |
| HP 250 G6 Notebook PC                      | 5         | 0.26%   |
| Dell Vostro 15-3568                        | 5         | 0.26%   |
| Dell Inspiron N5010                        | 5         | 0.26%   |
| Dell Inspiron 3582                         | 5         | 0.26%   |
| Dell Inspiron 3576                         | 5         | 0.26%   |
| ASUS VivoBook 15_ASUS Laptop X540MB_X540MB | 5         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 150       | 7.75%   |
| Lenovo IdeaPad        | 129       | 6.67%   |
| Lenovo ThinkPad       | 108       | 5.58%   |
| HP Pavilion           | 95        | 4.91%   |
| HP ProBook            | 93        | 4.81%   |
| ASUS VivoBook         | 90        | 4.65%   |
| Dell Inspiron         | 85        | 4.39%   |
| Dell Latitude         | 54        | 2.79%   |
| HP Laptop             | 44        | 2.27%   |
| Acer Swift            | 32        | 1.65%   |
| HP EliteBook          | 29        | 1.5%    |
| HP 250                | 26        | 1.34%   |
| HP ZBook              | 24        | 1.24%   |
| Dell Vostro           | 24        | 1.24%   |
| Toshiba Satellite     | 19        | 0.98%   |
| Acer TravelMate       | 17        | 0.88%   |
| HP Compaq             | 16        | 0.83%   |
| Acer Nitro            | 16        | 0.83%   |
| Acer Extensa          | 16        | 0.83%   |
| Lenovo Legion         | 15        | 0.78%   |
| ASUS ROG              | 15        | 0.78%   |
| Lenovo ThinkBook      | 14        | 0.72%   |
| Lenovo G580           | 14        | 0.72%   |
| HP 255                | 14        | 0.72%   |
| Unknown               | 14        | 0.72%   |
| Lenovo G500           | 13        | 0.67%   |
| Timi RedmiBook        | 12        | 0.62%   |
| Fujitsu LIFEBOOK      | 12        | 0.62%   |
| Dell Precision        | 12        | 0.62%   |
| Dell XPS              | 11        | 0.57%   |
| ASUS ASUS             | 9         | 0.47%   |
| Valve Jupiter         | 7         | 0.36%   |
| Packard Bell EasyNote | 7         | 0.36%   |
| Lenovo V580c          | 7         | 0.36%   |
| Lenovo B590           | 7         | 0.36%   |
| HP Presario           | 7         | 0.36%   |
| Samsung R59P          | 6         | 0.31%   |
| Samsung R528          | 6         | 0.31%   |
| Lenovo G550           | 6         | 0.31%   |
| HP Notebook           | 6         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 203       | 10.49%  |
| 2011    | 200       | 10.34%  |
| 2018    | 174       | 8.99%   |
| 2019    | 162       | 8.37%   |
| 2017    | 149       | 7.7%    |
| 2013    | 149       | 7.7%    |
| 2010    | 132       | 6.82%   |
| 2020    | 123       | 6.36%   |
| 2015    | 95        | 4.91%   |
| 2016    | 92        | 4.75%   |
| 2021    | 89        | 4.6%    |
| 2009    | 77        | 3.98%   |
| 2008    | 67        | 3.46%   |
| 2007    | 67        | 3.46%   |
| 2014    | 65        | 3.36%   |
| 2023    | 27        | 1.4%    |
| 2006    | 25        | 1.29%   |
| 2022    | 23        | 1.19%   |
| 2005    | 11        | 0.57%   |
| 2024    | 4         | 0.21%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1935      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1824      | 93.73%  |
| Enabled  | 122       | 6.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1928      | 99.64%  |
| Yes  | 7         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 523       | 26.6%   |
| 3.01-4.0    | 486       | 24.72%  |
| 8.01-16.0   | 303       | 15.41%  |
| 16.01-24.0  | 270       | 13.73%  |
| 1.01-2.0    | 171       | 8.7%    |
| 2.01-3.0    | 92        | 4.68%   |
| 32.01-64.0  | 73        | 3.71%   |
| 0.51-1.0    | 24        | 1.22%   |
| 24.01-32.0  | 13        | 0.66%   |
| 64.01-256.0 | 7         | 0.36%   |
| 0.01-0.5    | 4         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 701       | 32.9%   |
| 2.01-3.0   | 449       | 21.07%  |
| 0.51-1.0   | 351       | 16.47%  |
| 4.01-8.0   | 272       | 12.76%  |
| 3.01-4.0   | 225       | 10.56%  |
| 8.01-16.0  | 80        | 3.75%   |
| 0.01-0.5   | 43        | 2.02%   |
| 16.01-24.0 | 7         | 0.33%   |
| Unknown    | 2         | 0.09%   |
| 24.01-32.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1515      | 77.02%  |
| 2      | 395       | 20.08%  |
| 3      | 39        | 1.98%   |
| 0      | 12        | 0.61%   |
| 4      | 5         | 0.25%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1213      | 62.37%  |
| Yes       | 732       | 37.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1629      | 84.01%  |
| No        | 310       | 15.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1902      | 98.29%  |
| No        | 33        | 1.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1464      | 74.66%  |
| No        | 497       | 25.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ukraine | 1935      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Kyiv            | 501       | 24.81%  |
| Kharkiv         | 118       | 5.84%   |
| Lviv            | 89        | 4.41%   |
| Simferopol      | 88        | 4.36%   |
| Odessa          | 84        | 4.16%   |
| Dnipro          | 84        | 4.16%   |
| Sevastopol      | 79        | 3.91%   |
| Donetsk         | 61        | 3.02%   |
| Vinnytsia       | 28        | 1.39%   |
| Zaporizhzhya    | 25        | 1.24%   |
| Mykolayiv       | 25        | 1.24%   |
| Cherkasy        | 24        | 1.19%   |
| Zaporizhzhia    | 23        | 1.14%   |
| Ternopil        | 23        | 1.14%   |
| Poltava         | 21        | 1.04%   |
| Chernihiv       | 21        | 1.04%   |
| Mariupol        | 20        | 0.99%   |
| Kryvyi Rih      | 20        | 0.99%   |
| Ivano-Frankivsk | 19        | 0.94%   |
| Yalta           | 18        | 0.89%   |
| Odesa           | 18        | 0.89%   |
| Kherson         | 17        | 0.84%   |
| Kremenchug      | 16        | 0.79%   |
| Yasinovataya    | 13        | 0.64%   |
| Luhansk         | 13        | 0.64%   |
| Horlivka        | 13        | 0.64%   |
| Zhytomyr        | 12        | 0.59%   |
| Rivne           | 12        | 0.59%   |
| Irpin           | 12        | 0.59%   |
| Uzhhorod        | 11        | 0.54%   |
| Sumy            | 11        | 0.54%   |
| Novopskov       | 11        | 0.54%   |
| Mykytyn Rog     | 10        | 0.5%    |
| Yevpatoriya     | 9         | 0.45%   |
| Pavlohrad       | 9         | 0.45%   |
| Kramatorsk      | 9         | 0.45%   |
| Syeverodonets'k | 8         | 0.4%    |
| Osipenko        | 8         | 0.4%    |
| Brovary         | 8         | 0.4%    |
| Nova Kakhovka   | 7         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 362       | 450    | 15.26%  |
| WDC                         | 334       | 393    | 14.08%  |
| Samsung Electronics         | 285       | 346    | 12.02%  |
| Toshiba                     | 221       | 275    | 9.32%   |
| Kingston                    | 151       | 176    | 6.37%   |
| Hitachi                     | 130       | 165    | 5.48%   |
| Unknown                     | 105       | 128    | 4.43%   |
| SK hynix                    | 90        | 107    | 3.79%   |
| HGST                        | 89        | 112    | 3.75%   |
| SanDisk                     | 74        | 90     | 3.12%   |
| Intel                       | 69        | 89     | 2.91%   |
| Micron Technology           | 52        | 68     | 2.19%   |
| GOODRAM                     | 41        | 45     | 1.73%   |
| KIOXIA                      | 26        | 32     | 1.1%    |
| Apacer                      | 24        | 25     | 1.01%   |
| Patriot                     | 22        | 25     | 0.93%   |
| Transcend                   | 19        | 24     | 0.8%    |
| A-DATA Technology           | 19        | 21     | 0.8%    |
| Crucial                     | 18        | 19     | 0.76%   |
| SPCC                        | 17        | 22     | 0.72%   |
| China                       | 17        | 18     | 0.72%   |
| LITEON                      | 14        | 16     | 0.59%   |
| Apple                       | 12        | 15     | 0.51%   |
| Team                        | 11        | 11     | 0.46%   |
| Kingston Technology Company | 9         | 9      | 0.38%   |
| JMicron Technology          | 9         | 8      | 0.38%   |
| Phison Electronics          | 8         | 8      | 0.34%   |
| Fujitsu                     | 8         | 8      | 0.34%   |
| LITEONIT                    | 7         | 8      | 0.3%    |
| StoreJet                    | 6         | 6      | 0.25%   |
| Silicon Motion              | 6         | 7      | 0.25%   |
| OCZ                         | 6         | 6      | 0.25%   |
| Phison                      | 5         | 7      | 0.21%   |
| KingSpec                    | 5         | 5      | 0.21%   |
| Gigabyte Technology         | 5         | 6      | 0.21%   |
| AMD                         | 5         | 6      | 0.21%   |
| Yangtze Memory Technologies | 4         | 5      | 0.17%   |
| UMIS                        | 4         | 4      | 0.17%   |
| Plextor                     | 4         | 5      | 0.17%   |
| Netac                       | 4         | 4      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 67        | 2.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 52        | 2.14%   |
| Toshiba MQ01ABF050 500GB              | 45        | 1.85%   |
| Seagate ST9500325AS 500GB             | 34        | 1.4%    |
| Seagate ST500LT012-1DG142 500GB       | 33        | 1.36%   |
| Toshiba MQ01ABD100 1TB                | 30        | 1.23%   |
| Toshiba MQ04ABF100 1TB                | 23        | 0.95%   |
| Kingston SA400S37240G 240GB SSD       | 21        | 0.86%   |
| HGST HTS545050A7E680 500GB            | 19        | 0.78%   |
| Samsung NVMe SSD Drive 256GB          | 18        | 0.74%   |
| Kingston SA400S37120G 120GB SSD       | 18        | 0.74%   |
| Seagate ST9320325AS 320GB             | 16        | 0.66%   |
| Seagate ST500LT012-9WS142 500GB       | 16        | 0.66%   |
| HGST HTS721010A9E630 1TB              | 16        | 0.66%   |
| Unknown MMC Card  64GB                | 14        | 0.58%   |
| Hitachi HTS543232A7A384 320GB         | 14        | 0.58%   |
| Intel NVMe SSD Drive 512GB            | 13        | 0.53%   |
| WDC WD10SPZX-21Z10T0 1TB              | 12        | 0.49%   |
| SK hynix NVMe SSD Drive 256GB         | 12        | 0.49%   |
| Seagate ST9250315AS 250GB             | 12        | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 12        | 0.49%   |
| Samsung SSD 860 EVO 250GB             | 12        | 0.49%   |
| Patriot Burst 120GB SSD               | 12        | 0.49%   |
| HGST HTS545050A7E380 500GB            | 12        | 0.49%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 11        | 0.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 11        | 0.45%   |
| Unknown MMC Card  32GB                | 11        | 0.45%   |
| Samsung SSD 860 EVO 500GB             | 11        | 0.45%   |
| Samsung NVMe SSD Drive 512GB          | 11        | 0.45%   |
| Hitachi HTS545050B9A300 500GB         | 11        | 0.45%   |
| Hitachi HTS545050A7E380 500GB         | 11        | 0.45%   |
| Hitachi HTS545032B9A300 320GB         | 11        | 0.45%   |
| HGST HTS541010A9E680 1TB              | 11        | 0.45%   |
| GOODRAM SSD 120GB                     | 11        | 0.45%   |
| SanDisk NVMe SSD Drive 512GB          | 10        | 0.41%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 10        | 0.41%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 9         | 0.37%   |
| Toshiba MQ01ABD050 500GB              | 9         | 0.37%   |
| SK hynix NVMe SSD Drive 512GB         | 9         | 0.37%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 9         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 360       | 445    | 32.7%   |
| WDC                 | 280       | 321    | 25.43%  |
| Toshiba             | 184       | 229    | 16.71%  |
| Hitachi             | 130       | 165    | 11.81%  |
| HGST                | 89        | 112    | 8.08%   |
| Samsung Electronics | 33        | 40     | 3%      |
| Fujitsu             | 8         | 8      | 0.73%   |
| JMicron Technology  | 6         | 6      | 0.54%   |
| Unknown             | 2         | 3      | 0.18%   |
| HGST HTS            | 2         | 2      | 0.18%   |
| Apple               | 2         | 2      | 0.18%   |
| USB                 | 1         | 1      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |
| SILICONMOTION       | 1         | 1      | 0.09%   |
| SAGE                | 1         | 1      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 125       | 153    | 18.85%  |
| Kingston            | 117       | 137    | 17.65%  |
| SanDisk             | 40        | 49     | 6.03%   |
| GOODRAM             | 39        | 43     | 5.88%   |
| SK hynix            | 26        | 32     | 3.92%   |
| Micron Technology   | 25        | 29     | 3.77%   |
| Apacer              | 24        | 25     | 3.62%   |
| Patriot             | 22        | 25     | 3.32%   |
| Intel               | 20        | 25     | 3.02%   |
| Transcend           | 19        | 24     | 2.87%   |
| Crucial             | 18        | 19     | 2.71%   |
| SPCC                | 17        | 22     | 2.56%   |
| China               | 17        | 18     | 2.56%   |
| A-DATA Technology   | 17        | 19     | 2.56%   |
| WDC                 | 14        | 17     | 2.11%   |
| LITEON              | 13        | 15     | 1.96%   |
| Team                | 11        | 11     | 1.66%   |
| Toshiba             | 10        | 15     | 1.51%   |
| Apple               | 8         | 8      | 1.21%   |
| LITEONIT            | 7         | 8      | 1.06%   |
| OCZ                 | 6         | 6      | 0.9%    |
| StoreJet            | 5         | 5      | 0.75%   |
| Gigabyte Technology | 5         | 6      | 0.75%   |
| AMD                 | 4         | 5      | 0.6%    |
| Plextor             | 3         | 4      | 0.45%   |
| Netac               | 3         | 3      | 0.45%   |
| Leven               | 3         | 3      | 0.45%   |
| KingSpec            | 3         | 3      | 0.45%   |
| Verbatim            | 2         | 2      | 0.3%    |
| USB3.0              | 2         | 2      | 0.3%    |
| Unknown             | 2         | 2      | 0.3%    |
| KingDian            | 2         | 2      | 0.3%    |
| Indilinx            | 2         | 2      | 0.3%    |
| DeTech              | 2         | 3      | 0.3%    |
| XrayDisk            | 1         | 1      | 0.15%   |
| WHALEKOM            | 1         | 1      | 0.15%   |
| UNIC2               | 1         | 1      | 0.15%   |
| Teclast             | 1         | 1      | 0.15%   |
| SSSTC               | 1         | 1      | 0.15%   |
| SILICONMOTION       | 1         | 2      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1074      | 1338   | 46.78%  |
| SSD     | 627       | 775    | 27.31%  |
| NVMe    | 479       | 603    | 20.86%  |
| MMC     | 98        | 123    | 4.27%   |
| Unknown | 18        | 18     | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1487      | 2086   | 70.57%  |
| NVMe | 478       | 602    | 22.69%  |
| MMC  | 98        | 123    | 4.65%   |
| SAS  | 44        | 46     | 2.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1186      | 1554   | 72.58%  |
| 0.51-1.0   | 424       | 530    | 25.95%  |
| 1.01-2.0   | 22        | 26     | 1.35%   |
| 3.01-4.0   | 1         | 2      | 0.06%   |
| 4.01-10.0  | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 600       | 29.1%   |
| 251-500        | 570       | 27.64%  |
| 501-1000       | 267       | 12.95%  |
| 51-100         | 178       | 8.63%   |
| 1-20           | 173       | 8.39%   |
| 21-50          | 151       | 7.32%   |
| 1001-2000      | 73        | 3.54%   |
| Unknown        | 30        | 1.45%   |
| More than 3000 | 12        | 0.58%   |
| 2001-3000      | 8         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 946       | 45.07%  |
| 21-50          | 381       | 18.15%  |
| 51-100         | 265       | 12.63%  |
| 101-250        | 251       | 11.96%  |
| 251-500        | 140       | 6.67%   |
| 501-1000       | 68        | 3.24%   |
| Unknown        | 30        | 1.43%   |
| 1001-2000      | 12        | 0.57%   |
| More than 3000 | 4         | 0.19%   |
| 2001-3000      | 2         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 19        | 22     | 5.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 23     | 3.99%   |
| Seagate ST9320325AS 320GB           | 11        | 11     | 2.93%   |
| Seagate ST500LT012-1DG142 500GB     | 11        | 12     | 2.93%   |
| Hitachi HTS543232A7A384 320GB       | 11        | 12     | 2.93%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 12     | 2.66%   |
| Seagate ST9250315AS 250GB           | 8         | 9      | 2.13%   |
| HGST HTS545050A7E680 500GB          | 7         | 9      | 1.86%   |
| Toshiba MQ01ABD050 500GB            | 6         | 8      | 1.6%    |
| Toshiba MQ01ABD100 1TB              | 5         | 5      | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 1.33%   |
| Hitachi HTS545050A7E380 500GB       | 5         | 5      | 1.33%   |
| Hitachi HTS545032B9A300 320GB       | 5         | 7      | 1.33%   |
| Hitachi HTS542516K9SA00 160GB       | 5         | 5      | 1.33%   |
| HGST HTS545050A7E380 500GB          | 5         | 5      | 1.33%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 4         | 5      | 1.06%   |
| WDC WD3200BEVT-22A23T0 320GB        | 4         | 4      | 1.06%   |
| Seagate ST9500420AS 500GB           | 4         | 4      | 1.06%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 4         | 4      | 1.06%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 7      | 1.06%   |
| Seagate ST320LT020-9YG142 320GB     | 4         | 5      | 1.06%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 5      | 1.06%   |
| Hitachi HTS541612J9SA00 120GB       | 4         | 4      | 1.06%   |
| Toshiba MK2555GSX 250GB             | 3         | 3      | 0.8%    |
| Seagate ST9160821AS 160GB           | 3         | 3      | 0.8%    |
| Seagate ST1000LM014-1EJ164 1TB      | 3         | 4      | 0.8%    |
| Samsung Electronics HM160HI 160GB   | 3         | 3      | 0.8%    |
| Hitachi HTS543232L9A300 320GB       | 3         | 4      | 0.8%    |
| HGST HTS541010A9E680 1TB            | 3         | 4      | 0.8%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 0.53%   |
| WDC WD6400BPVT-80HXZT3 640GB        | 2         | 2      | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.53%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 3      | 0.53%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 2         | 2      | 0.53%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 2         | 2      | 0.53%   |
| WDC WD3200BPVT-16JJ5T0 320GB        | 2         | 2      | 0.53%   |
| WDC WD3200BEVT-60A23T0 320GB        | 2         | 2      | 0.53%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.53%   |
| WDC WD2500BEVT-60A23T0 250GB        | 2         | 2      | 0.53%   |
| Toshiba MQ01ABF050 500GB            | 2         | 3      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 131       | 158    | 34.93%  |
| Hitachi                     | 67        | 91     | 17.87%  |
| WDC                         | 66        | 73     | 17.6%   |
| Toshiba                     | 43        | 54     | 11.47%  |
| HGST                        | 17        | 21     | 4.53%   |
| Samsung Electronics         | 14        | 15     | 3.73%   |
| SanDisk                     | 5         | 7      | 1.33%   |
| SK hynix                    | 4         | 4      | 1.07%   |
| A-DATA Technology           | 4         | 4      | 1.07%   |
| Kingston                    | 3         | 4      | 0.8%    |
| OCZ                         | 2         | 2      | 0.53%   |
| LITEON                      | 2         | 3      | 0.53%   |
| Fujitsu                     | 2         | 2      | 0.53%   |
| China                       | 2         | 2      | 0.53%   |
| Team                        | 1         | 1      | 0.27%   |
| Netac                       | 1         | 1      | 0.27%   |
| Micron Technology           | 1         | 1      | 0.27%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.27%   |
| LS                          | 1         | 1      | 0.27%   |
| LITEONIT                    | 1         | 1      | 0.27%   |
| KingSpec                    | 1         | 1      | 0.27%   |
| JDa                         | 1         | 1      | 0.27%   |
| IBM/Hitachi                 | 1         | 1      | 0.27%   |
| HGST HTS                    | 1         | 1      | 0.27%   |
| DeTech                      | 1         | 1      | 0.27%   |
| Crucial                     | 1         | 1      | 0.27%   |
| Apple                       | 1         | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 131       | 158    | 38.76%  |
| Hitachi             | 67        | 91     | 19.82%  |
| WDC                 | 64        | 71     | 18.93%  |
| Toshiba             | 43        | 54     | 12.72%  |
| HGST                | 17        | 21     | 5.03%   |
| Samsung Electronics | 12        | 13     | 3.55%   |
| Fujitsu             | 2         | 2      | 0.59%   |
| IBM/Hitachi         | 1         | 1      | 0.3%    |
| HGST HTS            | 1         | 1      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 332       | 412    | 89.97%  |
| SSD  | 33        | 37     | 8.94%   |
| NVMe | 4         | 4      | 1.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 2         | 4      | 22.22%  |
| WDC WD3200BEVT-24A23T0 320GB          | 1         | 1      | 11.11%  |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1      | 11.11%  |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 11.11%  |
| Seagate ST9250315AS 250GB             | 1         | 1      | 11.11%  |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 11.11%  |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 11.11%  |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 44.44%  |
| WDC                 | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Intel               | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 891       | 1210   | 42.37%  |
| Detected | 837       | 1183   | 39.8%   |
| Malfunc  | 366       | 453    | 17.4%   |
| Failed   | 9         | 11     | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1432      | 65.18%  |
| AMD                              | 287       | 13.06%  |
| Samsung Electronics              | 138       | 6.28%   |
| SanDisk                          | 70        | 3.19%   |
| SK hynix                         | 62        | 2.82%   |
| Kingston Technology Company      | 41        | 1.87%   |
| Micron Technology                | 28        | 1.27%   |
| KIOXIA                           | 28        | 1.27%   |
| Toshiba America Info Systems     | 27        | 1.23%   |
| Phison Electronics               | 14        | 0.64%   |
| Union Memory (Shenzhen)          | 12        | 0.55%   |
| Nvidia                           | 11        | 0.5%    |
| Silicon Motion                   | 8         | 0.36%   |
| Silicon Integrated Systems [SiS] | 7         | 0.32%   |
| Yangtze Memory Technologies      | 5         | 0.23%   |
| ADATA Technology                 | 5         | 0.23%   |
| Shenzhen Longsys Electronics     | 4         | 0.18%   |
| Lite-On Technology               | 4         | 0.18%   |
| VIA Technologies                 | 3         | 0.14%   |
| Solid State Storage Technology   | 3         | 0.14%   |
| Realtek Semiconductor            | 2         | 0.09%   |
| Micron/Crucial Technology        | 2         | 0.09%   |
| Netac Technology                 | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.05%   |
| JMicron Technology               | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 209       | 8.74%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 195       | 8.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 174       | 7.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 122       | 5.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 86        | 3.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 81        | 3.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 60        | 2.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 58        | 2.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 53        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 50        | 2.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 47        | 1.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 46        | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 45        | 1.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 45        | 1.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 37        | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 37        | 1.55%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 36        | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 36        | 1.51%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 35        | 1.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 34        | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 30        | 1.26%   |
| Intel SSD 660P Series                                                                  | 28        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 28        | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 28        | 1.17%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 28        | 1.17%   |
| AMD SB600 IDE                                                                          | 28        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 26        | 1.09%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 25        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 24        | 1%      |
| SK hynix BC511 NVMe SSD                                                                | 23        | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 22        | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 21        | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 19        | 0.79%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)              | 17        | 0.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 17        | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 16        | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 15        | 0.63%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                         | 15        | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                  | 14        | 0.59%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 13        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1485      | 64.26%  |
| NVMe | 485       | 20.99%  |
| IDE  | 201       | 8.7%    |
| RAID | 140       | 6.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1580      | 81.65%  |
| AMD     | 354       | 18.29%  |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 37        | 1.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 36        | 1.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 27        | 1.39%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 26        | 1.34%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 26        | 1.34%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 1.19%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 21        | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 21        | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 21        | 1.08%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 18        | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 18        | 0.93%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 17        | 0.88%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 17        | 0.88%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 16        | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 0.83%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 15        | 0.77%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 15        | 0.77%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.72%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 14        | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 14        | 0.72%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 14        | 0.72%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 13        | 0.67%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 13        | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 13        | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 0.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.62%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 12        | 0.62%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 11        | 0.57%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 11        | 0.57%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 11        | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 11        | 0.57%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 11        | 0.57%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 10        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 395       | 20.39%  |
| Intel Core i7                  | 286       | 14.77%  |
| Intel Core i3                  | 220       | 11.36%  |
| Intel Celeron                  | 143       | 7.38%   |
| Intel Pentium                  | 142       | 7.33%   |
| Other                          | 100       | 5.16%   |
| Intel Core 2 Duo               | 76        | 3.92%   |
| AMD Ryzen 5                    | 73        | 3.77%   |
| Intel Atom                     | 71        | 3.67%   |
| AMD Ryzen 7                    | 51        | 2.63%   |
| AMD A6                         | 29        | 1.5%    |
| Intel Pentium Silver           | 28        | 1.45%   |
| Intel Pentium Dual-Core        | 28        | 1.45%   |
| Intel Core 2                   | 23        | 1.19%   |
| AMD E                          | 20        | 1.03%   |
| AMD E1                         | 19        | 0.98%   |
| AMD A4                         | 19        | 0.98%   |
| AMD Ryzen 3                    | 18        | 0.93%   |
| Intel Celeron Dual-Core        | 17        | 0.88%   |
| AMD A10                        | 17        | 0.88%   |
| Intel Pentium Dual             | 15        | 0.77%   |
| Intel Genuine                  | 15        | 0.77%   |
| Intel Celeron M                | 13        | 0.67%   |
| AMD E2                         | 13        | 0.67%   |
| AMD Athlon II                  | 12        | 0.62%   |
| AMD A8                         | 11        | 0.57%   |
| Intel Pentium M                | 7         | 0.36%   |
| Intel Core Duo                 | 7         | 0.36%   |
| AMD Ryzen 9                    | 6         | 0.31%   |
| AMD Turion 64 X2 Mobile        | 5         | 0.26%   |
| AMD Athlon II Dual-Core        | 5         | 0.26%   |
| AMD Athlon                     | 5         | 0.26%   |
| Intel Celeron D                | 4         | 0.21%   |
| AMD C-50                       | 4         | 0.21%   |
| AMD Athlon X2                  | 4         | 0.21%   |
| Intel Xeon                     | 3         | 0.15%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.15%   |
| AMD C-60                       | 3         | 0.15%   |
| AMD Athlon 64 X2               | 3         | 0.15%   |
| AMD A12                        | 3         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1113      | 57.22%  |
| 4       | 559       | 28.74%  |
| 6       | 78        | 4.01%   |
| 1       | 78        | 4.01%   |
| 8       | 57        | 2.93%   |
| Unknown | 39        | 2.01%   |
| 12      | 9         | 0.46%   |
| 14      | 6         | 0.31%   |
| 24      | 3         | 0.15%   |
| 10      | 2         | 0.1%    |
| 16      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 1932      | 99.84%  |
| 2       | 2         | 0.1%    |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1198      | 61.53%  |
| 1       | 710       | 36.47%  |
| Unknown | 39        | 2%      |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1824      | 93.97%  |
| Unknown        | 64        | 3.3%    |
| 32-bit         | 52        | 2.68%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 348       | 17.63%  |
| 0x206a7    | 171       | 8.66%   |
| 0x306a9    | 155       | 7.85%   |
| 0x806ea    | 77        | 3.9%    |
| 0x1067a    | 73        | 3.7%    |
| 0x806ec    | 57        | 2.89%   |
| 0x806e9    | 54        | 2.74%   |
| 0x20655    | 49        | 2.48%   |
| 0x306c3    | 47        | 2.38%   |
| 0x406e3    | 46        | 2.33%   |
| 0x906ea    | 44        | 2.23%   |
| 0x806c1    | 41        | 2.08%   |
| 0x6fd      | 41        | 2.08%   |
| 0x40651    | 41        | 2.08%   |
| 0x706a1    | 34        | 1.72%   |
| 0x306d4    | 33        | 1.67%   |
| 0x106ca    | 32        | 1.62%   |
| 0x406c4    | 28        | 1.42%   |
| 0x06001119 | 28        | 1.42%   |
| 0x30678    | 27        | 1.37%   |
| 0x08108109 | 23        | 1.17%   |
| 0x05000119 | 23        | 1.17%   |
| 0xa0652    | 20        | 1.01%   |
| 0x906e9    | 19        | 0.96%   |
| 0x506c9    | 18        | 0.91%   |
| 0x08600106 | 18        | 0.91%   |
| 0x08108102 | 18        | 0.91%   |
| 0x506e3    | 17        | 0.86%   |
| 0x20652    | 17        | 0.86%   |
| 0x806eb    | 16        | 0.81%   |
| 0x10676    | 16        | 0.81%   |
| 0x6d8      | 15        | 0.76%   |
| 0x406c3    | 15        | 0.76%   |
| 0x08600103 | 15        | 0.76%   |
| 0x010000c8 | 15        | 0.76%   |
| 0x03000027 | 14        | 0.71%   |
| 0x6f6      | 13        | 0.66%   |
| 0x06006705 | 13        | 0.66%   |
| 0x07030105 | 12        | 0.61%   |
| 0x706a8    | 11        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 348       | 17.94%  |
| SandyBridge      | 199       | 10.26%  |
| IvyBridge        | 170       | 8.76%   |
| Haswell          | 103       | 5.31%   |
| Penryn           | 98        | 5.05%   |
| Core             | 86        | 4.43%   |
| Skylake          | 79        | 4.07%   |
| Silvermont       | 76        | 3.92%   |
| Westmere         | 74        | 3.81%   |
| Goldmont plus    | 61        | 3.14%   |
| TigerLake        | 57        | 2.94%   |
| Unknown          | 55        | 2.84%   |
| Bonnell          | 51        | 2.63%   |
| Zen+             | 48        | 2.47%   |
| Zen 2            | 47        | 2.42%   |
| Bobcat           | 40        | 2.06%   |
| Broadwell        | 39        | 2.01%   |
| Piledriver       | 33        | 1.7%    |
| P6               | 31        | 1.6%    |
| Excavator        | 31        | 1.6%    |
| CometLake        | 27        | 1.39%   |
| Zen 3            | 24        | 1.24%   |
| K10              | 24        | 1.24%   |
| Goldmont         | 21        | 1.08%   |
| Alderlake Hybrid | 19        | 0.98%   |
| Puma             | 16        | 0.82%   |
| IceLake          | 16        | 0.82%   |
| Zen              | 15        | 0.77%   |
| K10 Llano        | 15        | 0.77%   |
| Jaguar           | 10        | 0.52%   |
| K8 & K10 hybrid  | 9         | 0.46%   |
| K8 Hammer        | 7         | 0.36%   |
| Tremont          | 6         | 0.31%   |
| Nehalem          | 5         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1408      | 54.38%  |
| Nvidia                           | 606       | 23.41%  |
| AMD                              | 565       | 21.82%  |
| Silicon Integrated Systems [SiS] | 5         | 0.19%   |
| VIA Technologies                 | 3         | 0.12%   |
| ATI Technologies                 | 2         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 183       | 6.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 166       | 6.1%    |
| Intel UHD Graphics 620                                                                   | 84        | 3.09%   |
| Intel HD Graphics 620                                                                    | 66        | 2.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 62        | 2.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 61        | 2.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 60        | 2.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 49        | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 49        | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 48        | 1.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 1.73%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 46        | 1.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 42        | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 1.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 37        | 1.36%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 34        | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 33        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 31        | 1.14%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 31        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 30        | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 29        | 1.07%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 29        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 1.03%   |
| Nvidia GP108M [GeForce MX150]                                                            | 27        | 0.99%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 27        | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 0.96%   |
| Nvidia GM108M [GeForce MX110]                                                            | 26        | 0.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 26        | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 24        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 24        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 24        | 0.88%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 23        | 0.85%   |
| Intel HD Graphics 630                                                                    | 23        | 0.85%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 23        | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 23        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 22        | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 21        | 0.77%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 21        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 786       | 40.56%  |
| Intel + Nvidia | 491       | 25.34%  |
| 1 x AMD        | 328       | 16.92%  |
| Intel + AMD    | 127       | 6.55%   |
| 1 x Nvidia     | 80        | 4.13%   |
| 2 x AMD        | 77        | 3.97%   |
| AMD + Nvidia   | 35        | 1.81%   |
| 1 x SiS        | 5         | 0.26%   |
| Other          | 3         | 0.15%   |
| 2 x Intel      | 3         | 0.15%   |
| 1 x VIA        | 3         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1641      | 83.72%  |
| Proprietary | 263       | 13.42%  |
| Unknown     | 56        | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 889       | 44.72%  |
| 1.01-2.0   | 464       | 23.34%  |
| 0.01-0.5   | 346       | 17.4%   |
| 0.51-1.0   | 140       | 7.04%   |
| 3.01-4.0   | 116       | 5.84%   |
| 5.01-6.0   | 17        | 0.86%   |
| 7.01-8.0   | 8         | 0.4%    |
| 2.01-3.0   | 7         | 0.35%   |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 429       | 20.3%   |
| LG Display              | 354       | 16.75%  |
| Samsung Electronics     | 282       | 13.35%  |
| Chimei Innolux          | 261       | 12.35%  |
| BOE                     | 254       | 12.02%  |
| Chi Mei Optoelectronics | 91        | 4.31%   |
| Dell                    | 60        | 2.84%   |
| Goldstar                | 47        | 2.22%   |
| LG Philips              | 34        | 1.61%   |
| Lenovo                  | 31        | 1.47%   |
| Philips                 | 30        | 1.42%   |
| Sharp                   | 29        | 1.37%   |
| PANDA                   | 27        | 1.28%   |
| HannStar                | 18        | 0.85%   |
| Apple                   | 18        | 0.85%   |
| Hewlett-Packard         | 14        | 0.66%   |
| Ancor Communications    | 13        | 0.62%   |
| Acer                    | 13        | 0.62%   |
| AOC                     | 12        | 0.57%   |
| Valve                   | 10        | 0.47%   |
| CPT                     | 10        | 0.47%   |
| BenQ                    | 9         | 0.43%   |
| Sony                    | 5         | 0.24%   |
| InfoVision              | 5         | 0.24%   |
| ViewSonic               | 4         | 0.19%   |
| Toshiba                 | 4         | 0.19%   |
| TMX                     | 4         | 0.19%   |
| Quanta Display          | 4         | 0.19%   |
| Panasonic               | 3         | 0.14%   |
| LGD                     | 3         | 0.14%   |
| InnoLux Display         | 3         | 0.14%   |
| CSO                     | 3         | 0.14%   |
| Xiaomi                  | 2         | 0.09%   |
| MStar                   | 2         | 0.09%   |
| KTC                     | 2         | 0.09%   |
| HKC                     | 2         | 0.09%   |
| CVT                     | 2         | 0.09%   |
| Belinea                 | 2         | 0.09%   |
| ASUSTek Computer        | 2         | 0.09%   |
| TCL                     | 1         | 0.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 34        | 1.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 28        | 1.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 1.13%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 24        | 1.13%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 1.13%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 22        | 1.03%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 21        | 0.98%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 21        | 0.98%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 20        | 0.94%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 20        | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 18        | 0.84%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 18        | 0.84%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 18        | 0.84%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 17        | 0.8%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 16        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 15        | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 15        | 0.7%    |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 14        | 0.66%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 12        | 0.56%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 12        | 0.56%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.52%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 11        | 0.52%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.52%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 10        | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch | 10        | 0.47%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 10        | 0.47%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 10        | 0.47%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.42%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 9         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 8         | 0.38%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch             | 8         | 0.38%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 8         | 0.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 8         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 8         | 0.38%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 8         | 0.38%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 8         | 0.38%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 8         | 0.38%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 7         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 786       | 39.22%  |
| 1366x768 (WXGA)    | 718       | 35.83%  |
| 1600x900 (HD+)     | 126       | 6.29%   |
| 1280x800 (WXGA)    | 95        | 4.74%   |
| 3840x2160 (4K)     | 49        | 2.45%   |
| 1024x600           | 42        | 2.1%    |
| 2560x1440 (QHD)    | 29        | 1.45%   |
| 1440x900 (WXGA+)   | 27        | 1.35%   |
| 1280x1024 (SXGA)   | 24        | 1.2%    |
| 1920x1200 (WUXGA)  | 18        | 0.9%    |
| 1680x1050 (WSXGA+) | 18        | 0.9%    |
| 2560x1600          | 13        | 0.65%   |
| 800x1280           | 10        | 0.5%    |
| 1024x768 (XGA)     | 8         | 0.4%    |
| 1360x768           | 5         | 0.25%   |
| 3456x2160          | 4         | 0.2%    |
| 3200x2000          | 4         | 0.2%    |
| 2560x1080          | 4         | 0.2%    |
| 3840x2400          | 3         | 0.15%   |
| 3200x1800 (QHD+)   | 3         | 0.15%   |
| 1280x720 (HD)      | 3         | 0.15%   |
| 2880x1620          | 2         | 0.1%    |
| 2160x1440          | 2         | 0.1%    |
| 1600x1200          | 2         | 0.1%    |
| 3840x1100          | 1         | 0.05%   |
| 2966x900           | 1         | 0.05%   |
| 2880x1800          | 1         | 0.05%   |
| 2520x1680          | 1         | 0.05%   |
| 2256x1504          | 1         | 0.05%   |
| 1920x540           | 1         | 0.05%   |
| 1400x1050          | 1         | 0.05%   |
| 1280x768           | 1         | 0.05%   |
| Unknown            | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1157      | 54.7%   |
| 14      | 178       | 8.42%   |
| 13      | 168       | 7.94%   |
| 17      | 161       | 7.61%   |
| 24      | 63        | 2.98%   |
| 23      | 49        | 2.32%   |
| 21      | 46        | 2.17%   |
| 11      | 40        | 1.89%   |
| 10      | 39        | 1.84%   |
| 27      | 35        | 1.65%   |
| 12      | 34        | 1.61%   |
| 16      | 21        | 0.99%   |
| Unknown | 20        | 0.95%   |
| 18      | 17        | 0.8%    |
| 19      | 15        | 0.71%   |
| 31      | 12        | 0.57%   |
| 7       | 10        | 0.47%   |
| 22      | 9         | 0.43%   |
| 32      | 5         | 0.24%   |
| 25      | 5         | 0.24%   |
| 20      | 5         | 0.24%   |
| 8       | 4         | 0.19%   |
| 72      | 3         | 0.14%   |
| 40      | 3         | 0.14%   |
| 34      | 3         | 0.14%   |
| 84      | 2         | 0.09%   |
| 52      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |
| 65      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 54      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |
| 43      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 35      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1417      | 67.22%  |
| 351-400     | 195       | 9.25%   |
| 201-300     | 194       | 9.2%    |
| 501-600     | 147       | 6.97%   |
| 401-500     | 77        | 3.65%   |
| Unknown     | 20        | 0.95%   |
| 601-700     | 19        | 0.9%    |
| 1-100       | 10        | 0.47%   |
| 701-800     | 8         | 0.38%   |
| 1001-1500   | 6         | 0.28%   |
| 1501-2000   | 5         | 0.24%   |
| 801-900     | 4         | 0.19%   |
| 101-200     | 4         | 0.19%   |
| 901-1000    | 2         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1654      | 86.28%  |
| 16/10   | 190       | 9.91%   |
| 5/4     | 25        | 1.3%    |
| Unknown | 13        | 0.68%   |
| 4/3     | 12        | 0.63%   |
| 3/2     | 7         | 0.37%   |
| 0.67    | 7         | 0.37%   |
| 21/9    | 4         | 0.21%   |
| 0.62    | 3         | 0.16%   |
| 32/9    | 1         | 0.05%   |
| 3.40    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1159      | 54.75%  |
| 81-90          | 276       | 13.04%  |
| 201-250        | 144       | 6.8%    |
| 121-130        | 128       | 6.05%   |
| 71-80          | 65        | 3.07%   |
| 51-60          | 41        | 1.94%   |
| 41-50          | 39        | 1.84%   |
| 301-350        | 35        | 1.65%   |
| 61-70          | 33        | 1.56%   |
| 151-200        | 31        | 1.46%   |
| 141-150        | 28        | 1.32%   |
| 131-140        | 24        | 1.13%   |
| 351-500        | 21        | 0.99%   |
| Unknown        | 20        | 0.94%   |
| 251-300        | 19        | 0.9%    |
| 111-120        | 15        | 0.71%   |
| 1-40           | 14        | 0.66%   |
| More than 1000 | 10        | 0.47%   |
| 91-100         | 9         | 0.43%   |
| 501-1000       | 6         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 787       | 37.8%   |
| 121-160       | 784       | 37.66%  |
| 51-100        | 377       | 18.11%  |
| 161-240       | 79        | 3.79%   |
| More than 240 | 27        | 1.3%    |
| Unknown       | 20        | 0.96%   |
| 1-50          | 8         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1665      | 84.6%   |
| 2     | 259       | 13.16%  |
| 0     | 32        | 1.63%   |
| 3     | 12        | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1105      | 34.85%  |
| Intel                                  | 746       | 23.53%  |
| Qualcomm Atheros                       | 666       | 21%     |
| Broadcom                               | 270       | 8.51%   |
| Broadcom Limited                       | 69        | 2.18%   |
| Marvell Technology Group               | 56        | 1.77%   |
| Ralink                                 | 55        | 1.73%   |
| MediaTek                               | 29        | 0.91%   |
| Ralink Technology                      | 22        | 0.69%   |
| Xiaomi                                 | 13        | 0.41%   |
| Huawei Technologies                    | 12        | 0.38%   |
| Dell                                   | 12        | 0.38%   |
| Samsung Electronics                    | 11        | 0.35%   |
| Attansic Technology                    | 11        | 0.35%   |
| ASIX Electronics                       | 8         | 0.25%   |
| Qualcomm Atheros Communications        | 7         | 0.22%   |
| JMicron Technology                     | 7         | 0.22%   |
| TP-Link                                | 6         | 0.19%   |
| Ericsson Business Mobile Networks      | 6         | 0.19%   |
| Sierra Wireless                        | 5         | 0.16%   |
| ICS Advent                             | 5         | 0.16%   |
| Hewlett-Packard                        | 5         | 0.16%   |
| VIA Technologies                       | 4         | 0.13%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.13%   |
| Qualcomm                               | 4         | 0.13%   |
| Fibocom                                | 3         | 0.09%   |
| DisplayLink                            | 3         | 0.09%   |
| ASUSTek Computer                       | 3         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.06%   |
| Nokia Mobile Phones                    | 2         | 0.06%   |
| Lenovo                                 | 2         | 0.06%   |
| D-Link System                          | 2         | 0.06%   |
| D-Link                                 | 2         | 0.06%   |
| ZyDAS                                  | 1         | 0.03%   |
| U-Blox                                 | 1         | 0.03%   |
| Toshiba                                | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| OKB SAPR                               | 1         | 0.03%   |
| Nvidia                                 | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 676       | 18.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 280       | 7.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 150       | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 103       | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 99        | 2.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 91        | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 83        | 2.25%   |
| Intel Wireless 8265 / 8275                                              | 60        | 1.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 52        | 1.41%   |
| Intel Wireless 7260                                                     | 48        | 1.3%    |
| Intel Wi-Fi 6 AX201                                                     | 45        | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 43        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 42        | 1.14%   |
| Intel Wi-Fi 6 AX200                                                     | 40        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 38        | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 37        | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 36        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 36        | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 35        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 34        | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 32        | 0.87%   |
| Intel Wireless 3165                                                     | 32        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 30        | 0.81%   |
| Intel Wireless 8260                                                     | 30        | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 29        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 28        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 27        | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 25        | 0.68%   |
| Intel Wireless 7265                                                     | 24        | 0.65%   |
| Intel Centrino Wireless-N 2230                                          | 24        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 23        | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 22        | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 22        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 21        | 0.57%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 21        | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 20        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 20        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 712       | 36.2%   |
| Qualcomm Atheros                | 572       | 29.08%  |
| Realtek Semiconductor           | 289       | 14.69%  |
| Broadcom                        | 204       | 10.37%  |
| Ralink                          | 55        | 2.8%    |
| Broadcom Limited                | 43        | 2.19%   |
| MediaTek                        | 29        | 1.47%   |
| Ralink Technology               | 22        | 1.12%   |
| Dell                            | 8         | 0.41%   |
| Qualcomm Atheros Communications | 7         | 0.36%   |
| Sierra Wireless                 | 5         | 0.25%   |
| TP-Link                         | 4         | 0.2%    |
| Qualcomm                        | 4         | 0.2%    |
| Fibocom                         | 3         | 0.15%   |
| D-Link System                   | 2         | 0.1%    |
| D-Link                          | 2         | 0.1%    |
| ZyDAS                           | 1         | 0.05%   |
| Microsoft                       | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| ASUSTek Computer                | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 150       | 7.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 103       | 5.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 99        | 5.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 91        | 4.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 4.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 83        | 4.21%   |
| Intel Wireless 8265 / 8275                                              | 60        | 3.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 52        | 2.64%   |
| Intel Wireless 7260                                                     | 48        | 2.44%   |
| Intel Wi-Fi 6 AX201                                                     | 45        | 2.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 42        | 2.13%   |
| Intel Wi-Fi 6 AX200                                                     | 40        | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 38        | 1.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 37        | 1.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 36        | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 1.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 36        | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 35        | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 32        | 1.62%   |
| Intel Wireless 3165                                                     | 32        | 1.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 30        | 1.52%   |
| Intel Wireless 8260                                                     | 30        | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 28        | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 27        | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 25        | 1.27%   |
| Intel Wireless 7265                                                     | 24        | 1.22%   |
| Intel Centrino Wireless-N 2230                                          | 24        | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 23        | 1.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 21        | 1.07%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 20        | 1.01%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 20        | 1.01%   |
| Intel Centrino Ultimate-N 6300                                          | 18        | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 17        | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 16        | 0.81%   |
| Intel WiFi Link 5100                                                    | 16        | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 15        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 13        | 0.66%   |
| Ralink MT7601U Wireless Adapter                                         | 12        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1006      | 59.99%  |
| Intel                                  | 217       | 12.94%  |
| Qualcomm Atheros                       | 186       | 11.09%  |
| Broadcom                               | 92        | 5.49%   |
| Marvell Technology Group               | 56        | 3.34%   |
| Broadcom Limited                       | 28        | 1.67%   |
| Xiaomi                                 | 13        | 0.78%   |
| Attansic Technology                    | 11        | 0.66%   |
| Huawei Technologies                    | 10        | 0.6%    |
| Samsung Electronics                    | 9         | 0.54%   |
| ASIX Electronics                       | 8         | 0.48%   |
| JMicron Technology                     | 7         | 0.42%   |
| ICS Advent                             | 5         | 0.3%    |
| VIA Technologies                       | 4         | 0.24%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.24%   |
| Hewlett-Packard                        | 3         | 0.18%   |
| DisplayLink                            | 3         | 0.18%   |
| TP-Link                                | 2         | 0.12%   |
| Spreadtrum Communications              | 2         | 0.12%   |
| Lenovo                                 | 2         | 0.12%   |
| ASUSTek Computer                       | 2         | 0.12%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OPPO Electronics                       | 1         | 0.06%   |
| OKB SAPR                               | 1         | 0.06%   |
| Nvidia                                 | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| LSI                                    | 1         | 0.06%   |
| Android                                | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 676       | 40.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 280       | 16.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 43        | 2.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 34        | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 29        | 1.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 22        | 1.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 22        | 1.3%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 21        | 1.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 20        | 1.18%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 20        | 1.18%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 16        | 0.95%   |
| Intel Ethernet Connection (6) I219-V                                   | 16        | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 15        | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 14        | 0.83%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 14        | 0.83%   |
| Intel Ethernet Connection I218-LM                                      | 12        | 0.71%   |
| Intel Ethernet Connection (4) I219-V                                   | 12        | 0.71%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 11        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 11        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                  | 11        | 0.65%   |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 11        | 0.65%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 0.59%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 0.59%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.53%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 9         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9         | 0.53%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 9         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 8         | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 8         | 0.47%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 8         | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 7         | 0.41%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 7         | 0.41%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 7         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1902      | 53.43%  |
| Ethernet | 1626      | 45.67%  |
| Modem    | 31        | 0.87%   |
| Unknown  | 1         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1605      | 78.48%  |
| Ethernet | 440       | 21.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1557      | 80.47%  |
| 1     | 357       | 18.45%  |
| 0     | 19        | 0.98%   |
| 3     | 2         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1923      | 99.38%  |
| Yes  | 12        | 0.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 526       | 35.71%  |
| Qualcomm Atheros Communications | 183       | 12.42%  |
| Realtek Semiconductor           | 170       | 11.54%  |
| IMC Networks                    | 150       | 10.18%  |
| Lite-On Technology              | 98        | 6.65%   |
| Broadcom                        | 93        | 6.31%   |
| Foxconn / Hon Hai               | 65        | 4.41%   |
| Ralink                          | 36        | 2.44%   |
| Hewlett-Packard                 | 29        | 1.97%   |
| Dell                            | 21        | 1.43%   |
| ASUSTek Computer                | 19        | 1.29%   |
| Apple                           | 16        | 1.09%   |
| Cambridge Silicon Radio         | 13        | 0.88%   |
| Toshiba                         | 10        | 0.68%   |
| Ralink Technology               | 10        | 0.68%   |
| Foxconn International           | 9         | 0.61%   |
| Realtek                         | 5         | 0.34%   |
| Opticis                         | 4         | 0.27%   |
| Alps Electric                   | 4         | 0.27%   |
| Micro Star International        | 3         | 0.2%    |
| MediaTek                        | 3         | 0.2%    |
| Taiyo Yuden                     | 2         | 0.14%   |
| Askey Computer                  | 2         | 0.14%   |
| Fujitsu                         | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 194       | 13.17%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 103       | 6.99%   |
| Intel AX201 Bluetooth                               | 95        | 6.45%   |
| Realtek Bluetooth Radio                             | 82        | 5.57%   |
| Qualcomm Atheros  Bluetooth Device                  | 71        | 4.82%   |
| IMC Networks Bluetooth Radio                        | 64        | 4.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 57        | 3.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 47        | 3.19%   |
| IMC Networks Bluetooth Device                       | 40        | 2.72%   |
| Intel AX200 Bluetooth                               | 39        | 2.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 38        | 2.58%   |
| Ralink RT3290 Bluetooth                             | 36        | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 34        | 2.31%   |
| Lite-On Bluetooth Device                            | 33        | 2.24%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 27        | 1.83%   |
| Foxconn / Hon Hai Bluetooth Device                  | 25        | 1.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 24        | 1.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 22        | 1.49%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 1.09%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 1.02%   |
| IMC Networks Wireless_Device                        | 14        | 0.95%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 13        | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 0.88%   |
| Qualcomm Atheros Bluetooth                          | 12        | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.81%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 12        | 0.81%   |
| Intel AX211 Bluetooth                               | 11        | 0.75%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 11        | 0.75%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.68%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 0.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 9         | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module   | 9         | 0.61%   |
| Broadcom BCM20702A0                                 | 9         | 0.61%   |
| Broadcom BCM2045 Bluetooth                          | 9         | 0.61%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 9         | 0.61%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 8         | 0.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.54%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1521      | 67.51%  |
| AMD                              | 435       | 19.31%  |
| Nvidia                           | 218       | 9.68%   |
| C-Media Electronics              | 9         | 0.4%    |
| Logitech                         | 8         | 0.36%   |
| Silicon Integrated Systems [SiS] | 7         | 0.31%   |
| Realtek Semiconductor            | 6         | 0.27%   |
| Plantronics                      | 5         | 0.22%   |
| Lenovo                           | 4         | 0.18%   |
| VIA Technologies                 | 3         | 0.13%   |
| JMTek                            | 3         | 0.13%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| GN Netcom                        | 3         | 0.13%   |
| DSEA A/S                         | 3         | 0.13%   |
| Texas Instruments                | 2         | 0.09%   |
| SteelSeries ApS                  | 2         | 0.09%   |
| Shenzhen Rapoo Technology        | 2         | 0.09%   |
| M-Audio                          | 2         | 0.09%   |
| Kingston Technology              | 2         | 0.09%   |
| Generalplus Technology           | 2         | 0.09%   |
| Trust                            | 1         | 0.04%   |
| Sony                             | 1         | 0.04%   |
| Samsung Electronics              | 1         | 0.04%   |
| Razer USA                        | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| iCreate Technologies             | 1         | 0.04%   |
| Google                           | 1         | 0.04%   |
| Focusrite-Novation               | 1         | 0.04%   |
| Cirrus Logic                     | 1         | 0.04%   |
| BY EDIFIER                       | 1         | 0.04%   |
| Audio-Technica                   | 1         | 0.04%   |
| ASUSTek Computer                 | 1         | 0.04%   |
| Unknown                          | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 229       | 8.51%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 222       | 8.25%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 155       | 5.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 139       | 5.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 89        | 3.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 87        | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 87        | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 86        | 3.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 79        | 2.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 75        | 2.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 66        | 2.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 61        | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 61        | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 58        | 2.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 57        | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 54        | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 50        | 1.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 49        | 1.82%   |
| Intel 8 Series HD Audio Controller                                                                | 49        | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 40        | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 39        | 1.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 39        | 1.45%   |
| Intel Broadwell-U Audio Controller                                                                | 39        | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 38        | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 38        | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 34        | 1.26%   |
| AMD Trinity HDMI Audio Controller                                                                 | 33        | 1.23%   |
| AMD Wrestler HDMI Audio                                                                           | 32        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 31        | 1.15%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 30        | 1.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 0.85%   |
| Intel CM238 HD Audio Controller                                                                   | 23        | 0.85%   |
| AMD High Definition Audio Controller                                                              | 23        | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 22        | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 21        | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 19        | 0.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 16        | 0.59%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 16        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 431       | 27.06%  |
| SK hynix                     | 328       | 20.59%  |
| Unknown                      | 167       | 10.48%  |
| Micron Technology            | 167       | 10.48%  |
| Kingston                     | 149       | 9.35%   |
| Ramaxel Technology           | 61        | 3.83%   |
| Elpida                       | 56        | 3.52%   |
| A-DATA Technology            | 34        | 2.13%   |
| Nanya Technology             | 31        | 1.95%   |
| GOODRAM                      | 23        | 1.44%   |
| Crucial                      | 21        | 1.32%   |
| Team                         | 16        | 1%      |
| Unknown (ABCD)               | 12        | 0.75%   |
| Transcend                    | 11        | 0.69%   |
| AMD                          | 10        | 0.63%   |
| ASint Technology             | 9         | 0.56%   |
| 48spaces                     | 8         | 0.5%    |
| SHARETRONIC                  | 7         | 0.44%   |
| Apacer                       | 6         | 0.38%   |
| Patriot                      | 5         | 0.31%   |
| Toshiba                      | 3         | 0.19%   |
| Qimonda                      | 3         | 0.19%   |
| G.Skill                      | 3         | 0.19%   |
| Unifosa                      | 2         | 0.13%   |
| Silicon Power                | 2         | 0.13%   |
| Kllisre                      | 2         | 0.13%   |
| Goldkey                      | 2         | 0.13%   |
| Exceleram                    | 2         | 0.13%   |
| DeTech                       | 2         | 0.13%   |
| Corsair                      | 2         | 0.13%   |
| Unknown                      | 2         | 0.13%   |
| Unknown (C289)               | 1         | 0.06%   |
| Unknown (768A)               | 1         | 0.06%   |
| Teikon                       | 1         | 0.06%   |
| Qumo                         | 1         | 0.06%   |
| Patriot Memory (PDP Systems) | 1         | 0.06%   |
| Kreton                       | 1         | 0.06%   |
| KingSpec                     | 1         | 0.06%   |
| Kingmax                      | 1         | 0.06%   |
| Kembona                      | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 1.27%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 1.15%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 1.1%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 18        | 1.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 1.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.98%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 16        | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.92%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 14        | 0.81%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 14        | 0.81%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 0.81%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 13        | 0.75%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 13        | 0.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.75%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 13        | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 12        | 0.69%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s        | 12        | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.63%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 11        | 0.63%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 10        | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 10        | 0.58%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 10        | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 0.58%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 10        | 0.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.58%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s          | 10        | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 9         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 9         | 0.52%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 9         | 0.52%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 9         | 0.52%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 9         | 0.52%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 8         | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 8         | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 607       | 44.83%  |
| DDR4    | 450       | 33.23%  |
| DDR2    | 108       | 7.98%   |
| SDRAM   | 66        | 4.87%   |
| LPDDR4  | 50        | 3.69%   |
| LPDDR3  | 15        | 1.11%   |
| DDR     | 15        | 1.11%   |
| DRAM    | 14        | 1.03%   |
| Unknown | 13        | 0.96%   |
| DDR5    | 10        | 0.74%   |
| LPDDR5  | 6         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1243      | 94.74%  |
| Row Of Chips | 52        | 3.96%   |
| DIMM         | 9         | 0.69%   |
| Chip         | 7         | 0.53%   |
| Unknown      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 513       | 33.23%  |
| 8192  | 394       | 25.52%  |
| 2048  | 338       | 21.89%  |
| 16384 | 151       | 9.78%   |
| 1024  | 109       | 7.06%   |
| 32768 | 18        | 1.17%   |
| 512   | 18        | 1.17%   |
| 256   | 3         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 387       | 25.9%   |
| 2667    | 218       | 14.59%  |
| 3200    | 148       | 9.91%   |
| 1334    | 141       | 9.44%   |
| 2400    | 103       | 6.89%   |
| 1333    | 97        | 6.49%   |
| Unknown | 67        | 4.48%   |
| 667     | 62        | 4.15%   |
| 2133    | 51        | 3.41%   |
| 4199    | 33        | 2.21%   |
| 1067    | 31        | 2.07%   |
| 800     | 21        | 1.41%   |
| 3266    | 16        | 1.07%   |
| 1066    | 13        | 0.87%   |
| 533     | 13        | 0.87%   |
| 2048    | 12        | 0.8%    |
| 4267    | 11        | 0.74%   |
| 4266    | 10        | 0.67%   |
| 1867    | 10        | 0.67%   |
| 975     | 7         | 0.47%   |
| 400     | 7         | 0.47%   |
| 333     | 7         | 0.47%   |
| 4800    | 6         | 0.4%    |
| 6400    | 5         | 0.33%   |
| 5600    | 5         | 0.33%   |
| 8400    | 4         | 0.27%   |
| 2933    | 3         | 0.2%    |
| 5500    | 1         | 0.07%   |
| 1866    | 1         | 0.07%   |
| 1776    | 1         | 0.07%   |
| 1639    | 1         | 0.07%   |
| 1596    | 1         | 0.07%   |
| 266     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 13        | 52%     |
| Samsung Electronics | 4         | 16%     |
| Hewlett-Packard     | 4         | 16%     |
| Xiaomi              | 1         | 4%      |
| Seiko Epson         | 1         | 4%      |
| Pantum              | 1         | 4%      |
| Dell                | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP LaserJet P1102               | 2         | 8%      |
| Xiaomi MiMouse 2                | 1         | 4%      |
| Seiko Epson ET-2600 Series      | 1         | 4%      |
| Samsung SCX-4100 Scanner        | 1         | 4%      |
| Samsung M2070 Series            | 1         | 4%      |
| Samsung Laser Printer           | 1         | 4%      |
| Samsung CLX-3300 Series         | 1         | 4%      |
| Pantum P2510 series             | 1         | 4%      |
| HP Ink Tank Wireless 410 series | 1         | 4%      |
| HP Deskjet 3540 series          | 1         | 4%      |
| Dell AIO 810                    | 1         | 4%      |
| Canon PIXMA MP495               | 1         | 4%      |
| Canon PIXMA MP280               | 1         | 4%      |
| Canon MG2200 series             | 1         | 4%      |
| Canon MF4410                    | 1         | 4%      |
| Canon MF4010 series             | 1         | 4%      |
| Canon MF3010                    | 1         | 4%      |
| Canon LBP6030/6030B/6018L       | 1         | 4%      |
| Canon LBP6000                   | 1         | 4%      |
| Canon LBP3010/LBP3018/LBP3050   | 1         | 4%      |
| Canon LBP2900                   | 1         | 4%      |
| Canon G4010 series              | 1         | 4%      |
| Canon G2010 series              | 1         | 4%      |
| Canon CAPT USB Device           | 1         | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 2         | 50%     |
| Seiko Epson    | 1         | 25%     |
| Canon          | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 25%     |
| Mustek Systems SNAPSCAN e22            | 1         | 25%     |
| Mustek Systems BearPaw 1200 CU Plus    | 1         | 25%     |
| Canon CanoScan LiDE 120                | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 437       | 25.3%   |
| IMC Networks                           | 248       | 14.36%  |
| Bison Electronics                      | 116       | 6.72%   |
| Realtek Semiconductor                  | 114       | 6.6%    |
| Microdia                               | 107       | 6.2%    |
| Quanta                                 | 103       | 5.96%   |
| Sunplus Innovation Technology          | 96        | 5.56%   |
| Suyin                                  | 82        | 4.75%   |
| Cheng Uei Precision Industry (Foxlink) | 82        | 4.75%   |
| Syntek                                 | 53        | 3.07%   |
| Silicon Motion                         | 41        | 2.37%   |
| Alcor Micro                            | 35        | 2.03%   |
| Lite-On Technology                     | 34        | 1.97%   |
| Acer                                   | 30        | 1.74%   |
| Luxvisions Innotech Limited            | 22        | 1.27%   |
| Apple                                  | 22        | 1.27%   |
| Z-Star Microelectronics                | 16        | 0.93%   |
| Logitech                               | 14        | 0.81%   |
| DigiTech                               | 11        | 0.64%   |
| Sonix Technology                       | 8         | 0.46%   |
| Ricoh                                  | 8         | 0.46%   |
| Primax Electronics                     | 7         | 0.41%   |
| ALi                                    | 7         | 0.41%   |
| Lenovo                                 | 4         | 0.23%   |
| Sunplus Technology                     | 3         | 0.17%   |
| SunplusIT                              | 2         | 0.12%   |
| ShineTech                              | 2         | 0.12%   |
| Samsung Electronics                    | 2         | 0.12%   |
| Genesys Logic                          | 2         | 0.12%   |
| GEMBIRD                                | 2         | 0.12%   |
| Alpha Imaging Technology               | 2         | 0.12%   |
| Xiaomi                                 | 1         | 0.06%   |
| USB Camera CS                          | 1         | 0.06%   |
| Shine-optics                           | 1         | 0.06%   |
| Razer USA                              | 1         | 0.06%   |
| OmniVision Technologies                | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| Intel                                  | 1         | 0.06%   |
| Importek                               | 1         | 0.06%   |
| icSpring                               | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                         | 71        | 4.09%   |
| Chicony Integrated Camera                                                  | 49        | 2.83%   |
| Chicony Lenovo EasyCamera                                                  | 38        | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 36        | 2.08%   |
| Chicony HD WebCam                                                          | 30        | 1.73%   |
| IMC Networks Integrated Camera                                             | 29        | 1.67%   |
| Bison Lenovo Integrated Webcam                                             | 29        | 1.67%   |
| Sunplus Integrated_Webcam_HD                                               | 27        | 1.56%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 27        | 1.56%   |
| Quanta HD User Facing                                                      | 26        | 1.5%    |
| Microdia Integrated_Webcam_HD                                              | 26        | 1.5%    |
| Syntek Lenovo EasyCamera                                                   | 25        | 1.44%   |
| Realtek Integrated_Webcam_HD                                               | 23        | 1.33%   |
| Chicony HP HD Camera                                                       | 22        | 1.27%   |
| Bison Lenovo EasyCamera                                                    | 22        | 1.27%   |
| Quanta HP TrueVision HD Camera                                             | 19        | 1.1%    |
| Bison Integrated Camera                                                    | 19        | 1.1%    |
| Chicony HP Webcam                                                          | 18        | 1.04%   |
| Sunplus HD WebCam                                                          | 16        | 0.92%   |
| IMC Networks Lenovo EasyCamera                                             | 15        | 0.87%   |
| Chicony HP Wide Vision HD Camera                                           | 15        | 0.87%   |
| Sunplus Asus Webcam                                                        | 14        | 0.81%   |
| Quanta HD WebCam                                                           | 14        | 0.81%   |
| Chicony HP Truevision HD                                                   | 14        | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 14        | 0.81%   |
| Lite-On Integrated Camera                                                  | 13        | 0.75%   |
| Lite-On HP HD Camera                                                       | 13        | 0.75%   |
| IMC Networks UVC VGA Webcam                                                | 13        | 0.75%   |
| IMC Networks Integrated Webcam                                             | 13        | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 13        | 0.75%   |
| Syntek Integrated Camera                                                   | 12        | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 12        | 0.69%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 12        | 0.69%   |
| Quanta VGA WebCam                                                          | 12        | 0.69%   |
| Quanta HP HD Camera                                                        | 12        | 0.69%   |
| Chicony VGA WebCam                                                         | 12        | 0.69%   |
| Chicony EasyCamera                                                         | 12        | 0.69%   |
| Alcor Micro Asus Integrated Webcam                                         | 12        | 0.69%   |
| Realtek Integrated Webcam                                                  | 11        | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 11        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 101       | 34.95%  |
| Synaptics                          | 60        | 20.76%  |
| Upek                               | 29        | 10.03%  |
| LighTuning Technology              | 27        | 9.34%   |
| Elan Microelectronics              | 24        | 8.3%    |
| Shenzhen Goodix Technology         | 23        | 7.96%   |
| AuthenTec                          | 15        | 5.19%   |
| STMicroelectronics                 | 6         | 2.08%   |
| FocalTech                          | 2         | 0.69%   |
| Samsung Electronics                | 1         | 0.35%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 36        | 12.46%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 29        | 10.03%  |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 5.54%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 16        | 5.54%   |
| Elan ELAN:Fingerprint                                                      | 16        | 5.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 4.15%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 4.15%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 3.81%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 3.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 3.46%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.77%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.77%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 2.42%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 2.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.08%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 2.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 2.08%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 2.08%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.73%   |
| Elan WBF Fingerprint Sensor                                                | 5         | 1.73%   |
| AuthenTec AES1600                                                          | 5         | 1.73%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 1.38%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.38%   |
| LighTuning Fingerprint Reader                                              | 3         | 1.04%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.04%   |
| AuthenTec AES2810                                                          | 3         | 1.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.69%   |
| FocalTech FocalTech Fingerprint Device                                     | 2         | 0.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.35%   |
| Validity Sensors VFS491                                                    | 1         | 0.35%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.35%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.35%   |
| Synaptics WBDI                                                             | 1         | 0.35%   |
| Synaptics  WBDI                                                            | 1         | 0.35%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 41        | 53.25%  |
| Alcor Micro               | 21        | 27.27%  |
| O2 Micro                  | 8         | 10.39%  |
| Upek                      | 3         | 3.9%    |
| Lenovo                    | 2         | 2.6%    |
| Gemalto (was Gemplus)     | 1         | 1.3%    |
| Aladdin Knowledge Systems | 1         | 1.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 21        | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 20.78%  |
| Broadcom 5880                                                                | 15        | 19.48%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 6.49%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.9%    |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 3.9%    |
| Broadcom 58200                                                               | 3         | 3.9%    |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.6%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.3%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1269      | 64.06%  |
| 1     | 577       | 29.13%  |
| 2     | 119       | 6.01%   |
| 3     | 10        | 0.5%    |
| 4     | 4         | 0.2%    |
| 6     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 287       | 34.17%  |
| Graphics card            | 247       | 29.4%   |
| Net/wireless             | 73        | 8.69%   |
| Chipcard                 | 63        | 7.5%    |
| Bluetooth                | 46        | 5.48%   |
| Multimedia controller    | 40        | 4.76%   |
| Communication controller | 21        | 2.5%    |
| Storage                  | 14        | 1.67%   |
| Camera                   | 14        | 1.67%   |
| Card reader              | 12        | 1.43%   |
| Flash memory             | 7         | 0.83%   |
| Net/ethernet             | 5         | 0.6%    |
| Sound                    | 3         | 0.36%   |
| Network                  | 3         | 0.36%   |
| Modem                    | 3         | 0.36%   |
| Storage/ata              | 1         | 0.12%   |
| Firewire controller      | 1         | 0.12%   |


Linux in Philippines - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

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

Total: 452

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | TravelMate P633-V           | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
| NEC Comput... | PC-VY25AAZR7                | [bc17a98c15](https://linux-hardware.org/?probe=bc17a98c15) | Feb 24, 2023 |
| HP            | ProBook 440 G7              | [9caa421a49](https://linux-hardware.org/?probe=9caa421a49) | Feb 19, 2023 |
| Dell          | Latitude E4200              | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [22b77a1f78](https://linux-hardware.org/?probe=22b77a1f78) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | [0a6d50bc2a](https://linux-hardware.org/?probe=0a6d50bc2a) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | [75980f2f55](https://linux-hardware.org/?probe=75980f2f55) | Feb 13, 2023 |
| Acer          | Aspire ES1-572              | [24c1c37b05](https://linux-hardware.org/?probe=24c1c37b05) | Feb 13, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [94c0fadd44](https://linux-hardware.org/?probe=94c0fadd44) | Feb 10, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [e3bbec75c5](https://linux-hardware.org/?probe=e3bbec75c5) | Feb 10, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | [5d2f191a6f](https://linux-hardware.org/?probe=5d2f191a6f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | [668b9a0bfe](https://linux-hardware.org/?probe=668b9a0bfe) | Feb 09, 2023 |
| Valve         | Jupiter                     | [f7f1655bc2](https://linux-hardware.org/?probe=f7f1655bc2) | Feb 08, 2023 |
| Valve         | Jupiter                     | [df167dd152](https://linux-hardware.org/?probe=df167dd152) | Feb 08, 2023 |
| Unknown       | Unknown                     | [83e2eaf929](https://linux-hardware.org/?probe=83e2eaf929) | Feb 07, 2023 |
| Acer          | Aspire V3-574G              | [5ce729f67f](https://linux-hardware.org/?probe=5ce729f67f) | Feb 04, 2023 |
| HP            | Laptop 17-cn0xxx            | [4029c64aec](https://linux-hardware.org/?probe=4029c64aec) | Feb 02, 2023 |
| HP            | Laptop 17-cn0xxx            | [71bfc02926](https://linux-hardware.org/?probe=71bfc02926) | Feb 01, 2023 |
| Dell          | Inspiron 13-5368            | [4e74651840](https://linux-hardware.org/?probe=4e74651840) | Jan 20, 2023 |
| Unknown       | X133                        | [ad31153d58](https://linux-hardware.org/?probe=ad31153d58) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [907784afb2](https://linux-hardware.org/?probe=907784afb2) | Jan 12, 2023 |
| MSI           | Modern 14 B4MW              | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| Dell          | Inspiron 3583               | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| Acer          | Aspire 4738                 | [62914eb5f1](https://linux-hardware.org/?probe=62914eb5f1) | Jan 09, 2023 |
| Dell          | Inspiron 14-3462            | [99d81ca38e](https://linux-hardware.org/?probe=99d81ca38e) | Jan 06, 2023 |
| Dell          | Inspiron 14-3462            | [582d8bfa18](https://linux-hardware.org/?probe=582d8bfa18) | Jan 06, 2023 |
| MSI           | Modern 14 B4MW              | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| Acer          | Aspire A515-57T             | [bc905f86da](https://linux-hardware.org/?probe=bc905f86da) | Jan 02, 2023 |
| Dell          | Inspiron 14-3462            | [1a8ed5998a](https://linux-hardware.org/?probe=1a8ed5998a) | Dec 30, 2022 |
| HP            | 431 Notebook                | [6a8d323e0c](https://linux-hardware.org/?probe=6a8d323e0c) | Dec 30, 2022 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | [e133481ab3](https://linux-hardware.org/?probe=e133481ab3) | Dec 29, 2022 |
| Dell          | Inspiron 5505               | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| Acer          | Aspire 4738                 | [ffbbc9ecb5](https://linux-hardware.org/?probe=ffbbc9ecb5) | Dec 26, 2022 |
| Acer          | Aspire 4738                 | [f5277ba6a0](https://linux-hardware.org/?probe=f5277ba6a0) | Dec 26, 2022 |
| Dell          | Inspiron 14-3462            | [f95fd7ca72](https://linux-hardware.org/?probe=f95fd7ca72) | Dec 25, 2022 |
| Dell          | Inspiron 14-3462            | [7b38daddb5](https://linux-hardware.org/?probe=7b38daddb5) | Dec 25, 2022 |
| MSI           | Modern 14 B4MW              | [e9dbd838ec](https://linux-hardware.org/?probe=e9dbd838ec) | Dec 25, 2022 |
| Dell          | Inspiron 3583               | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [06d690e9fe](https://linux-hardware.org/?probe=06d690e9fe) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [fe7f585504](https://linux-hardware.org/?probe=fe7f585504) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [63cbf5d0e9](https://linux-hardware.org/?probe=63cbf5d0e9) | Dec 13, 2022 |
| MSI           | Modern 14 B4MW              | [8489ca12d8](https://linux-hardware.org/?probe=8489ca12d8) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [3c5a5379a4](https://linux-hardware.org/?probe=3c5a5379a4) | Dec 13, 2022 |
| Lenovo        | G470 20078                  | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| MSI           | Modern 14 B4MW              | [03c0b9e50d](https://linux-hardware.org/?probe=03c0b9e50d) | Dec 05, 2022 |
| MSI           | Modern 14 B4MW              | [6890b98eeb](https://linux-hardware.org/?probe=6890b98eeb) | Dec 03, 2022 |
| HP            | Laptop 15-da3xxx            | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | Pavilion Power Laptop 15... | [913b35d3f0](https://linux-hardware.org/?probe=913b35d3f0) | Nov 25, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [09285b9428](https://linux-hardware.org/?probe=09285b9428) | Nov 13, 2022 |
| Unknown       | X133                        | [f89481552e](https://linux-hardware.org/?probe=f89481552e) | Nov 11, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [abbb784ea9](https://linux-hardware.org/?probe=abbb784ea9) | Nov 09, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [fbe5c4578c](https://linux-hardware.org/?probe=fbe5c4578c) | Nov 04, 2022 |
| HP            | EliteBook 745 G2            | [6eca80dabf](https://linux-hardware.org/?probe=6eca80dabf) | Nov 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [28cc86118e](https://linux-hardware.org/?probe=28cc86118e) | Nov 03, 2022 |
| Dell          | Vostro 5515                 | [881cd60670](https://linux-hardware.org/?probe=881cd60670) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HUAWEI        | KLVD-WXX9                   | [e9ce57f1c1](https://linux-hardware.org/?probe=e9ce57f1c1) | Oct 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| HP            | 431 Notebook                | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Lenovo        | ThinkPad X230 2325CF6       | [622d37f892](https://linux-hardware.org/?probe=622d37f892) | Oct 15, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [fbb018d1ef](https://linux-hardware.org/?probe=fbb018d1ef) | Oct 14, 2022 |
| Acer          | Swift SF314-57              | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [5eafc7c12c](https://linux-hardware.org/?probe=5eafc7c12c) | Oct 13, 2022 |
| HP            | Laptop 14s-dk1xxx           | [1eb06e8e12](https://linux-hardware.org/?probe=1eb06e8e12) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| Toshiba       | TECRA Z50-C                 | [fc6e63a30a](https://linux-hardware.org/?probe=fc6e63a30a) | Oct 11, 2022 |
| HP            | ENVY Sleekbook 4            | [c14c5b1ee3](https://linux-hardware.org/?probe=c14c5b1ee3) | Oct 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| HP            | ENVY Sleekbook 4            | [0b820a1c7e](https://linux-hardware.org/?probe=0b820a1c7e) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Dell          | Latitude 5490               | [4c59654ea9](https://linux-hardware.org/?probe=4c59654ea9) | Sep 29, 2022 |
| Acer          | Aspire E3-111               | [6646e09597](https://linux-hardware.org/?probe=6646e09597) | Sep 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| Acer          | AOD257                      | [35ca1c0b33](https://linux-hardware.org/?probe=35ca1c0b33) | Sep 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6c34753f58](https://linux-hardware.org/?probe=6c34753f58) | Sep 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Google        | Treeya                      | [0553290711](https://linux-hardware.org/?probe=0553290711) | Sep 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ecadc5740](https://linux-hardware.org/?probe=1ecadc5740) | Sep 11, 2022 |
| ASUSTek       | X441NA                      | [40f5cb1550](https://linux-hardware.org/?probe=40f5cb1550) | Sep 10, 2022 |
| Google        | Treeya                      | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Acer          | Aspire A314-22G             | [b6f9c0a0e7](https://linux-hardware.org/?probe=b6f9c0a0e7) | Sep 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [85d4f11486](https://linux-hardware.org/?probe=85d4f11486) | Sep 01, 2022 |
| Dell          | Inspiron MM061              | [7d69c012fb](https://linux-hardware.org/?probe=7d69c012fb) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| Dell          | Inspiron 7472               | [d9ff6dc8b4](https://linux-hardware.org/?probe=d9ff6dc8b4) | Aug 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| realme        | RMNBXXXX                    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| HP            | Laptop 14-bs1xx             | [4b603b6b08](https://linux-hardware.org/?probe=4b603b6b08) | Aug 15, 2022 |
| ASUSTek       | K56CB                       | [0ec4449fe2](https://linux-hardware.org/?probe=0ec4449fe2) | Aug 09, 2022 |
| HP            | Laptop 14s-dk0xxx           | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [93ae3bfcfd](https://linux-hardware.org/?probe=93ae3bfcfd) | Aug 02, 2022 |
| Lenovo        | ThinkPad E590 20NB0032CD    | [502b0eeb39](https://linux-hardware.org/?probe=502b0eeb39) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| HP            | Pavilion Notebook           | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [f47a0ecbf5](https://linux-hardware.org/?probe=f47a0ecbf5) | Jul 25, 2022 |
| MSI           | CX62 6QD                    | [d0c23fefca](https://linux-hardware.org/?probe=d0c23fefca) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| Unknown       | Unknown                     | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| Dell          | Vostro 3700                 | [2b7a37d662](https://linux-hardware.org/?probe=2b7a37d662) | Jul 16, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [24c803a5fc](https://linux-hardware.org/?probe=24c803a5fc) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| HP            | Laptop 15-ef1xxx            | [b6a7451086](https://linux-hardware.org/?probe=b6a7451086) | Jul 11, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [b9c939b2e2](https://linux-hardware.org/?probe=b9c939b2e2) | Jul 09, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [88cc242e02](https://linux-hardware.org/?probe=88cc242e02) | Jul 09, 2022 |
| HP            | Laptop 15-ef1xxx            | [264b084b00](https://linux-hardware.org/?probe=264b084b00) | Jul 08, 2022 |
| Acer          | Aspire E5-473G              | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [c9d2a76068](https://linux-hardware.org/?probe=c9d2a76068) | Jul 03, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [b7fedc25e4](https://linux-hardware.org/?probe=b7fedc25e4) | Jul 01, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [78eaeff700](https://linux-hardware.org/?probe=78eaeff700) | Jun 27, 2022 |
| Acer          | Predator PH315-53           | [c23e943030](https://linux-hardware.org/?probe=c23e943030) | Jun 21, 2022 |
| Dell          | Inspiron 3531               | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| Dell          | Vostro 5515                 | [b884e51280](https://linux-hardware.org/?probe=b884e51280) | May 21, 2022 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | [a3e1bf045d](https://linux-hardware.org/?probe=a3e1bf045d) | May 20, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | TravelMate P249-G2-MG       | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Unknown       | Unknown                     | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Aspire E5-576G              | [27f577ec86](https://linux-hardware.org/?probe=27f577ec86) | May 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5b877349c1](https://linux-hardware.org/?probe=5b877349c1) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [07ed7fd709](https://linux-hardware.org/?probe=07ed7fd709) | May 08, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [443d537d91](https://linux-hardware.org/?probe=443d537d91) | May 05, 2022 |
| Apple         | MacBookAir5,1               | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Acer          | TravelMate P249-G2-MG       | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Acer          | Aspire E5-551G              | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| Toshiba       | TECRA R940                  | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1f3827f38e](https://linux-hardware.org/?probe=1f3827f38e) | Apr 18, 2022 |
| Unknown       | Unknown                     | [cfd3bd53a8](https://linux-hardware.org/?probe=cfd3bd53a8) | Apr 18, 2022 |
| Acer          | Nitro AN515-57              | [b824b88050](https://linux-hardware.org/?probe=b824b88050) | Apr 15, 2022 |
| Toshiba       | Satellite E45t-A            | [3698a21b91](https://linux-hardware.org/?probe=3698a21b91) | Apr 15, 2022 |
| Toshiba       | dynabook B45/A              | [f430a05b2d](https://linux-hardware.org/?probe=f430a05b2d) | Apr 09, 2022 |
| Samsung       | RC420/RC520/RC720           | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Lenovo        | G50-45 80E3                 | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [1a9459872a](https://linux-hardware.org/?probe=1a9459872a) | Mar 13, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | [2f136d5bf5](https://linux-hardware.org/?probe=2f136d5bf5) | Mar 11, 2022 |
| Unknown       | Unknown                     | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Unknown       | Unknown                     | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [809dad2888](https://linux-hardware.org/?probe=809dad2888) | Mar 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Acer          | AOD270                      | [491fbe6832](https://linux-hardware.org/?probe=491fbe6832) | Feb 21, 2022 |
| Acer          | AOD270                      | [90f9f56240](https://linux-hardware.org/?probe=90f9f56240) | Feb 21, 2022 |
| ASUSTek       | 900                         | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| HP            | Unknown                     | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Lenovo        | ThinkPad X220 4290MN4       | [c0c3368738](https://linux-hardware.org/?probe=c0c3368738) | Feb 08, 2022 |
| Acer          | Aspire V5-471               | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | [c8f0deedbc](https://linux-hardware.org/?probe=c8f0deedbc) | Feb 03, 2022 |
| Acer          | Nitro AN515-55              | [ca4c953595](https://linux-hardware.org/?probe=ca4c953595) | Jan 27, 2022 |
| Acer          | Aspire A315-42              | [e01afda31f](https://linux-hardware.org/?probe=e01afda31f) | Jan 22, 2022 |
| HP            | Notebook                    | [826345f64e](https://linux-hardware.org/?probe=826345f64e) | Jan 13, 2022 |
| Acer          | Aspire A315-41G             | [647b2f2da2](https://linux-hardware.org/?probe=647b2f2da2) | Jan 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Dell          | Inspiron 5555               | [5f4e7a5f4b](https://linux-hardware.org/?probe=5f4e7a5f4b) | Dec 28, 2021 |
| HP            | Pavilion tx1000             | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Unknown       | Unknown                     | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Dell          | XPS 15 9570                 | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| HP            | Pavilion tx1000             | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| Dell          | MXG061                      | [72d7e58977](https://linux-hardware.org/?probe=72d7e58977) | Nov 28, 2021 |
| Sony          | SVT13115FGS                 | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| HP            | ProBook 4730s               | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Acer          | TravelMate P249-G2-M        | [7dbc9e305c](https://linux-hardware.org/?probe=7dbc9e305c) | Nov 11, 2021 |
| Toshiba       | NB255                       | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [bfd4d51591](https://linux-hardware.org/?probe=bfd4d51591) | Nov 09, 2021 |
| HP            | Unknown                     | [4ce778dffc](https://linux-hardware.org/?probe=4ce778dffc) | Nov 06, 2021 |
| HP            | Unknown                     | [285c5d9c85](https://linux-hardware.org/?probe=285c5d9c85) | Nov 06, 2021 |
| Acer          | Aspire E5-411               | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| PERSONA       | MYBOOK 14                   | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Acer          | Aspire E5-411               | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [fd3aefd54a](https://linux-hardware.org/?probe=fd3aefd54a) | Oct 27, 2021 |
| Dell          | Vostro 1400                 | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| Jumper        | EZbook                      | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HASEE Comp... | HNX4S                       | [aba8e89b9a](https://linux-hardware.org/?probe=aba8e89b9a) | Oct 17, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ec3329e68a](https://linux-hardware.org/?probe=ec3329e68a) | Oct 17, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [b8292ace4e](https://linux-hardware.org/?probe=b8292ace4e) | Oct 14, 2021 |
| HP            | Unknown                     | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| HP            | 14                          | [71ed61e3e0](https://linux-hardware.org/?probe=71ed61e3e0) | Oct 02, 2021 |
| HP            | 14                          | [8fc4fceaa1](https://linux-hardware.org/?probe=8fc4fceaa1) | Oct 02, 2021 |
| HP            | EliteBook 745 G2            | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| HP            | G60                         | [36ad0dc4bc](https://linux-hardware.org/?probe=36ad0dc4bc) | Sep 22, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| ASUSTek       | X510UQ                      | [ffeab1f23c](https://linux-hardware.org/?probe=ffeab1f23c) | Sep 16, 2021 |
| Toshiba       | Satellite P845              | [27d8557047](https://linux-hardware.org/?probe=27d8557047) | Sep 12, 2021 |
| Toshiba       | Satellite C55D-B            | [e9f2b0ceda](https://linux-hardware.org/?probe=e9f2b0ceda) | Sep 11, 2021 |
| Dell          | Latitude E7450              | [531e888c8b](https://linux-hardware.org/?probe=531e888c8b) | Sep 04, 2021 |
| Lenovo        | ThinkPad X220 42863MJ       | [68cbfb3edb](https://linux-hardware.org/?probe=68cbfb3edb) | Sep 04, 2021 |
| Cubix         | Morph                       | [ffc9d93c9b](https://linux-hardware.org/?probe=ffc9d93c9b) | Aug 30, 2021 |
| Gigabyte      | Q2006                       | [754a3fc1b5](https://linux-hardware.org/?probe=754a3fc1b5) | Aug 23, 2021 |
| Gigabyte      | Q2006                       | [a384b10b00](https://linux-hardware.org/?probe=a384b10b00) | Aug 23, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Acer          | Aspire V3-772G              | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Apple         | MacBookAir4,1               | [cc00e74712](https://linux-hardware.org/?probe=cc00e74712) | Aug 09, 2021 |
| Toshiba       | Satellite C650              | [3b5f090e84](https://linux-hardware.org/?probe=3b5f090e84) | Aug 01, 2021 |
| Acer          | Aspire E3-111               | [29d6febd6e](https://linux-hardware.org/?probe=29d6febd6e) | Jul 24, 2021 |
| Acer          | Aspire E3-111               | [f9c8b1d3ff](https://linux-hardware.org/?probe=f9c8b1d3ff) | Jul 24, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [9576a81942](https://linux-hardware.org/?probe=9576a81942) | Jul 23, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d86a6d7c9a](https://linux-hardware.org/?probe=d86a6d7c9a) | Jul 23, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Lenovo        | ThinkPad X220 4291LL6       | [3e8ed9be02](https://linux-hardware.org/?probe=3e8ed9be02) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | [ceedeef480](https://linux-hardware.org/?probe=ceedeef480) | Jul 01, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ca6df82553](https://linux-hardware.org/?probe=ca6df82553) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | [69031eda12](https://linux-hardware.org/?probe=69031eda12) | Jun 18, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | [d7b3c8fc20](https://linux-hardware.org/?probe=d7b3c8fc20) | Jun 18, 2021 |
| Lenovo        | ThinkPad L530 24811K2       | [3517541065](https://linux-hardware.org/?probe=3517541065) | Jun 11, 2021 |
| Toshiba       | Satellite L515              | [72858b36e6](https://linux-hardware.org/?probe=72858b36e6) | Jun 02, 2021 |
| NEC Comput... | PC-VK25MXZCB                | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Acer          | Aspire 4750                 | [5f6a294b7d](https://linux-hardware.org/?probe=5f6a294b7d) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cbe08b6f59](https://linux-hardware.org/?probe=cbe08b6f59) | May 09, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b2e6deb92e](https://linux-hardware.org/?probe=b2e6deb92e) | May 09, 2021 |
| ASUSTek       | X450MD                      | [b77e4abcd8](https://linux-hardware.org/?probe=b77e4abcd8) | May 06, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [bb346e5b0c](https://linux-hardware.org/?probe=bb346e5b0c) | Apr 26, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ff01911cb6](https://linux-hardware.org/?probe=ff01911cb6) | Apr 22, 2021 |
| Acer          | Aspire ES1-132              | [2e91d0c330](https://linux-hardware.org/?probe=2e91d0c330) | Apr 20, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Acer          | Nitro AN715-51              | [1cd3975ffa](https://linux-hardware.org/?probe=1cd3975ffa) | Apr 16, 2021 |
| HP            | Notebook                    | [023066c915](https://linux-hardware.org/?probe=023066c915) | Apr 08, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [b11b4274e4](https://linux-hardware.org/?probe=b11b4274e4) | Apr 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [2870ee333f](https://linux-hardware.org/?probe=2870ee333f) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [43b581a270](https://linux-hardware.org/?probe=43b581a270) | Apr 07, 2021 |
| Dell          | Inspiron 15-3567            | [40b47343b7](https://linux-hardware.org/?probe=40b47343b7) | Mar 28, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | [4f1b6f18bf](https://linux-hardware.org/?probe=4f1b6f18bf) | Mar 26, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | [aec0de9a30](https://linux-hardware.org/?probe=aec0de9a30) | Mar 26, 2021 |
| Acer          | TravelMate B117-M           | [c205b164c5](https://linux-hardware.org/?probe=c205b164c5) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [4b98fb1e80](https://linux-hardware.org/?probe=4b98fb1e80) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [42dd14b17d](https://linux-hardware.org/?probe=42dd14b17d) | Mar 09, 2021 |
| MSI           | CX62 7QL                    | [8241c594e5](https://linux-hardware.org/?probe=8241c594e5) | Mar 07, 2021 |
| eMachines     | eM250                       | [e20e648698](https://linux-hardware.org/?probe=e20e648698) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [ec866fbb40](https://linux-hardware.org/?probe=ec866fbb40) | Mar 04, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Acer          | TravelMate B115-M           | [46b6080608](https://linux-hardware.org/?probe=46b6080608) | Mar 02, 2021 |
| Acer          | TravelMate B115-M           | [4567b99e4e](https://linux-hardware.org/?probe=4567b99e4e) | Mar 02, 2021 |
| Acer          | TravelMate B113             | [5ff9f9bb03](https://linux-hardware.org/?probe=5ff9f9bb03) | Feb 23, 2021 |
| Lenovo        | G450 20022                  | [a98aa9041e](https://linux-hardware.org/?probe=a98aa9041e) | Feb 17, 2021 |
| Sony          | VPCEA36FA                   | [050c395bd5](https://linux-hardware.org/?probe=050c395bd5) | Feb 16, 2021 |
| Lenovo        | ThinkPad L530 24812K6       | [d78f3099e4](https://linux-hardware.org/?probe=d78f3099e4) | Feb 14, 2021 |
| Apple         | MacBookPro5,5               | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| Acer          | TravelMate B113             | [7e439b847d](https://linux-hardware.org/?probe=7e439b847d) | Feb 04, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [4c9b44d2d4](https://linux-hardware.org/?probe=4c9b44d2d4) | Jan 26, 2021 |
| Acer          | Aspire ES1-132              | [1e55ffedfe](https://linux-hardware.org/?probe=1e55ffedfe) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | [6f9868755e](https://linux-hardware.org/?probe=6f9868755e) | Jan 15, 2021 |
| Toshiba       | dynabook R73/W              | [b84a72cace](https://linux-hardware.org/?probe=b84a72cace) | Jan 02, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [459afa05c1](https://linux-hardware.org/?probe=459afa05c1) | Dec 26, 2020 |
| HP            | ZBook Create G7 Notebook... | [e40ffb436c](https://linux-hardware.org/?probe=e40ffb436c) | Dec 20, 2020 |
| HP            | ZBook Create G7 Notebook... | [b1a2ee65e0](https://linux-hardware.org/?probe=b1a2ee65e0) | Dec 20, 2020 |
| Acer          | Aspire ES1-431              | [6a99509d25](https://linux-hardware.org/?probe=6a99509d25) | Dec 16, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [e315898f10](https://linux-hardware.org/?probe=e315898f10) | Dec 16, 2020 |
| Toshiba       | dynabook R73/W              | [96710da884](https://linux-hardware.org/?probe=96710da884) | Dec 14, 2020 |
| Samsung       | RF511/RF411/RF711           | [db8ffa8342](https://linux-hardware.org/?probe=db8ffa8342) | Dec 06, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [4dd4445d4d](https://linux-hardware.org/?probe=4dd4445d4d) | Nov 29, 2020 |
| Acer          | Aspire A315-53G             | [9498233954](https://linux-hardware.org/?probe=9498233954) | Nov 26, 2020 |
| eMachines     | eM350                       | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| Apple         | MacBookPro5,5               | [d63213adad](https://linux-hardware.org/?probe=d63213adad) | Nov 22, 2020 |
| ASUSTek       | K43SD                       | [869c3395e8](https://linux-hardware.org/?probe=869c3395e8) | Nov 20, 2020 |
| ASUSTek       | K43SD                       | [3ce330e163](https://linux-hardware.org/?probe=3ce330e163) | Nov 19, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | X540NA                      | [7c1cb4cac0](https://linux-hardware.org/?probe=7c1cb4cac0) | Nov 02, 2020 |
| Lenovo        | ThinkPad X220 4290MN4       | [f305f22059](https://linux-hardware.org/?probe=f305f22059) | Oct 29, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [80d72786c1](https://linux-hardware.org/?probe=80d72786c1) | Oct 26, 2020 |
| Acer          | Aspire SW3-016              | [e110233803](https://linux-hardware.org/?probe=e110233803) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | [ecf79444ac](https://linux-hardware.org/?probe=ecf79444ac) | Oct 21, 2020 |
| HP            | EliteBook 840 G6            | [bfe2deec18](https://linux-hardware.org/?probe=bfe2deec18) | Oct 17, 2020 |
| Acer          | Aspire SW3-016              | [2f0952fbb5](https://linux-hardware.org/?probe=2f0952fbb5) | Oct 15, 2020 |
| Lenovo        | ThinkPad X260 20F5S04206    | [147c40fe70](https://linux-hardware.org/?probe=147c40fe70) | Oct 12, 2020 |
| HP            | Notebook                    | [8cbf9133f7](https://linux-hardware.org/?probe=8cbf9133f7) | Oct 11, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 15                          | [c44a5eaea1](https://linux-hardware.org/?probe=c44a5eaea1) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | [c1812f8ee0](https://linux-hardware.org/?probe=c1812f8ee0) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | [4e98739f72](https://linux-hardware.org/?probe=4e98739f72) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [73fd7565f6](https://linux-hardware.org/?probe=73fd7565f6) | Oct 05, 2020 |
| ASUSTek       | X540NA                      | [a2cee62097](https://linux-hardware.org/?probe=a2cee62097) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| HP            | Pavilion Laptop 15-cc0xx    | [a8678813c5](https://linux-hardware.org/?probe=a8678813c5) | Oct 01, 2020 |
| ASUSTek       | K75DE                       | [b4cb493794](https://linux-hardware.org/?probe=b4cb493794) | Sep 28, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | [72f627fd0e](https://linux-hardware.org/?probe=72f627fd0e) | Sep 21, 2020 |
| Apple         | MacBookAir3,1               | [73e9128968](https://linux-hardware.org/?probe=73e9128968) | Sep 21, 2020 |
| Fujitsu       | FMVA05008                   | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| Lenovo        | V110-14IAP 80TF             | [f0ac65615d](https://linux-hardware.org/?probe=f0ac65615d) | Sep 14, 2020 |
| Lenovo        | V110-14IAP 80TF             | [5acf002102](https://linux-hardware.org/?probe=5acf002102) | Sep 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1cf35a6180](https://linux-hardware.org/?probe=1cf35a6180) | Sep 13, 2020 |
| Lenovo        | V110-14IAP 80TF             | [d2fde2a21e](https://linux-hardware.org/?probe=d2fde2a21e) | Sep 13, 2020 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | [5a3c4a23bb](https://linux-hardware.org/?probe=5a3c4a23bb) | Sep 12, 2020 |
| ASUSTek       | X441URK                     | [f883ed5e4b](https://linux-hardware.org/?probe=f883ed5e4b) | Sep 12, 2020 |
| Dell          | Latitude E4300              | [8b163ddf1e](https://linux-hardware.org/?probe=8b163ddf1e) | Sep 09, 2020 |
| Apple         | MacBookAir2,1               | [c4b26d8019](https://linux-hardware.org/?probe=c4b26d8019) | Sep 08, 2020 |
| HP            | EliteBook 840 G6            | [809af585ab](https://linux-hardware.org/?probe=809af585ab) | Sep 08, 2020 |
| Lenovo        | ThinkPad E580 20KSA00UAU    | [becbbe530b](https://linux-hardware.org/?probe=becbbe530b) | Sep 07, 2020 |
| Acer          | Aspire 4752                 | [9c779dc588](https://linux-hardware.org/?probe=9c779dc588) | Sep 04, 2020 |
| Acer          | Aspire 4752                 | [efeb5dd920](https://linux-hardware.org/?probe=efeb5dd920) | Sep 04, 2020 |
| Acer          | Aspire A315-41G             | [ec1a232ba9](https://linux-hardware.org/?probe=ec1a232ba9) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | [3cff1527be](https://linux-hardware.org/?probe=3cff1527be) | Sep 03, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0fda90e55c](https://linux-hardware.org/?probe=0fda90e55c) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [4a5f93ed76](https://linux-hardware.org/?probe=4a5f93ed76) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e11793b02c](https://linux-hardware.org/?probe=e11793b02c) | Sep 02, 2020 |
| ASUSTek       | X441URK                     | [35b06d497e](https://linux-hardware.org/?probe=35b06d497e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | [100fc7862e](https://linux-hardware.org/?probe=100fc7862e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | [6d9f5403eb](https://linux-hardware.org/?probe=6d9f5403eb) | Sep 02, 2020 |
| Lenovo        | IdeaPad Z460 20059          | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS0SA0J    | [5e85d0fa0e](https://linux-hardware.org/?probe=5e85d0fa0e) | Aug 31, 2020 |
| Clevo         | M7x0S                       | [7efc902d33](https://linux-hardware.org/?probe=7efc902d33) | Aug 31, 2020 |
| Clevo         | M7x0S                       | [58b7846f61](https://linux-hardware.org/?probe=58b7846f61) | Aug 30, 2020 |
| Dell          | Latitude E7450              | [7b6b25e684](https://linux-hardware.org/?probe=7b6b25e684) | Aug 27, 2020 |
| Acer          | Swift SF314-41              | [290159761f](https://linux-hardware.org/?probe=290159761f) | Aug 27, 2020 |
| HP            | Pavilion g4                 | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| ASUSTek       | X540NA                      | [8747f9eb75](https://linux-hardware.org/?probe=8747f9eb75) | Aug 22, 2020 |
| ASUSTek       | X540NA                      | [b1d91b9932](https://linux-hardware.org/?probe=b1d91b9932) | Aug 21, 2020 |
| Sony          | SVF14216SGP                 | [31495e375f](https://linux-hardware.org/?probe=31495e375f) | Aug 19, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | [56702de7d4](https://linux-hardware.org/?probe=56702de7d4) | Aug 15, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | [d868e4a7f9](https://linux-hardware.org/?probe=d868e4a7f9) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [a5e0d02669](https://linux-hardware.org/?probe=a5e0d02669) | Aug 12, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [aa6089eda7](https://linux-hardware.org/?probe=aa6089eda7) | Aug 06, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [86ee9f7736](https://linux-hardware.org/?probe=86ee9f7736) | Aug 06, 2020 |
| MSI           | GV62 8RD                    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| HP            | Pavilion g4                 | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| Acer          | Aspire ES1-521              | [64a762e6b8](https://linux-hardware.org/?probe=64a762e6b8) | Jul 26, 2020 |
| HP            | Notebook                    | [7dd7f12bb9](https://linux-hardware.org/?probe=7dd7f12bb9) | Jul 25, 2020 |
| HP            | Notebook                    | [55ab6c06c5](https://linux-hardware.org/?probe=55ab6c06c5) | Jul 25, 2020 |
| Acer          | Aspire ES1-521              | [23d8c2d2cf](https://linux-hardware.org/?probe=23d8c2d2cf) | Jul 25, 2020 |
| Samsung       | RF511/RF411/RF711           | [ca9dc81053](https://linux-hardware.org/?probe=ca9dc81053) | Jul 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [d486d4bc03](https://linux-hardware.org/?probe=d486d4bc03) | Jul 24, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [f12d8d16e5](https://linux-hardware.org/?probe=f12d8d16e5) | Jul 16, 2020 |
| Acer          | Aspire ES1-132              | [d1bc3c3a8a](https://linux-hardware.org/?probe=d1bc3c3a8a) | Jul 10, 2020 |
| Acer          | Aspire ES1-132              | [cb26f9925f](https://linux-hardware.org/?probe=cb26f9925f) | Jul 09, 2020 |
| ASUSTek       | X540NA                      | [2e3aac14fe](https://linux-hardware.org/?probe=2e3aac14fe) | Jul 02, 2020 |
| Acer          | Aspire V5-431               | [0287b85983](https://linux-hardware.org/?probe=0287b85983) | Jun 30, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | [fb0a45d925](https://linux-hardware.org/?probe=fb0a45d925) | Jun 27, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | [99e750162d](https://linux-hardware.org/?probe=99e750162d) | Jun 27, 2020 |
| eMachines     | eM350                       | [b699bf9fb6](https://linux-hardware.org/?probe=b699bf9fb6) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | [1107791eab](https://linux-hardware.org/?probe=1107791eab) | Jun 22, 2020 |
| Acer          | Aspire ES1-132              | [7c1783588a](https://linux-hardware.org/?probe=7c1783588a) | Jun 12, 2020 |
| Acer          | Aspire ES1-132              | [cbbefff0a6](https://linux-hardware.org/?probe=cbbefff0a6) | Jun 12, 2020 |
| HP            | 15                          | [a4b90e7ad1](https://linux-hardware.org/?probe=a4b90e7ad1) | Jun 05, 2020 |
| ASUSTek       | X540UP                      | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Dell          | Latitude 7490               | [b7b69c9cbf](https://linux-hardware.org/?probe=b7b69c9cbf) | Jun 05, 2020 |
| MSI           | MS-N014                     | [e9fd398a70](https://linux-hardware.org/?probe=e9fd398a70) | Jun 04, 2020 |
| Google        | Caroline                    | [4e305a0551](https://linux-hardware.org/?probe=4e305a0551) | May 31, 2020 |
| Samsung       | N150P/N210P/N220P           | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| ASUSTek       | N45SF                       | [a73c8a7057](https://linux-hardware.org/?probe=a73c8a7057) | May 24, 2020 |
| Acer          | Aspire A315-51              | [8d5860b41f](https://linux-hardware.org/?probe=8d5860b41f) | May 23, 2020 |
| Acer          | Aspire A315-51              | [931084ae9c](https://linux-hardware.org/?probe=931084ae9c) | May 23, 2020 |
| ASUSTek       | N45SF                       | [e35a078b83](https://linux-hardware.org/?probe=e35a078b83) | May 23, 2020 |
| HP            | EliteBook 745 G3            | [ebd5778f8c](https://linux-hardware.org/?probe=ebd5778f8c) | May 22, 2020 |
| Lenovo        | ThinkPad X280 20KES69A00    | [c1fc46e405](https://linux-hardware.org/?probe=c1fc46e405) | May 21, 2020 |
| Acer          | Aspire ES1-431              | [58ad8d0b01](https://linux-hardware.org/?probe=58ad8d0b01) | May 18, 2020 |
| Samsung       | RF511/RF411/RF711           | [9e80b645d9](https://linux-hardware.org/?probe=9e80b645d9) | May 17, 2020 |
| Toshiba       | Satellite Pro U400          | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| Acer          | Aspire ES1-431              | [32fb20af11](https://linux-hardware.org/?probe=32fb20af11) | May 16, 2020 |
| Lenovo        | IdeaPad S540-15IML 81NG     | [89e361466e](https://linux-hardware.org/?probe=89e361466e) | May 14, 2020 |
| HP            | Notebook                    | [142457c9ea](https://linux-hardware.org/?probe=142457c9ea) | May 12, 2020 |
| Acer          | Aspire M5-481PT             | [772cc038ae](https://linux-hardware.org/?probe=772cc038ae) | May 09, 2020 |
| Acer          | Aspire M5-481PT             | [332e871ec3](https://linux-hardware.org/?probe=332e871ec3) | May 09, 2020 |
| Acer          | Aspire ES1-431              | [429d4a7720](https://linux-hardware.org/?probe=429d4a7720) | May 03, 2020 |
| Samsung       | RF511/RF411/RF711           | [028f510367](https://linux-hardware.org/?probe=028f510367) | May 03, 2020 |
| HP            | EliteBook 745 G2            | [60ee09d8aa](https://linux-hardware.org/?probe=60ee09d8aa) | May 02, 2020 |
| Lenovo        | ThinkPad T460s 20F9004FU... | [8eacfd828e](https://linux-hardware.org/?probe=8eacfd828e) | Apr 21, 2020 |
| Clevo         | M7x0S                       | [7ba28306d0](https://linux-hardware.org/?probe=7ba28306d0) | Apr 16, 2020 |
| Clevo         | M7x0S                       | [23aa6b7beb](https://linux-hardware.org/?probe=23aa6b7beb) | Apr 16, 2020 |
| Dell          | Inspiron 3442               | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| Clevo         | E412X                       | [0cca012f20](https://linux-hardware.org/?probe=0cca012f20) | Apr 09, 2020 |
| Acer          | Aspire ES1-431              | [3bf24f9dd6](https://linux-hardware.org/?probe=3bf24f9dd6) | Apr 07, 2020 |
| HP            | EliteBook 745 G2            | [68ecbaa367](https://linux-hardware.org/?probe=68ecbaa367) | Apr 03, 2020 |
| Acer          | Aspire V3-772G              | [9e4c202def](https://linux-hardware.org/?probe=9e4c202def) | Apr 03, 2020 |
| Acer          | Aspire ES1-431              | [3959954db3](https://linux-hardware.org/?probe=3959954db3) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Dell          | Latitude E6430              | [e38eb04918](https://linux-hardware.org/?probe=e38eb04918) | Mar 23, 2020 |
| ASUSTek       | N45SF                       | [17ec9504f1](https://linux-hardware.org/?probe=17ec9504f1) | Mar 22, 2020 |
| Sony          | SVP13215CDB                 | [0aac039fdc](https://linux-hardware.org/?probe=0aac039fdc) | Mar 06, 2020 |
| Dell          | Precision 3540              | [b30c51350c](https://linux-hardware.org/?probe=b30c51350c) | Mar 05, 2020 |
| ASUSTek       | X441SA                      | [e06798387f](https://linux-hardware.org/?probe=e06798387f) | Mar 05, 2020 |
| Acer          | Aspire V3-772G              | [162a9b6da7](https://linux-hardware.org/?probe=162a9b6da7) | Feb 22, 2020 |
| Acer          | Aspire V5-471G              | [85eca92a3b](https://linux-hardware.org/?probe=85eca92a3b) | Feb 22, 2020 |
| Acer          | Aspire ES1-132              | [7994c923a0](https://linux-hardware.org/?probe=7994c923a0) | Feb 21, 2020 |
| Acer          | Aspire V3-772G              | [5cce680c2e](https://linux-hardware.org/?probe=5cce680c2e) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [de6eba23f1](https://linux-hardware.org/?probe=de6eba23f1) | Feb 09, 2020 |
| Lenovo        | IdeaPad Y460                | [ece975c659](https://linux-hardware.org/?probe=ece975c659) | Feb 01, 2020 |
| Lenovo        | IdeaPad Y460                | [1a614a42a8](https://linux-hardware.org/?probe=1a614a42a8) | Jan 30, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [298e5dbad9](https://linux-hardware.org/?probe=298e5dbad9) | Jan 20, 2020 |
| Dell          | Inspiron N4030              | [f3d828d4b1](https://linux-hardware.org/?probe=f3d828d4b1) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | [600afa3fd4](https://linux-hardware.org/?probe=600afa3fd4) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | [57c3c5d09b](https://linux-hardware.org/?probe=57c3c5d09b) | Jan 11, 2020 |
| ASUSTek       | X540SAA                     | [1e5c712f0b](https://linux-hardware.org/?probe=1e5c712f0b) | Jan 05, 2020 |
| Acer          | Aspire A311-31              | [1db743caaf](https://linux-hardware.org/?probe=1db743caaf) | Dec 24, 2019 |
| Dell          | Inspiron 5567               | [eecdfa47b7](https://linux-hardware.org/?probe=eecdfa47b7) | Dec 15, 2019 |
| Acer          | Aspire A315-51              | [44ecc526a8](https://linux-hardware.org/?probe=44ecc526a8) | Dec 12, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| HP            | ProBook 440 G6              | [20bcca591f](https://linux-hardware.org/?probe=20bcca591f) | Dec 03, 2019 |
| HP            | Stream Laptop 14-ax0XX      | [777d549872](https://linux-hardware.org/?probe=777d549872) | Nov 22, 2019 |
| Acer          | Aspire A315-51              | [c5d4684f24](https://linux-hardware.org/?probe=c5d4684f24) | Nov 11, 2019 |
| Acer          | AO722                       | [a54b8c9315](https://linux-hardware.org/?probe=a54b8c9315) | Nov 08, 2019 |
| Acer          | Aspire A315-51              | [ac217a032c](https://linux-hardware.org/?probe=ac217a032c) | Nov 03, 2019 |
| Toshiba       | PORTEGE R30-A               | [619b0ce294](https://linux-hardware.org/?probe=619b0ce294) | Oct 09, 2019 |
| Acer          | Aspire A315-51              | [0f199af685](https://linux-hardware.org/?probe=0f199af685) | Sep 22, 2019 |
| Toshiba       | PORTEGE R30-A               | [8d497813d1](https://linux-hardware.org/?probe=8d497813d1) | Sep 19, 2019 |
| Acer          | TravelMate P249-G2-M        | [7c06f63670](https://linux-hardware.org/?probe=7c06f63670) | Sep 18, 2019 |
| ASUSTek       | X540NA                      | [36b5c905d1](https://linux-hardware.org/?probe=36b5c905d1) | Sep 16, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | [35b92b56a8](https://linux-hardware.org/?probe=35b92b56a8) | Sep 03, 2019 |
| Acer          | Aspire A315-51              | [eaadda80df](https://linux-hardware.org/?probe=eaadda80df) | Aug 25, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | [e57d7bb95a](https://linux-hardware.org/?probe=e57d7bb95a) | Aug 14, 2019 |
| HP            | Pavilion dm4                | [42df53b120](https://linux-hardware.org/?probe=42df53b120) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| ASUSTek       | X540NA                      | [ac8f1708fb](https://linux-hardware.org/?probe=ac8f1708fb) | Jun 30, 2019 |
| Acer          | Aspire 3935                 | [2288125313](https://linux-hardware.org/?probe=2288125313) | Jun 27, 2019 |
| Acer          | Aspire 3935                 | [fbb934cec8](https://linux-hardware.org/?probe=fbb934cec8) | Jun 27, 2019 |
| Acer          | Aspire 5516                 | [92691e9024](https://linux-hardware.org/?probe=92691e9024) | Jun 13, 2019 |
| ASUSTek       | N550JK                      | [d3769c3f4d](https://linux-hardware.org/?probe=d3769c3f4d) | Apr 16, 2019 |
| ASUSTek       | N550JK                      | [31f0b418f9](https://linux-hardware.org/?probe=31f0b418f9) | Apr 16, 2019 |
| HP            | ENVY 4                      | [97135eda99](https://linux-hardware.org/?probe=97135eda99) | Mar 31, 2019 |
| Dell          | Inspiron 5567               | [18266bd48a](https://linux-hardware.org/?probe=18266bd48a) | Jan 06, 2019 |
| ASUSTek       | X540NA                      | [d3d3b75d21](https://linux-hardware.org/?probe=d3d3b75d21) | Jan 04, 2019 |
| ASUSTek       | X540NA                      | [6f63118ade](https://linux-hardware.org/?probe=6f63118ade) | Jan 04, 2019 |
| Acer          | TravelMate B113             | [fea3b127ea](https://linux-hardware.org/?probe=fea3b127ea) | Dec 25, 2018 |
| ASUSTek       | GL553VD                     | [d43361263c](https://linux-hardware.org/?probe=d43361263c) | Dec 24, 2018 |
| ASUSTek       | X540NA                      | [03eadbe056](https://linux-hardware.org/?probe=03eadbe056) | Nov 20, 2018 |
| ASUSTek       | X540NA                      | [f06d9e94e9](https://linux-hardware.org/?probe=f06d9e94e9) | Nov 20, 2018 |
| MSI           | GT70 2PC                    | [020492bfa1](https://linux-hardware.org/?probe=020492bfa1) | Jul 04, 2017 |
| MSI           | GT70 2PC                    | [a5dafd1181](https://linux-hardware.org/?probe=a5dafd1181) | Jul 04, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 37        | 11.71%  |
| Ubuntu 22.04                 | 16        | 5.06%   |
| Ubuntu 18.04                 | 15        | 4.75%   |
| Pop!_OS 20.04                | 15        | 4.75%   |
| Pop!_OS 22.04                | 11        | 3.48%   |
| KDE neon 20.04               | 11        | 3.48%   |
| OpenMandriva 4.2             | 10        | 3.16%   |
| Arch                         | 7         | 2.22%   |
| Zorin 15                     | 6         | 1.9%    |
| Pop!_OS 21.04                | 6         | 1.9%    |
| Debian 11                    | 6         | 1.9%    |
| Manjaro                      | 5         | 1.58%   |
| Fedora 36                    | 5         | 1.58%   |
| Arch Rolling                 | 5         | 1.58%   |
| Zorin 16                     | 4         | 1.27%   |
| Linux Mint 20.2              | 4         | 1.27%   |
| Kubuntu 22.04                | 4         | 1.27%   |
| Fedora 37                    | 4         | 1.27%   |
| Fedora 35                    | 4         | 1.27%   |
| Ubuntu 20.10                 | 3         | 0.95%   |
| Pop!_OS 21.10                | 3         | 0.95%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.95%   |
| OpenMandriva 4.3             | 3         | 0.95%   |
| LMDE 4                       | 3         | 0.95%   |
| Linux Mint 21.1              | 3         | 0.95%   |
| Linux Mint 20.1              | 3         | 0.95%   |
| Linux Mint 19.3              | 3         | 0.95%   |
| KDE neon 22.04               | 3         | 0.95%   |
| KDE neon 18.04               | 3         | 0.95%   |
| Fedora 33                    | 3         | 0.95%   |
| EndeavourOS Rolling          | 3         | 0.95%   |
| Xubuntu 20.04                | 2         | 0.63%   |
| Xubuntu 18.04                | 2         | 0.63%   |
| Ubuntu MATE 20.04            | 2         | 0.63%   |
| Ubuntu 21.10                 | 2         | 0.63%   |
| Ubuntu 19.10                 | 2         | 0.63%   |
| OpenMandriva 23.01           | 2         | 0.63%   |
| Nobara 36                    | 2         | 0.63%   |
| Manjaro 20.1                 | 2         | 0.63%   |
| Lubuntu 20.04                | 2         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 77        | 25.75%  |
| Pop!_OS       | 36        | 12.04%  |
| Linux Mint    | 22        | 7.36%   |
| Fedora        | 20        | 6.69%   |
| OpenMandriva  | 16        | 5.35%   |
| KDE neon      | 16        | 5.35%   |
| Endless       | 15        | 5.02%   |
| Arch          | 12        | 4.01%   |
| Zorin         | 10        | 3.34%   |
| Manjaro       | 10        | 3.34%   |
| Debian        | 8         | 2.68%   |
| Kali          | 6         | 2.01%   |
| Xubuntu       | 5         | 1.67%   |
| Kubuntu       | 5         | 1.67%   |
| openSUSE      | 4         | 1.34%   |
| EndeavourOS   | 4         | 1.34%   |
| Elementary    | 4         | 1.34%   |
| Ubuntu MATE   | 3         | 1%      |
| Lubuntu       | 3         | 1%      |
| LMDE          | 3         | 1%      |
| ArcoLinux     | 3         | 1%      |
| Nobara        | 2         | 0.67%   |
| Clear Linux   | 2         | 0.67%   |
| BlackPanther  | 2         | 0.67%   |
| Ubuntu Unity  | 1         | 0.33%   |
| Ubuntu Budgie | 1         | 0.33%   |
| SteamOS       | 1         | 0.33%   |
| Sparky        | 1         | 0.33%   |
| Slackware     | 1         | 0.33%   |
| ROSA          | 1         | 0.33%   |
| Peppermint    | 1         | 0.33%   |
| MX            | 1         | 0.33%   |
| Linux Lite    | 1         | 0.33%   |
| Gentoo        | 1         | 0.33%   |
| Archcraft     | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 17        | 5.03%   |
| 5.10.14-desktop-1omv4002 | 10        | 2.96%   |
| 5.4.0-7634-generic       | 5         | 1.48%   |
| 5.4.0-48-generic         | 5         | 1.48%   |
| 5.4.0-47-generic         | 5         | 1.48%   |
| 5.4.0-19-generic         | 4         | 1.18%   |
| 5.3.0-28-generic         | 4         | 1.18%   |
| 5.15.0-58-generic        | 4         | 1.18%   |
| 5.15.0-56-generic        | 4         | 1.18%   |
| 5.15.0-52-generic        | 4         | 1.18%   |
| 5.15.0-50-generic        | 4         | 1.18%   |
| 5.15.0-41-generic        | 4         | 1.18%   |
| 5.13.0-28-generic        | 4         | 1.18%   |
| 5.11.0-7620-generic      | 4         | 1.18%   |
| 6.0.6-76060006-generic   | 3         | 0.89%   |
| 5.8.0-14-generic         | 3         | 0.89%   |
| 5.4.0-7642-generic       | 3         | 0.89%   |
| 5.4.0-45-generic         | 3         | 0.89%   |
| 5.3.0-23-generic         | 3         | 0.89%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.89%   |
| 5.15.0-43-generic        | 3         | 0.89%   |
| 5.13.0-7614-generic      | 3         | 0.89%   |
| 5.13.0-40-generic        | 3         | 0.89%   |
| 5.0.0-37-generic         | 3         | 0.89%   |
| 4.18.0-25-generic        | 3         | 0.89%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.59%   |
| 6.0.12-76060006-generic  | 2         | 0.59%   |
| 6.0.0-kali6-amd64        | 2         | 0.59%   |
| 5.9.16-1-MANJARO         | 2         | 0.59%   |
| 5.8.0-43-generic         | 2         | 0.59%   |
| 5.4.0-90-generic         | 2         | 0.59%   |
| 5.4.0-7625-generic       | 2         | 0.59%   |
| 5.4.0-58-generic         | 2         | 0.59%   |
| 5.4.0-54-generic         | 2         | 0.59%   |
| 5.4.0-52-generic         | 2         | 0.59%   |
| 5.4.0-39-generic         | 2         | 0.59%   |
| 5.4.0-31-generic         | 2         | 0.59%   |
| 5.3.0-42-generic         | 2         | 0.59%   |
| 5.3.0-40-generic         | 2         | 0.59%   |
| 5.19.0-76051900-generic  | 2         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 21.05%  |
| 5.15.0  | 34        | 10.53%  |
| 5.13.0  | 19        | 5.88%   |
| 5.3.0   | 17        | 5.26%   |
| 5.11.0  | 15        | 4.64%   |
| 5.8.0   | 11        | 3.41%   |
| 5.10.14 | 10        | 3.1%    |
| 4.15.0  | 10        | 3.1%    |
| 5.0.0   | 7         | 2.17%   |
| 4.18.0  | 6         | 1.86%   |
| 6.0.6   | 5         | 1.55%   |
| 5.10.0  | 5         | 1.55%   |
| 4.19.0  | 5         | 1.55%   |
| 5.19.0  | 4         | 1.24%   |
| 5.9.16  | 3         | 0.93%   |
| 5.17.5  | 3         | 0.93%   |
| 5.16.7  | 3         | 0.93%   |
| 4.9.20  | 3         | 0.93%   |
| 4.4.0   | 3         | 0.93%   |
| 6.1.1   | 2         | 0.62%   |
| 6.0.12  | 2         | 0.62%   |
| 6.0.0   | 2         | 0.62%   |
| 5.8.14  | 2         | 0.62%   |
| 5.19.12 | 2         | 0.62%   |
| 5.18.13 | 2         | 0.62%   |
| 5.18.10 | 2         | 0.62%   |
| 5.18.0  | 2         | 0.62%   |
| 5.15.10 | 2         | 0.62%   |
| 5.14.0  | 2         | 0.62%   |
| 5.11.16 | 2         | 0.62%   |
| 6.1.4   | 1         | 0.31%   |
| 6.1.12  | 1         | 0.31%   |
| 6.1.10  | 1         | 0.31%   |
| 6.0.8   | 1         | 0.31%   |
| 6.0.5   | 1         | 0.31%   |
| 6.0.16  | 1         | 0.31%   |
| 6.0.11  | 1         | 0.31%   |
| 6.0.10  | 1         | 0.31%   |
| 6.0.1   | 1         | 0.31%   |
| 5.9.13  | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 23.9%   |
| 5.15    | 48        | 15.09%  |
| 5.13    | 20        | 6.29%   |
| 5.3     | 19        | 5.97%   |
| 5.11    | 18        | 5.66%   |
| 5.10    | 18        | 5.66%   |
| 5.8     | 15        | 4.72%   |
| 6.0     | 14        | 4.4%    |
| 5.16    | 12        | 3.77%   |
| 4.15    | 10        | 3.14%   |
| 5.19    | 8         | 2.52%   |
| 5.18    | 8         | 2.52%   |
| 5.0     | 8         | 2.52%   |
| 4.18    | 7         | 2.2%    |
| 6.1     | 5         | 1.57%   |
| 5.9     | 5         | 1.57%   |
| 5.17    | 5         | 1.57%   |
| 4.19    | 5         | 1.57%   |
| 5.6     | 3         | 0.94%   |
| 5.14    | 3         | 0.94%   |
| 4.9     | 3         | 0.94%   |
| 4.4     | 3         | 0.94%   |
| 5.12    | 2         | 0.63%   |
| 5.7     | 1         | 0.31%   |
| 5.2     | 1         | 0.31%   |
| 3.8     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 280       | 96.55%  |
| i686   | 9         | 3.1%    |
| armv7l | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 149       | 49.01%  |
| KDE5       | 49        | 16.12%  |
| XFCE       | 25        | 8.22%   |
| Unknown    | 23        | 7.57%   |
| X-Cinnamon | 21        | 6.91%   |
| KDE        | 12        | 3.95%   |
| MATE       | 7         | 2.3%    |
| Pantheon   | 4         | 1.32%   |
| LXQt       | 3         | 0.99%   |
| Cinnamon   | 2         | 0.66%   |
| Unity      | 1         | 0.33%   |
| sway       | 1         | 0.33%   |
| river      | 1         | 0.33%   |
| Openbox    | 1         | 0.33%   |
| LXDE       | 1         | 0.33%   |
| default    | 1         | 0.33%   |
| Deepin     | 1         | 0.33%   |
| Cutefish   | 1         | 0.33%   |
| Budgie     | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 236       | 79.73%  |
| Wayland | 46        | 15.54%  |
| Unknown | 12        | 4.05%   |
| Tty     | 2         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 170       | 57.05%  |
| GDM     | 36        | 12.08%  |
| SDDM    | 35        | 11.74%  |
| LightDM | 24        | 8.05%   |
| GDM3    | 24        | 8.05%   |
| TDM     | 6         | 2.01%   |
| SLiM    | 1         | 0.34%   |
| MDM     | 1         | 0.34%   |
| LXDM    | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_PH   | 132       | 44.44%  |
| en_US   | 118       | 39.73%  |
| Unknown | 23        | 7.74%   |
| C       | 7         | 2.36%   |
| de_DE   | 6         | 2.02%   |
| en_GB   | 5         | 1.68%   |
| zh_HK   | 1         | 0.34%   |
| zh_CN   | 1         | 0.34%   |
| en_NZ   | 1         | 0.34%   |
| en_IN   | 1         | 0.34%   |
| en_CA   | 1         | 0.34%   |
| en_AU   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 153       | 51.52%  |
| BIOS | 144       | 48.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 224       | 75.17%  |
| Btrfs   | 32        | 10.74%  |
| Overlay | 28        | 9.4%    |
| Unknown | 7         | 2.35%   |
| Ext2    | 3         | 1.01%   |
| Zfs     | 2         | 0.67%   |
| Xfs     | 2         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 177       | 59.6%   |
| GPT     | 93        | 31.31%  |
| MBR     | 27        | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 267       | 91.44%  |
| Yes       | 25        | 8.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 74.74%  |
| Yes       | 74        | 25.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 67        | 23.18%  |
| Acer                | 58        | 20.07%  |
| Hewlett-Packard     | 41        | 14.19%  |
| Dell                | 32        | 11.07%  |
| ASUSTek Computer    | 29        | 10.03%  |
| Toshiba             | 12        | 4.15%   |
| MSI                 | 7         | 2.42%   |
| Apple               | 6         | 2.08%   |
| Samsung Electronics | 5         | 1.73%   |
| Unknown             | 5         | 1.73%   |
| Sony                | 4         | 1.38%   |
| Clevo               | 4         | 1.38%   |
| NEC Computers       | 3         | 1.04%   |
| eMachines           | 3         | 1.04%   |
| Google              | 2         | 0.69%   |
| Valve               | 1         | 0.35%   |
| realme              | 1         | 0.35%   |
| PERSONA             | 1         | 0.35%   |
| Notebook            | 1         | 0.35%   |
| Jumper              | 1         | 0.35%   |
| HUAWEI              | 1         | 0.35%   |
| HASEE Computer      | 1         | 0.35%   |
| Gigabyte Technology | 1         | 0.35%   |
| Fujitsu             | 1         | 0.35%   |
| Cubix               | 1         | 0.35%   |
| ALLDOCUBE           | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 8         | 2.77%   |
| Acer Aspire ES1-132                      | 6         | 2.08%   |
| HP Notebook                              | 3         | 1.04%   |
| Clevo M7x0S                              | 3         | 1.04%   |
| Lenovo V110-14IAP 80TF                   | 2         | 0.69%   |
| HP Pavilion Notebook                     | 2         | 0.69%   |
| eMachines eM350                          | 2         | 0.69%   |
| Dell Latitude E7450                      | 2         | 0.69%   |
| Dell Inspiron 5567                       | 2         | 0.69%   |
| ASUS X540NA                              | 2         | 0.69%   |
| Apple MacBookPro5,5                      | 2         | 0.69%   |
| Acer TravelMate P249-G2-M                | 2         | 0.69%   |
| Acer TravelMate B113                     | 2         | 0.69%   |
| Acer Swift SF314-57                      | 2         | 0.69%   |
| Acer Aspire E5-551G                      | 2         | 0.69%   |
| Acer Aspire E3-111                       | 2         | 0.69%   |
| Acer Aspire A315-51                      | 2         | 0.69%   |
| Acer Aspire A315-41G                     | 2         | 0.69%   |
| Valve Jupiter                            | 1         | 0.35%   |
| Toshiba TECRA Z50-C                      | 1         | 0.35%   |
| Toshiba TECRA R940                       | 1         | 0.35%   |
| Toshiba Satellite Pro U400               | 1         | 0.35%   |
| Toshiba Satellite P845                   | 1         | 0.35%   |
| Toshiba Satellite L515                   | 1         | 0.35%   |
| Toshiba Satellite E45t-A                 | 1         | 0.35%   |
| Toshiba Satellite C650                   | 1         | 0.35%   |
| Toshiba Satellite C55D-B                 | 1         | 0.35%   |
| Toshiba PORTEGE R30-A                    | 1         | 0.35%   |
| Toshiba NB255                            | 1         | 0.35%   |
| Toshiba dynabook R73/W                   | 1         | 0.35%   |
| Toshiba dynabook B45/A                   | 1         | 0.35%   |
| Sony VPCEA36FA                           | 1         | 0.35%   |
| Sony SVT13115FGS                         | 1         | 0.35%   |
| Sony SVP13215CDB                         | 1         | 0.35%   |
| Sony SVF14216SGP                         | 1         | 0.35%   |
| Samsung RF511/RF411/RF711                | 1         | 0.35%   |
| Samsung RC420/RC520/RC720                | 1         | 0.35%   |
| Samsung N150P/N210P/N220P                | 1         | 0.35%   |
| Samsung 905S3G/906S3G/915S3G/9305SG      | 1         | 0.35%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 40        | 13.84%  |
| Lenovo ThinkPad   | 31        | 10.73%  |
| Lenovo IdeaPad    | 26        | 9%      |
| Dell Inspiron     | 16        | 5.54%   |
| HP Pavilion       | 12        | 4.15%   |
| Acer TravelMate   | 8         | 2.77%   |
| Unknown           | 8         | 2.77%   |
| Dell Latitude     | 7         | 2.42%   |
| Toshiba Satellite | 6         | 2.08%   |
| HP Laptop         | 6         | 2.08%   |
| ASUS VivoBook     | 4         | 1.38%   |
| ASUS TUF          | 4         | 1.38%   |
| ASUS ROG          | 4         | 1.38%   |
| Lenovo Legion     | 3         | 1.04%   |
| HP ProBook        | 3         | 1.04%   |
| HP Notebook       | 3         | 1.04%   |
| HP EliteBook      | 3         | 1.04%   |
| Dell Vostro       | 3         | 1.04%   |
| Clevo M7x0S       | 3         | 1.04%   |
| Acer Swift        | 3         | 1.04%   |
| Acer Nitro        | 3         | 1.04%   |
| Toshiba TECRA     | 2         | 0.69%   |
| Toshiba dynabook  | 2         | 0.69%   |
| MSI CX62          | 2         | 0.69%   |
| Lenovo V110-14IAP | 2         | 0.69%   |
| HP Stream         | 2         | 0.69%   |
| HP OMEN           | 2         | 0.69%   |
| HP ENVY           | 2         | 0.69%   |
| eMachines eM350   | 2         | 0.69%   |
| Dell XPS          | 2         | 0.69%   |
| Dell Precision    | 2         | 0.69%   |
| ASUS X540NA       | 2         | 0.69%   |
| Apple MacBookPro5 | 2         | 0.69%   |
| Valve Jupiter     | 1         | 0.35%   |
| Toshiba PORTEGE   | 1         | 0.35%   |
| Toshiba NB255     | 1         | 0.35%   |
| Sony VPCEA36FA    | 1         | 0.35%   |
| Sony SVT13115FGS  | 1         | 0.35%   |
| Sony SVP13215CDB  | 1         | 0.35%   |
| Sony SVF14216SGP  | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 31        | 10.73%  |
| 2016    | 29        | 10.03%  |
| 2017    | 26        | 9%      |
| 2012    | 26        | 9%      |
| 2018    | 24        | 8.3%    |
| 2021    | 22        | 7.61%   |
| 2011    | 20        | 6.92%   |
| 2020    | 19        | 6.57%   |
| 2014    | 19        | 6.57%   |
| 2010    | 19        | 6.57%   |
| 2015    | 14        | 4.84%   |
| 2009    | 12        | 4.15%   |
| 2013    | 11        | 3.81%   |
| 2022    | 6         | 2.08%   |
| 2008    | 6         | 2.08%   |
| 2007    | 2         | 0.69%   |
| 2006    | 2         | 0.69%   |
| Unknown | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 289       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 250       | 85.91%  |
| Enabled  | 41        | 14.09%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 287       | 99.31%  |
| Yes  | 2         | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 81        | 27.55%  |
| 3.01-4.0   | 72        | 24.49%  |
| 8.01-16.0  | 52        | 17.69%  |
| 1.01-2.0   | 35        | 11.9%   |
| 16.01-24.0 | 34        | 11.56%  |
| 2.01-3.0   | 8         | 2.72%   |
| 32.01-64.0 | 6         | 2.04%   |
| 0.51-1.0   | 4         | 1.36%   |
| 24.01-32.0 | 2         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 114       | 35.08%  |
| 2.01-3.0  | 108       | 33.23%  |
| 3.01-4.0  | 38        | 11.69%  |
| 4.01-8.0  | 32        | 9.85%   |
| 0.51-1.0  | 23        | 7.08%   |
| 8.01-16.0 | 8         | 2.46%   |
| 0.01-0.5  | 1         | 0.31%   |
| Unknown   | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 220       | 73.58%  |
| 2      | 63        | 21.07%  |
| 3      | 12        | 4.01%   |
| 0      | 2         | 0.67%   |
| 5      | 1         | 0.33%   |
| 4      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 191       | 65.64%  |
| Yes       | 100       | 34.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 234       | 80.97%  |
| No        | 55        | 19.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 280       | 96.89%  |
| No        | 9         | 3.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 77.55%  |
| No        | 66        | 22.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Philippines | 289       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Quezon City         | 41        | 13.02%  |
| Cebu City           | 28        | 8.89%   |
| Pasig               | 14        | 4.44%   |
| Angeles City        | 14        | 4.44%   |
| Manila              | 13        | 4.13%   |
| Davao City          | 12        | 3.81%   |
| Paranaque City      | 11        | 3.49%   |
| Caloocan City       | 11        | 3.49%   |
| San Jose del Monte  | 8         | 2.54%   |
| Bacoor              | 8         | 2.54%   |
| Makati City         | 7         | 2.22%   |
| Iloilo City         | 7         | 2.22%   |
| Bacolod City        | 7         | 2.22%   |
| San Miguel          | 6         | 1.9%    |
| Mandaluyong City    | 6         | 1.9%    |
| Cagayan de Oro      | 6         | 1.9%    |
| Tarlac City         | 5         | 1.59%   |
| San Fernando City   | 5         | 1.59%   |
| Manajao             | 5         | 1.59%   |
| Las Pinas           | 5         | 1.59%   |
| Imus                | 5         | 1.59%   |
| City of Muntinglupa | 5         | 1.59%   |
| Santa Rosa          | 4         | 1.27%   |
| Malolos             | 4         | 1.27%   |
| Lahug               | 4         | 1.27%   |
| San Pedro           | 3         | 0.95%   |
| San Pablo City      | 3         | 0.95%   |
| Lucena City         | 3         | 0.95%   |
| Legazpi             | 3         | 0.95%   |
| Iligan City         | 3         | 0.95%   |
| Dasmarinas          | 3         | 0.95%   |
| Baguio City         | 3         | 0.95%   |
| Antipolo City       | 3         | 0.95%   |
| Zamboanga City      | 2         | 0.63%   |
| Talisay City        | 2         | 0.63%   |
| Taguig              | 2         | 0.63%   |
| San Juan            | 2         | 0.63%   |
| Oroquieta           | 2         | 0.63%   |
| Ormoc City          | 2         | 0.63%   |
| General Santos      | 2         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 56        | 60     | 15.22%  |
| Seagate                   | 55        | 76     | 14.95%  |
| Toshiba                   | 48        | 63     | 13.04%  |
| Samsung Electronics       | 30        | 36     | 8.15%   |
| SanDisk                   | 21        | 24     | 5.71%   |
| Unknown                   | 18        | 22     | 4.89%   |
| Kingston                  | 16        | 17     | 4.35%   |
| Hitachi                   | 15        | 21     | 4.08%   |
| SK hynix                  | 14        | 21     | 3.8%    |
| Micron Technology         | 9         | 13     | 2.45%   |
| HGST                      | 9         | 9      | 2.45%   |
| Intel                     | 6         | 6      | 1.63%   |
| A-DATA Technology         | 5         | 8      | 1.36%   |
| Ramsta                    | 4         | 5      | 1.09%   |
| Crucial                   | 4         | 4      | 1.09%   |
| Team                      | 3         | 5      | 0.82%   |
| LITEONIT                  | 3         | 4      | 0.82%   |
| Fujitsu                   | 3         | 4      | 0.82%   |
| China                     | 3         | 4      | 0.82%   |
| Apple                     | 3         | 3      | 0.82%   |
| ShiJi                     | 2         | 2      | 0.54%   |
| Phison                    | 2         | 2      | 0.54%   |
| Netac                     | 2         | 2      | 0.54%   |
| Micron/Crucial Technology | 2         | 2      | 0.54%   |
| Lite-On                   | 2         | 4      | 0.54%   |
| JMicron Technology        | 2         | 5      | 0.54%   |
| HS-SSD-E100               | 2         | 2      | 0.54%   |
| HS-SSD-C100               | 2         | 3      | 0.54%   |
| WALRAM                    | 1         | 1      | 0.27%   |
| Vaseky                    | 1         | 2      | 0.27%   |
| UMIS                      | 1         | 1      | 0.27%   |
| Transcend                 | 1         | 1      | 0.27%   |
| Teclast                   | 1         | 4      | 0.27%   |
| TAMMUZ                    | 1         | 1      | 0.27%   |
| SPCC                      | 1         | 2      | 0.27%   |
| Solid State Storage       | 1         | 1      | 0.27%   |
| Silicon Motion            | 1         | 1      | 0.27%   |
| SAGE                      | 1         | 1      | 0.27%   |
| Plextor                   | 1         | 1      | 0.27%   |
| OCZ                       | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                         | 15        | 3.93%   |
| Seagate ST1000LM035-1RK172 1TB                   | 11        | 2.88%   |
| WDC WD5000LPCX-21VHAT0 500GB                     | 7         | 1.83%   |
| Toshiba MQ04ABF100 1TB                           | 5         | 1.31%   |
| Toshiba MQ01ABD100 1TB                           | 5         | 1.31%   |
| Seagate ST500LT012-1DG142 500GB                  | 5         | 1.31%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 4         | 1.05%   |
| Unknown MMC Card  32GB                           | 4         | 1.05%   |
| Seagate ST500LT012-9WS142 500GB                  | 4         | 1.05%   |
| Seagate ST2000LM007-1R8174 2TB                   | 4         | 1.05%   |
| Seagate ST1000LM049-2GH172 1TB                   | 4         | 1.05%   |
| Kingston SA400S37240G 240GB SSD                  | 4         | 1.05%   |
| WDC WD5000LPVX-22V0TT0 500GB                     | 3         | 0.79%   |
| WDC WD5000LPCX-60VHAT0 500GB                     | 3         | 0.79%   |
| WDC WD5000LPCX-24VHAT0 500GB                     | 3         | 0.79%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 3         | 0.79%   |
| SK hynix NVMe SSD Drive 512GB                    | 3         | 0.79%   |
| Seagate ST9500325AS 500GB                        | 3         | 0.79%   |
| Seagate ST500LM030-1RK17D 500GB                  | 3         | 0.79%   |
| Seagate ST1000LM048-2E7172 1TB                   | 3         | 0.79%   |
| Samsung NVMe SSD Drive 512GB                     | 3         | 0.79%   |
| Micron NVMe SSD Drive 512GB                      | 3         | 0.79%   |
| HGST HTS721010A9E630 1TB                         | 3         | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                 | 2         | 0.52%   |
| WDC WD5000LPCX-24C6HT0 500GB                     | 2         | 0.52%   |
| WDC WD10SPZX-24Z10 1TB                           | 2         | 0.52%   |
| Unknown MMC Card  7GB                            | 2         | 0.52%   |
| Unknown MMC Card  64GB                           | 2         | 0.52%   |
| Unknown MMC Card  256GB                          | 2         | 0.52%   |
| Unknown DA4032  32GB                             | 2         | 0.52%   |
| Toshiba MK2555GSX 250GB                          | 2         | 0.52%   |
| SK hynix SC311 SATA 128GB SSD                    | 2         | 0.52%   |
| SK hynix NVMe SSD Drive 256GB                    | 2         | 0.52%   |
| SK hynix BC511 512GB                             | 2         | 0.52%   |
| Seagate ST500LM030-2E717D 500GB                  | 2         | 0.52%   |
| Seagate Expansion 1TB                            | 2         | 0.52%   |
| Seagate BUP Slim 2TB                             | 2         | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB               | 2         | 0.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 2         | 0.52%   |
| SanDisk NVMe SSD Drive 256GB                     | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 76     | 31.43%  |
| WDC                 | 47        | 51     | 26.86%  |
| Toshiba             | 41        | 53     | 23.43%  |
| Hitachi             | 15        | 21     | 8.57%   |
| HGST                | 9         | 9      | 5.14%   |
| Fujitsu             | 3         | 4      | 1.71%   |
| Unknown             | 1         | 1      | 0.57%   |
| Samsung Electronics | 1         | 1      | 0.57%   |
| SAGE                | 1         | 1      | 0.57%   |
| JMicron Technology  | 1         | 1      | 0.57%   |
| HGST HTS            | 1         | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 17     | 14.89%  |
| Kingston            | 10        | 10     | 10.64%  |
| SanDisk             | 9         | 11     | 9.57%   |
| WDC                 | 5         | 5      | 5.32%   |
| Micron Technology   | 5         | 5      | 5.32%   |
| Ramsta              | 4         | 5      | 4.26%   |
| A-DATA Technology   | 4         | 7      | 4.26%   |
| Toshiba             | 3         | 5      | 3.19%   |
| Team                | 3         | 5      | 3.19%   |
| SK hynix            | 3         | 8      | 3.19%   |
| LITEONIT            | 3         | 4      | 3.19%   |
| Crucial             | 3         | 3      | 3.19%   |
| China               | 3         | 4      | 3.19%   |
| Apple               | 3         | 3      | 3.19%   |
| Netac               | 2         | 2      | 2.13%   |
| Intel               | 2         | 2      | 2.13%   |
| HS-SSD-E100         | 2         | 2      | 2.13%   |
| Vaseky              | 1         | 2      | 1.06%   |
| Transcend           | 1         | 1      | 1.06%   |
| Teclast             | 1         | 4      | 1.06%   |
| TAMMUZ              | 1         | 1      | 1.06%   |
| ShiJi               | 1         | 1      | 1.06%   |
| Plextor             | 1         | 1      | 1.06%   |
| Phison              | 1         | 1      | 1.06%   |
| OCZ                 | 1         | 1      | 1.06%   |
| KingSpec            | 1         | 1      | 1.06%   |
| Kingmax             | 1         | 1      | 1.06%   |
| HS-SSD-C100         | 1         | 1      | 1.06%   |
| Hikvision           | 1         | 1      | 1.06%   |
| Gigabyte Technology | 1         | 1      | 1.06%   |
| GALAX               | 1         | 1      | 1.06%   |
| Colorful            | 1         | 1      | 1.06%   |
| ASUS-PHISON         | 1         | 2      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 166       | 219    | 47.98%  |
| SSD     | 88        | 119    | 25.43%  |
| NVMe    | 67        | 89     | 19.36%  |
| MMC     | 18        | 22     | 5.2%    |
| Unknown | 7         | 11     | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 235       | 330    | 69.94%  |
| NVMe | 67        | 89     | 19.94%  |
| MMC  | 18        | 22     | 5.36%   |
| SAS  | 16        | 19     | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 178       | 238    | 69.8%   |
| 0.51-1.0   | 66        | 85     | 25.88%  |
| 1.01-2.0   | 10        | 14     | 3.92%   |
| 4.01-10.0  | 1         | 1      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 84        | 27.81%  |
| 101-250        | 83        | 27.48%  |
| 501-1000       | 47        | 15.56%  |
| 1-20           | 29        | 9.6%    |
| 1001-2000      | 23        | 7.62%   |
| 51-100         | 15        | 4.97%   |
| 21-50          | 13        | 4.3%    |
| Unknown        | 4         | 1.32%   |
| More than 3000 | 2         | 0.66%   |
| 2001-3000      | 2         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 139       | 43.17%  |
| 21-50     | 62        | 19.25%  |
| 51-100    | 46        | 14.29%  |
| 101-250   | 40        | 12.42%  |
| 251-500   | 19        | 5.9%    |
| 501-1000  | 9         | 2.8%    |
| Unknown   | 4         | 1.24%   |
| 1001-2000 | 3         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST2000LM007-1R8174 2TB                 | 2         | 3      | 7.69%   |
| Seagate ST1000LM048-2E7172 1TB                 | 2         | 2      | 7.69%   |
| WDC WD5000LPVT-75G33T0 500GB                   | 1         | 1      | 3.85%   |
| WDC WD5000LPVT-22G33T0 500GB                   | 1         | 1      | 3.85%   |
| WDC WD3200BEVT-22A23T0 320GB                   | 1         | 1      | 3.85%   |
| WDC WD1600BEVT-24A23T0 160GB                   | 1         | 1      | 3.85%   |
| WDC WD10JPVX-60JC3T1 1TB                       | 1         | 1      | 3.85%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 3.85%   |
| Toshiba MK6465GSX 640GB                        | 1         | 1      | 3.85%   |
| Toshiba MK3259GSXP 320GB                       | 1         | 1      | 3.85%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD          | 1         | 1      | 3.85%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 3.85%   |
| Seagate ST9120821AS 120GB                      | 1         | 1      | 3.85%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 3.85%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 3.85%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 2      | 3.85%   |
| Hitachi HTS545050B9SA00 500GB                  | 1         | 1      | 3.85%   |
| Hitachi HTS542525K9SA00 250GB                  | 1         | 1      | 3.85%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 3.85%   |
| Fujitsu MHY2120BH 120GB                        | 1         | 1      | 3.85%   |
| Colorful SL300 128GB SSD                       | 1         | 1      | 3.85%   |
| A-DATA Technology SX6000PNP 512GB              | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 7      | 23.08%  |
| WDC               | 5         | 5      | 19.23%  |
| Toshiba           | 4         | 4      | 15.38%  |
| Hitachi           | 3         | 4      | 11.54%  |
| SK hynix          | 1         | 1      | 3.85%   |
| Ramsta            | 1         | 1      | 3.85%   |
| Micron Technology | 1         | 1      | 3.85%   |
| Kingston          | 1         | 1      | 3.85%   |
| HGST              | 1         | 1      | 3.85%   |
| Fujitsu           | 1         | 1      | 3.85%   |
| Colorful          | 1         | 1      | 3.85%   |
| A-DATA Technology | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 30%     |
| WDC     | 5         | 5      | 25%     |
| Toshiba | 4         | 4      | 20%     |
| Hitachi | 3         | 4      | 15%     |
| HGST    | 1         | 1      | 5%      |
| Fujitsu | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 22     | 76%     |
| SSD  | 5         | 5      | 20%     |
| NVMe | 1         | 1      | 4%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 193       | 313    | 62.66%  |
| Works    | 90        | 118    | 29.22%  |
| Malfunc  | 24        | 28     | 7.79%   |
| Failed   | 1         | 1      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 219       | 66.77%  |
| AMD                              | 32        | 9.76%   |
| Samsung Electronics              | 15        | 4.57%   |
| SanDisk                          | 12        | 3.66%   |
| SK hynix                         | 11        | 3.35%   |
| Nvidia                           | 7         | 2.13%   |
| Kingston Technology Company      | 6         | 1.83%   |
| Toshiba America Info Systems     | 4         | 1.22%   |
| Micron Technology                | 4         | 1.22%   |
| Silicon Integrated Systems [SiS] | 3         | 0.91%   |
| Micron/Crucial Technology        | 3         | 0.91%   |
| Solid State Storage Technology   | 2         | 0.61%   |
| Phison Electronics               | 2         | 0.61%   |
| Lite-On Technology               | 2         | 0.61%   |
| Union Memory (Shenzhen)          | 1         | 0.3%    |
| Silicon Motion                   | 1         | 0.3%    |
| Realtek Semiconductor            | 1         | 0.3%    |
| O2 Micro                         | 1         | 0.3%    |
| Lenovo                           | 1         | 0.3%    |
| KIOXIA                           | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 29        | 8.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 6.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 20        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 4.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 15        | 4.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 2.56%   |
| Samsung NVMe SSD Controller 980                                                  | 8         | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 8         | 2.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 1.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 1.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.99%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 1.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 1.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.42%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 4         | 1.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.14%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.14%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.85%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.85%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.85%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.85%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 3         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.85%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.57%   |
| Solid State Storage Non-Volatile memory controller                               | 2         | 0.57%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 0.57%   |
| SK hynix BC511                                                                   | 2         | 0.57%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                      | 2         | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.57%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 224       | 66.08%  |
| NVMe | 67        | 19.76%  |
| RAID | 28        | 8.26%   |
| IDE  | 20        | 5.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 243       | 84.08%  |
| AMD    | 45        | 15.57%  |
| ARM    | 1         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 2.42%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 2.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.08%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 2.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.73%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 1.73%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.38%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 1.38%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.38%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 1.38%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 1.38%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.04%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.04%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 3         | 1.04%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.04%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.04%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.04%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 1.04%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.69%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 0.69%   |
| Intel Genuine CPU T2060 @ 1.60GHz             | 2         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.69%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.69%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 2         | 0.69%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.69%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.69%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 78        | 26.99%  |
| Intel Core i7           | 48        | 16.61%  |
| Intel Celeron           | 37        | 12.8%   |
| Intel Core i3           | 27        | 9.34%   |
| Other                   | 13        | 4.5%    |
| Intel Atom              | 12        | 4.15%   |
| AMD Ryzen 5             | 11        | 3.81%   |
| Intel Core 2 Duo        | 10        | 3.46%   |
| Intel Pentium           | 8         | 2.77%   |
| AMD Ryzen 7             | 7         | 2.42%   |
| AMD Ryzen 3             | 5         | 1.73%   |
| Intel Pentium Dual-Core | 4         | 1.38%   |
| AMD A8                  | 4         | 1.38%   |
| AMD Athlon              | 3         | 1.04%   |
| Intel Pentium Silver    | 2         | 0.69%   |
| Intel Genuine           | 2         | 0.69%   |
| AMD Turion 64 X2 Mobile | 2         | 0.69%   |
| AMD A10                 | 2         | 0.69%   |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Core m3           | 1         | 0.35%   |
| Intel Core 2            | 1         | 0.35%   |
| Intel Celeron M         | 1         | 0.35%   |
| AMD Ryzen 9             | 1         | 0.35%   |
| AMD Quad-Core           | 1         | 0.35%   |
| AMD PRO A10             | 1         | 0.35%   |
| AMD FX                  | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD C-60                | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |
| AMD A4                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 159       | 55.02%  |
| 4      | 99        | 34.26%  |
| 6      | 12        | 4.15%   |
| 1      | 9         | 3.11%   |
| 8      | 8         | 2.77%   |
| 14     | 1         | 0.35%   |
| 10     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 289       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 201       | 69.55%  |
| 1      | 88        | 30.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 96.55%  |
| Unknown        | 6         | 2.07%   |
| 32-bit         | 4         | 1.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 23.08%  |
| 0x306a9    | 21        | 7.02%   |
| 0x206a7    | 17        | 5.69%   |
| 0x506c9    | 13        | 4.35%   |
| 0x406e3    | 13        | 4.35%   |
| 0x806ea    | 11        | 3.68%   |
| 0x1067a    | 10        | 3.34%   |
| 0x806ec    | 9         | 3.01%   |
| 0x806e9    | 9         | 3.01%   |
| 0x30678    | 9         | 3.01%   |
| 0x306d4    | 8         | 2.68%   |
| 0x906ea    | 5         | 1.67%   |
| 0x706e5    | 5         | 1.67%   |
| 0x406c4    | 5         | 1.67%   |
| 0x40651    | 5         | 1.67%   |
| 0x306c3    | 5         | 1.67%   |
| 0x20655    | 5         | 1.67%   |
| 0x106ca    | 5         | 1.67%   |
| 0x0a50000c | 5         | 1.67%   |
| 0xa0652    | 4         | 1.34%   |
| 0x806c1    | 4         | 1.34%   |
| 0x706a1    | 4         | 1.34%   |
| 0x10676    | 4         | 1.34%   |
| 0x406c3    | 3         | 1%      |
| 0x20652    | 3         | 1%      |
| 0x08108109 | 3         | 1%      |
| 0x07030105 | 3         | 1%      |
| 0x06003106 | 3         | 1%      |
| 0x906e9    | 2         | 0.67%   |
| 0x906c0    | 2         | 0.67%   |
| 0x806eb    | 2         | 0.67%   |
| 0x706a8    | 2         | 0.67%   |
| 0x6ec      | 2         | 0.67%   |
| 0x506e3    | 2         | 0.67%   |
| 0x30661    | 2         | 0.67%   |
| 0x08608103 | 2         | 0.67%   |
| 0x08600106 | 2         | 0.67%   |
| 0x08600104 | 2         | 0.67%   |
| 0x0700010f | 2         | 0.67%   |
| 0x05000119 | 2         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 54        | 18.69%  |
| IvyBridge        | 26        | 9%      |
| SandyBridge      | 19        | 6.57%   |
| Skylake          | 18        | 6.23%   |
| Silvermont       | 17        | 5.88%   |
| Penryn           | 16        | 5.54%   |
| Goldmont         | 15        | 5.19%   |
| Haswell          | 12        | 4.15%   |
| Westmere         | 10        | 3.46%   |
| Broadwell        | 10        | 3.46%   |
| Zen+             | 9         | 3.11%   |
| Bonnell          | 9         | 3.11%   |
| TigerLake        | 8         | 2.77%   |
| CometLake        | 7         | 2.42%   |
| Zen 3            | 6         | 2.08%   |
| Goldmont plus    | 6         | 2.08%   |
| Unknown          | 6         | 2.08%   |
| Zen 2            | 5         | 1.73%   |
| IceLake          | 5         | 1.73%   |
| Puma             | 4         | 1.38%   |
| Zen              | 3         | 1.04%   |
| Steamroller      | 3         | 1.04%   |
| P6               | 3         | 1.04%   |
| K8 Hammer        | 3         | 1.04%   |
| Excavator        | 3         | 1.04%   |
| Tremont          | 2         | 0.69%   |
| Jaguar           | 2         | 0.69%   |
| Core             | 2         | 0.69%   |
| Bobcat           | 2         | 0.69%   |
| Alderlake Hybrid | 2         | 0.69%   |
| Piledriver       | 1         | 0.35%   |
| K8 & K10 hybrid  | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 232       | 61.7%   |
| Nvidia                           | 74        | 19.68%  |
| AMD                              | 67        | 17.82%  |
| Silicon Integrated Systems [SiS] | 3         | 0.8%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 6.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 4.92%   |
| Intel UHD Graphics 620                                                                   | 14        | 3.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 3.37%   |
| Intel HD Graphics 620                                                                    | 13        | 3.37%   |
| Intel HD Graphics 500                                                                    | 13        | 3.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 2.33%   |
| Intel HD Graphics 5500                                                                   | 9         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.55%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 1.55%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 6         | 1.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.55%   |
| Intel HD Graphics 630                                                                    | 6         | 1.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.55%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.3%    |
| AMD Renoir                                                                               | 5         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.04%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.04%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.04%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 3         | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.78%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.78%   |
| Nvidia GM108M [GeForce 940M]                                                             | 3         | 0.78%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.78%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 152       | 52.6%   |
| Intel + Nvidia | 55        | 19.03%  |
| 1 x AMD        | 28        | 9.69%   |
| Intel + AMD    | 23        | 7.96%   |
| 1 x Nvidia     | 10        | 3.46%   |
| AMD + Nvidia   | 9         | 3.11%   |
| 2 x AMD        | 7         | 2.42%   |
| 1 x SiS        | 3         | 1.04%   |
| Other          | 1         | 0.35%   |
| 2 x Intel      | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 242       | 82.88%  |
| Proprietary | 43        | 14.73%  |
| Unknown     | 7         | 2.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 209       | 69.9%   |
| 1.01-2.0   | 31        | 10.37%  |
| 0.01-0.5   | 25        | 8.36%   |
| 3.01-4.0   | 15        | 5.02%   |
| 0.51-1.0   | 15        | 5.02%   |
| 5.01-6.0   | 3         | 1%      |
| 7.01-8.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 57        | 18.15%  |
| Chimei Innolux          | 55        | 17.52%  |
| BOE                     | 51        | 16.24%  |
| LG Display              | 36        | 11.46%  |
| Samsung Electronics     | 30        | 9.55%   |
| Lenovo                  | 12        | 3.82%   |
| Sharp                   | 6         | 1.91%   |
| InfoVision              | 6         | 1.91%   |
| PANDA                   | 5         | 1.59%   |
| Apple                   | 5         | 1.59%   |
| Acer                    | 4         | 1.27%   |
| Sony                    | 3         | 0.96%   |
| Philips                 | 3         | 0.96%   |
| Goldstar                | 3         | 0.96%   |
| Chi Mei Optoelectronics | 3         | 0.96%   |
| AOC                     | 3         | 0.96%   |
| Ancor Communications    | 3         | 0.96%   |
| RTK                     | 2         | 0.64%   |
| LG Philips              | 2         | 0.64%   |
| InnoLux Display         | 2         | 0.64%   |
| Hewlett-Packard         | 2         | 0.64%   |
| Dell                    | 2         | 0.64%   |
| BenQ                    | 2         | 0.64%   |
| ASUSTek Computer        | 2         | 0.64%   |
| ___                     | 1         | 0.32%   |
| Valve                   | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| TMX                     | 1         | 0.32%   |
| Pixio                   | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| MYS                     | 1         | 0.32%   |
| IPS                     | 1         | 0.32%   |
| HKC                     | 1         | 0.32%   |
| HannStar                | 1         | 0.32%   |
| GDH                     | 1         | 0.32%   |
| CSO                     | 1         | 0.32%   |
| COS                     | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 7         | 2.23%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 1.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 4         | 1.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 3         | 0.96%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x173mm 13.9-inch               | 3         | 0.96%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 3         | 0.96%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 3         | 0.96%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.96%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3549 1366x768 309x174mm 14.0-inch  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 2         | 0.64%   |
| RTK 32V3H-H6A RTK4C54 1280x1024 697x392mm 31.5-inch                   | 2         | 0.64%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.64%   |
| LG Display LP101WSA-TLN1 LGD0295 1024x600 224x126mm 10.1-inch         | 2         | 0.64%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 2         | 0.64%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 2         | 0.64%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.64%   |
| BOE LCD Monitor BOE08F2 1920x1080 310x174mm 14.0-inch                 | 2         | 0.64%   |
| BOE LCD Monitor BOE08B3 1920x1080 344x193mm 15.5-inch                 | 2         | 0.64%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 2         | 0.64%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.64%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                     | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch         | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch         | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO2992 1920x1080 344x193mm 15.5-inch        | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 139       | 47.12%  |
| 1920x1080 (FHD)   | 104       | 35.25%  |
| 1600x900 (HD+)    | 12        | 4.07%   |
| 1024x600          | 7         | 2.37%   |
| 1280x800 (WXGA)   | 6         | 2.03%   |
| 1280x1024 (SXGA)  | 5         | 1.69%   |
| 3840x2160 (4K)    | 4         | 1.36%   |
| 1920x1200 (WUXGA) | 4         | 1.36%   |
| 1360x768          | 4         | 1.36%   |
| 1440x900 (WXGA+)  | 3         | 1.02%   |
| 2160x1440         | 2         | 0.68%   |
| 800x1280          | 1         | 0.34%   |
| 2560x1600         | 1         | 0.34%   |
| 2560x1440 (QHD)   | 1         | 0.34%   |
| 2400x1600         | 1         | 0.34%   |
| 1600x1200         | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 113       | 36.22%  |
| 13      | 59        | 18.91%  |
| 14      | 42        | 13.46%  |
| 11      | 19        | 6.09%   |
| 17      | 17        | 5.45%   |
| 18      | 10        | 3.21%   |
| 12      | 10        | 3.21%   |
| 23      | 9         | 2.88%   |
| 10      | 7         | 2.24%   |
| 21      | 6         | 1.92%   |
| 27      | 5         | 1.6%    |
| 72      | 4         | 1.28%   |
| 31      | 4         | 1.28%   |
| Unknown | 2         | 0.64%   |
| 47      | 1         | 0.32%   |
| 24      | 1         | 0.32%   |
| 20      | 1         | 0.32%   |
| 16      | 1         | 0.32%   |
| 7       | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 196       | 63.43%  |
| 201-300     | 53        | 17.15%  |
| 401-500     | 17        | 5.5%    |
| 351-400     | 16        | 5.18%   |
| 501-600     | 13        | 4.21%   |
| 601-700     | 6         | 1.94%   |
| 1501-2000   | 4         | 1.29%   |
| Unknown     | 2         | 0.65%   |
| 1001-1500   | 1         | 0.32%   |
| 1-100       | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 260       | 93.19%  |
| 16/10   | 11        | 3.94%   |
| 5/4     | 3         | 1.08%   |
| 3/2     | 3         | 1.08%   |
| 0.67    | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 111       | 35.69%  |
| 81-90          | 87        | 27.97%  |
| 51-60          | 19        | 6.11%   |
| 71-80          | 14        | 4.5%    |
| 201-250        | 13        | 4.18%   |
| 141-150        | 13        | 4.18%   |
| 121-130        | 13        | 4.18%   |
| 61-70          | 10        | 3.22%   |
| 41-50          | 7         | 2.25%   |
| 301-350        | 5         | 1.61%   |
| More than 1000 | 4         | 1.29%   |
| 351-500        | 4         | 1.29%   |
| 151-200        | 3         | 0.96%   |
| 91-100         | 2         | 0.64%   |
| Unknown        | 2         | 0.64%   |
| 1-40           | 1         | 0.32%   |
| 131-140        | 1         | 0.32%   |
| 111-120        | 1         | 0.32%   |
| 501-1000       | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 135       | 43.55%  |
| 121-160       | 121       | 39.03%  |
| 51-100        | 32        | 10.32%  |
| 161-240       | 10        | 3.23%   |
| 1-50          | 7         | 2.26%   |
| More than 240 | 3         | 0.97%   |
| Unknown       | 2         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 252       | 85.14%  |
| 2     | 33        | 11.15%  |
| 0     | 8         | 2.7%    |
| 3     | 3         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 168       | 37.17%  |
| Intel                            | 127       | 28.1%   |
| Qualcomm Atheros                 | 82        | 18.14%  |
| Broadcom                         | 38        | 8.41%   |
| Ralink Technology                | 7         | 1.55%   |
| Nvidia                           | 5         | 1.11%   |
| Broadcom Limited                 | 4         | 0.88%   |
| Silicon Integrated Systems [SiS] | 3         | 0.66%   |
| Marvell Technology Group         | 3         | 0.66%   |
| TP-Link                          | 2         | 0.44%   |
| Qualcomm Atheros Communications  | 2         | 0.44%   |
| MediaTek                         | 2         | 0.44%   |
| JMicron Technology               | 2         | 0.44%   |
| Ralink                           | 1         | 0.22%   |
| NetGear                          | 1         | 0.22%   |
| Hewlett-Packard                  | 1         | 0.22%   |
| Encore Electronics               | 1         | 0.22%   |
| Dell                             | 1         | 0.22%   |
| BUFFALO                          | 1         | 0.22%   |
| ASIX Electronics                 | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 106       | 19.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 37        | 6.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 3.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.63%   |
| Intel Wireless 7265                                                     | 14        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 2.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 2.06%   |
| Intel Wireless 3165                                                     | 11        | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.31%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.13%   |
| Intel Wireless 8260                                                     | 6         | 1.13%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 0.94%   |
| Intel Wireless 8265 / 8275                                              | 5         | 0.94%   |
| Intel Wireless 7260                                                     | 5         | 0.94%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.75%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.56%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 3         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 41.84%  |
| Qualcomm Atheros                | 71        | 24.15%  |
| Realtek Semiconductor           | 53        | 18.03%  |
| Broadcom                        | 28        | 9.52%   |
| Ralink Technology               | 7         | 2.38%   |
| TP-Link                         | 2         | 0.68%   |
| Qualcomm Atheros Communications | 2         | 0.68%   |
| Broadcom Limited                | 2         | 0.68%   |
| Ralink                          | 1         | 0.34%   |
| NetGear                         | 1         | 0.34%   |
| MediaTek                        | 1         | 0.34%   |
| Encore Electronics              | 1         | 0.34%   |
| Dell                            | 1         | 0.34%   |
| BUFFALO                         | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 6.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 4.75%   |
| Intel Wireless 7265                                                     | 14        | 4.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 4.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 4.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 3.73%   |
| Intel Wireless 3165                                                     | 11        | 3.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 3.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.37%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 2.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 2.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 2.03%   |
| Intel Wireless 8260                                                     | 6         | 2.03%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.69%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.69%   |
| Intel Wireless 7260                                                     | 5         | 1.69%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.02%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.02%   |
| Intel Centrino Wireless-N 2200                                          | 3         | 1.02%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.02%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.68%   |
| Intel WiFi Link 5100                                                    | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 149       | 63.14%  |
| Intel                            | 38        | 16.1%   |
| Qualcomm Atheros                 | 19        | 8.05%   |
| Broadcom                         | 13        | 5.51%   |
| Nvidia                           | 5         | 2.12%   |
| Silicon Integrated Systems [SiS] | 3         | 1.27%   |
| Marvell Technology Group         | 3         | 1.27%   |
| JMicron Technology               | 2         | 0.85%   |
| Broadcom Limited                 | 2         | 0.85%   |
| MediaTek                         | 1         | 0.42%   |
| ASIX Electronics                 | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 106       | 44.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 37        | 15.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 5.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 5         | 2.11%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.69%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 1.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 1.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.84%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.84%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.84%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.84%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.84%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.84%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 2         | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.84%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.42%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.42%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.42%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.42%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.42%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.42%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.42%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.42%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.42%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.42%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 280       | 54.37%  |
| Ethernet | 234       | 45.44%  |
| Modem    | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 242       | 82.03%  |
| Ethernet | 53        | 17.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 219       | 75.78%  |
| 1     | 63        | 21.8%   |
| 0     | 6         | 2.08%   |
| 3     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 268       | 91.78%  |
| Yes  | 24        | 8.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 40.17%  |
| Realtek Semiconductor           | 31        | 13.54%  |
| Qualcomm Atheros Communications | 21        | 9.17%   |
| Lite-On Technology              | 20        | 8.73%   |
| IMC Networks                    | 15        | 6.55%   |
| Foxconn / Hon Hai               | 15        | 6.55%   |
| Broadcom                        | 15        | 6.55%   |
| Apple                           | 6         | 2.62%   |
| Toshiba                         | 3         | 1.31%   |
| Hewlett-Packard                 | 3         | 1.31%   |
| Cambridge Silicon Radio         | 3         | 1.31%   |
| Dell                            | 2         | 0.87%   |
| Chicony Electronics             | 2         | 0.87%   |
| Ralink                          | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 40        | 17.47%  |
| Realtek Bluetooth Radio                             | 18        | 7.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 7.42%   |
| Intel AX201 Bluetooth                               | 15        | 6.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 4.37%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 3.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 3.06%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 3.06%   |
| IMC Networks Bluetooth Device                       | 7         | 3.06%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.18%   |
| Intel AX200 Bluetooth                               | 5         | 2.18%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.75%   |
| Lite-On Bluetooth Device                            | 4         | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.75%   |
| Realtek RTL8723B Bluetooth                          | 3         | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.31%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.31%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.87%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.87%   |
| Lite-On BCM43142A0                                  | 2         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.87%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.87%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.87%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.87%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.87%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 0.87%   |
| Broadcom HP Portable Valentine                      | 2         | 0.87%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.87%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.87%   |
| Apple Bluetooth Host Controller                     | 2         | 0.87%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.44%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.44%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.44%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 233       | 70.18%  |
| AMD                              | 43        | 12.95%  |
| Nvidia                           | 37        | 11.14%  |
| Silicon Integrated Systems [SiS] | 3         | 0.9%    |
| Plantronics                      | 3         | 0.9%    |
| Realtek Semiconductor            | 2         | 0.6%    |
| Logitech                         | 2         | 0.6%    |
| JMTek                            | 2         | 0.6%    |
| USB MICROPHONE                   | 1         | 0.3%    |
| SteelSeries ApS                  | 1         | 0.3%    |
| OPPO Electronics                 | 1         | 0.3%    |
| Micronas                         | 1         | 0.3%    |
| Generalplus Technology           | 1         | 0.3%    |
| Creative Technology              | 1         | 0.3%    |
| C-Media Electronics              | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 43        | 11.11%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 6.98%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 25        | 6.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 4.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 3.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 3.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 2.58%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 2.58%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.55%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.55%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.55%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.55%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.29%   |
| Nvidia Audio device                                                                               | 5         | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.03%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 3         | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.78%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.78%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.78%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 25.84%  |
| SK hynix            | 38        | 21.35%  |
| Kingston            | 30        | 16.85%  |
| Micron Technology   | 18        | 10.11%  |
| Unknown             | 12        | 6.74%   |
| Ramaxel Technology  | 8         | 4.49%   |
| Team                | 5         | 2.81%   |
| Crucial             | 4         | 2.25%   |
| Unknown (ABCD)      | 3         | 1.69%   |
| Elpida              | 3         | 1.69%   |
| Transcend           | 2         | 1.12%   |
| Nanya Technology    | 2         | 1.12%   |
| Unknown (8A5D)      | 1         | 0.56%   |
| G.Skill             | 1         | 0.56%   |
| Avant               | 1         | 0.56%   |
| ASint Technology    | 1         | 0.56%   |
| Apacer              | 1         | 0.56%   |
| A-DATA Technology   | 1         | 0.56%   |
| Unknown             | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 3.21%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 2.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 2.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 2.14%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 2.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.6%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 3         | 1.6%    |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s             | 2         | 1.07%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.07%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.07%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.07%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 1.07%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.07%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.07%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.07%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.07%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.07%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.07%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.07%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.07%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4267MT/s               | 2         | 1.07%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.07%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 1.07%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 1.07%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 1.07%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 1.07%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1866MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                         | 1         | 0.53%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 47.83%  |
| DDR3    | 49        | 35.51%  |
| LPDDR4  | 8         | 5.8%    |
| DDR2    | 8         | 5.8%    |
| Unknown | 2         | 1.45%   |
| SDRAM   | 1         | 0.72%   |
| LPDDR3  | 1         | 0.72%   |
| DRAM    | 1         | 0.72%   |
| DDR5    | 1         | 0.72%   |
| DDR     | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 127       | 93.38%  |
| Row Of Chips | 9         | 6.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 63        | 39.38%  |
| 4096  | 53        | 33.13%  |
| 2048  | 23        | 14.38%  |
| 16384 | 9         | 5.63%   |
| 1024  | 9         | 5.63%   |
| 32768 | 3         | 1.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 37        | 23.42%  |
| 1600    | 37        | 23.42%  |
| 3200    | 23        | 14.56%  |
| 2400    | 15        | 9.49%   |
| 1334    | 9         | 5.7%    |
| 667     | 9         | 5.7%    |
| 2133    | 5         | 3.16%   |
| 1333    | 5         | 3.16%   |
| 8400    | 2         | 1.27%   |
| 4267    | 2         | 1.27%   |
| 1067    | 2         | 1.27%   |
| 1066    | 2         | 1.27%   |
| 4800    | 1         | 0.63%   |
| 4266    | 1         | 0.63%   |
| 3733    | 1         | 0.63%   |
| 3266    | 1         | 0.63%   |
| 2048    | 1         | 0.63%   |
| 1866    | 1         | 0.63%   |
| 800     | 1         | 0.63%   |
| 533     | 1         | 0.63%   |
| 400     | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 50%     |
| Seiko Epson        | 1         | 25%     |
| Unknown            | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L220 Series | 1         | 25%     |
| Brother DCP-T710W       | 1         | 25%     |
| Brother DCP-T310        | 1         | 25%     |
| Unknown                 | 1         | 25%     |

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
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 71        | 28.29%  |
| Realtek Semiconductor                  | 23        | 9.16%   |
| IMC Networks                           | 21        | 8.37%   |
| Quanta                                 | 18        | 7.17%   |
| Acer                                   | 17        | 6.77%   |
| Microdia                               | 16        | 6.37%   |
| Sunplus Innovation Technology          | 12        | 4.78%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 4.78%   |
| Lite-On Technology                     | 9         | 3.59%   |
| Suyin                                  | 7         | 2.79%   |
| Apple                                  | 7         | 2.79%   |
| Syntek                                 | 6         | 2.39%   |
| Silicon Motion                         | 5         | 1.99%   |
| Alcor Micro                            | 4         | 1.59%   |
| Luxvisions Innotech Limited            | 3         | 1.2%    |
| ALi                                    | 3         | 1.2%    |
| Samsung Electronics                    | 2         | 0.8%    |
| icSpring                               | 2         | 0.8%    |
| Z-Star Microelectronics                | 1         | 0.4%    |
| vivo                                   | 1         | 0.4%    |
| SunplusIT                              | 1         | 0.4%    |
| Ricoh                                  | 1         | 0.4%    |
| OPPO Electronics                       | 1         | 0.4%    |
| OmniVision Technologies                | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| Importek                               | 1         | 0.4%    |
| Goertek Electronics                    | 1         | 0.4%    |
| GEMBIRD                                | 1         | 0.4%    |
| DLEQNA19IFK6G2                         | 1         | 0.4%    |
| DigiTech                               | 1         | 0.4%    |
| Alpha Imaging Technology               | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 18        | 7.17%   |
| Chicony HD WebCam                                               | 15        | 5.98%   |
| Realtek Acer 640 x 480 laptop camera                            | 7         | 2.79%   |
| Microdia Integrated_Webcam_HD                                   | 7         | 2.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 7         | 2.79%   |
| Realtek Integrated_Webcam_HD                                    | 5         | 1.99%   |
| Quanta VGA WebCam                                               | 5         | 1.99%   |
| Quanta HD WebCam                                                | 5         | 1.99%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 1.99%   |
| Chicony VGA Webcam                                              | 5         | 1.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 1.59%   |
| Acer Integrated Camera                                          | 4         | 1.59%   |
| Realtek Integrated Webcam                                       | 3         | 1.2%    |
| Quanta HD User Facing                                           | 3         | 1.2%    |
| Lite-On Integrated Camera                                       | 3         | 1.2%    |
| IMC Networks Integrated Camera                                  | 3         | 1.2%    |
| Chicony Lenovo EasyCamera                                       | 3         | 1.2%    |
| Chicony HP Truevision HD                                        | 3         | 1.2%    |
| Apple Built-in iSight                                           | 3         | 1.2%    |
| ALi WebCam                                                      | 3         | 1.2%    |
| Acer Lenovo EasyCamera                                          | 3         | 1.2%    |
| Acer EasyCamera                                                 | 3         | 1.2%    |
| Syntek Lenovo EasyCamera                                        | 2         | 0.8%    |
| Syntek Integrated Camera                                        | 2         | 0.8%    |
| Syntek EasyCamera                                               | 2         | 0.8%    |
| Suyin HP Webcam                                                 | 2         | 0.8%    |
| Sunplus Laptop Integrated WebCam HD                             | 2         | 0.8%    |
| Sunplus Integrated_Webcam_HD                                    | 2         | 0.8%    |
| Sunplus Integrated Webcam                                       | 2         | 0.8%    |
| Sunplus HP Truevision HD                                        | 2         | 0.8%    |
| Sunplus HD WebCam                                               | 2         | 0.8%    |
| Samsung Galaxy A5 (MTP)                                         | 2         | 0.8%    |
| Realtek USB2.0 VGA UVC WebCam                                   | 2         | 0.8%    |
| Quanta HP TrueVision HD Camera                                  | 2         | 0.8%    |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 0.8%    |
| Lite-On TOSHIBA Web Camera - HD                                 | 2         | 0.8%    |
| Lite-On HP HD Camera                                            | 2         | 0.8%    |
| IMC Networks EasyCamera                                         | 2         | 0.8%    |
| icSpring camera                                                 | 2         | 0.8%    |
| Chicony USB 2.0 Camera                                          | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 33.33%  |
| Shenzhen Goodix Technology | 8         | 24.24%  |
| Synaptics                  | 5         | 15.15%  |
| LighTuning Technology      | 4         | 12.12%  |
| Upek                       | 3         | 9.09%   |
| AuthenTec                  | 2         | 6.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 6         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 3         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 6.06%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 6.06%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 6.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 3.03%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 3.03%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 3.03%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.03%   |
| Validity Sensors Synaptics WBDI                            | 1         | 3.03%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 3.03%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 3.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 3.03%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.03%   |
| Shenzhen Goodix FingerPrint                                | 1         | 3.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 3.03%   |
| AuthenTec Fingerprint Sensor                               | 1         | 3.03%   |
| AuthenTec AES1600                                          | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 5         | 45.45%  |
| Upek             | 3         | 27.27%  |
| O2 Micro         | 2         | 18.18%  |
| SCM Microsystems | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 27.27%  |
| Broadcom 5880                                                                | 2         | 18.18%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 9.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 213       | 71.48%  |
| 1     | 72        | 24.16%  |
| 2     | 13        | 4.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 32        | 33.68%  |
| Graphics card            | 24        | 25.26%  |
| Chipcard                 | 11        | 11.58%  |
| Net/wireless             | 10        | 10.53%  |
| Multimedia controller    | 5         | 5.26%   |
| Camera                   | 5         | 5.26%   |
| Net/ethernet             | 3         | 3.16%   |
| Storage                  | 1         | 1.05%   |
| Sound                    | 1         | 1.05%   |
| Modem                    | 1         | 1.05%   |
| Communication controller | 1         | 1.05%   |
| Bluetooth                | 1         | 1.05%   |


Linux in Philippines - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Philippines/Desktop/README.md) and [notebooks](/Location/Philippines/Notebook/README.md).

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

Total: 796

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Xunlong       | Orange Pi One               | Soc         | [8d982c6cd9](https://linux-hardware.org/?probe=8d982c6cd9) | Apr 01, 2023 |
| HP            | 3397                        | Desktop     | [5a25984320](https://linux-hardware.org/?probe=5a25984320) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [4eb8132fd2](https://linux-hardware.org/?probe=4eb8132fd2) | Mar 24, 2023 |
| EMAXX TECH... | EMX-B450M-GAMING            | Desktop     | [f147ee8484](https://linux-hardware.org/?probe=f147ee8484) | Mar 21, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ae258d05b1](https://linux-hardware.org/?probe=ae258d05b1) | Mar 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [a6114c514f](https://linux-hardware.org/?probe=a6114c514f) | Mar 13, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [26ecc0b7a2](https://linux-hardware.org/?probe=26ecc0b7a2) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [a3d866a82b](https://linux-hardware.org/?probe=a3d866a82b) | Mar 09, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [3832889508](https://linux-hardware.org/?probe=3832889508) | Mar 09, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [c124d02c5b](https://linux-hardware.org/?probe=c124d02c5b) | Mar 09, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [8c709c4723](https://linux-hardware.org/?probe=8c709c4723) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [97e8238d87](https://linux-hardware.org/?probe=97e8238d87) | Mar 05, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [3e4fdfbb73](https://linux-hardware.org/?probe=3e4fdfbb73) | Mar 05, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [ada5bd893b](https://linux-hardware.org/?probe=ada5bd893b) | Mar 04, 2023 |
| Lenovo        | ThinkPad X230 23255SM       | Notebook    | [2f5cd26eae](https://linux-hardware.org/?probe=2f5cd26eae) | Mar 04, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [ce3d086582](https://linux-hardware.org/?probe=ce3d086582) | Mar 04, 2023 |
| HP            | ENVY Sleekbook 4            | Notebook    | [d771874d8b](https://linux-hardware.org/?probe=d771874d8b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [587096ec48](https://linux-hardware.org/?probe=587096ec48) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [e1266ebf79](https://linux-hardware.org/?probe=e1266ebf79) | Feb 27, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [d6f5b00609](https://linux-hardware.org/?probe=d6f5b00609) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [89cd5d5c44](https://linux-hardware.org/?probe=89cd5d5c44) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | Notebook    | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | Notebook    | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [99b1ae3224](https://linux-hardware.org/?probe=99b1ae3224) | Feb 25, 2023 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [e88df81d6f](https://linux-hardware.org/?probe=e88df81d6f) | Feb 24, 2023 |
| NEC Comput... | PC-VY25AAZR7                | Notebook    | [bc17a98c15](https://linux-hardware.org/?probe=bc17a98c15) | Feb 24, 2023 |
| Biostar       | A320MH                      | Desktop     | [b6f7ef6e4a](https://linux-hardware.org/?probe=b6f7ef6e4a) | Feb 23, 2023 |
| Biostar       | A320MH                      | Desktop     | [e80f86a0bf](https://linux-hardware.org/?probe=e80f86a0bf) | Feb 23, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [9caa421a49](https://linux-hardware.org/?probe=9caa421a49) | Feb 19, 2023 |
| Dell          | Latitude E4200              | Notebook    | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [eb8434e607](https://linux-hardware.org/?probe=eb8434e607) | Feb 15, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [22b77a1f78](https://linux-hardware.org/?probe=22b77a1f78) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [0a6d50bc2a](https://linux-hardware.org/?probe=0a6d50bc2a) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [75980f2f55](https://linux-hardware.org/?probe=75980f2f55) | Feb 13, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [24c1c37b05](https://linux-hardware.org/?probe=24c1c37b05) | Feb 13, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [abe1e578c0](https://linux-hardware.org/?probe=abe1e578c0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [94c0fadd44](https://linux-hardware.org/?probe=94c0fadd44) | Feb 10, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [e3bbec75c5](https://linux-hardware.org/?probe=e3bbec75c5) | Feb 10, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | Notebook    | [5d2f191a6f](https://linux-hardware.org/?probe=5d2f191a6f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | Notebook    | [668b9a0bfe](https://linux-hardware.org/?probe=668b9a0bfe) | Feb 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [f7f1655bc2](https://linux-hardware.org/?probe=f7f1655bc2) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [df167dd152](https://linux-hardware.org/?probe=df167dd152) | Feb 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [83e2eaf929](https://linux-hardware.org/?probe=83e2eaf929) | Feb 07, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [5ce729f67f](https://linux-hardware.org/?probe=5ce729f67f) | Feb 04, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [4029c64aec](https://linux-hardware.org/?probe=4029c64aec) | Feb 02, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [71bfc02926](https://linux-hardware.org/?probe=71bfc02926) | Feb 01, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [4e74651840](https://linux-hardware.org/?probe=4e74651840) | Jan 20, 2023 |
| Unknown       | X133                        | Notebook    | [ad31153d58](https://linux-hardware.org/?probe=ad31153d58) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [907784afb2](https://linux-hardware.org/?probe=907784afb2) | Jan 12, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| Acer          | Aspire 4738                 | Notebook    | [62914eb5f1](https://linux-hardware.org/?probe=62914eb5f1) | Jan 09, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [99d81ca38e](https://linux-hardware.org/?probe=99d81ca38e) | Jan 06, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [582d8bfa18](https://linux-hardware.org/?probe=582d8bfa18) | Jan 06, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| Acer          | Aspire A515-57T             | Notebook    | [bc905f86da](https://linux-hardware.org/?probe=bc905f86da) | Jan 02, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [1a8ed5998a](https://linux-hardware.org/?probe=1a8ed5998a) | Dec 30, 2022 |
| HP            | 431 Notebook                | Notebook    | [6a8d323e0c](https://linux-hardware.org/?probe=6a8d323e0c) | Dec 30, 2022 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | Notebook    | [e133481ab3](https://linux-hardware.org/?probe=e133481ab3) | Dec 29, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [ffbbc9ecb5](https://linux-hardware.org/?probe=ffbbc9ecb5) | Dec 26, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [f5277ba6a0](https://linux-hardware.org/?probe=f5277ba6a0) | Dec 26, 2022 |
| Dell          | Inspiron 14-3462            | Notebook    | [f95fd7ca72](https://linux-hardware.org/?probe=f95fd7ca72) | Dec 25, 2022 |
| Dell          | Inspiron 14-3462            | Notebook    | [7b38daddb5](https://linux-hardware.org/?probe=7b38daddb5) | Dec 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [e9dbd838ec](https://linux-hardware.org/?probe=e9dbd838ec) | Dec 25, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cfeb9545a3](https://linux-hardware.org/?probe=cfeb9545a3) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [06d690e9fe](https://linux-hardware.org/?probe=06d690e9fe) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | Notebook    | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Unknown       | NVIDIA Jetson Xavier NX ... | Soc         | [b05faac149](https://linux-hardware.org/?probe=b05faac149) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [fe7f585504](https://linux-hardware.org/?probe=fe7f585504) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [63cbf5d0e9](https://linux-hardware.org/?probe=63cbf5d0e9) | Dec 13, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [8489ca12d8](https://linux-hardware.org/?probe=8489ca12d8) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [3c5a5379a4](https://linux-hardware.org/?probe=3c5a5379a4) | Dec 13, 2022 |
| Biostar       | A520MH                      | Desktop     | [b6c4fdd80b](https://linux-hardware.org/?probe=b6c4fdd80b) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| ASUSTek       | BM5242                      | Desktop     | [d37b75dc52](https://linux-hardware.org/?probe=d37b75dc52) | Dec 10, 2022 |
| ASUSTek       | BM5242                      | Desktop     | [7c17c8d773](https://linux-hardware.org/?probe=7c17c8d773) | Dec 10, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [03c0b9e50d](https://linux-hardware.org/?probe=03c0b9e50d) | Dec 05, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [6890b98eeb](https://linux-hardware.org/?probe=6890b98eeb) | Dec 03, 2022 |
| HP            | Laptop 15-da3xxx            | Notebook    | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [913b35d3f0](https://linux-hardware.org/?probe=913b35d3f0) | Nov 25, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| Intel         | D946GZAB AAD66610-302       | Desktop     | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [09285b9428](https://linux-hardware.org/?probe=09285b9428) | Nov 13, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [f63b2757ea](https://linux-hardware.org/?probe=f63b2757ea) | Nov 12, 2022 |
| Unknown       | X133                        | Notebook    | [f89481552e](https://linux-hardware.org/?probe=f89481552e) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [abbb784ea9](https://linux-hardware.org/?probe=abbb784ea9) | Nov 09, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5384de4df1](https://linux-hardware.org/?probe=5384de4df1) | Nov 09, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [c08b835f58](https://linux-hardware.org/?probe=c08b835f58) | Nov 07, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [7db5fcb7b0](https://linux-hardware.org/?probe=7db5fcb7b0) | Nov 05, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [fbe5c4578c](https://linux-hardware.org/?probe=fbe5c4578c) | Nov 04, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [6eca80dabf](https://linux-hardware.org/?probe=6eca80dabf) | Nov 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [28cc86118e](https://linux-hardware.org/?probe=28cc86118e) | Nov 03, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [452ec1a1ee](https://linux-hardware.org/?probe=452ec1a1ee) | Nov 02, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [881cd60670](https://linux-hardware.org/?probe=881cd60670) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HP            | 3048h                       | Desktop     | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [e9ce57f1c1](https://linux-hardware.org/?probe=e9ce57f1c1) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc0a9a6b24](https://linux-hardware.org/?probe=fc0a9a6b24) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | Desktop     | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| HP            | 431 Notebook                | Notebook    | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Lenovo        | ThinkPad X230 2325CF6       | Notebook    | [622d37f892](https://linux-hardware.org/?probe=622d37f892) | Oct 15, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [fbb018d1ef](https://linux-hardware.org/?probe=fbb018d1ef) | Oct 14, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [5eafc7c12c](https://linux-hardware.org/?probe=5eafc7c12c) | Oct 13, 2022 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [1eb06e8e12](https://linux-hardware.org/?probe=1eb06e8e12) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [9f52e46640](https://linux-hardware.org/?probe=9f52e46640) | Oct 11, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [aa7d067a6f](https://linux-hardware.org/?probe=aa7d067a6f) | Oct 11, 2022 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [fc6e63a30a](https://linux-hardware.org/?probe=fc6e63a30a) | Oct 11, 2022 |
| HP            | ENVY Sleekbook 4            | Notebook    | [c14c5b1ee3](https://linux-hardware.org/?probe=c14c5b1ee3) | Oct 10, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [379f85dfb3](https://linux-hardware.org/?probe=379f85dfb3) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [f02be8db4c](https://linux-hardware.org/?probe=f02be8db4c) | Oct 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [700c5cc2bc](https://linux-hardware.org/?probe=700c5cc2bc) | Oct 05, 2022 |
| HP            | ENVY Sleekbook 4            | Notebook    | [0b820a1c7e](https://linux-hardware.org/?probe=0b820a1c7e) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Dell          | Latitude 5490               | Notebook    | [4c59654ea9](https://linux-hardware.org/?probe=4c59654ea9) | Sep 29, 2022 |
| Acer          | Aspire E3-111               | Notebook    | [6646e09597](https://linux-hardware.org/?probe=6646e09597) | Sep 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| Acer          | AOD257                      | Notebook    | [35ca1c0b33](https://linux-hardware.org/?probe=35ca1c0b33) | Sep 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6c34753f58](https://linux-hardware.org/?probe=6c34753f58) | Sep 22, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [0553290711](https://linux-hardware.org/?probe=0553290711) | Sep 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4b5a146dc9](https://linux-hardware.org/?probe=4b5a146dc9) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [34c1beb103](https://linux-hardware.org/?probe=34c1beb103) | Sep 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| Biostar       | A780L3B                     | Desktop     | [bc83f32ddf](https://linux-hardware.org/?probe=bc83f32ddf) | Sep 12, 2022 |
| Biostar       | A780L3B                     | Desktop     | [61057dc040](https://linux-hardware.org/?probe=61057dc040) | Sep 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ecadc5740](https://linux-hardware.org/?probe=1ecadc5740) | Sep 11, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [40f5cb1550](https://linux-hardware.org/?probe=40f5cb1550) | Sep 10, 2022 |
| Google        | Treeya                      | Notebook    | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Biostar       | A780L3B                     | Desktop     | [6463bcc136](https://linux-hardware.org/?probe=6463bcc136) | Sep 10, 2022 |
| Biostar       | A780L3B                     | Desktop     | [f65db263d7](https://linux-hardware.org/?probe=f65db263d7) | Sep 10, 2022 |
| Acer          | Aspire A314-22G             | Notebook    | [b6f9c0a0e7](https://linux-hardware.org/?probe=b6f9c0a0e7) | Sep 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [b77aa249c8](https://linux-hardware.org/?probe=b77aa249c8) | Sep 09, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [dc69b9dde6](https://linux-hardware.org/?probe=dc69b9dde6) | Sep 09, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [85d4f11486](https://linux-hardware.org/?probe=85d4f11486) | Sep 01, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [7d69c012fb](https://linux-hardware.org/?probe=7d69c012fb) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| HP            | 83F3                        | Desktop     | [71d62174e2](https://linux-hardware.org/?probe=71d62174e2) | Aug 27, 2022 |
| HP            | 1850                        | Desktop     | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [d9ff6dc8b4](https://linux-hardware.org/?probe=d9ff6dc8b4) | Aug 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [65b569c23c](https://linux-hardware.org/?probe=65b569c23c) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| realme        | RMNBXXXX                    | Notebook    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| HP            | Laptop 14-bs1xx             | Notebook    | [4b603b6b08](https://linux-hardware.org/?probe=4b603b6b08) | Aug 15, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [0ec4449fe2](https://linux-hardware.org/?probe=0ec4449fe2) | Aug 09, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [7a37d5e6a5](https://linux-hardware.org/?probe=7a37d5e6a5) | Aug 07, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [db237c843c](https://linux-hardware.org/?probe=db237c843c) | Aug 06, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [5251e7868a](https://linux-hardware.org/?probe=5251e7868a) | Aug 06, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [93ae3bfcfd](https://linux-hardware.org/?probe=93ae3bfcfd) | Aug 02, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [64da165357](https://linux-hardware.org/?probe=64da165357) | Aug 01, 2022 |
| Lenovo        | ThinkPad E590 20NB0032CD    | Notebook    | [502b0eeb39](https://linux-hardware.org/?probe=502b0eeb39) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [f47a0ecbf5](https://linux-hardware.org/?probe=f47a0ecbf5) | Jul 25, 2022 |
| MSI           | CX62 6QD                    | Notebook    | [d0c23fefca](https://linux-hardware.org/?probe=d0c23fefca) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [37521f84c8](https://linux-hardware.org/?probe=37521f84c8) | Jul 20, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [57ed9f00c7](https://linux-hardware.org/?probe=57ed9f00c7) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [f99189e2d0](https://linux-hardware.org/?probe=f99189e2d0) | Jul 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [2b7a37d662](https://linux-hardware.org/?probe=2b7a37d662) | Jul 16, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [24c803a5fc](https://linux-hardware.org/?probe=24c803a5fc) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| YANYU         | EPIC-C19                    | Desktop     | [5bda78db57](https://linux-hardware.org/?probe=5bda78db57) | Jul 11, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [b6a7451086](https://linux-hardware.org/?probe=b6a7451086) | Jul 11, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [b9c939b2e2](https://linux-hardware.org/?probe=b9c939b2e2) | Jul 09, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [88cc242e02](https://linux-hardware.org/?probe=88cc242e02) | Jul 09, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [264b084b00](https://linux-hardware.org/?probe=264b084b00) | Jul 08, 2022 |
| Acer          | Aspire E5-473G              | Notebook    | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [c9d2a76068](https://linux-hardware.org/?probe=c9d2a76068) | Jul 03, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [b7fedc25e4](https://linux-hardware.org/?probe=b7fedc25e4) | Jul 01, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [78eaeff700](https://linux-hardware.org/?probe=78eaeff700) | Jun 27, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [c23e943030](https://linux-hardware.org/?probe=c23e943030) | Jun 21, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [47f765c61f](https://linux-hardware.org/?probe=47f765c61f) | Jun 14, 2022 |
| MSI           | H81M-E33                    | Desktop     | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [017e41e32c](https://linux-hardware.org/?probe=017e41e32c) | Jun 07, 2022 |
| MSI           | H81M-E33                    | Desktop     | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [512fb81a9b](https://linux-hardware.org/?probe=512fb81a9b) | May 31, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| MSI           | MS-7717                     | Desktop     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [0656adeb11](https://linux-hardware.org/?probe=0656adeb11) | May 24, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [b884e51280](https://linux-hardware.org/?probe=b884e51280) | May 21, 2022 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | Notebook    | [a3e1bf045d](https://linux-hardware.org/?probe=a3e1bf045d) | May 20, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [debbc95647](https://linux-hardware.org/?probe=debbc95647) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Aspire E5-576G              | Notebook    | [27f577ec86](https://linux-hardware.org/?probe=27f577ec86) | May 10, 2022 |
| ECS           | A68M-C4DL                   | Desktop     | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5b877349c1](https://linux-hardware.org/?probe=5b877349c1) | May 09, 2022 |
| HP            | 212A                        | Desktop     | [acd660910f](https://linux-hardware.org/?probe=acd660910f) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [07ed7fd709](https://linux-hardware.org/?probe=07ed7fd709) | May 08, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [443d537d91](https://linux-hardware.org/?probe=443d537d91) | May 05, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1f3827f38e](https://linux-hardware.org/?probe=1f3827f38e) | Apr 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [cfd3bd53a8](https://linux-hardware.org/?probe=cfd3bd53a8) | Apr 18, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b824b88050](https://linux-hardware.org/?probe=b824b88050) | Apr 15, 2022 |
| Toshiba       | Satellite E45t-A            | Notebook    | [3698a21b91](https://linux-hardware.org/?probe=3698a21b91) | Apr 15, 2022 |
| Toshiba       | dynabook B45/A              | Notebook    | [f430a05b2d](https://linux-hardware.org/?probe=f430a05b2d) | Apr 09, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Shenzhen B... | NBPC1078                    | Tablet      | [33e297566b](https://linux-hardware.org/?probe=33e297566b) | Mar 30, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [03b7f74d31](https://linux-hardware.org/?probe=03b7f74d31) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [42e921877b](https://linux-hardware.org/?probe=42e921877b) | Mar 29, 2022 |
| HP            | 2B38                        | Desktop     | [99fd9bb200](https://linux-hardware.org/?probe=99fd9bb200) | Mar 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| MSI           | MS-7619                     | Desktop     | [65c73f26b0](https://linux-hardware.org/?probe=65c73f26b0) | Mar 22, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [111cf21b7f](https://linux-hardware.org/?probe=111cf21b7f) | Mar 21, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [95373e24b7](https://linux-hardware.org/?probe=95373e24b7) | Mar 16, 2022 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [ad5840ceb1](https://linux-hardware.org/?probe=ad5840ceb1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [1a9459872a](https://linux-hardware.org/?probe=1a9459872a) | Mar 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | Notebook    | [2f136d5bf5](https://linux-hardware.org/?probe=2f136d5bf5) | Mar 11, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [946300c067](https://linux-hardware.org/?probe=946300c067) | Mar 10, 2022 |
| Dell          | 0K9T56 A00                  | All in one  | [503d10d676](https://linux-hardware.org/?probe=503d10d676) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Dell          | 0K9T56 A00                  | All in one  | [206a6faf1c](https://linux-hardware.org/?probe=206a6faf1c) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | Notebook    | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [a1b757e234](https://linux-hardware.org/?probe=a1b757e234) | Mar 05, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [4f6714e804](https://linux-hardware.org/?probe=4f6714e804) | Mar 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [809dad2888](https://linux-hardware.org/?probe=809dad2888) | Mar 01, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [70f59ecacf](https://linux-hardware.org/?probe=70f59ecacf) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [2bc13ee0e2](https://linux-hardware.org/?probe=2bc13ee0e2) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [a8334fb3c3](https://linux-hardware.org/?probe=a8334fb3c3) | Feb 28, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f269ebd3a2](https://linux-hardware.org/?probe=f269ebd3a2) | Feb 28, 2022 |
| Acer          | AOD270                      | Notebook    | [491fbe6832](https://linux-hardware.org/?probe=491fbe6832) | Feb 21, 2022 |
| Acer          | AOD270                      | Notebook    | [90f9f56240](https://linux-hardware.org/?probe=90f9f56240) | Feb 21, 2022 |
| ASUSTek       | 900                         | Notebook    | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| HP            | Unknown                     | Notebook    | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | Notebook    | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| Lenovo        | ThinkPad X220 4290MN4       | Notebook    | [c0c3368738](https://linux-hardware.org/?probe=c0c3368738) | Feb 08, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [da8ce5d5b5](https://linux-hardware.org/?probe=da8ce5d5b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | Notebook    | [c8f0deedbc](https://linux-hardware.org/?probe=c8f0deedbc) | Feb 03, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [ca4c953595](https://linux-hardware.org/?probe=ca4c953595) | Jan 27, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [e01afda31f](https://linux-hardware.org/?probe=e01afda31f) | Jan 22, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [56bbe3562f](https://linux-hardware.org/?probe=56bbe3562f) | Jan 15, 2022 |
| HP            | Notebook                    | Notebook    | [826345f64e](https://linux-hardware.org/?probe=826345f64e) | Jan 13, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b04287afb1](https://linux-hardware.org/?probe=b04287afb1) | Jan 11, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [647b2f2da2](https://linux-hardware.org/?probe=647b2f2da2) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [266128f234](https://linux-hardware.org/?probe=266128f234) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [900b250e00](https://linux-hardware.org/?probe=900b250e00) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [5f4e7a5f4b](https://linux-hardware.org/?probe=5f4e7a5f4b) | Dec 28, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [e0b5bc37a4](https://linux-hardware.org/?probe=e0b5bc37a4) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [60daadb8b0](https://linux-hardware.org/?probe=60daadb8b0) | Dec 18, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| EMAXX TECH... | EMX-A55GT-iCafe V1.0        | Desktop     | [d6d799c3d8](https://linux-hardware.org/?probe=d6d799c3d8) | Nov 28, 2021 |
| Dell          | MXG061                      | Notebook    | [72d7e58977](https://linux-hardware.org/?probe=72d7e58977) | Nov 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [31e306a09d](https://linux-hardware.org/?probe=31e306a09d) | Nov 26, 2021 |
| Sony          | SVT13115FGS                 | Notebook    | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| HP            | ProBook 4730s               | Notebook    | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [7dbc9e305c](https://linux-hardware.org/?probe=7dbc9e305c) | Nov 11, 2021 |
| Toshiba       | NB255                       | Notebook    | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [bfd4d51591](https://linux-hardware.org/?probe=bfd4d51591) | Nov 09, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [2302fee654](https://linux-hardware.org/?probe=2302fee654) | Nov 09, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [249f25308e](https://linux-hardware.org/?probe=249f25308e) | Nov 08, 2021 |
| MSI           | B350M PRO-VDH               | Desktop     | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| HP            | Unknown                     | Notebook    | [4ce778dffc](https://linux-hardware.org/?probe=4ce778dffc) | Nov 06, 2021 |
| HP            | Unknown                     | Notebook    | [285c5d9c85](https://linux-hardware.org/?probe=285c5d9c85) | Nov 06, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| PERSONA       | MYBOOK 14                   | Notebook    | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| ECS           | G41T-R3                     | Desktop     | [892069341e](https://linux-hardware.org/?probe=892069341e) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [0ac8e061f1](https://linux-hardware.org/?probe=0ac8e061f1) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [655000678d](https://linux-hardware.org/?probe=655000678d) | Oct 30, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [fd3aefd54a](https://linux-hardware.org/?probe=fd3aefd54a) | Oct 27, 2021 |
| Dell          | Vostro 1400                 | Notebook    | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| Jumper        | EZbook                      | Notebook    | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HASEE Comp... | HNX4S                       | Notebook    | [aba8e89b9a](https://linux-hardware.org/?probe=aba8e89b9a) | Oct 17, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ec3329e68a](https://linux-hardware.org/?probe=ec3329e68a) | Oct 17, 2021 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [b8292ace4e](https://linux-hardware.org/?probe=b8292ace4e) | Oct 14, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [cb279cfeaf](https://linux-hardware.org/?probe=cb279cfeaf) | Oct 09, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [2444a742a8](https://linux-hardware.org/?probe=2444a742a8) | Oct 09, 2021 |
| HP            | Unknown                     | Notebook    | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e584636758](https://linux-hardware.org/?probe=e584636758) | Oct 04, 2021 |
| HP            | 14                          | Notebook    | [71ed61e3e0](https://linux-hardware.org/?probe=71ed61e3e0) | Oct 02, 2021 |
| HP            | 14                          | Notebook    | [8fc4fceaa1](https://linux-hardware.org/?probe=8fc4fceaa1) | Oct 02, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [a9a92c303c](https://linux-hardware.org/?probe=a9a92c303c) | Sep 24, 2021 |
| HP            | G60                         | Notebook    | [36ad0dc4bc](https://linux-hardware.org/?probe=36ad0dc4bc) | Sep 22, 2021 |
| HP            | Unknown                     | Notebook    | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [54cc0ff25b](https://linux-hardware.org/?probe=54cc0ff25b) | Sep 17, 2021 |
| ASUSTek       | X510UQ                      | Notebook    | [ffeab1f23c](https://linux-hardware.org/?probe=ffeab1f23c) | Sep 16, 2021 |
| Toshiba       | Satellite P845              | Notebook    | [27d8557047](https://linux-hardware.org/?probe=27d8557047) | Sep 12, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [4f8d90f8ef](https://linux-hardware.org/?probe=4f8d90f8ef) | Sep 12, 2021 |
| Toshiba       | Satellite C55D-B            | Notebook    | [e9f2b0ceda](https://linux-hardware.org/?probe=e9f2b0ceda) | Sep 11, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [9b620ade68](https://linux-hardware.org/?probe=9b620ade68) | Sep 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [f6388fb1b0](https://linux-hardware.org/?probe=f6388fb1b0) | Sep 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [a19fc44e26](https://linux-hardware.org/?probe=a19fc44e26) | Sep 07, 2021 |
| Dell          | Latitude E7450              | Notebook    | [531e888c8b](https://linux-hardware.org/?probe=531e888c8b) | Sep 04, 2021 |
| Lenovo        | ThinkPad X220 42863MJ       | Notebook    | [68cbfb3edb](https://linux-hardware.org/?probe=68cbfb3edb) | Sep 04, 2021 |
| Cubix         | Morph                       | Notebook    | [ffc9d93c9b](https://linux-hardware.org/?probe=ffc9d93c9b) | Aug 30, 2021 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [8ea19cfa9d](https://linux-hardware.org/?probe=8ea19cfa9d) | Aug 25, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [754a3fc1b5](https://linux-hardware.org/?probe=754a3fc1b5) | Aug 23, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [a384b10b00](https://linux-hardware.org/?probe=a384b10b00) | Aug 23, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [07f3a8a2c9](https://linux-hardware.org/?probe=07f3a8a2c9) | Aug 13, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Unknown       | Ionics Carrier Board Adv... | Desktop     | [62a47a18c2](https://linux-hardware.org/?probe=62a47a18c2) | Aug 12, 2021 |
| Apple         | MacBookAir4,1               | Notebook    | [cc00e74712](https://linux-hardware.org/?probe=cc00e74712) | Aug 09, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [a595ba80d3](https://linux-hardware.org/?probe=a595ba80d3) | Aug 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [90e7e1e008](https://linux-hardware.org/?probe=90e7e1e008) | Aug 05, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [4bf2729f88](https://linux-hardware.org/?probe=4bf2729f88) | Aug 04, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [57f0c24236](https://linux-hardware.org/?probe=57f0c24236) | Aug 03, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [3b5f090e84](https://linux-hardware.org/?probe=3b5f090e84) | Aug 01, 2021 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [4d9f134679](https://linux-hardware.org/?probe=4d9f134679) | Jul 30, 2021 |
| Biostar       | H110MHV3                    | Desktop     | [28344398db](https://linux-hardware.org/?probe=28344398db) | Jul 27, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [29d6febd6e](https://linux-hardware.org/?probe=29d6febd6e) | Jul 24, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f9c8b1d3ff](https://linux-hardware.org/?probe=f9c8b1d3ff) | Jul 24, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [9576a81942](https://linux-hardware.org/?probe=9576a81942) | Jul 23, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d86a6d7c9a](https://linux-hardware.org/?probe=d86a6d7c9a) | Jul 23, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Inspiron 7373               | Convertible | [5514ed070a](https://linux-hardware.org/?probe=5514ed070a) | Jul 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2151a0b75d](https://linux-hardware.org/?probe=2151a0b75d) | Jul 13, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8165fc4d95](https://linux-hardware.org/?probe=8165fc4d95) | Jul 06, 2021 |
| Lenovo        | ThinkPad X220 4291LL6       | Notebook    | [3e8ed9be02](https://linux-hardware.org/?probe=3e8ed9be02) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [ceedeef480](https://linux-hardware.org/?probe=ceedeef480) | Jul 01, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63055a9c60](https://linux-hardware.org/?probe=63055a9c60) | Jun 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [00ef418c43](https://linux-hardware.org/?probe=00ef418c43) | Jun 24, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ca6df82553](https://linux-hardware.org/?probe=ca6df82553) | Jun 22, 2021 |
| Biostar       | A320MH                      | Desktop     | [16e2552ccc](https://linux-hardware.org/?probe=16e2552ccc) | Jun 20, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | Notebook    | [69031eda12](https://linux-hardware.org/?probe=69031eda12) | Jun 18, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | Notebook    | [d7b3c8fc20](https://linux-hardware.org/?probe=d7b3c8fc20) | Jun 18, 2021 |
| Lenovo        | ThinkPad L530 24811K2       | Notebook    | [3517541065](https://linux-hardware.org/?probe=3517541065) | Jun 11, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [8a9bdad1fd](https://linux-hardware.org/?probe=8a9bdad1fd) | Jun 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [cc3c9e3798](https://linux-hardware.org/?probe=cc3c9e3798) | Jun 08, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [10ccc894a1](https://linux-hardware.org/?probe=10ccc894a1) | Jun 07, 2021 |
| Toshiba       | Satellite L515              | Notebook    | [72858b36e6](https://linux-hardware.org/?probe=72858b36e6) | Jun 02, 2021 |
| HP            | 82A5                        | Mini pc     | [08b98b6a88](https://linux-hardware.org/?probe=08b98b6a88) | May 29, 2021 |
| NEC Comput... | PC-VK25MXZCB                | Notebook    | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e31519274b](https://linux-hardware.org/?probe=e31519274b) | May 22, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [523ced455c](https://linux-hardware.org/?probe=523ced455c) | May 22, 2021 |
| Acer          | Aspire X1900                | Desktop     | [c4e0203ed9](https://linux-hardware.org/?probe=c4e0203ed9) | May 19, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [a14cf2a48e](https://linux-hardware.org/?probe=a14cf2a48e) | May 18, 2021 |
| Dell          | Inspiron 7373               | Convertible | [e4ffc93c6a](https://linux-hardware.org/?probe=e4ffc93c6a) | May 16, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | Notebook    | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [5f6a294b7d](https://linux-hardware.org/?probe=5f6a294b7d) | May 12, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cbe08b6f59](https://linux-hardware.org/?probe=cbe08b6f59) | May 09, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b2e6deb92e](https://linux-hardware.org/?probe=b2e6deb92e) | May 09, 2021 |
| ASUSTek       | X450MD                      | Notebook    | [b77e4abcd8](https://linux-hardware.org/?probe=b77e4abcd8) | May 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8467906058](https://linux-hardware.org/?probe=8467906058) | May 04, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [55bfc7d608](https://linux-hardware.org/?probe=55bfc7d608) | May 03, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [bb346e5b0c](https://linux-hardware.org/?probe=bb346e5b0c) | Apr 26, 2021 |
| ASUSTek       | EX-B365M-V5                 | Desktop     | [c169d54571](https://linux-hardware.org/?probe=c169d54571) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ff01911cb6](https://linux-hardware.org/?probe=ff01911cb6) | Apr 22, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b866ec6925](https://linux-hardware.org/?probe=b866ec6925) | Apr 20, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2e91d0c330](https://linux-hardware.org/?probe=2e91d0c330) | Apr 20, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Acer          | Nitro AN715-51              | Notebook    | [1cd3975ffa](https://linux-hardware.org/?probe=1cd3975ffa) | Apr 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ef9ba18b59](https://linux-hardware.org/?probe=ef9ba18b59) | Apr 11, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f66e7cbdfd](https://linux-hardware.org/?probe=f66e7cbdfd) | Apr 11, 2021 |
| HP            | Notebook                    | Notebook    | [023066c915](https://linux-hardware.org/?probe=023066c915) | Apr 08, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [b11b4274e4](https://linux-hardware.org/?probe=b11b4274e4) | Apr 08, 2021 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [23fdbd4caa](https://linux-hardware.org/?probe=23fdbd4caa) | Apr 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [2870ee333f](https://linux-hardware.org/?probe=2870ee333f) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [43b581a270](https://linux-hardware.org/?probe=43b581a270) | Apr 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d1b688c0a9](https://linux-hardware.org/?probe=d1b688c0a9) | Mar 31, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [40b47343b7](https://linux-hardware.org/?probe=40b47343b7) | Mar 28, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | Notebook    | [4f1b6f18bf](https://linux-hardware.org/?probe=4f1b6f18bf) | Mar 26, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | Notebook    | [aec0de9a30](https://linux-hardware.org/?probe=aec0de9a30) | Mar 26, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [c205b164c5](https://linux-hardware.org/?probe=c205b164c5) | Mar 26, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53f5f073d5](https://linux-hardware.org/?probe=53f5f073d5) | Mar 18, 2021 |
| MSI           | Z270 GAMING M7              | Desktop     | [b72439b299](https://linux-hardware.org/?probe=b72439b299) | Mar 17, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d9ec96bf45](https://linux-hardware.org/?probe=d9ec96bf45) | Mar 15, 2021 |
| Gigabyte      | GA-MA78GM-US2H              | Desktop     | [0f6037a19e](https://linux-hardware.org/?probe=0f6037a19e) | Mar 14, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [4b98fb1e80](https://linux-hardware.org/?probe=4b98fb1e80) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [42dd14b17d](https://linux-hardware.org/?probe=42dd14b17d) | Mar 09, 2021 |
| MSI           | CX62 7QL                    | Notebook    | [8241c594e5](https://linux-hardware.org/?probe=8241c594e5) | Mar 07, 2021 |
| eMachines     | eM250                       | Notebook    | [e20e648698](https://linux-hardware.org/?probe=e20e648698) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [ec866fbb40](https://linux-hardware.org/?probe=ec866fbb40) | Mar 04, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | Notebook    | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Acer          | TravelMate B115-M           | Notebook    | [46b6080608](https://linux-hardware.org/?probe=46b6080608) | Mar 02, 2021 |
| Acer          | TravelMate B115-M           | Notebook    | [4567b99e4e](https://linux-hardware.org/?probe=4567b99e4e) | Mar 02, 2021 |
| HP            | 82A5                        | Mini pc     | [fa16fba963](https://linux-hardware.org/?probe=fa16fba963) | Feb 28, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c627833398](https://linux-hardware.org/?probe=c627833398) | Feb 23, 2021 |
| Acer          | TravelMate B113             | Notebook    | [5ff9f9bb03](https://linux-hardware.org/?probe=5ff9f9bb03) | Feb 23, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3582928f83](https://linux-hardware.org/?probe=3582928f83) | Feb 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [d392637e95](https://linux-hardware.org/?probe=d392637e95) | Feb 20, 2021 |
| Lenovo        | G450 20022                  | Notebook    | [a98aa9041e](https://linux-hardware.org/?probe=a98aa9041e) | Feb 17, 2021 |
| Sony          | VPCEA36FA                   | Notebook    | [050c395bd5](https://linux-hardware.org/?probe=050c395bd5) | Feb 16, 2021 |
| Lenovo        | ThinkPad L530 24812K6       | Notebook    | [d78f3099e4](https://linux-hardware.org/?probe=d78f3099e4) | Feb 14, 2021 |
| AMD           | A88                         | Desktop     | [11ecb6d298](https://linux-hardware.org/?probe=11ecb6d298) | Feb 14, 2021 |
| Dell          | 0JP3NX A00                  | Desktop     | [3e5d4f837a](https://linux-hardware.org/?probe=3e5d4f837a) | Feb 10, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [6feab903f8](https://linux-hardware.org/?probe=6feab903f8) | Feb 05, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [5fa1dabba9](https://linux-hardware.org/?probe=5fa1dabba9) | Feb 05, 2021 |
| Acer          | TravelMate B113             | Notebook    | [7e439b847d](https://linux-hardware.org/?probe=7e439b847d) | Feb 04, 2021 |
| Dell          | 0JP3NX A00                  | Desktop     | [1f5d53a4a2](https://linux-hardware.org/?probe=1f5d53a4a2) | Feb 03, 2021 |
| QTQD          | Unknown                     | Desktop     | [2912607416](https://linux-hardware.org/?probe=2912607416) | Jan 27, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [4c9b44d2d4](https://linux-hardware.org/?probe=4c9b44d2d4) | Jan 26, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [76f0201d14](https://linux-hardware.org/?probe=76f0201d14) | Jan 26, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [795b4f4c7b](https://linux-hardware.org/?probe=795b4f4c7b) | Jan 26, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [6e4545c96a](https://linux-hardware.org/?probe=6e4545c96a) | Jan 23, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [603bb5d8e4](https://linux-hardware.org/?probe=603bb5d8e4) | Jan 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [c108942b4e](https://linux-hardware.org/?probe=c108942b4e) | Jan 19, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d8720f796](https://linux-hardware.org/?probe=9d8720f796) | Jan 19, 2021 |
| Acer          | Aspire X1900                | Desktop     | [d0a0250e62](https://linux-hardware.org/?probe=d0a0250e62) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [1e55ffedfe](https://linux-hardware.org/?probe=1e55ffedfe) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [6f9868755e](https://linux-hardware.org/?probe=6f9868755e) | Jan 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [15b8546bd4](https://linux-hardware.org/?probe=15b8546bd4) | Jan 11, 2021 |
| Gigabyte      | AM1M-S2P                    | Desktop     | [433295603d](https://linux-hardware.org/?probe=433295603d) | Jan 09, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [3f75d5f2e1](https://linux-hardware.org/?probe=3f75d5f2e1) | Jan 07, 2021 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [e6533b7b24](https://linux-hardware.org/?probe=e6533b7b24) | Jan 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [91ccfb9b5a](https://linux-hardware.org/?probe=91ccfb9b5a) | Jan 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b5fa895a91](https://linux-hardware.org/?probe=b5fa895a91) | Jan 05, 2021 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| Toshiba       | dynabook R73/W              | Notebook    | [b84a72cace](https://linux-hardware.org/?probe=b84a72cace) | Jan 02, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [031ad52398](https://linux-hardware.org/?probe=031ad52398) | Jan 01, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [11a5fd5bae](https://linux-hardware.org/?probe=11a5fd5bae) | Dec 30, 2020 |
| MSI           | IONA                        | Desktop     | [bfb84589dd](https://linux-hardware.org/?probe=bfb84589dd) | Dec 28, 2020 |
| MSI           | IONA                        | Desktop     | [0ec5c79eb8](https://linux-hardware.org/?probe=0ec5c79eb8) | Dec 26, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [459afa05c1](https://linux-hardware.org/?probe=459afa05c1) | Dec 26, 2020 |
| ECS           | H110M-C3D/C3V               | Desktop     | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| ASRock        | N68-S3                      | Desktop     | [bfa6bd97d5](https://linux-hardware.org/?probe=bfa6bd97d5) | Dec 23, 2020 |
| MSI           | MS-7541                     | Desktop     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | Desktop     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| HP            | ZBook Create G7 Notebook... | Notebook    | [e40ffb436c](https://linux-hardware.org/?probe=e40ffb436c) | Dec 20, 2020 |
| HP            | ZBook Create G7 Notebook... | Notebook    | [b1a2ee65e0](https://linux-hardware.org/?probe=b1a2ee65e0) | Dec 20, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [d186067403](https://linux-hardware.org/?probe=d186067403) | Dec 17, 2020 |
| ASRock        | N68-S3                      | Desktop     | [1d3067d8cb](https://linux-hardware.org/?probe=1d3067d8cb) | Dec 17, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [6a99509d25](https://linux-hardware.org/?probe=6a99509d25) | Dec 16, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [e315898f10](https://linux-hardware.org/?probe=e315898f10) | Dec 16, 2020 |
| Toshiba       | dynabook R73/W              | Notebook    | [96710da884](https://linux-hardware.org/?probe=96710da884) | Dec 14, 2020 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [d942ed05b5](https://linux-hardware.org/?probe=d942ed05b5) | Dec 13, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [db8ffa8342](https://linux-hardware.org/?probe=db8ffa8342) | Dec 06, 2020 |
| HP            | 8061                        | Desktop     | [0f0bc8b49a](https://linux-hardware.org/?probe=0f0bc8b49a) | Dec 04, 2020 |
| HP            | 8061                        | Desktop     | [a63c8237f1](https://linux-hardware.org/?probe=a63c8237f1) | Dec 04, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| NEC Comput... | IS8XM                       | Desktop     | [57afeee773](https://linux-hardware.org/?probe=57afeee773) | Nov 30, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [4dd4445d4d](https://linux-hardware.org/?probe=4dd4445d4d) | Nov 29, 2020 |
| Acer          | Aspire A315-53G             | Notebook    | [9498233954](https://linux-hardware.org/?probe=9498233954) | Nov 26, 2020 |
| eMachines     | eM350                       | Notebook    | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | Notebook    | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [d63213adad](https://linux-hardware.org/?probe=d63213adad) | Nov 22, 2020 |
| ASUSTek       | K43SD                       | Notebook    | [869c3395e8](https://linux-hardware.org/?probe=869c3395e8) | Nov 20, 2020 |
| ASUSTek       | K43SD                       | Notebook    | [3ce330e163](https://linux-hardware.org/?probe=3ce330e163) | Nov 19, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [354202e98e](https://linux-hardware.org/?probe=354202e98e) | Nov 19, 2020 |
| HP            | Unknown                     | Notebook    | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [f86e0d2af5](https://linux-hardware.org/?probe=f86e0d2af5) | Nov 11, 2020 |
| HP            | 3031h                       | Desktop     | [fb54f48959](https://linux-hardware.org/?probe=fb54f48959) | Nov 10, 2020 |
| HP            | 8061                        | Desktop     | [7936b223e9](https://linux-hardware.org/?probe=7936b223e9) | Nov 10, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [2c9a8f0838](https://linux-hardware.org/?probe=2c9a8f0838) | Nov 08, 2020 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [c812c2b6f9](https://linux-hardware.org/?probe=c812c2b6f9) | Nov 07, 2020 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [e21be2124d](https://linux-hardware.org/?probe=e21be2124d) | Nov 04, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [7c1cb4cac0](https://linux-hardware.org/?probe=7c1cb4cac0) | Nov 02, 2020 |
| HP            | 8061                        | Desktop     | [d11b92ef18](https://linux-hardware.org/?probe=d11b92ef18) | Nov 01, 2020 |
| Gigabyte      | H81M-DS2                    | Desktop     | [a3cdedf351](https://linux-hardware.org/?probe=a3cdedf351) | Oct 30, 2020 |
| Lenovo        | ThinkPad X220 4290MN4       | Notebook    | [f305f22059](https://linux-hardware.org/?probe=f305f22059) | Oct 29, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [80d72786c1](https://linux-hardware.org/?probe=80d72786c1) | Oct 26, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [3919d06624](https://linux-hardware.org/?probe=3919d06624) | Oct 25, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [e110233803](https://linux-hardware.org/?probe=e110233803) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [ecf79444ac](https://linux-hardware.org/?probe=ecf79444ac) | Oct 21, 2020 |
| Pegatron      | IPMSB-H61                   | Desktop     | [c569d86fff](https://linux-hardware.org/?probe=c569d86fff) | Oct 19, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [bfe2deec18](https://linux-hardware.org/?probe=bfe2deec18) | Oct 17, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [2f0952fbb5](https://linux-hardware.org/?probe=2f0952fbb5) | Oct 15, 2020 |
| HP            | 8061                        | Desktop     | [b2cf684801](https://linux-hardware.org/?probe=b2cf684801) | Oct 13, 2020 |
| Lenovo        | ThinkPad X260 20F5S04206    | Notebook    | [147c40fe70](https://linux-hardware.org/?probe=147c40fe70) | Oct 12, 2020 |
| HP            | Notebook                    | Notebook    | [8cbf9133f7](https://linux-hardware.org/?probe=8cbf9133f7) | Oct 11, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 15                          | Notebook    | [c44a5eaea1](https://linux-hardware.org/?probe=c44a5eaea1) | Oct 07, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [11b8e32835](https://linux-hardware.org/?probe=11b8e32835) | Oct 06, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | Notebook    | [c1812f8ee0](https://linux-hardware.org/?probe=c1812f8ee0) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | Notebook    | [4e98739f72](https://linux-hardware.org/?probe=4e98739f72) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [73fd7565f6](https://linux-hardware.org/?probe=73fd7565f6) | Oct 05, 2020 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [2d6256e8c5](https://linux-hardware.org/?probe=2d6256e8c5) | Oct 05, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [a2cee62097](https://linux-hardware.org/?probe=a2cee62097) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [a8678813c5](https://linux-hardware.org/?probe=a8678813c5) | Oct 01, 2020 |
| ASUSTek       | K75DE                       | Notebook    | [b4cb493794](https://linux-hardware.org/?probe=b4cb493794) | Sep 28, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [074fb7cc02](https://linux-hardware.org/?probe=074fb7cc02) | Sep 28, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [32556e96bf](https://linux-hardware.org/?probe=32556e96bf) | Sep 27, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [7176092b12](https://linux-hardware.org/?probe=7176092b12) | Sep 27, 2020 |
| HP            | 8061                        | Desktop     | [1d3e0a6b3d](https://linux-hardware.org/?probe=1d3e0a6b3d) | Sep 25, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [bf1e06fe4f](https://linux-hardware.org/?probe=bf1e06fe4f) | Sep 23, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [337ba51577](https://linux-hardware.org/?probe=337ba51577) | Sep 23, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | Notebook    | [72f627fd0e](https://linux-hardware.org/?probe=72f627fd0e) | Sep 21, 2020 |
| Apple         | MacBookAir3,1               | Notebook    | [73e9128968](https://linux-hardware.org/?probe=73e9128968) | Sep 21, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [546b3fec83](https://linux-hardware.org/?probe=546b3fec83) | Sep 16, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [f0ac65615d](https://linux-hardware.org/?probe=f0ac65615d) | Sep 14, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [5acf002102](https://linux-hardware.org/?probe=5acf002102) | Sep 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1cf35a6180](https://linux-hardware.org/?probe=1cf35a6180) | Sep 13, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [d2fde2a21e](https://linux-hardware.org/?probe=d2fde2a21e) | Sep 13, 2020 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [5a3c4a23bb](https://linux-hardware.org/?probe=5a3c4a23bb) | Sep 12, 2020 |
| ASUSTek       | X441URK                     | Notebook    | [f883ed5e4b](https://linux-hardware.org/?probe=f883ed5e4b) | Sep 12, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [a2e7991749](https://linux-hardware.org/?probe=a2e7991749) | Sep 11, 2020 |
| Dell          | Latitude E4300              | Notebook    | [8b163ddf1e](https://linux-hardware.org/?probe=8b163ddf1e) | Sep 09, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [eaff730455](https://linux-hardware.org/?probe=eaff730455) | Sep 09, 2020 |
| Apple         | MacBookAir2,1               | Notebook    | [c4b26d8019](https://linux-hardware.org/?probe=c4b26d8019) | Sep 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [809af585ab](https://linux-hardware.org/?probe=809af585ab) | Sep 08, 2020 |
| Lenovo        | ThinkPad E580 20KSA00UAU    | Notebook    | [becbbe530b](https://linux-hardware.org/?probe=becbbe530b) | Sep 07, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [9c779dc588](https://linux-hardware.org/?probe=9c779dc588) | Sep 04, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [efeb5dd920](https://linux-hardware.org/?probe=efeb5dd920) | Sep 04, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [9557e9d02c](https://linux-hardware.org/?probe=9557e9d02c) | Sep 04, 2020 |
| Acer          | Aspire A315-41G             | Notebook    | [ec1a232ba9](https://linux-hardware.org/?probe=ec1a232ba9) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | Notebook    | [3cff1527be](https://linux-hardware.org/?probe=3cff1527be) | Sep 03, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0fda90e55c](https://linux-hardware.org/?probe=0fda90e55c) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [4a5f93ed76](https://linux-hardware.org/?probe=4a5f93ed76) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [e11793b02c](https://linux-hardware.org/?probe=e11793b02c) | Sep 02, 2020 |
| ASUSTek       | X441URK                     | Notebook    | [35b06d497e](https://linux-hardware.org/?probe=35b06d497e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | Notebook    | [100fc7862e](https://linux-hardware.org/?probe=100fc7862e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | Notebook    | [6d9f5403eb](https://linux-hardware.org/?probe=6d9f5403eb) | Sep 02, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [288f4f772c](https://linux-hardware.org/?probe=288f4f772c) | Sep 01, 2020 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS0SA0J    | Notebook    | [5e85d0fa0e](https://linux-hardware.org/?probe=5e85d0fa0e) | Aug 31, 2020 |
| Clevo         | M7x0S                       | Notebook    | [7efc902d33](https://linux-hardware.org/?probe=7efc902d33) | Aug 31, 2020 |
| Clevo         | M7x0S                       | Notebook    | [58b7846f61](https://linux-hardware.org/?probe=58b7846f61) | Aug 30, 2020 |
| Dell          | Latitude E7450              | Notebook    | [7b6b25e684](https://linux-hardware.org/?probe=7b6b25e684) | Aug 27, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [290159761f](https://linux-hardware.org/?probe=290159761f) | Aug 27, 2020 |
| HP            | Pavilion g4                 | Notebook    | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [8747f9eb75](https://linux-hardware.org/?probe=8747f9eb75) | Aug 22, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [b1d91b9932](https://linux-hardware.org/?probe=b1d91b9932) | Aug 21, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [ecd87de5e0](https://linux-hardware.org/?probe=ecd87de5e0) | Aug 21, 2020 |
| Sony          | SVF14216SGP                 | Notebook    | [31495e375f](https://linux-hardware.org/?probe=31495e375f) | Aug 19, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [b5e17b6229](https://linux-hardware.org/?probe=b5e17b6229) | Aug 16, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | Notebook    | [56702de7d4](https://linux-hardware.org/?probe=56702de7d4) | Aug 15, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | Notebook    | [d868e4a7f9](https://linux-hardware.org/?probe=d868e4a7f9) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [a5e0d02669](https://linux-hardware.org/?probe=a5e0d02669) | Aug 12, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [6b5b2287e0](https://linux-hardware.org/?probe=6b5b2287e0) | Aug 07, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [aa6089eda7](https://linux-hardware.org/?probe=aa6089eda7) | Aug 06, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [86ee9f7736](https://linux-hardware.org/?probe=86ee9f7736) | Aug 06, 2020 |
| MSI           | GV62 8RD                    | Notebook    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| HP            | Pavilion g4                 | Notebook    | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | Notebook    | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| HP            | 805D                        | Desktop     | [b0f200fe77](https://linux-hardware.org/?probe=b0f200fe77) | Jul 29, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [64a762e6b8](https://linux-hardware.org/?probe=64a762e6b8) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [7dd7f12bb9](https://linux-hardware.org/?probe=7dd7f12bb9) | Jul 25, 2020 |
| HP            | Notebook                    | Notebook    | [55ab6c06c5](https://linux-hardware.org/?probe=55ab6c06c5) | Jul 25, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [23d8c2d2cf](https://linux-hardware.org/?probe=23d8c2d2cf) | Jul 25, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ca9dc81053](https://linux-hardware.org/?probe=ca9dc81053) | Jul 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [d486d4bc03](https://linux-hardware.org/?probe=d486d4bc03) | Jul 24, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [f12d8d16e5](https://linux-hardware.org/?probe=f12d8d16e5) | Jul 16, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [d1bc3c3a8a](https://linux-hardware.org/?probe=d1bc3c3a8a) | Jul 10, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [cb26f9925f](https://linux-hardware.org/?probe=cb26f9925f) | Jul 09, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [2e3aac14fe](https://linux-hardware.org/?probe=2e3aac14fe) | Jul 02, 2020 |
| Acer          | Aspire V5-431               | Notebook    | [0287b85983](https://linux-hardware.org/?probe=0287b85983) | Jun 30, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | Notebook    | [fb0a45d925](https://linux-hardware.org/?probe=fb0a45d925) | Jun 27, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | Notebook    | [99e750162d](https://linux-hardware.org/?probe=99e750162d) | Jun 27, 2020 |
| eMachines     | eM350                       | Notebook    | [b699bf9fb6](https://linux-hardware.org/?probe=b699bf9fb6) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [1107791eab](https://linux-hardware.org/?probe=1107791eab) | Jun 22, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [22963b821f](https://linux-hardware.org/?probe=22963b821f) | Jun 20, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [c5779593cc](https://linux-hardware.org/?probe=c5779593cc) | Jun 20, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [7c1783588a](https://linux-hardware.org/?probe=7c1783588a) | Jun 12, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [cbbefff0a6](https://linux-hardware.org/?probe=cbbefff0a6) | Jun 12, 2020 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [ec653ae1fc](https://linux-hardware.org/?probe=ec653ae1fc) | Jun 11, 2020 |
| HP            | 15                          | Notebook    | [a4b90e7ad1](https://linux-hardware.org/?probe=a4b90e7ad1) | Jun 05, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Dell          | Latitude 7490               | Notebook    | [b7b69c9cbf](https://linux-hardware.org/?probe=b7b69c9cbf) | Jun 05, 2020 |
| MSI           | MS-N014                     | Notebook    | [e9fd398a70](https://linux-hardware.org/?probe=e9fd398a70) | Jun 04, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [5cde7141d6](https://linux-hardware.org/?probe=5cde7141d6) | Jun 02, 2020 |
| Google        | Caroline                    | Notebook    | [4e305a0551](https://linux-hardware.org/?probe=4e305a0551) | May 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [6bdc484d30](https://linux-hardware.org/?probe=6bdc484d30) | May 25, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [a73c8a7057](https://linux-hardware.org/?probe=a73c8a7057) | May 24, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [8d5860b41f](https://linux-hardware.org/?probe=8d5860b41f) | May 23, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [931084ae9c](https://linux-hardware.org/?probe=931084ae9c) | May 23, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [e35a078b83](https://linux-hardware.org/?probe=e35a078b83) | May 23, 2020 |
| HP            | 17E2                        | Mini pc     | [b62ca0352c](https://linux-hardware.org/?probe=b62ca0352c) | May 22, 2020 |
| HP            | EliteBook 745 G3            | Notebook    | [ebd5778f8c](https://linux-hardware.org/?probe=ebd5778f8c) | May 22, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [a36437dc35](https://linux-hardware.org/?probe=a36437dc35) | May 22, 2020 |
| Lenovo        | ThinkPad X280 20KES69A00    | Notebook    | [c1fc46e405](https://linux-hardware.org/?probe=c1fc46e405) | May 21, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [58ad8d0b01](https://linux-hardware.org/?probe=58ad8d0b01) | May 18, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [9e80b645d9](https://linux-hardware.org/?probe=9e80b645d9) | May 17, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [32fb20af11](https://linux-hardware.org/?probe=32fb20af11) | May 16, 2020 |
| Lenovo        | IdeaPad S540-15IML 81NG     | Notebook    | [89e361466e](https://linux-hardware.org/?probe=89e361466e) | May 14, 2020 |
| HP            | Notebook                    | Notebook    | [142457c9ea](https://linux-hardware.org/?probe=142457c9ea) | May 12, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [7ae56aa829](https://linux-hardware.org/?probe=7ae56aa829) | May 11, 2020 |
| Acer          | Aspire M5-481PT             | Notebook    | [772cc038ae](https://linux-hardware.org/?probe=772cc038ae) | May 09, 2020 |
| Acer          | Aspire M5-481PT             | Notebook    | [332e871ec3](https://linux-hardware.org/?probe=332e871ec3) | May 09, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [429d4a7720](https://linux-hardware.org/?probe=429d4a7720) | May 03, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [028f510367](https://linux-hardware.org/?probe=028f510367) | May 03, 2020 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [d4cbef0ab2](https://linux-hardware.org/?probe=d4cbef0ab2) | May 02, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [60ee09d8aa](https://linux-hardware.org/?probe=60ee09d8aa) | May 02, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [285c59f702](https://linux-hardware.org/?probe=285c59f702) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [36bb48017f](https://linux-hardware.org/?probe=36bb48017f) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [1f91672dce](https://linux-hardware.org/?probe=1f91672dce) | Apr 28, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [6b07754d1d](https://linux-hardware.org/?probe=6b07754d1d) | Apr 27, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [e487e06d2c](https://linux-hardware.org/?probe=e487e06d2c) | Apr 26, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [390a1cbbb3](https://linux-hardware.org/?probe=390a1cbbb3) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [252b646f8b](https://linux-hardware.org/?probe=252b646f8b) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [0fe6d54c09](https://linux-hardware.org/?probe=0fe6d54c09) | Apr 25, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [eec2e1e90f](https://linux-hardware.org/?probe=eec2e1e90f) | Apr 24, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [cb0a381ca1](https://linux-hardware.org/?probe=cb0a381ca1) | Apr 22, 2020 |
| Lenovo        | ThinkPad T460s 20F9004FU... | Notebook    | [8eacfd828e](https://linux-hardware.org/?probe=8eacfd828e) | Apr 21, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [dbe36dfd4f](https://linux-hardware.org/?probe=dbe36dfd4f) | Apr 21, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [06c5a92500](https://linux-hardware.org/?probe=06c5a92500) | Apr 18, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b87b3feefd](https://linux-hardware.org/?probe=b87b3feefd) | Apr 18, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [d092c3db85](https://linux-hardware.org/?probe=d092c3db85) | Apr 16, 2020 |
| Clevo         | M7x0S                       | Notebook    | [7ba28306d0](https://linux-hardware.org/?probe=7ba28306d0) | Apr 16, 2020 |
| Clevo         | M7x0S                       | Notebook    | [23aa6b7beb](https://linux-hardware.org/?probe=23aa6b7beb) | Apr 16, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [8eca04a69b](https://linux-hardware.org/?probe=8eca04a69b) | Apr 14, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [576c3b1853](https://linux-hardware.org/?probe=576c3b1853) | Apr 13, 2020 |
| TriGem Com... | DreamSys                    | Desktop     | [e5a22f4123](https://linux-hardware.org/?probe=e5a22f4123) | Apr 09, 2020 |
| Clevo         | E412X                       | Notebook    | [0cca012f20](https://linux-hardware.org/?probe=0cca012f20) | Apr 09, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [3bf24f9dd6](https://linux-hardware.org/?probe=3bf24f9dd6) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c00e4e1a0e](https://linux-hardware.org/?probe=c00e4e1a0e) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [087a36a4bd](https://linux-hardware.org/?probe=087a36a4bd) | Apr 04, 2020 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [35b973ebbb](https://linux-hardware.org/?probe=35b973ebbb) | Apr 03, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [68ecbaa367](https://linux-hardware.org/?probe=68ecbaa367) | Apr 03, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [9e4c202def](https://linux-hardware.org/?probe=9e4c202def) | Apr 03, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [3959954db3](https://linux-hardware.org/?probe=3959954db3) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | Notebook    | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9355c0ff9e](https://linux-hardware.org/?probe=9355c0ff9e) | Apr 01, 2020 |
| HP            | 0A5Ch                       | Desktop     | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c6dbdb971](https://linux-hardware.org/?probe=8c6dbdb971) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [70b408e2f0](https://linux-hardware.org/?probe=70b408e2f0) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [be10de1b16](https://linux-hardware.org/?probe=be10de1b16) | Mar 24, 2020 |
| Dell          | Latitude E6430              | Notebook    | [e38eb04918](https://linux-hardware.org/?probe=e38eb04918) | Mar 23, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [17ec9504f1](https://linux-hardware.org/?probe=17ec9504f1) | Mar 22, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [92e778ba2a](https://linux-hardware.org/?probe=92e778ba2a) | Mar 21, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f7cbec79e8](https://linux-hardware.org/?probe=f7cbec79e8) | Mar 15, 2020 |
| Gigabyte      | H310M DS2                   | Desktop     | [529f84f7d1](https://linux-hardware.org/?probe=529f84f7d1) | Mar 12, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [636f6029b4](https://linux-hardware.org/?probe=636f6029b4) | Mar 11, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [861919e59d](https://linux-hardware.org/?probe=861919e59d) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [dff3f373f6](https://linux-hardware.org/?probe=dff3f373f6) | Mar 08, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2b1b62332c](https://linux-hardware.org/?probe=2b1b62332c) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [e52b770dff](https://linux-hardware.org/?probe=e52b770dff) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [a06909608c](https://linux-hardware.org/?probe=a06909608c) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [b3e1633a13](https://linux-hardware.org/?probe=b3e1633a13) | Mar 08, 2020 |
| Sony          | SVP13215CDB                 | Notebook    | [0aac039fdc](https://linux-hardware.org/?probe=0aac039fdc) | Mar 06, 2020 |
| Dell          | Precision 3540              | Notebook    | [b30c51350c](https://linux-hardware.org/?probe=b30c51350c) | Mar 05, 2020 |
| ASUSTek       | X441SA                      | Notebook    | [e06798387f](https://linux-hardware.org/?probe=e06798387f) | Mar 05, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [a1d3a510e8](https://linux-hardware.org/?probe=a1d3a510e8) | Mar 04, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [6e803cdc23](https://linux-hardware.org/?probe=6e803cdc23) | Mar 02, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [fb41a1d23f](https://linux-hardware.org/?probe=fb41a1d23f) | Mar 02, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [162a9b6da7](https://linux-hardware.org/?probe=162a9b6da7) | Feb 22, 2020 |
| Acer          | Aspire V5-471G              | Notebook    | [85eca92a3b](https://linux-hardware.org/?probe=85eca92a3b) | Feb 22, 2020 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [f5bb829dbb](https://linux-hardware.org/?probe=f5bb829dbb) | Feb 22, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [e3c94b5684](https://linux-hardware.org/?probe=e3c94b5684) | Feb 22, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [c549e93013](https://linux-hardware.org/?probe=c549e93013) | Feb 21, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [7994c923a0](https://linux-hardware.org/?probe=7994c923a0) | Feb 21, 2020 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [3dc258b050](https://linux-hardware.org/?probe=3dc258b050) | Feb 20, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [5cce680c2e](https://linux-hardware.org/?probe=5cce680c2e) | Feb 20, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [75b9cc12a9](https://linux-hardware.org/?probe=75b9cc12a9) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [de6eba23f1](https://linux-hardware.org/?probe=de6eba23f1) | Feb 09, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [78d658fc64](https://linux-hardware.org/?probe=78d658fc64) | Feb 09, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [4f64209449](https://linux-hardware.org/?probe=4f64209449) | Feb 07, 2020 |
| Lenovo        | IdeaPad Y460                | Notebook    | [ece975c659](https://linux-hardware.org/?probe=ece975c659) | Feb 01, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [cb21aa111e](https://linux-hardware.org/?probe=cb21aa111e) | Jan 31, 2020 |
| Lenovo        | IdeaPad Y460                | Notebook    | [1a614a42a8](https://linux-hardware.org/?probe=1a614a42a8) | Jan 30, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [973270aee7](https://linux-hardware.org/?probe=973270aee7) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [459627eda2](https://linux-hardware.org/?probe=459627eda2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [61dfac2df2](https://linux-hardware.org/?probe=61dfac2df2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [880daf6c76](https://linux-hardware.org/?probe=880daf6c76) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [0d020faa5c](https://linux-hardware.org/?probe=0d020faa5c) | Jan 24, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [e3389e7b39](https://linux-hardware.org/?probe=e3389e7b39) | Jan 23, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [298e5dbad9](https://linux-hardware.org/?probe=298e5dbad9) | Jan 20, 2020 |
| Dell          | Inspiron N4030              | Notebook    | [f3d828d4b1](https://linux-hardware.org/?probe=f3d828d4b1) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [600afa3fd4](https://linux-hardware.org/?probe=600afa3fd4) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [57c3c5d09b](https://linux-hardware.org/?probe=57c3c5d09b) | Jan 11, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [1e5c712f0b](https://linux-hardware.org/?probe=1e5c712f0b) | Jan 05, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [d5df64e644](https://linux-hardware.org/?probe=d5df64e644) | Dec 29, 2019 |
| Acer          | Aspire A311-31              | Notebook    | [1db743caaf](https://linux-hardware.org/?probe=1db743caaf) | Dec 24, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [eecdfa47b7](https://linux-hardware.org/?probe=eecdfa47b7) | Dec 15, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [44ecc526a8](https://linux-hardware.org/?probe=44ecc526a8) | Dec 12, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [e4fecb44bc](https://linux-hardware.org/?probe=e4fecb44bc) | Dec 05, 2019 |
| HP            | ProBook 440 G6              | Notebook    | [20bcca591f](https://linux-hardware.org/?probe=20bcca591f) | Dec 03, 2019 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [777d549872](https://linux-hardware.org/?probe=777d549872) | Nov 22, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [c5d4684f24](https://linux-hardware.org/?probe=c5d4684f24) | Nov 11, 2019 |
| Acer          | AO722                       | Notebook    | [a54b8c9315](https://linux-hardware.org/?probe=a54b8c9315) | Nov 08, 2019 |
| Pegatron      | IPMSB-H61                   | Desktop     | [857c9bddda](https://linux-hardware.org/?probe=857c9bddda) | Nov 07, 2019 |
| Pegatron      | IPMSB-H61                   | Desktop     | [55e7a33a87](https://linux-hardware.org/?probe=55e7a33a87) | Nov 07, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [ac217a032c](https://linux-hardware.org/?probe=ac217a032c) | Nov 03, 2019 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [619b0ce294](https://linux-hardware.org/?probe=619b0ce294) | Oct 09, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [0f199af685](https://linux-hardware.org/?probe=0f199af685) | Sep 22, 2019 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [8d497813d1](https://linux-hardware.org/?probe=8d497813d1) | Sep 19, 2019 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [7c06f63670](https://linux-hardware.org/?probe=7c06f63670) | Sep 18, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [36b5c905d1](https://linux-hardware.org/?probe=36b5c905d1) | Sep 16, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | Desktop     | [e5d5c98452](https://linux-hardware.org/?probe=e5d5c98452) | Sep 11, 2019 |
| Wacom         | Citiq Companion             | Tablet      | [5a97b2a1a7](https://linux-hardware.org/?probe=5a97b2a1a7) | Sep 10, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | Notebook    | [35b92b56a8](https://linux-hardware.org/?probe=35b92b56a8) | Sep 03, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [eaadda80df](https://linux-hardware.org/?probe=eaadda80df) | Aug 25, 2019 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [6674277b6a](https://linux-hardware.org/?probe=6674277b6a) | Aug 23, 2019 |
| ASRock        | A780GM-LE                   | Desktop     | [80fb7e01aa](https://linux-hardware.org/?probe=80fb7e01aa) | Aug 22, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | Notebook    | [e57d7bb95a](https://linux-hardware.org/?probe=e57d7bb95a) | Aug 14, 2019 |
| Wacom         | Citiq Companion             | Tablet      | [ac4803b894](https://linux-hardware.org/?probe=ac4803b894) | Aug 11, 2019 |
| HP            | Pavilion dm4                | Notebook    | [42df53b120](https://linux-hardware.org/?probe=42df53b120) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | Desktop     | [1f7f86ed9e](https://linux-hardware.org/?probe=1f7f86ed9e) | Jul 13, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [ac8f1708fb](https://linux-hardware.org/?probe=ac8f1708fb) | Jun 30, 2019 |
| Acer          | Aspire 3935                 | Notebook    | [2288125313](https://linux-hardware.org/?probe=2288125313) | Jun 27, 2019 |
| Acer          | Aspire 3935                 | Notebook    | [fbb934cec8](https://linux-hardware.org/?probe=fbb934cec8) | Jun 27, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [704346ee85](https://linux-hardware.org/?probe=704346ee85) | Jun 24, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3fb0bfffca](https://linux-hardware.org/?probe=3fb0bfffca) | Jun 24, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| Acer          | Aspire 5516                 | Notebook    | [92691e9024](https://linux-hardware.org/?probe=92691e9024) | Jun 13, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [db39b4023e](https://linux-hardware.org/?probe=db39b4023e) | Jun 03, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [833afc1cd1](https://linux-hardware.org/?probe=833afc1cd1) | May 12, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [04903c40d9](https://linux-hardware.org/?probe=04903c40d9) | May 10, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [1d29713c8b](https://linux-hardware.org/?probe=1d29713c8b) | May 02, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [d3769c3f4d](https://linux-hardware.org/?probe=d3769c3f4d) | Apr 16, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [31f0b418f9](https://linux-hardware.org/?probe=31f0b418f9) | Apr 16, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| HP            | ENVY 4                      | Notebook    | [97135eda99](https://linux-hardware.org/?probe=97135eda99) | Mar 31, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ac265b9b6d](https://linux-hardware.org/?probe=ac265b9b6d) | Mar 27, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [18266bd48a](https://linux-hardware.org/?probe=18266bd48a) | Jan 06, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [d3d3b75d21](https://linux-hardware.org/?probe=d3d3b75d21) | Jan 04, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [6f63118ade](https://linux-hardware.org/?probe=6f63118ade) | Jan 04, 2019 |
| Acer          | TravelMate B113             | Notebook    | [fea3b127ea](https://linux-hardware.org/?probe=fea3b127ea) | Dec 25, 2018 |
| ASUSTek       | GL553VD                     | Notebook    | [d43361263c](https://linux-hardware.org/?probe=d43361263c) | Dec 24, 2018 |
| ASUSTek       | X540NA                      | Notebook    | [03eadbe056](https://linux-hardware.org/?probe=03eadbe056) | Nov 20, 2018 |
| ASUSTek       | X540NA                      | Notebook    | [f06d9e94e9](https://linux-hardware.org/?probe=f06d9e94e9) | Nov 20, 2018 |
| Lenovo        | No DPK                      | Desktop     | [02bdd4779e](https://linux-hardware.org/?probe=02bdd4779e) | Oct 21, 2018 |
| Lenovo        | No DPK                      | Desktop     | [d98528c04e](https://linux-hardware.org/?probe=d98528c04e) | Oct 21, 2018 |
| MSI           | A68HM-E33 V2                | Desktop     | [aee859c42b](https://linux-hardware.org/?probe=aee859c42b) | Jan 05, 2018 |
| MSI           | GT70 2PC                    | Notebook    | [020492bfa1](https://linux-hardware.org/?probe=020492bfa1) | Jul 04, 2017 |
| MSI           | GT70 2PC                    | Notebook    | [a5dafd1181](https://linux-hardware.org/?probe=a5dafd1181) | Jul 04, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Philippines/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 57        | 10.56%  |
| Ubuntu 22.04                 | 28        | 5.19%   |
| Pop!_OS 20.04                | 25        | 4.63%   |
| Ubuntu 18.04                 | 22        | 4.07%   |
| KDE neon 20.04               | 18        | 3.33%   |
| Pop!_OS 22.04                | 16        | 2.96%   |
| OpenMandriva 4.2             | 13        | 2.41%   |
| Zorin 15                     | 11        | 2.04%   |
| Fedora 36                    | 11        | 2.04%   |
| Pop!_OS 21.04                | 10        | 1.85%   |
| Manjaro                      | 10        | 1.85%   |
| Zorin 16                     | 9         | 1.67%   |
| Arch Rolling                 | 9         | 1.67%   |
| Linux Mint 20.2              | 8         | 1.48%   |
| BlackPanther 18.1            | 8         | 1.48%   |
| Arch                         | 8         | 1.48%   |
| OpenMandriva 4.3             | 7         | 1.3%    |
| Pop!_OS 20.10                | 6         | 1.11%   |
| Linux Mint 20.1              | 6         | 1.11%   |
| Kubuntu 22.04                | 6         | 1.11%   |
| KDE neon 22.04               | 6         | 1.11%   |
| Fedora 33                    | 6         | 1.11%   |
| Endless 3.7.7                | 6         | 1.11%   |
| Debian 11                    | 6         | 1.11%   |
| Ubuntu 20.10                 | 5         | 0.93%   |
| Linux Mint 19.3              | 5         | 0.93%   |
| Fedora 37                    | 5         | 0.93%   |
| Fedora 35                    | 5         | 0.93%   |
| Fedora 32                    | 5         | 0.93%   |
| Endless 3.7.6                | 5         | 0.93%   |
| BlackPanther 16.2            | 5         | 0.93%   |
| Xubuntu 20.04                | 4         | 0.74%   |
| Ubuntu Unity 18.04           | 4         | 0.74%   |
| Ubuntu 21.10                 | 4         | 0.74%   |
| Pop!_OS 21.10                | 4         | 0.74%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 0.74%   |
| LMDE 4                       | 4         | 0.74%   |
| Linux Mint 20.3              | 4         | 0.74%   |
| Fedora 34                    | 4         | 0.74%   |
| Ubuntu 19.10                 | 3         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 121       | 23.68%  |
| Pop!_OS       | 61        | 11.94%  |
| Linux Mint    | 38        | 7.44%   |
| Fedora        | 36        | 7.05%   |
| Endless       | 32        | 6.26%   |
| KDE neon      | 26        | 5.09%   |
| OpenMandriva  | 25        | 4.89%   |
| Zorin         | 20        | 3.91%   |
| Manjaro       | 19        | 3.72%   |
| Arch          | 17        | 3.33%   |
| Debian        | 11        | 2.15%   |
| Kubuntu       | 10        | 1.96%   |
| Kali          | 10        | 1.96%   |
| BlackPanther  | 10        | 1.96%   |
| Xubuntu       | 8         | 1.57%   |
| Elementary    | 6         | 1.17%   |
| Ubuntu Unity  | 5         | 0.98%   |
| openSUSE      | 5         | 0.98%   |
| Nobara        | 5         | 0.98%   |
| ArcoLinux     | 5         | 0.98%   |
| Ubuntu MATE   | 4         | 0.78%   |
| LMDE          | 4         | 0.78%   |
| EndeavourOS   | 4         | 0.78%   |
| ROSA          | 3         | 0.59%   |
| Lubuntu       | 3         | 0.59%   |
| SteamOS       | 2         | 0.39%   |
| Peppermint    | 2         | 0.39%   |
| MX            | 2         | 0.39%   |
| Gentoo        | 2         | 0.39%   |
| Clear Linux   | 2         | 0.39%   |
| Ubuntu Budgie | 1         | 0.2%    |
| Sparky        | 1         | 0.2%    |
| Solus         | 1         | 0.2%    |
| Slackware     | 1         | 0.2%    |
| Reborn OS     | 1         | 0.2%    |
| Raspbian      | 1         | 0.2%    |
| Parrot        | 1         | 0.2%    |
| Linux Lite    | 1         | 0.2%    |
| Hash Linux    | 1         | 0.2%    |
| Garuda Linux  | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 18        | 3.08%   |
| 5.10.14-desktop-1omv4002 | 13        | 2.23%   |
| 5.3.0-28-generic         | 10        | 1.71%   |
| 5.4.0-7634-generic       | 8         | 1.37%   |
| 5.4.0-48-generic         | 8         | 1.37%   |
| 4.18.16-desktop-1bP      | 8         | 1.37%   |
| 5.3.0-23-generic         | 7         | 1.2%    |
| 5.16.7-desktop-1omv4003  | 7         | 1.2%    |
| 5.8.0-7630-generic       | 6         | 1.03%   |
| 5.8.0-14-generic         | 6         | 1.03%   |
| 5.19.0-32-generic        | 6         | 1.03%   |
| 5.15.0-56-generic        | 6         | 1.03%   |
| 5.15.0-52-generic        | 6         | 1.03%   |
| 5.15.0-41-generic        | 6         | 1.03%   |
| 5.4.0-58-generic         | 5         | 0.86%   |
| 5.4.0-47-generic         | 5         | 0.86%   |
| 5.15.0-58-generic        | 5         | 0.86%   |
| 5.15.0-50-generic        | 5         | 0.86%   |
| 5.11.0-7620-generic      | 5         | 0.86%   |
| 4.9.20-desktop-pae-1bP   | 5         | 0.86%   |
| 5.4.0-7642-generic       | 4         | 0.68%   |
| 5.4.0-73-generic         | 4         | 0.68%   |
| 5.4.0-19-generic         | 4         | 0.68%   |
| 5.15.0-48-generic        | 4         | 0.68%   |
| 5.13.0-7614-generic      | 4         | 0.68%   |
| 5.13.0-30-generic        | 4         | 0.68%   |
| 5.13.0-28-generic        | 4         | 0.68%   |
| 4.18.0-25-generic        | 4         | 0.68%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.51%   |
| 6.0.6-76060006-generic   | 3         | 0.51%   |
| 6.0.0-kali6-amd64        | 3         | 0.51%   |
| 5.8.0-7642-generic       | 3         | 0.51%   |
| 5.4.0-80-generic         | 3         | 0.51%   |
| 5.4.0-74-generic         | 3         | 0.51%   |
| 5.4.0-52-generic         | 3         | 0.51%   |
| 5.4.0-45-generic         | 3         | 0.51%   |
| 5.4.0-31-generic         | 3         | 0.51%   |
| 5.3.0-46-generic         | 3         | 0.51%   |
| 5.17.5-76051705-generic  | 3         | 0.51%   |
| 5.15.0-60-generic        | 3         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 97        | 17.38%  |
| 5.15.0  | 55        | 9.86%   |
| 5.3.0   | 32        | 5.73%   |
| 5.13.0  | 32        | 5.73%   |
| 5.8.0   | 31        | 5.56%   |
| 5.11.0  | 26        | 4.66%   |
| 4.15.0  | 21        | 3.76%   |
| 5.10.14 | 13        | 2.33%   |
| 5.19.0  | 12        | 2.15%   |
| 5.0.0   | 11        | 1.97%   |
| 4.18.0  | 10        | 1.79%   |
| 4.19.0  | 8         | 1.43%   |
| 4.18.16 | 8         | 1.43%   |
| 5.16.7  | 7         | 1.25%   |
| 5.10.0  | 7         | 1.25%   |
| 5.17.5  | 6         | 1.08%   |
| 4.9.20  | 6         | 1.08%   |
| 6.0.6   | 5         | 0.9%    |
| 6.0.0   | 4         | 0.72%   |
| 6.2.0   | 3         | 0.54%   |
| 6.1.1   | 3         | 0.54%   |
| 5.9.16  | 3         | 0.54%   |
| 5.18.13 | 3         | 0.54%   |
| 5.18.10 | 3         | 0.54%   |
| 5.18.0  | 3         | 0.54%   |
| 5.16.0  | 3         | 0.54%   |
| 5.11.16 | 3         | 0.54%   |
| 4.4.0   | 3         | 0.54%   |
| 6.2.7   | 2         | 0.36%   |
| 6.2.6   | 2         | 0.36%   |
| 6.1.12  | 2         | 0.36%   |
| 6.0.7   | 2         | 0.36%   |
| 6.0.16  | 2         | 0.36%   |
| 6.0.12  | 2         | 0.36%   |
| 5.9.11  | 2         | 0.36%   |
| 5.8.14  | 2         | 0.36%   |
| 5.4.20  | 2         | 0.36%   |
| 5.19.13 | 2         | 0.36%   |
| 5.19.12 | 2         | 0.36%   |
| 5.18.12 | 2         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 108       | 19.64%  |
| 5.15    | 75        | 13.64%  |
| 5.8     | 38        | 6.91%   |
| 5.13    | 35        | 6.36%   |
| 5.3     | 34        | 6.18%   |
| 5.10    | 33        | 6%      |
| 5.11    | 31        | 5.64%   |
| 5.19    | 22        | 4%      |
| 4.15    | 21        | 3.82%   |
| 6.0     | 20        | 3.64%   |
| 5.16    | 18        | 3.27%   |
| 4.18    | 18        | 3.27%   |
| 6.1     | 14        | 2.55%   |
| 5.18    | 12        | 2.18%   |
| 5.0     | 12        | 2.18%   |
| 6.2     | 8         | 1.45%   |
| 5.17    | 8         | 1.45%   |
| 4.9     | 8         | 1.45%   |
| 4.19    | 8         | 1.45%   |
| 5.9     | 7         | 1.27%   |
| 5.14    | 4         | 0.73%   |
| 4.4     | 4         | 0.73%   |
| 5.6     | 3         | 0.55%   |
| 5.7     | 2         | 0.36%   |
| 5.12    | 2         | 0.36%   |
| 4.13    | 2         | 0.36%   |
| 5.2     | 1         | 0.18%   |
| 5.1     | 1         | 0.18%   |
| 3.8     | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 471       | 94.96%  |
| i686    | 15        | 3.02%   |
| armv7l  | 5         | 1.01%   |
| aarch64 | 5         | 1.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 245       | 47.39%  |
| KDE5            | 102       | 19.73%  |
| XFCE            | 39        | 7.54%   |
| Unknown         | 38        | 7.35%   |
| X-Cinnamon      | 33        | 6.38%   |
| KDE             | 17        | 3.29%   |
| MATE            | 11        | 2.13%   |
| Pantheon        | 5         | 0.97%   |
| LXQt            | 5         | 0.97%   |
| Unity           | 4         | 0.77%   |
| LXDE            | 3         | 0.58%   |
| Cinnamon        | 3         | 0.58%   |
| openbox         | 2         | 0.39%   |
| Budgie          | 2         | 0.39%   |
| sway            | 1         | 0.19%   |
| river           | 1         | 0.19%   |
| GNOME Flashback | 1         | 0.19%   |
| dwm             | 1         | 0.19%   |
| default         | 1         | 0.19%   |
| Deepin          | 1         | 0.19%   |
| Cutefish        | 1         | 0.19%   |
| awesome         | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 411       | 81.39%  |
| Wayland | 67        | 13.27%  |
| Unknown | 18        | 3.56%   |
| Tty     | 9         | 1.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 293       | 57.12%  |
| SDDM    | 72        | 14.04%  |
| GDM     | 54        | 10.53%  |
| GDM3    | 44        | 8.58%   |
| LightDM | 37        | 7.21%   |
| TDM     | 10        | 1.95%   |
| SLiM    | 1         | 0.19%   |
| MDM     | 1         | 0.19%   |
| LXDM    | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_PH   | 239       | 46.95%  |
| en_US   | 193       | 37.92%  |
| Unknown | 44        | 8.64%   |
| C       | 11        | 2.16%   |
| de_DE   | 7         | 1.38%   |
| en_GB   | 5         | 0.98%   |
| zh_CN   | 2         | 0.39%   |
| zh_HK   | 1         | 0.2%    |
| fil_PH  | 1         | 0.2%    |
| en_NZ   | 1         | 0.2%    |
| en_IN   | 1         | 0.2%    |
| en_HK   | 1         | 0.2%    |
| en_CA   | 1         | 0.2%    |
| en_AU   | 1         | 0.2%    |
| da_DK   | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 260       | 51.49%  |
| EFI  | 245       | 48.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 387       | 76.03%  |
| Btrfs   | 57        | 11.2%   |
| Overlay | 45        | 8.84%   |
| Unknown | 11        | 2.16%   |
| Xfs     | 4         | 0.79%   |
| Ext2    | 3         | 0.59%   |
| Zfs     | 2         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 305       | 59.92%  |
| GPT     | 155       | 30.45%  |
| MBR     | 49        | 9.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 444       | 87.75%  |
| Yes       | 62        | 12.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 375       | 73.96%  |
| Yes       | 132       | 26.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 74        | 15.01%  |
| ASUSTek Computer          | 64        | 12.98%  |
| Acer                      | 61        | 12.37%  |
| Hewlett-Packard           | 55        | 11.16%  |
| Dell                      | 43        | 8.72%   |
| Gigabyte Technology       | 42        | 8.52%   |
| MSI                       | 40        | 8.11%   |
| Toshiba                   | 13        | 2.64%   |
| ASRock                    | 13        | 2.64%   |
| Apple                     | 9         | 1.83%   |
| Unknown                   | 8         | 1.62%   |
| Biostar                   | 7         | 1.42%   |
| Samsung Electronics       | 5         | 1.01%   |
| Raspberry Pi Foundation   | 5         | 1.01%   |
| Foxconn                   | 5         | 1.01%   |
| Sony                      | 4         | 0.81%   |
| NEC Computers             | 4         | 0.81%   |
| EMAXX TECHNOLOGY          | 4         | 0.81%   |
| ECS                       | 4         | 0.81%   |
| Clevo                     | 4         | 0.81%   |
| eMachines                 | 3         | 0.61%   |
| Pegatron                  | 2         | 0.41%   |
| Jumper                    | 2         | 0.41%   |
| Intel                     | 2         | 0.41%   |
| Google                    | 2         | 0.41%   |
| YANYU                     | 1         | 0.2%    |
| Xunlong                   | 1         | 0.2%    |
| Wacom                     | 1         | 0.2%    |
| Valve                     | 1         | 0.2%    |
| TriGem Computer           | 1         | 0.2%    |
| Shenzhen Bmorn Technology | 1         | 0.2%    |
| realme                    | 1         | 0.2%    |
| QTQD                      | 1         | 0.2%    |
| PERSONA                   | 1         | 0.2%    |
| Notebook                  | 1         | 0.2%    |
| Microsoft                 | 1         | 0.2%    |
| JOOYON                    | 1         | 0.2%    |
| HUAWEI                    | 1         | 0.2%    |
| HASEE Computer            | 1         | 0.2%    |
| Fujitsu                   | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 12        | 2.43%   |
| Acer Aspire ES1-132        | 6         | 1.22%   |
| MSI MS-7309                | 5         | 1.01%   |
| ASRock B450M Steel Legend  | 5         | 1.01%   |
| RPi Raspberry Pi           | 4         | 0.81%   |
| MSI MS-7721                | 4         | 0.81%   |
| Gigabyte F2A68HM-S1        | 4         | 0.81%   |
| Gigabyte A320M-S2H V2      | 4         | 0.81%   |
| ASUS All Series            | 4         | 0.81%   |
| HP Notebook                | 3         | 0.61%   |
| Foxconn G31MX Series       | 3         | 0.61%   |
| Clevo M7x0S                | 3         | 0.61%   |
| ASUS P8H61-M LX3 PLUS R2.0 | 3         | 0.61%   |
| Pegatron IPMSB-H61         | 2         | 0.41%   |
| MSI MS-7C94                | 2         | 0.41%   |
| Lenovo Yoga 520-14IKB 81C8 | 2         | 0.41%   |
| Lenovo V110-14IAP 80TF     | 2         | 0.41%   |
| Jumper EZbook              | 2         | 0.41%   |
| HP Pavilion Notebook       | 2         | 0.41%   |
| Gigabyte Z590 AORUS ULTRA  | 2         | 0.41%   |
| Gigabyte H97M-D3H          | 2         | 0.41%   |
| Foxconn 500B Microtower    | 2         | 0.41%   |
| eMachines eM350            | 2         | 0.41%   |
| Dell OptiPlex 9010 AIO     | 2         | 0.41%   |
| Dell Latitude E7450        | 2         | 0.41%   |
| Dell Inspiron 5567         | 2         | 0.41%   |
| Biostar A320MH             | 2         | 0.41%   |
| ASUS X540NA                | 2         | 0.41%   |
| ASUS PRIME B250M-K         | 2         | 0.41%   |
| ASUS EX-H310M-V3 R2.0      | 2         | 0.41%   |
| ASUS A68HM-K               | 2         | 0.41%   |
| Apple MacBookPro5,5        | 2         | 0.41%   |
| Acer TravelMate P249-G2-M  | 2         | 0.41%   |
| Acer TravelMate B113       | 2         | 0.41%   |
| Acer Swift SF314-57        | 2         | 0.41%   |
| Acer Aspire E5-551G        | 2         | 0.41%   |
| Acer Aspire E3-111         | 2         | 0.41%   |
| Acer Aspire A315-51        | 2         | 0.41%   |
| Acer Aspire A315-41G       | 2         | 0.41%   |
| YANYU EPIC-C19             | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Acer Aspire         | 43        | 8.72%   |
| Lenovo ThinkPad     | 32        | 6.49%   |
| Lenovo IdeaPad      | 26        | 5.27%   |
| Dell Inspiron       | 18        | 3.65%   |
| HP Pavilion         | 12        | 2.43%   |
| Unknown             | 12        | 2.43%   |
| Dell OptiPlex       | 9         | 1.83%   |
| Acer TravelMate     | 8         | 1.62%   |
| Toshiba Satellite   | 7         | 1.42%   |
| Dell Latitude       | 7         | 1.42%   |
| ASUS TUF            | 7         | 1.42%   |
| ASUS ROG            | 7         | 1.42%   |
| HP Laptop           | 6         | 1.22%   |
| RPi Raspberry       | 5         | 1.01%   |
| MSI MS-7309         | 5         | 1.01%   |
| HP Compaq           | 5         | 1.01%   |
| Gigabyte A320M-S2H  | 5         | 1.01%   |
| ASUS VivoBook       | 5         | 1.01%   |
| ASUS PRIME          | 5         | 1.01%   |
| ASUS P8H61-M        | 5         | 1.01%   |
| ASRock B450M        | 5         | 1.01%   |
| MSI MS-7721         | 4         | 0.81%   |
| HP ProDesk          | 4         | 0.81%   |
| Gigabyte F2A68HM-S1 | 4         | 0.81%   |
| ASUS All            | 4         | 0.81%   |
| Lenovo Yoga         | 3         | 0.61%   |
| Lenovo Legion       | 3         | 0.61%   |
| HP ProBook          | 3         | 0.61%   |
| HP Notebook         | 3         | 0.61%   |
| HP ENVY             | 3         | 0.61%   |
| HP EliteBook        | 3         | 0.61%   |
| Gigabyte B450       | 3         | 0.61%   |
| Foxconn G31MX       | 3         | 0.61%   |
| Dell Vostro         | 3         | 0.61%   |
| Clevo M7x0S         | 3         | 0.61%   |
| Acer Swift          | 3         | 0.61%   |
| Acer Nitro          | 3         | 0.61%   |
| Toshiba TECRA       | 2         | 0.41%   |
| Toshiba dynabook    | 2         | 0.41%   |
| Pegatron IPMSB-H61  | 2         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 46        | 9.33%   |
| 2012    | 44        | 8.92%   |
| 2019    | 43        | 8.72%   |
| 2017    | 40        | 8.11%   |
| 2014    | 40        | 8.11%   |
| 2016    | 37        | 7.51%   |
| 2021    | 34        | 6.9%    |
| 2020    | 34        | 6.9%    |
| 2010    | 31        | 6.29%   |
| 2011    | 30        | 6.09%   |
| 2015    | 27        | 5.48%   |
| 2013    | 23        | 4.67%   |
| 2009    | 21        | 4.26%   |
| 2022    | 14        | 2.84%   |
| Unknown | 9         | 1.83%   |
| 2008    | 8         | 1.62%   |
| 2007    | 6         | 1.22%   |
| 2006    | 6         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 297       | 60.24%  |
| Desktop        | 169       | 34.28%  |
| System on chip | 7         | 1.42%   |
| Mini pc        | 7         | 1.42%   |
| Convertible    | 6         | 1.22%   |
| All in one     | 4         | 0.81%   |
| Tablet         | 3         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 445       | 89.9%   |
| Enabled  | 50        | 10.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 491       | 99.59%  |
| Yes  | 2         | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 125       | 24.65%  |
| 3.01-4.0    | 113       | 22.29%  |
| 8.01-16.0   | 104       | 20.51%  |
| 16.01-24.0  | 69        | 13.61%  |
| 1.01-2.0    | 43        | 8.48%   |
| 32.01-64.0  | 23        | 4.54%   |
| 2.01-3.0    | 13        | 2.56%   |
| 64.01-256.0 | 7         | 1.38%   |
| 0.51-1.0    | 6         | 1.18%   |
| 24.01-32.0  | 4         | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 194       | 34.95%  |
| 2.01-3.0   | 164       | 29.55%  |
| 4.01-8.0   | 65        | 11.71%  |
| 3.01-4.0   | 60        | 10.81%  |
| 0.51-1.0   | 42        | 7.57%   |
| 8.01-16.0  | 18        | 3.24%   |
| 0.01-0.5   | 9         | 1.62%   |
| 24.01-32.0 | 1         | 0.18%   |
| 16.01-24.0 | 1         | 0.18%   |
| Unknown    | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 321       | 62.33%  |
| 2      | 132       | 25.63%  |
| 3      | 29        | 5.63%   |
| 4      | 16        | 3.11%   |
| 5      | 8         | 1.55%   |
| 0      | 6         | 1.17%   |
| 14     | 1         | 0.19%   |
| 13     | 1         | 0.19%   |
| 6      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 359       | 71.51%  |
| Yes       | 143       | 28.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 416       | 84.38%  |
| No        | 77        | 15.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 382       | 77.02%  |
| No        | 114       | 22.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 299       | 59.92%  |
| No        | 200       | 40.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Philippines | 493       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Quezon City         | 84        | 15.27%  |
| Cebu City           | 35        | 6.36%   |
| Davao City          | 27        | 4.91%   |
| Angeles City        | 24        | 4.36%   |
| Manila              | 20        | 3.64%   |
| Cagayan de Oro      | 20        | 3.64%   |
| Pasig               | 17        | 3.09%   |
| Caloocan City       | 17        | 3.09%   |
| Paranaque City      | 15        | 2.73%   |
| Bacolod City        | 15        | 2.73%   |
| San Miguel          | 12        | 2.18%   |
| Manajao             | 12        | 2.18%   |
| Bacoor              | 12        | 2.18%   |
| Mandaluyong City    | 11        | 2%      |
| Makati City         | 11        | 2%      |
| San Jose del Monte  | 10        | 1.82%   |
| Iligan City         | 10        | 1.82%   |
| Imus                | 9         | 1.64%   |
| Zamboanga City      | 8         | 1.45%   |
| Tarlac City         | 8         | 1.45%   |
| Santa Rosa          | 8         | 1.45%   |
| Lahug               | 8         | 1.45%   |
| Iloilo City         | 8         | 1.45%   |
| San Fernando City   | 6         | 1.09%   |
| Malolos             | 6         | 1.09%   |
| Las Pinas           | 6         | 1.09%   |
| Antipolo City       | 6         | 1.09%   |
| Dasmarinas          | 5         | 0.91%   |
| City of Muntinglupa | 5         | 0.91%   |
| San Pablo City      | 4         | 0.73%   |
| Lucena City         | 4         | 0.73%   |
| General Santos      | 4         | 0.73%   |
| Baguio City         | 4         | 0.73%   |
| Taguig              | 3         | 0.55%   |
| San Pedro           | 3         | 0.55%   |
| Mandaue City        | 3         | 0.55%   |
| Lipa City           | 3         | 0.55%   |
| Legazpi             | 3         | 0.55%   |
| Cabanatuan City     | 3         | 0.55%   |
| Tuguegarao City     | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 128       | 182    | 17.63%  |
| WDC                       | 115       | 141    | 15.84%  |
| Toshiba                   | 72        | 97     | 9.92%   |
| Samsung Electronics       | 56        | 73     | 7.71%   |
| Kingston                  | 39        | 48     | 5.37%   |
| SanDisk                   | 34        | 41     | 4.68%   |
| Hitachi                   | 32        | 52     | 4.41%   |
| Unknown                   | 30        | 38     | 4.13%   |
| SK hynix                  | 18        | 32     | 2.48%   |
| HGST                      | 14        | 16     | 1.93%   |
| Micron Technology         | 11        | 15     | 1.52%   |
| Crucial                   | 10        | 12     | 1.38%   |
| Intel                     | 9         | 10     | 1.24%   |
| A-DATA Technology         | 9         | 12     | 1.24%   |
| Transcend                 | 8         | 8      | 1.1%    |
| Team                      | 8         | 12     | 1.1%    |
| Ramsta                    | 8         | 9      | 1.1%    |
| Lexar                     | 7         | 8      | 0.96%   |
| Gigabyte Technology       | 7         | 10     | 0.96%   |
| Fujitsu                   | 7         | 8      | 0.96%   |
| Phison                    | 5         | 5      | 0.69%   |
| WALRAM                    | 4         | 4      | 0.55%   |
| HS-SSD-C100               | 4         | 5      | 0.55%   |
| China                     | 4         | 9      | 0.55%   |
| Apple                     | 4         | 4      | 0.55%   |
| PNY                       | 3         | 3      | 0.41%   |
| Micron/Crucial Technology | 3         | 3      | 0.41%   |
| LITEONIT                  | 3         | 5      | 0.41%   |
| KingSpec                  | 3         | 3      | 0.41%   |
| Indilinx                  | 3         | 3      | 0.41%   |
| HS-SSD-E100               | 3         | 3      | 0.41%   |
| Unknown                   | 3         | 3      | 0.41%   |
| XPG                       | 2         | 2      | 0.28%   |
| UMIS                      | 2         | 2      | 0.28%   |
| Silicon Motion            | 2         | 2      | 0.28%   |
| ShiJi                     | 2         | 2      | 0.28%   |
| Phison Electronics        | 2         | 2      | 0.28%   |
| Patriot                   | 2         | 2      | 0.28%   |
| Netac                     | 2         | 2      | 0.28%   |
| Lite-On                   | 2         | 4      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB        | 16        | 2.05%   |
| Seagate ST1000DM010-2EP102 1TB  | 12        | 1.53%   |
| Seagate ST500DM002-1BD142 500GB | 11        | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB  | 11        | 1.41%   |
| Toshiba MQ01ABD100 1TB          | 8         | 1.02%   |
| Kingston SA400S37120G 120GB SSD | 8         | 1.02%   |
| WDC WD5000LPCX-21VHAT0 500GB    | 7         | 0.9%    |
| Toshiba MQ04ABF100 1TB          | 7         | 0.9%    |
| Toshiba DT01ACA050 500GB        | 7         | 0.9%    |
| Samsung SSD 860 EVO 500GB       | 7         | 0.9%    |
| Kingston SA400S37240G 240GB SSD | 7         | 0.9%    |
| Unknown MMC Card  32GB          | 6         | 0.77%   |
| Seagate ST500LT012-1DG142 500GB | 6         | 0.77%   |
| WDC WD10JPVX-22JC3T0 1TB        | 5         | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB        | 5         | 0.64%   |
| Seagate ST4000DM004-2CV104 4TB  | 5         | 0.64%   |
| Seagate ST1000LM049-2GH172 1TB  | 5         | 0.64%   |
| Samsung SSD 860 EVO 250GB       | 5         | 0.64%   |
| Hitachi HTS543232A7A384 320GB   | 5         | 0.64%   |
| Hitachi HDS721050CLA362 500GB   | 5         | 0.64%   |
| WDC WD5000LPCX-60VHAT0 500GB    | 4         | 0.51%   |
| WDC WD10SPZX-21Z10T0 1TB        | 4         | 0.51%   |
| Unknown MMC Card  64GB          | 4         | 0.51%   |
| Seagate ST500LT012-9WS142 500GB | 4         | 0.51%   |
| Seagate ST2000LM007-1R8174 2TB  | 4         | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB  | 4         | 0.51%   |
| Seagate BUP Slim 2TB            | 4         | 0.51%   |
| SanDisk SDSSDA240G 240GB        | 4         | 0.51%   |
| Hitachi HDS721616PLA380 160GB   | 4         | 0.51%   |
| HGST HTS725050A7E630 500GB      | 4         | 0.51%   |
| HGST HTS541010A9E680 1TB        | 4         | 0.51%   |
| WDC WD5000LPVX-22V0TT0 500GB    | 3         | 0.38%   |
| WDC WD5000LPCX-24VHAT0 500GB    | 3         | 0.38%   |
| WDC WD5000AZLX-60K2TA0 500GB    | 3         | 0.38%   |
| WDC WD10EZEX-22MFCA0 1TB        | 3         | 0.38%   |
| Transcend TS128GSSD370S 128GB   | 3         | 0.38%   |
| Toshiba MK2555GSX 250GB         | 3         | 0.38%   |
| Toshiba DT01ACA100 1TB          | 3         | 0.38%   |
| SK hynix NVMe SSD Drive 512GB   | 3         | 0.38%   |
| Seagate ST9500325AS 500GB       | 3         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 128       | 181    | 35.56%  |
| WDC                 | 105       | 125    | 29.17%  |
| Toshiba             | 63        | 82     | 17.5%   |
| Hitachi             | 32        | 52     | 8.89%   |
| HGST                | 14        | 16     | 3.89%   |
| Fujitsu             | 7         | 8      | 1.94%   |
| Samsung Electronics | 4         | 5      | 1.11%   |
| Unknown             | 3         | 4      | 0.83%   |
| USB3.0              | 1         | 1      | 0.28%   |
| SAGE                | 1         | 1      | 0.28%   |
| HGST HTS            | 1         | 1      | 0.28%   |
| ExcelStor           | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 30        | 35     | 14.35%  |
| Samsung Electronics | 29        | 39     | 13.88%  |
| SanDisk             | 19        | 23     | 9.09%   |
| WDC                 | 9         | 12     | 4.31%   |
| Team                | 8         | 12     | 3.83%   |
| A-DATA Technology   | 8         | 11     | 3.83%   |
| Transcend           | 7         | 7      | 3.35%   |
| SK hynix            | 7         | 19     | 3.35%   |
| Ramsta              | 7         | 8      | 3.35%   |
| Toshiba             | 6         | 9      | 2.87%   |
| Lexar               | 6         | 7      | 2.87%   |
| Micron Technology   | 5         | 5      | 2.39%   |
| Crucial             | 5         | 6      | 2.39%   |
| Intel               | 4         | 5      | 1.91%   |
| Gigabyte Technology | 4         | 4      | 1.91%   |
| China               | 4         | 9      | 1.91%   |
| Apple               | 4         | 4      | 1.91%   |
| PNY                 | 3         | 3      | 1.44%   |
| LITEONIT            | 3         | 5      | 1.44%   |
| KingSpec            | 3         | 3      | 1.44%   |
| HS-SSD-E100         | 3         | 3      | 1.44%   |
| Patriot             | 2         | 2      | 0.96%   |
| Netac               | 2         | 2      | 0.96%   |
| Kingmax             | 2         | 2      | 0.96%   |
| HS-SSD-C100         | 2         | 2      | 0.96%   |
| Hikvision           | 2         | 3      | 0.96%   |
| ZOTAC               | 1         | 1      | 0.48%   |
| WALRAM              | 1         | 1      | 0.48%   |
| Vaseky              | 1         | 2      | 0.48%   |
| Unknown             | 1         | 2      | 0.48%   |
| Teclast             | 1         | 4      | 0.48%   |
| TAMMUZ              | 1         | 1      | 0.48%   |
| SKIHOTAR            | 1         | 1      | 0.48%   |
| ShiJi               | 1         | 1      | 0.48%   |
| Plextor             | 1         | 1      | 0.48%   |
| Phison              | 1         | 1      | 0.48%   |
| OCZ                 | 1         | 1      | 0.48%   |
| Kimtigo             | 1         | 2      | 0.48%   |
| JMicron Technology  | 1         | 1      | 0.48%   |
| Indilinx            | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 312       | 477    | 48.45%  |
| SSD     | 179       | 274    | 27.8%   |
| NVMe    | 108       | 143    | 16.77%  |
| MMC     | 27        | 33     | 4.19%   |
| Unknown | 18        | 24     | 2.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 414       | 732    | 71.5%   |
| NVMe | 108       | 143    | 18.65%  |
| SAS  | 30        | 43     | 5.18%   |
| MMC  | 27        | 33     | 4.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 328       | 520    | 66.94%  |
| 0.51-1.0   | 122       | 176    | 24.9%   |
| 1.01-2.0   | 29        | 39     | 5.92%   |
| 3.01-4.0   | 9         | 14     | 1.84%   |
| 4.01-10.0  | 2         | 2      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 152       | 28.79%  |
| 251-500        | 134       | 25.38%  |
| 501-1000       | 69        | 13.07%  |
| 1001-2000      | 42        | 7.95%   |
| 1-20           | 40        | 7.58%   |
| 51-100         | 34        | 6.44%   |
| 21-50          | 21        | 3.98%   |
| More than 3000 | 13        | 2.46%   |
| Unknown        | 12        | 2.27%   |
| 2001-3000      | 11        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 216       | 38.99%  |
| 21-50          | 110       | 19.86%  |
| 51-100         | 78        | 14.08%  |
| 101-250        | 67        | 12.09%  |
| 251-500        | 31        | 5.6%    |
| 501-1000       | 23        | 4.15%   |
| Unknown        | 12        | 2.17%   |
| 1001-2000      | 9         | 1.62%   |
| 2001-3000      | 6         | 1.08%   |
| More than 3000 | 2         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HDS721050CLA362 500GB                  | 5         | 10     | 9.26%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 5      | 5.56%   |
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 3.7%    |
| Seagate ST2000LM007-1R8174 2TB                 | 2         | 3      | 3.7%    |
| Seagate ST1000LM048-2E7172 1TB                 | 2         | 2      | 3.7%    |
| HGST HTS541010A9E680 1TB                       | 2         | 3      | 3.7%    |
| WDC WD5003ABYZ-011FA0 500GB                    | 1         | 1      | 1.85%   |
| WDC WD5000LPVT-75G33T0 500GB                   | 1         | 1      | 1.85%   |
| WDC WD5000LPVT-22G33T0 500GB                   | 1         | 1      | 1.85%   |
| WDC WD5000LPCX-60VHAT0 500GB                   | 1         | 2      | 1.85%   |
| WDC WD5000AAVS-00ZTB0 500GB                    | 1         | 1      | 1.85%   |
| WDC WD5000AAKX-603CA0 500GB                    | 1         | 1      | 1.85%   |
| WDC WD3200BEVT-22A23T0 320GB                   | 1         | 1      | 1.85%   |
| WDC WD3200AAJS-08L7A0 320GB                    | 1         | 1      | 1.85%   |
| WDC WD1600BEVT-24A23T0 160GB                   | 1         | 1      | 1.85%   |
| WDC WD10JPVX-60JC3T1 1TB                       | 1         | 1      | 1.85%   |
| WDC WD10EZEX-00MFCA0 1TB                       | 1         | 1      | 1.85%   |
| Unknown S050 Hard drive 500GB                  | 1         | 1      | 1.85%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.85%   |
| Toshiba MK6465GSX 640GB                        | 1         | 1      | 1.85%   |
| Toshiba MK3259GSXP 320GB                       | 1         | 1      | 1.85%   |
| Toshiba MK2555GSX 250GB                        | 1         | 1      | 1.85%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 1.85%   |
| Toshiba DT01ACA050 500GB                       | 1         | 1      | 1.85%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD          | 1         | 1      | 1.85%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 1.85%   |
| Seagate ST9120821AS 120GB                      | 1         | 1      | 1.85%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 2      | 1.85%   |
| Seagate ST380815AS 80GB                        | 1         | 1      | 1.85%   |
| Seagate ST3500514NS 500GB                      | 1         | 1      | 1.85%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 1.85%   |
| Seagate ST2000DM008-2FR102 2TB                 | 1         | 1      | 1.85%   |
| SanDisk SDSSDA240G 240GB                       | 1         | 1      | 1.85%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 1.85%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.85%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 1.85%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 2      | 1.85%   |
| Hitachi HTS545050B9SA00 500GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS542525K9SA00 250GB                  | 1         | 1      | 1.85%   |
| Hitachi HDS721050CLA660 500GB                  | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 11        | 12     | 22%     |
| Seagate           | 11        | 13     | 22%     |
| Hitachi           | 9         | 20     | 18%     |
| Toshiba           | 7         | 8      | 14%     |
| HGST              | 3         | 4      | 6%      |
| Unknown           | 1         | 1      | 2%      |
| SK hynix          | 1         | 1      | 2%      |
| SanDisk           | 1         | 1      | 2%      |
| Ramsta            | 1         | 1      | 2%      |
| Micron Technology | 1         | 1      | 2%      |
| Kingston          | 1         | 1      | 2%      |
| Fujitsu           | 1         | 1      | 2%      |
| Colorful          | 1         | 1      | 2%      |
| A-DATA Technology | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 12     | 25.58%  |
| Seagate | 11        | 13     | 25.58%  |
| Hitachi | 9         | 20     | 20.93%  |
| Toshiba | 7         | 8      | 16.28%  |
| HGST    | 3         | 4      | 6.98%   |
| Unknown | 1         | 1      | 2.33%   |
| Fujitsu | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 59     | 84.44%  |
| SSD  | 6         | 6      | 13.33%  |
| NVMe | 1         | 1      | 2.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 330       | 628    | 62.15%  |
| Works    | 156       | 256    | 29.38%  |
| Malfunc  | 44        | 66     | 8.29%   |
| Failed   | 1         | 1      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 332       | 58.25%  |
| AMD                              | 103       | 18.07%  |
| Samsung Electronics              | 25        | 4.39%   |
| SanDisk                          | 15        | 2.63%   |
| Nvidia                           | 15        | 2.63%   |
| SK hynix                         | 11        | 1.93%   |
| Phison Electronics               | 11        | 1.93%   |
| Kingston Technology Company      | 9         | 1.58%   |
| Micron/Crucial Technology        | 7         | 1.23%   |
| Micron Technology                | 6         | 1.05%   |
| Toshiba America Info Systems     | 5         | 0.88%   |
| Silicon Motion                   | 5         | 0.88%   |
| Silicon Integrated Systems [SiS] | 3         | 0.53%   |
| Marvell Technology Group         | 3         | 0.53%   |
| Lite-On Technology               | 3         | 0.53%   |
| ASMedia Technology               | 3         | 0.53%   |
| Union Memory (Shenzhen)          | 2         | 0.35%   |
| Solid State Storage Technology   | 2         | 0.35%   |
| Realtek Semiconductor            | 2         | 0.35%   |
| KIOXIA                           | 2         | 0.35%   |
| ADATA Technology                 | 2         | 0.35%   |
| O2 Micro                         | 1         | 0.18%   |
| Lenovo                           | 1         | 0.18%   |
| JMicron Technology               | 1         | 0.18%   |
| Broadcom / LSI                   | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 70        | 10.39%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 35        | 5.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 28        | 4.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 21        | 3.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19        | 2.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 17        | 2.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 17        | 2.52%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17        | 2.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 15        | 2.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 2.08%   |
| Samsung NVMe SSD Controller 980                                                         | 11        | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10        | 1.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 1.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 1.34%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 9         | 1.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9         | 1.34%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 9         | 1.34%   |
| Nvidia MCP61 SATA Controller                                                            | 8         | 1.19%   |
| Nvidia MCP61 IDE                                                                        | 8         | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 8         | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 8         | 1.19%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8         | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8         | 1.19%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 7         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 7         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.04%   |
| Micron NVMe Storage Controller                                                          | 6         | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 0.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 0.89%   |
| AMD FCH SATA Controller D                                                               | 6         | 0.89%   |
| AMD FCH IDE Controller                                                                  | 6         | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 375       | 63.45%  |
| NVMe | 108       | 18.27%  |
| IDE  | 70        | 11.84%  |
| RAID | 37        | 6.26%   |
| SAS  | 1         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 356       | 72.21%  |
| AMD     | 127       | 25.76%  |
| ARM     | 9         | 1.83%   |
| Unknown | 1         | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz             | 9         | 1.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.42%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.22%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 6         | 1.22%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 1.22%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6         | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.01%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 1.01%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.01%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.81%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.81%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 0.81%   |
| ARM Processor                                 | 4         | 0.81%   |
| AMD Sempron Processor LE-1100                 | 4         | 0.81%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 0.81%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 0.81%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 0.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.61%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.61%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.61%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 3         | 0.61%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 0.61%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.61%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3         | 0.61%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.61%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 3         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 112       | 22.72%  |
| Intel Core i7           | 68        | 13.79%  |
| Intel Core i3           | 44        | 8.92%   |
| Intel Celeron           | 43        | 8.72%   |
| AMD Ryzen 5             | 37        | 7.51%   |
| Other                   | 30        | 6.09%   |
| Intel Core 2 Duo        | 21        | 4.26%   |
| AMD Ryzen 7             | 13        | 2.64%   |
| Intel Pentium           | 12        | 2.43%   |
| Intel Atom              | 12        | 2.43%   |
| AMD Ryzen 3             | 11        | 2.23%   |
| AMD A6                  | 10        | 2.03%   |
| Intel Pentium Dual-Core | 8         | 1.62%   |
| AMD A8                  | 8         | 1.62%   |
| AMD FX                  | 5         | 1.01%   |
| AMD Athlon              | 5         | 1.01%   |
| AMD A10                 | 5         | 1.01%   |
| AMD Sempron             | 4         | 0.81%   |
| AMD A4                  | 4         | 0.81%   |
| Intel Core 2 Quad       | 3         | 0.61%   |
| AMD Ryzen 9             | 3         | 0.61%   |
| AMD Athlon II X2        | 3         | 0.61%   |
| Intel Pentium Silver    | 2         | 0.41%   |
| Intel Pentium Gold      | 2         | 0.41%   |
| Intel Genuine           | 2         | 0.41%   |
| Intel Core 2            | 2         | 0.41%   |
| AMD Turion 64 X2 Mobile | 2         | 0.41%   |
| AMD Ryzen 7 PRO         | 2         | 0.41%   |
| AMD Phenom II X4        | 2         | 0.41%   |
| Intel Xeon              | 1         | 0.2%    |
| Intel Pentium Dual      | 1         | 0.2%    |
| Intel Core m3           | 1         | 0.2%    |
| Intel Core i9           | 1         | 0.2%    |
| Intel Celeron M         | 1         | 0.2%    |
| ARM BCM                 | 1         | 0.2%    |
| ARM Allwinner           | 1         | 0.2%    |
| AMD Ryzen 5 PRO         | 1         | 0.2%    |
| AMD Quad-Core           | 1         | 0.2%    |
| AMD PRO A10             | 1         | 0.2%    |
| AMD Phenom II X2        | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 226       | 45.84%  |
| 4      | 172       | 34.89%  |
| 6      | 46        | 9.33%   |
| 1      | 24        | 4.87%   |
| 8      | 17        | 3.45%   |
| 10     | 3         | 0.61%   |
| 16     | 2         | 0.41%   |
| 14     | 1         | 0.2%    |
| 12     | 1         | 0.2%    |
| 3      | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 491       | 99.59%  |
| 3      | 1         | 0.2%    |
| 2      | 1         | 0.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 319       | 64.71%  |
| 1      | 174       | 35.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 475       | 95.77%  |
| Unknown        | 16        | 3.23%   |
| 32-bit         | 4         | 0.81%   |
| 64-bit         | 1         | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 26.43%  |
| 0x306a9    | 32        | 6.31%   |
| 0x206a7    | 23        | 4.54%   |
| 0x1067a    | 22        | 4.34%   |
| 0x306c3    | 19        | 3.75%   |
| 0x506c9    | 14        | 2.76%   |
| 0x806ea    | 13        | 2.56%   |
| 0x406e3    | 13        | 2.56%   |
| 0x906ea    | 11        | 2.17%   |
| 0x806ec    | 10        | 1.97%   |
| 0x806e9    | 9         | 1.78%   |
| 0x30678    | 9         | 1.78%   |
| 0x40651    | 8         | 1.58%   |
| 0x306d4    | 8         | 1.58%   |
| 0x06003106 | 8         | 1.58%   |
| 0x906e9    | 7         | 1.38%   |
| 0x506e3    | 7         | 1.38%   |
| 0x10676    | 7         | 1.38%   |
| 0x0a50000c | 7         | 1.38%   |
| 0x08701021 | 7         | 1.38%   |
| 0x08108109 | 7         | 1.38%   |
| 0x0800820d | 7         | 1.38%   |
| 0x06001119 | 7         | 1.38%   |
| 0x08600106 | 6         | 1.18%   |
| 0x806c1    | 5         | 0.99%   |
| 0x706e5    | 5         | 0.99%   |
| 0x706a1    | 5         | 0.99%   |
| 0x406c4    | 5         | 0.99%   |
| 0x20655    | 5         | 0.99%   |
| 0x106ca    | 5         | 0.99%   |
| 0xa0671    | 4         | 0.79%   |
| 0xa0652    | 4         | 0.79%   |
| 0x0810100b | 4         | 0.79%   |
| 0x406c3    | 3         | 0.59%   |
| 0x20652    | 3         | 0.59%   |
| 0x07030105 | 3         | 0.59%   |
| 0x0700010f | 3         | 0.59%   |
| 0x0600611a | 3         | 0.59%   |
| 0x906c0    | 2         | 0.39%   |
| 0x906a4    | 2         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 72        | 14.6%   |
| IvyBridge        | 45        | 9.13%   |
| Haswell          | 33        | 6.69%   |
| Penryn           | 32        | 6.49%   |
| SandyBridge      | 27        | 5.48%   |
| Skylake          | 26        | 5.27%   |
| Zen+             | 23        | 4.67%   |
| Zen 2            | 19        | 3.85%   |
| Silvermont       | 18        | 3.65%   |
| Goldmont         | 17        | 3.45%   |
| Unknown          | 17        | 3.45%   |
| Piledriver       | 14        | 2.84%   |
| Zen 3            | 13        | 2.64%   |
| Zen              | 11        | 2.23%   |
| CometLake        | 11        | 2.23%   |
| Broadwell        | 11        | 2.23%   |
| Westmere         | 10        | 2.03%   |
| TigerLake        | 9         | 1.83%   |
| Steamroller      | 9         | 1.83%   |
| Bonnell          | 9         | 1.83%   |
| K8 Hammer        | 8         | 1.62%   |
| IceLake          | 8         | 1.62%   |
| Goldmont plus    | 7         | 1.42%   |
| Excavator        | 7         | 1.42%   |
| K10              | 6         | 1.22%   |
| Alderlake Hybrid | 6         | 1.22%   |
| Core             | 5         | 1.01%   |
| Puma             | 4         | 0.81%   |
| P6               | 3         | 0.61%   |
| Jaguar           | 3         | 0.61%   |
| Bobcat           | 3         | 0.61%   |
| Tremont          | 2         | 0.41%   |
| Nehalem          | 2         | 0.41%   |
| K8 & K10 hybrid  | 1         | 0.2%    |
| K10 Llano        | 1         | 0.2%    |
| Bulldozer        | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 306       | 51.34%  |
| Nvidia                           | 147       | 24.66%  |
| AMD                              | 140       | 23.49%  |
| Silicon Integrated Systems [SiS] | 3         | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 5.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 4.09%   |
| Intel UHD Graphics 620                                                                   | 17        | 2.78%   |
| Intel HD Graphics 500                                                                    | 15        | 2.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.29%   |
| Intel HD Graphics 620                                                                    | 13        | 2.13%   |
| Intel HD Graphics 630                                                                    | 11        | 1.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.47%   |
| Intel HD Graphics 5500                                                                   | 9         | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9         | 1.47%   |
| AMD Renoir                                                                               | 9         | 1.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 1.47%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 1.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.31%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 0.98%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 6         | 0.98%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 6         | 0.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.98%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 0.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 0.98%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.98%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 5         | 0.82%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 5         | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.82%   |
| Intel HD Graphics 530                                                                    | 5         | 0.82%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 5         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 210       | 41.92%  |
| 1 x AMD        | 98        | 19.56%  |
| 1 x Nvidia     | 70        | 13.97%  |
| Intel + Nvidia | 65        | 12.97%  |
| Intel + AMD    | 24        | 4.79%   |
| Other          | 10        | 2%      |
| AMD + Nvidia   | 10        | 2%      |
| 2 x AMD        | 8         | 1.6%    |
| 1 x SiS        | 3         | 0.6%    |
| 2 x Nvidia     | 2         | 0.4%    |
| 2 x Intel      | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 391       | 78.51%  |
| Proprietary | 82        | 16.47%  |
| Unknown     | 25        | 5.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 309       | 60.47%  |
| 1.01-2.0   | 64        | 12.52%  |
| 0.01-0.5   | 47        | 9.2%    |
| 0.51-1.0   | 34        | 6.65%   |
| 3.01-4.0   | 29        | 5.68%   |
| 7.01-8.0   | 10        | 1.96%   |
| 5.01-6.0   | 10        | 1.96%   |
| 8.01-16.0  | 6         | 1.17%   |
| 2.01-3.0   | 2         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 60        | 11.49%  |
| AU Optronics            | 60        | 11.49%  |
| Chimei Innolux          | 56        | 10.73%  |
| BOE                     | 55        | 10.54%  |
| LG Display              | 38        | 7.28%   |
| Dell                    | 32        | 6.13%   |
| AOC                     | 21        | 4.02%   |
| Acer                    | 21        | 4.02%   |
| Lenovo                  | 17        | 3.26%   |
| Goldstar                | 11        | 2.11%   |
| Hewlett-Packard         | 10        | 1.92%   |
| Sony                    | 9         | 1.72%   |
| ASUSTek Computer        | 9         | 1.72%   |
| InfoVision              | 8         | 1.53%   |
| BenQ                    | 8         | 1.53%   |
| Sharp                   | 7         | 1.34%   |
| Philips                 | 6         | 1.15%   |
| Apple                   | 6         | 1.15%   |
| Ancor Communications    | 6         | 1.15%   |
| PANDA                   | 5         | 0.96%   |
| ViewSonic               | 4         | 0.77%   |
| IPS                     | 4         | 0.77%   |
| Chi Mei Optoelectronics | 4         | 0.77%   |
| Unknown                 | 4         | 0.77%   |
| Unknown                 | 3         | 0.57%   |
| Mi                      | 3         | 0.57%   |
| VIE                     | 2         | 0.38%   |
| Unknown (XXX)           | 2         | 0.38%   |
| RTK                     | 2         | 0.38%   |
| Pixio                   | 2         | 0.38%   |
| MStar                   | 2         | 0.38%   |
| MSI                     | 2         | 0.38%   |
| LG Philips              | 2         | 0.38%   |
| InnoLux Display         | 2         | 0.38%   |
| HKC                     | 2         | 0.38%   |
| GDH                     | 2         | 0.38%   |
| eMachines               | 2         | 0.38%   |
| Eizo                    | 2         | 0.38%   |
| CTV                     | 2         | 0.38%   |
| ___                     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 7         | 1.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 6         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 0.94%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 5         | 0.94%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 0.75%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 4         | 0.75%   |
| Dell SE177FP DELF001 1280x1024 338x270mm 17.0-inch                    | 4         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 4         | 0.75%   |
| AOC 2060W AOC2060 1600x900 432x240mm 19.5-inch                        | 4         | 0.75%   |
| Unknown                                                               | 4         | 0.75%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.56%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 3         | 0.56%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x173mm 13.9-inch               | 3         | 0.56%   |
| Lenovo L1951p Wide LEN0990 1440x900 408x255mm 18.9-inch               | 3         | 0.56%   |
| Dell P170S DEL4058 1280x1024 340x270mm 17.1-inch                      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 3         | 0.56%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 3         | 0.56%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.56%   |
| VIE A/G1956 VIE1850 1366x768 414x257mm 19.2-inch                      | 2         | 0.37%   |
| Sony TV SNYAB03 1920x1080                                             | 2         | 0.37%   |
| Sony TV SNYA301 1920x1080                                             | 2         | 0.37%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3549 1366x768 309x174mm 14.0-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch | 2         | 0.37%   |
| RTK 32V3H-H6A RTK4C54 1280x1024 697x392mm 31.5-inch                   | 2         | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.37%   |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                       | 2         | 0.37%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2         | 0.37%   |
| LG Display LP101WSA-TLN1 LGD0295 1024x600 224x126mm 10.1-inch         | 2         | 0.37%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 2         | 0.37%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 2         | 0.37%   |
| IPS IP22V1 IPS2200 1920x1080 409x330mm 20.7-inch                      | 2         | 0.37%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch          | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 196       | 39.92%  |
| 1366x768 (WXGA)    | 170       | 34.62%  |
| 1600x900 (HD+)     | 24        | 4.89%   |
| 1280x1024 (SXGA)   | 23        | 4.68%   |
| 3840x2160 (4K)     | 16        | 3.26%   |
| 1440x900 (WXGA+)   | 9         | 1.83%   |
| 1024x600           | 7         | 1.43%   |
| 1920x1200 (WUXGA)  | 6         | 1.22%   |
| 1360x768           | 6         | 1.22%   |
| 1280x800 (WXGA)    | 6         | 1.22%   |
| 3440x1440          | 4         | 0.81%   |
| 2560x1440 (QHD)    | 4         | 0.81%   |
| 1680x1050 (WSXGA+) | 4         | 0.81%   |
| 2160x1440          | 3         | 0.61%   |
| 1920x540           | 3         | 0.61%   |
| 1024x768 (XGA)     | 2         | 0.41%   |
| 800x1280           | 1         | 0.2%    |
| 3200x1080          | 1         | 0.2%    |
| 2880x1800          | 1         | 0.2%    |
| 2560x1600          | 1         | 0.2%    |
| 2400x1600          | 1         | 0.2%    |
| 2288x1287          | 1         | 0.2%    |
| 1600x1200          | 1         | 0.2%    |
| Unknown            | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 126       | 24%     |
| 13      | 62        | 11.81%  |
| 14      | 48        | 9.14%   |
| 18      | 33        | 6.29%   |
| 23      | 31        | 5.9%    |
| 17      | 31        | 5.9%    |
| 21      | 30        | 5.71%   |
| 27      | 19        | 3.62%   |
| 11      | 19        | 3.62%   |
| 24      | 17        | 3.24%   |
| 20      | 17        | 3.24%   |
| Unknown | 17        | 3.24%   |
| 19      | 14        | 2.67%   |
| 12      | 11        | 2.1%    |
| 72      | 9         | 1.71%   |
| 31      | 8         | 1.52%   |
| 10      | 7         | 1.33%   |
| 32      | 6         | 1.14%   |
| 52      | 4         | 0.76%   |
| 34      | 3         | 0.57%   |
| 22      | 3         | 0.57%   |
| 54      | 2         | 0.38%   |
| 142     | 1         | 0.19%   |
| 58      | 1         | 0.19%   |
| 50      | 1         | 0.19%   |
| 47      | 1         | 0.19%   |
| 40      | 1         | 0.19%   |
| 39      | 1         | 0.19%   |
| 16      | 1         | 0.19%   |
| 7       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 229       | 44.55%  |
| 401-500        | 89        | 17.32%  |
| 501-600        | 62        | 12.06%  |
| 201-300        | 56        | 10.89%  |
| 351-400        | 20        | 3.89%   |
| Unknown        | 17        | 3.31%   |
| 601-700        | 10        | 1.95%   |
| 701-800        | 9         | 1.75%   |
| 1501-2000      | 9         | 1.75%   |
| 1001-1500      | 9         | 1.75%   |
| 801-900        | 2         | 0.39%   |
| More than 2000 | 1         | 0.19%   |
| 1-100          | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 396       | 83.72%  |
| 16/10   | 29        | 6.13%   |
| 5/4     | 20        | 4.23%   |
| Unknown | 16        | 3.38%   |
| 3/2     | 3         | 0.63%   |
| 21/9    | 3         | 0.63%   |
| 6/5     | 2         | 0.42%   |
| 4/3     | 2         | 0.42%   |
| 1.00    | 1         | 0.21%   |
| 0.67    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 123       | 23.84%  |
| 81-90          | 94        | 18.22%  |
| 201-250        | 62        | 12.02%  |
| 141-150        | 48        | 9.3%    |
| 151-200        | 40        | 7.75%   |
| 51-60          | 19        | 3.68%   |
| 301-350        | 19        | 3.68%   |
| More than 1000 | 18        | 3.49%   |
| 351-500        | 17        | 3.29%   |
| Unknown        | 17        | 3.29%   |
| 71-80          | 16        | 3.1%    |
| 121-130        | 13        | 2.52%   |
| 61-70          | 11        | 2.13%   |
| 41-50          | 7         | 1.36%   |
| 251-300        | 3         | 0.58%   |
| 501-1000       | 3         | 0.58%   |
| 91-100         | 3         | 0.58%   |
| 1-40           | 1         | 0.19%   |
| 131-140        | 1         | 0.19%   |
| 111-120        | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 177       | 35.05%  |
| 51-100        | 142       | 28.12%  |
| 121-160       | 130       | 25.74%  |
| 1-50          | 21        | 4.16%   |
| Unknown       | 17        | 3.37%   |
| 161-240       | 14        | 2.77%   |
| More than 240 | 4         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 411       | 81.23%  |
| 2     | 68        | 13.44%  |
| 0     | 24        | 4.74%   |
| 3     | 3         | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 305       | 41.95%  |
| Intel                                 | 179       | 24.62%  |
| Qualcomm Atheros                      | 100       | 13.76%  |
| Broadcom                              | 44        | 6.05%   |
| Ralink Technology                     | 24        | 3.3%    |
| Nvidia                                | 11        | 1.51%   |
| TP-Link                               | 10        | 1.38%   |
| Broadcom Limited                      | 7         | 0.96%   |
| Samsung Electronics                   | 4         | 0.55%   |
| MediaTek                              | 4         | 0.55%   |
| Marvell Technology Group              | 4         | 0.55%   |
| Silicon Integrated Systems [SiS]      | 3         | 0.41%   |
| Qualcomm Atheros Communications       | 3         | 0.41%   |
| JMicron Technology                    | 3         | 0.41%   |
| Huawei Technologies                   | 3         | 0.41%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.41%   |
| Xiaomi                                | 2         | 0.28%   |
| Ralink                                | 2         | 0.28%   |
| Qualcomm                              | 2         | 0.28%   |
| OPPO Electronics                      | 2         | 0.28%   |
| D-Link                                | 2         | 0.28%   |
| Tenda                                 | 1         | 0.14%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.14%   |
| NetGear                               | 1         | 0.14%   |
| ICS Advent                            | 1         | 0.14%   |
| Hewlett-Packard                       | 1         | 0.14%   |
| Encore Electronics                    | 1         | 0.14%   |
| Dell                                  | 1         | 0.14%   |
| D-Link System                         | 1         | 0.14%   |
| BUFFALO                               | 1         | 0.14%   |
| ASIX Electronics                      | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 222       | 26.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 4.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 2.01%   |
| Intel Wireless 7265                                               | 16        | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 15        | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 15        | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 15        | 1.77%   |
| Ralink MT7601U Wireless Adapter                                   | 14        | 1.65%   |
| Intel Wireless 3165                                               | 13        | 1.53%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 9         | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.94%   |
| Realtek 802.11ac NIC                                              | 8         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 0.94%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.71%   |
| Nvidia MCP61 Ethernet                                             | 6         | 0.71%   |
| Intel Wireless 8260                                               | 6         | 0.71%   |
| Intel Wireless 7260                                               | 6         | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.59%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.59%   |
| Intel I211 Gigabit Network Connection                             | 5         | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.59%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 155       | 38.46%  |
| Realtek Semiconductor                 | 80        | 19.85%  |
| Qualcomm Atheros                      | 80        | 19.85%  |
| Broadcom                              | 29        | 7.2%    |
| Ralink Technology                     | 24        | 5.96%   |
| TP-Link                               | 10        | 2.48%   |
| MediaTek                              | 4         | 0.99%   |
| Broadcom Limited                      | 4         | 0.99%   |
| Qualcomm Atheros Communications       | 3         | 0.74%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.74%   |
| Ralink                                | 2         | 0.5%    |
| D-Link                                | 2         | 0.5%    |
| Tenda                                 | 1         | 0.25%   |
| Samsung Electronics                   | 1         | 0.25%   |
| NetGear                               | 1         | 0.25%   |
| Marvell Technology Group              | 1         | 0.25%   |
| Encore Electronics                    | 1         | 0.25%   |
| Dell                                  | 1         | 0.25%   |
| BUFFALO                               | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 4.69%   |
| Intel Wireless 7265                                                     | 16        | 3.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 15        | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 15        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                         | 14        | 3.46%   |
| Intel Wireless 3165                                                     | 13        | 3.21%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 3.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 2.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.98%   |
| Realtek 802.11ac NIC                                                    | 8         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.98%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.73%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.48%   |
| Intel Wireless 8260                                                     | 6         | 1.48%   |
| Intel Wireless 7260                                                     | 6         | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.23%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.23%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.99%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 4         | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.99%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 3         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.74%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.74%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 3         | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 279       | 64.43%  |
| Intel                             | 72        | 16.63%  |
| Qualcomm Atheros                  | 29        | 6.7%    |
| Broadcom                          | 18        | 4.16%   |
| Nvidia                            | 11        | 2.54%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.69%   |
| Marvell Technology Group          | 3         | 0.69%   |
| JMicron Technology                | 3         | 0.69%   |
| Broadcom Limited                  | 3         | 0.69%   |
| Xiaomi                            | 2         | 0.46%   |
| OPPO Electronics                  | 2         | 0.46%   |
| Huawei Technologies               | 2         | 0.46%   |
| Sundance Technology Inc / IC Plus | 1         | 0.23%   |
| Samsung Electronics               | 1         | 0.23%   |
| Qualcomm                          | 1         | 0.23%   |
| ICS Advent                        | 1         | 0.23%   |
| D-Link System                     | 1         | 0.23%   |
| ASIX Electronics                  | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 222       | 50.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 9.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 3.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 2.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 1.37%   |
| Nvidia MCP61 Ethernet                                             | 6         | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.14%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.14%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.92%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.92%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.46%   |
| OPPO RMX3263                                                      | 2         | 0.46%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.46%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.46%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.46%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.46%   |
| Huawei ANA-NX9                                                    | 2         | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.46%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.46%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 416       | 51.81%  |
| WiFi     | 382       | 47.57%  |
| Modem    | 4         | 0.5%    |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 309       | 61.19%  |
| Ethernet | 196       | 38.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 258       | 52.23%  |
| 1     | 212       | 42.91%  |
| 0     | 14        | 2.83%   |
| 3     | 10        | 2.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 457       | 91.4%   |
| Yes  | 43        | 8.6%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 122       | 40.67%  |
| Realtek Semiconductor           | 40        | 13.33%  |
| Qualcomm Atheros Communications | 23        | 7.67%   |
| Lite-On Technology              | 23        | 7.67%   |
| Broadcom                        | 20        | 6.67%   |
| Cambridge Silicon Radio         | 18        | 6%      |
| IMC Networks                    | 17        | 5.67%   |
| Foxconn / Hon Hai               | 16        | 5.33%   |
| Apple                           | 8         | 2.67%   |
| Toshiba                         | 3         | 1%      |
| Hewlett-Packard                 | 3         | 1%      |
| Dell                            | 2         | 0.67%   |
| Chicony Electronics             | 2         | 0.67%   |
| Ralink                          | 1         | 0.33%   |
| Marvell Semiconductor           | 1         | 0.33%   |
| Integrated System Solution      | 1         | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 45        | 15%     |
| Realtek Bluetooth Radio                             | 25        | 8.33%   |
| Intel AX201 Bluetooth                               | 21        | 7%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 6%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 6%      |
| Intel AX200 Bluetooth                               | 13        | 4.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 3.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 3.33%   |
| IMC Networks Bluetooth Device                       | 8         | 2.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 2.33%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2%      |
| Lite-On Bluetooth Device                            | 6         | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 2%      |
| Realtek RTL8821A Bluetooth                          | 4         | 1.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.33%   |
| Intel AX210 Bluetooth                               | 4         | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.33%   |
| Realtek RTL8723B Bluetooth                          | 3         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 1%      |
| Apple Bluetooth Host Controller                     | 3         | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.67%   |
| Lite-On Wireless_Device                             | 2         | 0.67%   |
| Lite-On BCM43142A0                                  | 2         | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.67%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.67%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.67%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 0.67%   |
| Broadcom HP Portable Valentine                      | 2         | 0.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.67%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.67%   |
| Broadcom BCM2035 Bluetooth                          | 2         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 344       | 53.92%  |
| AMD                              | 132       | 20.69%  |
| Nvidia                           | 103       | 16.14%  |
| C-Media Electronics              | 8         | 1.25%   |
| Generalplus Technology           | 6         | 0.94%   |
| Logitech                         | 4         | 0.63%   |
| SteelSeries ApS                  | 3         | 0.47%   |
| Silicon Integrated Systems [SiS] | 3         | 0.47%   |
| Plantronics                      | 3         | 0.47%   |
| Kingston Technology              | 3         | 0.47%   |
| DCMT Technology                  | 3         | 0.47%   |
| Realtek Semiconductor            | 2         | 0.31%   |
| Razer USA                        | 2         | 0.31%   |
| JMTek                            | 2         | 0.31%   |
| GN Netcom                        | 2         | 0.31%   |
| Giga-Byte Technology             | 2         | 0.31%   |
| ZOOM                             | 1         | 0.16%   |
| XMOS                             | 1         | 0.16%   |
| USB MICROPHONE                   | 1         | 0.16%   |
| OPPO Electronics                 | 1         | 0.16%   |
| Micronas                         | 1         | 0.16%   |
| Hewlett-Packard                  | 1         | 0.16%   |
| Focusrite-Novation               | 1         | 0.16%   |
| FiiO Electronics Technology      | 1         | 0.16%   |
| FIFINE 683 Microphone            | 1         | 0.16%   |
| Elgato Systems                   | 1         | 0.16%   |
| Creative Technology              | 1         | 0.16%   |
| Corsair                          | 1         | 0.16%   |
| Cooler Master                    | 1         | 0.16%   |
| ASUSTek Computer                 | 1         | 0.16%   |
| Arturia                          | 1         | 0.16%   |
| AKAI Professional M.I.           | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 46        | 6.01%   |
| AMD Family 17h/19h HD Audio Controller                                     | 46        | 6.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 33        | 4.31%   |
| AMD FCH Azalia Controller                                                  | 31        | 4.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 27        | 3.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20        | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19        | 2.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 2.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 17        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 2.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 13        | 1.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 1.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 1.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 1.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 1.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 1.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 1.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 1.18%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.05%   |
| Nvidia MCP61 High Definition Audio                                         | 8         | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.05%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 8         | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 0.92%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 0.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 7         | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 6         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 18.89%  |
| Kingston            | 51        | 18.89%  |
| SK hynix            | 49        | 18.15%  |
| Unknown             | 21        | 7.78%   |
| Micron Technology   | 21        | 7.78%   |
| Team                | 13        | 4.81%   |
| Ramaxel Technology  | 9         | 3.33%   |
| G.Skill             | 8         | 2.96%   |
| Crucial             | 7         | 2.59%   |
| Corsair             | 6         | 2.22%   |
| Unknown (ABCD)      | 4         | 1.48%   |
| Elpida              | 4         | 1.48%   |
| Transcend           | 3         | 1.11%   |
| Nanya Technology    | 3         | 1.11%   |
| Unknown             | 3         | 1.11%   |
| PNY                 | 2         | 0.74%   |
| Patriot             | 2         | 0.74%   |
| Kingmax             | 2         | 0.74%   |
| A-DATA Technology   | 2         | 0.74%   |
| Uroad               | 1         | 0.37%   |
| Unknown (8A5D)      | 1         | 0.37%   |
| Unifosa             | 1         | 0.37%   |
| Silicon Power       | 1         | 0.37%   |
| Mitsubishi          | 1         | 0.37%   |
| Carry               | 1         | 0.37%   |
| Avant               | 1         | 0.37%   |
| ASint Technology    | 1         | 0.37%   |
| Apacer              | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 2.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.4%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.4%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.4%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 4         | 1.4%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 1.4%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 3         | 1.05%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.05%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.05%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.05%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 3         | 1.05%   |
| Unknown                                                          | 3         | 1.05%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.7%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 2         | 0.7%    |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 2         | 0.7%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.7%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.7%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.7%    |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                  | 2         | 0.7%    |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4267MT/s               | 2         | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.7%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 2         | 0.7%    |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s               | 2         | 0.7%    |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.7%    |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 113       | 50.9%   |
| DDR3    | 78        | 35.14%  |
| DDR2    | 11        | 4.95%   |
| LPDDR4  | 9         | 4.05%   |
| Unknown | 4         | 1.8%    |
| SDRAM   | 2         | 0.9%    |
| LPDDR5  | 1         | 0.45%   |
| LPDDR3  | 1         | 0.45%   |
| DRAM    | 1         | 0.45%   |
| DDR5    | 1         | 0.45%   |
| DDR     | 1         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 64.25%  |
| DIMM         | 68        | 30.77%  |
| Row Of Chips | 11        | 4.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 102       | 40.8%   |
| 4096  | 80        | 32%     |
| 2048  | 26        | 10.4%   |
| 16384 | 18        | 7.2%    |
| 32768 | 12        | 4.8%    |
| 1024  | 12        | 4.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 54        | 22.04%  |
| 2667    | 43        | 17.55%  |
| 3200    | 35        | 14.29%  |
| 2400    | 23        | 9.39%   |
| 2133    | 13        | 5.31%   |
| 667     | 10        | 4.08%   |
| 1334    | 9         | 3.67%   |
| 1333    | 9         | 3.67%   |
| 3600    | 6         | 2.45%   |
| 3733    | 4         | 1.63%   |
| Unknown | 4         | 1.63%   |
| 3866    | 3         | 1.22%   |
| 3800    | 3         | 1.22%   |
| 8400    | 2         | 0.82%   |
| 4267    | 2         | 0.82%   |
| 3266    | 2         | 0.82%   |
| 2666    | 2         | 0.82%   |
| 1867    | 2         | 0.82%   |
| 1800    | 2         | 0.82%   |
| 1067    | 2         | 0.82%   |
| 1066    | 2         | 0.82%   |
| 800     | 2         | 0.82%   |
| 6400    | 1         | 0.41%   |
| 4800    | 1         | 0.41%   |
| 4266    | 1         | 0.41%   |
| 3500    | 1         | 0.41%   |
| 3466    | 1         | 0.41%   |
| 2048    | 1         | 0.41%   |
| 1866    | 1         | 0.41%   |
| 1777    | 1         | 0.41%   |
| 1648    | 1         | 0.41%   |
| 533     | 1         | 0.41%   |
| 400     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 4         | 40%     |
| Brother Industries | 3         | 30%     |
| Canon              | 2         | 20%     |
| Unknown            | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L120 Series   | 2         | 20%     |
| Seiko Epson L3110 Series  | 1         | 10%     |
| Seiko Epson L220 Series   | 1         | 10%     |
| Canon PIXMA MG2500 Series | 1         | 10%     |
| Canon G2010 series        | 1         | 10%     |
| Brother DCP-T710W         | 1         | 10%     |
| Brother DCP-T700W         | 1         | 10%     |
| Brother DCP-T310          | 1         | 10%     |
| Unknown                   | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 74        | 23.27%  |
| Realtek Semiconductor                  | 29        | 9.12%   |
| Microdia                               | 25        | 7.86%   |
| IMC Networks                           | 22        | 6.92%   |
| Quanta                                 | 21        | 6.6%    |
| Acer                                   | 15        | 4.72%   |
| Sunplus Innovation Technology          | 12        | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 3.77%   |
| Lite-On Technology                     | 9         | 2.83%   |
| Apple                                  | 9         | 2.83%   |
| Syntek                                 | 7         | 2.2%    |
| Suyin                                  | 7         | 2.2%    |
| Logitech                               | 7         | 2.2%    |
| Silicon Motion                         | 6         | 1.89%   |
| Z-Star Microelectronics                | 5         | 1.57%   |
| Luxvisions Innotech Limited            | 5         | 1.57%   |
| Alcor Micro                            | 5         | 1.57%   |
| Samsung Electronics                    | 4         | 1.26%   |
| Jieli Technology                       | 4         | 1.26%   |
| A4Tech                                 | 4         | 1.26%   |
| Pixart Imaging                         | 3         | 0.94%   |
| Cubeternet                             | 3         | 0.94%   |
| Bison Electronics                      | 3         | 0.94%   |
| ALi                                    | 3         | 0.94%   |
| USB Camera                             | 2         | 0.63%   |
| Razer USA                              | 2         | 0.63%   |
| OPPO Electronics                       | 2         | 0.63%   |
| Importek                               | 2         | 0.63%   |
| Generalplus Technology                 | 2         | 0.63%   |
| Alpha Imaging Technology               | 2         | 0.63%   |
| Y Media                                | 1         | 0.31%   |
| vivo                                   | 1         | 0.31%   |
| SunplusIT                              | 1         | 0.31%   |
| Ricoh                                  | 1         | 0.31%   |
| OmniVision Technologies                | 1         | 0.31%   |
| Microsoft                              | 1         | 0.31%   |
| Lenovo                                 | 1         | 0.31%   |
| KYE Systems (Mouse Systems)            | 1         | 0.31%   |
| Goertek Electronics                    | 1         | 0.31%   |
| GEMBIRD                                | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 18        | 5.63%   |
| Chicony HD WebCam                                               | 15        | 4.69%   |
| Quanta VGA WebCam                                               | 9         | 2.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 8         | 2.5%    |
| Realtek Acer 640 x 480 laptop camera                            | 7         | 2.19%   |
| Microdia Integrated_Webcam_HD                                   | 7         | 2.19%   |
| Realtek Integrated_Webcam_HD                                    | 6         | 1.88%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 1.56%   |
| Chicony VGA Webcam                                              | 5         | 1.56%   |
| Jieli USB PHY 2.0                                               | 4         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 1.25%   |
| Acer Integrated Camera                                          | 4         | 1.25%   |
| Z-Star Venus USB2.0 Camera                                      | 3         | 0.94%   |
| Syntek Integrated Camera                                        | 3         | 0.94%   |
| Samsung Galaxy A5 (MTP)                                         | 3         | 0.94%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 3         | 0.94%   |
| Realtek Integrated Webcam                                       | 3         | 0.94%   |
| Quanta HD User Facing                                           | 3         | 0.94%   |
| Quanta ACER HD User Facing                                      | 3         | 0.94%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                            | 3         | 0.94%   |
| Microdia Sonix USB 2.0 Camera                                   | 3         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 3         | 0.94%   |
| Microdia Integrated Camera                                      | 3         | 0.94%   |
| Logitech Webcam C270                                            | 3         | 0.94%   |
| Lite-On Integrated Camera                                       | 3         | 0.94%   |
| IMC Networks Integrated Camera                                  | 3         | 0.94%   |
| Chicony Lenovo EasyCamera                                       | 3         | 0.94%   |
| Chicony HP Wide Vision HD Camera                                | 3         | 0.94%   |
| Chicony HP Truevision HD                                        | 3         | 0.94%   |
| Chicony EasyCamera                                              | 3         | 0.94%   |
| Apple Built-in iSight                                           | 3         | 0.94%   |
| ALi WebCam                                                      | 3         | 0.94%   |
| Acer Lenovo EasyCamera                                          | 3         | 0.94%   |
| Acer EasyCamera                                                 | 3         | 0.94%   |
| A4Tech FHD 1080P PC Camera                                      | 3         | 0.94%   |
| USB Camera USB Camera                                           | 2         | 0.63%   |
| Syntek Lenovo EasyCamera                                        | 2         | 0.63%   |
| Syntek EasyCamera                                               | 2         | 0.63%   |
| Suyin HP Webcam                                                 | 2         | 0.63%   |
| Sunplus Laptop Integrated WebCam HD                             | 2         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 29.73%  |
| Shenzhen Goodix Technology | 9         | 24.32%  |
| Synaptics                  | 7         | 18.92%  |
| LighTuning Technology      | 4         | 10.81%  |
| Upek                       | 3         | 8.11%   |
| AuthenTec                  | 2         | 5.41%   |
| Elan Microelectronics      | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 6         | 16.22%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 8.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 3         | 8.11%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 5.41%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 5.41%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 5.41%   |
| Synaptics  WBDI                                            | 2         | 5.41%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 5.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.7%    |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 2.7%    |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 2.7%    |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 2.7%    |
| Validity Sensors Synaptics WBDI                            | 1         | 2.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 2.7%    |
| Shenzhen Goodix FingerPrint                                | 1         | 2.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 2.7%    |
| Elan ELAN:Fingerprint                                      | 1         | 2.7%    |
| AuthenTec Fingerprint Sensor                               | 1         | 2.7%    |
| AuthenTec AES1600                                          | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 5         | 41.67%  |
| Upek             | 3         | 25%     |
| O2 Micro         | 2         | 16.67%  |
| SCM Microsystems | 1         | 8.33%   |
| Alcor Micro      | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 25%     |
| Broadcom 5880                                                                | 2         | 16.67%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 8.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 385       | 75.79%  |
| 1     | 103       | 20.28%  |
| 2     | 19        | 3.74%   |
| 3     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 38        | 27.34%  |
| Fingerprint reader       | 36        | 25.9%   |
| Net/wireless             | 24        | 17.27%  |
| Chipcard                 | 12        | 8.63%   |
| Camera                   | 7         | 5.04%   |
| Multimedia controller    | 6         | 4.32%   |
| Net/ethernet             | 4         | 2.88%   |
| Communication controller | 3         | 2.16%   |
| Sound                    | 2         | 1.44%   |
| Wireless                 | 1         | 0.72%   |
| Unassigned class         | 1         | 0.72%   |
| Storage/raid             | 1         | 0.72%   |
| Storage                  | 1         | 0.72%   |
| Network                  | 1         | 0.72%   |
| Modem                    | 1         | 0.72%   |
| Bluetooth                | 1         | 0.72%   |


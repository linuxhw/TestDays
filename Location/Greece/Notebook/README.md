Linux in Greece - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Greece.

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

Total: 924

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3537               | [78f270b35a](https://linux-hardware.org/?probe=78f270b35a) | Feb 27, 2023 |
| Dell          | Inspiron 3537               | [bb1ffc3498](https://linux-hardware.org/?probe=bb1ffc3498) | Feb 27, 2023 |
| Lenovo        | ThinkPad P70 20ESS2J700     | [5a94dfa289](https://linux-hardware.org/?probe=5a94dfa289) | Feb 23, 2023 |
| Lenovo        | ThinkPad P70 20ESS2J700     | [869614f52a](https://linux-hardware.org/?probe=869614f52a) | Feb 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [becb5b0ba1](https://linux-hardware.org/?probe=becb5b0ba1) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| HP            | Pavilion Notebook           | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Dell          | Inspiron 5559               | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4c191fe9c2](https://linux-hardware.org/?probe=4c191fe9c2) | Feb 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [70643a8be9](https://linux-hardware.org/?probe=70643a8be9) | Feb 11, 2023 |
| IBM           | ThinkPad T43 18714AG        | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c222b31f37](https://linux-hardware.org/?probe=c222b31f37) | Feb 05, 2023 |
| HP            | 255 G7 Notebook PC          | [cbec062cd5](https://linux-hardware.org/?probe=cbec062cd5) | Feb 04, 2023 |
| Dell          | Inspiron 15 5510            | [4af8568b93](https://linux-hardware.org/?probe=4af8568b93) | Feb 03, 2023 |
| MSI           | Modern 14 B11MOU            | [542173e9a2](https://linux-hardware.org/?probe=542173e9a2) | Feb 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [7bc88d72f0](https://linux-hardware.org/?probe=7bc88d72f0) | Jan 29, 2023 |
| Dell          | Inspiron 3501               | [7bb7fe1a4f](https://linux-hardware.org/?probe=7bb7fe1a4f) | Jan 29, 2023 |
| Dell          | Inspiron 3501               | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Timi          | TM1703                      | [6bb85263a7](https://linux-hardware.org/?probe=6bb85263a7) | Jan 29, 2023 |
| Acer          | Aspire 5738                 | [2aa7e026c4](https://linux-hardware.org/?probe=2aa7e026c4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [25ea296433](https://linux-hardware.org/?probe=25ea296433) | Jan 28, 2023 |
| Dell          | Inspiron 15 5510            | [babedb5bbc](https://linux-hardware.org/?probe=babedb5bbc) | Jan 26, 2023 |
| HP            | EliteBook 2560p             | [d5eae98224](https://linux-hardware.org/?probe=d5eae98224) | Jan 25, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [dcc2324c10](https://linux-hardware.org/?probe=dcc2324c10) | Jan 22, 2023 |
| Dell          | Latitude E5430 non-vPro     | [4ff88ad220](https://linux-hardware.org/?probe=4ff88ad220) | Jan 22, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| Valve         | Jupiter                     | [c87d98cab1](https://linux-hardware.org/?probe=c87d98cab1) | Jan 21, 2023 |
| Sony          | VPCF13Z1E                   | [3eaeffde09](https://linux-hardware.org/?probe=3eaeffde09) | Jan 21, 2023 |
| Acer          | Aspire A517-51G             | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| Sony          | VPCF13Z1E                   | [aa93abde02](https://linux-hardware.org/?probe=aa93abde02) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [fb0b3500da](https://linux-hardware.org/?probe=fb0b3500da) | Jan 15, 2023 |
| Lenovo        | G50-80 80L0                 | [08a00eef73](https://linux-hardware.org/?probe=08a00eef73) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [0536f685a0](https://linux-hardware.org/?probe=0536f685a0) | Jan 13, 2023 |
| Lenovo        | G50-70 20351                | [239e9a9620](https://linux-hardware.org/?probe=239e9a9620) | Jan 12, 2023 |
| HP            | 255 G7 Notebook PC          | [b1a7adefab](https://linux-hardware.org/?probe=b1a7adefab) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [45e96fb346](https://linux-hardware.org/?probe=45e96fb346) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [90dea18a86](https://linux-hardware.org/?probe=90dea18a86) | Jan 07, 2023 |
| Lenovo        | 3000 G530 444622G           | [7f1a67e904](https://linux-hardware.org/?probe=7f1a67e904) | Jan 07, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [d069cbd46b](https://linux-hardware.org/?probe=d069cbd46b) | Jan 06, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a2ec6616aa](https://linux-hardware.org/?probe=a2ec6616aa) | Jan 05, 2023 |
| MSI           | Modern 14 B11MOU            | [036ae164e8](https://linux-hardware.org/?probe=036ae164e8) | Jan 04, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [40af3a30ca](https://linux-hardware.org/?probe=40af3a30ca) | Jan 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [66538edc62](https://linux-hardware.org/?probe=66538edc62) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Sony          | VPCEL3S1E                   | [b57b0db39c](https://linux-hardware.org/?probe=b57b0db39c) | Jan 01, 2023 |
| Lenovo        | G40-30 80FY                 | [49bb82ca4b](https://linux-hardware.org/?probe=49bb82ca4b) | Dec 29, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [250104c525](https://linux-hardware.org/?probe=250104c525) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [7f33845279](https://linux-hardware.org/?probe=7f33845279) | Dec 28, 2022 |
| Acer          | Aspire E1-571               | [82b72a9059](https://linux-hardware.org/?probe=82b72a9059) | Dec 27, 2022 |
| Lenovo        | G50-30 80G0                 | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | Compaq Presario CQ61        | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Lenovo        | G510 20238                  | [b5fcbb8663](https://linux-hardware.org/?probe=b5fcbb8663) | Dec 22, 2022 |
| Lenovo        | G510 20238                  | [2489f01426](https://linux-hardware.org/?probe=2489f01426) | Dec 22, 2022 |
| Dell          | Vostro 3500                 | [a50ec1e677](https://linux-hardware.org/?probe=a50ec1e677) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| HP            | Unknown                     | [84f5cfd0cf](https://linux-hardware.org/?probe=84f5cfd0cf) | Dec 20, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | [76771fa0aa](https://linux-hardware.org/?probe=76771fa0aa) | Dec 19, 2022 |
| Acer          | AOA110                      | [560aa745c1](https://linux-hardware.org/?probe=560aa745c1) | Dec 14, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [a48e9c810c](https://linux-hardware.org/?probe=a48e9c810c) | Dec 14, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | [2499d7057e](https://linux-hardware.org/?probe=2499d7057e) | Dec 14, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| Acer          | Aspire A515-44G             | [b85a211b25](https://linux-hardware.org/?probe=b85a211b25) | Dec 11, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | [799470f1aa](https://linux-hardware.org/?probe=799470f1aa) | Dec 05, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [8d5c8e8f4d](https://linux-hardware.org/?probe=8d5c8e8f4d) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b475911aaf](https://linux-hardware.org/?probe=b475911aaf) | Dec 03, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| HP            | Pavilion g6                 | [fefac15f4c](https://linux-hardware.org/?probe=fefac15f4c) | Nov 29, 2022 |
| Clevo         | W55xEU                      | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| Acer          | Aspire A315-58              | [df3e0f4b6c](https://linux-hardware.org/?probe=df3e0f4b6c) | Nov 26, 2022 |
| Acer          | Aspire A315-58              | [82ee1f1740](https://linux-hardware.org/?probe=82ee1f1740) | Nov 26, 2022 |
| MSI           | GE62 2QC                    | [6bdf66b3b6](https://linux-hardware.org/?probe=6bdf66b3b6) | Nov 26, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| Dell          | Inspiron 3585               | [33485dee6d](https://linux-hardware.org/?probe=33485dee6d) | Nov 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS01H00    | [3714ee0985](https://linux-hardware.org/?probe=3714ee0985) | Nov 24, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [f442c854fc](https://linux-hardware.org/?probe=f442c854fc) | Nov 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a7f0189359](https://linux-hardware.org/?probe=a7f0189359) | Nov 23, 2022 |
| Dell          | Latitude D530               | [1403a8c938](https://linux-hardware.org/?probe=1403a8c938) | Nov 23, 2022 |
| HP            | Pavilion dv5                | [2a497ff54f](https://linux-hardware.org/?probe=2a497ff54f) | Nov 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | [f7ebd3f633](https://linux-hardware.org/?probe=f7ebd3f633) | Nov 20, 2022 |
| Purism        | Librem 14                   | [cbc8bf9c96](https://linux-hardware.org/?probe=cbc8bf9c96) | Nov 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [814b5d3d2e](https://linux-hardware.org/?probe=814b5d3d2e) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [49ac6f08f9](https://linux-hardware.org/?probe=49ac6f08f9) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [0007401910](https://linux-hardware.org/?probe=0007401910) | Nov 15, 2022 |
| Acer          | Aspire A315-58              | [961b736faa](https://linux-hardware.org/?probe=961b736faa) | Nov 13, 2022 |
| Sony          | VGN-CR31S_P                 | [ce99a279ca](https://linux-hardware.org/?probe=ce99a279ca) | Nov 11, 2022 |
| Lenovo        | ThinkPad T580 20LAS01H00    | [4d41c7236e](https://linux-hardware.org/?probe=4d41c7236e) | Nov 10, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [1cee1a7bd4](https://linux-hardware.org/?probe=1cee1a7bd4) | Nov 09, 2022 |
| MSI           | GE62 2QC                    | [513a929878](https://linux-hardware.org/?probe=513a929878) | Nov 08, 2022 |
| MSI           | GF65 Thin 10UE              | [ec09d9e22e](https://linux-hardware.org/?probe=ec09d9e22e) | Nov 06, 2022 |
| Insyde        | CherryTrail                 | [72fdd6a414](https://linux-hardware.org/?probe=72fdd6a414) | Nov 06, 2022 |
| Insyde        | CherryTrail                 | [1a65afa04d](https://linux-hardware.org/?probe=1a65afa04d) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [8b50396928](https://linux-hardware.org/?probe=8b50396928) | Nov 04, 2022 |
| HP            | Laptop 15-db0xxx            | [aad6abb936](https://linux-hardware.org/?probe=aad6abb936) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| Acer          | Aspire A315-58              | [7870d9b047](https://linux-hardware.org/?probe=7870d9b047) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK AH530              | [a3f55b1301](https://linux-hardware.org/?probe=a3f55b1301) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK AH530              | [285a7d17e3](https://linux-hardware.org/?probe=285a7d17e3) | Oct 27, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [c9393d50b5](https://linux-hardware.org/?probe=c9393d50b5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [5199be5418](https://linux-hardware.org/?probe=5199be5418) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| Toshiba       | dynabook Satellite T87/8... | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [ade038c388](https://linux-hardware.org/?probe=ade038c388) | Oct 24, 2022 |
| Toshiba       | Satellite C50-B             | [a9041efc75](https://linux-hardware.org/?probe=a9041efc75) | Oct 23, 2022 |
| Acer          | Aspire A315-58              | [e5b07599e3](https://linux-hardware.org/?probe=e5b07599e3) | Oct 22, 2022 |
| HP            | EliteBook 820 G1            | [7abef2546e](https://linux-hardware.org/?probe=7abef2546e) | Oct 21, 2022 |
| Apple         | MacBookPro8,1               | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [de5adb6775](https://linux-hardware.org/?probe=de5adb6775) | Oct 21, 2022 |
| HP            | Pavilion g7                 | [19048aa8f0](https://linux-hardware.org/?probe=19048aa8f0) | Oct 19, 2022 |
| Acer          | Aspire V3-771               | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| HP            | Pavilion g6                 | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [a281cc47e5](https://linux-hardware.org/?probe=a281cc47e5) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Dell          | Precision M6800             | [802d1dbfcd](https://linux-hardware.org/?probe=802d1dbfcd) | Oct 06, 2022 |
| Apple         | MacBookPro5,2               | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Dell          | XPS 13 9370                 | [4e0be93d26](https://linux-hardware.org/?probe=4e0be93d26) | Sep 29, 2022 |
| Purism        | Librem 14                   | [213731b934](https://linux-hardware.org/?probe=213731b934) | Sep 24, 2022 |
| HP            | Notebook                    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | ThinkPad X230 23252QG       | [4146ff55f9](https://linux-hardware.org/?probe=4146ff55f9) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | [906f27f221](https://linux-hardware.org/?probe=906f27f221) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | [d229fa96f3](https://linux-hardware.org/?probe=d229fa96f3) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| HP            | EliteBook 8470p             | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| HP            | 620                         | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [4aa935356c](https://linux-hardware.org/?probe=4aa935356c) | Sep 02, 2022 |
| Toshiba       | Satellite C850D-118         | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Dell          | G15 5515                    | [708ef41c02](https://linux-hardware.org/?probe=708ef41c02) | Aug 29, 2022 |
| Plaisio       | Turbo X                     | [ae92ead1ca](https://linux-hardware.org/?probe=ae92ead1ca) | Aug 29, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Sony          | VPCEB1S1E                   | [45dbb67d02](https://linux-hardware.org/?probe=45dbb67d02) | Aug 18, 2022 |
| Dell          | G15 5515                    | [3a7c8ea452](https://linux-hardware.org/?probe=3a7c8ea452) | Aug 17, 2022 |
| ASUSTek       | UX310UQ                     | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| Lenovo        | V3000 80KV                  | [32c1aa64cf](https://linux-hardware.org/?probe=32c1aa64cf) | Aug 09, 2022 |
| HP            | Laptop 15-db1xxx            | [9e849a1708](https://linux-hardware.org/?probe=9e849a1708) | Aug 07, 2022 |
| Toshiba       | NB100                       | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| HP            | Compaq 6730s                | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| HP            | 255 G8 Notebook PC          | [e271ff9bf8](https://linux-hardware.org/?probe=e271ff9bf8) | Jul 29, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [398fb75cec](https://linux-hardware.org/?probe=398fb75cec) | Jul 29, 2022 |
| HP            | 255 G8 Notebook PC          | [ceb1b7da41](https://linux-hardware.org/?probe=ceb1b7da41) | Jul 28, 2022 |
| Apple         | MacBookPro8,1               | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| HP            | Pavilion g6                 | [a57cf84361](https://linux-hardware.org/?probe=a57cf84361) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| Dynabook      | Satellite Pro C50D-B        | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| Dell          | Latitude 5420               | [eecbd6aeec](https://linux-hardware.org/?probe=eecbd6aeec) | Jul 22, 2022 |
| HP            | 255 G8 Notebook PC          | [59e9017400](https://linux-hardware.org/?probe=59e9017400) | Jul 19, 2022 |
| Dell          | Inspiron 15 3511            | [257823caa8](https://linux-hardware.org/?probe=257823caa8) | Jul 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [0f1dd0317a](https://linux-hardware.org/?probe=0f1dd0317a) | Jul 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [3884be1bc0](https://linux-hardware.org/?probe=3884be1bc0) | Jul 15, 2022 |
| Acer          | Extensa 215-32              | [bd34d99acc](https://linux-hardware.org/?probe=bd34d99acc) | Jul 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e992a45818](https://linux-hardware.org/?probe=e992a45818) | Jul 15, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [95b0d6d487](https://linux-hardware.org/?probe=95b0d6d487) | Jul 14, 2022 |
| Toshiba       | Satellite L550              | [cb3f0e6381](https://linux-hardware.org/?probe=cb3f0e6381) | Jul 13, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [f52d09ef30](https://linux-hardware.org/?probe=f52d09ef30) | Jul 07, 2022 |
| HP            | Compaq CQ58                 | [d46da7be57](https://linux-hardware.org/?probe=d46da7be57) | Jul 05, 2022 |
| Unknown       | Unknown                     | [df0722af87](https://linux-hardware.org/?probe=df0722af87) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| Toshiba       | Satellite A200              | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| HP            | Laptop 17-ca1xxx            | [10620fe30b](https://linux-hardware.org/?probe=10620fe30b) | Jun 29, 2022 |
| Valve         | Jupiter                     | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [bb4f0d2bce](https://linux-hardware.org/?probe=bb4f0d2bce) | Jun 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a2a6f48fe2](https://linux-hardware.org/?probe=a2a6f48fe2) | Jun 22, 2022 |
| ASUSTek       | X550JX                      | [999d6e4735](https://linux-hardware.org/?probe=999d6e4735) | Jun 20, 2022 |
| HP            | EliteBook 840 G4            | [d42c64a985](https://linux-hardware.org/?probe=d42c64a985) | Jun 18, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [ee0b4c4389](https://linux-hardware.org/?probe=ee0b4c4389) | Jun 14, 2022 |
| Dell          | XPS 13 9380                 | [af2362a1e4](https://linux-hardware.org/?probe=af2362a1e4) | Jun 12, 2022 |
| HP            | ProBook 4530s               | [8162a82eba](https://linux-hardware.org/?probe=8162a82eba) | Jun 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [039d0b1cdc](https://linux-hardware.org/?probe=039d0b1cdc) | Jun 07, 2022 |
| Dell          | Precision M4800             | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Dell          | Inspiron 5567               | [3ede7ad313](https://linux-hardware.org/?probe=3ede7ad313) | Jun 02, 2022 |
| Dell          | Inspiron 5567               | [e8e9948f71](https://linux-hardware.org/?probe=e8e9948f71) | Jun 02, 2022 |
| HP            | Unknown                     | [521124e0e2](https://linux-hardware.org/?probe=521124e0e2) | May 28, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Latitude 5420               | [28c0f1ba96](https://linux-hardware.org/?probe=28c0f1ba96) | May 24, 2022 |
| ASUSTek       | X505BA                      | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| Pegatron      | A15                         | [335d6a014c](https://linux-hardware.org/?probe=335d6a014c) | May 18, 2022 |
| HP            | Mini 110-1100               | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| HP            | ProBook 645 G1              | [771f25ecc9](https://linux-hardware.org/?probe=771f25ecc9) | May 14, 2022 |
| HP            | EliteBook 8470p             | [2c8d1eec1e](https://linux-hardware.org/?probe=2c8d1eec1e) | May 13, 2022 |
| HP            | EliteBook 8470p             | [074043a5ca](https://linux-hardware.org/?probe=074043a5ca) | May 13, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ec5dbcb034](https://linux-hardware.org/?probe=ec5dbcb034) | May 02, 2022 |
| Dell          | Latitude E6500              | [bbd302d9ba](https://linux-hardware.org/?probe=bbd302d9ba) | May 02, 2022 |
| Dell          | Latitude E6500              | [8eb92ca472](https://linux-hardware.org/?probe=8eb92ca472) | May 02, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Dell          | Inspiron 5567               | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| Dell          | Inspiron 5559               | [e9676d63f9](https://linux-hardware.org/?probe=e9676d63f9) | Apr 24, 2022 |
| HP            | Notebook                    | [4772a69956](https://linux-hardware.org/?probe=4772a69956) | Apr 23, 2022 |
| HP            | Notebook                    | [e6099e9fd5](https://linux-hardware.org/?probe=e6099e9fd5) | Apr 22, 2022 |
| HP            | Pavilion g7                 | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| HP            | Pavilion g7                 | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Dell          | XPS 15 7590                 | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Alienware     | M11x                        | [df72ecbe58](https://linux-hardware.org/?probe=df72ecbe58) | Apr 18, 2022 |
| Acer          | Aspire A315-51              | [a6ae41a1c9](https://linux-hardware.org/?probe=a6ae41a1c9) | Apr 18, 2022 |
| Toshiba       | Satellite L50D-B            | [c5d02ba256](https://linux-hardware.org/?probe=c5d02ba256) | Apr 17, 2022 |
| HP            | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Toshiba       | Satellite L50D-B            | [912c61bb9b](https://linux-hardware.org/?probe=912c61bb9b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [4838334e73](https://linux-hardware.org/?probe=4838334e73) | Apr 14, 2022 |
| Dell          | Latitude D630               | [dbee98e342](https://linux-hardware.org/?probe=dbee98e342) | Apr 13, 2022 |
| HP            | 250 G5 Notebook PC          | [92b78eaf1b](https://linux-hardware.org/?probe=92b78eaf1b) | Apr 13, 2022 |
| Dell          | Inspiron 3542               | [b41fc0fac0](https://linux-hardware.org/?probe=b41fc0fac0) | Apr 13, 2022 |
| Unknown       | Z37S                        | [25d5118843](https://linux-hardware.org/?probe=25d5118843) | Apr 13, 2022 |
| Schenker      | XMG NEO (TGL/M21)           | [eeb87dca9a](https://linux-hardware.org/?probe=eeb87dca9a) | Apr 13, 2022 |
| HP            | G7000                       | [11280d88c6](https://linux-hardware.org/?probe=11280d88c6) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| Acer          | Aspire 5745G                | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Acer          | Aspire 5750G                | [8aeaa381e8](https://linux-hardware.org/?probe=8aeaa381e8) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | [722346a184](https://linux-hardware.org/?probe=722346a184) | Apr 03, 2022 |
| Sony          | VGN-AW11XU_Q                | [b3f2270d5f](https://linux-hardware.org/?probe=b3f2270d5f) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| Dell          | Latitude 7420               | [9ef752b49a](https://linux-hardware.org/?probe=9ef752b49a) | Mar 27, 2022 |
| HP            | ProBook 4530s               | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E6220              | [b006a7da3b](https://linux-hardware.org/?probe=b006a7da3b) | Mar 23, 2022 |
| Acer          | Aspire 5930                 | [ac66ce376e](https://linux-hardware.org/?probe=ac66ce376e) | Mar 23, 2022 |
| ASUSTek       | N752VX                      | [9eb7fe04cf](https://linux-hardware.org/?probe=9eb7fe04cf) | Mar 21, 2022 |
| Dell          | Latitude E7470              | [db5eecff9e](https://linux-hardware.org/?probe=db5eecff9e) | Mar 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | [321ad64376](https://linux-hardware.org/?probe=321ad64376) | Mar 13, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d5bc8e4202](https://linux-hardware.org/?probe=d5bc8e4202) | Mar 13, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| Toshiba       | Satellite C50-B             | [6bffc83185](https://linux-hardware.org/?probe=6bffc83185) | Mar 08, 2022 |
| Dell          | Latitude E6430              | [e32f5b40a1](https://linux-hardware.org/?probe=e32f5b40a1) | Mar 07, 2022 |
| ASUSTek       | X101CH                      | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Acer          | Aspire A515-44G             | [7f95a3373c](https://linux-hardware.org/?probe=7f95a3373c) | Mar 06, 2022 |
| Acer          | Aspire A515-44G             | [ea17b9cff2](https://linux-hardware.org/?probe=ea17b9cff2) | Mar 06, 2022 |
| Dell          | Inspiron 3593               | [9e9718070f](https://linux-hardware.org/?probe=9e9718070f) | Mar 02, 2022 |
| Toshiba       | Satellite C50-A-19T         | [daa7733b2d](https://linux-hardware.org/?probe=daa7733b2d) | Feb 28, 2022 |
| ASUSTek       | X550CA                      | [926781b691](https://linux-hardware.org/?probe=926781b691) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| HP            | 2000                        | [53d7131a3d](https://linux-hardware.org/?probe=53d7131a3d) | Feb 26, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| Fujitsu       | LIFEBOOK AH512              | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| ASUSTek       | X550CA                      | [ad54ee0dbe](https://linux-hardware.org/?probe=ad54ee0dbe) | Feb 20, 2022 |
| Dell          | Inspiron 5567               | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| ASUSTek       | X550CA                      | [c036f1a977](https://linux-hardware.org/?probe=c036f1a977) | Feb 20, 2022 |
| Teclast       | F7                          | [fccda8fbdc](https://linux-hardware.org/?probe=fccda8fbdc) | Feb 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b8e767511b](https://linux-hardware.org/?probe=b8e767511b) | Feb 19, 2022 |
| Lenovo        | G700 20251                  | [2e68ddfdd3](https://linux-hardware.org/?probe=2e68ddfdd3) | Feb 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| E-shop.gr     | V113                        | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| HP            | ProBook 640 G1              | [640d06ac28](https://linux-hardware.org/?probe=640d06ac28) | Feb 12, 2022 |
| E-shop.gr     | V113                        | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| HP            | Pavilion 11 x360 PC         | [dcd0177f71](https://linux-hardware.org/?probe=dcd0177f71) | Feb 07, 2022 |
| ASUSTek       | 900                         | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | [5a3fcd1230](https://linux-hardware.org/?probe=5a3fcd1230) | Feb 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [2227d37e2f](https://linux-hardware.org/?probe=2227d37e2f) | Jan 30, 2022 |
| Sony          | SVE1113M1EB                 | [83220eef23](https://linux-hardware.org/?probe=83220eef23) | Jan 30, 2022 |
| HP            | Pavilion dv3                | [c1abcb66ee](https://linux-hardware.org/?probe=c1abcb66ee) | Jan 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [48ad956cc2](https://linux-hardware.org/?probe=48ad956cc2) | Jan 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| HP            | EliteBook 8570p             | [5716cdab2a](https://linux-hardware.org/?probe=5716cdab2a) | Jan 21, 2022 |
| HP            | ProBook 640 G1              | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| Dell          | Latitude E5440              | [e4ec245baf](https://linux-hardware.org/?probe=e4ec245baf) | Jan 12, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [41205188c5](https://linux-hardware.org/?probe=41205188c5) | Jan 12, 2022 |
| Unknown       | Unknown                     | [5557e91853](https://linux-hardware.org/?probe=5557e91853) | Jan 09, 2022 |
| HP            | Notebook                    | [97eb40cec9](https://linux-hardware.org/?probe=97eb40cec9) | Jan 07, 2022 |
| Dell          | Inspiron 3585               | [bd035d052c](https://linux-hardware.org/?probe=bd035d052c) | Jan 07, 2022 |
| Lenovo        | G50-70 20351                | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| HP            | Compaq 6730s                | [bd8962f904](https://linux-hardware.org/?probe=bd8962f904) | Dec 30, 2021 |
| Acer          | AOA110                      | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| HP            | EliteBook 8570p             | [261883bf38](https://linux-hardware.org/?probe=261883bf38) | Dec 23, 2021 |
| HP            | Notebook                    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| Dell          | Vostro 3580                 | [a57edf2ddc](https://linux-hardware.org/?probe=a57edf2ddc) | Dec 22, 2021 |
| Sony          | SVE1113M1EB                 | [09619ba678](https://linux-hardware.org/?probe=09619ba678) | Dec 19, 2021 |
| Dell          | Inspiron 3585               | [e12da201c3](https://linux-hardware.org/?probe=e12da201c3) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | [f8e1e0ea63](https://linux-hardware.org/?probe=f8e1e0ea63) | Dec 16, 2021 |
| Sony          | SVE1113M1EB                 | [a91f9c891f](https://linux-hardware.org/?probe=a91f9c891f) | Dec 15, 2021 |
| HP            | G62                         | [80ca0b53f0](https://linux-hardware.org/?probe=80ca0b53f0) | Dec 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Sony          | SVF1521A1EW                 | [3ffae5f3ba](https://linux-hardware.org/?probe=3ffae5f3ba) | Dec 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b049c5de44](https://linux-hardware.org/?probe=b049c5de44) | Dec 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [191c3b9c7e](https://linux-hardware.org/?probe=191c3b9c7e) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c7efd05b73](https://linux-hardware.org/?probe=c7efd05b73) | Dec 10, 2021 |
| Toshiba       | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f0a11b91f5](https://linux-hardware.org/?probe=f0a11b91f5) | Dec 09, 2021 |
| Dell          | Inspiron 3585               | [eea11725bb](https://linux-hardware.org/?probe=eea11725bb) | Dec 06, 2021 |
| Dell          | Inspiron 3585               | [d614f524af](https://linux-hardware.org/?probe=d614f524af) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| Dell          | Inspiron 3541               | [6b187612d2](https://linux-hardware.org/?probe=6b187612d2) | Dec 04, 2021 |
| Sony          | SVE1711Q1EB                 | [a4e4d21671](https://linux-hardware.org/?probe=a4e4d21671) | Dec 04, 2021 |
| HP            | Compaq 6910p (GC021ET#AB... | [677180a63e](https://linux-hardware.org/?probe=677180a63e) | Dec 03, 2021 |
| Lenovo        | V15-ADA 82C7                | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Lenovo        | G70-35 80Q5                 | [a53168ca9d](https://linux-hardware.org/?probe=a53168ca9d) | Nov 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| HP            | Pavilion g7                 | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| Sony          | SVE1113M1EB                 | [e2df3c29e6](https://linux-hardware.org/?probe=e2df3c29e6) | Nov 29, 2021 |
| Dell          | Latitude 7490               | [c12e537d05](https://linux-hardware.org/?probe=c12e537d05) | Nov 29, 2021 |
| Toshiba       | Satellite C855-27U          | [5974840aa7](https://linux-hardware.org/?probe=5974840aa7) | Nov 27, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [82a3d5c144](https://linux-hardware.org/?probe=82a3d5c144) | Nov 27, 2021 |
| Unknown       | Unknown                     | [72b623d149](https://linux-hardware.org/?probe=72b623d149) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| Sony          | SVF1521A1EW                 | [52bd968f68](https://linux-hardware.org/?probe=52bd968f68) | Nov 25, 2021 |
| Unknown       | Unknown                     | [b6800c14dc](https://linux-hardware.org/?probe=b6800c14dc) | Nov 21, 2021 |
| Unknown       | Unknown                     | [65b01d9a8a](https://linux-hardware.org/?probe=65b01d9a8a) | Nov 21, 2021 |
| ASUSTek       | X550CC                      | [9915f9e908](https://linux-hardware.org/?probe=9915f9e908) | Nov 20, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| Acer          | TravelMate 5720             | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| Acer          | Aspire 5735                 | [9b2574c5be](https://linux-hardware.org/?probe=9b2574c5be) | Nov 17, 2021 |
| ASUSTek       | X550CC                      | [e39729aec8](https://linux-hardware.org/?probe=e39729aec8) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [b22df8f53d](https://linux-hardware.org/?probe=b22df8f53d) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [93d20530a1](https://linux-hardware.org/?probe=93d20530a1) | Nov 14, 2021 |
| Acer          | Aspire 5742                 | [4c0a93b88d](https://linux-hardware.org/?probe=4c0a93b88d) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [9dc24197f3](https://linux-hardware.org/?probe=9dc24197f3) | Nov 09, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [dc9fcc92be](https://linux-hardware.org/?probe=dc9fcc92be) | Nov 08, 2021 |
| ASUSTek       | 900                         | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| HP            | 255 G1                      | [3676d15104](https://linux-hardware.org/?probe=3676d15104) | Nov 06, 2021 |
| Sony          | SVE1513Y1ESI                | [fc86d071c2](https://linux-hardware.org/?probe=fc86d071c2) | Nov 02, 2021 |
| Fujitsu Si... | AMILO Xi 2428               | [3332a4c510](https://linux-hardware.org/?probe=3332a4c510) | Oct 30, 2021 |
| Dell          | Latitude 5520               | [370dda1922](https://linux-hardware.org/?probe=370dda1922) | Oct 28, 2021 |
| HP            | Pavilion dv7                | [d4b81612a8](https://linux-hardware.org/?probe=d4b81612a8) | Oct 28, 2021 |
| Dell          | Latitude 5520               | [2a08ef4aeb](https://linux-hardware.org/?probe=2a08ef4aeb) | Oct 27, 2021 |
| Lenovo        | ThinkPad E595 20NF0002BM    | [52ba950565](https://linux-hardware.org/?probe=52ba950565) | Oct 25, 2021 |
| HP            | EliteBook 840 G1            | [cecd552e89](https://linux-hardware.org/?probe=cecd552e89) | Oct 25, 2021 |
| Lenovo        | G50-30 80G0                 | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [16268db25b](https://linux-hardware.org/?probe=16268db25b) | Oct 22, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [963b34aa8b](https://linux-hardware.org/?probe=963b34aa8b) | Oct 22, 2021 |
| Toshiba       | Satellite L50-A-1D9         | [cd55b73689](https://linux-hardware.org/?probe=cd55b73689) | Oct 20, 2021 |
| HP            | Notebook                    | [ff690977bf](https://linux-hardware.org/?probe=ff690977bf) | Oct 19, 2021 |
| Dell          | Inspiron 3537               | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Precision M4800             | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [7ba2477e56](https://linux-hardware.org/?probe=7ba2477e56) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| ARIMA         | W651UI                      | [287379af9f](https://linux-hardware.org/?probe=287379af9f) | Oct 10, 2021 |
| MSI           | Alpha 17 A4DEK              | [eca8493d4b](https://linux-hardware.org/?probe=eca8493d4b) | Oct 07, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [415ce3638d](https://linux-hardware.org/?probe=415ce3638d) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [74e6b1bc07](https://linux-hardware.org/?probe=74e6b1bc07) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [9e35238cd2](https://linux-hardware.org/?probe=9e35238cd2) | Oct 05, 2021 |
| HP            | 255 G6 Notebook PC          | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| Lenovo        | ThinkPad T420 4236A22       | [e92d8556e9](https://linux-hardware.org/?probe=e92d8556e9) | Sep 29, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | [c5a7069c64](https://linux-hardware.org/?probe=c5a7069c64) | Sep 26, 2021 |
| Apple         | MacBookAir3,1               | [2b14368aed](https://linux-hardware.org/?probe=2b14368aed) | Sep 25, 2021 |
| HP            | Pavilion g6                 | [43a34f4589](https://linux-hardware.org/?probe=43a34f4589) | Sep 23, 2021 |
| Sony          | VGN-FW510F                  | [8f2f403347](https://linux-hardware.org/?probe=8f2f403347) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Apple         | MacBookPro8,2               | [64a2bd261a](https://linux-hardware.org/?probe=64a2bd261a) | Sep 12, 2021 |
| Acer          | Aspire 5020                 | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| Acer          | Aspire 3610                 | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0bfdb154b9](https://linux-hardware.org/?probe=0bfdb154b9) | Sep 08, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [d3f86f70ae](https://linux-hardware.org/?probe=d3f86f70ae) | Sep 03, 2021 |
| HP            | Presario CQ58               | [313af01ef8](https://linux-hardware.org/?probe=313af01ef8) | Sep 01, 2021 |
| Dell          | Inspiron 15 5510            | [cbc1dd6499](https://linux-hardware.org/?probe=cbc1dd6499) | Aug 27, 2021 |
| Sony          | SVT1122B2EW                 | [cb166ff02b](https://linux-hardware.org/?probe=cb166ff02b) | Aug 24, 2021 |
| Sony          | SVT1122B2EW                 | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [80dfc52333](https://linux-hardware.org/?probe=80dfc52333) | Aug 21, 2021 |
| HP            | 255 G7 Notebook PC          | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [301da897a6](https://linux-hardware.org/?probe=301da897a6) | Aug 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| HP            | Laptop 14s-fq0xxx           | [0cdcd7cac9](https://linux-hardware.org/?probe=0cdcd7cac9) | Aug 17, 2021 |
| Acer          | Aspire A517-51G             | [6387ddee62](https://linux-hardware.org/?probe=6387ddee62) | Aug 13, 2021 |
| Dell          | Latitude 7420               | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| HP            | Pavilion g6                 | [d4523e209b](https://linux-hardware.org/?probe=d4523e209b) | Aug 09, 2021 |
| HP            | Pavilion g6                 | [4116e486f5](https://linux-hardware.org/?probe=4116e486f5) | Aug 07, 2021 |
| Samsung       | R780                        | [f59b3d2a3f](https://linux-hardware.org/?probe=f59b3d2a3f) | Aug 05, 2021 |
| Dell          | Latitude 5410               | [5f861ac987](https://linux-hardware.org/?probe=5f861ac987) | Aug 04, 2021 |
| Dell          | Latitude 5410               | [aed58623e2](https://linux-hardware.org/?probe=aed58623e2) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | [7243281e28](https://linux-hardware.org/?probe=7243281e28) | Aug 01, 2021 |
| Dell          | Latitude 7390               | [ee6d9cb25f](https://linux-hardware.org/?probe=ee6d9cb25f) | Aug 01, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | 255 G7 Notebook PC          | [49e2ef564c](https://linux-hardware.org/?probe=49e2ef564c) | Jul 31, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [4c6cb12482](https://linux-hardware.org/?probe=4c6cb12482) | Jul 30, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [1cd2de69ff](https://linux-hardware.org/?probe=1cd2de69ff) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| Dell          | Latitude E7470              | [9d580f1809](https://linux-hardware.org/?probe=9d580f1809) | Jul 28, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | 250 G3                      | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| HP            | ProBook 470 G0              | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [4ffde7a90a](https://linux-hardware.org/?probe=4ffde7a90a) | Jul 13, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | QIQY2                       | [7f8f82feb5](https://linux-hardware.org/?probe=7f8f82feb5) | Jul 07, 2021 |
| Dell          | Latitude D531               | [5a671e0dc0](https://linux-hardware.org/?probe=5a671e0dc0) | Jul 06, 2021 |
| Dell          | Latitude D531               | [bc3e80d306](https://linux-hardware.org/?probe=bc3e80d306) | Jul 06, 2021 |
| ASUSTek       | X540UA                      | [b9169c0ae3](https://linux-hardware.org/?probe=b9169c0ae3) | Jul 05, 2021 |
| HP            | Laptop 15-bs1xx             | [f57bd1d1d8](https://linux-hardware.org/?probe=f57bd1d1d8) | Jul 04, 2021 |
| Chuwi         | GemiBook Pro                | [03f12de5a1](https://linux-hardware.org/?probe=03f12de5a1) | Jun 17, 2021 |
| HP            | 255 G7 Notebook PC          | [22c9d6c7de](https://linux-hardware.org/?probe=22c9d6c7de) | Jun 16, 2021 |
| Dell          | Latitude 7400               | [c58ebb3bf8](https://linux-hardware.org/?probe=c58ebb3bf8) | Jun 15, 2021 |
| HP            | Notebook                    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | Pavilion Notebook           | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| Chuwi         | GemiBook Pro                | [7a4b730903](https://linux-hardware.org/?probe=7a4b730903) | Jun 13, 2021 |
| Dell          | Vostro 3500                 | [128de02660](https://linux-hardware.org/?probe=128de02660) | Jun 12, 2021 |
| Dell          | Vostro 3500                 | [e8a90de6cd](https://linux-hardware.org/?probe=e8a90de6cd) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| Sony          | VGN-FW510F                  | [88362a4659](https://linux-hardware.org/?probe=88362a4659) | Jun 10, 2021 |
| Sony          | VGN-FW510F                  | [d87f3ea107](https://linux-hardware.org/?probe=d87f3ea107) | Jun 10, 2021 |
| HP            | Compaq 6910p                | [5b4d256824](https://linux-hardware.org/?probe=5b4d256824) | Jun 10, 2021 |
| Dell          | Inspiron 5559               | [356b7fd3c6](https://linux-hardware.org/?probe=356b7fd3c6) | Jun 09, 2021 |
| ASUSTek       | N550JV                      | [7973dc9123](https://linux-hardware.org/?probe=7973dc9123) | Jun 08, 2021 |
| PLAISIO CO... | TURBO-X                     | [44f5d57c9d](https://linux-hardware.org/?probe=44f5d57c9d) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | [47473943ab](https://linux-hardware.org/?probe=47473943ab) | Jun 06, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [ef4e2ca66f](https://linux-hardware.org/?probe=ef4e2ca66f) | Jun 03, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [2ff583b918](https://linux-hardware.org/?probe=2ff583b918) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [36f36a1183](https://linux-hardware.org/?probe=36f36a1183) | Jun 01, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [bd16a61719](https://linux-hardware.org/?probe=bd16a61719) | May 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [da0e32387a](https://linux-hardware.org/?probe=da0e32387a) | May 31, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | [b9c73baf1d](https://linux-hardware.org/?probe=b9c73baf1d) | May 25, 2021 |
| Lenovo        | G500 20236                  | [91cf490677](https://linux-hardware.org/?probe=91cf490677) | May 24, 2021 |
| Toshiba       | Satellite A200              | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| HP            | G62                         | [72f8505e51](https://linux-hardware.org/?probe=72f8505e51) | May 20, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | [ead418c0a3](https://linux-hardware.org/?probe=ead418c0a3) | May 17, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | [8312f6899d](https://linux-hardware.org/?probe=8312f6899d) | May 17, 2021 |
| Dell          | Precision 3551              | [a080388baa](https://linux-hardware.org/?probe=a080388baa) | May 16, 2021 |
| Dell          | Precision 3551              | [f9f9852b96](https://linux-hardware.org/?probe=f9f9852b96) | May 16, 2021 |
| HP            | Unknown                     | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| Dell          | Inspiron 3537               | [3038e4027b](https://linux-hardware.org/?probe=3038e4027b) | May 14, 2021 |
| HP            | Compaq 6735s                | [b3d6b7770a](https://linux-hardware.org/?probe=b3d6b7770a) | May 13, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e6848fb30e](https://linux-hardware.org/?probe=e6848fb30e) | May 13, 2021 |
| Notebook      | W65_67SF                    | [342074c2e1](https://linux-hardware.org/?probe=342074c2e1) | May 13, 2021 |
| Notebook      | W65_67SF                    | [54aedd8090](https://linux-hardware.org/?probe=54aedd8090) | May 13, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [643481b28f](https://linux-hardware.org/?probe=643481b28f) | May 10, 2021 |
| MSI           | GF75 Thin 10SCSR            | [d88c558cda](https://linux-hardware.org/?probe=d88c558cda) | May 09, 2021 |
| Notebook      | W65_67SF                    | [89628bc0a5](https://linux-hardware.org/?probe=89628bc0a5) | May 07, 2021 |
| Sony          | SVE1513R1EB                 | [e87dd3a1c3](https://linux-hardware.org/?probe=e87dd3a1c3) | May 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| Lenovo        | B590 20208                  | [f483fd5a3b](https://linux-hardware.org/?probe=f483fd5a3b) | May 04, 2021 |
| HP            | Compaq 6735s                | [f50dd52975](https://linux-hardware.org/?probe=f50dd52975) | May 03, 2021 |
| Unknown       | Unknown                     | [6f9d6686f3](https://linux-hardware.org/?probe=6f9d6686f3) | May 03, 2021 |
| Apple         | MacBookPro8,1               | [ad00f41e81](https://linux-hardware.org/?probe=ad00f41e81) | May 02, 2021 |
| Toshiba       | NB100                       | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| HP            | G62                         | [327a8383cf](https://linux-hardware.org/?probe=327a8383cf) | Apr 30, 2021 |
| Acer          | AO756                       | [f398615a01](https://linux-hardware.org/?probe=f398615a01) | Apr 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [eb3e5cf436](https://linux-hardware.org/?probe=eb3e5cf436) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| Dell          | G3 3590                     | [5fe47837ac](https://linux-hardware.org/?probe=5fe47837ac) | Apr 19, 2021 |
| Toshiba       | Satellite C850D-119         | [7c519e9719](https://linux-hardware.org/?probe=7c519e9719) | Apr 17, 2021 |
| Google        | Coral                       | [d0fef96a1b](https://linux-hardware.org/?probe=d0fef96a1b) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| Acer          | Predator G3-571             | [2db50fb736](https://linux-hardware.org/?probe=2db50fb736) | Apr 12, 2021 |
| HP            | 255 G1                      | [0244337bdd](https://linux-hardware.org/?probe=0244337bdd) | Apr 12, 2021 |
| HP            | 255 G1                      | [df0d528c9c](https://linux-hardware.org/?probe=df0d528c9c) | Apr 12, 2021 |
| HP            | 255 G8 Notebook PC          | [fd8afa6f02](https://linux-hardware.org/?probe=fd8afa6f02) | Apr 11, 2021 |
| HP            | 255 G8 Notebook PC          | [166de8c643](https://linux-hardware.org/?probe=166de8c643) | Apr 11, 2021 |
| Hampoo        | Cherry Trail CR V200        | [fcbaa285ef](https://linux-hardware.org/?probe=fcbaa285ef) | Apr 07, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [f1c3f62a55](https://linux-hardware.org/?probe=f1c3f62a55) | Apr 04, 2021 |
| MSI           | GF75 Thin 10SCSR            | [4c5b57df0f](https://linux-hardware.org/?probe=4c5b57df0f) | Apr 03, 2021 |
| Acer          | Aspire A315-51              | [a6ad1251de](https://linux-hardware.org/?probe=a6ad1251de) | Mar 30, 2021 |
| Toshiba       | Satellite L500              | [d11d1f9916](https://linux-hardware.org/?probe=d11d1f9916) | Mar 28, 2021 |
| Quest         | GTN1408                     | [e0a15c69a8](https://linux-hardware.org/?probe=e0a15c69a8) | Mar 25, 2021 |
| ASUSTek       | X555QG                      | [9e2fba943d](https://linux-hardware.org/?probe=9e2fba943d) | Mar 25, 2021 |
| Dell          | Latitude D530               | [bd67bc09cd](https://linux-hardware.org/?probe=bd67bc09cd) | Mar 22, 2021 |
| Acer          | Aspire 5750G                | [82fb28dfec](https://linux-hardware.org/?probe=82fb28dfec) | Mar 19, 2021 |
| ASUSTek       | X556UQK                     | [67d33fc829](https://linux-hardware.org/?probe=67d33fc829) | Mar 19, 2021 |
| ASUSTek       | N552VX                      | [79120776d5](https://linux-hardware.org/?probe=79120776d5) | Mar 14, 2021 |
| ASUSTek       | N552VX                      | [2bb101d8ca](https://linux-hardware.org/?probe=2bb101d8ca) | Mar 14, 2021 |
| HP            | G62                         | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| Teclast       | F15                         | [2a9e97f18c](https://linux-hardware.org/?probe=2a9e97f18c) | Mar 10, 2021 |
| HP            | Notebook                    | [26fdd1f108](https://linux-hardware.org/?probe=26fdd1f108) | Mar 09, 2021 |
| Dell          | Latitude E7250              | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| Acer          | Aspire E5-771G              | [693347465d](https://linux-hardware.org/?probe=693347465d) | Mar 06, 2021 |
| Info Quest... | GTN1408                     | [571eedb776](https://linux-hardware.org/?probe=571eedb776) | Mar 03, 2021 |
| Toshiba       | NB100                       | [7876cca0bb](https://linux-hardware.org/?probe=7876cca0bb) | Mar 03, 2021 |
| Dell          | Latitude E6400              | [ebe53e8b99](https://linux-hardware.org/?probe=ebe53e8b99) | Feb 28, 2021 |
| Dell          | Inspiron 5567               | [e2ede83088](https://linux-hardware.org/?probe=e2ede83088) | Feb 27, 2021 |
| Dell          | Inspiron 5567               | [951acd6af9](https://linux-hardware.org/?probe=951acd6af9) | Feb 27, 2021 |
| HP            | ProBook 430 G7              | [b4b70424b9](https://linux-hardware.org/?probe=b4b70424b9) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [cada48fb79](https://linux-hardware.org/?probe=cada48fb79) | Feb 27, 2021 |
| ASUSTek       | UX305CA                     | [65b536ca2f](https://linux-hardware.org/?probe=65b536ca2f) | Feb 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c501aa1f72](https://linux-hardware.org/?probe=c501aa1f72) | Feb 26, 2021 |
| HP            | Pavilion dv6                | [ffde1aad10](https://linux-hardware.org/?probe=ffde1aad10) | Feb 25, 2021 |
| Dell          | Latitude E6400              | [256426a815](https://linux-hardware.org/?probe=256426a815) | Feb 22, 2021 |
| HP            | Pavilion Notebook           | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| HP            | Pavilion AB7                | [410cf90e15](https://linux-hardware.org/?probe=410cf90e15) | Feb 20, 2021 |
| Fujitsu       | LIFEBOOK NH570              | [9b2fc1e55f](https://linux-hardware.org/?probe=9b2fc1e55f) | Feb 19, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6e91e6e551](https://linux-hardware.org/?probe=6e91e6e551) | Feb 18, 2021 |
| HP            | Laptop 15-db0xxx            | [9e831f773a](https://linux-hardware.org/?probe=9e831f773a) | Feb 17, 2021 |
| Dell          | Studio 1557                 | [bf361a7ed3](https://linux-hardware.org/?probe=bf361a7ed3) | Feb 16, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [38a0ac2efa](https://linux-hardware.org/?probe=38a0ac2efa) | Feb 16, 2021 |
| Dell          | Precision M6400             | [2bd1a24330](https://linux-hardware.org/?probe=2bd1a24330) | Feb 14, 2021 |
| HP            | ProBook 450 G5              | [3e6fa8f362](https://linux-hardware.org/?probe=3e6fa8f362) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| Teclast       | F15                         | [1c7d49b0b0](https://linux-hardware.org/?probe=1c7d49b0b0) | Feb 13, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [654141e59d](https://linux-hardware.org/?probe=654141e59d) | Feb 13, 2021 |
| Fujitsu Si... | AMILO Li 1818               | [68c7aa1fa1](https://linux-hardware.org/?probe=68c7aa1fa1) | Feb 09, 2021 |
| Lenovo        | G510 20238                  | [0022cd41e5](https://linux-hardware.org/?probe=0022cd41e5) | Feb 06, 2021 |
| Lenovo        | Y50-70 20378                | [a95bc37d1f](https://linux-hardware.org/?probe=a95bc37d1f) | Feb 03, 2021 |
| HP            | G62                         | [273bf04457](https://linux-hardware.org/?probe=273bf04457) | Feb 03, 2021 |
| HP            | G62                         | [a74ecdb45c](https://linux-hardware.org/?probe=a74ecdb45c) | Feb 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| HP            | Pavilion Sleekbook 15       | [bf72f555cb](https://linux-hardware.org/?probe=bf72f555cb) | Jan 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| Acer          | Aspire A517-51G             | [7b7f7244e6](https://linux-hardware.org/?probe=7b7f7244e6) | Jan 28, 2021 |
| Lenovo        | G510 20238                  | [c53a37fb5a](https://linux-hardware.org/?probe=c53a37fb5a) | Jan 28, 2021 |
| HP            | Unknown                     | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| IBM           | ThinkPad T41 2373271        | [71daf2c5b4](https://linux-hardware.org/?probe=71daf2c5b4) | Jan 26, 2021 |
| Fujitsu       | AMILO Pi 3560               | [a54f523eae](https://linux-hardware.org/?probe=a54f523eae) | Jan 26, 2021 |
| HP            | 255 G7 Notebook PC          | [54bfedf54f](https://linux-hardware.org/?probe=54bfedf54f) | Jan 24, 2021 |
| Lenovo        | G40-30 80FY                 | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Unknown                     | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| Toshiba       | Satellite L50-B             | [6e7fe8b488](https://linux-hardware.org/?probe=6e7fe8b488) | Jan 18, 2021 |
| Toshiba       | Satellite L50-B             | [df23913572](https://linux-hardware.org/?probe=df23913572) | Jan 18, 2021 |
| HP            | 550                         | [384b3f65ed](https://linux-hardware.org/?probe=384b3f65ed) | Jan 18, 2021 |
| Acer          | Aspire 1410                 | [c7045484b1](https://linux-hardware.org/?probe=c7045484b1) | Jan 16, 2021 |
| Sony          | VPCS11X9E                   | [279fb61afa](https://linux-hardware.org/?probe=279fb61afa) | Jan 16, 2021 |
| Acer          | Aspire E1-571G              | [051b3d5b1b](https://linux-hardware.org/?probe=051b3d5b1b) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [a137e1b57f](https://linux-hardware.org/?probe=a137e1b57f) | Jan 11, 2021 |
| Medion        | P6612                       | [5e83afdaae](https://linux-hardware.org/?probe=5e83afdaae) | Jan 11, 2021 |
| Dell          | G3 3579                     | [d48d0d6f85](https://linux-hardware.org/?probe=d48d0d6f85) | Jan 11, 2021 |
| HP            | 550                         | [10da4607b5](https://linux-hardware.org/?probe=10da4607b5) | Jan 11, 2021 |
| Lenovo        | ThinkPad T430 2347AG4       | [01c5b6209d](https://linux-hardware.org/?probe=01c5b6209d) | Jan 11, 2021 |
| Dell          | Precision 3551              | [1f3d433e7b](https://linux-hardware.org/?probe=1f3d433e7b) | Jan 07, 2021 |
| Dell          | Precision 3551              | [b9869afb9a](https://linux-hardware.org/?probe=b9869afb9a) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [2040f17b4e](https://linux-hardware.org/?probe=2040f17b4e) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [7758717ed0](https://linux-hardware.org/?probe=7758717ed0) | Jan 07, 2021 |
| Unknown       | Unknown                     | [394c90d235](https://linux-hardware.org/?probe=394c90d235) | Jan 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7fa2f92090](https://linux-hardware.org/?probe=7fa2f92090) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [010507185c](https://linux-hardware.org/?probe=010507185c) | Jan 03, 2021 |
| HP            | G62                         | [26fedb2989](https://linux-hardware.org/?probe=26fedb2989) | Jan 03, 2021 |
| Sony          | VGN-CR11S_W                 | [e7b02a15dc](https://linux-hardware.org/?probe=e7b02a15dc) | Dec 30, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [33e1b7b962](https://linux-hardware.org/?probe=33e1b7b962) | Dec 28, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [7463092751](https://linux-hardware.org/?probe=7463092751) | Dec 28, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [cb411462ef](https://linux-hardware.org/?probe=cb411462ef) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | [502b2847a6](https://linux-hardware.org/?probe=502b2847a6) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | [29cadd906c](https://linux-hardware.org/?probe=29cadd906c) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| Dell          | Inspiron 5567               | [4bed00686e](https://linux-hardware.org/?probe=4bed00686e) | Dec 27, 2020 |
| Lenovo        | 3000 G530 444624G           | [34e6d98329](https://linux-hardware.org/?probe=34e6d98329) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| HP            | Pavilion dv7                | [cc13d41ddd](https://linux-hardware.org/?probe=cc13d41ddd) | Dec 25, 2020 |
| Dell          | XPS 15 7590                 | [2974690eda](https://linux-hardware.org/?probe=2974690eda) | Dec 25, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| HP            | Laptop 15-db0xxx            | [08f4092908](https://linux-hardware.org/?probe=08f4092908) | Dec 21, 2020 |
| Lenovo        | ThinkPad X200 7458Y28       | [508111c39d](https://linux-hardware.org/?probe=508111c39d) | Dec 20, 2020 |
| HP            | Laptop 15-db1xxx            | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| Lenovo        | IdeaPad S210 Touch 20257    | [faacb1a39b](https://linux-hardware.org/?probe=faacb1a39b) | Dec 19, 2020 |
| Lenovo        | ThinkPad X220 4291W3B       | [0cb7ed54d1](https://linux-hardware.org/?probe=0cb7ed54d1) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [c5c8b0a320](https://linux-hardware.org/?probe=c5c8b0a320) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [1a68fc4e19](https://linux-hardware.org/?probe=1a68fc4e19) | Dec 19, 2020 |
| Toshiba       | NB100                       | [01daa00e87](https://linux-hardware.org/?probe=01daa00e87) | Dec 19, 2020 |
| Dell          | Latitude D520               | [7f5d3e9a40](https://linux-hardware.org/?probe=7f5d3e9a40) | Dec 19, 2020 |
| Lenovo        | 3000 G530 444624G           | [fb187878c5](https://linux-hardware.org/?probe=fb187878c5) | Dec 16, 2020 |
| ASUSTek       | X550CC                      | [d8723f48ef](https://linux-hardware.org/?probe=d8723f48ef) | Dec 15, 2020 |
| Sony          | VPCCB2S1E                   | [dadaeb0257](https://linux-hardware.org/?probe=dadaeb0257) | Dec 14, 2020 |
| Sony          | VPCCB2S1E                   | [b08942a95c](https://linux-hardware.org/?probe=b08942a95c) | Dec 14, 2020 |
| Lenovo        | G50-80 80L0                 | [951a5a280f](https://linux-hardware.org/?probe=951a5a280f) | Dec 11, 2020 |
| Sony          | VGN-CR11S_W                 | [9f07e6181c](https://linux-hardware.org/?probe=9f07e6181c) | Dec 10, 2020 |
| HP            | OMEN by Laptop              | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b7becb585e](https://linux-hardware.org/?probe=b7becb585e) | Dec 08, 2020 |
| Intel         | CAPELL VALLEY CRB           | [59d2069d40](https://linux-hardware.org/?probe=59d2069d40) | Dec 07, 2020 |
| Intel         | CAPELL VALLEY CRB           | [ce350750e3](https://linux-hardware.org/?probe=ce350750e3) | Dec 05, 2020 |
| Toshiba       | Satellite C850D-119         | [4a0f2ef22e](https://linux-hardware.org/?probe=4a0f2ef22e) | Dec 05, 2020 |
| HP            | Pavilion dv7                | [ea3cf2d030](https://linux-hardware.org/?probe=ea3cf2d030) | Dec 04, 2020 |
| Lenovo        | G70-35 80Q5                 | [455f011c08](https://linux-hardware.org/?probe=455f011c08) | Dec 03, 2020 |
| ASUSTek       | X556UQK                     | [529e0c244d](https://linux-hardware.org/?probe=529e0c244d) | Dec 02, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [09b180815e](https://linux-hardware.org/?probe=09b180815e) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| Lenovo        | G70-35 80Q5                 | [23ee81bd5e](https://linux-hardware.org/?probe=23ee81bd5e) | Dec 01, 2020 |
| HP            | Pavilion Notebook           | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| Toshiba       | NB100                       | [73e92718a9](https://linux-hardware.org/?probe=73e92718a9) | Dec 01, 2020 |
| HP            | Unknown                     | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| Sony          | VPCW12J1E                   | [7f54f3a6f0](https://linux-hardware.org/?probe=7f54f3a6f0) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Acer          | Predator G5-793             | [ae170a3127](https://linux-hardware.org/?probe=ae170a3127) | Nov 30, 2020 |
| Acer          | Aspire 5738                 | [c34c324fc5](https://linux-hardware.org/?probe=c34c324fc5) | Nov 28, 2020 |
| HP            | EliteBook 850 G5            | [e261ebbf0e](https://linux-hardware.org/?probe=e261ebbf0e) | Nov 26, 2020 |
| Toshiba       | Satellite P500              | [25e5577463](https://linux-hardware.org/?probe=25e5577463) | Nov 24, 2020 |
| Dell          | Inspiron 5570               | [2074f71e04](https://linux-hardware.org/?probe=2074f71e04) | Nov 24, 2020 |
| Dell          | Inspiron 3537               | [0bc23c46e1](https://linux-hardware.org/?probe=0bc23c46e1) | Nov 23, 2020 |
| Acer          | Aspire 9500                 | [14c016a2f9](https://linux-hardware.org/?probe=14c016a2f9) | Nov 22, 2020 |
| HP            | EliteBook 840 G3            | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP            | EliteBook 840 G3            | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [00c9bbbec5](https://linux-hardware.org/?probe=00c9bbbec5) | Nov 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [baae1bd1ef](https://linux-hardware.org/?probe=baae1bd1ef) | Nov 20, 2020 |
| HP            | 14                          | [99583d854a](https://linux-hardware.org/?probe=99583d854a) | Nov 20, 2020 |
| Dell          | Inspiron 3542               | [6647cfca50](https://linux-hardware.org/?probe=6647cfca50) | Nov 18, 2020 |
| HP            | Pavilion g6                 | [4a521aad50](https://linux-hardware.org/?probe=4a521aad50) | Nov 16, 2020 |
| Clevo         | W55xEU                      | [932e7d8f27](https://linux-hardware.org/?probe=932e7d8f27) | Nov 16, 2020 |
| HP            | Laptop 17-ca1xxx            | [43e0f99b97](https://linux-hardware.org/?probe=43e0f99b97) | Nov 14, 2020 |
| HUAWEI        | KLVL-WXX9                   | [bd2dcac2ac](https://linux-hardware.org/?probe=bd2dcac2ac) | Nov 12, 2020 |
| Fujitsu Si... | AMILO Li1705                | [3233bbc0ec](https://linux-hardware.org/?probe=3233bbc0ec) | Nov 12, 2020 |
| MSI           | GE70 2OC\2OE                | [ba1376cdb9](https://linux-hardware.org/?probe=ba1376cdb9) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [0c0bf4e794](https://linux-hardware.org/?probe=0c0bf4e794) | Nov 11, 2020 |
| Dell          | Inspiron 3593               | [005da6030a](https://linux-hardware.org/?probe=005da6030a) | Nov 11, 2020 |
| ASUSTek       | X540LJ                      | [3a7e7932f2](https://linux-hardware.org/?probe=3a7e7932f2) | Nov 10, 2020 |
| Dell          | Latitude 7400               | [95aa8c5f82](https://linux-hardware.org/?probe=95aa8c5f82) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [b30631ff4c](https://linux-hardware.org/?probe=b30631ff4c) | Nov 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5a78c67deb](https://linux-hardware.org/?probe=5a78c67deb) | Oct 30, 2020 |
| HP            | 15                          | [8ebe037b8f](https://linux-hardware.org/?probe=8ebe037b8f) | Oct 29, 2020 |
| Toshiba       | Satellite C850D-119         | [493e216eea](https://linux-hardware.org/?probe=493e216eea) | Oct 25, 2020 |
| HP            | 255 G1                      | [bfd456834c](https://linux-hardware.org/?probe=bfd456834c) | Oct 24, 2020 |
| Toshiba       | Satellite P200              | [84d2d0d8cf](https://linux-hardware.org/?probe=84d2d0d8cf) | Oct 21, 2020 |
| Toshiba       | Satellite P200              | [932b71224c](https://linux-hardware.org/?probe=932b71224c) | Oct 21, 2020 |
| HP            | Pavilion x2 Detachable      | [b7f2a6ef39](https://linux-hardware.org/?probe=b7f2a6ef39) | Oct 21, 2020 |
| Dell          | System XPS L502X            | [dc6eea4b63](https://linux-hardware.org/?probe=dc6eea4b63) | Oct 17, 2020 |
| Clevo         | M550SE/M660SE VT6363A       | [01a8ac7cd9](https://linux-hardware.org/?probe=01a8ac7cd9) | Oct 14, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4974ae8ad2](https://linux-hardware.org/?probe=4974ae8ad2) | Oct 13, 2020 |
| Sony          | VPCCB2S1E                   | [8a80ad4971](https://linux-hardware.org/?probe=8a80ad4971) | Oct 13, 2020 |
| Clevo         | M550SE/M660SE VT6363A       | [9bd883acaa](https://linux-hardware.org/?probe=9bd883acaa) | Oct 12, 2020 |
| Dell          | G3 3590                     | [e710fb7efe](https://linux-hardware.org/?probe=e710fb7efe) | Oct 12, 2020 |
| ASUSTek       | GL702ZC                     | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [33f4f77db5](https://linux-hardware.org/?probe=33f4f77db5) | Oct 10, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | [8700c3217b](https://linux-hardware.org/?probe=8700c3217b) | Oct 10, 2020 |
| HP            | Notebook                    | [1e6bba57b7](https://linux-hardware.org/?probe=1e6bba57b7) | Oct 09, 2020 |
| Acer          | AO531h                      | [af1d7d28cc](https://linux-hardware.org/?probe=af1d7d28cc) | Oct 07, 2020 |
| Acer          | Aspire 5738                 | [f814a33c4c](https://linux-hardware.org/?probe=f814a33c4c) | Oct 07, 2020 |
| HP            | Pavilion g6                 | [c1ff9eb372](https://linux-hardware.org/?probe=c1ff9eb372) | Oct 06, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [2436dcb42a](https://linux-hardware.org/?probe=2436dcb42a) | Oct 02, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [815070f834](https://linux-hardware.org/?probe=815070f834) | Oct 02, 2020 |
| Lenovo        | ThinkPad E580 20KS006GUK    | [43cd14b799](https://linux-hardware.org/?probe=43cd14b799) | Oct 01, 2020 |
| HP            | Pavilion Notebook           | [85a733886a](https://linux-hardware.org/?probe=85a733886a) | Sep 29, 2020 |
| Dell          | XPS M1530                   | [dc08069215](https://linux-hardware.org/?probe=dc08069215) | Sep 29, 2020 |
| Sony          | VPCM13M1E                   | [139119fce3](https://linux-hardware.org/?probe=139119fce3) | Sep 28, 2020 |
| Sony          | VPCM13M1E                   | [40da79e9dc](https://linux-hardware.org/?probe=40da79e9dc) | Sep 28, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | [f6809ca4e3](https://linux-hardware.org/?probe=f6809ca4e3) | Sep 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [135cb18944](https://linux-hardware.org/?probe=135cb18944) | Sep 26, 2020 |
| Toshiba       | Satellite L750              | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | Pavilion g6                 | [7ed6ea1d8e](https://linux-hardware.org/?probe=7ed6ea1d8e) | Sep 24, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [301fab4ca7](https://linux-hardware.org/?probe=301fab4ca7) | Sep 17, 2020 |
| HP            | Pavilion Notebook           | [a1e9bd74fd](https://linux-hardware.org/?probe=a1e9bd74fd) | Sep 17, 2020 |
| Toshiba       | Satellite L750              | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [9149c8b59c](https://linux-hardware.org/?probe=9149c8b59c) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [d549f8665d](https://linux-hardware.org/?probe=d549f8665d) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [41a8975f07](https://linux-hardware.org/?probe=41a8975f07) | Sep 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | Aspire A315-31              | [118b474cc3](https://linux-hardware.org/?probe=118b474cc3) | Sep 06, 2020 |
| Dell          | Latitude 5400               | [1ae84c03c5](https://linux-hardware.org/?probe=1ae84c03c5) | Sep 02, 2020 |
| HP            | 15                          | [5b582297ed](https://linux-hardware.org/?probe=5b582297ed) | Sep 02, 2020 |
| Dell          | Inspiron 7720               | [9f2a48a228](https://linux-hardware.org/?probe=9f2a48a228) | Aug 25, 2020 |
| HP            | Compaq 6735s                | [529e1a4543](https://linux-hardware.org/?probe=529e1a4543) | Aug 21, 2020 |
| HP            | Pavilion Notebook           | [2afa749d39](https://linux-hardware.org/?probe=2afa749d39) | Aug 19, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [5faf279c4f](https://linux-hardware.org/?probe=5faf279c4f) | Aug 17, 2020 |
| Dell          | Inspiron 7559               | [85dd645b39](https://linux-hardware.org/?probe=85dd645b39) | Aug 16, 2020 |
| Lenovo        | V145-15AST 81MT             | [8b03ada262](https://linux-hardware.org/?probe=8b03ada262) | Aug 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [a9262f65c0](https://linux-hardware.org/?probe=a9262f65c0) | Aug 15, 2020 |
| Dell          | Vostro 5481                 | [fc1a36f64d](https://linux-hardware.org/?probe=fc1a36f64d) | Aug 13, 2020 |
| Toshiba       | Satellite P200D             | [9bb94d56ed](https://linux-hardware.org/?probe=9bb94d56ed) | Aug 06, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [20185e7b49](https://linux-hardware.org/?probe=20185e7b49) | Aug 04, 2020 |
| Hampoo        | Cherry Trail CR V200        | [62925bc138](https://linux-hardware.org/?probe=62925bc138) | Aug 01, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [50226c4586](https://linux-hardware.org/?probe=50226c4586) | Jul 30, 2020 |
| Dell          | Inspiron 5567               | [25489b5aa4](https://linux-hardware.org/?probe=25489b5aa4) | Jul 29, 2020 |
| Dell          | Inspiron 5567               | [d690a1848c](https://linux-hardware.org/?probe=d690a1848c) | Jul 29, 2020 |
| HP            | 250 G6 Notebook PC          | [7b6b423b68](https://linux-hardware.org/?probe=7b6b423b68) | Jul 23, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [192dd297bd](https://linux-hardware.org/?probe=192dd297bd) | Jul 22, 2020 |
| Dell          | G3 3590                     | [0bfa0fdeb2](https://linux-hardware.org/?probe=0bfa0fdeb2) | Jul 22, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [b73a34930b](https://linux-hardware.org/?probe=b73a34930b) | Jul 21, 2020 |
| HP            | ElitePad 1000 G2            | [b2c793bfb4](https://linux-hardware.org/?probe=b2c793bfb4) | Jul 09, 2020 |
| Dell          | Inspiron 3543               | [39df7edbea](https://linux-hardware.org/?probe=39df7edbea) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [152f8e9ebd](https://linux-hardware.org/?probe=152f8e9ebd) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [5054174795](https://linux-hardware.org/?probe=5054174795) | Jul 08, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | [717049c98f](https://linux-hardware.org/?probe=717049c98f) | Jul 07, 2020 |
| Acer          | Aspire A315-53G             | [b6506c9a23](https://linux-hardware.org/?probe=b6506c9a23) | Jul 07, 2020 |
| Fujitsu       | LIFEBOOK E751               | [6f4a149255](https://linux-hardware.org/?probe=6f4a149255) | Jul 02, 2020 |
| Lenovo        | G40-30 80FY                 | [2e7c3657fb](https://linux-hardware.org/?probe=2e7c3657fb) | Jun 30, 2020 |
| Notebook      | NJ50_70CU                   | [5c9684cdab](https://linux-hardware.org/?probe=5c9684cdab) | Jun 29, 2020 |
| Lenovo        | G40-30 80FY                 | [5cfcbbb4a4](https://linux-hardware.org/?probe=5cfcbbb4a4) | Jun 28, 2020 |
| Notebook      | NJ50_70CU                   | [427a02d3bc](https://linux-hardware.org/?probe=427a02d3bc) | Jun 27, 2020 |
| Dell          | Inspiron 15-3552            | [9b7f2ae65e](https://linux-hardware.org/?probe=9b7f2ae65e) | Jun 25, 2020 |
| HP            | ZBook 15                    | [ac608e1d37](https://linux-hardware.org/?probe=ac608e1d37) | Jun 25, 2020 |
| HP            | ProBook 6560b               | [5db87fcc49](https://linux-hardware.org/?probe=5db87fcc49) | Jun 24, 2020 |
| HP            | ProBook 6560b               | [9a78de8ed6](https://linux-hardware.org/?probe=9a78de8ed6) | Jun 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [31b59ae094](https://linux-hardware.org/?probe=31b59ae094) | Jun 24, 2020 |
| Lenovo        | ThinkPad P50 20EQS2CY01     | [68f2706e1c](https://linux-hardware.org/?probe=68f2706e1c) | Jun 22, 2020 |
| Sony          | VGN-N31Z_W                  | [9dbeef64ee](https://linux-hardware.org/?probe=9dbeef64ee) | Jun 22, 2020 |
| ASUSTek       | K52JU                       | [38a9288b85](https://linux-hardware.org/?probe=38a9288b85) | Jun 21, 2020 |
| ASUSTek       | K52JU                       | [a07e2655ec](https://linux-hardware.org/?probe=a07e2655ec) | Jun 21, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [c2f7f39a83](https://linux-hardware.org/?probe=c2f7f39a83) | Jun 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b388cd0a96](https://linux-hardware.org/?probe=b388cd0a96) | Jun 20, 2020 |
| ASUSTek       | X556UQK                     | [c6c57358a6](https://linux-hardware.org/?probe=c6c57358a6) | Jun 18, 2020 |
| Toshiba       | Satellite A300D             | [872199f2c5](https://linux-hardware.org/?probe=872199f2c5) | Jun 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [eaccc0249f](https://linux-hardware.org/?probe=eaccc0249f) | Jun 17, 2020 |
| Toshiba       | Satellite A300D             | [8e0f23dc31](https://linux-hardware.org/?probe=8e0f23dc31) | Jun 16, 2020 |
| HP            | 15                          | [7644a7713f](https://linux-hardware.org/?probe=7644a7713f) | Jun 16, 2020 |
| Acer          | Aspire 3935                 | [3957942dc1](https://linux-hardware.org/?probe=3957942dc1) | Jun 10, 2020 |
| HP            | Pavilion dv7                | [27d5196b74](https://linux-hardware.org/?probe=27d5196b74) | May 30, 2020 |
| Lenovo        | V330-14ARR 81B1             | [659d266fe7](https://linux-hardware.org/?probe=659d266fe7) | May 30, 2020 |
| HP            | 255 G7 Notebook PC          | [e4bba31386](https://linux-hardware.org/?probe=e4bba31386) | May 29, 2020 |
| HP            | 255 G7 Notebook PC          | [bd6ea57435](https://linux-hardware.org/?probe=bd6ea57435) | May 29, 2020 |
| Toshiba       | Satellite S855D             | [2b4ff1e9b6](https://linux-hardware.org/?probe=2b4ff1e9b6) | May 29, 2020 |
| Toshiba       | Satellite S855D             | [8e54bbb3e2](https://linux-hardware.org/?probe=8e54bbb3e2) | May 29, 2020 |
| Lenovo        | ThinkPad P50 20EQS2CY01     | [9975194681](https://linux-hardware.org/?probe=9975194681) | May 28, 2020 |
| HP            | Pavilion g6                 | [1fd4402991](https://linux-hardware.org/?probe=1fd4402991) | May 28, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | [15696a9c46](https://linux-hardware.org/?probe=15696a9c46) | May 28, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [0508854129](https://linux-hardware.org/?probe=0508854129) | May 27, 2020 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0d35855885](https://linux-hardware.org/?probe=0d35855885) | May 25, 2020 |
| Lenovo        | ThinkPad T580 20L90023RT    | [a7b6c79ac0](https://linux-hardware.org/?probe=a7b6c79ac0) | May 24, 2020 |
| HP            | Pavilion dv7                | [9d4e0753f6](https://linux-hardware.org/?probe=9d4e0753f6) | May 23, 2020 |
| HP            | Unknown                     | [f8fa416688](https://linux-hardware.org/?probe=f8fa416688) | May 22, 2020 |
| Dell          | Latitude E6410              | [7c8e49e14c](https://linux-hardware.org/?probe=7c8e49e14c) | May 22, 2020 |
| HP            | Compaq Presario C700        | [32ab884c0f](https://linux-hardware.org/?probe=32ab884c0f) | May 21, 2020 |
| HP            | Pavilion g6                 | [31a778de5b](https://linux-hardware.org/?probe=31a778de5b) | May 18, 2020 |
| HP            | Pavilion g6                 | [619ed13a7f](https://linux-hardware.org/?probe=619ed13a7f) | May 18, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [fa51e14d38](https://linux-hardware.org/?probe=fa51e14d38) | May 17, 2020 |
| Intel         | CAPELL VALLEY CRB           | [67b7ec6a84](https://linux-hardware.org/?probe=67b7ec6a84) | May 17, 2020 |
| HP            | Pavilion g6                 | [f5334be644](https://linux-hardware.org/?probe=f5334be644) | May 17, 2020 |
| Notebook      | W65_67SH                    | [497422c9fc](https://linux-hardware.org/?probe=497422c9fc) | May 16, 2020 |
| Notebook      | W65_67SH                    | [9559aff349](https://linux-hardware.org/?probe=9559aff349) | May 16, 2020 |
| Dell          | Latitude E5410              | [b51e124387](https://linux-hardware.org/?probe=b51e124387) | May 13, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [d225d411f9](https://linux-hardware.org/?probe=d225d411f9) | May 13, 2020 |
| HP            | 250 G4                      | [adc4529aff](https://linux-hardware.org/?probe=adc4529aff) | May 12, 2020 |
| Lenovo        | ThinkPad X230 23245D4       | [740b68266b](https://linux-hardware.org/?probe=740b68266b) | May 12, 2020 |
| Dell          | G3 3590                     | [85e10bcd60](https://linux-hardware.org/?probe=85e10bcd60) | May 11, 2020 |
| Toshiba       | NB100                       | [3459eb4984](https://linux-hardware.org/?probe=3459eb4984) | May 11, 2020 |
| HP            | Unknown                     | [b52569877b](https://linux-hardware.org/?probe=b52569877b) | May 11, 2020 |
| HP            | Pavilion Notebook           | [57203b3010](https://linux-hardware.org/?probe=57203b3010) | May 11, 2020 |
| HP            | G5000 (GF767EA#B1A)         | [39fd61954e](https://linux-hardware.org/?probe=39fd61954e) | May 10, 2020 |
| Dell          | Inspiron 3542               | [231fda4e89](https://linux-hardware.org/?probe=231fda4e89) | May 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS0110B    | [9da7641ead](https://linux-hardware.org/?probe=9da7641ead) | May 07, 2020 |
| Pegatron      | D15R                        | [9b128d4d23](https://linux-hardware.org/?probe=9b128d4d23) | May 05, 2020 |
| Pegatron      | D15R                        | [25cf2e91d8](https://linux-hardware.org/?probe=25cf2e91d8) | May 05, 2020 |
| Sony          | VGN-CR590E                  | [cb2c7466cc](https://linux-hardware.org/?probe=cb2c7466cc) | May 04, 2020 |
| Acer          | Aspire 5100                 | [0b4ce05d4b](https://linux-hardware.org/?probe=0b4ce05d4b) | May 03, 2020 |
| Fujitsu Si... | AMILO M1451G Series         | [f77cb5d716](https://linux-hardware.org/?probe=f77cb5d716) | Apr 30, 2020 |
| Lenovo        | G580 20150                  | [158ef386df](https://linux-hardware.org/?probe=158ef386df) | Apr 29, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [7deee5c6f4](https://linux-hardware.org/?probe=7deee5c6f4) | Apr 28, 2020 |
| HP            | ProBook 6560b               | [f7e0abeaf2](https://linux-hardware.org/?probe=f7e0abeaf2) | Apr 27, 2020 |
| HP            | Pavilion g6                 | [166222e5c9](https://linux-hardware.org/?probe=166222e5c9) | Apr 26, 2020 |
| HP            | Pavilion g6                 | [e5e0d5140e](https://linux-hardware.org/?probe=e5e0d5140e) | Apr 25, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [6770cf29bb](https://linux-hardware.org/?probe=6770cf29bb) | Apr 25, 2020 |
| Sony          | VGN-FE41E                   | [1d8645be3f](https://linux-hardware.org/?probe=1d8645be3f) | Apr 24, 2020 |
| Apple         | MacBook5,2                  | [33530c3091](https://linux-hardware.org/?probe=33530c3091) | Apr 21, 2020 |
| Apple         | MacBook5,2                  | [fbb9346ad4](https://linux-hardware.org/?probe=fbb9346ad4) | Apr 21, 2020 |
| Toshiba       | Satellite L450D             | [7f26f2d180](https://linux-hardware.org/?probe=7f26f2d180) | Apr 20, 2020 |
| HP            | Unknown                     | [6cd3c0a036](https://linux-hardware.org/?probe=6cd3c0a036) | Apr 19, 2020 |
| HP            | Unknown                     | [7a5b60f20c](https://linux-hardware.org/?probe=7a5b60f20c) | Apr 19, 2020 |
| HP            | Unknown                     | [97ca26d3d7](https://linux-hardware.org/?probe=97ca26d3d7) | Apr 19, 2020 |
| Toshiba       | Satellite L450D             | [f541e27fef](https://linux-hardware.org/?probe=f541e27fef) | Apr 14, 2020 |
| Toshiba       | Satellite L450D             | [dd6245c9f1](https://linux-hardware.org/?probe=dd6245c9f1) | Apr 14, 2020 |
| HP            | Compaq 6710b (GR680EA#B1... | [fb9d604f9d](https://linux-hardware.org/?probe=fb9d604f9d) | Apr 13, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [20eeb3f580](https://linux-hardware.org/?probe=20eeb3f580) | Apr 12, 2020 |
| Lenovo        | G510 20238                  | [72f97922cc](https://linux-hardware.org/?probe=72f97922cc) | Apr 09, 2020 |
| Lenovo        | G510 20238                  | [126766dead](https://linux-hardware.org/?probe=126766dead) | Apr 09, 2020 |
| Dell          | Inspiron 5558               | [9ecfa320c9](https://linux-hardware.org/?probe=9ecfa320c9) | Apr 08, 2020 |
| Dell          | G3 3590                     | [9466a720ff](https://linux-hardware.org/?probe=9466a720ff) | Apr 07, 2020 |
| HP            | Pavilion dv7                | [88ff5b44b7](https://linux-hardware.org/?probe=88ff5b44b7) | Apr 07, 2020 |
| Dell          | Latitude E6510              | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| HP            | Presario CQ62               | [3821156090](https://linux-hardware.org/?probe=3821156090) | Apr 06, 2020 |
| ASUSTek       | X540LJ                      | [3818f5dd9e](https://linux-hardware.org/?probe=3818f5dd9e) | Apr 05, 2020 |
| Dell          | Inspiron 1750               | [3b7ede7bc6](https://linux-hardware.org/?probe=3b7ede7bc6) | Apr 05, 2020 |
| HP            | Pavilion dv7                | [88debf96e8](https://linux-hardware.org/?probe=88debf96e8) | Apr 04, 2020 |
| HP            | Pavilion dv7                | [d64ce74086](https://linux-hardware.org/?probe=d64ce74086) | Apr 04, 2020 |
| Sony          | VGN-CR590E                  | [121394a15c](https://linux-hardware.org/?probe=121394a15c) | Apr 03, 2020 |
| E-shop.gr     | Innovator M1589             | [be146dfa67](https://linux-hardware.org/?probe=be146dfa67) | Mar 31, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [9c2eef7d10](https://linux-hardware.org/?probe=9c2eef7d10) | Mar 31, 2020 |
| Lenovo        | G50-70 20351                | [199d2287e2](https://linux-hardware.org/?probe=199d2287e2) | Mar 30, 2020 |
| Sony          | VPCM13M1E                   | [eb20399d8b](https://linux-hardware.org/?probe=eb20399d8b) | Mar 30, 2020 |
| Apple         | MacBook1,1                  | [27d210b0e2](https://linux-hardware.org/?probe=27d210b0e2) | Mar 30, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b9f6bf0ad4](https://linux-hardware.org/?probe=b9f6bf0ad4) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | [1ecc8fa4d3](https://linux-hardware.org/?probe=1ecc8fa4d3) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | [8d2c258ed7](https://linux-hardware.org/?probe=8d2c258ed7) | Mar 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [220c3c60b0](https://linux-hardware.org/?probe=220c3c60b0) | Mar 28, 2020 |
| Dell          | Inspiron 3543               | [5d80035b8d](https://linux-hardware.org/?probe=5d80035b8d) | Mar 27, 2020 |
| HP            | Compaq Mini 110c-1000       | [ba8efb8d78](https://linux-hardware.org/?probe=ba8efb8d78) | Mar 26, 2020 |
| Lenovo        | G50-70 20351                | [d361a95cae](https://linux-hardware.org/?probe=d361a95cae) | Mar 24, 2020 |
| Dell          | G3 3590                     | [ff14d5222d](https://linux-hardware.org/?probe=ff14d5222d) | Mar 24, 2020 |
| Sony          | VGN-NR11Z_S                 | [69fb7aa4d4](https://linux-hardware.org/?probe=69fb7aa4d4) | Mar 23, 2020 |
| HP            | ProBook 6560b               | [40d00a5fb1](https://linux-hardware.org/?probe=40d00a5fb1) | Mar 16, 2020 |
| Lenovo        | ThinkPad T490 20N2000BRT    | [a6b3d80476](https://linux-hardware.org/?probe=a6b3d80476) | Mar 11, 2020 |
| Lenovo        | ThinkPad T470 20HD000LUK    | [9c47172207](https://linux-hardware.org/?probe=9c47172207) | Mar 08, 2020 |
| Lenovo        | ThinkPad T420 4236Q23       | [65d50c61eb](https://linux-hardware.org/?probe=65d50c61eb) | Mar 05, 2020 |
| Acer          | Aspire A315-53G             | [150b9c6b6d](https://linux-hardware.org/?probe=150b9c6b6d) | Feb 25, 2020 |
| Compal        | JHL90 REFERENCE             | [56b05900a0](https://linux-hardware.org/?probe=56b05900a0) | Feb 24, 2020 |
| Dell          | Inspiron 15-3567            | [270e63cceb](https://linux-hardware.org/?probe=270e63cceb) | Feb 23, 2020 |
| Acer          | Aspire A315-51              | [77543de863](https://linux-hardware.org/?probe=77543de863) | Feb 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f3fe28b459](https://linux-hardware.org/?probe=f3fe28b459) | Feb 19, 2020 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [6beff5886c](https://linux-hardware.org/?probe=6beff5886c) | Feb 19, 2020 |
| HP            | EliteBook 6930p (KK082AV... | [55a53b12ce](https://linux-hardware.org/?probe=55a53b12ce) | Feb 15, 2020 |
| HP            | EliteBook 6930p (KK082AV... | [745a30749e](https://linux-hardware.org/?probe=745a30749e) | Feb 15, 2020 |
| HP            | EliteBook 8460p             | [b57c6ec496](https://linux-hardware.org/?probe=b57c6ec496) | Feb 12, 2020 |
| Chuwi         | HeroBook                    | [c63663b03e](https://linux-hardware.org/?probe=c63663b03e) | Feb 09, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b350a4e79](https://linux-hardware.org/?probe=7b350a4e79) | Feb 07, 2020 |
| HP            | 15                          | [16b52341f5](https://linux-hardware.org/?probe=16b52341f5) | Feb 04, 2020 |
| Acer          | TravelMate 2490             | [a93e1d86a8](https://linux-hardware.org/?probe=a93e1d86a8) | Jan 27, 2020 |
| VERO          | K147                        | [9f10ca8308](https://linux-hardware.org/?probe=9f10ca8308) | Jan 26, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMH    | [3a02dced23](https://linux-hardware.org/?probe=3a02dced23) | Jan 14, 2020 |
| Lenovo        | ThinkPad L412 0585W28       | [8ba74bb2b0](https://linux-hardware.org/?probe=8ba74bb2b0) | Jan 13, 2020 |
| Sony          | VGN-FW21M                   | [cda530b21f](https://linux-hardware.org/?probe=cda530b21f) | Jan 12, 2020 |
| HP            | 650                         | [41d463f623](https://linux-hardware.org/?probe=41d463f623) | Jan 09, 2020 |
| Acer          | TravelMate 2490             | [b883b5c1af](https://linux-hardware.org/?probe=b883b5c1af) | Jan 09, 2020 |
| Acer          | TravelMate 2490             | [76920bc1b7](https://linux-hardware.org/?probe=76920bc1b7) | Jan 03, 2020 |
| Acer          | Aspire 5755G                | [99f3d96106](https://linux-hardware.org/?probe=99f3d96106) | Dec 31, 2019 |
| HP            | 255 G6 Notebook PC          | [4d572c7a12](https://linux-hardware.org/?probe=4d572c7a12) | Dec 31, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [1a90ac4588](https://linux-hardware.org/?probe=1a90ac4588) | Dec 26, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [966b8a2a9a](https://linux-hardware.org/?probe=966b8a2a9a) | Dec 23, 2019 |
| ASUSTek       | X551MA                      | [cc9b263062](https://linux-hardware.org/?probe=cc9b263062) | Dec 23, 2019 |
| HP            | EliteBook 8440p             | [d1c32bf428](https://linux-hardware.org/?probe=d1c32bf428) | Dec 21, 2019 |
| HP            | EliteBook 8460p             | [00c6afae23](https://linux-hardware.org/?probe=00c6afae23) | Dec 19, 2019 |
| Acer          | Aspire A315-31              | [702d379dd6](https://linux-hardware.org/?probe=702d379dd6) | Dec 17, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [6498ff99ee](https://linux-hardware.org/?probe=6498ff99ee) | Dec 15, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [b27320fd81](https://linux-hardware.org/?probe=b27320fd81) | Dec 15, 2019 |
| Insyde        | CherryTrail                 | [deeda709d2](https://linux-hardware.org/?probe=deeda709d2) | Dec 07, 2019 |
| Insyde        | CherryTrail                 | [81201a03c1](https://linux-hardware.org/?probe=81201a03c1) | Dec 07, 2019 |
| HP            | 650                         | [2a96c9ca75](https://linux-hardware.org/?probe=2a96c9ca75) | Dec 03, 2019 |
| HP            | 650                         | [4a1d85a63b](https://linux-hardware.org/?probe=4a1d85a63b) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4db92d49fe](https://linux-hardware.org/?probe=4db92d49fe) | Nov 30, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [495e998bda](https://linux-hardware.org/?probe=495e998bda) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | [d73b2ac7d1](https://linux-hardware.org/?probe=d73b2ac7d1) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | [5fd6ae6ef8](https://linux-hardware.org/?probe=5fd6ae6ef8) | Nov 28, 2019 |
| Lenovo        | IdeaPad S210 Touch 20257    | [bf342390e8](https://linux-hardware.org/?probe=bf342390e8) | Nov 24, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Dell          | Precision M3800             | [b133f93faa](https://linux-hardware.org/?probe=b133f93faa) | Nov 10, 2019 |
| Toshiba       | Satellite P755              | [673d423adc](https://linux-hardware.org/?probe=673d423adc) | Nov 10, 2019 |
| Toshiba       | Satellite L50D-B            | [eb4b70f853](https://linux-hardware.org/?probe=eb4b70f853) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | [3b759734b2](https://linux-hardware.org/?probe=3b759734b2) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | [fe505beff6](https://linux-hardware.org/?probe=fe505beff6) | Nov 03, 2019 |
| Pegatron      | A15                         | [291f1aae6d](https://linux-hardware.org/?probe=291f1aae6d) | Oct 29, 2019 |
| HP            | Pavilion Notebook           | [87a279150a](https://linux-hardware.org/?probe=87a279150a) | Oct 26, 2019 |
| HP            | 630                         | [99ab4364d4](https://linux-hardware.org/?probe=99ab4364d4) | Oct 26, 2019 |
| Acer          | AOD270                      | [fbe9c7eee3](https://linux-hardware.org/?probe=fbe9c7eee3) | Oct 25, 2019 |
| Acer          | AOD270                      | [cfabf3084a](https://linux-hardware.org/?probe=cfabf3084a) | Oct 25, 2019 |
| HP            | Presario CQ57               | [758c395c78](https://linux-hardware.org/?probe=758c395c78) | Oct 23, 2019 |
| Acer          | AOD270                      | [1ae1144336](https://linux-hardware.org/?probe=1ae1144336) | Oct 19, 2019 |
| Sony          | SVE1512C6EW                 | [cc73d5214f](https://linux-hardware.org/?probe=cc73d5214f) | Sep 23, 2019 |
| Lenovo        | N22 80S6                    | [5850aa007f](https://linux-hardware.org/?probe=5850aa007f) | Sep 09, 2019 |
| Toshiba       | Satellite S855D             | [b0e8c02a13](https://linux-hardware.org/?probe=b0e8c02a13) | Sep 07, 2019 |
| ASUSTek       | X541NA                      | [dad09e76f4](https://linux-hardware.org/?probe=dad09e76f4) | Sep 05, 2019 |
| HP            | Compaq Presario C700        | [f05eb74bea](https://linux-hardware.org/?probe=f05eb74bea) | Aug 31, 2019 |
| HP            | Pavilion 15                 | [2f3cb20593](https://linux-hardware.org/?probe=2f3cb20593) | Aug 30, 2019 |
| Lenovo        | G550 20023                  | [d6126ff072](https://linux-hardware.org/?probe=d6126ff072) | Aug 30, 2019 |
| HP            | Pavilion 15                 | [61616fc1bf](https://linux-hardware.org/?probe=61616fc1bf) | Aug 10, 2019 |
| HP            | Pavilion 15                 | [dc6c804e81](https://linux-hardware.org/?probe=dc6c804e81) | Jul 26, 2019 |
| HP            | Pavilion 15                 | [3652e8f3c6](https://linux-hardware.org/?probe=3652e8f3c6) | Jul 26, 2019 |
| Pegatron      | A15                         | [1b6dcb6a34](https://linux-hardware.org/?probe=1b6dcb6a34) | Jul 20, 2019 |
| Lenovo        | N22 80S6                    | [97f993a2ca](https://linux-hardware.org/?probe=97f993a2ca) | Jul 19, 2019 |
| Packard Be... | EasyNote MH35               | [eb538975bd](https://linux-hardware.org/?probe=eb538975bd) | Jul 13, 2019 |
| HP            | Pavilion zd8000 (EL033EA... | [91c7ae2180](https://linux-hardware.org/?probe=91c7ae2180) | Jul 12, 2019 |
| HP            | Compaq Presario CQ60        | [265a212fdc](https://linux-hardware.org/?probe=265a212fdc) | Jun 02, 2019 |
| Lenovo        | IdeaPad S210 Touch 20257    | [5834730131](https://linux-hardware.org/?probe=5834730131) | May 31, 2019 |
| HP            | Compaq Presario CQ60        | [4e935854b3](https://linux-hardware.org/?probe=4e935854b3) | May 26, 2019 |
| Lenovo        | V510-15IKB 80WQ             | [a8db92bb48](https://linux-hardware.org/?probe=a8db92bb48) | May 23, 2019 |
| MSI           | GE70 2PC                    | [347632684e](https://linux-hardware.org/?probe=347632684e) | May 10, 2019 |
| Dell          | Inspiron 3537               | [b57530d6a4](https://linux-hardware.org/?probe=b57530d6a4) | May 07, 2019 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [bf6bd6c60d](https://linux-hardware.org/?probe=bf6bd6c60d) | May 06, 2019 |
| Fujitsu Si... | AMILO Xi 2428               | [7f4acc9070](https://linux-hardware.org/?probe=7f4acc9070) | May 03, 2019 |
| Dell          | Inspiron 3521               | [5913b022e4](https://linux-hardware.org/?probe=5913b022e4) | May 01, 2019 |
| Toshiba       | Satellite S855D             | [b1213b7b31](https://linux-hardware.org/?probe=b1213b7b31) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 2768WR2       | [90cf61c66f](https://linux-hardware.org/?probe=90cf61c66f) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 2768WR2       | [820530546d](https://linux-hardware.org/?probe=820530546d) | Apr 28, 2019 |
| HP            | Pavilion g6                 | [50125f8815](https://linux-hardware.org/?probe=50125f8815) | Apr 25, 2019 |
| Dell          | Inspiron 5323               | [d25db8c5f1](https://linux-hardware.org/?probe=d25db8c5f1) | Apr 24, 2019 |
| Dell          | Inspiron 3543               | [b028e3e4f9](https://linux-hardware.org/?probe=b028e3e4f9) | Apr 18, 2019 |
| Intel         | Calistoga & ICH7M Chipse... | [146663e5c0](https://linux-hardware.org/?probe=146663e5c0) | Apr 17, 2019 |
| Info Quest... | GTN1408                     | [968a29d212](https://linux-hardware.org/?probe=968a29d212) | Apr 06, 2019 |
| HP            | Pavilion x2 Detachable      | [f91e0fbe6b](https://linux-hardware.org/?probe=f91e0fbe6b) | Apr 05, 2019 |
| HP            | Pavilion x2 Detachable      | [7dfc4ddd35](https://linux-hardware.org/?probe=7dfc4ddd35) | Apr 05, 2019 |
| Info Quest... | GTN1408                     | [bfc5bebd38](https://linux-hardware.org/?probe=bfc5bebd38) | Apr 05, 2019 |
| Info Quest... | GTN1408                     | [b0a5ef56cb](https://linux-hardware.org/?probe=b0a5ef56cb) | Apr 05, 2019 |
| ASUSTek       | X551MA                      | [4d7df702b8](https://linux-hardware.org/?probe=4d7df702b8) | Apr 05, 2019 |
| ASUSTek       | X551MA                      | [1b08ea07c0](https://linux-hardware.org/?probe=1b08ea07c0) | Apr 05, 2019 |
| Dell          | Inspiron 3576               | [132c5c22bb](https://linux-hardware.org/?probe=132c5c22bb) | Mar 24, 2019 |
| Dell          | Inspiron 3576               | [df5ad730b4](https://linux-hardware.org/?probe=df5ad730b4) | Mar 18, 2019 |
| Dell          | Inspiron 3576               | [a88f966e70](https://linux-hardware.org/?probe=a88f966e70) | Mar 18, 2019 |
| Toshiba       | Satellite C660D             | [884f236bc9](https://linux-hardware.org/?probe=884f236bc9) | Mar 14, 2019 |
| Toshiba       | Satellite C660D             | [ec10f22ef4](https://linux-hardware.org/?probe=ec10f22ef4) | Mar 12, 2019 |
| Sony          | VGN-SZ71XN_C                | [afbc222743](https://linux-hardware.org/?probe=afbc222743) | Mar 10, 2019 |
| Sony          | VGN-SZ71XN_C                | [75a71aa3ec](https://linux-hardware.org/?probe=75a71aa3ec) | Mar 10, 2019 |
| ASUSTek       | X555BA                      | [79a6f78b23](https://linux-hardware.org/?probe=79a6f78b23) | Mar 07, 2019 |
| Acer          | Aspire 5935                 | [454098b840](https://linux-hardware.org/?probe=454098b840) | Mar 04, 2019 |
| HP            | Pavilion dv5                | [cfd60bad2b](https://linux-hardware.org/?probe=cfd60bad2b) | Feb 23, 2019 |
| Dell          | Inspiron 3543               | [bf3ef7e629](https://linux-hardware.org/?probe=bf3ef7e629) | Feb 17, 2019 |
| Dell          | Inspiron 5555               | [65100107dc](https://linux-hardware.org/?probe=65100107dc) | Feb 16, 2019 |
| HP            | 15                          | [30a42ae5dc](https://linux-hardware.org/?probe=30a42ae5dc) | Feb 13, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | [5a68cab2c0](https://linux-hardware.org/?probe=5a68cab2c0) | Jan 24, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | [103dc16b24](https://linux-hardware.org/?probe=103dc16b24) | Jan 24, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | [e7121f92f8](https://linux-hardware.org/?probe=e7121f92f8) | Jan 20, 2019 |
| Lenovo        | ThinkPad T420 4236NGG       | [5b72be1d6f](https://linux-hardware.org/?probe=5b72be1d6f) | Jan 01, 2019 |
| Lenovo        | ThinkPad T420 4236NGG       | [ac9ae784ed](https://linux-hardware.org/?probe=ac9ae784ed) | Dec 30, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | [9947b5b177](https://linux-hardware.org/?probe=9947b5b177) | Dec 28, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | [3cc96f096e](https://linux-hardware.org/?probe=3cc96f096e) | Dec 28, 2018 |
| Dell          | Inspiron 3542               | [a630fe7049](https://linux-hardware.org/?probe=a630fe7049) | Dec 25, 2018 |
| Dell          | Inspiron 3542               | [cd0695d1aa](https://linux-hardware.org/?probe=cd0695d1aa) | Dec 25, 2018 |
| Dell          | Inspiron 3521               | [f56872fdba](https://linux-hardware.org/?probe=f56872fdba) | Dec 15, 2018 |
| Dell          | Inspiron 3521               | [a3e64442a6](https://linux-hardware.org/?probe=a3e64442a6) | Dec 15, 2018 |
| Acer          | Aspire A315-31              | [03420d4e05](https://linux-hardware.org/?probe=03420d4e05) | Dec 03, 2018 |
| Acer          | Aspire A315-31              | [5afd838dfc](https://linux-hardware.org/?probe=5afd838dfc) | Dec 03, 2018 |
| Sony          | VGN-AR41L                   | [e80a4c81ba](https://linux-hardware.org/?probe=e80a4c81ba) | Nov 17, 2018 |
| Sony          | VGN-AR41L                   | [33c85bd949](https://linux-hardware.org/?probe=33c85bd949) | Nov 17, 2018 |
| HP            | 630                         | [375f1ecc8e](https://linux-hardware.org/?probe=375f1ecc8e) | Nov 11, 2018 |
| Fujitsu       | LIFEBOOK S760               | [e5a9a2740a](https://linux-hardware.org/?probe=e5a9a2740a) | Nov 03, 2018 |
| Lenovo        | ThinkPad X201 3680BW9       | [b2ac9f5577](https://linux-hardware.org/?probe=b2ac9f5577) | Nov 03, 2018 |
| HP            | Notebook                    | [643f8c70bb](https://linux-hardware.org/?probe=643f8c70bb) | Oct 30, 2018 |
| Lenovo        | G700 20251                  | [25cef818bf](https://linux-hardware.org/?probe=25cef818bf) | Oct 22, 2018 |
| HP            | Notebook                    | [8be002c789](https://linux-hardware.org/?probe=8be002c789) | Oct 21, 2018 |
| HP            | EliteBook 820 G1            | [5ffb2eac69](https://linux-hardware.org/?probe=5ffb2eac69) | Jun 12, 2018 |
| Dell          | Latitude D530               | [37fd80baa9](https://linux-hardware.org/?probe=37fd80baa9) | May 18, 2018 |
| Dell          | Latitude D530               | [4a84b665e6](https://linux-hardware.org/?probe=4a84b665e6) | May 18, 2018 |
| Lenovo        | G510 20238                  | [f39685a972](https://linux-hardware.org/?probe=f39685a972) | Apr 22, 2018 |
| HP            | G62                         | [4fd190da5e](https://linux-hardware.org/?probe=4fd190da5e) | Apr 18, 2018 |
| Clevo         | W251ESQ/W270ESQ             | [a9eccff022](https://linux-hardware.org/?probe=a9eccff022) | Aug 01, 2017 |
| ASUSTek       | UX31E                       | [6be30c42a9](https://linux-hardware.org/?probe=6be30c42a9) | Jun 28, 2017 |
| Dell          | Inspiron 5558               | [ffc88e7749](https://linux-hardware.org/?probe=ffc88e7749) | Apr 23, 2017 |
| Toshiba       | TECRA R850                  | [6f44cbe917](https://linux-hardware.org/?probe=6f44cbe917) | Mar 14, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Greece/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 91        | 13.58%  |
| Ubuntu 18.04       | 62        | 9.25%   |
| Ubuntu 22.04       | 33        | 4.93%   |
| KDE neon 20.04     | 15        | 2.24%   |
| Debian 11          | 15        | 2.24%   |
| OpenMandriva 4.3   | 14        | 2.09%   |
| OpenMandriva 4.2   | 14        | 2.09%   |
| Linux Mint 19.3    | 14        | 2.09%   |
| Pop!_OS 22.04      | 12        | 1.79%   |
| Arch Rolling       | 12        | 1.79%   |
| Zorin 15           | 11        | 1.64%   |
| Zorin 16           | 10        | 1.49%   |
| Ubuntu 19.10       | 10        | 1.49%   |
| Debian 10          | 10        | 1.49%   |
| Xubuntu 20.04      | 9         | 1.34%   |
| Pop!_OS 20.04      | 9         | 1.34%   |
| Manjaro            | 9         | 1.34%   |
| Linux Mint 20.2    | 9         | 1.34%   |
| Linux Mint 20.1    | 9         | 1.34%   |
| Fedora 35          | 9         | 1.34%   |
| Xubuntu 18.04      | 8         | 1.19%   |
| Pop!_OS 21.04      | 8         | 1.19%   |
| Linux Mint 21      | 8         | 1.19%   |
| Arch               | 8         | 1.19%   |
| Pop!_OS 20.10      | 7         | 1.04%   |
| Linux Mint 20.3    | 7         | 1.04%   |
| Gentoo 2.7         | 7         | 1.04%   |
| Ubuntu 21.10       | 6         | 0.9%    |
| Ubuntu 21.04       | 6         | 0.9%    |
| Ubuntu 19.04       | 6         | 0.9%    |
| ROSA R10           | 6         | 0.9%    |
| OpenMandriva 23.01 | 6         | 0.9%    |
| Kubuntu 20.04      | 6         | 0.9%    |
| ArcoLinux Rolling  | 6         | 0.9%    |
| Ubuntu 20.10       | 5         | 0.75%   |
| Linux Mint 20      | 5         | 0.75%   |
| Fedora 33          | 5         | 0.75%   |
| Fedora 32          | 5         | 0.75%   |
| Ubuntu 18.10       | 4         | 0.6%    |
| Pop!_OS 21.10      | 4         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 213       | 33.7%   |
| Linux Mint    | 61        | 9.65%   |
| Pop!_OS       | 37        | 5.85%   |
| OpenMandriva  | 37        | 5.85%   |
| Fedora        | 31        | 4.91%   |
| Debian        | 29        | 4.59%   |
| Manjaro       | 23        | 3.64%   |
| Zorin         | 22        | 3.48%   |
| Xubuntu       | 19        | 3.01%   |
| Arch          | 19        | 3.01%   |
| KDE neon      | 16        | 2.53%   |
| Endless       | 14        | 2.22%   |
| ROSA          | 12        | 1.9%    |
| Kubuntu       | 11        | 1.74%   |
| Gentoo        | 10        | 1.58%   |
| ArcoLinux     | 8         | 1.27%   |
| Ubuntu MATE   | 7         | 1.11%   |
| LMDE          | 5         | 0.79%   |
| Ubuntu Unity  | 4         | 0.63%   |
| Ubuntu Budgie | 4         | 0.63%   |
| Elementary    | 4         | 0.63%   |
| ALT Linux     | 4         | 0.63%   |
| openSUSE      | 3         | 0.47%   |
| Lubuntu       | 3         | 0.47%   |
| LinuxFX       | 3         | 0.47%   |
| Kali          | 3         | 0.47%   |
| EndeavourOS   | 3         | 0.47%   |
| BlackPanther  | 3         | 0.47%   |
| Xero          | 2         | 0.32%   |
| SteamOS       | 2         | 0.32%   |
| Peppermint    | 2         | 0.32%   |
| MX            | 2         | 0.32%   |
| CentOS        | 2         | 0.32%   |
| Void Linux    | 1         | 0.16%   |
| Solus         | 1         | 0.16%   |
| Slackware     | 1         | 0.16%   |
| Parrot        | 1         | 0.16%   |
| Mageia        | 1         | 0.16%   |
| GNOME OS      | 1         | 0.16%   |
| GalliumOS     | 1         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-58-generic         | 14        | 1.93%   |
| 5.16.7-desktop-1omv4003  | 14        | 1.93%   |
| 5.4.0-42-generic         | 13        | 1.79%   |
| 5.15.0-52-generic        | 13        | 1.79%   |
| 5.10.14-desktop-1omv4002 | 13        | 1.79%   |
| 5.15.0-56-generic        | 11        | 1.52%   |
| 5.4.0-29-generic         | 8         | 1.1%    |
| 5.4.0-48-generic         | 7         | 0.97%   |
| 5.15.0-58-generic        | 7         | 0.97%   |
| 5.15.0-53-generic        | 7         | 0.97%   |
| 6.1.1-desktop-1omv2290   | 6         | 0.83%   |
| 5.4.0-65-generic         | 6         | 0.83%   |
| 5.3.0-46-generic         | 6         | 0.83%   |
| 5.15.0-41-generic        | 6         | 0.83%   |
| 5.11.0-38-generic        | 6         | 0.83%   |
| 5.8.0-55-generic         | 5         | 0.69%   |
| 5.4.0-37-generic         | 5         | 0.69%   |
| 5.3.0-45-generic         | 5         | 0.69%   |
| 5.3.0-42-generic         | 5         | 0.69%   |
| 5.15.0-46-generic        | 5         | 0.69%   |
| 5.13.0-39-generic        | 5         | 0.69%   |
| 5.11.0-7620-generic      | 5         | 0.69%   |
| 5.11.0-7614-generic      | 5         | 0.69%   |
| 5.0.0-37-generic         | 5         | 0.69%   |
| 4.15.0-47-generic        | 5         | 0.69%   |
| 5.8.0-7630-generic       | 4         | 0.55%   |
| 5.8.0-48-generic         | 4         | 0.55%   |
| 5.8.0-43-generic         | 4         | 0.55%   |
| 5.4.0-91-generic         | 4         | 0.55%   |
| 5.4.0-72-generic         | 4         | 0.55%   |
| 5.4.0-66-generic         | 4         | 0.55%   |
| 5.4.0-56-generic         | 4         | 0.55%   |
| 5.4.0-54-generic         | 4         | 0.55%   |
| 5.4.0-52-generic         | 4         | 0.55%   |
| 5.18.10-76051810-generic | 4         | 0.55%   |
| 5.15.0-48-generic        | 4         | 0.55%   |
| 5.13.0-30-generic        | 4         | 0.55%   |
| 5.11.0-40-generic        | 4         | 0.55%   |
| 5.11.0-37-generic        | 4         | 0.55%   |
| 5.11.0-35-generic        | 4         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 129       | 18.64%  |
| 5.15.0  | 63        | 9.1%    |
| 5.11.0  | 50        | 7.23%   |
| 4.15.0  | 43        | 6.21%   |
| 5.8.0   | 40        | 5.78%   |
| 5.3.0   | 37        | 5.35%   |
| 5.13.0  | 35        | 5.06%   |
| 5.0.0   | 21        | 3.03%   |
| 5.10.0  | 18        | 2.6%    |
| 5.16.7  | 14        | 2.02%   |
| 5.10.14 | 13        | 1.88%   |
| 4.18.0  | 13        | 1.88%   |
| 4.19.0  | 11        | 1.59%   |
| 6.1.1   | 8         | 1.16%   |
| 5.9.11  | 5         | 0.72%   |
| 5.19.0  | 5         | 0.72%   |
| 5.10.88 | 5         | 0.72%   |
| 5.18.10 | 4         | 0.58%   |
| 5.11.12 | 4         | 0.58%   |
| 4.9.20  | 4         | 0.58%   |
| 6.0.6   | 3         | 0.43%   |
| 5.8.18  | 3         | 0.43%   |
| 5.7.2   | 3         | 0.43%   |
| 5.3.18  | 3         | 0.43%   |
| 5.17.5  | 3         | 0.43%   |
| 5.15.5  | 3         | 0.43%   |
| 4.9.60  | 3         | 0.43%   |
| 6.1.8   | 2         | 0.29%   |
| 6.0.9   | 2         | 0.29%   |
| 6.0.15  | 2         | 0.29%   |
| 6.0.12  | 2         | 0.29%   |
| 6.0.0   | 2         | 0.29%   |
| 5.9.16  | 2         | 0.29%   |
| 5.8.6   | 2         | 0.29%   |
| 5.8.16  | 2         | 0.29%   |
| 5.5.13  | 2         | 0.29%   |
| 5.4.77  | 2         | 0.29%   |
| 5.17.1  | 2         | 0.29%   |
| 5.15.32 | 2         | 0.29%   |
| 5.15.19 | 2         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 140       | 20.38%  |
| 5.15    | 80        | 11.64%  |
| 5.11    | 61        | 8.88%   |
| 5.8     | 54        | 7.86%   |
| 5.10    | 50        | 7.28%   |
| 5.3     | 43        | 6.26%   |
| 4.15    | 43        | 6.26%   |
| 5.13    | 40        | 5.82%   |
| 5.0     | 22        | 3.2%    |
| 5.16    | 20        | 2.91%   |
| 4.18    | 14        | 2.04%   |
| 6.0     | 12        | 1.75%   |
| 5.9     | 12        | 1.75%   |
| 6.1     | 11        | 1.6%    |
| 4.19    | 11        | 1.6%    |
| 5.19    | 9         | 1.31%   |
| 4.9     | 9         | 1.31%   |
| 5.18    | 8         | 1.16%   |
| 5.17    | 8         | 1.16%   |
| 5.14    | 8         | 1.16%   |
| 5.12    | 7         | 1.02%   |
| 5.7     | 6         | 0.87%   |
| 5.6     | 6         | 0.87%   |
| 5.5     | 5         | 0.73%   |
| 4.1     | 2         | 0.29%   |
| 5.2     | 1         | 0.15%   |
| 4.20    | 1         | 0.15%   |
| 4.16    | 1         | 0.15%   |
| 4.10    | 1         | 0.15%   |
| 3.16    | 1         | 0.15%   |
| 3.10    | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 574       | 93.79%  |
| i686   | 38        | 6.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| GNOME               | 285       | 44.32%  |
| KDE5                | 95        | 14.77%  |
| Unknown             | 76        | 11.82%  |
| XFCE                | 58        | 9.02%   |
| X-Cinnamon          | 50        | 7.78%   |
| MATE                | 22        | 3.42%   |
| KDE                 | 19        | 2.95%   |
| KDE4                | 6         | 0.93%   |
| Budgie              | 5         | 0.78%   |
| Unity               | 4         | 0.62%   |
| Pantheon            | 4         | 0.62%   |
| LXQt                | 4         | 0.62%   |
| LXDE                | 3         | 0.47%   |
| Cinnamon            | 3         | 0.47%   |
| i3                  | 2         | 0.31%   |
| GNOME Classic       | 2         | 0.31%   |
| openbox             | 1         | 0.16%   |
| ICEWM               | 1         | 0.16%   |
| Deepin              | 1         | 0.16%   |
| awesome             | 1         | 0.16%   |
| /usr/bin/startxfce4 | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 501       | 79.15%  |
| Wayland | 77        | 12.16%  |
| Unknown | 41        | 6.48%   |
| Tty     | 14        | 2.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 359       | 56.45%  |
| SDDM    | 78        | 12.26%  |
| GDM     | 62        | 9.75%   |
| LightDM | 57        | 8.96%   |
| GDM3    | 54        | 8.49%   |
| TDM     | 16        | 2.52%   |
| KDM     | 6         | 0.94%   |
| XDM     | 2         | 0.31%   |
| SLiM    | 1         | 0.16%   |
| Ly      | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 359       | 57.17%  |
| el_GR   | 159       | 25.32%  |
| Unknown | 72        | 11.46%  |
| en_GB   | 14        | 2.23%   |
| de_DE   | 6         | 0.96%   |
| C       | 6         | 0.96%   |
| POSIX   | 2         | 0.32%   |
| fr_FR   | 2         | 0.32%   |
| ru_RU   | 1         | 0.16%   |
| pl_PL   | 1         | 0.16%   |
| it_IT   | 1         | 0.16%   |
| hu_HU   | 1         | 0.16%   |
| en_IE   | 1         | 0.16%   |
| en_AG   | 1         | 0.16%   |
| C.UTF8  | 1         | 0.16%   |
| anp_IN  | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 340       | 54.31%  |
| EFI  | 286       | 45.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 495       | 79.07%  |
| Btrfs   | 50        | 7.99%   |
| Overlay | 46        | 7.35%   |
| Unknown | 28        | 4.47%   |
| Zfs     | 5         | 0.8%    |
| Tmpfs   | 1         | 0.16%   |
| F2fs    | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 389       | 61.65%  |
| GPT     | 165       | 26.15%  |
| MBR     | 77        | 12.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 537       | 86.2%   |
| Yes       | 86        | 13.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 447       | 72.45%  |
| Yes       | 170       | 27.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 139       | 22.71%  |
| Lenovo                  | 125       | 20.42%  |
| Dell                    | 96        | 15.69%  |
| ASUSTek Computer        | 46        | 7.52%   |
| Acer                    | 46        | 7.52%   |
| Toshiba                 | 28        | 4.58%   |
| Sony                    | 28        | 4.58%   |
| Fujitsu Siemens         | 10        | 1.63%   |
| Fujitsu                 | 10        | 1.63%   |
| Apple                   | 9         | 1.47%   |
| MSI                     | 7         | 1.14%   |
| HUAWEI                  | 7         | 1.14%   |
| Notebook                | 6         | 0.98%   |
| Clevo                   | 6         | 0.98%   |
| Unknown                 | 6         | 0.98%   |
| Samsung Electronics     | 4         | 0.65%   |
| Teclast                 | 3         | 0.49%   |
| Pegatron                | 3         | 0.49%   |
| Insyde                  | 3         | 0.49%   |
| Valve                   | 2         | 0.33%   |
| Intel                   | 2         | 0.33%   |
| Info Quest Technologies | 2         | 0.33%   |
| IBM                     | 2         | 0.33%   |
| Hampoo                  | 2         | 0.33%   |
| E-shop.gr               | 2         | 0.33%   |
| Chuwi                   | 2         | 0.33%   |
| VERO                    | 1         | 0.16%   |
| TUXEDO                  | 1         | 0.16%   |
| Timi                    | 1         | 0.16%   |
| Schenker                | 1         | 0.16%   |
| Quest                   | 1         | 0.16%   |
| Purism                  | 1         | 0.16%   |
| PLAISIO COMPUTERS SA    | 1         | 0.16%   |
| Plaisio                 | 1         | 0.16%   |
| PC Specialist           | 1         | 0.16%   |
| Packard Bell            | 1         | 0.16%   |
| Medion                  | 1         | 0.16%   |
| Google                  | 1         | 0.16%   |
| Dynabook                | 1         | 0.16%   |
| Compal                  | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 11        | 1.8%    |
| HP Pavilion g6                         | 9         | 1.47%   |
| HP Notebook                            | 7         | 1.14%   |
| HP 255 G7 Notebook PC                  | 5         | 0.82%   |
| Dell Inspiron 3542                     | 5         | 0.82%   |
| Dell Inspiron 3537                     | 5         | 0.82%   |
| Lenovo G510 20238                      | 4         | 0.65%   |
| HP G62                                 | 4         | 0.65%   |
| Dell Inspiron 5567                     | 4         | 0.65%   |
| Notebook W54_W94_W955TU,-T,-C          | 3         | 0.49%   |
| Lenovo IdeaPad 100-15IBD 80QQ          | 3         | 0.49%   |
| Lenovo G50-70 20351                    | 3         | 0.49%   |
| Lenovo G40-30 80FY                     | 3         | 0.49%   |
| Insyde CherryTrail                     | 3         | 0.49%   |
| HUAWEI KLVL-WXX9                       | 3         | 0.49%   |
| HP Pavilion dv7                        | 3         | 0.49%   |
| HP 255 G8 Notebook PC                  | 3         | 0.49%   |
| Dell Inspiron 5559                     | 3         | 0.49%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA | 3         | 0.49%   |
| Apple MacBookPro8,1                    | 3         | 0.49%   |
| Acer Aspire A315-51                    | 3         | 0.49%   |
| Acer Aspire A315-31                    | 3         | 0.49%   |
| Acer Aspire 5738                       | 3         | 0.49%   |
| Valve Jupiter                          | 2         | 0.33%   |
| Toshiba Satellite C850D-119            | 2         | 0.33%   |
| Toshiba Satellite C850D-118            | 2         | 0.33%   |
| Toshiba NB100                          | 2         | 0.33%   |
| Teclast F15                            | 2         | 0.33%   |
| Sony VPCM13M1E                         | 2         | 0.33%   |
| Sony VPCCB2S1E                         | 2         | 0.33%   |
| Pegatron A15                           | 2         | 0.33%   |
| Lenovo Legion Y530-15ICH 81FV          | 2         | 0.33%   |
| Lenovo IdeaPad S540-14API 81NH         | 2         | 0.33%   |
| Lenovo IdeaPad L340-17API 81LY         | 2         | 0.33%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK  | 2         | 0.33%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 2         | 0.33%   |
| Lenovo G700 20251                      | 2         | 0.33%   |
| Lenovo G70-35 80Q5                     | 2         | 0.33%   |
| Lenovo G50-80 80L0                     | 2         | 0.33%   |
| Lenovo G50-30 80G0                     | 2         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 42        | 6.86%   |
| Dell Inspiron         | 42        | 6.86%   |
| Lenovo ThinkPad       | 37        | 6.05%   |
| HP Pavilion           | 37        | 6.05%   |
| Acer Aspire           | 37        | 6.05%   |
| Dell Latitude         | 29        | 4.74%   |
| Toshiba Satellite     | 24        | 3.92%   |
| HP EliteBook          | 13        | 2.12%   |
| HP Compaq             | 13        | 2.12%   |
| HP 255                | 13        | 2.12%   |
| ASUS VivoBook         | 12        | 1.96%   |
| HP Laptop             | 11        | 1.8%    |
| Unknown               | 11        | 1.8%    |
| HP ProBook            | 9         | 1.47%   |
| Fujitsu LIFEBOOK      | 8         | 1.31%   |
| HP Notebook           | 7         | 1.14%   |
| Fujitsu Siemens AMILO | 7         | 1.14%   |
| Dell Precision        | 7         | 1.14%   |
| Dell Vostro           | 6         | 0.98%   |
| HP 250                | 5         | 0.82%   |
| Dell XPS              | 5         | 0.82%   |
| ASUS TUF              | 5         | 0.82%   |
| Lenovo Legion         | 4         | 0.65%   |
| Lenovo G510           | 4         | 0.65%   |
| HP G62                | 4         | 0.65%   |
| Apple MacBookPro8     | 4         | 0.65%   |
| Notebook W54          | 3         | 0.49%   |
| Lenovo ThinkBook      | 3         | 0.49%   |
| Lenovo G50-70         | 3         | 0.49%   |
| Lenovo G40-30         | 3         | 0.49%   |
| Insyde CherryTrail    | 3         | 0.49%   |
| HUAWEI KLVL-WXX9      | 3         | 0.49%   |
| HP Presario           | 3         | 0.49%   |
| HP ENVY               | 3         | 0.49%   |
| Valve Jupiter         | 2         | 0.33%   |
| Toshiba NB100         | 2         | 0.33%   |
| Teclast F15           | 2         | 0.33%   |
| Sony VPCM13M1E        | 2         | 0.33%   |
| Sony VPCCB2S1E        | 2         | 0.33%   |
| Pegatron A15          | 2         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 58        | 9.48%   |
| 2013 | 50        | 8.17%   |
| 2020 | 47        | 7.68%   |
| 2011 | 47        | 7.68%   |
| 2012 | 45        | 7.35%   |
| 2017 | 43        | 7.03%   |
| 2018 | 40        | 6.54%   |
| 2008 | 40        | 6.54%   |
| 2014 | 37        | 6.05%   |
| 2015 | 36        | 5.88%   |
| 2009 | 35        | 5.72%   |
| 2010 | 32        | 5.23%   |
| 2016 | 28        | 4.58%   |
| 2007 | 26        | 4.25%   |
| 2021 | 23        | 3.76%   |
| 2022 | 8         | 1.31%   |
| 2006 | 8         | 1.31%   |
| 2005 | 7         | 1.14%   |
| 2004 | 2         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 612       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 547       | 88.65%  |
| Enabled  | 70        | 11.35%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 610       | 99.67%  |
| Yes  | 2         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 178       | 28.8%   |
| 4.01-8.0    | 167       | 27.02%  |
| 8.01-16.0   | 98        | 15.86%  |
| 16.01-24.0  | 64        | 10.36%  |
| 1.01-2.0    | 61        | 9.87%   |
| 2.01-3.0    | 20        | 3.24%   |
| 32.01-64.0  | 15        | 2.43%   |
| 0.51-1.0    | 12        | 1.94%   |
| 24.01-32.0  | 2         | 0.32%   |
| 64.01-256.0 | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 281       | 41.88%  |
| 2.01-3.0   | 162       | 24.14%  |
| 4.01-8.0   | 71        | 10.58%  |
| 3.01-4.0   | 69        | 10.28%  |
| 0.51-1.0   | 67        | 9.99%   |
| 8.01-16.0  | 10        | 1.49%   |
| 0.01-0.5   | 9         | 1.34%   |
| 24.01-32.0 | 1         | 0.15%   |
| 16.01-24.0 | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 461       | 73.52%  |
| 2      | 144       | 22.97%  |
| 3      | 14        | 2.23%   |
| 0      | 6         | 0.96%   |
| 6      | 1         | 0.16%   |
| 4      | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 340       | 55.37%  |
| Yes       | 274       | 44.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 516       | 84.04%  |
| No        | 98        | 15.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 604       | 98.53%  |
| No        | 9         | 1.47%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 461       | 74.35%  |
| No        | 159       | 25.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Greece  | 612       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Athens       | 315       | 48.17%  |
| Thessaloniki | 99        | 15.14%  |
| Heraklion    | 22        | 3.36%   |
| Pátrai      | 14        | 2.14%   |
| Chalcis      | 13        | 1.99%   |
| Volos        | 10        | 1.53%   |
| Kavala       | 9         | 1.38%   |
| Katerini     | 8         | 1.22%   |
| Trikala      | 7         | 1.07%   |
| Piraeus      | 7         | 1.07%   |
| Rhodes       | 5         | 0.76%   |
| Ioannina     | 5         | 0.76%   |
| Corfu        | 5         | 0.76%   |
| Serres       | 4         | 0.61%   |
| Larissa      | 4         | 0.61%   |
| Kallithea    | 4         | 0.61%   |
| Kalamata     | 4         | 0.61%   |
| Fira         | 4         | 0.61%   |
| Corinth      | 4         | 0.61%   |
| Chania       | 4         | 0.61%   |
| Chalandri    | 4         | 0.61%   |
| Agrinio      | 4         | 0.61%   |
| Lamia        | 3         | 0.46%   |
| Koropi       | 3         | 0.46%   |
| Kilkis       | 3         | 0.46%   |
| Drama        | 3         | 0.46%   |
| Ano Liosia   | 3         | 0.46%   |
| Xanthi       | 2         | 0.31%   |
| Veroia       | 2         | 0.31%   |
| Salamina     | 2         | 0.31%   |
| Rethymno     | 2         | 0.31%   |
| Poros        | 2         | 0.31%   |
| Paros        | 2         | 0.31%   |
| Melissia     | 2         | 0.31%   |
| Marousi      | 2         | 0.31%   |
| Lefkada      | 2         | 0.31%   |
| Komotini     | 2         | 0.31%   |
| Karditsa     | 2         | 0.31%   |
| Grevena      | 2         | 0.31%   |
| Elateia      | 2         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 97        | 120    | 12.81%  |
| WDC                            | 94        | 125    | 12.42%  |
| Seagate                        | 83        | 103    | 10.96%  |
| Toshiba                        | 68        | 83     | 8.98%   |
| SanDisk                        | 53        | 65     | 7%      |
| Kingston                       | 52        | 65     | 6.87%   |
| Unknown                        | 40        | 60     | 5.28%   |
| SK hynix                       | 31        | 42     | 4.1%    |
| Patriot                        | 29        | 31     | 3.83%   |
| Hitachi                        | 26        | 26     | 3.43%   |
| HGST                           | 20        | 23     | 2.64%   |
| Micron Technology              | 17        | 20     | 2.25%   |
| Intenso                        | 17        | 20     | 2.25%   |
| Crucial                        | 17        | 18     | 2.25%   |
| Fujitsu                        | 16        | 17     | 2.11%   |
| Intel                          | 15        | 19     | 1.98%   |
| Team                           | 7         | 12     | 0.92%   |
| KIOXIA                         | 6         | 6      | 0.79%   |
| JMicron Technology             | 6         | 6      | 0.79%   |
| OCZ                            | 5         | 5      | 0.66%   |
| Micron/Crucial Technology      | 4         | 5      | 0.53%   |
| Transcend                      | 3         | 3      | 0.4%    |
| Teclast                        | 3         | 3      | 0.4%    |
| Gigabyte Technology            | 3         | 3      | 0.4%    |
| SPCC                           | 2         | 3      | 0.26%   |
| PNY                            | 2         | 2      | 0.26%   |
| Phison                         | 2         | 2      | 0.26%   |
| O2 Micro                       | 2         | 2      | 0.26%   |
| Mushkin                        | 2         | 2      | 0.26%   |
| LITEON                         | 2         | 2      | 0.26%   |
| Apple                          | 2         | 2      | 0.26%   |
| Apacer                         | 2         | 2      | 0.26%   |
| A-DATA Technology              | 2         | 2      | 0.26%   |
| Unknown                        | 2         | 2      | 0.26%   |
| XPG                            | 1         | 1      | 0.13%   |
| WDC WDS                        | 1         | 1      | 0.13%   |
| Verbatim                       | 1         | 1      | 0.13%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.13%   |
| SSSTC                          | 1         | 1      | 0.13%   |
| Solid State Storage Technology | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 16        | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 1.91%   |
| SK hynix NVMe SSD Drive 256GB       | 11        | 1.4%    |
| Samsung SSD 860 EVO 500GB           | 11        | 1.4%    |
| Unknown MMC Card  64GB              | 9         | 1.15%   |
| Toshiba MQ01ABF050 500GB            | 9         | 1.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 9         | 1.15%   |
| Patriot Burst 120GB SSD             | 9         | 1.15%   |
| Kingston SA400S37240G 240GB SSD     | 9         | 1.15%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 1.02%   |
| SanDisk NVMe SSD Drive 256GB        | 8         | 1.02%   |
| Samsung SSD 860 EVO 250GB           | 8         | 1.02%   |
| Unknown MMC Card  128GB             | 7         | 0.89%   |
| Toshiba MQ01ABD100 1TB              | 7         | 0.89%   |
| HGST HTS545050A7E680 500GB          | 7         | 0.89%   |
| Kingston SA400S37120G 120GB SSD     | 6         | 0.76%   |
| HGST HTS721010A9E630 1TB            | 6         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 5         | 0.64%   |
| Toshiba MQ04ABF100 1TB              | 5         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB        | 5         | 0.64%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.64%   |
| Samsung SSD 850 EVO 250GB           | 5         | 0.64%   |
| Kingston SA400S37480G 480GB SSD     | 5         | 0.64%   |
| Intenso External USB 3.0 4TB        | 5         | 0.64%   |
| Fujitsu MHY2200BH 200GB             | 5         | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 4         | 0.51%   |
| WDC WD10SPZX-60Z10T0 1TB            | 4         | 0.51%   |
| Unknown MMC Card  2GB               | 4         | 0.51%   |
| Toshiba MQ01ABD050 500GB            | 4         | 0.51%   |
| Samsung NVMe SSD Drive 512GB        | 4         | 0.51%   |
| Patriot Burst 480GB SSD             | 4         | 0.51%   |
| Patriot Burst 240GB SSD             | 4         | 0.51%   |
| JMicron Generic 200GB               | 4         | 0.51%   |
| Hitachi HTS545032B9A300 320GB       | 4         | 0.51%   |
| WDC WD10JPVX-75JC3T0 1TB            | 3         | 0.38%   |
| Unknown MMC Card  16GB              | 3         | 0.38%   |
| Seagate ST9500420AS 500GB           | 3         | 0.38%   |
| Seagate ST1000LM048-2E7172 1TB      | 3         | 0.38%   |
| SanDisk SDSSDA120G 120GB            | 3         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 100    | 28.93%  |
| WDC                 | 67        | 86     | 23.93%  |
| Toshiba             | 48        | 61     | 17.14%  |
| Hitachi             | 26        | 26     | 9.29%   |
| HGST                | 20        | 23     | 7.14%   |
| Fujitsu             | 16        | 17     | 5.71%   |
| Samsung Electronics | 9         | 10     | 3.21%   |
| Intenso             | 5         | 6      | 1.79%   |
| JMicron Technology  | 4         | 4      | 1.43%   |
| Unknown             | 1         | 1      | 0.36%   |
| IBM/Hitachi         | 1         | 1      | 0.36%   |
| ASMT109x            | 1         | 1      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 56        | 64     | 20.07%  |
| Kingston            | 42        | 53     | 15.05%  |
| SanDisk             | 31        | 38     | 11.11%  |
| Patriot             | 29        | 31     | 10.39%  |
| WDC                 | 17        | 26     | 6.09%   |
| Crucial             | 15        | 16     | 5.38%   |
| Toshiba             | 11        | 12     | 3.94%   |
| Intenso             | 11        | 13     | 3.94%   |
| Micron Technology   | 10        | 11     | 3.58%   |
| Team                | 7         | 12     | 2.51%   |
| Intel               | 6         | 8      | 2.15%   |
| OCZ                 | 5         | 5      | 1.79%   |
| SK hynix            | 4         | 4      | 1.43%   |
| Transcend           | 3         | 3      | 1.08%   |
| Teclast             | 3         | 3      | 1.08%   |
| Gigabyte Technology | 3         | 3      | 1.08%   |
| SPCC                | 2         | 3      | 0.72%   |
| PNY                 | 2         | 2      | 0.72%   |
| Mushkin             | 2         | 2      | 0.72%   |
| Apacer              | 2         | 2      | 0.72%   |
| A-DATA Technology   | 2         | 2      | 0.72%   |
| WDC WDS             | 1         | 1      | 0.36%   |
| Verbatim            | 1         | 1      | 0.36%   |
| Plextor             | 1         | 1      | 0.36%   |
| OCZ-AGIL            | 1         | 1      | 0.36%   |
| Netac               | 1         | 1      | 0.36%   |
| LITEON              | 1         | 1      | 0.36%   |
| Leven               | 1         | 1      | 0.36%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.36%   |
| KingSpec            | 1         | 1      | 0.36%   |
| Hewlett-Packard     | 1         | 1      | 0.36%   |
| Emtec               | 1         | 2      | 0.36%   |
| Drevo               | 1         | 1      | 0.36%   |
| China               | 1         | 1      | 0.36%   |
| ASUS-PHISON         | 1         | 2      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 273       | 337    | 37.5%   |
| SSD     | 265       | 331    | 36.4%   |
| NVMe    | 141       | 188    | 19.37%  |
| MMC     | 42        | 67     | 5.77%   |
| Unknown | 7         | 10     | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 474       | 642    | 69.4%   |
| NVMe | 141       | 188    | 20.64%  |
| MMC  | 42        | 67     | 6.15%   |
| SAS  | 26        | 36     | 3.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 405       | 522    | 77.44%  |
| 0.51-1.0   | 105       | 129    | 20.08%  |
| 1.01-2.0   | 7         | 10     | 1.34%   |
| 3.01-4.0   | 5         | 6      | 0.96%   |
| 4.01-10.0  | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 220       | 34%     |
| 251-500        | 142       | 21.95%  |
| 501-1000       | 73        | 11.28%  |
| 51-100         | 62        | 9.58%   |
| 1-20           | 51        | 7.88%   |
| 21-50          | 39        | 6.03%   |
| 1001-2000      | 33        | 5.1%    |
| Unknown        | 13        | 2.01%   |
| More than 3000 | 7         | 1.08%   |
| 2001-3000      | 7         | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 278       | 41.99%  |
| 21-50          | 122       | 18.43%  |
| 51-100         | 88        | 13.29%  |
| 101-250        | 74        | 11.18%  |
| 251-500        | 45        | 6.8%    |
| 501-1000       | 24        | 3.63%   |
| 1001-2000      | 15        | 2.27%   |
| Unknown        | 13        | 1.96%   |
| More than 3000 | 3         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                          | 4         | 4      | 10.53%  |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1         | 1      | 2.63%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 1      | 2.63%   |
| WDC WD5000BPVT-60HXZT1 500GB                        | 1         | 1      | 2.63%   |
| WDC WD3200BEVT-26ZCT0 320GB                         | 1         | 1      | 2.63%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 2.63%   |
| WDC WD1600BEVS-22RST0 160GB                         | 1         | 1      | 2.63%   |
| Toshiba MQ02ABF050H 500GB                           | 1         | 1      | 2.63%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD100M 1TB                             | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 3      | 2.63%   |
| SK hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 2.63%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 1         | 1      | 2.63%   |
| Seagate ST980811AS 80GB                             | 1         | 1      | 2.63%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.63%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.63%   |
| Seagate ST9160310AS 160GB                           | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.63%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 2.63%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 3      | 2.63%   |
| SanDisk SSD U100 128GB                              | 1         | 1      | 2.63%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 970 EVO 500GB               | 1         | 1      | 2.63%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB        | 1         | 1      | 2.63%   |
| OCZ-AGIL ITY3 64GB SSD                              | 1         | 1      | 2.63%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 2.63%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.63%   |
| Kingston RBUSNS8180DS3128GJ 128GB SSD               | 1         | 1      | 2.63%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.63%   |
| Hitachi HTS723216L9A360 160GB                       | 1         | 1      | 2.63%   |
| Hitachi HTS545032B9A300 320GB                       | 1         | 1      | 2.63%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 2.63%   |
| Fujitsu MHT2080BH 80GB                              | 1         | 1      | 2.63%   |
| Crucial CT480M500SSD1 480GB                         | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 21.05%  |
| WDC                 | 6         | 6      | 15.79%  |
| Toshiba             | 4         | 6      | 10.53%  |
| Hitachi             | 4         | 4      | 10.53%  |
| HGST                | 4         | 4      | 10.53%  |
| SK hynix            | 2         | 2      | 5.26%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Samsung Electronics | 2         | 2      | 5.26%   |
| Micron Technology   | 2         | 2      | 5.26%   |
| OCZ-AGIL            | 1         | 1      | 2.63%   |
| Kingston            | 1         | 1      | 2.63%   |
| Fujitsu             | 1         | 1      | 2.63%   |
| Crucial             | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 10     | 30.77%  |
| WDC     | 5         | 5      | 19.23%  |
| Toshiba | 4         | 6      | 15.38%  |
| Hitachi | 4         | 4      | 15.38%  |
| HGST    | 4         | 4      | 15.38%  |
| Fujitsu | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 30     | 68.42%  |
| SSD  | 9         | 9      | 23.68%  |
| NVMe | 3         | 3      | 7.89%   |

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
| Detected | 423       | 633    | 65.48%  |
| Works    | 185       | 258    | 28.64%  |
| Malfunc  | 38        | 42     | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 434       | 63.82%  |
| AMD                              | 93        | 13.68%  |
| Samsung Electronics              | 35        | 5.15%   |
| SK hynix                         | 26        | 3.82%   |
| SanDisk                          | 26        | 3.82%   |
| Kingston Technology Company      | 11        | 1.62%   |
| Toshiba America Info Systems     | 9         | 1.32%   |
| Micron Technology                | 7         | 1.03%   |
| KIOXIA                           | 7         | 1.03%   |
| Nvidia                           | 5         | 0.74%   |
| Micron/Crucial Technology        | 5         | 0.74%   |
| VIA Technologies                 | 3         | 0.44%   |
| Phison Electronics               | 3         | 0.44%   |
| Union Memory (Shenzhen)          | 2         | 0.29%   |
| Silicon Integrated Systems [SiS] | 2         | 0.29%   |
| Silicon Image                    | 2         | 0.29%   |
| O2 Micro                         | 2         | 0.29%   |
| JMicron Technology               | 2         | 0.29%   |
| ADATA Technology                 | 2         | 0.29%   |
| Solid State Storage Technology   | 1         | 0.15%   |
| Seagate Technology               | 1         | 0.15%   |
| Lite-On Technology               | 1         | 0.15%   |
| ASMedia Technology               | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 78        | 10.36%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 43        | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 40        | 5.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 38        | 5.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 34        | 4.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 28        | 3.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 24        | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23        | 3.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 22        | 2.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 2.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 2.26%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 16        | 2.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 16        | 2.12%   |
| Samsung NVMe SSD Controller 980                                                  | 13        | 1.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 1.73%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 1.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 12        | 1.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 12        | 1.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 10        | 1.33%   |
| Intel Tiger Lake-LP SATA Controller                                              | 9         | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 8         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 1.06%   |
| SK hynix BC511                                                                   | 7         | 0.93%   |
| Micron Non-Volatile memory controller                                            | 7         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 7         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 0.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 0.8%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 0.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 6         | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.8%    |
| SK hynix Non-Volatile memory controller                                          | 5         | 0.66%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 5         | 0.66%   |
| SanDisk PC SN520 NVMe SSD                                                        | 5         | 0.66%   |
| Intel SSD 660P Series                                                            | 5         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 455       | 62.85%  |
| NVMe | 144       | 19.89%  |
| IDE  | 86        | 11.88%  |
| RAID | 39        | 5.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 480       | 78.43%  |
| AMD          | 131       | 21.41%  |
| CentaurHauls | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 2.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 12        | 1.96%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 1.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 1.31%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 1.14%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 7         | 1.14%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 1.14%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 7         | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.98%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 6         | 0.98%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 6         | 0.98%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 0.98%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 6         | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 0.98%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.98%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.98%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 5         | 0.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.82%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 5         | 0.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.82%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.82%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 5         | 0.82%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 5         | 0.82%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.65%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 4         | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.65%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.65%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.65%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 4         | 0.65%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 4         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 119       | 19.44%  |
| Intel Core i7                  | 95        | 15.52%  |
| Intel Core i3                  | 54        | 8.82%   |
| Intel Core 2 Duo               | 53        | 8.66%   |
| Intel Celeron                  | 43        | 7.03%   |
| AMD Ryzen 5                    | 31        | 5.07%   |
| Other                          | 29        | 4.74%   |
| Intel Atom                     | 29        | 4.74%   |
| Intel Pentium                  | 21        | 3.43%   |
| AMD Ryzen 7                    | 18        | 2.94%   |
| AMD Ryzen 3                    | 13        | 2.12%   |
| AMD E1                         | 9         | 1.47%   |
| AMD A4                         | 9         | 1.47%   |
| AMD A6                         | 8         | 1.31%   |
| Intel Pentium Dual-Core        | 7         | 1.14%   |
| Intel Core 2                   | 7         | 1.14%   |
| AMD A10                        | 7         | 1.14%   |
| Intel Pentium Dual             | 6         | 0.98%   |
| Intel Pentium M                | 5         | 0.82%   |
| Intel Genuine                  | 5         | 0.82%   |
| Intel Celeron M                | 5         | 0.82%   |
| AMD A8                         | 5         | 0.82%   |
| Intel Celeron Dual-Core        | 4         | 0.65%   |
| AMD Ryzen 7 PRO                | 3         | 0.49%   |
| AMD E                          | 3         | 0.49%   |
| AMD Athlon                     | 3         | 0.49%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.33%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.33%   |
| AMD Turion                     | 2         | 0.33%   |
| AMD Sempron                    | 2         | 0.33%   |
| AMD E2                         | 2         | 0.33%   |
| AMD Athlon 64 X2               | 2         | 0.33%   |
| Intel Pentium 4                | 1         | 0.16%   |
| Intel Core m3                  | 1         | 0.16%   |
| Intel Core Duo                 | 1         | 0.16%   |
| Intel Core 2 Extreme           | 1         | 0.16%   |
| CentaurHauls VIA C7            | 1         | 0.16%   |
| AMD V140                       | 1         | 0.16%   |
| AMD Turion 64 Mobile           | 1         | 0.16%   |
| AMD Ryzen 5 PRO                | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 359       | 58.66%  |
| 4      | 174       | 28.43%  |
| 1      | 34        | 5.56%   |
| 6      | 28        | 4.58%   |
| 8      | 15        | 2.45%   |
| 14     | 1         | 0.16%   |
| 12     | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 612       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 372       | 60.78%  |
| 1      | 239       | 39.05%  |
| 8      | 1         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 577       | 93.82%  |
| 32-bit         | 26        | 4.23%   |
| Unknown        | 12        | 1.95%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 130       | 20.41%  |
| 0x206a7    | 44        | 6.91%   |
| 0x306a9    | 29        | 4.55%   |
| 0x40651    | 26        | 4.08%   |
| 0x1067a    | 24        | 3.77%   |
| 0x806ea    | 20        | 3.14%   |
| 0x306c3    | 18        | 2.83%   |
| 0x30678    | 17        | 2.67%   |
| 0x6fd      | 16        | 2.51%   |
| 0x08108102 | 15        | 2.35%   |
| 0x806e9    | 14        | 2.2%    |
| 0x10676    | 14        | 2.2%    |
| 0x806c1    | 13        | 2.04%   |
| 0x08108109 | 13        | 2.04%   |
| 0x906ea    | 12        | 1.88%   |
| 0x306d4    | 12        | 1.88%   |
| 0x506c9    | 10        | 1.57%   |
| 0x406c4    | 10        | 1.57%   |
| 0x20655    | 10        | 1.57%   |
| 0x106c2    | 10        | 1.57%   |
| 0x806ec    | 9         | 1.41%   |
| 0x406c3    | 9         | 1.41%   |
| 0x406e3    | 8         | 1.26%   |
| 0x20652    | 8         | 1.26%   |
| 0x05000119 | 8         | 1.26%   |
| 0x6d8      | 7         | 1.1%    |
| 0x08600106 | 6         | 0.94%   |
| 0x08600104 | 6         | 0.94%   |
| 0x06006705 | 6         | 0.94%   |
| 0x706e5    | 5         | 0.78%   |
| 0x6ec      | 5         | 0.78%   |
| 0x0810100b | 5         | 0.78%   |
| 0x906e9    | 4         | 0.63%   |
| 0x706a1    | 4         | 0.63%   |
| 0x6fb      | 4         | 0.63%   |
| 0x6f6      | 4         | 0.63%   |
| 0x506e3    | 4         | 0.63%   |
| 0x0a50000c | 4         | 0.63%   |
| 0x03000027 | 4         | 0.63%   |
| 0xa0652    | 3         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 77        | 12.58%  |
| Haswell          | 52        | 8.5%    |
| SandyBridge      | 51        | 8.33%   |
| Penryn           | 47        | 7.68%   |
| Silvermont       | 40        | 6.54%   |
| IvyBridge        | 36        | 5.88%   |
| Core             | 35        | 5.72%   |
| Zen+             | 33        | 5.39%   |
| Westmere         | 22        | 3.59%   |
| TigerLake        | 20        | 3.27%   |
| Skylake          | 18        | 2.94%   |
| Zen 2            | 17        | 2.78%   |
| P6               | 15        | 2.45%   |
| Broadwell        | 15        | 2.45%   |
| Excavator        | 14        | 2.29%   |
| Bonnell          | 14        | 2.29%   |
| Bobcat           | 11        | 1.8%    |
| Zen              | 10        | 1.63%   |
| Goldmont         | 10        | 1.63%   |
| Puma             | 9         | 1.47%   |
| Unknown          | 8         | 1.31%   |
| Zen 3            | 7         | 1.14%   |
| IceLake          | 7         | 1.14%   |
| CometLake        | 7         | 1.14%   |
| K8 & K10 hybrid  | 6         | 0.98%   |
| Goldmont plus    | 6         | 0.98%   |
| Piledriver       | 5         | 0.82%   |
| K8 Hammer        | 5         | 0.82%   |
| K10 Llano        | 5         | 0.82%   |
| Nehalem          | 4         | 0.65%   |
| K10              | 2         | 0.33%   |
| Alderlake Hybrid | 2         | 0.33%   |
| NetBurst         | 1         | 0.16%   |
| Jaguar           | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 403       | 53.66%  |
| AMD                              | 196       | 26.1%   |
| Nvidia                           | 147       | 19.57%  |
| VIA Technologies                 | 3         | 0.4%    |
| Silicon Integrated Systems [SiS] | 2         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 5.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 4.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 28        | 3.5%    |
| Intel UHD Graphics 620                                                                   | 21        | 2.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 2.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 2.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 2.62%   |
| Intel HD Graphics 620                                                                    | 19        | 2.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 2.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 2.25%   |
| AMD Renoir                                                                               | 17        | 2.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 1.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 1.87%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.25%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 1.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.12%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 1.12%   |
| Intel HD Graphics 500                                                                    | 9         | 1.12%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 1.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 1.12%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 1.12%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 0.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 0.87%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 7         | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.75%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 6         | 0.75%   |
| Intel HD Graphics 530                                                                    | 6         | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.75%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 6         | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.62%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 0.62%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.62%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 269       | 43.81%  |
| 1 x AMD        | 137       | 22.31%  |
| Intel + Nvidia | 98        | 15.96%  |
| 1 x Nvidia     | 42        | 6.84%   |
| Intel + AMD    | 35        | 5.7%    |
| 2 x AMD        | 18        | 2.93%   |
| AMD + Nvidia   | 6         | 0.98%   |
| 1 x VIA        | 3         | 0.49%   |
| 2 x Intel      | 2         | 0.33%   |
| 1 x SiS        | 2         | 0.33%   |
| Other          | 1         | 0.16%   |
| 2 x Nvidia     | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 537       | 87.18%  |
| Proprietary | 60        | 9.74%   |
| Unknown     | 19        | 3.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 346       | 54.92%  |
| 0.01-0.5   | 107       | 16.98%  |
| 1.01-2.0   | 89        | 14.13%  |
| 0.51-1.0   | 42        | 6.67%   |
| 3.01-4.0   | 37        | 5.87%   |
| 5.01-6.0   | 7         | 1.11%   |
| 7.01-8.0   | 1         | 0.16%   |
| 2.01-3.0   | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 112       | 17.36%  |
| AU Optronics            | 107       | 16.59%  |
| BOE                     | 93        | 14.42%  |
| Chimei Innolux          | 82        | 12.71%  |
| Samsung Electronics     | 78        | 12.09%  |
| Chi Mei Optoelectronics | 24        | 3.72%   |
| Goldstar                | 22        | 3.41%   |
| LG Philips              | 15        | 2.33%   |
| Dell                    | 15        | 2.33%   |
| Lenovo                  | 11        | 1.71%   |
| Apple                   | 9         | 1.4%    |
| CPT                     | 7         | 1.09%   |
| Sony                    | 6         | 0.93%   |
| Sharp                   | 6         | 0.93%   |
| PANDA                   | 6         | 0.93%   |
| InfoVision              | 6         | 0.93%   |
| HannStar                | 5         | 0.78%   |
| AOC                     | 5         | 0.78%   |
| Vestel Elektronik       | 3         | 0.47%   |
| Quanta Display          | 3         | 0.47%   |
| Philips                 | 3         | 0.47%   |
| Hewlett-Packard         | 3         | 0.47%   |
| CSO                     | 3         | 0.47%   |
| Iiyama                  | 2         | 0.31%   |
| Eizo                    | 2         | 0.31%   |
| Ancor Communications    | 2         | 0.31%   |
| ZLX                     | 1         | 0.16%   |
| ViewSonic               | 1         | 0.16%   |
| Valve                   | 1         | 0.16%   |
| TSL                     | 1         | 0.16%   |
| Toshiba                 | 1         | 0.16%   |
| Panasonic               | 1         | 0.16%   |
| Nvidia                  | 1         | 0.16%   |
| LPL                     | 1         | 0.16%   |
| LGD                     | 1         | 0.16%   |
| KDC                     | 1         | 0.16%   |
| JRY                     | 1         | 0.16%   |
| InnoLux Display         | 1         | 0.16%   |
| BenQ                    | 1         | 0.16%   |
| ASUSTek Computer        | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 1.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 1.23%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 1.23%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 7         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 7         | 1.08%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 7         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.92%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 5         | 0.77%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.77%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 5         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 4         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 4         | 0.62%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 4         | 0.62%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.62%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 4         | 0.62%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.62%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 3         | 0.46%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch        | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch    | 3         | 0.46%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 3         | 0.46%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.46%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch              | 3         | 0.46%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 3         | 0.46%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.46%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 3         | 0.46%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 3         | 0.46%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.46%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                    | 3         | 0.46%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 3         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 240       | 38.96%  |
| 1366x768 (WXGA)    | 217       | 35.23%  |
| 1280x800 (WXGA)    | 51        | 8.28%   |
| 1600x900 (HD+)     | 24        | 3.9%    |
| 3840x2160 (4K)     | 13        | 2.11%   |
| 1440x900 (WXGA+)   | 12        | 1.95%   |
| 2560x1440 (QHD)    | 9         | 1.46%   |
| 1024x600           | 9         | 1.46%   |
| 1920x1200 (WUXGA)  | 7         | 1.14%   |
| 1280x1024 (SXGA)   | 5         | 0.81%   |
| 1024x768 (XGA)     | 5         | 0.81%   |
| 2160x1440          | 4         | 0.65%   |
| 1680x1050 (WSXGA+) | 4         | 0.65%   |
| 2880x1800          | 3         | 0.49%   |
| 1360x768           | 3         | 0.49%   |
| 800x1280           | 2         | 0.32%   |
| 1600x1200          | 2         | 0.32%   |
| 3200x1800 (QHD+)   | 1         | 0.16%   |
| 2624x900           | 1         | 0.16%   |
| 2560x1600          | 1         | 0.16%   |
| 2560x1080          | 1         | 0.16%   |
| 1680x945           | 1         | 0.16%   |
| 1024x576           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 336       | 52.01%  |
| 13      | 70        | 10.84%  |
| 14      | 58        | 8.98%   |
| 17      | 46        | 7.12%   |
| 21      | 20        | 3.1%    |
| 27      | 17        | 2.63%   |
| 23      | 12        | 1.86%   |
| 12      | 12        | 1.86%   |
| 11      | 11        | 1.7%    |
| 10      | 11        | 1.7%    |
| 24      | 10        | 1.55%   |
| Unknown | 7         | 1.08%   |
| 84      | 4         | 0.62%   |
| 22      | 4         | 0.62%   |
| 18      | 4         | 0.62%   |
| 54      | 3         | 0.46%   |
| 16      | 3         | 0.46%   |
| 8       | 3         | 0.46%   |
| 72      | 2         | 0.31%   |
| 33      | 2         | 0.31%   |
| 31      | 2         | 0.31%   |
| 20      | 2         | 0.31%   |
| 65      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 40      | 1         | 0.15%   |
| 34      | 1         | 0.15%   |
| 25      | 1         | 0.15%   |
| 19      | 1         | 0.15%   |
| 7       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 434       | 67.81%  |
| 201-300     | 64        | 10%     |
| 351-400     | 49        | 7.66%   |
| 501-600     | 35        | 5.47%   |
| 401-500     | 29        | 4.53%   |
| Unknown     | 7         | 1.09%   |
| 1501-2000   | 6         | 0.94%   |
| 1001-1500   | 5         | 0.78%   |
| 701-800     | 3         | 0.47%   |
| 601-700     | 3         | 0.47%   |
| 101-200     | 3         | 0.47%   |
| 801-900     | 1         | 0.16%   |
| 1-100       | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 484       | 83.16%  |
| 16/10   | 74        | 12.71%  |
| 4/3     | 7         | 1.2%    |
| 5/4     | 5         | 0.86%   |
| 3/2     | 5         | 0.86%   |
| Unknown | 4         | 0.69%   |
| 21/9    | 1         | 0.17%   |
| 0.67    | 1         | 0.17%   |
| 0.62    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 335       | 51.94%  |
| 81-90          | 106       | 16.43%  |
| 201-250        | 40        | 6.2%    |
| 121-130        | 34        | 5.27%   |
| 71-80          | 22        | 3.41%   |
| 301-350        | 17        | 2.64%   |
| 61-70          | 12        | 1.86%   |
| More than 1000 | 11        | 1.71%   |
| 51-60          | 11        | 1.71%   |
| 41-50          | 11        | 1.71%   |
| 131-140        | 9         | 1.4%    |
| 151-200        | 7         | 1.09%   |
| Unknown        | 7         | 1.09%   |
| 141-150        | 6         | 0.93%   |
| 351-500        | 5         | 0.78%   |
| 1-40           | 4         | 0.62%   |
| 251-300        | 3         | 0.47%   |
| 111-120        | 2         | 0.31%   |
| 91-100         | 2         | 0.31%   |
| 501-1000       | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 234       | 37.08%  |
| 101-120       | 224       | 35.5%   |
| 51-100        | 124       | 19.65%  |
| 161-240       | 25        | 3.96%   |
| More than 240 | 9         | 1.43%   |
| 1-50          | 8         | 1.27%   |
| Unknown       | 7         | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 532       | 84.58%  |
| 2     | 69        | 10.97%  |
| 0     | 20        | 3.18%   |
| 3     | 7         | 1.11%   |
| 4     | 1         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 363       | 36.16%  |
| Intel                                 | 273       | 27.19%  |
| Qualcomm Atheros                      | 152       | 15.14%  |
| Broadcom                              | 78        | 7.77%   |
| Marvell Technology Group              | 24        | 2.39%   |
| Broadcom Limited                      | 19        | 1.89%   |
| Ralink                                | 15        | 1.49%   |
| TP-Link                               | 10        | 1%      |
| Ralink Technology                     | 8         | 0.8%    |
| MediaTek                              | 6         | 0.6%    |
| Qualcomm Atheros Communications       | 4         | 0.4%    |
| Nvidia                                | 4         | 0.4%    |
| Ericsson Business Mobile Networks     | 4         | 0.4%    |
| Dell                                  | 4         | 0.4%    |
| Sierra Wireless                       | 3         | 0.3%    |
| JMicron Technology                    | 3         | 0.3%    |
| Huawei Technologies                   | 3         | 0.3%    |
| Hewlett-Packard                       | 3         | 0.3%    |
| Xiaomi                                | 2         | 0.2%    |
| VIA Technologies                      | 2         | 0.2%    |
| Silicon Integrated Systems [SiS]      | 2         | 0.2%    |
| NetGear                               | 2         | 0.2%    |
| Edimax Technology                     | 2         | 0.2%    |
| D-Link                                | 2         | 0.2%    |
| ASIX Electronics                      | 2         | 0.2%    |
| Toshiba                               | 1         | 0.1%    |
| Sitecom Europe                        | 1         | 0.1%    |
| Samsung Electronics                   | 1         | 0.1%    |
| Linksys                               | 1         | 0.1%    |
| InProComm                             | 1         | 0.1%    |
| Google                                | 1         | 0.1%    |
| Fujitsu Siemens Computers             | 1         | 0.1%    |
| DisplayLink                           | 1         | 0.1%    |
| Belkin Components                     | 1         | 0.1%    |
| Attansic Technology                   | 1         | 0.1%    |
| ASUSTek Computer                      | 1         | 0.1%    |
| AMD                                   | 1         | 0.1%    |
| Accton Technology                     | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 186       | 15.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 111       | 9.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 30        | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 26        | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 2.19%   |
| Intel Wireless 8265 / 8275                                              | 25        | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 20        | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 1.6%    |
| Intel Wi-Fi 6 AX201                                                     | 18        | 1.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 1.51%   |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 1.43%   |
| Intel Wireless 7260                                                     | 16        | 1.35%   |
| Intel Wireless 3165                                                     | 16        | 1.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.26%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 1.18%   |
| Intel Wireless 3160                                                     | 12        | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 0.93%   |
| Intel Wireless 7265                                                     | 11        | 0.93%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 11        | 0.93%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 10        | 0.84%   |
| Intel WiFi Link 5100                                                    | 10        | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 0.76%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 8         | 0.67%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 0.67%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 6         | 0.5%    |
| Intel Wireless 8260                                                     | 6         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 261       | 40.53%  |
| Qualcomm Atheros                      | 133       | 20.65%  |
| Realtek Semiconductor                 | 125       | 19.41%  |
| Broadcom                              | 55        | 8.54%   |
| Ralink                                | 15        | 2.33%   |
| TP-Link                               | 9         | 1.4%    |
| Broadcom Limited                      | 9         | 1.4%    |
| Ralink Technology                     | 8         | 1.24%   |
| MediaTek                              | 5         | 0.78%   |
| Qualcomm Atheros Communications       | 4         | 0.62%   |
| Sierra Wireless                       | 3         | 0.47%   |
| NetGear                               | 2         | 0.31%   |
| Hewlett-Packard                       | 2         | 0.31%   |
| Edimax Technology                     | 2         | 0.31%   |
| D-Link                                | 2         | 0.31%   |
| Sitecom Europe                        | 1         | 0.16%   |
| Linksys                               | 1         | 0.16%   |
| InProComm                             | 1         | 0.16%   |
| Fujitsu Siemens Computers             | 1         | 0.16%   |
| Dell                                  | 1         | 0.16%   |
| Belkin Components                     | 1         | 0.16%   |
| ASUSTek Computer                      | 1         | 0.16%   |
| Accton Technology                     | 1         | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 30        | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 4.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 26        | 4.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 4.03%   |
| Intel Wireless 8265 / 8275                                              | 25        | 3.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 3.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 3.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 2.95%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 2.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 2.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 2.64%   |
| Intel Wireless 7260                                                     | 16        | 2.48%   |
| Intel Wireless 3165                                                     | 16        | 2.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 2.33%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 2.17%   |
| Intel Wireless 3160                                                     | 12        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.86%   |
| Intel Wireless 7265                                                     | 11        | 1.71%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 11        | 1.71%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 10        | 1.55%   |
| Intel WiFi Link 5100                                                    | 10        | 1.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 1.55%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 1.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.24%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.24%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.93%   |
| Intel Wireless 8260                                                     | 6         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.62%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 321       | 61.49%  |
| Intel                            | 78        | 14.94%  |
| Qualcomm Atheros                 | 35        | 6.7%    |
| Broadcom                         | 31        | 5.94%   |
| Marvell Technology Group         | 24        | 4.6%    |
| Broadcom Limited                 | 13        | 2.49%   |
| Nvidia                           | 4         | 0.77%   |
| JMicron Technology               | 3         | 0.57%   |
| Xiaomi                           | 2         | 0.38%   |
| VIA Technologies                 | 2         | 0.38%   |
| Silicon Integrated Systems [SiS] | 2         | 0.38%   |
| ASIX Electronics                 | 2         | 0.38%   |
| TP-Link                          | 1         | 0.19%   |
| Samsung Electronics              | 1         | 0.19%   |
| Huawei Technologies              | 1         | 0.19%   |
| DisplayLink                      | 1         | 0.19%   |
| Attansic Technology              | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 186       | 35.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 111       | 21.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 20        | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 2.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 1.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 1.52%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 1.14%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.14%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 6         | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 0.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.76%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 4         | 0.76%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.76%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 4         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.57%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.57%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 3         | 0.57%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.57%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.57%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 3         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 2         | 0.38%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 2         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.38%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.38%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 604       | 53.03%  |
| Ethernet | 516       | 45.3%   |
| Modem    | 19        | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 494       | 77.43%  |
| Ethernet | 144       | 22.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 489       | 79.51%  |
| 1     | 108       | 17.56%  |
| 0     | 14        | 2.28%   |
| 3     | 4         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 472       | 75.04%  |
| Yes  | 157       | 24.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 161       | 34.77%  |
| Realtek Semiconductor           | 71        | 15.33%  |
| Qualcomm Atheros Communications | 54        | 11.66%  |
| Broadcom                        | 28        | 6.05%   |
| IMC Networks                    | 23        | 4.97%   |
| Foxconn / Hon Hai               | 19        | 4.1%    |
| Toshiba                         | 16        | 3.46%   |
| Lite-On Technology              | 14        | 3.02%   |
| Hewlett-Packard                 | 14        | 3.02%   |
| Cambridge Silicon Radio         | 9         | 1.94%   |
| Apple                           | 9         | 1.94%   |
| Ralink                          | 8         | 1.73%   |
| Realtek                         | 6         | 1.3%    |
| Foxconn International           | 6         | 1.3%    |
| Dell                            | 6         | 1.3%    |
| Alps Electric                   | 6         | 1.3%    |
| Ralink Technology               | 4         | 0.86%   |
| Askey Computer                  | 4         | 0.86%   |
| Chicony Electronics             | 2         | 0.43%   |
| ASUSTek Computer                | 2         | 0.43%   |
| Syntek                          | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 81        | 17.49%  |
| Realtek Bluetooth Radio                                                             | 33        | 7.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 26        | 5.62%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 22        | 4.75%   |
| Intel AX201 Bluetooth                                                               | 21        | 4.54%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 19        | 4.1%    |
| Intel AX200 Bluetooth                                                               | 13        | 2.81%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 2.38%   |
| Realtek RTL8723B Bluetooth                                                          | 10        | 2.16%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 10        | 2.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 1.94%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 1.73%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 1.73%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 1.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 8         | 1.73%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 8         | 1.73%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 1.51%   |
| Realtek 802.11ac WLAN Adapter                                                       | 6         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.3%    |
| Foxconn International BCM43142A0 Bluetooth module                                   | 6         | 1.3%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 6         | 1.3%    |
| Toshiba RT Bluetooth Radio                                                          | 5         | 1.08%   |
| Toshiba Bluetooth Device                                                            | 5         | 1.08%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 1.08%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.08%   |
| Apple Bluetooth Host Controller                                                     | 5         | 1.08%   |
| Qualcomm Atheros Bluetooth                                                          | 4         | 0.86%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 0.86%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 4         | 0.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.86%   |
| Askey Bluetooth Device                                                              | 4         | 0.86%   |
| Realtek RTL8723A Bluetooth                                                          | 3         | 0.65%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 3         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 459       | 65.01%  |
| AMD                              | 153       | 21.67%  |
| Nvidia                           | 64        | 9.07%   |
| C-Media Electronics              | 4         | 0.57%   |
| VIA Technologies                 | 3         | 0.42%   |
| Creative Technology              | 3         | 0.42%   |
| Barco Display Systems            | 3         | 0.42%   |
| Silicon Integrated Systems [SiS] | 2         | 0.28%   |
| Logitech                         | 2         | 0.28%   |
| GN Netcom                        | 2         | 0.28%   |
| Trust                            | 1         | 0.14%   |
| Texas Instruments                | 1         | 0.14%   |
| Razer USA                        | 1         | 0.14%   |
| Lenovo                           | 1         | 0.14%   |
| Kingston Technology              | 1         | 0.14%   |
| Guillemot                        | 1         | 0.14%   |
| Generalplus Technology           | 1         | 0.14%   |
| CMX Systems                      | 1         | 0.14%   |
| bestechnic                       | 1         | 0.14%   |
| BEHRINGER International          | 1         | 0.14%   |
| ASUSTek Computer                 | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 67        | 7.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 5.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 50        | 5.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 4.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 40        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 37        | 4.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 29        | 3.27%   |
| Intel 8 Series HD Audio Controller                                                                | 29        | 3.27%   |
| AMD FCH Azalia Controller                                                                         | 29        | 3.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 27        | 3.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 2.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 24        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24        | 2.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 24        | 2.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 21        | 2.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 20        | 2.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 1.92%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 1.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 14        | 1.58%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 1.13%   |
| AMD Wrestler HDMI Audio                                                                           | 10        | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.01%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 9         | 1.01%   |
| AMD High Definition Audio Controller                                                              | 9         | 1.01%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.68%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 6         | 0.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 89        | 27.64%  |
| SK hynix            | 79        | 24.53%  |
| Micron Technology   | 38        | 11.8%   |
| Unknown             | 25        | 7.76%   |
| Kingston            | 25        | 7.76%   |
| Crucial             | 15        | 4.66%   |
| Ramaxel Technology  | 11        | 3.42%   |
| Elpida              | 7         | 2.17%   |
| Transcend           | 6         | 1.86%   |
| Corsair             | 5         | 1.55%   |
| Unknown (ABCD)      | 4         | 1.24%   |
| Nanya Technology    | 4         | 1.24%   |
| A-DATA Technology   | 4         | 1.24%   |
| Team                | 3         | 0.93%   |
| G.Skill             | 3         | 0.93%   |
| Toshiba             | 1         | 0.31%   |
| Infineon            | 1         | 0.31%   |
| GOODRAM             | 1         | 0.31%   |
| Apacer              | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 2.29%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 2.01%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 2.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 2.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 2.01%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 1.15%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.15%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.15%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.15%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.15%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.86%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.86%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.86%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.86%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.86%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.86%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.86%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.86%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 2         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 0.57%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                | 2         | 0.57%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 2         | 0.57%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.57%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.57%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.57%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.57%   |
| Samsung RAM Module 2048MB SODIMM DDR2 533MT/s                    | 2         | 0.57%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 113       | 41.39%  |
| DDR3    | 106       | 38.83%  |
| DDR2    | 26        | 9.52%   |
| LPDDR4  | 10        | 3.66%   |
| SDRAM   | 6         | 2.2%    |
| LPDDR3  | 4         | 1.47%   |
| DDR     | 3         | 1.1%    |
| DRAM    | 2         | 0.73%   |
| DDR5    | 2         | 0.73%   |
| Unknown | 1         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 252       | 92.65%  |
| Row Of Chips | 16        | 5.88%   |
| DIMM         | 3         | 1.1%    |
| Unknown      | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 104       | 34.67%  |
| 8192  | 100       | 33.33%  |
| 2048  | 49        | 16.33%  |
| 16384 | 25        | 8.33%   |
| 1024  | 15        | 5%      |
| 512   | 5         | 1.67%   |
| 32768 | 1         | 0.33%   |
| 256   | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 75        | 25.6%   |
| 2667    | 56        | 19.11%  |
| 3200    | 39        | 13.31%  |
| 2400    | 24        | 8.19%   |
| 1334    | 15        | 5.12%   |
| Unknown | 15        | 5.12%   |
| 667     | 12        | 4.1%    |
| 1333    | 10        | 3.41%   |
| 2133    | 9         | 3.07%   |
| 3266    | 7         | 2.39%   |
| 1067    | 6         | 2.05%   |
| 1066    | 4         | 1.37%   |
| 533     | 4         | 1.37%   |
| 4267    | 3         | 1.02%   |
| 4199    | 3         | 1.02%   |
| 4800    | 2         | 0.68%   |
| 2048    | 2         | 0.68%   |
| 1867    | 2         | 0.68%   |
| 800     | 2         | 0.68%   |
| 1639    | 1         | 0.34%   |
| 975     | 1         | 0.34%   |
| 400     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 50%     |
| Samsung Electronics | 3         | 30%     |
| Konica Minolta      | 1         | 10%     |
| Brother Industries  | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung M2020 Series                 | 3         | 30%     |
| Konica Minolta magicolor 1680MF scan | 1         | 10%     |
| HP OfficeJet 6200                    | 1         | 10%     |
| HP LaserJet P1102                    | 1         | 10%     |
| HP Laser 107w                        | 1         | 10%     |
| HP DeskJet 2620 All-in-One Printer   | 1         | 10%     |
| HP Color Laser 150nw                 | 1         | 10%     |
| Brother HL-2030 Laser Printer        | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Mustek Systems BearPaw 1200 CU Plus | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 126       | 23.86%  |
| IMC Networks                           | 56        | 10.61%  |
| Realtek Semiconductor                  | 49        | 9.28%   |
| Microdia                               | 45        | 8.52%   |
| Acer                                   | 44        | 8.33%   |
| Suyin                                  | 34        | 6.44%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 4.73%   |
| Sunplus Innovation Technology          | 23        | 4.36%   |
| Quanta                                 | 17        | 3.22%   |
| Ricoh                                  | 15        | 2.84%   |
| Lite-On Technology                     | 15        | 2.84%   |
| Syntek                                 | 13        | 2.46%   |
| Alcor Micro                            | 11        | 2.08%   |
| Silicon Motion                         | 7         | 1.33%   |
| Apple                                  | 7         | 1.33%   |
| Logitech                               | 5         | 0.95%   |
| Luxvisions Innotech Limited            | 4         | 0.76%   |
| Lenovo                                 | 4         | 0.76%   |
| Z-Star Microelectronics                | 3         | 0.57%   |
| Samsung Electronics                    | 3         | 0.57%   |
| Bison Electronics                      | 3         | 0.57%   |
| Sonix Technology                       | 2         | 0.38%   |
| Importek                               | 2         | 0.38%   |
| Genesys Logic                          | 2         | 0.38%   |
| DLEQNA19IFK6G2                         | 2         | 0.38%   |
| ALi                                    | 2         | 0.38%   |
| Primax Electronics                     | 1         | 0.19%   |
| Pixart Imaging                         | 1         | 0.19%   |
| OmniVision Technologies                | 1         | 0.19%   |
| Leap Motion                            | 1         | 0.19%   |
| Intel                                  | 1         | 0.19%   |
| Generalplus Technology                 | 1         | 0.19%   |
| GEMBIRD                                | 1         | 0.19%   |
| eMPIA Technology                       | 1         | 0.19%   |
| Arkmicro Technologies                  | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 22        | 4.17%   |
| Microdia Integrated_Webcam_HD                                   | 20        | 3.79%   |
| Realtek Integrated_Webcam_HD                                    | 18        | 3.41%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 15        | 2.84%   |
| IMC Networks Integrated Camera                                  | 14        | 2.65%   |
| Chicony HP Truevision HD                                        | 12        | 2.27%   |
| Acer Lenovo EasyCamera                                          | 10        | 1.89%   |
| Sunplus Integrated_Webcam_HD                                    | 8         | 1.52%   |
| Realtek Lenovo EasyCamera                                       | 8         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 8         | 1.52%   |
| Chicony TOSHIBA Web Camera - HD                                 | 7         | 1.33%   |
| Chicony HP Webcam                                               | 7         | 1.33%   |
| Acer BisonCam, NB Pro                                           | 7         | 1.33%   |
| Realtek 2SF022                                                  | 6         | 1.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 6         | 1.14%   |
| Chicony USB 2.0 Camera                                          | 6         | 1.14%   |
| Chicony HD WebCam                                               | 6         | 1.14%   |
| Acer SunplusIT Integrated Camera                                | 6         | 1.14%   |
| Syntek Integrated Camera                                        | 5         | 0.95%   |
| Suyin Integrated_Webcam_HD                                      | 5         | 0.95%   |
| Quanta VGA WebCam                                               | 5         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 5         | 0.95%   |
| IMC Networks Lenovo EasyCamera                                  | 5         | 0.95%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 5         | 0.95%   |
| Syntek Lenovo EasyCamera                                        | 4         | 0.76%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 4         | 0.76%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]             | 4         | 0.76%   |
| Realtek USB2.0 HD UVC WebCam                                    | 4         | 0.76%   |
| Realtek Integrated Webcam                                       | 4         | 0.76%   |
| Quanta HP TrueVision HD Camera                                  | 4         | 0.76%   |
| Lite-On HP Webcam                                               | 4         | 0.76%   |
| IMC Networks ov9734_azurewave_camera                            | 4         | 0.76%   |
| Chicony Lenovo EasyCamera                                       | 4         | 0.76%   |
| Chicony Integrated Camera (1280x720@30)                         | 4         | 0.76%   |
| Chicony HP HD Webcam                                            | 4         | 0.76%   |
| Chicony EasyCamera                                              | 4         | 0.76%   |
| Chicony CKF7063 Webcam (HP)                                     | 4         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 0.76%   |
| Apple FaceTime HD Camera                                        | 4         | 0.76%   |
| Alcor Micro HP Webcam-101                                       | 4         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 30.95%  |
| Synaptics                  | 15        | 17.86%  |
| AuthenTec                  | 13        | 15.48%  |
| Shenzhen Goodix Technology | 12        | 14.29%  |
| Upek                       | 11        | 13.1%   |
| Elan Microelectronics      | 5         | 5.95%   |
| STMicroelectronics         | 1         | 1.19%   |
| LighTuning Technology      | 1         | 1.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 11.9%   |
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 10.71%  |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 7.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 5.95%   |
| Elan ELAN:ARM-M4                                                           | 4         | 4.76%   |
| Synaptics  WBDI                                                            | 3         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.57%   |
| AuthenTec AES2810                                                          | 3         | 3.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.38%   |
| Validity Sensors VFS491                                                    | 2         | 2.38%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.38%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 2.38%   |
| Unknown                                                                    | 2         | 2.38%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.19%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.19%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.19%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.19%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.19%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.19%   |
| AuthenTec AES1600                                                          | 1         | 1.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 55.81%  |
| Alcor Micro | 9         | 20.93%  |
| O2 Micro    | 5         | 11.63%  |
| Upek        | 2         | 4.65%   |
| Lenovo      | 2         | 4.65%   |
| Yubico.com  | 1         | 2.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 10        | 23.26%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 20.93%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 20.93%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 11.63%  |
| Broadcom 5880                                                                | 3         | 6.98%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.65%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.65%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 2.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 395       | 62.6%   |
| 1     | 188       | 29.79%  |
| 2     | 39        | 6.18%   |
| 3     | 6         | 0.95%   |
| 6     | 2         | 0.32%   |
| 4     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 84        | 29.68%  |
| Graphics card            | 54        | 19.08%  |
| Chipcard                 | 39        | 13.78%  |
| Net/wireless             | 32        | 11.31%  |
| Bluetooth                | 19        | 6.71%   |
| Multimedia controller    | 18        | 6.36%   |
| Camera                   | 8         | 2.83%   |
| Storage                  | 5         | 1.77%   |
| Modem                    | 5         | 1.77%   |
| Flash memory             | 4         | 1.41%   |
| Communication controller | 4         | 1.41%   |
| Sound                    | 3         | 1.06%   |
| Card reader              | 3         | 1.06%   |
| Net/ethernet             | 2         | 0.71%   |
| Tv card                  | 1         | 0.35%   |
| Network                  | 1         | 0.35%   |
| Firewire controller      | 1         | 0.35%   |


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

Total: 877

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 91        | 14.31%  |
| Ubuntu 18.04      | 61        | 9.59%   |
| Ubuntu 22.04      | 26        | 4.09%   |
| KDE neon 20.04    | 15        | 2.36%   |
| OpenMandriva 4.3  | 14        | 2.2%    |
| OpenMandriva 4.2  | 14        | 2.2%    |
| Linux Mint 19.3   | 14        | 2.2%    |
| Debian 11         | 14        | 2.2%    |
| Zorin 15          | 11        | 1.73%   |
| Arch Rolling      | 11        | 1.73%   |
| Zorin 16          | 10        | 1.57%   |
| Ubuntu 19.10      | 10        | 1.57%   |
| Pop!_OS 22.04     | 10        | 1.57%   |
| Debian 10         | 10        | 1.57%   |
| Xubuntu 20.04     | 9         | 1.42%   |
| Pop!_OS 20.04     | 9         | 1.42%   |
| Manjaro           | 9         | 1.42%   |
| Linux Mint 20.2   | 9         | 1.42%   |
| Linux Mint 20.1   | 9         | 1.42%   |
| Fedora 35         | 9         | 1.42%   |
| Xubuntu 18.04     | 8         | 1.26%   |
| Pop!_OS 21.04     | 8         | 1.26%   |
| Linux Mint 21     | 8         | 1.26%   |
| Arch              | 8         | 1.26%   |
| Pop!_OS 20.10     | 7         | 1.1%    |
| Linux Mint 20.3   | 7         | 1.1%    |
| Gentoo 2.7        | 7         | 1.1%    |
| Ubuntu 21.10      | 6         | 0.94%   |
| Ubuntu 21.04      | 6         | 0.94%   |
| Ubuntu 19.04      | 6         | 0.94%   |
| ROSA R10          | 6         | 0.94%   |
| Kubuntu 20.04     | 6         | 0.94%   |
| ArcoLinux Rolling | 6         | 0.94%   |
| Ubuntu 20.10      | 5         | 0.79%   |
| Linux Mint 20     | 5         | 0.79%   |
| Fedora 33         | 5         | 0.79%   |
| Fedora 32         | 5         | 0.79%   |
| Ubuntu 18.10      | 4         | 0.63%   |
| Pop!_OS 21.10     | 4         | 0.63%   |
| Gentoo 2.8        | 4         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 204       | 34.06%  |
| Linux Mint    | 58        | 9.68%   |
| Pop!_OS       | 35        | 5.84%   |
| OpenMandriva  | 31        | 5.18%   |
| Fedora        | 27        | 4.51%   |
| Debian        | 27        | 4.51%   |
| Manjaro       | 23        | 3.84%   |
| Zorin         | 22        | 3.67%   |
| Xubuntu       | 18        | 3.01%   |
| Arch          | 18        | 3.01%   |
| KDE neon      | 16        | 2.67%   |
| Endless       | 14        | 2.34%   |
| ROSA          | 12        | 2%      |
| Kubuntu       | 11        | 1.84%   |
| Gentoo        | 10        | 1.67%   |
| ArcoLinux     | 8         | 1.34%   |
| Ubuntu MATE   | 7         | 1.17%   |
| Ubuntu Unity  | 4         | 0.67%   |
| Ubuntu Budgie | 4         | 0.67%   |
| LMDE          | 4         | 0.67%   |
| ALT Linux     | 4         | 0.67%   |
| openSUSE      | 3         | 0.5%    |
| Lubuntu       | 3         | 0.5%    |
| LinuxFX       | 3         | 0.5%    |
| Kali          | 3         | 0.5%    |
| EndeavourOS   | 3         | 0.5%    |
| Elementary    | 3         | 0.5%    |
| BlackPanther  | 3         | 0.5%    |
| Xero          | 2         | 0.33%   |
| Peppermint    | 2         | 0.33%   |
| CentOS        | 2         | 0.33%   |
| Void Linux    | 1         | 0.17%   |
| SteamOS       | 1         | 0.17%   |
| Solus         | 1         | 0.17%   |
| Slackware     | 1         | 0.17%   |
| Parrot        | 1         | 0.17%   |
| MX            | 1         | 0.17%   |
| Mageia        | 1         | 0.17%   |
| GNOME OS      | 1         | 0.17%   |
| GalliumOS     | 1         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-58-generic         | 14        | 2.03%   |
| 5.16.7-desktop-1omv4003  | 14        | 2.03%   |
| 5.4.0-42-generic         | 13        | 1.89%   |
| 5.15.0-52-generic        | 13        | 1.89%   |
| 5.10.14-desktop-1omv4002 | 13        | 1.89%   |
| 5.15.0-56-generic        | 9         | 1.31%   |
| 5.4.0-29-generic         | 8         | 1.16%   |
| 5.4.0-48-generic         | 7         | 1.02%   |
| 5.15.0-53-generic        | 7         | 1.02%   |
| 5.4.0-65-generic         | 6         | 0.87%   |
| 5.3.0-46-generic         | 6         | 0.87%   |
| 5.15.0-41-generic        | 6         | 0.87%   |
| 5.11.0-38-generic        | 6         | 0.87%   |
| 5.8.0-55-generic         | 5         | 0.73%   |
| 5.4.0-37-generic         | 5         | 0.73%   |
| 5.3.0-45-generic         | 5         | 0.73%   |
| 5.3.0-42-generic         | 5         | 0.73%   |
| 5.15.0-46-generic        | 5         | 0.73%   |
| 5.13.0-39-generic        | 5         | 0.73%   |
| 5.11.0-7620-generic      | 5         | 0.73%   |
| 5.11.0-7614-generic      | 5         | 0.73%   |
| 5.0.0-37-generic         | 5         | 0.73%   |
| 4.15.0-47-generic        | 5         | 0.73%   |
| 5.8.0-7630-generic       | 4         | 0.58%   |
| 5.8.0-48-generic         | 4         | 0.58%   |
| 5.8.0-43-generic         | 4         | 0.58%   |
| 5.4.0-91-generic         | 4         | 0.58%   |
| 5.4.0-72-generic         | 4         | 0.58%   |
| 5.4.0-66-generic         | 4         | 0.58%   |
| 5.4.0-56-generic         | 4         | 0.58%   |
| 5.4.0-54-generic         | 4         | 0.58%   |
| 5.4.0-52-generic         | 4         | 0.58%   |
| 5.18.10-76051810-generic | 4         | 0.58%   |
| 5.15.0-48-generic        | 4         | 0.58%   |
| 5.13.0-30-generic        | 4         | 0.58%   |
| 5.11.0-40-generic        | 4         | 0.58%   |
| 5.11.0-37-generic        | 4         | 0.58%   |
| 5.11.0-35-generic        | 4         | 0.58%   |
| 5.10.88-std-def-alt1     | 4         | 0.58%   |
| 5.0.0-23-generic         | 4         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 128       | 19.48%  |
| 5.15.0  | 53        | 8.07%   |
| 5.11.0  | 50        | 7.61%   |
| 4.15.0  | 43        | 6.54%   |
| 5.8.0   | 40        | 6.09%   |
| 5.3.0   | 37        | 5.63%   |
| 5.13.0  | 34        | 5.18%   |
| 5.0.0   | 21        | 3.2%    |
| 5.10.0  | 15        | 2.28%   |
| 5.16.7  | 14        | 2.13%   |
| 5.10.14 | 13        | 1.98%   |
| 4.18.0  | 13        | 1.98%   |
| 4.19.0  | 11        | 1.67%   |
| 5.9.11  | 5         | 0.76%   |
| 5.10.88 | 5         | 0.76%   |
| 5.18.10 | 4         | 0.61%   |
| 5.11.12 | 4         | 0.61%   |
| 4.9.20  | 4         | 0.61%   |
| 6.0.6   | 3         | 0.46%   |
| 5.8.18  | 3         | 0.46%   |
| 5.7.2   | 3         | 0.46%   |
| 5.3.18  | 3         | 0.46%   |
| 5.17.5  | 3         | 0.46%   |
| 5.15.5  | 3         | 0.46%   |
| 4.9.60  | 3         | 0.46%   |
| 5.9.16  | 2         | 0.3%    |
| 5.8.6   | 2         | 0.3%    |
| 5.8.16  | 2         | 0.3%    |
| 5.5.13  | 2         | 0.3%    |
| 5.4.77  | 2         | 0.3%    |
| 5.19.0  | 2         | 0.3%    |
| 5.17.1  | 2         | 0.3%    |
| 5.15.32 | 2         | 0.3%    |
| 5.15.19 | 2         | 0.3%    |
| 5.15.16 | 2         | 0.3%    |
| 5.14.14 | 2         | 0.3%    |
| 5.14.10 | 2         | 0.3%    |
| 5.14.0  | 2         | 0.3%    |
| 5.12.4  | 2         | 0.3%    |
| 5.12.14 | 2         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 139       | 21.29%  |
| 5.15    | 70        | 10.72%  |
| 5.11    | 61        | 9.34%   |
| 5.8     | 54        | 8.27%   |
| 5.10    | 47        | 7.2%    |
| 5.3     | 43        | 6.58%   |
| 4.15    | 43        | 6.58%   |
| 5.13    | 39        | 5.97%   |
| 5.0     | 22        | 3.37%   |
| 5.16    | 20        | 3.06%   |
| 4.18    | 14        | 2.14%   |
| 5.9     | 12        | 1.84%   |
| 4.19    | 11        | 1.68%   |
| 4.9     | 9         | 1.38%   |
| 5.18    | 8         | 1.23%   |
| 5.17    | 8         | 1.23%   |
| 5.14    | 8         | 1.23%   |
| 5.12    | 7         | 1.07%   |
| 6.0     | 6         | 0.92%   |
| 5.7     | 6         | 0.92%   |
| 5.6     | 6         | 0.92%   |
| 5.19    | 6         | 0.92%   |
| 5.5     | 5         | 0.77%   |
| 4.1     | 2         | 0.31%   |
| 6.1     | 1         | 0.15%   |
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
| x86_64 | 543       | 93.62%  |
| i686   | 37        | 6.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| GNOME               | 267       | 43.84%  |
| KDE5                | 88        | 14.45%  |
| Unknown             | 76        | 12.48%  |
| XFCE                | 54        | 8.87%   |
| X-Cinnamon          | 49        | 8.05%   |
| MATE                | 21        | 3.45%   |
| KDE                 | 19        | 3.12%   |
| KDE4                | 6         | 0.99%   |
| Budgie              | 5         | 0.82%   |
| Unity               | 4         | 0.66%   |
| Pantheon            | 3         | 0.49%   |
| LXQt                | 3         | 0.49%   |
| LXDE                | 3         | 0.49%   |
| Cinnamon            | 3         | 0.49%   |
| i3                  | 2         | 0.33%   |
| GNOME Classic       | 2         | 0.33%   |
| openbox             | 1         | 0.16%   |
| Deepin              | 1         | 0.16%   |
| awesome             | 1         | 0.16%   |
| /usr/bin/startxfce4 | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 480       | 79.87%  |
| Wayland | 66        | 10.98%  |
| Unknown | 41        | 6.82%   |
| Tty     | 14        | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 345       | 57.21%  |
| SDDM    | 72        | 11.94%  |
| GDM     | 61        | 10.12%  |
| LightDM | 53        | 8.79%   |
| GDM3    | 46        | 7.63%   |
| TDM     | 16        | 2.65%   |
| KDM     | 6         | 1%      |
| XDM     | 2         | 0.33%   |
| SLiM    | 1         | 0.17%   |
| Ly      | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 334       | 56.04%  |
| el_GR   | 154       | 25.84%  |
| Unknown | 72        | 12.08%  |
| en_GB   | 13        | 2.18%   |
| de_DE   | 6         | 1.01%   |
| C       | 5         | 0.84%   |
| POSIX   | 2         | 0.34%   |
| fr_FR   | 2         | 0.34%   |
| ru_RU   | 1         | 0.17%   |
| pl_PL   | 1         | 0.17%   |
| it_IT   | 1         | 0.17%   |
| hu_HU   | 1         | 0.17%   |
| en_IE   | 1         | 0.17%   |
| en_AG   | 1         | 0.17%   |
| C.UTF8  | 1         | 0.17%   |
| anp_IN  | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 323       | 54.47%  |
| EFI  | 270       | 45.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 477       | 80.44%  |
| Btrfs   | 43        | 7.25%   |
| Overlay | 40        | 6.75%   |
| Unknown | 28        | 4.72%   |
| Zfs     | 3         | 0.51%   |
| Tmpfs   | 1         | 0.17%   |
| F2fs    | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 375       | 62.71%  |
| GPT     | 151       | 25.25%  |
| MBR     | 72        | 12.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 511       | 86.46%  |
| Yes       | 80        | 13.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 418       | 71.58%  |
| Yes       | 166       | 28.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 136       | 23.45%  |
| Lenovo                  | 111       | 19.14%  |
| Dell                    | 91        | 15.69%  |
| ASUSTek Computer        | 45        | 7.76%   |
| Acer                    | 44        | 7.59%   |
| Toshiba                 | 28        | 4.83%   |
| Sony                    | 26        | 4.48%   |
| Fujitsu Siemens         | 10        | 1.72%   |
| Fujitsu                 | 10        | 1.72%   |
| Apple                   | 9         | 1.55%   |
| Notebook                | 6         | 1.03%   |
| MSI                     | 6         | 1.03%   |
| HUAWEI                  | 6         | 1.03%   |
| Clevo                   | 6         | 1.03%   |
| Unknown                 | 6         | 1.03%   |
| Samsung Electronics     | 4         | 0.69%   |
| Teclast                 | 3         | 0.52%   |
| Pegatron                | 3         | 0.52%   |
| Insyde                  | 3         | 0.52%   |
| Intel                   | 2         | 0.34%   |
| Info Quest Technologies | 2         | 0.34%   |
| Hampoo                  | 2         | 0.34%   |
| E-shop.gr               | 2         | 0.34%   |
| Chuwi                   | 2         | 0.34%   |
| VERO                    | 1         | 0.17%   |
| Valve                   | 1         | 0.17%   |
| TUXEDO                  | 1         | 0.17%   |
| Schenker                | 1         | 0.17%   |
| Quest                   | 1         | 0.17%   |
| Purism                  | 1         | 0.17%   |
| PLAISIO COMPUTERS SA    | 1         | 0.17%   |
| Plaisio                 | 1         | 0.17%   |
| PC Specialist           | 1         | 0.17%   |
| Packard Bell            | 1         | 0.17%   |
| Medion                  | 1         | 0.17%   |
| IBM                     | 1         | 0.17%   |
| Google                  | 1         | 0.17%   |
| Dynabook                | 1         | 0.17%   |
| Compal                  | 1         | 0.17%   |
| ARIMA                   | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 11        | 1.9%    |
| HP Pavilion g6                         | 9         | 1.55%   |
| HP Notebook                            | 7         | 1.21%   |
| Dell Inspiron 3542                     | 5         | 0.86%   |
| Lenovo G510 20238                      | 4         | 0.69%   |
| HP G62                                 | 4         | 0.69%   |
| HP 255 G7 Notebook PC                  | 4         | 0.69%   |
| Dell Inspiron 5567                     | 4         | 0.69%   |
| Dell Inspiron 3537                     | 4         | 0.69%   |
| Notebook W54_W94_W955TU,-T,-C          | 3         | 0.52%   |
| Lenovo G40-30 80FY                     | 3         | 0.52%   |
| Insyde CherryTrail                     | 3         | 0.52%   |
| HP Pavilion dv7                        | 3         | 0.52%   |
| HP 255 G8 Notebook PC                  | 3         | 0.52%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA | 3         | 0.52%   |
| Apple MacBookPro8,1                    | 3         | 0.52%   |
| Acer Aspire A315-51                    | 3         | 0.52%   |
| Acer Aspire A315-31                    | 3         | 0.52%   |
| Toshiba Satellite C850D-119            | 2         | 0.34%   |
| Toshiba Satellite C850D-118            | 2         | 0.34%   |
| Toshiba NB100                          | 2         | 0.34%   |
| Teclast F15                            | 2         | 0.34%   |
| Sony VPCM13M1E                         | 2         | 0.34%   |
| Sony VPCCB2S1E                         | 2         | 0.34%   |
| Pegatron A15                           | 2         | 0.34%   |
| Lenovo Legion Y530-15ICH 81FV          | 2         | 0.34%   |
| Lenovo IdeaPad S540-14API 81NH         | 2         | 0.34%   |
| Lenovo IdeaPad L340-17API 81LY         | 2         | 0.34%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK  | 2         | 0.34%   |
| Lenovo IdeaPad 100-15IBD 80QQ          | 2         | 0.34%   |
| Lenovo G700 20251                      | 2         | 0.34%   |
| Lenovo G70-35 80Q5                     | 2         | 0.34%   |
| Lenovo G50-70 20351                    | 2         | 0.34%   |
| Lenovo G50-30 80G0                     | 2         | 0.34%   |
| Lenovo B590 20208                      | 2         | 0.34%   |
| Intel Calistoga & ICH7M Chipset        | 2         | 0.34%   |
| HUAWEI NBLK-WAX9X                      | 2         | 0.34%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.34%   |
| HP Stream Laptop 14-ax0XX              | 2         | 0.34%   |
| HP ProBook 6560b                       | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 38        | 6.55%   |
| Lenovo ThinkPad       | 36        | 6.21%   |
| HP Pavilion           | 36        | 6.21%   |
| Lenovo IdeaPad        | 35        | 6.03%   |
| Acer Aspire           | 35        | 6.03%   |
| Dell Latitude         | 28        | 4.83%   |
| Toshiba Satellite     | 24        | 4.14%   |
| HP Compaq             | 13        | 2.24%   |
| HP EliteBook          | 12        | 2.07%   |
| HP 255                | 12        | 2.07%   |
| HP Laptop             | 11        | 1.9%    |
| ASUS VivoBook         | 11        | 1.9%    |
| Unknown               | 11        | 1.9%    |
| HP ProBook            | 9         | 1.55%   |
| Fujitsu LIFEBOOK      | 8         | 1.38%   |
| HP Notebook           | 7         | 1.21%   |
| Fujitsu Siemens AMILO | 7         | 1.21%   |
| Dell Precision        | 7         | 1.21%   |
| Dell Vostro           | 6         | 1.03%   |
| HP 250                | 5         | 0.86%   |
| Dell XPS              | 5         | 0.86%   |
| ASUS TUF              | 5         | 0.86%   |
| Lenovo G510           | 4         | 0.69%   |
| HP G62                | 4         | 0.69%   |
| Apple MacBookPro8     | 4         | 0.69%   |
| Notebook W54          | 3         | 0.52%   |
| Lenovo Legion         | 3         | 0.52%   |
| Lenovo G40-30         | 3         | 0.52%   |
| Insyde CherryTrail    | 3         | 0.52%   |
| HP Presario           | 3         | 0.52%   |
| HP ENVY               | 3         | 0.52%   |
| Toshiba NB100         | 2         | 0.34%   |
| Teclast F15           | 2         | 0.34%   |
| Sony VPCM13M1E        | 2         | 0.34%   |
| Sony VPCCB2S1E        | 2         | 0.34%   |
| Pegatron A15          | 2         | 0.34%   |
| Notebook W65          | 2         | 0.34%   |
| MSI GE70              | 2         | 0.34%   |
| Lenovo ThinkBook      | 2         | 0.34%   |
| Lenovo G700           | 2         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 57        | 9.83%   |
| 2013 | 48        | 8.28%   |
| 2011 | 46        | 7.93%   |
| 2012 | 43        | 7.41%   |
| 2020 | 42        | 7.24%   |
| 2017 | 40        | 6.9%    |
| 2008 | 40        | 6.9%    |
| 2018 | 38        | 6.55%   |
| 2014 | 36        | 6.21%   |
| 2009 | 33        | 5.69%   |
| 2015 | 31        | 5.34%   |
| 2010 | 31        | 5.34%   |
| 2016 | 28        | 4.83%   |
| 2007 | 26        | 4.48%   |
| 2021 | 20        | 3.45%   |
| 2006 | 8         | 1.38%   |
| 2005 | 6         | 1.03%   |
| 2022 | 5         | 0.86%   |
| 2004 | 2         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 580       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 520       | 89.04%  |
| Enabled  | 64        | 10.96%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 578       | 99.66%  |
| Yes  | 2         | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 169       | 28.84%  |
| 4.01-8.0    | 157       | 26.79%  |
| 8.01-16.0   | 93        | 15.87%  |
| 1.01-2.0    | 60        | 10.24%  |
| 16.01-24.0  | 57        | 9.73%   |
| 2.01-3.0    | 20        | 3.41%   |
| 32.01-64.0  | 15        | 2.56%   |
| 0.51-1.0    | 12        | 2.05%   |
| 24.01-32.0  | 2         | 0.34%   |
| 64.01-256.0 | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 268       | 42.07%  |
| 2.01-3.0   | 157       | 24.65%  |
| 0.51-1.0   | 66        | 10.36%  |
| 3.01-4.0   | 64        | 10.05%  |
| 4.01-8.0   | 61        | 9.58%   |
| 8.01-16.0  | 10        | 1.57%   |
| 0.01-0.5   | 9         | 1.41%   |
| 24.01-32.0 | 1         | 0.16%   |
| 16.01-24.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 436       | 73.4%   |
| 2      | 137       | 23.06%  |
| 3      | 13        | 2.19%   |
| 0      | 6         | 1.01%   |
| 6      | 1         | 0.17%   |
| 4      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 323       | 55.5%   |
| Yes       | 259       | 44.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 492       | 84.68%  |
| No        | 89        | 15.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 572       | 98.45%  |
| No        | 9         | 1.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 433       | 73.64%  |
| No        | 155       | 26.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Greece  | 580       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Athens       | 299       | 48.23%  |
| Thessaloniki | 95        | 15.32%  |
| Heraklion    | 20        | 3.23%   |
| Pátrai      | 14        | 2.26%   |
| Chalcis      | 13        | 2.1%    |
| Kavala       | 9         | 1.45%   |
| Katerini     | 8         | 1.29%   |
| Volos        | 7         | 1.13%   |
| Trikala      | 7         | 1.13%   |
| Piraeus      | 7         | 1.13%   |
| Rhodes       | 5         | 0.81%   |
| Corfu        | 5         | 0.81%   |
| Larissa      | 4         | 0.65%   |
| Kalamata     | 4         | 0.65%   |
| Ioannina     | 4         | 0.65%   |
| Fira         | 4         | 0.65%   |
| Corinth      | 4         | 0.65%   |
| Chania       | 4         | 0.65%   |
| Chalandri    | 4         | 0.65%   |
| Agrinio      | 4         | 0.65%   |
| Serres       | 3         | 0.48%   |
| Lamia        | 3         | 0.48%   |
| Koropi       | 3         | 0.48%   |
| Kilkis       | 3         | 0.48%   |
| Drama        | 3         | 0.48%   |
| Ano Liosia   | 3         | 0.48%   |
| Xanthi       | 2         | 0.32%   |
| Veroia       | 2         | 0.32%   |
| Salamina     | 2         | 0.32%   |
| Rethymno     | 2         | 0.32%   |
| Poros        | 2         | 0.32%   |
| Paros        | 2         | 0.32%   |
| Melissia     | 2         | 0.32%   |
| Marousi      | 2         | 0.32%   |
| Lefkada      | 2         | 0.32%   |
| Komotini     | 2         | 0.32%   |
| Kallithea    | 2         | 0.32%   |
| Grevena      | 2         | 0.32%   |
| Elateia      | 2         | 0.32%   |
| Chios        | 2         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 92        | 113    | 12.87%  |
| WDC                            | 91        | 120    | 12.73%  |
| Seagate                        | 81        | 100    | 11.33%  |
| Toshiba                        | 66        | 81     | 9.23%   |
| SanDisk                        | 51        | 63     | 7.13%   |
| Kingston                       | 47        | 59     | 6.57%   |
| Unknown                        | 40        | 59     | 5.59%   |
| SK hynix                       | 30        | 40     | 4.2%    |
| Patriot                        | 26        | 28     | 3.64%   |
| Hitachi                        | 24        | 24     | 3.36%   |
| HGST                           | 20        | 23     | 2.8%    |
| Micron Technology              | 16        | 19     | 2.24%   |
| Fujitsu                        | 16        | 17     | 2.24%   |
| Intenso                        | 15        | 18     | 2.1%    |
| Crucial                        | 14        | 15     | 1.96%   |
| Intel                          | 12        | 16     | 1.68%   |
| Team                           | 7         | 12     | 0.98%   |
| KIOXIA                         | 6         | 6      | 0.84%   |
| OCZ                            | 5         | 5      | 0.7%    |
| JMicron Technology             | 5         | 5      | 0.7%    |
| Transcend                      | 3         | 3      | 0.42%   |
| Teclast                        | 3         | 3      | 0.42%   |
| Micron/Crucial Technology      | 3         | 4      | 0.42%   |
| Gigabyte Technology            | 3         | 3      | 0.42%   |
| SPCC                           | 2         | 3      | 0.28%   |
| Phison                         | 2         | 2      | 0.28%   |
| Mushkin                        | 2         | 2      | 0.28%   |
| Apple                          | 2         | 2      | 0.28%   |
| Apacer                         | 2         | 2      | 0.28%   |
| Unknown                        | 2         | 2      | 0.28%   |
| XPG                            | 1         | 1      | 0.14%   |
| WDC WDS                        | 1         | 1      | 0.14%   |
| Verbatim                       | 1         | 1      | 0.14%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.14%   |
| SSSTC                          | 1         | 1      | 0.14%   |
| Solid State Storage Technology | 1         | 1      | 0.14%   |
| SMI                            | 1         | 1      | 0.14%   |
| PNY                            | 1         | 1      | 0.14%   |
| Plextor                        | 1         | 1      | 0.14%   |
| Phison Electronics             | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 16        | 2.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 14        | 1.89%   |
| SK hynix NVMe SSD Drive 256GB       | 11        | 1.49%   |
| Samsung SSD 860 EVO 500GB           | 11        | 1.49%   |
| Unknown MMC Card  64GB              | 9         | 1.22%   |
| Toshiba MQ01ABF050 500GB            | 9         | 1.22%   |
| Patriot Burst 120GB SSD             | 9         | 1.22%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 1.08%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 1.08%   |
| SanDisk NVMe SSD Drive 256GB        | 8         | 1.08%   |
| Samsung SSD 860 EVO 250GB           | 8         | 1.08%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 1.08%   |
| Toshiba MQ01ABD100 1TB              | 7         | 0.95%   |
| HGST HTS545050A7E680 500GB          | 7         | 0.95%   |
| Unknown MMC Card  128GB             | 6         | 0.81%   |
| Kingston SA400S37120G 120GB SSD     | 6         | 0.81%   |
| HGST HTS721010A9E630 1TB            | 6         | 0.81%   |
| SanDisk NVMe SSD Drive 512GB        | 5         | 0.68%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.68%   |
| Samsung SSD 850 EVO 250GB           | 5         | 0.68%   |
| Kingston SA400S37480G 480GB SSD     | 5         | 0.68%   |
| Intenso External USB 3.0 1TB        | 5         | 0.68%   |
| Fujitsu MHY2200BH 200GB             | 5         | 0.68%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 4         | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 4         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB            | 4         | 0.54%   |
| Unknown MMC Card  2GB               | 4         | 0.54%   |
| Toshiba MQ04ABF100 1TB              | 4         | 0.54%   |
| Toshiba MQ01ABD050 500GB            | 4         | 0.54%   |
| Samsung NVMe SSD Drive 512GB        | 4         | 0.54%   |
| Patriot Burst 480GB SSD             | 4         | 0.54%   |
| JMicron Generic 240GB SSD           | 4         | 0.54%   |
| Hitachi HTS545032B9A300 320GB       | 4         | 0.54%   |
| WDC WD10JPVX-75JC3T0 1TB            | 3         | 0.41%   |
| Unknown MMC Card  16GB              | 3         | 0.41%   |
| Seagate ST9500420AS 500GB           | 3         | 0.41%   |
| Seagate ST1000LM048-2E7172 1TB      | 3         | 0.41%   |
| SanDisk SDSSDA120G 120GB            | 3         | 0.41%   |
| SanDisk DF4032  32GB                | 3         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 97     | 29.37%  |
| WDC                 | 66        | 84     | 24.54%  |
| Toshiba             | 46        | 59     | 17.1%   |
| Hitachi             | 24        | 24     | 8.92%   |
| HGST                | 20        | 23     | 7.43%   |
| Fujitsu             | 16        | 17     | 5.95%   |
| Samsung Electronics | 9         | 10     | 3.35%   |
| Intenso             | 5         | 6      | 1.86%   |
| Unknown             | 1         | 1      | 0.37%   |
| IBM/Hitachi         | 1         | 1      | 0.37%   |
| ASMT109x            | 1         | 1      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 63     | 20.83%  |
| Kingston            | 39        | 50     | 14.77%  |
| SanDisk             | 31        | 38     | 11.74%  |
| Patriot             | 26        | 28     | 9.85%   |
| WDC                 | 16        | 24     | 6.06%   |
| Crucial             | 12        | 13     | 4.55%   |
| Toshiba             | 11        | 12     | 4.17%   |
| Micron Technology   | 9         | 10     | 3.41%   |
| Intenso             | 9         | 11     | 3.41%   |
| Team                | 7         | 12     | 2.65%   |
| OCZ                 | 5         | 5      | 1.89%   |
| Intel               | 5         | 7      | 1.89%   |
| SK hynix            | 4         | 4      | 1.52%   |
| JMicron Technology  | 4         | 4      | 1.52%   |
| Transcend           | 3         | 3      | 1.14%   |
| Teclast             | 3         | 3      | 1.14%   |
| Gigabyte Technology | 3         | 3      | 1.14%   |
| SPCC                | 2         | 3      | 0.76%   |
| Mushkin             | 2         | 2      | 0.76%   |
| Apacer              | 2         | 2      | 0.76%   |
| WDC WDS             | 1         | 1      | 0.38%   |
| Verbatim            | 1         | 1      | 0.38%   |
| PNY                 | 1         | 1      | 0.38%   |
| Plextor             | 1         | 1      | 0.38%   |
| OCZ-AGIL            | 1         | 1      | 0.38%   |
| Netac               | 1         | 1      | 0.38%   |
| Leven               | 1         | 1      | 0.38%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.38%   |
| KingSpec            | 1         | 1      | 0.38%   |
| Hewlett-Packard     | 1         | 1      | 0.38%   |
| Emtec               | 1         | 2      | 0.38%   |
| Drevo               | 1         | 1      | 0.38%   |
| ASUS-PHISON         | 1         | 2      | 0.38%   |
| Apple               | 1         | 1      | 0.38%   |
| A-DATA Technology   | 1         | 1      | 0.38%   |
| Unknown             | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 262       | 324    | 38.14%  |
| SSD     | 250       | 315    | 36.39%  |
| NVMe    | 127       | 168    | 18.49%  |
| MMC     | 42        | 66     | 6.11%   |
| Unknown | 6         | 8      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 452       | 615    | 70.08%  |
| NVMe | 127       | 168    | 19.69%  |
| MMC  | 42        | 66     | 6.51%   |
| SAS  | 24        | 32     | 3.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 387       | 502    | 77.87%  |
| 0.51-1.0   | 103       | 128    | 20.72%  |
| 1.01-2.0   | 6         | 8      | 1.21%   |
| 4.01-10.0  | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 208       | 33.99%  |
| 251-500        | 140       | 22.88%  |
| 501-1000       | 68        | 11.11%  |
| 51-100         | 59        | 9.64%   |
| 1-20           | 45        | 7.35%   |
| 21-50          | 39        | 6.37%   |
| 1001-2000      | 30        | 4.9%    |
| Unknown        | 11        | 1.8%    |
| More than 3000 | 6         | 0.98%   |
| 2001-3000      | 6         | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 263       | 41.88%  |
| 21-50          | 118       | 18.79%  |
| 51-100         | 83        | 13.22%  |
| 101-250        | 72        | 11.46%  |
| 251-500        | 44        | 7.01%   |
| 501-1000       | 20        | 3.18%   |
| 1001-2000      | 14        | 2.23%   |
| Unknown        | 11        | 1.75%   |
| More than 3000 | 3         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                          | 4         | 4      | 11.11%  |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1         | 1      | 2.78%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 1      | 2.78%   |
| WDC WD5000BPVT-60HXZT1 500GB                        | 1         | 1      | 2.78%   |
| WDC WD3200BEVT-26ZCT0 320GB                         | 1         | 1      | 2.78%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 2.78%   |
| WDC WD1600BEVS-22RST0 160GB                         | 1         | 1      | 2.78%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD100M 1TB                             | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 3      | 2.78%   |
| SK hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 2.78%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 1         | 1      | 2.78%   |
| Seagate ST980811AS 80GB                             | 1         | 1      | 2.78%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.78%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.78%   |
| Seagate ST9160310AS 160GB                           | 1         | 1      | 2.78%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.78%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 2.78%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 2.78%   |
| SanDisk SSD U100 128GB                              | 1         | 1      | 2.78%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 970 EVO 500GB               | 1         | 1      | 2.78%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB        | 1         | 1      | 2.78%   |
| OCZ-AGIL ITY3 120GB SSD                             | 1         | 1      | 2.78%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.78%   |
| Kingston RBUSNS8180DS3128GJ 128GB SSD               | 1         | 1      | 2.78%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.78%   |
| Hitachi HTS723216L9A360 160GB                       | 1         | 1      | 2.78%   |
| Hitachi HTS545032B9A300 320GB                       | 1         | 1      | 2.78%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 2.78%   |
| Fujitsu MHT2080BH 80GB                              | 1         | 1      | 2.78%   |
| Crucial CT480M500SSD1 480GB                         | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 22.22%  |
| WDC                 | 6         | 6      | 16.67%  |
| Hitachi             | 4         | 4      | 11.11%  |
| HGST                | 4         | 4      | 11.11%  |
| Toshiba             | 3         | 5      | 8.33%   |
| SK hynix            | 2         | 2      | 5.56%   |
| SanDisk             | 2         | 2      | 5.56%   |
| Samsung Electronics | 2         | 2      | 5.56%   |
| OCZ-AGIL            | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| Kingston            | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 9      | 32%     |
| WDC     | 5         | 5      | 20%     |
| Hitachi | 4         | 4      | 16%     |
| HGST    | 4         | 4      | 16%     |
| Toshiba | 3         | 5      | 12%     |
| Fujitsu | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 28     | 69.44%  |
| SSD  | 8         | 8      | 22.22%  |
| NVMe | 3         | 3      | 8.33%   |

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
| Detected | 404       | 606    | 66.12%  |
| Works    | 171       | 236    | 27.99%  |
| Malfunc  | 36        | 39     | 5.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 412       | 64.58%  |
| AMD                              | 86        | 13.48%  |
| Samsung Electronics              | 30        | 4.7%    |
| SK hynix                         | 25        | 3.92%   |
| SanDisk                          | 24        | 3.76%   |
| Toshiba America Info Systems     | 9         | 1.41%   |
| Kingston Technology Company      | 9         | 1.41%   |
| Micron Technology                | 7         | 1.1%    |
| KIOXIA                           | 7         | 1.1%    |
| Nvidia                           | 5         | 0.78%   |
| Micron/Crucial Technology        | 4         | 0.63%   |
| VIA Technologies                 | 3         | 0.47%   |
| Phison Electronics               | 3         | 0.47%   |
| Union Memory (Shenzhen)          | 2         | 0.31%   |
| Silicon Integrated Systems [SiS] | 2         | 0.31%   |
| Silicon Image                    | 2         | 0.31%   |
| JMicron Technology               | 2         | 0.31%   |
| Solid State Storage Technology   | 1         | 0.16%   |
| Seagate Technology               | 1         | 0.16%   |
| O2 Micro                         | 1         | 0.16%   |
| Lite-On Technology               | 1         | 0.16%   |
| ASMedia Technology               | 1         | 0.16%   |
| ADATA Technology                 | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 72        | 10.18%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 43        | 6.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 37        | 5.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 36        | 5.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 34        | 4.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 24        | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23        | 3.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 22        | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 22        | 3.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 2.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 16        | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 2.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 2.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 1.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 12        | 1.7%    |
| Samsung NVMe SSD Controller 980                                                  | 11        | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                              | 10        | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 10        | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 1.27%   |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 1.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 8         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 1.13%   |
| Micron Non-Volatile memory controller                                            | 7         | 0.99%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 7         | 0.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 0.99%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 0.85%   |
| SK hynix BC511                                                                   | 6         | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.85%   |
| SK hynix Non-Volatile memory controller                                          | 5         | 0.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 0.71%   |
| SanDisk PC SN520 NVMe SSD                                                        | 5         | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 432       | 63.53%  |
| NVMe | 130       | 19.12%  |
| IDE  | 84        | 12.35%  |
| RAID | 34        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 456       | 78.62%  |
| AMD          | 123       | 21.21%  |
| CentaurHauls | 1         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 2.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.9%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 10        | 1.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 1.38%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 1.21%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 1.21%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 7         | 1.21%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 1.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 1.03%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 6         | 1.03%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 6         | 1.03%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 6         | 1.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 1.03%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 6         | 1.03%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 1.03%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 5         | 0.86%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 5         | 0.86%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.86%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.86%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.86%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 5         | 0.86%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 5         | 0.86%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.69%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 4         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.69%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 4         | 0.69%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 4         | 0.69%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 4         | 0.69%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.69%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.69%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 112       | 19.31%  |
| Intel Core i7                  | 90        | 15.52%  |
| Intel Core 2 Duo               | 52        | 8.97%   |
| Intel Core i3                  | 51        | 8.79%   |
| Intel Celeron                  | 41        | 7.07%   |
| Intel Atom                     | 29        | 5%      |
| AMD Ryzen 5                    | 29        | 5%      |
| Other                          | 23        | 3.97%   |
| Intel Pentium                  | 21        | 3.62%   |
| AMD Ryzen 7                    | 17        | 2.93%   |
| AMD Ryzen 3                    | 11        | 1.9%    |
| AMD E1                         | 9         | 1.55%   |
| AMD A4                         | 9         | 1.55%   |
| AMD A6                         | 8         | 1.38%   |
| Intel Pentium Dual-Core        | 7         | 1.21%   |
| Intel Core 2                   | 7         | 1.21%   |
| AMD A10                        | 7         | 1.21%   |
| Intel Pentium Dual             | 6         | 1.03%   |
| Intel Genuine                  | 5         | 0.86%   |
| Intel Celeron M                | 5         | 0.86%   |
| AMD A8                         | 5         | 0.86%   |
| Intel Pentium M                | 4         | 0.69%   |
| Intel Celeron Dual-Core        | 4         | 0.69%   |
| AMD Ryzen 7 PRO                | 3         | 0.52%   |
| AMD Athlon                     | 3         | 0.52%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.34%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.34%   |
| AMD Turion                     | 2         | 0.34%   |
| AMD Sempron                    | 2         | 0.34%   |
| AMD E                          | 2         | 0.34%   |
| AMD Athlon 64 X2               | 2         | 0.34%   |
| Intel Pentium 4                | 1         | 0.17%   |
| Intel Core m3                  | 1         | 0.17%   |
| Intel Core Duo                 | 1         | 0.17%   |
| Intel Core 2 Extreme           | 1         | 0.17%   |
| CentaurHauls VIA C7            | 1         | 0.17%   |
| AMD V140                       | 1         | 0.17%   |
| AMD Turion 64 Mobile           | 1         | 0.17%   |
| AMD Ryzen 5 PRO                | 1         | 0.17%   |
| AMD E2                         | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 345       | 59.48%  |
| 4      | 163       | 28.1%   |
| 1      | 32        | 5.52%   |
| 6      | 24        | 4.14%   |
| 8      | 14        | 2.41%   |
| 14     | 1         | 0.17%   |
| 12     | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 580       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 349       | 60.17%  |
| 1      | 230       | 39.66%  |
| 8      | 1         | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 546       | 93.65%  |
| 32-bit         | 25        | 4.29%   |
| Unknown        | 12        | 2.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 121       | 20.03%  |
| 0x206a7    | 43        | 7.12%   |
| 0x306a9    | 28        | 4.64%   |
| 0x40651    | 23        | 3.81%   |
| 0x1067a    | 22        | 3.64%   |
| 0x806ea    | 18        | 2.98%   |
| 0x306c3    | 18        | 2.98%   |
| 0x6fd      | 16        | 2.65%   |
| 0x30678    | 16        | 2.65%   |
| 0x08108102 | 15        | 2.48%   |
| 0x806e9    | 14        | 2.32%   |
| 0x10676    | 14        | 2.32%   |
| 0x806c1    | 12        | 1.99%   |
| 0x306d4    | 12        | 1.99%   |
| 0x08108109 | 12        | 1.99%   |
| 0x906ea    | 11        | 1.82%   |
| 0x506c9    | 10        | 1.66%   |
| 0x406c4    | 10        | 1.66%   |
| 0x20655    | 10        | 1.66%   |
| 0x106c2    | 10        | 1.66%   |
| 0x806ec    | 9         | 1.49%   |
| 0x406c3    | 9         | 1.49%   |
| 0x20652    | 8         | 1.32%   |
| 0x406e3    | 7         | 1.16%   |
| 0x05000119 | 7         | 1.16%   |
| 0x6d8      | 6         | 0.99%   |
| 0x706e5    | 5         | 0.83%   |
| 0x6ec      | 5         | 0.83%   |
| 0x08600106 | 5         | 0.83%   |
| 0x06006705 | 5         | 0.83%   |
| 0x906e9    | 4         | 0.66%   |
| 0x706a1    | 4         | 0.66%   |
| 0x6fb      | 4         | 0.66%   |
| 0x6f6      | 4         | 0.66%   |
| 0x08600104 | 4         | 0.66%   |
| 0x0810100b | 4         | 0.66%   |
| 0x03000027 | 4         | 0.66%   |
| 0xa0652    | 3         | 0.5%    |
| 0x806eb    | 3         | 0.5%    |
| 0x506e3    | 3         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 74        | 12.76%  |
| SandyBridge      | 50        | 8.62%   |
| Haswell          | 48        | 8.28%   |
| Penryn           | 45        | 7.76%   |
| Silvermont       | 39        | 6.72%   |
| IvyBridge        | 35        | 6.03%   |
| Core             | 35        | 6.03%   |
| Zen+             | 33        | 5.69%   |
| Westmere         | 22        | 3.79%   |
| TigerLake        | 15        | 2.59%   |
| Skylake          | 15        | 2.59%   |
| Zen 2            | 14        | 2.41%   |
| P6               | 14        | 2.41%   |
| Broadwell        | 14        | 2.41%   |
| Bonnell          | 14        | 2.41%   |
| Excavator        | 13        | 2.24%   |
| Goldmont         | 10        | 1.72%   |
| Bobcat           | 10        | 1.72%   |
| Zen              | 9         | 1.55%   |
| Puma             | 9         | 1.55%   |
| IceLake          | 7         | 1.21%   |
| Unknown          | 7         | 1.21%   |
| Zen 3            | 6         | 1.03%   |
| K8 & K10 hybrid  | 6         | 1.03%   |
| Goldmont plus    | 6         | 1.03%   |
| CometLake        | 6         | 1.03%   |
| Piledriver       | 5         | 0.86%   |
| K8 Hammer        | 5         | 0.86%   |
| K10 Llano        | 5         | 0.86%   |
| Nehalem          | 3         | 0.52%   |
| K10              | 2         | 0.34%   |
| Alderlake Hybrid | 2         | 0.34%   |
| NetBurst         | 1         | 0.17%   |
| Jaguar           | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 381       | 53.59%  |
| AMD                              | 185       | 26.02%  |
| Nvidia                           | 140       | 19.69%  |
| VIA Technologies                 | 3         | 0.42%   |
| Silicon Integrated Systems [SiS] | 2         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 5.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 4.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 4.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 3.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 2.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 2.76%   |
| Intel UHD Graphics 620                                                                   | 19        | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 2.5%    |
| Intel HD Graphics 620                                                                    | 19        | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 2.37%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 2.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 1.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 1.97%   |
| AMD Renoir                                                                               | 14        | 1.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 1.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.71%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.31%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 1.18%   |
| Intel HD Graphics 500                                                                    | 9         | 1.18%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 1.18%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 1.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.05%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 1.05%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 1.05%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 0.92%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 7         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.79%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 6         | 0.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.66%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.66%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.66%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 5         | 0.66%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 5         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 256       | 43.99%  |
| 1 x AMD        | 129       | 22.16%  |
| Intel + Nvidia | 93        | 15.98%  |
| 1 x Nvidia     | 40        | 6.87%   |
| Intel + AMD    | 32        | 5.5%    |
| 2 x AMD        | 18        | 3.09%   |
| AMD + Nvidia   | 6         | 1.03%   |
| 1 x VIA        | 3         | 0.52%   |
| 1 x SiS        | 2         | 0.34%   |
| Other          | 1         | 0.17%   |
| 2 x Nvidia     | 1         | 0.17%   |
| 2 x Intel      | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 510       | 87.33%  |
| Proprietary | 55        | 9.42%   |
| Unknown     | 19        | 3.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 326       | 54.61%  |
| 0.01-0.5   | 102       | 17.09%  |
| 1.01-2.0   | 83        | 13.9%   |
| 0.51-1.0   | 42        | 7.04%   |
| 3.01-4.0   | 36        | 6.03%   |
| 5.01-6.0   | 6         | 1.01%   |
| 7.01-8.0   | 1         | 0.17%   |
| 2.01-3.0   | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 105       | 17.18%  |
| AU Optronics            | 102       | 16.69%  |
| BOE                     | 84        | 13.75%  |
| Chimei Innolux          | 78        | 12.77%  |
| Samsung Electronics     | 75        | 12.27%  |
| Chi Mei Optoelectronics | 23        | 3.76%   |
| Goldstar                | 21        | 3.44%   |
| LG Philips              | 15        | 2.45%   |
| Dell                    | 14        | 2.29%   |
| Lenovo                  | 11        | 1.8%    |
| Apple                   | 9         | 1.47%   |
| CPT                     | 7         | 1.15%   |
| Sharp                   | 6         | 0.98%   |
| PANDA                   | 6         | 0.98%   |
| InfoVision              | 6         | 0.98%   |
| Sony                    | 5         | 0.82%   |
| HannStar                | 5         | 0.82%   |
| AOC                     | 5         | 0.82%   |
| Vestel Elektronik       | 3         | 0.49%   |
| Quanta Display          | 3         | 0.49%   |
| Philips                 | 3         | 0.49%   |
| Hewlett-Packard         | 3         | 0.49%   |
| Iiyama                  | 2         | 0.33%   |
| Eizo                    | 2         | 0.33%   |
| CSO                     | 2         | 0.33%   |
| Ancor Communications    | 2         | 0.33%   |
| ZLX                     | 1         | 0.16%   |
| ViewSonic               | 1         | 0.16%   |
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
| ANX                     | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 1.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 1.3%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 7         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 7         | 1.14%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 7         | 1.14%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 6         | 0.98%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 5         | 0.81%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 5         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 4         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 4         | 0.65%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 4         | 0.65%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.65%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.65%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 3         | 0.49%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch        | 3         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 0.49%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1020x570mm 46.0-inch   | 3         | 0.49%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 3         | 0.49%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 3         | 0.49%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch              | 3         | 0.49%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.49%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 3         | 0.49%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.49%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                    | 3         | 0.49%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 3         | 0.49%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 3         | 0.49%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.49%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 3         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 225       | 38.53%  |
| 1366x768 (WXGA)    | 205       | 35.1%   |
| 1280x800 (WXGA)    | 50        | 8.56%   |
| 1600x900 (HD+)     | 24        | 4.11%   |
| 3840x2160 (4K)     | 13        | 2.23%   |
| 1440x900 (WXGA+)   | 12        | 2.05%   |
| 2560x1440 (QHD)    | 9         | 1.54%   |
| 1024x600           | 9         | 1.54%   |
| 1920x1200 (WUXGA)  | 7         | 1.2%    |
| 1280x1024 (SXGA)   | 5         | 0.86%   |
| 1024x768 (XGA)     | 5         | 0.86%   |
| 2160x1440          | 3         | 0.51%   |
| 1680x1050 (WSXGA+) | 3         | 0.51%   |
| 1360x768           | 3         | 0.51%   |
| 2880x1800          | 2         | 0.34%   |
| 1600x1200          | 2         | 0.34%   |
| 800x1280           | 1         | 0.17%   |
| 3200x1800 (QHD+)   | 1         | 0.17%   |
| 2624x900           | 1         | 0.17%   |
| 2560x1600          | 1         | 0.17%   |
| 2560x1080          | 1         | 0.17%   |
| 1680x945           | 1         | 0.17%   |
| 1024x576           | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 316       | 51.63%  |
| 13      | 67        | 10.95%  |
| 14      | 55        | 8.99%   |
| 17      | 44        | 7.19%   |
| 21      | 20        | 3.27%   |
| 27      | 17        | 2.78%   |
| 23      | 12        | 1.96%   |
| 12      | 11        | 1.8%    |
| 11      | 11        | 1.8%    |
| 10      | 11        | 1.8%    |
| 24      | 8         | 1.31%   |
| Unknown | 7         | 1.14%   |
| 84      | 4         | 0.65%   |
| 18      | 4         | 0.65%   |
| 54      | 3         | 0.49%   |
| 22      | 3         | 0.49%   |
| 16      | 3         | 0.49%   |
| 8       | 3         | 0.49%   |
| 72      | 2         | 0.33%   |
| 33      | 2         | 0.33%   |
| 31      | 2         | 0.33%   |
| 20      | 2         | 0.33%   |
| 65      | 1         | 0.16%   |
| 49      | 1         | 0.16%   |
| 34      | 1         | 0.16%   |
| 25      | 1         | 0.16%   |
| 19      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 410       | 67.55%  |
| 201-300     | 61        | 10.05%  |
| 351-400     | 47        | 7.74%   |
| 501-600     | 34        | 5.6%    |
| 401-500     | 28        | 4.61%   |
| Unknown     | 7         | 1.15%   |
| 1501-2000   | 6         | 0.99%   |
| 1001-1500   | 5         | 0.82%   |
| 701-800     | 3         | 0.49%   |
| 601-700     | 3         | 0.49%   |
| 101-200     | 3         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 457       | 83.09%  |
| 16/10   | 71        | 12.91%  |
| 4/3     | 7         | 1.27%   |
| 5/4     | 5         | 0.91%   |
| 3/2     | 4         | 0.73%   |
| Unknown | 4         | 0.73%   |
| 21/9    | 1         | 0.18%   |
| 0.62    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 315       | 51.55%  |
| 81-90          | 101       | 16.53%  |
| 201-250        | 37        | 6.06%   |
| 121-130        | 32        | 5.24%   |
| 71-80          | 21        | 3.44%   |
| 301-350        | 17        | 2.78%   |
| More than 1000 | 11        | 1.8%    |
| 61-70          | 11        | 1.8%    |
| 51-60          | 11        | 1.8%    |
| 41-50          | 11        | 1.8%    |
| 131-140        | 9         | 1.47%   |
| 151-200        | 7         | 1.15%   |
| Unknown        | 7         | 1.15%   |
| 141-150        | 6         | 0.98%   |
| 351-500        | 5         | 0.82%   |
| 1-40           | 3         | 0.49%   |
| 251-300        | 3         | 0.49%   |
| 111-120        | 2         | 0.33%   |
| 91-100         | 2         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 220       | 36.79%  |
| 101-120       | 213       | 35.62%  |
| 51-100        | 120       | 20.07%  |
| 161-240       | 22        | 3.68%   |
| More than 240 | 8         | 1.34%   |
| 1-50          | 8         | 1.34%   |
| Unknown       | 7         | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 500       | 84.03%  |
| 2     | 68        | 11.43%  |
| 0     | 20        | 3.36%   |
| 3     | 6         | 1.01%   |
| 4     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 344       | 36.02%  |
| Intel                                 | 255       | 26.7%   |
| Qualcomm Atheros                      | 149       | 15.6%   |
| Broadcom                              | 73        | 7.64%   |
| Marvell Technology Group              | 23        | 2.41%   |
| Broadcom Limited                      | 19        | 1.99%   |
| Ralink                                | 15        | 1.57%   |
| TP-Link                               | 9         | 0.94%   |
| Ralink Technology                     | 8         | 0.84%   |
| MediaTek                              | 6         | 0.63%   |
| Qualcomm Atheros Communications       | 4         | 0.42%   |
| Nvidia                                | 4         | 0.42%   |
| Ericsson Business Mobile Networks     | 4         | 0.42%   |
| Dell                                  | 4         | 0.42%   |
| Sierra Wireless                       | 3         | 0.31%   |
| JMicron Technology                    | 3         | 0.31%   |
| Huawei Technologies                   | 3         | 0.31%   |
| Hewlett-Packard                       | 3         | 0.31%   |
| VIA Technologies                      | 2         | 0.21%   |
| Silicon Integrated Systems [SiS]      | 2         | 0.21%   |
| NetGear                               | 2         | 0.21%   |
| Edimax Technology                     | 2         | 0.21%   |
| D-Link                                | 2         | 0.21%   |
| Xiaomi                                | 1         | 0.1%    |
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
| ASIX Electronics                      | 1         | 0.1%    |
| AMD                                   | 1         | 0.1%    |
| Accton Technology                     | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 176       | 15.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 106       | 9.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 2.12%   |
| Intel Wireless 8265 / 8275                                              | 24        | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 19        | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 1.5%    |
| Intel Wireless 7260                                                     | 16        | 1.41%   |
| Intel Wireless 3165                                                     | 16        | 1.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.33%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.15%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 0.97%   |
| Intel Wireless 7265                                                     | 11        | 0.97%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 10        | 0.88%   |
| Intel Wireless 3160                                                     | 10        | 0.88%   |
| Intel WiFi Link 5100                                                    | 10        | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 0.88%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 0.8%    |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 8         | 0.71%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.71%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.62%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 6         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 244       | 39.87%  |
| Qualcomm Atheros                      | 130       | 21.24%  |
| Realtek Semiconductor                 | 117       | 19.12%  |
| Broadcom                              | 52        | 8.5%    |
| Ralink                                | 15        | 2.45%   |
| Broadcom Limited                      | 9         | 1.47%   |
| TP-Link                               | 8         | 1.31%   |
| Ralink Technology                     | 8         | 1.31%   |
| MediaTek                              | 5         | 0.82%   |
| Qualcomm Atheros Communications       | 4         | 0.65%   |
| Sierra Wireless                       | 3         | 0.49%   |
| NetGear                               | 2         | 0.33%   |
| Hewlett-Packard                       | 2         | 0.33%   |
| Edimax Technology                     | 2         | 0.33%   |
| D-Link                                | 2         | 0.33%   |
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
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 4.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 4.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 4.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 3.92%   |
| Intel Wireless 8265 / 8275                                              | 24        | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 2.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 2.77%   |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 2.77%   |
| Intel Wireless 7260                                                     | 16        | 2.61%   |
| Intel Wireless 3165                                                     | 16        | 2.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 2.45%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 2.12%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.96%   |
| Intel Wireless 7265                                                     | 11        | 1.79%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 10        | 1.63%   |
| Intel Wireless 3160                                                     | 10        | 1.63%   |
| Intel WiFi Link 5100                                                    | 10        | 1.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 1.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 1.63%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.31%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.31%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.98%   |
| Intel Wireless 8260                                                     | 5         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 306       | 61.57%  |
| Intel                            | 76        | 15.29%  |
| Qualcomm Atheros                 | 34        | 6.84%   |
| Broadcom                         | 27        | 5.43%   |
| Marvell Technology Group         | 23        | 4.63%   |
| Broadcom Limited                 | 13        | 2.62%   |
| Nvidia                           | 4         | 0.8%    |
| JMicron Technology               | 3         | 0.6%    |
| VIA Technologies                 | 2         | 0.4%    |
| Silicon Integrated Systems [SiS] | 2         | 0.4%    |
| Xiaomi                           | 1         | 0.2%    |
| TP-Link                          | 1         | 0.2%    |
| Samsung Electronics              | 1         | 0.2%    |
| Huawei Technologies              | 1         | 0.2%    |
| DisplayLink                      | 1         | 0.2%    |
| Attansic Technology              | 1         | 0.2%    |
| ASIX Electronics                 | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 176       | 35.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 106       | 21.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 3.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 2.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 1.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 1.6%    |
| Intel Ethernet Connection I217-LM                                              | 7         | 1.4%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1%      |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 1%      |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1%      |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 5         | 1%      |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.8%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 4         | 0.8%    |
| Intel Ethernet Connection I218-LM                                              | 4         | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.8%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 4         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.6%    |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.6%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 3         | 0.6%    |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.6%    |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.6%    |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 3         | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 2         | 0.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 2         | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.4%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.4%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 2         | 0.4%    |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 572       | 52.82%  |
| Ethernet | 492       | 45.43%  |
| Modem    | 19        | 1.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 468       | 77.48%  |
| Ethernet | 136       | 22.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 467       | 80.1%   |
| 1     | 98        | 16.81%  |
| 0     | 14        | 2.4%    |
| 3     | 4         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 454       | 76.17%  |
| Yes  | 142       | 23.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 147       | 33.79%  |
| Realtek Semiconductor           | 67        | 15.4%   |
| Qualcomm Atheros Communications | 51        | 11.72%  |
| Broadcom                        | 28        | 6.44%   |
| IMC Networks                    | 21        | 4.83%   |
| Foxconn / Hon Hai               | 18        | 4.14%   |
| Toshiba                         | 16        | 3.68%   |
| Lite-On Technology              | 14        | 3.22%   |
| Hewlett-Packard                 | 13        | 2.99%   |
| Cambridge Silicon Radio         | 9         | 2.07%   |
| Apple                           | 9         | 2.07%   |
| Ralink                          | 8         | 1.84%   |
| Foxconn International           | 6         | 1.38%   |
| Alps Electric                   | 6         | 1.38%   |
| Realtek                         | 5         | 1.15%   |
| Dell                            | 5         | 1.15%   |
| Ralink Technology               | 4         | 0.92%   |
| Askey Computer                  | 4         | 0.92%   |
| ASUSTek Computer                | 2         | 0.46%   |
| Syntek                          | 1         | 0.23%   |
| Chicony Electronics             | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 76        | 17.47%  |
| Realtek Bluetooth Radio                             | 37        | 8.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 5.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 5.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 4.14%   |
| Intel AX201 Bluetooth                               | 17        | 3.91%   |
| Intel AX200 Bluetooth                               | 12        | 2.76%   |
| Realtek RTL8723B Bluetooth                          | 9         | 2.07%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 2.07%   |
| IMC Networks Bluetooth Radio                        | 9         | 2.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 2.07%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 1.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.61%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 1.38%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 1.38%   |
| Toshiba RT Bluetooth Radio                          | 5         | 1.15%   |
| Toshiba Bluetooth Device                            | 5         | 1.15%   |
| Realtek Bluetooth Radio                             | 5         | 1.15%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.15%   |
| Apple Bluetooth Host Controller                     | 5         | 1.15%   |
| Qualcomm Atheros Bluetooth                          | 4         | 0.92%   |
| Lite-On Bluetooth Device                            | 4         | 0.92%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.92%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.92%   |
| Askey Bluetooth Device                              | 4         | 0.92%   |
| Realtek RTL8723A Bluetooth                          | 3         | 0.69%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 3         | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.69%   |
| IMC Networks Bluetooth Device                       | 3         | 0.69%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.69%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.69%   |
| Alps Electric Bluetooth Adapter                     | 3         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 435       | 65.32%  |
| AMD                              | 145       | 21.77%  |
| Nvidia                           | 59        | 8.86%   |
| C-Media Electronics              | 4         | 0.6%    |
| VIA Technologies                 | 3         | 0.45%   |
| Creative Technology              | 3         | 0.45%   |
| Barco Display Systems            | 3         | 0.45%   |
| Silicon Integrated Systems [SiS] | 2         | 0.3%    |
| Logitech                         | 2         | 0.3%    |
| GN Netcom                        | 2         | 0.3%    |
| Texas Instruments                | 1         | 0.15%   |
| Razer USA                        | 1         | 0.15%   |
| Lenovo                           | 1         | 0.15%   |
| Guillemot                        | 1         | 0.15%   |
| CMX Systems                      | 1         | 0.15%   |
| bestechnic                       | 1         | 0.15%   |
| BEHRINGER International          | 1         | 0.15%   |
| ASUSTek Computer                 | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 62        | 7.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 49        | 5.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 48        | 5.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 41        | 4.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 39        | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 4.31%   |
| AMD FCH Azalia Controller                                                                         | 29        | 3.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 27        | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 2.99%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 25        | 2.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 24        | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24        | 2.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 21        | 2.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 20        | 2.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 16        | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 1.8%    |
| Intel Broadwell-U Audio Controller                                                                | 14        | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 1.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 1.08%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 9         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.96%   |
| AMD High Definition Audio Controller                                                              | 8         | 0.96%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.72%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.72%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 6         | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.6%    |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 82        | 27.06%  |
| SK hynix            | 78        | 25.74%  |
| Micron Technology   | 34        | 11.22%  |
| Unknown             | 23        | 7.59%   |
| Kingston            | 22        | 7.26%   |
| Crucial             | 15        | 4.95%   |
| Ramaxel Technology  | 11        | 3.63%   |
| Elpida              | 7         | 2.31%   |
| Transcend           | 6         | 1.98%   |
| Corsair             | 5         | 1.65%   |
| Unknown (ABCD)      | 4         | 1.32%   |
| Nanya Technology    | 4         | 1.32%   |
| A-DATA Technology   | 4         | 1.32%   |
| Team                | 3         | 0.99%   |
| Toshiba             | 1         | 0.33%   |
| Infineon            | 1         | 0.33%   |
| GOODRAM             | 1         | 0.33%   |
| G.Skill             | 1         | 0.33%   |
| Apacer              | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 2.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 2.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.83%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.22%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.22%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.22%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.91%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.91%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.91%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.91%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.91%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.91%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.91%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.91%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.91%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.91%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.91%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 0.61%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                | 2         | 0.61%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 2         | 0.61%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.61%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.61%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.61%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.61%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.61%   |
| Samsung RAM Module 2048MB SODIMM DDR2 533MT/s                    | 2         | 0.61%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 2         | 0.61%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.61%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 104       | 40.31%  |
| DDR3    | 102       | 39.53%  |
| DDR2    | 25        | 9.69%   |
| LPDDR4  | 10        | 3.88%   |
| SDRAM   | 6         | 2.33%   |
| LPDDR3  | 4         | 1.55%   |
| DRAM    | 2         | 0.78%   |
| DDR5    | 2         | 0.78%   |
| DDR     | 2         | 0.78%   |
| Unknown | 1         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 238       | 92.61%  |
| Row Of Chips | 15        | 5.84%   |
| DIMM         | 3         | 1.17%   |
| Unknown      | 1         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 99        | 35.11%  |
| 8192  | 91        | 32.27%  |
| 2048  | 48        | 17.02%  |
| 16384 | 24        | 8.51%   |
| 1024  | 14        | 4.96%   |
| 512   | 4         | 1.42%   |
| 32768 | 1         | 0.35%   |
| 256   | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 71        | 25.54%  |
| 2667    | 51        | 18.35%  |
| 3200    | 36        | 12.95%  |
| 2400    | 23        | 8.27%   |
| 1334    | 15        | 5.4%    |
| Unknown | 14        | 5.04%   |
| 1333    | 11        | 3.96%   |
| 667     | 11        | 3.96%   |
| 2133    | 9         | 3.24%   |
| 3266    | 6         | 2.16%   |
| 1067    | 6         | 2.16%   |
| 1066    | 4         | 1.44%   |
| 533     | 4         | 1.44%   |
| 4267    | 3         | 1.08%   |
| 4199    | 3         | 1.08%   |
| 4800    | 2         | 0.72%   |
| 2048    | 2         | 0.72%   |
| 1867    | 2         | 0.72%   |
| 800     | 2         | 0.72%   |
| 1639    | 1         | 0.36%   |
| 975     | 1         | 0.36%   |
| 400     | 1         | 0.36%   |

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
| HP Laser 107a                        | 1         | 10%     |
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
| Chicony Electronics                    | 119       | 23.75%  |
| IMC Networks                           | 53        | 10.58%  |
| Realtek Semiconductor                  | 48        | 9.58%   |
| Acer                                   | 43        | 8.58%   |
| Microdia                               | 41        | 8.18%   |
| Suyin                                  | 31        | 6.19%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 4.79%   |
| Sunplus Innovation Technology          | 22        | 4.39%   |
| Quanta                                 | 17        | 3.39%   |
| Ricoh                                  | 15        | 2.99%   |
| Lite-On Technology                     | 14        | 2.79%   |
| Syntek                                 | 12        | 2.4%    |
| Alcor Micro                            | 11        | 2.2%    |
| Apple                                  | 7         | 1.4%    |
| Silicon Motion                         | 6         | 1.2%    |
| Luxvisions Innotech Limited            | 6         | 1.2%    |
| Logitech                               | 5         | 1%      |
| Lenovo                                 | 4         | 0.8%    |
| Z-Star Microelectronics                | 3         | 0.6%    |
| Samsung Electronics                    | 3         | 0.6%    |
| Sonix Technology                       | 2         | 0.4%    |
| Importek                               | 2         | 0.4%    |
| Genesys Logic                          | 2         | 0.4%    |
| ALi                                    | 2         | 0.4%    |
| Primax Electronics                     | 1         | 0.2%    |
| Pixart Imaging                         | 1         | 0.2%    |
| OmniVision Technologies                | 1         | 0.2%    |
| Leap Motion                            | 1         | 0.2%    |
| Intel                                  | 1         | 0.2%    |
| Generalplus Technology                 | 1         | 0.2%    |
| GEMBIRD                                | 1         | 0.2%    |
| eMPIA Technology                       | 1         | 0.2%    |
| Arkmicro Technologies                  | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 19        | 3.79%   |
| Microdia Integrated_Webcam_HD                       | 18        | 3.59%   |
| Chicony Integrated Camera                           | 18        | 3.59%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 14        | 2.79%   |
| IMC Networks Integrated Camera                      | 14        | 2.79%   |
| Chicony HP Truevision HD                            | 12        | 2.4%    |
| Acer Lenovo EasyCamera                              | 9         | 1.8%    |
| Sunplus Integrated_Webcam_HD                        | 8         | 1.6%    |
| Realtek USB Camera                                  | 8         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 8         | 1.6%    |
| Realtek Lenovo EasyCamera                           | 7         | 1.4%    |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 1.4%    |
| Chicony HP Webcam                                   | 7         | 1.4%    |
| Acer BisonCam, NB Pro                               | 7         | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 6         | 1.2%    |
| Chicony USB 2.0 Camera                              | 6         | 1.2%    |
| Syntek Integrated Camera                            | 5         | 1%      |
| Suyin Integrated_Webcam_HD                          | 5         | 1%      |
| Quanta VGA WebCam                                   | 5         | 1%      |
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 1%      |
| Chicony HD WebCam                                   | 5         | 1%      |
| Acer SunplusIT Integrated Camera                    | 5         | 1%      |
| Sunplus HD WebCam                                   | 4         | 0.8%    |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 4         | 0.8%    |
| Realtek USB2.0 HD UVC WebCam                        | 4         | 0.8%    |
| Realtek Integrated Webcam                           | 4         | 0.8%    |
| Quanta HP TrueVision HD Camera                      | 4         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 0.8%    |
| IMC Networks ov9734_azurewave_camera                | 4         | 0.8%    |
| IMC Networks Lenovo EasyCamera                      | 4         | 0.8%    |
| Chicony Lenovo EasyCamera                           | 4         | 0.8%    |
| Chicony Integrated Camera (1280x720@30)             | 4         | 0.8%    |
| Chicony HP HD Webcam                                | 4         | 0.8%    |
| Chicony CKF7063 Webcam (HP)                         | 4         | 0.8%    |
| Apple FaceTime HD Camera                            | 4         | 0.8%    |
| Alcor Micro USB 2.0 Camera                          | 4         | 0.8%    |
| Alcor Micro HP Webcam-101                           | 4         | 0.8%    |
| Acer Integrated Camera                              | 4         | 0.8%    |
| Syntek Lenovo EasyCamera                            | 3         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 29.87%  |
| Synaptics                  | 15        | 19.48%  |
| AuthenTec                  | 13        | 16.88%  |
| Upek                       | 11        | 14.29%  |
| Shenzhen Goodix Technology | 10        | 12.99%  |
| Elan Microelectronics      | 3         | 3.9%    |
| STMicroelectronics         | 1         | 1.3%    |
| LighTuning Technology      | 1         | 1.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 12.99%  |
| Shenzhen Goodix  Fingerprint Device                                        | 7         | 9.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 7.79%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 6.49%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 6.49%   |
| Synaptics  WBDI                                                            | 3         | 3.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.9%    |
| Elan ELAN:ARM-M4                                                           | 3         | 3.9%    |
| AuthenTec AES2810                                                          | 3         | 3.9%    |
| Validity Sensors VFS491                                                    | 2         | 2.6%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.6%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.6%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 2.6%    |
| Unknown                                                                    | 2         | 2.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.3%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.3%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.3%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.3%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.3%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.3%    |
| LighTuning Fingerprint Reader                                              | 1         | 1.3%    |
| AuthenTec AES1600                                                          | 1         | 1.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 60%     |
| Alcor Micro | 7         | 17.5%   |
| O2 Micro    | 4         | 10%     |
| Upek        | 2         | 5%      |
| Lenovo      | 2         | 5%      |
| Yubico.com  | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 10        | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 22.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 17.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 10%     |
| Broadcom 5880                                                                | 3         | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5%      |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 382       | 63.77%  |
| 1     | 172       | 28.71%  |
| 2     | 37        | 6.18%   |
| 3     | 5         | 0.83%   |
| 6     | 2         | 0.33%   |
| 4     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 77        | 29.62%  |
| Graphics card            | 45        | 17.31%  |
| Chipcard                 | 36        | 13.85%  |
| Net/wireless             | 31        | 11.92%  |
| Bluetooth                | 19        | 7.31%   |
| Multimedia controller    | 15        | 5.77%   |
| Camera                   | 8         | 3.08%   |
| Storage                  | 5         | 1.92%   |
| Modem                    | 5         | 1.92%   |
| Flash memory             | 4         | 1.54%   |
| Communication controller | 4         | 1.54%   |
| Sound                    | 3         | 1.15%   |
| Card reader              | 3         | 1.15%   |
| Net/ethernet             | 2         | 0.77%   |
| Tv card                  | 1         | 0.38%   |
| Network                  | 1         | 0.38%   |
| Firewire controller      | 1         | 0.38%   |


LinuxFX 11 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for LinuxFX 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LinuxFX_11/Desktop/README.md) and [notebooks](/Dist/LinuxFX_11/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | F2A78M-D3H                  | Desktop     | [f508e8a6f8](https://linux-hardware.org/?probe=f508e8a6f8) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [4e66f349b5](https://linux-hardware.org/?probe=4e66f349b5) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [caa91028ac](https://linux-hardware.org/?probe=caa91028ac) | Jan 30, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [67d9bb3ace](https://linux-hardware.org/?probe=67d9bb3ace) | Jan 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [5204867d35](https://linux-hardware.org/?probe=5204867d35) | Jan 30, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [1fea9d48e2](https://linux-hardware.org/?probe=1fea9d48e2) | Jan 26, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [86e6d5c19a](https://linux-hardware.org/?probe=86e6d5c19a) | Jan 23, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [506ee71418](https://linux-hardware.org/?probe=506ee71418) | Jan 23, 2022 |
| ASUSTek       | K95VM                       | Notebook    | [8345888a5e](https://linux-hardware.org/?probe=8345888a5e) | Jan 23, 2022 |
| ASUSTek       | K95VM                       | Notebook    | [fb24768fa2](https://linux-hardware.org/?probe=fb24768fa2) | Jan 23, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [a397ea4233](https://linux-hardware.org/?probe=a397ea4233) | Jan 22, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [6326f72eff](https://linux-hardware.org/?probe=6326f72eff) | Jan 21, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [6c57abcd85](https://linux-hardware.org/?probe=6c57abcd85) | Jan 16, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [05a41ad625](https://linux-hardware.org/?probe=05a41ad625) | Jan 16, 2022 |
| HP            | Compaq 6730b (NA373UC#AB... | Notebook    | [0a2913bd14](https://linux-hardware.org/?probe=0a2913bd14) | Jan 16, 2022 |
| Toshiba       | TECRA R850                  | Notebook    | [cd13f4b4ab](https://linux-hardware.org/?probe=cd13f4b4ab) | Jan 15, 2022 |
| Toshiba       | TECRA R850                  | Notebook    | [445c000697](https://linux-hardware.org/?probe=445c000697) | Jan 15, 2022 |
| HP            | Compaq 6730b (NA373UC#AB... | Notebook    | [dff23d9e2e](https://linux-hardware.org/?probe=dff23d9e2e) | Jan 13, 2022 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [b7e4b6f2f1](https://linux-hardware.org/?probe=b7e4b6f2f1) | Jan 13, 2022 |
| Intel         | DQ57TM AAE92694-400         | Desktop     | [59ef421003](https://linux-hardware.org/?probe=59ef421003) | Jan 12, 2022 |
| Google        | Teemo                       | Desktop     | [0f67b5ae59](https://linux-hardware.org/?probe=0f67b5ae59) | Jan 10, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [2ff1ed4b2c](https://linux-hardware.org/?probe=2ff1ed4b2c) | Jan 05, 2022 |
| Toshiba       | Satellite P300              | Notebook    | [7540ebe059](https://linux-hardware.org/?probe=7540ebe059) | Jan 02, 2022 |
| ABIT          | AW9D-MAX                    | Desktop     | [104f0e6fde](https://linux-hardware.org/?probe=104f0e6fde) | Jan 01, 2022 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [7c247b0c9f](https://linux-hardware.org/?probe=7c247b0c9f) | Dec 29, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [5cff8b82d5](https://linux-hardware.org/?probe=5cff8b82d5) | Dec 28, 2021 |
| Foxconn       | D270S/D250S MP              | Desktop     | [82580ebcb5](https://linux-hardware.org/?probe=82580ebcb5) | Dec 28, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [dd7335ec13](https://linux-hardware.org/?probe=dd7335ec13) | Dec 27, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [135d34c579](https://linux-hardware.org/?probe=135d34c579) | Dec 26, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [84b16824bd](https://linux-hardware.org/?probe=84b16824bd) | Dec 26, 2021 |
| ASRock        | N68-S3 UCC                  | Desktop     | [ae1acd8bbe](https://linux-hardware.org/?probe=ae1acd8bbe) | Dec 24, 2021 |
| HP            | 2AF7                        | Desktop     | [3b7ab440c6](https://linux-hardware.org/?probe=3b7ab440c6) | Dec 23, 2021 |
| Pegatron      | Maureen                     | Desktop     | [4bb6b10ba4](https://linux-hardware.org/?probe=4bb6b10ba4) | Dec 23, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [f08b82f201](https://linux-hardware.org/?probe=f08b82f201) | Dec 22, 2021 |
| Dell          | Latitude E6400              | Notebook    | [74586d9c77](https://linux-hardware.org/?probe=74586d9c77) | Dec 21, 2021 |
| Fujitsu       | CELSIUS H700                | Notebook    | [63c35d8f1d](https://linux-hardware.org/?probe=63c35d8f1d) | Dec 19, 2021 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [882c4d6758](https://linux-hardware.org/?probe=882c4d6758) | Dec 17, 2021 |
| Lenovo        | ThinkPad L380 20M6S4E000    | Notebook    | [745c4f6a79](https://linux-hardware.org/?probe=745c4f6a79) | Dec 16, 2021 |
| Alienware     | M17xR3                      | Notebook    | [d8c0a193cd](https://linux-hardware.org/?probe=d8c0a193cd) | Dec 14, 2021 |
| Dell          | G5 5590                     | Notebook    | [d68d926208](https://linux-hardware.org/?probe=d68d926208) | Dec 13, 2021 |
| Dell          | G5 5590                     | Notebook    | [88f9dfa75d](https://linux-hardware.org/?probe=88f9dfa75d) | Dec 13, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [7bc4106877](https://linux-hardware.org/?probe=7bc4106877) | Dec 12, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [2b3e03c89b](https://linux-hardware.org/?probe=2b3e03c89b) | Dec 12, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [77ee4f08a8](https://linux-hardware.org/?probe=77ee4f08a8) | Dec 10, 2021 |
| Dell          | Latitude E5400              | Notebook    | [3ce40a821b](https://linux-hardware.org/?probe=3ce40a821b) | Dec 09, 2021 |
| Acer          | Extensa 5220                | Notebook    | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | Notebook    | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| ASUSTek       | CM6650                      | Desktop     | [ef34d60843](https://linux-hardware.org/?probe=ef34d60843) | Dec 09, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [6808d41bfe](https://linux-hardware.org/?probe=6808d41bfe) | Dec 08, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [543f25da6d](https://linux-hardware.org/?probe=543f25da6d) | Dec 06, 2021 |
| ASUSTek       | H110-PLUS                   | Desktop     | [78a4619b31](https://linux-hardware.org/?probe=78a4619b31) | Dec 05, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [f4b7b56b1b](https://linux-hardware.org/?probe=f4b7b56b1b) | Dec 05, 2021 |
| Acer          | Aspire X1930                | Desktop     | [68d51a9af5](https://linux-hardware.org/?probe=68d51a9af5) | Dec 03, 2021 |
| Intel         | H55                         | Desktop     | [57390a46ad](https://linux-hardware.org/?probe=57390a46ad) | Dec 02, 2021 |
| ASRock        | Q1900-ITX                   | Desktop     | [878cd074fb](https://linux-hardware.org/?probe=878cd074fb) | Nov 30, 2021 |
| ASRock        | Q1900-ITX                   | Desktop     | [3468f76ee4](https://linux-hardware.org/?probe=3468f76ee4) | Nov 30, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [2799629c61](https://linux-hardware.org/?probe=2799629c61) | Nov 28, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [1e80d1c181](https://linux-hardware.org/?probe=1e80d1c181) | Nov 28, 2021 |
| Acer          | One S1002                   | Notebook    | [8ae39c3aaf](https://linux-hardware.org/?probe=8ae39c3aaf) | Nov 23, 2021 |
| GPU Compan... | GWTN116-3                   | Notebook    | [5534b12f2d](https://linux-hardware.org/?probe=5534b12f2d) | Nov 21, 2021 |
| HP            | ProBook 440 G1              | Notebook    | [6159b4aa5a](https://linux-hardware.org/?probe=6159b4aa5a) | Nov 20, 2021 |
| HP            | ProBook 440 G1              | Notebook    | [42d0889355](https://linux-hardware.org/?probe=42d0889355) | Nov 20, 2021 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [1e36050d80](https://linux-hardware.org/?probe=1e36050d80) | Nov 18, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [947e251d2c](https://linux-hardware.org/?probe=947e251d2c) | Nov 18, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [9b2574c5be](https://linux-hardware.org/?probe=9b2574c5be) | Nov 17, 2021 |
| Positivo      | POS-PIQ67CG POSITIVO        | Desktop     | [bcec39d0de](https://linux-hardware.org/?probe=bcec39d0de) | Nov 16, 2021 |
| Positivo      | POS-PIQ67CG POSITIVO        | Desktop     | [8f7dd03e2d](https://linux-hardware.org/?probe=8f7dd03e2d) | Nov 15, 2021 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [2a9002ab69](https://linux-hardware.org/?probe=2a9002ab69) | Nov 10, 2021 |
| Lenovo        | G50-80 80R0                 | Notebook    | [a24e6b4e38](https://linux-hardware.org/?probe=a24e6b4e38) | Nov 06, 2021 |
| Lenovo        | G50-80 80R0                 | Notebook    | [94d7421e0c](https://linux-hardware.org/?probe=94d7421e0c) | Nov 06, 2021 |
| Acer          | Aspire XXXX                 | Notebook    | [2e486fd092](https://linux-hardware.org/?probe=2e486fd092) | Nov 05, 2021 |
| ASUSTek       | N71Vg                       | Notebook    | [4fee4d2ffc](https://linux-hardware.org/?probe=4fee4d2ffc) | Nov 03, 2021 |
| Google        | Peppy                       | Notebook    | [6408d61aa6](https://linux-hardware.org/?probe=6408d61aa6) | Nov 03, 2021 |
| Google        | Peppy                       | Notebook    | [894676acea](https://linux-hardware.org/?probe=894676acea) | Nov 03, 2021 |
| HP            | 8054                        | Desktop     | [0a502d18dd](https://linux-hardware.org/?probe=0a502d18dd) | Nov 03, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d954a6ba33](https://linux-hardware.org/?probe=d954a6ba33) | Oct 31, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [2ecc44141a](https://linux-hardware.org/?probe=2ecc44141a) | Oct 30, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [24fe21040d](https://linux-hardware.org/?probe=24fe21040d) | Oct 30, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1bfea4f4f9](https://linux-hardware.org/?probe=1bfea4f4f9) | Oct 28, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [a2c515584f](https://linux-hardware.org/?probe=a2c515584f) | Oct 27, 2021 |
| Pegatron      | 2A99                        | Desktop     | [29fd6eae29](https://linux-hardware.org/?probe=29fd6eae29) | Oct 27, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [b05ed4eff3](https://linux-hardware.org/?probe=b05ed4eff3) | Oct 24, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5fbb62218c](https://linux-hardware.org/?probe=5fbb62218c) | Oct 24, 2021 |
| HP            | Pavilion g6                 | Notebook    | [2dfb826827](https://linux-hardware.org/?probe=2dfb826827) | Oct 24, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7be969965e](https://linux-hardware.org/?probe=7be969965e) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [c53ba56444](https://linux-hardware.org/?probe=c53ba56444) | Oct 23, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [edf703fb1c](https://linux-hardware.org/?probe=edf703fb1c) | Oct 23, 2021 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [23bb246149](https://linux-hardware.org/?probe=23bb246149) | Oct 20, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [d08969a0a4](https://linux-hardware.org/?probe=d08969a0a4) | Oct 17, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [7075439e69](https://linux-hardware.org/?probe=7075439e69) | Oct 17, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [d5487c9b84](https://linux-hardware.org/?probe=d5487c9b84) | Oct 17, 2021 |
| Positivo      | Smash3                      | Notebook    | [3c9fe4acb8](https://linux-hardware.org/?probe=3c9fe4acb8) | Oct 14, 2021 |
| Positivo      | Smash3                      | Notebook    | [ab60c4e746](https://linux-hardware.org/?probe=ab60c4e746) | Oct 14, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [b3bd1860ac](https://linux-hardware.org/?probe=b3bd1860ac) | Oct 11, 2021 |
| Intel         | DG35EC AAE29266-202         | Desktop     | [d61f31abf0](https://linux-hardware.org/?probe=d61f31abf0) | Oct 10, 2021 |
| Intel         | DG35EC AAE29266-202         | Desktop     | [24fa8f8f31](https://linux-hardware.org/?probe=24fa8f8f31) | Oct 10, 2021 |
| MSI           | P67A-GD65                   | Desktop     | [13a07c6b4d](https://linux-hardware.org/?probe=13a07c6b4d) | Oct 09, 2021 |
| MSI           | P67A-GD65                   | Desktop     | [78c9f06350](https://linux-hardware.org/?probe=78c9f06350) | Oct 08, 2021 |
| HP            | G62                         | Notebook    | [6cbed79ca9](https://linux-hardware.org/?probe=6cbed79ca9) | Oct 05, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| Dell          | Precision M6400             | Notebook    | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [1e1bf5e8e0](https://linux-hardware.org/?probe=1e1bf5e8e0) | Oct 03, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [0778440642](https://linux-hardware.org/?probe=0778440642) | Oct 02, 2021 |
| Intel         | DG35EC AAE29266-202         | Desktop     | [74d233db8b](https://linux-hardware.org/?probe=74d233db8b) | Oct 02, 2021 |
| Intel         | DG35EC AAE29266-202         | Desktop     | [f29471dfd6](https://linux-hardware.org/?probe=f29471dfd6) | Oct 01, 2021 |
| Dell          | 0DN075                      | Desktop     | [1d0145e3e0](https://linux-hardware.org/?probe=1d0145e3e0) | Oct 01, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [60fe11ee00](https://linux-hardware.org/?probe=60fe11ee00) | Sep 30, 2021 |
| Positivo      | Smash3                      | Notebook    | [fe185c2e3f](https://linux-hardware.org/?probe=fe185c2e3f) | Sep 29, 2021 |
| MSI           | G31TM-P25                   | Desktop     | [efe15b35ca](https://linux-hardware.org/?probe=efe15b35ca) | Sep 29, 2021 |
| Dell          | System XPS L502X            | Notebook    | [437cc938df](https://linux-hardware.org/?probe=437cc938df) | Sep 28, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [2546c78314](https://linux-hardware.org/?probe=2546c78314) | Sep 27, 2021 |
| ASRock        | A55M-HVS                    | Desktop     | [3061a2007b](https://linux-hardware.org/?probe=3061a2007b) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [171fc1cb46](https://linux-hardware.org/?probe=171fc1cb46) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [f9373d8ba5](https://linux-hardware.org/?probe=f9373d8ba5) | Sep 27, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [8e473ca843](https://linux-hardware.org/?probe=8e473ca843) | Sep 27, 2021 |
| Dell          | System XPS L502X            | Notebook    | [763d21b747](https://linux-hardware.org/?probe=763d21b747) | Sep 26, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [c94e1e1031](https://linux-hardware.org/?probe=c94e1e1031) | Sep 26, 2021 |
| HP            | Pavilion 14                 | Notebook    | [2ab5781fef](https://linux-hardware.org/?probe=2ab5781fef) | Sep 25, 2021 |
| ASRock        | A55M-HVS                    | Desktop     | [4748ccb729](https://linux-hardware.org/?probe=4748ccb729) | Sep 25, 2021 |
| ASRockRack    | EPC621D8A                   | Server      | [2244eb7809](https://linux-hardware.org/?probe=2244eb7809) | Sep 24, 2021 |
| Positivo      | Smash3                      | Notebook    | [ee8284c509](https://linux-hardware.org/?probe=ee8284c509) | Sep 24, 2021 |
| ASRock        | A55M-HVS                    | Desktop     | [a367ec462a](https://linux-hardware.org/?probe=a367ec462a) | Sep 23, 2021 |
| Fujitsu Si... | AMILO Xi 1526               | Notebook    | [aab9c46556](https://linux-hardware.org/?probe=aab9c46556) | Sep 23, 2021 |
| ASRock        | A55M-HVS                    | Desktop     | [f0081639fb](https://linux-hardware.org/?probe=f0081639fb) | Sep 22, 2021 |
| MSI           | P67A-GD65                   | Desktop     | [b23b139081](https://linux-hardware.org/?probe=b23b139081) | Sep 20, 2021 |
| MSI           | P67A-GD65                   | Desktop     | [e42a9da750](https://linux-hardware.org/?probe=e42a9da750) | Sep 20, 2021 |
| Acer          | TravelMate 5744             | Notebook    | [63142c25a5](https://linux-hardware.org/?probe=63142c25a5) | Sep 20, 2021 |
| Acer          | TravelMate 5744             | Notebook    | [0bdce8f695](https://linux-hardware.org/?probe=0bdce8f695) | Sep 20, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [8daebb1450](https://linux-hardware.org/?probe=8daebb1450) | Sep 19, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [6488569b77](https://linux-hardware.org/?probe=6488569b77) | Sep 19, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [62502d6c87](https://linux-hardware.org/?probe=62502d6c87) | Sep 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-37-generic | 15        | 16.85%  |
| 5.11.0-43-generic | 12        | 13.48%  |
| 5.11.0-40-generic | 11        | 12.36%  |
| 5.11.0-38-generic | 11        | 12.36%  |
| 5.11.0-41-generic | 10        | 11.24%  |
| 5.13.0-27-generic | 8         | 8.99%   |
| 5.11.0-36-generic | 7         | 7.87%   |
| 5.11.0-34-generic | 6         | 6.74%   |
| 5.11.0-46-generic | 5         | 5.62%   |
| 5.13.0-28-generic | 1         | 1.12%   |
| 5.13.0-25-generic | 1         | 1.12%   |
| 5.11.0-44-generic | 1         | 1.12%   |
| 5.11.0-42-generic | 1         | 1.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 74        | 88.1%   |
| 5.13.0  | 10        | 11.9%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 74        | 88.1%   |
| 5.13    | 10        | 11.9%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 84        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 79        | 92.94%  |
| KDE        | 5         | 5.88%   |
| X-Cinnamon | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 84        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 83.33%  |
| SDDM    | 14        | 16.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 19        | 22.62%  |
| pt_BR | 13        | 15.48%  |
| de_DE | 8         | 9.52%   |
| it_IT | 4         | 4.76%   |
| fr_FR | 4         | 4.76%   |
| en_GB | 4         | 4.76%   |
| C     | 4         | 4.76%   |
| pl_PL | 3         | 3.57%   |
| en_IN | 3         | 3.57%   |
| es_MX | 2         | 2.38%   |
| en_CA | 2         | 2.38%   |
| el_GR | 2         | 2.38%   |
| cs_CZ | 2         | 2.38%   |
| zh_CN | 1         | 1.19%   |
| sv_SE | 1         | 1.19%   |
| ru_UA | 1         | 1.19%   |
| ru_RU | 1         | 1.19%   |
| pt_PT | 1         | 1.19%   |
| nl_BE | 1         | 1.19%   |
| fr_CA | 1         | 1.19%   |
| fi_FI | 1         | 1.19%   |
| es_ES | 1         | 1.19%   |
| es_CO | 1         | 1.19%   |
| es_AR | 1         | 1.19%   |
| en_NG | 1         | 1.19%   |
| en_AU | 1         | 1.19%   |
| da_DK | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 59        | 70.24%  |
| EFI  | 25        | 29.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 97.62%  |
| Overlay | 2         | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 97.62%  |
| MBR     | 1         | 1.19%   |
| GPT     | 1         | 1.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 95.24%  |
| Yes       | 4         | 4.76%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 90.48%  |
| Yes       | 8         | 9.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 15.48%  |
| Dell                | 10        | 11.9%   |
| Acer                | 8         | 9.52%   |
| MSI                 | 7         | 8.33%   |
| Lenovo              | 6         | 7.14%   |
| Gigabyte Technology | 5         | 5.95%   |
| ASUSTek Computer    | 5         | 5.95%   |
| ASRock              | 5         | 5.95%   |
| Toshiba             | 3         | 3.57%   |
| Samsung Electronics | 3         | 3.57%   |
| Positivo            | 3         | 3.57%   |
| Intel               | 3         | 3.57%   |
| Pegatron            | 2         | 2.38%   |
| Google              | 2         | 2.38%   |
| Apple               | 2         | 2.38%   |
| GPU Company         | 1         | 1.19%   |
| Fujitsu Siemens     | 1         | 1.19%   |
| Fujitsu             | 1         | 1.19%   |
| Foxconn             | 1         | 1.19%   |
| ASRockRack          | 1         | 1.19%   |
| Alienware           | 1         | 1.19%   |
| ABIT                | 1         | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| HP 255 G6 Notebook PC                       | 2         | 2.38%   |
| Toshiba TECRA R850                          | 1         | 1.19%   |
| Toshiba Satellite P300                      | 1         | 1.19%   |
| Toshiba Satellite C660                      | 1         | 1.19%   |
| Samsung RV415/RV515/E3415                   | 1         | 1.19%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 1.19%   |
| Samsung RF511/RF411/RF711                   | 1         | 1.19%   |
| Positivo Smash3                             | 1         | 1.19%   |
| Positivo POS-PIQ67CG                        | 1         | 1.19%   |
| Positivo POS-EIBTPDC                        | 1         | 1.19%   |
| Pegatron p6745br                            | 1         | 1.19%   |
| Pegatron NC045AA-ABU IQ525uk                | 1         | 1.19%   |
| MSI MS-7C37                                 | 1         | 1.19%   |
| MSI MS-7B79                                 | 1         | 1.19%   |
| MSI MS-7A71                                 | 1         | 1.19%   |
| MSI MS-7752                                 | 1         | 1.19%   |
| MSI MS-7693                                 | 1         | 1.19%   |
| MSI MS-7681                                 | 1         | 1.19%   |
| MSI MS-7529                                 | 1         | 1.19%   |
| Lenovo ThinkPad L380 20M6S4E000             | 1         | 1.19%   |
| Lenovo MIIX 310-10ICR 80SG                  | 1         | 1.19%   |
| Lenovo IdeaPad Y510P 20217                  | 1         | 1.19%   |
| Lenovo G550 2958                            | 1         | 1.19%   |
| Lenovo G50-80 80R0                          | 1         | 1.19%   |
| Lenovo G50-80 80E5                          | 1         | 1.19%   |
| Intel H55                                   | 1         | 1.19%   |
| Intel DG35EC AAE29266-202                   | 1         | 1.19%   |
| Intel DESKTOP 300                           | 1         | 1.19%   |
| HP ProBook 440 G1                           | 1         | 1.19%   |
| HP Pavilion g6                              | 1         | 1.19%   |
| HP Pavilion dv6700                          | 1         | 1.19%   |
| HP Pavilion 14                              | 1         | 1.19%   |
| HP Laptop 15-bw0xx                          | 1         | 1.19%   |
| HP Laptop 14-dk1xxx                         | 1         | 1.19%   |
| HP G62                                      | 1         | 1.19%   |
| HP EliteDesk 800 G2 SFF                     | 1         | 1.19%   |
| HP EliteBook 8440p                          | 1         | 1.19%   |
| HP Compaq 6730b (NA373UC#ABA)               | 1         | 1.19%   |
| HP 700-214                                  | 1         | 1.19%   |
| GPU Company GWTN116-3                       | 1         | 1.19%   |
| Google Teemo                                | 1         | 1.19%   |
| Google Peppy                                | 1         | 1.19%   |
| Gigabyte H61M-S2PV                          | 1         | 1.19%   |
| Gigabyte GA-970A-D3                         | 1         | 1.19%   |
| Gigabyte F2A78M-D3H                         | 1         | 1.19%   |
| Gigabyte 970A-D3                            | 1         | 1.19%   |
| Gigabyte 7200-5121B                         | 1         | 1.19%   |
| Fujitsu Siemens AMILO Xi 1526               | 1         | 1.19%   |
| Fujitsu CELSIUS H700                        | 1         | 1.19%   |
| Foxconn D270S/D250S MP                      | 1         | 1.19%   |
| Dell System XPS L502X                       | 1         | 1.19%   |
| Dell Precision WorkStation 390              | 1         | 1.19%   |
| Dell Precision M6400                        | 1         | 1.19%   |
| Dell OptiPlex 3020                          | 1         | 1.19%   |
| Dell Latitude E6540                         | 1         | 1.19%   |
| Dell Latitude E6400                         | 1         | 1.19%   |
| Dell Latitude E5400                         | 1         | 1.19%   |
| Dell Inspiron N5050                         | 1         | 1.19%   |
| Dell Inspiron 3670                          | 1         | 1.19%   |
| Dell G5 5590                                | 1         | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 5         | 5.95%   |
| HP Pavilion           | 3         | 3.57%   |
| Dell Latitude         | 3         | 3.57%   |
| Toshiba Satellite     | 2         | 2.38%   |
| Lenovo G50-80         | 2         | 2.38%   |
| HP Laptop             | 2         | 2.38%   |
| HP 255                | 2         | 2.38%   |
| Dell Precision        | 2         | 2.38%   |
| Dell Inspiron         | 2         | 2.38%   |
| Toshiba TECRA         | 1         | 1.19%   |
| Samsung RV415         | 1         | 1.19%   |
| Samsung RV411         | 1         | 1.19%   |
| Samsung RF511         | 1         | 1.19%   |
| Positivo Smash3       | 1         | 1.19%   |
| Positivo POS-PIQ67CG  | 1         | 1.19%   |
| Positivo POS-EIBTPDC  | 1         | 1.19%   |
| Pegatron p6745br      | 1         | 1.19%   |
| Pegatron NC045AA-ABU  | 1         | 1.19%   |
| MSI MS-7C37           | 1         | 1.19%   |
| MSI MS-7B79           | 1         | 1.19%   |
| MSI MS-7A71           | 1         | 1.19%   |
| MSI MS-7752           | 1         | 1.19%   |
| MSI MS-7693           | 1         | 1.19%   |
| MSI MS-7681           | 1         | 1.19%   |
| MSI MS-7529           | 1         | 1.19%   |
| Lenovo ThinkPad       | 1         | 1.19%   |
| Lenovo MIIX           | 1         | 1.19%   |
| Lenovo IdeaPad        | 1         | 1.19%   |
| Lenovo G550           | 1         | 1.19%   |
| Intel H55             | 1         | 1.19%   |
| Intel DG35EC          | 1         | 1.19%   |
| Intel DESKTOP         | 1         | 1.19%   |
| HP ProBook            | 1         | 1.19%   |
| HP G62                | 1         | 1.19%   |
| HP EliteDesk          | 1         | 1.19%   |
| HP EliteBook          | 1         | 1.19%   |
| HP Compaq             | 1         | 1.19%   |
| HP 700-214            | 1         | 1.19%   |
| GPU Company GWTN116-3 | 1         | 1.19%   |
| Google Teemo          | 1         | 1.19%   |
| Google Peppy          | 1         | 1.19%   |
| Gigabyte H61M-S2PV    | 1         | 1.19%   |
| Gigabyte GA-970A-D3   | 1         | 1.19%   |
| Gigabyte F2A78M-D3H   | 1         | 1.19%   |
| Gigabyte 970A-D3      | 1         | 1.19%   |
| Gigabyte 7200-5121B   | 1         | 1.19%   |
| Fujitsu Siemens AMILO | 1         | 1.19%   |
| Fujitsu CELSIUS       | 1         | 1.19%   |
| Foxconn D270S         | 1         | 1.19%   |
| Dell System           | 1         | 1.19%   |
| Dell OptiPlex         | 1         | 1.19%   |
| Dell G5               | 1         | 1.19%   |
| ASUS N71Vg            | 1         | 1.19%   |
| ASUS M5A78L-M         | 1         | 1.19%   |
| ASUS K95VM            | 1         | 1.19%   |
| ASUS H110-PLUS        | 1         | 1.19%   |
| ASUS CM6650           | 1         | 1.19%   |
| ASRockRack EPC621D8A  | 1         | 1.19%   |
| ASRock X370           | 1         | 1.19%   |
| ASRock Q1900-ITX      | 1         | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 18        | 21.43%  |
| 2019 | 7         | 8.33%   |
| 2014 | 7         | 8.33%   |
| 2013 | 7         | 8.33%   |
| 2010 | 7         | 8.33%   |
| 2016 | 6         | 7.14%   |
| 2008 | 6         | 7.14%   |
| 2017 | 5         | 5.95%   |
| 2009 | 5         | 5.95%   |
| 2015 | 4         | 4.76%   |
| 2012 | 4         | 4.76%   |
| 2021 | 3         | 3.57%   |
| 2007 | 3         | 3.57%   |
| 2018 | 1         | 1.19%   |
| 2006 | 1         | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 45        | 53.57%  |
| Desktop    | 36        | 42.86%  |
| Tablet     | 1         | 1.19%   |
| All in one | 1         | 1.19%   |
| Server     | 1         | 1.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 80        | 95.24%  |
| Enabled  | 4         | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 97.62%  |
| Yes  | 2         | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 24        | 28.57%  |
| 8.01-16.0  | 19        | 22.62%  |
| 4.01-8.0   | 17        | 20.24%  |
| 16.01-24.0 | 10        | 11.9%   |
| 32.01-64.0 | 5         | 5.95%   |
| 1.01-2.0   | 5         | 5.95%   |
| 24.01-32.0 | 2         | 2.38%   |
| 2.01-3.0   | 2         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 42        | 48.28%  |
| 2.01-3.0  | 22        | 25.29%  |
| 3.01-4.0  | 9         | 10.34%  |
| 0.51-1.0  | 8         | 9.2%    |
| 4.01-8.0  | 4         | 4.6%    |
| 8.01-16.0 | 2         | 2.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 62.79%  |
| 2      | 22        | 25.58%  |
| 3      | 7         | 8.14%   |
| 5      | 2         | 2.33%   |
| 4      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 63.1%   |
| No        | 31        | 36.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 95.24%  |
| No        | 4         | 4.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 75.29%  |
| No        | 21        | 24.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 51.19%  |
| No        | 41        | 48.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 17        | 20.24%  |
| Brazil      | 14        | 16.67%  |
| Germany     | 8         | 9.52%   |
| Canada      | 5         | 5.95%   |
| Poland      | 4         | 4.76%   |
| Italy       | 4         | 4.76%   |
| UK          | 3         | 3.57%   |
| India       | 3         | 3.57%   |
| France      | 3         | 3.57%   |
| Mexico      | 2         | 2.38%   |
| Greece      | 2         | 2.38%   |
| Czechia     | 2         | 2.38%   |
| Ukraine     | 1         | 1.19%   |
| Sweden      | 1         | 1.19%   |
| Spain       | 1         | 1.19%   |
| Russia      | 1         | 1.19%   |
| Puerto Rico | 1         | 1.19%   |
| Portugal    | 1         | 1.19%   |
| Pakistan    | 1         | 1.19%   |
| Nigeria     | 1         | 1.19%   |
| Namibia     | 1         | 1.19%   |
| Jamaica     | 1         | 1.19%   |
| Finland     | 1         | 1.19%   |
| Denmark     | 1         | 1.19%   |
| Colombia    | 1         | 1.19%   |
| China       | 1         | 1.19%   |
| Belgium     | 1         | 1.19%   |
| Australia   | 1         | 1.19%   |
| Argentina   | 1         | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Warsaw              | 3         | 3.49%   |
| Rio de Janeiro      | 3         | 3.49%   |
| S??o Paulo          | 2         | 2.33%   |
| Campinas            | 2         | 2.33%   |
| Zaventem            | 1         | 1.16%   |
| Windhoek            | 1         | 1.16%   |
| Wabern              | 1         | 1.16%   |
| Vivian              | 1         | 1.16%   |
| Vicksburg           | 1         | 1.16%   |
| Toronto             | 1         | 1.16%   |
| Toluca              | 1         | 1.16%   |
| Stourbridge         | 1         | 1.16%   |
| Stockholm           | 1         | 1.16%   |
| Spicheren           | 1         | 1.16%   |
| Sparta              | 1         | 1.16%   |
| Shamrock            | 1         | 1.16%   |
| Senas               | 1         | 1.16%   |
| Sankt Augustin      | 1         | 1.16%   |
| Saloa               | 1         | 1.16%   |
| Rome                | 1         | 1.16%   |
| Rio das Ostras      | 1         | 1.16%   |
| Ringgold            | 1         | 1.16%   |
| Reims               | 1         | 1.16%   |
| Qu?�bec             | 1         | 1.16%   |
| Prague              | 1         | 1.16%   |
| Porto               | 1         | 1.16%   |
| Port Coquitlam      | 1         | 1.16%   |
| Patchogue           | 1         | 1.16%   |
| Oswego              | 1         | 1.16%   |
| Oshawa              | 1         | 1.16%   |
| Odense              | 1         | 1.16%   |
| Northwich           | 1         | 1.16%   |
| Niter??i            | 1         | 1.16%   |
| Newcastle upon Tyne | 1         | 1.16%   |
| Newburgh            | 1         | 1.16%   |
| Naples              | 1         | 1.16%   |
| Nanning             | 1         | 1.16%   |
| Missoula            | 1         | 1.16%   |
| Milan               | 1         | 1.16%   |
| Melbourne           | 1         | 1.16%   |
| Mandi               | 1         | 1.16%   |
| Madrid              | 1         | 1.16%   |
| Lohja               | 1         | 1.16%   |
| Lares               | 1         | 1.16%   |
| Lagos               | 1         | 1.16%   |
| Kochi               | 1         | 1.16%   |
| Kladno              | 1         | 1.16%   |
| Kingston            | 1         | 1.16%   |
| Karachi             | 1         | 1.16%   |
| Jo??o Pessoa        | 1         | 1.16%   |
| Itaperuna           | 1         | 1.16%   |
| Ingolstadt          | 1         | 1.16%   |
| Ilsede              | 1         | 1.16%   |
| Ibipitanga          | 1         | 1.16%   |
| Holmen              | 1         | 1.16%   |
| Hobart              | 1         | 1.16%   |
| Guadalajara         | 1         | 1.16%   |
| Grossenhain         | 1         | 1.16%   |
| Genoa               | 1         | 1.16%   |
| G??tersloh          | 1         | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 27     | 19.83%  |
| Seagate             | 23        | 29     | 19.83%  |
| Samsung Electronics | 10        | 10     | 8.62%   |
| Toshiba             | 9         | 9      | 7.76%   |
| SanDisk             | 7         | 7      | 6.03%   |
| Unknown             | 5         | 8      | 4.31%   |
| Crucial             | 4         | 4      | 3.45%   |
| JMicron             | 3         | 3      | 2.59%   |
| Hitachi             | 3         | 3      | 2.59%   |
| SPCC                | 2         | 2      | 1.72%   |
| PNY                 | 2         | 2      | 1.72%   |
| Patriot             | 2         | 2      | 1.72%   |
| HGST                | 2         | 2      | 1.72%   |
| A-DATA Technology   | 2         | 2      | 1.72%   |
| Transcend           | 1         | 1      | 0.86%   |
| SK Hynix            | 1         | 2      | 0.86%   |
| SATAFIRM            | 1         | 1      | 0.86%   |
| Phison              | 1         | 1      | 0.86%   |
| OCZ                 | 1         | 1      | 0.86%   |
| Micron_1            | 1         | 1      | 0.86%   |
| MAXTOR              | 1         | 1      | 0.86%   |
| LITEON              | 1         | 1      | 0.86%   |
| Lenovo              | 1         | 1      | 0.86%   |
| Kingston            | 1         | 1      | 0.86%   |
| I/OMAGIC            | 1         | 1      | 0.86%   |
| HEORIADY            | 1         | 1      | 0.86%   |
| DOGFISH             | 1         | 1      | 0.86%   |
| Apple               | 1         | 2      | 0.86%   |
| Apacer              | 1         | 2      | 0.86%   |
| AMD                 | 1         | 1      | 0.86%   |
| ALERTSEAL           | 1         | 1      | 0.86%   |
| AFOX                | 1         | 1      | 0.86%   |
| Unknown             | 1         | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  64GB              | 4         | 3.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 2.4%    |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 2.4%    |
| Toshiba MK2552GSX 250GB             | 2         | 1.6%    |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 1.6%    |
| Seagate Expansion Desk 8TB          | 2         | 1.6%    |
| SanDisk SDSSDX240GG25 240GB         | 2         | 1.6%    |
| PNY CS900 120GB SSD                 | 2         | 1.6%    |
| Patriot Burst 120GB SSD             | 2         | 1.6%    |
| Crucial CT1000MX500SSD1 1TB         | 2         | 1.6%    |
| WDC WDS500G2B0C-00PXH0 500GB        | 1         | 0.8%    |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1         | 0.8%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 0.8%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.8%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.8%    |
| WDC WDBNCE5000PNC 500GB SSD         | 1         | 0.8%    |
| WDC WD6402AAEX-00Y9A0 640GB         | 1         | 0.8%    |
| WDC WD6401AALS-00L3B2 640GB         | 1         | 0.8%    |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 0.8%    |
| WDC WD5000BPVT-60HXZT1 500GB        | 1         | 0.8%    |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 0.8%    |
| WDC WD5000AVVS-63M8B0 500GB         | 1         | 0.8%    |
| WDC WD5000AAKS-75A7B2 500GB         | 1         | 0.8%    |
| WDC WD3200BEKT-00PVMT0 320GB        | 1         | 0.8%    |
| WDC WD3200AAKS-61L9A0 320GB         | 1         | 0.8%    |
| WDC WD30EZRZ-00WN9B0 3TB            | 1         | 0.8%    |
| WDC WD30EZRX-00MMMB0 3TB            | 1         | 0.8%    |
| WDC WD2500BEVT-24A23T0 250GB        | 1         | 0.8%    |
| WDC WD20EADS-00R6B0 2TB             | 1         | 0.8%    |
| WDC WD1600JB-32FUA0 160GB           | 1         | 0.8%    |
| WDC WD1600BEVT-75ZCT1 160GB         | 1         | 0.8%    |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB            | 1         | 0.8%    |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 0.8%    |
| WDC WD1003FBYX-02A6B0 1TB           | 1         | 0.8%    |
| WDC WD1001FALS-00J7B0 1TB           | 1         | 0.8%    |
| Unknown MMC Card  7GB               | 1         | 0.8%    |
| Unknown MMC Card  32GB              | 1         | 0.8%    |
| Transcend TS32GMTS400 32GB SSD      | 1         | 0.8%    |
| Toshiba MQ04ABF100 1TB              | 1         | 0.8%    |
| Toshiba MQ01ACF032 320GB            | 1         | 0.8%    |
| Toshiba MQ01ABD075 752GB            | 1         | 0.8%    |
| Toshiba MQ01ABD050 500GB            | 1         | 0.8%    |
| Toshiba MQ01ABD032 320GB            | 1         | 0.8%    |
| Toshiba MK1656GSYF 160GB            | 1         | 0.8%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1         | 0.8%    |
| SPCC Solid State Disk 512GB         | 1         | 0.8%    |
| SPCC Solid State Disk 128GB         | 1         | 0.8%    |
| SK Hynix NVMe SSD Drive 512GB       | 1         | 0.8%    |
| SK Hynix BC511 NVMe 512GB           | 1         | 0.8%    |
| Seagate ST9250410AS 250GB           | 1         | 0.8%    |
| Seagate ST9250315AS 250GB           | 1         | 0.8%    |
| Seagate ST9160310AS 160GB           | 1         | 0.8%    |
| Seagate ST500LT012-9WS142 500GB     | 1         | 0.8%    |
| Seagate ST500DM009-2F110A 500GB     | 1         | 0.8%    |
| Seagate ST500DM002-1BD142 500GB     | 1         | 0.8%    |
| Seagate ST3750640NS 752GB           | 1         | 0.8%    |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 0.8%    |
| Seagate ST3160811AS 160GB           | 1         | 0.8%    |
| Seagate ST31000528AS 1TB            | 1         | 0.8%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 29     | 38.33%  |
| WDC                 | 18        | 21     | 30%     |
| Toshiba             | 8         | 8      | 13.33%  |
| Hitachi             | 3         | 3      | 5%      |
| Samsung Electronics | 2         | 2      | 3.33%   |
| HGST                | 2         | 2      | 3.33%   |
| SATAFIRM            | 1         | 1      | 1.67%   |
| MAXTOR              | 1         | 1      | 1.67%   |
| JMicron             | 1         | 1      | 1.67%   |
| Apple               | 1         | 2      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 7      | 17.5%   |
| Samsung Electronics | 6         | 6      | 15%     |
| WDC                 | 5         | 5      | 12.5%   |
| Crucial             | 4         | 4      | 10%     |
| SPCC                | 2         | 2      | 5%      |
| PNY                 | 2         | 2      | 5%      |
| Patriot             | 2         | 2      | 5%      |
| A-DATA Technology   | 2         | 2      | 5%      |
| Transcend           | 1         | 1      | 2.5%    |
| OCZ                 | 1         | 1      | 2.5%    |
| Micron_1            | 1         | 1      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| Kingston            | 1         | 1      | 2.5%    |
| HEORIADY            | 1         | 1      | 2.5%    |
| DOGFISH             | 1         | 1      | 2.5%    |
| Apacer              | 1         | 2      | 2.5%    |
| AMD                 | 1         | 1      | 2.5%    |
| ALERTSEAL           | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 52        | 70     | 49.52%  |
| SSD     | 36        | 41     | 34.29%  |
| NVMe    | 8         | 9      | 7.62%   |
| MMC     | 6         | 9      | 5.71%   |
| Unknown | 3         | 3      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 79        | 105    | 78.22%  |
| SAS  | 9         | 10     | 8.91%   |
| NVMe | 7         | 8      | 6.93%   |
| MMC  | 6         | 9      | 5.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 65     | 60.64%  |
| 0.51-1.0   | 28        | 37     | 29.79%  |
| 1.01-2.0   | 4         | 4      | 4.26%   |
| 4.01-10.0  | 3         | 3      | 3.19%   |
| 2.01-3.0   | 2         | 2      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 29.41%  |
| 251-500        | 19        | 22.35%  |
| 501-1000       | 14        | 16.47%  |
| 21-50          | 10        | 11.76%  |
| 51-100         | 7         | 8.24%   |
| 1001-2000      | 4         | 4.71%   |
| 1-20           | 3         | 3.53%   |
| More than 3000 | 2         | 2.35%   |
| 2001-3000      | 1         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 39        | 44.83%  |
| 1-20      | 27        | 31.03%  |
| 51-100    | 12        | 13.79%  |
| 101-250   | 5         | 5.75%   |
| 251-500   | 2         | 2.3%    |
| 2001-3000 | 2         | 2.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 82        | 128    | 96.47%  |
| Works    | 3         | 4      | 3.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 61        | 63.54%  |
| AMD                           | 15        | 15.63%  |
| Nvidia                        | 3         | 3.13%   |
| ASMedia Technology            | 3         | 3.13%   |
| Samsung Electronics           | 2         | 2.08%   |
| JMicron Technology            | 2         | 2.08%   |
| VIA Technologies              | 1         | 1.04%   |
| Toshiba America Info Systems  | 1         | 1.04%   |
| SK Hynix                      | 1         | 1.04%   |
| Silicon Image                 | 1         | 1.04%   |
| Sandisk                       | 1         | 1.04%   |
| Promise Technology            | 1         | 1.04%   |
| Phison Electronics            | 1         | 1.04%   |
| Marvell Technology Group      | 1         | 1.04%   |
| Lenovo                        | 1         | 1.04%   |
| Integrated Technology Express | 1         | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 7.63%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 5.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 4.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 4.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 3.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 2.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 2.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 2.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 2.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 2.54%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.69%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.69%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 1.69%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.85%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.85%   |
| SK Hynix BC511                                                                          | 1         | 0.85%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.85%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.85%   |
| Promise PDC20262 (FastTrak66/Ultra66)                                                   | 1         | 0.85%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.85%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.85%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.85%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1         | 0.85%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1         | 0.85%   |
| Lenovo Non-Volatile memory controller                                                   | 1         | 0.85%   |
| JMicron JMB368 IDE controller                                                           | 1         | 0.85%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 0.85%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.85%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 1         | 0.85%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 1         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.85%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1         | 0.85%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1         | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 0.85%   |
| Integrated Express IT8212 Dual channel ATA RAID controller                              | 1         | 0.85%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1         | 0.85%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 64        | 64.65%  |
| IDE  | 21        | 21.21%  |
| RAID | 7         | 7.07%   |
| NVMe | 7         | 7.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 79.76%  |
| AMD    | 17        | 20.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 3         | 3.57%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 2         | 2.38%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 2.38%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 2         | 2.38%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 2.38%   |
| AMD FX-8350 Eight-Core Processor             | 2         | 2.38%   |
| AMD A6-9220 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 2.38%   |
| Intel Xeon Platinum 8171M CPU @ 2.60GHz      | 1         | 1.19%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 1.19%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 1.19%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz       | 1         | 1.19%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 1.19%   |
| Intel Core i7-7700 CPU @ 3.60GHz             | 1         | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1         | 1.19%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 1.19%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 1.19%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 1.19%   |
| Intel Core i7-2820QM CPU @ 2.30GHz           | 1         | 1.19%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 1.19%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 1         | 1.19%   |
| Intel Core i5-9400 CPU @ 2.90GHz             | 1         | 1.19%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 1         | 1.19%   |
| Intel Core i5-7400 CPU @ 3.00GHz             | 1         | 1.19%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 1.19%   |
| Intel Core i5-4440 CPU @ 3.10GHz             | 1         | 1.19%   |
| Intel Core i5-3570K CPU @ 3.40GHz            | 1         | 1.19%   |
| Intel Core i5-3570 CPU @ 3.40GHz             | 1         | 1.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1         | 1.19%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 1.19%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 1.19%   |
| Intel Core i5-2310 CPU @ 2.90GHz             | 1         | 1.19%   |
| Intel Core i5-2300 CPU @ 2.80GHz             | 1         | 1.19%   |
| Intel Core i5 CPU 650 @ 3.20GHz              | 1         | 1.19%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 1.19%   |
| Intel Core i3-4160 CPU @ 3.60GHz             | 1         | 1.19%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 1         | 1.19%   |
| Intel Core i3-2350M CPU @ 2.30GHz            | 1         | 1.19%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 1         | 1.19%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 1         | 1.19%   |
| Intel Core i3 CPU M 350 @ 2.27GHz            | 1         | 1.19%   |
| Intel Core i3 CPU M 330 @ 2.13GHz            | 1         | 1.19%   |
| Intel Core i3 CPU 530 @ 2.93GHz              | 1         | 1.19%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz        | 1         | 1.19%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1         | 1.19%   |
| Intel Core 2 Extreme CPU Q9300 @ 2.53GHz     | 1         | 1.19%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 1         | 1.19%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz         | 1         | 1.19%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz         | 1         | 1.19%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz         | 1         | 1.19%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz         | 1         | 1.19%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz         | 1         | 1.19%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz         | 1         | 1.19%   |
| Intel Core 2 CPU T5500 @ 1.66GHz             | 1         | 1.19%   |
| Intel Core 2 CPU 4300 @ 1.80GHz              | 1         | 1.19%   |
| Intel Celeron N4020 CPU @ 1.10GHz            | 1         | 1.19%   |
| Intel Celeron Dual-Core CPU T3500 @ 2.10GHz  | 1         | 1.19%   |
| Intel Celeron CPU J1900 @ 1.99GHz            | 1         | 1.19%   |
| Intel Celeron CPU J1800 @ 2.41GHz            | 1         | 1.19%   |
| Intel Celeron CPU 3215U @ 1.70GHz            | 1         | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 22.62%  |
| Intel Core i7           | 10        | 11.9%   |
| Intel Core 2 Duo        | 10        | 11.9%   |
| Intel Core i3           | 9         | 10.71%  |
| Intel Celeron           | 5         | 5.95%   |
| Intel Atom              | 4         | 4.76%   |
| AMD FX                  | 4         | 4.76%   |
| Intel Pentium Dual      | 2         | 2.38%   |
| Intel Core 2 Quad       | 2         | 2.38%   |
| Intel Core 2            | 2         | 2.38%   |
| AMD Ryzen 5             | 2         | 2.38%   |
| AMD A6                  | 2         | 2.38%   |
| Intel Xeon Platinum     | 1         | 1.19%   |
| Intel Pentium Dual-Core | 1         | 1.19%   |
| Intel Core 2 Extreme    | 1         | 1.19%   |
| Intel Celeron Dual-Core | 1         | 1.19%   |
| AMD Ryzen 7             | 1         | 1.19%   |
| AMD Phenom II X4        | 1         | 1.19%   |
| AMD Phenom II X2        | 1         | 1.19%   |
| AMD E2                  | 1         | 1.19%   |
| AMD E                   | 1         | 1.19%   |
| AMD Athlon II X2        | 1         | 1.19%   |
| AMD Athlon              | 1         | 1.19%   |
| AMD A8                  | 1         | 1.19%   |
| AMD A10                 | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 48        | 57.14%  |
| 4      | 28        | 33.33%  |
| 6      | 4         | 4.76%   |
| 3      | 2         | 2.38%   |
| 26     | 1         | 1.19%   |
| 8      | 1         | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 84        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 54.76%  |
| 2      | 38        | 45.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 84        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 11        | 13.1%   |
| 0x206a7    | 9         | 10.71%  |
| 0x306a9    | 5         | 5.95%   |
| 0x306c3    | 4         | 4.76%   |
| 0x20652    | 4         | 4.76%   |
| 0x6fd      | 3         | 3.57%   |
| 0x506e3    | 3         | 3.57%   |
| 0x06000852 | 3         | 3.57%   |
| 0x010000c8 | 3         | 3.57%   |
| Unknown    | 3         | 3.57%   |
| 0x906e9    | 2         | 2.38%   |
| 0x406c4    | 2         | 2.38%   |
| 0x40651    | 2         | 2.38%   |
| 0x306d4    | 2         | 2.38%   |
| 0x30678    | 2         | 2.38%   |
| 0x20655    | 2         | 2.38%   |
| 0x10676    | 2         | 2.38%   |
| 0x06006705 | 2         | 2.38%   |
| 0x906ed    | 1         | 1.19%   |
| 0x906ea    | 1         | 1.19%   |
| 0x806ea    | 1         | 1.19%   |
| 0x806e9    | 1         | 1.19%   |
| 0x706a8    | 1         | 1.19%   |
| 0x6fb      | 1         | 1.19%   |
| 0x6f6      | 1         | 1.19%   |
| 0x6f2      | 1         | 1.19%   |
| 0x50654    | 1         | 1.19%   |
| 0x30673    | 1         | 1.19%   |
| 0x30661    | 1         | 1.19%   |
| 0x106e5    | 1         | 1.19%   |
| 0x08701021 | 1         | 1.19%   |
| 0x08108109 | 1         | 1.19%   |
| 0x08001138 | 1         | 1.19%   |
| 0x06006704 | 1         | 1.19%   |
| 0x06001119 | 1         | 1.19%   |
| 0x0600063e | 1         | 1.19%   |
| 0x05000119 | 1         | 1.19%   |
| 0x03000027 | 1         | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 13        | 15.48%  |
| SandyBridge   | 9         | 10.71%  |
| Haswell       | 8         | 9.52%   |
| Westmere      | 6         | 7.14%   |
| KabyLake      | 6         | 7.14%   |
| Core          | 6         | 7.14%   |
| Silvermont    | 5         | 5.95%   |
| IvyBridge     | 5         | 5.95%   |
| Skylake       | 4         | 4.76%   |
| Piledriver    | 4         | 4.76%   |
| K10           | 3         | 3.57%   |
| Excavator     | 3         | 3.57%   |
| Zen 2         | 2         | 2.38%   |
| Broadwell     | 2         | 2.38%   |
| Zen+          | 1         | 1.19%   |
| Zen           | 1         | 1.19%   |
| Nehalem       | 1         | 1.19%   |
| K10 Llano     | 1         | 1.19%   |
| Goldmont plus | 1         | 1.19%   |
| Bulldozer     | 1         | 1.19%   |
| Bonnell       | 1         | 1.19%   |
| Bobcat        | 1         | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 49.48%  |
| Nvidia | 29        | 29.9%   |
| AMD    | 20        | 20.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 7.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 7.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 6.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 3.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 3.06%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.04%   |
| Intel HD Graphics 530                                                                    | 2         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 2.04%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 2.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.02%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 1.02%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.02%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.02%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 1.02%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.02%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 1.02%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.02%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1         | 1.02%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.02%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.02%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 1.02%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.02%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1         | 1.02%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 1.02%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1         | 1.02%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.02%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.02%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.02%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 1.02%   |
| Nvidia G96CM [GeForce GT 220M]                                                           | 1         | 1.02%   |
| Nvidia G96CM [GeForce 9600M GS]                                                          | 1         | 1.02%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.02%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 1.02%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.02%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.02%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.02%   |
| Intel HD Graphics 630                                                                    | 1         | 1.02%   |
| Intel HD Graphics 620                                                                    | 1         | 1.02%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.02%   |
| Intel HD Graphics                                                                        | 1         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.02%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.02%   |
| Intel 82G35 Express Integrated Graphics Controller                                       | 1         | 1.02%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.02%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.02%   |
| AMD Sumo [Radeon HD 6550D]                                                               | 1         | 1.02%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.02%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 1.02%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 1         | 1.02%   |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 41.67%  |
| 1 x Nvidia     | 20        | 23.81%  |
| 1 x AMD        | 18        | 21.43%  |
| Intel + Nvidia | 9         | 10.71%  |
| Intel + AMD    | 2         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 72        | 85.71%  |
| Proprietary | 6         | 7.14%   |
| Unknown     | 6         | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 48.81%  |
| 0.51-1.0   | 13        | 15.48%  |
| 0.01-0.5   | 11        | 13.1%   |
| 1.01-2.0   | 9         | 10.71%  |
| 3.01-4.0   | 4         | 4.76%   |
| 2.01-3.0   | 3         | 3.57%   |
| 5.01-6.0   | 2         | 2.38%   |
| 7.01-8.0   | 1         | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 19.23%  |
| LG Display              | 12        | 15.38%  |
| AU Optronics            | 8         | 10.26%  |
| Ancor Communications    | 6         | 7.69%   |
| Goldstar                | 4         | 5.13%   |
| Dell                    | 4         | 5.13%   |
| Philips                 | 3         | 3.85%   |
| Hewlett-Packard         | 3         | 3.85%   |
| Chimei Innolux          | 3         | 3.85%   |
| AOC                     | 3         | 3.85%   |
| LG Philips              | 2         | 2.56%   |
| Apple                   | 2         | 2.56%   |
| Acer                    | 2         | 2.56%   |
| ___                     | 1         | 1.28%   |
| ViewSonic               | 1         | 1.28%   |
| Tech Concepts           | 1         | 1.28%   |
| PANDA                   | 1         | 1.28%   |
| Microstep               | 1         | 1.28%   |
| Lenovo                  | 1         | 1.28%   |
| Insignia                | 1         | 1.28%   |
| Chi Mei Optoelectronics | 1         | 1.28%   |
| BOE                     | 1         | 1.28%   |
| BenQ                    | 1         | 1.28%   |
| Unknown                 | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch      | 2         | 2.5%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 2         | 2.5%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch             | 2         | 2.5%    |
| ___ AAA ___01FF 1366x768 700x390mm 31.5-inch                              | 1         | 1.25%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch             | 1         | 1.25%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                                | 1         | 1.25%   |
| Samsung Electronics T24C310 SAM0AEA 1920x1080 531x299mm 24.0-inch         | 1         | 1.25%   |
| Samsung Electronics SMT22A550 SAM07AE 1920x1080 477x268mm 21.5-inch       | 1         | 1.25%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch         | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch      | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch      | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x170mm 13.9-inch      | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768                          | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                          | 1         | 1.25%   |
| Samsung Electronics LCD Monitor S24B300 3840x1080                         | 1         | 1.25%   |
| Philips PHL 241P4 PHL08D5 1920x1080 531x299mm 24.0-inch                   | 1         | 1.25%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch                 | 1         | 1.25%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                        | 1         | 1.25%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                   | 1         | 1.25%   |
| Microstep LCD Monitor MSI MAG341CQ 3440x1440                              | 1         | 1.25%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch               | 1         | 1.25%   |
| LG Philips LCD Monitor LPL012B 1280x800 304x190mm 14.1-inch               | 1         | 1.25%   |
| LG Display LCD Monitor LGD7001 1366x768 344x194mm 15.5-inch               | 1         | 1.25%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch              | 1         | 1.25%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch               | 1         | 1.25%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch               | 1         | 1.25%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch               | 1         | 1.25%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.25%   |
| LG Display LCD Monitor LGD02D9 1920x1080 345x194mm 15.6-inch              | 1         | 1.25%   |
| LG Display LCD Monitor LGD02A6 1366x768 345x194mm 15.6-inch               | 1         | 1.25%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch               | 1         | 1.25%   |
| LG Display LCD Monitor LGD01AF 1680x1050 331x207mm 15.4-inch              | 1         | 1.25%   |
| LG Display LCD Monitor LGD018E 1920x1200 367x230mm 17.1-inch              | 1         | 1.25%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                   | 1         | 1.25%   |
| Insignia NS28D310NA15 BBY0028 1680x1050 640x384mm 29.4-inch               | 1         | 1.25%   |
| Hewlett-Packard v185e HWP2838 1366x768 410x230mm 18.5-inch                | 1         | 1.25%   |
| Hewlett-Packard LCD Monitor w2338h                                        | 1         | 1.25%   |
| Hewlett-Packard Compaq W185q HWP284F 1366x768 410x230mm 18.5-inch         | 1         | 1.25%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                      | 1         | 1.25%   |
| Goldstar RZ32LZ55 GSM7546 1360x768 930x523mm 42.0-inch                    | 1         | 1.25%   |
| Goldstar M237WDP GSM5778 1920x1080 510x290mm 23.1-inch                    | 1         | 1.25%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                       | 1         | 1.25%   |
| Goldstar 32LG7000 GSM765E 1920x1080 700x390mm 31.5-inch                   | 1         | 1.25%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                     | 1         | 1.25%   |
| Dell E2216HV DELF06F 1920x1080 476x268mm 21.5-inch                        | 1         | 1.25%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                          | 1         | 1.25%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch                  | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 309x173mm 13.9-inch           | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 1         | 1.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1808 1920x1080 408x230mm 18.4-inch | 1         | 1.25%   |
| BOE LCD Monitor BOE097F 1366x768 256x144mm 11.6-inch                      | 1         | 1.25%   |
| BenQ FP71V BNQ76A2 1280x1024 376x301mm 19.0-inch                          | 1         | 1.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 1         | 1.25%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 1         | 1.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 1         | 1.25%   |
| AU Optronics LCD Monitor AUO162C 1366x768 293x164mm 13.2-inch             | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 27        | 35.53%  |
| 1920x1080 (FHD)    | 20        | 26.32%  |
| 3840x2160 (4K)     | 5         | 6.58%   |
| 1600x900 (HD+)     | 4         | 5.26%   |
| 1440x900 (WXGA+)   | 4         | 5.26%   |
| 1680x1050 (WSXGA+) | 3         | 3.95%   |
| 1360x768           | 3         | 3.95%   |
| 1280x800 (WXGA)    | 3         | 3.95%   |
| 1920x1200 (WUXGA)  | 2         | 2.63%   |
| 3840x1080          | 1         | 1.32%   |
| 3440x1440          | 1         | 1.32%   |
| 1280x720 (HD)      | 1         | 1.32%   |
| 1280x1024 (SXGA)   | 1         | 1.32%   |
| Unknown            | 1         | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 29.49%  |
| 17      | 8         | 10.26%  |
| 27      | 6         | 7.69%   |
| 24      | 6         | 7.69%   |
| 31      | 5         | 6.41%   |
| 21      | 5         | 6.41%   |
| 18      | 5         | 6.41%   |
| 14      | 4         | 5.13%   |
| Unknown | 4         | 5.13%   |
| 13      | 3         | 3.85%   |
| 23      | 2         | 2.56%   |
| 22      | 2         | 2.56%   |
| 19      | 2         | 2.56%   |
| 11      | 2         | 2.56%   |
| 42      | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 36.84%  |
| 401-500     | 13        | 17.11%  |
| 501-600     | 11        | 14.47%  |
| 351-400     | 9         | 11.84%  |
| 601-700     | 6         | 7.89%   |
| 201-300     | 4         | 5.26%   |
| Unknown     | 4         | 5.26%   |
| 901-1000    | 1         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 55        | 74.32%  |
| 16/10   | 13        | 17.57%  |
| Unknown | 4         | 5.41%   |
| 5/4     | 2         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 29.87%  |
| 201-250        | 10        | 12.99%  |
| 301-350        | 6         | 7.79%   |
| 141-150        | 6         | 7.79%   |
| 81-90          | 5         | 6.49%   |
| 351-500        | 5         | 6.49%   |
| 131-140        | 5         | 6.49%   |
| 151-200        | 4         | 5.19%   |
| Unknown        | 4         | 5.19%   |
| 71-80          | 2         | 2.6%    |
| 51-60          | 2         | 2.6%    |
| 251-300        | 2         | 2.6%    |
| 121-130        | 2         | 2.6%    |
| 501-1000       | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 28        | 37.33%  |
| 101-120 | 27        | 36%     |
| 121-160 | 10        | 13.33%  |
| 1-50    | 5         | 6.67%   |
| Unknown | 4         | 5.33%   |
| 161-240 | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 86.9%   |
| 2     | 6         | 7.14%   |
| 0     | 4         | 4.76%   |
| 3     | 1         | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 54        | 39.13%  |
| Intel                           | 29        | 21.01%  |
| Qualcomm Atheros                | 14        | 10.14%  |
| Broadcom                        | 13        | 9.42%   |
| Broadcom Limited                | 7         | 5.07%   |
| Ralink                          | 4         | 2.9%    |
| Nvidia                          | 3         | 2.17%   |
| TP-Link                         | 2         | 1.45%   |
| Samsung Electronics             | 2         | 1.45%   |
| Marvell Technology Group        | 2         | 1.45%   |
| Toshiba                         | 1         | 0.72%   |
| Ralink Technology               | 1         | 0.72%   |
| Qualcomm Atheros Communications | 1         | 0.72%   |
| Motorola PCS                    | 1         | 0.72%   |
| MediaTek                        | 1         | 0.72%   |
| Lenovo                          | 1         | 0.72%   |
| Huawei Technologies             | 1         | 0.72%   |
| D-Link                          | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 38        | 24.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 8         | 5.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 4         | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.92%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 1.92%   |
| Intel 82579V Gigabit Network Connection                                                       | 3         | 1.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 3         | 1.92%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2         | 1.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1.28%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 1.28%   |
| Nvidia MCP61 Ethernet                                                                         | 2         | 1.28%   |
| Intel Wireless 3160                                                                           | 2         | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.28%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 1.28%   |
| Intel 82577LM Gigabit Network Connection                                                      | 2         | 1.28%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                                     | 2         | 1.28%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 0.64%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 0.64%   |
| Toshiba F5521gw                                                                               | 1         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.64%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.64%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 0.64%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.64%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1         | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1         | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 0.64%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.64%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                                              | 1         | 0.64%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.64%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1         | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 1         | 0.64%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1         | 0.64%   |
| Nvidia MCP79 Ethernet                                                                         | 1         | 0.64%   |
| Motorola PCS Moto G (4)                                                                       | 1         | 0.64%   |
| MediaTek 802.11 n WLAN                                                                        | 1         | 0.64%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.64%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                                         | 1         | 0.64%   |
| Lenovo Thinkpad USB LAN                                                                       | 1         | 0.64%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 0.64%   |
| Intel Wireless 7265                                                                           | 1         | 0.64%   |
| Intel Wireless 7260                                                                           | 1         | 0.64%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.64%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 0.64%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 0.64%   |
| Intel I211 Gigabit Network Connection                                                         | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 30.43%  |
| Realtek Semiconductor           | 14        | 20.29%  |
| Qualcomm Atheros                | 11        | 15.94%  |
| Broadcom                        | 11        | 15.94%  |
| Ralink                          | 4         | 5.8%    |
| TP-Link                         | 2         | 2.9%    |
| Broadcom Limited                | 2         | 2.9%    |
| Ralink Technology               | 1         | 1.45%   |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| MediaTek                        | 1         | 1.45%   |
| D-Link                          | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 4         | 5.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 4.35%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 4.35%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 3         | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 2.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 2.9%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 2.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 2.9%    |
| Intel Wireless 3160                                                                           | 2         | 2.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 2.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.9%    |
| Intel Centrino Advanced-N 6200                                                                | 2         | 2.9%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 1.45%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 1.45%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 1.45%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 1.45%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1         | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 1.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.45%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 1.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.45%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.45%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1         | 1.45%   |
| MediaTek 802.11 n WLAN                                                                        | 1         | 1.45%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.45%   |
| Intel Wireless 7265                                                                           | 1         | 1.45%   |
| Intel Wireless 7260                                                                           | 1         | 1.45%   |
| Intel WiFi Link 5100                                                                          | 1         | 1.45%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 1.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.45%   |
| Intel Centrino Wireless-N 2230                                                                | 1         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                                                | 1         | 1.45%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                                 | 1         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.45%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1         | 1.45%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.45%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.45%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                   | 1         | 1.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1         | 1.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 1         | 1.45%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 56.47%  |
| Intel                    | 13        | 15.29%  |
| Broadcom Limited         | 5         | 5.88%   |
| Broadcom                 | 5         | 5.88%   |
| Qualcomm Atheros         | 4         | 4.71%   |
| Nvidia                   | 3         | 3.53%   |
| Samsung Electronics      | 2         | 2.35%   |
| Marvell Technology Group | 2         | 2.35%   |
| Motorola PCS             | 1         | 1.18%   |
| Lenovo                   | 1         | 1.18%   |
| Huawei Technologies      | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 44.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 9.3%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 3.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.33%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.33%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 2.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.16%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.16%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.16%   |
| Motorola PCS Moto G (4)                                           | 1         | 1.16%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.16%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 1.16%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 1.16%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.16%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.16%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.16%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.16%   |
| Intel 82566DC Gigabit Network Connection                          | 1         | 1.16%   |
| Huawei E353/E3131                                                 | 1         | 1.16%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.16%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.16%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.16%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.16%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.16%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1         | 1.16%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.16%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 80        | 55.17%  |
| WiFi     | 64        | 44.14%  |
| Modem    | 1         | 0.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 77        | 58.33%  |
| WiFi     | 55        | 41.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 52        | 61.9%   |
| 1     | 27        | 32.14%  |
| 0     | 4         | 4.76%   |
| 4     | 1         | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 64.29%  |
| Yes  | 30        | 35.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 30.23%  |
| Cambridge Silicon Radio         | 6         | 13.95%  |
| Qualcomm Atheros Communications | 3         | 6.98%   |
| Hewlett-Packard                 | 3         | 6.98%   |
| Dell                            | 3         | 6.98%   |
| Realtek Semiconductor           | 2         | 4.65%   |
| Lite-On Technology              | 2         | 4.65%   |
| Foxconn / Hon Hai               | 2         | 4.65%   |
| Broadcom                        | 2         | 4.65%   |
| ASUSTek Computer                | 2         | 4.65%   |
| Apple                           | 2         | 4.65%   |
| Toshiba                         | 1         | 2.33%   |
| Ralink                          | 1         | 2.33%   |
| Askey Computer                  | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 7         | 16.28%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 13.95%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 4.65%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 4.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 4.65%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.33%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.33%   |
| Lite-On Atheros Bluetooth                           | 1         | 2.33%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.33%   |
| Intel Bluetooth wireless interface                  | 1         | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.33%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 2.33%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.33%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 2.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.33%   |
| Askey Bluetooth Device                              | 1         | 2.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.33%   |
| Apple Bluetooth Host Controller                     | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 60        | 49.18%  |
| AMD                       | 24        | 19.67%  |
| Nvidia                    | 23        | 18.85%  |
| C-Media Electronics       | 4         | 3.28%   |
| GN Netcom                 | 2         | 1.64%   |
| Texas Instruments         | 1         | 0.82%   |
| Sennheiser Communications | 1         | 0.82%   |
| Realtek Semiconductor     | 1         | 0.82%   |
| Microsoft                 | 1         | 0.82%   |
| M-Audio                   | 1         | 0.82%   |
| JMTek                     | 1         | 0.82%   |
| iSoft Silicon             | 1         | 0.82%   |
| Creative Labs             | 1         | 0.82%   |
| AOKEO                     | 1         | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 7.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 7.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 4.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 2.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 2.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.14%   |
| AMD High Definition Audio Controller                                       | 3         | 2.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 2.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 2.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.43%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.43%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.43%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.43%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.43%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.43%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 1.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.43%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.43%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.43%   |
| Texas Instruments PCM2903B Audio CODEC                                     | 1         | 0.71%   |
| Sennheiser Communications PXC 550                                          | 1         | 0.71%   |
| Realtek Semiconductor Realtek USB audio                                    | 1         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.71%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.71%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.71%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.71%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.71%   |
| Microsoft LifeChat LX-3000 Headset                                         | 1         | 0.71%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 0.71%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.71%   |
| iSoft Silicon USB Ear-Microphone                                           | 1         | 0.71%   |
| Intel Lewisburg MROM 0                                                     | 1         | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.71%   |
| GN Netcom Jabra Link 380                                                   | 1         | 0.71%   |
| GN Netcom enc060:Buttons Volume up/down/mute + phone [Jabra]               | 1         | 0.71%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 0.71%   |
| C-Media Electronics Blue Snowball                                          | 1         | 0.71%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 0.71%   |
| AOKEO LCS_USB_Audio                                                        | 1         | 0.71%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                            | 1         | 0.71%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1         | 0.71%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 33.33%  |
| Kingston            | 2         | 33.33%  |
| Unknown             | 1         | 16.67%  |
| Corsair             | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 533MT/s              | 1         | 14.29%  |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s              | 1         | 14.29%  |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 1         | 14.29%  |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 14.29%  |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 1         | 14.29%  |
| Kingston RAM 9905428-020.A00LF 4096MB SODIMM DDR3 1067MT/s | 1         | 14.29%  |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 1         | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 2         | 40%     |
| DDR3 | 2         | 40%     |
| DDR2 | 1         | 20%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 4         | 80%     |
| DIMM   | 1         | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 2         | 33.33%  |
| 16384 | 1         | 16.67%  |
| 8192  | 1         | 16.67%  |
| 2048  | 1         | 16.67%  |
| 1024  | 1         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3600  | 1         | 16.67%  |
| 2667  | 1         | 16.67%  |
| 1600  | 1         | 16.67%  |
| 1334  | 1         | 16.67%  |
| 1067  | 1         | 16.67%  |
| 533   | 1         | 16.67%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L395 Series  | 1         | 50%     |
| Canon PIXMA MX920 Series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 21.57%  |
| Silicon Motion                         | 5         | 9.8%    |
| Acer                                   | 4         | 7.84%   |
| Quanta                                 | 3         | 5.88%   |
| Microdia                               | 3         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.88%   |
| Suyin                                  | 2         | 3.92%   |
| Sunplus Innovation Technology          | 2         | 3.92%   |
| Ricoh                                  | 2         | 3.92%   |
| Microsoft                              | 2         | 3.92%   |
| Logitech                               | 2         | 3.92%   |
| Apple                                  | 2         | 3.92%   |
| YGTek                                  | 1         | 1.96%   |
| USB2.0 Webcamera                       | 1         | 1.96%   |
| Syntek                                 | 1         | 1.96%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 1.96%   |
| Samsung Electronics                    | 1         | 1.96%   |
| Realtek Semiconductor                  | 1         | 1.96%   |
| Primax Electronics                     | 1         | 1.96%   |
| PC-LM1E                                | 1         | 1.96%   |
| Jieli Technology                       | 1         | 1.96%   |
| Creative Technology                    | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus HD WebCam                                   | 2         | 3.92%   |
| Quanta HP Webcam                                    | 2         | 3.92%   |
| Chicony HD WebCam                                   | 2         | 3.92%   |
| Chicony CNF9055 Toshiba Webcam                      | 2         | 3.92%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 2         | 3.92%   |
| Acer Lenovo EasyCamera                              | 2         | 3.92%   |
| YGTek Webcam                                        | 1         | 1.96%   |
| USB2.0 Webcamera USB2.0 Webcamera                   | 1         | 1.96%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.96%   |
| Suyin UVC HD Webcam                                 | 1         | 1.96%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.96%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 1.96%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 1.96%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.96%   |
| Silicon Motion SM731 Camera                         | 1         | 1.96%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.96%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960      | 1         | 1.96%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 1.96%   |
| Ricoh Laptop_Integrated_Webcam_3M                   | 1         | 1.96%   |
| Ricoh Integrated Webcam                             | 1         | 1.96%   |
| Realtek USB Camera                                  | 1         | 1.96%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 1.96%   |
| Primax HP Webcam-101                                | 1         | 1.96%   |
| PC-LM1E PC-LM1E                                     | 1         | 1.96%   |
| Microsoft LifeCam VX-5000                           | 1         | 1.96%   |
| Microsoft LifeCam VX-500 [1357]                     | 1         | 1.96%   |
| Microdia Lenovo EasyCamera                          | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.96%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.96%   |
| Logitech Webcam C600                                | 1         | 1.96%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 1.96%   |
| Jieli USB PHY 2.0                                   | 1         | 1.96%   |
| Creative Live! Cam Sync HD [VF0770]                 | 1         | 1.96%   |
| Chicony USB 2.0 Camera                              | 1         | 1.96%   |
| Chicony HP Webcam                                   | 1         | 1.96%   |
| Chicony HP TrueVision HD Camera                     | 1         | 1.96%   |
| Chicony FJ Camera                                   | 1         | 1.96%   |
| Chicony CNF7042                                     | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 1.96%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 1.96%   |
| Apple Built-in iSight                               | 1         | 1.96%   |
| Acer SunplusIT Integrated Camera                    | 1         | 1.96%   |
| Acer Crystal Eye webcam                             | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS451 Fingerprint Reader | 1         | 33.33%  |
| AuthenTec Fingerprint Sensor               | 1         | 33.33%  |
| AuthenTec AES2550 Fingerprint Sensor       | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 59        | 70.24%  |
| 1     | 21        | 25%     |
| 2     | 4         | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 10        | 37.04%  |
| Net/wireless          | 6         | 22.22%  |
| Fingerprint reader    | 3         | 11.11%  |
| Storage               | 2         | 7.41%   |
| Multimedia controller | 2         | 7.41%   |
| Chipcard              | 2         | 7.41%   |
| Unassigned class      | 1         | 3.7%    |
| Bluetooth             | 1         | 3.7%    |


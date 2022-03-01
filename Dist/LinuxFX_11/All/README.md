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
| ASUSTek       | PRIME A320M-K               | Desktop     | [65b41a7a67](https://linux-hardware.org/?probe=65b41a7a67) | Feb 26, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [f3ec55a392](https://linux-hardware.org/?probe=f3ec55a392) | Feb 25, 2022 |
| Positivo      | Smash                       | Notebook    | [68fd957c2e](https://linux-hardware.org/?probe=68fd957c2e) | Feb 21, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [2ef0397f90](https://linux-hardware.org/?probe=2ef0397f90) | Feb 20, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [33c341d85e](https://linux-hardware.org/?probe=33c341d85e) | Feb 20, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| ASUSTek       | X751LAB                     | Notebook    | [10ea8f6500](https://linux-hardware.org/?probe=10ea8f6500) | Feb 17, 2022 |
| HP            | Compaq CQ45                 | Notebook    | [51144497b2](https://linux-hardware.org/?probe=51144497b2) | Feb 16, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [a3ebde02ae](https://linux-hardware.org/?probe=a3ebde02ae) | Feb 15, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [b7696b0129](https://linux-hardware.org/?probe=b7696b0129) | Feb 14, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [504bb820fe](https://linux-hardware.org/?probe=504bb820fe) | Feb 14, 2022 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [bd77a66760](https://linux-hardware.org/?probe=bd77a66760) | Feb 12, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [75ee9c8a17](https://linux-hardware.org/?probe=75ee9c8a17) | Feb 10, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [d849fe0859](https://linux-hardware.org/?probe=d849fe0859) | Feb 10, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [403c9202cf](https://linux-hardware.org/?probe=403c9202cf) | Feb 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [85d1f4fe0a](https://linux-hardware.org/?probe=85d1f4fe0a) | Feb 09, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [6942d0b7dc](https://linux-hardware.org/?probe=6942d0b7dc) | Feb 07, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [cc840b5085](https://linux-hardware.org/?probe=cc840b5085) | Feb 05, 2022 |
| HP            | ProBook 4720s               | Notebook    | [aa5c35966f](https://linux-hardware.org/?probe=aa5c35966f) | Feb 04, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [175d1e66d3](https://linux-hardware.org/?probe=175d1e66d3) | Feb 02, 2022 |
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
| 5.11.0-37-generic | 15        | 14.85%  |
| 5.11.0-43-generic | 12        | 11.88%  |
| 5.11.0-40-generic | 11        | 10.89%  |
| 5.11.0-38-generic | 11        | 10.89%  |
| 5.11.0-41-generic | 10        | 9.9%    |
| 5.13.0-28-generic | 9         | 8.91%   |
| 5.13.0-27-generic | 8         | 7.92%   |
| 5.11.0-36-generic | 7         | 6.93%   |
| 5.11.0-34-generic | 6         | 5.94%   |
| 5.11.0-46-generic | 5         | 4.95%   |
| 5.13.0-30-generic | 4         | 3.96%   |
| 5.13.0-25-generic | 1         | 0.99%   |
| 5.11.0-44-generic | 1         | 0.99%   |
| 5.11.0-42-generic | 1         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 74        | 77.08%  |
| 5.13.0  | 22        | 22.92%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 74        | 77.08%  |
| 5.13    | 22        | 22.92%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 95        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 90        | 93.75%  |
| KDE        | 5         | 5.21%   |
| X-Cinnamon | 1         | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 94        | 98.95%  |
| Wayland | 1         | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 80        | 84.21%  |
| SDDM    | 15        | 15.79%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 22        | 23.16%  |
| pt_BR | 14        | 14.74%  |
| de_DE | 9         | 9.47%   |
| fr_FR | 6         | 6.32%   |
| it_IT | 4         | 4.21%   |
| en_GB | 4         | 4.21%   |
| C     | 4         | 4.21%   |
| pl_PL | 3         | 3.16%   |
| en_IN | 3         | 3.16%   |
| en_AU | 3         | 3.16%   |
| es_MX | 2         | 2.11%   |
| en_CA | 2         | 2.11%   |
| el_GR | 2         | 2.11%   |
| cs_CZ | 2         | 2.11%   |
| zh_CN | 1         | 1.05%   |
| sv_SE | 1         | 1.05%   |
| ru_UA | 1         | 1.05%   |
| ru_RU | 1         | 1.05%   |
| pt_PT | 1         | 1.05%   |
| nl_NL | 1         | 1.05%   |
| nl_BE | 1         | 1.05%   |
| fr_CA | 1         | 1.05%   |
| fi_FI | 1         | 1.05%   |
| es_HN | 1         | 1.05%   |
| es_ES | 1         | 1.05%   |
| es_CO | 1         | 1.05%   |
| es_AR | 1         | 1.05%   |
| en_NG | 1         | 1.05%   |
| da_DK | 1         | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 65        | 68.42%  |
| EFI  | 30        | 31.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 93        | 97.89%  |
| Overlay | 2         | 2.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 92        | 96.84%  |
| GPT     | 2         | 2.11%   |
| MBR     | 1         | 1.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 94.74%  |
| Yes       | 5         | 5.26%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 91.58%  |
| Yes       | 8         | 8.42%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 15.79%  |
| Dell                | 12        | 12.63%  |
| Acer                | 9         | 9.47%   |
| ASUSTek Computer    | 8         | 8.42%   |
| MSI                 | 7         | 7.37%   |
| Lenovo              | 6         | 6.32%   |
| Gigabyte Technology | 5         | 5.26%   |
| ASRock              | 5         | 5.26%   |
| Samsung Electronics | 4         | 4.21%   |
| Positivo            | 4         | 4.21%   |
| Intel               | 4         | 4.21%   |
| Toshiba             | 3         | 3.16%   |
| Pegatron            | 2         | 2.11%   |
| Google              | 2         | 2.11%   |
| Apple               | 2         | 2.11%   |
| GPU Company         | 1         | 1.05%   |
| Fujitsu Siemens     | 1         | 1.05%   |
| Fujitsu             | 1         | 1.05%   |
| Foxconn             | 1         | 1.05%   |
| ASRockRack          | 1         | 1.05%   |
| Alienware           | 1         | 1.05%   |
| ABIT                | 1         | 1.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP 255 G6 Notebook PC                                                                    | 2         | 2.11%   |
| Toshiba TECRA R850                                                                       | 1         | 1.05%   |
| Toshiba Satellite P300                                                                   | 1         | 1.05%   |
| Toshiba Satellite C660                                                                   | 1         | 1.05%   |
| Samsung RV415/RV515/E3415                                                                | 1         | 1.05%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411                                              | 1         | 1.05%   |
| Samsung RF511/RF411/RF711                                                                | 1         | 1.05%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.05%   |
| Positivo Smash3                                                                          | 1         | 1.05%   |
| Positivo Smash                                                                           | 1         | 1.05%   |
| Positivo POS-PIQ67CG                                                                     | 1         | 1.05%   |
| Positivo POS-EIBTPDC                                                                     | 1         | 1.05%   |
| Pegatron p6745br                                                                         | 1         | 1.05%   |
| Pegatron NC045AA-ABU IQ525uk                                                             | 1         | 1.05%   |
| MSI MS-7C37                                                                              | 1         | 1.05%   |
| MSI MS-7B79                                                                              | 1         | 1.05%   |
| MSI MS-7A71                                                                              | 1         | 1.05%   |
| MSI MS-7752                                                                              | 1         | 1.05%   |
| MSI MS-7693                                                                              | 1         | 1.05%   |
| MSI MS-7681                                                                              | 1         | 1.05%   |
| MSI MS-7529                                                                              | 1         | 1.05%   |
| Lenovo ThinkPad L380 20M6S4E000                                                          | 1         | 1.05%   |
| Lenovo MIIX 310-10ICR 80SG                                                               | 1         | 1.05%   |
| Lenovo IdeaPad Y510P 20217                                                               | 1         | 1.05%   |
| Lenovo G550 2958                                                                         | 1         | 1.05%   |
| Lenovo G50-80 80R0                                                                       | 1         | 1.05%   |
| Lenovo G50-80 80E5                                                                       | 1         | 1.05%   |
| Intel H55                                                                                | 1         | 1.05%   |
| Intel DP55WB AAE64798-205                                                                | 1         | 1.05%   |
| Intel DG35EC AAE29266-202                                                                | 1         | 1.05%   |
| Intel DESKTOP 300                                                                        | 1         | 1.05%   |
| HP ProBook 4720s                                                                         | 1         | 1.05%   |
| HP ProBook 440 G1                                                                        | 1         | 1.05%   |
| HP Pavilion g6                                                                           | 1         | 1.05%   |
| HP Pavilion dv6700                                                                       | 1         | 1.05%   |
| HP Pavilion 14                                                                           | 1         | 1.05%   |
| HP Laptop 15-bw0xx                                                                       | 1         | 1.05%   |
| HP Laptop 14-dk1xxx                                                                      | 1         | 1.05%   |
| HP G62                                                                                   | 1         | 1.05%   |
| HP EliteDesk 800 G2 SFF                                                                  | 1         | 1.05%   |
| HP EliteBook 8440p                                                                       | 1         | 1.05%   |
| HP Compaq CQ45                                                                           | 1         | 1.05%   |
| HP Compaq 6730b (NA373UC#ABA)                                                            | 1         | 1.05%   |
| HP 700-214                                                                               | 1         | 1.05%   |
| GPU Company GWTN116-3                                                                    | 1         | 1.05%   |
| Google Teemo                                                                             | 1         | 1.05%   |
| Google Peppy                                                                             | 1         | 1.05%   |
| Gigabyte H61M-S2PV                                                                       | 1         | 1.05%   |
| Gigabyte GA-970A-D3                                                                      | 1         | 1.05%   |
| Gigabyte F2A78M-D3H                                                                      | 1         | 1.05%   |
| Gigabyte 970A-D3                                                                         | 1         | 1.05%   |
| Gigabyte 7200-5121B                                                                      | 1         | 1.05%   |
| Fujitsu Siemens AMILO Xi 1526                                                            | 1         | 1.05%   |
| Fujitsu CELSIUS H700                                                                     | 1         | 1.05%   |
| Foxconn D270S/D250S MP                                                                   | 1         | 1.05%   |
| Dell System XPS L502X                                                                    | 1         | 1.05%   |
| Dell Precision WorkStation 390                                                           | 1         | 1.05%   |
| Dell Precision M6400                                                                     | 1         | 1.05%   |
| Dell OptiPlex 3050                                                                       | 1         | 1.05%   |
| Dell OptiPlex 3020                                                                       | 1         | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 6         | 6.32%   |
| Dell Latitude         | 4         | 4.21%   |
| HP Pavilion           | 3         | 3.16%   |
| Toshiba Satellite     | 2         | 2.11%   |
| Lenovo G50-80         | 2         | 2.11%   |
| HP ProBook            | 2         | 2.11%   |
| HP Laptop             | 2         | 2.11%   |
| HP Compaq             | 2         | 2.11%   |
| HP 255                | 2         | 2.11%   |
| Dell Precision        | 2         | 2.11%   |
| Dell OptiPlex         | 2         | 2.11%   |
| Dell Inspiron         | 2         | 2.11%   |
| Toshiba TECRA         | 1         | 1.05%   |
| Samsung RV415         | 1         | 1.05%   |
| Samsung RV411         | 1         | 1.05%   |
| Samsung RF511         | 1         | 1.05%   |
| Samsung 355V4C        | 1         | 1.05%   |
| Positivo Smash3       | 1         | 1.05%   |
| Positivo Smash        | 1         | 1.05%   |
| Positivo POS-PIQ67CG  | 1         | 1.05%   |
| Positivo POS-EIBTPDC  | 1         | 1.05%   |
| Pegatron p6745br      | 1         | 1.05%   |
| Pegatron NC045AA-ABU  | 1         | 1.05%   |
| MSI MS-7C37           | 1         | 1.05%   |
| MSI MS-7B79           | 1         | 1.05%   |
| MSI MS-7A71           | 1         | 1.05%   |
| MSI MS-7752           | 1         | 1.05%   |
| MSI MS-7693           | 1         | 1.05%   |
| MSI MS-7681           | 1         | 1.05%   |
| MSI MS-7529           | 1         | 1.05%   |
| Lenovo ThinkPad       | 1         | 1.05%   |
| Lenovo MIIX           | 1         | 1.05%   |
| Lenovo IdeaPad        | 1         | 1.05%   |
| Lenovo G550           | 1         | 1.05%   |
| Intel H55             | 1         | 1.05%   |
| Intel DP55WB          | 1         | 1.05%   |
| Intel DG35EC          | 1         | 1.05%   |
| Intel DESKTOP         | 1         | 1.05%   |
| HP G62                | 1         | 1.05%   |
| HP EliteDesk          | 1         | 1.05%   |
| HP EliteBook          | 1         | 1.05%   |
| HP 700-214            | 1         | 1.05%   |
| GPU Company GWTN116-3 | 1         | 1.05%   |
| Google Teemo          | 1         | 1.05%   |
| Google Peppy          | 1         | 1.05%   |
| Gigabyte H61M-S2PV    | 1         | 1.05%   |
| Gigabyte GA-970A-D3   | 1         | 1.05%   |
| Gigabyte F2A78M-D3H   | 1         | 1.05%   |
| Gigabyte 970A-D3      | 1         | 1.05%   |
| Gigabyte 7200-5121B   | 1         | 1.05%   |
| Fujitsu Siemens AMILO | 1         | 1.05%   |
| Fujitsu CELSIUS       | 1         | 1.05%   |
| Foxconn D270S         | 1         | 1.05%   |
| Dell System           | 1         | 1.05%   |
| Dell G5               | 1         | 1.05%   |
| ASUS X751LAB          | 1         | 1.05%   |
| ASUS PRIME            | 1         | 1.05%   |
| ASUS P7H55-M          | 1         | 1.05%   |
| ASUS N71Vg            | 1         | 1.05%   |
| ASUS M5A78L-M         | 1         | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 19        | 20%     |
| 2010 | 9         | 9.47%   |
| 2019 | 8         | 8.42%   |
| 2017 | 7         | 7.37%   |
| 2014 | 7         | 7.37%   |
| 2013 | 7         | 7.37%   |
| 2009 | 7         | 7.37%   |
| 2016 | 6         | 6.32%   |
| 2012 | 6         | 6.32%   |
| 2008 | 6         | 6.32%   |
| 2015 | 5         | 5.26%   |
| 2021 | 3         | 3.16%   |
| 2007 | 3         | 3.16%   |
| 2018 | 1         | 1.05%   |
| 2006 | 1         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 52        | 54.74%  |
| Desktop    | 40        | 42.11%  |
| Tablet     | 1         | 1.05%   |
| All in one | 1         | 1.05%   |
| Server     | 1         | 1.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 90        | 94.74%  |
| Enabled  | 5         | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 93        | 97.89%  |
| Yes  | 2         | 2.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 26        | 27.37%  |
| 4.01-8.0   | 22        | 23.16%  |
| 8.01-16.0  | 21        | 22.11%  |
| 16.01-24.0 | 12        | 12.63%  |
| 32.01-64.0 | 5         | 5.26%   |
| 1.01-2.0   | 5         | 5.26%   |
| 24.01-32.0 | 2         | 2.11%   |
| 2.01-3.0   | 2         | 2.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 50        | 51.02%  |
| 2.01-3.0  | 24        | 24.49%  |
| 3.01-4.0  | 9         | 9.18%   |
| 0.51-1.0  | 9         | 9.18%   |
| 4.01-8.0  | 4         | 4.08%   |
| 8.01-16.0 | 2         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 61        | 62.89%  |
| 2      | 23        | 23.71%  |
| 3      | 8         | 8.25%   |
| 4      | 3         | 3.09%   |
| 5      | 2         | 2.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 66.32%  |
| No        | 32        | 33.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 94.74%  |
| No        | 5         | 5.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 73.96%  |
| No        | 25        | 26.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 50.53%  |
| Yes       | 47        | 49.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 19        | 20%     |
| Brazil      | 15        | 15.79%  |
| Germany     | 9         | 9.47%   |
| France      | 5         | 5.26%   |
| Canada      | 5         | 5.26%   |
| Poland      | 4         | 4.21%   |
| Italy       | 4         | 4.21%   |
| UK          | 3         | 3.16%   |
| India       | 3         | 3.16%   |
| Australia   | 3         | 3.16%   |
| Mexico      | 2         | 2.11%   |
| Greece      | 2         | 2.11%   |
| Czechia     | 2         | 2.11%   |
| Ukraine     | 1         | 1.05%   |
| Sweden      | 1         | 1.05%   |
| Spain       | 1         | 1.05%   |
| Serbia      | 1         | 1.05%   |
| Russia      | 1         | 1.05%   |
| Puerto Rico | 1         | 1.05%   |
| Portugal    | 1         | 1.05%   |
| Pakistan    | 1         | 1.05%   |
| Nigeria     | 1         | 1.05%   |
| Netherlands | 1         | 1.05%   |
| Namibia     | 1         | 1.05%   |
| Jamaica     | 1         | 1.05%   |
| Honduras    | 1         | 1.05%   |
| Finland     | 1         | 1.05%   |
| Denmark     | 1         | 1.05%   |
| Colombia    | 1         | 1.05%   |
| China       | 1         | 1.05%   |
| Belgium     | 1         | 1.05%   |
| Argentina   | 1         | 1.05%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Rio de Janeiro      | 4         | 4.12%   |
| Warsaw              | 3         | 3.09%   |
| SÃ£o Paulo        | 2         | 2.06%   |
| Hobart              | 2         | 2.06%   |
| Campinas            | 2         | 2.06%   |
| Zaventem            | 1         | 1.03%   |
| Windhoek            | 1         | 1.03%   |
| Wabern              | 1         | 1.03%   |
| Vivian              | 1         | 1.03%   |
| Vicksburg           | 1         | 1.03%   |
| Toronto             | 1         | 1.03%   |
| Toluca              | 1         | 1.03%   |
| Tegucigalpa         | 1         | 1.03%   |
| Stourbridge         | 1         | 1.03%   |
| Stockholm           | 1         | 1.03%   |
| Spicheren           | 1         | 1.03%   |
| Sparta              | 1         | 1.03%   |
| Shamrock            | 1         | 1.03%   |
| Senas               | 1         | 1.03%   |
| Sankt Augustin      | 1         | 1.03%   |
| Salt Lake City      | 1         | 1.03%   |
| Saloa               | 1         | 1.03%   |
| Rome                | 1         | 1.03%   |
| Rio das Ostras      | 1         | 1.03%   |
| Ringgold            | 1         | 1.03%   |
| Reims               | 1         | 1.03%   |
| QuÃ©bec           | 1         | 1.03%   |
| Prague              | 1         | 1.03%   |
| Porto               | 1         | 1.03%   |
| Port Coquitlam      | 1         | 1.03%   |
| Patchogue           | 1         | 1.03%   |
| Oswego              | 1         | 1.03%   |
| Oshawa              | 1         | 1.03%   |
| Odense              | 1         | 1.03%   |
| Novi Karlovci       | 1         | 1.03%   |
| Northwich           | 1         | 1.03%   |
| North Plains        | 1         | 1.03%   |
| NiterÃ³i          | 1         | 1.03%   |
| Newcastle upon Tyne | 1         | 1.03%   |
| Newburgh            | 1         | 1.03%   |
| Naples              | 1         | 1.03%   |
| Nanning             | 1         | 1.03%   |
| Missoula            | 1         | 1.03%   |
| Milan               | 1         | 1.03%   |
| Melbourne           | 1         | 1.03%   |
| Mandi               | 1         | 1.03%   |
| Madrid              | 1         | 1.03%   |
| Lutjegast           | 1         | 1.03%   |
| Lohja               | 1         | 1.03%   |
| Lares               | 1         | 1.03%   |
| Lagos               | 1         | 1.03%   |
| Kochi               | 1         | 1.03%   |
| Kladno              | 1         | 1.03%   |
| Kingston            | 1         | 1.03%   |
| Karachi             | 1         | 1.03%   |
| JoÃ£o Pessoa      | 1         | 1.03%   |
| Itaperuna           | 1         | 1.03%   |
| Ingolstadt          | 1         | 1.03%   |
| Ilsede              | 1         | 1.03%   |
| Ibipitanga          | 1         | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 34     | 18.94%  |
| WDC                 | 24        | 28     | 18.18%  |
| Samsung Electronics | 12        | 12     | 9.09%   |
| Toshiba             | 11        | 11     | 8.33%   |
| SanDisk             | 10        | 10     | 7.58%   |
| Unknown             | 6         | 10     | 4.55%   |
| Crucial             | 5         | 6      | 3.79%   |
| PNY                 | 3         | 3      | 2.27%   |
| Kingston            | 3         | 3      | 2.27%   |
| JMicron             | 3         | 3      | 2.27%   |
| Hitachi             | 3         | 3      | 2.27%   |
| Transcend           | 2         | 2      | 1.52%   |
| SPCC                | 2         | 2      | 1.52%   |
| Patriot             | 2         | 2      | 1.52%   |
| HGST                | 2         | 2      | 1.52%   |
| A-DATA Technology   | 2         | 2      | 1.52%   |
| SK Hynix            | 1         | 2      | 0.76%   |
| SATAFIRM            | 1         | 1      | 0.76%   |
| Phison              | 1         | 1      | 0.76%   |
| OCZ                 | 1         | 1      | 0.76%   |
| Micron_1            | 1         | 2      | 0.76%   |
| MAXTOR              | 1         | 1      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| Lenovo              | 1         | 1      | 0.76%   |
| I/OMAGIC            | 1         | 1      | 0.76%   |
| HEORIADY            | 1         | 1      | 0.76%   |
| DOGFISH             | 1         | 1      | 0.76%   |
| Apple               | 1         | 2      | 0.76%   |
| Apacer              | 1         | 2      | 0.76%   |
| AMD                 | 1         | 1      | 0.76%   |
| ALERTSEAL           | 1         | 1      | 0.76%   |
| AFOX                | 1         | 1      | 0.76%   |
| Unknown             | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  64GB              | 4         | 2.8%    |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 2.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 2.1%    |
| SanDisk SDSSDX240GG25 240GB         | 3         | 2.1%    |
| Toshiba MK2552GSX 250GB             | 2         | 1.4%    |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 1.4%    |
| Seagate Expansion Desk 8TB          | 2         | 1.4%    |
| Samsung NVMe SSD Drive 500GB        | 2         | 1.4%    |
| PNY CS900 120GB SSD                 | 2         | 1.4%    |
| Patriot Burst 120GB SSD             | 2         | 1.4%    |
| Kingston SA400S37240G 240GB SSD     | 2         | 1.4%    |
| Crucial CT1000MX500SSD1 1TB         | 2         | 1.4%    |
| WDC WDS500G2B0C-00PXH0 500GB        | 1         | 0.7%    |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1         | 0.7%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.7%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.7%    |
| WDC WDBNCE5000PNC 500GB SSD         | 1         | 0.7%    |
| WDC WD6402AAEX-00Y9A0 640GB         | 1         | 0.7%    |
| WDC WD6401AALS-00L3B2 640GB         | 1         | 0.7%    |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 0.7%    |
| WDC WD5000BPVT-60HXZT1 500GB        | 1         | 0.7%    |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 0.7%    |
| WDC WD5000AVVS-63M8B0 500GB         | 1         | 0.7%    |
| WDC WD5000AAKS-75A7B2 500GB         | 1         | 0.7%    |
| WDC WD3200BEKT-00PVMT0 320GB        | 1         | 0.7%    |
| WDC WD3200AAKS-61L9A0 320GB         | 1         | 0.7%    |
| WDC WD30EZRZ-00WN9B0 3TB            | 1         | 0.7%    |
| WDC WD30EZRX-00MMMB0 3TB            | 1         | 0.7%    |
| WDC WD2500BEVT-24A23T0 250GB        | 1         | 0.7%    |
| WDC WD20EADS-00R6B0 2TB             | 1         | 0.7%    |
| WDC WD1600JB-32FUA0 160GB           | 1         | 0.7%    |
| WDC WD1600BEVT-75ZCT1 160GB         | 1         | 0.7%    |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB            | 1         | 0.7%    |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 0.7%    |
| WDC WD10EADS-22M2B0 1TB             | 1         | 0.7%    |
| WDC WD1003FBYX-02A6B0 1TB           | 1         | 0.7%    |
| WDC WD1001FALS-00J7B0 1TB           | 1         | 0.7%    |
| Unknown SD  128GB                   | 1         | 0.7%    |
| Unknown MMC Card  7GB               | 1         | 0.7%    |
| Unknown MMC Card  32GB              | 1         | 0.7%    |
| Unknown BJTD4R  32GB                | 1         | 0.7%    |
| Transcend TS32GMTS400 32GB SSD      | 1         | 0.7%    |
| Transcend TS128GSSD360S 128GB       | 1         | 0.7%    |
| Toshiba MQ04ABF100 1TB              | 1         | 0.7%    |
| Toshiba MQ01ACF032 320GB            | 1         | 0.7%    |
| Toshiba MQ01ABF032 320GB            | 1         | 0.7%    |
| Toshiba MQ01ABD100 1TB              | 1         | 0.7%    |
| Toshiba MQ01ABD075 752GB            | 1         | 0.7%    |
| Toshiba MQ01ABD050 500GB            | 1         | 0.7%    |
| Toshiba MQ01ABD032 320GB            | 1         | 0.7%    |
| Toshiba MK1656GSYF 160GB            | 1         | 0.7%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1         | 0.7%    |
| SPCC Solid State Disk 512GB         | 1         | 0.7%    |
| SPCC Solid State Disk 128GB         | 1         | 0.7%    |
| SK Hynix NVMe SSD Drive 512GB       | 1         | 0.7%    |
| SK Hynix BC511 NVMe 512GB           | 1         | 0.7%    |
| Seagate ST9250410AS 250GB           | 1         | 0.7%    |
| Seagate ST9250315AS 250GB           | 1         | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 34     | 38.46%  |
| WDC                 | 19        | 22     | 29.23%  |
| Toshiba             | 10        | 10     | 15.38%  |
| Hitachi             | 3         | 3      | 4.62%   |
| Samsung Electronics | 2         | 2      | 3.08%   |
| HGST                | 2         | 2      | 3.08%   |
| SATAFIRM            | 1         | 1      | 1.54%   |
| MAXTOR              | 1         | 1      | 1.54%   |
| JMicron             | 1         | 1      | 1.54%   |
| Apple               | 1         | 2      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 9         | 9      | 18.75%  |
| Samsung Electronics | 7         | 7      | 14.58%  |
| WDC                 | 5         | 5      | 10.42%  |
| Crucial             | 5         | 6      | 10.42%  |
| PNY                 | 3         | 3      | 6.25%   |
| Kingston            | 3         | 3      | 6.25%   |
| Transcend           | 2         | 2      | 4.17%   |
| SPCC                | 2         | 2      | 4.17%   |
| Patriot             | 2         | 2      | 4.17%   |
| A-DATA Technology   | 2         | 2      | 4.17%   |
| OCZ                 | 1         | 1      | 2.08%   |
| Micron_1            | 1         | 2      | 2.08%   |
| LITEON              | 1         | 1      | 2.08%   |
| HEORIADY            | 1         | 1      | 2.08%   |
| DOGFISH             | 1         | 1      | 2.08%   |
| Apacer              | 1         | 2      | 2.08%   |
| AMD                 | 1         | 1      | 2.08%   |
| ALERTSEAL           | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 57        | 78     | 48.31%  |
| SSD     | 41        | 51     | 34.75%  |
| NVMe    | 10        | 11     | 8.47%   |
| MMC     | 7         | 11     | 5.93%   |
| Unknown | 3         | 3      | 2.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 122    | 77.88%  |
| SAS  | 9         | 11     | 7.96%   |
| NVMe | 9         | 10     | 7.96%   |
| MMC  | 7         | 11     | 6.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 76     | 60.38%  |
| 0.51-1.0   | 31        | 41     | 29.25%  |
| 1.01-2.0   | 6         | 7      | 5.66%   |
| 4.01-10.0  | 3         | 3      | 2.83%   |
| 2.01-3.0   | 2         | 2      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 30.21%  |
| 251-500        | 21        | 21.88%  |
| 501-1000       | 16        | 16.67%  |
| 21-50          | 12        | 12.5%   |
| 51-100         | 8         | 8.33%   |
| 1001-2000      | 4         | 4.17%   |
| 1-20           | 3         | 3.13%   |
| More than 3000 | 2         | 2.08%   |
| 2001-3000      | 1         | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 46        | 46.94%  |
| 1-20      | 29        | 29.59%  |
| 51-100    | 12        | 12.24%  |
| 101-250   | 7         | 7.14%   |
| 251-500   | 2         | 2.04%   |
| 2001-3000 | 2         | 2.04%   |

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
| Detected | 93        | 150    | 96.88%  |
| Works    | 3         | 4      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 68        | 62.39%  |
| AMD                           | 18        | 16.51%  |
| Samsung Electronics           | 3         | 2.75%   |
| Nvidia                        | 3         | 2.75%   |
| JMicron Technology            | 3         | 2.75%   |
| ASMedia Technology            | 3         | 2.75%   |
| Sandisk                       | 2         | 1.83%   |
| VIA Technologies              | 1         | 0.92%   |
| Toshiba America Info Systems  | 1         | 0.92%   |
| SK Hynix                      | 1         | 0.92%   |
| Silicon Image                 | 1         | 0.92%   |
| Promise Technology            | 1         | 0.92%   |
| Phison Electronics            | 1         | 0.92%   |
| Marvell Technology Group      | 1         | 0.92%   |
| Lenovo                        | 1         | 0.92%   |
| Integrated Technology Express | 1         | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 7.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 6.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 3.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 2.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.27%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 1.52%   |
| JMicron JMB368 IDE controller                                                           | 2         | 1.52%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.52%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 1.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.52%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.76%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.76%   |
| SK Hynix BC511                                                                          | 1         | 0.76%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.76%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.76%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.76%   |
| Promise PDC20262 (FastTrak66/Ultra66)                                                   | 1         | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.76%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.76%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1         | 0.76%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1         | 0.76%   |
| Lenovo Non-Volatile memory controller                                                   | 1         | 0.76%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.76%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 1         | 0.76%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 1         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.76%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1         | 0.76%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1         | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.76%   |
| Integrated Express IT8212 Dual channel ATA RAID controller                              | 1         | 0.76%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 64.29%  |
| IDE  | 22        | 19.64%  |
| RAID | 9         | 8.04%   |
| NVMe | 9         | 8.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 75        | 78.95%  |
| AMD    | 20        | 21.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 3         | 3.16%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 3         | 3.16%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 2         | 2.11%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 2.11%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 2         | 2.11%   |
| Intel Core i3 CPU M 350 @ 2.27GHz            | 2         | 2.11%   |
| AMD FX-8350 Eight-Core Processor             | 2         | 2.11%   |
| AMD A6-9220 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 2.11%   |
| Intel Xeon Platinum 8171M CPU @ 2.60GHz      | 1         | 1.05%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 1.05%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 1.05%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz       | 1         | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 1.05%   |
| Intel Core i7-7700 CPU @ 3.60GHz             | 1         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 1         | 1.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1         | 1.05%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 1.05%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 1.05%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 1.05%   |
| Intel Core i7-2820QM CPU @ 2.30GHz           | 1         | 1.05%   |
| Intel Core i7-2620M CPU @ 2.70GHz            | 1         | 1.05%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 1.05%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 1         | 1.05%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1         | 1.05%   |
| Intel Core i5-9400 CPU @ 2.90GHz             | 1         | 1.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 1         | 1.05%   |
| Intel Core i5-7400 CPU @ 3.00GHz             | 1         | 1.05%   |
| Intel Core i5-6500T CPU @ 2.50GHz            | 1         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 1.05%   |
| Intel Core i5-4440 CPU @ 3.10GHz             | 1         | 1.05%   |
| Intel Core i5-3570K CPU @ 3.40GHz            | 1         | 1.05%   |
| Intel Core i5-3570 CPU @ 3.40GHz             | 1         | 1.05%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1         | 1.05%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 1.05%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 1.05%   |
| Intel Core i5-2310 CPU @ 2.90GHz             | 1         | 1.05%   |
| Intel Core i5-2300 CPU @ 2.80GHz             | 1         | 1.05%   |
| Intel Core i5 CPU M 430 @ 2.27GHz            | 1         | 1.05%   |
| Intel Core i5 CPU 650 @ 3.20GHz              | 1         | 1.05%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 1.05%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 1.05%   |
| Intel Core i3-4160 CPU @ 3.60GHz             | 1         | 1.05%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 1         | 1.05%   |
| Intel Core i3-2350M CPU @ 2.30GHz            | 1         | 1.05%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 1         | 1.05%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 1         | 1.05%   |
| Intel Core i3 CPU M 330 @ 2.13GHz            | 1         | 1.05%   |
| Intel Core i3 CPU 540 @ 3.07GHz              | 1         | 1.05%   |
| Intel Core i3 CPU 530 @ 2.93GHz              | 1         | 1.05%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz        | 1         | 1.05%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1         | 1.05%   |
| Intel Core 2 Extreme CPU Q9300 @ 2.53GHz     | 1         | 1.05%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 1         | 1.05%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz         | 1         | 1.05%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz         | 1         | 1.05%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz         | 1         | 1.05%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz         | 1         | 1.05%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz         | 1         | 1.05%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz         | 1         | 1.05%   |
| Intel Core 2 CPU T5500 @ 1.66GHz             | 1         | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 22.11%  |
| Intel Core i7           | 12        | 12.63%  |
| Intel Core i3           | 12        | 12.63%  |
| Intel Core 2 Duo        | 10        | 10.53%  |
| Intel Celeron           | 5         | 5.26%   |
| Intel Atom              | 5         | 5.26%   |
| AMD FX                  | 4         | 4.21%   |
| AMD Ryzen 5             | 3         | 3.16%   |
| AMD A6                  | 3         | 3.16%   |
| Intel Pentium Dual      | 2         | 2.11%   |
| Intel Core 2 Quad       | 2         | 2.11%   |
| Intel Core 2            | 2         | 2.11%   |
| AMD E                   | 2         | 2.11%   |
| Intel Xeon Platinum     | 1         | 1.05%   |
| Intel Pentium Dual-Core | 1         | 1.05%   |
| Intel Core 2 Extreme    | 1         | 1.05%   |
| Intel Celeron Dual-Core | 1         | 1.05%   |
| AMD Ryzen 7             | 1         | 1.05%   |
| AMD Phenom II X4        | 1         | 1.05%   |
| AMD Phenom II X2        | 1         | 1.05%   |
| AMD E2                  | 1         | 1.05%   |
| AMD Athlon II X2        | 1         | 1.05%   |
| AMD Athlon              | 1         | 1.05%   |
| AMD A8                  | 1         | 1.05%   |
| AMD A10                 | 1         | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 56.84%  |
| 4      | 32        | 33.68%  |
| 6      | 4         | 4.21%   |
| 3      | 2         | 2.11%   |
| 26     | 1         | 1.05%   |
| 8      | 1         | 1.05%   |
| 1      | 1         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 51.58%  |
| 2      | 46        | 48.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 95        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 11        | 11.58%  |
| 0x206a7    | 10        | 10.53%  |
| 0x20652    | 6         | 6.32%   |
| 0x306a9    | 5         | 5.26%   |
| 0x506e3    | 4         | 4.21%   |
| 0x306c3    | 4         | 4.21%   |
| 0x6fd      | 3         | 3.16%   |
| 0x406c4    | 3         | 3.16%   |
| 0x306d4    | 3         | 3.16%   |
| 0x20655    | 3         | 3.16%   |
| 0x06000852 | 3         | 3.16%   |
| 0x010000c8 | 3         | 3.16%   |
| Unknown    | 3         | 3.16%   |
| 0x906e9    | 2         | 2.11%   |
| 0x40651    | 2         | 2.11%   |
| 0x30678    | 2         | 2.11%   |
| 0x106e5    | 2         | 2.11%   |
| 0x10676    | 2         | 2.11%   |
| 0x06006705 | 2         | 2.11%   |
| 0x06001119 | 2         | 2.11%   |
| 0x05000119 | 2         | 2.11%   |
| 0x906ed    | 1         | 1.05%   |
| 0x906ea    | 1         | 1.05%   |
| 0x806ea    | 1         | 1.05%   |
| 0x806e9    | 1         | 1.05%   |
| 0x706a8    | 1         | 1.05%   |
| 0x6fb      | 1         | 1.05%   |
| 0x6f6      | 1         | 1.05%   |
| 0x6f2      | 1         | 1.05%   |
| 0x50654    | 1         | 1.05%   |
| 0x30673    | 1         | 1.05%   |
| 0x30661    | 1         | 1.05%   |
| 0x08701021 | 1         | 1.05%   |
| 0x08108109 | 1         | 1.05%   |
| 0x08101016 | 1         | 1.05%   |
| 0x08001138 | 1         | 1.05%   |
| 0x06006704 | 1         | 1.05%   |
| 0x0600063e | 1         | 1.05%   |
| 0x03000027 | 1         | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 13        | 13.68%  |
| SandyBridge   | 10        | 10.53%  |
| Westmere      | 9         | 9.47%   |
| Haswell       | 8         | 8.42%   |
| Silvermont    | 6         | 6.32%   |
| KabyLake      | 6         | 6.32%   |
| Core          | 6         | 6.32%   |
| Skylake       | 5         | 5.26%   |
| Piledriver    | 5         | 5.26%   |
| IvyBridge     | 5         | 5.26%   |
| K10           | 3         | 3.16%   |
| Excavator     | 3         | 3.16%   |
| Broadwell     | 3         | 3.16%   |
| Zen 2         | 2         | 2.11%   |
| Zen           | 2         | 2.11%   |
| Nehalem       | 2         | 2.11%   |
| Bobcat        | 2         | 2.11%   |
| Zen+          | 1         | 1.05%   |
| K10 Llano     | 1         | 1.05%   |
| Goldmont plus | 1         | 1.05%   |
| Bulldozer     | 1         | 1.05%   |
| Bonnell       | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 48.62%  |
| Nvidia | 32        | 29.36%  |
| AMD    | 24        | 22.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 7.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 6.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 6.31%   |
| Intel HD Graphics 530                                                                    | 3         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.8%    |
| Intel HD Graphics 5500                                                                   | 2         | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.8%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.8%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 1.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.9%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.9%    |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.9%    |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.9%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.9%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.9%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.9%    |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.9%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.9%    |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1         | 0.9%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.9%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.9%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.9%    |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1         | 0.9%    |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 0.9%    |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1         | 0.9%    |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.9%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.9%    |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.9%    |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.9%    |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.9%    |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.9%    |
| Nvidia G96CM [GeForce GT 220M]                                                           | 1         | 0.9%    |
| Nvidia G96CM [GeForce 9600M GS]                                                          | 1         | 0.9%    |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 0.9%    |
| Nvidia G92 [GeForce GTS 250]                                                             | 1         | 0.9%    |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.9%    |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.9%    |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.9%    |
| Intel UHD Graphics 620                                                                   | 1         | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.9%    |
| Intel HD Graphics 630                                                                    | 1         | 0.9%    |
| Intel HD Graphics 620                                                                    | 1         | 0.9%    |
| Intel HD Graphics                                                                        | 1         | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 0.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.9%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.9%    |
| Intel 82G35 Express Integrated Graphics Controller                                       | 1         | 0.9%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.9%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.9%    |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 0.9%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 41.05%  |
| 1 x Nvidia     | 22        | 23.16%  |
| 1 x AMD        | 21        | 22.11%  |
| Intel + Nvidia | 10        | 10.53%  |
| Intel + AMD    | 2         | 2.11%   |
| 2 x AMD        | 1         | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 82        | 86.32%  |
| Proprietary | 7         | 7.37%   |
| Unknown     | 6         | 6.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 47.37%  |
| 0.51-1.0   | 15        | 15.79%  |
| 0.01-0.5   | 15        | 15.79%  |
| 1.01-2.0   | 10        | 10.53%  |
| 3.01-4.0   | 4         | 4.21%   |
| 2.01-3.0   | 3         | 3.16%   |
| 5.01-6.0   | 2         | 2.11%   |
| 7.01-8.0   | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 18.68%  |
| LG Display              | 14        | 15.38%  |
| AU Optronics            | 10        | 10.99%  |
| Ancor Communications    | 6         | 6.59%   |
| Goldstar                | 4         | 4.4%    |
| Dell                    | 4         | 4.4%    |
| Chimei Innolux          | 4         | 4.4%    |
| AOC                     | 4         | 4.4%    |
| Philips                 | 3         | 3.3%    |
| Hewlett-Packard         | 3         | 3.3%    |
| Acer                    | 3         | 3.3%    |
| ViewSonic               | 2         | 2.2%    |
| LG Philips              | 2         | 2.2%    |
| BOE                     | 2         | 2.2%    |
| Apple                   | 2         | 2.2%    |
| ___                     | 1         | 1.1%    |
| Tech Concepts           | 1         | 1.1%    |
| PANDA                   | 1         | 1.1%    |
| Microstep               | 1         | 1.1%    |
| Lenovo                  | 1         | 1.1%    |
| Insignia                | 1         | 1.1%    |
| Idek Iiyama             | 1         | 1.1%    |
| HKC                     | 1         | 1.1%    |
| Chi Mei Optoelectronics | 1         | 1.1%    |
| BenQ                    | 1         | 1.1%    |
| Unknown                 | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch | 2         | 2.15%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch | 2         | 2.15%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 2         | 2.15%   |
| ___ AAA ___01FF 1366x768 700x390mm 31.5-inch                         | 1         | 1.08%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch        | 1         | 1.08%   |
| ViewSonic VA2013wSERIES VSCF122 1600x900 443x249mm 20.0-inch         | 1         | 1.08%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                           | 1         | 1.08%   |
| Samsung Electronics T24C310 SAM0AEA 1920x1080 531x299mm 24.0-inch    | 1         | 1.08%   |
| Samsung Electronics SMT22A550 SAM07AE 1920x1080 477x268mm 21.5-inch  | 1         | 1.08%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch    | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor S24B300 3840x1080                    | 1         | 1.08%   |
| Philips PHL 241P4 PHL08D5 1920x1080 531x299mm 24.0-inch              | 1         | 1.08%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch            | 1         | 1.08%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                   | 1         | 1.08%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch              | 1         | 1.08%   |
| Microstep LCD Monitor MSI MAG341CQ 3440x1440                         | 1         | 1.08%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch          | 1         | 1.08%   |
| LG Philips LCD Monitor LPL012B 1280x800 304x190mm 14.1-inch          | 1         | 1.08%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch        | 1         | 1.08%   |
| LG Display LCD Monitor LGD7001 1366x768 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch         | 1         | 1.08%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 1.08%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD02D9 1920x1080 345x194mm 15.6-inch         | 1         | 1.08%   |
| LG Display LCD Monitor LGD02A6 1366x768 345x194mm 15.6-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD01AF 1680x1050 331x207mm 15.4-inch         | 1         | 1.08%   |
| LG Display LCD Monitor LGD018E 1920x1200 367x230mm 17.1-inch         | 1         | 1.08%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch              | 1         | 1.08%   |
| Insignia NS28D310NA15 BBY0028 1680x1050 640x384mm 29.4-inch          | 1         | 1.08%   |
| Idek Iiyama LCD Monitor PL2473HD 1920x1080                           | 1         | 1.08%   |
| HKC LCD Monitor HKC2400 1920x1080 597x336mm 27.0-inch                | 1         | 1.08%   |
| Hewlett-Packard v185e HWP2838 1366x768 410x230mm 18.5-inch           | 1         | 1.08%   |
| Hewlett-Packard LCD Monitor w2338h                                   | 1         | 1.08%   |
| Hewlett-Packard Compaq W185q HWP284F 1366x768 410x230mm 18.5-inch    | 1         | 1.08%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 1         | 1.08%   |
| Goldstar RZ32LZ55 GSM7546 1360x768 930x523mm 42.0-inch               | 1         | 1.08%   |
| Goldstar M237WDP GSM5778 1920x1080 510x290mm 23.1-inch               | 1         | 1.08%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 1         | 1.08%   |
| Goldstar 32LG7000 GSM765E 1920x1080 700x390mm 31.5-inch              | 1         | 1.08%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                | 1         | 1.08%   |
| Dell E2216HV DELF06F 1920x1080 476x268mm 21.5-inch                   | 1         | 1.08%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 1         | 1.08%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch             | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch      | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 309x173mm 13.9-inch      | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 32        | 36.36%  |
| 1920x1080 (FHD)    | 22        | 25%     |
| 1600x900 (HD+)     | 7         | 7.95%   |
| 3840x2160 (4K)     | 5         | 5.68%   |
| 1440x900 (WXGA+)   | 4         | 4.55%   |
| 1360x768           | 4         | 4.55%   |
| 1680x1050 (WSXGA+) | 3         | 3.41%   |
| 1280x800 (WXGA)    | 3         | 3.41%   |
| 1920x1200 (WUXGA)  | 2         | 2.27%   |
| 3840x1080          | 1         | 1.14%   |
| 3440x1440          | 1         | 1.14%   |
| 2560x1440 (QHD)    | 1         | 1.14%   |
| 1280x720 (HD)      | 1         | 1.14%   |
| 1280x1024 (SXGA)   | 1         | 1.14%   |
| Unknown            | 1         | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 27.47%  |
| 17      | 10        | 10.99%  |
| 27      | 8         | 8.79%   |
| 24      | 6         | 6.59%   |
| 21      | 6         | 6.59%   |
| 14      | 6         | 6.59%   |
| 31      | 5         | 5.49%   |
| 18      | 5         | 5.49%   |
| Unknown | 5         | 5.49%   |
| 13      | 4         | 4.4%    |
| 19      | 3         | 3.3%    |
| 23      | 2         | 2.2%    |
| 22      | 2         | 2.2%    |
| 11      | 2         | 2.2%    |
| 42      | 1         | 1.1%    |
| 20      | 1         | 1.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 37.08%  |
| 401-500     | 16        | 17.98%  |
| 501-600     | 13        | 14.61%  |
| 351-400     | 11        | 12.36%  |
| 601-700     | 6         | 6.74%   |
| Unknown     | 5         | 5.62%   |
| 201-300     | 4         | 4.49%   |
| 901-1000    | 1         | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 64        | 74.42%  |
| 16/10   | 15        | 17.44%  |
| Unknown | 5         | 5.81%   |
| 5/4     | 2         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 27.78%  |
| 201-250        | 10        | 11.11%  |
| 81-90          | 8         | 8.89%   |
| 301-350        | 8         | 8.89%   |
| 151-200        | 7         | 7.78%   |
| 141-150        | 6         | 6.67%   |
| 131-140        | 6         | 6.67%   |
| 351-500        | 5         | 5.56%   |
| Unknown        | 5         | 5.56%   |
| 121-130        | 3         | 3.33%   |
| 71-80          | 2         | 2.22%   |
| 51-60          | 2         | 2.22%   |
| 251-300        | 2         | 2.22%   |
| 501-1000       | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 35        | 39.77%  |
| 51-100  | 32        | 36.36%  |
| 121-160 | 10        | 11.36%  |
| 1-50    | 5         | 5.68%   |
| Unknown | 5         | 5.68%   |
| 161-240 | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 82        | 86.32%  |
| 2     | 8         | 8.42%   |
| 0     | 4         | 4.21%   |
| 3     | 1         | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 61        | 39.87%  |
| Intel                           | 33        | 21.57%  |
| Qualcomm Atheros                | 16        | 10.46%  |
| Broadcom                        | 15        | 9.8%    |
| Broadcom Limited                | 7         | 4.58%   |
| Ralink                          | 4         | 2.61%   |
| Nvidia                          | 3         | 1.96%   |
| TP-Link                         | 2         | 1.31%   |
| Samsung Electronics             | 2         | 1.31%   |
| Marvell Technology Group        | 2         | 1.31%   |
| Toshiba                         | 1         | 0.65%   |
| Ralink Technology               | 1         | 0.65%   |
| Qualcomm Atheros Communications | 1         | 0.65%   |
| Motorola PCS                    | 1         | 0.65%   |
| MediaTek                        | 1         | 0.65%   |
| Lenovo                          | 1         | 0.65%   |
| Huawei Technologies             | 1         | 0.65%   |
| D-Link                          | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 44        | 25.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 9         | 5.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4         | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 4         | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3         | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.73%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 1.73%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 1.73%   |
| Intel 82579V Gigabit Network Connection                                                       | 3         | 1.73%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 3         | 1.73%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2         | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1.16%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 1.16%   |
| Nvidia MCP61 Ethernet                                                                         | 2         | 1.16%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.16%   |
| Intel Wireless 3160                                                                           | 2         | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.16%   |
| Intel 82577LM Gigabit Network Connection                                                      | 2         | 1.16%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                                     | 2         | 1.16%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 1.16%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 0.58%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 0.58%   |
| Toshiba F5521gw                                                                               | 1         | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.58%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.58%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 0.58%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.58%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1         | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.58%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1         | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 0.58%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.58%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                                              | 1         | 0.58%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.58%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1         | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 1         | 0.58%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1         | 0.58%   |
| Nvidia MCP79 Ethernet                                                                         | 1         | 0.58%   |
| Motorola PCS motorola edge                                                                    | 1         | 0.58%   |
| MediaTek 802.11 n WLAN                                                                        | 1         | 0.58%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.58%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                                         | 1         | 0.58%   |
| Lenovo Thinkpad USB LAN                                                                       | 1         | 0.58%   |
| Intel Wireless 7265                                                                           | 1         | 0.58%   |
| Intel Wireless 7260                                                                           | 1         | 0.58%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.58%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 31.58%  |
| Realtek Semiconductor           | 14        | 18.42%  |
| Qualcomm Atheros                | 13        | 17.11%  |
| Broadcom                        | 13        | 17.11%  |
| Ralink                          | 4         | 5.26%   |
| TP-Link                         | 2         | 2.63%   |
| Broadcom Limited                | 2         | 2.63%   |
| Ralink Technology               | 1         | 1.32%   |
| Qualcomm Atheros Communications | 1         | 1.32%   |
| MediaTek                        | 1         | 1.32%   |
| D-Link                          | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4         | 5.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 4         | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3         | 3.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 3.95%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 3.95%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 3.95%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 3         | 3.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 2.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 2.63%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2.63%   |
| Intel Wireless 3160                                                                           | 2         | 2.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 2.63%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 1.32%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.32%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 1.32%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 1.32%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1         | 1.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.32%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 1.32%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.32%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 1.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.32%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.32%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1         | 1.32%   |
| MediaTek 802.11 n WLAN                                                                        | 1         | 1.32%   |
| Intel Wireless 7265                                                                           | 1         | 1.32%   |
| Intel Wireless 7260                                                                           | 1         | 1.32%   |
| Intel WiFi Link 5100                                                                          | 1         | 1.32%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 1.32%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.32%   |
| Intel Centrino Wireless-N 2230                                                                | 1         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                                                | 1         | 1.32%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                                 | 1         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.32%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1         | 1.32%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.32%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.32%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                   | 1         | 1.32%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1         | 1.32%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 1.32%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 55        | 57.89%  |
| Intel                    | 15        | 15.79%  |
| Broadcom                 | 6         | 6.32%   |
| Broadcom Limited         | 5         | 5.26%   |
| Qualcomm Atheros         | 4         | 4.21%   |
| Nvidia                   | 3         | 3.16%   |
| Samsung Electronics      | 2         | 2.11%   |
| Marvell Technology Group | 2         | 2.11%   |
| Motorola PCS             | 1         | 1.05%   |
| Lenovo                   | 1         | 1.05%   |
| Huawei Technologies      | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 45.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 9.38%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 3.13%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.08%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.08%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 2.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.04%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.04%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.04%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.04%   |
| Motorola PCS motorola edge                                        | 1         | 1.04%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.04%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 1.04%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 1.04%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.04%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.04%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.04%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 1.04%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.04%   |
| Intel 82566DC Gigabit Network Connection                          | 1         | 1.04%   |
| Huawei E353/E3131                                                 | 1         | 1.04%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.04%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.04%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.04%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.04%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1         | 1.04%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.04%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 90        | 55.56%  |
| WiFi     | 71        | 43.83%  |
| Modem    | 1         | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 87        | 58.39%  |
| WiFi     | 62        | 41.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 59        | 62.11%  |
| 1     | 30        | 31.58%  |
| 0     | 5         | 5.26%   |
| 4     | 1         | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 62.11%  |
| Yes  | 36        | 37.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 29.79%  |
| Cambridge Silicon Radio         | 6         | 12.77%  |
| Dell                            | 4         | 8.51%   |
| Hewlett-Packard                 | 3         | 6.38%   |
| Realtek Semiconductor           | 2         | 4.26%   |
| Qualcomm Atheros Communications | 2         | 4.26%   |
| Qualcomm Atheros                | 2         | 4.26%   |
| Lite-On Technology              | 2         | 4.26%   |
| Foxconn / Hon Hai               | 2         | 4.26%   |
| Broadcom                        | 2         | 4.26%   |
| ASUSTek Computer                | 2         | 4.26%   |
| Apple                           | 2         | 4.26%   |
| Toshiba                         | 1         | 2.13%   |
| Ralink                          | 1         | 2.13%   |
| IMC Networks                    | 1         | 2.13%   |
| Askey Computer                  | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 12.77%  |
| Intel Bluetooth wireless interface                  | 4         | 8.51%   |
| Intel Bluetooth Device                              | 4         | 8.51%   |
| Intel AX200 Bluetooth                               | 3         | 6.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 4.26%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 4.26%   |
| Dell DW375 Bluetooth Module                         | 2         | 4.26%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 4.26%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.13%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.13%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.13%   |
| Lite-On Atheros Bluetooth                           | 1         | 2.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.13%   |
| IMC Networks Bluetooth Device                       | 1         | 2.13%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.13%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 2.13%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 2.13%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.13%   |
| Askey Bluetooth Device                              | 1         | 2.13%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.13%   |
| Apple Bluetooth Host Controller                     | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 67        | 49.26%  |
| AMD                       | 28        | 20.59%  |
| Nvidia                    | 25        | 18.38%  |
| C-Media Electronics       | 4         | 2.94%   |
| GN Netcom                 | 3         | 2.21%   |
| Texas Instruments         | 1         | 0.74%   |
| Sennheiser Communications | 1         | 0.74%   |
| Realtek Semiconductor     | 1         | 0.74%   |
| Microsoft                 | 1         | 0.74%   |
| M-Audio                   | 1         | 0.74%   |
| JMTek                     | 1         | 0.74%   |
| iSoft Silicon             | 1         | 0.74%   |
| Creative Labs             | 1         | 0.74%   |
| AOKEO                     | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 7.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 6.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 6.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 3.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.53%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.53%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 2.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.9%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 1.9%    |
| AMD High Definition Audio Controller                                       | 3         | 1.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.27%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.27%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.27%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.27%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 1.27%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 1.27%   |
| Texas Instruments PCM2903B Audio CODEC                                     | 1         | 0.63%   |
| Sennheiser Communications PXC 550                                          | 1         | 0.63%   |
| Realtek Semiconductor Realtek USB audio                                    | 1         | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.63%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.63%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.63%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.63%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.63%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.63%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.63%   |
| Nvidia GF104 High Definition Audio Controller                              | 1         | 0.63%   |
| Microsoft LifeChat LX-3000 Headset                                         | 1         | 0.63%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 0.63%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.63%   |
| iSoft Silicon USB Ear-Microphone                                           | 1         | 0.63%   |
| Intel Lewisburg MROM 0                                                     | 1         | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.63%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 0.63%   |
| GN Netcom Jabra Link 380                                                   | 1         | 0.63%   |
| GN Netcom Jabra Link 370                                                   | 1         | 0.63%   |
| GN Netcom Jabra EVOLVE 30 II                                               | 1         | 0.63%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 28.57%  |
| Kingston            | 2         | 28.57%  |
| Unknown             | 1         | 14.29%  |
| SK Hynix            | 1         | 14.29%  |
| Corsair             | 1         | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 533MT/s              | 1         | 12.5%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s              | 1         | 12.5%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1066MT/s            | 1         | 12.5%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 1         | 12.5%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 12.5%   |
| Kingston RAM KHX2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s | 1         | 12.5%   |
| Kingston RAM 9905428-020.A00LF 4096MB SODIMM DDR3 1067MT/s | 1         | 12.5%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s   | 1         | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR3 | 3         | 50%     |
| DDR4 | 2         | 33.33%  |
| DDR2 | 1         | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 5         | 83.33%  |
| DIMM   | 1         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 3         | 42.86%  |
| 16384 | 1         | 14.29%  |
| 8192  | 1         | 14.29%  |
| 2048  | 1         | 14.29%  |
| 1024  | 1         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3600  | 1         | 14.29%  |
| 2667  | 1         | 14.29%  |
| 1600  | 1         | 14.29%  |
| 1334  | 1         | 14.29%  |
| 1067  | 1         | 14.29%  |
| 1066  | 1         | 14.29%  |
| 533   | 1         | 14.29%  |

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
| Chicony Electronics                    | 11        | 19.64%  |
| Silicon Motion                         | 5         | 8.93%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 7.14%   |
| Acer                                   | 4         | 7.14%   |
| Quanta                                 | 3         | 5.36%   |
| Microdia                               | 3         | 5.36%   |
| Suyin                                  | 2         | 3.57%   |
| Sunplus Innovation Technology          | 2         | 3.57%   |
| Ricoh                                  | 2         | 3.57%   |
| Realtek Semiconductor                  | 2         | 3.57%   |
| Microsoft                              | 2         | 3.57%   |
| Logitech                               | 2         | 3.57%   |
| Apple                                  | 2         | 3.57%   |
| Z-Star Microelectronics                | 1         | 1.79%   |
| Syntek                                 | 1         | 1.79%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 1.79%   |
| Samsung Electronics                    | 1         | 1.79%   |
| Primax Electronics                     | 1         | 1.79%   |
| Jieli Technology                       | 1         | 1.79%   |
| icSpring                               | 1         | 1.79%   |
| HD WEBCAM                              | 1         | 1.79%   |
| HD 2MP WEBCAM                          | 1         | 1.79%   |
| Creative Technology                    | 1         | 1.79%   |
| ALi                                    | 1         | 1.79%   |
| Alcor Micro                            | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Sunplus HD WebCam                                       | 2         | 3.57%   |
| Realtek USB Camera                                      | 2         | 3.57%   |
| Quanta HP Webcam                                        | 2         | 3.57%   |
| Chicony HD WebCam                                       | 2         | 3.57%   |
| Chicony CNF9055 Toshiba Webcam                          | 2         | 3.57%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 2         | 3.57%   |
| Acer Lenovo EasyCamera                                  | 2         | 3.57%   |
| Z-Star WebCam SC-03FFL11739P                            | 1         | 1.79%   |
| Syntek Lenovo EasyCamera                                | 1         | 1.79%   |
| Suyin UVC HD Webcam                                     | 1         | 1.79%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 1.79%   |
| Silicon Motion WebCam SCB-1100N                         | 1         | 1.79%   |
| Silicon Motion WebCam SCB-0385N                         | 1         | 1.79%   |
| Silicon Motion WebCam SC-0311139N                       | 1         | 1.79%   |
| Silicon Motion SM731 Camera                             | 1         | 1.79%   |
| Silicon Motion 300k Pixel Camera                        | 1         | 1.79%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960          | 1         | 1.79%   |
| Samsung Galaxy A5 (MTP)                                 | 1         | 1.79%   |
| Ricoh Laptop_Integrated_Webcam_3M                       | 1         | 1.79%   |
| Ricoh Integrated Webcam                                 | 1         | 1.79%   |
| Quanta Laptop_Integrated_Webcam_2HDM                    | 1         | 1.79%   |
| Primax HP Webcam-101                                    | 1         | 1.79%   |
| Microsoft LifeCam VX-5000                               | 1         | 1.79%   |
| Microsoft LifeCam VX-500 [1357]                         | 1         | 1.79%   |
| Microdia Lenovo EasyCamera                              | 1         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_0.3M                  | 1         | 1.79%   |
| Microdia Integrated_Webcam_HD                           | 1         | 1.79%   |
| Logitech Webcam C600                                    | 1         | 1.79%   |
| Logitech C922 Pro Stream Webcam                         | 1         | 1.79%   |
| Jieli USB PHY 2.0                                       | 1         | 1.79%   |
| icSpring camera                                         | 1         | 1.79%   |
| HD WEBCAM Web Camera                                    | 1         | 1.79%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                             | 1         | 1.79%   |
| Creative Live! Cam Sync HD [VF0770]                     | 1         | 1.79%   |
| Chicony USB 2.0 Camera                                  | 1         | 1.79%   |
| Chicony HP Webcam                                       | 1         | 1.79%   |
| Chicony HP TrueVision HD Camera                         | 1         | 1.79%   |
| Chicony FJ Camera                                       | 1         | 1.79%   |
| Chicony CNF7042                                         | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 1         | 1.79%   |
| Apple FaceTime HD Camera (Built-in)                     | 1         | 1.79%   |
| Apple Built-in iSight                                   | 1         | 1.79%   |
| ALi Gateway Webcam                                      | 1         | 1.79%   |
| Alcor Micro USB 2.0 Camera                              | 1         | 1.79%   |
| Acer SunplusIT Integrated Camera                        | 1         | 1.79%   |
| Acer Crystal Eye webcam                                 | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| AuthenTec        | 2         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS451 Fingerprint Reader | 2         | 50%     |
| AuthenTec Fingerprint Sensor               | 1         | 25%     |
| AuthenTec AES2550 Fingerprint Sensor       | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 69        | 72.63%  |
| 1     | 21        | 22.11%  |
| 2     | 5         | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 9         | 31.03%  |
| Net/wireless          | 6         | 20.69%  |
| Fingerprint reader    | 4         | 13.79%  |
| Storage               | 3         | 10.34%  |
| Chipcard              | 3         | 10.34%  |
| Multimedia controller | 2         | 6.9%    |
| Unassigned class      | 1         | 3.45%   |
| Bluetooth             | 1         | 3.45%   |


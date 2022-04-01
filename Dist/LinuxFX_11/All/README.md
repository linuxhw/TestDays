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

Total: 166

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProBook 640 G1              | Notebook    | [0834bd783c](https://linux-hardware.org/?probe=0834bd783c) | Mar 30, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [3f0b633075](https://linux-hardware.org/?probe=3f0b633075) | Mar 30, 2022 |
| Dell          | Latitude 7389               | Convertible | [994b9bbd25](https://linux-hardware.org/?probe=994b9bbd25) | Mar 27, 2022 |
| Dell          | Latitude 7389               | Convertible | [fb50f0fee3](https://linux-hardware.org/?probe=fb50f0fee3) | Mar 27, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [18d216846f](https://linux-hardware.org/?probe=18d216846f) | Mar 23, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Dell          | Latitude 7389               | Convertible | [41c5b09aa4](https://linux-hardware.org/?probe=41c5b09aa4) | Mar 11, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b43ace9110](https://linux-hardware.org/?probe=b43ace9110) | Mar 11, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [cfd96dd963](https://linux-hardware.org/?probe=cfd96dd963) | Mar 08, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [851e340c24](https://linux-hardware.org/?probe=851e340c24) | Mar 03, 2022 |
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
| 5.11.0-37-generic | 15        | 13.89%  |
| 5.11.0-43-generic | 12        | 11.11%  |
| 5.13.0-27-generic | 11        | 10.19%  |
| 5.11.0-40-generic | 11        | 10.19%  |
| 5.11.0-38-generic | 11        | 10.19%  |
| 5.11.0-41-generic | 10        | 9.26%   |
| 5.13.0-28-generic | 9         | 8.33%   |
| 5.11.0-36-generic | 7         | 6.48%   |
| 5.11.0-34-generic | 6         | 5.56%   |
| 5.13.0-30-generic | 5         | 4.63%   |
| 5.11.0-46-generic | 5         | 4.63%   |
| 5.13.0-39-generic | 2         | 1.85%   |
| 5.13.0-35-generic | 1         | 0.93%   |
| 5.13.0-25-generic | 1         | 0.93%   |
| 5.11.0-44-generic | 1         | 0.93%   |
| 5.11.0-42-generic | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 74        | 71.84%  |
| 5.13.0  | 29        | 28.16%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 74        | 71.84%  |
| 5.13    | 29        | 28.16%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 102       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 97        | 94.17%  |
| KDE        | 5         | 4.85%   |
| X-Cinnamon | 1         | 0.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 101       | 99.02%  |
| Wayland | 1         | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 86        | 84.31%  |
| SDDM    | 16        | 15.69%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 23        | 22.55%  |
| pt_BR | 14        | 13.73%  |
| de_DE | 11        | 10.78%  |
| it_IT | 6         | 5.88%   |
| fr_FR | 6         | 5.88%   |
| en_GB | 4         | 3.92%   |
| C     | 4         | 3.92%   |
| pl_PL | 3         | 2.94%   |
| en_IN | 3         | 2.94%   |
| en_AU | 3         | 2.94%   |
| nl_NL | 2         | 1.96%   |
| es_MX | 2         | 1.96%   |
| en_CA | 2         | 1.96%   |
| el_GR | 2         | 1.96%   |
| cs_CZ | 2         | 1.96%   |
| zh_CN | 1         | 0.98%   |
| sv_SE | 1         | 0.98%   |
| ru_UA | 1         | 0.98%   |
| ru_RU | 1         | 0.98%   |
| pt_PT | 1         | 0.98%   |
| nl_BE | 1         | 0.98%   |
| hr_BA | 1         | 0.98%   |
| fr_CA | 1         | 0.98%   |
| fi_FI | 1         | 0.98%   |
| es_HN | 1         | 0.98%   |
| es_ES | 1         | 0.98%   |
| es_CO | 1         | 0.98%   |
| es_AR | 1         | 0.98%   |
| en_NG | 1         | 0.98%   |
| da_DK | 1         | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 69        | 67.65%  |
| EFI  | 33        | 32.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 100       | 98.04%  |
| Overlay | 2         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 99        | 97.06%  |
| GPT     | 2         | 1.96%   |
| MBR     | 1         | 0.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 95.1%   |
| Yes       | 5         | 4.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 94        | 92.16%  |
| Yes       | 8         | 7.84%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 17.65%  |
| Dell                | 13        | 12.75%  |
| ASUSTek Computer    | 9         | 8.82%   |
| Acer                | 9         | 8.82%   |
| MSI                 | 7         | 6.86%   |
| Lenovo              | 7         | 6.86%   |
| Gigabyte Technology | 5         | 4.9%    |
| ASRock              | 5         | 4.9%    |
| Samsung Electronics | 4         | 3.92%   |
| Positivo            | 4         | 3.92%   |
| Intel               | 4         | 3.92%   |
| Toshiba             | 3         | 2.94%   |
| Apple               | 3         | 2.94%   |
| Pegatron            | 2         | 1.96%   |
| Google              | 2         | 1.96%   |
| GPU Company         | 1         | 0.98%   |
| Fujitsu Siemens     | 1         | 0.98%   |
| Fujitsu             | 1         | 0.98%   |
| Foxconn             | 1         | 0.98%   |
| ASRockRack          | 1         | 0.98%   |
| Alienware           | 1         | 0.98%   |
| ABIT                | 1         | 0.98%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP 255 G6 Notebook PC                                                                    | 2         | 1.96%   |
| Toshiba TECRA R850                                                                       | 1         | 0.98%   |
| Toshiba Satellite P300                                                                   | 1         | 0.98%   |
| Toshiba Satellite C660                                                                   | 1         | 0.98%   |
| Samsung RV415/RV515/E3415                                                                | 1         | 0.98%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411                                              | 1         | 0.98%   |
| Samsung RF511/RF411/RF711                                                                | 1         | 0.98%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.98%   |
| Positivo Smash3                                                                          | 1         | 0.98%   |
| Positivo Smash                                                                           | 1         | 0.98%   |
| Positivo POS-PIQ67CG                                                                     | 1         | 0.98%   |
| Positivo POS-EIBTPDC                                                                     | 1         | 0.98%   |
| Pegatron p6745br                                                                         | 1         | 0.98%   |
| Pegatron NC045AA-ABU IQ525uk                                                             | 1         | 0.98%   |
| MSI MS-7C37                                                                              | 1         | 0.98%   |
| MSI MS-7B79                                                                              | 1         | 0.98%   |
| MSI MS-7A71                                                                              | 1         | 0.98%   |
| MSI MS-7752                                                                              | 1         | 0.98%   |
| MSI MS-7693                                                                              | 1         | 0.98%   |
| MSI MS-7681                                                                              | 1         | 0.98%   |
| MSI MS-7529                                                                              | 1         | 0.98%   |
| Lenovo ThinkPad L380 20M6S4E000                                                          | 1         | 0.98%   |
| Lenovo MIIX 310-10ICR 80SG                                                               | 1         | 0.98%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                                                         | 1         | 0.98%   |
| Lenovo IdeaPad Y510P 20217                                                               | 1         | 0.98%   |
| Lenovo G550 2958                                                                         | 1         | 0.98%   |
| Lenovo G50-80 80R0                                                                       | 1         | 0.98%   |
| Lenovo G50-80 80E5                                                                       | 1         | 0.98%   |
| Intel H55                                                                                | 1         | 0.98%   |
| Intel DP55WB AAE64798-205                                                                | 1         | 0.98%   |
| Intel DG35EC AAE29266-202                                                                | 1         | 0.98%   |
| Intel DESKTOP 300                                                                        | 1         | 0.98%   |
| HP ProBook 640 G1                                                                        | 1         | 0.98%   |
| HP ProBook 4720s                                                                         | 1         | 0.98%   |
| HP ProBook 440 G1                                                                        | 1         | 0.98%   |
| HP Pavilion g6                                                                           | 1         | 0.98%   |
| HP Pavilion dv6700                                                                       | 1         | 0.98%   |
| HP Pavilion 14                                                                           | 1         | 0.98%   |
| HP Laptop 15-da0xxx                                                                      | 1         | 0.98%   |
| HP Laptop 15-bw0xx                                                                       | 1         | 0.98%   |
| HP Laptop 14-dk1xxx                                                                      | 1         | 0.98%   |
| HP G62                                                                                   | 1         | 0.98%   |
| HP EliteDesk 800 G2 SFF                                                                  | 1         | 0.98%   |
| HP EliteBook 8570w                                                                       | 1         | 0.98%   |
| HP EliteBook 8440p                                                                       | 1         | 0.98%   |
| HP Compaq CQ45                                                                           | 1         | 0.98%   |
| HP Compaq 6730b (NA373UC#ABA)                                                            | 1         | 0.98%   |
| HP 700-214                                                                               | 1         | 0.98%   |
| GPU Company GWTN116-3                                                                    | 1         | 0.98%   |
| Google Teemo                                                                             | 1         | 0.98%   |
| Google Peppy                                                                             | 1         | 0.98%   |
| Gigabyte H61M-S2PV                                                                       | 1         | 0.98%   |
| Gigabyte GA-970A-D3                                                                      | 1         | 0.98%   |
| Gigabyte F2A78M-D3H                                                                      | 1         | 0.98%   |
| Gigabyte 970A-D3                                                                         | 1         | 0.98%   |
| Gigabyte 7200-5121B                                                                      | 1         | 0.98%   |
| Fujitsu Siemens AMILO Xi 1526                                                            | 1         | 0.98%   |
| Fujitsu CELSIUS H700                                                                     | 1         | 0.98%   |
| Foxconn D270S/D250S MP                                                                   | 1         | 0.98%   |
| Dell System XPS L502X                                                                    | 1         | 0.98%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 6         | 5.88%   |
| Dell Latitude         | 5         | 4.9%    |
| HP ProBook            | 3         | 2.94%   |
| HP Pavilion           | 3         | 2.94%   |
| HP Laptop             | 3         | 2.94%   |
| Toshiba Satellite     | 2         | 1.96%   |
| Lenovo G50-80         | 2         | 1.96%   |
| HP EliteBook          | 2         | 1.96%   |
| HP Compaq             | 2         | 1.96%   |
| HP 255                | 2         | 1.96%   |
| Dell Precision        | 2         | 1.96%   |
| Dell OptiPlex         | 2         | 1.96%   |
| Dell Inspiron         | 2         | 1.96%   |
| Apple MacBookPro5     | 2         | 1.96%   |
| Toshiba TECRA         | 1         | 0.98%   |
| Samsung RV415         | 1         | 0.98%   |
| Samsung RV411         | 1         | 0.98%   |
| Samsung RF511         | 1         | 0.98%   |
| Samsung 355V4C        | 1         | 0.98%   |
| Positivo Smash3       | 1         | 0.98%   |
| Positivo Smash        | 1         | 0.98%   |
| Positivo POS-PIQ67CG  | 1         | 0.98%   |
| Positivo POS-EIBTPDC  | 1         | 0.98%   |
| Pegatron p6745br      | 1         | 0.98%   |
| Pegatron NC045AA-ABU  | 1         | 0.98%   |
| MSI MS-7C37           | 1         | 0.98%   |
| MSI MS-7B79           | 1         | 0.98%   |
| MSI MS-7A71           | 1         | 0.98%   |
| MSI MS-7752           | 1         | 0.98%   |
| MSI MS-7693           | 1         | 0.98%   |
| MSI MS-7681           | 1         | 0.98%   |
| MSI MS-7529           | 1         | 0.98%   |
| Lenovo ThinkPad       | 1         | 0.98%   |
| Lenovo MIIX           | 1         | 0.98%   |
| Lenovo Legion         | 1         | 0.98%   |
| Lenovo IdeaPad        | 1         | 0.98%   |
| Lenovo G550           | 1         | 0.98%   |
| Intel H55             | 1         | 0.98%   |
| Intel DP55WB          | 1         | 0.98%   |
| Intel DG35EC          | 1         | 0.98%   |
| Intel DESKTOP         | 1         | 0.98%   |
| HP G62                | 1         | 0.98%   |
| HP EliteDesk          | 1         | 0.98%   |
| HP 700-214            | 1         | 0.98%   |
| GPU Company GWTN116-3 | 1         | 0.98%   |
| Google Teemo          | 1         | 0.98%   |
| Google Peppy          | 1         | 0.98%   |
| Gigabyte H61M-S2PV    | 1         | 0.98%   |
| Gigabyte GA-970A-D3   | 1         | 0.98%   |
| Gigabyte F2A78M-D3H   | 1         | 0.98%   |
| Gigabyte 970A-D3      | 1         | 0.98%   |
| Gigabyte 7200-5121B   | 1         | 0.98%   |
| Fujitsu Siemens AMILO | 1         | 0.98%   |
| Fujitsu CELSIUS       | 1         | 0.98%   |
| Foxconn D270S         | 1         | 0.98%   |
| Dell System           | 1         | 0.98%   |
| Dell G5               | 1         | 0.98%   |
| ASUS X751LAB          | 1         | 0.98%   |
| ASUS PRIME            | 1         | 0.98%   |
| ASUS P7H55-M          | 1         | 0.98%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 19        | 18.63%  |
| 2010 | 10        | 9.8%    |
| 2019 | 8         | 7.84%   |
| 2013 | 8         | 7.84%   |
| 2009 | 8         | 7.84%   |
| 2017 | 7         | 6.86%   |
| 2014 | 7         | 6.86%   |
| 2012 | 7         | 6.86%   |
| 2015 | 6         | 5.88%   |
| 2008 | 6         | 5.88%   |
| 2021 | 5         | 4.9%    |
| 2016 | 5         | 4.9%    |
| 2007 | 3         | 2.94%   |
| 2018 | 2         | 1.96%   |
| 2006 | 1         | 0.98%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 57        | 55.88%  |
| Desktop     | 41        | 40.2%   |
| Tablet      | 1         | 0.98%   |
| Convertible | 1         | 0.98%   |
| All in one  | 1         | 0.98%   |
| Server      | 1         | 0.98%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 97        | 95.1%   |
| Enabled  | 5         | 4.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 100       | 98.04%  |
| Yes  | 2         | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 27        | 26.47%  |
| 8.01-16.0  | 24        | 23.53%  |
| 4.01-8.0   | 23        | 22.55%  |
| 16.01-24.0 | 14        | 13.73%  |
| 32.01-64.0 | 5         | 4.9%    |
| 1.01-2.0   | 5         | 4.9%    |
| 24.01-32.0 | 2         | 1.96%   |
| 2.01-3.0   | 2         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 53        | 50.48%  |
| 2.01-3.0  | 28        | 26.67%  |
| 3.01-4.0  | 9         | 8.57%   |
| 0.51-1.0  | 9         | 8.57%   |
| 4.01-8.0  | 4         | 3.81%   |
| 8.01-16.0 | 2         | 1.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 68        | 65.38%  |
| 2      | 23        | 22.12%  |
| 3      | 8         | 7.69%   |
| 4      | 3         | 2.88%   |
| 5      | 2         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 65.69%  |
| No        | 35        | 34.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 94.12%  |
| No        | 6         | 5.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 74.76%  |
| No        | 26        | 25.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 52.94%  |
| No        | 48        | 47.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 19.61%  |
| Brazil      | 15        | 14.71%  |
| Germany     | 11        | 10.78%  |
| Italy       | 6         | 5.88%   |
| France      | 5         | 4.9%    |
| Canada      | 5         | 4.9%    |
| Poland      | 4         | 3.92%   |
| UK          | 3         | 2.94%   |
| India       | 3         | 2.94%   |
| Australia   | 3         | 2.94%   |
| Netherlands | 2         | 1.96%   |
| Mexico      | 2         | 1.96%   |
| Greece      | 2         | 1.96%   |
| Czechia     | 2         | 1.96%   |
| Ukraine     | 1         | 0.98%   |
| Sweden      | 1         | 0.98%   |
| Spain       | 1         | 0.98%   |
| Serbia      | 1         | 0.98%   |
| Russia      | 1         | 0.98%   |
| Puerto Rico | 1         | 0.98%   |
| Portugal    | 1         | 0.98%   |
| Pakistan    | 1         | 0.98%   |
| Nigeria     | 1         | 0.98%   |
| Namibia     | 1         | 0.98%   |
| Jamaica     | 1         | 0.98%   |
| Honduras    | 1         | 0.98%   |
| Finland     | 1         | 0.98%   |
| Denmark     | 1         | 0.98%   |
| Croatia     | 1         | 0.98%   |
| Colombia    | 1         | 0.98%   |
| China       | 1         | 0.98%   |
| Belgium     | 1         | 0.98%   |
| Argentina   | 1         | 0.98%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Rio de Janeiro      | 4         | 3.85%   |
| Warsaw              | 3         | 2.88%   |
| Sao Paulo           | 2         | 1.92%   |
| Lutjegast           | 2         | 1.92%   |
| Hobart              | 2         | 1.92%   |
| Campinas            | 2         | 1.92%   |
| Zaventem            | 1         | 0.96%   |
| Zagreb              | 1         | 0.96%   |
| Windhoek            | 1         | 0.96%   |
| Wabern              | 1         | 0.96%   |
| Vivian              | 1         | 0.96%   |
| Vicksburg           | 1         | 0.96%   |
| Toronto             | 1         | 0.96%   |
| Toluca              | 1         | 0.96%   |
| Temple Hills        | 1         | 0.96%   |
| Tegucigalpa         | 1         | 0.96%   |
| Stourbridge         | 1         | 0.96%   |
| Stockholm           | 1         | 0.96%   |
| Spicheren           | 1         | 0.96%   |
| Sparta              | 1         | 0.96%   |
| Siegburg            | 1         | 0.96%   |
| Shamrock            | 1         | 0.96%   |
| Senas               | 1         | 0.96%   |
| Sankt Augustin      | 1         | 0.96%   |
| Salt Lake City      | 1         | 0.96%   |
| Saloa               | 1         | 0.96%   |
| Rome                | 1         | 0.96%   |
| Rio das Ostras      | 1         | 0.96%   |
| Ringgold            | 1         | 0.96%   |
| Reims               | 1         | 0.96%   |
| QuÃ©bec           | 1         | 0.96%   |
| Prague              | 1         | 0.96%   |
| Porto               | 1         | 0.96%   |
| Port Coquitlam      | 1         | 0.96%   |
| Patchogue           | 1         | 0.96%   |
| Oswego              | 1         | 0.96%   |
| Oshawa              | 1         | 0.96%   |
| Odense              | 1         | 0.96%   |
| Novi Karlovci       | 1         | 0.96%   |
| Northwich           | 1         | 0.96%   |
| North Plains        | 1         | 0.96%   |
| NiterÃ³i          | 1         | 0.96%   |
| Newcastle upon Tyne | 1         | 0.96%   |
| Newburgh            | 1         | 0.96%   |
| Naples              | 1         | 0.96%   |
| Nanning             | 1         | 0.96%   |
| Missoula            | 1         | 0.96%   |
| Milan               | 1         | 0.96%   |
| Melbourne           | 1         | 0.96%   |
| Mandi               | 1         | 0.96%   |
| Madrid              | 1         | 0.96%   |
| Lohja               | 1         | 0.96%   |
| Lares               | 1         | 0.96%   |
| Lagos               | 1         | 0.96%   |
| Kochi               | 1         | 0.96%   |
| Kladno              | 1         | 0.96%   |
| Kingston            | 1         | 0.96%   |
| Karachi             | 1         | 0.96%   |
| JoÃ£o Pessoa      | 1         | 0.96%   |
| Itaperuna           | 1         | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 34     | 17.99%  |
| WDC                 | 24        | 28     | 17.27%  |
| Samsung Electronics | 14        | 14     | 10.07%  |
| Toshiba             | 13        | 13     | 9.35%   |
| SanDisk             | 11        | 11     | 7.91%   |
| Unknown             | 6         | 10     | 4.32%   |
| Crucial             | 5         | 6      | 3.6%    |
| Kingston            | 4         | 4      | 2.88%   |
| PNY                 | 3         | 3      | 2.16%   |
| JMicron             | 3         | 3      | 2.16%   |
| Hitachi             | 3         | 3      | 2.16%   |
| Transcend           | 2         | 2      | 1.44%   |
| SPCC                | 2         | 2      | 1.44%   |
| SK Hynix            | 2         | 3      | 1.44%   |
| Patriot             | 2         | 2      | 1.44%   |
| HGST                | 2         | 2      | 1.44%   |
| A-DATA Technology   | 2         | 2      | 1.44%   |
| SATAFIRM            | 1         | 1      | 0.72%   |
| Phison              | 1         | 1      | 0.72%   |
| OCZ                 | 1         | 1      | 0.72%   |
| Micron_1            | 1         | 2      | 0.72%   |
| MAXTOR              | 1         | 1      | 0.72%   |
| LITEON              | 1         | 1      | 0.72%   |
| Lenovo              | 1         | 1      | 0.72%   |
| I/OMAGIC            | 1         | 1      | 0.72%   |
| HEORIADY            | 1         | 1      | 0.72%   |
| DOGFISH             | 1         | 1      | 0.72%   |
| Apple               | 1         | 2      | 0.72%   |
| Apacer              | 1         | 2      | 0.72%   |
| AMD                 | 1         | 1      | 0.72%   |
| ALERTSEAL           | 1         | 1      | 0.72%   |
| AFOX                | 1         | 1      | 0.72%   |
| Unknown             | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  64GB              | 4         | 2.67%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 2.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 2%      |
| SanDisk SDSSDX240GG25 240GB         | 3         | 2%      |
| Kingston SA400S37240G 240GB SSD     | 3         | 2%      |
| Toshiba MQ04ABF100 1TB              | 2         | 1.33%   |
| Toshiba MQ01ABD050 500GB            | 2         | 1.33%   |
| Toshiba MK2552GSX 250GB             | 2         | 1.33%   |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 1.33%   |
| Seagate Expansion Desk 4TB          | 2         | 1.33%   |
| Samsung NVMe SSD Drive 500GB        | 2         | 1.33%   |
| PNY CS900 120GB SSD                 | 2         | 1.33%   |
| Patriot Burst 120GB SSD             | 2         | 1.33%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 1.33%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1         | 0.67%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.67%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.67%   |
| WDC WDBNCE5000PNC 500GB SSD         | 1         | 0.67%   |
| WDC WD6402AAEX-00Y9A0 640GB         | 1         | 0.67%   |
| WDC WD6401AALS-00L3B2 640GB         | 1         | 0.67%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 0.67%   |
| WDC WD5000BPVT-60HXZT1 500GB        | 1         | 0.67%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 0.67%   |
| WDC WD5000AVVS-63M8B0 500GB         | 1         | 0.67%   |
| WDC WD5000AAKS-75A7B2 500GB         | 1         | 0.67%   |
| WDC WD3200BEKT-00PVMT0 320GB        | 1         | 0.67%   |
| WDC WD3200AAKS-61L9A0 320GB         | 1         | 0.67%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1         | 0.67%   |
| WDC WD30EZRX-00MMMB0 3TB            | 1         | 0.67%   |
| WDC WD2500BEVT-24A23T0 250GB        | 1         | 0.67%   |
| WDC WD20EADS-00R6B0 2TB             | 1         | 0.67%   |
| WDC WD1600JB-32FUA0 160GB           | 1         | 0.67%   |
| WDC WD1600BEVT-75ZCT1 160GB         | 1         | 0.67%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1         | 0.67%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 0.67%   |
| WDC WD10EADS-22M2B0 1TB             | 1         | 0.67%   |
| WDC WD1003FBYX-02A6B0 1TB           | 1         | 0.67%   |
| WDC WD1001FALS-00J7B0 1TB           | 1         | 0.67%   |
| Unknown SD  128GB                   | 1         | 0.67%   |
| Unknown MMC Card  7GB               | 1         | 0.67%   |
| Unknown MMC Card  32GB              | 1         | 0.67%   |
| Unknown BJTD4R  32GB                | 1         | 0.67%   |
| Transcend TS32GMTS400 32GB SSD      | 1         | 0.67%   |
| Transcend TS128GSSD360S 128GB       | 1         | 0.67%   |
| Toshiba MQ01ACF032 320GB            | 1         | 0.67%   |
| Toshiba MQ01ABF032 320GB            | 1         | 0.67%   |
| Toshiba MQ01ABD100 1TB              | 1         | 0.67%   |
| Toshiba MQ01ABD075 752GB            | 1         | 0.67%   |
| Toshiba MQ01ABD032 320GB            | 1         | 0.67%   |
| Toshiba MK1656GSYF 160GB            | 1         | 0.67%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1         | 0.67%   |
| SPCC Solid State Disk 512GB         | 1         | 0.67%   |
| SPCC Solid State Disk 128GB         | 1         | 0.67%   |
| SK Hynix NVMe SSD Drive 512GB       | 1         | 0.67%   |
| SK Hynix NVMe SSD Drive 1024GB      | 1         | 0.67%   |
| SK Hynix BC511 NVMe 512GB           | 1         | 0.67%   |
| Seagate ST9250410AS 250GB           | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 34     | 37.88%  |
| WDC                 | 19        | 22     | 28.79%  |
| Toshiba             | 12        | 12     | 18.18%  |
| Hitachi             | 3         | 3      | 4.55%   |
| Samsung Electronics | 2         | 2      | 3.03%   |
| HGST                | 2         | 2      | 3.03%   |
| MAXTOR              | 1         | 1      | 1.52%   |
| JMicron             | 1         | 1      | 1.52%   |
| Apple               | 1         | 2      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 10        | 10     | 18.87%  |
| Samsung Electronics | 8         | 8      | 15.09%  |
| WDC                 | 5         | 5      | 9.43%   |
| Crucial             | 5         | 6      | 9.43%   |
| Kingston            | 4         | 4      | 7.55%   |
| PNY                 | 3         | 3      | 5.66%   |
| Transcend           | 2         | 2      | 3.77%   |
| SPCC                | 2         | 2      | 3.77%   |
| Patriot             | 2         | 2      | 3.77%   |
| A-DATA Technology   | 2         | 2      | 3.77%   |
| SATAFIRM            | 1         | 1      | 1.89%   |
| OCZ                 | 1         | 1      | 1.89%   |
| Micron_1            | 1         | 2      | 1.89%   |
| LITEON              | 1         | 1      | 1.89%   |
| JMicron             | 1         | 1      | 1.89%   |
| HEORIADY            | 1         | 1      | 1.89%   |
| DOGFISH             | 1         | 1      | 1.89%   |
| Apacer              | 1         | 2      | 1.89%   |
| AMD                 | 1         | 1      | 1.89%   |
| ALERTSEAL           | 1         | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 59        | 79     | 46.83%  |
| SSD     | 46        | 56     | 36.51%  |
| NVMe    | 11        | 12     | 8.73%   |
| MMC     | 7         | 11     | 5.56%   |
| Unknown | 3         | 3      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 93        | 127    | 77.5%   |
| NVMe | 11        | 12     | 9.17%   |
| SAS  | 9         | 11     | 7.5%    |
| MMC  | 7         | 11     | 5.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 80     | 60.71%  |
| 0.51-1.0   | 33        | 43     | 29.46%  |
| 1.01-2.0   | 6         | 7      | 5.36%   |
| 3.01-4.0   | 2         | 2      | 1.79%   |
| 2.01-3.0   | 2         | 2      | 1.79%   |
| 4.01-10.0  | 1         | 1      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 29.13%  |
| 251-500        | 24        | 23.3%   |
| 501-1000       | 18        | 17.48%  |
| 21-50          | 12        | 11.65%  |
| 51-100         | 8         | 7.77%   |
| 1001-2000      | 4         | 3.88%   |
| More than 3000 | 3         | 2.91%   |
| 1-20           | 3         | 2.91%   |
| 2001-3000      | 1         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 52        | 49.52%  |
| 1-20      | 30        | 28.57%  |
| 51-100    | 12        | 11.43%  |
| 101-250   | 7         | 6.67%   |
| 251-500   | 2         | 1.9%    |
| 2001-3000 | 2         | 1.9%    |

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
| Detected | 100       | 157    | 97.09%  |
| Works    | 3         | 4      | 2.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 73        | 61.86%  |
| AMD                           | 19        | 16.1%   |
| Samsung Electronics           | 4         | 3.39%   |
| Nvidia                        | 4         | 3.39%   |
| JMicron Technology            | 3         | 2.54%   |
| ASMedia Technology            | 3         | 2.54%   |
| SK Hynix                      | 2         | 1.69%   |
| Sandisk                       | 2         | 1.69%   |
| VIA Technologies              | 1         | 0.85%   |
| Toshiba America Info Systems  | 1         | 0.85%   |
| Silicon Image                 | 1         | 0.85%   |
| Promise Technology            | 1         | 0.85%   |
| Phison Electronics            | 1         | 0.85%   |
| Marvell Technology Group      | 1         | 0.85%   |
| Lenovo                        | 1         | 0.85%   |
| Integrated Technology Express | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 7.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 6.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 4.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 3.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 2.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 2.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 2.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 2.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 2.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 2.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 2.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.1%    |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 1.4%    |
| Nvidia MCP61 SATA Controller                                                            | 2         | 1.4%    |
| JMicron JMB368 IDE controller                                                           | 2         | 1.4%    |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.4%    |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.4%    |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.7%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.7%    |
| SK Hynix Gold P31 SSD                                                                   | 1         | 0.7%    |
| SK Hynix BC511                                                                          | 1         | 0.7%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.7%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.7%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.7%    |
| Promise PDC20262 (FastTrak66/Ultra66)                                                   | 1         | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 1         | 0.7%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1         | 0.7%    |
| Marvell Group 88SE912x IDE Controller                                                   | 1         | 0.7%    |
| Lenovo Non-Volatile memory controller                                                   | 1         | 0.7%    |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.7%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 1         | 0.7%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 1         | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.7%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1         | 0.7%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1         | 0.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.7%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1         | 0.7%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 1         | 0.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 75        | 61.98%  |
| IDE  | 24        | 19.83%  |
| RAID | 11        | 9.09%   |
| NVMe | 11        | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 81        | 79.41%  |
| AMD    | 21        | 20.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 3         | 2.94%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 3         | 2.94%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 2         | 1.96%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 1.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 2         | 1.96%   |
| Intel Core i3 CPU M 350 @ 2.27GHz            | 2         | 1.96%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 2         | 1.96%   |
| AMD FX-8350 Eight-Core Processor             | 2         | 1.96%   |
| AMD A6-9220 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.96%   |
| Intel Xeon Platinum 8171M CPU @ 2.60GHz      | 1         | 0.98%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 0.98%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 0.98%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz       | 1         | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.98%   |
| Intel Core i7-7700 CPU @ 3.60GHz             | 1         | 0.98%   |
| Intel Core i7-7600U CPU @ 2.80GHz            | 1         | 0.98%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 1         | 0.98%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1         | 0.98%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.98%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.98%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 0.98%   |
| Intel Core i7-2820QM CPU @ 2.30GHz           | 1         | 0.98%   |
| Intel Core i7-2620M CPU @ 2.70GHz            | 1         | 0.98%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 0.98%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 1         | 0.98%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1         | 0.98%   |
| Intel Core i5-9400 CPU @ 2.90GHz             | 1         | 0.98%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 1         | 0.98%   |
| Intel Core i5-7400 CPU @ 3.00GHz             | 1         | 0.98%   |
| Intel Core i5-6500T CPU @ 2.50GHz            | 1         | 0.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 0.98%   |
| Intel Core i5-4440 CPU @ 3.10GHz             | 1         | 0.98%   |
| Intel Core i5-4210M CPU @ 2.60GHz            | 1         | 0.98%   |
| Intel Core i5-3570K CPU @ 3.40GHz            | 1         | 0.98%   |
| Intel Core i5-3570 CPU @ 3.40GHz             | 1         | 0.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1         | 0.98%   |
| Intel Core i5-3360M CPU @ 2.80GHz            | 1         | 0.98%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 0.98%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 0.98%   |
| Intel Core i5-2310 CPU @ 2.90GHz             | 1         | 0.98%   |
| Intel Core i5-2300 CPU @ 2.80GHz             | 1         | 0.98%   |
| Intel Core i5 CPU M 430 @ 2.27GHz            | 1         | 0.98%   |
| Intel Core i5 CPU 650 @ 3.20GHz              | 1         | 0.98%   |
| Intel Core i3-8130U CPU @ 2.20GHz            | 1         | 0.98%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 0.98%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 0.98%   |
| Intel Core i3-4160 CPU @ 3.60GHz             | 1         | 0.98%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 1         | 0.98%   |
| Intel Core i3-2350M CPU @ 2.30GHz            | 1         | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 1         | 0.98%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 1         | 0.98%   |
| Intel Core i3 CPU M 330 @ 2.13GHz            | 1         | 0.98%   |
| Intel Core i3 CPU 540 @ 3.07GHz              | 1         | 0.98%   |
| Intel Core i3 CPU 530 @ 2.93GHz              | 1         | 0.98%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz        | 1         | 0.98%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz        | 1         | 0.98%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1         | 0.98%   |
| Intel Core 2 Extreme CPU Q9300 @ 2.53GHz     | 1         | 0.98%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz         | 1         | 0.98%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz         | 1         | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 22.55%  |
| Intel Core i7           | 13        | 12.75%  |
| Intel Core i3           | 13        | 12.75%  |
| Intel Core 2 Duo        | 11        | 10.78%  |
| Intel Celeron           | 5         | 4.9%    |
| Intel Atom              | 5         | 4.9%    |
| AMD FX                  | 4         | 3.92%   |
| Intel Core 2 Quad       | 3         | 2.94%   |
| AMD Ryzen 5             | 3         | 2.94%   |
| AMD A6                  | 3         | 2.94%   |
| Intel Pentium Dual      | 2         | 1.96%   |
| Intel Core 2            | 2         | 1.96%   |
| AMD Ryzen 7             | 2         | 1.96%   |
| AMD E                   | 2         | 1.96%   |
| Intel Xeon Platinum     | 1         | 0.98%   |
| Intel Pentium Dual-Core | 1         | 0.98%   |
| Intel Core 2 Extreme    | 1         | 0.98%   |
| Intel Celeron Dual-Core | 1         | 0.98%   |
| AMD Phenom II X4        | 1         | 0.98%   |
| AMD Phenom II X2        | 1         | 0.98%   |
| AMD E2                  | 1         | 0.98%   |
| AMD Athlon II X2        | 1         | 0.98%   |
| AMD Athlon              | 1         | 0.98%   |
| AMD A8                  | 1         | 0.98%   |
| AMD A10                 | 1         | 0.98%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 59        | 57.84%  |
| 4      | 33        | 32.35%  |
| 6      | 4         | 3.92%   |
| 8      | 2         | 1.96%   |
| 3      | 2         | 1.96%   |
| 26     | 1         | 0.98%   |
| 1      | 1         | 0.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 102       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 51        | 50%     |
| 1      | 51        | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 102       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 13        | 12.75%  |
| 0x206a7    | 10        | 9.8%    |
| 0x306a9    | 6         | 5.88%   |
| 0x20652    | 6         | 5.88%   |
| 0x306c3    | 5         | 4.9%    |
| 0x506e3    | 4         | 3.92%   |
| 0x6fd      | 3         | 2.94%   |
| 0x406c4    | 3         | 2.94%   |
| 0x306d4    | 3         | 2.94%   |
| 0x20655    | 3         | 2.94%   |
| 0x06000852 | 3         | 2.94%   |
| 0x010000c8 | 3         | 2.94%   |
| Unknown    | 3         | 2.94%   |
| 0x906e9    | 2         | 1.96%   |
| 0x806ea    | 2         | 1.96%   |
| 0x806e9    | 2         | 1.96%   |
| 0x40651    | 2         | 1.96%   |
| 0x30678    | 2         | 1.96%   |
| 0x106e5    | 2         | 1.96%   |
| 0x10676    | 2         | 1.96%   |
| 0x06006705 | 2         | 1.96%   |
| 0x06001119 | 2         | 1.96%   |
| 0x05000119 | 2         | 1.96%   |
| 0x906ed    | 1         | 0.98%   |
| 0x906ea    | 1         | 0.98%   |
| 0x706a8    | 1         | 0.98%   |
| 0x6fb      | 1         | 0.98%   |
| 0x6f6      | 1         | 0.98%   |
| 0x6f2      | 1         | 0.98%   |
| 0x50654    | 1         | 0.98%   |
| 0x30673    | 1         | 0.98%   |
| 0x30661    | 1         | 0.98%   |
| 0x0a50000c | 1         | 0.98%   |
| 0x08701021 | 1         | 0.98%   |
| 0x08108109 | 1         | 0.98%   |
| 0x08101016 | 1         | 0.98%   |
| 0x08001138 | 1         | 0.98%   |
| 0x06006704 | 1         | 0.98%   |
| 0x0600063e | 1         | 0.98%   |
| 0x03000027 | 1         | 0.98%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 15        | 14.71%  |
| SandyBridge   | 10        | 9.8%    |
| Westmere      | 9         | 8.82%   |
| Haswell       | 9         | 8.82%   |
| KabyLake      | 8         | 7.84%   |
| Silvermont    | 6         | 5.88%   |
| IvyBridge     | 6         | 5.88%   |
| Core          | 6         | 5.88%   |
| Skylake       | 5         | 4.9%    |
| Piledriver    | 5         | 4.9%    |
| K10           | 3         | 2.94%   |
| Excavator     | 3         | 2.94%   |
| Broadwell     | 3         | 2.94%   |
| Zen 2         | 2         | 1.96%   |
| Zen           | 2         | 1.96%   |
| Nehalem       | 2         | 1.96%   |
| Bobcat        | 2         | 1.96%   |
| Zen+          | 1         | 0.98%   |
| Zen 3         | 1         | 0.98%   |
| K10 Llano     | 1         | 0.98%   |
| Goldmont plus | 1         | 0.98%   |
| Bulldozer     | 1         | 0.98%   |
| Bonnell       | 1         | 0.98%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 56        | 48.28%  |
| Nvidia | 36        | 31.03%  |
| AMD    | 24        | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 6.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 5.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 5.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 3.36%   |
| Intel HD Graphics 530                                                                    | 3         | 2.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.68%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 2         | 1.68%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.68%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.68%   |
| Intel HD Graphics 620                                                                    | 2         | 1.68%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.68%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 1.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.84%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.84%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.84%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.84%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.84%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.84%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.84%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.84%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1         | 0.84%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.84%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.84%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.84%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 0.84%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.84%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1         | 0.84%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.84%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.84%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.84%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.84%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.84%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.84%   |
| Nvidia G96CM [GeForce GT 220M]                                                           | 1         | 0.84%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.84%   |
| Nvidia G96CM [GeForce 9600M GS]                                                          | 1         | 0.84%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 0.84%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 1         | 0.84%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.84%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.84%   |
| Intel HD Graphics 630                                                                    | 1         | 0.84%   |
| Intel HD Graphics                                                                        | 1         | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 0.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.84%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.84%   |
| Intel 82G35 Express Integrated Graphics Controller                                       | 1         | 0.84%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 41.18%  |
| 1 x Nvidia     | 25        | 24.51%  |
| 1 x AMD        | 21        | 20.59%  |
| Intel + Nvidia | 10        | 9.8%    |
| Intel + AMD    | 2         | 1.96%   |
| 2 x Nvidia     | 1         | 0.98%   |
| 2 x AMD        | 1         | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 87        | 85.29%  |
| Proprietary | 8         | 7.84%   |
| Unknown     | 7         | 6.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 49.02%  |
| 0.51-1.0   | 15        | 14.71%  |
| 0.01-0.5   | 15        | 14.71%  |
| 1.01-2.0   | 11        | 10.78%  |
| 3.01-4.0   | 4         | 3.92%   |
| 2.01-3.0   | 4         | 3.92%   |
| 5.01-6.0   | 2         | 1.96%   |
| 7.01-8.0   | 1         | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 18.75%  |
| LG Display              | 16        | 16.67%  |
| AU Optronics            | 10        | 10.42%  |
| Chimei Innolux          | 6         | 6.25%   |
| Ancor Communications    | 6         | 6.25%   |
| Goldstar                | 4         | 4.17%   |
| Dell                    | 4         | 4.17%   |
| AOC                     | 4         | 4.17%   |
| Philips                 | 3         | 3.13%   |
| Hewlett-Packard         | 3         | 3.13%   |
| Acer                    | 3         | 3.13%   |
| ViewSonic               | 2         | 2.08%   |
| LG Philips              | 2         | 2.08%   |
| BOE                     | 2         | 2.08%   |
| Apple                   | 2         | 2.08%   |
| ___                     | 1         | 1.04%   |
| Tech Concepts           | 1         | 1.04%   |
| PANDA                   | 1         | 1.04%   |
| Microstep               | 1         | 1.04%   |
| Lenovo                  | 1         | 1.04%   |
| Insignia                | 1         | 1.04%   |
| Idek Iiyama             | 1         | 1.04%   |
| HKC                     | 1         | 1.04%   |
| Chi Mei Optoelectronics | 1         | 1.04%   |
| BenQ                    | 1         | 1.04%   |
| Unknown                 | 1         | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch | 2         | 2.04%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch | 2         | 2.04%   |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch | 2         | 2.04%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 2         | 2.04%   |
| ___ AAA ___01FF 1366x768 700x390mm 31.5-inch                         | 1         | 1.02%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch        | 1         | 1.02%   |
| ViewSonic VA2013wSERIES VSCF122 1600x900 443x249mm 20.0-inch         | 1         | 1.02%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                           | 1         | 1.02%   |
| Samsung Electronics T24C310 SAM0AEA 1920x1080 531x299mm 24.0-inch    | 1         | 1.02%   |
| Samsung Electronics SMT22A550 SAM07AE 1920x1080 477x268mm 21.5-inch  | 1         | 1.02%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch    | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                     | 1         | 1.02%   |
| Samsung Electronics LCD Monitor S24B300 3840x1080                    | 1         | 1.02%   |
| Philips PHL 241P4 PHL08D5 1920x1080 531x299mm 24.0-inch              | 1         | 1.02%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch            | 1         | 1.02%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                   | 1         | 1.02%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch              | 1         | 1.02%   |
| Microstep LCD Monitor MSI MAG341CQ 3440x1440                         | 1         | 1.02%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch          | 1         | 1.02%   |
| LG Philips LCD Monitor LPL012B 1280x800 304x190mm 14.1-inch          | 1         | 1.02%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch        | 1         | 1.02%   |
| LG Display LCD Monitor LGD7001 1366x768 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch         | 1         | 1.02%   |
| LG Display LCD Monitor LGD0589 1920x1080 294x165mm 13.3-inch         | 1         | 1.02%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 1.02%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 1.02%   |
| LG Display LCD Monitor LGD02A6 1366x768 345x194mm 15.6-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch         | 1         | 1.02%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD01AF 1680x1050 331x207mm 15.4-inch         | 1         | 1.02%   |
| LG Display LCD Monitor LGD018E 1920x1200 367x230mm 17.1-inch         | 1         | 1.02%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch              | 1         | 1.02%   |
| Insignia NS28D310NA15 BBY0028 1680x1050 640x384mm 29.4-inch          | 1         | 1.02%   |
| Idek Iiyama LCD Monitor PL2473HD 1920x1080                           | 1         | 1.02%   |
| HKC LCD Monitor HKC2400 1920x1080 597x336mm 27.0-inch                | 1         | 1.02%   |
| Hewlett-Packard v185e HWP2838 1366x768 410x230mm 18.5-inch           | 1         | 1.02%   |
| Hewlett-Packard LCD Monitor w2338h                                   | 1         | 1.02%   |
| Hewlett-Packard Compaq W185q HWP284F 1366x768 410x230mm 18.5-inch    | 1         | 1.02%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 1         | 1.02%   |
| Goldstar RZ32LZ55 GSM7546 1360x768 930x523mm 42.0-inch               | 1         | 1.02%   |
| Goldstar M237WDP GSM5778 1920x1080 510x290mm 23.1-inch               | 1         | 1.02%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 1         | 1.02%   |
| Goldstar 32LG7000 GSM765E 1920x1080 700x390mm 31.5-inch              | 1         | 1.02%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                | 1         | 1.02%   |
| Dell E2216HV DELF06F 1920x1080 476x268mm 21.5-inch                   | 1         | 1.02%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 1         | 1.02%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch             | 1         | 1.02%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch      | 1         | 1.02%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 33        | 35.48%  |
| 1920x1080 (FHD)    | 24        | 25.81%  |
| 1600x900 (HD+)     | 8         | 8.6%    |
| 3840x2160 (4K)     | 5         | 5.38%   |
| 1360x768           | 5         | 5.38%   |
| 1440x900 (WXGA+)   | 4         | 4.3%    |
| 1680x1050 (WSXGA+) | 3         | 3.23%   |
| 1280x800 (WXGA)    | 3         | 3.23%   |
| 1920x1200 (WUXGA)  | 2         | 2.15%   |
| 3840x1080          | 1         | 1.08%   |
| 3440x1440          | 1         | 1.08%   |
| 2560x1440 (QHD)    | 1         | 1.08%   |
| 1280x720 (HD)      | 1         | 1.08%   |
| 1280x1024 (SXGA)   | 1         | 1.08%   |
| Unknown            | 1         | 1.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 28.13%  |
| 17      | 10        | 10.42%  |
| 27      | 8         | 8.33%   |
| 14      | 7         | 7.29%   |
| 24      | 6         | 6.25%   |
| 21      | 6         | 6.25%   |
| 31      | 5         | 5.21%   |
| 18      | 5         | 5.21%   |
| 13      | 5         | 5.21%   |
| Unknown | 5         | 5.21%   |
| 19      | 4         | 4.17%   |
| 23      | 2         | 2.08%   |
| 22      | 2         | 2.08%   |
| 11      | 2         | 2.08%   |
| 42      | 1         | 1.04%   |
| 20      | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 38.3%   |
| 401-500     | 17        | 18.09%  |
| 501-600     | 13        | 13.83%  |
| 351-400     | 11        | 11.7%   |
| 601-700     | 6         | 6.38%   |
| 201-300     | 5         | 5.32%   |
| Unknown     | 5         | 5.32%   |
| 901-1000    | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 74.73%  |
| 16/10   | 16        | 17.58%  |
| Unknown | 5         | 5.49%   |
| 5/4     | 2         | 2.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 28.42%  |
| 201-250        | 10        | 10.53%  |
| 81-90          | 9         | 9.47%   |
| 301-350        | 8         | 8.42%   |
| 151-200        | 8         | 8.42%   |
| 141-150        | 6         | 6.32%   |
| 131-140        | 6         | 6.32%   |
| 351-500        | 5         | 5.26%   |
| Unknown        | 5         | 5.26%   |
| 71-80          | 3         | 3.16%   |
| 121-130        | 3         | 3.16%   |
| 51-60          | 2         | 2.11%   |
| 251-300        | 2         | 2.11%   |
| 501-1000       | 1         | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 36        | 38.71%  |
| 51-100  | 33        | 35.48%  |
| 121-160 | 12        | 12.9%   |
| 1-50    | 5         | 5.38%   |
| Unknown | 5         | 5.38%   |
| 161-240 | 2         | 2.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 86        | 84.31%  |
| 2     | 9         | 8.82%   |
| 0     | 6         | 5.88%   |
| 3     | 1         | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 63        | 38.65%  |
| Intel                           | 36        | 22.09%  |
| Qualcomm Atheros                | 17        | 10.43%  |
| Broadcom                        | 17        | 10.43%  |
| Broadcom Limited                | 7         | 4.29%   |
| Ralink                          | 4         | 2.45%   |
| Nvidia                          | 4         | 2.45%   |
| TP-Link                         | 2         | 1.23%   |
| Samsung Electronics             | 2         | 1.23%   |
| MEDIATEK                        | 2         | 1.23%   |
| Marvell Technology Group        | 2         | 1.23%   |
| Toshiba                         | 1         | 0.61%   |
| Ralink Technology               | 1         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.61%   |
| Motorola PCS                    | 1         | 0.61%   |
| Lenovo                          | 1         | 0.61%   |
| Huawei Technologies             | 1         | 0.61%   |
| D-Link                          | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 46        | 24.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 9         | 4.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4         | 2.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 4         | 2.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 4         | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3         | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.62%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 1.62%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 1.62%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 1.62%   |
| Intel 82579V Gigabit Network Connection                                                       | 3         | 1.62%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2         | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1.08%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 2         | 1.08%   |
| Nvidia MCP79 Ethernet                                                                         | 2         | 1.08%   |
| Nvidia MCP61 Ethernet                                                                         | 2         | 1.08%   |
| Intel Wireless 3160                                                                           | 2         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                                                      | 2         | 1.08%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                                     | 2         | 1.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 1.08%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 0.54%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 0.54%   |
| Toshiba F5521gw                                                                               | 1         | 0.54%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 0.54%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 0.54%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1         | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1         | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 0.54%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.54%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                                              | 1         | 0.54%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.54%   |
| Realtek 802.11n                                                                               | 1         | 0.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.54%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1         | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 1         | 0.54%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1         | 0.54%   |
| Motorola PCS moto g(7) optimo maxx(XT1955DL)                                                  | 1         | 0.54%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 0.54%   |
| MediaTek 802.11 n WLAN                                                                        | 1         | 0.54%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.54%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                                         | 1         | 0.54%   |
| Lenovo Thinkpad USB LAN                                                                       | 1         | 0.54%   |
| Intel Wireless 7265                                                                           | 1         | 0.54%   |
| Intel Wireless 7260                                                                           | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 31.71%  |
| Realtek Semiconductor           | 15        | 18.29%  |
| Broadcom                        | 15        | 18.29%  |
| Qualcomm Atheros                | 13        | 15.85%  |
| Ralink                          | 4         | 4.88%   |
| TP-Link                         | 2         | 2.44%   |
| MEDIATEK                        | 2         | 2.44%   |
| Broadcom Limited                | 2         | 2.44%   |
| Ralink Technology               | 1         | 1.22%   |
| Qualcomm Atheros Communications | 1         | 1.22%   |
| D-Link                          | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4         | 4.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 4         | 4.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 4         | 4.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3         | 3.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 3.66%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 3.66%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 3.66%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 3.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 2.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 2.44%   |
| Intel Wireless 3160                                                                           | 2         | 2.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 2.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 2.44%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 2.44%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 1.22%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 1.22%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 1.22%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.22%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 1.22%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 1.22%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1         | 1.22%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 1.22%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.22%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 1.22%   |
| Realtek 802.11n                                                                               | 1         | 1.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.22%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.22%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.22%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1         | 1.22%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 1.22%   |
| MediaTek 802.11 n WLAN                                                                        | 1         | 1.22%   |
| Intel Wireless 7265                                                                           | 1         | 1.22%   |
| Intel Wireless 7260                                                                           | 1         | 1.22%   |
| Intel WiFi Link 5100                                                                          | 1         | 1.22%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 1.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.22%   |
| Intel Centrino Wireless-N 2230                                                                | 1         | 1.22%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                                 | 1         | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.22%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1         | 1.22%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.22%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                   | 1         | 1.22%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1         | 1.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1         | 1.22%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 1.22%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 57        | 56.44%  |
| Intel                    | 17        | 16.83%  |
| Broadcom                 | 6         | 5.94%   |
| Qualcomm Atheros         | 5         | 4.95%   |
| Broadcom Limited         | 5         | 4.95%   |
| Nvidia                   | 4         | 3.96%   |
| Samsung Electronics      | 2         | 1.98%   |
| Marvell Technology Group | 2         | 1.98%   |
| Motorola PCS             | 1         | 0.99%   |
| Lenovo                   | 1         | 0.99%   |
| Huawei Technologies      | 1         | 0.99%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 45.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 8.82%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 2.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.96%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.96%   |
| Nvidia MCP61 Ethernet                                             | 2         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.96%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 1.96%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.98%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.98%   |
| Motorola PCS moto g(7) optimo maxx(XT1955DL)                      | 1         | 0.98%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.98%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.98%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 0.98%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.98%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.98%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.98%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.98%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.98%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.98%   |
| Intel 82566DC Gigabit Network Connection                          | 1         | 0.98%   |
| Huawei E353/E3131                                                 | 1         | 0.98%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.98%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.98%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.98%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.98%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.98%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1         | 0.98%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.98%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 96        | 55.17%  |
| WiFi     | 77        | 44.25%  |
| Modem    | 1         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 91        | 57.59%  |
| WiFi     | 67        | 42.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 62.75%  |
| 1     | 32        | 31.37%  |
| 0     | 5         | 4.9%    |
| 4     | 1         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 63        | 61.76%  |
| Yes  | 39        | 38.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 27.78%  |
| Cambridge Silicon Radio         | 7         | 12.96%  |
| Qualcomm Atheros Communications | 4         | 7.41%   |
| Dell                            | 4         | 7.41%   |
| Broadcom                        | 4         | 7.41%   |
| Realtek Semiconductor           | 3         | 5.56%   |
| Hewlett-Packard                 | 3         | 5.56%   |
| Foxconn / Hon Hai               | 3         | 5.56%   |
| Apple                           | 3         | 5.56%   |
| Lite-On Technology              | 2         | 3.7%    |
| ASUSTek Computer                | 2         | 3.7%    |
| Toshiba                         | 1         | 1.85%   |
| Ralink                          | 1         | 1.85%   |
| IMC Networks                    | 1         | 1.85%   |
| Askey Computer                  | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 12.96%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 12.96%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 5.56%   |
| Intel AX200 Bluetooth                               | 3         | 5.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.7%    |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 3.7%    |
| Dell DW375 Bluetooth Module                         | 2         | 3.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 3.7%    |
| Apple Bluetooth USB Host Controller                 | 2         | 3.7%    |
| Toshiba Askey Bluetooth Module                      | 1         | 1.85%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.85%   |
| Lite-On Atheros Bluetooth                           | 1         | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.85%   |
| IMC Networks Bluetooth Device                       | 1         | 1.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.85%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.85%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.85%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.85%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.85%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.85%   |
| Askey Bluetooth Device                              | 1         | 1.85%   |
| Apple Bluetooth Host Controller                     | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 72        | 48.98%  |
| Nvidia                    | 29        | 19.73%  |
| AMD                       | 29        | 19.73%  |
| C-Media Electronics       | 4         | 2.72%   |
| GN Netcom                 | 3         | 2.04%   |
| Texas Instruments         | 1         | 0.68%   |
| Sennheiser Communications | 1         | 0.68%   |
| ROCCAT                    | 1         | 0.68%   |
| Realtek Semiconductor     | 1         | 0.68%   |
| Microsoft                 | 1         | 0.68%   |
| M-Audio                   | 1         | 0.68%   |
| JMTek                     | 1         | 0.68%   |
| iSoft Silicon             | 1         | 0.68%   |
| Creative Labs             | 1         | 0.68%   |
| AOKEO                     | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 7.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 6.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 6.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 4.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 3.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 2.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 2.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 2.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.35%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.35%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 2.35%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.76%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.76%   |
| AMD High Definition Audio Controller                                       | 3         | 1.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.76%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.18%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.18%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.18%   |
| Nvidia GK110 High Definition Audio Controller                              | 2         | 1.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.18%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.18%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 1.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.18%   |
| Texas Instruments PCM2903B Audio CODEC                                     | 1         | 0.59%   |
| Sennheiser Communications PXC 550                                          | 1         | 0.59%   |
| ROCCAT Juke                                                                | 1         | 0.59%   |
| Realtek Semiconductor Realtek USB audio                                    | 1         | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.59%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.59%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.59%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.59%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.59%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.59%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GF104 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia Audio device                                                        | 1         | 0.59%   |
| Microsoft LifeChat LX-3000 Headset                                         | 1         | 0.59%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 0.59%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.59%   |
| iSoft Silicon USB Ear-Microphone                                           | 1         | 0.59%   |
| Intel Lewisburg MROM 0                                                     | 1         | 0.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.59%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 0.59%   |
| GN Netcom Jabra Link 380                                                   | 1         | 0.59%   |
| GN Netcom Jabra Link 370                                                   | 1         | 0.59%   |

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
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 1         | 12.5%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 12.5%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 1         | 12.5%   |
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
| Chicony Electronics                    | 12        | 19.67%  |
| Silicon Motion                         | 5         | 8.2%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 8.2%    |
| Microdia                               | 4         | 6.56%   |
| Acer                                   | 4         | 6.56%   |
| Quanta                                 | 3         | 4.92%   |
| Apple                                  | 3         | 4.92%   |
| Suyin                                  | 2         | 3.28%   |
| Sunplus Innovation Technology          | 2         | 3.28%   |
| Ricoh                                  | 2         | 3.28%   |
| Realtek Semiconductor                  | 2         | 3.28%   |
| Primax Electronics                     | 2         | 3.28%   |
| Microsoft                              | 2         | 3.28%   |
| Logitech                               | 2         | 3.28%   |
| Z-Star Microelectronics                | 1         | 1.64%   |
| USB Camera                             | 1         | 1.64%   |
| Syntek                                 | 1         | 1.64%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 1.64%   |
| Samsung Electronics                    | 1         | 1.64%   |
| Jieli Technology                       | 1         | 1.64%   |
| HD WEBCAM                              | 1         | 1.64%   |
| HD 2MP WEBCAM                          | 1         | 1.64%   |
| Creative Technology                    | 1         | 1.64%   |
| ALi                                    | 1         | 1.64%   |
| Alcor Micro                            | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus HD WebCam                                              | 2         | 3.28%   |
| Realtek USB Camera                                             | 2         | 3.28%   |
| Quanta HP Webcam                                               | 2         | 3.28%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 3.28%   |
| Chicony HD WebCam                                              | 2         | 3.28%   |
| Chicony CNF9055 Toshiba Webcam                                 | 2         | 3.28%   |
| Chicony 2.0M UVC Webcam / CNF7129                              | 2         | 3.28%   |
| Apple Built-in iSight                                          | 2         | 3.28%   |
| Acer Lenovo EasyCamera                                         | 2         | 3.28%   |
| Z-Star WebCam SC-03FFL11739P                                   | 1         | 1.64%   |
| USB Camera USB Camera                                          | 1         | 1.64%   |
| Syntek Lenovo EasyCamera                                       | 1         | 1.64%   |
| Suyin UVC HD Webcam                                            | 1         | 1.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 1.64%   |
| Silicon Motion WebCam SCB-1100N                                | 1         | 1.64%   |
| Silicon Motion WebCam SCB-0385N                                | 1         | 1.64%   |
| Silicon Motion WebCam SC-0311139N                              | 1         | 1.64%   |
| Silicon Motion SM731 Camera                                    | 1         | 1.64%   |
| Silicon Motion 300k Pixel Camera                               | 1         | 1.64%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960                 | 1         | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 1.64%   |
| Ricoh Laptop_Integrated_Webcam_3M                              | 1         | 1.64%   |
| Ricoh Integrated Webcam                                        | 1         | 1.64%   |
| Quanta Laptop_Integrated_Webcam_2HDM                           | 1         | 1.64%   |
| Primax HP Webcam-101                                           | 1         | 1.64%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 1.64%   |
| Microsoft LifeCam VX-5000                                      | 1         | 1.64%   |
| Microsoft LifeCam VX-500 [1357]                                | 1         | 1.64%   |
| Microdia Lenovo EasyCamera                                     | 1         | 1.64%   |
| Microdia Laptop_Integrated_Webcam_0.3M                         | 1         | 1.64%   |
| Logitech Webcam C600                                           | 1         | 1.64%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 1.64%   |
| Jieli USB PHY 2.0                                              | 1         | 1.64%   |
| HD WEBCAM NexiGo N660 FHD Webcam                               | 1         | 1.64%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                                    | 1         | 1.64%   |
| Creative Live! Cam Sync HD [VF0770]                            | 1         | 1.64%   |
| Chicony USB 2.0 Camera                                         | 1         | 1.64%   |
| Chicony HP Webcam                                              | 1         | 1.64%   |
| Chicony HP TrueVision HD Camera                                | 1         | 1.64%   |
| Chicony HP HD Webcam                                           | 1         | 1.64%   |
| Chicony FJ Camera                                              | 1         | 1.64%   |
| Chicony CNF7042                                                | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 1         | 1.64%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 1.64%   |
| ALi Gateway Webcam                                             | 1         | 1.64%   |
| Alcor Micro USB 2.0 PC cam                                     | 1         | 1.64%   |
| Acer SunplusIT Integrated Camera                               | 1         | 1.64%   |
| Acer Crystal Eye webcam                                        | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 66.67%  |
| AuthenTec        | 2         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS451 Fingerprint Reader | 2         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 16.67%  |
| Validity Sensors VFS491                    | 1         | 16.67%  |
| AuthenTec Fingerprint Sensor               | 1         | 16.67%  |
| AuthenTec AES2550 Fingerprint Sensor       | 1         | 16.67%  |

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
| 0     | 72        | 70.59%  |
| 1     | 24        | 23.53%  |
| 2     | 6         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 10        | 30.3%   |
| Net/wireless          | 6         | 18.18%  |
| Fingerprint reader    | 6         | 18.18%  |
| Storage               | 3         | 9.09%   |
| Multimedia controller | 3         | 9.09%   |
| Chipcard              | 3         | 9.09%   |
| Unassigned class      | 1         | 3.03%   |
| Bluetooth             | 1         | 3.03%   |


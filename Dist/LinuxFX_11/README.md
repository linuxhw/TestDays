LinuxFX 11 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for LinuxFX 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LinuxFX_11/Desktop/README.md) and [notebooks](/Dist/LinuxFX_11/Notebook/README.md).

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

Total: 169

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T420 4180MY7       | Notebook    | [e6a930e933](https://linux-hardware.org/?probe=e6a930e933) | Sep 19, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a0177bc58d](https://linux-hardware.org/?probe=a0177bc58d) | Aug 05, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [740ba48457](https://linux-hardware.org/?probe=740ba48457) | Jul 03, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | Notebook    | [a57e4e84f8](https://linux-hardware.org/?probe=a57e4e84f8) | Jun 29, 2022 |
| Toshiba       | Satellite A215              | Notebook    | [f609309a08](https://linux-hardware.org/?probe=f609309a08) | Jun 19, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [bcca05b660](https://linux-hardware.org/?probe=bcca05b660) | Jun 19, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [adc58c941b](https://linux-hardware.org/?probe=adc58c941b) | Jun 07, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [07a415d261](https://linux-hardware.org/?probe=07a415d261) | Jun 02, 2022 |
| Dell          | Latitude 7389               | Convertible | [c7c04eece7](https://linux-hardware.org/?probe=c7c04eece7) | May 27, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d9ed530aa9](https://linux-hardware.org/?probe=d9ed530aa9) | May 04, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [ab72c3ae3f](https://linux-hardware.org/?probe=ab72c3ae3f) | May 03, 2022 |
| Dell          | Precision M4800             | Notebook    | [44583b1142](https://linux-hardware.org/?probe=44583b1142) | May 02, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [a7396f278d](https://linux-hardware.org/?probe=a7396f278d) | May 02, 2022 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [7d75948e9a](https://linux-hardware.org/?probe=7d75948e9a) | May 01, 2022 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [1d3dfb69e7](https://linux-hardware.org/?probe=1d3dfb69e7) | May 01, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [0e0d0dd3aa](https://linux-hardware.org/?probe=0e0d0dd3aa) | Apr 30, 2022 |
| Positivo      | C464C                       | Convertible | [c4bf224f57](https://linux-hardware.org/?probe=c4bf224f57) | Apr 15, 2022 |
| Dell          | Precision M4700             | Notebook    | [850dba476c](https://linux-hardware.org/?probe=850dba476c) | Apr 15, 2022 |
| Acer          | Aspire 7735                 | Notebook    | [e54c0831d6](https://linux-hardware.org/?probe=e54c0831d6) | Apr 07, 2022 |
| MSI           | X58M                        | Desktop     | [d4146d0724](https://linux-hardware.org/?probe=d4146d0724) | Apr 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8aeaa381e8](https://linux-hardware.org/?probe=8aeaa381e8) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [722346a184](https://linux-hardware.org/?probe=722346a184) | Apr 03, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [0834bd783c](https://linux-hardware.org/?probe=0834bd783c) | Mar 30, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [3f0b633075](https://linux-hardware.org/?probe=3f0b633075) | Mar 30, 2022 |
| Dell          | Latitude 7389               | Convertible | [994b9bbd25](https://linux-hardware.org/?probe=994b9bbd25) | Mar 27, 2022 |
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
| Dell          | Latitude E6420              | Notebook    | [85d1f4fe0a](https://linux-hardware.org/?probe=85d1f4fe0a) | Feb 09, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [cc840b5085](https://linux-hardware.org/?probe=cc840b5085) | Feb 05, 2022 |
| HP            | ProBook 4720s               | Notebook    | [aa5c35966f](https://linux-hardware.org/?probe=aa5c35966f) | Feb 04, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [175d1e66d3](https://linux-hardware.org/?probe=175d1e66d3) | Feb 02, 2022 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [f508e8a6f8](https://linux-hardware.org/?probe=f508e8a6f8) | Jan 31, 2022 |
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
| Pegatron      | 2A99                        | Desktop     | [29fd6eae29](https://linux-hardware.org/?probe=29fd6eae29) | Oct 27, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7be969965e](https://linux-hardware.org/?probe=7be969965e) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [c53ba56444](https://linux-hardware.org/?probe=c53ba56444) | Oct 23, 2021 |
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
| HP            | G62                         | Notebook    | [6cbed79ca9](https://linux-hardware.org/?probe=6cbed79ca9) | Oct 05, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| Dell          | Precision M6400             | Notebook    | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [1e1bf5e8e0](https://linux-hardware.org/?probe=1e1bf5e8e0) | Oct 03, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [0778440642](https://linux-hardware.org/?probe=0778440642) | Oct 02, 2021 |
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
| Dell          | System XPS L502X            | Notebook    | [763d21b747](https://linux-hardware.org/?probe=763d21b747) | Sep 26, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [c94e1e1031](https://linux-hardware.org/?probe=c94e1e1031) | Sep 26, 2021 |
| HP            | Pavilion 14                 | Notebook    | [2ab5781fef](https://linux-hardware.org/?probe=2ab5781fef) | Sep 25, 2021 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-37-generic | 15        | 12%     |
| 5.13.0-27-generic | 13        | 10.4%   |
| 5.11.0-43-generic | 12        | 9.6%    |
| 5.11.0-38-generic | 11        | 8.8%    |
| 5.13.0-28-generic | 10        | 8%      |
| 5.11.0-41-generic | 10        | 8%      |
| 5.11.0-40-generic | 10        | 8%      |
| 5.11.0-36-generic | 7         | 5.6%    |
| 5.13.0-39-generic | 6         | 4.8%    |
| 5.11.0-34-generic | 6         | 4.8%    |
| 5.13.0-30-generic | 5         | 4%      |
| 5.11.0-46-generic | 5         | 4%      |
| 5.13.0-44-generic | 3         | 2.4%    |
| 5.13.0-40-generic | 3         | 2.4%    |
| 5.13.0-51-generic | 2         | 1.6%    |
| 5.13.0-35-generic | 2         | 1.6%    |
| 5.15.0-46-generic | 1         | 0.8%    |
| 5.15.0-41-generic | 1         | 0.8%    |
| 5.13.0-25-generic | 1         | 0.8%    |
| 5.11.0-44-generic | 1         | 0.8%    |
| 5.11.0-42-generic | 1         | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 74        | 61.67%  |
| 5.13.0  | 44        | 36.67%  |
| 5.15.0  | 2         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 74        | 61.67%  |
| 5.13    | 44        | 36.67%  |
| 5.15    | 2         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 118       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 113       | 94.96%  |
| KDE        | 5         | 4.2%    |
| X-Cinnamon | 1         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 116       | 98.31%  |
| Wayland | 2         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 101       | 85.59%  |
| SDDM    | 17        | 14.41%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 29        | 24.58%  |
| pt_BR | 16        | 13.56%  |
| de_DE | 13        | 11.02%  |
| it_IT | 6         | 5.08%   |
| fr_FR | 6         | 5.08%   |
| pl_PL | 5         | 4.24%   |
| nl_NL | 4         | 3.39%   |
| en_GB | 4         | 3.39%   |
| C     | 4         | 3.39%   |
| en_IN | 3         | 2.54%   |
| en_AU | 3         | 2.54%   |
| es_MX | 2         | 1.69%   |
| en_CA | 2         | 1.69%   |
| el_GR | 2         | 1.69%   |
| cs_CZ | 2         | 1.69%   |
| zh_CN | 1         | 0.85%   |
| sv_SE | 1         | 0.85%   |
| ru_UA | 1         | 0.85%   |
| ru_RU | 1         | 0.85%   |
| pt_PT | 1         | 0.85%   |
| nl_BE | 1         | 0.85%   |
| hr_BA | 1         | 0.85%   |
| fr_CA | 1         | 0.85%   |
| fr_BE | 1         | 0.85%   |
| fi_FI | 1         | 0.85%   |
| es_HN | 1         | 0.85%   |
| es_ES | 1         | 0.85%   |
| es_CO | 1         | 0.85%   |
| es_AR | 1         | 0.85%   |
| en_ZA | 1         | 0.85%   |
| en_NG | 1         | 0.85%   |
| da_DK | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 80        | 67.8%   |
| EFI  | 38        | 32.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 115       | 97.46%  |
| Overlay | 3         | 2.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 115       | 97.46%  |
| GPT     | 2         | 1.69%   |
| MBR     | 1         | 0.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 95.76%  |
| Yes       | 5         | 4.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 92.37%  |
| Yes       | 9         | 7.63%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 15.25%  |
| Dell                | 16        | 13.56%  |
| ASUSTek Computer    | 12        | 10.17%  |
| Acer                | 12        | 10.17%  |
| MSI                 | 9         | 7.63%   |
| Lenovo              | 9         | 7.63%   |
| Positivo            | 5         | 4.24%   |
| Intel               | 5         | 4.24%   |
| Gigabyte Technology | 5         | 4.24%   |
| ASRock              | 5         | 4.24%   |
| Toshiba             | 4         | 3.39%   |
| Samsung Electronics | 4         | 3.39%   |
| Apple               | 3         | 2.54%   |
| Pegatron            | 2         | 1.69%   |
| Google              | 2         | 1.69%   |
| GPU Company         | 1         | 0.85%   |
| Fujitsu Siemens     | 1         | 0.85%   |
| Fujitsu             | 1         | 0.85%   |
| Foxconn             | 1         | 0.85%   |
| ASRockRack          | 1         | 0.85%   |
| Alienware           | 1         | 0.85%   |
| ABIT                | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP 255 G6 Notebook PC                                                                    | 2         | 1.69%   |
| Toshiba TECRA R850                                                                       | 1         | 0.85%   |
| Toshiba Satellite P300                                                                   | 1         | 0.85%   |
| Toshiba Satellite C660                                                                   | 1         | 0.85%   |
| Toshiba Satellite A215                                                                   | 1         | 0.85%   |
| Samsung RV415/RV515/E3415                                                                | 1         | 0.85%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411                                              | 1         | 0.85%   |
| Samsung RF511/RF411/RF711                                                                | 1         | 0.85%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.85%   |
| Positivo Smash3                                                                          | 1         | 0.85%   |
| Positivo Smash                                                                           | 1         | 0.85%   |
| Positivo POS-PIQ67CG                                                                     | 1         | 0.85%   |
| Positivo POS-EIBTPDC                                                                     | 1         | 0.85%   |
| Positivo C464C                                                                           | 1         | 0.85%   |
| Pegatron p6745br                                                                         | 1         | 0.85%   |
| Pegatron NC045AA-ABU IQ525uk                                                             | 1         | 0.85%   |
| MSI MS-7C56                                                                              | 1         | 0.85%   |
| MSI MS-7C37                                                                              | 1         | 0.85%   |
| MSI MS-7B79                                                                              | 1         | 0.85%   |
| MSI MS-7A71                                                                              | 1         | 0.85%   |
| MSI MS-7752                                                                              | 1         | 0.85%   |
| MSI MS-7693                                                                              | 1         | 0.85%   |
| MSI MS-7681                                                                              | 1         | 0.85%   |
| MSI MS-7593                                                                              | 1         | 0.85%   |
| MSI MS-7529                                                                              | 1         | 0.85%   |
| Lenovo ThinkPad T420 4180MY7                                                             | 1         | 0.85%   |
| Lenovo ThinkPad L380 20M6S4E000                                                          | 1         | 0.85%   |
| Lenovo ThinkCentre M82 2929AZ6                                                           | 1         | 0.85%   |
| Lenovo MIIX 310-10ICR 80SG                                                               | 1         | 0.85%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                                                         | 1         | 0.85%   |
| Lenovo IdeaPad Y510P 20217                                                               | 1         | 0.85%   |
| Lenovo G550 2958                                                                         | 1         | 0.85%   |
| Lenovo G50-80 80R0                                                                       | 1         | 0.85%   |
| Lenovo G50-80 80E5                                                                       | 1         | 0.85%   |
| Intel H55                                                                                | 1         | 0.85%   |
| Intel DP55WB AAE64798-205                                                                | 1         | 0.85%   |
| Intel DG35EC AAE29266-202                                                                | 1         | 0.85%   |
| Intel DESKTOP 300                                                                        | 1         | 0.85%   |
| Intel DB85FL AAG89861-203                                                                | 1         | 0.85%   |
| HP ProBook 640 G1                                                                        | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 9         | 7.63%   |
| Dell Latitude        | 5         | 4.24%   |
| Dell Precision       | 4         | 3.39%   |
| Toshiba Satellite    | 3         | 2.54%   |
| HP ProBook           | 3         | 2.54%   |
| HP Pavilion          | 3         | 2.54%   |
| HP Laptop            | 3         | 2.54%   |
| Dell Inspiron        | 3         | 2.54%   |
| Lenovo ThinkPad      | 2         | 1.69%   |
| Lenovo G50-80        | 2         | 1.69%   |
| HP EliteBook         | 2         | 1.69%   |
| HP Compaq            | 2         | 1.69%   |
| HP 255               | 2         | 1.69%   |
| Dell OptiPlex        | 2         | 1.69%   |
| ASUS M5A78L-M        | 2         | 1.69%   |
| Apple MacBookPro5    | 2         | 1.69%   |
| Toshiba TECRA        | 1         | 0.85%   |
| Samsung RV415        | 1         | 0.85%   |
| Samsung RV411        | 1         | 0.85%   |
| Samsung RF511        | 1         | 0.85%   |
| Samsung 355V4C       | 1         | 0.85%   |
| Positivo Smash3      | 1         | 0.85%   |
| Positivo Smash       | 1         | 0.85%   |
| Positivo POS-PIQ67CG | 1         | 0.85%   |
| Positivo POS-EIBTPDC | 1         | 0.85%   |
| Positivo C464C       | 1         | 0.85%   |
| Pegatron p6745br     | 1         | 0.85%   |
| Pegatron NC045AA-ABU | 1         | 0.85%   |
| MSI MS-7C56          | 1         | 0.85%   |
| MSI MS-7C37          | 1         | 0.85%   |
| MSI MS-7B79          | 1         | 0.85%   |
| MSI MS-7A71          | 1         | 0.85%   |
| MSI MS-7752          | 1         | 0.85%   |
| MSI MS-7693          | 1         | 0.85%   |
| MSI MS-7681          | 1         | 0.85%   |
| MSI MS-7593          | 1         | 0.85%   |
| MSI MS-7529          | 1         | 0.85%   |
| Lenovo ThinkCentre   | 1         | 0.85%   |
| Lenovo MIIX          | 1         | 0.85%   |
| Lenovo Legion        | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 22        | 18.64%  |
| 2013 | 11        | 9.32%   |
| 2012 | 10        | 8.47%   |
| 2010 | 10        | 8.47%   |
| 2009 | 10        | 8.47%   |
| 2019 | 8         | 6.78%   |
| 2014 | 8         | 6.78%   |
| 2017 | 7         | 5.93%   |
| 2016 | 6         | 5.08%   |
| 2008 | 6         | 5.08%   |
| 2021 | 5         | 4.24%   |
| 2015 | 5         | 4.24%   |
| 2007 | 4         | 3.39%   |
| 2018 | 3         | 2.54%   |
| 2020 | 2         | 1.69%   |
| 2006 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 66        | 55.93%  |
| Desktop     | 47        | 39.83%  |
| Convertible | 2         | 1.69%   |
| Tablet      | 1         | 0.85%   |
| All in one  | 1         | 0.85%   |
| Server      | 1         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 113       | 95.76%  |
| Enabled  | 5         | 4.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 98.31%  |
| Yes  | 2         | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 32        | 27.12%  |
| 4.01-8.0   | 25        | 21.19%  |
| 8.01-16.0  | 25        | 21.19%  |
| 16.01-24.0 | 19        | 16.1%   |
| 32.01-64.0 | 7         | 5.93%   |
| 1.01-2.0   | 5         | 4.24%   |
| 2.01-3.0   | 3         | 2.54%   |
| 24.01-32.0 | 2         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 61        | 50%     |
| 2.01-3.0  | 32        | 26.23%  |
| 3.01-4.0  | 13        | 10.66%  |
| 0.51-1.0  | 9         | 7.38%   |
| 4.01-8.0  | 5         | 4.1%    |
| 8.01-16.0 | 2         | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 77        | 63.64%  |
| 2      | 29        | 23.97%  |
| 3      | 8         | 6.61%   |
| 4      | 5         | 4.13%   |
| 5      | 2         | 1.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 63.87%  |
| No        | 43        | 36.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 93.22%  |
| No        | 8         | 6.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 75.63%  |
| No        | 29        | 24.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 53.39%  |
| No        | 55        | 46.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 21.01%  |
| Brazil       | 17        | 14.29%  |
| Germany      | 13        | 10.92%  |
| Poland       | 6         | 5.04%   |
| Italy        | 6         | 5.04%   |
| France       | 5         | 4.2%    |
| Canada       | 5         | 4.2%    |
| UK           | 4         | 3.36%   |
| Netherlands  | 4         | 3.36%   |
| India        | 3         | 2.52%   |
| Greece       | 3         | 2.52%   |
| Australia    | 3         | 2.52%   |
| Mexico       | 2         | 1.68%   |
| Czechia      | 2         | 1.68%   |
| Belgium      | 2         | 1.68%   |
| Ukraine      | 1         | 0.84%   |
| Sweden       | 1         | 0.84%   |
| Spain        | 1         | 0.84%   |
| South Africa | 1         | 0.84%   |
| Serbia       | 1         | 0.84%   |
| Russia       | 1         | 0.84%   |
| Puerto Rico  | 1         | 0.84%   |
| Portugal     | 1         | 0.84%   |
| Pakistan     | 1         | 0.84%   |
| Nigeria      | 1         | 0.84%   |
| Namibia      | 1         | 0.84%   |
| Jamaica      | 1         | 0.84%   |
| Honduras     | 1         | 0.84%   |
| Finland      | 1         | 0.84%   |
| Denmark      | 1         | 0.84%   |
| Croatia      | 1         | 0.84%   |
| Colombia     | 1         | 0.84%   |
| China        | 1         | 0.84%   |
| Argentina    | 1         | 0.84%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Rio de Janeiro     | 4         | 3.31%   |
| Warsaw             | 3         | 2.48%   |
| Sao Paulo          | 3         | 2.48%   |
| Lutjegast          | 2         | 1.65%   |
| Hobart             | 2         | 1.65%   |
| Athens             | 2         | 1.65%   |
| Zagreb             | 1         | 0.83%   |
| Wroclaw            | 1         | 0.83%   |
| Winter Springs     | 1         | 0.83%   |
| Windhoek           | 1         | 0.83%   |
| Wilsdruff          | 1         | 0.83%   |
| Wegberg            | 1         | 0.83%   |
| Vivian             | 1         | 0.83%   |
| Vicksburg          | 1         | 0.83%   |
| Toronto            | 1         | 0.83%   |
| Toluca             | 1         | 0.83%   |
| Thungersheim       | 1         | 0.83%   |
| Temple Hills       | 1         | 0.83%   |
| Tegucigalpa        | 1         | 0.83%   |
| Tampere            | 1         | 0.83%   |
| Stourbridge        | 1         | 0.83%   |
| Stockport          | 1         | 0.83%   |
| Stockholm          | 1         | 0.83%   |
| Sparta             | 1         | 0.83%   |
| Skarzysko-Kamienna | 1         | 0.83%   |
| Siegburg           | 1         | 0.83%   |
| Senas              | 1         | 0.83%   |
| Seelze             | 1         | 0.83%   |
| Schenectady        | 1         | 0.83%   |
| Sankt Augustin     | 1         | 0.83%   |
| Salt Lake City     | 1         | 0.83%   |
| Ruda Śląska      | 1         | 0.83%   |
| Rome               | 1         | 0.83%   |
| Rio das Ostras     | 1         | 0.83%   |
| Ringgold           | 1         | 0.83%   |
| Reims              | 1         | 0.83%   |
| Pretoria           | 1         | 0.83%   |
| Prague             | 1         | 0.83%   |
| Porto              | 1         | 0.83%   |
| Port Coquitlam     | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 37     | 17.79%  |
| WDC                 | 28        | 34     | 17.18%  |
| Samsung Electronics | 19        | 23     | 11.66%  |
| Toshiba             | 13        | 13     | 7.98%   |
| SanDisk             | 12        | 12     | 7.36%   |
| Unknown             | 7         | 12     | 4.29%   |
| Hitachi             | 6         | 6      | 3.68%   |
| Crucial             | 6         | 7      | 3.68%   |
| Kingston            | 4         | 4      | 2.45%   |
| JMicron Technology  | 4         | 4      | 2.45%   |
| SPCC                | 3         | 4      | 1.84%   |
| PNY                 | 3         | 3      | 1.84%   |
| Transcend           | 2         | 2      | 1.23%   |
| SK hynix            | 2         | 3      | 1.23%   |
| Patriot             | 2         | 2      | 1.23%   |
| HGST                | 2         | 2      | 1.23%   |
| Apple               | 2         | 3      | 1.23%   |
| A-DATA Technology   | 2         | 2      | 1.23%   |
| SATAFIRM            | 1         | 1      | 0.61%   |
| Phison              | 1         | 1      | 0.61%   |
| OCZ                 | 1         | 1      | 0.61%   |
| Micron_1            | 1         | 1      | 0.61%   |
| Maxtor              | 1         | 1      | 0.61%   |
| LITEON              | 1         | 1      | 0.61%   |
| Leven               | 1         | 1      | 0.61%   |
| Lenovo              | 1         | 1      | 0.61%   |
| KingFast            | 1         | 1      | 0.61%   |
| I/OMAGIC            | 1         | 1      | 0.61%   |
| HEORIADY            | 1         | 1      | 0.61%   |
| Dogfish             | 1         | 1      | 0.61%   |
| Apacer              | 1         | 2      | 0.61%   |
| AMD                 | 1         | 1      | 0.61%   |
| ALERTSEAL           | 1         | 1      | 0.61%   |
| AFOX                | 1         | 1      | 0.61%   |
| Unknown             | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 5         | 2.81%   |
| Seagate ST1000DM010-2EP102 1TB     | 4         | 2.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.69%   |
| SanDisk SDSSDX240GG25 240GB        | 3         | 1.69%   |
| Samsung NVMe SSD Drive 500GB       | 3         | 1.69%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 1.69%   |
| Crucial CT1000MX500SSD1 1TB        | 3         | 1.69%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 1.12%   |
| Toshiba MQ04ABF100 1TB             | 2         | 1.12%   |
| Toshiba MQ01ABD050 500GB           | 2         | 1.12%   |
| Toshiba MK2552GSX 250GB            | 2         | 1.12%   |
| SPCC Solid State Disk 512GB        | 2         | 1.12%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 1.12%   |
| Seagate Expansion Desk 5TB         | 2         | 1.12%   |
| Samsung SSD 860 EVO 1TB            | 2         | 1.12%   |
| Samsung SSD 850 EVO 500GB          | 2         | 1.12%   |
| PNY CS900 120GB SSD                | 2         | 1.12%   |
| Patriot Burst 120GB SSD            | 2         | 1.12%   |
| JMicron Tech 250GB                 | 2         | 1.12%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.56%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 1         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.56%   |
| WDC WDBNCE5000PNC 500GB SSD        | 1         | 0.56%   |
| WDC WDBNCE0010PNC 1TB SSD          | 1         | 0.56%   |
| WDC WD6402AAEX-00Y9A0 640GB        | 1         | 0.56%   |
| WDC WD6401AALS-00L3B2 640GB        | 1         | 0.56%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 0.56%   |
| WDC WD5000BPVT-60HXZT1 500GB       | 1         | 0.56%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 0.56%   |
| WDC WD5000AVVS-63M8B0 500GB        | 1         | 0.56%   |
| WDC WD5000AAKS-75A7B2 500GB        | 1         | 0.56%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1         | 0.56%   |
| WDC WD3200BEKT-00PVMT0 320GB       | 1         | 0.56%   |
| WDC WD3200AAKS-61L9A0 320GB        | 1         | 0.56%   |
| WDC WD30EZRZ-00WN9B0 3TB           | 1         | 0.56%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1         | 0.56%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 0.56%   |
| WDC WD20EADS-00R6B0 2TB            | 1         | 0.56%   |
| WDC WD2002FAEX-007BA0 2TB          | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 37     | 37.66%  |
| WDC                 | 21        | 26     | 27.27%  |
| Toshiba             | 12        | 12     | 15.58%  |
| Hitachi             | 6         | 6      | 7.79%   |
| Samsung Electronics | 3         | 3      | 3.9%    |
| HGST                | 2         | 2      | 2.6%    |
| Apple               | 2         | 3      | 2.6%    |
| Maxtor              | 1         | 1      | 1.3%    |
| JMicron Technology  | 1         | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 11        | 11     | 17.74%  |
| Samsung Electronics | 11        | 12     | 17.74%  |
| WDC                 | 7         | 7      | 11.29%  |
| Crucial             | 6         | 7      | 9.68%   |
| Kingston            | 4         | 4      | 6.45%   |
| SPCC                | 3         | 4      | 4.84%   |
| PNY                 | 3         | 3      | 4.84%   |
| Transcend           | 2         | 2      | 3.23%   |
| Patriot             | 2         | 2      | 3.23%   |
| A-DATA Technology   | 2         | 2      | 3.23%   |
| SATAFIRM            | 1         | 1      | 1.61%   |
| OCZ                 | 1         | 1      | 1.61%   |
| Micron_1            | 1         | 1      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| Leven               | 1         | 1      | 1.61%   |
| JMicron Technology  | 1         | 1      | 1.61%   |
| HEORIADY            | 1         | 1      | 1.61%   |
| Dogfish             | 1         | 1      | 1.61%   |
| Apacer              | 1         | 2      | 1.61%   |
| AMD                 | 1         | 1      | 1.61%   |
| ALERTSEAL           | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 68        | 91     | 45.64%  |
| SSD     | 55        | 66     | 36.91%  |
| NVMe    | 13        | 16     | 8.72%   |
| MMC     | 8         | 13     | 5.37%   |
| Unknown | 5         | 5      | 3.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 108       | 151    | 77.7%   |
| NVMe | 13        | 16     | 9.35%   |
| SAS  | 10        | 11     | 7.19%   |
| MMC  | 8         | 13     | 5.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 76        | 90     | 58.46%  |
| 0.51-1.0   | 39        | 50     | 30%     |
| 1.01-2.0   | 8         | 10     | 6.15%   |
| 4.01-10.0  | 3         | 3      | 2.31%   |
| 3.01-4.0   | 2         | 2      | 1.54%   |
| 2.01-3.0   | 2         | 2      | 1.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 33        | 27.5%   |
| 251-500        | 30        | 25%     |
| 501-1000       | 23        | 19.17%  |
| 21-50          | 13        | 10.83%  |
| 51-100         | 8         | 6.67%   |
| 1001-2000      | 4         | 3.33%   |
| 1-20           | 4         | 3.33%   |
| More than 3000 | 3         | 2.5%    |
| 2001-3000      | 1         | 0.83%   |
| Unknown        | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 58        | 47.15%  |
| 1-20      | 33        | 26.83%  |
| 51-100    | 14        | 11.38%  |
| 101-250   | 10        | 8.13%   |
| 251-500   | 5         | 4.07%   |
| 2001-3000 | 2         | 1.63%   |
| Unknown   | 1         | 0.81%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 116       | 187    | 97.48%  |
| Works    | 3         | 4      | 2.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 85        | 62.04%  |
| AMD                           | 23        | 16.79%  |
| Samsung Electronics           | 6         | 4.38%   |
| Nvidia                        | 4         | 2.92%   |
| JMicron Technology            | 4         | 2.92%   |
| ASMedia Technology            | 3         | 2.19%   |
| SK hynix                      | 2         | 1.46%   |
| SanDisk                       | 2         | 1.46%   |
| VIA Technologies              | 1         | 0.73%   |
| Toshiba America Info Systems  | 1         | 0.73%   |
| Silicon Image                 | 1         | 0.73%   |
| Promise Technology            | 1         | 0.73%   |
| Phison Electronics            | 1         | 0.73%   |
| Marvell Technology Group      | 1         | 0.73%   |
| Lenovo                        | 1         | 0.73%   |
| Integrated Technology Express | 1         | 0.73%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 6.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 6.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 4.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 3.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 3.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 3.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 2.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 2.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 2.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 1.82%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 1.82%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 1.21%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 1.21%   |
| JMicron JMB368 IDE controller                                                           | 2         | 1.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.21%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.21%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.61%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.61%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 0.61%   |
| SK hynix BC511                                                                          | 1         | 0.61%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 88        | 62.41%  |
| IDE  | 27        | 19.15%  |
| RAID | 13        | 9.22%   |
| NVMe | 13        | 9.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 93        | 78.81%  |
| AMD    | 25        | 21.19%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 3         | 2.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 3         | 2.54%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 2         | 1.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 2         | 1.69%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 2         | 1.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 2         | 1.69%   |
| Intel Core i3 CPU M 350 @ 2.27GHz            | 2         | 1.69%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 2         | 1.69%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 2         | 1.69%   |
| AMD FX-8350 Eight-Core Processor             | 2         | 1.69%   |
| AMD A6-9220 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.69%   |
| Intel Xeon Platinum 8171M CPU @ 2.60GHz      | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 1         | 0.85%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 0.85%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz       | 1         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz             | 1         | 0.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz            | 1         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz           | 1         | 0.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1         | 0.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz             | 1         | 0.85%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.85%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.85%   |
| Intel Core i7-2820QM CPU @ 2.30GHz           | 1         | 0.85%   |
| Intel Core i7-2630QM CPU @ 2.00GHz           | 1         | 0.85%   |
| Intel Core i7-2620M CPU @ 2.70GHz            | 1         | 0.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 0.85%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 1         | 0.85%   |
| Intel Core i7 CPU 920 @ 2.67GHz              | 1         | 0.85%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1         | 0.85%   |
| Intel Core i5-9400 CPU @ 2.90GHz             | 1         | 0.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 1         | 0.85%   |
| Intel Core i5-7400 CPU @ 3.00GHz             | 1         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i5-6500T CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 26        | 22.03%  |
| Intel Core i7           | 19        | 16.1%   |
| Intel Core i3           | 13        | 11.02%  |
| Intel Core 2 Duo        | 11        | 9.32%   |
| Intel Celeron           | 7         | 5.93%   |
| Intel Atom              | 5         | 4.24%   |
| AMD FX                  | 5         | 4.24%   |
| Intel Core 2 Quad       | 3         | 2.54%   |
| AMD Ryzen 7             | 3         | 2.54%   |
| AMD Ryzen 5             | 3         | 2.54%   |
| AMD A6                  | 3         | 2.54%   |
| Intel Pentium Dual-Core | 2         | 1.69%   |
| Intel Pentium Dual      | 2         | 1.69%   |
| Intel Core 2            | 2         | 1.69%   |
| AMD Phenom II X4        | 2         | 1.69%   |
| AMD E                   | 2         | 1.69%   |
| Intel Xeon Platinum     | 1         | 0.85%   |
| Intel Core 2 Extreme    | 1         | 0.85%   |
| Intel Celeron Dual-Core | 1         | 0.85%   |
| AMD Phenom II X2        | 1         | 0.85%   |
| AMD E2                  | 1         | 0.85%   |
| AMD Athlon II X2        | 1         | 0.85%   |
| AMD Athlon 64 X2        | 1         | 0.85%   |
| AMD Athlon              | 1         | 0.85%   |
| AMD A8                  | 1         | 0.85%   |
| AMD A10                 | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 66        | 55.93%  |
| 4      | 40        | 33.9%   |
| 6      | 5         | 4.24%   |
| 8      | 3         | 2.54%   |
| 3      | 2         | 1.69%   |
| 26     | 1         | 0.85%   |
| 1      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 118       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 61        | 51.69%  |
| 1      | 57        | 48.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 118       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 14        | 11.86%  |
| 0x206a7    | 13        | 11.02%  |
| 0x306a9    | 8         | 6.78%   |
| 0x306c3    | 7         | 5.93%   |
| 0x20652    | 6         | 5.08%   |
| 0x506e3    | 4         | 3.39%   |
| Unknown    | 4         | 3.39%   |
| 0x806e9    | 3         | 2.54%   |
| 0x6fd      | 3         | 2.54%   |
| 0x406c4    | 3         | 2.54%   |
| 0x306d4    | 3         | 2.54%   |
| 0x20655    | 3         | 2.54%   |
| 0x06000852 | 3         | 2.54%   |
| 0x010000c8 | 3         | 2.54%   |
| 0x906ea    | 2         | 1.69%   |
| 0x906e9    | 2         | 1.69%   |
| 0x806ea    | 2         | 1.69%   |
| 0x40651    | 2         | 1.69%   |
| 0x30678    | 2         | 1.69%   |
| 0x106e5    | 2         | 1.69%   |
| 0x10676    | 2         | 1.69%   |
| 0x08701021 | 2         | 1.69%   |
| 0x06006705 | 2         | 1.69%   |
| 0x06001119 | 2         | 1.69%   |
| 0x0600063e | 2         | 1.69%   |
| 0x05000119 | 2         | 1.69%   |
| 0x906ed    | 1         | 0.85%   |
| 0x706a8    | 1         | 0.85%   |
| 0x6fb      | 1         | 0.85%   |
| 0x6f6      | 1         | 0.85%   |
| 0x6f2      | 1         | 0.85%   |
| 0x506c9    | 1         | 0.85%   |
| 0x50654    | 1         | 0.85%   |
| 0x30673    | 1         | 0.85%   |
| 0x30661    | 1         | 0.85%   |
| 0x106a5    | 1         | 0.85%   |
| 0x0a50000c | 1         | 0.85%   |
| 0x08108109 | 1         | 0.85%   |
| 0x08101016 | 1         | 0.85%   |
| 0x08001138 | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 16        | 13.56%  |
| SandyBridge   | 13        | 11.02%  |
| Haswell       | 11        | 9.32%   |
| KabyLake      | 10        | 8.47%   |
| Westmere      | 9         | 7.63%   |
| IvyBridge     | 8         | 6.78%   |
| Silvermont    | 6         | 5.08%   |
| Core          | 6         | 5.08%   |
| Skylake       | 5         | 4.24%   |
| Piledriver    | 5         | 4.24%   |
| K10           | 4         | 3.39%   |
| Zen 2         | 3         | 2.54%   |
| Nehalem       | 3         | 2.54%   |
| Excavator     | 3         | 2.54%   |
| Broadwell     | 3         | 2.54%   |
| Zen           | 2         | 1.69%   |
| Bulldozer     | 2         | 1.69%   |
| Bobcat        | 2         | 1.69%   |
| Zen+          | 1         | 0.85%   |
| Zen 3         | 1         | 0.85%   |
| K8 Hammer     | 1         | 0.85%   |
| K10 Llano     | 1         | 0.85%   |
| Goldmont plus | 1         | 0.85%   |
| Goldmont      | 1         | 0.85%   |
| Bonnell       | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 64        | 46.72%  |
| Nvidia | 44        | 32.12%  |
| AMD    | 29        | 21.17%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 7.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 5%      |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 5%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 3.57%   |
| Intel HD Graphics 620                                                                    | 3         | 2.14%   |
| Intel HD Graphics 530                                                                    | 3         | 2.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.14%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.14%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.43%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 1.43%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 1.43%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 2         | 1.43%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 1.43%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.43%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.43%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.43%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 1.43%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.43%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 1.43%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.71%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.71%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.71%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.71%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.71%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.71%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.71%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1         | 0.71%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.71%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.71%   |
| Nvidia GM107GL [Quadro K620]                                                             | 1         | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.71%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 0.71%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 38.14%  |
| 1 x Nvidia     | 29        | 24.58%  |
| 1 x AMD        | 25        | 21.19%  |
| Intel + Nvidia | 14        | 11.86%  |
| Intel + AMD    | 3         | 2.54%   |
| 2 x Nvidia     | 1         | 0.85%   |
| 2 x AMD        | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 100       | 84.75%  |
| Proprietary | 9         | 7.63%   |
| Unknown     | 9         | 7.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 47.46%  |
| 0.01-0.5   | 18        | 15.25%  |
| 1.01-2.0   | 16        | 13.56%  |
| 0.51-1.0   | 16        | 13.56%  |
| 3.01-4.0   | 5         | 4.24%   |
| 2.01-3.0   | 4         | 3.39%   |
| 5.01-6.0   | 2         | 1.69%   |
| 7.01-8.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 20.35%  |
| LG Display              | 21        | 18.58%  |
| AU Optronics            | 12        | 10.62%  |
| Chimei Innolux          | 7         | 6.19%   |
| Ancor Communications    | 6         | 5.31%   |
| Goldstar                | 5         | 4.42%   |
| Dell                    | 4         | 3.54%   |
| AOC                     | 4         | 3.54%   |
| Acer                    | 4         | 3.54%   |
| Philips                 | 3         | 2.65%   |
| Hewlett-Packard         | 3         | 2.65%   |
| ViewSonic               | 2         | 1.77%   |
| LG Philips              | 2         | 1.77%   |
| BOE                     | 2         | 1.77%   |
| Apple                   | 2         | 1.77%   |
| ___                     | 1         | 0.88%   |
| Tech Concepts           | 1         | 0.88%   |
| PANDA                   | 1         | 0.88%   |
| Panasonic               | 1         | 0.88%   |
| Onkyo                   | 1         | 0.88%   |
| Microstep               | 1         | 0.88%   |
| Lenovo                  | 1         | 0.88%   |
| Insignia                | 1         | 0.88%   |
| Idek Iiyama             | 1         | 0.88%   |
| HKC                     | 1         | 0.88%   |
| Chi Mei Optoelectronics | 1         | 0.88%   |
| BenQ                    | 1         | 0.88%   |
| Unknown                 | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch    | 2         | 1.74%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch    | 2         | 1.74%   |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch    | 2         | 1.74%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 2         | 1.74%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch           | 2         | 1.74%   |
| ___ AAA ___01FF 1366x768 700x390mm 31.5-inch                            | 1         | 0.87%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch           | 1         | 0.87%   |
| ViewSonic VA2013wSERIES VSCF122 1600x900 443x249mm 20.0-inch            | 1         | 0.87%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                              | 1         | 0.87%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1         | 0.87%   |
| Samsung Electronics T24C310 SAM0AEA 1920x1080 531x299mm 24.0-inch       | 1         | 0.87%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch    | 1         | 0.87%   |
| Samsung Electronics SMT22A550 SAM07AE 1920x1080 477x268mm 21.5-inch     | 1         | 0.87%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 600x340mm 27.2-inch       | 1         | 0.87%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3645 1280x800 331x207mm 15.4-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch    | 1         | 0.87%   |
| Samsung Electronics LCD Monitor S24B300 3840x1080                       | 1         | 0.87%   |
| Philips PHL 241P4 PHL08D5 1920x1080 531x299mm 24.0-inch                 | 1         | 0.87%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch               | 1         | 0.87%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                      | 1         | 0.87%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                 | 1         | 0.87%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                      | 1         | 0.87%   |
| Onkyo AV Receiver ONK1050 1920x1080                                     | 1         | 0.87%   |
| Microstep LCD Monitor MSI MAG341CQ 3440x1440                            | 1         | 0.87%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch             | 1         | 0.87%   |
| LG Philips LCD Monitor LPL012B 1280x800 304x190mm 14.1-inch             | 1         | 0.87%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch             | 1         | 0.87%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch            | 1         | 0.87%   |
| LG Display LCD Monitor LGD0589 1920x1080 294x165mm 13.3-inch            | 1         | 0.87%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch             | 1         | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 36        | 33.03%  |
| 1920x1080 (FHD)    | 30        | 27.52%  |
| 1600x900 (HD+)     | 10        | 9.17%   |
| 3840x2160 (4K)     | 9         | 8.26%   |
| 1360x768           | 5         | 4.59%   |
| 1440x900 (WXGA+)   | 4         | 3.67%   |
| 1280x800 (WXGA)    | 4         | 3.67%   |
| 1680x1050 (WSXGA+) | 3         | 2.75%   |
| 1920x1200 (WUXGA)  | 2         | 1.83%   |
| 3840x1080          | 1         | 0.92%   |
| 3440x1440          | 1         | 0.92%   |
| 2560x1440 (QHD)    | 1         | 0.92%   |
| 1280x720 (HD)      | 1         | 0.92%   |
| 1280x1024 (SXGA)   | 1         | 0.92%   |
| Unknown            | 1         | 0.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 29.2%   |
| 17      | 12        | 10.62%  |
| 27      | 10        | 8.85%   |
| 14      | 8         | 7.08%   |
| 24      | 7         | 6.19%   |
| 21      | 7         | 6.19%   |
| Unknown | 7         | 6.19%   |
| 31      | 5         | 4.42%   |
| 18      | 5         | 4.42%   |
| 13      | 5         | 4.42%   |
| 19      | 4         | 3.54%   |
| 84      | 2         | 1.77%   |
| 23      | 2         | 1.77%   |
| 22      | 2         | 1.77%   |
| 11      | 2         | 1.77%   |
| 42      | 1         | 0.88%   |
| 20      | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 38.74%  |
| 401-500     | 18        | 16.22%  |
| 501-600     | 15        | 13.51%  |
| 351-400     | 13        | 11.71%  |
| 601-700     | 7         | 6.31%   |
| Unknown     | 7         | 6.31%   |
| 201-300     | 5         | 4.5%    |
| 1501-2000   | 2         | 1.8%    |
| 901-1000    | 1         | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 82        | 77.36%  |
| 16/10   | 17        | 16.04%  |
| Unknown | 5         | 4.72%   |
| 5/4     | 2         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 29.46%  |
| 201-250        | 12        | 10.71%  |
| 81-90          | 10        | 8.93%   |
| 301-350        | 10        | 8.93%   |
| 151-200        | 8         | 7.14%   |
| Unknown        | 7         | 6.25%   |
| 141-150        | 6         | 5.36%   |
| 131-140        | 6         | 5.36%   |
| 351-500        | 5         | 4.46%   |
| 121-130        | 5         | 4.46%   |
| 71-80          | 3         | 2.68%   |
| More than 1000 | 2         | 1.79%   |
| 51-60          | 2         | 1.79%   |
| 251-300        | 2         | 1.79%   |
| 501-1000       | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 40        | 36.36%  |
| 51-100  | 38        | 34.55%  |
| 121-160 | 17        | 15.45%  |
| Unknown | 7         | 6.36%   |
| 1-50    | 5         | 4.55%   |
| 161-240 | 3         | 2.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 98        | 83.05%  |
| 2     | 12        | 10.17%  |
| 0     | 7         | 5.93%   |
| 3     | 1         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 70        | 37.23%  |
| Intel                             | 43        | 22.87%  |
| Qualcomm Atheros                  | 21        | 11.17%  |
| Broadcom                          | 21        | 11.17%  |
| Broadcom Limited                  | 7         | 3.72%   |
| Ralink                            | 4         | 2.13%   |
| Nvidia                            | 4         | 2.13%   |
| TP-Link                           | 2         | 1.06%   |
| Samsung Electronics               | 2         | 1.06%   |
| Ralink Technology                 | 2         | 1.06%   |
| MediaTek                          | 2         | 1.06%   |
| Marvell Technology Group          | 2         | 1.06%   |
| Toshiba                           | 1         | 0.53%   |
| Qualcomm Atheros Communications   | 1         | 0.53%   |
| Motorola PCS                      | 1         | 0.53%   |
| Lenovo                            | 1         | 0.53%   |
| Huawei Technologies               | 1         | 0.53%   |
| Ericsson Business Mobile Networks | 1         | 0.53%   |
| D-Link System                     | 1         | 0.53%   |
| D-Link                            | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 23.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 4.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 2.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 4         | 1.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.4%    |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.4%    |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.4%    |
| Intel Centrino Advanced-N 6200                                    | 3         | 1.4%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.93%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.93%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.93%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.93%   |
| Intel Wireless 3160                                               | 2         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.93%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.93%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.93%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.93%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.47%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1         | 0.47%   |
| Toshiba F5521gw                                                   | 1         | 0.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 31.58%  |
| Realtek Semiconductor           | 17        | 17.89%  |
| Qualcomm Atheros                | 17        | 17.89%  |
| Broadcom                        | 16        | 16.84%  |
| Ralink                          | 4         | 4.21%   |
| TP-Link                         | 2         | 2.11%   |
| Ralink Technology               | 2         | 2.11%   |
| MediaTek                        | 2         | 2.11%   |
| Broadcom Limited                | 2         | 2.11%   |
| Qualcomm Atheros Communications | 1         | 1.05%   |
| D-Link System                   | 1         | 1.05%   |
| D-Link                          | 1         | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 5         | 5.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4         | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 4.17%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 4         | 4.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 3         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 3.13%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 3.13%   |
| Intel Wi-Fi 6 AX200                                                                           | 3         | 3.13%   |
| Intel Centrino Ultimate-N 6300                                                                | 3         | 3.13%   |
| Intel Centrino Advanced-N 6200                                                                | 3         | 3.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 2.08%   |
| Realtek 802.11n WLAN Adapter                                                                  | 2         | 2.08%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 2.08%   |
| Intel Wireless 3160                                                                           | 2         | 2.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 2.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2         | 2.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 2.08%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 1.04%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 1.04%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 1.04%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1         | 1.04%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1         | 1.04%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 1.04%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 1.04%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.04%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.04%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.04%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 63        | 54.78%  |
| Intel                    | 22        | 19.13%  |
| Broadcom                 | 9         | 7.83%   |
| Qualcomm Atheros         | 5         | 4.35%   |
| Broadcom Limited         | 5         | 4.35%   |
| Nvidia                   | 4         | 3.48%   |
| Samsung Electronics      | 2         | 1.74%   |
| Marvell Technology Group | 2         | 1.74%   |
| Motorola PCS             | 1         | 0.87%   |
| Lenovo                   | 1         | 0.87%   |
| Huawei Technologies      | 1         | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 43.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 8.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.31%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 2.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.72%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.72%   |
| Nvidia MCP61 Ethernet                                             | 2         | 1.72%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.72%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.72%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 2         | 1.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.86%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.86%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.86%   |
| Motorola PCS moto g(9) play                                       | 1         | 0.86%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.86%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.86%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.86%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.86%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.86%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.86%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.86%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.86%   |
| Intel 82566DC Gigabit Network Connection                          | 1         | 0.86%   |
| Huawei E353/E3131                                                 | 1         | 0.86%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.86%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.86%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.86%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.86%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1         | 0.86%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 110       | 54.46%  |
| WiFi     | 90        | 44.55%  |
| Modem    | 2         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 53.33%  |
| Ethernet | 56        | 46.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 60.17%  |
| 1     | 39        | 33.05%  |
| 0     | 6         | 5.08%   |
| 4     | 1         | 0.85%   |
| 3     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 74        | 62.71%  |
| Yes  | 44        | 37.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 26.98%  |
| Cambridge Silicon Radio         | 11        | 17.46%  |
| Broadcom                        | 7         | 11.11%  |
| Qualcomm Atheros Communications | 4         | 6.35%   |
| Dell                            | 4         | 6.35%   |
| Realtek Semiconductor           | 3         | 4.76%   |
| Hewlett-Packard                 | 3         | 4.76%   |
| Foxconn / Hon Hai               | 3         | 4.76%   |
| Apple                           | 3         | 4.76%   |
| Lite-On Technology              | 2         | 3.17%   |
| ASUSTek Computer                | 2         | 3.17%   |
| Toshiba                         | 1         | 1.59%   |
| Ralink                          | 1         | 1.59%   |
| IMC Networks                    | 1         | 1.59%   |
| Askey Computer                  | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 17.46%  |
| Intel Bluetooth wireless interface                  | 8         | 12.7%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.76%   |
| Intel AX200 Bluetooth                               | 3         | 4.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.17%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 3.17%   |
| Dell DW375 Bluetooth Module                         | 2         | 3.17%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 3.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 3.17%   |
| Apple Bluetooth USB Host Controller                 | 2         | 3.17%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.59%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.59%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.59%   |
| Lite-On Atheros Bluetooth                           | 1         | 1.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.59%   |
| Intel AX210 Bluetooth                               | 1         | 1.59%   |
| IMC Networks Bluetooth Device                       | 1         | 1.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.59%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.59%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.59%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.59%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.59%   |
| Broadcom Bluetooth Device                           | 1         | 1.59%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.59%   |
| Askey Bluetooth Device                              | 1         | 1.59%   |
| Apple Bluetooth Host Controller                     | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 48.28%  |
| Nvidia                | 35        | 20.11%  |
| AMD                   | 34        | 19.54%  |
| C-Media Electronics   | 5         | 2.87%   |
| GN Netcom             | 3         | 1.72%   |
| Creative Labs         | 2         | 1.15%   |
| Texas Instruments     | 1         | 0.57%   |
| Roland                | 1         | 0.57%   |
| ROCCAT                | 1         | 0.57%   |
| Realtek Semiconductor | 1         | 0.57%   |
| Microsoft             | 1         | 0.57%   |
| M-Audio               | 1         | 0.57%   |
| JMTek                 | 1         | 0.57%   |
| iSoft Silicon         | 1         | 0.57%   |
| Focusrite-Novation    | 1         | 0.57%   |
| DSEA A/S              | 1         | 0.57%   |
| AOKEO                 | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 7%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 6%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 5.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 4.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 4.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 3.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 3%      |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.5%    |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 2%      |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 2%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2%      |
| AMD FCH Azalia Controller                                                  | 4         | 2%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 2%      |
| Nvidia GM206 High Definition Audio Controller                              | 3         | 1.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.5%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3         | 1.5%    |
| AMD High Definition Audio Controller                                       | 3         | 1.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.5%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.5%    |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1%      |
| Nvidia GK110 High Definition Audio Controller                              | 2         | 1%      |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1%      |
| Intel 8 Series HD Audio Controller                                         | 2         | 1%      |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 1%      |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2         | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1%      |
| Texas Instruments PCM2903B Audio CODEC                                     | 1         | 0.5%    |
| Roland QUAD-CAPTURE                                                        | 1         | 0.5%    |
| ROCCAT Juke                                                                | 1         | 0.5%    |
| Realtek Semiconductor Realtek USB audio                                    | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 28.57%  |
| Kingston            | 2         | 28.57%  |
| Unknown             | 1         | 14.29%  |
| SK hynix            | 1         | 14.29%  |
| Corsair             | 1         | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 533MT/s           | 1         | 12.5%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s           | 1         | 12.5%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s         | 1         | 12.5%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 1         | 12.5%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 12.5%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s | 1         | 12.5%   |
| Kingston RAM 9905428-020.A00LF 4GB SODIMM DDR3 1067MT/s | 1         | 12.5%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 1         | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR3 | 3         | 50%     |
| DDR4 | 2         | 33.33%  |
| DDR2 | 1         | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 5         | 83.33%  |
| DIMM   | 1         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


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

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


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

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson ET-2600 Series | 1         | 50%     |
| Canon PIXMA MX920 Series   | 1         | 50%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 19.72%  |
| Microdia                               | 6         | 8.45%   |
| Silicon Motion                         | 5         | 7.04%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 7.04%   |
| Acer                                   | 4         | 5.63%   |
| Suyin                                  | 3         | 4.23%   |
| Quanta                                 | 3         | 4.23%   |
| Apple                                  | 3         | 4.23%   |
| Alcor Micro                            | 3         | 4.23%   |
| Sunplus Innovation Technology          | 2         | 2.82%   |
| Ricoh                                  | 2         | 2.82%   |
| Realtek Semiconductor                  | 2         | 2.82%   |
| Primax Electronics                     | 2         | 2.82%   |
| Microsoft                              | 2         | 2.82%   |
| Logitech                               | 2         | 2.82%   |
| Z-Star Microelectronics                | 1         | 1.41%   |
| YGTek                                  | 1         | 1.41%   |
| USB Camera                             | 1         | 1.41%   |
| Syntek                                 | 1         | 1.41%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 1.41%   |
| Samsung Electronics                    | 1         | 1.41%   |
| Ruision                                | 1         | 1.41%   |
| Jieli Technology                       | 1         | 1.41%   |
| IMC Networks                           | 1         | 1.41%   |
| Hewlett-Packard                        | 1         | 1.41%   |
| HD 2MP WEBCAM                          | 1         | 1.41%   |
| Creative Technology                    | 1         | 1.41%   |
| ALi                                    | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                     | 3         | 4.23%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                              | 2         | 2.82%   |
| Sunplus HD WebCam                                                     | 2         | 2.82%   |
| Realtek USB Camera                                                    | 2         | 2.82%   |
| Quanta HP Webcam                                                      | 2         | 2.82%   |
| Microdia Integrated_Webcam_HD                                         | 2         | 2.82%   |
| Chicony CNF9055 Toshiba Webcam                                        | 2         | 2.82%   |
| Chicony 2.0M UVC Webcam / CNF7129                                     | 2         | 2.82%   |
| Apple Built-in iSight                                                 | 2         | 2.82%   |
| Alcor Micro USB 2.0 Camera                                            | 2         | 2.82%   |
| Acer Lenovo EasyCamera                                                | 2         | 2.82%   |
| Z-Star WebCam SC-03FFL11739P                                          | 1         | 1.41%   |
| YGTek Webcam                                                          | 1         | 1.41%   |
| USB Camera USB Camera                                                 | 1         | 1.41%   |
| Syntek Lenovo EasyCamera                                              | 1         | 1.41%   |
| Suyin UVC HD Webcam                                                   | 1         | 1.41%   |
| Silicon Motion WebCam SCB-1100N                                       | 1         | 1.41%   |
| Silicon Motion WebCam SCB-0385N                                       | 1         | 1.41%   |
| Silicon Motion WebCam SC-0311139N                                     | 1         | 1.41%   |
| Silicon Motion SM731 Camera                                           | 1         | 1.41%   |
| Silicon Motion 300k Pixel Camera                                      | 1         | 1.41%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960                        | 1         | 1.41%   |
| Samsung Galaxy A5 (MTP)                                               | 1         | 1.41%   |
| Ruision UVC Camera                                                    | 1         | 1.41%   |
| Ricoh Laptop_Integrated_Webcam_3M                                     | 1         | 1.41%   |
| Ricoh Integrated Webcam                                               | 1         | 1.41%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                  | 1         | 1.41%   |
| Primax HP Webcam-101                                                  | 1         | 1.41%   |
| Primax HP HD Webcam [Fixed]                                           | 1         | 1.41%   |
| Microsoft LifeCam VX-5000                                             | 1         | 1.41%   |
| Microsoft LifeCam VX-500 [1357]                                       | 1         | 1.41%   |
| Microdia Lenovo EasyCamera                                            | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 1.41%   |
| Microdia Integrated Webcam                                            | 1         | 1.41%   |
| Microdia Dell Integrated HD Webcam                                    | 1         | 1.41%   |
| Logitech Webcam C600                                                  | 1         | 1.41%   |
| Logitech C922 Pro Stream Webcam                                       | 1         | 1.41%   |
| Jieli USB PHY 2.0                                                     | 1         | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 1.41%   |
| HP Webcam 3110                                                        | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 66.67%  |
| AuthenTec        | 2         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 4         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 84        | 71.19%  |
| 1     | 28        | 23.73%  |
| 2     | 6         | 5.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 13        | 35.14%  |
| Net/wireless          | 6         | 16.22%  |
| Fingerprint reader    | 6         | 16.22%  |
| Chipcard              | 4         | 10.81%  |
| Storage               | 3         | 8.11%   |
| Multimedia controller | 3         | 8.11%   |
| Unassigned class      | 1         | 2.7%    |
| Bluetooth             | 1         | 2.7%    |


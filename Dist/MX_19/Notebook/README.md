MX 19 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 19.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 111

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7480               | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
| Lenovo        | ThinkPad T420 4236TL7       | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | [f8f2a6263a](https://linux-hardware.org/?probe=f8f2a6263a) | Sep 04, 2022 |
| Acer          | Extensa 5630                | [9ea053d8e8](https://linux-hardware.org/?probe=9ea053d8e8) | Aug 12, 2022 |
| Acer          | Extensa 5630                | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| HP            | ProBook 6460b               | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Toshiba       | Satellite L850-CJK          | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| Lenovo        | Unknown                     | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Google        | Akemi                       | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| Dell          | Latitude E7450              | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Dell          | Latitude 3190               | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Sony          | SVT13115FBS                 | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| GTZS          | Unknown                     | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Pixus         | Rise                        | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| Acer          | Aspire E5-574G              | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Medion        | P6669 MD60147               | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Dell          | Vostro 3460                 | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Acer          | Extensa 5620                | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Intel         | ChiefRiver                  | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| ASUSTek       | 1025C                       | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| Dell          | Latitude E5470              | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | 15                          | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| Dell          | Latitude E5520              | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| Lenovo        | ThinkPad X220 4291WMQ       | [165b895e27](https://linux-hardware.org/?probe=165b895e27) | Dec 01, 2020 |
| Toshiba       | Satellite A300              | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| Acer          | Aspire SW5-015              | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| Lenovo        | V145-15AST 81MT             | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| HP            | ZBook 15 G4                 | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire 7520                 | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| HP            | Pavilion dv7                | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| Sony          | VPCF23P1E                   | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Samsung       | R780/R778                   | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Clevo         | P150HMx                     | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| Dell          | Latitude E7440              | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| Dell          | Inspiron 13-5378            | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| Dell          | Latitude 3190               | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Acer          | Aspire 8943G                | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T11... | [9c888bfdde](https://linux-hardware.org/?probe=9c888bfdde) | Feb 11, 2020 |
| Lenovo        | ThinkPad X201 3680MY9       | [26a7c0e493](https://linux-hardware.org/?probe=26a7c0e493) | Feb 09, 2020 |
| Google        | Gnawty                      | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | [8865e9546b](https://linux-hardware.org/?probe=8865e9546b) | Feb 03, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | [f4779c95ce](https://linux-hardware.org/?probe=f4779c95ce) | Feb 03, 2020 |
| Acer          | Swift SF314-54G             | [48912b8dc6](https://linux-hardware.org/?probe=48912b8dc6) | Jan 19, 2020 |
| ASUSTek       | TUF Gaming FX505GT_TUF50... | [0abd5b1d73](https://linux-hardware.org/?probe=0abd5b1d73) | Jan 18, 2020 |
| Toshiba       | Satellite P875              | [b267e93d40](https://linux-hardware.org/?probe=b267e93d40) | Jan 15, 2020 |
| Toshiba       | Satellite P875              | [7e579fcba2](https://linux-hardware.org/?probe=7e579fcba2) | Jan 15, 2020 |
| MSI           | GP63 Leopard 8RD            | [0a8865c437](https://linux-hardware.org/?probe=0a8865c437) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| HP            | Pavilion g6                 | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| HP            | Laptop 14-ck0xxx            | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| MSI           | MS-N033                     | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| ASUSTek       | X101CH                      | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| MSI           | GP63 Leopard 8RD            | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| HP            | Pavilion g6                 | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 24        | 25.53%  |
| 5.10.0-5mx-amd64           | 6         | 6.38%   |
| 4.19.0-13-amd64            | 6         | 6.38%   |
| 5.8.0-3-amd64              | 5         | 5.32%   |
| 4.19.0-14-amd64            | 5         | 5.32%   |
| 5.6.0-2-amd64              | 4         | 4.26%   |
| 4.19.0-16-amd64            | 3         | 3.19%   |
| 5.6.10-antix.1-amd64-smp   | 2         | 2.13%   |
| 5.10.0-8mx-amd64           | 2         | 2.13%   |
| 4.19.0-9-amd64             | 2         | 2.13%   |
| 4.19.0-8-amd64             | 2         | 2.13%   |
| 4.19.0-17-amd64            | 2         | 2.13%   |
| 4.19.0-12-amd64            | 2         | 2.13%   |
| 5.9.1-rt20avl1             | 1         | 1.06%   |
| 5.8.16-antix.1-amd64-smp   | 1         | 1.06%   |
| 5.7.0-19.1-liquorix-amd64  | 1         | 1.06%   |
| 5.4.0-antix.1-amd64-smp    | 1         | 1.06%   |
| 5.4.0-3-amd64              | 1         | 1.06%   |
| 5.4.0-13.3-liquorix-amd64  | 1         | 1.06%   |
| 5.4.0-11.2-liquorix-amd64  | 1         | 1.06%   |
| 5.4.0-10.2-liquorix-amd64  | 1         | 1.06%   |
| 5.3.10-antix.1-amd64-smp   | 1         | 1.06%   |
| 5.3.0-2-amd64              | 1         | 1.06%   |
| 5.3.0-10.1-liquorix-amd64  | 1         | 1.06%   |
| 5.2.21-antix.2-amd64-smp   | 1         | 1.06%   |
| 5.2.21-antix.2-686-smp-pae | 1         | 1.06%   |
| 5.2.0-21.2-liquorix-amd64  | 1         | 1.06%   |
| 5.15.0-1mx-amd64           | 1         | 1.06%   |
| 5.13.0-12.3-liquorix-amd64 | 1         | 1.06%   |
| 5.11.0-21.1-liquorix-amd64 | 1         | 1.06%   |
| 5.10.1-gnu                 | 1         | 1.06%   |
| 5.10.0-9mx-amd64           | 1         | 1.06%   |
| 4.9.246-0409246-lowlatency | 1         | 1.06%   |
| 4.9.193-antix.1-amd64-smp  | 1         | 1.06%   |
| 4.19.174                   | 1         | 1.06%   |
| 4.19.0-6-686-pae           | 1         | 1.06%   |
| 4.19.0-20-amd64            | 1         | 1.06%   |
| 4.19.0-18-amd64            | 1         | 1.06%   |
| 4.19.0-16-686-pae          | 1         | 1.06%   |
| 4.19.0-14-686-pae          | 1         | 1.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.0   | 51        | 55.43%  |
| 5.10.0   | 9         | 9.78%   |
| 5.8.0    | 5         | 5.43%   |
| 5.4.0    | 5         | 5.43%   |
| 5.6.0    | 4         | 4.35%   |
| 5.6.10   | 2         | 2.17%   |
| 5.3.0    | 2         | 2.17%   |
| 5.2.21   | 2         | 2.17%   |
| 5.9.1    | 1         | 1.09%   |
| 5.8.16   | 1         | 1.09%   |
| 5.7.0    | 1         | 1.09%   |
| 5.3.10   | 1         | 1.09%   |
| 5.2.0    | 1         | 1.09%   |
| 5.15.0   | 1         | 1.09%   |
| 5.13.0   | 1         | 1.09%   |
| 5.11.0   | 1         | 1.09%   |
| 5.10.1   | 1         | 1.09%   |
| 4.9.246  | 1         | 1.09%   |
| 4.9.193  | 1         | 1.09%   |
| 4.19.174 | 1         | 1.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 52        | 56.52%  |
| 5.10    | 10        | 10.87%  |
| 5.8     | 6         | 6.52%   |
| 5.6     | 6         | 6.52%   |
| 5.4     | 5         | 5.43%   |
| 5.3     | 3         | 3.26%   |
| 5.2     | 3         | 3.26%   |
| 4.9     | 2         | 2.17%   |
| 5.9     | 1         | 1.09%   |
| 5.7     | 1         | 1.09%   |
| 5.15    | 1         | 1.09%   |
| 5.13    | 1         | 1.09%   |
| 5.11    | 1         | 1.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 82        | 94.25%  |
| i686   | 5         | 5.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 63        | 72.41%  |
| KDE5            | 9         | 10.34%  |
| Unknown         | 4         | 4.6%    |
| MATE            | 2         | 2.3%    |
| Budgie          | 2         | 2.3%    |
| X-Cinnamon      | 1         | 1.15%   |
| LXQt            | 1         | 1.15%   |
| LXDE            | 1         | 1.15%   |
| i3              | 1         | 1.15%   |
| GNOME Flashback | 1         | 1.15%   |
| fluxbox         | 1         | 1.15%   |
| Cinnamon        | 1         | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 87        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 71        | 80.68%  |
| SDDM    | 8         | 9.09%   |
| SLiM    | 5         | 5.68%   |
| TDM     | 4         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 30        | 32.97%  |
| Unknown | 18        | 19.78%  |
| en_GB   | 7         | 7.69%   |
| de_DE   | 7         | 7.69%   |
| sk_SK   | 5         | 5.49%   |
| ru_RU   | 5         | 5.49%   |
| pt_BR   | 3         | 3.3%    |
| it_IT   | 3         | 3.3%    |
| pl_PL   | 2         | 2.2%    |
| fr_FR   | 2         | 2.2%    |
| zh_CN   | 1         | 1.1%    |
| uk_UA   | 1         | 1.1%    |
| tr_TR   | 1         | 1.1%    |
| nl_NL   | 1         | 1.1%    |
| fr_BE   | 1         | 1.1%    |
| es_MX   | 1         | 1.1%    |
| en_IE   | 1         | 1.1%    |
| en_AU   | 1         | 1.1%    |
| cs_CZ   | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 53        | 60.92%  |
| EFI  | 34        | 39.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 78        | 89.66%  |
| Overlay | 7         | 8.05%   |
| F2fs    | 1         | 1.15%   |
| Btrfs   | 1         | 1.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 44        | 50.57%  |
| MBR     | 41        | 47.13%  |
| Unknown | 2         | 2.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 85.23%  |
| Yes       | 13        | 14.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 57.47%  |
| Yes       | 37        | 42.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 19.54%  |
| Hewlett-Packard     | 16        | 18.39%  |
| Dell                | 13        | 14.94%  |
| Acer                | 11        | 12.64%  |
| ASUSTek Computer    | 9         | 10.34%  |
| Toshiba             | 5         | 5.75%   |
| Sony                | 2         | 2.3%    |
| Samsung Electronics | 2         | 2.3%    |
| MSI                 | 2         | 2.3%    |
| Medion              | 2         | 2.3%    |
| Google              | 2         | 2.3%    |
| Fujitsu Siemens     | 2         | 2.3%    |
| Pixus               | 1         | 1.15%   |
| Intel               | 1         | 1.15%   |
| eMachines           | 1         | 1.15%   |
| Clevo               | 1         | 1.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite P875                   | 1         | 1.15%   |
| Toshiba Satellite L850-CJK               | 1         | 1.15%   |
| Toshiba Satellite C50-A-12K              | 1         | 1.15%   |
| Toshiba Satellite A300                   | 1         | 1.15%   |
| Toshiba PORTEGE R705                     | 1         | 1.15%   |
| Sony VPCF23P1E                           | 1         | 1.15%   |
| Sony SVT13115FBS                         | 1         | 1.15%   |
| Samsung R780/R778                        | 1         | 1.15%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 1.15%   |
| Pixus Rise                               | 1         | 1.15%   |
| MSI MS-N033                              | 1         | 1.15%   |
| MSI GP63 Leopard 8RD                     | 1         | 1.15%   |
| Medion P6669 MD60147                     | 1         | 1.15%   |
| Medion E6234                             | 1         | 1.15%   |
| Lenovo V145-15AST 81MT                   | 1         | 1.15%   |
| Lenovo ThinkPad X301 2776LBU             | 1         | 1.15%   |
| Lenovo ThinkPad X270 W10DG 20K5S0YT00    | 1         | 1.15%   |
| Lenovo ThinkPad X250 20CLS4YA00          | 1         | 1.15%   |
| Lenovo ThinkPad X220 4291WMQ             | 1         | 1.15%   |
| Lenovo ThinkPad X201 3680MY9             | 1         | 1.15%   |
| Lenovo ThinkPad X1C 5th W10DG 20K4S0EC00 | 1         | 1.15%   |
| Lenovo ThinkPad W510 4875W17             | 1         | 1.15%   |
| Lenovo ThinkPad T440p 20AWS2T11D         | 1         | 1.15%   |
| Lenovo ThinkPad T440p 20AWA1NAUK         | 1         | 1.15%   |
| Lenovo ThinkPad T420 4236TL7             | 1         | 1.15%   |
| Lenovo ThinkPad T420 4236MBU             | 1         | 1.15%   |
| Lenovo ThinkPad T410 2537G99             | 1         | 1.15%   |
| Lenovo ThinkPad L412 0585W28             | 1         | 1.15%   |
| Lenovo ThinkPad E490 20N9S26G00          | 1         | 1.15%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.15%   |
| Intel ChiefRiver                         | 1         | 1.15%   |
| HP ZBook 15 G4                           | 1         | 1.15%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.15%   |
| HP ProBook 650 G1                        | 1         | 1.15%   |
| HP ProBook 6460b                         | 1         | 1.15%   |
| HP ProBook 4440s                         | 1         | 1.15%   |
| HP Presario CQ57                         | 1         | 1.15%   |
| HP Pavilion Laptop 15-cw0xxx             | 1         | 1.15%   |
| HP Pavilion Laptop 14-ce3xxx             | 1         | 1.15%   |
| HP Pavilion g6                           | 1         | 1.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 14        | 16.09%  |
| Dell Latitude           | 7         | 8.05%   |
| Acer Aspire             | 6         | 6.9%    |
| Toshiba Satellite       | 4         | 4.6%    |
| HP Pavilion             | 4         | 4.6%    |
| HP ProBook              | 3         | 3.45%   |
| Dell Inspiron           | 3         | 3.45%   |
| HP EliteBook            | 2         | 2.3%    |
| Dell Vostro             | 2         | 2.3%    |
| ASUS TUF                | 2         | 2.3%    |
| Acer Extensa            | 2         | 2.3%    |
| Toshiba PORTEGE         | 1         | 1.15%   |
| Sony VPCF23P1E          | 1         | 1.15%   |
| Sony SVT13115FBS        | 1         | 1.15%   |
| Samsung R780            | 1         | 1.15%   |
| Samsung 305E4A          | 1         | 1.15%   |
| Pixus Rise              | 1         | 1.15%   |
| MSI MS-N033             | 1         | 1.15%   |
| MSI GP63                | 1         | 1.15%   |
| Medion P6669            | 1         | 1.15%   |
| Medion E6234            | 1         | 1.15%   |
| Lenovo V145-15AST       | 1         | 1.15%   |
| Lenovo IdeaPad          | 1         | 1.15%   |
| Intel ChiefRiver        | 1         | 1.15%   |
| HP ZBook                | 1         | 1.15%   |
| HP Stream               | 1         | 1.15%   |
| HP Presario             | 1         | 1.15%   |
| HP Notebook             | 1         | 1.15%   |
| HP Mini                 | 1         | 1.15%   |
| HP Laptop               | 1         | 1.15%   |
| HP 15                   | 1         | 1.15%   |
| Google Gnawty           | 1         | 1.15%   |
| Google Akemi            | 1         | 1.15%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.15%   |
| Fujitsu Siemens AMILO   | 1         | 1.15%   |
| eMachines E727          | 1         | 1.15%   |
| Dell 0UW744??????       | 1         | 1.15%   |
| Clevo P150HMx           | 1         | 1.15%   |
| ASUS ZenBook            | 1         | 1.15%   |
| ASUS X540UP             | 1         | 1.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 12        | 13.79%  |
| 2010 | 11        | 12.64%  |
| 2012 | 10        | 11.49%  |
| 2018 | 8         | 9.2%    |
| 2016 | 6         | 6.9%    |
| 2013 | 6         | 6.9%    |
| 2019 | 5         | 5.75%   |
| 2015 | 4         | 4.6%    |
| 2014 | 4         | 4.6%    |
| 2008 | 4         | 4.6%    |
| 2007 | 4         | 4.6%    |
| 2021 | 3         | 3.45%   |
| 2020 | 3         | 3.45%   |
| 2017 | 3         | 3.45%   |
| 2009 | 3         | 3.45%   |
| 2006 | 1         | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 87        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 87        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 84        | 96.55%  |
| Yes  | 3         | 3.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 22        | 25%     |
| 8.01-16.0  | 20        | 22.73%  |
| 3.01-4.0   | 19        | 21.59%  |
| 16.01-24.0 | 10        | 11.36%  |
| 1.01-2.0   | 10        | 11.36%  |
| 32.01-64.0 | 3         | 3.41%   |
| 2.01-3.0   | 2         | 2.27%   |
| 0.51-1.0   | 2         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 38        | 41.3%   |
| 2.01-3.0  | 20        | 21.74%  |
| 0.51-1.0  | 14        | 15.22%  |
| 3.01-4.0  | 9         | 9.78%   |
| 4.01-8.0  | 8         | 8.7%    |
| 8.01-16.0 | 2         | 2.17%   |
| 0.01-0.5  | 1         | 1.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 75%     |
| 2      | 20        | 22.73%  |
| 3      | 1         | 1.14%   |
| 0      | 1         | 1.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 63.22%  |
| Yes       | 32        | 36.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 89.66%  |
| No        | 9         | 10.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 98.85%  |
| No        | 1         | 1.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 75%     |
| No        | 22        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 17        | 19.54%  |
| UK          | 7         | 8.05%   |
| Slovakia    | 6         | 6.9%    |
| Germany     | 6         | 6.9%    |
| Russia      | 4         | 4.6%    |
| Austria     | 4         | 4.6%    |
| Ukraine     | 3         | 3.45%   |
| Poland      | 3         | 3.45%   |
| Italy       | 3         | 3.45%   |
| India       | 3         | 3.45%   |
| France      | 3         | 3.45%   |
| Brazil      | 3         | 3.45%   |
| Thailand    | 2         | 2.3%    |
| Spain       | 2         | 2.3%    |
| Netherlands | 2         | 2.3%    |
| Mexico      | 2         | 2.3%    |
| China       | 2         | 2.3%    |
| Canada      | 2         | 2.3%    |
| Turkey      | 1         | 1.15%   |
| Sweden      | 1         | 1.15%   |
| Romania     | 1         | 1.15%   |
| Philippines | 1         | 1.15%   |
| Nigeria     | 1         | 1.15%   |
| Latvia      | 1         | 1.15%   |
| Indonesia   | 1         | 1.15%   |
| Greece      | 1         | 1.15%   |
| Czechia     | 1         | 1.15%   |
| Chile       | 1         | 1.15%   |
| Belgium     | 1         | 1.15%   |
| Australia   | 1         | 1.15%   |
| Algeria     | 1         | 1.15%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Bratislava                | 6         | 6.82%   |
| Vienna                    | 4         | 4.55%   |
| Berlin                    | 3         | 3.41%   |
| Warsaw                    | 2         | 2.27%   |
| Oxford                    | 2         | 2.27%   |
| Los Angeles               | 2         | 2.27%   |
| Dnipro                    | 2         | 2.27%   |
| Xalapa                    | 1         | 1.14%   |
| Wentzville                | 1         | 1.14%   |
| Valencia                  | 1         | 1.14%   |
| Tver                      | 1         | 1.14%   |
| Trzebinia                 | 1         | 1.14%   |
| Suzhou                    | 1         | 1.14%   |
| St Petersburg             | 1         | 1.14%   |
| Shenzhen                  | 1         | 1.14%   |
| Schiedam                  | 1         | 1.14%   |
| Santa Pola                | 1         | 1.14%   |
| San Giovanni in Persiceto | 1         | 1.14%   |
| Romulus                   | 1         | 1.14%   |
| Rome                      | 1         | 1.14%   |
| Rivne                     | 1         | 1.14%   |
| Riga                      | 1         | 1.14%   |
| Relizane                  | 1         | 1.14%   |
| Puerto Vallarta           | 1         | 1.14%   |
| Portsmouth                | 1         | 1.14%   |
| Philadelphia              | 1         | 1.14%   |
| Pátrai                   | 1         | 1.14%   |
| Pasig                     | 1         | 1.14%   |
| Olinda                    | 1         | 1.14%   |
| Novoplastunovskaya        | 1         | 1.14%   |
| New Delhi                 | 1         | 1.14%   |
| Netolice                  | 1         | 1.14%   |
| Nashville                 | 1         | 1.14%   |
| Mount Laurel              | 1         | 1.14%   |
| Moscow                    | 1         | 1.14%   |
| Monument                  | 1         | 1.14%   |
| Mitcham                   | 1         | 1.14%   |
| Melbourne                 | 1         | 1.14%   |
| Mebane                    | 1         | 1.14%   |
| Makassar                  | 1         | 1.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 10        | 11     | 9.26%   |
| WDC                 | 9         | 9      | 8.33%   |
| Seagate             | 9         | 9      | 8.33%   |
| Samsung Electronics | 9         | 12     | 8.33%   |
| Crucial             | 9         | 10     | 8.33%   |
| Kingston            | 8         | 8      | 7.41%   |
| Unknown             | 7         | 10     | 6.48%   |
| SanDisk             | 6         | 7      | 5.56%   |
| HGST                | 6         | 7      | 5.56%   |
| Intel               | 5         | 6      | 4.63%   |
| SK hynix            | 3         | 3      | 2.78%   |
| Micron Technology   | 3         | 4      | 2.78%   |
| Hitachi             | 3         | 3      | 2.78%   |
| PNY                 | 2         | 2      | 1.85%   |
| KingSpec            | 2         | 2      | 1.85%   |
| KingDian            | 2         | 2      | 1.85%   |
| A-DATA Technology   | 2         | 2      | 1.85%   |
| ZTC                 | 1         | 1      | 0.93%   |
| Transcend           | 1         | 1      | 0.93%   |
| Team                | 1         | 1      | 0.93%   |
| Smart               | 1         | 1      | 0.93%   |
| Phison Electronics  | 1         | 2      | 0.93%   |
| Phison              | 1         | 1      | 0.93%   |
| Patriot             | 1         | 1      | 0.93%   |
| LITEONIT            | 1         | 1      | 0.93%   |
| Lexar               | 1         | 1      | 0.93%   |
| KingFast            | 1         | 1      | 0.93%   |
| Indilinx            | 1         | 1      | 0.93%   |
| GOODRAM             | 1         | 1      | 0.93%   |
| Corsair             | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Kingston SV300S37A120G 120GB SSD    | 3         | 2.75%   |
| Toshiba MQ01ABF050 500GB            | 2         | 1.83%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 1.83%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 1.83%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2         | 1.83%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 1.83%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 1.83%   |
| Intel SSDSA2BW120G3H 120GB          | 2         | 1.83%   |
| Intel SSDPEKNW512G8 512GB           | 2         | 1.83%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 1.83%   |
| HGST HTS721010A9E630 1TB            | 2         | 1.83%   |
| HGST HTS541010A9E680 1TB            | 2         | 1.83%   |
| Crucial CT250MX500SSD1 250GB        | 2         | 1.83%   |
| ZTC SM201-256G SSD                  | 1         | 0.92%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.92%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.92%   |
| WDC WD5000BPVT-60HXZT3 500GB        | 1         | 0.92%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.92%   |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 0.92%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 0.92%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 0.92%   |
| WDC WD10SPZX-00Z10T0 1TB            | 1         | 0.92%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 0.92%   |
| Unknown SS08G  8GB                  | 1         | 0.92%   |
| Unknown SLD64G  64GB                | 1         | 0.92%   |
| Unknown SD16G  32GB                 | 1         | 0.92%   |
| Unknown SD04G  129GB                | 1         | 0.92%   |
| Unknown SD  32GB                    | 1         | 0.92%   |
| Unknown HAG2e  16GB                 | 1         | 0.92%   |
| Unknown CWBC3R  64GB                | 1         | 0.92%   |
| Unknown BJTD4R  32GB                | 1         | 0.92%   |
| Transcend TS256GMTS430S 256GB SSD   | 1         | 0.92%   |
| Toshiba THNSNC128GMLJ 128GB SSD     | 1         | 0.92%   |
| Toshiba MQ02ABD100H 1TB             | 1         | 0.92%   |
| Toshiba MQ01ABD075 752GB            | 1         | 0.92%   |
| Toshiba MK7575GSX 752GB             | 1         | 0.92%   |
| Toshiba MK2565GSX 250GB             | 1         | 0.92%   |
| Toshiba MK1032GSX 100GB             | 1         | 0.92%   |
| Toshiba KXG60ZNV1T02 1TB            | 1         | 0.92%   |
| Toshiba KBG40ZMT128G MEMORY 128GB   | 1         | 0.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 26.47%  |
| WDC                 | 7         | 7      | 20.59%  |
| Toshiba             | 7         | 8      | 20.59%  |
| HGST                | 6         | 7      | 17.65%  |
| Hitachi             | 3         | 3      | 8.82%   |
| Samsung Electronics | 2         | 3      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 10     | 16.07%  |
| Kingston            | 8         | 8      | 14.29%  |
| SanDisk             | 6         | 7      | 10.71%  |
| Samsung Electronics | 4         | 5      | 7.14%   |
| Micron Technology   | 3         | 4      | 5.36%   |
| Intel               | 3         | 4      | 5.36%   |
| WDC                 | 2         | 2      | 3.57%   |
| PNY                 | 2         | 2      | 3.57%   |
| KingSpec            | 2         | 2      | 3.57%   |
| KingDian            | 2         | 2      | 3.57%   |
| A-DATA Technology   | 2         | 2      | 3.57%   |
| ZTC                 | 1         | 1      | 1.79%   |
| Transcend           | 1         | 1      | 1.79%   |
| Toshiba             | 1         | 1      | 1.79%   |
| Team                | 1         | 1      | 1.79%   |
| Smart               | 1         | 1      | 1.79%   |
| SK hynix            | 1         | 1      | 1.79%   |
| Phison              | 1         | 1      | 1.79%   |
| Patriot             | 1         | 1      | 1.79%   |
| LITEONIT            | 1         | 1      | 1.79%   |
| KingFast            | 1         | 1      | 1.79%   |
| Indilinx            | 1         | 1      | 1.79%   |
| GOODRAM             | 1         | 1      | 1.79%   |
| Corsair             | 1         | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 51        | 61     | 50.5%   |
| HDD  | 33        | 37     | 32.67%  |
| NVMe | 9         | 12     | 8.91%   |
| MMC  | 8         | 11     | 7.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 98     | 80.9%   |
| NVMe | 9         | 12     | 10.11%  |
| MMC  | 8         | 11     | 8.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 72     | 71.6%   |
| 0.51-1.0   | 23        | 26     | 28.4%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 32        | 35.56%  |
| 51-100     | 17        | 18.89%  |
| 501-1000   | 13        | 14.44%  |
| 251-500    | 9         | 10%     |
| 21-50      | 7         | 7.78%   |
| 1-20       | 5         | 5.56%   |
| 1001-2000  | 4         | 4.44%   |
| Unknown    | 2         | 2.22%   |
| 2001-3000  | 1         | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 44        | 48.35%  |
| 101-250   | 11        | 12.09%  |
| 21-50     | 10        | 10.99%  |
| 51-100    | 10        | 10.99%  |
| 251-500   | 7         | 7.69%   |
| 501-1000  | 6         | 6.59%   |
| Unknown   | 2         | 2.2%    |
| 1001-2000 | 1         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-60HXZT3 500GB        | 1         | 1      | 6.25%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 6.25%   |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 1      | 6.25%   |
| Toshiba MK7575GSX 752GB             | 1         | 2      | 6.25%   |
| Toshiba MK2565GSX 250GB             | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 6.25%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 6.25%   |
| Samsung Electronics HS122JC 120GB   | 1         | 2      | 6.25%   |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 6.25%   |
| Indilinx IND-S325S120G 120GB SSD    | 1         | 1      | 6.25%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 6.25%   |
| Hitachi HTS543232A7A384 320GB       | 1         | 1      | 6.25%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 6.25%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 6.25%   |
| Crucial CT512M550SSD1 512GB         | 1         | 1      | 6.25%   |
| A-DATA Technology SU650 240GB SSD   | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 18.75%  |
| Toshiba             | 2         | 3      | 12.5%   |
| Hitachi             | 2         | 2      | 12.5%   |
| HGST                | 2         | 2      | 12.5%   |
| Seagate             | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 2      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| Indilinx            | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |
| A-DATA Technology   | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 27.27%  |
| Toshiba             | 2         | 3      | 18.18%  |
| Hitachi             | 2         | 2      | 18.18%  |
| HGST                | 2         | 2      | 18.18%  |
| Seagate             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 68.75%  |
| SSD  | 5         | 5      | 31.25%  |

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
| Works    | 68        | 92     | 73.91%  |
| Malfunc  | 15        | 18     | 16.3%   |
| Detected | 9         | 11     | 9.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 69        | 77.53%  |
| AMD                          | 10        | 11.24%  |
| Samsung Electronics          | 3         | 3.37%   |
| Nvidia                       | 2         | 2.25%   |
| Toshiba America Info Systems | 1         | 1.12%   |
| SK hynix                     | 1         | 1.12%   |
| Silicon Motion               | 1         | 1.12%   |
| Phison Electronics           | 1         | 1.12%   |
| KIOXIA                       | 1         | 1.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 9.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 9.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 8.42%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 8.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 7.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 6.32%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 4.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 3.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.11%   |
| Intel SSD 660P Series                                                            | 2         | 2.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 2.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.05%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.05%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.05%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 1.05%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.05%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.05%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.05%   |
| AMD SB600 IDE                                                                    | 1         | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 66        | 70.97%  |
| RAID | 10        | 10.75%  |
| NVMe | 9         | 9.68%   |
| IDE  | 8         | 8.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 86.21%  |
| AMD    | 12        | 13.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 4.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 4.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 2.3%    |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 2         | 2.3%    |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 2.3%    |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 2.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 2.3%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 2.3%    |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 2.3%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.15%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.15%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.15%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 1.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.15%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.15%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.15%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.15%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.15%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 1.15%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.15%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.15%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.15%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 1.15%   |
| Intel Core i7 CPU M 640 @ 2.80GHz           | 1         | 1.15%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.15%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.15%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.15%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.15%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.15%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.15%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.15%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.15%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.15%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.15%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 28.74%  |
| Intel Core i7           | 21        | 24.14%  |
| Intel Celeron           | 8         | 9.2%    |
| Intel Atom              | 6         | 6.9%    |
| Intel Core 2 Duo        | 5         | 5.75%   |
| Intel Core i3           | 4         | 4.6%    |
| AMD A6                  | 3         | 3.45%   |
| Intel Pentium           | 2         | 2.3%    |
| AMD Turion 64 X2 Mobile | 2         | 2.3%    |
| AMD Ryzen 7             | 2         | 2.3%    |
| Other                   | 1         | 1.15%   |
| Intel Pentium Silver    | 1         | 1.15%   |
| Intel Pentium Dual-Core | 1         | 1.15%   |
| Intel Core 2            | 1         | 1.15%   |
| AMD Ryzen 5             | 1         | 1.15%   |
| AMD E1                  | 1         | 1.15%   |
| AMD E                   | 1         | 1.15%   |
| AMD Athlon 64 X2        | 1         | 1.15%   |
| AMD A8                  | 1         | 1.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 67.82%  |
| 4      | 21        | 24.14%  |
| 1      | 3         | 3.45%   |
| 8      | 2         | 2.3%    |
| 6      | 2         | 2.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 87        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 58        | 66.67%  |
| 1      | 29        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 84        | 96.55%  |
| 32-bit         | 3         | 3.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 14.61%  |
| 0x306a9    | 8         | 8.99%   |
| 0x406e3    | 7         | 7.87%   |
| 0x206a7    | 7         | 7.87%   |
| 0x20655    | 5         | 5.62%   |
| 0x806ec    | 3         | 3.37%   |
| 0x306c3    | 3         | 3.37%   |
| 0x20652    | 3         | 3.37%   |
| 0x906ea    | 2         | 2.25%   |
| 0x806e9    | 2         | 2.25%   |
| 0x6fd      | 2         | 2.25%   |
| 0x406c4    | 2         | 2.25%   |
| 0x40651    | 2         | 2.25%   |
| 0x306d4    | 2         | 2.25%   |
| 0x30678    | 2         | 2.25%   |
| 0x30661    | 2         | 2.25%   |
| 0x106ca    | 2         | 2.25%   |
| 0x10676    | 2         | 2.25%   |
| 0x03000027 | 2         | 2.25%   |
| 0x906e9    | 1         | 1.12%   |
| 0x806ea    | 1         | 1.12%   |
| 0x806c1    | 1         | 1.12%   |
| 0x706e5    | 1         | 1.12%   |
| 0x706a1    | 1         | 1.12%   |
| 0x6f2      | 1         | 1.12%   |
| 0x506c9    | 1         | 1.12%   |
| 0x406c3    | 1         | 1.12%   |
| 0x106e5    | 1         | 1.12%   |
| 0x106c2    | 1         | 1.12%   |
| 0x1067a    | 1         | 1.12%   |
| 0x08608103 | 1         | 1.12%   |
| 0x08600104 | 1         | 1.12%   |
| 0x0810100b | 1         | 1.12%   |
| 0x07030105 | 1         | 1.12%   |
| 0x0700010f | 1         | 1.12%   |
| 0x06006705 | 1         | 1.12%   |
| 0x05000119 | 1         | 1.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 11        | 12.64%  |
| KabyLake      | 10        | 11.49%  |
| IvyBridge     | 9         | 10.34%  |
| Westmere      | 8         | 9.2%    |
| Skylake       | 7         | 8.05%   |
| Silvermont    | 6         | 6.9%    |
| Haswell       | 5         | 5.75%   |
| Bonnell       | 5         | 5.75%   |
| Penryn        | 4         | 4.6%    |
| K8 Hammer     | 3         | 3.45%   |
| Core          | 3         | 3.45%   |
| K10 Llano     | 2         | 2.3%    |
| Broadwell     | 2         | 2.3%    |
| Zen 2         | 1         | 1.15%   |
| Zen           | 1         | 1.15%   |
| TigerLake     | 1         | 1.15%   |
| Puma          | 1         | 1.15%   |
| Nehalem       | 1         | 1.15%   |
| Jaguar        | 1         | 1.15%   |
| IceLake       | 1         | 1.15%   |
| Goldmont plus | 1         | 1.15%   |
| Goldmont      | 1         | 1.15%   |
| Excavator     | 1         | 1.15%   |
| Bobcat        | 1         | 1.15%   |
| Unknown       | 1         | 1.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 64        | 63.37%  |
| AMD    | 19        | 18.81%  |
| Nvidia | 18        | 17.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 7.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 7.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 6.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.8%    |
| Intel HD Graphics 620                                                                    | 3         | 2.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 2.8%    |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 1.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.87%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.87%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.87%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.87%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.87%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 1.87%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.93%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.93%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.93%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.93%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.93%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.93%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.93%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.93%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 1         | 0.93%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 51        | 58.62%  |
| 1 x AMD        | 12        | 13.79%  |
| Intel + Nvidia | 10        | 11.49%  |
| 1 x Nvidia     | 7         | 8.05%   |
| 2 x AMD        | 3         | 3.45%   |
| Intel + AMD    | 3         | 3.45%   |
| AMD + Nvidia   | 1         | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 83        | 95.4%   |
| Proprietary | 2         | 2.3%    |
| Unknown     | 2         | 2.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 73.86%  |
| 0.01-0.5   | 11        | 12.5%   |
| 0.51-1.0   | 7         | 7.95%   |
| 1.01-2.0   | 5         | 5.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 23.66%  |
| LG Display              | 14        | 15.05%  |
| Chimei Innolux          | 14        | 15.05%  |
| Samsung Electronics     | 13        | 13.98%  |
| Lenovo                  | 5         | 5.38%   |
| BOE                     | 5         | 5.38%   |
| Chi Mei Optoelectronics | 3         | 3.23%   |
| LG Philips              | 2         | 2.15%   |
| InfoVision              | 2         | 2.15%   |
| HannStar                | 2         | 2.15%   |
| Dell                    | 2         | 2.15%   |
| Vizio                   | 1         | 1.08%   |
| PANDA                   | 1         | 1.08%   |
| InnoLux Display         | 1         | 1.08%   |
| Hewlett-Packard         | 1         | 1.08%   |
| Goldstar                | 1         | 1.08%   |
| CPT                     | 1         | 1.08%   |
| AOC                     | 1         | 1.08%   |
| Ancor Communications    | 1         | 1.08%   |
| Acer                    | 1         | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 2.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 2.15%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 2.15%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 2.15%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 2.15%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 2         | 2.15%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 2.15%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch         | 2         | 2.15%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                     | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch  | 1         | 1.08%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1         | 1.08%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 1.08%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 1.08%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.08%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD04FC 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch           | 1         | 1.08%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 1         | 1.08%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 1         | 1.08%   |
| Lenovo LCD Monitor LEN4074 1440x900 287x180mm 13.3-inch               | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 35.16%  |
| 1366x768 (WXGA)    | 32        | 35.16%  |
| 1600x900 (HD+)     | 9         | 9.89%   |
| 1280x800 (WXGA)    | 6         | 6.59%   |
| 1024x600           | 4         | 4.4%    |
| 2560x1440 (QHD)    | 2         | 2.2%    |
| 1440x900 (WXGA+)   | 2         | 2.2%    |
| 1280x1024 (SXGA)   | 2         | 2.2%    |
| 1920x1200 (WUXGA)  | 1         | 1.1%    |
| 1680x1050 (WSXGA+) | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 36        | 38.71%  |
| 14     | 14        | 15.05%  |
| 13     | 13        | 13.98%  |
| 17     | 5         | 5.38%   |
| 12     | 4         | 4.3%    |
| 10     | 4         | 4.3%    |
| 11     | 3         | 3.23%   |
| 23     | 2         | 2.15%   |
| 20     | 2         | 2.15%   |
| 19     | 2         | 2.15%   |
| 18     | 2         | 2.15%   |
| 37     | 1         | 1.08%   |
| 32     | 1         | 1.08%   |
| 27     | 1         | 1.08%   |
| 26     | 1         | 1.08%   |
| 24     | 1         | 1.08%   |
| 16     | 1         | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 59.14%  |
| 201-300     | 16        | 17.2%   |
| 351-400     | 11        | 11.83%  |
| 501-600     | 5         | 5.38%   |
| 401-500     | 4         | 4.3%    |
| 801-900     | 1         | 1.08%   |
| 701-800     | 1         | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 73        | 84.88%  |
| 16/10 | 10        | 11.63%  |
| 5/4   | 2         | 2.33%   |
| 3/2   | 1         | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 38.71%  |
| 81-90          | 22        | 23.66%  |
| 71-80          | 5         | 5.38%   |
| 61-70          | 4         | 4.3%    |
| 41-50          | 4         | 4.3%    |
| 151-200        | 4         | 4.3%    |
| 121-130        | 4         | 4.3%    |
| 51-60          | 3         | 3.23%   |
| 251-300        | 2         | 2.15%   |
| 201-250        | 2         | 2.15%   |
| 141-150        | 2         | 2.15%   |
| 351-500        | 1         | 1.08%   |
| 301-350        | 1         | 1.08%   |
| 131-140        | 1         | 1.08%   |
| 111-120        | 1         | 1.08%   |
| 501-1000       | 1         | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 36        | 40%     |
| 121-160 | 31        | 34.44%  |
| 51-100  | 20        | 22.22%  |
| 161-240 | 3         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 74        | 85.06%  |
| 2     | 13        | 14.94%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 51        | 36.43%  |
| Realtek Semiconductor    | 39        | 27.86%  |
| Qualcomm Atheros         | 26        | 18.57%  |
| Broadcom                 | 10        | 7.14%   |
| Ralink                   | 2         | 1.43%   |
| Nvidia                   | 2         | 1.43%   |
| Marvell Technology Group | 2         | 1.43%   |
| Huawei Technologies      | 2         | 1.43%   |
| Attansic Technology      | 2         | 1.43%   |
| Ralink Technology        | 1         | 0.71%   |
| MediaTek                 | 1         | 0.71%   |
| JMicron Technology       | 1         | 0.71%   |
| ASIX Electronics         | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 24        | 13.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 9         | 5.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 8         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 6         | 3.49%   |
| Intel Wireless 7260                                                                           | 5         | 2.91%   |
| Intel 82577LM Gigabit Network Connection                                                      | 5         | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 2.33%   |
| Intel Wireless 7265                                                                           | 4         | 2.33%   |
| Intel Centrino Advanced-N 6200                                                                | 4         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.74%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 1.74%   |
| Intel Wireless 8260                                                                           | 3         | 1.74%   |
| Intel Wireless 3165                                                                           | 3         | 1.74%   |
| Intel Ethernet Connection I217-LM                                                             | 3         | 1.74%   |
| Intel Centrino Wireless-N 2230                                                                | 3         | 1.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 1.16%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                        | 2         | 1.16%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2         | 1.16%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 2         | 1.16%   |
| Intel Ethernet Connection I219-V                                                              | 2         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                                                         | 2         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.16%   |
| Attansic AR8152 v2.0 Fast Ethernet                                                            | 2         | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 0.58%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.58%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 55.06%  |
| Qualcomm Atheros      | 20        | 22.47%  |
| Realtek Semiconductor | 11        | 12.36%  |
| Broadcom              | 6         | 6.74%   |
| Ralink                | 2         | 2.25%   |
| Ralink Technology     | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 8         | 8.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 6         | 6.67%   |
| Intel Wireless 7260                                                                           | 5         | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 4.44%   |
| Intel Wireless 7265                                                                           | 4         | 4.44%   |
| Intel Centrino Advanced-N 6200                                                                | 4         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 3.33%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 3.33%   |
| Intel Wireless 8260                                                                           | 3         | 3.33%   |
| Intel Wireless 3165                                                                           | 3         | 3.33%   |
| Intel Centrino Wireless-N 2230                                                                | 3         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 2.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 2         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 1.11%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.11%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.11%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.11%   |
| Intel Wireless-AC 9260                                                                        | 1         | 1.11%   |
| Intel WiFi Link 5100                                                                          | 1         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.11%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 1         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 41.98%  |
| Intel                    | 22        | 27.16%  |
| Qualcomm Atheros         | 10        | 12.35%  |
| Broadcom                 | 5         | 6.17%   |
| Nvidia                   | 2         | 2.47%   |
| Marvell Technology Group | 2         | 2.47%   |
| Attansic Technology      | 2         | 2.47%   |
| MediaTek                 | 1         | 1.23%   |
| JMicron Technology       | 1         | 1.23%   |
| Huawei Technologies      | 1         | 1.23%   |
| ASIX Electronics         | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 24        | 29.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 11.11%  |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 6.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 4.94%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 3.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 2.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 2.47%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.47%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 2.47%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 2.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.23%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.23%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 1.23%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.23%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 1.23%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 1.23%   |
| MediaTek TECNO CAMON 18P                                                       | 1         | 1.23%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.23%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.23%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.23%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.23%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.23%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.23%   |
| Huawei STK-L21                                                                 | 1         | 1.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 1.23%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 1.23%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 1.23%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 1.23%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 52.12%  |
| Ethernet | 78        | 47.27%  |
| Modem    | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 78.65%  |
| Ethernet | 19        | 21.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 75        | 86.21%  |
| 1     | 11        | 12.64%  |
| 0     | 1         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 81        | 92.05%  |
| Yes  | 7         | 7.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 42.03%  |
| Broadcom                        | 9         | 13.04%  |
| Realtek Semiconductor           | 7         | 10.14%  |
| Qualcomm Atheros Communications | 5         | 7.25%   |
| Cambridge Silicon Radio         | 4         | 5.8%    |
| Lite-On Technology              | 3         | 4.35%   |
| IMC Networks                    | 3         | 4.35%   |
| Hewlett-Packard                 | 3         | 4.35%   |
| Toshiba                         | 2         | 2.9%    |
| Dell                            | 2         | 2.9%    |
| Ralink                          | 1         | 1.45%   |
| Foxconn / Hon Hai               | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 24.64%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 5.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 5.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.35%   |
| Realtek Bluetooth Radio                             | 3         | 4.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.35%   |
| Intel AX201 Bluetooth                               | 3         | 4.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.9%    |
| Qualcomm Atheros Bluetooth                          | 2         | 2.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.9%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.9%    |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 1.45%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 1.45%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.45%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.45%   |
| Intel AX210 Bluetooth                               | 1         | 1.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.45%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.45%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.45%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.45%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.45%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 1.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 74        | 71.84%  |
| AMD                 | 16        | 15.53%  |
| Nvidia              | 11        | 10.68%  |
| GN Netcom           | 1         | 0.97%   |
| C-Media Electronics | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 9.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 9.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 7.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 7.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 5.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 3.39%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.39%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 2.54%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.69%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.69%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.69%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.69%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 1.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.85%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.85%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.85%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.85%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.85%   |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.85%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.85%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 24.3%   |
| SK hynix            | 24        | 22.43%  |
| Unknown             | 14        | 13.08%  |
| Micron Technology   | 13        | 12.15%  |
| Kingston            | 8         | 7.48%   |
| Elpida              | 3         | 2.8%    |
| A-DATA Technology   | 3         | 2.8%    |
| Unknown (ABCD)      | 2         | 1.87%   |
| Ramaxel Technology  | 2         | 1.87%   |
| Crucial             | 2         | 1.87%   |
| Unknown (F301)      | 1         | 0.93%   |
| TRS STAR            | 1         | 0.93%   |
| Teikon              | 1         | 0.93%   |
| Team                | 1         | 0.93%   |
| Smart               | 1         | 0.93%   |
| Patriot             | 1         | 0.93%   |
| High Bridge         | 1         | 0.93%   |
| Corsair             | 1         | 0.93%   |
| Apacer              | 1         | 0.93%   |
| Unknown             | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 2.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.56%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 2.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.71%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.71%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 1.71%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.71%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.71%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 2         | 1.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.71%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.71%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DRAM                               | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 1         | 0.85%   |
| Unknown RAM Module 1024MB Chip DDR 533MT/s                       | 1         | 0.85%   |
| Unknown (F301) RAM G2BT-4AFP00 16384MB SODIMM DDR4 2133MT/s      | 1         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.85%   |
| TRS STAR RAM Module 8GB SODIMM DDR3 1333MT/s                     | 1         | 0.85%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 0.85%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s         | 1         | 0.85%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2400MT/s                 | 1         | 0.85%   |
| SK hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.85%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 50        | 56.18%  |
| DDR4    | 21        | 23.6%   |
| DDR2    | 8         | 8.99%   |
| LPDDR4  | 3         | 3.37%   |
| SDRAM   | 2         | 2.25%   |
| DRAM    | 2         | 2.25%   |
| LPDDR3  | 1         | 1.12%   |
| DDR     | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 81        | 94.19%  |
| Row Of Chips | 2         | 2.33%   |
| DIMM         | 1         | 1.16%   |
| Chip         | 1         | 1.16%   |
| Unknown      | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 44        | 44.9%   |
| 8192  | 21        | 21.43%  |
| 2048  | 21        | 21.43%  |
| 16384 | 9         | 9.18%   |
| 1024  | 3         | 3.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 30.39%  |
| 2667    | 13        | 12.75%  |
| 1334    | 13        | 12.75%  |
| 2400    | 8         | 7.84%   |
| 1333    | 6         | 5.88%   |
| 667     | 5         | 4.9%    |
| Unknown | 5         | 4.9%    |
| 3200    | 3         | 2.94%   |
| 1067    | 3         | 2.94%   |
| 800     | 3         | 2.94%   |
| 4199    | 2         | 1.96%   |
| 3266    | 2         | 1.96%   |
| 2133    | 2         | 1.96%   |
| 1867    | 2         | 1.96%   |
| 8400    | 1         | 0.98%   |
| 4267    | 1         | 0.98%   |
| 666     | 1         | 0.98%   |
| 533     | 1         | 0.98%   |

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


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 24%     |
| Realtek Semiconductor                  | 9         | 12%     |
| Microdia                               | 6         | 8%      |
| Sunplus Innovation Technology          | 5         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 6.67%   |
| Acer                                   | 5         | 6.67%   |
| Suyin                                  | 4         | 5.33%   |
| Lite-On Technology                     | 3         | 4%      |
| Lenovo                                 | 3         | 4%      |
| IMC Networks                           | 3         | 4%      |
| Z-Star Microelectronics                | 2         | 2.67%   |
| Syntek                                 | 2         | 2.67%   |
| Quanta                                 | 2         | 2.67%   |
| Xiongmai                               | 1         | 1.33%   |
| WaveRider Communications               | 1         | 1.33%   |
| Silicon Motion                         | 1         | 1.33%   |
| Samsung Electronics                    | 1         | 1.33%   |
| Ricoh                                  | 1         | 1.33%   |
| Importek                               | 1         | 1.33%   |
| Cubeternet                             | 1         | 1.33%   |
| Alcor Micro                            | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                   | 5         | 6.67%   |
| Realtek Integrated_Webcam_HD                                | 4         | 5.33%   |
| Syntek EasyCamera                                           | 2         | 2.67%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 2.67%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 2.67%   |
| Microdia USB 2.0 Camera                                     | 2         | 2.67%   |
| Microdia Integrated Webcam                                  | 2         | 2.67%   |
| Lite-On Integrated Camera                                   | 2         | 2.67%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 2.67%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 2.67%   |
| Chicony USB 2.0 Camera                                      | 2         | 2.67%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 2.67%   |
| Chicony HP Truevision HD camera                             | 2         | 2.67%   |
| Chicony HD WebCam                                           | 2         | 2.67%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 1.33%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 1.33%   |
| Xiongmai web camera                                         | 1         | 1.33%   |
| WaveRider USB 2.0 Camera                                    | 1         | 1.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.33%   |
| Suyin 1.3M HD WebCam                                        | 1         | 1.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.33%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.33%   |
| Sunplus Integrated Webcam                                   | 1         | 1.33%   |
| Sunplus HD WebCam                                           | 1         | 1.33%   |
| Sunplus Asus Webcam                                         | 1         | 1.33%   |
| Silicon Motion Silicon Motion Camera                        | 1         | 1.33%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 1.33%   |
| Ricoh USB2.0 Camera                                         | 1         | 1.33%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 1.33%   |
| Realtek Integrated Webcam                                   | 1         | 1.33%   |
| Realtek HD Webcam - Realtek                                 | 1         | 1.33%   |
| Quanta USB2.0 HD UVC WebCam                                 | 1         | 1.33%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.33%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 1.33%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.33%   |
| Lite-On HP Wide Vision FHD Camera                           | 1         | 1.33%   |
| Lenovo UVC Camera                                           | 1         | 1.33%   |
| Importek TOSHIBA Web Camera - HD                            | 1         | 1.33%   |
| IMC Networks USB 2.0 UVC VGA WebCam                         | 1         | 1.33%   |
| Cubeternet GL-UPC822 UVC WebCam                             | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 46.67%  |
| Upek                  | 4         | 26.67%  |
| LighTuning Technology | 2         | 13.33%  |
| Synaptics             | 1         | 6.67%   |
| AuthenTec             | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.67%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                        | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.67%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.67%   |
| LighTuning Fingerprint Reader                          | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.67%   |
| AuthenTec AES2810                                      | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 42.86%  |
| Broadcom    | 2         | 28.57%  |
| O2 Micro    | 1         | 14.29%  |
| Lenovo      | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 42.86%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 14.29%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 51        | 57.95%  |
| 1     | 29        | 32.95%  |
| 2     | 8         | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 35.56%  |
| Fingerprint reader       | 15        | 33.33%  |
| Chipcard                 | 6         | 13.33%  |
| Storage                  | 3         | 6.67%   |
| Net/wireless             | 2         | 4.44%   |
| Multimedia controller    | 1         | 2.22%   |
| Communication controller | 1         | 2.22%   |
| Bluetooth                | 1         | 2.22%   |


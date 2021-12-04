MX 19 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 19.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Unknown                     | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Google        | Akemi                       | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| Dell          | Latitude E7450              | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Dell          | Latitude 3190               | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Dell          | Latitude 3190               | [e05975be8f](https://linux-hardware.org/?probe=e05975be8f) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Dell          | Latitude 3190               | [c5242a21e6](https://linux-hardware.org/?probe=c5242a21e6) | Oct 11, 2021 |
| Sony          | SVT13115FBS                 | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| Dell          | Latitude 3190               | [bb6d2c2c67](https://linux-hardware.org/?probe=bb6d2c2c67) | Oct 04, 2021 |
| Dell          | Latitude 3190               | [6a71754838](https://linux-hardware.org/?probe=6a71754838) | Sep 27, 2021 |
| Dell          | Latitude 3190               | [c5f29e40e9](https://linux-hardware.org/?probe=c5f29e40e9) | Sep 20, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Dell          | Latitude 3190               | [91b5632082](https://linux-hardware.org/?probe=91b5632082) | Sep 13, 2021 |
| GTZS          | Unknown                     | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Dell          | Latitude 3190               | [76feb70b2f](https://linux-hardware.org/?probe=76feb70b2f) | Aug 30, 2021 |
| Dell          | Latitude 3190               | [bf62dc4914](https://linux-hardware.org/?probe=bf62dc4914) | Aug 23, 2021 |
| Dell          | Latitude 3190               | [1b11784345](https://linux-hardware.org/?probe=1b11784345) | Aug 16, 2021 |
| Pixus         | Rise                        | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| Dell          | Latitude 3190               | [bbef2b9d97](https://linux-hardware.org/?probe=bbef2b9d97) | Aug 09, 2021 |
| Dell          | Latitude 3190               | [61b56c3bd9](https://linux-hardware.org/?probe=61b56c3bd9) | Aug 02, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| Dell          | Latitude 3190               | [520fb53552](https://linux-hardware.org/?probe=520fb53552) | Jul 26, 2021 |
| Acer          | Aspire E5-574G              | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| Dell          | Latitude 3190               | [dc44dffece](https://linux-hardware.org/?probe=dc44dffece) | Jul 19, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3190               | [701b0f5439](https://linux-hardware.org/?probe=701b0f5439) | Jul 12, 2021 |
| Dell          | Latitude 3190               | [6ca8a34d23](https://linux-hardware.org/?probe=6ca8a34d23) | Jul 05, 2021 |
| Dell          | Latitude 3190               | [ec46d1beb2](https://linux-hardware.org/?probe=ec46d1beb2) | Jun 28, 2021 |
| Dell          | Latitude 3190               | [c4cdd3a43c](https://linux-hardware.org/?probe=c4cdd3a43c) | Jun 21, 2021 |
| Dell          | Latitude 3190               | [5a6254c4af](https://linux-hardware.org/?probe=5a6254c4af) | Jun 14, 2021 |
| Medion        | P6669 MD60147               | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Dell          | Latitude 3190               | [e96a8c3e76](https://linux-hardware.org/?probe=e96a8c3e76) | Jun 07, 2021 |
| Dell          | Latitude 3190               | [7bdec3eb56](https://linux-hardware.org/?probe=7bdec3eb56) | May 31, 2021 |
| Dell          | Vostro 3460                 | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| Dell          | Latitude 3190               | [8918c312ff](https://linux-hardware.org/?probe=8918c312ff) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Dell          | Latitude 3190               | [5ffc389a2a](https://linux-hardware.org/?probe=5ffc389a2a) | May 17, 2021 |
| Dell          | Latitude 3190               | [4eeed413e6](https://linux-hardware.org/?probe=4eeed413e6) | May 10, 2021 |
| Dell          | Latitude 3190               | [5caeaa658b](https://linux-hardware.org/?probe=5caeaa658b) | May 03, 2021 |
| Dell          | Latitude 3190               | [a046e7b3f8](https://linux-hardware.org/?probe=a046e7b3f8) | Apr 26, 2021 |
| Acer          | Extensa 5620                | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Dell          | Latitude 3190               | [c94ccb949b](https://linux-hardware.org/?probe=c94ccb949b) | Apr 19, 2021 |
| Intel         | ChiefRiver                  | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Dell          | Latitude 3190               | [d0e46bf61f](https://linux-hardware.org/?probe=d0e46bf61f) | Apr 12, 2021 |
| ASUSTek       | 1025C                       | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| Dell          | Latitude 3190               | [2ff832079d](https://linux-hardware.org/?probe=2ff832079d) | Apr 05, 2021 |
| Dell          | Latitude 3190               | [3afafda719](https://linux-hardware.org/?probe=3afafda719) | Mar 29, 2021 |
| Dell          | Latitude 3190               | [d00e8dc9e8](https://linux-hardware.org/?probe=d00e8dc9e8) | Mar 22, 2021 |
| Dell          | Latitude 3190               | [83f4f1e1f1](https://linux-hardware.org/?probe=83f4f1e1f1) | Mar 15, 2021 |
| Dell          | Latitude E5470              | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| Dell          | Latitude 3190               | [8bb5c10a3c](https://linux-hardware.org/?probe=8bb5c10a3c) | Mar 08, 2021 |
| HP            | Notebook                    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Dell          | Latitude 3190               | [fb4469e67a](https://linux-hardware.org/?probe=fb4469e67a) | Mar 01, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Dell          | Latitude 3190               | [6708c8b87a](https://linux-hardware.org/?probe=6708c8b87a) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| Google        | Gnawty                      | [2983bbfda3](https://linux-hardware.org/?probe=2983bbfda3) | Feb 11, 2021 |
| HP            | 15                          | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| Google        | Gnawty                      | [ee5279728d](https://linux-hardware.org/?probe=ee5279728d) | Feb 04, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| Dell          | Latitude E5520              | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | [16a2a0af55](https://linux-hardware.org/?probe=16a2a0af55) | Dec 31, 2020 |
| HP            | Presario CQ57               | [63b31db6e7](https://linux-hardware.org/?probe=63b31db6e7) | Dec 30, 2020 |
| HP            | Presario CQ57               | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [5b5f1330c5](https://linux-hardware.org/?probe=5b5f1330c5) | Dec 13, 2020 |
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
| 4.19.0-6-amd64             | 22        | 25%     |
| 5.8.0-3-amd64              | 6         | 6.82%   |
| 5.10.0-5mx-amd64           | 6         | 6.82%   |
| 4.19.0-14-amd64            | 5         | 5.68%   |
| 4.19.0-13-amd64            | 5         | 5.68%   |
| 5.6.0-2-amd64              | 4         | 4.55%   |
| 4.19.0-16-amd64            | 3         | 3.41%   |
| 5.6.10-antix.1-amd64-smp   | 2         | 2.27%   |
| 4.19.0-9-amd64             | 2         | 2.27%   |
| 4.19.0-8-amd64             | 2         | 2.27%   |
| 4.19.0-17-amd64            | 2         | 2.27%   |
| 4.19.0-12-amd64            | 2         | 2.27%   |
| 5.8.16-antix.1-amd64-smp   | 1         | 1.14%   |
| 5.7.0-19.1-liquorix-amd64  | 1         | 1.14%   |
| 5.4.0-antix.1-amd64-smp    | 1         | 1.14%   |
| 5.4.0-3-amd64              | 1         | 1.14%   |
| 5.4.0-13.3-liquorix-amd64  | 1         | 1.14%   |
| 5.4.0-11.2-liquorix-amd64  | 1         | 1.14%   |
| 5.4.0-10.2-liquorix-amd64  | 1         | 1.14%   |
| 5.3.10-antix.1-amd64-smp   | 1         | 1.14%   |
| 5.3.0-2-amd64              | 1         | 1.14%   |
| 5.3.0-10.1-liquorix-amd64  | 1         | 1.14%   |
| 5.2.21-antix.2-amd64-smp   | 1         | 1.14%   |
| 5.2.21-antix.2-686-smp-pae | 1         | 1.14%   |
| 5.2.0-21.2-liquorix-amd64  | 1         | 1.14%   |
| 5.13.0-12.3-liquorix-amd64 | 1         | 1.14%   |
| 5.11.0-21.1-liquorix-amd64 | 1         | 1.14%   |
| 5.10.1-gnu                 | 1         | 1.14%   |
| 5.10.0-8mx-amd64           | 1         | 1.14%   |
| 5.10.0-4mx-amd64           | 1         | 1.14%   |
| 4.9.246-0409246-lowlatency | 1         | 1.14%   |
| 4.9.193-antix.1-amd64-smp  | 1         | 1.14%   |
| 4.19.174                   | 1         | 1.14%   |
| 4.19.0-6-686-pae           | 1         | 1.14%   |
| 4.19.0-18-amd64            | 1         | 1.14%   |
| 4.19.0-16-686-pae          | 1         | 1.14%   |
| 4.19.0-14-686-pae          | 1         | 1.14%   |
| 4.19.0-11-amd64            | 1         | 1.14%   |
| 4.19.0-11-686-pae          | 1         | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.0   | 47        | 54.65%  |
| 5.10.0   | 8         | 9.3%    |
| 5.8.0    | 6         | 6.98%   |
| 5.4.0    | 5         | 5.81%   |
| 5.6.0    | 4         | 4.65%   |
| 5.6.10   | 2         | 2.33%   |
| 5.3.0    | 2         | 2.33%   |
| 5.2.21   | 2         | 2.33%   |
| 5.8.16   | 1         | 1.16%   |
| 5.7.0    | 1         | 1.16%   |
| 5.3.10   | 1         | 1.16%   |
| 5.2.0    | 1         | 1.16%   |
| 5.13.0   | 1         | 1.16%   |
| 5.11.0   | 1         | 1.16%   |
| 5.10.1   | 1         | 1.16%   |
| 4.9.246  | 1         | 1.16%   |
| 4.9.193  | 1         | 1.16%   |
| 4.19.174 | 1         | 1.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 48        | 55.81%  |
| 5.10    | 9         | 10.47%  |
| 5.8     | 7         | 8.14%   |
| 5.6     | 6         | 6.98%   |
| 5.4     | 5         | 5.81%   |
| 5.3     | 3         | 3.49%   |
| 5.2     | 3         | 3.49%   |
| 4.9     | 2         | 2.33%   |
| 5.7     | 1         | 1.16%   |
| 5.13    | 1         | 1.16%   |
| 5.11    | 1         | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 76        | 93.83%  |
| i686   | 5         | 6.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 58        | 71.6%   |
| KDE5            | 8         | 9.88%   |
| Unknown         | 4         | 4.94%   |
| MATE            | 2         | 2.47%   |
| Budgie          | 2         | 2.47%   |
| X-Cinnamon      | 1         | 1.23%   |
| LXQt            | 1         | 1.23%   |
| LXDE            | 1         | 1.23%   |
| i3              | 1         | 1.23%   |
| GNOME Flashback | 1         | 1.23%   |
| fluxbox         | 1         | 1.23%   |
| Cinnamon        | 1         | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 81        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 70        | 86.42%  |
| SDDM    | 7         | 8.64%   |
| SLiM    | 4         | 4.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 28        | 33.33%  |
| Unknown | 18        | 21.43%  |
| de_DE   | 6         | 7.14%   |
| sk_SK   | 5         | 5.95%   |
| en_GB   | 5         | 5.95%   |
| ru_RU   | 4         | 4.76%   |
| pt_BR   | 3         | 3.57%   |
| pl_PL   | 2         | 2.38%   |
| it_IT   | 2         | 2.38%   |
| fr_FR   | 2         | 2.38%   |
| zh_CN   | 1         | 1.19%   |
| uk_UA   | 1         | 1.19%   |
| tr_TR   | 1         | 1.19%   |
| nl_NL   | 1         | 1.19%   |
| fr_BE   | 1         | 1.19%   |
| es_MX   | 1         | 1.19%   |
| en_IE   | 1         | 1.19%   |
| en_AU   | 1         | 1.19%   |
| cs_CZ   | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 48        | 59.26%  |
| EFI  | 33        | 40.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 72        | 88.89%  |
| Overlay | 7         | 8.64%   |
| F2fs    | 1         | 1.23%   |
| Btrfs   | 1         | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 42        | 51.85%  |
| MBR     | 38        | 46.91%  |
| Unknown | 1         | 1.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 85.19%  |
| Yes       | 12        | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 56.79%  |
| Yes       | 35        | 43.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 19.75%  |
| Hewlett-Packard     | 15        | 18.52%  |
| Dell                | 12        | 14.81%  |
| Acer                | 10        | 12.35%  |
| ASUSTek Computer    | 8         | 9.88%   |
| Toshiba             | 4         | 4.94%   |
| Sony                | 2         | 2.47%   |
| Samsung Electronics | 2         | 2.47%   |
| MSI                 | 2         | 2.47%   |
| Medion              | 2         | 2.47%   |
| Google              | 2         | 2.47%   |
| Fujitsu Siemens     | 2         | 2.47%   |
| Pixus               | 1         | 1.23%   |
| Intel               | 1         | 1.23%   |
| eMachines           | 1         | 1.23%   |
| Clevo               | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite P875                   | 1         | 1.23%   |
| Toshiba Satellite C50-A-12K              | 1         | 1.23%   |
| Toshiba Satellite A300                   | 1         | 1.23%   |
| Toshiba PORTEGE R705                     | 1         | 1.23%   |
| Sony VPCF23P1E                           | 1         | 1.23%   |
| Sony SVT13115FBS                         | 1         | 1.23%   |
| Samsung R780/R778                        | 1         | 1.23%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 1.23%   |
| Pixus Rise                               | 1         | 1.23%   |
| MSI MS-N033                              | 1         | 1.23%   |
| MSI GP63 Leopard 8RD                     | 1         | 1.23%   |
| Medion P6669 MD60147                     | 1         | 1.23%   |
| Medion E6234                             | 1         | 1.23%   |
| Lenovo V145-15AST 81MT                   | 1         | 1.23%   |
| Lenovo ThinkPad X301 2776LBU             | 1         | 1.23%   |
| Lenovo ThinkPad X270 W10DG 20K5S0YT00    | 1         | 1.23%   |
| Lenovo ThinkPad X250 20CLS4YA00          | 1         | 1.23%   |
| Lenovo ThinkPad X220 4291WMQ             | 1         | 1.23%   |
| Lenovo ThinkPad X201 3680MY9             | 1         | 1.23%   |
| Lenovo ThinkPad X1C 5th W10DG 20K4S0EC00 | 1         | 1.23%   |
| Lenovo ThinkPad W510 4875W17             | 1         | 1.23%   |
| Lenovo ThinkPad T440p 20AWS2T11D         | 1         | 1.23%   |
| Lenovo ThinkPad T440p 20AWA1NAUK         | 1         | 1.23%   |
| Lenovo ThinkPad T420 4236MBU             | 1         | 1.23%   |
| Lenovo ThinkPad T410 2537G99             | 1         | 1.23%   |
| Lenovo ThinkPad L412 0585W28             | 1         | 1.23%   |
| Lenovo ThinkPad E490 20N9S26G00          | 1         | 1.23%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.23%   |
| Intel ChiefRiver                         | 1         | 1.23%   |
| HP ZBook 15 G4                           | 1         | 1.23%   |
| HP Stream Laptop 14-cb0XX                | 1         | 1.23%   |
| HP ProBook 650 G1                        | 1         | 1.23%   |
| HP ProBook 4440s                         | 1         | 1.23%   |
| HP Presario CQ57                         | 1         | 1.23%   |
| HP Pavilion Laptop 15-cw0xxx             | 1         | 1.23%   |
| HP Pavilion Laptop 14-ce3xxx             | 1         | 1.23%   |
| HP Pavilion g6                           | 1         | 1.23%   |
| HP Pavilion dv7                          | 1         | 1.23%   |
| HP Notebook                              | 1         | 1.23%   |
| HP Mini 110-3500                         | 1         | 1.23%   |
| HP Laptop 14-ck0xxx                      | 1         | 1.23%   |
| HP EliteBook 8560p                       | 1         | 1.23%   |
| HP EliteBook 8540w                       | 1         | 1.23%   |
| HP 15                                    | 1         | 1.23%   |
| Google Gnawty                            | 1         | 1.23%   |
| Google Akemi                             | 1         | 1.23%   |
| Fujitsu Siemens ESPRIMO Mobile D9500     | 1         | 1.23%   |
| Fujitsu Siemens AMILO Xa 1526            | 1         | 1.23%   |
| eMachines E727                           | 1         | 1.23%   |
| Dell Vostro 5515                         | 1         | 1.23%   |
| Dell Vostro 3460                         | 1         | 1.23%   |
| Dell Latitude E7450                      | 1         | 1.23%   |
| Dell Latitude E7440                      | 1         | 1.23%   |
| Dell Latitude E5520                      | 1         | 1.23%   |
| Dell Latitude E5470                      | 1         | 1.23%   |
| Dell Latitude D430                       | 1         | 1.23%   |
| Dell Latitude 3190                       | 1         | 1.23%   |
| Dell Inspiron N5010                      | 1         | 1.23%   |
| Dell Inspiron 14-3452                    | 1         | 1.23%   |
| Dell Inspiron 13-5378                    | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 13        | 16.05%  |
| Dell Latitude           | 6         | 7.41%   |
| Acer Aspire             | 6         | 7.41%   |
| HP Pavilion             | 4         | 4.94%   |
| Toshiba Satellite       | 3         | 3.7%    |
| Dell Inspiron           | 3         | 3.7%    |
| HP ProBook              | 2         | 2.47%   |
| HP EliteBook            | 2         | 2.47%   |
| Dell Vostro             | 2         | 2.47%   |
| ASUS TUF                | 2         | 2.47%   |
| Toshiba PORTEGE         | 1         | 1.23%   |
| Sony VPCF23P1E          | 1         | 1.23%   |
| Sony SVT13115FBS        | 1         | 1.23%   |
| Samsung R780            | 1         | 1.23%   |
| Samsung 305E4A          | 1         | 1.23%   |
| Pixus Rise              | 1         | 1.23%   |
| MSI MS-N033             | 1         | 1.23%   |
| MSI GP63                | 1         | 1.23%   |
| Medion P6669            | 1         | 1.23%   |
| Medion E6234            | 1         | 1.23%   |
| Lenovo V145-15AST       | 1         | 1.23%   |
| Lenovo IdeaPad          | 1         | 1.23%   |
| Intel ChiefRiver        | 1         | 1.23%   |
| HP ZBook                | 1         | 1.23%   |
| HP Stream               | 1         | 1.23%   |
| HP Presario             | 1         | 1.23%   |
| HP Notebook             | 1         | 1.23%   |
| HP Mini                 | 1         | 1.23%   |
| HP Laptop               | 1         | 1.23%   |
| HP 15                   | 1         | 1.23%   |
| Google Gnawty           | 1         | 1.23%   |
| Google Akemi            | 1         | 1.23%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.23%   |
| Fujitsu Siemens AMILO   | 1         | 1.23%   |
| eMachines E727          | 1         | 1.23%   |
| Dell 0UW744??????       | 1         | 1.23%   |
| Clevo P150HMx           | 1         | 1.23%   |
| ASUS ZenBook            | 1         | 1.23%   |
| ASUS X540UP             | 1         | 1.23%   |
| ASUS X200CA             | 1         | 1.23%   |
| ASUS X101CH             | 1         | 1.23%   |
| ASUS N56VZ              | 1         | 1.23%   |
| ASUS 1025C              | 1         | 1.23%   |
| Acer TravelMate         | 1         | 1.23%   |
| Acer Swift              | 1         | 1.23%   |
| Acer Extensa            | 1         | 1.23%   |
| Acer AOD255             | 1         | 1.23%   |
| Unknown                 | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 12.35%  |
| 2015 | 9         | 11.11%  |
| 2013 | 9         | 11.11%  |
| 2012 | 9         | 11.11%  |
| 2018 | 8         | 9.88%   |
| 2011 | 7         | 8.64%   |
| 2010 | 7         | 8.64%   |
| 2020 | 5         | 6.17%   |
| 2008 | 5         | 6.17%   |
| 2016 | 4         | 4.94%   |
| 2021 | 3         | 3.7%    |
| 2014 | 2         | 2.47%   |
| 2017 | 1         | 1.23%   |
| 2009 | 1         | 1.23%   |
| 2006 | 1         | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 81        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 81        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 97.53%  |
| Yes  | 2         | 2.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 22        | 26.83%  |
| 8.01-16.0  | 19        | 23.17%  |
| 3.01-4.0   | 17        | 20.73%  |
| 1.01-2.0   | 10        | 12.2%   |
| 16.01-24.0 | 7         | 8.54%   |
| 32.01-64.0 | 3         | 3.66%   |
| 2.01-3.0   | 2         | 2.44%   |
| 0.51-1.0   | 2         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 37        | 42.53%  |
| 2.01-3.0  | 18        | 20.69%  |
| 0.51-1.0  | 14        | 16.09%  |
| 3.01-4.0  | 10        | 11.49%  |
| 4.01-8.0  | 6         | 6.9%    |
| 8.01-16.0 | 1         | 1.15%   |
| 0.01-0.5  | 1         | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 61        | 74.39%  |
| 2      | 19        | 23.17%  |
| 3      | 1         | 1.22%   |
| 0      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 65.43%  |
| Yes       | 28        | 34.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 88.89%  |
| No        | 9         | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 98.77%  |
| No        | 1         | 1.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 75.31%  |
| No        | 20        | 24.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 16        | 19.51%  |
| UK          | 6         | 7.32%   |
| Slovakia    | 6         | 7.32%   |
| Germany     | 5         | 6.1%    |
| Austria     | 4         | 4.88%   |
| Ukraine     | 3         | 3.66%   |
| Russia      | 3         | 3.66%   |
| Poland      | 3         | 3.66%   |
| France      | 3         | 3.66%   |
| Brazil      | 3         | 3.66%   |
| Thailand    | 2         | 2.44%   |
| Spain       | 2         | 2.44%   |
| Netherlands | 2         | 2.44%   |
| Mexico      | 2         | 2.44%   |
| Italy       | 2         | 2.44%   |
| India       | 2         | 2.44%   |
| China       | 2         | 2.44%   |
| Canada      | 2         | 2.44%   |
| Turkey      | 1         | 1.22%   |
| Sweden      | 1         | 1.22%   |
| Romania     | 1         | 1.22%   |
| Philippines | 1         | 1.22%   |
| Nigeria     | 1         | 1.22%   |
| Latvia      | 1         | 1.22%   |
| Indonesia   | 1         | 1.22%   |
| Greece      | 1         | 1.22%   |
| Czechia     | 1         | 1.22%   |
| Croatia     | 1         | 1.22%   |
| Chile       | 1         | 1.22%   |
| Belgium     | 1         | 1.22%   |
| Australia   | 1         | 1.22%   |
| Algeria     | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Bratislava              | 6         | 7.06%   |
| Vienna                  | 4         | 4.71%   |
| Oxford                  | 2         | 2.35%   |
| Los Angeles             | 2         | 2.35%   |
| Dnipro                  | 2         | 2.35%   |
| Berlin                  | 2         | 2.35%   |
| Zliv                    | 1         | 1.18%   |
| Xalapa                  | 1         | 1.18%   |
| Warsaw                  | 1         | 1.18%   |
| Vista                   | 1         | 1.18%   |
| Vertou                  | 1         | 1.18%   |
| Valencia                | 1         | 1.18%   |
| Uthai                   | 1         | 1.18%   |
| Ulverston               | 1         | 1.18%   |
| Street                  | 1         | 1.18%   |
| Steenwijk               | 1         | 1.18%   |
| Shenzhen                | 1         | 1.18%   |
| Schiedam                | 1         | 1.18%   |
| Santa Pola              | 1         | 1.18%   |
| Romulus                 | 1         | 1.18%   |
| Rivne                   | 1         | 1.18%   |
| Riga                    | 1         | 1.18%   |
| Relizane                | 1         | 1.18%   |
| Puerto Vallarta         | 1         | 1.18%   |
| Portsmouth              | 1         | 1.18%   |
| Pelham                  | 1         | 1.18%   |
| P??trai                 | 1         | 1.18%   |
| Pateros                 | 1         | 1.18%   |
| Ozark                   | 1         | 1.18%   |
| Otwock                  | 1         | 1.18%   |
| Olinda                  | 1         | 1.18%   |
| New Delhi               | 1         | 1.18%   |
| Nashville               | 1         | 1.18%   |
| Mount Laurel            | 1         | 1.18%   |
| Moscow                  | 1         | 1.18%   |
| Monument                | 1         | 1.18%   |
| Melbourne               | 1         | 1.18%   |
| Makassar                | 1         | 1.18%   |
| Macomb                  | 1         | 1.18%   |
| Leoncin                 | 1         | 1.18%   |
| Las Condes              | 1         | 1.18%   |
| Lagos                   | 1         | 1.18%   |
| Krasnodar               | 1         | 1.18%   |
| Kollam                  | 1         | 1.18%   |
| Kimry                   | 1         | 1.18%   |
| Kelso                   | 1         | 1.18%   |
| Jemappes                | 1         | 1.18%   |
| Jaworzno                | 1         | 1.18%   |
| Jaworowa                | 1         | 1.18%   |
| Jaboticabal             | 1         | 1.18%   |
| Istanbul                | 1         | 1.18%   |
| Henfield                | 1         | 1.18%   |
| Heide                   | 1         | 1.18%   |
| Hastings                | 1         | 1.18%   |
| Hartland                | 1         | 1.18%   |
| Greven                  | 1         | 1.18%   |
| Grays                   | 1         | 1.18%   |
| Gothenburg              | 1         | 1.18%   |
| Gonneville-sur-Honfleur | 1         | 1.18%   |
| Falkenstein             | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 8.82%   |
| Toshiba             | 9         | 10     | 8.82%   |
| Samsung Electronics | 9         | 12     | 8.82%   |
| Seagate             | 8         | 8      | 7.84%   |
| Kingston            | 8         | 8      | 7.84%   |
| Crucial             | 8         | 17     | 7.84%   |
| Unknown             | 7         | 10     | 6.86%   |
| HGST                | 6         | 7      | 5.88%   |
| SanDisk             | 5         | 5      | 4.9%    |
| Intel               | 4         | 5      | 3.92%   |
| SK Hynix            | 3         | 3      | 2.94%   |
| Hitachi             | 3         | 3      | 2.94%   |
| PNY                 | 2         | 2      | 1.96%   |
| Micron Technology   | 2         | 3      | 1.96%   |
| KingSpec            | 2         | 2      | 1.96%   |
| KingDian            | 2         | 2      | 1.96%   |
| A-DATA Technology   | 2         | 2      | 1.96%   |
| ZTC                 | 1         | 1      | 0.98%   |
| Transcend           | 1         | 1      | 0.98%   |
| Team                | 1         | 1      | 0.98%   |
| SMART               | 1         | 1      | 0.98%   |
| Phison Electronics  | 1         | 1      | 0.98%   |
| PHISON              | 1         | 1      | 0.98%   |
| Patriot             | 1         | 1      | 0.98%   |
| LITEONIT            | 1         | 1      | 0.98%   |
| Lexar               | 1         | 1      | 0.98%   |
| KingFast            | 1         | 1      | 0.98%   |
| Indilinx            | 1         | 1      | 0.98%   |
| GOODRAM             | 1         | 1      | 0.98%   |
| Corsair             | 1         | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Kingston SV300S37A120G 120GB SSD      | 3         | 2.91%   |
| Toshiba MQ01ABF050 500GB              | 2         | 1.94%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 1.94%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 2         | 1.94%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 1.94%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 1.94%   |
| Intel SSDSA2BW120G3H 120GB            | 2         | 1.94%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 1.94%   |
| HGST HTS721010A9E630 1TB              | 2         | 1.94%   |
| HGST HTS541010A9E680 1TB              | 2         | 1.94%   |
| Crucial CT250MX500SSD1 250GB          | 2         | 1.94%   |
| ZTC SM201-256G SSD                    | 1         | 0.97%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 0.97%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.97%   |
| WDC WD5000BPVT-60HXZT3 500GB          | 1         | 0.97%   |
| WDC WD3200LPVX-22V0TT0 320GB          | 1         | 0.97%   |
| WDC WD3200BEKT-60PVMT0 320GB          | 1         | 0.97%   |
| WDC WD2500BEVT-22A23T0 250GB          | 1         | 0.97%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.97%   |
| WDC WD10SPZX-00Z10T0 1TB              | 1         | 0.97%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 0.97%   |
| Unknown SS08G  8GB                    | 1         | 0.97%   |
| Unknown SLD64G  64GB                  | 1         | 0.97%   |
| Unknown SD16G  32GB                   | 1         | 0.97%   |
| Unknown SD04G  129GB                  | 1         | 0.97%   |
| Unknown SD  32GB                      | 1         | 0.97%   |
| Unknown HAG2e  16GB                   | 1         | 0.97%   |
| Unknown CWBC3R  64GB                  | 1         | 0.97%   |
| Unknown BJTD4R  32GB                  | 1         | 0.97%   |
| Transcend TS256GMTS430S 256GB SSD     | 1         | 0.97%   |
| Toshiba THNSNC128GMLJ 128GB SSD       | 1         | 0.97%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 0.97%   |
| Toshiba MK7575GSX 752GB               | 1         | 0.97%   |
| Toshiba MK2565GSX 250GB               | 1         | 0.97%   |
| Toshiba MK1032GSX 99GB                | 1         | 0.97%   |
| Toshiba KXG60ZNV1T02 1TB              | 1         | 0.97%   |
| Toshiba KBG40ZMT128G MEMORY 128GB     | 1         | 0.97%   |
| Team T253LE240G 240GB SSD             | 1         | 0.97%   |
| SMART SSD XceedValue2 mSATA 32GB      | 1         | 0.97%   |
| SK Hynix HFS128G3BMND-3210A 128GB SSD | 1         | 0.97%   |
| SK Hynix HBG4e  32GB                  | 1         | 0.97%   |
| SK Hynix BC711 NVMe 512GB             | 1         | 0.97%   |
| Seagate ST95005620AS 500GB            | 1         | 0.97%   |
| Seagate ST500LX012-1LM162-SSHD 500GB  | 1         | 0.97%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 0.97%   |
| Seagate ST500LM034-2GH17A 500GB       | 1         | 0.97%   |
| Seagate ST1500LM006 HN-M151RAD 1TB    | 1         | 0.97%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 0.97%   |
| SanDisk SSD U100 32GB                 | 1         | 0.97%   |
| SanDisk SSD PLUS 240GB                | 1         | 0.97%   |
| SanDisk SDSSDA120G 120GB              | 1         | 0.97%   |
| SanDisk SDSSDA-1T00 1TB               | 1         | 0.97%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 0.97%   |
| Samsung MZVLW256HEHP-000L7 256GB      | 1         | 0.97%   |
| Samsung MZVLB512HAJQ-000L7 512GB      | 1         | 0.97%   |
| Samsung MZVLB256HAHQ-000H1 256GB      | 1         | 0.97%   |
| Samsung MZNLN256HAJQ-000L7 256GB SSD  | 1         | 0.97%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD  | 1         | 0.97%   |
| Samsung MZ7LN128HCHP-000L1 128GB SSD  | 1         | 0.97%   |
| Samsung MMCQE28G8MUP-0VA 128GB SSD    | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 25%     |
| WDC                 | 7         | 7      | 21.88%  |
| Toshiba             | 6         | 7      | 18.75%  |
| HGST                | 6         | 7      | 18.75%  |
| Hitachi             | 3         | 3      | 9.38%   |
| Samsung Electronics | 2         | 3      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 8      | 15.09%  |
| Crucial             | 8         | 17     | 15.09%  |
| SanDisk             | 5         | 5      | 9.43%   |
| Samsung Electronics | 4         | 5      | 7.55%   |
| Intel               | 3         | 4      | 5.66%   |
| WDC                 | 2         | 2      | 3.77%   |
| PNY                 | 2         | 2      | 3.77%   |
| Micron Technology   | 2         | 3      | 3.77%   |
| KingSpec            | 2         | 2      | 3.77%   |
| KingDian            | 2         | 2      | 3.77%   |
| A-DATA Technology   | 2         | 2      | 3.77%   |
| ZTC                 | 1         | 1      | 1.89%   |
| Transcend           | 1         | 1      | 1.89%   |
| Toshiba             | 1         | 1      | 1.89%   |
| Team                | 1         | 1      | 1.89%   |
| SMART               | 1         | 1      | 1.89%   |
| SK Hynix            | 1         | 1      | 1.89%   |
| PHISON              | 1         | 1      | 1.89%   |
| Patriot             | 1         | 1      | 1.89%   |
| LITEONIT            | 1         | 1      | 1.89%   |
| KingFast            | 1         | 1      | 1.89%   |
| Indilinx            | 1         | 1      | 1.89%   |
| GOODRAM             | 1         | 1      | 1.89%   |
| Corsair             | 1         | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 48        | 65     | 50.53%  |
| HDD  | 31        | 35     | 32.63%  |
| MMC  | 8         | 11     | 8.42%   |
| NVMe | 8         | 10     | 8.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 100    | 80.72%  |
| NVMe | 8         | 10     | 9.64%   |
| MMC  | 8         | 11     | 9.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 69     | 73.68%  |
| 0.51-1.0   | 20        | 31     | 26.32%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 29        | 34.94%  |
| 51-100     | 17        | 20.48%  |
| 501-1000   | 12        | 14.46%  |
| 251-500    | 7         | 8.43%   |
| 21-50      | 7         | 8.43%   |
| 1-20       | 5         | 6.02%   |
| 1001-2000  | 4         | 4.82%   |
| Unknown    | 2         | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 44        | 52.38%  |
| 51-100   | 11        | 13.1%   |
| 21-50    | 9         | 10.71%  |
| 101-250  | 9         | 10.71%  |
| 501-1000 | 5         | 5.95%   |
| 251-500  | 4         | 4.76%   |
| Unknown  | 2         | 2.38%   |

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
| Works    | 62        | 92     | 72.94%  |
| Malfunc  | 15        | 18     | 17.65%  |
| Detected | 8         | 11     | 9.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 63        | 75.9%   |
| AMD                          | 10        | 12.05%  |
| Samsung Electronics          | 3         | 3.61%   |
| Nvidia                       | 2         | 2.41%   |
| Toshiba America Info Systems | 1         | 1.2%    |
| SK Hynix                     | 1         | 1.2%    |
| Silicon Motion               | 1         | 1.2%    |
| Phison Electronics           | 1         | 1.2%    |
| KIOXIA                       | 1         | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 7.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 7.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 7.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 6.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 3.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.14%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.14%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.14%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 1.14%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.14%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.14%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.14%   |
| Intel SSD 660P Series                                                            | 1         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.14%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.14%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.14%   |
| AMD SB600 IDE                                                                    | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 61        | 70.93%  |
| RAID | 9         | 10.47%  |
| NVMe | 8         | 9.3%    |
| IDE  | 8         | 9.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 85.19%  |
| AMD    | 12        | 14.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 4.94%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 4.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 2.47%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 2.47%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 2.47%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 2.47%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 2.47%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.23%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.23%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.23%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 1.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.23%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.23%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.23%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 1.23%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.23%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.23%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.23%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.23%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 1.23%   |
| Intel Core i7 CPU M 640 @ 2.80GHz           | 1         | 1.23%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.23%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.23%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.23%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.23%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.23%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.23%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.23%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 1.23%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.23%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 1.23%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz        | 1         | 1.23%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 1.23%   |
| Intel Core 2 Duo CPU T5470 @ 1.60GHz        | 1         | 1.23%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 1.23%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 1         | 1.23%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 1         | 1.23%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 1.23%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.23%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 1.23%   |
| Intel Celeron CPU B820 @ 1.70GHz            | 1         | 1.23%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1         | 1.23%   |
| Intel Celeron CPU 1005M @ 1.90GHz           | 1         | 1.23%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 1         | 1.23%   |
| Intel Atom CPU N550 @ 1.50GHz               | 1         | 1.23%   |
| Intel Atom CPU N450 @ 1.66GHz               | 1         | 1.23%   |
| Intel Atom CPU N280 @ 1.66GHz               | 1         | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 1.23%   |
| AMD Turion 64 X2 Mobile Technology TL-56    | 1         | 1.23%   |
| AMD Turion 64 X2 Mobile Technology TL-50    | 1         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 28.4%   |
| Intel Core i7           | 18        | 22.22%  |
| Intel Celeron           | 8         | 9.88%   |
| Intel Atom              | 6         | 7.41%   |
| Intel Core i3           | 4         | 4.94%   |
| Intel Core 2 Duo        | 4         | 4.94%   |
| AMD A6                  | 3         | 3.7%    |
| Intel Pentium           | 2         | 2.47%   |
| AMD Turion 64 X2 Mobile | 2         | 2.47%   |
| AMD Ryzen 7             | 2         | 2.47%   |
| Other                   | 1         | 1.23%   |
| Intel Pentium Silver    | 1         | 1.23%   |
| Intel Pentium Dual-Core | 1         | 1.23%   |
| Intel Core 2            | 1         | 1.23%   |
| AMD Ryzen 5             | 1         | 1.23%   |
| AMD E1                  | 1         | 1.23%   |
| AMD E                   | 1         | 1.23%   |
| AMD Athlon 64 X2        | 1         | 1.23%   |
| AMD A8                  | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 55        | 67.9%   |
| 4      | 19        | 23.46%  |
| 1      | 3         | 3.7%    |
| 8      | 2         | 2.47%   |
| 6      | 2         | 2.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 65.43%  |
| 1      | 28        | 34.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 96.3%   |
| 32-bit         | 3         | 3.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 10.98%  |
| 0x306a9    | 8         | 9.76%   |
| 0x206a7    | 7         | 8.54%   |
| 0x406e3    | 6         | 7.32%   |
| 0x20655    | 5         | 6.1%    |
| 0x306c3    | 3         | 3.66%   |
| 0x20652    | 3         | 3.66%   |
| 0x906ea    | 2         | 2.44%   |
| 0x806ec    | 2         | 2.44%   |
| 0x806e9    | 2         | 2.44%   |
| 0x6fd      | 2         | 2.44%   |
| 0x406c4    | 2         | 2.44%   |
| 0x40651    | 2         | 2.44%   |
| 0x306d4    | 2         | 2.44%   |
| 0x30678    | 2         | 2.44%   |
| 0x30661    | 2         | 2.44%   |
| 0x106ca    | 2         | 2.44%   |
| 0x03000027 | 2         | 2.44%   |
| 0x906e9    | 1         | 1.22%   |
| 0x806ea    | 1         | 1.22%   |
| 0x806c1    | 1         | 1.22%   |
| 0x706e5    | 1         | 1.22%   |
| 0x706a1    | 1         | 1.22%   |
| 0x6f2      | 1         | 1.22%   |
| 0x506c9    | 1         | 1.22%   |
| 0x406c3    | 1         | 1.22%   |
| 0x106e5    | 1         | 1.22%   |
| 0x106c2    | 1         | 1.22%   |
| 0x1067a    | 1         | 1.22%   |
| 0x10676    | 1         | 1.22%   |
| 0x08608103 | 1         | 1.22%   |
| 0x08600104 | 1         | 1.22%   |
| 0x0810100b | 1         | 1.22%   |
| 0x07030105 | 1         | 1.22%   |
| 0x0700010f | 1         | 1.22%   |
| 0x06006705 | 1         | 1.22%   |
| 0x05000119 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 9         | 11.11%  |
| KabyLake      | 9         | 11.11%  |
| Westmere      | 8         | 9.88%   |
| IvyBridge     | 8         | 9.88%   |
| Skylake       | 6         | 7.41%   |
| Silvermont    | 6         | 7.41%   |
| Haswell       | 5         | 6.17%   |
| Bonnell       | 5         | 6.17%   |
| Penryn        | 3         | 3.7%    |
| K8 Hammer     | 3         | 3.7%    |
| Core          | 3         | 3.7%    |
| K10 Llano     | 2         | 2.47%   |
| Broadwell     | 2         | 2.47%   |
| Zen 2         | 1         | 1.23%   |
| Zen           | 1         | 1.23%   |
| TigerLake     | 1         | 1.23%   |
| Puma          | 1         | 1.23%   |
| Nehalem       | 1         | 1.23%   |
| Jaguar        | 1         | 1.23%   |
| IceLake       | 1         | 1.23%   |
| Goldmont plus | 1         | 1.23%   |
| Goldmont      | 1         | 1.23%   |
| Excavator     | 1         | 1.23%   |
| Bobcat        | 1         | 1.23%   |
| Unknown       | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 62.11%  |
| Nvidia | 18        | 18.95%  |
| AMD    | 18        | 18.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 7.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 5.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.96%   |
| Intel HD Graphics 620                                                                    | 3         | 2.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.97%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 2.97%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 1.98%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.98%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.98%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.98%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.98%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 1.98%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 1.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.99%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.99%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.99%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.99%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.99%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.99%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.99%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.99%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.99%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.99%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.99%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.99%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.99%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.99%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 1         | 0.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.99%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.99%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.99%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.99%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.99%   |
| Intel HD Graphics 630                                                                    | 1         | 0.99%   |
| Intel HD Graphics 500                                                                    | 1         | 0.99%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.99%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 0.99%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.99%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 0.99%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                                  | 1         | 0.99%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 1         | 0.99%   |
| AMD Renoir                                                                               | 1         | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.99%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 0.99%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 0.99%   |
| AMD Mars [Radeon HD 8730M]                                                               | 1         | 0.99%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 0.99%   |
| AMD Lucienne                                                                             | 1         | 0.99%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.99%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 56.79%  |
| 1 x AMD        | 11        | 13.58%  |
| Intel + Nvidia | 10        | 12.35%  |
| 1 x Nvidia     | 7         | 8.64%   |
| 2 x AMD        | 3         | 3.7%    |
| Intel + AMD    | 3         | 3.7%    |
| AMD + Nvidia   | 1         | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 77        | 95.06%  |
| Proprietary | 2         | 2.47%   |
| Unknown     | 2         | 2.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 71.6%   |
| 0.01-0.5   | 11        | 13.58%  |
| 0.51-1.0   | 7         | 8.64%   |
| 1.01-2.0   | 5         | 6.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 23.26%  |
| Chimei Innolux          | 14        | 16.28%  |
| Samsung Electronics     | 13        | 15.12%  |
| LG Display              | 13        | 15.12%  |
| Lenovo                  | 5         | 5.81%   |
| BOE                     | 4         | 4.65%   |
| Chi Mei Optoelectronics | 3         | 3.49%   |
| LG Philips              | 2         | 2.33%   |
| InfoVision              | 2         | 2.33%   |
| HannStar                | 2         | 2.33%   |
| Dell                    | 2         | 2.33%   |
| Vizio                   | 1         | 1.16%   |
| PANDA                   | 1         | 1.16%   |
| Hewlett-Packard         | 1         | 1.16%   |
| CPT                     | 1         | 1.16%   |
| AOC                     | 1         | 1.16%   |
| Ancor Communications    | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch          | 2         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch             | 2         | 2.33%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                         | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch      | 1         | 1.16%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 1.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch      | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch      | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch      | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch      | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch     | 1         | 1.16%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 1         | 1.16%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch               | 1         | 1.16%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD04FC 1366x768 344x194mm 15.5-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD038E 1366x768 340x190mm 15.3-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD02D9 1920x1080 350x190mm 15.7-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD027A 1600x900 380x210mm 17.1-inch               | 1         | 1.16%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                   | 1         | 1.16%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                   | 1         | 1.16%   |
| Lenovo LCD Monitor LEN4074 1440x900 287x180mm 13.3-inch                   | 1         | 1.16%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch                   | 1         | 1.16%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 1         | 1.16%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 309x174mm 14.0-inch              | 1         | 1.16%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch              | 1         | 1.16%   |
| Hewlett-Packard 32 QHD HPN360C 2560x1440 710x400mm 32.1-inch              | 1         | 1.16%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 1         | 1.16%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                 | 1         | 1.16%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                          | 1         | 1.16%   |
| Dell 1908FP DEL4026 1280x1024 376x301mm 19.0-inch                         | 1         | 1.16%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                      | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch           | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 350x190mm 15.7-inch           | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 344x193mm 15.5-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch           | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 309x173mm 13.9-inch           | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1341 1366x768 290x160mm 13.0-inch           | 1         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1807 1920x1080 408x230mm 18.4-inch | 1         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1600 1920x1080 374x192mm 16.6-inch | 1         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 1.16%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                     | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 31        | 36.9%   |
| 1920x1080 (FHD)   | 29        | 34.52%  |
| 1600x900 (HD+)    | 8         | 9.52%   |
| 1280x800 (WXGA)   | 5         | 5.95%   |
| 1024x600          | 4         | 4.76%   |
| 2560x1440 (QHD)   | 2         | 2.38%   |
| 1440x900 (WXGA+)  | 2         | 2.38%   |
| 1280x1024 (SXGA)  | 2         | 2.38%   |
| 1920x1200 (WUXGA) | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 34        | 39.53%  |
| 14     | 12        | 13.95%  |
| 13     | 12        | 13.95%  |
| 17     | 5         | 5.81%   |
| 12     | 4         | 4.65%   |
| 10     | 4         | 4.65%   |
| 11     | 3         | 3.49%   |
| 19     | 2         | 2.33%   |
| 18     | 2         | 2.33%   |
| 37     | 1         | 1.16%   |
| 32     | 1         | 1.16%   |
| 27     | 1         | 1.16%   |
| 24     | 1         | 1.16%   |
| 23     | 1         | 1.16%   |
| 21     | 1         | 1.16%   |
| 20     | 1         | 1.16%   |
| 16     | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 58.14%  |
| 201-300     | 16        | 18.6%   |
| 351-400     | 11        | 12.79%  |
| 401-500     | 4         | 4.65%   |
| 501-600     | 3         | 3.49%   |
| 801-900     | 1         | 1.16%   |
| 701-800     | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 68        | 86.08%  |
| 16/10 | 8         | 10.13%  |
| 5/4   | 2         | 2.53%   |
| 3/2   | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 39.53%  |
| 81-90          | 19        | 22.09%  |
| 71-80          | 5         | 5.81%   |
| 61-70          | 4         | 4.65%   |
| 41-50          | 4         | 4.65%   |
| 121-130        | 4         | 4.65%   |
| 51-60          | 3         | 3.49%   |
| 151-200        | 3         | 3.49%   |
| 201-250        | 2         | 2.33%   |
| 141-150        | 2         | 2.33%   |
| 351-500        | 1         | 1.16%   |
| 301-350        | 1         | 1.16%   |
| 251-300        | 1         | 1.16%   |
| 131-140        | 1         | 1.16%   |
| 111-120        | 1         | 1.16%   |
| 501-1000       | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 36        | 42.86%  |
| 121-160 | 28        | 33.33%  |
| 51-100  | 17        | 20.24%  |
| 161-240 | 3         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 72        | 88.89%  |
| 2     | 9         | 11.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 45        | 34.88%  |
| Realtek Semiconductor    | 36        | 27.91%  |
| Qualcomm Atheros         | 25        | 19.38%  |
| Broadcom                 | 9         | 6.98%   |
| Ralink                   | 2         | 1.55%   |
| Nvidia                   | 2         | 1.55%   |
| Marvell Technology Group | 2         | 1.55%   |
| Huawei Technologies      | 2         | 1.55%   |
| Attansic Technology      | 2         | 1.55%   |
| Ralink Technology        | 1         | 0.78%   |
| MediaTek                 | 1         | 0.78%   |
| JMicron Technology       | 1         | 0.78%   |
| ASIX Electronics         | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 22        | 13.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 5.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 7         | 4.43%   |
| Intel Wireless 7260                                                            | 5         | 3.16%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 3.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 2.53%   |
| Intel Wireless 7265                                                            | 4         | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 4         | 2.53%   |
| Intel Centrino Advanced-N 6200                                                 | 4         | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.9%    |
| Intel Wireless 8260                                                            | 3         | 1.9%    |
| Intel Wireless 3165                                                            | 3         | 1.9%    |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.9%    |
| Intel Centrino Wireless-N 2230                                                 | 3         | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 2         | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.27%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.27%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                                 | 2         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.27%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.63%   |
| Realtek 802.11ac WLAN Adapter                                                  | 1         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.63%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.63%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.63%   |
| MediaTek WP5                                                                   | 1         | 0.63%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.63%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.63%   |
| Intel WiFi Link 5100                                                           | 1         | 0.63%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 1         | 0.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 53.09%  |
| Qualcomm Atheros      | 19        | 23.46%  |
| Realtek Semiconductor | 10        | 12.35%  |
| Broadcom              | 6         | 7.41%   |
| Ralink                | 2         | 2.47%   |
| Ralink Technology     | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 8.54%   |
| Intel Wireless 7260                                                     | 5         | 6.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.88%   |
| Intel Wireless 7265                                                     | 4         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 4.88%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 4.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.66%   |
| Intel Wireless 8260                                                     | 3         | 3.66%   |
| Intel Wireless 3165                                                     | 3         | 3.66%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 3.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.44%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.22%   |
| Realtek 802.11ac WLAN Adapter                                           | 1         | 1.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.22%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.22%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.22%   |
| Intel WiFi Link 5100                                                    | 1         | 1.22%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.22%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.22%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.22%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 42.67%  |
| Intel                    | 19        | 25.33%  |
| Qualcomm Atheros         | 10        | 13.33%  |
| Broadcom                 | 4         | 5.33%   |
| Nvidia                   | 2         | 2.67%   |
| Marvell Technology Group | 2         | 2.67%   |
| Attansic Technology      | 2         | 2.67%   |
| MediaTek                 | 1         | 1.33%   |
| JMicron Technology       | 1         | 1.33%   |
| Huawei Technologies      | 1         | 1.33%   |
| ASIX Electronics         | 1         | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 22        | 29.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 12%     |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 6.67%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 4%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 2.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 2.67%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.67%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 2.67%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 2.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.33%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 1.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.33%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 1.33%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 1.33%   |
| MediaTek WP5                                                                   | 1         | 1.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.33%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.33%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.33%   |
| Huawei DRA-L01                                                                 | 1         | 1.33%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 1.33%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 1.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 1.33%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 52.29%  |
| Ethernet | 72        | 47.06%  |
| Modem    | 1         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 55.88%  |
| Ethernet | 60        | 44.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 69        | 85.19%  |
| 1     | 11        | 13.58%  |
| 0     | 1         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 93.83%  |
| Yes  | 5         | 6.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 41.27%  |
| Broadcom                        | 9         | 14.29%  |
| Realtek Semiconductor           | 6         | 9.52%   |
| Qualcomm Atheros Communications | 5         | 7.94%   |
| Cambridge Silicon Radio         | 4         | 6.35%   |
| Lite-On Technology              | 3         | 4.76%   |
| IMC Networks                    | 3         | 4.76%   |
| Hewlett-Packard                 | 2         | 3.17%   |
| Dell                            | 2         | 3.17%   |
| Toshiba                         | 1         | 1.59%   |
| Ralink                          | 1         | 1.59%   |
| Foxconn / Hon Hai               | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 25.4%   |
| Intel Bluetooth Device                              | 6         | 9.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 6.35%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 6.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.76%   |
| Realtek Bluetooth Radio                             | 2         | 3.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.17%   |
| Qualcomm Atheros Bluetooth                          | 2         | 3.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.17%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 3.17%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 1.59%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.59%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.59%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.59%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.59%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.59%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.59%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.59%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.59%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 1.59%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 68        | 70.83%  |
| AMD                 | 15        | 15.63%  |
| Nvidia              | 11        | 11.46%  |
| GN Netcom           | 1         | 1.04%   |
| C-Media Electronics | 1         | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 9.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 9.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 8.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 6.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 5.41%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.6%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.7%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 3         | 2.7%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.8%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.8%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.8%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 1.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.9%    |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.9%    |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.9%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.9%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.9%    |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.9%    |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 0.9%    |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.9%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.9%    |
| AMD High Definition Audio Controller                                                              | 1         | 0.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.9%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 23%     |
| SK Hynix            | 21        | 21%     |
| Unknown             | 14        | 14%     |
| Micron Technology   | 13        | 13%     |
| Kingston            | 8         | 8%      |
| Elpida              | 3         | 3%      |
| A-DATA Technology   | 3         | 3%      |
| Unknown (ABCD)      | 2         | 2%      |
| Ramaxel Technology  | 2         | 2%      |
| Crucial             | 2         | 2%      |
| Unknown (F301)      | 1         | 1%      |
| TRS STAR            | 1         | 1%      |
| Teikon              | 1         | 1%      |
| Team                | 1         | 1%      |
| Smart               | 1         | 1%      |
| Patriot             | 1         | 1%      |
| High Bridge         | 1         | 1%      |
| Corsair             | 1         | 1%      |
| Apacer              | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                     | 3         | 2.73%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s                     | 3         | 2.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                        | 3         | 2.73%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s                       | 3         | 2.73%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 2         | 1.82%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.82%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                       | 2         | 1.82%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s                    | 2         | 1.82%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s                    | 2         | 1.82%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                        | 2         | 1.82%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s                        | 2         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                        | 2         | 1.82%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s                        | 2         | 1.82%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                               | 1         | 0.91%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                                  | 1         | 0.91%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                               | 1         | 0.91%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                        | 1         | 0.91%   |
| Unknown RAM Module 2GB SODIMM DRAM                                           | 1         | 0.91%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                   | 1         | 0.91%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                                    | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                               | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                        | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 1         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                     | 1         | 0.91%   |
| Unknown RAM Module 1024MB SODIMM DRAM                                        | 1         | 0.91%   |
| Unknown RAM Module 1024MB Chip DDR 533MT/s                                   | 1         | 0.91%   |
| Unknown (F301) RAM G2BT-4AFP00 16384MB SODIMM DDR4 2133MT/s                  | 1         | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s               | 1         | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM LPDDR3 2400MT/s            | 1         | 0.91%   |
| TRS STAR RAM Module 8GB SODIMM DDR3 1333MT/s                                 | 1         | 0.91%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.91%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 2667MT/s                        | 1         | 0.91%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s                        | 1         | 0.91%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2400MT/s                             | 1         | 0.91%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR2 667MT/s                     | 1         | 0.91%   |
| SK Hynix RAM HMT451S6MFR8C-H9 4096MB SODIMM DDR3 1333MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.91%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.91%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 0.91%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMT351S6BFR8C-G7 4096MB SODIMM DDR3 1067MT/s                    | 1         | 0.91%   |
| SK Hynix RAM HMT351S6AFR8C-G7 4096MB SODIMM 1067MT/s                         | 1         | 0.91%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                       | 1         | 0.91%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s                       | 1         | 0.91%   |
| SK Hynix RAM 48594D503131325336344350362D53362020 1024MB SODIMM DDR2 667MT/s | 1         | 0.91%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s                       | 1         | 0.91%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B5173BH0-CK0 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.91%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s                        | 1         | 0.91%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.91%   |
| Samsung RAM M471A5644EB0-CPB 2GB SODIMM DDR4 2133MT/s                        | 1         | 0.91%   |
| Samsung RAM M471A5244BB0-CPB 4096MB SODIMM DDR4 2400MT/s                     | 1         | 0.91%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.91%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                        | 1         | 0.91%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s                 | 1         | 0.91%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 48        | 57.14%  |
| DDR4    | 19        | 22.62%  |
| DDR2    | 7         | 8.33%   |
| LPDDR4  | 3         | 3.57%   |
| SDRAM   | 2         | 2.38%   |
| DRAM    | 2         | 2.38%   |
| LPDDR3  | 1         | 1.19%   |
| DDR     | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 95.06%  |
| Row Of Chips | 2         | 2.47%   |
| DIMM         | 1         | 1.23%   |
| Chip         | 1         | 1.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 43        | 45.74%  |
| 2048  | 21        | 22.34%  |
| 8192  | 19        | 20.21%  |
| 16384 | 8         | 8.51%   |
| 1024  | 3         | 3.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 30        | 31.25%  |
| 2667    | 12        | 12.5%   |
| 1334    | 12        | 12.5%   |
| 2400    | 7         | 7.29%   |
| 1333    | 7         | 7.29%   |
| Unknown | 5         | 5.21%   |
| 667     | 4         | 4.17%   |
| 3200    | 3         | 3.13%   |
| 1067    | 3         | 3.13%   |
| 800     | 3         | 3.13%   |
| 4199    | 2         | 2.08%   |
| 3266    | 2         | 2.08%   |
| 2133    | 2         | 2.08%   |
| 4267    | 1         | 1.04%   |
| 1867    | 1         | 1.04%   |
| 1777    | 1         | 1.04%   |
| 533     | 1         | 1.04%   |

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
| Chicony Electronics                    | 16        | 23.53%  |
| Realtek Semiconductor                  | 8         | 11.76%  |
| Microdia                               | 6         | 8.82%   |
| Sunplus Innovation Technology          | 5         | 7.35%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 7.35%   |
| Acer                                   | 5         | 7.35%   |
| Suyin                                  | 4         | 5.88%   |
| Lite-On Technology                     | 3         | 4.41%   |
| Lenovo                                 | 3         | 4.41%   |
| IMC Networks                           | 3         | 4.41%   |
| Z-Star Microelectronics                | 2         | 2.94%   |
| Syntek                                 | 2         | 2.94%   |
| Silicon Motion                         | 1         | 1.47%   |
| Ricoh                                  | 1         | 1.47%   |
| Quanta                                 | 1         | 1.47%   |
| Importek                               | 1         | 1.47%   |
| Cubeternet                             | 1         | 1.47%   |
| Alcor Micro                            | 1         | 1.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 4         | 5.88%   |
| Syntek EasyCamera                                           | 2         | 2.94%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 2.94%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 2         | 2.94%   |
| Microdia Integrated Webcam                                  | 2         | 2.94%   |
| Lite-On Integrated Camera                                   | 2         | 2.94%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 2.94%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 2.94%   |
| Chicony USB 2.0 Camera                                      | 2         | 2.94%   |
| Chicony HP Truevision HD camera                             | 2         | 2.94%   |
| Chicony HD WebCam                                           | 2         | 2.94%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 1.47%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 1.47%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.47%   |
| Suyin 1.3M HD WebCam                                        | 1         | 1.47%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.47%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.47%   |
| Sunplus HD WebCam                                           | 1         | 1.47%   |
| Sunplus Dell Integrated Webcam                              | 1         | 1.47%   |
| Sunplus Asus Webcam                                         | 1         | 1.47%   |
| Silicon Motion Silicon Motion Camera                        | 1         | 1.47%   |
| Ricoh USB2.0 Camera                                         | 1         | 1.47%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 1.47%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 1.47%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.47%   |
| Realtek Integrated Webcam                                   | 1         | 1.47%   |
| Realtek HD Webcam - Realtek                                 | 1         | 1.47%   |
| Realtek 2SF001                                              | 1         | 1.47%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.47%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.47%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 1.47%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.47%   |
| Microdia HP Integrated Webcam                               | 1         | 1.47%   |
| Lite-On HP Wide Vision FHD Camera                           | 1         | 1.47%   |
| Lenovo UVC Camera                                           | 1         | 1.47%   |
| Importek TOSHIBA Web Camera - HD                            | 1         | 1.47%   |
| IMC Networks USB 2.0 UVC VGA WebCam                         | 1         | 1.47%   |
| Cubeternet GL-UPC822 UVC WebCam                             | 1         | 1.47%   |
| Chicony VGA Webcam                                          | 1         | 1.47%   |
| Chicony USB2.0 0.3M UVC WebCam                              | 1         | 1.47%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.47%   |
| Chicony Integrated HP HD Webcam                             | 1         | 1.47%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 1.47%   |
| Chicony HP HD Webcam [Fixed]                                | 1         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101        | 1         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 1         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 1         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 1.47%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 1.47%   |
| Acer SunplusIT INC. Integrated Camera                       | 1         | 1.47%   |
| Acer Lenovo EasyCamera                                      | 1         | 1.47%   |
| Acer Integrated Camera                                      | 1         | 1.47%   |
| Acer HP Webcam                                              | 1         | 1.47%   |
| Acer HD Webcam                                              | 1         | 1.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 42.86%  |
| Upek                  | 4         | 28.57%  |
| LighTuning Technology | 2         | 14.29%  |
| Synaptics             | 1         | 7.14%   |
| AuthenTec             | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 21.43%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.14%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| LighTuning Fingerprint Reader                          | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.14%   |
| AuthenTec AES2810                                      | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 50%     |
| O2 Micro    | 1         | 16.67%  |
| Lenovo      | 1         | 16.67%  |
| Broadcom    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 50%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 48        | 59.26%  |
| 1     | 27        | 33.33%  |
| 2     | 6         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 15        | 37.5%   |
| Fingerprint reader       | 14        | 35%     |
| Chipcard                 | 5         | 12.5%   |
| Storage                  | 2         | 5%      |
| Net/wireless             | 1         | 2.5%    |
| Multimedia controller    | 1         | 2.5%    |
| Communication controller | 1         | 2.5%    |
| Bluetooth                | 1         | 2.5%    |


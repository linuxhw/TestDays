MX 19 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 19.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_19/Desktop/README.md) and [notebooks](/Dist/MX_19/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=mx-19

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
| MSI           | B460M PRO                   | Desktop     | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                     | Desktop     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Dell          | Latitude E7450              | Notebook    | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Dell          | Latitude 3190               | Notebook    | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Dell          | Latitude 3190               | Notebook    | [e05975be8f](https://linux-hardware.org/?probe=e05975be8f) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| Dell          | Latitude 3190               | Notebook    | [c5242a21e6](https://linux-hardware.org/?probe=c5242a21e6) | Oct 11, 2021 |
| Sony          | SVT13115FBS                 | Notebook    | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| GreatWall     | U320                        | Desktop     | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                        | Desktop     | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Dell          | Latitude 3190               | Notebook    | [bb6d2c2c67](https://linux-hardware.org/?probe=bb6d2c2c67) | Oct 04, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Lenovo        | IdeaPad Flex 5 15ITL05 8... | Convertible | [536f6d67e3](https://linux-hardware.org/?probe=536f6d67e3) | Oct 02, 2021 |
| Intel         | Unknown                     | Desktop     | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| Dell          | Latitude 3190               | Notebook    | [6a71754838](https://linux-hardware.org/?probe=6a71754838) | Sep 27, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| Dell          | Latitude 3190               | Notebook    | [c5f29e40e9](https://linux-hardware.org/?probe=c5f29e40e9) | Sep 20, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Dell          | Latitude 3190               | Notebook    | [91b5632082](https://linux-hardware.org/?probe=91b5632082) | Sep 13, 2021 |
| GTZS          | Unknown                     | Notebook    | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Dell          | Latitude 3190               | Notebook    | [76feb70b2f](https://linux-hardware.org/?probe=76feb70b2f) | Aug 30, 2021 |
| Dell          | Latitude 3190               | Notebook    | [bf62dc4914](https://linux-hardware.org/?probe=bf62dc4914) | Aug 23, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| Dell          | Latitude 3190               | Notebook    | [1b11784345](https://linux-hardware.org/?probe=1b11784345) | Aug 16, 2021 |
| Pixus         | Rise                        | Notebook    | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | Notebook    | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| Dell          | Latitude 3190               | Notebook    | [bbef2b9d97](https://linux-hardware.org/?probe=bbef2b9d97) | Aug 09, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [6949bed845](https://linux-hardware.org/?probe=6949bed845) | Aug 05, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [e94701caeb](https://linux-hardware.org/?probe=e94701caeb) | Aug 03, 2021 |
| Dell          | Latitude 3190               | Notebook    | [61b56c3bd9](https://linux-hardware.org/?probe=61b56c3bd9) | Aug 02, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| Dell          | Latitude 3190               | Notebook    | [520fb53552](https://linux-hardware.org/?probe=520fb53552) | Jul 26, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| Acer          | Aspire E5-574G              | Notebook    | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| Dell          | Latitude 3190               | Notebook    | [dc44dffece](https://linux-hardware.org/?probe=dc44dffece) | Jul 19, 2021 |
| Dell          | Vostro 5515                 | Notebook    | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3190               | Notebook    | [701b0f5439](https://linux-hardware.org/?probe=701b0f5439) | Jul 12, 2021 |
| Dell          | Latitude 3190               | Notebook    | [6ca8a34d23](https://linux-hardware.org/?probe=6ca8a34d23) | Jul 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [ec46d1beb2](https://linux-hardware.org/?probe=ec46d1beb2) | Jun 28, 2021 |
| Dell          | Latitude 3190               | Notebook    | [c4cdd3a43c](https://linux-hardware.org/?probe=c4cdd3a43c) | Jun 21, 2021 |
| Dell          | Latitude 3190               | Notebook    | [5a6254c4af](https://linux-hardware.org/?probe=5a6254c4af) | Jun 14, 2021 |
| Medion        | P6669 MD60147               | Notebook    | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Dell          | Latitude 3190               | Notebook    | [e96a8c3e76](https://linux-hardware.org/?probe=e96a8c3e76) | Jun 07, 2021 |
| Dell          | Latitude 3190               | Notebook    | [7bdec3eb56](https://linux-hardware.org/?probe=7bdec3eb56) | May 31, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | Notebook    | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| Dell          | Latitude 3190               | Notebook    | [8918c312ff](https://linux-hardware.org/?probe=8918c312ff) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Dell          | Latitude 3190               | Notebook    | [5ffc389a2a](https://linux-hardware.org/?probe=5ffc389a2a) | May 17, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| Dell          | Latitude 3190               | Notebook    | [4eeed413e6](https://linux-hardware.org/?probe=4eeed413e6) | May 10, 2021 |
| Dell          | Latitude 3190               | Notebook    | [5caeaa658b](https://linux-hardware.org/?probe=5caeaa658b) | May 03, 2021 |
| Dell          | Latitude 3190               | Notebook    | [a046e7b3f8](https://linux-hardware.org/?probe=a046e7b3f8) | Apr 26, 2021 |
| Acer          | Extensa 5620                | Notebook    | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | Notebook    | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Dell          | Latitude 3190               | Notebook    | [c94ccb949b](https://linux-hardware.org/?probe=c94ccb949b) | Apr 19, 2021 |
| Intel         | ChiefRiver                  | Notebook    | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | Notebook    | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Dell          | Latitude 3190               | Notebook    | [d0e46bf61f](https://linux-hardware.org/?probe=d0e46bf61f) | Apr 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | Notebook    | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| Dell          | Latitude 3190               | Notebook    | [2ff832079d](https://linux-hardware.org/?probe=2ff832079d) | Apr 05, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| Dell          | Latitude 3190               | Notebook    | [3afafda719](https://linux-hardware.org/?probe=3afafda719) | Mar 29, 2021 |
| Dell          | Latitude 3190               | Notebook    | [d00e8dc9e8](https://linux-hardware.org/?probe=d00e8dc9e8) | Mar 22, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| Dell          | Latitude 3190               | Notebook    | [83f4f1e1f1](https://linux-hardware.org/?probe=83f4f1e1f1) | Mar 15, 2021 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [dcc5bdef7d](https://linux-hardware.org/?probe=dcc5bdef7d) | Mar 12, 2021 |
| Dell          | Latitude E5470              | Notebook    | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| Dell          | Latitude 3190               | Notebook    | [8bb5c10a3c](https://linux-hardware.org/?probe=8bb5c10a3c) | Mar 08, 2021 |
| HP            | Notebook                    | Notebook    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | Notebook    | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Dell          | Latitude 3190               | Notebook    | [fb4469e67a](https://linux-hardware.org/?probe=fb4469e67a) | Mar 01, 2021 |
| Google        | Gnawty                      | Notebook    | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | Notebook    | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [2340ea8f96](https://linux-hardware.org/?probe=2340ea8f96) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | Notebook    | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Dell          | Latitude 3190               | Notebook    | [6708c8b87a](https://linux-hardware.org/?probe=6708c8b87a) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Medion        | E1235T MD99743              | Tablet      | [314aa4d200](https://linux-hardware.org/?probe=314aa4d200) | Feb 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| Google        | Gnawty                      | Notebook    | [2983bbfda3](https://linux-hardware.org/?probe=2983bbfda3) | Feb 11, 2021 |
| HP            | 15                          | Notebook    | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| Google        | Gnawty                      | Notebook    | [ee5279728d](https://linux-hardware.org/?probe=ee5279728d) | Feb 04, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| Dell          | Latitude D430               | Notebook    | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [ba37404fee](https://linux-hardware.org/?probe=ba37404fee) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| Dell          | Latitude E5520              | Notebook    | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | Notebook    | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | Notebook    | [16a2a0af55](https://linux-hardware.org/?probe=16a2a0af55) | Dec 31, 2020 |
| HP            | Presario CQ57               | Notebook    | [63b31db6e7](https://linux-hardware.org/?probe=63b31db6e7) | Dec 30, 2020 |
| HP            | Presario CQ57               | Notebook    | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [98c8e4f3a6](https://linux-hardware.org/?probe=98c8e4f3a6) | Dec 20, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [5b5f1330c5](https://linux-hardware.org/?probe=5b5f1330c5) | Dec 13, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [5783b64146](https://linux-hardware.org/?probe=5783b64146) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 4291WMQ       | Notebook    | [165b895e27](https://linux-hardware.org/?probe=165b895e27) | Dec 01, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [d3e3aa3011](https://linux-hardware.org/?probe=d3e3aa3011) | Nov 28, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [b51d9808ea](https://linux-hardware.org/?probe=b51d9808ea) | Nov 28, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4f8648d28](https://linux-hardware.org/?probe=d4f8648d28) | Nov 24, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [282590eccb](https://linux-hardware.org/?probe=282590eccb) | Nov 24, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| ASRock        | H110M-ITX                   | Desktop     | [e3ca7996d2](https://linux-hardware.org/?probe=e3ca7996d2) | Nov 13, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7bb20fa67](https://linux-hardware.org/?probe=a7bb20fa67) | Nov 08, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| Dell          | 0D28YY A00                  | Desktop     | [584335af3e](https://linux-hardware.org/?probe=584335af3e) | Oct 29, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| Hometech      | Wi11T                       | Tablet      | [78d63aeadc](https://linux-hardware.org/?probe=78d63aeadc) | Sep 30, 2020 |
| Dell          | 0M9KCM A02                  | Desktop     | [3e66c830f8](https://linux-hardware.org/?probe=3e66c830f8) | Sep 22, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| HP            | 838B 0100                   | All in one  | [c3133d1a1c](https://linux-hardware.org/?probe=c3133d1a1c) | Sep 09, 2020 |
| HP            | 8265                        | Desktop     | [38f924e8f9](https://linux-hardware.org/?probe=38f924e8f9) | Sep 07, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [f138fd7e0c](https://linux-hardware.org/?probe=f138fd7e0c) | Aug 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2f71e9b242](https://linux-hardware.org/?probe=2f71e9b242) | Aug 03, 2020 |
| HP            | 3031h                       | Desktop     | [205dd10b09](https://linux-hardware.org/?probe=205dd10b09) | Jul 29, 2020 |
| HP            | 3031h                       | Desktop     | [22ebc88fac](https://linux-hardware.org/?probe=22ebc88fac) | Jul 29, 2020 |
| HP            | Pavilion dv7                | Notebook    | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| Sony          | VPCF23P1E                   | Notebook    | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | Notebook    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| MSI           | 970A-G43                    | Desktop     | [ada20a047e](https://linux-hardware.org/?probe=ada20a047e) | May 27, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | Notebook    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Samsung       | R780/R778                   | Notebook    | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [0357ef50d4](https://linux-hardware.org/?probe=0357ef50d4) | Apr 05, 2020 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [617031b37d](https://linux-hardware.org/?probe=617031b37d) | Mar 28, 2020 |
| Clevo         | P150HMx                     | Notebook    | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [73690787f9](https://linux-hardware.org/?probe=73690787f9) | Mar 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| Dell          | 0F373D A00                  | Desktop     | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | Notebook    | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | Notebook    | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| Dell          | Latitude 3190               | Notebook    | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [296f21e934](https://linux-hardware.org/?probe=296f21e934) | Mar 03, 2020 |
| Acer          | Aspire 8943G                | Notebook    | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| ASUSTek       | M4A77T                      | Desktop     | [75d0b42f08](https://linux-hardware.org/?probe=75d0b42f08) | Mar 01, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T11... | Notebook    | [9c888bfdde](https://linux-hardware.org/?probe=9c888bfdde) | Feb 11, 2020 |
| Lenovo        | ThinkPad X201 3680MY9       | Notebook    | [26a7c0e493](https://linux-hardware.org/?probe=26a7c0e493) | Feb 09, 2020 |
| Google        | Gnawty                      | Notebook    | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | Notebook    | [8865e9546b](https://linux-hardware.org/?probe=8865e9546b) | Feb 03, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | Notebook    | [f4779c95ce](https://linux-hardware.org/?probe=f4779c95ce) | Feb 03, 2020 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ed464b4172](https://linux-hardware.org/?probe=ed464b4172) | Jan 23, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [f703814098](https://linux-hardware.org/?probe=f703814098) | Jan 23, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [3c0686b801](https://linux-hardware.org/?probe=3c0686b801) | Jan 23, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [d2104c3416](https://linux-hardware.org/?probe=d2104c3416) | Jan 20, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [48912b8dc6](https://linux-hardware.org/?probe=48912b8dc6) | Jan 19, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASUSTek       | TUF Gaming FX505GT_TUF50... | Notebook    | [0abd5b1d73](https://linux-hardware.org/?probe=0abd5b1d73) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| Toshiba       | Satellite P875              | Notebook    | [b267e93d40](https://linux-hardware.org/?probe=b267e93d40) | Jan 15, 2020 |
| Toshiba       | Satellite P875              | Notebook    | [7e579fcba2](https://linux-hardware.org/?probe=7e579fcba2) | Jan 15, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [811669dbdd](https://linux-hardware.org/?probe=811669dbdd) | Jan 13, 2020 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [8a0171b4b0](https://linux-hardware.org/?probe=8a0171b4b0) | Jan 13, 2020 |
| Gateway       | SX2185                      | Desktop     | [74f9db3262](https://linux-hardware.org/?probe=74f9db3262) | Jan 13, 2020 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [0a8865c437](https://linux-hardware.org/?probe=0a8865c437) | Jan 13, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [f10553e785](https://linux-hardware.org/?probe=f10553e785) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [3c957a3758](https://linux-hardware.org/?probe=3c957a3758) | Dec 23, 2019 |
| HP            | Pavilion g6                 | Notebook    | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | Notebook    | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [c96e6bc37c](https://linux-hardware.org/?probe=c96e6bc37c) | Dec 02, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [02ae0c5f5b](https://linux-hardware.org/?probe=02ae0c5f5b) | Dec 02, 2019 |
| MSI           | MS-N033                     | Notebook    | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | Notebook    | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | Notebook    | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| Gigabyte      | P43-ES3G                    | Desktop     | [96fa353482](https://linux-hardware.org/?probe=96fa353482) | Nov 07, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [585b07ffaf](https://linux-hardware.org/?probe=585b07ffaf) | Nov 04, 2019 |
| ASUSTek       | X101CH                      | Notebook    | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | Notebook    | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | Notebook    | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | Notebook    | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [71373d2071](https://linux-hardware.org/?probe=71373d2071) | Oct 20, 2019 |
| HP            | Pavilion g6                 | Notebook    | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 38        | 26.21%  |
| 5.6.0-2-amd64              | 11        | 7.59%   |
| 5.10.0-5mx-amd64           | 9         | 6.21%   |
| 5.8.0-3-amd64              | 8         | 5.52%   |
| 4.19.0-14-amd64            | 8         | 5.52%   |
| 4.19.0-13-amd64            | 8         | 5.52%   |
| 4.19.0-17-amd64            | 4         | 2.76%   |
| 5.8.16-antix.1-amd64-smp   | 3         | 2.07%   |
| 5.4.0-3-amd64              | 3         | 2.07%   |
| 5.2.21-antix.2-amd64-smp   | 3         | 2.07%   |
| 4.19.0-16-amd64            | 3         | 2.07%   |
| 4.19.0-12-amd64            | 3         | 2.07%   |
| 5.6.10-antix.1-amd64-smp   | 2         | 1.38%   |
| 5.10.0-8mx-amd64           | 2         | 1.38%   |
| 4.19.0-9-amd64             | 2         | 1.38%   |
| 4.19.0-8-amd64             | 2         | 1.38%   |
| 4.19.0-18-amd64            | 2         | 1.38%   |
| 5.7.0-19.1-liquorix-amd64  | 1         | 0.69%   |
| 5.6.10-antix.1-686-smp-pae | 1         | 0.69%   |
| 5.5.0-10.2-liquorix-amd64  | 1         | 0.69%   |
| 5.5.0-050500rc1-lowlatency | 1         | 0.69%   |
| 5.4.7-antix.1-amd64-smp    | 1         | 0.69%   |
| 5.4.10                     | 1         | 0.69%   |
| 5.4.0-antix.1-amd64-smp    | 1         | 0.69%   |
| 5.4.0-13.3-liquorix-amd64  | 1         | 0.69%   |
| 5.4.0-11.2-liquorix-amd64  | 1         | 0.69%   |
| 5.4.0-10.2-liquorix-amd64  | 1         | 0.69%   |
| 5.3.10-antix.1-amd64-smp   | 1         | 0.69%   |
| 5.3.0-2-amd64              | 1         | 0.69%   |
| 5.3.0-10.1-liquorix-amd64  | 1         | 0.69%   |
| 5.3.0-0.bpo.2-amd64        | 1         | 0.69%   |
| 5.2.21-antix.2-686-smp-pae | 1         | 0.69%   |
| 5.2.15-antix.1-amd64-smp   | 1         | 0.69%   |
| 5.2.0-21.2-liquorix-amd64  | 1         | 0.69%   |
| 5.13.0-12.3-liquorix-amd64 | 1         | 0.69%   |
| 5.11.0-21.1-liquorix-amd64 | 1         | 0.69%   |
| 5.10.1-gnu                 | 1         | 0.69%   |
| 5.10.0-9mx-amd64           | 1         | 0.69%   |
| 5.10.0-8mx-rt-amd64        | 1         | 0.69%   |
| 5.10.0-4mx-amd64           | 1         | 0.69%   |
| 5.10.0-0.bpo.3-amd64       | 1         | 0.69%   |
| 4.9.246-0409246-lowlatency | 1         | 0.69%   |
| 4.9.193-antix.1-amd64-smp  | 1         | 0.69%   |
| 4.9.189-antix.1-486-smp    | 1         | 0.69%   |
| 4.19.174                   | 1         | 0.69%   |
| 4.19.0-6-686-pae           | 1         | 0.69%   |
| 4.19.0-16-686-pae          | 1         | 0.69%   |
| 4.19.0-14-686-pae          | 1         | 0.69%   |
| 4.19.0-11-amd64            | 1         | 0.69%   |
| 4.19.0-11-686-pae          | 1         | 0.69%   |
| 4.19.0-10-686-pae          | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.19.0   | 69        | 50%     |
| 5.10.0   | 15        | 10.87%  |
| 5.6.0    | 11        | 7.97%   |
| 5.8.0    | 8         | 5.8%    |
| 5.4.0    | 7         | 5.07%   |
| 5.2.21   | 4         | 2.9%    |
| 5.8.16   | 3         | 2.17%   |
| 5.6.10   | 3         | 2.17%   |
| 5.3.0    | 3         | 2.17%   |
| 5.5.0    | 2         | 1.45%   |
| 5.7.0    | 1         | 0.72%   |
| 5.4.7    | 1         | 0.72%   |
| 5.4.10   | 1         | 0.72%   |
| 5.3.10   | 1         | 0.72%   |
| 5.2.15   | 1         | 0.72%   |
| 5.2.0    | 1         | 0.72%   |
| 5.13.0   | 1         | 0.72%   |
| 5.11.0   | 1         | 0.72%   |
| 5.10.1   | 1         | 0.72%   |
| 4.9.246  | 1         | 0.72%   |
| 4.9.193  | 1         | 0.72%   |
| 4.9.189  | 1         | 0.72%   |
| 4.19.174 | 1         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 70        | 50.72%  |
| 5.10    | 16        | 11.59%  |
| 5.6     | 14        | 10.14%  |
| 5.8     | 11        | 7.97%   |
| 5.4     | 9         | 6.52%   |
| 5.2     | 6         | 4.35%   |
| 5.3     | 4         | 2.9%    |
| 4.9     | 3         | 2.17%   |
| 5.5     | 2         | 1.45%   |
| 5.7     | 1         | 0.72%   |
| 5.13    | 1         | 0.72%   |
| 5.11    | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 122       | 93.85%  |
| i686   | 8         | 6.15%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 98        | 74.81%  |
| KDE5            | 14        | 10.69%  |
| Unknown         | 5         | 3.82%   |
| MATE            | 3         | 2.29%   |
| Budgie          | 2         | 1.53%   |
| X-Cinnamon      | 1         | 0.76%   |
| LXQt            | 1         | 0.76%   |
| LXDE            | 1         | 0.76%   |
| KDE             | 1         | 0.76%   |
| i3              | 1         | 0.76%   |
| GNOME Flashback | 1         | 0.76%   |
| GNOME           | 1         | 0.76%   |
| fluxbox         | 1         | 0.76%   |
| Cinnamon        | 1         | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 130       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 114       | 87.69%  |
| SDDM    | 11        | 8.46%   |
| SLiM    | 5         | 3.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 42        | 30.43%  |
| Unknown | 31        | 22.46%  |
| sk_SK   | 10        | 7.25%   |
| en_GB   | 9         | 6.52%   |
| de_DE   | 9         | 6.52%   |
| pt_BR   | 5         | 3.62%   |
| pl_PL   | 5         | 3.62%   |
| ru_RU   | 4         | 2.9%    |
| tr_TR   | 3         | 2.17%   |
| it_IT   | 3         | 2.17%   |
| fr_FR   | 3         | 2.17%   |
| uk_UA   | 2         | 1.45%   |
| es_ES   | 2         | 1.45%   |
| en_IE   | 2         | 1.45%   |
| en_AU   | 2         | 1.45%   |
| nl_NL   | 1         | 0.72%   |
| hu_HU   | 1         | 0.72%   |
| fr_CH   | 1         | 0.72%   |
| fr_BE   | 1         | 0.72%   |
| es_MX   | 1         | 0.72%   |
| cs_CZ   | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 79        | 60.77%  |
| EFI  | 51        | 39.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 119       | 90.84%  |
| Overlay | 8         | 6.11%   |
| Btrfs   | 3         | 2.29%   |
| F2fs    | 1         | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 69        | 53.08%  |
| MBR     | 59        | 45.38%  |
| Unknown | 2         | 1.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 79.7%   |
| Yes       | 27        | 20.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 50.38%  |
| No        | 65        | 49.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 20        | 15.38%  |
| Hewlett-Packard     | 19        | 14.62%  |
| ASUSTek Computer    | 18        | 13.85%  |
| Lenovo              | 16        | 12.31%  |
| Acer                | 10        | 7.69%   |
| MSI                 | 6         | 4.62%   |
| Gigabyte Technology | 6         | 4.62%   |
| ASRock              | 6         | 4.62%   |
| Intel               | 5         | 3.85%   |
| Toshiba             | 4         | 3.08%   |
| Medion              | 3         | 2.31%   |
| Fujitsu Siemens     | 3         | 2.31%   |
| Sony                | 2         | 1.54%   |
| Samsung Electronics | 2         | 1.54%   |
| ZOTAC               | 1         | 0.77%   |
| Radiant Systems     | 1         | 0.77%   |
| Pixus               | 1         | 0.77%   |
| Hometech            | 1         | 0.77%   |
| GreatWall           | 1         | 0.77%   |
| Google              | 1         | 0.77%   |
| Gateway             | 1         | 0.77%   |
| eMachines           | 1         | 0.77%   |
| ECS                 | 1         | 0.77%   |
| Clevo               | 1         | 0.77%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell Studio 540                          | 2         | 1.54%   |
| ASRock K8A780LM                          | 2         | 1.54%   |
| ZOTAC ZBOX-BI320                         | 1         | 0.77%   |
| Toshiba Satellite P875                   | 1         | 0.77%   |
| Toshiba Satellite C50-A-12K              | 1         | 0.77%   |
| Toshiba Satellite A300                   | 1         | 0.77%   |
| Toshiba PORTEGE R705                     | 1         | 0.77%   |
| Sony VPCF23P1E                           | 1         | 0.77%   |
| Sony SVT13115FBS                         | 1         | 0.77%   |
| Samsung R780/R778                        | 1         | 0.77%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 0.77%   |
| Radiant Systems P845                     | 1         | 0.77%   |
| Pixus Rise                               | 1         | 0.77%   |
| MSI MS-N033                              | 1         | 0.77%   |
| MSI MS-7C88                              | 1         | 0.77%   |
| MSI MS-7C56                              | 1         | 0.77%   |
| MSI MS-7A34                              | 1         | 0.77%   |
| MSI MS-7693                              | 1         | 0.77%   |
| MSI GP63 Leopard 8RD                     | 1         | 0.77%   |
| Medion P6669 MD60147                     | 1         | 0.77%   |
| Medion E6234                             | 1         | 0.77%   |
| Medion E1235T MD99743                    | 1         | 0.77%   |
| Lenovo V145-15AST 81MT                   | 1         | 0.77%   |
| Lenovo ThinkPad X301 2776LBU             | 1         | 0.77%   |
| Lenovo ThinkPad X270 W10DG 20K5S0YT00    | 1         | 0.77%   |
| Lenovo ThinkPad X250 20CLS4YA00          | 1         | 0.77%   |
| Lenovo ThinkPad X220 4291WMQ             | 1         | 0.77%   |
| Lenovo ThinkPad X201 3680MY9             | 1         | 0.77%   |
| Lenovo ThinkPad X1C 5th W10DG 20K4S0EC00 | 1         | 0.77%   |
| Lenovo ThinkPad W510 4875W17             | 1         | 0.77%   |
| Lenovo ThinkPad T440p 20AWS2T11D         | 1         | 0.77%   |
| Lenovo ThinkPad T440p 20AWA1NAUK         | 1         | 0.77%   |
| Lenovo ThinkPad T420 4236MBU             | 1         | 0.77%   |
| Lenovo ThinkPad T410 2537G99             | 1         | 0.77%   |
| Lenovo ThinkPad L412 0585W28             | 1         | 0.77%   |
| Lenovo ThinkPad E490 20N9S26G00          | 1         | 0.77%   |
| Lenovo IdeaPad Flex 5 15ITL05 82HT       | 1         | 0.77%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 0.77%   |
| Intel NUC8i7HVK                          | 1         | 0.77%   |
| Intel MAHOBAY                            | 1         | 0.77%   |
| Intel DCP847SKE G80890-105               | 1         | 0.77%   |
| Intel ChiefRiver                         | 1         | 0.77%   |
| Hometech Wi11T                           | 1         | 0.77%   |
| HP ZBook 15 G4                           | 1         | 0.77%   |
| HP Stream Laptop 14-cb0XX                | 1         | 0.77%   |
| HP Spectre x360 Convertible 15-df1xxx    | 1         | 0.77%   |
| HP Spectre x2 Detachable 12-c0XX         | 1         | 0.77%   |
| HP ProBook 650 G1                        | 1         | 0.77%   |
| HP ProBook 4440s                         | 1         | 0.77%   |
| HP Presario CQ57                         | 1         | 0.77%   |
| HP Pavilion Laptop 15-cw0xxx             | 1         | 0.77%   |
| HP Pavilion Laptop 14-ce3xxx             | 1         | 0.77%   |
| HP Pavilion g6                           | 1         | 0.77%   |
| HP Pavilion dv7                          | 1         | 0.77%   |
| HP Notebook                              | 1         | 0.77%   |
| HP Mini 110-3500                         | 1         | 0.77%   |
| HP Laptop 14-ck0xxx                      | 1         | 0.77%   |
| HP EliteBook 8560p                       | 1         | 0.77%   |
| HP EliteBook 8540w                       | 1         | 0.77%   |
| HP 838B 0100                             | 1         | 0.77%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 13        | 10%     |
| Dell Latitude           | 6         | 4.62%   |
| Acer Aspire             | 6         | 4.62%   |
| HP Pavilion             | 4         | 3.08%   |
| Dell OptiPlex           | 4         | 3.08%   |
| Dell Inspiron           | 4         | 3.08%   |
| Toshiba Satellite       | 3         | 2.31%   |
| ASUS TUF                | 3         | 2.31%   |
| ASUS PRIME              | 3         | 2.31%   |
| Lenovo IdeaPad          | 2         | 1.54%   |
| HP Spectre              | 2         | 1.54%   |
| HP ProBook              | 2         | 1.54%   |
| HP EliteBook            | 2         | 1.54%   |
| Fujitsu Siemens ESPRIMO | 2         | 1.54%   |
| Dell Vostro             | 2         | 1.54%   |
| Dell Studio             | 2         | 1.54%   |
| ASRock K8A780LM         | 2         | 1.54%   |
| ZOTAC ZBOX-BI320        | 1         | 0.77%   |
| Toshiba PORTEGE         | 1         | 0.77%   |
| Sony VPCF23P1E          | 1         | 0.77%   |
| Sony SVT13115FBS        | 1         | 0.77%   |
| Samsung R780            | 1         | 0.77%   |
| Samsung 305E4A          | 1         | 0.77%   |
| Radiant Systems P845    | 1         | 0.77%   |
| Pixus Rise              | 1         | 0.77%   |
| MSI MS-N033             | 1         | 0.77%   |
| MSI MS-7C88             | 1         | 0.77%   |
| MSI MS-7C56             | 1         | 0.77%   |
| MSI MS-7A34             | 1         | 0.77%   |
| MSI MS-7693             | 1         | 0.77%   |
| MSI GP63                | 1         | 0.77%   |
| Medion P6669            | 1         | 0.77%   |
| Medion E6234            | 1         | 0.77%   |
| Medion E1235T           | 1         | 0.77%   |
| Lenovo V145-15AST       | 1         | 0.77%   |
| Intel NUC8i7HVK         | 1         | 0.77%   |
| Intel MAHOBAY           | 1         | 0.77%   |
| Intel DCP847SKE         | 1         | 0.77%   |
| Intel ChiefRiver        | 1         | 0.77%   |
| Hometech Wi11T          | 1         | 0.77%   |
| HP ZBook                | 1         | 0.77%   |
| HP Stream               | 1         | 0.77%   |
| HP Presario             | 1         | 0.77%   |
| HP Notebook             | 1         | 0.77%   |
| HP Mini                 | 1         | 0.77%   |
| HP Laptop               | 1         | 0.77%   |
| HP 838B                 | 1         | 0.77%   |
| HP 3031h                | 1         | 0.77%   |
| HP 15                   | 1         | 0.77%   |
| GreatWall U320          | 1         | 0.77%   |
| Google Gnawty           | 1         | 0.77%   |
| Gigabyte Z68AP-D3       | 1         | 0.77%   |
| Gigabyte P43-ES3G       | 1         | 0.77%   |
| Gigabyte GA-880GM-UD2H  | 1         | 0.77%   |
| Gigabyte GA-880GA-UD3H  | 1         | 0.77%   |
| Gigabyte B450M          | 1         | 0.77%   |
| Gigabyte A320M-DS2      | 1         | 0.77%   |
| Gateway SX2185          | 1         | 0.77%   |
| Fujitsu Siemens AMILO   | 1         | 0.77%   |
| eMachines E727          | 1         | 0.77%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 17        | 13.08%  |
| 2013 | 14        | 10.77%  |
| 2012 | 13        | 10%     |
| 2018 | 12        | 9.23%   |
| 2011 | 12        | 9.23%   |
| 2015 | 11        | 8.46%   |
| 2010 | 10        | 7.69%   |
| 2008 | 10        | 7.69%   |
| 2020 | 8         | 6.15%   |
| 2016 | 8         | 6.15%   |
| 2021 | 5         | 3.85%   |
| 2017 | 4         | 3.08%   |
| 2014 | 3         | 2.31%   |
| 2009 | 1         | 0.77%   |
| 2007 | 1         | 0.77%   |
| 2006 | 1         | 0.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 79        | 60.77%  |
| Desktop     | 41        | 31.54%  |
| Tablet      | 4         | 3.08%   |
| Mini pc     | 3         | 2.31%   |
| Convertible | 2         | 1.54%   |
| All in one  | 1         | 0.77%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 130       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 99.23%  |
| Yes  | 1         | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 29        | 21.97%  |
| 4.01-8.0   | 27        | 20.45%  |
| 3.01-4.0   | 26        | 19.7%   |
| 16.01-24.0 | 22        | 16.67%  |
| 1.01-2.0   | 17        | 12.88%  |
| 32.01-64.0 | 6         | 4.55%   |
| 0.51-1.0   | 3         | 2.27%   |
| 2.01-3.0   | 2         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 53        | 37.59%  |
| 2.01-3.0  | 33        | 23.4%   |
| 0.51-1.0  | 24        | 17.02%  |
| 3.01-4.0  | 17        | 12.06%  |
| 4.01-8.0  | 10        | 7.09%   |
| 8.01-16.0 | 2         | 1.42%   |
| 0.01-0.5  | 2         | 1.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 80        | 60.15%  |
| 2      | 41        | 30.83%  |
| 3      | 4         | 3.01%   |
| 5      | 3         | 2.26%   |
| 4      | 3         | 2.26%   |
| 0      | 2         | 1.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 60%     |
| Yes       | 52        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 90.77%  |
| No        | 12        | 9.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 74.62%  |
| No        | 33        | 25.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 54.62%  |
| No        | 59        | 45.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 28        | 21.37%  |
| Slovakia    | 12        | 9.16%   |
| UK          | 11        | 8.4%    |
| Germany     | 7         | 5.34%   |
| Poland      | 6         | 4.58%   |
| Brazil      | 5         | 3.82%   |
| Austria     | 5         | 3.82%   |
| Ukraine     | 4         | 3.05%   |
| Spain       | 4         | 3.05%   |
| India       | 4         | 3.05%   |
| France      | 4         | 3.05%   |
| Turkey      | 3         | 2.29%   |
| Russia      | 3         | 2.29%   |
| Netherlands | 3         | 2.29%   |
| Italy       | 3         | 2.29%   |
| Canada      | 3         | 2.29%   |
| Australia   | 3         | 2.29%   |
| Thailand    | 2         | 1.53%   |
| Serbia      | 2         | 1.53%   |
| Mexico      | 2         | 1.53%   |
| Chile       | 2         | 1.53%   |
| Switzerland | 1         | 0.76%   |
| Sweden      | 1         | 0.76%   |
| Romania     | 1         | 0.76%   |
| Philippines | 1         | 0.76%   |
| Nigeria     | 1         | 0.76%   |
| Latvia      | 1         | 0.76%   |
| Ireland     | 1         | 0.76%   |
| Indonesia   | 1         | 0.76%   |
| Hungary     | 1         | 0.76%   |
| Greece      | 1         | 0.76%   |
| Denmark     | 1         | 0.76%   |
| Czechia     | 1         | 0.76%   |
| Croatia     | 1         | 0.76%   |
| Belgium     | 1         | 0.76%   |
| Algeria     | 1         | 0.76%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Bratislava      | 12        | 8.96%   |
| Vienna          | 5         | 3.73%   |
| Oxford          | 3         | 2.24%   |
| Istanbul        | 3         | 2.24%   |
| Valencia        | 2         | 1.49%   |
| Montevallo      | 2         | 1.49%   |
| Melbourne       | 2         | 1.49%   |
| Los Angeles     | 2         | 1.49%   |
| Dnipro          | 2         | 1.49%   |
| Berlin          | 2         | 1.49%   |
| Belgrade        | 2         | 1.49%   |
| Zliv            | 1         | 0.75%   |
| Xalapa          | 1         | 0.75%   |
| Warsaw          | 1         | 0.75%   |
| Vitacura        | 1         | 0.75%   |
| Vista           | 1         | 0.75%   |
| Virginia Beach  | 1         | 0.75%   |
| Vertou          | 1         | 0.75%   |
| Uthai           | 1         | 0.75%   |
| Ulverston       | 1         | 0.75%   |
| Tilburg         | 1         | 0.75%   |
| Szar            | 1         | 0.75%   |
| Sydney          | 1         | 0.75%   |
| Street          | 1         | 0.75%   |
| Steenwijk       | 1         | 0.75%   |
| Stargard        | 1         | 0.75%   |
| Springdale      | 1         | 0.75%   |
| Serrana         | 1         | 0.75%   |
| Schiedam        | 1         | 0.75%   |
| Santa Pola      | 1         | 0.75%   |
| Romulus         | 1         | 0.75%   |
| Rivne           | 1         | 0.75%   |
| Riga            | 1         | 0.75%   |
| Relizane        | 1         | 0.75%   |
| Puerto Vallarta | 1         | 0.75%   |
| Portsmouth      | 1         | 0.75%   |
| Pleasant Hill   | 1         | 0.75%   |
| Pelham          | 1         | 0.75%   |
| P??trai         | 1         | 0.75%   |
| Pateros         | 1         | 0.75%   |
| Pabianice       | 1         | 0.75%   |
| Ozark           | 1         | 0.75%   |
| Otwock          | 1         | 0.75%   |
| Olinda          | 1         | 0.75%   |
| Norwalk         | 1         | 0.75%   |
| Newtownabbey    | 1         | 0.75%   |
| New Delhi       | 1         | 0.75%   |
| Nashville       | 1         | 0.75%   |
| Mount Laurel    | 1         | 0.75%   |
| Moscow          | 1         | 0.75%   |
| Monument        | 1         | 0.75%   |
| McLoud          | 1         | 0.75%   |
| Makassar        | 1         | 0.75%   |
| Mainz           | 1         | 0.75%   |
| Madrid          | 1         | 0.75%   |
| Macomb          | 1         | 0.75%   |
| Lyon            | 1         | 0.75%   |
| Luton           | 1         | 0.75%   |
| Leoncin         | 1         | 0.75%   |
| Las Condes      | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 28        | 37     | 14.89%  |
| WDC                       | 27        | 30     | 14.36%  |
| Samsung Electronics       | 16        | 19     | 8.51%   |
| Crucial                   | 14        | 28     | 7.45%   |
| Toshiba                   | 13        | 15     | 6.91%   |
| Kingston                  | 12        | 13     | 6.38%   |
| Unknown                   | 11        | 15     | 5.85%   |
| Hitachi                   | 11        | 14     | 5.85%   |
| SanDisk                   | 9         | 9      | 4.79%   |
| Intel                     | 6         | 9      | 3.19%   |
| HGST                      | 5         | 6      | 2.66%   |
| A-DATA Technology         | 4         | 5      | 2.13%   |
| SK Hynix                  | 3         | 3      | 1.6%    |
| GOODRAM                   | 3         | 4      | 1.6%    |
| PNY                       | 2         | 2      | 1.06%   |
| Mushkin                   | 2         | 2      | 1.06%   |
| Micron Technology         | 2         | 3      | 1.06%   |
| KingFast                  | 2         | 2      | 1.06%   |
| KingDian                  | 2         | 2      | 1.06%   |
| Corsair                   | 2         | 2      | 1.06%   |
| ZTC                       | 1         | 1      | 0.53%   |
| Transcend                 | 1         | 1      | 0.53%   |
| Team                      | 1         | 1      | 0.53%   |
| SMART                     | 1         | 1      | 0.53%   |
| Phison Electronics        | 1         | 1      | 0.53%   |
| PHISON                    | 1         | 1      | 0.53%   |
| Patriot                   | 1         | 1      | 0.53%   |
| Micron/Crucial Technology | 1         | 1      | 0.53%   |
| LITEONIT                  | 1         | 1      | 0.53%   |
| Lexar                     | 1         | 1      | 0.53%   |
| KingSpec                  | 1         | 1      | 0.53%   |
| Indilinx                  | 1         | 1      | 0.53%   |
| Fujitsu                   | 1         | 2      | 0.53%   |
| ASMT                      | 1         | 3      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SV300S37A120G 120GB SSD    | 4         | 2%      |
| Hitachi HTS543232A7A384 320GB       | 4         | 2%      |
| Seagate ST500DM002-1BD142 500GB     | 3         | 1.5%    |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 1.5%    |
| WDC WD30EZRX-00D8PB0 3TB            | 2         | 1%      |
| WDC WD15EARX-00PASB0 1TB            | 2         | 1%      |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 1%      |
| Toshiba MQ01ABF050 500GB            | 2         | 1%      |
| Toshiba MK5065GSX 500GB             | 2         | 1%      |
| Seagate ST4000DM004-2CV104 4TB      | 2         | 1%      |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 1%      |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 1%      |
| SanDisk SDSSDP128G 128GB            | 2         | 1%      |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2         | 1%      |
| Kingston SA400S37240G 240GB SSD     | 2         | 1%      |
| Kingston SA400S37120G 120GB SSD     | 2         | 1%      |
| Intel SSDSA2BW120G3H 120GB          | 2         | 1%      |
| HGST HTS541010A9E680 1TB            | 2         | 1%      |
| Crucial CT250MX500SSD1 250GB        | 2         | 1%      |
| Crucial CT1000MX500SSD1 1TB         | 2         | 1%      |
| A-DATA SP600 32GB SSD               | 2         | 1%      |
| ZTC SM201-256G SSD                  | 1         | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 0.5%    |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 1         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.5%    |
| WDC WD80EZAZ-11TDBA0 8TB            | 1         | 0.5%    |
| WDC WD5003ABYX-01WERA1 500GB        | 1         | 0.5%    |
| WDC WD5000BPVT-60HXZT3 500GB        | 1         | 0.5%    |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 0.5%    |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.5%    |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 0.5%    |
| WDC WD2500JS-75NCB3 250GB           | 1         | 0.5%    |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 0.5%    |
| WDC WD2500AAJS-00L7A0 250GB         | 1         | 0.5%    |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 0.5%    |
| WDC WD20EARX-00PASB0 2TB            | 1         | 0.5%    |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 0.5%    |
| WDC WD1600AVVS-63L2B0 160GB         | 1         | 0.5%    |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 0.5%    |
| WDC WD10SPZX-00Z10T0 1TB            | 1         | 0.5%    |
| WDC WD10EZEX-75WN4A0 1TB            | 1         | 0.5%    |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 0.5%    |
| WDC WD10EARX-00N0YB0 1TB            | 1         | 0.5%    |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 0.5%    |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB  | 1         | 0.5%    |
| Unknown USD00  64GB                 | 1         | 0.5%    |
| Unknown SU08G  8GB                  | 1         | 0.5%    |
| Unknown SS08G  8GB                  | 1         | 0.5%    |
| Unknown SLD64G  64GB                | 1         | 0.5%    |
| Unknown SD16G  32GB                 | 1         | 0.5%    |
| Unknown SD128  128GB                | 1         | 0.5%    |
| Unknown SD04G  129GB                | 1         | 0.5%    |
| Unknown SD  32GB                    | 1         | 0.5%    |
| Unknown NCard  32GB                 | 1         | 0.5%    |
| Unknown HAG2e  16GB                 | 1         | 0.5%    |
| Unknown CWBC3R  64GB                | 1         | 0.5%    |
| Unknown BJTD4R  32GB                | 1         | 0.5%    |
| Unknown 032G72  32GB                | 1         | 0.5%    |
| Transcend TS256GMTS430S 256GB SSD   | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 37     | 34.57%  |
| WDC                 | 22        | 25     | 27.16%  |
| Toshiba             | 11        | 13     | 13.58%  |
| Hitachi             | 11        | 14     | 13.58%  |
| HGST                | 5         | 6      | 6.17%   |
| Samsung Electronics | 3         | 4      | 3.7%    |
| Fujitsu             | 1         | 2      | 1.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 13        | 22     | 17.11%  |
| Kingston            | 11        | 12     | 14.47%  |
| SanDisk             | 8         | 8      | 10.53%  |
| Samsung Electronics | 7         | 8      | 9.21%   |
| WDC                 | 4         | 4      | 5.26%   |
| Intel               | 4         | 6      | 5.26%   |
| A-DATA Technology   | 4         | 5      | 5.26%   |
| GOODRAM             | 3         | 4      | 3.95%   |
| PNY                 | 2         | 2      | 2.63%   |
| Micron Technology   | 2         | 3      | 2.63%   |
| KingFast            | 2         | 2      | 2.63%   |
| KingDian            | 2         | 2      | 2.63%   |
| ZTC                 | 1         | 1      | 1.32%   |
| Transcend           | 1         | 1      | 1.32%   |
| Toshiba             | 1         | 1      | 1.32%   |
| Team                | 1         | 1      | 1.32%   |
| SMART               | 1         | 1      | 1.32%   |
| SK Hynix            | 1         | 1      | 1.32%   |
| PHISON              | 1         | 1      | 1.32%   |
| Patriot             | 1         | 1      | 1.32%   |
| Mushkin             | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| KingSpec            | 1         | 1      | 1.32%   |
| Indilinx            | 1         | 1      | 1.32%   |
| Corsair             | 1         | 1      | 1.32%   |
| ASMT                | 1         | 3      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 67        | 94     | 41.1%   |
| HDD  | 67        | 101    | 41.1%   |
| NVMe | 17        | 25     | 10.43%  |
| MMC  | 12        | 17     | 7.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 107       | 192    | 78.1%   |
| NVMe | 17        | 25     | 12.41%  |
| MMC  | 12        | 17     | 8.76%   |
| SAS  | 1         | 3      | 0.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 88        | 122    | 63.31%  |
| 0.51-1.0   | 37        | 58     | 26.62%  |
| 1.01-2.0   | 6         | 7      | 4.32%   |
| 2.01-3.0   | 4         | 4      | 2.88%   |
| 3.01-4.0   | 2         | 2      | 1.44%   |
| 4.01-10.0  | 2         | 2      | 1.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 25.36%  |
| 501-1000       | 22        | 15.94%  |
| 51-100         | 22        | 15.94%  |
| 251-500        | 18        | 13.04%  |
| 21-50          | 14        | 10.14%  |
| 1001-2000      | 12        | 8.7%    |
| More than 3000 | 5         | 3.62%   |
| 1-20           | 5         | 3.62%   |
| 2001-3000      | 3         | 2.17%   |
| Unknown        | 2         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 60        | 43.8%   |
| 21-50          | 18        | 13.14%  |
| 101-250        | 16        | 11.68%  |
| 51-100         | 14        | 10.22%  |
| 251-500        | 12        | 8.76%   |
| 501-1000       | 9         | 6.57%   |
| 1001-2000      | 3         | 2.19%   |
| 2001-3000      | 2         | 1.46%   |
| Unknown        | 2         | 1.46%   |
| More than 3000 | 1         | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5003ABYX-01WERA1 500GB        | 1         | 1      | 2.86%   |
| WDC WD5000BPVT-60HXZT3 500GB        | 1         | 1      | 2.86%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 2.86%   |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 1      | 2.86%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 1      | 2.86%   |
| WDC WD20EARX-00PASB0 2TB            | 1         | 1      | 2.86%   |
| WDC WD1600AVVS-63L2B0 160GB         | 1         | 1      | 2.86%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1         | 1      | 2.86%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1      | 2.86%   |
| Toshiba MK7575GSX 752GB             | 1         | 2      | 2.86%   |
| Toshiba MK6465GSX 640GB             | 1         | 1      | 2.86%   |
| Toshiba MK2565GSX 250GB             | 1         | 1      | 2.86%   |
| Seagate ST3500820AS 500GB           | 1         | 1      | 2.86%   |
| Seagate ST3320413CS 320GB           | 1         | 1      | 2.86%   |
| Seagate ST33000651NS 3TB            | 1         | 1      | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 2.86%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1      | 2.86%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 2.86%   |
| Samsung Electronics HS122JC 120GB   | 1         | 2      | 2.86%   |
| Samsung Electronics HD322GJ 320GB   | 1         | 1      | 2.86%   |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 2.86%   |
| Indilinx IND-S325S120G 120GB SSD    | 1         | 1      | 2.86%   |
| Hitachi HUA722020ALA331 2TB         | 1         | 1      | 2.86%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 2.86%   |
| Hitachi HTS543232A7A384 320GB       | 1         | 1      | 2.86%   |
| Hitachi HDT721010SLA360 1TB         | 1         | 1      | 2.86%   |
| Hitachi HDP725016GLA380 160GB       | 1         | 1      | 2.86%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 2.86%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 2.86%   |
| Fujitsu MHV2060BH PL 64GB           | 1         | 2      | 2.86%   |
| Crucial CT512M550SSD1 512GB         | 1         | 1      | 2.86%   |
| Crucial CT256M550SSD1 256GB         | 1         | 1      | 2.86%   |
| Crucial CT240M500SSD1 240GB         | 1         | 1      | 2.86%   |
| Crucial CT1000P1SSD8 1TB            | 1         | 6      | 2.86%   |
| A-DATA Technology SU650 240GB SSD   | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 26.47%  |
| Hitachi             | 5         | 5      | 14.71%  |
| Seagate             | 4         | 5      | 11.76%  |
| Crucial             | 4         | 9      | 11.76%  |
| Toshiba             | 3         | 4      | 8.82%   |
| Samsung Electronics | 2         | 3      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| SanDisk             | 1         | 1      | 2.94%   |
| Kingston            | 1         | 1      | 2.94%   |
| Indilinx            | 1         | 1      | 2.94%   |
| Fujitsu             | 1         | 2      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 34.62%  |
| Hitachi             | 5         | 5      | 19.23%  |
| Seagate             | 4         | 5      | 15.38%  |
| Toshiba             | 3         | 4      | 11.54%  |
| Samsung Electronics | 2         | 3      | 7.69%   |
| HGST                | 2         | 2      | 7.69%   |
| Fujitsu             | 1         | 2      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 30     | 75%     |
| SSD  | 7         | 7      | 21.88%  |
| NVMe | 1         | 6      | 3.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB   | 2         | 2      | 66.67%  |
| Seagate ST3500418AS 500GB | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 97        | 164    | 65.54%  |
| Malfunc  | 30        | 43     | 20.27%  |
| Detected | 18        | 26     | 12.16%  |
| Failed   | 3         | 4      | 2.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 88        | 63.31%  |
| AMD                          | 25        | 17.99%  |
| Samsung Electronics          | 6         | 4.32%   |
| Nvidia                       | 4         | 2.88%   |
| Silicon Motion               | 2         | 1.44%   |
| Phison Electronics           | 2         | 1.44%   |
| Micron/Crucial Technology    | 2         | 1.44%   |
| Marvell Technology Group     | 2         | 1.44%   |
| JMicron Technology           | 2         | 1.44%   |
| ASMedia Technology           | 2         | 1.44%   |
| Toshiba America Info Systems | 1         | 0.72%   |
| SK Hynix                     | 1         | 0.72%   |
| Sandisk                      | 1         | 0.72%   |
| Kingston Technology Company  | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 8.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 5.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 4.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 4.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 2.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 2.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.38%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 2.38%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 3         | 1.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 3         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.19%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2         | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.19%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2         | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.19%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 2         | 1.19%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.6%    |
| SK Hynix Gold P31 SSD                                                          | 1         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.6%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.6%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.6%    |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 0.6%    |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.6%    |
| Nvidia MCP61 IDE                                                               | 1         | 0.6%    |
| Nvidia MCP55 SATA Controller                                                   | 1         | 0.6%    |
| Nvidia MCP55 IDE                                                               | 1         | 0.6%    |
| Nvidia MCP51 Serial ATA Controller                                             | 1         | 0.6%    |
| Nvidia MCP51 IDE                                                               | 1         | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.6%    |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 1         | 0.6%    |
| Marvell Group 88SE9170 SATA 6G Controller                                      | 1         | 0.6%    |
| Kingston Company KC2000 NVMe SSD                                               | 1         | 0.6%    |
| JMicron JMB368 IDE controller                                                  | 1         | 0.6%    |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 0.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.6%    |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.6%    |
| Intel SSD 660P Series                                                          | 1         | 0.6%    |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.6%    |
| Intel Non-Volatile memory controller                                           | 1         | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.6%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 92        | 62.16%  |
| IDE  | 27        | 18.24%  |
| NVMe | 17        | 11.49%  |
| RAID | 12        | 8.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 78.46%  |
| AMD    | 28        | 21.54%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 3.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 3.08%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3         | 2.31%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2         | 1.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.54%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 1.54%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.54%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.54%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2         | 1.54%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.54%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 1.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.54%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.54%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.77%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.77%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.77%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.77%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.77%   |
| Intel Core i7-8809G CPU @ 3.10GHz           | 1         | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.77%   |
| Intel Core i7-7560U CPU @ 2.40GHz           | 1         | 0.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.77%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.77%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1         | 0.77%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.77%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.77%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.77%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.77%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 0.77%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.77%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.77%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 0.77%   |
| Intel Core i7 CPU M 640 @ 2.80GHz           | 1         | 0.77%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.77%   |
| Intel Core i5-7400T CPU @ 2.40GHz           | 1         | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.77%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 0.77%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.77%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.77%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 0.77%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 0.77%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 0.77%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 0.77%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 0.77%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 0.77%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 0.77%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1         | 0.77%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 0.77%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 28        | 21.54%  |
| Intel Core i7           | 25        | 19.23%  |
| Intel Celeron           | 10        | 7.69%   |
| Intel Atom              | 10        | 7.69%   |
| Intel Core i3           | 7         | 5.38%   |
| Intel Core 2 Duo        | 5         | 3.85%   |
| AMD Ryzen 7             | 5         | 3.85%   |
| AMD Ryzen 5             | 5         | 3.85%   |
| Intel Pentium           | 4         | 3.08%   |
| Intel Core 2 Quad       | 3         | 2.31%   |
| AMD A6                  | 3         | 2.31%   |
| Other                   | 2         | 1.54%   |
| Intel Pentium Dual-Core | 2         | 1.54%   |
| AMD Turion 64 X2 Mobile | 2         | 1.54%   |
| AMD Sempron             | 2         | 1.54%   |
| AMD Phenom II X4        | 2         | 1.54%   |
| AMD E1                  | 2         | 1.54%   |
| Intel Pentium Silver    | 1         | 0.77%   |
| Intel Pentium Gold      | 1         | 0.77%   |
| Intel Core 2 Extreme    | 1         | 0.77%   |
| Intel Core 2            | 1         | 0.77%   |
| Intel Celeron M         | 1         | 0.77%   |
| Intel Celeron D         | 1         | 0.77%   |
| AMD Phenom II X6        | 1         | 0.77%   |
| AMD E                   | 1         | 0.77%   |
| AMD Athlon X4           | 1         | 0.77%   |
| AMD Athlon II X2        | 1         | 0.77%   |
| AMD Athlon 64 X2        | 1         | 0.77%   |
| AMD Athlon              | 1         | 0.77%   |
| AMD A4                  | 1         | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 73        | 56.15%  |
| 4      | 37        | 28.46%  |
| 6      | 7         | 5.38%   |
| 1      | 7         | 5.38%   |
| 8      | 6         | 4.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 130       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 73        | 56.15%  |
| 1      | 57        | 43.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 96.92%  |
| 32-bit         | 4         | 3.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 11.45%  |
| 0x206a7    | 12        | 9.16%   |
| 0x306a9    | 9         | 6.87%   |
| 0x406e3    | 6         | 4.58%   |
| 0x306c3    | 6         | 4.58%   |
| 0x20655    | 5         | 3.82%   |
| 0x20652    | 4         | 3.05%   |
| 0x906e9    | 3         | 2.29%   |
| 0x806e9    | 3         | 2.29%   |
| 0x406c4    | 3         | 2.29%   |
| 0x40651    | 3         | 2.29%   |
| 0x30678    | 3         | 2.29%   |
| 0x30661    | 3         | 2.29%   |
| 0x1067a    | 3         | 2.29%   |
| 0x03000027 | 3         | 2.29%   |
| 0x906ea    | 2         | 1.53%   |
| 0x806c1    | 2         | 1.53%   |
| 0x6fd      | 2         | 1.53%   |
| 0x406c3    | 2         | 1.53%   |
| 0x306d4    | 2         | 1.53%   |
| 0x106ca    | 2         | 1.53%   |
| 0x10677    | 2         | 1.53%   |
| 0x08701021 | 2         | 1.53%   |
| 0x0800820d | 2         | 1.53%   |
| 0x0700010f | 2         | 1.53%   |
| 0xf65      | 1         | 0.76%   |
| 0xa0653    | 1         | 0.76%   |
| 0x906ed    | 1         | 0.76%   |
| 0x906eb    | 1         | 0.76%   |
| 0x806ec    | 1         | 0.76%   |
| 0x806ea    | 1         | 0.76%   |
| 0x706e5    | 1         | 0.76%   |
| 0x706a1    | 1         | 0.76%   |
| 0x6fb      | 1         | 0.76%   |
| 0x6f2      | 1         | 0.76%   |
| 0x6d8      | 1         | 0.76%   |
| 0x506e3    | 1         | 0.76%   |
| 0x506c9    | 1         | 0.76%   |
| 0x306e4    | 1         | 0.76%   |
| 0x106e5    | 1         | 0.76%   |
| 0x106c2    | 1         | 0.76%   |
| 0x10676    | 1         | 0.76%   |
| 0x08608103 | 1         | 0.76%   |
| 0x08600104 | 1         | 0.76%   |
| 0x0810100b | 1         | 0.76%   |
| 0x08001138 | 1         | 0.76%   |
| 0x08001137 | 1         | 0.76%   |
| 0x08001126 | 1         | 0.76%   |
| 0x06006705 | 1         | 0.76%   |
| 0x06006118 | 1         | 0.76%   |
| 0x05000119 | 1         | 0.76%   |
| 0x010000dc | 1         | 0.76%   |
| 0x010000db | 1         | 0.76%   |
| 0x010000c8 | 1         | 0.76%   |
| 0x01000083 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 14        | 10.77%  |
| KabyLake      | 14        | 10.77%  |
| IvyBridge     | 11        | 8.46%   |
| Westmere      | 9         | 6.92%   |
| Silvermont    | 9         | 6.92%   |
| Haswell       | 9         | 6.92%   |
| Penryn        | 8         | 6.15%   |
| Skylake       | 7         | 5.38%   |
| Bonnell       | 6         | 4.62%   |
| K8 Hammer     | 5         | 3.85%   |
| K10           | 5         | 3.85%   |
| Zen           | 4         | 3.08%   |
| Core          | 4         | 3.08%   |
| Zen 2         | 3         | 2.31%   |
| K10 Llano     | 3         | 2.31%   |
| Zen+          | 2         | 1.54%   |
| TigerLake     | 2         | 1.54%   |
| Jaguar        | 2         | 1.54%   |
| Excavator     | 2         | 1.54%   |
| Broadwell     | 2         | 1.54%   |
| P6            | 1         | 0.77%   |
| NetBurst      | 1         | 0.77%   |
| Nehalem       | 1         | 0.77%   |
| IceLake       | 1         | 0.77%   |
| Goldmont plus | 1         | 0.77%   |
| Goldmont      | 1         | 0.77%   |
| CometLake     | 1         | 0.77%   |
| Bobcat        | 1         | 0.77%   |
| Unknown       | 1         | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 82        | 53.95%  |
| Nvidia | 35        | 23.03%  |
| AMD    | 35        | 23.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 6.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 3.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.48%   |
| Intel HD Graphics 630                                                                    | 3         | 1.86%   |
| Intel HD Graphics 620                                                                    | 3         | 1.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.86%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 1.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.86%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.86%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.24%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 1.24%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.24%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.24%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.24%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.24%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 1.24%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                                | 2         | 1.24%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 2         | 1.24%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 1.24%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.62%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.62%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.62%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.62%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 0.62%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.62%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.62%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.62%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.62%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.62%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.62%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1         | 0.62%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.62%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                                        | 1         | 0.62%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.62%   |
| Nvidia GF114 [GeForce GTX 560 SE]                                                        | 1         | 0.62%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1         | 0.62%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.62%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.62%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 0.62%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1         | 0.62%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.62%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.62%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 1         | 0.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.62%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 63        | 47.37%  |
| 1 x AMD        | 28        | 21.05%  |
| 1 x Nvidia     | 22        | 16.54%  |
| Intel + Nvidia | 12        | 9.02%   |
| Intel + AMD    | 4         | 3.01%   |
| 2 x AMD        | 2         | 1.5%    |
| 3 x AMD        | 1         | 0.75%   |
| AMD + Nvidia   | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 115       | 87.79%  |
| Proprietary | 13        | 9.92%   |
| Unknown     | 3         | 2.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 59.4%   |
| 0.01-0.5   | 19        | 14.29%  |
| 1.01-2.0   | 14        | 10.53%  |
| 0.51-1.0   | 12        | 9.02%   |
| 3.01-4.0   | 4         | 3.01%   |
| 7.01-8.0   | 3         | 2.26%   |
| 5.01-6.0   | 1         | 0.75%   |
| 2.01-3.0   | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 17.29%  |
| AU Optronics            | 21        | 15.79%  |
| LG Display              | 14        | 10.53%  |
| Chimei Innolux          | 14        | 10.53%  |
| Goldstar                | 9         | 6.77%   |
| Dell                    | 8         | 6.02%   |
| Lenovo                  | 5         | 3.76%   |
| BOE                     | 4         | 3.01%   |
| Acer                    | 4         | 3.01%   |
| Chi Mei Optoelectronics | 3         | 2.26%   |
| Ancor Communications    | 3         | 2.26%   |
| ViewSonic               | 2         | 1.5%    |
| Philips                 | 2         | 1.5%    |
| LG Philips              | 2         | 1.5%    |
| InfoVision              | 2         | 1.5%    |
| Hewlett-Packard         | 2         | 1.5%    |
| HannStar                | 2         | 1.5%    |
| BenQ                    | 2         | 1.5%    |
| Vizio                   | 1         | 0.75%   |
| Vestel Elektronik       | 1         | 0.75%   |
| Sanyo                   | 1         | 0.75%   |
| PANDA                   | 1         | 0.75%   |
| MSI                     | 1         | 0.75%   |
| IBM                     | 1         | 0.75%   |
| HYO                     | 1         | 0.75%   |
| Eizo                    | 1         | 0.75%   |
| CPT                     | 1         | 0.75%   |
| CHR                     | 1         | 0.75%   |
| AOC                     | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6         | 4.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 1.5%    |
| Goldstar LG 32 FHD GSM76FF 1920x1080 700x390mm 31.5-inch                | 2         | 1.5%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch        | 2         | 1.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 1.5%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch         | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch           | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch           | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch           | 2         | 1.5%    |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                       | 1         | 0.75%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.75%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1         | 0.75%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.75%   |
| Sanyo LCD MONITOR SAN2213 1920x1080 474x296mm 22.0-inch                 | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch    | 1         | 0.75%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.75%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 0.75%   |
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch   | 1         | 0.75%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.75%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch       | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.75%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 1         | 0.75%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 1         | 0.75%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 1         | 0.75%   |
| MSI MAG271C MSI3FA6 1920x1080 600x340mm 27.2-inch                       | 1         | 0.75%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch             | 1         | 0.75%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD055D 3000x2000 260x173mm 12.3-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD04FC 1366x768 344x194mm 15.5-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD038E 1366x768 340x190mm 15.3-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD02D9 1920x1080 350x190mm 15.7-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD027A 1600x900 380x210mm 17.1-inch             | 1         | 0.75%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                 | 1         | 0.75%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                 | 1         | 0.75%   |
| Lenovo LCD Monitor LEN4074 1440x900 287x180mm 13.3-inch                 | 1         | 0.75%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch                 | 1         | 0.75%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                 | 1         | 0.75%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 309x174mm 14.0-inch            | 1         | 0.75%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch            | 1         | 0.75%   |
| IBM L191p IBM24CB 1280x1024 380x300mm 19.1-inch                         | 1         | 0.75%   |
| HYO DUAL-DVI HYO049B 2560x1440 597x336mm 27.0-inch                      | 1         | 0.75%   |
| Hewlett-Packard ALL-in-One HWP426F 1920x1080 527x296mm 23.8-inch        | 1         | 0.75%   |
| Hewlett-Packard 32 QHD HPN360C 2560x1440 710x400mm 32.1-inch            | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 50        | 38.46%  |
| 1366x768 (WXGA)    | 34        | 26.15%  |
| 1600x900 (HD+)     | 10        | 7.69%   |
| 1600x1200          | 6         | 4.62%   |
| 3840x2160 (4K)     | 5         | 3.85%   |
| 1280x800 (WXGA)    | 5         | 3.85%   |
| 1440x900 (WXGA+)   | 4         | 3.08%   |
| 1280x1024 (SXGA)   | 4         | 3.08%   |
| 1024x600           | 4         | 3.08%   |
| 2560x1440 (QHD)    | 3         | 2.31%   |
| 1920x1200 (WUXGA)  | 2         | 1.54%   |
| 1680x1050 (WSXGA+) | 2         | 1.54%   |
| 3000x2000          | 1         | 0.77%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 36        | 27.07%  |
| 14     | 12        | 9.02%   |
| 21     | 11        | 8.27%   |
| 13     | 11        | 8.27%   |
| 24     | 10        | 7.52%   |
| 23     | 6         | 4.51%   |
| 19     | 6         | 4.51%   |
| 17     | 5         | 3.76%   |
| 12     | 5         | 3.76%   |
| 27     | 4         | 3.01%   |
| 18     | 4         | 3.01%   |
| 11     | 4         | 3.01%   |
| 10     | 4         | 3.01%   |
| 20     | 3         | 2.26%   |
| 84     | 2         | 1.5%    |
| 65     | 2         | 1.5%    |
| 31     | 2         | 1.5%    |
| 42     | 1         | 0.75%   |
| 39     | 1         | 0.75%   |
| 37     | 1         | 0.75%   |
| 32     | 1         | 0.75%   |
| 22     | 1         | 0.75%   |
| 16     | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 39.39%  |
| 401-500     | 21        | 15.91%  |
| 501-600     | 19        | 14.39%  |
| 201-300     | 17        | 12.88%  |
| 351-400     | 13        | 9.85%   |
| 801-900     | 2         | 1.52%   |
| 601-700     | 2         | 1.52%   |
| 1501-2000   | 2         | 1.52%   |
| 1001-1500   | 2         | 1.52%   |
| 701-800     | 1         | 0.76%   |
| 901-1000    | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 99        | 79.84%  |
| 16/10 | 13        | 10.48%  |
| 4/3   | 6         | 4.84%   |
| 5/4   | 4         | 3.23%   |
| 3/2   | 2         | 1.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 27.48%  |
| 201-250        | 25        | 19.08%  |
| 81-90          | 19        | 14.5%   |
| 151-200        | 9         | 6.87%   |
| 61-70          | 5         | 3.82%   |
| More than 1000 | 4         | 3.05%   |
| 71-80          | 4         | 3.05%   |
| 51-60          | 4         | 3.05%   |
| 41-50          | 4         | 3.05%   |
| 301-350        | 4         | 3.05%   |
| 121-130        | 4         | 3.05%   |
| 351-500        | 3         | 2.29%   |
| 141-150        | 3         | 2.29%   |
| 501-1000       | 3         | 2.29%   |
| 251-300        | 2         | 1.53%   |
| 131-140        | 1         | 0.76%   |
| 111-120        | 1         | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 51        | 39.53%  |
| 101-120       | 41        | 31.78%  |
| 121-160       | 30        | 23.26%  |
| More than 240 | 3         | 2.33%   |
| 1-50          | 2         | 1.55%   |
| 161-240       | 2         | 1.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 119       | 90.84%  |
| 2     | 12        | 9.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 34.76%  |
| Intel                    | 60        | 32.09%  |
| Qualcomm Atheros         | 29        | 15.51%  |
| Broadcom                 | 12        | 6.42%   |
| Ralink                   | 4         | 2.14%   |
| Nvidia                   | 3         | 1.6%    |
| Marvell Technology Group | 2         | 1.07%   |
| Huawei Technologies      | 2         | 1.07%   |
| Attansic Technology      | 2         | 1.07%   |
| ASIX Electronics         | 2         | 1.07%   |
| Ralink Technology        | 1         | 0.53%   |
| MediaTek                 | 1         | 0.53%   |
| JMicron Technology       | 1         | 0.53%   |
| D-Link System            | 1         | 0.53%   |
| Broadcom Limited         | 1         | 0.53%   |
| ASUSTek Computer         | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 48        | 21.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 11        | 4.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 7         | 3.13%   |
| Intel Wireless 7260                                                                           | 6         | 2.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 5         | 2.23%   |
| Intel 82577LM Gigabit Network Connection                                                      | 5         | 2.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 1.79%   |
| Intel Wireless 8265 / 8275                                                                    | 4         | 1.79%   |
| Intel Wireless 7265                                                                           | 4         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 4         | 1.79%   |
| Intel Centrino Advanced-N 6200                                                                | 4         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 1.34%   |
| Intel Wireless 8260                                                                           | 3         | 1.34%   |
| Intel Wireless 3165                                                                           | 3         | 1.34%   |
| Intel Ethernet Connection I217-LM                                                             | 3         | 1.34%   |
| Intel Centrino Wireless-N 2230                                                                | 3         | 1.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 0.89%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 0.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                        | 2         | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2         | 0.89%   |
| Intel Wi-Fi 6 AX201                                                                           | 2         | 0.89%   |
| Intel Ethernet Connection I219-V                                                              | 2         | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                                                         | 2         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 2         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 0.89%   |
| Intel 82579V Gigabit Network Connection                                                       | 2         | 0.89%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 2         | 0.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 0.89%   |
| Attansic AR8152 v2.0 Fast Ethernet                                                            | 2         | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1         | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 0.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.45%   |
| Realtek 802.11ac NIC                                                                          | 1         | 0.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.45%   |
| Ralink RT2800 802.11n PCI                                                                     | 1         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.45%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                                         | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                                    | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                 | 1         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 0.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.45%   |
| Nvidia MCP67 Ethernet                                                                         | 1         | 0.45%   |
| Nvidia MCP61 Ethernet                                                                         | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 48.98%  |
| Qualcomm Atheros      | 22        | 22.45%  |
| Realtek Semiconductor | 14        | 14.29%  |
| Broadcom              | 8         | 8.16%   |
| Ralink                | 4         | 4.08%   |
| Ralink Technology     | 1         | 1.02%   |
| ASUSTek Computer      | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 7         | 7.07%   |
| Intel Wireless 7260                                                                           | 6         | 6.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 4.04%   |
| Intel Wireless 8265 / 8275                                                                    | 4         | 4.04%   |
| Intel Wireless 7265                                                                           | 4         | 4.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 4         | 4.04%   |
| Intel Centrino Advanced-N 6200                                                                | 4         | 4.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 3.03%   |
| Intel Wireless 8260                                                                           | 3         | 3.03%   |
| Intel Wireless 3165                                                                           | 3         | 3.03%   |
| Intel Centrino Wireless-N 2230                                                                | 3         | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 2.02%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 2.02%   |
| Intel Wi-Fi 6 AX201                                                                           | 2         | 2.02%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 2.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2         | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.01%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.01%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1         | 1.01%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.01%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.01%   |
| Realtek 802.11ac NIC                                                                          | 1         | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.01%   |
| Ralink RT2800 802.11n PCI                                                                     | 1         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.01%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1         | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.01%   |
| Intel Wireless-AC 9260                                                                        | 1         | 1.01%   |
| Intel WiFi Link 5100                                                                          | 1         | 1.01%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.01%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 1         | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 1         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 1.01%   |
| Intel Centrino Wireless-N 2200                                                                | 1         | 1.01%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1         | 1.01%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 1         | 1.01%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.01%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                                      | 1         | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 50%     |
| Intel                    | 31        | 25.41%  |
| Qualcomm Atheros         | 11        | 9.02%   |
| Broadcom                 | 5         | 4.1%    |
| Nvidia                   | 3         | 2.46%   |
| Marvell Technology Group | 2         | 1.64%   |
| Attansic Technology      | 2         | 1.64%   |
| ASIX Electronics         | 2         | 1.64%   |
| MediaTek                 | 1         | 0.82%   |
| JMicron Technology       | 1         | 0.82%   |
| Huawei Technologies      | 1         | 0.82%   |
| D-Link System            | 1         | 0.82%   |
| Broadcom Limited         | 1         | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 48        | 38.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11        | 8.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 4.03%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 4.03%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.61%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.61%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 1.61%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.81%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.81%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.81%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.81%   |
| MediaTek SP-001                                                                | 1         | 0.81%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.81%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.81%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.81%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.81%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.81%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.81%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.81%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                             | 1         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.81%   |
| Huawei BLA-L29                                                                 | 1         | 0.81%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 1         | 0.81%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.81%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 1         | 0.81%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.81%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.81%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 1         | 0.81%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.81%   |
| ASIX AX88772A Fast Ethernet                                                    | 1         | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 118       | 54.63%  |
| WiFi     | 97        | 44.91%  |
| Modem    | 1         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 103       | 52.82%  |
| WiFi     | 92        | 47.18%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 79        | 60.77%  |
| 1     | 46        | 35.38%  |
| 0     | 3         | 2.31%   |
| 3     | 2         | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 94.62%  |
| Yes  | 7         | 5.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 41.1%   |
| Broadcom                        | 10        | 13.7%   |
| Realtek Semiconductor           | 6         | 8.22%   |
| Qualcomm Atheros Communications | 6         | 8.22%   |
| Cambridge Silicon Radio         | 6         | 8.22%   |
| IMC Networks                    | 4         | 5.48%   |
| Lite-On Technology              | 3         | 4.11%   |
| Hewlett-Packard                 | 2         | 2.74%   |
| Dell                            | 2         | 2.74%   |
| Toshiba                         | 1         | 1.37%   |
| Ralink                          | 1         | 1.37%   |
| Foxconn / Hon Hai               | 1         | 1.37%   |
| ASUSTek Computer                | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 17.81%  |
| Intel Bluetooth Device                              | 9         | 12.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 8.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.48%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 5.48%   |
| Intel AX201 Bluetooth                               | 3         | 4.11%   |
| Realtek Bluetooth Radio                             | 2         | 2.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.74%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 2.74%   |
| Lite-On Bluetooth Device                            | 2         | 2.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.74%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.74%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.74%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 1.37%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.37%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.37%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.37%   |
| Intel AX200 Bluetooth                               | 1         | 1.37%   |
| IMC Networks Bluetooth Device                       | 1         | 1.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.37%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.37%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.37%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.37%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.37%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 1.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.37%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.37%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.37%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.37%   |
| ASUS BCM20702A0                                     | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 96        | 56.8%   |
| AMD                 | 36        | 21.3%   |
| Nvidia              | 26        | 15.38%  |
| Creative Labs       | 4         | 2.37%   |
| C-Media Electronics | 3         | 1.78%   |
| Tenx Technology     | 1         | 0.59%   |
| Logitech            | 1         | 0.59%   |
| JMTek               | 1         | 0.59%   |
| GN Netcom           | 1         | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 6.12%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 5.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 5.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.55%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 2.55%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.04%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.53%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.53%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 3         | 1.53%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.53%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 3         | 1.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.02%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.02%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.02%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.02%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.02%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 2         | 1.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.02%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 2         | 1.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.02%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.02%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 1.02%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.51%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.51%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.51%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.51%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.51%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.51%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia GF110 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Logitech G432 Gaming Headset                                                                      | 1         | 0.51%   |
| JMTek iTalk-02                                                                                    | 1         | 0.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.51%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 19.21%  |
| Unknown             | 27        | 17.88%  |
| SK Hynix            | 25        | 16.56%  |
| Kingston            | 16        | 10.6%   |
| Micron Technology   | 15        | 9.93%   |
| Corsair             | 8         | 5.3%    |
| Crucial             | 4         | 2.65%   |
| Patriot             | 3         | 1.99%   |
| G.Skill             | 3         | 1.99%   |
| Elpida              | 3         | 1.99%   |
| A-DATA Technology   | 3         | 1.99%   |
| Unknown (ABCD)      | 2         | 1.32%   |
| Smart               | 2         | 1.32%   |
| Ramaxel Technology  | 2         | 1.32%   |
| Apacer              | 2         | 1.32%   |
| Unknown (F301)      | 1         | 0.66%   |
| TRS STAR            | 1         | 0.66%   |
| Teikon              | 1         | 0.66%   |
| Team                | 1         | 0.66%   |
| OCZ                 | 1         | 0.66%   |
| High Bridge         | 1         | 0.66%   |
| Axiom               | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s            | 4         | 2.38%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                           | 3         | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 1.79%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s          | 3         | 1.79%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s          | 3         | 1.79%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                    | 2         | 1.19%   |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 2         | 1.19%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                        | 2         | 1.19%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s             | 2         | 1.19%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s            | 2         | 1.19%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 2         | 1.19%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s         | 2         | 1.19%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s             | 2         | 1.19%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s             | 2         | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 2         | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 2         | 1.19%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s             | 2         | 1.19%   |
| Apacer RAM 76.A302G.C4D0B 2048MB SODIMM DDR3 1600MT/s             | 2         | 1.19%   |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                            | 1         | 0.6%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                    | 1         | 0.6%    |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                         | 1         | 0.6%    |
| Unknown RAM Module 4GB DIMM SDRAM                                 | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                    | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3                             | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DRAM                                | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                         | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR3                             | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                          | 1         | 0.6%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                            | 1         | 0.6%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                           | 1         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DRAM                             | 1         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DDR                              | 1         | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                        | 1         | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR 200MT/s                        | 1         | 0.6%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                            | 1         | 0.6%    |
| Unknown RAM Module 1024MB Chip DDR 533MT/s                        | 1         | 0.6%    |
| Unknown (F301) RAM G2BT-4AFP00 16384MB SODIMM DDR4 2133MT/s       | 1         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM DDR3 2400MT/s | 1         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s      | 1         | 0.6%    |
| TRS STAR RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.6%    |
| Teikon RAM TMT451S6BFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.6%    |
| Team RAM TEAMGROUP-SD4-2400 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.6%    |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s             | 1         | 0.6%    |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s               | 1         | 0.6%    |
| Smart RAM SH564128FH8N0QHSCG 4096MB DIMM DDR3 1333MT/s            | 1         | 0.6%    |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2400MT/s                  | 1         | 0.6%    |
| SK Hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR2 667MT/s          | 1         | 0.6%    |
| SK Hynix RAM HMT451S6MFR8C-H9 4096MB SODIMM DDR3 1333MT/s         | 1         | 0.6%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.6%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.6%    |
| SK Hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s           | 1         | 0.6%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.6%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.6%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.6%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 65        | 48.87%  |
| DDR4    | 33        | 24.81%  |
| DDR2    | 13        | 9.77%   |
| Unknown | 6         | 4.51%   |
| SDRAM   | 5         | 3.76%   |
| DDR     | 4         | 3.01%   |
| LPDDR4  | 3         | 2.26%   |
| LPDDR3  | 2         | 1.5%    |
| DRAM    | 2         | 1.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 66.92%  |
| DIMM         | 40        | 30.77%  |
| Row Of Chips | 2         | 1.54%   |
| Chip         | 1         | 0.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 59        | 40.14%  |
| 2048  | 34        | 23.13%  |
| 8192  | 32        | 21.77%  |
| 16384 | 12        | 8.16%   |
| 1024  | 8         | 5.44%   |
| 32768 | 1         | 0.68%   |
| 512   | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 28.1%   |
| 1333    | 18        | 11.76%  |
| 2667    | 13        | 8.5%    |
| 1334    | 12        | 7.84%   |
| 2400    | 11        | 7.19%   |
| Unknown | 7         | 4.58%   |
| 3200    | 6         | 3.92%   |
| 800     | 6         | 3.92%   |
| 667     | 6         | 3.92%   |
| 3000    | 4         | 2.61%   |
| 2133    | 4         | 2.61%   |
| 1067    | 3         | 1.96%   |
| 49926   | 2         | 1.31%   |
| 4199    | 2         | 1.31%   |
| 3266    | 2         | 1.31%   |
| 1867    | 2         | 1.31%   |
| 533     | 2         | 1.31%   |
| 333     | 2         | 1.31%   |
| 4267    | 1         | 0.65%   |
| 3600    | 1         | 0.65%   |
| 3466    | 1         | 0.65%   |
| 2048    | 1         | 0.65%   |
| 1777    | 1         | 0.65%   |
| 1639    | 1         | 0.65%   |
| 400     | 1         | 0.65%   |
| 200     | 1         | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Konica Minolta  | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L380 Series | 1         | 33.33%  |
| Konica Minolta 206      | 1         | 33.33%  |
| HP LaserJet M101-M106   | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 50%     |
| Canon CanoScan LiDE 700F           | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 15        | 19.74%  |
| Realtek Semiconductor                  | 8         | 10.53%  |
| Microdia                               | 6         | 7.89%   |
| Sunplus Innovation Technology          | 5         | 6.58%   |
| Logitech                               | 5         | 6.58%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 6.58%   |
| Acer                                   | 5         | 6.58%   |
| Suyin                                  | 4         | 5.26%   |
| Lite-On Technology                     | 3         | 3.95%   |
| Lenovo                                 | 3         | 3.95%   |
| IMC Networks                           | 3         | 3.95%   |
| Z-Star Microelectronics                | 2         | 2.63%   |
| Syntek                                 | 2         | 2.63%   |
| Quanta                                 | 2         | 2.63%   |
| Silicon Motion                         | 1         | 1.32%   |
| Ricoh                                  | 1         | 1.32%   |
| Microsoft                              | 1         | 1.32%   |
| Importek                               | 1         | 1.32%   |
| Huawei Technologies                    | 1         | 1.32%   |
| Generalplus Technology                 | 1         | 1.32%   |
| Cubeternet                             | 1         | 1.32%   |
| Alcor Micro                            | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                | 3         | 3.95%   |
| Chicony integrated camera                                   | 3         | 3.95%   |
| Syntek EasyCamera                                           | 2         | 2.63%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 2.63%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 2.63%   |
| Microdia Integrated Webcam                                  | 2         | 2.63%   |
| Logitech Webcam C200                                        | 2         | 2.63%   |
| Lite-On Integrated Camera                                   | 2         | 2.63%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 2.63%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 2.63%   |
| Chicony USB 2.0 Camera                                      | 2         | 2.63%   |
| Chicony HP Truevision HD camera                             | 2         | 2.63%   |
| Chicony HD WebCam                                           | 2         | 2.63%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 1.32%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 1.32%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.32%   |
| Suyin 1.3M HD WebCam                                        | 1         | 1.32%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.32%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.32%   |
| Sunplus HD WebCam                                           | 1         | 1.32%   |
| Sunplus Dell Integrated Webcam                              | 1         | 1.32%   |
| Sunplus Asus Webcam                                         | 1         | 1.32%   |
| Silicon Motion Silicon Motion Camera                        | 1         | 1.32%   |
| Ricoh USB2.0 Camera                                         | 1         | 1.32%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 1.32%   |
| Realtek Integrated Webcam                                   | 1         | 1.32%   |
| Realtek HD Webcam - Realtek                                 | 1         | 1.32%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.32%   |
| Quanta HP 2.0MP High Definition Webcam                      | 1         | 1.32%   |
| Microsoft LifeCam HD-3000                                   | 1         | 1.32%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.32%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 1.32%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.32%   |
| Microdia HP Integrated Webcam                               | 1         | 1.32%   |
| Logitech Webcam Pro 9000                                    | 1         | 1.32%   |
| Logitech Webcam C270                                        | 1         | 1.32%   |
| Logitech HD Webcam C910                                     | 1         | 1.32%   |
| Lite-On HP Wide Vision FHD Camera                           | 1         | 1.32%   |
| Lenovo UVC Camera                                           | 1         | 1.32%   |
| Importek TOSHIBA Web Camera - HD                            | 1         | 1.32%   |
| IMC Networks USB 2.0 UVC VGA WebCam                         | 1         | 1.32%   |
| Huawei UVC Camera                                           | 1         | 1.32%   |
| Generalplus 808 Camera                                      | 1         | 1.32%   |
| Cubeternet GL-UPC822 UVC WebCam                             | 1         | 1.32%   |
| Chicony VGA Webcam                                          | 1         | 1.32%   |
| Chicony USB2.0 0.3M UVC WebCam                              | 1         | 1.32%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.32%   |
| Chicony Integrated HP HD Webcam                             | 1         | 1.32%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 1.32%   |
| Chicony HP HD Webcam [Fixed]                                | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101        | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 1.32%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 1.32%   |
| Acer SunplusIT Integrated Camera                            | 1         | 1.32%   |
| Acer SunplusIT INC. Integrated Camera                       | 1         | 1.32%   |
| Acer Integrated Camera                                      | 1         | 1.32%   |
| Acer HP Webcam                                              | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 37.5%   |
| Upek                  | 4         | 25%     |
| Synaptics             | 2         | 12.5%   |
| LighTuning Technology | 2         | 12.5%   |
| Elan Microelectronics | 1         | 6.25%   |
| AuthenTec             | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 18.75%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                        | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.25%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.25%   |
| LighTuning Fingerprint Reader                          | 1         | 6.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.25%   |
| AuthenTec AES2810                                      | 1         | 6.25%   |
| Unknown                                                | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 50%     |
| O2 Micro    | 1         | 16.67%  |
| Lenovo      | 1         | 16.67%  |
| Broadcom    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 70%     |
| 1     | 30        | 23.08%  |
| 2     | 6         | 4.62%   |
| 3     | 3         | 2.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 18        | 35.29%  |
| Fingerprint reader       | 16        | 31.37%  |
| Chipcard                 | 5         | 9.8%    |
| Multimedia controller    | 3         | 5.88%   |
| Communication controller | 3         | 5.88%   |
| Storage                  | 2         | 3.92%   |
| Net/wireless             | 2         | 3.92%   |
| Camera                   | 1         | 1.96%   |
| Bluetooth                | 1         | 1.96%   |


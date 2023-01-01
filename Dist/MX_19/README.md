MX 19 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 19.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_19/Desktop/README.md) and [notebooks](/Dist/MX_19/Notebook/README.md).

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

Total: 192

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7480               | Notebook    | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [732e924bbb](https://linux-hardware.org/?probe=732e924bbb) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4236TL7       | Notebook    | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | Notebook    | [f8f2a6263a](https://linux-hardware.org/?probe=f8f2a6263a) | Sep 04, 2022 |
| Acer          | Extensa 5630                | Notebook    | [9ea053d8e8](https://linux-hardware.org/?probe=9ea053d8e8) | Aug 12, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [03878be4ec](https://linux-hardware.org/?probe=03878be4ec) | Apr 20, 2022 |
| Acer          | Extensa 5630                | Notebook    | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [ecc5ad7332](https://linux-hardware.org/?probe=ecc5ad7332) | Feb 25, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [d0ba3786b2](https://linux-hardware.org/?probe=d0ba3786b2) | Feb 03, 2022 |
| HP            | ProBook 6460b               | Notebook    | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Intel         | H81                         | Desktop     | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Toshiba       | Satellite L850-CJK          | Notebook    | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| Lenovo        | Unknown                     | Notebook    | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| ECS           | A55F-M3                     | Desktop     | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| Google        | Akemi                       | Notebook    | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| MSI           | B460M PRO                   | Desktop     | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                     | Desktop     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Dell          | Latitude E7450              | Notebook    | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Dell          | Latitude 3190               | Notebook    | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| Sony          | SVT13115FBS                 | Notebook    | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| GreatWall     | U320                        | Desktop     | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                        | Desktop     | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [536f6d67e3](https://linux-hardware.org/?probe=536f6d67e3) | Oct 02, 2021 |
| Intel         | Unknown                     | Desktop     | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| GTZS          | Unknown                     | Notebook    | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| Pixus         | Rise                        | Notebook    | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | Notebook    | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [6949bed845](https://linux-hardware.org/?probe=6949bed845) | Aug 05, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [e94701caeb](https://linux-hardware.org/?probe=e94701caeb) | Aug 03, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| Acer          | Aspire E5-574G              | Notebook    | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| Dell          | Vostro 5515                 | Notebook    | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Medion        | P6669 MD60147               | Notebook    | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | Notebook    | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| Acer          | Extensa 5620                | Notebook    | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | Notebook    | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Intel         | ChiefRiver                  | Notebook    | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | Notebook    | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | Notebook    | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [dcc5bdef7d](https://linux-hardware.org/?probe=dcc5bdef7d) | Mar 12, 2021 |
| Dell          | Latitude E5470              | Notebook    | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | Notebook    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | Notebook    | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | Notebook    | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | Notebook    | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | Notebook    | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Medion        | E1235T MD99743              | Tablet      | [314aa4d200](https://linux-hardware.org/?probe=314aa4d200) | Feb 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | 15                          | Notebook    | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| Dell          | Latitude D430               | Notebook    | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| Dell          | Latitude E5520              | Notebook    | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | Notebook    | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | Notebook    | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [98c8e4f3a6](https://linux-hardware.org/?probe=98c8e4f3a6) | Dec 20, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
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
| 4.19.0-6-amd64             | 40        | 25.48%  |
| 5.6.0-2-amd64              | 11        | 7.01%   |
| 5.10.0-5mx-amd64           | 10        | 6.37%   |
| 4.19.0-13-amd64            | 9         | 5.73%   |
| 5.8.0-3-amd64              | 8         | 5.1%    |
| 4.19.0-14-amd64            | 8         | 5.1%    |
| 5.4.0-3-amd64              | 4         | 2.55%   |
| 4.19.0-18-amd64            | 4         | 2.55%   |
| 4.19.0-17-amd64            | 4         | 2.55%   |
| 5.8.16-antix.1-amd64-smp   | 3         | 1.91%   |
| 5.2.21-antix.2-amd64-smp   | 3         | 1.91%   |
| 5.10.0-8mx-amd64           | 3         | 1.91%   |
| 4.19.0-16-amd64            | 3         | 1.91%   |
| 4.19.0-12-amd64            | 3         | 1.91%   |
| 5.6.10-antix.1-amd64-smp   | 2         | 1.27%   |
| 5.10.0-9mx-amd64           | 2         | 1.27%   |
| 4.19.0-9-amd64             | 2         | 1.27%   |
| 4.19.0-8-amd64             | 2         | 1.27%   |
| 4.19.0-20-amd64            | 2         | 1.27%   |
| 5.9.1-rt20avl1             | 1         | 0.64%   |
| 5.7.0-19.1-liquorix-amd64  | 1         | 0.64%   |
| 5.6.10-antix.1-686-smp-pae | 1         | 0.64%   |
| 5.5.0-10.2-liquorix-amd64  | 1         | 0.64%   |
| 5.5.0-050500rc1-lowlatency | 1         | 0.64%   |
| 5.4.7-antix.1-amd64-smp    | 1         | 0.64%   |
| 5.4.10                     | 1         | 0.64%   |
| 5.4.0-antix.1-amd64-smp    | 1         | 0.64%   |
| 5.4.0-13.3-liquorix-amd64  | 1         | 0.64%   |
| 5.4.0-11.2-liquorix-amd64  | 1         | 0.64%   |
| 5.4.0-10.2-liquorix-amd64  | 1         | 0.64%   |
| 5.3.10-antix.1-amd64-smp   | 1         | 0.64%   |
| 5.3.0-2-amd64              | 1         | 0.64%   |
| 5.3.0-10.1-liquorix-amd64  | 1         | 0.64%   |
| 5.3.0-0.bpo.2-amd64        | 1         | 0.64%   |
| 5.2.21-antix.2-686-smp-pae | 1         | 0.64%   |
| 5.2.15-antix.1-amd64-smp   | 1         | 0.64%   |
| 5.2.0-21.2-liquorix-amd64  | 1         | 0.64%   |
| 5.15.0-1mx-amd64           | 1         | 0.64%   |
| 5.13.0-12.3-liquorix-amd64 | 1         | 0.64%   |
| 5.11.0-21.1-liquorix-amd64 | 1         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.19.0   | 76        | 50.67%  |
| 5.10.0   | 17        | 11.33%  |
| 5.6.0    | 11        | 7.33%   |
| 5.8.0    | 8         | 5.33%   |
| 5.4.0    | 8         | 5.33%   |
| 5.2.21   | 4         | 2.67%   |
| 5.8.16   | 3         | 2%      |
| 5.6.10   | 3         | 2%      |
| 5.3.0    | 3         | 2%      |
| 5.5.0    | 2         | 1.33%   |
| 5.9.1    | 1         | 0.67%   |
| 5.7.0    | 1         | 0.67%   |
| 5.4.7    | 1         | 0.67%   |
| 5.4.10   | 1         | 0.67%   |
| 5.3.10   | 1         | 0.67%   |
| 5.2.15   | 1         | 0.67%   |
| 5.2.0    | 1         | 0.67%   |
| 5.15.0   | 1         | 0.67%   |
| 5.13.0   | 1         | 0.67%   |
| 5.11.0   | 1         | 0.67%   |
| 5.10.1   | 1         | 0.67%   |
| 4.9.246  | 1         | 0.67%   |
| 4.9.193  | 1         | 0.67%   |
| 4.9.189  | 1         | 0.67%   |
| 4.19.174 | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 77        | 51.33%  |
| 5.10    | 18        | 12%     |
| 5.6     | 14        | 9.33%   |
| 5.8     | 11        | 7.33%   |
| 5.4     | 10        | 6.67%   |
| 5.2     | 6         | 4%      |
| 5.3     | 4         | 2.67%   |
| 4.9     | 3         | 2%      |
| 5.5     | 2         | 1.33%   |
| 5.9     | 1         | 0.67%   |
| 5.7     | 1         | 0.67%   |
| 5.15    | 1         | 0.67%   |
| 5.13    | 1         | 0.67%   |
| 5.11    | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 133       | 94.33%  |
| i686   | 8         | 5.67%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 108       | 76.06%  |
| KDE5            | 15        | 10.56%  |
| Unknown         | 5         | 3.52%   |
| MATE            | 3         | 2.11%   |
| Budgie          | 2         | 1.41%   |
| X-Cinnamon      | 1         | 0.7%    |
| LXQt            | 1         | 0.7%    |
| LXDE            | 1         | 0.7%    |
| KDE             | 1         | 0.7%    |
| i3              | 1         | 0.7%    |
| GNOME Flashback | 1         | 0.7%    |
| GNOME           | 1         | 0.7%    |
| fluxbox         | 1         | 0.7%    |
| Cinnamon        | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 141       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 118       | 83.1%   |
| SDDM    | 12        | 8.45%   |
| TDM     | 6         | 4.23%   |
| SLiM    | 6         | 4.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 47        | 31.33%  |
| Unknown | 31        | 20.67%  |
| en_GB   | 11        | 7.33%   |
| sk_SK   | 10        | 6.67%   |
| de_DE   | 10        | 6.67%   |
| pt_BR   | 6         | 4%      |
| ru_RU   | 5         | 3.33%   |
| pl_PL   | 5         | 3.33%   |
| it_IT   | 4         | 2.67%   |
| tr_TR   | 3         | 2%      |
| fr_FR   | 3         | 2%      |
| uk_UA   | 2         | 1.33%   |
| es_ES   | 2         | 1.33%   |
| en_IE   | 2         | 1.33%   |
| en_AU   | 2         | 1.33%   |
| zh_CN   | 1         | 0.67%   |
| nl_NL   | 1         | 0.67%   |
| hu_HU   | 1         | 0.67%   |
| fr_CH   | 1         | 0.67%   |
| fr_BE   | 1         | 0.67%   |
| es_MX   | 1         | 0.67%   |
| cs_CZ   | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 87        | 61.7%   |
| EFI  | 54        | 38.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 129       | 90.85%  |
| Overlay | 9         | 6.34%   |
| Btrfs   | 3         | 2.11%   |
| F2fs    | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 73        | 51.77%  |
| MBR     | 65        | 46.1%   |
| Unknown | 3         | 2.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 79.31%  |
| Yes       | 30        | 20.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 51.41%  |
| Yes       | 69        | 48.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 21        | 14.89%  |
| Hewlett-Packard     | 20        | 14.18%  |
| ASUSTek Computer    | 20        | 14.18%  |
| Lenovo              | 18        | 12.77%  |
| Acer                | 11        | 7.8%    |
| ASRock              | 7         | 4.96%   |
| MSI                 | 6         | 4.26%   |
| Intel               | 6         | 4.26%   |
| Gigabyte Technology | 6         | 4.26%   |
| Toshiba             | 5         | 3.55%   |
| Medion              | 3         | 2.13%   |
| Fujitsu Siemens     | 3         | 2.13%   |
| Sony                | 2         | 1.42%   |
| Samsung Electronics | 2         | 1.42%   |
| Google              | 2         | 1.42%   |
| ZOTAC               | 1         | 0.71%   |
| Radiant Systems     | 1         | 0.71%   |
| Pixus               | 1         | 0.71%   |
| Hometech            | 1         | 0.71%   |
| GreatWall           | 1         | 0.71%   |
| Gateway             | 1         | 0.71%   |
| eMachines           | 1         | 0.71%   |
| ECS                 | 1         | 0.71%   |
| Clevo               | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell Studio 540                          | 2         | 1.42%   |
| ASRock K8A780LM                          | 2         | 1.42%   |
| Unknown                                  | 2         | 1.42%   |
| ZOTAC ZBOX-BI320                         | 1         | 0.71%   |
| Toshiba Satellite P875                   | 1         | 0.71%   |
| Toshiba Satellite L850-CJK               | 1         | 0.71%   |
| Toshiba Satellite C50-A-12K              | 1         | 0.71%   |
| Toshiba Satellite A300                   | 1         | 0.71%   |
| Toshiba PORTEGE R705                     | 1         | 0.71%   |
| Sony VPCF23P1E                           | 1         | 0.71%   |
| Sony SVT13115FBS                         | 1         | 0.71%   |
| Samsung R780/R778                        | 1         | 0.71%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 0.71%   |
| Radiant Systems P845                     | 1         | 0.71%   |
| Pixus Rise                               | 1         | 0.71%   |
| MSI MS-N033                              | 1         | 0.71%   |
| MSI MS-7C88                              | 1         | 0.71%   |
| MSI MS-7C56                              | 1         | 0.71%   |
| MSI MS-7A34                              | 1         | 0.71%   |
| MSI MS-7693                              | 1         | 0.71%   |
| MSI GP63 Leopard 8RD                     | 1         | 0.71%   |
| Medion P6669 MD60147                     | 1         | 0.71%   |
| Medion E6234                             | 1         | 0.71%   |
| Medion E1235T MD99743                    | 1         | 0.71%   |
| Lenovo V145-15AST 81MT                   | 1         | 0.71%   |
| Lenovo ThinkPad X301 2776LBU             | 1         | 0.71%   |
| Lenovo ThinkPad X270 W10DG 20K5S0YT00    | 1         | 0.71%   |
| Lenovo ThinkPad X250 20CLS4YA00          | 1         | 0.71%   |
| Lenovo ThinkPad X220 4291WMQ             | 1         | 0.71%   |
| Lenovo ThinkPad X201 3680MY9             | 1         | 0.71%   |
| Lenovo ThinkPad X1C 5th W10DG 20K4S0EC00 | 1         | 0.71%   |
| Lenovo ThinkPad W510 4875W17             | 1         | 0.71%   |
| Lenovo ThinkPad T440p 20AWS2T11D         | 1         | 0.71%   |
| Lenovo ThinkPad T440p 20AWA1NAUK         | 1         | 0.71%   |
| Lenovo ThinkPad T420 4236TL7             | 1         | 0.71%   |
| Lenovo ThinkPad T420 4236MBU             | 1         | 0.71%   |
| Lenovo ThinkPad T410 2537G99             | 1         | 0.71%   |
| Lenovo ThinkPad L412 0585W28             | 1         | 0.71%   |
| Lenovo ThinkPad E490 20N9S26G00          | 1         | 0.71%   |
| Lenovo IdeaPadFlex 5 15ITL05 82HT        | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 14        | 9.93%   |
| Dell Latitude           | 7         | 4.96%   |
| Acer Aspire             | 6         | 4.26%   |
| Toshiba Satellite       | 4         | 2.84%   |
| HP Pavilion             | 4         | 2.84%   |
| Dell OptiPlex           | 4         | 2.84%   |
| Dell Inspiron           | 4         | 2.84%   |
| HP ProBook              | 3         | 2.13%   |
| ASUS TUF                | 3         | 2.13%   |
| ASUS PRIME              | 3         | 2.13%   |
| HP Spectre              | 2         | 1.42%   |
| HP EliteBook            | 2         | 1.42%   |
| Fujitsu Siemens ESPRIMO | 2         | 1.42%   |
| Dell Vostro             | 2         | 1.42%   |
| Dell Studio             | 2         | 1.42%   |
| ASRock K8A780LM         | 2         | 1.42%   |
| Acer Extensa            | 2         | 1.42%   |
| Unknown                 | 2         | 1.42%   |
| ZOTAC ZBOX-BI320        | 1         | 0.71%   |
| Toshiba PORTEGE         | 1         | 0.71%   |
| Sony VPCF23P1E          | 1         | 0.71%   |
| Sony SVT13115FBS        | 1         | 0.71%   |
| Samsung R780            | 1         | 0.71%   |
| Samsung 305E4A          | 1         | 0.71%   |
| Radiant Systems P845    | 1         | 0.71%   |
| Pixus Rise              | 1         | 0.71%   |
| MSI MS-N033             | 1         | 0.71%   |
| MSI MS-7C88             | 1         | 0.71%   |
| MSI MS-7C56             | 1         | 0.71%   |
| MSI MS-7A34             | 1         | 0.71%   |
| MSI MS-7693             | 1         | 0.71%   |
| MSI GP63                | 1         | 0.71%   |
| Medion P6669            | 1         | 0.71%   |
| Medion E6234            | 1         | 0.71%   |
| Medion E1235T           | 1         | 0.71%   |
| Lenovo V145-15AST       | 1         | 0.71%   |
| Lenovo IdeaPadFlex      | 1         | 0.71%   |
| Lenovo IdeaPad          | 1         | 0.71%   |
| Intel NUC8i7HVK         | 1         | 0.71%   |
| Intel MAHOBAY           | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 19        | 13.48%  |
| 2018 | 15        | 10.64%  |
| 2010 | 14        | 9.93%   |
| 2013 | 12        | 8.51%   |
| 2012 | 12        | 8.51%   |
| 2019 | 10        | 7.09%   |
| 2016 | 9         | 6.38%   |
| 2008 | 9         | 6.38%   |
| 2017 | 8         | 5.67%   |
| 2020 | 7         | 4.96%   |
| 2015 | 6         | 4.26%   |
| 2014 | 5         | 3.55%   |
| 2009 | 5         | 3.55%   |
| 2007 | 5         | 3.55%   |
| 2021 | 3         | 2.13%   |
| 2006 | 2         | 1.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 87        | 61.7%   |
| Desktop     | 44        | 31.21%  |
| Tablet      | 4         | 2.84%   |
| Mini pc     | 3         | 2.13%   |
| Convertible | 2         | 1.42%   |
| All in one  | 1         | 0.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 141       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 138       | 97.87%  |
| Yes  | 3         | 2.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 33        | 23.08%  |
| 4.01-8.0   | 28        | 19.58%  |
| 3.01-4.0   | 28        | 19.58%  |
| 16.01-24.0 | 26        | 18.18%  |
| 1.01-2.0   | 17        | 11.89%  |
| 32.01-64.0 | 6         | 4.2%    |
| 0.51-1.0   | 3         | 2.1%    |
| 2.01-3.0   | 2         | 1.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 57        | 37.75%  |
| 2.01-3.0  | 35        | 23.18%  |
| 0.51-1.0  | 24        | 15.89%  |
| 3.01-4.0  | 17        | 11.26%  |
| 4.01-8.0  | 13        | 8.61%   |
| 8.01-16.0 | 3         | 1.99%   |
| 0.01-0.5  | 2         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 87        | 60.42%  |
| 2      | 44        | 30.56%  |
| 3      | 4         | 2.78%   |
| 5      | 3         | 2.08%   |
| 4      | 3         | 2.08%   |
| 0      | 3         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 58.87%  |
| Yes       | 58        | 41.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 90.78%  |
| No        | 13        | 9.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 75.18%  |
| No        | 35        | 24.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 54.93%  |
| No        | 64        | 45.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 29        | 20.57%  |
| UK          | 12        | 8.51%   |
| Slovakia    | 12        | 8.51%   |
| Germany     | 8         | 5.67%   |
| Brazil      | 7         | 4.96%   |
| Poland      | 6         | 4.26%   |
| India       | 5         | 3.55%   |
| Austria     | 5         | 3.55%   |
| Ukraine     | 4         | 2.84%   |
| Spain       | 4         | 2.84%   |
| Russia      | 4         | 2.84%   |
| Italy       | 4         | 2.84%   |
| France      | 4         | 2.84%   |
| Canada      | 4         | 2.84%   |
| Turkey      | 3         | 2.13%   |
| Netherlands | 3         | 2.13%   |
| Australia   | 3         | 2.13%   |
| Thailand    | 2         | 1.42%   |
| Serbia      | 2         | 1.42%   |
| Mexico      | 2         | 1.42%   |
| China       | 2         | 1.42%   |
| Chile       | 2         | 1.42%   |
| Switzerland | 1         | 0.71%   |
| Sweden      | 1         | 0.71%   |
| Romania     | 1         | 0.71%   |
| Philippines | 1         | 0.71%   |
| Nigeria     | 1         | 0.71%   |
| Latvia      | 1         | 0.71%   |
| Ireland     | 1         | 0.71%   |
| Indonesia   | 1         | 0.71%   |
| Hungary     | 1         | 0.71%   |
| Greece      | 1         | 0.71%   |
| Denmark     | 1         | 0.71%   |
| Czechia     | 1         | 0.71%   |
| Belgium     | 1         | 0.71%   |
| Algeria     | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Bratislava                | 12        | 8.33%   |
| Vienna                    | 5         | 3.47%   |
| Warsaw                    | 3         | 2.08%   |
| Oxford                    | 3         | 2.08%   |
| Berlin                    | 3         | 2.08%   |
| Valencia                  | 2         | 1.39%   |
| Melbourne                 | 2         | 1.39%   |
| Los Angeles               | 2         | 1.39%   |
| Florianópolis            | 2         | 1.39%   |
| Dnipro                    | 2         | 1.39%   |
| Centreville               | 2         | 1.39%   |
| Calgary                   | 2         | 1.39%   |
| Bengaluru                 | 2         | 1.39%   |
| Belgrade                  | 2         | 1.39%   |
| Ankara                    | 2         | 1.39%   |
| Xalapa                    | 1         | 0.69%   |
| Williamsburg              | 1         | 0.69%   |
| Wentzville                | 1         | 0.69%   |
| Vitacura                  | 1         | 0.69%   |
| Virginia Beach            | 1         | 0.69%   |
| Tver                      | 1         | 0.69%   |
| Trzebinia                 | 1         | 0.69%   |
| Tilburg                   | 1         | 0.69%   |
| Sydney                    | 1         | 0.69%   |
| Suzhou                    | 1         | 0.69%   |
| St Petersburg             | 1         | 0.69%   |
| Springdale                | 1         | 0.69%   |
| Southsea                  | 1         | 0.69%   |
| Shenzhen                  | 1         | 0.69%   |
| Serrana                   | 1         | 0.69%   |
| Schiedam                  | 1         | 0.69%   |
| Santa Pola                | 1         | 0.69%   |
| San Giovanni in Persiceto | 1         | 0.69%   |
| Romulus                   | 1         | 0.69%   |
| Rome                      | 1         | 0.69%   |
| Rivne                     | 1         | 0.69%   |
| Riga                      | 1         | 0.69%   |
| Relizane                  | 1         | 0.69%   |
| Puerto Vallarta           | 1         | 0.69%   |
| Portsmouth                | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 29        | 38     | 14.5%   |
| WDC                       | 28        | 31     | 14%     |
| Samsung Electronics       | 16        | 20     | 8%      |
| Crucial                   | 16        | 22     | 8%      |
| Toshiba                   | 15        | 17     | 7.5%    |
| Kingston                  | 13        | 14     | 6.5%    |
| Unknown                   | 11        | 16     | 5.5%    |
| Hitachi                   | 11        | 14     | 5.5%    |
| SanDisk                   | 10        | 12     | 5%      |
| Intel                     | 7         | 10     | 3.5%    |
| HGST                      | 6         | 7      | 3%      |
| A-DATA Technology         | 4         | 4      | 2%      |
| SK hynix                  | 3         | 3      | 1.5%    |
| Micron Technology         | 3         | 4      | 1.5%    |
| GOODRAM                   | 3         | 4      | 1.5%    |
| PNY                       | 2         | 2      | 1%      |
| Mushkin                   | 2         | 2      | 1%      |
| KingSpec                  | 2         | 2      | 1%      |
| KingFast                  | 2         | 2      | 1%      |
| KingDian                  | 2         | 2      | 1%      |
| Corsair                   | 2         | 2      | 1%      |
| ZTC                       | 1         | 1      | 0.5%    |
| Transcend                 | 1         | 1      | 0.5%    |
| Team                      | 1         | 1      | 0.5%    |
| Smart                     | 1         | 1      | 0.5%    |
| Phison Electronics        | 1         | 2      | 0.5%    |
| Phison                    | 1         | 1      | 0.5%    |
| Patriot                   | 1         | 1      | 0.5%    |
| Micron/Crucial Technology | 1         | 1      | 0.5%    |
| LITEONIT                  | 1         | 1      | 0.5%    |
| Lexar                     | 1         | 1      | 0.5%    |
| Indilinx                  | 1         | 1      | 0.5%    |
| Fujitsu                   | 1         | 1      | 0.5%    |
| ASMT                      | 1         | 3      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SV300S37A120G 120GB SSD    | 4         | 1.89%   |
| Hitachi HTS543232A7A384 320GB       | 4         | 1.89%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 1.42%   |
| Seagate ST1000LM048-2E7172 1TB      | 3         | 1.42%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 1.42%   |
| Kingston SA400S37240G 240GB SSD     | 3         | 1.42%   |
| WDC WD30EZRX-00D8PB0 3TB            | 2         | 0.94%   |
| WDC WD15EARX-00PASB0 1TB            | 2         | 0.94%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 0.94%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.94%   |
| Toshiba MK5065GSX 500GB             | 2         | 0.94%   |
| Seagate ST4000DM004-2CV104 4TB      | 2         | 0.94%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.94%   |
| SanDisk SDSSDP128G 128GB            | 2         | 0.94%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2         | 0.94%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.94%   |
| Intel SSDSA2BW120G3H 120GB          | 2         | 0.94%   |
| Intel SSDPEKNW512G8 512GB           | 2         | 0.94%   |
| HGST HTS721010A9E630 1TB            | 2         | 0.94%   |
| HGST HTS541010A9E680 1TB            | 2         | 0.94%   |
| Crucial CT250MX500SSD1 250GB        | 2         | 0.94%   |
| Crucial CT120BX500SSD1 120GB        | 2         | 0.94%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.94%   |
| A-DATA SP600 32GB SSD               | 2         | 0.94%   |
| ZTC SM201-256G SSD                  | 1         | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 0.47%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 1         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.47%   |
| WDC WD80EZAZ-11TDBA0 8TB            | 1         | 0.47%   |
| WDC WD5003ABYX-01WERA1 500GB        | 1         | 0.47%   |
| WDC WD5000BPVT-60HXZT3 500GB        | 1         | 0.47%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 0.47%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.47%   |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 0.47%   |
| WDC WD2500JS-75NCB3 250GB           | 1         | 0.47%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 0.47%   |
| WDC WD2500AAJS-00L7A0 250GB         | 1         | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 0.47%   |
| WDC WD20EARX-00PASB0 2TB            | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 38     | 33.72%  |
| WDC                 | 23        | 26     | 26.74%  |
| Toshiba             | 12        | 14     | 13.95%  |
| Hitachi             | 11        | 14     | 12.79%  |
| HGST                | 6         | 7      | 6.98%   |
| Samsung Electronics | 3         | 5      | 3.49%   |
| Fujitsu             | 1         | 1      | 1.16%   |
| ASMT                | 1         | 3      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 15        | 16     | 18.52%  |
| Kingston            | 12        | 13     | 14.81%  |
| SanDisk             | 9         | 10     | 11.11%  |
| Samsung Electronics | 7         | 8      | 8.64%   |
| WDC                 | 4         | 4      | 4.94%   |
| Intel               | 4         | 6      | 4.94%   |
| A-DATA Technology   | 4         | 4      | 4.94%   |
| Micron Technology   | 3         | 4      | 3.7%    |
| GOODRAM             | 3         | 4      | 3.7%    |
| PNY                 | 2         | 2      | 2.47%   |
| KingSpec            | 2         | 2      | 2.47%   |
| KingFast            | 2         | 2      | 2.47%   |
| KingDian            | 2         | 2      | 2.47%   |
| ZTC                 | 1         | 1      | 1.23%   |
| Transcend           | 1         | 1      | 1.23%   |
| Toshiba             | 1         | 1      | 1.23%   |
| Team                | 1         | 1      | 1.23%   |
| Smart               | 1         | 1      | 1.23%   |
| SK hynix            | 1         | 1      | 1.23%   |
| Phison              | 1         | 1      | 1.23%   |
| Patriot             | 1         | 1      | 1.23%   |
| Mushkin             | 1         | 1      | 1.23%   |
| LITEONIT            | 1         | 1      | 1.23%   |
| Indilinx            | 1         | 1      | 1.23%   |
| Corsair             | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 72        | 89     | 41.14%  |
| HDD  | 72        | 108    | 41.14%  |
| NVMe | 19        | 28     | 10.86%  |
| MMC  | 12        | 19     | 6.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 115       | 194    | 78.23%  |
| NVMe | 19        | 28     | 12.93%  |
| MMC  | 12        | 19     | 8.16%   |
| SAS  | 1         | 3      | 0.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 93        | 127    | 62.42%  |
| 0.51-1.0   | 42        | 55     | 28.19%  |
| 1.01-2.0   | 6         | 7      | 4.03%   |
| 2.01-3.0   | 4         | 4      | 2.68%   |
| 3.01-4.0   | 2         | 2      | 1.34%   |
| 4.01-10.0  | 2         | 2      | 1.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 28%     |
| 501-1000       | 23        | 15.33%  |
| 51-100         | 22        | 14.67%  |
| 251-500        | 20        | 13.33%  |
| 21-50          | 14        | 9.33%   |
| 1001-2000      | 12        | 8%      |
| 1-20           | 6         | 4%      |
| More than 3000 | 5         | 3.33%   |
| 2001-3000      | 4         | 2.67%   |
| Unknown        | 2         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 63        | 42.28%  |
| 21-50          | 19        | 12.75%  |
| 101-250        | 19        | 12.75%  |
| 251-500        | 15        | 10.07%  |
| 51-100         | 14        | 9.4%    |
| 501-1000       | 10        | 6.71%   |
| 1001-2000      | 4         | 2.68%   |
| 2001-3000      | 2         | 1.34%   |
| Unknown        | 2         | 1.34%   |
| More than 3000 | 1         | 0.67%   |

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
| Samsung Electronics HD322GJ 320GB   | 1         | 2      | 2.86%   |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 2.86%   |
| Indilinx IND-S325S120G 120GB SSD    | 1         | 1      | 2.86%   |
| Hitachi HUA722020ALA331 2TB         | 1         | 1      | 2.86%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 2.86%   |
| Hitachi HTS543232A7A384 320GB       | 1         | 1      | 2.86%   |
| Hitachi HDT721010SLA360 1TB         | 1         | 1      | 2.86%   |
| Hitachi HDP725016GLA380 160GB       | 1         | 1      | 2.86%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 2.86%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 2.86%   |
| Fujitsu MHV2060BH PL 64GB           | 1         | 1      | 2.86%   |
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
| Samsung Electronics | 2         | 4      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| SanDisk             | 1         | 1      | 2.94%   |
| Kingston            | 1         | 1      | 2.94%   |
| Indilinx            | 1         | 1      | 2.94%   |
| Fujitsu             | 1         | 1      | 2.94%   |
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
| Samsung Electronics | 2         | 4      | 7.69%   |
| HGST                | 2         | 2      | 7.69%   |
| Fujitsu             | 1         | 1      | 3.85%   |

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
| Works    | 107       | 169    | 67.3%   |
| Malfunc  | 30        | 43     | 18.87%  |
| Detected | 19        | 28     | 11.95%  |
| Failed   | 3         | 4      | 1.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 96        | 64%     |
| AMD                          | 27        | 18%     |
| Samsung Electronics          | 6         | 4%      |
| Nvidia                       | 4         | 2.67%   |
| Silicon Motion               | 2         | 1.33%   |
| Phison Electronics           | 2         | 1.33%   |
| Micron/Crucial Technology    | 2         | 1.33%   |
| Marvell Technology Group     | 2         | 1.33%   |
| JMicron Technology           | 2         | 1.33%   |
| ASMedia Technology           | 2         | 1.33%   |
| Toshiba America Info Systems | 1         | 0.67%   |
| SK hynix                     | 1         | 0.67%   |
| SanDisk                      | 1         | 0.67%   |
| KIOXIA                       | 1         | 0.67%   |
| Kingston Technology Company  | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 8.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 5.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 5.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 4.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 3.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 3.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 3.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 2.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.21%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 2.21%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 3         | 1.66%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 3         | 1.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.66%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.1%    |
| Phison E12 NVMe Controller                                                     | 2         | 1.1%    |
| Intel SSD 660P Series                                                          | 2         | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.1%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.1%    |
| Intel 4 Series Chipset PT IDER Controller                                      | 2         | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.55%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.55%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.55%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 0.55%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.55%   |
| Nvidia MCP61 IDE                                                               | 1         | 0.55%   |
| Nvidia MCP55 SATA Controller                                                   | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 101       | 62.73%  |
| IDE  | 28        | 17.39%  |
| NVMe | 19        | 11.8%   |
| RAID | 13        | 8.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 111       | 78.72%  |
| AMD    | 30        | 21.28%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 2.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 2.84%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3         | 2.13%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2         | 1.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.42%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 2         | 1.42%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 1.42%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.42%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.42%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2         | 1.42%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.42%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 2         | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.42%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.42%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.71%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.71%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.71%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.71%   |
| Intel Core i7-8809G CPU @ 3.10GHz           | 1         | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.71%   |
| Intel Core i7-7560U CPU @ 2.40GHz           | 1         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1         | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.71%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.71%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.71%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.71%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 23.4%   |
| Intel Core i7           | 28        | 19.86%  |
| Intel Celeron           | 10        | 7.09%   |
| Intel Atom              | 10        | 7.09%   |
| Intel Core i3           | 7         | 4.96%   |
| Intel Core 2 Duo        | 6         | 4.26%   |
| AMD Ryzen 7             | 5         | 3.55%   |
| AMD Ryzen 5             | 5         | 3.55%   |
| Intel Pentium           | 4         | 2.84%   |
| Intel Core 2 Quad       | 3         | 2.13%   |
| AMD A6                  | 3         | 2.13%   |
| Other                   | 2         | 1.42%   |
| Intel Pentium Dual-Core | 2         | 1.42%   |
| AMD Turion 64 X2 Mobile | 2         | 1.42%   |
| AMD Sempron             | 2         | 1.42%   |
| AMD Phenom II X4        | 2         | 1.42%   |
| AMD E1                  | 2         | 1.42%   |
| AMD Athlon II X2        | 2         | 1.42%   |
| Intel Pentium Silver    | 1         | 0.71%   |
| Intel Pentium Gold      | 1         | 0.71%   |
| Intel Core 2 Extreme    | 1         | 0.71%   |
| Intel Core 2            | 1         | 0.71%   |
| Intel Celeron M         | 1         | 0.71%   |
| Intel Celeron D         | 1         | 0.71%   |
| AMD Phenom II X6        | 1         | 0.71%   |
| AMD E                   | 1         | 0.71%   |
| AMD Athlon X4           | 1         | 0.71%   |
| AMD Athlon 64 X2        | 1         | 0.71%   |
| AMD Athlon              | 1         | 0.71%   |
| AMD A8                  | 1         | 0.71%   |
| AMD A4                  | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 78        | 55.32%  |
| 4      | 43        | 30.5%   |
| 6      | 7         | 4.96%   |
| 1      | 7         | 4.96%   |
| 8      | 6         | 4.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 141       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 79        | 56.03%  |
| 1      | 62        | 43.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 137       | 97.16%  |
| 32-bit         | 4         | 2.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 13.29%  |
| 0x206a7    | 12        | 8.39%   |
| 0x306a9    | 9         | 6.29%   |
| 0x306c3    | 8         | 5.59%   |
| 0x406e3    | 7         | 4.9%    |
| 0x20655    | 5         | 3.5%    |
| 0x20652    | 4         | 2.8%    |
| 0x906e9    | 3         | 2.1%    |
| 0x806ec    | 3         | 2.1%    |
| 0x806e9    | 3         | 2.1%    |
| 0x406c4    | 3         | 2.1%    |
| 0x40651    | 3         | 2.1%    |
| 0x30678    | 3         | 2.1%    |
| 0x30661    | 3         | 2.1%    |
| 0x1067a    | 3         | 2.1%    |
| 0x03000027 | 3         | 2.1%    |
| 0x906ea    | 2         | 1.4%    |
| 0x806c1    | 2         | 1.4%    |
| 0x6fd      | 2         | 1.4%    |
| 0x406c3    | 2         | 1.4%    |
| 0x306d4    | 2         | 1.4%    |
| 0x106ca    | 2         | 1.4%    |
| 0x10677    | 2         | 1.4%    |
| 0x10676    | 2         | 1.4%    |
| 0x08701021 | 2         | 1.4%    |
| 0x0800820d | 2         | 1.4%    |
| 0x0700010f | 2         | 1.4%    |
| 0x010000c8 | 2         | 1.4%    |
| 0xf65      | 1         | 0.7%    |
| 0xa0653    | 1         | 0.7%    |
| 0x906ed    | 1         | 0.7%    |
| 0x906eb    | 1         | 0.7%    |
| 0x806ea    | 1         | 0.7%    |
| 0x706e5    | 1         | 0.7%    |
| 0x706a1    | 1         | 0.7%    |
| 0x6fb      | 1         | 0.7%    |
| 0x6f2      | 1         | 0.7%    |
| 0x6d8      | 1         | 0.7%    |
| 0x506e3    | 1         | 0.7%    |
| 0x506c9    | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 16        | 11.35%  |
| KabyLake      | 16        | 11.35%  |
| IvyBridge     | 12        | 8.51%   |
| Haswell       | 11        | 7.8%    |
| Westmere      | 9         | 6.38%   |
| Silvermont    | 9         | 6.38%   |
| Penryn        | 9         | 6.38%   |
| Skylake       | 8         | 5.67%   |
| K10           | 6         | 4.26%   |
| Bonnell       | 6         | 4.26%   |
| K8 Hammer     | 5         | 3.55%   |
| Zen           | 4         | 2.84%   |
| Core          | 4         | 2.84%   |
| Zen 2         | 3         | 2.13%   |
| K10 Llano     | 3         | 2.13%   |
| Zen+          | 2         | 1.42%   |
| TigerLake     | 2         | 1.42%   |
| Jaguar        | 2         | 1.42%   |
| Excavator     | 2         | 1.42%   |
| Broadwell     | 2         | 1.42%   |
| Puma          | 1         | 0.71%   |
| P6            | 1         | 0.71%   |
| NetBurst      | 1         | 0.71%   |
| Nehalem       | 1         | 0.71%   |
| IceLake       | 1         | 0.71%   |
| Goldmont plus | 1         | 0.71%   |
| Goldmont      | 1         | 0.71%   |
| CometLake     | 1         | 0.71%   |
| Bobcat        | 1         | 0.71%   |
| Unknown       | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 88        | 53.99%  |
| Nvidia | 38        | 23.31%  |
| AMD    | 37        | 22.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 7.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 4.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.89%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.73%   |
| Intel HD Graphics 630                                                                    | 3         | 1.73%   |
| Intel HD Graphics 620                                                                    | 3         | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.73%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 1.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.73%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.73%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.16%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 1.16%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.16%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.16%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.16%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 1.16%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 1.16%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                                | 2         | 1.16%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 2         | 1.16%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 1.16%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.58%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.58%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.58%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 0.58%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.58%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.58%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 69        | 47.92%  |
| 1 x AMD        | 29        | 20.14%  |
| 1 x Nvidia     | 25        | 17.36%  |
| Intel + Nvidia | 12        | 8.33%   |
| Intel + AMD    | 4         | 2.78%   |
| 2 x AMD        | 3         | 2.08%   |
| 3 x AMD        | 1         | 0.69%   |
| AMD + Nvidia   | 1         | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 124       | 87.32%  |
| Proprietary | 15        | 10.56%  |
| Unknown     | 3         | 2.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 60%     |
| 0.01-0.5   | 19        | 13.1%   |
| 1.01-2.0   | 16        | 11.03%  |
| 0.51-1.0   | 14        | 9.66%   |
| 3.01-4.0   | 4         | 2.76%   |
| 7.01-8.0   | 3         | 2.07%   |
| 5.01-6.0   | 1         | 0.69%   |
| 2.01-3.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 24        | 16.33%  |
| AU Optronics            | 24        | 16.33%  |
| LG Display              | 15        | 10.2%   |
| Chimei Innolux          | 14        | 9.52%   |
| Goldstar                | 11        | 7.48%   |
| Dell                    | 8         | 5.44%   |
| BOE                     | 6         | 4.08%   |
| Lenovo                  | 5         | 3.4%    |
| Acer                    | 5         | 3.4%    |
| ViewSonic               | 3         | 2.04%   |
| Chi Mei Optoelectronics | 3         | 2.04%   |
| Ancor Communications    | 3         | 2.04%   |
| Philips                 | 2         | 1.36%   |
| LG Philips              | 2         | 1.36%   |
| InfoVision              | 2         | 1.36%   |
| Hewlett-Packard         | 2         | 1.36%   |
| HannStar                | 2         | 1.36%   |
| BenQ                    | 2         | 1.36%   |
| AOC                     | 2         | 1.36%   |
| Vizio                   | 1         | 0.68%   |
| Vestel Elektronik       | 1         | 0.68%   |
| SANYO                   | 1         | 0.68%   |
| PANDA                   | 1         | 0.68%   |
| MSI                     | 1         | 0.68%   |
| InnoLux Display         | 1         | 0.68%   |
| IBM                     | 1         | 0.68%   |
| HYO                     | 1         | 0.68%   |
| Eizo                    | 1         | 0.68%   |
| DTV                     | 1         | 0.68%   |
| CPT                     | 1         | 0.68%   |
| CHR                     | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6         | 4.05%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 1.35%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                   | 2         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch        | 2         | 1.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch         | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch           | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch           | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch           | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch           | 2         | 1.35%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                       | 1         | 0.68%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.68%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1         | 0.68%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch              | 1         | 0.68%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch    | 1         | 0.68%   |
| SANYO Casper SAN2213 1600x900 304x228mm 15.0-inch                       | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch    | 1         | 0.68%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.68%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 0.68%   |
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch   | 1         | 0.68%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1         | 0.68%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.68%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 1         | 0.68%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 1         | 0.68%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 1         | 0.68%   |
| MSI MAG271C MSI3FA6 1920x1080 600x340mm 27.2-inch                       | 1         | 0.68%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch             | 1         | 0.68%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 57        | 39.31%  |
| 1366x768 (WXGA)    | 36        | 24.83%  |
| 1600x900 (HD+)     | 11        | 7.59%   |
| 1600x1200          | 7         | 4.83%   |
| 3840x2160 (4K)     | 6         | 4.14%   |
| 1280x800 (WXGA)    | 6         | 4.14%   |
| 2560x1440 (QHD)    | 4         | 2.76%   |
| 1440x900 (WXGA+)   | 4         | 2.76%   |
| 1280x1024 (SXGA)   | 4         | 2.76%   |
| 1024x600           | 4         | 2.76%   |
| 1680x1050 (WSXGA+) | 3         | 2.07%   |
| 1920x1200 (WUXGA)  | 2         | 1.38%   |
| 3000x2000          | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 38        | 25.68%  |
| 14     | 14        | 9.46%   |
| 13     | 13        | 8.78%   |
| 21     | 12        | 8.11%   |
| 24     | 10        | 6.76%   |
| 23     | 7         | 4.73%   |
| 19     | 7         | 4.73%   |
| 18     | 6         | 4.05%   |
| 27     | 5         | 3.38%   |
| 17     | 5         | 3.38%   |
| 12     | 5         | 3.38%   |
| 20     | 4         | 2.7%    |
| 11     | 4         | 2.7%    |
| 10     | 4         | 2.7%    |
| 31     | 3         | 2.03%   |
| 84     | 2         | 1.35%   |
| 65     | 2         | 1.35%   |
| 42     | 1         | 0.68%   |
| 39     | 1         | 0.68%   |
| 37     | 1         | 0.68%   |
| 32     | 1         | 0.68%   |
| 26     | 1         | 0.68%   |
| 22     | 1         | 0.68%   |
| 16     | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 39.04%  |
| 401-500     | 25        | 17.12%  |
| 501-600     | 22        | 15.07%  |
| 201-300     | 18        | 12.33%  |
| 351-400     | 13        | 8.9%    |
| 601-700     | 3         | 2.05%   |
| 801-900     | 2         | 1.37%   |
| 1501-2000   | 2         | 1.37%   |
| 1001-1500   | 2         | 1.37%   |
| 701-800     | 1         | 0.68%   |
| 901-1000    | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 110       | 80.29%  |
| 16/10 | 15        | 10.95%  |
| 4/3   | 6         | 4.38%   |
| 5/4   | 4         | 2.92%   |
| 3/2   | 2         | 1.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 26.03%  |
| 201-250        | 27        | 18.49%  |
| 81-90          | 22        | 15.07%  |
| 151-200        | 11        | 7.53%   |
| 71-80          | 5         | 3.42%   |
| 61-70          | 5         | 3.42%   |
| 301-350        | 5         | 3.42%   |
| 141-150        | 5         | 3.42%   |
| More than 1000 | 4         | 2.74%   |
| 51-60          | 4         | 2.74%   |
| 351-500        | 4         | 2.74%   |
| 41-50          | 4         | 2.74%   |
| 121-130        | 4         | 2.74%   |
| 251-300        | 3         | 2.05%   |
| 501-1000       | 3         | 2.05%   |
| 131-140        | 1         | 0.68%   |
| 111-120        | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 56        | 39.44%  |
| 101-120       | 45        | 31.69%  |
| 121-160       | 33        | 23.24%  |
| More than 240 | 3         | 2.11%   |
| 161-240       | 3         | 2.11%   |
| 1-50          | 2         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 124       | 86.71%  |
| 2     | 18        | 12.59%  |
| 0     | 1         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 35.29%  |
| Intel                    | 67        | 32.84%  |
| Qualcomm Atheros         | 30        | 14.71%  |
| Broadcom                 | 13        | 6.37%   |
| Ralink                   | 5         | 2.45%   |
| Nvidia                   | 3         | 1.47%   |
| Marvell Technology Group | 2         | 0.98%   |
| Huawei Technologies      | 2         | 0.98%   |
| Attansic Technology      | 2         | 0.98%   |
| ASIX Electronics         | 2         | 0.98%   |
| Ralink Technology        | 1         | 0.49%   |
| MediaTek                 | 1         | 0.49%   |
| JMicron Technology       | 1         | 0.49%   |
| D-Link System            | 1         | 0.49%   |
| Broadcom Limited         | 1         | 0.49%   |
| ASUSTek Computer         | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 21.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 3.27%   |
| Intel Wireless 7260                                               | 6         | 2.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.45%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.63%   |
| Intel Wireless 7265                                               | 4         | 1.63%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.22%   |
| Intel Wireless 8260                                               | 3         | 1.22%   |
| Intel Wireless 3165                                               | 3         | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.22%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.82%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.82%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.82%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 2         | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 55        | 50.46%  |
| Qualcomm Atheros      | 23        | 21.1%   |
| Realtek Semiconductor | 16        | 14.68%  |
| Broadcom              | 8         | 7.34%   |
| Ralink                | 5         | 4.59%   |
| Ralink Technology     | 1         | 0.92%   |
| ASUSTek Computer      | 1         | 0.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 8         | 7.27%   |
| Intel Wireless 7260                                                                           | 6         | 5.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 6         | 5.45%   |
| Intel Wireless 8265 / 8275                                                                    | 5         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 3.64%   |
| Intel Wireless 7265                                                                           | 4         | 3.64%   |
| Intel Centrino Advanced-N 6200                                                                | 4         | 3.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 2.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 2.73%   |
| Intel Wireless 8260                                                                           | 3         | 2.73%   |
| Intel Wireless 3165                                                                           | 3         | 2.73%   |
| Intel Centrino Wireless-N 2230                                                                | 3         | 2.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 1.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 1.82%   |
| Intel Wi-Fi 6 AX201                                                                           | 2         | 1.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 2         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 1.82%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 1.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.91%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.91%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.91%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.91%   |
| Realtek 802.11ac NIC                                                                          | 1         | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.91%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1         | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.91%   |
| Ralink RT2800 802.11n PCI                                                                     | 1         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.91%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1         | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 67        | 50.76%  |
| Intel                    | 34        | 25.76%  |
| Qualcomm Atheros         | 11        | 8.33%   |
| Broadcom                 | 6         | 4.55%   |
| Nvidia                   | 3         | 2.27%   |
| Marvell Technology Group | 2         | 1.52%   |
| Attansic Technology      | 2         | 1.52%   |
| ASIX Electronics         | 2         | 1.52%   |
| MediaTek                 | 1         | 0.76%   |
| JMicron Technology       | 1         | 0.76%   |
| Huawei Technologies      | 1         | 0.76%   |
| D-Link System            | 1         | 0.76%   |
| Broadcom Limited         | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 53        | 39.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 8.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 4.48%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 3.73%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.24%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 2.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.49%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.49%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 1.49%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.75%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.75%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.75%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.75%   |
| MediaTek TECNO CAMON 18P                                                       | 1         | 0.75%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.75%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.75%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.75%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.75%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.75%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.75%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.75%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                             | 1         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.75%   |
| Huawei STK-L21                                                                 | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 128       | 54.47%  |
| WiFi     | 106       | 45.11%  |
| Modem    | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 87        | 60%     |
| Ethernet | 58        | 40%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 87        | 61.7%   |
| 1     | 49        | 34.75%  |
| 0     | 3         | 2.13%   |
| 3     | 2         | 1.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 131       | 92.25%  |
| Yes  | 11        | 7.75%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 41.98%  |
| Broadcom                        | 10        | 12.35%  |
| Realtek Semiconductor           | 8         | 9.88%   |
| Qualcomm Atheros Communications | 6         | 7.41%   |
| Cambridge Silicon Radio         | 6         | 7.41%   |
| IMC Networks                    | 4         | 4.94%   |
| Lite-On Technology              | 3         | 3.7%    |
| Hewlett-Packard                 | 3         | 3.7%    |
| Toshiba                         | 2         | 2.47%   |
| Dell                            | 2         | 2.47%   |
| Ralink                          | 1         | 1.23%   |
| Foxconn / Hon Hai               | 1         | 1.23%   |
| ASUSTek Computer                | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 24.69%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 7.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.94%   |
| Intel AX201 Bluetooth                               | 4         | 4.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 4.94%   |
| Realtek Bluetooth Radio                             | 3         | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 3.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.47%   |
| Qualcomm Atheros Bluetooth                          | 2         | 2.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.47%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.47%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 1.23%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 1.23%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.23%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.23%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.23%   |
| Intel AX210 Bluetooth                               | 1         | 1.23%   |
| Intel AX200 Bluetooth                               | 1         | 1.23%   |
| IMC Networks Bluetooth Device                       | 1         | 1.23%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.23%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.23%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.23%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.23%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.23%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.23%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.23%   |
| ASUS BCM20702A0                                     | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 105       | 57.07%  |
| AMD                 | 39        | 21.2%   |
| Nvidia              | 29        | 15.76%  |
| Creative Labs       | 4         | 2.17%   |
| C-Media Electronics | 3         | 1.63%   |
| Tenx Technology     | 1         | 0.54%   |
| Logitech            | 1         | 0.54%   |
| JMTek               | 1         | 0.54%   |
| GN Netcom           | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 6.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 6.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 5.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 4.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 4.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 3.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.3%    |
| AMD FCH Azalia Controller                                                                         | 6         | 2.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 2.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.89%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.89%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.42%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.42%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.42%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 3         | 1.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.42%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.42%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.42%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.94%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.94%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.94%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.94%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.94%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 2         | 0.94%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.94%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 2         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 19.39%  |
| Unknown             | 29        | 17.58%  |
| SK hynix            | 29        | 17.58%  |
| Kingston            | 19        | 11.52%  |
| Micron Technology   | 15        | 9.09%   |
| Corsair             | 8         | 4.85%   |
| Crucial             | 4         | 2.42%   |
| Patriot             | 3         | 1.82%   |
| G.Skill             | 3         | 1.82%   |
| Elpida              | 3         | 1.82%   |
| A-DATA Technology   | 3         | 1.82%   |
| Unknown (ABCD)      | 2         | 1.21%   |
| Smart               | 2         | 1.21%   |
| Ramaxel Technology  | 2         | 1.21%   |
| Apacer              | 2         | 1.21%   |
| Unknown (F301)      | 1         | 0.61%   |
| TRS STAR            | 1         | 0.61%   |
| Teikon              | 1         | 0.61%   |
| Team                | 1         | 0.61%   |
| RZX                 | 1         | 0.61%   |
| OCZ                 | 1         | 0.61%   |
| High Bridge         | 1         | 0.61%   |
| Axiom               | 1         | 0.61%   |
| Unknown             | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s   | 4         | 2.2%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 3         | 1.65%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s | 3         | 1.65%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s    | 3         | 1.65%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s           | 2         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR2                    | 2         | 1.1%    |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s               | 2         | 1.1%    |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s    | 2         | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.1%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s   | 2         | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 2         | 1.1%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s   | 2         | 1.1%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 2         | 1.1%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s    | 2         | 1.1%    |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s    | 2         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 1.1%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s    | 2         | 1.1%    |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s    | 2         | 1.1%    |
| Apacer RAM 76.A302G.C4D0B 2048MB SODIMM DDR3 1600MT/s    | 2         | 1.1%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.55%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                | 1         | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s              | 1         | 0.55%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1         | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                 | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3                    | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DRAM                       | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1         | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s           | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR3                    | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                 | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 1         | 0.55%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DRAM                    | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DDR                     | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 70        | 48.95%  |
| DDR4    | 36        | 25.17%  |
| DDR2    | 15        | 10.49%  |
| Unknown | 6         | 4.2%    |
| SDRAM   | 5         | 3.5%    |
| DDR     | 4         | 2.8%    |
| LPDDR4  | 3         | 2.1%    |
| LPDDR3  | 2         | 1.4%    |
| DRAM    | 2         | 1.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 93        | 66.43%  |
| DIMM         | 43        | 30.71%  |
| Row Of Chips | 2         | 1.43%   |
| Chip         | 1         | 0.71%   |
| Unknown      | 1         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 62        | 39.49%  |
| 8192  | 38        | 24.2%   |
| 2048  | 34        | 21.66%  |
| 16384 | 13        | 8.28%   |
| 1024  | 8         | 5.1%    |
| 32768 | 1         | 0.64%   |
| 512   | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 27.88%  |
| 1333    | 17        | 10.3%   |
| 2667    | 15        | 9.09%   |
| 1334    | 13        | 7.88%   |
| 2400    | 11        | 6.67%   |
| 800     | 7         | 4.24%   |
| 667     | 7         | 4.24%   |
| Unknown | 7         | 4.24%   |
| 3200    | 5         | 3.03%   |
| 2133    | 5         | 3.03%   |
| 1867    | 4         | 2.42%   |
| 3466    | 3         | 1.82%   |
| 3000    | 3         | 1.82%   |
| 1067    | 3         | 1.82%   |
| 49926   | 2         | 1.21%   |
| 4199    | 2         | 1.21%   |
| 3266    | 2         | 1.21%   |
| 533     | 2         | 1.21%   |
| 333     | 2         | 1.21%   |
| 8400    | 1         | 0.61%   |
| 4267    | 1         | 0.61%   |
| 3600    | 1         | 0.61%   |
| 2666    | 1         | 0.61%   |
| 2048    | 1         | 0.61%   |
| 1639    | 1         | 0.61%   |
| 666     | 1         | 0.61%   |
| 400     | 1         | 0.61%   |
| 200     | 1         | 0.61%   |

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
| Chicony Electronics                    | 18        | 20.93%  |
| Realtek Semiconductor                  | 9         | 10.47%  |
| Microdia                               | 6         | 6.98%   |
| Logitech                               | 6         | 6.98%   |
| Acer                                   | 6         | 6.98%   |
| Sunplus Innovation Technology          | 5         | 5.81%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.81%   |
| Suyin                                  | 4         | 4.65%   |
| Quanta                                 | 3         | 3.49%   |
| Lite-On Technology                     | 3         | 3.49%   |
| Lenovo                                 | 3         | 3.49%   |
| IMC Networks                           | 3         | 3.49%   |
| Z-Star Microelectronics                | 2         | 2.33%   |
| Syntek                                 | 2         | 2.33%   |
| Xiongmai                               | 1         | 1.16%   |
| WaveRider Communications               | 1         | 1.16%   |
| Silicon Motion                         | 1         | 1.16%   |
| Samsung Electronics                    | 1         | 1.16%   |
| Ricoh                                  | 1         | 1.16%   |
| Microsoft                              | 1         | 1.16%   |
| Importek                               | 1         | 1.16%   |
| Huawei Technologies                    | 1         | 1.16%   |
| Generalplus Technology                 | 1         | 1.16%   |
| Cubeternet                             | 1         | 1.16%   |
| Alcor Micro                            | 1         | 1.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                   | 5         | 5.81%   |
| Realtek Integrated_Webcam_HD                                | 4         | 4.65%   |
| Syntek EasyCamera                                           | 2         | 2.33%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 2.33%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 2.33%   |
| Microdia USB 2.0 Camera                                     | 2         | 2.33%   |
| Microdia Integrated Webcam                                  | 2         | 2.33%   |
| Logitech Webcam C200                                        | 2         | 2.33%   |
| Lite-On Integrated Camera                                   | 2         | 2.33%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 2.33%   |
| Chicony USB 2.0 Camera                                      | 2         | 2.33%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 2.33%   |
| Chicony HP Truevision HD camera                             | 2         | 2.33%   |
| Chicony HD WebCam                                           | 2         | 2.33%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 1.16%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 1.16%   |
| Xiongmai web camera                                         | 1         | 1.16%   |
| WaveRider USB 2.0 Camera                                    | 1         | 1.16%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.16%   |
| Suyin 1.3M HD WebCam                                        | 1         | 1.16%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.16%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.16%   |
| Sunplus Integrated Webcam                                   | 1         | 1.16%   |
| Sunplus HD WebCam                                           | 1         | 1.16%   |
| Sunplus Asus Webcam                                         | 1         | 1.16%   |
| Silicon Motion Silicon Motion Camera                        | 1         | 1.16%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 1.16%   |
| Ricoh USB2.0 Camera                                         | 1         | 1.16%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 1.16%   |
| Realtek Integrated Webcam                                   | 1         | 1.16%   |
| Realtek HD Webcam - Realtek                                 | 1         | 1.16%   |
| Quanta USB2.0 HD UVC WebCam                                 | 1         | 1.16%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.16%   |
| Quanta HP 2.0MP High Definition Webcam                      | 1         | 1.16%   |
| Microsoft LifeCam HD-3000                                   | 1         | 1.16%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 1.16%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.16%   |
| Logitech Webcam Pro 9000                                    | 1         | 1.16%   |
| Logitech Webcam C270                                        | 1         | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 41.18%  |
| Upek                  | 4         | 23.53%  |
| Synaptics             | 2         | 11.76%  |
| LighTuning Technology | 2         | 11.76%  |
| Elan Microelectronics | 1         | 5.88%   |
| AuthenTec             | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 17.65%  |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 11.76%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.88%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                        | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.88%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 5.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5.88%   |
| LighTuning Fingerprint Reader                          | 1         | 5.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.88%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.88%   |
| AuthenTec AES2810                                      | 1         | 5.88%   |
| Unknown                                                | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 42.86%  |
| Broadcom    | 2         | 28.57%  |
| O2 Micro    | 1         | 14.29%  |
| Lenovo      | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 99        | 69.72%  |
| 1     | 32        | 22.54%  |
| 2     | 8         | 5.63%   |
| 3     | 3         | 2.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 33.93%  |
| Fingerprint reader       | 17        | 30.36%  |
| Chipcard                 | 6         | 10.71%  |
| Storage                  | 3         | 5.36%   |
| Net/wireless             | 3         | 5.36%   |
| Multimedia controller    | 3         | 5.36%   |
| Communication controller | 3         | 5.36%   |
| Camera                   | 1         | 1.79%   |
| Bluetooth                | 1         | 1.79%   |


Linux in Ireland - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

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

Total: 378

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Timi          | TM1709                      | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| HP            | Pavilion m6                 | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| HP            | Pavilion g6                 | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| HP            | EliteBook 755 G5            | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Samsung       | 935XDB                      | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Samsung       | 935XDB                      | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Jumper        | EZbook                      | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| HP            | EliteBook 840 G1            | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | Stealth GS66 12UGS          | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| Dell          | Latitude E6520              | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| Packard Be... | EasyNote TK85               | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Dell          | Latitude E5440              | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| Dell          | Latitude E6430              | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| PC Special... | NH5xAx                      | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| Dell          | Latitude 9420               | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | XPS 13 9310                 | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Toshiba       | PORTEGE R830                | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291W99       | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Acer          | AOD255                      | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Dell          | Inspiron MM061              | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Dell          | XPS 13 9310                 | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Toshiba       | PORTEGE R830                | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Acer          | Nitro AN515-45              | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| Apple         | MacBookPro5,3               | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Sony          | VPCCB35FG                   | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Dell          | Studio XPS 1640             | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| Dell          | Latitude 7370               | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| Entroware     | Apollo                      | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Dell          | Inspiron 1525               | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| Dell          | XPS 13 9300                 | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | Inspiron 1764               | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| HP            | Pavilion 15                 | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 15                          | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Entroware     | Proteus                     | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| HP            | HDX 18                      | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| HP            | EliteBook Folio G1          | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Acer          | Aspire 5333                 | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| HP            | Pavilion g6                 | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Acer          | Aspire 5920G                | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | X540LA                      | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| HP            | Pavilion m6                 | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| HP            | EliteBook 745 G6            | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| HUAWEI        | BOHL-WXX9                   | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Samsung       | N150/N210/N220              | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| Dell          | System XPS L502X            | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| Acer          | Aspire 5551                 | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| Dell          | Latitude E6420              | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| Notebook      | NL40_50CU                   | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| System76      | Galago Pro                  | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Medion        | E6239 MD99452               | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| HP            | Laptop 14-bs0xx             | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Apple         | MacBook5,1                  | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| Dell          | XPS 13 9360                 | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| Toshiba       | Satellite L50-B             | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| HP            | G70                         | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| Apple         | MacBookPro12,1              | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| HP            | Laptop 14-bs0xx             | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Acer          | Aspire 5349                 | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| Dell          | Latitude E7450              | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| MSI           | WS65 9TK                    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Dell          | Latitude 5480               | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 255 G2                      | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| Dell          | Inspiron 15-3552            | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| SLIMBOOK      | PROX15                      | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Dell          | Latitude E5420              | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Dell          | Vostro 5490                 | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | ThinkPad T520 424329U       | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| HP            | EliteBook 8560w             | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Dell          | Latitude E7240              | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | XPS M1530                   | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| Dell          | Latitude E5450              | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| HP            | Pavilion dv6                | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| Dell          | Inspiron 13-5378            | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | Precision M6300             | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| System76      | Galago Pro                  | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Alienware     | 17 R4                       | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Lenovo        | V145-15AST 81MT             | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Acer          | Aspire ES1-512              | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| Acer          | Aspire E1-572               | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| Advent        | Roma                        | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| System76      | Bonobo Extreme              | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| HP            | Pavilion dv6                | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| ASUSTek       | S550CA                      | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| ASUSTek       | S550CA                      | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| Dell          | Inspiron ME051              | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| eMachines     | eM350                       | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Toshiba       | Satellite Pro C660          | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| Dell          | Latitude E6230              | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Acer          | Aspire E5-575G              | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| Dell          | Latitude E6230              | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 45        | 16.19%  |
| Ubuntu 18.04       | 28        | 10.07%  |
| Debian 11          | 9         | 3.24%   |
| Debian 10          | 7         | 2.52%   |
| Ubuntu 22.04       | 6         | 2.16%   |
| OpenMandriva 4.2   | 6         | 2.16%   |
| Zorin 16           | 5         | 1.8%    |
| Ubuntu 19.10       | 5         | 1.8%    |
| Manjaro            | 5         | 1.8%    |
| Linux Mint 20.2    | 5         | 1.8%    |
| KDE neon 20.04     | 5         | 1.8%    |
| Fedora 36          | 5         | 1.8%    |
| Ubuntu 21.10       | 4         | 1.44%   |
| Ubuntu 19.04       | 4         | 1.44%   |
| Pop!_OS 21.10      | 4         | 1.44%   |
| Pop!_OS 20.04      | 4         | 1.44%   |
| Linux Mint 20      | 4         | 1.44%   |
| Linux Mint 19.3    | 4         | 1.44%   |
| Fedora 34          | 4         | 1.44%   |
| Debian Unstable    | 4         | 1.44%   |
| BlackPanther 18.1  | 4         | 1.44%   |
| ArcoLinux Rolling  | 4         | 1.44%   |
| Arch               | 4         | 1.44%   |
| Zorin 15           | 3         | 1.08%   |
| ROSA R10           | 3         | 1.08%   |
| Pop!_OS 22.04      | 3         | 1.08%   |
| Pop!_OS 20.10      | 3         | 1.08%   |
| Lubuntu 20.04      | 3         | 1.08%   |
| Linux Mint 20.3    | 3         | 1.08%   |
| Linux Mint 19.2    | 3         | 1.08%   |
| Kubuntu 20.04      | 3         | 1.08%   |
| Fedora 33          | 3         | 1.08%   |
| Arch Rolling       | 3         | 1.08%   |
| Ubuntu Unity 16.04 | 2         | 0.72%   |
| Ubuntu MATE 20.04  | 2         | 0.72%   |
| Ubuntu 16.04       | 2         | 0.72%   |
| ROSA R9            | 2         | 0.72%   |
| Pop!_OS 21.04      | 2         | 0.72%   |
| Manjaro 21.0.7     | 2         | 0.72%   |
| Linux Mint 20.1    | 2         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 95        | 35.71%  |
| Linux Mint    | 24        | 9.02%   |
| Debian        | 20        | 7.52%   |
| Pop!_OS       | 16        | 6.02%   |
| Fedora        | 15        | 5.64%   |
| Manjaro       | 12        | 4.51%   |
| Kubuntu       | 10        | 3.76%   |
| Zorin         | 8         | 3.01%   |
| OpenMandriva  | 7         | 2.63%   |
| Arch          | 7         | 2.63%   |
| ROSA          | 6         | 2.26%   |
| Lubuntu       | 5         | 1.88%   |
| KDE neon      | 5         | 1.88%   |
| Elementary    | 4         | 1.5%    |
| BlackPanther  | 4         | 1.5%    |
| ArcoLinux     | 4         | 1.5%    |
| Ubuntu Unity  | 3         | 1.13%   |
| openSUSE      | 3         | 1.13%   |
| Endless       | 3         | 1.13%   |
| Xubuntu       | 2         | 0.75%   |
| Ubuntu MATE   | 2         | 0.75%   |
| Ubuntu Budgie | 2         | 0.75%   |
| LMDE          | 2         | 0.75%   |
| Clear Linux   | 2         | 0.75%   |
| CentOS        | 2         | 0.75%   |
| RHEL          | 1         | 0.38%   |
| Peppermint    | 1         | 0.38%   |
| Chrome OS     | 1         | 0.38%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.3.0-46-generic         | 8         | 2.66%   |
| 5.4.0-42-generic         | 6         | 1.99%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.99%   |
| 5.4.0-52-generic         | 5         | 1.66%   |
| 5.15.0-46-generic        | 5         | 1.66%   |
| 5.4.0-26-generic         | 4         | 1.33%   |
| 5.4.0-31-generic         | 3         | 1%      |
| 5.4.0-29-generic         | 3         | 1%      |
| 5.15.0-40-generic        | 3         | 1%      |
| 5.11.0-27-generic        | 3         | 1%      |
| 5.10.0-14-amd64          | 3         | 1%      |
| 4.19.0-9-amd64           | 3         | 1%      |
| 4.18.16-desktop-1bP      | 3         | 1%      |
| 5.8.0-7625-generic       | 2         | 0.66%   |
| 5.8.0-53-generic         | 2         | 0.66%   |
| 5.8.0-43-generic         | 2         | 0.66%   |
| 5.4.0-91-generic         | 2         | 0.66%   |
| 5.4.0-80-generic         | 2         | 0.66%   |
| 5.4.0-7634-generic       | 2         | 0.66%   |
| 5.4.0-73-generic         | 2         | 0.66%   |
| 5.4.0-72-generic         | 2         | 0.66%   |
| 5.4.0-65-generic         | 2         | 0.66%   |
| 5.4.0-62-generic         | 2         | 0.66%   |
| 5.4.0-58-generic         | 2         | 0.66%   |
| 5.4.0-56-generic         | 2         | 0.66%   |
| 5.4.0-54-generic         | 2         | 0.66%   |
| 5.4.0-53-generic         | 2         | 0.66%   |
| 5.4.0-40-generic         | 2         | 0.66%   |
| 5.3.0-40-generic         | 2         | 0.66%   |
| 5.3.0-18-generic         | 2         | 0.66%   |
| 5.18.17-200.fc36.x86_64  | 2         | 0.66%   |
| 5.15.0-48-generic        | 2         | 0.66%   |
| 5.13.0-40-generic        | 2         | 0.66%   |
| 5.13.0-21-generic        | 2         | 0.66%   |
| 5.11.0-41-generic        | 2         | 0.66%   |
| 5.11.0-40-generic        | 2         | 0.66%   |
| 5.11.0-38-generic        | 2         | 0.66%   |
| 5.11.0-37-generic        | 2         | 0.66%   |
| 5.11.0-25-generic        | 2         | 0.66%   |
| 5.10.42-1-MANJARO        | 2         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 65        | 23.38%  |
| 4.15.0  | 23        | 8.27%   |
| 5.3.0   | 17        | 6.12%   |
| 5.11.0  | 17        | 6.12%   |
| 5.8.0   | 15        | 5.4%    |
| 5.15.0  | 12        | 4.32%   |
| 5.13.0  | 10        | 3.6%    |
| 5.10.0  | 10        | 3.6%    |
| 5.0.0   | 8         | 2.88%   |
| 4.19.0  | 8         | 2.88%   |
| 5.10.14 | 6         | 2.16%   |
| 4.18.0  | 5         | 1.8%    |
| 4.18.16 | 3         | 1.08%   |
| 5.7.9   | 2         | 0.72%   |
| 5.6.7   | 2         | 0.72%   |
| 5.6.15  | 2         | 0.72%   |
| 5.6.0   | 2         | 0.72%   |
| 5.19.1  | 2         | 0.72%   |
| 5.18.17 | 2         | 0.72%   |
| 5.18.0  | 2         | 0.72%   |
| 5.17.5  | 2         | 0.72%   |
| 5.16.11 | 2         | 0.72%   |
| 5.10.42 | 2         | 0.72%   |
| 4.9.60  | 2         | 0.72%   |
| 4.9.41  | 2         | 0.72%   |
| 4.12.14 | 2         | 0.72%   |
| 3.10.0  | 2         | 0.72%   |
| 5.9.16  | 1         | 0.36%   |
| 5.9.11  | 1         | 0.36%   |
| 5.9.1   | 1         | 0.36%   |
| 5.9.0   | 1         | 0.36%   |
| 5.8.18  | 1         | 0.36%   |
| 5.8.14  | 1         | 0.36%   |
| 5.7.7   | 1         | 0.36%   |
| 5.7.12  | 1         | 0.36%   |
| 5.6.14  | 1         | 0.36%   |
| 5.4.85  | 1         | 0.36%   |
| 5.4.40  | 1         | 0.36%   |
| 5.4.24  | 1         | 0.36%   |
| 5.3.12  | 1         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 24.73%  |
| 4.15    | 23        | 8.36%   |
| 5.10    | 22        | 8%      |
| 5.3     | 18        | 6.55%   |
| 5.8     | 17        | 6.18%   |
| 5.15    | 17        | 6.18%   |
| 5.11    | 17        | 6.18%   |
| 5.13    | 12        | 4.36%   |
| 4.19    | 9         | 3.27%   |
| 5.0     | 8         | 2.91%   |
| 4.18    | 8         | 2.91%   |
| 5.6     | 7         | 2.55%   |
| 5.18    | 6         | 2.18%   |
| 5.17    | 6         | 2.18%   |
| 4.9     | 5         | 1.82%   |
| 5.9     | 4         | 1.45%   |
| 5.7     | 4         | 1.45%   |
| 5.19    | 4         | 1.45%   |
| 5.14    | 4         | 1.45%   |
| 5.12    | 4         | 1.45%   |
| 5.16    | 3         | 1.09%   |
| 4.12    | 2         | 0.73%   |
| 3.10    | 2         | 0.73%   |
| 5.2     | 1         | 0.36%   |
| 4.4     | 1         | 0.36%   |
| 4.14    | 1         | 0.36%   |
| 4.13    | 1         | 0.36%   |
| 4.10    | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 246       | 95.35%  |
| i686   | 12        | 4.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 127       | 46.69%  |
| Unknown         | 39        | 14.34%  |
| KDE5            | 32        | 11.76%  |
| XFCE            | 16        | 5.88%   |
| X-Cinnamon      | 15        | 5.51%   |
| KDE             | 11        | 4.04%   |
| LXQt            | 5         | 1.84%   |
| Cinnamon        | 5         | 1.84%   |
| Pantheon        | 4         | 1.47%   |
| MATE            | 4         | 1.47%   |
| i3              | 4         | 1.47%   |
| Unity           | 3         | 1.1%    |
| KDE4            | 2         | 0.74%   |
| GNOME Classic   | 2         | 0.74%   |
| Budgie          | 2         | 0.74%   |
| GNOME Flashback | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 214       | 81.68%  |
| Wayland | 24        | 9.16%   |
| Unknown | 22        | 8.4%    |
| Tty     | 2         | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 150       | 56.6%   |
| GDM     | 36        | 13.58%  |
| SDDM    | 31        | 11.7%   |
| LightDM | 21        | 7.92%   |
| GDM3    | 13        | 4.91%   |
| TDM     | 12        | 4.53%   |
| KDM     | 2         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IE   | 131       | 49.25%  |
| en_US   | 40        | 15.04%  |
| en_GB   | 36        | 13.53%  |
| Unknown | 35        | 13.16%  |
| pl_PL   | 10        | 3.76%   |
| en_CA   | 2         | 0.75%   |
| bg_BG   | 2         | 0.75%   |
| pt_PT   | 1         | 0.38%   |
| it_IT   | 1         | 0.38%   |
| ga_IE   | 1         | 0.38%   |
| fr_FR   | 1         | 0.38%   |
| fr_BE   | 1         | 0.38%   |
| es_ES   | 1         | 0.38%   |
| en_ZA   | 1         | 0.38%   |
| en_IN   | 1         | 0.38%   |
| en_DE   | 1         | 0.38%   |
| C       | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 134       | 51.34%  |
| BIOS | 127       | 48.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 206       | 79.23%  |
| Overlay             | 16        | 6.15%   |
| Btrfs               | 16        | 6.15%   |
| Unknown             | 14        | 5.38%   |
| Xfs                 | 4         | 1.54%   |
| Zfs                 | 3         | 1.15%   |
| Fuse.fuse-overlayfs | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 160       | 61.54%  |
| GPT     | 73        | 28.08%  |
| MBR     | 27        | 10.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 230       | 88.8%   |
| Yes       | 29        | 11.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 198       | 76.15%  |
| Yes       | 62        | 23.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 62        | 24.03%  |
| Dell                | 57        | 22.09%  |
| Hewlett-Packard     | 36        | 13.95%  |
| Acer                | 19        | 7.36%   |
| ASUSTek Computer    | 18        | 6.98%   |
| Toshiba             | 10        | 3.88%   |
| Apple               | 9         | 3.49%   |
| Samsung Electronics | 5         | 1.94%   |
| TUXEDO              | 4         | 1.55%   |
| PC Specialist       | 4         | 1.55%   |
| Medion              | 4         | 1.55%   |
| Timi                | 3         | 1.16%   |
| Notebook            | 3         | 1.16%   |
| System76            | 2         | 0.78%   |
| MSI                 | 2         | 0.78%   |
| HUAWEI              | 2         | 0.78%   |
| Entroware           | 2         | 0.78%   |
| eMachines           | 2         | 0.78%   |
| Chuwi               | 2         | 0.78%   |
| Sony                | 1         | 0.39%   |
| SLIMBOOK            | 1         | 0.39%   |
| Schenker            | 1         | 0.39%   |
| Packard Bell        | 1         | 0.39%   |
| Microtech           | 1         | 0.39%   |
| Jumper              | 1         | 0.39%   |
| Gigabyte Technology | 1         | 0.39%   |
| Fujitsu Siemens     | 1         | 0.39%   |
| Framework           | 1         | 0.39%   |
| AVITA               | 1         | 0.39%   |
| Alienware           | 1         | 0.39%   |
| Advent              | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Lenovo V145-15AST 81MT              | 3         | 1.16%   |
| TUXEDO Pulse 15 Gen1                | 2         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 3443CTO   | 2         | 0.78%   |
| Lenovo IdeaPad 510-15ISK 80SR       | 2         | 0.78%   |
| HP Pavilion g6                      | 2         | 0.78%   |
| HP Notebook                         | 2         | 0.78%   |
| Dell XPS 9320                       | 2         | 0.78%   |
| Dell XPS 13 9310                    | 2         | 0.78%   |
| Dell XPS 13 9300                    | 2         | 0.78%   |
| Dell XPS 13 7390                    | 2         | 0.78%   |
| Dell Precision 5550                 | 2         | 0.78%   |
| Dell Latitude E6230                 | 2         | 0.78%   |
| Dell Inspiron 13-5378               | 2         | 0.78%   |
| Apple MacBook6,1                    | 2         | 0.78%   |
| Acer Aspire E5-575G                 | 2         | 0.78%   |
| TUXEDO InfinityBook Pro 15 v5       | 1         | 0.39%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 1         | 0.39%   |
| Toshiba TECRA R850                  | 1         | 0.39%   |
| Toshiba TECRA M4                    | 1         | 0.39%   |
| Toshiba Satellite Pro R50-B         | 1         | 0.39%   |
| Toshiba Satellite Pro C660          | 1         | 0.39%   |
| Toshiba Satellite L500              | 1         | 0.39%   |
| Toshiba Satellite L50-C             | 1         | 0.39%   |
| Toshiba Satellite L50-B             | 1         | 0.39%   |
| Toshiba Satellite C50-B             | 1         | 0.39%   |
| Toshiba Satellite A300              | 1         | 0.39%   |
| Toshiba PORTEGE R830                | 1         | 0.39%   |
| Timi TM1709                         | 1         | 0.39%   |
| Timi TM1703                         | 1         | 0.39%   |
| Timi TM1607                         | 1         | 0.39%   |
| System76 Galago Pro                 | 1         | 0.39%   |
| System76 Bonobo Extreme             | 1         | 0.39%   |
| Sony VPCCB35FG                      | 1         | 0.39%   |
| SLIMBOOK PROX15                     | 1         | 0.39%   |
| Schenker XMG NEO (TGL/M21)          | 1         | 0.39%   |
| Samsung RC420/RC520/RC720           | 1         | 0.39%   |
| Samsung N150/N210/N220              | 1         | 0.39%   |
| Samsung 935XDB                      | 1         | 0.39%   |
| Samsung 550P5C/550P7C               | 1         | 0.39%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 33        | 12.79%  |
| Dell Latitude        | 24        | 9.3%    |
| Lenovo IdeaPad       | 14        | 5.43%   |
| Acer Aspire          | 14        | 5.43%   |
| Dell XPS             | 12        | 4.65%   |
| Dell Inspiron        | 11        | 4.26%   |
| HP EliteBook         | 10        | 3.88%   |
| HP Pavilion          | 9         | 3.49%   |
| Toshiba Satellite    | 7         | 2.71%   |
| Dell Precision       | 6         | 2.33%   |
| Lenovo V145-15AST    | 3         | 1.16%   |
| HP Presario          | 3         | 1.16%   |
| HP Laptop            | 3         | 1.16%   |
| Apple MacBookPro5    | 3         | 1.16%   |
| TUXEDO Pulse         | 2         | 0.78%   |
| TUXEDO InfinityBook  | 2         | 0.78%   |
| Toshiba TECRA        | 2         | 0.78%   |
| Lenovo ThinkBook     | 2         | 0.78%   |
| HP Notebook          | 2         | 0.78%   |
| Dell Vostro          | 2         | 0.78%   |
| ASUS ZenBook         | 2         | 0.78%   |
| ASUS TUF             | 2         | 0.78%   |
| ASUS ROG             | 2         | 0.78%   |
| Apple MacBook6       | 2         | 0.78%   |
| Toshiba PORTEGE      | 1         | 0.39%   |
| Timi TM1709          | 1         | 0.39%   |
| Timi TM1703          | 1         | 0.39%   |
| Timi TM1607          | 1         | 0.39%   |
| System76 Galago      | 1         | 0.39%   |
| System76 Bonobo      | 1         | 0.39%   |
| Sony VPCCB35FG       | 1         | 0.39%   |
| SLIMBOOK PROX15      | 1         | 0.39%   |
| Schenker XMG         | 1         | 0.39%   |
| Samsung RC420        | 1         | 0.39%   |
| Samsung N150         | 1         | 0.39%   |
| Samsung 935XDB       | 1         | 0.39%   |
| Samsung 550P5C       | 1         | 0.39%   |
| Samsung 350V5C       | 1         | 0.39%   |
| PC Specialist TF     | 1         | 0.39%   |
| PC Specialist PCX0DX | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 28        | 10.85%  |
| 2019 | 25        | 9.69%   |
| 2017 | 21        | 8.14%   |
| 2013 | 21        | 8.14%   |
| 2012 | 19        | 7.36%   |
| 2011 | 19        | 7.36%   |
| 2018 | 17        | 6.59%   |
| 2016 | 17        | 6.59%   |
| 2021 | 16        | 6.2%    |
| 2015 | 14        | 5.43%   |
| 2009 | 14        | 5.43%   |
| 2010 | 12        | 4.65%   |
| 2008 | 12        | 4.65%   |
| 2014 | 9         | 3.49%   |
| 2007 | 6         | 2.33%   |
| 2022 | 3         | 1.16%   |
| 2006 | 3         | 1.16%   |
| 2005 | 1         | 0.39%   |
| 2003 | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 258       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 226       | 86.59%  |
| Enabled  | 35        | 13.41%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 258       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 80        | 30.53%  |
| 3.01-4.0    | 54        | 20.61%  |
| 16.01-24.0  | 47        | 17.94%  |
| 8.01-16.0   | 36        | 13.74%  |
| 32.01-64.0  | 22        | 8.4%    |
| 1.01-2.0    | 10        | 3.82%   |
| 2.01-3.0    | 5         | 1.91%   |
| 64.01-256.0 | 3         | 1.15%   |
| 24.01-32.0  | 2         | 0.76%   |
| 0.51-1.0    | 2         | 0.76%   |
| 0.01-0.5    | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 93        | 32.98%  |
| 2.01-3.0   | 71        | 25.18%  |
| 3.01-4.0   | 47        | 16.67%  |
| 4.01-8.0   | 37        | 13.12%  |
| 0.51-1.0   | 21        | 7.45%   |
| 8.01-16.0  | 8         | 2.84%   |
| 16.01-24.0 | 3         | 1.06%   |
| 0.01-0.5   | 2         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 196       | 73.68%  |
| 2      | 58        | 21.8%   |
| 3      | 10        | 3.76%   |
| 0      | 2         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 162       | 62.07%  |
| Yes       | 99        | 37.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 80.69%  |
| No        | 50        | 19.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 256       | 98.84%  |
| No        | 3         | 1.16%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 75.38%  |
| No        | 64        | 24.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ireland | 258       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dublin              | 150       | 57.03%  |
| Cork                | 15        | 5.7%    |
| Galway              | 10        | 3.8%    |
| Limerick            | 9         | 3.42%   |
| Naas                | 7         | 2.66%   |
| Drogheda            | 6         | 2.28%   |
| Ennis               | 5         | 1.9%    |
| Navan               | 4         | 1.52%   |
| Enniscorthy         | 3         | 1.14%   |
| Dún Laoghaire      | 3         | 1.14%   |
| Wexford             | 2         | 0.76%   |
| Westport            | 2         | 0.76%   |
| Waterford           | 2         | 0.76%   |
| Portlaoise          | 2         | 0.76%   |
| Nenagh              | 2         | 0.76%   |
| Kilkenny            | 2         | 0.76%   |
| Clonakilty          | 2         | 0.76%   |
| Athlone             | 2         | 0.76%   |
| Youghal             | 1         | 0.38%   |
| Wicklow             | 1         | 0.38%   |
| Tullow              | 1         | 0.38%   |
| Tullamore           | 1         | 0.38%   |
| Tobercurry          | 1         | 0.38%   |
| Sligo               | 1         | 0.38%   |
| Slane               | 1         | 0.38%   |
| Scarriff            | 1         | 0.38%   |
| Santry              | 1         | 0.38%   |
| Newmarket on Fergus | 1         | 0.38%   |
| New Ross            | 1         | 0.38%   |
| Midleton            | 1         | 0.38%   |
| Maynooth            | 1         | 0.38%   |
| Mallow              | 1         | 0.38%   |
| Loughrea            | 1         | 0.38%   |
| Letterkenny         | 1         | 0.38%   |
| Leixlip             | 1         | 0.38%   |
| Kilrush             | 1         | 0.38%   |
| Killorglin          | 1         | 0.38%   |
| Kenmare             | 1         | 0.38%   |
| Greystones          | 1         | 0.38%   |
| Gorey               | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 64        | 86     | 20.13%  |
| WDC                       | 42        | 50     | 13.21%  |
| Seagate                   | 28        | 36     | 8.81%   |
| Toshiba                   | 24        | 27     | 7.55%   |
| Unknown                   | 23        | 31     | 7.23%   |
| SanDisk                   | 22        | 22     | 6.92%   |
| Hitachi                   | 19        | 22     | 5.97%   |
| Crucial                   | 13        | 20     | 4.09%   |
| Kingston                  | 9         | 11     | 2.83%   |
| HGST                      | 9         | 10     | 2.83%   |
| Micron Technology         | 8         | 9      | 2.52%   |
| Intel                     | 8         | 11     | 2.52%   |
| SK hynix                  | 7         | 7      | 2.2%    |
| Fujitsu                   | 6         | 7      | 1.89%   |
| PNY                       | 3         | 3      | 0.94%   |
| KIOXIA                    | 3         | 3      | 0.94%   |
| Silicon Motion            | 2         | 3      | 0.63%   |
| LITEONIT                  | 2         | 2      | 0.63%   |
| KingSpec                  | 2         | 2      | 0.63%   |
| Apple                     | 2         | 2      | 0.63%   |
| A-DATA Technology         | 2         | 2      | 0.63%   |
| Zheino                    | 1         | 1      | 0.31%   |
| W800S                     | 1         | 2      | 0.31%   |
| Verbatim                  | 1         | 1      | 0.31%   |
| Union Memory              | 1         | 1      | 0.31%   |
| SABRENT                   | 1         | 2      | 0.31%   |
| QNAP                      | 1         | 1      | 0.31%   |
| Plextor                   | 1         | 1      | 0.31%   |
| Phison                    | 1         | 1      | 0.31%   |
| OCZ                       | 1         | 1      | 0.31%   |
| Micron/Crucial Technology | 1         | 1      | 0.31%   |
| LITEON                    | 1         | 1      | 0.31%   |
| LaCie                     | 1         | 1      | 0.31%   |
| Integral                  | 1         | 1      | 0.31%   |
| GOODRAM                   | 1         | 1      | 0.31%   |
| FORESEE                   | 1         | 1      | 0.31%   |
| faspeed                   | 1         | 1      | 0.31%   |
| Emtec                     | 1         | 2      | 0.31%   |
| Dogfish                   | 1         | 1      | 0.31%   |
| China                     | 1         | 4      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 5         | 1.52%   |
| SanDisk NVMe SSD Drive 512GB        | 5         | 1.52%   |
| Unknown MMC Card  64GB              | 4         | 1.21%   |
| Toshiba MQ01ABD100 1TB              | 4         | 1.21%   |
| Samsung NVMe SSD Drive 256GB        | 4         | 1.21%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 1.21%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 3         | 0.91%   |
| Unknown MMC Card  32GB              | 3         | 0.91%   |
| Samsung SSD 860 EVO 500GB           | 3         | 0.91%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.91%   |
| Samsung NVMe SSD Drive 512GB        | 3         | 0.91%   |
| Samsung NVMe SSD Drive 500GB        | 3         | 0.91%   |
| PNY CS900 120GB SSD                 | 3         | 0.91%   |
| Hitachi HTS723232A7A364 320GB       | 3         | 0.91%   |
| HGST HTS721010A9E630 1TB            | 3         | 0.91%   |
| HGST HTS545050A7E680 500GB          | 3         | 0.91%   |
| Crucial M4-CT128M4SSD2 128GB        | 3         | 0.91%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD      | 2         | 0.61%   |
| WDC WD10JPVX-00JC3T0 1TB            | 2         | 0.61%   |
| WDC WD10JPCX-24UE4T0 1TB            | 2         | 0.61%   |
| Unknown SL16G  16GB                 | 2         | 0.61%   |
| Unknown HBG4a2  32GB                | 2         | 0.61%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.61%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.61%   |
| SK hynix NVMe SSD Drive 2TB         | 2         | 0.61%   |
| Seagate ST9500420ASG 500GB          | 2         | 0.61%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.61%   |
| Seagate ST500LM000-1EJ162 500GB     | 2         | 0.61%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 2         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.61%   |
| SanDisk X400 2.5 7MM 256GB SSD      | 2         | 0.61%   |
| SanDisk SD5SG2128G1052E 128GB SSD   | 2         | 0.61%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB      | 2         | 0.61%   |
| Samsung SSD 840 EVO 250GB           | 2         | 0.61%   |
| Samsung NVMe SSD Drive 250GB        | 2         | 0.61%   |
| Micron 2300 NVMe 512GB              | 2         | 0.61%   |
| KIOXIA KXG70PNV2T04 NVMe 2048GB     | 2         | 0.61%   |
| KingSpec NT-512 512GB SSD           | 2         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 36     | 25.45%  |
| WDC                 | 27        | 30     | 24.55%  |
| Hitachi             | 19        | 22     | 17.27%  |
| Toshiba             | 14        | 15     | 12.73%  |
| HGST                | 9         | 10     | 8.18%   |
| Fujitsu             | 6         | 7      | 5.45%   |
| Samsung Electronics | 3         | 4      | 2.73%   |
| SABRENT             | 1         | 2      | 0.91%   |
| QNAP                | 1         | 1      | 0.91%   |
| LaCie               | 1         | 1      | 0.91%   |
| Apple               | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 34     | 30.3%   |
| SanDisk             | 14        | 14     | 14.14%  |
| Crucial             | 12        | 19     | 12.12%  |
| Kingston            | 9         | 11     | 9.09%   |
| WDC                 | 5         | 8      | 5.05%   |
| Toshiba             | 3         | 4      | 3.03%   |
| PNY                 | 3         | 3      | 3.03%   |
| Micron Technology   | 2         | 2      | 2.02%   |
| LITEONIT            | 2         | 2      | 2.02%   |
| KingSpec            | 2         | 2      | 2.02%   |
| Zheino              | 1         | 1      | 1.01%   |
| W800S               | 1         | 2      | 1.01%   |
| Verbatim            | 1         | 1      | 1.01%   |
| SK hynix            | 1         | 1      | 1.01%   |
| Plextor             | 1         | 1      | 1.01%   |
| OCZ                 | 1         | 1      | 1.01%   |
| LITEON              | 1         | 1      | 1.01%   |
| Intel               | 1         | 1      | 1.01%   |
| Integral            | 1         | 1      | 1.01%   |
| GOODRAM             | 1         | 1      | 1.01%   |
| FORESEE             | 1         | 1      | 1.01%   |
| faspeed             | 1         | 1      | 1.01%   |
| Emtec               | 1         | 2      | 1.01%   |
| Dogfish             | 1         | 1      | 1.01%   |
| China               | 1         | 4      | 1.01%   |
| Apple               | 1         | 1      | 1.01%   |
| A-DATA Technology   | 1         | 1      | 1.01%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 103       | 129    | 34.33%  |
| SSD     | 91        | 121    | 30.33%  |
| NVMe    | 82        | 110    | 27.33%  |
| MMC     | 21        | 29     | 7%      |
| Unknown | 3         | 3      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 179       | 245    | 62.37%  |
| NVMe | 82        | 110    | 28.57%  |
| MMC  | 21        | 29     | 7.32%   |
| SAS  | 5         | 8      | 1.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 131       | 169    | 68.59%  |
| 0.51-1.0   | 53        | 70     | 27.75%  |
| 1.01-2.0   | 6         | 10     | 3.14%   |
| 3.01-4.0   | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 74        | 27.92%  |
| 101-250        | 73        | 27.55%  |
| 501-1000       | 33        | 12.45%  |
| 51-100         | 25        | 9.43%   |
| 1-20           | 23        | 8.68%   |
| 1001-2000      | 16        | 6.04%   |
| Unknown        | 9         | 3.4%    |
| 21-50          | 8         | 3.02%   |
| More than 3000 | 2         | 0.75%   |
| 2001-3000      | 2         | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 39.5%   |
| 101-250        | 47        | 16.73%  |
| 21-50          | 43        | 15.3%   |
| 51-100         | 36        | 12.81%  |
| 251-500        | 20        | 7.12%   |
| 501-1000       | 11        | 3.91%   |
| Unknown        | 9         | 3.2%    |
| 1001-2000      | 3         | 1.07%   |
| More than 3000 | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 12.5%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 6.25%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 6.25%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 6.25%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 6.25%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 6.25%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 6.25%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 6.25%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 2      | 6.25%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 6.25%   |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 6.25%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 6.25%   |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 7      | 37.5%   |
| Toshiba             | 3         | 3      | 18.75%  |
| WDC                 | 1         | 1      | 6.25%   |
| Seagate             | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 7      | 42.86%  |
| Toshiba             | 3         | 3      | 21.43%  |
| WDC                 | 1         | 1      | 7.14%   |
| Seagate             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |
| Fujitsu             | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 15     | 84.62%  |
| SSD  | 2         | 2      | 15.38%  |

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
| Detected | 166       | 250    | 61.25%  |
| Works    | 92        | 125    | 33.95%  |
| Malfunc  | 13        | 17     | 4.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 181       | 59.74%  |
| Samsung Electronics          | 33        | 10.89%  |
| AMD                          | 30        | 9.9%    |
| SanDisk                      | 19        | 6.27%   |
| Nvidia                       | 8         | 2.64%   |
| Toshiba America Info Systems | 7         | 2.31%   |
| SK hynix                     | 6         | 1.98%   |
| Micron Technology            | 6         | 1.98%   |
| KIOXIA                       | 3         | 0.99%   |
| Union Memory (Shenzhen)      | 2         | 0.66%   |
| Silicon Motion               | 2         | 0.66%   |
| Micron/Crucial Technology    | 2         | 0.66%   |
| Silicon Image                | 1         | 0.33%   |
| Phison Electronics           | 1         | 0.33%   |
| ADATA Technology             | 1         | 0.33%   |
| Adaptec                      | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 8.07%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 26        | 8.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 5.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 4.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 4.04%   |
| Samsung NVMe SSD Controller 980                                                | 10        | 3.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 3.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 2.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 2.17%   |
| Micron Non-Volatile memory controller                                          | 6         | 1.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 1.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 1.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.86%   |
| Nvidia MCP79 AHCI Controller                                                   | 5         | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.24%   |
| SanDisk PC SN520 NVMe SSD                                                      | 4         | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.24%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 1.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.24%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.93%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.93%   |
| Intel SSD 660P Series                                                          | 3         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.93%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.62%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 182       | 59.28%  |
| NVMe | 83        | 27.04%  |
| IDE  | 21        | 6.84%   |
| RAID | 20        | 6.51%   |
| SCSI | 1         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 216       | 83.72%  |
| AMD    | 42        | 16.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 1.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.94%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 1.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.55%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.55%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 1.16%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.16%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.16%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.16%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 1.16%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 1.16%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.16%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 1.16%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.16%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 1.16%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.78%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.78%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.78%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.78%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.78%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.78%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.78%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 2         | 0.78%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 61        | 23.64%  |
| Intel Core i5           | 57        | 22.09%  |
| Other                   | 24        | 9.3%    |
| Intel Core 2 Duo        | 18        | 6.98%   |
| Intel Core i3           | 17        | 6.59%   |
| Intel Celeron           | 16        | 6.2%    |
| AMD Ryzen 5             | 8         | 3.1%    |
| AMD Ryzen 7             | 7         | 2.71%   |
| Intel Atom              | 6         | 2.33%   |
| Intel Pentium           | 5         | 1.94%   |
| AMD A8                  | 4         | 1.55%   |
| Intel Core 2            | 3         | 1.16%   |
| Intel Pentium Dual-Core | 2         | 0.78%   |
| Intel Core i9           | 2         | 0.78%   |
| Intel Celeron Dual-Core | 2         | 0.78%   |
| AMD Ryzen 9             | 2         | 0.78%   |
| AMD E2                  | 2         | 0.78%   |
| Intel Pentium M         | 1         | 0.39%   |
| Intel Pentium III       | 1         | 0.39%   |
| Intel Genuine           | 1         | 0.39%   |
| Intel Core m7           | 1         | 0.39%   |
| Intel Core m5           | 1         | 0.39%   |
| Intel Core m3           | 1         | 0.39%   |
| Intel Core 2 Extreme    | 1         | 0.39%   |
| Intel Celeron M         | 1         | 0.39%   |
| AMD Turion 64 X2 Mobile | 1         | 0.39%   |
| AMD Sempron             | 1         | 0.39%   |
| AMD Ryzen 7 PRO         | 1         | 0.39%   |
| AMD Ryzen 5 PRO         | 1         | 0.39%   |
| AMD Ryzen 3 PRO         | 1         | 0.39%   |
| AMD Ryzen 3             | 1         | 0.39%   |
| AMD Phenom II           | 1         | 0.39%   |
| AMD FX                  | 1         | 0.39%   |
| AMD E1                  | 1         | 0.39%   |
| AMD E                   | 1         | 0.39%   |
| AMD Athlon 64 X2        | 1         | 0.39%   |
| AMD Athlon              | 1         | 0.39%   |
| AMD A6                  | 1         | 0.39%   |
| AMD A10                 | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 136       | 52.71%  |
| 4      | 85        | 32.95%  |
| 8      | 12        | 4.65%   |
| 6      | 10        | 3.88%   |
| 1      | 9         | 3.49%   |
| 14     | 4         | 1.55%   |
| 12     | 1         | 0.39%   |
| 3      | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 258       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 184       | 71.32%  |
| 1      | 74        | 28.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 249       | 95.77%  |
| Unknown        | 8         | 3.08%   |
| 32-bit         | 3         | 1.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 21.59%  |
| 0x306a9    | 16        | 6.06%   |
| 0x806ec    | 14        | 5.3%    |
| 0x806e9    | 12        | 4.55%   |
| 0x206a7    | 12        | 4.55%   |
| 0x1067a    | 12        | 4.55%   |
| 0x806c1    | 10        | 3.79%   |
| 0x40651    | 9         | 3.41%   |
| 0x806ea    | 7         | 2.65%   |
| 0x406e3    | 7         | 2.65%   |
| 0xa0652    | 6         | 2.27%   |
| 0x306d4    | 6         | 2.27%   |
| 0x30678    | 5         | 1.89%   |
| 0x20655    | 5         | 1.89%   |
| 0x10676    | 5         | 1.89%   |
| 0x06006705 | 5         | 1.89%   |
| 0x906ea    | 4         | 1.52%   |
| 0x906e9    | 4         | 1.52%   |
| 0x6fd      | 4         | 1.52%   |
| 0x406c4    | 4         | 1.52%   |
| 0x306c3    | 4         | 1.52%   |
| 0x08108102 | 4         | 1.52%   |
| 0x706e5    | 3         | 1.14%   |
| 0x106ca    | 3         | 1.14%   |
| 0x08108109 | 3         | 1.14%   |
| 0x906a3    | 2         | 0.76%   |
| 0x806d1    | 2         | 0.76%   |
| 0x6f6      | 2         | 0.76%   |
| 0x6d8      | 2         | 0.76%   |
| 0x506e3    | 2         | 0.76%   |
| 0x20652    | 2         | 0.76%   |
| 0x0a50000c | 2         | 0.76%   |
| 0x08600103 | 2         | 0.76%   |
| 0x07030106 | 2         | 0.76%   |
| 0x06001119 | 2         | 0.76%   |
| 0x906ed    | 1         | 0.38%   |
| 0x706a8    | 1         | 0.38%   |
| 0x706a1    | 1         | 0.38%   |
| 0x6fb      | 1         | 0.38%   |
| 0x6f2      | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 18.99%  |
| IvyBridge        | 21        | 8.14%   |
| SandyBridge      | 18        | 6.98%   |
| Penryn           | 17        | 6.59%   |
| Skylake          | 15        | 5.81%   |
| Haswell          | 15        | 5.81%   |
| TigerLake        | 13        | 5.04%   |
| Silvermont       | 13        | 5.04%   |
| Westmere         | 10        | 3.88%   |
| Core             | 9         | 3.49%   |
| Zen+             | 8         | 3.1%    |
| Zen 2            | 7         | 2.71%   |
| Excavator        | 7         | 2.71%   |
| Broadwell        | 7         | 2.71%   |
| IceLake          | 6         | 2.33%   |
| CometLake        | 6         | 2.33%   |
| P6               | 4         | 1.55%   |
| Zen 3            | 3         | 1.16%   |
| Puma             | 3         | 1.16%   |
| K8 Hammer        | 3         | 1.16%   |
| Goldmont plus    | 3         | 1.16%   |
| Bonnell          | 3         | 1.16%   |
| Bobcat           | 3         | 1.16%   |
| Unknown          | 3         | 1.16%   |
| Zen              | 2         | 0.78%   |
| Piledriver       | 2         | 0.78%   |
| K10              | 2         | 0.78%   |
| Goldmont         | 2         | 0.78%   |
| Alderlake Hybrid | 2         | 0.78%   |
| Nehalem          | 1         | 0.39%   |
| Jaguar           | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 185       | 59.11%  |
| Nvidia | 81        | 25.88%  |
| AMD    | 47        | 15.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 6.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 4.64%   |
| Intel HD Graphics 620                                                                    | 12        | 3.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.1%    |
| Intel UHD Graphics 620                                                                   | 9         | 2.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.17%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.86%   |
| AMD Renoir                                                                               | 6         | 1.86%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.55%   |
| Intel HD Graphics 630                                                                    | 5         | 1.55%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.24%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.24%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.24%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.93%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.93%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.93%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.93%   |
| AMD Cezanne                                                                              | 3         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.62%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.62%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.62%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.62%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.62%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 136       | 52.71%  |
| Intel + Nvidia | 47        | 18.22%  |
| 1 x AMD        | 34        | 13.18%  |
| 1 x Nvidia     | 27        | 10.47%  |
| AMD + Nvidia   | 6         | 2.33%   |
| 2 x AMD        | 5         | 1.94%   |
| Intel + AMD    | 2         | 0.78%   |
| 2 x Nvidia     | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 210       | 80.77%  |
| Proprietary | 42        | 16.15%  |
| Unknown     | 8         | 3.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 158       | 59.62%  |
| 0.01-0.5   | 41        | 15.47%  |
| 1.01-2.0   | 22        | 8.3%    |
| 3.01-4.0   | 20        | 7.55%   |
| 0.51-1.0   | 15        | 5.66%   |
| 5.01-6.0   | 4         | 1.51%   |
| 7.01-8.0   | 3         | 1.13%   |
| 2.01-3.0   | 2         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 17.77%  |
| LG Display              | 49        | 17.07%  |
| BOE                     | 35        | 12.2%   |
| Chimei Innolux          | 30        | 10.45%  |
| Samsung Electronics     | 25        | 8.71%   |
| Sharp                   | 19        | 6.62%   |
| Dell                    | 15        | 5.23%   |
| Apple                   | 8         | 2.79%   |
| Chi Mei Optoelectronics | 7         | 2.44%   |
| PANDA                   | 6         | 2.09%   |
| Lenovo                  | 6         | 2.09%   |
| Philips                 | 4         | 1.39%   |
| Hewlett-Packard         | 4         | 1.39%   |
| Goldstar                | 4         | 1.39%   |
| Acer                    | 4         | 1.39%   |
| AOC                     | 3         | 1.05%   |
| LG Philips              | 2         | 0.7%    |
| InfoVision              | 2         | 0.7%    |
| CPT                     | 2         | 0.7%    |
| BOE Technology Group    | 2         | 0.7%    |
| ___                     | 1         | 0.35%   |
| ViewSonic               | 1         | 0.35%   |
| Unknown                 | 1         | 0.35%   |
| Toshiba                 | 1         | 0.35%   |
| Quanta Display          | 1         | 0.35%   |
| LGD                     | 1         | 0.35%   |
| Lenovo Group Limited    | 1         | 0.35%   |
| Iiyama                  | 1         | 0.35%   |
| BenQ                    | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 3         | 1.02%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 1.02%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 3         | 1.02%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 2         | 0.68%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch              | 2         | 0.68%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.68%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.68%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.68%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.68%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 2         | 0.68%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 2         | 0.68%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 2         | 0.68%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.68%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 2         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.68%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 2         | 0.68%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch           | 2         | 0.68%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch     | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 2         | 0.68%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                | 2         | 0.68%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.68%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 0.68%   |
| ___ TV ___9000 1360x768                                              | 1         | 0.34%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch            | 1         | 0.34%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1         | 0.34%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch            | 1         | 0.34%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch              | 1         | 0.34%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch              | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 115       | 41.67%  |
| 1366x768 (WXGA)    | 77        | 27.9%   |
| 1600x900 (HD+)     | 13        | 4.71%   |
| 1280x800 (WXGA)    | 12        | 4.35%   |
| 3840x2160 (4K)     | 11        | 3.99%   |
| 1920x1200 (WUXGA)  | 10        | 3.62%   |
| 1440x900 (WXGA+)   | 9         | 3.26%   |
| 2560x1440 (QHD)    | 6         | 2.17%   |
| 3440x1440          | 4         | 1.45%   |
| 3840x2400          | 3         | 1.09%   |
| 1024x600           | 3         | 1.09%   |
| 3200x1800 (QHD+)   | 2         | 0.72%   |
| 2560x1600          | 2         | 0.72%   |
| 1600x1200          | 2         | 0.72%   |
| 1360x768           | 2         | 0.72%   |
| 3456x2160          | 1         | 0.36%   |
| 2256x1504          | 1         | 0.36%   |
| 2160x1440          | 1         | 0.36%   |
| 1680x1050 (WSXGA+) | 1         | 0.36%   |
| 1280x1024 (SXGA)   | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 121       | 41.44%  |
| 14      | 43        | 14.73%  |
| 13      | 37        | 12.67%  |
| 17      | 15        | 5.14%   |
| 27      | 14        | 4.79%   |
| 12      | 12        | 4.11%   |
| 24      | 9         | 3.08%   |
| Unknown | 8         | 2.74%   |
| 21      | 7         | 2.4%    |
| 34      | 5         | 1.71%   |
| 23      | 4         | 1.37%   |
| 11      | 4         | 1.37%   |
| 18      | 3         | 1.03%   |
| 10      | 3         | 1.03%   |
| 31      | 2         | 0.68%   |
| 72      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 29      | 1         | 0.34%   |
| 25      | 1         | 0.34%   |
| 20      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 172       | 59.72%  |
| 201-300     | 44        | 15.28%  |
| 501-600     | 22        | 7.64%   |
| 351-400     | 18        | 6.25%   |
| 401-500     | 11        | 3.82%   |
| Unknown     | 8         | 2.78%   |
| 601-700     | 6         | 2.08%   |
| 701-800     | 5         | 1.74%   |
| 801-900     | 1         | 0.35%   |
| 1501-2000   | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 206       | 79.84%  |
| 16/10   | 34        | 13.18%  |
| Unknown | 7         | 2.71%   |
| 21/9    | 5         | 1.94%   |
| 3/2     | 3         | 1.16%   |
| 4/3     | 2         | 0.78%   |
| 5/4     | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 120       | 41.24%  |
| 81-90          | 59        | 20.27%  |
| 71-80          | 22        | 7.56%   |
| 201-250        | 16        | 5.5%    |
| 301-350        | 14        | 4.81%   |
| 61-70          | 11        | 3.78%   |
| 121-130        | 11        | 3.78%   |
| 351-500        | 8         | 2.75%   |
| Unknown        | 8         | 2.75%   |
| 51-60          | 4         | 1.37%   |
| 141-150        | 4         | 1.37%   |
| 41-50          | 3         | 1.03%   |
| 251-300        | 3         | 1.03%   |
| 131-140        | 3         | 1.03%   |
| 151-200        | 2         | 0.69%   |
| More than 1000 | 1         | 0.34%   |
| 111-120        | 1         | 0.34%   |
| 501-1000       | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 116       | 40.56%  |
| 101-120       | 90        | 31.47%  |
| 51-100        | 38        | 13.29%  |
| 161-240       | 23        | 8.04%   |
| More than 240 | 9         | 3.15%   |
| Unknown       | 8         | 2.8%    |
| 1-50          | 2         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 207       | 79.01%  |
| 2     | 40        | 15.27%  |
| 0     | 9         | 3.44%   |
| 3     | 5         | 1.91%   |
| 4     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 148       | 35.66%  |
| Realtek Semiconductor             | 121       | 29.16%  |
| Qualcomm Atheros                  | 49        | 11.81%  |
| Broadcom                          | 36        | 8.67%   |
| Broadcom Limited                  | 9         | 2.17%   |
| Nvidia                            | 8         | 1.93%   |
| Ralink Technology                 | 5         | 1.2%    |
| Marvell Technology Group          | 5         | 1.2%    |
| Ericsson Business Mobile Networks | 5         | 1.2%    |
| Samsung Electronics               | 3         | 0.72%   |
| Ralink                            | 3         | 0.72%   |
| MediaTek                          | 3         | 0.72%   |
| Lenovo                            | 3         | 0.72%   |
| Xilinx                            | 1         | 0.24%   |
| Xiaomi                            | 1         | 0.24%   |
| TP-Link                           | 1         | 0.24%   |
| Toshiba                           | 1         | 0.24%   |
| T & A Mobile Phones               | 1         | 0.24%   |
| Qualcomm                          | 1         | 0.24%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.24%   |
| NetGear                           | 1         | 0.24%   |
| LSI                               | 1         | 0.24%   |
| ICS Advent                        | 1         | 0.24%   |
| Hewlett-Packard                   | 1         | 0.24%   |
| DisplayLink                       | 1         | 0.24%   |
| Dell                              | 1         | 0.24%   |
| Bose                              | 1         | 0.24%   |
| ASIX Electronics                  | 1         | 0.24%   |
| Apple                             | 1         | 0.24%   |
| 3Com                              | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 13.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 5.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.56%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 2.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 2.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 2.17%   |
| Intel Wireless 8265 / 8275                                        | 11        | 2.17%   |
| Intel Wireless 7260                                               | 11        | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.98%   |
| Intel Wireless 8260                                               | 8         | 1.58%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.19%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.19%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.19%   |
| Intel Wireless 7265                                               | 5         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.99%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.79%   |
| Intel Wireless 3165                                               | 4         | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.59%   |
| Realtek 802.11ac NIC                                              | 3         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.59%   |
| Intel Wireless 3160                                               | 3         | 0.59%   |
| Intel WiFi Link 5100                                              | 3         | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 144       | 53.14%  |
| Qualcomm Atheros                  | 42        | 15.5%   |
| Realtek Semiconductor             | 35        | 12.92%  |
| Broadcom                          | 29        | 10.7%   |
| Ralink Technology                 | 5         | 1.85%   |
| Ralink                            | 3         | 1.11%   |
| MediaTek                          | 3         | 1.11%   |
| Broadcom Limited                  | 3         | 1.11%   |
| Ericsson Business Mobile Networks | 2         | 0.74%   |
| TP-Link                           | 1         | 0.37%   |
| Qualcomm                          | 1         | 0.37%   |
| NetGear                           | 1         | 0.37%   |
| Dell                              | 1         | 0.37%   |
| Apple                             | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 17        | 6.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 5.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 4.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 4.03%   |
| Intel Wireless 8265 / 8275                                     | 11        | 4.03%   |
| Intel Wireless 7260                                            | 11        | 4.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.66%   |
| Intel Wireless 8260                                            | 8         | 2.93%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 2.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 2.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.2%    |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 2.2%    |
| Intel Wireless 7265                                            | 5         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 1.83%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 5         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.47%   |
| Intel Wireless 3165                                            | 4         | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.1%    |
| Realtek 802.11ac NIC                                           | 3         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.1%    |
| Intel Wireless 3160                                            | 3         | 1.1%    |
| Intel WiFi Link 5100                                           | 3         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.1%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 1.1%    |
| Broadcom BCM4311 802.11b/g WLAN                                | 3         | 1.1%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2         | 0.73%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.73%   |
| Intel Wireless-AC 9260                                         | 2         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 108       | 48.87%  |
| Intel                         | 56        | 25.34%  |
| Qualcomm Atheros              | 13        | 5.88%   |
| Broadcom                      | 10        | 4.52%   |
| Nvidia                        | 8         | 3.62%   |
| Broadcom Limited              | 7         | 3.17%   |
| Marvell Technology Group      | 5         | 2.26%   |
| Samsung Electronics           | 3         | 1.36%   |
| Lenovo                        | 3         | 1.36%   |
| Xilinx                        | 1         | 0.45%   |
| Xiaomi                        | 1         | 0.45%   |
| T & A Mobile Phones           | 1         | 0.45%   |
| OnePlus Technology (Shenzhen) | 1         | 0.45%   |
| ICS Advent                    | 1         | 0.45%   |
| DisplayLink                   | 1         | 0.45%   |
| ASIX Electronics              | 1         | 0.45%   |
| 3Com                          | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 31.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 11.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 8.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 5.36%   |
| Nvidia MCP79 Ethernet                                             | 6         | 2.68%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 1.34%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.34%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.34%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.34%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.34%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 1.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.89%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.89%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.89%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.89%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.89%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.89%   |
| Xilinx Ethernet controller                                        | 1         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.45%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.45%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.45%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 256       | 54.01%  |
| Ethernet | 209       | 44.09%  |
| Modem    | 9         | 1.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 210       | 77.49%  |
| Ethernet | 61        | 22.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 194       | 74.9%   |
| 1     | 61        | 23.55%  |
| 0     | 3         | 1.16%   |
| 3     | 1         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 232       | 89.23%  |
| Yes  | 28        | 10.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 104       | 53.06%  |
| Realtek Semiconductor           | 18        | 9.18%   |
| Broadcom                        | 15        | 7.65%   |
| Qualcomm Atheros Communications | 11        | 5.61%   |
| IMC Networks                    | 11        | 5.61%   |
| Lite-On Technology              | 10        | 5.1%    |
| Apple                           | 7         | 3.57%   |
| Dell                            | 6         | 3.06%   |
| Hewlett-Packard                 | 5         | 2.55%   |
| Toshiba                         | 2         | 1.02%   |
| Realtek                         | 2         | 1.02%   |
| Cambridge Silicon Radio         | 2         | 1.02%   |
| Ralink                          | 1         | 0.51%   |
| Foxconn International           | 1         | 0.51%   |
| Foxconn / Hon Hai               | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 46        | 23.47%  |
| Intel AX201 Bluetooth                                       | 19        | 9.69%   |
| Intel AX200 Bluetooth                                       | 16        | 8.16%   |
| Realtek Bluetooth Radio                                     | 15        | 7.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 4.08%   |
| Qualcomm Atheros  Bluetooth Device                          | 6         | 3.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 3.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 2.55%   |
| IMC Networks Bluetooth Radio                                | 5         | 2.55%   |
| Apple Bluetooth Host Controller                             | 5         | 2.55%   |
| Intel AX210 Bluetooth                                       | 4         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 4         | 2.04%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 3         | 1.53%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 1.53%   |
| Intel Bluetooth Device                                      | 3         | 1.53%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.53%   |
| Realtek Bluetooth Radio                                     | 2         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.02%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.02%   |
| IMC Networks Wireless_Device                                | 2         | 1.02%   |
| IMC Networks Bluetooth Device                               | 2         | 1.02%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.02%   |
| Dell Wireless 355 Bluetooth                                 | 2         | 1.02%   |
| Dell DW375 Bluetooth Module                                 | 2         | 1.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 1.02%   |
| Toshiba Bluetooth Device                                    | 1         | 0.51%   |
| Toshiba BCM43142A0                                          | 1         | 0.51%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.51%   |
| Lite-On Wireless_Device                                     | 1         | 0.51%   |
| Lite-On BCM43142A0                                          | 1         | 0.51%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.51%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.51%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.51%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.51%   |
| Foxconn International BCM43142A0 Bluetooth module           | 1         | 0.51%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 205       | 64.26%  |
| Nvidia                | 52        | 16.3%   |
| AMD                   | 45        | 14.11%  |
| Realtek Semiconductor | 3         | 0.94%   |
| GN Netcom             | 3         | 0.94%   |
| Lenovo                | 2         | 0.63%   |
| C-Media Electronics   | 2         | 0.63%   |
| VIA Technologies      | 1         | 0.31%   |
| RODE Microphones      | 1         | 0.31%   |
| No brand              | 1         | 0.31%   |
| Logitech              | 1         | 0.31%   |
| ESS Technology        | 1         | 0.31%   |
| Creative Technology   | 1         | 0.31%   |
| AUDIOLAB              | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 34        | 9.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 6.15%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 4.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 3.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 2.67%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.14%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.87%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.87%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.6%    |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.6%    |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.6%    |
| Intel CM238 HD Audio Controller                                                                   | 5         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.34%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.34%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.07%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.07%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.8%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 43        | 28.1%   |
| SK hynix            | 29        | 18.95%  |
| Micron Technology   | 20        | 13.07%  |
| Kingston            | 13        | 8.5%    |
| Unknown             | 12        | 7.84%   |
| Crucial             | 9         | 5.88%   |
| Corsair             | 6         | 3.92%   |
| Ramaxel Technology  | 5         | 3.27%   |
| Elpida              | 4         | 2.61%   |
| Nanya Technology    | 3         | 1.96%   |
| Unknown (ABCD)      | 2         | 1.31%   |
| Transcend           | 1         | 0.65%   |
| SHARETRONIC         | 1         | 0.65%   |
| Patriot             | 1         | 0.65%   |
| G.Skill             | 1         | 0.65%   |
| CSX                 | 1         | 0.65%   |
| Apacer              | 1         | 0.65%   |
| A Force             | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 3.11%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 2.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 1.86%   |
| Corsair RAM CM4X16GE2666C18S4 16384MB SODIMM DDR4 2667MT/s       | 3         | 1.86%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.24%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.24%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.24%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.24%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.24%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.24%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 1.24%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 2         | 1.24%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.24%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.24%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.24%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 1.24%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.24%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 1.24%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.24%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 4GB Chip DDR3 1333MT/s              | 2         | 1.24%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 1.24%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.62%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.62%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.62%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                         | 1         | 0.62%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.62%   |
| Unknown RAM Module 256MB SODIMM DRAM                             | 1         | 0.62%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.62%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.62%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.62%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.62%   |
| Unknown RAM Module 128MB SODIMM DRAM                             | 1         | 0.62%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.62%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                | 1         | 0.62%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.62%   |
| SK hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s          | 1         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 64        | 47.41%  |
| DDR3    | 39        | 28.89%  |
| LPDDR4  | 9         | 6.67%   |
| DDR2    | 8         | 5.93%   |
| LPDDR3  | 5         | 3.7%    |
| SDRAM   | 4         | 2.96%   |
| DDR     | 2         | 1.48%   |
| Unknown | 2         | 1.48%   |
| DRAM    | 1         | 0.74%   |
| DDR5    | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 85.4%   |
| Row Of Chips | 15        | 10.95%  |
| Chip         | 4         | 2.92%   |
| Unknown      | 1         | 0.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 47        | 31.97%  |
| 4096  | 45        | 30.61%  |
| 16384 | 23        | 15.65%  |
| 2048  | 19        | 12.93%  |
| 1024  | 6         | 4.08%   |
| 32768 | 5         | 3.4%    |
| 256   | 1         | 0.68%   |
| 128   | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 27        | 18.49%  |
| 1600    | 24        | 16.44%  |
| 3200    | 17        | 11.64%  |
| 2400    | 14        | 9.59%   |
| 2133    | 12        | 8.22%   |
| 1334    | 8         | 5.48%   |
| 4267    | 6         | 4.11%   |
| 3266    | 5         | 3.42%   |
| 1333    | 5         | 3.42%   |
| 800     | 5         | 3.42%   |
| 667     | 5         | 3.42%   |
| 1867    | 3         | 2.05%   |
| 1067    | 3         | 2.05%   |
| 8400    | 2         | 1.37%   |
| 4800    | 2         | 1.37%   |
| 4199    | 2         | 1.37%   |
| 975     | 2         | 1.37%   |
| Unknown | 2         | 1.37%   |
| 2267    | 1         | 0.68%   |
| 2048    | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| STMicroelectronics | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 50%     |
| Brother HL-L2340D series                                  | 1         | 50%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 57        | 25%     |
| Realtek Semiconductor                  | 32        | 14.04%  |
| IMC Networks                           | 24        | 10.53%  |
| Acer                                   | 23        | 10.09%  |
| Microdia                               | 21        | 9.21%   |
| Quanta                                 | 8         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.07%   |
| Apple                                  | 7         | 3.07%   |
| Suyin                                  | 6         | 2.63%   |
| Sunplus Innovation Technology          | 6         | 2.63%   |
| Logitech                               | 6         | 2.63%   |
| Samsung Electronics                    | 5         | 2.19%   |
| ALi                                    | 5         | 2.19%   |
| Syntek                                 | 4         | 1.75%   |
| Silicon Motion                         | 3         | 1.32%   |
| Ricoh                                  | 3         | 1.32%   |
| Lite-On Technology                     | 3         | 1.32%   |
| Z-Star Microelectronics                | 1         | 0.44%   |
| Y Media                                | 1         | 0.44%   |
| Unknown                                | 1         | 0.44%   |
| Trust                                  | 1         | 0.44%   |
| Nikon                                  | 1         | 0.44%   |
| Lenovo                                 | 1         | 0.44%   |
| DigiTech                               | 1         | 0.44%   |
| Alcor Micro                            | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD               | 12        | 5.22%   |
| Microdia Integrated_Webcam_HD              | 10        | 4.35%   |
| IMC Networks Integrated Camera             | 9         | 3.91%   |
| Chicony USB2.0 Camera                      | 7         | 3.04%   |
| Chicony Integrated Camera                  | 7         | 3.04%   |
| Chicony HD Webcam                          | 7         | 3.04%   |
| Acer Integrated Camera                     | 7         | 3.04%   |
| Apple Built-in iSight                      | 6         | 2.61%   |
| Samsung Galaxy A5 (MTP)                    | 5         | 2.17%   |
| Microdia Integrated Webcam                 | 4         | 1.74%   |
| IMC Networks USB2.0 HD UVC WebCam          | 4         | 1.74%   |
| Acer EasyCamera                            | 4         | 1.74%   |
| Realtek Integrated Webcam HD               | 3         | 1.3%    |
| Chicony Lenovo EasyCamera                  | 3         | 1.3%    |
| ALi WebCam                                 | 3         | 1.3%    |
| Acer BisonCam, NB Pro                      | 3         | 1.3%    |
| Syntek Integrated Camera                   | 2         | 0.87%   |
| Syntek EasyCamera                          | 2         | 0.87%   |
| Suyin HP Truevision HD                     | 2         | 0.87%   |
| Sunplus Integrated_Webcam_HD               | 2         | 0.87%   |
| Realtek USB2.0 HD UVC WebCam               | 2         | 0.87%   |
| Realtek USB Camera                         | 2         | 0.87%   |
| Realtek HP Truevision HD integrated webcam | 2         | 0.87%   |
| Realtek HD WebCam                          | 2         | 0.87%   |
| Realtek EasyCamera                         | 2         | 0.87%   |
| Quanta HP Webcam                           | 2         | 0.87%   |
| Logitech B525 HD Webcam                    | 2         | 0.87%   |
| Lite-On HP HD Camera                       | 2         | 0.87%   |
| IMC Networks USB2.0 VGA UVC WebCam         | 2         | 0.87%   |
| IMC Networks TOSHIBA Web Camera - HD       | 2         | 0.87%   |
| IMC Networks EasyCamera                    | 2         | 0.87%   |
| Chicony USB2.0 HD UVC WebCam               | 2         | 0.87%   |
| Chicony USB 2.0 Camera                     | 2         | 0.87%   |
| Chicony thinkpad t430s camera              | 2         | 0.87%   |
| Chicony Lenovo Integrated Camera (0.3MP)   | 2         | 0.87%   |
| Chicony Integrated Camera (1280x720@30)    | 2         | 0.87%   |
| Chicony HP Wide Vision HD Camera           | 2         | 0.87%   |
| Chicony HP TrueVision HD Camera            | 2         | 0.87%   |
| Chicony HP Truevision HD                   | 2         | 0.87%   |
| Chicony EasyCamera                         | 2         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 31.48%  |
| Synaptics                  | 15        | 27.78%  |
| Shenzhen Goodix Technology | 11        | 20.37%  |
| Upek                       | 4         | 7.41%   |
| LighTuning Technology      | 2         | 3.7%    |
| AuthenTec                  | 2         | 3.7%    |
| STMicroelectronics         | 1         | 1.85%   |
| Focal-systems.Corp         | 1         | 1.85%   |
| Elan Microelectronics      | 1         | 1.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 8         | 14.81%  |
| Shenzhen Goodix FingerPrint                                | 6         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 7.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 7.41%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 5.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 3.7%    |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 3.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 3.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 3.7%    |
| AuthenTec Fingerprint Sensor                               | 2         | 3.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.85%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.85%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.85%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.85%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.85%   |
| Validity Sensors Synaptics WBDI                            | 1         | 1.85%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.85%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.85%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.85%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 17        | 50%     |
| Alcor Micro | 7         | 20.59%  |
| Upek        | 5         | 14.71%  |
| O2 Micro    | 4         | 11.76%  |
| Lenovo      | 1         | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 20.59%  |
| Broadcom 58200                                                               | 6         | 17.65%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 14.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 14.71%  |
| Broadcom 5880                                                                | 4         | 11.76%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 8.82%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.94%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 148       | 55.43%  |
| 1     | 95        | 35.58%  |
| 2     | 19        | 7.12%   |
| 3     | 5         | 1.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 38.13%  |
| Chipcard                 | 29        | 20.86%  |
| Net/wireless             | 19        | 13.67%  |
| Graphics card            | 17        | 12.23%  |
| Multimedia controller    | 5         | 3.6%    |
| Storage                  | 4         | 2.88%   |
| Communication controller | 3         | 2.16%   |
| Card reader              | 3         | 2.16%   |
| Camera                   | 3         | 2.16%   |
| Bluetooth                | 2         | 1.44%   |
| Modem                    | 1         | 0.72%   |


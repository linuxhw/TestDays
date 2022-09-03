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

Total: 375

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 45        | 16.3%   |
| Ubuntu 18.04                 | 29        | 10.51%  |
| Debian 11                    | 9         | 3.26%   |
| Debian 10                    | 7         | 2.54%   |
| OpenMandriva 4.2             | 6         | 2.17%   |
| Zorin 16                     | 5         | 1.81%   |
| Ubuntu 22.04                 | 5         | 1.81%   |
| Ubuntu 19.10                 | 5         | 1.81%   |
| Manjaro                      | 5         | 1.81%   |
| Linux Mint 20.2              | 5         | 1.81%   |
| KDE neon 20.04               | 5         | 1.81%   |
| Fedora 36                    | 5         | 1.81%   |
| Ubuntu 21.10                 | 4         | 1.45%   |
| Ubuntu 19.04                 | 4         | 1.45%   |
| Ubuntu 16.04                 | 4         | 1.45%   |
| Pop!_OS 21.10                | 4         | 1.45%   |
| Pop!_OS 20.04                | 4         | 1.45%   |
| Linux Mint 20                | 4         | 1.45%   |
| Linux Mint 19.3              | 4         | 1.45%   |
| Fedora 34                    | 4         | 1.45%   |
| Debian Unstable              | 4         | 1.45%   |
| BlackPanther 18.1            | 4         | 1.45%   |
| ArcoLinux Rolling            | 4         | 1.45%   |
| Arch                         | 4         | 1.45%   |
| Zorin 15                     | 3         | 1.09%   |
| ROSA R10                     | 3         | 1.09%   |
| Pop!_OS 22.04                | 3         | 1.09%   |
| Pop!_OS 20.10                | 3         | 1.09%   |
| Lubuntu 20.04                | 3         | 1.09%   |
| Linux Mint 20.3              | 3         | 1.09%   |
| Linux Mint 19.2              | 3         | 1.09%   |
| Kubuntu 20.04                | 3         | 1.09%   |
| Fedora 33                    | 3         | 1.09%   |
| Arch Rolling                 | 3         | 1.09%   |
| Ubuntu MATE 20.04            | 2         | 0.72%   |
| ROSA R9                      | 2         | 0.72%   |
| Pop!_OS 21.04                | 2         | 0.72%   |
| Manjaro 21.0.7               | 2         | 0.72%   |
| Linux Mint 20.1              | 2         | 0.72%   |
| Linux Mint 19.1              | 2         | 0.72%   |
| Kubuntu 21.10                | 2         | 0.72%   |
| Kubuntu 21.04                | 2         | 0.72%   |
| Fedora 35                    | 2         | 0.72%   |
| Fedora 32                    | 2         | 0.72%   |
| Xubuntu 20.10                | 1         | 0.36%   |
| Xubuntu 20.04                | 1         | 0.36%   |
| Ubuntu Budgie 22.04          | 1         | 0.36%   |
| Ubuntu Budgie 21.04          | 1         | 0.36%   |
| Ubuntu Budgie 19.10          | 1         | 0.36%   |
| Ubuntu 20.10                 | 1         | 0.36%   |
| Ubuntu 18.10                 | 1         | 0.36%   |
| ROSA R11.1                   | 1         | 0.36%   |
| ROSA R11                     | 1         | 0.36%   |
| RHEL 8                       | 1         | 0.36%   |
| RHEL 7                       | 1         | 0.36%   |
| Peppermint 9                 | 1         | 0.36%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.36%   |
| openSUSE Leap-15.1           | 1         | 0.36%   |
| openSUSE Leap-15.0           | 1         | 0.36%   |
| OpenMandriva 4.50            | 1         | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 97        | 36.74%  |
| Linux Mint    | 23        | 8.71%   |
| Debian        | 20        | 7.58%   |
| Pop!_OS       | 16        | 6.06%   |
| Fedora        | 15        | 5.68%   |
| Manjaro       | 12        | 4.55%   |
| Kubuntu       | 10        | 3.79%   |
| Zorin         | 8         | 3.03%   |
| OpenMandriva  | 7         | 2.65%   |
| Arch          | 7         | 2.65%   |
| ROSA          | 6         | 2.27%   |
| Lubuntu       | 5         | 1.89%   |
| KDE neon      | 5         | 1.89%   |
| Elementary    | 4         | 1.52%   |
| BlackPanther  | 4         | 1.52%   |
| ArcoLinux     | 4         | 1.52%   |
| openSUSE      | 3         | 1.14%   |
| Endless       | 3         | 1.14%   |
| Xubuntu       | 2         | 0.76%   |
| Ubuntu MATE   | 2         | 0.76%   |
| Ubuntu Budgie | 2         | 0.76%   |
| LMDE          | 2         | 0.76%   |
| Clear Linux   | 2         | 0.76%   |
| CentOS        | 2         | 0.76%   |
| RHEL          | 1         | 0.38%   |
| Peppermint    | 1         | 0.38%   |
| Chrome OS     | 1         | 0.38%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.3.0-46-generic                | 8         | 2.68%   |
| 5.4.0-42-generic                | 6         | 2.01%   |
| 5.10.14-desktop-1omv4002        | 6         | 2.01%   |
| 5.4.0-52-generic                | 5         | 1.68%   |
| 5.15.0-46-generic               | 5         | 1.68%   |
| 5.4.0-26-generic                | 4         | 1.34%   |
| 5.4.0-31-generic                | 3         | 1.01%   |
| 5.4.0-29-generic                | 3         | 1.01%   |
| 5.15.0-40-generic               | 3         | 1.01%   |
| 5.11.0-27-generic               | 3         | 1.01%   |
| 5.10.0-14-amd64                 | 3         | 1.01%   |
| 4.19.0-9-amd64                  | 3         | 1.01%   |
| 4.18.16-desktop-1bP             | 3         | 1.01%   |
| 5.8.0-7625-generic              | 2         | 0.67%   |
| 5.8.0-53-generic                | 2         | 0.67%   |
| 5.8.0-43-generic                | 2         | 0.67%   |
| 5.4.0-91-generic                | 2         | 0.67%   |
| 5.4.0-80-generic                | 2         | 0.67%   |
| 5.4.0-7634-generic              | 2         | 0.67%   |
| 5.4.0-73-generic                | 2         | 0.67%   |
| 5.4.0-72-generic                | 2         | 0.67%   |
| 5.4.0-65-generic                | 2         | 0.67%   |
| 5.4.0-62-generic                | 2         | 0.67%   |
| 5.4.0-58-generic                | 2         | 0.67%   |
| 5.4.0-56-generic                | 2         | 0.67%   |
| 5.4.0-54-generic                | 2         | 0.67%   |
| 5.4.0-53-generic                | 2         | 0.67%   |
| 5.4.0-40-generic                | 2         | 0.67%   |
| 5.3.0-40-generic                | 2         | 0.67%   |
| 5.3.0-18-generic                | 2         | 0.67%   |
| 5.18.17-200.fc36.x86_64         | 2         | 0.67%   |
| 5.13.0-40-generic               | 2         | 0.67%   |
| 5.13.0-21-generic               | 2         | 0.67%   |
| 5.11.0-41-generic               | 2         | 0.67%   |
| 5.11.0-40-generic               | 2         | 0.67%   |
| 5.11.0-38-generic               | 2         | 0.67%   |
| 5.11.0-37-generic               | 2         | 0.67%   |
| 5.11.0-25-generic               | 2         | 0.67%   |
| 5.10.42-1-MANJARO               | 2         | 0.67%   |
| 5.10.0-8-amd64                  | 2         | 0.67%   |
| 5.0.0-37-generic                | 2         | 0.67%   |
| 5.0.0-25-generic                | 2         | 0.67%   |
| 4.9.41-nrj-desktop-1rosa-x86_64 | 2         | 0.67%   |
| 4.18.0-15-generic               | 2         | 0.67%   |
| 4.15.0-65-generic               | 2         | 0.67%   |
| 4.15.0-51-generic               | 2         | 0.67%   |
| 4.15.0-50-generic               | 2         | 0.67%   |
| 3.10.0-1062.18.1.el7.x86_64     | 2         | 0.67%   |
| 5.9.16-200.fc33.x86_64          | 1         | 0.34%   |
| 5.9.11-3-MANJARO                | 1         | 0.34%   |
| 5.9.1-1-default                 | 1         | 0.34%   |
| 5.9.0-1-amd64                   | 1         | 0.34%   |
| 5.8.18-300.fc33.x86_64          | 1         | 0.34%   |
| 5.8.14-300.fc33.x86_64          | 1         | 0.34%   |
| 5.8.0-7630-generic              | 1         | 0.34%   |
| 5.8.0-55-generic                | 1         | 0.34%   |
| 5.8.0-50-generic                | 1         | 0.34%   |
| 5.8.0-48-generic                | 1         | 0.34%   |
| 5.8.0-44-generic                | 1         | 0.34%   |
| 5.8.0-41-generic                | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 65        | 23.64%  |
| 4.15.0  | 23        | 8.36%   |
| 5.3.0   | 17        | 6.18%   |
| 5.11.0  | 17        | 6.18%   |
| 5.8.0   | 15        | 5.45%   |
| 5.15.0  | 10        | 3.64%   |
| 5.13.0  | 10        | 3.64%   |
| 5.10.0  | 10        | 3.64%   |
| 5.0.0   | 8         | 2.91%   |
| 4.19.0  | 8         | 2.91%   |
| 5.10.14 | 6         | 2.18%   |
| 4.18.0  | 5         | 1.82%   |
| 4.18.16 | 3         | 1.09%   |
| 5.7.9   | 2         | 0.73%   |
| 5.6.7   | 2         | 0.73%   |
| 5.6.15  | 2         | 0.73%   |
| 5.6.0   | 2         | 0.73%   |
| 5.19.1  | 2         | 0.73%   |
| 5.18.17 | 2         | 0.73%   |
| 5.18.0  | 2         | 0.73%   |
| 5.17.5  | 2         | 0.73%   |
| 5.16.11 | 2         | 0.73%   |
| 5.10.42 | 2         | 0.73%   |
| 4.9.60  | 2         | 0.73%   |
| 4.9.41  | 2         | 0.73%   |
| 4.12.14 | 2         | 0.73%   |
| 3.10.0  | 2         | 0.73%   |
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
| 5.2.17  | 1         | 0.36%   |
| 5.19.0  | 1         | 0.36%   |
| 5.18.16 | 1         | 0.36%   |
| 5.18.13 | 1         | 0.36%   |
| 5.18.12 | 1         | 0.36%   |
| 5.18.1  | 1         | 0.36%   |
| 5.17.4  | 1         | 0.36%   |
| 5.17.3  | 1         | 0.36%   |
| 5.17.1  | 1         | 0.36%   |
| 5.17.0  | 1         | 0.36%   |
| 5.16.15 | 1         | 0.36%   |
| 5.15.7  | 1         | 0.36%   |
| 5.15.5  | 1         | 0.36%   |
| 5.15.25 | 1         | 0.36%   |
| 5.15.15 | 1         | 0.36%   |
| 5.15.12 | 1         | 0.36%   |
| 5.14.7  | 1         | 0.36%   |
| 5.14.5  | 1         | 0.36%   |
| 5.14.13 | 1         | 0.36%   |
| 5.14.11 | 1         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 25%     |
| 4.15    | 23        | 8.46%   |
| 5.10    | 22        | 8.09%   |
| 5.3     | 18        | 6.62%   |
| 5.8     | 17        | 6.25%   |
| 5.11    | 17        | 6.25%   |
| 5.15    | 15        | 5.51%   |
| 5.13    | 12        | 4.41%   |
| 4.19    | 9         | 3.31%   |
| 5.0     | 8         | 2.94%   |
| 4.18    | 8         | 2.94%   |
| 5.6     | 7         | 2.57%   |
| 5.18    | 6         | 2.21%   |
| 5.17    | 6         | 2.21%   |
| 4.9     | 5         | 1.84%   |
| 5.9     | 4         | 1.47%   |
| 5.7     | 4         | 1.47%   |
| 5.14    | 4         | 1.47%   |
| 5.12    | 4         | 1.47%   |
| 5.19    | 3         | 1.1%    |
| 5.16    | 3         | 1.1%    |
| 4.12    | 2         | 0.74%   |
| 3.10    | 2         | 0.74%   |
| 5.2     | 1         | 0.37%   |
| 4.4     | 1         | 0.37%   |
| 4.14    | 1         | 0.37%   |
| 4.13    | 1         | 0.37%   |
| 4.10    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 244       | 95.31%  |
| i686   | 12        | 4.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 126       | 46.67%  |
| Unknown         | 39        | 14.44%  |
| KDE5            | 32        | 11.85%  |
| XFCE            | 16        | 5.93%   |
| X-Cinnamon      | 14        | 5.19%   |
| KDE             | 11        | 4.07%   |
| LXQt            | 5         | 1.85%   |
| Cinnamon        | 5         | 1.85%   |
| Pantheon        | 4         | 1.48%   |
| MATE            | 4         | 1.48%   |
| i3              | 4         | 1.48%   |
| Unity           | 3         | 1.11%   |
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
| X11     | 213       | 81.92%  |
| Wayland | 23        | 8.85%   |
| Unknown | 22        | 8.46%   |
| Tty     | 2         | 0.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 149       | 56.65%  |
| GDM     | 36        | 13.69%  |
| SDDM    | 31        | 11.79%  |
| LightDM | 20        | 7.6%    |
| GDM3    | 13        | 4.94%   |
| TDM     | 12        | 4.56%   |
| KDM     | 2         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IE   | 131       | 49.62%  |
| en_US   | 40        | 15.15%  |
| en_GB   | 35        | 13.26%  |
| Unknown | 35        | 13.26%  |
| pl_PL   | 9         | 3.41%   |
| en_CA   | 2         | 0.76%   |
| bg_BG   | 2         | 0.76%   |
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
| EFI  | 134       | 51.74%  |
| BIOS | 125       | 48.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 204       | 79.07%  |
| Overlay             | 16        | 6.2%    |
| Btrfs               | 16        | 6.2%    |
| Unknown             | 14        | 5.43%   |
| Xfs                 | 4         | 1.55%   |
| Zfs                 | 3         | 1.16%   |
| Fuse.fuse-overlayfs | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 159       | 61.63%  |
| GPT     | 72        | 27.91%  |
| MBR     | 27        | 10.47%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 228       | 88.72%  |
| Yes       | 29        | 11.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 196       | 75.97%  |
| Yes       | 62        | 24.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 62        | 24.22%  |
| Dell                | 56        | 21.88%  |
| Hewlett-Packard     | 36        | 14.06%  |
| Acer                | 19        | 7.42%   |
| ASUSTek Computer    | 18        | 7.03%   |
| Toshiba             | 10        | 3.91%   |
| Apple               | 9         | 3.52%   |
| Samsung Electronics | 5         | 1.95%   |
| TUXEDO              | 4         | 1.56%   |
| PC Specialist       | 4         | 1.56%   |
| Medion              | 4         | 1.56%   |
| Notebook            | 3         | 1.17%   |
| Timi                | 2         | 0.78%   |
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
| Lenovo V145-15AST 81MT              | 3         | 1.17%   |
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
| PC Specialist TF                    | 1         | 0.39%   |
| PC Specialist PCX0DX                | 1         | 0.39%   |
| PC Specialist NH5xAx                | 1         | 0.39%   |
| PC Specialist N150CU                | 1         | 0.39%   |
| Packard Bell EasyNote TK85          | 1         | 0.39%   |
| Notebook P65_P67RGRERA              | 1         | 0.39%   |
| Notebook P15SM                      | 1         | 0.39%   |
| Notebook NL40_50CU                  | 1         | 0.39%   |
| MSI WS65 9TK                        | 1         | 0.39%   |
| MSI Stealth GS66 12UGS              | 1         | 0.39%   |
| Microtech e-book Lite               | 1         | 0.39%   |
| Medion Erazer X7843 MD99945         | 1         | 0.39%   |
| Medion E6239 MD99452                | 1         | 0.39%   |
| Medion E6227                        | 1         | 0.39%   |
| Medion Akoya E6239                  | 1         | 0.39%   |
| Lenovo Y520-15IKBN 80WK             | 1         | 0.39%   |
| Lenovo V15-IIL 82C5                 | 1         | 0.39%   |
| Lenovo V110-15ISK 80TL              | 1         | 0.39%   |
| Lenovo U410                         | 1         | 0.39%   |
| Lenovo ThinkPad X260 20F5S13K00     | 1         | 0.39%   |
| Lenovo ThinkPad X250 20CLS3ST01     | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 33        | 12.89%  |
| Dell Latitude         | 23        | 8.98%   |
| Lenovo IdeaPad        | 14        | 5.47%   |
| Acer Aspire           | 14        | 5.47%   |
| Dell XPS              | 12        | 4.69%   |
| Dell Inspiron         | 11        | 4.3%    |
| HP EliteBook          | 10        | 3.91%   |
| HP Pavilion           | 9         | 3.52%   |
| Toshiba Satellite     | 7         | 2.73%   |
| Dell Precision        | 6         | 2.34%   |
| Lenovo V145-15AST     | 3         | 1.17%   |
| HP Presario           | 3         | 1.17%   |
| HP Laptop             | 3         | 1.17%   |
| Apple MacBookPro5     | 3         | 1.17%   |
| TUXEDO Pulse          | 2         | 0.78%   |
| TUXEDO InfinityBook   | 2         | 0.78%   |
| Toshiba TECRA         | 2         | 0.78%   |
| Lenovo ThinkBook      | 2         | 0.78%   |
| HP Notebook           | 2         | 0.78%   |
| Dell Vostro           | 2         | 0.78%   |
| ASUS ZenBook          | 2         | 0.78%   |
| ASUS TUF              | 2         | 0.78%   |
| ASUS ROG              | 2         | 0.78%   |
| Apple MacBook6        | 2         | 0.78%   |
| Toshiba PORTEGE       | 1         | 0.39%   |
| Timi TM1703           | 1         | 0.39%   |
| Timi TM1607           | 1         | 0.39%   |
| System76 Galago       | 1         | 0.39%   |
| System76 Bonobo       | 1         | 0.39%   |
| Sony VPCCB35FG        | 1         | 0.39%   |
| SLIMBOOK PROX15       | 1         | 0.39%   |
| Schenker XMG          | 1         | 0.39%   |
| Samsung RC420         | 1         | 0.39%   |
| Samsung N150          | 1         | 0.39%   |
| Samsung 935XDB        | 1         | 0.39%   |
| Samsung 550P5C        | 1         | 0.39%   |
| Samsung 350V5C        | 1         | 0.39%   |
| PC Specialist TF      | 1         | 0.39%   |
| PC Specialist PCX0DX  | 1         | 0.39%   |
| PC Specialist NH5xAx  | 1         | 0.39%   |
| PC Specialist N150CU  | 1         | 0.39%   |
| Packard Bell EasyNote | 1         | 0.39%   |
| Notebook P65          | 1         | 0.39%   |
| Notebook P15SM        | 1         | 0.39%   |
| Notebook NL40         | 1         | 0.39%   |
| MSI WS65              | 1         | 0.39%   |
| MSI Stealth           | 1         | 0.39%   |
| Microtech e-book      | 1         | 0.39%   |
| Medion Erazer         | 1         | 0.39%   |
| Medion E6239          | 1         | 0.39%   |
| Medion E6227          | 1         | 0.39%   |
| Medion Akoya          | 1         | 0.39%   |
| Lenovo Y520-15IKBN    | 1         | 0.39%   |
| Lenovo V15-IIL        | 1         | 0.39%   |
| Lenovo V110-15ISK     | 1         | 0.39%   |
| Lenovo U410           | 1         | 0.39%   |
| Lenovo Legion         | 1         | 0.39%   |
| Lenovo IdeaPadFlex    | 1         | 0.39%   |
| Lenovo G580           | 1         | 0.39%   |
| Lenovo G550           | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 27        | 10.55%  |
| 2019 | 25        | 9.77%   |
| 2017 | 21        | 8.2%    |
| 2013 | 21        | 8.2%    |
| 2012 | 19        | 7.42%   |
| 2011 | 19        | 7.42%   |
| 2016 | 17        | 6.64%   |
| 2021 | 16        | 6.25%   |
| 2018 | 16        | 6.25%   |
| 2015 | 14        | 5.47%   |
| 2009 | 14        | 5.47%   |
| 2010 | 12        | 4.69%   |
| 2008 | 12        | 4.69%   |
| 2014 | 9         | 3.52%   |
| 2007 | 6         | 2.34%   |
| 2022 | 3         | 1.17%   |
| 2006 | 3         | 1.17%   |
| 2005 | 1         | 0.39%   |
| 2003 | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 256       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 224       | 86.49%  |
| Enabled  | 35        | 13.51%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 256       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 79        | 30.38%  |
| 3.01-4.0    | 54        | 20.77%  |
| 16.01-24.0  | 46        | 17.69%  |
| 8.01-16.0   | 36        | 13.85%  |
| 32.01-64.0  | 22        | 8.46%   |
| 1.01-2.0    | 10        | 3.85%   |
| 2.01-3.0    | 5         | 1.92%   |
| 64.01-256.0 | 3         | 1.15%   |
| 24.01-32.0  | 2         | 0.77%   |
| 0.51-1.0    | 2         | 0.77%   |
| 0.01-0.5    | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 93        | 33.21%  |
| 2.01-3.0   | 70        | 25%     |
| 3.01-4.0   | 47        | 16.79%  |
| 4.01-8.0   | 37        | 13.21%  |
| 0.51-1.0   | 21        | 7.5%    |
| 8.01-16.0  | 7         | 2.5%    |
| 16.01-24.0 | 3         | 1.07%   |
| 0.01-0.5   | 2         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 194       | 73.48%  |
| 2      | 58        | 21.97%  |
| 3      | 10        | 3.79%   |
| 0      | 2         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 160       | 61.78%  |
| Yes       | 99        | 38.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 80.54%  |
| No        | 50        | 19.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 254       | 98.83%  |
| No        | 3         | 1.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 75.19%  |
| No        | 64        | 24.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ireland | 256       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dublin              | 149       | 57.09%  |
| Cork                | 15        | 5.75%   |
| Galway              | 10        | 3.83%   |
| Limerick            | 9         | 3.45%   |
| Naas                | 7         | 2.68%   |
| Drogheda            | 6         | 2.3%    |
| Ennis               | 5         | 1.92%   |
| Navan               | 4         | 1.53%   |
| Enniscorthy         | 3         | 1.15%   |
| Dún Laoghaire      | 3         | 1.15%   |
| Wexford             | 2         | 0.77%   |
| Westport            | 2         | 0.77%   |
| Waterford           | 2         | 0.77%   |
| Portlaoise          | 2         | 0.77%   |
| Nenagh              | 2         | 0.77%   |
| Kilkenny            | 2         | 0.77%   |
| Clonakilty          | 2         | 0.77%   |
| Athlone             | 2         | 0.77%   |
| Youghal             | 1         | 0.38%   |
| Wicklow             | 1         | 0.38%   |
| Tullow              | 1         | 0.38%   |
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
| Enfield             | 1         | 0.38%   |
| Donegal             | 1         | 0.38%   |
| Cobh                | 1         | 0.38%   |
| Clonsilla           | 1         | 0.38%   |
| Clonmel             | 1         | 0.38%   |
| Clane               | 1         | 0.38%   |
| Castlepollard       | 1         | 0.38%   |
| Carrigaline         | 1         | 0.38%   |
| Carrick on Shannon  | 1         | 0.38%   |
| Carbury             | 1         | 0.38%   |
| Ballyjamesduff      | 1         | 0.38%   |
| Ballina             | 1         | 0.38%   |
| Balbriggan          | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 64        | 85     | 20.25%  |
| WDC                       | 42        | 50     | 13.29%  |
| Seagate                   | 28        | 36     | 8.86%   |
| Toshiba                   | 24        | 27     | 7.59%   |
| Unknown                   | 23        | 31     | 7.28%   |
| SanDisk                   | 22        | 22     | 6.96%   |
| Hitachi                   | 19        | 22     | 6.01%   |
| Crucial                   | 13        | 20     | 4.11%   |
| Kingston                  | 9         | 11     | 2.85%   |
| HGST                      | 9         | 10     | 2.85%   |
| Micron Technology         | 8         | 9      | 2.53%   |
| Intel                     | 8         | 11     | 2.53%   |
| SK hynix                  | 7         | 7      | 2.22%   |
| Fujitsu                   | 6         | 7      | 1.9%    |
| PNY                       | 3         | 3      | 0.95%   |
| Silicon Motion            | 2         | 3      | 0.63%   |
| LITEONIT                  | 2         | 2      | 0.63%   |
| KIOXIA                    | 2         | 2      | 0.63%   |
| KingSpec                  | 2         | 2      | 0.63%   |
| Apple                     | 2         | 2      | 0.63%   |
| A-DATA Technology         | 2         | 2      | 0.63%   |
| Zheino                    | 1         | 1      | 0.32%   |
| W800S                     | 1         | 2      | 0.32%   |
| Verbatim                  | 1         | 1      | 0.32%   |
| Union Memory              | 1         | 1      | 0.32%   |
| SABRENT                   | 1         | 2      | 0.32%   |
| QNAP                      | 1         | 1      | 0.32%   |
| Plextor                   | 1         | 1      | 0.32%   |
| Phison                    | 1         | 1      | 0.32%   |
| OCZ                       | 1         | 1      | 0.32%   |
| Micron/Crucial Technology | 1         | 1      | 0.32%   |
| LITEON                    | 1         | 1      | 0.32%   |
| LaCie                     | 1         | 1      | 0.32%   |
| Integral                  | 1         | 1      | 0.32%   |
| FORESEE                   | 1         | 1      | 0.32%   |
| faspeed                   | 1         | 1      | 0.32%   |
| Emtec                     | 1         | 2      | 0.32%   |
| Dogfish                   | 1         | 1      | 0.32%   |
| China                     | 1         | 4      | 0.32%   |
| ADplus                    | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 5         | 1.52%   |
| SanDisk NVMe SSD Drive 512GB        | 5         | 1.52%   |
| Unknown MMC Card  64GB              | 4         | 1.22%   |
| Toshiba MQ01ABD100 1TB              | 4         | 1.22%   |
| Samsung NVMe SSD Drive 256GB        | 4         | 1.22%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 1.22%   |
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
| Intel NVMe SSD Drive 512GB          | 2         | 0.61%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 0.61%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 0.61%   |
| Hitachi HTS545025B9A300 250GB       | 2         | 0.61%   |
| HGST HTS541010A9E680 1TB            | 2         | 0.61%   |
| Fujitsu MHW2120BH 120GB             | 2         | 0.61%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.61%   |
| Zheino CHN 25SATA01M 030 32GB SSD   | 1         | 0.3%    |
| WDC WDS250G2B0C-00PXH0 250GB        | 1         | 0.3%    |
| WDC WD7500BPKT-80PK4T0 752GB        | 1         | 0.3%    |
| WDC WD6400BPVT-22HXZT3 640GB        | 1         | 0.3%    |
| WDC WD600VE-75HDT1 64GB             | 1         | 0.3%    |
| WDC WD5000LPVX-00V0TT0 500GB        | 1         | 0.3%    |
| WDC WD5000LPVT-08G33T1 500GB        | 1         | 0.3%    |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 0.3%    |
| WDC WD5000LPCX-00VHAT0 500GB        | 1         | 0.3%    |
| WDC WD5000BPVX-00JC3T0 500GB        | 1         | 0.3%    |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 0.3%    |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 0.3%    |
| WDC WD3200LPVX-75V0TT0 320GB        | 1         | 0.3%    |

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
| Samsung Electronics | 30        | 34     | 30.61%  |
| SanDisk             | 14        | 14     | 14.29%  |
| Crucial             | 12        | 19     | 12.24%  |
| Kingston            | 9         | 11     | 9.18%   |
| WDC                 | 5         | 8      | 5.1%    |
| Toshiba             | 3         | 4      | 3.06%   |
| PNY                 | 3         | 3      | 3.06%   |
| Micron Technology   | 2         | 2      | 2.04%   |
| LITEONIT            | 2         | 2      | 2.04%   |
| KingSpec            | 2         | 2      | 2.04%   |
| Zheino              | 1         | 1      | 1.02%   |
| W800S               | 1         | 2      | 1.02%   |
| Verbatim            | 1         | 1      | 1.02%   |
| SK hynix            | 1         | 1      | 1.02%   |
| Plextor             | 1         | 1      | 1.02%   |
| OCZ                 | 1         | 1      | 1.02%   |
| LITEON              | 1         | 1      | 1.02%   |
| Intel               | 1         | 1      | 1.02%   |
| Integral            | 1         | 1      | 1.02%   |
| FORESEE             | 1         | 1      | 1.02%   |
| faspeed             | 1         | 1      | 1.02%   |
| Emtec               | 1         | 2      | 1.02%   |
| Dogfish             | 1         | 1      | 1.02%   |
| China               | 1         | 4      | 1.02%   |
| Apple               | 1         | 1      | 1.02%   |
| A-DATA Technology   | 1         | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 103       | 129    | 34.56%  |
| SSD     | 90        | 120    | 30.2%   |
| NVMe    | 81        | 108    | 27.18%  |
| MMC     | 21        | 29     | 7.05%   |
| Unknown | 3         | 3      | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 178       | 244    | 62.46%  |
| NVMe | 81        | 108    | 28.42%  |
| MMC  | 21        | 29     | 7.37%   |
| SAS  | 5         | 8      | 1.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 131       | 171    | 69.31%  |
| 0.51-1.0   | 51        | 67     | 26.98%  |
| 1.01-2.0   | 4         | 7      | 2.12%   |
| 3.01-4.0   | 3         | 4      | 1.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 73        | 27.76%  |
| 101-250        | 72        | 27.38%  |
| 501-1000       | 33        | 12.55%  |
| 51-100         | 25        | 9.51%   |
| 1-20           | 23        | 8.75%   |
| 1001-2000      | 16        | 6.08%   |
| Unknown        | 9         | 3.42%   |
| 21-50          | 8         | 3.04%   |
| More than 3000 | 2         | 0.76%   |
| 2001-3000      | 2         | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 39.78%  |
| 101-250        | 47        | 16.85%  |
| 21-50          | 42        | 15.05%  |
| 51-100         | 35        | 12.54%  |
| 251-500        | 20        | 7.17%   |
| 501-1000       | 11        | 3.94%   |
| Unknown        | 9         | 3.23%   |
| 1001-2000      | 3         | 1.08%   |
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
| Detected | 165       | 249    | 61.34%  |
| Works    | 91        | 123    | 33.83%  |
| Malfunc  | 13        | 17     | 4.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 180       | 59.8%   |
| Samsung Electronics          | 33        | 10.96%  |
| AMD                          | 30        | 9.97%   |
| SanDisk                      | 19        | 6.31%   |
| Nvidia                       | 8         | 2.66%   |
| Toshiba America Info Systems | 7         | 2.33%   |
| SK hynix                     | 6         | 1.99%   |
| Micron Technology            | 6         | 1.99%   |
| Union Memory (Shenzhen)      | 2         | 0.66%   |
| Silicon Motion               | 2         | 0.66%   |
| Micron/Crucial Technology    | 2         | 0.66%   |
| KIOXIA                       | 2         | 0.66%   |
| Silicon Image                | 1         | 0.33%   |
| Phison Electronics           | 1         | 0.33%   |
| ADATA Technology             | 1         | 0.33%   |
| Adaptec                      | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 8.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 25        | 7.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 5.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 4.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 4.06%   |
| Samsung NVMe SSD Controller 980                                                  | 10        | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 2.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 2.19%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 2.19%   |
| Micron Non-Volatile memory controller                                            | 6         | 1.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.88%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 1.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 1.88%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 1.25%   |
| SanDisk PC SN520 NVMe SSD                                                        | 4         | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 1.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.25%   |
| SK hynix Non-Volatile memory controller                                          | 3         | 0.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.94%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.94%   |
| Intel SSD 660P Series                                                            | 3         | 0.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.94%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.63%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 2         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.63%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.63%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.63%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.63%   |
| Intel Non-Volatile memory controller                                             | 2         | 0.63%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.63%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.31%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.31%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.31%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.31%   |
| Silicon Image PCI0646                                                            | 1         | 0.31%   |
| Samsung Electronics SATA controller                                              | 1         | 0.31%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.31%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.31%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.31%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 181       | 59.34%  |
| NVMe | 82        | 26.89%  |
| IDE  | 21        | 6.89%   |
| RAID | 20        | 6.56%   |
| SCSI | 1         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 214       | 83.59%  |
| AMD    | 42        | 16.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 1.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.56%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.56%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 1.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.17%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 1.17%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.17%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.17%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 1.17%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 1.17%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.17%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 1.17%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.17%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 1.17%   |
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
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 0.78%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.78%   |
| Intel Celeron CPU B815 @ 1.60GHz              | 2         | 0.78%   |
| Intel 12th Gen Core i7-1280P                  | 2         | 0.78%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.78%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.78%   |
| AMD E2-1800 APU with Radeon HD Graphics       | 2         | 0.78%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 0.78%   |
| Intel Pentium M processor 2.00GHz             | 1         | 0.39%   |
| Intel Pentium III Mobile CPU 1000MHz          | 1         | 0.39%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.39%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.39%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.39%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.39%   |
| Intel Pentium CPU 6405U @ 2.40GHz             | 1         | 0.39%   |
| Intel Genuine CPU T2130 @ 1.86GHz             | 1         | 0.39%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.39%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.39%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 61        | 23.83%  |
| Intel Core i5           | 56        | 21.88%  |
| Other                   | 23        | 8.98%   |
| Intel Core 2 Duo        | 18        | 7.03%   |
| Intel Core i3           | 17        | 6.64%   |
| Intel Celeron           | 16        | 6.25%   |
| AMD Ryzen 5             | 8         | 3.13%   |
| AMD Ryzen 7             | 7         | 2.73%   |
| Intel Atom              | 6         | 2.34%   |
| Intel Pentium           | 5         | 1.95%   |
| AMD A8                  | 4         | 1.56%   |
| Intel Core 2            | 3         | 1.17%   |
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
| 2      | 136       | 53.13%  |
| 4      | 83        | 32.42%  |
| 8      | 12        | 4.69%   |
| 6      | 10        | 3.91%   |
| 1      | 9         | 3.52%   |
| 14     | 4         | 1.56%   |
| 12     | 1         | 0.39%   |
| 3      | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 256       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 182       | 71.09%  |
| 1      | 74        | 28.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 247       | 95.74%  |
| Unknown        | 8         | 3.1%    |
| 32-bit         | 3         | 1.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 20.99%  |
| 0x306a9    | 16        | 6.11%   |
| 0x806ec    | 14        | 5.34%   |
| 0x806e9    | 12        | 4.58%   |
| 0x206a7    | 12        | 4.58%   |
| 0x1067a    | 12        | 4.58%   |
| 0x806c1    | 10        | 3.82%   |
| 0x40651    | 9         | 3.44%   |
| 0x806ea    | 7         | 2.67%   |
| 0x406e3    | 7         | 2.67%   |
| 0xa0652    | 6         | 2.29%   |
| 0x306d4    | 6         | 2.29%   |
| 0x30678    | 5         | 1.91%   |
| 0x20655    | 5         | 1.91%   |
| 0x10676    | 5         | 1.91%   |
| 0x06006705 | 5         | 1.91%   |
| 0x906ea    | 4         | 1.53%   |
| 0x906e9    | 4         | 1.53%   |
| 0x6fd      | 4         | 1.53%   |
| 0x406c4    | 4         | 1.53%   |
| 0x306c3    | 4         | 1.53%   |
| 0x08108102 | 4         | 1.53%   |
| 0x706e5    | 3         | 1.15%   |
| 0x106ca    | 3         | 1.15%   |
| 0x08108109 | 3         | 1.15%   |
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
| 0x6ec      | 1         | 0.38%   |
| 0x6b1      | 1         | 0.38%   |
| 0x506ca    | 1         | 0.38%   |
| 0x506c9    | 1         | 0.38%   |
| 0x406c3    | 1         | 0.38%   |
| 0x106e5    | 1         | 0.38%   |
| 0x0a50000b | 1         | 0.38%   |
| 0x08701013 | 1         | 0.38%   |
| 0x08608103 | 1         | 0.38%   |
| 0x08600106 | 1         | 0.38%   |
| 0x08600104 | 1         | 0.38%   |
| 0x0810100b | 1         | 0.38%   |
| 0x07030105 | 1         | 0.38%   |
| 0x0700010f | 1         | 0.38%   |
| 0x06006115 | 1         | 0.38%   |
| 0x0600610e | 1         | 0.38%   |
| 0x05000119 | 1         | 0.38%   |
| 0x010000c8 | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 48        | 18.75%  |
| IvyBridge        | 21        | 8.2%    |
| SandyBridge      | 18        | 7.03%   |
| Penryn           | 17        | 6.64%   |
| Skylake          | 15        | 5.86%   |
| Haswell          | 15        | 5.86%   |
| Silvermont       | 13        | 5.08%   |
| TigerLake        | 12        | 4.69%   |
| Westmere         | 10        | 3.91%   |
| Core             | 9         | 3.52%   |
| Zen+             | 8         | 3.13%   |
| Zen 2            | 7         | 2.73%   |
| Excavator        | 7         | 2.73%   |
| Broadwell        | 7         | 2.73%   |
| IceLake          | 6         | 2.34%   |
| CometLake        | 6         | 2.34%   |
| P6               | 4         | 1.56%   |
| Zen 3            | 3         | 1.17%   |
| Puma             | 3         | 1.17%   |
| K8 Hammer        | 3         | 1.17%   |
| Goldmont plus    | 3         | 1.17%   |
| Bonnell          | 3         | 1.17%   |
| Bobcat           | 3         | 1.17%   |
| Unknown          | 3         | 1.17%   |
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
| Intel  | 183       | 59.03%  |
| Nvidia | 80        | 25.81%  |
| AMD    | 47        | 15.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 4.69%   |
| Intel HD Graphics 620                                                                    | 12        | 3.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.81%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.19%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.88%   |
| AMD Renoir                                                                               | 6         | 1.88%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.56%   |
| Intel HD Graphics 630                                                                    | 5         | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.25%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 1.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.25%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.94%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.94%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.94%   |
| AMD Cezanne                                                                              | 3         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.63%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.63%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.63%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.63%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.63%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.63%   |
| Nvidia GF108M [NVS 5400M]                                                                | 2         | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.63%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.63%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.63%   |
| Intel HD Graphics 530                                                                    | 2         | 0.63%   |
| Intel HD Graphics 515                                                                    | 2         | 0.63%   |
| Intel HD Graphics 500                                                                    | 2         | 0.63%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 2         | 0.63%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.63%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.63%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.63%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.31%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.31%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.31%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.31%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 135       | 52.73%  |
| Intel + Nvidia | 46        | 17.97%  |
| 1 x AMD        | 34        | 13.28%  |
| 1 x Nvidia     | 27        | 10.55%  |
| AMD + Nvidia   | 6         | 2.34%   |
| 2 x AMD        | 5         | 1.95%   |
| Intel + AMD    | 2         | 0.78%   |
| 2 x Nvidia     | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 208       | 80.62%  |
| Proprietary | 42        | 16.28%  |
| Unknown     | 8         | 3.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 59.32%  |
| 0.01-0.5   | 41        | 15.59%  |
| 1.01-2.0   | 22        | 8.37%   |
| 3.01-4.0   | 20        | 7.6%    |
| 0.51-1.0   | 15        | 5.7%    |
| 5.01-6.0   | 4         | 1.52%   |
| 7.01-8.0   | 3         | 1.14%   |
| 2.01-3.0   | 2         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 18.02%  |
| LG Display              | 49        | 17.31%  |
| BOE                     | 34        | 12.01%  |
| Chimei Innolux          | 30        | 10.6%   |
| Samsung Electronics     | 25        | 8.83%   |
| Sharp                   | 19        | 6.71%   |
| Dell                    | 14        | 4.95%   |
| Apple                   | 8         | 2.83%   |
| Chi Mei Optoelectronics | 7         | 2.47%   |
| Lenovo                  | 6         | 2.12%   |
| PANDA                   | 5         | 1.77%   |
| Philips                 | 4         | 1.41%   |
| Hewlett-Packard         | 4         | 1.41%   |
| Goldstar                | 4         | 1.41%   |
| Acer                    | 4         | 1.41%   |
| AOC                     | 3         | 1.06%   |
| LG Philips              | 2         | 0.71%   |
| InfoVision              | 2         | 0.71%   |
| CPT                     | 2         | 0.71%   |
| BOE Technology Group    | 2         | 0.71%   |
| ___                     | 1         | 0.35%   |
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


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 1.03%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 1.03%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 3         | 1.03%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.69%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch               | 2         | 0.69%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.69%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch               | 2         | 0.69%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 2         | 0.69%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.69%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 2         | 0.69%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 2         | 0.69%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 0.69%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.69%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.69%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 2         | 0.69%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch            | 2         | 0.69%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                     | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch      | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch      | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 2         | 0.69%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.69%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch         | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 0.69%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.34%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.34%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch             | 1         | 0.34%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.34%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP14A1 3840x2160 344x194mm 15.5-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP138E 1600x1200 304x228mm 15.0-inch               | 1         | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.34%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.34%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 1         | 0.34%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC4C47 1680x1050 367x229mm 17.0-inch | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3258 1440x900 367x230mm 17.1-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 113       | 41.39%  |
| 1366x768 (WXGA)    | 77        | 28.21%  |
| 1600x900 (HD+)     | 13        | 4.76%   |
| 1280x800 (WXGA)    | 12        | 4.4%    |
| 3840x2160 (4K)     | 11        | 4.03%   |
| 1920x1200 (WUXGA)  | 10        | 3.66%   |
| 1440x900 (WXGA+)   | 9         | 3.3%    |
| 2560x1440 (QHD)    | 5         | 1.83%   |
| 3440x1440          | 4         | 1.47%   |
| 3840x2400          | 3         | 1.1%    |
| 1024x600           | 3         | 1.1%    |
| 3200x1800 (QHD+)   | 2         | 0.73%   |
| 2560x1600          | 2         | 0.73%   |
| 1600x1200          | 2         | 0.73%   |
| 1360x768           | 2         | 0.73%   |
| 3456x2160          | 1         | 0.37%   |
| 2256x1504          | 1         | 0.37%   |
| 2160x1440          | 1         | 0.37%   |
| 1680x1050 (WSXGA+) | 1         | 0.37%   |
| 1280x1024 (SXGA)   | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 120       | 41.67%  |
| 14      | 42        | 14.58%  |
| 13      | 37        | 12.85%  |
| 17      | 15        | 5.21%   |
| 27      | 13        | 4.51%   |
| 12      | 12        | 4.17%   |
| 24      | 9         | 3.13%   |
| Unknown | 8         | 2.78%   |
| 21      | 6         | 2.08%   |
| 34      | 5         | 1.74%   |
| 23      | 4         | 1.39%   |
| 11      | 4         | 1.39%   |
| 18      | 3         | 1.04%   |
| 10      | 3         | 1.04%   |
| 31      | 2         | 0.69%   |
| 72      | 1         | 0.35%   |
| 40      | 1         | 0.35%   |
| 29      | 1         | 0.35%   |
| 25      | 1         | 0.35%   |
| 20      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 170       | 59.86%  |
| 201-300     | 44        | 15.49%  |
| 501-600     | 21        | 7.39%   |
| 351-400     | 18        | 6.34%   |
| 401-500     | 10        | 3.52%   |
| Unknown     | 8         | 2.82%   |
| 601-700     | 6         | 2.11%   |
| 701-800     | 5         | 1.76%   |
| 801-900     | 1         | 0.35%   |
| 1501-2000   | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 204       | 79.69%  |
| 16/10   | 34        | 13.28%  |
| Unknown | 7         | 2.73%   |
| 21/9    | 5         | 1.95%   |
| 3/2     | 3         | 1.17%   |
| 4/3     | 2         | 0.78%   |
| 5/4     | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 119       | 41.46%  |
| 81-90          | 58        | 20.21%  |
| 71-80          | 22        | 7.67%   |
| 201-250        | 15        | 5.23%   |
| 301-350        | 13        | 4.53%   |
| 61-70          | 11        | 3.83%   |
| 121-130        | 11        | 3.83%   |
| 351-500        | 8         | 2.79%   |
| Unknown        | 8         | 2.79%   |
| 51-60          | 4         | 1.39%   |
| 141-150        | 4         | 1.39%   |
| 41-50          | 3         | 1.05%   |
| 251-300        | 3         | 1.05%   |
| 131-140        | 3         | 1.05%   |
| 151-200        | 2         | 0.7%    |
| More than 1000 | 1         | 0.35%   |
| 111-120        | 1         | 0.35%   |
| 501-1000       | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 114       | 40.28%  |
| 101-120       | 89        | 31.45%  |
| 51-100        | 38        | 13.43%  |
| 161-240       | 23        | 8.13%   |
| More than 240 | 9         | 3.18%   |
| Unknown       | 8         | 2.83%   |
| 1-50          | 2         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 206       | 79.23%  |
| 2     | 40        | 15.38%  |
| 0     | 9         | 3.46%   |
| 3     | 4         | 1.54%   |
| 4     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 147       | 35.68%  |
| Realtek Semiconductor             | 119       | 28.88%  |
| Qualcomm Atheros                  | 49        | 11.89%  |
| Broadcom                          | 36        | 8.74%   |
| Broadcom Limited                  | 9         | 2.18%   |
| Nvidia                            | 8         | 1.94%   |
| Ralink Technology                 | 5         | 1.21%   |
| Marvell Technology Group          | 5         | 1.21%   |
| Ericsson Business Mobile Networks | 5         | 1.21%   |
| Samsung Electronics               | 3         | 0.73%   |
| Ralink                            | 3         | 0.73%   |
| MediaTek                          | 3         | 0.73%   |
| Lenovo                            | 3         | 0.73%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 13.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 5.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.59%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 3.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 2.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 2.19%   |
| Intel Wireless 8265 / 8275                                        | 11        | 2.19%   |
| Intel Wireless 7260                                               | 11        | 2.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.79%   |
| Intel Wireless 8260                                               | 8         | 1.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.2%    |
| Nvidia MCP79 Ethernet                                             | 6         | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.2%    |
| Intel Wireless 7265                                               | 5         | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 1%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.8%    |
| Intel Wireless 3165                                               | 4         | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.6%    |
| Intel Wireless 3160                                               | 3         | 0.6%    |
| Intel WiFi Link 5100                                              | 3         | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.6%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.6%    |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 0.6%    |
| Broadcom BCM4311 802.11b/g WLAN                                   | 3         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.4%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.4%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.4%    |
| Realtek 802.11ac NIC                                              | 2         | 0.4%    |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.4%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.4%    |
| Intel Wireless-AC 9260                                            | 2         | 0.4%    |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 0.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 143       | 53.16%  |
| Qualcomm Atheros                  | 42        | 15.61%  |
| Realtek Semiconductor             | 34        | 12.64%  |
| Broadcom                          | 29        | 10.78%  |
| Ralink Technology                 | 5         | 1.86%   |
| Ralink                            | 3         | 1.12%   |
| MediaTek                          | 3         | 1.12%   |
| Broadcom Limited                  | 3         | 1.12%   |
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


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 17        | 6.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 15        | 5.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 12        | 4.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 11        | 4.06%   |
| Intel Wireless 8265 / 8275                                          | 11        | 4.06%   |
| Intel Wireless 7260                                                 | 11        | 4.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 9         | 3.32%   |
| Intel Wireless 8260                                                 | 8         | 2.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 7         | 2.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 6         | 2.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 6         | 2.21%   |
| Intel Wi-Fi 6 AX201                                                 | 6         | 2.21%   |
| Broadcom BCM43142 802.11b/g/n                                       | 6         | 2.21%   |
| Intel Wireless 7265                                                 | 5         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 5         | 1.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 5         | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 4         | 1.48%   |
| Intel Wireless 3165                                                 | 4         | 1.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4         | 1.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 4         | 1.48%   |
| Intel Centrino Ultimate-N 6300                                      | 4         | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 4         | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3         | 1.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 3         | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 3         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 3         | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 3         | 1.11%   |
| Intel Wireless 3160                                                 | 3         | 1.11%   |
| Intel WiFi Link 5100                                                | 3         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 3         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 3         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 3         | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                    | 3         | 1.11%   |
| Broadcom BCM43224 802.11a/b/g/n                                     | 3         | 1.11%   |
| Broadcom BCM4311 802.11b/g WLAN                                     | 3         | 1.11%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 2         | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 2         | 0.74%   |
| Realtek 802.11ac NIC                                                | 2         | 0.74%   |
| Ralink RT5370 Wireless Adapter                                      | 2         | 0.74%   |
| Intel Wireless-AC 9260                                              | 2         | 0.74%   |
| Intel Ultimate N WiFi Link 5300                                     | 2         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2         | 0.74%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 2         | 0.74%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                        | 2         | 0.74%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                       | 2         | 0.74%   |
| Intel Centrino Advanced-N 6200                                      | 2         | 0.74%   |
| Ericsson Business Mobile Networks N5321 gw                          | 2         | 0.74%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                           | 2         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 0.74%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 0.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                   | 2         | 0.74%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1         | 0.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1         | 0.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 0.37%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 1         | 0.37%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 0.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1         | 0.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                         | 1         | 0.37%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)           | 1         | 0.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 106       | 48.4%   |
| Intel                         | 56        | 25.57%  |
| Qualcomm Atheros              | 13        | 5.94%   |
| Broadcom                      | 10        | 4.57%   |
| Nvidia                        | 8         | 3.65%   |
| Broadcom Limited              | 7         | 3.2%    |
| Marvell Technology Group      | 5         | 2.28%   |
| Samsung Electronics           | 3         | 1.37%   |
| Lenovo                        | 3         | 1.37%   |
| Xilinx                        | 1         | 0.46%   |
| Xiaomi                        | 1         | 0.46%   |
| T & A Mobile Phones           | 1         | 0.46%   |
| OnePlus Technology (Shenzhen) | 1         | 0.46%   |
| ICS Advent                    | 1         | 0.46%   |
| DisplayLink                   | 1         | 0.46%   |
| ASIX Electronics              | 1         | 0.46%   |
| 3Com                          | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 31.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 11.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 8.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 4.95%   |
| Nvidia MCP79 Ethernet                                             | 6         | 2.7%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 1.35%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.35%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.35%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 1.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.9%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.9%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.9%    |
| Intel Ethernet Connection I219-V                                  | 2         | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.9%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.9%    |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.9%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.9%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.9%    |
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
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.45%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.45%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 0.45%   |
| Lenovo Ethernet adapter [U2L 100P-Y1]                             | 1         | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.45%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.45%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.45%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.45%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.45%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 254       | 54.04%  |
| Ethernet | 207       | 44.04%  |
| Modem    | 9         | 1.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 210       | 78.07%  |
| Ethernet | 59        | 21.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 193       | 75.1%   |
| 1     | 60        | 23.35%  |
| 0     | 3         | 1.17%   |
| 3     | 1         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 231       | 89.53%  |
| Yes  | 27        | 10.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 53.09%  |
| Realtek Semiconductor           | 17        | 8.76%   |
| Broadcom                        | 15        | 7.73%   |
| Qualcomm Atheros Communications | 11        | 5.67%   |
| IMC Networks                    | 11        | 5.67%   |
| Lite-On Technology              | 10        | 5.15%   |
| Apple                           | 7         | 3.61%   |
| Dell                            | 6         | 3.09%   |
| Hewlett-Packard                 | 5         | 2.58%   |
| Toshiba                         | 2         | 1.03%   |
| Realtek                         | 2         | 1.03%   |
| Cambridge Silicon Radio         | 2         | 1.03%   |
| Ralink                          | 1         | 0.52%   |
| Foxconn International           | 1         | 0.52%   |
| Foxconn / Hon Hai               | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 46        | 23.71%  |
| Intel AX201 Bluetooth                                       | 18        | 9.28%   |
| Intel AX200 Bluetooth                                       | 16        | 8.25%   |
| Realtek Bluetooth Radio                                     | 11        | 5.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 4.12%   |
| Qualcomm Atheros  Bluetooth Device                          | 6         | 3.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 3.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 2.58%   |
| IMC Networks Bluetooth Radio                                | 5         | 2.58%   |
| Apple Bluetooth Host Controller                             | 5         | 2.58%   |
| Intel AX210 Bluetooth                                       | 4         | 2.06%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 4         | 2.06%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 1.55%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 3         | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 1.55%   |
| Intel Bluetooth Device                                      | 3         | 1.55%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.55%   |
| Realtek Bluetooth Radio                                     | 2         | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.03%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.03%   |
| IMC Networks Wireless_Device                                | 2         | 1.03%   |
| IMC Networks Bluetooth Device                               | 2         | 1.03%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.03%   |
| Dell Wireless 355 Bluetooth                                 | 2         | 1.03%   |
| Dell DW375 Bluetooth Module                                 | 2         | 1.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.03%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 1.03%   |
| Toshiba Bluetooth Device                                    | 1         | 0.52%   |
| Toshiba BCM43142A0                                          | 1         | 0.52%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.52%   |
| Lite-On Wireless_Device                                     | 1         | 0.52%   |
| Lite-On BCM43142A0                                          | 1         | 0.52%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.52%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.52%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module           | 1         | 0.52%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 0.52%   |
| Dell Wireless 365 Bluetooth                                 | 1         | 0.52%   |
| Dell Wireless 350 Bluetooth                                 | 1         | 0.52%   |
| Broadcom Bluetooth Device                                   | 1         | 0.52%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 0.52%   |
| Broadcom BCM2070 Bluetooth Device                           | 1         | 0.52%   |
| Apple Bluetooth USB Host Controller                         | 1         | 0.52%   |
| Apple Bluetooth HCI                                         | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 203       | 64.44%  |
| Nvidia                | 52        | 16.51%  |
| AMD                   | 45        | 14.29%  |
| Realtek Semiconductor | 2         | 0.63%   |
| Lenovo                | 2         | 0.63%   |
| GN Netcom             | 2         | 0.63%   |
| C-Media Electronics   | 2         | 0.63%   |
| VIA Technologies      | 1         | 0.32%   |
| RODE Microphones      | 1         | 0.32%   |
| No brand              | 1         | 0.32%   |
| Logitech              | 1         | 0.32%   |
| ESS Technology        | 1         | 0.32%   |
| Creative Technology   | 1         | 0.32%   |
| AUDIOLAB              | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 8.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 6.22%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 4.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 2.7%    |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.16%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.89%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.62%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 1.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.62%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.62%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.35%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.35%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 1.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.81%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.81%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.54%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.54%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.54%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.54%   |
| VIA Technologies VX1                                                                              | 1         | 0.27%   |
| RODE Microphones RODE NT-USB                                                                      | 1         | 0.27%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.27%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.27%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.27%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.27%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 43        | 28.29%  |
| SK hynix            | 28        | 18.42%  |
| Micron Technology   | 20        | 13.16%  |
| Kingston            | 13        | 8.55%   |
| Unknown             | 12        | 7.89%   |
| Crucial             | 9         | 5.92%   |
| Corsair             | 6         | 3.95%   |
| Ramaxel Technology  | 5         | 3.29%   |
| Elpida              | 4         | 2.63%   |
| Nanya Technology    | 3         | 1.97%   |
| Unknown (ABCD)      | 2         | 1.32%   |
| Transcend           | 1         | 0.66%   |
| SHARETRONIC         | 1         | 0.66%   |
| Patriot             | 1         | 0.66%   |
| G.Skill             | 1         | 0.66%   |
| CSX                 | 1         | 0.66%   |
| Apacer              | 1         | 0.66%   |
| A Force             | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 5         | 3.13%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 2.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 1.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.88%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s             | 3         | 1.88%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.25%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 1.25%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB Row Of Chips DDR4 2667MT/s     | 2         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.25%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.25%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.25%   |
| Samsung RAM M471A5244BB0-CPB 4096MB SODIMM DDR4 2400MT/s            | 2         | 1.25%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 2         | 1.25%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.25%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.25%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.25%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                | 2         | 1.25%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 1.25%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 2         | 1.25%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 2         | 1.25%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 4GB Chip DDR3 1333MT/s                 | 2         | 1.25%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s          | 2         | 1.25%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.63%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                       | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                         | 1         | 0.63%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                            | 1         | 0.63%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.63%   |
| Unknown RAM Module 256MB SODIMM DRAM                                | 1         | 0.63%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.63%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.63%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.63%   |
| Unknown RAM Module 128MB SODIMM DRAM                                | 1         | 0.63%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                              | 1         | 0.63%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                   | 1         | 0.63%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.63%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s               | 1         | 0.63%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s               | 1         | 0.63%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.63%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s                | 1         | 0.63%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.63%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.63%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM 4800MT/s                   | 1         | 0.63%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.63%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.63%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.63%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.63%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.63%   |
| Samsung RAM U5H504AM-JGCR 1GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.63%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 63        | 47.01%  |
| DDR3    | 39        | 29.1%   |
| LPDDR4  | 9         | 6.72%   |
| DDR2    | 8         | 5.97%   |
| LPDDR3  | 5         | 3.73%   |
| SDRAM   | 4         | 2.99%   |
| Unknown | 3         | 2.24%   |
| DDR     | 2         | 1.49%   |
| DRAM    | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 116       | 85.29%  |
| Row Of Chips | 15        | 11.03%  |
| Chip         | 4         | 2.94%   |
| Unknown      | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 31.94%  |
| 4096  | 45        | 31.25%  |
| 16384 | 21        | 14.58%  |
| 2048  | 19        | 13.19%  |
| 1024  | 6         | 4.17%   |
| 32768 | 5         | 3.47%   |
| 256   | 1         | 0.69%   |
| 128   | 1         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 27        | 18.62%  |
| 1600    | 24        | 16.55%  |
| 3200    | 17        | 11.72%  |
| 2400    | 13        | 8.97%   |
| 2133    | 12        | 8.28%   |
| 1334    | 8         | 5.52%   |
| 4267    | 6         | 4.14%   |
| 3266    | 5         | 3.45%   |
| 1333    | 5         | 3.45%   |
| 800     | 5         | 3.45%   |
| 667     | 5         | 3.45%   |
| 1867    | 3         | 2.07%   |
| 1067    | 3         | 2.07%   |
| 8400    | 2         | 1.38%   |
| 4800    | 2         | 1.38%   |
| 4199    | 2         | 1.38%   |
| 975     | 2         | 1.38%   |
| Unknown | 2         | 1.38%   |
| 2267    | 1         | 0.69%   |
| 2048    | 1         | 0.69%   |

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
| Chicony Electronics                    | 57        | 25.22%  |
| Realtek Semiconductor                  | 32        | 14.16%  |
| IMC Networks                           | 24        | 10.62%  |
| Acer                                   | 23        | 10.18%  |
| Microdia                               | 21        | 9.29%   |
| Quanta                                 | 8         | 3.54%   |
| Apple                                  | 7         | 3.1%    |
| Suyin                                  | 6         | 2.65%   |
| Logitech                               | 6         | 2.65%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.65%   |
| Sunplus Innovation Technology          | 5         | 2.21%   |
| Samsung Electronics                    | 5         | 2.21%   |
| ALi                                    | 5         | 2.21%   |
| Syntek                                 | 4         | 1.77%   |
| Silicon Motion                         | 3         | 1.33%   |
| Ricoh                                  | 3         | 1.33%   |
| Lite-On Technology                     | 3         | 1.33%   |
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


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 12        | 5.26%   |
| Microdia Integrated_Webcam_HD                    | 10        | 4.39%   |
| IMC Networks Integrated Camera                   | 9         | 3.95%   |
| Chicony USB2.0 Camera                            | 7         | 3.07%   |
| Chicony Integrated Camera                        | 7         | 3.07%   |
| Chicony HD Webcam                                | 7         | 3.07%   |
| Acer Integrated Camera                           | 7         | 3.07%   |
| Apple Built-in iSight                            | 6         | 2.63%   |
| Samsung Galaxy series, misc. (MTP mode)          | 5         | 2.19%   |
| Microdia Integrated Webcam                       | 4         | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 1.75%   |
| Acer EasyCamera                                  | 4         | 1.75%   |
| Realtek Integrated Webcam HD                     | 3         | 1.32%   |
| Chicony Lenovo EasyCamera                        | 3         | 1.32%   |
| ALi WebCam                                       | 3         | 1.32%   |
| Acer BisonCam, NB Pro                            | 3         | 1.32%   |
| Syntek Integrated Camera                         | 2         | 0.88%   |
| Syntek EasyCamera                                | 2         | 0.88%   |
| Suyin HP Truevision HD                           | 2         | 0.88%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 0.88%   |
| Realtek USB2.0 HD UVC WebCam                     | 2         | 0.88%   |
| Realtek USB Camera                               | 2         | 0.88%   |
| Realtek HP Truevision HD integrated webcam       | 2         | 0.88%   |
| Realtek HD WebCam                                | 2         | 0.88%   |
| Realtek EasyCamera                               | 2         | 0.88%   |
| Quanta HP Webcam                                 | 2         | 0.88%   |
| Logitech B525 HD Webcam                          | 2         | 0.88%   |
| Lite-On HP HD Camera                             | 2         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.88%   |
| IMC Networks TOSHIBA Web Camera - HD             | 2         | 0.88%   |
| IMC Networks EasyCamera                          | 2         | 0.88%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 0.88%   |
| Chicony USB 2.0 Camera                           | 2         | 0.88%   |
| Chicony thinkpad t430s camera                    | 2         | 0.88%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 0.88%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 0.88%   |
| Chicony HP Wide Vision HD Camera                 | 2         | 0.88%   |
| Chicony HP TrueVision HD Camera                  | 2         | 0.88%   |
| Chicony HP Truevision HD                         | 2         | 0.88%   |
| Chicony EasyCamera                               | 2         | 0.88%   |
| Chicony CNF9055 Toshiba Webcam                   | 2         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 0.88%   |
| ALi Gateway Webcam                               | 2         | 0.88%   |
| Acer Lenovo EasyCamera                           | 2         | 0.88%   |
| Acer BisonCam,NB Pro                             | 2         | 0.88%   |
| Z-Star Webcam                                    | 1         | 0.44%   |
| Y Media USB Camera                               | 1         | 0.44%   |
| Unknown 720p HD Camera                           | 1         | 0.44%   |
| Trust USB Camera                                 | 1         | 0.44%   |
| Suyin VGA Webcam                                 | 1         | 0.44%   |
| Suyin HD Video WebCam                            | 1         | 0.44%   |
| Suyin Acer CrystalEye Webcam                     | 1         | 0.44%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.44%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.44%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.44%   |
| Sunplus HD WebCam                                | 1         | 0.44%   |
| Silicon Motion WebCam SC-13HDL11939N             | 1         | 0.44%   |
| Silicon Motion Lenovo EasyCamera                 | 1         | 0.44%   |
| Silicon Motion HP Webcam-101                     | 1         | 0.44%   |
| Ricoh USB2.0 Camera                              | 1         | 0.44%   |

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
| Broadcom    | 16        | 48.48%  |
| Alcor Micro | 7         | 21.21%  |
| Upek        | 5         | 15.15%  |
| O2 Micro    | 4         | 12.12%  |
| Lenovo      | 1         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 21.21%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 15.15%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 15.15%  |
| Broadcom 58200                                                               | 5         | 15.15%  |
| Broadcom 5880                                                                | 4         | 12.12%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.03%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 146       | 55.09%  |
| 1     | 96        | 36.23%  |
| 2     | 18        | 6.79%   |
| 3     | 5         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 38.13%  |
| Chipcard                 | 28        | 20.14%  |
| Net/wireless             | 19        | 13.67%  |
| Graphics card            | 18        | 12.95%  |
| Multimedia controller    | 5         | 3.6%    |
| Storage                  | 4         | 2.88%   |
| Communication controller | 3         | 2.16%   |
| Card reader              | 3         | 2.16%   |
| Camera                   | 3         | 2.16%   |
| Bluetooth                | 2         | 1.44%   |
| Modem                    | 1         | 0.72%   |


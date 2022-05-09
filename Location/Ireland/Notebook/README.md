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

Total: 350

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Toshiba       | PORTEGE R830                | [3b3c03d206](https://linux-hardware.org/?probe=3b3c03d206) | Jan 06, 2022 |
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
| Lenovo        | V110-15ISK 80TL             | [0bcae30730](https://linux-hardware.org/?probe=0bcae30730) | Apr 18, 2021 |
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
| HP            | Notebook                    | [fcb1a0a7f0](https://linux-hardware.org/?probe=fcb1a0a7f0) | Feb 22, 2021 |
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
| Lenovo        | V110-15ISK 80TL             | [75538dc806](https://linux-hardware.org/?probe=75538dc806) | Jan 19, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | XPS L502X                   | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| HUAWEI        | BOHL-WXX9                   | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Samsung       | N150/N210/N220              | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| Dell          | XPS L502X                   | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
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
| Alienware     | 17 R4                       | [2b8b2aec58](https://linux-hardware.org/?probe=2b8b2aec58) | Nov 16, 2020 |
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
| HP            | Laptop 14-bs0xx             | [464a456cc4](https://linux-hardware.org/?probe=464a456cc4) | Oct 25, 2020 |
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
| Lenovo        | U410                        | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| HP            | Laptop 14-bs0xx             | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| ASUSTek       | E200HA                      | [270b48d11a](https://linux-hardware.org/?probe=270b48d11a) | Aug 07, 2020 |
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
| Dell          | Latitude E7240              | [6ffc46e99c](https://linux-hardware.org/?probe=6ffc46e99c) | May 06, 2020 |
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
| Dell          | XPS M1530                   | [dbd1208fb0](https://linux-hardware.org/?probe=dbd1208fb0) | Apr 10, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | [3ec999d67c](https://linux-hardware.org/?probe=3ec999d67c) | Apr 07, 2020 |
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
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [82bfd8fc5c](https://linux-hardware.org/?probe=82bfd8fc5c) | Jan 18, 2020 |
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
| Alienware     | 17 R4                       | [7dc27cbde9](https://linux-hardware.org/?probe=7dc27cbde9) | Sep 18, 2019 |
| Alienware     | 17 R4                       | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | [6c0b10b183](https://linux-hardware.org/?probe=6c0b10b183) | Sep 12, 2019 |
| System76      | Galago Pro                  | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Lenovo        | V145-15AST 81MT             | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Acer          | Aspire ES1-512              | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | [b998963e7a](https://linux-hardware.org/?probe=b998963e7a) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | [80df58f615](https://linux-hardware.org/?probe=80df58f615) | Aug 17, 2019 |
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
| ASUSTek       | K53U                        | [44c9ce32b9](https://linux-hardware.org/?probe=44c9ce32b9) | May 18, 2019 |
| ASUSTek       | K53U                        | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| ASUSTek       | S550CA                      | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| Dell          | Inspiron ME051              | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | [4b838f8f56](https://linux-hardware.org/?probe=4b838f8f56) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| eMachines     | eM350                       | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | [0df880aebd](https://linux-hardware.org/?probe=0df880aebd) | Feb 06, 2019 |
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
| Ubuntu 20.04                 | 44        | 17.89%  |
| Ubuntu 18.04                 | 29        | 11.79%  |
| Debian 10                    | 7         | 2.85%   |
| OpenMandriva 4.2             | 6         | 2.44%   |
| Ubuntu 19.10                 | 5         | 2.03%   |
| Linux Mint 20.2              | 5         | 2.03%   |
| KDE neon 20.04               | 5         | 2.03%   |
| Debian 11                    | 5         | 2.03%   |
| Ubuntu 21.10                 | 4         | 1.63%   |
| Ubuntu 19.04                 | 4         | 1.63%   |
| Ubuntu 16.04                 | 4         | 1.63%   |
| Pop!_OS 21.10                | 4         | 1.63%   |
| Pop!_OS 20.04                | 4         | 1.63%   |
| Manjaro                      | 4         | 1.63%   |
| Linux Mint 19.3              | 4         | 1.63%   |
| Fedora 34                    | 4         | 1.63%   |
| Debian Unstable              | 4         | 1.63%   |
| BlackPanther 18.1            | 4         | 1.63%   |
| ArcoLinux Rolling            | 4         | 1.63%   |
| Zorin 16                     | 3         | 1.22%   |
| Zorin 15                     | 3         | 1.22%   |
| ROSA R10                     | 3         | 1.22%   |
| Pop!_OS 20.10                | 3         | 1.22%   |
| Lubuntu 20.04                | 3         | 1.22%   |
| Linux Mint 20                | 3         | 1.22%   |
| Linux Mint 19.2              | 3         | 1.22%   |
| Kubuntu 20.04                | 3         | 1.22%   |
| Fedora 33                    | 3         | 1.22%   |
| Arch                         | 3         | 1.22%   |
| Ubuntu MATE 20.04            | 2         | 0.81%   |
| ROSA R9                      | 2         | 0.81%   |
| Pop!_OS 21.04                | 2         | 0.81%   |
| Manjaro 21.0.7               | 2         | 0.81%   |
| Linux Mint 20.1              | 2         | 0.81%   |
| Linux Mint 19.1              | 2         | 0.81%   |
| Kubuntu 21.10                | 2         | 0.81%   |
| Kubuntu 21.04                | 2         | 0.81%   |
| Fedora 35                    | 2         | 0.81%   |
| Fedora 32                    | 2         | 0.81%   |
| Arch Rolling                 | 2         | 0.81%   |
| Xubuntu 20.10                | 1         | 0.41%   |
| Xubuntu 20.04                | 1         | 0.41%   |
| Ubuntu Budgie 22.04          | 1         | 0.41%   |
| Ubuntu Budgie 21.04          | 1         | 0.41%   |
| Ubuntu Budgie 19.10          | 1         | 0.41%   |
| Ubuntu 20.10                 | 1         | 0.41%   |
| Ubuntu 18.10                 | 1         | 0.41%   |
| ROSA R11.1                   | 1         | 0.41%   |
| ROSA R11                     | 1         | 0.41%   |
| RHEL 8                       | 1         | 0.41%   |
| RHEL 7                       | 1         | 0.41%   |
| Peppermint 9                 | 1         | 0.41%   |
| openSUSE Tumbleweed-20201030 | 1         | 0.41%   |
| openSUSE Leap-15.1           | 1         | 0.41%   |
| openSUSE Leap-15.0           | 1         | 0.41%   |
| OpenMandriva 4.50            | 1         | 0.41%   |
| Manjaro 21.2.4               | 1         | 0.41%   |
| Manjaro 21.0.5               | 1         | 0.41%   |
| Manjaro 20.2                 | 1         | 0.41%   |
| Manjaro 19.0.2               | 1         | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 91        | 38.56%  |
| Linux Mint    | 20        | 8.47%   |
| Debian        | 15        | 6.36%   |
| Pop!_OS       | 13        | 5.51%   |
| Fedora        | 12        | 5.08%   |
| Manjaro       | 10        | 4.24%   |
| Kubuntu       | 9         | 3.81%   |
| OpenMandriva  | 7         | 2.97%   |
| Zorin         | 6         | 2.54%   |
| ROSA          | 6         | 2.54%   |
| Lubuntu       | 5         | 2.12%   |
| KDE neon      | 5         | 2.12%   |
| Arch          | 5         | 2.12%   |
| Elementary    | 4         | 1.69%   |
| BlackPanther  | 4         | 1.69%   |
| ArcoLinux     | 4         | 1.69%   |
| openSUSE      | 3         | 1.27%   |
| Endless       | 3         | 1.27%   |
| Xubuntu       | 2         | 0.85%   |
| Ubuntu MATE   | 2         | 0.85%   |
| Ubuntu Budgie | 2         | 0.85%   |
| Clear Linux   | 2         | 0.85%   |
| CentOS        | 2         | 0.85%   |
| RHEL          | 1         | 0.42%   |
| Peppermint    | 1         | 0.42%   |
| LMDE          | 1         | 0.42%   |
| Chrome OS     | 1         | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.3.0-46-generic                | 8         | 3.02%   |
| 5.4.0-42-generic                | 6         | 2.26%   |
| 5.10.14-desktop-1omv4002        | 6         | 2.26%   |
| 5.4.0-52-generic                | 4         | 1.51%   |
| 5.4.0-26-generic                | 4         | 1.51%   |
| 5.4.0-31-generic                | 3         | 1.13%   |
| 5.4.0-29-generic                | 3         | 1.13%   |
| 5.11.0-27-generic               | 3         | 1.13%   |
| 4.19.0-9-amd64                  | 3         | 1.13%   |
| 4.18.16-desktop-1bP             | 3         | 1.13%   |
| 5.8.0-7625-generic              | 2         | 0.75%   |
| 5.8.0-53-generic                | 2         | 0.75%   |
| 5.8.0-43-generic                | 2         | 0.75%   |
| 5.4.0-91-generic                | 2         | 0.75%   |
| 5.4.0-80-generic                | 2         | 0.75%   |
| 5.4.0-7634-generic              | 2         | 0.75%   |
| 5.4.0-73-generic                | 2         | 0.75%   |
| 5.4.0-72-generic                | 2         | 0.75%   |
| 5.4.0-65-generic                | 2         | 0.75%   |
| 5.4.0-62-generic                | 2         | 0.75%   |
| 5.4.0-58-generic                | 2         | 0.75%   |
| 5.4.0-56-generic                | 2         | 0.75%   |
| 5.4.0-54-generic                | 2         | 0.75%   |
| 5.4.0-53-generic                | 2         | 0.75%   |
| 5.4.0-51-generic                | 2         | 0.75%   |
| 5.3.0-40-generic                | 2         | 0.75%   |
| 5.3.0-18-generic                | 2         | 0.75%   |
| 5.13.0-21-generic               | 2         | 0.75%   |
| 5.11.0-41-generic               | 2         | 0.75%   |
| 5.11.0-40-generic               | 2         | 0.75%   |
| 5.11.0-38-generic               | 2         | 0.75%   |
| 5.11.0-37-generic               | 2         | 0.75%   |
| 5.11.0-25-generic               | 2         | 0.75%   |
| 5.10.42-1-MANJARO               | 2         | 0.75%   |
| 5.10.0-8-amd64                  | 2         | 0.75%   |
| 5.0.0-37-generic                | 2         | 0.75%   |
| 5.0.0-25-generic                | 2         | 0.75%   |
| 4.9.41-nrj-desktop-1rosa-x86_64 | 2         | 0.75%   |
| 4.18.0-15-generic               | 2         | 0.75%   |
| 4.15.0-65-generic               | 2         | 0.75%   |
| 4.15.0-51-generic               | 2         | 0.75%   |
| 4.15.0-50-generic               | 2         | 0.75%   |
| 3.10.0-1062.18.1.el7.x86_64     | 2         | 0.75%   |
| 5.9.16-200.fc33.x86_64          | 1         | 0.38%   |
| 5.9.11-3-MANJARO                | 1         | 0.38%   |
| 5.9.1-1-default                 | 1         | 0.38%   |
| 5.9.0-1-amd64                   | 1         | 0.38%   |
| 5.8.18-300.fc33.x86_64          | 1         | 0.38%   |
| 5.8.14-300.fc33.x86_64          | 1         | 0.38%   |
| 5.8.0-7630-generic              | 1         | 0.38%   |
| 5.8.0-55-generic                | 1         | 0.38%   |
| 5.8.0-50-generic                | 1         | 0.38%   |
| 5.8.0-48-generic                | 1         | 0.38%   |
| 5.8.0-44-generic                | 1         | 0.38%   |
| 5.8.0-41-generic                | 1         | 0.38%   |
| 5.8.0-40-generic                | 1         | 0.38%   |
| 5.8.0-33-generic                | 1         | 0.38%   |
| 5.8.0-26-generic                | 1         | 0.38%   |
| 5.8.0-14-generic                | 1         | 0.38%   |
| 5.7.9-200.fc32.x86_64           | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 63        | 25.93%  |
| 4.15.0  | 23        | 9.47%   |
| 5.3.0   | 17        | 7%      |
| 5.11.0  | 17        | 7%      |
| 5.8.0   | 15        | 6.17%   |
| 5.13.0  | 8         | 3.29%   |
| 5.0.0   | 8         | 3.29%   |
| 4.19.0  | 8         | 3.29%   |
| 5.10.14 | 6         | 2.47%   |
| 5.10.0  | 6         | 2.47%   |
| 4.18.0  | 5         | 2.06%   |
| 4.18.16 | 3         | 1.23%   |
| 5.7.9   | 2         | 0.82%   |
| 5.6.7   | 2         | 0.82%   |
| 5.6.15  | 2         | 0.82%   |
| 5.6.0   | 2         | 0.82%   |
| 5.16.11 | 2         | 0.82%   |
| 5.10.42 | 2         | 0.82%   |
| 4.9.60  | 2         | 0.82%   |
| 4.9.41  | 2         | 0.82%   |
| 4.12.14 | 2         | 0.82%   |
| 3.10.0  | 2         | 0.82%   |
| 5.9.16  | 1         | 0.41%   |
| 5.9.11  | 1         | 0.41%   |
| 5.9.1   | 1         | 0.41%   |
| 5.9.0   | 1         | 0.41%   |
| 5.8.18  | 1         | 0.41%   |
| 5.8.14  | 1         | 0.41%   |
| 5.7.7   | 1         | 0.41%   |
| 5.7.12  | 1         | 0.41%   |
| 5.6.14  | 1         | 0.41%   |
| 5.4.85  | 1         | 0.41%   |
| 5.4.40  | 1         | 0.41%   |
| 5.4.24  | 1         | 0.41%   |
| 5.3.12  | 1         | 0.41%   |
| 5.2.17  | 1         | 0.41%   |
| 5.17.4  | 1         | 0.41%   |
| 5.17.3  | 1         | 0.41%   |
| 5.17.1  | 1         | 0.41%   |
| 5.16.15 | 1         | 0.41%   |
| 5.15.7  | 1         | 0.41%   |
| 5.15.5  | 1         | 0.41%   |
| 5.15.25 | 1         | 0.41%   |
| 5.15.15 | 1         | 0.41%   |
| 5.15.12 | 1         | 0.41%   |
| 5.15.0  | 1         | 0.41%   |
| 5.14.7  | 1         | 0.41%   |
| 5.14.5  | 1         | 0.41%   |
| 5.14.13 | 1         | 0.41%   |
| 5.14.11 | 1         | 0.41%   |
| 5.13.9  | 1         | 0.41%   |
| 5.13.6  | 1         | 0.41%   |
| 5.12.8  | 1         | 0.41%   |
| 5.12.4  | 1         | 0.41%   |
| 5.12.2  | 1         | 0.41%   |
| 5.10.85 | 1         | 0.41%   |
| 5.10.24 | 1         | 0.41%   |
| 5.10.2  | 1         | 0.41%   |
| 5.10.12 | 1         | 0.41%   |
| 4.9.76  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 66        | 27.27%  |
| 4.15    | 23        | 9.5%    |
| 5.3     | 18        | 7.44%   |
| 5.10    | 18        | 7.44%   |
| 5.8     | 17        | 7.02%   |
| 5.11    | 17        | 7.02%   |
| 5.13    | 10        | 4.13%   |
| 4.19    | 9         | 3.72%   |
| 5.0     | 8         | 3.31%   |
| 4.18    | 8         | 3.31%   |
| 5.6     | 7         | 2.89%   |
| 5.15    | 6         | 2.48%   |
| 4.9     | 5         | 2.07%   |
| 5.9     | 4         | 1.65%   |
| 5.7     | 4         | 1.65%   |
| 5.14    | 4         | 1.65%   |
| 5.17    | 3         | 1.24%   |
| 5.16    | 3         | 1.24%   |
| 5.12    | 3         | 1.24%   |
| 4.12    | 2         | 0.83%   |
| 3.10    | 2         | 0.83%   |
| 5.2     | 1         | 0.41%   |
| 4.4     | 1         | 0.41%   |
| 4.14    | 1         | 0.41%   |
| 4.13    | 1         | 0.41%   |
| 4.10    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 217       | 94.76%  |
| i686   | 12        | 5.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 111       | 45.68%  |
| Unknown         | 37        | 15.23%  |
| KDE5            | 28        | 11.52%  |
| XFCE            | 15        | 6.17%   |
| X-Cinnamon      | 11        | 4.53%   |
| KDE             | 11        | 4.53%   |
| Cinnamon        | 5         | 2.06%   |
| Pantheon        | 4         | 1.65%   |
| LXQt            | 4         | 1.65%   |
| i3              | 4         | 1.65%   |
| Unity           | 3         | 1.23%   |
| MATE            | 3         | 1.23%   |
| KDE4            | 2         | 0.82%   |
| GNOME Classic   | 2         | 0.82%   |
| Budgie          | 2         | 0.82%   |
| GNOME Flashback | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 196       | 84.48%  |
| Unknown | 21        | 9.05%   |
| Wayland | 13        | 5.6%    |
| Tty     | 2         | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 134       | 57.51%  |
| GDM     | 33        | 14.16%  |
| SDDM    | 27        | 11.59%  |
| LightDM | 19        | 8.15%   |
| TDM     | 12        | 5.15%   |
| GDM3    | 6         | 2.58%   |
| KDM     | 2         | 0.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IE   | 114       | 48.31%  |
| en_US   | 36        | 15.25%  |
| Unknown | 35        | 14.83%  |
| en_GB   | 34        | 14.41%  |
| pl_PL   | 9         | 3.81%   |
| it_IT   | 1         | 0.42%   |
| ga_IE   | 1         | 0.42%   |
| fr_FR   | 1         | 0.42%   |
| fr_BE   | 1         | 0.42%   |
| es_ES   | 1         | 0.42%   |
| en_CA   | 1         | 0.42%   |
| C       | 1         | 0.42%   |
| bg_BG   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 119       | 51.52%  |
| BIOS | 112       | 48.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 182       | 78.79%  |
| Overlay             | 16        | 6.93%   |
| Unknown             | 14        | 6.06%   |
| Btrfs               | 11        | 4.76%   |
| Xfs                 | 4         | 1.73%   |
| Zfs                 | 3         | 1.3%    |
| Fuse.fuse-overlayfs | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 143       | 62.17%  |
| GPT     | 61        | 26.52%  |
| MBR     | 26        | 11.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 203       | 88.26%  |
| Yes       | 27        | 11.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 172       | 74.46%  |
| Yes       | 59        | 25.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 53        | 23.14%  |
| Dell                | 51        | 22.27%  |
| Hewlett-Packard     | 31        | 13.54%  |
| Acer                | 19        | 8.3%    |
| ASUSTek Computer    | 16        | 6.99%   |
| Toshiba             | 10        | 4.37%   |
| Apple               | 9         | 3.93%   |
| PC Specialist       | 4         | 1.75%   |
| TUXEDO              | 3         | 1.31%   |
| Samsung Electronics | 3         | 1.31%   |
| Notebook            | 3         | 1.31%   |
| Medion              | 3         | 1.31%   |
| Timi                | 2         | 0.87%   |
| System76            | 2         | 0.87%   |
| MSI                 | 2         | 0.87%   |
| HUAWEI              | 2         | 0.87%   |
| Entroware           | 2         | 0.87%   |
| eMachines           | 2         | 0.87%   |
| Chuwi               | 2         | 0.87%   |
| Sony                | 1         | 0.44%   |
| SLIMBOOK            | 1         | 0.44%   |
| Schenker            | 1         | 0.44%   |
| Packard Bell        | 1         | 0.44%   |
| Microtech           | 1         | 0.44%   |
| Gigabyte Technology | 1         | 0.44%   |
| Fujitsu Siemens     | 1         | 0.44%   |
| AVITA               | 1         | 0.44%   |
| Alienware           | 1         | 0.44%   |
| Advent              | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo V145-15AST 81MT                   | 3         | 1.31%   |
| TUXEDO Pulse 15 Gen1                     | 2         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 3443CTO        | 2         | 0.87%   |
| Lenovo IdeaPad 510-15ISK 80SR            | 2         | 0.87%   |
| HP Notebook                              | 2         | 0.87%   |
| Dell XPS 13 9310                         | 2         | 0.87%   |
| Dell XPS 13 9300                         | 2         | 0.87%   |
| Dell XPS 13 7390                         | 2         | 0.87%   |
| Dell Precision 5550                      | 2         | 0.87%   |
| Dell Latitude E6230                      | 2         | 0.87%   |
| Dell Inspiron 13-5378                    | 2         | 0.87%   |
| Apple MacBook6,1                         | 2         | 0.87%   |
| Acer Aspire E5-575G                      | 2         | 0.87%   |
| TUXEDO InfinityBook Pro 15 v5            | 1         | 0.44%   |
| Toshiba TECRA R850                       | 1         | 0.44%   |
| Toshiba TECRA M4                         | 1         | 0.44%   |
| Toshiba Satellite Pro R50-B              | 1         | 0.44%   |
| Toshiba Satellite Pro C660               | 1         | 0.44%   |
| Toshiba Satellite L500                   | 1         | 0.44%   |
| Toshiba Satellite L50-C                  | 1         | 0.44%   |
| Toshiba Satellite L50-B                  | 1         | 0.44%   |
| Toshiba Satellite C50-B                  | 1         | 0.44%   |
| Toshiba Satellite A300                   | 1         | 0.44%   |
| Toshiba PORTEGE R830                     | 1         | 0.44%   |
| Timi TM1703                              | 1         | 0.44%   |
| Timi TM1607                              | 1         | 0.44%   |
| System76 Galago Pro                      | 1         | 0.44%   |
| System76 Bonobo Extreme                  | 1         | 0.44%   |
| Sony VPCCB35FG                           | 1         | 0.44%   |
| SLIMBOOK PROX15                          | 1         | 0.44%   |
| Schenker XMG NEO (TGL/M21)               | 1         | 0.44%   |
| Samsung N150/N210/N220                   | 1         | 0.44%   |
| Samsung 550P5C/550P7C                    | 1         | 0.44%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 0.44%   |
| PC Specialist TF                         | 1         | 0.44%   |
| PC Specialist PCX0DX                     | 1         | 0.44%   |
| PC Specialist NH5xAx                     | 1         | 0.44%   |
| PC Specialist N150CU                     | 1         | 0.44%   |
| Packard Bell EasyNote TK85               | 1         | 0.44%   |
| Notebook P65_P67RGRERA                   | 1         | 0.44%   |
| Notebook P15SM                           | 1         | 0.44%   |
| Notebook NL40_50CU                       | 1         | 0.44%   |
| MSI WS65 9TK                             | 1         | 0.44%   |
| MSI Stealth GS66 12UGS                   | 1         | 0.44%   |
| Microtech e-book Lite                    | 1         | 0.44%   |
| Medion Erazer X7843 MD99945              | 1         | 0.44%   |
| Medion E6239 MD99452                     | 1         | 0.44%   |
| Medion Akoya E6239                       | 1         | 0.44%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 0.44%   |
| Lenovo V15-IIL 82C5                      | 1         | 0.44%   |
| Lenovo V110-15ISK 80TL                   | 1         | 0.44%   |
| Lenovo U410                              | 1         | 0.44%   |
| Lenovo ThinkPad X260 20F5S13K00          | 1         | 0.44%   |
| Lenovo ThinkPad X250 20CLS3ST01          | 1         | 0.44%   |
| Lenovo ThinkPad X230 Tablet 34382BG      | 1         | 0.44%   |
| Lenovo ThinkPad X220 4291W99             | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES0410J | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 34431C4        | 1         | 0.44%   |
| Lenovo ThinkPad W530 24491D1             | 1         | 0.44%   |
| Lenovo ThinkPad T520 424329U             | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 28        | 12.23%  |
| Dell Latitude         | 22        | 9.61%   |
| Acer Aspire           | 14        | 6.11%   |
| Lenovo IdeaPad        | 12        | 5.24%   |
| Dell Inspiron         | 11        | 4.8%    |
| Dell XPS              | 10        | 4.37%   |
| HP EliteBook          | 8         | 3.49%   |
| Toshiba Satellite     | 7         | 3.06%   |
| HP Pavilion           | 7         | 3.06%   |
| Dell Precision        | 5         | 2.18%   |
| Lenovo V145-15AST     | 3         | 1.31%   |
| HP Presario           | 3         | 1.31%   |
| HP Laptop             | 3         | 1.31%   |
| Apple MacBookPro5     | 3         | 1.31%   |
| TUXEDO Pulse          | 2         | 0.87%   |
| Toshiba TECRA         | 2         | 0.87%   |
| HP Notebook           | 2         | 0.87%   |
| Dell Vostro           | 2         | 0.87%   |
| ASUS ZenBook          | 2         | 0.87%   |
| ASUS TUF              | 2         | 0.87%   |
| ASUS ROG              | 2         | 0.87%   |
| Apple MacBook6        | 2         | 0.87%   |
| TUXEDO InfinityBook   | 1         | 0.44%   |
| Toshiba PORTEGE       | 1         | 0.44%   |
| Timi TM1703           | 1         | 0.44%   |
| Timi TM1607           | 1         | 0.44%   |
| System76 Galago       | 1         | 0.44%   |
| System76 Bonobo       | 1         | 0.44%   |
| Sony VPCCB35FG        | 1         | 0.44%   |
| SLIMBOOK PROX15       | 1         | 0.44%   |
| Schenker XMG          | 1         | 0.44%   |
| Samsung N150          | 1         | 0.44%   |
| Samsung 550P5C        | 1         | 0.44%   |
| Samsung 350V5C        | 1         | 0.44%   |
| PC Specialist TF      | 1         | 0.44%   |
| PC Specialist PCX0DX  | 1         | 0.44%   |
| PC Specialist NH5xAx  | 1         | 0.44%   |
| PC Specialist N150CU  | 1         | 0.44%   |
| Packard Bell EasyNote | 1         | 0.44%   |
| Notebook P65          | 1         | 0.44%   |
| Notebook P15SM        | 1         | 0.44%   |
| Notebook NL40         | 1         | 0.44%   |
| MSI WS65              | 1         | 0.44%   |
| MSI Stealth           | 1         | 0.44%   |
| Microtech e-book      | 1         | 0.44%   |
| Medion Erazer         | 1         | 0.44%   |
| Medion E6239          | 1         | 0.44%   |
| Medion Akoya          | 1         | 0.44%   |
| Lenovo Y520-15IKBN    | 1         | 0.44%   |
| Lenovo V15-IIL        | 1         | 0.44%   |
| Lenovo V110-15ISK     | 1         | 0.44%   |
| Lenovo U410           | 1         | 0.44%   |
| Lenovo Legion         | 1         | 0.44%   |
| Lenovo IdeaPadFlex    | 1         | 0.44%   |
| Lenovo G580           | 1         | 0.44%   |
| Lenovo G550           | 1         | 0.44%   |
| Lenovo G500           | 1         | 0.44%   |
| Lenovo B50-30         | 1         | 0.44%   |
| HUAWEI NBLK-WAX9X     | 1         | 0.44%   |
| HUAWEI BOHL-WXX9      | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 24        | 10.48%  |
| 2020 | 21        | 9.17%   |
| 2017 | 18        | 7.86%   |
| 2012 | 18        | 7.86%   |
| 2016 | 17        | 7.42%   |
| 2013 | 17        | 7.42%   |
| 2011 | 17        | 7.42%   |
| 2018 | 15        | 6.55%   |
| 2015 | 14        | 6.11%   |
| 2009 | 14        | 6.11%   |
| 2010 | 12        | 5.24%   |
| 2008 | 12        | 5.24%   |
| 2021 | 10        | 4.37%   |
| 2014 | 10        | 4.37%   |
| 2007 | 6         | 2.62%   |
| 2006 | 2         | 0.87%   |
| 2005 | 1         | 0.44%   |
| 2003 | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 229       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 200       | 86.21%  |
| Enabled  | 32        | 13.79%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 229       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 67        | 28.76%  |
| 3.01-4.0    | 52        | 22.32%  |
| 16.01-24.0  | 39        | 16.74%  |
| 8.01-16.0   | 35        | 15.02%  |
| 32.01-64.0  | 19        | 8.15%   |
| 1.01-2.0    | 9         | 3.86%   |
| 2.01-3.0    | 5         | 2.15%   |
| 24.01-32.0  | 2         | 0.86%   |
| 64.01-256.0 | 2         | 0.86%   |
| 0.51-1.0    | 2         | 0.86%   |
| 0.01-0.5    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 87        | 34.8%   |
| 2.01-3.0   | 66        | 26.4%   |
| 3.01-4.0   | 41        | 16.4%   |
| 4.01-8.0   | 26        | 10.4%   |
| 0.51-1.0   | 21        | 8.4%    |
| 8.01-16.0  | 4         | 1.6%    |
| 16.01-24.0 | 3         | 1.2%    |
| 0.01-0.5   | 2         | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 172       | 73.19%  |
| 2      | 52        | 22.13%  |
| 3      | 10        | 4.26%   |
| 0      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 139       | 59.91%  |
| Yes       | 93        | 40.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 81.66%  |
| No        | 42        | 18.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 99.13%  |
| No        | 2         | 0.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 74.03%  |
| No        | 60        | 25.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ireland | 229       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Dublin         | 141       | 59.49%  |
| Naas           | 8         | 3.38%   |
| Cork           | 8         | 3.38%   |
| Galway         | 7         | 2.95%   |
| Navan          | 5         | 2.11%   |
| Kilkenny       | 4         | 1.69%   |
| Ennis          | 4         | 1.69%   |
| Portlaoise     | 3         | 1.27%   |
| Nenagh         | 3         | 1.27%   |
| Limerick       | 3         | 1.27%   |
| Enniscorthy    | 3         | 1.27%   |
| Drogheda       | 3         | 1.27%   |
| Westport       | 2         | 0.84%   |
| Midleton       | 2         | 0.84%   |
| Mallow         | 2         | 0.84%   |
| Macroom        | 2         | 0.84%   |
| Clonsilla      | 2         | 0.84%   |
| Carrigaline    | 2         | 0.84%   |
| Athlone        | 2         | 0.84%   |
| Wicklow        | 1         | 0.42%   |
| Wexford        | 1         | 0.42%   |
| Waterford      | 1         | 0.42%   |
| Tuam           | 1         | 0.42%   |
| Tipperary      | 1         | 0.42%   |
| Tallaght       | 1         | 0.42%   |
| Swords         | 1         | 0.42%   |
| Sligo          | 1         | 0.42%   |
| Shannon        | 1         | 0.42%   |
| Roscommon      | 1         | 0.42%   |
| Rathcoole      | 1         | 0.42%   |
| New Ross       | 1         | 0.42%   |
| Malahide       | 1         | 0.42%   |
| Letterkenny    | 1         | 0.42%   |
| Leixlip        | 1         | 0.42%   |
| Killorglin     | 1         | 0.42%   |
| Kilcock        | 1         | 0.42%   |
| Kenmare        | 1         | 0.42%   |
| Harristown     | 1         | 0.42%   |
| Gorey          | 1         | 0.42%   |
| Enfield        | 1         | 0.42%   |
| Droichead Nua  | 1         | 0.42%   |
| Donegal        | 1         | 0.42%   |
| Clonmel        | 1         | 0.42%   |
| Clonakilty     | 1         | 0.42%   |
| Cavan          | 1         | 0.42%   |
| Ballymote      | 1         | 0.42%   |
| Ballinagleragh | 1         | 0.42%   |
| Ballina        | 1         | 0.42%   |
| Balbriggan     | 1         | 0.42%   |
| Athy           | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 55        | 75     | 19.23%  |
| WDC                       | 41        | 48     | 14.34%  |
| Seagate                   | 26        | 33     | 9.09%   |
| Toshiba                   | 24        | 28     | 8.39%   |
| Unknown                   | 20        | 26     | 6.99%   |
| Hitachi                   | 19        | 21     | 6.64%   |
| SanDisk                   | 15        | 15     | 5.24%   |
| Crucial                   | 12        | 19     | 4.2%    |
| HGST                      | 9         | 9      | 3.15%   |
| Kingston                  | 8         | 10     | 2.8%    |
| Micron Technology         | 7         | 8      | 2.45%   |
| Intel                     | 7         | 10     | 2.45%   |
| Fujitsu                   | 6         | 7      | 2.1%    |
| SK Hynix                  | 5         | 5      | 1.75%   |
| PNY                       | 3         | 3      | 1.05%   |
| Union Memory              | 2         | 2      | 0.7%    |
| Silicon Motion            | 2         | 3      | 0.7%    |
| KingSpec                  | 2         | 2      | 0.7%    |
| Apple                     | 2         | 2      | 0.7%    |
| A-DATA Technology         | 2         | 2      | 0.7%    |
| Zheino                    | 1         | 1      | 0.35%   |
| W800S                     | 1         | 2      | 0.35%   |
| Verbatim                  | 1         | 1      | 0.35%   |
| Sabrent                   | 1         | 2      | 0.35%   |
| QNAP                      | 1         | 1      | 0.35%   |
| PLEXTOR                   | 1         | 1      | 0.35%   |
| Phison                    | 1         | 1      | 0.35%   |
| OCZ                       | 1         | 1      | 0.35%   |
| Micron/Crucial Technology | 1         | 1      | 0.35%   |
| LITEONIT                  | 1         | 1      | 0.35%   |
| LITEON                    | 1         | 1      | 0.35%   |
| LaCie                     | 1         | 1      | 0.35%   |
| KIOXIA                    | 1         | 1      | 0.35%   |
| Integral                  | 1         | 1      | 0.35%   |
| FORESEE                   | 1         | 1      | 0.35%   |
| Emtec                     | 1         | 2      | 0.35%   |
| DOGFISH                   | 1         | 1      | 0.35%   |
| China                     | 1         | 4      | 0.35%   |
| ADplus                    | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 5         | 1.69%   |
| Unknown MMC Card  64GB             | 4         | 1.35%   |
| Toshiba MQ01ABD100 1TB             | 4         | 1.35%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 3         | 1.01%   |
| Unknown MMC Card  32GB             | 3         | 1.01%   |
| Sandisk NVMe SSD Drive 512GB       | 3         | 1.01%   |
| Samsung SSD 850 EVO 250GB          | 3         | 1.01%   |
| Samsung NVMe SSD Drive 512GB       | 3         | 1.01%   |
| Samsung NVMe SSD Drive 500GB       | 3         | 1.01%   |
| PNY CS900 120GB SSD                | 3         | 1.01%   |
| Kingston SA400S37480G 480GB SSD    | 3         | 1.01%   |
| Hitachi HTS723232A7A364 320GB      | 3         | 1.01%   |
| HGST HTS721010A9E630 1TB           | 3         | 1.01%   |
| HGST HTS545050A7E680 500GB         | 3         | 1.01%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD     | 2         | 0.68%   |
| WDC WD10JPVX-00JC3T0 1TB           | 2         | 0.68%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.68%   |
| Unknown HBG4a2  32GB               | 2         | 0.68%   |
| Toshiba MQ04ABF100 1TB             | 2         | 0.68%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.68%   |
| Seagate ST9500420ASG 500GB         | 2         | 0.68%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.68%   |
| Seagate ST500LM000-1EJ162 500GB    | 2         | 0.68%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2         | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.68%   |
| SanDisk X400 2.5 7MM 256GB SSD     | 2         | 0.68%   |
| SanDisk SD5SG2128G1052E 128GB SSD  | 2         | 0.68%   |
| Samsung SSD 970 EVO Plus 500GB     | 2         | 0.68%   |
| Samsung SSD 840 EVO 250GB          | 2         | 0.68%   |
| Samsung NVMe SSD Drive 256GB       | 2         | 0.68%   |
| Micron 2300 NVMe 512GB             | 2         | 0.68%   |
| KingSpec NT-512 512GB SSD          | 2         | 0.68%   |
| Intel NVMe SSD Drive 512GB         | 2         | 0.68%   |
| Hitachi HTS547575A9E384 752GB      | 2         | 0.68%   |
| Hitachi HTS545050B9A300 500GB      | 2         | 0.68%   |
| Hitachi HTS545025B9A300 250GB      | 2         | 0.68%   |
| HGST HTS541010A9E680 1TB           | 2         | 0.68%   |
| Fujitsu MHW2120BH 120GB            | 2         | 0.68%   |
| Crucial M4-CT128M4SSD2 128GB       | 2         | 0.68%   |
| Crucial CT1000MX500SSD1 1TB        | 2         | 0.68%   |
| Zheino CHN 25SATA01M 030 32GB SSD  | 1         | 0.34%   |
| WDC WDS250G2B0C-00PXH0 250GB       | 1         | 0.34%   |
| WDC WD7500BPKT-80PK4T0 752GB       | 1         | 0.34%   |
| WDC WD6400BPVT-22HXZT3 640GB       | 1         | 0.34%   |
| WDC WD600VE-75HDT1 64GB            | 1         | 0.34%   |
| WDC WD5000LPVX-00V0TT0 500GB       | 1         | 0.34%   |
| WDC WD5000LPVT-08G33T1 500GB       | 1         | 0.34%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 0.34%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 0.34%   |
| WDC WD5000BPVX-00JC3T0 500GB       | 1         | 0.34%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 0.34%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 0.34%   |
| WDC WD3200LPVX-75V0TT0 320GB       | 1         | 0.34%   |
| WDC WD3200BPVT-00HXZT1 320GB       | 1         | 0.34%   |
| WDC WD3200BEVT-75ZCT1 320GB        | 1         | 0.34%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 0.34%   |
| WDC WD3200BEKT-60V5T1 320GB        | 1         | 0.34%   |
| WDC WD2500BPVT-00JJ5T0 250GB       | 1         | 0.34%   |
| WDC WD2500BEVT-22A23T0 250GB       | 1         | 0.34%   |
| WDC WD1600BEVS-07RST0 160GB        | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 29     | 24.3%   |
| Seagate             | 26        | 33     | 24.3%   |
| Hitachi             | 19        | 21     | 17.76%  |
| Toshiba             | 14        | 15     | 13.08%  |
| HGST                | 9         | 9      | 8.41%   |
| Fujitsu             | 6         | 7      | 5.61%   |
| Samsung Electronics | 3         | 4      | 2.8%    |
| Sabrent             | 1         | 2      | 0.93%   |
| QNAP                | 1         | 1      | 0.93%   |
| LaCie               | 1         | 1      | 0.93%   |
| Apple               | 1         | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 32     | 31.11%  |
| SanDisk             | 12        | 12     | 13.33%  |
| Crucial             | 11        | 18     | 12.22%  |
| Kingston            | 8         | 10     | 8.89%   |
| WDC                 | 5         | 8      | 5.56%   |
| Toshiba             | 3         | 4      | 3.33%   |
| PNY                 | 3         | 3      | 3.33%   |
| Micron Technology   | 2         | 2      | 2.22%   |
| KingSpec            | 2         | 2      | 2.22%   |
| Zheino              | 1         | 1      | 1.11%   |
| W800S               | 1         | 2      | 1.11%   |
| Verbatim            | 1         | 1      | 1.11%   |
| SK Hynix            | 1         | 1      | 1.11%   |
| PLEXTOR             | 1         | 1      | 1.11%   |
| OCZ                 | 1         | 1      | 1.11%   |
| LITEONIT            | 1         | 1      | 1.11%   |
| LITEON              | 1         | 1      | 1.11%   |
| Intel               | 1         | 1      | 1.11%   |
| Integral            | 1         | 1      | 1.11%   |
| FORESEE             | 1         | 1      | 1.11%   |
| Emtec               | 1         | 2      | 1.11%   |
| DOGFISH             | 1         | 1      | 1.11%   |
| China               | 1         | 4      | 1.11%   |
| Apple               | 1         | 1      | 1.11%   |
| A-DATA Technology   | 1         | 1      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 100       | 123    | 37.17%  |
| SSD     | 83        | 112    | 30.86%  |
| NVMe    | 65        | 91     | 24.16%  |
| MMC     | 18        | 24     | 6.69%   |
| Unknown | 3         | 3      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 168       | 230    | 65.63%  |
| NVMe | 65        | 91     | 25.39%  |
| MMC  | 18        | 24     | 7.03%   |
| SAS  | 5         | 8      | 1.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 161    | 68.89%  |
| 0.51-1.0   | 49        | 63     | 27.22%  |
| 1.01-2.0   | 5         | 8      | 2.78%   |
| 3.01-4.0   | 1         | 1      | 0.56%   |
| 2.01-3.0   | 1         | 2      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 67        | 28.51%  |
| 101-250        | 61        | 25.96%  |
| 501-1000       | 27        | 11.49%  |
| 51-100         | 25        | 10.64%  |
| 1-20           | 23        | 9.79%   |
| 1001-2000      | 14        | 5.96%   |
| 21-50          | 7         | 2.98%   |
| Unknown        | 7         | 2.98%   |
| More than 3000 | 2         | 0.85%   |
| 2001-3000      | 2         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 103       | 41.37%  |
| 101-250        | 41        | 16.47%  |
| 21-50          | 38        | 15.26%  |
| 51-100         | 30        | 12.05%  |
| 251-500        | 17        | 6.83%   |
| 501-1000       | 9         | 3.61%   |
| Unknown        | 7         | 2.81%   |
| 1001-2000      | 3         | 1.2%    |
| More than 3000 | 1         | 0.4%    |

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
| Hitachi HTS545025B9SA02 250GB                  | 1         | 1      | 6.25%   |
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
| Hitachi             | 6         | 6      | 37.5%   |
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
| Hitachi             | 6         | 6      | 42.86%  |
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
| HDD  | 11        | 14     | 84.62%  |
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
| Detected | 146       | 227    | 61.09%  |
| Works    | 80        | 110    | 33.47%  |
| Malfunc  | 13        | 16     | 5.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 166       | 62.17%  |
| Samsung Electronics          | 26        | 9.74%   |
| AMD                          | 26        | 9.74%   |
| Sandisk                      | 14        | 5.24%   |
| Nvidia                       | 8         | 3%      |
| Toshiba America Info Systems | 7         | 2.62%   |
| Micron Technology            | 5         | 1.87%   |
| SK Hynix                     | 4         | 1.5%    |
| Union Memory (Shenzhen)      | 2         | 0.75%   |
| Silicon Motion               | 2         | 0.75%   |
| Micron/Crucial Technology    | 2         | 0.75%   |
| Silicon Image                | 1         | 0.37%   |
| Phison Electronics           | 1         | 0.37%   |
| KIOXIA                       | 1         | 0.37%   |
| ADATA Technology             | 1         | 0.37%   |
| Adaptec                      | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 23        | 8.07%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 7.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 6.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 4.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 4.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 3.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 2.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 2.11%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 2.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.11%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 1.75%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.75%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 1.75%   |
| Micron Non-Volatile memory controller                                            | 5         | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.4%    |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.4%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.05%   |
| Intel SSD 660P Series                                                            | 3         | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 1.05%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.05%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.7%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 2         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.7%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.7%    |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.7%    |
| Sandisk Non-Volatile memory controller                                           | 2         | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.7%    |
| Intel Non-Volatile memory controller                                             | 2         | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.7%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.35%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.35%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.35%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.35%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.35%   |
| Silicon Image PCI0646                                                            | 1         | 0.35%   |
| Samsung Electronics SATA controller                                              | 1         | 0.35%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.35%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.35%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.35%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 0.35%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.35%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.35%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 170       | 62.73%  |
| NVMe | 65        | 23.99%  |
| IDE  | 19        | 7.01%   |
| RAID | 16        | 5.9%    |
| SCSI | 1         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 193       | 84.28%  |
| AMD    | 36        | 15.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 2.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 2.18%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.75%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.31%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.31%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 1.31%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.31%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.31%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.31%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 1.31%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 1.31%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.31%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 1.31%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.31%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.31%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 1.31%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.87%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.87%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.87%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.87%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.87%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.87%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.87%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.87%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 2         | 0.87%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.87%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 0.87%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.87%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.87%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.87%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 0.87%   |
| Intel Pentium M processor 2.00GHz             | 1         | 0.44%   |
| Intel Pentium III Mobile CPU 1000MHz          | 1         | 0.44%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.44%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.44%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.44%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.44%   |
| Intel Genuine CPU T2130 @ 1.86GHz             | 1         | 0.44%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.44%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.44%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.44%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.44%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.44%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.44%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.44%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.44%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.44%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.44%   |
| Intel Core i7-6820HK CPU @ 2.70GHz            | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 57        | 24.89%  |
| Intel Core i5           | 53        | 23.14%  |
| Intel Core 2 Duo        | 18        | 7.86%   |
| Intel Core i3           | 16        | 6.99%   |
| Other                   | 14        | 6.11%   |
| Intel Celeron           | 14        | 6.11%   |
| AMD Ryzen 5             | 7         | 3.06%   |
| Intel Atom              | 6         | 2.62%   |
| AMD Ryzen 7             | 6         | 2.62%   |
| Intel Pentium           | 4         | 1.75%   |
| AMD A8                  | 4         | 1.75%   |
| Intel Pentium Dual-Core | 2         | 0.87%   |
| Intel Core i9           | 2         | 0.87%   |
| Intel Core 2            | 2         | 0.87%   |
| Intel Celeron Dual-Core | 2         | 0.87%   |
| AMD Ryzen 9             | 2         | 0.87%   |
| Intel Pentium M         | 1         | 0.44%   |
| Intel Pentium III       | 1         | 0.44%   |
| Intel Genuine           | 1         | 0.44%   |
| Intel Core m7           | 1         | 0.44%   |
| Intel Core m5           | 1         | 0.44%   |
| Intel Core m3           | 1         | 0.44%   |
| Intel Core 2 Extreme    | 1         | 0.44%   |
| Intel Celeron M         | 1         | 0.44%   |
| AMD Turion 64 X2 Mobile | 1         | 0.44%   |
| AMD Sempron             | 1         | 0.44%   |
| AMD Ryzen 5 PRO         | 1         | 0.44%   |
| AMD Ryzen 3             | 1         | 0.44%   |
| AMD Phenom II           | 1         | 0.44%   |
| AMD FX                  | 1         | 0.44%   |
| AMD E2                  | 1         | 0.44%   |
| AMD E                   | 1         | 0.44%   |
| AMD Athlon 64 X2        | 1         | 0.44%   |
| AMD Athlon              | 1         | 0.44%   |
| AMD A6                  | 1         | 0.44%   |
| AMD A10                 | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 126       | 55.02%  |
| 4      | 71        | 31%     |
| 8      | 11        | 4.8%    |
| 6      | 9         | 3.93%   |
| 1      | 9         | 3.93%   |
| 14     | 1         | 0.44%   |
| 12     | 1         | 0.44%   |
| 3      | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 229       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 161       | 70.31%  |
| 1      | 68        | 29.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 220       | 95.24%  |
| Unknown        | 8         | 3.46%   |
| 32-bit         | 3         | 1.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 18.38%  |
| 0x306a9    | 16        | 6.84%   |
| 0x806ec    | 12        | 5.13%   |
| 0x1067a    | 12        | 5.13%   |
| 0x806e9    | 11        | 4.7%    |
| 0x206a7    | 11        | 4.7%    |
| 0x40651    | 8         | 3.42%   |
| 0x806ea    | 7         | 2.99%   |
| 0x406e3    | 7         | 2.99%   |
| 0x806c1    | 6         | 2.56%   |
| 0x306d4    | 6         | 2.56%   |
| 0xa0652    | 5         | 2.14%   |
| 0x30678    | 5         | 2.14%   |
| 0x20655    | 5         | 2.14%   |
| 0x10676    | 5         | 2.14%   |
| 0x06006705 | 5         | 2.14%   |
| 0x906ea    | 4         | 1.71%   |
| 0x906e9    | 4         | 1.71%   |
| 0x6fd      | 4         | 1.71%   |
| 0x406c4    | 4         | 1.71%   |
| 0x306c3    | 4         | 1.71%   |
| 0x706e5    | 3         | 1.28%   |
| 0x106ca    | 3         | 1.28%   |
| 0x08108109 | 3         | 1.28%   |
| 0x08108102 | 3         | 1.28%   |
| 0x806d1    | 2         | 0.85%   |
| 0x6f6      | 2         | 0.85%   |
| 0x6d8      | 2         | 0.85%   |
| 0x506e3    | 2         | 0.85%   |
| 0x20652    | 2         | 0.85%   |
| 0x0a50000c | 2         | 0.85%   |
| 0x08600103 | 2         | 0.85%   |
| 0x07030106 | 2         | 0.85%   |
| 0x06001119 | 2         | 0.85%   |
| 0x906ed    | 1         | 0.43%   |
| 0x906a3    | 1         | 0.43%   |
| 0x706a8    | 1         | 0.43%   |
| 0x706a1    | 1         | 0.43%   |
| 0x6fb      | 1         | 0.43%   |
| 0x6ec      | 1         | 0.43%   |
| 0x6b1      | 1         | 0.43%   |
| 0x506c9    | 1         | 0.43%   |
| 0x406c3    | 1         | 0.43%   |
| 0x106e5    | 1         | 0.43%   |
| 0x0a50000b | 1         | 0.43%   |
| 0x08701013 | 1         | 0.43%   |
| 0x08600106 | 1         | 0.43%   |
| 0x08600104 | 1         | 0.43%   |
| 0x0810100b | 1         | 0.43%   |
| 0x07030105 | 1         | 0.43%   |
| 0x06006115 | 1         | 0.43%   |
| 0x0600610e | 1         | 0.43%   |
| 0x05000119 | 1         | 0.43%   |
| 0x010000c8 | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 18.78%  |
| IvyBridge        | 21        | 9.17%   |
| Penryn           | 17        | 7.42%   |
| SandyBridge      | 16        | 6.99%   |
| Skylake          | 15        | 6.55%   |
| Silvermont       | 13        | 5.68%   |
| Haswell          | 13        | 5.68%   |
| Westmere         | 10        | 4.37%   |
| Core             | 8         | 3.49%   |
| Zen+             | 7         | 3.06%   |
| Excavator        | 7         | 3.06%   |
| Broadwell        | 7         | 3.06%   |
| Zen 2            | 6         | 2.62%   |
| TigerLake        | 6         | 2.62%   |
| IceLake          | 6         | 2.62%   |
| CometLake        | 5         | 2.18%   |
| P6               | 4         | 1.75%   |
| Zen 3            | 3         | 1.31%   |
| Puma             | 3         | 1.31%   |
| K8 Hammer        | 3         | 1.31%   |
| Goldmont plus    | 3         | 1.31%   |
| Bonnell          | 3         | 1.31%   |
| Piledriver       | 2         | 0.87%   |
| K10              | 2         | 0.87%   |
| Bobcat           | 2         | 0.87%   |
| Zen              | 1         | 0.44%   |
| Nehalem          | 1         | 0.44%   |
| Goldmont         | 1         | 0.44%   |
| Alderlake Hybrid | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 162       | 58.48%  |
| Nvidia | 74        | 26.71%  |
| AMD    | 41        | 14.8%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 6.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.55%   |
| Intel HD Graphics 620                                                                    | 10        | 3.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.8%    |
| Intel UHD Graphics 620                                                                   | 7         | 2.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.45%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.1%    |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.75%   |
| Intel HD Graphics 630                                                                    | 5         | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.75%   |
| AMD Renoir                                                                               | 5         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.4%    |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 1.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.4%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.05%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.05%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.05%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.05%   |
| AMD Cezanne                                                                              | 3         | 1.05%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.7%    |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.7%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.7%    |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.7%    |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.7%    |
| Nvidia GF108M [NVS 5400M]                                                                | 2         | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.7%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.7%    |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.7%    |
| Intel HD Graphics 530                                                                    | 2         | 0.7%    |
| Intel HD Graphics 515                                                                    | 2         | 0.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.7%    |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.7%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.7%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.7%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.35%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.35%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.35%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 1         | 0.35%   |
| Nvidia NV43M [GeForce Go6200 TE / 6600 TE]                                               | 1         | 0.35%   |
| Nvidia NV11M [GeForce2 Go]                                                               | 1         | 0.35%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.35%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.35%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.35%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 120       | 52.4%   |
| Intel + Nvidia | 40        | 17.47%  |
| 1 x AMD        | 28        | 12.23%  |
| 1 x Nvidia     | 27        | 11.79%  |
| AMD + Nvidia   | 6         | 2.62%   |
| 2 x AMD        | 5         | 2.18%   |
| Intel + AMD    | 2         | 0.87%   |
| 2 x Nvidia     | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 184       | 79.65%  |
| Proprietary | 39        | 16.88%  |
| Unknown     | 8         | 3.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 56.6%   |
| 0.01-0.5   | 40        | 17.02%  |
| 3.01-4.0   | 19        | 8.09%   |
| 1.01-2.0   | 19        | 8.09%   |
| 0.51-1.0   | 15        | 6.38%   |
| 5.01-6.0   | 4         | 1.7%    |
| 7.01-8.0   | 3         | 1.28%   |
| 2.01-3.0   | 2         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 47        | 18.73%  |
| AU Optronics            | 44        | 17.53%  |
| Chimei Innolux          | 28        | 11.16%  |
| BOE                     | 26        | 10.36%  |
| Samsung Electronics     | 22        | 8.76%   |
| Sharp                   | 17        | 6.77%   |
| Dell                    | 12        | 4.78%   |
| Apple                   | 8         | 3.19%   |
| Lenovo                  | 6         | 2.39%   |
| Chi Mei Optoelectronics | 6         | 2.39%   |
| PANDA                   | 4         | 1.59%   |
| Hewlett-Packard         | 4         | 1.59%   |
| Acer                    | 4         | 1.59%   |
| Philips                 | 3         | 1.2%    |
| AOC                     | 3         | 1.2%    |
| LG Philips              | 2         | 0.8%    |
| InfoVision              | 2         | 0.8%    |
| CPT                     | 2         | 0.8%    |
| BOE Technology Group    | 2         | 0.8%    |
| ___                     | 1         | 0.4%    |
| Unknown                 | 1         | 0.4%    |
| Toshiba                 | 1         | 0.4%    |
| Quanta Display          | 1         | 0.4%    |
| LGD                     | 1         | 0.4%    |
| Lenovo Group Limited    | 1         | 0.4%    |
| Iiyama                  | 1         | 0.4%    |
| Goldstar                | 1         | 0.4%    |
| BenQ                    | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.55%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 1.16%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 3         | 1.16%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.78%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.78%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch               | 2         | 0.78%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.78%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.78%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 2         | 0.78%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 2         | 0.78%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.78%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 2         | 0.78%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch            | 2         | 0.78%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                     | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 2         | 0.78%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 0.78%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.39%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.39%   |
| Toshiba Internal LCD TOS5091 1366x768 340x190mm 15.3-inch             | 1         | 0.39%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP14A1 3840x2160 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP138E 1600x1200 304x228mm 15.0-inch               | 1         | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.39%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.39%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 1         | 0.39%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4C47 1680x1050 367x229mm 17.0-inch | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3258 1440x900 367x230mm 17.1-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC5451 1366x768 344x194mm 15.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 98        | 40.5%   |
| 1366x768 (WXGA)    | 72        | 29.75%  |
| 1600x900 (HD+)     | 12        | 4.96%   |
| 1280x800 (WXGA)    | 12        | 4.96%   |
| 1440x900 (WXGA+)   | 9         | 3.72%   |
| 3840x2160 (4K)     | 8         | 3.31%   |
| 1920x1200 (WUXGA)  | 7         | 2.89%   |
| 3440x1440          | 4         | 1.65%   |
| 2560x1440 (QHD)    | 4         | 1.65%   |
| 3840x2400          | 3         | 1.24%   |
| 1024x600           | 3         | 1.24%   |
| 3200x1800 (QHD+)   | 2         | 0.83%   |
| 1600x1200          | 2         | 0.83%   |
| 1360x768           | 2         | 0.83%   |
| 2560x1600          | 1         | 0.41%   |
| 2160x1440          | 1         | 0.41%   |
| 1680x1050 (WSXGA+) | 1         | 0.41%   |
| 1280x1024 (SXGA)   | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 109       | 42.41%  |
| 14      | 33        | 12.84%  |
| 13      | 31        | 12.06%  |
| 17      | 15        | 5.84%   |
| 27      | 12        | 4.67%   |
| 12      | 12        | 4.67%   |
| 24      | 9         | 3.5%    |
| Unknown | 8         | 3.11%   |
| 21      | 5         | 1.95%   |
| 34      | 4         | 1.56%   |
| 23      | 4         | 1.56%   |
| 11      | 4         | 1.56%   |
| 18      | 3         | 1.17%   |
| 10      | 3         | 1.17%   |
| 72      | 1         | 0.39%   |
| 40      | 1         | 0.39%   |
| 31      | 1         | 0.39%   |
| 25      | 1         | 0.39%   |
| 20      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 151       | 59.68%  |
| 201-300     | 38        | 15.02%  |
| 501-600     | 20        | 7.91%   |
| 351-400     | 17        | 6.72%   |
| 401-500     | 9         | 3.56%   |
| Unknown     | 8         | 3.16%   |
| 701-800     | 4         | 1.58%   |
| 601-700     | 4         | 1.58%   |
| 801-900     | 1         | 0.4%    |
| 1501-2000   | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 181       | 79.74%  |
| 16/10   | 30        | 13.22%  |
| Unknown | 7         | 3.08%   |
| 21/9    | 4         | 1.76%   |
| 4/3     | 2         | 0.88%   |
| 3/2     | 2         | 0.88%   |
| 5/4     | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 108       | 42.19%  |
| 81-90          | 48        | 18.75%  |
| 71-80          | 17        | 6.64%   |
| 201-250        | 14        | 5.47%   |
| 301-350        | 12        | 4.69%   |
| 61-70          | 11        | 4.3%    |
| 121-130        | 11        | 4.3%    |
| Unknown        | 8         | 3.13%   |
| 351-500        | 5         | 1.95%   |
| 51-60          | 4         | 1.56%   |
| 141-150        | 4         | 1.56%   |
| 41-50          | 3         | 1.17%   |
| 251-300        | 3         | 1.17%   |
| 131-140        | 3         | 1.17%   |
| 151-200        | 2         | 0.78%   |
| More than 1000 | 1         | 0.39%   |
| 111-120        | 1         | 0.39%   |
| 501-1000       | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 100       | 39.84%  |
| 101-120       | 82        | 32.67%  |
| 51-100        | 35        | 13.94%  |
| 161-240       | 16        | 6.37%   |
| More than 240 | 8         | 3.19%   |
| Unknown       | 8         | 3.19%   |
| 1-50          | 2         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 184       | 79.31%  |
| 2     | 36        | 15.52%  |
| 0     | 9         | 3.88%   |
| 3     | 2         | 0.86%   |
| 4     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 127       | 33.96%  |
| Realtek Semiconductor             | 106       | 28.34%  |
| Qualcomm Atheros                  | 46        | 12.3%   |
| Broadcom                          | 35        | 9.36%   |
| Broadcom Limited                  | 9         | 2.41%   |
| Nvidia                            | 8         | 2.14%   |
| Ralink Technology                 | 5         | 1.34%   |
| Marvell Technology Group          | 5         | 1.34%   |
| Ericsson Business Mobile Networks | 5         | 1.34%   |
| Samsung Electronics               | 3         | 0.8%    |
| Ralink                            | 3         | 0.8%    |
| MEDIATEK                          | 3         | 0.8%    |
| Lenovo                            | 2         | 0.53%   |
| Xilinx                            | 1         | 0.27%   |
| Xiaomi                            | 1         | 0.27%   |
| TP-Link                           | 1         | 0.27%   |
| Toshiba                           | 1         | 0.27%   |
| T & A Mobile Phones               | 1         | 0.27%   |
| Qualcomm                          | 1         | 0.27%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.27%   |
| NetGear                           | 1         | 0.27%   |
| LSI                               | 1         | 0.27%   |
| ICS Advent                        | 1         | 0.27%   |
| Hewlett-Packard                   | 1         | 0.27%   |
| DisplayLink                       | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| Bose                              | 1         | 0.27%   |
| ASIX Electronics                  | 1         | 0.27%   |
| Apple                             | 1         | 0.27%   |
| 3Com                              | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 13.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 5.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 3.3%    |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.2%    |
| Intel Wireless 8265 / 8275                                        | 10        | 2.2%    |
| Intel Wireless 7260                                               | 9         | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.76%   |
| Intel Wireless 8260                                               | 7         | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.32%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.1%    |
| Intel Wireless 7265                                               | 5         | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.88%   |
| Intel Wireless 3165                                               | 4         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.66%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.66%   |
| Intel Wireless 3160                                               | 3         | 0.66%   |
| Intel WiFi Link 5100                                              | 3         | 0.66%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.66%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.66%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 0.66%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 3         | 0.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.44%   |
| Realtek 802.11ac NIC                                              | 2         | 0.44%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.44%   |
| Intel Wireless-AC 9260                                            | 2         | 0.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.44%   |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 0.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.44%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 0.44%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 123       | 51.04%  |
| Qualcomm Atheros      | 39        | 16.18%  |
| Realtek Semiconductor | 31        | 12.86%  |
| Broadcom              | 29        | 12.03%  |
| Ralink Technology     | 5         | 2.07%   |
| Ralink                | 3         | 1.24%   |
| MEDIATEK              | 3         | 1.24%   |
| Broadcom Limited      | 3         | 1.24%   |
| TP-Link               | 1         | 0.41%   |
| Qualcomm              | 1         | 0.41%   |
| NetGear               | 1         | 0.41%   |
| Dell                  | 1         | 0.41%   |
| Apple                 | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 15        | 6.17%   |
| Intel Wi-Fi 6 AX200                                                 | 13        | 5.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 11        | 4.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 10        | 4.12%   |
| Intel Wireless 8265 / 8275                                          | 10        | 4.12%   |
| Intel Wireless 7260                                                 | 9         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 8         | 3.29%   |
| Intel Wireless 8260                                                 | 7         | 2.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 7         | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 6         | 2.47%   |
| Broadcom BCM43142 802.11b/g/n                                       | 6         | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 5         | 2.06%   |
| Intel Wireless 7265                                                 | 5         | 2.06%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 5         | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 4         | 1.65%   |
| Intel Wireless 3165                                                 | 4         | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 4         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                      | 4         | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 4         | 1.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 3         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 3         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 3         | 1.23%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter       | 3         | 1.23%   |
| Intel Wireless 3160                                                 | 3         | 1.23%   |
| Intel WiFi Link 5100                                                | 3         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                 | 3         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 3         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 3         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 3         | 1.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                     | 3         | 1.23%   |
| Broadcom BCM4311 802.11b/g WLAN                                     | 3         | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 2         | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 2         | 0.82%   |
| Realtek 802.11ac NIC                                                | 2         | 0.82%   |
| Ralink RT5370 Wireless Adapter                                      | 2         | 0.82%   |
| Intel Wireless-AC 9260                                              | 2         | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2         | 0.82%   |
| Intel Ultimate N WiFi Link 5300                                     | 2         | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2         | 0.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 2         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 2         | 0.82%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                        | 2         | 0.82%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                       | 2         | 0.82%   |
| Intel Centrino Advanced-N 6200                                      | 2         | 0.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                           | 2         | 0.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 0.82%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 0.82%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                   | 2         | 0.82%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1         | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1         | 0.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 1         | 0.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 1         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 0.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1         | 0.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                         | 1         | 0.41%   |
| Realtek RTL8187SE Wireless LAN Controller                           | 1         | 0.41%   |
| Realtek 802.11n WLAN Adapter                                        | 1         | 0.41%   |
| Ralink RT5572 Wireless Adapter                                      | 1         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 94        | 47.24%  |
| Intel                         | 50        | 25.13%  |
| Qualcomm Atheros              | 13        | 6.53%   |
| Broadcom                      | 9         | 4.52%   |
| Nvidia                        | 8         | 4.02%   |
| Broadcom Limited              | 7         | 3.52%   |
| Marvell Technology Group      | 5         | 2.51%   |
| Samsung Electronics           | 3         | 1.51%   |
| Lenovo                        | 2         | 1.01%   |
| Xilinx                        | 1         | 0.5%    |
| Xiaomi                        | 1         | 0.5%    |
| T & A Mobile Phones           | 1         | 0.5%    |
| OnePlus Technology (Shenzhen) | 1         | 0.5%    |
| ICS Advent                    | 1         | 0.5%    |
| DisplayLink                   | 1         | 0.5%    |
| ASIX Electronics              | 1         | 0.5%    |
| 3Com                          | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 30.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 11.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 8.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.98%   |
| Nvidia MCP79 Ethernet                                             | 6         | 2.99%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 1.49%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.49%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.49%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 1.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1%      |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1%      |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 1%      |
| Intel Ethernet Connection I219-V                                  | 2         | 1%      |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1%      |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 1%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1%      |
| Xilinx Ethernet controller                                        | 1         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.5%    |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.5%    |
| OnePlus (Shenzhen) AC2001                                         | 1         | 0.5%    |
| Nvidia MCP67 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.5%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 0.5%    |
| Lenovo Ethernet adapter [U2L 100P-Y1]                             | 1         | 0.5%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.5%    |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.5%    |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.5%    |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 0.5%    |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express | 1         | 0.5%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.5%    |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.5%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 228       | 53.65%  |
| Ethernet | 187       | 44%     |
| Modem    | 10        | 2.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 193       | 65.65%  |
| Ethernet | 100       | 34.01%  |
| Modem    | 1         | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 177       | 76.96%  |
| 1     | 49        | 21.3%   |
| 0     | 3         | 1.3%    |
| 3     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 211       | 91.34%  |
| Yes  | 20        | 8.66%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 49.71%  |
| Realtek Semiconductor           | 16        | 9.36%   |
| Broadcom                        | 14        | 8.19%   |
| Lite-On Technology              | 10        | 5.85%   |
| IMC Networks                    | 10        | 5.85%   |
| Qualcomm Atheros Communications | 9         | 5.26%   |
| Apple                           | 7         | 4.09%   |
| Dell                            | 6         | 3.51%   |
| Hewlett-Packard                 | 5         | 2.92%   |
| Toshiba                         | 2         | 1.17%   |
| Realtek                         | 2         | 1.17%   |
| Cambridge Silicon Radio         | 2         | 1.17%   |
| Ralink                          | 1         | 0.58%   |
| Foxconn International           | 1         | 0.58%   |
| Foxconn / Hon Hai               | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 42        | 24.56%  |
| Intel AX201 Bluetooth                                       | 13        | 7.6%    |
| Intel AX200 Bluetooth                                       | 13        | 7.6%    |
| Realtek Bluetooth Radio                                     | 10        | 5.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 4.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 3.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 2.92%   |
| Apple Bluetooth Host Controller                             | 5         | 2.92%   |
| Qualcomm Atheros  Bluetooth Device                          | 4         | 2.34%   |
| IMC Networks Bluetooth Radio                                | 4         | 2.34%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 4         | 2.34%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 1.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 3         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.17%   |
| Realtek Bluetooth Radio                                     | 2         | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.17%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.17%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.17%   |
| Intel Bluetooth Device                                      | 2         | 1.17%   |
| Intel AX210 Bluetooth                                       | 2         | 1.17%   |
| IMC Networks Wireless_Device                                | 2         | 1.17%   |
| IMC Networks Bluetooth Device                               | 2         | 1.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.17%   |
| Dell Wireless 355 Bluetooth                                 | 2         | 1.17%   |
| Dell DW375 Bluetooth Module                                 | 2         | 1.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.17%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 1.17%   |
| Toshiba Bluetooth Device                                    | 1         | 0.58%   |
| Toshiba BCM43142A0                                          | 1         | 0.58%   |
| Realtek 802.11n WLAN Adapter                                | 1         | 0.58%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.58%   |
| Lite-On Wireless_Device                                     | 1         | 0.58%   |
| Lite-On BCM43142A0                                          | 1         | 0.58%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.58%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.58%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.58%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.58%   |
| Foxconn International BCM43142A0 Bluetooth module           | 1         | 0.58%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 0.58%   |
| Dell Wireless 365 Bluetooth                                 | 1         | 0.58%   |
| Dell Wireless 350 Bluetooth                                 | 1         | 0.58%   |
| Broadcom Bluetooth Device                                   | 1         | 0.58%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 0.58%   |
| Apple Bluetooth USB Host Controller                         | 1         | 0.58%   |
| Apple Bluetooth HCI                                         | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 183       | 64.44%  |
| Nvidia                | 50        | 17.61%  |
| AMD                   | 39        | 13.73%  |
| Realtek Semiconductor | 2         | 0.7%    |
| GN Netcom             | 2         | 0.7%    |
| C-Media Electronics   | 2         | 0.7%    |
| VIA Technologies      | 1         | 0.35%   |
| RODE Microphones      | 1         | 0.35%   |
| Lenovo                | 1         | 0.35%   |
| ESS Technology        | 1         | 0.35%   |
| Creative Technology   | 1         | 0.35%   |
| AUDIOLAB              | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 9.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 6.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 4.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.73%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.73%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.12%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 2.12%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 1.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.82%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.82%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.52%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 1.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.52%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.91%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.91%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.91%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.61%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.61%   |
| Nvidia Audio device                                                                               | 2         | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.61%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.61%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.61%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.61%   |
| VIA Technologies VX1                                                                              | 1         | 0.3%    |
| RODE Microphones RODE NT-USB                                                                      | 1         | 0.3%    |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.3%    |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.3%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.3%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.3%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.3%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.3%    |
| Lenovo ThinkPad Dock Audio                                                                        | 1         | 0.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 27.74%  |
| SK Hynix            | 25        | 18.25%  |
| Micron Technology   | 16        | 11.68%  |
| Unknown             | 12        | 8.76%   |
| Kingston            | 12        | 8.76%   |
| Crucial             | 8         | 5.84%   |
| Corsair             | 6         | 4.38%   |
| Ramaxel Technology  | 5         | 3.65%   |
| Elpida              | 4         | 2.92%   |
| Nanya Technology    | 3         | 2.19%   |
| Unknown (ABCD)      | 1         | 0.73%   |
| Transcend           | 1         | 0.73%   |
| SHARETRONIC         | 1         | 0.73%   |
| Patriot             | 1         | 0.73%   |
| G.Skill             | 1         | 0.73%   |
| CSX                 | 1         | 0.73%   |
| Apacer              | 1         | 0.73%   |
| A Force             | 1         | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 3.45%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 2.07%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 2.07%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 2.07%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s             | 3         | 2.07%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 1.38%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 1.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.38%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 2         | 1.38%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s               | 2         | 1.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 1.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.38%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                | 2         | 1.38%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 2         | 1.38%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 2048MB Chip DDR3 1333MT/s              | 2         | 1.38%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16384MB SODIMM DDR4 3200MT/s       | 2         | 1.38%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.69%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                       | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                         | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                            | 1         | 0.69%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.69%   |
| Unknown RAM Module 256MB SODIMM DRAM                                | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.69%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.69%   |
| Unknown RAM Module 128MB SODIMM DRAM                                | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                              | 1         | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.69%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                   | 1         | 0.69%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.69%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s             | 1         | 0.69%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                | 1         | 0.69%   |
| SK Hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.69%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s                | 1         | 0.69%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMCG78MEBSA095N 16GB SODIMM 4800MT/s                   | 1         | 0.69%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.69%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.69%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.69%   |
| SK Hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.69%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.69%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.69%   |
| Samsung RAM Module 2GB Row Of Chips DDR3 1600MT/s                   | 1         | 0.69%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s            | 1         | 0.69%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 0.69%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 0.69%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 57        | 46.72%  |
| DDR3    | 37        | 30.33%  |
| DDR2    | 8         | 6.56%   |
| LPDDR4  | 7         | 5.74%   |
| SDRAM   | 4         | 3.28%   |
| LPDDR3  | 4         | 3.28%   |
| DDR     | 2         | 1.64%   |
| Unknown | 2         | 1.64%   |
| DRAM    | 1         | 0.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 86.18%  |
| Row Of Chips | 12        | 9.76%   |
| Chip         | 4         | 3.25%   |
| Unknown      | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 41        | 31.3%   |
| 4096  | 41        | 31.3%   |
| 16384 | 20        | 15.27%  |
| 2048  | 19        | 14.5%   |
| 1024  | 5         | 3.82%   |
| 32768 | 3         | 2.29%   |
| 256   | 1         | 0.76%   |
| 128   | 1         | 0.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 28        | 21.21%  |
| 1600    | 23        | 17.42%  |
| 3200    | 12        | 9.09%   |
| 2400    | 12        | 9.09%   |
| 2133    | 12        | 9.09%   |
| 1334    | 7         | 5.3%    |
| 4267    | 5         | 3.79%   |
| 3266    | 5         | 3.79%   |
| 1333    | 5         | 3.79%   |
| 800     | 5         | 3.79%   |
| 667     | 5         | 3.79%   |
| 1067    | 3         | 2.27%   |
| 4199    | 2         | 1.52%   |
| 1867    | 2         | 1.52%   |
| 975     | 2         | 1.52%   |
| Unknown | 2         | 1.52%   |
| 4800    | 1         | 0.76%   |
| 2048    | 1         | 0.76%   |

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
| Chicony Electronics                    | 54        | 26.6%   |
| Realtek Semiconductor                  | 27        | 13.3%   |
| Microdia                               | 20        | 9.85%   |
| IMC Networks                           | 20        | 9.85%   |
| Acer                                   | 19        | 9.36%   |
| Quanta                                 | 7         | 3.45%   |
| Apple                                  | 7         | 3.45%   |
| Suyin                                  | 6         | 2.96%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.96%   |
| Sunplus Innovation Technology          | 5         | 2.46%   |
| Samsung Electronics                    | 5         | 2.46%   |
| Logitech                               | 5         | 2.46%   |
| ALi                                    | 5         | 2.46%   |
| Syntek                                 | 3         | 1.48%   |
| Silicon Motion                         | 3         | 1.48%   |
| Ricoh                                  | 3         | 1.48%   |
| Lite-On Technology                     | 2         | 0.99%   |
| Z-Star Microelectronics                | 1         | 0.49%   |
| Y Media                                | 1         | 0.49%   |
| Trust                                  | 1         | 0.49%   |
| Nikon                                  | 1         | 0.49%   |
| Lenovo                                 | 1         | 0.49%   |
| Alcor Micro                            | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 12        | 5.85%   |
| Microdia Integrated_Webcam_HD                    | 9         | 4.39%   |
| Chicony USB2.0 Camera                            | 7         | 3.41%   |
| Chicony HD Webcam                                | 7         | 3.41%   |
| IMC Networks Integrated Camera                   | 6         | 2.93%   |
| Chicony Integrated Camera                        | 6         | 2.93%   |
| Apple Built-in iSight                            | 6         | 2.93%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 2.44%   |
| Microdia Integrated Webcam                       | 4         | 1.95%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 1.95%   |
| Acer EasyCamera                                  | 4         | 1.95%   |
| Realtek Integrated Webcam HD                     | 3         | 1.46%   |
| Chicony Lenovo EasyCamera                        | 3         | 1.46%   |
| ALi WebCam                                       | 3         | 1.46%   |
| Acer Integrated Camera                           | 3         | 1.46%   |
| Acer BisonCam, NB Pro                            | 3         | 1.46%   |
| Syntek EasyCamera                                | 2         | 0.98%   |
| Suyin HP Truevision HD                           | 2         | 0.98%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 0.98%   |
| Realtek USB Camera                               | 2         | 0.98%   |
| Realtek HD WebCam                                | 2         | 0.98%   |
| Realtek EasyCamera                               | 2         | 0.98%   |
| Quanta HP Webcam                                 | 2         | 0.98%   |
| Logitech B525 HD Webcam                          | 2         | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.98%   |
| IMC Networks TOSHIBA Web Camera - HD             | 2         | 0.98%   |
| IMC Networks EasyCamera                          | 2         | 0.98%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 0.98%   |
| Chicony thinkpad t430s camera                    | 2         | 0.98%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 0.98%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 0.98%   |
| Chicony HP Wide Vision HD Camera                 | 2         | 0.98%   |
| Chicony HP TrueVision HD Camera                  | 2         | 0.98%   |
| Chicony HP Truevision HD                         | 2         | 0.98%   |
| Chicony EasyCamera                               | 2         | 0.98%   |
| Chicony CNF9055 Toshiba Webcam                   | 2         | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 0.98%   |
| ALi Gateway Webcam                               | 2         | 0.98%   |
| Acer Lenovo EasyCamera                           | 2         | 0.98%   |
| Acer BisonCam,NB Pro                             | 2         | 0.98%   |
| Z-Star Webcam                                    | 1         | 0.49%   |
| Y Media USB Camera                               | 1         | 0.49%   |
| Trust USB Camera                                 | 1         | 0.49%   |
| Syntek Integrated Camera                         | 1         | 0.49%   |
| Suyin VGA Webcam                                 | 1         | 0.49%   |
| Suyin Acer HD Crystal Eye webcam                 | 1         | 0.49%   |
| Suyin Acer CrystalEye Webcam                     | 1         | 0.49%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.49%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.49%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.49%   |
| Sunplus HD Webcam                                | 1         | 0.49%   |
| Silicon Motion WebCam SC-13HDL11939N             | 1         | 0.49%   |
| Silicon Motion Lenovo EasyCamera                 | 1         | 0.49%   |
| Silicon Motion HP Webcam-101                     | 1         | 0.49%   |
| Ricoh USB2.0 Camera                              | 1         | 0.49%   |
| Ricoh Laptop_Integrated_Webcam_FHD               | 1         | 0.49%   |
| Ricoh Integrated Webcam                          | 1         | 0.49%   |
| Realtek VGA WebCam                               | 1         | 0.49%   |
| Realtek USB2.0 VGA UVC WebCam                    | 1         | 0.49%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 30.61%  |
| Synaptics                  | 14        | 28.57%  |
| Shenzhen Goodix Technology | 9         | 18.37%  |
| Upek                       | 4         | 8.16%   |
| LighTuning Technology      | 2         | 4.08%   |
| AuthenTec                  | 2         | 4.08%   |
| STMicroelectronics         | 1         | 2.04%   |
| Focal-systems.Corp         | 1         | 2.04%   |
| Elan Microelectronics      | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 8         | 16.33%  |
| Shenzhen Goodix FingerPrint                                | 6         | 12.24%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 8.16%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 6.12%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 4.08%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 4.08%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 4.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.08%   |
| Shenzhen Goodix  Fingerprint Device                        | 2         | 4.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 4.08%   |
| AuthenTec Fingerprint Sensor                               | 2         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.04%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.04%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 2.04%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 2.04%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.04%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.04%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 2.04%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 2.04%   |
| Elan ELAN:Fingerprint                                      | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 51.72%  |
| Upek        | 5         | 17.24%  |
| O2 Micro    | 4         | 13.79%  |
| Alcor Micro | 4         | 13.79%  |
| Lenovo      | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 17.24%  |
| Broadcom 58200                                                               | 5         | 17.24%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 13.79%  |
| Broadcom 5880                                                                | 4         | 13.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 13.79%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.9%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 128       | 54.47%  |
| 1     | 89        | 37.87%  |
| 2     | 14        | 5.96%   |
| 3     | 4         | 1.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 48        | 39.02%  |
| Chipcard                 | 27        | 21.95%  |
| Net/wireless             | 17        | 13.82%  |
| Graphics card            | 14        | 11.38%  |
| Storage                  | 4         | 3.25%   |
| Multimedia controller    | 4         | 3.25%   |
| Communication controller | 3         | 2.44%   |
| Camera                   | 3         | 2.44%   |
| Modem                    | 1         | 0.81%   |
| Card reader              | 1         | 0.81%   |
| Bluetooth                | 1         | 0.81%   |


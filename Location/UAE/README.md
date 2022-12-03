Linux in UAE - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Linux in UAE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UAE/Desktop/README.md) and [notebooks](/Location/UAE/Notebook/README.md).

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

Total: 194

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Modern 14 B5M               | Notebook    | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Dell          | 0F9N89 A00                  | Server      | [3a917876ba](https://linux-hardware.org/?probe=3a917876ba) | Nov 23, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [79119cca36](https://linux-hardware.org/?probe=79119cca36) | Nov 19, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [1b30c252bb](https://linux-hardware.org/?probe=1b30c252bb) | Nov 19, 2022 |
| HP            | 0AECh D                     | Desktop     | [9e2ddc5dbd](https://linux-hardware.org/?probe=9e2ddc5dbd) | Nov 18, 2022 |
| HP            | 0AECh D                     | Desktop     | [95b36ddda4](https://linux-hardware.org/?probe=95b36ddda4) | Nov 18, 2022 |
| HP            | 1495                        | Desktop     | [c4535d8ea8](https://linux-hardware.org/?probe=c4535d8ea8) | Nov 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [faf014b2e6](https://linux-hardware.org/?probe=faf014b2e6) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d9af542480](https://linux-hardware.org/?probe=d9af542480) | Nov 08, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [7d3eac2c7d](https://linux-hardware.org/?probe=7d3eac2c7d) | Nov 05, 2022 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [46874cc0a1](https://linux-hardware.org/?probe=46874cc0a1) | Nov 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [910b452558](https://linux-hardware.org/?probe=910b452558) | Oct 30, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [7406489511](https://linux-hardware.org/?probe=7406489511) | Oct 21, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e8e0acd06e](https://linux-hardware.org/?probe=e8e0acd06e) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b1590cf8fa](https://linux-hardware.org/?probe=b1590cf8fa) | Oct 03, 2022 |
| Intel         | NUC10i3FNB K61362-306       | Mini pc     | [e8130be6f2](https://linux-hardware.org/?probe=e8130be6f2) | Oct 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [512c793b51](https://linux-hardware.org/?probe=512c793b51) | Sep 06, 2022 |
| Lenovo        | ThinkPad T61 76653JG        | Notebook    | [0fae1da16b](https://linux-hardware.org/?probe=0fae1da16b) | Aug 02, 2022 |
| Lenovo        | 81FV                        | Notebook    | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PA... | Notebook    | [de71ab8780](https://linux-hardware.org/?probe=de71ab8780) | Jul 21, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [b847a4a45d](https://linux-hardware.org/?probe=b847a4a45d) | Jul 03, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [0aa196cd0c](https://linux-hardware.org/?probe=0aa196cd0c) | Jul 03, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [eca7a31c46](https://linux-hardware.org/?probe=eca7a31c46) | Jun 23, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [134bf128f7](https://linux-hardware.org/?probe=134bf128f7) | Jun 23, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [0fbbdf9197](https://linux-hardware.org/?probe=0fbbdf9197) | Jun 07, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [ad2442631e](https://linux-hardware.org/?probe=ad2442631e) | May 28, 2022 |
| HP            | 8446                        | All in one  | [821752cb21](https://linux-hardware.org/?probe=821752cb21) | May 11, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [6c498d2ce5](https://linux-hardware.org/?probe=6c498d2ce5) | Apr 29, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS4... | Notebook    | [28c774c6de](https://linux-hardware.org/?probe=28c774c6de) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4edc1d31b5](https://linux-hardware.org/?probe=4edc1d31b5) | Mar 06, 2022 |
| Google        | Terra                       | Notebook    | [54163369b2](https://linux-hardware.org/?probe=54163369b2) | Feb 23, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [f014fcba4f](https://linux-hardware.org/?probe=f014fcba4f) | Feb 14, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a8aeb155b0](https://linux-hardware.org/?probe=a8aeb155b0) | Feb 10, 2022 |
| Biostar       | TZ77XE4                     | Desktop     | [081c3be70e](https://linux-hardware.org/?probe=081c3be70e) | Feb 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Dell          | Latitude E5440              | Notebook    | [ebbb8ee138](https://linux-hardware.org/?probe=ebbb8ee138) | Jan 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FV0... | Notebook    | [78080db667](https://linux-hardware.org/?probe=78080db667) | Jan 13, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4670daefab](https://linux-hardware.org/?probe=4670daefab) | Jan 04, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c36553e3a3](https://linux-hardware.org/?probe=c36553e3a3) | Dec 27, 2021 |
| Google        | Akemi                       | Notebook    | [aaf0a3e10e](https://linux-hardware.org/?probe=aaf0a3e10e) | Dec 20, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [927497310e](https://linux-hardware.org/?probe=927497310e) | Nov 16, 2021 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [7b77d5463d](https://linux-hardware.org/?probe=7b77d5463d) | Nov 13, 2021 |
| win elemen... | MoreFine S500+              | Notebook    | [ace08cf199](https://linux-hardware.org/?probe=ace08cf199) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | Notebook    | [0e31d4b6fa](https://linux-hardware.org/?probe=0e31d4b6fa) | Nov 11, 2021 |
| MSI           | PS63 Modern 8RD             | Notebook    | [519048dea2](https://linux-hardware.org/?probe=519048dea2) | Nov 01, 2021 |
| MSI           | PS63 Modern 8RD             | Notebook    | [6d3cd2f117](https://linux-hardware.org/?probe=6d3cd2f117) | Nov 01, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [24d1bd52cc](https://linux-hardware.org/?probe=24d1bd52cc) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| HP            | ProBook 6475b               | Notebook    | [9d60bf5397](https://linux-hardware.org/?probe=9d60bf5397) | Oct 02, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [eccb23bda1](https://linux-hardware.org/?probe=eccb23bda1) | Sep 24, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [e1f91ca6de](https://linux-hardware.org/?probe=e1f91ca6de) | Sep 02, 2021 |
| HP            | 8446                        | All in one  | [430c02980a](https://linux-hardware.org/?probe=430c02980a) | Aug 13, 2021 |
| Sony          | VGN-NS10J_S                 | Notebook    | [31d1e0e91d](https://linux-hardware.org/?probe=31d1e0e91d) | Aug 12, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| LG Electro... | C500-G.AEF5BE1              | Notebook    | [b78f4cd34d](https://linux-hardware.org/?probe=b78f4cd34d) | Jun 14, 2021 |
| Toshiba       | Satellite C850-A966         | Notebook    | [391d22d993](https://linux-hardware.org/?probe=391d22d993) | Jun 02, 2021 |
| Sony          | SVE14A25CAB                 | Notebook    | [78ddb916b5](https://linux-hardware.org/?probe=78ddb916b5) | May 30, 2021 |
| Sony          | SVE14A25CAB                 | Notebook    | [0a2c5cf1cd](https://linux-hardware.org/?probe=0a2c5cf1cd) | May 30, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5707e7ae37](https://linux-hardware.org/?probe=5707e7ae37) | May 28, 2021 |
| Dell          | OptiPlex 980                | Desktop     | [1fe360b027](https://linux-hardware.org/?probe=1fe360b027) | May 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [66cc8bd4a5](https://linux-hardware.org/?probe=66cc8bd4a5) | May 19, 2021 |
| Dell          | G5 5587                     | Notebook    | [2d2cf67a2d](https://linux-hardware.org/?probe=2d2cf67a2d) | May 08, 2021 |
| Dell          | Latitude E6510              | Notebook    | [06d38294ab](https://linux-hardware.org/?probe=06d38294ab) | May 03, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| HP            | 8446                        | All in one  | [a52aa6f1bd](https://linux-hardware.org/?probe=a52aa6f1bd) | Mar 10, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [6b82d5c050](https://linux-hardware.org/?probe=6b82d5c050) | Mar 07, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [227244211b](https://linux-hardware.org/?probe=227244211b) | Mar 07, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [3c9d39abce](https://linux-hardware.org/?probe=3c9d39abce) | Mar 06, 2021 |
| Lenovo        | ThinkPad X230 2325DV8       | Notebook    | [11d5145d10](https://linux-hardware.org/?probe=11d5145d10) | Feb 12, 2021 |
| HP            | Elite Dragonfly             | Convertible | [87b2f82af5](https://linux-hardware.org/?probe=87b2f82af5) | Feb 01, 2021 |
| HP            | Elite Dragonfly             | Convertible | [6e1ef1920c](https://linux-hardware.org/?probe=6e1ef1920c) | Jan 31, 2021 |
| HP            | Elite Dragonfly             | Convertible | [215ff8ccba](https://linux-hardware.org/?probe=215ff8ccba) | Jan 31, 2021 |
| HP            | Pavilion dv6                | Notebook    | [317b81878c](https://linux-hardware.org/?probe=317b81878c) | Jan 27, 2021 |
| Lenovo        | 3098 NOK                    | Desktop     | [d0ccf5266d](https://linux-hardware.org/?probe=d0ccf5266d) | Jan 27, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [3d8ea2b061](https://linux-hardware.org/?probe=3d8ea2b061) | Jan 27, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [a3c15a6f74](https://linux-hardware.org/?probe=a3c15a6f74) | Jan 18, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [58bf01b1e7](https://linux-hardware.org/?probe=58bf01b1e7) | Jan 18, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1c5ef3cfe4](https://linux-hardware.org/?probe=1c5ef3cfe4) | Jan 11, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d071e37713](https://linux-hardware.org/?probe=d071e37713) | Jan 10, 2021 |
| HP            | 8446                        | All in one  | [a07d483bab](https://linux-hardware.org/?probe=a07d483bab) | Jan 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [6a02570e23](https://linux-hardware.org/?probe=6a02570e23) | Jan 03, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [092666f171](https://linux-hardware.org/?probe=092666f171) | Dec 31, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [93e3d5b038](https://linux-hardware.org/?probe=93e3d5b038) | Dec 25, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [d24a3c768e](https://linux-hardware.org/?probe=d24a3c768e) | Dec 24, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cb1c064071](https://linux-hardware.org/?probe=cb1c064071) | Dec 16, 2020 |
| Dell          | Latitude E6410              | Notebook    | [a2a46d21e9](https://linux-hardware.org/?probe=a2a46d21e9) | Dec 15, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [e2816ed19c](https://linux-hardware.org/?probe=e2816ed19c) | Nov 27, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [12a3adede5](https://linux-hardware.org/?probe=12a3adede5) | Nov 06, 2020 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [91e0e6c6bc](https://linux-hardware.org/?probe=91e0e6c6bc) | Nov 04, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6f0218a447](https://linux-hardware.org/?probe=6f0218a447) | Oct 28, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7ad824c6f9](https://linux-hardware.org/?probe=7ad824c6f9) | Oct 26, 2020 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [54531ec292](https://linux-hardware.org/?probe=54531ec292) | Oct 21, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f372424ac5](https://linux-hardware.org/?probe=f372424ac5) | Oct 18, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [387171a87d](https://linux-hardware.org/?probe=387171a87d) | Oct 08, 2020 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b1cd303933](https://linux-hardware.org/?probe=b1cd303933) | Oct 08, 2020 |
| HP            | 2AA2                        | Desktop     | [ceebc6a90b](https://linux-hardware.org/?probe=ceebc6a90b) | Oct 04, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [7d3672caff](https://linux-hardware.org/?probe=7d3672caff) | Oct 04, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [2a18eaa0ab](https://linux-hardware.org/?probe=2a18eaa0ab) | Oct 04, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [f9f212a509](https://linux-hardware.org/?probe=f9f212a509) | Oct 01, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [42c8711bea](https://linux-hardware.org/?probe=42c8711bea) | Sep 29, 2020 |
| Acer          | ChiefRiver Platform         | Notebook    | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [22369a8f3c](https://linux-hardware.org/?probe=22369a8f3c) | Sep 20, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [d026d40366](https://linux-hardware.org/?probe=d026d40366) | Sep 17, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [18778a34f2](https://linux-hardware.org/?probe=18778a34f2) | Sep 10, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ff1f32c975](https://linux-hardware.org/?probe=ff1f32c975) | Sep 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [94cbf8e66c](https://linux-hardware.org/?probe=94cbf8e66c) | Sep 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a25d4e5346](https://linux-hardware.org/?probe=a25d4e5346) | Sep 09, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c4c1a329af](https://linux-hardware.org/?probe=c4c1a329af) | Sep 06, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| Dell          | Latitude E6540              | Notebook    | [9abf14d168](https://linux-hardware.org/?probe=9abf14d168) | Aug 31, 2020 |
| HP            | 8446                        | All in one  | [08b9600cae](https://linux-hardware.org/?probe=08b9600cae) | Aug 29, 2020 |
| Dell          | Precision 5540              | Notebook    | [76f1cfa736](https://linux-hardware.org/?probe=76f1cfa736) | Aug 23, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [19af27b191](https://linux-hardware.org/?probe=19af27b191) | Aug 20, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [f555bad747](https://linux-hardware.org/?probe=f555bad747) | Aug 14, 2020 |
| I-Life Dig... | ZED AIR                     | Notebook    | [b40d7e9c7c](https://linux-hardware.org/?probe=b40d7e9c7c) | Aug 10, 2020 |
| I-Life Dig... | ZED AIR                     | Notebook    | [5662aa186c](https://linux-hardware.org/?probe=5662aa186c) | Aug 10, 2020 |
| HP            | 2AA2                        | Desktop     | [f20932c5c3](https://linux-hardware.org/?probe=f20932c5c3) | Aug 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | Notebook    | [81d46e4c4a](https://linux-hardware.org/?probe=81d46e4c4a) | Aug 02, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [670cc8a66c](https://linux-hardware.org/?probe=670cc8a66c) | Jul 26, 2020 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [aea3470496](https://linux-hardware.org/?probe=aea3470496) | Jul 21, 2020 |
| HP            | 2AA2                        | Desktop     | [424f0397a7](https://linux-hardware.org/?probe=424f0397a7) | Jul 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [b3dbd3f2af](https://linux-hardware.org/?probe=b3dbd3f2af) | Jul 14, 2020 |
| Toshiba       | TECRA A50-C                 | Notebook    | [adf7a73571](https://linux-hardware.org/?probe=adf7a73571) | Jul 03, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [d6c0a21749](https://linux-hardware.org/?probe=d6c0a21749) | Jul 02, 2020 |
| HP            | Pavilion 15                 | Notebook    | [499f0c72ee](https://linux-hardware.org/?probe=499f0c72ee) | Jun 29, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [dc74d7b188](https://linux-hardware.org/?probe=dc74d7b188) | Jun 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [dd5c9e8d9f](https://linux-hardware.org/?probe=dd5c9e8d9f) | Jun 23, 2020 |
| Dell          | Latitude E6410              | Notebook    | [06055ff260](https://linux-hardware.org/?probe=06055ff260) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [b53cc32ed0](https://linux-hardware.org/?probe=b53cc32ed0) | Jun 19, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [fdc9496e84](https://linux-hardware.org/?probe=fdc9496e84) | Jun 19, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [fdbf1ae7da](https://linux-hardware.org/?probe=fdbf1ae7da) | Jun 19, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [0d398d9227](https://linux-hardware.org/?probe=0d398d9227) | Jun 14, 2020 |
| HP            | 2AA2                        | Desktop     | [24c07d9d0d](https://linux-hardware.org/?probe=24c07d9d0d) | Jun 11, 2020 |
| HP            | 8446                        | All in one  | [d64a9cef98](https://linux-hardware.org/?probe=d64a9cef98) | Jun 11, 2020 |
| Dell          | Latitude E6410              | Notebook    | [1b73d74e65](https://linux-hardware.org/?probe=1b73d74e65) | Jun 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | Notebook    | [e9b38b78d7](https://linux-hardware.org/?probe=e9b38b78d7) | May 30, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [83ae823929](https://linux-hardware.org/?probe=83ae823929) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [af063f022b](https://linux-hardware.org/?probe=af063f022b) | May 23, 2020 |
| HP            | Presario C300 (RH208UA#A... | Notebook    | [50e95ff237](https://linux-hardware.org/?probe=50e95ff237) | May 14, 2020 |
| HP            | Presario C300 (RH208UA#A... | Notebook    | [6b4a8eab4c](https://linux-hardware.org/?probe=6b4a8eab4c) | May 14, 2020 |
| Toshiba       | TECRA X40-D                 | Notebook    | [3255796d07](https://linux-hardware.org/?probe=3255796d07) | May 10, 2020 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [49363e9553](https://linux-hardware.org/?probe=49363e9553) | May 07, 2020 |
| HP            | 8446                        | All in one  | [96d169caae](https://linux-hardware.org/?probe=96d169caae) | May 06, 2020 |
| HP            | 8446                        | All in one  | [835b1abcee](https://linux-hardware.org/?probe=835b1abcee) | May 02, 2020 |
| HP            | 8446                        | All in one  | [aa03445e30](https://linux-hardware.org/?probe=aa03445e30) | May 01, 2020 |
| HP            | 8446                        | All in one  | [d9db887931](https://linux-hardware.org/?probe=d9db887931) | May 01, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS6GB00    | Notebook    | [3fa804be21](https://linux-hardware.org/?probe=3fa804be21) | May 01, 2020 |
| HP            | 8446                        | All in one  | [eab561395e](https://linux-hardware.org/?probe=eab561395e) | Apr 27, 2020 |
| HP            | 8446                        | All in one  | [ad2491858f](https://linux-hardware.org/?probe=ad2491858f) | Apr 25, 2020 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [d2328783da](https://linux-hardware.org/?probe=d2328783da) | Apr 24, 2020 |
| Dell          | Vostro 14-5480              | Notebook    | [1bba68101c](https://linux-hardware.org/?probe=1bba68101c) | Apr 20, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [aac474f532](https://linux-hardware.org/?probe=aac474f532) | Apr 18, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | Notebook                    | Notebook    | [4f154f82b0](https://linux-hardware.org/?probe=4f154f82b0) | Apr 01, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [5cd86dffe9](https://linux-hardware.org/?probe=5cd86dffe9) | Mar 16, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [7f0b4db18a](https://linux-hardware.org/?probe=7f0b4db18a) | Mar 12, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [87df29714d](https://linux-hardware.org/?probe=87df29714d) | Mar 11, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [04da794ff5](https://linux-hardware.org/?probe=04da794ff5) | Feb 25, 2020 |
| HP            | EliteBook 2760p             | Notebook    | [40333472c7](https://linux-hardware.org/?probe=40333472c7) | Feb 21, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [b12186f161](https://linux-hardware.org/?probe=b12186f161) | Feb 13, 2020 |
| HP            | Notebook                    | Notebook    | [a25a67e533](https://linux-hardware.org/?probe=a25a67e533) | Feb 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | Notebook    | [c2a7159d3a](https://linux-hardware.org/?probe=c2a7159d3a) | Jan 04, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | Notebook    | [028d728043](https://linux-hardware.org/?probe=028d728043) | Jan 04, 2020 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [d1ca80edff](https://linux-hardware.org/?probe=d1ca80edff) | Dec 24, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [420c738977](https://linux-hardware.org/?probe=420c738977) | Oct 15, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [036dc7e829](https://linux-hardware.org/?probe=036dc7e829) | Oct 15, 2019 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [ab1c14d729](https://linux-hardware.org/?probe=ab1c14d729) | Oct 12, 2019 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [558c01fdce](https://linux-hardware.org/?probe=558c01fdce) | Oct 07, 2019 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [d4ad7906b5](https://linux-hardware.org/?probe=d4ad7906b5) | Sep 11, 2019 |
| Dell          | 0NK70N A03                  | Desktop     | [8aa5224a4a](https://linux-hardware.org/?probe=8aa5224a4a) | Aug 01, 2019 |
| I-Life Dig... | ZED AIR                     | Notebook    | [514c494f7f](https://linux-hardware.org/?probe=514c494f7f) | Jul 23, 2019 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a9fe92aa3c](https://linux-hardware.org/?probe=a9fe92aa3c) | Jul 23, 2019 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [309f371381](https://linux-hardware.org/?probe=309f371381) | May 27, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [1f8a20b199](https://linux-hardware.org/?probe=1f8a20b199) | May 25, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [60d0e8dd5d](https://linux-hardware.org/?probe=60d0e8dd5d) | May 25, 2019 |
| HP            | ProBook 4540s               | Notebook    | [271be85705](https://linux-hardware.org/?probe=271be85705) | May 15, 2019 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [ab25f83cd0](https://linux-hardware.org/?probe=ab25f83cd0) | Mar 27, 2019 |
| ASUSTek       | ROG STRIX X299-XE GAMING    | Desktop     | [c8fdc5e958](https://linux-hardware.org/?probe=c8fdc5e958) | Dec 25, 2018 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [c48aa05e74](https://linux-hardware.org/?probe=c48aa05e74) | Oct 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 32        | 24.06%  |
| Ubuntu 18.04       | 16        | 12.03%  |
| Ubuntu 22.04       | 5         | 3.76%   |
| Arch               | 5         | 3.76%   |
| Ubuntu 19.10       | 4         | 3.01%   |
| Fedora 36          | 4         | 3.01%   |
| Debian 11          | 4         | 3.01%   |
| Zorin 15           | 3         | 2.26%   |
| Ubuntu 22.10       | 3         | 2.26%   |
| Ubuntu 20.10       | 3         | 2.26%   |
| Linux Mint 20.3    | 3         | 2.26%   |
| Debian 10          | 3         | 2.26%   |
| Zorin 16           | 2         | 1.5%    |
| Ubuntu 21.10       | 2         | 1.5%    |
| Ubuntu 16.04       | 2         | 1.5%    |
| Pop!_OS 20.10      | 2         | 1.5%    |
| Pop!_OS 20.04      | 2         | 1.5%    |
| OpenMandriva 4.3   | 2         | 1.5%    |
| KDE neon 20.04     | 2         | 1.5%    |
| Fedora 35          | 2         | 1.5%    |
| Fedora 34          | 2         | 1.5%    |
| BlackPanther 18.1  | 2         | 1.5%    |
| ArcoLinux Rolling  | 2         | 1.5%    |
| Xubuntu 20.04      | 1         | 0.75%   |
| Xubuntu 16.04      | 1         | 0.75%   |
| Ubuntu Unity 18.04 | 1         | 0.75%   |
| Ubuntu MATE 20.04  | 1         | 0.75%   |
| Ubuntu 21.04       | 1         | 0.75%   |
| Ubuntu 19.04       | 1         | 0.75%   |
| ROSA 12.2          | 1         | 0.75%   |
| Reborn OS Rolling  | 1         | 0.75%   |
| Pop!_OS 22.04      | 1         | 0.75%   |
| Pop!_OS 21.10      | 1         | 0.75%   |
| OpenMandriva 4.90  | 1         | 0.75%   |
| OpenMandriva 4.2   | 1         | 0.75%   |
| Manjaro 21.2.1     | 1         | 0.75%   |
| Manjaro 20.2.1     | 1         | 0.75%   |
| Manjaro 20.2       | 1         | 0.75%   |
| Manjaro 20.1       | 1         | 0.75%   |
| Manjaro 18.1.4     | 1         | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 67        | 51.94%  |
| Fedora       | 8         | 6.2%    |
| Manjaro      | 6         | 4.65%   |
| Debian       | 6         | 4.65%   |
| Zorin        | 5         | 3.88%   |
| Pop!_OS      | 5         | 3.88%   |
| Linux Mint   | 5         | 3.88%   |
| Arch         | 5         | 3.88%   |
| OpenMandriva | 4         | 3.1%    |
| Xubuntu      | 2         | 1.55%   |
| KDE neon     | 2         | 1.55%   |
| Endless      | 2         | 1.55%   |
| BlackPanther | 2         | 1.55%   |
| ArcoLinux    | 2         | 1.55%   |
| Ubuntu Unity | 1         | 0.78%   |
| Ubuntu MATE  | 1         | 0.78%   |
| ROSA         | 1         | 0.78%   |
| Reborn OS    | 1         | 0.78%   |
| Kubuntu      | 1         | 0.78%   |
| GNOME OS     | 1         | 0.78%   |
| Feren OS     | 1         | 0.78%   |
| Elementary   | 1         | 0.78%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 7         | 4.86%   |
| 5.4.0-58-generic        | 4         | 2.78%   |
| 5.4.0-26-generic        | 4         | 2.78%   |
| 5.4.0-37-generic        | 3         | 2.08%   |
| 5.11.0-40-generic       | 3         | 2.08%   |
| 4.15.0-50-generic       | 3         | 2.08%   |
| 5.8.0-40-generic        | 2         | 1.39%   |
| 5.4.0-81-generic        | 2         | 1.39%   |
| 5.4.0-48-generic        | 2         | 1.39%   |
| 5.4.0-33-generic        | 2         | 1.39%   |
| 5.4.0-29-generic        | 2         | 1.39%   |
| 5.3.0-40-generic        | 2         | 1.39%   |
| 5.3.0-29-generic        | 2         | 1.39%   |
| 5.19.0-23-generic       | 2         | 1.39%   |
| 5.16.7-desktop-1omv4003 | 2         | 1.39%   |
| 5.0.0-23-generic        | 2         | 1.39%   |
| 6.0.6-76060006-generic  | 1         | 0.69%   |
| 5.9.3-arch1-1           | 1         | 0.69%   |
| 5.9.16-1-MANJARO        | 1         | 0.69%   |
| 5.9.11-3-MANJARO        | 1         | 0.69%   |
| 5.9.1-050901-generic    | 1         | 0.69%   |
| 5.8.7-050807-generic    | 1         | 0.69%   |
| 5.8.5-arch1-1           | 1         | 0.69%   |
| 5.8.12-050812-generic   | 1         | 0.69%   |
| 5.8.0-7642-generic      | 1         | 0.69%   |
| 5.8.0-7630-generic      | 1         | 0.69%   |
| 5.8.0-54-generic        | 1         | 0.69%   |
| 5.8.0-53-generic        | 1         | 0.69%   |
| 5.8.0-50-generic        | 1         | 0.69%   |
| 5.8.0-41-generic        | 1         | 0.69%   |
| 5.8.0-0.bpo.2-amd64     | 1         | 0.69%   |
| 5.7.6-arch1-1           | 1         | 0.69%   |
| 5.7.14-1-MANJARO        | 1         | 0.69%   |
| 5.7.14                  | 1         | 0.69%   |
| 5.6.16-1-MANJARO        | 1         | 0.69%   |
| 5.6.14-desktop-2bP      | 1         | 0.69%   |
| 5.5.11-050511-generic   | 1         | 0.69%   |
| 5.4.68-1-lts            | 1         | 0.69%   |
| 5.4.2-1-MANJARO         | 1         | 0.69%   |
| 5.4.0-73-generic        | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 33        | 24.63%  |
| 4.15.0  | 14        | 10.45%  |
| 5.8.0   | 9         | 6.72%   |
| 5.11.0  | 9         | 6.72%   |
| 5.15.0  | 7         | 5.22%   |
| 5.3.0   | 6         | 4.48%   |
| 5.10.0  | 4         | 2.99%   |
| 5.19.0  | 3         | 2.24%   |
| 5.13.0  | 3         | 2.24%   |
| 5.0.0   | 3         | 2.24%   |
| 5.7.14  | 2         | 1.49%   |
| 5.16.7  | 2         | 1.49%   |
| 4.18.0  | 2         | 1.49%   |
| 6.0.6   | 1         | 0.75%   |
| 5.9.3   | 1         | 0.75%   |
| 5.9.16  | 1         | 0.75%   |
| 5.9.11  | 1         | 0.75%   |
| 5.9.1   | 1         | 0.75%   |
| 5.8.7   | 1         | 0.75%   |
| 5.8.5   | 1         | 0.75%   |
| 5.8.12  | 1         | 0.75%   |
| 5.7.6   | 1         | 0.75%   |
| 5.6.16  | 1         | 0.75%   |
| 5.6.14  | 1         | 0.75%   |
| 5.5.11  | 1         | 0.75%   |
| 5.4.68  | 1         | 0.75%   |
| 5.4.2   | 1         | 0.75%   |
| 5.19.8  | 1         | 0.75%   |
| 5.19.13 | 1         | 0.75%   |
| 5.19.12 | 1         | 0.75%   |
| 5.18.12 | 1         | 0.75%   |
| 5.18.11 | 1         | 0.75%   |
| 5.17.4  | 1         | 0.75%   |
| 5.16.5  | 1         | 0.75%   |
| 5.16.18 | 1         | 0.75%   |
| 5.16.16 | 1         | 0.75%   |
| 5.16.12 | 1         | 0.75%   |
| 5.15.77 | 1         | 0.75%   |
| 5.15.5  | 1         | 0.75%   |
| 5.15.12 | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 35        | 26.72%  |
| 4.15    | 14        | 10.69%  |
| 5.8     | 11        | 8.4%    |
| 5.15    | 10        | 7.63%   |
| 5.11    | 9         | 6.87%   |
| 5.3     | 6         | 4.58%   |
| 5.19    | 6         | 4.58%   |
| 5.10    | 6         | 4.58%   |
| 5.16    | 5         | 3.82%   |
| 5.13    | 4         | 3.05%   |
| 5.9     | 3         | 2.29%   |
| 5.7     | 3         | 2.29%   |
| 5.0     | 3         | 2.29%   |
| 4.18    | 3         | 2.29%   |
| 5.6     | 2         | 1.53%   |
| 5.18    | 2         | 1.53%   |
| 5.14    | 2         | 1.53%   |
| 4.19    | 2         | 1.53%   |
| 6.0     | 1         | 0.76%   |
| 5.5     | 1         | 0.76%   |
| 5.17    | 1         | 0.76%   |
| 5.12    | 1         | 0.76%   |
| 4.4     | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 123       | 98.4%   |
| i686   | 2         | 1.6%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 82        | 63.08%  |
| Unknown    | 18        | 13.85%  |
| KDE5       | 10        | 7.69%   |
| X-Cinnamon | 5         | 3.85%   |
| XFCE       | 4         | 3.08%   |
| KDE        | 4         | 3.08%   |
| MATE       | 2         | 1.54%   |
| Unity      | 1         | 0.77%   |
| Pantheon   | 1         | 0.77%   |
| DWM        | 1         | 0.77%   |
| bspwm      | 1         | 0.77%   |
| awesome    | 1         | 0.77%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 92        | 71.88%  |
| Wayland | 25        | 19.53%  |
| Unknown | 11        | 8.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 57.81%  |
| GDM     | 24        | 18.75%  |
| GDM3    | 12        | 9.38%   |
| SDDM    | 11        | 8.59%   |
| LightDM | 5         | 3.91%   |
| TDM     | 2         | 1.56%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 93        | 73.81%  |
| Unknown | 15        | 11.9%   |
| C       | 6         | 4.76%   |
| en_GB   | 5         | 3.97%   |
| ru_RU   | 1         | 0.79%   |
| hu_HU   | 1         | 0.79%   |
| en_IN   | 1         | 0.79%   |
| en_AU   | 1         | 0.79%   |
| en_AG   | 1         | 0.79%   |
| de_DE   | 1         | 0.79%   |
| ar_AE   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 72        | 55.38%  |
| BIOS | 58        | 44.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 105       | 84%     |
| Btrfs   | 10        | 8%      |
| Overlay | 7         | 5.6%    |
| Xfs     | 2         | 1.6%    |
| Unknown | 1         | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 78        | 61.9%   |
| GPT     | 40        | 31.75%  |
| MBR     | 8         | 6.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 88.89%  |
| Yes       | 14        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 59.38%  |
| Yes       | 52        | 40.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 33        | 26.4%   |
| Lenovo                      | 30        | 24%     |
| Dell                        | 17        | 13.6%   |
| ASUSTek Computer            | 14        | 11.2%   |
| Toshiba                     | 5         | 4%      |
| Intel                       | 4         | 3.2%    |
| MSI                         | 3         | 2.4%    |
| Gigabyte Technology         | 3         | 2.4%    |
| Sony                        | 2         | 1.6%    |
| Microsoft                   | 2         | 1.6%    |
| Google                      | 2         | 1.6%    |
| Acer                        | 2         | 1.6%    |
| YJKC                        | 1         | 0.8%    |
| win element                 | 1         | 0.8%    |
| Notebook                    | 1         | 0.8%    |
| LG Electronics              | 1         | 0.8%    |
| I-Life Digital Technologies | 1         | 0.8%    |
| ECS                         | 1         | 0.8%    |
| Biostar                     | 1         | 0.8%    |
| Apple                       | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| HP Pavilion Notebook                        | 2         | 1.6%    |
| HP ENVY Laptop 13-aq0xxx                    | 2         | 1.6%    |
| HP All-in-One 22-c0xx                       | 2         | 1.6%    |
| ASUS All Series                             | 2         | 1.6%    |
| YJKC vBOOK Plus                             | 1         | 0.8%    |
| win element MoreFine S500+                  | 1         | 0.8%    |
| Toshiba TECRA X40-D                         | 1         | 0.8%    |
| Toshiba TECRA A50-C                         | 1         | 0.8%    |
| Toshiba Satellite C850-A966                 | 1         | 0.8%    |
| Toshiba Satellite C660                      | 1         | 0.8%    |
| Toshiba Satellite A300                      | 1         | 0.8%    |
| Sony VGN-NS10J_S                            | 1         | 0.8%    |
| Sony SVE14A25CAB                            | 1         | 0.8%    |
| Notebook P95_96_97Ex,Rx                     | 1         | 0.8%    |
| MSI PS63 Modern 8RD                         | 1         | 0.8%    |
| MSI MS-7850                                 | 1         | 0.8%    |
| MSI Modern 14 B5M                           | 1         | 0.8%    |
| Microsoft Surface Pro 4                     | 1         | 0.8%    |
| Microsoft Surface Pro 3                     | 1         | 0.8%    |
| LG C500-G.AEF5BE1                           | 1         | 0.8%    |
| Lenovo Yoga S730-13IWL 81J0                 | 1         | 0.8%    |
| Lenovo Yoga 2 Pro 20266                     | 1         | 0.8%    |
| Lenovo ThinkPad Yoga 260 20FD000GAD         | 1         | 0.8%    |
| Lenovo ThinkPad X240 20AMS6GB00             | 1         | 0.8%    |
| Lenovo ThinkPad X230 2325DV8                | 1         | 0.8%    |
| Lenovo ThinkPad X1 Yoga 4th 20QF0015US      | 1         | 0.8%    |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 1         | 0.8%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A9US  | 1         | 0.8%    |
| Lenovo ThinkPad T61 76653JG                 | 1         | 0.8%    |
| Lenovo ThinkPad T480s 20L8S3FV00            | 1         | 0.8%    |
| Lenovo ThinkPad T480s 20L7001PAD            | 1         | 0.8%    |
| Lenovo ThinkPad T470 W10DG 20JMS0Q300       | 1         | 0.8%    |
| Lenovo ThinkPad T460 20FMS1A200             | 1         | 0.8%    |
| Lenovo ThinkPad P1 Gen 5 21DC000DCK         | 1         | 0.8%    |
| Lenovo ThinkPad P1 Gen 3 20TJS4RX00         | 1         | 0.8%    |
| Lenovo ThinkPad L480 20LS0012AD             | 1         | 0.8%    |
| Lenovo ThinkPad E14 Gen 2 20TA0018AD        | 1         | 0.8%    |
| Lenovo ThinkCentre E93 10AR004LAX           | 1         | 0.8%    |
| Lenovo ThinkCentre E73 10AS0041AX           | 1         | 0.8%    |
| Lenovo Legion Y7000P 81LD                   | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 15        | 12%     |
| HP Pavilion          | 9         | 7.2%    |
| Lenovo IdeaPad       | 7         | 5.6%    |
| HP EliteBook         | 6         | 4.8%    |
| Dell Latitude        | 5         | 4%      |
| ASUS ROG             | 4         | 3.2%    |
| Toshiba Satellite    | 3         | 2.4%    |
| HP ProBook           | 3         | 2.4%    |
| HP Laptop            | 3         | 2.4%    |
| HP ENVY              | 3         | 2.4%    |
| Dell Precision       | 3         | 2.4%    |
| Dell Inspiron        | 3         | 2.4%    |
| ASUS PRIME           | 3         | 2.4%    |
| Toshiba TECRA        | 2         | 1.6%    |
| Microsoft Surface    | 2         | 1.6%    |
| Lenovo Yoga          | 2         | 1.6%    |
| Lenovo ThinkCentre   | 2         | 1.6%    |
| HP All-in-One        | 2         | 1.6%    |
| Dell OptiPlex        | 2         | 1.6%    |
| ASUS VivoBook        | 2         | 1.6%    |
| ASUS All             | 2         | 1.6%    |
| YJKC vBOOK           | 1         | 0.8%    |
| win element MoreFine | 1         | 0.8%    |
| Sony VGN-NS10J       | 1         | 0.8%    |
| Sony SVE14A25CAB     | 1         | 0.8%    |
| Notebook P95         | 1         | 0.8%    |
| MSI PS63             | 1         | 0.8%    |
| MSI MS-7850          | 1         | 0.8%    |
| MSI Modern           | 1         | 0.8%    |
| LG C500-G.AEF5BE1    | 1         | 0.8%    |
| Lenovo Legion        | 1         | 0.8%    |
| Lenovo IdeaPadFlex   | 1         | 0.8%    |
| Lenovo G500          | 1         | 0.8%    |
| Lenovo 81FV          | 1         | 0.8%    |
| Intel NUC6i7KYB      | 1         | 0.8%    |
| Intel NUC10i3FNH     | 1         | 0.8%    |
| Intel DH67CL         | 1         | 0.8%    |
| Intel D865PERL       | 1         | 0.8%    |
| I-Life Digital ZED   | 1         | 0.8%    |
| HP Z800              | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 17        | 13.6%   |
| 2020 | 14        | 11.2%   |
| 2018 | 14        | 11.2%   |
| 2013 | 12        | 9.6%    |
| 2021 | 9         | 7.2%    |
| 2012 | 9         | 7.2%    |
| 2016 | 8         | 6.4%    |
| 2010 | 8         | 6.4%    |
| 2017 | 7         | 5.6%    |
| 2011 | 6         | 4.8%    |
| 2014 | 5         | 4%      |
| 2015 | 4         | 3.2%    |
| 2022 | 3         | 2.4%    |
| 2009 | 3         | 2.4%    |
| 2007 | 3         | 2.4%    |
| 2008 | 2         | 1.6%    |
| 2005 | 1         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 86        | 68.8%   |
| Desktop     | 26        | 20.8%   |
| Convertible | 6         | 4.8%    |
| Tablet      | 2         | 1.6%    |
| Mini pc     | 2         | 1.6%    |
| All in one  | 2         | 1.6%    |
| Server      | 1         | 0.8%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 110       | 87.3%   |
| Enabled  | 16        | 12.7%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 98.4%   |
| Yes  | 2         | 1.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 29        | 23.2%   |
| 16.01-24.0      | 28        | 22.4%   |
| 3.01-4.0        | 21        | 16.8%   |
| 8.01-16.0       | 20        | 16%     |
| 32.01-64.0      | 12        | 9.6%    |
| 64.01-256.0     | 6         | 4.8%    |
| 0.51-1.0        | 3         | 2.4%    |
| 2.01-3.0        | 2         | 1.6%    |
| 1.01-2.0        | 2         | 1.6%    |
| More than 256.0 | 1         | 0.8%    |
| 24.01-32.0      | 1         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 42        | 31.34%  |
| 2.01-3.0  | 30        | 22.39%  |
| 4.01-8.0  | 27        | 20.15%  |
| 3.01-4.0  | 21        | 15.67%  |
| 8.01-16.0 | 7         | 5.22%   |
| 0.51-1.0  | 5         | 3.73%   |
| 0.01-0.5  | 2         | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 72.22%  |
| 2      | 23        | 18.25%  |
| 3      | 5         | 3.97%   |
| 4      | 3         | 2.38%   |
| 0      | 2         | 1.59%   |
| 9      | 1         | 0.79%   |
| 8      | 1         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 69.6%   |
| Yes       | 38        | 30.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 76.8%   |
| No        | 29        | 23.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 86.4%   |
| No        | 17        | 13.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 70.08%  |
| No        | 38        | 29.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UAE     | 125       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Dubai            | 56        | 43.75%  |
| Abu Dhabi        | 41        | 32.03%  |
| Sharjah          | 17        | 13.28%  |
| Al Ain City      | 7         | 5.47%   |
| Al Fujairah City | 3         | 2.34%   |
| Ajman            | 3         | 2.34%   |
| Al Halah         | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 29        | 33     | 18.01%  |
| Samsung Electronics   | 29        | 43     | 18.01%  |
| Seagate               | 18        | 24     | 11.18%  |
| Toshiba               | 17        | 21     | 10.56%  |
| Unknown               | 7         | 14     | 4.35%   |
| Intel                 | 7         | 9      | 4.35%   |
| HGST                  | 7         | 8      | 4.35%   |
| Kingston              | 5         | 5      | 3.11%   |
| Crucial               | 5         | 6      | 3.11%   |
| SK hynix              | 4         | 5      | 2.48%   |
| SanDisk               | 4         | 5      | 2.48%   |
| Micron Technology     | 4         | 4      | 2.48%   |
| Hitachi               | 4         | 4      | 2.48%   |
| Phison                | 2         | 2      | 1.24%   |
| Lexar                 | 2         | 2      | 1.24%   |
| Apple                 | 2         | 3      | 1.24%   |
| USB3.0                | 1         | 1      | 0.62%   |
| Transcend             | 1         | 1      | 0.62%   |
| Team                  | 1         | 1      | 0.62%   |
| Realtek Semiconductor | 1         | 1      | 0.62%   |
| Patriot               | 1         | 1      | 0.62%   |
| OCZ                   | 1         | 1      | 0.62%   |
| Maxtor                | 1         | 1      | 0.62%   |
| Lite-On               | 1         | 1      | 0.62%   |
| Lenovo                | 1         | 1      | 0.62%   |
| KingSpec              | 1         | 2      | 0.62%   |
| Gigabyte Technology   | 1         | 1      | 0.62%   |
| Fujitsu               | 1         | 1      | 0.62%   |
| External              | 1         | 1      | 0.62%   |
| Corsair               | 1         | 1      | 0.62%   |
| China                 | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 4         | 2.34%   |
| HGST HTS725050A7E630 500GB             | 4         | 2.34%   |
| Intel NVMe SSD Drive 512GB             | 3         | 1.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 1.17%   |
| WDC WD10SPZX-08Z10 1TB                 | 2         | 1.17%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 2         | 1.17%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB     | 2         | 1.17%   |
| Unknown SD/MMC/MS PRO 8GB              | 2         | 1.17%   |
| Unknown MMC Card  16GB                 | 2         | 1.17%   |
| Toshiba MQ01ABD075 752GB               | 2         | 1.17%   |
| Toshiba DT01ACA100 1TB                 | 2         | 1.17%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 1.17%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 1.17%   |
| Samsung SSD 970 EVO Plus 500GB         | 2         | 1.17%   |
| Samsung SSD 850 PRO 1TB                | 2         | 1.17%   |
| Samsung SSD 850 EVO 250GB              | 2         | 1.17%   |
| Intel SSDPEKNW512G8H 512GB             | 2         | 1.17%   |
| HGST HTS721010A9E630 1TB               | 2         | 1.17%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 1.17%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.58%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.58%   |
| WDC WDS120G1G0A-00SS50 120GB SSD       | 1         | 0.58%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.58%   |
| WDC WD800BB-55JHC0 80GB                | 1         | 0.58%   |
| WDC WD6400AAKS-22A7B0 640GB            | 1         | 0.58%   |
| WDC WD5000LPVX-60V0TT0 500GB           | 1         | 0.58%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 1         | 0.58%   |
| WDC WD5000LPCX-22VHAT1 500GB           | 1         | 0.58%   |
| WDC WD5000AAKS-65V0A0 500GB            | 1         | 0.58%   |
| WDC WD5000AAKS-00A7B2 500GB            | 1         | 0.58%   |
| WDC WD40EFRX-68N32N0 4TB               | 1         | 0.58%   |
| WDC WD2500BEVS-26UST0 250GB            | 1         | 0.58%   |
| WDC WD2500AAJS-75M0A0 249GB            | 1         | 0.58%   |
| WDC WD20EZRX-00D8PB0 2TB               | 1         | 0.58%   |
| WDC WD1600AAJS-60B4A0 160GB            | 1         | 0.58%   |
| WDC WD1200BEVS-08UST0 120GB            | 1         | 0.58%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 0.58%   |
| WDC WD10JPVX-60JC3T1 1TB               | 1         | 0.58%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 21        | 25     | 30.43%  |
| Seagate | 18        | 24     | 26.09%  |
| Toshiba | 14        | 18     | 20.29%  |
| HGST    | 7         | 8      | 10.14%  |
| Hitachi | 4         | 4      | 5.8%    |
| Unknown | 2         | 5      | 2.9%    |
| Maxtor  | 1         | 1      | 1.45%   |
| Fujitsu | 1         | 1      | 1.45%   |
| Apple   | 1         | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 18     | 32.35%  |
| WDC                 | 5         | 5      | 14.71%  |
| Crucial             | 4         | 5      | 11.76%  |
| Kingston            | 3         | 3      | 8.82%   |
| USB3.0              | 1         | 1      | 2.94%   |
| Transcend           | 1         | 1      | 2.94%   |
| Team                | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| SanDisk             | 1         | 1      | 2.94%   |
| Patriot             | 1         | 1      | 2.94%   |
| Lexar               | 1         | 1      | 2.94%   |
| KingSpec            | 1         | 2      | 2.94%   |
| Gigabyte Technology | 1         | 1      | 2.94%   |
| Corsair             | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 87     | 42.76%  |
| NVMe | 50        | 65     | 34.48%  |
| SSD  | 28        | 43     | 19.31%  |
| MMC  | 5         | 9      | 3.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 78        | 123    | 57.35%  |
| NVMe | 49        | 64     | 36.03%  |
| MMC  | 5         | 9      | 3.68%   |
| SAS  | 4         | 8      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 73     | 58.95%  |
| 0.51-1.0   | 32        | 42     | 33.68%  |
| 1.01-2.0   | 5         | 9      | 5.26%   |
| 3.01-4.0   | 1         | 5      | 1.05%   |
| 4.01-10.0  | 1         | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 38        | 29.69%  |
| 101-250        | 30        | 23.44%  |
| 21-50          | 11        | 8.59%   |
| 501-1000       | 11        | 8.59%   |
| 1001-2000      | 9         | 7.03%   |
| 51-100         | 9         | 7.03%   |
| Unknown        | 7         | 5.47%   |
| 1-20           | 6         | 4.69%   |
| 2001-3000      | 4         | 3.13%   |
| More than 3000 | 3         | 2.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 58        | 42.65%  |
| 21-50     | 30        | 22.06%  |
| 51-100    | 16        | 11.76%  |
| 101-250   | 11        | 8.09%   |
| 251-500   | 7         | 5.15%   |
| Unknown   | 7         | 5.15%   |
| 501-1000  | 5         | 3.68%   |
| 2001-3000 | 1         | 0.74%   |
| 1001-2000 | 1         | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T1 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 83        | 134    | 66.94%  |
| Works    | 40        | 69     | 32.26%  |
| Malfunc  | 1         | 1      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 95        | 61.29%  |
| Samsung Electronics          | 19        | 12.26%  |
| SanDisk                      | 6         | 3.87%   |
| AMD                          | 5         | 3.23%   |
| Micron Technology            | 4         | 2.58%   |
| Toshiba America Info Systems | 3         | 1.94%   |
| SK hynix                     | 3         | 1.94%   |
| Phison Electronics           | 2         | 1.29%   |
| LSI Logic / Symbios Logic    | 2         | 1.29%   |
| Kingston Technology Company  | 2         | 1.29%   |
| ASMedia Technology           | 2         | 1.29%   |
| VIA Technologies             | 1         | 0.65%   |
| Silicon Motion               | 1         | 0.65%   |
| Realtek Semiconductor        | 1         | 0.65%   |
| OCZ Technology Group         | 1         | 0.65%   |
| Nvidia                       | 1         | 0.65%   |
| Micron/Crucial Technology    | 1         | 0.65%   |
| Marvell Technology Group     | 1         | 0.65%   |
| Lite-On Technology           | 1         | 0.65%   |
| Lenovo                       | 1         | 0.65%   |
| JMicron Technology           | 1         | 0.65%   |
| Broadcom / LSI               | 1         | 0.65%   |
| Apple                        | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 7.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 5.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 4.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 4.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.07%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.91%   |
| Intel SSD 660P Series                                                          | 5         | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 2.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 2.33%   |
| Micron Non-Volatile memory controller                                          | 4         | 2.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 2.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.74%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.16%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.16%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.16%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.16%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.16%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 1.16%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.16%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.16%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.58%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.58%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.58%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 76        | 50%     |
| NVMe | 49        | 32.24%  |
| RAID | 17        | 11.18%  |
| IDE  | 8         | 5.26%   |
| SAS  | 1         | 0.66%   |
| SCSI | 1         | 0.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 114       | 91.2%   |
| AMD    | 11        | 8.8%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz           | 5         | 4%      |
| Intel Core i5-4200U CPU @ 1.60GHz           | 5         | 4%      |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 3.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 2.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 2.4%    |
| Intel Core i3-10110U CPU @ 2.10GHz          | 3         | 2.4%    |
| Intel Xeon CPU E5620 @ 2.40GHz              | 2         | 1.6%    |
| Intel Core i9-10885H CPU @ 2.40GHz          | 2         | 1.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 1.6%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 1.6%    |
| Intel Core i5-9400T CPU @ 1.80GHz           | 2         | 1.6%    |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.6%    |
| Intel Xeon Silver 4214 CPU @ 2.20GHz        | 1         | 0.8%    |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz         | 1         | 0.8%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.8%    |
| Intel Pentium 4 CPU 2.80GHz                 | 1         | 0.8%    |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 0.8%    |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.8%    |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.8%    |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.8%    |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.8%    |
| Intel Core i7-7740X CPU @ 4.30GHz           | 1         | 0.8%    |
| Intel Core i7-6770HQ CPU @ 2.60GHz          | 1         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.8%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.8%    |
| Intel Core i7-5960X CPU @ 3.00GHz           | 1         | 0.8%    |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1         | 0.8%    |
| Intel Core i7-4790S CPU @ 3.20GHz           | 1         | 0.8%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.8%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.8%    |
| Intel Core i7-4600M CPU @ 2.90GHz           | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 33.6%   |
| Intel Core i7           | 40        | 32%     |
| Intel Core i3           | 8         | 6.4%    |
| Other                   | 5         | 4%      |
| AMD Ryzen 5             | 4         | 3.2%    |
| Intel Xeon              | 3         | 2.4%    |
| Intel Core i9           | 3         | 2.4%    |
| Intel Core 2 Duo        | 3         | 2.4%    |
| Intel Celeron           | 3         | 2.4%    |
| AMD Ryzen 9             | 2         | 1.6%    |
| Intel Xeon Silver       | 1         | 0.8%    |
| Intel Pentium Dual-Core | 1         | 0.8%    |
| Intel Pentium 4         | 1         | 0.8%    |
| Intel Core m5           | 1         | 0.8%    |
| Intel Core 2 Quad       | 1         | 0.8%    |
| Intel Celeron M         | 1         | 0.8%    |
| Intel Atom              | 1         | 0.8%    |
| AMD Sempron             | 1         | 0.8%    |
| AMD Ryzen Threadripper  | 1         | 0.8%    |
| AMD Ryzen 7 PRO         | 1         | 0.8%    |
| AMD Ryzen 7             | 1         | 0.8%    |
| AMD A6                  | 1         | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 41.6%   |
| 4      | 42        | 33.6%   |
| 6      | 12        | 9.6%    |
| 8      | 10        | 8%      |
| 1      | 4         | 3.2%    |
| 16     | 2         | 1.6%    |
| 14     | 2         | 1.6%    |
| 12     | 1         | 0.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 123       | 98.4%   |
| 2      | 2         | 1.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 104       | 83.2%   |
| 1      | 21        | 16.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 122       | 97.6%   |
| 32-bit         | 2         | 1.6%    |
| Unknown        | 1         | 0.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 20.77%  |
| 0x306a9    | 9         | 6.92%   |
| 0x806ec    | 7         | 5.38%   |
| 0x406e3    | 7         | 5.38%   |
| 0x906ea    | 6         | 4.62%   |
| 0x40651    | 6         | 4.62%   |
| 0x206a7    | 6         | 4.62%   |
| 0x906e9    | 4         | 3.08%   |
| 0x806ea    | 4         | 3.08%   |
| 0x806e9    | 4         | 3.08%   |
| 0x306c3    | 4         | 3.08%   |
| 0xa0652    | 3         | 2.31%   |
| 0x806c1    | 3         | 2.31%   |
| 0x20655    | 3         | 2.31%   |
| 0x906ed    | 2         | 1.54%   |
| 0x806eb    | 2         | 1.54%   |
| 0x6fd      | 2         | 1.54%   |
| 0x506e3    | 2         | 1.54%   |
| 0x306f2    | 2         | 1.54%   |
| 0x306d4    | 2         | 1.54%   |
| 0x206c2    | 2         | 1.54%   |
| 0xf29      | 1         | 0.77%   |
| 0xa0655    | 1         | 0.77%   |
| 0x906a3    | 1         | 0.77%   |
| 0x706a1    | 1         | 0.77%   |
| 0x6fb      | 1         | 0.77%   |
| 0x6e8      | 1         | 0.77%   |
| 0x406c4    | 1         | 0.77%   |
| 0x406c3    | 1         | 0.77%   |
| 0x306e4    | 1         | 0.77%   |
| 0x20652    | 1         | 0.77%   |
| 0x106e5    | 1         | 0.77%   |
| 0x1067a    | 1         | 0.77%   |
| 0x0a601203 | 1         | 0.77%   |
| 0x0a50000c | 1         | 0.77%   |
| 0x08608103 | 1         | 0.77%   |
| 0x08608102 | 1         | 0.77%   |
| 0x08600106 | 1         | 0.77%   |
| 0x08600104 | 1         | 0.77%   |
| 0x08600102 | 1         | 0.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 29.6%   |
| Haswell          | 15        | 12%     |
| Skylake          | 12        | 9.6%    |
| IvyBridge        | 11        | 8.8%    |
| SandyBridge      | 8         | 6.4%    |
| Westmere         | 7         | 5.6%    |
| CometLake        | 4         | 3.2%    |
| Broadwell        | 4         | 3.2%    |
| Unknown          | 4         | 3.2%    |
| TigerLake        | 3         | 2.4%    |
| Core             | 3         | 2.4%    |
| Zen+             | 2         | 1.6%    |
| Zen 2            | 2         | 1.6%    |
| Silvermont       | 2         | 1.6%    |
| Penryn           | 2         | 1.6%    |
| Zen 3            | 1         | 0.8%    |
| Zen              | 1         | 0.8%    |
| Piledriver       | 1         | 0.8%    |
| P6               | 1         | 0.8%    |
| NetBurst         | 1         | 0.8%    |
| Nehalem          | 1         | 0.8%    |
| K8 Hammer        | 1         | 0.8%    |
| Goldmont plus    | 1         | 0.8%    |
| Alderlake Hybrid | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 96        | 55.81%  |
| Nvidia                     | 54        | 31.4%   |
| AMD                        | 21        | 12.21%  |
| Matrox Electronics Systems | 1         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 5.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 5.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.47%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.89%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 2.31%   |
| Intel HD Graphics 620                                                                    | 4         | 2.31%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.31%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 1.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.73%   |
| Intel HD Graphics 530                                                                    | 3         | 1.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.16%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.16%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.16%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.16%   |
| Intel HD Graphics 630                                                                    | 2         | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.16%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.16%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.16%   |
| AMD Renoir                                                                               | 2         | 1.16%   |
| AMD Lucienne                                                                             | 2         | 1.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.58%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.58%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.58%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.58%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.58%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1         | 0.58%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 50        | 40%     |
| Intel + Nvidia     | 35        | 28%     |
| 1 x Nvidia         | 17        | 13.6%   |
| Intel + AMD        | 10        | 8%      |
| 1 x AMD            | 10        | 8%      |
| 1 x Matrox         | 1         | 0.8%    |
| Intel + 2 x Nvidia | 1         | 0.8%    |
| AMD + Nvidia       | 1         | 0.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 98        | 77.78%  |
| Proprietary | 23        | 18.25%  |
| Unknown     | 5         | 3.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 52.76%  |
| 1.01-2.0   | 23        | 18.11%  |
| 3.01-4.0   | 12        | 9.45%   |
| 0.01-0.5   | 11        | 8.66%   |
| 7.01-8.0   | 5         | 3.94%   |
| 0.51-1.0   | 5         | 3.94%   |
| 2.01-3.0   | 2         | 1.57%   |
| 5.01-6.0   | 1         | 0.79%   |
| 16.01-24.0 | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 15.56%  |
| Samsung Electronics     | 18        | 13.33%  |
| BOE                     | 17        | 12.59%  |
| LG Display              | 16        | 11.85%  |
| Chimei Innolux          | 14        | 10.37%  |
| Goldstar                | 8         | 5.93%   |
| Dell                    | 5         | 3.7%    |
| Lenovo                  | 4         | 2.96%   |
| Hewlett-Packard         | 4         | 2.96%   |
| BenQ                    | 4         | 2.96%   |
| Ancor Communications    | 3         | 2.22%   |
| Sharp                   | 2         | 1.48%   |
| LG Philips              | 2         | 1.48%   |
| InfoVision              | 2         | 1.48%   |
| Chi Mei Optoelectronics | 2         | 1.48%   |
| ViewSonic               | 1         | 0.74%   |
| Seiko/Epson             | 1         | 0.74%   |
| RTK                     | 1         | 0.74%   |
| Philips                 | 1         | 0.74%   |
| Panasonic               | 1         | 0.74%   |
| Mi                      | 1         | 0.74%   |
| LGD                     | 1         | 0.74%   |
| LG Electronics          | 1         | 0.74%   |
| Hitachi                 | 1         | 0.74%   |
| Gigabyte Technology     | 1         | 0.74%   |
| CSO                     | 1         | 0.74%   |
| Apple                   | 1         | 0.74%   |
| AOC                     | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 2         | 1.46%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch            | 2         | 1.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.46%   |
| Hewlett-Packard ALL-in-One HPN401F 1920x1080 476x268mm 21.5-inch        | 2         | 1.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 1.46%   |
| BOE LCD Monitor BOE06B3 1920x1080 310x170mm 13.9-inch                   | 2         | 1.46%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 1.46%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch          | 2         | 1.46%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch          | 2         | 1.46%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch          | 2         | 1.46%   |
| ViewSonic VA1918wm VSCC821 1440x900 410x256mm 19.0-inch                 | 1         | 0.73%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.73%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.73%   |
| Seiko/Epson LCD Monitor 1280x800                                        | 1         | 0.73%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.73%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5741 1280x800 261x163mm 12.1-inch    | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch   | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4341 1366x768 344x194mm 15.5-inch    | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4157 3840x2160 344x194mm 15.5-inch   | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch   | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch   | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SAM0D74 1920x1080 1210x680mm 54.6-inch  | 1         | 0.73%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1         | 0.73%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch       | 1         | 0.73%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                  | 1         | 0.73%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                      | 1         | 0.73%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                      | 1         | 0.73%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                        | 1         | 0.73%   |
| LGD LCD Monitor 1366x768                                                | 1         | 0.73%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch           | 1         | 0.73%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch             | 1         | 0.73%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                       | 1         | 0.73%   |
| LG Display LCD Monitor LGD05EF 2560x1440 309x174mm 14.0-inch            | 1         | 0.73%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 1         | 0.73%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 60        | 45.8%   |
| 1366x768 (WXGA)   | 33        | 25.19%  |
| 3840x2160 (4K)    | 11        | 8.4%    |
| 2560x1440 (QHD)   | 5         | 3.82%   |
| 1600x900 (HD+)    | 4         | 3.05%   |
| 1280x800 (WXGA)   | 4         | 3.05%   |
| 1920x1200 (WUXGA) | 3         | 2.29%   |
| 2560x1080         | 2         | 1.53%   |
| 1440x900 (WXGA+)  | 2         | 1.53%   |
| 3440x1440         | 1         | 0.76%   |
| 3200x1800 (QHD+)  | 1         | 0.76%   |
| 2880x1920         | 1         | 0.76%   |
| 2736x1824         | 1         | 0.76%   |
| 2560x1600         | 1         | 0.76%   |
| 2304x1440         | 1         | 0.76%   |
| 2160x1440         | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 38        | 27.94%  |
| 14      | 23        | 16.91%  |
| 13      | 15        | 11.03%  |
| 24      | 8         | 5.88%   |
| 21      | 8         | 5.88%   |
| 12      | 7         | 5.15%   |
| 27      | 6         | 4.41%   |
| 23      | 4         | 2.94%   |
| Unknown | 4         | 2.94%   |
| 84      | 3         | 2.21%   |
| 31      | 3         | 2.21%   |
| 19      | 3         | 2.21%   |
| 16      | 3         | 2.21%   |
| 34      | 2         | 1.47%   |
| 18      | 2         | 1.47%   |
| 11      | 2         | 1.47%   |
| 54      | 1         | 0.74%   |
| 52      | 1         | 0.74%   |
| 46      | 1         | 0.74%   |
| 20      | 1         | 0.74%   |
| 17      | 1         | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 69        | 51.49%  |
| 501-600     | 18        | 13.43%  |
| 201-300     | 17        | 12.69%  |
| 401-500     | 13        | 9.7%    |
| Unknown     | 4         | 2.99%   |
| 601-700     | 3         | 2.24%   |
| 351-400     | 3         | 2.24%   |
| 1501-2000   | 3         | 2.24%   |
| 701-800     | 2         | 1.49%   |
| 1001-1500   | 2         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 105       | 85.37%  |
| 16/10   | 11        | 8.94%   |
| Unknown | 4         | 3.25%   |
| 21/9    | 2         | 1.63%   |
| 3/2     | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 28.68%  |
| 81-90          | 30        | 22.06%  |
| 201-250        | 13        | 9.56%   |
| 71-80          | 8         | 5.88%   |
| 151-200        | 8         | 5.88%   |
| 61-70          | 7         | 5.15%   |
| 301-350        | 6         | 4.41%   |
| More than 1000 | 5         | 3.68%   |
| 351-500        | 5         | 3.68%   |
| Unknown        | 4         | 2.94%   |
| 251-300        | 3         | 2.21%   |
| 51-60          | 2         | 1.47%   |
| 141-150        | 2         | 1.47%   |
| 111-120        | 2         | 1.47%   |
| 121-130        | 1         | 0.74%   |
| 501-1000       | 1         | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 44        | 33.08%  |
| 101-120       | 35        | 26.32%  |
| 51-100        | 30        | 22.56%  |
| 161-240       | 12        | 9.02%   |
| More than 240 | 6         | 4.51%   |
| Unknown       | 4         | 3.01%   |
| 1-50          | 2         | 1.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 101       | 78.91%  |
| 2     | 19        | 14.84%  |
| 0     | 6         | 4.69%   |
| 3     | 2         | 1.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 78        | 43.09%  |
| Realtek Semiconductor    | 55        | 30.39%  |
| Qualcomm Atheros         | 13        | 7.18%   |
| Broadcom                 | 12        | 6.63%   |
| Ralink                   | 4         | 2.21%   |
| Marvell Technology Group | 4         | 2.21%   |
| TP-Link                  | 3         | 1.66%   |
| ASIX Electronics         | 2         | 1.1%    |
| Wilocity                 | 1         | 0.55%   |
| VIA Technologies         | 1         | 0.55%   |
| SILICON Laboratories     | 1         | 0.55%   |
| Sigma Designs            | 1         | 0.55%   |
| Ralink Technology        | 1         | 0.55%   |
| Nvidia                   | 1         | 0.55%   |
| MediaTek                 | 1         | 0.55%   |
| Lenovo                   | 1         | 0.55%   |
| D-Link                   | 1         | 0.55%   |
| Broadcom Limited         | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 14.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 6.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 2.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.26%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.26%   |
| Intel Wireless 8260                                               | 5         | 2.26%   |
| Intel Wireless 7260                                               | 5         | 2.26%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.36%   |
| Intel Wireless 7265                                               | 3         | 1.36%   |
| Intel Wireless 3165                                               | 3         | 1.36%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.36%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.36%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2         | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.9%    |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.9%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.9%    |
| Intel I211 Gigabit Network Connection                             | 2         | 0.9%    |
| Intel I210 Gigabit Network Connection                             | 2         | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.9%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.9%    |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.9%    |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.9%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 63        | 55.75%  |
| Realtek Semiconductor    | 19        | 16.81%  |
| Qualcomm Atheros         | 9         | 7.96%   |
| Broadcom                 | 8         | 7.08%   |
| Ralink                   | 4         | 3.54%   |
| TP-Link                  | 3         | 2.65%   |
| Marvell Technology Group | 2         | 1.77%   |
| Wilocity                 | 1         | 0.88%   |
| Ralink Technology        | 1         | 0.88%   |
| MediaTek                 | 1         | 0.88%   |
| D-Link                   | 1         | 0.88%   |
| Broadcom Limited         | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 5.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.42%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.42%   |
| Intel Wireless 8260                                            | 5         | 4.42%   |
| Intel Wireless 7260                                            | 5         | 4.42%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 4.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 3.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2.65%   |
| Intel Wireless 7265                                            | 3         | 2.65%   |
| Intel Wireless 3165                                            | 3         | 2.65%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.65%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 2.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.65%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2         | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.77%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.77%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 1.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.77%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.77%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.77%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.77%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 0.88%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.88%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 48.98%  |
| Intel                    | 35        | 35.71%  |
| Qualcomm Atheros         | 4         | 4.08%   |
| Broadcom                 | 4         | 4.08%   |
| Marvell Technology Group | 2         | 2.04%   |
| ASIX Electronics         | 2         | 2.04%   |
| VIA Technologies         | 1         | 1.02%   |
| Nvidia                   | 1         | 1.02%   |
| Lenovo                   | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 30.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 13.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5.66%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.83%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.89%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.89%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.89%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.89%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.89%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.94%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.94%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.94%   |
| Marvell Group 88E8070 based Ethernet Controller                   | 1         | 0.94%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.94%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.94%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.94%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.94%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.94%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.94%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.94%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.94%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.94%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.94%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 108       | 52.68%  |
| Ethernet | 95        | 46.34%  |
| Modem    | 2         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 90        | 69.77%  |
| Ethernet | 39        | 30.23%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 75        | 60%     |
| 1     | 45        | 36%     |
| 3     | 2         | 1.6%    |
| 8     | 1         | 0.8%    |
| 4     | 1         | 0.8%    |
| 0     | 1         | 0.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 101       | 80.8%   |
| Yes  | 24        | 19.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 56.18%  |
| Realtek Semiconductor           | 11        | 12.36%  |
| Qualcomm Atheros Communications | 6         | 6.74%   |
| Broadcom                        | 4         | 4.49%   |
| ASUSTek Computer                | 4         | 4.49%   |
| Ralink                          | 3         | 3.37%   |
| Toshiba                         | 2         | 2.25%   |
| Marvell Semiconductor           | 2         | 2.25%   |
| Dell                            | 2         | 2.25%   |
| Cambridge Silicon Radio         | 2         | 2.25%   |
| MediaTek                        | 1         | 1.12%   |
| Hewlett-Packard                 | 1         | 1.12%   |
| Foxconn / Hon Hai               | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 18        | 20.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 12        | 13.48%  |
| Realtek Bluetooth Radio                               | 7         | 7.87%   |
| Intel AX201 Bluetooth                                 | 7         | 7.87%   |
| Intel AX200 Bluetooth                                 | 5         | 5.62%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3         | 3.37%   |
| Ralink RT3290 Bluetooth                               | 3         | 3.37%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 3.37%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 2.25%   |
| Intel Bluetooth Device                                | 2         | 2.25%   |
| Intel AX210 Bluetooth                                 | 2         | 2.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 2.25%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2         | 2.25%   |
| Toshiba RT Bluetooth Radio                            | 1         | 1.12%   |
| Toshiba Integrated Bluetooth HCI                      | 1         | 1.12%   |
| Realtek RTL8821A Bluetooth                            | 1         | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 1.12%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 1.12%   |
| MediaTek Wireless_Device                              | 1         | 1.12%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 1.12%   |
| Marvell Bluetooth and Wireless LAN Composite          | 1         | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 1.12%   |
| Dell DW375 Bluetooth Module                           | 1         | 1.12%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 1.12%   |
| Broadcom HP Portable SoftSailing                      | 1         | 1.12%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1         | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 1.12%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 1         | 1.12%   |
| ASUS Bluetooth Radio                                  | 1         | 1.12%   |
| ASUS Bluetooth Device                                 | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 113       | 69.33%  |
| Nvidia             | 29        | 17.79%  |
| AMD                | 12        | 7.36%   |
| Logitech           | 3         | 1.84%   |
| SteelSeries ApS    | 1         | 0.61%   |
| Lenovo             | 1         | 0.61%   |
| JMTek              | 1         | 0.61%   |
| Griffin Technology | 1         | 0.61%   |
| ASUSTek Computer   | 1         | 0.61%   |
| Apogee Electronics | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 16        | 8.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 5.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 5.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 4.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 4.81%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 3.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 3.21%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 3.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 2.67%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 2.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.14%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4         | 2.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.6%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.6%    |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.6%    |
| Nvidia TU104 HD Audio Controller                                           | 2         | 1.07%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.07%   |
| Nvidia Audio device                                                        | 2         | 1.07%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.07%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 1.07%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.07%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.07%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1         | 0.53%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.53%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.53%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 32.26%  |
| SK hynix            | 13        | 20.97%  |
| Micron Technology   | 9         | 14.52%  |
| Crucial             | 7         | 11.29%  |
| Kingston            | 4         | 6.45%   |
| Corsair             | 4         | 6.45%   |
| Ramaxel Technology  | 3         | 4.84%   |
| Unknown             | 2         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 3.13%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 3.13%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s       | 2         | 3.13%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s         | 2         | 3.13%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                  | 1         | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.56%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 1.56%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s            | 1         | 1.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.56%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.56%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s          | 1         | 1.56%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 1.56%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s         | 1         | 1.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.56%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 1.56%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.56%   |
| SK hynix RAM HMA82GR7JJR8N-WM 16384MB DIMM DDR4 2933MT/s        | 1         | 1.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 1         | 1.56%   |
| SK hynix RAM H5ANAG6NCMR-XNC 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.56%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.56%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.56%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.56%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.56%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s           | 1         | 1.56%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 1.56%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.56%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s        | 1         | 1.56%   |
| Samsung RAM M393B5170FH0-CH9 4096MB DIMM DDR3 1333MT/s          | 1         | 1.56%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s             | 1         | 1.56%   |
| Samsung RAM M393A8G40MB2-CVF 64GB DIMM DDR4 2933MT/s            | 1         | 1.56%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.56%   |
| Samsung RAM K4AAG165WA-BCWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.56%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB Row Of Chips DDR4 2400MT/s | 1         | 1.56%   |
| Micron RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 1.56%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 1         | 1.56%   |
| Micron RAM 36JSZF51272PZ1G4G1 4096MB DIMM DDR3 1333MT/s         | 1         | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 34        | 65.38%  |
| DDR3   | 11        | 21.15%  |
| LPDDR3 | 3         | 5.77%   |
| DDR5   | 3         | 5.77%   |
| DDR2   | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 69.81%  |
| DIMM         | 10        | 18.87%  |
| Row Of Chips | 6         | 11.32%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 47.46%  |
| 16384 | 15        | 25.42%  |
| 4096  | 8         | 13.56%  |
| 32768 | 3         | 5.08%   |
| 2048  | 3         | 5.08%   |
| 65536 | 1         | 1.69%   |
| 1024  | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 17        | 30.91%  |
| 3200  | 10        | 18.18%  |
| 2133  | 6         | 10.91%  |
| 1600  | 6         | 10.91%  |
| 2400  | 4         | 7.27%   |
| 4800  | 3         | 5.45%   |
| 1334  | 2         | 3.64%   |
| 1333  | 2         | 3.64%   |
| 3400  | 1         | 1.82%   |
| 3000  | 1         | 1.82%   |
| 2933  | 1         | 1.82%   |
| 1067  | 1         | 1.82%   |
| 667   | 1         | 1.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| HP Deskjet F2280 series   | 1         | 33.33%  |
| Canon PIXMA MG3600 Series | 1         | 33.33%  |
| Brother MFC-9330CDW       | 1         | 33.33%  |

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
| Chicony Electronics                    | 27        | 27.27%  |
| IMC Networks                           | 10        | 10.1%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 9.09%   |
| Acer                                   | 7         | 7.07%   |
| Microdia                               | 6         | 6.06%   |
| Sunplus Innovation Technology          | 5         | 5.05%   |
| Realtek Semiconductor                  | 4         | 4.04%   |
| Syntek                                 | 3         | 3.03%   |
| Samsung Electronics                    | 3         | 3.03%   |
| Ricoh                                  | 3         | 3.03%   |
| Lite-On Technology                     | 3         | 3.03%   |
| Apple                                  | 3         | 3.03%   |
| Suyin                                  | 2         | 2.02%   |
| Quanta                                 | 2         | 2.02%   |
| Microsoft                              | 2         | 2.02%   |
| Logitech                               | 2         | 2.02%   |
| Ruision                                | 1         | 1.01%   |
| Luxvisions Innotech Limited            | 1         | 1.01%   |
| LG Electronics                         | 1         | 1.01%   |
| Lenovo                                 | 1         | 1.01%   |
| KYE Systems (Mouse Systems)            | 1         | 1.01%   |
| DJKANA19IDX53W                         | 1         | 1.01%   |
| Creative Technology                    | 1         | 1.01%   |
| Alcor Micro                            | 1         | 1.01%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 9         | 9.09%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 5.05%   |
| Syntek Integrated Camera                                        | 3         | 3.03%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 3         | 3.03%   |
| IMC Networks Integrated Camera                                  | 3         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)                         | 3         | 3.03%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 3         | 3.03%   |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 2.02%   |
| Ricoh HD Webcam                                                 | 2         | 2.02%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 2.02%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 2.02%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 2.02%   |
| Logitech Webcam C270                                            | 2         | 2.02%   |
| Lite-On HP Wide Vision HD Camera                                | 2         | 2.02%   |
| Chicony Lenovo EasyCamera                                       | 2         | 2.02%   |
| Chicony HP Truevision HD                                        | 2         | 2.02%   |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 2.02%   |
| Chicony EasyCamera                                              | 2         | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 2         | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 2.02%   |
| Suyin HP TrueVision HD                                          | 1         | 1.01%   |
| Suyin 1.3M HD WebCam                                            | 1         | 1.01%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 1.01%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 1.01%   |
| Sunplus Integrated Webcam                                       | 1         | 1.01%   |
| Ruision UVC Camera                                              | 1         | 1.01%   |
| Ricoh Sony Vaio Integrated Webcam                               | 1         | 1.01%   |
| Realtek Lenovo EasyCamera                                       | 1         | 1.01%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 1.01%   |
| Realtek Integrated Webcam                                       | 1         | 1.01%   |
| Realtek HP Truevision HD                                        | 1         | 1.01%   |
| Microsoft LifeCam Rear                                          | 1         | 1.01%   |
| Microsoft LifeCam HD-3000                                       | 1         | 1.01%   |
| Microdia Integrated Webcam                                      | 1         | 1.01%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 1.01%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 1.01%   |
| Lite-On HP HD Camera                                            | 1         | 1.01%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)           | 1         | 1.01%   |
| Lenovo Integrated Webcam                                        | 1         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 13        | 48.15%  |
| Validity Sensors           | 11        | 40.74%  |
| STMicroelectronics         | 1         | 3.7%    |
| Shenzhen Goodix Technology | 1         | 3.7%    |
| Elan Microelectronics      | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 5         | 18.52%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 3         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 11.11%  |
| Validity Sensors VFS491                                    | 2         | 7.41%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 7.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 3.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 3.7%    |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 3.7%    |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.7%    |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                            | 1         | 3.7%    |
| Validity Sensors Fingerprint scanner                       | 1         | 3.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.7%    |
| STMicroelectronics Fingerprint Reader                      | 1         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.7%    |
| Elan ELAN:ARM-M4                                           | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 50%     |
| Alcor Micro | 2         | 33.33%  |
| Upek        | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 64        | 50.39%  |
| 1     | 50        | 39.37%  |
| 2     | 11        | 8.66%   |
| 3     | 2         | 1.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 36%     |
| Graphics card            | 17        | 22.67%  |
| Net/wireless             | 9         | 12%     |
| Chipcard                 | 6         | 8%      |
| Unassigned class         | 3         | 4%      |
| Communication controller | 3         | 4%      |
| Camera                   | 3         | 4%      |
| Bluetooth                | 3         | 4%      |
| Multimedia controller    | 2         | 2.67%   |
| Sound                    | 1         | 1.33%   |
| Modem                    | 1         | 1.33%   |


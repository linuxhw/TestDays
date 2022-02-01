Garuda Linux - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

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
| Lenovo        | ThinkPad T440p 20AWS58F0... | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| MSI           | GP75 Leopard 9SD            | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Unknown       | Unknown                     | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| Acer          | Aspire F5-573G              | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire A515-51G             | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| ASUSTek       | K53SD                       | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| Lenovo        | G510 20238                  | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Panasonic     | CF-191HYAX1M                | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| Notebook      | P7xxDM2                     | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Razer         | Blade                       | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| Google        | Kindred                     | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| ASUSTek       | G750JZ                      | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| Lenovo        | LEGION 5 15IMH05 82AU       | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| PC Special... | GK5NPFO                     | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| HP            | EliteBook 8540p             | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Alienware     | 17 R3                       | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| Acer          | Nitro AN515-44              | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| Medion        | E7419 MD60025               | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| Dell          | XPS L702X                   | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | XPS L702X                   | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| HP            | EliteBook 8540p             | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| HP            | EliteBook 8540p             | [9dececac24](https://linux-hardware.org/?probe=9dececac24) | Feb 11, 2021 |
| HP            | EliteBook 8540p             | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | EliteBook 8540p             | [23cece38ed](https://linux-hardware.org/?probe=23cece38ed) | Feb 02, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| Dell          | Latitude E6520              | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| Dell          | XPS 15 9500                 | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| HP            | EliteBook 8540p             | [c504347399](https://linux-hardware.org/?probe=c504347399) | Jan 23, 2021 |
| HP            | EliteBook 8540p             | [643af77934](https://linux-hardware.org/?probe=643af77934) | Jan 18, 2021 |
| HP            | Compaq 6735b                | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| HP            | EliteBook 8540p             | [86c3c2d1d3](https://linux-hardware.org/?probe=86c3c2d1d3) | Jan 12, 2021 |
| Unknown       | Unknown                     | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| HP            | EliteBook 8540p             | [ad733c377c](https://linux-hardware.org/?probe=ad733c377c) | Jan 09, 2021 |
| HP            | EliteBook 8540p             | [d4206bf424](https://linux-hardware.org/?probe=d4206bf424) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| Dell          | Latitude E6430              | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Unknown       | Unknown                     | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| HP            | Laptop 17-ak0xx             | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| Dell          | Latitude E6430              | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| HP            | 450                         | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.14.14-zen1-1-zen          | 4         | 3.7%    |
| 5.16.2-zen1-1-zen           | 3         | 2.78%   |
| 5.15.6-zen2-1-zen           | 3         | 2.78%   |
| 5.15.2-zen1-1-zen           | 3         | 2.78%   |
| 5.15.12-zen1-1-zen          | 3         | 2.78%   |
| 5.14.6-zen1-1-zen           | 3         | 2.78%   |
| 5.13.9-zen1-1-zen           | 3         | 2.78%   |
| 5.13.13-zen1-1-zen          | 3         | 2.78%   |
| 5.11.11-zen1-1-zen          | 3         | 2.78%   |
| 5.10.1-103-tkg-bmq          | 3         | 2.78%   |
| 5.16.1-zen1-1-zen           | 2         | 1.85%   |
| 5.15.5-zen1-1-zen           | 2         | 1.85%   |
| 5.15.4-zen1-1-zen           | 2         | 1.85%   |
| 5.15.13-zen1-1-zen          | 2         | 1.85%   |
| 5.14.9-zen2-1-zen           | 2         | 1.85%   |
| 5.14.15-zen1-1-zen          | 2         | 1.85%   |
| 5.13.5-zen1-1-zen           | 2         | 1.85%   |
| 5.12.9-zen1-1-zen           | 2         | 1.85%   |
| 5.12.15-zen1-1-zen          | 2         | 1.85%   |
| 5.11.16-zen1-1-zen          | 2         | 1.85%   |
| 5.10.2-104-tkg-bmq          | 2         | 1.85%   |
| 5.10.15-120-tkg-bmq         | 2         | 1.85%   |
| 5.10.10-115-tkg-bmq         | 2         | 1.85%   |
| 5.9.9-zen1-1-zen            | 1         | 0.93%   |
| 5.9.8-zen1-1-zen            | 1         | 0.93%   |
| 5.9.2-zen1-1-zen            | 1         | 0.93%   |
| 5.9.10-zen1-1-zen           | 1         | 0.93%   |
| 5.6.6-zen1-1-zen            | 1         | 0.93%   |
| 5.4.97-120-tkg-bmq          | 1         | 0.93%   |
| 5.16.0-rc5-1-mainline-anbox | 1         | 0.93%   |
| 5.15.7-zen1-1-zen           | 1         | 0.93%   |
| 5.15.7-arch1-1              | 1         | 0.93%   |
| 5.15.3-zen1-1-zen           | 1         | 0.93%   |
| 5.15.11-zen1-1-zen          | 1         | 0.93%   |
| 5.15.11-230-tkg-cfs         | 1         | 0.93%   |
| 5.15.10-zen1-1-zen          | 1         | 0.93%   |
| 5.14.8-zen1-1-zen           | 1         | 0.93%   |
| 5.14.7-zen1-1-zen           | 1         | 0.93%   |
| 5.14.5-zen2-1-zen           | 1         | 0.93%   |
| 5.14.2-zen1-2-zen           | 1         | 0.93%   |
| 5.14.12-zen1-1-zen          | 1         | 0.93%   |
| 5.14.11-arch1-1             | 1         | 0.93%   |
| 5.13.4-zen1-1-zen           | 1         | 0.93%   |
| 5.13.1-zen1-1-zen           | 1         | 0.93%   |
| 5.12.9-164-tkg-muqss        | 1         | 0.93%   |
| 5.12.8-zen1-1-zen           | 1         | 0.93%   |
| 5.12.7-zen1-1-zen           | 1         | 0.93%   |
| 5.12.6-xanmod1-1            | 1         | 0.93%   |
| 5.12.2-153-tkg-bmq          | 1         | 0.93%   |
| 5.12.14-zen1-1-zen          | 1         | 0.93%   |
| 5.12.13-zen1-1-zen          | 1         | 0.93%   |
| 5.12.12-AMD-znver2          | 1         | 0.93%   |
| 5.11.7-zen1-1-zen           | 1         | 0.93%   |
| 5.11.6-zen1-1-zen           | 1         | 0.93%   |
| 5.11.6-137-tkg-bmq          | 1         | 0.93%   |
| 5.11.2-zen1-1-zen           | 1         | 0.93%   |
| 5.11.15-zen1-2-zen          | 1         | 0.93%   |
| 5.11.12-zen1-1-zen          | 1         | 0.93%   |
| 5.11.11-144-tkg-bmq         | 1         | 0.93%   |
| 5.11.0-zen1-1-zen-anbox     | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.14 | 4         | 3.7%    |
| 5.11.11 | 4         | 3.7%    |
| 5.16.2  | 3         | 2.78%   |
| 5.15.6  | 3         | 2.78%   |
| 5.15.2  | 3         | 2.78%   |
| 5.15.12 | 3         | 2.78%   |
| 5.14.6  | 3         | 2.78%   |
| 5.13.9  | 3         | 2.78%   |
| 5.13.13 | 3         | 2.78%   |
| 5.12.9  | 3         | 2.78%   |
| 5.10.15 | 3         | 2.78%   |
| 5.10.1  | 3         | 2.78%   |
| 5.16.1  | 2         | 1.85%   |
| 5.15.7  | 2         | 1.85%   |
| 5.15.5  | 2         | 1.85%   |
| 5.15.4  | 2         | 1.85%   |
| 5.15.13 | 2         | 1.85%   |
| 5.15.11 | 2         | 1.85%   |
| 5.14.9  | 2         | 1.85%   |
| 5.14.15 | 2         | 1.85%   |
| 5.13.5  | 2         | 1.85%   |
| 5.12.15 | 2         | 1.85%   |
| 5.11.6  | 2         | 1.85%   |
| 5.11.16 | 2         | 1.85%   |
| 5.10.4  | 2         | 1.85%   |
| 5.10.2  | 2         | 1.85%   |
| 5.10.12 | 2         | 1.85%   |
| 5.10.10 | 2         | 1.85%   |
| 5.9.9   | 1         | 0.93%   |
| 5.9.8   | 1         | 0.93%   |
| 5.9.2   | 1         | 0.93%   |
| 5.9.10  | 1         | 0.93%   |
| 5.6.6   | 1         | 0.93%   |
| 5.4.97  | 1         | 0.93%   |
| 5.16.0  | 1         | 0.93%   |
| 5.15.3  | 1         | 0.93%   |
| 5.15.10 | 1         | 0.93%   |
| 5.14.8  | 1         | 0.93%   |
| 5.14.7  | 1         | 0.93%   |
| 5.14.5  | 1         | 0.93%   |
| 5.14.2  | 1         | 0.93%   |
| 5.14.12 | 1         | 0.93%   |
| 5.14.11 | 1         | 0.93%   |
| 5.13.4  | 1         | 0.93%   |
| 5.13.1  | 1         | 0.93%   |
| 5.12.8  | 1         | 0.93%   |
| 5.12.7  | 1         | 0.93%   |
| 5.12.6  | 1         | 0.93%   |
| 5.12.2  | 1         | 0.93%   |
| 5.12.14 | 1         | 0.93%   |
| 5.12.13 | 1         | 0.93%   |
| 5.12.12 | 1         | 0.93%   |
| 5.11.7  | 1         | 0.93%   |
| 5.11.2  | 1         | 0.93%   |
| 5.11.15 | 1         | 0.93%   |
| 5.11.12 | 1         | 0.93%   |
| 5.11.0  | 1         | 0.93%   |
| 5.10.8  | 1         | 0.93%   |
| 5.10.78 | 1         | 0.93%   |
| 5.10.7  | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 21        | 20.19%  |
| 5.10    | 20        | 19.23%  |
| 5.14    | 17        | 16.35%  |
| 5.12    | 12        | 11.54%  |
| 5.11    | 12        | 11.54%  |
| 5.13    | 10        | 9.62%   |
| 5.16    | 6         | 5.77%   |
| 5.9     | 4         | 3.85%   |
| 5.6     | 1         | 0.96%   |
| 5.4     | 1         | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 98        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KDE5              | 57        | 57.58%  |
| GNOME             | 13        | 13.13%  |
| KDE               | 12        | 12.12%  |
| XFCE              | 8         | 8.08%   |
| X-Cinnamon        | 2         | 2.02%   |
| sway              | 2         | 2.02%   |
| Deepin            | 2         | 2.02%   |
| Yaru:ubuntu:GNOME | 1         | 1.01%   |
| MATE              | 1         | 1.01%   |
| i3                | 1         | 1.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 92        | 93.88%  |
| Wayland | 4         | 4.08%   |
| Tty     | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 53        | 53.54%  |
| Unknown | 27        | 27.27%  |
| LightDM | 11        | 11.11%  |
| GDM     | 7         | 7.07%   |
| GREETD  | 1         | 1.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 47        | 47.47%  |
| en_GB   | 12        | 12.12%  |
| en_IN   | 7         | 7.07%   |
| it_IT   | 6         | 6.06%   |
| de_DE   | 6         | 6.06%   |
| pt_BR   | 3         | 3.03%   |
| ru_RU   | 2         | 2.02%   |
| pl_PL   | 2         | 2.02%   |
| fi_FI   | 2         | 2.02%   |
| es_MX   | 2         | 2.02%   |
| es_CO   | 2         | 2.02%   |
| sv_SE   | 1         | 1.01%   |
| nl_NL   | 1         | 1.01%   |
| ko_KR   | 1         | 1.01%   |
| es_VE   | 1         | 1.01%   |
| es_ES   | 1         | 1.01%   |
| en_ZA   | 1         | 1.01%   |
| de_AT   | 1         | 1.01%   |
| Unknown | 1         | 1.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 70        | 70.71%  |
| BIOS | 29        | 29.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 97        | 98.98%  |
| F2fs  | 1         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 66        | 67.35%  |
| Unknown | 24        | 24.49%  |
| MBR     | 8         | 8.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 92.86%  |
| Yes       | 7         | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 69.39%  |
| Yes       | 30        | 30.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 23        | 23.47%  |
| Hewlett-Packard     | 16        | 16.33%  |
| Dell                | 15        | 15.31%  |
| Acer                | 11        | 11.22%  |
| ASUSTek Computer    | 10        | 10.2%   |
| Notebook            | 3         | 3.06%   |
| Samsung Electronics | 2         | 2.04%   |
| Razer               | 2         | 2.04%   |
| MSI                 | 2         | 2.04%   |
| Medion              | 2         | 2.04%   |
| Unknown             | 2         | 2.04%   |
| Toshiba             | 1         | 1.02%   |
| Sony                | 1         | 1.02%   |
| PC Specialist       | 1         | 1.02%   |
| Panasonic           | 1         | 1.02%   |
| GPU Company         | 1         | 1.02%   |
| Google              | 1         | 1.02%   |
| Fujitsu Siemens     | 1         | 1.02%   |
| Chuwi               | 1         | 1.02%   |
| Apple               | 1         | 1.02%   |
| Alienware           | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 3         | 3.06%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 2.04%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 2         | 2.04%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 2.04%   |
| Acer Nitro AN515-44                        | 2         | 2.04%   |
| Toshiba Satellite C55-A                    | 1         | 1.02%   |
| Sony VPCSB1C5E                             | 1         | 1.02%   |
| Samsung 550XCJ/550XCR                      | 1         | 1.02%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 1.02%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 1.02%   |
| Razer Blade                                | 1         | 1.02%   |
| PC Specialist GK5NPFO                      | 1         | 1.02%   |
| Panasonic CF-191HYAX1M                     | 1         | 1.02%   |
| Notebook W54_W550SU2                       | 1         | 1.02%   |
| Notebook P7xxDM2(-G)                       | 1         | 1.02%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 1.02%   |
| MSI GP75 Leopard 9SD                       | 1         | 1.02%   |
| MSI GE72VR 6RF                             | 1         | 1.02%   |
| Medion P861X                               | 1         | 1.02%   |
| Medion E7419 MD60025                       | 1         | 1.02%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 1.02%   |
| Lenovo ThinkPad T510 4384WB4               | 1         | 1.02%   |
| Lenovo ThinkPad T470s 20HGS0B900           | 1         | 1.02%   |
| Lenovo ThinkPad T470 20HD000RUS            | 1         | 1.02%   |
| Lenovo ThinkPad T440p 20AWS58F00           | 1         | 1.02%   |
| Lenovo ThinkPad T440p 20AWS4RC00           | 1         | 1.02%   |
| Lenovo ThinkPad T14 Gen 1 20UDS00N00       | 1         | 1.02%   |
| Lenovo Legion S7 15ACH6 82K8               | 1         | 1.02%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 1         | 1.02%   |
| Lenovo Legion 5 15IMH05H 81Y6              | 1         | 1.02%   |
| Lenovo LEGION 5 15IMH05 82AU               | 1         | 1.02%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 1         | 1.02%   |
| Lenovo IdeaPad S340-15API 81NC             | 1         | 1.02%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 1         | 1.02%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 1.02%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 1         | 1.02%   |
| Lenovo IdeaPad 110-15ACL 80TJ              | 1         | 1.02%   |
| Lenovo G510 20238                          | 1         | 1.02%   |
| HP ProBook 640 G1                          | 1         | 1.02%   |
| HP Pavilion Laptop 15z-eh100               | 1         | 1.02%   |
| HP Pavilion Laptop 15-eh0xxx               | 1         | 1.02%   |
| HP Pavilion Laptop 15-cs0xxx               | 1         | 1.02%   |
| HP Pavilion Gaming Laptop 15-dk0xxx        | 1         | 1.02%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 1         | 1.02%   |
| HP Pavilion 14                             | 1         | 1.02%   |
| HP OMEN Laptop 15-en1xxx                   | 1         | 1.02%   |
| HP OMEN Laptop 15-en0xxx                   | 1         | 1.02%   |
| HP OMEN by HP Laptop 15-dc1xxx             | 1         | 1.02%   |
| HP Laptop 17-ak0xx                         | 1         | 1.02%   |
| HP Laptop 15-dy2xxx                        | 1         | 1.02%   |
| HP EliteBook 8540p                         | 1         | 1.02%   |
| HP EliteBook 845 G7 Notebook PC            | 1         | 1.02%   |
| HP Compaq 6735b                            | 1         | 1.02%   |
| HP 450                                     | 1         | 1.02%   |
| GPU Company GWTN156-11                     | 1         | 1.02%   |
| Google Kindred                             | 1         | 1.02%   |
| Fujitsu Siemens ESPRIMO Mobile D9500       | 1         | 1.02%   |
| Dell XPS L702X                             | 1         | 1.02%   |
| Dell XPS 15 9500                           | 1         | 1.02%   |
| Dell XPS 15 7590                           | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 8         | 8.16%   |
| Lenovo IdeaPad          | 8         | 8.16%   |
| Dell Inspiron           | 7         | 7.14%   |
| HP Pavilion             | 6         | 6.12%   |
| Acer Aspire             | 5         | 5.1%    |
| Lenovo Legion           | 4         | 4.08%   |
| Dell XPS                | 4         | 4.08%   |
| Acer Nitro              | 4         | 4.08%   |
| HP OMEN                 | 3         | 3.06%   |
| Dell Latitude           | 3         | 3.06%   |
| Unknown                 | 3         | 3.06%   |
| Razer Blade             | 2         | 2.04%   |
| HP Laptop               | 2         | 2.04%   |
| HP EliteBook            | 2         | 2.04%   |
| ASUS TUF                | 2         | 2.04%   |
| ASUS ASUS               | 2         | 2.04%   |
| Toshiba Satellite       | 1         | 1.02%   |
| Sony VPCSB1C5E          | 1         | 1.02%   |
| Samsung 550XCJ          | 1         | 1.02%   |
| Samsung 300V3A          | 1         | 1.02%   |
| PC Specialist GK5NPFO   | 1         | 1.02%   |
| Panasonic CF-191HYAX1M  | 1         | 1.02%   |
| Notebook W54            | 1         | 1.02%   |
| Notebook P7xxDM2(-G)    | 1         | 1.02%   |
| Notebook N85            | 1         | 1.02%   |
| MSI GP75                | 1         | 1.02%   |
| MSI GE72VR              | 1         | 1.02%   |
| Medion P861X            | 1         | 1.02%   |
| Medion E7419            | 1         | 1.02%   |
| Lenovo Yoga             | 1         | 1.02%   |
| Lenovo G510             | 1         | 1.02%   |
| HP ProBook              | 1         | 1.02%   |
| HP Compaq               | 1         | 1.02%   |
| HP 450                  | 1         | 1.02%   |
| GPU Company GWTN156-11  | 1         | 1.02%   |
| Google Kindred          | 1         | 1.02%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.02%   |
| Dell Precision          | 1         | 1.02%   |
| Chuwi GemiBook          | 1         | 1.02%   |
| ASUS X550ZE             | 1         | 1.02%   |
| ASUS X550CC             | 1         | 1.02%   |
| ASUS ROG                | 1         | 1.02%   |
| ASUS K53SD              | 1         | 1.02%   |
| ASUS GL503VM            | 1         | 1.02%   |
| ASUS G750JZ             | 1         | 1.02%   |
| Apple MacBookPro9       | 1         | 1.02%   |
| Alienware 17            | 1         | 1.02%   |
| Acer TravelMate         | 1         | 1.02%   |
| Acer Swift              | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 21        | 21.43%  |
| 2021 | 11        | 11.22%  |
| 2019 | 10        | 10.2%   |
| 2016 | 10        | 10.2%   |
| 2017 | 9         | 9.18%   |
| 2013 | 8         | 8.16%   |
| 2018 | 6         | 6.12%   |
| 2012 | 6         | 6.12%   |
| 2014 | 5         | 5.1%    |
| 2011 | 5         | 5.1%    |
| 2010 | 2         | 2.04%   |
| 2009 | 2         | 2.04%   |
| 2007 | 2         | 2.04%   |
| 2008 | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 98        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 98        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 98.98%  |
| Yes  | 1         | 1.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 27        | 27.27%  |
| 16.01-24.0 | 26        | 26.26%  |
| 8.01-16.0  | 26        | 26.26%  |
| 3.01-4.0   | 11        | 11.11%  |
| 32.01-64.0 | 5         | 5.05%   |
| 24.01-32.0 | 3         | 3.03%   |
| 2.01-3.0   | 1         | 1.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 32        | 30.19%  |
| 2.01-3.0  | 31        | 29.25%  |
| 3.01-4.0  | 26        | 24.53%  |
| 1.01-2.0  | 8         | 7.55%   |
| 8.01-16.0 | 8         | 7.55%   |
| 0.51-1.0  | 1         | 0.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 57.43%  |
| 2      | 34        | 33.66%  |
| 3      | 8         | 7.92%   |
| 4      | 1         | 0.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 74%     |
| Yes       | 26        | 26%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 80.61%  |
| No        | 19        | 19.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 97.96%  |
| No        | 2         | 2.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 87.76%  |
| No        | 12        | 12.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 26        | 26.26%  |
| UK           | 9         | 9.09%   |
| Germany      | 9         | 9.09%   |
| India        | 8         | 8.08%   |
| Italy        | 7         | 7.07%   |
| Brazil       | 4         | 4.04%   |
| Romania      | 3         | 3.03%   |
| Mexico       | 3         | 3.03%   |
| Finland      | 3         | 3.03%   |
| Sweden       | 2         | 2.02%   |
| Spain        | 2         | 2.02%   |
| Russia       | 2         | 2.02%   |
| Poland       | 2         | 2.02%   |
| Netherlands  | 2         | 2.02%   |
| Colombia     | 2         | 2.02%   |
| Venezuela    | 1         | 1.01%   |
| Switzerland  | 1         | 1.01%   |
| South Korea  | 1         | 1.01%   |
| South Africa | 1         | 1.01%   |
| Serbia       | 1         | 1.01%   |
| Luxembourg   | 1         | 1.01%   |
| Kuwait       | 1         | 1.01%   |
| Kenya        | 1         | 1.01%   |
| Hungary      | 1         | 1.01%   |
| Czechia      | 1         | 1.01%   |
| China        | 1         | 1.01%   |
| Canada       | 1         | 1.01%   |
| Belgium      | 1         | 1.01%   |
| Bahrain      | 1         | 1.01%   |
| Austria      | 1         | 1.01%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 3         | 2.94%   |
| Helsinki           | 2         | 1.96%   |
| Bryansk            | 2         | 1.96%   |
| Berlin             | 2         | 1.96%   |
| Winston-Salem      | 1         | 0.98%   |
| Welwyn Garden City | 1         | 0.98%   |
| Warsaw             | 1         | 0.98%   |
| Vufflens-la-Ville  | 1         | 0.98%   |
| Viganello          | 1         | 0.98%   |
| Vienna             | 1         | 0.98%   |
| Valenzano          | 1         | 0.98%   |
| Turku              | 1         | 0.98%   |
| Turin              | 1         | 0.98%   |
| Tucson             | 1         | 0.98%   |
| Toronto            | 1         | 0.98%   |
| Timișoara         | 1         | 0.98%   |
| Spring Hill        | 1         | 0.98%   |
| Spitalfields       | 1         | 0.98%   |
| Southampton        | 1         | 0.98%   |
| Sighetu Marma??iei | 1         | 0.98%   |
| San Jose           | 1         | 0.98%   |
| San Francisco      | 1         | 0.98%   |
| Reno               | 1         | 0.98%   |
| Qalali             | 1         | 0.98%   |
| Pune               | 1         | 0.98%   |
| Puebla City        | 1         | 0.98%   |
| Pompano Beach      | 1         | 0.98%   |
| Pitalito           | 1         | 0.98%   |
| Palmer             | 1         | 0.98%   |
| Oxford             | 1         | 0.98%   |
| Owings Mills       | 1         | 0.98%   |
| New Delhi          | 1         | 0.98%   |
| Nairobi            | 1         | 0.98%   |
| Münster           | 1         | 0.98%   |
| Mostoles           | 1         | 0.98%   |
| Milan              | 1         | 0.98%   |
| Mexico City        | 1         | 0.98%   |
| Manning            | 1         | 0.98%   |
| Luxembourg         | 1         | 0.98%   |
| Lochristi          | 1         | 0.98%   |
| Leyton             | 1         | 0.98%   |
| Leesville          | 1         | 0.98%   |
| Lancaster          | 1         | 0.98%   |
| Kuwait City        | 1         | 0.98%   |
| Kolkata            | 1         | 0.98%   |
| Kirkland           | 1         | 0.98%   |
| Imbersago          | 1         | 0.98%   |
| Ilhéus            | 1         | 0.98%   |
| Hyderabad          | 1         | 0.98%   |
| Hloubetin          | 1         | 0.98%   |
| Hillsdale          | 1         | 0.98%   |
| Highland Park      | 1         | 0.98%   |
| Hammaro            | 1         | 0.98%   |
| Halle              | 1         | 0.98%   |
| Guwahati           | 1         | 0.98%   |
| Groningen          | 1         | 0.98%   |
| Glendale           | 1         | 0.98%   |
| Gaissach           | 1         | 0.98%   |
| Foshan             | 1         | 0.98%   |
| Fort Lauderdale    | 1         | 0.98%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 27        | 33     | 18.88%  |
| Seagate                   | 17        | 18     | 11.89%  |
| WDC                       | 14        | 15     | 9.79%   |
| SK Hynix                  | 10        | 11     | 6.99%   |
| SanDisk                   | 9         | 12     | 6.29%   |
| Unknown                   | 7         | 7      | 4.9%    |
| Toshiba                   | 7         | 9      | 4.9%    |
| HGST                      | 6         | 6      | 4.2%    |
| Kingston                  | 5         | 5      | 3.5%    |
| Crucial                   | 5         | 8      | 3.5%    |
| Micron Technology         | 3         | 3      | 2.1%    |
| Intel                     | 3         | 4      | 2.1%    |
| Hitachi                   | 3         | 3      | 2.1%    |
| Corsair                   | 3         | 3      | 2.1%    |
| KIOXIA                    | 2         | 3      | 1.4%    |
| China                     | 2         | 2      | 1.4%    |
| WDC WDS                   | 1         | 1      | 0.7%    |
| VisionTek                 | 1         | 2      | 0.7%    |
| Union Memory (Shenzhen)   | 1         | 1      | 0.7%    |
| SPCC                      | 1         | 1      | 0.7%    |
| Silicon Motion            | 1         | 1      | 0.7%    |
| ShanDianZhe               | 1         | 1      | 0.7%    |
| SABRENT                   | 1         | 2      | 0.7%    |
| PNY CS90                  | 1         | 1      | 0.7%    |
| PNY                       | 1         | 1      | 0.7%    |
| Phison Electronics        | 1         | 1      | 0.7%    |
| Phison                    | 1         | 1      | 0.7%    |
| Netac                     | 1         | 1      | 0.7%    |
| Mushkin                   | 1         | 1      | 0.7%    |
| Micron/Crucial Technology | 1         | 1      | 0.7%    |
| LITEONIT                  | 1         | 1      | 0.7%    |
| LITEON                    | 1         | 1      | 0.7%    |
| Lenovo                    | 1         | 1      | 0.7%    |
| KIOXIA-EXCERIA            | 1         | 1      | 0.7%    |
| FORESEE                   | 1         | 1      | 0.7%    |
| A-DATA Technology         | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 4         | 2.67%   |
| Samsung NVMe SSD Drive 1TB                   | 4         | 2.67%   |
| Toshiba MQ01ABD100 1TB                       | 3         | 2%      |
| Seagate ST1000LM049-2GH172 1TB               | 3         | 2%      |
| Samsung SSD 860 EVO 1TB                      | 3         | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 1.33%   |
| Seagate ST1000LM014-1EJ164 1TB               | 2         | 1.33%   |
| Samsung SSD 870 QVO 1TB                      | 2         | 1.33%   |
| Samsung SSD 870 EVO 500GB                    | 2         | 1.33%   |
| Samsung NVMe SSD Drive 256GB                 | 2         | 1.33%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD         | 2         | 1.33%   |
| KIOXIA NVMe SSD Drive 512GB                  | 2         | 1.33%   |
| Intel SSDPEKNW010T8 1TB                      | 2         | 1.33%   |
| HGST HTS721010A9E630 1TB                     | 2         | 1.33%   |
| Corsair Force MP300 960GB                    | 2         | 1.33%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 0.67%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 1         | 0.67%   |
| WDC WDS 500G2B0B-00YS70 500GB SSD            | 1         | 0.67%   |
| WDC WDBNCE5000PNC 500GB SSD                  | 1         | 0.67%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 0.67%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 0.67%   |
| WDC WD5000BEVT-60A0RT0 500GB                 | 1         | 0.67%   |
| WDC WD10JPVX-11JC3T0 1TB                     | 1         | 0.67%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB           | 1         | 0.67%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB         | 1         | 0.67%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB         | 1         | 0.67%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB         | 1         | 0.67%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB         | 1         | 0.67%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB         | 1         | 0.67%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB         | 1         | 0.67%   |
| VisionTek SSD 120GB                          | 1         | 0.67%   |
| Unknown SL64G  64GB                          | 1         | 0.67%   |
| Unknown SF256  256GB                         | 1         | 0.67%   |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 0.67%   |
| Unknown MMC128  128GB                        | 1         | 0.67%   |
| Unknown MMC Card  16GB                       | 1         | 0.67%   |
| Unknown DA4128  128GB                        | 1         | 0.67%   |
| Unknown APPSD  16GB                          | 1         | 0.67%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.67%   |
| Toshiba THNSNJ128G8NY 128GB SSD              | 1         | 0.67%   |
| Toshiba MQ02ABD100H 1TB                      | 1         | 0.67%   |
| Toshiba KXG60ZNV1T02 NVMe KIOXIA 1024GB      | 1         | 0.67%   |
| Toshiba KBG40ZNT512G MEMORY 512GB            | 1         | 0.67%   |
| SPCC M.2 PCIe SSD 512GB                      | 1         | 0.67%   |
| SK Hynix SKHynix_HFS512GDE9X084N 512GB       | 1         | 0.67%   |
| SK Hynix SKHynix_HFS512GD9TNG-L3A0B 512GB    | 1         | 0.67%   |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB         | 1         | 0.67%   |
| SK Hynix SC311 SATA 256GB SSD                | 1         | 0.67%   |
| SK Hynix NVMe SSD Drive 512GB                | 1         | 0.67%   |
| SK Hynix HFM512GDHTNG-8310A 512GB            | 1         | 0.67%   |
| SK Hynix HFM256GDJTNG-8310A 256GB            | 1         | 0.67%   |
| SK Hynix HFM128GDJTNG-8310A 128GB            | 1         | 0.67%   |
| SK Hynix BC711 NVMe 256GB                    | 1         | 0.67%   |
| SK Hynix BC511 NVMe 256GB                    | 1         | 0.67%   |
| SK Hynix BC501 HFM512GDJTNG-8310A 512GB      | 1         | 0.67%   |
| Silicon Motion NE-256 256GB                  | 1         | 0.67%   |
| ShanDianZhe 128G                             | 1         | 0.67%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 0.67%   |
| Seagate ST1000LM048-2E7172 1TB               | 1         | 0.67%   |
| Seagate ST1000LM044 HN-M101SAD 1TB           | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 16     | 47.06%  |
| HGST    | 6         | 6      | 17.65%  |
| WDC     | 4         | 4      | 11.76%  |
| Toshiba | 4         | 6      | 11.76%  |
| Hitachi | 3         | 3      | 8.82%   |
| Unknown | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 18     | 31.91%  |
| SanDisk             | 5         | 8      | 10.64%  |
| Crucial             | 4         | 7      | 8.51%   |
| WDC                 | 3         | 4      | 6.38%   |
| Kingston            | 3         | 3      | 6.38%   |
| China               | 2         | 2      | 4.26%   |
| WDC WDS             | 1         | 1      | 2.13%   |
| VisionTek           | 1         | 2      | 2.13%   |
| Toshiba             | 1         | 1      | 2.13%   |
| SK Hynix            | 1         | 1      | 2.13%   |
| SABRENT             | 1         | 2      | 2.13%   |
| PNY CS90            | 1         | 1      | 2.13%   |
| PNY                 | 1         | 1      | 2.13%   |
| Netac               | 1         | 1      | 2.13%   |
| Mushkin             | 1         | 1      | 2.13%   |
| LITEONIT            | 1         | 1      | 2.13%   |
| LITEON              | 1         | 1      | 2.13%   |
| KIOXIA-EXCERIA      | 1         | 1      | 2.13%   |
| FORESEE             | 1         | 1      | 2.13%   |
| Corsair             | 1         | 1      | 2.13%   |
| A-DATA Technology   | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 47        | 59     | 35.88%  |
| SSD     | 43        | 59     | 32.82%  |
| HDD     | 31        | 36     | 23.66%  |
| MMC     | 7         | 7      | 5.34%   |
| Unknown | 3         | 3      | 2.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 61        | 86     | 49.19%  |
| NVMe | 47        | 59     | 37.9%   |
| SAS  | 9         | 12     | 7.26%   |
| MMC  | 7         | 7      | 5.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 48     | 51.95%  |
| 0.51-1.0   | 36        | 46     | 46.75%  |
| 1.01-2.0   | 1         | 1      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 34        | 34.34%  |
| 1001-2000      | 21        | 21.21%  |
| 501-1000       | 19        | 19.19%  |
| 2001-3000      | 11        | 11.11%  |
| Unknown        | 7         | 7.07%   |
| 251-500        | 4         | 4.04%   |
| 1-20           | 2         | 2.02%   |
| 101-250        | 1         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 30.1%   |
| 251-500        | 18        | 17.48%  |
| 51-100         | 15        | 14.56%  |
| 1001-2000      | 14        | 13.59%  |
| 501-1000       | 12        | 11.65%  |
| Unknown        | 7         | 6.8%    |
| 2001-3000      | 3         | 2.91%   |
| 1-20           | 2         | 1.94%   |
| More than 3000 | 1         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB   | 1         | 1      | 16.67%  |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 16.67%  |
| Seagate ST1000LM014-1EJ164 1TB | 1         | 1      | 16.67%  |
| Hitachi HTS547575A9E384 752GB  | 1         | 1      | 16.67%  |
| Hitachi HTS542525K9SA00 250GB  | 1         | 1      | 16.67%  |
| HGST HTS541075A9E680 752GB     | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 33.33%  |
| Hitachi | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 33.33%  |
| Hitachi | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 100%    |

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
| Works    | 61        | 83     | 54.95%  |
| Detected | 44        | 75     | 39.64%  |
| Malfunc  | 6         | 6      | 5.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 65        | 48.87%  |
| AMD                          | 18        | 13.53%  |
| Samsung Electronics          | 13        | 9.77%   |
| Sandisk                      | 10        | 7.52%   |
| SK Hynix                     | 9         | 6.77%   |
| Phison Electronics           | 5         | 3.76%   |
| Micron/Crucial Technology    | 2         | 1.5%    |
| Micron Technology            | 2         | 1.5%    |
| KIOXIA                       | 2         | 1.5%    |
| Kingston Technology Company  | 2         | 1.5%    |
| Union Memory (Shenzhen)      | 1         | 0.75%   |
| Toshiba America Info Systems | 1         | 0.75%   |
| Silicon Motion               | 1         | 0.75%   |
| Nvidia                       | 1         | 0.75%   |
| Lenovo                       | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 17        | 12.5%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 6.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 8         | 5.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 5.88%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 6         | 4.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 4.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 5         | 3.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 3.68%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 4         | 2.94%   |
| SK Hynix Gold P31 SSD                                                                  | 3         | 2.21%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 2.21%   |
| Phison E12 NVMe Controller                                                             | 3         | 2.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 2.21%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 2.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 2.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 2.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 2.21%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 2.21%   |
| Phison NVMe Storage Controller                                                         | 2         | 1.47%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 1.47%   |
| Micron Non-Volatile memory controller                                                  | 2         | 1.47%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 1.47%   |
| Intel SSD 660P Series                                                                  | 2         | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.47%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.74%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 0.74%   |
| SK Hynix BC511                                                                         | 1         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.74%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.74%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.74%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.74%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.74%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 0.74%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.74%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.74%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.74%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 69        | 53.91%  |
| NVMe | 46        | 35.94%  |
| RAID | 10        | 7.81%   |
| IDE  | 3         | 2.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 70.41%  |
| AMD    | 29        | 29.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 5.1%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 5.1%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 5.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 4.08%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 4.08%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 3.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 2.04%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 2.04%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 2.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.04%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 2.04%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 2.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.04%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 2.04%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.04%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 2.04%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.02%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 1.02%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 1.02%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.02%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 1.02%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 1.02%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.02%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.02%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1.02%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.02%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.02%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.02%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 1.02%   |
| Intel Core i7 CPU Q 840 @ 1.87GHz             | 1         | 1.02%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.02%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.02%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.02%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 1.02%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.02%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.02%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.02%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.02%   |
| Intel Core i3-2365M CPU @ 1.40GHz             | 1         | 1.02%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 1.02%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 1.02%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.02%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 1.02%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 1.02%   |
| Intel Celeron CPU 5205U @ 1.90GHz             | 1         | 1.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.02%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz       | 1         | 1.02%   |
| AMD Turion X2 Ultra DualCore Mobile ZM-84     | 1         | 1.02%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 1.02%   |
| AMD Ryzen 7 4800U with Radeon Graphics        | 1         | 1.02%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 1.02%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 1.02%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 1.02%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.02%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 32        | 32.65%  |
| Intel Core i5           | 18        | 18.37%  |
| AMD Ryzen 7             | 12        | 12.24%  |
| AMD Ryzen 5             | 7         | 7.14%   |
| Intel Core i3           | 5         | 5.1%    |
| Other                   | 4         | 4.08%   |
| Intel Celeron           | 4         | 4.08%   |
| Intel Pentium Silver    | 2         | 2.04%   |
| Intel Pentium           | 2         | 2.04%   |
| Intel Core 2 Duo        | 2         | 2.04%   |
| AMD Ryzen 7 PRO         | 2         | 2.04%   |
| Intel Pentium Dual-Core | 1         | 1.02%   |
| Intel Core m3           | 1         | 1.02%   |
| AMD Turion              | 1         | 1.02%   |
| AMD Ryzen 9             | 1         | 1.02%   |
| AMD A8                  | 1         | 1.02%   |
| AMD A6                  | 1         | 1.02%   |
| AMD A4                  | 1         | 1.02%   |
| AMD A10                 | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 37.76%  |
| 4      | 35        | 35.71%  |
| 8      | 13        | 13.27%  |
| 6      | 13        | 13.27%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 81        | 82.65%  |
| 1      | 17        | 17.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 98        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 33.66%  |
| 0x306a9    | 5         | 4.95%   |
| 0x206a7    | 5         | 4.95%   |
| 0x906ea    | 4         | 3.96%   |
| 0x906e9    | 4         | 3.96%   |
| 0x306c3    | 4         | 3.96%   |
| 0x0a50000c | 4         | 3.96%   |
| 0x08600103 | 4         | 3.96%   |
| 0xa0652    | 3         | 2.97%   |
| 0x806e9    | 3         | 2.97%   |
| 0x08108102 | 3         | 2.97%   |
| 0x806ec    | 2         | 1.98%   |
| 0x506e3    | 2         | 1.98%   |
| 0x40651    | 2         | 1.98%   |
| 0x106e5    | 2         | 1.98%   |
| 0x08600106 | 2         | 1.98%   |
| 0x06006705 | 2         | 1.98%   |
| 0xa0660    | 1         | 0.99%   |
| 0x806ea    | 1         | 0.99%   |
| 0x806c1    | 1         | 0.99%   |
| 0x706a8    | 1         | 0.99%   |
| 0x706a1    | 1         | 0.99%   |
| 0x506c9    | 1         | 0.99%   |
| 0x406e3    | 1         | 0.99%   |
| 0x20655    | 1         | 0.99%   |
| 0x1067a    | 1         | 0.99%   |
| 0x10676    | 1         | 0.99%   |
| 0x0a50000b | 1         | 0.99%   |
| 0x08608103 | 1         | 0.99%   |
| 0x08600104 | 1         | 0.99%   |
| 0x08108109 | 1         | 0.99%   |
| 0x08101007 | 1         | 0.99%   |
| 0x0700010f | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 22        | 22.45%  |
| Zen 2           | 10        | 10.2%   |
| Haswell         | 8         | 8.16%   |
| SandyBridge     | 7         | 7.14%   |
| IvyBridge       | 7         | 7.14%   |
| Zen 3           | 6         | 6.12%   |
| Skylake         | 6         | 6.12%   |
| CometLake       | 6         | 6.12%   |
| Zen+            | 4         | 4.08%   |
| Penryn          | 3         | 3.06%   |
| Goldmont plus   | 3         | 3.06%   |
| TigerLake       | 2         | 2.04%   |
| Puma            | 2         | 2.04%   |
| Nehalem         | 2         | 2.04%   |
| Excavator       | 2         | 2.04%   |
| Zen             | 1         | 1.02%   |
| Westmere        | 1         | 1.02%   |
| Steamroller     | 1         | 1.02%   |
| Silvermont      | 1         | 1.02%   |
| K8 & K10 hybrid | 1         | 1.02%   |
| Jaguar          | 1         | 1.02%   |
| Goldmont        | 1         | 1.02%   |
| Unknown         | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 42.96%  |
| Nvidia | 49        | 34.51%  |
| AMD    | 32        | 22.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                            | 10        | 6.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 7         | 4.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 7         | 4.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 4.05%   |
| AMD Cezanne                                                                           | 6         | 4.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 5         | 3.38%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 5         | 3.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 3.38%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 4         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 4         | 2.7%    |
| Intel HD Graphics 630                                                                 | 4         | 2.7%    |
| Intel HD Graphics 620                                                                 | 4         | 2.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 4         | 2.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 2.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 2.03%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 3         | 2.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 2.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 2.03%   |
| Nvidia TU117M                                                                         | 2         | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.35%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 2         | 1.35%   |
| Intel UHD Graphics 620                                                                | 2         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 1.35%   |
| Intel HD Graphics 530                                                                 | 2         | 1.35%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 2         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 1.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 1.35%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 1         | 0.68%   |
| Nvidia GT218M [NVS 3100M]                                                             | 1         | 0.68%   |
| Nvidia GT215GLM [Quadro FX 1800M]                                                     | 1         | 0.68%   |
| Nvidia Graphics Device                                                                | 1         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 0.68%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                              | 1         | 0.68%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 1         | 0.68%   |
| Nvidia GM204 [GeForce GTX 980]                                                        | 1         | 0.68%   |
| Nvidia GM108M [GeForce MX110]                                                         | 1         | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.68%   |
| Nvidia GK104M [GeForce GTX 880M]                                                      | 1         | 0.68%   |
| Nvidia GF119M [GeForce 610M]                                                          | 1         | 0.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 0.68%   |
| Nvidia GF106M [GeForce GT 550M]                                                       | 1         | 0.68%   |
| Nvidia GF106GLM [Quadro 2000M]                                                        | 1         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 0.68%   |
| Nvidia C79 [GeForce 9100M G]                                                          | 1         | 0.68%   |
| Intel UHD Graphics 615                                                                | 1         | 0.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 0.68%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 0.68%   |
| Intel HD Graphics 510                                                                 | 1         | 0.68%   |
| Intel HD Graphics 500                                                                 | 1         | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 0.68%   |
| Intel Comet Lake UHD Graphics                                                         | 1         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 0.68%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 1         | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 31        | 31.63%  |
| Intel + Nvidia     | 26        | 26.53%  |
| AMD + Nvidia       | 14        | 14.29%  |
| 1 x AMD            | 13        | 13.27%  |
| 1 x Nvidia         | 8         | 8.16%   |
| Intel + AMD        | 3         | 3.06%   |
| 2 x AMD            | 2         | 2.04%   |
| Intel + 2 x Nvidia | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 63        | 63.64%  |
| Proprietary | 36        | 36.36%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 63%     |
| 0.01-0.5   | 16        | 16%     |
| 1.01-2.0   | 9         | 9%      |
| 3.01-4.0   | 5         | 5%      |
| 5.01-6.0   | 4         | 4%      |
| 0.51-1.0   | 2         | 2%      |
| 7.01-8.0   | 1         | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 24        | 21.62%  |
| LG Display              | 20        | 18.02%  |
| Chimei Innolux          | 13        | 11.71%  |
| BOE                     | 12        | 10.81%  |
| Samsung Electronics     | 8         | 7.21%   |
| PANDA                   | 7         | 6.31%   |
| Sharp                   | 5         | 4.5%    |
| Lenovo                  | 3         | 2.7%    |
| CSO                     | 2         | 1.8%    |
| Acer                    | 2         | 1.8%    |
| Sony                    | 1         | 0.9%    |
| Philips                 | 1         | 0.9%    |
| Mi                      | 1         | 0.9%    |
| InfoVision              | 1         | 0.9%    |
| Hewlett-Packard         | 1         | 0.9%    |
| Goldstar                | 1         | 0.9%    |
| G-Story                 | 1         | 0.9%    |
| Eizo                    | 1         | 0.9%    |
| Dell                    | 1         | 0.9%    |
| CPT                     | 1         | 0.9%    |
| Chi Mei Optoelectronics | 1         | 0.9%    |
| BenQ                    | 1         | 0.9%    |
| ASUSTek Computer        | 1         | 0.9%    |
| Apple                   | 1         | 0.9%    |
| AOC                     | 1         | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.7%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch  | 2         | 1.8%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.8%    |
| PANDA LCD Monitor NCP0036 1920x1080 340x190mm 15.3-inch               | 2         | 1.8%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 1.8%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.8%    |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.9%    |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.9%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.9%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.9%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.9%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.9%    |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch     | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 1         | 0.9%    |
| Philips 272P4 PHL08C5 2560x1440 597x336mm 27.0-inch                   | 1         | 0.9%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.9%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.9%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.9%    |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                      | 1         | 0.9%    |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD046A 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD03FE 1920x1080 345x194mm 15.6-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD01AF 1680x1050 331x207mm 15.4-inch          | 1         | 0.9%    |
| Lenovo LEN L27q-10 LEN65CE 2560x1440 597x336mm 27.0-inch              | 1         | 0.9%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 1         | 0.9%    |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 1         | 0.9%    |
| InfoVision LCD Monitor IVO061F 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| Hewlett-Packard Z23i HWP3090 1920x1080 509x286mm 23.0-inch            | 1         | 0.9%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 0.9%    |
| G-Story GSW56TB-HDMI GSV1560 1920x1080 345x194mm 15.6-inch            | 1         | 0.9%    |
| Eizo L885 ENC1705 1600x1200 408x306mm 20.1-inch                       | 1         | 0.9%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.9%    |
| CSO LCD Monitor CSO1601 2560x1600 345x215mm 16.0-inch                 | 1         | 0.9%    |
| CSO LCD Monitor CSO1600 2560x1600 345x215mm 16.0-inch                 | 1         | 0.9%    |
| CPT LCD Monitor CPT1464 1440x900 331x207mm 15.4-inch                  | 1         | 0.9%    |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch      | 1         | 0.9%    |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch      | 1         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1746 1600x900 382x214mm 17.2-inch       | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 57        | 54.81%  |
| 1366x768 (WXGA)    | 19        | 18.27%  |
| 1600x900 (HD+)     | 7         | 6.73%   |
| 2560x1440 (QHD)    | 4         | 3.85%   |
| 3840x2160 (4K)     | 2         | 1.92%   |
| 2560x1600          | 2         | 1.92%   |
| 1680x1050 (WSXGA+) | 2         | 1.92%   |
| 1280x800 (WXGA)    | 2         | 1.92%   |
| 3840x2400          | 1         | 0.96%   |
| 3440x1440          | 1         | 0.96%   |
| 3200x1800 (QHD+)   | 1         | 0.96%   |
| 2256x1504          | 1         | 0.96%   |
| 2160x1440          | 1         | 0.96%   |
| 1920x1200 (WUXGA)  | 1         | 0.96%   |
| 1680x945           | 1         | 0.96%   |
| 1600x1200          | 1         | 0.96%   |
| 1440x900 (WXGA+)   | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 61        | 55.45%  |
| 14      | 12        | 10.91%  |
| 17      | 8         | 7.27%   |
| 13      | 8         | 7.27%   |
| 27      | 4         | 3.64%   |
| 23      | 3         | 2.73%   |
| 18      | 3         | 2.73%   |
| 21      | 2         | 1.82%   |
| 16      | 2         | 1.82%   |
| 72      | 1         | 0.91%   |
| 34      | 1         | 0.91%   |
| 24      | 1         | 0.91%   |
| 22      | 1         | 0.91%   |
| 20      | 1         | 0.91%   |
| 11      | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 79        | 71.82%  |
| 501-600     | 8         | 7.27%   |
| 351-400     | 8         | 7.27%   |
| 401-500     | 7         | 6.36%   |
| 201-300     | 5         | 4.55%   |
| 701-800     | 1         | 0.91%   |
| 1501-2000   | 1         | 0.91%   |
| Unknown     | 1         | 0.91%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 89        | 87.25%  |
| 16/10 | 9         | 8.82%   |
| 3/2   | 2         | 1.96%   |
| 4/3   | 1         | 0.98%   |
| 21/9  | 1         | 0.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 60        | 54.55%  |
| 81-90          | 18        | 16.36%  |
| 121-130        | 8         | 7.27%   |
| 201-250        | 5         | 4.55%   |
| 301-350        | 4         | 3.64%   |
| 141-150        | 3         | 2.73%   |
| 71-80          | 2         | 1.82%   |
| 151-200        | 2         | 1.82%   |
| 111-120        | 2         | 1.82%   |
| More than 1000 | 1         | 0.91%   |
| 51-60          | 1         | 0.91%   |
| 351-500        | 1         | 0.91%   |
| 251-300        | 1         | 0.91%   |
| 91-100         | 1         | 0.91%   |
| Unknown        | 1         | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 58        | 54.21%  |
| 101-120       | 28        | 26.17%  |
| 51-100        | 11        | 10.28%  |
| 161-240       | 5         | 4.67%   |
| More than 240 | 3         | 2.8%    |
| 1-50          | 1         | 0.93%   |
| Unknown       | 1         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 78        | 78.79%  |
| 2     | 20        | 20.2%   |
| 0     | 1         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 57        | 35.63%  |
| Intel                 | 52        | 32.5%   |
| Qualcomm Atheros      | 28        | 17.5%   |
| Broadcom              | 8         | 5%      |
| Samsung Electronics   | 2         | 1.25%   |
| MEDIATEK              | 2         | 1.25%   |
| Xiaomi                | 1         | 0.63%   |
| Wacom                 | 1         | 0.63%   |
| TP-Link               | 1         | 0.63%   |
| Ralink Technology     | 1         | 0.63%   |
| Qualcomm              | 1         | 0.63%   |
| Nvidia                | 1         | 0.63%   |
| NetGear               | 1         | 0.63%   |
| Lenovo                | 1         | 0.63%   |
| DisplayLink           | 1         | 0.63%   |
| ASUSTek Computer      | 1         | 0.63%   |
| ASIX Electronics      | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 39        | 20.86%  |
| Intel Wi-Fi 6 AX200                                                     | 12        | 6.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 3.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.67%   |
| Intel Wireless 3165                                                     | 5         | 2.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 2.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 4         | 2.14%   |
| Intel Wireless 7260                                                     | 4         | 2.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.14%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 1.6%    |
| Intel Wireless 8265 / 8275                                              | 3         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.6%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.6%    |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.07%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.07%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.07%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.07%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 2         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.53%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                | 1         | 0.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.53%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.53%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.53%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.53%   |
| Qualcomm U673C                                                          | 1         | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.53%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.53%   |
| MediaTek WiFi                                                           | 1         | 0.53%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.53%   |
| Lenovo ThinkPad Lan                                                     | 1         | 0.53%   |
| Intel Wireless 8260                                                     | 1         | 0.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.53%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.53%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.53%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.53%   |
| Intel Ethernet Connection I217-V                                        | 1         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                   | 1         | 0.53%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 48.04%  |
| Qualcomm Atheros      | 24        | 23.53%  |
| Realtek Semiconductor | 15        | 14.71%  |
| Broadcom              | 7         | 6.86%   |
| MEDIATEK              | 2         | 1.96%   |
| Wacom                 | 1         | 0.98%   |
| TP-Link               | 1         | 0.98%   |
| Ralink Technology     | 1         | 0.98%   |
| NetGear               | 1         | 0.98%   |
| ASUSTek Computer      | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 12        | 11.65%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 6.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 5.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.85%   |
| Intel Wireless 3165                                                     | 5         | 4.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 4.85%   |
| Intel Wireless 7260                                                     | 4         | 3.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 3.88%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.91%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.94%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.94%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                | 1         | 0.97%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.97%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.97%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.97%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.97%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.97%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.97%   |
| MediaTek WiFi                                                           | 1         | 0.97%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.97%   |
| Intel Wireless 8260                                                     | 1         | 0.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.97%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.97%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.97%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.97%   |
| Intel Centrino Wireless-N 100                                           | 1         | 0.97%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.97%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.97%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.97%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.97%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]          | 1         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 50        | 59.52%  |
| Intel                 | 15        | 17.86%  |
| Qualcomm Atheros      | 8         | 9.52%   |
| Broadcom              | 3         | 3.57%   |
| Samsung Electronics   | 2         | 2.38%   |
| Xiaomi                | 1         | 1.19%   |
| Qualcomm              | 1         | 1.19%   |
| Nvidia                | 1         | 1.19%   |
| Lenovo                | 1         | 1.19%   |
| DisplayLink           | 1         | 1.19%   |
| ASIX Electronics      | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 46.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 4.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 3.57%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 3.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.38%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 2.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.19%   |
| Qualcomm U673C                                                    | 1         | 1.19%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.19%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.19%   |
| Lenovo ThinkPad Lan                                               | 1         | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.19%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.19%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.19%   |
| DisplayLink Dell D1000 USB3.0 Dock                                | 1         | 1.19%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.19%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 54.86%  |
| Ethernet | 79        | 45.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 72.73%  |
| Ethernet | 30        | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 72        | 73.47%  |
| 1     | 24        | 24.49%  |
| 3     | 1         | 1.02%   |
| 0     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 77.78%  |
| Yes  | 22        | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 44.32%  |
| Qualcomm Atheros Communications | 18        | 20.45%  |
| Realtek Semiconductor           | 10        | 11.36%  |
| IMC Networks                    | 5         | 5.68%   |
| Lite-On Technology              | 4         | 4.55%   |
| Broadcom                        | 4         | 4.55%   |
| Hewlett-Packard                 | 2         | 2.27%   |
| Foxconn / Hon Hai               | 2         | 2.27%   |
| Dell                            | 2         | 2.27%   |
| Cambridge Silicon Radio         | 1         | 1.14%   |
| Apple                           | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 26        | 29.55%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 7.95%   |
| Realtek Bluetooth Radio                                                             | 5         | 5.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 5.68%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 4.55%   |
| Intel Bluetooth wireless interface                                                  | 3         | 3.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 2.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.27%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.27%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1.14%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.14%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.14%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.14%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.14%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.14%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.14%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.14%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.14%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.14%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.14%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.14%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 1.14%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.14%   |
| Broadcom BCM2045A0                                                                  | 1         | 1.14%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 68        | 54.4%   |
| AMD                 | 29        | 23.2%   |
| Nvidia              | 21        | 16.8%   |
| Turtle Beach        | 1         | 0.8%    |
| RODE Microphones    | 1         | 0.8%    |
| Phison Electronics  | 1         | 0.8%    |
| JMTek               | 1         | 0.8%    |
| Huawei Technologies | 1         | 0.8%    |
| GN Netcom           | 1         | 0.8%    |
| Corsair             | 1         | 0.8%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 22        | 14.67%  |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 7.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 4.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.33%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 3.33%   |
| Intel CM238 HD Audio Controller                                            | 5         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 3.33%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 2.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.67%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.67%   |
| Nvidia Audio device                                                        | 3         | 2%      |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2%      |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2%      |
| Intel 8 Series HD Audio Controller                                         | 3         | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2%      |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2%      |
| Nvidia High Definition Audio Controller                                    | 2         | 1.33%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.33%   |
| Nvidia GF106 High Definition Audio Controller                              | 2         | 1.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.33%   |
| AMD High Definition Audio Controller                                       | 2         | 1.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.33%   |
| Turtle Beach Ear Force P11 Headset                                         | 1         | 0.67%   |
| RODE Microphones RODE NT-USB                                               | 1         | 0.67%   |
| Phison Electronics SoundYou Voyage                                         | 1         | 0.67%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.67%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.67%   |
| Huawei Technologies USB-C HEADSET                                          | 1         | 0.67%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                            | 1         | 0.67%   |
| Corsair HS70 Pro Wireless Gaming Headset                                   | 1         | 0.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.67%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 29.21%  |
| SK Hynix            | 17        | 19.1%   |
| Crucial             | 11        | 12.36%  |
| Micron Technology   | 9         | 10.11%  |
| Unknown             | 4         | 4.49%   |
| Ramaxel Technology  | 3         | 3.37%   |
| Corsair             | 3         | 3.37%   |
| Unknown (ABCD)      | 2         | 2.25%   |
| Smart               | 2         | 2.25%   |
| Nanya Technology    | 2         | 2.25%   |
| Kingston            | 2         | 2.25%   |
| A-DATA Technology   | 2         | 2.25%   |
| Transcend           | 1         | 1.12%   |
| Patriot             | 1         | 1.12%   |
| G.Skill             | 1         | 1.12%   |
| CSX                 | 1         | 1.12%   |
| Avant               | 1         | 1.12%   |
| 48spaces            | 1         | 1.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 4.26%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 3.19%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 3.19%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 3         | 3.19%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR3 2400MT/s    | 2         | 2.13%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 2.13%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 2         | 2.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.13%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s            | 2         | 2.13%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 2.13%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 2.13%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 2.13%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 2         | 2.13%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                         | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 1.06%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s            | 1         | 1.06%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s               | 1         | 1.06%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB DDR4 2667MT/s                   | 1         | 1.06%   |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s                | 1         | 1.06%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.06%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.06%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.06%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 1.06%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s        | 1         | 1.06%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 1.06%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.06%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 1.06%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1600MT/s               | 1         | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.06%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.06%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.06%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.06%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.06%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| Patriot RAM PSD38G16002S 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.06%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s               | 1         | 1.06%   |
| Micron RAM MT53E1G32D4NQ-046WTE 8192MB Row Of Chips LPDDR4 4266MT/s | 1         | 1.06%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s               | 1         | 1.06%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.06%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.06%   |
| Micron RAM 8ATF1G64HDZ-2G3B1 8GB SODIMM DDR4 2400MT/s               | 1         | 1.06%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s               | 1         | 1.06%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 1         | 1.06%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s               | 1         | 1.06%   |
| Kingston RAM KHX2133C13S4/8G 8192MB SODIMM DDR4 2133MT/s            | 1         | 1.06%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s              | 1         | 1.06%   |
| G.Skill RAM F3-1600C9-8GRSL 8192MB SODIMM DDR3 1600MT/s             | 1         | 1.06%   |
| CSX RAM V01D4S88GB1G81G82400 8GB SODIMM DDR4 2400MT/s               | 1         | 1.06%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s              | 1         | 1.06%   |
| Crucial RAM CT8G4SFS824A.C8FBD1 8GB SODIMM DDR4 2667MT/s            | 1         | 1.06%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 45        | 60.81%  |
| DDR3   | 23        | 31.08%  |
| LPDDR4 | 3         | 4.05%   |
| DDR2   | 2         | 2.7%    |
| LPDDR3 | 1         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 89.47%  |
| Row Of Chips | 7         | 9.21%   |
| Unknown      | 1         | 1.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 43        | 53.09%  |
| 4096  | 26        | 32.1%   |
| 16384 | 8         | 9.88%   |
| 2048  | 4         | 4.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 21        | 25.61%  |
| 2667  | 20        | 24.39%  |
| 1600  | 18        | 21.95%  |
| 2400  | 10        | 12.2%   |
| 1334  | 3         | 3.66%   |
| 3266  | 2         | 2.44%   |
| 1333  | 2         | 2.44%   |
| 4266  | 1         | 1.22%   |
| 2133  | 1         | 1.22%   |
| 1867  | 1         | 1.22%   |
| 1866  | 1         | 1.22%   |
| 800   | 1         | 1.22%   |
| 667   | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Kyocera             | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series  | 1         | 33.33%  |
| Kyocera FS-1030D printer        | 1         | 33.33%  |
| HP LaserJet 200 colorMFP M275nw | 1         | 33.33%  |

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
| Chicony Electronics                    | 28        | 31.11%  |
| IMC Networks                           | 10        | 11.11%  |
| Microdia                               | 9         | 10%     |
| Realtek Semiconductor                  | 8         | 8.89%   |
| Sunplus Innovation Technology          | 4         | 4.44%   |
| Quanta                                 | 4         | 4.44%   |
| Acer                                   | 4         | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.33%   |
| Apple                                  | 3         | 3.33%   |
| Syntek                                 | 2         | 2.22%   |
| Suyin                                  | 2         | 2.22%   |
| Silicon Motion                         | 2         | 2.22%   |
| Luxvisions Innotech Limited            | 2         | 2.22%   |
| WaveRider Communications               | 1         | 1.11%   |
| Sonix Technology                       | 1         | 1.11%   |
| Samsung Electronics                    | 1         | 1.11%   |
| Microsoft                              | 1         | 1.11%   |
| Logitech                               | 1         | 1.11%   |
| Lite-On Technology                     | 1         | 1.11%   |
| Lenovo                                 | 1         | 1.11%   |
| Importek                               | 1         | 1.11%   |
| Genesys Logic                          | 1         | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 6         | 6.67%   |
| IMC Networks Integrated Camera                                             | 5         | 5.56%   |
| Chicony Integrated Camera                                                  | 5         | 5.56%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 4         | 4.44%   |
| Chicony HD WebCam                                                          | 4         | 4.44%   |
| Chicony HD User Facing                                                     | 4         | 4.44%   |
| Syntek Integrated Camera                                                   | 2         | 2.22%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 2.22%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 2.22%   |
| Chicony USB 2.0 Camera                                                     | 2         | 2.22%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 2.22%   |
| Chicony EasyCamera                                                         | 2         | 2.22%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 2         | 2.22%   |
| WaveRider USB 2.0 Camera                                                   | 1         | 1.11%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 1.11%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.11%   |
| Sunplus USB2.0 Camera                                                      | 1         | 1.11%   |
| Sunplus MTD Camera                                                         | 1         | 1.11%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 1.11%   |
| Silicon Motion WebCam SCB-1100N                                            | 1         | 1.11%   |
| Silicon Motion Web Camera                                                  | 1         | 1.11%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.11%   |
| Realtek USB Camera                                                         | 1         | 1.11%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 1.11%   |
| Realtek Integrated Webcam                                                  | 1         | 1.11%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 1.11%   |
| Realtek HD WebCam                                                          | 1         | 1.11%   |
| Realtek EasyCamera                                                         | 1         | 1.11%   |
| Realtek Built-In Video Camera                                              | 1         | 1.11%   |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 1.11%   |
| Quanta WEBCAM                                                              | 1         | 1.11%   |
| Quanta HD User Facing                                                      | 1         | 1.11%   |
| Microsoft LifeCam HD-3000                                                  | 1         | 1.11%   |
| Microdia Webcam Vitade AF                                                  | 1         | 1.11%   |
| Microdia PC Microscope camera                                              | 1         | 1.11%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.11%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 1         | 1.11%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.11%   |
| Logitech Webcam Pro 9000                                                   | 1         | 1.11%   |
| Lite-On HP Wide Vision HD Camera                                           | 1         | 1.11%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 1.11%   |
| Importek TOSHIBA Web Camera - HD                                           | 1         | 1.11%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 1.11%   |
| Genesys Logic USB 2.0 Camera                                               | 1         | 1.11%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 1.11%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.11%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.11%   |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 1.11%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.11%   |
| Chicony HP Truevision HD                                                   | 1         | 1.11%   |
| Chicony HP HD Webcam                                                       | 1         | 1.11%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.11%   |
| Chicony CKF7037 HP webcam                                                  | 1         | 1.11%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.11%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 1         | 1.11%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.11%   |
| Apple FaceTime HD Camera                                                   | 1         | 1.11%   |
| Acer SunplusIT INC. Integrated Camera                                      | 1         | 1.11%   |
| Acer Integrated Camera                                                     | 1         | 1.11%   |
| Acer HD Webcam                                                             | 1         | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 35.71%  |
| Synaptics                  | 3         | 21.43%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |
| LighTuning Technology      | 2         | 14.29%  |
| AuthenTec                  | 2         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 2         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 7.14%   |
| Synaptics WBDI Device                             | 1         | 7.14%   |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 7.14%   |
| Shenzhen Goodix FingerPrint                       | 1         | 7.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 7.14%   |
| AuthenTec AES2810                                 | 1         | 7.14%   |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 57.14%  |
| Upek        | 1         | 14.29%  |
| Lenovo      | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 14.29%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 48.48%  |
| 0     | 26        | 26.26%  |
| 2     | 22        | 22.22%  |
| 3     | 3         | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 63        | 60.58%  |
| Fingerprint reader       | 14        | 13.46%  |
| Chipcard                 | 7         | 6.73%   |
| Graphics card            | 6         | 5.77%   |
| Net/wireless             | 4         | 3.85%   |
| Net/ethernet             | 4         | 3.85%   |
| Multimedia controller    | 2         | 1.92%   |
| Wireless                 | 1         | 0.96%   |
| Storage                  | 1         | 0.96%   |
| Camera                   | 1         | 0.96%   |
| Bluetooth                | 1         | 0.96%   |


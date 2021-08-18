Ubuntu 21.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.04 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-21.04

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
| ASUSTek       | K52Je                       | [d35de28c56](https://linux-hardware.org/?probe=d35de28c56) | Aug 17, 2021 |
| HP            | ENVY 17                     | [339f78f408](https://linux-hardware.org/?probe=339f78f408) | Aug 17, 2021 |
| Acer          | Nitro AN515-57              | [3c18d3a700](https://linux-hardware.org/?probe=3c18d3a700) | Aug 17, 2021 |
| Lenovo        | ThinkPad W541 20EF0020GE    | [ea3fc647ce](https://linux-hardware.org/?probe=ea3fc647ce) | Aug 17, 2021 |
| HP            | EliteBook 820 G1            | [00bff94489](https://linux-hardware.org/?probe=00bff94489) | Aug 17, 2021 |
| Acer          | Swift SF314-54              | [d238322295](https://linux-hardware.org/?probe=d238322295) | Aug 16, 2021 |
| Medion        | P6640                       | [e83d5a51ac](https://linux-hardware.org/?probe=e83d5a51ac) | Aug 16, 2021 |
| Acer          | Aspire 5733                 | [7d63c49cee](https://linux-hardware.org/?probe=7d63c49cee) | Aug 16, 2021 |
| Notebook      | W94_95_97JU                 | [816ddae34c](https://linux-hardware.org/?probe=816ddae34c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8e47965ba8](https://linux-hardware.org/?probe=8e47965ba8) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [f406892aa9](https://linux-hardware.org/?probe=f406892aa9) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b333da4703](https://linux-hardware.org/?probe=b333da4703) | Aug 14, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [3a83d976d0](https://linux-hardware.org/?probe=3a83d976d0) | Aug 14, 2021 |
| Dell          | Inspiron 1525               | [7df7534dd9](https://linux-hardware.org/?probe=7df7534dd9) | Aug 14, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [977c948bad](https://linux-hardware.org/?probe=977c948bad) | Aug 14, 2021 |
| Apple         | MacBookAir3,2               | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| HP            | EliteBook Folio 1040 G3     | [d03439a8d0](https://linux-hardware.org/?probe=d03439a8d0) | Aug 14, 2021 |
| Medion        | E2213 MD60193               | [5bb52d1b1b](https://linux-hardware.org/?probe=5bb52d1b1b) | Aug 14, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [6346388737](https://linux-hardware.org/?probe=6346388737) | Aug 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [11f9ccb3ad](https://linux-hardware.org/?probe=11f9ccb3ad) | Aug 13, 2021 |
| Radxa         | ROCK Pi X v1.4              | [d5c46e7235](https://linux-hardware.org/?probe=d5c46e7235) | Aug 13, 2021 |
| Dell          | XPS 15 7590                 | [8bb8411127](https://linux-hardware.org/?probe=8bb8411127) | Aug 13, 2021 |
| Acer          | TravelMate B117-M           | [be84ceed7a](https://linux-hardware.org/?probe=be84ceed7a) | Aug 12, 2021 |
| MSI           | Modern 14 A10M              | [d6668ff825](https://linux-hardware.org/?probe=d6668ff825) | Aug 12, 2021 |
| HP            | EliteBook Folio 1040 G3     | [fbeb3986b3](https://linux-hardware.org/?probe=fbeb3986b3) | Aug 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [6d351fec42](https://linux-hardware.org/?probe=6d351fec42) | Aug 12, 2021 |
| Dell          | G5 5587                     | [204e0318ab](https://linux-hardware.org/?probe=204e0318ab) | Aug 12, 2021 |
| Razer         | Blade                       | [d04a50103d](https://linux-hardware.org/?probe=d04a50103d) | Aug 11, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [1f6745d6bb](https://linux-hardware.org/?probe=1f6745d6bb) | Aug 11, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [d24254d911](https://linux-hardware.org/?probe=d24254d911) | Aug 11, 2021 |
| Dell          | Latitude 5400               | [4f804f2046](https://linux-hardware.org/?probe=4f804f2046) | Aug 11, 2021 |
| HP            | Laptop 15s-du1xxx           | [19412614ef](https://linux-hardware.org/?probe=19412614ef) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [90ae378555](https://linux-hardware.org/?probe=90ae378555) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [268452e2ee](https://linux-hardware.org/?probe=268452e2ee) | Aug 11, 2021 |
| ASUSTek       | TP300LA                     | [f5dca95f99](https://linux-hardware.org/?probe=f5dca95f99) | Aug 11, 2021 |
| Apple         | MacBookPro7,1               | [4b8bdfd1eb](https://linux-hardware.org/?probe=4b8bdfd1eb) | Aug 10, 2021 |
| Dell          | Latitude E6330              | [cc6a9823e1](https://linux-hardware.org/?probe=cc6a9823e1) | Aug 10, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | 15 Notebook PC              | [d01d6a6ab0](https://linux-hardware.org/?probe=d01d6a6ab0) | Aug 10, 2021 |
| ASUSTek       | T100HAN                     | [8b463c7abb](https://linux-hardware.org/?probe=8b463c7abb) | Aug 10, 2021 |
| Dell          | Latitude E5400              | [c54ea52d26](https://linux-hardware.org/?probe=c54ea52d26) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| HP            | ProBook 450 G5              | [f8bbb08a59](https://linux-hardware.org/?probe=f8bbb08a59) | Aug 09, 2021 |
| HP            | ProBook 450 G5              | [8e62a52f33](https://linux-hardware.org/?probe=8e62a52f33) | Aug 09, 2021 |
| LG Electro... | 17Z90P-G.AD88B              | [d18eda768e](https://linux-hardware.org/?probe=d18eda768e) | Aug 09, 2021 |
| ASUSTek       | N552VW                      | [9cc9b3d62e](https://linux-hardware.org/?probe=9cc9b3d62e) | Aug 09, 2021 |
| Monster       | TULPAR T7 V20.4             | [f94dfc2fc6](https://linux-hardware.org/?probe=f94dfc2fc6) | Aug 09, 2021 |
| HP            | Laptop 15-da0xxx            | [22fa8558fa](https://linux-hardware.org/?probe=22fa8558fa) | Aug 09, 2021 |
| Dell          | Precision M6600             | [58b77bf05d](https://linux-hardware.org/?probe=58b77bf05d) | Aug 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e88a377feb](https://linux-hardware.org/?probe=e88a377feb) | Aug 08, 2021 |
| HP            | EliteBook 8570w             | [59783ba71d](https://linux-hardware.org/?probe=59783ba71d) | Aug 08, 2021 |
| HP            | EliteBook 8570w             | [093f956e28](https://linux-hardware.org/?probe=093f956e28) | Aug 08, 2021 |
| HP            | EliteBook 840 G4            | [756d4b46ad](https://linux-hardware.org/?probe=756d4b46ad) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [45d400c67b](https://linux-hardware.org/?probe=45d400c67b) | Aug 08, 2021 |
| Dell          | Inspiron N5110              | [f36ecee8d1](https://linux-hardware.org/?probe=f36ecee8d1) | Aug 07, 2021 |
| Dell          | Latitude 5290 2-in-1        | [293b45eded](https://linux-hardware.org/?probe=293b45eded) | Aug 07, 2021 |
| Panasonic     | CF-19KDR78CE                | [29eee33555](https://linux-hardware.org/?probe=29eee33555) | Aug 07, 2021 |
| ASUSTek       | E402SA                      | [790033a704](https://linux-hardware.org/?probe=790033a704) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| Medion        | P6640                       | [ee12482cc7](https://linux-hardware.org/?probe=ee12482cc7) | Aug 07, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [3d2bc47483](https://linux-hardware.org/?probe=3d2bc47483) | Aug 07, 2021 |
| HP            | EliteBook 840 G4            | [0dd35a18fe](https://linux-hardware.org/?probe=0dd35a18fe) | Aug 07, 2021 |
| Dell          | XPS 13 9380                 | [9ffd679117](https://linux-hardware.org/?probe=9ffd679117) | Aug 07, 2021 |
| Dell          | XPS 13 9380                 | [e9e8cca53d](https://linux-hardware.org/?probe=e9e8cca53d) | Aug 07, 2021 |
| ASUSTek       | X550CA                      | [a1e7efd7c1](https://linux-hardware.org/?probe=a1e7efd7c1) | Aug 07, 2021 |
| HP            | EliteBook 840 G3            | [78bd17f4c4](https://linux-hardware.org/?probe=78bd17f4c4) | Aug 06, 2021 |
| HP            | ProBook 4540s               | [52b0186956](https://linux-hardware.org/?probe=52b0186956) | Aug 06, 2021 |
| eMachines     | E627                        | [b83fe7564f](https://linux-hardware.org/?probe=b83fe7564f) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-ba1xxx       | [da4fd46a9b](https://linux-hardware.org/?probe=da4fd46a9b) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [6af058344f](https://linux-hardware.org/?probe=6af058344f) | Aug 06, 2021 |
| Dell          | Inspiron 5515               | [975daf858c](https://linux-hardware.org/?probe=975daf858c) | Aug 06, 2021 |
| Acer          | Aspire ES1-511              | [d8963041b5](https://linux-hardware.org/?probe=d8963041b5) | Aug 06, 2021 |
| HP            | ProBook 640 G1              | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [e0b87e63a3](https://linux-hardware.org/?probe=e0b87e63a3) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | [47fca1c82c](https://linux-hardware.org/?probe=47fca1c82c) | Aug 05, 2021 |
| HKC           | Y11CC                       | [a8e149ef22](https://linux-hardware.org/?probe=a8e149ef22) | Aug 05, 2021 |
| Fujitsu       | LIFEBOOK E752               | [85bd90092b](https://linux-hardware.org/?probe=85bd90092b) | Aug 05, 2021 |
| Unknown       | Unknown                     | [d4db86e4ac](https://linux-hardware.org/?probe=d4db86e4ac) | Aug 05, 2021 |
| Unknown       | Unknown                     | [bcb72c9247](https://linux-hardware.org/?probe=bcb72c9247) | Aug 05, 2021 |
| Dell          | Latitude 7380               | [c83f32076d](https://linux-hardware.org/?probe=c83f32076d) | Aug 05, 2021 |
| IP3 Tech      | X30                         | [700e39c30d](https://linux-hardware.org/?probe=700e39c30d) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Acer          | Swift SF313-53              | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [fc2c2761bc](https://linux-hardware.org/?probe=fc2c2761bc) | Aug 03, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [636e961fcc](https://linux-hardware.org/?probe=636e961fcc) | Aug 03, 2021 |
| ASUSTek       | X542UQ                      | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| ASUSTek       | K73BY                       | [37b4b1362f](https://linux-hardware.org/?probe=37b4b1362f) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3980... | [32507fdf80](https://linux-hardware.org/?probe=32507fdf80) | Aug 03, 2021 |
| Dell          | G3 3500                     | [3480d1f83d](https://linux-hardware.org/?probe=3480d1f83d) | Aug 03, 2021 |
| HP            | ENVY m6                     | [6d72ad672c](https://linux-hardware.org/?probe=6d72ad672c) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AW0002I... | [7f53bdba21](https://linux-hardware.org/?probe=7f53bdba21) | Aug 03, 2021 |
| Dell          | Inspiron 5301               | [2387a6a66c](https://linux-hardware.org/?probe=2387a6a66c) | Aug 03, 2021 |
| HP            | ProBook 4540s               | [42b95781f5](https://linux-hardware.org/?probe=42b95781f5) | Aug 03, 2021 |
| Acer          | Swift SF314-54G             | [04a33a7d5c](https://linux-hardware.org/?probe=04a33a7d5c) | Aug 02, 2021 |
| HP            | ZBook 15u G4                | [d77bb6209a](https://linux-hardware.org/?probe=d77bb6209a) | Aug 02, 2021 |
| ASUSTek       | K73BY                       | [8fb5845dd4](https://linux-hardware.org/?probe=8fb5845dd4) | Aug 02, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [5ac36e570a](https://linux-hardware.org/?probe=5ac36e570a) | Aug 02, 2021 |
| HP            | EliteBook 820 G1            | [7b564a6ba6](https://linux-hardware.org/?probe=7b564a6ba6) | Aug 02, 2021 |
| HP            | 250 G4                      | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| HP            | EliteBook 820 G1            | [e9e0269b1a](https://linux-hardware.org/?probe=e9e0269b1a) | Aug 01, 2021 |
| Acer          | Swift SF313-53              | [5144862148](https://linux-hardware.org/?probe=5144862148) | Aug 01, 2021 |
| HP            | Pavilion dm1                | [ac0e534d86](https://linux-hardware.org/?probe=ac0e534d86) | Aug 01, 2021 |
| Advance       | AN-5431                     | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| HP            | Presario CQ61               | [3496f82684](https://linux-hardware.org/?probe=3496f82684) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [fb4efe3736](https://linux-hardware.org/?probe=fb4efe3736) | Aug 01, 2021 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [22790f2a7e](https://linux-hardware.org/?probe=22790f2a7e) | Aug 01, 2021 |
| Alienware     | M17xR4                      | [940c3efccf](https://linux-hardware.org/?probe=940c3efccf) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [ec65d6706f](https://linux-hardware.org/?probe=ec65d6706f) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [91cc6c6711](https://linux-hardware.org/?probe=91cc6c6711) | Aug 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| MSI           | MS-16GF                     | [ba0b532d35](https://linux-hardware.org/?probe=ba0b532d35) | Aug 01, 2021 |
| Google        | Stout                       | [dcc159aacb](https://linux-hardware.org/?probe=dcc159aacb) | Aug 01, 2021 |
| Dell          | Latitude E5520              | [495c7ad655](https://linux-hardware.org/?probe=495c7ad655) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [e2db581d0b](https://linux-hardware.org/?probe=e2db581d0b) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [b893ad294a](https://linux-hardware.org/?probe=b893ad294a) | Jul 31, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [1e14356790](https://linux-hardware.org/?probe=1e14356790) | Jul 31, 2021 |
| Dell          | Vostro 14-5459              | [1a120753db](https://linux-hardware.org/?probe=1a120753db) | Jul 31, 2021 |
| HP            | Pavilion g6                 | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Dell          | Vostro 14-5459              | [affecdcdb7](https://linux-hardware.org/?probe=affecdcdb7) | Jul 31, 2021 |
| Apple         | MacBookPro9,2               | [abb1e8ea82](https://linux-hardware.org/?probe=abb1e8ea82) | Jul 31, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [842c9c2629](https://linux-hardware.org/?probe=842c9c2629) | Jul 30, 2021 |
| Dell          | XPS 15 9570                 | [75228088e0](https://linux-hardware.org/?probe=75228088e0) | Jul 30, 2021 |
| Dell          | Inspiron 5720               | [08e504b4d9](https://linux-hardware.org/?probe=08e504b4d9) | Jul 30, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [d7a0f68d0d](https://linux-hardware.org/?probe=d7a0f68d0d) | Jul 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [64b0d25c3a](https://linux-hardware.org/?probe=64b0d25c3a) | Jul 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5c8b0fb32b](https://linux-hardware.org/?probe=5c8b0fb32b) | Jul 29, 2021 |
| Sony          | SVF1521H2EW                 | [025ae9003b](https://linux-hardware.org/?probe=025ae9003b) | Jul 29, 2021 |
| Lenovo        | ThinkPad T430 2347AT2       | [ceac6ce540](https://linux-hardware.org/?probe=ceac6ce540) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [5cacc2c659](https://linux-hardware.org/?probe=5cacc2c659) | Jul 29, 2021 |
| Toshiba       | TECRA Z40-B                 | [d353412a4f](https://linux-hardware.org/?probe=d353412a4f) | Jul 29, 2021 |
| Sony          | VPCEJ1L1E                   | [03e1c179a3](https://linux-hardware.org/?probe=03e1c179a3) | Jul 29, 2021 |
| Samsung       | 935XDB                      | [ebc69d8a77](https://linux-hardware.org/?probe=ebc69d8a77) | Jul 29, 2021 |
| Sony          | VPCEJ1L1E                   | [a43c899910](https://linux-hardware.org/?probe=a43c899910) | Jul 29, 2021 |
| Dell          | Inspiron 5521               | [8242b46551](https://linux-hardware.org/?probe=8242b46551) | Jul 29, 2021 |
| Lenovo        | Unknown                     | [eef802c064](https://linux-hardware.org/?probe=eef802c064) | Jul 29, 2021 |
| ASUSTek       | T100HAN                     | [bdea6cca11](https://linux-hardware.org/?probe=bdea6cca11) | Jul 29, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [09419fd70a](https://linux-hardware.org/?probe=09419fd70a) | Jul 28, 2021 |
| Apple         | MacBookAir1,1               | [53bd733ffa](https://linux-hardware.org/?probe=53bd733ffa) | Jul 28, 2021 |
| Gigabyte      | i1520M                      | [5d0fb03190](https://linux-hardware.org/?probe=5d0fb03190) | Jul 28, 2021 |
| Gigabyte      | i1520M                      | [95de13078b](https://linux-hardware.org/?probe=95de13078b) | Jul 28, 2021 |
| HP            | 255 G7 Notebook PC          | [4b4496337a](https://linux-hardware.org/?probe=4b4496337a) | Jul 27, 2021 |
| Dell          | XPS 15 9570                 | [b6f42df92b](https://linux-hardware.org/?probe=b6f42df92b) | Jul 27, 2021 |
| Fujitsu       | LIFEBOOK E752               | [72e045b4da](https://linux-hardware.org/?probe=72e045b4da) | Jul 27, 2021 |
| Dell          | Latitude 7370               | [8844c61431](https://linux-hardware.org/?probe=8844c61431) | Jul 27, 2021 |
| Dell          | Latitude 7370               | [65b034f3f3](https://linux-hardware.org/?probe=65b034f3f3) | Jul 27, 2021 |
| Toshiba       | Satellite Pro L650          | [10e8624257](https://linux-hardware.org/?probe=10e8624257) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Chuwi         | GemiBook Pro                | [a4ecebc31b](https://linux-hardware.org/?probe=a4ecebc31b) | Jul 27, 2021 |
| ASUSTek       | X551CAP                     | [59e9b7398f](https://linux-hardware.org/?probe=59e9b7398f) | Jul 27, 2021 |
| HP            | ProBook 650 G1              | [98486b5f47](https://linux-hardware.org/?probe=98486b5f47) | Jul 27, 2021 |
| Dell          | Precision M6600             | [67a1d8b2e4](https://linux-hardware.org/?probe=67a1d8b2e4) | Jul 27, 2021 |
| ASUSTek       | N551JM                      | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| HP            | ProBook 650 G1              | [86b2b34f64](https://linux-hardware.org/?probe=86b2b34f64) | Jul 27, 2021 |
| ASUSTek       | G73Jh                       | [e7af78fad2](https://linux-hardware.org/?probe=e7af78fad2) | Jul 26, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [177743cfae](https://linux-hardware.org/?probe=177743cfae) | Jul 26, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [b56b5cfff2](https://linux-hardware.org/?probe=b56b5cfff2) | Jul 26, 2021 |
| roda compu... | DS13                        | [be0c6525a4](https://linux-hardware.org/?probe=be0c6525a4) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire V5-531P              | [b236b9b9d9](https://linux-hardware.org/?probe=b236b9b9d9) | Jul 26, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [26ab6b470a](https://linux-hardware.org/?probe=26ab6b470a) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f3199bc88b](https://linux-hardware.org/?probe=f3199bc88b) | Jul 25, 2021 |
| Dell          | XPS 15 9510                 | [074932b079](https://linux-hardware.org/?probe=074932b079) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | [335bb2e92e](https://linux-hardware.org/?probe=335bb2e92e) | Jul 25, 2021 |
| ASUSTek       | T100HAN                     | [8d6daa25e8](https://linux-hardware.org/?probe=8d6daa25e8) | Jul 25, 2021 |
| HP            | ProBook 650 G5              | [6d3f09e9c2](https://linux-hardware.org/?probe=6d3f09e9c2) | Jul 25, 2021 |
| HP            | ProBook 650 G5              | [7580d2b74e](https://linux-hardware.org/?probe=7580d2b74e) | Jul 25, 2021 |
| Acer          | Aspire V7-582P              | [308aee8cb1](https://linux-hardware.org/?probe=308aee8cb1) | Jul 25, 2021 |
| Acer          | Aspire V7-582P              | [6ce43ddc17](https://linux-hardware.org/?probe=6ce43ddc17) | Jul 25, 2021 |
| HP            | ProBook 650 G5              | [d3851a242f](https://linux-hardware.org/?probe=d3851a242f) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | [534e1afff4](https://linux-hardware.org/?probe=534e1afff4) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | [1f1197a640](https://linux-hardware.org/?probe=1f1197a640) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | [ad6bb28669](https://linux-hardware.org/?probe=ad6bb28669) | Jul 24, 2021 |
| HP            | EliteBook 820 G1            | [7ed4e2945c](https://linux-hardware.org/?probe=7ed4e2945c) | Jul 24, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [7fa1d5f6ab](https://linux-hardware.org/?probe=7fa1d5f6ab) | Jul 24, 2021 |
| Sony          | VPCEJ1L1E                   | [ae5dc242e4](https://linux-hardware.org/?probe=ae5dc242e4) | Jul 24, 2021 |
| Dell          | Inspiron N5010              | [d83e888f43](https://linux-hardware.org/?probe=d83e888f43) | Jul 24, 2021 |
| Dell          | XPS 15 7590                 | [df948c9a32](https://linux-hardware.org/?probe=df948c9a32) | Jul 23, 2021 |
| Dell          | XPS 15 7590                 | [80e7ec8f3f](https://linux-hardware.org/?probe=80e7ec8f3f) | Jul 23, 2021 |
| DNS           | Unknown                     | [fce7ca77f0](https://linux-hardware.org/?probe=fce7ca77f0) | Jul 23, 2021 |
| roda compu... | DS13                        | [ff3f6c2d6f](https://linux-hardware.org/?probe=ff3f6c2d6f) | Jul 23, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [d058df63d2](https://linux-hardware.org/?probe=d058df63d2) | Jul 23, 2021 |
| Dell          | Inspiron N5010              | [cca8fb82b1](https://linux-hardware.org/?probe=cca8fb82b1) | Jul 23, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [0dc7d14a68](https://linux-hardware.org/?probe=0dc7d14a68) | Jul 23, 2021 |
| HP            | 14                          | [29af89c91b](https://linux-hardware.org/?probe=29af89c91b) | Jul 23, 2021 |
| Medion        | E6226                       | [aee8a0be6f](https://linux-hardware.org/?probe=aee8a0be6f) | Jul 22, 2021 |
| Lenovo        | Unknown                     | [425e6aa6da](https://linux-hardware.org/?probe=425e6aa6da) | Jul 22, 2021 |
| Dell          | Inspiron N5010              | [4f3af1bdc2](https://linux-hardware.org/?probe=4f3af1bdc2) | Jul 22, 2021 |
| Dell          | Latitude 3410               | [4058065b38](https://linux-hardware.org/?probe=4058065b38) | Jul 21, 2021 |
| HP            | EliteBook 820 G1            | [2682c21b3a](https://linux-hardware.org/?probe=2682c21b3a) | Jul 21, 2021 |
| Lenovo        | G485                        | [0810c75be3](https://linux-hardware.org/?probe=0810c75be3) | Jul 21, 2021 |
| ASUSTek       | K52JT                       | [243cac5745](https://linux-hardware.org/?probe=243cac5745) | Jul 20, 2021 |
| HP            | ProBook 650 G5              | [0880c07a99](https://linux-hardware.org/?probe=0880c07a99) | Jul 20, 2021 |
| Lenovo        | G485                        | [aa805dfe8d](https://linux-hardware.org/?probe=aa805dfe8d) | Jul 20, 2021 |
| Apple         | MacBookPro12,1              | [20eed1cd12](https://linux-hardware.org/?probe=20eed1cd12) | Jul 20, 2021 |
| HP            | 14                          | [345be169ae](https://linux-hardware.org/?probe=345be169ae) | Jul 20, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [30a28565e9](https://linux-hardware.org/?probe=30a28565e9) | Jul 19, 2021 |
| HP            | ProBook 650 G1              | [1a9549039b](https://linux-hardware.org/?probe=1a9549039b) | Jul 19, 2021 |
| HP            | ProBook 650 G1              | [576d7b9871](https://linux-hardware.org/?probe=576d7b9871) | Jul 19, 2021 |
| Lenovo        | G500 20236                  | [e9ecd52e2c](https://linux-hardware.org/?probe=e9ecd52e2c) | Jul 18, 2021 |
| Apple         | MacBook8,1                  | [f7cabbb5fe](https://linux-hardware.org/?probe=f7cabbb5fe) | Jul 18, 2021 |
| Dell          | Latitude E6520              | [67d96eeb17](https://linux-hardware.org/?probe=67d96eeb17) | Jul 17, 2021 |
| HUAWEI        | HLYL-WXX9                   | [a44ab9f722](https://linux-hardware.org/?probe=a44ab9f722) | Jul 17, 2021 |
| ASUSTek       | K52Jr                       | [e8672d5819](https://linux-hardware.org/?probe=e8672d5819) | Jul 17, 2021 |
| Dell          | G3 3500                     | [12e1eb1ce7](https://linux-hardware.org/?probe=12e1eb1ce7) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| Dell          | XPS 15 9550                 | [1183f6f39b](https://linux-hardware.org/?probe=1183f6f39b) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d1105aa53f](https://linux-hardware.org/?probe=d1105aa53f) | Jul 16, 2021 |
| Dell          | Inspiron 3793               | [a87acc7896](https://linux-hardware.org/?probe=a87acc7896) | Jul 15, 2021 |
| ASUSTek       | X751LJ                      | [fcbeeff3a2](https://linux-hardware.org/?probe=fcbeeff3a2) | Jul 15, 2021 |
| ASUSTek       | X751SA                      | [8bde6f919c](https://linux-hardware.org/?probe=8bde6f919c) | Jul 15, 2021 |
| Dell          | Inspiron 15-3567            | [1b1591901f](https://linux-hardware.org/?probe=1b1591901f) | Jul 15, 2021 |
| Samsung       | 800G5H/800G5S               | [43c5271ff4](https://linux-hardware.org/?probe=43c5271ff4) | Jul 15, 2021 |
| HP            | Laptop 15-bs1xx             | [3d1c92e425](https://linux-hardware.org/?probe=3d1c92e425) | Jul 15, 2021 |
| System76      | Serval WS                   | [9c6e77076c](https://linux-hardware.org/?probe=9c6e77076c) | Jul 15, 2021 |
| Acer          | Swift SF114-34              | [a27de08174](https://linux-hardware.org/?probe=a27de08174) | Jul 15, 2021 |
| Dell          | XPS 13 9310                 | [96ce85594c](https://linux-hardware.org/?probe=96ce85594c) | Jul 14, 2021 |
| Timi          | A35S                        | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| Dell          | XPS 13 9310                 | [8e96e56dc3](https://linux-hardware.org/?probe=8e96e56dc3) | Jul 14, 2021 |
| Lenovo        | ThinkPad E14 20RBS7WC00     | [4d34393d9f](https://linux-hardware.org/?probe=4d34393d9f) | Jul 14, 2021 |
| Dell          | Latitude 5300               | [c1bf5424e4](https://linux-hardware.org/?probe=c1bf5424e4) | Jul 14, 2021 |
| HP            | ProBook 4530s               | [603ec2d5c9](https://linux-hardware.org/?probe=603ec2d5c9) | Jul 14, 2021 |
| HP            | EliteBook 8560p             | [41a7775b52](https://linux-hardware.org/?probe=41a7775b52) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Latitude E7440              | [e4d6f94ccb](https://linux-hardware.org/?probe=e4d6f94ccb) | Jul 13, 2021 |
| HP            | EliteBook 8460p             | [870b9bdfca](https://linux-hardware.org/?probe=870b9bdfca) | Jul 13, 2021 |
| Dell          | Inspiron 7501               | [f63afb571d](https://linux-hardware.org/?probe=f63afb571d) | Jul 13, 2021 |
| Acer          | AS5750G                     | [5059f64428](https://linux-hardware.org/?probe=5059f64428) | Jul 13, 2021 |
| Dell          | Inspiron 7501               | [4ad9830a25](https://linux-hardware.org/?probe=4ad9830a25) | Jul 12, 2021 |
| Lenovo        | ThinkPad W540 20BHS2LM02    | [6d00312e5e](https://linux-hardware.org/?probe=6d00312e5e) | Jul 12, 2021 |
| Acer          | Aspire E1-571               | [a32287126e](https://linux-hardware.org/?probe=a32287126e) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Chuwi         | HeroBook Pro+               | [ab9af242f2](https://linux-hardware.org/?probe=ab9af242f2) | Jul 12, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [3cf8675c2d](https://linux-hardware.org/?probe=3cf8675c2d) | Jul 12, 2021 |
| Fujitsu       | LIFEBOOK A556               | [076bf0f706](https://linux-hardware.org/?probe=076bf0f706) | Jul 11, 2021 |
| Dell          | XPS 15 9560                 | [62a4b43bb7](https://linux-hardware.org/?probe=62a4b43bb7) | Jul 11, 2021 |
| Apple         | MacBookAir6,2               | [f00c776e5d](https://linux-hardware.org/?probe=f00c776e5d) | Jul 11, 2021 |
| Dell          | Inspiron 15-3567            | [e76377da85](https://linux-hardware.org/?probe=e76377da85) | Jul 11, 2021 |
| Lenovo        | 3000 N200 0769ESG           | [17edd23abd](https://linux-hardware.org/?probe=17edd23abd) | Jul 10, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [dc0cd1d174](https://linux-hardware.org/?probe=dc0cd1d174) | Jul 10, 2021 |
| Acer          | Aspire V3-771               | [9371836e3e](https://linux-hardware.org/?probe=9371836e3e) | Jul 10, 2021 |
| Acer          | Aspire E1-531               | [064d13dec1](https://linux-hardware.org/?probe=064d13dec1) | Jul 10, 2021 |
| Medion        | Akoya E6416 MD99610         | [fa99920590](https://linux-hardware.org/?probe=fa99920590) | Jul 10, 2021 |
| Medion        | Akoya E6416 MD99610         | [a1a9ad6ac8](https://linux-hardware.org/?probe=a1a9ad6ac8) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6C... | [516709833b](https://linux-hardware.org/?probe=516709833b) | Jul 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c006002427](https://linux-hardware.org/?probe=c006002427) | Jul 09, 2021 |
| Dell          | Vostro 5470                 | [aff224171e](https://linux-hardware.org/?probe=aff224171e) | Jul 09, 2021 |
| Wiltronic     | IVIEW Maximus Pro           | [94e424774a](https://linux-hardware.org/?probe=94e424774a) | Jul 09, 2021 |
| ASUSTek       | X751SA                      | [79ebf739a1](https://linux-hardware.org/?probe=79ebf739a1) | Jul 08, 2021 |
| HP            | EliteBook 840 G3            | [950a407dff](https://linux-hardware.org/?probe=950a407dff) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK E752               | [71f2a9ae1f](https://linux-hardware.org/?probe=71f2a9ae1f) | Jul 08, 2021 |
| Lenovo        | G500 20236                  | [cdc6087931](https://linux-hardware.org/?probe=cdc6087931) | Jul 08, 2021 |
| Lenovo        | G500 20236                  | [905b293afa](https://linux-hardware.org/?probe=905b293afa) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | [6aa95f6599](https://linux-hardware.org/?probe=6aa95f6599) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | [2a2e03aaa8](https://linux-hardware.org/?probe=2a2e03aaa8) | Jul 08, 2021 |
| Unknown       | 1.0                         | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| ASUSTek       | X751SA                      | [fa4822db25](https://linux-hardware.org/?probe=fa4822db25) | Jul 08, 2021 |
| HP            | Laptop 14s-fq1xxx           | [f05a96bdac](https://linux-hardware.org/?probe=f05a96bdac) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3980... | [99729a0a68](https://linux-hardware.org/?probe=99729a0a68) | Jul 07, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [de0ab0b7c2](https://linux-hardware.org/?probe=de0ab0b7c2) | Jul 07, 2021 |
| Alienware     | M17xR4                      | [584079f0f6](https://linux-hardware.org/?probe=584079f0f6) | Jul 07, 2021 |
| Dell          | G7 7700                     | [6fc41408bf](https://linux-hardware.org/?probe=6fc41408bf) | Jul 07, 2021 |
| Dell          | Inspiron 3501               | [64371c73a0](https://linux-hardware.org/?probe=64371c73a0) | Jul 07, 2021 |
| ASUSTek       | X551CAP                     | [bc8df07ff7](https://linux-hardware.org/?probe=bc8df07ff7) | Jul 06, 2021 |
| Dell          | Inspiron 5482               | [0d8c9adb49](https://linux-hardware.org/?probe=0d8c9adb49) | Jul 06, 2021 |
| Dell          | Latitude 5511               | [cac1bff4a1](https://linux-hardware.org/?probe=cac1bff4a1) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [0b10aaa23c](https://linux-hardware.org/?probe=0b10aaa23c) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [6c81e98dd0](https://linux-hardware.org/?probe=6c81e98dd0) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1b38515a6a](https://linux-hardware.org/?probe=1b38515a6a) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [0033ea368f](https://linux-hardware.org/?probe=0033ea368f) | Jul 06, 2021 |
| ASUSTek       | X551CAP                     | [c3bed169fd](https://linux-hardware.org/?probe=c3bed169fd) | Jul 06, 2021 |
| Dell          | Inspiron 5521               | [f2ab6f6a6f](https://linux-hardware.org/?probe=f2ab6f6a6f) | Jul 05, 2021 |
| Dell          | Inspiron 5521               | [260f6cb321](https://linux-hardware.org/?probe=260f6cb321) | Jul 05, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [92cfe5edd3](https://linux-hardware.org/?probe=92cfe5edd3) | Jul 05, 2021 |
| Dell          | Latitude E6320              | [dc31c90631](https://linux-hardware.org/?probe=dc31c90631) | Jul 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [621494a6e3](https://linux-hardware.org/?probe=621494a6e3) | Jul 05, 2021 |
| Packard Be... | EasyNote LS11HR             | [09dbdc286a](https://linux-hardware.org/?probe=09dbdc286a) | Jul 05, 2021 |
| Dell          | Latitude E5520              | [11a20a01eb](https://linux-hardware.org/?probe=11a20a01eb) | Jul 05, 2021 |
| ASUSTek       | X751SA                      | [98d8d8a1ca](https://linux-hardware.org/?probe=98d8d8a1ca) | Jul 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [94e917d395](https://linux-hardware.org/?probe=94e917d395) | Jul 04, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [867e24050a](https://linux-hardware.org/?probe=867e24050a) | Jul 04, 2021 |
| HP            | Compaq 510                  | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| Dell          | Inspiron 5593               | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| Dell          | Latitude E6400              | [18d5b00f71](https://linux-hardware.org/?probe=18d5b00f71) | Jul 03, 2021 |
| Dell          | Latitude 7490               | [c669795b35](https://linux-hardware.org/?probe=c669795b35) | Jul 03, 2021 |
| Chuwi         | HeroBook Pro+               | [bbd1ce59fa](https://linux-hardware.org/?probe=bbd1ce59fa) | Jul 03, 2021 |
| Dell          | Latitude E6430              | [43100da49e](https://linux-hardware.org/?probe=43100da49e) | Jul 02, 2021 |
| Dell          | Inspiron 1750               | [2ff81df67a](https://linux-hardware.org/?probe=2ff81df67a) | Jul 02, 2021 |
| Toshiba       | QOSMIO X70-B                | [dcec6c2c5f](https://linux-hardware.org/?probe=dcec6c2c5f) | Jul 02, 2021 |
| HP            | Stream Laptop 11-ak0xxx     | [f0de8a11c7](https://linux-hardware.org/?probe=f0de8a11c7) | Jul 02, 2021 |
| Sony          | VGN-FE880E                  | [920adf56ec](https://linux-hardware.org/?probe=920adf56ec) | Jul 02, 2021 |
| Sony          | VGN-FE880E                  | [6ae2ef9b19](https://linux-hardware.org/?probe=6ae2ef9b19) | Jul 02, 2021 |
| HP            | ProBook 430 G3              | [36176e3082](https://linux-hardware.org/?probe=36176e3082) | Jul 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [0dd8596f55](https://linux-hardware.org/?probe=0dd8596f55) | Jul 01, 2021 |
| Acer          | Aspire ES1-572              | [4e808a5437](https://linux-hardware.org/?probe=4e808a5437) | Jul 01, 2021 |
| Timi          | TM1701                      | [fe9f90644b](https://linux-hardware.org/?probe=fe9f90644b) | Jul 01, 2021 |
| HP            | 620                         | [a1ca12ac2c](https://linux-hardware.org/?probe=a1ca12ac2c) | Jul 01, 2021 |
| Dell          | Studio 1735                 | [2ed92032e0](https://linux-hardware.org/?probe=2ed92032e0) | Jul 01, 2021 |
| HP            | ProBook 430 G3              | [c7dfa113bc](https://linux-hardware.org/?probe=c7dfa113bc) | Jul 01, 2021 |
| HP            | EliteBook 8460p             | [f95f9de725](https://linux-hardware.org/?probe=f95f9de725) | Jul 01, 2021 |
| HP            | EliteBook 8460p             | [e752d2b1b7](https://linux-hardware.org/?probe=e752d2b1b7) | Jul 01, 2021 |
| HP            | EliteBook 840 G2            | [1c7ba3c173](https://linux-hardware.org/?probe=1c7ba3c173) | Jul 01, 2021 |
| HP            | EliteBook 8570w             | [57d8d9da44](https://linux-hardware.org/?probe=57d8d9da44) | Jun 30, 2021 |
| Dell          | Inspiron 7472               | [0624b57fad](https://linux-hardware.org/?probe=0624b57fad) | Jun 30, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3ec309cb24](https://linux-hardware.org/?probe=3ec309cb24) | Jun 30, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [618305c432](https://linux-hardware.org/?probe=618305c432) | Jun 30, 2021 |
| HP            | Laptop 15-dw1xxx            | [fa67031341](https://linux-hardware.org/?probe=fa67031341) | Jun 29, 2021 |
| HP            | Notebook                    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | Notebook                    | [510eaefd82](https://linux-hardware.org/?probe=510eaefd82) | Jun 29, 2021 |
| HP            | ENVY Laptop 17m-ch0xxx      | [a310f33226](https://linux-hardware.org/?probe=a310f33226) | Jun 29, 2021 |
| Timi          | Mi Laptop Pro 15 2020       | [6632675d89](https://linux-hardware.org/?probe=6632675d89) | Jun 29, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [afce0a6d68](https://linux-hardware.org/?probe=afce0a6d68) | Jun 29, 2021 |
| Acer          | Aspire V3-771               | [44ea4016b6](https://linux-hardware.org/?probe=44ea4016b6) | Jun 29, 2021 |
| Acer          | Aspire V3-771               | [3f2438194e](https://linux-hardware.org/?probe=3f2438194e) | Jun 29, 2021 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [a26ce90876](https://linux-hardware.org/?probe=a26ce90876) | Jun 29, 2021 |
| Wiltronic     | IVIEW Maximus Pro           | [92570b133c](https://linux-hardware.org/?probe=92570b133c) | Jun 29, 2021 |
| HP            | Pavilion dv6                | [c0e15bcf06](https://linux-hardware.org/?probe=c0e15bcf06) | Jun 27, 2021 |
| Acer          | TravelMate P653-M           | [f8509314e3](https://linux-hardware.org/?probe=f8509314e3) | Jun 27, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [5c56f0fc2f](https://linux-hardware.org/?probe=5c56f0fc2f) | Jun 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| HP            | ProBook 440 G5              | [d7bcf08f6a](https://linux-hardware.org/?probe=d7bcf08f6a) | Jun 26, 2021 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [fa17f630fc](https://linux-hardware.org/?probe=fa17f630fc) | Jun 26, 2021 |
| HP            | ProBook 440 G4              | [730c184b2b](https://linux-hardware.org/?probe=730c184b2b) | Jun 26, 2021 |
| Dell          | Inspiron MM061              | [b28ac0c857](https://linux-hardware.org/?probe=b28ac0c857) | Jun 26, 2021 |
| HP            | EliteBook 8460p             | [5808532dbd](https://linux-hardware.org/?probe=5808532dbd) | Jun 26, 2021 |
| Dell          | G3 3590                     | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| HP            | Laptop 15s-eq1xxx           | [d1d2e34e3c](https://linux-hardware.org/?probe=d1d2e34e3c) | Jun 25, 2021 |
| Lenovo        | ThinkPad P73 20QR0024GE     | [16b2f5dcfc](https://linux-hardware.org/?probe=16b2f5dcfc) | Jun 25, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [71134cd640](https://linux-hardware.org/?probe=71134cd640) | Jun 25, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [7c679b05c3](https://linux-hardware.org/?probe=7c679b05c3) | Jun 25, 2021 |
| Teclast       | F7 Plus                     | [a11823af5a](https://linux-hardware.org/?probe=a11823af5a) | Jun 24, 2021 |
| Dell          | Latitude E6420              | [68f21f9b57](https://linux-hardware.org/?probe=68f21f9b57) | Jun 24, 2021 |
| Medion        | E6429 MD60812               | [8f8daf18b9](https://linux-hardware.org/?probe=8f8daf18b9) | Jun 24, 2021 |
| HP            | 245 G6                      | [7f8e4b050a](https://linux-hardware.org/?probe=7f8e4b050a) | Jun 24, 2021 |
| ASUSTek       | E402SA                      | [6e79fb94aa](https://linux-hardware.org/?probe=6e79fb94aa) | Jun 24, 2021 |
| Dell          | Latitude 5511               | [10434415d8](https://linux-hardware.org/?probe=10434415d8) | Jun 24, 2021 |
| HP            | Notebook                    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| Dell          | Latitude E5540              | [a240b57157](https://linux-hardware.org/?probe=a240b57157) | Jun 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [7804268ecf](https://linux-hardware.org/?probe=7804268ecf) | Jun 23, 2021 |
| HP            | Pavilion dv6700             | [f1d9fcd165](https://linux-hardware.org/?probe=f1d9fcd165) | Jun 23, 2021 |
| HP            | EliteBook 8460p             | [463c88f144](https://linux-hardware.org/?probe=463c88f144) | Jun 23, 2021 |
| Acer          | Extensa 5635Z               | [8c9260d570](https://linux-hardware.org/?probe=8c9260d570) | Jun 23, 2021 |
| Dell          | Vostro 5581                 | [5e0ea603d3](https://linux-hardware.org/?probe=5e0ea603d3) | Jun 23, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f52276d111](https://linux-hardware.org/?probe=f52276d111) | Jun 22, 2021 |
| Maibenben     | MaiBook S                   | [a6e045f815](https://linux-hardware.org/?probe=a6e045f815) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| Dell          | Latitude 5511               | [6625368d80](https://linux-hardware.org/?probe=6625368d80) | Jun 21, 2021 |
| Positivo      | W940SU2                     | [7baff31673](https://linux-hardware.org/?probe=7baff31673) | Jun 21, 2021 |
| HP            | Laptop 17-ak0xx             | [4ae96f3d68](https://linux-hardware.org/?probe=4ae96f3d68) | Jun 21, 2021 |
| Medion        | E6429 MD60812               | [05db194f3f](https://linux-hardware.org/?probe=05db194f3f) | Jun 21, 2021 |
| Dell          | Vostro 5581                 | [bd7fdd93ec](https://linux-hardware.org/?probe=bd7fdd93ec) | Jun 21, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ba24de57b3](https://linux-hardware.org/?probe=ba24de57b3) | Jun 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [08c40500a8](https://linux-hardware.org/?probe=08c40500a8) | Jun 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [550a41e850](https://linux-hardware.org/?probe=550a41e850) | Jun 21, 2021 |
| ASUSTek       | X550LB                      | [81070e651b](https://linux-hardware.org/?probe=81070e651b) | Jun 21, 2021 |
| Lenovo        | ThinkPad X230 23255NG       | [e8196c8861](https://linux-hardware.org/?probe=e8196c8861) | Jun 21, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ac12b3d63e](https://linux-hardware.org/?probe=ac12b3d63e) | Jun 21, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [3f07752a76](https://linux-hardware.org/?probe=3f07752a76) | Jun 20, 2021 |
| Positivo      | CHT12CP                     | [a563fa0660](https://linux-hardware.org/?probe=a563fa0660) | Jun 20, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [a3b81cc44c](https://linux-hardware.org/?probe=a3b81cc44c) | Jun 20, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [6cd85599cd](https://linux-hardware.org/?probe=6cd85599cd) | Jun 20, 2021 |
| Pegatron      | H36Y                        | [9209a16c5c](https://linux-hardware.org/?probe=9209a16c5c) | Jun 20, 2021 |
| System76      | Serval WS serw8-17g         | [913f491e05](https://linux-hardware.org/?probe=913f491e05) | Jun 20, 2021 |
| HP            | Laptop 14-dq1xxx            | [24e2ca432c](https://linux-hardware.org/?probe=24e2ca432c) | Jun 19, 2021 |
| Dell          | Latitude E5570              | [b4bd39cf38](https://linux-hardware.org/?probe=b4bd39cf38) | Jun 19, 2021 |
| Dell          | Precision 5540              | [399b3e61e0](https://linux-hardware.org/?probe=399b3e61e0) | Jun 19, 2021 |
| HP            | Notebook                    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| HP            | 18-5600br                   | [d0583b92ed](https://linux-hardware.org/?probe=d0583b92ed) | Jun 19, 2021 |
| HP            | 18-5600br                   | [cd3657d994](https://linux-hardware.org/?probe=cd3657d994) | Jun 19, 2021 |
| HP            | 18-5600br                   | [cae1aa1394](https://linux-hardware.org/?probe=cae1aa1394) | Jun 18, 2021 |
| HP            | 18-5600br                   | [e3f995175a](https://linux-hardware.org/?probe=e3f995175a) | Jun 18, 2021 |
| Dell          | Latitude E6420              | [c9cefa3aea](https://linux-hardware.org/?probe=c9cefa3aea) | Jun 18, 2021 |
| Schenker      | XMG CORE 17(M20, GTX 165... | [9445d67978](https://linux-hardware.org/?probe=9445d67978) | Jun 18, 2021 |
| Lenovo        | ThinkPad L580 20LXS6NE02    | [d9a2077c08](https://linux-hardware.org/?probe=d9a2077c08) | Jun 18, 2021 |
| Dell          | Latitude XT3                | [1c523898cb](https://linux-hardware.org/?probe=1c523898cb) | Jun 18, 2021 |
| Dell          | Latitude XT3                | [80e1b1d818](https://linux-hardware.org/?probe=80e1b1d818) | Jun 18, 2021 |
| HP            | EliteBook Folio 9470m       | [33fce68a70](https://linux-hardware.org/?probe=33fce68a70) | Jun 18, 2021 |
| Dell          | XPS 15 7590                 | [11daeeac47](https://linux-hardware.org/?probe=11daeeac47) | Jun 18, 2021 |
| HP            | Pavilion Laptop 15-cc6xx    | [b0d1052f9f](https://linux-hardware.org/?probe=b0d1052f9f) | Jun 17, 2021 |
| Lenovo        | IdeaPad Flex 15 20309       | [7a60f78b32](https://linux-hardware.org/?probe=7a60f78b32) | Jun 17, 2021 |
| Acer          | Aspire A715-75G             | [32ef787520](https://linux-hardware.org/?probe=32ef787520) | Jun 17, 2021 |
| Dell          | G3 3590                     | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [097a4a8f7c](https://linux-hardware.org/?probe=097a4a8f7c) | Jun 16, 2021 |
| Acer          | Aspire A715-75G             | [886132fd6a](https://linux-hardware.org/?probe=886132fd6a) | Jun 16, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [fff555363c](https://linux-hardware.org/?probe=fff555363c) | Jun 16, 2021 |
| HP            | EliteBook 725 G3            | [f57f7d1e53](https://linux-hardware.org/?probe=f57f7d1e53) | Jun 16, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9045745027](https://linux-hardware.org/?probe=9045745027) | Jun 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [ab0934d142](https://linux-hardware.org/?probe=ab0934d142) | Jun 15, 2021 |
| Lenovo        | BS145-15IIL 82HB            | [e1e37c4609](https://linux-hardware.org/?probe=e1e37c4609) | Jun 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [27be88c747](https://linux-hardware.org/?probe=27be88c747) | Jun 14, 2021 |
| Dell          | Vostro 1220                 | [c951207d24](https://linux-hardware.org/?probe=c951207d24) | Jun 14, 2021 |
| HP            | 255 G7 Notebook PC          | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E590 20NB0029UK    | [073912d946](https://linux-hardware.org/?probe=073912d946) | Jun 14, 2021 |
| Dell          | Latitude 3350               | [7fe0552d03](https://linux-hardware.org/?probe=7fe0552d03) | Jun 14, 2021 |
| HP            | 18-5600br                   | [2fca89986a](https://linux-hardware.org/?probe=2fca89986a) | Jun 13, 2021 |
| Dell          | Studio 1735                 | [6cd1b25005](https://linux-hardware.org/?probe=6cd1b25005) | Jun 13, 2021 |
| VINGA         | Iron S140                   | [24d0a16acd](https://linux-hardware.org/?probe=24d0a16acd) | Jun 13, 2021 |
| HP            | Notebook                    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8b7af4e6fa](https://linux-hardware.org/?probe=8b7af4e6fa) | Jun 13, 2021 |
| Acer          | Aspire A515-44              | [611dfe93f6](https://linux-hardware.org/?probe=611dfe93f6) | Jun 12, 2021 |
| Timi          | TM1703                      | [61a3e61fd2](https://linux-hardware.org/?probe=61a3e61fd2) | Jun 12, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [6c64f10207](https://linux-hardware.org/?probe=6c64f10207) | Jun 12, 2021 |
| Alienware     | M17xR4                      | [ea7685d41d](https://linux-hardware.org/?probe=ea7685d41d) | Jun 12, 2021 |
| UNOWHY        | Y13G002S4EI                 | [805e3de988](https://linux-hardware.org/?probe=805e3de988) | Jun 11, 2021 |
| Dell          | Inspiron 3480               | [5e9614f03e](https://linux-hardware.org/?probe=5e9614f03e) | Jun 11, 2021 |
| Chuwi         | HeroBook Pro+               | [978d937d24](https://linux-hardware.org/?probe=978d937d24) | Jun 11, 2021 |
| Lenovo        | G50-80 80L0                 | [e13e5ed99e](https://linux-hardware.org/?probe=e13e5ed99e) | Jun 11, 2021 |
| Dell          | Precision 5540              | [b21ffd09ff](https://linux-hardware.org/?probe=b21ffd09ff) | Jun 11, 2021 |
| ASUSTek       | X550LD                      | [aea5a6b230](https://linux-hardware.org/?probe=aea5a6b230) | Jun 10, 2021 |
| Acer          | AS5750G                     | [29a60b38c7](https://linux-hardware.org/?probe=29a60b38c7) | Jun 10, 2021 |
| Dell          | XPS 15 9500                 | [fa7bfd58f6](https://linux-hardware.org/?probe=fa7bfd58f6) | Jun 10, 2021 |
| Lenovo        | ThinkPad T480s 20L7001PF... | [b54604a23d](https://linux-hardware.org/?probe=b54604a23d) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | [22e9ce0306](https://linux-hardware.org/?probe=22e9ce0306) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | [4bc5bdf702](https://linux-hardware.org/?probe=4bc5bdf702) | Jun 10, 2021 |
| Acer          | Aspire A515-51G             | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| Acer          | Aspire ES1-512              | [ca026e3930](https://linux-hardware.org/?probe=ca026e3930) | Jun 09, 2021 |
| Fujitsu       | STYLISTIC Q702              | [7607b3bb86](https://linux-hardware.org/?probe=7607b3bb86) | Jun 09, 2021 |
| Dell          | XPS 15 7590                 | [03514539b0](https://linux-hardware.org/?probe=03514539b0) | Jun 09, 2021 |
| MSI           | GS63 Stealth 8RE            | [a098121a4b](https://linux-hardware.org/?probe=a098121a4b) | Jun 09, 2021 |
| Acer          | Aspire A517-51P             | [0d9f4bfb3f](https://linux-hardware.org/?probe=0d9f4bfb3f) | Jun 08, 2021 |
| Acer          | Aspire V5-573G              | [4f2c1d3cf1](https://linux-hardware.org/?probe=4f2c1d3cf1) | Jun 08, 2021 |
| HP            | Pavilion dv5                | [a3ec72db59](https://linux-hardware.org/?probe=a3ec72db59) | Jun 08, 2021 |
| ASUSTek       | F50Z                        | [cf099f4a72](https://linux-hardware.org/?probe=cf099f4a72) | Jun 08, 2021 |
| Dell          | Inspiron 3480               | [c37379b181](https://linux-hardware.org/?probe=c37379b181) | Jun 08, 2021 |
| Dell          | Latitude E7440              | [5f0d57018e](https://linux-hardware.org/?probe=5f0d57018e) | Jun 07, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [7c843291b5](https://linux-hardware.org/?probe=7c843291b5) | Jun 07, 2021 |
| Dell          | Inspiron N5110              | [81034d3717](https://linux-hardware.org/?probe=81034d3717) | Jun 07, 2021 |
| Lenovo        | V14-IIL 82C4                | [5ccbd0c9dc](https://linux-hardware.org/?probe=5ccbd0c9dc) | Jun 07, 2021 |
| Lenovo        | V14-IIL 82C4                | [bf27f62c50](https://linux-hardware.org/?probe=bf27f62c50) | Jun 07, 2021 |
| Lenovo        | 100e 2nd Gen 82GJ           | [ce0d33750c](https://linux-hardware.org/?probe=ce0d33750c) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK S751               | [8cf5dc5f75](https://linux-hardware.org/?probe=8cf5dc5f75) | Jun 06, 2021 |
| Apple         | MacBookPro10,1              | [4081189cda](https://linux-hardware.org/?probe=4081189cda) | Jun 06, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [e192001666](https://linux-hardware.org/?probe=e192001666) | Jun 06, 2021 |
| ASUSTek       | G72GX                       | [9445bda61c](https://linux-hardware.org/?probe=9445bda61c) | Jun 05, 2021 |
| Lenovo        | ThinkPad T61 6463WCH        | [7497f56037](https://linux-hardware.org/?probe=7497f56037) | Jun 05, 2021 |
| Acer          | Aspire 5742Z                | [89ae1206bb](https://linux-hardware.org/?probe=89ae1206bb) | Jun 05, 2021 |
| Fujitsu       | LIFEBOOK A530               | [f8d06e3e17](https://linux-hardware.org/?probe=f8d06e3e17) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f0133f78dc](https://linux-hardware.org/?probe=f0133f78dc) | Jun 04, 2021 |
| Acer          | Aspire ES1-512              | [fa65ebf8c6](https://linux-hardware.org/?probe=fa65ebf8c6) | Jun 04, 2021 |
| Dell          | Inspiron 3480               | [cf9db1ce7a](https://linux-hardware.org/?probe=cf9db1ce7a) | Jun 04, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [99de24cb78](https://linux-hardware.org/?probe=99de24cb78) | Jun 04, 2021 |
| Dell          | Inspiron 3505               | [fe512b6857](https://linux-hardware.org/?probe=fe512b6857) | Jun 04, 2021 |
| HP            | ProBook 4430s               | [46588303b9](https://linux-hardware.org/?probe=46588303b9) | Jun 03, 2021 |
| HP            | ProBook 4430s               | [53188205ea](https://linux-hardware.org/?probe=53188205ea) | Jun 03, 2021 |
| HP            | EliteBook 840 G1            | [7a364bc855](https://linux-hardware.org/?probe=7a364bc855) | Jun 03, 2021 |
| LG Electro... | 16Z90P-G.AA76G              | [7a64de799d](https://linux-hardware.org/?probe=7a64de799d) | Jun 03, 2021 |
| Toshiba       | PORTEGE Z930                | [4a95259edd](https://linux-hardware.org/?probe=4a95259edd) | Jun 03, 2021 |
| Dell          | Latitude 3350               | [abb4701070](https://linux-hardware.org/?probe=abb4701070) | Jun 03, 2021 |
| ASUSTek       | X550LB                      | [c5c49a53de](https://linux-hardware.org/?probe=c5c49a53de) | Jun 03, 2021 |
| HP            | Pavilion dv6                | [caa052636f](https://linux-hardware.org/?probe=caa052636f) | Jun 03, 2021 |
| HP            | Laptop 15s-eq1xxx           | [d53b1525ed](https://linux-hardware.org/?probe=d53b1525ed) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [ea28219e8a](https://linux-hardware.org/?probe=ea28219e8a) | Jun 02, 2021 |
| Dell          | Studio 1735                 | [b0485d3960](https://linux-hardware.org/?probe=b0485d3960) | Jun 02, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [8533dbc1de](https://linux-hardware.org/?probe=8533dbc1de) | Jun 02, 2021 |
| Dell          | Latitude 9520               | [10a4c770cf](https://linux-hardware.org/?probe=10a4c770cf) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [390085b056](https://linux-hardware.org/?probe=390085b056) | Jun 02, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [61b78ffc77](https://linux-hardware.org/?probe=61b78ffc77) | Jun 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0271a8fd47](https://linux-hardware.org/?probe=0271a8fd47) | Jun 02, 2021 |
| Dell          | Inspiron 3505               | [6efb3f85be](https://linux-hardware.org/?probe=6efb3f85be) | Jun 02, 2021 |
| HP            | ProBook 6560b               | [f9ee7c5367](https://linux-hardware.org/?probe=f9ee7c5367) | Jun 01, 2021 |
| HP            | ProBook 450 G6              | [6c241e0b82](https://linux-hardware.org/?probe=6c241e0b82) | Jun 01, 2021 |
| Dell          | Inspiron 5370               | [51235b00db](https://linux-hardware.org/?probe=51235b00db) | Jun 01, 2021 |
| HP            | ProBook 6560b               | [f2b70f9230](https://linux-hardware.org/?probe=f2b70f9230) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [36f36a1183](https://linux-hardware.org/?probe=36f36a1183) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Lenovo        | G50-80 80E5                 | [09cc2aed35](https://linux-hardware.org/?probe=09cc2aed35) | May 31, 2021 |
| Dell          | Latitude 3350               | [14584ee6c7](https://linux-hardware.org/?probe=14584ee6c7) | May 31, 2021 |
| HP            | ProBook 6560b               | [523614fee6](https://linux-hardware.org/?probe=523614fee6) | May 31, 2021 |
| HP            | Pavilion dv6                | [6ac306c0da](https://linux-hardware.org/?probe=6ac306c0da) | May 31, 2021 |
| Lenovo        | V560                        | [62053ae42b](https://linux-hardware.org/?probe=62053ae42b) | May 30, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [f8eb7b0f52](https://linux-hardware.org/?probe=f8eb7b0f52) | May 30, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [d7f2524297](https://linux-hardware.org/?probe=d7f2524297) | May 30, 2021 |
| HCL Infosy... | HCL ME Laptop               | [5c17f36c61](https://linux-hardware.org/?probe=5c17f36c61) | May 30, 2021 |
| Lenovo        | ThinkPad T420 42366Y0       | [74547808d3](https://linux-hardware.org/?probe=74547808d3) | May 30, 2021 |
| HUAWEI        | MACH-WX9                    | [9358c3afbf](https://linux-hardware.org/?probe=9358c3afbf) | May 29, 2021 |
| Dell          | Inspiron 3505               | [4157528079](https://linux-hardware.org/?probe=4157528079) | May 29, 2021 |
| Lenovo        | ThinkPad T420 42366Y0       | [d36582d3d6](https://linux-hardware.org/?probe=d36582d3d6) | May 29, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [e2d1740f3a](https://linux-hardware.org/?probe=e2d1740f3a) | May 28, 2021 |
| Acer          | Aspire A515-55              | [09499164b9](https://linux-hardware.org/?probe=09499164b9) | May 28, 2021 |
| ASUSTek       | X550LB                      | [21f1da73fd](https://linux-hardware.org/?probe=21f1da73fd) | May 28, 2021 |
| ASUSTek       | X550LB                      | [cc4245844a](https://linux-hardware.org/?probe=cc4245844a) | May 28, 2021 |
| Acer          | Aspire E5-553               | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| Samsung       | RF510/RF410/RF710           | [ee109d9097](https://linux-hardware.org/?probe=ee109d9097) | May 27, 2021 |
| Dell          | Latitude 5520               | [f9327e8bb8](https://linux-hardware.org/?probe=f9327e8bb8) | May 27, 2021 |
| Acer          | Aspire A515-55              | [3cfa12f511](https://linux-hardware.org/?probe=3cfa12f511) | May 27, 2021 |
| Alienware     | M17xR4                      | [d3da4ef72c](https://linux-hardware.org/?probe=d3da4ef72c) | May 27, 2021 |
| Alienware     | M17xR4                      | [f534e321eb](https://linux-hardware.org/?probe=f534e321eb) | May 27, 2021 |
| ASUSTek       | GL553VD                     | [5c45dfb686](https://linux-hardware.org/?probe=5c45dfb686) | May 26, 2021 |
| ASUSTek       | GL553VD                     | [5177972753](https://linux-hardware.org/?probe=5177972753) | May 26, 2021 |
| HP            | Laptop 15-dy2xxx            | [5ec38e0f3f](https://linux-hardware.org/?probe=5ec38e0f3f) | May 25, 2021 |
| Lenovo        | ThinkPad T410 2537Z2J       | [d86d3e8984](https://linux-hardware.org/?probe=d86d3e8984) | May 25, 2021 |
| Apple         | MacBookPro8,3               | [c34278c355](https://linux-hardware.org/?probe=c34278c355) | May 25, 2021 |
| Dell          | G7 7500                     | [89f41d7487](https://linux-hardware.org/?probe=89f41d7487) | May 25, 2021 |
| HP            | EliteBook 820 G2            | [f9ed2cd1c9](https://linux-hardware.org/?probe=f9ed2cd1c9) | May 25, 2021 |
| MSI           | GS60 2QE                    | [7ef8c79c08](https://linux-hardware.org/?probe=7ef8c79c08) | May 24, 2021 |
| Apple         | MacBookAir5,2               | [ec1abd9485](https://linux-hardware.org/?probe=ec1abd9485) | May 24, 2021 |
| Sony          | VGN-AR850E                  | [e17fe551fb](https://linux-hardware.org/?probe=e17fe551fb) | May 24, 2021 |
| MSI           | GS60 2QE                    | [1660ac34ec](https://linux-hardware.org/?probe=1660ac34ec) | May 24, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [f6856776e4](https://linux-hardware.org/?probe=f6856776e4) | May 24, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [08d0784b54](https://linux-hardware.org/?probe=08d0784b54) | May 24, 2021 |
| Lenovo        | G500 20236                  | [91cf490677](https://linux-hardware.org/?probe=91cf490677) | May 24, 2021 |
| Dell          | G5 5587                     | [65c1600593](https://linux-hardware.org/?probe=65c1600593) | May 24, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [2bbea8f317](https://linux-hardware.org/?probe=2bbea8f317) | May 24, 2021 |
| HUAWEI        | MACH-WX9                    | [1261bed89a](https://linux-hardware.org/?probe=1261bed89a) | May 24, 2021 |
| Acer          | TravelMate P215-53          | [dc89b4797f](https://linux-hardware.org/?probe=dc89b4797f) | May 24, 2021 |
| Acer          | Aspire one 1-431            | [db306fa1f7](https://linux-hardware.org/?probe=db306fa1f7) | May 24, 2021 |
| Dell          | Inspiron 1525               | [6fbef63c17](https://linux-hardware.org/?probe=6fbef63c17) | May 23, 2021 |
| Toshiba       | PORTEGE Z930                | [5169c2f96a](https://linux-hardware.org/?probe=5169c2f96a) | May 23, 2021 |
| Acer          | TravelMate P215-53          | [18ea2a888a](https://linux-hardware.org/?probe=18ea2a888a) | May 23, 2021 |
| System76      | Galago Pro                  | [7bc86eb366](https://linux-hardware.org/?probe=7bc86eb366) | May 23, 2021 |
| Dell          | XPS 13 9360                 | [97dbd7a2d0](https://linux-hardware.org/?probe=97dbd7a2d0) | May 23, 2021 |
| HUAWEI        | KLVL-WXX9                   | [8a8a2bded7](https://linux-hardware.org/?probe=8a8a2bded7) | May 23, 2021 |
| HP            | Pavilion dv5                | [97c2972e03](https://linux-hardware.org/?probe=97c2972e03) | May 22, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b3da27422d](https://linux-hardware.org/?probe=b3da27422d) | May 22, 2021 |
| Acer          | Swift SF314-59              | [c781b981de](https://linux-hardware.org/?probe=c781b981de) | May 22, 2021 |
| Unknown       | T3 MRD                      | [1c16d2db6c](https://linux-hardware.org/?probe=1c16d2db6c) | May 21, 2021 |
| Lenovo        | ThinkPad T61 6463WCH        | [e1b3b6e090](https://linux-hardware.org/?probe=e1b3b6e090) | May 21, 2021 |
| Sony          | VGN-NS21Z_S                 | [4c412bd16f](https://linux-hardware.org/?probe=4c412bd16f) | May 21, 2021 |
| Dell          | Latitude 5410               | [6b5502593e](https://linux-hardware.org/?probe=6b5502593e) | May 21, 2021 |
| HP            | Spectre Pro x360 G2         | [236efc033e](https://linux-hardware.org/?probe=236efc033e) | May 21, 2021 |
| Dell          | Precision 5530              | [a5c63380d6](https://linux-hardware.org/?probe=a5c63380d6) | May 21, 2021 |
| Razer         | Blade Stealth               | [274e57be67](https://linux-hardware.org/?probe=274e57be67) | May 21, 2021 |
| HP            | Pavilion Notebook           | [d63952115c](https://linux-hardware.org/?probe=d63952115c) | May 20, 2021 |
| HP            | 15                          | [814d85cf91](https://linux-hardware.org/?probe=814d85cf91) | May 20, 2021 |
| HP            | 350 G1                      | [949ae1ce88](https://linux-hardware.org/?probe=949ae1ce88) | May 20, 2021 |
| Dell          | XPS 15 7590                 | [6d6ff7b4d8](https://linux-hardware.org/?probe=6d6ff7b4d8) | May 20, 2021 |
| Fujitsu       | LIFEBOOK T730               | [f220f9ac45](https://linux-hardware.org/?probe=f220f9ac45) | May 20, 2021 |
| Dell          | Inspiron 3505               | [c973055db8](https://linux-hardware.org/?probe=c973055db8) | May 20, 2021 |
| HUAWEI        | MACH-WX9                    | [6331748487](https://linux-hardware.org/?probe=6331748487) | May 20, 2021 |
| Lenovo        | ThinkPad W510 4318CTO       | [ed2a5f47c6](https://linux-hardware.org/?probe=ed2a5f47c6) | May 20, 2021 |
| Acer          | Aspire A515-43              | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| HP            | ProBook 455 G7              | [30a5ddc9a4](https://linux-hardware.org/?probe=30a5ddc9a4) | May 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [013af3c5de](https://linux-hardware.org/?probe=013af3c5de) | May 19, 2021 |
| ASUSTek       | GL502VSK                    | [577af42985](https://linux-hardware.org/?probe=577af42985) | May 19, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [99d22d0422](https://linux-hardware.org/?probe=99d22d0422) | May 19, 2021 |
| HP            | Pavilion 15                 | [c689ad926b](https://linux-hardware.org/?probe=c689ad926b) | May 19, 2021 |
| ASUSTek       | T100HAN                     | [bb0d60af3d](https://linux-hardware.org/?probe=bb0d60af3d) | May 19, 2021 |
| Notebook      | PCX0DX                      | [4556010665](https://linux-hardware.org/?probe=4556010665) | May 18, 2021 |
| Toshiba       | PORTEGE Z930                | [3b82b0b360](https://linux-hardware.org/?probe=3b82b0b360) | May 18, 2021 |
| Toshiba       | PORTEGE Z930                | [e006b8bf83](https://linux-hardware.org/?probe=e006b8bf83) | May 18, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [12ffaaefb1](https://linux-hardware.org/?probe=12ffaaefb1) | May 18, 2021 |
| ASUSTek       | X550LB                      | [3dc677388a](https://linux-hardware.org/?probe=3dc677388a) | May 18, 2021 |
| Apple         | MacBook5,1                  | [1bfce84c69](https://linux-hardware.org/?probe=1bfce84c69) | May 17, 2021 |
| HP            | ProBook 450 G7              | [deb906b69f](https://linux-hardware.org/?probe=deb906b69f) | May 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7724221aba](https://linux-hardware.org/?probe=7724221aba) | May 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [0e9e4151e9](https://linux-hardware.org/?probe=0e9e4151e9) | May 17, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [ed92840007](https://linux-hardware.org/?probe=ed92840007) | May 17, 2021 |
| Fujitsu       | STYLISTIC Q702              | [6af6b1aa99](https://linux-hardware.org/?probe=6af6b1aa99) | May 17, 2021 |
| Acer          | Aspire E3-112               | [fed9ba4c7d](https://linux-hardware.org/?probe=fed9ba4c7d) | May 16, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [65a3c1a830](https://linux-hardware.org/?probe=65a3c1a830) | May 16, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [0c0dec114b](https://linux-hardware.org/?probe=0c0dec114b) | May 16, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [5c67466a7e](https://linux-hardware.org/?probe=5c67466a7e) | May 16, 2021 |
| Dell          | XPS M1530                   | [19be0f2492](https://linux-hardware.org/?probe=19be0f2492) | May 16, 2021 |
| Dell          | Precision 3551              | [a080388baa](https://linux-hardware.org/?probe=a080388baa) | May 16, 2021 |
| Dell          | Precision 3551              | [f9f9852b96](https://linux-hardware.org/?probe=f9f9852b96) | May 16, 2021 |
| Dell          | Latitude 5285               | [c5396b5734](https://linux-hardware.org/?probe=c5396b5734) | May 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [00a8ed533c](https://linux-hardware.org/?probe=00a8ed533c) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [14b8295348](https://linux-hardware.org/?probe=14b8295348) | May 15, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [30fa3fc2c7](https://linux-hardware.org/?probe=30fa3fc2c7) | May 15, 2021 |
| Dell          | Latitude 3350               | [f4e6b7cf7f](https://linux-hardware.org/?probe=f4e6b7cf7f) | May 15, 2021 |
| Positivo      | C14CR21TV                   | [8af930f7e1](https://linux-hardware.org/?probe=8af930f7e1) | May 15, 2021 |
| Lenovo        | G40-70 80GA                 | [619b20ccfb](https://linux-hardware.org/?probe=619b20ccfb) | May 15, 2021 |
| Lenovo        | G40-70 80GA                 | [c674fa597f](https://linux-hardware.org/?probe=c674fa597f) | May 15, 2021 |
| HP            | 1000                        | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP            | G62                         | [aec231d673](https://linux-hardware.org/?probe=aec231d673) | May 14, 2021 |
| Apple         | MacBookAir7,2               | [df405076a1](https://linux-hardware.org/?probe=df405076a1) | May 14, 2021 |
| MSI           | GF65 Thin 10SDR             | [fcbfa1c448](https://linux-hardware.org/?probe=fcbfa1c448) | May 14, 2021 |
| Sony          | VGN-AR51SU                  | [6d72715029](https://linux-hardware.org/?probe=6d72715029) | May 13, 2021 |
| Dell          | Latitude 3350               | [bb64b2df5c](https://linux-hardware.org/?probe=bb64b2df5c) | May 13, 2021 |
| HP            | ProBook 430 G1              | [20a2c142bf](https://linux-hardware.org/?probe=20a2c142bf) | May 13, 2021 |
| Insignia      | NS-P11W7100                 | [6bb54d0349](https://linux-hardware.org/?probe=6bb54d0349) | May 13, 2021 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | [9f56d64c9d](https://linux-hardware.org/?probe=9f56d64c9d) | May 13, 2021 |
| HP            | ProBook 450 G4              | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| HP            | 1000                        | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| HP            | 1000                        | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| MSI           | Prestige 15 A11SCS          | [f892f92e65](https://linux-hardware.org/?probe=f892f92e65) | May 12, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [ca2397cddf](https://linux-hardware.org/?probe=ca2397cddf) | May 12, 2021 |
| Dell          | Precision M4500             | [784b8e3db4](https://linux-hardware.org/?probe=784b8e3db4) | May 11, 2021 |
| HP            | EliteBook 850 G4            | [2502c3d7e7](https://linux-hardware.org/?probe=2502c3d7e7) | May 11, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [2543210bfd](https://linux-hardware.org/?probe=2543210bfd) | May 11, 2021 |
| Acer          | Swift SF114-32              | [09ca2a6a53](https://linux-hardware.org/?probe=09ca2a6a53) | May 10, 2021 |
| Apple         | MacBookPro8,3               | [0537199c9f](https://linux-hardware.org/?probe=0537199c9f) | May 10, 2021 |
| Sony          | VPCCW2S8E                   | [4398b323b3](https://linux-hardware.org/?probe=4398b323b3) | May 10, 2021 |
| Sony          | VPCCW2S8E                   | [eba79cc54f](https://linux-hardware.org/?probe=eba79cc54f) | May 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5ca33ceca6](https://linux-hardware.org/?probe=5ca33ceca6) | May 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [fc4143b244](https://linux-hardware.org/?probe=fc4143b244) | May 10, 2021 |
| Apple         | MacBookPro8,1               | [8afdfe2827](https://linux-hardware.org/?probe=8afdfe2827) | May 10, 2021 |
| Acer          | Aspire A315-33              | [b50018b47b](https://linux-hardware.org/?probe=b50018b47b) | May 09, 2021 |
| Dell          | Vostro 7500                 | [6041d49bff](https://linux-hardware.org/?probe=6041d49bff) | May 09, 2021 |
| Apple         | MacBookPro8,1               | [5da4e125b2](https://linux-hardware.org/?probe=5da4e125b2) | May 09, 2021 |
| Dell          | XPS 15 9500                 | [cf55e0e340](https://linux-hardware.org/?probe=cf55e0e340) | May 09, 2021 |
| Dell          | XPS 15 9500                 | [287b32a385](https://linux-hardware.org/?probe=287b32a385) | May 09, 2021 |
| HP            | Laptop 17-bs0xx             | [e6623d7b8e](https://linux-hardware.org/?probe=e6623d7b8e) | May 09, 2021 |
| Lenovo        | E41-25 81FS                 | [4ccf4659d4](https://linux-hardware.org/?probe=4ccf4659d4) | May 08, 2021 |
| Lenovo        | E41-25 81FS                 | [532af26481](https://linux-hardware.org/?probe=532af26481) | May 08, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [adfdb43f0b](https://linux-hardware.org/?probe=adfdb43f0b) | May 08, 2021 |
| MSI           | GS66 Stealth 10SE           | [2869638c1b](https://linux-hardware.org/?probe=2869638c1b) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9d937a5244](https://linux-hardware.org/?probe=9d937a5244) | May 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [089fa466bc](https://linux-hardware.org/?probe=089fa466bc) | May 07, 2021 |
| HP            | Laptop 17-bs0xx             | [86f4c24f8f](https://linux-hardware.org/?probe=86f4c24f8f) | May 07, 2021 |
| ASUSTek       | K52F                        | [871f4c23c5](https://linux-hardware.org/?probe=871f4c23c5) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [34b008d2a3](https://linux-hardware.org/?probe=34b008d2a3) | May 06, 2021 |
| Samsung       | RC530/RC730                 | [479ca4a221](https://linux-hardware.org/?probe=479ca4a221) | May 06, 2021 |
| Samsung       | RC530/RC730                 | [96541e6169](https://linux-hardware.org/?probe=96541e6169) | May 06, 2021 |
| HP            | ZBook 15                    | [ccdf2eebed](https://linux-hardware.org/?probe=ccdf2eebed) | May 06, 2021 |
| HP            | ZBook 15                    | [702b924ad3](https://linux-hardware.org/?probe=702b924ad3) | May 06, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| HUAWEI        | HLYL-WXX9                   | [a8ae42440e](https://linux-hardware.org/?probe=a8ae42440e) | May 06, 2021 |
| ASUSTek       | T100TA                      | [61c9e8ca48](https://linux-hardware.org/?probe=61c9e8ca48) | May 05, 2021 |
| Acer          | Swift SF314-59              | [5a4f35e056](https://linux-hardware.org/?probe=5a4f35e056) | May 05, 2021 |
| Standard      | Unknown                     | [e9a891227f](https://linux-hardware.org/?probe=e9a891227f) | May 05, 2021 |
| HP            | ProBook 430 G1              | [64221d8f8a](https://linux-hardware.org/?probe=64221d8f8a) | May 04, 2021 |
| HP            | Pavilion Notebook           | [2d0fb807ed](https://linux-hardware.org/?probe=2d0fb807ed) | May 04, 2021 |
| Dell          | Vostro 5490                 | [c89b28e2f3](https://linux-hardware.org/?probe=c89b28e2f3) | May 03, 2021 |
| Acer          | Predator G9-793             | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| Dell          | Vostro 5490                 | [b852cc3b14](https://linux-hardware.org/?probe=b852cc3b14) | May 03, 2021 |
| Dell          | Vostro 5490                 | [43ecd6539f](https://linux-hardware.org/?probe=43ecd6539f) | May 03, 2021 |
| HP            | EliteBook 2540p             | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| HP            | Pavilion Notebook           | [dc246b5e6d](https://linux-hardware.org/?probe=dc246b5e6d) | May 02, 2021 |
| System76      | Galago Pro                  | [0081dd52a5](https://linux-hardware.org/?probe=0081dd52a5) | May 02, 2021 |
| Lenovo        | ThinkPad T470 20HES1HD01    | [4eb1086713](https://linux-hardware.org/?probe=4eb1086713) | May 02, 2021 |
| TUXEDO        | Unknown                     | [9e7bc88973](https://linux-hardware.org/?probe=9e7bc88973) | May 02, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [6223ea92f1](https://linux-hardware.org/?probe=6223ea92f1) | May 02, 2021 |
| Dell          | Vostro 3550                 | [8c78374db7](https://linux-hardware.org/?probe=8c78374db7) | May 02, 2021 |
| Acer          | Aspire A515-43              | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | ProBook 6460b               | [24fab4aa05](https://linux-hardware.org/?probe=24fab4aa05) | May 02, 2021 |
| HUAWEI        | WRTB-WXX9                   | [f9ceb7c523](https://linux-hardware.org/?probe=f9ceb7c523) | May 02, 2021 |
| Dell          | Vostro 3550                 | [9eaacbadec](https://linux-hardware.org/?probe=9eaacbadec) | May 01, 2021 |
| Sony          | VGN-FZ11S                   | [bd472575f4](https://linux-hardware.org/?probe=bd472575f4) | May 01, 2021 |
| Lenovo        | ThinkPad E480 20KN0061RT    | [6d6d654a5a](https://linux-hardware.org/?probe=6d6d654a5a) | May 01, 2021 |
| Lenovo        | ThinkPad E470 20H2S00700    | [cc35722c1f](https://linux-hardware.org/?probe=cc35722c1f) | May 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [d0838b99d8](https://linux-hardware.org/?probe=d0838b99d8) | May 01, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [7d6a70d93f](https://linux-hardware.org/?probe=7d6a70d93f) | Apr 30, 2021 |
| Samsung       | 270E5J/2570EJ               | [48c0082d7e](https://linux-hardware.org/?probe=48c0082d7e) | Apr 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [61c335bd08](https://linux-hardware.org/?probe=61c335bd08) | Apr 28, 2021 |
| Acer          | Swift SF114-32              | [2b9b5faf20](https://linux-hardware.org/?probe=2b9b5faf20) | Apr 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [8e8858711b](https://linux-hardware.org/?probe=8e8858711b) | Apr 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [2c4d248451](https://linux-hardware.org/?probe=2c4d248451) | Apr 28, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | [56406a43bd](https://linux-hardware.org/?probe=56406a43bd) | Apr 28, 2021 |
| MSI           | GL75 Leopard 10SDR          | [458deed3d3](https://linux-hardware.org/?probe=458deed3d3) | Apr 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [b3217892ed](https://linux-hardware.org/?probe=b3217892ed) | Apr 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [ec5b0541a2](https://linux-hardware.org/?probe=ec5b0541a2) | Apr 27, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [8638d59270](https://linux-hardware.org/?probe=8638d59270) | Apr 27, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [f729b14cca](https://linux-hardware.org/?probe=f729b14cca) | Apr 27, 2021 |
| Dell          | Inspiron 5593               | [cd9f6f91af](https://linux-hardware.org/?probe=cd9f6f91af) | Apr 26, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [604a50766b](https://linux-hardware.org/?probe=604a50766b) | Apr 26, 2021 |
| HP            | EliteBook 840 G5            | [266fb405d7](https://linux-hardware.org/?probe=266fb405d7) | Apr 26, 2021 |
| Toshiba       | Satellite A350              | [5da06fd6b1](https://linux-hardware.org/?probe=5da06fd6b1) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bf2ec3a69c](https://linux-hardware.org/?probe=bf2ec3a69c) | Apr 26, 2021 |
| TUXEDO        | Unknown                     | [0609ea696c](https://linux-hardware.org/?probe=0609ea696c) | Apr 26, 2021 |
| Dell          | Inspiron 3542               | [9e090254cd](https://linux-hardware.org/?probe=9e090254cd) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [0bcc333251](https://linux-hardware.org/?probe=0bcc333251) | Apr 25, 2021 |
| Lenovo        | ThinkPad T410 2537FP3       | [ae38a32169](https://linux-hardware.org/?probe=ae38a32169) | Apr 25, 2021 |
| Lenovo        | ThinkPad T410 2537FP3       | [45559a492c](https://linux-hardware.org/?probe=45559a492c) | Apr 25, 2021 |
| Lenovo        | ThinkPad T420 4236EF4       | [4d07ea7b58](https://linux-hardware.org/?probe=4d07ea7b58) | Apr 24, 2021 |
| Samsung       | NC210/NC110                 | [45678e2907](https://linux-hardware.org/?probe=45678e2907) | Apr 24, 2021 |
| Samsung       | NC210/NC110                 | [f178c672cf](https://linux-hardware.org/?probe=f178c672cf) | Apr 24, 2021 |
| HUAWEI        | MACHC-WAX9                  | [15cbbda6f8](https://linux-hardware.org/?probe=15cbbda6f8) | Apr 24, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [b6b305b0bd](https://linux-hardware.org/?probe=b6b305b0bd) | Apr 24, 2021 |
| HP            | ProBook 450 G7              | [f5bfb4f382](https://linux-hardware.org/?probe=f5bfb4f382) | Apr 24, 2021 |
| HP            | ProBook 450 G7              | [af9117e999](https://linux-hardware.org/?probe=af9117e999) | Apr 24, 2021 |
| ASUSTek       | K50IN                       | [7a84f17bdb](https://linux-hardware.org/?probe=7a84f17bdb) | Apr 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS55S00    | [5dc10377ab](https://linux-hardware.org/?probe=5dc10377ab) | Apr 23, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | [3120e73dca](https://linux-hardware.org/?probe=3120e73dca) | Apr 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Dell          | XPS 15 7590                 | [7963c5b064](https://linux-hardware.org/?probe=7963c5b064) | Apr 23, 2021 |
| Lenovo        | ThinkPad T420 4236EF4       | [015d11b9cb](https://linux-hardware.org/?probe=015d11b9cb) | Apr 19, 2021 |
| Acer          | Aspire E5-771G              | [eb63a6bb36](https://linux-hardware.org/?probe=eb63a6bb36) | Apr 17, 2021 |
| Acer          | Aspire E5-771G              | [e3bc507a07](https://linux-hardware.org/?probe=e3bc507a07) | Apr 17, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| HP            | Compaq CQ58                 | [3274addf89](https://linux-hardware.org/?probe=3274addf89) | Apr 14, 2021 |
| HP            | Spectre XT Ultrabook PC     | [adf30d3202](https://linux-hardware.org/?probe=adf30d3202) | Apr 09, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [519d1fea88](https://linux-hardware.org/?probe=519d1fea88) | Apr 09, 2021 |
| Dell          | Inspiron 7560               | [b3110fa6fb](https://linux-hardware.org/?probe=b3110fa6fb) | Apr 09, 2021 |
| ASUSTek       | X542URR                     | [d49a5f2b6c](https://linux-hardware.org/?probe=d49a5f2b6c) | Apr 07, 2021 |
| Lenovo        | ThinkPad T430 2349DD5       | [3cf8173314](https://linux-hardware.org/?probe=3cf8173314) | Apr 05, 2021 |
| Lenovo        | B50-70 80EU                 | [6534232c53](https://linux-hardware.org/?probe=6534232c53) | Apr 04, 2021 |
| HUAWEI        | MACH-WX9                    | [806a28ffcb](https://linux-hardware.org/?probe=806a28ffcb) | Apr 02, 2021 |
| Lenovo        | ThinkPad T430 2349UWT       | [d6edf7c2df](https://linux-hardware.org/?probe=d6edf7c2df) | Mar 28, 2021 |
| Dell          | G3 3500                     | [83f2a24875](https://linux-hardware.org/?probe=83f2a24875) | Mar 27, 2021 |
| Google        | Edgar                       | [e31c334180](https://linux-hardware.org/?probe=e31c334180) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [50b82af935](https://linux-hardware.org/?probe=50b82af935) | Mar 18, 2021 |
| Acer          | Aspire A515-56              | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| Razer         | Blade                       | [638dd21f45](https://linux-hardware.org/?probe=638dd21f45) | Mar 03, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [986679aa93](https://linux-hardware.org/?probe=986679aa93) | Feb 25, 2021 |
| Dell          | XPS 15 7590                 | [bded62870c](https://linux-hardware.org/?probe=bded62870c) | Feb 23, 2021 |
| Acer          | Aspire A515-44              | [d87649a1b4](https://linux-hardware.org/?probe=d87649a1b4) | Jan 27, 2021 |
| Acer          | Aspire A515-44              | [ea1a9ef713](https://linux-hardware.org/?probe=ea1a9ef713) | Jan 27, 2021 |
| HASEE Comp... | HINS                        | [2419cd659a](https://linux-hardware.org/?probe=2419cd659a) | Jan 24, 2021 |
| HP            | 630                         | [1e3eae8729](https://linux-hardware.org/?probe=1e3eae8729) | Jan 21, 2021 |
| Acer          | Aspire V5-552G              | [8e70dd07f9](https://linux-hardware.org/?probe=8e70dd07f9) | Jan 19, 2021 |
| HP            | ProBook 650 G1              | [57427da656](https://linux-hardware.org/?probe=57427da656) | Jan 02, 2021 |
| Lenovo        | G505s 20255                 | [772dc9d4d7](https://linux-hardware.org/?probe=772dc9d4d7) | Dec 27, 2020 |
| ASUSTek       | X541NA                      | [b17ba4582e](https://linux-hardware.org/?probe=b17ba4582e) | Dec 22, 2020 |
| ASUSTek       | X541NA                      | [1feb258908](https://linux-hardware.org/?probe=1feb258908) | Dec 20, 2020 |
| Gateway       | M290                        | [0b09493054](https://linux-hardware.org/?probe=0b09493054) | Dec 15, 2020 |
| Gateway       | M290                        | [647ec28bce](https://linux-hardware.org/?probe=647ec28bce) | Dec 13, 2020 |
| Acer          | Aspire V5-552G              | [8f8a054e09](https://linux-hardware.org/?probe=8f8a054e09) | Dec 13, 2020 |
| Gateway       | M290                        | [361d599d08](https://linux-hardware.org/?probe=361d599d08) | Dec 11, 2020 |
| ASUSTek       | X556UQ                      | [06423fe399](https://linux-hardware.org/?probe=06423fe399) | Dec 02, 2020 |
| Alienware     | 13 R3                       | [b4b8471219](https://linux-hardware.org/?probe=b4b8471219) | Nov 22, 2020 |
| ASUSTek       | X556UQ                      | [4526906af6](https://linux-hardware.org/?probe=4526906af6) | Nov 06, 2020 |
| ASUSTek       | X556UQ                      | [d55510c234](https://linux-hardware.org/?probe=d55510c234) | Nov 06, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-25-generic        | 107       | 19.81%  |
| 5.11.0-22-generic        | 92        | 17.04%  |
| 5.11.0-16-generic        | 92        | 17.04%  |
| 5.11.0-18-generic        | 81        | 15%     |
| 5.11.0-17-generic        | 80        | 14.81%  |
| 5.11.0-26-generic        | 10        | 1.85%   |
| 5.11.0-20-generic        | 7         | 1.3%    |
| 5.11.0-24-generic        | 6         | 1.11%   |
| 5.11.0-13-generic        | 6         | 1.11%   |
| 5.13.0-051300-generic    | 4         | 0.74%   |
| 5.11.0-31-generic        | 3         | 0.56%   |
| 5.11.0-11-generic        | 3         | 0.56%   |
| 5.10.0-14-generic        | 3         | 0.56%   |
| 5.8.0-50-generic         | 2         | 0.37%   |
| 5.8.0-36-generic         | 2         | 0.37%   |
| 5.8.0-32-generic         | 2         | 0.37%   |
| 5.8.0-25-generic         | 2         | 0.37%   |
| 5.13.9-051309-generic    | 2         | 0.37%   |
| 5.13.1-051301-generic    | 2         | 0.37%   |
| 5.12.12-051212-generic   | 2         | 0.37%   |
| 5.12.0-051200rc3-generic | 2         | 0.37%   |
| 5.12.0-051200-generic    | 2         | 0.37%   |
| 5.11.0-14-generic        | 2         | 0.37%   |
| 5.8.0-63-generic         | 1         | 0.19%   |
| 5.8.0-55-generic         | 1         | 0.19%   |
| 5.8.0-44-generic         | 1         | 0.19%   |
| 5.8.0-41-generic         | 1         | 0.19%   |
| 5.8.0-33-generic         | 1         | 0.19%   |
| 5.8.0-31-lowlatency      | 1         | 0.19%   |
| 5.8.0-29-generic         | 1         | 0.19%   |
| 5.8.0-26-lowlatency      | 1         | 0.19%   |
| 5.14.0-051400rc5-generic | 1         | 0.19%   |
| 5.14.0-051400rc3-generic | 1         | 0.19%   |
| 5.13.7-051307-generic    | 1         | 0.19%   |
| 5.13.4-051304-generic    | 1         | 0.19%   |
| 5.13.0-051300rc7-generic | 1         | 0.19%   |
| 5.13.0-051300rc4-generic | 1         | 0.19%   |
| 5.12.9-051209-generic    | 1         | 0.19%   |
| 5.12.4-051204-generic    | 1         | 0.19%   |
| 5.12.0-051200rc5-generic | 1         | 0.19%   |
| 5.11.6-051106-generic    | 1         | 0.19%   |
| 5.11.12-051112-generic   | 1         | 0.19%   |
| 5.11.0-7614-generic      | 1         | 0.19%   |
| 5.11.0-26-lowlatency     | 1         | 0.19%   |
| 5.11.0-22-lowlatency     | 1         | 0.19%   |
| 5.11.0-19-generic        | 1         | 0.19%   |
| 5.11.0-17-lowlatency     | 1         | 0.19%   |
| 5.11.0-16-lowlatency     | 1         | 0.19%   |
| 5.10.0-12-generic        | 1         | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 468       | 91.41%  |
| 5.8.0   | 15        | 2.93%   |
| 5.13.0  | 6         | 1.17%   |
| 5.12.0  | 5         | 0.98%   |
| 5.10.0  | 4         | 0.78%   |
| 5.14.0  | 2         | 0.39%   |
| 5.13.9  | 2         | 0.39%   |
| 5.13.1  | 2         | 0.39%   |
| 5.12.12 | 2         | 0.39%   |
| 5.13.7  | 1         | 0.2%    |
| 5.13.4  | 1         | 0.2%    |
| 5.12.9  | 1         | 0.2%    |
| 5.12.4  | 1         | 0.2%    |
| 5.11.6  | 1         | 0.2%    |
| 5.11.12 | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 470       | 91.98%  |
| 5.8     | 15        | 2.94%   |
| 5.13    | 11        | 2.15%   |
| 5.12    | 9         | 1.76%   |
| 5.10    | 4         | 0.78%   |
| 5.14    | 2         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 508       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 441       | 85.96%  |
| Unknown         | 54        | 10.53%  |
| X-Cinnamon      | 6         | 1.17%   |
| Unity           | 4         | 0.78%   |
| Deepin          | 4         | 0.78%   |
| Cinnamon        | 3         | 0.58%   |
| GNOME Flashback | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 312       | 60.58%  |
| X11     | 168       | 32.62%  |
| Unknown | 32        | 6.21%   |
| Tty     | 3         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 344       | 67.58%  |
| GDM     | 156       | 30.65%  |
| TDM     | 6         | 1.18%   |
| SDDM    | 2         | 0.39%   |
| GDM3    | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 218       | 42.91%  |
| de_DE   | 45        | 8.86%   |
| fr_FR   | 35        | 6.89%   |
| en_GB   | 29        | 5.71%   |
| en_IN   | 21        | 4.13%   |
| it_IT   | 18        | 3.54%   |
| pt_BR   | 17        | 3.35%   |
| ru_RU   | 14        | 2.76%   |
| es_ES   | 13        | 2.56%   |
| pl_PL   | 11        | 2.17%   |
| cs_CZ   | 10        | 1.97%   |
| en_CA   | 8         | 1.57%   |
| en_AU   | 7         | 1.38%   |
| nl_NL   | 4         | 0.79%   |
| es_MX   | 4         | 0.79%   |
| es_CL   | 4         | 0.79%   |
| en_ZA   | 4         | 0.79%   |
| zh_CN   | 3         | 0.59%   |
| de_AT   | 3         | 0.59%   |
| Unknown | 3         | 0.59%   |
| zh_TW   | 2         | 0.39%   |
| sv_SE   | 2         | 0.39%   |
| ja_JP   | 2         | 0.39%   |
| es_UY   | 2         | 0.39%   |
| es_EC   | 2         | 0.39%   |
| da_DK   | 2         | 0.39%   |
| C       | 2         | 0.39%   |
| vi_VN   | 1         | 0.2%    |
| tr_TR   | 1         | 0.2%    |
| sr_RS   | 1         | 0.2%    |
| ru_UA   | 1         | 0.2%    |
| pt_PT   | 1         | 0.2%    |
| nb_NO   | 1         | 0.2%    |
| hu_HU   | 1         | 0.2%    |
| hr_HR   | 1         | 0.2%    |
| fr_CA   | 1         | 0.2%    |
| fr_BE   | 1         | 0.2%    |
| fi_FI   | 1         | 0.2%    |
| es_PE   | 1         | 0.2%    |
| es_HN   | 1         | 0.2%    |
| es_CU   | 1         | 0.2%    |
| es_CO   | 1         | 0.2%    |
| en_NZ   | 1         | 0.2%    |
| en_IL   | 1         | 0.2%    |
| en_DK   | 1         | 0.2%    |
| de_IT   | 1         | 0.2%    |
| de_CH   | 1         | 0.2%    |
| ca_ES   | 1         | 0.2%    |
| bg_BG   | 1         | 0.2%    |
| ar_SA   | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 295       | 57.5%   |
| EFI  | 218       | 42.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 473       | 93.11%  |
| Zfs     | 19        | 3.74%   |
| Overlay | 7         | 1.38%   |
| Btrfs   | 7         | 1.38%   |
| Xfs     | 1         | 0.2%    |
| Ext2    | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 339       | 66.6%   |
| GPT     | 163       | 32.02%  |
| MBR     | 7         | 1.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 455       | 89.39%  |
| Yes       | 54        | 10.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 340       | 66.67%  |
| Yes       | 170       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo                                       | 101       | 19.88%  |
| Hewlett-Packard                              | 100       | 19.69%  |
| Dell                                         | 92        | 18.11%  |
| ASUSTek Computer                             | 51        | 10.04%  |
| Acer                                         | 42        | 8.27%   |
| Apple                                        | 13        | 2.56%   |
| Samsung Electronics                          | 11        | 2.17%   |
| HUAWEI                                       | 11        | 2.17%   |
| Sony                                         | 9         | 1.77%   |
| MSI                                          | 9         | 1.77%   |
| Fujitsu                                      | 7         | 1.38%   |
| Toshiba                                      | 6         | 1.18%   |
| Medion                                       | 5         | 0.98%   |
| Timi                                         | 4         | 0.79%   |
| System76                                     | 3         | 0.59%   |
| Razer                                        | 3         | 0.59%   |
| Positivo                                     | 3         | 0.59%   |
| Unknown                                      | 3         | 0.59%   |
| TUXEDO                                       | 2         | 0.39%   |
| Notebook                                     | 2         | 0.39%   |
| LG Electronics                               | 2         | 0.39%   |
| Google                                       | 2         | 0.39%   |
| Alienware                                    | 2         | 0.39%   |
| Wiltronic                                    | 1         | 0.2%    |
| VINGA                                        | 1         | 0.2%    |
| Teclast                                      | 1         | 0.2%    |
| Standard                                     | 1         | 0.2%    |
| Schenker                                     | 1         | 0.2%    |
| roda computer                                | 1         | 0.2%    |
| Radxa                                        | 1         | 0.2%    |
| Positivo Bahia - VAIO                        | 1         | 0.2%    |
| Pegatron                                     | 1         | 0.2%    |
| Panasonic                                    | 1         | 0.2%    |
| Packard Bell                                 | 1         | 0.2%    |
| Monster                                      | 1         | 0.2%    |
| Maibenben                                    | 1         | 0.2%    |
| IP3 Tech                                     | 1         | 0.2%    |
| Insignia                                     | 1         | 0.2%    |
| HKC                                          | 1         | 0.2%    |
| HCL Infosystems Limited                      | 1         | 0.2%    |
| HASEE Computer                               | 1         | 0.2%    |
| Gigabyte Technology                          | 1         | 0.2%    |
| Gateway                                      | 1         | 0.2%    |
| eMachines                                    | 1         | 0.2%    |
| DNS                                          | 1         | 0.2%    |
| CHUWI?Innovation?And?Technology(ShenZhen)co. | 1         | 0.2%    |
| Chuwi                                        | 1         | 0.2%    |
| Advance                                      | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 8         | 1.57%   |
| Dell XPS 15 7590                       | 7         | 1.38%   |
| Lenovo G500 20236                      | 3         | 0.59%   |
| HUAWEI HLYL-WXX9                       | 3         | 0.59%   |
| Dell G3 3500                           | 3         | 0.59%   |
| Acer Aspire A515-44                    | 3         | 0.59%   |
| System76 Serval WS                     | 2         | 0.39%   |
| Razer Blade                            | 2         | 0.39%   |
| Lenovo IdeaPad 520-15IKB 81BF          | 2         | 0.39%   |
| Lenovo IdeaPad 3 17ADA05 81W2          | 2         | 0.39%   |
| HUAWEI MACH-WX9                        | 2         | 0.39%   |
| HUAWEI BOHK-WAX9X                      | 2         | 0.39%   |
| HP ProBook 650 G1                      | 2         | 0.39%   |
| HP ProBook 4540s                       | 2         | 0.39%   |
| HP ProBook 450 G7                      | 2         | 0.39%   |
| HP Pavilion Notebook                   | 2         | 0.39%   |
| HP Pavilion dv6                        | 2         | 0.39%   |
| HP Pavilion dv5                        | 2         | 0.39%   |
| HP Notebook                            | 2         | 0.39%   |
| HP Laptop 15s-eq1xxx                   | 2         | 0.39%   |
| HP EliteBook Folio 1040 G3             | 2         | 0.39%   |
| HP EliteBook 8570w                     | 2         | 0.39%   |
| HP EliteBook 840 G3                    | 2         | 0.39%   |
| HP EliteBook 840 G2                    | 2         | 0.39%   |
| HP EliteBook 820 G1                    | 2         | 0.39%   |
| HP 255 G7 Notebook PC                  | 2         | 0.39%   |
| Fujitsu STYLISTIC Q702                 | 2         | 0.39%   |
| Dell XPS 15 9570                       | 2         | 0.39%   |
| Dell XPS 15 9500                       | 2         | 0.39%   |
| Dell Latitude E7440                    | 2         | 0.39%   |
| Dell Latitude E5520                    | 2         | 0.39%   |
| Dell Latitude 5511                     | 2         | 0.39%   |
| Dell Inspiron 5593                     | 2         | 0.39%   |
| Dell Inspiron 5521                     | 2         | 0.39%   |
| Dell Inspiron 1525                     | 2         | 0.39%   |
| Dell Inspiron 15-3567                  | 2         | 0.39%   |
| Dell G5 5587                           | 2         | 0.39%   |
| ASUS X551CAP                           | 2         | 0.39%   |
| ASUS VivoBook_ASUSLaptop X512JA_F512JA | 2         | 0.39%   |
| ASUS T100HAN                           | 2         | 0.39%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV  | 2         | 0.39%   |
| Acer Swift SF314-59                    | 2         | 0.39%   |
| Acer Aspire ES1-512                    | 2         | 0.39%   |
| Wiltronic IVIEW Maximus Pro            | 1         | 0.2%    |
| VINGA Iron S140                        | 1         | 0.2%    |
| Toshiba TECRA Z40-B                    | 1         | 0.2%    |
| Toshiba Satellite Pro L650             | 1         | 0.2%    |
| Toshiba Satellite A350                 | 1         | 0.2%    |
| Toshiba QOSMIO X70-B                   | 1         | 0.2%    |
| Toshiba PORTEGE Z930                   | 1         | 0.2%    |
| Toshiba PORTEGE R705                   | 1         | 0.2%    |
| Timi TM1703                            | 1         | 0.2%    |
| Timi TM1701                            | 1         | 0.2%    |
| Timi Mi Laptop Pro 15 2020             | 1         | 0.2%    |
| Timi A35S                              | 1         | 0.2%    |
| Teclast F7 Plus                        | 1         | 0.2%    |
| System76 Galago Pro                    | 1         | 0.2%    |
| Sony VPCEJ1L1E                         | 1         | 0.2%    |
| Sony VPCCW2S8E                         | 1         | 0.2%    |
| Sony VGN-NS21Z_S                       | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 55        | 10.83%  |
| Dell Latitude     | 28        | 5.51%   |
| Acer Aspire       | 27        | 5.31%   |
| Dell Inspiron     | 25        | 4.92%   |
| HP EliteBook      | 23        | 4.53%   |
| Lenovo IdeaPad    | 21        | 4.13%   |
| HP ProBook        | 19        | 3.74%   |
| Dell XPS          | 18        | 3.54%   |
| HP Pavilion       | 15        | 2.95%   |
| HP Laptop         | 11        | 2.17%   |
| ASUS ROG          | 10        | 1.97%   |
| Acer Swift        | 8         | 1.57%   |
| Unknown           | 8         | 1.57%   |
| Dell Vostro       | 7         | 1.38%   |
| ASUS VivoBook     | 7         | 1.38%   |
| HP ENVY           | 6         | 1.18%   |
| Fujitsu LIFEBOOK  | 5         | 0.98%   |
| Dell Precision    | 5         | 0.98%   |
| Lenovo ThinkBook  | 4         | 0.79%   |
| Dell G3           | 4         | 0.79%   |
| Razer Blade       | 3         | 0.59%   |
| Lenovo G500       | 3         | 0.59%   |
| HUAWEI HLYL-WXX9  | 3         | 0.59%   |
| HP OMEN           | 3         | 0.59%   |
| Acer TravelMate   | 3         | 0.59%   |
| Toshiba Satellite | 2         | 0.39%   |
| Toshiba PORTEGE   | 2         | 0.39%   |
| System76 Serval   | 2         | 0.39%   |
| Lenovo Yoga       | 2         | 0.39%   |
| Lenovo Legion     | 2         | 0.39%   |
| Lenovo G50-80     | 2         | 0.39%   |
| HUAWEI MACH-WX9   | 2         | 0.39%   |
| HUAWEI BOHK-WAX9X | 2         | 0.39%   |
| HP ZBook          | 2         | 0.39%   |
| HP Spectre        | 2         | 0.39%   |
| HP Notebook       | 2         | 0.39%   |
| HP Compaq         | 2         | 0.39%   |
| HP 255            | 2         | 0.39%   |
| HP 15             | 2         | 0.39%   |
| Fujitsu STYLISTIC | 2         | 0.39%   |
| Dell G7           | 2         | 0.39%   |
| Dell G5           | 2         | 0.39%   |
| ASUS ZenBook      | 2         | 0.39%   |
| ASUS X551CAP      | 2         | 0.39%   |
| ASUS T100HAN      | 2         | 0.39%   |
| ASUS ASUS         | 2         | 0.39%   |
| Apple MacBookPro8 | 2         | 0.39%   |
| Wiltronic IVIEW   | 1         | 0.2%    |
| VINGA Iron        | 1         | 0.2%    |
| Toshiba TECRA     | 1         | 0.2%    |
| Toshiba QOSMIO    | 1         | 0.2%    |
| Timi TM1703       | 1         | 0.2%    |
| Timi TM1701       | 1         | 0.2%    |
| Timi Mi           | 1         | 0.2%    |
| Timi A35S         | 1         | 0.2%    |
| Teclast F7        | 1         | 0.2%    |
| System76 Galago   | 1         | 0.2%    |
| Sony VPCEJ1L1E    | 1         | 0.2%    |
| Sony VPCCW2S8E    | 1         | 0.2%    |
| Sony VGN-NS21Z    | 1         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 118       | 23.23%  |
| 2021 | 104       | 20.47%  |
| 2019 | 57        | 11.22%  |
| 2018 | 35        | 6.89%   |
| 2011 | 30        | 5.91%   |
| 2015 | 27        | 5.31%   |
| 2013 | 24        | 4.72%   |
| 2017 | 20        | 3.94%   |
| 2012 | 18        | 3.54%   |
| 2009 | 17        | 3.35%   |
| 2016 | 15        | 2.95%   |
| 2014 | 15        | 2.95%   |
| 2010 | 14        | 2.76%   |
| 2008 | 10        | 1.97%   |
| 2007 | 4         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 508       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 450       | 88.41%  |
| Enabled  | 59        | 11.59%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 505       | 99.41%  |
| Yes  | 3         | 0.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 163       | 32.09%  |
| 16.01-24.0  | 96        | 18.9%   |
| 3.01-4.0    | 95        | 18.7%   |
| 8.01-16.0   | 80        | 15.75%  |
| 32.01-64.0  | 42        | 8.27%   |
| 1.01-2.0    | 22        | 4.33%   |
| 64.01-256.0 | 6         | 1.18%   |
| 24.01-32.0  | 3         | 0.59%   |
| 2.01-3.0    | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 194       | 36.74%  |
| 2.01-3.0   | 145       | 27.46%  |
| 4.01-8.0   | 80        | 15.15%  |
| 3.01-4.0   | 76        | 14.39%  |
| 8.01-16.0  | 17        | 3.22%   |
| 0.51-1.0   | 11        | 2.08%   |
| 16.01-24.0 | 2         | 0.38%   |
| 0.01-0.5   | 2         | 0.38%   |
| 24.01-32.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 379       | 74.17%  |
| 2      | 111       | 21.72%  |
| 3      | 11        | 2.15%   |
| 4      | 4         | 0.78%   |
| 0      | 4         | 0.78%   |
| 6      | 1         | 0.2%    |
| 5      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 354       | 69.69%  |
| Yes       | 154       | 30.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 392       | 77.01%  |
| No        | 117       | 22.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 494       | 97.05%  |
| No        | 15        | 2.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 410       | 80.55%  |
| No        | 99        | 19.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 75        | 14.76%  |
| Germany             | 57        | 11.22%  |
| France              | 34        | 6.69%   |
| Russia              | 26        | 5.12%   |
| Italy               | 25        | 4.92%   |
| UK                  | 24        | 4.72%   |
| Brazil              | 23        | 4.53%   |
| India               | 22        | 4.33%   |
| Spain               | 21        | 4.13%   |
| Poland              | 16        | 3.15%   |
| Czechia             | 13        | 2.56%   |
| Canada              | 13        | 2.56%   |
| Netherlands         | 10        | 1.97%   |
| Finland             | 9         | 1.77%   |
| Mexico              | 8         | 1.57%   |
| Austria             | 7         | 1.38%   |
| Australia           | 7         | 1.38%   |
| Ukraine             | 6         | 1.18%   |
| Turkey              | 6         | 1.18%   |
| Switzerland         | 5         | 0.98%   |
| Sweden              | 5         | 0.98%   |
| Vietnam             | 4         | 0.79%   |
| South Africa        | 4         | 0.79%   |
| Chile               | 4         | 0.79%   |
| Romania             | 3         | 0.59%   |
| Portugal            | 3         | 0.59%   |
| Luxembourg          | 3         | 0.59%   |
| Japan               | 3         | 0.59%   |
| Israel              | 3         | 0.59%   |
| Indonesia           | 3         | 0.59%   |
| Hungary             | 3         | 0.59%   |
| Greece              | 3         | 0.59%   |
| Croatia             | 3         | 0.59%   |
| Colombia            | 3         | 0.59%   |
| China               | 3         | 0.59%   |
| Belgium             | 3         | 0.59%   |
| Belarus             | 3         | 0.59%   |
| Uruguay             | 2         | 0.39%   |
| Taiwan              | 2         | 0.39%   |
| Slovakia            | 2         | 0.39%   |
| Serbia              | 2         | 0.39%   |
| Peru                | 2         | 0.39%   |
| Lithuania           | 2         | 0.39%   |
| Latvia              | 2         | 0.39%   |
| Ecuador             | 2         | 0.39%   |
| Denmark             | 2         | 0.39%   |
| Zimbabwe            | 1         | 0.2%    |
| Trinidad and Tobago | 1         | 0.2%    |
| Sudan               | 1         | 0.2%    |
| Saudi Arabia        | 1         | 0.2%    |
| Pakistan            | 1         | 0.2%    |
| Norway              | 1         | 0.2%    |
| New Zealand         | 1         | 0.2%    |
| Nepal               | 1         | 0.2%    |
| Morocco             | 1         | 0.2%    |
| Moldova             | 1         | 0.2%    |
| Mauritius           | 1         | 0.2%    |
| Malaysia            | 1         | 0.2%    |
| Malawi              | 1         | 0.2%    |
| Madagascar          | 1         | 0.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Moscow              | 9         | 1.74%   |
| Vienna              | 7         | 1.36%   |
| Prague              | 7         | 1.36%   |
| Paris               | 7         | 1.36%   |
| Milan               | 5         | 0.97%   |
| Helsinki            | 5         | 0.97%   |
| Cologne             | 5         | 0.97%   |
| Berlin              | 5         | 0.97%   |
| Warsaw              | 4         | 0.78%   |
| St Petersburg       | 3         | 0.58%   |
| Santiago            | 3         | 0.58%   |
| New Delhi           | 3         | 0.58%   |
| Montreal            | 3         | 0.58%   |
| Kyiv                | 3         | 0.58%   |
| Gdansk              | 3         | 0.58%   |
| Athens              | 3         | 0.58%   |
| Zagreb              | 2         | 0.39%   |
| Valencia            | 2         | 0.39%   |
| Utrecht             | 2         | 0.39%   |
| Sydney              | 2         | 0.39%   |
| Schifflange         | 2         | 0.39%   |
| S??o Paulo          | 2         | 0.39%   |
| Rostov-on-Don       | 2         | 0.39%   |
| Riga                | 2         | 0.39%   |
| Nuremberg           | 2         | 0.39%   |
| Nizhnevartovsk      | 2         | 0.39%   |
| New York            | 2         | 0.39%   |
| New Braunfels       | 2         | 0.39%   |
| Minsk               | 2         | 0.39%   |
| Mexico City         | 2         | 0.39%   |
| Madrid              | 2         | 0.39%   |
| Los Angeles         | 2         | 0.39%   |
| London              | 2         | 0.39%   |
| Krasnodar           | 2         | 0.39%   |
| Krakow              | 2         | 0.39%   |
| Kolkata             | 2         | 0.39%   |
| Kaunas              | 2         | 0.39%   |
| Johannesburg        | 2         | 0.39%   |
| Jakarta             | 2         | 0.39%   |
| Istanbul            | 2         | 0.39%   |
| Hamburg             | 2         | 0.39%   |
| Florence            | 2         | 0.39%   |
| Dresden             | 2         | 0.39%   |
| D??sseldorf         | 2         | 0.39%   |
| Dallas              | 2         | 0.39%   |
| Brno                | 2         | 0.39%   |
| Brisbane            | 2         | 0.39%   |
| Birmingham          | 2         | 0.39%   |
| Bengaluru           | 2         | 0.39%   |
| Belgrade            | 2         | 0.39%   |
| Alexandria          | 2         | 0.39%   |
| Łomża             | 1         | 0.19%   |
| České Budějovice | 1         | 0.19%   |
| Örnsköldsvik      | 1         | 0.19%   |
| Złotoryja          | 1         | 0.19%   |
| Zabrze              | 1         | 0.19%   |
| Yilan               | 1         | 0.19%   |
| Yekaterinburg       | 1         | 0.19%   |
| Woodstock           | 1         | 0.19%   |
| Woerden             | 1         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 100       | 114    | 16.16%  |
| WDC                       | 76        | 82     | 12.28%  |
| Toshiba                   | 66        | 79     | 10.66%  |
| Seagate                   | 65        | 70     | 10.5%   |
| SanDisk                   | 38        | 45     | 6.14%   |
| SK Hynix                  | 37        | 37     | 5.98%   |
| Unknown                   | 31        | 41     | 5.01%   |
| Intel                     | 24        | 30     | 3.88%   |
| Kingston                  | 23        | 24     | 3.72%   |
| HGST                      | 21        | 25     | 3.39%   |
| Crucial                   | 20        | 27     | 3.23%   |
| Micron Technology         | 16        | 16     | 2.58%   |
| Hitachi                   | 12        | 13     | 1.94%   |
| KIOXIA                    | 7         | 7      | 1.13%   |
| Apple                     | 7         | 7      | 1.13%   |
| A-DATA Technology         | 7         | 7      | 1.13%   |
| Patriot                   | 6         | 7      | 0.97%   |
| Micron/Crucial Technology | 4         | 4      | 0.65%   |
| LITEONIT                  | 4         | 7      | 0.65%   |
| Hewlett-Packard           | 4         | 4      | 0.65%   |
| SPCC                      | 3         | 3      | 0.48%   |
| Phison                    | 3         | 3      | 0.48%   |
| LITEON                    | 3         | 3      | 0.48%   |
| KingSpec                  | 3         | 3      | 0.48%   |
| China                     | 3         | 3      | 0.48%   |
| Union Memory              | 2         | 2      | 0.32%   |
| OCZ                       | 2         | 2      | 0.32%   |
| Lenovo                    | 2         | 3      | 0.32%   |
| Intenso                   | 2         | 3      | 0.32%   |
| Indilinx                  | 2         | 2      | 0.32%   |
| Fujitsu                   | 2         | 2      | 0.32%   |
| BIWIN                     | 2         | 2      | 0.32%   |
| ASMT                      | 2         | 2      | 0.32%   |
| XPG                       | 1         | 1      | 0.16%   |
| VALK                      | 1         | 1      | 0.16%   |
| USB3.1                    | 1         | 1      | 0.16%   |
| Transcend                 | 1         | 1      | 0.16%   |
| Teclast                   | 1         | 1      | 0.16%   |
| Team                      | 1         | 1      | 0.16%   |
| Silicon Motion            | 1         | 1      | 0.16%   |
| S3+                       | 1         | 1      | 0.16%   |
| PNY                       | 1         | 2      | 0.16%   |
| Phison Electronics        | 1         | 2      | 0.16%   |
| PCIe SSD                  | 1         | 2      | 0.16%   |
| OSCOO                     | 1         | 1      | 0.16%   |
| Netac                     | 1         | 1      | 0.16%   |
| Mushkin                   | 1         | 2      | 0.16%   |
| Lite-On                   | 1         | 1      | 0.16%   |
| KingFast                  | 1         | 1      | 0.16%   |
| EZCOOL                    | 1         | 1      | 0.16%   |
| External                  | 1         | 1      | 0.16%   |
| EMTEC                     | 1         | 1      | 0.16%   |
| ADATA Technology          | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 15        | 2.34%   |
| Samsung NVMe SSD Drive 512GB           | 14        | 2.18%   |
| Toshiba MQ01ABD100 1TB                 | 10        | 1.56%   |
| Unknown MMC Card  32GB                 | 9         | 1.4%    |
| Toshiba MQ01ABF050 500GB               | 8         | 1.25%   |
| HGST HTS721010A9E630 1TB               | 8         | 1.25%   |
| Seagate ST500LT012-1DG142 500GB        | 7         | 1.09%   |
| Intel NVMe SSD Drive 512GB             | 7         | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 6         | 0.93%   |
| Sandisk NVMe SSD Drive 512GB           | 6         | 0.93%   |
| Unknown MMC Card  64GB                 | 5         | 0.78%   |
| SK Hynix NVMe SSD Drive 512GB          | 5         | 0.78%   |
| HGST HTS545050A7E680 500GB             | 5         | 0.78%   |
| Toshiba NVMe SSD Drive 512GB           | 4         | 0.62%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 0.62%   |
| SK Hynix NVMe SSD Drive 128GB          | 4         | 0.62%   |
| SK Hynix NVMe SSD Drive 1024GB         | 4         | 0.62%   |
| Samsung NVMe SSD Drive 1TB             | 4         | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 3         | 0.47%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 3         | 0.47%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB   | 3         | 0.47%   |
| WDC PC SN730 NVMe 1024GB               | 3         | 0.47%   |
| SK Hynix BC511 NVMe 512GB              | 3         | 0.47%   |
| Seagate ST9500325AS 500GB              | 3         | 0.47%   |
| Seagate ST1000LM014-1EJ164 1TB         | 3         | 0.47%   |
| SanDisk SSD PLUS 480GB                 | 3         | 0.47%   |
| SanDisk SSD PLUS 240GB                 | 3         | 0.47%   |
| Sandisk NVMe SSD Drive 256GB           | 3         | 0.47%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.47%   |
| Samsung SSD 840 EVO 120GB              | 3         | 0.47%   |
| Samsung NVMe SSD Drive 256GB           | 3         | 0.47%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 3         | 0.47%   |
| Samsung HM500JI 500GB                  | 3         | 0.47%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 3         | 0.47%   |
| KIOXIA KBG40ZNS512G NVMe 512GB         | 3         | 0.47%   |
| Kingston SUV400S37120G 120GB SSD       | 3         | 0.47%   |
| Kingston SA400S37120G 120GB SSD        | 3         | 0.47%   |
| HGST HTS545050A7E380 500GB             | 3         | 0.47%   |
| Crucial CT120BX500SSD1 120GB           | 3         | 0.47%   |
| A-DATA SP550 240GB SSD                 | 3         | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2         | 0.31%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 2         | 0.31%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.31%   |
| WDC WD3200BPVT-22JJ5T0 320GB           | 2         | 0.31%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.31%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 0.31%   |
| WDC PC SN520 SDAPNUW-256G-1014 256GB   | 2         | 0.31%   |
| Unknown SD/MMC/MS PRO 128GB            | 2         | 0.31%   |
| Unknown MMC Card  16GB                 | 2         | 0.31%   |
| Unknown MMC Card  128GB                | 2         | 0.31%   |
| Toshiba THNSNJ128GMCU 128GB SSD        | 2         | 0.31%   |
| Toshiba KXG60ZNV512G NVMe KIOXIA 512GB | 2         | 0.31%   |
| Toshiba KXG60ZNV512G 512GB             | 2         | 0.31%   |
| Toshiba KXG60ZNV1T02 NVMe 1024GB       | 2         | 0.31%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 2         | 0.31%   |
| Toshiba KXG50ZNV512G 512GB             | 2         | 0.31%   |
| Toshiba KBG40ZNT512G MEMORY 512GB      | 2         | 0.31%   |
| Toshiba KBG30ZMV256G KIOXIA 256GB      | 2         | 0.31%   |
| SK Hynix PC711 NVMe 1TB                | 2         | 0.31%   |
| SK Hynix PC611 NVMe 1TB                | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 64     | 35.23%  |
| WDC                 | 39        | 42     | 22.16%  |
| Toshiba             | 31        | 35     | 17.61%  |
| HGST                | 21        | 25     | 11.93%  |
| Hitachi             | 12        | 13     | 6.82%   |
| Samsung Electronics | 5         | 6      | 2.84%   |
| Intenso             | 2         | 3      | 1.14%   |
| Fujitsu             | 2         | 2      | 1.14%   |
| ASMT                | 1         | 1      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 53     | 23.81%  |
| SanDisk             | 24        | 27     | 12.7%   |
| Crucial             | 19        | 26     | 10.05%  |
| Kingston            | 16        | 17     | 8.47%   |
| WDC                 | 10        | 10     | 5.29%   |
| Intel               | 8         | 10     | 4.23%   |
| Toshiba             | 7         | 8      | 3.7%    |
| Patriot             | 6         | 7      | 3.17%   |
| Micron Technology   | 6         | 6      | 3.17%   |
| Apple               | 5         | 5      | 2.65%   |
| SK Hynix            | 4         | 4      | 2.12%   |
| LITEONIT            | 4         | 7      | 2.12%   |
| Hewlett-Packard     | 4         | 4      | 2.12%   |
| A-DATA Technology   | 4         | 4      | 2.12%   |
| SPCC                | 3         | 3      | 1.59%   |
| LITEON              | 3         | 3      | 1.59%   |
| KingSpec            | 3         | 3      | 1.59%   |
| China               | 3         | 3      | 1.59%   |
| OCZ                 | 2         | 2      | 1.06%   |
| Indilinx            | 2         | 2      | 1.06%   |
| VALK                | 1         | 1      | 0.53%   |
| Union Memory        | 1         | 1      | 0.53%   |
| Transcend           | 1         | 1      | 0.53%   |
| Teclast             | 1         | 1      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| S3+                 | 1         | 1      | 0.53%   |
| PNY                 | 1         | 2      | 0.53%   |
| OSCOO               | 1         | 1      | 0.53%   |
| Lenovo              | 1         | 2      | 0.53%   |
| EZCOOL              | 1         | 1      | 0.53%   |
| ASMT                | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 210       | 239    | 35%     |
| SSD     | 178       | 217    | 29.67%  |
| HDD     | 170       | 192    | 28.33%  |
| MMC     | 30        | 40     | 5%      |
| Unknown | 12        | 15     | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 315       | 397    | 54.97%  |
| NVMe | 209       | 238    | 36.47%  |
| MMC  | 30        | 40     | 5.24%   |
| SAS  | 19        | 28     | 3.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 227       | 277    | 66.57%  |
| 0.51-1.0   | 104       | 121    | 30.5%   |
| 1.01-2.0   | 8         | 8      | 2.35%   |
| 2.01-3.0   | 1         | 1      | 0.29%   |
| 4.01-10.0  | 1         | 2      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 159       | 31.12%  |
| 251-500        | 149       | 29.16%  |
| 501-1000       | 76        | 14.87%  |
| 51-100         | 38        | 7.44%   |
| 1-20           | 33        | 6.46%   |
| 1001-2000      | 22        | 4.31%   |
| 21-50          | 21        | 4.11%   |
| More than 3000 | 7         | 1.37%   |
| 2001-3000      | 3         | 0.59%   |
| Unknown        | 3         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 216       | 41.7%   |
| 21-50          | 95        | 18.34%  |
| 51-100         | 78        | 15.06%  |
| 101-250        | 68        | 13.13%  |
| 251-500        | 31        | 5.98%   |
| 501-1000       | 16        | 3.09%   |
| 1001-2000      | 6         | 1.16%   |
| More than 3000 | 4         | 0.77%   |
| Unknown        | 3         | 0.58%   |
| 2001-3000      | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB               | 2         | 2      | 9.52%   |
| WDC WD5000LPLX-60ZNTT1 500GB                  | 1         | 1      | 4.76%   |
| WDC WD3200LPCX-24C6HT0 320GB                  | 1         | 1      | 4.76%   |
| WDC WD10SPZX-17Z10T0 1TB                      | 1         | 1      | 4.76%   |
| Toshiba MK3263GSXN 320GB                      | 1         | 1      | 4.76%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD         | 1         | 1      | 4.76%   |
| Seagate ST9320423AS 320GB                     | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB               | 1         | 1      | 4.76%   |
| Seagate ST320LT020-9YG142 320GB               | 1         | 1      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 4.76%   |
| SanDisk SSD PLUS 480GB                        | 1         | 1      | 4.76%   |
| SanDisk SDSSDHII240G 240GB                    | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 860 EVO 500GB         | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 850 EVO 250GB         | 1         | 1      | 4.76%   |
| Micron Technology MTFDDAT256MAM-1K2 256GB SSD | 1         | 1      | 4.76%   |
| LITEONIT LMT-32L3M mSATA 32GB SSD             | 1         | 1      | 4.76%   |
| Hitachi HTS542525K9A300 250GB                 | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB                    | 1         | 1      | 4.76%   |
| Fujitsu MHV2080BH PL 80GB                     | 1         | 1      | 4.76%   |
| Crucial CT1000P1SSD8 1TB                      | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 28.57%  |
| WDC                 | 3         | 3      | 14.29%  |
| SanDisk             | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Toshiba             | 1         | 1      | 4.76%   |
| SK Hynix            | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| LITEONIT            | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 46.15%  |
| WDC     | 3         | 3      | 23.08%  |
| Toshiba | 1         | 1      | 7.69%   |
| Hitachi | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |
| Fujitsu | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 61.9%   |
| SSD  | 7         | 7      | 33.33%  |
| NVMe | 1         | 1      | 4.76%   |

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
| Detected | 322       | 451    | 60.3%   |
| Works    | 191       | 231    | 35.77%  |
| Malfunc  | 21        | 21     | 3.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 353       | 57.49%  |
| Samsung Electronics          | 53        | 8.63%   |
| AMD                          | 53        | 8.63%   |
| Sandisk                      | 40        | 6.51%   |
| SK Hynix                     | 33        | 5.37%   |
| Toshiba America Info Systems | 27        | 4.4%    |
| Micron Technology            | 10        | 1.63%   |
| KIOXIA                       | 10        | 1.63%   |
| Kingston Technology Company  | 7         | 1.14%   |
| Micron/Crucial Technology    | 5         | 0.81%   |
| ADATA Technology             | 5         | 0.81%   |
| Phison Electronics           | 4         | 0.65%   |
| Nvidia                       | 4         | 0.65%   |
| Silicon Motion               | 3         | 0.49%   |
| Union Memory (Shenzhen)      | 1         | 0.16%   |
| Seagate Technology           | 1         | 0.16%   |
| Marvell Technology Group     | 1         | 0.16%   |
| Lite-On Technology           | 1         | 0.16%   |
| Lenovo                       | 1         | 0.16%   |
| ASMedia Technology           | 1         | 0.16%   |
| Apple                        | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 46        | 7.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 40        | 6.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 38        | 5.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 33        | 5.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 23        | 3.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 23        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 23        | 3.55%   |
| Samsung NVMe Controller                                                          | 19        | 2.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 19        | 2.93%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 17        | 2.62%   |
| Intel Volume Management Device NVMe RAID Controller                              | 16        | 2.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 2.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 13        | 2.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 2.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 13        | 2.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 11        | 1.7%    |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 1.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 11        | 1.7%    |
| SK Hynix BC511                                                                   | 10        | 1.54%   |
| Micron Non-Volatile memory controller                                            | 10        | 1.54%   |
| KIOXIA Non-Volatile memory controller                                            | 10        | 1.54%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 10        | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 10        | 1.54%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 9         | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 1.39%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 8         | 1.23%   |
| SK Hynix NVMe SSD Controller                                                     | 8         | 1.23%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 7         | 1.08%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 7         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 7         | 1.08%   |
| Intel SSD 660P Series                                                            | 7         | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.08%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 6         | 0.93%   |
| SK Hynix Non-Volatile memory controller                                          | 6         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 0.77%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 0.62%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.46%   |
| Sandisk PC SN520 NVMe SSD                                                        | 3         | 0.46%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.46%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 0.46%   |
| Kingston Company A2000 NVMe SSD                                                  | 3         | 0.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.46%   |
| Intel Non-Volatile memory controller                                             | 3         | 0.46%   |
| ADATA Non-Volatile memory controller                                             | 3         | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.31%   |
| Samsung Electronics SATA controller                                              | 2         | 0.31%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 0.31%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.31%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.31%   |
| Intel SSD 600P Series                                                            | 2         | 0.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.31%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.31%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 0.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 354       | 55.75%  |
| NVMe | 209       | 32.91%  |
| RAID | 50        | 7.87%   |
| IDE  | 22        | 3.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 421       | 82.87%  |
| AMD    | 87        | 17.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 14        | 2.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 2.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 2.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 2.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 1.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 1.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 1.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 1.38%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 1.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 1.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.18%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 1.18%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 1.18%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 6         | 1.18%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 1.18%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.98%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 0.98%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 5         | 0.98%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 0.98%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.98%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.79%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.79%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 4         | 0.79%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 3         | 0.59%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.59%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.59%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 0.59%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.59%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 3         | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.59%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.59%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.59%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 3         | 0.59%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.59%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 0.59%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 3         | 0.59%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 3         | 0.59%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.59%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 3         | 0.59%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.59%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.59%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.39%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.39%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.39%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 2         | 0.39%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz              | 2         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 133       | 26.18%  |
| Intel Core i5                  | 127       | 25%     |
| Intel Core i3                  | 43        | 8.46%   |
| Other                          | 33        | 6.5%    |
| Intel Core 2 Duo               | 26        | 5.12%   |
| Intel Celeron                  | 22        | 4.33%   |
| AMD Ryzen 7                    | 19        | 3.74%   |
| AMD Ryzen 5                    | 18        | 3.54%   |
| Intel Pentium                  | 16        | 3.15%   |
| Intel Atom                     | 11        | 2.17%   |
| AMD Ryzen 7 PRO                | 7         | 1.38%   |
| AMD Ryzen 9                    | 6         | 1.18%   |
| AMD Athlon                     | 6         | 1.18%   |
| AMD Ryzen 3                    | 5         | 0.98%   |
| AMD A10                        | 5         | 0.98%   |
| AMD A6                         | 4         | 0.79%   |
| Intel Pentium Silver           | 3         | 0.59%   |
| Intel Pentium Dual-Core        | 3         | 0.59%   |
| AMD E                          | 3         | 0.59%   |
| AMD A8                         | 3         | 0.59%   |
| Intel Pentium Dual             | 2         | 0.39%   |
| Intel Core i9                  | 2         | 0.39%   |
| Intel Core 2                   | 2         | 0.39%   |
| AMD E1                         | 2         | 0.39%   |
| Intel Core m7                  | 1         | 0.2%    |
| Intel Core M                   | 1         | 0.2%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.2%    |
| AMD PRO A10                    | 1         | 0.2%    |
| AMD Athlon X2                  | 1         | 0.2%    |
| AMD Athlon II Dual-Core        | 1         | 0.2%    |
| AMD A12                        | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 248       | 48.82%  |
| 4      | 180       | 35.43%  |
| 6      | 46        | 9.06%   |
| 8      | 31        | 6.1%    |
| 1      | 2         | 0.39%   |
| 3      | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 508       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 397       | 78.15%  |
| 1      | 111       | 21.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 508       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 263       | 51.27%  |
| 0x806ec    | 23        | 4.48%   |
| 0x806c1    | 21        | 4.09%   |
| 0x806ea    | 19        | 3.7%    |
| 0x306a9    | 16        | 3.12%   |
| 0xa0652    | 14        | 2.73%   |
| 0x08600104 | 11        | 2.14%   |
| 0x206a7    | 10        | 1.95%   |
| 0x906ea    | 9         | 1.75%   |
| 0x806e9    | 9         | 1.75%   |
| 0x706e5    | 9         | 1.75%   |
| 0x406e3    | 8         | 1.56%   |
| 0x306d4    | 8         | 1.56%   |
| 0x08600106 | 7         | 1.36%   |
| 0x306c3    | 6         | 1.17%   |
| 0x08600103 | 6         | 1.17%   |
| 0x08108109 | 6         | 1.17%   |
| 0x906e9    | 5         | 0.97%   |
| 0x806eb    | 5         | 0.97%   |
| 0x1067a    | 5         | 0.97%   |
| 0x406c4    | 4         | 0.78%   |
| 0x40651    | 4         | 0.78%   |
| 0x30678    | 4         | 0.78%   |
| 0x0a50000b | 4         | 0.78%   |
| 0x806d1    | 3         | 0.58%   |
| 0x0a50000c | 3         | 0.58%   |
| 0x06006705 | 3         | 0.58%   |
| 0x706a1    | 2         | 0.39%   |
| 0x506e3    | 2         | 0.39%   |
| 0x20655    | 2         | 0.39%   |
| 0x106e5    | 2         | 0.39%   |
| 0x08200103 | 2         | 0.39%   |
| 0x08108102 | 2         | 0.39%   |
| 0x05000119 | 2         | 0.39%   |
| 0x906ed    | 1         | 0.19%   |
| 0x706a8    | 1         | 0.19%   |
| 0x6fd      | 1         | 0.19%   |
| 0x406c3    | 1         | 0.19%   |
| 0x30673    | 1         | 0.19%   |
| 0x20652    | 1         | 0.19%   |
| 0x08608103 | 1         | 0.19%   |
| 0x08608102 | 1         | 0.19%   |
| 0x0810100b | 1         | 0.19%   |
| 0x07030106 | 1         | 0.19%   |
| 0x07030105 | 1         | 0.19%   |
| 0x06006704 | 1         | 0.19%   |
| 0x06006110 | 1         | 0.19%   |
| 0x02000032 | 1         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 118       | 23.23%  |
| Haswell         | 39        | 7.68%   |
| IvyBridge       | 38        | 7.48%   |
| SandyBridge     | 34        | 6.69%   |
| Zen 2           | 29        | 5.71%   |
| TigerLake       | 26        | 5.12%   |
| Silvermont      | 24        | 4.72%   |
| Westmere        | 23        | 4.53%   |
| Skylake         | 21        | 4.13%   |
| Penryn          | 21        | 4.13%   |
| CometLake       | 19        | 3.74%   |
| IceLake         | 17        | 3.35%   |
| Broadwell       | 16        | 3.15%   |
| Zen+            | 14        | 2.76%   |
| Core            | 12        | 2.36%   |
| Zen 3           | 11        | 2.17%   |
| Excavator       | 8         | 1.57%   |
| Goldmont plus   | 6         | 1.18%   |
| Piledriver      | 5         | 0.98%   |
| Zen             | 4         | 0.79%   |
| Bobcat          | 4         | 0.79%   |
| Unknown         | 4         | 0.79%   |
| Puma            | 3         | 0.59%   |
| Nehalem         | 3         | 0.59%   |
| K8 & K10 hybrid | 2         | 0.39%   |
| Goldmont        | 2         | 0.39%   |
| K8 Hammer       | 1         | 0.2%    |
| K10 Llano       | 1         | 0.2%    |
| K10             | 1         | 0.2%    |
| Jaguar          | 1         | 0.2%    |
| Bonnell         | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 379       | 58.67%  |
| Nvidia | 154       | 23.84%  |
| AMD    | 113       | 17.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 36        | 5.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 4.55%   |
| AMD Renoir                                                                               | 28        | 4.25%   |
| Intel UHD Graphics 620                                                                   | 27        | 4.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 3.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 3.49%   |
| Intel HD Graphics 620                                                                    | 21        | 3.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 3.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 2.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 2.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 2.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 2.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 2.43%   |
| AMD Picasso                                                                              | 16        | 2.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 2.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.82%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 1.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 1.52%   |
| AMD Cezanne                                                                              | 10        | 1.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 1.06%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 1.06%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.91%   |
| Nvidia GP108M [GeForce MX250]                                                            | 5         | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.76%   |
| Intel HD Graphics 630                                                                    | 5         | 0.76%   |
| Intel HD Graphics 530                                                                    | 5         | 0.76%   |
| Nvidia TU117M                                                                            | 4         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.61%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.61%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.61%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.61%   |
| Nvidia GP108M [GeForce MX230]                                                            | 3         | 0.46%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 3         | 0.46%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.46%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.46%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 3         | 0.46%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.46%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.46%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 3         | 0.46%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.46%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 0.46%   |
| AMD Lucienne                                                                             | 3         | 0.46%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.3%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.3%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.3%    |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.3%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.3%    |
| Nvidia GT216M [GeForce GT 320M]                                                          | 2         | 0.3%    |
| Nvidia GP107M [GeForce MX350]                                                            | 2         | 0.3%    |
| Nvidia GP107GLM [Quadro P620]                                                            | 2         | 0.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 258       | 50.79%  |
| Intel + Nvidia | 105       | 20.67%  |
| 1 x AMD        | 74        | 14.57%  |
| 1 x Nvidia     | 32        | 6.3%    |
| AMD + Nvidia   | 17        | 3.35%   |
| Intel + AMD    | 16        | 3.15%   |
| 2 x AMD        | 6         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 428       | 84.09%  |
| Proprietary | 75        | 14.73%  |
| Unknown     | 6         | 1.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 382       | 74.61%  |
| 1.01-2.0   | 37        | 7.23%   |
| 0.01-0.5   | 33        | 6.45%   |
| 3.01-4.0   | 26        | 5.08%   |
| 5.01-6.0   | 16        | 3.13%   |
| 0.51-1.0   | 11        | 2.15%   |
| 7.01-8.0   | 5         | 0.98%   |
| 2.01-3.0   | 1         | 0.2%    |
| 8.01-16.0  | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 122       | 20.68%  |
| LG Display              | 82        | 13.9%   |
| Chimei Innolux          | 74        | 12.54%  |
| BOE                     | 68        | 11.53%  |
| Samsung Electronics     | 55        | 9.32%   |
| Sharp                   | 26        | 4.41%   |
| Dell                    | 19        | 3.22%   |
| Goldstar                | 15        | 2.54%   |
| Chi Mei Optoelectronics | 14        | 2.37%   |
| Hewlett-Packard         | 13        | 2.2%    |
| Apple                   | 13        | 2.2%    |
| Acer                    | 12        | 2.03%   |
| Lenovo                  | 11        | 1.86%   |
| PANDA                   | 8         | 1.36%   |
| Unknown                 | 5         | 0.85%   |
| Philips                 | 5         | 0.85%   |
| BenQ                    | 5         | 0.85%   |
| LG Philips              | 3         | 0.51%   |
| InfoVision              | 3         | 0.51%   |
| CSO                     | 3         | 0.51%   |
| ASUSTek Computer        | 3         | 0.51%   |
| Ancor Communications    | 3         | 0.51%   |
| Sony                    | 2         | 0.34%   |
| LGD                     | 2         | 0.34%   |
| JDI                     | 2         | 0.34%   |
| Iiyama                  | 2         | 0.34%   |
| CHR                     | 2         | 0.34%   |
| Vizio                   | 1         | 0.17%   |
| ViewSonic               | 1         | 0.17%   |
| Unknown (XXX)           | 1         | 0.17%   |
| Toshiba                 | 1         | 0.17%   |
| TIANMA XM               | 1         | 0.17%   |
| SGT                     | 1         | 0.17%   |
| Sceptre Tech            | 1         | 0.17%   |
| Sanyo                   | 1         | 0.17%   |
| S2-Tek                  | 1         | 0.17%   |
| Panasonic               | 1         | 0.17%   |
| Nvidia                  | 1         | 0.17%   |
| MiTAC                   | 1         | 0.17%   |
| Hitachi                 | 1         | 0.17%   |
| HannStar                | 1         | 0.17%   |
| Denver                  | 1         | 0.17%   |
| Cbox                    | 1         | 0.17%   |
| BOE Technology Group    | 1         | 0.17%   |
| AOC                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 1.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 1.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 5         | 0.84%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 4         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 4         | 0.67%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.67%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 3         | 0.5%    |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 3         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 3         | 0.5%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 3         | 0.5%    |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                  | 2         | 0.34%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.34%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch                  | 2         | 0.34%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch    | 2         | 0.34%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                  | 2         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.34%   |
| LG Philips LCD Monitor LPL0301 1280x800 331x207mm 15.4-inch              | 2         | 0.34%   |
| LG Display LP156WH2-TLBA LGD026C 1366x768 344x194mm 15.5-inch            | 2         | 0.34%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 2         | 0.34%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch             | 2         | 0.34%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.34%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD03EE 1366x768 277x156mm 12.5-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 2         | 0.34%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.34%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch                  | 2         | 0.34%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                    | 2         | 0.34%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.34%   |
| CHR AIO-21.5"-10 CHR7511 1920x1080 476x268mm 21.5-inch                   | 2         | 0.34%   |
| Chimei Innolux P130ZDZ-EF1 CMN8201 2160x1440 275x183mm 13.0-inch         | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch         | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 350x190mm 15.7-inch          | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1409 1920x1080 309x173mm 13.9-inch         | 2         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.34%   |
| BOE LCD Monitor BOE08E4 1600x900 382x215mm 17.3-inch                     | 2         | 0.34%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                    | 2         | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.34%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                    | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 250       | 45.7%   |
| 1366x768 (WXGA)    | 146       | 26.69%  |
| 1600x900 (HD+)     | 33        | 6.03%   |
| 3840x2160 (4K)     | 22        | 4.02%   |
| 1280x800 (WXGA)    | 17        | 3.11%   |
| 2560x1440 (QHD)    | 15        | 2.74%   |
| 1440x900 (WXGA+)   | 10        | 1.83%   |
| 1920x1200 (WUXGA)  | 8         | 1.46%   |
| 2560x1600          | 5         | 0.91%   |
| 1280x1024 (SXGA)   | 5         | 0.91%   |
| 3440x1440          | 4         | 0.73%   |
| Unknown            | 4         | 0.73%   |
| 3000x2000          | 3         | 0.55%   |
| 2160x1440          | 3         | 0.55%   |
| 3456x2160          | 2         | 0.37%   |
| 3200x1800 (QHD+)   | 2         | 0.37%   |
| 1920x1280          | 2         | 0.37%   |
| 1360x768           | 2         | 0.37%   |
| 5760x2160          | 1         | 0.18%   |
| 3840x2400          | 1         | 0.18%   |
| 3840x1200          | 1         | 0.18%   |
| 3520x1080          | 1         | 0.18%   |
| 3280x1050          | 1         | 0.18%   |
| 2880x1800          | 1         | 0.18%   |
| 2560x1080          | 1         | 0.18%   |
| 2304x1440          | 1         | 0.18%   |
| 2256x1504          | 1         | 0.18%   |
| 1920x540           | 1         | 0.18%   |
| 1680x1050 (WSXGA+) | 1         | 0.18%   |
| 1600x1200          | 1         | 0.18%   |
| 1280x768           | 1         | 0.18%   |
| 1024x600           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 236       | 40.07%  |
| 13      | 82        | 13.92%  |
| 14      | 73        | 12.39%  |
| 17      | 44        | 7.47%   |
| 23      | 24        | 4.07%   |
| 24      | 20        | 3.4%    |
| 21      | 18        | 3.06%   |
| 27      | 16        | 2.72%   |
| 12      | 14        | 2.38%   |
| 11      | 12        | 2.04%   |
| Unknown | 11        | 1.87%   |
| 19      | 8         | 1.36%   |
| 31      | 6         | 1.02%   |
| 16      | 6         | 1.02%   |
| 34      | 5         | 0.85%   |
| 84      | 2         | 0.34%   |
| 40      | 2         | 0.34%   |
| 54      | 1         | 0.17%   |
| 49      | 1         | 0.17%   |
| 48      | 1         | 0.17%   |
| 43      | 1         | 0.17%   |
| 42      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |
| 22      | 1         | 0.17%   |
| 20      | 1         | 0.17%   |
| 18      | 1         | 0.17%   |
| 10      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 345       | 58.77%  |
| 201-300     | 70        | 11.93%  |
| 501-600     | 56        | 9.54%   |
| 351-400     | 56        | 9.54%   |
| 401-500     | 26        | 4.43%   |
| Unknown     | 11        | 1.87%   |
| 601-700     | 8         | 1.36%   |
| 701-800     | 6         | 1.02%   |
| 801-900     | 3         | 0.51%   |
| 1001-1500   | 3         | 0.51%   |
| 1501-2000   | 2         | 0.34%   |
| 901-1000    | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 431       | 84.84%  |
| 16/10   | 46        | 9.06%   |
| 3/2     | 10        | 1.97%   |
| Unknown | 8         | 1.57%   |
| 5/4     | 5         | 0.98%   |
| 21/9    | 5         | 0.98%   |
| 4/3     | 2         | 0.39%   |
| 32/9    | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 238       | 40.61%  |
| 81-90          | 124       | 21.16%  |
| 201-250        | 52        | 8.87%   |
| 121-130        | 41        | 7%      |
| 71-80          | 30        | 5.12%   |
| 301-350        | 16        | 2.73%   |
| 61-70          | 14        | 2.39%   |
| 51-60          | 12        | 2.05%   |
| 351-500        | 12        | 2.05%   |
| 151-200        | 12        | 2.05%   |
| Unknown        | 11        | 1.88%   |
| More than 1000 | 5         | 0.85%   |
| 251-300        | 5         | 0.85%   |
| 501-1000       | 4         | 0.68%   |
| 111-120        | 3         | 0.51%   |
| 141-150        | 2         | 0.34%   |
| 131-140        | 2         | 0.34%   |
| 91-100         | 2         | 0.34%   |
| 41-50          | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 236       | 40.97%  |
| 101-120       | 159       | 27.6%   |
| 51-100        | 99        | 17.19%  |
| 161-240       | 42        | 7.29%   |
| More than 240 | 24        | 4.17%   |
| Unknown       | 11        | 1.91%   |
| 1-50          | 5         | 0.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 388       | 75.93%  |
| 2     | 95        | 18.59%  |
| 0     | 17        | 3.33%   |
| 3     | 10        | 1.96%   |
| 4     | 1         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 281       | 35.52%  |
| Realtek Semiconductor             | 254       | 32.11%  |
| Qualcomm Atheros                  | 112       | 14.16%  |
| Broadcom                          | 54        | 6.83%   |
| Marvell Technology Group          | 13        | 1.64%   |
| Broadcom Limited                  | 12        | 1.52%   |
| Ralink                            | 6         | 0.76%   |
| Hewlett-Packard                   | 6         | 0.76%   |
| TP-Link                           | 5         | 0.63%   |
| MEDIATEK                          | 5         | 0.63%   |
| JMicron Technology                | 5         | 0.63%   |
| Samsung Electronics               | 4         | 0.51%   |
| Lenovo                            | 4         | 0.51%   |
| Dell                              | 4         | 0.51%   |
| Ericsson Business Mobile Networks | 3         | 0.38%   |
| U-Blox                            | 2         | 0.25%   |
| Ralink Technology                 | 2         | 0.25%   |
| NetGear                           | 2         | 0.25%   |
| Edimax Technology                 | 2         | 0.25%   |
| DisplayLink                       | 2         | 0.25%   |
| Xiaomi                            | 1         | 0.13%   |
| Sierra Wireless                   | 1         | 0.13%   |
| Qualcomm Atheros Communications   | 1         | 0.13%   |
| Nvidia                            | 1         | 0.13%   |
| Motorola PCS                      | 1         | 0.13%   |
| ICS Advent                        | 1         | 0.13%   |
| Huawei Technologies               | 1         | 0.13%   |
| Google                            | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| ASUSTek Computer                  | 1         | 0.13%   |
| ASIX Electronics                  | 1         | 0.13%   |
| Arduino SA                        | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 167       | 17.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 4.16%   |
| Intel Wi-Fi 6 AX200                                               | 35        | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 2.56%   |
| Intel Wi-Fi 6 AX201                                               | 22        | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 21        | 2.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 2.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 20        | 2.13%   |
| Intel Wireless 7265                                               | 20        | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 18        | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 16        | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.49%   |
| Intel Wireless 7260                                               | 14        | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 14        | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 12        | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                     | 11        | 1.17%   |
| Intel Wireless 8260                                               | 9         | 0.96%   |
| Intel Wireless 3160                                               | 9         | 0.96%   |
| Intel Wireless-AC 9260                                            | 8         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 0.85%   |
| Intel Wireless 3165                                               | 7         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.75%   |
| Intel Centrino Advanced-N 6235                                    | 7         | 0.75%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.53%   |
| MEDIATEK Network controller                                       | 5         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 5         | 0.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.43%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.43%   |
| Intel WiFi Link 5100                                              | 4         | 0.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.43%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.43%   |
| HP HP lt4120 Snapdragon X5 LTE                                    | 4         | 0.43%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.43%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.32%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.32%   |
| Realtek Realtek Network controller                                | 3         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 266       | 52.05%  |
| Qualcomm Atheros                  | 102       | 19.96%  |
| Realtek Semiconductor             | 61        | 11.94%  |
| Broadcom                          | 47        | 9.2%    |
| Broadcom Limited                  | 9         | 1.76%   |
| Ralink                            | 6         | 1.17%   |
| MEDIATEK                          | 5         | 0.98%   |
| Ralink Technology                 | 2         | 0.39%   |
| Edimax Technology                 | 2         | 0.39%   |
| Dell                              | 2         | 0.39%   |
| TP-Link                           | 1         | 0.2%    |
| Sierra Wireless                   | 1         | 0.2%    |
| Qualcomm Atheros Communications   | 1         | 0.2%    |
| NetGear                           | 1         | 0.2%    |
| Hewlett-Packard                   | 1         | 0.2%    |
| Fibocom                           | 1         | 0.2%    |
| Ericsson Business Mobile Networks | 1         | 0.2%    |
| D-Link                            | 1         | 0.2%    |
| ASUSTek Computer                  | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 35        | 6.81%   |
| Intel Wi-Fi 6 AX201                                            | 22        | 4.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 21        | 4.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 21        | 4.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 20        | 3.89%   |
| Intel Wireless 7265                                            | 20        | 3.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 3.5%    |
| Intel Wireless 8265 / 8275                                     | 18        | 3.5%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 3.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 3.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 16        | 3.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 2.72%   |
| Intel Wireless 7260                                            | 14        | 2.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 14        | 2.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 2.14%   |
| Broadcom BCM43142 802.11b/g/n                                  | 11        | 2.14%   |
| Intel Wireless 8260                                            | 9         | 1.75%   |
| Intel Wireless 3160                                            | 9         | 1.75%   |
| Intel Wireless-AC 9260                                         | 8         | 1.56%   |
| Intel Wireless 3165                                            | 7         | 1.36%   |
| Intel Centrino Advanced-N 6235                                 | 7         | 1.36%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 0.97%   |
| MEDIATEK Network controller                                    | 5         | 0.97%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 0.78%   |
| Intel WiFi Link 5100                                           | 4         | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 0.58%   |
| Realtek Realtek Network controller                             | 3         | 0.58%   |
| Realtek 802.11ac NIC                                           | 3         | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.58%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 3         | 0.58%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 0.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.39%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.39%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 2         | 0.39%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.39%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 0.39%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 0.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.19%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                | 1         | 0.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 226       | 54.85%  |
| Intel                    | 100       | 24.27%  |
| Qualcomm Atheros         | 23        | 5.58%   |
| Broadcom                 | 16        | 3.88%   |
| Marvell Technology Group | 13        | 3.16%   |
| JMicron Technology       | 5         | 1.21%   |
| TP-Link                  | 4         | 0.97%   |
| Samsung Electronics      | 4         | 0.97%   |
| Lenovo                   | 4         | 0.97%   |
| Hewlett-Packard          | 4         | 0.97%   |
| Broadcom Limited         | 3         | 0.73%   |
| DisplayLink              | 2         | 0.49%   |
| Xiaomi                   | 1         | 0.24%   |
| Nvidia                   | 1         | 0.24%   |
| NetGear                  | 1         | 0.24%   |
| Motorola PCS             | 1         | 0.24%   |
| ICS Advent               | 1         | 0.24%   |
| Huawei Technologies      | 1         | 0.24%   |
| Google                   | 1         | 0.24%   |
| ASIX Electronics         | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 167       | 40.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 39        | 9.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 24        | 5.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 17        | 4.1%    |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 1.93%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 1.69%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 1.69%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 1.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 6         | 1.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 5         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.2%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 4         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 4         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 0.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 0.96%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 0.96%   |
| HP HP lt4120 Snapdragon X5 LTE                                                 | 4         | 0.96%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 3         | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 0.72%   |
| Lenovo ThinkPad Lan                                                            | 3         | 0.72%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.72%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.48%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.48%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.48%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.48%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.24%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.24%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.24%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.24%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.24%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.24%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.24%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.24%   |
| NetGear LB1120-100NAS                                                          | 1         | 0.24%   |
| Motorola PCS Moto G Play                                                       | 1         | 0.24%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.24%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1         | 0.24%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.24%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.24%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.24%   |
| Intel Ethernet controller                                                      | 1         | 0.24%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.24%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.24%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.24%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 495       | 55.31%  |
| Ethernet | 392       | 43.8%   |
| Modem    | 8         | 0.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 430       | 69.69%  |
| Ethernet | 187       | 30.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 360       | 70.87%  |
| 1     | 137       | 26.97%  |
| 0     | 8         | 1.57%   |
| 3     | 3         | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 385       | 75.64%  |
| Yes  | 124       | 24.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 214       | 52.07%  |
| Qualcomm Atheros Communications | 44        | 10.71%  |
| Realtek Semiconductor           | 35        | 8.52%   |
| Broadcom                        | 25        | 6.08%   |
| IMC Networks                    | 14        | 3.41%   |
| Apple                           | 14        | 3.41%   |
| Lite-On Technology              | 11        | 2.68%   |
| Foxconn / Hon Hai               | 11        | 2.68%   |
| Dell                            | 10        | 2.43%   |
| Realtek                         | 7         | 1.7%    |
| Cambridge Silicon Radio         | 7         | 1.7%    |
| Hewlett-Packard                 | 5         | 1.22%   |
| Ralink                          | 4         | 0.97%   |
| ASUSTek Computer                | 3         | 0.73%   |
| Alps Electric                   | 3         | 0.73%   |
| Foxconn International           | 2         | 0.49%   |
| Toshiba                         | 1         | 0.24%   |
| Askey Computer                  | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 81        | 19.71%  |
| Intel Bluetooth wireless interface                                                  | 49        | 11.92%  |
| Intel AX200 Bluetooth                                                               | 35        | 8.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 34        | 8.27%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 21        | 5.11%   |
| Realtek Bluetooth Radio                                                             | 19        | 4.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 2.92%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 2.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 8         | 1.95%   |
| Realtek Bluetooth Radio                                                             | 7         | 1.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 1.7%    |
| Apple Bluetooth USB Host Controller                                                 | 7         | 1.7%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.46%   |
| Apple Bluetooth Host Controller                                                     | 6         | 1.46%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.22%   |
| Realtek 802.11ac WLAN Adapter                                                       | 4         | 0.97%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 0.97%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.97%   |
| IMC Networks Wireless_Device                                                        | 4         | 0.97%   |
| IMC Networks Bluetooth Device                                                       | 4         | 0.97%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.97%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.73%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.73%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.73%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.73%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.73%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.49%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.49%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.49%   |
| Dell BCM20702A0                                                                     | 2         | 0.49%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.49%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.49%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 2         | 0.49%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.24%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.24%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.24%   |
| Lite-On Wireless_Device                                                             | 1         | 0.24%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.24%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.24%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.24%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 1         | 0.24%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.24%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.24%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.24%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.24%   |
| Broadcom BCM20703A1 Bluetooth 4.1 + LE                                              | 1         | 0.24%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.24%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.24%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.24%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.24%   |
| Askey Bluetooth Device                                                              | 1         | 0.24%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 408       | 66.89%  |
| AMD                                             | 99        | 16.23%  |
| Nvidia                                          | 73        | 11.97%  |
| C-Media Electronics                             | 5         | 0.82%   |
| Sennheiser Communications                       | 2         | 0.33%   |
| Logitech                                        | 2         | 0.33%   |
| Lenovo                                          | 2         | 0.33%   |
| Focusrite-Novation                              | 2         | 0.33%   |
| Creative Technology                             | 2         | 0.33%   |
| Texas Instruments                               | 1         | 0.16%   |
| SteelSeries ApS                                 | 1         | 0.16%   |
| Samson Technologies                             | 1         | 0.16%   |
| RODE Microphones                                | 1         | 0.16%   |
| Realtek Semiconductor                           | 1         | 0.16%   |
| No brand                                        | 1         | 0.16%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.16%   |
| JMTek                                           | 1         | 0.16%   |
| GN Netcom                                       | 1         | 0.16%   |
| Elitegroup Computer Systems (ECS)               | 1         | 0.16%   |
| Dell                                            | 1         | 0.16%   |
| Corsair                                         | 1         | 0.16%   |
| CMX Systems                                     | 1         | 0.16%   |
| Astro Gaming                                    | 1         | 0.16%   |
| Afatech                                         | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 65        | 8.76%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 61        | 8.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 44        | 5.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 35        | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 3.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 26        | 3.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 3.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 24        | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 24        | 3.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 2.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 2.83%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 2.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 19        | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 2.16%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 2.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.62%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 1.08%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 0.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.67%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.54%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.54%   |
| Nvidia Audio device                                                                               | 4         | 0.54%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.4%    |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.4%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.4%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.4%    |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.27%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.27%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.27%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.27%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.27%   |
| C-Media Electronics CM108 Audio Controller                                                        | 2         | 0.27%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.27%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.27%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.27%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.13%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                                     | 1         | 0.13%   |
| Sennheiser Communications Headset [PC 8]                                                          | 1         | 0.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 104       | 31.9%   |
| SK Hynix            | 80        | 24.54%  |
| Micron Technology   | 39        | 11.96%  |
| Kingston            | 34        | 10.43%  |
| Unknown             | 19        | 5.83%   |
| Crucial             | 12        | 3.68%   |
| ELPIDA              | 5         | 1.53%   |
| A-DATA Technology   | 5         | 1.53%   |
| Smart               | 4         | 1.23%   |
| Nanya Technology    | 4         | 1.23%   |
| Unknown (ABCD)      | 3         | 0.92%   |
| Ramaxel Technology  | 3         | 0.92%   |
| G.Skill             | 3         | 0.92%   |
| Corsair             | 3         | 0.92%   |
| Transcend           | 2         | 0.61%   |
| Team                | 2         | 0.61%   |
| Unknown (08AE)      | 1         | 0.31%   |
| Smart Modular       | 1         | 0.31%   |
| High Bridge         | 1         | 0.31%   |
| GOODRAM             | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 8         | 2.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.76%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 1.76%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 5         | 1.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 1.47%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.17%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s         | 4         | 1.17%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 4         | 1.17%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 1.17%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.17%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.88%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.88%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.88%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.88%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 0.88%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 3         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.88%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 3         | 0.88%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.59%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 2         | 0.59%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.59%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.59%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 2         | 0.59%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 2         | 0.59%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.59%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.59%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.59%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.59%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.59%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.59%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.59%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.59%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.59%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 2         | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.59%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 2         | 0.59%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.59%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.59%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 2         | 0.59%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 0.59%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s          | 2         | 0.59%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.59%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s            | 2         | 0.59%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.59%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s          | 2         | 0.59%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2048MB SODIMM DDR3 1334MT/s         | 2         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 163       | 58.21%  |
| DDR3   | 75        | 26.79%  |
| LPDDR3 | 20        | 7.14%   |
| LPDDR4 | 15        | 5.36%   |
| DDR2   | 6         | 2.14%   |
| SDRAM  | 1         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 237       | 84.04%  |
| Row Of Chips | 43        | 15.25%  |
| DIMM         | 2         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 120       | 40.27%  |
| 4096  | 90        | 30.2%   |
| 16384 | 48        | 16.11%  |
| 2048  | 27        | 9.06%   |
| 32768 | 8         | 2.68%   |
| 1024  | 5         | 1.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 80        | 26.58%  |
| 3200    | 70        | 23.26%  |
| 1600    | 53        | 17.61%  |
| 2133    | 24        | 7.97%   |
| 2400    | 20        | 6.64%   |
| 1334    | 13        | 4.32%   |
| 1333    | 10        | 3.32%   |
| 4267    | 9         | 2.99%   |
| 1867    | 7         | 2.33%   |
| 800     | 5         | 1.66%   |
| Unknown | 3         | 1%      |
| 975     | 2         | 0.66%   |
| 4266    | 1         | 0.33%   |
| 2048    | 1         | 0.33%   |
| 1777    | 1         | 0.33%   |
| 1066    | 1         | 0.33%   |
| 533     | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-4100 Series | 1         | 33.33%  |
| HP LaserJet M101-M106      | 1         | 33.33%  |
| Canon PIXMA TS6250         | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1         | 50%     |
| Canon CanoScan LiDE 600F              | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 118       | 25.99%  |
| IMC Networks                           | 50        | 11.01%  |
| Realtek Semiconductor                  | 44        | 9.69%   |
| Microdia                               | 44        | 9.69%   |
| Acer                                   | 28        | 6.17%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 5.95%   |
| Quanta                                 | 23        | 5.07%   |
| Sunplus Innovation Technology          | 21        | 4.63%   |
| Suyin                                  | 15        | 3.3%    |
| Lite-On Technology                     | 15        | 3.3%    |
| Silicon Motion                         | 11        | 2.42%   |
| Apple                                  | 11        | 2.42%   |
| Ricoh                                  | 7         | 1.54%   |
| Syntek                                 | 6         | 1.32%   |
| Luxvisions Innotech Limited            | 6         | 1.32%   |
| Alcor Micro                            | 5         | 1.1%    |
| Samsung Electronics                    | 4         | 0.88%   |
| OmniVision Technologies                | 3         | 0.66%   |
| Logitech                               | 2         | 0.44%   |
| 8SSC20F27114V1SR11K1SE2                | 2         | 0.44%   |
| Unknown                                | 1         | 0.22%   |
| Trust                                  | 1         | 0.22%   |
| Sunplus Technology                     | 1         | 0.22%   |
| Primax Electronics                     | 1         | 0.22%   |
| Pixart Imaging                         | 1         | 0.22%   |
| OPPO Electronics                       | 1         | 0.22%   |
| LG Electronics                         | 1         | 0.22%   |
| Lenovo                                 | 1         | 0.22%   |
| kingcome                               | 1         | 0.22%   |
| Importek                               | 1         | 0.22%   |
| Huawei Technologies                    | 1         | 0.22%   |
| ARC International                      | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 28        | 6.17%   |
| Chicony Integrated Camera                           | 24        | 5.29%   |
| Realtek Integrated_Webcam_HD                        | 23        | 5.07%   |
| IMC Networks Integrated Camera                      | 20        | 4.41%   |
| Chicony HD WebCam                                   | 13        | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 2.64%   |
| Quanta HD User Facing                               | 9         | 1.98%   |
| Realtek USB Camera                                  | 7         | 1.54%   |
| Chicony HP HD Camera                                | 7         | 1.54%   |
| Acer Integrated Camera                              | 7         | 1.54%   |
| Lite-On HP HD Camera                                | 6         | 1.32%   |
| Chicony USB 2.0 Camera                              | 6         | 1.32%   |
| Sunplus Integrated_Webcam_HD                        | 5         | 1.1%    |
| Quanta HP TrueVision HD Camera                      | 5         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.1%    |
| Chicony USB2.0 Camera                               | 5         | 1.1%    |
| Chicony Integrated HP HD Webcam                     | 5         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 5         | 1.1%    |
| Samsung Galaxy A5 (MTP)                             | 4         | 0.88%   |
| IMC Networks Integrated Webcam                      | 4         | 0.88%   |
| Chicony HP Wide Vision HD Camera                    | 4         | 0.88%   |
| Chicony HP Truevision HD                            | 4         | 0.88%   |
| Chicony FJ Camera                                   | 4         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 4         | 0.88%   |
| Acer SunplusIT Integrated Camera                    | 4         | 0.88%   |
| Acer Lenovo EasyCamera                              | 4         | 0.88%   |
| Acer BisonCam, NB Pro                               | 4         | 0.88%   |
| Syntek Integrated Camera                            | 3         | 0.66%   |
| Suyin 1.3M HD WebCam                                | 3         | 0.66%   |
| Realtek USB2.0 HD UVC WebCam                        | 3         | 0.66%   |
| Realtek Lenovo EasyCamera                           | 3         | 0.66%   |
| Quanta HD Webcam                                    | 3         | 0.66%   |
| Lite-On Integrated Camera                           | 3         | 0.66%   |
| Lite-On HP HD Webcam                                | 3         | 0.66%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 0.66%   |
| Chicony VGA Webcam                                  | 3         | 0.66%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 0.66%   |
| Chicony Lenovo EasyCamera                           | 3         | 0.66%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.66%   |
| Chicony HD User Facing                              | 3         | 0.66%   |
| Chicony EasyCamera                                  | 3         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 3         | 0.66%   |
| Apple FaceTime HD Camera                            | 3         | 0.66%   |
| Apple Built-in iSight                               | 3         | 0.66%   |
| Syntek EasyCamera                                   | 2         | 0.44%   |
| Sunplus Laptop Integrated Webcam FHD                | 2         | 0.44%   |
| Sunplus HP HD Webcam [Fixed]                        | 2         | 0.44%   |
| Sunplus HD WebCam                                   | 2         | 0.44%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 0.44%   |
| Ricoh Sony Vaio Integrated Webcam                   | 2         | 0.44%   |
| Ricoh Integrated Webcam                             | 2         | 0.44%   |
| Quanta ov9734_techfront_camera                      | 2         | 0.44%   |
| OmniVision OV2640 Webcam                            | 2         | 0.44%   |
| Microdia Webcam Vitade AF                           | 2         | 0.44%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.44%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 2         | 0.44%   |
| Microdia Integrated Webcam                          | 2         | 0.44%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.44%   |
| Luxvisions Innotech Limited HP HD Camera            | 2         | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 43        | 37.07%  |
| Synaptics                  | 31        | 26.72%  |
| Shenzhen Goodix Technology | 23        | 19.83%  |
| LighTuning Technology      | 7         | 6.03%   |
| Elan Microelectronics      | 5         | 4.31%   |
| AuthenTec                  | 4         | 3.45%   |
| STMicroelectronics         | 2         | 1.72%   |
| Upek                       | 1         | 0.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 20        | 17.24%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 10.34%  |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 9.48%   |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 7.76%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 4.31%   |
| Elan ELAN:Fingerprint                                                      | 5         | 4.31%   |
| Unknown                                                                    | 5         | 4.31%   |
| Validity Sensors VFS491                                                    | 4         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.59%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.59%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.59%   |
| Synaptics  WBDI                                                            | 3         | 2.59%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.59%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 2.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.59%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.72%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.72%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.72%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.86%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.86%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.86%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 0.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.86%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.86%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 17        | 43.59%  |
| Alcor Micro           | 14        | 35.9%   |
| Lenovo                | 2         | 5.13%   |
| Gemalto (was Gemplus) | 2         | 5.13%   |
| Upek                  | 1         | 2.56%   |
| O2 Micro              | 1         | 2.56%   |
| Clay Logic            | 1         | 2.56%   |
| Cherry                | 1         | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 35.9%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 15.38%  |
| Broadcom 58200                                                               | 5         | 12.82%  |
| Broadcom 5880                                                                | 4         | 10.26%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.13%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.13%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.56%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 2.56%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 303       | 59.18%  |
| 1     | 158       | 30.86%  |
| 2     | 44        | 8.59%   |
| 3     | 7         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 114       | 44.36%  |
| Graphics card         | 43        | 16.73%  |
| Net/wireless          | 36        | 14.01%  |
| Chipcard              | 35        | 13.62%  |
| Multimedia controller | 8         | 3.11%   |
| Storage               | 6         | 2.33%   |
| Bluetooth             | 5         | 1.95%   |
| Camera                | 4         | 1.56%   |
| Card reader           | 3         | 1.17%   |
| Sound                 | 1         | 0.39%   |
| Net/ethernet          | 1         | 0.39%   |
| Modem                 | 1         | 0.39%   |


Ubuntu 21.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.04.

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
| Dell          | Inspiron 5559               | [e646bde765](https://linux-hardware.org/?probe=e646bde765) | Sep 17, 2021 |
| ASUSTek       | N71Vg                       | [8e1fd4910a](https://linux-hardware.org/?probe=8e1fd4910a) | Sep 17, 2021 |
| Dell          | XPS 13 9310                 | [d374535153](https://linux-hardware.org/?probe=d374535153) | Sep 17, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [85cb48e026](https://linux-hardware.org/?probe=85cb48e026) | Sep 17, 2021 |
| HP            | Notebook                    | [f4ae81e712](https://linux-hardware.org/?probe=f4ae81e712) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | [670c2b0df7](https://linux-hardware.org/?probe=670c2b0df7) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | [134631220f](https://linux-hardware.org/?probe=134631220f) | Sep 16, 2021 |
| Acer          | Aspire A515-43              | [bf09dd7f40](https://linux-hardware.org/?probe=bf09dd7f40) | Sep 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4d4918a470](https://linux-hardware.org/?probe=4d4918a470) | Sep 15, 2021 |
| Apple         | MacBookPro9,2               | [8d085a9a13](https://linux-hardware.org/?probe=8d085a9a13) | Sep 15, 2021 |
| Toshiba       | TECRA A50-C                 | [1a625d3feb](https://linux-hardware.org/?probe=1a625d3feb) | Sep 15, 2021 |
| Acer          | Aspire 8730                 | [6e53b2cfa9](https://linux-hardware.org/?probe=6e53b2cfa9) | Sep 15, 2021 |
| ASUSTek       | U50Vg                       | [7d12a66551](https://linux-hardware.org/?probe=7d12a66551) | Sep 15, 2021 |
| Dell          | Inspiron 5570               | [218d153444](https://linux-hardware.org/?probe=218d153444) | Sep 15, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [c51f5529e4](https://linux-hardware.org/?probe=c51f5529e4) | Sep 15, 2021 |
| ASUSTek       | N552VX                      | [ca7b7f7df9](https://linux-hardware.org/?probe=ca7b7f7df9) | Sep 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [5fb084ffa4](https://linux-hardware.org/?probe=5fb084ffa4) | Sep 15, 2021 |
| ASUSTek       | N751JK                      | [9d34ea25cd](https://linux-hardware.org/?probe=9d34ea25cd) | Sep 14, 2021 |
| Dell          | Latitude 5290               | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad T450s 20BWZ0CKU... | [a9e206d41b](https://linux-hardware.org/?probe=a9e206d41b) | Sep 14, 2021 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [b193a554c5](https://linux-hardware.org/?probe=b193a554c5) | Sep 14, 2021 |
| Acer          | Swift SF314-43              | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| Advance       | AN-5431                     | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| Dell          | Latitude E7270              | [479b6d4aa9](https://linux-hardware.org/?probe=479b6d4aa9) | Sep 14, 2021 |
| Toshiba       | Satellite C55-C             | [8966b3a7b5](https://linux-hardware.org/?probe=8966b3a7b5) | Sep 14, 2021 |
| Notebook      | W54_55SU1,SUW               | [7d4ed6e466](https://linux-hardware.org/?probe=7d4ed6e466) | Sep 13, 2021 |
| Sony          | SVS1312G3EW                 | [0a315b4077](https://linux-hardware.org/?probe=0a315b4077) | Sep 13, 2021 |
| Sony          | SVS1312G3EW                 | [bee47d862e](https://linux-hardware.org/?probe=bee47d862e) | Sep 13, 2021 |
| Dell          | Latitude 7370               | [7b446e8905](https://linux-hardware.org/?probe=7b446e8905) | Sep 13, 2021 |
| Dell          | Latitude 7370               | [ec12323a7e](https://linux-hardware.org/?probe=ec12323a7e) | Sep 13, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [9624b39eea](https://linux-hardware.org/?probe=9624b39eea) | Sep 13, 2021 |
| HP            | Notebook                    | [9082e7207c](https://linux-hardware.org/?probe=9082e7207c) | Sep 13, 2021 |
| HP            | EliteBook 8470p             | [651fc72613](https://linux-hardware.org/?probe=651fc72613) | Sep 13, 2021 |
| ASUSTek       | U50Vg                       | [f5d7593025](https://linux-hardware.org/?probe=f5d7593025) | Sep 13, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Thomson       | WWNEO14A-2BK32              | [1423ee3d10](https://linux-hardware.org/?probe=1423ee3d10) | Sep 13, 2021 |
| Schenker      | XMG CORE (TGL/M21)          | [d1f9d8c10c](https://linux-hardware.org/?probe=d1f9d8c10c) | Sep 13, 2021 |
| Dell          | Precision 5540              | [2888ae8d0a](https://linux-hardware.org/?probe=2888ae8d0a) | Sep 13, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [c4f8c481e7](https://linux-hardware.org/?probe=c4f8c481e7) | Sep 13, 2021 |
| Dell          | Latitude 5400               | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | U50Vg                       | [8013b7cbcf](https://linux-hardware.org/?probe=8013b7cbcf) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f8ebf7eb90](https://linux-hardware.org/?probe=f8ebf7eb90) | Sep 13, 2021 |
| Dell          | XPS 13 9300                 | [d4ae821034](https://linux-hardware.org/?probe=d4ae821034) | Sep 12, 2021 |
| HP            | EliteBook 840 G1            | [1124d5133b](https://linux-hardware.org/?probe=1124d5133b) | Sep 12, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [0bba3925b9](https://linux-hardware.org/?probe=0bba3925b9) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ed7eccc83b](https://linux-hardware.org/?probe=ed7eccc83b) | Sep 12, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [edc7645bfe](https://linux-hardware.org/?probe=edc7645bfe) | Sep 12, 2021 |
| HP            | Pavilion Notebook           | [8fe2203713](https://linux-hardware.org/?probe=8fe2203713) | Sep 12, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [395e1bc884](https://linux-hardware.org/?probe=395e1bc884) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | [800d54370e](https://linux-hardware.org/?probe=800d54370e) | Sep 11, 2021 |
| Toshiba       | Satellite C850-1MC          | [98127c6225](https://linux-hardware.org/?probe=98127c6225) | Sep 11, 2021 |
| Toshiba       | Satellite Z930              | [2768d5ccb6](https://linux-hardware.org/?probe=2768d5ccb6) | Sep 11, 2021 |
| HP            | EliteBook 840 G1            | [c8da3fea5a](https://linux-hardware.org/?probe=c8da3fea5a) | Sep 11, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dd09fcf11e](https://linux-hardware.org/?probe=dd09fcf11e) | Sep 10, 2021 |
| Timi          | TM1613                      | [a79355ced3](https://linux-hardware.org/?probe=a79355ced3) | Sep 10, 2021 |
| Dell          | G5 5587                     | [943e12f3e8](https://linux-hardware.org/?probe=943e12f3e8) | Sep 10, 2021 |
| HP            | Pavilion x2 Detachable      | [ddcedfc109](https://linux-hardware.org/?probe=ddcedfc109) | Sep 10, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0a2430ae78](https://linux-hardware.org/?probe=0a2430ae78) | Sep 10, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [6829dbdafc](https://linux-hardware.org/?probe=6829dbdafc) | Sep 10, 2021 |
| Dell          | Latitude E5400              | [191b8606ba](https://linux-hardware.org/?probe=191b8606ba) | Sep 09, 2021 |
| Notebook      | NJ5x_NJ7xLU                 | [4d544fc5d5](https://linux-hardware.org/?probe=4d544fc5d5) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [41fef8dc7e](https://linux-hardware.org/?probe=41fef8dc7e) | Sep 09, 2021 |
| Thomson       | WWNEO14A-2BK32              | [752aa1b840](https://linux-hardware.org/?probe=752aa1b840) | Sep 09, 2021 |
| Dell          | Latitude 5520               | [7e327f4604](https://linux-hardware.org/?probe=7e327f4604) | Sep 09, 2021 |
| Timi          | Mi NoteBook Ultra           | [1619cb6257](https://linux-hardware.org/?probe=1619cb6257) | Sep 08, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [588250b1be](https://linux-hardware.org/?probe=588250b1be) | Sep 08, 2021 |
| TUXEDO        | N130BU                      | [e81e4cc415](https://linux-hardware.org/?probe=e81e4cc415) | Sep 08, 2021 |
| ASUSTek       | P55VA                       | [b00df8e82a](https://linux-hardware.org/?probe=b00df8e82a) | Sep 08, 2021 |
| ASUSTek       | X550LC                      | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | [f1bdc44923](https://linux-hardware.org/?probe=f1bdc44923) | Sep 08, 2021 |
| HP            | ProBook 430 G6              | [56f6e80ac3](https://linux-hardware.org/?probe=56f6e80ac3) | Sep 07, 2021 |
| Timi          | A35S                        | [0b22fc8994](https://linux-hardware.org/?probe=0b22fc8994) | Sep 07, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0C50... | [5ac7df1c1c](https://linux-hardware.org/?probe=5ac7df1c1c) | Sep 07, 2021 |
| Dell          | XPS 15 9510                 | [7ca1df084e](https://linux-hardware.org/?probe=7ca1df084e) | Sep 07, 2021 |
| Acer          | Swift SF514-51              | [6ab5bc3174](https://linux-hardware.org/?probe=6ab5bc3174) | Sep 06, 2021 |
| Acer          | Swift SF514-51              | [1bf499eb80](https://linux-hardware.org/?probe=1bf499eb80) | Sep 06, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [d410366b57](https://linux-hardware.org/?probe=d410366b57) | Sep 06, 2021 |
| TUXEDO        | P65_P67RGRERA               | [342dd3e712](https://linux-hardware.org/?probe=342dd3e712) | Sep 06, 2021 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | [782ea245a4](https://linux-hardware.org/?probe=782ea245a4) | Sep 06, 2021 |
| Apple         | MacBookPro7,1               | [51e31a6fa5](https://linux-hardware.org/?probe=51e31a6fa5) | Sep 05, 2021 |
| Intel         | SharkBay Platform           | [a19a4b3125](https://linux-hardware.org/?probe=a19a4b3125) | Sep 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [06404619aa](https://linux-hardware.org/?probe=06404619aa) | Sep 04, 2021 |
| Dell          | Latitude 7390 2-in-1        | [d1705e50a2](https://linux-hardware.org/?probe=d1705e50a2) | Sep 04, 2021 |
| Timi          | RedmiBook Pro 15S           | [9e63bc0888](https://linux-hardware.org/?probe=9e63bc0888) | Sep 04, 2021 |
| Acer          | Aspire 4750                 | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [f42fc0ef77](https://linux-hardware.org/?probe=f42fc0ef77) | Sep 04, 2021 |
| Packard Be... | EasyNote TE69HW             | [b02379df11](https://linux-hardware.org/?probe=b02379df11) | Sep 04, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [f485e570b4](https://linux-hardware.org/?probe=f485e570b4) | Sep 04, 2021 |
| HP            | Pavilion 17                 | [ef065acdd0](https://linux-hardware.org/?probe=ef065acdd0) | Sep 04, 2021 |
| Lenovo        | ThinkPad L470 20J5S2CP00    | [9ba4ef1dc5](https://linux-hardware.org/?probe=9ba4ef1dc5) | Sep 04, 2021 |
| Lenovo        | U310                        | [0be64d0c02](https://linux-hardware.org/?probe=0be64d0c02) | Sep 03, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [ae8bd5e632](https://linux-hardware.org/?probe=ae8bd5e632) | Sep 03, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [df9db29c8e](https://linux-hardware.org/?probe=df9db29c8e) | Sep 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d26d6327b1](https://linux-hardware.org/?probe=d26d6327b1) | Sep 03, 2021 |
| HP            | EliteBook Folio 1040 G3     | [6275aab341](https://linux-hardware.org/?probe=6275aab341) | Sep 03, 2021 |
| HP            | ProBook 4730s               | [36834479ab](https://linux-hardware.org/?probe=36834479ab) | Sep 03, 2021 |
| Dell          | XPS 13 7390                 | [be1de37337](https://linux-hardware.org/?probe=be1de37337) | Sep 03, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| Dell          | XPS 13 9360                 | [77a32d2048](https://linux-hardware.org/?probe=77a32d2048) | Sep 02, 2021 |
| Acer          | Aspire 8730                 | [23961f8f02](https://linux-hardware.org/?probe=23961f8f02) | Sep 02, 2021 |
| Acer          | Aspire 8730                 | [a0f96eb144](https://linux-hardware.org/?probe=a0f96eb144) | Sep 02, 2021 |
| Acer          | Aspire V3-571               | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| Dell          | Latitude 5580               | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Dell          | Inspiron 5584               | [48b4af3338](https://linux-hardware.org/?probe=48b4af3338) | Sep 01, 2021 |
| Dell          | XPS 15 9510                 | [5de0135b30](https://linux-hardware.org/?probe=5de0135b30) | Sep 01, 2021 |
| Lenovo        | ThinkPad X201 3626FBU       | [2a1b838727](https://linux-hardware.org/?probe=2a1b838727) | Sep 01, 2021 |
| Lenovo        | ThinkPad X201 3626FBU       | [ebe27cb3e0](https://linux-hardware.org/?probe=ebe27cb3e0) | Sep 01, 2021 |
| Acer          | Aspire ES1-572              | [301e2787bd](https://linux-hardware.org/?probe=301e2787bd) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [8c8a4d9cdf](https://linux-hardware.org/?probe=8c8a4d9cdf) | Aug 31, 2021 |
| ASUSTek       | UX550VE                     | [cd80e1ebb2](https://linux-hardware.org/?probe=cd80e1ebb2) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [bb2bba4301](https://linux-hardware.org/?probe=bb2bba4301) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [8f1f4a2c99](https://linux-hardware.org/?probe=8f1f4a2c99) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [d33400a4fe](https://linux-hardware.org/?probe=d33400a4fe) | Aug 31, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2c57f8fa2f](https://linux-hardware.org/?probe=2c57f8fa2f) | Aug 31, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0413b7b1e4](https://linux-hardware.org/?probe=0413b7b1e4) | Aug 31, 2021 |
| ASUSTek       | GL752VW                     | [1476b07c9d](https://linux-hardware.org/?probe=1476b07c9d) | Aug 31, 2021 |
| HUAWEI        | KLVL-WXX9                   | [b86e557def](https://linux-hardware.org/?probe=b86e557def) | Aug 31, 2021 |
| ASUSTek       | GL752VW                     | [625ac8c8bc](https://linux-hardware.org/?probe=625ac8c8bc) | Aug 31, 2021 |
| ASUSTek       | X550ZA                      | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | [628f8d49c7](https://linux-hardware.org/?probe=628f8d49c7) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | [882678793f](https://linux-hardware.org/?probe=882678793f) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | [1fcdd4041b](https://linux-hardware.org/?probe=1fcdd4041b) | Aug 30, 2021 |
| Dell          | Latitude E6520              | [03f5b8cb05](https://linux-hardware.org/?probe=03f5b8cb05) | Aug 30, 2021 |
| HP            | Pavilion Notebook           | [846b2e2a87](https://linux-hardware.org/?probe=846b2e2a87) | Aug 30, 2021 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [780244d79f](https://linux-hardware.org/?probe=780244d79f) | Aug 30, 2021 |
| HP            | Pavilion 17                 | [ca125d2f3c](https://linux-hardware.org/?probe=ca125d2f3c) | Aug 30, 2021 |
| ASUSTek       | P55VA                       | [12266fad85](https://linux-hardware.org/?probe=12266fad85) | Aug 30, 2021 |
| Lenovo        | B50-30 20382                | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [05e455f345](https://linux-hardware.org/?probe=05e455f345) | Aug 29, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [d700bad32f](https://linux-hardware.org/?probe=d700bad32f) | Aug 29, 2021 |
| Acer          | AOD260                      | [de4ce44515](https://linux-hardware.org/?probe=de4ce44515) | Aug 29, 2021 |
| MSI           | MS-16Y1                     | [a9801b616e](https://linux-hardware.org/?probe=a9801b616e) | Aug 29, 2021 |
| Acer          | AOD260                      | [3ed8c06a9c](https://linux-hardware.org/?probe=3ed8c06a9c) | Aug 29, 2021 |
| Toshiba       | Satellite C55-B             | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Acer          | Aspire 5742                 | [5a1fa64f5d](https://linux-hardware.org/?probe=5a1fa64f5d) | Aug 29, 2021 |
| Lenovo        | ThinkPad X201 3626FBU       | [7fe9be041a](https://linux-hardware.org/?probe=7fe9be041a) | Aug 29, 2021 |
| Acer          | Extensa 2509                | [b6615e1699](https://linux-hardware.org/?probe=b6615e1699) | Aug 29, 2021 |
| Acer          | Extensa 2509                | [a185b2f23f](https://linux-hardware.org/?probe=a185b2f23f) | Aug 29, 2021 |
| HP            | EliteBook 8530w             | [19a30277a2](https://linux-hardware.org/?probe=19a30277a2) | Aug 28, 2021 |
| Acer          | Aspire A515-56              | [2672ce2fe7](https://linux-hardware.org/?probe=2672ce2fe7) | Aug 28, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | [757d521e89](https://linux-hardware.org/?probe=757d521e89) | Aug 28, 2021 |
| ASUSTek       | K52Jr                       | [7ec475cdd0](https://linux-hardware.org/?probe=7ec475cdd0) | Aug 28, 2021 |
| Monster       | ABRA A7 V7.3                | [17d5cd11fa](https://linux-hardware.org/?probe=17d5cd11fa) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | [97ed1ed910](https://linux-hardware.org/?probe=97ed1ed910) | Aug 28, 2021 |
| HP            | Laptop 15-bw0xx             | [3c7b22938d](https://linux-hardware.org/?probe=3c7b22938d) | Aug 27, 2021 |
| Apple         | MacBookPro5,5               | [e035ede092](https://linux-hardware.org/?probe=e035ede092) | Aug 27, 2021 |
| Lenovo        | B50-30 20382                | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| Google        | Careena                     | [c71e6267cb](https://linux-hardware.org/?probe=c71e6267cb) | Aug 27, 2021 |
| ASUSTek       | X550ZA                      | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| HP            | ProBook 650 G1              | [fe97c44f4f](https://linux-hardware.org/?probe=fe97c44f4f) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [50477e1758](https://linux-hardware.org/?probe=50477e1758) | Aug 27, 2021 |
| Acer          | AOD260                      | [d8cf89df4e](https://linux-hardware.org/?probe=d8cf89df4e) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [d51c8093ec](https://linux-hardware.org/?probe=d51c8093ec) | Aug 27, 2021 |
| Acer          | Swift SF314-59              | [c4ec7d7706](https://linux-hardware.org/?probe=c4ec7d7706) | Aug 27, 2021 |
| Apple         | MacBookPro16,2              | [7e1625f75d](https://linux-hardware.org/?probe=7e1625f75d) | Aug 27, 2021 |
| Acer          | Aspire 5750G                | [03a89677c0](https://linux-hardware.org/?probe=03a89677c0) | Aug 26, 2021 |
| Apple         | MacBookPro8,1               | [d76439fc39](https://linux-hardware.org/?probe=d76439fc39) | Aug 26, 2021 |
| Apple         | MacBookPro8,1               | [41dce1e5d4](https://linux-hardware.org/?probe=41dce1e5d4) | Aug 26, 2021 |
| Dell          | Inspiron 15-3573            | [9ca63b6d40](https://linux-hardware.org/?probe=9ca63b6d40) | Aug 26, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [cfeb92ade1](https://linux-hardware.org/?probe=cfeb92ade1) | Aug 26, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [b090440019](https://linux-hardware.org/?probe=b090440019) | Aug 26, 2021 |
| ASUSTek       | S400CA                      | [d1c2760711](https://linux-hardware.org/?probe=d1c2760711) | Aug 26, 2021 |
| System76      | Oryx Pro                    | [ed8769ce16](https://linux-hardware.org/?probe=ed8769ce16) | Aug 26, 2021 |
| System76      | Oryx Pro                    | [a4ba687465](https://linux-hardware.org/?probe=a4ba687465) | Aug 26, 2021 |
| Dell          | Inspiron 5521               | [24bfc2b04a](https://linux-hardware.org/?probe=24bfc2b04a) | Aug 26, 2021 |
| Acer          | Swift SF313-53              | [8b7983c6f4](https://linux-hardware.org/?probe=8b7983c6f4) | Aug 26, 2021 |
| Acer          | Swift SF313-53              | [60ba1a6cf7](https://linux-hardware.org/?probe=60ba1a6cf7) | Aug 25, 2021 |
| BANGHO        | MOV                         | [9bacff92e1](https://linux-hardware.org/?probe=9bacff92e1) | Aug 25, 2021 |
| Acer          | Swift SF313-53              | [91b876aec6](https://linux-hardware.org/?probe=91b876aec6) | Aug 25, 2021 |
| Acer          | Swift SF313-53              | [19f99141b9](https://linux-hardware.org/?probe=19f99141b9) | Aug 25, 2021 |
| Lenovo        | ThinkPad T420s 4176W27      | [b84d5c31e3](https://linux-hardware.org/?probe=b84d5c31e3) | Aug 25, 2021 |
| Dell          | Inspiron 13-7359            | [0d1a190ded](https://linux-hardware.org/?probe=0d1a190ded) | Aug 25, 2021 |
| Dell          | Inspiron 13-7359            | [347f0ad714](https://linux-hardware.org/?probe=347f0ad714) | Aug 25, 2021 |
| Google        | Akemi                       | [11b458a90a](https://linux-hardware.org/?probe=11b458a90a) | Aug 25, 2021 |
| Google        | Akemi                       | [ebd0d7d1f9](https://linux-hardware.org/?probe=ebd0d7d1f9) | Aug 25, 2021 |
| Lenovo        | G500 20236                  | [fb90bc01bc](https://linux-hardware.org/?probe=fb90bc01bc) | Aug 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [642e4b5727](https://linux-hardware.org/?probe=642e4b5727) | Aug 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [f75424e1e1](https://linux-hardware.org/?probe=f75424e1e1) | Aug 25, 2021 |
| Dell          | XPS 13 9300                 | [2ef66334f0](https://linux-hardware.org/?probe=2ef66334f0) | Aug 24, 2021 |
| Lenovo        | B580 4377A9G                | [4a7f165a2f](https://linux-hardware.org/?probe=4a7f165a2f) | Aug 24, 2021 |
| Sony          | VGN-SZ4MN_B                 | [9b51d6eff6](https://linux-hardware.org/?probe=9b51d6eff6) | Aug 24, 2021 |
| Packard Be... | EasyNote LE69KB             | [adb16307d7](https://linux-hardware.org/?probe=adb16307d7) | Aug 24, 2021 |
| HP            | EliteBook 8530w             | [ea7f22c125](https://linux-hardware.org/?probe=ea7f22c125) | Aug 24, 2021 |
| CyberPower... | TRACER V                    | [d32f6e01af](https://linux-hardware.org/?probe=d32f6e01af) | Aug 24, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fa55eabafd](https://linux-hardware.org/?probe=fa55eabafd) | Aug 23, 2021 |
| HP            | Notebook                    | [5edda59c62](https://linux-hardware.org/?probe=5edda59c62) | Aug 23, 2021 |
| Samsung       | 750XDA                      | [a93fe624c9](https://linux-hardware.org/?probe=a93fe624c9) | Aug 23, 2021 |
| Dell          | Vostro 5568                 | [bf921c6ff6](https://linux-hardware.org/?probe=bf921c6ff6) | Aug 23, 2021 |
| Dell          | Inspiron 3558               | [946f2bf799](https://linux-hardware.org/?probe=946f2bf799) | Aug 22, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [6a52dc6e12](https://linux-hardware.org/?probe=6a52dc6e12) | Aug 22, 2021 |
| Acer          | Aspire 4750                 | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| Acer          | Aspire ES1-572              | [12cb2077ff](https://linux-hardware.org/?probe=12cb2077ff) | Aug 22, 2021 |
| Toshiba       | Satellite C655D             | [63dfa0ffd8](https://linux-hardware.org/?probe=63dfa0ffd8) | Aug 22, 2021 |
| Toshiba       | Satellite C55-B             | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| HP            | EliteBook 850 G2            | [89bfd52b3d](https://linux-hardware.org/?probe=89bfd52b3d) | Aug 22, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [dcf6e0d950](https://linux-hardware.org/?probe=dcf6e0d950) | Aug 22, 2021 |
| HP            | EliteBook 850 G2            | [a82576e8e2](https://linux-hardware.org/?probe=a82576e8e2) | Aug 22, 2021 |
| HP            | Notebook                    | [5ac3618644](https://linux-hardware.org/?probe=5ac3618644) | Aug 22, 2021 |
| HP            | ProBook 650 G1              | [521e8315c2](https://linux-hardware.org/?probe=521e8315c2) | Aug 22, 2021 |
| Lenovo        | G500 20236                  | [37294c9129](https://linux-hardware.org/?probe=37294c9129) | Aug 21, 2021 |
| Dell          | Latitude E5400              | [0e1ba1167e](https://linux-hardware.org/?probe=0e1ba1167e) | Aug 21, 2021 |
| Dell          | Latitude E5400              | [10eee4ecd9](https://linux-hardware.org/?probe=10eee4ecd9) | Aug 21, 2021 |
| ASUSTek       | ZenBook UX434FQ             | [e5778c606b](https://linux-hardware.org/?probe=e5778c606b) | Aug 21, 2021 |
| HP            | Laptop 15s-du1xxx           | [0db32c3e7e](https://linux-hardware.org/?probe=0db32c3e7e) | Aug 21, 2021 |
| Dell          | XPS 13 9305                 | [875e2fe9eb](https://linux-hardware.org/?probe=875e2fe9eb) | Aug 20, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [05298cb71d](https://linux-hardware.org/?probe=05298cb71d) | Aug 20, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [bad0ffd0e2](https://linux-hardware.org/?probe=bad0ffd0e2) | Aug 20, 2021 |
| HP            | EliteBook 8570w             | [353385ccb8](https://linux-hardware.org/?probe=353385ccb8) | Aug 20, 2021 |
| Lenovo        | G560 0679                   | [a5d3d1f80c](https://linux-hardware.org/?probe=a5d3d1f80c) | Aug 20, 2021 |
| Lenovo        | G560 0679                   | [ce91db6192](https://linux-hardware.org/?probe=ce91db6192) | Aug 20, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [d1800db637](https://linux-hardware.org/?probe=d1800db637) | Aug 20, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [e5f9d8b06f](https://linux-hardware.org/?probe=e5f9d8b06f) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | [a7ce746e66](https://linux-hardware.org/?probe=a7ce746e66) | Aug 20, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b8f5afa2f7](https://linux-hardware.org/?probe=b8f5afa2f7) | Aug 20, 2021 |
| Dell          | Inspiron N5050              | [ed6b51261d](https://linux-hardware.org/?probe=ed6b51261d) | Aug 20, 2021 |
| SLIMBOOK      | TITAN                       | [1eb70ec6e6](https://linux-hardware.org/?probe=1eb70ec6e6) | Aug 19, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [743442952d](https://linux-hardware.org/?probe=743442952d) | Aug 19, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [a4e0272377](https://linux-hardware.org/?probe=a4e0272377) | Aug 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [481800b937](https://linux-hardware.org/?probe=481800b937) | Aug 19, 2021 |
| Dell          | Vostro 3360                 | [03074a36b2](https://linux-hardware.org/?probe=03074a36b2) | Aug 19, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [74f533e1b3](https://linux-hardware.org/?probe=74f533e1b3) | Aug 19, 2021 |
| HP            | 450                         | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| ASUSTek       | G55VW                       | [7daa09d3c3](https://linux-hardware.org/?probe=7daa09d3c3) | Aug 19, 2021 |
| Samsung       | 520U4C/520U4X               | [1863ae7d28](https://linux-hardware.org/?probe=1863ae7d28) | Aug 19, 2021 |
| ASUSTek       | K54C                        | [816e5c7efa](https://linux-hardware.org/?probe=816e5c7efa) | Aug 19, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [ea3fc1154c](https://linux-hardware.org/?probe=ea3fc1154c) | Aug 18, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [d9923e15e0](https://linux-hardware.org/?probe=d9923e15e0) | Aug 18, 2021 |
| Toshiba       | Satellite Z930              | [3138585fd8](https://linux-hardware.org/?probe=3138585fd8) | Aug 18, 2021 |
| Toshiba       | PORTEGE Z930                | [a49ad7f306](https://linux-hardware.org/?probe=a49ad7f306) | Aug 18, 2021 |
| Toshiba       | Satellite Z930              | [dfb39f616a](https://linux-hardware.org/?probe=dfb39f616a) | Aug 18, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [251af23ff3](https://linux-hardware.org/?probe=251af23ff3) | Aug 18, 2021 |
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
| 5.11.0-25-generic        | 114       | 15.79%  |
| 5.11.0-16-generic        | 105       | 14.54%  |
| 5.11.0-22-generic        | 94        | 13.02%  |
| 5.11.0-31-generic        | 92        | 12.74%  |
| 5.11.0-18-generic        | 81        | 11.22%  |
| 5.11.0-17-generic        | 81        | 11.22%  |
| 5.11.0-34-generic        | 48        | 6.65%   |
| 5.11.0-26-generic        | 12        | 1.66%   |
| 5.11.0-20-generic        | 7         | 0.97%   |
| 5.11.0-33-generic        | 6         | 0.83%   |
| 5.11.0-24-generic        | 6         | 0.83%   |
| 5.11.0-13-generic        | 6         | 0.83%   |
| 5.13.0-051300-generic    | 4         | 0.55%   |
| 5.11.0-11-generic        | 3         | 0.42%   |
| 5.10.0-14-generic        | 3         | 0.42%   |
| 5.8.0-50-generic         | 2         | 0.28%   |
| 5.8.0-36-generic         | 2         | 0.28%   |
| 5.8.0-32-generic         | 2         | 0.28%   |
| 5.8.0-25-generic         | 2         | 0.28%   |
| 5.14.0-051400-generic    | 2         | 0.28%   |
| 5.13.9-051309-generic    | 2         | 0.28%   |
| 5.13.12-051312-generic   | 2         | 0.28%   |
| 5.13.1-051301-generic    | 2         | 0.28%   |
| 5.12.12-051212-generic   | 2         | 0.28%   |
| 5.12.0-051200rc3-generic | 2         | 0.28%   |
| 5.12.0-051200-generic    | 2         | 0.28%   |
| 5.11.0-35-generic        | 2         | 0.28%   |
| 5.11.0-14-generic        | 2         | 0.28%   |
| 5.8.0-63-generic         | 1         | 0.14%   |
| 5.8.0-56-generic         | 1         | 0.14%   |
| 5.8.0-55-generic         | 1         | 0.14%   |
| 5.8.0-44-generic         | 1         | 0.14%   |
| 5.8.0-41-generic         | 1         | 0.14%   |
| 5.8.0-33-generic         | 1         | 0.14%   |
| 5.8.0-31-lowlatency      | 1         | 0.14%   |
| 5.8.0-29-generic         | 1         | 0.14%   |
| 5.8.0-26-lowlatency      | 1         | 0.14%   |
| 5.14.3-051403-generic    | 1         | 0.14%   |
| 5.14.1-051401-generic    | 1         | 0.14%   |
| 5.14.0-051400rc7-generic | 1         | 0.14%   |
| 5.14.0-051400rc6-generic | 1         | 0.14%   |
| 5.14.0-051400rc5-generic | 1         | 0.14%   |
| 5.14.0-051400rc3-generic | 1         | 0.14%   |
| 5.13.7-051307-generic    | 1         | 0.14%   |
| 5.13.4-051304-generic    | 1         | 0.14%   |
| 5.13.0-051300rc7-generic | 1         | 0.14%   |
| 5.13.0-051300rc4-generic | 1         | 0.14%   |
| 5.12.9-051209-generic    | 1         | 0.14%   |
| 5.12.4-051204-generic    | 1         | 0.14%   |
| 5.12.0-051200rc5-generic | 1         | 0.14%   |
| 5.11.6-051106-generic    | 1         | 0.14%   |
| 5.11.12-051112-generic   | 1         | 0.14%   |
| 5.11.0-7620-generic      | 1         | 0.14%   |
| 5.11.0-7614-generic      | 1         | 0.14%   |
| 5.11.0-35-lowlatency     | 1         | 0.14%   |
| 5.11.0-33-lowlatency     | 1         | 0.14%   |
| 5.11.0-26-lowlatency     | 1         | 0.14%   |
| 5.11.0-22-lowlatency     | 1         | 0.14%   |
| 5.11.0-19-generic        | 1         | 0.14%   |
| 5.11.0-17-lowlatency     | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 619       | 92.25%  |
| 5.8.0   | 16        | 2.38%   |
| 5.13.0  | 6         | 0.89%   |
| 5.14.0  | 5         | 0.75%   |
| 5.12.0  | 5         | 0.75%   |
| 5.10.0  | 4         | 0.6%    |
| 5.13.9  | 2         | 0.3%    |
| 5.13.12 | 2         | 0.3%    |
| 5.13.1  | 2         | 0.3%    |
| 5.12.12 | 2         | 0.3%    |
| 5.14.3  | 1         | 0.15%   |
| 5.14.1  | 1         | 0.15%   |
| 5.13.7  | 1         | 0.15%   |
| 5.13.4  | 1         | 0.15%   |
| 5.12.9  | 1         | 0.15%   |
| 5.12.4  | 1         | 0.15%   |
| 5.11.6  | 1         | 0.15%   |
| 5.11.12 | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 621       | 92.69%  |
| 5.8     | 16        | 2.39%   |
| 5.13    | 13        | 1.94%   |
| 5.12    | 9         | 1.34%   |
| 5.14    | 7         | 1.04%   |
| 5.10    | 4         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 666       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 588       | 87.24%  |
| Unknown         | 66        | 9.79%   |
| X-Cinnamon      | 7         | 1.04%   |
| Unity           | 4         | 0.59%   |
| Deepin          | 4         | 0.59%   |
| Cinnamon        | 3         | 0.45%   |
| i3              | 1         | 0.15%   |
| GNOME Flashback | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 421       | 61.73%  |
| X11     | 219       | 32.11%  |
| Unknown | 38        | 5.57%   |
| Tty     | 4         | 0.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 438       | 65.67%  |
| GDM     | 219       | 32.83%  |
| TDM     | 6         | 0.9%    |
| SDDM    | 2         | 0.3%    |
| LightDM | 1         | 0.15%   |
| GDM3    | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 290       | 43.48%  |
| de_DE   | 66        | 9.9%    |
| fr_FR   | 40        | 6%      |
| en_GB   | 36        | 5.4%    |
| en_IN   | 31        | 4.65%   |
| pt_BR   | 21        | 3.15%   |
| it_IT   | 20        | 3%      |
| es_ES   | 19        | 2.85%   |
| ru_RU   | 15        | 2.25%   |
| pl_PL   | 13        | 1.95%   |
| en_CA   | 12        | 1.8%    |
| cs_CZ   | 12        | 1.8%    |
| en_AU   | 10        | 1.5%    |
| nl_NL   | 7         | 1.05%   |
| de_AT   | 5         | 0.75%   |
| Unknown | 5         | 0.75%   |
| es_MX   | 4         | 0.6%    |
| es_CL   | 4         | 0.6%    |
| en_ZA   | 4         | 0.6%    |
| zh_CN   | 3         | 0.45%   |
| tr_TR   | 3         | 0.45%   |
| fr_BE   | 3         | 0.45%   |
| C       | 3         | 0.45%   |
| zh_TW   | 2         | 0.3%    |
| sv_SE   | 2         | 0.3%    |
| ru_UA   | 2         | 0.3%    |
| ja_JP   | 2         | 0.3%    |
| es_UY   | 2         | 0.3%    |
| es_EC   | 2         | 0.3%    |
| es_CO   | 2         | 0.3%    |
| es_AR   | 2         | 0.3%    |
| en_NZ   | 2         | 0.3%    |
| en_IL   | 2         | 0.3%    |
| da_DK   | 2         | 0.3%    |
| vi_VN   | 1         | 0.15%   |
| sr_RS   | 1         | 0.15%   |
| ro_RO   | 1         | 0.15%   |
| pt_PT   | 1         | 0.15%   |
| nb_NO   | 1         | 0.15%   |
| hu_HU   | 1         | 0.15%   |
| hr_HR   | 1         | 0.15%   |
| fr_CA   | 1         | 0.15%   |
| fi_FI   | 1         | 0.15%   |
| et_EE   | 1         | 0.15%   |
| es_PE   | 1         | 0.15%   |
| es_HN   | 1         | 0.15%   |
| es_CU   | 1         | 0.15%   |
| en_DK   | 1         | 0.15%   |
| de_IT   | 1         | 0.15%   |
| de_CH   | 1         | 0.15%   |
| ca_ES   | 1         | 0.15%   |
| bg_BG   | 1         | 0.15%   |
| ar_SA   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 387       | 57.5%   |
| EFI  | 286       | 42.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 618       | 92.79%  |
| Zfs     | 21        | 3.15%   |
| Overlay | 13        | 1.95%   |
| Btrfs   | 9         | 1.35%   |
| Xfs     | 2         | 0.3%    |
| Ext2    | 2         | 0.3%    |
| Unknown | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 432       | 64.77%  |
| GPT     | 225       | 33.73%  |
| MBR     | 10        | 1.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 600       | 89.69%  |
| Yes       | 69        | 10.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 446       | 66.77%  |
| Yes       | 222       | 33.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo                                       | 132       | 19.82%  |
| Hewlett-Packard                              | 130       | 19.52%  |
| Dell                                         | 118       | 17.72%  |
| ASUSTek Computer                             | 71        | 10.66%  |
| Acer                                         | 55        | 8.26%   |
| Apple                                        | 18        | 2.7%    |
| Samsung Electronics                          | 15        | 2.25%   |
| Toshiba                                      | 13        | 1.95%   |
| HUAWEI                                       | 12        | 1.8%    |
| Sony                                         | 11        | 1.65%   |
| MSI                                          | 10        | 1.5%    |
| Timi                                         | 8         | 1.2%    |
| Fujitsu                                      | 7         | 1.05%   |
| Medion                                       | 5         | 0.75%   |
| TUXEDO                                       | 4         | 0.6%    |
| System76                                     | 4         | 0.6%    |
| Notebook                                     | 4         | 0.6%    |
| Razer                                        | 3         | 0.45%   |
| Positivo                                     | 3         | 0.45%   |
| Packard Bell                                 | 3         | 0.45%   |
| Google                                       | 3         | 0.45%   |
| Unknown                                      | 3         | 0.45%   |
| Schenker                                     | 2         | 0.3%    |
| Monster                                      | 2         | 0.3%    |
| LG Electronics                               | 2         | 0.3%    |
| Alienware                                    | 2         | 0.3%    |
| Wiltronic                                    | 1         | 0.15%   |
| VINGA                                        | 1         | 0.15%   |
| Thomson                                      | 1         | 0.15%   |
| Teclast                                      | 1         | 0.15%   |
| Standard                                     | 1         | 0.15%   |
| roda computer                                | 1         | 0.15%   |
| Radxa                                        | 1         | 0.15%   |
| Positivo Bahia - VAIO                        | 1         | 0.15%   |
| Pegatron                                     | 1         | 0.15%   |
| Panasonic                                    | 1         | 0.15%   |
| Maibenben                                    | 1         | 0.15%   |
| IP3 Tech                                     | 1         | 0.15%   |
| Intel                                        | 1         | 0.15%   |
| Insignia                                     | 1         | 0.15%   |
| HKC                                          | 1         | 0.15%   |
| HCL Infosystems Limited                      | 1         | 0.15%   |
| HASEE Computer                               | 1         | 0.15%   |
| Gigabyte Technology                          | 1         | 0.15%   |
| Gateway                                      | 1         | 0.15%   |
| eMachines                                    | 1         | 0.15%   |
| DNS                                          | 1         | 0.15%   |
| CyberPowerPC                                 | 1         | 0.15%   |
| CHUWI?Innovation?And?Technology(ShenZhen)co. | 1         | 0.15%   |
| Chuwi                                        | 1         | 0.15%   |
| BANGHO                                       | 1         | 0.15%   |
| Advance                                      | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 8         | 1.2%    |
| Dell XPS 15 7590                      | 7         | 1.05%   |
| HP Notebook                           | 6         | 0.9%    |
| HP EliteBook 820 G1                   | 4         | 0.6%    |
| Lenovo G500 20236                     | 3         | 0.45%   |
| HUAWEI HLYL-WXX9                      | 3         | 0.45%   |
| HP Pavilion Notebook                  | 3         | 0.45%   |
| HP EliteBook 840 G2                   | 3         | 0.45%   |
| Dell XPS 15 9510                      | 3         | 0.45%   |
| Dell G5 5587                          | 3         | 0.45%   |
| Dell G3 3500                          | 3         | 0.45%   |
| ASUS ROG Strix G513QY_G513QY          | 3         | 0.45%   |
| Acer Swift SF314-59                   | 3         | 0.45%   |
| Acer Aspire A515-44                   | 3         | 0.45%   |
| Toshiba PORTEGE Z930                  | 2         | 0.3%    |
| Timi A35S                             | 2         | 0.3%    |
| System76 Serval WS                    | 2         | 0.3%    |
| Samsung 300E4C/300E5C/300E7C          | 2         | 0.3%    |
| Razer Blade                           | 2         | 0.3%    |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW | 2         | 0.3%    |
| Lenovo ThinkBook 16p Gen 2 20YM       | 2         | 0.3%    |
| Lenovo IdeaPad 520-15IKB 81BF         | 2         | 0.3%    |
| Lenovo IdeaPad 5 15ITL05 82FG         | 2         | 0.3%    |
| Lenovo IdeaPad 5 14ARE05 81YM         | 2         | 0.3%    |
| Lenovo IdeaPad 330S-15ARR 81FB        | 2         | 0.3%    |
| Lenovo IdeaPad 330-15IKB 81DE         | 2         | 0.3%    |
| Lenovo IdeaPad 3 17ADA05 81W2         | 2         | 0.3%    |
| HUAWEI MACH-WX9                       | 2         | 0.3%    |
| HUAWEI KLVL-WXX9                      | 2         | 0.3%    |
| HUAWEI BOHK-WAX9X                     | 2         | 0.3%    |
| HP ProBook 650 G1                     | 2         | 0.3%    |
| HP ProBook 4540s                      | 2         | 0.3%    |
| HP ProBook 450 G7                     | 2         | 0.3%    |
| HP ProBook 450 G6                     | 2         | 0.3%    |
| HP Pavilion Laptop 15-cs3xxx          | 2         | 0.3%    |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 2         | 0.3%    |
| HP Pavilion dv6                       | 2         | 0.3%    |
| HP Pavilion dv5                       | 2         | 0.3%    |
| HP Pavilion 17                        | 2         | 0.3%    |
| HP Laptop 15s-eq1xxx                  | 2         | 0.3%    |
| HP EliteBook Folio 1040 G3            | 2         | 0.3%    |
| HP EliteBook 8570w                    | 2         | 0.3%    |
| HP EliteBook 8530w                    | 2         | 0.3%    |
| HP EliteBook 850 G2                   | 2         | 0.3%    |
| HP EliteBook 845 G7 Notebook PC       | 2         | 0.3%    |
| HP EliteBook 840 G3                   | 2         | 0.3%    |
| HP EliteBook 840 G1                   | 2         | 0.3%    |
| HP 255 G7 Notebook PC                 | 2         | 0.3%    |
| Fujitsu STYLISTIC Q702                | 2         | 0.3%    |
| Dell XPS 15 9570                      | 2         | 0.3%    |
| Dell XPS 15 9560                      | 2         | 0.3%    |
| Dell XPS 15 9500                      | 2         | 0.3%    |
| Dell XPS 13 9360                      | 2         | 0.3%    |
| Dell XPS 13 9310                      | 2         | 0.3%    |
| Dell Latitude E7440                   | 2         | 0.3%    |
| Dell Latitude E5520                   | 2         | 0.3%    |
| Dell Latitude E5400                   | 2         | 0.3%    |
| Dell Latitude 7370                    | 2         | 0.3%    |
| Dell Latitude 5520                    | 2         | 0.3%    |
| Dell Latitude 5511                    | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 67        | 10.06%  |
| Lenovo IdeaPad        | 35        | 5.26%   |
| Dell Latitude         | 35        | 5.26%   |
| HP EliteBook          | 34        | 5.11%   |
| Acer Aspire           | 34        | 5.11%   |
| Dell Inspiron         | 32        | 4.8%    |
| Dell XPS              | 26        | 3.9%    |
| HP Pavilion           | 24        | 3.6%    |
| HP ProBook            | 22        | 3.3%    |
| ASUS ROG              | 13        | 1.95%   |
| HP Laptop             | 12        | 1.8%    |
| Acer Swift            | 11        | 1.65%   |
| Dell Vostro           | 10        | 1.5%    |
| Unknown               | 8         | 1.2%    |
| Toshiba Satellite     | 7         | 1.05%   |
| ASUS VivoBook         | 7         | 1.05%   |
| HP Notebook           | 6         | 0.9%    |
| HP ENVY               | 6         | 0.9%    |
| Lenovo ThinkBook      | 5         | 0.75%   |
| Fujitsu LIFEBOOK      | 5         | 0.75%   |
| Dell Precision        | 5         | 0.75%   |
| HP OMEN               | 4         | 0.6%    |
| Dell G3               | 4         | 0.6%    |
| ASUS ZenBook          | 4         | 0.6%    |
| Toshiba PORTEGE       | 3         | 0.45%   |
| Razer Blade           | 3         | 0.45%   |
| Packard Bell EasyNote | 3         | 0.45%   |
| Lenovo G500           | 3         | 0.45%   |
| HUAWEI HLYL-WXX9      | 3         | 0.45%   |
| Dell G5               | 3         | 0.45%   |
| ASUS ASUS             | 3         | 0.45%   |
| Apple MacBookPro8     | 3         | 0.45%   |
| Acer TravelMate       | 3         | 0.45%   |
| Toshiba TECRA         | 2         | 0.3%    |
| Timi Mi               | 2         | 0.3%    |
| Timi A35S             | 2         | 0.3%    |
| System76 Serval       | 2         | 0.3%    |
| Schenker XMG          | 2         | 0.3%    |
| Samsung 300E4C        | 2         | 0.3%    |
| Lenovo Yoga           | 2         | 0.3%    |
| Lenovo Legion         | 2         | 0.3%    |
| Lenovo G50-80         | 2         | 0.3%    |
| HUAWEI MACH-WX9       | 2         | 0.3%    |
| HUAWEI KLVL-WXX9      | 2         | 0.3%    |
| HUAWEI BOHK-WAX9X     | 2         | 0.3%    |
| HP ZBook              | 2         | 0.3%    |
| HP Spectre            | 2         | 0.3%    |
| HP Compaq             | 2         | 0.3%    |
| HP 255                | 2         | 0.3%    |
| HP 15                 | 2         | 0.3%    |
| Fujitsu STYLISTIC     | 2         | 0.3%    |
| Dell G7               | 2         | 0.3%    |
| ASUS X551CAP          | 2         | 0.3%    |
| ASUS U50Vg            | 2         | 0.3%    |
| ASUS T100HAN          | 2         | 0.3%    |
| Apple MacBookPro9     | 2         | 0.3%    |
| Apple MacBookPro7     | 2         | 0.3%    |
| Acer Nitro            | 2         | 0.3%    |
| Acer Extensa          | 2         | 0.3%    |
| Wiltronic IVIEW       | 1         | 0.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 145       | 21.77%  |
| 2020 | 140       | 21.02%  |
| 2019 | 72        | 10.81%  |
| 2018 | 48        | 7.21%   |
| 2011 | 40        | 6.01%   |
| 2013 | 38        | 5.71%   |
| 2015 | 33        | 4.95%   |
| 2012 | 28        | 4.2%    |
| 2016 | 24        | 3.6%    |
| 2017 | 23        | 3.45%   |
| 2009 | 22        | 3.3%    |
| 2014 | 21        | 3.15%   |
| 2010 | 16        | 2.4%    |
| 2008 | 11        | 1.65%   |
| 2007 | 5         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 666       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 595       | 88.94%  |
| Enabled  | 74        | 11.06%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 662       | 99.4%   |
| Yes  | 4         | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 204       | 30.63%  |
| 16.01-24.0  | 135       | 20.27%  |
| 3.01-4.0    | 131       | 19.67%  |
| 8.01-16.0   | 108       | 16.22%  |
| 32.01-64.0  | 49        | 7.36%   |
| 1.01-2.0    | 25        | 3.75%   |
| 64.01-256.0 | 8         | 1.2%    |
| 24.01-32.0  | 5         | 0.75%   |
| 2.01-3.0    | 1         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 254       | 36.44%  |
| 2.01-3.0   | 193       | 27.69%  |
| 4.01-8.0   | 108       | 15.49%  |
| 3.01-4.0   | 102       | 14.63%  |
| 8.01-16.0  | 21        | 3.01%   |
| 0.51-1.0   | 13        | 1.87%   |
| 16.01-24.0 | 3         | 0.43%   |
| 0.01-0.5   | 2         | 0.29%   |
| 24.01-32.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 499       | 74.59%  |
| 2      | 145       | 21.67%  |
| 3      | 14        | 2.09%   |
| 4      | 5         | 0.75%   |
| 0      | 4         | 0.6%    |
| 6      | 1         | 0.15%   |
| 5      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 458       | 68.77%  |
| Yes       | 208       | 31.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 514       | 76.95%  |
| No        | 154       | 23.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 650       | 97.45%  |
| No        | 17        | 2.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 546       | 81.49%  |
| No        | 124       | 18.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 98        | 14.67%  |
| Germany             | 83        | 12.43%  |
| France              | 42        | 6.29%   |
| India               | 32        | 4.79%   |
| UK                  | 31        | 4.64%   |
| Russia              | 29        | 4.34%   |
| Brazil              | 29        | 4.34%   |
| Spain               | 27        | 4.04%   |
| Italy               | 27        | 4.04%   |
| Poland              | 24        | 3.59%   |
| Canada              | 17        | 2.54%   |
| Czechia             | 15        | 2.25%   |
| Netherlands         | 14        | 2.1%    |
| Finland             | 11        | 1.65%   |
| Austria             | 10        | 1.5%    |
| Australia           | 10        | 1.5%    |
| Ukraine             | 9         | 1.35%   |
| Turkey              | 9         | 1.35%   |
| Mexico              | 8         | 1.2%    |
| Sweden              | 7         | 1.05%   |
| Romania             | 7         | 1.05%   |
| Belgium             | 6         | 0.9%    |
| Switzerland         | 5         | 0.75%   |
| Israel              | 5         | 0.75%   |
| Vietnam             | 4         | 0.6%    |
| South Africa        | 4         | 0.6%    |
| Portugal            | 4         | 0.6%    |
| Indonesia           | 4         | 0.6%    |
| Hungary             | 4         | 0.6%    |
| Greece              | 4         | 0.6%    |
| Croatia             | 4         | 0.6%    |
| Colombia            | 4         | 0.6%    |
| Chile               | 4         | 0.6%    |
| Serbia              | 3         | 0.45%   |
| Saudi Arabia        | 3         | 0.45%   |
| Peru                | 3         | 0.45%   |
| New Zealand         | 3         | 0.45%   |
| Luxembourg          | 3         | 0.45%   |
| Japan               | 3         | 0.45%   |
| Iran                | 3         | 0.45%   |
| China               | 3         | 0.45%   |
| Belarus             | 3         | 0.45%   |
| Uruguay             | 2         | 0.3%    |
| Taiwan              | 2         | 0.3%    |
| Sudan               | 2         | 0.3%    |
| Slovakia            | 2         | 0.3%    |
| Malaysia            | 2         | 0.3%    |
| Lithuania           | 2         | 0.3%    |
| Latvia              | 2         | 0.3%    |
| Ecuador             | 2         | 0.3%    |
| Denmark             | 2         | 0.3%    |
| Argentina           | 2         | 0.3%    |
| Zimbabwe            | 1         | 0.15%   |
| Uzbekistan          | 1         | 0.15%   |
| Trinidad and Tobago | 1         | 0.15%   |
| Pakistan            | 1         | 0.15%   |
| Norway              | 1         | 0.15%   |
| Nepal               | 1         | 0.15%   |
| Morocco             | 1         | 0.15%   |
| Moldova             | 1         | 0.15%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Paris          | 10        | 1.47%   |
| Moscow         | 10        | 1.47%   |
| Prague         | 8         | 1.17%   |
| Warsaw         | 7         | 1.03%   |
| Vienna         | 7         | 1.03%   |
| Milan          | 6         | 0.88%   |
| Helsinki       | 6         | 0.88%   |
| Berlin         | 6         | 0.88%   |
| Cologne        | 5         | 0.73%   |
| New Delhi      | 4         | 0.59%   |
| Madrid         | 4         | 0.59%   |
| Kyiv           | 4         | 0.59%   |
| Zagreb         | 3         | 0.44%   |
| St Petersburg  | 3         | 0.44%   |
| S??o Paulo     | 3         | 0.44%   |
| Santiago       | 3         | 0.44%   |
| Nuremberg      | 3         | 0.44%   |
| Munich         | 3         | 0.44%   |
| Montreal       | 3         | 0.44%   |
| Krakow         | 3         | 0.44%   |
| Kolkata        | 3         | 0.44%   |
| Jakarta        | 3         | 0.44%   |
| Gdansk         | 3         | 0.44%   |
| Fort Wayne     | 3         | 0.44%   |
| Dallas         | 3         | 0.44%   |
| Bucharest      | 3         | 0.44%   |
| Bielefeld      | 3         | 0.44%   |
| Belgrade       | 3         | 0.44%   |
| Barcelona      | 3         | 0.44%   |
| Athens         | 3         | 0.44%   |
| Alexandria     | 3         | 0.44%   |
| Valencia       | 2         | 0.29%   |
| Utrecht        | 2         | 0.29%   |
| Tehran         | 2         | 0.29%   |
| Sydney         | 2         | 0.29%   |
| Stuttgart      | 2         | 0.29%   |
| Schifflange    | 2         | 0.29%   |
| Rostov-on-Don  | 2         | 0.29%   |
| Riga           | 2         | 0.29%   |
| Pune           | 2         | 0.29%   |
| Oklahoma City  | 2         | 0.29%   |
| O'Fallon       | 2         | 0.29%   |
| Nizhnevartovsk | 2         | 0.29%   |
| New York       | 2         | 0.29%   |
| New Braunfels  | 2         | 0.29%   |
| Minsk          | 2         | 0.29%   |
| Mexico City    | 2         | 0.29%   |
| Los Angeles    | 2         | 0.29%   |
| London         | 2         | 0.29%   |
| Lima           | 2         | 0.29%   |
| Las Vegas      | 2         | 0.29%   |
| Krasnodar      | 2         | 0.29%   |
| Kaunas         | 2         | 0.29%   |
| Johannesburg   | 2         | 0.29%   |
| Istanbul       | 2         | 0.29%   |
| Hamburg        | 2         | 0.29%   |
| Glasgow        | 2         | 0.29%   |
| Florence       | 2         | 0.29%   |
| Ernakulam      | 2         | 0.29%   |
| Dunedin        | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 125       | 147    | 15.47%  |
| WDC                       | 110       | 120    | 13.61%  |
| Toshiba                   | 86        | 101    | 10.64%  |
| Seagate                   | 85        | 97     | 10.52%  |
| SanDisk                   | 48        | 57     | 5.94%   |
| SK Hynix                  | 45        | 47     | 5.57%   |
| Unknown                   | 39        | 50     | 4.83%   |
| Intel                     | 33        | 41     | 4.08%   |
| Kingston                  | 31        | 34     | 3.84%   |
| HGST                      | 24        | 29     | 2.97%   |
| Crucial                   | 24        | 32     | 2.97%   |
| Micron Technology         | 22        | 25     | 2.72%   |
| Hitachi                   | 16        | 19     | 1.98%   |
| KIOXIA                    | 13        | 13     | 1.61%   |
| Apple                     | 8         | 8      | 0.99%   |
| A-DATA Technology         | 8         | 9      | 0.99%   |
| Patriot                   | 6         | 7      | 0.74%   |
| LITEON                    | 6         | 6      | 0.74%   |
| Union Memory              | 4         | 4      | 0.5%    |
| Team                      | 4         | 4      | 0.5%    |
| SPCC                      | 4         | 5      | 0.5%    |
| Phison                    | 4         | 4      | 0.5%    |
| Micron/Crucial Technology | 4         | 4      | 0.5%    |
| LITEONIT                  | 4         | 8      | 0.5%    |
| Hewlett-Packard           | 4         | 4      | 0.5%    |
| Transcend                 | 3         | 4      | 0.37%   |
| KingSpec                  | 3         | 3      | 0.37%   |
| Intenso                   | 3         | 4      | 0.37%   |
| China                     | 3         | 3      | 0.37%   |
| ASMT                      | 3         | 6      | 0.37%   |
| Solid State Storage       | 2         | 2      | 0.25%   |
| OCZ                       | 2         | 2      | 0.25%   |
| Lenovo                    | 2         | 3      | 0.25%   |
| Indilinx                  | 2         | 2      | 0.25%   |
| Fujitsu                   | 2         | 2      | 0.25%   |
| BIWIN                     | 2         | 2      | 0.25%   |
| XPG                       | 1         | 1      | 0.12%   |
| VALK                      | 1         | 1      | 0.12%   |
| USB3.1                    | 1         | 1      | 0.12%   |
| TwinMOS                   | 1         | 1      | 0.12%   |
| Teclast                   | 1         | 1      | 0.12%   |
| StoreJet                  | 1         | 1      | 0.12%   |
| Silicon Motion            | 1         | 1      | 0.12%   |
| S3+                       | 1         | 1      | 0.12%   |
| PNY                       | 1         | 2      | 0.12%   |
| PLEXTOR                   | 1         | 1      | 0.12%   |
| Phison Electronics        | 1         | 2      | 0.12%   |
| PCIe SSD                  | 1         | 2      | 0.12%   |
| OSCOO                     | 1         | 1      | 0.12%   |
| Netac                     | 1         | 1      | 0.12%   |
| Mushkin                   | 1         | 2      | 0.12%   |
| Lite-On                   | 1         | 2      | 0.12%   |
| KingFast                  | 1         | 1      | 0.12%   |
| HGST HUS                  | 1         | 1      | 0.12%   |
| EZCOOL                    | 1         | 1      | 0.12%   |
| External                  | 1         | 1      | 0.12%   |
| EMTEC                     | 1         | 1      | 0.12%   |
| Dogfish                   | 1         | 1      | 0.12%   |
| Biostar                   | 1         | 1      | 0.12%   |
| ADATA Technology          | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 19        | 2.26%   |
| Samsung NVMe SSD Drive 512GB         | 19        | 2.26%   |
| Toshiba MQ01ABD100 1TB               | 14        | 1.67%   |
| Unknown MMC Card  32GB               | 12        | 1.43%   |
| Toshiba MQ01ABF050 500GB             | 10        | 1.19%   |
| Intel NVMe SSD Drive 512GB           | 10        | 1.19%   |
| HGST HTS721010A9E630 1TB             | 10        | 1.19%   |
| Seagate ST500LT012-1DG142 500GB      | 9         | 1.07%   |
| SK Hynix NVMe SSD Drive 512GB        | 8         | 0.95%   |
| Toshiba MQ04ABF100 1TB               | 7         | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 7         | 0.83%   |
| Sandisk NVMe SSD Drive 512GB         | 6         | 0.72%   |
| HGST HTS545050A7E680 500GB           | 6         | 0.72%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 5         | 0.6%    |
| Unknown MMC Card  64GB               | 5         | 0.6%    |
| Seagate ST9500325AS 500GB            | 5         | 0.6%    |
| Samsung NVMe SSD Drive 1TB           | 5         | 0.6%    |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 4         | 0.48%   |
| Unknown MMC Card  128GB              | 4         | 0.48%   |
| Toshiba NVMe SSD Drive 512GB         | 4         | 0.48%   |
| SK Hynix NVMe SSD Drive 128GB        | 4         | 0.48%   |
| SK Hynix NVMe SSD Drive 1024GB       | 4         | 0.48%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.48%   |
| Samsung NVMe SSD Drive 256GB         | 4         | 0.48%   |
| KIOXIA KBG40ZNV512G 512GB            | 4         | 0.48%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.48%   |
| Kingston SA400S37120G 120GB SSD      | 4         | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 3         | 0.36%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB             | 3         | 0.36%   |
| WDC PC SN730 NVMe 1024GB             | 3         | 0.36%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 3         | 0.36%   |
| SK Hynix BC511 NVMe 512GB            | 3         | 0.36%   |
| Seagate ST9320423AS 320GB            | 3         | 0.36%   |
| Seagate ST9320325AS 320GB            | 3         | 0.36%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 3         | 0.36%   |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 0.36%   |
| SanDisk SSD PLUS 480GB               | 3         | 0.36%   |
| SanDisk SSD PLUS 240GB               | 3         | 0.36%   |
| Sandisk NVMe SSD Drive 256GB         | 3         | 0.36%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.36%   |
| Samsung SSD 840 EVO 120GB            | 3         | 0.36%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 3         | 0.36%   |
| Samsung MZVLQ512HALU-000H1 512GB     | 3         | 0.36%   |
| Samsung HM500JI 500GB                | 3         | 0.36%   |
| Micron/Crucial NVMe SSD Drive 1TB    | 3         | 0.36%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 3         | 0.36%   |
| Kingston SUV400S37120G 120GB SSD     | 3         | 0.36%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.36%   |
| Hitachi HTS545050B9A300 500GB        | 3         | 0.36%   |
| HGST HTS545050A7E380 500GB           | 3         | 0.36%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.36%   |
| A-DATA SP550 240GB SSD               | 3         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.24%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.24%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.24%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 2         | 0.24%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.24%   |
| WDC WD10SPCX-24HWST1 1TB             | 2         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 91     | 34.02%  |
| WDC                 | 58        | 63     | 24.07%  |
| Toshiba             | 47        | 52     | 19.5%   |
| HGST                | 24        | 29     | 9.96%   |
| Hitachi             | 16        | 19     | 6.64%   |
| Samsung Electronics | 5         | 8      | 2.07%   |
| Unknown             | 2         | 2      | 0.83%   |
| Intenso             | 2         | 3      | 0.83%   |
| Fujitsu             | 2         | 2      | 0.83%   |
| ASMT                | 2         | 5      | 0.83%   |
| Apple               | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 66     | 23.46%  |
| SanDisk             | 33        | 38     | 13.58%  |
| Kingston            | 23        | 25     | 9.47%   |
| Crucial             | 22        | 30     | 9.05%   |
| WDC                 | 12        | 12     | 4.94%   |
| Intel               | 11        | 14     | 4.53%   |
| Micron Technology   | 8         | 9      | 3.29%   |
| Toshiba             | 7         | 8      | 2.88%   |
| Patriot             | 6         | 7      | 2.47%   |
| LITEON              | 6         | 6      | 2.47%   |
| SK Hynix            | 5         | 5      | 2.06%   |
| Apple               | 5         | 5      | 2.06%   |
| Team                | 4         | 4      | 1.65%   |
| SPCC                | 4         | 5      | 1.65%   |
| LITEONIT            | 4         | 8      | 1.65%   |
| Hewlett-Packard     | 4         | 4      | 1.65%   |
| A-DATA Technology   | 4         | 4      | 1.65%   |
| Transcend           | 3         | 4      | 1.23%   |
| KingSpec            | 3         | 3      | 1.23%   |
| China               | 3         | 3      | 1.23%   |
| OCZ                 | 2         | 2      | 0.82%   |
| Indilinx            | 2         | 2      | 0.82%   |
| VALK                | 1         | 1      | 0.41%   |
| Union Memory        | 1         | 1      | 0.41%   |
| TwinMOS             | 1         | 1      | 0.41%   |
| Teclast             | 1         | 1      | 0.41%   |
| StoreJet            | 1         | 1      | 0.41%   |
| S3+                 | 1         | 1      | 0.41%   |
| PNY                 | 1         | 2      | 0.41%   |
| PLEXTOR             | 1         | 1      | 0.41%   |
| OSCOO               | 1         | 1      | 0.41%   |
| Lenovo              | 1         | 2      | 0.41%   |
| Intenso             | 1         | 1      | 0.41%   |
| EZCOOL              | 1         | 1      | 0.41%   |
| Dogfish             | 1         | 1      | 0.41%   |
| Biostar             | 1         | 1      | 0.41%   |
| ASMT                | 1         | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 272       | 319    | 34.96%  |
| HDD     | 232       | 275    | 29.82%  |
| SSD     | 226       | 281    | 29.05%  |
| MMC     | 36        | 47     | 4.63%   |
| Unknown | 12        | 15     | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 415       | 534    | 55.56%  |
| NVMe | 271       | 318    | 36.28%  |
| MMC  | 36        | 47     | 4.82%   |
| SAS  | 25        | 38     | 3.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 295       | 367    | 64.84%  |
| 0.51-1.0   | 143       | 167    | 31.43%  |
| 1.01-2.0   | 12        | 12     | 2.64%   |
| 3.01-4.0   | 2         | 3      | 0.44%   |
| 4.01-10.0  | 2         | 6      | 0.44%   |
| 2.01-3.0   | 1         | 1      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 208       | 31%     |
| 251-500        | 192       | 28.61%  |
| 501-1000       | 103       | 15.35%  |
| 51-100         | 50        | 7.45%   |
| 1-20           | 42        | 6.26%   |
| 1001-2000      | 29        | 4.32%   |
| 21-50          | 26        | 3.87%   |
| More than 3000 | 12        | 1.79%   |
| 2001-3000      | 5         | 0.75%   |
| Unknown        | 4         | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 278       | 40.64%  |
| 21-50          | 132       | 19.3%   |
| 51-100         | 104       | 15.2%   |
| 101-250        | 90        | 13.16%  |
| 251-500        | 40        | 5.85%   |
| 501-1000       | 21        | 3.07%   |
| More than 3000 | 7         | 1.02%   |
| 1001-2000      | 7         | 1.02%   |
| Unknown        | 4         | 0.58%   |
| 2001-3000      | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB               | 2         | 2      | 7.41%   |
| WDC WD5000LPLX-60ZNTT1 500GB                  | 1         | 1      | 3.7%    |
| WDC WD3200LPCX-24C6HT0 320GB                  | 1         | 1      | 3.7%    |
| WDC WD3200BEKT-60PVMT0 320GB                  | 1         | 1      | 3.7%    |
| WDC WD10SPZX-17Z10T0 1TB                      | 1         | 1      | 3.7%    |
| Toshiba MK3263GSXN 320GB                      | 1         | 1      | 3.7%    |
| Toshiba MK3252GSX 320GB                       | 1         | 1      | 3.7%    |
| SK Hynix HFS256G39TND-N210A 256GB SSD         | 1         | 1      | 3.7%    |
| Seagate ST9320423AS 320GB                     | 1         | 1      | 3.7%    |
| Seagate ST500LT012-1DG142 500GB               | 1         | 1      | 3.7%    |
| Seagate ST320LT020-9YG142 320GB               | 1         | 1      | 3.7%    |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 3.7%    |
| SanDisk SSD U100 128GB                        | 1         | 1      | 3.7%    |
| SanDisk SSD PLUS 480GB                        | 1         | 1      | 3.7%    |
| SanDisk SDSSDHII240G 240GB                    | 1         | 1      | 3.7%    |
| SanDisk SD7SB3Q128G1002 128GB SSD             | 1         | 1      | 3.7%    |
| Samsung Electronics SSD 860 EVO 500GB         | 1         | 1      | 3.7%    |
| Samsung Electronics SSD 850 EVO 250GB         | 1         | 1      | 3.7%    |
| Micron Technology MTFDDAT256MAM-1K2 256GB SSD | 1         | 1      | 3.7%    |
| LITEONIT LMT-32L3M mSATA 32GB SSD             | 1         | 1      | 3.7%    |
| Intel SSDSC2KF256H6L 256GB                    | 1         | 1      | 3.7%    |
| Intel SSDPEKKF256G7L 256GB                    | 1         | 1      | 3.7%    |
| Hitachi HTS542525K9A300 250GB                 | 1         | 1      | 3.7%    |
| HGST HTS725050A7E630 500GB                    | 1         | 1      | 3.7%    |
| Fujitsu MHV2080BH PL 80GB                     | 1         | 1      | 3.7%    |
| Crucial CT1000P1SSD8 1TB                      | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 22.22%  |
| WDC                 | 4         | 4      | 14.81%  |
| SanDisk             | 4         | 4      | 14.81%  |
| Toshiba             | 2         | 2      | 7.41%   |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Intel               | 2         | 2      | 7.41%   |
| SK Hynix            | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| LITEONIT            | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 1      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |
| Fujitsu             | 1         | 1      | 3.7%    |
| Crucial             | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 40%     |
| WDC     | 4         | 4      | 26.67%  |
| Toshiba | 2         | 2      | 13.33%  |
| Hitachi | 1         | 1      | 6.67%   |
| HGST    | 1         | 1      | 6.67%   |
| Fujitsu | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 55.56%  |
| SSD  | 10        | 10     | 37.04%  |
| NVMe | 2         | 2      | 7.41%   |

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
| Detected | 418       | 592    | 59.38%  |
| Works    | 259       | 318    | 36.79%  |
| Malfunc  | 27        | 27     | 3.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 468       | 58.06%  |
| AMD                            | 70        | 8.68%   |
| Samsung Electronics            | 66        | 8.19%   |
| Sandisk                        | 55        | 6.82%   |
| SK Hynix                       | 39        | 4.84%   |
| Toshiba America Info Systems   | 31        | 3.85%   |
| KIOXIA                         | 16        | 1.99%   |
| Micron Technology              | 14        | 1.74%   |
| Kingston Technology Company    | 8         | 0.99%   |
| Nvidia                         | 6         | 0.74%   |
| Micron/Crucial Technology      | 6         | 0.74%   |
| Phison Electronics             | 5         | 0.62%   |
| ADATA Technology               | 5         | 0.62%   |
| Union Memory (Shenzhen)        | 3         | 0.37%   |
| Silicon Motion                 | 3         | 0.37%   |
| Solid State Storage Technology | 2         | 0.25%   |
| Apple                          | 2         | 0.25%   |
| Unknown                        | 1         | 0.12%   |
| Seagate Technology             | 1         | 0.12%   |
| Realtek Semiconductor          | 1         | 0.12%   |
| Marvell Technology Group       | 1         | 0.12%   |
| Lite-On Technology             | 1         | 0.12%   |
| Lenovo                         | 1         | 0.12%   |
| ASMedia Technology             | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 62        | 7.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 56        | 6.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 50        | 5.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 40        | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 32        | 3.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 30        | 3.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 29        | 3.42%   |
| Samsung NVMe SSD Controller 980                                                  | 26        | 3.07%   |
| Intel Volume Management Device NVMe RAID Controller                              | 25        | 2.95%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 23        | 2.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 22        | 2.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 2.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 17        | 2%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 17        | 2%      |
| KIOXIA Non-Volatile memory controller                                            | 16        | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 1.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 1.77%   |
| Micron Non-Volatile memory controller                                            | 14        | 1.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 1.42%   |
| SK Hynix BC511                                                                   | 12        | 1.42%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 12        | 1.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 12        | 1.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 12        | 1.42%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 11        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 1.3%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 10        | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 1.18%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 9         | 1.06%   |
| SK Hynix NVMe SSD Controller                                                     | 9         | 1.06%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 9         | 1.06%   |
| Intel SSD 660P Series                                                            | 9         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 1.06%   |
| SK Hynix Non-Volatile memory controller                                          | 8         | 0.94%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 8         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 8         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 0.94%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 6         | 0.71%   |
| Sandisk PC SN520 NVMe SSD                                                        | 6         | 0.71%   |
| Intel Non-Volatile memory controller                                             | 6         | 0.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 0.71%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 4         | 0.47%   |
| Kingston Company A2000 NVMe SSD                                                  | 4         | 0.47%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 0.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 4         | 0.47%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.35%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.35%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.35%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.35%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.35%   |
| Intel SSD 600P Series                                                            | 3         | 0.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 3         | 0.35%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 0.35%   |
| ADATA Non-Volatile memory controller                                             | 3         | 0.35%   |
| Solid State Storage Non-Volatile memory controller                               | 2         | 0.24%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.24%   |
| Sandisk Non-Volatile memory controller                                           | 2         | 0.24%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 464       | 55.9%   |
| NVMe | 270       | 32.53%  |
| RAID | 67        | 8.07%   |
| IDE  | 29        | 3.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 550       | 82.58%  |
| AMD    | 116       | 17.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 14        | 2.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 13        | 1.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 1.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 1.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 12        | 1.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 1.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 1.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 1.35%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 9         | 1.35%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 1.2%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 1.2%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 1.05%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 7         | 1.05%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 1.05%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 7         | 1.05%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 6         | 0.9%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 0.9%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.9%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 6         | 0.9%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 0.9%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.75%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 0.75%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 5         | 0.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 5         | 0.75%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 0.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.6%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 4         | 0.6%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.6%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 4         | 0.6%    |
| Intel Core i3-2330M CPU @ 2.20GHz             | 4         | 0.6%    |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 4         | 0.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.6%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 0.6%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 4         | 0.6%    |
| AMD Athlon Silver 3050U with Radeon Graphics  | 4         | 0.6%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.45%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 3         | 0.45%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 3         | 0.45%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.45%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.45%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.45%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 3         | 0.45%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 171       | 25.68%  |
| Intel Core i7                  | 167       | 25.08%  |
| Intel Core i3                  | 55        | 8.26%   |
| Other                          | 50        | 7.51%   |
| Intel Core 2 Duo               | 35        | 5.26%   |
| Intel Celeron                  | 27        | 4.05%   |
| AMD Ryzen 5                    | 27        | 4.05%   |
| AMD Ryzen 7                    | 23        | 3.45%   |
| Intel Pentium                  | 19        | 2.85%   |
| Intel Atom                     | 14        | 2.1%    |
| AMD Ryzen 7 PRO                | 11        | 1.65%   |
| AMD Ryzen 9                    | 9         | 1.35%   |
| AMD Ryzen 3                    | 6         | 0.9%    |
| AMD Athlon                     | 6         | 0.9%    |
| AMD A10                        | 6         | 0.9%    |
| AMD A8                         | 5         | 0.75%   |
| Intel Pentium Silver           | 4         | 0.6%    |
| AMD E                          | 4         | 0.6%    |
| AMD A6                         | 4         | 0.6%    |
| Intel Pentium Dual-Core        | 3         | 0.45%   |
| Intel Core 2                   | 3         | 0.45%   |
| Intel Pentium Dual             | 2         | 0.3%    |
| Intel Core m7                  | 2         | 0.3%    |
| Intel Core i9                  | 2         | 0.3%    |
| AMD E1                         | 2         | 0.3%    |
| Intel Core M                   | 1         | 0.15%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.15%   |
| AMD Ryzen 5 PRO                | 1         | 0.15%   |
| AMD PRO A10                    | 1         | 0.15%   |
| AMD E2                         | 1         | 0.15%   |
| AMD Athlon X2                  | 1         | 0.15%   |
| AMD Athlon II Dual-Core        | 1         | 0.15%   |
| AMD A4                         | 1         | 0.15%   |
| AMD A12                        | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 327       | 49.1%   |
| 4      | 229       | 34.38%  |
| 6      | 59        | 8.86%   |
| 8      | 47        | 7.06%   |
| 1      | 3         | 0.45%   |
| 3      | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 666       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 524       | 78.68%  |
| 1      | 142       | 21.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 665       | 99.85%  |
| Unknown        | 1         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 355       | 52.28%  |
| 0x806c1    | 30        | 4.42%   |
| 0x806ec    | 26        | 3.83%   |
| 0x306a9    | 22        | 3.24%   |
| 0x806ea    | 21        | 3.09%   |
| 0xa0652    | 16        | 2.36%   |
| 0x08600104 | 14        | 2.06%   |
| 0x906ea    | 12        | 1.77%   |
| 0x706e5    | 12        | 1.77%   |
| 0x206a7    | 12        | 1.77%   |
| 0x806e9    | 11        | 1.62%   |
| 0x406e3    | 11        | 1.62%   |
| 0x08600106 | 11        | 1.62%   |
| 0x306d4    | 10        | 1.47%   |
| 0x0a50000c | 10        | 1.47%   |
| 0x906e9    | 9         | 1.33%   |
| 0x806d1    | 7         | 1.03%   |
| 0x40651    | 7         | 1.03%   |
| 0x806eb    | 6         | 0.88%   |
| 0x306c3    | 6         | 0.88%   |
| 0x08600103 | 6         | 0.88%   |
| 0x08108109 | 6         | 0.88%   |
| 0x506e3    | 5         | 0.74%   |
| 0x1067a    | 5         | 0.74%   |
| 0x406c4    | 4         | 0.59%   |
| 0x30678    | 4         | 0.59%   |
| 0x20655    | 4         | 0.59%   |
| 0x0a50000b | 4         | 0.59%   |
| 0x08108102 | 3         | 0.44%   |
| 0x06006705 | 3         | 0.44%   |
| 0x706a1    | 2         | 0.29%   |
| 0x6fd      | 2         | 0.29%   |
| 0x106e5    | 2         | 0.29%   |
| 0x08608103 | 2         | 0.29%   |
| 0x08200103 | 2         | 0.29%   |
| 0x0810100b | 2         | 0.29%   |
| 0x05000119 | 2         | 0.29%   |
| 0x906ed    | 1         | 0.15%   |
| 0x706a8    | 1         | 0.15%   |
| 0x406c3    | 1         | 0.15%   |
| 0x30673    | 1         | 0.15%   |
| 0x20652    | 1         | 0.15%   |
| 0x08608102 | 1         | 0.15%   |
| 0x07030106 | 1         | 0.15%   |
| 0x07030105 | 1         | 0.15%   |
| 0x0700010f | 1         | 0.15%   |
| 0x06006704 | 1         | 0.15%   |
| 0x0600611a | 1         | 0.15%   |
| 0x06006110 | 1         | 0.15%   |
| 0x02000032 | 1         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 144       | 21.62%  |
| IvyBridge       | 52        | 7.81%   |
| Haswell         | 48        | 7.21%   |
| SandyBridge     | 47        | 7.06%   |
| Zen 2           | 38        | 5.71%   |
| TigerLake       | 37        | 5.56%   |
| Skylake         | 35        | 5.26%   |
| Silvermont      | 30        | 4.5%    |
| Penryn          | 29        | 4.35%   |
| Westmere        | 27        | 4.05%   |
| IceLake         | 26        | 3.9%    |
| Broadwell       | 23        | 3.45%   |
| CometLake       | 22        | 3.3%    |
| Zen 3           | 18        | 2.7%    |
| Zen+            | 17        | 2.55%   |
| Core            | 14        | 2.1%    |
| Excavator       | 10        | 1.5%    |
| Goldmont plus   | 7         | 1.05%   |
| Unknown         | 7         | 1.05%   |
| Zen             | 5         | 0.75%   |
| Piledriver      | 5         | 0.75%   |
| Bobcat          | 5         | 0.75%   |
| Puma            | 4         | 0.6%    |
| Nehalem         | 3         | 0.45%   |
| Jaguar          | 3         | 0.45%   |
| K8 & K10 hybrid | 2         | 0.3%    |
| Goldmont        | 2         | 0.3%    |
| Bonnell         | 2         | 0.3%    |
| Steamroller     | 1         | 0.15%   |
| K8 Hammer       | 1         | 0.15%   |
| K10 Llano       | 1         | 0.15%   |
| K10             | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 493       | 58.27%  |
| Nvidia | 204       | 24.11%  |
| AMD    | 149       | 17.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 47        | 5.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 43        | 4.98%   |
| AMD Renoir                                                                               | 37        | 4.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 32        | 3.71%   |
| Intel UHD Graphics 620                                                                   | 31        | 3.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 31        | 3.59%   |
| Intel HD Graphics 620                                                                    | 27        | 3.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 2.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 2.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 2.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 2.32%   |
| Intel HD Graphics 5500                                                                   | 19        | 2.2%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 19        | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 2.2%    |
| AMD Picasso                                                                              | 19        | 2.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 2.09%   |
| AMD Cezanne                                                                              | 17        | 1.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 1.51%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 1.39%   |
| Intel HD Graphics 530                                                                    | 12        | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 10        | 1.16%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.04%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.93%   |
| Intel HD Graphics 630                                                                    | 8         | 0.93%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 7         | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.7%    |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.58%   |
| Nvidia GP108M [GeForce MX250]                                                            | 5         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.58%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.58%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.58%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.58%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.58%   |
| AMD Lucienne                                                                             | 5         | 0.58%   |
| Nvidia TU117M                                                                            | 4         | 0.46%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.46%   |
| Intel Tiger Lake UHD Graphics                                                            | 4         | 0.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.46%   |
| AMD Opal PRO [Radeon R7 M260X]                                                           | 4         | 0.46%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 3         | 0.35%   |
| Nvidia GP108M [GeForce MX230]                                                            | 3         | 0.35%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 3         | 0.35%   |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 0.35%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 3         | 0.35%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.35%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.35%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 0.35%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.35%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.35%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 3         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 333       | 50%     |
| Intel + Nvidia | 138       | 20.72%  |
| 1 x AMD        | 98        | 14.71%  |
| 1 x Nvidia     | 46        | 6.91%   |
| Intel + AMD    | 22        | 3.3%    |
| AMD + Nvidia   | 20        | 3%      |
| 2 x AMD        | 9         | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 565       | 84.2%   |
| Proprietary | 98        | 14.61%  |
| Unknown     | 8         | 1.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 500       | 74.52%  |
| 1.01-2.0   | 48        | 7.15%   |
| 0.01-0.5   | 44        | 6.56%   |
| 3.01-4.0   | 36        | 5.37%   |
| 5.01-6.0   | 18        | 2.68%   |
| 0.51-1.0   | 15        | 2.24%   |
| 7.01-8.0   | 5         | 0.75%   |
| 8.01-16.0  | 3         | 0.45%   |
| 2.01-3.0   | 2         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 152       | 19.51%  |
| LG Display              | 118       | 15.15%  |
| BOE                     | 94        | 12.07%  |
| Chimei Innolux          | 93        | 11.94%  |
| Samsung Electronics     | 74        | 9.5%    |
| Sharp                   | 32        | 4.11%   |
| Dell                    | 24        | 3.08%   |
| Goldstar                | 21        | 2.7%    |
| Apple                   | 18        | 2.31%   |
| Hewlett-Packard         | 16        | 2.05%   |
| Chi Mei Optoelectronics | 15        | 1.93%   |
| PANDA                   | 14        | 1.8%    |
| Lenovo                  | 13        | 1.67%   |
| Acer                    | 13        | 1.67%   |
| BenQ                    | 7         | 0.9%    |
| Philips                 | 6         | 0.77%   |
| InfoVision              | 6         | 0.77%   |
| Unknown                 | 5         | 0.64%   |
| TMX                     | 4         | 0.51%   |
| Iiyama                  | 4         | 0.51%   |
| ASUSTek Computer        | 4         | 0.51%   |
| Ancor Communications    | 4         | 0.51%   |
| LGD                     | 3         | 0.39%   |
| LG Philips              | 3         | 0.39%   |
| CSO                     | 3         | 0.39%   |
| ViewSonic               | 2         | 0.26%   |
| Toshiba                 | 2         | 0.26%   |
| Sony                    | 2         | 0.26%   |
| Sceptre Tech            | 2         | 0.26%   |
| JDI                     | 2         | 0.26%   |
| CHR                     | 2         | 0.26%   |
| AOC                     | 2         | 0.26%   |
| Westinghouse            | 1         | 0.13%   |
| Vizio                   | 1         | 0.13%   |
| Unknown (XXX)           | 1         | 0.13%   |
| TIANMA XM               | 1         | 0.13%   |
| SGT                     | 1         | 0.13%   |
| Sanyo                   | 1         | 0.13%   |
| S2-Tek                  | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| Nvidia                  | 1         | 0.13%   |
| MiTAC                   | 1         | 0.13%   |
| LG Electronics          | 1         | 0.13%   |
| Insignia                | 1         | 0.13%   |
| Hitachi                 | 1         | 0.13%   |
| HannStar                | 1         | 0.13%   |
| Fujitsu Siemens         | 1         | 0.13%   |
| Denver                  | 1         | 0.13%   |
| CPT                     | 1         | 0.13%   |
| Cbox                    | 1         | 0.13%   |
| BOE Technology Group    | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 1.14%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 1.01%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 6         | 0.76%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.63%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                  | 4         | 0.51%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 4         | 0.51%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 4         | 0.51%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 3         | 0.38%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD056D 1920x1080 380x210mm 17.1-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD03EE 1366x768 277x156mm 12.5-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.38%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch                  | 3         | 0.38%   |
| InfoVision LCD Monitor IVO061F 1920x1080 344x194mm 15.5-inch             | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 3         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 3         | 0.38%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 3         | 0.38%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.38%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO31EC 1366x768 340x190mm 15.3-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.38%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 3         | 0.38%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 3         | 0.38%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 2         | 0.25%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                  | 2         | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.25%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch                  | 2         | 0.25%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC324C 1366x768 353x198mm 15.9-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch    | 2         | 0.25%   |
| Samsung Electronics EPSON PJ SECA603 1920x1080 1600x900mm 72.3-inch      | 2         | 0.25%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                  | 2         | 0.25%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.25%   |
| LG Philips LCD Monitor LPL0301 1280x800 331x207mm 15.4-inch              | 2         | 0.25%   |
| LG Display LP156WH2-TLBA LGD026C 1366x768 344x194mm 15.5-inch            | 2         | 0.25%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 321       | 44.21%  |
| 1366x768 (WXGA)    | 195       | 26.86%  |
| 1600x900 (HD+)     | 44        | 6.06%   |
| 3840x2160 (4K)     | 28        | 3.86%   |
| 1280x800 (WXGA)    | 25        | 3.44%   |
| 2560x1440 (QHD)    | 19        | 2.62%   |
| 1920x1200 (WUXGA)  | 13        | 1.79%   |
| 1440x900 (WXGA+)   | 13        | 1.79%   |
| 2560x1600          | 7         | 0.96%   |
| 1280x1024 (SXGA)   | 6         | 0.83%   |
| 3440x1440          | 5         | 0.69%   |
| Unknown            | 5         | 0.69%   |
| 3200x2000          | 4         | 0.55%   |
| 2160x1440          | 4         | 0.55%   |
| 3840x2400          | 3         | 0.41%   |
| 3456x2160          | 3         | 0.41%   |
| 3200x1800 (QHD+)   | 3         | 0.41%   |
| 3000x2000          | 3         | 0.41%   |
| 2560x1080          | 3         | 0.41%   |
| 2256x1504          | 2         | 0.28%   |
| 1920x540           | 2         | 0.28%   |
| 1920x1280          | 2         | 0.28%   |
| 1680x1050 (WSXGA+) | 2         | 0.28%   |
| 1360x768           | 2         | 0.28%   |
| 5760x2160          | 1         | 0.14%   |
| 3840x1200          | 1         | 0.14%   |
| 3840x1080          | 1         | 0.14%   |
| 3520x1080          | 1         | 0.14%   |
| 3280x1050          | 1         | 0.14%   |
| 2880x1800          | 1         | 0.14%   |
| 2304x1440          | 1         | 0.14%   |
| 1680x945           | 1         | 0.14%   |
| 1600x1200          | 1         | 0.14%   |
| 1280x768           | 1         | 0.14%   |
| 1080x2160          | 1         | 0.14%   |
| 1024x600           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 319       | 40.95%  |
| 13      | 110       | 14.12%  |
| 14      | 91        | 11.68%  |
| 17      | 61        | 7.83%   |
| 23      | 29        | 3.72%   |
| 24      | 25        | 3.21%   |
| 27      | 21        | 2.7%    |
| 21      | 21        | 2.7%    |
| 12      | 19        | 2.44%   |
| Unknown | 13        | 1.67%   |
| 19      | 12        | 1.54%   |
| 11      | 12        | 1.54%   |
| 34      | 7         | 0.9%    |
| 31      | 7         | 0.9%    |
| 16      | 7         | 0.9%    |
| 18      | 4         | 0.51%   |
| 84      | 2         | 0.26%   |
| 72      | 2         | 0.26%   |
| 48      | 2         | 0.26%   |
| 40      | 2         | 0.26%   |
| 22      | 2         | 0.26%   |
| 20      | 2         | 0.26%   |
| 10      | 2         | 0.26%   |
| 54      | 1         | 0.13%   |
| 49      | 1         | 0.13%   |
| 43      | 1         | 0.13%   |
| 42      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |
| 29      | 1         | 0.13%   |
| 5       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 450       | 58.14%  |
| 201-300     | 97        | 12.53%  |
| 351-400     | 75        | 9.69%   |
| 501-600     | 70        | 9.04%   |
| 401-500     | 38        | 4.91%   |
| Unknown     | 13        | 1.68%   |
| 601-700     | 10        | 1.29%   |
| 701-800     | 8         | 1.03%   |
| 1501-2000   | 4         | 0.52%   |
| 1001-1500   | 4         | 0.52%   |
| 801-900     | 3         | 0.39%   |
| 901-1000    | 1         | 0.13%   |
| 1-100       | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 563       | 83.28%  |
| 16/10   | 71        | 10.5%   |
| 3/2     | 13        | 1.92%   |
| Unknown | 10        | 1.48%   |
| 21/9    | 8         | 1.18%   |
| 5/4     | 6         | 0.89%   |
| 4/3     | 2         | 0.3%    |
| 32/9    | 1         | 0.15%   |
| 1.96    | 1         | 0.15%   |
| 0.46    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 321       | 41.42%  |
| 81-90          | 155       | 20%     |
| 201-250        | 64        | 8.26%   |
| 121-130        | 57        | 7.35%   |
| 71-80          | 45        | 5.81%   |
| 301-350        | 22        | 2.84%   |
| 61-70          | 19        | 2.45%   |
| 151-200        | 19        | 2.45%   |
| 351-500        | 15        | 1.94%   |
| Unknown        | 13        | 1.68%   |
| 51-60          | 12        | 1.55%   |
| More than 1000 | 7         | 0.9%    |
| 251-300        | 5         | 0.65%   |
| 141-150        | 5         | 0.65%   |
| 501-1000       | 5         | 0.65%   |
| 111-120        | 4         | 0.52%   |
| 41-50          | 2         | 0.26%   |
| 131-140        | 2         | 0.26%   |
| 91-100         | 2         | 0.26%   |
| 1-40           | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 304       | 39.84%  |
| 101-120       | 219       | 28.7%   |
| 51-100        | 123       | 16.12%  |
| 161-240       | 57        | 7.47%   |
| More than 240 | 38        | 4.98%   |
| Unknown       | 13        | 1.7%    |
| 1-50          | 9         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 508       | 75.71%  |
| 2     | 131       | 19.52%  |
| 0     | 20        | 2.98%   |
| 3     | 11        | 1.64%   |
| 4     | 1         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 378       | 36.59%  |
| Realtek Semiconductor             | 331       | 32.04%  |
| Qualcomm Atheros                  | 143       | 13.84%  |
| Broadcom                          | 71        | 6.87%   |
| Marvell Technology Group          | 14        | 1.36%   |
| Broadcom Limited                  | 13        | 1.26%   |
| MEDIATEK                          | 9         | 0.87%   |
| Ralink                            | 8         | 0.77%   |
| TP-Link                           | 6         | 0.58%   |
| JMicron Technology                | 6         | 0.58%   |
| Hewlett-Packard                   | 6         | 0.58%   |
| Dell                              | 5         | 0.48%   |
| Samsung Electronics               | 4         | 0.39%   |
| Lenovo                            | 4         | 0.39%   |
| Ericsson Business Mobile Networks | 4         | 0.39%   |
| NetGear                           | 3         | 0.29%   |
| DisplayLink                       | 3         | 0.29%   |
| Xiaomi                            | 2         | 0.19%   |
| U-Blox                            | 2         | 0.19%   |
| Sierra Wireless                   | 2         | 0.19%   |
| Ralink Technology                 | 2         | 0.19%   |
| Nvidia                            | 2         | 0.19%   |
| Edimax Technology                 | 2         | 0.19%   |
| ASUSTek Computer                  | 2         | 0.19%   |
| ASIX Electronics                  | 2         | 0.19%   |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Huawei Technologies               | 1         | 0.1%    |
| Google                            | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| D-Link                            | 1         | 0.1%    |
| Arduino SA                        | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 211       | 17.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 4.56%   |
| Intel Wi-Fi 6 AX200                                               | 48        | 3.91%   |
| Intel Wi-Fi 6 AX201                                               | 31        | 2.52%   |
| Intel Wireless 8265 / 8275                                        | 28        | 2.28%   |
| Intel Wireless 7265                                               | 27        | 2.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 2.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 25        | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24        | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 22        | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 21        | 1.71%   |
| Intel Wireless 7260                                               | 19        | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 19        | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 19        | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 1.22%   |
| Intel Wireless 8260                                               | 15        | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 15        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                     | 14        | 1.14%   |
| Intel Wireless 3165                                               | 13        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 13        | 1.06%   |
| Intel Wireless 3160                                               | 12        | 0.98%   |
| Intel Centrino Advanced-N 6235                                    | 12        | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 10        | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 0.81%   |
| MEDIATEK Network controller                                       | 9         | 0.73%   |
| Intel Centrino Advanced-N 6200                                    | 9         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.65%   |
| Intel Wireless-AC 9260                                            | 8         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.57%   |
| Intel WiFi Link 5100                                              | 7         | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 7         | 0.57%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 6         | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.49%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.49%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 0.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 6         | 0.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 0.41%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.41%   |
| TP-Link USB 10/100/1000 LAN                                       | 4         | 0.33%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 4         | 0.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 363       | 53.86%  |
| Qualcomm Atheros                  | 125       | 18.55%  |
| Realtek Semiconductor             | 81        | 12.02%  |
| Broadcom                          | 59        | 8.75%   |
| Broadcom Limited                  | 10        | 1.48%   |
| MEDIATEK                          | 9         | 1.34%   |
| Ralink                            | 8         | 1.19%   |
| Dell                              | 3         | 0.45%   |
| TP-Link                           | 2         | 0.3%    |
| Sierra Wireless                   | 2         | 0.3%    |
| Ralink Technology                 | 2         | 0.3%    |
| NetGear                           | 2         | 0.3%    |
| Edimax Technology                 | 2         | 0.3%    |
| Qualcomm Atheros Communications   | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| Fibocom                           | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |
| D-Link                            | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 48        | 7.08%   |
| Intel Wi-Fi 6 AX201                                            | 31        | 4.57%   |
| Intel Wireless 8265 / 8275                                     | 28        | 4.13%   |
| Intel Wireless 7265                                            | 27        | 3.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 25        | 3.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 24        | 3.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 24        | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 22        | 3.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 21        | 3.1%    |
| Intel Wireless 7260                                            | 19        | 2.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 19        | 2.8%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 2.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 2.21%   |
| Intel Wireless 8260                                            | 15        | 2.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 15        | 2.21%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 2.06%   |
| Intel Wireless 3165                                            | 13        | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 1.92%   |
| Intel Wireless 3160                                            | 12        | 1.77%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 1.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 1.47%   |
| MEDIATEK Network controller                                    | 9         | 1.33%   |
| Intel Centrino Advanced-N 6200                                 | 9         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.18%   |
| Intel Wireless-AC 9260                                         | 8         | 1.18%   |
| Intel WiFi Link 5100                                           | 7         | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 1.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 6         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.59%   |
| Realtek 802.11ac NIC                                           | 4         | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4         | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.59%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 0.44%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 0.44%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.44%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.44%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 3         | 0.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.29%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.29%   |
| Realtek RTL8187 Wireless Adapter                               | 2         | 0.29%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 0.29%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.29%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 2         | 0.29%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 0.29%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 295       | 54.93%  |
| Intel                         | 125       | 23.28%  |
| Qualcomm Atheros              | 35        | 6.52%   |
| Broadcom                      | 27        | 5.03%   |
| Marvell Technology Group      | 14        | 2.61%   |
| JMicron Technology            | 6         | 1.12%   |
| TP-Link                       | 4         | 0.74%   |
| Samsung Electronics           | 4         | 0.74%   |
| Lenovo                        | 4         | 0.74%   |
| Hewlett-Packard               | 4         | 0.74%   |
| DisplayLink                   | 3         | 0.56%   |
| Broadcom Limited              | 3         | 0.56%   |
| Xiaomi                        | 2         | 0.37%   |
| Nvidia                        | 2         | 0.37%   |
| ASIX Electronics              | 2         | 0.37%   |
| OnePlus Technology (Shenzhen) | 1         | 0.19%   |
| NetGear                       | 1         | 0.19%   |
| Motorola PCS                  | 1         | 0.19%   |
| ICS Advent                    | 1         | 0.19%   |
| Huawei Technologies           | 1         | 0.19%   |
| Google                        | 1         | 0.19%   |
| ASUSTek Computer              | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 211       | 39.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 56        | 10.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 27        | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 22        | 4.07%   |
| Intel Ethernet Connection I218-LM                                              | 10        | 1.85%   |
| Intel 82577LM Gigabit Network Connection                                       | 10        | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                                          | 8         | 1.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 7         | 1.3%    |
| Intel Ethernet Connection I217-LM                                              | 7         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                                          | 7         | 1.3%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 6         | 1.11%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 6         | 1.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 1.11%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.93%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 0.93%   |
| TP-Link USB 10/100/1000 LAN                                                    | 4         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.74%   |
| Intel 82579V Gigabit Network Connection                                        | 4         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 0.74%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 4         | 0.74%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 3         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 0.56%   |
| Lenovo ThinkPad Lan                                                            | 3         | 0.56%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.56%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.37%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.37%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 2         | 0.37%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.37%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.37%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.37%   |
| Intel Ethernet Connection (10) I219-LM                                         | 2         | 0.37%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.37%   |
| Xiaomi SDM660-MTP _SN:6C524624                                                 | 1         | 0.19%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.19%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.19%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.19%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.19%   |
| OnePlus (Shenzhen) IN2013                                                      | 1         | 0.19%   |
| NetGear LB1120-100NAS                                                          | 1         | 0.19%   |
| Motorola PCS Moto E (4)                                                        | 1         | 0.19%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 651       | 55.4%   |
| Ethernet | 514       | 43.74%  |
| Modem    | 9         | 0.77%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 577       | 70.71%  |
| Ethernet | 239       | 29.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 474       | 71.17%  |
| 1     | 179       | 26.88%  |
| 0     | 9         | 1.35%   |
| 3     | 4         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 496       | 74.25%  |
| Yes  | 172       | 25.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 297       | 54.3%   |
| Qualcomm Atheros Communications | 54        | 9.87%   |
| Realtek Semiconductor           | 47        | 8.59%   |
| Broadcom                        | 31        | 5.67%   |
| IMC Networks                    | 19        | 3.47%   |
| Apple                           | 17        | 3.11%   |
| Lite-On Technology              | 15        | 2.74%   |
| Foxconn / Hon Hai               | 13        | 2.38%   |
| Dell                            | 10        | 1.83%   |
| Realtek                         | 8         | 1.46%   |
| Cambridge Silicon Radio         | 8         | 1.46%   |
| Ralink                          | 6         | 1.1%    |
| Hewlett-Packard                 | 5         | 0.91%   |
| ASUSTek Computer                | 5         | 0.91%   |
| Toshiba                         | 4         | 0.73%   |
| Alps Electric                   | 4         | 0.73%   |
| Foxconn International           | 2         | 0.37%   |
| Chicony Electronics             | 1         | 0.18%   |
| Askey Computer                  | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 110       | 20.11%  |
| Intel AX201 Bluetooth                                                               | 68        | 12.43%  |
| Intel Bluetooth Device                                                              | 46        | 8.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 41        | 7.5%    |
| Realtek Bluetooth Radio                                                             | 32        | 5.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 25        | 4.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 14        | 2.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 13        | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 10        | 1.83%   |
| Lite-On Bluetooth Device                                                            | 10        | 1.83%   |
| Realtek Bluetooth Radio                                                             | 8         | 1.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 8         | 1.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 1.46%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 1.46%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 1.46%   |
| Apple Bluetooth Host Controller                                                     | 8         | 1.46%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 1.28%   |
| IMC Networks Wireless_Device                                                        | 7         | 1.28%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.1%    |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.91%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 5         | 0.91%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 0.73%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 0.73%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.73%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.73%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.55%   |
| Realtek 802.11n WLAN Adapter                                                        | 3         | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 0.55%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.55%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.55%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.55%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 0.55%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 3         | 0.55%   |
| Lite-On Wireless_Device                                                             | 2         | 0.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.37%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.37%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.37%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 2         | 0.37%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 2         | 0.37%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.18%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.18%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.18%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.18%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.18%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.18%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.18%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.18%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.18%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.18%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 1         | 0.18%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.18%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.18%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.18%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.18%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 533       | 66.54%  |
| AMD                                             | 129       | 16.1%   |
| Nvidia                                          | 98        | 12.23%  |
| C-Media Electronics                             | 5         | 0.62%   |
| Lenovo                                          | 3         | 0.37%   |
| GN Netcom                                       | 3         | 0.37%   |
| Texas Instruments                               | 2         | 0.25%   |
| Sennheiser Communications                       | 2         | 0.25%   |
| Samson Technologies                             | 2         | 0.25%   |
| Realtek Semiconductor                           | 2         | 0.25%   |
| Logitech                                        | 2         | 0.25%   |
| Focusrite-Novation                              | 2         | 0.25%   |
| Creative Technology                             | 2         | 0.25%   |
| USB MICROPHONE                                  | 1         | 0.12%   |
| SteelSeries ApS                                 | 1         | 0.12%   |
| RODE Microphones                                | 1         | 0.12%   |
| No brand                                        | 1         | 0.12%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.12%   |
| JMTek                                           | 1         | 0.12%   |
| Hewlett-Packard                                 | 1         | 0.12%   |
| Elitegroup Computer Systems (ECS)               | 1         | 0.12%   |
| Dell                                            | 1         | 0.12%   |
| Datelink Technology                             | 1         | 0.12%   |
| Corsair                                         | 1         | 0.12%   |
| C&T12L5V                                        | 1         | 0.12%   |
| Barco Display Systems                           | 1         | 0.12%   |
| Astro Gaming                                    | 1         | 0.12%   |
| Apple                                           | 1         | 0.12%   |
| Afatech                                         | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 83        | 8.5%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 82        | 8.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 61        | 6.24%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 50        | 5.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 38        | 3.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 37        | 3.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 3.17%   |
| Intel 8 Series HD Audio Controller                                                                | 31        | 3.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 30        | 3.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 27        | 2.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 25        | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 2.35%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 2.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 2.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 21        | 2.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 2.15%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 1.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 1.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 16        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.54%   |
| Intel CM238 HD Audio Controller                                                                   | 12        | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9         | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 9         | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 0.82%   |
| Nvidia Audio device                                                                               | 8         | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 0.51%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.51%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.41%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.41%   |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.31%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.31%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.31%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.31%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                                         | 3         | 0.31%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.31%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.31%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.2%    |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.2%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.2%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.2%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.2%    |
| Intel USB PnP Sound Device                                                                        | 2         | 0.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.2%    |
| C-Media Electronics CM108 Audio Controller                                                        | 2         | 0.2%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 139       | 33.02%  |
| SK Hynix            | 95        | 22.57%  |
| Micron Technology   | 58        | 13.78%  |
| Kingston            | 40        | 9.5%    |
| Unknown             | 23        | 5.46%   |
| Crucial             | 15        | 3.56%   |
| Ramaxel Technology  | 8         | 1.9%    |
| A-DATA Technology   | 7         | 1.66%   |
| Elpida              | 5         | 1.19%   |
| Team                | 4         | 0.95%   |
| Smart               | 4         | 0.95%   |
| Nanya Technology    | 4         | 0.95%   |
| G.Skill             | 4         | 0.95%   |
| Corsair             | 4         | 0.95%   |
| Unknown (ABCD)      | 3         | 0.71%   |
| Transcend           | 2         | 0.48%   |
| Unknown (09D5)      | 1         | 0.24%   |
| Unknown (08AE)      | 1         | 0.24%   |
| Smart Modular       | 1         | 0.24%   |
| SHARETRONIC         | 1         | 0.24%   |
| High Bridge         | 1         | 0.24%   |
| GOODRAM             | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 10        | 2.25%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 2.03%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 7         | 1.58%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s   | 7         | 1.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.35%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 5         | 1.13%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 5         | 1.13%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s         | 5         | 1.13%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 1.13%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 1.13%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 1.13%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.9%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.9%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.9%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.9%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.9%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 4         | 0.9%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.68%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.68%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.68%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 3         | 0.68%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.68%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.68%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s         | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.45%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.45%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 2         | 0.45%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.45%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.45%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.45%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 2         | 0.45%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 2         | 0.45%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.45%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.45%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.45%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.45%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.45%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.45%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.45%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.45%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.45%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.45%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.45%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.45%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.45%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.45%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.45%   |
| SK Hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.45%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 215       | 59.23%  |
| DDR3   | 97        | 26.72%  |
| LPDDR3 | 22        | 6.06%   |
| LPDDR4 | 21        | 5.79%   |
| DDR2   | 7         | 1.93%   |
| SDRAM  | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 306       | 82.7%   |
| Row Of Chips | 60        | 16.22%  |
| DIMM         | 2         | 0.54%   |
| Chip         | 1         | 0.27%   |
| Unknown      | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 155       | 40.26%  |
| 4096  | 114       | 29.61%  |
| 16384 | 64        | 16.62%  |
| 2048  | 36        | 9.35%   |
| 32768 | 11        | 2.86%   |
| 1024  | 5         | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 98        | 25.06%  |
| 3200    | 96        | 24.55%  |
| 1600    | 74        | 18.93%  |
| 2133    | 27        | 6.91%   |
| 2400    | 26        | 6.65%   |
| 1334    | 16        | 4.09%   |
| 4267    | 14        | 3.58%   |
| 1333    | 11        | 2.81%   |
| 1867    | 8         | 2.05%   |
| 800     | 5         | 1.28%   |
| 3266    | 4         | 1.02%   |
| Unknown | 3         | 0.77%   |
| 975     | 2         | 0.51%   |
| 4266    | 1         | 0.26%   |
| 3733    | 1         | 0.26%   |
| 2048    | 1         | 0.26%   |
| 1777    | 1         | 0.26%   |
| 1066    | 1         | 0.26%   |
| 667     | 1         | 0.26%   |
| 533     | 1         | 0.26%   |

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


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Ultima Electronics | 1         | 33.33%  |
| Seiko Epson        | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000              | 1         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 33.33%  |
| Canon CanoScan LiDE 600F              | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 161       | 26.7%   |
| IMC Networks                           | 63        | 10.45%  |
| Realtek Semiconductor                  | 59        | 9.78%   |
| Microdia                               | 53        | 8.79%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 5.8%    |
| Acer                                   | 35        | 5.8%    |
| Quanta                                 | 31        | 5.14%   |
| Sunplus Innovation Technology          | 29        | 4.81%   |
| Lite-On Technology                     | 19        | 3.15%   |
| Suyin                                  | 18        | 2.99%   |
| Apple                                  | 15        | 2.49%   |
| Silicon Motion                         | 14        | 2.32%   |
| Syntek                                 | 11        | 1.82%   |
| Ricoh                                  | 7         | 1.16%   |
| Alcor Micro                            | 7         | 1.16%   |
| Luxvisions Innotech Limited            | 6         | 1%      |
| Samsung Electronics                    | 5         | 0.83%   |
| Logitech                               | 5         | 0.83%   |
| OmniVision Technologies                | 3         | 0.5%    |
| Lenovo                                 | 3         | 0.5%    |
| Intel                                  | 2         | 0.33%   |
| Importek                               | 2         | 0.33%   |
| 8SSC20F27114V1SR11K1SE2                | 2         | 0.33%   |
| Unknown                                | 1         | 0.17%   |
| Trust                                  | 1         | 0.17%   |
| SunplusIT                              | 1         | 0.17%   |
| Sunplus Technology                     | 1         | 0.17%   |
| Sonix Technology                       | 1         | 0.17%   |
| Primax Electronics                     | 1         | 0.17%   |
| Pixart Imaging                         | 1         | 0.17%   |
| OPPO Electronics                       | 1         | 0.17%   |
| Microsoft                              | 1         | 0.17%   |
| LG Electronics                         | 1         | 0.17%   |
| kingcome                               | 1         | 0.17%   |
| Huawei Technologies                    | 1         | 0.17%   |
| Guillemot                              | 1         | 0.17%   |
| Genesys Logic                          | 1         | 0.17%   |
| Generalplus Technology                 | 1         | 0.17%   |
| DJKANA1RSEYCJF                         | 1         | 0.17%   |
| ARC International                      | 1         | 0.17%   |
| ALi                                    | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 36        | 5.97%   |
| Chicony Integrated Camera                                                  | 32        | 5.31%   |
| Realtek Integrated_Webcam_HD                                               | 30        | 4.98%   |
| IMC Networks Integrated Camera                                             | 25        | 4.15%   |
| Chicony HD Webcam                                                          | 19        | 3.15%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 14        | 2.32%   |
| Quanta HD User Facing                                                      | 11        | 1.82%   |
| Acer Integrated Camera                                                     | 11        | 1.82%   |
| Chicony USB2.0 Camera                                                      | 8         | 1.33%   |
| Sunplus Integrated_Webcam_HD                                               | 7         | 1.16%   |
| Realtek USB Camera                                                         | 7         | 1.16%   |
| Chicony Integrated HP HD Webcam                                            | 7         | 1.16%   |
| Chicony HP TrueVision HD                                                   | 7         | 1.16%   |
| Chicony HP HD Camera                                                       | 7         | 1.16%   |
| Acer BisonCam, NB Pro                                                      | 7         | 1.16%   |
| Syntek Integrated Camera                                                   | 6         | 1%      |
| Lite-On HP HD Camera                                                       | 6         | 1%      |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 6         | 1%      |
| Chicony Lenovo EasyCamera                                                  | 6         | 1%      |
| Samsung Galaxy A5 (MTP)                                                    | 5         | 0.83%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 0.83%   |
| Chicony USB2.0 HD UVC WebCam                                               | 5         | 0.83%   |
| Chicony USB 2.0 Camera                                                     | 5         | 0.83%   |
| Chicony HP Wide Vision HD Camera                                           | 5         | 0.83%   |
| Chicony HD User Facing                                                     | 5         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 5         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 5         | 0.83%   |
| Apple FaceTime HD Camera                                                   | 5         | 0.83%   |
| Apple Built-in iSight                                                      | 5         | 0.83%   |
| Acer Lenovo EasyCamera                                                     | 5         | 0.83%   |
| Sunplus HD WebCam                                                          | 4         | 0.66%   |
| Realtek Integrated Webcam                                                  | 4         | 0.66%   |
| Quanta HP Wide Vision HD Camera                                            | 4         | 0.66%   |
| Lite-On Integrated Camera                                                  | 4         | 0.66%   |
| Lite-On HP HD Webcam                                                       | 4         | 0.66%   |
| IMC Networks Integrated Webcam                                             | 4         | 0.66%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 0.66%   |
| Chicony FJ Camera                                                          | 4         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam               | 4         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 4         | 0.66%   |
| Acer SunplusIT Integrated Camera                                           | 4         | 0.66%   |
| Suyin HP Truevision HD                                                     | 3         | 0.5%    |
| Suyin 1.3M HD WebCam                                                       | 3         | 0.5%    |
| Realtek USB2.0 HD UVC WebCam                                               | 3         | 0.5%    |
| Realtek Lenovo EasyCamera                                                  | 3         | 0.5%    |
| Quanta HP HD Camera                                                        | 3         | 0.5%    |
| Quanta HD Webcam                                                           | 3         | 0.5%    |
| Microdia Integrated Webcam                                                 | 3         | 0.5%    |
| Luxvisions Innotech Limited HP HD Camera                                   | 3         | 0.5%    |
| Lite-On HP Wide Vision HD Camera                                           | 3         | 0.5%    |
| IMC Networks ov9734_azurewave_camera                                       | 3         | 0.5%    |
| Chicony VGA Webcam                                                         | 3         | 0.5%    |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 0.5%    |
| Chicony HP Webcam                                                          | 3         | 0.5%    |
| Chicony HP Truevision HD camera                                            | 3         | 0.5%    |
| Chicony HP HD Webcam                                                       | 3         | 0.5%    |
| Chicony EasyCamera                                                         | 3         | 0.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.5%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 3         | 0.5%    |
| Alcor Micro USB 2.0 Camera                                                 | 3         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 53        | 35.1%   |
| Synaptics                  | 39        | 25.83%  |
| Shenzhen Goodix Technology | 31        | 20.53%  |
| LighTuning Technology      | 8         | 5.3%    |
| Elan Microelectronics      | 8         | 5.3%    |
| AuthenTec                  | 5         | 3.31%   |
| Upek                       | 4         | 2.65%   |
| STMicroelectronics         | 2         | 1.32%   |
| HOLTEK                     | 1         | 0.66%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 15.89%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 10.6%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 9.93%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 7.28%   |
| Elan ELAN:Fingerprint                                                      | 8         | 5.3%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 4.64%   |
| Validity Sensors VFS491                                                    | 5         | 3.31%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 3.31%   |
| Unknown                                                                    | 5         | 3.31%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.65%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 2.65%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 2.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 2.65%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.99%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.99%   |
| Synaptics  WBDI                                                            | 3         | 1.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.99%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.32%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.32%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.32%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.32%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.32%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.32%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.66%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.66%   |
| Synaptics WBDI Device                                                      | 1         | 0.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.66%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.66%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.66%   |
| AuthenTec AES2810                                                          | 1         | 0.66%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.66%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.66%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 41.18%  |
| Alcor Micro           | 21        | 41.18%  |
| O2 Micro              | 2         | 3.92%   |
| Lenovo                | 2         | 3.92%   |
| Gemalto (was Gemplus) | 2         | 3.92%   |
| Upek                  | 1         | 1.96%   |
| Clay Logic            | 1         | 1.96%   |
| Cherry                | 1         | 1.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 21        | 41.18%  |
| Broadcom 5880                                                                | 7         | 13.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 11.76%  |
| Broadcom 58200                                                               | 6         | 11.76%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.92%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.96%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.96%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 1.96%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.96%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 403       | 59.88%  |
| 1     | 211       | 31.35%  |
| 2     | 50        | 7.43%   |
| 3     | 8         | 1.19%   |
| 4     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 148       | 45.4%   |
| Graphics card            | 56        | 17.18%  |
| Chipcard                 | 44        | 13.5%   |
| Net/wireless             | 42        | 12.88%  |
| Multimedia controller    | 8         | 2.45%   |
| Bluetooth                | 7         | 2.15%   |
| Storage                  | 6         | 1.84%   |
| Camera                   | 4         | 1.23%   |
| Card reader              | 3         | 0.92%   |
| Sound                    | 2         | 0.61%   |
| Net/ethernet             | 2         | 0.61%   |
| Unassigned class         | 1         | 0.31%   |
| Network                  | 1         | 0.31%   |
| Modem                    | 1         | 0.31%   |
| Communication controller | 1         | 0.31%   |


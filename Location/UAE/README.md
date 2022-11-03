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

Total: 184

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 30        | 23.81%  |
| Ubuntu 18.04       | 16        | 12.7%   |
| Arch               | 5         | 3.97%   |
| Ubuntu 22.04       | 4         | 3.17%   |
| Ubuntu 19.10       | 4         | 3.17%   |
| Fedora 36          | 4         | 3.17%   |
| Debian 11          | 4         | 3.17%   |
| Zorin 15           | 3         | 2.38%   |
| Ubuntu 20.10       | 3         | 2.38%   |
| Linux Mint 20.3    | 3         | 2.38%   |
| Debian 10          | 3         | 2.38%   |
| Zorin 16           | 2         | 1.59%   |
| Ubuntu 21.10       | 2         | 1.59%   |
| Ubuntu 16.04       | 2         | 1.59%   |
| Pop!_OS 20.10      | 2         | 1.59%   |
| Pop!_OS 20.04      | 2         | 1.59%   |
| OpenMandriva 4.3   | 2         | 1.59%   |
| KDE neon 20.04     | 2         | 1.59%   |
| Fedora 35          | 2         | 1.59%   |
| Fedora 34          | 2         | 1.59%   |
| BlackPanther 18.1  | 2         | 1.59%   |
| ArcoLinux Rolling  | 2         | 1.59%   |
| Xubuntu 20.04      | 1         | 0.79%   |
| Xubuntu 16.04      | 1         | 0.79%   |
| Ubuntu Unity 18.04 | 1         | 0.79%   |
| Ubuntu MATE 20.04  | 1         | 0.79%   |
| Ubuntu 22.10       | 1         | 0.79%   |
| Ubuntu 21.04       | 1         | 0.79%   |
| Ubuntu 19.04       | 1         | 0.79%   |
| ROSA 12.2          | 1         | 0.79%   |
| Pop!_OS 21.10      | 1         | 0.79%   |
| OpenMandriva 4.90  | 1         | 0.79%   |
| OpenMandriva 4.2   | 1         | 0.79%   |
| Manjaro 21.2.1     | 1         | 0.79%   |
| Manjaro 20.2.1     | 1         | 0.79%   |
| Manjaro 20.2       | 1         | 0.79%   |
| Manjaro 20.1       | 1         | 0.79%   |
| Manjaro 18.1.4     | 1         | 0.79%   |
| Manjaro            | 1         | 0.79%   |
| Linux Mint 20.1    | 1         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 62        | 50.82%  |
| Fedora       | 8         | 6.56%   |
| Manjaro      | 6         | 4.92%   |
| Debian       | 6         | 4.92%   |
| Zorin        | 5         | 4.1%    |
| Linux Mint   | 5         | 4.1%    |
| Arch         | 5         | 4.1%    |
| Pop!_OS      | 4         | 3.28%   |
| OpenMandriva | 4         | 3.28%   |
| Xubuntu      | 2         | 1.64%   |
| KDE neon     | 2         | 1.64%   |
| Endless      | 2         | 1.64%   |
| BlackPanther | 2         | 1.64%   |
| ArcoLinux    | 2         | 1.64%   |
| Ubuntu Unity | 1         | 0.82%   |
| Ubuntu MATE  | 1         | 0.82%   |
| ROSA         | 1         | 0.82%   |
| Kubuntu      | 1         | 0.82%   |
| GNOME OS     | 1         | 0.82%   |
| Feren OS     | 1         | 0.82%   |
| Elementary   | 1         | 0.82%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 7         | 5.11%   |
| 5.4.0-58-generic        | 4         | 2.92%   |
| 5.4.0-26-generic        | 4         | 2.92%   |
| 5.4.0-37-generic        | 3         | 2.19%   |
| 5.11.0-40-generic       | 3         | 2.19%   |
| 4.15.0-50-generic       | 3         | 2.19%   |
| 5.8.0-40-generic        | 2         | 1.46%   |
| 5.4.0-81-generic        | 2         | 1.46%   |
| 5.4.0-48-generic        | 2         | 1.46%   |
| 5.4.0-33-generic        | 2         | 1.46%   |
| 5.4.0-29-generic        | 2         | 1.46%   |
| 5.3.0-40-generic        | 2         | 1.46%   |
| 5.3.0-29-generic        | 2         | 1.46%   |
| 5.16.7-desktop-1omv4003 | 2         | 1.46%   |
| 5.0.0-23-generic        | 2         | 1.46%   |
| 5.9.3-arch1-1           | 1         | 0.73%   |
| 5.9.16-1-MANJARO        | 1         | 0.73%   |
| 5.9.11-3-MANJARO        | 1         | 0.73%   |
| 5.9.1-050901-generic    | 1         | 0.73%   |
| 5.8.7-050807-generic    | 1         | 0.73%   |
| 5.8.5-arch1-1           | 1         | 0.73%   |
| 5.8.12-050812-generic   | 1         | 0.73%   |
| 5.8.0-7642-generic      | 1         | 0.73%   |
| 5.8.0-7630-generic      | 1         | 0.73%   |
| 5.8.0-54-generic        | 1         | 0.73%   |
| 5.8.0-53-generic        | 1         | 0.73%   |
| 5.8.0-50-generic        | 1         | 0.73%   |
| 5.8.0-41-generic        | 1         | 0.73%   |
| 5.8.0-0.bpo.2-amd64     | 1         | 0.73%   |
| 5.7.6-arch1-1           | 1         | 0.73%   |
| 5.7.14-1-MANJARO        | 1         | 0.73%   |
| 5.7.14                  | 1         | 0.73%   |
| 5.6.16-1-MANJARO        | 1         | 0.73%   |
| 5.6.14-desktop-2bP      | 1         | 0.73%   |
| 5.5.11-050511-generic   | 1         | 0.73%   |
| 5.4.68-1-lts            | 1         | 0.73%   |
| 5.4.2-1-MANJARO         | 1         | 0.73%   |
| 5.4.0-73-generic        | 1         | 0.73%   |
| 5.4.0-72-generic        | 1         | 0.73%   |
| 5.4.0-65-generic        | 1         | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 25.2%   |
| 4.15.0  | 14        | 11.02%  |
| 5.8.0   | 9         | 7.09%   |
| 5.11.0  | 9         | 7.09%   |
| 5.3.0   | 6         | 4.72%   |
| 5.15.0  | 5         | 3.94%   |
| 5.10.0  | 4         | 3.15%   |
| 5.13.0  | 3         | 2.36%   |
| 5.0.0   | 3         | 2.36%   |
| 5.7.14  | 2         | 1.57%   |
| 5.16.7  | 2         | 1.57%   |
| 4.18.0  | 2         | 1.57%   |
| 5.9.3   | 1         | 0.79%   |
| 5.9.16  | 1         | 0.79%   |
| 5.9.11  | 1         | 0.79%   |
| 5.9.1   | 1         | 0.79%   |
| 5.8.7   | 1         | 0.79%   |
| 5.8.5   | 1         | 0.79%   |
| 5.8.12  | 1         | 0.79%   |
| 5.7.6   | 1         | 0.79%   |
| 5.6.16  | 1         | 0.79%   |
| 5.6.14  | 1         | 0.79%   |
| 5.5.11  | 1         | 0.79%   |
| 5.4.68  | 1         | 0.79%   |
| 5.4.2   | 1         | 0.79%   |
| 5.19.8  | 1         | 0.79%   |
| 5.19.13 | 1         | 0.79%   |
| 5.19.12 | 1         | 0.79%   |
| 5.19.0  | 1         | 0.79%   |
| 5.18.12 | 1         | 0.79%   |
| 5.18.11 | 1         | 0.79%   |
| 5.17.4  | 1         | 0.79%   |
| 5.16.5  | 1         | 0.79%   |
| 5.16.18 | 1         | 0.79%   |
| 5.16.16 | 1         | 0.79%   |
| 5.16.12 | 1         | 0.79%   |
| 5.15.5  | 1         | 0.79%   |
| 5.15.12 | 1         | 0.79%   |
| 5.14.13 | 1         | 0.79%   |
| 5.14.0  | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 27.42%  |
| 4.15    | 14        | 11.29%  |
| 5.8     | 11        | 8.87%   |
| 5.11    | 9         | 7.26%   |
| 5.15    | 7         | 5.65%   |
| 5.3     | 6         | 4.84%   |
| 5.10    | 6         | 4.84%   |
| 5.16    | 5         | 4.03%   |
| 5.19    | 4         | 3.23%   |
| 5.13    | 4         | 3.23%   |
| 5.9     | 3         | 2.42%   |
| 5.7     | 3         | 2.42%   |
| 5.0     | 3         | 2.42%   |
| 4.18    | 3         | 2.42%   |
| 5.6     | 2         | 1.61%   |
| 5.18    | 2         | 1.61%   |
| 5.14    | 2         | 1.61%   |
| 4.19    | 2         | 1.61%   |
| 5.5     | 1         | 0.81%   |
| 5.17    | 1         | 0.81%   |
| 5.12    | 1         | 0.81%   |
| 4.4     | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 116       | 98.31%  |
| i686   | 2         | 1.69%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 76        | 61.79%  |
| Unknown    | 18        | 14.63%  |
| KDE5       | 9         | 7.32%   |
| X-Cinnamon | 5         | 4.07%   |
| XFCE       | 4         | 3.25%   |
| KDE        | 4         | 3.25%   |
| MATE       | 2         | 1.63%   |
| Unity      | 1         | 0.81%   |
| Pantheon   | 1         | 0.81%   |
| DWM        | 1         | 0.81%   |
| bspwm      | 1         | 0.81%   |
| awesome    | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 90        | 74.38%  |
| Wayland | 20        | 16.53%  |
| Unknown | 11        | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 61.16%  |
| GDM     | 23        | 19.01%  |
| SDDM    | 10        | 8.26%   |
| GDM3    | 7         | 5.79%   |
| LightDM | 5         | 4.13%   |
| TDM     | 2         | 1.65%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 91        | 76.47%  |
| Unknown | 15        | 12.61%  |
| en_GB   | 4         | 3.36%   |
| C       | 4         | 3.36%   |
| ru_RU   | 1         | 0.84%   |
| hu_HU   | 1         | 0.84%   |
| en_IN   | 1         | 0.84%   |
| en_AU   | 1         | 0.84%   |
| de_DE   | 1         | 0.84%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 69        | 56.1%   |
| BIOS | 54        | 43.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 101       | 85.59%  |
| Btrfs   | 9         | 7.63%   |
| Overlay | 6         | 5.08%   |
| Xfs     | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 78        | 65.55%  |
| GPT     | 35        | 29.41%  |
| MBR     | 6         | 5.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 89.92%  |
| Yes       | 12        | 10.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 59.5%   |
| Yes       | 49        | 40.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 30        | 25.42%  |
| Hewlett-Packard             | 30        | 25.42%  |
| Dell                        | 16        | 13.56%  |
| ASUSTek Computer            | 13        | 11.02%  |
| Toshiba                     | 5         | 4.24%   |
| Intel                       | 4         | 3.39%   |
| Sony                        | 2         | 1.69%   |
| MSI                         | 2         | 1.69%   |
| Microsoft                   | 2         | 1.69%   |
| Google                      | 2         | 1.69%   |
| Gigabyte Technology         | 2         | 1.69%   |
| Acer                        | 2         | 1.69%   |
| YJKC                        | 1         | 0.85%   |
| win element                 | 1         | 0.85%   |
| Notebook                    | 1         | 0.85%   |
| LG Electronics              | 1         | 0.85%   |
| I-Life Digital Technologies | 1         | 0.85%   |
| ECS                         | 1         | 0.85%   |
| Biostar                     | 1         | 0.85%   |
| Apple                       | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| HP Pavilion Notebook                        | 2         | 1.69%   |
| HP ENVY Laptop 13-aq0xxx                    | 2         | 1.69%   |
| HP All-in-One 22-c0xx                       | 2         | 1.69%   |
| ASUS All Series                             | 2         | 1.69%   |
| YJKC vBOOK Plus                             | 1         | 0.85%   |
| win element MoreFine S500+                  | 1         | 0.85%   |
| Toshiba TECRA X40-D                         | 1         | 0.85%   |
| Toshiba TECRA A50-C                         | 1         | 0.85%   |
| Toshiba Satellite C850-A966                 | 1         | 0.85%   |
| Toshiba Satellite C660                      | 1         | 0.85%   |
| Toshiba Satellite A300                      | 1         | 0.85%   |
| Sony VGN-NS10J_S                            | 1         | 0.85%   |
| Sony SVE14A25CAB                            | 1         | 0.85%   |
| Notebook P95_96_97Ex,Rx                     | 1         | 0.85%   |
| MSI PS63 Modern 8RD                         | 1         | 0.85%   |
| MSI MS-7850                                 | 1         | 0.85%   |
| Microsoft Surface Pro 4                     | 1         | 0.85%   |
| Microsoft Surface Pro 3                     | 1         | 0.85%   |
| LG C500-G.AEF5BE1                           | 1         | 0.85%   |
| Lenovo Yoga S730-13IWL 81J0                 | 1         | 0.85%   |
| Lenovo Yoga 2 Pro 20266                     | 1         | 0.85%   |
| Lenovo ThinkPad Yoga 260 20FD000GAD         | 1         | 0.85%   |
| Lenovo ThinkPad X240 20AMS6GB00             | 1         | 0.85%   |
| Lenovo ThinkPad X230 2325DV8                | 1         | 0.85%   |
| Lenovo ThinkPad X1 Yoga 4th 20QF0015US      | 1         | 0.85%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A9US  | 1         | 0.85%   |
| Lenovo ThinkPad T61 76653JG                 | 1         | 0.85%   |
| Lenovo ThinkPad T480s 20L8S3FV00            | 1         | 0.85%   |
| Lenovo ThinkPad T480s 20L7001PAD            | 1         | 0.85%   |
| Lenovo ThinkPad T470 W10DG 20JMS0Q300       | 1         | 0.85%   |
| Lenovo ThinkPad T460 20FMS1A200             | 1         | 0.85%   |
| Lenovo ThinkPad P1 Gen 5 21DC000DCK         | 1         | 0.85%   |
| Lenovo ThinkPad P1 Gen 3 20TJS4RX00         | 1         | 0.85%   |
| Lenovo ThinkPad L480 20LS0012AD             | 1         | 0.85%   |
| Lenovo ThinkPad E14 Gen 2 20TA0018AD        | 1         | 0.85%   |
| Lenovo ThinkCentre E93 10AR004LAX           | 1         | 0.85%   |
| Lenovo ThinkCentre E73 10AS0041AX           | 1         | 0.85%   |
| Lenovo Legion Y7000P 81LD                   | 1         | 0.85%   |
| Lenovo IdeaPadFlex 14 20308                 | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 15        | 12.71%  |
| HP Pavilion          | 9         | 7.63%   |
| Lenovo IdeaPad       | 7         | 5.93%   |
| HP EliteBook         | 5         | 4.24%   |
| Dell Latitude        | 5         | 4.24%   |
| Toshiba Satellite    | 3         | 2.54%   |
| HP ProBook           | 3         | 2.54%   |
| HP Laptop            | 3         | 2.54%   |
| HP ENVY              | 3         | 2.54%   |
| Dell Precision       | 3         | 2.54%   |
| Dell Inspiron        | 3         | 2.54%   |
| ASUS ROG             | 3         | 2.54%   |
| ASUS PRIME           | 3         | 2.54%   |
| Toshiba TECRA        | 2         | 1.69%   |
| Microsoft Surface    | 2         | 1.69%   |
| Lenovo Yoga          | 2         | 1.69%   |
| Lenovo ThinkCentre   | 2         | 1.69%   |
| HP All-in-One        | 2         | 1.69%   |
| Dell OptiPlex        | 2         | 1.69%   |
| ASUS VivoBook        | 2         | 1.69%   |
| ASUS All             | 2         | 1.69%   |
| YJKC vBOOK           | 1         | 0.85%   |
| win element MoreFine | 1         | 0.85%   |
| Sony VGN-NS10J       | 1         | 0.85%   |
| Sony SVE14A25CAB     | 1         | 0.85%   |
| Notebook P95         | 1         | 0.85%   |
| MSI PS63             | 1         | 0.85%   |
| MSI MS-7850          | 1         | 0.85%   |
| LG C500-G.AEF5BE1    | 1         | 0.85%   |
| Lenovo Legion        | 1         | 0.85%   |
| Lenovo IdeaPadFlex   | 1         | 0.85%   |
| Lenovo G500          | 1         | 0.85%   |
| Lenovo 81FV          | 1         | 0.85%   |
| Intel NUC6i7KYB      | 1         | 0.85%   |
| Intel NUC10i3FNH     | 1         | 0.85%   |
| Intel DH67CL         | 1         | 0.85%   |
| Intel D865PERL       | 1         | 0.85%   |
| I-Life Digital ZED   | 1         | 0.85%   |
| HP Presario          | 1         | 0.85%   |
| HP Notebook          | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 17        | 14.41%  |
| 2020 | 14        | 11.86%  |
| 2018 | 14        | 11.86%  |
| 2013 | 11        | 9.32%   |
| 2012 | 9         | 7.63%   |
| 2021 | 8         | 6.78%   |
| 2016 | 8         | 6.78%   |
| 2017 | 7         | 5.93%   |
| 2010 | 7         | 5.93%   |
| 2014 | 5         | 4.24%   |
| 2011 | 5         | 4.24%   |
| 2015 | 4         | 3.39%   |
| 2007 | 3         | 2.54%   |
| 2009 | 2         | 1.69%   |
| 2008 | 2         | 1.69%   |
| 2022 | 1         | 0.85%   |
| 2005 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 84        | 71.19%  |
| Desktop     | 22        | 18.64%  |
| Convertible | 6         | 5.08%   |
| Tablet      | 2         | 1.69%   |
| Mini pc     | 2         | 1.69%   |
| All in one  | 2         | 1.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 103       | 86.55%  |
| Enabled  | 16        | 13.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 98.31%  |
| Yes  | 2         | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 24.58%  |
| 16.01-24.0  | 27        | 22.88%  |
| 3.01-4.0    | 20        | 16.95%  |
| 8.01-16.0   | 19        | 16.1%   |
| 32.01-64.0  | 10        | 8.47%   |
| 64.01-256.0 | 5         | 4.24%   |
| 0.51-1.0    | 3         | 2.54%   |
| 2.01-3.0    | 2         | 1.69%   |
| 1.01-2.0    | 2         | 1.69%   |
| 24.01-32.0  | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 40        | 31.5%   |
| 2.01-3.0  | 29        | 22.83%  |
| 4.01-8.0  | 26        | 20.47%  |
| 3.01-4.0  | 20        | 15.75%  |
| 8.01-16.0 | 5         | 3.94%   |
| 0.51-1.0  | 5         | 3.94%   |
| 0.01-0.5  | 2         | 1.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 86        | 72.27%  |
| 2      | 22        | 18.49%  |
| 3      | 5         | 4.2%    |
| 4      | 3         | 2.52%   |
| 0      | 2         | 1.68%   |
| 8      | 1         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 68.91%  |
| Yes       | 37        | 31.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 76.27%  |
| No        | 28        | 23.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 86.44%  |
| No        | 16        | 13.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 71.67%  |
| No        | 34        | 28.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UAE     | 118       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Dubai            | 54        | 44.63%  |
| Abu Dhabi        | 38        | 31.4%   |
| Sharjah          | 17        | 14.05%  |
| Al Ain City      | 5         | 4.13%   |
| Al Fujairah City | 3         | 2.48%   |
| Ajman            | 3         | 2.48%   |
| Al Halah         | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 26        | 30     | 16.99%  |
| Samsung Electronics   | 26        | 34     | 16.99%  |
| Toshiba               | 17        | 21     | 11.11%  |
| Seagate               | 17        | 23     | 11.11%  |
| Unknown               | 7         | 14     | 4.58%   |
| Intel                 | 7         | 9      | 4.58%   |
| HGST                  | 7         | 8      | 4.58%   |
| Kingston              | 5         | 5      | 3.27%   |
| Crucial               | 5         | 6      | 3.27%   |
| SK hynix              | 4         | 5      | 2.61%   |
| Micron Technology     | 4         | 4      | 2.61%   |
| Hitachi               | 4         | 4      | 2.61%   |
| SanDisk               | 3         | 4      | 1.96%   |
| Phison                | 2         | 2      | 1.31%   |
| Lexar                 | 2         | 2      | 1.31%   |
| Apple                 | 2         | 3      | 1.31%   |
| USB3.0                | 1         | 1      | 0.65%   |
| Transcend             | 1         | 1      | 0.65%   |
| Team                  | 1         | 1      | 0.65%   |
| Realtek Semiconductor | 1         | 1      | 0.65%   |
| Patriot               | 1         | 1      | 0.65%   |
| OCZ                   | 1         | 1      | 0.65%   |
| Maxtor                | 1         | 1      | 0.65%   |
| Lite-On               | 1         | 1      | 0.65%   |
| Lenovo                | 1         | 1      | 0.65%   |
| KingSpec              | 1         | 2      | 0.65%   |
| Gigabyte Technology   | 1         | 1      | 0.65%   |
| Fujitsu               | 1         | 1      | 0.65%   |
| External              | 1         | 1      | 0.65%   |
| Corsair               | 1         | 1      | 0.65%   |
| China                 | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 4         | 2.47%   |
| HGST HTS725050A7E630 500GB             | 4         | 2.47%   |
| Intel NVMe SSD Drive 512GB             | 3         | 1.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 1.23%   |
| WDC WD10SPZX-08Z10 1TB                 | 2         | 1.23%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 2         | 1.23%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB     | 2         | 1.23%   |
| Unknown SD/MMC/MS PRO 1TB              | 2         | 1.23%   |
| Unknown MMC Card  16GB                 | 2         | 1.23%   |
| Toshiba MQ01ABD075 752GB               | 2         | 1.23%   |
| Toshiba DT01ACA100 1TB                 | 2         | 1.23%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 1.23%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 1.23%   |
| Samsung SSD 970 EVO Plus 500GB         | 2         | 1.23%   |
| Samsung SSD 850 PRO 1TB                | 2         | 1.23%   |
| Samsung SSD 850 EVO 250GB              | 2         | 1.23%   |
| Intel SSDPEKNW512G8H 512GB             | 2         | 1.23%   |
| HGST HTS721010A9E630 1TB               | 2         | 1.23%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 1.23%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.62%   |
| WDC WDS120G1G0A-00SS50 120GB SSD       | 1         | 0.62%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.62%   |
| WDC WD800BB-55JHC0 80GB                | 1         | 0.62%   |
| WDC WD6400AAKS-22A7B0 640GB            | 1         | 0.62%   |
| WDC WD5000LPVX-60V0TT0 500GB           | 1         | 0.62%   |
| WDC WD5000LPCX-22VHAT1 500GB           | 1         | 0.62%   |
| WDC WD5000AAKS-65V0A0 500GB            | 1         | 0.62%   |
| WDC WD40EFRX-68N32N0 4TB               | 1         | 0.62%   |
| WDC WD2500BEVS-26UST0 250GB            | 1         | 0.62%   |
| WDC WD2500AAJS-75M0A0 250GB            | 1         | 0.62%   |
| WDC WD20EZRX-00D8PB0 2TB               | 1         | 0.62%   |
| WDC WD1600AAJS-60B4A0 160GB            | 1         | 0.62%   |
| WDC WD1200BEVS-08UST0 120GB            | 1         | 0.62%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 0.62%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 0.62%   |
| WDC WD10JPVX-60JC3T1 1TB               | 1         | 0.62%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 0.62%   |
| WDC WD10EZEX-08M2NA0 1TB               | 1         | 0.62%   |
| USB3.0 Super Speed 1TB                 | 1         | 0.62%   |
| Unknown SR64G  64GB                    | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 19        | 23     | 28.36%  |
| Seagate | 17        | 23     | 25.37%  |
| Toshiba | 14        | 18     | 20.9%   |
| HGST    | 7         | 8      | 10.45%  |
| Hitachi | 4         | 4      | 5.97%   |
| Unknown | 2         | 5      | 2.99%   |
| USB3.0  | 1         | 1      | 1.49%   |
| Maxtor  | 1         | 1      | 1.49%   |
| Fujitsu | 1         | 1      | 1.49%   |
| Apple   | 1         | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 32.26%  |
| WDC                 | 4         | 4      | 12.9%   |
| Crucial             | 4         | 5      | 12.9%   |
| Kingston            | 3         | 3      | 9.68%   |
| Transcend           | 1         | 1      | 3.23%   |
| Team                | 1         | 1      | 3.23%   |
| SK hynix            | 1         | 1      | 3.23%   |
| SanDisk             | 1         | 1      | 3.23%   |
| Patriot             | 1         | 1      | 3.23%   |
| Lexar               | 1         | 1      | 3.23%   |
| KingSpec            | 1         | 2      | 3.23%   |
| Gigabyte Technology | 1         | 1      | 3.23%   |
| Corsair             | 1         | 1      | 3.23%   |
| China               | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 59        | 85     | 43.07%  |
| NVMe | 48        | 62     | 35.04%  |
| SSD  | 25        | 34     | 18.25%  |
| MMC  | 5         | 9      | 3.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 112    | 56.92%  |
| NVMe | 47        | 61     | 36.15%  |
| MMC  | 5         | 9      | 3.85%   |
| SAS  | 4         | 8      | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 62     | 57.47%  |
| 0.51-1.0   | 31        | 47     | 35.63%  |
| 1.01-2.0   | 4         | 4      | 4.6%    |
| 3.01-4.0   | 1         | 5      | 1.15%   |
| 4.01-10.0  | 1         | 1      | 1.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 35        | 28.93%  |
| 101-250        | 29        | 23.97%  |
| 21-50          | 11        | 9.09%   |
| 501-1000       | 10        | 8.26%   |
| 1001-2000      | 9         | 7.44%   |
| 51-100         | 9         | 7.44%   |
| Unknown        | 7         | 5.79%   |
| 1-20           | 6         | 4.96%   |
| 2001-3000      | 4         | 3.31%   |
| More than 3000 | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 56        | 43.41%  |
| 21-50     | 30        | 23.26%  |
| 51-100    | 13        | 10.08%  |
| 101-250   | 11        | 8.53%   |
| Unknown   | 7         | 5.43%   |
| 251-500   | 5         | 3.88%   |
| 501-1000  | 5         | 3.88%   |
| 2001-3000 | 1         | 0.78%   |
| 1001-2000 | 1         | 0.78%   |

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
| Detected | 80        | 131    | 67.8%   |
| Works    | 37        | 58     | 31.36%  |
| Malfunc  | 1         | 1      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 90        | 62.94%  |
| Samsung Electronics          | 17        | 11.89%  |
| SanDisk                      | 5         | 3.5%    |
| Micron Technology            | 4         | 2.8%    |
| AMD                          | 4         | 2.8%    |
| Toshiba America Info Systems | 3         | 2.1%    |
| SK hynix                     | 3         | 2.1%    |
| Phison Electronics           | 2         | 1.4%    |
| Kingston Technology Company  | 2         | 1.4%    |
| ASMedia Technology           | 2         | 1.4%    |
| VIA Technologies             | 1         | 0.7%    |
| Silicon Motion               | 1         | 0.7%    |
| Realtek Semiconductor        | 1         | 0.7%    |
| OCZ Technology Group         | 1         | 0.7%    |
| Nvidia                       | 1         | 0.7%    |
| Micron/Crucial Technology    | 1         | 0.7%    |
| Marvell Technology Group     | 1         | 0.7%    |
| Lite-On Technology           | 1         | 0.7%    |
| Lenovo                       | 1         | 0.7%    |
| Broadcom / LSI               | 1         | 0.7%    |
| Apple                        | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 8.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 6.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 4.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 3.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 3.8%    |
| Samsung NVMe SSD Controller 980                                                | 5         | 3.16%   |
| Intel SSD 660P Series                                                          | 5         | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 3.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 2.53%   |
| Micron Non-Volatile memory controller                                          | 4         | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.53%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 2.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.9%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.27%   |
| SK hynix Gold P31 SSD                                                          | 2         | 1.27%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.27%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.27%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.27%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 1.27%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.27%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.27%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.63%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.63%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 50.7%   |
| NVMe | 47        | 33.1%   |
| RAID | 15        | 10.56%  |
| IDE  | 7         | 4.93%   |
| SAS  | 1         | 0.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 109       | 92.37%  |
| AMD    | 9         | 7.63%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz           | 5         | 4.24%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 3.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 4         | 3.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 2.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 2.54%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 3         | 2.54%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 2         | 1.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.69%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 1.69%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 1.69%   |
| Intel Core i5-9400T CPU @ 1.80GHz           | 2         | 1.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.69%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 0.85%   |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz         | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.85%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1         | 0.85%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 0.85%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.85%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.85%   |
| Intel Core i7-7740X CPU @ 4.30GHz           | 1         | 0.85%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz          | 1         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i7-5960X CPU @ 3.00GHz           | 1         | 0.85%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1         | 0.85%   |
| Intel Core i7-4790S CPU @ 3.20GHz           | 1         | 0.85%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i7-4600M CPU @ 2.90GHz           | 1         | 0.85%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.85%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 40        | 33.9%   |
| Intel Core i5           | 40        | 33.9%   |
| Intel Core i3           | 8         | 6.78%   |
| Other                   | 5         | 4.24%   |
| Intel Core i9           | 3         | 2.54%   |
| Intel Core 2 Duo        | 3         | 2.54%   |
| Intel Celeron           | 3         | 2.54%   |
| AMD Ryzen 5             | 3         | 2.54%   |
| Intel Xeon              | 2         | 1.69%   |
| Intel Pentium Dual-Core | 1         | 0.85%   |
| Intel Pentium 4         | 1         | 0.85%   |
| Intel Core m5           | 1         | 0.85%   |
| Intel Celeron M         | 1         | 0.85%   |
| Intel Atom              | 1         | 0.85%   |
| AMD Sempron             | 1         | 0.85%   |
| AMD Ryzen Threadripper  | 1         | 0.85%   |
| AMD Ryzen 9             | 1         | 0.85%   |
| AMD Ryzen 7 PRO         | 1         | 0.85%   |
| AMD Ryzen 7             | 1         | 0.85%   |
| AMD A6                  | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 51        | 43.22%  |
| 4      | 40        | 33.9%   |
| 6      | 11        | 9.32%   |
| 8      | 9         | 7.63%   |
| 1      | 4         | 3.39%   |
| 14     | 2         | 1.69%   |
| 16     | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 117       | 99.15%  |
| 2      | 1         | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 100       | 84.75%  |
| 1      | 18        | 15.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 115       | 97.46%  |
| 32-bit         | 2         | 1.69%   |
| Unknown        | 1         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 18.7%   |
| 0x306a9    | 9         | 7.32%   |
| 0x806ec    | 7         | 5.69%   |
| 0x406e3    | 7         | 5.69%   |
| 0x906ea    | 6         | 4.88%   |
| 0x40651    | 6         | 4.88%   |
| 0x206a7    | 6         | 4.88%   |
| 0x906e9    | 4         | 3.25%   |
| 0x806ea    | 4         | 3.25%   |
| 0x806e9    | 4         | 3.25%   |
| 0x306c3    | 4         | 3.25%   |
| 0xa0652    | 3         | 2.44%   |
| 0x806c1    | 3         | 2.44%   |
| 0x20655    | 3         | 2.44%   |
| 0x906ed    | 2         | 1.63%   |
| 0x806eb    | 2         | 1.63%   |
| 0x6fd      | 2         | 1.63%   |
| 0x506e3    | 2         | 1.63%   |
| 0x306f2    | 2         | 1.63%   |
| 0x306d4    | 2         | 1.63%   |
| 0xf29      | 1         | 0.81%   |
| 0xa0655    | 1         | 0.81%   |
| 0x906a3    | 1         | 0.81%   |
| 0x706a1    | 1         | 0.81%   |
| 0x6fb      | 1         | 0.81%   |
| 0x6e8      | 1         | 0.81%   |
| 0x406c4    | 1         | 0.81%   |
| 0x406c3    | 1         | 0.81%   |
| 0x306e4    | 1         | 0.81%   |
| 0x206c2    | 1         | 0.81%   |
| 0x20652    | 1         | 0.81%   |
| 0x106e5    | 1         | 0.81%   |
| 0x1067a    | 1         | 0.81%   |
| 0x0a50000c | 1         | 0.81%   |
| 0x08608102 | 1         | 0.81%   |
| 0x08600106 | 1         | 0.81%   |
| 0x08600104 | 1         | 0.81%   |
| 0x08600102 | 1         | 0.81%   |
| 0x08108109 | 1         | 0.81%   |
| 0x0800820d | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 31.36%  |
| Haswell          | 14        | 11.86%  |
| Skylake          | 11        | 9.32%   |
| IvyBridge        | 11        | 9.32%   |
| SandyBridge      | 7         | 5.93%   |
| Westmere         | 6         | 5.08%   |
| CometLake        | 4         | 3.39%   |
| Broadwell        | 4         | 3.39%   |
| TigerLake        | 3         | 2.54%   |
| Core             | 3         | 2.54%   |
| Zen+             | 2         | 1.69%   |
| Zen 2            | 2         | 1.69%   |
| Silvermont       | 2         | 1.69%   |
| Unknown          | 2         | 1.69%   |
| Zen 3            | 1         | 0.85%   |
| Zen              | 1         | 0.85%   |
| Piledriver       | 1         | 0.85%   |
| Penryn           | 1         | 0.85%   |
| P6               | 1         | 0.85%   |
| NetBurst         | 1         | 0.85%   |
| Nehalem          | 1         | 0.85%   |
| K8 Hammer        | 1         | 0.85%   |
| Goldmont plus    | 1         | 0.85%   |
| Alderlake Hybrid | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 94        | 57.32%  |
| Nvidia | 51        | 31.1%   |
| AMD    | 19        | 11.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 6.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 4.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 3.64%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.03%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 2.42%   |
| Intel HD Graphics 620                                                                    | 4         | 2.42%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.42%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.82%   |
| Intel HD Graphics 530                                                                    | 3         | 1.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.82%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.82%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.21%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.21%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.21%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 1.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.21%   |
| Intel HD Graphics 630                                                                    | 2         | 1.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.21%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.21%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.21%   |
| AMD Renoir                                                                               | 2         | 1.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.61%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.61%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.61%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.61%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.61%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1         | 0.61%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 0.61%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 48        | 40.68%  |
| Intel + Nvidia     | 35        | 29.66%  |
| 1 x Nvidia         | 15        | 12.71%  |
| Intel + AMD        | 10        | 8.47%   |
| 1 x AMD            | 9         | 7.63%   |
| Intel + 2 x Nvidia | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 92        | 77.31%  |
| Proprietary | 22        | 18.49%  |
| Unknown     | 5         | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 52.5%   |
| 1.01-2.0   | 23        | 19.17%  |
| 3.01-4.0   | 12        | 10%     |
| 0.01-0.5   | 10        | 8.33%   |
| 7.01-8.0   | 5         | 4.17%   |
| 0.51-1.0   | 5         | 4.17%   |
| 5.01-6.0   | 1         | 0.83%   |
| 2.01-3.0   | 1         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 16.28%  |
| Samsung Electronics     | 17        | 13.18%  |
| LG Display              | 16        | 12.4%   |
| BOE                     | 16        | 12.4%   |
| Chimei Innolux          | 13        | 10.08%  |
| Goldstar                | 6         | 4.65%   |
| Dell                    | 5         | 3.88%   |
| Hewlett-Packard         | 4         | 3.1%    |
| BenQ                    | 4         | 3.1%    |
| Lenovo                  | 3         | 2.33%   |
| Ancor Communications    | 3         | 2.33%   |
| Sharp                   | 2         | 1.55%   |
| LG Philips              | 2         | 1.55%   |
| InfoVision              | 2         | 1.55%   |
| Chi Mei Optoelectronics | 2         | 1.55%   |
| ViewSonic               | 1         | 0.78%   |
| Seiko/Epson             | 1         | 0.78%   |
| RTK                     | 1         | 0.78%   |
| Philips                 | 1         | 0.78%   |
| Panasonic               | 1         | 0.78%   |
| Mi                      | 1         | 0.78%   |
| LGD                     | 1         | 0.78%   |
| LG Electronics          | 1         | 0.78%   |
| Hitachi                 | 1         | 0.78%   |
| Gigabyte Technology     | 1         | 0.78%   |
| CSO                     | 1         | 0.78%   |
| Apple                   | 1         | 0.78%   |
| AOC                     | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch           | 2         | 1.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 1.53%   |
| Hewlett-Packard ALL-in-One HPN401F 1920x1080 476x268mm 21.5-inch       | 2         | 1.53%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 2         | 1.53%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                   | 2         | 1.53%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                  | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch         | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch         | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch         | 2         | 1.53%   |
| ViewSonic VA1918wm VSCC821 1440x900 410x256mm 19.0-inch                | 1         | 0.76%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.76%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                | 1         | 0.76%   |
| Seiko/Epson LCD Monitor 1280x800                                       | 1         | 0.76%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1         | 0.76%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch      | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC5741 1280x800 261x163mm 12.1-inch   | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4341 1366x768 344x194mm 15.5-inch   | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4157 3840x2160 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 950x540mm 43.0-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM0D74 1920x1080 1210x680mm 54.6-inch | 1         | 0.76%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 1         | 0.76%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch      | 1         | 0.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1         | 0.76%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                 | 1         | 0.76%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                     | 1         | 0.76%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 1         | 0.76%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                       | 1         | 0.76%   |
| LGD LCD Monitor 1366x768                                               | 1         | 0.76%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch          | 1         | 0.76%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch            | 1         | 0.76%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1         | 0.76%   |
| LG Display LCD Monitor LGD05EF 2560x1440 309x174mm 14.0-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 57        | 45.6%   |
| 1366x768 (WXGA)   | 33        | 26.4%   |
| 3840x2160 (4K)    | 10        | 8%      |
| 2560x1440 (QHD)   | 5         | 4%      |
| 1280x800 (WXGA)   | 4         | 3.2%    |
| 1920x1200 (WUXGA) | 3         | 2.4%    |
| 2560x1080         | 2         | 1.6%    |
| 1600x900 (HD+)    | 2         | 1.6%    |
| 1440x900 (WXGA+)  | 2         | 1.6%    |
| 3440x1440         | 1         | 0.8%    |
| 3200x1800 (QHD+)  | 1         | 0.8%    |
| 2880x1920         | 1         | 0.8%    |
| 2736x1824         | 1         | 0.8%    |
| 2560x1600         | 1         | 0.8%    |
| 2304x1440         | 1         | 0.8%    |
| 2160x1440         | 1         | 0.8%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 38        | 29.23%  |
| 14      | 21        | 16.15%  |
| 13      | 15        | 11.54%  |
| 24      | 8         | 6.15%   |
| 21      | 7         | 5.38%   |
| 12      | 7         | 5.38%   |
| 27      | 5         | 3.85%   |
| Unknown | 4         | 3.08%   |
| 84      | 3         | 2.31%   |
| 31      | 3         | 2.31%   |
| 23      | 3         | 2.31%   |
| 16      | 3         | 2.31%   |
| 34      | 2         | 1.54%   |
| 19      | 2         | 1.54%   |
| 18      | 2         | 1.54%   |
| 11      | 2         | 1.54%   |
| 54      | 1         | 0.77%   |
| 52      | 1         | 0.77%   |
| 46      | 1         | 0.77%   |
| 20      | 1         | 0.77%   |
| 17      | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 67        | 52.34%  |
| 201-300     | 17        | 13.28%  |
| 501-600     | 16        | 12.5%   |
| 401-500     | 11        | 8.59%   |
| Unknown     | 4         | 3.13%   |
| 601-700     | 3         | 2.34%   |
| 351-400     | 3         | 2.34%   |
| 1501-2000   | 3         | 2.34%   |
| 701-800     | 2         | 1.56%   |
| 1001-1500   | 2         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 99        | 84.62%  |
| 16/10   | 11        | 9.4%    |
| Unknown | 4         | 3.42%   |
| 21/9    | 2         | 1.71%   |
| 3/2     | 1         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 30%     |
| 81-90          | 28        | 21.54%  |
| 201-250        | 11        | 8.46%   |
| 71-80          | 8         | 6.15%   |
| 61-70          | 7         | 5.38%   |
| 151-200        | 7         | 5.38%   |
| More than 1000 | 5         | 3.85%   |
| 351-500        | 5         | 3.85%   |
| 301-350        | 5         | 3.85%   |
| Unknown        | 4         | 3.08%   |
| 251-300        | 3         | 2.31%   |
| 51-60          | 2         | 1.54%   |
| 141-150        | 2         | 1.54%   |
| 111-120        | 2         | 1.54%   |
| 121-130        | 1         | 0.77%   |
| 501-1000       | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 33.07%  |
| 101-120       | 34        | 26.77%  |
| 51-100        | 28        | 22.05%  |
| 161-240       | 11        | 8.66%   |
| More than 240 | 6         | 4.72%   |
| Unknown       | 4         | 3.15%   |
| 1-50          | 2         | 1.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 95        | 78.51%  |
| 2     | 19        | 15.7%   |
| 0     | 5         | 4.13%   |
| 3     | 2         | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 75        | 43.86%  |
| Realtek Semiconductor    | 54        | 31.58%  |
| Qualcomm Atheros         | 13        | 7.6%    |
| Broadcom                 | 10        | 5.85%   |
| Ralink                   | 4         | 2.34%   |
| Marvell Technology Group | 4         | 2.34%   |
| ASIX Electronics         | 2         | 1.17%   |
| Wilocity                 | 1         | 0.58%   |
| VIA Technologies         | 1         | 0.58%   |
| SILICON Laboratories     | 1         | 0.58%   |
| Sigma Designs            | 1         | 0.58%   |
| Ralink Technology        | 1         | 0.58%   |
| Nvidia                   | 1         | 0.58%   |
| Lenovo                   | 1         | 0.58%   |
| D-Link                   | 1         | 0.58%   |
| Broadcom Limited         | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 14.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 6.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.42%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.42%   |
| Intel Wireless 8260                                               | 5         | 2.42%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.93%   |
| Intel Wireless 7260                                               | 4         | 1.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.45%   |
| Intel Wireless 7265                                               | 3         | 1.45%   |
| Intel Wireless 3165                                               | 3         | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.97%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.97%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.97%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.97%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.97%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.97%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.97%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.97%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.97%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.97%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.97%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 61        | 57.01%  |
| Realtek Semiconductor    | 19        | 17.76%  |
| Qualcomm Atheros         | 9         | 8.41%   |
| Broadcom                 | 8         | 7.48%   |
| Ralink                   | 4         | 3.74%   |
| Marvell Technology Group | 2         | 1.87%   |
| Wilocity                 | 1         | 0.93%   |
| Ralink Technology        | 1         | 0.93%   |
| D-Link                   | 1         | 0.93%   |
| Broadcom Limited         | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 5.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.67%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.67%   |
| Intel Wireless 8260                                            | 5         | 4.67%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 4.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 3.74%   |
| Intel Wireless 7260                                            | 4         | 3.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2.8%    |
| Intel Wireless 7265                                            | 3         | 2.8%    |
| Intel Wireless 3165                                            | 3         | 2.8%    |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.8%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 2.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.87%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 1.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.87%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 1.87%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.87%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.87%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.93%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.93%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.93%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Intel Wireless-AC 9260                                         | 1         | 0.93%   |
| Intel Wireless 3160                                            | 1         | 0.93%   |
| Intel WiFi Link 5100                                           | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 47        | 51.09%  |
| Intel                    | 32        | 34.78%  |
| Qualcomm Atheros         | 4         | 4.35%   |
| Marvell Technology Group | 2         | 2.17%   |
| Broadcom                 | 2         | 2.17%   |
| ASIX Electronics         | 2         | 2.17%   |
| VIA Technologies         | 1         | 1.09%   |
| Nvidia                   | 1         | 1.09%   |
| Lenovo                   | 1         | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 31.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 14.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.1%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 3.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.04%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.04%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.04%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.04%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.04%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 2.04%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.04%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.02%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.02%   |
| Marvell Group 88E8070 based Ethernet Controller                   | 1         | 1.02%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.02%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.02%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.02%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.02%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.02%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 52.85%  |
| Ethernet | 89        | 46.11%  |
| Modem    | 2         | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 87        | 71.9%   |
| Ethernet | 34        | 28.1%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 72        | 61.02%  |
| 1     | 42        | 35.59%  |
| 3     | 2         | 1.69%   |
| 4     | 1         | 0.85%   |
| 0     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 81.36%  |
| Yes  | 22        | 18.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 55.81%  |
| Realtek Semiconductor           | 11        | 12.79%  |
| Qualcomm Atheros Communications | 6         | 6.98%   |
| Broadcom                        | 4         | 4.65%   |
| ASUSTek Computer                | 4         | 4.65%   |
| Ralink                          | 3         | 3.49%   |
| Toshiba                         | 2         | 2.33%   |
| Marvell Semiconductor           | 2         | 2.33%   |
| Dell                            | 2         | 2.33%   |
| Cambridge Silicon Radio         | 2         | 2.33%   |
| Hewlett-Packard                 | 1         | 1.16%   |
| Foxconn / Hon Hai               | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 17        | 19.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 12        | 13.95%  |
| Intel AX201 Bluetooth                                 | 7         | 8.14%   |
| Realtek Bluetooth Radio                               | 5         | 5.81%   |
| Intel AX200 Bluetooth                                 | 5         | 5.81%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3         | 3.49%   |
| Ralink RT3290 Bluetooth                               | 3         | 3.49%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 3.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 2         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 2.33%   |
| Intel Bluetooth Device                                | 2         | 2.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 2.33%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2         | 2.33%   |
| Toshiba RT Bluetooth Radio                            | 1         | 1.16%   |
| Toshiba Integrated Bluetooth HCI                      | 1         | 1.16%   |
| Realtek RTL8821A Bluetooth                            | 1         | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 1.16%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1         | 1.16%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 1.16%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 1.16%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 1.16%   |
| Marvell Bluetooth and Wireless LAN Composite          | 1         | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 1.16%   |
| Intel AX210 Bluetooth                                 | 1         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.16%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 1.16%   |
| Dell DW375 Bluetooth Module                           | 1         | 1.16%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 1.16%   |
| Broadcom HP Portable SoftSailing                      | 1         | 1.16%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1         | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 1         | 1.16%   |
| ASUS Bluetooth Radio                                  | 1         | 1.16%   |
| ASUS Bluetooth Device                                 | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 109       | 71.71%  |
| Nvidia             | 27        | 17.76%  |
| AMD                | 10        | 6.58%   |
| SteelSeries ApS    | 1         | 0.66%   |
| Logitech           | 1         | 0.66%   |
| Lenovo             | 1         | 0.66%   |
| JMTek              | 1         | 0.66%   |
| Griffin Technology | 1         | 0.66%   |
| Apogee Electronics | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 16        | 9.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 6.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 5.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 5.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 4.6%    |
| Intel 8 Series HD Audio Controller                                         | 8         | 4.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 3.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 2.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.87%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 2.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.3%    |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.72%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.72%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.72%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.72%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 1.15%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.15%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.15%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 1.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.15%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1         | 0.57%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.57%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.57%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 32.14%  |
| SK hynix            | 12        | 21.43%  |
| Micron Technology   | 8         | 14.29%  |
| Crucial             | 6         | 10.71%  |
| Kingston            | 4         | 7.14%   |
| Ramaxel Technology  | 3         | 5.36%   |
| Corsair             | 3         | 5.36%   |
| Unknown             | 2         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 3.51%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 3.51%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s       | 2         | 3.51%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s         | 2         | 3.51%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                  | 1         | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.75%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 1.75%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s            | 1         | 1.75%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.75%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.75%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s          | 1         | 1.75%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 1.75%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s         | 1         | 1.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.75%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 1.75%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.75%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.75%   |
| SK hynix RAM H5ANAG6NCMR-XNC 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.75%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.75%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.75%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.75%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.75%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s           | 1         | 1.75%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.75%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s        | 1         | 1.75%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s             | 1         | 1.75%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.75%   |
| Samsung RAM K4AAG165WA-BCWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.75%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB Row Of Chips DDR4 2400MT/s | 1         | 1.75%   |
| Micron RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 1.75%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Micron RAM 36JSZF51272PZ1G4F1 4096MB DIMM DDR3 1333MT/s         | 1         | 1.75%   |
| Micron RAM 18ASF2G72HZ-2G3B1 16GB SODIMM DDR4 2400MT/s          | 1         | 1.75%   |
| Micron RAM 16JTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.75%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s           | 1         | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 32        | 66.67%  |
| DDR3   | 10        | 20.83%  |
| LPDDR3 | 3         | 6.25%   |
| DDR5   | 2         | 4.17%   |
| DDR2   | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 73.47%  |
| DIMM         | 7         | 14.29%  |
| Row Of Chips | 6         | 12.24%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 51.85%  |
| 16384 | 12        | 22.22%  |
| 4096  | 7         | 12.96%  |
| 32768 | 3         | 5.56%   |
| 2048  | 3         | 5.56%   |
| 1024  | 1         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 17        | 33.33%  |
| 3200  | 9         | 17.65%  |
| 2133  | 6         | 11.76%  |
| 1600  | 6         | 11.76%  |
| 2400  | 4         | 7.84%   |
| 4800  | 2         | 3.92%   |
| 1334  | 2         | 3.92%   |
| 3400  | 1         | 1.96%   |
| 3000  | 1         | 1.96%   |
| 1333  | 1         | 1.96%   |
| 1067  | 1         | 1.96%   |
| 667   | 1         | 1.96%   |

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
| Chicony Electronics                    | 27        | 27.84%  |
| IMC Networks                           | 10        | 10.31%  |
| Cheng Uei Precision Industry (Foxlink) | 8         | 8.25%   |
| Microdia                               | 6         | 6.19%   |
| Acer                                   | 6         | 6.19%   |
| Sunplus Innovation Technology          | 5         | 5.15%   |
| Realtek Semiconductor                  | 4         | 4.12%   |
| Syntek                                 | 3         | 3.09%   |
| Samsung Electronics                    | 3         | 3.09%   |
| Ricoh                                  | 3         | 3.09%   |
| Lite-On Technology                     | 3         | 3.09%   |
| Apple                                  | 3         | 3.09%   |
| Suyin                                  | 2         | 2.06%   |
| Quanta                                 | 2         | 2.06%   |
| Microsoft                              | 2         | 2.06%   |
| Luxvisions Innotech Limited            | 2         | 2.06%   |
| Logitech                               | 2         | 2.06%   |
| Ruision                                | 1         | 1.03%   |
| LG Electronics                         | 1         | 1.03%   |
| Lenovo                                 | 1         | 1.03%   |
| KYE Systems (Mouse Systems)            | 1         | 1.03%   |
| Creative Technology                    | 1         | 1.03%   |
| Alcor Micro                            | 1         | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 9         | 9.28%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 5.15%   |
| Syntek Integrated Camera                                        | 3         | 3.09%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 3         | 3.09%   |
| IMC Networks Integrated Camera                                  | 3         | 3.09%   |
| Chicony Integrated Camera (1280x720@30)                         | 3         | 3.09%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 3         | 3.09%   |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 2.06%   |
| Ricoh HD Webcam                                                 | 2         | 2.06%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 2.06%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 2.06%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 2.06%   |
| Logitech Webcam C270                                            | 2         | 2.06%   |
| Lite-On HP Wide Vision HD Camera                                | 2         | 2.06%   |
| Chicony Lenovo EasyCamera                                       | 2         | 2.06%   |
| Chicony HP Truevision HD                                        | 2         | 2.06%   |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 2.06%   |
| Chicony EasyCamera                                              | 2         | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 2         | 2.06%   |
| Suyin HP TrueVision HD                                          | 1         | 1.03%   |
| Suyin 1.3M HD WebCam                                            | 1         | 1.03%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 1.03%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 1.03%   |
| Sunplus Integrated Webcam                                       | 1         | 1.03%   |
| Ruision UVC Camera                                              | 1         | 1.03%   |
| Ricoh Sony Vaio Integrated Webcam                               | 1         | 1.03%   |
| Realtek Lenovo EasyCamera                                       | 1         | 1.03%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 1.03%   |
| Realtek Integrated Webcam                                       | 1         | 1.03%   |
| Realtek HP Truevision HD                                        | 1         | 1.03%   |
| Microsoft LifeCam Rear                                          | 1         | 1.03%   |
| Microsoft LifeCam HD-3000                                       | 1         | 1.03%   |
| Microdia Integrated Webcam                                      | 1         | 1.03%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 1.03%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 1         | 1.03%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 1.03%   |
| Lite-On HP HD Camera                                            | 1         | 1.03%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)           | 1         | 1.03%   |
| Lenovo Integrated Webcam                                        | 1         | 1.03%   |

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
| 0     | 62        | 51.67%  |
| 1     | 46        | 38.33%  |
| 2     | 11        | 9.17%   |
| 3     | 1         | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 39.13%  |
| Graphics card            | 15        | 21.74%  |
| Net/wireless             | 7         | 10.14%  |
| Chipcard                 | 6         | 8.7%    |
| Camera                   | 3         | 4.35%   |
| Bluetooth                | 3         | 4.35%   |
| Unassigned class         | 2         | 2.9%    |
| Multimedia controller    | 2         | 2.9%    |
| Communication controller | 2         | 2.9%    |
| Sound                    | 1         | 1.45%   |
| Modem                    | 1         | 1.45%   |


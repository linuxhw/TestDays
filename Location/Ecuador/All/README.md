Linux in Ecuador - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ecuador/Desktop/README.md) and [notebooks](/Location/Ecuador/Notebook/README.md).

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

Total: 290

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Biostar       | H61MGV3                     | Desktop     | [bb42e29bbb](https://linux-hardware.org/?probe=bb42e29bbb) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Google        | Delbin                      | Notebook    | [26becdfc83](https://linux-hardware.org/?probe=26becdfc83) | Jun 26, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c434320a62](https://linux-hardware.org/?probe=c434320a62) | Jun 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ff0b730eed](https://linux-hardware.org/?probe=ff0b730eed) | Jun 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [edb1f4bda1](https://linux-hardware.org/?probe=edb1f4bda1) | Jun 14, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [70d24e4237](https://linux-hardware.org/?probe=70d24e4237) | Jun 02, 2022 |
| ASUSTek       | UX360CA                     | Notebook    | [63fac2dc9b](https://linux-hardware.org/?probe=63fac2dc9b) | May 29, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| Alienware     | 15 R3                       | Notebook    | [84df370117](https://linux-hardware.org/?probe=84df370117) | May 26, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Sony          | SVE14113ELW                 | Notebook    | [647c09a7be](https://linux-hardware.org/?probe=647c09a7be) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [ec5867b2f7](https://linux-hardware.org/?probe=ec5867b2f7) | May 17, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [9b06242456](https://linux-hardware.org/?probe=9b06242456) | May 17, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [7f46e36f35](https://linux-hardware.org/?probe=7f46e36f35) | May 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [81b3317aa8](https://linux-hardware.org/?probe=81b3317aa8) | May 14, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9c54929196](https://linux-hardware.org/?probe=9c54929196) | May 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [e559318a8b](https://linux-hardware.org/?probe=e559318a8b) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Biostar       | G41D3C                      | Desktop     | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [e049bbd414](https://linux-hardware.org/?probe=e049bbd414) | Apr 26, 2022 |
| Biostar       | G41D3C                      | Desktop     | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C                      | Desktop     | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| HP            | Unknown                     | Notebook    | [0a47967da0](https://linux-hardware.org/?probe=0a47967da0) | Apr 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| HP            | Unknown                     | Notebook    | [fa5bba3e33](https://linux-hardware.org/?probe=fa5bba3e33) | Apr 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| HP            | Pavilion dv6                | Notebook    | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| Google        | Panther                     | Desktop     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | Desktop     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| Sony          | VPCEG30EL                   | Notebook    | [c19f1a4739](https://linux-hardware.org/?probe=c19f1a4739) | Mar 26, 2022 |
| Sony          | SVE14A25CLB                 | Notebook    | [2e6afba454](https://linux-hardware.org/?probe=2e6afba454) | Mar 25, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Dell          | Inspiron 7547               | Notebook    | [af0de64399](https://linux-hardware.org/?probe=af0de64399) | Mar 22, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [1ef1ffe2a3](https://linux-hardware.org/?probe=1ef1ffe2a3) | Mar 20, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [faae36d70e](https://linux-hardware.org/?probe=faae36d70e) | Mar 17, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4d5aa250a1](https://linux-hardware.org/?probe=4d5aa250a1) | Mar 17, 2022 |
| TrekStor      | Primebook C13               | Convertible | [2c908202fc](https://linux-hardware.org/?probe=2c908202fc) | Mar 17, 2022 |
| Toshiba       | Satellite C55D-A            | Notebook    | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [c27fb51c94](https://linux-hardware.org/?probe=c27fb51c94) | Mar 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [15b0517729](https://linux-hardware.org/?probe=15b0517729) | Mar 13, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [f08be29479](https://linux-hardware.org/?probe=f08be29479) | Mar 12, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d9e67c0484](https://linux-hardware.org/?probe=d9e67c0484) | Mar 12, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [bd4f7daadb](https://linux-hardware.org/?probe=bd4f7daadb) | Mar 10, 2022 |
| Compal        | PBL2021                     | Notebook    | [4e367db737](https://linux-hardware.org/?probe=4e367db737) | Feb 28, 2022 |
| Intel         | H81                         | Desktop     | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                         | Desktop     | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Dell          | G5 5587                     | Notebook    | [5f51492976](https://linux-hardware.org/?probe=5f51492976) | Jan 29, 2022 |
| Dell          | Latitude 7280               | Notebook    | [fdf5a41dcc](https://linux-hardware.org/?probe=fdf5a41dcc) | Jan 25, 2022 |
| Dell          | Latitude 7280               | Notebook    | [b4c6f2fe35](https://linux-hardware.org/?probe=b4c6f2fe35) | Jan 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d8fc419747](https://linux-hardware.org/?probe=d8fc419747) | Jan 18, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [2f9b9ff8ee](https://linux-hardware.org/?probe=2f9b9ff8ee) | Jan 13, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [332b6e1f8a](https://linux-hardware.org/?probe=332b6e1f8a) | Jan 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ddd3544bcf](https://linux-hardware.org/?probe=ddd3544bcf) | Jan 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fbd40dba79](https://linux-hardware.org/?probe=fbd40dba79) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f2ba12e1f](https://linux-hardware.org/?probe=9f2ba12e1f) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [82281b42b0](https://linux-hardware.org/?probe=82281b42b0) | Dec 29, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [ef48db912e](https://linux-hardware.org/?probe=ef48db912e) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| ASUSTek       | G750JX                      | Notebook    | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Google        | Treeya                      | Notebook    | [a0ab206cd8](https://linux-hardware.org/?probe=a0ab206cd8) | Nov 09, 2021 |
| Dell          | Inspiron MP061              | Notebook    | [d6ed71bc78](https://linux-hardware.org/?probe=d6ed71bc78) | Nov 02, 2021 |
| HP            | G42                         | Notebook    | [5ee39658a8](https://linux-hardware.org/?probe=5ee39658a8) | Oct 28, 2021 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d31c8b483c](https://linux-hardware.org/?probe=d31c8b483c) | Oct 28, 2021 |
| HP            | G42                         | Notebook    | [a8181c9c9b](https://linux-hardware.org/?probe=a8181c9c9b) | Oct 24, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [b5d6c0ae9c](https://linux-hardware.org/?probe=b5d6c0ae9c) | Oct 20, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [177f79d880](https://linux-hardware.org/?probe=177f79d880) | Oct 18, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [70e96b19b2](https://linux-hardware.org/?probe=70e96b19b2) | Oct 17, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [2297765c40](https://linux-hardware.org/?probe=2297765c40) | Oct 14, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [87b00b0a80](https://linux-hardware.org/?probe=87b00b0a80) | Oct 12, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [0de7c95a46](https://linux-hardware.org/?probe=0de7c95a46) | Oct 12, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [6257ee6ddd](https://linux-hardware.org/?probe=6257ee6ddd) | Oct 07, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [5972d02719](https://linux-hardware.org/?probe=5972d02719) | Oct 07, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [2307619c77](https://linux-hardware.org/?probe=2307619c77) | Sep 27, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [d4cd8cbc7e](https://linux-hardware.org/?probe=d4cd8cbc7e) | Sep 27, 2021 |
| Foxconn       | H61MXL-K                    | Desktop     | [e776e3f647](https://linux-hardware.org/?probe=e776e3f647) | Sep 08, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [5e208c3927](https://linux-hardware.org/?probe=5e208c3927) | Sep 02, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [f667f32489](https://linux-hardware.org/?probe=f667f32489) | Aug 31, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [72cddcc75c](https://linux-hardware.org/?probe=72cddcc75c) | Aug 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [449fdc2d2d](https://linux-hardware.org/?probe=449fdc2d2d) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| Toshiba       | Satellite S55-B             | Notebook    | [c4ec7d25a7](https://linux-hardware.org/?probe=c4ec7d25a7) | Aug 21, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3276092f1e](https://linux-hardware.org/?probe=3276092f1e) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| Unknown       | Unknown                     | Notebook    | [008647318c](https://linux-hardware.org/?probe=008647318c) | Aug 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [5de2d0ae61](https://linux-hardware.org/?probe=5de2d0ae61) | Aug 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| Acer          | TravelMate X3410-M          | Notebook    | [18b5757039](https://linux-hardware.org/?probe=18b5757039) | Jul 29, 2021 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [33c83a65d8](https://linux-hardware.org/?probe=33c83a65d8) | Jul 24, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [a071db12c9](https://linux-hardware.org/?probe=a071db12c9) | Jul 12, 2021 |
| Google        | Banjo                       | Notebook    | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Google        | Grunt                       | Notebook    | [2bb0921a94](https://linux-hardware.org/?probe=2bb0921a94) | Jul 01, 2021 |
| Google        | Grunt                       | Notebook    | [4ea5c8f438](https://linux-hardware.org/?probe=4ea5c8f438) | Jul 01, 2021 |
| Pegatron      | 2ACC                        | Desktop     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0f90b91804](https://linux-hardware.org/?probe=0f90b91804) | Jun 25, 2021 |
| Google        | Kip                         | Notebook    | [7634152b76](https://linux-hardware.org/?probe=7634152b76) | Jun 21, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [a5fc625cf2](https://linux-hardware.org/?probe=a5fc625cf2) | Jun 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [54a4075ac5](https://linux-hardware.org/?probe=54a4075ac5) | May 16, 2021 |
| HP            | 1000                        | Notebook    | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP            | 1000                        | Notebook    | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| Acer          | Aspire V5-121               | Notebook    | [cc73e2b026](https://linux-hardware.org/?probe=cc73e2b026) | May 13, 2021 |
| HP            | 1000                        | Notebook    | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| Lenovo        | ThinkPad E15 20REA00000     | Notebook    | [1ac42dd429](https://linux-hardware.org/?probe=1ac42dd429) | May 09, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [cd6a799646](https://linux-hardware.org/?probe=cd6a799646) | Apr 29, 2021 |
| ASRock        | B550M-HDV                   | Desktop     | [aaee9d166a](https://linux-hardware.org/?probe=aaee9d166a) | Apr 26, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [e34aa83281](https://linux-hardware.org/?probe=e34aa83281) | Apr 16, 2021 |
| Dell          | G5 5587                     | Notebook    | [c88e053304](https://linux-hardware.org/?probe=c88e053304) | Apr 07, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [0ba2e43e56](https://linux-hardware.org/?probe=0ba2e43e56) | Mar 24, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [02f80c53ea](https://linux-hardware.org/?probe=02f80c53ea) | Mar 05, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [7b12363b97](https://linux-hardware.org/?probe=7b12363b97) | Mar 04, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [d5ef689e13](https://linux-hardware.org/?probe=d5ef689e13) | Feb 27, 2021 |
| Dell          | Inspiron 7375               | Notebook    | [eea996c7d4](https://linux-hardware.org/?probe=eea996c7d4) | Feb 26, 2021 |
| Shuttle       | SFM27 V20                   | Desktop     | [14a841b718](https://linux-hardware.org/?probe=14a841b718) | Feb 21, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [35cc521571](https://linux-hardware.org/?probe=35cc521571) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [2162db2610](https://linux-hardware.org/?probe=2162db2610) | Feb 03, 2021 |
| Sony          | VPCCW1S1E                   | Notebook    | [f57d56b50e](https://linux-hardware.org/?probe=f57d56b50e) | Jan 31, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [c30b6ae115](https://linux-hardware.org/?probe=c30b6ae115) | Jan 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f4e1001265](https://linux-hardware.org/?probe=f4e1001265) | Jan 23, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [063b008ad5](https://linux-hardware.org/?probe=063b008ad5) | Jan 15, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [473e0472d5](https://linux-hardware.org/?probe=473e0472d5) | Jan 12, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [5a7277af8b](https://linux-hardware.org/?probe=5a7277af8b) | Jan 08, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [bbbf68f88b](https://linux-hardware.org/?probe=bbbf68f88b) | Jan 08, 2021 |
| Google        | Parrot                      | Notebook    | [a3a6c2f819](https://linux-hardware.org/?probe=a3a6c2f819) | Jan 04, 2021 |
| Google        | Parrot                      | Notebook    | [55b807260c](https://linux-hardware.org/?probe=55b807260c) | Jan 04, 2021 |
| HP            | Pavilion 14                 | Notebook    | [91b047b61a](https://linux-hardware.org/?probe=91b047b61a) | Dec 31, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [c0e2f63e04](https://linux-hardware.org/?probe=c0e2f63e04) | Dec 20, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3f61162824](https://linux-hardware.org/?probe=3f61162824) | Dec 07, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [e5dab19c0f](https://linux-hardware.org/?probe=e5dab19c0f) | Dec 05, 2020 |
| Intel         | DP55KG AAE47218-404         | Desktop     | [5604be0f67](https://linux-hardware.org/?probe=5604be0f67) | Nov 25, 2020 |
| HP            | ProBook 4440s               | Notebook    | [b4747f87a1](https://linux-hardware.org/?probe=b4747f87a1) | Nov 24, 2020 |
| Dell          | Inspiron 1750               | Notebook    | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [cffed87fd7](https://linux-hardware.org/?probe=cffed87fd7) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [1505bb0505](https://linux-hardware.org/?probe=1505bb0505) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [364a814fd0](https://linux-hardware.org/?probe=364a814fd0) | Nov 19, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [b0fbbd8176](https://linux-hardware.org/?probe=b0fbbd8176) | Nov 19, 2020 |
| HP            | 3115m                       | Notebook    | [1ae9651614](https://linux-hardware.org/?probe=1ae9651614) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [106453a877](https://linux-hardware.org/?probe=106453a877) | Oct 23, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [fea6f132fa](https://linux-hardware.org/?probe=fea6f132fa) | Oct 23, 2020 |
| Toshiba       | PORTEGE M805                | Notebook    | [cacfe4abd9](https://linux-hardware.org/?probe=cacfe4abd9) | Oct 22, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [146545f430](https://linux-hardware.org/?probe=146545f430) | Oct 17, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [61e809ea3a](https://linux-hardware.org/?probe=61e809ea3a) | Oct 12, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6353946b7e](https://linux-hardware.org/?probe=6353946b7e) | Oct 12, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [03631f1005](https://linux-hardware.org/?probe=03631f1005) | Oct 08, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [78e7085775](https://linux-hardware.org/?probe=78e7085775) | Oct 08, 2020 |
| MSI           | B75A-G43                    | Desktop     | [fd4f003fa9](https://linux-hardware.org/?probe=fd4f003fa9) | Sep 28, 2020 |
| MSI           | B75A-G43                    | Desktop     | [148c1711fe](https://linux-hardware.org/?probe=148c1711fe) | Sep 28, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [3e989ff916](https://linux-hardware.org/?probe=3e989ff916) | Sep 24, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| Toshiba       | Satellite C45-A             | Notebook    | [2774da64f6](https://linux-hardware.org/?probe=2774da64f6) | Sep 18, 2020 |
| HP            | Pavilion 15                 | Notebook    | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP            | Mini 210-1100               | Notebook    | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| HP            | Pavilion 15                 | Notebook    | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| HP            | 1497                        | Desktop     | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [40aeea62f1](https://linux-hardware.org/?probe=40aeea62f1) | Sep 13, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [489cee4d9a](https://linux-hardware.org/?probe=489cee4d9a) | Sep 12, 2020 |
| Toshiba       | Satellite P775              | Notebook    | [d71ccb1065](https://linux-hardware.org/?probe=d71ccb1065) | Sep 10, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [8626b52852](https://linux-hardware.org/?probe=8626b52852) | Sep 08, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [cb7ecd71b1](https://linux-hardware.org/?probe=cb7ecd71b1) | Sep 07, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [917f5d9bd0](https://linux-hardware.org/?probe=917f5d9bd0) | Sep 07, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [c3f5f6d566](https://linux-hardware.org/?probe=c3f5f6d566) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4e0f1689a3](https://linux-hardware.org/?probe=4e0f1689a3) | Sep 06, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [8eb7cfa128](https://linux-hardware.org/?probe=8eb7cfa128) | Sep 05, 2020 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1b11abd994](https://linux-hardware.org/?probe=1b11abd994) | Sep 04, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [21f0c0015c](https://linux-hardware.org/?probe=21f0c0015c) | Aug 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [29f01daf9e](https://linux-hardware.org/?probe=29f01daf9e) | Aug 26, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [e39ccc961c](https://linux-hardware.org/?probe=e39ccc961c) | Aug 20, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Convertible | [1f4ef5bb49](https://linux-hardware.org/?probe=1f4ef5bb49) | Aug 19, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [dd8aa75b79](https://linux-hardware.org/?probe=dd8aa75b79) | Aug 16, 2020 |
| ASUSTek       | X502CA                      | Notebook    | [7876d4c48d](https://linux-hardware.org/?probe=7876d4c48d) | Aug 14, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [ca4fa8777d](https://linux-hardware.org/?probe=ca4fa8777d) | Aug 10, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9bcbc98b0f](https://linux-hardware.org/?probe=9bcbc98b0f) | Jul 26, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [c32745014a](https://linux-hardware.org/?probe=c32745014a) | Jul 22, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a70d38c48c](https://linux-hardware.org/?probe=a70d38c48c) | Jul 20, 2020 |
| Acer          | AO722                       | Notebook    | [90943ce018](https://linux-hardware.org/?probe=90943ce018) | Jul 10, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [87be3f63a0](https://linux-hardware.org/?probe=87be3f63a0) | Jul 09, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [82f2a3732c](https://linux-hardware.org/?probe=82f2a3732c) | Jul 09, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [e4318a8dea](https://linux-hardware.org/?probe=e4318a8dea) | Jul 04, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [ba6d8528e9](https://linux-hardware.org/?probe=ba6d8528e9) | Jul 04, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | Notebook                    | Notebook    | [b646ab05a7](https://linux-hardware.org/?probe=b646ab05a7) | Jun 30, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [0a4363a1ba](https://linux-hardware.org/?probe=0a4363a1ba) | Jun 28, 2020 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [853f76e35e](https://linux-hardware.org/?probe=853f76e35e) | Jun 23, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [56a67b5ddc](https://linux-hardware.org/?probe=56a67b5ddc) | Jun 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b8b588701d](https://linux-hardware.org/?probe=b8b588701d) | Jun 22, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| ASRock        | H61M-VS                     | Desktop     | [87788ef1c8](https://linux-hardware.org/?probe=87788ef1c8) | Jun 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [87e6d2f056](https://linux-hardware.org/?probe=87e6d2f056) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [7332f612bc](https://linux-hardware.org/?probe=7332f612bc) | May 30, 2020 |
| HP            | ProBook 4440s               | Notebook    | [5442b989be](https://linux-hardware.org/?probe=5442b989be) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [15c3385fcd](https://linux-hardware.org/?probe=15c3385fcd) | May 30, 2020 |
| Biostar       | H81MLV3                     | Desktop     | [d912bc8bdc](https://linux-hardware.org/?probe=d912bc8bdc) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [21283d29b3](https://linux-hardware.org/?probe=21283d29b3) | May 10, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [84339f57da](https://linux-hardware.org/?probe=84339f57da) | May 09, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [f43cc5765b](https://linux-hardware.org/?probe=f43cc5765b) | Apr 25, 2020 |
| Apple         | MacBookPro13,3              | Notebook    | [81946cb76f](https://linux-hardware.org/?probe=81946cb76f) | Apr 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [df8a7bcad8](https://linux-hardware.org/?probe=df8a7bcad8) | Mar 26, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [2971fd6031](https://linux-hardware.org/?probe=2971fd6031) | Mar 26, 2020 |
| HP            | 15                          | Notebook    | [cb0cf73a5d](https://linux-hardware.org/?probe=cb0cf73a5d) | Mar 04, 2020 |
| HP            | 15                          | Notebook    | [687592ff11](https://linux-hardware.org/?probe=687592ff11) | Mar 04, 2020 |
| Acer          | AO722                       | Notebook    | [08d71a347b](https://linux-hardware.org/?probe=08d71a347b) | Feb 29, 2020 |
| Acer          | AO722                       | Notebook    | [291cea2763](https://linux-hardware.org/?probe=291cea2763) | Feb 29, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [5ae0871de5](https://linux-hardware.org/?probe=5ae0871de5) | Feb 23, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [cfc85f91d5](https://linux-hardware.org/?probe=cfc85f91d5) | Feb 22, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [ab03f678e6](https://linux-hardware.org/?probe=ab03f678e6) | Feb 22, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b37b6efdf7](https://linux-hardware.org/?probe=b37b6efdf7) | Feb 18, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [f8c6ef3229](https://linux-hardware.org/?probe=f8c6ef3229) | Feb 17, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [0893b14338](https://linux-hardware.org/?probe=0893b14338) | Feb 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d2b7a56172](https://linux-hardware.org/?probe=d2b7a56172) | Jan 14, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [30baa09d89](https://linux-hardware.org/?probe=30baa09d89) | Jan 14, 2020 |
| Acer          | Aspire ES1-131              | Notebook    | [fcb74db0f2](https://linux-hardware.org/?probe=fcb74db0f2) | Jan 14, 2020 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [ca1baf42c2](https://linux-hardware.org/?probe=ca1baf42c2) | Dec 18, 2019 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [b3270b7077](https://linux-hardware.org/?probe=b3270b7077) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [5097027e46](https://linux-hardware.org/?probe=5097027e46) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [3fc475bd40](https://linux-hardware.org/?probe=3fc475bd40) | Dec 05, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Dell          | System XPS L502X            | Notebook    | [d43cf2a533](https://linux-hardware.org/?probe=d43cf2a533) | Sep 12, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a4264e7371](https://linux-hardware.org/?probe=a4264e7371) | Sep 12, 2019 |
| HP            | 18E7                        | Desktop     | [2d2bb51f61](https://linux-hardware.org/?probe=2d2bb51f61) | Aug 27, 2019 |
| Toshiba       | Satellite E45t-B            | Notebook    | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [29c5995612](https://linux-hardware.org/?probe=29c5995612) | Jul 29, 2019 |
| Toshiba       | Satellite P55W-C            | Notebook    | [cc12571867](https://linux-hardware.org/?probe=cc12571867) | Jul 27, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [76dbbe880b](https://linux-hardware.org/?probe=76dbbe880b) | Jul 10, 2019 |
| HP            | Pavilion 14                 | Notebook    | [6dde2ab979](https://linux-hardware.org/?probe=6dde2ab979) | Jun 08, 2019 |
| Apple         | MacBook1,1                  | Notebook    | [57ca5e1449](https://linux-hardware.org/?probe=57ca5e1449) | Jun 02, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a4d0b9a0cc](https://linux-hardware.org/?probe=a4d0b9a0cc) | May 27, 2019 |
| Dell          | 0CRH6C A02                  | Desktop     | [9bfbd0c2f6](https://linux-hardware.org/?probe=9bfbd0c2f6) | May 16, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [ebe6dcff50](https://linux-hardware.org/?probe=ebe6dcff50) | May 05, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [2d6ea0b597](https://linux-hardware.org/?probe=2d6ea0b597) | May 05, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6abf9ea94e](https://linux-hardware.org/?probe=6abf9ea94e) | Apr 17, 2019 |
| HP            | ENVY Notebook               | Notebook    | [4d812e744e](https://linux-hardware.org/?probe=4d812e744e) | Apr 17, 2019 |
| Cartimex      | H61H2-MV                    | Desktop     | [aa36029d7f](https://linux-hardware.org/?probe=aa36029d7f) | Apr 09, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [d857fd97fd](https://linux-hardware.org/?probe=d857fd97fd) | Mar 11, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [4b50a9d6a2](https://linux-hardware.org/?probe=4b50a9d6a2) | Jan 08, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [91f58fec26](https://linux-hardware.org/?probe=91f58fec26) | Jan 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Ubuntu 20.04         | 39        | 19.5%   |
| Ubuntu 18.04         | 21        | 10.5%   |
| Debian 11            | 8         | 4%      |
| Linux Mint 20.3      | 7         | 3.5%    |
| Ubuntu 22.04         | 6         | 3%      |
| OpenMandriva 4.3     | 5         | 2.5%    |
| Linux Mint 19.3      | 5         | 2.5%    |
| Fedora 34            | 5         | 2.5%    |
| Zorin 16             | 4         | 2%      |
| Zorin 15             | 4         | 2%      |
| Pop!_OS 21.10        | 4         | 2%      |
| Pop!_OS 21.04        | 4         | 2%      |
| OpenMandriva 4.2     | 4         | 2%      |
| KDE neon 20.04       | 4         | 2%      |
| Fedora 33            | 4         | 2%      |
| Ubuntu 21.10         | 3         | 1.5%    |
| Pop!_OS 20.04        | 3         | 1.5%    |
| Linux Mint 20.1      | 3         | 1.5%    |
| Fedora 36            | 3         | 1.5%    |
| Elementary 5.1.7     | 3         | 1.5%    |
| Xubuntu 18.04        | 2         | 1%      |
| Ubuntu 21.04         | 2         | 1%      |
| Ubuntu               | 2         | 1%      |
| Manjaro 21.2.5       | 2         | 1%      |
| Manjaro              | 2         | 1%      |
| Linux Mint 20.2      | 2         | 1%      |
| Linux Mint 20        | 2         | 1%      |
| Linux Mint 19.1      | 2         | 1%      |
| Fedora 35            | 2         | 1%      |
| Debian 10            | 2         | 1%      |
| BlackPanther 18.1    | 2         | 1%      |
| Arch Rolling         | 2         | 1%      |
| Arch                 | 2         | 1%      |
| Xubuntu 20.04        | 1         | 0.5%    |
| Void Linux           | 1         | 0.5%    |
| Ubuntu MATE 20.04    | 1         | 0.5%    |
| Ubuntu MATE 18.04    | 1         | 0.5%    |
| Ubuntu Budgie 22.04  | 1         | 0.5%    |
| Ubuntu Budgie 20.04  | 1         | 0.5%    |
| Ubuntu 20.10         | 1         | 0.5%    |
| Ubuntu 19.10         | 1         | 0.5%    |
| Ubuntu 19.04         | 1         | 0.5%    |
| Ubuntu 18.10         | 1         | 0.5%    |
| Ubuntu 16.04         | 1         | 0.5%    |
| RHEL 8               | 1         | 0.5%    |
| Peppermint 10        | 1         | 0.5%    |
| openSUSE Leap-15.2   | 1         | 0.5%    |
| Manjaro 21.2.1       | 1         | 0.5%    |
| Manjaro 20.1         | 1         | 0.5%    |
| Lubuntu 20.04        | 1         | 0.5%    |
| Lubuntu 18.04        | 1         | 0.5%    |
| Lubuntu 16.04        | 1         | 0.5%    |
| LMDE 5               | 1         | 0.5%    |
| LMDE 4               | 1         | 0.5%    |
| Kubuntu 22.04        | 1         | 0.5%    |
| Kubuntu 20.04        | 1         | 0.5%    |
| KDE neon 18.04       | 1         | 0.5%    |
| Kali 2022.2          | 1         | 0.5%    |
| Garuda Linux Soaring | 1         | 0.5%    |
| Fedora 32            | 1         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 76        | 38.78%  |
| Linux Mint    | 19        | 9.69%   |
| Fedora        | 16        | 8.16%   |
| Pop!_OS       | 11        | 5.61%   |
| Debian        | 10        | 5.1%    |
| OpenMandriva  | 9         | 4.59%   |
| Zorin         | 8         | 4.08%   |
| Manjaro       | 6         | 3.06%   |
| KDE neon      | 5         | 2.55%   |
| Elementary    | 4         | 2.04%   |
| Arch          | 4         | 2.04%   |
| Xubuntu       | 3         | 1.53%   |
| Lubuntu       | 3         | 1.53%   |
| Ubuntu MATE   | 2         | 1.02%   |
| Ubuntu Budgie | 2         | 1.02%   |
| LMDE          | 2         | 1.02%   |
| Kubuntu       | 2         | 1.02%   |
| Clear Linux   | 2         | 1.02%   |
| BlackPanther  | 2         | 1.02%   |
| Void Linux    | 1         | 0.51%   |
| RHEL          | 1         | 0.51%   |
| Peppermint    | 1         | 0.51%   |
| openSUSE      | 1         | 0.51%   |
| Kali          | 1         | 0.51%   |
| Garuda Linux  | 1         | 0.51%   |
| Endless       | 1         | 0.51%   |
| Deepin        | 1         | 0.51%   |
| CentOS        | 1         | 0.51%   |
| ArcoLinux     | 1         | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-54-generic         | 6         | 2.75%   |
| 5.4.0-42-generic         | 5         | 2.29%   |
| 5.4.0-45-generic         | 4         | 1.83%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.83%   |
| 5.15.0-33-generic        | 4         | 1.83%   |
| 5.13.0-35-generic        | 4         | 1.83%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.83%   |
| 5.8.0-41-generic         | 3         | 1.38%   |
| 5.4.0-7634-generic       | 3         | 1.38%   |
| 5.4.0-58-generic         | 3         | 1.38%   |
| 5.4.0-56-generic         | 3         | 1.38%   |
| 5.4.0-48-generic         | 3         | 1.38%   |
| 5.4.0-37-generic         | 3         | 1.38%   |
| 5.4.0-26-generic         | 3         | 1.38%   |
| 5.16.11-76051611-generic | 3         | 1.38%   |
| 5.13.0-7614-generic      | 3         | 1.38%   |
| 5.0.0-37-generic         | 3         | 1.38%   |
| 5.0.0-23-generic         | 3         | 1.38%   |
| 5.8.0-50-generic         | 2         | 0.92%   |
| 5.8.0-43-generic         | 2         | 0.92%   |
| 5.4.0-77-generic         | 2         | 0.92%   |
| 5.4.0-73-generic         | 2         | 0.92%   |
| 5.4.0-47-generic         | 2         | 0.92%   |
| 5.4.0-29-generic         | 2         | 0.92%   |
| 5.4.0-110-generic        | 2         | 0.92%   |
| 5.3.0-62-generic         | 2         | 0.92%   |
| 5.15.0-27-generic        | 2         | 0.92%   |
| 5.13.0-51-generic        | 2         | 0.92%   |
| 5.13.0-30-generic        | 2         | 0.92%   |
| 5.13.0-27-generic        | 2         | 0.92%   |
| 5.11.16-300.fc34.x86_64  | 2         | 0.92%   |
| 5.11.0-27-generic        | 2         | 0.92%   |
| 5.10.0-8-amd64           | 2         | 0.92%   |
| 4.18.16-desktop-1bP      | 2         | 0.92%   |
| 4.18.0-17-generic        | 2         | 0.92%   |
| 4.15.0-54-generic        | 2         | 0.92%   |
| 4.15.0-50-generic        | 2         | 0.92%   |
| 4.15.0-43-generic        | 2         | 0.92%   |
| 4.15.0-20-generic        | 2         | 0.92%   |
| 4.15.0-109-generic       | 2         | 0.92%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.46%   |
| 5.8.15-201.fc32.x86_64   | 1         | 0.46%   |
| 5.8.1-arch1-1            | 1         | 0.46%   |
| 5.8.0-63-generic         | 1         | 0.46%   |
| 5.8.0-45-generic         | 1         | 0.46%   |
| 5.8.0-40-generic         | 1         | 0.46%   |
| 5.8.0-14-generic         | 1         | 0.46%   |
| 5.7.17-2-MANJARO         | 1         | 0.46%   |
| 5.7.1-050701-generic     | 1         | 0.46%   |
| 5.7.0-0.bpo.2-amd64      | 1         | 0.46%   |
| 5.5.5-arch1-1            | 1         | 0.46%   |
| 5.5.16-200.fc31.x86_64   | 1         | 0.46%   |
| 5.4.50-amd64-desktop     | 1         | 0.46%   |
| 5.4.26-rt17-1-rt         | 1         | 0.46%   |
| 5.4.111                  | 1         | 0.46%   |
| 5.4.0-94-generic         | 1         | 0.46%   |
| 5.4.0-91-generic         | 1         | 0.46%   |
| 5.4.0-90-generic         | 1         | 0.46%   |
| 5.4.0-89-generic         | 1         | 0.46%   |
| 5.4.0-88-generic         | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 56        | 27.32%  |
| 4.15.0   | 18        | 8.78%   |
| 5.13.0   | 16        | 7.8%    |
| 5.8.0    | 11        | 5.37%   |
| 5.11.0   | 9         | 4.39%   |
| 5.0.0    | 9         | 4.39%   |
| 5.15.0   | 8         | 3.9%    |
| 5.10.0   | 7         | 3.41%   |
| 5.3.0    | 6         | 2.93%   |
| 5.16.7   | 5         | 2.44%   |
| 5.10.14  | 4         | 1.95%   |
| 5.16.11  | 3         | 1.46%   |
| 4.19.0   | 3         | 1.46%   |
| 4.18.0   | 3         | 1.46%   |
| 5.17.5   | 2         | 0.98%   |
| 5.16.13  | 2         | 0.98%   |
| 5.16.0   | 2         | 0.98%   |
| 5.11.16  | 2         | 0.98%   |
| 4.18.16  | 2         | 0.98%   |
| 5.9.16   | 1         | 0.49%   |
| 5.8.15   | 1         | 0.49%   |
| 5.8.1    | 1         | 0.49%   |
| 5.7.17   | 1         | 0.49%   |
| 5.7.1    | 1         | 0.49%   |
| 5.7.0    | 1         | 0.49%   |
| 5.5.5    | 1         | 0.49%   |
| 5.5.16   | 1         | 0.49%   |
| 5.4.50   | 1         | 0.49%   |
| 5.4.26   | 1         | 0.49%   |
| 5.4.111  | 1         | 0.49%   |
| 5.3.9    | 1         | 0.49%   |
| 5.3.18   | 1         | 0.49%   |
| 5.18.6   | 1         | 0.49%   |
| 5.18.5   | 1         | 0.49%   |
| 5.17.9   | 1         | 0.49%   |
| 5.17.4   | 1         | 0.49%   |
| 5.17.0   | 1         | 0.49%   |
| 5.16.15  | 1         | 0.49%   |
| 5.15.7   | 1         | 0.49%   |
| 5.15.5   | 1         | 0.49%   |
| 5.15.28  | 1         | 0.49%   |
| 5.15.12  | 1         | 0.49%   |
| 5.14.11  | 1         | 0.49%   |
| 5.14.10  | 1         | 0.49%   |
| 5.13.4   | 1         | 0.49%   |
| 5.12.9   | 1         | 0.49%   |
| 5.12.1   | 1         | 0.49%   |
| 5.12.0   | 1         | 0.49%   |
| 5.11.11  | 1         | 0.49%   |
| 5.10.79  | 1         | 0.49%   |
| 5.10.59  | 1         | 0.49%   |
| 5.10.13  | 1         | 0.49%   |
| 5.10.105 | 1         | 0.49%   |
| 5.0.10   | 1         | 0.49%   |
| 4.9.0    | 1         | 0.49%   |
| 3.10.0   | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 59        | 29.06%  |
| 4.15    | 18        | 8.87%   |
| 5.13    | 17        | 8.37%   |
| 5.10    | 15        | 7.39%   |
| 5.8     | 13        | 6.4%    |
| 5.16    | 13        | 6.4%    |
| 5.11    | 12        | 5.91%   |
| 5.15    | 11        | 5.42%   |
| 5.0     | 10        | 4.93%   |
| 5.3     | 8         | 3.94%   |
| 5.17    | 5         | 2.46%   |
| 4.18    | 5         | 2.46%   |
| 5.7     | 3         | 1.48%   |
| 4.19    | 3         | 1.48%   |
| 5.5     | 2         | 0.99%   |
| 5.18    | 2         | 0.99%   |
| 5.14    | 2         | 0.99%   |
| 5.12    | 2         | 0.99%   |
| 5.9     | 1         | 0.49%   |
| 4.9     | 1         | 0.49%   |
| 3.10    | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 175       | 93.58%  |
| i686   | 12        | 6.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 92        | 47.67%  |
| Unknown    | 26        | 13.47%  |
| KDE5       | 20        | 10.36%  |
| X-Cinnamon | 17        | 8.81%   |
| XFCE       | 9         | 4.66%   |
| MATE       | 7         | 3.63%   |
| KDE        | 6         | 3.11%   |
| Pantheon   | 4         | 2.07%   |
| LXDE       | 3         | 1.55%   |
| qtile      | 2         | 1.04%   |
| Deepin     | 2         | 1.04%   |
| Budgie     | 2         | 1.04%   |
| LXQt       | 1         | 0.52%   |
| jwm        | 1         | 0.52%   |
| ICEWM      | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 150       | 76.92%  |
| Wayland | 30        | 15.38%  |
| Unknown | 14        | 7.18%   |
| Tty     | 1         | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 120       | 60.91%  |
| GDM     | 26        | 13.2%   |
| SDDM    | 21        | 10.66%  |
| GDM3    | 16        | 8.12%   |
| LightDM | 9         | 4.57%   |
| TDM     | 5         | 2.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_EC   | 95        | 50.26%  |
| en_US   | 47        | 24.87%  |
| Unknown | 19        | 10.05%  |
| es_ES   | 15        | 7.94%   |
| C       | 3         | 1.59%   |
| ru_RU   | 2         | 1.06%   |
| fr_FR   | 2         | 1.06%   |
| es_PE   | 2         | 1.06%   |
| de_DE   | 2         | 1.06%   |
| es_US   | 1         | 0.53%   |
| es_MX   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 106       | 55.5%   |
| EFI  | 85        | 44.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 153       | 79.27%  |
| Overlay | 16        | 8.29%   |
| Btrfs   | 13        | 6.74%   |
| Xfs     | 4         | 2.07%   |
| Unknown | 4         | 2.07%   |
| Zfs     | 1         | 0.52%   |
| Tmpfs   | 1         | 0.52%   |
| Ext2    | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 129       | 67.89%  |
| GPT     | 42        | 22.11%  |
| MBR     | 19        | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 168       | 87.96%  |
| Yes       | 23        | 12.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 131       | 68.95%  |
| Yes       | 59        | 31.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 32        | 17.11%  |
| ASUSTek Computer      | 27        | 14.44%  |
| Dell                  | 22        | 11.76%  |
| Lenovo                | 18        | 9.63%   |
| Toshiba               | 11        | 5.88%   |
| Intel                 | 9         | 4.81%   |
| Gigabyte Technology   | 9         | 4.81%   |
| Biostar               | 8         | 4.28%   |
| Google                | 7         | 3.74%   |
| Acer                  | 7         | 3.74%   |
| Sony                  | 5         | 2.67%   |
| MSI                   | 3         | 1.6%    |
| Foxconn               | 3         | 1.6%    |
| ASRock                | 3         | 1.6%    |
| Apple                 | 3         | 1.6%    |
| Samsung Electronics   | 2         | 1.07%   |
| Razer                 | 2         | 1.07%   |
| Unknown               | 2         | 1.07%   |
| XTRATECH COMPUTERS SA | 1         | 0.53%   |
| TrekStor              | 1         | 0.53%   |
| TPV-INVENTA           | 1         | 0.53%   |
| Timi                  | 1         | 0.53%   |
| Shuttle               | 1         | 0.53%   |
| Pegatron              | 1         | 0.53%   |
| Gateway               | 1         | 0.53%   |
| Fujitsu               | 1         | 0.53%   |
| ECS                   | 1         | 0.53%   |
| Compal                | 1         | 0.53%   |
| Chuwi                 | 1         | 0.53%   |
| Cartimex              | 1         | 0.53%   |
| AMI                   | 1         | 0.53%   |
| Alienware             | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| ASUS All Series                                    | 4         | 2.14%   |
| ASUS PRIME A320M-A                                 | 3         | 1.6%    |
| Unknown                                            | 3         | 1.6%    |
| Lenovo IdeaPad 320-15ABR 80XS                      | 2         | 1.07%   |
| HP ProBook 4440s                                   | 2         | 1.07%   |
| HP Pavilion Laptop 15-cw0xxx                       | 2         | 1.07%   |
| Gigabyte H81M-H                                    | 2         | 1.07%   |
| Dell Inspiron 5570                                 | 2         | 1.07%   |
| Dell Inspiron 3442                                 | 2         | 1.07%   |
| Dell Inspiron 1420                                 | 2         | 1.07%   |
| Dell G5 5587                                       | 2         | 1.07%   |
| Biostar H61MGV3                                    | 2         | 1.07%   |
| Biostar G31-M7 TE                                  | 2         | 1.07%   |
| XTRATECH COMPUTERS SA MN-1022X                     | 1         | 0.53%   |
| TrekStor Primebook C13                             | 1         | 0.53%   |
| TPV-INVENTA 2AF2 A01                               | 1         | 0.53%   |
| Toshiba Satellite S55-B                            | 1         | 0.53%   |
| Toshiba Satellite S55-A                            | 1         | 0.53%   |
| Toshiba Satellite P775                             | 1         | 0.53%   |
| Toshiba Satellite P55W-C                           | 1         | 0.53%   |
| Toshiba Satellite L50-B                            | 1         | 0.53%   |
| Toshiba Satellite L45-B                            | 1         | 0.53%   |
| Toshiba Satellite E45t-B                           | 1         | 0.53%   |
| Toshiba Satellite C55D-A                           | 1         | 0.53%   |
| Toshiba Satellite C55-B                            | 1         | 0.53%   |
| Toshiba Satellite C45-A                            | 1         | 0.53%   |
| Toshiba PORTEGE M805                               | 1         | 0.53%   |
| Timi RedmiBook 14-APCS                             | 1         | 0.53%   |
| Sony VPCEG30EL                                     | 1         | 0.53%   |
| Sony VPCCW1S1E                                     | 1         | 0.53%   |
| Sony VGN-CR120E                                    | 1         | 0.53%   |
| Sony SVE14A25CLB                                   | 1         | 0.53%   |
| Sony SVE14113ELW                                   | 1         | 0.53%   |
| Shuttle SFM27                                      | 1         | 0.53%   |
| Samsung 550XCJ/550XCR                              | 1         | 0.53%   |
| Samsung 530U4E/540U4E                              | 1         | 0.53%   |
| Razer Blade Stealth                                | 1         | 0.53%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.53%   |
| Pegatron CQ1506LA                                  | 1         | 0.53%   |
| MSI MS-7B98                                        | 1         | 0.53%   |
| MSI MS-7758                                        | 1         | 0.53%   |
| MSI GF63 Thin 9SC                                  | 1         | 0.53%   |
| Lenovo Yoga C930-13IKB 81C4                        | 1         | 0.53%   |
| Lenovo Yoga 730-13IKB 81CT                         | 1         | 0.53%   |
| Lenovo V15-IIL 82C5                                | 1         | 0.53%   |
| Lenovo ThinkPad X201 3680PKS                       | 1         | 0.53%   |
| Lenovo ThinkPad T530 2429JB5                       | 1         | 0.53%   |
| Lenovo ThinkPad P40 Yoga 20GQ000EUS                | 1         | 0.53%   |
| Lenovo ThinkPad E15 20REA00000                     | 1         | 0.53%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2                  | 1         | 0.53%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK              | 1         | 0.53%   |
| Lenovo IdeaPad 330S-15IKB 81F5                     | 1         | 0.53%   |
| Lenovo IdeaPad 330-15AST 81D6                      | 1         | 0.53%   |
| Lenovo IdeaPad 330-14IGM 81D0                      | 1         | 0.53%   |
| Lenovo IdeaPad 320-15IKB 80XL                      | 1         | 0.53%   |
| Lenovo G710 20252                                  | 1         | 0.53%   |
| Lenovo G580 20150                                  | 1         | 0.53%   |
| Lenovo 3000 V200 076433G                           | 1         | 0.53%   |
| Intel NUC8i3BEH                                    | 1         | 0.53%   |
| Intel H81                                          | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Inspiron                  | 14        | 7.49%   |
| Toshiba Satellite              | 10        | 5.35%   |
| HP Pavilion                    | 9         | 4.81%   |
| ASUS PRIME                     | 8         | 4.28%   |
| Lenovo IdeaPad                 | 7         | 3.74%   |
| Lenovo ThinkPad                | 4         | 2.14%   |
| HP Laptop                      | 4         | 2.14%   |
| ASUS VivoBook                  | 4         | 2.14%   |
| ASUS All                       | 4         | 2.14%   |
| Acer Aspire                    | 4         | 2.14%   |
| HP ProBook                     | 3         | 1.6%    |
| Unknown                        | 3         | 1.6%    |
| Razer Blade                    | 2         | 1.07%   |
| Lenovo Yoga                    | 2         | 1.07%   |
| HP ENVY                        | 2         | 1.07%   |
| HP EliteBook                   | 2         | 1.07%   |
| HP 15                          | 2         | 1.07%   |
| Gigabyte H81M-H                | 2         | 1.07%   |
| Dell Latitude                  | 2         | 1.07%   |
| Dell G5                        | 2         | 1.07%   |
| Biostar H61MGV3                | 2         | 1.07%   |
| Biostar G31-M7                 | 2         | 1.07%   |
| Acer TravelMate                | 2         | 1.07%   |
| XTRATECH COMPUTERS SA MN-1022X | 1         | 0.53%   |
| TrekStor Primebook             | 1         | 0.53%   |
| TPV-INVENTA 2AF2               | 1         | 0.53%   |
| Toshiba PORTEGE                | 1         | 0.53%   |
| Timi RedmiBook                 | 1         | 0.53%   |
| Sony VPCEG30EL                 | 1         | 0.53%   |
| Sony VPCCW1S1E                 | 1         | 0.53%   |
| Sony VGN-CR120E                | 1         | 0.53%   |
| Sony SVE14A25CLB               | 1         | 0.53%   |
| Sony SVE14113ELW               | 1         | 0.53%   |
| Shuttle SFM27                  | 1         | 0.53%   |
| Samsung 550XCJ                 | 1         | 0.53%   |
| Samsung 530U4E                 | 1         | 0.53%   |
| Pegatron CQ1506LA              | 1         | 0.53%   |
| MSI MS-7B98                    | 1         | 0.53%   |
| MSI MS-7758                    | 1         | 0.53%   |
| MSI GF63                       | 1         | 0.53%   |
| Lenovo V15-IIL                 | 1         | 0.53%   |
| Lenovo IdeaPadFlex             | 1         | 0.53%   |
| Lenovo G710                    | 1         | 0.53%   |
| Lenovo G580                    | 1         | 0.53%   |
| Lenovo 3000                    | 1         | 0.53%   |
| Intel NUC8i3BEH                | 1         | 0.53%   |
| Intel H81                      | 1         | 0.53%   |
| Intel DZ68DB                   | 1         | 0.53%   |
| Intel DP55KG                   | 1         | 0.53%   |
| Intel DH61WW                   | 1         | 0.53%   |
| Intel DH61BF                   | 1         | 0.53%   |
| Intel DG41RQ                   | 1         | 0.53%   |
| Intel DG33BU                   | 1         | 0.53%   |
| Intel DB75EN                   | 1         | 0.53%   |
| HP ProLiant                    | 1         | 0.53%   |
| HP ProDesk                     | 1         | 0.53%   |
| HP Notebook                    | 1         | 0.53%   |
| HP Mini                        | 1         | 0.53%   |
| HP G42                         | 1         | 0.53%   |
| HP Compaq                      | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 23        | 12.3%   |
| 2013 | 21        | 11.23%  |
| 2017 | 19        | 10.16%  |
| 2012 | 19        | 10.16%  |
| 2020 | 16        | 8.56%   |
| 2011 | 13        | 6.95%   |
| 2019 | 11        | 5.88%   |
| 2014 | 10        | 5.35%   |
| 2016 | 9         | 4.81%   |
| 2015 | 9         | 4.81%   |
| 2021 | 8         | 4.28%   |
| 2007 | 8         | 4.28%   |
| 2010 | 7         | 3.74%   |
| 2009 | 7         | 3.74%   |
| 2008 | 4         | 2.14%   |
| 2006 | 2         | 1.07%   |
| 2005 | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 120       | 64.17%  |
| Desktop     | 57        | 30.48%  |
| Convertible | 7         | 3.74%   |
| Mini pc     | 2         | 1.07%   |
| Tablet      | 1         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 174       | 92.55%  |
| Enabled  | 14        | 7.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 180       | 96.26%  |
| Yes  | 7         | 3.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 54        | 28.13%  |
| 8.01-16.0  | 43        | 22.4%   |
| 3.01-4.0   | 39        | 20.31%  |
| 16.01-24.0 | 21        | 10.94%  |
| 1.01-2.0   | 18        | 9.38%   |
| 32.01-64.0 | 9         | 4.69%   |
| 24.01-32.0 | 4         | 2.08%   |
| 2.01-3.0   | 3         | 1.56%   |
| 0.51-1.0   | 1         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 65        | 31.25%  |
| 2.01-3.0   | 59        | 28.37%  |
| 4.01-8.0   | 32        | 15.38%  |
| 3.01-4.0   | 32        | 15.38%  |
| 0.51-1.0   | 10        | 4.81%   |
| 8.01-16.0  | 6         | 2.88%   |
| 0.01-0.5   | 3         | 1.44%   |
| 24.01-32.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 135       | 69.95%  |
| 2      | 45        | 23.32%  |
| 3      | 12        | 6.22%   |
| 5      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 59.04%  |
| Yes       | 77        | 40.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 84.49%  |
| No        | 29        | 15.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 77.13%  |
| No        | 43        | 22.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 56.91%  |
| No        | 81        | 43.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ecuador | 187       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Quito                          | 79        | 41.15%  |
| Guayaquil                      | 50        | 26.04%  |
| Cuenca                         | 15        | 7.81%   |
| Manta                          | 6         | 3.13%   |
| Loja                           | 4         | 2.08%   |
| Ambato                         | 4         | 2.08%   |
| Riobamba                       | 3         | 1.56%   |
| Portoviejo                     | 3         | 1.56%   |
| Hacienda Ibarra                | 3         | 1.56%   |
| Machala                        | 2         | 1.04%   |
| Latacunga                      | 2         | 1.04%   |
| Cotacachi                      | 2         | 1.04%   |
| Uyumbicho                      | 1         | 0.52%   |
| Santo Domingo de los Colorados | 1         | 0.52%   |
| Samborondon                    | 1         | 0.52%   |
| Quevedo                        | 1         | 0.52%   |
| Ponceano                       | 1         | 0.52%   |
| Otavalo                        | 1         | 0.52%   |
| Nueva Loja                     | 1         | 0.52%   |
| Montecristi                    | 1         | 0.52%   |
| Las Pinas                      | 1         | 0.52%   |
| La Troncal                     | 1         | 0.52%   |
| La Providencia                 | 1         | 0.52%   |
| Ibarra                         | 1         | 0.52%   |
| Hacienda La Libertad           | 1         | 0.52%   |
| Guanujo                        | 1         | 0.52%   |
| Guamani                        | 1         | 0.52%   |
| Cayambe                        | 1         | 0.52%   |
| Cariamanga                     | 1         | 0.52%   |
| Babahoyo                       | 1         | 0.52%   |
| Ayacucho                       | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 56        | 75     | 23.14%  |
| Toshiba                 | 36        | 42     | 14.88%  |
| Seagate                 | 36        | 52     | 14.88%  |
| Samsung Electronics     | 17        | 18     | 7.02%   |
| Kingston                | 15        | 20     | 6.2%    |
| Hitachi                 | 15        | 17     | 6.2%    |
| Unknown                 | 10        | 17     | 4.13%   |
| SK hynix                | 6         | 7      | 2.48%   |
| A-DATA Technology       | 6         | 8      | 2.48%   |
| SanDisk                 | 5         | 5      | 2.07%   |
| Hewlett-Packard         | 5         | 5      | 2.07%   |
| HGST                    | 4         | 5      | 1.65%   |
| PNY                     | 3         | 3      | 1.24%   |
| Intel                   | 3         | 4      | 1.24%   |
| Fujitsu                 | 3         | 3      | 1.24%   |
| SPCC                    | 2         | 2      | 0.83%   |
| Micron Technology       | 2         | 2      | 0.83%   |
| Crucial                 | 2         | 2      | 0.83%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.41%   |
| SABRENT                 | 1         | 1      | 0.41%   |
| Phison                  | 1         | 1      | 0.41%   |
| OWC                     | 1         | 1      | 0.41%   |
| Netac                   | 1         | 1      | 0.41%   |
| Micro Center            | 1         | 1      | 0.41%   |
| Lite-On                 | 1         | 1      | 0.41%   |
| KIOXIA                  | 1         | 2      | 0.41%   |
| JMicron Technology      | 1         | 1      | 0.41%   |
| Imation                 | 1         | 1      | 0.41%   |
| HS-SSD-E100N            | 1         | 1      | 0.41%   |
| HPE                     | 1         | 1      | 0.41%   |
| Golden                  | 1         | 1      | 0.41%   |
| Gigabyte Technology     | 1         | 1      | 0.41%   |
| Apple                   | 1         | 2      | 0.41%   |
| Unknown                 | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                | 6         | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 2.33%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 2.33%   |
| Seagate ST500DM002-1BD142 500GB         | 5         | 1.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 4         | 1.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 4         | 1.55%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.55%   |
| Toshiba DT01ACA100 1TB                  | 4         | 1.55%   |
| Unknown MMC Card  32GB                  | 3         | 1.16%   |
| Unknown MMC Card  16GB                  | 3         | 1.16%   |
| Samsung HD502HJ 500GB                   | 3         | 1.16%   |
| HP SSD S700 500GB                       | 3         | 1.16%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 2         | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 0.78%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 0.78%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 0.78%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.78%   |
| Unknown MMC Card  64GB                  | 2         | 0.78%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.78%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 0.78%   |
| Toshiba DT01ACA200 2TB                  | 2         | 0.78%   |
| SK hynix NVMe SSD Drive 256GB           | 2         | 0.78%   |
| Seagate ST9500325AS 500GB               | 2         | 0.78%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 0.78%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 0.78%   |
| Kingston SV300S37A60G 64GB SSD          | 2         | 0.78%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.78%   |
| Hitachi HTS543232A7A384 320GB           | 2         | 0.78%   |
| Hitachi HTS541616J9SA00 160GB           | 2         | 0.78%   |
| Hitachi HDS721050CLA660 500GB           | 2         | 0.78%   |
| HGST HTS545050A7E380 500GB              | 2         | 0.78%   |
| A-DATA SU650 120GB SSD                  | 2         | 0.78%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.39%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.39%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.39%   |
| WDC WDBNCE5000PNC 500GB SSD             | 1         | 0.39%   |
| WDC WD7500BPVX-22JC3T0 752GB            | 1         | 0.39%   |
| WDC WD7500BPKX-80HPJT0 752GB            | 1         | 0.39%   |
| WDC WD7500BPKT-75PK4T0 752GB            | 1         | 0.39%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.39%   |
| WDC WD5000AVVS-63M8B0 500GB             | 1         | 0.39%   |
| WDC WD5000AAKX-75U6AA0 500GB            | 1         | 0.39%   |
| WDC WD5000AAKX-60U6AA0 500GB            | 1         | 0.39%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 1         | 0.39%   |
| WDC WD5000AAKS-00V2B0 500GB             | 1         | 0.39%   |
| WDC WD3200AVVS-63L2B0 320GB             | 1         | 0.39%   |
| WDC WD3200AAJS-60M0A0 320GB             | 1         | 0.39%   |
| WDC WD30EZRS-00J99B0 3TB                | 1         | 0.39%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.39%   |
| WDC WD2500BEVS-75UST0 250GB             | 1         | 0.39%   |
| WDC WD20SPZX-75UA7T1 2TB                | 1         | 0.39%   |
| WDC WD20EARX-00PASB0 2TB                | 1         | 0.39%   |
| WDC WD1600HLHX-60JJPV1 160GB            | 1         | 0.39%   |
| WDC WD1600AAJS-75M0A0 160GB             | 1         | 0.39%   |
| WDC WD1200BEVS-22UST0 120GB             | 1         | 0.39%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 40        | 56     | 27.59%  |
| Seagate             | 36        | 52     | 24.83%  |
| Toshiba             | 33        | 38     | 22.76%  |
| Hitachi             | 15        | 17     | 10.34%  |
| Samsung Electronics | 11        | 12     | 7.59%   |
| HGST                | 4         | 5      | 2.76%   |
| Fujitsu             | 3         | 3      | 2.07%   |
| Unknown             | 1         | 3      | 0.69%   |
| JMicron Technology  | 1         | 1      | 0.69%   |
| HPE                 | 1         | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 17     | 22.22%  |
| WDC                 | 13        | 14     | 20.63%  |
| SanDisk             | 5         | 5      | 7.94%   |
| A-DATA Technology   | 5         | 6      | 7.94%   |
| Hewlett-Packard     | 4         | 4      | 6.35%   |
| PNY                 | 3         | 3      | 4.76%   |
| Toshiba             | 2         | 3      | 3.17%   |
| SPCC                | 2         | 2      | 3.17%   |
| SK hynix            | 2         | 2      | 3.17%   |
| Intel               | 2         | 2      | 3.17%   |
| Crucial             | 2         | 2      | 3.17%   |
| Samsung Electronics | 1         | 1      | 1.59%   |
| OWC                 | 1         | 1      | 1.59%   |
| Netac               | 1         | 1      | 1.59%   |
| Micron Technology   | 1         | 1      | 1.59%   |
| Micro Center        | 1         | 1      | 1.59%   |
| HS-SSD-E100N        | 1         | 1      | 1.59%   |
| Golden              | 1         | 1      | 1.59%   |
| Gigabyte Technology | 1         | 1      | 1.59%   |
| Apple               | 1         | 2      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 129       | 188    | 58.37%  |
| SSD     | 56        | 70     | 25.34%  |
| NVMe    | 26        | 31     | 11.76%  |
| MMC     | 9         | 15     | 4.07%   |
| Unknown | 1         | 1      | 0.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 164       | 251    | 81.19%  |
| NVMe | 25        | 30     | 12.38%  |
| MMC  | 9         | 15     | 4.46%   |
| SAS  | 4         | 9      | 1.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 153    | 58.64%  |
| 0.51-1.0   | 64        | 86     | 33.51%  |
| 1.01-2.0   | 14        | 18     | 7.33%   |
| 2.01-3.0   | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 52        | 26.4%   |
| 101-250        | 49        | 24.87%  |
| 501-1000       | 28        | 14.21%  |
| 1001-2000      | 22        | 11.17%  |
| 1-20           | 15        | 7.61%   |
| 51-100         | 13        | 6.6%    |
| 21-50          | 10        | 5.08%   |
| More than 3000 | 4         | 2.03%   |
| Unknown        | 4         | 2.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 36.95%  |
| 21-50          | 39        | 19.21%  |
| 101-250        | 31        | 15.27%  |
| 251-500        | 21        | 10.34%  |
| 51-100         | 15        | 7.39%   |
| 501-1000       | 10        | 4.93%   |
| 1001-2000      | 6         | 2.96%   |
| Unknown        | 4         | 1.97%   |
| More than 3000 | 2         | 0.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2         | 3      | 9.09%   |
| Hitachi HDS721050CLA660 500GB     | 2         | 2      | 9.09%   |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 4.55%   |
| Toshiba MQ01ABF050 500GB          | 1         | 2      | 4.55%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 4.55%   |
| Toshiba MK3259GSXP 320GB          | 1         | 1      | 4.55%   |
| Seagate ST3750330AS 752GB         | 1         | 1      | 4.55%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 4.55%   |
| Seagate ST1000LX015-1U7172 1TB    | 1         | 2      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 4.55%   |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 2      | 4.55%   |
| Samsung Electronics HD501LJ 500GB | 1         | 1      | 4.55%   |
| Samsung Electronics HD322HJ 320GB | 1         | 1      | 4.55%   |
| Kingston SNS4151S316GD 16GB SSD   | 1         | 1      | 4.55%   |
| HPE MB0500EAMZD 500GB             | 1         | 1      | 4.55%   |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 4.55%   |
| Hitachi HTS543232L9SA00 320GB     | 1         | 1      | 4.55%   |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 4.55%   |
| Fujitsu MHZ2160BH G1 160GB        | 1         | 1      | 4.55%   |
| Fujitsu MHY2250BH 250GB           | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 31.82%  |
| Hitachi             | 4         | 4      | 18.18%  |
| Toshiba             | 3         | 4      | 13.64%  |
| Samsung Electronics | 2         | 2      | 9.09%   |
| Fujitsu             | 2         | 2      | 9.09%   |
| WDC                 | 1         | 1      | 4.55%   |
| Kingston            | 1         | 1      | 4.55%   |
| HPE                 | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 33.33%  |
| Hitachi             | 4         | 4      | 19.05%  |
| Toshiba             | 3         | 4      | 14.29%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Fujitsu             | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| HPE                 | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 25     | 94.74%  |
| SSD  | 1         | 1      | 5.26%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 130       | 219    | 65.99%  |
| Works    | 48        | 60     | 24.37%  |
| Malfunc  | 19        | 26     | 9.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 134       | 65.05%  |
| AMD                          | 37        | 17.96%  |
| Samsung Electronics          | 6         | 2.91%   |
| SanDisk                      | 5         | 2.43%   |
| SK hynix                     | 4         | 1.94%   |
| Marvell Technology Group     | 4         | 1.94%   |
| VIA Technologies             | 2         | 0.97%   |
| Kingston Technology Company  | 2         | 0.97%   |
| JMicron Technology           | 2         | 0.97%   |
| ASMedia Technology           | 2         | 0.97%   |
| Union Memory (Shenzhen)      | 1         | 0.49%   |
| Toshiba America Info Systems | 1         | 0.49%   |
| Silicon Motion               | 1         | 0.49%   |
| Phison Electronics           | 1         | 0.49%   |
| Micron Technology            | 1         | 0.49%   |
| Lite-On Technology           | 1         | 0.49%   |
| KIOXIA                       | 1         | 0.49%   |
| ADATA Technology             | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28        | 11.72%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 5.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 5.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 5.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 4.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 3.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 2.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.67%   |
| AMD FCH SATA Controller D                                                               | 4         | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 1.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.26%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.84%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.84%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.84%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 0.84%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.84%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1         | 0.42%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.42%   |
| VIA Serial ATA Controller                                                               | 1         | 0.42%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.42%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.42%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 1         | 0.42%   |
| SK hynix BC511                                                                          | 1         | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.42%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.42%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.42%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 0.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.42%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.42%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.42%   |
| Micron Non-Volatile memory controller                                                   | 1         | 0.42%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1         | 0.42%   |
| Marvell Group 88SE914D SATA-600 Controller                                              | 1         | 0.42%   |
| Marvell Group 88SE6145 SATA II PCI-E controller                                         | 1         | 0.42%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1         | 0.42%   |
| Lite-On NVMe Controller                                                                 | 1         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 139       | 67.15%  |
| IDE  | 30        | 14.49%  |
| NVMe | 25        | 12.08%  |
| RAID | 13        | 6.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 146       | 78.07%  |
| AMD    | 41        | 21.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 7         | 3.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 4         | 2.14%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 4         | 2.14%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 3         | 1.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz               | 3         | 1.6%    |
| Intel Core i7-4510U CPU @ 2.00GHz               | 3         | 1.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 1.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 1.6%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 3         | 1.6%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 3         | 1.6%    |
| Intel Pentium CPU G2030 @ 3.00GHz               | 2         | 1.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.07%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 2         | 1.07%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 2         | 1.07%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.07%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 1.07%   |
| Intel Core i3-10100F CPU @ 3.60GHz              | 2         | 1.07%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz           | 2         | 1.07%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz            | 2         | 1.07%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz            | 2         | 1.07%   |
| Intel Atom CPU N455 @ 1.66GHz                   | 2         | 1.07%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2         | 1.07%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2         | 1.07%   |
| AMD E1-2100 APU with Radeon HD Graphics         | 2         | 1.07%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 2         | 1.07%   |
| AMD E-300 APU with Radeon HD Graphics           | 2         | 1.07%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 2         | 1.07%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 1.07%   |
| Intel Xeon CPU X5660 @ 2.80GHz                  | 1         | 0.53%   |
| Intel Pentium M processor 1.86GHz               | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1         | 0.53%   |
| Intel Pentium CPU G630 @ 2.70GHz                | 1         | 0.53%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 1         | 0.53%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1         | 0.53%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.53%   |
| Intel Genuine CPU T2500 @ 2.00GHz               | 1         | 0.53%   |
| Intel Genuine CPU T2300 @ 1.66GHz               | 1         | 0.53%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 0.53%   |
| Intel Core i7-9750HF CPU @ 2.60GHz              | 1         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.53%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1         | 0.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1         | 0.53%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1         | 0.53%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 0.53%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.53%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 0.53%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 0.53%   |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 0.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 0.53%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 0.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 41        | 21.93%  |
| Intel Core i5           | 34        | 18.18%  |
| Intel Core i3           | 22        | 11.76%  |
| AMD Ryzen 5             | 17        | 9.09%   |
| Intel Celeron           | 15        | 8.02%   |
| Intel Core 2 Duo        | 11        | 5.88%   |
| Intel Pentium           | 6         | 3.21%   |
| Intel Atom              | 6         | 3.21%   |
| AMD E1                  | 4         | 2.14%   |
| Other                   | 3         | 1.6%    |
| AMD Ryzen 7             | 3         | 1.6%    |
| Intel Pentium Dual-Core | 2         | 1.07%   |
| Intel Genuine           | 2         | 1.07%   |
| Intel Core 2 Quad       | 2         | 1.07%   |
| AMD E                   | 2         | 1.07%   |
| AMD A8                  | 2         | 1.07%   |
| AMD A4                  | 2         | 1.07%   |
| AMD A12                 | 2         | 1.07%   |
| Intel Xeon              | 1         | 0.53%   |
| Intel Pentium M         | 1         | 0.53%   |
| Intel Core m3           | 1         | 0.53%   |
| AMD Ryzen 3             | 1         | 0.53%   |
| AMD Phenom II X6        | 1         | 0.53%   |
| AMD Phenom II X2        | 1         | 0.53%   |
| AMD E2                  | 1         | 0.53%   |
| AMD C-70                | 1         | 0.53%   |
| AMD C-60                | 1         | 0.53%   |
| AMD Athlon II Neo       | 1         | 0.53%   |
| AMD A10                 | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 103       | 55.08%  |
| 4      | 62        | 33.16%  |
| 6      | 15        | 8.02%   |
| 8      | 4         | 2.14%   |
| 1      | 3         | 1.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 187       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 110       | 58.82%  |
| 1      | 77        | 41.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 182       | 97.33%  |
| 32-bit         | 3         | 1.6%    |
| Unknown        | 2         | 1.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 14.51%  |
| 0x306a9    | 17        | 8.81%   |
| 0x206a7    | 14        | 7.25%   |
| 0x806ea    | 12        | 6.22%   |
| 0x306c3    | 12        | 6.22%   |
| 0x6fd      | 7         | 3.63%   |
| 0x40651    | 7         | 3.63%   |
| 0x306d4    | 7         | 3.63%   |
| 0x1067a    | 7         | 3.63%   |
| 0x0810100b | 4         | 2.07%   |
| 0x05000119 | 4         | 2.07%   |
| 0x906ed    | 3         | 1.55%   |
| 0x706e5    | 3         | 1.55%   |
| 0x406e3    | 3         | 1.55%   |
| 0x30678    | 3         | 1.55%   |
| 0x106ca    | 3         | 1.55%   |
| 0x08108109 | 3         | 1.55%   |
| 0x0600611a | 3         | 1.55%   |
| 0x906ea    | 2         | 1.04%   |
| 0x806eb    | 2         | 1.04%   |
| 0x806e9    | 2         | 1.04%   |
| 0x806c1    | 2         | 1.04%   |
| 0x706a1    | 2         | 1.04%   |
| 0x6e8      | 2         | 1.04%   |
| 0x406c4    | 2         | 1.04%   |
| 0x106e5    | 2         | 1.04%   |
| 0x0a201005 | 2         | 1.04%   |
| 0x08600104 | 2         | 1.04%   |
| 0x0700010f | 2         | 1.04%   |
| 0x06006705 | 2         | 1.04%   |
| 0x06006704 | 2         | 1.04%   |
| 0xa0660    | 1         | 0.52%   |
| 0xa0653    | 1         | 0.52%   |
| 0x906ec    | 1         | 0.52%   |
| 0x806ec    | 1         | 0.52%   |
| 0x706a8    | 1         | 0.52%   |
| 0x6fa      | 1         | 0.52%   |
| 0x6d8      | 1         | 0.52%   |
| 0x506e3    | 1         | 0.52%   |
| 0x406c3    | 1         | 0.52%   |
| 0x206c2    | 1         | 0.52%   |
| 0x20655    | 1         | 0.52%   |
| 0x106c2    | 1         | 0.52%   |
| 0x106a5    | 1         | 0.52%   |
| 0x10676    | 1         | 0.52%   |
| 0x0a201204 | 1         | 0.52%   |
| 0x08701021 | 1         | 0.52%   |
| 0x08701013 | 1         | 0.52%   |
| 0x08608103 | 1         | 0.52%   |
| 0x08108102 | 1         | 0.52%   |
| 0x08101016 | 1         | 0.52%   |
| 0x08101007 | 1         | 0.52%   |
| 0x08101004 | 1         | 0.52%   |
| 0x07030105 | 1         | 0.52%   |
| 0x0500010d | 1         | 0.52%   |
| 0x03000027 | 1         | 0.52%   |
| 0x010000c8 | 1         | 0.52%   |
| 0x010000bf | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 15.51%  |
| Haswell       | 23        | 12.3%   |
| IvyBridge     | 19        | 10.16%  |
| SandyBridge   | 14        | 7.49%   |
| Penryn        | 8         | 4.28%   |
| Core          | 8         | 4.28%   |
| Excavator     | 7         | 3.74%   |
| Broadwell     | 7         | 3.74%   |
| Zen 2         | 6         | 3.21%   |
| Zen           | 6         | 3.21%   |
| Skylake       | 6         | 3.21%   |
| Silvermont    | 6         | 3.21%   |
| Bobcat        | 6         | 3.21%   |
| Zen+          | 5         | 2.67%   |
| CometLake     | 4         | 2.14%   |
| Bonnell       | 4         | 2.14%   |
| Zen 3         | 3         | 1.6%    |
| Westmere      | 3         | 1.6%    |
| P6            | 3         | 1.6%    |
| Nehalem       | 3         | 1.6%    |
| K10           | 3         | 1.6%    |
| IceLake       | 3         | 1.6%    |
| Goldmont plus | 3         | 1.6%    |
| TigerLake     | 2         | 1.07%   |
| Jaguar        | 2         | 1.07%   |
| Puma          | 1         | 0.53%   |
| K10 Llano     | 1         | 0.53%   |
| Goldmont      | 1         | 0.53%   |
| Unknown       | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 129       | 58.9%   |
| AMD              | 50        | 22.83%  |
| Nvidia           | 39        | 17.81%  |
| VIA Technologies | 1         | 0.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 5.73%   |
| Intel UHD Graphics 620                                                                   | 12        | 5.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 3.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 3.08%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 2.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 2.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 2.2%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.76%   |
| Intel HD Graphics 620                                                                    | 4         | 1.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.76%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.32%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.32%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.32%   |
| AMD Renoir                                                                               | 3         | 1.32%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.88%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.88%   |
| Intel HD Graphics 630                                                                    | 2         | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.88%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.88%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.88%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 0.88%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.44%   |
| Nvidia TU117M                                                                            | 1         | 0.44%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.44%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.44%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.44%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.44%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.44%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.44%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.44%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.44%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.44%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.44%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 0.44%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.44%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 100       | 53.19%  |
| 1 x AMD        | 38        | 20.21%  |
| Intel + Nvidia | 19        | 10.11%  |
| 1 x Nvidia     | 18        | 9.57%   |
| Intel + AMD    | 9         | 4.79%   |
| AMD + Nvidia   | 2         | 1.06%   |
| 2 x AMD        | 1         | 0.53%   |
| 1 x VIA        | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 159       | 84.13%  |
| Proprietary | 21        | 11.11%  |
| Unknown     | 9         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 59.49%  |
| 1.01-2.0   | 29        | 14.87%  |
| 0.01-0.5   | 26        | 13.33%  |
| 3.01-4.0   | 10        | 5.13%   |
| 0.51-1.0   | 9         | 4.62%   |
| 7.01-8.0   | 2         | 1.03%   |
| 5.01-6.0   | 2         | 1.03%   |
| 2.01-3.0   | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 30        | 15%     |
| BOE                     | 25        | 12.5%   |
| LG Display              | 24        | 12%     |
| Chimei Innolux          | 22        | 11%     |
| AU Optronics            | 19        | 9.5%    |
| Samsung Electronics     | 15        | 7.5%    |
| BenQ                    | 9         | 4.5%    |
| AOC                     | 9         | 4.5%    |
| Hewlett-Packard         | 8         | 4%      |
| Chi Mei Optoelectronics | 5         | 2.5%    |
| LG Electronics          | 4         | 2%      |
| Acer                    | 4         | 2%      |
| Apple                   | 3         | 1.5%    |
| Unknown (XXX)           | 2         | 1%      |
| Sharp                   | 2         | 1%      |
| PANDA                   | 2         | 1%      |
| LG Philips              | 2         | 1%      |
| InfoVision              | 2         | 1%      |
| Dell                    | 2         | 1%      |
| ASUSTek Computer        | 2         | 1%      |
| Toshiba                 | 1         | 0.5%    |
| TCL                     | 1         | 0.5%    |
| Sony                    | 1         | 0.5%    |
| SKY                     | 1         | 0.5%    |
| NEC Computers           | 1         | 0.5%    |
| Lenovo                  | 1         | 0.5%    |
| InnoLux Display         | 1         | 0.5%    |
| DMT                     | 1         | 0.5%    |
| CPT                     | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3         | 1.46%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 3         | 1.46%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                  | 3         | 1.46%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 2         | 0.97%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 2         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 0.97%   |
| LG Electronics LCD Monitor LG TV 1360x768                             | 2         | 0.97%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.97%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 2         | 0.97%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 2         | 0.97%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 2         | 0.97%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 2         | 0.97%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                  | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch       | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.97%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 0.97%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch         | 2         | 0.97%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 2         | 0.97%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 0.49%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.49%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.49%   |
| SKY TV-monitor SKY1202 1920x1080 885x498mm 40.0-inch                  | 1         | 0.49%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.49%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 304x228mm 15.0-inch   | 1         | 0.49%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch      | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5557 1920x1200 367x230mm 17.1-inch | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                  | 1         | 0.49%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 0.49%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.49%   |
| NEC Computers LCD1850E NEC65D1 1280x1024 359x287mm 18.1-inch          | 1         | 0.49%   |
| LG Philips LCD Monitor LPL2601 1280x800 286x179mm 13.3-inch           | 1         | 0.49%   |
| LG Philips LCD Monitor LPL0D01 1280x800 304x190mm 14.1-inch           | 1         | 0.49%   |
| LG Electronics LCD Monitor W2043 3520x1080                            | 1         | 0.49%   |
| LG Electronics LCD Monitor 2D HD LG TV                                | 1         | 0.49%   |
| LG Electronics LCD Monitor 23MP55                                     | 1         | 0.49%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD05BC 3840x2160 309x174mm 14.0-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD05B4 1920x1080 294x165mm 13.3-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD05AB 1920x1080 309x174mm 14.0-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD04F0 2560x1440 310x174mm 14.0-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch          | 1         | 0.49%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 78        | 40%     |
| 1920x1080 (FHD)    | 57        | 29.23%  |
| 1600x900 (HD+)     | 16        | 8.21%   |
| 1440x900 (WXGA+)   | 7         | 3.59%   |
| 1280x800 (WXGA)    | 7         | 3.59%   |
| 1360x768           | 6         | 3.08%   |
| 3840x2160 (4K)     | 5         | 2.56%   |
| 1024x768 (XGA)     | 4         | 2.05%   |
| 1280x1024 (SXGA)   | 3         | 1.54%   |
| 2560x1440 (QHD)    | 2         | 1.03%   |
| 1024x600           | 2         | 1.03%   |
| Unknown            | 2         | 1.03%   |
| 3520x1080          | 1         | 0.51%   |
| 2880x1800          | 1         | 0.51%   |
| 2646x1024          | 1         | 0.51%   |
| 2560x1600          | 1         | 0.51%   |
| 1920x1200 (WUXGA)  | 1         | 0.51%   |
| 1680x1050 (WSXGA+) | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 59        | 29.21%  |
| 18      | 22        | 10.89%  |
| 14      | 22        | 10.89%  |
| 13      | 22        | 10.89%  |
| 19      | 16        | 7.92%   |
| 21      | 9         | 4.46%   |
| 23      | 8         | 3.96%   |
| 17      | 7         | 3.47%   |
| 11      | 7         | 3.47%   |
| Unknown | 7         | 3.47%   |
| 12      | 5         | 2.48%   |
| 24      | 4         | 1.98%   |
| 20      | 4         | 1.98%   |
| 54      | 3         | 1.49%   |
| 31      | 2         | 0.99%   |
| 10      | 2         | 0.99%   |
| 40      | 1         | 0.5%    |
| 32      | 1         | 0.5%    |
| 27      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 95        | 47.74%  |
| 401-500     | 45        | 22.61%  |
| 201-300     | 22        | 11.06%  |
| 501-600     | 13        | 6.53%   |
| 351-400     | 10        | 5.03%   |
| Unknown     | 7         | 3.52%   |
| 1001-1500   | 3         | 1.51%   |
| 601-700     | 2         | 1.01%   |
| 801-900     | 1         | 0.5%    |
| 701-800     | 1         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 145       | 81.92%  |
| 16/10   | 17        | 9.6%    |
| Unknown | 7         | 3.95%   |
| 4/3     | 4         | 2.26%   |
| 5/4     | 3         | 1.69%   |
| 3/2     | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 28.71%  |
| 81-90          | 38        | 18.81%  |
| 151-200        | 23        | 11.39%  |
| 141-150        | 21        | 10.4%   |
| 201-250        | 18        | 8.91%   |
| 51-60          | 7         | 3.47%   |
| Unknown        | 7         | 3.47%   |
| 71-80          | 6         | 2.97%   |
| 61-70          | 5         | 2.48%   |
| 121-130        | 5         | 2.48%   |
| More than 1000 | 3         | 1.49%   |
| 351-500        | 3         | 1.49%   |
| 41-50          | 2         | 0.99%   |
| 131-140        | 2         | 0.99%   |
| 301-350        | 1         | 0.5%    |
| 251-300        | 1         | 0.5%    |
| 501-1000       | 1         | 0.5%    |
| 91-100         | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 70        | 35.71%  |
| 51-100        | 58        | 29.59%  |
| 121-160       | 47        | 23.98%  |
| 161-240       | 7         | 3.57%   |
| Unknown       | 7         | 3.57%   |
| 1-50          | 5         | 2.55%   |
| More than 240 | 2         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 156       | 81.25%  |
| 2     | 29        | 15.1%   |
| 0     | 6         | 3.13%   |
| 3     | 1         | 0.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 114       | 41.61%  |
| Intel                           | 59        | 21.53%  |
| Qualcomm Atheros                | 47        | 17.15%  |
| Broadcom                        | 19        | 6.93%   |
| Ralink Technology               | 6         | 2.19%   |
| Ralink                          | 6         | 2.19%   |
| Marvell Technology Group        | 5         | 1.82%   |
| TP-Link                         | 4         | 1.46%   |
| Broadcom Limited                | 3         | 1.09%   |
| Xiaomi                          | 2         | 0.73%   |
| Qualcomm Atheros Communications | 2         | 0.73%   |
| D-Link System                   | 2         | 0.73%   |
| VIA Technologies                | 1         | 0.36%   |
| Samsung Electronics             | 1         | 0.36%   |
| MediaTek                        | 1         | 0.36%   |
| Hewlett-Packard                 | 1         | 0.36%   |
| Arduino SA                      | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 22.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 9.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 3.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.89%   |
| Intel Wireless 3160                                               | 5         | 1.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.58%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 1.26%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.95%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3         | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.95%   |
| Intel Wireless 8260                                               | 3         | 0.95%   |
| Intel Wireless 7260                                               | 3         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.95%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.63%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                              | 2         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.63%   |
| Intel Wireless 7265                                               | 2         | 0.63%   |
| Intel Wireless 3165                                               | 2         | 0.63%   |
| Intel WiFi Link 5100                                              | 2         | 0.63%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.63%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.63%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.63%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.32%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.32%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.32%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.32%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.32%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 0.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 32.67%  |
| Qualcomm Atheros                | 36        | 24%     |
| Realtek Semiconductor           | 33        | 22%     |
| Broadcom                        | 13        | 8.67%   |
| Ralink Technology               | 6         | 4%      |
| Ralink                          | 6         | 4%      |
| TP-Link                         | 3         | 2%      |
| Qualcomm Atheros Communications | 2         | 1.33%   |
| MediaTek                        | 1         | 0.67%   |
| Broadcom Limited                | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 10        | 6.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 9         | 5.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 8         | 5.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 6         | 3.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 6         | 3.97%   |
| Intel Wireless 3160                                                                           | 5         | 3.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 5         | 3.31%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 4         | 2.65%   |
| Intel Wireless 8265 / 8275                                                                    | 4         | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 1.99%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3         | 1.99%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 3         | 1.99%   |
| Intel Wireless 8260                                                                           | 3         | 1.99%   |
| Intel Wireless 7260                                                                           | 3         | 1.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 1.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 3         | 1.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 3         | 1.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 1.32%   |
| Ralink MT7601U Wireless Adapter                                                               | 2         | 1.32%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2         | 1.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2         | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.32%   |
| Intel Wireless 7265                                                                           | 2         | 1.32%   |
| Intel Wireless 3165                                                                           | 2         | 1.32%   |
| Intel WiFi Link 5100                                                                          | 2         | 1.32%   |
| Intel Wi-Fi 6 AX200                                                                           | 2         | 1.32%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 2         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 1.32%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                   | 2         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1         | 0.66%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 0.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.66%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1         | 0.66%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 0.66%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.66%   |
| Realtek 802.11ac NIC                                                                          | 1         | 0.66%   |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 0.66%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1         | 0.66%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                                                  | 1         | 0.66%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 0.66%   |
| Intel Wireless-AC 9260                                                                        | 1         | 0.66%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 0.66%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 0.66%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                                     | 1         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 0.66%   |
| Intel Centrino Wireless-N 2200                                                                | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 106       | 65.03%  |
| Intel                    | 19        | 11.66%  |
| Qualcomm Atheros         | 16        | 9.82%   |
| Broadcom                 | 8         | 4.91%   |
| Marvell Technology Group | 5         | 3.07%   |
| Xiaomi                   | 2         | 1.23%   |
| D-Link System            | 2         | 1.23%   |
| Broadcom Limited         | 2         | 1.23%   |
| VIA Technologies         | 1         | 0.61%   |
| TP-Link                  | 1         | 0.61%   |
| Samsung Electronics      | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 43.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 18.4%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.84%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.84%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 1.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.23%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.23%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.23%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.61%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.61%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.61%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.61%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.61%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.61%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.61%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.61%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.61%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.61%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1         | 0.61%   |
| Broadcom Limited NetXtreme BCM5751M Gigabit Ethernet PCI Express  | 1         | 0.61%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 158       | 51.63%  |
| WiFi     | 145       | 47.39%  |
| Modem    | 3         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 59.79%  |
| Ethernet | 76        | 40.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 104       | 55.61%  |
| 1     | 80        | 42.78%  |
| 0     | 2         | 1.07%   |
| 3     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 164       | 85.86%  |
| Yes  | 27        | 14.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 31.78%  |
| Realtek Semiconductor           | 17        | 15.89%  |
| Qualcomm Atheros Communications | 14        | 13.08%  |
| Foxconn / Hon Hai               | 8         | 7.48%   |
| Cambridge Silicon Radio         | 7         | 6.54%   |
| IMC Networks                    | 5         | 4.67%   |
| Broadcom                        | 5         | 4.67%   |
| Lite-On Technology              | 4         | 3.74%   |
| Toshiba                         | 3         | 2.8%    |
| Ralink Technology               | 2         | 1.87%   |
| Ralink                          | 2         | 1.87%   |
| Apple                           | 2         | 1.87%   |
| Hewlett-Packard                 | 1         | 0.93%   |
| Foxconn International           | 1         | 0.93%   |
| D-Link System                   | 1         | 0.93%   |
| Alps Electric                   | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19        | 17.76%  |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 8.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 8.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 6.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 6.54%   |
| Realtek Bluetooth Radio                             | 6         | 5.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 4.67%   |
| Toshiba Bluetooth Device                            | 3         | 2.8%    |
| Intel Bluetooth Device                              | 3         | 2.8%    |
| IMC Networks Bluetooth Radio                        | 3         | 2.8%    |
| Ralink RT3290 Bluetooth                             | 2         | 1.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.87%   |
| Lite-On Bluetooth Device                            | 2         | 1.87%   |
| Intel AX200 Bluetooth                               | 2         | 1.87%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 1.87%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.93%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.93%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.93%   |
| Ralink CSR BS8510                                   | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.93%   |
| Lite-On Wireless_Device                             | 1         | 0.93%   |
| Lite-On Bluetooth Radio                             | 1         | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.93%   |
| IMC Networks Bluetooth Device                       | 1         | 0.93%   |
| IMC Networks BCM20702A0                             | 1         | 0.93%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.93%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.93%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.93%   |
| D-Link System DBT-122 Bluetooth                     | 1         | 0.93%   |
| Broadcom HP Portable Valentine                      | 1         | 0.93%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.93%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.93%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.93%   |
| Apple Bluetooth Host Controller                     | 1         | 0.93%   |
| Apple Bluetooth HCI                                 | 1         | 0.93%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 145       | 65.61%  |
| AMD                 | 47        | 21.27%  |
| Nvidia              | 25        | 11.31%  |
| VIA Technologies    | 1         | 0.45%   |
| Focusrite-Novation  | 1         | 0.45%   |
| Corsair             | 1         | 0.45%   |
| C-Media Electronics | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 7.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 6.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.73%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 5.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 4.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 3.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 3.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.51%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.51%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 2.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.79%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.43%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 1.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.72%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.72%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.36%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.36%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.36%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.36%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.36%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series LPE Audio Controller                                    | 1         | 0.36%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.36%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 25%     |
| Kingston            | 20        | 18.52%  |
| SK hynix            | 17        | 15.74%  |
| Unknown             | 11        | 10.19%  |
| Micron Technology   | 10        | 9.26%   |
| Ramaxel Technology  | 5         | 4.63%   |
| A-DATA Technology   | 4         | 3.7%    |
| Crucial             | 3         | 2.78%   |
| Corsair             | 3         | 2.78%   |
| Nanya Technology    | 2         | 1.85%   |
| Unknown (ABCD)      | 1         | 0.93%   |
| Team                | 1         | 0.93%   |
| PNY                 | 1         | 0.93%   |
| Goodram             | 1         | 0.93%   |
| Elpida              | 1         | 0.93%   |
| Avant               | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 4         | 3.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.71%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s             | 2         | 1.71%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s             | 2         | 1.71%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.71%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s             | 2         | 1.71%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                           | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.85%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1         | 0.85%   |
| Unknown RAM Module 1GB DIMM DDR2                                    | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                            | 1         | 0.85%   |
| Unknown RAM Module 1024MB DIMM 1333MT/s                             | 1         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.85%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s               | 1         | 0.85%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.85%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| SK hynix RAM H9HCNNNBKMMLXR-NEE 1024MB LPDDR4 3733MT/s              | 1         | 0.85%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 0.85%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.85%   |
| Samsung RAM M471B5273CH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.85%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 1         | 0.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.85%   |
| Samsung RAM M471A5244BB0-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.85%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.85%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.85%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.85%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s               | 1         | 0.85%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s              | 1         | 0.85%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 37        | 42.53%  |
| DDR3    | 34        | 39.08%  |
| DDR2    | 6         | 6.9%    |
| SDRAM   | 3         | 3.45%   |
| LPDDR4  | 3         | 3.45%   |
| LPDDR3  | 2         | 2.3%    |
| Unknown | 2         | 2.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 69.41%  |
| DIMM         | 21        | 24.71%  |
| Row Of Chips | 3         | 3.53%   |
| Chip         | 1         | 1.18%   |
| Unknown      | 1         | 1.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 39        | 39.8%   |
| 8192  | 29        | 29.59%  |
| 2048  | 14        | 14.29%  |
| 16384 | 9         | 9.18%   |
| 1024  | 6         | 6.12%   |
| 32768 | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 23        | 22.77%  |
| 2667    | 22        | 21.78%  |
| 1333    | 10        | 9.9%    |
| 3200    | 6         | 5.94%   |
| 2400    | 6         | 5.94%   |
| 1334    | 5         | 4.95%   |
| 3266    | 4         | 3.96%   |
| Unknown | 4         | 3.96%   |
| 2133    | 3         | 2.97%   |
| 4199    | 2         | 1.98%   |
| 3466    | 2         | 1.98%   |
| 800     | 2         | 1.98%   |
| 667     | 2         | 1.98%   |
| 8400    | 1         | 0.99%   |
| 3733    | 1         | 0.99%   |
| 3600    | 1         | 0.99%   |
| 3533    | 1         | 0.99%   |
| 2933    | 1         | 0.99%   |
| 1867    | 1         | 0.99%   |
| 1866    | 1         | 0.99%   |
| 1066    | 1         | 0.99%   |
| 975     | 1         | 0.99%   |
| 933     | 1         | 0.99%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Seiko Epson         | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Prolific Technology | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L3110 Series           | 1         | 20%     |
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| Prolific PL2305 Parallel Port      | 1         | 20%     |
| HP Ink Tank Wireless 410 series    | 1         | 20%     |
| HP Deskjet 2050 J510               | 1         | 20%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26        | 19.55%  |
| IMC Networks                           | 19        | 14.29%  |
| Microdia                               | 11        | 8.27%   |
| Realtek Semiconductor                  | 9         | 6.77%   |
| Quanta                                 | 9         | 6.77%   |
| Syntek                                 | 7         | 5.26%   |
| Suyin                                  | 7         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.76%   |
| Sunplus Innovation Technology          | 4         | 3.01%   |
| Lite-On Technology                     | 4         | 3.01%   |
| Ricoh                                  | 3         | 2.26%   |
| Generalplus Technology                 | 3         | 2.26%   |
| Alcor Micro                            | 3         | 2.26%   |
| Silicon Motion                         | 2         | 1.5%    |
| Pixart Imaging                         | 2         | 1.5%    |
| OmniVision Technologies                | 2         | 1.5%    |
| Logitech                               | 2         | 1.5%    |
| KYE Systems (Mouse Systems)            | 2         | 1.5%    |
| Apple                                  | 2         | 1.5%    |
| Acer                                   | 2         | 1.5%    |
| Samsung Electronics                    | 1         | 0.75%   |
| Lenovo                                 | 1         | 0.75%   |
| Jieli Technology                       | 1         | 0.75%   |
| Importek                               | 1         | 0.75%   |
| Genesys Logic                          | 1         | 0.75%   |
| GEMBIRD                                | 1         | 0.75%   |
| Foxconn / Hon Hai                      | 1         | 0.75%   |
| Arkmicro Technologies                  | 1         | 0.75%   |
| ALi                                    | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 5         | 3.76%   |
| IMC Networks Integrated Camera                      | 5         | 3.76%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 3.01%   |
| IMC Networks TOSHIBA Web Camera - HD                | 3         | 2.26%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 2.26%   |
| Chicony Integrated Camera                           | 3         | 2.26%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.5%    |
| Syntek Integrated Camera                            | 2         | 1.5%    |
| Syntek EasyCamera                                   | 2         | 1.5%    |
| Suyin Integrated_Webcam_HD                          | 2         | 1.5%    |
| Suyin HP Truevision HD                              | 2         | 1.5%    |
| Suyin HD WebCam                                     | 2         | 1.5%    |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.5%    |
| Realtek Integrated_Webcam_HD                        | 2         | 1.5%    |
| Realtek Integrated Webcam                           | 2         | 1.5%    |
| Realtek HD WebCam                                   | 2         | 1.5%    |
| Quanta HP Webcam-50                                 | 2         | 1.5%    |
| Quanta HP Webcam                                    | 2         | 1.5%    |
| OmniVision OV2640 Webcam                            | 2         | 1.5%    |
| Microdia Camera                                     | 2         | 1.5%    |
| Logitech Webcam C270                                | 2         | 1.5%    |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 1.5%    |
| Lite-On HP TrueVision HD Camera                     | 2         | 1.5%    |
| IMC Networks VGA UVC WebCam                         | 2         | 1.5%    |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.5%    |
| Chicony HP TrueVision HD                            | 2         | 1.5%    |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1.5%    |
| Chicony HD User Facing                              | 2         | 1.5%    |
| Chicony EasyCamera                                  | 2         | 1.5%    |
| Syntek USB Video Device                             | 1         | 0.75%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.75%   |
| Sunplus HP TrueVision HD Camera                     | 1         | 0.75%   |
| Sunplus HD WebCam                                   | 1         | 0.75%   |
| Silicon Motion WebCam SC-10HDP12631N                | 1         | 0.75%   |
| Silicon Motion Web Camera                           | 1         | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.75%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 1         | 0.75%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 0.75%   |
| Ricoh Integrated_Webcam_1.3M                        | 1         | 0.75%   |
| Realtek Integrated Webcam HD                        | 1         | 0.75%   |
| Realtek HP Truevision HD                            | 1         | 0.75%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.75%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 0.75%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 0.75%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.75%   |
| Quanta HP TrueVision HD Webcam                      | 1         | 0.75%   |
| Quanta HP TrueVision HD Camera                      | 1         | 0.75%   |
| Pixart Imaging Webcam Genius iLook 300              | 1         | 0.75%   |
| Pixart Imaging Multimedia audio controller          | 1         | 0.75%   |
| Microdia Webcam Vitade AF                           | 1         | 0.75%   |
| Microdia Sony Visual Communication Camera           | 1         | 0.75%   |
| Microdia Rapoo camera                               | 1         | 0.75%   |
| Microdia Integrated Webcam                          | 1         | 0.75%   |
| Lenovo Integrated Webcam                            | 1         | 0.75%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera          | 1         | 0.75%   |
| KYE Systems (Mouse Systems) FaceCam 310             | 1         | 0.75%   |
| Jieli USB PHY 2.0                                   | 1         | 0.75%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 0.75%   |
| IMC Networks XHC Camera                             | 1         | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 23.08%  |
| Synaptics             | 3         | 23.08%  |
| AuthenTec             | 3         | 23.08%  |
| Upek                  | 1         | 7.69%   |
| STMicroelectronics    | 1         | 7.69%   |
| LighTuning Technology | 1         | 7.69%   |
| Elan Microelectronics | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics  WBDI                                        | 2         | 15.38%  |
| AuthenTec AES1600                                      | 2         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 7.69%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 7.69%   |
| LighTuning Fingerprint Sensor                          | 1         | 7.69%   |
| Elan ELAN:Fingerprint                                  | 1         | 7.69%   |
| AuthenTec AES2810                                      | 1         | 7.69%   |
| Unknown                                                | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| O2 Micro | 2         | 50%     |
| Upek     | 1         | 25%     |
| Broadcom | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 25%     |
| O2 Micro Oz776 SmartCard Reader                            | 1         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 25%     |
| Broadcom 5880                                              | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 147       | 77.37%  |
| 1     | 37        | 19.47%  |
| 2     | 6         | 3.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 28.57%  |
| Fingerprint reader       | 13        | 26.53%  |
| Net/wireless             | 9         | 18.37%  |
| Chipcard                 | 4         | 8.16%   |
| Multimedia controller    | 3         | 6.12%   |
| Communication controller | 2         | 4.08%   |
| Bluetooth                | 2         | 4.08%   |
| Storage                  | 1         | 2.04%   |
| Sound                    | 1         | 2.04%   |


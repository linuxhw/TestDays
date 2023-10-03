MX - Tested Hardware & Statistics
---------------------------------

A project to collect tested hardware configurations for MX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX/Desktop/README.md) and [notebooks](/Dist/MX/Notebook/README.md).

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

Total: 928

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu Si... | AMILO A1650G                | Notebook    | [ec61a60044](https://linux-hardware.org/?probe=ec61a60044) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4a6090c2f4](https://linux-hardware.org/?probe=4a6090c2f4) | Sep 29, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [ee6e1996b9](https://linux-hardware.org/?probe=ee6e1996b9) | Sep 29, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [3c87964524](https://linux-hardware.org/?probe=3c87964524) | Sep 28, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | Notebook    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |
| MSI           | G41M4                       | Desktop     | [0554e9757f](https://linux-hardware.org/?probe=0554e9757f) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4054ad9d77](https://linux-hardware.org/?probe=4054ad9d77) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [76d936bb5b](https://linux-hardware.org/?probe=76d936bb5b) | Sep 26, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [55dec782e7](https://linux-hardware.org/?probe=55dec782e7) | Sep 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [0c1f872edb](https://linux-hardware.org/?probe=0c1f872edb) | Sep 23, 2023 |
| Dell          | Precision 5570              | Notebook    | [27b003d343](https://linux-hardware.org/?probe=27b003d343) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c00e994c2c](https://linux-hardware.org/?probe=c00e994c2c) | Sep 21, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [0ad032f320](https://linux-hardware.org/?probe=0ad032f320) | Sep 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [0a698044d8](https://linux-hardware.org/?probe=0a698044d8) | Sep 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9e9652809d](https://linux-hardware.org/?probe=9e9652809d) | Sep 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d66a3d9329](https://linux-hardware.org/?probe=d66a3d9329) | Sep 18, 2023 |
| Dell          | Latitude D620               | Notebook    | [65d2f56829](https://linux-hardware.org/?probe=65d2f56829) | Sep 18, 2023 |
| HP            | Pavilion dv2                | Notebook    | [ee227b3d35](https://linux-hardware.org/?probe=ee227b3d35) | Sep 16, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [82cae5303a](https://linux-hardware.org/?probe=82cae5303a) | Sep 16, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [db874f0737](https://linux-hardware.org/?probe=db874f0737) | Sep 16, 2023 |
| ASUSTek       | K54L                        | Notebook    | [4b62e4c882](https://linux-hardware.org/?probe=4b62e4c882) | Sep 15, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [fcfde3095d](https://linux-hardware.org/?probe=fcfde3095d) | Sep 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a03ec42023](https://linux-hardware.org/?probe=a03ec42023) | Sep 12, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [e83ef4efd8](https://linux-hardware.org/?probe=e83ef4efd8) | Sep 11, 2023 |
| HP            | 620                         | Notebook    | [6fd1497e1a](https://linux-hardware.org/?probe=6fd1497e1a) | Sep 10, 2023 |
| Lenovo        | ThinkPad L580 20LW000VFR    | Notebook    | [a7dfc5e0f5](https://linux-hardware.org/?probe=a7dfc5e0f5) | Sep 09, 2023 |
| Lenovo        | ThinkPad L580 20LW000VFR    | Notebook    | [e224a5dc53](https://linux-hardware.org/?probe=e224a5dc53) | Sep 09, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [b906e23303](https://linux-hardware.org/?probe=b906e23303) | Sep 08, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [318f1010b6](https://linux-hardware.org/?probe=318f1010b6) | Sep 08, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [d72c4b5cce](https://linux-hardware.org/?probe=d72c4b5cce) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7be68f9c9a](https://linux-hardware.org/?probe=7be68f9c9a) | Sep 06, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [baad816533](https://linux-hardware.org/?probe=baad816533) | Sep 05, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [a9fdf4f92b](https://linux-hardware.org/?probe=a9fdf4f92b) | Sep 03, 2023 |
| ASRock        | J4205-ITX                   | Desktop     | [8831793b97](https://linux-hardware.org/?probe=8831793b97) | Sep 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [af96cda252](https://linux-hardware.org/?probe=af96cda252) | Sep 02, 2023 |
| Foxconn       | 2A92                        | Desktop     | [50ca8342d7](https://linux-hardware.org/?probe=50ca8342d7) | Sep 01, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9d8f7c345f](https://linux-hardware.org/?probe=9d8f7c345f) | Sep 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2e3c70287a](https://linux-hardware.org/?probe=2e3c70287a) | Aug 30, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [51ea627e30](https://linux-hardware.org/?probe=51ea627e30) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c8e9f89359](https://linux-hardware.org/?probe=c8e9f89359) | Aug 25, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fcb0ac31fe](https://linux-hardware.org/?probe=fcb0ac31fe) | Aug 23, 2023 |
| Dell          | Latitude 3190               | Notebook    | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [c6f294e543](https://linux-hardware.org/?probe=c6f294e543) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [d6e0b89f34](https://linux-hardware.org/?probe=d6e0b89f34) | Aug 21, 2023 |
| Biostar       | H310MHC2                    | Desktop     | [12f3b0d269](https://linux-hardware.org/?probe=12f3b0d269) | Aug 20, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [768e7b97fc](https://linux-hardware.org/?probe=768e7b97fc) | Aug 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [27d598d911](https://linux-hardware.org/?probe=27d598d911) | Aug 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [e5661bef5b](https://linux-hardware.org/?probe=e5661bef5b) | Aug 16, 2023 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [f059d25382](https://linux-hardware.org/?probe=f059d25382) | Aug 14, 2023 |
| Beelink       | Gemini X                    | Notebook    | [d5c4e54794](https://linux-hardware.org/?probe=d5c4e54794) | Aug 14, 2023 |
| Dell          | Latitude E5410              | Notebook    | [4ae8d448a2](https://linux-hardware.org/?probe=4ae8d448a2) | Aug 14, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [b422d7c8cc](https://linux-hardware.org/?probe=b422d7c8cc) | Aug 12, 2023 |
| Toshiba       | Satellite T110              | Notebook    | [8180105119](https://linux-hardware.org/?probe=8180105119) | Aug 11, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [69123aa283](https://linux-hardware.org/?probe=69123aa283) | Aug 10, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [9c28979b9d](https://linux-hardware.org/?probe=9c28979b9d) | Aug 10, 2023 |
| Dell          | Latitude E6540              | Notebook    | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [11f3b9cfad](https://linux-hardware.org/?probe=11f3b9cfad) | Aug 08, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [f30c6c7bb5](https://linux-hardware.org/?probe=f30c6c7bb5) | Aug 08, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [c7a3dd2647](https://linux-hardware.org/?probe=c7a3dd2647) | Aug 07, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [ed6fdbd235](https://linux-hardware.org/?probe=ed6fdbd235) | Aug 07, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5777798e8f](https://linux-hardware.org/?probe=5777798e8f) | Aug 07, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [44556227ff](https://linux-hardware.org/?probe=44556227ff) | Aug 05, 2023 |
| ASUSTek       | ProArt StudioBook W5600Q... | Notebook    | [96211a5c87](https://linux-hardware.org/?probe=96211a5c87) | Aug 05, 2023 |
| OEM           | Intel H81                   | Desktop     | [82606b5050](https://linux-hardware.org/?probe=82606b5050) | Aug 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Dell          | Latitude E6320              | Notebook    | [9b42be4945](https://linux-hardware.org/?probe=9b42be4945) | Aug 02, 2023 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [c7e057da76](https://linux-hardware.org/?probe=c7e057da76) | Aug 02, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a0270160ad](https://linux-hardware.org/?probe=a0270160ad) | Aug 02, 2023 |
| HP            | 620                         | Notebook    | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| Lenovo        | 3000 C100 07612GU           | Notebook    | [3941ecc4f2](https://linux-hardware.org/?probe=3941ecc4f2) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [f84a39b436](https://linux-hardware.org/?probe=f84a39b436) | Jul 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| Intel         | JSL MRD                     | Desktop     | [feb19ee725](https://linux-hardware.org/?probe=feb19ee725) | Jul 29, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ca5990cfa3](https://linux-hardware.org/?probe=ca5990cfa3) | Jul 29, 2023 |
| Dell          | Latitude 5340               | Notebook    | [5ab5c25167](https://linux-hardware.org/?probe=5ab5c25167) | Jul 28, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [bb2046286f](https://linux-hardware.org/?probe=bb2046286f) | Jul 26, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [6ced09890f](https://linux-hardware.org/?probe=6ced09890f) | Jul 26, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d10701a88b](https://linux-hardware.org/?probe=d10701a88b) | Jul 22, 2023 |
| Dell          | Latitude 3510               | Notebook    | [e1eb8b885c](https://linux-hardware.org/?probe=e1eb8b885c) | Jul 21, 2023 |
| Dell          | Latitude 5530               | Notebook    | [235731a6f1](https://linux-hardware.org/?probe=235731a6f1) | Jul 20, 2023 |
| Dell          | Latitude 5310               | Notebook    | [5b81040709](https://linux-hardware.org/?probe=5b81040709) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| CONNEX        | L1415-BAY                   | Notebook    | [8f5663e9c8](https://linux-hardware.org/?probe=8f5663e9c8) | Jul 18, 2023 |
| ASRock        | B660M-HDV                   | Desktop     | [3a0685bcf0](https://linux-hardware.org/?probe=3a0685bcf0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| Dell          | Precision 5510              | Notebook    | [ff4ea6ba94](https://linux-hardware.org/?probe=ff4ea6ba94) | Jul 17, 2023 |
| Sony          | VGN-S3HP                    | Notebook    | [6e2c92c447](https://linux-hardware.org/?probe=6e2c92c447) | Jul 17, 2023 |
| Dell          | Latitude 5530               | Notebook    | [37681b3327](https://linux-hardware.org/?probe=37681b3327) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| Dell          | Precision 3571              | Notebook    | [2123567cb0](https://linux-hardware.org/?probe=2123567cb0) | Jul 16, 2023 |
| Dell          | System XPS L502X            | Notebook    | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| Acer          | Aspire ES1-511              | Notebook    | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| Medion        | MS-7667                     | Desktop     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| HP            | 620                         | Notebook    | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| AOpen         | D1009 A1A4                  | Desktop     | [2819e086aa](https://linux-hardware.org/?probe=2819e086aa) | Jul 02, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [d04862302e](https://linux-hardware.org/?probe=d04862302e) | Jul 01, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4540c6370](https://linux-hardware.org/?probe=f4540c6370) | Jun 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [cadc656340](https://linux-hardware.org/?probe=cadc656340) | Jun 25, 2023 |
| HP            | Spectre Folio Convertibl... | Convertible | [123d2215a1](https://linux-hardware.org/?probe=123d2215a1) | Jun 25, 2023 |
| Dell          | Latitude E6510              | Notebook    | [a85838194d](https://linux-hardware.org/?probe=a85838194d) | Jun 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ed43d5454c](https://linux-hardware.org/?probe=ed43d5454c) | Jun 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [56c650c8b1](https://linux-hardware.org/?probe=56c650c8b1) | Jun 15, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | Notebook    | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [4c56663011](https://linux-hardware.org/?probe=4c56663011) | Jun 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Dell          | Latitude E6510              | Notebook    | [49743c8db7](https://linux-hardware.org/?probe=49743c8db7) | Jun 04, 2023 |
| Dell          | Latitude E6510              | Notebook    | [51c45b0aa7](https://linux-hardware.org/?probe=51c45b0aa7) | Jun 04, 2023 |
| MSI           | U200                        | Notebook    | [01900b8117](https://linux-hardware.org/?probe=01900b8117) | Jun 04, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [f47c68a2a7](https://linux-hardware.org/?probe=f47c68a2a7) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [51d10ac11e](https://linux-hardware.org/?probe=51d10ac11e) | Jun 02, 2023 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [c64fbbcad9](https://linux-hardware.org/?probe=c64fbbcad9) | Jun 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [c46684adac](https://linux-hardware.org/?probe=c46684adac) | Jun 02, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| Dell          | Latitude 5540               | Notebook    | [98ec8ec8bf](https://linux-hardware.org/?probe=98ec8ec8bf) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Dell          | Latitude E6510              | Notebook    | [9edaeb2ffa](https://linux-hardware.org/?probe=9edaeb2ffa) | May 25, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Dell          | Latitude E6510              | Notebook    | [342b8d094e](https://linux-hardware.org/?probe=342b8d094e) | May 20, 2023 |
| Dell          | Latitude E6510              | Notebook    | [4d606396f8](https://linux-hardware.org/?probe=4d606396f8) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e6746606b4](https://linux-hardware.org/?probe=e6746606b4) | May 19, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [58066198c4](https://linux-hardware.org/?probe=58066198c4) | May 18, 2023 |
| Dell          | Latitude 3190               | Notebook    | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [4c33c99aab](https://linux-hardware.org/?probe=4c33c99aab) | May 14, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3bc96663a8](https://linux-hardware.org/?probe=3bc96663a8) | May 14, 2023 |
| ASUSTek       | X202E                       | Notebook    | [d6b7617a17](https://linux-hardware.org/?probe=d6b7617a17) | May 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [08afd40365](https://linux-hardware.org/?probe=08afd40365) | May 13, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | Notebook    | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [f894b9a2c4](https://linux-hardware.org/?probe=f894b9a2c4) | May 07, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| HP            | Pro Tablet 10 EE G1         | Notebook    | [6af53fb237](https://linux-hardware.org/?probe=6af53fb237) | May 05, 2023 |
| Lenovo        | ThinkPad T460s 20F9003GU... | Notebook    | [7a570efe74](https://linux-hardware.org/?probe=7a570efe74) | May 05, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [8349b363f4](https://linux-hardware.org/?probe=8349b363f4) | May 03, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [49971d9c29](https://linux-hardware.org/?probe=49971d9c29) | May 03, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| Lenovo        | ThinkPad X260 20F5S89L02    | Notebook    | [4e2f57ccc3](https://linux-hardware.org/?probe=4e2f57ccc3) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [a36c4e671d](https://linux-hardware.org/?probe=a36c4e671d) | May 02, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [2d1086090c](https://linux-hardware.org/?probe=2d1086090c) | May 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | G42                         | Notebook    | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | 090Ch                       | Desktop     | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | Desktop     | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| Compal        | HEL81I                      | Notebook    | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Google        | Akali 360                   | Notebook    | [2d18714bb2](https://linux-hardware.org/?probe=2d18714bb2) | Apr 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | Notebook    | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [843dd1e105](https://linux-hardware.org/?probe=843dd1e105) | Apr 18, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [c271ba95b9](https://linux-hardware.org/?probe=c271ba95b9) | Apr 16, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [494fc3e648](https://linux-hardware.org/?probe=494fc3e648) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [3d53b9ee9e](https://linux-hardware.org/?probe=3d53b9ee9e) | Apr 12, 2023 |
| HP            | 3646h                       | Desktop     | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c2a70674ac](https://linux-hardware.org/?probe=c2a70674ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4290WC7       | Notebook    | [07ed4faaa0](https://linux-hardware.org/?probe=07ed4faaa0) | Apr 10, 2023 |
| HP            | 18E5                        | Desktop     | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9a5c9ee256](https://linux-hardware.org/?probe=9a5c9ee256) | Apr 02, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| HP            | 3029h                       | Desktop     | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [498bb39808](https://linux-hardware.org/?probe=498bb39808) | Mar 24, 2023 |
| Unknown       | GB01                        | Desktop     | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 3048h                       | Desktop     | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [978df2886a](https://linux-hardware.org/?probe=978df2886a) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Samsung       | 950QDB                      | Convertible | [e16175f1c5](https://linux-hardware.org/?probe=e16175f1c5) | Mar 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9f3f315f73](https://linux-hardware.org/?probe=9f3f315f73) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [42653f8c2a](https://linux-hardware.org/?probe=42653f8c2a) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | Desktop     | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [7ccc0f584e](https://linux-hardware.org/?probe=7ccc0f584e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | Notebook    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [153652da71](https://linux-hardware.org/?probe=153652da71) | Mar 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 255 G3                      | Notebook    | [9ccab85062](https://linux-hardware.org/?probe=9ccab85062) | Mar 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a84948f124](https://linux-hardware.org/?probe=a84948f124) | Mar 04, 2023 |
| HP            | 8184 X4                     | Desktop     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5718d685e4](https://linux-hardware.org/?probe=5718d685e4) | Mar 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5fe3c354ff](https://linux-hardware.org/?probe=5fe3c354ff) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a15227fc75](https://linux-hardware.org/?probe=a15227fc75) | Mar 02, 2023 |
| Dell          | Latitude 3190               | Notebook    | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | 255 G3                      | Notebook    | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [b6321ee5a4](https://linux-hardware.org/?probe=b6321ee5a4) | Feb 25, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [efc95d4697](https://linux-hardware.org/?probe=efc95d4697) | Feb 25, 2023 |
| Unknown       | 1.0                         | Desktop     | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| Positivo      | POS-PQ45AU POSITIVO         | Desktop     | [8ed6dacaa7](https://linux-hardware.org/?probe=8ed6dacaa7) | Feb 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | Notebook    | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [aba30bb2d8](https://linux-hardware.org/?probe=aba30bb2d8) | Feb 17, 2023 |
| RTD Embedd... | CMA34CR                     | Notebook    | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Linx          | LINX1010B                   | Notebook    | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [86103b5293](https://linux-hardware.org/?probe=86103b5293) | Feb 12, 2023 |
| Medion        | P6634                       | Notebook    | [ec0002869f](https://linux-hardware.org/?probe=ec0002869f) | Feb 11, 2023 |
| Medion        | P6634                       | Notebook    | [15c3260ecf](https://linux-hardware.org/?probe=15c3260ecf) | Feb 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [d32909e1a4](https://linux-hardware.org/?probe=d32909e1a4) | Feb 09, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [700f0ded17](https://linux-hardware.org/?probe=700f0ded17) | Feb 08, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b4c5f2e2de](https://linux-hardware.org/?probe=b4c5f2e2de) | Feb 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [e6f4812d50](https://linux-hardware.org/?probe=e6f4812d50) | Feb 07, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| HP            | 450                         | Notebook    | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a255954f75](https://linux-hardware.org/?probe=a255954f75) | Feb 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [7e94a2328d](https://linux-hardware.org/?probe=7e94a2328d) | Feb 05, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | Desktop     | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| HP            | 3396                        | Desktop     | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | Notebook    | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Toshiba       | Satellite M70               | Notebook    | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| HP            | 304Ah                       | Desktop     | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | Notebook    | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [6e930633c0](https://linux-hardware.org/?probe=6e930633c0) | Nov 18, 2022 |
| Dell          | 0J051K A00                  | Server      | [cb579ef51b](https://linux-hardware.org/?probe=cb579ef51b) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Latitude 7480               | Notebook    | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [732e924bbb](https://linux-hardware.org/?probe=732e924bbb) | Nov 07, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [9c72952af7](https://linux-hardware.org/?probe=9c72952af7) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | Notebook    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Vulcan Ele... | Excursion XB                | Notebook    | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Biostar       | H61MH                       | Desktop     | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [226e4471e1](https://linux-hardware.org/?probe=226e4471e1) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | Desktop     | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [59dabaff86](https://linux-hardware.org/?probe=59dabaff86) | Oct 23, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [c389b44ab5](https://linux-hardware.org/?probe=c389b44ab5) | Oct 21, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [b6c2cf5b2e](https://linux-hardware.org/?probe=b6c2cf5b2e) | Oct 17, 2022 |
| Dell          | Latitude 3190               | Notebook    | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1f6ff0e213](https://linux-hardware.org/?probe=1f6ff0e213) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| Pegatron      | NARRA3                      | Desktop     | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | Notebook    | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Lenovo        | ThinkPad T420 4236TL7       | Notebook    | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | Notebook    | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [bb43eb5333](https://linux-hardware.org/?probe=bb43eb5333) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f97d2b97ad](https://linux-hardware.org/?probe=f97d2b97ad) | Oct 01, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | Notebook    | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | Notebook    | [f8f2a6263a](https://linux-hardware.org/?probe=f8f2a6263a) | Sep 04, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | Notebook    | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [83e026f682](https://linux-hardware.org/?probe=83e026f682) | Aug 12, 2022 |
| Acer          | Extensa 5630                | Notebook    | [9ea053d8e8](https://linux-hardware.org/?probe=9ea053d8e8) | Aug 12, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | Notebook    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | Notebook    | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| MP            | MS-7848                     | Desktop     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| UMAX          | VisionBook-N12R             | Notebook    | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Dell          | 0DR845                      | Desktop     | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| Alienware     | 13 R2                       | Notebook    | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | Notebook    | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [77c632ea8e](https://linux-hardware.org/?probe=77c632ea8e) | Jul 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | Desktop     | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c21cd1f8f3](https://linux-hardware.org/?probe=c21cd1f8f3) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [03878be4ec](https://linux-hardware.org/?probe=03878be4ec) | Apr 20, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Gigabyte      | P35-DS3P                    | Desktop     | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Acer          | Extensa 5630                | Notebook    | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [ecc5ad7332](https://linux-hardware.org/?probe=ecc5ad7332) | Feb 25, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [d0ba3786b2](https://linux-hardware.org/?probe=d0ba3786b2) | Feb 03, 2022 |
| HP            | ProBook 6460b               | Notebook    | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Intel         | H81                         | Desktop     | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Acer          | Spin SP111-31               | Convertible | [21bfc2a904](https://linux-hardware.org/?probe=21bfc2a904) | Jan 16, 2022 |
| IBM           | 8183B2U                     | Desktop     | [d070680dfb](https://linux-hardware.org/?probe=d070680dfb) | Jan 14, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [52e09bab91](https://linux-hardware.org/?probe=52e09bab91) | Jan 02, 2022 |
| HP            | 2000                        | Notebook    | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Toshiba       | Satellite L850-CJK          | Notebook    | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | Unknown                     | Notebook    | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| ECS           | A55F-M3                     | Desktop     | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| Google        | Akemi                       | Notebook    | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| MSI           | B460M PRO                   | Desktop     | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                     | Desktop     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Dell          | Latitude E7450              | Notebook    | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Dell          | Latitude 3190               | Notebook    | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Lenovo        | ThinkPad L520 78595VG       | Notebook    | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [08e803937e](https://linux-hardware.org/?probe=08e803937e) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| HP            | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Sony          | SVT13115FBS                 | Notebook    | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| GreatWall     | U320                        | Desktop     | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                        | Desktop     | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | Notebook    | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [536f6d67e3](https://linux-hardware.org/?probe=536f6d67e3) | Oct 02, 2021 |
| Intel         | Unknown                     | Desktop     | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [8699437e9e](https://linux-hardware.org/?probe=8699437e9e) | Oct 01, 2021 |
| Lenovo        | ThinkPad L490 20Q5S0PR00    | Notebook    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer          | Aspire 4820T                | Notebook    | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Lenovo        | ThinkPad P51 20HJS0TP00     | Notebook    | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo        | B40-45 20394                | Notebook    | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| GTZS          | Unknown                     | Notebook    | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Pixus         | Rise                        | Notebook    | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | Notebook    | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [3c5ac88729](https://linux-hardware.org/?probe=3c5ac88729) | Aug 08, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [6949bed845](https://linux-hardware.org/?probe=6949bed845) | Aug 05, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [e94701caeb](https://linux-hardware.org/?probe=e94701caeb) | Aug 03, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| Acer          | Aspire E5-574G              | Notebook    | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| Dell          | Vostro 5515                 | Notebook    | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3340               | Notebook    | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Acer          | Aspire one                  | Notebook    | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [b85b636b73](https://linux-hardware.org/?probe=b85b636b73) | Jun 26, 2021 |
| Medion        | P6669 MD60147               | Notebook    | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | Notebook    | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| Irbis         | TW94                        | Notebook    | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Dell          | Latitude E6320              | Notebook    | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [506efba999](https://linux-hardware.org/?probe=506efba999) | May 02, 2021 |
| Acer          | Extensa 5620                | Notebook    | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | Notebook    | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | Notebook    | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | Notebook    | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Intel         | ChiefRiver                  | Notebook    | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | Notebook    | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [6d6b869b27](https://linux-hardware.org/?probe=6d6b869b27) | Apr 08, 2021 |
| HP            | Falco                       | Notebook    | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | Notebook    | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| ASUSTek       | P5K-E                       | Desktop     | [f0c435ead1](https://linux-hardware.org/?probe=f0c435ead1) | Apr 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| Dell          | 0W7H8C A02                  | Server      | [1a32b081a7](https://linux-hardware.org/?probe=1a32b081a7) | Mar 30, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [04145c0b36](https://linux-hardware.org/?probe=04145c0b36) | Mar 29, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| MSI           | MS-7210 100                 | Desktop     | [e8723eb58b](https://linux-hardware.org/?probe=e8723eb58b) | Mar 17, 2021 |
| HP            | ZBook 17 G6                 | Notebook    | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [dcc5bdef7d](https://linux-hardware.org/?probe=dcc5bdef7d) | Mar 12, 2021 |
| Dell          | Latitude E5470              | Notebook    | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | Notebook    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | Notebook    | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | Notebook    | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | Notebook    | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | Notebook    | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Lenovo        | ThinkPad E425 1198CTO       | Notebook    | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Medion        | E1235T MD99743              | Tablet      | [314aa4d200](https://linux-hardware.org/?probe=314aa4d200) | Feb 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | Mini 110-3500               | Notebook    | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP            | Notebook                    | Notebook    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| HP            | 15                          | Notebook    | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo         | P170EM                      | Notebook    | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| Dell          | Latitude D430               | Notebook    | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
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
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6a65eeffd1](https://linux-hardware.org/?probe=6a65eeffd1) | Nov 27, 2020 |
| HP            | 1905                        | Desktop     | [03a91e7ecc](https://linux-hardware.org/?probe=03a91e7ecc) | Nov 27, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4f8648d28](https://linux-hardware.org/?probe=d4f8648d28) | Nov 24, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [282590eccb](https://linux-hardware.org/?probe=282590eccb) | Nov 24, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| ASRock        | H110M-ITX                   | Desktop     | [e3ca7996d2](https://linux-hardware.org/?probe=e3ca7996d2) | Nov 13, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7bb20fa67](https://linux-hardware.org/?probe=a7bb20fa67) | Nov 08, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [c4f4df2ec5](https://linux-hardware.org/?probe=c4f4df2ec5) | Oct 31, 2020 |
| Dell          | 0D28YY A00                  | Desktop     | [584335af3e](https://linux-hardware.org/?probe=584335af3e) | Oct 29, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| Dell          | Latitude 5175               | Tablet      | [5144248c79](https://linux-hardware.org/?probe=5144248c79) | Oct 19, 2020 |
| HP            | Compaq 8510p (KM229AV)      | Notebook    | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| HP            | Pavilion 15                 | Notebook    | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| Hometech      | Wi11T                       | Tablet      | [78d63aeadc](https://linux-hardware.org/?probe=78d63aeadc) | Sep 30, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Dell          | 0M9KCM A02                  | Desktop     | [3e66c830f8](https://linux-hardware.org/?probe=3e66c830f8) | Sep 22, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [a5f308c899](https://linux-hardware.org/?probe=a5f308c899) | Sep 21, 2020 |
| Lenovo        | ThinkPad T60 20085TG        | Notebook    | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| HP            | 838B 0100                   | All in one  | [c3133d1a1c](https://linux-hardware.org/?probe=c3133d1a1c) | Sep 09, 2020 |
| HP            | 8265                        | Desktop     | [38f924e8f9](https://linux-hardware.org/?probe=38f924e8f9) | Sep 07, 2020 |
| Teclast       | F5                          | Convertible | [1003072bc5](https://linux-hardware.org/?probe=1003072bc5) | Sep 06, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire A114-32              | Notebook    | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [f138fd7e0c](https://linux-hardware.org/?probe=f138fd7e0c) | Aug 09, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [e01126d9bd](https://linux-hardware.org/?probe=e01126d9bd) | Aug 06, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [7a48a3ced3](https://linux-hardware.org/?probe=7a48a3ced3) | Aug 06, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2f71e9b242](https://linux-hardware.org/?probe=2f71e9b242) | Aug 03, 2020 |
| HP            | 3031h                       | Desktop     | [205dd10b09](https://linux-hardware.org/?probe=205dd10b09) | Jul 29, 2020 |
| HP            | 3031h                       | Desktop     | [22ebc88fac](https://linux-hardware.org/?probe=22ebc88fac) | Jul 29, 2020 |
| HP            | Pavilion dv7                | Notebook    | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| Sony          | VPCF23P1E                   | Notebook    | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | Notebook    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | Notebook    | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| MSI           | 970A-G43                    | Desktop     | [ada20a047e](https://linux-hardware.org/?probe=ada20a047e) | May 27, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo        | B590 20206                  | Notebook    | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [901dfafdbf](https://linux-hardware.org/?probe=901dfafdbf) | May 21, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | Notebook    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [34335c5fb5](https://linux-hardware.org/?probe=34335c5fb5) | Apr 24, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Samsung       | R780/R778                   | Notebook    | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [0357ef50d4](https://linux-hardware.org/?probe=0357ef50d4) | Apr 05, 2020 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [60ae29c5ac](https://linux-hardware.org/?probe=60ae29c5ac) | Apr 04, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | Z97-E                       | Desktop     | [42c2810369](https://linux-hardware.org/?probe=42c2810369) | Apr 03, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| MSI           | 760GM-P23                   | Desktop     | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [67d9f2023b](https://linux-hardware.org/?probe=67d9f2023b) | Apr 01, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [104b035076](https://linux-hardware.org/?probe=104b035076) | Apr 01, 2020 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [617031b37d](https://linux-hardware.org/?probe=617031b37d) | Mar 28, 2020 |
| Clevo         | P150HMx                     | Notebook    | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [73690787f9](https://linux-hardware.org/?probe=73690787f9) | Mar 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| Dell          | 0F373D A00                  | Desktop     | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | X455LAB                     | Notebook    | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook      | W65_W67RZ1                  | Notebook    | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | Notebook    | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1243c4a0d9](https://linux-hardware.org/?probe=1243c4a0d9) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | Notebook    | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| HP            | 1790                        | Desktop     | [68a167efd3](https://linux-hardware.org/?probe=68a167efd3) | Mar 24, 2020 |
| Medion        | Akoya E1318T                | Notebook    | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |
| Dell          | Latitude 3190               | Notebook    | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [296f21e934](https://linux-hardware.org/?probe=296f21e934) | Mar 03, 2020 |
| Acer          | Aspire 8943G                | Notebook    | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| ASUSTek       | M4A77T                      | Desktop     | [75d0b42f08](https://linux-hardware.org/?probe=75d0b42f08) | Mar 01, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [370f5d5063](https://linux-hardware.org/?probe=370f5d5063) | Feb 26, 2020 |
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
| Packard Be... | EasyNote TE11HC             | Notebook    | [aa52528043](https://linux-hardware.org/?probe=aa52528043) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [3c957a3758](https://linux-hardware.org/?probe=3c957a3758) | Dec 23, 2019 |
| HP            | Pavilion g6                 | Notebook    | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [2a979257ab](https://linux-hardware.org/?probe=2a979257ab) | Dec 21, 2019 |
| MSI           | MS-7199                     | Desktop     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [b7165ade10](https://linux-hardware.org/?probe=b7165ade10) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | Notebook    | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| Dell          | G3 3579                     | Notebook    | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | Notebook    | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [c96e6bc37c](https://linux-hardware.org/?probe=c96e6bc37c) | Dec 02, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [02ae0c5f5b](https://linux-hardware.org/?probe=02ae0c5f5b) | Dec 02, 2019 |
| MSI           | MS-N033                     | Notebook    | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| ASUSTek       | 1005HA                      | Notebook    | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| MSI           | B75MA-E33                   | Desktop     | [a08cc9782c](https://linux-hardware.org/?probe=a08cc9782c) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | Notebook    | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | Notebook    | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| Gigabyte      | P43-ES3G                    | Desktop     | [96fa353482](https://linux-hardware.org/?probe=96fa353482) | Nov 07, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [585b07ffaf](https://linux-hardware.org/?probe=585b07ffaf) | Nov 04, 2019 |
| ASUSTek       | X101CH                      | Notebook    | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | Notebook    | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | Notebook    | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | Notebook    | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| Dell          | 0F8096                      | Desktop     | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| ZOTAC         | ZBOX-ID18                   | Mini pc     | [4c4d77145b](https://linux-hardware.org/?probe=4c4d77145b) | Oct 20, 2019 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [71373d2071](https://linux-hardware.org/?probe=71373d2071) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| HP            | Pavilion g6                 | Notebook    | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [13dbc6f66d](https://linux-hardware.org/?probe=13dbc6f66d) | Oct 06, 2019 |
| Lenovo        | ThinkPad X220 4291F52       | Notebook    | [e024139431](https://linux-hardware.org/?probe=e024139431) | Aug 29, 2019 |
| Lenovo        | ThinkPad X201s 5413A19      | Notebook    | [673c3629dc](https://linux-hardware.org/?probe=673c3629dc) | Aug 22, 2019 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [acbec08287](https://linux-hardware.org/?probe=acbec08287) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [6a9aa2dd84](https://linux-hardware.org/?probe=6a9aa2dd84) | Jul 22, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [bf82fba8fd](https://linux-hardware.org/?probe=bf82fba8fd) | Apr 29, 2019 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [e42fd626b2](https://linux-hardware.org/?probe=e42fd626b2) | Apr 23, 2019 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [8469904453](https://linux-hardware.org/?probe=8469904453) | Apr 17, 2019 |
| ASUSTek       | K55VM                       | Notebook    | [e967dd6404](https://linux-hardware.org/?probe=e967dd6404) | Mar 27, 2019 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [c68bd6bce7](https://linux-hardware.org/?probe=c68bd6bce7) | Feb 23, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [67b484c4a0](https://linux-hardware.org/?probe=67b484c4a0) | Jan 19, 2019 |
| Acer          | Aspire C22-760              | All in one  | [ff0b5db4bf](https://linux-hardware.org/?probe=ff0b5db4bf) | Dec 18, 2018 |
| Acer          | Aspire C22-760              | All in one  | [7909d2b661](https://linux-hardware.org/?probe=7909d2b661) | Nov 09, 2018 |
| Toshiba       | Satellite C70-B             | Notebook    | [9b54677f2e](https://linux-hardware.org/?probe=9b54677f2e) | Oct 27, 2018 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [ec89febb0c](https://linux-hardware.org/?probe=ec89febb0c) | Oct 27, 2018 |
| Dell          | Inspiron ME051              | Notebook    | [f789720dc4](https://linux-hardware.org/?probe=f789720dc4) | Nov 26, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/MX/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| MX 21          | 359       | 53.66%  |
| MX 19          | 144       | 21.52%  |
| MX 20          | 74        | 11.06%  |
| MX 23          | 58        | 8.67%   |
| MX 18          | 27        | 4.04%   |
| MX 17          | 4         | 0.6%    |
| MX 22          | 1         | 0.15%   |
| MX 16-migrated | 1         | 0.15%   |
| MX 16          | 1         | 0.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MX   | 651       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 4.19.0-6-amd64            | 57        | 7.94%   |
| 5.10.0-21-amd64           | 41        | 5.71%   |
| 6.0.0-6mx-amd64           | 36        | 5.01%   |
| 5.10.0-23-amd64           | 24        | 3.34%   |
| 5.10.0-20-amd64           | 24        | 3.34%   |
| 5.10.0-5mx-amd64          | 23        | 3.2%    |
| 6.1.0-10-amd64            | 20        | 2.79%   |
| 5.10.0-18-amd64           | 20        | 2.79%   |
| 5.10.0-13-amd64           | 20        | 2.79%   |
| 5.10.0-9-amd64            | 18        | 2.51%   |
| 5.10.0-19-amd64           | 18        | 2.51%   |
| 5.14.0-4mx-amd64          | 16        | 2.23%   |
| 5.8.0-3-amd64             | 15        | 2.09%   |
| 5.6.0-2-amd64             | 15        | 2.09%   |
| 5.16.0-5mx-amd64          | 14        | 1.95%   |
| 5.10.0-16-amd64           | 13        | 1.81%   |
| 5.18.0-4mx-amd64          | 11        | 1.53%   |
| 6.4.0-1mx-ahs-amd64       | 10        | 1.39%   |
| 4.19.0-14-amd64           | 10        | 1.39%   |
| 4.19.0-13-amd64           | 10        | 1.39%   |
| 4.19.0-17-amd64           | 9         | 1.25%   |
| 6.1.0-9-amd64             | 8         | 1.11%   |
| 6.1.0-11-amd64            | 8         | 1.11%   |
| 5.10.0-11-amd64           | 8         | 1.11%   |
| 4.19.0-16-amd64           | 8         | 1.11%   |
| 5.10.0-22-amd64           | 7         | 0.97%   |
| 4.19.0-5-amd64            | 7         | 0.97%   |
| 6.0.0-10.1-liquorix-amd64 | 6         | 0.84%   |
| 5.10.0-15-amd64           | 6         | 0.84%   |
| 5.10.0-14-amd64           | 6         | 0.84%   |
| 4.19.0-1-amd64            | 6         | 0.84%   |
| 6.0.0-4mx-amd64           | 5         | 0.7%    |
| 5.4.0-3-amd64             | 5         | 0.7%    |
| 5.10.0-8mx-amd64          | 5         | 0.7%    |
| 4.19.0-18-amd64           | 5         | 0.7%    |
| 4.19.0-12-amd64           | 5         | 0.7%    |
| 5.8.16-antix.1-amd64-smp  | 4         | 0.56%   |
| 5.19.0-2mx-amd64          | 4         | 0.56%   |
| 5.10.0-17-amd64           | 4         | 0.56%   |
| 5.10.0-10-amd64           | 4         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 252       | 36.68%  |
| 4.19.0  | 133       | 19.36%  |
| 6.0.0   | 53        | 7.71%   |
| 6.1.0   | 50        | 7.28%   |
| 5.16.0  | 23        | 3.35%   |
| 5.14.0  | 19        | 2.77%   |
| 5.6.0   | 17        | 2.47%   |
| 5.8.0   | 15        | 2.18%   |
| 6.4.0   | 13        | 1.89%   |
| 5.18.0  | 13        | 1.89%   |
| 5.19.0  | 10        | 1.46%   |
| 5.4.0   | 9         | 1.31%   |
| 5.5.0   | 6         | 0.87%   |
| 5.17.0  | 6         | 0.87%   |
| 4.15.0  | 6         | 0.87%   |
| 5.15.0  | 5         | 0.73%   |
| 5.8.16  | 4         | 0.58%   |
| 5.3.0   | 4         | 0.58%   |
| 5.2.21  | 4         | 0.58%   |
| 5.6.10  | 3         | 0.44%   |
| 6.3.0   | 2         | 0.29%   |
| 6.2.14  | 2         | 0.29%   |
| 6.1.15  | 2         | 0.29%   |
| 5.4.7   | 2         | 0.29%   |
| 5.11.0  | 2         | 0.29%   |
| 4.9.193 | 2         | 0.29%   |
| 4.18.0  | 2         | 0.29%   |
| 6.4.9   | 1         | 0.15%   |
| 6.4.3   | 1         | 0.15%   |
| 6.4.14  | 1         | 0.15%   |
| 6.2.7   | 1         | 0.15%   |
| 6.1.12  | 1         | 0.15%   |
| 6.0.5   | 1         | 0.15%   |
| 5.9.1   | 1         | 0.15%   |
| 5.7.0   | 1         | 0.15%   |
| 5.4.10  | 1         | 0.15%   |
| 5.3.10  | 1         | 0.15%   |
| 5.2.8   | 1         | 0.15%   |
| 5.2.15  | 1         | 0.15%   |
| 5.2.0   | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 258       | 37.55%  |
| 4.19    | 134       | 19.51%  |
| 6.0     | 54        | 7.86%   |
| 6.1     | 53        | 7.71%   |
| 5.16    | 23        | 3.35%   |
| 5.6     | 20        | 2.91%   |
| 5.8     | 19        | 2.77%   |
| 5.14    | 19        | 2.77%   |
| 6.4     | 16        | 2.33%   |
| 5.18    | 13        | 1.89%   |
| 5.4     | 12        | 1.75%   |
| 5.19    | 10        | 1.46%   |
| 5.2     | 7         | 1.02%   |
| 5.5     | 6         | 0.87%   |
| 5.17    | 6         | 0.87%   |
| 4.15    | 6         | 0.87%   |
| 5.3     | 5         | 0.73%   |
| 5.15    | 5         | 0.73%   |
| 4.9     | 5         | 0.73%   |
| 6.2     | 3         | 0.44%   |
| 6.3     | 2         | 0.29%   |
| 5.11    | 2         | 0.29%   |
| 4.18    | 2         | 0.29%   |
| 5.9     | 1         | 0.15%   |
| 5.7     | 1         | 0.15%   |
| 5.13    | 1         | 0.15%   |
| 5.1     | 1         | 0.15%   |
| 5.0     | 1         | 0.15%   |
| 3.16    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 619       | 94.94%  |
| i686   | 33        | 5.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 490       | 73.91%  |
| KDE5             | 115       | 17.35%  |
| Unknown          | 10        | 1.51%   |
| lightdm-xsession | 7         | 1.06%   |
| Budgie           | 7         | 1.06%   |
| i3               | 5         | 0.75%   |
| GNOME            | 5         | 0.75%   |
| MATE             | 4         | 0.6%    |
| LXQt             | 4         | 0.6%    |
| X-Cinnamon       | 3         | 0.45%   |
| fluxbox          | 3         | 0.45%   |
| GNOME Flashback  | 2         | 0.3%    |
| Cinnamon         | 2         | 0.3%    |
| Trinity          | 1         | 0.15%   |
| spectrwm         | 1         | 0.15%   |
| LXDE             | 1         | 0.15%   |
| KDE4             | 1         | 0.15%   |
| KDE              | 1         | 0.15%   |
| GNOME Classic    | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 646       | 99.23%  |
| Tty     | 4         | 0.61%   |
| Wayland | 1         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 524       | 79.64%  |
| SDDM    | 104       | 15.81%  |
| TDM     | 13        | 1.98%   |
| SLiM    | 13        | 1.98%   |
| Unknown | 2         | 0.3%    |
| GDM3    | 1         | 0.15%   |
| GDM     | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 262       | 39.28%  |
| Unknown | 103       | 15.44%  |
| de_DE   | 63        | 9.45%   |
| en_GB   | 36        | 5.4%    |
| it_IT   | 25        | 3.75%   |
| ru_RU   | 19        | 2.85%   |
| es_ES   | 17        | 2.55%   |
| pl_PL   | 16        | 2.4%    |
| fr_FR   | 13        | 1.95%   |
| sk_SK   | 12        | 1.8%    |
| en_AU   | 12        | 1.8%    |
| pt_BR   | 10        | 1.5%    |
| es_AR   | 8         | 1.2%    |
| es_MX   | 7         | 1.05%   |
| tr_TR   | 6         | 0.9%    |
| de_CH   | 6         | 0.9%    |
| nl_NL   | 5         | 0.75%   |
| en_NZ   | 4         | 0.6%    |
| en_CA   | 4         | 0.6%    |
| hu_HU   | 3         | 0.45%   |
| fi_FI   | 3         | 0.45%   |
| es_VE   | 3         | 0.45%   |
| es_CO   | 3         | 0.45%   |
| en_IE   | 3         | 0.45%   |
| uk_UA   | 2         | 0.3%    |
| sv_SE   | 2         | 0.3%    |
| fr_BE   | 2         | 0.3%    |
| bg_BG   | 2         | 0.3%    |
| zh_CN   | 1         | 0.15%   |
| ro_RO   | 1         | 0.15%   |
| nl_BE   | 1         | 0.15%   |
| nb_NO   | 1         | 0.15%   |
| ja_JP   | 1         | 0.15%   |
| id_ID   | 1         | 0.15%   |
| hr_HR   | 1         | 0.15%   |
| fr_CH   | 1         | 0.15%   |
| fr_CA   | 1         | 0.15%   |
| eu_ES   | 1         | 0.15%   |
| es_UY   | 1         | 0.15%   |
| es_PE   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 371       | 56.81%  |
| BIOS | 282       | 43.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 557       | 84.91%  |
| Overlay  | 68        | 10.37%  |
| Btrfs    | 22        | 3.35%   |
| Xfs      | 3         | 0.46%   |
| Unknown  | 2         | 0.3%    |
| Tmpfs    | 1         | 0.15%   |
| Reiserfs | 1         | 0.15%   |
| F2fs     | 1         | 0.15%   |
| Ext3     | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 424       | 64.73%  |
| MBR     | 224       | 34.2%   |
| Unknown | 7         | 1.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 503       | 75.64%  |
| Yes       | 162       | 24.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 367       | 56.03%  |
| Yes       | 288       | 43.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 93        | 14.29%  |
| Hewlett-Packard                      | 93        | 14.29%  |
| ASUSTek Computer                     | 93        | 14.29%  |
| Dell                                 | 80        | 12.29%  |
| Acer                                 | 38        | 5.84%   |
| Gigabyte Technology                  | 35        | 5.38%   |
| MSI                                  | 31        | 4.76%   |
| ASRock                               | 23        | 3.53%   |
| Apple                                | 22        | 3.38%   |
| Sony                                 | 12        | 1.84%   |
| Intel                                | 12        | 1.84%   |
| Toshiba                              | 11        | 1.69%   |
| Medion                               | 10        | 1.54%   |
| Samsung Electronics                  | 7         | 1.08%   |
| Unknown                              | 7         | 1.08%   |
| Fujitsu Siemens                      | 6         | 0.92%   |
| ZOTAC                                | 4         | 0.61%   |
| Alienware                            | 4         | 0.61%   |
| Notebook                             | 3         | 0.46%   |
| Google                               | 3         | 0.46%   |
| Foxconn                              | 3         | 0.46%   |
| Biostar                              | 3         | 0.46%   |
| TUXEDO                               | 2         | 0.31%   |
| Pegatron                             | 2         | 0.31%   |
| Microsoft                            | 2         | 0.31%   |
| Gateway                              | 2         | 0.31%   |
| Fujitsu                              | 2         | 0.31%   |
| ECS                                  | 2         | 0.31%   |
| Clevo                                | 2         | 0.31%   |
| Chuwi                                | 2         | 0.31%   |
| AZW                                  | 2         | 0.31%   |
| win element                          | 1         | 0.15%   |
| Vulcan Electronics                   | 1         | 0.15%   |
| UMAX                                 | 1         | 0.15%   |
| Teclast                              | 1         | 0.15%   |
| Sun Microsystems                     | 1         | 0.15%   |
| SLIMBOOK                             | 1         | 0.15%   |
| SIRAGON                              | 1         | 0.15%   |
| Shenzhen Wangang Technology          | 1         | 0.15%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 11        | 1.69%   |
| ASUS All Series                 | 9         | 1.38%   |
| HP Pavilion Laptop 15-eh1xxx    | 3         | 0.46%   |
| Samsung 305E4A/305E5A/305E7A    | 2         | 0.31%   |
| MSI MS-7C91                     | 2         | 0.31%   |
| MSI MS-7A34                     | 2         | 0.31%   |
| Lenovo ThinkBook 15 G3 ACL 21A4 | 2         | 0.31%   |
| HP Stream Laptop 14-cb0XX       | 2         | 0.31%   |
| HP ProBook 650 G1               | 2         | 0.31%   |
| HP ProBook 450 G1               | 2         | 0.31%   |
| HP Laptop 17-ak0xx              | 2         | 0.31%   |
| Gigabyte GA-MA785GM-US2H        | 2         | 0.31%   |
| Foxconn Pro3500 Series          | 2         | 0.31%   |
| Dell Studio 540                 | 2         | 0.31%   |
| Dell OptiPlex 9020              | 2         | 0.31%   |
| Dell OptiPlex 9010              | 2         | 0.31%   |
| Dell OptiPlex 790               | 2         | 0.31%   |
| Dell OptiPlex 755               | 2         | 0.31%   |
| Dell Latitude E6540             | 2         | 0.31%   |
| Dell Latitude E6320             | 2         | 0.31%   |
| Dell Latitude 5530              | 2         | 0.31%   |
| Dell Inspiron 13-5378           | 2         | 0.31%   |
| Chuwi GemiBook Pro              | 2         | 0.31%   |
| AZW SER                         | 2         | 0.31%   |
| ASUS ZenBook UX363EA_UX363EA    | 2         | 0.31%   |
| ASUS X200CA                     | 2         | 0.31%   |
| ASUS ROG Maximus XIII HERO      | 2         | 0.31%   |
| ASUS PRIME B450M-A              | 2         | 0.31%   |
| ASRock K8A780LM                 | 2         | 0.31%   |
| Apple Macmini8,1                | 2         | 0.31%   |
| Apple MacBookAir7,2             | 2         | 0.31%   |
| Acer Nitro AN515-55             | 2         | 0.31%   |
| Acer Aspire ES1-511             | 2         | 0.31%   |
| ZOTAC ZBOX-ID18                 | 1         | 0.15%   |
| ZOTAC ZBOX-ECM73070C/53060C     | 1         | 0.15%   |
| ZOTAC ZBOX-BI320                | 1         | 0.15%   |
| win element MoreFine S500+      | 1         | 0.15%   |
| Vulcan Excursion XB             | 1         | 0.15%   |
| UMAX VisionBook-N12R            | 1         | 0.15%   |
| TUXEDO N7x0WU                   | 1         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 52        | 7.99%   |
| Dell Latitude         | 27        | 4.15%   |
| Acer Aspire           | 25        | 3.84%   |
| Dell Inspiron         | 16        | 2.46%   |
| Dell OptiPlex         | 14        | 2.15%   |
| Lenovo IdeaPad        | 12        | 1.84%   |
| HP ProBook            | 12        | 1.84%   |
| HP Pavilion           | 12        | 1.84%   |
| HP EliteBook          | 11        | 1.69%   |
| Unknown               | 11        | 1.69%   |
| HP Laptop             | 10        | 1.54%   |
| Toshiba Satellite     | 9         | 1.38%   |
| ASUS VivoBook         | 9         | 1.38%   |
| ASUS All              | 9         | 1.38%   |
| ASUS TUF              | 8         | 1.23%   |
| HP Compaq             | 7         | 1.08%   |
| ASUS ROG              | 7         | 1.08%   |
| Dell Precision        | 6         | 0.92%   |
| ASUS PRIME            | 6         | 0.92%   |
| Dell Vostro           | 5         | 0.77%   |
| HP ZBook              | 4         | 0.61%   |
| HP Spectre            | 4         | 0.61%   |
| HP ENVY               | 4         | 0.61%   |
| Lenovo ThinkBook      | 3         | 0.46%   |
| HP 250                | 3         | 0.46%   |
| Fujitsu Siemens AMILO | 3         | 0.46%   |
| Dell XPS              | 3         | 0.46%   |
| ASUS ZenBook          | 3         | 0.46%   |
| Acer Swift            | 3         | 0.46%   |
| Acer Nitro            | 3         | 0.46%   |
| Acer Extensa          | 3         | 0.46%   |
| Toshiba PORTEGE       | 2         | 0.31%   |
| Samsung 305E4A        | 2         | 0.31%   |
| MSI MS-7C91           | 2         | 0.31%   |
| MSI MS-7A34           | 2         | 0.31%   |
| Microsoft Surface     | 2         | 0.31%   |
| Medion Akoya          | 2         | 0.31%   |
| Lenovo Yoga           | 2         | 0.31%   |
| Lenovo ThinkCentre    | 2         | 0.31%   |
| Lenovo MIIX           | 2         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 58        | 8.91%   |
| 2011    | 57        | 8.76%   |
| 2018    | 53        | 8.14%   |
| 2020    | 49        | 7.53%   |
| 2013    | 49        | 7.53%   |
| 2012    | 49        | 7.53%   |
| 2010    | 43        | 6.61%   |
| 2019    | 39        | 5.99%   |
| 2016    | 39        | 5.99%   |
| 2022    | 34        | 5.22%   |
| 2014    | 32        | 4.92%   |
| 2015    | 30        | 4.61%   |
| 2017    | 29        | 4.45%   |
| 2008    | 24        | 3.69%   |
| 2009    | 22        | 3.38%   |
| 2007    | 17        | 2.61%   |
| 2006    | 11        | 1.69%   |
| 2023    | 7         | 1.08%   |
| 2005    | 7         | 1.08%   |
| 2004    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 392       | 60.22%  |
| Desktop     | 204       | 31.34%  |
| Convertible | 17        | 2.61%   |
| Mini pc     | 17        | 2.61%   |
| Tablet      | 9         | 1.38%   |
| All in one  | 8         | 1.23%   |
| Server      | 4         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 640       | 98.31%  |
| Enabled  | 11        | 1.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 646       | 99.23%  |
| Yes  | 5         | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 165       | 25.27%  |
| 8.01-16.0   | 133       | 20.37%  |
| 16.01-24.0  | 108       | 16.54%  |
| 3.01-4.0    | 99        | 15.16%  |
| 32.01-64.0  | 59        | 9.04%   |
| 1.01-2.0    | 46        | 7.04%   |
| 24.01-32.0  | 13        | 1.99%   |
| 2.01-3.0    | 13        | 1.99%   |
| 0.51-1.0    | 9         | 1.38%   |
| 64.01-256.0 | 8         | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 246       | 35.76%  |
| 2.01-3.0   | 186       | 27.03%  |
| 3.01-4.0   | 99        | 14.39%  |
| 4.01-8.0   | 69        | 10.03%  |
| 0.51-1.0   | 62        | 9.01%   |
| 8.01-16.0  | 17        | 2.47%   |
| 0.01-0.5   | 7         | 1.02%   |
| 16.01-24.0 | 2         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 401       | 60.39%  |
| 2      | 156       | 23.49%  |
| 3      | 61        | 9.19%   |
| 4      | 21        | 3.16%   |
| 5      | 11        | 1.66%   |
| 0      | 7         | 1.05%   |
| 8      | 4         | 0.6%    |
| 9      | 1         | 0.15%   |
| 7      | 1         | 0.15%   |
| 6      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 407       | 62.14%  |
| Yes       | 248       | 37.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 567       | 87.1%   |
| No        | 84        | 12.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 520       | 79.63%  |
| No        | 133       | 20.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 396       | 60.64%  |
| No        | 257       | 39.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 143       | 21.83%  |
| Germany      | 69        | 10.53%  |
| Italy        | 36        | 5.5%    |
| UK           | 30        | 4.58%   |
| Canada       | 28        | 4.27%   |
| Russia       | 24        | 3.66%   |
| Spain        | 23        | 3.51%   |
| Poland       | 21        | 3.21%   |
| India        | 19        | 2.9%    |
| France       | 19        | 2.9%    |
| Australia    | 19        | 2.9%    |
| Slovakia     | 17        | 2.6%    |
| Netherlands  | 14        | 2.14%   |
| Brazil       | 14        | 2.14%   |
| Greece       | 12        | 1.83%   |
| Finland      | 10        | 1.53%   |
| Mexico       | 9         | 1.37%   |
| Sweden       | 8         | 1.22%   |
| Serbia       | 8         | 1.22%   |
| Turkey       | 7         | 1.07%   |
| Switzerland  | 7         | 1.07%   |
| Austria      | 7         | 1.07%   |
| Argentina    | 7         | 1.07%   |
| Romania      | 6         | 0.92%   |
| Indonesia    | 6         | 0.92%   |
| Belgium      | 6         | 0.92%   |
| Ukraine      | 5         | 0.76%   |
| New Zealand  | 5         | 0.76%   |
| Venezuela    | 4         | 0.61%   |
| Hungary      | 4         | 0.61%   |
| Czechia      | 4         | 0.61%   |
| Colombia     | 4         | 0.61%   |
| Thailand     | 3         | 0.46%   |
| South Africa | 3         | 0.46%   |
| Singapore    | 3         | 0.46%   |
| Portugal     | 3         | 0.46%   |
| Denmark      | 3         | 0.46%   |
| Chile        | 3         | 0.46%   |
| Belarus      | 3         | 0.46%   |
| Vietnam      | 2         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Bratislava     | 16        | 2.36%   |
| Berlin         | 10        | 1.47%   |
| Vienna         | 7         | 1.03%   |
| Sydney         | 7         | 1.03%   |
| Moscow         | 7         | 1.03%   |
| Athens         | 7         | 1.03%   |
| St Petersburg  | 6         | 0.88%   |
| Warsaw         | 5         | 0.74%   |
| Milan          | 5         | 0.74%   |
| Melbourne      | 5         | 0.74%   |
| Bengaluru      | 5         | 0.74%   |
| Belgrade       | 5         | 0.74%   |
| Rome           | 4         | 0.59%   |
| Madrid         | 4         | 0.59%   |
| Amsterdam      | 4         | 0.59%   |
| Singapore      | 3         | 0.44%   |
| Patna          | 3         | 0.44%   |
| Oxford         | 3         | 0.44%   |
| Otwock         | 3         | 0.44%   |
| Oakland        | 3         | 0.44%   |
| Munich         | 3         | 0.44%   |
| Montreal       | 3         | 0.44%   |
| Mesquite       | 3         | 0.44%   |
| Los Angeles    | 3         | 0.44%   |
| Krakow         | 3         | 0.44%   |
| Istanbul       | 3         | 0.44%   |
| Helsinki       | 3         | 0.44%   |
| Hamburg        | 3         | 0.44%   |
| Florianópolis | 3         | 0.44%   |
| Florence       | 3         | 0.44%   |
| Catania        | 3         | 0.44%   |
| Cambridge      | 3         | 0.44%   |
| Calgary        | 3         | 0.44%   |
| Buffalo        | 3         | 0.44%   |
| Budapest       | 3         | 0.44%   |
| Bogotá        | 3         | 0.44%   |
| Birmingham     | 3         | 0.44%   |
| Barcelona      | 3         | 0.44%   |
| Walled Lake    | 2         | 0.29%   |
| Vera           | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 139       | 165    | 14.36%  |
| Samsung Electronics | 136       | 191    | 14.05%  |
| Seagate             | 116       | 160    | 11.98%  |
| Kingston            | 64        | 68     | 6.61%   |
| Toshiba             | 53        | 62     | 5.48%   |
| SanDisk             | 48        | 54     | 4.96%   |
| Crucial             | 46        | 76     | 4.75%   |
| Unknown             | 44        | 54     | 4.55%   |
| Hitachi             | 34        | 42     | 3.51%   |
| SK hynix            | 27        | 28     | 2.79%   |
| Intel               | 21        | 28     | 2.17%   |
| HGST                | 15        | 20     | 1.55%   |
| China               | 15        | 18     | 1.55%   |
| A-DATA Technology   | 15        | 17     | 1.55%   |
| Micron Technology   | 11        | 15     | 1.14%   |
| Apple               | 11        | 15     | 1.14%   |
| SPCC                | 10        | 10     | 1.03%   |
| PNY                 | 9         | 11     | 0.93%   |
| KIOXIA              | 9         | 11     | 0.93%   |
| LITEON              | 7         | 7      | 0.72%   |
| Corsair             | 7         | 7      | 0.72%   |
| Transcend           | 6         | 6      | 0.62%   |
| GOODRAM             | 6         | 7      | 0.62%   |
| Fujitsu             | 6         | 6      | 0.62%   |
| Team                | 5         | 5      | 0.52%   |
| Netac               | 5         | 5      | 0.52%   |
| Maxtor              | 5         | 6      | 0.52%   |
| Apacer              | 5         | 5      | 0.52%   |
| Unknown             | 5         | 5      | 0.52%   |
| Silicon Motion      | 4         | 4      | 0.41%   |
| Phison              | 4         | 5      | 0.41%   |
| Patriot             | 3         | 3      | 0.31%   |
| OCZ                 | 3         | 3      | 0.31%   |
| Mushkin             | 3         | 3      | 0.31%   |
| KingSpec            | 3         | 3      | 0.31%   |
| Dogfish             | 3         | 3      | 0.31%   |
| WALRAM              | 2         | 2      | 0.21%   |
| UMIS                | 2         | 2      | 0.21%   |
| Teclast             | 2         | 2      | 0.21%   |
| Phison Electronics  | 2         | 3      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 13        | 1.24%   |
| Kingston SA400S37480G 480GB SSD        | 12        | 1.14%   |
| Samsung SSD 850 EVO 250GB              | 8         | 0.76%   |
| Kingston SV300S37A120G 120GB SSD       | 8         | 0.76%   |
| Kingston SA400S37240G 240GB SSD        | 8         | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB         | 7         | 0.67%   |
| Samsung SSD 970 EVO Plus 1TB           | 7         | 0.67%   |
| Kingston SA400S37120G 120GB SSD        | 7         | 0.67%   |
| Seagate ST4000DM004-2CV104 4TB         | 6         | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB         | 6         | 0.57%   |
| Samsung SSD 980 PRO 1TB                | 6         | 0.57%   |
| Crucial CT500MX500SSD1 500GB           | 6         | 0.57%   |
| Crucial CT120BX500SSD1 120GB           | 6         | 0.57%   |
| Toshiba MQ01ABF050 500GB               | 5         | 0.48%   |
| Seagate ST1000LM048-2E7172 1TB         | 5         | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB         | 5         | 0.48%   |
| SanDisk NVMe SSD Drive 1TB             | 5         | 0.48%   |
| Samsung SSD 870 EVO 500GB              | 5         | 0.48%   |
| Samsung SSD 850 EVO 500GB              | 5         | 0.48%   |
| Kingston SV300S37A240G 240GB SSD       | 5         | 0.48%   |
| HGST HTS721010A9E630 1TB               | 5         | 0.48%   |
| Unknown                                | 5         | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB               | 4         | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB            | 4         | 0.38%   |
| Toshiba DT01ACA100 1TB                 | 4         | 0.38%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 4         | 0.38%   |
| Seagate ST500LM021-1KJ152 500GB        | 4         | 0.38%   |
| Seagate ST500DM002-1BD142 500GB        | 4         | 0.38%   |
| Seagate ST3500413AS 500GB              | 4         | 0.38%   |
| SanDisk SDSSDA120G 120GB               | 4         | 0.38%   |
| Samsung SSD 860 EVO 250GB              | 4         | 0.38%   |
| Hitachi HTS543232A7A384 320GB          | 4         | 0.38%   |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.38%   |
| Crucial CT1000MX500SSD1 1TB            | 4         | 0.38%   |
| A-DATA SP600 32GB SSD                  | 4         | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 3         | 0.29%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 3         | 0.29%   |
| WDC WD10EZEX-60WN4A0 1TB               | 3         | 0.29%   |
| WDC WD10EZEX-00BN5A0 1TB               | 3         | 0.29%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 3         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 116       | 159    | 33.72%  |
| WDC                 | 105       | 127    | 30.52%  |
| Toshiba             | 41        | 49     | 11.92%  |
| Hitachi             | 34        | 42     | 9.88%   |
| HGST                | 15        | 20     | 4.36%   |
| Samsung Electronics | 11        | 14     | 3.2%    |
| Fujitsu             | 6         | 6      | 1.74%   |
| Maxtor              | 5         | 6      | 1.45%   |
| Unknown             | 4         | 4      | 1.16%   |
| External            | 2         | 2      | 0.58%   |
| Space ke            | 1         | 2      | 0.29%   |
| SABRENT             | 1         | 1      | 0.29%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |
| ASMT                | 1         | 1      | 0.29%   |
| Apple               | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 80        | 105    | 20.89%  |
| Kingston            | 50        | 53     | 13.05%  |
| Crucial             | 39        | 62     | 10.18%  |
| SanDisk             | 33        | 37     | 8.62%   |
| WDC                 | 15        | 16     | 3.92%   |
| China               | 15        | 18     | 3.92%   |
| A-DATA Technology   | 13        | 15     | 3.39%   |
| SPCC                | 10        | 10     | 2.61%   |
| SK hynix            | 8         | 8      | 2.09%   |
| PNY                 | 8         | 9      | 2.09%   |
| Apple               | 8         | 11     | 2.09%   |
| Intel               | 7         | 11     | 1.83%   |
| Transcend           | 6         | 6      | 1.57%   |
| LITEON              | 6         | 6      | 1.57%   |
| GOODRAM             | 6         | 7      | 1.57%   |
| Netac               | 5         | 5      | 1.31%   |
| Micron Technology   | 5         | 9      | 1.31%   |
| Toshiba             | 4         | 4      | 1.04%   |
| Team                | 4         | 4      | 1.04%   |
| OCZ                 | 3         | 3      | 0.78%   |
| KingSpec            | 3         | 3      | 0.78%   |
| Dogfish             | 3         | 3      | 0.78%   |
| Apacer              | 3         | 3      | 0.78%   |
| WALRAM              | 2         | 2      | 0.52%   |
| Teclast             | 2         | 2      | 0.52%   |
| Patriot             | 2         | 2      | 0.52%   |
| Mushkin             | 2         | 2      | 0.52%   |
| KingFast            | 2         | 2      | 0.52%   |
| KingDian            | 2         | 2      | 0.52%   |
| Intenso             | 2         | 2      | 0.52%   |
| Indilinx            | 2         | 4      | 0.52%   |
| Gigabyte Technology | 2         | 2      | 0.52%   |
| EYOTA               | 2         | 2      | 0.52%   |
| Corsair             | 2         | 2      | 0.52%   |
| Unknown             | 2         | 2      | 0.52%   |
| ZTC                 | 1         | 1      | 0.26%   |
| Yeyian              | 1         | 1      | 0.26%   |
| X12                 | 1         | 1      | 0.26%   |
| WDC WDS1            | 1         | 1      | 0.26%   |
| Vaseky              | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 328       | 463    | 38.1%   |
| HDD     | 293       | 435    | 34.03%  |
| NVMe    | 191       | 240    | 22.18%  |
| MMC     | 42        | 54     | 4.88%   |
| Unknown | 7         | 9      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 487       | 868    | 65.28%  |
| NVMe | 190       | 239    | 25.47%  |
| MMC  | 42        | 54     | 5.63%   |
| SAS  | 27        | 40     | 3.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 399       | 570    | 62.74%  |
| 0.51-1.0   | 162       | 224    | 25.47%  |
| 1.01-2.0   | 41        | 51     | 6.45%   |
| 3.01-4.0   | 13        | 14     | 2.04%   |
| 2.01-3.0   | 11        | 14     | 1.73%   |
| 4.01-10.0  | 9         | 24     | 1.42%   |
| 10.01-20.0 | 1         | 1      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 176       | 25.96%  |
| 251-500        | 139       | 20.5%   |
| 501-1000       | 88        | 12.98%  |
| 51-100         | 76        | 11.21%  |
| 21-50          | 59        | 8.7%    |
| 1001-2000      | 48        | 7.08%   |
| 1-20           | 40        | 5.9%    |
| More than 3000 | 27        | 3.98%   |
| 2001-3000      | 23        | 3.39%   |
| Unknown        | 2         | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 277       | 40.38%  |
| 21-50          | 103       | 15.01%  |
| 101-250        | 88        | 12.83%  |
| 51-100         | 83        | 12.1%   |
| 251-500        | 55        | 8.02%   |
| 501-1000       | 34        | 4.96%   |
| 1001-2000      | 24        | 3.5%    |
| More than 3000 | 12        | 1.75%   |
| 2001-3000      | 8         | 1.17%   |
| Unknown        | 2         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 3         | 3      | 2.13%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 2      | 1.42%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2      | 1.42%   |
| Toshiba MK7575GSX 752GB              | 2         | 3      | 1.42%   |
| Toshiba MK5059GSXP 500GB             | 2         | 2      | 1.42%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 1.42%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 2      | 1.42%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 2      | 1.42%   |
| Indilinx IND-S325S120G 120GB SSD     | 2         | 4      | 1.42%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 2      | 1.42%   |
| China SSD 512GB                      | 2         | 2      | 1.42%   |
| A-DATA Technology SU650 240GB SSD    | 2         | 2      | 1.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 1      | 0.71%   |
| WDC WD5003ABYX-01WERA1 500GB         | 1         | 1      | 0.71%   |
| WDC WD5000BPVT-60HXZT3 500GB         | 1         | 1      | 0.71%   |
| WDC WD5000AAKS-40V6A0 500GB          | 1         | 1      | 0.71%   |
| WDC WD40EZRX-00SPEB0 4TB             | 1         | 1      | 0.71%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 1      | 0.71%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 1         | 1      | 0.71%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 1      | 0.71%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1      | 0.71%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 1      | 0.71%   |
| WDC WD3200AAKS-00UU3A0 320GB         | 1         | 1      | 0.71%   |
| WDC WD3200AAJS-00B4A0 320GB          | 1         | 1      | 0.71%   |
| WDC WD2500AAJS-00B4A0 250GB          | 1         | 2      | 0.71%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 1      | 0.71%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 1      | 0.71%   |
| WDC WD20EARS-00J99B0 2TB             | 1         | 1      | 0.71%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1      | 0.71%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 1      | 0.71%   |
| WDC WD1600AVVS-63L2B0 160GB          | 1         | 1      | 0.71%   |
| WDC WD15EADS-11P8B2 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 1      | 0.71%   |
| WDC WD10EZEX-75WN4A0 1TB             | 1         | 1      | 0.71%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 1      | 0.71%   |
| WDC WD10EAVS-00D7B1 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EADS-98M2B0 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EADS-00M2B0 1TB              | 1         | 1      | 0.71%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 37     | 23.02%  |
| WDC                 | 28        | 29     | 20.14%  |
| Hitachi             | 15        | 16     | 10.79%  |
| Toshiba             | 11        | 12     | 7.91%   |
| Samsung Electronics | 10        | 15     | 7.19%   |
| HGST                | 7         | 8      | 5.04%   |
| Crucial             | 5         | 19     | 3.6%    |
| Maxtor              | 4         | 4      | 2.88%   |
| Kingston            | 4         | 4      | 2.88%   |
| Fujitsu             | 4         | 4      | 2.88%   |
| SK hynix            | 2         | 2      | 1.44%   |
| Indilinx            | 2         | 4      | 1.44%   |
| China               | 2         | 2      | 1.44%   |
| A-DATA Technology   | 2         | 2      | 1.44%   |
| SPCC                | 1         | 1      | 0.72%   |
| SanDisk             | 1         | 1      | 0.72%   |
| RENICE              | 1         | 1      | 0.72%   |
| OCZ                 | 1         | 1      | 0.72%   |
| Netac               | 1         | 1      | 0.72%   |
| Lexar               | 1         | 1      | 0.72%   |
| KingSpec            | 1         | 1      | 0.72%   |
| Intenso             | 1         | 1      | 0.72%   |
| Intel               | 1         | 2      | 0.72%   |
| IBM/Hitachi         | 1         | 1      | 0.72%   |
| GOODRAM             | 1         | 1      | 0.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 37     | 31.07%  |
| WDC                 | 27        | 28     | 26.21%  |
| Hitachi             | 15        | 16     | 14.56%  |
| Toshiba             | 10        | 11     | 9.71%   |
| HGST                | 7         | 8      | 6.8%    |
| Maxtor              | 4         | 4      | 3.88%   |
| Fujitsu             | 4         | 4      | 3.88%   |
| Samsung Electronics | 3         | 5      | 2.91%   |
| IBM/Hitachi         | 1         | 1      | 0.97%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 100       | 114    | 74.07%  |
| SSD  | 31        | 46     | 22.96%  |
| NVMe | 4         | 10     | 2.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB   | 2         | 2      | 66.67%  |
| Seagate ST3500418AS 500GB | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 532       | 909    | 70.46%  |
| Malfunc  | 131       | 170    | 17.35%  |
| Detected | 89        | 118    | 11.79%  |
| Failed   | 3         | 4      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 440       | 55.28%  |
| AMD                          | 111       | 13.94%  |
| Samsung Electronics          | 59        | 7.41%   |
| SanDisk                      | 31        | 3.89%   |
| SK hynix                     | 17        | 2.14%   |
| Kingston Technology Company  | 14        | 1.76%   |
| Phison Electronics           | 13        | 1.63%   |
| Nvidia                       | 13        | 1.63%   |
| ASMedia Technology           | 13        | 1.63%   |
| KIOXIA                       | 12        | 1.51%   |
| Silicon Motion               | 10        | 1.26%   |
| Micron/Crucial Technology    | 10        | 1.26%   |
| Marvell Technology Group     | 9         | 1.13%   |
| JMicron Technology           | 9         | 1.13%   |
| Micron Technology            | 6         | 0.75%   |
| Toshiba America Info Systems | 5         | 0.63%   |
| VIA Technologies             | 3         | 0.38%   |
| ADATA Technology             | 3         | 0.38%   |
| Union Memory (Shenzhen)      | 2         | 0.25%   |
| ULi Electronics              | 2         | 0.25%   |
| Silicon Image                | 2         | 0.25%   |
| Shenzhen Longsys Electronics | 2         | 0.25%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.25%   |
| Broadcom / LSI               | 2         | 0.25%   |
| Apple                        | 2         | 0.25%   |
| LSI Logic / Symbios Logic    | 1         | 0.13%   |
| Lite-On Technology           | 1         | 0.13%   |
| Lenovo                       | 1         | 0.13%   |
| Hewlett-Packard              | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 69        | 7.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 41        | 4.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 32        | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 30        | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 28        | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25        | 2.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 2.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 17        | 1.87%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 13        | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 13        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 13        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 13        | 1.43%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12        | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11        | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11        | 1.21%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 1.21%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 9         | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 0.99%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 0.99%   |
| Phison E12 NVMe Controller                                                     | 8         | 0.88%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 8         | 0.88%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 8         | 0.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 8         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 8         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8         | 0.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 0.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 0.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 7         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 477       | 59.03%  |
| NVMe | 187       | 23.14%  |
| IDE  | 96        | 11.88%  |
| RAID | 46        | 5.69%   |
| SCSI | 2         | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 508       | 78.03%  |
| AMD          | 142       | 21.81%  |
| CentaurHauls | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz       | 9         | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 1.38%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 8         | 1.23%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 8         | 1.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 7         | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 7         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 0.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 6         | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 6         | 0.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 5         | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 5         | 0.77%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 5         | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 5         | 0.77%   |
| Intel 12th Gen Core i5-1235U            | 5         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 4         | 0.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 4         | 0.61%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 4         | 0.61%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 4         | 0.61%   |
| Intel Celeron CPU 1007U @ 1.50GHz       | 4         | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 4         | 0.61%   |
| Intel 12th Gen Core i7-12700H           | 4         | 0.61%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4         | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 0.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 0.46%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 3         | 0.46%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 3         | 0.46%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 3         | 0.46%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 3         | 0.46%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 3         | 0.46%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 3         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 0.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 3         | 0.46%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 0.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 0.46%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 3         | 0.46%   |
| Intel Core i3-4000M CPU @ 2.40GHz       | 3         | 0.46%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 3         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 132       | 20.28%  |
| Intel Core i7           | 114       | 17.51%  |
| Other                   | 50        | 7.68%   |
| Intel Core i3           | 47        | 7.22%   |
| Intel Celeron           | 44        | 6.76%   |
| AMD Ryzen 5             | 36        | 5.53%   |
| AMD Ryzen 7             | 32        | 4.92%   |
| Intel Core 2 Duo        | 27        | 4.15%   |
| Intel Atom              | 25        | 3.84%   |
| Intel Pentium           | 14        | 2.15%   |
| Intel Xeon              | 9         | 1.38%   |
| AMD Ryzen 3             | 8         | 1.23%   |
| AMD Ryzen 9             | 7         | 1.08%   |
| Intel Core 2 Quad       | 6         | 0.92%   |
| Intel Pentium Dual-Core | 5         | 0.77%   |
| AMD Phenom II X4        | 5         | 0.77%   |
| AMD A6                  | 5         | 0.77%   |
| Intel Pentium 4         | 4         | 0.61%   |
| Intel Genuine           | 4         | 0.61%   |
| AMD E1                  | 4         | 0.61%   |
| AMD A8                  | 4         | 0.61%   |
| AMD A4                  | 4         | 0.61%   |
| Intel Pentium Silver    | 3         | 0.46%   |
| Intel Pentium M         | 3         | 0.46%   |
| Intel Pentium Gold      | 3         | 0.46%   |
| Intel Core i9           | 3         | 0.46%   |
| Intel Core 2            | 3         | 0.46%   |
| Intel Celeron M         | 3         | 0.46%   |
| AMD Turion 64 X2 Mobile | 3         | 0.46%   |
| AMD Sempron             | 3         | 0.46%   |
| AMD E                   | 3         | 0.46%   |
| AMD Athlon II X4        | 3         | 0.46%   |
| AMD Athlon II X2        | 3         | 0.46%   |
| Intel Pentium Dual      | 2         | 0.31%   |
| Intel Pentium D         | 2         | 0.31%   |
| AMD Phenom II X6        | 2         | 0.31%   |
| AMD Phenom              | 2         | 0.31%   |
| AMD FX                  | 2         | 0.31%   |
| AMD Athlon 64 X2        | 2         | 0.31%   |
| AMD Athlon              | 2         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 273       | 41.94%  |
| 4      | 217       | 33.33%  |
| 6      | 57        | 8.76%   |
| 8      | 49        | 7.53%   |
| 1      | 27        | 4.15%   |
| 12     | 10        | 1.54%   |
| 10     | 10        | 1.54%   |
| 14     | 5         | 0.77%   |
| 16     | 1         | 0.15%   |
| 5      | 1         | 0.15%   |
| 3      | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 647       | 99.39%  |
| 2      | 4         | 0.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 403       | 61.81%  |
| 1      | 249       | 38.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 634       | 97.24%  |
| 32-bit         | 18        | 2.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 11.2%   |
| 0x206a7    | 49        | 7.41%   |
| 0x306a9    | 41        | 6.2%    |
| 0x306c3    | 34        | 5.14%   |
| 0x1067a    | 22        | 3.33%   |
| 0x406e3    | 20        | 3.03%   |
| 0x806c1    | 18        | 2.72%   |
| 0x20655    | 15        | 2.27%   |
| 0x0a50000c | 15        | 2.27%   |
| 0x906ea    | 13        | 1.97%   |
| 0x506e3    | 13        | 1.97%   |
| 0x40651    | 13        | 1.97%   |
| 0x806ec    | 12        | 1.82%   |
| 0x806e9    | 12        | 1.82%   |
| 0x30678    | 12        | 1.82%   |
| 0x806ea    | 10        | 1.51%   |
| 0x306d4    | 10        | 1.51%   |
| 0x706a1    | 9         | 1.36%   |
| 0x08608103 | 9         | 1.36%   |
| 0x906ed    | 8         | 1.21%   |
| 0x906e9    | 8         | 1.21%   |
| 0x906a3    | 8         | 1.21%   |
| 0x706a8    | 8         | 1.21%   |
| 0x406c4    | 8         | 1.21%   |
| 0x906a4    | 7         | 1.06%   |
| 0x08701021 | 7         | 1.06%   |
| 0xa0671    | 6         | 0.91%   |
| 0x6fd      | 6         | 0.91%   |
| 0x20652    | 6         | 0.91%   |
| 0x106e5    | 6         | 0.91%   |
| 0x0800820d | 6         | 0.91%   |
| 0xa0653    | 5         | 0.76%   |
| 0xa0652    | 5         | 0.76%   |
| 0x6d8      | 5         | 0.76%   |
| 0x506c9    | 5         | 0.76%   |
| 0x10676    | 5         | 0.76%   |
| 0x08108109 | 5         | 0.76%   |
| 0x03000027 | 5         | 0.76%   |
| 0x010000c8 | 5         | 0.76%   |
| 0x906c0    | 4         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 74        | 11.35%  |
| SandyBridge      | 57        | 8.74%   |
| Haswell          | 55        | 8.44%   |
| IvyBridge        | 49        | 7.52%   |
| Skylake          | 36        | 5.52%   |
| Penryn           | 34        | 5.21%   |
| Unknown          | 30        | 4.6%    |
| Silvermont       | 25        | 3.83%   |
| Zen 3            | 24        | 3.68%   |
| Westmere         | 23        | 3.53%   |
| TigerLake        | 20        | 3.07%   |
| Zen+             | 18        | 2.76%   |
| Zen 2            | 17        | 2.61%   |
| K10              | 17        | 2.61%   |
| Goldmont plus    | 17        | 2.61%   |
| Core             | 15        | 2.3%    |
| Alderlake Hybrid | 13        | 1.99%   |
| CometLake        | 12        | 1.84%   |
| Icelake          | 11        | 1.69%   |
| Broadwell        | 11        | 1.69%   |
| Bonnell          | 11        | 1.69%   |
| Zen              | 10        | 1.53%   |
| K8 Hammer        | 10        | 1.53%   |
| P6               | 9         | 1.38%   |
| Nehalem          | 9         | 1.38%   |
| NetBurst         | 7         | 1.07%   |
| K10 Llano        | 6         | 0.92%   |
| Goldmont         | 6         | 0.92%   |
| Puma             | 5         | 0.77%   |
| Excavator        | 5         | 0.77%   |
| Tremont          | 4         | 0.61%   |
| Jaguar           | 3         | 0.46%   |
| Bobcat           | 3         | 0.46%   |
| Steamroller      | 2         | 0.31%   |
| Piledriver       | 2         | 0.31%   |
| K8 & K10 hybrid  | 1         | 0.15%   |
| Bulldozer        | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 404       | 52.81%  |
| Nvidia                     | 187       | 24.44%  |
| AMD                        | 172       | 22.48%  |
| VIA Technologies           | 1         | 0.13%   |
| Matrox Electronics Systems | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 35        | 4.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 2.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 2.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 1.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 1.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.77%   |
| Intel UHD Graphics 620                                                                   | 13        | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.39%   |
| AMD Lucienne                                                                             | 11        | 1.39%   |
| Intel HD Graphics 620                                                                    | 10        | 1.26%   |
| Intel HD Graphics 530                                                                    | 10        | 1.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 0.88%   |
| Intel HD Graphics 630                                                                    | 7         | 0.88%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 7         | 0.88%   |
| AMD Renoir                                                                               | 7         | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 0.76%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 0.76%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.63%   |
| AMD Raphael                                                                              | 5         | 0.63%   |
| AMD Barcelo                                                                              | 5         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 303       | 46.26%  |
| 1 x AMD        | 131       | 20%     |
| 1 x Nvidia     | 108       | 16.49%  |
| Intel + Nvidia | 65        | 9.92%   |
| Intel + AMD    | 20        | 3.05%   |
| AMD + Nvidia   | 13        | 1.98%   |
| 2 x AMD        | 9         | 1.37%   |
| 2 x Intel      | 3         | 0.46%   |
| 3 x AMD        | 1         | 0.15%   |
| 1 x VIA        | 1         | 0.15%   |
| 1 x Matrox     | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 551       | 83.61%  |
| Proprietary | 79        | 11.99%  |
| Unknown     | 29        | 4.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 400       | 60.61%  |
| 0.01-0.5   | 85        | 12.88%  |
| 1.01-2.0   | 60        | 9.09%   |
| 0.51-1.0   | 45        | 6.82%   |
| 3.01-4.0   | 33        | 5%      |
| 7.01-8.0   | 22        | 3.33%   |
| 8.01-16.0  | 6         | 0.91%   |
| 5.01-6.0   | 5         | 0.76%   |
| 2.01-3.0   | 4         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 91        | 13.15%  |
| AU Optronics            | 86        | 12.43%  |
| Chimei Innolux          | 67        | 9.68%   |
| LG Display              | 55        | 7.95%   |
| BOE                     | 50        | 7.23%   |
| Goldstar                | 34        | 4.91%   |
| Dell                    | 32        | 4.62%   |
| Hewlett-Packard         | 24        | 3.47%   |
| Acer                    | 23        | 3.32%   |
| Lenovo                  | 19        | 2.75%   |
| Chi Mei Optoelectronics | 19        | 2.75%   |
| Apple                   | 15        | 2.17%   |
| Ancor Communications    | 15        | 2.17%   |
| Sony                    | 11        | 1.59%   |
| BenQ                    | 11        | 1.59%   |
| AOC                     | 11        | 1.59%   |
| Philips                 | 10        | 1.45%   |
| PANDA                   | 10        | 1.45%   |
| ViewSonic               | 8         | 1.16%   |
| Sharp                   | 8         | 1.16%   |
| InfoVision              | 6         | 0.87%   |
| HannStar                | 6         | 0.87%   |
| ASUSTek Computer        | 6         | 0.87%   |
| Iiyama                  | 5         | 0.72%   |
| Fujitsu Siemens         | 5         | 0.72%   |
| Eizo                    | 5         | 0.72%   |
| LG Philips              | 4         | 0.58%   |
| CPT                     | 4         | 0.58%   |
| Vizio                   | 3         | 0.43%   |
| Vestel Elektronik       | 3         | 0.43%   |
| Sceptre Tech            | 3         | 0.43%   |
| MSI                     | 3         | 0.43%   |
| Medion                  | 3         | 0.43%   |
| Panasonic               | 2         | 0.29%   |
| NEC Computers           | 2         | 0.29%   |
| MiTAC                   | 2         | 0.29%   |
| Hitachi                 | 2         | 0.29%   |
| Xiaomi                  | 1         | 0.14%   |
| Videoseven              | 1         | 0.14%   |
| Toshiba                 | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 8         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.71%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.57%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 4         | 0.57%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 3         | 0.43%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 3         | 0.43%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.43%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 3         | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.43%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch                | 2         | 0.29%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                       | 2         | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 2         | 0.29%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch        | 2         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.29%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.29%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                          | 2         | 0.29%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.29%   |
| LG Display LCD Monitor LGD0709 1920x1080 344x194mm 15.5-inch             | 2         | 0.29%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.29%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.29%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.29%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                    | 2         | 0.29%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.29%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch                 | 2         | 0.29%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.29%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 2         | 0.29%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                    | 2         | 0.29%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 294       | 43.75%  |
| 1366x768 (WXGA)    | 138       | 20.54%  |
| 3840x2160 (4K)     | 41        | 6.1%    |
| 2560x1440 (QHD)    | 23        | 3.42%   |
| 1680x1050 (WSXGA+) | 23        | 3.42%   |
| 1600x900 (HD+)     | 23        | 3.42%   |
| 1280x800 (WXGA)    | 22        | 3.27%   |
| 1280x1024 (SXGA)   | 21        | 3.13%   |
| 1440x900 (WXGA+)   | 14        | 2.08%   |
| 1920x1200 (WUXGA)  | 9         | 1.34%   |
| 1600x1200          | 9         | 1.34%   |
| 1024x600           | 8         | 1.19%   |
| 2560x1600          | 5         | 0.74%   |
| 2560x1080          | 5         | 0.74%   |
| 1360x768           | 5         | 0.74%   |
| 1024x768 (XGA)     | 5         | 0.74%   |
| 3840x2400          | 3         | 0.45%   |
| 3440x1440          | 3         | 0.45%   |
| 2880x1800          | 3         | 0.45%   |
| 2160x1440          | 3         | 0.45%   |
| 2256x1504          | 2         | 0.3%    |
| 1400x1050          | 2         | 0.3%    |
| 1280x720 (HD)      | 2         | 0.3%    |
| Unknown            | 2         | 0.3%    |
| 3840x1080          | 1         | 0.15%   |
| 3200x2000          | 1         | 0.15%   |
| 3200x1800 (QHD+)   | 1         | 0.15%   |
| 3000x2000          | 1         | 0.15%   |
| 2736x1824          | 1         | 0.15%   |
| 2048x1536          | 1         | 0.15%   |
| 1920x1440          | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 190       | 27.5%   |
| 13      | 66        | 9.55%   |
| 23      | 48        | 6.95%   |
| 14      | 45        | 6.51%   |
| 27      | 43        | 6.22%   |
| 24      | 41        | 5.93%   |
| 21      | 41        | 5.93%   |
| 17      | 36        | 5.21%   |
| 19      | 17        | 2.46%   |
| 11      | 17        | 2.46%   |
| 31      | 16        | 2.32%   |
| 12      | 15        | 2.17%   |
| 22      | 13        | 1.88%   |
| 18      | 13        | 1.88%   |
| 10      | 11        | 1.59%   |
| Unknown | 11        | 1.59%   |
| 20      | 10        | 1.45%   |
| 16      | 9         | 1.3%    |
| 34      | 8         | 1.16%   |
| 84      | 7         | 1.01%   |
| 65      | 4         | 0.58%   |
| 26      | 4         | 0.58%   |
| 40      | 3         | 0.43%   |
| 32      | 3         | 0.43%   |
| 25      | 3         | 0.43%   |
| 54      | 2         | 0.29%   |
| 46      | 2         | 0.29%   |
| 43      | 2         | 0.29%   |
| 42      | 2         | 0.29%   |
| 74      | 1         | 0.14%   |
| 72      | 1         | 0.14%   |
| 61      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 49      | 1         | 0.14%   |
| 39      | 1         | 0.14%   |
| 37      | 1         | 0.14%   |
| 36      | 1         | 0.14%   |
| 28      | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 270       | 39.53%  |
| 501-600     | 127       | 18.59%  |
| 401-500     | 80        | 11.71%  |
| 201-300     | 76        | 11.13%  |
| 351-400     | 57        | 8.35%   |
| 601-700     | 21        | 3.07%   |
| 701-800     | 12        | 1.76%   |
| 1001-1500   | 11        | 1.61%   |
| Unknown     | 11        | 1.61%   |
| 1501-2000   | 9         | 1.32%   |
| 801-900     | 5         | 0.73%   |
| 901-1000    | 4         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 495       | 77.34%  |
| 16/10   | 81        | 12.66%  |
| 5/4     | 21        | 3.28%   |
| 4/3     | 18        | 2.81%   |
| 3/2     | 10        | 1.56%   |
| 21/9    | 8         | 1.25%   |
| Unknown | 7         | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 188       | 27.49%  |
| 201-250        | 121       | 17.69%  |
| 81-90          | 86        | 12.57%  |
| 301-350        | 45        | 6.58%   |
| 151-200        | 40        | 5.85%   |
| 351-500        | 28        | 4.09%   |
| 121-130        | 27        | 3.95%   |
| 71-80          | 25        | 3.65%   |
| More than 1000 | 17        | 2.49%   |
| 51-60          | 17        | 2.49%   |
| 141-150        | 15        | 2.19%   |
| 61-70          | 14        | 2.05%   |
| 251-300        | 14        | 2.05%   |
| 501-1000       | 12        | 1.75%   |
| 41-50          | 11        | 1.61%   |
| Unknown        | 11        | 1.61%   |
| 111-120        | 8         | 1.17%   |
| 91-100         | 3         | 0.44%   |
| 131-140        | 2         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 238       | 35.52%  |
| 121-160       | 188       | 28.06%  |
| 101-120       | 168       | 25.07%  |
| 161-240       | 37        | 5.52%   |
| 1-50          | 15        | 2.24%   |
| More than 240 | 13        | 1.94%   |
| Unknown       | 11        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 544       | 82.3%   |
| 2     | 89        | 13.46%  |
| 0     | 23        | 3.48%   |
| 3     | 5         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 336       | 33.43%  |
| Intel                             | 312       | 31.04%  |
| Qualcomm Atheros                  | 118       | 11.74%  |
| Broadcom                          | 66        | 6.57%   |
| MediaTek                          | 21        | 2.09%   |
| TP-Link                           | 17        | 1.69%   |
| Broadcom Limited                  | 15        | 1.49%   |
| Ralink Technology                 | 11        | 1.09%   |
| Marvell Technology Group          | 11        | 1.09%   |
| Ralink                            | 10        | 1%      |
| Nvidia                            | 10        | 1%      |
| ASIX Electronics                  | 7         | 0.7%    |
| Samsung Electronics               | 6         | 0.6%    |
| Sierra Wireless                   | 4         | 0.4%    |
| OPPO Electronics                  | 4         | 0.4%    |
| Motorola PCS                      | 4         | 0.4%    |
| Microsoft                         | 4         | 0.4%    |
| Qualcomm Atheros Communications   | 3         | 0.3%    |
| Huawei Technologies               | 3         | 0.3%    |
| Ericsson Business Mobile Networks | 3         | 0.3%    |
| AVM                               | 3         | 0.3%    |
| Attansic Technology               | 3         | 0.3%    |
| Xiaomi                            | 2         | 0.2%    |
| VIA Technologies                  | 2         | 0.2%    |
| NetGear                           | 2         | 0.2%    |
| Linksys                           | 2         | 0.2%    |
| JMicron Technology                | 2         | 0.2%    |
| Edimax Technology                 | 2         | 0.2%    |
| Dell                              | 2         | 0.2%    |
| D-Link System                     | 2         | 0.2%    |
| D-Link                            | 2         | 0.2%    |
| ASUSTek Computer                  | 2         | 0.2%    |
| ZyDAS                             | 1         | 0.1%    |
| U-Blox                            | 1         | 0.1%    |
| Sweex                             | 1         | 0.1%    |
| Qualcomm Technologies             | 1         | 0.1%    |
| Qualcomm                          | 1         | 0.1%    |
| Mercucys                          | 1         | 0.1%    |
| Lenovo                            | 1         | 0.1%    |
| IMC Networks                      | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 228       | 19.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 36        | 3.03%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 22        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 20        | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 18        | 1.52%   |
| Intel Wireless 8260                                                     | 17        | 1.43%   |
| Intel Wireless 8265 / 8275                                              | 16        | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 1.26%   |
| Intel Wireless 7260                                                     | 15        | 1.26%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 1.26%   |
| Intel Ethernet Connection I217-LM                                       | 15        | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.18%   |
| Intel Wireless 3165                                                     | 14        | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                       | 13        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 1.09%   |
| Intel Ethernet Controller I225-V                                        | 12        | 1.01%   |
| Intel Wireless 7265                                                     | 11        | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.93%   |
| Intel Wireless-AC 9260                                                  | 10        | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 8         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.67%   |
| Intel I211 Gigabit Network Connection                                   | 8         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.59%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.59%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 7         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 6         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 240       | 42.7%   |
| Realtek Semiconductor           | 93        | 16.55%  |
| Qualcomm Atheros                | 89        | 15.84%  |
| Broadcom                        | 44        | 7.83%   |
| MediaTek                        | 20        | 3.56%   |
| TP-Link                         | 15        | 2.67%   |
| Ralink Technology               | 11        | 1.96%   |
| Ralink                          | 10        | 1.78%   |
| Broadcom Limited                | 10        | 1.78%   |
| Sierra Wireless                 | 4         | 0.71%   |
| Qualcomm Atheros Communications | 3         | 0.53%   |
| AVM                             | 3         | 0.53%   |
| NetGear                         | 2         | 0.36%   |
| Microsoft                       | 2         | 0.36%   |
| Linksys                         | 2         | 0.36%   |
| Edimax Technology               | 2         | 0.36%   |
| D-Link                          | 2         | 0.36%   |
| ASUSTek Computer                | 2         | 0.36%   |
| ZyDAS                           | 1         | 0.18%   |
| Sweex                           | 1         | 0.18%   |
| Qualcomm Technologies           | 1         | 0.18%   |
| Mercucys                        | 1         | 0.18%   |
| Marvell Technology Group        | 1         | 0.18%   |
| IMC Networks                    | 1         | 0.18%   |
| Hewlett-Packard                 | 1         | 0.18%   |
| D-Link System                   | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 23        | 4.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 20        | 3.55%   |
| Intel Wireless 8260                                                     | 17        | 3.01%   |
| Intel Wireless 8265 / 8275                                              | 16        | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 2.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.66%   |
| Intel Wireless 7260                                                     | 15        | 2.66%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 2.48%   |
| Intel Wireless 3165                                                     | 14        | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 2.3%    |
| Intel Wireless 7265                                                     | 11        | 1.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 1.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.95%   |
| Intel Wireless-AC 9260                                                  | 10        | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 1.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 8         | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 1.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 1.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.24%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.24%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.24%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.06%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.06%   |
| Realtek 802.11ac NIC                                                    | 5         | 0.89%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.89%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 298       | 49.83%  |
| Intel                    | 159       | 26.59%  |
| Qualcomm Atheros         | 42        | 7.02%   |
| Broadcom                 | 33        | 5.52%   |
| Nvidia                   | 10        | 1.67%   |
| Marvell Technology Group | 10        | 1.67%   |
| ASIX Electronics         | 7         | 1.17%   |
| Samsung Electronics      | 6         | 1%      |
| Broadcom Limited         | 5         | 0.84%   |
| OPPO Electronics         | 4         | 0.67%   |
| Motorola PCS             | 3         | 0.5%    |
| Attansic Technology      | 3         | 0.5%    |
| Xiaomi                   | 2         | 0.33%   |
| VIA Technologies         | 2         | 0.33%   |
| TP-Link                  | 2         | 0.33%   |
| Microsoft                | 2         | 0.33%   |
| JMicron Technology       | 2         | 0.33%   |
| Qualcomm                 | 1         | 0.17%   |
| MediaTek                 | 1         | 0.17%   |
| Lenovo                   | 1         | 0.17%   |
| Huawei Technologies      | 1         | 0.17%   |
| Foxconn / Hon Hai        | 1         | 0.17%   |
| D-Link System            | 1         | 0.17%   |
| Aquantia                 | 1         | 0.17%   |
| Apple                    | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 228       | 37.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 5.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 3.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 2.95%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 2.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 2.13%   |
| Intel Ethernet Controller I225-V                                  | 12        | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 8         | 1.31%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7         | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.82%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.82%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.65%   |
| OPPO 8                                                            | 4         | 0.65%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.49%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.49%   |
| Motorola PCS moto g51 5G                                          | 3         | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.49%   |
| Intel Ethernet Connection (16) I219-LM                            | 3         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 566       | 51.5%   |
| WiFi     | 520       | 47.32%  |
| Modem    | 11        | 1%      |
| Unknown  | 2         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 406       | 61.24%  |
| Ethernet | 256       | 38.61%  |
| Unknown  | 1         | 0.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 380       | 58.19%  |
| 1     | 245       | 37.52%  |
| 0     | 14        | 2.14%   |
| 3     | 12        | 1.84%   |
| 12    | 1         | 0.15%   |
| 4     | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 526       | 79.94%  |
| Yes  | 132       | 20.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 180       | 44.33%  |
| Realtek Semiconductor           | 39        | 9.61%   |
| Qualcomm Atheros Communications | 32        | 7.88%   |
| Broadcom                        | 25        | 6.16%   |
| Cambridge Silicon Radio         | 22        | 5.42%   |
| Apple                           | 20        | 4.93%   |
| IMC Networks                    | 16        | 3.94%   |
| Foxconn / Hon Hai               | 16        | 3.94%   |
| Lite-On Technology              | 14        | 3.45%   |
| Hewlett-Packard                 | 8         | 1.97%   |
| MediaTek                        | 7         | 1.72%   |
| Dell                            | 7         | 1.72%   |
| ASUSTek Computer                | 5         | 1.23%   |
| Toshiba                         | 4         | 0.99%   |
| Ralink                          | 3         | 0.74%   |
| Alps Electric                   | 3         | 0.74%   |
| TP-Link                         | 2         | 0.49%   |
| Realtek                         | 1         | 0.25%   |
| Ralink Technology               | 1         | 0.25%   |
| Marvell Semiconductor           | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 74        | 18.23%  |
| Realtek Bluetooth Radio                                                             | 29        | 7.14%   |
| Intel AX201 Bluetooth                                                               | 26        | 6.4%    |
| Intel AX200 Bluetooth                                                               | 23        | 5.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 22        | 5.42%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 3.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 3.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 10        | 2.46%   |
| Intel Bluetooth Device                                                              | 10        | 2.46%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 1.97%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 1.97%   |
| Apple Bluetooth Host Controller                                                     | 8         | 1.97%   |
| MediaTek Wireless_Device                                                            | 7         | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 1.72%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.72%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 1.72%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.48%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.23%   |
| IMC Networks Wireless_Device                                                        | 5         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.99%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 0.99%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 0.99%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.74%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 0.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 0.74%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.74%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.74%   |
| TP-Link UB5A Adapter                                                                | 2         | 0.49%   |
| Lite-On Wireless_Device                                                             | 2         | 0.49%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 478       | 54.01%  |
| AMD                        | 170       | 19.21%  |
| Nvidia                     | 148       | 16.72%  |
| C-Media Electronics        | 12        | 1.36%   |
| Creative Labs              | 10        | 1.13%   |
| Texas Instruments          | 5         | 0.56%   |
| JMTek                      | 5         | 0.56%   |
| VIA Technologies           | 4         | 0.45%   |
| Realtek Semiconductor      | 4         | 0.45%   |
| GN Netcom                  | 3         | 0.34%   |
| Focusrite-Novation         | 3         | 0.34%   |
| ROCCAT                     | 2         | 0.23%   |
| Microsoft                  | 2         | 0.23%   |
| Logitech                   | 2         | 0.23%   |
| Kingston Technology        | 2         | 0.23%   |
| Generalplus Technology     | 2         | 0.23%   |
| BR23                       | 2         | 0.23%   |
| BEHRINGER International    | 2         | 0.23%   |
| Apple                      | 2         | 0.23%   |
| ULi Electronics            | 1         | 0.11%   |
| TerraTec Electronic        | 1         | 0.11%   |
| Tenx Technology            | 1         | 0.11%   |
| SteelSeries ApS            | 1         | 0.11%   |
| Shenzhen Riitek Technology | 1         | 0.11%   |
| Setek Elektronik           | 1         | 0.11%   |
| Schiit Audio               | 1         | 0.11%   |
| Razer USA                  | 1         | 0.11%   |
| Plantronics                | 1         | 0.11%   |
| Philips (or NXP)           | 1         | 0.11%   |
| Mark of the Unicorn        | 1         | 0.11%   |
| M-Audio                    | 1         | 0.11%   |
| LG Electronics             | 1         | 0.11%   |
| Lenovo                     | 1         | 0.11%   |
| GYROCOM C&C                | 1         | 0.11%   |
| Guillemot                  | 1         | 0.11%   |
| Giga-Byte Technology       | 1         | 0.11%   |
| Fortemedia                 | 1         | 0.11%   |
| FIFINE 683 Microphone      | 1         | 0.11%   |
| Ensoniq                    | 1         | 0.11%   |
| Emotiva                    | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 62        | 5.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 54        | 5.21%   |
| Intel Sunrise Point-LP HD Audio                                            | 48        | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 48        | 4.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 35        | 3.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30        | 2.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 28        | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24        | 2.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 23        | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 22        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 20        | 1.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 1.83%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 17        | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16        | 1.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 1.35%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12        | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 0.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 0.97%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 9         | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9         | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 8         | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8         | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 0.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 0.77%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8         | 0.77%   |
| Nvidia Audio device                                                        | 7         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 149       | 19.68%  |
| SK hynix                       | 129       | 17.04%  |
| Unknown                        | 102       | 13.47%  |
| Kingston                       | 79        | 10.44%  |
| Micron Technology              | 63        | 8.32%   |
| Crucial                        | 43        | 5.68%   |
| Corsair                        | 38        | 5.02%   |
| G.Skill                        | 22        | 2.91%   |
| A-DATA Technology              | 17        | 2.25%   |
| Ramaxel Technology             | 16        | 2.11%   |
| Elpida                         | 15        | 1.98%   |
| Unknown (ABCD)                 | 13        | 1.72%   |
| Unknown                        | 10        | 1.32%   |
| Nanya Technology               | 8         | 1.06%   |
| Transcend                      | 7         | 0.92%   |
| Smart                          | 5         | 0.66%   |
| Patriot                        | 5         | 0.66%   |
| Apacer                         | 4         | 0.53%   |
| Teikon                         | 2         | 0.26%   |
| Team                           | 2         | 0.26%   |
| PNY                            | 2         | 0.26%   |
| Lexar Co Limited               | 2         | 0.26%   |
| CSX                            | 2         | 0.26%   |
| Avant                          | 2         | 0.26%   |
| Wilk                           | 1         | 0.13%   |
| Unknown (F301)                 | 1         | 0.13%   |
| Unknown (AB)                   | 1         | 0.13%   |
| Unknown (0x0E9D)               | 1         | 0.13%   |
| Unifosa                        | 1         | 0.13%   |
| TRS STAR                       | 1         | 0.13%   |
| Timetec                        | 1         | 0.13%   |
| RZX                            | 1         | 0.13%   |
| Qumo                           | 1         | 0.13%   |
| Patriot Memory (PDP Systems)   | 1         | 0.13%   |
| OCZ                            | 1         | 0.13%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.13%   |
| Innodisk                       | 1         | 0.13%   |
| High Bridge                    | 1         | 0.13%   |
| Hewlett-Packard                | 1         | 0.13%   |
| Golden Empire                  | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 10        | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 9         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.73%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 0.73%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.61%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.61%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.61%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 5         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 4         | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.49%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 4         | 0.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 3         | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 3         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 3         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.37%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 3         | 0.37%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 0.37%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.37%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.37%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.37%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 264       | 40.18%  |
| DDR4    | 244       | 37.14%  |
| DDR2    | 42        | 6.39%   |
| LPDDR4  | 24        | 3.65%   |
| SDRAM   | 20        | 3.04%   |
| Unknown | 20        | 3.04%   |
| DDR     | 16        | 2.44%   |
| LPDDR3  | 12        | 1.83%   |
| DDR5    | 8         | 1.22%   |
| DRAM    | 4         | 0.61%   |
| LPDDR5  | 3         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 426       | 65.04%  |
| DIMM         | 193       | 29.47%  |
| Row Of Chips | 29        | 4.43%   |
| Chip         | 4         | 0.61%   |
| Unknown      | 3         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 235       | 32.46%  |
| 4096  | 228       | 31.49%  |
| 2048  | 115       | 15.88%  |
| 16384 | 86        | 11.88%  |
| 1024  | 39        | 5.39%   |
| 32768 | 14        | 1.93%   |
| 512   | 6         | 0.83%   |
| 256   | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 153       | 21.52%  |
| 3200    | 96        | 13.5%   |
| 2667    | 69        | 9.7%    |
| 1333    | 68        | 9.56%   |
| 2400    | 46        | 6.47%   |
| 1334    | 36        | 5.06%   |
| Unknown | 29        | 4.08%   |
| 2133    | 26        | 3.66%   |
| 667     | 25        | 3.52%   |
| 800     | 17        | 2.39%   |
| 1067    | 15        | 2.11%   |
| 3600    | 14        | 1.97%   |
| 1867    | 13        | 1.83%   |
| 533     | 8         | 1.13%   |
| 3266    | 7         | 0.98%   |
| 3000    | 7         | 0.98%   |
| 4267    | 5         | 0.7%    |
| 4199    | 5         | 0.7%    |
| 2933    | 5         | 0.7%    |
| 1800    | 5         | 0.7%    |
| 4800    | 4         | 0.56%   |
| 2666    | 4         | 0.56%   |
| 400     | 4         | 0.56%   |
| 333     | 4         | 0.56%   |
| 6000    | 3         | 0.42%   |
| 3733    | 3         | 0.42%   |
| 3533    | 3         | 0.42%   |
| 2048    | 3         | 0.42%   |
| 1639    | 3         | 0.42%   |
| 49926   | 2         | 0.28%   |
| 8400    | 2         | 0.28%   |
| 6400    | 2         | 0.28%   |
| 3466    | 2         | 0.28%   |
| 3400    | 2         | 0.28%   |
| 2800    | 2         | 0.28%   |
| 1866    | 2         | 0.28%   |
| 975     | 2         | 0.28%   |
| 5800    | 1         | 0.14%   |
| 5500    | 1         | 0.14%   |
| 4266    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 5         | 27.78%  |
| Canon                 | 4         | 22.22%  |
| Brother Industries    | 4         | 22.22%  |
| Seiko Epson           | 1         | 5.56%   |
| Samsung Electronics   | 1         | 5.56%   |
| Lexmark International | 1         | 5.56%   |
| Konica Minolta        | 1         | 5.56%   |
| Dymo-CoStar           | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon MF641C                       | 2         | 11.11%  |
| Brother DCP-L2540DW                | 2         | 11.11%  |
| Seiko Epson L380 Series            | 1         | 5.56%   |
| Samsung ML-1610 Mono Laser Printer | 1         | 5.56%   |
| Lexmark International CS417dn      | 1         | 5.56%   |
| Konica Minolta 206                 | 1         | 5.56%   |
| HP LaserJet P2055 series           | 1         | 5.56%   |
| HP LaserJet M101-M106              | 1         | 5.56%   |
| HP LaserJet 1022                   | 1         | 5.56%   |
| HP ENVY 4500 series                | 1         | 5.56%   |
| HP Deskjet 1510                    | 1         | 5.56%   |
| Dymo-CoStar LabelWriter 450        | 1         | 5.56%   |
| Canon MG5700 series                | 1         | 5.56%   |
| Canon LiDE 400                     | 1         | 5.56%   |
| Brother MFC-7340                   | 1         | 5.56%   |
| Brother HL-2150N series            | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 5         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 20%     |
| Canon CanoScan LiDE 700F           | 1         | 20%     |
| Canon CanoScan LIDE 25             | 1         | 20%     |
| Canon CanoScan LiDE 210            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 80        | 20.15%  |
| Microdia                               | 33        | 8.31%   |
| Realtek Semiconductor                  | 32        | 8.06%   |
| IMC Networks                           | 31        | 7.81%   |
| Sunplus Innovation Technology          | 23        | 5.79%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 5.54%   |
| Bison Electronics                      | 21        | 5.29%   |
| Quanta                                 | 19        | 4.79%   |
| Logitech                               | 16        | 4.03%   |
| Apple                                  | 13        | 3.27%   |
| Suyin                                  | 12        | 3.02%   |
| Lite-On Technology                     | 12        | 3.02%   |
| Luxvisions Innotech Limited            | 11        | 2.77%   |
| Acer                                   | 11        | 2.77%   |
| Lenovo                                 | 8         | 2.02%   |
| Microsoft                              | 7         | 1.76%   |
| Alcor Micro                            | 6         | 1.51%   |
| Silicon Motion                         | 5         | 1.26%   |
| Ricoh                                  | 5         | 1.26%   |
| Z-Star Microelectronics                | 3         | 0.76%   |
| Syntek                                 | 3         | 0.76%   |
| Hewlett-Packard                        | 2         | 0.5%    |
| Generalplus Technology                 | 2         | 0.5%    |
| GEMBIRD                                | 2         | 0.5%    |
| Y Media                                | 1         | 0.25%   |
| Xiongmai                               | 1         | 0.25%   |
| WaveRider Communications               | 1         | 0.25%   |
| Trust                                  | 1         | 0.25%   |
| Sunplus Technology                     | 1         | 0.25%   |
| Sonix Technology                       | 1         | 0.25%   |
| Samsung Electronics                    | 1         | 0.25%   |
| Primax Electronics                     | 1         | 0.25%   |
| Pixart Imaging                         | 1         | 0.25%   |
| Novatek Microelectronics               | 1         | 0.25%   |
| LG Electronics                         | 1         | 0.25%   |
| Importek                               | 1         | 0.25%   |
| icSpring                               | 1         | 0.25%   |
| Huawei Technologies                    | 1         | 0.25%   |
| Goodong Industry                       | 1         | 0.25%   |
| Cubeternet                             | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 20        | 5.03%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 13        | 3.27%   |
| Realtek Integrated_Webcam_HD                                | 10        | 2.51%   |
| Microdia Integrated_Webcam_HD                               | 10        | 2.51%   |
| Sunplus Integrated_Webcam_HD                                | 6         | 1.51%   |
| Lite-On Integrated Camera                                   | 6         | 1.51%   |
| Chicony HD WebCam                                           | 6         | 1.51%   |
| IMC Networks Integrated Camera                              | 5         | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 5         | 1.26%   |
| Bison Integrated Camera                                     | 5         | 1.26%   |
| Apple Built-in iSight                                       | 5         | 1.26%   |
| Sunplus HD WebCam                                           | 4         | 1.01%   |
| Sunplus Asus Webcam                                         | 4         | 1.01%   |
| Realtek USB2.0 HD UVC WebCam                                | 4         | 1.01%   |
| Realtek USB Camera                                          | 4         | 1.01%   |
| Quanta HD User Facing                                       | 4         | 1.01%   |
| Microsoft LifeCam HD-3000                                   | 4         | 1.01%   |
| Microdia USB 2.0 Camera                                     | 4         | 1.01%   |
| Microdia Integrated_Webcam_FHD                              | 4         | 1.01%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 4         | 1.01%   |
| Logitech Webcam C930e                                       | 4         | 1.01%   |
| Lenovo Integrated Webcam [R5U877]                           | 4         | 1.01%   |
| Chicony USB 2.0 Camera                                      | 4         | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 1.01%   |
| Chicony HP TrueVision HD Camera                             | 4         | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 4         | 1.01%   |
| Bison BisonCam, NB Pro                                      | 4         | 1.01%   |
| Apple FaceTime HD Camera (Built-in)                         | 4         | 1.01%   |
| Acer BisonCam,NB Pro                                        | 4         | 1.01%   |
| Syntek EasyCamera                                           | 3         | 0.75%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 0.75%   |
| Ricoh USB2.0 Camera                                         | 3         | 0.75%   |
| Quanta HP TrueVision HD Camera                              | 3         | 0.75%   |
| Microdia Integrated Webcam                                  | 3         | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 3         | 0.75%   |
| Logitech Webcam C270                                        | 3         | 0.75%   |
| Lenovo Integrated Webcam                                    | 3         | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 0.75%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 0.75%   |
| Chicony HD User Facing                                      | 3         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 22        | 29.73%  |
| Synaptics                          | 15        | 20.27%  |
| Shenzhen Goodix Technology         | 10        | 13.51%  |
| Upek                               | 8         | 10.81%  |
| AuthenTec                          | 7         | 9.46%   |
| Elan Microelectronics              | 5         | 6.76%   |
| STMicroelectronics                 | 2         | 2.7%    |
| LighTuning Technology              | 2         | 2.7%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.35%   |
| Microsoft                          | 1         | 1.35%   |
| Focal-systems.Corp                 | 1         | 1.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 8.11%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 6         | 8.11%   |
| Shenzhen Goodix  FingerPrint Device                             | 6         | 8.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 6.76%   |
| AuthenTec AES2810                                               | 4         | 5.41%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 4.05%   |
| Validity Sensors Synaptics WBDI                                 | 3         | 4.05%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 4.05%   |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 4.05%   |
| Elan ELAN:Fingerprint                                           | 3         | 4.05%   |
| Upek TCS5B Fingerprint sensor                                   | 2         | 2.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 2         | 2.7%    |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 2.7%    |
| STMicroelectronics Fingerprint Reader                           | 2         | 2.7%    |
| Elan ELAN:ARM-M4                                                | 2         | 2.7%    |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 2.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 1.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.35%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.35%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.35%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.35%   |
| Synaptics WBDI Fingerprint Reader USB 102                       | 1         | 1.35%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.35%   |
| Synaptics UWP WBDI                                              | 1         | 1.35%   |
| Synaptics  WBDI                                                 | 1         | 1.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.35%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.35%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.35%   |
| Microsoft Fingerprint Reader                                    | 1         | 1.35%   |
| LighTuning Fingerprint Reader                                   | 1         | 1.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 1.35%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.35%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 1.35%   |
| Unknown                                                         | 1         | 1.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 15        | 45.45%  |
| Alcor Micro           | 11        | 33.33%  |
| Lenovo                | 3         | 9.09%   |
| O2 Micro              | 2         | 6.06%   |
| Advanced Card Systems | 2         | 6.06%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 33.33%  |
| Broadcom 58200                                                               | 6         | 18.18%  |
| Broadcom 5880                                                                | 5         | 15.15%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 9.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 6.06%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.03%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 3.03%   |
| Advanced Card Systems ACR122U                                                | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 444       | 67.07%  |
| 1     | 162       | 24.47%  |
| 2     | 48        | 7.25%   |
| 3     | 8         | 1.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 108       | 40.75%  |
| Fingerprint reader       | 74        | 27.92%  |
| Chipcard                 | 30        | 11.32%  |
| Net/wireless             | 15        | 5.66%   |
| Multimedia controller    | 10        | 3.77%   |
| Communication controller | 9         | 3.4%    |
| Camera                   | 5         | 1.89%   |
| Unassigned class         | 3         | 1.13%   |
| Storage                  | 3         | 1.13%   |
| Net/ethernet             | 2         | 0.75%   |
| Flash memory             | 2         | 0.75%   |
| Bluetooth                | 2         | 0.75%   |
| Sound                    | 1         | 0.38%   |
| Dvb card                 | 1         | 0.38%   |


EndeavourOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

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
| Lenovo        | ThinkPad E550 20DF0030US    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| Eluktronic... | Prometheus XVII             | [0797cebf2d](https://linux-hardware.org/?probe=0797cebf2d) | Feb 26, 2022 |
| Eluktronic... | Prometheus XVII             | [148eddd1ee](https://linux-hardware.org/?probe=148eddd1ee) | Feb 25, 2022 |
| Dell          | Latitude 3420               | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Eluktronic... | Prometheus XVII             | [36436d1aff](https://linux-hardware.org/?probe=36436d1aff) | Feb 17, 2022 |
| HUAWEI        | HLYL-WXX9                   | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| ASUSTek       | UX490UA                     | [5e40078555](https://linux-hardware.org/?probe=5e40078555) | Feb 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| Dell          | G3 3500                     | [92ee625013](https://linux-hardware.org/?probe=92ee625013) | Feb 09, 2022 |
| HP            | Pavilion 10 TS              | [1228be8404](https://linux-hardware.org/?probe=1228be8404) | Feb 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Dell          | Latitude E4310              | [ef92697af7](https://linux-hardware.org/?probe=ef92697af7) | Feb 07, 2022 |
| Dell          | Latitude E6400              | [919eb44cc5](https://linux-hardware.org/?probe=919eb44cc5) | Feb 07, 2022 |
| Acer          | Aspire V5-471               | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| HP            | Pavilion dv7                | [28bb1241de](https://linux-hardware.org/?probe=28bb1241de) | Feb 06, 2022 |
| Notebook      | NH5x_7xDPx                  | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| HP            | Pavilion g6                 | [c2b7d7cdd1](https://linux-hardware.org/?probe=c2b7d7cdd1) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| HP            | 250 G7 Notebook PC          | [b8f0614b9c](https://linux-hardware.org/?probe=b8f0614b9c) | Feb 01, 2022 |
| HP            | Pavilion g6                 | [be25fc4f46](https://linux-hardware.org/?probe=be25fc4f46) | Feb 01, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| ASUSTek       | G751JT                      | [ffadc47152](https://linux-hardware.org/?probe=ffadc47152) | Jan 25, 2022 |
| ASUSTek       | G751JT                      | [fabdb73d12](https://linux-hardware.org/?probe=fabdb73d12) | Jan 25, 2022 |
| Dell          | Inspiron 3542               | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [cc0c86531b](https://linux-hardware.org/?probe=cc0c86531b) | Jan 22, 2022 |
| ASUSTek       | K45VD                       | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Acer          | Swift SF514-54T             | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| HUAWEI        | MACH-WX9                    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [b1600a4c5c](https://linux-hardware.org/?probe=b1600a4c5c) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c22ba841f6](https://linux-hardware.org/?probe=c22ba841f6) | Jan 06, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| Dell          | Inspiron 5520               | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Timi          | A35S                        | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |
| Dell          | Inspiron 3542               | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Dell          | Precision 5560              | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [b608797946](https://linux-hardware.org/?probe=b608797946) | Dec 28, 2021 |
| HP            | Laptop 14-fq0xxx            | [756df875af](https://linux-hardware.org/?probe=756df875af) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | [cd01eec1a8](https://linux-hardware.org/?probe=cd01eec1a8) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | [4d153ddb81](https://linux-hardware.org/?probe=4d153ddb81) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [deb1a17957](https://linux-hardware.org/?probe=deb1a17957) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [ca89ed6eab](https://linux-hardware.org/?probe=ca89ed6eab) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| Unknown       | Unknown                     | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| MSI           | Modern 14 B5M               | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0LU0... | [ab6c683160](https://linux-hardware.org/?probe=ab6c683160) | Dec 16, 2021 |
| Dell          | Inspiron 5558               | [16daa16444](https://linux-hardware.org/?probe=16daa16444) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| HP            | 255 G7 Notebook PC          | [a34aa5357b](https://linux-hardware.org/?probe=a34aa5357b) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| MSI           | Prestige 15 A10SC           | [706fc926ca](https://linux-hardware.org/?probe=706fc926ca) | Dec 08, 2021 |
| Dell          | Latitude 7480               | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| Unknown       | Unknown                     | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| Framework     | Laptop                      | [c1a31372f4](https://linux-hardware.org/?probe=c1a31372f4) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Apple         | MacBookAir6,2               | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | Bravo 15 B5DD               | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Unknown       | Unknown                     | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| MSI           | GS63VR 6RF                  | [2d9061c72e](https://linux-hardware.org/?probe=2d9061c72e) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| HP            | 15 TS                       | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Dell          | XPS 13 9350                 | [ec54ffae7a](https://linux-hardware.org/?probe=ec54ffae7a) | Nov 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [778d32ce4b](https://linux-hardware.org/?probe=778d32ce4b) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [9fc3f12603](https://linux-hardware.org/?probe=9fc3f12603) | Nov 16, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [8382b9a420](https://linux-hardware.org/?probe=8382b9a420) | Nov 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [c11672a55e](https://linux-hardware.org/?probe=c11672a55e) | Nov 11, 2021 |
| ASUSTek       | G751JT                      | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [e95d2fa980](https://linux-hardware.org/?probe=e95d2fa980) | Nov 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [85dff2829f](https://linux-hardware.org/?probe=85dff2829f) | Nov 03, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [222ce004da](https://linux-hardware.org/?probe=222ce004da) | Nov 01, 2021 |
| ASUSTek       | G751JT                      | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3fcea4d382](https://linux-hardware.org/?probe=3fcea4d382) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | [cce67d37aa](https://linux-hardware.org/?probe=cce67d37aa) | Oct 28, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [689f9368f1](https://linux-hardware.org/?probe=689f9368f1) | Oct 23, 2021 |
| Apple         | MacBookPro16,2              | [7b3cdda6e2](https://linux-hardware.org/?probe=7b3cdda6e2) | Oct 20, 2021 |
| HP            | ENVY 6                      | [94471889b0](https://linux-hardware.org/?probe=94471889b0) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ff566c77ce](https://linux-hardware.org/?probe=ff566c77ce) | Oct 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [2d3f367fa7](https://linux-hardware.org/?probe=2d3f367fa7) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | [6e745a1ec9](https://linux-hardware.org/?probe=6e745a1ec9) | Oct 17, 2021 |
| Dell          | Latitude E6410              | [68d7531397](https://linux-hardware.org/?probe=68d7531397) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | [8d0e93e90f](https://linux-hardware.org/?probe=8d0e93e90f) | Oct 16, 2021 |
| Lenovo        | Z50-70 20354                | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Dell          | Precision M4400             | [bae8becab1](https://linux-hardware.org/?probe=bae8becab1) | Oct 11, 2021 |
| Google        | Kindred                     | [9420945432](https://linux-hardware.org/?probe=9420945432) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [c486155f48](https://linux-hardware.org/?probe=c486155f48) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [52e0d626fa](https://linux-hardware.org/?probe=52e0d626fa) | Oct 10, 2021 |
| Dell          | Latitude E6410              | [ebfe78c927](https://linux-hardware.org/?probe=ebfe78c927) | Oct 08, 2021 |
| Dell          | G3 3500                     | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | Z50-70 20354                | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0923a8b728](https://linux-hardware.org/?probe=0923a8b728) | Oct 05, 2021 |
| Dell          | Precision M4400             | [ab43bad624](https://linux-hardware.org/?probe=ab43bad624) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9c8bc954a7](https://linux-hardware.org/?probe=9c8bc954a7) | Oct 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [dc91b564a8](https://linux-hardware.org/?probe=dc91b564a8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [86c4b5769f](https://linux-hardware.org/?probe=86c4b5769f) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [263233be76](https://linux-hardware.org/?probe=263233be76) | Sep 28, 2021 |
| HP            | Pavilion dv6                | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| Lenovo        | ThinkPad T480 20L6S3S500    | [067f3cf110](https://linux-hardware.org/?probe=067f3cf110) | Sep 26, 2021 |
| Lenovo        | ThinkPad T470 20HES2SF00    | [9cf10e22a6](https://linux-hardware.org/?probe=9cf10e22a6) | Sep 25, 2021 |
| Lenovo        | ThinkPad E460 20ET004LGE    | [b64e2c4a07](https://linux-hardware.org/?probe=b64e2c4a07) | Sep 25, 2021 |
| Dell          | Precision 3560              | [d9b527db16](https://linux-hardware.org/?probe=d9b527db16) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1e1e40ce8b](https://linux-hardware.org/?probe=1e1e40ce8b) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [711e2e3960](https://linux-hardware.org/?probe=711e2e3960) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | [3a7231ce53](https://linux-hardware.org/?probe=3a7231ce53) | Sep 17, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [8dfad66767](https://linux-hardware.org/?probe=8dfad66767) | Sep 16, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | [3e845646c9](https://linux-hardware.org/?probe=3e845646c9) | Sep 15, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | [0fe0fa66d6](https://linux-hardware.org/?probe=0fe0fa66d6) | Sep 14, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | [d5e170957e](https://linux-hardware.org/?probe=d5e170957e) | Sep 14, 2021 |
| Acer          | Nitro AN515-54              | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| AMI           | Intel                       | [49dd022241](https://linux-hardware.org/?probe=49dd022241) | Sep 10, 2021 |
| Razer         | Blade 15 Advanced Model ... | [0c83ae1e11](https://linux-hardware.org/?probe=0c83ae1e11) | Sep 10, 2021 |
| Lenovo        | Legion Y545 81Q6            | [167df4c15e](https://linux-hardware.org/?probe=167df4c15e) | Sep 09, 2021 |
| Dell          | Latitude E4310              | [34c3815468](https://linux-hardware.org/?probe=34c3815468) | Sep 02, 2021 |
| TrekStor      | Primebook P14               | [026e7277ee](https://linux-hardware.org/?probe=026e7277ee) | Sep 02, 2021 |
| HP            | Laptop 15s-fq2xxx           | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| Dell          | Precision M4400             | [289a2606bd](https://linux-hardware.org/?probe=289a2606bd) | Sep 02, 2021 |
| Apple         | MacBookAir7,2               | [581b1be43c](https://linux-hardware.org/?probe=581b1be43c) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d3ab28e58e](https://linux-hardware.org/?probe=d3ab28e58e) | Aug 30, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [24a34a526e](https://linux-hardware.org/?probe=24a34a526e) | Aug 28, 2021 |
| Lenovo        | IdeaPad 510S-14IKB 80UV     | [146390e85e](https://linux-hardware.org/?probe=146390e85e) | Aug 25, 2021 |
| ASUSTek       | G752VT                      | [23dea85a93](https://linux-hardware.org/?probe=23dea85a93) | Aug 24, 2021 |
| Dell          | Latitude E7440              | [0de5415ad7](https://linux-hardware.org/?probe=0de5415ad7) | Aug 22, 2021 |
| Dell          | Inspiron 5577               | [ae8d8171a7](https://linux-hardware.org/?probe=ae8d8171a7) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [5d560f16cc](https://linux-hardware.org/?probe=5d560f16cc) | Aug 12, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [9be95b3419](https://linux-hardware.org/?probe=9be95b3419) | Aug 12, 2021 |
| HP            | EliteBook 745 G6            | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Dell          | Inspiron 5570               | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Notebook      | W65_67SZ                    | [ddd6f26db4](https://linux-hardware.org/?probe=ddd6f26db4) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [1ccf2e3d28](https://linux-hardware.org/?probe=1ccf2e3d28) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [b5b8bac74a](https://linux-hardware.org/?probe=b5b8bac74a) | Jul 26, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [12d6be24d7](https://linux-hardware.org/?probe=12d6be24d7) | Jul 25, 2021 |
| Apple         | MacBookAir7,2               | [a5959b657f](https://linux-hardware.org/?probe=a5959b657f) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [f8f9bf0717](https://linux-hardware.org/?probe=f8f9bf0717) | Jul 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7cdf389d4c](https://linux-hardware.org/?probe=7cdf389d4c) | Jul 22, 2021 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [4421b175f7](https://linux-hardware.org/?probe=4421b175f7) | Jul 16, 2021 |
| Acer          | Predator G9-792             | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| Acer          | Aspire A515-43              | [c79cfacd5e](https://linux-hardware.org/?probe=c79cfacd5e) | Jul 05, 2021 |
| Apple         | MacBookPro9,2               | [282a2e2926](https://linux-hardware.org/?probe=282a2e2926) | Jul 04, 2021 |
| Acer          | Nitro AN515-54              | [3be93cbc0c](https://linux-hardware.org/?probe=3be93cbc0c) | Jul 03, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | [181cfa9437](https://linux-hardware.org/?probe=181cfa9437) | Jul 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [a92028f13a](https://linux-hardware.org/?probe=a92028f13a) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | [56a361debf](https://linux-hardware.org/?probe=56a361debf) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | [431df4bc98](https://linux-hardware.org/?probe=431df4bc98) | Jul 01, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [81ccc0c89d](https://linux-hardware.org/?probe=81ccc0c89d) | Jun 29, 2021 |
| Dell          | G7 7588                     | [259694c4a1](https://linux-hardware.org/?probe=259694c4a1) | Jun 27, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [4b70691f2e](https://linux-hardware.org/?probe=4b70691f2e) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [397e22935b](https://linux-hardware.org/?probe=397e22935b) | Jun 25, 2021 |
| HP            | 255 G7 Notebook PC          | [2762be36c4](https://linux-hardware.org/?probe=2762be36c4) | Jun 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d3e7a93219](https://linux-hardware.org/?probe=d3e7a93219) | Jun 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [44a7645f10](https://linux-hardware.org/?probe=44a7645f10) | Jun 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [9e238ebb4f](https://linux-hardware.org/?probe=9e238ebb4f) | Jun 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| HP            | EliteBook Revolve 810       | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | [4c600416f9](https://linux-hardware.org/?probe=4c600416f9) | May 28, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [99ab618bee](https://linux-hardware.org/?probe=99ab618bee) | May 25, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [684dfb967f](https://linux-hardware.org/?probe=684dfb967f) | May 22, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [c18360d17e](https://linux-hardware.org/?probe=c18360d17e) | May 22, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [c1b869c13a](https://linux-hardware.org/?probe=c1b869c13a) | May 22, 2021 |
| Acer          | Swift SF314-51              | [a666be1df5](https://linux-hardware.org/?probe=a666be1df5) | May 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [457597b9d1](https://linux-hardware.org/?probe=457597b9d1) | May 21, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [e18030e5f0](https://linux-hardware.org/?probe=e18030e5f0) | May 20, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [7e5dbc86b9](https://linux-hardware.org/?probe=7e5dbc86b9) | May 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [14b3851754](https://linux-hardware.org/?probe=14b3851754) | May 20, 2021 |
| Notebook      | NS50MU                      | [8e08645823](https://linux-hardware.org/?probe=8e08645823) | May 19, 2021 |
| Lenovo        | ThinkPad P51 20HHCT01WW     | [3f42eaf28b](https://linux-hardware.org/?probe=3f42eaf28b) | May 19, 2021 |
| MSI           | GE72 6QD                    | [7637f1ad9c](https://linux-hardware.org/?probe=7637f1ad9c) | May 19, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [634c63d316](https://linux-hardware.org/?probe=634c63d316) | May 15, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [17af51e9b1](https://linux-hardware.org/?probe=17af51e9b1) | May 14, 2021 |
| HP            | EliteBook 2170p             | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9048b606d2](https://linux-hardware.org/?probe=9048b606d2) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f02e90a00f](https://linux-hardware.org/?probe=f02e90a00f) | May 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | [b3a5056cbf](https://linux-hardware.org/?probe=b3a5056cbf) | May 07, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [365c656e4a](https://linux-hardware.org/?probe=365c656e4a) | May 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [fca3b0c89b](https://linux-hardware.org/?probe=fca3b0c89b) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9e8b256742](https://linux-hardware.org/?probe=9e8b256742) | May 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [e7cd00034c](https://linux-hardware.org/?probe=e7cd00034c) | May 02, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [39f6decf99](https://linux-hardware.org/?probe=39f6decf99) | May 02, 2021 |
| HP            | 255 G4                      | [9070448ace](https://linux-hardware.org/?probe=9070448ace) | May 01, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [3d3ef81b3b](https://linux-hardware.org/?probe=3d3ef81b3b) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Acer          | Extensa 2510                | [1f257d3f4e](https://linux-hardware.org/?probe=1f257d3f4e) | Apr 25, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [764390758a](https://linux-hardware.org/?probe=764390758a) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [eabc0fa5e5](https://linux-hardware.org/?probe=eabc0fa5e5) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [fae6227cfc](https://linux-hardware.org/?probe=fae6227cfc) | Apr 19, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [010a6ef208](https://linux-hardware.org/?probe=010a6ef208) | Apr 14, 2021 |
| Toshiba       | Satellite P750              | [d248a5f049](https://linux-hardware.org/?probe=d248a5f049) | Apr 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Dell          | Inspiron 5391               | [80bf268441](https://linux-hardware.org/?probe=80bf268441) | Apr 08, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [9e5b4c92f4](https://linux-hardware.org/?probe=9e5b4c92f4) | Apr 01, 2021 |
| Toshiba       | Satellite L50D-B            | [6fdb3a7d9e](https://linux-hardware.org/?probe=6fdb3a7d9e) | Mar 31, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [269185aba1](https://linux-hardware.org/?probe=269185aba1) | Mar 28, 2021 |
| Dell          | G7 7588                     | [95e0518b2c](https://linux-hardware.org/?probe=95e0518b2c) | Mar 25, 2021 |
| Dell          | Latitude 5300               | [efd4a051e5](https://linux-hardware.org/?probe=efd4a051e5) | Mar 23, 2021 |
| Lenovo        | ThinkPad L460 20FV002EBR    | [f19448d66f](https://linux-hardware.org/?probe=f19448d66f) | Mar 19, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | [e03adb0720](https://linux-hardware.org/?probe=e03adb0720) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [13dfc4a9af](https://linux-hardware.org/?probe=13dfc4a9af) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [c7fbd818e8](https://linux-hardware.org/?probe=c7fbd818e8) | Mar 16, 2021 |
| Dell          | G5 5505                     | [e8e38279d3](https://linux-hardware.org/?probe=e8e38279d3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [062dfb8010](https://linux-hardware.org/?probe=062dfb8010) | Mar 09, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [eec4ef3dce](https://linux-hardware.org/?probe=eec4ef3dce) | Mar 07, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [bd3a730b32](https://linux-hardware.org/?probe=bd3a730b32) | Mar 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [04c16e80ba](https://linux-hardware.org/?probe=04c16e80ba) | Mar 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [4b204c80ad](https://linux-hardware.org/?probe=4b204c80ad) | Mar 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [ccd6f06e61](https://linux-hardware.org/?probe=ccd6f06e61) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | [88635c9f76](https://linux-hardware.org/?probe=88635c9f76) | Feb 23, 2021 |
| Gigabyte      | AERO 15XV8                  | [c4ecc96eae](https://linux-hardware.org/?probe=c4ecc96eae) | Feb 19, 2021 |
| Apple         | MacBookPro7,1               | [93115f0746](https://linux-hardware.org/?probe=93115f0746) | Feb 14, 2021 |
| Apple         | MacBookPro7,1               | [1bd84f7c03](https://linux-hardware.org/?probe=1bd84f7c03) | Feb 13, 2021 |
| HP            | ZBook 15                    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| ASUSTek       | GL503VM                     | [72f95227fd](https://linux-hardware.org/?probe=72f95227fd) | Feb 11, 2021 |
| ASUSTek       | GL503VM                     | [130e9bdb5c](https://linux-hardware.org/?probe=130e9bdb5c) | Feb 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [43bb3ec644](https://linux-hardware.org/?probe=43bb3ec644) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [5856d93198](https://linux-hardware.org/?probe=5856d93198) | Feb 07, 2021 |
| HP            | ENVY Notebook               | [4f20314e69](https://linux-hardware.org/?probe=4f20314e69) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [311f54d837](https://linux-hardware.org/?probe=311f54d837) | Jan 28, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [a0c3014b22](https://linux-hardware.org/?probe=a0c3014b22) | Jan 17, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [9fd64a3945](https://linux-hardware.org/?probe=9fd64a3945) | Jan 11, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [6499961dbf](https://linux-hardware.org/?probe=6499961dbf) | Jan 09, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [2df429a577](https://linux-hardware.org/?probe=2df429a577) | Jan 06, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [f2b808bdd1](https://linux-hardware.org/?probe=f2b808bdd1) | Dec 24, 2020 |
| MSI           | GL75 Leopard 10SDK          | [8b792fe096](https://linux-hardware.org/?probe=8b792fe096) | Dec 23, 2020 |
| HP            | Laptop 15-db1xxx            | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| HP            | EliteBook Revolve 810       | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| Apple         | MacBookAir4,2               | [a3ebd820e2](https://linux-hardware.org/?probe=a3ebd820e2) | Dec 17, 2020 |
| Alienware     | 14                          | [3211a0e18d](https://linux-hardware.org/?probe=3211a0e18d) | Dec 12, 2020 |
| HP            | 255 G7 Notebook PC          | [75384533dc](https://linux-hardware.org/?probe=75384533dc) | Dec 06, 2020 |
| Dell          | Precision M6600             | [c3eafadf96](https://linux-hardware.org/?probe=c3eafadf96) | Dec 05, 2020 |
| HP            | 255 G7 Notebook PC          | [7e7ad00d75](https://linux-hardware.org/?probe=7e7ad00d75) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | [7e75c8dc00](https://linux-hardware.org/?probe=7e75c8dc00) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | [2381ec1bad](https://linux-hardware.org/?probe=2381ec1bad) | Nov 30, 2020 |
| MSI           | GT80S 6QE                   | [a938950688](https://linux-hardware.org/?probe=a938950688) | Nov 28, 2020 |
| MSI           | GT80S 6QE                   | [a07d34dcff](https://linux-hardware.org/?probe=a07d34dcff) | Nov 28, 2020 |
| Dell          | Precision M6600             | [990be59736](https://linux-hardware.org/?probe=990be59736) | Nov 21, 2020 |
| ASUSTek       | X550CL                      | [5315051a75](https://linux-hardware.org/?probe=5315051a75) | Nov 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2a4a52111f](https://linux-hardware.org/?probe=2a4a52111f) | Nov 21, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [650cf712bb](https://linux-hardware.org/?probe=650cf712bb) | Nov 08, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| Timi          | TM1607                      | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| HP            | Laptop 14-dk1xxx            | [5cdfdbceae](https://linux-hardware.org/?probe=5cdfdbceae) | Oct 26, 2020 |
| HP            | Laptop 14-dk1xxx            | [130d636b9e](https://linux-hardware.org/?probe=130d636b9e) | Oct 26, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [3e19ade739](https://linux-hardware.org/?probe=3e19ade739) | Oct 25, 2020 |
| HP            | Notebook                    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1e6190a4f2](https://linux-hardware.org/?probe=1e6190a4f2) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | [d3265c616b](https://linux-hardware.org/?probe=d3265c616b) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | [01f75c41ed](https://linux-hardware.org/?probe=01f75c41ed) | Oct 20, 2020 |
| Dell          | Inspiron 3493               | [502cfa6428](https://linux-hardware.org/?probe=502cfa6428) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | [459870a593](https://linux-hardware.org/?probe=459870a593) | Oct 14, 2020 |
| ASUSTek       | GL702ZC                     | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [2abc472e43](https://linux-hardware.org/?probe=2abc472e43) | Oct 08, 2020 |
| Acer          | Aspire E5-573               | [89237e04fc](https://linux-hardware.org/?probe=89237e04fc) | Oct 04, 2020 |
| Unknown       | Unknown                     | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4ec2f0a6cc](https://linux-hardware.org/?probe=4ec2f0a6cc) | Sep 29, 2020 |
| Dell          | G3 3579                     | [6853280510](https://linux-hardware.org/?probe=6853280510) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| Acer          | TravelMate P633-M           | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| Dell          | Latitude E6440              | [ddd1e2f728](https://linux-hardware.org/?probe=ddd1e2f728) | Sep 03, 2020 |
| ASUSTek       | UX310UA                     | [90e38ace34](https://linux-hardware.org/?probe=90e38ace34) | Sep 03, 2020 |
| HP            | EliteBook 840 G5            | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [82736e9fa5](https://linux-hardware.org/?probe=82736e9fa5) | Aug 23, 2020 |
| Dell          | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [935afc3dde](https://linux-hardware.org/?probe=935afc3dde) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [fd00cb49a3](https://linux-hardware.org/?probe=fd00cb49a3) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [4830a55da9](https://linux-hardware.org/?probe=4830a55da9) | Jul 27, 2020 |
| Dell          | Latitude 7400               | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| Lenovo        | ThinkPad E595 20NFS0TD00    | [7fbac3cf0a](https://linux-hardware.org/?probe=7fbac3cf0a) | Jul 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [ed0f57c08d](https://linux-hardware.org/?probe=ed0f57c08d) | Jul 14, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [fc1d360821](https://linux-hardware.org/?probe=fc1d360821) | Jun 29, 2020 |
| Dell          | Inspiron 5559               | [a2e2a6cf66](https://linux-hardware.org/?probe=a2e2a6cf66) | May 12, 2020 |
| Lenovo        | G505s 20255                 | [21f31cf2d0](https://linux-hardware.org/?probe=21f31cf2d0) | Apr 21, 2020 |
| HP            | EliteBook 8770w             | [44b687a5ef](https://linux-hardware.org/?probe=44b687a5ef) | Jan 31, 2020 |
| HP            | EliteBook 830 G6            | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Acer          | Aspire ES1-520              | [12a0136c2d](https://linux-hardware.org/?probe=12a0136c2d) | Jan 20, 2020 |
| Notebook      | W65KJ1_KK1                  | [924a887f7d](https://linux-hardware.org/?probe=924a887f7d) | Dec 09, 2019 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [d5c741f8df](https://linux-hardware.org/?probe=d5c741f8df) | Dec 08, 2019 |
| Dell          | Inspiron 7520               | [3477d2f29e](https://linux-hardware.org/?probe=3477d2f29e) | Sep 10, 2019 |
| Dell          | Inspiron 7520               | [80bdb92976](https://linux-hardware.org/?probe=80bdb92976) | Sep 10, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.15.12-arch1-1    | 8         | 3.19%   |
| 5.13.13-arch1-1    | 7         | 2.79%   |
| 5.15.10-arch1-1    | 6         | 2.39%   |
| 5.9.14-arch1-1     | 5         | 1.99%   |
| 5.15.4-arch1-1     | 5         | 1.99%   |
| 5.9.1-arch1-1      | 4         | 1.59%   |
| 5.7.8-arch1-1      | 4         | 1.59%   |
| 5.16.8-arch1-1     | 4         | 1.59%   |
| 5.16.4-arch1-1     | 4         | 1.59%   |
| 5.16.10-arch1-1    | 4         | 1.59%   |
| 5.15.2-arch1-1     | 4         | 1.59%   |
| 5.14.9-arch2-1     | 4         | 1.59%   |
| 5.12.14-arch1-1    | 4         | 1.59%   |
| 5.11.16-arch1-1    | 4         | 1.59%   |
| 5.11.11-arch1-1    | 4         | 1.59%   |
| 5.9.8-arch1-1      | 3         | 1.2%    |
| 5.9.10-arch1-1     | 3         | 1.2%    |
| 5.15.6-zen2-1-zen  | 3         | 1.2%    |
| 5.14.6-arch1-1     | 3         | 1.2%    |
| 5.14.14-arch1-1    | 3         | 1.2%    |
| 5.12.13-arch1-2    | 3         | 1.2%    |
| 5.11.16-zen1-1-zen | 3         | 1.2%    |
| 5.10.15-arch1-1    | 3         | 1.2%    |
| 5.9.2-arch1-1      | 2         | 0.8%    |
| 5.7.10-arch1-1     | 2         | 0.8%    |
| 5.4.2-arch1-1      | 2         | 0.8%    |
| 5.16.5-arch1-1     | 2         | 0.8%    |
| 5.16.2-arch1-1     | 2         | 0.8%    |
| 5.16.0-arch1-1     | 2         | 0.8%    |
| 5.15.7-arch1-1     | 2         | 0.8%    |
| 5.15.6-arch2-1     | 2         | 0.8%    |
| 5.15.4-zen1-1-zen  | 2         | 0.8%    |
| 5.15.2-zen1-1-zen  | 2         | 0.8%    |
| 5.15.18-1-lts      | 2         | 0.8%    |
| 5.15.11-arch2-1    | 2         | 0.8%    |
| 5.14.9-lqx4-1-lqx  | 2         | 0.8%    |
| 5.14.8-zen1-1-zen  | 2         | 0.8%    |
| 5.14.3-arch1-1     | 2         | 0.8%    |
| 5.14.16-arch1-1    | 2         | 0.8%    |
| 5.14.11-arch1-1    | 2         | 0.8%    |
| 5.13.9-arch1-1     | 2         | 0.8%    |
| 5.13.4-arch1-1     | 2         | 0.8%    |
| 5.13.13-lqx1-1-lqx | 2         | 0.8%    |
| 5.13.12-arch1-1    | 2         | 0.8%    |
| 5.13.10-arch1-1    | 2         | 0.8%    |
| 5.12.8-arch1-1     | 2         | 0.8%    |
| 5.12.5-zen1-1-zen  | 2         | 0.8%    |
| 5.12.5-arch1-1     | 2         | 0.8%    |
| 5.12.3-arch1-1     | 2         | 0.8%    |
| 5.11.8-arch1-1     | 2         | 0.8%    |
| 5.11.4-arch1-1     | 2         | 0.8%    |
| 5.11.14-zen1-1-zen | 2         | 0.8%    |
| 5.10.68-1-lts      | 2         | 0.8%    |
| 5.10.4-arch2-1     | 2         | 0.8%    |
| 5.10.16-arch1-1    | 2         | 0.8%    |
| 5.10.11-arch1-1    | 2         | 0.8%    |
| 5.9.9-arch1-1      | 1         | 0.4%    |
| 5.9.13-arch1-1     | 1         | 0.4%    |
| 5.9.11-arch2-1     | 1         | 0.4%    |
| 5.9.1-zen2-1-zen   | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.12 | 11        | 4.38%   |
| 5.13.13 | 10        | 3.98%   |
| 5.15.4  | 8         | 3.19%   |
| 5.15.2  | 7         | 2.79%   |
| 5.12.13 | 7         | 2.79%   |
| 5.11.16 | 7         | 2.79%   |
| 5.15.10 | 6         | 2.39%   |
| 5.14.9  | 6         | 2.39%   |
| 5.9.14  | 5         | 1.99%   |
| 5.9.1   | 5         | 1.99%   |
| 5.16.8  | 5         | 1.99%   |
| 5.16.4  | 5         | 1.99%   |
| 5.15.6  | 5         | 1.99%   |
| 5.11.11 | 5         | 1.99%   |
| 5.7.8   | 4         | 1.59%   |
| 5.16.10 | 4         | 1.59%   |
| 5.14.6  | 4         | 1.59%   |
| 5.14.14 | 4         | 1.59%   |
| 5.13.4  | 4         | 1.59%   |
| 5.12.5  | 4         | 1.59%   |
| 5.12.14 | 4         | 1.59%   |
| 5.9.8   | 3         | 1.2%    |
| 5.9.10  | 3         | 1.2%    |
| 5.16.5  | 3         | 1.2%    |
| 5.14.8  | 3         | 1.2%    |
| 5.13.9  | 3         | 1.2%    |
| 5.11.14 | 3         | 1.2%    |
| 5.10.15 | 3         | 1.2%    |
| 5.9.2   | 2         | 0.8%    |
| 5.8.12  | 2         | 0.8%    |
| 5.7.10  | 2         | 0.8%    |
| 5.4.2   | 2         | 0.8%    |
| 5.16.7  | 2         | 0.8%    |
| 5.16.2  | 2         | 0.8%    |
| 5.16.1  | 2         | 0.8%    |
| 5.16.0  | 2         | 0.8%    |
| 5.15.7  | 2         | 0.8%    |
| 5.15.18 | 2         | 0.8%    |
| 5.15.13 | 2         | 0.8%    |
| 5.15.11 | 2         | 0.8%    |
| 5.15.0  | 2         | 0.8%    |
| 5.14.3  | 2         | 0.8%    |
| 5.14.2  | 2         | 0.8%    |
| 5.14.16 | 2         | 0.8%    |
| 5.14.15 | 2         | 0.8%    |
| 5.14.11 | 2         | 0.8%    |
| 5.13.12 | 2         | 0.8%    |
| 5.13.10 | 2         | 0.8%    |
| 5.12.8  | 2         | 0.8%    |
| 5.12.3  | 2         | 0.8%    |
| 5.12.1  | 2         | 0.8%    |
| 5.11.8  | 2         | 0.8%    |
| 5.11.4  | 2         | 0.8%    |
| 5.10.68 | 2         | 0.8%    |
| 5.10.4  | 2         | 0.8%    |
| 5.10.16 | 2         | 0.8%    |
| 5.10.11 | 2         | 0.8%    |
| 5.9.9   | 1         | 0.4%    |
| 5.9.13  | 1         | 0.4%    |
| 5.9.11  | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 48        | 19.83%  |
| 5.14    | 30        | 12.4%   |
| 5.16    | 27        | 11.16%  |
| 5.13    | 24        | 9.92%   |
| 5.12    | 24        | 9.92%   |
| 5.9     | 21        | 8.68%   |
| 5.11    | 21        | 8.68%   |
| 5.10    | 20        | 8.26%   |
| 5.8     | 9         | 3.72%   |
| 5.7     | 8         | 3.31%   |
| 5.4     | 6         | 2.48%   |
| 5.6     | 2         | 0.83%   |
| 4.19    | 2         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 225       | 99.56%  |
| aarch64 | 1         | 0.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 64        | 27.35%  |
| KDE5       | 57        | 24.36%  |
| XFCE       | 56        | 23.93%  |
| X-Cinnamon | 11        | 4.7%    |
| KDE        | 10        | 4.27%   |
| Unknown    | 7         | 2.99%   |
| i3         | 6         | 2.56%   |
| Cinnamon   | 6         | 2.56%   |
| Budgie     | 5         | 2.14%   |
| MATE       | 3         | 1.28%   |
| sway       | 2         | 0.85%   |
| LXQt       | 2         | 0.85%   |
| Deepin     | 2         | 0.85%   |
| awesome    | 2         | 0.85%   |
| LXDE       | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 171       | 74.35%  |
| Wayland | 47        | 20.43%  |
| Tty     | 6         | 2.61%   |
| Unknown | 6         | 2.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 62        | 26.5%   |
| Unknown | 52        | 22.22%  |
| SDDM    | 50        | 21.37%  |
| GDM     | 44        | 18.8%   |
| TDM     | 26        | 11.11%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 116       | 51.33%  |
| en_GB   | 21        | 9.29%   |
| en_CA   | 9         | 3.98%   |
| fr_FR   | 8         | 3.54%   |
| it_IT   | 7         | 3.1%    |
| en_IN   | 7         | 3.1%    |
| de_DE   | 7         | 3.1%    |
| en_AU   | 5         | 2.21%   |
| Unknown | 5         | 2.21%   |
| en_NZ   | 4         | 1.77%   |
| tr_TR   | 3         | 1.33%   |
| ru_RU   | 3         | 1.33%   |
| pt_BR   | 3         | 1.33%   |
| pl_PL   | 3         | 1.33%   |
| en_PH   | 3         | 1.33%   |
| sv_SE   | 2         | 0.88%   |
| pt_PT   | 2         | 0.88%   |
| nl_NL   | 2         | 0.88%   |
| es_ES   | 2         | 0.88%   |
| es_AR   | 2         | 0.88%   |
| en_DK   | 2         | 0.88%   |
| ru_UA   | 1         | 0.44%   |
| nl_BE   | 1         | 0.44%   |
| hr_HR   | 1         | 0.44%   |
| fi_FI   | 1         | 0.44%   |
| es_MX   | 1         | 0.44%   |
| en_MY   | 1         | 0.44%   |
| en_IL   | 1         | 0.44%   |
| de_AT   | 1         | 0.44%   |
| cs_CZ   | 1         | 0.44%   |
| an_ES   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 160       | 69.57%  |
| BIOS | 70        | 30.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 170       | 74.89%  |
| Btrfs   | 52        | 22.91%  |
| Overlay | 3         | 1.32%   |
| Xfs     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 155       | 67.1%   |
| Unknown | 57        | 24.68%  |
| MBR     | 19        | 8.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 206       | 90.75%  |
| Yes       | 21        | 9.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 171       | 74.03%  |
| Yes       | 60        | 25.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 69        | 30.53%  |
| Dell                | 34        | 15.04%  |
| Hewlett-Packard     | 33        | 14.6%   |
| ASUSTek Computer    | 28        | 12.39%  |
| Acer                | 15        | 6.64%   |
| Apple               | 9         | 3.98%   |
| MSI                 | 8         | 3.54%   |
| HUAWEI              | 6         | 2.65%   |
| Notebook            | 3         | 1.33%   |
| Unknown             | 3         | 1.33%   |
| Toshiba             | 2         | 0.88%   |
| Timi                | 2         | 0.88%   |
| Schenker            | 2         | 0.88%   |
| TUXEDO              | 1         | 0.44%   |
| TrekStor            | 1         | 0.44%   |
| Samsung Electronics | 1         | 0.44%   |
| Razer               | 1         | 0.44%   |
| Radxa               | 1         | 0.44%   |
| Pine Microsystems   | 1         | 0.44%   |
| Gigabyte Technology | 1         | 0.44%   |
| Framework           | 1         | 0.44%   |
| Eluktronics         | 1         | 0.44%   |
| Dynabook            | 1         | 0.44%   |
| AMI                 | 1         | 0.44%   |
| Alienware           | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                                   | 4         | 1.77%   |
| Lenovo ThinkPad X140e 20BL000BUS                      | 3         | 1.33%   |
| Unknown                                               | 3         | 1.33%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB                  | 2         | 0.88%   |
| Lenovo IdeaPad FLEX-14API 81SS                        | 2         | 0.88%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 2         | 0.88%   |
| HUAWEI MACH-WX9                                       | 2         | 0.88%   |
| HP Pavilion Gaming Laptop 15-cx0xxx                   | 2         | 0.88%   |
| HP ENVY Laptop 13-ba0xxx                              | 2         | 0.88%   |
| HP 255 G7 Notebook PC                                 | 2         | 0.88%   |
| Dell Inspiron 3542                                    | 2         | 0.88%   |
| Dell G7 7588                                          | 2         | 0.88%   |
| Dell G3 3500                                          | 2         | 0.88%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR                 | 2         | 0.88%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV                 | 2         | 0.88%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.44%   |
| TrekStor Primebook P14                                | 1         | 0.44%   |
| Toshiba Satellite P750                                | 1         | 0.44%   |
| Toshiba Satellite L50D-B                              | 1         | 0.44%   |
| Timi TM1607                                           | 1         | 0.44%   |
| Timi A35S                                             | 1         | 0.44%   |
| Schenker XMG NEO 15(E20, RTX 20xx)                    | 1         | 0.44%   |
| Schenker XMG FUSION 15 (XFU15L19)                     | 1         | 0.44%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.44%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.44%   |
| Radxa ROCK Pi X                                       | 1         | 0.44%   |
| Pine Microsystems Pine64 Pinebook Pro                 | 1         | 0.44%   |
| Notebook W65_67SZ                                     | 1         | 0.44%   |
| Notebook W65KJ1_KK1                                   | 1         | 0.44%   |
| Notebook NH5x_7xDPx                                   | 1         | 0.44%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.44%   |
| MSI Modern 14 B5M                                     | 1         | 0.44%   |
| MSI GT80S 6QE                                         | 1         | 0.44%   |
| MSI GS63VR 6RF                                        | 1         | 0.44%   |
| MSI GP66 Leopard 10UH                                 | 1         | 0.44%   |
| MSI GL75 Leopard 10SDK                                | 1         | 0.44%   |
| MSI GE72 6QD                                          | 1         | 0.44%   |
| MSI Bravo 15 B5DD                                     | 1         | 0.44%   |
| Lenovo Z50-70 20354                                   | 1         | 0.44%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.44%   |
| Lenovo Yoga S740-14IIL 81RS                           | 1         | 0.44%   |
| Lenovo Yoga 700-14ISK 80QD                            | 1         | 0.44%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.44%   |
| Lenovo V14 G2 ITL 82NM                                | 1         | 0.44%   |
| Lenovo ThinkPad X240 20AMS2QDOC                       | 1         | 0.44%   |
| Lenovo ThinkPad X240 20AMA2F8MS                       | 1         | 0.44%   |
| Lenovo ThinkPad X220 Tablet 4294CT0                   | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0ET00              | 1         | 0.44%   |
| Lenovo ThinkPad T61 7659W1W                           | 1         | 0.44%   |
| Lenovo ThinkPad T560 20FJS4FV00                       | 1         | 0.44%   |
| Lenovo ThinkPad T520 4239CTO                          | 1         | 0.44%   |
| Lenovo ThinkPad T510 4384FF3                          | 1         | 0.44%   |
| Lenovo ThinkPad T480 20L6S3S500                       | 1         | 0.44%   |
| Lenovo ThinkPad T480 20L5S1S000                       | 1         | 0.44%   |
| Lenovo ThinkPad T470 W10DG 20JNS0DB00                 | 1         | 0.44%   |
| Lenovo ThinkPad T470 20HES2SF00                       | 1         | 0.44%   |
| Lenovo ThinkPad T460 20FMS2J000                       | 1         | 0.44%   |
| Lenovo ThinkPad T450s 20BW0007US                      | 1         | 0.44%   |
| Lenovo ThinkPad T440s 20ARS34900                      | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 37        | 16.37%  |
| Lenovo IdeaPad           | 19        | 8.41%   |
| Dell Latitude            | 11        | 4.87%   |
| Dell Inspiron            | 11        | 4.87%   |
| ASUS ROG                 | 11        | 4.87%   |
| Acer Aspire              | 9         | 3.98%   |
| HP Pavilion              | 7         | 3.1%    |
| HP EliteBook             | 7         | 3.1%    |
| HP Laptop                | 6         | 2.65%   |
| HP ENVY                  | 5         | 2.21%   |
| Dell Precision           | 4         | 1.77%   |
| Apple MacBookAir7        | 4         | 1.77%   |
| Lenovo Yoga              | 3         | 1.33%   |
| Lenovo ThinkBook         | 3         | 1.33%   |
| HP 255                   | 3         | 1.33%   |
| Dell G3                  | 3         | 1.33%   |
| ASUS TUF                 | 3         | 1.33%   |
| Unknown                  | 3         | 1.33%   |
| Toshiba Satellite        | 2         | 0.88%   |
| Schenker XMG             | 2         | 0.88%   |
| Lenovo Legion            | 2         | 0.88%   |
| HUAWEI MACH-WX9          | 2         | 0.88%   |
| Dell XPS                 | 2         | 0.88%   |
| Dell G7                  | 2         | 0.88%   |
| ASUS VivoBook            | 2         | 0.88%   |
| ASUS ASUS                | 2         | 0.88%   |
| Acer Swift               | 2         | 0.88%   |
| TUXEDO Pulse             | 1         | 0.44%   |
| TrekStor Primebook       | 1         | 0.44%   |
| Timi TM1607              | 1         | 0.44%   |
| Timi A35S                | 1         | 0.44%   |
| Samsung 340XAA           | 1         | 0.44%   |
| Razer Blade              | 1         | 0.44%   |
| Radxa ROCK               | 1         | 0.44%   |
| Pine Microsystems Pine64 | 1         | 0.44%   |
| Notebook W65KJ1          | 1         | 0.44%   |
| Notebook W65             | 1         | 0.44%   |
| Notebook NH5x            | 1         | 0.44%   |
| MSI Prestige             | 1         | 0.44%   |
| MSI Modern               | 1         | 0.44%   |
| MSI GT80S                | 1         | 0.44%   |
| MSI GS63VR               | 1         | 0.44%   |
| MSI GP66                 | 1         | 0.44%   |
| MSI GL75                 | 1         | 0.44%   |
| MSI GE72                 | 1         | 0.44%   |
| MSI Bravo                | 1         | 0.44%   |
| Lenovo Z50-70            | 1         | 0.44%   |
| Lenovo Y520-15IKBN       | 1         | 0.44%   |
| Lenovo V14               | 1         | 0.44%   |
| Lenovo G505s             | 1         | 0.44%   |
| Lenovo E31-80            | 1         | 0.44%   |
| HUAWEI KLVL-WXX9         | 1         | 0.44%   |
| HUAWEI HN-WX9X           | 1         | 0.44%   |
| HUAWEI HLYL-WXX9         | 1         | 0.44%   |
| HUAWEI BOHK-WAX9X        | 1         | 0.44%   |
| HP ZBook                 | 1         | 0.44%   |
| HP Stream                | 1         | 0.44%   |
| HP Notebook              | 1         | 0.44%   |
| HP 250                   | 1         | 0.44%   |
| HP 15                    | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 35        | 15.49%  |
| 2021    | 30        | 13.27%  |
| 2019    | 27        | 11.95%  |
| 2018    | 22        | 9.73%   |
| 2017    | 19        | 8.41%   |
| 2015    | 16        | 7.08%   |
| 2016    | 15        | 6.64%   |
| 2014    | 15        | 6.64%   |
| 2013    | 15        | 6.64%   |
| 2012    | 13        | 5.75%   |
| 2011    | 7         | 3.1%    |
| 2010    | 5         | 2.21%   |
| 2008    | 4         | 1.77%   |
| 2009    | 1         | 0.44%   |
| 2007    | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 226       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 226       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 226       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 72        | 31.72%  |
| 8.01-16.0   | 53        | 23.35%  |
| 16.01-24.0  | 50        | 22.03%  |
| 3.01-4.0    | 28        | 12.33%  |
| 32.01-64.0  | 18        | 7.93%   |
| 24.01-32.0  | 3         | 1.32%   |
| 64.01-256.0 | 2         | 0.88%   |
| 1.01-2.0    | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 73        | 29.55%  |
| 1.01-2.0   | 68        | 27.53%  |
| 3.01-4.0   | 42        | 17%     |
| 4.01-8.0   | 39        | 15.79%  |
| 0.51-1.0   | 17        | 6.88%   |
| 8.01-16.0  | 5         | 2.02%   |
| 0.01-0.5   | 2         | 0.81%   |
| 16.01-24.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 157       | 67.97%  |
| 2      | 65        | 28.14%  |
| 3      | 6         | 2.6%    |
| 4      | 2         | 0.87%   |
| 0      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 177       | 77.29%  |
| Yes       | 52        | 22.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 176       | 77.88%  |
| No        | 50        | 22.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 99.12%  |
| No        | 2         | 0.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 91.63%  |
| No        | 19        | 8.37%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 53        | 23.25%  |
| Germany     | 13        | 5.7%    |
| India       | 10        | 4.39%   |
| France      | 10        | 4.39%   |
| UK          | 9         | 3.95%   |
| Italy       | 9         | 3.95%   |
| Canada      | 9         | 3.95%   |
| Poland      | 8         | 3.51%   |
| Brazil      | 8         | 3.51%   |
| Netherlands | 7         | 3.07%   |
| Turkey      | 6         | 2.63%   |
| Russia      | 6         | 2.63%   |
| Sweden      | 5         | 2.19%   |
| Finland     | 5         | 2.19%   |
| Australia   | 5         | 2.19%   |
| New Zealand | 4         | 1.75%   |
| Vietnam     | 3         | 1.32%   |
| Ukraine     | 3         | 1.32%   |
| Spain       | 3         | 1.32%   |
| Portugal    | 3         | 1.32%   |
| Philippines | 3         | 1.32%   |
| Mexico      | 3         | 1.32%   |
| Indonesia   | 3         | 1.32%   |
| Greece      | 3         | 1.32%   |
| Belgium     | 3         | 1.32%   |
| Bahrain     | 3         | 1.32%   |
| Romania     | 2         | 0.88%   |
| Norway      | 2         | 0.88%   |
| Hong Kong   | 2         | 0.88%   |
| Georgia     | 2         | 0.88%   |
| Denmark     | 2         | 0.88%   |
| Czechia     | 2         | 0.88%   |
| Croatia     | 2         | 0.88%   |
| Argentina   | 2         | 0.88%   |
| Thailand    | 1         | 0.44%   |
| Taiwan      | 1         | 0.44%   |
| South Korea | 1         | 0.44%   |
| Slovenia    | 1         | 0.44%   |
| Puerto Rico | 1         | 0.44%   |
| Pakistan    | 1         | 0.44%   |
| Morocco     | 1         | 0.44%   |
| Malaysia    | 1         | 0.44%   |
| Israel      | 1         | 0.44%   |
| Hungary     | 1         | 0.44%   |
| Egypt       | 1         | 0.44%   |
| Colombia    | 1         | 0.44%   |
| Bulgaria    | 1         | 0.44%   |
| Bangladesh  | 1         | 0.44%   |
| Austria     | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Toms River        | 6         | 2.52%   |
| Montreal          | 5         | 2.1%    |
| Barberton         | 4         | 1.68%   |
| Victoria          | 3         | 1.26%   |
| Sydney            | 3         | 1.26%   |
| Moscow            | 3         | 1.26%   |
| Manama            | 3         | 1.26%   |
| Jacksonville      | 3         | 1.26%   |
| Berlin            | 3         | 1.26%   |
| Amsterdam         | 3         | 1.26%   |
| Yuma              | 2         | 0.84%   |
| Warsaw            | 2         | 0.84%   |
| Tbilisi           | 2         | 0.84%   |
| St Petersburg     | 2         | 0.84%   |
| SÃ£o Paulo      | 2         | 0.84%   |
| Recife            | 2         | 0.84%   |
| Portland          | 2         | 0.84%   |
| Paris             | 2         | 0.84%   |
| Orlando           | 2         | 0.84%   |
| Mesa              | 2         | 0.84%   |
| Krakow            | 2         | 0.84%   |
| Ho Chi Minh City  | 2         | 0.84%   |
| Helsinki          | 2         | 0.84%   |
| Gothenburg        | 2         | 0.84%   |
| Frankfurt am Main | 2         | 0.84%   |
| Florence          | 2         | 0.84%   |
| Chicago           | 2         | 0.84%   |
| Central           | 2         | 0.84%   |
| Brussels          | 2         | 0.84%   |
| Bengaluru         | 2         | 0.84%   |
| Bandung           | 2         | 0.84%   |
| Auckland          | 2         | 0.84%   |
| Ankara            | 2         | 0.84%   |
| Г…lesund       | 1         | 0.42%   |
| Zapopan           | 1         | 0.42%   |
| Wroclaw           | 1         | 0.42%   |
| Wilmington        | 1         | 0.42%   |
| Whittier          | 1         | 0.42%   |
| Wellington        | 1         | 0.42%   |
| Vrbovec           | 1         | 0.42%   |
| Villa Ballester   | 1         | 0.42%   |
| Velika Gorica     | 1         | 0.42%   |
| Valparaiso        | 1         | 0.42%   |
| Valence           | 1         | 0.42%   |
| Turku             | 1         | 0.42%   |
| Turin             | 1         | 0.42%   |
| Toronto           | 1         | 0.42%   |
| Tervakoski        | 1         | 0.42%   |
| Tel Aviv          | 1         | 0.42%   |
| Tarsus            | 1         | 0.42%   |
| Tampere           | 1         | 0.42%   |
| Stockholm         | 1         | 0.42%   |
| Srinagar          | 1         | 0.42%   |
| Sofia             | 1         | 0.42%   |
| Ski               | 1         | 0.42%   |
| Sint-Amands       | 1         | 0.42%   |
| Silverdale        | 1         | 0.42%   |
| Secaucus          | 1         | 0.42%   |
| Santo AndrГ©    | 1         | 0.42%   |
| Santo AndrÃ©    | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 65        | 87     | 21.59%  |
| Seagate                        | 34        | 36     | 11.3%   |
| WDC                            | 24        | 29     | 7.97%   |
| SK Hynix                       | 18        | 19     | 5.98%   |
| Kingston                       | 16        | 20     | 5.32%   |
| Toshiba                        | 15        | 17     | 4.98%   |
| SanDisk                        | 15        | 16     | 4.98%   |
| HGST                           | 13        | 15     | 4.32%   |
| Intel                          | 10        | 11     | 3.32%   |
| Unknown                        | 8         | 11     | 2.66%   |
| Apple                          | 7         | 7      | 2.33%   |
| Micron Technology              | 6         | 6      | 1.99%   |
| KIOXIA                         | 6         | 6      | 1.99%   |
| Crucial                        | 6         | 7      | 1.99%   |
| Phison                         | 4         | 4      | 1.33%   |
| A-DATA Technology              | 4         | 5      | 1.33%   |
| Transcend                      | 3         | 3      | 1%      |
| LITEONIT                       | 3         | 4      | 1%      |
| Hitachi                        | 3         | 3      | 1%      |
| WDC WDS                        | 2         | 2      | 0.66%   |
| Solid State Storage Technology | 2         | 2      | 0.66%   |
| Mushkin                        | 2         | 2      | 0.66%   |
| Maxone                         | 2         | 2      | 0.66%   |
| LITEON                         | 2         | 2      | 0.66%   |
| KingSpec                       | 2         | 2      | 0.66%   |
| HFS256G3                       | 2         | 2      | 0.66%   |
| Fujitsu                        | 2         | 2      | 0.66%   |
| China                          | 2         | 2      | 0.66%   |
| XPG                            | 1         | 1      | 0.33%   |
| V-GeN                          | 1         | 1      | 0.33%   |
| USB3.0                         | 1         | 1      | 0.33%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.33%   |
| Teclast                        | 1         | 1      | 0.33%   |
| Team                           | 1         | 2      | 0.33%   |
| StoreJet                       | 1         | 1      | 0.33%   |
| SSSTC                          | 1         | 1      | 0.33%   |
| PNY                            | 1         | 1      | 0.33%   |
| OCZ                            | 1         | 1      | 0.33%   |
| Micron/Crucial Technology      | 1         | 1      | 0.33%   |
| Lite-On                        | 1         | 1      | 0.33%   |
| Lenovo                         | 1         | 1      | 0.33%   |
| KingFast                       | 1         | 1      | 0.33%   |
| KingDian                       | 1         | 1      | 0.33%   |
| JMicron                        | 1         | 1      | 0.33%   |
| HUAWEI                         | 1         | 1      | 0.33%   |
| GOODRAM                        | 1         | 1      | 0.33%   |
| Gigabyte Technology            | 1         | 1      | 0.33%   |
| Generic-                       | 1         | 1      | 0.33%   |
| FORESEE                        | 1         | 1      | 0.33%   |
| Corsair                        | 1         | 1      | 0.33%   |
| APPLE HD                       | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 11        | 3.53%   |
| HGST HTS721010A9E630 1TB                  | 7         | 2.24%   |
| Seagate ST500LT012-1DG142 500GB           | 6         | 1.92%   |
| Samsung SSD 970 EVO 500GB                 | 4         | 1.28%   |
| Samsung SSD 870 EVO 250GB                 | 4         | 1.28%   |
| Samsung SSD 860 EVO 250GB                 | 4         | 1.28%   |
| Samsung NVMe SSD Drive 512GB              | 4         | 1.28%   |
| Apple SSD SM0128G 121GB                   | 4         | 1.28%   |
| WDC WD10SPZX-24Z10 1TB                    | 3         | 0.96%   |
| Transcend TS240GMTS420S 240GB SSD         | 3         | 0.96%   |
| Seagate ST1000LM049-2GH172 1TB            | 3         | 0.96%   |
| Samsung SSD 860 EVO 500GB                 | 3         | 0.96%   |
| Samsung SSD 860 EVO 1TB                   | 3         | 0.96%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 0.96%   |
| WDC WDS 500G2B0B-00YS70 500GB SSD         | 2         | 0.64%   |
| Unknown MMC Card  64GB                    | 2         | 0.64%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 0.64%   |
| Toshiba KBG40ZNT512G MEMORY 512GB         | 2         | 0.64%   |
| Solid State Storage NVMe SSD Drive 256GB  | 2         | 0.64%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 2         | 0.64%   |
| SK Hynix HFM128GDJTNG-8310A 128GB         | 2         | 0.64%   |
| SK Hynix HFM001TD3JX013N 1TB              | 2         | 0.64%   |
| Seagate ST2000LM015-2E8174 2TB            | 2         | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 0.64%   |
| Sandisk NVMe SSD Drive 1TB                | 2         | 0.64%   |
| Samsung SSD 970 EVO 1TB                   | 2         | 0.64%   |
| Samsung SSD 870 QVO 1TB                   | 2         | 0.64%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.64%   |
| Samsung SSD 850 EVO 250GB                 | 2         | 0.64%   |
| Samsung NVMe SSD Drive 1TB                | 2         | 0.64%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD      | 2         | 0.64%   |
| Samsung MZVLB256HAHQ-000H1 256GB          | 2         | 0.64%   |
| Samsung MZVLB1T0HBLR-00000 1TB            | 2         | 0.64%   |
| Samsung MZVL21T0HCLR-00B00 1TB            | 2         | 0.64%   |
| Samsung MZNLN256HAJQ-000H1 256GB SSD      | 2         | 0.64%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD      | 2         | 0.64%   |
| Maxone USB 3.0 160GB                      | 2         | 0.64%   |
| KIOXIA KBG40ZNV512G 512GB                 | 2         | 0.64%   |
| KIOXIA KBG40ZNV1T02 1TB                   | 2         | 0.64%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 0.64%   |
| Kingston OM8PCP3512F-AI1 512GB            | 2         | 0.64%   |
| Kingston OM8PCP3512F-AB 512GB             | 2         | 0.64%   |
| Intel SSDPEKNW512G8H 512GB                | 2         | 0.64%   |
| Intel NVMe SSD Drive 512GB                | 2         | 0.64%   |
| Hitachi HTS545050A7E380 500GB             | 2         | 0.64%   |
| HGST HTS541010B7E610 1TB                  | 2         | 0.64%   |
| HFS256G3 9TND-N210A 256GB                 | 2         | 0.64%   |
| Crucial CT250MX500SSD1 250GB              | 2         | 0.64%   |
| XPG NVMe SSD Drive 2TB                    | 1         | 0.32%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 0.32%   |
| WDC WDS250G2B0A-00SM50 250GB SSD          | 1         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 0.32%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.32%   |
| WDC WD5000LPVT-22G33T0 500GB              | 1         | 0.32%   |
| WDC WD5000LPCX-24C6HT0 500GB              | 1         | 0.32%   |
| WDC WD5000BEVT-60ZAT1 500GB               | 1         | 0.32%   |
| WDC WD1600BEVT-22ZCT0 160GB               | 1         | 0.32%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 0.32%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 31        | 32     | 43.06%  |
| HGST     | 13        | 15     | 18.06%  |
| WDC      | 11        | 13     | 15.28%  |
| Toshiba  | 6         | 6      | 8.33%   |
| Hitachi  | 3         | 3      | 4.17%   |
| Maxone   | 2         | 2      | 2.78%   |
| Fujitsu  | 2         | 2      | 2.78%   |
| USB3.0   | 1         | 1      | 1.39%   |
| Unknown  | 1         | 1      | 1.39%   |
| StoreJet | 1         | 1      | 1.39%   |
| Generic- | 1         | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 51     | 34.21%  |
| Kingston            | 11        | 15     | 9.65%   |
| SanDisk             | 10        | 10     | 8.77%   |
| Apple               | 6         | 6      | 5.26%   |
| WDC                 | 5         | 7      | 4.39%   |
| SK Hynix            | 4         | 4      | 3.51%   |
| Crucial             | 4         | 4      | 3.51%   |
| Transcend           | 3         | 3      | 2.63%   |
| LITEONIT            | 3         | 4      | 2.63%   |
| WDC WDS             | 2         | 2      | 1.75%   |
| Toshiba             | 2         | 2      | 1.75%   |
| Mushkin             | 2         | 2      | 1.75%   |
| Micron Technology   | 2         | 2      | 1.75%   |
| KingSpec            | 2         | 2      | 1.75%   |
| China               | 2         | 2      | 1.75%   |
| A-DATA Technology   | 2         | 3      | 1.75%   |
| V-GeN               | 1         | 1      | 0.88%   |
| Unknown             | 1         | 2      | 0.88%   |
| Teclast             | 1         | 1      | 0.88%   |
| Team                | 1         | 2      | 0.88%   |
| Seagate             | 1         | 1      | 0.88%   |
| PNY                 | 1         | 1      | 0.88%   |
| OCZ                 | 1         | 1      | 0.88%   |
| LITEON              | 1         | 1      | 0.88%   |
| KingFast            | 1         | 1      | 0.88%   |
| KingDian            | 1         | 1      | 0.88%   |
| Intel               | 1         | 1      | 0.88%   |
| GOODRAM             | 1         | 1      | 0.88%   |
| Gigabyte Technology | 1         | 1      | 0.88%   |
| FORESEE             | 1         | 1      | 0.88%   |
| Corsair             | 1         | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 100       | 136    | 35.59%  |
| NVMe    | 98        | 120    | 34.88%  |
| HDD     | 70        | 77     | 24.91%  |
| MMC     | 7         | 9      | 2.49%   |
| Unknown | 6         | 6      | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 144       | 201    | 54.75%  |
| NVMe | 98        | 120    | 37.26%  |
| SAS  | 14        | 18     | 5.32%   |
| MMC  | 7         | 9      | 2.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 108       | 145    | 63.91%  |
| 0.51-1.0   | 56        | 62     | 33.14%  |
| 1.01-2.0   | 5         | 6      | 2.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 59        | 25.32%  |
| 251-500        | 54        | 23.18%  |
| 501-1000       | 37        | 15.88%  |
| 1001-2000      | 26        | 11.16%  |
| Unknown        | 16        | 6.87%   |
| 51-100         | 12        | 5.15%   |
| More than 3000 | 11        | 4.72%   |
| 21-50          | 7         | 3%      |
| 2001-3000      | 6         | 2.58%   |
| 1-20           | 5         | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 60        | 24.79%  |
| 21-50          | 47        | 19.42%  |
| 101-250        | 41        | 16.94%  |
| 51-100         | 32        | 13.22%  |
| 251-500        | 24        | 9.92%   |
| Unknown        | 16        | 6.61%   |
| 1001-2000      | 10        | 4.13%   |
| 501-1000       | 8         | 3.31%   |
| More than 3000 | 2         | 0.83%   |
| 2001-3000      | 2         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 3         | 3      | 16.67%  |
| Hitachi HTS545050A7E380 500GB                    | 2         | 2      | 11.11%  |
| WDC WD5000LPVT-22G33T0 500GB                     | 1         | 1      | 5.56%   |
| Transcend TS240GMTS420S 240GB SSD                | 1         | 1      | 5.56%   |
| Toshiba MK5055GSXF 500GB                         | 1         | 1      | 5.56%   |
| SK Hynix SC308 SATA 128GB SSD                    | 1         | 1      | 5.56%   |
| Seagate ST500LX012-SSHD-8GB                      | 1         | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5.56%   |
| Seagate ST1000LM049-2GH172 1TB                   | 1         | 1      | 5.56%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 970 EVO 500GB            | 1         | 1      | 5.56%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5.56%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 5.56%   |
| Fujitsu MHZ2320BH G2 320GB                       | 1         | 1      | 5.56%   |
| Apple SSD SM256C 256GB                           | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 4      | 22.22%  |
| Seagate             | 3         | 3      | 16.67%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| Hitachi             | 2         | 2      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| Transcend           | 1         | 1      | 5.56%   |
| Toshiba             | 1         | 1      | 5.56%   |
| SK Hynix            | 1         | 1      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |
| Apple               | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 4      | 33.33%  |
| Seagate | 3         | 3      | 25%     |
| Hitachi | 2         | 2      | 16.67%  |
| WDC     | 1         | 1      | 8.33%   |
| Toshiba | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 66.67%  |
| SSD  | 5         | 5      | 27.78%  |
| NVMe | 1         | 1      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| LITEON CA3-8D512 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| LITEON | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 157       | 222    | 63.82%  |
| Detected | 70        | 107    | 28.46%  |
| Malfunc  | 18        | 18     | 7.32%   |
| Failed   | 1         | 1      | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 138       | 50.55%  |
| Samsung Electronics            | 33        | 12.09%  |
| AMD                            | 32        | 11.72%  |
| SK Hynix                       | 13        | 4.76%   |
| Sandisk                        | 12        | 4.4%    |
| KIOXIA                         | 9         | 3.3%    |
| Kingston Technology Company    | 5         | 1.83%   |
| Toshiba America Info Systems   | 4         | 1.47%   |
| Phison Electronics             | 4         | 1.47%   |
| Micron Technology              | 4         | 1.47%   |
| Solid State Storage Technology | 3         | 1.1%    |
| Micron/Crucial Technology      | 3         | 1.1%    |
| ADATA Technology               | 3         | 1.1%    |
| Seagate Technology             | 2         | 0.73%   |
| Lite-On Technology             | 2         | 0.73%   |
| Union Memory (Shenzhen)        | 1         | 0.37%   |
| Nvidia                         | 1         | 0.37%   |
| Marvell Technology Group       | 1         | 0.37%   |
| Lenovo                         | 1         | 0.37%   |
| JMicron Technology             | 1         | 0.37%   |
| Apple                          | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30        | 10.49%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 27        | 9.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 7.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 5.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 4.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 3.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 3.5%    |
| KIOXIA Non-Volatile memory controller                                          | 9         | 3.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 2.8%    |
| Intel SSD 660P Series                                                          | 6         | 2.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.1%    |
| SK Hynix Gold P31 SSD                                                          | 5         | 1.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.75%   |
| SK Hynix Non-Volatile memory controller                                        | 4         | 1.4%    |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.4%    |
| Samsung Electronics SATA controller                                            | 4         | 1.4%    |
| Micron Non-Volatile memory controller                                          | 4         | 1.4%    |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.4%    |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.4%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 4         | 1.4%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 4         | 1.4%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.05%   |
| Solid State Storage Non-Volatile memory controller                             | 3         | 1.05%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.05%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.05%   |
| Sandisk Non-Volatile memory controller                                         | 3         | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.05%   |
| SK Hynix BC511                                                                 | 2         | 0.7%    |
| SK Hynix BC501 NVMe Solid State Drive                                          | 2         | 0.7%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.7%    |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.7%    |
| Phison E12 NVMe Controller                                                     | 2         | 0.7%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 0.7%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 0.7%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.35%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.35%   |
| Seagate Non-Volatile memory controller                                         | 1         | 0.35%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.35%   |
| Sandisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.35%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.35%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.35%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.35%   |
| Lite-On NVMe Controller                                                        | 1         | 0.35%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.35%   |
| Lenovo Non-Volatile memory controller                                          | 1         | 0.35%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.35%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 0.35%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.35%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 0.35%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 0.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 150       | 54.95%  |
| NVMe | 97        | 35.53%  |
| RAID | 22        | 8.06%   |
| IDE  | 4         | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 166       | 73.45%  |
| AMD    | 59        | 26.11%  |
| ARM    | 1         | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 3.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 2.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.21%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 2.21%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 2.21%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.21%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 2.21%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 2.21%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.77%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.33%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 3         | 1.33%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.33%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.33%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 1.33%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.33%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 3         | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.88%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.88%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 2         | 0.88%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 2         | 0.88%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 0.88%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.88%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 2         | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.88%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.88%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.88%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.88%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.88%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 2         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.88%   |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 2         | 0.88%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.88%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.88%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 0.88%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.44%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.44%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.44%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.44%   |
| Intel Core i7-6820HK CPU @ 2.70GHz            | 1         | 0.44%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.44%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.44%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.44%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.44%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.44%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 0.44%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.44%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 66        | 29.2%   |
| Intel Core i7        | 63        | 27.88%  |
| Other                | 15        | 6.64%   |
| AMD Ryzen 7          | 15        | 6.64%   |
| Intel Core i3        | 11        | 4.87%   |
| AMD Ryzen 5          | 11        | 4.87%   |
| AMD A4               | 7         | 3.1%    |
| AMD Ryzen 9          | 6         | 2.65%   |
| AMD Ryzen 7 PRO      | 6         | 2.65%   |
| Intel Core 2 Duo     | 5         | 2.21%   |
| Intel Celeron        | 4         | 1.77%   |
| AMD Ryzen 3          | 3         | 1.33%   |
| AMD A8               | 3         | 1.33%   |
| AMD E1               | 2         | 0.88%   |
| Intel Xeon           | 1         | 0.44%   |
| Intel Pentium        | 1         | 0.44%   |
| Intel Core m3        | 1         | 0.44%   |
| Intel Core 2 Extreme | 1         | 0.44%   |
| Intel Atom           | 1         | 0.44%   |
| AMD Ryzen 5 PRO      | 1         | 0.44%   |
| AMD E                | 1         | 0.44%   |
| AMD Athlon II        | 1         | 0.44%   |
| AMD Athlon           | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 90        | 39.82%  |
| 4      | 85        | 37.61%  |
| 8      | 31        | 13.72%  |
| 6      | 20        | 8.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 225       | 99.56%  |
| 2      | 1         | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 193       | 85.4%   |
| 1      | 33        | 14.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 224       | 99.12%  |
| 64-bit         | 1         | 0.44%   |
| Unknown        | 1         | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 25.76%  |
| 0x406e3    | 13        | 5.68%   |
| 0x806ea    | 10        | 4.37%   |
| 0x40651    | 10        | 4.37%   |
| 0x906ea    | 9         | 3.93%   |
| 0x306c3    | 9         | 3.93%   |
| 0x306a9    | 9         | 3.93%   |
| 0x0a50000c | 9         | 3.93%   |
| 0x806ec    | 8         | 3.49%   |
| 0x506e3    | 6         | 2.62%   |
| 0x08108109 | 6         | 2.62%   |
| 0xa0652    | 5         | 2.18%   |
| 0x806e9    | 5         | 2.18%   |
| 0x806c1    | 5         | 2.18%   |
| 0x706e5    | 5         | 2.18%   |
| 0x306d4    | 5         | 2.18%   |
| 0x206a7    | 5         | 2.18%   |
| 0x08600104 | 5         | 2.18%   |
| 0x08108102 | 5         | 2.18%   |
| 0x08600106 | 4         | 1.75%   |
| 0x906e9    | 3         | 1.31%   |
| 0x806d1    | 3         | 1.31%   |
| 0x20655    | 3         | 1.31%   |
| 0x1067a    | 3         | 1.31%   |
| 0x706a1    | 2         | 0.87%   |
| 0x08608103 | 2         | 0.87%   |
| 0x08600102 | 2         | 0.87%   |
| 0x07000110 | 2         | 0.87%   |
| 0x0700010f | 2         | 0.87%   |
| 0x06006705 | 2         | 0.87%   |
| 0x806eb    | 1         | 0.44%   |
| 0x706a8    | 1         | 0.44%   |
| 0x506c9    | 1         | 0.44%   |
| 0x406c4    | 1         | 0.44%   |
| 0x20652    | 1         | 0.44%   |
| 0x08608102 | 1         | 0.44%   |
| 0x08600103 | 1         | 0.44%   |
| 0x08001137 | 1         | 0.44%   |
| 0x07030105 | 1         | 0.44%   |
| 0x07030104 | 1         | 0.44%   |
| 0x06006704 | 1         | 0.44%   |
| 0x06001119 | 1         | 0.44%   |
| 0x010000c8 | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 48        | 21.24%  |
| Skylake       | 24        | 10.62%  |
| Haswell       | 23        | 10.18%  |
| Zen 2         | 16        | 7.08%   |
| IvyBridge     | 13        | 5.75%   |
| Zen+          | 12        | 5.31%   |
| Zen 3         | 11        | 4.87%   |
| IceLake       | 10        | 4.42%   |
| TigerLake     | 8         | 3.54%   |
| CometLake     | 8         | 3.54%   |
| Broadwell     | 8         | 3.54%   |
| SandyBridge   | 7         | 3.1%    |
| Jaguar        | 6         | 2.65%   |
| Penryn        | 5         | 2.21%   |
| Unknown       | 5         | 2.21%   |
| Westmere      | 4         | 1.77%   |
| Excavator     | 4         | 1.77%   |
| Goldmont plus | 3         | 1.33%   |
| Silvermont    | 2         | 0.88%   |
| Puma          | 2         | 0.88%   |
| Piledriver    | 2         | 0.88%   |
| Zen           | 1         | 0.44%   |
| K10           | 1         | 0.44%   |
| Goldmont      | 1         | 0.44%   |
| Core          | 1         | 0.44%   |
| Bobcat        | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 154       | 50.99%  |
| Nvidia | 79        | 26.16%  |
| AMD    | 69        | 22.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                   | 16        | 5.19%   |
| AMD Renoir                                                                            | 16        | 5.19%   |
| Intel UHD Graphics 620                                                                | 14        | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 13        | 4.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 13        | 4.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 12        | 3.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 12        | 3.9%    |
| AMD Cezanne                                                                           | 11        | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 9         | 2.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 2.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 2.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 2.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 6         | 1.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 1.62%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 5         | 1.62%   |
| Intel HD Graphics 530                                                                 | 5         | 1.62%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 4         | 1.3%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 4         | 1.3%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 4         | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 1.3%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 1.3%    |
| Intel HD Graphics 620                                                                 | 4         | 1.3%    |
| Intel HD Graphics 6000                                                                | 4         | 1.3%    |
| Intel HD Graphics 5500                                                                | 4         | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                                   | 4         | 1.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 4         | 1.3%    |
| Nvidia GP108M [GeForce MX250]                                                         | 3         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 0.97%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 3         | 0.97%   |
| Nvidia GM108M [GeForce 940M]                                                          | 3         | 0.97%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 3         | 0.97%   |
| Intel HD Graphics 630                                                                 | 3         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 0.97%   |
| AMD Lucienne                                                                          | 3         | 0.97%   |
| AMD Kabini [Radeon HD 8330]                                                           | 3         | 0.97%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 2         | 0.65%   |
| Nvidia GP107M [GeForce MX350]                                                         | 2         | 0.65%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 2         | 0.65%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 2         | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 0.65%   |
| Nvidia GF108M [GeForce GT 540M]                                                       | 2         | 0.65%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                              | 2         | 0.65%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 0.65%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 2         | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 0.65%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                               | 2         | 0.65%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                    | 1         | 0.32%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 0.32%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.32%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.32%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                 | 1         | 0.32%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                 | 1         | 0.32%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 1         | 0.32%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 0.32%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                 | 1         | 0.32%   |
| Nvidia GM108M [GeForce MX110]                                                         | 1         | 0.32%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 38.05%  |
| Intel + Nvidia | 59        | 26.11%  |
| 1 x AMD        | 46        | 20.35%  |
| 1 x Nvidia     | 11        | 4.87%   |
| Intel + AMD    | 9         | 3.98%   |
| AMD + Nvidia   | 9         | 3.98%   |
| 2 x AMD        | 5         | 2.21%   |
| Other          | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 169       | 74.78%  |
| Proprietary | 56        | 24.78%  |
| Unknown     | 1         | 0.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 65.65%  |
| 0.01-0.5   | 32        | 13.91%  |
| 1.01-2.0   | 20        | 8.7%    |
| 3.01-4.0   | 8         | 3.48%   |
| 0.51-1.0   | 8         | 3.48%   |
| 7.01-8.0   | 5         | 2.17%   |
| 5.01-6.0   | 3         | 1.3%    |
| 2.01-3.0   | 3         | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 20.59%  |
| LG Display              | 41        | 15.07%  |
| Chimei Innolux          | 40        | 14.71%  |
| BOE                     | 28        | 10.29%  |
| Samsung Electronics     | 20        | 7.35%   |
| PANDA                   | 9         | 3.31%   |
| Apple                   | 9         | 3.31%   |
| Sharp                   | 7         | 2.57%   |
| Dell                    | 7         | 2.57%   |
| Goldstar                | 6         | 2.21%   |
| Lenovo                  | 5         | 1.84%   |
| InfoVision              | 5         | 1.84%   |
| Philips                 | 4         | 1.47%   |
| ViewSonic               | 3         | 1.1%    |
| Sony                    | 3         | 1.1%    |
| Hewlett-Packard         | 3         | 1.1%    |
| Acer                    | 3         | 1.1%    |
| JDI                     | 2         | 0.74%   |
| CSO                     | 2         | 0.74%   |
| Chi Mei Optoelectronics | 2         | 0.74%   |
| BenQ                    | 2         | 0.74%   |
| AOC                     | 2         | 0.74%   |
| Ancor Communications    | 2         | 0.74%   |
| Vizio                   | 1         | 0.37%   |
| Unknown                 | 1         | 0.37%   |
| Sun                     | 1         | 0.37%   |
| Sceptre Tech            | 1         | 0.37%   |
| Pixio                   | 1         | 0.37%   |
| LG Philips              | 1         | 0.37%   |
| InnoLux Display         | 1         | 0.37%   |
| Iiyama                  | 1         | 0.37%   |
| HKC                     | 1         | 0.37%   |
| Gigabyte Technology     | 1         | 0.37%   |
| DENON                   | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 5         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.09%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.73%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 2         | 0.73%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.73%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 2         | 0.73%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 2         | 0.73%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.73%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.73%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 2         | 0.73%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.73%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 2         | 0.73%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.73%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.73%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 2         | 0.73%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.73%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 2         | 0.73%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                 | 2         | 0.73%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                 | 2         | 0.73%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.73%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch        | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch         | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 2         | 0.73%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                   | 1         | 0.36%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.36%   |
| ViewSonic VX2456 SERIES VSC4F2F 1920x1080 521x293mm 23.5-inch         | 1         | 0.36%   |
| ViewSonic LCD Monitor VSC3E32 1920x1080 600x340mm 27.2-inch           | 1         | 0.36%   |
| Unknown LCD Monitor Sharp LQ156M1JW03 3840x1080                       | 1         | 0.36%   |
| Unknown LCD Monitor Dell SE2717H/HX                                   | 1         | 0.36%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.36%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.36%   |
| Sony TV *00 SNYF503 1920x1080 1439x809mm 65.0-inch                    | 1         | 0.36%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                         | 1         | 0.36%   |
| Sharp LQ156M1JW16 SHP14F4 1920x1080 344x194mm 15.5-inch               | 1         | 0.36%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.36%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.36%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.36%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.36%   |
| Sceptre Tech Sceptre C27 SPT0AD7 1920x1080 598x336mm 27.0-inch        | 1         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.36%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.36%   |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch      | 1         | 0.36%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 136       | 52.92%  |
| 1366x768 (WXGA)    | 61        | 23.74%  |
| 2560x1440 (QHD)    | 11        | 4.28%   |
| 3840x2160 (4K)     | 9         | 3.5%    |
| 1440x900 (WXGA+)   | 9         | 3.5%    |
| 2560x1600          | 5         | 1.95%   |
| 1920x1200 (WUXGA)  | 5         | 1.95%   |
| 1280x800 (WXGA)    | 4         | 1.56%   |
| 3000x2000          | 2         | 0.78%   |
| 2560x1080          | 2         | 0.78%   |
| 2160x1440          | 2         | 0.78%   |
| 1600x900 (HD+)     | 2         | 0.78%   |
| 3840x2400          | 1         | 0.39%   |
| 3840x1080          | 1         | 0.39%   |
| 3456x2160          | 1         | 0.39%   |
| 3440x1440          | 1         | 0.39%   |
| 3200x1800 (QHD+)   | 1         | 0.39%   |
| 2880x1800          | 1         | 0.39%   |
| 2256x1504          | 1         | 0.39%   |
| 1680x1050 (WSXGA+) | 1         | 0.39%   |
| Unknown            | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 103       | 37.73%  |
| 13      | 56        | 20.51%  |
| 14      | 29        | 10.62%  |
| 17      | 15        | 5.49%   |
| 27      | 13        | 4.76%   |
| 24      | 8         | 2.93%   |
| 23      | 6         | 2.2%    |
| 21      | 6         | 2.2%    |
| 12      | 5         | 1.83%   |
| 11      | 5         | 1.83%   |
| 18      | 4         | 1.47%   |
| 16      | 4         | 1.47%   |
| 34      | 2         | 0.73%   |
| 31      | 2         | 0.73%   |
| 72      | 1         | 0.37%   |
| 65      | 1         | 0.37%   |
| 57      | 1         | 0.37%   |
| 54      | 1         | 0.37%   |
| 49      | 1         | 0.37%   |
| 42      | 1         | 0.37%   |
| 40      | 1         | 0.37%   |
| 29      | 1         | 0.37%   |
| 28      | 1         | 0.37%   |
| 26      | 1         | 0.37%   |
| 25      | 1         | 0.37%   |
| 22      | 1         | 0.37%   |
| 10      | 1         | 0.37%   |
| 8       | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 160       | 58.61%  |
| 201-300     | 40        | 14.65%  |
| 501-600     | 29        | 10.62%  |
| 351-400     | 18        | 6.59%   |
| 401-500     | 11        | 4.03%   |
| 601-700     | 4         | 1.47%   |
| 1001-1500   | 4         | 1.47%   |
| 701-800     | 2         | 0.73%   |
| 801-900     | 1         | 0.37%   |
| 1501-2000   | 1         | 0.37%   |
| 101-200     | 1         | 0.37%   |
| 901-1000    | 1         | 0.37%   |
| Unknown     | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 195       | 84.05%  |
| 16/10   | 26        | 11.21%  |
| 3/2     | 5         | 2.16%   |
| 21/9    | 2         | 0.86%   |
| 4/3     | 1         | 0.43%   |
| 2.65    | 1         | 0.43%   |
| 0.62    | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 104       | 38.24%  |
| 81-90          | 63        | 23.16%  |
| 71-80          | 23        | 8.46%   |
| 201-250        | 17        | 6.25%   |
| 301-350        | 14        | 5.15%   |
| 121-130        | 13        | 4.78%   |
| More than 1000 | 5         | 1.84%   |
| 51-60          | 5         | 1.84%   |
| 351-500        | 5         | 1.84%   |
| 251-300        | 5         | 1.84%   |
| 61-70          | 4         | 1.47%   |
| 141-150        | 4         | 1.47%   |
| 111-120        | 3         | 1.1%    |
| 131-140        | 2         | 0.74%   |
| 501-1000       | 2         | 0.74%   |
| 41-50          | 1         | 0.37%   |
| 1-40           | 1         | 0.37%   |
| Unknown        | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 129       | 47.78%  |
| 101-120       | 65        | 24.07%  |
| 51-100        | 34        | 12.59%  |
| 161-240       | 25        | 9.26%   |
| More than 240 | 11        | 4.07%   |
| 1-50          | 5         | 1.85%   |
| Unknown       | 1         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 182       | 78.79%  |
| 2     | 48        | 20.78%  |
| 3     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 142       | 38.8%   |
| Realtek Semiconductor             | 131       | 35.79%  |
| Qualcomm Atheros                  | 36        | 9.84%   |
| Broadcom                          | 13        | 3.55%   |
| MEDIATEK                          | 8         | 2.19%   |
| TP-Link                           | 6         | 1.64%   |
| D-Link                            | 6         | 1.64%   |
| Broadcom Limited                  | 6         | 1.64%   |
| ASIX Electronics                  | 4         | 1.09%   |
| Hewlett-Packard                   | 3         | 0.82%   |
| Sierra Wireless                   | 2         | 0.55%   |
| Lenovo                            | 2         | 0.55%   |
| NetGear                           | 1         | 0.27%   |
| Linksys                           | 1         | 0.27%   |
| Huawei Technologies               | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| DisplayLink                       | 1         | 0.27%   |
| Cypress Semiconductor             | 1         | 0.27%   |
| Apple                             | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 20.18%  |
| Intel Wi-Fi 6 AX200                                               | 26        | 5.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 3.63%   |
| Intel Wireless 7260                                               | 14        | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.72%   |
| Intel Wireless 8265 / 8275                                        | 11        | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 2.04%   |
| Intel Wireless 8260                                               | 8         | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.81%   |
| Intel Wireless 7265                                               | 7         | 1.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 1.36%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.36%   |
| D-Link 802.11ac NIC                                               | 6         | 1.36%   |
| TP-Link 802.11ac NIC                                              | 5         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.13%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.13%   |
| Intel Wireless 3165                                               | 5         | 1.13%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 5         | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.91%   |
| Realtek 802.11ac NIC                                              | 4         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.91%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.68%   |
| Intel Wireless 3160                                               | 3         | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.68%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.68%   |
| HP un2430 Mobile Broadband Module                                 | 3         | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.45%   |
| Realtek Realtek Ethernet controller                               | 2         | 0.45%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.45%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.45%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.45%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.23%   |
| Sierra Wireless EM7455 QualcommÂ Snapdragonâ¢ X7 LTE-A       | 1         | 0.23%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 141       | 57.79%  |
| Realtek Semiconductor | 32        | 13.11%  |
| Qualcomm Atheros      | 31        | 12.7%   |
| Broadcom              | 11        | 4.51%   |
| MEDIATEK              | 8         | 3.28%   |
| TP-Link               | 6         | 2.46%   |
| D-Link                | 6         | 2.46%   |
| Broadcom Limited      | 6         | 2.46%   |
| Sierra Wireless       | 2         | 0.82%   |
| Linksys               | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 26        | 10.53%  |
| Intel Wireless 7260                                                    | 14        | 5.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12        | 4.86%   |
| Intel Wireless 8265 / 8275                                             | 11        | 4.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 10        | 4.05%   |
| Intel Wireless 8260                                                    | 8         | 3.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 3.24%   |
| Intel Wireless 7265                                                    | 7         | 2.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 7         | 2.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 7         | 2.83%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 2.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 2.43%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 2.43%   |
| D-Link 802.11ac NIC                                                    | 6         | 2.43%   |
| TP-Link 802.11ac NIC                                                   | 5         | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 2.02%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 2.02%   |
| Intel Wireless 3165                                                    | 5         | 2.02%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter             | 5         | 2.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 1.62%   |
| Realtek 802.11ac NIC                                                   | 4         | 1.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 4         | 1.62%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 1.62%   |
| Broadcom BCM43142 802.11b/g/n                                          | 4         | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.21%   |
| Intel Wireless 3160                                                    | 3         | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 3         | 1.21%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 0.81%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.81%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1         | 0.4%    |
| Sierra Wireless EM7455 QualcommÂ Snapdragonâ¢ X7 LTE-A            | 1         | 0.4%    |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 0.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.4%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.4%    |
| Realtek RTL8723AU 802.11n WLAN Adapter                                 | 1         | 0.4%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 0.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.4%    |
| MediaTek WiFi                                                          | 1         | 0.4%    |
| MEDIATEK Network controller                                            | 1         | 0.4%    |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                    | 1         | 0.4%    |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1         | 0.4%    |
| Intel Wireless-AC 9260                                                 | 1         | 0.4%    |
| Intel Ultimate N WiFi Link 5300                                        | 1         | 0.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 0.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 1         | 0.4%    |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1         | 0.4%    |
| Intel Centrino Wireless-N 2230                                         | 1         | 0.4%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 1         | 0.4%    |
| D-Link DWA-171                                                         | 1         | 0.4%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 117       | 63.24%  |
| Intel                 | 43        | 23.24%  |
| Qualcomm Atheros      | 11        | 5.95%   |
| Broadcom              | 4         | 2.16%   |
| ASIX Electronics      | 4         | 2.16%   |
| Lenovo                | 2         | 1.08%   |
| NetGear               | 1         | 0.54%   |
| DisplayLink           | 1         | 0.54%   |
| Cypress Semiconductor | 1         | 0.54%   |
| Apple                 | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 47.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 8.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 3.17%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 3.17%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.12%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.12%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.12%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.59%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.06%   |
| Realtek Realtek Ethernet controller                               | 2         | 1.06%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 1.06%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 1.06%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.53%   |
| NetGear LB1120-100NAS                                             | 1         | 0.53%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.53%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.53%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.53%   |
| Cypress K38231_03                                                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 0.53%   |
| Apple T2 Controller                                               | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 225       | 55.56%  |
| Ethernet | 175       | 43.21%  |
| Modem    | 5         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 205       | 75.09%  |
| Ethernet | 67        | 24.54%  |
| Modem    | 1         | 0.37%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 158       | 69.91%  |
| 1     | 60        | 26.55%  |
| 3     | 6         | 2.65%   |
| 0     | 2         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 185       | 81.14%  |
| Yes  | 43        | 18.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 128       | 60.09%  |
| Realtek Semiconductor           | 21        | 9.86%   |
| Qualcomm Atheros Communications | 15        | 7.04%   |
| Broadcom                        | 9         | 4.23%   |
| Apple                           | 8         | 3.76%   |
| Lite-On Technology              | 7         | 3.29%   |
| IMC Networks                    | 7         | 3.29%   |
| Foxconn / Hon Hai               | 5         | 2.35%   |
| Realtek                         | 3         | 1.41%   |
| Qualcomm Atheros                | 3         | 1.41%   |
| Dell                            | 3         | 1.41%   |
| Toshiba                         | 1         | 0.47%   |
| MediaTek                        | 1         | 0.47%   |
| Foxconn International           | 1         | 0.47%   |
| Cambridge Silicon Radio         | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 37        | 17.37%  |
| Intel Bluetooth Device                              | 37        | 17.37%  |
| Intel AX200 Bluetooth                               | 26        | 12.21%  |
| Intel AX201 Bluetooth                               | 21        | 9.86%   |
| Realtek Bluetooth Radio                             | 13        | 6.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 5.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 3.29%   |
| Apple Bluetooth USB Host Controller                 | 6         | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.88%   |
| IMC Networks Wireless_Device                        | 4         | 1.88%   |
| Realtek Bluetooth Radio                             | 3         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.41%   |
| Lite-On Bluetooth Device                            | 3         | 1.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 1.41%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.94%   |
| Toshiba BCM43142A0                                  | 1         | 0.47%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.47%   |
| MediaTek Wireless_Device                            | 1         | 0.47%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.47%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.47%   |
| Foxconn / Hon Hai BT                                | 1         | 0.47%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 0.47%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.47%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.47%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.47%   |
| Broadcom HP Portable Valentine                      | 1         | 0.47%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.47%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.47%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.47%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 0.47%   |
| Broadcom BCM2045A0                                  | 1         | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.47%   |
| Apple Bluetooth Host Controller                     | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 164       | 52.9%   |
| AMD                                             | 60        | 19.35%  |
| Nvidia                                          | 46        | 14.84%  |
| C-Media Electronics                             | 6         | 1.94%   |
| Texas Instruments                               | 5         | 1.61%   |
| KORG                                            | 4         | 1.29%   |
| AKAI                                            | 4         | 1.29%   |
| Realtek Semiconductor                           | 3         | 0.97%   |
| Logitech                                        | 2         | 0.65%   |
| Lenovo                                          | 2         | 0.65%   |
| XMOS                                            | 1         | 0.32%   |
| Tdlasunnic                                      | 1         | 0.32%   |
| Sony                                            | 1         | 0.32%   |
| Samson Technologies                             | 1         | 0.32%   |
| Micro Star International                        | 1         | 0.32%   |
| M-Audio                                         | 1         | 0.32%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.32%   |
| JMTek                                           | 1         | 0.32%   |
| Generalplus Technology                          | 1         | 0.32%   |
| Focusrite-Novation                              | 1         | 0.32%   |
| Creative Technology                             | 1         | 0.32%   |
| Corsair                                         | 1         | 0.32%   |
| Apple                                           | 1         | 0.32%   |
| AKAI Professional M.I.                          | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 41        | 10.33%  |
| Intel Sunrise Point-LP HD Audio                                            | 36        | 9.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 28        | 7.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 3.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 3.27%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 3.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 3.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 2.52%   |
| AMD FCH Azalia Controller                                                  | 10        | 2.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.02%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 2.02%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 2.02%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 2.02%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 1.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.26%   |
| Nvidia Audio device                                                        | 5         | 1.26%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                              | 4         | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.01%   |
| KORG nanoKONTROL2 MIDI Controller                                          | 4         | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.01%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.01%   |
| AMD High Definition Audio Controller                                       | 4         | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.01%   |
| AKAI MPKmini2                                                              | 4         | 1.01%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.76%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3         | 0.76%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.5%    |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.5%    |
| C-Media Electronics USB Advanced Audio Device                              | 2         | 0.5%    |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 0.5%    |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.5%    |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.5%    |
| Texas Instruments PCM2912A Audio Codec                                     | 1         | 0.25%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1         | 0.25%   |
| Tdlasunnic Sharkoon Mobile DAC                                             | 1         | 0.25%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.25%   |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.25%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                 | 1         | 0.25%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.25%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.25%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.25%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.25%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 67        | 32.84%  |
| SK Hynix            | 53        | 25.98%  |
| Micron Technology   | 30        | 14.71%  |
| Kingston            | 8         | 3.92%   |
| Unknown             | 7         | 3.43%   |
| A-DATA Technology   | 7         | 3.43%   |
| Crucial             | 6         | 2.94%   |
| Corsair             | 5         | 2.45%   |
| Ramaxel Technology  | 4         | 1.96%   |
| Unknown (ABCD)      | 3         | 1.47%   |
| Elpida              | 3         | 1.47%   |
| Shenzhen Mic        | 2         | 0.98%   |
| G.Skill             | 2         | 0.98%   |
| V-GeN               | 1         | 0.49%   |
| Team                | 1         | 0.49%   |
| SMART Brazil        | 1         | 0.49%   |
| Sesame              | 1         | 0.49%   |
| Patriot             | 1         | 0.49%   |
| Nanya Technology    | 1         | 0.49%   |
| Kllisre             | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 7         | 3.15%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 5         | 2.25%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 5         | 2.25%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.25%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.8%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.8%    |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 1.8%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 1.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 1.8%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 4         | 1.8%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 1.8%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.35%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.35%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 1.35%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.35%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 3         | 1.35%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.9%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.9%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 2         | 0.9%    |
| SK Hynix RAM HMP351S6AFR8C-S6 4GB SODIMM DDR2 800MT/s            | 2         | 0.9%    |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.9%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.9%    |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s      | 2         | 0.9%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.9%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.9%    |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.9%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.9%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 2         | 0.9%    |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s         | 2         | 0.9%    |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s           | 2         | 0.9%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 0.9%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.9%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.9%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 2         | 0.9%    |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.9%    |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 0.9%    |
| V-GeN RAM D3R4GS16B8R 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.45%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.45%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s  | 1         | 0.45%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.45%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.45%   |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR4 3733MT/s             | 1         | 0.45%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1600MT/s                       | 1         | 0.45%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.45%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.45%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.45%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.45%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.45%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s           | 1         | 0.45%   |
| SK Hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.45%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.45%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.45%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB Row Of Chips DDR4 3200MT/s  | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 96        | 55.81%  |
| DDR3   | 61        | 35.47%  |
| LPDDR4 | 7         | 4.07%   |
| LPDDR3 | 6         | 3.49%   |
| DDR2   | 2         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 89.33%  |
| Row Of Chips | 14        | 7.87%   |
| Chip         | 4         | 2.25%   |
| DIMM         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 84        | 44.68%  |
| 4096  | 68        | 36.17%  |
| 16384 | 23        | 12.23%  |
| 2048  | 11        | 5.85%   |
| 32768 | 2         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 54        | 29.51%  |
| 3200  | 45        | 24.59%  |
| 2667  | 37        | 20.22%  |
| 2400  | 15        | 8.2%    |
| 3266  | 7         | 3.83%   |
| 2133  | 7         | 3.83%   |
| 1334  | 6         | 3.28%   |
| 1867  | 3         | 1.64%   |
| 1333  | 2         | 1.09%   |
| 800   | 2         | 1.09%   |
| 4267  | 1         | 0.55%   |
| 4266  | 1         | 0.55%   |
| 3733  | 1         | 0.55%   |
| 3000  | 1         | 0.55%   |
| 1067  | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 50%     |
| HP DeskJet 2130 series        | 1         | 50%     |

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
| Chicony Electronics                    | 46        | 23.35%  |
| IMC Networks                           | 28        | 14.21%  |
| Acer                                   | 18        | 9.14%   |
| Microdia                               | 15        | 7.61%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 7.11%   |
| Realtek Semiconductor                  | 12        | 6.09%   |
| Sunplus Innovation Technology          | 9         | 4.57%   |
| Lite-On Technology                     | 9         | 4.57%   |
| Syntek                                 | 8         | 4.06%   |
| Quanta                                 | 8         | 4.06%   |
| Apple                                  | 7         | 3.55%   |
| Logitech                               | 5         | 2.54%   |
| Suyin                                  | 3         | 1.52%   |
| Sonix Technology                       | 2         | 1.02%   |
| Primax Electronics                     | 2         | 1.02%   |
| Intel                                  | 2         | 1.02%   |
| Alcor Micro                            | 2         | 1.02%   |
| Silicon Motion                         | 1         | 0.51%   |
| Ricoh                                  | 1         | 0.51%   |
| MacroSilicon                           | 1         | 0.51%   |
| Luxvisions Innotech Limited            | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| Google                                 | 1         | 0.51%   |
| DJKANA1BIF866I                         | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 14        | 7.11%   |
| Chicony Integrated Camera                                      | 14        | 7.11%   |
| Chicony HD Webcam                                              | 10        | 5.08%   |
| Microdia Integrated_Webcam_HD                                  | 8         | 4.06%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 7         | 3.55%   |
| Realtek Integrated_Webcam_HD                                   | 5         | 2.54%   |
| Acer Integrated Camera                                         | 5         | 2.54%   |
| Syntek Integrated Camera                                       | 4         | 2.03%   |
| Lite-On Integrated Camera                                      | 4         | 2.03%   |
| Syntek Lenovo EasyCamera                                       | 3         | 1.52%   |
| Sunplus Integrated_Webcam_HD                                   | 3         | 1.52%   |
| Sunplus HD WebCam                                              | 3         | 1.52%   |
| Microdia Integrated Webcam                                     | 3         | 1.52%   |
| Lite-On HP Webcam                                              | 3         | 1.52%   |
| Chicony USB2.0 HD UVC WebCam                                   | 3         | 1.52%   |
| Chicony EasyCamera                                             | 3         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 3         | 1.52%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 3         | 1.52%   |
| Acer HD Webcam                                                 | 3         | 1.52%   |
| Acer EasyCamera                                                | 3         | 1.52%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 1.02%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.02%   |
| Quanta HP HD Camera                                            | 2         | 1.02%   |
| Logitech HD Pro Webcam C920                                    | 2         | 1.02%   |
| Lite-On HP Wide Vision HD Camera                               | 2         | 1.02%   |
| Intel RealSense 3D Camera (Front F200)                         | 2         | 1.02%   |
| IMC Networks ov9734_azurewave_camera                           | 2         | 1.02%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 2         | 1.02%   |
| Chicony HP Webcam                                              | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1.02%   |
| Acer SunplusIT Integrated Camera                               | 2         | 1.02%   |
| Syntek EasyCamera                                              | 1         | 0.51%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.51%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.51%   |
| Suyin HP TrueVision HD                                         | 1         | 0.51%   |
| Sunplus WebCamera                                              | 1         | 0.51%   |
| Sunplus Lenovo EasyCamera                                      | 1         | 0.51%   |
| Sunplus Asus Webcam                                            | 1         | 0.51%   |
| Silicon Motion Web Camera                                      | 1         | 0.51%   |
| Ricoh HD Webcam                                                | 1         | 0.51%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 0.51%   |
| Realtek USB HD Webcam                                          | 1         | 0.51%   |
| Realtek MTD Camera                                             | 1         | 0.51%   |
| Realtek Laptop_Integrated_Webcam_HD                            | 1         | 0.51%   |
| Realtek Integrated Webcam_HD                                   | 1         | 0.51%   |
| Realtek Integrated Webcam                                      | 1         | 0.51%   |
| Realtek EasyCamera                                             | 1         | 0.51%   |
| Quanta VGA WebCam                                              | 1         | 0.51%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 0.51%   |
| Quanta USB2.0 HD UVC WebCam                                    | 1         | 0.51%   |
| Quanta HD Webcam                                               | 1         | 0.51%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 0.51%   |
| Primax Dell Laptop Integrated Webcam 2Mpix                     | 1         | 0.51%   |
| Microdia Webcam Vitade AF                                      | 1         | 0.51%   |
| Microdia Laptop_Integrated_Webcam_FHD                          | 1         | 0.51%   |
| Microdia HP Integrated Webcam                                  | 1         | 0.51%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 0.51%   |
| MacroSilicon USB Video                                         | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 34.09%  |
| Validity Sensors           | 13        | 29.55%  |
| Shenzhen Goodix Technology | 10        | 22.73%  |
| LighTuning Technology      | 3         | 6.82%   |
| Elan Microelectronics      | 2         | 4.55%   |
| Upek                       | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 6         | 13.64%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 11.36%  |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 11.36%  |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 11.36%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 9.09%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 6.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 4.55%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.27%   |
| Validity Sensors VFS491                                                    | 1         | 2.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.27%   |
| Synaptics  WBDI                                                            | 1         | 2.27%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.27%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 57.89%  |
| Alcor Micro | 7         | 36.84%  |
| Lenovo      | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 35%     |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15%     |
| Broadcom 58200                                                               | 3         | 15%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5%      |
| Broadcom 5880                                                                | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 121       | 51.49%  |
| 1     | 91        | 38.72%  |
| 2     | 23        | 9.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 33.85%  |
| Net/ethernet             | 23        | 17.69%  |
| Chipcard                 | 18        | 13.85%  |
| Multimedia controller    | 15        | 11.54%  |
| Graphics card            | 13        | 10%     |
| Net/wireless             | 8         | 6.15%   |
| Bluetooth                | 4         | 3.08%   |
| Camera                   | 2         | 1.54%   |
| Storage                  | 1         | 0.77%   |
| Modem                    | 1         | 0.77%   |
| Communication controller | 1         | 0.77%   |


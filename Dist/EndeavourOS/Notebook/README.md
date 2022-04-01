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

Total: 359

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| HP            | Laptop 15-bw0xx             | [3500cd92bf](https://linux-hardware.org/?probe=3500cd92bf) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f070f33060](https://linux-hardware.org/?probe=f070f33060) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f2003c1f90](https://linux-hardware.org/?probe=f2003c1f90) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| Google        | Akemi                       | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| Dell          | Precision M6800             | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| ASUSTek       | G751JT                      | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Unknown       | Unknown                     | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Dell          | Latitude E5430 non-vPro     | [2d2bd57c8b](https://linux-hardware.org/?probe=2d2bd57c8b) | Mar 06, 2022 |
| HP            | ZBook 17 G2                 | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
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

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 183       | 74.69%  |
| EndeavourOS         | 62        | 25.31%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| EndeavourOS | 240       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.15.12-arch1-1    | 8         | 3%      |
| 5.13.13-arch1-1    | 7         | 2.62%   |
| 5.15.10-arch1-1    | 6         | 2.25%   |
| 5.9.14-arch1-1     | 5         | 1.87%   |
| 5.15.4-arch1-1     | 5         | 1.87%   |
| 5.9.1-arch1-1      | 4         | 1.5%    |
| 5.7.8-arch1-1      | 4         | 1.5%    |
| 5.16.8-arch1-1     | 4         | 1.5%    |
| 5.16.4-arch1-1     | 4         | 1.5%    |
| 5.16.10-arch1-1    | 4         | 1.5%    |
| 5.15.2-arch1-1     | 4         | 1.5%    |
| 5.14.9-arch2-1     | 4         | 1.5%    |
| 5.12.14-arch1-1    | 4         | 1.5%    |
| 5.11.16-arch1-1    | 4         | 1.5%    |
| 5.11.11-arch1-1    | 4         | 1.5%    |
| 5.9.8-arch1-1      | 3         | 1.12%   |
| 5.9.10-arch1-1     | 3         | 1.12%   |
| 5.16.14-arch1-1    | 3         | 1.12%   |
| 5.16.13-arch1-1    | 3         | 1.12%   |
| 5.15.6-zen2-1-zen  | 3         | 1.12%   |
| 5.14.6-arch1-1     | 3         | 1.12%   |
| 5.14.14-arch1-1    | 3         | 1.12%   |
| 5.12.13-arch1-2    | 3         | 1.12%   |
| 5.11.16-zen1-1-zen | 3         | 1.12%   |
| 5.10.15-arch1-1    | 3         | 1.12%   |
| 5.9.2-arch1-1      | 2         | 0.75%   |
| 5.7.10-arch1-1     | 2         | 0.75%   |
| 5.4.2-arch1-1      | 2         | 0.75%   |
| 5.17.1-arch1-1     | 2         | 0.75%   |
| 5.16.5-arch1-1     | 2         | 0.75%   |
| 5.16.2-arch1-1     | 2         | 0.75%   |
| 5.16.16-arch1-1    | 2         | 0.75%   |
| 5.16.12-arch1-1    | 2         | 0.75%   |
| 5.16.0-arch1-1     | 2         | 0.75%   |
| 5.15.7-arch1-1     | 2         | 0.75%   |
| 5.15.6-arch2-1     | 2         | 0.75%   |
| 5.15.4-zen1-1-zen  | 2         | 0.75%   |
| 5.15.29-1-lts      | 2         | 0.75%   |
| 5.15.2-zen1-1-zen  | 2         | 0.75%   |
| 5.15.18-1-lts      | 2         | 0.75%   |
| 5.15.11-arch2-1    | 2         | 0.75%   |
| 5.14.9-lqx4-1-lqx  | 2         | 0.75%   |
| 5.14.8-zen1-1-zen  | 2         | 0.75%   |
| 5.14.3-arch1-1     | 2         | 0.75%   |
| 5.14.16-arch1-1    | 2         | 0.75%   |
| 5.14.11-arch1-1    | 2         | 0.75%   |
| 5.13.9-arch1-1     | 2         | 0.75%   |
| 5.13.4-arch1-1     | 2         | 0.75%   |
| 5.13.13-lqx1-1-lqx | 2         | 0.75%   |
| 5.13.12-arch1-1    | 2         | 0.75%   |
| 5.13.10-arch1-1    | 2         | 0.75%   |
| 5.12.8-arch1-1     | 2         | 0.75%   |
| 5.12.5-zen1-1-zen  | 2         | 0.75%   |
| 5.12.5-arch1-1     | 2         | 0.75%   |
| 5.12.3-arch1-1     | 2         | 0.75%   |
| 5.11.8-arch1-1     | 2         | 0.75%   |
| 5.11.4-arch1-1     | 2         | 0.75%   |
| 5.11.14-zen1-1-zen | 2         | 0.75%   |
| 5.10.68-1-lts      | 2         | 0.75%   |
| 5.10.4-arch2-1     | 2         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.12 | 11        | 4.12%   |
| 5.13.13 | 10        | 3.75%   |
| 5.15.4  | 8         | 3%      |
| 5.15.2  | 7         | 2.62%   |
| 5.12.13 | 7         | 2.62%   |
| 5.11.16 | 7         | 2.62%   |
| 5.15.10 | 6         | 2.25%   |
| 5.14.9  | 6         | 2.25%   |
| 5.9.14  | 5         | 1.87%   |
| 5.9.1   | 5         | 1.87%   |
| 5.16.8  | 5         | 1.87%   |
| 5.16.4  | 5         | 1.87%   |
| 5.15.6  | 5         | 1.87%   |
| 5.11.11 | 5         | 1.87%   |
| 5.7.8   | 4         | 1.5%    |
| 5.16.14 | 4         | 1.5%    |
| 5.16.10 | 4         | 1.5%    |
| 5.14.6  | 4         | 1.5%    |
| 5.14.14 | 4         | 1.5%    |
| 5.13.4  | 4         | 1.5%    |
| 5.12.5  | 4         | 1.5%    |
| 5.12.14 | 4         | 1.5%    |
| 5.9.8   | 3         | 1.12%   |
| 5.9.10  | 3         | 1.12%   |
| 5.16.5  | 3         | 1.12%   |
| 5.16.13 | 3         | 1.12%   |
| 5.14.8  | 3         | 1.12%   |
| 5.13.9  | 3         | 1.12%   |
| 5.11.14 | 3         | 1.12%   |
| 5.10.15 | 3         | 1.12%   |
| 5.9.2   | 2         | 0.75%   |
| 5.8.12  | 2         | 0.75%   |
| 5.7.10  | 2         | 0.75%   |
| 5.4.2   | 2         | 0.75%   |
| 5.17.1  | 2         | 0.75%   |
| 5.16.7  | 2         | 0.75%   |
| 5.16.2  | 2         | 0.75%   |
| 5.16.16 | 2         | 0.75%   |
| 5.16.12 | 2         | 0.75%   |
| 5.16.1  | 2         | 0.75%   |
| 5.16.0  | 2         | 0.75%   |
| 5.15.7  | 2         | 0.75%   |
| 5.15.29 | 2         | 0.75%   |
| 5.15.18 | 2         | 0.75%   |
| 5.15.13 | 2         | 0.75%   |
| 5.15.11 | 2         | 0.75%   |
| 5.15.0  | 2         | 0.75%   |
| 5.14.3  | 2         | 0.75%   |
| 5.14.2  | 2         | 0.75%   |
| 5.14.16 | 2         | 0.75%   |
| 5.14.15 | 2         | 0.75%   |
| 5.14.11 | 2         | 0.75%   |
| 5.13.12 | 2         | 0.75%   |
| 5.13.10 | 2         | 0.75%   |
| 5.12.8  | 2         | 0.75%   |
| 5.12.3  | 2         | 0.75%   |
| 5.12.1  | 2         | 0.75%   |
| 5.11.8  | 2         | 0.75%   |
| 5.11.4  | 2         | 0.75%   |
| 5.10.68 | 2         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 51        | 19.84%  |
| 5.16    | 37        | 14.4%   |
| 5.14    | 30        | 11.67%  |
| 5.13    | 24        | 9.34%   |
| 5.12    | 24        | 9.34%   |
| 5.9     | 21        | 8.17%   |
| 5.11    | 21        | 8.17%   |
| 5.10    | 20        | 7.78%   |
| 5.8     | 9         | 3.5%    |
| 5.7     | 8         | 3.11%   |
| 5.4     | 6         | 2.33%   |
| 5.6     | 2         | 0.78%   |
| 5.17    | 2         | 0.78%   |
| 4.19    | 2         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 239       | 99.58%  |
| aarch64 | 1         | 0.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 68        | 27.2%   |
| KDE5            | 63        | 25.2%   |
| XFCE            | 58        | 23.2%   |
| X-Cinnamon      | 13        | 5.2%    |
| KDE             | 10        | 4%      |
| Unknown         | 7         | 2.8%    |
| i3              | 6         | 2.4%    |
| Cinnamon        | 6         | 2.4%    |
| Budgie          | 5         | 2%      |
| MATE            | 3         | 1.2%    |
| LXQt            | 3         | 1.2%    |
| sway            | 2         | 0.8%    |
| Deepin          | 2         | 0.8%    |
| awesome         | 2         | 0.8%    |
| LXDE            | 1         | 0.4%    |
| GNOME Flashback | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 182       | 74.59%  |
| Wayland | 50        | 20.49%  |
| Tty     | 6         | 2.46%   |
| Unknown | 6         | 2.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 67        | 26.91%  |
| Unknown | 59        | 23.69%  |
| SDDM    | 52        | 20.88%  |
| GDM     | 45        | 18.07%  |
| TDM     | 26        | 10.44%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 121       | 50.42%  |
| en_GB   | 23        | 9.58%   |
| en_CA   | 10        | 4.17%   |
| fr_FR   | 9         | 3.75%   |
| it_IT   | 7         | 2.92%   |
| en_IN   | 7         | 2.92%   |
| de_DE   | 7         | 2.92%   |
| en_AU   | 5         | 2.08%   |
| Unknown | 5         | 2.08%   |
| en_PH   | 4         | 1.67%   |
| en_NZ   | 4         | 1.67%   |
| tr_TR   | 3         | 1.25%   |
| ru_RU   | 3         | 1.25%   |
| pt_BR   | 3         | 1.25%   |
| pl_PL   | 3         | 1.25%   |
| sv_SE   | 2         | 0.83%   |
| pt_PT   | 2         | 0.83%   |
| nl_NL   | 2         | 0.83%   |
| es_MX   | 2         | 0.83%   |
| es_ES   | 2         | 0.83%   |
| es_AR   | 2         | 0.83%   |
| en_DK   | 2         | 0.83%   |
| ru_UA   | 1         | 0.42%   |
| nl_BE   | 1         | 0.42%   |
| id_ID   | 1         | 0.42%   |
| hu_HU   | 1         | 0.42%   |
| hr_HR   | 1         | 0.42%   |
| fi_FI   | 1         | 0.42%   |
| es_PY   | 1         | 0.42%   |
| en_MY   | 1         | 0.42%   |
| en_IL   | 1         | 0.42%   |
| de_AT   | 1         | 0.42%   |
| cs_CZ   | 1         | 0.42%   |
| an_ES   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 165       | 67.35%  |
| BIOS | 80        | 32.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 181       | 74.79%  |
| Btrfs   | 55        | 22.73%  |
| Overlay | 3         | 1.24%   |
| Xfs     | 1         | 0.41%   |
| Ext2    | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 161       | 65.71%  |
| Unknown | 63        | 25.71%  |
| MBR     | 21        | 8.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 91.29%  |
| Yes       | 21        | 8.71%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 181       | 73.88%  |
| Yes       | 64        | 26.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 73        | 30.42%  |
| Dell                | 36        | 15%     |
| Hewlett-Packard     | 34        | 14.17%  |
| ASUSTek Computer    | 31        | 12.92%  |
| Acer                | 17        | 7.08%   |
| Apple               | 9         | 3.75%   |
| MSI                 | 8         | 3.33%   |
| HUAWEI              | 6         | 2.5%    |
| Toshiba             | 3         | 1.25%   |
| Notebook            | 3         | 1.25%   |
| Unknown             | 3         | 1.25%   |
| Timi                | 2         | 0.83%   |
| Schenker            | 2         | 0.83%   |
| TUXEDO              | 1         | 0.42%   |
| TrekStor            | 1         | 0.42%   |
| Samsung Electronics | 1         | 0.42%   |
| Razer               | 1         | 0.42%   |
| Radxa               | 1         | 0.42%   |
| Pine Microsystems   | 1         | 0.42%   |
| Google              | 1         | 0.42%   |
| Gigabyte Technology | 1         | 0.42%   |
| Framework           | 1         | 0.42%   |
| Eluktronics         | 1         | 0.42%   |
| Dynabook            | 1         | 0.42%   |
| AMI                 | 1         | 0.42%   |
| Alienware           | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                                   | 4         | 1.67%   |
| Lenovo ThinkPad X140e 20BL000BUS                      | 3         | 1.25%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV                 | 3         | 1.25%   |
| Unknown                                               | 3         | 1.25%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB                  | 2         | 0.83%   |
| Lenovo IdeaPad FLEX-14API 81SS                        | 2         | 0.83%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 2         | 0.83%   |
| HUAWEI MACH-WX9                                       | 2         | 0.83%   |
| HP Pavilion Gaming Laptop 15-cx0xxx                   | 2         | 0.83%   |
| HP ENVY Laptop 13-ba0xxx                              | 2         | 0.83%   |
| HP 255 G7 Notebook PC                                 | 2         | 0.83%   |
| Dell Inspiron 3542                                    | 2         | 0.83%   |
| Dell G7 7588                                          | 2         | 0.83%   |
| Dell G3 3500                                          | 2         | 0.83%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR                 | 2         | 0.83%   |
| ASUS G752VT                                           | 2         | 0.83%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.42%   |
| TrekStor Primebook P14                                | 1         | 0.42%   |
| Toshiba Satellite Pro C50-A-1E6                       | 1         | 0.42%   |
| Toshiba Satellite P750                                | 1         | 0.42%   |
| Toshiba Satellite L50D-B                              | 1         | 0.42%   |
| Timi TM1607                                           | 1         | 0.42%   |
| Timi A35S                                             | 1         | 0.42%   |
| Schenker XMG NEO 15(E20, RTX 20xx)                    | 1         | 0.42%   |
| Schenker XMG FUSION 15 (XFU15L19)                     | 1         | 0.42%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.42%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.42%   |
| Radxa ROCK Pi X                                       | 1         | 0.42%   |
| Pine Microsystems Pine64 Pinebook Pro                 | 1         | 0.42%   |
| Notebook W65_67SZ                                     | 1         | 0.42%   |
| Notebook W65KJ1_KK1                                   | 1         | 0.42%   |
| Notebook NH5x_7xDPx                                   | 1         | 0.42%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.42%   |
| MSI Modern 14 B5M                                     | 1         | 0.42%   |
| MSI GT80S 6QE                                         | 1         | 0.42%   |
| MSI GS63VR 6RF                                        | 1         | 0.42%   |
| MSI GP66 Leopard 10UH                                 | 1         | 0.42%   |
| MSI GL75 Leopard 10SDK                                | 1         | 0.42%   |
| MSI GE72 6QD                                          | 1         | 0.42%   |
| MSI Bravo 15 B5DD                                     | 1         | 0.42%   |
| Lenovo Z50-70 20354                                   | 1         | 0.42%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.42%   |
| Lenovo Yoga S740-14IIL 81RS                           | 1         | 0.42%   |
| Lenovo Yoga 700-14ISK 80QD                            | 1         | 0.42%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.42%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.42%   |
| Lenovo V14 G2 ITL 82NM                                | 1         | 0.42%   |
| Lenovo ThinkPad X240 20AMS2QDOC                       | 1         | 0.42%   |
| Lenovo ThinkPad X240 20AMA2F8MS                       | 1         | 0.42%   |
| Lenovo ThinkPad X220 Tablet 4294CT0                   | 1         | 0.42%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 0.42%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0ET00              | 1         | 0.42%   |
| Lenovo ThinkPad T61 7659W1W                           | 1         | 0.42%   |
| Lenovo ThinkPad T560 20FJS4FV00                       | 1         | 0.42%   |
| Lenovo ThinkPad T520 4239CTO                          | 1         | 0.42%   |
| Lenovo ThinkPad T510 4384FF3                          | 1         | 0.42%   |
| Lenovo ThinkPad T480 20L6S3S500                       | 1         | 0.42%   |
| Lenovo ThinkPad T480 20L5S1S000                       | 1         | 0.42%   |
| Lenovo ThinkPad T470 W10DG 20JNS0DB00                 | 1         | 0.42%   |
| Lenovo ThinkPad T470 20HES2SF00                       | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 39        | 16.25%  |
| Lenovo IdeaPad           | 20        | 8.33%   |
| Dell Latitude            | 12        | 5%      |
| ASUS ROG                 | 12        | 5%      |
| Dell Inspiron            | 11        | 4.58%   |
| Acer Aspire              | 10        | 4.17%   |
| HP Pavilion              | 7         | 2.92%   |
| HP Laptop                | 7         | 2.92%   |
| HP EliteBook             | 7         | 2.92%   |
| HP ENVY                  | 5         | 2.08%   |
| Dell Precision           | 5         | 2.08%   |
| Apple MacBookAir7        | 4         | 1.67%   |
| Toshiba Satellite        | 3         | 1.25%   |
| Lenovo Yoga              | 3         | 1.25%   |
| Lenovo ThinkBook         | 3         | 1.25%   |
| HP 255                   | 3         | 1.25%   |
| Dell G3                  | 3         | 1.25%   |
| ASUS TUF                 | 3         | 1.25%   |
| Unknown                  | 3         | 1.25%   |
| Schenker XMG             | 2         | 0.83%   |
| Lenovo Legion            | 2         | 0.83%   |
| HUAWEI MACH-WX9          | 2         | 0.83%   |
| Dell XPS                 | 2         | 0.83%   |
| Dell G7                  | 2         | 0.83%   |
| ASUS VivoBook            | 2         | 0.83%   |
| ASUS G752VT              | 2         | 0.83%   |
| ASUS ASUS                | 2         | 0.83%   |
| Acer Swift               | 2         | 0.83%   |
| Acer Extensa             | 2         | 0.83%   |
| TUXEDO Pulse             | 1         | 0.42%   |
| TrekStor Primebook       | 1         | 0.42%   |
| Timi TM1607              | 1         | 0.42%   |
| Timi A35S                | 1         | 0.42%   |
| Samsung 340XAA           | 1         | 0.42%   |
| Razer Blade              | 1         | 0.42%   |
| Radxa ROCK               | 1         | 0.42%   |
| Pine Microsystems Pine64 | 1         | 0.42%   |
| Notebook W65KJ1          | 1         | 0.42%   |
| Notebook W65             | 1         | 0.42%   |
| Notebook NH5x            | 1         | 0.42%   |
| MSI Prestige             | 1         | 0.42%   |
| MSI Modern               | 1         | 0.42%   |
| MSI GT80S                | 1         | 0.42%   |
| MSI GS63VR               | 1         | 0.42%   |
| MSI GP66                 | 1         | 0.42%   |
| MSI GL75                 | 1         | 0.42%   |
| MSI GE72                 | 1         | 0.42%   |
| MSI Bravo                | 1         | 0.42%   |
| Lenovo Z50-70            | 1         | 0.42%   |
| Lenovo Y520-15IKBN       | 1         | 0.42%   |
| Lenovo V330-14IKB        | 1         | 0.42%   |
| Lenovo V14               | 1         | 0.42%   |
| Lenovo G505s             | 1         | 0.42%   |
| Lenovo E31-80            | 1         | 0.42%   |
| HUAWEI KLVL-WXX9         | 1         | 0.42%   |
| HUAWEI HN-WX9X           | 1         | 0.42%   |
| HUAWEI HLYL-WXX9         | 1         | 0.42%   |
| HUAWEI BOHK-WAX9X        | 1         | 0.42%   |
| HP ZBook                 | 1         | 0.42%   |
| HP Stream                | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 37        | 15.42%  |
| 2021    | 31        | 12.92%  |
| 2019    | 25        | 10.42%  |
| 2018    | 22        | 9.17%   |
| 2017    | 21        | 8.75%   |
| 2015    | 18        | 7.5%    |
| 2016    | 17        | 7.08%   |
| 2013    | 17        | 7.08%   |
| 2014    | 15        | 6.25%   |
| 2012    | 14        | 5.83%   |
| 2011    | 9         | 3.75%   |
| 2010    | 6         | 2.5%    |
| 2008    | 4         | 1.67%   |
| 2022    | 1         | 0.42%   |
| 2009    | 1         | 0.42%   |
| 2007    | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 240       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 240       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 239       | 99.58%  |
| Yes  | 1         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 79        | 32.78%  |
| 8.01-16.0   | 55        | 22.82%  |
| 16.01-24.0  | 52        | 21.58%  |
| 3.01-4.0    | 30        | 12.45%  |
| 32.01-64.0  | 19        | 7.88%   |
| 24.01-32.0  | 3         | 1.24%   |
| 64.01-256.0 | 2         | 0.83%   |
| 1.01-2.0    | 1         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 80        | 30.53%  |
| 1.01-2.0   | 72        | 27.48%  |
| 3.01-4.0   | 44        | 16.79%  |
| 4.01-8.0   | 40        | 15.27%  |
| 0.51-1.0   | 17        | 6.49%   |
| 8.01-16.0  | 6         | 2.29%   |
| 0.01-0.5   | 2         | 0.76%   |
| 16.01-24.0 | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 167       | 68.16%  |
| 2      | 68        | 27.76%  |
| 3      | 7         | 2.86%   |
| 4      | 2         | 0.82%   |
| 0      | 1         | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 184       | 76.35%  |
| Yes       | 57        | 23.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 77.5%   |
| No        | 54        | 22.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 238       | 98.76%  |
| No        | 3         | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 91.7%   |
| No        | 20        | 8.3%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 55        | 22.73%  |
| Germany     | 13        | 5.37%   |
| France      | 12        | 4.96%   |
| UK          | 10        | 4.13%   |
| India       | 10        | 4.13%   |
| Canada      | 10        | 4.13%   |
| Italy       | 9         | 3.72%   |
| Poland      | 8         | 3.31%   |
| Brazil      | 8         | 3.31%   |
| Netherlands | 7         | 2.89%   |
| Turkey      | 6         | 2.48%   |
| Russia      | 6         | 2.48%   |
| Sweden      | 5         | 2.07%   |
| Finland     | 5         | 2.07%   |
| Australia   | 5         | 2.07%   |
| Philippines | 4         | 1.65%   |
| New Zealand | 4         | 1.65%   |
| Mexico      | 4         | 1.65%   |
| Indonesia   | 4         | 1.65%   |
| Vietnam     | 3         | 1.24%   |
| Ukraine     | 3         | 1.24%   |
| Spain       | 3         | 1.24%   |
| Portugal    | 3         | 1.24%   |
| Norway      | 3         | 1.24%   |
| Greece      | 3         | 1.24%   |
| Belgium     | 3         | 1.24%   |
| Bahrain     | 3         | 1.24%   |
| Romania     | 2         | 0.83%   |
| Hong Kong   | 2         | 0.83%   |
| Georgia     | 2         | 0.83%   |
| Denmark     | 2         | 0.83%   |
| Czechia     | 2         | 0.83%   |
| Croatia     | 2         | 0.83%   |
| Argentina   | 2         | 0.83%   |
| Uruguay     | 1         | 0.41%   |
| Thailand    | 1         | 0.41%   |
| Taiwan      | 1         | 0.41%   |
| South Korea | 1         | 0.41%   |
| Slovenia    | 1         | 0.41%   |
| Slovakia    | 1         | 0.41%   |
| Puerto Rico | 1         | 0.41%   |
| Paraguay    | 1         | 0.41%   |
| Pakistan    | 1         | 0.41%   |
| Morocco     | 1         | 0.41%   |
| Malaysia    | 1         | 0.41%   |
| Israel      | 1         | 0.41%   |
| Hungary     | 1         | 0.41%   |
| Egypt       | 1         | 0.41%   |
| Colombia    | 1         | 0.41%   |
| Bulgaria    | 1         | 0.41%   |
| Brunei      | 1         | 0.41%   |
| Bangladesh  | 1         | 0.41%   |
| Austria     | 1         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Toms River        | 6         | 2.37%   |
| Montreal          | 5         | 1.98%   |
| Barberton         | 4         | 1.58%   |
| Victoria          | 3         | 1.19%   |
| Sydney            | 3         | 1.19%   |
| Moscow            | 3         | 1.19%   |
| Manama            | 3         | 1.19%   |
| Jacksonville      | 3         | 1.19%   |
| Berlin            | 3         | 1.19%   |
| Amsterdam         | 3         | 1.19%   |
| Yuma              | 2         | 0.79%   |
| Warsaw            | 2         | 0.79%   |
| Turku             | 2         | 0.79%   |
| Tbilisi           | 2         | 0.79%   |
| St Petersburg     | 2         | 0.79%   |
| Sao Paulo         | 2         | 0.79%   |
| Recife            | 2         | 0.79%   |
| Portland          | 2         | 0.79%   |
| Paris             | 2         | 0.79%   |
| Orlando           | 2         | 0.79%   |
| Mesa              | 2         | 0.79%   |
| Krakow            | 2         | 0.79%   |
| Ho Chi Minh City  | 2         | 0.79%   |
| Helsinki          | 2         | 0.79%   |
| Gothenburg        | 2         | 0.79%   |
| Frankfurt am Main | 2         | 0.79%   |
| Florence          | 2         | 0.79%   |
| Elk Grove         | 2         | 0.79%   |
| Chicago           | 2         | 0.79%   |
| Central           | 2         | 0.79%   |
| Cagayan de Oro    | 2         | 0.79%   |
| Brussels          | 2         | 0.79%   |
| Bengaluru         | 2         | 0.79%   |
| Bandung           | 2         | 0.79%   |
| Auckland          | 2         | 0.79%   |
| Ankara            | 2         | 0.79%   |
| Г…lesund       | 1         | 0.4%    |
| Zapopan           | 1         | 0.4%    |
| Wroclaw           | 1         | 0.4%    |
| Wilmington        | 1         | 0.4%    |
| Whittier          | 1         | 0.4%    |
| Wellington        | 1         | 0.4%    |
| Vrbovec           | 1         | 0.4%    |
| Villa Ballester   | 1         | 0.4%    |
| Velika Gorica     | 1         | 0.4%    |
| Valparaiso        | 1         | 0.4%    |
| Valence           | 1         | 0.4%    |
| Turin             | 1         | 0.4%    |
| Toronto           | 1         | 0.4%    |
| Tervakoski        | 1         | 0.4%    |
| Tel Aviv          | 1         | 0.4%    |
| Tarsus            | 1         | 0.4%    |
| Tampere           | 1         | 0.4%    |
| Stockholm         | 1         | 0.4%    |
| Srinagar          | 1         | 0.4%    |
| Sofia             | 1         | 0.4%    |
| Ski               | 1         | 0.4%    |
| Sint-Amands       | 1         | 0.4%    |
| Silverdale        | 1         | 0.4%    |
| Secaucus          | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 71        | 94     | 22.12%  |
| Seagate                        | 36        | 38     | 11.21%  |
| WDC                            | 28        | 33     | 8.72%   |
| SK Hynix                       | 18        | 19     | 5.61%   |
| Sandisk                        | 17        | 18     | 5.3%    |
| Kingston                       | 17        | 21     | 5.3%    |
| Toshiba                        | 16        | 18     | 4.98%   |
| HGST                           | 13        | 16     | 4.05%   |
| Intel                          | 10        | 11     | 3.12%   |
| Unknown                        | 8         | 11     | 2.49%   |
| Crucial                        | 7         | 8      | 2.18%   |
| Apple                          | 7         | 7      | 2.18%   |
| Micron Technology              | 6         | 6      | 1.87%   |
| KIOXIA                         | 6         | 6      | 1.87%   |
| A-DATA Technology              | 5         | 6      | 1.56%   |
| Phison                         | 4         | 4      | 1.25%   |
| LITEONIT                       | 4         | 5      | 1.25%   |
| Transcend                      | 3         | 3      | 0.93%   |
| Hitachi                        | 3         | 3      | 0.93%   |
| WDC WDS                        | 2         | 2      | 0.62%   |
| Solid State Storage Technology | 2         | 2      | 0.62%   |
| Mushkin                        | 2         | 2      | 0.62%   |
| Maxone                         | 2         | 2      | 0.62%   |
| LITEON                         | 2         | 2      | 0.62%   |
| KingSpec                       | 2         | 2      | 0.62%   |
| HFS256G3                       | 2         | 2      | 0.62%   |
| Fujitsu                        | 2         | 2      | 0.62%   |
| China                          | 2         | 2      | 0.62%   |
| XPG                            | 1         | 1      | 0.31%   |
| V-GeN                          | 1         | 1      | 0.31%   |
| USB3.0                         | 1         | 1      | 0.31%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.31%   |
| Teclast                        | 1         | 2      | 0.31%   |
| Team                           | 1         | 2      | 0.31%   |
| StoreJet                       | 1         | 1      | 0.31%   |
| SSSTC                          | 1         | 1      | 0.31%   |
| PNY                            | 1         | 1      | 0.31%   |
| OCZ                            | 1         | 1      | 0.31%   |
| Micron/Crucial Technology      | 1         | 1      | 0.31%   |
| Lite-On                        | 1         | 1      | 0.31%   |
| Lenovo                         | 1         | 1      | 0.31%   |
| KingFast                       | 1         | 1      | 0.31%   |
| KingDian                       | 1         | 1      | 0.31%   |
| JMicron                        | 1         | 1      | 0.31%   |
| HUAWEI                         | 1         | 1      | 0.31%   |
| GOODRAM                        | 1         | 1      | 0.31%   |
| Gigabyte Technology            | 1         | 1      | 0.31%   |
| Generic-                       | 1         | 1      | 0.31%   |
| FORESEE                        | 1         | 1      | 0.31%   |
| Corsair                        | 1         | 1      | 0.31%   |
| APPLE HD                       | 1         | 1      | 0.31%   |
| AMicro                         | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 11        | 3.31%   |
| HGST HTS721010A9E630 1TB                  | 7         | 2.11%   |
| Seagate ST500LT012-1DG142 500GB           | 6         | 1.81%   |
| Samsung SSD 860 EVO 250GB                 | 5         | 1.51%   |
| Samsung SSD 970 EVO 500GB                 | 4         | 1.2%    |
| Samsung SSD 870 EVO 250GB                 | 4         | 1.2%    |
| Samsung NVMe SSD Drive 512GB              | 4         | 1.2%    |
| Kingston SA400S37240G 240GB SSD           | 4         | 1.2%    |
| Apple SSD SM0128G 121GB                   | 4         | 1.2%    |
| WDC WD10SPZX-24Z10 1TB                    | 3         | 0.9%    |
| Transcend TS240GMTS420S 240GB SSD         | 3         | 0.9%    |
| Seagate ST1000LM049-2GH172 1TB            | 3         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 3         | 0.9%    |
| Samsung SSD 860 EVO 500GB                 | 3         | 0.9%    |
| Samsung SSD 860 EVO 1TB                   | 3         | 0.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 2         | 0.6%    |
| WDC WDS 500G2B0B-00YS70 500GB SSD         | 2         | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB                  | 2         | 0.6%    |
| Unknown MMC Card  64GB                    | 2         | 0.6%    |
| Toshiba MQ01ABD100 1TB                    | 2         | 0.6%    |
| Toshiba KBG40ZNT512G MEMORY 512GB         | 2         | 0.6%    |
| Solid State Storage NVMe SSD Drive 256GB  | 2         | 0.6%    |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 2         | 0.6%    |
| SK Hynix HFM128GDJTNG-8310A 128GB         | 2         | 0.6%    |
| SK Hynix HFM001TD3JX013N 1TB              | 2         | 0.6%    |
| Seagate ST2000LM015-2E8174 2TB            | 2         | 0.6%    |
| Sandisk NVMe SSD Drive 1TB                | 2         | 0.6%    |
| Samsung SSD 970 EVO 1TB                   | 2         | 0.6%    |
| Samsung SSD 870 QVO 1TB                   | 2         | 0.6%    |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.6%    |
| Samsung SSD 850 EVO 250GB                 | 2         | 0.6%    |
| Samsung NVMe SSD Drive 1TB                | 2         | 0.6%    |
| Samsung MZYTY256HDHP-000L2 256GB SSD      | 2         | 0.6%    |
| Samsung MZVLB256HAHQ-000H1 256GB          | 2         | 0.6%    |
| Samsung MZVLB1T0HBLR-00000 1TB            | 2         | 0.6%    |
| Samsung MZVL21T0HCLR-00B00 1TB            | 2         | 0.6%    |
| Samsung MZNLN256HAJQ-000H1 256GB SSD      | 2         | 0.6%    |
| Samsung MZ7TY256HDHP-000L7 256GB SSD      | 2         | 0.6%    |
| Maxone USB 3.0 160GB                      | 2         | 0.6%    |
| KIOXIA KBG40ZNV512G 512GB                 | 2         | 0.6%    |
| KIOXIA KBG40ZNV1T02 1TB                   | 2         | 0.6%    |
| Kingston SA400S37120G 120GB SSD           | 2         | 0.6%    |
| Kingston OM8PCP3512F-AI1 512GB            | 2         | 0.6%    |
| Kingston OM8PCP3512F-AB 512GB             | 2         | 0.6%    |
| Intel SSDPEKNW512G8H 512GB                | 2         | 0.6%    |
| Intel NVMe SSD Drive 512GB                | 2         | 0.6%    |
| Hitachi HTS545050A7E380 500GB             | 2         | 0.6%    |
| HGST HTS541010B7E610 1TB                  | 2         | 0.6%    |
| HFS256G3 9TND-N210A 256GB                 | 2         | 0.6%    |
| Crucial CT250MX500SSD1 250GB              | 2         | 0.6%    |
| XPG NVMe SSD Drive 2TB                    | 1         | 0.3%    |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 0.3%    |
| WDC WDS250G2B0A-00SM50 250GB SSD          | 1         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 0.3%    |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.3%    |
| WDC WD5000LPVT-22G33T0 500GB              | 1         | 0.3%    |
| WDC WD5000LPCX-24C6HT0 500GB              | 1         | 0.3%    |
| WDC WD5000BEVT-60ZAT1 500GB               | 1         | 0.3%    |
| WDC WD1600BEVT-22ZCT0 160GB               | 1         | 0.3%    |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 33        | 34     | 42.86%  |
| WDC      | 14        | 16     | 18.18%  |
| HGST     | 13        | 16     | 16.88%  |
| Toshiba  | 7         | 7      | 9.09%   |
| Hitachi  | 3         | 3      | 3.9%    |
| Maxone   | 2         | 2      | 2.6%    |
| Fujitsu  | 2         | 2      | 2.6%    |
| Unknown  | 1         | 1      | 1.3%    |
| StoreJet | 1         | 1      | 1.3%    |
| Generic- | 1         | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 54     | 33.61%  |
| Kingston            | 12        | 16     | 9.84%   |
| SanDisk             | 10        | 10     | 8.2%    |
| WDC                 | 6         | 8      | 4.92%   |
| Apple               | 6         | 6      | 4.92%   |
| Crucial             | 5         | 5      | 4.1%    |
| SK Hynix            | 4         | 4      | 3.28%   |
| LITEONIT            | 4         | 5      | 3.28%   |
| Transcend           | 3         | 3      | 2.46%   |
| A-DATA Technology   | 3         | 4      | 2.46%   |
| WDC WDS             | 2         | 2      | 1.64%   |
| Toshiba             | 2         | 2      | 1.64%   |
| Mushkin             | 2         | 2      | 1.64%   |
| Micron Technology   | 2         | 2      | 1.64%   |
| KingSpec            | 2         | 2      | 1.64%   |
| China               | 2         | 2      | 1.64%   |
| V-GeN               | 1         | 1      | 0.82%   |
| USB3.0              | 1         | 1      | 0.82%   |
| Unknown             | 1         | 2      | 0.82%   |
| Teclast             | 1         | 2      | 0.82%   |
| Team                | 1         | 2      | 0.82%   |
| Seagate             | 1         | 1      | 0.82%   |
| PNY                 | 1         | 1      | 0.82%   |
| OCZ                 | 1         | 1      | 0.82%   |
| LITEON              | 1         | 1      | 0.82%   |
| KingFast            | 1         | 1      | 0.82%   |
| KingDian            | 1         | 1      | 0.82%   |
| Intel               | 1         | 1      | 0.82%   |
| GOODRAM             | 1         | 1      | 0.82%   |
| Gigabyte Technology | 1         | 1      | 0.82%   |
| FORESEE             | 1         | 1      | 0.82%   |
| Corsair             | 1         | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 106       | 146    | 35.45%  |
| NVMe    | 103       | 126    | 34.45%  |
| HDD     | 76        | 83     | 25.42%  |
| MMC     | 7         | 9      | 2.34%   |
| Unknown | 7         | 7      | 2.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 154       | 216    | 55.2%   |
| NVMe | 103       | 126    | 36.92%  |
| SAS  | 15        | 20     | 5.38%   |
| MMC  | 7         | 9      | 2.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 114       | 155    | 63.33%  |
| 0.51-1.0   | 61        | 68     | 33.89%  |
| 1.01-2.0   | 5         | 6      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 25.81%  |
| 251-500        | 58        | 23.39%  |
| 501-1000       | 39        | 15.73%  |
| 1001-2000      | 29        | 11.69%  |
| Unknown        | 17        | 6.85%   |
| 51-100         | 12        | 4.84%   |
| More than 3000 | 11        | 4.44%   |
| 21-50          | 7         | 2.82%   |
| 2001-3000      | 6         | 2.42%   |
| 1-20           | 5         | 2.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 62        | 24.12%  |
| 21-50          | 50        | 19.46%  |
| 101-250        | 45        | 17.51%  |
| 51-100         | 34        | 13.23%  |
| 251-500        | 25        | 9.73%   |
| Unknown        | 17        | 6.61%   |
| 1001-2000      | 10        | 3.89%   |
| 501-1000       | 10        | 3.89%   |
| More than 3000 | 2         | 0.78%   |
| 2001-3000      | 2         | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 3         | 3      | 15%     |
| Hitachi HTS545050A7E380 500GB                    | 2         | 2      | 10%     |
| WDC WD5000LPVT-22G33T0 500GB                     | 1         | 1      | 5%      |
| WDC WD10SPZX-24Z10T0 1TB                         | 1         | 1      | 5%      |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 5%      |
| Transcend TS240GMTS420S 240GB SSD                | 1         | 1      | 5%      |
| Toshiba MK5055GSXF 500GB                         | 1         | 1      | 5%      |
| SK Hynix SC308 SATA 128GB SSD                    | 1         | 1      | 5%      |
| Seagate ST500LX012-SSHD-8GB                      | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5%      |
| Seagate ST1000LM049-2GH172 1TB                   | 1         | 1      | 5%      |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 5%      |
| Samsung Electronics SSD 970 EVO 500GB            | 1         | 1      | 5%      |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5%      |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 5%      |
| Fujitsu MHZ2320BH G2 320GB                       | 1         | 1      | 5%      |
| Apple SSD SM256C 256GB                           | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 4      | 20%     |
| WDC                 | 3         | 3      | 15%     |
| Seagate             | 3         | 3      | 15%     |
| Samsung Electronics | 2         | 2      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| Transcend           | 1         | 1      | 5%      |
| Toshiba             | 1         | 1      | 5%      |
| SK Hynix            | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |
| Apple               | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 4      | 28.57%  |
| WDC     | 3         | 3      | 21.43%  |
| Seagate | 3         | 3      | 21.43%  |
| Hitachi | 2         | 2      | 14.29%  |
| Toshiba | 1         | 1      | 7.14%   |
| Fujitsu | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 70%     |
| SSD  | 5         | 5      | 25%     |
| NVMe | 1         | 1      | 5%      |

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
| Works    | 163       | 232    | 62.21%  |
| Detected | 78        | 118    | 29.77%  |
| Malfunc  | 20        | 20     | 7.63%   |
| Failed   | 1         | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 148       | 50.68%  |
| Samsung Electronics            | 37        | 12.67%  |
| AMD                            | 35        | 11.99%  |
| Sandisk                        | 14        | 4.79%   |
| SK Hynix                       | 13        | 4.45%   |
| KIOXIA                         | 9         | 3.08%   |
| Kingston Technology Company    | 5         | 1.71%   |
| Toshiba America Info Systems   | 4         | 1.37%   |
| Phison Electronics             | 4         | 1.37%   |
| Micron Technology              | 4         | 1.37%   |
| Solid State Storage Technology | 3         | 1.03%   |
| Micron/Crucial Technology      | 3         | 1.03%   |
| ADATA Technology               | 3         | 1.03%   |
| Seagate Technology             | 2         | 0.68%   |
| Lite-On Technology             | 2         | 0.68%   |
| Union Memory (Shenzhen)        | 1         | 0.34%   |
| Nvidia                         | 1         | 0.34%   |
| Marvell Technology Group       | 1         | 0.34%   |
| Lenovo                         | 1         | 0.34%   |
| JMicron Technology             | 1         | 0.34%   |
| Apple                          | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 10.82%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 30        | 9.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 7.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 6.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 3.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 3.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 3.28%   |
| KIOXIA Non-Volatile memory controller                                          | 9         | 2.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 2.62%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 2.3%    |
| Intel SSD 660P Series                                                          | 6         | 1.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.97%   |
| SK Hynix Gold P31 SSD                                                          | 5         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.64%   |
| SK Hynix Non-Volatile memory controller                                        | 4         | 1.31%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.31%   |
| Samsung Electronics SATA controller                                            | 4         | 1.31%   |
| Micron Non-Volatile memory controller                                          | 4         | 1.31%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.31%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 4         | 1.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.31%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 4         | 1.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.98%   |
| Solid State Storage Non-Volatile memory controller                             | 3         | 0.98%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.98%   |
| Sandisk Non-Volatile memory controller                                         | 3         | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.98%   |
| SK Hynix BC511                                                                 | 2         | 0.66%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 2         | 0.66%   |
| Sandisk WD Blue SN570 NVMe SSD                                                 | 2         | 0.66%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.66%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.66%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.66%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 0.66%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.66%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 0.66%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.33%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.33%   |
| Seagate Non-Volatile memory controller                                         | 1         | 0.33%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.33%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.33%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.33%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.33%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.33%   |
| Lite-On NVMe Controller                                                        | 1         | 0.33%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.33%   |
| Lenovo Non-Volatile memory controller                                          | 1         | 0.33%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.33%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 0.33%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.33%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 161       | 55.33%  |
| NVMe | 102       | 35.05%  |
| RAID | 24        | 8.25%   |
| IDE  | 4         | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 176       | 73.33%  |
| AMD    | 63        | 26.25%  |
| ARM    | 1         | 0.42%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 3.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 2.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.08%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 2.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 2.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 2.08%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 2.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.67%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.25%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 3         | 1.25%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.25%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.25%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 1.25%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.25%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 3         | 1.25%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.83%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.83%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 2         | 0.83%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 2         | 0.83%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 0.83%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.83%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 2         | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.83%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.83%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.83%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.83%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.83%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 2         | 0.83%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.83%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.83%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 2         | 0.83%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 2         | 0.83%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.83%   |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 2         | 0.83%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.83%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.83%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.83%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 0.83%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.42%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.42%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.42%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.42%   |
| Intel Core i7-6820HK CPU @ 2.70GHz            | 1         | 0.42%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.42%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.42%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.42%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.42%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 69        | 28.75%  |
| Intel Core i7        | 65        | 27.08%  |
| Intel Core i3        | 16        | 6.67%   |
| AMD Ryzen 7          | 16        | 6.67%   |
| Other                | 15        | 6.25%   |
| AMD Ryzen 5          | 12        | 5%      |
| AMD Ryzen 9          | 7         | 2.92%   |
| AMD A4               | 7         | 2.92%   |
| AMD Ryzen 7 PRO      | 6         | 2.5%    |
| Intel Core 2 Duo     | 5         | 2.08%   |
| Intel Celeron        | 4         | 1.67%   |
| AMD Ryzen 3          | 3         | 1.25%   |
| AMD A8               | 3         | 1.25%   |
| AMD E1               | 2         | 0.83%   |
| Intel Xeon           | 1         | 0.42%   |
| Intel Pentium        | 1         | 0.42%   |
| Intel Core m3        | 1         | 0.42%   |
| Intel Core 2 Extreme | 1         | 0.42%   |
| Intel Atom           | 1         | 0.42%   |
| AMD Ryzen 5 PRO      | 1         | 0.42%   |
| AMD E                | 1         | 0.42%   |
| AMD Athlon II        | 1         | 0.42%   |
| AMD Athlon           | 1         | 0.42%   |
| AMD A10              | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 98        | 40.83%  |
| 4      | 88        | 36.67%  |
| 8      | 33        | 13.75%  |
| 6      | 21        | 8.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 239       | 99.58%  |
| 2      | 1         | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 206       | 85.83%  |
| 1      | 34        | 14.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 238       | 99.17%  |
| 64-bit         | 1         | 0.42%   |
| Unknown        | 1         | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 27.05%  |
| 0x406e3    | 14        | 5.74%   |
| 0x806ea    | 11        | 4.51%   |
| 0x306a9    | 11        | 4.51%   |
| 0x40651    | 10        | 4.1%    |
| 0x306c3    | 10        | 4.1%    |
| 0x906ea    | 9         | 3.69%   |
| 0x806ec    | 9         | 3.69%   |
| 0x0a50000c | 9         | 3.69%   |
| 0x506e3    | 7         | 2.87%   |
| 0x08108109 | 6         | 2.46%   |
| 0xa0652    | 5         | 2.05%   |
| 0x806e9    | 5         | 2.05%   |
| 0x806c1    | 5         | 2.05%   |
| 0x706e5    | 5         | 2.05%   |
| 0x306d4    | 5         | 2.05%   |
| 0x206a7    | 5         | 2.05%   |
| 0x08600104 | 5         | 2.05%   |
| 0x08108102 | 5         | 2.05%   |
| 0x08600106 | 4         | 1.64%   |
| 0x906e9    | 3         | 1.23%   |
| 0x806d1    | 3         | 1.23%   |
| 0x20655    | 3         | 1.23%   |
| 0x1067a    | 3         | 1.23%   |
| 0x706a1    | 2         | 0.82%   |
| 0x08608103 | 2         | 0.82%   |
| 0x08600103 | 2         | 0.82%   |
| 0x08600102 | 2         | 0.82%   |
| 0x07000110 | 2         | 0.82%   |
| 0x0700010f | 2         | 0.82%   |
| 0x06006705 | 2         | 0.82%   |
| 0x806eb    | 1         | 0.41%   |
| 0x706a8    | 1         | 0.41%   |
| 0x506c9    | 1         | 0.41%   |
| 0x406c4    | 1         | 0.41%   |
| 0x20652    | 1         | 0.41%   |
| 0x08608102 | 1         | 0.41%   |
| 0x08001137 | 1         | 0.41%   |
| 0x07030105 | 1         | 0.41%   |
| 0x07030104 | 1         | 0.41%   |
| 0x06006704 | 1         | 0.41%   |
| 0x06001119 | 1         | 0.41%   |
| 0x010000c8 | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 50        | 20.83%  |
| Skylake       | 27        | 11.25%  |
| Haswell       | 24        | 10%     |
| Zen 2         | 18        | 7.5%    |
| IvyBridge     | 15        | 6.25%   |
| Zen+          | 12        | 5%      |
| Zen 3         | 11        | 4.58%   |
| IceLake       | 10        | 4.17%   |
| Broadwell     | 9         | 3.75%   |
| TigerLake     | 8         | 3.33%   |
| CometLake     | 8         | 3.33%   |
| SandyBridge   | 7         | 2.92%   |
| Jaguar        | 6         | 2.5%    |
| Unknown       | 6         | 2.5%    |
| Westmere      | 5         | 2.08%   |
| Penryn        | 5         | 2.08%   |
| Excavator     | 5         | 2.08%   |
| Goldmont plus | 3         | 1.25%   |
| Silvermont    | 2         | 0.83%   |
| Puma          | 2         | 0.83%   |
| Piledriver    | 2         | 0.83%   |
| Zen           | 1         | 0.42%   |
| K10           | 1         | 0.42%   |
| Goldmont      | 1         | 0.42%   |
| Core          | 1         | 0.42%   |
| Bobcat        | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 163       | 50.94%  |
| Nvidia | 84        | 26.25%  |
| AMD    | 73        | 22.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                   | 18        | 5.5%    |
| AMD Renoir                                                                            | 18        | 5.5%    |
| Intel UHD Graphics 620                                                                | 15        | 4.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 14        | 4.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 13        | 3.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 13        | 3.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 12        | 3.67%   |
| AMD Cezanne                                                                           | 11        | 3.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 10        | 3.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 8         | 2.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 2.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 2.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 6         | 1.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 1.53%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 5         | 1.53%   |
| Intel HD Graphics 5500                                                                | 5         | 1.53%   |
| Intel HD Graphics 530                                                                 | 5         | 1.53%   |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 1.53%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 4         | 1.22%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 4         | 1.22%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 4         | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 4         | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 1.22%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.22%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 1.22%   |
| Intel HD Graphics 620                                                                 | 4         | 1.22%   |
| Intel HD Graphics 6000                                                                | 4         | 1.22%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 1.22%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 4         | 1.22%   |
| AMD Lucienne                                                                          | 4         | 1.22%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 3         | 0.92%   |
| Nvidia GP108M [GeForce MX250]                                                         | 3         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 0.92%   |
| Nvidia GM108M [GeForce 940M]                                                          | 3         | 0.92%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 3         | 0.92%   |
| Intel HD Graphics 630                                                                 | 3         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 0.92%   |
| AMD Kabini [Radeon HD 8330]                                                           | 3         | 0.92%   |
| Nvidia GP107M [GeForce MX350]                                                         | 2         | 0.61%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 2         | 0.61%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 2         | 0.61%   |
| Nvidia GK104GLM [Quadro K3100M]                                                       | 2         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 0.61%   |
| Nvidia GF108M [GeForce GT 540M]                                                       | 2         | 0.61%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                              | 2         | 0.61%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 0.61%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 2         | 0.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 0.61%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                               | 2         | 0.61%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                    | 1         | 0.31%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 0.31%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.31%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.31%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                 | 1         | 0.31%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                 | 1         | 0.31%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 1         | 0.31%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 0.31%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                 | 1         | 0.31%   |
| Nvidia GM108M [GeForce MX110]                                                         | 1         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 93        | 38.75%  |
| Intel + Nvidia | 61        | 25.42%  |
| 1 x AMD        | 48        | 20%     |
| 1 x Nvidia     | 12        | 5%      |
| AMD + Nvidia   | 10        | 4.17%   |
| Intel + AMD    | 9         | 3.75%   |
| 2 x AMD        | 6         | 2.5%    |
| Other          | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 181       | 75.42%  |
| Proprietary | 58        | 24.17%  |
| Unknown     | 1         | 0.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 162       | 66.39%  |
| 0.01-0.5   | 33        | 13.52%  |
| 1.01-2.0   | 20        | 8.2%    |
| 3.01-4.0   | 9         | 3.69%   |
| 0.51-1.0   | 8         | 3.28%   |
| 7.01-8.0   | 5         | 2.05%   |
| 2.01-3.0   | 4         | 1.64%   |
| 5.01-6.0   | 3         | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 60        | 20.69%  |
| LG Display              | 44        | 15.17%  |
| Chimei Innolux          | 40        | 13.79%  |
| BOE                     | 31        | 10.69%  |
| Samsung Electronics     | 21        | 7.24%   |
| PANDA                   | 9         | 3.1%    |
| Apple                   | 9         | 3.1%    |
| Sharp                   | 8         | 2.76%   |
| Lenovo                  | 7         | 2.41%   |
| Goldstar                | 7         | 2.41%   |
| Dell                    | 7         | 2.41%   |
| InfoVision              | 5         | 1.72%   |
| Acer                    | 5         | 1.72%   |
| Philips                 | 4         | 1.38%   |
| ViewSonic               | 3         | 1.03%   |
| Sony                    | 3         | 1.03%   |
| Hewlett-Packard         | 3         | 1.03%   |
| BenQ                    | 3         | 1.03%   |
| JDI                     | 2         | 0.69%   |
| CSO                     | 2         | 0.69%   |
| Chi Mei Optoelectronics | 2         | 0.69%   |
| AOC                     | 2         | 0.69%   |
| Ancor Communications    | 2         | 0.69%   |
| Vizio                   | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |
| Sun                     | 1         | 0.34%   |
| Sceptre Tech            | 1         | 0.34%   |
| Pixio                   | 1         | 0.34%   |
| LG Philips              | 1         | 0.34%   |
| InnoLux Display         | 1         | 0.34%   |
| Iiyama                  | 1         | 0.34%   |
| HKC                     | 1         | 0.34%   |
| Gigabyte Technology     | 1         | 0.34%   |
| DENON                   | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 5         | 1.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch   | 3         | 1.02%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 3         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 3         | 1.02%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 1.02%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch       | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch         | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch          | 3         | 1.02%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 3         | 1.02%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0E35 1920x1080 1210x680mm 54.6-inch | 2         | 0.68%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 2         | 0.68%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.68%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 2         | 0.68%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch           | 2         | 0.68%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 2         | 0.68%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 2         | 0.68%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 2         | 0.68%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 2         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 0.68%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 2         | 0.68%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                  | 2         | 0.68%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch           | 2         | 0.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch       | 2         | 0.68%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 2         | 0.68%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                  | 2         | 0.68%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                  | 2         | 0.68%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                   | 2         | 0.68%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch         | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch          | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch          | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 0.68%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                    | 1         | 0.34%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1         | 0.34%   |
| ViewSonic VX2456 SERIES VSC4F2F 1920x1080 521x293mm 23.5-inch          | 1         | 0.34%   |
| ViewSonic LCD Monitor VSC3E32 1920x1080 600x340mm 27.2-inch            | 1         | 0.34%   |
| Unknown LCD Monitor Sharp LQ156M1JW03 3840x1080                        | 1         | 0.34%   |
| Unknown LCD Monitor Dell SE2717H/HX                                    | 1         | 0.34%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                 | 1         | 0.34%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.34%   |
| Sony TV *00 SNYF503 1920x1080 1439x809mm 65.0-inch                     | 1         | 0.34%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                          | 1         | 0.34%   |
| Sharp LQ156M1JW16 SHP14F4 1920x1080 344x194mm 15.5-inch                | 1         | 0.34%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.34%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch                | 1         | 0.34%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 1         | 0.34%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                | 1         | 0.34%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.34%   |
| Sceptre Tech Sceptre C27 SPT0AD7 1920x1080 600x340mm 27.2-inch         | 1         | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1         | 0.34%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 1         | 0.34%   |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch       | 1         | 0.34%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch      | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 145       | 52.92%  |
| 1366x768 (WXGA)    | 67        | 24.45%  |
| 2560x1440 (QHD)    | 11        | 4.01%   |
| 3840x2160 (4K)     | 9         | 3.28%   |
| 1440x900 (WXGA+)   | 9         | 3.28%   |
| 2560x1600          | 5         | 1.82%   |
| 1920x1200 (WUXGA)  | 5         | 1.82%   |
| 1280x800 (WXGA)    | 4         | 1.46%   |
| 3000x2000          | 2         | 0.73%   |
| 2560x1080          | 2         | 0.73%   |
| 2160x1440          | 2         | 0.73%   |
| 1680x1050 (WSXGA+) | 2         | 0.73%   |
| 1600x900 (HD+)     | 2         | 0.73%   |
| 3840x2400          | 1         | 0.36%   |
| 3840x1080          | 1         | 0.36%   |
| 3456x2160          | 1         | 0.36%   |
| 3440x1440          | 1         | 0.36%   |
| 3200x1800 (QHD+)   | 1         | 0.36%   |
| 2880x1800          | 1         | 0.36%   |
| 2256x1504          | 1         | 0.36%   |
| 1360x768           | 1         | 0.36%   |
| Unknown            | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 110       | 37.67%  |
| 13      | 58        | 19.86%  |
| 14      | 32        | 10.96%  |
| 17      | 17        | 5.82%   |
| 27      | 13        | 4.45%   |
| 24      | 9         | 3.08%   |
| 21      | 7         | 2.4%    |
| 23      | 6         | 2.05%   |
| 18      | 5         | 1.71%   |
| 12      | 5         | 1.71%   |
| 11      | 5         | 1.71%   |
| 16      | 4         | 1.37%   |
| 54      | 2         | 0.68%   |
| 34      | 2         | 0.68%   |
| 31      | 2         | 0.68%   |
| 22      | 2         | 0.68%   |
| 72      | 1         | 0.34%   |
| 65      | 1         | 0.34%   |
| 57      | 1         | 0.34%   |
| 49      | 1         | 0.34%   |
| 42      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 29      | 1         | 0.34%   |
| 28      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |
| 25      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |
| 8       | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 170       | 58.42%  |
| 201-300     | 41        | 14.09%  |
| 501-600     | 30        | 10.31%  |
| 351-400     | 21        | 7.22%   |
| 401-500     | 14        | 4.81%   |
| 601-700     | 4         | 1.37%   |
| 1001-1500   | 4         | 1.37%   |
| 701-800     | 2         | 0.69%   |
| 801-900     | 1         | 0.34%   |
| 1501-2000   | 1         | 0.34%   |
| 101-200     | 1         | 0.34%   |
| 901-1000    | 1         | 0.34%   |
| Unknown     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 209       | 84.62%  |
| 16/10   | 27        | 10.93%  |
| 3/2     | 5         | 2.02%   |
| 21/9    | 2         | 0.81%   |
| 4/3     | 1         | 0.4%    |
| 2.65    | 1         | 0.4%    |
| 0.62    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 111       | 38.28%  |
| 81-90          | 67        | 23.1%   |
| 71-80          | 24        | 8.28%   |
| 201-250        | 20        | 6.9%    |
| 121-130        | 15        | 5.17%   |
| 301-350        | 14        | 4.83%   |
| More than 1000 | 5         | 1.72%   |
| 51-60          | 5         | 1.72%   |
| 351-500        | 5         | 1.72%   |
| 251-300        | 5         | 1.72%   |
| 141-150        | 5         | 1.72%   |
| 61-70          | 4         | 1.38%   |
| 111-120        | 3         | 1.03%   |
| 131-140        | 2         | 0.69%   |
| 501-1000       | 2         | 0.69%   |
| 41-50          | 1         | 0.34%   |
| 1-40           | 1         | 0.34%   |
| Unknown        | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 136       | 47.55%  |
| 101-120       | 70        | 24.48%  |
| 51-100        | 37        | 12.94%  |
| 161-240       | 26        | 9.09%   |
| More than 240 | 11        | 3.85%   |
| 1-50          | 5         | 1.75%   |
| Unknown       | 1         | 0.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 192       | 78.37%  |
| 2     | 52        | 21.22%  |
| 3     | 1         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 149       | 38.4%   |
| Realtek Semiconductor             | 140       | 36.08%  |
| Qualcomm Atheros                  | 39        | 10.05%  |
| Broadcom                          | 14        | 3.61%   |
| MEDIATEK                          | 8         | 2.06%   |
| TP-Link                           | 6         | 1.55%   |
| D-Link                            | 6         | 1.55%   |
| Broadcom Limited                  | 6         | 1.55%   |
| ASIX Electronics                  | 5         | 1.29%   |
| Hewlett-Packard                   | 3         | 0.77%   |
| Sierra Wireless                   | 2         | 0.52%   |
| Lenovo                            | 2         | 0.52%   |
| DisplayLink                       | 2         | 0.52%   |
| NetGear                           | 1         | 0.26%   |
| Linksys                           | 1         | 0.26%   |
| Huawei Technologies               | 1         | 0.26%   |
| Ericsson Business Mobile Networks | 1         | 0.26%   |
| Cypress Semiconductor             | 1         | 0.26%   |
| Apple                             | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 20.6%   |
| Intel Wi-Fi 6 AX200                                               | 28        | 6.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 3.43%   |
| Intel Wireless 7260                                               | 15        | 3.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 2.36%   |
| Intel Wireless 8265 / 8275                                        | 11        | 2.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.93%   |
| Intel Wireless 8260                                               | 8         | 1.72%   |
| Intel Wireless 7265                                               | 8         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 8         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 1.29%   |
| Intel Wireless 3165                                               | 6         | 1.29%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.29%   |
| D-Link 802.11ac NIC                                               | 6         | 1.29%   |
| TP-Link 802.11ac NIC                                              | 5         | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.07%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.07%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.07%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 5         | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.86%   |
| Realtek 802.11ac NIC                                              | 4         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.86%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.64%   |
| Intel Wireless 3160                                               | 3         | 0.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.64%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.64%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.64%   |
| HP un2430 Mobile Broadband Module                                 | 3         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.43%   |
| Realtek Realtek Ethernet controller                               | 2         | 0.43%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.43%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.43%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.43%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.43%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.21%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 148       | 57.36%  |
| Realtek Semiconductor             | 35        | 13.57%  |
| Qualcomm Atheros                  | 34        | 13.18%  |
| Broadcom                          | 11        | 4.26%   |
| MEDIATEK                          | 8         | 3.1%    |
| TP-Link                           | 6         | 2.33%   |
| D-Link                            | 6         | 2.33%   |
| Broadcom Limited                  | 6         | 2.33%   |
| Sierra Wireless                   | 2         | 0.78%   |
| Linksys                           | 1         | 0.39%   |
| Ericsson Business Mobile Networks | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 28        | 10.73%  |
| Intel Wireless 7260                                                    | 15        | 5.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12        | 4.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 4.21%   |
| Intel Wireless 8265 / 8275                                             | 11        | 4.21%   |
| Intel Wireless 8260                                                    | 8         | 3.07%   |
| Intel Wireless 7265                                                    | 8         | 3.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 8         | 3.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 8         | 3.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 3.07%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 2.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 2.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 2.3%    |
| Intel Wireless 3165                                                    | 6         | 2.3%    |
| Intel Wi-Fi 6 AX201                                                    | 6         | 2.3%    |
| D-Link 802.11ac NIC                                                    | 6         | 2.3%    |
| TP-Link 802.11ac NIC                                                   | 5         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.92%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 1.92%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter             | 5         | 1.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 1.53%   |
| Realtek 802.11ac NIC                                                   | 4         | 1.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 4         | 1.53%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                          | 4         | 1.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.15%   |
| Intel Wireless 3160                                                    | 3         | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 3         | 1.15%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.15%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.77%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 2         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 0.77%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.77%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1         | 0.38%   |
| Sierra Wireless EM7455                                                 | 1         | 0.38%   |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 0.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.38%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                 | 1         | 0.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 1         | 0.38%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.38%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.38%   |
| MediaTek WiFi                                                          | 1         | 0.38%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                          | 1         | 0.38%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                    | 1         | 0.38%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1         | 0.38%   |
| Intel Wireless-AC 9260                                                 | 1         | 0.38%   |
| Intel Ultimate N WiFi Link 5300                                        | 1         | 0.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 0.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 1         | 0.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1         | 0.38%   |
| Intel Centrino Wireless-N 2230                                         | 1         | 0.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 1         | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 124       | 62.94%  |
| Intel                 | 44        | 22.34%  |
| Qualcomm Atheros      | 12        | 6.09%   |
| Broadcom              | 5         | 2.54%   |
| ASIX Electronics      | 5         | 2.54%   |
| Lenovo                | 2         | 1.02%   |
| DisplayLink           | 2         | 1.02%   |
| NetGear               | 1         | 0.51%   |
| Cypress Semiconductor | 1         | 0.51%   |
| Apple                 | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 47.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 7.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 2.99%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.99%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.49%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.99%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.99%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1%      |
| Realtek Realtek Ethernet controller                               | 2         | 1%      |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1%      |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 1%      |
| Intel Ethernet Connection I219-V                                  | 2         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.5%    |
| NetGear LB1120-100NAS                                             | 1         | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.5%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.5%    |
| DisplayLink Plugable UD-3900H                                     | 1         | 0.5%    |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.5%    |
| Cypress K38231_03                                                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.5%    |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 0.5%    |
| Apple iBridge                                                     | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 238       | 55.74%  |
| Ethernet | 185       | 43.33%  |
| Modem    | 4         | 0.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 216       | 74.48%  |
| Ethernet | 73        | 25.17%  |
| Modem    | 1         | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 167       | 69.58%  |
| 1     | 65        | 27.08%  |
| 3     | 6         | 2.5%    |
| 0     | 2         | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 197       | 81.4%   |
| Yes  | 45        | 18.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 134       | 58.77%  |
| Realtek Semiconductor           | 24        | 10.53%  |
| Qualcomm Atheros Communications | 18        | 7.89%   |
| Broadcom                        | 10        | 4.39%   |
| IMC Networks                    | 9         | 3.95%   |
| Lite-On Technology              | 8         | 3.51%   |
| Apple                           | 8         | 3.51%   |
| Foxconn / Hon Hai               | 5         | 2.19%   |
| Realtek                         | 3         | 1.32%   |
| Dell                            | 3         | 1.32%   |
| Toshiba                         | 2         | 0.88%   |
| Cambridge Silicon Radio         | 2         | 0.88%   |
| MediaTek                        | 1         | 0.44%   |
| Foxconn International           | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 58        | 25.44%  |
| Intel AX200 Bluetooth                               | 28        | 12.28%  |
| Intel AX201 Bluetooth                               | 22        | 9.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 7.02%   |
| Realtek Bluetooth Radio                             | 14        | 6.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 4.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 3.07%   |
| Apple Bluetooth USB Host Controller                 | 6         | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.75%   |
| IMC Networks Wireless_Device                        | 4         | 1.75%   |
| Realtek Bluetooth Radio                             | 3         | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 1.32%   |
| Intel AX210 Bluetooth                               | 3         | 1.32%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.88%   |
| Lite-On Bluetooth Device                            | 2         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.88%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.88%   |
| Toshiba BCM43142A0                                  | 1         | 0.44%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.44%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.44%   |
| MediaTek Wireless_Device                            | 1         | 0.44%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.44%   |
| Intel Bluetooth Device                              | 1         | 0.44%   |
| IMC Networks Bluetooth Device                       | 1         | 0.44%   |
| IMC Networks Bluetooth                              | 1         | 0.44%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.44%   |
| Foxconn / Hon Hai BT                                | 1         | 0.44%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 0.44%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.44%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.44%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.44%   |
| Broadcom HP Portable Valentine                      | 1         | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.44%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.44%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.44%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 0.44%   |
| Broadcom BCM2045A0                                  | 1         | 0.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.44%   |
| Apple Bluetooth Host Controller                     | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 174       | 52.73%  |
| AMD                                             | 64        | 19.39%  |
| Nvidia                                          | 50        | 15.15%  |
| C-Media Electronics                             | 6         | 1.82%   |
| Texas Instruments                               | 5         | 1.52%   |
| KORG                                            | 4         | 1.21%   |
| AKAI                                            | 4         | 1.21%   |
| Realtek Semiconductor                           | 3         | 0.91%   |
| Logitech                                        | 2         | 0.61%   |
| Lenovo                                          | 2         | 0.61%   |
| Corsair                                         | 2         | 0.61%   |
| XMOS                                            | 1         | 0.3%    |
| Tdlasunnic                                      | 1         | 0.3%    |
| Sony                                            | 1         | 0.3%    |
| Samson Technologies                             | 1         | 0.3%    |
| NAD Electronics                                 | 1         | 0.3%    |
| Micro Star International                        | 1         | 0.3%    |
| M-Audio                                         | 1         | 0.3%    |
| Licensed by Sony Computer Entertainment America | 1         | 0.3%    |
| JMTek                                           | 1         | 0.3%    |
| Generalplus Technology                          | 1         | 0.3%    |
| Focusrite-Novation                              | 1         | 0.3%    |
| Creative Technology                             | 1         | 0.3%    |
| Apple                                           | 1         | 0.3%    |
| AKAI Professional M.I.                          | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 44        | 10.4%   |
| Intel Sunrise Point-LP HD Audio                                            | 39        | 9.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 31        | 7.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 3.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 3.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 3.07%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 3.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.6%    |
| AMD FCH Azalia Controller                                                  | 10        | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 2.13%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.13%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 1.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.89%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.18%   |
| Nvidia GM204 High Definition Audio Controller                              | 5         | 1.18%   |
| Nvidia Audio device                                                        | 5         | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.95%   |
| KORG nanoKONTROL2 MIDI Controller                                          | 4         | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.95%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 0.95%   |
| AMD High Definition Audio Controller                                       | 4         | 0.95%   |
| AKAI MPKmini2                                                              | 4         | 0.95%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.71%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.71%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3         | 0.71%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.47%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.47%   |
| C-Media Electronics USB Advanced Audio Device                              | 2         | 0.47%   |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 0.47%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.47%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.47%   |
| Texas Instruments PCM2912A Audio Codec                                     | 1         | 0.24%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1         | 0.24%   |
| Tdlasunnic Sharkoon Mobile DAC                                             | 1         | 0.24%   |
| Sony Wireless Controller                                                   | 1         | 0.24%   |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.24%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                 | 1         | 0.24%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.24%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.24%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.24%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 71        | 33.02%  |
| SK Hynix            | 55        | 25.58%  |
| Micron Technology   | 31        | 14.42%  |
| Kingston            | 10        | 4.65%   |
| Unknown             | 9         | 4.19%   |
| A-DATA Technology   | 7         | 3.26%   |
| Crucial             | 6         | 2.79%   |
| Corsair             | 5         | 2.33%   |
| Ramaxel Technology  | 4         | 1.86%   |
| Unknown (ABCD)      | 3         | 1.4%    |
| Elpida              | 3         | 1.4%    |
| Shenzhen Mic        | 2         | 0.93%   |
| G.Skill             | 2         | 0.93%   |
| V-GeN               | 1         | 0.47%   |
| Team                | 1         | 0.47%   |
| SMART Brazil        | 1         | 0.47%   |
| Sesame              | 1         | 0.47%   |
| Patriot             | 1         | 0.47%   |
| Nanya Technology    | 1         | 0.47%   |
| Kllisre             | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 7         | 2.99%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 6         | 2.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 6         | 2.56%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 5         | 2.14%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 5         | 2.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 2.14%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 4         | 1.71%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 4         | 1.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 4         | 1.71%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 4         | 1.71%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s             | 4         | 1.71%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 1.28%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 1.28%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 3         | 1.28%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 3         | 1.28%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s               | 3         | 1.28%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 2         | 0.85%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.85%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.85%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.85%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK Hynix RAM HMP351S6AFR8C-S6 4GB SODIMM DDR2 800MT/s               | 2         | 0.85%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.85%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.85%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s         | 2         | 0.85%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.85%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.85%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s               | 2         | 0.85%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.85%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.85%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s            | 2         | 0.85%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s              | 2         | 0.85%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s               | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 0.85%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.85%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 0.85%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                         | 2         | 0.85%   |
| V-GeN RAM D3R4GS16B8R 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.43%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 0.43%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s     | 1         | 0.43%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2667MT/s                        | 1         | 0.43%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.43%   |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR4 3733MT/s                | 1         | 0.43%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1600MT/s                          | 1         | 0.43%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1333MT/s                        | 1         | 0.43%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.43%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.43%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.43%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 1600MT/s           | 1         | 0.43%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.43%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.43%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s              | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 100       | 55.56%  |
| DDR3   | 65        | 36.11%  |
| LPDDR4 | 7         | 3.89%   |
| LPDDR3 | 6         | 3.33%   |
| DDR2   | 2         | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 167       | 89.78%  |
| Row Of Chips | 14        | 7.53%   |
| Chip         | 4         | 2.15%   |
| DIMM         | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 87        | 44.16%  |
| 4096  | 74        | 37.56%  |
| 16384 | 23        | 11.68%  |
| 2048  | 11        | 5.58%   |
| 32768 | 2         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 58        | 30.37%  |
| 3200  | 46        | 24.08%  |
| 2667  | 39        | 20.42%  |
| 2400  | 16        | 8.38%   |
| 3266  | 7         | 3.66%   |
| 2133  | 7         | 3.66%   |
| 1334  | 6         | 3.14%   |
| 1867  | 3         | 1.57%   |
| 1333  | 2         | 1.05%   |
| 800   | 2         | 1.05%   |
| 4267  | 1         | 0.52%   |
| 4266  | 1         | 0.52%   |
| 3733  | 1         | 0.52%   |
| 3000  | 1         | 0.52%   |
| 1067  | 1         | 0.52%   |

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
| Chicony Electronics                    | 51        | 24.17%  |
| IMC Networks                           | 28        | 13.27%  |
| Acer                                   | 20        | 9.48%   |
| Microdia                               | 17        | 8.06%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 6.64%   |
| Realtek Semiconductor                  | 13        | 6.16%   |
| Sunplus Innovation Technology          | 10        | 4.74%   |
| Lite-On Technology                     | 10        | 4.74%   |
| Syntek                                 | 8         | 3.79%   |
| Quanta                                 | 8         | 3.79%   |
| Apple                                  | 7         | 3.32%   |
| Logitech                               | 6         | 2.84%   |
| Suyin                                  | 3         | 1.42%   |
| Sonix Technology                       | 2         | 0.95%   |
| Primax Electronics                     | 2         | 0.95%   |
| Lenovo                                 | 2         | 0.95%   |
| Intel                                  | 2         | 0.95%   |
| Alcor Micro                            | 2         | 0.95%   |
| Silicon Motion                         | 1         | 0.47%   |
| Ricoh                                  | 1         | 0.47%   |
| MacroSilicon                           | 1         | 0.47%   |
| Google                                 | 1         | 0.47%   |
| DJKANA1BIFZTDM                         | 1         | 0.47%   |
| 8SSC21B70095V1SR1BS026P                | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 16        | 7.58%   |
| IMC Networks Integrated Camera                                 | 14        | 6.64%   |
| Chicony HD WebCam                                              | 11        | 5.21%   |
| Acer Integrated Camera                                         | 8         | 3.79%   |
| Microdia Integrated_Webcam_HD                                  | 7         | 3.32%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 7         | 3.32%   |
| Realtek Integrated_Webcam_HD                                   | 5         | 2.37%   |
| Syntek Integrated Camera                                       | 4         | 1.9%    |
| Sunplus Integrated_Webcam_HD                                   | 4         | 1.9%    |
| Microdia Integrated Webcam                                     | 4         | 1.9%    |
| Lite-On Integrated Camera                                      | 4         | 1.9%    |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 1.9%    |
| Syntek Lenovo EasyCamera                                       | 3         | 1.42%   |
| Sunplus HD WebCam                                              | 3         | 1.42%   |
| Lite-On HP Webcam                                              | 3         | 1.42%   |
| Chicony EasyCamera                                             | 3         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 3         | 1.42%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 3         | 1.42%   |
| Acer HD Webcam                                                 | 3         | 1.42%   |
| Acer EasyCamera                                                | 3         | 1.42%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 0.95%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 0.95%   |
| Quanta HP HD Camera                                            | 2         | 0.95%   |
| Microdia Dell Integrated HD Webcam                             | 2         | 0.95%   |
| Logitech HD Pro Webcam C920                                    | 2         | 0.95%   |
| Lite-On HP Wide Vision HD Camera                               | 2         | 0.95%   |
| Intel RealSense 3D Camera (Front F200)                         | 2         | 0.95%   |
| IMC Networks HD Camera                                         | 2         | 0.95%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 2         | 0.95%   |
| Chicony HP Webcam                                              | 2         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 0.95%   |
| Acer SunplusIT Integrated Camera                               | 2         | 0.95%   |
| Syntek EasyCamera                                              | 1         | 0.47%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.47%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.47%   |
| Suyin HP TrueVision HD                                         | 1         | 0.47%   |
| Sunplus Lenovo EasyCamera                                      | 1         | 0.47%   |
| Sunplus HP TrueVision HD Camera                                | 1         | 0.47%   |
| Sunplus Asus Webcam                                            | 1         | 0.47%   |
| Silicon Motion Web Camera                                      | 1         | 0.47%   |
| Ricoh HD Webcam                                                | 1         | 0.47%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 0.47%   |
| Realtek USB HD Webcam                                          | 1         | 0.47%   |
| Realtek MTD Camera                                             | 1         | 0.47%   |
| Realtek Laptop_Integrated_Webcam_HD                            | 1         | 0.47%   |
| Realtek Integrated Webcam_HD                                   | 1         | 0.47%   |
| Realtek Integrated Webcam                                      | 1         | 0.47%   |
| Realtek HD Webcam - Realtek                                    | 1         | 0.47%   |
| Realtek EasyCamera                                             | 1         | 0.47%   |
| Quanta VGA WebCam                                              | 1         | 0.47%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 0.47%   |
| Quanta USB2.0 HD UVC WebCam                                    | 1         | 0.47%   |
| Quanta HD Webcam                                               | 1         | 0.47%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 0.47%   |
| Primax Dell Laptop Integrated Webcam 2Mpix                     | 1         | 0.47%   |
| Microdia Webcam Vitade AF                                      | 1         | 0.47%   |
| Microdia Laptop_Integrated_Webcam_FHD                          | 1         | 0.47%   |
| Microdia Integrated Webcam HD                                  | 1         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 16        | 34.78%  |
| Validity Sensors           | 13        | 28.26%  |
| Shenzhen Goodix Technology | 10        | 21.74%  |
| LighTuning Technology      | 3         | 6.52%   |
| Elan Microelectronics      | 3         | 6.52%   |
| Upek                       | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 6         | 13.04%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 10.87%  |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 10.87%  |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 10.87%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 8.7%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 6.52%   |
| Synaptics  WBDI                                                            | 2         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 4.35%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.17%   |
| Validity Sensors VFS491                                                    | 1         | 2.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.17%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.17%   |
| Elan ELAN:ARM-M4                                                           | 1         | 2.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 57.14%  |
| Alcor Micro | 7         | 33.33%  |
| O2 Micro    | 1         | 4.76%   |
| Lenovo      | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 31.82%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 13.64%  |
| Broadcom 58200                                                               | 3         | 13.64%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.55%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.55%   |
| Broadcom 5880                                                                | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 128       | 51.41%  |
| 1     | 98        | 39.36%  |
| 2     | 23        | 9.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 33.58%  |
| Net/ethernet             | 24        | 17.52%  |
| Chipcard                 | 20        | 14.6%   |
| Multimedia controller    | 17        | 12.41%  |
| Graphics card            | 13        | 9.49%   |
| Net/wireless             | 8         | 5.84%   |
| Bluetooth                | 4         | 2.92%   |
| Camera                   | 2         | 1.46%   |
| Storage                  | 1         | 0.73%   |
| Modem                    | 1         | 0.73%   |
| Communication controller | 1         | 0.73%   |


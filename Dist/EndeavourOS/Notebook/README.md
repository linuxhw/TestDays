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


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.12-arch1-1        | 8         | 3.74%   |
| 5.13.13-arch1-1        | 7         | 3.27%   |
| 5.15.10-arch1-1        | 6         | 2.8%    |
| 5.9.14-arch1-1         | 5         | 2.34%   |
| 5.15.4-arch1-1         | 5         | 2.34%   |
| 5.9.1-arch1-1          | 4         | 1.87%   |
| 5.7.8-arch1-1          | 4         | 1.87%   |
| 5.15.2-arch1-1         | 4         | 1.87%   |
| 5.14.9-arch2-1         | 4         | 1.87%   |
| 5.12.14-arch1-1        | 4         | 1.87%   |
| 5.11.16-arch1-1        | 4         | 1.87%   |
| 5.11.11-arch1-1        | 4         | 1.87%   |
| 5.9.8-arch1-1          | 3         | 1.4%    |
| 5.9.10-arch1-1         | 3         | 1.4%    |
| 5.15.6-zen2-1-zen      | 3         | 1.4%    |
| 5.14.6-arch1-1         | 3         | 1.4%    |
| 5.14.14-arch1-1        | 3         | 1.4%    |
| 5.12.13-arch1-2        | 3         | 1.4%    |
| 5.11.16-zen1-1-zen     | 3         | 1.4%    |
| 5.10.15-arch1-1        | 3         | 1.4%    |
| 5.9.2-arch1-1          | 2         | 0.93%   |
| 5.7.10-arch1-1         | 2         | 0.93%   |
| 5.4.2-arch1-1          | 2         | 0.93%   |
| 5.15.7-arch1-1         | 2         | 0.93%   |
| 5.15.6-arch2-1         | 2         | 0.93%   |
| 5.15.4-zen1-1-zen      | 2         | 0.93%   |
| 5.15.2-zen1-1-zen      | 2         | 0.93%   |
| 5.14.9-lqx4-1-lqx      | 2         | 0.93%   |
| 5.14.8-zen1-1-zen      | 2         | 0.93%   |
| 5.14.3-arch1-1         | 2         | 0.93%   |
| 5.14.16-arch1-1        | 2         | 0.93%   |
| 5.13.9-arch1-1         | 2         | 0.93%   |
| 5.13.4-arch1-1         | 2         | 0.93%   |
| 5.13.13-lqx1-1-lqx     | 2         | 0.93%   |
| 5.13.12-arch1-1        | 2         | 0.93%   |
| 5.13.10-arch1-1        | 2         | 0.93%   |
| 5.12.8-arch1-1         | 2         | 0.93%   |
| 5.12.5-zen1-1-zen      | 2         | 0.93%   |
| 5.12.5-arch1-1         | 2         | 0.93%   |
| 5.12.3-arch1-1         | 2         | 0.93%   |
| 5.11.8-arch1-1         | 2         | 0.93%   |
| 5.11.4-arch1-1         | 2         | 0.93%   |
| 5.11.14-zen1-1-zen     | 2         | 0.93%   |
| 5.10.68-1-lts          | 2         | 0.93%   |
| 5.10.4-arch2-1         | 2         | 0.93%   |
| 5.10.16-arch1-1        | 2         | 0.93%   |
| 5.10.11-arch1-1        | 2         | 0.93%   |
| 5.9.9-arch1-1          | 1         | 0.47%   |
| 5.9.13-arch1-1         | 1         | 0.47%   |
| 5.9.11-arch2-1         | 1         | 0.47%   |
| 5.9.1-zen2-1-zen       | 1         | 0.47%   |
| 5.9.0-arch1-1          | 1         | 0.47%   |
| 5.8.8-arch1-1          | 1         | 0.47%   |
| 5.8.7-zen1-1-zen-anbox | 1         | 0.47%   |
| 5.8.5-zen1-1-zen       | 1         | 0.47%   |
| 5.8.3-arch1-1          | 1         | 0.47%   |
| 5.8.14-arch1-1         | 1         | 0.47%   |
| 5.8.13-arch1-1         | 1         | 0.47%   |
| 5.8.12-zen1-1-zen      | 1         | 0.47%   |
| 5.8.12-arch1-1         | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.12 | 10        | 4.67%   |
| 5.13.13 | 10        | 4.67%   |
| 5.15.4  | 8         | 3.74%   |
| 5.15.2  | 7         | 3.27%   |
| 5.12.13 | 7         | 3.27%   |
| 5.11.16 | 7         | 3.27%   |
| 5.15.10 | 6         | 2.8%    |
| 5.14.9  | 6         | 2.8%    |
| 5.9.14  | 5         | 2.34%   |
| 5.9.1   | 5         | 2.34%   |
| 5.15.6  | 5         | 2.34%   |
| 5.11.11 | 5         | 2.34%   |
| 5.7.8   | 4         | 1.87%   |
| 5.14.6  | 4         | 1.87%   |
| 5.14.14 | 4         | 1.87%   |
| 5.13.4  | 4         | 1.87%   |
| 5.12.5  | 4         | 1.87%   |
| 5.12.14 | 4         | 1.87%   |
| 5.9.8   | 3         | 1.4%    |
| 5.9.10  | 3         | 1.4%    |
| 5.14.8  | 3         | 1.4%    |
| 5.13.9  | 3         | 1.4%    |
| 5.10.15 | 3         | 1.4%    |
| 5.9.2   | 2         | 0.93%   |
| 5.8.12  | 2         | 0.93%   |
| 5.7.10  | 2         | 0.93%   |
| 5.4.2   | 2         | 0.93%   |
| 5.15.7  | 2         | 0.93%   |
| 5.15.0  | 2         | 0.93%   |
| 5.14.3  | 2         | 0.93%   |
| 5.14.2  | 2         | 0.93%   |
| 5.14.16 | 2         | 0.93%   |
| 5.14.15 | 2         | 0.93%   |
| 5.13.12 | 2         | 0.93%   |
| 5.13.10 | 2         | 0.93%   |
| 5.12.8  | 2         | 0.93%   |
| 5.12.3  | 2         | 0.93%   |
| 5.12.1  | 2         | 0.93%   |
| 5.11.8  | 2         | 0.93%   |
| 5.11.4  | 2         | 0.93%   |
| 5.11.14 | 2         | 0.93%   |
| 5.10.68 | 2         | 0.93%   |
| 5.10.4  | 2         | 0.93%   |
| 5.10.16 | 2         | 0.93%   |
| 5.10.11 | 2         | 0.93%   |
| 5.9.9   | 1         | 0.47%   |
| 5.9.13  | 1         | 0.47%   |
| 5.9.11  | 1         | 0.47%   |
| 5.9.0   | 1         | 0.47%   |
| 5.8.8   | 1         | 0.47%   |
| 5.8.7   | 1         | 0.47%   |
| 5.8.5   | 1         | 0.47%   |
| 5.8.3   | 1         | 0.47%   |
| 5.8.14  | 1         | 0.47%   |
| 5.8.13  | 1         | 0.47%   |
| 5.8.10  | 1         | 0.47%   |
| 5.7.6   | 1         | 0.47%   |
| 5.7.12  | 1         | 0.47%   |
| 5.6.4   | 1         | 0.47%   |
| 5.6.11  | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 41        | 19.9%   |
| 5.14    | 29        | 14.08%  |
| 5.13    | 24        | 11.65%  |
| 5.12    | 24        | 11.65%  |
| 5.9     | 21        | 10.19%  |
| 5.11    | 20        | 9.71%   |
| 5.10    | 20        | 9.71%   |
| 5.8     | 9         | 4.37%   |
| 5.7     | 8         | 3.88%   |
| 5.4     | 6         | 2.91%   |
| 5.6     | 2         | 0.97%   |
| 4.19    | 2         | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 194       | 99.49%  |
| aarch64 | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 55        | 27.5%   |
| KDE5       | 47        | 23.5%   |
| XFCE       | 46        | 23%     |
| X-Cinnamon | 10        | 5%      |
| KDE        | 10        | 5%      |
| Unknown    | 7         | 3.5%    |
| Cinnamon   | 6         | 3%      |
| i3         | 5         | 2.5%    |
| Budgie     | 4         | 2%      |
| sway       | 2         | 1%      |
| MATE       | 2         | 1%      |
| LXQt       | 2         | 1%      |
| Deepin     | 2         | 1%      |
| awesome    | 2         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 148       | 74.75%  |
| Wayland | 41        | 20.71%  |
| Unknown | 6         | 3.03%   |
| Tty     | 3         | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 23.38%  |
| SDDM    | 45        | 22.39%  |
| LightDM | 44        | 21.89%  |
| GDM     | 39        | 19.4%   |
| TDM     | 26        | 12.94%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 101       | 51.79%  |
| en_GB   | 18        | 9.23%   |
| en_CA   | 8         | 4.1%    |
| it_IT   | 7         | 3.59%   |
| de_DE   | 7         | 3.59%   |
| en_IN   | 6         | 3.08%   |
| fr_FR   | 5         | 2.56%   |
| Unknown | 5         | 2.56%   |
| en_NZ   | 4         | 2.05%   |
| tr_TR   | 3         | 1.54%   |
| ru_RU   | 3         | 1.54%   |
| pt_BR   | 3         | 1.54%   |
| en_AU   | 3         | 1.54%   |
| sv_SE   | 2         | 1.03%   |
| pt_PT   | 2         | 1.03%   |
| pl_PL   | 2         | 1.03%   |
| nl_NL   | 2         | 1.03%   |
| es_ES   | 2         | 1.03%   |
| en_PH   | 2         | 1.03%   |
| en_DK   | 2         | 1.03%   |
| ru_UA   | 1         | 0.51%   |
| hr_HR   | 1         | 0.51%   |
| fi_FI   | 1         | 0.51%   |
| es_MX   | 1         | 0.51%   |
| es_AR   | 1         | 0.51%   |
| en_MY   | 1         | 0.51%   |
| cs_CZ   | 1         | 0.51%   |
| an_ES   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 140       | 70.71%  |
| BIOS | 58        | 29.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 145       | 73.98%  |
| Btrfs   | 47        | 23.98%  |
| Overlay | 2         | 1.02%   |
| Xfs     | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 135       | 67.84%  |
| Unknown | 50        | 25.13%  |
| MBR     | 14        | 7.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 178       | 91.28%  |
| Yes       | 17        | 8.72%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 148       | 74.37%  |
| Yes       | 51        | 25.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 62        | 31.79%  |
| Dell                | 30        | 15.38%  |
| Hewlett-Packard     | 27        | 13.85%  |
| ASUSTek Computer    | 23        | 11.79%  |
| Acer                | 12        | 6.15%   |
| Apple               | 9         | 4.62%   |
| MSI                 | 8         | 4.1%    |
| HUAWEI              | 3         | 1.54%   |
| Unknown             | 3         | 1.54%   |
| Toshiba             | 2         | 1.03%   |
| Timi                | 2         | 1.03%   |
| Schenker            | 2         | 1.03%   |
| Notebook            | 2         | 1.03%   |
| TUXEDO              | 1         | 0.51%   |
| TrekStor            | 1         | 0.51%   |
| Samsung Electronics | 1         | 0.51%   |
| Razer               | 1         | 0.51%   |
| Pine Microsystems   | 1         | 0.51%   |
| Gigabyte Technology | 1         | 0.51%   |
| Framework           | 1         | 0.51%   |
| Dynabook            | 1         | 0.51%   |
| AMI                 | 1         | 0.51%   |
| Alienware           | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                                   | 4         | 2.05%   |
| Lenovo ThinkPad X140e 20BL000BUS                      | 3         | 1.54%   |
| Unknown                                               | 3         | 1.54%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB                  | 2         | 1.03%   |
| Lenovo IdeaPad FLEX-14API 81SS                        | 2         | 1.03%   |
| HP Pavilion Gaming Laptop 15-cx0xxx                   | 2         | 1.03%   |
| HP ENVY Laptop 13-ba0xxx                              | 2         | 1.03%   |
| HP 255 G7 Notebook PC                                 | 2         | 1.03%   |
| Dell G7 7588                                          | 2         | 1.03%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR                 | 2         | 1.03%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV                 | 2         | 1.03%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.51%   |
| TrekStor Primebook P14                                | 1         | 0.51%   |
| Toshiba Satellite P750                                | 1         | 0.51%   |
| Toshiba Satellite L50D-B                              | 1         | 0.51%   |
| Timi TM1607                                           | 1         | 0.51%   |
| Timi A35S                                             | 1         | 0.51%   |
| Schenker XMG NEO 15(E20, RTX 20xx)                    | 1         | 0.51%   |
| Schenker XMG FUSION 15 (XFU15L19)                     | 1         | 0.51%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.51%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.51%   |
| Pine Microsystems Pine64 Pinebook Pro                 | 1         | 0.51%   |
| Notebook W65_67SZ                                     | 1         | 0.51%   |
| Notebook W65KJ1_KK1                                   | 1         | 0.51%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.51%   |
| MSI Modern 14 B5M                                     | 1         | 0.51%   |
| MSI GT80S 6QE                                         | 1         | 0.51%   |
| MSI GS63VR 6RF                                        | 1         | 0.51%   |
| MSI GP66 Leopard 10UH                                 | 1         | 0.51%   |
| MSI GL75 Leopard 10SDK                                | 1         | 0.51%   |
| MSI GE72 6QD                                          | 1         | 0.51%   |
| MSI Bravo 15 B5DD                                     | 1         | 0.51%   |
| Lenovo Z50-70 20354                                   | 1         | 0.51%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.51%   |
| Lenovo Yoga S740-14IIL 81RS                           | 1         | 0.51%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.51%   |
| Lenovo V14 G2 ITL 82NM                                | 1         | 0.51%   |
| Lenovo ThinkPad X240 20AMS2QDOC                       | 1         | 0.51%   |
| Lenovo ThinkPad X220 Tablet 4294CT0                   | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0ET00              | 1         | 0.51%   |
| Lenovo ThinkPad T61 7659W1W                           | 1         | 0.51%   |
| Lenovo ThinkPad T560 20FJS4FV00                       | 1         | 0.51%   |
| Lenovo ThinkPad T520 4239CTO                          | 1         | 0.51%   |
| Lenovo ThinkPad T510 4384FF3                          | 1         | 0.51%   |
| Lenovo ThinkPad T480 20L6S3S500                       | 1         | 0.51%   |
| Lenovo ThinkPad T480 20L5S1S000                       | 1         | 0.51%   |
| Lenovo ThinkPad T470 W10DG 20JNS0DB00                 | 1         | 0.51%   |
| Lenovo ThinkPad T470 20HES2SF00                       | 1         | 0.51%   |
| Lenovo ThinkPad T460 20FMS2J000                       | 1         | 0.51%   |
| Lenovo ThinkPad T450s 20BW0007US                      | 1         | 0.51%   |
| Lenovo ThinkPad T440s 20ARS34900                      | 1         | 0.51%   |
| Lenovo ThinkPad T440s 20ARS0LU00                      | 1         | 0.51%   |
| Lenovo ThinkPad T440p 20AWS3UX00                      | 1         | 0.51%   |
| Lenovo ThinkPad T14 Gen 2a 20XK0019US                 | 1         | 0.51%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW                  | 1         | 0.51%   |
| Lenovo ThinkPad T14 Gen 1 20UD000LUS                  | 1         | 0.51%   |
| Lenovo ThinkPad T14 Gen 1 20S1SFJH1H                  | 1         | 0.51%   |
| Lenovo ThinkPad P51 20HHCT01WW                        | 1         | 0.51%   |
| Lenovo ThinkPad L460 20FV002EBR                       | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 35        | 17.95%  |
| Lenovo IdeaPad           | 16        | 8.21%   |
| Dell Inspiron            | 10        | 5.13%   |
| ASUS ROG                 | 10        | 5.13%   |
| Dell Latitude            | 9         | 4.62%   |
| HP EliteBook             | 7         | 3.59%   |
| Acer Aspire              | 7         | 3.59%   |
| HP Laptop                | 5         | 2.56%   |
| HP ENVY                  | 5         | 2.56%   |
| Dell Precision           | 4         | 2.05%   |
| Apple MacBookAir7        | 4         | 2.05%   |
| HP Pavilion              | 3         | 1.54%   |
| HP 255                   | 3         | 1.54%   |
| Unknown                  | 3         | 1.54%   |
| Toshiba Satellite        | 2         | 1.03%   |
| Schenker XMG             | 2         | 1.03%   |
| Lenovo Yoga              | 2         | 1.03%   |
| Lenovo ThinkBook         | 2         | 1.03%   |
| Lenovo Legion            | 2         | 1.03%   |
| Dell XPS                 | 2         | 1.03%   |
| Dell G7                  | 2         | 1.03%   |
| Dell G3                  | 2         | 1.03%   |
| ASUS TUF                 | 2         | 1.03%   |
| ASUS ASUS                | 2         | 1.03%   |
| TUXEDO Pulse             | 1         | 0.51%   |
| TrekStor Primebook       | 1         | 0.51%   |
| Timi TM1607              | 1         | 0.51%   |
| Timi A35S                | 1         | 0.51%   |
| Samsung 340XAA           | 1         | 0.51%   |
| Razer Blade              | 1         | 0.51%   |
| Pine Microsystems Pine64 | 1         | 0.51%   |
| Notebook W65KJ1          | 1         | 0.51%   |
| Notebook W65             | 1         | 0.51%   |
| MSI Prestige             | 1         | 0.51%   |
| MSI Modern               | 1         | 0.51%   |
| MSI GT80S                | 1         | 0.51%   |
| MSI GS63VR               | 1         | 0.51%   |
| MSI GP66                 | 1         | 0.51%   |
| MSI GL75                 | 1         | 0.51%   |
| MSI GE72                 | 1         | 0.51%   |
| MSI Bravo                | 1         | 0.51%   |
| Lenovo Z50-70            | 1         | 0.51%   |
| Lenovo Y520-15IKBN       | 1         | 0.51%   |
| Lenovo V14               | 1         | 0.51%   |
| Lenovo G505s             | 1         | 0.51%   |
| Lenovo E31-80            | 1         | 0.51%   |
| HUAWEI KLVL-WXX9         | 1         | 0.51%   |
| HUAWEI HN-WX9X           | 1         | 0.51%   |
| HUAWEI BOHK-WAX9X        | 1         | 0.51%   |
| HP ZBook                 | 1         | 0.51%   |
| HP Stream                | 1         | 0.51%   |
| HP Notebook              | 1         | 0.51%   |
| HP 15                    | 1         | 0.51%   |
| Gigabyte AERO            | 1         | 0.51%   |
| Framework Laptop         | 1         | 0.51%   |
| Dynabook Satellite       | 1         | 0.51%   |
| Dell G5                  | 1         | 0.51%   |
| ASUS X550CL              | 1         | 0.51%   |
| ASUS VivoBook            | 1         | 0.51%   |
| ASUS UX310UA             | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 48        | 24.62%  |
| 2021    | 45        | 23.08%  |
| 2019    | 26        | 13.33%  |
| 2018    | 17        | 8.72%   |
| 2017    | 14        | 7.18%   |
| 2015    | 14        | 7.18%   |
| 2014    | 10        | 5.13%   |
| 2016    | 5         | 2.56%   |
| 2013    | 5         | 2.56%   |
| 2011    | 5         | 2.56%   |
| 2012    | 3         | 1.54%   |
| 2010    | 2         | 1.03%   |
| Unknown | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 195       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 195       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 195       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 62        | 31.63%  |
| 8.01-16.0   | 47        | 23.98%  |
| 16.01-24.0  | 45        | 22.96%  |
| 3.01-4.0    | 22        | 11.22%  |
| 32.01-64.0  | 17        | 8.67%   |
| 24.01-32.0  | 2         | 1.02%   |
| 64.01-256.0 | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 62        | 29.38%  |
| 1.01-2.0   | 59        | 27.96%  |
| 3.01-4.0   | 38        | 18.01%  |
| 4.01-8.0   | 33        | 15.64%  |
| 0.51-1.0   | 13        | 6.16%   |
| 8.01-16.0  | 3         | 1.42%   |
| 0.01-0.5   | 2         | 0.95%   |
| 16.01-24.0 | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 133       | 66.5%   |
| 2      | 59        | 29.5%   |
| 3      | 5         | 2.5%    |
| 4      | 2         | 1%      |
| 0      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 154       | 78.57%  |
| Yes       | 42        | 21.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 78.97%  |
| No        | 41        | 21.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 98.98%  |
| No        | 2         | 1.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 92.86%  |
| No        | 14        | 7.14%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 46        | 23.47%  |
| Germany     | 13        | 6.63%   |
| Italy       | 9         | 4.59%   |
| India       | 9         | 4.59%   |
| UK          | 8         | 4.08%   |
| Canada      | 8         | 4.08%   |
| France      | 7         | 3.57%   |
| Brazil      | 7         | 3.57%   |
| Russia      | 6         | 3.06%   |
| Poland      | 6         | 3.06%   |
| Netherlands | 6         | 3.06%   |
| Turkey      | 5         | 2.55%   |
| Sweden      | 4         | 2.04%   |
| New Zealand | 4         | 2.04%   |
| Vietnam     | 3         | 1.53%   |
| Portugal    | 3         | 1.53%   |
| Indonesia   | 3         | 1.53%   |
| Greece      | 3         | 1.53%   |
| Finland     | 3         | 1.53%   |
| Bahrain     | 3         | 1.53%   |
| Australia   | 3         | 1.53%   |
| Ukraine     | 2         | 1.02%   |
| Spain       | 2         | 1.02%   |
| Romania     | 2         | 1.02%   |
| Philippines | 2         | 1.02%   |
| Norway      | 2         | 1.02%   |
| Mexico      | 2         | 1.02%   |
| Hong Kong   | 2         | 1.02%   |
| Georgia     | 2         | 1.02%   |
| Denmark     | 2         | 1.02%   |
| Czechia     | 2         | 1.02%   |
| Croatia     | 2         | 1.02%   |
| Belgium     | 2         | 1.02%   |
| Taiwan      | 1         | 0.51%   |
| South Korea | 1         | 0.51%   |
| Slovenia    | 1         | 0.51%   |
| Puerto Rico | 1         | 0.51%   |
| Pakistan    | 1         | 0.51%   |
| Morocco     | 1         | 0.51%   |
| Malaysia    | 1         | 0.51%   |
| Hungary     | 1         | 0.51%   |
| Egypt       | 1         | 0.51%   |
| Colombia    | 1         | 0.51%   |
| Bulgaria    | 1         | 0.51%   |
| Bangladesh  | 1         | 0.51%   |
| Argentina   | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Montreal                    | 5         | 2.45%   |
| Barberton                   | 4         | 1.96%   |
| Toms River                  | 3         | 1.47%   |
| Moscow                      | 3         | 1.47%   |
| Manama                      | 3         | 1.47%   |
| Jacksonville                | 3         | 1.47%   |
| Berlin                      | 3         | 1.47%   |
| Yuma                        | 2         | 0.98%   |
| Warsaw                      | 2         | 0.98%   |
| Victoria                    | 2         | 0.98%   |
| Tbilisi                     | 2         | 0.98%   |
| Sydney                      | 2         | 0.98%   |
| St Petersburg               | 2         | 0.98%   |
| S??o Paulo                  | 2         | 0.98%   |
| Portland                    | 2         | 0.98%   |
| Orlando                     | 2         | 0.98%   |
| Mesa                        | 2         | 0.98%   |
| Ho Chi Minh City            | 2         | 0.98%   |
| Gothenburg                  | 2         | 0.98%   |
| Frankfurt am Main           | 2         | 0.98%   |
| Florence                    | 2         | 0.98%   |
| Chicago                     | 2         | 0.98%   |
| Central                     | 2         | 0.98%   |
| Brussels                    | 2         | 0.98%   |
| Bengaluru                   | 2         | 0.98%   |
| Bandung                     | 2         | 0.98%   |
| Auckland                    | 2         | 0.98%   |
| Ankara                      | 2         | 0.98%   |
| Amsterdam                   | 2         | 0.98%   |
| Ålesund                    | 1         | 0.49%   |
| Zapopan                     | 1         | 0.49%   |
| Wroclaw                     | 1         | 0.49%   |
| Wilmington                  | 1         | 0.49%   |
| Whittier                    | 1         | 0.49%   |
| Wellington                  | 1         | 0.49%   |
| Vrbovec                     | 1         | 0.49%   |
| Villa Ballester             | 1         | 0.49%   |
| Velika Gorica               | 1         | 0.49%   |
| Valparaiso                  | 1         | 0.49%   |
| Valence                     | 1         | 0.49%   |
| Turku                       | 1         | 0.49%   |
| Turin                       | 1         | 0.49%   |
| Toronto                     | 1         | 0.49%   |
| Tampere                     | 1         | 0.49%   |
| Stockholm                   | 1         | 0.49%   |
| Srinagar                    | 1         | 0.49%   |
| Sofia                       | 1         | 0.49%   |
| Ski                         | 1         | 0.49%   |
| Silverdale                  | 1         | 0.49%   |
| Secaucus                    | 1         | 0.49%   |
| Santo André                | 1         | 0.49%   |
| Santo Andr?�                | 1         | 0.49%   |
| San Juan                    | 1         | 0.49%   |
| San Casciano in Val di Pesa | 1         | 0.49%   |
| Saeffle                     | 1         | 0.49%   |
| Rognaix                     | 1         | 0.49%   |
| Rogasovci                   | 1         | 0.49%   |
| Recife                      | 1         | 0.49%   |
| Prague                      | 1         | 0.49%   |
| Poznan                      | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 59        | 76     | 22.43%  |
| Seagate                        | 29        | 31     | 11.03%  |
| WDC                            | 17        | 21     | 6.46%   |
| SK Hynix                       | 16        | 17     | 6.08%   |
| Kingston                       | 14        | 17     | 5.32%   |
| Toshiba                        | 13        | 15     | 4.94%   |
| HGST                           | 13        | 14     | 4.94%   |
| SanDisk                        | 12        | 13     | 4.56%   |
| Intel                          | 9         | 10     | 3.42%   |
| Unknown                        | 7         | 10     | 2.66%   |
| Apple                          | 7         | 7      | 2.66%   |
| KIOXIA                         | 6         | 6      | 2.28%   |
| Crucial                        | 6         | 7      | 2.28%   |
| Micron Technology              | 5         | 5      | 1.9%    |
| A-DATA Technology              | 4         | 5      | 1.52%   |
| Phison                         | 3         | 3      | 1.14%   |
| LITEONIT                       | 3         | 4      | 1.14%   |
| WDC WDS                        | 2         | 2      | 0.76%   |
| Transcend                      | 2         | 2      | 0.76%   |
| Solid State Storage Technology | 2         | 2      | 0.76%   |
| Maxone                         | 2         | 2      | 0.76%   |
| KingSpec                       | 2         | 2      | 0.76%   |
| Hitachi                        | 2         | 2      | 0.76%   |
| HFS256G3                       | 2         | 2      | 0.76%   |
| China                          | 2         | 2      | 0.76%   |
| V-GeN                          | 1         | 1      | 0.38%   |
| USB3.0                         | 1         | 1      | 0.38%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.38%   |
| Teclast                        | 1         | 1      | 0.38%   |
| Team                           | 1         | 2      | 0.38%   |
| StoreJet                       | 1         | 1      | 0.38%   |
| PNY                            | 1         | 1      | 0.38%   |
| OCZ                            | 1         | 1      | 0.38%   |
| Mushkin                        | 1         | 1      | 0.38%   |
| Micron/Crucial Technology      | 1         | 1      | 0.38%   |
| LITEON                         | 1         | 1      | 0.38%   |
| Lite-On                        | 1         | 1      | 0.38%   |
| Lenovo                         | 1         | 1      | 0.38%   |
| KingFast                       | 1         | 1      | 0.38%   |
| KingDian                       | 1         | 1      | 0.38%   |
| JMicron                        | 1         | 1      | 0.38%   |
| HUAWEI                         | 1         | 1      | 0.38%   |
| GOODRAM                        | 1         | 1      | 0.38%   |
| Gigabyte Technology            | 1         | 1      | 0.38%   |
| Generic-                       | 1         | 1      | 0.38%   |
| Fujitsu                        | 1         | 1      | 0.38%   |
| FORESEE                        | 1         | 1      | 0.38%   |
| Corsair                        | 1         | 1      | 0.38%   |
| APPLE HD                       | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 10        | 3.66%   |
| HGST HTS721010A9E630 1TB                  | 7         | 2.56%   |
| Seagate ST500LT012-1DG142 500GB           | 6         | 2.2%    |
| Samsung SSD 970 EVO 500GB                 | 4         | 1.47%   |
| Samsung SSD 870 EVO 250GB                 | 4         | 1.47%   |
| Samsung SSD 860 EVO 250GB                 | 4         | 1.47%   |
| Apple SSD SM0128G 121GB                   | 4         | 1.47%   |
| Seagate ST1000LM049-2GH172 1TB            | 3         | 1.1%    |
| Samsung SSD 860 EVO 500GB                 | 3         | 1.1%    |
| Samsung SSD 860 EVO 1TB                   | 3         | 1.1%    |
| Samsung NVMe SSD Drive 512GB              | 3         | 1.1%    |
| Kingston SA400S37240G 240GB SSD           | 3         | 1.1%    |
| WDC WDS 500G2B0B-00YS70 500GB SSD         | 2         | 0.73%   |
| WDC WD10SPZX-24Z10 1TB                    | 2         | 0.73%   |
| Unknown MMC Card  64GB                    | 2         | 0.73%   |
| Transcend TS240GMTS420S 240GB SSD         | 2         | 0.73%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 0.73%   |
| Toshiba KBG40ZNT512G MEMORY 512GB         | 2         | 0.73%   |
| Solid State Storage NVMe SSD Drive 256GB  | 2         | 0.73%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 2         | 0.73%   |
| SK Hynix HFM128GDJTNG-8310A 128GB         | 2         | 0.73%   |
| SK Hynix HFM001TD3JX013N 1TB              | 2         | 0.73%   |
| Sandisk NVMe SSD Drive 1TB                | 2         | 0.73%   |
| Samsung SSD 970 EVO 1TB                   | 2         | 0.73%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 0.73%   |
| Samsung SSD 850 EVO 250GB                 | 2         | 0.73%   |
| Samsung NVMe SSD Drive 1TB                | 2         | 0.73%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD      | 2         | 0.73%   |
| Samsung MZVLB256HAHQ-000H1 256GB          | 2         | 0.73%   |
| Samsung MZVLB1T0HBLR-00000 1TB            | 2         | 0.73%   |
| Samsung MZVL21T0HCLR-00B00 1TB            | 2         | 0.73%   |
| Samsung MZNLN256HAJQ-000H1 256GB SSD      | 2         | 0.73%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD      | 2         | 0.73%   |
| Maxone USB 3.0 160GB                      | 2         | 0.73%   |
| KIOXIA KBG40ZNV512G 512GB                 | 2         | 0.73%   |
| KIOXIA KBG40ZNV1T02 1TB                   | 2         | 0.73%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 0.73%   |
| Kingston OM8PCP3512F-AI1 512GB            | 2         | 0.73%   |
| Intel NVMe SSD Drive 512GB                | 2         | 0.73%   |
| Hitachi HTS545050A7E380 500GB             | 2         | 0.73%   |
| HGST HTS541010B7E610 1TB                  | 2         | 0.73%   |
| HFS256G3 9TND-N210A 256GB                 | 2         | 0.73%   |
| Crucial CT250MX500SSD1 250GB              | 2         | 0.73%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.37%   |
| WDC WD5000LPCX-24C6HT0 500GB              | 1         | 0.37%   |
| WDC WD1600BEVT-22ZCT0 160GB               | 1         | 0.37%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.37%   |
| WDC WD10JPCX-24UE4T0 1TB                  | 1         | 0.37%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB        | 1         | 0.37%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB      | 1         | 0.37%   |
| WDC PC SN720 SDAPNTW-256G-1006 256GB      | 1         | 0.37%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB      | 1         | 0.37%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB        | 1         | 0.37%   |
| WDC PC SN530 NVMe 256GB                   | 1         | 0.37%   |
| V-GeN V-GEN12AS19AR120SDK 120GB SSD       | 1         | 0.37%   |
| USB3.0 Super Speed 320GB                  | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 26        | 27     | 42.62%  |
| HGST     | 13        | 14     | 21.31%  |
| WDC      | 7         | 8      | 11.48%  |
| Toshiba  | 6         | 6      | 9.84%   |
| Maxone   | 2         | 2      | 3.28%   |
| Hitachi  | 2         | 2      | 3.28%   |
| USB3.0   | 1         | 1      | 1.64%   |
| Unknown  | 1         | 1      | 1.64%   |
| StoreJet | 1         | 1      | 1.64%   |
| Generic- | 1         | 1      | 1.64%   |
| Fujitsu  | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 45     | 34.62%  |
| Kingston            | 10        | 13     | 9.62%   |
| SanDisk             | 8         | 8      | 7.69%   |
| Apple               | 6         | 6      | 5.77%   |
| WDC                 | 4         | 6      | 3.85%   |
| SK Hynix            | 4         | 4      | 3.85%   |
| Crucial             | 4         | 4      | 3.85%   |
| LITEONIT            | 3         | 4      | 2.88%   |
| WDC WDS             | 2         | 2      | 1.92%   |
| Transcend           | 2         | 2      | 1.92%   |
| Micron Technology   | 2         | 2      | 1.92%   |
| KingSpec            | 2         | 2      | 1.92%   |
| China               | 2         | 2      | 1.92%   |
| A-DATA Technology   | 2         | 3      | 1.92%   |
| V-GeN               | 1         | 1      | 0.96%   |
| Unknown             | 1         | 2      | 0.96%   |
| Toshiba             | 1         | 1      | 0.96%   |
| Teclast             | 1         | 1      | 0.96%   |
| Team                | 1         | 2      | 0.96%   |
| Seagate             | 1         | 1      | 0.96%   |
| PNY                 | 1         | 1      | 0.96%   |
| OCZ                 | 1         | 1      | 0.96%   |
| Mushkin             | 1         | 1      | 0.96%   |
| LITEON              | 1         | 1      | 0.96%   |
| KingFast            | 1         | 1      | 0.96%   |
| KingDian            | 1         | 1      | 0.96%   |
| Intel               | 1         | 1      | 0.96%   |
| GOODRAM             | 1         | 1      | 0.96%   |
| Gigabyte Technology | 1         | 1      | 0.96%   |
| FORESEE             | 1         | 1      | 0.96%   |
| Corsair             | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 91        | 122    | 36.84%  |
| NVMe    | 85        | 102    | 34.41%  |
| HDD     | 59        | 64     | 23.89%  |
| MMC     | 6         | 8      | 2.43%   |
| Unknown | 6         | 6      | 2.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 174    | 54.74%  |
| NVMe | 85        | 102    | 36.64%  |
| SAS  | 14        | 18     | 6.03%   |
| MMC  | 6         | 8      | 2.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 126    | 64%     |
| 0.51-1.0   | 49        | 54     | 32.67%  |
| 1.01-2.0   | 5         | 6      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 24.75%  |
| 251-500        | 44        | 21.78%  |
| 501-1000       | 33        | 16.34%  |
| 1001-2000      | 22        | 10.89%  |
| Unknown        | 15        | 7.43%   |
| More than 3000 | 10        | 4.95%   |
| 51-100         | 10        | 4.95%   |
| 21-50          | 7         | 3.47%   |
| 2001-3000      | 6         | 2.97%   |
| 1-20           | 5         | 2.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 22.82%  |
| 21-50          | 41        | 19.9%   |
| 101-250        | 35        | 16.99%  |
| 51-100         | 25        | 12.14%  |
| 251-500        | 23        | 11.17%  |
| Unknown        | 15        | 7.28%   |
| 1001-2000      | 10        | 4.85%   |
| 501-1000       | 6         | 2.91%   |
| More than 3000 | 2         | 0.97%   |
| 2001-3000      | 2         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 3         | 3      | 20%     |
| Hitachi HTS545050A7E380 500GB                    | 2         | 2      | 13.33%  |
| Toshiba MK5055GSXF 500GB                         | 1         | 1      | 6.67%   |
| SK Hynix SC308 SATA 128GB SSD                    | 1         | 1      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 6.67%   |
| Seagate ST1000LM049-2GH172 1TB                   | 1         | 1      | 6.67%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 970 EVO 500GB            | 1         | 1      | 6.67%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 6.67%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 6.67%   |
| Fujitsu MHZ2320BH G2 320GB                       | 1         | 1      | 6.67%   |
| Apple SSD SM256C 256GB                           | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 4      | 26.67%  |
| Seagate             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Hitachi             | 2         | 2      | 13.33%  |
| Toshiba             | 1         | 1      | 6.67%   |
| SK Hynix            | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 1      | 6.67%   |
| Fujitsu             | 1         | 1      | 6.67%   |
| Apple               | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 4      | 40%     |
| Seagate | 2         | 2      | 20%     |
| Hitachi | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 66.67%  |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 1         | 1      | 6.67%   |

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
| Works    | 137       | 191    | 64.02%  |
| Detected | 62        | 96     | 28.97%  |
| Malfunc  | 15        | 15     | 7.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 119       | 50.64%  |
| Samsung Electronics            | 30        | 12.77%  |
| AMD                            | 28        | 11.91%  |
| SK Hynix                       | 11        | 4.68%   |
| Sandisk                        | 9         | 3.83%   |
| KIOXIA                         | 8         | 3.4%    |
| Toshiba America Info Systems   | 4         | 1.7%    |
| Kingston Technology Company    | 4         | 1.7%    |
| Phison Electronics             | 3         | 1.28%   |
| Micron/Crucial Technology      | 3         | 1.28%   |
| Micron Technology              | 3         | 1.28%   |
| Solid State Storage Technology | 2         | 0.85%   |
| Seagate Technology             | 2         | 0.85%   |
| ADATA Technology               | 2         | 0.85%   |
| Union Memory (Shenzhen)        | 1         | 0.43%   |
| Nvidia                         | 1         | 0.43%   |
| Marvell Technology Group       | 1         | 0.43%   |
| Lite-On Technology             | 1         | 0.43%   |
| Lenovo                         | 1         | 0.43%   |
| JMicron Technology             | 1         | 0.43%   |
| Apple                          | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 27        | 10.98%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 24        | 9.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 8.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 6.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 4.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 3.66%   |
| KIOXIA Non-Volatile memory controller                                          | 8         | 3.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.44%   |
| SK Hynix Gold P31 SSD                                                          | 5         | 2.03%   |
| Intel SSD 660P Series                                                          | 5         | 2.03%   |
| SK Hynix Non-Volatile memory controller                                        | 4         | 1.63%   |
| Samsung Electronics SATA controller                                            | 4         | 1.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.63%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 4         | 1.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.22%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.22%   |
| Micron Non-Volatile memory controller                                          | 3         | 1.22%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.22%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 0.81%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.81%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.81%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 0.81%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.81%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 0.81%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.81%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.41%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.41%   |
| SK Hynix BC511                                                                 | 1         | 0.41%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 0.41%   |
| Seagate Non-Volatile memory controller                                         | 1         | 0.41%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.41%   |
| Sandisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.41%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 0.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.41%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.41%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.41%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.41%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.41%   |
| Lite-On NVMe Controller                                                        | 1         | 0.41%   |
| Lenovo Non-Volatile memory controller                                          | 1         | 0.41%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.41%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 0.41%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.41%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.41%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 0.41%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 0.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 0.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 131       | 55.51%  |
| NVMe | 84        | 35.59%  |
| RAID | 18        | 7.63%   |
| IDE  | 3         | 1.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 144       | 73.85%  |
| AMD    | 50        | 25.64%  |
| ARM    | 1         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 3.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 3.08%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 2.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 2.56%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 2.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 2.05%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 2.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.54%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 3         | 1.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.54%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.54%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 3         | 1.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.03%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.03%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 2         | 1.03%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.03%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 2         | 1.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.03%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 1.03%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.03%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.03%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.03%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.03%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 2         | 1.03%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.03%   |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 2         | 1.03%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.03%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.03%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 1.03%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.51%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.51%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.51%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.51%   |
| Intel Core i7-6820HK CPU @ 2.70GHz            | 1         | 0.51%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.51%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.51%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.51%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.51%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.51%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 0.51%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.51%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.51%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 0.51%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 0.51%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.51%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.51%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.51%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 59        | 30.26%  |
| Intel Core i7        | 55        | 28.21%  |
| AMD Ryzen 7          | 12        | 6.15%   |
| Other                | 11        | 5.64%   |
| Intel Core i3        | 10        | 5.13%   |
| AMD Ryzen 5          | 9         | 4.62%   |
| AMD Ryzen 7 PRO      | 6         | 3.08%   |
| AMD A4               | 6         | 3.08%   |
| AMD Ryzen 9          | 5         | 2.56%   |
| Intel Celeron        | 4         | 2.05%   |
| Intel Core 2 Duo     | 3         | 1.54%   |
| AMD Ryzen 3          | 3         | 1.54%   |
| AMD A8               | 3         | 1.54%   |
| AMD E1               | 2         | 1.03%   |
| Intel Xeon           | 1         | 0.51%   |
| Intel Pentium        | 1         | 0.51%   |
| Intel Core m3        | 1         | 0.51%   |
| Intel Core 2 Extreme | 1         | 0.51%   |
| AMD Ryzen 5 PRO      | 1         | 0.51%   |
| AMD E                | 1         | 0.51%   |
| AMD Athlon           | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 40%     |
| 4      | 72        | 36.92%  |
| 8      | 26        | 13.33%  |
| 6      | 19        | 9.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 194       | 99.49%  |
| 2      | 1         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 168       | 86.15%  |
| 1      | 27        | 13.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 193       | 98.97%  |
| 64-bit         | 1         | 0.51%   |
| Unknown        | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 25.76%  |
| 0x406e3    | 12        | 6.06%   |
| 0x906ea    | 9         | 4.55%   |
| 0x806ec    | 8         | 4.04%   |
| 0x806ea    | 8         | 4.04%   |
| 0x40651    | 8         | 4.04%   |
| 0x306c3    | 8         | 4.04%   |
| 0x306a9    | 8         | 4.04%   |
| 0x0a50000c | 7         | 3.54%   |
| 0x506e3    | 6         | 3.03%   |
| 0x306d4    | 5         | 2.53%   |
| 0x206a7    | 5         | 2.53%   |
| 0x08600104 | 5         | 2.53%   |
| 0x08108109 | 5         | 2.53%   |
| 0xa0652    | 4         | 2.02%   |
| 0x806e9    | 4         | 2.02%   |
| 0x706e5    | 4         | 2.02%   |
| 0x08600106 | 4         | 2.02%   |
| 0x08108102 | 4         | 2.02%   |
| 0x906e9    | 3         | 1.52%   |
| 0x806d1    | 3         | 1.52%   |
| 0x20655    | 3         | 1.52%   |
| 0x806c1    | 2         | 1.01%   |
| 0x706a1    | 2         | 1.01%   |
| 0x1067a    | 2         | 1.01%   |
| 0x08608103 | 2         | 1.01%   |
| 0x08600102 | 2         | 1.01%   |
| 0x07000110 | 2         | 1.01%   |
| 0x706a8    | 1         | 0.51%   |
| 0x506c9    | 1         | 0.51%   |
| 0x20652    | 1         | 0.51%   |
| 0x08608102 | 1         | 0.51%   |
| 0x08600103 | 1         | 0.51%   |
| 0x08001137 | 1         | 0.51%   |
| 0x07030105 | 1         | 0.51%   |
| 0x07030104 | 1         | 0.51%   |
| 0x0700010f | 1         | 0.51%   |
| 0x06006705 | 1         | 0.51%   |
| 0x06006704 | 1         | 0.51%   |
| 0x06001119 | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 43        | 22.05%  |
| Skylake       | 23        | 11.79%  |
| Haswell       | 18        | 9.23%   |
| Zen 2         | 15        | 7.69%   |
| IvyBridge     | 11        | 5.64%   |
| Zen+          | 10        | 5.13%   |
| IceLake       | 9         | 4.62%   |
| Zen 3         | 8         | 4.1%    |
| Broadwell     | 8         | 4.1%    |
| SandyBridge   | 7         | 3.59%   |
| CometLake     | 6         | 3.08%   |
| TigerLake     | 5         | 2.56%   |
| Jaguar        | 5         | 2.56%   |
| Unknown       | 5         | 2.56%   |
| Westmere      | 4         | 2.05%   |
| Penryn        | 3         | 1.54%   |
| Goldmont plus | 3         | 1.54%   |
| Excavator     | 3         | 1.54%   |
| Puma          | 2         | 1.03%   |
| Piledriver    | 2         | 1.03%   |
| Zen           | 1         | 0.51%   |
| Silvermont    | 1         | 0.51%   |
| Goldmont      | 1         | 0.51%   |
| Core          | 1         | 0.51%   |
| Bobcat        | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 134       | 51.34%  |
| Nvidia | 69        | 26.44%  |
| AMD    | 58        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                   | 15        | 5.62%   |
| AMD Renoir                                                                            | 15        | 5.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 13        | 4.87%   |
| Intel UHD Graphics 620                                                                | 11        | 4.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 3.75%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 10        | 3.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 10        | 3.75%   |
| AMD Cezanne                                                                           | 8         | 3%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 2.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 2.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 6         | 2.25%   |
| Intel HD Graphics 530                                                                 | 5         | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 5         | 1.87%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 4         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 4         | 1.5%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 4         | 1.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 1.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.5%    |
| Intel HD Graphics 6000                                                                | 4         | 1.5%    |
| Intel HD Graphics 5500                                                                | 4         | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                                   | 4         | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 1.12%   |
| Nvidia GP108M [GeForce MX250]                                                         | 3         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.12%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 3         | 1.12%   |
| Nvidia GM108M [GeForce 940M]                                                          | 3         | 1.12%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 3         | 1.12%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 1.12%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 3         | 1.12%   |
| Intel HD Graphics 630                                                                 | 3         | 1.12%   |
| Intel HD Graphics 620                                                                 | 3         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 1.12%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 3         | 1.12%   |
| AMD Lucienne                                                                          | 3         | 1.12%   |
| AMD Kabini [Radeon HD 8330]                                                           | 3         | 1.12%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 2         | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 0.75%   |
| Nvidia GP107M [GeForce MX350]                                                         | 2         | 0.75%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 2         | 0.75%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 2         | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 0.75%   |
| Nvidia GF108M [GeForce GT 540M]                                                       | 2         | 0.75%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 0.75%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 2         | 0.75%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                               | 2         | 0.75%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                    | 1         | 0.37%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 0.37%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.37%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.37%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                 | 1         | 0.37%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                 | 1         | 0.37%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 1         | 0.37%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 0.37%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                 | 1         | 0.37%   |
| Nvidia GM108M [GeForce MX110]                                                         | 1         | 0.37%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.37%   |
| Nvidia GK107M [GeForce GT 755M]                                                       | 1         | 0.37%   |
| Nvidia GK107M [GeForce GT 750M]                                                       | 1         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 73        | 37.44%  |
| Intel + Nvidia | 53        | 27.18%  |
| 1 x AMD        | 39        | 20%     |
| 1 x Nvidia     | 10        | 5.13%   |
| Intel + AMD    | 8         | 4.1%    |
| AMD + Nvidia   | 6         | 3.08%   |
| 2 x AMD        | 5         | 2.56%   |
| Other          | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 145       | 74.36%  |
| Proprietary | 49        | 25.13%  |
| Unknown     | 1         | 0.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 64.65%  |
| 0.01-0.5   | 26        | 13.13%  |
| 1.01-2.0   | 18        | 9.09%   |
| 3.01-4.0   | 8         | 4.04%   |
| 0.51-1.0   | 7         | 3.54%   |
| 7.01-8.0   | 5         | 2.53%   |
| 5.01-6.0   | 3         | 1.52%   |
| 2.01-3.0   | 3         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 50        | 21.55%  |
| LG Display              | 36        | 15.52%  |
| Chimei Innolux          | 31        | 13.36%  |
| BOE                     | 25        | 10.78%  |
| Samsung Electronics     | 18        | 7.76%   |
| Apple                   | 9         | 3.88%   |
| PANDA                   | 8         | 3.45%   |
| Sharp                   | 6         | 2.59%   |
| Dell                    | 6         | 2.59%   |
| Lenovo                  | 5         | 2.16%   |
| InfoVision              | 5         | 2.16%   |
| Goldstar                | 4         | 1.72%   |
| ViewSonic               | 3         | 1.29%   |
| Sony                    | 3         | 1.29%   |
| Philips                 | 3         | 1.29%   |
| Hewlett-Packard         | 3         | 1.29%   |
| CSO                     | 2         | 0.86%   |
| Chi Mei Optoelectronics | 2         | 0.86%   |
| Ancor Communications    | 2         | 0.86%   |
| Acer                    | 2         | 0.86%   |
| Vizio                   | 1         | 0.43%   |
| Unknown                 | 1         | 0.43%   |
| Sun                     | 1         | 0.43%   |
| Sceptre Tech            | 1         | 0.43%   |
| Pixio                   | 1         | 0.43%   |
| InnoLux Display         | 1         | 0.43%   |
| Gigabyte Technology     | 1         | 0.43%   |
| DENON                   | 1         | 0.43%   |
| AOC                     | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 5         | 2.14%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch         | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch          | 3         | 1.28%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 2         | 0.85%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 2         | 0.85%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.85%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 2         | 0.85%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 2         | 0.85%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 2         | 0.85%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 2         | 0.85%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 2         | 0.85%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 0.85%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch           | 2         | 0.85%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch       | 2         | 0.85%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 2         | 0.85%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                  | 2         | 0.85%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                  | 2         | 0.85%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                   | 2         | 0.85%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch         | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 340x190mm 15.3-inch          | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 0.85%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                    | 1         | 0.43%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1         | 0.43%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1         | 0.43%   |
| ViewSonic VX2456 SERIES VSC4F2F 1920x1080 521x293mm 23.5-inch          | 1         | 0.43%   |
| Unknown LCD Monitor Sharp LQ156M1JW03 3840x1080                        | 1         | 0.43%   |
| Unknown LCD Monitor Dell SE2717H/HX                                    | 1         | 0.43%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                 | 1         | 0.43%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.43%   |
| Sony TV *00 SNYF503 1920x1080 1218x685mm 55.0-inch                     | 1         | 0.43%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                          | 1         | 0.43%   |
| Sharp LQ156M1JW16 SHP14F4 1920x1080 344x194mm 15.5-inch                | 1         | 0.43%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.43%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                | 1         | 0.43%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.43%   |
| Sceptre Tech Sceptre T27 SPT0AD7 1920x1080 600x330mm 27.0-inch         | 1         | 0.43%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch      | 1         | 0.43%   |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch       | 1         | 0.43%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 630x360mm 28.6-inch      | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch   | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch   | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch   | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch   | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4652 1366x768 344x194mm 15.5-inch   | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC3854 1920x1080 382x215mm 17.3-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SAM0E35 1920x1080 1210x680mm 54.6-inch | 1         | 0.43%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 121       | 55%     |
| 1366x768 (WXGA)    | 50        | 22.73%  |
| 3840x2160 (4K)     | 9         | 4.09%   |
| 1440x900 (WXGA+)   | 8         | 3.64%   |
| 2560x1440 (QHD)    | 7         | 3.18%   |
| 2560x1600          | 5         | 2.27%   |
| 1280x800 (WXGA)    | 4         | 1.82%   |
| 1920x1200 (WUXGA)  | 3         | 1.36%   |
| 2160x1440          | 2         | 0.91%   |
| 1600x900 (HD+)     | 2         | 0.91%   |
| 3840x2400          | 1         | 0.45%   |
| 3840x1080          | 1         | 0.45%   |
| 3456x2160          | 1         | 0.45%   |
| 3200x1800 (QHD+)   | 1         | 0.45%   |
| 2880x1800          | 1         | 0.45%   |
| 2560x1080          | 1         | 0.45%   |
| 2256x1504          | 1         | 0.45%   |
| 1680x1050 (WSXGA+) | 1         | 0.45%   |
| Unknown            | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 91        | 39.06%  |
| 13      | 49        | 21.03%  |
| 14      | 25        | 10.73%  |
| 17      | 13        | 5.58%   |
| 27      | 10        | 4.29%   |
| 21      | 6         | 2.58%   |
| 24      | 5         | 2.15%   |
| 23      | 5         | 2.15%   |
| 11      | 5         | 2.15%   |
| 12      | 4         | 1.72%   |
| 18      | 3         | 1.29%   |
| 16      | 3         | 1.29%   |
| 31      | 2         | 0.86%   |
| 72      | 1         | 0.43%   |
| 65      | 1         | 0.43%   |
| 57      | 1         | 0.43%   |
| 54      | 1         | 0.43%   |
| 49      | 1         | 0.43%   |
| 42      | 1         | 0.43%   |
| 29      | 1         | 0.43%   |
| 28      | 1         | 0.43%   |
| 25      | 1         | 0.43%   |
| 22      | 1         | 0.43%   |
| 8       | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 141       | 60.52%  |
| 201-300     | 34        | 14.59%  |
| 501-600     | 21        | 9.01%   |
| 351-400     | 15        | 6.44%   |
| 401-500     | 10        | 4.29%   |
| 601-700     | 4         | 1.72%   |
| 1001-1500   | 4         | 1.72%   |
| 1501-2000   | 1         | 0.43%   |
| 101-200     | 1         | 0.43%   |
| 901-1000    | 1         | 0.43%   |
| Unknown     | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 170       | 85.43%  |
| 16/10   | 23        | 11.56%  |
| 3/2     | 3         | 1.51%   |
| 2.65    | 1         | 0.5%    |
| 0.62    | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 91        | 39.22%  |
| 81-90          | 54        | 23.28%  |
| 71-80          | 21        | 9.05%   |
| 201-250        | 14        | 6.03%   |
| 121-130        | 11        | 4.74%   |
| 301-350        | 10        | 4.31%   |
| More than 1000 | 5         | 2.16%   |
| 51-60          | 5         | 2.16%   |
| 251-300        | 4         | 1.72%   |
| 61-70          | 3         | 1.29%   |
| 351-500        | 3         | 1.29%   |
| 141-150        | 3         | 1.29%   |
| 111-120        | 3         | 1.29%   |
| 131-140        | 2         | 0.86%   |
| 1-40           | 1         | 0.43%   |
| 501-1000       | 1         | 0.43%   |
| Unknown        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 116       | 50.43%  |
| 101-120       | 52        | 22.61%  |
| 51-100        | 26        | 11.3%   |
| 161-240       | 21        | 9.13%   |
| More than 240 | 9         | 3.91%   |
| 1-50          | 5         | 2.17%   |
| Unknown       | 1         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 159       | 79.9%   |
| 2     | 39        | 19.6%   |
| 3     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 121       | 38.17%  |
| Realtek Semiconductor | 112       | 35.33%  |
| Qualcomm Atheros      | 31        | 9.78%   |
| Broadcom              | 12        | 3.79%   |
| MediaTek              | 8         | 2.52%   |
| D-Link                | 6         | 1.89%   |
| Broadcom Limited      | 6         | 1.89%   |
| TP-Link               | 5         | 1.58%   |
| Hewlett-Packard       | 3         | 0.95%   |
| ASIX Electronics      | 3         | 0.95%   |
| Sierra Wireless       | 2         | 0.63%   |
| Lenovo                | 2         | 0.63%   |
| NetGear               | 1         | 0.32%   |
| Linksys               | 1         | 0.32%   |
| Huawei Technologies   | 1         | 0.32%   |
| DisplayLink           | 1         | 0.32%   |
| Cypress Semiconductor | 1         | 0.32%   |
| Apple                 | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 20.26%  |
| Intel Wi-Fi 6 AX200                                               | 22        | 5.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.12%   |
| Intel Wireless 7260                                               | 11        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.08%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 2.08%   |
| Intel Wireless 8260                                               | 7         | 1.82%   |
| Intel Wireless 7265                                               | 7         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 1.56%   |
| MEDIATEK Network controller                                       | 6         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 1.56%   |
| D-Link 802.11ac NIC                                               | 6         | 1.56%   |
| TP-Link 802.11ac NIC                                              | 5         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.3%    |
| Intel Wireless 3165                                               | 5         | 1.3%    |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.3%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 5         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.04%   |
| Realtek 802.11ac NIC                                              | 4         | 1.04%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.78%   |
| Intel Wireless 3160                                               | 3         | 0.78%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.78%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.78%   |
| HP un2430 Mobile Broadband Module                                 | 3         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.52%   |
| Realtek Realtek Ethernet controller                               | 2         | 0.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.52%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.52%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.52%   |
| Sierra Wireless EM7455                                            | 1         | 0.26%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.26%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.26%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                            | 1         | 0.26%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 0.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 120       | 56.87%  |
| Realtek Semiconductor | 27        | 12.8%   |
| Qualcomm Atheros      | 26        | 12.32%  |
| Broadcom              | 11        | 5.21%   |
| MediaTek              | 8         | 3.79%   |
| D-Link                | 6         | 2.84%   |
| Broadcom Limited      | 6         | 2.84%   |
| TP-Link               | 5         | 2.37%   |
| Sierra Wireless       | 1         | 0.47%   |
| Linksys               | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 22        | 10.28%  |
| Intel Wireless 7260                                                    | 11        | 5.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 4.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 4.21%   |
| Intel Wireless 8265 / 8275                                             | 8         | 3.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 3.74%   |
| Intel Wireless 8260                                                    | 7         | 3.27%   |
| Intel Wireless 7265                                                    | 7         | 3.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 7         | 3.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 2.8%    |
| MEDIATEK Network controller                                            | 6         | 2.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 6         | 2.8%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 2.8%    |
| D-Link 802.11ac NIC                                                    | 6         | 2.8%    |
| TP-Link 802.11ac NIC                                                   | 5         | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 2.34%   |
| Intel Wireless 3165                                                    | 5         | 2.34%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter             | 5         | 2.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 1.87%   |
| Realtek 802.11ac NIC                                                   | 4         | 1.87%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 1.87%   |
| Broadcom BCM43142 802.11b/g/n                                          | 4         | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 1.4%    |
| Intel Wireless 3160                                                    | 3         | 1.4%    |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 3         | 1.4%    |
| Intel Centrino Advanced-N 6235                                         | 3         | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 0.93%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.93%   |
| Sierra Wireless EM7455                                                 | 1         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.47%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                 | 1         | 0.47%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1         | 0.47%   |
| MediaTek WiFi                                                          | 1         | 0.47%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                    | 1         | 0.47%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1         | 0.47%   |
| Intel Wireless-AC 9260                                                 | 1         | 0.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 0.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 1         | 0.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 1         | 0.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1         | 0.47%   |
| Intel Centrino Wireless-N 2230                                         | 1         | 0.47%   |
| D-Link DWA-171                                                         | 1         | 0.47%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter             | 1         | 0.47%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                     | 1         | 0.47%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                     | 1         | 0.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 1         | 0.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 1         | 0.47%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 99        | 60.74%  |
| Intel                 | 40        | 24.54%  |
| Qualcomm Atheros      | 11        | 6.75%   |
| Broadcom              | 3         | 1.84%   |
| ASIX Electronics      | 3         | 1.84%   |
| Lenovo                | 2         | 1.23%   |
| Sierra Wireless       | 1         | 0.61%   |
| NetGear               | 1         | 0.61%   |
| DisplayLink           | 1         | 0.61%   |
| Cypress Semiconductor | 1         | 0.61%   |
| Apple                 | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 46.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 7.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 4.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 3.59%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.99%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.4%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.4%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.8%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.2%    |
| Realtek Realtek Ethernet controller                               | 2         | 1.2%    |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 1.2%    |
| Intel Ethernet Connection I219-V                                  | 2         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.2%    |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.6%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.6%    |
| NetGear LB1120-100NAS                                             | 1         | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.6%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.6%    |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.6%    |
| Cypress K38231_03                                                 | 1         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.6%    |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 1         | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.6%    |
| Apple T2 Controller                                               | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 194       | 55.27%  |
| Ethernet | 153       | 43.59%  |
| Modem    | 4         | 1.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 176       | 74.58%  |
| Ethernet | 59        | 25%     |
| Modem    | 1         | 0.42%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 138       | 70.77%  |
| 1     | 49        | 25.13%  |
| 3     | 6         | 3.08%   |
| 0     | 2         | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 162       | 82.23%  |
| Yes  | 35        | 17.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 59.46%  |
| Realtek Semiconductor           | 19        | 10.27%  |
| Qualcomm Atheros Communications | 16        | 8.65%   |
| Broadcom                        | 9         | 4.86%   |
| Apple                           | 8         | 4.32%   |
| Lite-On Technology              | 6         | 3.24%   |
| IMC Networks                    | 6         | 3.24%   |
| Foxconn / Hon Hai               | 4         | 2.16%   |
| Realtek                         | 3         | 1.62%   |
| Toshiba                         | 1         | 0.54%   |
| MediaTek                        | 1         | 0.54%   |
| Foxconn International           | 1         | 0.54%   |
| Dell                            | 1         | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 47        | 25.41%  |
| Intel Bluetooth Device                            | 34        | 18.38%  |
| Intel AX200 Bluetooth                             | 22        | 11.89%  |
| Qualcomm Atheros  Bluetooth Device                | 11        | 5.95%   |
| Realtek Bluetooth Radio                           | 10        | 5.41%   |
| Realtek  Bluetooth 4.2 Adapter                    | 6         | 3.24%   |
| Apple Bluetooth USB Host Controller               | 6         | 3.24%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 4         | 2.16%   |
| IMC Networks Wireless_Device                      | 4         | 2.16%   |
| Realtek Bluetooth Radio                           | 3         | 1.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 3         | 1.62%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 2         | 1.08%   |
| Lite-On Bluetooth Device                          | 2         | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 1.08%   |
| IMC Networks Bluetooth Radio                      | 2         | 1.08%   |
| Broadcom BCM2045B (BDC-2.1)                       | 2         | 1.08%   |
| Toshiba BCM43142A0                                | 1         | 0.54%   |
| Realtek RTL8821A Bluetooth                        | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.54%   |
| MediaTek Wireless_Device                          | 1         | 0.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 0.54%   |
| Lite-On Atheros Bluetooth                         | 1         | 0.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 0.54%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                 | 1         | 0.54%   |
| Foxconn / Hon Hai BT                              | 1         | 0.54%   |
| Foxconn / Hon Hai Bluetooth Device                | 1         | 0.54%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth   | 1         | 0.54%   |
| Dell Broadcom BCM20702A0 Bluetooth                | 1         | 0.54%   |
| Broadcom HP Portable Valentine                    | 1         | 0.54%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.54%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 0.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                 | 1         | 0.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 1         | 0.54%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]  | 1         | 0.54%   |
| Broadcom BCM2045A0                                | 1         | 0.54%   |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 1         | 0.54%   |
| Apple Bluetooth Host Controller                   | 1         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 143       | 52.96%  |
| AMD                                             | 50        | 18.52%  |
| Nvidia                                          | 42        | 15.56%  |
| Texas Instruments                               | 5         | 1.85%   |
| C-Media Electronics                             | 5         | 1.85%   |
| KORG                                            | 4         | 1.48%   |
| AKAI                                            | 4         | 1.48%   |
| Realtek Semiconductor                           | 2         | 0.74%   |
| Lenovo                                          | 2         | 0.74%   |
| Tdlasunnic                                      | 1         | 0.37%   |
| Sony                                            | 1         | 0.37%   |
| Samson Technologies                             | 1         | 0.37%   |
| Micro Star International                        | 1         | 0.37%   |
| M-Audio                                         | 1         | 0.37%   |
| Logitech                                        | 1         | 0.37%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.37%   |
| Generalplus Technology                          | 1         | 0.37%   |
| Focusrite-Novation                              | 1         | 0.37%   |
| Creative Technology                             | 1         | 0.37%   |
| Corsair                                         | 1         | 0.37%   |
| Apple                                           | 1         | 0.37%   |
| AKAI Professional M.I.                          | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 35        | 10.14%  |
| Intel Sunrise Point-LP HD Audio                                            | 31        | 8.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 7.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 3.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 3.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 2.9%    |
| Intel 8 Series HD Audio Controller                                         | 10        | 2.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 2.9%    |
| AMD FCH Azalia Controller                                                  | 9         | 2.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 2.32%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 2.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 2.32%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 2.03%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.74%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.45%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.16%   |
| Nvidia GM204 High Definition Audio Controller                              | 4         | 1.16%   |
| Nvidia Audio device                                                        | 4         | 1.16%   |
| KORG nanoKONTROL2 MIDI Controller                                          | 4         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.16%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.16%   |
| AKAI MPKmini2                                                              | 4         | 1.16%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.87%   |
| AMD High Definition Audio Controller                                       | 3         | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 0.87%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.58%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.58%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.58%   |
| C-Media Electronics USB Advanced Audio Device                              | 2         | 0.58%   |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 0.58%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.58%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.58%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.58%   |
| Texas Instruments PCM2912A Audio Codec                                     | 1         | 0.29%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1         | 0.29%   |
| Tdlasunnic Sharkoon Mobile DAC                                             | 1         | 0.29%   |
| Sony Wireless Controller                                                   | 1         | 0.29%   |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.29%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.29%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.29%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.29%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.29%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.29%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.29%   |
| Nvidia GF104 High Definition Audio Controller                              | 1         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 59        | 33.91%  |
| SK Hynix            | 44        | 25.29%  |
| Micron Technology   | 21        | 12.07%  |
| Unknown             | 7         | 4.02%   |
| A-DATA Technology   | 7         | 4.02%   |
| Kingston            | 5         | 2.87%   |
| Crucial             | 5         | 2.87%   |
| Corsair             | 5         | 2.87%   |
| Ramaxel Technology  | 4         | 2.3%    |
| Unknown (ABCD)      | 3         | 1.72%   |
| Elpida              | 3         | 1.72%   |
| Shenzhen Mic        | 2         | 1.15%   |
| G.Skill             | 2         | 1.15%   |
| V-GeN               | 1         | 0.57%   |
| Team                | 1         | 0.57%   |
| SMART Brazil        | 1         | 0.57%   |
| Sesame              | 1         | 0.57%   |
| Patriot             | 1         | 0.57%   |
| Nanya Technology    | 1         | 0.57%   |
| Kllisre             | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 6         | 3.14%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 5         | 2.62%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 4         | 2.09%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 4         | 2.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 2.09%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 2.09%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 2.09%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 4         | 2.09%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 4         | 2.09%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 1.57%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 1.57%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 3         | 1.57%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 3         | 1.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.57%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s      | 3         | 1.57%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 1.05%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.05%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 2         | 1.05%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 1.05%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s         | 2         | 1.05%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 1.05%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.05%   |
| Samsung RAM M471A5244BB0-CPB 4096MB SODIMM DDR4 2400MT/s            | 2         | 1.05%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 1.05%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 1.05%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s               | 2         | 1.05%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8192MB SODIMM DDR4 2400MT/s         | 2         | 1.05%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s              | 2         | 1.05%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s            | 2         | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.05%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 1.05%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                         | 2         | 1.05%   |
| V-GeN RAM D3R4GS16B8R 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 0.52%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 0.52%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 1         | 0.52%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2667MT/s                        | 1         | 0.52%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.52%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1333MT/s                        | 1         | 0.52%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMP351S6AFR8C-S6 4096MB SODIMM DDR2 800MT/s            | 1         | 0.52%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.52%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 1         | 0.52%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.52%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.52%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 86        | 58.11%  |
| DDR3   | 52        | 35.14%  |
| LPDDR4 | 5         | 3.38%   |
| LPDDR3 | 4         | 2.7%    |
| DDR2   | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 139       | 91.45%  |
| Row Of Chips | 9         | 5.92%   |
| Chip         | 4         | 2.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 75        | 46.88%  |
| 4096  | 53        | 33.13%  |
| 16384 | 21        | 13.13%  |
| 2048  | 9         | 5.63%   |
| 32768 | 2         | 1.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 46        | 28.93%  |
| 3200  | 39        | 24.53%  |
| 2667  | 34        | 21.38%  |
| 2400  | 15        | 9.43%   |
| 3266  | 6         | 3.77%   |
| 2133  | 5         | 3.14%   |
| 1334  | 5         | 3.14%   |
| 1867  | 3         | 1.89%   |
| 1333  | 2         | 1.26%   |
| 4267  | 1         | 0.63%   |
| 3000  | 1         | 0.63%   |
| 1067  | 1         | 0.63%   |
| 800   | 1         | 0.63%   |

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
| Chicony Electronics                    | 42        | 25.15%  |
| IMC Networks                           | 23        | 13.77%  |
| Acer                                   | 14        | 8.38%   |
| Microdia                               | 13        | 7.78%   |
| Realtek Semiconductor                  | 11        | 6.59%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5.99%   |
| Syntek                                 | 7         | 4.19%   |
| Quanta                                 | 7         | 4.19%   |
| Lite-On Technology                     | 7         | 4.19%   |
| Apple                                  | 7         | 4.19%   |
| Sunplus Innovation Technology          | 6         | 3.59%   |
| Logitech                               | 4         | 2.4%    |
| Suyin                                  | 3         | 1.8%    |
| Sonix Technology                       | 2         | 1.2%    |
| Primax Electronics                     | 2         | 1.2%    |
| Intel                                  | 2         | 1.2%    |
| Alcor Micro                            | 2         | 1.2%    |
| Silicon Motion                         | 1         | 0.6%    |
| Ricoh                                  | 1         | 0.6%    |
| MACROSILICON                           | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| 8SSC21B70095V1SR17900E1                | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 14        | 8.38%   |
| IMC Networks Integrated Camera                          | 13        | 7.78%   |
| Chicony HD Webcam                                       | 8         | 4.79%   |
| Acer Integrated Camera                                  | 7         | 4.19%   |
| Microdia Integrated_Webcam_HD                           | 6         | 3.59%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 2.99%   |
| Realtek Integrated_Webcam_HD                            | 4         | 2.4%    |
| Syntek Lenovo EasyCamera                                | 3         | 1.8%    |
| Syntek Integrated Camera                                | 3         | 1.8%    |
| Lite-On Integrated Camera                               | 3         | 1.8%    |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 1.8%    |
| Chicony EasyCamera                                      | 3         | 1.8%    |
| Apple iPhone 5/5C/5S/6/SE                               | 3         | 1.8%    |
| Acer HD Webcam                                          | 3         | 1.8%    |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.2%    |
| Sunplus HD WebCam                                       | 2         | 1.2%    |
| Sonix USB2.0 HD UVC WebCam                              | 2         | 1.2%    |
| Quanta HP TrueVision HD Camera                          | 2         | 1.2%    |
| Quanta HP HD Camera                                     | 2         | 1.2%    |
| Microdia Integrated Webcam                              | 2         | 1.2%    |
| Lite-On HP Wide Vision HD Camera                        | 2         | 1.2%    |
| Lite-On HP Webcam                                       | 2         | 1.2%    |
| Intel RealSense 3D Camera (Front F200)                  | 2         | 1.2%    |
| Chicony Lenovo Integrated Camera (0.3MP)                | 2         | 1.2%    |
| Chicony HP Webcam                                       | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.2%    |
| Acer EasyCamera                                         | 2         | 1.2%    |
| Syntek EasyCamera                                       | 1         | 0.6%    |
| Suyin Integrated_Webcam_HD                              | 1         | 0.6%    |
| Suyin HP TrueVision HD Integrated Webcam                | 1         | 0.6%    |
| Suyin HP TrueVision HD                                  | 1         | 0.6%    |
| Sunplus FHD Camera Microphone                           | 1         | 0.6%    |
| Sunplus Asus Webcam                                     | 1         | 0.6%    |
| Silicon Motion Web Camera                               | 1         | 0.6%    |
| Ricoh HD Webcam                                         | 1         | 0.6%    |
| Realtek USB2.0 HD UVC WebCam                            | 1         | 0.6%    |
| Realtek USB HD Webcam                                   | 1         | 0.6%    |
| Realtek MTD Camera                                      | 1         | 0.6%    |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 0.6%    |
| Realtek Integrated Webcam_HD                            | 1         | 0.6%    |
| Realtek Integrated Webcam                               | 1         | 0.6%    |
| Realtek EasyCamera                                      | 1         | 0.6%    |
| Quanta VGA WebCam                                       | 1         | 0.6%    |
| Quanta USB2.0 HD UVC WebCam                             | 1         | 0.6%    |
| Quanta HD Webcam                                        | 1         | 0.6%    |
| Primax HP HD Webcam [Fixed]                             | 1         | 0.6%    |
| Primax Dell Laptop Integrated Webcam 2Mpix              | 1         | 0.6%    |
| Microdia USB 2.0 Camera                                 | 1         | 0.6%    |
| Microdia Laptop_Integrated_Webcam_FHD                   | 1         | 0.6%    |
| Microdia Integrated Webcam HD                           | 1         | 0.6%    |
| Microdia HP Integrated Webcam                           | 1         | 0.6%    |
| Microdia Dell Integrated HD Webcam                      | 1         | 0.6%    |
| MACROSILICON USB Video                                  | 1         | 0.6%    |
| Logitech Webcam C170                                    | 1         | 0.6%    |
| Logitech HD Pro Webcam C920                             | 1         | 0.6%    |
| Logitech C505 HD Webcam                                 | 1         | 0.6%    |
| Logitech B525 HD Webcam                                 | 1         | 0.6%    |
| Lenovo FULL HD 1080P Webcam                             | 1         | 0.6%    |
| IMC Networks XiaoMi Webcam                              | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 39.47%  |
| Validity Sensors           | 13        | 34.21%  |
| Shenzhen Goodix Technology | 7         | 18.42%  |
| LighTuning Technology      | 2         | 5.26%   |
| Upek                       | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 6         | 15.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 13.16%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 10.53%  |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 10.53%  |
| Validity Sensors Synaptics WBDI                                            | 3         | 7.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 7.89%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.63%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.63%   |
| Validity Sensors VFS491                                                    | 1         | 2.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.63%   |
| Synaptics  WBDI                                                            | 1         | 2.63%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 58.82%  |
| Alcor Micro | 6         | 35.29%  |
| Lenovo      | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 27.78%  |
| Broadcom 58200                                                               | 3         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 11.11%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.56%   |
| Broadcom 5880                                                                | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 105       | 51.98%  |
| 1     | 76        | 37.62%  |
| 2     | 21        | 10.4%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 33.93%  |
| Net/ethernet             | 22        | 19.64%  |
| Chipcard                 | 15        | 13.39%  |
| Multimedia controller    | 13        | 11.61%  |
| Graphics card            | 9         | 8.04%   |
| Net/wireless             | 7         | 6.25%   |
| Bluetooth                | 4         | 3.57%   |
| Storage                  | 1         | 0.89%   |
| Modem                    | 1         | 0.89%   |
| Communication controller | 1         | 0.89%   |
| Camera                   | 1         | 0.89%   |

